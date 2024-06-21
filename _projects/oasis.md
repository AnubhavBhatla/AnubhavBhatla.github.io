---
layout: page
title: "Enabling Provably Secure Randomized Caches at Ultra-Low Cost"
description: "Working on a randomized cache design which enables security with minimal additional complexity"
img: assets/img/mirage.png
importance: 1
category: research
related_publications: maya, mirage
---

<center>
<div class="row">
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/mirage.png" title="MIRAGE cache design" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    An overview of the MIRAGE cache design
</div>
</center>

_Guides: [Prof. Moinuddin Qureshi](https://moin.cc.gatech.edu), [Prof. Biswabandan Panda](https://www.cse.iitb.ac.in/~biswa/)_  

MIRAGE is a secure fully-associative last-level cache design which guarantees complete security against eviction-based side-channel attacks, but at a hefty hardware overhead of 17%. MAYA, on the other hand, guarantees the same level of security, at no hardware overhead. It is also able to save around 6% in terms of energy and area compared to the baseline. However, both these designs have a fair bit of additional design complexity, which make them impractical to be adopted by the industry. We are working on a secure randomized cache design which provides security at an ultra-low cost and minimal additional design complexity. This makes our cache design very pratical and easy to implement.

