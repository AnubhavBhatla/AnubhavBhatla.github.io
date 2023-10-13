---
layout: page
title: RUL Estimation for EV Batteries
description: Estimated the Remaining Useful Life of Li-ion EV batteries with an R2 score of 98.09
img: assets/img/ev.jpg
importance: 9
category: "Technical Projects"
related_publications: xgboost
---

<center>
<div class="row">
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/xgboost.png" title="XGBoost Regression Model" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
</center>
<div class="caption">
    A flow chart of the XGBoost Regression Model
</div>

_Guides: [Prof. Amit Sethi](https://www.ee.iitb.ac.in/~asethi/)_  

This was a course project as part of the course DS203: Programming for Data Science taught by Prof. Amit Sethi. We chose the problem statement of predicting the remaining useful life of Li-ion EV batteries using indirect discharge cycle parameters. We started by performing exploratory data analysis on the charging, discharging and impedance cycles for Li-ion batteries using NASA's PCoE datasets. We moved on to understanding, implementing and testing various regression models such as SVR, Multilayer Perceptron, LSTM, and various Boosting algorithms. We were able to achieve an R2 score of 98.09 for estimating the battery capacity using the XGBoost regression model.

[Report](https://anubhavbhatla.github.io/assets/pdf/RUL_Report.pdf){: .btn--report} &nbsp;&nbsp;&nbsp;&nbsp; [GitHub](https://github.com/AnubhavBhatla/ev-battery-degradation){: .btn--github}
