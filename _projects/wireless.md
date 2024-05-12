---
layout: page
title: Error Correction in FSK
description: Implemented an Error-correction mechanism in FSK using Convolutional codes
img: assets/img/wireless.jpeg
importance: 11
category: "Technical Projects"
related_publications: 
---

<center>
<div class="row">
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/fsk.jpeg" title="GNURadio Flow Chart" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
</center>
<div class="caption">
    Overview of error-correction mechanism in FSK
</div>

_Guides: [Prof. Sibi Raj Pillai](https://www.ee.iitb.ac.in/wiki/faculty/bsraj)_  

This was a course project as part of the course EE764: Wireless and Mobile Communication taught by Prof. Sibi Raj Pillai. I implemented an error correction mechnaism using convolutional codes as part of the FSK flow. I successfully tested its effectiveness when a Gaussian noise is artificially inserted into the channel. Without error correction, BER went above -6 for a noise amplitude of 0.6, and with error correction, BER stayed below -6 even for a 1.1 noise amplitude.

&nbsp;&nbsp;&nbsp;&nbsp; [Report](https://anubhavbhatla.github.io/assets/pdf/EE764_report.pdf){: .btn--report} &nbsp;&nbsp;&nbsp;&nbsp; [GitHub](https://github.com/AnubhavBhatla/Digital-Signal-Processing){: .btn--github}
