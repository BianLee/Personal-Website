---
---

<br/>
<h2>Music</h2>
{% for post in site.posts %}
{% if post.tags contains "music" %}
{% include posts-list-item.html %}
{% endif %}
{% endfor %}
<br/>
<h2>Web3 & DeFi</h2>
{% for post in site.posts %}
{% if post.tags contains "finance" %}
{% include posts-list-item.html %}
{% endif %}
{% endfor %}
