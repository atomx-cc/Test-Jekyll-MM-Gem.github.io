# Git 分支管理命令和注释

project name: Test-Jekyll-MM-Gem-based.github.io  

quote from: https://github.com/mmistakes/minimal-mistakes

以本Jekyll项目为例，设计一种更好的管理方式，将程序文件放到theme分支，日志文件放到posts分支，主分支main用于合并其他分支并运行程序。


# 1. 创建并切换到 theme 分支
git checkout -b theme

# 返回到 main 分支并创建 posts 分支
git checkout main
git checkout -b posts

# 2. 在 theme 分支中删除内容目录
git checkout theme
git rm -r _posts _pages README.md
git commit -m "从 theme 分支中删除内容目录"

# 确保 .gitignore 文件在 theme 分支中包含忽略规则
git merge main -- .gitignore
git commit -m "更新 theme 分支中的 .gitignore 文件"

# 3. 在 posts 分支中删除主题目录
git checkout posts
git rm -r _layouts _includes assets Gemfile Gemfile.lock index.html
git commit -m "从 posts 分支中删除主题目录"

# 确保 .gitignore 文件在 posts 分支中包含忽略规则
git merge main -- .gitignore
git commit -m "更新 posts 分支中的 .gitignore 文件"

# 4. 切换到 main 分支并合并 theme 和 posts 分支
git checkout main

# 合并 theme 分支
git merge theme
# 如果有冲突，解决冲突后提交
git add .
git commit -m "将 theme 分支合并到 main"

# 合并 posts 分支
git merge posts
# 如果有冲突，解决冲突后提交
git add .
git commit -m "将 posts 分支合并到 main"

# 5. 推送 main 分支到远程仓库
git push origin main

# 6. 在 posts 和 theme 分支中删除 Jekyll 生成的目录
# 切换到 posts 分支
git checkout posts
rm -rf _site/ .sass-cache/ .jekyll-cache/
# 添加 .gitignore 文件到 Git 以确保忽略规则生效
git add .gitignore
git commit -m "在 posts 分支中添加 .gitignore 文件"

# 切换到 theme 分支
git checkout theme
rm -rf _site/ .sass-cache/ .jekyll-cache/
# 添加 .gitignore 文件到 Git
git add .gitignore
git commit -m "在 theme 分支中添加 .gitignore 文件"

# 7. 确保 .gitignore 文件在所有分支中一致
# 从 main 分支合并 .gitignore 到 theme 分支
git checkout theme
git merge main -- .gitignore
git commit -m "更新 theme 分支中的 .gitignore 文件"

# 从 main 分支合并 .gitignore 到 posts 分支
git checkout posts
git merge main -- .gitignore
git commit -m "更新 posts 分支中的 .gitignore 文件"

# 8. 查看仓库状态，包含被忽略的文件
git status --ignored

# 9. 从 Git 跟踪中移除被忽略的文件（如必要）
git rm -r --cached _site .sass-cache .jekyll-cache (除了日志之外的其他全部程序文件)
git commit -m "从 Git 跟踪中移除生成的目录"

# 10. 验证目录已被忽略
git status --ignored

# 11. 避免在非 main 分支中运行 Jekyll 构建命令
# 仅在 main 分支中执行以下命令
jekyll build
jekyll serve

# 12. 列出所有分支
git branch

