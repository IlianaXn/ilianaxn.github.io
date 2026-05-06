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
<h4>MORP4: A Dynamic Network Telescope</h4>
 <h5>I. Xygkou, J.K. Sojan, D. Rauthan, F. Zhu, T. Holterbach, S. Alcock, B. Flanagan, A. Saeed, A. Dainotti</h5>
 <a href="{{ site.url }}{{ site.baseurl }}/papers/morp4_dynamic_telescope.pdf" target="_blank">Paper</a><br/>
 <a href="https://www.usenix.org/conference/nsdi26/presentation/xygkou">Paper (online)</a><br/>
 <a href="{{ site.url }}{{ site.baseurl }}/presentations/nsdi-morp4-presentation.pdf" target="_blank">Presentation</a><br/>
<p align="justify">A network telescope passively monitors traffic reaching Internet address space that is not assigned to any hosts but is advertised to the global routing system. This traffic is by definition unsolicited. For more than two decades, network telescopes have enabled research breakthroughs by allowing global visibility into a wide range of Internet phenomena. However, telescopes are afflicted by two main issues: progressive erosion, due to the increasing scarcity and commercial value of address space, and blacklisting. To overcome these issues, we propose MORP4, a programmable data-plane framework implementing a “dynamic” network telescope. MORP4 accurately and adaptively tracks unused space of an organization’s network with configurable time and space granularity and captures only traffic directed towards unused addresses at line rate. We provide an implementation in P4 and Python/C++, and deploy it on a Tofino switch. We show that it can detect unused IPv4 address space at the finest granularity (/32) while operating at line rate as well as providing an effective approach for operating a telescope in the IPv6 domain.
</p>
 <h4>A First Look into Long-lived BGP Zombies</h4>
 <h5>I. Xygkou, A. Chariton, X. Dimitropoulos, A. Dainotti</h5>
 <a href="{{ site.url }}{{ site.baseurl }}/papers/imc-zombies.pdf" target="_blank">Paper</a><br/>
 <a href="https://dl.acm.org/doi/abs/10.1145/3730567.3764469">Paper (online)</a><br/>
 <a href="{{ site.url }}{{ site.baseurl }}/presentations/BGPZombies-IMC2025.pdf" target="_blank">Presentation</a><br/>
<p align="justify">BGP is the de facto protocol used to manage a network’s reachabilityon the Internet. Network operators announce and withdraw theirprefixes on BGP to enable or to prevent communication towardstheir origin network, respectively. However, the withdrawal of aprefix could fail to propagate totally in the Internet and routestowards withdrawn prefixes could remain in the routing tablesof routers. These routes are called stuck or zombie BGP routes,and their persistence can lead to performance degradation, or evenpartial or complete outage. In this paper, we first revisit existingwork on BGP zombies using RIPE RIS beacons, identify the double-counting discrepancy, and revise the methodology to address thisproblem and detect zombies more accurately. Second, we point outlimitations of the RIPE RIS beacons with respect to their periodicity,lack of diversity, and noise, and introduce and deploy our ownbeacons, which address these limitations. Using our beacons andthe revised methodology, we analyze the lifespan of BGP zombies.We show that zombie routes can persist in RIBs for days, weeks,or even months. Furthermore, we document that BGP zombies canbe announced months after their original withdrawal, affectingnew ASes. Finally, we discuss interesting cases of long-lived zombieoutbreaks that affected large ISPs with hundreds of ASes in theircustomer cones.
</p>
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
