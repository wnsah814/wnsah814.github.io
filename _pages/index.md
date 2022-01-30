---
layout: defaults/page
permalink: index.html
narrow: true
title: Welcome to Junmo's Blog
---

## What is it?

{% include components/intro.md %}

<hr />

### Recent Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}


