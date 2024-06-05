
<h2>2024-06</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.02520v1">Digital Privacy for Migrants: Exploring Current Research Trends and
  Future Prospects</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-06-04T17:41:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sarah Tabassum, Cori Faklaris</p>
    <p><b>Summary:</b> This paper explores digital privacy challenges for migrants, analyzing trends
from 2013 to 2023. Migrants face heightened risks such as government
surveillance and identity theft. Understanding these threats is vital for
raising awareness and guiding research towards effective solutions and policies
to protect migrant digital privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.02463v1">Click Without Compromise: Online Advertising Measurement via Per User
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-04T16:31:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yingtai Xiao, Jian Du, Shikun Zhang, Qiang Yan, Danfeng Zhang, Daniel Kifer</p>
    <p><b>Summary:</b> Online advertising is a cornerstone of the Internet ecosystem, with
advertising measurement playing a crucial role in optimizing efficiency. Ad
measurement entails attributing desired behaviors, such as purchases, to ad
exposures across various platforms, necessitating the collection of user
activities across these platforms. As this practice faces increasing
restrictions due to rising privacy concerns, safeguarding user privacy in this
context is imperative. Our work is the first to formulate the real-world
challenge of advertising measurement systems with real-time reporting of
streaming data in advertising campaigns. We introduce Ads-BPC, a novel
user-level differential privacy protection scheme for advertising measurement
results. This approach optimizes global noise power and results in a
non-identically distributed noise distribution that preserves differential
privacy while enhancing measurement accuracy. Through experiments on both
real-world advertising campaigns and synthetic datasets, Ads-BPC achieves a 25%
to 50% increase in accuracy over existing streaming DP mechanisms applied to
advertising measurement. This highlights our method's effectiveness in
achieving superior accuracy alongside a formal privacy guarantee, thereby
advancing the state-of-the-art in privacy-preserving advertising measurement.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.02424v1">Contextual Dynamic Pricing: Algorithms, Optimality, and Local
  Differential Privacy Constraints</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">  
  <p><b>Published on:</b> 2024-06-04T15:44:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zifeng Zhao, Feiyu Jiang, Yi Yu</p>
    <p><b>Summary:</b> We study the contextual dynamic pricing problem where a firm sells products
to $T$ sequentially arriving consumers that behave according to an unknown
demand model. The firm aims to maximize its revenue, i.e. minimize its regret
over a clairvoyant that knows the model in advance. The demand model is a
generalized linear model (GLM), allowing for a stochastic feature vector in
$\mathbb R^d$ that encodes product and consumer information. We first show that
the optimal regret upper bound is of order $\sqrt{dT}$, up to a logarithmic
factor, improving upon existing upper bounds in the literature by a $\sqrt{d}$
factor. This sharper rate is materialised by two algorithms: a confidence
bound-type (supCB) algorithm and an explore-then-commit (ETC) algorithm. A key
insight of our theoretical result is an intrinsic connection between dynamic
pricing and the contextual multi-armed bandit problem with many arms based on a
careful discretization. We further study contextual dynamic pricing under the
local differential privacy (LDP) constraints. In particular, we propose a
stochastic gradient descent based ETC algorithm that achieves an optimal regret
upper bound of order $d\sqrt{T}/\epsilon$, up to a logarithmic factor, where
$\epsilon>0$ is the privacy parameter. The regret upper bounds with and without
LDP constraints are accompanied by newly constructed minimax lower bounds,
which further characterize the cost of privacy. Extensive numerical experiments
and a real data application on online lending are conducted to illustrate the
efficiency and practical value of the proposed algorithms in dynamic pricing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.01811v1">A Game-Theoretic Approach to Privacy-Utility Tradeoff in Sharing Genomic
  Summary Statistics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-03T22:09:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tao Zhang, Rajagopal Venkatesaramani, Rajat K. De, Bradley A. Malin, Yevgeniy Vorobeychik</p>
    <p><b>Summary:</b> The advent of online genomic data-sharing services has sought to enhance the
accessibility of large genomic datasets by allowing queries about genetic
variants, such as summary statistics, aiding care providers in distinguishing
between spurious genomic variations and those with clinical significance.
However, numerous studies have demonstrated that even sharing summary genomic
information exposes individual members of such datasets to a significant
privacy risk due to membership inference attacks. While several approaches have
emerged that reduce privacy risks by adding noise or reducing the amount of
information shared, these typically assume non-adaptive attacks that use
likelihood ratio test (LRT) statistics. We propose a Bayesian game-theoretic
framework for optimal privacy-utility tradeoff in the sharing of genomic
summary statistics. Our first contribution is to prove that a very general
Bayesian attacker model that anchors our game-theoretic approach is more
powerful than the conventional LRT-based threat models in that it induces worse
privacy loss for the defender who is modeled as a von Neumann-Morgenstern (vNM)
decision-maker. We show this to be true even when the attacker uses a
non-informative subjective prior. Next, we present an analytically tractable
approach to compare the Bayesian attacks with arbitrary subjective priors and
the Neyman-Pearson optimal LRT attacks under the Gaussian mechanism common in
differential privacy frameworks. Finally, we propose an approach for
approximating Bayes-Nash equilibria of the game using deep neural network
generators to implicitly represent player mixed strategies. Our experiments
demonstrate that the proposed game-theoretic framework yields both stronger
attacks and stronger defense strategies than the state of the art.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.01394v1">PrivacyRestore: Privacy-Preserving Inference in Large Language Models
  via Privacy Removal and Restoration</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-06-03T14:57:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ziqian Zeng, Jianwei Wang, Zhengdong Lu, Huiping Zhuang, Cen Chen</p>
    <p><b>Summary:</b> The widespread usage of online Large Language Models (LLMs) inference
services has raised significant privacy concerns about the potential exposure
of private information in user inputs to eavesdroppers or untrustworthy service
providers. Existing privacy protection methods for LLMs suffer from
insufficient privacy protection, performance degradation, or severe inference
time overhead. In this paper, we propose PrivacyRestore to protect the privacy
of user inputs during LLM inference. PrivacyRestore directly removes privacy
spans in user inputs and restores privacy information via activation steering
during inference. The privacy spans are encoded as restoration vectors. We
propose Attention-aware Weighted Aggregation (AWA) which aggregates restoration
vectors of all privacy spans in the input into a meta restoration vector. AWA
not only ensures proper representation of all privacy spans but also prevents
attackers from inferring the privacy spans from the meta restoration vector
alone. This meta restoration vector, along with the query with privacy spans
removed, is then sent to the server. The experimental results show that
PrivacyRestore can protect private information while maintaining acceptable
levels of performance and inference efficiency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.01363v1">Privacy in LLM-based Recommendation: Recent Advances and Future
  Directions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2024-06-03T14:31:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sichun Luo, Wei Shao, Yuxuan Yao, Jian Xu, Mingyang Liu, Qintong Li, Bowei He, Maolin Wang, Guanzhi Deng, Hanxu Hou, Xinyi Zhang, Linqi Song</p>
    <p><b>Summary:</b> Nowadays, large language models (LLMs) have been integrated with conventional
recommendation models to improve recommendation performance. However, while
most of the existing works have focused on improving the model performance, the
privacy issue has only received comparatively less attention. In this paper, we
review recent advancements in privacy within LLM-based recommendation,
categorizing them into privacy attacks and protection mechanisms. Additionally,
we highlight several challenges and propose future directions for the community
to address these critical problems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.01085v1">FedAdOb: Privacy-Preserving Federated Deep Learning with Adaptive
  Obfuscation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-06-03T08:12:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hanlin Gu, Jiahuan Luo, Yan Kang, Yuan Yao, Gongxi Zhu, Bowen Li, Lixin Fan, Qiang Yang</p>
    <p><b>Summary:</b> Federated learning (FL) has emerged as a collaborative approach that allows
multiple clients to jointly learn a machine learning model without sharing
their private data. The concern about privacy leakage, albeit demonstrated
under specific conditions, has triggered numerous follow-up research in
designing powerful attacking methods and effective defending mechanisms aiming
to thwart these attacking methods. Nevertheless, privacy-preserving mechanisms
employed in these defending methods invariably lead to compromised model
performances due to a fixed obfuscation applied to private data or gradients.
In this article, we, therefore, propose a novel adaptive obfuscation mechanism,
coined FedAdOb, to protect private data without yielding original model
performances. Technically, FedAdOb utilizes passport-based adaptive obfuscation
to ensure data privacy in both horizontal and vertical federated learning
settings. The privacy-preserving capabilities of FedAdOb, specifically with
regard to private features and labels, are theoretically proven through
Theorems 1 and 2. Furthermore, extensive experimental evaluations conducted on
various datasets and network architectures demonstrate the effectiveness of
FedAdOb by manifesting its superior trade-off between privacy preservation and
model performance, surpassing existing methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.01080v1">No Vandalism: Privacy-Preserving and Byzantine-Robust Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-06-03T07:59:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhibo Xing, Zijian Zhang, Zi'ang Zhang, Jiamou Liu, Liehuang Zhu, Giovanni Russello</p>
    <p><b>Summary:</b> Federated learning allows several clients to train one machine learning model
jointly without sharing private data, providing privacy protection. However,
traditional federated learning is vulnerable to poisoning attacks, which can
not only decrease the model performance, but also implant malicious backdoors.
In addition, direct submission of local model parameters can also lead to the
privacy leakage of the training dataset. In this paper, we aim to build a
privacy-preserving and Byzantine-robust federated learning scheme to provide an
environment with no vandalism (NoV) against attacks from malicious
participants. Specifically, we construct a model filter for poisoned local
models, protecting the global model from data and model poisoning attacks. This
model filter combines zero-knowledge proofs to provide further privacy
protection. Then, we adopt secret sharing to provide verifiable secure
aggregation, removing malicious clients that disrupting the aggregation
process. Our formal analysis proves that NoV can protect data privacy and weed
out Byzantine attackers. Our experiments illustrate that NoV can effectively
address data and model poisoning attacks, including PGD, and outperforms other
related schemes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.00966v1">Guaranteeing Data Privacy in Federated Unlearning with Dynamic User
  Participation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-03T03:39:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ziyao Liu, Yu Jiang, Weifeng Jiang, Jiale Guo, Jun Zhao, Kwok-Yan Lam</p>
    <p><b>Summary:</b> Federated Unlearning (FU) is gaining prominence for its capacity to eliminate
influences of Federated Learning (FL) users' data from trained global FL
models. A straightforward FU method involves removing the unlearned users and
subsequently retraining a new global FL model from scratch with all remaining
users, a process that leads to considerable overhead. To enhance unlearning
efficiency, a widely adopted strategy employs clustering, dividing FL users
into clusters, with each cluster maintaining its own FL model. The final
inference is then determined by aggregating the majority vote from the
inferences of these sub-models. This method confines unlearning processes to
individual clusters for removing a user, thereby enhancing unlearning
efficiency by eliminating the need for participation from all remaining users.
However, current clustering-based FU schemes mainly concentrate on refining
clustering to boost unlearning efficiency but overlook the potential
information leakage from FL users' gradients, a privacy concern that has been
extensively studied. Typically, integrating secure aggregation (SecAgg) schemes
within each cluster can facilitate a privacy-preserving FU. Nevertheless,
crafting a clustering methodology that seamlessly incorporates SecAgg schemes
is challenging, particularly in scenarios involving adversarial users and
dynamic users. In this connection, we systematically explore the integration of
SecAgg protocols within the most widely used federated unlearning scheme, which
is based on clustering, to establish a privacy-preserving FU framework, aimed
at ensuring privacy while effectively managing dynamic user participation.
Comprehensive theoretical assessments and experimental results show that our
proposed scheme achieves comparable unlearning effectiveness, alongside
offering improved privacy protection and resilience in the face of varying user
participation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.00808v1">EchoNet-Synthetic: Privacy-preserving Video Generation for Safe Medical
  Data Sharing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-06-02T17:18:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hadrien Reynaud, Qingjie Meng, Mischa Dombrowski, Arijit Ghosh, Thomas Day, Alberto Gomez, Paul Leeson, Bernhard Kainz</p>
    <p><b>Summary:</b> To make medical datasets accessible without sharing sensitive patient
information, we introduce a novel end-to-end approach for generative
de-identification of dynamic medical imaging data. Until now, generative
methods have faced constraints in terms of fidelity, spatio-temporal coherence,
and the length of generation, failing to capture the complete details of
dataset distributions. We present a model designed to produce high-fidelity,
long and complete data samples with near-real-time efficiency and explore our
approach on a challenging task: generating echocardiogram videos. We develop
our generation method based on diffusion models and introduce a protocol for
medical video dataset anonymization. As an exemplar, we present
EchoNet-Synthetic, a fully synthetic, privacy-compliant echocardiogram dataset
with paired ejection fraction labels. As part of our de-identification
protocol, we evaluate the quality of the generated dataset and propose to use
clinical downstream tasks as a measurement on top of widely used but
potentially biased image quality metrics. Experimental outcomes demonstrate
that EchoNet-Synthetic achieves comparable dataset fidelity to the actual
dataset, effectively supporting the ejection fraction regression task. Code,
weights and dataset are available at
https://github.com/HReynaud/EchoNet-Synthetic.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.00359v1">Location Privacy in B5G/6G: Systematization of Knowledge</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2024-06-01T08:25:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hannah B. Pasandi, Faith Parastar</p>
    <p><b>Summary:</b> As we transition into the era of B5G/6G networks, the promise of seamless,
high-speed connectivity brings unprecedented opportunities and challenges.
Among the most critical concerns is the preservation of location privacy, given
the enhanced precision and pervasive connectivity of these advanced networks.
This paper systematically reviews the state of knowledge on location privacy in
B5G/6G networks, highlighting the architectural advancements and
infrastructural complexities that contribute to increased privacy risks. The
urgency of studying these technologies is underscored by the rapid adoption of
B5G/6G and the growing sophistication of location tracking methods. We evaluate
current and emerging privacy-preserving mechanisms, exploring the implications
of sophisticated tracking methods and the challenges posed by the complex
network infrastructures. Our findings reveal the effectiveness of various
mitigation strategies and emphasize the important role of physical layer
security. Additionally, we propose innovative approaches, including
decentralized authentication systems and the potential of satellite
communications, to enhance location privacy. By addressing these challenges,
this paper provides a comprehensive perspective on preserving user privacy in
the rapidly evolving landscape of modern communication networks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.00256v1">Over-the-Air Collaborative Inference with Feature Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-06-01T01:39:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohamed Seif, Yuqi Nie, Andrea Goldsmith, Vincent Poor</p>
    <p><b>Summary:</b> Collaborative inference in next-generation networks can enhance Artificial
Intelligence (AI) applications, including autonomous driving, personal
identification, and activity classification. This method involves a three-stage
process: a) data acquisition through sensing, b) feature extraction, and c)
feature encoding for transmission. Transmission of the extracted features
entails the potential risk of exposing sensitive personal data. To address this
issue, in this work a new privacy-protecting collaborative inference mechanism
is developed. Under this mechanism, each edge device in the network protects
the privacy of extracted features before transmitting them to a central server
for inference. This mechanism aims to achieve two main objectives while
ensuring effective inference performance: 1) reducing communication overhead,
and 2) maintaining strict privacy guarantees during features transmission.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.00249v1">Privacy Challenges in Meta-Learning: An Investigation on Model-Agnostic
  Meta-Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-01T01:10:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mina Rafiei, Mohammadmahdi Maheri, Hamid R. Rabiee</p>
    <p><b>Summary:</b> Meta-learning involves multiple learners, each dedicated to specific tasks,
collaborating in a data-constrained setting. In current meta-learning methods,
task learners locally learn models from sensitive data, termed support sets.
These task learners subsequently share model-related information, such as
gradients or loss values, which is computed using another part of the data
termed query set, with a meta-learner. The meta-learner employs this
information to update its meta-knowledge. Despite the absence of explicit data
sharing, privacy concerns persist. This paper examines potential data leakage
in a prominent metalearning algorithm, specifically Model-Agnostic
Meta-Learning (MAML). In MAML, gradients are shared between the metalearner and
task-learners. The primary objective is to scrutinize the gradient and the
information it encompasses about the task dataset. Subsequently, we endeavor to
propose membership inference attacks targeting the task dataset containing
support and query sets. Finally, we explore various noise injection methods
designed to safeguard the privacy of task data and thwart potential attacks.
Experimental results demonstrate the effectiveness of these attacks on MAML and
the efficacy of proper noise injection methods in countering them.</p>
  </details>
</div>



<h2>2024-05</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.20914v1">RASE: Efficient Privacy-preserving Data Aggregation against Disclosure
  Attacks for IoTs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-31T15:21:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zuyan Wang, Jun Tao, Dika Zou</p>
    <p><b>Summary:</b> The growing popular awareness of personal privacy raises the following
quandary: what is the new paradigm for collecting and protecting the data
produced by ever-increasing sensor devices. Most previous studies on co-design
of data aggregation and privacy preservation assume that a trusted fusion
center adheres to privacy regimes. Very recent work has taken steps towards
relaxing the assumption by allowing data contributors to locally perturb their
own data. Although these solutions withhold some data content to mitigate
privacy risks, they have been shown to offer insufficient protection against
disclosure attacks. Aiming at providing a more rigorous data safeguard for the
Internet of Things (IoTs), this paper initiates the study of privacy-preserving
data aggregation. We propose a novel paradigm (called RASE), which can be
generalized into a 3-step sequential procedure, noise addition, followed by
random permutation, and then parameter estimation. Specially, we design a
differentially private randomizer, which carefully guides data contributors to
obfuscate the truth. Then, a shuffler is employed to receive the noisy data
from all data contributors. After that, it breaks the correct linkage between
senders and receivers by applying a random permutation. The estimation phase
involves using inaccurate data to calculate an approximate aggregate value.
Extensive simulations are provided to explore the privacy-utility landscape of
our RASE.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.20900v1">Large Language Models: A New Approach for Privacy Policy Analysis at
  Scale</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-05-31T15:12:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> David Rodriguez, Ian Yang, Jose M. Del Alamo, Norman Sadeh</p>
    <p><b>Summary:</b> The number and dynamic nature of web and mobile applications presents
significant challenges for assessing their compliance with data protection
laws. In this context, symbolic and statistical Natural Language Processing
(NLP) techniques have been employed for the automated analysis of these
systems' privacy policies. However, these techniques typically require
labor-intensive and potentially error-prone manually annotated datasets for
training and validation. This research proposes the application of Large
Language Models (LLMs) as an alternative for effectively and efficiently
extracting privacy practices from privacy policies at scale. Particularly, we
leverage well-known LLMs such as ChatGPT and Llama 2, and offer guidance on the
optimal design of prompts, parameters, and models, incorporating advanced
strategies such as few-shot learning. We further illustrate its capability to
detect detailed and varied privacy practices accurately. Using several renowned
datasets in the domain as a benchmark, our evaluation validates its exceptional
performance, achieving an F1 score exceeding 93%. Besides, it does so with
reduced costs, faster processing times, and fewer technical knowledge
requirements. Consequently, we advocate for LLM-based solutions as a sound
alternative to traditional NLP techniques for the automated analysis of privacy
policies at scale.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.20761v1">Share Your Secrets for Privacy! Confidential Forecasting with Vertical
  Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-05-31T12:27:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aditya Shankar, Lydia Y. Chen, Jérémie Decouchant, Dimitra Gkorou, Rihan Hai</p>
    <p><b>Summary:</b> Vertical federated learning (VFL) is a promising area for time series
forecasting in industrial applications, such as predictive maintenance and
machine control. Critical challenges to address in manufacturing include data
privacy and over-fitting on small and noisy datasets during both training and
inference. Additionally, to increase industry adaptability, such forecasting
models must scale well with the number of parties while ensuring strong
convergence and low-tuning complexity. We address those challenges and propose
'Secret-shared Time Series Forecasting with VFL' (STV), a novel framework that
exhibits the following key features: i) a privacy-preserving algorithm for
forecasting with SARIMAX and autoregressive trees on vertically partitioned
data; ii) serverless forecasting using secret sharing and multi-party
computation; iii) novel N-party algorithms for matrix multiplication and
inverse operations for direct parameter optimization, giving strong convergence
with minimal hyperparameter tuning complexity. We conduct evaluations on six
representative datasets from public and industry-specific contexts. Our results
demonstrate that STV's forecasting accuracy is comparable to those of
centralized approaches. They also show that our direct optimization can
outperform centralized methods, which include state-of-the-art diffusion models
and long-short-term memory, by 23.81% on forecasting accuracy. We also conduct
a scalability analysis by examining the communication costs of direct and
iterative optimization to navigate the choice between the two. Code and
appendix are available: https://github.com/adis98/STV</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.20681v1">No Free Lunch Theorem for Privacy-Preserving LLM Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-05-31T08:22:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaojin Zhang, Yulin Fei, Yan Kang, Wei Chen, Lixin Fan, Hai Jin, Qiang Yang</p>
    <p><b>Summary:</b> Individuals and businesses have been significantly benefited by Large
Language Models (LLMs) including PaLM, Gemini and ChatGPT in various ways. For
example, LLMs enhance productivity, reduce costs, and enable us to focus on
more valuable tasks. Furthermore, LLMs possess the capacity to sift through
extensive datasets, uncover underlying patterns, and furnish critical insights
that propel the frontiers of technology and science. However, LLMs also pose
privacy concerns. Users' interactions with LLMs may expose their sensitive
personal or company information. A lack of robust privacy safeguards and legal
frameworks could permit the unwarranted intrusion or improper handling of
individual data, thereby risking infringements of privacy and the theft of
personal identities. To ensure privacy, it is essential to minimize the
dependency between shared prompts and private information. Various
randomization approaches have been proposed to protect prompts' privacy, but
they may incur utility loss compared to unprotected LLMs prompting. Therefore,
it is essential to evaluate the balance between the risk of privacy leakage and
loss of utility when conducting effective protection mechanisms. The current
study develops a framework for inferring privacy-protected Large Language
Models (LLMs) and lays down a solid theoretical basis for examining the
interplay between privacy preservation and utility. The core insight is
encapsulated within a theorem that is called as the NFL (abbreviation of the
word No-Free-Lunch) Theorem.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.20576v1">Federated Graph Analytics with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-31T02:09:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shang Liu, Yang Cao, Takao Murakami, Weiran Liu, Seng Pei Liew, Tsubasa Takahashi, Jinfei Liu, Masatoshi Yoshikawa</p>
    <p><b>Summary:</b> Collaborative graph analysis across multiple institutions is becoming
increasingly popular. Realistic examples include social network analysis across
various social platforms, financial transaction analysis across multiple banks,
and analyzing the transmission of infectious diseases across multiple
hospitals. We define the federated graph analytics, a new problem for
collaborative graph analytics under differential privacy. Although
differentially private graph analysis has been widely studied, it fails to
achieve a good tradeoff between utility and privacy in federated scenarios, due
to the limited view of local clients and overlapping information across
multiple subgraphs. Motivated by this, we first propose a federated graph
analytic framework, named FEAT, which enables arbitrary downstream common graph
statistics while preserving individual privacy. Furthermore, we introduce an
optimized framework based on our proposed degree-based partition algorithm,
called FEAT+, which improves the overall utility by leveraging the true local
subgraphs. Finally, extensive experiments demonstrate that our FEAT and FEAT+
significantly outperform the baseline approach by approximately one and four
orders of magnitude, respectively.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.00073v1">A Novel Review of Stability Techniques for Improved Privacy-Preserving
  Machine Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-31T00:30:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Coleman DuPlessie, Aidan Gao</p>
    <p><b>Summary:</b> Machine learning models have recently enjoyed a significant increase in size
and popularity. However, this growth has created concerns about dataset
privacy. To counteract data leakage, various privacy frameworks guarantee that
the output of machine learning models does not compromise their training data.
However, this privatization comes at a cost by adding random noise to the
training process, which reduces model performance. By making models more
resistant to small changes in input and thus more stable, the necessary amount
of noise can be decreased while still protecting privacy. This paper
investigates various techniques to enhance stability, thereby minimizing the
negative effects of privatization in machine learning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.20483v1">Hiding Your Awful Online Choices Made More Efficient and Secure: A New
  Privacy-Aware Recommender System</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-30T21:08:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shibam Mukherjee, Roman Walch, Fredrik Meisingseth, Elisabeth Lex, Christian Rechberger</p>
    <p><b>Summary:</b> Recommender systems are an integral part of online platforms that recommend
new content to users with similar interests. However, they demand a
considerable amount of user activity data where, if the data is not adequately
protected, constitute a critical threat to the user privacy. Privacy-aware
recommender systems enable protection of such sensitive user data while still
maintaining a similar recommendation accuracy compared to the traditional
non-private recommender systems. However, at present, the current privacy-aware
recommender systems suffer from a significant trade-off between privacy and
computational efficiency. For instance, it is well known that architectures
that rely purely on cryptographic primitives offer the most robust privacy
guarantees, however, they suffer from substantial computational and network
overhead. Thus, it is crucial to improve this trade-off for better performance.
This paper presents a novel privacy-aware recommender system that combines
privacy-aware machine learning algorithms for practical scalability and
efficiency with cryptographic primitives like Homomorphic Encryption and
Multi-Party Computation - without assumptions like trusted-party or secure
hardware - for solid privacy guarantees. Experiments on standard benchmark
datasets show that our approach results in time and memory gains by three
orders of magnitude compared to using cryptographic primitives in a standalone
for constructing a privacy-aware recommender system. Furthermore, for the first
time our method makes it feasible to compute private recommendations for
datasets containing 100 million entries, even on memory-constrained low-power
SOC (System on Chip) devices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.20405v1">Private Mean Estimation with Person-Level Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">  
  <p><b>Published on:</b> 2024-05-30T18:20:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sushant Agarwal, Gautam Kamath, Mahbod Majid, Argyris Mouzakis, Rose Silver, Jonathan Ullman</p>
    <p><b>Summary:</b> We study differentially private (DP) mean estimation in the case where each
person holds multiple samples. Commonly referred to as the "user-level"
setting, DP here requires the usual notion of distributional stability when all
of a person's datapoints can be modified. Informally, if $n$ people each have
$m$ samples from an unknown $d$-dimensional distribution with bounded $k$-th
moments, we show that
  \[n = \tilde \Theta\left(\frac{d}{\alpha^2 m} + \frac{d }{ \alpha m^{1/2}
\varepsilon} + \frac{d}{\alpha^{k/(k-1)} m \varepsilon} +
\frac{d}{\varepsilon}\right)\]
  people are necessary and sufficient to estimate the mean up to distance
$\alpha$ in $\ell_2$-norm under $\varepsilon$-differential privacy (and its
common relaxations). In the multivariate setting, we give computationally
efficient algorithms under approximate DP (with slightly degraded sample
complexity) and computationally inefficient algorithms under pure DP, and our
nearly matching lower bounds hold for the most permissive case of approximate
DP. Our computationally efficient estimators are based on the well known
noisy-clipped-mean approach, but the analysis for our setting requires new
bounds on the tails of sums of independent, vector-valued, bounded-moments
random variables, and a new argument for bounding the bias introduced by
clipping.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.19831v2">Just Rewrite It Again: A Post-Processing Method for Enhanced Semantic
  Similarity and Privacy Preservation of Differentially Private Rewritten Text</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-05-30T08:41:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stephen Meisenbacher, Florian Matthes</p>
    <p><b>Summary:</b> The study of Differential Privacy (DP) in Natural Language Processing often
views the task of text privatization as a $\textit{rewriting}$ task, in which
sensitive input texts are rewritten to hide explicit or implicit private
information. In order to evaluate the privacy-preserving capabilities of a DP
text rewriting mechanism, $\textit{empirical privacy}$ tests are frequently
employed. In these tests, an adversary is modeled, who aims to infer sensitive
information (e.g., gender) about the author behind a (privatized) text. Looking
to improve the empirical protections provided by DP rewriting methods, we
propose a simple post-processing method based on the goal of aligning rewritten
texts with their original counterparts, where DP rewritten texts are rewritten
$\textit{again}$. Our results show that such an approach not only produces
outputs that are more semantically reminiscent of the original inputs, but also
texts which score on average better in empirical privacy evaluations.
Therefore, our approach raises the bar for DP rewriting methods in their
empirical privacy evaluations, providing an extra layer of protection against
malicious adversaries.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.20785v1">How the Future Works at SOUPS: Analyzing Future Work Statements and
  Their Impact on Usable Security and Privacy Research</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-05-30T07:07:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jacques Suray, Jan H. Klemmer, Juliane Schmüser, Sascha Fahl</p>
    <p><b>Summary:</b> Extending knowledge by identifying and investigating valuable research
questions and problems is a core function of research. Research publications
often suggest avenues for future work to extend and build upon their results.
Considering these suggestions can contribute to developing research ideas that
build upon previous work and produce results that tie into existing knowledge.
Usable security and privacy researchers commonly add future work statements to
their publications. However, our community lacks an in-depth understanding of
their prevalence, quality, and impact on future research.
  Our work aims to address this gap in the research literature. We reviewed all
27 papers from the 2019 SOUPS proceedings and analyzed their future work
statements. Additionally, we analyzed 978 publications that cite any paper from
SOUPS 2019 proceedings to assess their future work statements' impact. We find
that most papers from the SOUPS 2019 proceedings include future work
statements. However, they are often unspecific or ambiguous, and not always
easy to find. Therefore, the citing publications often matched the future work
statements' content thematically, but rarely explicitly acknowledged them,
indicating a limited impact. We conclude with recommendations for the usable
security and privacy community to improve the utility of future work statements
by making them more tangible and actionable, and avenues for future work.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.19272v1">Mitigating Disparate Impact of Differential Privacy in Federated
  Learning through Robust Clustering</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-05-29T17:03:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Saber Malekmohammadi, Afaf Taik, Golnoosh Farnadi</p>
    <p><b>Summary:</b> Federated Learning (FL) is a decentralized machine learning (ML) approach
that keeps data localized and often incorporates Differential Privacy (DP) to
enhance privacy guarantees. Similar to previous work on DP in ML, we observed
that differentially private federated learning (DPFL) introduces performance
disparities, particularly affecting minority groups. Recent work has attempted
to address performance fairness in vanilla FL through clustering, but this
method remains sensitive and prone to errors, which are further exacerbated by
the DP noise in DPFL. To fill this gap, in this paper, we propose a novel
clustered DPFL algorithm designed to effectively identify clients' clusters in
highly heterogeneous settings while maintaining high accuracy with DP
guarantees. To this end, we propose to cluster clients based on both their
model updates and training loss values. Our proposed approach also addresses
the server's uncertainties in clustering clients' model updates by employing
larger batch sizes along with Gaussian Mixture Model (GMM) to alleviate the
impact of noise and potential clustering errors, especially in
privacy-sensitive scenarios. We provide theoretical analysis of the
effectiveness of our proposed approach. We also extensively evaluate our
approach across diverse data distributions and privacy budgets and show its
effectiveness in mitigating the disparate impact of DP in FL settings with a
small computational cost.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.19259v1">A Privacy-Preserving Graph Encryption Scheme Based on Oblivious RAM</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-29T16:47:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Seyni Kane, Anis Bkakria</p>
    <p><b>Summary:</b> Graph encryption schemes play a crucial role in facilitating secure queries
on encrypted graphs hosted on untrusted servers. With applications spanning
navigation systems, network topology, and social networks, the need to
safeguard sensitive data becomes paramount. Existing graph encryption methods,
however, exhibit vulnerabilities by inadvertently revealing aspects of the
graph structure and query patterns, posing threats to security and privacy. In
response, we propose a novel graph encryption scheme designed to mitigate
access pattern and query pattern leakage through the integration of oblivious
RAM and trusted execution environment techniques, exemplified by a Trusted
Execution Environment (TEE). Our solution establishes two key security
objectives: (1) ensuring that adversaries, when presented with an encrypted
graph, remain oblivious to any information regarding the underlying graph, and
(2) achieving query indistinguishability by concealing access patterns.
Additionally, we conducted experimentation to evaluate the efficiency of the
proposed schemes when dealing with real-world location navigation services.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.19187v1">Algorithmic Transparency and Participation through the Handoff Lens:
  Lessons Learned from the U.S. Census Bureau's Adoption of Differential
  Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-05-29T15:29:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Amina A. Abdu, Lauren M. Chambers, Deirdre K. Mulligan, Abigail Z. Jacobs</p>
    <p><b>Summary:</b> Emerging discussions on the responsible government use of algorithmic
technologies propose transparency and public participation as key mechanisms
for preserving accountability and trust. But in practice, the adoption and use
of any technology shifts the social, organizational, and political context in
which it is embedded. Therefore translating transparency and participation
efforts into meaningful, effective accountability must take into account these
shifts. We adopt two theoretical frames, Mulligan and Nissenbaum's handoff
model and Star and Griesemer's boundary objects, to reveal such shifts during
the U.S. Census Bureau's adoption of differential privacy (DP) in its updated
disclosure avoidance system (DAS) for the 2020 census. This update preserved
(and arguably strengthened) the confidentiality protections that the Bureau is
mandated to uphold, and the Bureau engaged in a range of activities to
facilitate public understanding of and participation in the system design
process. Using publicly available documents concerning the Census'
implementation of DP, this case study seeks to expand our understanding of how
technical shifts implicate values, how such shifts can afford (or fail to
afford) greater transparency and participation in system design, and the
importance of localized expertise throughout. We present three lessons from
this case study toward grounding understandings of algorithmic transparency and
participation: (1) efforts towards transparency and participation in
algorithmic governance must center values and policy decisions, not just
technical design decisions; (2) the handoff model is a useful tool for
revealing how such values may be cloaked beneath technical decisions; and (3)
boundary objects alone cannot bridge distant communities without trusted
experts traveling alongside to broker their adoption.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.18888v1">Proactive Load-Shaping Strategies with Privacy-Cost Trade-offs in
  Residential Households based on Deep Reinforcement Learning</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2024-05-29T08:45:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruichang Zhang, Youcheng Sun, Mustafa A. Mustafa</p>
    <p><b>Summary:</b> Smart meters play a crucial role in enhancing energy management and
efficiency, but they raise significant privacy concerns by potentially
revealing detailed user behaviors through energy consumption patterns. Recent
scholarly efforts have focused on developing battery-aided load-shaping
techniques to protect user privacy while balancing costs. This paper proposes a
novel deep reinforcement learning-based load-shaping algorithm (PLS-DQN)
designed to protect user privacy by proactively creating artificial load
signatures that mislead potential attackers. We evaluate our proposed algorithm
against a non-intrusive load monitoring (NILM) adversary. The results
demonstrate that our approach not only effectively conceals real energy usage
patterns but also outperforms state-of-the-art methods in enhancing user
privacy while maintaining cost efficiency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.18878v1">Privacy Preserving Data Imputation via Multi-party Computation for
  Medical Applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-05-29T08:36:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Julia Jentsch, Ali Burak Ünal, Şeyma Selcan Mağara, Mete Akgün</p>
    <p><b>Summary:</b> Handling missing data is crucial in machine learning, but many datasets
contain gaps due to errors or non-response. Unlike traditional methods such as
listwise deletion, which are simple but inadequate, the literature offers more
sophisticated and effective methods, thereby improving sample size and
accuracy. However, these methods require accessing the whole dataset, which
contradicts the privacy regulations when the data is distributed among multiple
sources. Especially in the medical and healthcare domain, such access reveals
sensitive information about patients. This study addresses privacy-preserving
imputation methods for sensitive data using secure multi-party computation,
enabling secure computations without revealing any party's sensitive
information. In this study, we realized the mean, median, regression, and kNN
imputation methods in a privacy-preserving way. We specifically target the
medical and healthcare domains considering the significance of protection of
the patient data, showcasing our methods on a diabetes dataset. Experiments on
the diabetes dataset validated the correctness of our privacy-preserving
imputation methods, yielding the largest error around $3 \times 10^{-3}$,
closely matching plaintext methods. We also analyzed the scalability of our
methods to varying numbers of samples, showing their applicability to
real-world healthcare problems. Our analysis demonstrated that all our methods
scale linearly with the number of samples. Except for kNN, the runtime of all
our methods indicates that they can be utilized for large datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.18802v1">Enhancing Security and Privacy in Federated Learning using Update
  Digests and Voting-Based Defense</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-05-29T06:46:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenjie Li, Kai Fan, Jingyuan Zhang, Hui Li, Wei Yang Bryan Lim, Qiang Yang</p>
    <p><b>Summary:</b> Federated Learning (FL) is a promising privacy-preserving machine learning
paradigm that allows data owners to collaboratively train models while keeping
their data localized. Despite its potential, FL faces challenges related to the
trustworthiness of both clients and servers, especially in the presence of
curious or malicious adversaries. In this paper, we introduce a novel framework
named \underline{\textbf{F}}ederated \underline{\textbf{L}}earning with
\underline{\textbf{U}}pdate \underline{\textbf{D}}igest (FLUD), which addresses
the critical issues of privacy preservation and resistance to Byzantine attacks
within distributed learning environments. FLUD utilizes an innovative approach,
the $\mathsf{LinfSample}$ method, allowing clients to compute the $l_{\infty}$
norm across sliding windows of updates as an update digest. This digest enables
the server to calculate a shared distance matrix, significantly reducing the
overhead associated with Secure Multi-Party Computation (SMPC) by three orders
of magnitude while effectively distinguishing between benign and malicious
updates. Additionally, FLUD integrates a privacy-preserving, voting-based
defense mechanism that employs optimized SMPC protocols to minimize
communication rounds. Our comprehensive experiments demonstrate FLUD's
effectiveness in countering Byzantine adversaries while incurring low
communication and runtime overhead. FLUD offers a scalable framework for secure
and reliable FL in distributed environments, facilitating its application in
scenarios requiring robust data management and security.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.18534v1">Individualized Privacy Accounting via Subsampling with Applications in
  Combinatorial Optimization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-28T19:02:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Badih Ghazi, Pritish Kamath, Ravi Kumar, Pasin Manurangsi, Adam Sealfon</p>
    <p><b>Summary:</b> In this work, we give a new technique for analyzing individualized privacy
accounting via the following simple observation: if an algorithm is one-sided
add-DP, then its subsampled variant satisfies two-sided DP. From this, we
obtain several improved algorithms for private combinatorial optimization
problems, including decomposable submodular maximization and set cover. Our
error guarantees are asymptotically tight and our algorithm satisfies pure-DP
while previously known algorithms (Gupta et al., 2010; Chaturvedi et al., 2021)
are approximate-DP. We also show an application of our technique beyond
combinatorial optimization by giving a pure-DP algorithm for the shifting heavy
hitter problem in a stream; previously, only an approximateDP algorithm was
known (Kaplan et al., 2021; Cohen & Lyu, 2023).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.18430v1">Feasibility of Privacy-Preserving Entity Resolution on Confidential
  Healthcare Datasets Using Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computational Engineering, Finance, and Science-5BC0EB">
  <p><b>Published on:</b> 2024-05-28T17:59:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yixiang Yao, Joseph Cecil, Praveen Angyan, Neil Bahroos, Srivatsan Ravi</p>
    <p><b>Summary:</b> Patient datasets contain confidential information which is protected by laws
and regulations such as HIPAA and GDPR. Ensuring comprehensive patient
information necessitates privacy-preserving entity resolution (PPER), which
identifies identical patient entities across multiple databases from different
healthcare organizations while maintaining data privacy. Existing methods often
lack cryptographic security or are computationally impractical for real-world
datasets. We introduce a PPER pipeline based on AMPPERE, a secure abstract
computation model utilizing cryptographic tools like homomorphic encryption.
Our tailored approach incorporates extensive parallelization techniques and
optimal parameters specifically for patient datasets. Experimental results
demonstrate the proposed method's effectiveness in terms of accuracy and
efficiency compared to various baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.17971v1">A Qualitative Analysis Framework for mHealth Privacy Practices</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-05-28T08:57:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Thomas Cory, Wolf Rieder, Thu-My Huynh</p>
    <p><b>Summary:</b> Mobile Health (mHealth) applications have become a crucial part of health
monitoring and management. However, the proliferation of these applications has
also raised concerns over the privacy and security of Personally Identifiable
Information and Protected Health Information. Addressing these concerns, this
paper introduces a novel framework for the qualitative evaluation of privacy
practices in mHealth apps, particularly focusing on the handling and
transmission of sensitive user data. Our investigation encompasses an analysis
of 152 leading mHealth apps on the Android platform, leveraging the proposed
framework to provide a multifaceted view of their data processing activities.
Despite stringent regulations like the General Data Protection Regulation in
the European Union and the Health Insurance Portability and Accountability Act
in the United States, our findings indicate persistent issues with negligence
and misuse of sensitive user information. We uncover significant instances of
health information leakage to third-party trackers and a widespread neglect of
privacy-by-design and transparency principles. Our research underscores the
critical need for stricter enforcement of data protection laws and sets a
foundation for future efforts aimed at enhancing user privacy within the
mHealth ecosystem.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.20769v1">Avoiding Pitfalls for Privacy Accounting of Subsampled Mechanisms under
  Composition</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2024-05-27T20:30:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Christian Janos Lebeda, Matthew Regehr, Gautam Kamath, Thomas Steinke</p>
    <p><b>Summary:</b> We consider the problem of computing tight privacy guarantees for the
composition of subsampled differentially private mechanisms. Recent algorithms
can numerically compute the privacy parameters to arbitrary precision but must
be carefully applied.
  Our main contribution is to address two common points of confusion. First,
some privacy accountants assume that the privacy guarantees for the composition
of a subsampled mechanism are determined by self-composing the worst-case
datasets for the uncomposed mechanism. We show that this is not true in
general. Second, Poisson subsampling is sometimes assumed to have similar
privacy guarantees compared to sampling without replacement. We show that the
privacy guarantees may in fact differ significantly between the two sampling
schemes. In particular, we give an example of hyperparameters that result in
$\varepsilon \approx 1$ for Poisson subsampling and $\varepsilon > 10$ for
sampling without replacement. This occurs for some parameters that could
realistically be chosen for DP-SGD.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.17423v1">Privacy-Aware Visual Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-05-27T17:59:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Laurens Samson, Nimrod Barazani, Sennay Ghebreab, Yuki M. Asano</p>
    <p><b>Summary:</b> This paper aims to advance our understanding of how Visual Language Models
(VLMs) handle privacy-sensitive information, a crucial concern as these
technologies become integral to everyday life. To this end, we introduce a new
benchmark PrivBench, which contains images from 8 sensitive categories such as
passports, or fingerprints. We evaluate 10 state-of-the-art VLMs on this
benchmark and observe a generally limited understanding of privacy,
highlighting a significant area for model improvement. Based on this we
introduce PrivTune, a new instruction-tuning dataset aimed at equipping VLMs
with knowledge about visual privacy. By tuning two pretrained VLMs, TinyLLaVa
and MiniGPT-v2, on this small dataset, we achieve strong gains in their ability
to recognize sensitive content, outperforming even GPT4-V. At the same time, we
show that privacy-tuning only minimally affects the VLMs performance on
standard benchmarks such as VQA. Overall, this paper lays out a crucial
challenge for making VLMs effective in handling real-world data safely and
provides a simple recipe that takes the first step towards building
privacy-aware VLMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.17079v1">Learning with User-Level Local Differential Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-05-27T11:52:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Puning Zhao, Li Shen, Rongfei Fan, Qingming Li, Huiwen Wu, Jiafei Wu, Zhe Liu</p>
    <p><b>Summary:</b> User-level privacy is important in distributed systems. Previous research
primarily focuses on the central model, while the local models have received
much less attention. Under the central model, user-level DP is strictly
stronger than the item-level one. However, under the local model, the
relationship between user-level and item-level LDP becomes more complex, thus
the analysis is crucially different. In this paper, we first analyze the mean
estimation problem and then apply it to stochastic optimization,
classification, and regression. In particular, we propose adaptive strategies
to achieve optimal performance at all privacy levels. Moreover, we also obtain
information-theoretic lower bounds, which show that the proposed methods are
minimax optimal up to logarithmic factors. Unlike the central DP model, where
user-level DP always leads to slower convergence, our result shows that under
the local model, the convergence rates are nearly the same between user-level
and item-level cases for distributions with bounded support. For heavy-tailed
distributions, the user-level rate is even faster than the item-level one.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.16905v2">Privacy and Security Trade-off in Interconnected Systems with Known or
  Unknown Privacy Noise Covariance</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2024-05-27T07:53:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haojun Wang, Kun Liu, Baojia Li, Emilia Fridman, Yuanqing Xia</p>
    <p><b>Summary:</b> This paper is concerned with the security problem for interconnected systems,
where each subsystem is required to detect local attacks using locally
available information and the information received from its neighboring
subsystems. Moreover, we consider that there exists an additional eavesdropper
being able to infer the private information by eavesdropping transmitted data
between subsystems. Then, a privacy-preserving method is employed by adding
privacy noise to transmitted data, and the privacy level is measured by mutual
information. Nevertheless, adding privacy noise to transmitted data may affect
the detection performance metrics such as detection probability and false alarm
probability. Thus, we theoretically analyze the trade-off between the privacy
and the detection performance. An optimization problem with maximizing both the
degree of privacy preservation and the detection probability is established to
obtain the covariance of the privacy noise. In addition, the attack detector of
each subsystem may not obtain all information about the privacy noise. We
further theoretically analyze the trade-off between the privacy and the false
alarm probability when the attack detector has no knowledge of the privacy
noise covariance. An optimization problem with maximizing the degree of privacy
preservation with guaranteeing a bound of false alarm distortion level is
established to obtain {\color{black}{the covariance of the privacy noise}}.
Moreover, to analyze the effect of the privacy noise on the detection
probability, we consider that each subsystem can estimate the unknown privacy
noise covariance by the secondary data. Based on the estimated covariance, we
construct another attack detector and analyze how the privacy noise affects its
detection performance. Finally, a numerical example is provided to verify the
effectiveness of theoretical results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.16895v1">Anonymization Prompt Learning for Facial Privacy-Preserving
  Text-to-Image Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-05-27T07:38:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Liang Shi, Jie Zhang, Shiguang Shan</p>
    <p><b>Summary:</b> Text-to-image diffusion models, such as Stable Diffusion, generate highly
realistic images from text descriptions. However, the generation of certain
content at such high quality raises concerns. A prominent issue is the accurate
depiction of identifiable facial images, which could lead to malicious deepfake
generation and privacy violations. In this paper, we propose Anonymization
Prompt Learning (APL) to address this problem. Specifically, we train a
learnable prompt prefix for text-to-image diffusion models, which forces the
model to generate anonymized facial identities, even when prompted to produce
images of specific individuals. Extensive quantitative and qualitative
experiments demonstrate the successful anonymization performance of APL, which
anonymizes any specific individuals without compromising the quality of
non-identity-specific image generation. Furthermore, we reveal the
plug-and-play property of the learned prompt prefix, enabling its effective
application across different pretrained text-to-image models for transferrable
privacy and security protection against the risks of deepfakes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.16058v2">A Novel Privacy Enhancement Scheme with Dynamic Quantization for
  Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E">
  <p><b>Published on:</b> 2024-05-25T04:56:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yifan Wang, Xianghui Cao, Shi Jin, Mo-Yuen Chow</p>
    <p><b>Summary:</b> Federated learning (FL) has been widely regarded as a promising paradigm for
privacy preservation of raw data in machine learning. Although, the data
privacy in FL is locally protected to some extent, it is still a desideratum to
enhance privacy and alleviate communication overhead caused by repetitively
transmitting model parameters. Typically, these challenges are addressed
separately, or jointly via a unified scheme that consists of noise-injected
privacy mechanism and communication compression, which may lead to model
corruption due to the introduced composite noise. In this work, we propose a
novel model-splitting privacy-preserving FL (MSP-FL) scheme to achieve private
FL with precise accuracy guarantee. Based upon MSP-FL, we further propose a
model-splitting privacy-preserving FL with dynamic quantization (MSPDQ-FL) to
mitigate the communication overhead, which incorporates a shrinking
quantization interval to reduce the quantization error. We provide privacy and
convergence analysis for both MSP-FL and MSPDQ-FL under non-i.i.d. dataset,
partial clients participation and finite quantization level. Numerical results
are presented to validate the superiority of the proposed schemes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.15398v1">PriCE: Privacy-Preserving and Cost-Effective Scheduling for
  Parallelizing the Large Medical Image Processing Workflow over Hybrid Clouds</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computational Engineering, Finance, and Science-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2024-05-24T09:52:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuandou Wang, Neel Kanwal, Kjersti Engan, Chunming Rong, Paola Grosso, Zhiming Zhao</p>
    <p><b>Summary:</b> Running deep neural networks for large medical images is a resource-hungry
and time-consuming task with centralized computing. Outsourcing such medical
image processing tasks to hybrid clouds has benefits, such as a significant
reduction of execution time and monetary cost. However, due to privacy
concerns, it is still challenging to process sensitive medical images over
clouds, which would hinder their deployment in many real-world applications. To
overcome this, we first formulate the overall optimization objectives of the
privacy-preserving distributed system model, i.e., minimizing the amount of
information about the private data learned by the adversaries throughout the
process, reducing the maximum execution time and cost under the user budget
constraint. We propose a novel privacy-preserving and cost-effective method
called PriCE to solve this multi-objective optimization problem. We performed
extensive simulation experiments for artifact detection tasks on medical images
using an ensemble of five deep convolutional neural network inferences as the
workflow task. Experimental results show that PriCE successfully splits a wide
range of input gigapixel medical images with graph-coloring-based strategies,
yielding desired output utility and lowering the privacy risk, makespan, and
monetary cost under user's budget.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.01603v1">Privacy-preserving recommender system using the data collaboration
  analysis for distributed datasets</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-05-24T07:43:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tomoya Yanagi, Shunnosuke Ikeda, Noriyoshi Sukegawa, Yuichi Takano</p>
    <p><b>Summary:</b> In order to provide high-quality recommendations for users, it is desirable
to share and integrate multiple datasets held by different parties. However,
when sharing such distributed datasets, we need to protect personal and
confidential information contained in the datasets. To this end, we establish a
framework for privacy-preserving recommender systems using the data
collaboration analysis of distributed datasets. Numerical experiments with two
public rating datasets demonstrate that our privacy-preserving method for
rating prediction can improve the prediction accuracy for distributed datasets.
This study opens up new possibilities for privacy-preserving techniques in
recommender systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.15272v1">Physiological Data: Challenges for Privacy and Ethics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> 
  <p><b>Published on:</b> 2024-05-24T06:59:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Keith Davis, Tuukka Ruotsalo</p>
    <p><b>Summary:</b> Wearable devices that measure and record physiological signals are now
becoming widely available to the general public with ever-increasing
affordability and signal quality. The data from these devices introduce serious
ethical challenges that remain largely unaddressed. Users do not always
understand how these data can be leveraged to reveal private information about
them and developers of these devices may not fully grasp how physiological data
collected today could be used in the future for completely different purposes.
We discuss the potential for wearable devices, initially designed to help users
improve their well-being or enhance the experience of some digital application,
to be appropriated in ways that extend far beyond their original intended
purpose. We identify how the currently available technology can be misused,
discuss how pairing physiological data with non-physiological data can
radically expand the predictive capacity of physiological wearables, and
explore the implications of these expanded capacities for a variety of
stakeholders.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.15150v1">Enhancing Learning with Label Differential Privacy by Vector
  Approximation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-05-24T02:08:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Puning Zhao, Rongfei Fan, Huiwen Wu, Qingming Li, Jiafei Wu, Zhe Liu</p>
    <p><b>Summary:</b> Label differential privacy (DP) is a framework that protects the privacy of
labels in training datasets, while the feature vectors are public. Existing
approaches protect the privacy of labels by flipping them randomly, and then
train a model to make the output approximate the privatized label. However, as
the number of classes $K$ increases, stronger randomization is needed, thus the
performances of these methods become significantly worse. In this paper, we
propose a vector approximation approach, which is easy to implement and
introduces little additional computational overhead. Instead of flipping each
label into a single scalar, our method converts each label into a random vector
with $K$ components, whose expectations reflect class conditional
probabilities. Intuitively, vector approximation retains more information than
scalar labels. A brief theoretical analysis shows that the performance of our
method only decays slightly with $K$. Finally, we conduct experiments on both
synthesized and real datasets, which validate our theoretical analysis as well
as the practical performance of our method.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.15140v1">Better Membership Inference Privacy Measurement through Discrepancy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-05-24T01:33:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruihan Wu, Pengrun Huang, Kamalika Chaudhuri</p>
    <p><b>Summary:</b> Membership Inference Attacks have emerged as a dominant method for
empirically measuring privacy leakage from machine learning models. Here,
privacy is measured by the {\em{advantage}} or gap between a score or a
function computed on the training and the test data. A major barrier to the
practical deployment of these attacks is that they do not scale to large
well-generalized models -- either the advantage is relatively low, or the
attack involves training multiple models which is highly compute-intensive. In
this work, inspired by discrepancy theory, we propose a new empirical privacy
metric that is an upper bound on the advantage of a family of membership
inference attacks. We show that this metric does not involve training multiple
models, can be applied to large Imagenet classification models in-the-wild, and
has higher advantage than existing metrics on models trained with more recent
and sophisticated training recipes. Motivated by our empirical results, we also
propose new membership inference attacks tailored to these training losses.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.14725v1">A Systematic and Formal Study of the Impact of Local Differential
  Privacy on Fairness: Preliminary Results</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-23T15:54:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Karima Makhlouf, Tamara Stefanovic, Heber H. Arcolezi, Catuscia Palamidessi</p>
    <p><b>Summary:</b> Machine learning (ML) algorithms rely primarily on the availability of
training data, and, depending on the domain, these data may include sensitive
information about the data providers, thus leading to significant privacy
issues. Differential privacy (DP) is the predominant solution for
privacy-preserving ML, and the local model of DP is the preferred choice when
the server or the data collector are not trusted. Recent experimental studies
have shown that local DP can impact ML prediction for different subgroups of
individuals, thus affecting fair decision-making. However, the results are
conflicting in the sense that some studies show a positive impact of privacy on
fairness while others show a negative one. In this work, we conduct a
systematic and formal study of the effect of local DP on fairness.
Specifically, we perform a quantitative study of how the fairness of the
decisions made by the ML model changes under local DP for different levels of
privacy and data distributions. In particular, we provide bounds in terms of
the joint distributions and the privacy level, delimiting the extent to which
local DP can impact the fairness of the model. We characterize the cases in
which privacy reduces discrimination and those with the opposite effect. We
validate our theoretical findings on synthetic and real-world datasets. Our
results are preliminary in the sense that, for now, we study only the case of
one sensitive attribute, and only statistical disparity, conditional
statistical disparity, and equal opportunity difference.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.14528v1">Towards Privacy-Aware and Personalised Assistive Robots: A User-Centred
  Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-05-23T13:14:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fernando E. Casado</p>
    <p><b>Summary:</b> The global increase in the elderly population necessitates innovative
long-term care solutions to improve the quality of life for vulnerable
individuals while reducing caregiver burdens. Assistive robots, leveraging
advancements in Machine Learning, offer promising personalised support.
However, their integration into daily life raises significant privacy concerns.
Widely used frameworks like the Robot Operating System (ROS) historically lack
inherent privacy mechanisms, complicating data-driven approaches in robotics.
This research pioneers user-centric, privacy-aware technologies such as
Federated Learning (FL) to advance assistive robotics. FL enables collaborative
learning without sharing sensitive data, addressing privacy and scalability
issues. This work includes developing solutions for smart wheelchair
assistance, enhancing user independence and well-being. By tackling challenges
related to non-stationary data and heterogeneous environments, the research
aims to improve personalisation and user experience. Ultimately, it seeks to
lead the responsible integration of assistive robots into society, enhancing
the quality of life for elderly and care-dependent individuals.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.14457v1">Tighter Privacy Auditing of DP-SGD in the Hidden State Threat Model</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-23T11:38:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tudor Cebere, Aurélien Bellet, Nicolas Papernot</p>
    <p><b>Summary:</b> Machine learning models can be trained with formal privacy guarantees via
differentially private optimizers such as DP-SGD. In this work, we study such
privacy guarantees when the adversary only accesses the final model, i.e.,
intermediate model updates are not released. In the existing literature, this
hidden state threat model exhibits a significant gap between the lower bound
provided by empirical privacy auditing and the theoretical upper bound provided
by privacy accounting. To challenge this gap, we propose to audit this threat
model with adversaries that craft a gradient sequence to maximize the privacy
loss of the final model without accessing intermediate models. We demonstrate
experimentally how this approach consistently outperforms prior attempts at
auditing the hidden state model. When the crafted gradient is inserted at every
optimization step, our results imply that releasing only the final model does
not amplify privacy, providing a novel negative result. On the other hand, when
the crafted gradient is not inserted at every step, we show strong evidence
that a privacy amplification phenomenon emerges in the general non-convex
setting (albeit weaker than in convex regimes), suggesting that existing
privacy upper bounds can be improved.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.14038v1">FLIPHAT: Joint Differential Privacy for High Dimensional Sparse Linear
  Bandits</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> 
  <p><b>Published on:</b> 2024-05-22T22:19:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sunrit Chakraborty, Saptarshi Roy, Debabrota Basu</p>
    <p><b>Summary:</b> High dimensional sparse linear bandits serve as an efficient model for
sequential decision-making problems (e.g. personalized medicine), where high
dimensional features (e.g. genomic data) on the users are available, but only a
small subset of them are relevant. Motivated by data privacy concerns in these
applications, we study the joint differentially private high dimensional sparse
linear bandits, where both rewards and contexts are considered as private data.
First, to quantify the cost of privacy, we derive a lower bound on the regret
achievable in this setting. To further address the problem, we design a
computationally efficient bandit algorithm, \textbf{F}orgetfu\textbf{L}
\textbf{I}terative \textbf{P}rivate \textbf{HA}rd \textbf{T}hresholding
(FLIPHAT). Along with doubling of episodes and episodic forgetting, FLIPHAT
deploys a variant of Noisy Iterative Hard Thresholding (N-IHT) algorithm as a
sparse linear regression oracle to ensure both privacy and regret-optimality.
We show that FLIPHAT achieves optimal regret up to logarithmic factors. We
analyze the regret by providing a novel refined analysis of the estimation
error of N-IHT, which is of parallel interest.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.13857v1">What Do Privacy Advertisements Communicate to Consumers?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-05-22T17:32:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaoxin Shen, Eman Alashwali, Lorrie Faith Cranor</p>
    <p><b>Summary:</b> When companies release marketing materials aimed at promoting their privacy
practices or highlighting specific privacy features, what do they actually
communicate to consumers? In this paper, we explore the impact of privacy
marketing materials on: (1) consumers' attitude towards the organizations
providing the campaigns, (2) overall privacy awareness, and (3) the
actionability of suggested privacy advice. To this end, we investigated the
impact of four privacy advertising videos and one privacy game published by
five different technology companies. We conducted 24 semi-structured interviews
with participants randomly assigned to view one or two of the videos or play
the game. Our findings suggest that awareness of privacy features can
contribute to positive perceptions of a company or its products. The ads we
tested were more successful in communicating the advertised privacy features
than the game we tested. We observed that advertising a single privacy feature
using a single metaphor in a short ad increased awareness of the advertised
feature. The game failed to communicate privacy features or motivate study
participants to use the features. Our results also suggest that privacy
campaigns can be useful for raising awareness about privacy features and
improving brand image, but may not be the most effective way to teach viewers
how to use privacy features.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.13847v1">AI-Protected Blockchain-based IoT environments: Harnessing the Future of
  Network Security and Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-22T17:14:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ali Mohammadi Ruzbahani</p>
    <p><b>Summary:</b> Integrating blockchain technology with the Internet of Things offers
transformative possibilities for enhancing network security and privacy in the
contemporary digital landscape, where interconnected devices and expansive
networks are ubiquitous. This paper explores the pivotal role of artificial
intelligence in bolstering blockchain-enabled IoT systems, potentially marking
a significant leap forward in safeguarding data integrity and confidentiality
across networks. Blockchain technology provides a decentralized and immutable
ledger, ideal for the secure management of device identities and transactions
in IoT networks. When coupled with AI, these systems gain the ability to not
only automate and optimize security protocols but also adaptively respond to
new and evolving cyber threats. This dual capability enhances the resilience of
networks against cyber-attacks, a critical consideration as IoT devices
increasingly permeate critical infrastructures. The synergy between AI and
blockchain in IoT is profound. AI algorithms can analyze vast amounts of data
from IoT devices to detect patterns and anomalies that may signify security
breaches. Concurrently, blockchain can ensure that data records are
tamper-proof, enhancing the reliability of AI-driven security measures.
Moreover, this research evaluates the implications of AI-enhanced blockchain
systems on privacy protection within IoT networks. IoT devices often collect
sensitive personal data, making privacy a paramount concern. AI can facilitate
the development of new protocols that ensure data privacy and user anonymity
without compromising the functionality of IoT systems. Through comprehensive
analysis and case studies, this paper aims to provide an in-depth understanding
of how AI-enhanced blockchain technology can revolutionize network security and
privacy in IoT environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.13804v1">Guarding Multiple Secrets: Enhanced Summary Statistic Privacy for Data
  Sharing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-22T16:30:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuaiqi Wang, Rongzhe Wei, Mohsen Ghassemi, Eleonora Kreacic, Vamsi K. Potluru</p>
    <p><b>Summary:</b> Data sharing enables critical advances in many research areas and business
applications, but it may lead to inadvertent disclosure of sensitive summary
statistics (e.g., means or quantiles). Existing literature only focuses on
protecting a single confidential quantity, while in practice, data sharing
involves multiple sensitive statistics. We propose a novel framework to define,
analyze, and protect multi-secret summary statistics privacy in data sharing.
Specifically, we measure the privacy risk of any data release mechanism by the
worst-case probability of an attacker successfully inferring summary statistic
secrets. Given an attacker's objective spanning from inferring a subset to the
entirety of summary statistic secrets, we systematically design and analyze
tailored privacy metrics. Defining the distortion as the worst-case distance
between the original and released data distribution, we analyze the tradeoff
between privacy and distortion. Our contribution also includes designing and
analyzing data release mechanisms tailored for different data distributions and
secret types. Evaluations on real-world data demonstrate the effectiveness of
our mechanisms in practical applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.13801v1">Bayesian Inference Under Differential Privacy: Prior Selection
  Considerations with Application to Univariate Gaussian Data and Regression</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-22T16:27:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zeki Kazan, Jerome P. Reiter</p>
    <p><b>Summary:</b> We describe Bayesian inference for the mean and variance of bounded data
protected by differential privacy and modeled as Gaussian. Using this setting,
we demonstrate that analysts can and should take the constraints imposed by the
bounds into account when specifying prior distributions. Additionally, we
provide theoretical and empirical results regarding what classes of default
priors produce valid inference for a differentially private release in settings
where substantial prior information is not available. We discuss how these
results can be applied to Bayesian inference for regression with differentially
private data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.13744v1">A Privacy Measure Turned Upside Down? Investigating the Use of HTTP
  Client Hints on the Web</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B">
  <p><b>Published on:</b> 2024-05-22T15:32:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stephan Wiefling, Marian Hönscheid, Luigi Lo Iacono</p>
    <p><b>Summary:</b> HTTP client hints are a set of standardized HTTP request headers designed to
modernize and potentially replace the traditional user agent string. While the
user agent string exposes a wide range of information about the client's
browser and device, client hints provide a controlled and structured approach
for clients to selectively disclose their capabilities and preferences to
servers. Essentially, client hints aim at more effective and privacy-friendly
disclosure of browser or client properties than the user agent string.
  We present a first long-term study of the use of HTTP client hints in the
wild. We found that despite being implemented in almost all web browsers,
server-side usage of client hints remains generally low. However, in the
context of third-party websites, which are often linked to trackers, the
adoption rate is significantly higher. This is concerning because client hints
allow the retrieval of more data from the client than the user agent string
provides, and there are currently no mechanisms for users to detect or control
this potential data leakage. Our work provides valuable insights for web users,
browser vendors, and researchers by exposing potential privacy violations via
client hints and providing help in developing remediation strategies as well as
further research.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.13453v1">A Huber Loss Minimization Approach to Mean Estimation under User-level
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-22T08:46:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Puning Zhao, Lifeng Lai, Li Shen, Qingming Li, Jiafei Wu, Zhe Liu</p>
    <p><b>Summary:</b> Privacy protection of users' entire contribution of samples is important in
distributed systems. The most effective approach is the two-stage scheme, which
finds a small interval first and then gets a refined estimate by clipping
samples into the interval. However, the clipping operation induces bias, which
is serious if the sample distribution is heavy-tailed. Besides, users with
large local sample sizes can make the sensitivity much larger, thus the method
is not suitable for imbalanced users. Motivated by these challenges, we propose
a Huber loss minimization approach to mean estimation under user-level
differential privacy. The connecting points of Huber loss can be adaptively
adjusted to deal with imbalanced users. Moreover, it avoids the clipping
operation, thus significantly reducing the bias compared with the two-stage
approach. We provide a theoretical analysis of our approach, which gives the
noise strength needed for privacy protection, as well as the bound of mean
squared error. The result shows that the new method is much less sensitive to
the imbalance of user-wise sample sizes and the tail of sample distributions.
Finally, we perform numerical experiments to validate our theoretical analysis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.13380v1">The Illusion of Anonymity: Uncovering the Impact of User Actions on
  Privacy in Web3 Social Ecosystems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-22T06:26:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bin Wang, Tianjian Liu, Wenqi Wang, Yuan Weng, Chao Li, Guangquan Xu, Meng Shen, Sencun Zhu, Wei Wang</p>
    <p><b>Summary:</b> The rise of Web3 social ecosystems signifies the dawn of a new chapter in
digital interaction, offering significant prospects for user engagement and
financial advancement. Nonetheless, this progress is shadowed by potential
privacy concessions, especially as these platforms frequently merge with
existing Web2.0 social media accounts, amplifying data privacy risks for users.
  In this study, we investigate the nuanced dynamics between user engagement on
Web3 social platforms and the consequent privacy concerns. We scrutinize the
widespread phenomenon of fabricated activities, which encompasses the
establishment of bogus accounts aimed at mimicking popularity and the
deliberate distortion of social interactions by some individuals to gain
financial rewards. Such deceptive maneuvers not only distort the true measure
of the active user base but also amplify privacy threats for all members of the
user community. We also find that, notwithstanding their attempts to limit
social exposure, users remain entangled in privacy vulnerabilities. The actions
of those highly engaged users, albeit often a minority group, can inadvertently
breach the privacy of the larger collective.
  By casting light on the delicate interplay between user engagement, financial
motives, and privacy issues, we offer a comprehensive examination of the
intrinsic challenges and hazards present in the Web3 social milieu. We
highlight the urgent need for more stringent privacy measures and ethical
protocols to navigate the complex web of social exchanges and financial
ambitions in the rapidly evolving Web3.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.13156v1">A Privacy-Preserving DAO Model Using NFT Authentication for the
  Punishment not Reward Blockchain Architecture</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2024-05-21T18:53:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Talgar Bayan, Richard Banach</p>
    <p><b>Summary:</b> \This paper presents a novel decentralized autonomous organization (DAO)
model leveraging non-fungible tokens (NFTs) for advanced access control and
privacy-preserving interactions within a Punishment not Reward (PnR) blockchain
framework. The proposed model introduces a dual NFT architecture: Membership
NFTs (\(NFT_{auth}\)) for authentication and access control, and Interaction
NFTs (\(NFT_{priv}\)) for enabling private, encrypted interactions among
participants. Governance is enforced through smart contracts that manage
reputation and administer punitive measures, such as conditional identity
disclosure. By prioritizing privacy, security, and deterrence over financial
rewards, this model addresses key challenges in existing blockchain incentive
structures, paving the way for more sustainable and decentralized governance
frameworks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.11975v2">A Stochastic Sampling Approach to Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2024-05-20T12:10:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chuanghong Weng, Ehsan Nekouei</p>
    <p><b>Summary:</b> This paper proposes an optimal stochastic sampling approach to privacy, in
which a sensor observes a process which is correlated to private information,
and a sampler decides to keep or discard the sensor's observations. The kept
samples are shared with an adversary who might attempt to infer the private
process. The privacy leakages are captured with the mutual information between
the private process and sampler's output. We cast the optimal sampling design
as an optimization problem that (i) minimizes the reconstruction error of the
observed process using the sampler's output, (ii) and reduces privacy leakages.
We first show the optimal reconstruction is obtained by solving a one-step
optimization problem at each time step. We derive the optimality equations of
the sampler for a general processes via the dynamic decomposition method, and
show the sampler controls adversary's belief about the private input. Also, we
propose a simplified design for linear Gaussian processes by restricting the
sampling policy to a special collection. We show that the optimal
reconstruction of states, the belief state and the optimization objective can
be analytically expressed based on a conditional mean and covariance matrix. We
develop an numerical algorithm to optimize the sampling and reconstruction
policies based on the implicit function theorem. Finally, we verify our design
and show its capabilities in state reconstruction, privacy protection and data
size reduction via simulations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.11923v1">Rate Optimality and Phase Transition for User-Level Local Differential
  Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">  
  <p><b>Published on:</b> 2024-05-20T09:59:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alexander Kent, Thomas B. Berrett, Yi Yu</p>
    <p><b>Summary:</b> Most of the literature on differential privacy considers the item-level case
where each user has a single observation, but a growing field of interest is
that of user-level privacy where each of the $n$ users holds $T$ observations
and wishes to maintain the privacy of their entire collection.
  In this paper, we derive a general minimax lower bound, which shows that, for
locally private user-level estimation problems, the risk cannot, in general, be
made to vanish for a fixed number of users even when each user holds an
arbitrarily large number of observations. We then derive matching, up to
logarithmic factors, lower and upper bounds for univariate and multidimensional
mean estimation, sparse mean estimation and non-parametric density estimation.
In particular, with other model parameters held fixed, we observe phase
transition phenomena in the minimax rates as $T$ the number of observations
each user holds varies.
  In the case of (non-sparse) mean estimation and density estimation, we see
that, for $T$ below a phase transition boundary, the rate is the same as having
$nT$ users in the item-level setting. Different behaviour is however observed
in the case of $s$-sparse $d$-dimensional mean estimation, wherein consistent
estimation is impossible when $d$ exceeds the number of observations in the
item-level setting, but is possible in the user-level setting when $T \gtrsim s
\log (d)$, up to logarithmic factors. This may be of independent interest for
applications as an example of a high-dimensional problem that is feasible under
local privacy constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.11713v1">Decentralized Privacy Preservation for Critical Connections in Graphs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2024-05-20T01:22:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Conggai Li, Wei Ni, Ming Ding, Youyang Qu, Jianjun Chen, David Smith, Wenjie Zhang, Thierry Rakotoarivelo</p>
    <p><b>Summary:</b> Many real-world interconnections among entities can be characterized as
graphs. Collecting local graph information with balanced privacy and data
utility has garnered notable interest recently. This paper delves into the
problem of identifying and protecting critical information of entity
connections for individual participants in a graph based on cohesive subgraph
searches. This problem has not been addressed in the literature. To address the
problem, we propose to extract the critical connections of a queried vertex
using a fortress-like cohesive subgraph model known as $p$-cohesion. A user's
connections within a fortress are obfuscated when being released, to protect
critical information about the user. Novel merit and penalty score functions
are designed to measure each participant's critical connections in the minimal
$p$-cohesion, facilitating effective identification of the connections. We
further propose to preserve the privacy of a vertex enquired by only protecting
its critical connections when responding to queries raised by data collectors.
We prove that, under the decentralized differential privacy (DDP) mechanism,
one's response satisfies $(\varepsilon, \delta)$-DDP when its critical
connections are protected while the rest remains unperturbed. The effectiveness
of our proposed method is demonstrated through extensive experiments on
real-life graph datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.11712v1">Trust, Because You Can't Verify:Privacy and Security Hurdles in
  Education Technology Acquisition Practices</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-05-20T01:15:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Easton Kelso, Ananta Soneji, Sazzadur Rahaman, Yan Soshitaishvili, Rakibul Hasan</p>
    <p><b>Summary:</b> The education technology (EdTech) landscape is expanding rapidly in higher
education institutes (HEIs). This growth brings enormous complexity. Protecting
the extensive data collected by these tools is crucial for HEIs. Privacy
incidents of data breaches and misuses can have dire security and privacy
consequences on the data subjects, particularly students, who are often
compelled to use these tools. This urges an in-depth understanding of HEI and
EdTech vendor dynamics, which is largely understudied.
  To address this gap, we conduct a semi-structured interview study with 13
participants who are in the EdTech leadership roles at seven HEIs. Our study
uncovers the EdTech acquisition process in the HEI context, the consideration
of security and privacy issues throughout that process, the pain points of HEI
personnel in establishing adequate security and privacy protection mechanisms
in service contracts, and their struggle in holding vendors accountable due to
a lack of visibility into their system and power-asymmetry, among other
reasons. We discuss certain observations about the status quo and conclude with
recommendations to improve the situation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.11580v1">Securing Health Data on the Blockchain: A Differential Privacy and
  Federated Learning Framework</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-05-19T15:15:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Daniel Commey, Sena Hounsinou, Garth V. Crosby</p>
    <p><b>Summary:</b> This study proposes a framework to enhance privacy in Blockchain-based
Internet of Things (BIoT) systems used in the healthcare sector. The framework
addresses the challenge of leveraging health data for analytics while
protecting patient privacy. To achieve this, the study integrates Differential
Privacy (DP) with Federated Learning (FL) to protect sensitive health data
collected by IoT nodes. The proposed framework utilizes dynamic personalization
and adaptive noise distribution strategies to balance privacy and data utility.
Additionally, blockchain technology ensures secure and transparent aggregation
and storage of model updates. Experimental results on the SVHN dataset
demonstrate that the proposed framework achieves strong privacy guarantees
against various attack scenarios while maintaining high accuracy in health
analytics tasks. For 15 rounds of federated learning with an epsilon value of
8.0, the model obtains an accuracy of 64.50%. The blockchain integration,
utilizing Ethereum, Ganache, Web3.py, and IPFS, exhibits an average transaction
latency of around 6 seconds and consistent gas consumption across rounds,
validating the practicality and feasibility of the proposed approach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.11419v1">Sketches-based join size estimation under local differential privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-19T01:21:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Meifan Zhang, Xin Liu, Lihua Yin</p>
    <p><b>Summary:</b> Join size estimation on sensitive data poses a risk of privacy leakage. Local
differential privacy (LDP) is a solution to preserve privacy while collecting
sensitive data, but it introduces significant noise when dealing with sensitive
join attributes that have large domains. Employing probabilistic structures
such as sketches is a way to handle large domains, but it leads to
hash-collision errors. To achieve accurate estimations, it is necessary to
reduce both the noise error and hash-collision error. To tackle the noise error
caused by protecting sensitive join values with large domains, we introduce a
novel algorithm called LDPJoinSketch for sketch-based join size estimation
under LDP. Additionally, to address the inherent hash-collision errors in
sketches under LDP, we propose an enhanced method called LDPJoinSketch+. It
utilizes a frequency-aware perturbation mechanism that effectively separates
high-frequency and low-frequency items without compromising privacy. The
proposed methods satisfy LDP, and the estimation error is bounded. Experimental
results show that our method outperforms existing methods, effectively
enhancing the accuracy of join size estimation under LDP.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.11341v1">A Secure and Privacy-Friendly Logging Scheme</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-05-18T17:10:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Andreas Aßmuth, Robert Duncan, Simon Liebl, Matthias Söllner</p>
    <p><b>Summary:</b> Finding a robust security mechanism for audit trail logging has long been a
poorly satisfied goal. There are many reasons for this. The most significant of
these is that the audit trail is a highly sought after goal of attackers to
ensure that they do not get caught. Thus they have an incredibly strong
incentive to prevent companies from succeeding in this worthy aim. Regulation,
such as the European Union General Data Protection Regulation, has brought a
strong incentive for companies to achieve success in this area due to the
punitive level of fines that can now be levied in the event of a successful
breach by an attacker. We seek to resolve this issue through the use of an
encrypted audit trail process that saves encrypted records to a true immutable
database, which can ensure audit trail records are permanently retained in
encrypted form, with no possibility of the records being compromised. This
ensures compliance with the General Data Protection Regulation can be achieved.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.10904v1">Broadening Privacy and Surveillance: Eliciting Interconnected Values
  with a Scenarios Workbook on Smart Home Cameras</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-05-17T16:50:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Richmond Y. Wong, Jason Caleb Valdez, Ashten Alexander, Ariel Chiang, Olivia Quesada, James Pierce</p>
    <p><b>Summary:</b> We use a design workbook of speculative scenarios as a values elicitation
activity with 14 participants. The workbook depicts use case scenarios with
smart home camera technologies that involve surveillance and uneven power
relations. The scenarios were initially designed by the researchers to explore
scenarios of privacy and surveillance within three social relationships
involving "primary" and "non-primary" users: Parents-Children,
Landlords-Tenants, and Residents-Domestic Workers. When the scenarios were
utilized as part of a values elicitation activity with participants, we found
that they reflected on a broader set of interconnected social values beyond
privacy and surveillance, including autonomy and agency, physical safety,
property rights, trust and accountability, and fairness. The paper suggests
that future research about ethical issues in smart homes should conceptualize
privacy as interconnected with a broader set of social values (which can align
or be in tension with privacy), and reflects on considerations for doing
research with non-primary users.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.10870v1">Multicenter Privacy-Preserving Model Training for Deep Learning Brain
  Metastases Autosegmentation</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-05-17T16:01:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yixing Huang, Zahra Khodabakhshi, Ahmed Gomaa, Manuel Schmidt, Rainer Fietkau, Matthias Guckenberger, Nicolaus Andratschke, Christoph Bert, Stephanie Tanadini-Lang, Florian Putz</p>
    <p><b>Summary:</b> Objectives: This work aims to explore the impact of multicenter data
heterogeneity on deep learning brain metastases (BM) autosegmentation
performance, and assess the efficacy of an incremental transfer learning
technique, namely learning without forgetting (LWF), to improve model
generalizability without sharing raw data.
  Materials and methods: A total of six BM datasets from University Hospital
Erlangen (UKER), University Hospital Zurich (USZ), Stanford, UCSF, NYU and
BraTS Challenge 2023 on BM segmentation were used for this evaluation. First,
the multicenter performance of a convolutional neural network (DeepMedic) for
BM autosegmentation was established for exclusive single-center training and
for training on pooled data, respectively. Subsequently bilateral collaboration
was evaluated, where a UKER pretrained model is shared to another center for
further training using transfer learning (TL) either with or without LWF.
  Results: For single-center training, average F1 scores of BM detection range
from 0.625 (NYU) to 0.876 (UKER) on respective single-center test data. Mixed
multicenter training notably improves F1 scores at Stanford and NYU, with
negligible improvement at other centers. When the UKER pretrained model is
applied to USZ, LWF achieves a higher average F1 score (0.839) than naive TL
(0.570) and single-center training (0.688) on combined UKER and USZ test data.
Naive TL improves sensitivity and contouring accuracy, but compromises
precision. Conversely, LWF demonstrates commendable sensitivity, precision and
contouring accuracy. When applied to Stanford, similar performance was
observed.
  Conclusion: Data heterogeneity results in varying performance in BM
autosegmentation, posing challenges to model generalizability. LWF is a
promising approach to peer-to-peer privacy-preserving model training.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.10868v1">Air Signing and Privacy-Preserving Signature Verification for Digital
  Documents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-05-17T16:00:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> P. Sarveswarasarma, T. Sathulakjan, V. J. V. Godfrey, Thanuja D. Ambegoda</p>
    <p><b>Summary:</b> This paper presents a novel approach to the digital signing of electronic
documents through the use of a camera-based interaction system, single-finger
tracking for sign recognition, and multi commands executing hand gestures. The
proposed solution, referred to as "Air Signature," involves writing the
signature in front of the camera, rather than relying on traditional methods
such as mouse drawing or physically signing on paper and showing it to a web
camera. The goal is to develop a state-of-the-art method for detecting and
tracking gestures and objects in real-time. The proposed methods include
applying existing gesture recognition and object tracking systems, improving
accuracy through smoothing and line drawing, and maintaining continuity during
fast finger movements. An evaluation of the fingertip detection, sketching, and
overall signing process is performed to assess the effectiveness of the
proposed solution. The secondary objective of this research is to develop a
model that can effectively recognize the unique signature of a user. This type
of signature can be verified by neural cores that analyze the movement, speed,
and stroke pixels of the signing in real time. The neural cores use machine
learning algorithms to match air signatures to the individual's stored
signatures, providing a secure and efficient method of verification. Our
proposed System does not require sensors or any hardware other than the camera.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.10521v1">Generative AI for Secure and Privacy-Preserving Mobile Crowdsensing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-17T04:00:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yaoqi Yang, Bangning Zhang, Daoxing Guo, Hongyang Du, Zehui Xiong, Dusit Niyato, Zhu Han</p>
    <p><b>Summary:</b> Recently, generative AI has attracted much attention from both academic and
industrial fields, which has shown its potential, especially in the data
generation and synthesis aspects. Simultaneously, secure and privacy-preserving
mobile crowdsensing (SPPMCS) has been widely applied in data collection/
acquirement due to an advantage on low deployment cost, flexible
implementation, and high adaptability. Since generative AI can generate new
synthetic data to replace the original data to be analyzed and processed, it
can lower data attacks and privacy leakage risks for the original data.
Therefore, integrating generative AI into SPPMCS is feasible and significant.
Moreover, this paper investigates an integration of generative AI in SPPMCS,
where we present potential research focuses, solutions, and case studies.
Specifically, we firstly review the preliminaries for generative AI and SPPMCS,
where their integration potential is presented. Then, we discuss research
issues and solutions for generative AI-enabled SPPMCS, including security
defense of malicious data injection, illegal authorization, malicious spectrum
manipulation at the physical layer, and privacy protection on sensing data
content, sensing terminals' identification and location. Next, we propose a
framework for sensing data content protection with generative AI, and
simulations results have clearly demonstrated the effectiveness of the proposed
framework. Finally, we present major research directions for generative
AI-enabled SPPMCS.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.10096v1">The Effect of Quantization in Federated Learning: A Rényi Differential
  Privacy Perspective</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-05-16T13:50:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tianqu Kang, Lumin Liu, Hengtao He, Jun Zhang, S. H. Song, Khaled B. Letaief</p>
    <p><b>Summary:</b> Federated Learning (FL) is an emerging paradigm that holds great promise for
privacy-preserving machine learning using distributed data. To enhance privacy,
FL can be combined with Differential Privacy (DP), which involves adding
Gaussian noise to the model weights. However, FL faces a significant challenge
in terms of large communication overhead when transmitting these model weights.
To address this issue, quantization is commonly employed. Nevertheless, the
presence of quantized Gaussian noise introduces complexities in understanding
privacy protection. This research paper investigates the impact of quantization
on privacy in FL systems. We examine the privacy guarantees of quantized
Gaussian mechanisms using R\'enyi Differential Privacy (RDP). By deriving the
privacy budget of quantized Gaussian mechanisms, we demonstrate that lower
quantization bit levels provide improved privacy protection. To validate our
theoretical findings, we employ Membership Inference Attacks (MIA), which gauge
the accuracy of privacy leakage. The numerical results align with our
theoretical analysis, confirming that quantization can indeed enhance privacy
protection. This study not only enhances our understanding of the correlation
between privacy and communication in FL but also underscores the advantages of
quantization in preserving privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.10989v1">Learnable Privacy Neurons Localization in Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-16T08:11:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruizhe Chen, Tianxiang Hu, Yang Feng, Zuozhu Liu</p>
    <p><b>Summary:</b> Concerns regarding Large Language Models (LLMs) to memorize and disclose
private information, particularly Personally Identifiable Information (PII),
become prominent within the community. Many efforts have been made to mitigate
the privacy risks. However, the mechanism through which LLMs memorize PII
remains poorly understood. To bridge this gap, we introduce a pioneering method
for pinpointing PII-sensitive neurons (privacy neurons) within LLMs. Our method
employs learnable binary weight masks to localize specific neurons that account
for the memorization of PII in LLMs through adversarial training. Our
investigations discover that PII is memorized by a small subset of neurons
across all layers, which shows the property of PII specificity. Furthermore, we
propose to validate the potential in PII risk mitigation by deactivating the
localized privacy neurons. Both quantitative and qualitative experiments
demonstrate the effectiveness of our neuron localization algorithm.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.09882v1">DiffAM: Diffusion-based Adversarial Makeup Transfer for Facial Privacy
  Protection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-05-16T08:05:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuhao Sun, Lingyun Yu, Hongtao Xie, Jiaming Li, Yongdong Zhang</p>
    <p><b>Summary:</b> With the rapid development of face recognition (FR) systems, the privacy of
face images on social media is facing severe challenges due to the abuse of
unauthorized FR systems. Some studies utilize adversarial attack techniques to
defend against malicious FR systems by generating adversarial examples.
However, the generated adversarial examples, i.e., the protected face images,
tend to suffer from subpar visual quality and low transferability. In this
paper, we propose a novel face protection approach, dubbed DiffAM, which
leverages the powerful generative ability of diffusion models to generate
high-quality protected face images with adversarial makeup transferred from
reference images. To be specific, we first introduce a makeup removal module to
generate non-makeup images utilizing a fine-tuned diffusion model with guidance
of textual prompts in CLIP space. As the inverse process of makeup transfer,
makeup removal can make it easier to establish the deterministic relationship
between makeup domain and non-makeup domain regardless of elaborate text
prompts. Then, with this relationship, a CLIP-based makeup loss along with an
ensemble attack strategy is introduced to jointly guide the direction of
adversarial makeup domain, achieving the generation of protected face images
with natural-looking makeup and high black-box transferability. Extensive
experiments demonstrate that DiffAM achieves higher visual quality and attack
success rates with a gain of 12.98% under black-box setting compared with the
state of the arts. The code will be available at
https://github.com/HansSunY/DiffAM.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.09306v1">Words Blending Boxes. Obfuscating Queries in Information Retrieval using
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-15T12:51:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Francesco Luigi De Faveri, Guglielmo Faggioli, Nicola Ferro</p>
    <p><b>Summary:</b> Ensuring the effectiveness of search queries while protecting user privacy
remains an open issue. When an Information Retrieval System (IRS) does not
protect the privacy of its users, sensitive information may be disclosed
through the queries sent to the system. Recent improvements, especially in NLP,
have shown the potential of using Differential Privacy to obfuscate texts while
maintaining satisfactory effectiveness. However, such approaches may protect
the user's privacy only from a theoretical perspective while, in practice, the
real user's information need can still be inferred if perturbed terms are too
semantically similar to the original ones. We overcome such limitations by
proposing Word Blending Boxes, a novel differentially private mechanism for
query obfuscation, which protects the words in the user queries by employing
safe boxes. To measure the overall effectiveness of the proposed WBB mechanism,
we measure the privacy obtained by the obfuscation process, i.e., the lexical
and semantic similarity between original and obfuscated queries. Moreover, we
assess the effectiveness of the privatized queries in retrieving relevant
documents from the IRS. Our findings indicate that WBB can be integrated
effectively into existing IRSs, offering a key to the challenge of protecting
user privacy from both a theoretical and a practical point of view.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.09234v1">Enhancing Image Privacy in Semantic Communication over Wiretap Channels
  leveraging Differential Privacy</a></h3>
  
  <p><b>Published on:</b> 2024-05-15T10:30:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Weixuan Chen, Shunpu Tang, Qianqian Yang</p>
    <p><b>Summary:</b> Semantic communication (SemCom) enhances transmission efficiency by sending
only task-relevant information compared to traditional methods. However,
transmitting semantic-rich data over insecure or public channels poses security
and privacy risks. This paper addresses the privacy problem of transmitting
images over wiretap channels and proposes a novel SemCom approach ensuring
privacy through a differential privacy (DP)-based image protection and
deprotection mechanism. The method utilizes the GAN inversion technique to
extract disentangled semantic features and applies a DP mechanism to protect
sensitive features within the extracted semantic information. To address the
non-invertibility of DP, we introduce two neural networks to approximate the DP
application and removal processes, offering a privacy protection level close to
that by the original DP process. Simulation results validate the effectiveness
of our method in preventing eavesdroppers from obtaining sensitive information
while maintaining high-fidelity image reconstruction at the legitimate
receiver.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.09230v1">Reduce to the MACs -- Privacy Friendly Generic Probe Requests</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2024-05-15T10:18:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Johanna Ansohn McDougall, Alessandro Brighente, Anne Kunstmann, Niklas Zapatka, Hannes Federrath</p>
    <p><b>Summary:</b> Abstract. Since the introduction of active discovery in Wi-Fi networks, users
can be tracked via their probe requests. Although manufacturers typically try
to conceal Media Access Control (MAC) addresses using MAC address
randomisation, probe requests still contain Information Elements (IEs) that
facilitate device identification. This paper introduces generic probe requests:
By removing all unnecessary information from IEs, the requests become
indistinguishable from one another, letting single devices disappear in the
largest possible anonymity set. Conducting a comprehensive evaluation, we
demonstrate that a large IE set contained within undirected probe requests does
not necessarily imply fast connection establishment. Furthermore, we show that
minimising IEs to nothing but Supported Rates would enable 82.55% of the
devices to share the same anonymity set. Our contributions provide a
significant advancement in the pursuit of robust privacy solutions for wireless
networks, paving the way for more user anonymity and less surveillance in
wireless communication ecosystems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.09014v1">Feature-based Federated Transfer Learning: Communication Efficiency,
  Robustness and Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2024-05-15T00:43:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Feng Wang, M. Cenk Gursoy, Senem Velipasalar</p>
    <p><b>Summary:</b> In this paper, we propose feature-based federated transfer learning as a
novel approach to improve communication efficiency by reducing the uplink
payload by multiple orders of magnitude compared to that of existing approaches
in federated learning and federated transfer learning. Specifically, in the
proposed feature-based federated learning, we design the extracted features and
outputs to be uploaded instead of parameter updates. For this distributed
learning model, we determine the required payload and provide comparisons with
the existing schemes. Subsequently, we analyze the robustness of feature-based
federated transfer learning against packet loss, data insufficiency, and
quantization. Finally, we address privacy considerations by defining and
analyzing label privacy leakage and feature privacy leakage, and investigating
mitigating approaches. For all aforementioned analyses, we evaluate the
performance of the proposed learning scheme via experiments on an image
classification task and a natural language processing task to demonstrate its
effectiveness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.08920v2">Neural Collapse Meets Differential Privacy: Curious Behaviors of NoisyGD
  with Near-perfect Representation Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> 
  <p><b>Published on:</b> 2024-05-14T19:18:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chendi Wang, Yuqing Zhu, Weijie J. Su, Yu-Xiang Wang</p>
    <p><b>Summary:</b> A recent study by De et al. (2022) has reported that large-scale
representation learning through pre-training on a public dataset significantly
enhances differentially private (DP) learning in downstream tasks, despite the
high dimensionality of the feature space. To theoretically explain this
phenomenon, we consider the setting of a layer-peeled model in representation
learning, which results in interesting phenomena related to learned features in
deep learning and transfer learning, known as Neural Collapse (NC).
  Within the framework of NC, we establish an error bound indicating that the
misclassification error is independent of dimension when the distance between
actual features and the ideal ones is smaller than a threshold. Additionally,
the quality of the features in the last layer is empirically evaluated under
different pre-trained models within the framework of NC, showing that a more
powerful transformer leads to a better feature representation. Furthermore, we
reveal that DP fine-tuning is less robust compared to fine-tuning without DP,
particularly in the presence of perturbations. These observations are supported
by both theoretical analyses and experimental evaluation. Moreover, to enhance
the robustness of DP fine-tuning, we suggest several strategies, such as
feature normalization or employing dimension reduction methods like Principal
Component Analysis (PCA). Empirically, we demonstrate a significant improvement
in testing accuracy by conducting PCA on the last-layer features.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.08801v2">Prospects of Privacy Advantage in Quantum Machine Learning</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-05-14T17:49:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jamie Heredge, Niraj Kumar, Dylan Herman, Shouvanik Chakrabarti, Romina Yalovetzky, Shree Hari Sureshbabu, Changhao Li, Marco Pistoia</p>
    <p><b>Summary:</b> Ensuring data privacy in machine learning models is critical, particularly in
distributed settings where model gradients are typically shared among multiple
parties to allow collaborative learning. Motivated by the increasing success of
recovering input data from the gradients of classical models, this study
addresses a central question: How hard is it to recover the input data from the
gradients of quantum machine learning models? Focusing on variational quantum
circuits (VQC) as learning models, we uncover the crucial role played by the
dynamical Lie algebra (DLA) of the VQC ansatz in determining privacy
vulnerabilities. While the DLA has previously been linked to the classical
simulatability and trainability of VQC models, this work, for the first time,
establishes its connection to the privacy of VQC models. In particular, we show
that properties conducive to the trainability of VQCs, such as a
polynomial-sized DLA, also facilitate the extraction of detailed snapshots of
the input. We term this a weak privacy breach, as the snapshots enable training
VQC models for distinct learning tasks without direct access to the original
input. Further, we investigate the conditions for a strong privacy breach where
the original input data can be recovered from these snapshots by classical or
quantum-assisted polynomial time methods. We establish conditions on the
encoding map such as classical simulatability, overlap with DLA basis, and its
Fourier frequency characteristics that enable such a privacy breach of VQC
models. Our findings thus play a crucial role in detailing the prospects of
quantum privacy advantage by guiding the requirements for designing quantum
machine learning models that balance trainability with robust privacy
protection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.08698v1">Byzantine-Resilient Secure Aggregation for Federated Learning Without
  Privacy Compromises</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2024-05-14T15:37:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yue Xia, Christoph Hofmeister, Maximilian Egger, Rawad Bitar</p>
    <p><b>Summary:</b> Federated learning (FL) shows great promise in large scale machine learning,
but brings new risks in terms of privacy and security. We propose ByITFL, a
novel scheme for FL that provides resilience against Byzantine users while
keeping the users' data private from the federator and private from other
users. The scheme builds on the preexisting non-private FLTrust scheme, which
tolerates malicious users through trust scores (TS) that attenuate or amplify
the users' gradients. The trust scores are based on the ReLU function, which we
approximate by a polynomial. The distributed and privacy-preserving computation
in ByITFL is designed using a combination of Lagrange coded computing,
verifiable secret sharing and re-randomization steps. ByITFL is the first
Byzantine resilient scheme for FL with full information-theoretic privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.08518v1">Cryptography-Based Privacy-Preserving Method for Distributed
  Optimization over Time-Varying Directed Graphs with Enhanced Efficiency</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E">
  <p><b>Published on:</b> 2024-05-14T11:48:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bing Liu, Furan Xie, Li Chai</p>
    <p><b>Summary:</b> In this paper, we study the privacy-preserving distributed optimization
problem, aiming to prevent attackers from stealing the private information of
agents. For this purpose, we propose a novel privacy-preserving algorithm based
on the Advanced Encryption Standard (AES), which is both secure and
computationally efficient. By appropriately constructing the underlying weight
matrices, our algorithm can be applied to time-varying directed networks. We
show that the proposed algorithm can protect an agent's privacy if the agent
has at least one legitimate neighbor at the initial iteration. Under the
assumption that the objective function is strongly convex and Lipschitz smooth,
we rigorously prove that the proposed algorithm has a linear convergence rate.
Finally, the effectiveness of the proposed algorithm is demonstrated by
numerical simulations of the canonical sensor fusion problem.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.08356v1">A Model-oriented Reasoning Framework for Privacy Analysis of Complex
  Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-14T06:52:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sebastian Rehms, Stefan Köpsell, Verena Klös, Florian Tschorsch</p>
    <p><b>Summary:</b> This paper proposes a reasoning framework for privacy properties of systems
and their environments that can capture any knowledge leaks on different
logical levels of the system to answer the question: which entity can learn
what? With the term knowledge we refer to any kind of data, meta-data or
interpretation of those that might be relevant. To achieve this, we present a
modeling framework that forces the developers to explicitly describe which
knowledge is available at which entity, which knowledge flows between entities
and which knowledge can be inferred from other knowledge. In addition, privacy
requirements are specified as rules describing forbidden knowledge for
entities. Our modeling approach is incremental, starting from an abstract view
of the system and adding details through well-defined transformations. This
work is intended to complement existing approaches and introduces steps towards
more formal foundations for privacy oriented analyses while keeping them as
accessible as possible. It is designed to be extensible through schemata and
vocabulary to enable compatibility with external requirements and standards.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.08084v1">PrivFED -- A Framework for Privacy-Preserving Federated Learning in
  Enhanced Breast Cancer Diagnosis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-13T18:01:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maithili Jha, S. Maitri, M. Lohithdakshan, Shiny Duela J, K. Raja</p>
    <p><b>Summary:</b> In the day-to-day operations of healthcare institutions, a multitude of
Personally Identifiable Information (PII) data exchanges occur, exposing the
data to a spectrum of cybersecurity threats. This study introduces a federated
learning framework, trained on the Wisconsin dataset, to mitigate challenges
such as data scarcity and imbalance. Techniques like the Synthetic Minority
Over-sampling Technique (SMOTE) are incorporated to bolster robustness, while
isolation forests are employed to fortify the model against outliers. Catboost
serves as the classification tool across all devices. The identification of
optimal features for heightened accuracy is pursued through Principal Component
Analysis (PCA),accentuating the significance of hyperparameter tuning, as
underscored in a comparative analysis. The model exhibits an average accuracy
of 99.95% on edge devices and 98% on the central server.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.07596v1">Local Mutual-Information Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2024-05-13T09:58:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Khac-Hoang Ngo, Johan Östman, Alexandre Graell i Amat</p>
    <p><b>Summary:</b> Local mutual-information differential privacy (LMIDP) is a privacy notion
that aims to quantify the reduction of uncertainty about the input data when
the output of a privacy-preserving mechanism is revealed. We study the relation
of LMIDP with local differential privacy (LDP), the de facto standard notion of
privacy in context-independent (CI) scenarios, and with local information
privacy (LIP), the state-of-the-art notion for context-dependent settings. We
establish explicit conversion rules, i.e., bounds on the privacy parameters for
a LMIDP mechanism to also satisfy LDP/LIP, and vice versa. We use our bounds to
formally verify that LMIDP is a weak privacy notion. We also show that
uncorrelated Gaussian noise is the best-case noise in terms of CI-LMIDP if both
the input data and the noise are subject to an average power constraint.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.07440v1">Maximizing Information Gain in Privacy-Aware Active Learning of Email
  Anomalies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-05-13T02:58:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mu-Huan Miles Chung, Sharon Li, Jaturong Kongmanee, Lu Wang, Yuhong Yang, Calvin Giang, Khilan Jerath, Abhay Raman, David Lie, Mark Chignell</p>
    <p><b>Summary:</b> Redacted emails satisfy most privacy requirements but they make it more
difficult to detect anomalous emails that may be indicative of data
exfiltration. In this paper we develop an enhanced method of Active Learning
using an information gain maximizing heuristic, and we evaluate its
effectiveness in a real world setting where only redacted versions of email
could be labeled by human analysts due to privacy concerns. In the first case
study we examined how Active Learning should be carried out. We found that
model performance was best when a single highly skilled (in terms of the
labelling task) analyst provided the labels. In the second case study we used
confidence ratings to estimate the labeling uncertainty of analysts and then
prioritized instances for labeling based on the expected information gain (the
difference between model uncertainty and analyst uncertainty) that would be
provided by labelling each instance. We found that the information maximization
gain heuristic improved model performance over existing sampling methods for
Active Learning. Based on the results obtained, we recommend that analysts
should be screened, and possibly trained, prior to implementation of Active
Learning in cybersecurity applications. We also recommend that the information
gain maximizing sample method (based on expert confidence) should be used in
early stages of Active Learning, providing that well-calibrated confidence can
be obtained. We also note that the expertise of analysts should be assessed
prior to Active Learning, as we found that analysts with lower labelling skill
had poorly calibrated (over-) confidence in their labels.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.07020v1">Adaptive Online Bayesian Estimation of Frequency Distributions with
  Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-05-11T13:59:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Soner Aydin, Sinan Yildirim</p>
    <p><b>Summary:</b> We propose a novel Bayesian approach for the adaptive and online estimation
of the frequency distribution of a finite number of categories under the local
differential privacy (LDP) framework. The proposed algorithm performs Bayesian
parameter estimation via posterior sampling and adapts the randomization
mechanism for LDP based on the obtained posterior samples. We propose a
randomized mechanism for LDP which uses a subset of categories as an input and
whose performance depends on the selected subset and the true frequency
distribution. By using the posterior sample as an estimate of the frequency
distribution, the algorithm performs a computationally tractable subset
selection step to maximize the utility of the privatized response of the next
user. We propose several utility functions related to well-known information
metrics, such as (but not limited to) Fisher information matrix, total
variation distance, and information entropy. We compare each of these utility
metrics in terms of their computational complexity. We employ stochastic
gradient Langevin dynamics for posterior sampling, a computationally efficient
approximate Markov chain Monte Carlo method. We provide a theoretical analysis
showing that (i) the posterior distribution targeted by the algorithm converges
to the true parameter even for approximate posterior sampling, and (ii) the
algorithm selects the optimal subset with high probability if posterior
sampling is performed exactly. We also provide numerical results that
empirically demonstrate the estimation accuracy of our algorithm where we
compare it with nonadaptive and semi-adaptive approaches under experimental
settings with various combinations of privacy parameters and population
distribution parameters.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.06307v1">Smooth Sensitivity for Geo-Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-10T08:32:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuting Liang, Ke Yi</p>
    <p><b>Summary:</b> Suppose each user $i$ holds a private value $x_i$ in some metric space $(U,
\mathrm{dist})$, and an untrusted data analyst wishes to compute $\sum_i
f(x_i)$ for some function $f : U \rightarrow \mathbb{R}$ by asking each user to
send in a privatized $f(x_i)$. This is a fundamental problem in
privacy-preserving population analytics, and the local model of differential
privacy (LDP) is the predominant model under which the problem has been
studied. However, LDP requires any two different $x_i, x'_i$ to be
$\varepsilon$-distinguishable, which can be overly strong for
geometric/numerical data. On the other hand, Geo-Privacy (GP) stipulates that
the level of distinguishability be proportional to $\mathrm{dist}(x_i, x_i')$,
providing an attractive alternative notion of personal data privacy in a metric
space. However, existing GP mechanisms for this problem, which add a uniform
noise to either $x_i$ or $f(x_i)$, are not satisfactory. In this paper, we
generalize the smooth sensitivity framework from Differential Privacy to
Geo-Privacy, which allows us to add noise tailored to the hardness of the given
instance. We provide definitions, mechanisms, and a generic procedure for
computing the smooth sensitivity under GP equipped with a general metric. Then
we present three applications: one-way and two-way threshold functions, and
Gaussian kernel density estimation, to demonstrate the applicability and
utility of our smooth sensitivity framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.06261v1">Improving the Privacy Loss Under User-Level DP Composition for Fixed
  Estimation Error</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2024-05-10T06:24:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> V. Arvind Rameshwar, Anshoo Tandon</p>
    <p><b>Summary:</b> This paper considers the private release of statistics of several disjoint
subsets of a datasets, under user-level $\epsilon$-differential privacy (DP).
In particular, we consider the user-level differentially private release of
sample means and variances of speed values in several grids in a city, in a
potentially sequential manner. Traditional analysis of the privacy loss due to
the sequential composition of queries necessitates a privacy loss degradation
by a factor that equals the total number of grids. Our main contribution is an
iterative, instance-dependent algorithm, based on clipping the number of user
contributions, which seeks to reduce the overall privacy loss degradation under
a canonical Laplace mechanism, while not increasing the {worst} estimation
error among the different grids. We test the performance of our algorithm on
synthetic datasets and demonstrate improvements in the privacy loss degradation
factor via our algorithm. We also demonstrate improvements in the worst-case
error using a simple extension of a pseudo-user creation-based mechanism. An
important component of this analysis is our exact characterization of the
sensitivities and the worst-case estimation errors of sample means and
variances incurred by clipping user contributions in an arbitrary fashion,
which we believe is of independent interest.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.05930v1">Trustworthy AI-Generative Content in Intelligent 6G Network:
  Adversarial, Privacy, and Fairness</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2024-05-09T17:16:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Siyuan Li, Xi Lin, Yaju Liu, Jianhua Li</p>
    <p><b>Summary:</b> AI-generated content (AIGC) models, represented by large language models
(LLM), have brought revolutionary changes to the content generation fields. The
high-speed and extensive 6G technology is an ideal platform for providing
powerful AIGC mobile service applications, while future 6G mobile networks also
need to support intelligent and personalized mobile generation services.
However, the significant ethical and security issues of current AIGC models,
such as adversarial attacks, privacy, and fairness, greatly affect the
credibility of 6G intelligent networks, especially in ensuring secure, private,
and fair AIGC applications. In this paper, we propose TrustGAIN, a novel
paradigm for trustworthy AIGC in 6G networks, to ensure trustworthy large-scale
AIGC services in future 6G networks. We first discuss the adversarial attacks
and privacy threats faced by AIGC systems in 6G networks, as well as the
corresponding protection issues. Subsequently, we emphasize the importance of
ensuring the unbiasedness and fairness of the mobile generative service in
future intelligent networks. In particular, we conduct a use case to
demonstrate that TrustGAIN can effectively guide the resistance against
malicious or generated false information. We believe that TrustGAIN is a
necessary paradigm for intelligent and trustworthy 6G networks to support AIGC
services, ensuring the security, privacy, and fairness of AIGC network
services.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.05789v1">High-Performance Privacy-Preserving Matrix Completion for Trajectory
  Recovery</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Numerical Analysis-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Numerical Analysis-D91E36">
  <p><b>Published on:</b> 2024-05-09T14:12:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiahao Guo, An-Bao Xu</p>
    <p><b>Summary:</b> Matrix completion has important applications in trajectory recovery and
mobile social networks. However, sending raw data containing personal,
sensitive information to cloud computing nodes may lead to privacy exposure
issue.The privacy-preserving matrix completion is a useful approach to perform
matrix completion while preserving privacy. In this paper, we propose a
high-performance method for privacy-preserving matrix completion. First,we use
a lightweight encryption scheme to encrypt the raw data and then perform matrix
completion using alternating direction method of multipliers (ADMM). Then,the
complemented matrix is decrypted and compared with the original matrix to
calculate the error. This method has faster speed with higher accuracy. The
results of numerical experiments reveal that the proposed method is faster than
other algorithms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.05611v1">Privacy-Preserving Edge Federated Learning for Intelligent Mobile-Health
  Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-09T08:15:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Amin Aminifar, Matin Shokri, Amir Aminifar</p>
    <p><b>Summary:</b> Machine Learning (ML) algorithms are generally designed for scenarios in
which all data is stored in one data center, where the training is performed.
However, in many applications, e.g., in the healthcare domain, the training
data is distributed among several entities, e.g., different hospitals or
patients' mobile devices/sensors. At the same time, transferring the data to a
central location for learning is certainly not an option, due to privacy
concerns and legal issues, and in certain cases, because of the communication
and computation overheads. Federated Learning (FL) is the state-of-the-art
collaborative ML approach for training an ML model across multiple parties
holding local data samples, without sharing them. However, enabling learning
from distributed data over such edge Internet of Things (IoT) systems (e.g.,
mobile-health and wearable technologies, involving sensitive personal/medical
data) in a privacy-preserving fashion presents a major challenge mainly due to
their stringent resource constraints, i.e., limited computing capacity,
communication bandwidth, memory storage, and battery lifetime. In this paper,
we propose a privacy-preserving edge FL framework for resource-constrained
mobile-health and wearable technologies over the IoT infrastructure. We
evaluate our proposed framework extensively and provide the implementation of
our technique on Amazon's AWS cloud platform based on the seizure detection
application in epilepsy monitoring using wearable technologies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.05567v1">Perfect Subset Privacy in Polynomial Computation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2024-05-09T06:11:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zirui Deng, Vinayak Ramkumar, Netanel Raviv</p>
    <p><b>Summary:</b> Delegating large-scale computations to service providers is a common practice
which raises privacy concerns. This paper studies information-theoretic
privacy-preserving delegation of data to a service provider, who may further
delegate the computation to auxiliary worker nodes, in order to compute a
polynomial over that data at a later point in time. We study techniques which
are compatible with robust management of distributed computation systems, an
area known as coded computing. Privacy in coded computing, however, has
traditionally addressed the problem of colluding workers, and assumed that the
server that administrates the computation is trusted. This viewpoint of privacy
does not accurately reflect real-world privacy concerns, since normally, the
service provider as a whole (i.e., the administrator and the worker nodes) form
one cohesive entity which itself poses a privacy risk. This paper aims to shift
the focus of privacy in coded computing to safeguarding the privacy of the user
against the service provider as a whole, instead of merely against colluding
workers inside the service provider. To this end, we leverage the recently
defined notion of perfect subset privacy, which guarantees zero information
leakage from all subsets of the data up to a certain size. Using known
techniques from Reed-Muller decoding, we provide a scheme which enables
polynomial computation with perfect subset privacy in straggler-free systems.
Furthermore, by studying information super-sets in Reed-Muller codes, which may
be of independent interest, we extend the previous scheme to tolerate
straggling worker nodes inside the service provider.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.05175v1">Air Gap: Protecting Privacy-Conscious Conversational Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-05-08T16:12:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Eugene Bagdasaryan, Ren Yi, Sahra Ghalebikesabi, Peter Kairouz, Marco Gruteser, Sewoong Oh, Borja Balle, Daniel Ramage</p>
    <p><b>Summary:</b> The growing use of large language model (LLM)-based conversational agents to
manage sensitive user data raises significant privacy concerns. While these
agents excel at understanding and acting on context, this capability can be
exploited by malicious actors. We introduce a novel threat model where
adversarial third-party apps manipulate the context of interaction to trick
LLM-based agents into revealing private information not relevant to the task at
hand.
  Grounded in the framework of contextual integrity, we introduce AirGapAgent,
a privacy-conscious agent designed to prevent unintended data leakage by
restricting the agent's access to only the data necessary for a specific task.
Extensive experiments using Gemini, GPT, and Mistral models as agents validate
our approach's effectiveness in mitigating this form of context hijacking while
maintaining core agent functionality. For example, we show that a single-query
context hijacking attack on a Gemini Ultra agent reduces its ability to protect
user data from 94% to 45%, while an AirGapAgent achieves 97% protection,
rendering the same attack ineffective.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.04344v2">Enhancing Scalability of Metric Differential Privacy via Secret Dataset
  Partitioning and Benders Decomposition</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-07T14:19:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chenxi Qiu</p>
    <p><b>Summary:</b> Metric Differential Privacy (mDP) extends the concept of Differential Privacy
(DP) to serve as a new paradigm of data perturbation. It is designed to protect
secret data represented in general metric space, such as text data encoded as
word embeddings or geo-location data on the road network or grid maps. To
derive an optimal data perturbation mechanism under mDP, a widely used method
is linear programming (LP), which, however, might suffer from a polynomial
explosion of decision variables, rendering it impractical in large-scale mDP.
  In this paper, our objective is to develop a new computation framework to
enhance the scalability of the LP-based mDP. Considering the connections
established by the mDP constraints among the secret records, we partition the
original secret dataset into various subsets. Building upon the partition, we
reformulate the LP problem for mDP and solve it via Benders Decomposition,
which is composed of two stages: (1) a master program to manage the
perturbation calculation across subsets and (2) a set of subproblems, each
managing the perturbation derivation within a subset. Our experimental results
on multiple datasets, including geo-location data in the road network/grid
maps, text data, and synthetic data, underscore our proposed mechanism's
superior scalability and efficiency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.04108v1">A2-DIDM: Privacy-preserving Accumulator-enabled Auditing for Distributed
  Identity of DNN Model</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-05-07T08:24:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tianxiu Xie, Keke Gai, Jing Yu, Liehuang Zhu, Kim-Kwang Raymond Choo</p>
    <p><b>Summary:</b> Recent booming development of Generative Artificial Intelligence (GenAI) has
facilitated an emerging model commercialization for the purpose of
reinforcement on model performance, such as licensing or trading Deep Neural
Network (DNN) models. However, DNN model trading may trigger concerns of the
unauthorized replications or misuses over the model, so that the benefit of the
model ownership will be violated. Model identity auditing is a challenging
issue in protecting intellectual property of DNN models and verifying the
integrity and ownership of models for guaranteeing trusts in transactions is
one of the critical obstacles. In this paper, we focus on the above issue and
propose a novel Accumulator-enabled Auditing for Distributed Identity of DNN
Model (A2-DIDM) that utilizes blockchain and zero-knowledge techniques to
protect data and function privacy while ensuring the lightweight on-chain
ownership verification. The proposed model presents a scheme of identity
records via configuring model weight checkpoints with corresponding
zero-knowledge proofs, which incorporates predicates to capture incremental
state changes in model weight checkpoints. Our scheme ensures both
computational integrity of DNN training process and programmability, so that
the uniqueness of the weight checkpoint sequence in a DNN model is preserved,
ensuring the correctness of the model identity auditing. In addition, A2-DIDM
also addresses privacy protections in distributed identity via a proposed
method of accumulators. We systematically analyze the security and robustness
of our proposed model and further evaluate the effectiveness and usability of
auditing DNN model identities.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.04029v1">Enabling Privacy-Preserving and Publicly Auditable Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-05-07T06:03:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Huang Zeng, Anjia Yang, Jian Weng, Min-Rong Chen, Fengjun Xiao, Yi Liu, Ye Yao</p>
    <p><b>Summary:</b> Federated learning (FL) has attracted widespread attention because it
supports the joint training of models by multiple participants without moving
private dataset. However, there are still many security issues in FL that
deserve discussion. In this paper, we consider three major issues: 1) how to
ensure that the training process can be publicly audited by any third party; 2)
how to avoid the influence of malicious participants on training; 3) how to
ensure that private gradients and models are not leaked to third parties. Many
solutions have been proposed to address these issues, while solving the above
three problems simultaneously is seldom considered. In this paper, we propose a
publicly auditable and privacy-preserving federated learning scheme that is
resistant to malicious participants uploading gradients with wrong directions
and enables anyone to audit and verify the correctness of the training process.
In particular, we design a robust aggregation algorithm capable of detecting
gradients with wrong directions from malicious participants. Then, we design a
random vector generation algorithm and combine it with zero sharing and
blockchain technologies to make the joint training process publicly auditable,
meaning anyone can verify the correctness of the training. Finally, we conduct
a series of experiments, and the experimental results show that the model
generated by the protocol is comparable in accuracy to the original FL approach
while keeping security advantages.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.03915v1">Motivating Users to Attend to Privacy: A Theory-Driven Design Study</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-05-07T00:23:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Varun Shiri, Maggie Xiong, Jinghui Cheng, Jin L. C. Guo</p>
    <p><b>Summary:</b> In modern technology environments, raising users' privacy awareness is
crucial. Existing efforts largely focused on privacy policy presentation and
failed to systematically address a radical challenge of user motivation for
initiating privacy awareness. Leveraging the Protection Motivation Theory
(PMT), we proposed design ideas and categories dedicated to motivating users to
engage with privacy-related information. Using these design ideas, we created a
conceptual prototype, enhancing the current App Store product page. Results
from an online experiment and follow-up interviews showed that our design
effectively motivated participants to attend to privacy issues, raising both
the threat appraisal and coping appraisal, two main factors in PMT. Our work
indicated that effective design should consider combining PMT components,
calibrating information content, and integrating other design elements, such as
visual cues and user familiarity. Overall, our study contributes valuable
design considerations driven by the PMT to amplify the motivational aspect of
privacy communication.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.03903v1">Unified Locational Differential Privacy Framework</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-05-06T23:33:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aman Priyanshu, Yash Maurya, Suriya Ganesh, Vy Tran</p>
    <p><b>Summary:</b> Aggregating statistics over geographical regions is important for many
applications, such as analyzing income, election results, and disease spread.
However, the sensitive nature of this data necessitates strong privacy
protections to safeguard individuals. In this work, we present a unified
locational differential privacy (DP) framework to enable private aggregation of
various data types, including one-hot encoded, boolean, float, and integer
arrays, over geographical regions. Our framework employs local DP mechanisms
such as randomized response, the exponential mechanism, and the Gaussian
mechanism. We evaluate our approach on four datasets representing significant
location data aggregation scenarios. Results demonstrate the utility of our
framework in providing formal DP guarantees while enabling geographical data
analysis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.03636v1">Federated Learning Privacy: Attacks, Defenses, Applications, and Policy
  Landscape - A Survey</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2024-05-06T16:55:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joshua C. Zhao, Saurabh Bagchi, Salman Avestimehr, Kevin S. Chan, Somali Chaterji, Dimitris Dimitriadis, Jiacheng Li, Ninghui Li, Arash Nourian, Holger R. Roth</p>
    <p><b>Summary:</b> Deep learning has shown incredible potential across a vast array of tasks and
accompanying this growth has been an insatiable appetite for data. However, a
large amount of data needed for enabling deep learning is stored on personal
devices and recent concerns on privacy have further highlighted challenges for
accessing such data. As a result, federated learning (FL) has emerged as an
important privacy-preserving technology enabling collaborative training of
machine learning models without the need to send the raw, potentially
sensitive, data to a central server. However, the fundamental premise that
sending model updates to a server is privacy-preserving only holds if the
updates cannot be "reverse engineered" to infer information about the private
training data. It has been shown under a wide variety of settings that this
premise for privacy does {\em not} hold.
  In this survey paper, we provide a comprehensive literature review of the
different privacy attacks and defense methods in FL. We identify the current
limitations of these attacks and highlight the settings in which FL client
privacy can be broken. We dissect some of the successful industry applications
of FL and draw lessons for future successful adoption. We survey the emerging
landscape of privacy regulation for FL. We conclude with future directions for
taking FL toward the cherished goal of generating accurate models while
preserving the privacy of the data from its participants.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.03106v1">Compression-based Privacy Preservation for Distributed Nash Equilibrium
  Seeking in Aggregative Games</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2024-05-06T01:42:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wei Huo, Xiaomeng Chen, Kemi Ding, Subhrakanti Dey, Ling Shi</p>
    <p><b>Summary:</b> This paper explores distributed aggregative games in multi-agent systems.
Current methods for finding distributed Nash equilibrium require players to
send original messages to their neighbors, leading to communication burden and
privacy issues. To jointly address these issues, we propose an algorithm that
uses stochastic compression to save communication resources and conceal
information through random errors induced by compression. Our theoretical
analysis shows that the algorithm guarantees convergence accuracy, even with
aggressive compression errors used to protect privacy. We prove that the
algorithm achieves differential privacy through a stochastic quantization
scheme. Simulation results for energy consumption games support the
effectiveness of our approach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.03065v1">Powering the Future of IoT: Federated Learning for Optimized Power
  Consumption and Enhanced Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-05T22:18:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ghazaleh Shirvani, Saeid Ghasemshirazi</p>
    <p><b>Summary:</b> The widespread use of the Internet of Things has led to the development of
large amounts of perception data, making it necessary to develop effective and
scalable data analysis tools. Federated Learning emerges as a promising
paradigm to address the inherent challenges of power consumption and data
privacy in IoT environments. This paper explores the transformative potential
of FL in enhancing the longevity of IoT devices by mitigating power consumption
and enhancing privacy and security measures. We delve into the intricacies of
FL, elucidating its components and applications within IoT ecosystems.
Additionally, we discuss the critical characteristics and challenges of IoT,
highlighting the need for such machine learning solutions in processing
perception data. While FL introduces many benefits for IoT sustainability, it
also has limitations. Through a comprehensive discussion and analysis, this
paper elucidates the opportunities and constraints of FL in shaping the future
of sustainable and secure IoT systems. Our findings highlight the importance of
developing new approaches and conducting additional research to maximise the
benefits of FL in creating a secure and privacy-focused IoT environment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.02665v1">Metric Differential Privacy at the User-Level</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-04T13:29:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jacob Imola, Amrita Roy Chowdhury, Kamalika Chaudhuri</p>
    <p><b>Summary:</b> Metric differential privacy (DP) provides heterogeneous privacy guarantees
based on a distance between the pair of inputs. It is a widely popular notion
of privacy since it captures the natural privacy semantics for many
applications (such as, for location data) and results in better utility than
standard DP. However, prior work in metric DP has primarily focused on the
\textit{item-level} setting where every user only reports a single data item. A
more realistic setting is that of user-level DP where each user contributes
multiple items and privacy is then desired at the granularity of the user's
\textit{entire} contribution. In this paper, we initiate the study of metric DP
at the user-level. Specifically, we use the earth-mover's distance
($d_\textsf{EM}$) as our metric to obtain a notion of privacy as it captures
both the magnitude and spatial aspects of changes in a user's data.
  We make three main technical contributions. First, we design two novel
mechanisms under $d_\textsf{EM}$-DP to answer linear queries and item-wise
queries. Specifically, our analysis for the latter involves a generalization of
the privacy amplification by shuffling result which may be of independent
interest. Second, we provide a black-box reduction from the general unbounded
to bounded $d_\textsf{EM}$-DP (size of the dataset is fixed and public) with a
novel sampling based mechanism. Third, we show that our proposed mechanisms can
provably provide improved utility over user-level DP, for certain types of
linear queries and frequency estimation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.02437v1">FastLloyd: Federated, Accurate, Secure, and Tunable $k$-Means Clustering
  with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-05-03T19:04:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abdulrahman Diaa, Thomas Humphries, Florian Kerschbaum</p>
    <p><b>Summary:</b> We study the problem of privacy-preserving $k$-means clustering in the
horizontally federated setting. Existing federated approaches using secure
computation, suffer from substantial overheads and do not offer output privacy.
At the same time, differentially private (DP) $k$-means algorithms assume a
trusted central curator and do not extend to federated settings. Naively
combining the secure and DP solutions results in a protocol with impractical
overhead. Instead, our work provides enhancements to both the DP and secure
computation components, resulting in a design that is faster, more private, and
more accurate than previous work. By utilizing the computational DP model, we
design a lightweight, secure aggregation-based approach that achieves four
orders of magnitude speed-up over state-of-the-art related work. Furthermore,
we not only maintain the utility of the state-of-the-art in the central model
of DP, but we improve the utility further by taking advantage of constrained
clustering techniques.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.01844v1">A Survey on Privacy-Preserving Caching at Network Edge: Classification,
  Solutions, and Challenges</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-05-03T04:27:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xianzhi Zhang, Yipeng Zhou, Di Wu, Shazia Riaz, Quan Z. Sheng, Miao Hu, Linchang Xiao</p>
    <p><b>Summary:</b> Caching content at the network edge is a popular and effective technique
widely deployed to alleviate the burden of network backhaul, shorten service
delay and improve service quality. However, there has been some controversy
over privacy violations in caching content at the network edge. On the one
hand, the multi-access open edge network provides an ideal surface for external
attackers to obtain private data from the edge cache by extracting sensitive
information. On the other hand, privacy can be infringed by curious edge
caching providers through caching trace analysis targeting to achieve better
caching performance or higher profits. Therefore, an in-depth understanding of
privacy issues in edge caching networks is vital and indispensable for creating
a privacy-preserving caching service at the network edge. In this article, we
are among the first to fill in this gap by examining privacy-preserving
techniques for caching content at the network edge. Firstly, we provide an
introduction to the background of Privacy-Preserving Edge Caching (PPEC). Next,
we summarize the key privacy issues and present a taxonomy for caching at the
network edge from the perspective of private data. Additionally, we conduct a
retrospective review of the state-of-the-art countermeasures against privacy
leakage from content caching at the network edge. Finally, we conclude the
survey and envision challenges for future research.</p>
  </details>
</div>

