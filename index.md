---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Hailey's Soapbox
---
<head>
<meta property="og:title" content="Hailey's Soapbox" />
<meta property="og:type" content="website" />
<meta property="og:url" content="https://cudsys.github.io" />
<meta property="og:image" content="https://cudsys.github.io/assets/img/hailey.png" />
<meta property="og:description" content="my very own website/blog! :D" />
<meta name="theme-color" content="#00FFFF">
</head>

## Hi there!
Welcome to my website/blog! I don't know exactly what to put on this homepage yet, but go check out these posts:
## Latest posts
<!-- jekyll, 3 latest posts but in markdown -->
{% for post in site.posts limit:10 %}
<a href="{{ post.url }}">**{{ post.title }}**</a> *{{ post.date | date_to_string }}*
{% endfor %}

## Status
<div id="statuscafe"><div id="statuscafe-username"></div><div id="statuscafe-content"></div></div><script src="https://status.cafe/current-status.js?name=cudsys" defer></script>

> Source: [status.cafe](https://status.cafe/users/cudsys)