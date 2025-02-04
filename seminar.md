---
layout: seminar
title: Theory Seminar
---
Welcome to the Spring 2025 series of the **University of Massachusetts Computer Science Theory Seminar**. The seminar is **4-5 pm on Tuesdays** in **CS 140**, in the Computer Science Building at UMass Amherst, and is free and open to the public. The faculty host is [Yair Zick](https://people.cs.umass.edu/~yzick/). If you are interested in giving a talk, please email Professor Zick or [Adam Lechowicz](https://adamlechowicz.github.io/#contact). Note that in addition to being a public lecture series, this is also a one-credit graduate seminar (**CompSci 891M**) that can be taken repeatedly for credit.

All Tuesday talks are in **CS 140**, unless otherwise stated.

<hr>

<hr>

#### Spring 2025 Schedule of Speakers

**NOTE:** In order to ensure you get weekly updates for all the talks, please make sure you are part of the **seminars@cs.umass.edu** mailing list. If you wish to give a talk, or would like to nominate someone to give one, please email us to let us know!

<hr>

##### Organizational Meeting

*Tuesday, February 4 @ 4 pm*

<hr>


##### Optimality and Complexity in Decentralized Multi-agent Multi-armed Bandits

[Mengfan Xu](https://mengfanxu1997.github.io/) (UMass M&I Eng.) --  *Tuesday, February 11 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
We study the optimality and complexity of decentralized multi-agent multi-armed bandits (MA-MAB). We first consider MA-MAB in which multiple clients are connected by time dependent random graphs. The reward distributions of each arm vary across agents, including both sub-exponential and sub-Gaussian distributions. Each agent pulls an arm and communicates with neighbors based on the graph. The goal is to minimize the overall regret of the entire system through collaborations. To this end, we introduce a novel algorithmic framework, which first provides robust simulation methods for generating random graphs, and then combines an averaging-based consensus approach with a newly proposed weighting technique and the upper confidence bound to deliver a UCB-type solution. We derive instance-dependent and mean-gap regret upper bounds of order $$\log{T}$$ and $$\sqrt{T}\log T$$, respectively. While efficient algorithms with regret upper bounds have emerged, limited attention has been given to the corresponding regret lower bounds that characterizes the complexity of MA-MAB, except for a recent lower bound for adversarial settings, which, however, has a gap with let known upper bounds. To this end, we provide a study on regret lower bounds in different MA-MAB and establish their tightness. Specifically, for graphs with good connectivity properties and stochastic rewards, we demonstrate tight lower bounds $$O(\log T)$$ and $$\sqrt{T}$$ for instance-dependent and mean-gap bounds, respectively. Assuming adversarial rewards, we establish a lower bound $$O(T^{\frac{2}{3}})$$ for connected graphs, thereby bridging the gap between the lower and upper bound in the prior work. We also show a linear regret lower bound when the graph is disconnected.

</details>
<details markdown="1">
<summary>Bio</summary>

Mengfan Xu is an assistant professor in the Department of Mechanical and Industrial Engineering at UMass Amherst. Before joining UMass, she earned her Ph.D. in Operations Research from the Department of Industrial Engineering and Management Sciences at Northwestern University in 2024. Her research leverages statistical and mathematical tools to advance machine learning by developing novel formulations and provably effective algorithms, inspired by emerging real-world problems in operations research. Her research focuses on online and statistical learning, particularly multi-armed bandits and reinforcement learning, and their applications in various operations research problems, including supply chain management and healthcare. Her work has been recognized by top-tier machine learning conferences, including NeurIPS, ICML, AISTATS, and workshops at KDD and RLC. Beyond academia, she interned at LinkedIn in Summer 2023 and Didi Chuxing in 2021, where she worked on people recommendation using large language models and online dynamic pricing using causal inference, respectively.

</details>

<hr>

##### Pseudorandom Error-Correcting Codes with Applications to Watermarking Generative AI

[Miranda Christ](https://www.cs.columbia.edu/~mchrist/) (Columbia) --  *Tuesday, February 18 @ 4 pm*
<details markdown="1" open='1'>
<summary>Abstract</summary>
  
The rise of increasingly realistic generative models has necessitated tools for distinguishing between human-generated and AI-generated content. A promising approach is watermarking, where a hidden pattern is embedded in this AI-generated content. We introduce a powerful new framework for watermarking, which can be instantiated with a cryptographic primitive that we define, called a pseudorandom error-correcting code (PRC). While motivated by watermarking, a PRC is a natural cryptographic object of independent interest.

A PRC is an error-correcting code with the property that any polynomial number of codewords are pseudorandom to any efficient adversary. We construct PRCs from standard cryptographic assumptions, and in this talk I will give an overview of our construction relying on subexponential hardness of LPN. I will then show how PRCs yield LLM watermarks with strong quality and robustness guarantees.

This is based on works with Sam Gunn, Omar Alrabiah, Prabhanjan Ananth, and Yevgeniy Dodis: [https://eprint.iacr.org/2024/235.pdf](https://eprint.iacr.org/2024/235.pdf), [https://eprint.iacr.org/2024/1840](https://eprint.iacr.org/2024/1840)

</details>
<details markdown="1" open='1'>
<summary>Bio</summary>

Miranda Christ is a computer science PhD student at Columbia University, advised by Tal Malkin and Mihalis Yannakakis. She is a member of the Theory Group and the Crypto Lab. Her research is generally on theoretical cryptography, and recently has focused on the intersection of cryptography and machine learning.

</details>

<hr>

##### TBA

[Deeparnab Chakrabarty](https://www.cs.dartmouth.edu/~deepc/) (Dartmouth) --  *Tuesday, February 25 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
Abstract TBA

</details>
<details markdown="1">
<summary>Bio</summary>

Bio TBA

</details>

<hr>

##### TBA

[Manolis Zampetakis](https://mzampet.com/) (Yale) --  *Tuesday, March 4 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
Abstract TBA

</details>
<details markdown="1">
<summary>Bio</summary>

Bio TBA

</details>

<hr>

##### Equilibrium Computation in the Hotelling-Downs Model of Spatial Competition

[Soumyajit Pyne](https://sites.google.com/view/soumyajitpyne) (TIFR) --  *Tuesday, March 11 @ 4 pm*
<details markdown="1" open='1'>
<summary>Abstract</summary>
  
The Hotelling-Downs model is a natural and appealing model for understanding strategic positioning by candidates in elections. In this model, voters are distributed on a line, representing their ideological position on an issue. Each candidate then chooses as a strategy a position on the line to maximize her vote share. Each voter votes for the nearest candidate, closest to their ideological position. This sets up a game between the candidates, and we study pure Nash equilibria in this game. The model and its variants are an important tool in political economics, and are studied widely in computational social choice as well.

Despite the interest and practical relevance, most prior work focuses on the existence and properties of pure Nash equilibria in this model, ignoring computational issues. Our work gives algorithms for computing pure Nash equilibria in the basic model. We give three algorithms, depending on whether the distribution of voters is continuous or discrete, and similarly, whether the possible candidate positions are continuous or discrete. In each case, our algorithms return either an exact equilibrium or one arbitrarily close to exact, assuming existence. We believe our work will be useful, and may prompt interest, in computing equilibria in the wide variety of extensions of the basic model as well.

Arxiv link: [https://arxiv.org/abs/2412.12523](https://arxiv.org/abs/2412.12523)


</details>

<hr>

##### *No seminar (spring break)*

*Tuesday, March 18 @ 4 pm*

<hr>

##### TBA

[Mahsa Derakhshan](https://www.khoury.northeastern.edu/home/derakhshan/) (Northeastern) --  *Tuesday, March 25 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
Abstract TBA

</details>
<details markdown="1">
<summary>Bio</summary>

Bio TBA

</details>

<hr>

##### TBA

[TBA](TBA) (TBA) --  *Tuesday, April 1 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
Abstract TBA

</details>
<details markdown="1">
<summary>Bio</summary>

Bio TBA

</details>

<hr>

##### Sub-quadratic $$(1+\epsilon)$$-approximate Euclidean Spanners, with Applications

[Hengjie Zhang](https://www.cs.columbia.edu/~zhj/) (Columbia) --  *Tuesday, April 8 @ 4 pm*
<details markdown="1" open='1'>
<summary>Abstract</summary>
  
We study graph spanners for point-set in the high-dimensional Euclidean space. On the one hand, we prove that spanners with stretch $$<\sqrt{2}$$ and subquadratic size are not possible, even if we add Steiner points. On the other hand, if we add extra nodes to the graph (non-metric Steiner points), then we can obtain $$(1+\epsilon)$$-approximate spanners of subquadratic size. We show how to construct a spanner of size $$n^{2-\Omega(\epsilon^3)}$$, as well as a directed version of the spanner of size $$n^{2-\Omega(\epsilon^2)}$$.

We use our directed spanner to obtain an algorithm for computing $$(1+\epsilon)$$-approximation to Earth-Mover Distance (optimal transport) between two sets of size $$n$$ in time $$n^{2-\Omega(\epsilon^2)}$$.

</details>

<hr>

##### TBA

[Brendan Lucier](https://www.microsoft.com/en-us/research/people/brlucier/) (Microsoft Research) --  *Tuesday, April 15 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
Abstract TBA

</details>
<details markdown="1">
<summary>Bio</summary>

Bio TBA

</details>

<hr>

##### TBA

[Ariel Procaccia](http://procaccia.info/) (Harvard) --  *Tuesday, April 22 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
Abstract TBA

</details>
<details markdown="1">
<summary>Bio</summary>

Bio TBA

</details>

<hr>

##### TBA

[Emmanuele Viola](https://www.khoury.northeastern.edu/home/viola/) (Northeastern) --  *Tuesday, April 29 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
Abstract TBA

</details>
<details markdown="1">
<summary>Bio</summary>

Bio TBA

</details>

<hr>

##### TBA

[TBA](TBA) (TBA) --  *Tuesday, May 6 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
Abstract TBA

</details>
<details markdown="1">
<summary>Bio</summary>

Bio TBA

</details>

<hr>

<!-- ##### TBD

[TBA](https://groups.cs.umass.edu/theory/) (TBA) --  *Tuesday, October 24 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
Abstract TBA

</details>
<details markdown="1">
<summary>Bio</summary>

Bio TBA

</details>

<hr> -->

<hr>

#### Past Seminars Archive

[Fall 2024](https://theory.cs.umass.edu/seminar-f24)

