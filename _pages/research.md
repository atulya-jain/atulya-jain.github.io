---
layout: archive
title: "research"
permalink: /research/
author_profile: true
---


- Calibrated Forecasting and Persuasion with Vianney Perchet

(Best Poster Award at <a href="https://summerschool.hi-paris.fr">Hi! PARIS Summer School 2023</a>.)


<details>
  <summary>**Abstract**</summary>
  
How should an expert send forecasts to maximize her payoff given she has to pass the calibration test? We consider a dynamic game where an expert sends probability forecasts to a decision-maker. The decision-maker, based on  past outcomes, verifies the claims of the expert using the calibration test.  We find the optimal forecasting strategy by reducing the dynamic  game in terms of a static persuasion problem for the class of stationary ergodic processes.   We compare what an informed and uninformed expert can attain and thus characterize the value of expertise. We also compare the calibration test and regret minimization as heuristics for decision-making. We show that an expert can always guarantee the calibration benchmark and in some instances, she can guarantee strictly more.

</details>




<div class="button-container">
  <a href="https://atulya-jain.github.io/files/calibration.pdf" download class="button">PDF</a>
  <a href="https://atulya-jain.github.io/files/poster-calibration.pdf" download class="button">Poster</a>
</div>



- Are Bayesian persuasion outcomes efficient? with Itai Arieli, Yakov Babichenko and Rann Smorodinsky

**Abstract**:  Information transmission between players with asymmetric information can improve outcomes and lead to  efficiency. We consider the model of Bayesian persuasion: a sender commits to a signaling policy to persuade an uninformed receiver. We analyze the Pareto efficiency of the equilibrium outcome and provide a necessary condition for it.  Using a natural class of games, we show that  efficiency   is non-trivial and  difficult to attain.


- Dynamic Cheap Talk with no feedback


**Abstract**: We study a dynamic sender-receiver game, where the sequence of states follows an irreducible Markov chain. The sender provides valuable information but gets no feedback on the receiver’s actions. Under certain assumptions, we characterize the set of uniform equilibrium payoffs in terms of a static cheap talk game, where the marginal distribution of messages is fixed. We show that the sender benefits from the dynamic interaction, even without feedback. We provide sufficient conditions to bridge the gap of commitment and thus secure the Bayesian persuasion value.



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
