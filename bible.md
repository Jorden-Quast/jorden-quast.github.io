---
layout: page
title: Bible Notes
permalink: /bible
---

Welcome to the Bible page! I try my best to study the Bible, and sometimes, I might write something down and possibly upload it here. I'm not an
expert, or really even have any idea what's going on, I'm just doing my best to see what God is telling me. If you find them useful in any way, thank
God, I definitely don't have enough understanding to take credit for it. If you think I'm wrong about something or I've got something confused or
you've got feedback, please email me at <a class="u-email" href="mailto:{{site.email}}">{{ site.email }}</a>, I'd love to hear from you, because if
iron doesn't sharpen iron, we'll all end up pretty dull... which isn't ideal.

{%assign biblePosts = site.posts | where: "category", "bible" %}

{% include prettyPostList.html posts=biblePosts %}
