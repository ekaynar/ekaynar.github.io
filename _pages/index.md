---
title: 
layout: defaults/page
permalink: index.html 
narrow: true
skills:
  - Team Leadership
  - Technical Architecture
  - User Interface Design
  - Project Management
---
I have just receieved my Ph.D. (May 2022) from the Department of Computer Science at Boston University. I am working with <a href="https://www.bu.edu/eng/profile/orran-krieger/">Prof. Orran Krieger</a>, <a href="http://people.csail.mit.edu/rudolph/">Prof. Larry Rudolph</a> and <a href="http://www.ccs.neu.edu/home/pjd/index.html"> Prof. Peter Desnoyers</a>. 
<br>
I'm a member of <a target="_blank" href="http://www.bu.edu/cs/research/systems/"> the Systems Research Group</a>, and associated with <a target="_blank" href="https://massopen.cloud/">Mass Open Cloud</a> and <a target="_blank" href="https://research.redhat.com/">Red Hat Research.</a>

<b>Interests:</b> Computer System Design for Cloud Computing, Distributed Systems, Cloud Storage Systems, Performance Analysis and Tuning
<br>
<b>Skills:</b> Ceph, OpenStack, Alluxio, Hadoop, Spark, C++, Bash, Python
<br>

I am passionate about building large distributed systems and contributing to open source projects. I worked on the design/development of scalable cloud-based platforms and improving the performance and efficiency of distributed frameworks. 


<!--My research interests lie broadly in the fields of  <b>cloud computing</b>, <b>distributed systems</b> and <b>cloud storage systems</b>. 
<br>
Currently, my research is focused on storage-related topics including <b>caching systems</b>, <b>object storage</b>, <b>erasure coding</b> and <b>distributed storage systems</b>.
-->
<div class="card card-post w-100 border-top-0 border-left-0 border-right-0 rounded-0 mb-4">
</div>

### Education
<div class="card card-post w-100 border-top-0 border-left-0 border-right-0 rounded-0 mb-4">
<ul>
<li>
<b>
Ph.D. in Computer Science</b> - Boston University, May 2022 <br/>
<ul>
<li> Dissertation: Cooperative Caching for Object Storage (Advisor: Orran Krieger)</li>
</ul>
</li>

<li>
<b>M.Sc. in Computer Science</b> - SUNY at Binghamton,  August 2013 <br/>
<ul>
<li>Thesis: Impact of Encryption on Live Virtual Machine Migration (Advisor: Ping Yang) </li>
</ul>
</li>

<li>
<b>B.Sc. in Information Systems Engineering</b> - Bogazici University/SUNY at Binghamton,  May 2011 <br/>
</li>
</ul>

</div>

### Open Source Software
<div class="card card-post w-100 border-top-0 border-left-0 border-right-0 rounded-0 mb-4">
D3N Data Cache For Ceph Object Storage, Merged into Ceph by Red Hat, 2021. 
<a target="_blank" href="https://docs.ceph.com/en/quincy/radosgw/d3n_datacache/">[Ceph Documentation]</a>
<br/>
</div>

### Selected Research Projects

<div class="card card-post w-100 border-top-0 border-left-0 border-right-0 rounded-0 mb-4">

<ul>
<li><b> D4N (<u>D</u>irectory Based D3N)</b>
is a directory-based cooperative cache that provides a distributed directory for a global state, re-uses the existing data lake (Ceph) software for implementing a write tier and exploits the semantics of immutable objects to move aged objects to the shared data lake.
<br/>
We are still in the process of upstreaming the D4N and convincing the Ceph upstream community.
<br/>
<a target="_blank" href="https://github.com/ekaynar/ceph-master/tree/datacache">[Github]</a>
<a target="_blank" href="https://research.redhat.com/blog/research_project/hybrid-cloud-cache/">[Red Hat Research D4N Page]</a>
</li>
</ul>

<ul>
<li><b>D3N (<u>D</u>atacenter-scale <u>D</u>ata <u>D</u>elivery <u>N</u>etwork)</b>
is a multi layer cooperative caching extension to storage system itself as a solution to network constrained data centers. 
D3N enables data sharing across analytic clusters (e.g., Spark) in a data center, and dynamically adapts to changes in access patterns.
<!--D3N has been <b>upstreamed</b> into the <b>Ceph</b> code base by <i>Red Hat</i> and is available as an experimental feature in Ceph today.-->
<br/>
<a target="_blank" href="https://docs.ceph.com/en/quincy/radosgw/d3n_datacache/">[Ceph Documentation]</a>
<a target="_blank" href="https://massopen.cloud/research-and-development/cloud-research/d3n/">[Project Page]</a>
<a target="_blank" href="https://research.redhat.com/blog/research_project/d3n-multilayer-cache/">[Red Hat Research D3N Page]</a>
<a target="_blank" href="https://research.redhat.com/wp-content/uploads/2019/05/RRQ-Vol1-2.pdf">[Article]</a>
<a target="_blank" href="https://ieeexplore.ieee.org/abstract/document/9006396">[Paper]</a>
</li>
</ul>

<ul>
<li><b>Elastic Secure Infrastructure (ESI):</b>
Involved ESI project which explores how to build a secure bare-metal elastic infrastructure for data centers and efficiently multiplexing bare-metal servers between different tenants. <a target="_blank" href="https://github.com/CCI-MOC/m2">Bare-Metal Imaging (BMI)</a> prototype we developed is a generic bare-metal provisioning solution for rapid deployment of bare-metal nodes on demand, and brings attractive image management capabilities (e.g., fast snapshotting, cloning, rapid provisioning etc.) of virtualized solutions to bare-metal systems.


<br/>
<a target="_blank" href="https://massopen.cloud/research-and-development/reproducible-cloud/elastic-secure-infrastructure-esi/">[Project Page]</a>
</li>
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
<b>Universal Data Center Cache</b>, <i>Submitted (2022)</i>
<br/>
<b>E. U. Kaynar</b>, A. Mosayyebzadeh, M. Abdi, M. Benjamin, L. Rudolph, P. Desnoyers, O. Krieger 
</li>
<br/>


<li>
<b>Cooperative Caching For Object Storage</b>, <i>Ph.D. Dissertation</i>, 2022
<br/>
<b>E. U. Kaynar</b>
<br/>
</li>
<br />



<li>
<b>Beating the I/O Bottleneck: A Case for Log-structured Virtual Disks</b>, <i>EUROSYS 2022</i>
<br/>
M. H. Hajkazemi, Vojtech Aschenbrenner, M. Abdi, <b>E. U. Kaynar</b>, A. Mosayyebzadeh, O. Krieger, P. Desnoyers,
<a target="_blank" href="publications/lsvd-eurosys22.pdf">[Paper]</a>
</li>
<br/>


<li>
<b>A Community Cache with Complete Information</b>, <i>USENIX FAST 2021</i>
<br/>
M. Abdi, A. Mosayyebzadeh, M. H. Hajkazemi, <b>E. U. Kaynar</b>, A. Turk, L. Rudolph, O. Krieger, P. Desnoyers,
<a target="_blank" href="publications/kariz-fast21.pdf">[Paper]</a>
</li>
<br />

<li>
<b>D3N: A multi-layer cache for the rest of us</b>, <i>IEEE BIGDATA 2019 </i>
<br/> 
<b>E. U. Kaynar</b>, M. Abdi, M. H. Hajkazemi, A. Turk, R. R. Sambasivan, L. Rudolph, P. Desnoyers, O. Krieger,
<a target="_blank" href="publications/ekaynar_bigdata19.pdf">[Paper]</a>
</li>
<br />

<!--
<li>
<b>D3N: A multi-level cache for improving big-data applications’ performance in datacenters with imbalanced networks</b>, <i>USENIX ATC 2018 </i>
<br/> 
<b>E. U. Kaynar</b>, M. H. Hajkazemi, M. Abdi, A. Turk, R. R. Sambasivan, L. Rudolph, D. Cohen, P. Desnoyers, O. Krieger,
<a target="_blank" href="publications/d3n_poster.pdf">[Poster]</a> 
</li>
<br />
-->

<li>
<b>M2: Malleable Metal as a Service</b>, <i>IEEE IC2E 2018</i>
<br/>
A. Mohan, A. Turk, R. S. Gudimetla, S. Tikale, J. Hennesey, <b>E. U. Kaynar</b>,
G. Cooperman, P. Desnoyers, O. Krieger,
<a target="_blank" href="publications/m2.pdf">[Paper]</a>
</li>
<br />

<li><b>An Experiment on Bare-Metal BigData Provisioning</b>, <i>USENIX HotCloud 2016</i>
<br/>
A. Turk, R. S. Gudimetla, <b>E. U. Kaynar</b>, J. Hennessey, S. Tikale, P. Desnoyers, O. Krieger,
<a target="_blank" href="publications/bmi-hotcloud16.pdf">[Paper]</a>
</li>
<br />


   <li><b> HIL: Designing an Exokernel for the Data Center</b>, <i>SoCC 2016</i> 
	<br/>
   J. Hennessey, S. Tikale, A. Turk, <b>E. U. Kaynar</b>, C. Hill, P. Desnoyers, O. Krieger, 
   <a target="_blank" href="publications/hil-socc16.pdf">[Paper]</a>
   </li>
<br />

   <li><b>Performance Analysis of Encryption in Securing the Live Migration of Virtual Machines</b>, <i>IEEE CLOUD 2015</i>
   <br/>
    Y. Hu, S. Panhale, T. Li, <b>E. U. Kaynar</b>, D. Chan, U. Deshpande, P. Yang, K. Gopalan, 
  <a target="_blank" href="publications/cloud15.pdf">[Paper]</a>
   </li>
   <br/>
   
  <li><b>Impacts of Encryption on the Performance of Virtual Machine Migration</b>, <i>M.Sc. Thesis</i>,2013
   <br/>E. U. Kaynar
   </li>

</ul>
</div>

### Experience
<div class="card card-post w-100 border-top-0 border-left-0 border-right-0 rounded-0 mb-4">
<ul>

<li> <b>Red Hat</b>, Boston<br>
<b> Research Intern </b>, May 2017 to Present<br>
<!--<b>Projects:</b>-->
	<ul>
	<li> Hybrid Cloud Cache</li>
	<li> Upstreaming D3N into Ceph Object Storage</li>
    <li> Impact of node/rack failure and recovery on Ceph Object Storage </li>
	<li> Performance analysis of erasure coding and replication for Ceph Object Storage </li>
	</ul>
</li>

<li> <b>Mass Open Cloud (MOC) Alliance</b>, Boston<br>
<b>System Researcher</b>, May 2015 - Present <br>
<!--<b>Projects:</b>-->
	<ul>
    <li>Big Data Platform</li>
	<li>Monitoring Platform</li>
<!--	<li>Automated Deployment of Big Data Processing Environment</li>-->
	</ul>

</li>

</ul>
</div>

### Teaching and Mentoring Experience
<div class="card card-post w-100 border-top-0 border-left-0 border-right-0 rounded-0 mb-4">
<ul>

<li> <b>Mentoring</b><br/>
<i>Department of Computer Science, Boston University</i>
<ul>
<li><b>Accelerating Ceph Cloud Storage with D4N</b>
<a target="_blank" href="https://github.com/EC528-Project/ceph">[GitHub]</a>,
team of 4 graduate students
</li>

<li><b>Ceph RGW S3-Select Caching</b>
<a target="_blank" href="https://github.com/CS6620-S21/D4N-S3Select-Caching">[GitHub]</a>,
team of 4 graduate students
</li>

<li><b>Ceph RGW Cache Prefetching</b>
<a target="_blank" href="https://github.com/bu-528-sp19/Ceph-RGW-Prefetching">[GitHub]</a>,
team of 3 graduate students
</li>

<li><b>Mass Open Cloud Monitoring Platform</b>
<a target="_blank" href="https://github.com/BU-NU-CLOUD-SP16/MOC-Monitoring">[GitHub]</a>,
team of 3 graduate students
</li>
</ul>
</li>

<li><b>Teaching Assistant</b><br/>
<i>Department of Computer Science, Boston University</i>
<ul>
<li>Cloud Computing</li>
<li>Introduction to Application Programming </li>
<li>Introduction to Computer Science </li>
</ul>

<i>Department of Computer Science, SUNY at Binghamton</i>
<ul>
<li>Introduction to Computer Security</li>
<li>Programming Languages</li>
</ul>
</li>
</ul>
</div>


### Talks and Presentations
<ul>
<li><b>Hybrid cloud storage</b>,
Open Cloud Workshop 2020, Boston MA,
<a target="_blank" href="https://www.youtube.com/watch?v=O1b4-W1OuLE">[video]</a>
</li> 


<li> <b>D3N: A multi-layer cache for data centers</b>,
DevConf.us 2019, Boston MA,
<a target="_blank" href="https://www.youtube.com/watch?v=troLFFM6btc">[video]</a>
</li>

<li><b> D3N: A multi-layer cache for improving big-data applications' performance</b>,
Mass Open Cloud Workshop 2019, Boston MA,
<a target="_blank" href="https://www.youtube.com/watch?v=9EGuEXWf8ts">[video]</a>
</li> 

<li><b>The Massachusetts Open Cloud:an Open Cloud eXchange</b>, Red Hat Summit 2017, Boston MA </li> 

<li><b>Big Data as a Service at Mass Open Cloud</b>,
Open Stack Summit 2017, Boston MA,
<a target="_blank" href="https://www.openstack.org/videos/summits/boston-2017/big-data-as-a-service-at-mass-open-cloud">[video]</a>
</li>

</ul>

