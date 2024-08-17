---
layout: page
title: Secure Cache-Line Reallocation
description: "Exploring the idea of preferentially re-allocating dead blocks for improving performance"
img: assets/img/passp.png
importance: 5
category: research
related_publications: passp, ucp
---

<center>
<div class="row">
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/passp.png" title="PASS-P Re-allocation Scheme" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    An overview of PASS-P
</div>
</center>

_Guide: [Prof. Virendra Singh](https://www.ee.iitb.ac.in/~viren/)_  

Performance and Security Sensitive Dynamic Reallocation (PASS-P) is a modification on top of Utitlity-Based Partioning (UCP) which preferentially re-allocates clean cache lines in order to reduce memory latency and also invalidates them to prevent any side-channel attack to be mounted on the system. We performed an extensive analysis of PASS-P and concluded that because the LLC has a very high dead block percentage (dead blocks are blocks which never get a hit after being brought into the cache), they would serve as a good eviction candidate, since they are anyways going to be evicted after some time without getting a hit. With our proposal, were able to reduce the deadblock percentage by over 10% averaged across all benchmarks.  

&nbsp;&nbsp;&nbsp;&nbsp; [Report](https://anubhavbhatla.github.io/assets/pdf/R&D_report.pdf){: .btn--report} &nbsp;&nbsp;&nbsp;&nbsp; [Slides](https://anubhavbhatla.github.io/assets/pptx/R&D_presentation.pptx){: .btn--slides}


