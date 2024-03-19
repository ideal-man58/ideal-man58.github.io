---
title: "data structure"
layout: archive
permalink: /data_structure
author_profile: true
sidebar:
    nav: "sidebar-category"
---
{% assign posts = site.categories.data_structure %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}