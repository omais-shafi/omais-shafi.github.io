---
layout: archive
title: "Projects"
permalink: teaching/
author_profile: true

---
 

<p style="color:blue;font-size:20px;font-family:verdana;"><b>1. SecSched: Flexible Scheduling in Secure Processors[2017-2018]</b></p>

<p>
        
 Trusted execution environments (TEEs) are an integral part of modern processors because security has become a very important concern. However, many such environments are bedeviled by the high cost of context switches, particularly when there is a switch from secure mode to non-secure mode owing primarily to cache pollution and TLB-flushing overheads. State-of-the-art implementations create a secure shared memory channel between a thread running in secure mode and a thread running in non-secure mode, which invokes system calls on its behalf. We argue that this is in-efficient, and it is possible to reduce the overheads significantly by efficiently storing the context of secure threads and intelligent scheduling. In this paper, we propose a new scheduling algorithm SecSched that uses Cuckoo filters to capture the context of a thread. We schedule threads with similar contexts on the same core to leverage the effects of the locality. Our algorithm requires minimal hardware enhancements that are limited to maintaining a Cuckoofilter per core and a thread with the addition of few performance counters per thread to keep track of the miss counts. We show that with these minimal changes we can increase the performance of a suite of OS-intensive workloads by 27.6% with a minimal area overhead (around 0.04%).
 
 </p>

<p style="color:blue;font-size:20px;font-family:verdana;"><b>2. FreqCounter: Efficient Cacheability of Encryption and Integrity Tree Counters in Secure Processors[2018-2019]</b></p>

<p>
The data in the off-chip main memory can be potentially extracted or tampered by an adversary having physical access to the device and thus it becomes inevitable to secure the data present in the off-chip memory. The modern designs consider storing the counters on-chip to prevent replay attacks. However,  these designs have significant overheads in terms of the on-chip storage used to store counters, and the additional execution time. In this paper,we propose a new mechanism FreqCounter that trims the on-chip storage by storing the counters in a different manner.

</p>

<p style="color:blue;font-size:20px;font-family:verdana;"><b>3. TACT: Throughput, Accuracy, Cost and Thermal Trade-offs inEmbedded Road Traffic Management for Developing Regions[2020]</b></p>

<p>
Road traffic congestion increases vehicular emissions and air pollution. Traffic rule violation causes road accidents. Both pollution and accidents take tremendous social and economic toll worldwide, and more so in developing countries where the skewed vehicle to road infrastructure ratio amplifies the problems. This work takes an important first step towards automating traffic intersection management in developing countries, using state-of-the-art Convolutional Neural Network (CNN) on traffic camera feeds.
 
 </p>
 

<p style="color:blue;font-size:20px;font-family:verdana;"><b>4. An Efficient Memory Authentication for Secure Processors[2019-2020]</b></p>
<p>
 The off-chip main memory data can be extracted or tampered by an adversary having physical access to a device. In modern designs, such tampering or data attacks can be preventedby storing the integrity tree built using  encryption  counters. However, these approaches have high performance and on-chip storage overheads. In this work, we focus on reducing these performance and storage overheads of prior approaches used in secure processors.
</p>


<p style="color:blue;font-size:20px;font-family:verdana;"><b>5. Performance Prediction of end to end GPU Applications Using Analytical Modeling [2021 Ongoing]</b></p>
