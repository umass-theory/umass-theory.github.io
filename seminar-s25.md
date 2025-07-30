---
layout: seminar
title: Theory Seminar
---
This is an archive of the Spring 2025 series of the **University of Massachusetts Computer Science Theory Seminar**. The seminar was **4-5 pm on Tuesdays** in **CS 140**, in the Computer Science Building at UMass Amherst, and is free and open to the public. The faculty host was [Yair Zick](https://people.cs.umass.edu/~yzick/). 

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

[Miranda Christ](https://www.cs.columbia.edu/~mchrist/) (Columbia) --  *Tuesday, February 18 @ 4 pm ([virtual talk](https://umass-amherst.zoom.us/j/92005101364))*
<details markdown="1">
<summary>Abstract</summary>
  
The rise of increasingly realistic generative models has necessitated tools for distinguishing between human-generated and AI-generated content. A promising approach is watermarking, where a hidden pattern is embedded in this AI-generated content. We introduce a powerful new framework for watermarking, which can be instantiated with a cryptographic primitive that we define, called a pseudorandom error-correcting code (PRC). While motivated by watermarking, a PRC is a natural cryptographic object of independent interest.

A PRC is an error-correcting code with the property that any polynomial number of codewords are pseudorandom to any efficient adversary. We construct PRCs from standard cryptographic assumptions, and in this talk I will give an overview of our construction relying on subexponential hardness of LPN. I will then show how PRCs yield LLM watermarks with strong quality and robustness guarantees.

This is based on works with Sam Gunn, Omar Alrabiah, Prabhanjan Ananth, and Yevgeniy Dodis: [https://eprint.iacr.org/2024/235.pdf](https://eprint.iacr.org/2024/235.pdf), [https://eprint.iacr.org/2024/1840](https://eprint.iacr.org/2024/1840)

</details>
<details markdown="1">
<summary>Bio</summary>

Miranda Christ is a computer science PhD student at Columbia University, advised by Tal Malkin and Mihalis Yannakakis. She is a member of the Theory Group and the Crypto Lab. Her research is generally on theoretical cryptography, and recently has focused on the intersection of cryptography and machine learning.

</details>

<hr>

##### Representation Theory of Graph Isomorphism

[Jacob Urisman](https://www.linkedin.com/in/jurisman) (UMass) --  *Tuesday, February 25 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
The problem of Graph Isomorphism exists in a very strange place in the landscape of complexity theory under our current understanding. It is one of a very small number of problems that is known to be in NP but has not been proven to be either in P or NP-complete.

A promising, relatively new approach for problems in complexity theory has been using the algebraic tools commonly used in algebraic geometry and representation theory to see if they may shed new light on open problems. This led us to a natural motivating question: Can we use these tools to tackle Graph Isomorphism?

The talk will discuss some interesting results that have arisen from an approach to Graph Isomorphism using representation theory. This work is in collaboration with Dr. Joshua Grochow at CU Boulder.


</details>

<!-- ##### Some lower bounds on submodular function minimization

[Deeparnab Chakrabarty](https://www.cs.dartmouth.edu/~deepc/) (Dartmouth) --  *Tuesday, February 25 @ 4 pm*
<details markdown="1" open='1'>
<summary>Abstract</summary>
  
Submodular functions are set-functions which appear in many areas; for example, the graph cut function is a submodular function as a function of subset of vertices, and so is the “log-determinant” function as a function of rows/columns selected. It is quite a remarkable fact that one can find the unconditional minimizer of a general submodular function (called the SFM problem) in polynomially many queries, and this generalizes many fundamental combinatorial optimization problems like global minimum cut, s,t-cut, and even matroid intersection. What this polynomial dependence exactly is, is still not nailed down – it’s still between $$\thicksim n$$ to $$\thicksim n^2$$ (which is a big or small gap, depending on who one asks).

In this talk, I’d like to describe a few lower bounds. For most of the talk, I’ll focus on the “parallel complexity” of the problem – how many rounds-of-queries one needs to minimize a submodular function given the total number of queries is at most a polynomial? We will see that the answer is ~ n rounds! In doing so, we will also encounter the so-far best known example of query lower bound. Time permitting (perhaps not), I’d also like to talk about a few “upper bounds” for approximate SFM, and also some special cases of submodular functions (like graph cuts).
All this is based on multiple works with collaborators whose union is Yu Chen, Andrei Graur, Haotian Jiang, Sanjeev Khanna, Hang Liao and Aaron Sidford.

</details>
<details markdown="1" open='1'>
<summary>Bio</summary>

Deeparnab Chakrabarty is an associate professor at Dartmouth. Prior to this he was a researcher at Microsoft Research in Bangalore, India. He received his PhD from Georgia Institute of Technology. His research interests lie in the interplay of optimization and algorithm design, with a bent towards approximation and sublinear algorithms.

</details> -->

<hr>

##### Learning from Missing and Imperfect Data

[Manolis Zampetakis](https://mzampet.com/) (Yale) --  *Tuesday, March 4 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
Positive-Unlabeled (PU) learning enables classification when only positive and unlabeled data are available, a scenario common in bioinformatics, medical studies, and fraud detection. Its significance lies in learning from datasets where negative samples are difficult or costly to obtain. In this talk, we generalize PU learning to Positive and Imperfect Unlabeled (PIU) Learning. PIU Learning is a generalization of PU learning that accounts for poor-quality unlabeled data due to bias and adversarial corruption. This issue arises when we rely on public and crowdsourced sources to collect the unlabeled data.
Beyond its practical relevance, PIU Learning has deep theoretical implications. We show how it connects to fundamental problems, such as learning from smoothed distributions, detecting data truncation, and estimation under truncation—each central to statistics and learning theory. If time permits, we will also explore how PIU Learning provides a new perspective on causal inference in settings where standard assumptions, like overlap and unconfoundedness, break down.

Based on joined works with Jane Lee, Anay Mehrotra, Alkis Kalavasis, Katerina Mamali, and Yang Cai.


</details>
<details markdown="1">
<summary>Bio</summary>

Manolis Zampetakis is an Assistant Professor of Computer Science at Yale University working on the foundations of machine learning (ML), statistics, and data science, with focus on statistical analysis from biased and missing data, and optimization methods for multi-agent environments. Before Yale, Manolis was a post-doctoral researcher at the EECS Department of UC Berkeley. He received his PhD from the EECS Department at MIT where he was advised by Constantinos Daskalakis. He has been awarded the Google PhD Fellowship and the ACM SIGEcom Doctoral Dissertation Award.

</details>

<hr>

##### Equilibrium Computation in the Hotelling-Downs Model of Spatial Competition

[Soumyajit Pyne](https://sites.google.com/view/soumyajitpyne) (TIFR) --  *Tuesday, March 11 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
The Hotelling-Downs model is a natural and appealing model for understanding strategic positioning by candidates in elections. In this model, voters are distributed on a line, representing their ideological position on an issue. Each candidate then chooses as a strategy a position on the line to maximize her vote share. Each voter votes for the nearest candidate, closest to their ideological position. This sets up a game between the candidates, and we study pure Nash equilibria in this game. The model and its variants are an important tool in political economics, and are studied widely in computational social choice as well.

Despite the interest and practical relevance, most prior work focuses on the existence and properties of pure Nash equilibria in this model, ignoring computational issues. Our work gives algorithms for computing pure Nash equilibria in the basic model. We give three algorithms, depending on whether the distribution of voters is continuous or discrete, and similarly, whether the possible candidate positions are continuous or discrete. In each case, our algorithms return either an exact equilibrium or one arbitrarily close to exact, assuming existence. We believe our work will be useful, and may prompt interest, in computing equilibria in the wide variety of extensions of the basic model as well.

Arxiv link: [https://arxiv.org/abs/2412.12523](https://arxiv.org/abs/2412.12523)


</details>

<hr>

##### *No seminar (spring break)*

*Tuesday, March 18 @ 4 pm*

<hr>

##### Query Complexity of Stochastic Minimum Vertex Cover

[Mahsa Derakhshan](https://www.khoury.northeastern.edu/home/derakhshan/) (Northeastern) --  *Tuesday, March 25 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
In this talk, we explore the relationship between the query complexity of the stochastic minimum vertex cover problem and the density of Ruzsa–Szemerédi graphs. We are given an $$n$$-vertex graph $$G=(V,E)$$ and a (constant) existence probability for each edge. Each edge of $$G$$ is realized (i.e., it exists) independently with this probability, forming a realized subgraph $$G^\star$$. The presence or absence of an edge in $$G^\star$$ can be verified only via edge queries. Our goal is to find a near-optimal vertex cover of $$G^\star$$ using few queries.

We first show that under mild correlation among edge realizations, obtaining any approximation ratio better than $$1.5$$ requires querying a subgraph of size $$\Omega(n \text{RS}(n))$$. Here, $$\text{RS}(n)$$ refers to Ruzsa–Szemerédi graphs and represents the largest number of induced edge-disjoint matchings of size $$\Theta(n)$$ in an n-vertex graph. We then discuss a simple algorithm that finds a $$(1+\epsilon)$$-approximate vertex cover by querying a subgraph of size $$O(n \text{RS}(n))$$ for any absolute constant $$\epsilon >0$$. The analysis extends to the case of $$O(n \text{RS}(n))$$ correlated edges, effectively completing our understanding of this problem under mild correlation.

This talk is based on joint work with Nika Haghtalab and Naveen Durvasula (STOC’23), as well as Mohammad Saneian and Zhiyang Xun (ITCS’25).

</details>
<details markdown="1">
<summary>Bio</summary>

Mahsa Derakhshan is an assistant professor in the Khoury College of Computer Sciences at Northeastern University. Prior to that, she was a FODSI fellow at UC Berkeley and also a Postdoctoral Researcher at Princeton University in the Department of Computer Science.  She received her Ph.D. in Computer Science from the University of Maryland.

She is broadly interested in the design and analysis of algorithms. Mainly, she studies algorithms under uncertainty. A few sources of such uncertainty in her research are having stochastic data, limited access to information, and the presence of strategic behavior.  She primarily studies problems with applications to markets, such as matching markets and auctions.

</details>

<hr>

##### Some lower bounds on submodular function minimization

[Deeparnab Chakrabarty](https://www.cs.dartmouth.edu/~deepc/) (Dartmouth) -- *Tuesday, April 1 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
Submodular functions are set-functions which appear in many areas; for example, the graph cut function is a submodular function as a function of subset of vertices, and so is the “log-determinant” function as a function of rows/columns selected. It is quite a remarkable fact that one can find the unconditional minimizer of a general submodular function (called the SFM problem) in polynomially many queries, and this generalizes many fundamental combinatorial optimization problems like global minimum cut, s,t-cut, and even matroid intersection. What this polynomial dependence exactly is, is still not nailed down – it’s still between $$\thicksim n$$ to $$\thicksim n^2$$ (which is a big or small gap, depending on who one asks).

In this talk, I’d like to describe a few lower bounds. For most of the talk, I’ll focus on the “parallel complexity” of the problem – how many rounds-of-queries one needs to minimize a submodular function given the total number of queries is at most a polynomial? We will see that the answer is ~ n rounds! In doing so, we will also encounter the so-far best known example of query lower bound. Time permitting (perhaps not), I’d also like to talk about a few “upper bounds” for approximate SFM, and also some special cases of submodular functions (like graph cuts).
All this is based on multiple works with collaborators whose union is Yu Chen, Andrei Graur, Haotian Jiang, Sanjeev Khanna, Hang Liao and Aaron Sidford.

</details>
<details markdown="1">
<summary>Bio</summary>

Deeparnab Chakrabarty is an associate professor at Dartmouth. Prior to this he was a researcher at Microsoft Research in Bangalore, India. He received his PhD from Georgia Institute of Technology. His research interests lie in the interplay of optimization and algorithm design, with a bent towards approximation and sublinear algorithms.

</details>

<hr>

##### Sub-quadratic $$(1+\epsilon)$$-approximate Euclidean Spanners, with Applications

[Hengjie Zhang](https://www.cs.columbia.edu/~zhj/) (Columbia) --  *Tuesday, April 8 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
We study graph spanners for point-set in the high-dimensional Euclidean space. On the one hand, we prove that spanners with stretch $$<\sqrt{2}$$ and subquadratic size are not possible, even if we add Steiner points. On the other hand, if we add extra nodes to the graph (non-metric Steiner points), then we can obtain $$(1+\epsilon)$$-approximate spanners of subquadratic size. We show how to construct a spanner of size $$n^{2-\Omega(\epsilon^3)}$$, as well as a directed version of the spanner of size $$n^{2-\Omega(\epsilon^2)}$$.

We use our directed spanner to obtain an algorithm for computing $$(1+\epsilon)$$-approximation to Earth-Mover Distance (optimal transport) between two sets of size $$n$$ in time $$n^{2-\Omega(\epsilon^2)}$$.

</details>

<hr>

##### Market Impacts of AI Agents

[Brendan Lucier](https://www.microsoft.com/en-us/research/people/brlucier/) (Microsoft Research) --  *Tuesday, April 15 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
There is an increasing proliferation of AI-powered agents that can help optimize on a user's behalf. This includes algorithmic assistance embedded into online platforms, AI tools for worker productivity, and more. As automated assistance agents become increasingly common, how will users strategically maneuver their usage, and how does this influence the system design problems faced by firms and platforms?

In this talk we will address these questions through a game-theoretic lens. We will explore applications of strategic use of AI agents, from advertising auctions to task automation in the workplace. Viewing algorithmic agents as components of a broader system, we will discuss ways to analyze and optimize for aggregate performance.

Based on joint works with Mert Demirer, Yiding Feng, John Horton, Nicole Immorlica, Peyman Shahidi, and Alex Slivkins.

</details>
<details markdown="1">
<summary>Bio</summary>

Brendan Lucier is a Senior Principal Researcher at Microsoft Research New England in the Economics and Computation group. He received his PhD in Computer Science from the University of Toronto. Brendan’s research lies at the intersection of microeconomic theory and theoretical computer science. He uses tools from game theory, computation, and stochastic analysis to understand how the algorithms embedded in online platforms and other sociotechnical systems influence user behavior. He is especially interested in the ways that users interact with (and through) algorithms and how this informs market design. His research is motivated by applications such as digital advertising, matching markets, and markets for sustainability.

</details>

<hr>

##### Thoughts on P vs NP, correlation bounds, and all that.

[Emanuele “Manu” Viola](https://www.khoury.northeastern.edu/home/viola/) (Northeastern) --  *Tuesday, April 22 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
I will give a broad talk on the P vs NP problem, offering my
perspective on some of the history and the available results, and
discussing connections (some recent) between various models.  For
example I will discuss the fundamental bottleneck of proving correlation
bounds against low-degree polynomials.

</details>
<details markdown="1">
<summary>Bio</summary>

Emanuele "Manu" Viola is a former video game developer and a professor
of computer science at Northeastern University in Boston. Originally
from Rome, Italy, he earned a Laurea in computer science from La
Sapienza University in 2000, followed by a PhD in computer science from
Harvard University in 2006. He subsequently held postdoctoral positions
at the Institute for Advanced Study in Princeton and at Columbia University.

Viola's research spans several areas in theoretical computer science,
including pseudorandomness, cryptography, data structures, and
communication complexity. He also maintains a blog and wrote the book
"Mathematics of the Impossible."

</details>

<hr>

##### *No seminar*

*Tuesday, April 29 @ 4 pm*

<hr>

##### A Better-Than-1.6-Approximation for Prize-Collecting TSP

[Nathan Klein](https://nathan-klein.github.io/) (Boston U.) --  *Tuesday, May 6 @ 4 pm*
<details markdown="1" open='1'>
<summary>Abstract</summary>
  
We give a 1.599 approximation for the prize-collecting traveling salesperson problem (PCTSP), a variant of the traveling salesperson problem in which vertices can be excluded from the tour for an added penalty. This improves upon the recent 1.774 approximation of Blauth and Nägele. Our algorithm is quite simple, and similar to Christofides' algorithm for TSP: we first decompose the solution to the natural LP relaxation for PCTSP into a distribution over rooted trees. Then, we find the minimum cost matching on the odd vertices of the tree after performing a pruning step. It is open whether the analysis for our algorithm can be improved to 1.5 (a natural barrier for the problem). 

Based on joint work with Jannis Blauth and Martin Nägele.

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
