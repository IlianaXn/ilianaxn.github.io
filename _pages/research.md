---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

<!-- <style> -->
<!-- iframe { -->
<!--   height: 100%; -->
<!--   width: 175px !important; -->
<!--   display: inline; -->
<!--   vertical-align:middle; -->
<!--   margin:0px !important; -->
<!--   padding:0px !important; -->
<!--   width: 175px; -->
<!--   display: inline; -->
<!--   vertical-align:middle; -->
<!--   border: 1px solid red; -->
<!-- } -->
<!-- .col-md-3 { -->
<!--   margin:0px !important; -->
<!--   padding:0px !important; -->
<!--   overflow:hidden; -->
<!--   display: table-cell; -->
<!--   text-align:center; -->
<!--   background: white; -->
<!--   width: 175px; -->
<!--   border: 0px solid transparent; -->
<!--   border-radius:20px; -->
<!-- } -->
<!-- </style> -->

<style>
img{
  border-radius: 10px;
}
.col-md-3 {
  margin-top:10px;
  margin-bottom:10px;
  padding:0px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  background: white;
  border-radius: 20px;
  height: auto;
  <!-- border: 1px solid black; -->
}
iframe {
  margin:0;
  padding:0;
  width: 175px;
  display: inline;
  vertical-align: middle;
}
</style>

  <!-- border: 5px solid red; -->
  <!-- margin-bottom:5px; -->
  <!-- margin-left:5px; -->
  <!-- float: none; -->

## Research

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4>Misinformation containment in social network platforms</h4>
 <a href="{{ site.url }}{{ site.baseurl }}/papers/thesis_xygkou_iliana.pdf" target="_blank">Diploma Thesis (in Greek)</a> <br/>
 <a href="{{ site.url }}{{ site.baseurl }}/presentations/thesis.pdf" target="_blank">Presentation</a>
<p align="justify">In my thesis I studied the problem of Cautious Misinformation Minimization (CMM) which is defined as minimizing the spread of false information while minimizing the decrement of the spread of true information by limiting the interactions between the users, i.e., by removing a limited number of edges in the graph representing the network. The known Independent Cascade (IC) and Deterministic Linear Threshold (DLT) models are modified in this Thesis, in order to take into account the user's specialization in the thematic category to which the disseminated information belongs. Under these models as well as the probabilistic Linear Threshold model (LT), the CMM problem is proved to be NP-Hard. Thus, to solve it under the LT and DLT models, greedy iterative algorithms are employed whose criterion for selecting the edge to be removed in each iteration is the maximum reduction of the sum of the difference between true information's current spread and its initial one, and false information's current spread.
</p>
<p align="justify">
The experimental evaluation of the proposed algorithms is carried out using real social networks. Their results are compared with the ones of the methods that utilize mainly topological features and partly the dynamic evolution of information dissemination. Based on these, the superiority of the proposed methods is highlighted since they achieve through the removal of a small number of edges the significant reduction of the spread of misinformation without greatly affecting the dissemination of true information.
</p>
 <h4>A survey on the Minimum Linear Arrangement problem</h4>
 <a href="{{ site.url }}{{ site.baseurl }}/papers/mla_survey.pdf" target="_blank">Paper Draft</a><br/>
 <a href="{{ site.url }}{{ site.baseurl }}/presentations/mla_presentation.pdf" target="_blank">Presentation</a>
<p align="justify">The Minimum Linear Arrangement problem has
been proven to be NP-complete for arbitrary graphs. However,
it can be simplified by specifying the type of graph. There have
been found efficient algorithms by applying restrictions to the
input or the output, and there exist approximation techniques
trying to achieve the optimal.
</p>
</div>
</div>
</div>
