---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<ul>
  
<li> <a href="http://proceedings.mlr.press/v134/bassily21a/bassily21a.pdf"> Non-euclidean  differentially  private  stochastic  convex optimization. </a> <br>
  Raef Bassily, Crist&ograve;bal Guzm&agrave;n, and <b>Anupama Nandi</b>. <br>
In the <i>34th Annual Conference on Learning Theory (COLT 2021)</i>
</li>

<li> <a href="https://papers.nips.cc/paper/2020/hash/1ee942c6b182d0f041a2312947385b23-Abstract.html"> Learning from mixtures of private and public populations. </a> <br>
  Raef Bassily, Shay Moran, and <b>Anupama Nandi</b>. <br>
In the <i>34th Conference on Neural Information Processing Systems (NeurIPS 2020).</i> 
</li>

<li> <a href="http://proceedings.mlr.press/v117/nandi20a.html"> Privately answering classification queries in the agnostic PAC model. </a> <br>
  Raef Bassily, and <b>Anupama Nandi</b>. <br>
In the  <i>31st International Conference on Algorithmic Learning Theory, (ALT 2020).</i>
</li>
 
 <li> <a href="https://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/viewFile/14756/14326"> Heavy-tailed analogues of the covariancematrix for ICA. </a> <br>
  Joseph Anderson, Navin Goyal, <b>Anupama Nandi</b>, and Luis Rademacher. <br>
In the <i>31st Conference on Association on Artificial Intelligence, (AAAI-2017).</i>'
</li>
 
<li> <a href="https://arxiv.org/abs/1509.00727"> Heavy-tailed independent component analysis. </a> <br>
  Joseph Anderson, Navin Goyal, <b>Anupama Nandi</b>, and Luis Rademacher. <br>
In the <i> 56th Annual Symposium on Foundations of Computer Science (FOCS 2015).</i>
</li>
</ul>


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=b6L2F7cAAAAJ&hl=en}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

