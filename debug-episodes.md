---
layout: default
title: "Debug: Episode List"
permalink: /debug-episodes/
---

# Debug: Episode List

Below is a list of all detected episodes in the `_episodes` collection.

{% assign episodes = site.episodes | sort: "date" | reverse %}
<ul>
  {% for episode in episodes %}
    <li>
      <a href="{{ site.baseurl }}{{ episode.url }}">{{ episode.title }}</a>
      — {{ episode.date | date: "%B %d, %Y" }}
    </li>
  {% else %}
    <li>No episodes were detected. 😢</li>
  {% endfor %}
</ul>

<hr>
<p><strong>Base URL:</strong> {{ site.baseurl }}</p>
<p><strong>Site URL:</strong> {{ site.url }}</p>
