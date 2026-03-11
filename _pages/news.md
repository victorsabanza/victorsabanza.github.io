---
title: "News"
layout: archive
permalink: /news/
author_profile: true
---

{% include base_path %}

{% for post in site.news reversed %}
{% include archive-single.html %}
{% endfor %}
