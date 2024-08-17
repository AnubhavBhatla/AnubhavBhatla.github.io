---
layout: page
title: "Branch Predictor Partitioning for Performance"
description: "Proposed the Oasis cache: A randomized cache design with minimal design complexity and ultra-low cost"
img: assets/img/tage.png
importance: 3
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

MIRAGE is a secure fully-associative last-level cache design which guarantees complete security against eviction-based side-channel attacks, but at a hefty hardware overhead of 17%. MAYA, on the other hand, guarantees the same level of security, at no hardware overhead. It is also able to save around 6% in terms of energy and area compared to the baseline. However, both these designs have a fair bit of additional design complexity, which make them impractical to be adopted by the industry. We are working on a secure randomized cache design which provides security at an ultra-low cost and minimal additional design complexity. This makes our cache design very pratical and easy to implement.

