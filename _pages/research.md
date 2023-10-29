---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

- Informing agents amidst biased narratives (*Job Market Paper*)

  <details>
    <summary>Abstract</summary>
  
    I study the strategic interaction between a benevolent sender (who provides data) and a biased narrator (who interprets data) who compete to persuade a boundedly rational receiver (who takes action). The receiver does not know the data-generating model and must choose between  models provided by the sender and the narrator. The receiver chooses the model using the maximum likelihood principle, selecting the one that best fits the data given her prior belief.  The sender faces a trade-off between providing information and minimizing misinterpretation. To find the optimal data-generating model, which maximizes the receiver's expected utility, I restrict the search to a finite set of models. This set  only depends on the preferences of the narrator and receiver, along with the prior belief. I show that the fully informative model can be sub-optimal and  even backfire.  Finally, I apply this framework to information campaigns and  employee feedback.

  </details>



- Calibrated Forecasting and Persuasion (with Vianney Perchet)

  (Best Poster  at  [Hi! Paris Summer School 2023](https://summerschool.hi-paris.fr/))

<div class="button-container"> 
  <a href="https://atulya-jain.github.io/files/calibration.pdf" download class="button">PDF</a>
  <a href="https://atulya-jain.github.io/files/poster-calibration.pdf" download class="button">Poster</a>
</div>


<details>
    <summary>Abstract</summary>
  
  How should an expert send forecasts to maximize her payoff given she has to pass a calibration test? We consider a dynamic game where an expert sends probability forecasts to a decision-maker. The decision-maker, based on  past outcomes, verifies the claims of the expert using the calibration test.  We find the optimal forecasting strategy by reducing the dynamic  game in terms of a static persuasion problem for the class of stationary ergodic processes.  We characterize the value of expertise by showing that an informed expert can achieve the best outcome in the persuasion problem, while an uninformed expert can only achieve the worst. We also compare the calibration test and regret minimization as heuristics for decision-making. We show that an expert can always guarantee the calibration benchmark and in some instances, she can guarantee strictly more. 

  </details>






- Are Bayesian persuasion outcomes efficient? (with Itai Arieli, Yakov Babichenko and Rann Smorodinsky)

    <details>
    <summary>Abstract</summary>
  

Information transmission between players with asymmetric information can improve outcomes and lead to efficiency. We consider the model of Bayesian persuasion: a sender commits to a signaling policy to persuade an uninformed receiver. We analyze the Pareto efficiency of the equilibrium outcome and provide a necessary condition for it. Using a natural class of games, we show that efficiency is non-trivial and difficult to attain.

  </details>


- Dynamic Cheap Talk with no feedback

    <details>
    <summary>Abstract</summary>
  

     I study a dynamic sender-receiver game, where the sequence of states follows an irreducible Markov chain. The sender provides valuable information but gets no feedback on the receiver’s actions. Under certain assumptions, I characterize the set of uniform equilibrium payoffs. I show that the sender benefits from the dynamic interaction, even without feedback.  The  interaction can restore commitment but only partially.  The sender can attain any outcome where she cannot profit by altering her signals while keeping the marginal distribution of signals  unchanged.  If the sender's payoff is state-independent, she can achieve the commitment benchmark  of  Bayesian  Persuasion.

  </details>


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
