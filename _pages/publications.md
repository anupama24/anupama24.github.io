---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<ul>
<li> <a href="https://papers.nips.cc/paper/2020/hash/1ee942c6b182d0f041a2312947385b23-Abstract.html"> Learning from mixtures of private and public populations. </a> </br>
  Raef Bassily, Shay Moran, and <b>Anupama Nandi</b>. </br>
In the <i>34th Conference on Neural Information Processing Systems (NeurIPS 2020).</i> 
</li>
 
</ul>


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=b6L2F7cAAAAJ&hl=en}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

