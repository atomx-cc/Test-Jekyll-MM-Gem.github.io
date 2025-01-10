# Minimal Mistakes Gem-based method

project name: Test-Jekyll-MM-Gem-based.github.io  

quote from: https://github.com/mmistakes/minimal-mistakes

# start jekyll site local

start virtual environment: ```source ~/Github/venv/bin/activate```

```bundle exec jekyll clean``

unique port number: ```bundle exec jekyll serve --port 4003 ```


# Custom function
- option 1, use the theme's provided customization hooks. 
 
add special functions to site without overriding the default layout.

Create the _includes/head/custom.html File, Add Your Configuration and Script

- option 2, change layout default.

create _includes/mathjax.html, mathjax scripture is the same as above option 1, and add ```{% include mathjax.html %}``` to head or body tag in _layouts/default.html.


## MathJax
mathematical equations on webpages. As mentioned earlier, it uses JavaScript to beautifully display LaTeX, MathML, and AsciiMath notation.


# Debug
When I set all layout as default in ./_config.yml, then I lose all margins and title on every page.

## Why Does Setting layout: single in _config.yml Restore Margins and Titles?

In the Minimal Mistakes Jekyll theme, different layouts provide different structures and styling for your pages and posts. 

The single layout is designed for detailed content pages like blog posts and includes all the necessary components such as sidebars, headers, footers, margins, and titles. 

On the other hand, the default layout is a more basic structure meant to be extended by other layouts and might lack some of these components.


## why merge failed?
```git checkout main```
```git merge theme```

I tried to update from theme to main branch for many times, something wired happened. 

<!--
// in theme branch, we can see  3 dirs（ assets，_data, _includes）and mathjax.html were updated.

 % git show --stat 272c0a50bb44
commit 272c0a50bb (HEAD -> theme)
Author: Atomx3 
Date:   Fri Jan 10 14:57:03 2025 +0100

    theme 7

 _data/navigation.yml                             |    10 +
 _data/ui-text.yml                                |  2185 +++++
 _includes/head/custom.html                       |    23 +
 assets/css/main.scss                             |     9 +              
 +++++++++++++++++++++
 mathjax.html                                     |    19 +
 20 files changed, 20993 insertions(+)


// except 3 dirs（ assets，_data, _includes）, the other file such as mathjax could be updated to branch main from theme, why?

// in main branch
% git log
commit caffc813eb9 (HEAD -> main)
Merge: 4e53757 272c0a5
Author: Atomx3 
Date:   Fri Jan 10 14:57:19 2025 +0100

    add 78


% git show --stat caffc813eb9
commit caffc813eb98e (HEAD -> main)
Merge: 4e53757 272c0a5
Author: Atomx3 
Date:   Fri Jan 10 14:57:19 2025 +0100

    add 78

 mathjax.html | 19 +++++++++++++++++++
 1 file changed, 19 insertions(+)


% git show --stat 272c0a50bb44c
commit 272c0a50bb44 (theme)
Author: Atomx3 
Date:   Fri Jan 10 14:57:03 2025 +0100

    theme 7

 _data/navigation.yml                             |    10 +
 _data/ui-text.yml                                |  2185 +++++
 _includes/head/custom.html                       |    23 +
 assets/css/main.scss                             |     9 +

-->