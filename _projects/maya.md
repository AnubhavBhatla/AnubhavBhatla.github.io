---
layout: page
title: "Hardware-Efficient Secure Cache Design"
description: "Proposed the Maya Cache: A secure and storage-efficient fully-associative last-level cache design"
img: assets/img/mirage.png
importance: 2
category: research
related_publications: maya mirage
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

_Guide: [Prof. Biswabandan Panda](https://www.cse.iitb.ac.in/~biswa/)_  

MIRAGE is a secure fully-associative last-level cache design which guarantees complete security against eviction-based side-channel attacks, but at a hefty hardware overhead of 17%. We propose MAYA, which guarantees the same level of security, and at no hardware overhead compared to a non-secure baseline. We are also able to save around 6% in terms of energy and area compared to the baseline.

