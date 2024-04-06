---
---

<!--

<h2>Personal</h2>
{% for post in site.posts %}
{% if post.tags contains "personal" %}
{% include posts-list-item.html %}
{% endif %}
{% endfor %}
-->
<h2>Policy</h2>
{% for post in site.posts %}
{% if post.tags contains "policy" %}
{% include posts-list-item.html %}
{% endif %}
{% endfor %}

<h2>Music</h2>
{% for post in site.posts %}
{% if post.tags contains "music" %}
{% include posts-list-item.html %}
{% endif %}
{% endfor %}

<h2>Web3 & DeFi</h2>
{% for post in site.posts %}
{% if post.tags contains "finance" %}
{% include posts-list-item.html %}
{% endif %}
{% endfor %}
