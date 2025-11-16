---
layout: page
title: "Branch Predictor Partitioning for Performance"
description: "Optimizing the NOP padding algorithm and working on identifying hot branches to improve their prediction rates"
img: assets/img/tage.png
importance: 5
category: research
related_publications: halfnhalf
---

<center>
<div class="row">
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/halfnhalf.png" title="Code translation in Half&Half" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Code translation in Half&Half
</div>
</center>

_Guide: [Prof. Dean Tullsen](https://cseweb.ucsd.edu/~tullsen/)_  

Half&Half is a novel technique that reverse-engineers modern branch predictors, identifying a simple way to partition the predictor space across two processes running in SMT mode. I am currently working on improving this partitioning algorithm to optimized the number of NOPs required. I am also working on identifying hot branches in a workload to separate them in order to improve their misprediction rate and thus improve performance.

