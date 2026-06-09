---
layout: page
title: extra
permalink: /extra/
description: A collection of projects, ideas and blog posts
nav: true
nav_order: 5
---

{% assign extra_items = site.extra | sort: 'date' | reverse %}

{% for item in extra_items %}
  {% include item.liquid %}
{% endfor %}
