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
<h2>Writing</h2>
<ul>
  {% for post in site.posts %}
    {% if post.tags contains "policy" %}
      <li style="font-size:1.1rem;"><a href="{{ post.url }}" style="color: black;">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>




<!--
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
 -->
