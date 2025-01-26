---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: main
title: "หน้าแรก"
permalink: /
---
{% assign lang = page.lang | default: site.default_lang %}
{% include components/home/content.html %}
