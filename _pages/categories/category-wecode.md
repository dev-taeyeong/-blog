---
title: 'Wecode'
layout: archive
permalink: categories/wecode
author_profile: true
sidebar_main: true
---

{% assign posts = site.categories.Wecode %}<hr />
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} <hr />{% endfor %}