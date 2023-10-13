---
layout: page
title: RISC Processor Design
description: Designed and implemented 16-bit 6-stage pipelined processor in VHDL
img: assets/img/risc.png
importance: 7
category: "Technical Projects"
related_publications:
---

<center>
<div class="row">
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/pipeline.jpg" title="Pipelined Processor" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Overview of a 6-stage pipeline processor
</div>
</center>

_Guide: [Prof. Virendra Singh](https://www.ee.iitb.ac.in/~viren/)_  

This was a course project as part of the course EE309: Microprocessors taught by Prof. Virendra Singh. The project involved designing a 6-stage Pipelined processor, capable of running a Turing-complete ISA of 17 instructions. Ours was one of the few teams to optimize the processor using hazard mitigation techniques, forwarding logic, and branch prediction techniques. We also performed software testing for all the instructions using the Intel Quartus Environment and the ModelSim HDL simulator.

| [GitHub](https://github.com/AnubhavBhatla/IITB-RISC-22){: .btn--github} |
