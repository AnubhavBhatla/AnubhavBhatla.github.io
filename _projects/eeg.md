---
layout: page
title: EEG Data Acquistion System
description: Designed a 24-channel data acquisition system for capturing EEG signals
img: assets/img/eeg.jpg
importance: 2
category: "Technical Projects"
related_publications:
---

<center>
<div class="row">
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/eeg.png" title="EEG Data Acquisition System" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
</center>

<div class="caption">
    Overview of the designed EEG data acquistion system
</div>

_Guides: [Prof. Siddharth Tallur](https://www.ee.iitb.ac.in/web/people/siddharth-tallur/) and [rof. Laxmeesha Somappa](https://www.ee.iitb.ac.in/web/people/laxmeesha-somappa/)_

This project was done as part of the course EE344: Electronic Design Lab taken by Prof. Siddharth Tallur. My team designed a 24-channel EEG differential signal acquisition setup on a 4-layer PCB, complete with the analog front-end, daisy-chaining for the ADCs, analog and digital power regulators, and peripheral interfacing of Wi-Fi, SD-Card reader, and Accelerometer using two SPI buses present on the microcontroller. In order to make sure our design was correct, we studied the datasheets for various ADCs, voltage regulators, microcontrollers, Wi-Fi modules, and other peripherals. Since the design and verification process took a lot of time, and the printing process also takes time, we designed a 4-channel, modular, easy-to-stack signal acquisition setup along with a 3D-printed headgear for demo purposes. Due to our exemplary performance throughout the duration of the course, our team won the Best Project Award out of 60+ teams.

| [Report](https://anubhavbhatla.github.io/assets/pdf/EEG_Report.pdf){: .btn--report} | Design Files: [GitHub](https://github.com/AnubhavBhatla/EEG-Data-Acquisition-System){: .btn--github} | Software: [GitHub](https://github.com/aweditya/welbci){: .btn--github} |
