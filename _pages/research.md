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






- <a href="https://atulya-jain.github.io/files/WhenCommunicationEfficient.pdf">   When Does Communication Lead to Efficiency?</a>  (with Itai Arieli, Yakov Babichenko and Rann Smorodinsky)

    <details>
      <summary>Abstract</summary>
  

  We study games with incomplete information and characterize when a feasible outcome is Pareto efficient. We show that any outcome with excessive randomization over actions is inefficient. Generically, efficiency requires that the total number of actions taken across states be strictly less than the sum of the number of players and states. We then examine the efficiency of equilibrium outcomes in communication models. Generically, a cheap talk outcome is efficient only if it is pure. When the sender's payoff is state-independent, it is efficient if and only if the sender's most preferred action is chosen with certainty. In natural buyer-seller settings, Bayesian persuasion outcomes are inefficient across a wide range of priors and preferences. Finally, we show that our results apply to mechanism design problems with many players.


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
