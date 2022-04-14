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

<h4>Hybrid Cloud Storage</h4>
<ul>
The values offered by public cloud services are clear for analytic workloads.  Specialized hardware such as GPUs for doing AI/ML may make more sense to effectively lease with Opex rather than invest Capex on infrastructure that is not continually utilized.  However, it may not make sense to build large data sets inside public clouds due both to the cost multiple compared to building out and maintaining private infrastructure and the lock-in nature of using public cloud services.
These drivers then lead toward a hybrid architecture where large data sets are built and maintained in private clouds, but compute/analytic clusters are spun up in public clouds to the actual analytics on these data sets.  
<br/>
<br/>
Maintaining a hybrid architecture as described introduces challenges with latency and bandwidth to the public cloud compute cluster from the private data lake.  In this project, we design and implement a new hybrid cloud caching architecture to maximize throughput of these leased analytics clusters and avoid re-reading the same data from the external private data lake. Our solution enables users of Kubernetes clusters to easily access any S3 compatible data lake. 
<br/>
<br/>
Check out hybrid cloud caching code on <a target="_blank" href="https://github.com/ekaynar/ceph-master">Github</a> for updates and new functionalities.

<!--   <li><a target="_blank" href="https://www.bu.edu/rhcollab/projects/d3n/"> Project Page</a> </li>
-->

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

### Past Projects
<div class="card card-post w-100 border-top-0 border-left-0 border-right-0 rounded-0 mb-4">
<h5>D3N: Caching for datacenters and datalakes</h5>
<ul>
D3N is a multi layer caching extension to storage system itself as a solution to network constrained datacenters. It is essentially designed to accelerate big data analytic workloads with strong locality traits and a limited network connectivity between compute clusters and data storage. The prototype of D3N has been implemented as a modification to Ceph Storages RADOS Gateway which is currently being integrated into the standard Ceph distribution (“upstreamed”) by Red Hat engineers.
<br/>
<br/>
To learn more about the D3N project, check out <a target="_blank" href="https://www.bu.edu/rhcollab/projects/d3n/">our website</a>.
Download and install D3N for your Ceph object store now. Check out <a target="_blank" href="https://github.com/ekaynar/ceph/tree/rgw_datacache/">Github Repo</a> for updates and new functionalities.
<br/>
<br/>
<a target="_blank" href="https://www.bu.edu/rhcollab/projects/d3n/">[Project Page]</a>
<a target="_blank" href="https://ieeexplore.ieee.org/abstract/document/9006396">[Paper]</a>
<a target="_blank" href="https://github.com/ekaynar/ceph/tree/rgw_datacache/">[Github]</a>
<br/>
</ul>
</div>

### Publications

<div class="card card-post w-100 border-top-0 border-left-0 border-right-0 rounded-0 mb-4">
<ul>
<li>
<b>A Community Cache with Complete Information </b>
<br/>
Mania Abdi, Amin Mosayyebzadeh, Mohammad Hossein Hajkazemi, Emine Ugur Kaynar, Ata Turk, Larry Rudolph, Orran Krieger, Peter Desnoyers <i>USENIX FAST 2021 </i>
<a target="_blank" href="papers/ekaynar_bigdata19.pdf">[Paper]</a>
</li>
<br />

<li>
<b>D3N: A multi-layer cache for the rest of us </b>
<br/> 
E. Ugur Kaynar, Mania Abdi, Mohammad Hossein Hajkazemi, Ata Turk, Raja R. Sambasivan, Larry Rudolph, Peter Desnoyers, Orran Krieger <i>IEEE BIGDATA 2019 </i>
<a target="_blank" href="papers/ekaynar_bigdata19.pdf">[Paper]</a>
</li>
<br />


<li>
<b>D3N: A multi-level cache for improving big-data applications’ performance in datacenters with imbalanced networks </b>
<br/> 
E. Ugur Kaynar, Mohammad Hossein Hajkazemi, Mania Abdi, Ata Turk, Raja R Sambasivan, Larry Rudolph, David Cohen, Peter Desnoyers, Orran Krieger, <i>USENIX ATC 2018 </i>
<a target="_blank" href="papers/d3n_poster.pdf">[Poster]</a> 
</li>
<br />


<li>
<b>M2: Malleable Metal as a Service </b><br />
Apoorve Mohan, Ata Turk, Ravi S Gudimetla, Sahil Tikale, Jason Hennesey, E. Ugur Kaynar,
Gene Cooperman, Peter Desnoyers, Orran Krieger, <i>    IEEE IC2E 2018 </i>
<a target="_blank" href="papers/m2.pdf">[Paper]</a>
</li>
<br />

<li><b>An Experiment on Bare-Metal BigData Provisioning</b> <br />
Ata Turk, Ravi S. Gudimetla, Emine Ugur Kaynar, Jason Hennessey, Sahil Tikale, Peter Desnoyers, Orran Krieger, <i>USENIX HotCloud 2016</i>
<a target="_blank" href="papers/hotcloud16.pdf">[Paper]</a>
</li>
<br />


   <li><b> HIL: Designing an Exokernel for the Data Center </b> <br />
   Jason Hennessey, Sahil Tikale, Ata Turk, Emine Ugur Kaynar, Chris Hill, Peter Desnoyers, Orran Krieger, <i>SoCC 2016</i> 
   <a target="_blank" href="papers/socc16.pdf">[Paper]</a>
   </li>
<br />

   <li><b>Performance Analysis of Encryption in Securing the Live Migration of Virtual Machines</b><br />
    Yaohui Hu, Sanket Panhale, TIanlin Li, Emine Ugur Kaynar, Danny Chan, Umesh Deshpande, Ping Yang, Kartik Gopalan

   <i> IEEE CLOUD 2015</i>
  <a target="_blank" href="papers/cloud15.pdf">[Paper]</a>

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
