---
layout: seminar
title: Theory Seminar
---
Welcome to the Fall 2025 series of the **University of Massachusetts Computer Science Theory Seminar**. The seminar is **noon-1 pm on Wednesdays** in **LGRC A311**, in the Lederle Graduate Research Center (lowrise) at UMass Amherst, and is free and open to the public. The faculty hosts are [Mohammad Hajiesmaili](https://groups.cs.umass.edu/hajiesmaili/) and [Hedyeh Beyhaghi](https://hedyehbeyhaghi.github.io/). If you are interested in giving a talk, please email the faculty hosts, or [Adam Lechowicz](https://adamlechowicz.github.io/#contact). Note that in addition to being a public lecture series, this is also a one-credit graduate seminar (**CompSci 891M**) that can be taken repeatedly for credit.

All Wednesday talks are in **LGRC A311**, unless otherwise stated.

<hr>

<hr>

#### Fall 2025 Schedule of Speakers

**NOTE:** In order to ensure you get weekly updates for all the talks, please make sure you are part of the **seminars@cs.umass.edu** mailing list. If you wish to give a talk, or would like to nominate someone to give one, please email us to let us know!

<hr>

##### Organizational Meeting
*Wednesday, September 3 @ noon*

<hr>

##### Rethinking Information in Mechanism Design

[Divyarthi Mohan](https://www.divyarthimohan.com/) (Boston University) --  *Wednesday, September 10 @ noon*
<details markdown="1">
<summary>Abstract</summary>
  
Online markets and platforms have drastically shaped the algorithmic landscape into a complex ecosystem of strategic or self-interested entities. Hence, it is important to design algorithmic systems that are robust to strategic behavior and other informational uncertainties in order to guarantee desirable outcomes. In this talk, I will focus on my recent work that tackles three important challenges—uncertain decision making, strategic behavior, and interdependence—by using approximation algorithms to go beyond standard assumptions on information structures.

</details>
<details markdown="1">
<summary>Bio</summary>

Divyarthi Mohan is a postdoctoral researcher in the Faculty of Computing & Data Sciences at Boston University. Her research broadly lies at the intersection of computer science and economics, with a focus on algorithmic mechanisms design and the interplay of incentives and information. She obtained her PhD in Computer Science at Princeton University, advised by Matt Weinberg, and was previously a postdoctoral fellow at Tel Aviv University hosted by Michal Feldman. Her research has been recognized with the Simons-Berkeley Research Fellowship for Fall 2022, the class of 2021 Siebel Scholarship, and 2019 SEAS award of excellence at Princeton University, and her work was invited to the Highlights Beyond EC 2024.

</details>

<hr>

##### ML for discrete optimization: Theoretical foundations

[Ellen Vitercik](https://vitercik.github.io/) (Stanford) --  *Wednesday, September 17 @ noon*
<details markdown="1" open="1">
<summary>Abstract</summary>
  
Many of the most important optimization problems in practice are massive in scale, mathematically complex, and involve numerous unknown parameters. Machine learning offers a powerful way to address these challenges by uncovering hidden structure and improving decision quality, but integrating predictions into algorithms raises fundamental questions: which architectures align with combinatorial structure, and how can we ensure robustness to error? This talk presents two case studies. First, we show how graph neural networks can approximate the optimal dynamic program for online matching, yielding algorithms that generalize across graph sizes and achieve strong empirical performance. Second, we introduce calibration as a principled interface between machine learning and decision-making, demonstrating through rent-or-buy and job scheduling problems that calibrated predictions yield both theoretical guarantees and practical improvements. Together, these results illustrate how learning can meaningfully augment algorithm design while retaining rigorous performance guarantees. This is joint work with Alexandre Hayderi, Amin Saberi, Anders Wikum, and Judy Hanwen Shen.

</details>
<details markdown="1" open="1">
<summary>Bio</summary>

Ellen Vitercik is an Assistant Professor at Stanford University with a joint appointment between the Management Science & Engineering department and the Computer Science department. Her research interests include machine learning, algorithm design, discrete and combinatorial optimization, and the interface between economics and computation. Before joining Stanford, she spent a year as a Miller Postdoctoral Fellow at UC Berkeley and received a PhD in Computer Science from Carnegie Mellon University. Her research has been recognized with a Schmidt Sciences AI2050 Early Career Fellowship, an NSF CAREER award, the SIGecom Doctoral Dissertation Award, and the CMU School of Computer Science Distinguished Dissertation Award, among other honors.

</details>

<hr>

##### Learning and Games: A New Frontier in Algorithmic Game Theory

[Yang Cai](https://www.cs.yale.edu/homes/cai/) (Yale) -- *Wednesday, September 24 @ noon*
<details markdown="1">
<summary>Abstract</summary>
  
Over the past decade, machine learning has achieved remarkable progress across a wide range of applications. This success is largely attributable to the paradigm of training machine learning systems by minimizing a single loss function using gradient-descent-based optimization algorithms. However, the landscape is shifting, and many of the outstanding challenges in machine learning now lie at its intersection with game theory. These challenges arise either from explicitly strategic environments—such as multi-agent reinforcement learning systems, autobidding in auctions, and algorithmic pricing—or from problems that can be implicitly modeled as games, such as robustifying models against adversarial attacks, training generative models, and alignment.

These emerging problems present new challenges for both machine learning and game theory. On the one hand, it remains unclear what types of optimization algorithms are effective in these game-theoretic settings. On the other hand, the games arising from machine learning problems often involve non-concave utilities, whereas traditional game theory has largely focused on games with (quasi)-concave utilities. In this talk, we will discuss recent progress in tackling these challenges and explore the obstacles and opportunities that lie ahead for both machine learning and game theory.

</details>
<details markdown="1">
<summary>Bio</summary>

Yang Cai is a Professor of Computer Science and Economics (secondary appointment) at Yale University. He finished his Ph.D. at MIT in Computer Science under the supervision of Costis Daskalakis and received his B.Sc. in EECS at Peking University. His research interests lie in theoretical computer science and its interface with economics, optimization, and machine learning. His work has been recognized with the COLT Best Paper Award, the FOCS Test of Time Award, the Sloan Research Fellowship, the NSF CAREER Award, the William Dawson Scholarship, and the Simons-Berkeley Research Fellowship.

</details>

<hr>

##### Incentive-Aware Dynamic Resource Allocation under Long-Term Cost Constraints

[Yan Dai](https://yandaichn.github.io/) (MIT) -- *Wednesday, October 1 @ noon*
<details markdown="1">
<summary>Abstract</summary>
  
We consider the problem of dynamically allocating a reusable resource to strategic agents under long-term budget constraints, so that we simultaneously (i) maximize social welfare, (ii) satisfy multi-dimensional long-term cost constraints, and (iii) incentivize truthful reporting. Finding that primal-dual methods, widely used in constrained online optimization, are highly fragile in strategic settings, we develop an incentive-aware primal-dual framework achiving $$\tilde O(\sqrt T)$$ social welfare regret -- matching the non-strategic lower bound -- while being robust to strategic agents and adhering to all constraints. Technically, our primal side design features epoch-based lazy updates, dual-adjusted pricing rule, and randomized exploration rounds to fix agents' expectations about future and discourage misreporting. On the dual side, we carefully design a novel online learning technique -- which can be of independent interest -- to efficiently learn optimal duals despite lazy updates and strategic agents.

</details>
<details markdown="1">
<summary>Bio</summary>

Yan Dai is a 2nd-year PhD student in Operations Research at MIT, co-advised by Prof. Patrick Jaillet and Prof. Negin Golrezaei. His research focuses on developing robust mechanisms for strategic economic systems under incomplete information via an online learning toolbox. He also works on online learning topics like bandits or reinforcement learning. He belongs to the COLT, ICML, and NeurIPS community, and was recognized by a Best Paper award at SIGMETRICS 2025.

</details>

<hr>

##### Title TBA

[Vahideh Manshadi](https://vahideh-manshadi.com) (Yale) -- *Wednesday, October 8 @ noon*
<details markdown="1">
<summary>Abstract</summary>
  
TBA

</details>
<details markdown="1">
<summary>Bio</summary>

TBA

</details>

<hr>

##### Title TBA

[Sid Banerjee](https://sidbanerjee.orie.cornell.edu/) (Cornell) -- *Wednesday, October 15 @ noon*
<details markdown="1">
<summary>Abstract</summary>
  
TBA

</details>
<details markdown="1">
<summary>Bio</summary>

TBA

</details>

<hr>

##### Approximating High-Dimensional Earth Mover’s Distance as Fast as Closest Pair

[Lorenzo Berreta](https://lorenzo2beretta.github.io) (UC Santa Cruz) -- *Wednesday, October 22 @ noon*
<details markdown="1" open="1">
<summary>Abstract</summary>
  
We give a reduction from $$(1+\epsilon)$$-approximate Earth Mover's Distance (EMD) to $$(1+\epsilon)$$-approximate Closest Pair. As a consequence, we improve the fastest known approximation algorithm for high-dimensional EMD. Here, given $$p\in [1, 2]$$ and two sets of $$n$$ points $$X,Y \subset (\R^d,\ell_p)$$, their EMD is the minimum cost of a perfect matching between $$X$$ and $$Y$$, where the cost of matching two vectors is their $$\ell_p$$ distance. Further, Closest Pair is the basic problem of finding a pair of points realizing $$\min_{x \in X, y\in Y} \Vert x-y \Vert_p$$.

</details>

<hr>

##### Speaker TBA
*Wednesday, October 29 @ noon*
<details markdown="1">
<summary>Abstract</summary>
  
TBA

</details>
<details markdown="1">
<summary>Bio</summary>

TBA

</details>

<hr>

##### Title TBA

[Nico Christianson](https://nicochristianson.com/) (Stanford) -- *Wednesday, November 5 @ noon*
<details markdown="1">
<summary>Abstract</summary>
  
TBA

</details>
<details markdown="1">
<summary>Bio</summary>

TBA

</details>

<hr>

##### Speaker TBA
*Wednesday, November 12 @ noon*
<details markdown="1">
<summary>Abstract</summary>
  
TBA

</details>
<details markdown="1">
<summary>Bio</summary>

TBA

</details>

<hr>

##### Speaker TBA
*Wednesday, November 19 @ noon*
<details markdown="1">
<summary>Abstract</summary>
  
TBA

</details>
<details markdown="1">
<summary>Bio</summary>

TBA

</details>

<hr>

##### *No seminar (Thanksgiving break)*
*Wednesday, November 26*

<hr>

##### Title TBA

[Dimitrios Christou](https://scholar.google.com/citations?user=t46iMM8AAAAJ&hl=en) (UT Austin) -- *Wednesday, December 3 @ noon*
<details markdown="1">
<summary>Abstract</summary>
  
TBA

</details>
<details markdown="1">
<summary>Bio</summary>

TBA

</details>

<!-- ##### TBD

[TBA](https://groups.cs.umass.edu/theory/) (TBA) --  *Tuesday, October 24 @ noon*
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

[Spring 2025](https://theory.cs.umass.edu/seminar-s25)

