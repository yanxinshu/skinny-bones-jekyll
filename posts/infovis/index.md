<div class="tiles">
{% for post in site.categories.posts/infovis %}
  {% include post-grid.html %}
{% endfor %}
</div>
