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

- <a href="https://atulya-jain.github.io/files/calibration.pdf"> Calibrated Forecasting and Persuasion</a>  (with Vianney Perchet)  <a href="https://atulya-jain.github.io/files/poster-calibration.pdf" download class="button">Poster</a>  [<b>New version</b>] 

   (Extended abstract at EC'24)

   



  <details>
      <summary>Abstract</summary>
    
  We study a dynamic game where an expert sends probabilistic forecasts to a decision-maker. The decision-maker verifies these forecasts using a calibration test based on past data. How should the expert send forecasts to maximize her payoff while passing the test? For a stationary ergodic process, we characterize the optimal forecasting strategy by reducing the dynamic game to a static persuasion problem. The distributions of forecasts that can arise under calibration are precisely the mean-preserving contractions of the distribution of conditionals. We compare the payoffs attainable by an informed and uninformed expert, providing a benchmark for the value of information. Finally, we consider a regret-minimizing decision-maker and show that the expert can always guarantee at least the calibration benchmark and sometimes strictly more.

  </details>






- <a href="https://atulya-jain.github.io/files/efficiency-incomplete-information.pdf">   Efficiency in Games with Incomplete Information</a>  (with Itai Arieli, Yakov Babichenko and Rann Smorodinsky)  <a href="https://atulya-jain.github.io/files/Efficiency30mins.pdf" download class="button">Slides</a>

    <details>
      <summary>Abstract</summary>
  

  We study games with incomplete information and characterize when a feasible outcome is Pareto efficient. Outcomes with excessive randomization are inefficient: generically, the total number of action profiles across states must be strictly less than the sum of the number of players and the number of states. We consider three applications. A cheap talk outcome is efficient only if pure; with state-independent sender payoffs, it is efficient if and only if the sender’s most preferred action is induced with certainty. In natural settings, Bayesian persuasion outcomes are inefficient across many priors. Finally, ranking-based allocation mechanisms are inefficient under mild conditions.

  </details>

- <a href="https://atulya-jain.github.io/files/inefficiency-social-learning.pdf">   On the Inefficiency of Social Learning</a>  (with Florian Brandl and Wanying (Kate) Huang)  

    <details>
      <summary>Abstract</summary>
  

     We study whether a social planner can improve the efficiency of learning, measured by the expected total welfare loss, in a sequential decision-making environment. Agents arrive in order and each makes a binary action based on their private signal and the social information they observe. The planner can intervene by jointly designing the social information disclosed to agents and offering monetary transfers contingent on agents’ actions. We show that, despite such flexibility, efficient learning cannot be restored with a finite budget: whenever learning is inefficient without intervention, no combination of information disclosure and transfers can achieve efficient learning while keeping total expected transfers finite.
  </details>


-  <a href="https://atulya-jain.github.io/files/dynamic-cheap-talk-without-feedback.pdf">  Dynamic Cheap Talk without Feedback</a>  

    <details>
    <summary>Abstract</summary>
      
     We study a dynamic sender-receiver game in which the state evolves according to a Markov chain observed by the sender, who does not observe the receiver’s action. Despite the absence of feedback, dynamic interaction partially restores commitment. We show that any equilibrium payoff of a persuasion model with partial commitments—where the sender can deviate only to signaling policies that preserve the marginal distribution over messages—as well as any convex combination of such payoffs across distributions over messages, can be achieved as a uniform equilibrium payoff in the dynamic game. When the sender's payoff is state-independent, she fully bridges the commitment gap and achieves the Bayesian persuasion payoff.
    </details>


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
