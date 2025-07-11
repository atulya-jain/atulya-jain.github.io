---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---



- <a href="https://atulya-jain.github.io/files/jmp_jain.pdf"> Informing agents amidst biased narratives </a>  

  <details>
    <summary>Abstract</summary>
  
   I study the strategic interaction between a benevolent sender (who provides data) and a biased narrator (who interprets data) who compete to persuade a boundedly rational receiver (who takes action). The receiver does not know the data-generating model. She chooses between
models provided by the sender and the narrator using the maximum likelihood principle, selecting the one that best fits the data given her prior belief. The sender faces a trade-off between providing precise information and minimizing misinterpretation. Surprisingly, full disclosure
can be suboptimal and even backfire. I identify a finite set of models that contain the optimal data-generating model, which maximizes the receiver’s expected utility. The sender can guarantee non-negative value of information, preventing harm from misinterpretation. I apply this framework to information campaigns and employee feedback.

  </details>

<!-- <a href="https://vianney.ai/"> Vianney Perchet </a>  <a href="https://iarieli.net.technion.ac.il/"> <a href="https://yakovbabichenko.net.technion.ac.il/"> <a href="https://web.iem.technion.ac.il/site/academicstaff/rann-smorodinsky/">  -->

- <a href="https://atulya-jain.github.io/files/calibration.pdf"> Calibrated Forecasting and Persuasion </a>  (with Vianney Perchet)    <a href="https://atulya-jain.github.io/files/poster-calibration.pdf" download class="button">Poster</a>

   (Extended abstract at EC'24)

   



  <details>
      <summary>Abstract</summary>
    
  How should an expert send forecasts to maximize her payoff given that she has to pass a calibration test? We consider a dynamic game where an expert sends probability forecasts to a decision-maker. The decision-maker, based on  past outcomes, verifies the claims of the expert using the calibration test.  We find the optimal forecasting strategy by reducing the dynamic  game in terms of a static persuasion problem for the class of stationary ergodic processes.  We characterize the value of expertise by showing that an informed expert can achieve the best outcome in the persuasion problem, while an uninformed expert can only achieve the uninformative outcome. We also compare the calibration test and regret minimization as heuristics for decision-making. We show that an expert can always guarantee the calibration benchmark and in some instances, she can guarantee strictly more. 

    </details>






- When Does Communication Lead to Efficiency? (with Itai Arieli, Yakov Babichenko and Rann Smorodinsky)

    <details>
      <summary>Abstract</summary>
  

  We study a sender-receiver model where the sender chooses a signaling policy to influence the receiver's action. We classify outcomes by the number of actions taken in each state and show that an outcome is generically Pareto efficient only if it is pure or quasi-pure. We then analyze the conditions under which equilibrium outcomes in cheap talk and Bayesian persuasion can be efficient. A cheap talk outcome is generically efficient only if it is pure. Moreover, when the sender’s preferences are state-independent, a cheap talk outcome is efficient if and only if it induces the sender's most preferred action with certainty. In a natural class of buyer-seller scenarios, we show that the Bayesian persuasion outcome is inefficient across a large range of priors and preferences.

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
