---
layout: post
title:  "Learning about Jekyll"
date:   2016-05-01 09:42:00 -0400
categories: jekyll learning
tags: prehistory
---
This is my first experience with [Jekyll](http://jekyllrb.com/). So far, I've noticed:

1. Jekyll is a static website. Unless Javascript is utilized, there is no feedback or functional capabilities other than straight up text presentation.
2. The Jekyll tool has no inherent capabilities for generating a post a priori. You have to open a file with the correct filename format, with the right [YAML front matter](http://assemble.io/docs/YAML-front-matter.html).
3. Jekyll does provide customization in the form of Liquid templates, SCSS for look and feel, and a Ruby plugin framework that all work together to produce the site.
4. It appears that GitHub does the generation for you on their side, as I've pushed pages without building and yet Github picks up on it without issue.

Things I will have to do to improve my flow in posting:

1. Automatic page generation. This will be a simple BASH/Ruby/Go code that will allow for quick startup for posts.
2. Customization of the page... right now it's nothing great to look at.
3. Picking of a nicer URL (for now it's ironhandedlayman.github.io, which is a handful). 
4. I have personal and professional GitHub accounts. I'd also like to use this on my professional account as an internal blog, but am not sure how to set the access control to have it only visible to people in the organization.

