---
layout: page
title: "Practical and Secure Cache Design at Ultra-Low Cost"
description: "Proposed the Avatar cache: A morphable LLC design which provides security-on-demand with minimal design complexity and ultra-low cost"
img: assets/img/mirage.png
importance: 3
category: research
related_publications: avatar, maya, mirage
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

MIRAGE is a secure fully-associative last-level cache design which guarantees complete security against eviction-based side-channel attacks, but at a hefty hardware overhead of 17%. MAYA, on the other hand, guarantees the same level of security, at no hardware overhead. It is also able to save around 6% in terms of energy and area compared to the baseline. However, both these designs have a fair bit of additional design complexity, which make them impractical to be adopted by the industry. We propose a framework for a morphable last-level cache design which provides security-on-demand based on the system/user's security and performance requirements with minimal changes to a traditional LLC.

