---
layout: seminar
title: Theory Seminar
---
Welcome to the Fall 2024 series of the **University of Massachusetts Computer Science Theory Seminar**. The seminar is **4-5 pm on Thursdays** in **CS 140**, in the Computer Science Building at UMass Amherst, and is free and open to the public. The faculty host is [Hung Le](https://hunglvosu.github.io/). If you are interested in giving a talk, please email Professor Le or [Adam Lechowicz](https://adamlechowicz.github.io/#contact). Note that in addition to being a public lecture series, this is also a one-credit graduate seminar (**CompSci 891M**) that can be taken repeatedly for credit.

All Thursday talks are in **CS 140**, unless otherwise stated.

<hr>

<hr>

#### Fall 2024 Schedule of Speakers

**NOTE:** In order to ensure you get weekly updates for all the talks, please make sure you are part of the **seminars@cs.umass.edu** mailing list. If you wish to give a talk, or would like to nominate someone to give one, please email us to let us know!

<hr>

##### Strongly Tail-Optimal Scheduling in the Light-Tailed M/G/1

[Ziv Scully](https://ziv.codes/) (Cornell ORIE) --  *Thursday, September 5 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
We study the problem of scheduling jobs in a queueing system, specifically an M/G/1 with light-tailed job sizes, to asymptotically optimize the response time tail. For some time, the best known policy was First-Come First-Served (FCFS), which has an asymptotically exponential tail. FCFS achieves the optimal exponential decay rate, but its leading constant is suboptimal. Designing a policy that minimizes this leading constant is a long-standing open problem.  

We solve this open problem with a new scheduling policy called 𝛾-Boost. Roughly speaking, 𝛾-Boost operates similarly to FCFS, but it pretends that small jobs arrive earlier than their true arrival times. This reduces the response time of small jobs without unduly delaying large jobs. We prove 𝛾-Boost’s asymptotic tail optimality, and we show via simulation that 𝛾-Boost has excellent practical performance.  
 
The 𝛾-Boost policy as described above requires knowledge of job sizes. In preliminary work, we generalize 𝛾-Boost to work with unknown job sizes, proving an analogous asymptotic optimality result in the unknown-size setting. Our generalization reveals that 𝛾-Boost is a type of Gittins index policy, but with an unusual feature: it uses a negative discount rate.  
 

Joint work with George Yu (Cornell) and Amit Harlev (Cornell). 
</details>
<details markdown="1">
<summary>Bio</summary>

Ziv Scully is an assistant professor at Cornell ORIE (Operations Research and Information Engineering). He completed his PhD in Computer Science at CMU in 2022, advised by Mor Harchol-Balter and Guy Blelloch, and obtained his BS from MIT in 2016. Between graduating from CMU and starting at Cornell, Ziv was a research fellow at the UC Berkeley Simons Institute for the Data-Driven Decision Processes program; and then an NSF FODSI postdoc at Harvard SEAS and MIT CSAIL, mentored by Michael Mitzenmacher and Piotr Indyk.  
 

Broadly, Ziv researches the theory of decision making under uncertainty, including stochastic control, resource allocation, and performance evaluation. A particular emphasis of his work is scheduling and load balancing in queueing systems, as motivated by the needs of cloud computing data centers and service systems.  
 

Ziv’s work has been recognized by multiple awards from INFORMS, ACM SIGMETRICS, and IFIP PERFORMANCE, including most recently the SIGMETRICS 2024 Best Paper Award.
</details>

<hr>

##### Organizational Meeting

*Thursday, September 12 @ 4 pm*

<hr>

##### Lifting Uniform Learners via Distributional Decomposition

[Jane Lange](https://people.csail.mit.edu/jlange/) (MIT) --  *Thursday, September 19 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
We show how any PAC learning algorithm that works under the uniform distribution can be transformed, in a blackbox fashion, into one that works under an arbitrary and unknown distribution D. The efficiency of our transformation scales with the inherent complexity of D, running in poly(n, (md)^d) time for distributions over {±1}^n whose pmfs are computed by depth-d decision trees, where m is the sample complexity of the original algorithm. For monotone distributions our transformation uses only samples from D, and for general ones it uses subcube conditioning samples. A key technical ingredient is an algorithm which, given the aforementioned access to D, produces an optimal decision tree decomposition of D: an approximation of D as a mixture of uniform distributions over disjoint subcubes. With this decomposition in hand, we run the uniform-distribution learner on each subcube and combine the hypotheses using the decision tree. This algorithmic decomposition lemma also yields new algorithms for learning decision tree distributions with runtimes that exponentially improve on the prior state of the art—results of independent interest in distribution learning.

</details>

<hr>

##### Truthfulness of Calibration Measures

[Mingda Qiao](https://sites.google.com/site/acmonsterqiao/) (MIT) --  *Thursday, September 26 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
In sequential calibration, a forecaster makes probabilistic predictions on a sequence of T adversarially chosen binary outcomes. The predictions are called perfectly calibrated if, among the steps on which each value p in [0, 1] is predicted, exactly a p fraction of the outcomes are ones. Since perfectly calibrated forecasts are often unachievable, calibration measures have been introduced to quantify the deviation from perfect calibration. 

We initiate the study of the truthfulness of calibration measures. A calibration measure is said to be truthful if the forecaster (approximately) minimizes the expected penalty by predicting the conditional expectation of the next outcome, given the prior distribution of outcomes. Our main contribution is the introduction of a new calibration measure, termed the Subsampled Smooth Calibration Error (SSCE), under which truthful prediction is optimal up to a constant factor. In contrast, all the existing calibration measures are far from being truthful: there are simple distributions on which a polylogarithmic (or even zero) penalty is achievable, while truthful prediction leads to a polynomial penalty. 

Based on joint work with Nika Haghtalab, Kunhe Yang, Eric Zhao, and Letian Zheng. Papers available at [https://arxiv.org/abs/2402.07458](https://arxiv.org/abs/2402.07458), [https://arxiv.org/abs/2407.13979](https://arxiv.org/abs/2402.07458).
</details>

<hr>

##### Deterministic Expander Routing: Faster and More Versatile

[Hsin-Hao Su](https://sites.google.com/site/distributedhsinhao/home?authuser=0) (Boston College) --  *Thursday, October 3 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
In the expander routing problem, the goal is to route all the tokens to their destinations given that each vertex is the source and the destination of at most $\deg(v)$ tokens. Ghaffari, Kuhn, and Su (PODC 2017) developed randomized algorithms that solve this problem in $\poly(\phi^{-1}) \cdot 2^{O(\sqrt{\log n \log \log n})}$ rounds in the CONGEST model, where $\phi$ is the conductance of the graph. In addition, as noted by Chang, Pettie, Saranurak, and Zhang (JACM 2021), it is possible to obtain a preprocessing/query tradeoff so that the routing queries can be answered faster at the cost of more preprocessing time. The efficiency and flexibility of the processing/query tradeoff of expander routing have led to many other distributed algorithms in the CONGEST model, such as subpolynomial-round minimum spanning tree algorithms in expander graphs and near-optimal algorithms for $k$-clique enumeration in general graphs.

As the routing algorithm of Ghaffari, Kuhn, and Su and the subsequent improved algorithm by Ghaffari and Li (DISC 2018) are both randomized, all the resulting applications are also randomized. Recently, Chang and Saranurak (FOCS 2020) gave a deterministic algorithm that solves an expander routing instance in $2^{O(\log^{2/3} n \cdot \log^{1/3} \log n)}$ rounds. The deterministic algorithm is less efficient and does not allow preprocessing/query tradeoffs, which precludes the de-randomization of algorithms that require this feature, such as the aforementioned $k$-clique enumeration algorithm in general graphs.

In this talk, I will present a new deterministic expander routing algorithm that not only matches the randomized bound of Ghaffari, Kuhn, and Su but also allows preprocessing/query tradeoffs. Our algorithm solves a single instance of a routing query in $2^{O(\sqrt{\log n \cdot \log \log n})}$ rounds. For instance, this allows us to compute an MST in an expander graph in the same round complexity deterministically, improving the previous state-of-the-art $2^{O(\log^{2/3} n \cdot \log^{1/3} \log n)}$. Our algorithm achieves the following preprocessing and query tradeoffs: For $0 < \epsilon < 1$, we can answer every routing query in $\log^{O(1/\epsilon)} n$ rounds at the cost of a $(n^{O(\epsilon)} + \log^{O(1/\epsilon)} n)$-round preprocessing procedure. Combining this with the approach of Censor-Hillel, Leitersdorf, and Vulakh (PODC 2022), we obtain a near-optimal $\tilde{O}(n^{1-2/k})$-round deterministic algorithm for $k$-clique enumeration in general graphs, improving the previous state-of-the-art  $n^{1-2/k+o(1)}$.
</details>
<details markdown="1">
<summary>Bio</summary>

Hsin-Hao Su is an assistant professor in the computer science department at Boston College. His research interests lie in algorithms for combinatorial optimization problems in large-scale network settings, including distributed, parallel, and streaming settings. He obtained his Ph.D. from the University of Michigan under the supervision of Seth Pettie in 2015. His thesis, titled “Algorithms for Fundamental Problems in Computer Networks,” received the ACM-EATCS Principles of Distributed Computing Doctoral Dissertation Award. He did his postdoc at MIT with Nancy Lynch from 2015 to 2017.

</details>

<hr>

##### Gaussian Polytope Approximation

[Shivam Nadimpalli](https://math.mit.edu/~shivamn/) (MIT) --  *Thursday, October 10 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
We study the approximability of high-dimensional convex sets by intersections of halfspaces, where the approximation quality is measured with respect to the standard Gaussian distribution and the complexity of an approximation is the number of halfspaces used. 

We establish a range of upper and lower bounds both for general convex sets and for specific natural convex sets that are of particular interest. We rely on techniques from many different areas, including classical results from convex geometry, Cramér-type bounds from probability theory, and—perhaps surprisingly—a range of topics from computational complexity theory, including computational learning theory, unconditional pseudorandomness, and the study of influences and noise sensitivity in the analysis of Boolean functions. 

Based on joint work ([https://arxiv.org/abs/2311.08575](https://arxiv.org/abs/2311.08575)) with Anindya De and Rocco Servedio that will appear in FOCS 2024.

</details>
<details markdown="1">
<summary>Bio</summary>

Shivam Nadimpalli is a postdoc at MIT where he does research in analysis of Boolean functions, complexity theory, and property testing. He completed his PhD at Columbia under the supervision of Rocco Servedio and Mihalis Yannakakis. 

</details>

<hr>

##### Eliciting Honest Information from Authors Using Sequential Review

[Yichi Zhang](https://yichiz97.github.io/) (University of Michigan) --  *Thursday, October 17 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
In the setting of conference peer review, the conference aims to accept high-quality papers and reject low-quality papers based on noisy review scores. A recent work proposes the isotonic mechanism, which can elicit the ranking of paper qualities from an author with multiple submissions to help improve the conference’s decisions. However, the isotonic mechanism relies on the assumption that the author’s utility is both an increasing and a convex function with respect to the review score, which is often violated in peer review settings (e.g. when authors aim to maximize the number of accepted papers). In this paper, we propose a sequential review mechanism that can truthfully elicit the ranking information from authors while only assuming the agent’s utility is increasing with respect to the true quality of her accepted papers. The key idea is to review the papers of an author in a sequence based on the provided ranking and conditioning the review of the next paper on the review scores of the previous papers. Advantages of the sequential review mechanism include 1) eliciting truthful ranking information in a more realistic setting than prior work; 2) improving the quality of accepted papers, reducing the reviewing workload and increasing the average quality of papers being reviewed; 3) incentivizing authors to write fewer papers of higher quality.

Paper link: [https://arxiv.org/abs/2311.14619](https://arxiv.org/abs/2311.14619)


</details>
<details markdown="1">
<summary>Bio</summary>

Yichi Zhang is a Postdoctoral Researcher at DIMACS, Rutgers University, hosted by David Pennock and Lirong Xia. His research focuses on the intersection of computer science and economics, with particular interests in information elicitation and aggregation, mechanism design, multi-agent systems, and human-AI collaborations. He earned his Ph.D. from the University of Michigan in 2024, under the supervision of Grant Schoenebeck.

</details>

<hr>

##### Analyzing Federated Learning using a Game Theoretic Lens

[Kate Donahue](https://www.katedonahue.me) (MIT) --  *Thursday, October 24 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
Federated learning is a distributed learning paradigm where multiple agents, each only with access to local data, jointly learn a global model. There has recently been an explosion of research aiming not only to improve the accuracy rates of federated learning, but also provide certain guarantees around social good properties such as total error or fairness. In this talk, I describe three papers analyzing federated learning through the lens of cooperative game theory, all joint with Jon Kleinberg ([https://arxiv.org/abs/2010.00753](https://arxiv.org/abs/2010.00753), [https://arxiv.org/abs/2106.09580](https://arxiv.org/abs/2106.09580), [https://arxiv.org/abs/2112.00818](https://arxiv.org/abs/2112.00818))

In the first paper, we discuss fairness in federated learning, which relates to how error rates differ between federating agents. In this work, we consider two notions of fairness: egalitarian fairness (which aims to bound how dissimilar error rates can be) and proportional fairness (which aims to reward players for contributing more data). For egalitarian fairness, we obtain a tight multiplicative bound on how widely error rates can diverge between agents federating together. For proportional fairness, we show that sub-proportional error (relative to the number of data points contributed) is guaranteed for any individually rational federating coalition. The second paper explores optimality in federated learning with respect to an objective of minimizing the average error rate among federating agents. In this work, we provide and prove the correctness of an efficient algorithm to calculate an optimal (error minimizing) arrangement of players. This paper builds on our prior work on stability in federated learning, and allows us to give the first constant-factor bound on the performance gap between stability and optimality, proving that the total error of the worst stable solution can be no higher than 9 times the total error of an optimal solution (Price of Anarchy bound of 9).


</details>
<details markdown="1">
<summary>Bio</summary>

Kate Donahue is a MIT METEOR postdoc at MIT (mentored by Manish Raghavan) and starting fall '24 will be an assistant professor of CS at UIUC. She completed her PhD in CS at Cornell, where she was advised by Jon Kleinberg. She works on algorithmic problems relating to the societal impact of AI such as fairness, human/AI collaboration and game-theoretic models of federated learning and data sharing. Her work has been supported by an NSF fellowship and recognized by a FAccT Best Paper award. During her PhD, she interned at Amazon, Google, and Microsoft Research.

</details>

<hr>

##### Learning from Strategic Data Sources

[Han Shao](https://sites.google.com/view/hanshao) (Harvard) --  *Thursday, October 31 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
In contrast with standard classification tasks, strategic classification involves agents strategically modifying their features in an effort to receive favorable predictions. For instance, given a classifier determining loan approval based on credit scores, applicants may open or close their credit cards and bank accounts to fool the classifier. The learning goal is to find a classifier robust against strategic manipulations. Various settings, based on what and when information is known, have been explored in strategic classification. In this talk, I will focus on addressing a fundamental question: the learnability gaps between strategic classification and standard learning. This talk is based on joint work with Avrim Blum, Omar Montasser, Lee Cohen, Yishay Mansour, and Shay Moran ([arxiv.org/abs/2305.16501](arxiv.org/abs/2305.16501), [arxiv.org/abs/2402.19303](arxiv.org/abs/2402.19303)).

</details>
<details markdown="1">
<summary>Bio</summary>

Han Shao is a CMSA postdoc at Harvard, working with Cynthia Dwork and Ariel Procaccia. She will join the Department of Computer Science at the University of Maryland in Fall 2025 as an Assistant Professor. She completed her Ph.D. at TTIC, where she was advised by Avrim Blum. Her research focuses on the theoretical foundations of machine learning, particularly on fundamental questions arising from human social and adversarial behaviors in the learning process. She is interested in understanding how these behaviors affect machine learning systems and developing methods to enhance accuracy and robustness. Additionally, she is interested in gaining a theoretical understanding of empirical observations concerning adversarial robustness. Her work has been published in machine learning venues including NeurIPS, ICML, and COLT. In 2023, she was awarded EECS Rising Star by Georgia Tech and Rising Star in Machine Learning by the University of Maryland.

</details>

<hr>

##### Collusion in the Age of Algorithmic Agents

[Sampath Kannan](https://www.cis.upenn.edu/~kannan/) (UPenn) --  *Monday, November 4 @ 4 pm (SPECIAL TIME)*
<details markdown="1">
<summary>Abstract</summary>
  
Fair competition demands that sellers do not collude with each other in setting prices. But what does this mean? Prior work has shown that two sellers  can set supra-competitive prices and gain supra-competitive revenue by either encoding threats in their behavior, or by not optimizing their own payoffs. Moreover, reinforcement learning algorithms can learn such threat strategies on their own.

Here we show that supra-competitive prices can arise in seemingly innocuous settings, when no threats are being encoded, and each agent is playing optimally. In our model each of the two agents sets a price for a good at each point in time, and the agent setting the lower price sells the good. We show that if one of the agents uses a no-regret algorithm to set prices, and the other aproximately best responds, then both agents can get close to monopolistic profits, rather than the near-zero profit they should get under perfect competition. This suggests that it is non-trivial to define collusion in the age of algorithmic agents.

This talk will be self-contained and introduce the bits of game theory, online learning, and economics needed for understanding it.

The work is joint with Natalie Collina, Eshwar Arunachaleswaran, Aaron Roth, and Juba Ziani.

</details>
<details markdown="1">
<summary>Bio</summary>

Sampath Kannan is the associate director of the Simons Institute for the Theory of Computing and the Henry Salvatori Professor in the Department of Computer and Information Science at the University of Pennsylvania. His research interests are in the areas of Algorithmic Fairness, Combinatorial Algorithms, Program Reliability, Streaming Computation, and Computational Biology. Sampath served as Associate Dean for Academics in the School of Engineering and Applied Science at Penn between 2006 and 2008 and as Division Director for the Computing and Communication Foundations Division at the National Science Foundation from 2008 to 2010. He served as Associate Director for Theoretical Computer Science at the Simons Foundation from 2010 to 2013. He was the Chair of the Computer and Information Science Department at Penn between 2013 and 2018. He is a Fellow of the ACM, and the recipient of the ACM SIGACT Distinguished Service Award. He is also a Fellow of the American Association for the Advancement of Science.

</details>

<hr>

##### TBD

[Nikhil Vyas](https://nikhilvyas.github.io) (Harvard) --  *Thursday, November 7 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
Abstract TBA

</details>
<details markdown="1">
<summary>Bio</summary>

Bio TBA

</details>

<hr>

##### TBD

[TBA](https://groups.cs.umass.edu/theory/) (TBA) --  *Thursday, November 14 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
Abstract TBA

</details>
<details markdown="1">
<summary>Bio</summary>

Bio TBA

</details>

<hr>

##### TBD

[Andreas Maggiori](https://andreasr27.github.io/) (Columbia) --  *Thursday, November 21 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
Abstract TBA

</details>
<details markdown="1">
<summary>Bio</summary>

Bio TBA

</details>

<hr>

##### *No seminar (Thanksgiving Break)*

*Thursday, November 28 @ 4 pm*

<hr>

##### TBD

[Omer Wasim](https://www.khoury.northeastern.edu/people/omer-wasim/) (Northeastern) --  *Thursday, December 5 @ 4 pm*
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

[TBA](https://groups.cs.umass.edu/theory/) (TBA) --  *Thursday, October 24 @ 4 pm*
<details markdown="1">
<summary>Abstract</summary>
  
Abstract TBA

</details>
<details markdown="1">
<summary>Bio</summary>

Bio TBA

</details>

<hr> -->

