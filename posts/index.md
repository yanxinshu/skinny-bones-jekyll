---
layout: archive
title: "学习笔记"
date: 
modified:
excerpt: ""
tags: []
image: 
---

以下是我的学习笔记

<br/>[RWD学习笔记](https://yanxinshu.github.io/posts/rwd)
<div class="tiles">
{% for post in site.categories.rwd %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 rwd 的列出来-->


<br/>
<br>[Tableau学习笔记](https://yanxinshu.github.io/posts/infovis-notes)
<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis-notes 的列出来-->
