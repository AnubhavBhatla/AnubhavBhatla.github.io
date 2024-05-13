---
layout: page
title: FPGA Accelerator for SNNs
description: Implemented and simulated an FPGA-based accelerator for Spiking Neural Networks
img: assets/img/snn.jpeg
importance: 3
category: "Technical Projects"
related_publications:
---

<center>
<div class="row">
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/snn.png" title="Spiking Neural Network" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
</center>
<div class="caption">
    Overview of the designed Spiking Neural Network flow
</div>

_Guide: [Prof. Sachin Patkar](https://www.ee.iitb.ac.in/wiki/faculty/patkar)_

This project was taken up as part of the course EE705: VLSI Design Lab by Prof. Sachin Patkar. The problem statement was to implement an FPGA-based accelerator for spiking neural networks. We designed an SNN flow graph with 784 input neurons and 100 hidden layer neurons. The input neurons were fed the MNIST images (encoded as a spike train) and finally the hidden layer neuron with the most spikes was used for classifying the image. The project involved the use of ROM IPs to store the input image, neuron weights, and the assignment mapping.

&nbsp;&nbsp;&nbsp;&nbsp; [Report](https://anubhavbhatla.github.io/assets/pdf/EE705_Report.pdf){: .btn--report} &nbsp;&nbsp;&nbsp;&nbsp; [GitHub](https://github.com/AnubhavBhatla/VLSI-Design-Lab){: .btn--github}
