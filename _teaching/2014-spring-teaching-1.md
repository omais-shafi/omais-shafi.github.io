---
layout: archive
title: "Projects"
permalink: teaching/
author_profile: true

---
<p style="color:blue;font-size:20px;font-family:verdana;"><b>1. SecSched: Flexible Scheduling in Secure Processors</b></p>
<p>
 Trusted execution environments (TEEs) are an integral part ofmodern processors because security has become a very importantconcern. However, many such environments are bedeviled by thehigh cost of context switches, particularly when there is a switchfrom secure mode to non-secure mode owing primarily to cachepollution and TLB-flushing overheads. State-of-the-art implemen-tations create a secure shared memory channel between a threadrunning in secure mode and a thread running in non-secure mode,which invokes system calls on its behalf. We argue that this is in-efficient, and it is possible to reduce the overheads significantlyby efficiently storing the context of secure threads and intelligentscheduling. In this paper, we propose a new scheduling algorithmSecSchedthat uses Cuckoo filters to capture the context of a thread.We schedule threads with similar contexts on the same core toleverage the effects of the locality. Our algorithm requires minimalhardware enhancements that are limited to maintaining a Cuckoofilter per core and a thread with the addition of few performancecounters per thread to keep track of the miss counts. We show thatwith these minimal changes we can increase the performance ofa suite of OS-intensive workloads by 27.6% with a minimal areaoverhead (around 0.04%).
 
 </p>

<p style="color:blue;font-size:20px;font-family:verdana;"><b>2. FreqCounter: Efficient Cacheability of Encryption and Integrity Tree Counters in Secure Processors</b></p>

<p>
The data in the off-chip main memory can be potentially extracted or tampered by an adversary having physical access to the device and thus it becomes inevitable to secure the data present in the off-chip memory. The modern designs consider storing the counters on-chip to prevent replay attacks. However,  these designs have significant overheads in terms of the on-chip storage used to store counters, and the additional execution time. In this paper,we propose a new mechanism FreqCounter that trims the on-chip storage by storing the counters in a different manner.

</p>

<p style="color:blue;font-size:20px;font-family:verdana;"><b>3. TACT: Throughput, Accuracy, Cost and Thermal Trade-offs inEmbedded Road Traffic Management for Developing Regions</b></p>

<p>
Road traffic congestion increases vehicular emissions and air pollution. Traffic rule violation causes road accidents. Both pollution and accidents take tremendous social and economic toll worldwide, and more so in developing countries where the skewed vehicle to road infrastructure ratio amplifies the problems. This paper takes an important first step towards automating traffic intersection management in developing countries, using state-of-the-art Convolutional Neural Network (CNN) on traffic camera feeds. There are non-trivial accuracy challenges in handling the chaotic, non-laned traffic scenes in developing countries. Maintaining high throughput is another challenge, as broadband connectivity to remote GPU servers is absent in developing countries, and embedded GPU platforms on roads need to satisfy moderate budget constraints. Finally, ambient temperatures in developing country cities can go to 40-45 degree Celsius in summer, where continuous embedded processing can lead to lower lifetimes of the embedded platforms. This paper presents TACT, a careful throughput, accuracy, cost and thermal trade-off analysis for embedded road traffic management in developing regions. TACT achieves impressive balance of these conflicting metrics, through careful CNN optimizations, processor concurrency and frequency scaling, and measurement based modeling of thermal and power characteristics. In collaboration with our urban traffic management partners in New Delhi who are productizing TACT, this paper is a promising first step towards real world adoption of automated intersection control in developing countries, harnessing the power of ubiquitous and pervasive computing.
 
 </p>
 

<p style="color:blue;font-size:20px;font-family:verdana;"><b>4. CuckoOnsai: An Efficient Memory Authentication Using Amalgam of Cuckoo Filters and Integrity Trees</b></p>
<p>
 The off-chip main memory data can be extracted or tampered by an adversary having physical access to a device. In modern designs, such tampering or data attacks can be preventedby storing the integrity tree built using  encryption  counters. However, these approaches have high performance and on-chip storage overheads. In this work, we focus on reducing these performance and storage overheads of prior approaches used in secure processors.
</p>


<p style="color:blue;font-size:20px;font-family:verdana;"><b>5. Performance Prediction of end to end GPU Applications Using Analytical Modeling.</b></p>
<p>
 </p>


