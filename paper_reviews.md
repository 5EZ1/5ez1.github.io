---
layout: page
title: Paper Reviews
permalink: /paper-reviews/
nav_order: 7
---

# Paper Reviews

Here you can find my reviews and interpretations of various academic papers in the fields of machine learning, deep learning, and data science.

{% assign sorted_reviews = site.paper_reviews | sort: 'date' | reverse %}

<ul class="post-list">
  {% for review in sorted_reviews %}
    <li>
      <span class="post-meta">{{ review.date | date: "%b %-d, %Y" }}</span>
      <h3>
        <a class="post-link" href="{{ review.url | relative_url }}">
          {{ review.title | escape }}
        </a>
      </h3>
      {% if review.description %}
        <p class="post-description">{{ review.description | escape }}</p>
      {% endif %}
    </li>
  {% endfor %}
</ul>