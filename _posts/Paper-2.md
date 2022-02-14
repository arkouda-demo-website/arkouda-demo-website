---
title: "Large Scale String Analytics In Arkouda. IEEE HPEC."
date: 2021-09-18T15:34:30-04:00
categories:
  - Publications
tags:
  - large scale string sets
  - Arkouda
---
#### Authors
<p align="justify">
Zhihui Du, Oliver Alvarado Rodriguez, and David A. Bader
</p>

#### Abstract
<p align="justify">
Large scale data sets from the web, social networks, and bioinformatics are widely available and can often be represented by strings and suffix arrays are highly efficient data structures enabling string analysis. But, our personal devices and corresponding exploratory data analysis (EDA) tools cannot handle big data sets beyond the local memory. Arkouda is a framework under early development that brings together the productivity of Python at the user side with the high-performance of Chapel at the server-side. In this paper, an efficient suffix array data structure design and integration method are given first. A suffix array algorithm library integration method instead of one single suffix algorithm is presented to enable runtime performance optimization in Arkouda since different suffix array algorithms may have very different practical performances for strings in various applications. A parallel suffix array construction algorithm framework is given to further exploit hierarchical parallelism on multiple locales in Chapel. A corresponding benchmark is developed to evaluate the feasibility of the provided suffix array integration method and measure the end-to-end performance. Experimental results show that the proposed solution can provide data scientists an easy and efficient method to build suffix arrays with high performance in Python.
</p>



