---
layout: post
author: ath
---

TLDR; How I built my portfolio/blog using Jekyll.

### The problem starts

I successfully installed Jekyll, with some hiccup in installing ruby using chruby on my Mac. I used rbnev instead and it works. 

I mainly referred to the docs on [GitHub](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll) and [Jekyll](https://jekyllrb.com/docs/installation/). [Stackoverflow](https://stackoverflow.com) is a great help in solving the small hiccups, as always.

I managed to create a site and publish it on my GitHub Pages, but once I tried changing the theme using remote_theme and plugins, the changes wouldn't appear on my site. 

I couldn't figure it out. 

In the end, I forked one of the themes from [Jamstack Themes](https://jamstackthemes.dev/ssg/jekyll/) (they have a few cool ones) and customized from there.

### Hacked Jekyll

Hacked-jekyll is a "microtheme that looks like JSON". 

I loved the coder/hacker theme and used it as a homepage. I expanded it by adding a photo gallery, a draggable navigation bar (idea inspired by draggable posts on [Anon](http://anon.com.hk)), and a blog page. 

The outcome: <https://github.com/nadath/hacking-jekyll>, thanks to the following references.
1. [A simple image gallery in Jekyll without plugins](https://dmnfarrell.github.io/software/jekyll-galleries)
2. [Create a Draggable HTML Element](https://www.w3schools.com/howto/howto_js_draggable.asp)

I'm thinking up something cool/weird to customize the blog page further. Let's see how it'd go.

Till then.