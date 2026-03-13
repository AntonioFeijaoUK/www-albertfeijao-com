---
title: Albert Feijao Stories
layout: default
---

Welcome to **Albert Feijao stories**.

This website shares imaginative stories written in Markdown and published with GitHub Pages.

All stories are published under **Creative Commons Attribution 4.0 International (CC BY 4.0)**.  
You may copy, share, and adapt them, but you must credit the original author and link back to the original story page.

---

## Stories

<div class="story-grid">
  {% assign sorted_stories = site.stories | sort: "date" | reverse %}
  {% for story in sorted_stories %}
    {% include story-card.html story=story %}
  {% endfor %}
</div>

---

## About This Site

These stories are shared publicly so that others can enjoy, reuse, and build on them with proper attribution.

## Licence

Unless stated otherwise, all stories on this site are licensed under:

**Creative Commons Attribution 4.0 International (CC BY 4.0)**

> Story by Albert Feijao, originally published at https://www.albertfeijao.com, licensed under CC BY 4.0.
