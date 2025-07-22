---
layout: default
title: Rambling Bramble Podcast
---

<h1>{{ site.title }}</h1>
<p>{{ site.description }}</p>

<section>
  <h2>Episodes</h2>
  {% include episode-list.html %}
</section>

<section>
  <h3>RSS Feed Link</h3>
  {% include feed.xml %}
</section>
