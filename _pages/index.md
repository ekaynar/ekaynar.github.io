---
title: 
layout: defaults/page
permalink: home
narrow: true
---
I am a Ph.D. candidate in the Department of Computer Science at Boston University working with <a href="http://okrieg.github.io/">Prof. Orran Krieger</a>, <a href="http://people.csail.mit.edu/rudolph/">Prof. Larry Rudolph</a> and <a href="http://www.ccs.neu.edu/home/pjd/index.html"> Prof. Peter Desnoyers</a>. 
<br>
I'm a member of <a target="_blank" href="http://www.bu.edu/cs/research/systems/"> the Systems Research Group</a>, and associated with <a target="_blank" href="https://massopen.cloud/">Mass Open Cloud</a> and <a target="_blank" href="https://research.redhat.com/">Red Hat Research.</a>

<!--{% include components/intro.md %}-->

<!--### Research Interests-->
My research interests lie broadly in the fields of <b>storage systems</b> and <b>cloud computing</b>. 
<br>
Currently, my research is focused on storage-related topics including <i><b>object storage caching</b></i>, <i><b>erasure coding</b></i> and <i><b>distributed storage systems</b></i>.

<div class="card card-post w-100 border-top-0 border-left-0 border-right-0 rounded-0 mb-4">
</div>

### Selected Research Projects

<div class="card card-post w-100 border-top-0 border-left-0 border-right-0 rounded-0 mb-4">

<h5>D4N: <u>D</u>irectory Based D3N</h5>
<ul>
D4N is a directory-based cooperative cache that provides a distributed directory that maintains a global state, re-uses the existing data lake (Ceph) software for implementing a write tier and exploits the semantics of immutable objects to move aged objects to the shared data lake.
<br/>
We are still in the process of “upstreaming” the D4N and convincing the Ceph upstream community.
<br/>
<a target="_blank" href="https://github.com/ekaynar/ceph-master/tree/datacache">[Github]</a>
<a target="_blank" href="https://research.redhat.com/blog/research_project/hybrid-cloud-cache/">[Red Hat Research D4N Page]</a>
</ul>

<h5>D3N: <u>D</u>atacenter-scale <u>D</u>ata <u>D</u>elivery <u>N</u>etwork</h5>
<ul>
D3N is a multi layer cooperative caching extension to storage system itself as a solution to network constrained data centers. 
D3N has been <b>upstreamed</b> into the <b>Ceph</b> code base by <i>Red Hat</i> and is available as an experimental feature in Ceph today.
<br/>
<a target="_blank" href="https://github.com/ceph/ceph/pull/36266">[Github]</a>
<a target="_blank" href="https://massopen.cloud/research-and-development/cloud-research/d3n/">[Project Page]</a>
<a target="_blank" href="https://research.redhat.com/blog/research_project/d3n-multilayer-cache/">[Red Hat Research D3N Page]</a>
<a target="_blank" href="https://https://research.redhat.com/wp-content/uploads/2019/05/RRQ-Vol1-2.pdf">[Article]</a>
<a target="_blank" href="https://ieeexplore.ieee.org/abstract/document/9006396">[Paper]</a>
</ul>
</div>

<!--<h4>Erasure Coding for Performance</h4>
<ul>
<li>In this project, we provide a detailed performance comparison of replication and erasure coding in
a modern distributed object store deployment using a simple mathematical model and empirical
analysis, and investigate the impact of storage solution characteristics (e.g. disk capacity, network
bandwidth) and workloads I/O profiles (read/write ratios) on the performance. In addition, we
show that a simple read cache increases the write fraction of the workload significantly, where
erasure coding has an great advantage. For both approaches, we point the possible improvements
which may improve the performance of redundancy solutions.</li>
</ul>
-->
### Publications

<div class="card card-post w-100 border-top-0 border-left-0 border-right-0 rounded-0 mb-4">
<ul>


<li>
<b>Universal Data Center Cache</b>, <i>Submitted</i>
<br/>
<b>Emine Ugur Kaynar</b>, Amin Mosayyebzadeh, Mania Abdi, Matt Benjamin, Larry Rudolph, Peter Desnoyers, Orran Krieger 
</li>
<br/>


<li>
<b>Cooperative Caching For Object Storage</b>, <i>Ph.D. Dissertation</i>,2022
<br/>
Emine Ugur Kaynar
<br/>
</li>
<br />



<li>
<b>Beating the I/O bottleneck: a case for log-structured virtual disks</b>, <i>EUROSYS 2022</i>
<br/>
Mohammad Hossein Hajkazemi, Vojtech Aschenbrenner, Mania Abdi, <b>Emine Ugur Kaynar</b>, Amin Mosayyebzadeh, Orran Krieger, Peter Desnoyers,
<a target="_blank" href="publications/lsvd-eurosys22.pdf">[Paper]</a>
</li>
<br/>


<li>
<b>A Community Cache with Complete Information</b>, <i>USENIX FAST 2021</i>
<br/>
Mania Abdi, Amin Mosayyebzadeh, Mohammad Hossein Hajkazemi, <b>Emine Ugur Kaynar</b>, Ata Turk, Larry Rudolph, Orran Krieger, Peter Desnoyers,
<a target="_blank" href="publications/kariz-fast21.pdf">[Paper]</a>
</li>
<br />

<li>
<b>D3N: A multi-layer cache for the rest of us</b>, <i>IEEE BIGDATA 2019 </i>
<br/> 
<b>Emine Ugur Kaynar</b>, Mania Abdi, Mohammad Hossein Hajkazemi, Ata Turk, Raja R. Sambasivan, Larry Rudolph, Peter Desnoyers, Orran Krieger,
<a target="_blank" href="publications/ekaynar_bigdata19.pdf">[Paper]</a>
</li>
<br />


<li>
<b>D3N: A multi-level cache for improving big-data applications’ performance in datacenters with imbalanced networks</b>, <i>USENIX ATC 2018 </i>
<br/> 
<b>Emine Ugur Kaynar</b>, Mohammad Hossein Hajkazemi, Mania Abdi, Ata Turk, Raja R Sambasivan, Larry Rudolph, David Cohen, Peter Desnoyers, Orran Krieger,
<a target="_blank" href="publications/d3n_poster.pdf">[Poster]</a> 
</li>
<br />


<li>
<b>M2: Malleable Metal as a Service</b>, <i>IEEE IC2E 2018</i>
<br/>
Apoorve Mohan, Ata Turk, Ravi S Gudimetla, Sahil Tikale, Jason Hennesey, <b>Emine Ugur Kaynar</b>,
Gene Cooperman, Peter Desnoyers, Orran Krieger,
<a target="_blank" href="publications/m2.pdf">[Paper]</a>
</li>
<br />

<li><b>An Experiment on Bare-Metal BigData Provisioning</b>, <i>USENIX HotCloud 2016</i>
<br/>
Ata Turk, Ravi S. Gudimetla, <b>Emine Ugur Kaynar</b>, Jason Hennessey, Sahil Tikale, Peter Desnoyers, Orran Krieger,
<a target="_blank" href="publications/bmi-hotcloud16.pdf">[Paper]</a>
</li>
<br />


   <li><b> HIL: Designing an Exokernel for the Data Center</b>, <i>SoCC 2016</i> 
	<br/>
   Jason Hennessey, Sahil Tikale, Ata Turk, <b>Emine Ugur Kaynar</b>, Chris Hill, Peter Desnoyers, Orran Krieger, 
   <a target="_blank" href="publications/hil-socc16.pdf">[Paper]</a>
   </li>
<br />

   <li><b>Performance Analysis of Encryption in Securing the Live Migration of Virtual Machines</b>, <i>IEEE CLOUD 2015</i>
   <br/>
    Yaohui Hu, Sanket Panhale, Tianlin Li, <b>Emine Ugur Kaynar</b>, Danny Chan, Umesh Deshpande, Ping Yang, Kartik Gopalan, 
  <a target="_blank" href="publications/cloud15.pdf">[Paper]</a>
   </li>
   <br/>
   
  <li><b>Impacts of Encryption on the Performance of Virtual Machine Migration</b>, <i>M.Sc. Thesis</i>,2013
   <br/>Emine Ugur Kaynar
   </li>

</ul>
</div>

### Research and Engineering Experience
<div class="card card-post w-100 border-top-0 border-left-0 border-right-0 rounded-0 mb-4">
<ul>

<li> <b>Red Hat</b>, Boston<br>
<b> Research Intern </b>, May 2017 to Present<br>
<b>Projects:</b>
	<ul>
	<li> D4N Caching for Ceph Object Storage </li>
	<li> Impact of node/rack failure and recovery on Ceph Object Storage </li>
	<li> Performance analysis of erasure coding and replication for Ceph Object Storage </li>
	<li> D3N Caching for Ceph Object Storage </li>
	</ul>
</li>

<li> <b>Mass Open Cloud</b>, Boston<br>
<b>System Researcher</b>, May 2015 - Present <br>
<b>Projects:</b>
	<ul>
	<li>MOC Monasca Monitoring Platform</li>
	<li>The Bare Metal Imaging Service</li>
	<li>Automated Deployment of Big Data Processing Environment</li>
	</ul>

</li>

</ul>
</div>

### Other Experience
<div class="card card-post w-100 border-top-0 border-left-0 border-right-0 rounded-0 mb-4">
<ul>

<li> <b> Project Mentor</b><br/>
<i>Department of Computer Science, Boston University</i>
<ul>
<li>CS 591/EC 528 Cloud Computing: <b>Accelerating Ceph Cloud Storage with D4N</b>
<a target="_blank" href="https://github.com/EC528-Project/ceph">[GitHub]</a>,
team of 4 graduate students
</li>

<li>CS 6620/EC 528 Cloud Computing: <b>Ceph RGW S3-Select Caching</b>
<a target="_blank" href="https://github.com/CS6620-S21/D4N-S3Select-Caching">[GitHub]</a>,
team of 4 graduate students
</li>

<li>CS 591/EC 528 Cloud Computing: <b>Ceph RGW Cache Prefetching</b>
<a target="_blank" href="https://github.com/bu-528-sp19/Ceph-RGW-Prefetching">[GitHub]</a>,
team of 3 graduate students
</li>

<li>CS 591/EC 520 Cloud Computing: <b>Mass Open Cloud Monitoring Platform</b>
<a target="_blank" href="https://github.com/BU-NU-CLOUD-SP16/MOC-Monitoring">[GitHub]</a>,
team of 3 undergrad/graduate students
</li>
</ul>
</li>

<li><b>Teaching</b><br/>
<i>Department of Computer Science, Boston University</i>
<ul>
<li>CS 591/EC 500 Cloud Computing</li>
<li>CS 108 Introduction to Application Programming </li>
<li>CS 111 Introduction to Computer Science </li>
</ul>

<i>Department of Computer Science, SUNY at Binghamton</i>
<ul>
<li>CS 458/CS 558 Introduction to Computer Security</li>
<li>CS 571 Programming Languages</li>
</ul>
</li>
</ul>
</div>


### Presentations
<ul>
<li><b>Hybrid Cloud Storage</b>,
Open Cloud Workshop 2020, Boston MA,
<a target="_blank" href="https://www.youtube.com/watch?v=O1b4-W1OuLE">[video]</a>
</li> 


<li> <b>D3N: A multi-layer cache for data centers</b>,
DevConf.us 2019, Boston MA,
<a target="_blank" href="https://www.youtube.com/watch?v=troLFFM6btc">[video]</a>
</li>

<li><b> D3N: A multi-layer cache for improving big-data applications' performance</b>
Mass Open Cloud Workshop 2019, Boston MA,
<a target="_blank" href="https://www.youtube.com/watch?v=9EGuEXWf8ts">[video]</a>
</li> 

<li><b>The Massachusetts Open Cloud:an Open Cloud eXchange</b>, Red Hat Summit 2017, Boston MA </li> 

<li><b>Big Data as a Service at Mass Open Cloud</b>
Open Stack Summit 2017, Boston MA,
<a target="_blank" href="https://www.openstack.org/videos/summits/boston-2017/big-data-as-a-service-at-mass-open-cloud">[video]</a>
</li>

</ul>

