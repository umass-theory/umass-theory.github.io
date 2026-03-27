---
layout: seminar
title: Theory Seminar
---
Welcome to the Spring 2026 series of the **University of Massachusetts Computer Science Theory Seminar**. The seminar is **4-5 pm on Tuesdays** in **Room 140, in the Computer Science Building (CSB) at UMass Amherst**, and is free and open to the public. The faculty host this semester is [Cameron Musco](https://people.cs.umass.edu/~cmusco/). If you are interested in giving a talk, please email the faculty host, or [Adam Lechowicz](https://adamlechowicz.github.io/#contact). Note that in addition to being a public lecture series, this is also a one-credit graduate seminar (**CompSci 891M**) that can be taken repeatedly for credit.

<hr>

<hr>

#### Spring 2026 Schedule of Speakers

**NOTE:** In order to ensure you get weekly updates for all the talks, please make sure you are part of the **seminars@cs.umass.edu** mailing list. If you wish to give a talk, or would like to nominate someone to give one, please email us to let us know!

<hr>

##### Organizational Meeting
*Tuesday, February 3 @ 4pm*

<hr>

##### Double Header: Fairness in the k-Server Problem and The Secretary Problem with Predictions and a Chosen Order

[Mohammadreza Daneshvaramoli](https://moreda-a.github.io/) --  *Tuesday, February 10 @ 4pm*
<details markdown="1">
<summary>Abstract </summary>
**Part 1:** We formalize fairness for the $$k$$-server problem via $$(\alpha,\beta)$$-fairness: each server's cost is at most an $$\alpha/k$$ fraction of the total plus $$\beta$$. We show fairness can be achieved without losing competitiveness.
Offline, we transform any optimal solution into a fair one with $$\alpha=1+\epsilon$$ and $$\beta=O(diam \cdot \log k/\epsilon)$$ while incurring only an additive $$O(diam \cdot k\log k/\epsilon)$$ cost.
Online, we convert any competitive algorithm into a randomized algorithm that is fair with high probability against an oblivious adversary, with only a small competitiveness loss.
We also analyze classics: DCA is fair on lines and on trees for $$k=2$$ but fails on general trees; on paging, FIFO is fair and marking algorithms (including LRU) satisfy a weaker fairness notion.

**Part 2:** We study the secretary problem with value predictions in both the standard random-order model (ROSP) and a learning-augmented model where the decision-maker can choose the arrival order based on predictions (COSP). We design a randomized algorithm that trusts predictions unless a large deviation is detected, then switches to a threshold rule.
If $$\epsilon\in[0,1]$$ bounds the multiplicative prediction error, we obtain competitive ratio $$\max\{0.221,\frac{1-\epsilon}{1+\epsilon}\}$$ for ROSP (improving [Fujii Yoshida '23]) and $$\max\{0.262,\frac{1-\epsilon}{1+\epsilon}\}$$ for COSP, demonstrating the benefit of combining predictions with arrival-order control.
</details>
<details markdown="1">
<summary>Bio</summary>

</details>

<hr>

##### Characterizing Strong Proofs Systems via Total Search Problems

[Stefan Grosser](https://blog.catalangrenade.com/p/about.html) (McGill) --  *Tuesday, February 17 @ 4pm*
<details markdown="1">
<summary>Abstract</summary>
In 1929, Gödel proved his celebrated completeness theorem, showing that in first-order logic a statement is true if and only if it has a finite proof. Exactly fifty years later, Cook and Reckhow asked whether a stronger phenomenon might hold in propositional logic: is there a fixed proof system—such as the sequent calculus or ZFC—in which every tautology admits a short proof? Equivalently, does NP = coNP? This question lies at the heart of propositional proof complexity, whose central goal is to show that for every proof system there exist tautologies that require exponentially long proofs.

In this talk, we survey a recent and successful line of work in proof complexity that connects the strength of proof systems to the complexity of combinatorial search problems. We will see how short proofs correspond to efficient algorithms (and conversely), and how this connection has been used to obtain new lower bounds in both proof complexity and circuit complexity. This talk is based on joint work with Noah Fleming, Toniann Pitassi, and Robert Robere.
</details>
<details markdown="1">
<summary>Bio</summary>

Stefan is a fifth year PhD student at McGill University, advised by Robert Robere. His research is in computational complexity, with a focus on proof complexity and circuit lower bounds. 

Previously, Stefan received his bachelor's in computer science from UMass Amherst, and his Masters in mathematics from McGill. 

</details>

<hr>

#####  Adversarial Online Learning with Limited Feedback and Memory

[Chen Wang](https://sites.google.com/view/chen-wang/home) (RPI) -- *Tuesday, February 24 @ 4pm*
<details markdown="1">
<summary>Abstract</summary>

While classical MWU and EXP3 algorithms for online learning and adversarial bandits achieve sqrt{T} poly(n) regret, they require O(n log(T)) space to implement, which is inefficient for modern large-scale applications. Recent work by Srinivas et al. [STOC’22]; Peng and Zhang [SODA’23]; Peng and Rubinstein [FOCS’23] has established polylogarithmic memory algorithms for the full-feedback setting (q=n, where q is the number of experts/bandits we can query at each step), but the limited feedback case ($$q < n$$) remains open.

In this talk, we present the first algorithms to achieve $$o(T)$$ regret with $$o(n)$$ memory for $$q < n$$. In fact, all of our algorithms only require $$polylog(nT)$$ memory. Our results include: (i) a $$T^{2/3}$$ regret bound for the $$q=1$$ bandit case, and the bound can be improved to the optimal $$\sqrt{nT}$$ under random-order losses; (ii) a near-optimal $$\sqrt{nT}$$ regret bound for $$q=2$$; and (iii) generalizations to interval regret and sliding-window models. Our main techniques include using the estimated losses of the bandits for pool management and the separation of exploration and exploitation to remove dependency for boosting. These techniques might be of independent interest for the broader theory community. 

Based on a joint work with Vladimir Braverman, Sumegha Garg, David P. Woodruff, and Samson Zhou (SODA 2026).

</details>
<details markdown="1">
<summary>Bio</summary>

TBD

</details>

<hr>

##### Keeping the World Connected: Building a Faster, Smarter, and Greener Internet

[Ramesh Sitaraman ](https://groups.cs.umass.edu/ramesh/) (UMass Amherst) -- *Tuesday, March 3 @ 4pm.* **Distinguished University Professor Lecture, Great Hall, Old Chapel**
<details markdown="1">
<summary>Abstract</summary>
  
TBD

</details>
<details markdown="1">
<summary>Bio</summary>

TBD

</details>

<hr>

##### On the Interplay Between Combinatorics and Geometry in Beyond-Planar Graphs

[Myroslav Kryven](https://myroslavkryven.gitlab.io/website/) (Amherst College) -- *Tuesday, March 10 @ 4pm*
<details markdown="1">
<summary>Abstract</summary>
  
Edge crossings are the dominant source of visual clutter in graph drawings and are known to significantly hinder readability. A core goal in graph visualization is therefore to reduce the impact of crossings on the drawing. This is one of the fundamental problems in Computer Science, which, unfortunately, does not have a good solution for dense graphs, where many crossings are unavoidable. Beyond-planar graph theory attempts to classify graphs that do admit drawings in which crossings are limited in some way. In this talk, we focus on two prominent such families: k-planar graphs, that have drawings in which each edge is crossed at most k times (a purely combinatorial constraint), and right-angle crossing (RAC) graphs, that have drawings in which all crossings occur at a right angle (a geometric constraint that helps distinguish crossings easier). Although these classes are defined by very different principles, we will present a surprising relationship between them.

</details>
<details markdown="1">
<summary>Bio</summary>

Myroslav Kryven is an Assistant Professor of Computer Science at Amherst College. His research lies at the intersection of theoretical and applied computer science, with interests in network visualization, parameterized algorithms, computational geometry, and pursuit–evasion games.

Previously, Myroslav was a postdoctoral researcher at the GADA Lab in the Department of Computer Science at the University of Manitoba, working with Stephane Durocher. Before that, he held postdoctoral positions at the University of Arizona with Stephen Kobourov and at the University of Würzburg with Alexander Wolff.

He earned his PhD in Network Visualization from the University of Würzburg (2016–2020), supervised by Alexander Wolff.

</details>
<hr>

##### No Meeting -- Spring Break
*Tuesday, March 17 @ 4pm*

<hr>

##### Pebble Games and Logic

[Rik Sengupta](https://people.cs.umass.edu/~rsengupta/) (IBM Research) -- *Tuesday, March 24 @ 4pm*
<details markdown="1">
<summary>Abstract</summary>
  
Two-player combinatorial games have been used for decades to capture syntactic properties of formal logical languages. For instance, the widely used Ehrenfeucht-Fraïssé (EF) game captures the quantifier rank of first-order formulas. Quite surprisingly, these and related games show up in unexpected places in both upper and lower bound proofs in complexity and finite model theory. In this talk, I’ll give an overview of some of these games, and then go deeper into a related (and natural) decision problem about them.

</details>
<details markdown="1">
<summary>Bio</summary>

Rik Sengupta is a Research Scientist at IBM Research in Cambridge, MA, where he specializes in complexity theory, algorithms, and optimization. He is a recent alumnus of UMass, where he completed his Ph.D. in Computer Science in 2024 under Andrew McGregor and Neil Immerman.

</details>

<hr>


##### Optimizing Multiserver Scheduling: Beyond SRPT-k

[Izzy Grosof](https://isaacg1.github.io/) (Northwestern) -- *Tuesday, March 31 @ 4pm*
<details markdown="1" open="1">
<summary>Abstract</summary>
  
Shortest Remaining Processing Time (SRPT) is a simple and compelling scheduling policy: Run the jobs that are nearest to completion. It has long been known to optimize mean response time with one server, and heavy-traffic mean response time with many servers. But is it optimal? No!

I present the first policy to improve beyond multiserver SRPT: SRPT-Except-k+1 (SEK), which always outperforms basic multiserver SRPT [1]. The proof uses a novel combination of change-from-baseline analysis, stochastic analysis, and worst-case analysis.

To measure SEK's progress towards the true optimal policy, I also present state-of-the-art lower bounds on optimal mean response time, based on the WINE formula and new analysis of the Increasing Speed Queue [2].

**Papers:**

[1]: "Outperforming Multiserver SRPT at All Loads". Izzy Grosof and Daniela Hurtado-Lange. To appear at ACM SIGMETRICS 2026.

[2]: "Novel Lower Bounds on M/G/k Scheduling". Ziyuan Wang and Isaac Grosof. Under submission.

</details>
<details markdown="1" open="1">
<summary>Bio</summary>

Izzy Grosof is an Assistant Professor at Northwestern University, studying stochastic queueing theory, especially multiserver scheduling theory, with applications to computing systems. Their research has received Best Paper and Best Dissertation awards from INFORMS, ACM SIGMETRICS, and IFIP Performance, and their teaching has received multiple awards at Northwestern. She received her PhD from Carnegie Mellon University, advised by Prof. Mor Harchol-Balter.

</details>

<hr>

##### TBD

[Rikhav Shah](https://math.berkeley.edu/~rdshah/) (MIT) -- *Tuesday, April 7 @ 4pm*

<details markdown="1">
<summary>Abstract</summary>
  
TBD

</details>
<details markdown="1">
<summary>Bio</summary>

TBD

</details>

<hr>

##### Sparsifying Intersections of Halfspaces

[Shivam Nadimpalli](https://math.mit.edu/~shivamn/) (MIT) -- *Tuesday, April 14 @ 4pm*
<details markdown="1">
<summary>Abstract</summary>
  
Given an intersection of (possibly infinitely many) halfspaces at bounded distance from the origin, we show that it can be sparsified, i.e. approximated (under the Gaussian distribution) by an intersection of halfspaces where the number of halfspaces depends only on the desired accuracy.  This yields efficient algorithms for learning, tolerant testing, and volume estimation of convex sets of bounded width.

Our result follows from a more general sparsification lemma for Gaussian processes, which relies on Talagrand's majorizing measures theorem. As another consequence, we obtain a "junta theorem" for norms over Gaussian space: Every norm over R^n can be multiplicatively approximated (under the Gaussian measure) by a norm that depends on only a constant number of coordinates.

The talk will be self-contained and will require no prior background on Gaussian processes. Based on joint work with Anindya De, Ryan O'Donnell, and Rocco Servedio that will appear in STOC 2026: [https://arxiv.org/abs/2411.14664](https://arxiv.org/abs/2411.14664). 

</details>
<details markdown="1">
<summary>Bio</summary>

TBD

</details>

<hr>

##### TBD

[Tiantian Gong](https://www.ttiangong.com/) (Yale) -- *Tuesday, April 21 @ 4pm*
<details markdown="1">
<summary>Abstract</summary>
  
TBD

</details>
<details markdown="1">
<summary>Bio</summary>

TBD

</details>

<hr>

##### TBD

[Neha Makhija](https://people.cs.umass.edu/~nehamakhija/) (UMass Amherst) -- *Tuesday, April 28 @ 4pm*
<details markdown="1">
<summary>Abstract</summary>
  
TBD

</details>
<details markdown="1">
<summary>Bio</summary>

TBD

</details>

<hr>

##### TBD

[Mordecai Golen]() (UMass Amherst) -- *Tuesday, May 5 @ 4pm*

<details markdown="1">
<summary>Abstract</summary>
  
TBD

</details>
<details markdown="1">
<summary>Bio</summary>

TBD

</details>

<hr>

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

#### Past Seminars Archive

[Fall 2025](https://theory.cs.umass.edu/seminar-f25)

[Spring 2025](https://theory.cs.umass.edu/seminar-s25)

[Fall 2024](https://theory.cs.umass.edu/seminar-f24)  

