---
layout: page
title: 2-stage OTA Design
description: Designed a 2-stage Operational Transconductance Amplifier for the specified parameters and implemented it using Cadence Virtuoso
img: assets/img/cmos.png
importance: 5
category: "Technical Projects"
related_publications:
---

<center>
<div class="row">
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/ota.png" title="CMOS VLSI Design" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
</center>
<div class="caption">
    Overview of a 2-stage Operational Transconductance Amplifier
</div>

_Guide: [Prof. Rajesh Zele](http://www.ee.iitb.ac.in/~zelerajesh/index.php)_

I worked on this project as part of the course EE618: CMOS Analog VLSI Design taken by Prof. Rajesh Zele. To get us familiarized with Virtuoso, we were tasked with design the schematic and layout for a CMOS Inverter with specified rise and fall times. We were also required to perform post-layout simulations by incorporating parasitic capacitances and observing the change in the output voltage. 
The final project was to design and simulate a 2-stage OTA with RC compensation for the given parameters of noise, gain, slew rate, unity gain frequency, and phase margin. The final layout for the OTA had a 50dB gain, unity-gain frequency of 108MHz, 67.4 degree phase margin, all within a power budget of 0.22mW.

&nbsp;&nbsp;&nbsp;&nbsp; [Report](https://anubhavbhatla.github.io/assets/pdf/EE618_report.pdf){: .btn--report}
