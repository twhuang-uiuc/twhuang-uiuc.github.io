---
title: "TW's Research Group - Research"
layout: textlay
excerpt: "TW's Research Group -- Research"
sitemap: false
permalink: /research/
---

## Research

Our overarching goal is to create innovative software systems that can assist researchers and developers in the implementation of parallel and heterogeneous programs. We focus on a multidisciplinary area of electronic design automation, scientific computing, and machine learning.
We have released several open-source software
(<a href="https://taskflow.github.io/">Taskflow</a>,
<a href="https://github.com/OpenTimer/OpenTimer">OpenTimer</a>,
<a href="https://tsung-wei-huang.github.io/DtCraft/">DtCraft</a>,
<a href="https://github.com/dian-lun-lin/SNIG">SNIG</a>)
that is being used by many industrial and academic projects 
(>1M downloads & 5000+ GitHub stars).
Our research is framed by three themes.

+ [Theme #1: Parallel Programming Environments](#theme-1-parallel-programming-environments)
+ [Theme #2: VLSI Electronic Design Automation](#theme-2-vlsi-electronic-design-automation)
+ [Theme #3: Machine Learning Kernels Acceleration](#theme-3-machine-learning-kernels-acceleration)

<hr>

### Theme 1: Parallel Programming Environments

**Research Question**: *How can we make it easier for researchers and developers to write parallel and heterogeneous programs with high performance and simultaneous high productivity?*

<div style="max-width: 500px">
<img src="{{ site.url }}{{ site.baseurl }}/images/respic/theme_parallelism.png"  class="rounded" style="max-width: 100%">
</div>

<!--![]({{ site.url }}{{ site.baseurl }}/images/respic/theme_parallelism.png){: style="width: 450px; float: right; margin: 0px 0px"}-->

Modern scientific computing relies on a heterogeneous mix of computational patterns, domain algorithms, and specialized hardware to achieve key scientific milestones that go beyond traditional capabilities. However, programming these applications often requires complex expert-level tools and a deep understanding of parallel decomposition methodologies. Specifically, a suitable software environment that can overcome the complexity of programming large parallel and heterogeneous systems is extremely crucial to facilitate transformational scientific discoveries. Decades of research in high productivity computing has yielded methods and languages that offer either programmer productivity or performance scalability, but rarely both simultaneously. As applications continue to demand more computing power, there is a critical need for new parallel programming tools to advance various scientific computing applications. **Our research investigates new programming environments to assist researchers and developers to tackle the implementation complexities of high-performance parallel and heterogeneous programs.**

<div class="row row-padded align-items-center">
  <div class="col-md-2 col-sm-2 masthead">
  <div style="max-width: 100px; display: inline-block; text-align: center;">
  <p><a href="https://taskflow.github.io/"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/taskflow_logo.png" style="width: 100%;"></a></p>
  </div>
  </div>

  <div class="col-md-10 col-sm-10">
  <h4><a href="https://taskflow.github.io">Taskflow: A General-purpose Parallel and Heterogeneous Task Programming System</a></h4>
  <p>
  Taskflow helps C++ developers quickly write parallel and heterogeneous programs
  with high performance and simultaneous high productivity.
  </p>
  </div>
</div>

<div class="row row-padded align-items-center">
  <div class="col-md-2 col-sm-2 masthead">
  <div style="max-width: 100px; display: inline-block; text-align: center;">
  <p><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/dtcraft_logo.png" style="width: 100%;"></p>
  </div>
  </div>

  <div class="col-md-10 col-sm-10">
  <h4><a href="https://tsung-wei-huang.github.io/DtCraft/">DtCraft: A Distributed Programming System using Data-parallel Streams</a></h4>
  <p>DtCraft helps developers streamline the building of high-performance distributed applications using data-parallel streams on a machine cluster.</p>
  </div>
</div>

<hr>

### Theme 2: VLSI Electronic Design Automation

**Research Question**: *How can we leverage emerging heterogeneous parallelism to speed up electronic design automation (EDA) algorithms and achieve order-of-magnitude performance breakthrough?*

<div style="max-width: 500px">
<img src="{{ site.url }}{{ site.baseurl }}/images/respic/theme_cad.png"  class="rounded" style="max-width: 100%">
</div>

<!--![]({{ site.url }}{{ site.baseurl }}/images/respic/theme_cad.png){: style="width: 450px; float: right;"}-->
The ever-increasing design complexity in very-large-scale integration (VLSI) implementation has far exceeded what many existing electronic design automation (EDA) tools can scale with reasonable design time and effort. A key fundamental challenge is that EDA must incorporate new parallel paradigms comprising manycore central processing units (CPUs) and graphics processing units (GPUs) to achieve transformational performance and productivity milestones. However, this goal is impossible to achieve without a novel computing system to tackle the implementation complexities of parallelizing EDA, such as irregular task parallelism, large CPU-GPU dependent tasks, dynamic control flow, and distributed computing, which cannot be expressed and executed efficiently with mainstream parallel computing systems. **Our research investigates new computing methods to advance the current state-of-the-art by assisting everyone to efficiently tackle the challenges of designing, implementing, and deploying parallel EDA algorithms on heterogeneous nodes.**
  
<div class="row row-padded align-items-center">
  <div class="col-md-2 col-sm-2 masthead">
  <div style="max-width: 100px; display: inline-block; text-align: center;">
  <p><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/opentimer_logo.png" style="width: 100%;"></p>
  </div>
  </div>
  <div class="col-md-10 col-sm-10">
  <h4><a href="https://github.com/OpenTimer/OpenTimer">OpenTimer: A High-performance Timing Analysis Tool for VLSI Systems</a></h4>
  <p>OpenTimer helps electronic design automation tool researchers and developers quickly analyze the timing of large circuit designs.</p>
  </div>
</div>


<hr>

### Theme 3: Machine Learning Kernels Acceleration

**Research Question**: *How can we accelerate machine learning kernels in large-scale inference and training workloads using modern heterogeneous computing techniques?*

<div style="max-width: 500px">
<img src="{{ site.url }}{{ site.baseurl }}/images/respic/theme_ml.png"  class="rounded" style="max-width: 100%">
</div>
<!--![]({{ site.url }}{{ site.baseurl }}/images/respic/theme_ml.png){: style="width: 450px; float: right; margin: 0px 0px"}-->
Machine learning has become centric to a wide range of today's applications, such as autonomous driving, recommendation systems, and natural language processing. Machine learning algorithms are based on deep neural networks (DNN), which commonly have millions or billions of parameters to compute. Due to the unique performance characteristics, graphics processing units (GPUs) are increasingly used for machine learning applications and can dramatically accelerate neural network training and inference. Modern GPUs are fast and are equipped with new programming models and scheduling runtimes that can bring significant yet largely untapped performance benefits to many machine learning applications. For example, our research has shown that by leveraging the new GPU task graph model in CUDA to describe end-to-end parallelism, we can achieve 5--10 times speed-up over existing systems. **Our research investigates novel parallel algorithms and frameworks to accelerate machine learning system kernels with order-of-magnitude performance breakthrough.**

<div class="row row-padded align-items-center">
  <div class="col-md-2 col-sm-2 masthead">
  <div style="max-width: 100px; display: inline-block; text-align: center;">
  <p><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/snig_logo.png" style="width: 100%;"></p>
  </div>
  </div>
  <div class="col-md-10 col-sm-10">
  <h4><a href="https://github.com/dian-lun-lin/SNIG">SNIG: Large Sparse Neural Network Inference using Task Graph Parallelism</a></h4>
  <p>SNIG is the Champion-Award inference engine of the 2020 IEEE/MIT/Amazon HPEC Graph Challenge for Large Sparse Neural Network.</p>
  </div>
</div>

<br>


