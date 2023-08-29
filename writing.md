---
---

<h3>Finance</h3>
{% for post in site.posts %}
{% if post.tags contains "finance" %}
{% include posts-list-item.html %}
{% endif %}
{% endfor %}

<h3>Music</h3>
{% for post in site.posts %}
{% if post.tags contains "music" %}
{% include posts-list-item.html %}
{% endif %}
{% endfor %}
