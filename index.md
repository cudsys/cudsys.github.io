---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Hailey's Soapbox
---
## Hi there!
Welcome to my website/blog! I don't know exactly what to put on this homepage yet, but go check out these posts:
## Latest posts
<!-- jekyll, 3 latest posts but in markdown -->
{% for post in site.posts limit:10 %}
<a href="{{ post.url }}">**{{ post.title }}**</a> *{{ post.date | date_to_string }}*
{% endfor %}