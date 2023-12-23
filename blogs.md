---
layout: page
title: Blogs
permalink: /blogs
---

Welcome to the blogs portion of the site. I might write things... I might not, who knows how long it'll be before I write something new down.
Everything here are just my musings about life, so I have no idea what's going to be here... This will be whatever.

{% assign blogPosts = site.posts | where: "category", "blogs" %}

{% include prettyPostList.html posts=blogPosts %}
