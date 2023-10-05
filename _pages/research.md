---
layout: archive
title: "research"
permalink: /research/
author_profile: true
---


Calibrated Forecasting and Persuasion

(Best Poster Award at <u><a href="https://summerschool.hi-paris.fr">Hi! PARIS Summer School 2023</a>.</u>)






**Abstract**:  How should an expert send forecasts to maximize her payoff given she has to pass the calibration test? We consider a dynamic game where an expert sends probability forecasts to a decision-maker. The decision-maker, based on  past outcomes, verifies the claims of the expert using the calibration test.  We find the optimal forecasting strategy by reducing the dynamic  game in terms of a static persuasion problem for the class of stationary ergodic processes.   We compare what an informed and uninformed expert can attain and thus characterize the value of expertise. We also compare the calibration test and regret minimization as heuristics for decision-making. We show that an expert can always guarantee the calibration benchmark and in some instances, she can guarantee strictly more.

<div class="button-container">
  <a href="https://atulya-jain.github.io/files/calibration.pdf" download class="button">PDF</a>
  <a href="https://atulya-jain.github.io/files/poster-calibration.pdf" download class="button">Poster</a>
</div>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
