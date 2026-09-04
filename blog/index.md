---
title: News
nav:
  order: 5
  tooltip: News and updates
---

# {% include icon.html icon="fa-solid fa-newspaper" %} News

Latest news from the Macrophages & Cancer team: publications, awards, conferences, events, and life in the lab.

{% include section.html %}

{% include search-box.html %}

{% include tags.html tags=site.tags %}

{% include search-info.html %}

<div class="news-grid">
  {% for post in site.posts %}
    {% include post-excerpt.html
      lookup=post.slug
    %}
  {% endfor %}
</div>