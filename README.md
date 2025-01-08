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


