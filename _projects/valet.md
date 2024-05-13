---
layout: page
title: Valet Parking Bot
description: Built a line-follower bot, capable of obstacle-avoidance and parking using the Arduino-UNO based Alphabot
img: assets/img/valet.jpg
importance: 11
category: "Technical Projects"
related_publications:
---

<center>
<div class="row">
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/arena.png" title="Arena" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
</center>
<div class="caption">
    The arena used for the testing of the bot
</div>

_Guides: [Prof. Paritosh Pandya](https://www.cse.iitb.ac.in/~pandya58/) and [Prof. Kavi Arya](https://iitb.irins.org/profile/51854)_  

This was a course project as part of the course CS684: Embedded Systems taught by Prof. Paritosh Pandya and Prof. Kavi Arya. For this project, we were tasked with building a line follower bot, capable of avoiding obstacles and parking itself in an empty location in a marked region. A valet parking bot! We interfaced various tracker sensors, proximity sensors, and position encoders using the Arduino board present on the Alphabot, used for the project. All the required algorithms for line following, obstacle avoidance, and parking using the Heptagon language. The controller was programmed in Embedded C, and used to set up sensors and motor drivers, and interface with the Heptagon code.

&nbsp;&nbsp;&nbsp;&nbsp; [GitHub](https://github.com/AnubhavBhatla/Valet-Parking-Bot){: .btn--github}
