---
layout: page
title: Hardware-Efficient Secure Cache Design
description: "Proposed MAYA: A secure and storage-efficient fully-associative last-level cache design"
img: assets/img/mirage.png
importance: 1
category: work
related_publications: einstein1956investigations, einstein1950meaning
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/mirage.png" title="MIRAGE cache design" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    An overview of the MIRAGE cache design
</div>

The MIRAGE cache is a secure fully-associative last-level cache design which guarantees complete security against eviction-based side-channel attacks, but at a hefty hardware overhead of 17%. We propose MAYA, which guarantees the same level of security, but at no hardware overhead compared to a non-secure baseline. We are also able to save around 6% in terms of energy and area compared to the baseline.

<!-- <div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div> -->
<!-- <div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div> -->