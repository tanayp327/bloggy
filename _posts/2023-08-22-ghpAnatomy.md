---
toc: true
comments: true
layout: post
title: Anatomy of GitHub Pages Blog
---

## Terms and files

- README.md is what contains a description of the project, it also has instructions and necessary information
- _notebooks has all of the notebook files that can contian both markdown and code cells. all these notebooks files are dependent on jekyll to convert them into HTML
- _posts: Directory holding Markdown (.md) files containing content for the website
- index.md contains all the content for the project's home page
- _data has repository for data files
- images contain all the images that are used in the _posts or _notebooks directories
- config.yml contains the key-value pairs that Jekyll needs to build the website
- .gitignore specifies exclusions from version control