
<h2>2024-12</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.06728v1">Byzantine-Eavesdropper Alliance: How to Achieve Symmetric Privacy in
  Quantum $X$-Secure $B$-Byzantine $E$-Eavesdropped $U$-Unresponsive
  $T$-Colluding PIR?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">   
  <p><b>Published on:</b> 2024-12-09T18:17:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohamed Nomeir, Alptug Aytekin, Sennur Ulukus</p>
    <p><b>Summary:</b> We consider the quantum \emph{symmetric} private information retrieval
(QSPIR) problem in a system with $N$ databases and $K$ messages, with $U$
unresponsive servers, $T$-colluding servers, and $X$-security parameter, under
several fundamental threat models. In the first model, there are
$\mathcal{E}_1$ eavesdropped links in the uplink direction (the direction from
the user to the $N$ servers), $\mathcal{E}_2$ eavesdropped links in the
downlink direction (the direction from the servers to the user), where
$|\mathcal{E}_1|, |\mathcal{E}_2| \leq E$; we coin this eavesdropper setting as
\emph{dynamic} eavesdroppers. We show that super-dense coding gain can be
achieved for some regimes. In the second model, we consider the case with
Byzantine servers, i.e., servers that can coordinate to devise a plan to harm
the privacy and security of the system together with static eavesdroppers, by
listening to the same links in both uplink and downlink directions. It is
important to note the considerable difference between the two threat models,
since the eavesdroppers can take huge advantage of the presence of the
Byzantine servers. Unlike the previous works in SPIR with Byzantine servers,
that assume that the Byzantine servers can send only random symbols independent
of the stored messages, we follow the definition of Byzantine servers in
\cite{byzantine_tpir}, where the Byzantine servers can send symbols that can be
functions of the storage, queries, as well as the random symbols in a way that
can produce worse harm to the system. In the third and the most novel threat
model, we consider the presence of Byzantine servers and dynamic eavesdroppers
together. We show that having dynamic eavesdroppers along with Byzantine
servers in the same system model creates more threats to the system than having
static eavesdroppers with Byzantine servers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.06689v1">Impact of Privacy Parameters on Deep Learning Models for Image
  Classification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-12-09T17:31:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Basanta Chaulagain</p>
    <p><b>Summary:</b> The project aims to develop differentially private deep learning models for
image classification on CIFAR-10 datasets \cite{cifar10} and analyze the impact
of various privacy parameters on model accuracy. We have implemented five
different deep learning models, namely ConvNet, ResNet18, EfficientNet, ViT,
and DenseNet121 and three supervised classifiers namely K-Nearest Neighbors,
Naive Bayes Classifier and Support Vector Machine. We evaluated the performance
of these models under varying settings. Our best performing model to date is
EfficientNet with test accuracy of $59.63\%$ with the following parameters
(Adam optimizer, batch size 256, epoch size 100, epsilon value 5.0, learning
rate $1e-3$, clipping threshold 1.0, and noise multiplier 0.912).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.06541v1">Numerical Estimation of Spatial Distributions under Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2024-12-09T14:53:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Leilei Du, Peng Cheng, Libin Zheng, Xiang Lian, Lei Chen, Wei Xi, Wangze Ni</p>
    <p><b>Summary:</b> Estimating spatial distributions is important in data analysis, such as
traffic flow forecasting and epidemic prevention. To achieve accurate spatial
distribution estimation, the analysis needs to collect sufficient user data.
However, collecting data directly from individuals could compromise their
privacy. Most previous works focused on private distribution estimation for
one-dimensional data, which does not consider spatial data relation and leads
to poor accuracy for spatial distribution estimation. In this paper, we address
the problem of private spatial distribution estimation, where we collect
spatial data from individuals and aim to minimize the distance between the
actual distribution and estimated one under Local Differential Privacy (LDP).
To leverage the numerical nature of the domain, we project spatial data and its
relationships onto a one-dimensional distribution. We then use this projection
to estimate the overall spatial distribution. Specifically, we propose a
reporting mechanism called Disk Area Mechanism (DAM), which projects the
spatial domain onto a line and optimizes the estimation using the sliced
Wasserstein distance. Through extensive experiments, we show the effectiveness
of our DAM approach on both real and synthetic data sets, compared with the
state-of-the-art methods, such as Multi-dimensional Square Wave Mechanism
(MDSW) and Subset Exponential Mechanism with Geo-I (SEM-Geo-I). Our results
show that our DAM always performs better than MDSW and is better than SEM-Geo-I
when the data granularity is fine enough.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.06248v1">Rendering-Refined Stable Diffusion for Privacy Compliant Synthetic Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-12-09T06:47:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kartik Patwari, David Schneider, Xiaoxiao Sun, Chen-Nee Chuah, Lingjuan Lyu, Vivek Sharma</p>
    <p><b>Summary:</b> Growing privacy concerns and regulations like GDPR and CCPA necessitate
pseudonymization techniques that protect identity in image datasets. However,
retaining utility is also essential. Traditional methods like masking and
blurring degrade quality and obscure critical context, especially in
human-centric images. We introduce Rendering-Refined Stable Diffusion (RefSD),
a pipeline that combines 3D-rendering with Stable Diffusion, enabling
prompt-based control over human attributes while preserving posture. Unlike
standard diffusion models that fail to retain posture or GANs that lack realism
and flexible attribute control, RefSD balances posture preservation, realism,
and customization. We also propose HumanGenAI, a framework for human perception
and utility evaluation. Human perception assessments reveal attribute-specific
strengths and weaknesses of RefSD. Our utility experiments show that models
trained on RefSD pseudonymized data outperform those trained on real data in
detection tasks, with further performance gains when combining RefSD with real
data. For classification tasks, we consistently observe performance
improvements when using RefSD data with real data, confirming the utility of
our pseudonymized data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.06196v1">BECS: A Privacy-Preserving Computing Sharing Mechanism in 6G Computing
  Power Network</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762"> 
  <p><b>Published on:</b> 2024-12-09T04:26:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kun Yan, Wenping Ma, Shaohui Sun</p>
    <p><b>Summary:</b> 5G networks provide secure and reliable information transmission services for
the Internet of Everything, thus paving the way for 6G networks, which is
anticipated to be an AI-based network, supporting unprecedented intelligence
across applications. Abundant computing resources will establish the 6G
Computing Power Network (CPN) to facilitate ubiquitous intelligent services. In
this article, we propose BECS, a computing sharing mechanism based on
evolutionary algorithm and blockchain, designed to balance task offloading
among user devices, edge devices, and cloud resources within 6G CPN, thereby
enhancing the computing resource utilization. We model computing sharing as a
multi-objective optimization problem, aiming to improve resource utilization
while balancing other issues. To tackle this NP-hard problem, we devise a
kernel distance-based dominance relation and incorporated it into the
Non-dominated Sorting Genetic Algorithm III, significantly enhancing the
diversity of the evolutionary population. In addition, we propose a pseudonym
scheme based on zero-knowledge proof to protect the privacy of users
participating in computing sharing. Finally, the security analysis and
simulation results demonstrate that BECS can fully and effectively utilize all
computing resources in 6G CPN, significantly improving the computing resource
utilization while protecting user privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.06120v1">Lightweight Federated Learning with Differential Privacy and Straggler
  Resilience</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-12-09T00:54:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shu Hong, Xiaojun Lin, Lingjie Duan</p>
    <p><b>Summary:</b> Federated learning (FL) enables collaborative model training through model
parameter exchanges instead of raw data. To avoid potential inference attacks
from exchanged parameters, differential privacy (DP) offers rigorous guarantee
against various attacks. However, conventional methods of ensuring DP by adding
local noise alone often result in low training accuracy. Combining secure
multi-party computation (SMPC) with DP, while improving the accuracy, incurs
high communication and computation overheads and straggler vulnerability, in
either client-to-server or client-to-client links. In this paper, we propose
LightDP-FL, a novel lightweight scheme that ensures provable DP against
untrusted peers and server, while maintaining straggler-resilience, low
overheads and high training accuracy. Our approach incorporates both individual
and pairwise noise into each client's parameter, which can be implemented with
minimal overheads. Given the uncertain straggler and colluder sets, we utilize
the upper bound on the numbers of stragglers and colluders to prove sufficient
noise variance conditions to ensure DP in the worst case. Moreover, we optimize
the expected convergence bound to ensure accuracy performance by flexibly
controlling the noise variances. Using the CIFAR-10 dataset, our experimental
results demonstrate that LightDP-FL achieves faster convergence and stronger
straggler resilience of our scheme compared to baseline methods of the same DP
level.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.06113v1">Privacy-Preserving Large Language Models: Mechanisms, Applications, and
  Future Directions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-12-09T00:24:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guoshenghui Zhao, Eric Song</p>
    <p><b>Summary:</b> The rapid advancement of large language models (LLMs) has revolutionized
natural language processing, enabling applications in diverse domains such as
healthcare, finance and education. However, the growing reliance on extensive
data for training and inference has raised significant privacy concerns,
ranging from data leakage to adversarial attacks. This survey comprehensively
explores the landscape of privacy-preserving mechanisms tailored for LLMs,
including differential privacy, federated learning, cryptographic protocols,
and trusted execution environments. We examine their efficacy in addressing key
privacy challenges, such as membership inference and model inversion attacks,
while balancing trade-offs between privacy and model utility. Furthermore, we
analyze privacy-preserving applications of LLMs in privacy-sensitive domains,
highlighting successful implementations and inherent limitations. Finally, this
survey identifies emerging research directions, emphasizing the need for novel
frameworks that integrate privacy by design into the lifecycle of LLMs. By
synthesizing state-of-the-art approaches and future trends, this paper provides
a foundation for developing robust, privacy-preserving large language models
that safeguard sensitive information without compromising performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.05894v1">FedRBE -- a decentralized privacy-preserving federated batch effect
  correction tool for omics data based on limma</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-12-08T11:23:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuliya Burankova, Julian Klemm, Jens J. G. Lohmann, Ahmad Taheri, Niklas Probul, Jan Baumbach, Olga Zolotareva</p>
    <p><b>Summary:</b> Batch effects in omics data obscure true biological signals and constitute a
major challenge for privacy-preserving analyses of distributed patient data.
Existing batch effect correction methods either require data centralization,
which may easily conflict with privacy requirements, or lack support for
missing values and automated workflows. To bridge this gap, we developed
fedRBE, a federated implementation of limma's removeBatchEffect method. We
implemented it as an app for the FeatureCloud platform. Unlike its existing
analogs, fedRBE effectively handles data with missing values and offers an
automated, user-friendly online user interface
(https://featurecloud.ai/app/fedrbe). Leveraging secure multi-party computation
provides enhanced security guarantees over classical federated learning
approaches. We evaluated our fedRBE algorithm on simulated and real omics data,
achieving performance comparable to the centralized method with negligible
differences (no greater than 3.6E-13). By enabling collaborative correction
without data sharing, fedRBE facilitates large-scale omics studies where batch
effect correction is crucial.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.05767v1">DeMem: Privacy-Enhanced Robust Adversarial Learning via De-Memorization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-12-08T00:22:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaoyu Luo, Qiongxiu Li</p>
    <p><b>Summary:</b> Adversarial robustness, the ability of a model to withstand manipulated
inputs that cause errors, is essential for ensuring the trustworthiness of
machine learning models in real-world applications. However, previous studies
have shown that enhancing adversarial robustness through adversarial training
increases vulnerability to privacy attacks. While differential privacy can
mitigate these attacks, it often compromises robustness against both natural
and adversarial samples. Our analysis reveals that differential privacy
disproportionately impacts low-risk samples, causing an unintended performance
drop. To address this, we propose DeMem, which selectively targets high-risk
samples, achieving a better balance between privacy protection and model
robustness. DeMem is versatile and can be seamlessly integrated into various
adversarial training techniques. Extensive evaluations across multiple training
methods and datasets demonstrate that DeMem significantly reduces privacy
leakage while maintaining robustness against both natural and adversarial
samples. These results confirm DeMem's effectiveness and broad applicability in
enhancing privacy without compromising robustness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.05734v1">PrivAgent: Agentic-based Red-teaming for LLM Privacy Leakage</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-12-07T20:09:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuzhou Nie, Zhun Wang, Ye Yu, Xian Wu, Xuandong Zhao, Wenbo Guo, Dawn Song</p>
    <p><b>Summary:</b> Recent studies have discovered that LLMs have serious privacy leakage
concerns, where an LLM may be fooled into outputting private information under
carefully crafted adversarial prompts. These risks include leaking system
prompts, personally identifiable information, training data, and model
parameters. Most existing red-teaming approaches for privacy leakage rely on
humans to craft the adversarial prompts. A few automated methods are proposed
for system prompt extraction, but they cannot be applied to more severe risks
(e.g., training data extraction) and have limited effectiveness even for system
prompt extraction.
  In this paper, we propose PrivAgent, a novel black-box red-teaming framework
for LLM privacy leakage. We formulate different risks as a search problem with
a unified attack goal. Our framework trains an open-source LLM through
reinforcement learning as the attack agent to generate adversarial prompts for
different target models under different risks. We propose a novel reward
function to provide effective and fine-grained rewards for the attack agent.
Finally, we introduce customizations to better fit our general framework to
system prompt extraction and training data extraction. Through extensive
evaluations, we first show that PrivAgent outperforms existing automated
methods in system prompt leakage against six popular LLMs. Notably, our
approach achieves a 100% success rate in extracting system prompts from
real-world applications in OpenAI's GPT Store. We also show PrivAgent's
effectiveness in extracting training data from an open-source LLM with a
success rate of 5.9%. We further demonstrate PrivAgent's effectiveness in
evading the existing guardrail defense and its helpfulness in enabling better
safety alignment. Finally, we validate our customized designs through a
detailed ablation study. We release our code here
https://github.com/rucnyz/RedAgent.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.05636v1">A Game-Theoretic Framework for Privacy-Aware Client Sampling in
  Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB">
  <p><b>Published on:</b> 2024-12-07T12:42:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenhao Yuan, Xuehe Wang</p>
    <p><b>Summary:</b> This paper aims to design a Privacy-aware Client Sampling framework in
Federated learning, named FedPCS, to tackle the heterogeneous client sampling
issues and improve model performance. First, we obtain a pioneering upper bound
for the accuracy loss of the FL model with privacy-aware client sampling
probabilities. Based on this, we model the interactions between the central
server and participating clients as a two-stage Stackelberg game. In Stage I,
the central server designs the optimal time-dependent reward for cost
minimization by considering the trade-off between the accuracy loss of the FL
model and the rewards allocated. In Stage II, each client determines the
correction factor that dynamically adjusts its privacy budget based on the
reward allocated to maximize its utility. To surmount the obstacle of
approximating other clients' private information, we introduce the mean-field
estimator to estimate the average privacy budget. We analytically demonstrate
the existence and convergence of the fixed point for the mean-field estimator
and derive the Stackelberg Nash Equilibrium to obtain the optimal strategy
profile. By rigorously theoretical convergence analysis, we guarantee the
robustness of FedPCS. Moreover, considering the conventional sampling strategy
in privacy-preserving FL, we prove that the random sampling approach's PoA can
be arbitrarily large. To remedy such efficiency loss, we show that the proposed
privacy-aware client sampling strategy successfully reduces PoA, which is upper
bounded by a reachable constant. To address the challenge of varying privacy
requirements throughout different training phases in FL, we extend our model
and analysis and derive the adaptive optimal sampling ratio for the central
server. Experimental results on different datasets demonstrate the superiority
of FedPCS compared with the existing SOTA FL strategies under IID and Non-IID
datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.05533v1">Can large language models be privacy preserving and fair medical coders?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-12-07T04:27:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ali Dadsetan, Dorsa Soleymani, Xijie Zeng, Frank Rudzicz</p>
    <p><b>Summary:</b> Protecting patient data privacy is a critical concern when deploying machine
learning algorithms in healthcare. Differential privacy (DP) is a common method
for preserving privacy in such settings and, in this work, we examine two key
trade-offs in applying DP to the NLP task of medical coding (ICD
classification). Regarding the privacy-utility trade-off, we observe a
significant performance drop in the privacy preserving models, with more than a
40% reduction in micro F1 scores on the top 50 labels in the MIMIC-III dataset.
From the perspective of the privacy-fairness trade-off, we also observe an
increase of over 3% in the recall gap between male and female patients in the
DP models. Further understanding these trade-offs will help towards the
challenges of real-world deployment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.05183v1">Privacy Drift: Evolving Privacy Concerns in Incremental Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-12-06T17:04:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sayyed Farid Ahamed, Soumya Banerjee, Sandip Roy, Aayush Kapoor, Marc Vucovich, Kevin Choi, Abdul Rahman, Edward Bowen, Sachin Shetty</p>
    <p><b>Summary:</b> In the evolving landscape of machine learning (ML), Federated Learning (FL)
presents a paradigm shift towards decentralized model training while preserving
user data privacy. This paper introduces the concept of ``privacy drift", an
innovative framework that parallels the well-known phenomenon of concept drift.
While concept drift addresses the variability in model accuracy over time due
to changes in the data, privacy drift encapsulates the variation in the leakage
of private information as models undergo incremental training. By defining and
examining privacy drift, this study aims to unveil the nuanced relationship
between the evolution of model performance and the integrity of data privacy.
Through rigorous experimentation, we investigate the dynamics of privacy drift
in FL systems, focusing on how model updates and data distribution shifts
influence the susceptibility of models to privacy attacks, such as membership
inference attacks (MIA). Our results highlight a complex interplay between
model accuracy and privacy safeguards, revealing that enhancements in model
performance can lead to increased privacy risks. We provide empirical evidence
from experiments on customized datasets derived from CIFAR-100 (Canadian
Institute for Advanced Research, 100 classes), showcasing the impact of data
and concept drift on privacy. This work lays the groundwork for future research
on privacy-aware machine learning, aiming to achieve a delicate balance between
model accuracy and data privacy in decentralized environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.05164v1">A Differentially Private Kaplan-Meier Estimator for Privacy-Preserving
  Survival Analysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-12-06T16:29:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Narasimha Raghavan Veeraragavan, Sai Praneeth Karimireddy, Jan Franz Nygård</p>
    <p><b>Summary:</b> This paper presents a differentially private approach to Kaplan-Meier
estimation that achieves accurate survival probability estimates while
safeguarding individual privacy. The Kaplan-Meier estimator is widely used in
survival analysis to estimate survival functions over time, yet applying it to
sensitive datasets, such as clinical records, risks revealing private
information. To address this, we introduce a novel algorithm that applies
time-indexed Laplace noise, dynamic clipping, and smoothing to produce a
privacy-preserving survival curve while maintaining the cumulative structure of
the Kaplan-Meier estimator. By scaling noise over time, the algorithm accounts
for decreasing sensitivity as fewer individuals remain at risk, while dynamic
clipping and smoothing prevent extreme values and reduce fluctuations,
preserving the natural shape of the survival curve.
  Our results, evaluated on the NCCTG lung cancer dataset, show that the
proposed method effectively lowers root mean squared error (RMSE) and enhances
accuracy across privacy budgets ($\epsilon$). At $\epsilon = 10$, the algorithm
achieves an RMSE as low as 0.04, closely approximating non-private estimates.
Additionally, membership inference attacks reveal that higher $\epsilon$ values
(e.g., $\epsilon \geq 6$) significantly reduce influential points, particularly
at higher thresholds, lowering susceptibility to inference attacks. These
findings confirm that our approach balances privacy and utility, advancing
privacy-preserving survival analysis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.04697v1">Privacy-Preserving Retrieval Augmented Generation with Differential
  Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-12-06T01:20:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tatsuki Koga, Ruihan Wu, Kamalika Chaudhuri</p>
    <p><b>Summary:</b> With the recent remarkable advancement of large language models (LLMs), there
has been a growing interest in utilizing them in the domains with highly
sensitive data that lies outside their training data. For this purpose,
retrieval augmented generation (RAG) is particularly effective -- it assists
LLMs by directly providing relevant information from the external knowledge
sources. However, without extra privacy safeguards, RAG outputs risk leaking
sensitive information from the external data source. In this work, we explore
RAG under differential privacy (DP), a formal guarantee of data privacy. The
main challenge with differentially private RAG is how to generate long accurate
answers within a moderate privacy budget. We address this by proposing an
algorithm that smartly spends privacy budget only for the tokens that require
the sensitive information and uses the non-private LLM for other tokens. Our
extensive empirical evaluations reveal that our algorithm outperforms the
non-RAG baseline under a reasonable privacy budget of $\epsilon\approx 10$
across different models and datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.04408v1">Providing Differential Privacy for Federated Learning Over Wireless: A
  Cross-layer Framework</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2024-12-05T18:27:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiayu Mao, Tongxin Yin, Aylin Yener, Mingyan Liu</p>
    <p><b>Summary:</b> Federated Learning (FL) is a distributed machine learning framework that
inherently allows edge devices to maintain their local training data, thus
providing some level of privacy. However, FL's model updates still pose a risk
of privacy leakage, which must be mitigated. Over-the-air FL (OTA-FL) is an
adapted FL design for wireless edge networks that leverages the natural
superposition property of the wireless medium. We propose a wireless physical
layer (PHY) design for OTA-FL which improves differential privacy (DP) through
a decentralized, dynamic power control that utilizes both inherent Gaussian
noise in the wireless channel and a cooperative jammer (CJ) for additional
artificial noise generation when higher privacy levels are required. Although
primarily implemented within the Upcycled-FL framework, where a
resource-efficient method with first-order approximations is used at every even
iteration to decrease the required information from clients, our power control
strategy is applicable to any FL framework, including FedAvg and FedProx as
shown in the paper. This adaptation showcases the flexibility and effectiveness
of our design across different learning algorithms while maintaining a strong
emphasis on privacy. Our design removes the need for client-side artificial
noise injection for DP, utilizing a cooperative jammer to enhance privacy
without affecting transmission efficiency for higher privacy demands. Privacy
analysis is provided using the Moments Accountant method. We perform a
convergence analysis for non-convex objectives to tackle heterogeneous data
distributions, highlighting the inherent trade-offs between privacy and
accuracy. Numerical results show that our approach with various FL algorithms
outperforms the state-of-the-art under the same DP conditions on the non-i.i.d.
FEMNIST dataset, and highlight the cooperative jammer's effectiveness in
ensuring strict privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.04178v1">Multi-Layer Privacy-Preserving Record Linkage with Clerical Review based
  on gradual information disclosure</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-12-05T14:18:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Florens Rohde, Victor Christen, Martin Franke, Erhard Rahm</p>
    <p><b>Summary:</b> Privacy-Preserving Record linkage (PPRL) is an essential component in data
integration tasks of sensitive information. The linkage quality determines the
usability of combined datasets and (machine learning) applications based on
them. We present a novel privacy-preserving protocol that integrates clerical
review in PPRL using a multi-layer active learning process. Uncertain match
candidates are reviewed on several layers by human and non-human oracles to
reduce the amount of disclosed information per record and in total. Predictions
are propagated back to update previous layers, resulting in an improved linkage
performance for non-reviewed candidates as well. The data owners remain in
control of the amount of information they share for each record. Therefore, our
approach follows need-to-know and data sovereignty principles. The experimental
evaluation on real-world datasets shows considerable linkage quality
improvements with limited labeling effort and privacy risks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.04031v1">Dimension Reduction via Random Projection for Privacy in Multi-Agent
  Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-12-05T10:09:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Puspanjali Ghoshal, Ashok Singh Sairam</p>
    <p><b>Summary:</b> The agents in a Multi-Agent System (MAS) make observations about the system
and send that information to a fusion center. The fusion center aggregates the
information and concludes about the system parameters with as much accuracy as
possible. However for the purposes of better efficiency of the system at large,
the agents need to append some private parameters to the observed data. In this
scenario, the data sent to the fusion center is faced with privacy risks. The
data communicated to the fusion center must be secured against data privacy
breaches and inference attacks in a decentralized manner. However, this in turn
leads to a loss of utility of the data being sent to the fusion center. We
quantify the utility and privacy of the system using Cosine similarity. We
formulate our MAS problem in terms of deducing a concept for which
compression-based methods are there in literature. Next, we propose a novel
sanitization mechanism for our MAS using one such compression-based method
while addressing the utility-privacy tradeoff problem.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.04518v1">Privacy-Preserving Gesture Tracking System Utilizing Frequency-Hopping
  RFID Signals</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2024-12-05T08:51:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bojun Zhang</p>
    <p><b>Summary:</b> Gesture tracking technology provides users with a hands free interactive
experience without the need to hold or touch devices. However, current gesture
tracking research has primarily focused on tracking accuracy while neglecting
issues of user privacy protection and security. This study aims to develop a
gesture tracking system based on frequency hopping RFID signals that
effectively protects user privacy without compromising tracking efficiency and
accuracy. By introducing frequency hopping technology, we have designed a
mechanism that prevents potential eavesdroppers from obtaining raw RFID
signals, thereby enhancing the systems privacy protection capabilities. The
system architec ture includes the collection of RFID signals, data processing,
signal recovery, and gesture tracking. Experimental results show that our
method significantly improves privacy protection levels while maintaining real
time and accuracy. This research not only provides a new perspective for the
field of gesture tracking but also offers valuable insights for the use of RFID
technology in privacy-sensitive applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.03924v1">Privacy-Preserving in Medical Image Analysis: A Review of Methods and
  Applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-12-05T06:56:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yanming Zhu, Xuefei Yin, Alan Wee-Chung Liew, Hui Tian</p>
    <p><b>Summary:</b> With the rapid advancement of artificial intelligence and deep learning,
medical image analysis has become a critical tool in modern healthcare,
significantly improving diagnostic accuracy and efficiency. However, AI-based
methods also raise serious privacy concerns, as medical images often contain
highly sensitive patient information. This review offers a comprehensive
overview of privacy-preserving techniques in medical image analysis, including
encryption, differential privacy, homomorphic encryption, federated learning,
and generative adversarial networks. We explore the application of these
techniques across various medical image analysis tasks, such as diagnosis,
pathology, and telemedicine. Notably, we organizes the review based on specific
challenges and their corresponding solutions in different medical image
analysis applications, so that technical applications are directly aligned with
practical issues, addressing gaps in the current research landscape.
Additionally, we discuss emerging trends, such as zero-knowledge proofs and
secure multi-party computation, offering insights for future research. This
review serves as a valuable resource for researchers and practitioners and can
help advance privacy-preserving in medical image analysis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.02987v1">Advancing Conversational Psychotherapy: Integrating Privacy,
  Dual-Memory, and Domain Expertise with Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-12-04T03:02:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> XiuYu Zhang, Zening Luo</p>
    <p><b>Summary:</b> Mental health has increasingly become a global issue that reveals the
limitations of traditional conversational psychotherapy, constrained by
location, time, expense, and privacy concerns. In response to these challenges,
we introduce SoulSpeak, a Large Language Model (LLM)-enabled chatbot designed
to democratize access to psychotherapy. SoulSpeak improves upon the
capabilities of standard LLM-enabled chatbots by incorporating a novel
dual-memory component that combines short-term and long-term context via
Retrieval Augmented Generation (RAG) to offer personalized responses while
ensuring the preservation of user privacy and intimacy through a dedicated
privacy module. In addition, it leverages a counseling chat dataset of
therapist-client interactions and various prompting techniques to align the
generated responses with psychotherapeutic methods. We introduce two fine-tuned
BERT models to evaluate the system against existing LLMs and human therapists:
the Conversational Psychotherapy Preference Model (CPPM) to simulate human
preference among responses and another to assess response relevance to user
input. CPPM is useful for training and evaluating psychotherapy-focused
language models independent from SoulSpeak, helping with the constrained
resources available for psychotherapy. Furthermore, the effectiveness of the
dual-memory component and the robustness of the privacy module are also
examined. Our findings highlight the potential and challenge of enhancing
mental health care by offering an alternative that combines the expertise of
traditional therapy with the advantages of LLMs, providing a promising way to
address the accessibility and personalization gap in current mental health
services.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.02934v1">BGTplanner: Maximizing Training Accuracy for Differentially Private
  Federated Recommenders via Strategic Privacy Budget Allocation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-12-04T01:07:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xianzhi Zhang, Yipeng Zhou, Miao Hu, Di Wu, Pengshan Liao, Mohsen Guizani, Michael Sheng</p>
    <p><b>Summary:</b> To mitigate the rising concern about privacy leakage, the federated
recommender (FR) paradigm emerges, in which decentralized clients co-train the
recommendation model without exposing their raw user-item rating data. The
differentially private federated recommender (DPFR) further enhances FR by
injecting differentially private (DP) noises into clients. Yet, current DPFRs,
suffering from noise distortion, cannot achieve satisfactory accuracy. Various
efforts have been dedicated to improving DPFRs by adaptively allocating the
privacy budget over the learning process. However, due to the intricate
relation between privacy budget allocation and model accuracy, existing works
are still far from maximizing DPFR accuracy. To address this challenge, we
develop BGTplanner (Budget Planner) to strategically allocate the privacy
budget for each round of DPFR training, improving overall training performance.
Specifically, we leverage the Gaussian process regression and historical
information to predict the change in recommendation accuracy with a certain
allocated privacy budget. Additionally, Contextual Multi-Armed Bandit (CMAB) is
harnessed to make privacy budget allocation decisions by reconciling the
current improvement and long-term privacy constraints. Our extensive
experimental results on real datasets demonstrate that \emph{BGTplanner}
achieves an average improvement of 6.76\% in training performance compared to
state-of-the-art baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.02868v1">A Novel Compact LLM Framework for Local, High-Privacy EHR Data
  Applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-12-03T22:06:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yixiang Qu, Yifan Dai, Shilin Yu, Pradham Tanikella, Travis Schrank, Trevor Hackman, Didong Li, Di Wu</p>
    <p><b>Summary:</b> Large Language Models (LLMs) have shown impressive capabilities in natural
language processing, yet their use in sensitive domains like healthcare,
particularly with Electronic Health Records (EHR), faces significant challenges
due to privacy concerns and limited computational resources. This paper
presents a compact LLM framework designed for local deployment in settings with
strict privacy requirements and limited access to high-performance GPUs. We
introduce a novel preprocessing technique that uses information extraction
methods, e.g., regular expressions, to filter and emphasize critical
information in clinical notes, enhancing the performance of smaller LLMs on EHR
data. Our framework is evaluated using zero-shot and few-shot learning
paradigms on both private and publicly available (MIMIC-IV) datasets, and we
also compare its performance with fine-tuned LLMs on the MIMIC-IV dataset. The
results demonstrate that our preprocessing approach significantly boosts the
prediction accuracy of smaller LLMs, making them suitable for high-privacy,
resource-constrained applications. This study offers valuable insights into
optimizing LLM performance for sensitive, data-intensive tasks while addressing
computational and privacy limitations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.02578v1">Private Linear Regression with Differential Privacy and PAC Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-12-03T17:04:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hillary Yang</p>
    <p><b>Summary:</b> Linear regression is a fundamental tool for statistical analysis, which has
motivated the development of linear regression methods that satisfy provable
privacy guarantees so that the learned model reveals little about any one data
point used to construct it. Most existing privacy-preserving linear regression
methods rely on the well-established framework of differential privacy, while
the newly proposed PAC Privacy has not yet been explored in this context. In
this paper, we systematically compare linear regression models trained with
differential privacy and PAC privacy across three real-world datasets,
observing several key findings that impact the performance of
privacy-preserving linear regression.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.02538v2">On Privacy, Security, and Trustworthiness in Distributed Wireless Large
  AI Models (WLAM)</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">  
  <p><b>Published on:</b> 2024-12-03T16:32:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhaohui Yang, Wei Xu, Le Liang, Yuanhao Cui, Zhijin Qin, Merouane Debbah</p>
    <p><b>Summary:</b> Combining wireless communication with large artificial intelligence (AI)
models can open up a myriad of novel application scenarios. In sixth generation
(6G) networks, ubiquitous communication and computing resources allow large AI
models to serve democratic large AI models-related services to enable real-time
applications like autonomous vehicles, smart cities, and Internet of Things
(IoT) ecosystems. However, the security considerations and sustainable
communication resources limit the deployment of large AI models over
distributed wireless networks. This paper provides a comprehensive overview of
privacy, security, and trustworthy for distributed wireless large AI model
(WLAM). In particular, a detailed privacy and security are analysis for
distributed WLAM is fist revealed. The classifications and theoretical findings
about privacy and security in distributed WLAM are discussed. Then the
trustworthy and ethics for implementing distributed WLAM are described.
Finally, the comprehensive applications of distributed WLAM are presented in
the context of electromagnetic signal processing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.02340v1">Federated Analytics in Practice: Engineering for Privacy, Scalability
  and Practicality</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-12-03T10:03:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Harish Srinivas, Graham Cormode, Mehrdad Honarkhah, Samuel Lurye, Jonathan Hehir, Lunwen He, George Hong, Ahmed Magdy, Dzmitry Huba, Kaikai Wang, Shen Guo, Shoubhik Bhattacharya</p>
    <p><b>Summary:</b> Cross-device Federated Analytics (FA) is a distributed computation paradigm
designed to answer analytics queries about and derive insights from data held
locally on users' devices. On-device computations combined with other privacy
and security measures ensure that only minimal data is transmitted off-device,
achieving a high standard of data protection. Despite FA's broad relevance, the
applicability of existing FA systems is limited by compromised accuracy; lack
of flexibility for data analytics; and an inability to scale effectively. In
this paper, we describe our approach to combine privacy, scalability, and
practicality to build and deploy a system that overcomes these limitations. Our
FA system leverages trusted execution environments (TEEs) and optimizes the use
of on-device computing resources to facilitate federated data processing across
large fleets of devices, while ensuring robust, defensible, and verifiable
privacy safeguards. We focus on federated analytics (statistics and
monitoring), in contrast to systems for federated learning (ML workloads), and
we flag the key differences.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.02130v1">A privacy-preserving distributed credible evidence fusion algorithm for
  collective decision-making</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-12-03T03:36:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chaoxiong Ma, Yan Liang, Xinyu Yang, Han Wu, Huixia Zhang</p>
    <p><b>Summary:</b> The theory of evidence reasoning has been applied to collective
decision-making in recent years. However, existing distributed evidence fusion
methods lead to participants' preference leakage and fusion failures as they
directly exchange raw evidence and do not assess evidence credibility like
centralized credible evidence fusion (CCEF) does. To do so, a
privacy-preserving distributed credible evidence fusion method with three-level
consensus (PCEF) is proposed in this paper. In evidence difference measure
(EDM) neighbor consensus, an evidence-free equivalent expression of EDM among
neighbored agents is derived with the shared dot product protocol for pignistic
probability and the identical judgment of two events with maximal subjective
probabilities, so that evidence privacy is guaranteed due to such irreversible
evidence transformation. In EDM network consensus, the non-neighbored EDMs are
inferred and neighbored EDMs reach uniformity via interaction between linear
average consensus (LAC) and low-rank matrix completion with rank adaptation to
guarantee EDM consensus convergence and no solution of inferring raw evidence
in numerical iteration style. In fusion network consensus, a privacy-preserving
LAC with a self-cancelling differential privacy term is proposed, where each
agent adds its randomness to the sharing content and step-by-step cancels such
randomness in consensus iterations. Besides, the sufficient condition of the
convergence to the CCEF is explored, and it is proven that raw evidence is
impossibly inferred in such an iterative consensus. The simulations show that
PCEF is close to CCEF both in credibility and fusion results and obtains higher
decision accuracy with less time-comsuming than existing methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.01756v1">Adversarial Sample-Based Approach for Tighter Privacy Auditing in Final
  Model-Only Scenarios</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-12-02T17:52:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sangyeon Yoon, Wonje Jeung, Albert No</p>
    <p><b>Summary:</b> Auditing Differentially Private Stochastic Gradient Descent (DP-SGD) in the
final model setting is challenging and often results in empirical lower bounds
that are significantly looser than theoretical privacy guarantees. We introduce
a novel auditing method that achieves tighter empirical lower bounds without
additional assumptions by crafting worst-case adversarial samples through
loss-based input-space auditing. Our approach surpasses traditional
canary-based heuristics and is effective in both white-box and black-box
scenarios. Specifically, with a theoretical privacy budget of $\varepsilon =
10.0$, our method achieves empirical lower bounds of $6.68$ in white-box
settings and $4.51$ in black-box settings, compared to the baseline of $4.11$
for MNIST. Moreover, we demonstrate that significant privacy auditing results
can be achieved using in-distribution (ID) samples as canaries, obtaining an
empirical lower bound of $4.33$ where traditional methods produce near-zero
leakage detection. Our work offers a practical framework for reliable and
accurate privacy auditing in differentially private machine learning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.01671v2">Verified Foundations for Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-12-02T16:19:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Markus de Medeiros, Muhammad Naveed, Tancrede Lepoint, Temesghen Kahsai, Tristan Ravitch, Stefan Zetzsche, Anjali Joshi, Joseph Tassarotti, Aws Albarghouthi, Jean-Baptiste Tristan</p>
    <p><b>Summary:</b> Differential privacy (DP) has become the gold standard for privacy-preserving
data analysis, but implementing it correctly has proven challenging. Prior work
has focused on verifying DP at a high level, assuming the foundations are
correct and a perfect source of randomness is available. However, the
underlying theory of differential privacy can be very complex and subtle. Flaws
in basic mechanisms and random number generation have been a critical source of
vulnerabilities in real-world DP systems.
  In this paper, we present SampCert, the first comprehensive, mechanized
foundation for differential privacy. SampCert is written in Lean with over
12,000 lines of proof. It offers a generic and extensible notion of DP, a
framework for constructing and composing DP mechanisms, and formally verified
implementations of Laplace and Gaussian sampling algorithms. SampCert provides
(1) a mechanized foundation for developing the next generation of
differentially private algorithms, and (2) mechanically verified primitives
that can be deployed in production systems. Indeed, SampCert's verified
algorithms power the DP offerings of Amazon Web Services (AWS), demonstrating
its real-world impact.
  SampCert's key innovations include: (1) A generic DP foundation that can be
instantiated for various DP definitions (e.g., pure, concentrated, R\'enyi DP);
(2) formally verified discrete Laplace and Gaussian sampling algorithms that
avoid the pitfalls of floating-point implementations; and (3) a simple
probability monad and novel proof techniques that streamline the formalization.
To enable proving complex correctness properties of DP and random number
generation, SampCert makes heavy use of Lean's extensive Mathlib library,
leveraging theorems in Fourier analysis, measure and probability theory, number
theory, and topology.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.01650v2">Privacy-Preserving Federated Learning via Homomorphic Adversarial
  Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-12-02T15:59:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenhan Dong, Chao Lin, Xinlei He, Xinyi Huang, Shengmin Xu</p>
    <p><b>Summary:</b> Privacy-preserving federated learning (PPFL) aims to train a global model for
multiple clients while maintaining their data privacy. However, current PPFL
protocols exhibit one or more of the following insufficiencies: considerable
degradation in accuracy, the requirement for sharing keys, and cooperation
during the key generation or decryption processes. As a mitigation, we develop
the first protocol that utilizes neural networks to implement PPFL, as well as
incorporating an Aggregatable Hybrid Encryption scheme tailored to the needs of
PPFL. We name these networks as Homomorphic Adversarial Networks (HANs) which
demonstrate that neural networks are capable of performing tasks similar to
multi-key homomorphic encryption (MK-HE) while solving the problems of key
distribution and collaborative decryption. Our experiments show that HANs are
robust against privacy attacks. Compared with non-private federated learning,
experiments conducted on multiple datasets demonstrate that HANs exhibit a
negligible accuracy loss (at most 1.35%). Compared to traditional MK-HE
schemes, HANs increase encryption aggregation speed by 6,075 times while
incurring a 29.2 times increase in communication overhead.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.01541v1">Effectiveness of L2 Regularization in Privacy-Preserving Machine
  Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-12-02T14:31:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nikolaos Chandrinos, Iliana Loi, Panagiotis Zachos, Ioannis Symeonidis, Aristotelis Spiliotis, Maria Panou, Konstantinos Moustakas</p>
    <p><b>Summary:</b> Artificial intelligence, machine learning, and deep learning as a service
have become the status quo for many industries, leading to the widespread
deployment of models that handle sensitive data. Well-performing models, the
industry seeks, usually rely on a large volume of training data. However, the
use of such data raises serious privacy concerns due to the potential risks of
leaks of highly sensitive information. One prominent threat is the Membership
Inference Attack, where adversaries attempt to deduce whether a specific data
point was used in a model's training process. An adversary's ability to
determine an individual's presence represents a significant privacy threat,
especially when related to a group of users sharing sensitive information.
Hence, well-designed privacy-preserving machine learning solutions are
critically needed in the industry. In this work, we compare the effectiveness
of L2 regularization and differential privacy in mitigating Membership
Inference Attack risks. Even though regularization techniques like L2
regularization are commonly employed to reduce overfitting, a condition that
enhances the effectiveness of Membership Inference Attacks, their impact on
mitigating these attacks has not been systematically explored.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.01141v1">Lossless and Privacy-Preserving Graph Convolution Network for Federated
  Item Recommendation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2024-12-02T05:31:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guowei Wu, Weike Pan, Qiang Yang, Zhong Ming</p>
    <p><b>Summary:</b> Graph neural network (GNN) has emerged as a state-of-the-art solution for
item recommendation. However, existing GNN-based recommendation methods rely on
a centralized storage of fragmented user-item interaction sub-graphs and
training on an aggregated global graph, which will lead to privacy concerns. As
a response, some recent works develop GNN-based federated recommendation
methods by exploiting decentralized and fragmented user-item sub-graphs in
order to preserve user privacy. However, due to privacy constraints, the graph
convolution process in existing federated recommendation methods is incomplete
compared with the centralized counterpart, causing a degradation of the
recommendation performance. In this paper, we propose a novel lossless and
privacy-preserving graph convolution network (LP-GCN), which fully completes
the graph convolution process with decentralized user-item interaction
sub-graphs while ensuring privacy. It is worth mentioning that its performance
is equivalent to that of the non-federated (i.e., centralized) counterpart.
Moreover, we validate its effectiveness through both theoretical analysis and
empirical studies. Extensive experiments on three real-world datasets show that
our LP-GCN outperforms the existing federated recommendation methods. The code
will be publicly available once the paper is accepted.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.01079v1">Federated Motor Imagery Classification for Privacy-Preserving
  Brain-Computer Interfaces</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-12-02T03:35:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tianwang Jia, Lubin Meng, Siyang Li, Jiajing Liu, Dongrui Wu</p>
    <p><b>Summary:</b> Training an accurate classifier for EEG-based brain-computer interface (BCI)
requires EEG data from a large number of users, whereas protecting their data
privacy is a critical consideration. Federated learning (FL) is a promising
solution to this challenge. This paper proposes Federated classification with
local Batch-specific batch normalization and Sharpness-aware minimization
(FedBS) for privacy protection in EEG-based motor imagery (MI) classification.
FedBS utilizes local batch-specific batch normalization to reduce data
discrepancies among different clients, and sharpness-aware minimization
optimizer in local training to improve model generalization. Experiments on
three public MI datasets using three popular deep learning models demonstrated
that FedBS outperformed six state-of-the-art FL approaches. Remarkably, it also
outperformed centralized training, which does not consider privacy protection
at all. In summary, FedBS protects user EEG data privacy, enabling multiple BCI
users to participate in large-scale machine learning model training, which in
turn improves the BCI decoding accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.01072v1">When Fine-Tuning LLMs Meets Data Privacy: An Empirical Study of
  Federated Learning in LLM-Based Program Repair</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2024-12-02T03:18:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenqiang Luo, Jacky Wai Keung, Boyang Yang, He Ye, Claire Le Goues, Tegawende F. Bissyande, Haoye Tian, Bach Le</p>
    <p><b>Summary:</b> Software systems have been evolving rapidly and inevitably introducing bugs
at an increasing rate, leading to significant losses in resources consumed by
software maintenance. Recently, large language models (LLMs) have demonstrated
remarkable potential in enhancing software development and maintenance
practices, particularly in automated program repair (APR) with improved
accuracy and efficiency of bug fixing. However, LLM-based APR heavily relies on
high-quality code repositories. A larger portion of existing code repositories
are for private use and proprietary assets from various industries, reflecting
more diversity and nuances in the data since real-world industries often have
more extensive software development practices, which cannot be covered by
merely public datasets. Therefore, utilizing private datasets shows significant
potential in enhancing software development and maintenance. However, obtaining
such data from various industries is hindered by data privacy concerns, as
companies are reluctant to share their codebases. To address the gap, we
investigate the use of federated learning as a privacy-preserving approach that
enables private entities to fine-tune LLMs on proprietary and decentralized
data, facilitating the collaboration between clients to fully utilize their
data to help enhance software development and maintenance. Our evaluation
reveals that federated fine-tuning can effectively enhance program repair
capabilities. Notably, the impact of heterogeneous code on LLM fine-tuning is
negligible, indicating that real-world industries can benefit from
collaborative development regardless of diverse data distributions.
Furthermore, each type of federated algorithm exhibits unique strengths across
different LLMs, suggesting that fine-tuning for program repair can be enhanced
by tailoring the optimization process to specific characteristics of different
LLMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.01056v1">Classifying Simulated Gait Impairments using Privacy-preserving
  Explainable Artificial Intelligence and Mobile Phone Videos</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> 
  <p><b>Published on:</b> 2024-12-02T02:35:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lauhitya Reddy, Ketan Anand, Shoibolina Kaushik, Corey Rodrigo, J. Lucas McKay, Trisha M. Kesar, Hyeokhyen Kwon</p>
    <p><b>Summary:</b> Accurate diagnosis of gait impairments is often hindered by subjective or
costly assessment methods, with current solutions requiring either expensive
multi-camera equipment or relying on subjective clinical observation. There is
a critical need for accessible, objective tools that can aid in gait assessment
while preserving patient privacy. In this work, we present a mobile
phone-based, privacy-preserving artificial intelligence (AI) system for
classifying gait impairments and introduce a novel dataset of 743 videos
capturing seven distinct gait patterns. The dataset consists of frontal and
sagittal views of trained subjects simulating normal gait and six types of
pathological gait (circumduction, Trendelenburg, antalgic, crouch,
Parkinsonian, and vaulting), recorded using standard mobile phone cameras. Our
system achieved 86.5% accuracy using combined frontal and sagittal views, with
sagittal views generally outperforming frontal views except for specific gait
patterns like Circumduction. Model feature importance analysis revealed that
frequency-domain features and entropy measures were critical for classifcation
performance, specifically lower limb keypoints proved most important for
classification, aligning with clinical understanding of gait assessment. These
findings demonstrate that mobile phone-based systems can effectively classify
diverse gait patterns while preserving privacy through on-device processing.
The high accuracy achieved using simulated gait data suggests their potential
for rapid prototyping of gait analysis systems, though clinical validation with
patient data remains necessary. This work represents a significant step toward
accessible, objective gait assessment tools for clinical, community, and
tele-rehabilitation settings</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.00898v1">Preserving Privacy in Software Composition Analysis: A Study of
  Technical Solutions and Enhancements</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-12-01T17:17:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Huaijin Wang, Zhibo Liu, Yanbo Dai, Shuai Wang, Qiyi Tang, Sen Nie, Shi Wu</p>
    <p><b>Summary:</b> Software composition analysis (SCA) denotes the process of identifying
open-source software components in an input software application. SCA has been
extensively developed and adopted by academia and industry. However, we notice
that the modern SCA techniques in industry scenarios still need to be improved
due to privacy concerns. Overall, SCA requires the users to upload their
applications' source code to a remote SCA server, which then inspects the
applications and reports the component usage to users. This process is
privacy-sensitive since the applications may contain sensitive information,
such as proprietary source code, algorithms, trade secrets, and user data.
  Privacy concerns have prevented the SCA technology from being used in
real-world scenarios. Therefore, academia and the industry demand
privacy-preserving SCA solutions. For the first time, we analyze the privacy
requirements of SCA and provide a landscape depicting possible technical
solutions with varying privacy gains and overheads. In particular, given that
de facto SCA frameworks are primarily driven by code similarity-based
techniques, we explore combining several privacy-preserving protocols to
encapsulate the similarity-based SCA framework. Among all viable solutions, we
find that multi-party computation (MPC) offers the strongest privacy guarantee
and plausible accuracy; it, however, incurs high overhead (184 times). We
optimize the MPC-based SCA framework by reducing the amount of crypto protocol
transactions using program analysis techniques. The evaluation results show
that our proposed optimizations can reduce the MPC-based SCA overhead to only
8.5% without sacrificing SCA's privacy guarantee or accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.00774v1">Post-Vaccination COVID-19 Data Analysis: Privacy and Ethics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-12-01T11:41:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sankha Das, Amit Dua</p>
    <p><b>Summary:</b> The COVID-19 pandemic has severely affected the world in terms of health,
economy and peace. Fortunately, the countries are trying to overcome the
situation by actively carrying out vaccinations. However, like any other
massive operation involving humans such as human resource management,
elections, surveys, etc., the vaccination process raises several questions
about citizen privacy and misuse of personal data. In most of the countries,
few attempts have been made to verify the vaccination statistics as reported by
the health centers. These issues collectively require the solutions of
anonymity of citizens' personal information, immutability of vaccination data
and easy yet restricted access by adversarial bodies such as the government for
the verification and analysis of the data. This paper introduces a
blockchain-based application to simulate and monitor the vaccination process.
The structure of data model used in the proposed system is based on the IEEE
Standard for Data Format for Blockchain Systems 2418.2TM-2020. The proposed
system enables authorized stakeholders to share and access relevant information
for vaccination process chain while preserving citizen privacy and
accountability of the system. It is implemented on the Ethereum blockchain and
uses a Python API for the simulation and validation of each step of the
vaccination process.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.00687v1">Towards Privacy-Preserving Medical Imaging: Federated Learning with
  Differential Privacy and Secure Aggregation Using a Modified ResNet
  Architecture</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-12-01T05:52:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohamad Haj Fares, Ahmed Mohamed Saad Emam Saad</p>
    <p><b>Summary:</b> With increasing concerns over privacy in healthcare, especially for sensitive
medical data, this research introduces a federated learning framework that
combines local differential privacy and secure aggregation using Secure
Multi-Party Computation for medical image classification. Further, we propose
DPResNet, a modified ResNet architecture optimized for differential privacy.
Leveraging the BloodMNIST benchmark dataset, we simulate a realistic
data-sharing environment across different hospitals, addressing the distinct
privacy challenges posed by federated healthcare data. Experimental results
indicate that our privacy-preserving federated model achieves accuracy levels
close to non-private models, surpassing traditional approaches while
maintaining strict data confidentiality. By enhancing the privacy, efficiency,
and reliability of healthcare data management, our approach offers substantial
benefits to patients, healthcare providers, and the broader healthcare
ecosystem.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.00620v1">TraCS: Trajectory Collection in Continuous Space under Local
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-12-01T00:07:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ye Zheng, Yidan Hu</p>
    <p><b>Summary:</b> Trajectory collection is fundamental for location-based services but often
involves sensitive information, such as a user's daily routine, raising privacy
concerns. Local differential privacy (LDP) provides provable privacy guarantees
for users, even when the data collector is untrusted. Existing trajectory
collection methods ensure LDP only for discrete location spaces, where the
number of locations affects their privacy guarantees and trajectory utility.
Moreover, the location space is often naturally continuous, such as in flying
and sailing trajectories, making these methods unsuitable. This paper proposes
two trajectory collection methods that ensure LDP for continuous spaces:
TraCS-D, which perturbs the direction and distance of locations, and TraCS-C,
which perturbs the Cartesian coordinates of locations. Both methods are
theoretically and experimentally analyzed for trajectory utility. TraCS can
also be applied to discrete spaces by rounding perturbed locations to the
nearest discrete points. It is independent of the number of locations and has
only $\Theta(1)$ time complexity in each perturbation generation. Evaluation
results on discrete location spaces validate this advantage and show that TraCS
outperforms state-of-the-art methods with improved trajectory utility,
especially for large privacy parameters.</p>
  </details>
</div>



<h2>2024-11</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.00367v1">Joint Optimization of Communication Enhancement and Location Privacy
  Protection in RIS-Assisted Underwater Communication System</a></h3>
  
  <p><b>Published on:</b> 2024-11-30T06:08:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ziqi Chen, Jun Du, Chunxiao Jiang, Zhu Han</p>
    <p><b>Summary:</b> As the demand for underwater communication continues to grow, underwater
acoustic RIS (UARIS), as an emerging paradigm in underwater acoustic
communication (UAC), can significantly improve the communication rate of
underwater acoustic systems. However, in open underwater environments, the
location of the source node is highly susceptible to being obtained by
eavesdropping nodes through correlation analysis, leading to the issue of
location privacy in underwater communication systems, which has been overlooked
by many studies. To enhance underwater communication and protect location
privacy, we propose a novel UARIS architecture integrated with an artificial
noise (AN) module. This architecture not only improves communication quality
but also introduces noise to interfere with the eavesdroppers' attempts to
locate the source node. We derive the Cram\'er-Rao Lower Bound (CRLB) for the
localization method deployed by the eavesdroppers and, based on this, model the
UARIS-assisted communication scenario as a multi-objective optimization
problem. This problem optimizes transmission beamforming, reflective precoding,
and noise factors to maximize communication performance and location privacy
protection. To efficiently solve this non-convex optimization problem, we
develop an iterative algorithm based on fractional programming. Simulation
results validate that the proposed system significantly enhances data
transmission rates while effectively maintaining the location privacy of the
source node in UAC systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.00277v2">Facial Expression Recognition with Controlled Privacy Preservation and
  Feature Compensation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-11-29T23:12:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Feng Xu, David Ahmedt-Aristizabal, Lars Petersson, Dadong Wang, Xun Li</p>
    <p><b>Summary:</b> Facial expression recognition (FER) systems raise significant privacy
concerns due to the potential exposure of sensitive identity information. This
paper presents a study on removing identity information while preserving FER
capabilities. Drawing on the observation that low-frequency components
predominantly contain identity information and high-frequency components
capture expression, we propose a novel two-stream framework that applies
privacy enhancement to each component separately. We introduce a controlled
privacy enhancement mechanism to optimize performance and a feature compensator
to enhance task-relevant features without compromising privacy. Furthermore, we
propose a novel privacy-utility trade-off, providing a quantifiable measure of
privacy preservation efficacy in closed-set FER tasks. Extensive experiments on
the benchmark CREMA-D dataset demonstrate that our framework achieves 78.84%
recognition accuracy with a privacy (facial identity) leakage ratio of only
2.01%, highlighting its potential for secure and reliable video-based FER
applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.19678v1">Privacy-Preserving Orthogonal Aggregation for Guaranteeing Gender
  Fairness in Federated Recommendation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-11-29T13:12:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Siqing Zhang, Yuchen Ding, Wei Tang, Wei Sun, Yong Liao, Peng Yuan Zhou</p>
    <p><b>Summary:</b> Under stringent privacy constraints, whether federated recommendation systems
can achieve group fairness remains an inadequately explored question. Taking
gender fairness as a representative issue, we identify three phenomena in
federated recommendation systems: performance difference, data imbalance, and
preference disparity. We discover that the state-of-the-art methods only focus
on the first phenomenon. Consequently, their imposition of inappropriate
fairness constraints detrimentally affects the model training. Moreover, due to
insufficient sensitive attribute protection of existing works, we can infer the
gender of all users with 99.90% accuracy even with the addition of maximal
noise. In this work, we propose Privacy-Preserving Orthogonal Aggregation
(PPOA), which employs the secure aggregation scheme and quantization technique,
to prevent the suppression of minority groups by the majority and preserve the
distinct preferences for better group fairness. PPOA can assist different
groups in obtaining their respective model aggregation results through a
designed orthogonal mapping while keeping their attributes private.
Experimental results on three real-world datasets demonstrate that PPOA
enhances recommendation effectiveness for both females and males by up to 8.25%
and 6.36%, respectively, with a maximum overall improvement of 7.30%, and
achieves optimal fairness in most cases. Extensive ablation experiments and
visualizations indicate that PPOA successfully maintains preferences for
different gender groups.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.19498v1">Protecting Multiple Types of Privacy Simultaneously in EEG-based
  Brain-Computer Interfaces</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-11-29T06:33:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lubin Meng, Xue Jiang, Tianwang Jia, Dongrui Wu</p>
    <p><b>Summary:</b> A brain-computer interface (BCI) enables direct communication between the
brain and an external device. Electroencephalogram (EEG) is the preferred input
signal in non-invasive BCIs, due to its convenience and low cost. EEG-based
BCIs have been successfully used in many applications, such as neurological
rehabilitation, text input, games, and so on. However, EEG signals inherently
carry rich personal information, necessitating privacy protection. This paper
demonstrates that multiple types of private information (user identity, gender,
and BCI-experience) can be easily inferred from EEG data, imposing a serious
privacy threat to BCIs. To address this issue, we design perturbations to
convert the original EEG data into privacy-protected EEG data, which conceal
the private information while maintaining the primary BCI task performance.
Experimental results demonstrated that the privacy-protected EEG data can
significantly reduce the classification accuracy of user identity, gender and
BCI-experience, but almost do not affect at all the classification accuracy of
the primary BCI task, enabling user privacy protection in EEG-based BCIs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.19142v1">GDPR-Relevant Privacy Concerns in Mobile Apps Research: A Systematic
  Literature Review</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2024-11-28T13:42:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Orlando Amaral Cejas, Nicolas Sannier, Sallam Abualhaija, Marcello Ceci, Domenico Bianculli</p>
    <p><b>Summary:</b> The General Data Protection Regulation (GDPR) is the benchmark in the
European Union (EU) for privacy and data protection standards. Substantial
research has been conducted in the requirements engineering (RE) literature
investigating the elicitation, representation, and verification of privacy
requirements in GDPR. Software systems including mobile apps must comply with
the GDPR. With the growing pervasiveness of mobile apps and their increasing
demand for personal data, privacy concerns have acquired further interest
within the software engineering (SE) community at large. Despite the extensive
literature on GDPR-relevant privacy concerns in mobile apps, there is no
secondary study that describes, analyzes, and categorizes the current focus.
Research gaps and persistent challenges are thus left unnoticed. In this
article, we aim to systematically review existing primary studies highlighting
various GDPR concepts and how these concepts are addressed in mobile apps
research. The objective is to reconcile the existing work on GDPR in the RE
literature with the research on GDPR-related privacy concepts in mobile apps in
the SE literature. Our findings show that the current research landscape
reflects a rather shallow understanding of GDPR requirements. Some GDPR
concepts such as data subject rights (i.e., the rights of individuals over
their personal data) are fundamental to GDPR, yet under-explored in the
literature. In this article, we highlight future directions to be pursued by
the SE community for supporting the development of GDPR-compliant mobile apps.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.18746v1">Inference Privacy: Properties and Mechanisms</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2024-11-27T20:47:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fengwei Tian, Ravi Tandon</p>
    <p><b>Summary:</b> Ensuring privacy during inference stage is crucial to prevent malicious third
parties from reconstructing users' private inputs from outputs of public
models. Despite a large body of literature on privacy preserving learning
(which ensures privacy of training data), there is no existing systematic
framework to ensure the privacy of users' data during inference. Motivated by
this problem, we introduce the notion of Inference Privacy (IP), which can
allow a user to interact with a model (for instance, a classifier, or an
AI-assisted chat-bot) while providing a rigorous privacy guarantee for the
users' data at inference. We establish fundamental properties of the IP privacy
notion and also contrast it with the notion of Local Differential Privacy
(LDP). We then present two types of mechanisms for achieving IP: namely, input
perturbations and output perturbations which are customizable by the users and
can allow them to navigate the trade-off between utility and privacy. We also
demonstrate the usefulness of our framework via experiments and highlight the
resulting trade-offs between utility and privacy during inference.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.18380v1">SoK: Privacy Personalised -- Mapping Personal Attributes \& Preferences
  of Privacy Mechanisms for Shoulder Surfing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-11-27T14:27:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Habiba Farzand, Karola Marky, Mohamed Khamis</p>
    <p><b>Summary:</b> Shoulder surfing is a byproduct of smartphone use that enables bystanders to
access personal information (such as text and photos) by making screen
observations without consent. To mitigate this, several protection mechanisms
have been proposed to protect user privacy. However, the mechanisms that users
prefer remain unexplored. This paper explores correlations between personal
attributes and properties of shoulder surfing protection mechanisms. For this,
we first conducted a structured literature review and identified ten protection
mechanism categories against content-based shoulder surfing. We then surveyed
N=192 users and explored correlations between personal attributes and
properties of shoulder surfing protection mechanisms. Our results show that
users agreed that the presented mechanisms assisted in protecting their
privacy, but they preferred non-digital alternatives. Among the mechanisms,
participants mainly preferred an icon overlay mechanism followed by a tangible
mechanism. We also found that users who prioritized out-of-device privacy and a
high tendency to interact with technology favoured the personalisation of
protection mechanisms. On the contrary, age and smartphone OS did not impact
users' preference for perceived usefulness and personalisation of mechanisms.
Based on the results, we present key takeaways to support the design of future
protection mechanisms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.18269v1">Hidden Data Privacy Breaches in Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-11-27T12:04:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xueluan Gong, Yuji Wang, Shuaike Li, Mengyuan Sun, Songze Li, Qian Wang, Kwok-Yan Lam, Chen Chen</p>
    <p><b>Summary:</b> Federated Learning (FL) emerged as a paradigm for conducting machine learning
across broad and decentralized datasets, promising enhanced privacy by
obviating the need for direct data sharing. However, recent studies show that
attackers can steal private data through model manipulation or gradient
analysis. Existing attacks are constrained by low theft quantity or
low-resolution data, and they are often detected through anomaly monitoring in
gradients or weights. In this paper, we propose a novel data-reconstruction
attack leveraging malicious code injection, supported by two key techniques,
i.e., distinctive and sparse encoding design and block partitioning. Unlike
conventional methods that require detectable changes to the model, our method
stealthily embeds a hidden model using parameter sharing to systematically
extract sensitive data. The Fibonacci-based index design ensures efficient,
structured retrieval of memorized data, while the block partitioning method
enhances our method's capability to handle high-resolution images by dividing
them into smaller, manageable units. Extensive experiments on 4 datasets
confirmed that our method is superior to the five state-of-the-art
data-reconstruction attacks under the five respective detection methods. Our
method can handle large-scale and high-resolution data without being detected
or mitigated by state-of-the-art data reconstruction defense methods. In
contrast to baselines, our method can be directly applied to both FedAVG and
FedSGD scenarios, underscoring the need for developers to devise new defenses
against such vulnerabilities. We will open-source our code upon acceptance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.18653v1">PRSI: Privacy-Preserving Recommendation Model Based on Vector Splitting
  and Interactive Protocols</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-11-27T05:14:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaokai Cao, Wenjin Mo, Zhenyu He, Changdong Wang</p>
    <p><b>Summary:</b> With the development of the internet, recommending interesting products to
users has become a highly valuable research topic for businesses.
Recommendation systems play a crucial role in addressing this issue. To prevent
the leakage of each user's (client's) private data, Federated Recommendation
Systems (FedRec) have been proposed and widely used. However, extensive
research has shown that FedRec suffers from security issues such as data
privacy leakage, and it is challenging to train effective models with FedRec
when each client only holds interaction information for a single user. To
address these two problems, this paper proposes a new privacy-preserving
recommendation system (PRSI), which includes a preprocessing module and two
main phases. The preprocessing module employs split vectors and fake
interaction items to protect clients' interaction information and
recommendation results. The two main phases are: (1) the collection of
interaction information and (2) the sending of recommendation results. In the
interaction information collection phase, each client uses the preprocessing
module and random communication methods (according to the designed interactive
protocol) to protect their ID information and IP addresses. In the
recommendation results sending phase, the central server uses the preprocessing
module and triplets to distribute recommendation results to each client under
secure conditions, following the designed interactive protocol. Finally, we
conducted multiple sets of experiments to verify the security, accuracy, and
communication cost of the proposed method.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.18027v1">Privacy-preserving Robotic-based Multi-factor Authentication Scheme for
  Secure Automated Delivery System</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-11-27T03:48:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yang Yang, Aryan Mohammadi Pasikhani, Prosanta Gope, Biplab Sikdar</p>
    <p><b>Summary:</b> Package delivery is a critical aspect of various industries, but it often
incurs high financial costs and inefficiencies when relying solely on human
resources. The last-mile transport problem, in particular, contributes
significantly to the expenditure of human resources in major companies.
Robot-based delivery systems have emerged as a potential solution for last-mile
delivery to address this challenge. However, robotic delivery systems still
face security and privacy issues, like impersonation, replay, man-in-the-middle
attacks (MITM), unlinkability, and identity theft. In this context, we propose
a privacy-preserving multi-factor authentication scheme specifically designed
for robot delivery systems. Additionally, AI-assisted robotic delivery systems
are susceptible to machine learning-based attacks (e.g. FGSM, PGD, etc.). We
introduce the \emph{first} transformer-based audio-visual fusion defender to
tackle this issue, which effectively provides resilience against adversarial
samples. Furthermore, we provide a rigorous formal analysis of the proposed
protocol and also analyse the protocol security using a popular symbolic proof
tool called ProVerif and Scyther. Finally, we present a real-world
implementation of the proposed robotic system with the computation cost and
energy consumption analysis. Code and pre-trained models are available at:
https://drive.google.com/drive/folders/18B2YbxtV0Pyj5RSFX-ZzCGtFOyorBHil</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.17589v1">Privacy-Preserving Behaviour of Chatbot Users: Steering Through Trust
  Dynamics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-11-26T16:55:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Julia Ive, Vishal Yadav, Mariia Ignashina, Matthew Rand, Paulina Bondaronek</p>
    <p><b>Summary:</b> Introduction: The use of chatbots is becoming increasingly important across
various aspects of daily life. However, the privacy concerns associated with
these communications have not yet been thoroughly addressed. The aim of this
study was to investigate user awareness of privacy risks in chatbot
interactions, the privacy-preserving behaviours users practice, and how these
behaviours relate to their awareness of privacy threats, even when no immediate
threat is perceived. Methods: We developed a novel "privacy-safe" setup to
analyse user behaviour under the guarantees of anonymization and non-sharing.
We employed a mixed-methods approach, starting with the quantification of
broader trends by coding responses, followed by conducting a qualitative
content analysis to gain deeper insights. Results: Overall, there was a
substantial lack of understanding among users about how chatbot providers
handle data (27% of the participants) and the basics of privacy risks (76% of
the participants). Older users, in particular, expressed fears that chatbot
providers might sell their data. Moreover, even users with privacy knowledge do
not consistently exhibit privacy-preserving behaviours when assured of
transparent data processing by chatbots. Notably, under-protective behaviours
were observed among more expert users. Discussion: These findings highlight the
need for a strategic approach to enhance user education on privacy concepts to
ensure informed decision when interacting with chatbot technology. This
includes the development of tools to help users monitor and control the
information they share with chatbots</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.17321v1">A Framework for the Security and Privacy of Biometric System
  Constructions under Defined Computational Assumptions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-11-26T11:10:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sam Grierson, William J Buchanan, Craig Thomson, Baraq Galeb, Chris Eckl</p>
    <p><b>Summary:</b> Biometric systems, while offering convenient authentication, often fall short
in providing rigorous security assurances. A primary reason is the ad-hoc
design of protocols and components, which hinders the establishment of
comprehensive security proofs. This paper introduces a formal framework for
constructing secure and privacy-preserving biometric systems. By leveraging the
principles of universal composability, we enable the modular analysis and
verification of individual system components. This approach allows us to derive
strong security and privacy properties for the entire system, grounded in
well-defined computational assumptions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.17287v1">Privacy Preserving Federated Unsupervised Domain Adaptation with
  Application to Age Prediction from DNA Methylation Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-11-26T10:19:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Cem Ata Baykara, Ali Burak Ünal, Nico Pfeifer, Mete Akgün</p>
    <p><b>Summary:</b> In computational biology, predictive models are widely used to address
complex tasks, but their performance can suffer greatly when applied to data
from different distributions. The current state-of-the-art domain adaptation
method for high-dimensional data aims to mitigate these issues by aligning the
input dependencies between training and test data. However, this approach
requires centralized access to both source and target domain data, raising
concerns about data privacy, especially when the data comes from multiple
sources. In this paper, we introduce a privacy-preserving federated framework
for unsupervised domain adaptation in high-dimensional settings. Our method
employs federated training of Gaussian processes and weighted elastic nets to
effectively address the problem of distribution shift between domains, while
utilizing secure aggregation and randomized encoding to protect the local data
of participating data owners. We evaluate our framework on the task of age
prediction using DNA methylation data from multiple tissues, demonstrating that
our approach performs comparably to existing centralized methods while
maintaining data privacy, even in distributed environments where data is spread
across multiple institutions. Our framework is the first privacy-preserving
solution for high-dimensional domain adaptation in federated environments,
offering a promising tool for fields like computational biology and medicine,
where protecting sensitive data is essential.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.17035v1">Achieving Privacy Utility Balance for Multivariate Time Series Data</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-11-26T01:59:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gaurab Hore, Tucker McElroy, Anindya Roy</p>
    <p><b>Summary:</b> Utility-preserving data privatization is of utmost importance for
data-producing agencies. The popular noise-addition privacy mechanism distorts
autocorrelation patterns in time series data, thereby marring utility; in
response, McElroy et al. (2023) introduced all-pass filtering (FLIP) as a
utility-preserving time series data privatization method. Adapting this concept
to multivariate data is more complex, and in this paper we propose a
multivariate all-pass (MAP) filtering method, employing an optimization
algorithm to achieve the best balance between data utility and privacy
protection. To test the effectiveness of our approach, we apply MAP filtering
to both simulated and real data, sourced from the U.S. Census Bureau's
Quarterly Workforce Indicator (QWI) dataset.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.17758v1">PP-LEM: Efficient and Privacy-Preserving Clearance Mechanism for Local
  Energy Markets</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-11-26T00:22:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kamil Erdayandi, Mustafa Asan Mustafa</p>
    <p><b>Summary:</b> In this paper, we propose a novel Privacy-Preserving clearance mechanism for
Local Energy Markets (PP-LEM), designed for computational efficiency and social
welfare. PP-LEM incorporates a novel competitive game-theoretical clearance
mechanism, modelled as a Stackelberg Game. Based on this mechanism, a
privacy-preserving market model is developed using a partially homomorphic
cryptosystem, allowing buyers' reaction function calculations to be executed
over encrypted data without exposing sensitive information of both buyers and
sellers. The comprehensive performance evaluation demonstrates that PP-LEM is
highly effective in delivering an incentive clearance mechanism with
computational efficiency, enabling it to clear the market for 200 users within
the order of seconds while concurrently protecting user privacy. Compared to
the state of the art, PP-LEM achieves improved computational efficiency without
compromising social welfare while still providing user privacy protection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.16516v1">Curator Attack: When Blackbox Differential Privacy Auditing Loses Its
  Power</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-11-25T16:00:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shiming Wang, Liyao Xiang, Bowei Cheng, Zhe Ji, Tianran Sun, Xinbing Wang</p>
    <p><b>Summary:</b> A surge in data-driven applications enhances everyday life but also raises
serious concerns about private information leakage. Hence many privacy auditing
tools are emerging for checking if the data sanitization performed meets the
privacy standard of the data owner. Blackbox auditing for differential privacy
is particularly gaining popularity for its effectiveness and applicability to a
wide range of scenarios. Yet, we identified that blackbox auditing is
essentially flawed with its setting: small probabilities or densities are
ignored due to inaccurate observation. Our argument is based on a solid false
positive analysis from a hypothesis testing perspective, which is missed out by
prior blackbox auditing tools. This oversight greatly reduces the reliability
of these tools, as it allows malicious or incapable data curators to pass the
auditing with an overstated privacy guarantee, posing significant risks to data
owners. We demonstrate the practical existence of such threats in classical
differential privacy mechanisms against four representative blackbox auditors
with experimental validations. Our findings aim to reveal the limitations of
blackbox auditing tools, empower the data owner with the awareness of risks in
using these tools, and encourage the development of more reliable differential
privacy auditing methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.16440v1">AnonyNoise: Anonymizing Event Data with Smart Noise to Outsmart
  Re-Identification and Preserve Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-11-25T14:43:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Katharina Bendig, René Schuster, Nicole Thiemer, Karen Joisten, Didier Stricker</p>
    <p><b>Summary:</b> The increasing capabilities of deep neural networks for re-identification,
combined with the rise in public surveillance in recent years, pose a
substantial threat to individual privacy. Event cameras were initially
considered as a promising solution since their output is sparse and therefore
difficult for humans to interpret. However, recent advances in deep learning
proof that neural networks are able to reconstruct high-quality grayscale
images and re-identify individuals using data from event cameras. In our paper,
we contribute a crucial ethical discussion on data privacy and present the
first event anonymization pipeline to prevent re-identification not only by
humans but also by neural networks. Our method effectively introduces learnable
data-dependent noise to cover personally identifiable information in raw event
data, reducing attackers' re-identification capabilities by up to 60%, while
maintaining substantial information for the performing of downstream tasks.
Moreover, our anonymization generalizes well on unseen data and is robust
against image reconstruction and inversion attacks. Code:
https://github.com/dfki-av/AnonyNoise</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.16437v1">Privacy Protection in Personalized Diffusion Models via Targeted
  Cross-Attention Adversarial Attack</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-11-25T14:39:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xide Xu, Muhammad Atif Butt, Sandesh Kamath, Bogdan Raducanu</p>
    <p><b>Summary:</b> The growing demand for customized visual content has led to the rise of
personalized text-to-image (T2I) diffusion models. Despite their remarkable
potential, they pose significant privacy risk when misused for malicious
purposes. In this paper, we propose a novel and efficient adversarial attack
method, Concept Protection by Selective Attention Manipulation (CoPSAM) which
targets only the cross-attention layers of a T2I diffusion model. For this
purpose, we carefully construct an imperceptible noise to be added to clean
samples to get their adversarial counterparts. This is obtained during the
fine-tuning process by maximizing the discrepancy between the corresponding
cross-attention maps of the user-specific token and the class-specific token,
respectively. Experimental validation on a subset of CelebA-HQ face images
dataset demonstrates that our approach outperforms existing methods. Besides
this, our method presents two important advantages derived from the qualitative
evaluation: (i) we obtain better protection results for lower noise levels than
our competitors; and (ii) we protect the content from unauthorized use thereby
protecting the individual's identity from potential misuse.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.16404v1">A Survey of Blockchain-Based Privacy Applications: An Analysis of
  Consent Management and Self-Sovereign Identity Approaches</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2024-11-25T14:10:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rodrigo Dutra Garcia, Gowri Ramachandran, Kealan Dunnett, Raja Jurdak, Caetano Ranieri, Bhaskar Krishnamachari, Jo Ueyama</p>
    <p><b>Summary:</b> Modern distributed applications in healthcare, supply chain, and the Internet
of Things handle a large amount of data in a diverse application setting with
multiple stakeholders. Such applications leverage advanced artificial
intelligence (AI) and machine learning algorithms to automate business
processes. The proliferation of modern AI technologies increases the data
demand. However, real-world networks often include private and sensitive
information of businesses, users, and other organizations. Emerging
data-protection regulations such as the General Data Protection Regulation
(GDPR) and the California Consumer Privacy Act (CCPA) introduce policies around
collecting, storing, and managing digital data. While Blockchain technology
offers transparency, auditability, and immutability for multi-stakeholder
applications, it lacks inherent support for privacy. Typically, privacy support
is added to a blockchain-based application by incorporating cryptographic
schemes, consent mechanisms, and self-sovereign identity. This article surveys
the literature on blockchain-based privacy-preserving systems and identifies
the tools for protecting privacy. Besides, consent mechanisms and identity
management in the context of blockchain-based systems are also analyzed. The
article concludes by highlighting the list of open challenges and further
research opportunities.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.16380v1">Privacy-Preserving Federated Foundation Model for Generalist Ultrasound
  Artificial Intelligence</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-11-25T13:40:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuncheng Jiang, Chun-Mei Feng, Jinke Ren, Jun Wei, Zixun Zhang, Yiwen Hu, Yunbi Liu, Rui Sun, Xuemei Tang, Juan Du, Xiang Wan, Yong Xu, Bo Du, Xin Gao, Guangyu Wang, Shaohua Zhou, Shuguang Cui, Rick Siow Mong Goh, Yong Liu, Zhen Li</p>
    <p><b>Summary:</b> Ultrasound imaging is widely used in clinical diagnosis due to its
non-invasive nature and real-time capabilities. However, conventional
ultrasound diagnostics face several limitations, including high dependence on
physician expertise and suboptimal image quality, which complicates
interpretation and increases the likelihood of diagnostic errors. Artificial
intelligence (AI) has emerged as a promising solution to enhance clinical
diagnosis, particularly in detecting abnormalities across various biomedical
imaging modalities. Nonetheless, current AI models for ultrasound imaging face
critical challenges. First, these models often require large volumes of labeled
medical data, raising concerns over patient privacy breaches. Second, most
existing models are task-specific, which restricts their broader clinical
utility. To overcome these challenges, we present UltraFedFM, an innovative
privacy-preserving ultrasound foundation model. UltraFedFM is collaboratively
pre-trained using federated learning across 16 distributed medical institutions
in 9 countries, leveraging a dataset of over 1 million ultrasound images
covering 19 organs and 10 ultrasound modalities. This extensive and diverse
data, combined with a secure training framework, enables UltraFedFM to exhibit
strong generalization and diagnostic capabilities. It achieves an average area
under the receiver operating characteristic curve of 0.927 for disease
diagnosis and a dice similarity coefficient of 0.878 for lesion segmentation.
Notably, UltraFedFM surpasses the diagnostic accuracy of mid-level
ultrasonographers and matches the performance of expert-level sonographers in
the joint diagnosis of 8 common systemic diseases. These findings indicate that
UltraFedFM can significantly enhance clinical diagnostics while safeguarding
patient privacy, marking an advancement in AI-driven ultrasound imaging for
future clinical applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.16340v2">Exploring Privacy and Security as Drivers for Environmental
  Sustainability in Cloud-Based Office Solutions (Extended Abstract)</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-11-25T12:36:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jason Kayembe, Iness Ben Guirat, Jan Tobias Muehlberg</p>
    <p><b>Summary:</b> This paper explores the intersection of privacy, cybersecurity, and
environmental impacts, specifically energy consumption and carbon emissions, in
cloud-based office solutions. We hypothesise that solutions that emphasise
privacy and security are typically "greener" than solutions that are financed
through data collection and advertising. To test our hypothesis, we first
investigate how the underlying architectures and business models of these
services, e.g., monetisation through (personalised) advertising, contribute to
the services' environmental impact. We then explore commonly used methodologies
and identify tools that facilitate environmental assessments of software
systems. By combining these tools, we develop an approach to systematically
assess the environmental footprint of the user-side of online services, which
we apply to investigate and compare the influence of service design and
ad-blocking technology on the emissions of common web-mail services. Our
measurements of a limited selection of such services does not yet conclusively
support or falsify our hypothesis regarding primary impacts. However, we are
already able to identify the greener web-mail services on the user-side and
continue the investigation towards conclusive assessment strategies for online
office solutions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.16121v1">DP-CDA: An Algorithm for Enhanced Privacy Preservation in Dataset
  Synthesis Through Randomized Mixing</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-11-25T06:14:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Utsab Saha, Tanvir Muntakim Tonoy, Hafiz Imtiaz</p>
    <p><b>Summary:</b> In recent years, the growth of data across various sectors, including
healthcare, security, finance, and education, has created significant
opportunities for analysis and informed decision-making. However, these
datasets often contain sensitive and personal information, which raises serious
privacy concerns. Protecting individual privacy is crucial, yet many existing
machine learning and data publishing algorithms struggle with high-dimensional
data, facing challenges related to computational efficiency and privacy
preservation. To address these challenges, we introduce an effective data
publishing algorithm \emph{DP-CDA}. Our proposed algorithm generates synthetic
datasets by randomly mixing data in a class-specific manner, and inducing
carefully-tuned randomness to ensure formal privacy guarantees. Our
comprehensive privacy accounting shows that DP-CDA provides a stronger privacy
guarantee compared to existing methods, allowing for better utility while
maintaining strict level of privacy. To evaluate the effectiveness of DP-CDA,
we examine the accuracy of predictive models trained on the synthetic data,
which serves as a measure of dataset utility. Importantly, we identify an
optimal order of mixing that balances privacy guarantee with predictive
accuracy. Our results indicate that synthetic datasets produced using the
DP-CDA can achieve superior utility compared to those generated by traditional
data publishing algorithms, even when subject to the same privacy requirements.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.15948v1">Over-the-Air Federated Adaptive Data Analysis: Preserving Accuracy via
  Opportunistic Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-11-24T18:26:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Amir Hossein Hadavi, Mohammad M. Mojahedian, Mohammad Reza Aref</p>
    <p><b>Summary:</b> Adaptive data analysis (ADA) involves a dynamic interaction between an
analyst and a dataset owner, where the analyst submits queries sequentially,
adapting them based on previous answers. This process can become adversarial,
as the analyst may attempt to overfit by targeting non-generalizable patterns
in the data. To counteract this, the dataset owner introduces randomization
techniques, such as adding noise to the responses. This noise not only helps
prevent overfitting but also enhances data privacy. However, it must be
carefully calibrated to ensure that the statistical reliability of the
responses is not compromised. In this paper, we extend the ADA problem to the
context of distributed datasets. Specifically, we consider a scenario where a
potentially adversarial analyst interacts with multiple distributed responders
through adaptive queries. We assume that the responses are subject to noise
introduced by the channel connecting the responders and the analyst. We
demonstrate how, through a federated mechanism, this noise can be
opportunistically leveraged to enhance the generalizability of ADA, thereby
increasing the number of query-response interactions between the analyst and
the responders. We illustrate that careful tuning of the transmission
amplitude, based on the theoretically achievable bounds, can significantly
impact the number of accurately answerable queries.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.15796v1">Data Lineage Inference: Uncovering Privacy Vulnerabilities of Dataset
  Pruning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-11-24T11:46:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qi Li, Cheng-Long Wang, Yinzhi Cao, Di Wang</p>
    <p><b>Summary:</b> In this work, we systematically explore the data privacy issues of dataset
pruning in machine learning systems. Our findings reveal, for the first time,
that even if data in the redundant set is solely used before model training,
its pruning-phase membership status can still be detected through attacks.
Since this is a fully upstream process before model training, traditional model
output-based privacy inference methods are completely unsuitable. To address
this, we introduce a new task called Data-Centric Membership Inference and
propose the first ever data-centric privacy inference paradigm named Data
Lineage Inference (DaLI). Under this paradigm, four threshold-based attacks are
proposed, named WhoDis, CumDis, ArraDis and SpiDis. We show that even without
access to downstream models, adversaries can accurately identify the redundant
set with only limited prior knowledge. Furthermore, we find that different
pruning methods involve varying levels of privacy leakage, and even the same
pruning method can present different privacy risks at different pruning
fractions. We conducted an in-depth analysis of these phenomena and introduced
a metric called the Brimming score to offer guidance for selecting pruning
methods with privacy protection in mind.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.16737v1">Federated Learning in Chemical Engineering: A Tutorial on a Framework
  for Privacy-Preserving Collaboration Across Distributed Data Sources</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Neural and Evolutionary Computing-5BC0EB">
  <p><b>Published on:</b> 2024-11-23T13:16:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Siddhant Dutta, Iago Leal de Freitas, Pedro Maciel Xavier, Claudio Miceli de Farias, David Esteban Bernal Neira</p>
    <p><b>Summary:</b> Federated Learning (FL) is a decentralized machine learning approach that has
gained attention for its potential to enable collaborative model training
across clients while protecting data privacy, making it an attractive solution
for the chemical industry. This work aims to provide the chemical engineering
community with an accessible introduction to the discipline. Supported by a
hands-on tutorial and a comprehensive collection of examples, it explores the
application of FL in tasks such as manufacturing optimization, multimodal data
integration, and drug discovery while addressing the unique challenges of
protecting proprietary information and managing distributed datasets. The
tutorial was built using key frameworks such as $\texttt{Flower}$ and
$\texttt{TensorFlow Federated}$ and was designed to provide chemical engineers
with the right tools to adopt FL in their specific needs. We compare the
performance of FL against centralized learning across three different datasets
relevant to chemical engineering applications, demonstrating that FL will often
maintain or improve classification performance, particularly for complex and
heterogeneous data. We conclude with an outlook on the open challenges in
federated learning to be tackled and current approaches designed to remediate
and improve this framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.14718v1">GraphTheft: Quantifying Privacy Risks in Graph Prompt Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-11-22T04:10:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiani Zhu, Xi Lin, Yuxin Qi, Qinghua Mao</p>
    <p><b>Summary:</b> Graph Prompt Learning (GPL) represents an innovative approach in graph
representation learning, enabling task-specific adaptations by fine-tuning
prompts without altering the underlying pre-trained model. Despite its growing
prominence, the privacy risks inherent in GPL remain unexplored. In this study,
we provide the first evaluation of privacy leakage in GPL across three attacker
capabilities: black-box attacks when GPL as a service, and scenarios where node
embeddings and prompt representations are accessible to third parties. We
assess GPL's privacy vulnerabilities through Attribute Inference Attacks (AIAs)
and Link Inference Attacks (LIAs), finding that under any capability, attackers
can effectively infer the properties and relationships of sensitive nodes, and
the success rate of inference on some data sets is as high as 98%. Importantly,
while targeted inference attacks on specific prompts (e.g., GPF-plus) maintain
high success rates, our analysis suggests that the prompt-tuning in GPL does
not significantly elevate privacy risks compared to traditional GNNs. To
mitigate these risks, we explored defense mechanisms, identifying that
Laplacian noise perturbation can substantially reduce inference success, though
balancing privacy protection with model performance remains challenging. This
work highlights critical privacy risks in GPL, offering new insights and
foundational directions for future privacy-preserving strategies in graph
learning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.14565v1">Privacy-Preserving Video Anomaly Detection: A Survey</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-11-21T20:29:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jing Liu, Yang Liu, Xiaoguang Zhu</p>
    <p><b>Summary:</b> Video Anomaly Detection (VAD) aims to automatically analyze spatiotemporal
patterns in surveillance videos collected from open spaces to detect anomalous
events that may cause harm without physical contact. However, vision-based
surveillance systems such as closed-circuit television often capture personally
identifiable information. The lack of transparency and interpretability in
video transmission and usage raises public concerns about privacy and ethics,
limiting the real-world application of VAD. Recently, researchers have focused
on privacy concerns in VAD by conducting systematic studies from various
perspectives including data, features, and systems, making Privacy-Preserving
Video Anomaly Detection (P2VAD) a hotspot in the AI community. However, current
research in P2VAD is fragmented, and prior reviews have mostly focused on
methods using RGB sequences, overlooking privacy leakage and appearance bias
considerations. To address this gap, this article systematically reviews the
progress of P2VAD for the first time, defining its scope and providing an
intuitive taxonomy. We outline the basic assumptions, learning frameworks, and
optimization objectives of various approaches, analyzing their strengths,
weaknesses, and potential correlations. Additionally, we provide open access to
research resources such as benchmark datasets and available code. Finally, we
discuss key challenges and future opportunities from the perspectives of AI
development and P2VAD deployment, aiming to guide future work in the field.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.14557v1">Privacy-Preserving Power Flow Analysis via Secure Multi-Party
  Computation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36"> 
  <p><b>Published on:</b> 2024-11-21T20:04:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jonas von der Heyden, Nils Schlüter, Philipp Binfet, Martin Asman, Markus Zdrallek, Tibor Jager, Moritz Schulze Darup</p>
    <p><b>Summary:</b> Smart grids feature a bidirectional flow of electricity and data, enhancing
flexibility, efficiency, and reliability in increasingly volatile energy grids.
However, data from smart meters can reveal sensitive private information.
Consequently, the adoption of smart meters is often restricted via legal means
and hampered by limited user acceptance. Since metering data is beneficial for
fault-free grid operation, power management, and resource allocation, applying
privacy-preserving techniques to smart metering data is an important research
problem. This work addresses this by using secure multi-party computation
(SMPC), allowing multiple parties to jointly evaluate functions of their
private inputs without revealing the latter. Concretely, we show how to perform
power flow analysis on cryptographically hidden prosumer data. More precisely,
we present a tailored solution to the power flow problem building on an SMPC
implementation of Newtons method. We analyze the security of our approach in
the universal composability framework and provide benchmarks for various grid
types, threat models, and solvers. Our results indicate that secure multi-party
computation can be able to alleviate privacy issues in smart grids in certain
applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.12451v1">Empirical Privacy Evaluations of Generative and Predictive Machine
  Learning Models -- A review and challenges for practice</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-11-19T12:19:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Flavio Hafner, Chang Sun</p>
    <p><b>Summary:</b> Synthetic data generators, when trained using privacy-preserving techniques
like differential privacy, promise to produce synthetic data with formal
privacy guarantees, facilitating the sharing of sensitive data. However, it is
crucial to empirically assess the privacy risks associated with the generated
synthetic data before deploying generative technologies. This paper outlines
the key concepts and assumptions underlying empirical privacy evaluation in
machine learning-based generative and predictive models. Then, this paper
explores the practical challenges for privacy evaluations of generative models
for use cases with millions of training records, such as data from statistical
agencies and healthcare providers. Our findings indicate that methods designed
to verify the correct operation of the training algorithm are effective for
large datasets, but they often assume an adversary that is unrealistic in many
scenarios. Based on the findings, we highlight a crucial trade-off between the
computational feasibility of the evaluation and the level of realism of the
assumed threat model. Finally, we conclude with ideas and suggestions for
future research.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.12223v1">Perception of Digital Privacy Protection: An Empirical Study using GDPR
  Framework</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-11-19T04:36:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hamoud Alhazmi, Ahmed Imran, Mohammad Abu Alsheikh</p>
    <p><b>Summary:</b> Perception of privacy is a contested concept, which is also evolving along
with the rapid proliferation and expansion of technological advancements.
Information systems (IS) applications incorporate various sensing
infrastructures, high-speed networks, and computing components that enable
pervasive data collection about people. Any digital privacy breach within such
systems can result in harmful and far-reaching impacts on individuals and
societies. Accordingly, IS organisations have a legal and ethical
responsibility to respect and protect individuals digital privacy rights. This
study investigates people perception of digital privacy protection of
government data using the General Data Protection Regulation (GDPR) framework.
Findings suggest a dichotomy of perception in protecting people privacy rights.
For example, people perceive the right to be informed as the most respected and
protected in Information Technology (IT) systems. On the contrary, the right to
object by granting and with-drawing consent is perceived as the least
protected. Second, the study shows evidence of a social dilemma in people
perception of digital privacy based on their context and culture.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.13598v1">Preserving Expert-Level Privacy in Offline Reinforcement Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-11-18T21:26:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Navodita Sharma, Vishnu Vinod, Abhradeep Thakurta, Alekh Agarwal, Borja Balle, Christoph Dann, Aravindan Raghuveer</p>
    <p><b>Summary:</b> The offline reinforcement learning (RL) problem aims to learn an optimal
policy from historical data collected by one or more behavioural policies
(experts) by interacting with an environment. However, the individual experts
may be privacy-sensitive in that the learnt policy may retain information about
their precise choices. In some domains like personalized retrieval, advertising
and healthcare, the expert choices are considered sensitive data. To provably
protect the privacy of such experts, we propose a novel consensus-based
expert-level differentially private offline RL training approach compatible
with any existing offline RL algorithm. We prove rigorous differential privacy
guarantees, while maintaining strong empirical performance. Unlike existing
work in differentially private RL, we supplement the theory with
proof-of-concept experiments on classic RL environments featuring large
continuous state spaces, demonstrating substantial improvements over a natural
baseline across multiple tasks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.12045v1">Fingerprinting and Tracing Shadows: The Development and Impact of
  Browser Fingerprinting on Digital Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-11-18T20:32:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alexander Lawall</p>
    <p><b>Summary:</b> Browser fingerprinting is a growing technique for identifying and tracking
users online without traditional methods like cookies. This paper gives an
overview by examining the various fingerprinting techniques and analyzes the
entropy and uniqueness of the collected data. The analysis highlights that
browser fingerprinting poses a complex challenge from both technical and
privacy perspectives, as users often have no control over the collection and
use of their data. In addition, it raises significant privacy concerns as users
are often tracked without their knowledge or consent.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.11713v1">FLMarket: Enabling Privacy-preserved Pre-training Data Pricing for
  Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-11-18T16:37:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhenyu Wen, Wanglei Feng, Di Wu, Haozhen Hu, Chang Xu, Bin Qian, Zhen Hong, Cong Wang, Shouling Ji</p>
    <p><b>Summary:</b> Federated Learning (FL), as a mainstream privacy-preserving machine learning
paradigm, offers promising solutions for privacy-critical domains such as
healthcare and finance. Although extensive efforts have been dedicated from
both academia and industry to improve the vanilla FL, little work focuses on
the data pricing mechanism. In contrast to the straightforward in/post-training
pricing techniques, we study a more difficult problem of pre-training pricing
without direct information from the learning process. We propose FLMarket that
integrates a two-stage, auction-based pricing mechanism with a security
protocol to address the utility-privacy conflict. Through comprehensive
experiments, we show that the client selection according to FLMarket can
achieve more than 10% higher accuracy in subsequent FL training compared to
state-of-the-art methods. In addition, it outperforms the in-training baseline
with more than 2% accuracy increase and 3x run-time speedup.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.11521v1">Preempting Text Sanitization Utility in Resource-Constrained
  Privacy-Preserving LLM Interactions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-11-18T12:31:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Robin Carpentier, Benjamin Zi Hao Zhao, Hassan Jameel Asghar, Dali Kaafar</p>
    <p><b>Summary:</b> Individuals have been increasingly interacting with online Large Language
Models (LLMs), both in their work and personal lives. These interactions raise
privacy issues as the LLMs are typically hosted by third-parties who can gather
a variety of sensitive information about users and their companies. Text
Sanitization techniques have been proposed in the literature and can be used to
sanitize user prompts before sending them to the LLM. However, sanitization has
an impact on the downstream task performed by the LLM, and often to such an
extent that it leads to unacceptable results for the user. This is not just a
minor annoyance, with clear monetary consequences as LLM services charge on a
per use basis as well as great amount of computing resources wasted. We propose
an architecture leveraging a Small Language Model (SLM) at the user-side to
help estimate the impact of sanitization on a prompt before it is sent to the
LLM, thus preventing resource losses.
  Our evaluation of this architecture revealed a significant problem with text
sanitization based on Differential Privacy, on which we want to draw the
attention of the community for further investigation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.12766v2">Exploiting the Uncoordinated Privacy Protections of Eye Tracking and VR
  Motion Data for Unauthorized User Identification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-11-17T22:16:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Samantha Aziz, Oleg Komogortsev</p>
    <p><b>Summary:</b> Virtual reality (VR) devices use a variety of sensors to capture a rich body
of user-generated data. This data can be misused by malicious parties to
covertly infer information about the user. Privacy-enhancing techniques that
seek to reduce the amount of personally identifying information in sensor data
are typically developed for a subset of data streams that are available on the
platform, without consideration for the auxiliary information that may be
readily available from other sensors. In this paper, we evaluate whether body
motion data can be used to circumvent the privacy protections applied to eye
tracking data to enable user identification on a VR platform, and vice versa.
We empirically show that eye tracking, headset tracking, and hand tracking data
are not only informative for inferring user identity on their own, but contain
complementary information that can increase the rate of successful user
identification. Most importantly, we demonstrate that applying privacy
protections to only a subset of the data available in VR can create an
opportunity for an adversary to bypass those privacy protections by using other
unprotected data streams that are available on the platform, performing a user
identification attack as accurately as though a privacy mechanism was never
applied. These results highlight a new privacy consideration at the
intersection between eye tracking and VR, and emphasizes the need for
privacy-enhancing techniques that address multiple technologies
comprehensively.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.11044v1">Efficient Federated Unlearning with Adaptive Differential Privacy
  Preservation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-11-17T11:45:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yu Jiang, Xindi Tong, Ziyao Liu, Huanyi Ye, Chee Wei Tan, Kwok-Yan Lam</p>
    <p><b>Summary:</b> Federated unlearning (FU) offers a promising solution to effectively address
the need to erase the impact of specific clients' data on the global model in
federated learning (FL), thereby granting individuals the ``Right to be
Forgotten". The most straightforward approach to achieve unlearning is to train
the model from scratch, excluding clients who request data removal, but it is
resource-intensive. Current state-of-the-art FU methods extend traditional FL
frameworks by leveraging stored historical updates, enabling more efficient
unlearning than training from scratch. However, the use of stored updates
introduces significant privacy risks. Adversaries with access to these updates
can potentially reconstruct clients' local data, a well-known vulnerability in
the privacy domain. While privacy-enhanced techniques exist, their applications
to FU scenarios that balance unlearning efficiency with privacy protection
remain underexplored. To address this gap, we propose FedADP, a method designed
to achieve both efficiency and privacy preservation in FU. Our approach
incorporates an adaptive differential privacy (DP) mechanism, carefully
balancing privacy and unlearning performance through a novel budget allocation
strategy tailored for FU. FedADP also employs a dual-layered selection process,
focusing on global models with significant changes and client updates closely
aligned with the global model, reducing storage and communication costs.
Additionally, a novel calibration method is introduced to facilitate effective
unlearning. Extensive experimental results demonstrate that FedADP effectively
manages the trade-off between unlearning efficiency and privacy protection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.10964v1">Exploring Device-Oriented Video Encryption for Hierarchical Privacy
  Protection in AR Content Sharing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-11-17T05:03:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yongquan Hu, Dongsheng Zheng, Kexin Nie, Junyan Zhang, Wen Hu, Aaron Quigley</p>
    <p><b>Summary:</b> Content sharing across multiple Augmented Reality (AR) displays is becoming
commonplace, enhancing team communication and collaboration through devices
like smartphones and AR glasses. However, this practice raises significant
privacy concerns, especially concerning the physical environment visible in AR,
which may include sensitive personal details like facial features and
identifiable information. Our research focuses on protecting privacy within AR
environments, particularly the physical backgrounds visible during content
sharing across three common AR display methods: projection, smartphone, and AR
glasses. We analyze the potential privacy risks associated with each method and
employ a Region Of Interest (ROI) video encryption system to hierarchically
encrypt the physical backdrop based on its safety rating. This study pioneers
the integration of ROI video encryption at the bitstream level within AR
contexts, providing a more efficient solution than traditional pixel-level
encryption by enhancing encryption speed and reducing the required space. Our
adaptive system dynamically adjusts the encryption intensity based on the AR
display method, ensuring tailored privacy protection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.10612v1">Contextualizing Security and Privacy of Software-Defined Vehicles: State
  of the Art and Industry Perspectives</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Operating Systems-04E762">
  <p><b>Published on:</b> 2024-11-15T22:30:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marco De Vincenzi, Mert D. Pesé, Chiara Bodei, Ilaria Matteucci, Richard R. Brooks, Monowar Hasan, Andrea Saracino, Mohammad Hamad, Sebastian Steinhorst</p>
    <p><b>Summary:</b> The growing reliance on software in vehicles has given rise to the concept of
Software-Defined Vehicles (SDVs), fundamentally reshaping the vehicles and the
automotive industry. This survey explores the cybersecurity and privacy
challenges posed by SDVs, which increasingly integrate features like
Over-the-Air (OTA) updates and Vehicle-to-Everything (V2X) communication. While
these advancements enhance vehicle capabilities and flexibility, they also come
with a flip side: increased exposure to security risks including API
vulnerabilities, third-party software risks, and supply-chain threats. The
transition to SDVs also raises significant privacy concerns, with vehicles
collecting vast amounts of sensitive data, such as location and driver
behavior, that could be exploited using inference attacks. This work aims to
provide a detailed overview of security threats, mitigation strategies, and
privacy risks in SDVs, primarily through a literature review, enriched with
insights from a targeted questionnaire with industry experts. Key topics
include defining SDVs, comparing them to Connected Vehicles (CVs) and
Autonomous Vehicles (AVs), discussing the security challenges associated with
OTA updates and the impact of SDV features on data privacy. Our findings
highlight the need for robust security frameworks, standardized communication
protocols, and privacy-preserving techniques to address the issues of SDVs.
This work ultimately emphasizes the importance of a multi-layered defense
strategy,integrating both in-vehicle and cloud-based security solutions, to
safeguard future SDVs and increase user trust.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.10512v1">On the Privacy Risk of In-context Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-11-15T17:11:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haonan Duan, Adam Dziedzic, Mohammad Yaghini, Nicolas Papernot, Franziska Boenisch</p>
    <p><b>Summary:</b> Large language models (LLMs) are excellent few-shot learners. They can
perform a wide variety of tasks purely based on natural language prompts
provided to them. These prompts contain data of a specific downstream task --
often the private dataset of a party, e.g., a company that wants to leverage
the LLM for their purposes. We show that deploying prompted models presents a
significant privacy risk for the data used within the prompt by instantiating a
highly effective membership inference attack. We also observe that the privacy
risk of prompted models exceeds fine-tuned models at the same utility levels.
After identifying the model's sensitivity to their prompts -- in the form of a
significantly higher prediction confidence on the prompted data -- as a cause
for the increased risk, we propose ensembling as a mitigation strategy. By
aggregating over multiple different versions of a prompted model, membership
inference risk can be decreased.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.12756v1">FedCL-Ensemble Learning: A Framework of Federated Continual Learning
  with Ensemble Transfer Learning Enhanced for Alzheimer's MRI Classifications
  while Preserving Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-11-15T13:49:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rishit Kapoor, Jesher Joshua, Muralidharan Vijayarangan, Natarajan B</p>
    <p><b>Summary:</b> This research work introduces a novel approach to the classification of
Alzheimer's disease by using the advanced deep learning techniques combined
with secure data processing methods. This research work primary uses transfer
learning models such as ResNet, ImageNet, and VNet to extract high-level
features from medical image data. Thereafter, these pre-trained models were
fine-tuned for Alzheimer's related subtle patterns such that the model is
capable of robust feature extraction over varying data sources. Further, the
federated learning approaches were incorporated to tackle a few other
challenges related to classification, aimed to provide better prediction
performance and protect data privacy. The proposed model was built using
federated learning without sharing sensitive patient data. This way, the
decentralized model benefits from the large and diversified dataset that it is
trained upon while ensuring confidentiality. The cipher-based encryption
mechanism is added that allows us to secure the transportation of data and
further ensure the privacy and integrity of patient information throughout
training and classification. The results of the experiments not only help to
improve the accuracy of the classification of Alzheimer's but at the same time
provides a framework for secure and collaborative analysis of health care data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.09914v1">mmSpyVR: Exploiting mmWave Radar for Penetrating Obstacles to Uncover
  Privacy Vulnerability of Virtual Reality</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-11-15T03:22:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Luoyu Mei, Ruofeng Liu, Zhimeng Yin, Qingchuan Zhao, Wenchao Jiang, Shuai Wang, Kangjie Lu, Tian He</p>
    <p><b>Summary:</b> Virtual reality (VR), while enhancing user experiences, introduces
significant privacy risks. This paper reveals a novel vulnerability in VR
systems that allows attackers to capture VR privacy through obstacles utilizing
millimeter-wave (mmWave) signals without physical intrusion and virtual
connection with the VR devices. We propose mmSpyVR, a novel attack on VR user's
privacy via mmWave radar. The mmSpyVR framework encompasses two main parts: (i)
A transfer learning-based feature extraction model to achieve VR feature
extraction from mmWave signal. (ii) An attention-based VR privacy spying module
to spy VR privacy information from the extracted feature. The mmSpyVR
demonstrates the capability to extract critical VR privacy from the mmWave
signals that have penetrated through obstacles. We evaluate mmSpyVR through
IRB-approved user studies. Across 22 participants engaged in four experimental
scenes utilizing VR devices from three different manufacturers, our system
achieves an application recognition accuracy of 98.5\% and keystroke
recognition accuracy of 92.6\%. This newly discovered vulnerability has
implications across various domains, such as cybersecurity, privacy protection,
and VR technology development. We also engage with VR manufacturer Meta to
discuss and explore potential mitigation strategies. Data and code are publicly
available for scrutiny and research at https://github.com/luoyumei1-a/mmSpyVR/</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.09523v1">Navigating the Risks: A Survey of Security, Privacy, and Ethics Threats
  in LLM-Based Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-11-14T15:40:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuyou Gan, Yong Yang, Zhe Ma, Ping He, Rui Zeng, Yiming Wang, Qingming Li, Chunyi Zhou, Songze Li, Ting Wang, Yunjun Gao, Yingcai Wu, Shouling Ji</p>
    <p><b>Summary:</b> With the continuous development of large language models (LLMs),
transformer-based models have made groundbreaking advances in numerous natural
language processing (NLP) tasks, leading to the emergence of a series of agents
that use LLMs as their control hub. While LLMs have achieved success in various
tasks, they face numerous security and privacy threats, which become even more
severe in the agent scenarios. To enhance the reliability of LLM-based
applications, a range of research has emerged to assess and mitigate these
risks from different perspectives.
  To help researchers gain a comprehensive understanding of various risks, this
survey collects and analyzes the different threats faced by these agents. To
address the challenges posed by previous taxonomies in handling cross-module
and cross-stage threats, we propose a novel taxonomy framework based on the
sources and impacts. Additionally, we identify six key features of LLM-based
agents, based on which we summarize the current research progress and analyze
their limitations. Subsequently, we select four representative agents as case
studies to analyze the risks they may face in practical use. Finally, based on
the aforementioned analyses, we propose future research directions from the
perspectives of data, methodology, and policy, respectively.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.09287v1">The Communication-Friendly Privacy-Preserving Machine Learning against
  Malicious Adversaries</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-11-14T08:55:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tianpei Lu, Bingsheng Zhang, Lichun Li, Kui Ren</p>
    <p><b>Summary:</b> With the increasing emphasis on privacy regulations, such as GDPR, protecting
individual privacy and ensuring compliance have become critical concerns for
both individuals and organizations. Privacy-preserving machine learning (PPML)
is an innovative approach that allows for secure data analysis while
safeguarding sensitive information. It enables organizations to extract
valuable insights from data without compromising privacy. Secure multi-party
computation (MPC) is a key tool in PPML, as it allows multiple parties to
jointly compute functions without revealing their private inputs, making it
essential in multi-server environments. We address the performance overhead of
existing maliciously secure protocols, particularly in finite rings like
$\mathbb{Z}_{2^\ell}$, by introducing an efficient protocol for secure linear
function evaluation. We implement our maliciously secure MPC protocol on GPUs,
significantly improving its efficiency and scalability. We extend the protocol
to handle linear and non-linear layers, ensuring compatibility with a wide
range of machine-learning models. Finally, we comprehensively evaluate machine
learning models by integrating our protocol into the workflow, enabling secure
and efficient inference across simple and complex models, such as convolutional
neural networks (CNNs).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.09178v2">SAFES: Sequential Privacy and Fairness Enhancing Data Synthesis for
  Responsible AI</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-11-14T04:36:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Spencer Giddens, Fang Liu</p>
    <p><b>Summary:</b> As data-driven and AI-based decision making gains widespread adoption in most
disciplines, it is crucial that both data privacy and decision fairness are
appropriately addressed. While differential privacy (DP) provides a robust
framework for guaranteeing privacy and several widely accepted methods have
been proposed for improving fairness, the vast majority of existing literature
treats the two concerns independently. For methods that do consider privacy and
fairness simultaneously, they often only apply to a specific machine learning
task, limiting their generalizability. In response, we introduce SAFES, a
Sequential PrivAcy and Fairness Enhancing data Synthesis procedure that
sequentially combines DP data synthesis with a fairness-aware data
transformation. SAFES allows full control over the privacy-fairness-utility
trade-off via tunable privacy and fairness parameters. We illustrate SAFES by
combining AIM, a graphical model-based DP data synthesizer, with a popular
fairness-aware data pre-processing transformation. Empirical evaluations on the
Adult and COMPAS datasets demonstrate that for reasonable privacy loss,
SAFES-generated synthetic data achieve significantly improved fairness metrics
with relatively low utility loss.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.09142v1">Laplace Transform Interpretation of Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-11-14T02:52:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rishav Chourasia, Uzair Javaid, Biplap Sikdar</p>
    <p><b>Summary:</b> We introduce a set of useful expressions of Differential Privacy (DP) notions
in terms of the Laplace transform of the privacy loss distribution. Its bare
form expression appears in several related works on analyzing DP, either as an
integral or an expectation. We show that recognizing the expression as a
Laplace transform unlocks a new way to reason about DP properties by exploiting
the duality between time and frequency domains. Leveraging our interpretation,
we connect the $(q, \rho(q))$-R\'enyi DP curve and the $(\epsilon,
\delta(\epsilon))$-DP curve as being the Laplace and inverse-Laplace transforms
of one another. This connection shows that the R\'enyi divergence is
well-defined for complex orders $q = \gamma + i \omega$. Using our Laplace
transform-based analysis, we also prove an adaptive composition theorem for
$(\epsilon, \delta)$-DP guarantees that is exactly tight (i.e., matches even in
constants) for all values of $\epsilon$. Additionally, we resolve an issue
regarding symmetry of $f$-DP on subsampling that prevented equivalence across
all functional DP notions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.09064v2">Minimax Optimal Two-Sample Testing under Local Differential Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2024-11-13T22:44:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jongmin Mun, Seungwoo Kwak, Ilmun Kim</p>
    <p><b>Summary:</b> We explore the trade-off between privacy and statistical utility in private
two-sample testing under local differential privacy (LDP) for both multinomial
and continuous data. We begin by addressing the multinomial case, where we
introduce private permutation tests using practical privacy mechanisms such as
Laplace, discrete Laplace, and Google's RAPPOR. We then extend our multinomial
approach to continuous data via binning and study its uniform separation rates
under LDP over H\"older and Besov smoothness classes. The proposed tests for
both discrete and continuous cases rigorously control the type I error for any
finite sample size, strictly adhere to LDP constraints, and achieve minimax
separation rates under LDP. The attained minimax rates reveal inherent
privacy-utility trade-offs that are unavoidable in private testing. To address
scenarios with unknown smoothness parameters in density testing, we propose an
adaptive test based on a Bonferroni-type approach that ensures robust
performance without prior knowledge of the smoothness parameters. We validate
our theoretical findings with extensive numerical experiments and demonstrate
the practical relevance and effectiveness of our proposed methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.08635v1">Synthesis with Privacy Against an Observer</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Logic in Computer Science-662E9B">
  <p><b>Published on:</b> 2024-11-13T14:22:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Orna Kupferman, Ofer Leshkowitz, Namma Shamash Halevy</p>
    <p><b>Summary:</b> We study automatic synthesis of systems that interact with their environment
and maintain privacy against an observer to the interaction. The system and the
environment interact via sets $I$ and $O$ of input and output signals. The
input to the synthesis problem contains, in addition to a specification, also a
list of secrets, a function $cost: I\cup O\rightarrow\mathbb{N}$, which maps
each signal to the cost of hiding it, and a bound $b\in\mathbb{N}$ on the
budget that the system may use for hiding of signals. The desired output is an
$(I/O)$-transducer $T$ and a set $H\subseteq I\cup O$ of signals that respects
the bound on the budget, thus $\sum_{s\in H} cost(s)\leq b$, such that for
every possible interaction of $T$, the generated computation satisfies the
specification, yet an observer, from whom the signals in $H$ are hidden, cannot
evaluate the secrets.
  We first show that the problem's complexity is 2EXPTIME-complete for
specifications and secrets in LTL, making it no harder than synthesis without
privacy requirements. We then analyze the complexity further, isolating the two
aspects that do not exist in traditional synthesis: the need to hide secret
values and the need to choose the set $H$. We do this by studying settings in
which traditional synthesis is solvable in polynomial time -- when the
specification formalism is deterministic automata and when the system is closed
-- and show that each of these aspects adds an exponential blow-up in
complexity. We continue and study bounded synthesis with privacy, where the
input includes a bound on the synthesized transducer size, as well as a variant
of the problem in which the observer has knowledge, either about the
specification or about the system, which can be helpful in evaluating the
secrets. Additionally, we study certified privacy, where the synthesis
algorithm provides certification that the secrets remain hidden.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.07806v2">Federated Low-Rank Adaptation with Differential Privacy over Wireless
  Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-11-12T14:01:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tianqu Kang, Zixin Wang, Hengtao He, Jun Zhang, Shenghui Song, Khaled B. Letaief</p>
    <p><b>Summary:</b> Fine-tuning large pre-trained foundation models (FMs) on distributed edge
devices presents considerable computational and privacy challenges. Federated
fine-tuning (FedFT) mitigates some privacy issues by facilitating collaborative
model training without the need to share raw data. To lessen the computational
burden on resource-limited devices, combining low-rank adaptation (LoRA) with
federated learning enables parameter-efficient fine-tuning. Additionally, the
split FedFT architecture partitions an FM between edge devices and a central
server, reducing the necessity for complete model deployment on individual
devices. However, the risk of privacy eavesdropping attacks in FedFT remains a
concern, particularly in sensitive areas such as healthcare and finance. In
this paper, we propose a split FedFT framework with differential privacy (DP)
over wireless networks, where the inherent wireless channel noise in the uplink
transmission is utilized to achieve DP guarantees without adding an extra
artificial noise. We shall investigate the impact of the wireless noise on
convergence performance of the proposed framework. We will also show that by
updating only one of the low-rank matrices in the split FedFT with DP, the
proposed method can mitigate the noise amplification effect. Simulation results
will demonstrate that the proposed framework achieves higher accuracy under
strict privacy budgets compared to baseline methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.07691v1">New Emerged Security and Privacy of Pre-trained Model: a Survey and
  Outlook</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-11-12T10:15:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Meng Yang, Tianqing Zhu, Chi Liu, WanLei Zhou, Shui Yu, Philip S. Yu</p>
    <p><b>Summary:</b> Thanks to the explosive growth of data and the development of computational
resources, it is possible to build pre-trained models that can achieve
outstanding performance on various tasks, such as neural language processing,
computer vision, and more. Despite their powerful capabilities, pre-trained
models have also sparked attention to the emerging security challenges
associated with their real-world applications. Security and privacy issues,
such as leaking privacy information and generating harmful responses, have
seriously undermined users' confidence in these powerful models. Concerns are
growing as model performance improves dramatically. Researchers are eager to
explore the unique security and privacy issues that have emerged, their
distinguishing factors, and how to defend against them. However, the current
literature lacks a clear taxonomy of emerging attacks and defenses for
pre-trained models, which hinders a high-level and comprehensive understanding
of these questions. To fill the gap, we conduct a systematical survey on the
security risks of pre-trained models, proposing a taxonomy of attack and
defense methods based on the accessibility of pre-trained models' input and
weights in various security test scenarios. This taxonomy categorizes attacks
and defenses into No-Change, Input-Change, and Model-Change approaches. With
the taxonomy analysis, we capture the unique security and privacy issues of
pre-trained models, categorizing and summarizing existing security issues based
on their characteristics. In addition, we offer a timely and comprehensive
review of each category's strengths and limitations. Our survey concludes by
highlighting potential new research opportunities in the security and privacy
of pre-trained models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.07468v2">Privacy-Preserving Verifiable Neural Network Inference Service</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-11-12T01:09:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arman Riasi, Jorge Guajardo, Thang Hoang</p>
    <p><b>Summary:</b> Machine learning has revolutionized data analysis and pattern recognition,
but its resource-intensive training has limited accessibility. Machine Learning
as a Service (MLaaS) simplifies this by enabling users to delegate their data
samples to an MLaaS provider and obtain the inference result using a
pre-trained model. Despite its convenience, leveraging MLaaS poses significant
privacy and reliability concerns to the client. Specifically, sensitive
information from the client inquiry data can be leaked to an adversarial MLaaS
provider. Meanwhile, the lack of a verifiability guarantee can potentially
result in biased inference results or even unfair payment issues. While
existing trustworthy machine learning techniques, such as those relying on
verifiable computation or secure computation, offer solutions to privacy and
reliability concerns, they fall short of simultaneously protecting the privacy
of client data and providing provable inference verifiability.
  In this paper, we propose vPIN, a privacy-preserving and verifiable CNN
inference scheme that preserves privacy for client data samples while ensuring
verifiability for the inference. vPIN makes use of partial homomorphic
encryption and commit-and-prove succinct non-interactive argument of knowledge
techniques to achieve desirable security properties. In vPIN, we develop
various optimization techniques to minimize the proving circuit for homomorphic
inference evaluation thereby, improving the efficiency and performance of our
technique. We fully implemented and evaluated our vPIN scheme on standard
datasets (e.g., MNIST, CIFAR-10). Our experimental results show that vPIN
achieves high efficiency in terms of proving time, verification time, and proof
size, while providing client data privacy guarantees and provable
verifiability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.07128v1">ZT-RIC:A Zero Trust RIC Framework for ensuring data Privacy and
  Confidentiality in Open RAN</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-11-11T16:59:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Diana Lin, Samarth Bhargav, Azuka Chiejina, Mohamed I. Ibrahem, Vijay K. Shah</p>
    <p><b>Summary:</b> The advancement of 5G and NextG networks through Open Radio Access Network
(O-RAN) architecture enables a shift toward virtualized, modular, and
disaggregated configurations. A core component of O-RAN is the RAN Intelligent
Controller (RIC), which manages RAN using machine learning-driven xApps that
access sensitive data from RAN and User Equipment (UE), stored in the near
Real-Time RIC (Near-RT RIC) database. This shared, open environment increases
the risk of unauthorized data exposure. To address these concerns, this paper
proposes a zero-trust RIC (ZT-RIC) framework that preserves data privacy across
the RIC platform, including the RIC database, xApps, and E2 interface. ZT-RIC
employs Inner Product Functional Encryption (IPFE) to encrypt RAN/UE data at
the base station, preventing leaks through the E2 interface and shared
database. Additionally, ZT-RIC enables xApps to perform inference on encrypted
data without exposing sensitive information. For evaluation, a state-of-the-art
InterClass xApp, which detects jamming signals using RAN key performance
metrics (KPMs), is implemented. Testing on an LTE/5G O-RAN testbed shows that
ZT-RIC preserves data confidentiality while achieving 97.9% accuracy in jamming
detection and meeting sub-second latency requirements, with a round-trip time
(RTT) of 0.527 seconds.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.07070v2">On Active Privacy Auditing in Supervised Fine-tuning for White-Box
  Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-11-11T15:46:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qian Sun, Hanpeng Wu, Xi Sheryl Zhang</p>
    <p><b>Summary:</b> The pretraining and fine-tuning approach has become the leading technique for
various NLP applications. However, recent studies reveal that fine-tuning data,
due to their sensitive nature, domain-specific characteristics, and
identifiability, pose significant privacy concerns. To help develop more
privacy-resilient fine-tuning models, we introduce a novel active privacy
auditing framework, dubbed Parsing, designed to identify and quantify privacy
leakage risks during the supervised fine-tuning (SFT) of language models (LMs).
The framework leverages improved white-box membership inference attacks (MIAs)
as the core technology, utilizing novel learning objectives and a two-stage
pipeline to monitor the privacy of the LMs' fine-tuning process, maximizing the
exposure of privacy risks. Additionally, we have improved the effectiveness of
MIAs on large LMs including GPT-2, Llama2, and certain variants of them. Our
research aims to provide the SFT community of LMs with a reliable, ready-to-use
privacy auditing tool, and to offer valuable insights into safeguarding privacy
during the fine-tuning process. Experimental results confirm the framework's
efficiency across various models and tasks, emphasizing notable privacy
concerns in the fine-tuning process. Project code available for
https://anonymous.4open.science/r/PARSING-4817/.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.06613v1">Are Neuromorphic Architectures Inherently Privacy-preserving? An
  Exploratory Study</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Neural and Evolutionary Computing-5BC0EB">
  <p><b>Published on:</b> 2024-11-10T22:18:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ayana Moshruba, Ihsen Alouani, Maryam Parsa</p>
    <p><b>Summary:</b> While machine learning (ML) models are becoming mainstream, especially in
sensitive application areas, the risk of data leakage has become a growing
concern. Attacks like membership inference (MIA) have shown that trained models
can reveal sensitive data, jeopardizing confidentiality. While traditional
Artificial Neural Networks (ANNs) dominate ML applications, neuromorphic
architectures, specifically Spiking Neural Networks (SNNs), are emerging as
promising alternatives due to their low power consumption and event-driven
processing, akin to biological neurons. Privacy in ANNs is well-studied;
however, little work has explored the privacy-preserving properties of SNNs.
This paper examines whether SNNs inherently offer better privacy. Using MIAs,
we assess the privacy resilience of SNNs versus ANNs across diverse datasets.
We analyze the impact of learning algorithms (surrogate gradient and
evolutionary), frameworks (snnTorch, TENNLab, LAVA), and parameters on SNN
privacy. Our findings show that SNNs consistently outperform ANNs in privacy
preservation, with evolutionary algorithms offering additional resilience. For
instance, on CIFAR-10, SNNs achieve an AUC of 0.59, significantly lower than
ANNs' 0.82, and on CIFAR-100, SNNs maintain an AUC of 0.58 compared to ANNs'
0.88. Additionally, we explore the privacy-utility trade-off with
Differentially Private Stochastic Gradient Descent (DPSGD), finding that SNNs
sustain less accuracy loss than ANNs under similar privacy constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.06549v1">In-Context Learning for Preserving Patient Privacy: A Framework for
  Synthesizing Realistic Patient Portal Messages</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-11-10T18:06:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joseph Gatto, Parker Seegmiller, Timothy E. Burdick, Sarah Masud Preum</p>
    <p><b>Summary:</b> Since the COVID-19 pandemic, clinicians have seen a large and sustained
influx in patient portal messages, significantly contributing to clinician
burnout. To the best of our knowledge, there are no large-scale public patient
portal messages corpora researchers can use to build tools to optimize
clinician portal workflows. Informed by our ongoing work with a regional
hospital, this study introduces an LLM-powered framework for configurable and
realistic patient portal message generation. Our approach leverages few-shot
grounded text generation, requiring only a small number of de-identified
patient portal messages to help LLMs better match the true style and tone of
real data. Clinical experts in our team deem this framework as HIPAA-friendly,
unlike existing privacy-preserving approaches to synthetic text generation
which cannot guarantee all sensitive attributes will be protected. Through
extensive quantitative and human evaluation, we show that our framework
produces data of higher quality than comparable generation methods as well as
all related datasets. We believe this work provides a path forward for (i) the
release of large-scale synthetic patient message datasets that are
stylistically similar to ground-truth samples and (ii) HIPAA-friendly data
generation which requires minimal human de-identification efforts.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.06513v1">PRISM: Privacy-preserving Inter-Site MRI Harmonization via Disentangled
  Representation Learning</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-11-10T16:29:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sarang Galada, Tanurima Halder, Kunal Deo, Ram P Krish, Kshitij Jadhav</p>
    <p><b>Summary:</b> Multi-site MRI studies often suffer from site-specific variations arising
from differences in methodology, hardware, and acquisition protocols, thereby
compromising accuracy and reliability in clinical AI/ML tasks. We present PRISM
(Privacy-preserving Inter-Site MRI Harmonization), a novel Deep Learning
framework for harmonizing structural brain MRI across multiple sites while
preserving data privacy. PRISM employs a dual-branch autoencoder with
contrastive learning and variational inference to disentangle anatomical
features from style and site-specific variations, enabling unpaired image
translation without traveling subjects or multiple MRI modalities. Our modular
design allows harmonization to any target site and seamless integration of new
sites without the need for retraining or fine-tuning. Using multi-site
structural MRI data, we demonstrate PRISM's effectiveness in downstream tasks
such as brain tissue segmentation and validate its harmonization performance
through multiple experiments. Our framework addresses key challenges in medical
AI/ML, including data privacy, distribution shifts, model generalizability and
interpretability. Code is available at https://github.com/saranggalada/PRISM</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.06317v2">Harpocrates: A Statically Typed Privacy Conscious Programming Framework</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36"> 
  <p><b>Published on:</b> 2024-11-10T00:28:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sinan Pehlivanoglu, Malte Schwarzkopf</p>
    <p><b>Summary:</b> In this paper, we introduce Harpocrates, a compiler plugin and a framework
pair for Scala that binds the privacy policies to the data during data creation
in form of oblivious membranes. Harpocrates eliminates raw data for a policy
protected type from the application, ensuring it can only exist in protected
form and centralizes the policy checking to the policy declaration site, making
the privacy logic easy to maintain and verify. Instead of approaching privacy
from an information flow verification perspective, Harpocrates allow the data
to flow freely throughout the application, inside the policy membranes but
enforces the policies when the data is tried to be accessed, mutated,
declassified or passed through the application boundary. The centralization of
the policies allow the maintainers to change the enforced logic simply by
updating a single function while keeping the rest of the application oblivious
to the change. Especially in a setting where the data definition is shared by
multiple applications, the publisher can update the policies without requiring
the dependent applications to make any changes beyond updating the dependency
version.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.06263v1">Federated Split Learning for Human Activity Recognition with
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-11-09T19:32:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Josue Ndeko, Shaba Shaon, Aubrey Beal, Avimanyu Sahoo, Dinh C. Nguyen</p>
    <p><b>Summary:</b> This paper proposes a novel intelligent human activity recognition (HAR)
framework based on a new design of Federated Split Learning (FSL) with
Differential Privacy (DP) over edge networks. Our FSL-DP framework leverages
both accelerometer and gyroscope data, achieving significant improvements in
HAR accuracy. The evaluation includes a detailed comparison between traditional
Federated Learning (FL) and our FSL framework, showing that the FSL framework
outperforms FL models in both accuracy and loss metrics. Additionally, we
examine the privacy-performance trade-off under different data settings in the
DP mechanism, highlighting the balance between privacy guarantees and model
accuracy. The results also indicate that our FSL framework achieves faster
communication times per training round compared to traditional FL, further
emphasizing its efficiency and effectiveness. This work provides valuable
insight and a novel framework which was tested on a real-life dataset.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.06107v1">A capacity renting framework for shared energy storage considering
  peer-to-peer energy trading of prosumers with privacy protection</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2024-11-09T08:01:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yingcong Sun, Laijun Chen, Yue Chen, Mingrui Tang, Shengwei Mei</p>
    <p><b>Summary:</b> Shared energy storage systems (ESS) present a promising solution to the
temporal imbalance between energy generation from renewable distributed
generators (DGs) and the power demands of prosumers. However, as DG penetration
rates rise, spatial energy imbalances become increasingly significant,
necessitating the integration of peer-to-peer (P2P) energy trading within the
shared ESS framework. Two key challenges emerge in this context: the absence of
effective mechanisms and the greater difficulty for privacy protection due to
increased data communication. This research proposes a capacity renting
framework for shared ESS considering P2P energy trading of prosumers. In the
proposed framework, prosumers can participate in P2P energy trading and rent
capacities from shared ESS. A generalized Nash game is formulated to model the
trading process and the competitive interactions among prosumers, and the
variational equilibrium of the game is proved to be equivalent to the optimal
solution of a quadratic programming (QP) problem. To address the privacy
protection concern, the problem is solved using the alternating direction
method of multipliers (ADMM) with the Paillier cryptosystem. Finally, numerical
simulations demonstrate the impact of P2P energy trading on the shared ESS
framework and validate the effectiveness of the proposed privacy-preserving
algorithm.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.05743v1">Free Record-Level Privacy Risk Evaluation Through Artifact-Based Methods</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-11-08T18:04:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joseph Pollock, Igor Shilov, Euodia Dodd, Yves-Alexandre de Montjoye</p>
    <p><b>Summary:</b> Membership inference attacks (MIAs) are widely used to empirically assess the
privacy risks of samples used to train a target machine learning model.
State-of-the-art methods however require training hundreds of shadow models,
with the same size and architecture of the target model, solely to evaluate the
privacy risk. While one might be able to afford this for small models, the cost
often becomes prohibitive for medium and large models.
  We here instead propose a novel approach to identify the at-risk samples
using only artifacts available during training, with little to no additional
computational overhead. Our method analyzes individual per-sample loss traces
and uses them to identify the vulnerable data samples. We demonstrate the
effectiveness of our artifact-based approach through experiments on the CIFAR10
dataset, showing high precision in identifying vulnerable samples as determined
by a SOTA shadow model-based MIA (LiRA). Impressively, our method reaches the
same precision as another SOTA MIA when measured against LiRA, despite it being
orders of magnitude cheaper. We then show LT-IQR to outperform alternative loss
aggregation methods, perform ablation studies on hyperparameters, and validate
the robustness of our method to the target metric. Finally, we study the
evolution of the vulnerability score distribution throughout training as a
metric for model-level risk assessment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.05733v1">Differential Privacy Under Class Imbalance: Methods and Empirical
  Insights</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">  
  <p><b>Published on:</b> 2024-11-08T17:46:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lucas Rosenblatt, Yuliia Lut, Eitan Turok, Marco Avella-Medina, Rachel Cummings</p>
    <p><b>Summary:</b> Imbalanced learning occurs in classification settings where the distribution
of class-labels is highly skewed in the training data, such as when predicting
rare diseases or in fraud detection. This class imbalance presents a
significant algorithmic challenge, which can be further exacerbated when
privacy-preserving techniques such as differential privacy are applied to
protect sensitive training data. Our work formalizes these challenges and
provides a number of algorithmic solutions. We consider DP variants of
pre-processing methods that privately augment the original dataset to reduce
the class imbalance; these include oversampling, SMOTE, and private synthetic
data generation. We also consider DP variants of in-processing techniques,
which adjust the learning algorithm to account for the imbalance; these include
model bagging, class-weighted empirical risk minimization and class-weighted
deep learning. For each method, we either adapt an existing imbalanced learning
technique to the private setting or demonstrate its incompatibility with
differential privacy. Finally, we empirically evaluate these privacy-preserving
imbalanced learning methods under various data and distributional settings. We
find that private synthetic data methods perform well as a data pre-processing
step, while class-weighted ERMs are an alternative in higher-dimensional
settings where private synthetic data suffers from the curse of dimensionality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.05901v1">ViT Enhanced Privacy-Preserving Secure Medical Data Sharing and
  Classification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-11-08T16:33:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Al Amin, Kamrul Hasan, Sharif Ullah, M. Shamim Hossain</p>
    <p><b>Summary:</b> Privacy-preserving and secure data sharing are critical for medical image
analysis while maintaining accuracy and minimizing computational overhead are
also crucial. Applying existing deep neural networks (DNNs) to encrypted
medical data is not always easy and often compromises performance and security.
To address these limitations, this research introduces a secure framework
consisting of a learnable encryption method based on the block-pixel operation
to encrypt the data and subsequently integrate it with the Vision Transformer
(ViT). The proposed framework ensures data privacy and security by creating
unique scrambling patterns per key, providing robust performance against
leading bit attacks and minimum difference attacks.</p>
  </details>
</div>

