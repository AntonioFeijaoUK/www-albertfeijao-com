---
title: Stories
layout: default
permalink: /stories/
---

## All Stories

<div class="story-grid">
  {% assign sorted_stories = site.stories | sort: "date" | reverse %}
  {% for story in sorted_stories %}
    {% include story-card.html story=story %}
  {% endfor %}
</div>
