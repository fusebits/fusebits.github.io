---
title: Welcome to FuseBits!
keywords: homepage
tags: [getting_started]
sidebar: mydoc_sidebar
permalink: index.html

---

## What we do

At FuseBits we make really cool electronics and help other people make their products and projects. If you have a board to be assembled, firmware to be written, or enclosure designed, we can help. 



### 1. Build the Theme (*with* the github-pages gem) {#option2}

If you *are* in fact publishing on Github Pages, leave the Gemfile and Gemfile.lock files in the theme.The Gemfile tells Jekyll to use the github-pages gem. **However, note that you cannot use the normal `jekyll serve` command with this gem due to dependency conflicts between the latest version of Jekyll and Github Pages** (which are noted [briefly here](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/)).

You need Bundler to resolve these dependency conflicts. Use Bundler to install all the needed Ruby gems:

```
bundle update
```

Then *always* use this command to build Jekyll:

```
bundle exec jekyll serve
```

If you want to shorten this long command, you can put this code in a file such as jekyll.sh (on a Mac) and then simply type `. jekyll.sh` to build Jekyll.

