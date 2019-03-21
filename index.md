---
layout: default
---

<div class="search-results">
{% if site.posts.size == 0 %}
  <h2>No posts found</h2>
{% else %}
  <ul class="list--unstyled">
    {% for post in site.posts %}
      <li class="search-results__result">
        <div class="dataset-summary">
          <h2 class="dataset-summary-title">
            <a href="{{ post.url }}">{{ post.title }}</a>
          </h2>
          <div class="dataset-summary-meta">
            <div class="dataset-summary-updated">
              <time>{{ post.date | date_to_string }}</time>
            </div>
          </div>
        </div>
      </li>
    {% endfor %}
  </ul>
{% endif %}
</div>
