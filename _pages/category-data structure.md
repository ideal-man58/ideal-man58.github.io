---
title: "data structure"
layout: archive
permalink: /data structure
author_profile: true
sidebar:
    nav: "sidebar-category"
---
{% assign posts = site.categories.data structure %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}