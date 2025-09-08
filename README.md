
<h2>2025-09</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.05265v1">On Evaluating the Poisoning Robustness of Federated Learning under Local
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-09-05T17:23:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zijian Wang, Wei Tong, Tingxuan Han, Haoyu Chen, Tianling Zhang, Yunlong Mao, Sheng Zhong</p>
    <p><b>Summary:</b> Federated learning (FL) combined with local differential privacy (LDP)
enables privacy-preserving model training across decentralized data sources.
However, the decentralized data-management paradigm leaves LDPFL vulnerable to
participants with malicious intent. The robustness of LDPFL protocols,
particularly against model poisoning attacks (MPA), where adversaries inject
malicious updates to disrupt global model convergence, remains insufficiently
studied. In this paper, we propose a novel and extensible model poisoning
attack framework tailored for LDPFL settings. Our approach is driven by the
objective of maximizing the global training loss while adhering to local
privacy constraints. To counter robust aggregation mechanisms such as
Multi-Krum and trimmed mean, we develop adaptive attacks that embed carefully
crafted constraints into a reverse training process, enabling evasion of these
defenses. We evaluate our framework across three representative LDPFL
protocols, three benchmark datasets, and two types of deep neural networks.
Additionally, we investigate the influence of data heterogeneity and privacy
budgets on attack effectiveness. Experimental results demonstrate that our
adaptive attacks can significantly degrade the performance of the global model,
revealing critical vulnerabilities and highlighting the need for more robust
LDPFL defense strategies against MPA. Our code is available at
https://github.com/ZiJW/LDPFL-Attack</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.05162v1">Verifiability and Privacy in Federated Learning through Context-Hiding
  Multi-Key Homomorphic Authenticators</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-09-05T14:57:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Simone Bottoni, Giulio Zizzo, Stefano Braghin, Alberto Trombetta</p>
    <p><b>Summary:</b> Federated Learning has rapidly expanded from its original inception to now
have a large body of research, several frameworks, and sold in a variety of
commercial offerings. Thus, its security and robustness is of significant
importance. There are many algorithms that provide robustness in the case of
malicious clients. However, the aggregator itself may behave maliciously, for
example, by biasing the model or tampering with the weights to weaken the
models privacy. In this work, we introduce a verifiable federated learning
protocol that enables clients to verify the correctness of the aggregators
computation without compromising the confidentiality of their updates. Our
protocol uses a standard secure aggregation technique to protect individual
model updates with a linearly homomorphic authenticator scheme that enables
efficient, privacy-preserving verification of the aggregated result. Our
construction ensures that clients can detect manipulation by the aggregator
while maintaining low computational overhead. We demonstrate that our approach
scales to large models, enabling verification over large neural networks with
millions of parameters.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.04919v1">Optimal Variance and Covariance Estimation under Differential Privacy in
  the Add-Remove Model and Beyond</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-09-05T08:37:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shokichi Takakura, Seng Pei Liew, Satoshi Hasegawa</p>
    <p><b>Summary:</b> In this paper, we study the problem of estimating the variance and covariance
of datasets under differential privacy in the add-remove model. While
estimation in the swap model has been extensively studied in the literature,
the add-remove model remains less explored and more challenging, as the dataset
size must also be kept private. To address this issue, we develop efficient
mechanisms for variance and covariance estimation based on the \emph{B\'{e}zier
mechanism}, a novel moment-release framework that leverages Bernstein bases. We
prove that our proposed mechanisms are minimax optimal in the high-privacy
regime by establishing new minimax lower bounds. Moreover, beyond worst-case
scenarios, we analyze instance-wise utility and show that the B\'{e}zier-based
estimator consistently achieves better utility compared to alternative
mechanisms. Finally, we demonstrate the effectiveness of the B\'{e}zier
mechanism beyond variance and covariance estimation, showcasing its
applicability to other statistical tasks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.04710v1">Network-Aware Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-09-04T23:53:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhou Li, Yu Zheng, Tianhao Wang, Sang-Woo Jun</p>
    <p><b>Summary:</b> Differential privacy (DP) is a privacy-enhancement technology (PET) that
receives prominent attention from the academia, industry, and government. One
main development over the past decade has been the decentralization of DP,
including local DP and shuffle DP. Despite that decentralized DP heavily relies
on network communications for data collection,we found that: 1) no systematic
study has surveyed the research opportunities at the intersection of networking
and DP; 2) nor have there been significant efforts to develop DP mechanisms
that are explicitly tailored for network environments. In this paper, we seek
to address this gap by initiating a new direction of network-aware DP. We
identified two focus areas where the network research can offer substantive
contributions to the design and deployment of DP, related to network security
and topology. Through this work, we hope to encourage more research that
adapt/optimize DP's deployment in various network environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.04358v1">Privacy Perceptions in Robot-Assisted Well-Being Coaching: Examining the
  Roles of Information Transparency, User Control, and Proactivity</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E">
  <p><b>Published on:</b> 2025-09-04T16:19:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Atikkhan Faridkhan Nilgar, Manuel Dietrich, Kristof Van Laerhoven</p>
    <p><b>Summary:</b> Social robots are increasingly recognized as valuable supporters in the field
of well-being coaching. They can function as independent coaches or provide
support alongside human coaches, and healthcare professionals. In coaching
interactions, these robots often handle sensitive information shared by users,
making privacy a relevant issue. Despite this, little is known about the
factors that shape users' privacy perceptions. This research aims to examine
three key factors systematically: (1) the transparency about information usage,
(2) the level of specific user control over how the robot uses their
information, and (3) the robot's behavioral approach - whether it acts
proactively or only responds on demand. Our results from an online study (N =
200) show that even when users grant the robot general access to personal data,
they additionally expect the ability to explicitly control how that information
is interpreted and shared during sessions. Experimental conditions that
provided such control received significantly higher ratings for perceived
privacy appropriateness and trust. Compared to user control, the effects of
transparency and proactivity on privacy appropriateness perception were low,
and we found no significant impact. The results suggest that merely informing
users or proactive sharing is insufficient without accompanying user control.
These insights underscore the need for further research on mechanisms that
allow users to manage robots' information processing and sharing, especially
when social robots take on more proactive roles alongside humans.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.04290v1">An Interactive Framework for Finding the Optimal Trade-off in
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-09-04T15:02:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yaohong Yang, Aki Rehn, Sammie Katt, Antti Honkela, Samuel Kaski</p>
    <p><b>Summary:</b> Differential privacy (DP) is the standard for privacy-preserving analysis,
and introduces a fundamental trade-off between privacy guarantees and model
performance. Selecting the optimal balance is a critical challenge that can be
framed as a multi-objective optimization (MOO) problem where one first
discovers the set of optimal trade-offs (the Pareto front) and then learns a
decision-maker's preference over them. While a rich body of work on interactive
MOO exists, the standard approach -- modeling the objective functions with
generic surrogates and learning preferences from simple pairwise feedback -- is
inefficient for DP because it fails to leverage the problem's unique structure:
a point on the Pareto front can be generated directly by maximizing accuracy
for a fixed privacy level. Motivated by this property, we first derive the
shape of the trade-off theoretically, which allows us to model the Pareto front
directly and efficiently. To address inefficiency in preference learning, we
replace pairwise comparisons with a more informative interaction. In
particular, we present the user with hypothetical trade-off curves and ask them
to pick their preferred trade-off. Our experiments on differentially private
logistic regression and deep transfer learning across six real-world datasets
show that our method converges to the optimal privacy-accuracy trade-off with
significantly less computational cost and user interaction than baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.04232v1">Rethinking Layer-wise Gaussian Noise Injection: Bridging Implicit
  Objectives and Privacy Budget Allocation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-09-04T14:09:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qifeng Tan, Shusen Yang, Xuebin Ren, Yikai Zhang</p>
    <p><b>Summary:</b> Layer-wise Gaussian mechanisms (LGM) enhance flexibility in differentially
private deep learning by injecting noise into partitioned gradient vectors.
However, existing methods often rely on heuristic noise allocation strategies,
lacking a rigorous understanding of their theoretical grounding in connecting
noise allocation to formal privacy-utility tradeoffs. In this paper, we present
a unified analytical framework that systematically connects layer-wise noise
injection strategies with their implicit optimization objectives and associated
privacy budget allocations. Our analysis reveals that several existing
approaches optimize ill-posed objectives -- either ignoring inter-layer
signal-to-noise ratio (SNR) consistency or leading to inefficient use of the
privacy budget. In response, we propose a SNR-Consistent noise allocation
strategy that unifies both aspects, yielding a noise allocation scheme that
achieves better signal preservation and more efficient privacy budget
utilization. Extensive experiments in both centralized and federated learning
settings demonstrate that our method consistently outperforms existing
allocation strategies, achieving better privacy-utility tradeoffs. Our
framework not only offers diagnostic insights into prior methods but also
provides theoretical guidance for designing adaptive and effective noise
injection schemes in deep models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.04169v1">Privacy Risks in Time Series Forecasting: User- and Record-Level
  Membership Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-09-04T12:43:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nicolas Johansson, Tobias Olsson, Daniel Nilsson, Johan Östman, Fazeleh Hoseini</p>
    <p><b>Summary:</b> Membership inference attacks (MIAs) aim to determine whether specific data
were used to train a model. While extensively studied on classification models,
their impact on time series forecasting remains largely unexplored. We address
this gap by introducing two new attacks: (i) an adaptation of multivariate
LiRA, a state-of-the-art MIA originally developed for classification models, to
the time-series forecasting setting, and (ii) a novel end-to-end learning
approach called Deep Time Series (DTS) attack. We benchmark these methods
against adapted versions of other leading attacks from the classification
setting.
  We evaluate all attacks in realistic settings on the TUH-EEG and ELD
datasets, targeting two strong forecasting architectures, LSTM and the
state-of-the-art N-HiTS, under both record- and user-level threat models. Our
results show that forecasting models are vulnerable, with user-level attacks
often achieving perfect detection. The proposed methods achieve the strongest
performance in several settings, establishing new baselines for privacy risk
assessment in time series forecasting. Furthermore, vulnerability increases
with longer prediction horizons and smaller training populations, echoing
trends observed in large language models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.03350v1">Exposing Privacy Risks in Anonymizing Clinical Data: Combinatorial
  Refinement Attacks on k-Anonymity Without Auxiliary Information</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-09-03T14:36:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Somiya Chhillar, Mary K. Righi, Rebecca E. Sutter, Evgenios M. Kornaropoulos</p>
    <p><b>Summary:</b> Despite longstanding criticism from the privacy community, k-anonymity
remains a widely used standard for data anonymization, mainly due to its
simplicity, regulatory alignment, and preservation of data utility. However,
non-experts often defend k-anonymity on the grounds that, in the absence of
auxiliary information, no known attacks can compromise its protections. In this
work, we refute this claim by introducing Combinatorial Refinement Attacks
(CRA), a new class of privacy attacks targeting k-anonymized datasets produced
using local recoding. This is the first method that does not rely on external
auxiliary information or assumptions about the underlying data distribution.
CRA leverages the utility-optimizing behavior of local recoding anonymization
of ARX, which is a widely used open-source software for anonymizing data in
clinical settings, to formulate a linear program that significantly reduces the
space of plausible sensitive values. To validate our findings, we partnered
with a network of free community health clinics, an environment where (1)
auxiliary information is indeed hard to find due to the population they serve
and (2) open-source k-anonymity solutions are attractive due to regulatory
obligations and limited resources. Our results on real-world clinical microdata
reveal that even in the absence of external information, established
anonymization frameworks do not deliver the promised level of privacy, raising
critical privacy concerns.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.03294v1">A Comprehensive Guide to Differential Privacy: From Theory to User
  Expectations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2025-09-03T13:23:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Napsu Karmitsa, Antti Airola, Tapio Pahikkala, Tinja Pitkämäki</p>
    <p><b>Summary:</b> The increasing availability of personal data has enabled significant advances
in fields such as machine learning, healthcare, and cybersecurity. However,
this data abundance also raises serious privacy concerns, especially in light
of powerful re-identification attacks and growing legal and ethical demands for
responsible data use. Differential privacy (DP) has emerged as a principled,
mathematically grounded framework for mitigating these risks. This review
provides a comprehensive survey of DP, covering its theoretical foundations,
practical mechanisms, and real-world applications. It explores key algorithmic
tools and domain-specific challenges - particularly in privacy-preserving
machine learning and synthetic data generation. The report also highlights
usability issues and the need for improved communication and transparency in DP
systems. Overall, the goal is to support informed adoption of DP by researchers
and practitioners navigating the evolving landscape of data privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.03024v1">Efficient Privacy-Preserving Recommendation on Sparse Data using Fully
  Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-09-03T05:15:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Moontaha Nishat Chowdhury, André Bauer, Minxuan Zhou</p>
    <p><b>Summary:</b> In today's data-driven world, recommendation systems personalize user
experiences across industries but rely on sensitive data, raising privacy
concerns. Fully homomorphic encryption (FHE) can secure these systems, but a
significant challenge in applying FHE to recommendation systems is efficiently
handling the inherently large and sparse user-item rating matrices. FHE
operations are computationally intensive, and naively processing various sparse
matrices in recommendation systems would be prohibitively expensive.
Additionally, the communication overhead between parties remains a critical
concern in encrypted domains. We propose a novel approach combining Compressed
Sparse Row (CSR) representation with FHE-based matrix factorization that
efficiently handles matrix sparsity in the encrypted domain while minimizing
communication costs. Our experimental results demonstrate high recommendation
accuracy with encrypted data while achieving the lowest communication costs,
effectively preserving user privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.02856v1">Managing Correlations in Data and Privacy Demand</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-09-02T22:03:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Syomantak Chaudhuri, Thomas A. Courtade</p>
    <p><b>Summary:</b> Previous works in the differential privacy literature that allow users to
choose their privacy levels typically operate under the heterogeneous
differential privacy (HDP) framework with the simplifying assumption that user
data and privacy levels are not correlated. Firstly, we demonstrate that the
standard HDP framework falls short when user data and privacy demands are
allowed to be correlated. Secondly, to address this shortcoming, we propose an
alternate framework, Add-remove Heterogeneous Differential Privacy (AHDP), that
jointly accounts for user data and privacy preference. We show that AHDP is
robust to possible correlations between data and privacy. Thirdly, we formalize
the guarantees of the proposed AHDP framework through an operational hypothesis
testing perspective. The hypothesis testing setup may be of independent
interest in analyzing other privacy frameworks as well. Fourthly, we show that
there exists non-trivial AHDP mechanisms that notably do not require prior
knowledge of the data-privacy correlations. We propose some such mechanisms and
apply them to core statistical tasks such as mean estimation, frequency
estimation, and linear regression. The proposed mechanisms are simple to
implement with minimal assumptions and modeling requirements, making them
attractive for real-world use. Finally, we empirically evaluate proposed AHDP
mechanisms, highlighting their trade-offs using LLM-generated synthetic
datasets, which we release for future research.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.02768v1">Sequential Change Detection with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> 
  <p><b>Published on:</b> 2025-09-02T19:15:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Liyan Xie, Ruizhi Zhang</p>
    <p><b>Summary:</b> Sequential change detection is a fundamental problem in statistics and signal
processing, with the CUSUM procedure widely used to achieve minimax detection
delay under a prescribed false-alarm rate when pre- and post-change
distributions are fully known. However, releasing CUSUM statistics and the
corresponding stopping time directly can compromise individual data privacy. We
therefore introduce a differentially private (DP) variant, called DP-CUSUM,
that injects calibrated Laplace noise into both the vanilla CUSUM statistics
and the detection threshold, preserving the recursive simplicity of the
classical CUSUM statistics while ensuring per-sample differential privacy. We
derive closed-form bounds on the average run length to false alarm and on the
worst-case average detection delay, explicitly characterizing the trade-off
among privacy level, false-alarm rate, and detection efficiency. Our
theoretical results imply that under a weak privacy constraint, our proposed
DP-CUSUM procedure achieves the same first-order asymptotic optimality as the
classical, non-private CUSUM procedure. Numerical simulations are conducted to
demonstrate the detection efficiency of our proposed DP-CUSUM under different
privacy constraints, and the results are consistent with our theoretical
findings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.02411v1">A Survey: Towards Privacy and Security in Mobile Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-09-02T15:19:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Honghui Xu, Kaiyang Li, Wei Chen, Danyang Zheng, Zhiyuan Li, Zhipeng Cai</p>
    <p><b>Summary:</b> Mobile Large Language Models (LLMs) are revolutionizing diverse fields such
as healthcare, finance, and education with their ability to perform advanced
natural language processing tasks on-the-go. However, the deployment of these
models in mobile and edge environments introduces significant challenges
related to privacy and security due to their resource-intensive nature and the
sensitivity of the data they process. This survey provides a comprehensive
overview of privacy and security issues associated with mobile LLMs,
systematically categorizing existing solutions such as differential privacy,
federated learning, and prompt encryption. Furthermore, we analyze
vulnerabilities unique to mobile LLMs, including adversarial attacks,
membership inference, and side-channel attacks, offering an in-depth comparison
of their effectiveness and limitations. Despite recent advancements, mobile
LLMs face unique hurdles in achieving robust security while maintaining
efficiency in resource-constrained environments. To bridge this gap, we propose
potential applications, discuss open challenges, and suggest future research
directions, paving the way for the development of trustworthy,
privacy-compliant, and scalable mobile LLM systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.02048v1">Privacy-Utility Trade-off in Data Publication: A Bilevel Optimization
  Framework with Curvature-Guided Perturbation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-09-02T07:44:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yi Yin, Guangquan Zhang, Hua Zuo, Jie Lu</p>
    <p><b>Summary:</b> Machine learning models require datasets for effective training, but directly
sharing raw data poses significant privacy risk such as membership inference
attacks (MIA). To mitigate the risk, privacy-preserving techniques such as data
perturbation, generalization, and synthetic data generation are commonly
utilized. However, these methods often degrade data accuracy, specificity, and
diversity, limiting the performance of downstream tasks and thus reducing data
utility. Therefore, striking an optimal balance between privacy preservation
and data utility remains a critical challenge.
  To address this issue, we introduce a novel bilevel optimization framework
for the publication of private datasets, where the upper-level task focuses on
data utility and the lower-level task focuses on data privacy. In the
upper-level task, a discriminator guides the generation process to ensure that
perturbed latent variables are mapped to high-quality samples, maintaining
fidelity for downstream tasks. In the lower-level task, our framework employs
local extrinsic curvature on the data manifold as a quantitative measure of
individual vulnerability to MIA, providing a geometric foundation for targeted
privacy protection. By perturbing samples toward low-curvature regions, our
method effectively suppresses distinctive feature combinations that are
vulnerable to MIA. Through alternating optimization of both objectives, we
achieve a synergistic balance between privacy and utility. Extensive
experimental evaluations demonstrate that our method not only enhances
resistance to MIA in downstream tasks but also surpasses existing methods in
terms of sample quality and diversity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.02004v1">Augmented Shuffle Differential Privacy Protocols for Large-Domain
  Categorical and Key-Value Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-09-02T06:40:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Takao Murakami, Yuichi Sei, Reo Eriguchi</p>
    <p><b>Summary:</b> Shuffle DP (Differential Privacy) protocols provide high accuracy and privacy
by introducing a shuffler who randomly shuffles data in a distributed system.
However, most shuffle DP protocols are vulnerable to two attacks: collusion
attacks by the data collector and users and data poisoning attacks. A recent
study addresses this issue by introducing an augmented shuffle DP protocol,
where users do not add noise and the shuffler performs random sampling and
dummy data addition. However, it focuses on frequency estimation over
categorical data with a small domain and cannot be applied to a large domain
due to prohibitively high communication and computational costs.
  In this paper, we fill this gap by introducing a novel augmented shuffle DP
protocol called the FME (Filtering-with-Multiple-Encryption) protocol. Our FME
protocol uses a hash function to filter out unpopular items and then accurately
calculates frequencies for popular items. To perform this within one round of
interaction between users and the shuffler, our protocol carefully communicates
within a system using multiple encryption. We also apply our FME protocol to
more advanced KV (Key-Value) statistics estimation with an additional technique
to reduce bias. For both categorical and KV data, we prove that our protocol
provides computational DP, high robustness to the above two attacks, accuracy,
and efficiency. We show the effectiveness of our proposals through comparisons
with twelve existing protocols.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.01716v1">An LLM-enabled semantic-centric framework to consume privacy policies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-09-01T18:53:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rui Zhao, Vladyslav Melnychuk, Jun Zhao, Jesse Wright, Nigel Shadbolt</p>
    <p><b>Summary:</b> In modern times, people have numerous online accounts, but they rarely read
the Terms of Service or Privacy Policy of those sites, despite claiming
otherwise, due to the practical difficulty in comprehending them. The mist of
data privacy practices forms a major barrier for user-centred Web approaches,
and for data sharing and reusing in an agentic world. Existing research
proposed methods for using formal languages and reasoning for verifying the
compliance of a specified policy, as a potential cure for ignoring privacy
policies. However, a critical gap remains in the creation or acquisition of
such formal policies at scale. We present a semantic-centric approach for using
state-of-the-art large language models (LLM), to automatically identify key
information about privacy practices from privacy policies, and construct
$\mathit{Pr}^2\mathit{Graph}$, knowledge graph with grounding from Data Privacy
Vocabulary (DPV) for privacy practices, to support downstream tasks. Along with
the pipeline, the $\mathit{Pr}^2\mathit{Graph}$ for the top-100 popular
websites is also released as a public resource, by using the pipeline for
analysis. We also demonstrate how the $\mathit{Pr}^2\mathit{Graph}$ can be used
to support downstream tasks by constructing formal policy representations such
as Open Digital Right Language (ODRL) or perennial semantic Data Terms of Use
(psDToU). To evaluate the technology capability, we enriched the Policy-IE
dataset by employing legal experts to create custom annotations. We benchmarked
the performance of different large language models for our pipeline and
verified their capabilities. Overall, they shed light on the possibility of
large-scale analysis of online services' privacy practices, as a promising
direction to audit the Web and the Internet. We release all datasets and source
code as public resources to facilitate reuse and improvement.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.01527v2">A Privacy-Preserving Recommender for Filling Web Forms Using a Local
  Large Language Model</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-09-01T15:02:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Amirreza Nayyeri, Abbas Rasoolzadegan</p>
    <p><b>Summary:</b> Web applications are increasingly used in critical domains such as education,
finance, and e-commerce. This highlights the need to ensure their failure-free
performance. One effective method for evaluating failure-free performance is
web form testing, where defining effective test scenarios is key to a complete
and accurate evaluation. A core aspect of this process involves filling form
fields with suitable values to create effective test cases. However, manually
generating these values is time-consuming and prone to errors. To address this,
various tools have been developed to assist testers. With the appearance of
large language models (LLMs), a new generation of tools seeks to handle this
task more intelligently. Although many LLM-based tools have been introduced, as
these models typically rely on cloud infrastructure, their use in testing
confidential web forms raises concerns about unintended data leakage and
breaches of confidentiality. This paper introduces a privacy-preserving
recommender that operates locally using a large language model. The tool
assists testers in web form testing by suggesting effective field values. This
tool analyzes the HTML structure of forms, detects input types, and extracts
constraints based on each field's type and contextual content, guiding proper
field filling.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.01470v1">Privacy-preserving authentication for military 5G networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-09-01T13:38:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> I. D. Lutz, A. M. Hill, M. C. Valenti</p>
    <p><b>Summary:</b> As 5G networks gain traction in defense applications, ensuring the privacy
and integrity of the Authentication and Key Agreement (AKA) protocol is
critical. While 5G AKA improves upon previous generations by concealing
subscriber identities, it remains vulnerable to replay-based synchronization
and linkability threats under realistic adversary models. This paper provides a
unified analysis of the standardized 5G AKA flow, identifying several
vulnerabilities and highlighting how each exploits protocol behavior to
compromise user privacy. To address these risks, we present five lightweight
mitigation strategies. We demonstrate through prototype implementation and
testing that these enhancements strengthen resilience against linkability
attacks with minimal computational and signaling overhead. Among the solutions
studied, those introducing a UE-generated nonce emerge as the most promising,
effectively neutralizing the identified tracking and correlation attacks with
negligible additional overhead. Integrating this extension as an optional
feature to the standard 5G AKA protocol offers a backward-compatible,
low-overhead path toward a more privacy-preserving authentication framework for
both commercial and military 5G deployments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.01354v1">DPF-CM: A Data Processing Framework with Privacy-Preserving Vector
  Databases for Chinese Medical LLMs Training and Deployment</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-09-01T10:49:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wei Huang, Anda Cheng, Zhao Zhang, Yinggui Wang</p>
    <p><b>Summary:</b> Current open-source training pipelines for Chinese medical language models
predominantly emphasize optimizing training methodologies to enhance the
performance of large language models (LLMs), yet lack comprehensive exploration
into training data processing. To address this gap, we propose DPF-CM, a
holistic Data Processing Framework for Chinese Medical LLMs training and
deployment. DPF-CM comprises two core modules. The first module is a data
processing pipeline tailored for model training. Beyond standard data
processing operations, we (1) introduce a chained examples context-learning
strategy to generate question-oriented instructions to mitigate the lack of
instruction content, and (2) implement an ensemble-based filtering mechanism
for preference data curation that averages multiple reward models to suppress
noisy samples. The second module focuses on privacy preservation during model
deployment. To prevent privacy risks from the inadvertent exposure of training
data, we propose a Privacy Preserving Vector Database (PPVD) approach, which
involves model memory search, high-risk database construction, secure database
construction, and match-and-replace, four key stages to minimize privacy
leakage during inference collectively. Experimental results show that DPF-CM
significantly improves model accuracy, enabling our trained Chinese medical LLM
to achieve state-of-the-art performance among open-source counterparts.
Moreover, the framework reduces training data privacy leakage by 27%.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.01088v1">Privacy-Preserving Reasoning with Knowledge-Distilled Parametric
  Retrieval Augmented Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-09-01T03:23:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jinwen Chen, Hainan Zhang, Liang Pang, Yongxin Tong, Haibo Zhou, Yuan Zhan, Wei Lin, Zhiming Zheng</p>
    <p><b>Summary:</b> The current RAG system requires uploading plaintext documents to the cloud,
risking private data leakage. Parametric RAG (PRAG) addresses this by encoding
documents as LoRA within LLMs, enabling reasoning without exposing raw content.
However, it still faces two issues: (1) PRAG demands synthesizing QA pairs and
fine-tuning LLM for each individual document to create its corresponding LoRA,
leading to unacceptable inference latency. (2) The performance of PRAG relies
solely on synthetic QA data, lacking internal alignment with standard RAG,
resulting in poor generalization on out-of-distribution(OOD) inputs. Therefore,
achieving high-efficiency parameterization while maintaining RAG-level
performance remains a critical challenge for privacy-preserving reasoning. In
this paper, we propose DistilledPRAG, a generalizable knowledge-distilled
parametric RAG model aligned with standard RAG in document structure and
parameter activation. We first synthesize QA pairs from single and
multi-documents to enhance cross-document reasoning. Then, we mask the
plaintext documents with a special token and translate them to LoRA via a
parameter generator, maintaining the standard RAG document structure. Finally,
guided by synthetic QA data, we train the parameter generator to match standard
RAG's hidden states and output logits, enabling RAG-style reasoning without
original documents. Experiments on four QA datasets show that DistilledPRAG
outperforms baselines in accuracy and generalizes well on OOD data.</p>
  </details>
</div>



<h2>2025-08</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.00693v1">DELTA: Variational Disentangled Learning for Privacy-Preserving Data
  Reprogramming</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> 
  <p><b>Published on:</b> 2025-08-31T04:18:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arun Vignesh Malarkkan, Haoyue Bai, Anjali Kaushik, Yanjie Fu</p>
    <p><b>Summary:</b> In real-world applications, domain data often contains identifiable or
sensitive attributes, is subject to strict regulations (e.g., HIPAA, GDPR), and
requires explicit data feature engineering for interpretability and
transparency. Existing feature engineering primarily focuses on advancing
downstream task performance, often risking privacy leakage. We generalize this
learning task under such new requirements as Privacy-Preserving Data
Reprogramming (PPDR): given a dataset, transforming features to maximize target
attribute prediction accuracy while minimizing sensitive attribute prediction
accuracy. PPDR poses challenges for existing systems: 1) generating
high-utility feature transformations without being overwhelmed by a large
search space, and 2) disentangling and eliminating sensitive information from
utility-oriented features to reduce privacy inferability. To tackle these
challenges, we propose DELTA, a two-phase variational disentangled generative
learning framework. Phase I uses policy-guided reinforcement learning to
discover feature transformations with downstream task utility, without any
regard to privacy inferability. Phase II employs a variational LSTM seq2seq
encoder-decoder with a utility-privacy disentangled latent space design and
adversarial-causal disentanglement regularization to suppress privacy signals
during feature generation. Experiments on eight datasets show DELTA improves
predictive performance by ~9.3% and reduces privacy leakage by ~35%,
demonstrating robust, privacy-aware data transformation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.00615v1">Federated Survival Analysis with Node-Level Differential Privacy:
  Private Kaplan-Meier Curves</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-08-30T21:47:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Narasimha Raghavan Veeraragavan, Jan Franz Nygård</p>
    <p><b>Summary:</b> We investigate how to calculate Kaplan-Meier survival curves across multiple
health-care jurisdictions while protecting patient privacy with node-level
differential privacy. Each site discloses its curve only once, adding Laplace
noise whose scale is determined by the length of the common time grid; the
server then averages the noisy curves, so the overall privacy budget remains
unchanged. We benchmark four one-shot smoothing techniques: Discrete Cosine
Transform, Haar Wavelet shrinkage, adaptive Total-Variation denoising, and a
parametric Weibull fit on the NCCTG lung-cancer cohort under five privacy
levels and three partition scenarios (uniform, moderately skewed, highly
imbalanced). Total-Variation gives the best mean accuracy, whereas the
frequency-domain smoothers offer stronger worst-case robustness and the Weibull
model shows the most stable behaviour at the strictest privacy setting. Across
all methods the released curves keep the empirical log-rank type-I error below
fifteen percent for privacy budgets of 0.5 and higher, demonstrating that
clinically useful survival information can be shared without iterative training
or heavy cryptography.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.00192v1">Safe-LLaVA: A Privacy-Preserving Vision-Language Dataset and Benchmark
  for Biometric Safety</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-08-29T18:54:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Younggun Kim, Sirnam Swetha, Fazil Kagdi, Mubarak Shah</p>
    <p><b>Summary:</b> Multimodal Large Language Models (MLLMs) have demonstrated remarkable
capabilities in vision-language tasks. However, these models often infer and
reveal sensitive biometric attributes - such as race, gender, age, body weight,
and eye color - even when such information is not explicitly requested. This
raises critical concerns, particularly in real-world applications and
socially-sensitive domains. Despite increasing awareness, no publicly available
dataset or benchmark exists to comprehensively evaluate or mitigate biometric
leakage in MLLMs. To address this gap, we introduce PRISM (Privacy-aware
Evaluation of Responses in Sensitive Modalities), a new benchmark designed to
assess MLLMs on two fronts: (1) refuse biometric-related queries and (2)
implicit biometric leakage in general responses while maintaining semantic
faithfulness. Further, we conduct a detailed audit of the widely used LLaVA
datasets and uncover extensive biometric leakage across pretraining and
instruction data. To address this, we present Safe-LLaVA dataset, the first
privacy-preserving MLLM training dataset constructed by systematically removing
explicit and implicit biometric information from LLaVA dataset. Our evaluations
on PRISM reveal biometric leakages across MLLMs for different attributes,
highlighting the detailed privacy-violations. We also fine-tune a model on
Safe-LLaVA dataset and show that it substantially reduces the biometric
leakages. Together, Safe-LLaVA & PRISM set a new standard for privacy-aligned
development and evaluation of MLLMs. The Safe-LLaVA dataset & PRISM benchmark
are publicly available at https://huggingface.co/datasets/kyh9191/Safe-LLaVA,
and the source code is available at
https://github.com/Kimyounggun99/Safe-LLaVA.git.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.21815v1">Achieving Hilbert-Schmidt Independence Under Rényi Differential
  Privacy for Fair and Private Data Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-08-29T17:51:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tobias Hyrup, Emmanouil Panagiotou, Arjun Roy, Arthur Zimek, Eirini Ntoutsi, Peter Schneider-Kamp</p>
    <p><b>Summary:</b> As privacy regulations such as the GDPR and HIPAA and responsibility
frameworks for artificial intelligence such as the AI Act gain traction, the
ethical and responsible use of real-world data faces increasing constraints.
Synthetic data generation has emerged as a promising solution to risk-aware
data sharing and model development, particularly for tabular datasets that are
foundational to sensitive domains such as healthcare. To address both privacy
and fairness concerns in this setting, we propose FLIP (Fair Latent
Intervention under Privacy guarantees), a transformer-based variational
autoencoder augmented with latent diffusion to generate heterogeneous tabular
data. Unlike the typical setup in fairness-aware data generation, we assume a
task-agnostic setup, not reliant on a fixed, defined downstream task, thus
offering broader applicability. To ensure privacy, FLIP employs R\'enyi
differential privacy (RDP) constraints during training and addresses fairness
in the input space with RDP-compatible balanced sampling that accounts for
group-specific noise levels across multiple sampling rates. In the latent
space, we promote fairness by aligning neuron activation patterns across
protected groups using Centered Kernel Alignment (CKA), a similarity measure
extending the Hilbert-Schmidt Independence Criterion (HSIC). This alignment
encourages statistical independence between latent representations and the
protected feature. Empirical results demonstrate that FLIP effectively provides
significant fairness improvements for task-agnostic fairness and across diverse
downstream tasks under differential privacy constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.21146v1">Privacy Auditing Synthetic Data Release through Local Likelihood Attacks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2025-08-28T18:27:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joshua Ward, Chi-Hua Wang, Guang Cheng</p>
    <p><b>Summary:</b> Auditing the privacy leakage of synthetic data is an important but unresolved
problem. Most existing privacy auditing frameworks for synthetic data rely on
heuristics and unreasonable assumptions to attack the failure modes of
generative models, exhibiting limited capability to describe and detect the
privacy exposure of training data through synthetic data release. In this
paper, we study designing Membership Inference Attacks (MIAs) that specifically
exploit the observation that tabular generative models tend to significantly
overfit to certain regions of the training distribution. Here, we propose
Generative Likelihood Ratio Attack (Gen-LRA), a novel, computationally
efficient No-Box MIA that, with no assumption of model knowledge or access,
formulates its attack by evaluating the influence a test observation has in a
surrogate model's estimation of a local likelihood ratio over the synthetic
data. Assessed over a comprehensive benchmark spanning diverse datasets, model
architectures, and attack parameters, we find that Gen-LRA consistently
dominates other MIAs for generative models across multiple performance metrics.
These results underscore Gen-LRA's effectiveness as a privacy auditing tool for
the release of synthetic data, highlighting the significant privacy risks posed
by generative model overfitting in real-world applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.20736v1">Leveraging Semantic Triples for Private Document Generation with Local
  Differential Privacy Guarantees</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-08-28T12:59:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stephen Meisenbacher, Maulik Chevli, Florian Matthes</p>
    <p><b>Summary:</b> Many works at the intersection of Differential Privacy (DP) in Natural
Language Processing aim to protect privacy by transforming texts under DP
guarantees. This can be performed in a variety of ways, from word perturbations
to full document rewriting, and most often under local DP. Here, an input text
must be made indistinguishable from any other potential text, within some bound
governed by the privacy parameter $\varepsilon$. Such a guarantee is quite
demanding, and recent works show that privatizing texts under local DP can only
be done reasonably under very high $\varepsilon$ values. Addressing this
challenge, we introduce DP-ST, which leverages semantic triples for
neighborhood-aware private document generation under local DP guarantees.
Through the evaluation of our method, we demonstrate the effectiveness of the
divide-and-conquer paradigm, particularly when limiting the DP notion (and
privacy guarantees) to that of a privatization neighborhood. When combined with
LLM post-processing, our method allows for coherent text generation even at
lower $\varepsilon$ values, while still balancing privacy and utility. These
findings highlight the importance of coherence in achieving balanced
privatization outputs at reasonable $\varepsilon$ levels.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.20613v1">Revisiting the Privacy Risks of Split Inference: A GAN-Based Data
  Reconstruction Attack via Progressive Feature Optimization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-28T10:00:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yixiang Qiu, Yanhan Liu, Hongyao Yu, Hao Fang, Bin Chen, Shu-Tao Xia, Ke Xu</p>
    <p><b>Summary:</b> The growing complexity of Deep Neural Networks (DNNs) has led to the adoption
of Split Inference (SI), a collaborative paradigm that partitions computation
between edge devices and the cloud to reduce latency and protect user privacy.
However, recent advances in Data Reconstruction Attacks (DRAs) reveal that
intermediate features exchanged in SI can be exploited to recover sensitive
input data, posing significant privacy risks. Existing DRAs are typically
effective only on shallow models and fail to fully leverage semantic priors,
limiting their reconstruction quality and generalizability across datasets and
model architectures. In this paper, we propose a novel GAN-based DRA framework
with Progressive Feature Optimization (PFO), which decomposes the generator
into hierarchical blocks and incrementally refines intermediate representations
to enhance the semantic fidelity of reconstructed images. To stabilize the
optimization and improve image realism, we introduce an L1-ball constraint
during reconstruction. Extensive experiments show that our method outperforms
prior attacks by a large margin, especially in high-resolution scenarios,
out-of-distribution settings, and against deeper and more complex DNNs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.20250v2">Efficient and Privacy-Protecting Background Removal for 2D Video
  Streaming using iPhone 15 Pro Max LiDAR</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Multimedia-5BC0EB">  
  <p><b>Published on:</b> 2025-08-27T20:14:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jessica Kinnevan, Naifa Alqahtani, Toral Chauhan</p>
    <p><b>Summary:</b> Light Detection and Ranging (LiDAR) technology in consumer-grade mobile
devices can be used as a replacement for traditional background removal and
compositing techniques. Unlike approaches such as chroma keying and trained AI
models, LiDAR's depth information is independent of subject lighting, and
performs equally well in low-light and well-lit environments. We integrate the
LiDAR and color cameras on the iPhone 15 Pro Max with GPU-based image
processing. We use Apple's SwiftUI and Swift frameworks for user interface and
backend development, and Metal Shader Language (MSL) for realtime image
enhancement at the standard iPhone streaming frame rate of 60 frames per
second. The only meaningful limitations of the technology are the streaming
bandwidth of the depth data, which currently reduces the depth map resolution
to 320x240, and any pre-existing limitations of the LiDAR IR laser to reflect
accurate depth from some materials. If the LiDAR resolution on a mobile device
like the iPhone can be improved to match the color image resolution, LiDAR
could feasibly become the preeminent method of background removal for video
applications and photography.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.00101v1">Privacy, Informed Consent and the Demand for Anonymisation of Smart
  Meter Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36"> 
  <p><b>Published on:</b> 2025-08-27T20:05:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Saurab Chhachhi, Fei Teng</p>
    <p><b>Summary:</b> Access to smart meter data offers system-wide benefits but raises significant
privacy concerns due to the personal information it contains.
Privacy-preserving techniques could facilitate wider access, though they
introduce privacy-utility trade-offs. Understanding consumer valuations for
anonymisation can help identify appropriate trade-offs. However, existing
studies do not focus on anonymisation specifically or account for information
asymmetries regarding privacy risks, raising questions about the validity of
informed consent under current regulations.
  We use a mixed-methods approach to estimate non-monetary
(willingness-to-share and smart metering demand) and monetary
(willingness-to-pay/accept) preferences for anonymisation, based on a
representative sample of 965 GB bill payers. An embedded randomised control
trial examines the effect of providing information about privacy implications.
  On average, consumers are willing to pay for anonymisation, are more willing
to share data when anonymised and less willing to share non-anonymised data
once anonymisation is presented as an option. However, a significant minority
remains unwilling to adopt smart meters, despite anonymisation. We find strong
evidence of information asymmetries that suppress demand for anonymisation and
identify substantial variation across demographic and electricity supply
characteristics. Qualitative responses corroborate the quantitative findings,
underscoring the need for stronger privacy defaults, user-centric design, and
consent mechanisms that enable truly informed decisions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.19640v1">Optimal Cox regression under federated differential privacy:
  coefficients and cumulative hazards</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">  
  <p><b>Published on:</b> 2025-08-27T07:29:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Elly K. H. Hung, Yi Yu</p>
    <p><b>Summary:</b> We study two foundational problems in distributed survival analysis:
estimating Cox regression coefficients and cumulative hazard functions, under
federated differential privacy constraints, allowing for heterogeneous
per-sever sample sizes and privacy budgets. To quantify the fundamental cost of
privacy, we derive minimax lower bounds along with matching (up to
poly-logarithmic factors) upper bounds. In particular, to estimate the
cumulative hazard function, we design a private tree-based algorithm for
nonparametric integral estimation. Our results reveal server-level phase
transitions between the private and non-private rates, as well as the reduced
estimation accuracy from imposing privacy constraints on distributed subsets of
data.
  To address scenarios with partially public information, we also consider a
relaxed differential privacy framework and provide a corresponding minimax
analysis. To our knowledge, this is the first treatment of partially public
data in survival analysis, and it establishes a no-gain in accuracy phenomenon.
Finally, we conduct extensive numerical experiments, with an accompanying R
package FDPCox, validating our theoretical findings. These experiments also
include a fully-interactive algorithm with tighter privacy composition, which
demonstrates improved estimation accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.19493v2">Mind the Third Eye! Benchmarking Privacy Awareness in MLLM-powered
  Smartphone Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-08-27T00:41:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhixin Lin, Jungang Li, Shidong Pan, Yibo Shi, Yue Yao, Dongliang Xu</p>
    <p><b>Summary:</b> Smartphones bring significant convenience to users but also enable devices to
extensively record various types of personal information. Existing smartphone
agents powered by Multimodal Large Language Models (MLLMs) have achieved
remarkable performance in automating different tasks. However, as the cost,
these agents are granted substantial access to sensitive users' personal
information during this operation. To gain a thorough understanding of the
privacy awareness of these agents, we present the first large-scale benchmark
encompassing 7,138 scenarios to the best of our knowledge. In addition, for
privacy context in scenarios, we annotate its type (e.g., Account Credentials),
sensitivity level, and location. We then carefully benchmark seven available
mainstream smartphone agents. Our results demonstrate that almost all
benchmarked agents show unsatisfying privacy awareness (RA), with performance
remaining below 60% even with explicit hints. Overall, closed-source agents
show better privacy ability than open-source ones, and Gemini 2.0-flash
achieves the best, achieving an RA of 67%. We also find that the agents'
privacy detection capability is highly related to scenario sensitivity level,
i.e., the scenario with a higher sensitivity level is typically more
identifiable. We hope the findings enlighten the research community to rethink
the unbalanced utility-privacy tradeoff about smartphone agents. Our code and
benchmark are available at https://zhixin-l.github.io/SAPA-Bench.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.19458v1">The Sample Complexity of Membership Inference and Privacy Auditing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2025-08-26T22:19:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mahdi Haghifam, Adam Smith, Jonathan Ullman</p>
    <p><b>Summary:</b> A membership-inference attack gets the output of a learning algorithm, and a
target individual, and tries to determine whether this individual is a member
of the training data or an independent sample from the same distribution. A
successful membership-inference attack typically requires the attacker to have
some knowledge about the distribution that the training data was sampled from,
and this knowledge is often captured through a set of independent reference
samples from that distribution. In this work we study how much information the
attacker needs for membership inference by investigating the sample
complexity-the minimum number of reference samples required-for a successful
attack. We study this question in the fundamental setting of Gaussian mean
estimation where the learning algorithm is given $n$ samples from a Gaussian
distribution $\mathcal{N}(\mu,\Sigma)$ in $d$ dimensions, and tries to estimate
$\hat\mu$ up to some error $\mathbb{E}[\|\hat \mu - \mu\|^2_{\Sigma}]\leq
\rho^2 d$. Our result shows that for membership inference in this setting,
$\Omega(n + n^2 \rho^2)$ samples can be necessary to carry out any attack that
competes with a fully informed attacker. Our result is the first to show that
the attacker sometimes needs many more samples than the training algorithm uses
to train the model. This result has significant implications for practice, as
all attacks used in practice have a restricted form that uses $O(n)$ samples
and cannot benefit from $\omega(n)$ samples. Thus, these attacks may be
underestimating the possibility of membership inference, and better attacks may
be possible when information about the distribution is easy to obtain.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.19345v1">Privacy-Preserving Distributed Control for a Networked Battery Energy
  Storage System</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2025-08-26T18:06:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mihitha Maithripala, Zongli Lin</p>
    <p><b>Summary:</b> The increasing deployment of distributed Battery Energy Storage Systems
(BESSs) in modern power grids necessitates effective coordination strategies to
ensure state-of-charge (SoC) balancing and accurate power delivery. While
distributed control frameworks offer scalability and resilience, they also
raise significant privacy concerns due to the need for inter-agent information
exchange. This paper presents a novel privacy-preserving distributed control
algorithm for SoC balancing in a networked BESS. The proposed framework
includes distributed power allocation law that is designed based on two
privacy-preserving distributed estimators, one for the average unit state and
the other for the average desired power. The average unit state estimator is
designed via the state decomposition method without disclosing sensitive
internal states. The proposed power allocation law based on these estimators
ensures asymptotic SoC balancing and global power delivery while safeguarding
agent privacy from external eavesdroppers. The effectiveness and
privacy-preserving properties of the proposed control strategy are demonstrated
through simulation results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.19115v1">SecureV2X: An Efficient and Privacy-Preserving System for
  Vehicle-to-Everything (V2X) Applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> 
  <p><b>Published on:</b> 2025-08-26T15:17:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joshua Lee, Ali Arastehfard, Weiran Liu, Xuegang Ban, Yuan Hong</p>
    <p><b>Summary:</b> Autonomous driving and V2X technologies have developed rapidly in the past
decade, leading to improved safety and efficiency in modern transportation.
These systems interact with extensive networks of vehicles, roadside
infrastructure, and cloud resources to support their machine learning
capabilities. However, the widespread use of machine learning in V2X systems
raises issues over the privacy of the data involved. This is particularly
concerning for smart-transit and driver safety applications which can
implicitly reveal user locations or explicitly disclose medical data such as
EEG signals. To resolve these issues, we propose SecureV2X, a scalable,
multi-agent system for secure neural network inferences deployed between the
server and each vehicle. Under this setting, we study two multi-agent V2X
applications: secure drowsiness detection, and secure red-light violation
detection. Our system achieves strong performance relative to baselines, and
scales efficiently to support a large number of secure computation interactions
simultaneously. For instance, SecureV2X is $9.4 \times$ faster, requires
$143\times$ fewer computational rounds, and involves $16.6\times$ less
communication on drowsiness detection compared to other secure systems.
Moreover, it achieves a runtime nearly $100\times$ faster than state-of-the-art
benchmarks in object detection tasks for red light violation detection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.18976v1">The Double-edged Sword of LLM-based Data Reconstruction: Understanding
  and Mitigating Contextual Vulnerability in Word-level Differential Privacy
  Text Sanitization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-08-26T12:22:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stephen Meisenbacher, Alexandra Klymenko, Andreea-Elena Bodea, Florian Matthes</p>
    <p><b>Summary:</b> Differentially private text sanitization refers to the process of privatizing
texts under the framework of Differential Privacy (DP), providing provable
privacy guarantees while also empirically defending against adversaries seeking
to harm privacy. Despite their simplicity, DP text sanitization methods
operating at the word level exhibit a number of shortcomings, among them the
tendency to leave contextual clues from the original texts due to randomization
during sanitization $\unicode{x2013}$ this we refer to as $\textit{contextual
vulnerability}$. Given the powerful contextual understanding and inference
capabilities of Large Language Models (LLMs), we explore to what extent LLMs
can be leveraged to exploit the contextual vulnerability of DP-sanitized texts.
We expand on previous work not only in the use of advanced LLMs, but also in
testing a broader range of sanitization mechanisms at various privacy levels.
Our experiments uncover a double-edged sword effect of LLM-based data
reconstruction attacks on privacy and utility: while LLMs can indeed infer
original semantics and sometimes degrade empirical privacy protections, they
can also be used for good, to improve the quality and privacy of DP-sanitized
texts. Based on our findings, we propose recommendations for using LLM data
reconstruction as a post-processing step, serving to increase privacy
protection by thinking adversarially.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.18971v1">Can we make NeRF-based visual localization privacy-preserving?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-08-26T12:17:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maxime Pietrantoni, Martin Humenberger, Torsten Sattler, Gabriela Csurka</p>
    <p><b>Summary:</b> Visual localization (VL) is the task of estimating the camera pose in a known
scene. VL methods, a.o., can be distinguished based on how they represent the
scene, e.g., explicitly through a (sparse) point cloud or a collection of
images or implicitly through the weights of a neural network. Recently,
NeRF-based methods have become popular for VL. While NeRFs offer high-quality
novel view synthesis, they inadvertently encode fine scene details, raising
privacy concerns when deployed in cloud-based localization services as
sensitive information could be recovered. In this paper, we tackle this
challenge on two ends. We first propose a new protocol to assess
privacy-preservation of NeRF-based representations. We show that NeRFs trained
with photometric losses store fine-grained details in their geometry
representations, making them vulnerable to privacy attacks, even if the head
that predicts colors is removed. Second, we propose ppNeSF (Privacy-Preserving
Neural Segmentation Field), a NeRF variant trained with segmentation
supervision instead of RGB images. These segmentation labels are learned in a
self-supervised manner, ensuring they are coarse enough to obscure identifiable
scene details while remaining discriminativeness in 3D. The segmentation space
of ppNeSF can be used for accurate visual localization, yielding
state-of-the-art results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.18942v1">EnerSwap: Large-Scale, Privacy-First Automated Market Maker for V2G
  Energy Trading</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-26T11:31:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ahmed Mounsf Rafik Bendada, Yacine Ghamri-Doudane</p>
    <p><b>Summary:</b> With the rapid growth of Electric Vehicle (EV) technology, EVs are destined
to shape the future of transportation. The large number of EVs facilitates the
development of the emerging vehicle-to-grid (V2G) technology, which realizes
bidirectional energy exchanges between EVs and the power grid. This has led to
the setting up of electricity markets that are usually confined to a small
geographical location, often with a small number of participants. Usually,
these markets are manipulated by intermediaries responsible for collecting bids
from prosumers, determining the market-clearing price, incorporating grid
constraints, and accounting for network losses. While centralized models can be
highly efficient, they grant excessive power to the intermediary by allowing
them to gain exclusive access to prosumers \textquotesingle price preferences.
This opens the door to potential market manipulation and raises significant
privacy concerns for users, such as the location of energy providers. This lack
of protection exposes users to potential risks, as untrustworthy servers and
malicious adversaries can exploit this information to infer trading activities
and real identities. This work proposes a secure, decentralized exchange market
built on blockchain technology, utilizing a privacy-preserving Automated Market
Maker (AMM) model to offer open and fair, and equal access to traders, and
mitigates the most common trading-manipulation attacks. Additionally, it
incorporates a scalable architecture based on geographical dynamic sharding,
allowing for efficient resource allocation and improved performance as the
market grows.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.18911v2">Enhancing Model Privacy in Federated Learning with Random Masking and
  Quantization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-26T10:34:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhibo Xu, Jianhao Zhu, Jingwen Xu, Changze Lv, Zisu Huang, Xiaohua Wang, Muling Wu, Qi Qian, Xiaoqing Zheng, Xuanjing Huang</p>
    <p><b>Summary:</b> The primary goal of traditional federated learning is to protect data privacy
by enabling distributed edge devices to collaboratively train a shared global
model while keeping raw data decentralized at local clients. The rise of large
language models (LLMs) has introduced new challenges in distributed systems, as
their substantial computational requirements and the need for specialized
expertise raise critical concerns about protecting intellectual property (IP).
This highlights the need for a federated learning approach that can safeguard
both sensitive data and proprietary models. To tackle this challenge, we
propose FedQSN, a federated learning approach that leverages random masking to
obscure a subnetwork of model parameters and applies quantization to the
remaining parameters. Consequently, the server transmits only a
privacy-preserving proxy of the global model to clients during each
communication round, thus enhancing the model's confidentiality. Experimental
results across various models and tasks demonstrate that our approach not only
maintains strong model performance in federated learning settings but also
achieves enhanced protection of model parameters compared to baseline methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.18832v1">A Tight Context-aware Privacy Bound for Histogram Publication</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2025-08-26T09:12:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sara Saeidian, Ata Yavuzyılmaz, Leonhard Grosse, Georg Schuppe, Tobias J. Oechtering</p>
    <p><b>Summary:</b> We analyze the privacy guarantees of the Laplace mechanism releasing the
histogram of a dataset through the lens of pointwise maximal leakage (PML).
While differential privacy is commonly used to quantify the privacy loss, it is
a context-free definition that does not depend on the data distribution. In
contrast, PML enables a more refined analysis by incorporating assumptions
about the data distribution. We show that when the probability of each
histogram bin is bounded away from zero, stronger privacy protection can be
achieved for a fixed level of noise. Our results demonstrate the advantage of
context-aware privacy measures and show that incorporating assumptions about
the data can improve privacy-utility tradeoffs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.18513v1">An Analytical Approach to Privacy and Performance Trade-Offs in
  Healthcare Data Sharing</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-08-25T21:36:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yusi Wei, Hande Y. Benson, Muge Capan</p>
    <p><b>Summary:</b> The secondary use of healthcare data is vital for research and clinical
innovation, but it raises concerns about patient privacy. This study
investigates how to balance privacy preservation and data utility in healthcare
data sharing, considering the perspectives of both data providers and data
users. Using a dataset of adult patients hospitalized between 2013 and 2015, we
predict whether sepsis was present at admission or developed during the
hospital stay. We identify sub-populations, such as older adults, frequently
hospitalized patients, and racial minorities, that are especially vulnerable to
privacy attacks due to their unique combinations of demographic and healthcare
utilization attributes. These groups are also critical for machine learning
(ML) model performance. We evaluate three anonymization methods-$k$-anonymity,
the technique by Zheng et al., and the MO-OBAM model-based on their ability to
reduce re-identification risk while maintaining ML utility. Results show that
$k$-anonymity offers limited protection. The methods of Zheng et al. and
MO-OBAM provide stronger privacy safeguards, with MO-OBAM yielding the best
utility outcomes: only a 2% change in precision and recall compared to the
original dataset. This work provides actionable insights for healthcare
organizations on how to share data responsibly. It highlights the need for
anonymization methods that protect vulnerable populations without sacrificing
the performance of data-driven models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.18453v2">Privacy-Preserving Federated Learning Framework for Risk-Based Adaptive
  Authentication</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-25T20:02:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yaser Baseri, Abdelhakim Senhaji Hafid, Dimitrios Makrakis, Hamidreza Fereidouni</p>
    <p><b>Summary:</b> Balancing robust security with strong privacy guarantees is critical for
Risk-Based Adaptive Authentication (RBA), particularly in decentralized
settings. Federated Learning (FL) offers a promising solution by enabling
collaborative risk assessment without centralizing user data. However, existing
FL approaches struggle with Non-Independent and Identically Distributed
(Non-IID) user features, resulting in biased, unstable, and poorly generalized
global models. This paper introduces FL-RBA2, a novel Federated Learning
framework for Risk-Based Adaptive Authentication that addresses Non-IID
challenges through a mathematically grounded similarity transformation. By
converting heterogeneous user features (including behavioral, biometric,
contextual, interaction-based, and knowledge-based modalities) into IID
similarity vectors, FL-RBA2 supports unbiased aggregation and personalized risk
modeling across distributed clients. The framework mitigates cold-start
limitations via clustering-based risk labeling, incorporates Differential
Privacy (DP) to safeguard sensitive information, and employs Message
Authentication Codes (MACs) to ensure model integrity and authenticity.
Federated updates are securely aggregated into a global model, achieving strong
balance between user privacy, scalability, and adaptive authentication
robustness. Rigorous game-based security proofs in the Random Oracle Model
formally establish privacy, correctness, and adaptive security guarantees.
Extensive experiments on keystroke, mouse, and contextual datasets validate
FL-RBA2's effectiveness in high-risk user detection and its resilience to model
inversion and inference attacks, even under strong DP constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.17962v1">"Nobody should control the end user": Exploring Privacy Perspectives of
  Indian Internet Users in Light of DPDPA</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-08-25T12:22:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sana Athar, Devashish Gosain, Anja Feldmann, Mannat Kaur, Ha Dao</p>
    <p><b>Summary:</b> With the rapid increase in online interactions, concerns over data privacy
and transparency of data processing practices have become more pronounced.
While regulations like the GDPR have driven the widespread adoption of cookie
banners in the EU, India's Digital Personal Data Protection Act (DPDPA)
promises similar changes domestically, aiming to introduce a framework for data
protection. However, certain clauses within the DPDPA raise concerns about
potential infringements on user privacy, given the exemptions for government
accountability and user consent requirements. In this study, for the first
time, we explore Indian Internet users' awareness and perceptions of cookie
banners, online privacy, and privacy regulations, especially in light of the
newly passed DPDPA. We conducted an online anonymous survey with 428 Indian
participants, which addressed: (1) users' perspectives on cookie banners, (2)
their attitudes towards online privacy and privacy regulations, and (3) their
acceptance of 10 contentious DPDPA clauses that favor state authorities and may
enable surveillance. Our findings reveal that privacy-conscious users often
lack consistent awareness of privacy mechanisms, and their concerns do not
always lead to protective actions. Our thematic analysis of 143 open ended
responses shows that users' privacy and data protection concerns are rooted in
skepticism towards the government, shaping their perceptions of the DPDPA and
fueling demands for policy revisions. Our study highlights the need for clearer
communication regarding the DPDPA, user-centric consent mechanisms, and policy
refinements to enhance data privacy practices in India.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.19286v1">RL-Finetuned LLMs for Privacy-Preserving Synthetic Rewriting</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-08-25T04:38:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhan Shi, Yefeng Yuan, Yuhong Liu, Liang Cheng, Yi Fang</p>
    <p><b>Summary:</b> The performance of modern machine learning systems depends on access to
large, high-quality datasets, often sourced from user-generated content or
proprietary, domain-specific corpora. However, these rich datasets inherently
contain sensitive personal information, raising significant concerns about
privacy, data security, and compliance with regulatory frameworks. While
conventional anonymization techniques can remove explicit identifiers, such
removal may result in performance drop in downstream machine learning tasks.
More importantly, simple anonymization may not be effective against inference
attacks that exploit implicit signals such as writing style, topical focus, or
demographic cues, highlighting the need for more robust privacy safeguards
during model training. To address the challenging issue of balancing user
privacy and data utility, we propose a reinforcement learning framework that
fine-tunes a large language model (LLM) using a composite reward function that
jointly optimizes for explicit and implicit privacy, semantic fidelity, and
output diversity. To effectively capture population level regularities, the
privacy reward combines semantic cues with structural patterns derived from a
minimum spanning tree (MST) over latent representations. By modeling these
privacy-sensitive signals in their distributional context, the proposed
approach guides the model to generate synthetic rewrites that preserve utility
while mitigating privacy risks. Empirical results show that the proposed method
significantly enhances author obfuscation and privacy metrics without degrading
semantic quality, providing a scalable and model-agnostic solution for privacy
preserving data generation in the era of large language models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.17341v1">MetaFed: Advancing Privacy, Performance, and Sustainability in Federated
  Metaverse Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2025-08-24T12:53:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Muhammet Anil Yagiz, Zeynep Sude Cengiz, Polat Goktas</p>
    <p><b>Summary:</b> The rapid expansion of immersive Metaverse applications introduces complex
challenges at the intersection of performance, privacy, and environmental
sustainability. Centralized architectures fall short in addressing these
demands, often resulting in elevated energy consumption, latency, and privacy
concerns. This paper proposes MetaFed, a decentralized federated learning (FL)
framework that enables sustainable and intelligent resource orchestration for
Metaverse environments. MetaFed integrates (i) multi-agent reinforcement
learning for dynamic client selection, (ii) privacy-preserving FL using
homomorphic encryption, and (iii) carbon-aware scheduling aligned with
renewable energy availability. Evaluations on MNIST and CIFAR-10 using
lightweight ResNet architectures demonstrate that MetaFed achieves up to 25\%
reduction in carbon emissions compared to conventional approaches, while
maintaining high accuracy and minimal communication overhead. These results
highlight MetaFed as a scalable solution for building environmentally
responsible and privacy-compliant Metaverse infrastructures.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.17222v1">Exposing Privacy Risks in Graph Retrieval-Augmented Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2025-08-24T06:19:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiale Liu, Jiahao Zhang, Suhang Wang</p>
    <p><b>Summary:</b> Retrieval-Augmented Generation (RAG) is a powerful technique for enhancing
Large Language Models (LLMs) with external, up-to-date knowledge. Graph RAG has
emerged as an advanced paradigm that leverages graph-based knowledge structures
to provide more coherent and contextually rich answers. However, the move from
plain document retrieval to structured graph traversal introduces new,
under-explored privacy risks. This paper investigates the data extraction
vulnerabilities of the Graph RAG systems. We design and execute tailored data
extraction attacks to probe their susceptibility to leaking both raw text and
structured data, such as entities and their relationships. Our findings reveal
a critical trade-off: while Graph RAG systems may reduce raw text leakage, they
are significantly more vulnerable to the extraction of structured entity and
relationship information. We also explore potential defense mechanisms to
mitigate these novel attack surfaces. This work provides a foundational
analysis of the unique privacy challenges in Graph RAG and offers insights for
building more secure systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.18318v1">ZTFed-MAS2S: A Zero-Trust Federated Learning Framework with Verifiable
  Privacy and Trust-Aware Aggregation for Wind Power Data Imputation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36"> 
  <p><b>Published on:</b> 2025-08-24T01:50:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yang Li, Hanjie Wang, Yuanzheng Li, Jiazheng Li, Zhaoyang Dong</p>
    <p><b>Summary:</b> Wind power data often suffers from missing values due to sensor faults and
unstable transmission at edge sites. While federated learning enables
privacy-preserving collaboration without sharing raw data, it remains
vulnerable to anomalous updates and privacy leakage during parameter exchange.
These challenges are amplified in open industrial environments, necessitating
zero-trust mechanisms where no participant is inherently trusted. To address
these challenges, this work proposes ZTFed-MAS2S, a zero-trust federated
learning framework that integrates a multi-head attention-based
sequence-to-sequence imputation model. ZTFed integrates verifiable differential
privacy with non-interactive zero-knowledge proofs and a confidentiality and
integrity verification mechanism to ensure verifiable privacy preservation and
secure model parameters transmission. A dynamic trust-aware aggregation
mechanism is employed, where trust is propagated over similarity graphs to
enhance robustness, and communication overhead is reduced via sparsity- and
quantization-based compression. MAS2S captures long-term dependencies in wind
power data for accurate imputation. Extensive experiments on real-world wind
farm datasets validate the superiority of ZTFed-MAS2S in both federated
learning performance and missing data imputation, demonstrating its
effectiveness as a secure and efficient solution for practical applications in
the energy sector.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.17135v1">Rao Differential Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2025-08-23T20:25:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Carlos Soto</p>
    <p><b>Summary:</b> Differential privacy (DP) has recently emerged as a definition of privacy to
release private estimates. DP calibrates noise to be on the order of an
individuals contribution. Due to the this calibration a private estimate
obscures any individual while preserving the utility of the estimate. Since the
original definition, many alternate definitions have been proposed. These
alternates have been proposed for various reasons including improvements on
composition results, relaxations, and formalizations. Nevertheless, thus far
nearly all definitions of privacy have used a divergence of densities as the
basis of the definition. In this paper we take an information geometry
perspective towards differential privacy. Specifically, rather than define
privacy via a divergence, we define privacy via the Rao distance. We show that
our proposed definition of privacy shares the interpretation of previous
definitions of privacy while improving on sequential composition.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.17043v1">ZAPS: A Zero-Knowledge Proof Protocol for Secure UAV Authentication with
  Flight Path Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-23T14:45:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shayesta Naziri, Xu Wang, Guangsheng Yu, Christy Jie Liang, Wei Ni</p>
    <p><b>Summary:</b> The increasing deployment of Unmanned Aerial Vehicles (UAVs) for military,
commercial, and logistics applications has raised significant concerns
regarding flight path privacy. Conventional UAV communication systems often
expose flight path data to third parties, making them vulnerable to tracking,
surveillance, and location inference attacks. Existing encryption techniques
provide security but fail to ensure complete privacy, as adversaries can still
infer movement patterns through metadata analysis. To address these challenges,
we propose a zk-SNARK(Zero-Knowledge Succinct Non-Interactive Argument of
Knowledge)-based privacy-preserving flight path authentication and verification
framework. Our approach ensures that a UAV can prove its authorisation,
validate its flight path with a control centre, and comply with regulatory
constraints without revealing any sensitive trajectory information. By
leveraging zk-SNARKs, the UAV can generate cryptographic proofs that verify
compliance with predefined flight policies while keeping the exact path and
location undisclosed. This method mitigates risks associated with real-time
tracking, identity exposure, and unauthorised interception, thereby enhancing
UAV operational security in adversarial environments. Our proposed solution
balances privacy, security, and computational efficiency, making it suitable
for resource-constrained UAVs in both civilian and military applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.16765v1">Guarding Your Conversations: Privacy Gatekeepers for Secure Interactions
  with Cloud-Based AI Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-08-22T19:49:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> GodsGift Uzor, Hasan Al-Qudah, Ynes Ineza, Abdul Serwadda</p>
    <p><b>Summary:</b> The interactive nature of Large Language Models (LLMs), which closely track
user data and context, has prompted users to share personal and private
information in unprecedented ways. Even when users opt out of allowing their
data to be used for training, these privacy settings offer limited protection
when LLM providers operate in jurisdictions with weak privacy laws, invasive
government surveillance, or poor data security practices. In such cases, the
risk of sensitive information, including Personally Identifiable Information
(PII), being mishandled or exposed remains high. To address this, we propose
the concept of an "LLM gatekeeper", a lightweight, locally run model that
filters out sensitive information from user queries before they are sent to the
potentially untrustworthy, though highly capable, cloud-based LLM. Through
experiments with human subjects, we demonstrate that this dual-model approach
introduces minimal overhead while significantly enhancing user privacy, without
compromising the quality of LLM responses.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.15523v1">Stabilization of Perturbed Loss Function: Differential Privacy without
  Gradient Noise</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2025-08-21T12:54:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Salman Habib, Remi Chou, Taejoon Kim</p>
    <p><b>Summary:</b> We propose SPOF (Stabilization of Perturbed Loss Function), a differentially
private training mechanism intended for multi-user local differential privacy
(LDP). SPOF perturbs a stabilized Taylor expanded polynomial approximation of a
model's training loss function, where each user's data is privatized by
calibrated noise added to the coefficients of the polynomial. Unlike
gradient-based mechanisms such as differentially private stochastic gradient
descent (DP-SGD), SPOF does not require injecting noise into the gradients of
the loss function, which improves both computational efficiency and stability.
This formulation naturally supports simultaneous privacy guarantees across all
users. Moreover, SPOF exhibits robustness to environmental noise during
training, maintaining stable performance even when user inputs are corrupted.
We compare SPOF with a multi-user extension of DP-SGD, evaluating both methods
in a wireless body area network (WBAN) scenario involving heterogeneous user
data and stochastic channel noise from body sensors. Our results show that SPOF
achieves, on average, up to 3.5% higher reconstruction accuracy and reduces
mean training time by up to 57.2% compared to DP-SGD, demonstrating superior
privacy-utility trade-offs in multi-user environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.15421v1">A Study of Privacy-preserving Language Modeling Approaches</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-08-21T10:22:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pritilata Saha, Abhirup Sinha</p>
    <p><b>Summary:</b> Recent developments in language modeling have increased their use in various
applications and domains. Language models, often trained on sensitive data, can
memorize and disclose this information during privacy attacks, raising concerns
about protecting individuals' privacy rights. Preserving privacy in language
models has become a crucial area of research, as privacy is one of the
fundamental human rights. Despite its significance, understanding of how much
privacy risk these language models possess and how it can be mitigated is still
limited. This research addresses this by providing a comprehensive study of the
privacy-preserving language modeling approaches. This study gives an in-depth
overview of these approaches, highlights their strengths, and investigates
their limitations. The outcomes of this study contribute to the ongoing
research on privacy-preserving language modeling, providing valuable insights
and outlining future research directions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.15089v1">Tighter Privacy Analysis for Truncated Poisson Sampling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-20T22:00:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arun Ganesh</p>
    <p><b>Summary:</b> We give a new privacy amplification analysis for truncated Poisson sampling,
a Poisson sampling variant that truncates a batch if it exceeds a given maximum
batch size.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.15036v1">MoEcho: Exploiting Side-Channel Attacks to Compromise User Privacy in
  Mixture-of-Experts LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-20T20:02:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruyi Ding, Tianhong Xu, Xinyi Shen, Aidong Adam Ding, Yunsi Fei</p>
    <p><b>Summary:</b> The transformer architecture has become a cornerstone of modern AI, fueling
remarkable progress across applications in natural language processing,
computer vision, and multimodal learning. As these models continue to scale
explosively for performance, implementation efficiency remains a critical
challenge. Mixture of Experts (MoE) architectures, selectively activating
specialized subnetworks (experts), offer a unique balance between model
accuracy and computational cost. However, the adaptive routing in MoE
architectures, where input tokens are dynamically directed to specialized
experts based on their semantic meaning inadvertently opens up a new attack
surface for privacy breaches. These input-dependent activation patterns leave
distinctive temporal and spatial traces in hardware execution, which
adversaries could exploit to deduce sensitive user data. In this work, we
propose MoEcho, discovering a side channel analysis based attack surface that
compromises user privacy on MoE based systems. Specifically, in MoEcho, we
introduce four novel architectural side channels on different computing
platforms, including Cache Occupancy Channels and Pageout+Reload on CPUs, and
Performance Counter and TLB Evict+Reload on GPUs, respectively. Exploiting
these vulnerabilities, we propose four attacks that effectively breach user
privacy in large language models (LLMs) and vision language models (VLMs) based
on MoE architectures: Prompt Inference Attack, Response Reconstruction Attack,
Visual Inference Attack, and Visual Reconstruction Attack. MoEcho is the first
runtime architecture level security analysis of the popular MoE structure
common in modern transformers, highlighting a serious security and privacy
threat and calling for effective and timely safeguards when harnessing MoE
based models for developing efficient large scale AI services.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.14815v1">A Lightweight Privacy-Preserving Smart Metering Billing Protocol with
  Dynamic Tariff Policy Adjustment</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-20T16:06:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Farid Zaredar, Morteza Amini</p>
    <p><b>Summary:</b> The integration of information and communication technology (ICT) with
traditional power grids has led to the emergence of smart grids. Advanced
metering infrastructure (AMI) plays a crucial role in smart grids by
facilitating two-way communication between smart meters and the utility
provider. This bidirectional communication allows intelligent meters to report
fine-grained consumption data at predefined intervals, enabling accurate
billing, efficient grid monitoring and management, and rapid outage detection.
However, the collection of detailed consumption data can inadvertently disclose
consumers' daily activities, raising privacy concerns and potentially leading
to privacy violations. To address these issues and preserve individuals'
privacy, we propose a lightweight privacy-preserving smart metering protocol
specifically designed to support real-time tariff billing service with dynamic
policy adjustment. Our scheme employs an efficient data perturbation technique
to obscure precise energy usage data from internal adversaries, including the
intermediary gateways and the utility provider. Subsequently, we validate the
efficiency and security of our protocol through comprehensive performance and
privacy evaluations. We examined the computational, memory, and communication
overhead of the proposed scheme. The execution time of our secure and
privacy-aware billing system is approximately 3.94540 seconds for a complete
year. Furthermore, we employed the Jensen-Shannon divergence as a privacy
metric to demonstrate that our protocol can effectively safeguard users'
privacy by increasing the noise scale.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.14744v1">A Collusion-Resistance Privacy-Preserving Smart Metering Protocol for
  Operational Utility</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-20T14:40:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Farid Zaredar, Morteza Amini</p>
    <p><b>Summary:</b> Modern grids have adopted advanced metering infrastructure (AMI) to
facilitate bidirectional communication between smart meters and control
centers. This enables smart meters to report consumption values at predefined
intervals to utility providers for purposes including demand balancing, load
forecasting, dynamic billing, and operational efficiency. Compared to
traditional power grids, smart grids offer advantages such as enhanced
reliability, improved energy efficiency, and increased security. However,
utility providers can compromise user privacy by analyzing fine-grained
readings and extracting individuals' daily activities from this time-series
data. To address this concern, we propose a collusion-resistant,
privacy-preserving aggregation protocol for smart metering in operational
services. Our protocol ensures privacy by leveraging techniques such as
partially additive homomorphic encryption, aggregation, data perturbation, and
data minimization. The scheme aggregates perturbed readings using the additive
homomorphic property of the Paillier cryptosystem to provide results for
multiple operational purposes. We evaluate the protocol in terms of both
performance and privacy. Computational, memory, and communication overhead were
examined. The total execution time with 1024-bit key size is about 2.21
seconds. We also evaluated privacy through the normalized conditional entropy
(NCE) metric. Higher NCE values, closer to 1, indicate stronger privacy. By
increasing noise scale, the NCE value rises, showing perturbed values retain
minimal information about the original, thereby reducing risks. Overall,
evaluation demonstrates the protocol's efficiency while employing various
privacy-preserving techniques.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.14703v1">A Lightweight Incentive-Based Privacy-Preserving Smart Metering Protocol
  for Value-Added Services</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-20T13:28:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Farid Zaredar, Morteza Amini</p>
    <p><b>Summary:</b> The emergence of smart grids and advanced metering infrastructure (AMI) has
revolutionized energy management. Unlike traditional power grids, smart grids
benefit from two-way communication through AMI, which surpasses earlier
automated meter reading (AMR). AMI enables diverse demand- and supply-side
utilities such as accurate billing, outage detection, real-time grid control,
load forecasting, and value-added services. Smart meters play a key role by
delivering consumption values at predefined intervals to the utility provider
(UP). However, such reports may raise privacy concerns, as adversaries can
infer lifestyle patterns, political orientations, and the types of electrical
devices in a household, or even sell the data to third parties (TP) such as
insurers. In this paper, we propose a lightweight, privacy-preserving smart
metering protocol for incentive-based value-added services. The scheme employs
local differential privacy, hash chains, blind digital signatures, pseudonyms,
temporal aggregation, and anonymous overlay networks to report coarse-grained
values with adjustable granularity to the UP. This protects consumers' privacy
while preserving data utility. The scheme prevents identity disclosure while
enabling automatic token redemption. From a performance perspective, our
results show that with a 1024-bit RSA key, a 7-day duration, and four reports
per day, our protocol runs in approximately 0.51s and consumes about 4.5 MB of
memory. From a privacy perspective, the protocol resists semi-trusted and
untrusted adversaries.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.15844v1">Ransomware Negotiation: Dynamics and Privacy-Preserving Mechanism Design</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-19T20:29:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haohui Zhang, Sirui Shen, Xinyu Hu, Chenglu Jin</p>
    <p><b>Summary:</b> Ransomware attacks have become a pervasive and costly form of cybercrime,
causing tens of millions of dollars in losses as organizations increasingly pay
ransoms to mitigate operational disruptions and financial risks. While prior
research has largely focused on proactive defenses, the post-infection
negotiation dynamics between attackers and victims remains underexplored. This
paper presents a formal analysis of attacker-victim interactions in modern
ransomware incidents using a finite-horizon alternating-offers bargaining game
model. Our analysis demonstrates how bargaining alters the optimal strategies
of both parties. In practice, incomplete information-attackers lacking
knowledge of victims' data valuations and victims lacking knowledge of
attackers' reservation ransoms-can prolong negotiations and increase victims'
business interruption costs. To address this, we design a Bayesian
incentive-compatible mechanism that facilitates rapid agreement on a fair
ransom without requiring either party to disclose private valuations. We
further implement this mechanism using secure two-party computation based on
garbled circuits, thereby eliminating the need for trusted intermediaries and
preserving the privacy of both parties throughout the negotiation. To the best
of our knowledge, this is the first automated, privacy-preserving negotiation
mechanism grounded in a formal analysis of ransomware negotiation dynamics.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.13914v1">Development of a defacing algorithm to protect the privacy of head and
  neck cancer patients in publicly-accessible radiotherapy datasets</a></h3>
  
  <p><b>Published on:</b> 2025-08-19T15:14:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kayla O'Sullivan-Steben, Luc Galarneau, John Kildea</p>
    <p><b>Summary:</b> Introduction: The rise in public medical imaging datasets has raised concerns
about patient reidentification from head CT scans. However, existing defacing
algorithms often remove or distort Organs at Risk (OARs) and Planning Target
Volumes (PTVs) in head and neck cancer (HNC) patients, and ignore DICOM-RT
Structure Set and Dose data. Therefore, we developed and validated a novel
automated defacing algorithm that preserves these critical structures while
removing identifiable features from HNC CTs and DICOM-RT data.
  Methods: Eye contours were used as landmarks to automate the removal of CT
pixels above the inferior-most eye slice and anterior to the eye midpoint.
Pixels within PTVs were retained if they intersected with the removed region.
The body contour and dose map were reshaped to reflect the defaced image. We
validated our approach on 829 HNC CTs from 622 patients. Privacy protection was
evaluated by applying the FaceNet512 facial recognition algorithm before and
after defacing on 3D-rendered CT pairs from 70 patients. Research utility was
assessed by examining the impact of defacing on autocontouring performance
using LimbusAI and analyzing PTV locations relative to the defaced regions.
  Results: Before defacing, FaceNet512 matched 97% of patients' CTs. After
defacing, this rate dropped to 4%. LimbusAI effectively autocontoured organs in
the defaced CTs, with perfect Dice scores of 1 for OARs below the defaced
region, and excellent scores exceeding 0.95 for OARs on the same slices as the
crop. We found that 86% of PTVs were entirely below the cropped region, 9.1%
were on the same slice as the crop without overlap, and only 4.9% extended into
the cropped area.
  Conclusions: We developed a novel defacing algorithm that anonymizes HNC CT
scans and related DICOM-RT data while preserving essential structures, enabling
the sharing of HNC imaging datasets for Big Data and AI.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.13730v1">On the Security and Privacy of Federated Learning: A Survey with
  Attacks, Defenses, Frameworks, Applications, and Future Directions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-08-19T11:06:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Daniel M. Jimenez-Gutierrez, Yelizaveta Falkouskaya, Jose L. Hernandez-Ramos, Aris Anagnostopoulos, Ioannis Chatzigiannakis, Andrea Vitaletti</p>
    <p><b>Summary:</b> Federated Learning (FL) is an emerging distributed machine learning paradigm
enabling multiple clients to train a global model collaboratively without
sharing their raw data. While FL enhances data privacy by design, it remains
vulnerable to various security and privacy threats. This survey provides a
comprehensive overview of more than 200 papers regarding the state-of-the-art
attacks and defense mechanisms developed to address these challenges,
categorizing them into security-enhancing and privacy-preserving techniques.
Security-enhancing methods aim to improve FL robustness against malicious
behaviors such as byzantine attacks, poisoning, and Sybil attacks. At the same
time, privacy-preserving techniques focus on protecting sensitive data through
cryptographic approaches, differential privacy, and secure aggregation. We
critically analyze the strengths and limitations of existing methods, highlight
the trade-offs between privacy, security, and model performance, and discuss
the implications of non-IID data distributions on the effectiveness of these
defenses. Furthermore, we identify open research challenges and future
directions, including the need for scalable, adaptive, and energy-efficient
solutions operating in dynamic and heterogeneous FL environments. Our survey
aims to guide researchers and practitioners in developing robust and
privacy-preserving FL systems, fostering advancements safeguarding
collaborative learning frameworks' integrity and confidentiality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.13425v1">When Secure Aggregation Falls Short: Achieving Long-Term Privacy in
  Asynchronous Federated Learning for LEO Satellite Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-19T00:55:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohamed Elmahallawy, Tie Luo</p>
    <p><b>Summary:</b> Secure aggregation is a common technique in federated learning (FL) for
protecting data privacy from both curious internal entities (clients or server)
and external adversaries (eavesdroppers). However, in dynamic and
resource-constrained environments such as low Earth orbit (LEO) satellite
networks, traditional secure aggregation methods fall short in two aspects: (1)
they assume continuous client availability while LEO satellite visibility is
intermittent and irregular; (2) they consider privacy in each communication
round but have overlooked the possible privacy leakage through multiple rounds.
To address these limitations, we propose LTP-FLEO, an asynchronous FL framework
that preserves long-term privacy (LTP) for LEO satellite networks. LTP-FLEO
introduces (i) privacy-aware satellite partitioning, which groups satellites
based on their predictable visibility to the server and enforces joint
participation; (ii) model age balancing, which mitigates the adverse impact of
stale model updates; and (iii) fair global aggregation, which treats satellites
of different visibility durations in an equitable manner. Theoretical analysis
and empirical validation demonstrate that LTP-FLEO effectively safeguards both
model and data privacy across multi-round training, promotes fairness in line
with satellite contributions, accelerates global convergence, and achieves
competitive model accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.12832v2">Efficient and Verifiable Privacy-Preserving Convolutional Computation
  for CNN Inference with Untrusted Clouds</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-08-18T11:17:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jinyu Lu, Xinrong Sun, Yunting Tao, Tong Ji, Fanyu Kong, Guoqiang Yang</p>
    <p><b>Summary:</b> The widespread adoption of convolutional neural networks (CNNs) in
resource-constrained scenarios has driven the development of Machine Learning
as a Service (MLaaS) system. However, this approach is susceptible to privacy
leakage, as the data sent from the client to the untrusted cloud server often
contains sensitive information. Existing CNN privacy-preserving schemes, while
effective in ensuring data confidentiality through homomorphic encryption and
secret sharing, face efficiency bottlenecks, particularly in convolution
operations. In this paper, we propose a novel verifiable privacy-preserving
scheme tailored for CNN convolutional layers. Our scheme enables efficient
encryption and decryption, allowing resource-constrained clients to securely
offload computations to the untrusted cloud server. Additionally, we present a
verification mechanism capable of detecting the correctness of the results with
a success probability of at least $1-\frac{1}{\left|Z\right|}$. Extensive
experiments conducted on 10 datasets and various CNN models demonstrate that
our scheme achieves speedups ranging $26 \times$ ~ $\ 87\times$ compared to the
original plaintext model while maintaining accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.12539v1">The Hidden Cost of Correlation: Rethinking Privacy Leakage in Local
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2025-08-18T00:34:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sandaru Jayawardana, Sennur Ulukus, Ming Ding, Kanchana Thilakarathna</p>
    <p><b>Summary:</b> Local differential privacy (LDP) has emerged as a promising paradigm for
privacy-preserving data collection in distributed systems, where users
contribute multi-dimensional records with potentially correlated attributes.
Recent work has highlighted that correlation-induced privacy leakage (CPL)
plays a critical role in shaping the privacy-utility trade-off under LDP,
especially when correlations exist among attributes. Nevertheless, it remains
unclear to what extent the prevailing assumptions and proposed solutions are
valid and how significant CPL is in real-world data. To address this gap, we
first perform a comprehensive statistical analysis of five widely used LDP
mechanisms -- GRR, RAPPOR, OUE, OLH and Exponential mechanism -- to assess CPL
across four real-world datasets. We identify that many primary assumptions and
metrics in current approaches fall short of accurately characterising these
leakages. Moreover, current studies have been limited to a set of pure LDP
(i.e., {\delta = 0}) mechanisms. In response, we develop the first algorithmic
framework to theoretically quantify CPL for any general approximated LDP
(({\varepsilon},{\delta})-LDP) mechanism. We validate our theoretical results
against empirical statistical results and provide a theoretical explanation for
the observed statistical patterns. Finally, we propose two novel benchmarks to
validate correlation analysis algorithms and evaluate the utility vs CPL of LDP
mechanisms. Further, we demonstrate how these findings can be applied to
achieve an efficient privacy-utility trade-off in real-world data governance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.12158v1">LLM-as-a-Judge for Privacy Evaluation? Exploring the Alignment of Human
  and LLM Perceptions of Privacy in Textual Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-08-16T20:49:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stephen Meisenbacher, Alexandra Klymenko, Florian Matthes</p>
    <p><b>Summary:</b> Despite advances in the field of privacy-preserving Natural Language
Processing (NLP), a significant challenge remains the accurate evaluation of
privacy. As a potential solution, using LLMs as a privacy evaluator presents a
promising approach $\unicode{x2013}$ a strategy inspired by its success in
other subfields of NLP. In particular, the so-called $\textit{LLM-as-a-Judge}$
paradigm has achieved impressive results on a variety of natural language
evaluation tasks, demonstrating high agreement rates with human annotators.
Recognizing that privacy is both subjective and difficult to define, we
investigate whether LLM-as-a-Judge can also be leveraged to evaluate the
privacy sensitivity of textual data. Furthermore, we measure how closely LLM
evaluations align with human perceptions of privacy in text. Resulting from a
study involving 10 datasets, 13 LLMs, and 677 human survey participants, we
confirm that privacy is indeed a difficult concept to measure empirically,
exhibited by generally low inter-human agreement rates. Nevertheless, we find
that LLMs can accurately model a global human privacy perspective, and through
an analysis of human and LLM reasoning patterns, we discuss the merits and
limitations of LLM-as-a-Judge for privacy evaluation in textual data. Our
findings pave the way for exploring the feasibility of LLMs as privacy
evaluators, addressing a core challenge in solving pressing privacy issues with
innovative technical solutions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.12093v2">PP-STAT: An Efficient Privacy-Preserving Statistical Analysis Framework
  using Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-16T16:24:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hyunmin Choi</p>
    <p><b>Summary:</b> With the widespread adoption of cloud computing, the need for outsourcing
statistical analysis to third-party platforms is growing rapidly. However,
handling sensitive data such as medical records and financial information in
cloud environments raises serious privacy concerns. In this paper, we present
PP-STAT, a novel and efficient Homomorphic Encryption (HE)-based framework for
privacy-preserving statistical analysis. HE enables computations to be
performed directly on encrypted data without revealing the underlying
plaintext. PP-STAT supports advanced statistical measures, including Z-score
normalization, skewness, kurtosis, coefficient of variation, and Pearson
correlation coefficient, all computed securely over encrypted data. To improve
efficiency, PP-STAT introduces two key optimizations: (1) a Chebyshev-based
approximation strategy for initializing inverse square root operations, and (2)
a pre-normalization scaling technique that reduces multiplicative depth by
folding constant scaling factors into mean and variance computations. These
techniques significantly lower computational overhead and minimize the number
of expensive bootstrapping procedures. Our evaluation on real-world datasets
demonstrates that PP-STAT achieves high numerical accuracy, with mean relative
error (MRE) below 2.4x10-4. Notably, the encrypted Pearson correlation between
the smoker attribute and charges reaches 0.7873, with an MRE of 2.86x10-4.
These results confirm the practical utility of PP-STAT for secure and precise
statistical analysis in privacy-sensitive domains.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.11907v1">Deciphering the Interplay between Attack and Protection Complexity in
  Privacy-Preserving Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-16T04:39:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaojin Zhang, Mingcong Xu, Yiming Li, Wei Chen, Qiang Yang</p>
    <p><b>Summary:</b> Federated learning (FL) offers a promising paradigm for collaborative model
training while preserving data privacy. However, its susceptibility to gradient
inversion attacks poses a significant challenge, necessitating robust privacy
protection mechanisms. This paper introduces a novel theoretical framework to
decipher the intricate interplay between attack and protection complexities in
privacy-preserving FL. We formally define "Attack Complexity" as the minimum
computational and data resources an adversary requires to reconstruct private
data below a given error threshold, and "Protection Complexity" as the expected
distortion introduced by privacy mechanisms. Leveraging Maximum Bayesian
Privacy (MBP), we derive tight theoretical bounds for protection complexity,
demonstrating its scaling with model dimensionality and privacy budget.
Furthermore, we establish comprehensive bounds for attack complexity, revealing
its dependence on privacy leakage, gradient distortion, model dimension, and
the chosen privacy level. Our findings quantitatively illuminate the
fundamental trade-offs between privacy guarantees, system utility, and the
effort required for both attacking and defending. This framework provides
critical insights for designing more secure and efficient federated learning
systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.11797v1">AegisBlock: A Privacy-Preserving Medical Research Framework using
  Blockchain</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-08-15T20:43:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Calkin Garg, Omar Rios Cruz, Tessa Andersen, Gaby G. Dagher, Donald Winiecki, Min Long</p>
    <p><b>Summary:</b> Due to HIPAA and other privacy regulations, it is imperative to maintain
patient privacy while conducting research on patient health records. In this
paper, we propose AegisBlock, a patient-centric access controlled framework to
share medical records with researchers such that the anonymity of the patient
is maintained while ensuring the trustworthiness of the data provided to
researchers. AegisBlock allows for patients to provide access to their medical
data, verified by miners. A researcher submits a time-based range query to
request access to records from a certain patient, and upon patient approval,
access will be granted. Our experimental evaluation results show that
AegisBlock is scalable with respect to the number of patients and hospitals in
the system, and efficient with up to 50% of malicious miners.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.11742v1">Assessing User Privacy Leakage in Synthetic Packet Traces: An
  Attack-Grounded Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2025-08-15T17:54:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Minhao Jin, Hongyu He, Maria Apostolaki</p>
    <p><b>Summary:</b> Current synthetic traffic generators (SynNetGens) promise privacy but lack
comprehensive guarantees or empirical validation, even as their fidelity
steadily improves. We introduce the first attack-grounded benchmark for
assessing the privacy of SynNetGens directly from the traffic they produce. We
frame privacy as membership inference at the traffic-source level--a realistic
and actionable threat for data holders. To this end, we present TraceBleed, the
first attack that exploits behavioral fingerprints across flows using
contrastive learning and temporal chunking, outperforming prior membership
inference baselines by 172%. Our large-scale study across GAN-, diffusion-, and
GPT-based SynNetGens uncovers critical insights: (i) SynNetGens leak user-level
information; (ii) differential privacy either fails to stop these attacks or
severely degrades fidelity; and (iii) sharing more synthetic data amplifies
leakage by 59% on average. Finally, we introduce TracePatch, the first
SynNetGen-agnostic defense that combines adversarial ML with SMT constraints to
mitigate leakage while preserving fidelity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.11575v1">Activate Me!: Designing Efficient Activation Functions for
  Privacy-Preserving Machine Learning with Fully Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-15T16:31:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nges Brian Njungle, Michel A. Kinsy</p>
    <p><b>Summary:</b> The growing adoption of machine learning in sensitive areas such as
healthcare and defense introduces significant privacy and security challenges.
These domains demand robust data protection, as models depend on large volumes
of sensitive information for both training and inference. Fully Homomorphic
Encryption (FHE) presents a compelling solution by enabling computations
directly on encrypted data, maintaining confidentiality across the entire
machine learning workflow. However, FHE inherently supports only linear
operations, making it difficult to implement non-linear activation functions,
essential components of modern neural networks. This work focuses on designing,
implementing, and evaluating activation functions tailored for FHE-based
machine learning. We investigate two commonly used functions: the Square
function and Rectified Linear Unit (ReLU), using LeNet-5 and ResNet-20
architectures with the CKKS scheme from the OpenFHE library. For ReLU, we
assess two methods: a conventional low-degree polynomial approximation and a
novel scheme-switching technique that securely evaluates ReLU under FHE
constraints. Our findings show that the Square function performs well in
shallow networks like LeNet-5, achieving 99.4% accuracy with 128 seconds per
image. In contrast, deeper models like ResNet-20 benefit more from ReLU. The
polynomial approximation yields 83.8% accuracy with 1,145 seconds per image,
while our scheme-switching method improves accuracy to 89.8%, albeit with a
longer inference time of 1,697 seconds. These results underscore a critical
trade-off in FHE-based ML: faster activation functions often reduce accuracy,
whereas those preserving accuracy demand greater computational resources.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.11495v1">KV-Auditor: Auditing Local Differential Privacy for Correlated Key-Value
  Estimation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-15T14:17:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jingnan Xu, Leixia Wang, Xiaofeng Meng</p>
    <p><b>Summary:</b> To protect privacy for data-collection-based services, local differential
privacy (LDP) is widely adopted due to its rigorous theoretical bound on
privacy loss. However, mistakes in complex theoretical analysis or subtle
implementation errors may undermine its practical guarantee. To address this,
auditing is crucial to confirm that LDP protocols truly protect user data.
However, existing auditing methods, though, mainly target machine learning and
federated learning tasks based on centralized differentially privacy (DP), with
limited attention to LDP. Moreover, the few studies on LDP auditing focus
solely on simple frequency estimation task for discrete data, leaving
correlated key-value data - which requires both discrete frequency estimation
for keys and continuous mean estimation for values - unexplored.
  To bridge this gap, we propose KV-Auditor, a framework for auditing LDP-based
key-value estimation mechanisms by estimating their empirical privacy lower
bounds. Rather than traditional LDP auditing methods that relies on binary
output predictions, KV-Auditor estimates this lower bound by analyzing
unbounded output distributions, supporting continuous data. Specifically, we
classify state-of-the-art LDP key-value mechanisms into interactive and
non-interactive types. For non-interactive mechanisms, we propose horizontal
KV-Auditor for small domains with sufficient samples and vertical KV-Auditor
for large domains with limited samples. For interactive mechanisms, we design a
segmentation strategy to capture incremental privacy leakage across iterations.
Finally, we perform extensive experiments to validate the effectiveness of our
approach, offering insights for optimizing LDP-based key-value estimators.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.11419v1">Training-free Dimensionality Reduction via Feature Truncation: Enhancing
  Efficiency in Privacy-preserving Multi-Biometric Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-08-15T11:49:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Florian Bayer, Maximilian Russo, Christian Rathgeb</p>
    <p><b>Summary:</b> Biometric recognition is widely used, making the privacy and security of
extracted templates a critical concern. Biometric Template Protection schemes,
especially those utilizing Homomorphic Encryption, introduce significant
computational challenges due to increased workload. Recent advances in deep
neural networks have enabled state-of-the-art feature extraction for face,
fingerprint, and iris modalities. The ubiquity and affordability of biometric
sensors further facilitate multi-modal fusion, which can enhance security by
combining features from different modalities. This work investigates the
biometric performance of reduced multi-biometric template sizes. Experiments
are conducted on an in-house virtual multi-biometric database, derived from
DNN-extracted features for face, fingerprint, and iris, using the FRGC, MCYT,
and CASIA databases. The evaluated approaches are (i) explainable and
straightforward to implement under encryption, (ii) training-free, and (iii)
capable of generalization. Dimensionality reduction of feature vectors leads to
fewer operations in the Homomorphic Encryption (HE) domain, enabling more
efficient encrypted processing while maintaining biometric accuracy and
security at a level equivalent to or exceeding single-biometric recognition.
Our results demonstrate that, by fusing feature vectors from multiple
modalities, template size can be reduced by 67 % with no loss in Equal Error
Rate (EER) compared to the best-performing single modality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.11115v1">UWB-PostureGuard: A Privacy-Preserving RF Sensing System for Continuous
  Ergonomic Sitting Posture Monitoring</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> 
  <p><b>Published on:</b> 2025-08-14T23:40:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haotang Li, Zhenyu Qi, Sen He, Kebin Peng, Sheng Tan, Yili Ren, Tomas Cerny, Jiyue Zhao, Zi Wang</p>
    <p><b>Summary:</b> Improper sitting posture during prolonged computer use has become a
significant public health concern. Traditional posture monitoring solutions
face substantial barriers, including privacy concerns with camera-based systems
and user discomfort with wearable sensors. This paper presents
UWB-PostureGuard, a privacy-preserving ultra-wideband (UWB) sensing system that
advances mobile technologies for preventive health management through
continuous, contactless monitoring of ergonomic sitting posture. Our system
leverages commercial UWB devices, utilizing comprehensive feature engineering
to extract multiple ergonomic sitting posture features. We develop PoseGBDT to
effectively capture temporal dependencies in posture patterns, addressing
limitations of traditional frame-wise classification approaches. Extensive
real-world evaluation across 10 participants and 19 distinct postures
demonstrates exceptional performance, achieving 99.11% accuracy while
maintaining robustness against environmental variables such as clothing
thickness, additional devices, and furniture configurations. Our system
provides a scalable, privacy-preserving mobile health solution on existing
platforms for proactive ergonomic management, improving quality of life at low
costs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.10880v1">Searching for Privacy Risks in LLM Agents via Simulation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-08-14T17:49:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yanzhe Zhang, Diyi Yang</p>
    <p><b>Summary:</b> The widespread deployment of LLM-based agents is likely to introduce a
critical privacy threat: malicious agents that proactively engage others in
multi-turn interactions to extract sensitive information. These dynamic
dialogues enable adaptive attack strategies that can cause severe privacy
violations, yet their evolving nature makes it difficult to anticipate and
discover sophisticated vulnerabilities manually. To tackle this problem, we
present a search-based framework that alternates between improving attacker and
defender instructions by simulating privacy-critical agent interactions. Each
simulation involves three roles: data subject, data sender, and data recipient.
While the data subject's behavior is fixed, the attacker (data recipient)
attempts to extract sensitive information from the defender (data sender)
through persistent and interactive exchanges. To explore this interaction space
efficiently, our search algorithm employs LLMs as optimizers, using parallel
search with multiple threads and cross-thread propagation to analyze simulation
trajectories and iteratively propose new instructions. Through this process, we
find that attack strategies escalate from simple direct requests to
sophisticated multi-turn tactics such as impersonation and consent forgery,
while defenses advance from rule-based constraints to identity-verification
state machines. The discovered attacks and defenses transfer across diverse
scenarios and backbone models, demonstrating strong practical utility for
building privacy-aware agents.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.11716v2">Privacy-Aware Detection of Fake Identity Documents: Methodology,
  Benchmark, and Improved Algorithms (FakeIDet2)</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> 
  <p><b>Published on:</b> 2025-08-14T17:30:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Javier Muñoz-Haro, Ruben Tolosana, Julian Fierrez, Ruben Vera-Rodriguez, Aythami Morales</p>
    <p><b>Summary:</b> Remote user verification in Internet-based applications is becoming
increasingly important nowadays. A popular scenario for it consists of
submitting a picture of the user's Identity Document (ID) to a service
platform, authenticating its veracity, and then granting access to the
requested digital service. An ID is well-suited to verify the identity of an
individual, since it is government issued, unique, and nontransferable.
However, with recent advances in Artificial Intelligence (AI), attackers can
surpass security measures in IDs and create very realistic physical and
synthetic fake IDs. Researchers are now trying to develop methods to detect an
ever-growing number of these AI-based fakes that are almost indistinguishable
from authentic (bona fide) IDs. In this counterattack effort, researchers are
faced with an important challenge: the difficulty in using real data to train
fake ID detectors. This real data scarcity for research and development is
originated by the sensitive nature of these documents, which are usually kept
private by the ID owners (the users) and the ID Holders (e.g., government,
police, bank, etc.). The main contributions of our study are: 1) We propose and
discuss a patch-based methodology to preserve privacy in fake ID detection
research. 2) We provide a new public database, FakeIDet2-db, comprising over
900K real/fake ID patches extracted from 2,000 ID images, acquired using
different smartphone sensors, illumination and height conditions, etc. In
addition, three physical attacks are considered: print, screen, and composite.
3) We present a new privacy-aware fake ID detection method, FakeIDet2. 4) We
release a standard reproducible benchmark that considers physical and synthetic
attacks from popular databases in the literature.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.10737v1">Privacy-enhancing Sclera Segmentation Benchmarking Competition: SSBC
  2025</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-08-14T15:16:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Matej Vitek, Darian Tomašević, Abhijit Das, Sabari Nathan, Gökhan Özbulak, Gözde Ayşe Tataroğlu Özbulak, Jean-Paul Calbimonte, André Anjos, Hariohm Hemant Bhatt, Dhruv Dhirendra Premani, Jay Chaudhari, Caiyong Wang, Jian Jiang, Chi Zhang, Qi Zhang, Iyyakutti Iyappan Ganapathi, Syed Sadaf Ali, Divya Velayudan, Maregu Assefa, Naoufel Werghi, Zachary A. Daniels, Leeon John, Ritesh Vyas, Jalil Nourmohammadi Khiarak, Taher Akbari Saeed, Mahsa Nasehi, Ali Kianfar, Mobina Pashazadeh Panahi, Geetanjali Sharma, Pushp Raj Panth, Raghavendra Ramachandra, Aditya Nigam, Umapada Pal, Peter Peer, Vitomir Štruc</p>
    <p><b>Summary:</b> This paper presents a summary of the 2025 Sclera Segmentation Benchmarking
Competition (SSBC), which focused on the development of privacy-preserving
sclera-segmentation models trained using synthetically generated ocular images.
The goal of the competition was to evaluate how well models trained on
synthetic data perform in comparison to those trained on real-world datasets.
The competition featured two tracks: $(i)$ one relying solely on synthetic data
for model development, and $(ii)$ one combining/mixing synthetic with (a
limited amount of) real-world data. A total of nine research groups submitted
diverse segmentation models, employing a variety of architectural designs,
including transformer-based solutions, lightweight models, and segmentation
networks guided by generative frameworks. Experiments were conducted across
three evaluation datasets containing both synthetic and real-world images,
collected under diverse conditions. Results show that models trained entirely
on synthetic data can achieve competitive performance, particularly when
dedicated training strategies are employed, as evidenced by the top performing
models that achieved $F_1$ scores of over $0.8$ in the synthetic data track.
Moreover, performance gains in the mixed track were often driven more by
methodological choices rather than by the inclusion of real data, highlighting
the promise of synthetic data for privacy-aware biometric development. The code
and data for the competition is available at:
https://github.com/dariant/SSBC_2025.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.10672v2">Hybrid Generative Fusion for Efficient and Privacy-Preserving Face
  Recognition Dataset Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-14T14:14:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Feiran Li, Qianqian Xu, Shilong Bao, Boyu Han, Zhiyong Yang, Qingming Huang</p>
    <p><b>Summary:</b> In this paper, we present our approach to the DataCV ICCV Challenge, which
centers on building a high-quality face dataset to train a face recognition
model. The constructed dataset must not contain identities overlapping with any
existing public face datasets. To handle this challenge, we begin with a
thorough cleaning of the baseline HSFace dataset, identifying and removing
mislabeled or inconsistent identities through a Mixture-of-Experts (MoE)
strategy combining face embedding clustering and GPT-4o-assisted verification.
We retain the largest consistent identity cluster and apply data augmentation
up to a fixed number of images per identity. To further diversify the dataset,
we generate synthetic identities using Stable Diffusion with prompt
engineering. As diffusion models are computationally intensive, we generate
only one reference image per identity and efficiently expand it using Vec2Face,
which rapidly produces 49 identity-consistent variants. This hybrid approach
fuses GAN-based and diffusion-based samples, enabling efficient construction of
a diverse and high-quality dataset. To address the high visual similarity among
synthetic identities, we adopt a curriculum learning strategy by placing them
early in the training schedule, allowing the model to progress from easier to
harder samples. Our final dataset contains 50 images per identity, and all
newly generated identities are checked with mainstream face datasets to ensure
no identity leakage. Our method achieves \textbf{1st place} in the competition,
and experimental results show that our dataset improves model performance
across 10K, 20K, and 100K identity scales. Code is available at
https://github.com/Ferry-Li/datacv_fr.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.10482v2">When Explainability Meets Privacy: An Investigation at the Intersection
  of Post-hoc Explainability and Differential Privacy in the Context of Natural
  Language Processing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-08-14T09:34:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mahdi Dhaini, Stephen Meisenbacher, Ege Erdogan, Florian Matthes, Gjergji Kasneci</p>
    <p><b>Summary:</b> In the study of trustworthy Natural Language Processing (NLP), a number of
important research fields have emerged, including that of explainability and
privacy. While research interest in both explainable and privacy-preserving NLP
has increased considerably in recent years, there remains a lack of
investigation at the intersection of the two. This leaves a considerable gap in
understanding of whether achieving both explainability and privacy is possible,
or whether the two are at odds with each other. In this work, we conduct an
empirical investigation into the privacy-explainability trade-off in the
context of NLP, guided by the popular overarching methods of Differential
Privacy (DP) and Post-hoc Explainability. Our findings include a view into the
intricate relationship between privacy and explainability, which is formed by a
number of factors, including the nature of the downstream task and choice of
the text privatization and explainability method. In this, we highlight the
potential for privacy and explainability to co-exist, and we summarize our
findings in a collection of practical recommendations for future work at this
important intersection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.10469v1">Enhanced Sparse Point Cloud Data Processing for Privacy-aware Human
  Action Recognition</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-14T09:09:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maimunatu Tunau, Vincent Gbouna Zakka, Zhuangzhuang Dai</p>
    <p><b>Summary:</b> Human Action Recognition (HAR) plays a crucial role in healthcare, fitness
tracking, and ambient assisted living technologies. While traditional vision
based HAR systems are effective, they pose privacy concerns. mmWave radar
sensors offer a privacy preserving alternative but present challenges due to
the sparse and noisy nature of their point cloud data. In the literature, three
primary data processing methods: Density-Based Spatial Clustering of
Applications with Noise (DBSCAN), the Hungarian Algorithm, and Kalman Filtering
have been widely used to improve the quality and continuity of radar data.
However, a comprehensive evaluation of these methods, both individually and in
combination, remains lacking. This paper addresses that gap by conducting a
detailed performance analysis of the three methods using the MiliPoint dataset.
We evaluate each method individually, all possible pairwise combinations, and
the combination of all three, assessing both recognition accuracy and
computational cost. Furthermore, we propose targeted enhancements to the
individual methods aimed at improving accuracy. Our results provide crucial
insights into the strengths and trade-offs of each method and their
integrations, guiding future work on mmWave based HAR systems</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.10373v1">Privacy-Preserving Approximate Nearest Neighbor Search on
  High-Dimensional Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2025-08-14T06:09:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yingfan Liu, Yandi Zhang, Jiadong Xie, Hui Li, Jeffrey Xu Yu, Jiangtao Cui</p>
    <p><b>Summary:</b> In the era of cloud computing and AI, data owners outsource ubiquitous
vectors to the cloud, which furnish approximate $k$-nearest neighbors
($k$-ANNS) services to users. To protect data privacy against the untrusted
server, privacy-preserving $k$-ANNS (PP-ANNS) on vectors has been a fundamental
and urgent problem. However, existing PP-ANNS solutions fall short of meeting
the requirements of data privacy, efficiency, accuracy, and minimal user
involvement concurrently. To tackle this challenge, we introduce a novel
solution that primarily executes PP-ANNS on a single cloud server to avoid the
heavy communication overhead between the cloud and the user. To ensure data
privacy, we introduce a novel encryption method named distance comparison
encryption, facilitating secure, efficient, and exact distance comparisons. To
optimize the trade-off between data privacy and search performance, we design a
privacy-preserving index that combines the state-of-the-art $k$-ANNS method
with an approximate distance computation method. Then, we devise a search
method using a filter-and-refine strategy based on the index. Moreover, we
provide the security analysis of our solution and conduct extensive experiments
to demonstrate its superiority over existing solutions. Based on our
experimental results, our method accelerates PP-ANNS by up to 3 orders of
magnitude compared to state-of-the-art methods, while not compromising the
accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.09882v1">Location Privacy-Enabled Beamforming in ISAC Scenarios</a></h3>
  
  <p><b>Published on:</b> 2025-08-13T15:32:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Umair Ali Khan, Lester Ho, Holger Claussen, Chinmoy Kundu</p>
    <p><b>Summary:</b> Integrated sensing and communication (ISAC) technology enables simultaneous
environmental perception and data transmission in wireless networks; however,
it also exposes user location to receivers. In this paper, we introduce a novel
beamforming framework guided by the proposed privacy metric direction of
arrival obfuscation ratio (DAOR) to protect transmitter location privacy in
ISAC scenarios. Unlike previous approaches, we do not suppress the
line-of-sight (LOS) component while reshaping the angular power distribution so
that a false direction appears dominant at the receiver. We derive closed-form
bounds on the feasible DAOR via generalized eigenvalue analysis and formulate
an achievable rate-maximization problem under the DAOR constraint. The
resulting problem is non-convex, which is efficiently solved using semidefinite
relaxation, eigenmode selection, and optimal power allocation. A suboptimal
design strategy is also proposed with reduced complexity. Numerical results
demonstrate that the proposed DAOR-based beamformer achieves a trade-off
between location privacy and communication rate without nullifying the LOS
path. Results also show that a suboptimal design achieves a near-optimal
communication rate with nearly an 85% reduction in computation time at a
signal-to-noise ratio (SNR) of 10 dB.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.09442v1">Shadow in the Cache: Unveiling and Mitigating Privacy Risks of KV-cache
  in LLM Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-08-13T02:48:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhifan Luo, Shuo Shao, Su Zhang, Lijing Zhou, Yuke Hu, Chenxu Zhao, Zhihao Liu, Zhan Qin</p>
    <p><b>Summary:</b> The Key-Value (KV) cache, which stores intermediate attention computations
(Key and Value pairs) to avoid redundant calculations, is a fundamental
mechanism for accelerating Large Language Model (LLM) inference. However, this
efficiency optimization introduces significant yet underexplored privacy risks.
This paper provides the first comprehensive analysis of these vulnerabilities,
demonstrating that an attacker can reconstruct sensitive user inputs directly
from the KV-cache. We design and implement three distinct attack vectors: a
direct Inversion Attack, a more broadly applicable and potent Collision Attack,
and a semantic-based Injection Attack. These methods demonstrate the
practicality and severity of KV-cache privacy leakage issues. To mitigate this,
we propose KV-Cloak, a novel, lightweight, and efficient defense mechanism.
KV-Cloak uses a reversible matrix-based obfuscation scheme, combined with
operator fusion, to secure the KV-cache. Our extensive experiments show that
KV-Cloak effectively thwarts all proposed attacks, reducing reconstruction
quality to random noise. Crucially, it achieves this robust security with
virtually no degradation in model accuracy and minimal performance overhead,
offering a practical solution for trustworthy LLM deployment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.09426v1">Security Analysis of ChatGPT: Threats and Privacy Risks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-13T02:03:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yushan Xiang, Zhongwen Li, Xiaoqi Li</p>
    <p><b>Summary:</b> As artificial intelligence technology continues to advance, chatbots are
becoming increasingly powerful. Among them, ChatGPT, launched by OpenAI, has
garnered widespread attention globally due to its powerful natural language
processing capabilities based on the GPT model, which enables it to engage in
natural conversations with users, understand various forms of linguistic
expressions, and generate useful information and suggestions. However, as its
application scope expands, user demand grows, and malicious attacks related to
it become increasingly frequent, the security threats and privacy risks faced
by ChatGPT are gradually coming to the forefront. In this paper, the security
of ChatGPT is mainly studied from two aspects, security threats and privacy
risks. The article systematically analyzes various types of vulnerabilities
involved in the above two types of problems and their causes. Briefly, we
discuss the controversies that ChatGPT may cause at the ethical and moral
levels. In addition, this paper reproduces several network attack and defense
test scenarios by simulating the attacker's perspective and methodology.
Simultaneously, it explores the feasibility of using ChatGPT for security
vulnerability detection and security tool generation from the defender's
perspective.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.09245v1">Beyond Blanket Masking: Examining Granularity for Privacy Protection in
  Images Captured by Blind and Low Vision Users</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-08-12T17:56:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jeffri Murrugarra-LLerena, Haoran Niu, K. Suzanne Barber, Hal Daumé III, Yang Trista Cao, Paola Cascante-Bonilla</p>
    <p><b>Summary:</b> As visual assistant systems powered by visual language models (VLMs) become
more prevalent, concerns over user privacy have grown, particularly for blind
and low vision users who may unknowingly capture personal private information
in their images. Existing privacy protection methods rely on coarse-grained
segmentation, which uniformly masks entire private objects, often at the cost
of usability. In this work, we propose FiGPriv, a fine-grained privacy
protection framework that selectively masks only high-risk private information
while preserving low-risk information. Our approach integrates fine-grained
segmentation with a data-driven risk scoring mechanism. We evaluate our
framework using the BIV-Priv-Seg dataset and show that FiG-Priv preserves +26%
of image content, enhancing the ability of VLMs to provide useful responses by
11% and identify the image content by 45%, while ensuring privacy protection.
Project Page: https://artcs1.github.io/VLMPrivacy/</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.09036v1">Can We Trust AI to Govern AI? Benchmarking LLM Performance on Privacy
  and AI Governance Exams</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-12T15:57:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zane Witherspoon, Thet Mon Aye, YingYing Hao</p>
    <p><b>Summary:</b> The rapid emergence of large language models (LLMs) has raised urgent
questions across the modern workforce about this new technology's strengths,
weaknesses, and capabilities. For privacy professionals, the question is
whether these AI systems can provide reliable support on regulatory compliance,
privacy program management, and AI governance. In this study, we evaluate ten
leading open and closed LLMs, including models from OpenAI, Anthropic, Google
DeepMind, Meta, and DeepSeek, by benchmarking their performance on
industry-standard certification exams: CIPP/US, CIPM, CIPT, and AIGP from the
International Association of Privacy Professionals (IAPP). Each model was
tested using official sample exams in a closed-book setting and compared to
IAPP's passing thresholds. Our findings show that several frontier models such
as Gemini 2.5 Pro and OpenAI's GPT-5 consistently achieve scores exceeding the
standards for professional human certification - demonstrating substantial
expertise in privacy law, technical controls, and AI governance. The results
highlight both the strengths and domain-specific gaps of current LLMs and offer
practical insights for privacy officers, compliance leads, and technologists
assessing the readiness of AI tools for high-stakes data governance roles. This
paper provides an overview for professionals navigating the intersection of AI
advancement and regulatory risk and establishes a machine benchmark based on
human-centric evaluations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.08785v1">Privacy-protected Retrieval-Augmented Generation for Knowledge Graph
  Question Answering</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-08-12T09:38:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yunfeng Ning, Mayi Xu, Jintao Wen, Qiankun Pi, Yuanyuan Zhu, Ming Zhong, Jiawei Jiang, Tieyun Qian</p>
    <p><b>Summary:</b> LLMs often suffer from hallucinations and outdated or incomplete knowledge.
RAG is proposed to address these issues by integrating external knowledge like
that in KGs into LLMs. However, leveraging private KGs in RAG systems poses
significant privacy risks due to the black-box nature of LLMs and potential
insecure data transmission, especially when using third-party LLM APIs lacking
transparency and control. In this paper, we investigate the privacy-protected
RAG scenario for the first time, where entities in KGs are anonymous for LLMs,
thus preventing them from accessing entity semantics. Due to the loss of
semantics of entities, previous RAG systems cannot retrieve question-relevant
knowledge from KGs by matching questions with the meaningless identifiers of
anonymous entities. To realize an effective RAG system in this scenario, two
key challenges must be addressed: (1) How can anonymous entities be converted
into retrievable information. (2) How to retrieve question-relevant anonymous
entities. Hence, we propose a novel ARoG framework including relation-centric
abstraction and structure-oriented abstraction strategies. For challenge (1),
the first strategy abstracts entities into high-level concepts by dynamically
capturing the semantics of their adjacent relations. It supplements meaningful
semantics which can further support the retrieval process. For challenge (2),
the second strategy transforms unstructured natural language questions into
structured abstract concept paths. These paths can be more effectively aligned
with the abstracted concepts in KGs, thereby improving retrieval performance.
To guide LLMs to effectively retrieve knowledge from KGs, the two strategies
strictly protect privacy from being exposed to LLMs. Experiments on three
datasets demonstrate that ARoG achieves strong performance and
privacy-robustness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.08749v2">Approximate DBSCAN under Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2025-08-12T08:55:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuan Qiu, Ke Yi</p>
    <p><b>Summary:</b> This paper revisits the DBSCAN problem under differential privacy (DP).
Existing DP-DBSCAN algorithms aim at publishing the cluster labels of the input
points. However, we show that both empirically and theoretically, this approach
cannot offer any utility in the published results. We therefore propose an
alternative definition of DP-DBSCAN based on the notion of spans. We argue that
publishing the spans actually better serves the purposes of visualization and
classification of DBSCAN. Then we present a linear-time DP-DBSCAN algorithm
achieving the sandwich quality guarantee in any constant dimensions, as well as
matching lower bounds on the approximation ratio. A key building block in our
algorithm is a linear-time algorithm for constructing a histogram under
pure-DP, which is of independent interest. Finally, we conducted experiments on
both synthetic and real-world datasets to verify the practical performance of
our DP-DBSCAN algorithm.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.09232v1">PETLP: A Privacy-by-Design Pipeline for Social Media Data in AI Research</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Multimedia-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2025-08-12T08:33:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nick Oh, Giorgos D. Vrakas, Siân J. M. Brooke, Sasha Morinière, Toju Duke</p>
    <p><b>Summary:</b> Social media data presents AI researchers with overlapping obligations under
the GDPR, copyright law, and platform terms -- yet existing frameworks fail to
integrate these regulatory domains, leaving researchers without unified
guidance. We introduce PETLP (Privacy-by-design Extract, Transform, Load, and
Present), a compliance framework that embeds legal safeguards directly into
extended ETL pipelines. Central to PETLP is treating Data Protection Impact
Assessments as living documents that evolve from pre-registration through
dissemination. Through systematic Reddit analysis, we demonstrate how
extraction rights fundamentally differ between qualifying research
organisations (who can invoke DSM Article 3 to override platform restrictions)
and commercial entities (bound by terms of service), whilst GDPR obligations
apply universally. We reveal why true anonymisation remains unachievable for
social media data and expose the legal gap between permitted dataset creation
and uncertain model distribution. By structuring compliance decisions into
practical workflows and simplifying institutional data management plans, PETLP
enables researchers to navigate regulatory complexity with confidence, bridging
the gap between legal requirements and research practice.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.14905v1">Privacy Preserving Inference of Personalized Content for Out of Matrix
  Users</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-08-12T02:55:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Michael Sun, Tai Vu, Andrew Wang</p>
    <p><b>Summary:</b> Recommender systems for niche and dynamic communities face persistent
challenges from data sparsity, cold start users and items, and privacy
constraints. Traditional collaborative filtering and content-based approaches
underperform in these settings, either requiring invasive user data or failing
when preference histories are absent. We present DeepNaniNet, a deep neural
recommendation framework that addresses these challenges through an inductive
graph-based architecture combining user-item interactions, item-item relations,
and rich textual review embeddings derived from BERT. Our design enables cold
start recommendations without profile mining, using a novel "content basket"
user representation and an autoencoder-based generalization strategy for unseen
users. We introduce AnimeULike, a new dataset of 10,000 anime titles and 13,000
users, to evaluate performance in realistic scenarios with high proportions of
guest or low-activity users. DeepNaniNet achieves state-of-the-art cold start
results on the CiteULike benchmark, matches DropoutNet in user recall without
performance degradation for out-of-matrix users, and outperforms Weighted
Matrix Factorization (WMF) and DropoutNet on AnimeULike warm start by up to 7x
and 1.5x in Recall@100, respectively. Our findings demonstrate that DeepNaniNet
delivers high-quality, privacy-preserving recommendations in data-sparse, cold
start-heavy environments while effectively integrating heterogeneous content
sources.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.00006v1">Case Studies: Effective Approaches for Navigating Cross-Border Cloud
  Data Transfers Amid U.S. Government Privacy and Safety Concerns</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-08-12T01:35:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Motunrayo Adebayo</p>
    <p><b>Summary:</b> This study attempts to explain the impact of information exchange from one
country to another, as well as the legal and technological implications for
these exchanges. Due to the emergence of cloud technology, possibilities for
free exchange of information between countries have increased rapidly, as it
has become possible to save information in a country and access it in almost
any part of the world. Countries all around the world have been confronted with
developing frameworks to facilitate this process, although there are
significant challenges which must be confronted on legal and technological
fronts, as loopholes in the framework adopted by countries may hinder free
access to information stored on cloud, and also compromise data privacy. Cloud
technology is impacting a lot of issues, including domestic and international
businesses, hence the need for a study to propose measures for safe exchange of
information using cloud technology.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.08502v1">AirSignatureDB: Exploring In-Air Signature Biometrics in the Wild and
  its Privacy Concerns</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-08-11T22:24:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marta Robledo-Moreno, Ruben Vera-Rodriguez, Ruben Tolosana, Javier Ortega-Garcia, Andres Huergo, Julian Fierrez</p>
    <p><b>Summary:</b> Behavioral biometrics based on smartphone motion sensors are growing in
popularity for authentication purposes. In this study, AirSignatureDB is
presented: a new publicly accessible dataset of in-air signatures collected
from 108 participants under real-world conditions, using 83 different
smartphone models across four sessions. This dataset includes genuine samples
and skilled forgeries, enabling a comprehensive evaluation of system robustness
against realistic attack scenarios. Traditional and deep learning-based methods
for in-air signature verification are benchmarked, while analyzing the
influence of sensor modality and enrollment strategies. Beyond verification, a
first approach to reconstructing the three-dimensional trajectory of in-air
signatures from inertial sensor data alone is introduced. Using on-line
handwritten signatures as a reference, we demonstrate that the recovery of
accurate trajectories is feasible, challenging the long-held assumption that
in-air gestures are inherently traceless. Although this approach enables
forensic traceability, it also raises critical questions about the privacy
boundaries of behavioral biometrics. Our findings underscore the need for a
reevaluation of the privacy assumptions surrounding inertial sensor data, as
they can reveal user-specific information that had not previously been
considered in the design of in-air signature systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.08190v1">Differential Privacy for Regulatory Compliance in Cyberattack Detection
  on Critical Infrastructure Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-11T17:10:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Paritosh Ramanan, H. M. Mohaimanul Islam, Abhiram Reddy Alugula</p>
    <p><b>Summary:</b> Industrial control systems are a fundamental component of critical
infrastructure networks (CIN) such as gas, water and power. With the growing
risk of cyberattacks, regulatory compliance requirements are also increasing
for large scale critical infrastructure systems comprising multiple utility
stakeholders. The primary goal of regulators is to ensure overall system
stability with recourse to trustworthy stakeholder attack detection. However,
adhering to compliance requirements requires stakeholders to also disclose
sensor and control data to regulators raising privacy concerns. In this paper,
we present a cyberattack detection framework that utilizes differentially
private (DP) hypothesis tests geared towards enhancing regulatory confidence
while alleviating privacy concerns of CIN stakeholders. The hallmark of our
approach is a two phase privacy scheme that protects the privacy of covariance,
as well as the associated sensor driven test statistics computed as a means to
generate alarms. Theoretically, we show that our method induces a
misclassification error rate comparable to the non-DP cases while delivering
robust privacy guarantees. With the help of real-world datasets, we show the
reliability of our DP-detection outcomes for a wide variety of attack scenarios
for interdependent stakeholders.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.07960v1">VOIDFace: A Privacy-Preserving Multi-Network Face Recognition With
  Enhanced Security</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-08-11T13:15:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ajnas Muhammed, Iurri Medvedev, Nuno Gonçalves</p>
    <p><b>Summary:</b> Advancement of machine learning techniques, combined with the availability of
large-scale datasets, has significantly improved the accuracy and efficiency of
facial recognition. Modern facial recognition systems are trained using large
face datasets collected from diverse individuals or public repositories.
However, for training, these datasets are often replicated and stored in
multiple workstations, resulting in data replication, which complicates
database management and oversight. Currently, once a user submits their face
for dataset preparation, they lose control over how their data is used, raising
significant privacy and ethical concerns. This paper introduces VOIDFace, a
novel framework for facial recognition systems that addresses two major issues.
First, it eliminates the need of data replication and improves data control to
securely store training face data by using visual secret sharing. Second, it
proposes a patch-based multi-training network that uses this novel training
data storage mechanism to develop a robust, privacy-preserving facial
recognition system. By integrating these advancements, VOIDFace aims to improve
the privacy, security, and efficiency of facial recognition training, while
ensuring greater control over sensitive personal face data. VOIDFace also
enables users to exercise their Right-To-Be-Forgotten property to control their
personal data. Experimental evaluations on the VGGFace2 dataset show that
VOIDFace provides Right-To-Be-Forgotten, improved data control, security, and
privacy while maintaining competitive facial recognition performance. Code is
available at: https://github.com/ajnasmuhammed89/VOIDFace</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.07676v1">Multi-Hop Privacy Propagation for Differentially Private Federated
  Learning in Social Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB">
  <p><b>Published on:</b> 2025-08-11T06:53:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chenchen Lin, Xuehe Wang</p>
    <p><b>Summary:</b> Federated learning (FL) enables collaborative model training across
decentralized clients without sharing local data, thereby enhancing privacy and
facilitating collaboration among clients connected via social networks.
However, these social connections introduce privacy externalities: a client's
privacy loss depends not only on its privacy protection strategy but also on
the privacy decisions of others, propagated through the network via multi-hop
interactions. In this work, we propose a socially-aware privacy-preserving FL
mechanism that systematically quantifies indirect privacy leakage through a
multi-hop propagation model. We formulate the server-client interaction as a
two-stage Stackelberg game, where the server, as the leader, optimizes
incentive policies, and clients, as followers, strategically select their
privacy budgets, which determine their privacy-preserving levels by controlling
the magnitude of added noise. To mitigate information asymmetry in networked
privacy estimation, we introduce a mean-field estimator to approximate the
average external privacy risk. We theoretically prove the existence and
convergence of the fixed point of the mean-field estimator and derive
closed-form expressions for the Stackelberg Nash Equilibrium. Despite being
designed from a client-centric incentive perspective, our mechanism achieves
approximately-optimal social welfare, as revealed by Price of Anarchy (PoA)
analysis. Experiments on diverse datasets demonstrate that our approach
significantly improves client utilities and reduces server costs while
maintaining model performance, outperforming both Social-Agnostic (SA)
baselines and methods that account for social externalities.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.07672v1">Towards Aligning Personalized Conversational Recommendation Agents with
  Users' Privacy Preferences</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-08-11T06:51:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuning Zhang, Ying Ma, Jingruo Chen, Simin Li, Xin Yi, Hewu Li</p>
    <p><b>Summary:</b> The proliferation of AI agents, with their complex and context-dependent
actions, renders conventional privacy paradigms obsolete. This position paper
argues that the current model of privacy management, rooted in a user's
unilateral control over a passive tool, is inherently mismatched with the
dynamic and interactive nature of AI agents. We contend that ensuring effective
privacy protection necessitates that the agents proactively align with users'
privacy preferences instead of passively waiting for the user to control. To
ground this shift, and using personalized conversational recommendation agents
as a case, we propose a conceptual framework built on Contextual Integrity (CI)
theory and Privacy Calculus theory. This synthesis first reframes automatically
controlling users' privacy as an alignment problem, where AI agents initially
did not know users' preferences, and would learn their privacy preferences
through implicit or explicit feedback. Upon receiving the preference feedback,
the agents used alignment and Pareto optimization for aligning preferences and
balancing privacy and utility. We introduced formulations and instantiations,
potential applications, as well as five challenges.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.07667v1">1-2-3 Check: Enhancing Contextual Privacy in LLM via Multi-Agent
  Reasoning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-11T06:34:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenkai Li, Liwen Sun, Zhenxiang Guan, Xuhui Zhou, Maarten Sap</p>
    <p><b>Summary:</b> Addressing contextual privacy concerns remains challenging in interactive
settings where large language models (LLMs) process information from multiple
sources (e.g., summarizing meetings with private and public information). We
introduce a multi-agent framework that decomposes privacy reasoning into
specialized subtasks (extraction, classification), reducing the information
load on any single agent while enabling iterative validation and more reliable
adherence to contextual privacy norms. To understand how privacy errors emerge
and propagate, we conduct a systematic ablation over information-flow
topologies, revealing when and why upstream detection mistakes cascade into
downstream leakage. Experiments on the ConfAIde and PrivacyLens benchmark with
several open-source and closed-sourced LLMs demonstrate that our best
multi-agent configuration substantially reduces private information leakage
(\textbf{18\%} on ConfAIde and \textbf{19\%} on PrivacyLens with GPT-4o) while
preserving the fidelity of public content, outperforming single-agent
baselines. These results highlight the promise of principled information-flow
design in multi-agent systems for contextual privacy with LLMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.07664v1">Understanding Users' Privacy Perceptions Towards LLM's RAG-based Memory</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-08-11T06:26:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuning Zhang, Rongjun Ma, Ying Ma, Shixuan Li, Yiqun Xu, Xin Yi, Hewu Li</p>
    <p><b>Summary:</b> Large Language Models (LLMs) are increasingly integrating memory
functionalities to provide personalized and context-aware interactions.
However, user understanding, practices and expectations regarding these memory
systems are not yet well understood. This paper presents a thematic analysis of
semi-structured interviews with 18 users to explore their mental models of
LLM's Retrieval Augmented Generation (RAG)-based memory, current usage
practices, perceived benefits and drawbacks, privacy concerns and expectations
for future memory systems. Our findings reveal diverse and often incomplete
mental models of how memory operates. While users appreciate the potential for
enhanced personalization and efficiency, significant concerns exist regarding
privacy, control and the accuracy of remembered information. Users express a
desire for granular control over memory generation, management, usage and
updating, including clear mechanisms for reviewing, editing, deleting and
categorizing memories, as well as transparent insight into how memories and
inferred information are used. We discuss design implications for creating more
user-centric, transparent, and trustworthy LLM memory systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.07505v1">Enhancing Privacy in Decentralized Min-Max Optimization: A
  Differentially Private Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-08-10T23:24:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yueyang Quan, Chang Wang, Shengjie Zhai, Minghong Fang, Zhuqing Liu</p>
    <p><b>Summary:</b> Decentralized min-max optimization allows multi-agent systems to
collaboratively solve global min-max optimization problems by facilitating the
exchange of model updates among neighboring agents, eliminating the need for a
central server. However, sharing model updates in such systems carry a risk of
exposing sensitive data to inference attacks, raising significant privacy
concerns. To mitigate these privacy risks, differential privacy (DP) has become
a widely adopted technique for safeguarding individual data. Despite its
advantages, implementing DP in decentralized min-max optimization poses
challenges, as the added noise can hinder convergence, particularly in
non-convex scenarios with complex agent interactions in min-max optimization
problems. In this work, we propose an algorithm called DPMixSGD (Differential
Private Minmax Hybrid Stochastic Gradient Descent), a novel privacy-preserving
algorithm specifically designed for non-convex decentralized min-max
optimization. Our method builds on the state-of-the-art STORM-based algorithm,
one of the fastest decentralized min-max solutions. We rigorously prove that
the noise added to local gradients does not significantly compromise
convergence performance, and we provide theoretical bounds to ensure privacy
guarantees. To validate our theoretical findings, we conduct extensive
experiments across various tasks and models, demonstrating the effectiveness of
our approach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.07057v1">Rethinking Privacy Indicators in Extended Reality: Multimodal Design for
  Situationally Impaired Bystanders</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2025-08-09T17:48:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Syed Ibrahim Mustafa Shah Bukhari, Maha Sajid, Bo Ji, Brendan David-John</p>
    <p><b>Summary:</b> As Extended Reality (XR) devices become increasingly prevalent in everyday
settings, they raise significant privacy concerns for bystanders: individuals
in the vicinity of an XR device during its use, whom the device sensors may
accidentally capture. Current privacy indicators, such as small LEDs, often
presume that bystanders are attentive enough to interpret the privacy signals.
However, these cues can be easily overlooked when bystanders are distracted or
have limited vision. We define such individuals as situationally impaired
bystanders. This study explores XR privacy indicator designs that are effective
for situationally impaired bystanders. A focus group with eight participants
was conducted to design five novel privacy indicators. We evaluated these
designs through a user study with seven additional participants. Our results
show that visual-only indicators, typical in commercial XR devices, received
low ratings for perceived usefulness in impairment scenarios. In contrast,
multimodal indicators were preferred in privacy-sensitive scenarios with
situationally impaired bystanders. Ultimately, our results highlight the need
to move toward adaptable, multimodal, and situationally aware designs that
effectively support bystander privacy in everyday XR environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.07044v1">Balancing Privacy and Efficiency: Music Information Retrieval via
  Additive Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-09T17:00:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> William Zerong Wang, Dongfang Zhao</p>
    <p><b>Summary:</b> In the era of generative AI, ensuring the privacy of music data presents
unique challenges: unlike static artworks such as images, music data is
inherently temporal and multimodal, and it is sampled, transformed, and remixed
at an unprecedented scale. These characteristics make its core vector
embeddings, i.e, the numerical representations of the music, highly susceptible
to being learned, misused, or even stolen by models without accessing the
original audio files. Traditional methods like copyright licensing and digital
watermarking offer limited protection for these abstract mathematical
representations, thus necessitating a stronger, e.g., cryptographic, approach
to safeguarding the embeddings themselves. Standard encryption schemes, such as
AES, render data unintelligible for computation, making such searches
impossible. While Fully Homomorphic Encryption (FHE) provides a plausible
solution by allowing arbitrary computations on ciphertexts, its substantial
performance overhead remains impractical for large-scale vector similarity
searches. Given this trade-off, we propose a more practical approach using
Additive Homomorphic Encryption (AHE) for vector similarity search. The primary
contributions of this paper are threefold: we analyze threat models unique to
music information retrieval systems; we provide a theoretical analysis and
propose an efficient AHE-based solution through inner products of music
embeddings to deliver privacy-preserving similarity search; and finally, we
demonstrate the efficiency and practicality of the proposed approach through
empirical evaluation and comparison to FHE schemes on real-world MP3 files.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.06760v1">Understanding Privacy Norms Around LLM-Based Chatbots: A Contextual
  Integrity Perspective</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-08-09T00:22:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sarah Tran, Hongfan Lu, Isaac Slaughter, Bernease Herman, Aayushi Dangol, Yue Fu, Lufei Chen, Biniyam Gebreyohannes, Bill Howe, Alexis Hiniker, Nicholas Weber, Robert Wolfe</p>
    <p><b>Summary:</b> LLM-driven chatbots like ChatGPT have created large volumes of conversational
data, but little is known about how user privacy expectations are evolving with
this technology. We conduct a survey experiment with 300 US ChatGPT users to
understand emerging privacy norms for sharing chatbot data. Our findings reveal
a stark disconnect between user concerns and behavior: 82% of respondents rated
chatbot conversations as sensitive or highly sensitive - more than email or
social media posts - but nearly half reported discussing health topics and over
one-third discussed personal finances with ChatGPT. Participants expressed
strong privacy concerns (t(299) = 8.5, p < .01) and doubted their conversations
would remain private (t(299) = -6.9, p < .01). Despite this, respondents
uniformly rejected sharing personal data (search history, emails, device
access) for improved services, even in exchange for premium features worth
$200. To identify which factors influence appropriate chatbot data sharing, we
presented participants with factorial vignettes manipulating seven contextual
factors. Linear mixed models revealed that only the transmission factors such
as informed consent, data anonymization, or the removal of personally
identifiable information, significantly affected perceptions of appropriateness
and concern for data access. Surprisingly, contextual factors including the
recipient of the data (hospital vs. tech company), purpose (research vs.
advertising), type of content, and geographic location did not show significant
effects. Our results suggest that users apply consistent baseline privacy
expectations to chatbot data, prioritizing procedural safeguards over recipient
trustworthiness. This has important implications for emerging agentic AI
systems that assume user willingness to integrate personal data across
platforms.</p>
  </details>
</div>

