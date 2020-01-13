---
layout: defaults/page
permalink: index.html
narrow: true
---

{% include components/intro.md %}

### Research Interests
My research interests lie broadly in the fields of <b>storage systems</b>, <b>cloud computing</b> and <b>big data analytics</b>. Currently, my research is focused on storage-related topics including <i><b>caching systems</b></i>, <i><b>erasure coding</b></i> and <i><b>distributed storage systems</b></i>.

<!--Currently, I am working on designing and building cache architectures for object storage systems in datacenters, and exploring the performance characteristic of erasure-coded storage systems.
-->

<div class="card card-post w-100 border-top-0 border-left-0 border-right-0 rounded-0 mb-4">
</div>

### Current Projects

<div class="card card-post w-100 border-top-0 border-left-0 border-right-0 rounded-0 mb-4">

<h4>D3N: A multi-layer cache for improving big-data applications performance</h4>
<ul>
  <li>D3N is a throughput-oriented multi-layer caching architecture that mitigates network imbalances
by caching data on the access side of each layer of a hierarchical network topology. The prototype
of D3N, which incorporates a two-layer cache has been implemented as a modification to Red Hat
Ceph Storages RADOS Gateway in the Massachusetts Open Cloud datacenter. To fully utilize
bandwidth within each layer under dynamic conditions, D3N provides an algorithm that adaptively
adjusts cache sizes based on observed workload patterns and congestion. D3N is highly-performant
and significantly improves big-data jobs performance.</li>
   <li><a target="_blank" href="https://www.bu.edu/rhcollab/projects/d3n/"> Project Page</a> </li>
</ul>


<h4>Erasure Coding for Performance</h4>
<ul>
   <li>In this project, we provide a detailed performance comparison of replication and erasure coding in
a modern distributed object store deployment using a simple mathematical model and empirical
analysis, and investigate the impact of storage solution characteristics (e.g. disk capacity, network
bandwidth) and workloads I/O profiles (read/write ratios) on the performance. In addition, we
show that a simple read cache increases the write fraction of the workload significantly, where
erasure coding has an great advantage. For both approaches, we point the possible improvements
which may improve the performance of redundancy solutions.</li>
</ul>
</div>



### Publications

<div class="card card-post w-100 border-top-0 border-left-0 border-right-0 rounded-0 mb-4">
<ul>
<li>
<b>D3N: A multi-layer cache for the rest of us </b>
<br/> 
E. Ugur Kaynar, Mania Abdi, Mohammad Hossein Hajkazemi, Ata Turk, Raja R. Sambasivan, Larry Rudolph, Peter Desnoyers, Orran Krieger <i>IEEE BIGDATA 2019<a target="_blank" href="papers/ekaynar_bigdata19.pdf"></a>[PDF]</i>
</li>
<br />


<li>
<b>D3N: A multi-level cache for improving big-data applications’ performance in datacenters with imbalanced networks </b>
<br/> 
E. Ugur Kaynar, Mohammad Hossein Hajkazemi, Mania Abdi, Ata Turk, Raja R Sambasivan, Larry Rudolph, David Cohen, Peter Desnoyers, Orran Krieger, <i>USENIX ATC 2018 - <a target="_blank" href="papers/d3n_poster.pdf">[Poster]</a> </i>
</li>
<br />


<li>
<b>M2: Malleable Metal as a Service </b><br />
Apoorve Mohan, Ata Turk, Ravi S Gudimetla, Sahil Tikale, Jason Hennesey, E. Ugur Kaynar,
Gene Cooperman, Peter Desnoyers, Orran Krieger, <i>    IEEE IC2E 2018 </i>
<a target="_blank" href="papers/m2.pdf">[PDF]</a>
</li>
<br />

<li><b>An Experiment on Bare-Metal BigData Provisioning</b> <br />
Ata Turk, Ravi S. Gudimetla, Emine Ugur Kaynar, Jason Hennessey, Sahil Tikale, Peter Desnoyers, Orran Krieger, <i>USENIX HotCloud 2016</i>
<a target="_blank" href="papers/hotcloud16.pdf">[PDF]</a>
</li>
<br />


   <li><b> HIL: Designing an Exokernel for the Data Center </b> <br />
   Jason Hennessey, Sahil Tikale, Ata Turk, Emine Ugur Kaynar, Chris Hill, Peter Desnoyers, Orran Krieger, <i>SoCC 2016</i> 
   <a target="_blank" href="papers/socc16.pdf">[PDF]</a>
   </li>
<br />

   <li><b>Performance Analysis of Encryption in Securing the Live Migration of Virtual Machines</b><br />
    Yaohui Hu, Sanket Panhale, TIanlin Li, Emine Ugur Kaynar, Danny Chan, Umesh Deshpande, Ping Yang, Kartik Gopalan

   <i> IEEE CLOUD 2015</i>
  <a target="_blank" href="papers/cloud15.pdf">[PDF]</a>

   </li>
</ul>
</div>

<h3 id="research_experience">Research Experience</h3>
<div class="card card-post w-100 border-top-0 border-left-0 border-right-0 rounded-0 mb-4">
<ul>
   <li> <b>RedHat Inc, Boston </b><br>
			May 2017 - Present<br>
		    Ceph Research Intern<br>
</li>
<br>
<li> <b>	Mass Open Cloud, Boston </b> <br>
			May 2015 - Present <br>
			Research Student <br>
</li>
</ul>
</div>

### Teaching
<div class="card card-post w-100 border-top-0 border-left-0 border-right-0 rounded-0 mb-4">
<i>Department of Computer Science, Boston University</i>
<ul>
<li>CS 591/ EC500 Cloud Computing</li>
<li>CS 108 Introduction to Application Programming </li>
<li>CS 111 Introduction to Computer Science </li>
</ul>

<i>Department of Computer Science, SUNY at Binghamton</i>
<ul>
<li>CS458/CS558 Introduction to Computer Security</li>
<li>CS 571 Programming Languages</li>
</ul>
</div>
