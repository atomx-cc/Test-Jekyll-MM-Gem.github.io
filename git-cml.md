# Git Branch Management Commands and Notes

Project name: Test-Jekyll-MM-Gem-based.github.io

Quoted from: [https://github.com/mmistakes/minimal-mistakes](https://github.com/mmistakes/minimal-mistakes)

---

## Overview

This Jekyll project uses a branch management strategy that separates concerns into dedicated branches:

- **`theme` Branch**: Contains theme-related files (layouts, includes, assets, etc.).
- **`posts` Branch**: Contains content-related files (posts, pages, etc.).
- **`main` Branch**: The primary branch for merging and running the project.

---

## Branch Creation and Management

```bash:commands.sh
# Create and switch to the 'theme' branch
git checkout -b theme

# Remove content directories from the 'theme' branch
git rm -r _posts _pages README.md
git commit -m "Remove content directories from theme branch"

# Merge .gitignore from main into theme
git merge main -- .gitignore
git commit -m "Update .gitignore in theme branch"


# Switch back to the main branch
git checkout main

# Create and switch to the 'posts' branch
git checkout -b posts

# Remove theme directories from the 'posts' branch
git rm -r _layouts _includes assets Gemfile Gemfile.lock index.html
git commit -m "Remove theme directories from posts branch"

# Merge .gitignore from main into posts
git merge main -- .gitignore
git commit -m "Update .gitignore in posts branch"


# Switch to the 'main' branch
git checkout main

# Merge the 'theme' branch into 'main'
git merge theme
# Resolve any conflicts, then stage and commit
git add .
git commit -m "Merge theme branch into main"

# Merge the 'posts' branch into 'main'
git merge posts
# Resolve any conflicts, then stage and commit
git add .
git commit -m "Merge posts branch into main"

# Push the 'main' branch to the remote repository named 'origin'
git push origin main


# Clean up generated directories and update .gitignore

# Switch to the 'posts' branch
git checkout posts
rm -rf _site/ .sass-cache/ .jekyll-cache/
git add .gitignore
git commit -m "Add .gitignore to posts branch"

# Switch to the 'theme' branch
git checkout theme
rm -rf _site/ .sass-cache/ .jekyll-cache/
git add .gitignore
git commit -m "Add .gitignore to theme branch"

# Ensure .gitignore consistency across all branches
git checkout theme
git merge main -- .gitignore
git commit -m "Update .gitignore in theme branch"

git checkout posts
git merge main -- .gitignore
git commit -m "Update .gitignore in posts branch"


# Check repository status, including ignored files
git status --ignored

# Remove generated directories from git tracking (if necessary)
git rm -r --cached _site .sass-cache .jekyll-cache
git commit -m "Remove generated directories from Git tracking"

# Verify ignored status
git status --ignored

# Only execute the following commands in the 'main' branch
jekyll build
jekyll serve