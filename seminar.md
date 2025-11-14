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
<details markdown="1">
<summary>Abstract</summary>
  
Many of the most important optimization problems in practice are massive in scale, mathematically complex, and involve numerous unknown parameters. Machine learning offers a powerful way to address these challenges by uncovering hidden structure and improving decision quality, but integrating predictions into algorithms raises fundamental questions: which architectures align with combinatorial structure, and how can we ensure robustness to error? This talk presents two case studies. First, we show how graph neural networks can approximate the optimal dynamic program for online matching, yielding algorithms that generalize across graph sizes and achieve strong empirical performance. Second, we introduce calibration as a principled interface between machine learning and decision-making, demonstrating through rent-or-buy and job scheduling problems that calibrated predictions yield both theoretical guarantees and practical improvements. Together, these results illustrate how learning can meaningfully augment algorithm design while retaining rigorous performance guarantees. This is joint work with Alexandre Hayderi, Amin Saberi, Anders Wikum, and Judy Hanwen Shen.

</details>
<details markdown="1">
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

##### Dynamic Matching with Post-allocation Service and its Application to Refugee Resettlement

[Vahideh Manshadi](https://vahideh-manshadi.com) (Yale) -- *Wednesday, October 8 @ noon*
<details markdown="1">
<summary>Abstract</summary>
  
Motivated by our collaboration with a major refugee resettlement agency in the U.S., we study a dynamic matching problem where each new arrival (a refugee case) must be matched immediately and irrevocably to one of the static resources (a location with a fixed annual quota). In addition to consuming the static resource, each case requires post-allocation services from a server, such as a translator. Given the uncertainty in service time, a server may not be available at a given time, thus we refer to it as a dynamic resource. Upon matching, the case will wait to avail service in a first-come-first-serve manner. Bursty matching to a location may result in undesirable congestion at its corresponding server. Consequently, the central planner (the agency) faces a dynamic matching problem with an objective that combines the matching reward (captured by pair-specific employment outcomes) with the cost for congestion for dynamic resources and over-allocation for the static ones. Motivated by the observed fluctuations in the composition of refugee pools across the years, we aim to design algorithms that do not rely on distributional knowledge. We develop learning-based algorithms that are asymptotically optimal in certain regimes, easy to interpret, and computationally fast. Our design is based on learning the dual variables of the underlying optimization problem; however, the main challenge lies in the time-varying nature of the dual variables associated with dynamic resources. Our theoretical development brings together techniques from Lyapunov analysis, adversarial online learning, and stochastic optimization. On the application side, when tested on real data from our partner agency and incorporating practical considerations, our method outperforms existing ones making it a viable candidate for replacing the current practice upon experimentation.

</details>
<hr>

##### Towards Instance Optimality in Online Decision-Making

[Sid Banerjee](https://sidbanerjee.orie.cornell.edu/) (Cornell) -- *Wednesday, October 15 @ noon*
<details markdown="1">
<summary>Abstract</summary>
  
Online decision-making is one of the most active research areas in computer science and operations research - these problems show up everywhere, and thanks to the ever present "curse-of-dimensionality", enable a constant stream of work on new models, algorithms, and performance metrics. The huge diversity in methodologies, however, means that these policies are hard to understand and compare. In practice, we would ideally like a policy that does *as well as possible for our given setting*; but is this possible?  

In this talk, I will try and present two case-studies based on my research that offers hope towards this goal. First, for a large class of "exchangeable action" problems (which includes several widely-studied settings including online resource-allocation, dynamic pricing, generalized assignment and online bin packing), I will present a class of simple greedy policies that, under stochastic inputs, get constant regret, i.e., have additive loss compared to the optimal solution in hindsight which is independent of the horizon and state-space. One downside of these policies is that their performance can be bad under certain adversarial inputs. To this end, for the simpler "online learning" setting (i.e., repeated decision-making problems with no intertemporal constraints and additive rewards), I will present a policy that in every instance can match (up to constant factors) the regret of both the above greedy policies as well as the minimax optimal policy, whichever is better for that given instance. In both cases, the resulting policies are surprisingly simple, despite beating the performance of complex state-of-the-art algorithms for widely studied problems. The magic behind this is in the use of new sample-path coupling approaches, and I will try to give examples in each case to illustrate these techniques.

</details>
<details markdown="1">
<summary>Bio</summary>

Sid Banerjee is an associate professor in the School of Operations Research at Cornell, working on topics at the intersection of data-driven decision-making, network algorithms and market design. His research is supported by grants from the NSF (including an NSF CAREER award), ARO, and AFOSR, and has received multiple awards including the INFORMS Applied Probability Society Best Publication award in 2021 and the Erlang Prize in 2022. He completed his PhD from the ECE Department at UT Austin, and was a postdoctoral researcher in the Social Algorithms Lab at Stanford. He also served as a technical consultant with the research science group at Lyft from 2014-18.

</details>

<hr>

##### Approximating High-Dimensional Earth Mover’s Distance as Fast as Closest Pair

[Lorenzo Berreta](https://lorenzo2beretta.github.io) (IBM Cambridge) -- *Wednesday, October 22 @ noon*
<details markdown="1">
<summary>Abstract</summary>
  
We give a reduction from $$(1+\epsilon)$$-approximate Earth Mover's Distance (EMD) to $$(1+\epsilon)$$-approximate Closest Pair. As a consequence, we improve the fastest known approximation algorithm for high-dimensional EMD. Here, given $$p\in [1, 2]$$ and two sets of $$n$$ points $$X,Y \subset (\R^d,\ell_p)$$, their EMD is the minimum cost of a perfect matching between $$X$$ and $$Y$$, where the cost of matching two vectors is their $$\ell_p$$ distance. Further, Closest Pair is the basic problem of finding a pair of points realizing $$\min_{x \in X, y\in Y} \Vert x-y \Vert_p$$.

</details>

<hr>

##### *No seminar*
*Wednesday, October 29*

<hr>

##### Risk-Sensitive Online Algorithms

[Nico Christianson](https://nicochristianson.com/) (Stanford) -- *Wednesday, November 5 @ noon* -- ***special location: CSL E400 (new building)***
<details markdown="1">
<summary>Abstract</summary>
  
Randomness can improve performance in many online decision-making problems. However, this improved performance is only obtained on average, exposing the decision-maker to potentially poor performance on any given run, which may be undesirable for agents which are sensitive to risks of a particular size or likelihood. Motivated by this challenge, we study the design of risk-sensitive online algorithms, in which risk measures are used in the competitive analysis of randomized online algorithms. We introduce a new performance metric, the CVaR$$_δ$$-Competitive Ratio, which compares the conditional value-at-risk of an algorithm's cost against the offline optimal cost, and we discuss the question of designing optimal algorithms for online ski rental and one-max search with this metric. We find that (near)-optimal algorithms for these problems can be obtained via the solution of certain delay differential equations, and the resulting performance bounds can exhibit phase transitions which highlight a fundamental limit to the power of randomization when decision-makers are sufficiently risk-sensitive. We will also discuss the application of this framework to the design of learning-augmented online algorithms.

</details>
<details markdown="1">
<summary>Bio</summary>

Nico Christianson is a Stanford Energy Postdoctoral Fellow and an incoming Assistant Professor of Computer Science at Johns Hopkins University (starting Fall 2026). His research lies broadly at the intersection of algorithms, machine learning, and optimization, with a specific emphasis on the development of new, theoretically-grounded algorithms and AI/ML methods for reliable decision-making under uncertainty. Much of his work is motivated by modern energy and sustainability challenges, with applications ranging from energy resource operation to sustainable computing systems. Nico received his PhD in computing and mathematical sciences at Caltech in 2025, where he was supported by an NSF Graduate Research Fellowship and a PIMCO Data Science Fellowship. His PhD dissertation won Caltech’s Ben P.C. Chou Doctoral Prize in Information Science and Technology and the Demetriades-Tsafka-Kokkalis Prize in Renewable Energy. Before Caltech, Nico received an AB in applied mathematics at Harvard College.

</details>

<hr>

##### Meta-Configurations Tracking: Machine Verifying Fast Multiprocess Data Structures

[Siddartha Jayanti](https://sites.google.com/view/siddhartha-jayanti/home?authuser=0) (Dartmouth) -- *Wednesday, November 12 @ noon*
<details markdown="1">
<summary>Abstract</summary>
  
As computing permeates our lives, the reliability of algorithms has become indispensable. Particularly challenging is the task of ensuring the reliability of concurrent data structures, which underlie the design of fast parallel algorithms for the modern multicores in our phones, laptops, and data center servers.

In this talk, I will describe some uses of concurrent data structures, motivate the need for their machine-verification, and describe an elegant technique for machine-verification of concurrent data structures, known as _meta-configuration tracking_ [Jayanti, Jayanti, Yavuz, Hernandez: ACM POPL 2024]. This technique is simple to use, requiring only forward reasoning, yet it is universal and complete, i.e., powerful enough to prove the correctness of even intricate data structures with future and far-future dependent linearization structures. We have used meta-configuration tracking to machine-verify impactful data structures, including: the Jayanti-Tarjan concurrent union-find data structure which enables "parallel clustering algorithms which scale to graphs with tens of billions of edges" at Google [received Google _Healthys_ Platinum Award], the ParlayHash data structure which is "the fastest concurrent hash table at Google" [received Google _Healthys_ Gold Award], and MemSnap which is a fast far-future dependent snapshot object [received ACM SPAA 2025 Distinguished Paper Award].

</details>
<details markdown="1">
<summary>Bio</summary>

Siddhartha Jayanti is an Assistant Professor of computer science at Dartmouth College, where he leads the Distributed Computing and Verification Lab. His research spans algorithms, verification, and applications with a focus on designing simple, fast, scalable, and reliable solutions to challenging multidisciplinary problems. Siddhartha's work has touched several areas of inquiry, including distributed computing, algorithms and data structures, verification, relativistic physics, economics, security, and machine learning. Prior to Dartmouth, Siddhartha worked as a research scientist at Google Research, where he designed and deployed fast and formally verified algorithms for large-scale data processing and clustering.

Siddhartha received his bachelor's from Princeton University, and his Masters and Ph.D. from MIT. His dissertation entitled _Simple, Fast, Scalable, and Reliable Multiprocessor Algorithms_, received the _2023 ACM-EATCS Principles of Distributed Computing Doctoral Dissertation Award_.

</details>

<hr>

##### Online Learning × Quantum Network: Foundations, Fusion, & Frontier

[Xuchuang Wang](https://xuchuangw.com/) (UMass) -- *Wednesday, November 19 @ noon*
<details markdown="1" open="1">
<summary>Abstract</summary>
  
Online learning (OL) theory examines how to make sequential decisions optimally, yet classical formulations often fall short when applied to complex, real-world systems. In the first part of this talk, I will introduce new algorithmic foundations that extend OL to multi-agent settings and to feedback models that better reflect practical constraints. In the second part, I will turn to quantum networks (QNs)—emerging infrastructures that enable the transmission of fragile quantum states over long distances—and discuss how to evaluate and optimize their performance.
Building on these foundations, I will highlight two recent works that illustrate a bidirectional synergy between OL and QNs: (1) how challenges in cutting-edge quantum networks motivate the development of more expressive and powerful online learning frameworks, and (2) how advances in OL theory, in turn, lead to more efficient, reliable algorithms for quantum network operation. I will conclude with a forward-looking discussion on the joint frontier of OL and QN, outlining potential pathways toward deployable quantum networks and robust multi-role agent systems.

</details>
<details markdown="1" open="1">
<summary>Bio</summary>

Xuchuang Wang is a postdoctoral researcher in the Manning College of Information & Computer Sciences at the University of Massachusetts Amherst, working with Don Towsley and Mohammad Hajiesmaili. He received his Ph.D. in Computer Science & Engineering from The Chinese University of Hong Kong, advised by John C.S. Lui. His research spans online learning theory, quantum networking systems, and the emerging intersection between the two. His interdisciplinary work has appeared in top-tier venues across machine learning, networking, and performance evaluation. His recent paper was selected as a Best Paper Finalist (top 5) at ACM SIGMETRICS 2025.

</details>

<hr>

##### *No seminar (Thanksgiving break)*
*Wednesday, November 26*

<hr>

##### Combinatorial Selection Models with Costly Information

[Dimitrios Christou](https://scholar.google.com/citations?user=t46iMM8AAAAJ&hl=en) (UT Austin) -- *Wednesday, December 3 @ noon*
<details markdown="1" open="1">
<summary>Abstract</summary>
  
We consider a class of optimization problems over stochastic variables where the algorithm can learn information about the value of any variable through a series of costly steps; we model this information acquisition process as a Markov Decision Process (MDP). The algorithm's goal is to maximize the value of its solution minus the cost of information acquisition under a selection constraint. Such bandit superprocesses have been studied previously but solutions are known only for fairly restrictive special cases and the problem is computationally challenging in general.

To address this challenge, previous approaches have turned to approximation algorithms by considering a restricted class of committing policies that simplify the decision-making aspects of the problem and allow for efficient optimization. This motivates the question of bounding the commitment gap, measuring the worst case ratio in the performance of the optimal committing policy and the overall optimal.

In this talk, we provide a unified framework for bounding the commitment gap by developing a bound on the utility of the overall optimal through a novel cost amortization technique. We then proceed to develop two different approaches for exploiting that bound. The first one is a local approximation condition that is established individually for each MDP and then composes into a (global) bound on the commitment gap. The second one relies on an ex ante relaxation of the objective and provides MDP-invariant bounds on the commitment gap that are related to the correlation gap of the underlying selection constraint. Both techniques provide improved bounds on the commitment gap and approximately optimal solutions to many costly information models, including different variants of the Pandora’s Box problem.

</details>
<details markdown="1" open="1">
<summary>Bio</summary>

Dimitrios (aka Dimitris) Christou is a 5th year Computer Science PhD student at UT Austin. He is fortunate to be advised by Prof. Shuchi Chawla. Prior to joining UT Austin, he received a Diploma in Electrical and Computer Engineering from the National Technical University of Athens. His research focuses on optimisation in uncertain environments and spans many areas, including the design of online algorithms, online-learning algorithms and data-driven algorithmic design. Recently, he has worked in problems in the intersection of Computer Science, Operations Research and Economics such as revenue maximization in online markets and costly-information models like bandit superprocesses.

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

