
<h2>2025-09</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.09485v1">Balancing Utility and Privacy: Dynamically Private SGD with Random
  Projection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-09-11T14:17:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhanhong Jiang, Md Zahid Hasan, Nastaran Saadati, Aditya Balu, Chao Liu, Soumik Sarkar</p>
    <p><b>Summary:</b> Stochastic optimization is a pivotal enabler in modern machine learning,
producing effective models for various tasks. However, several existing works
have shown that model parameters and gradient information are susceptible to
privacy leakage. Although Differentially Private SGD (DPSGD) addresses privacy
concerns, its static noise mechanism impacts the error bounds for model
performance. Additionally, with the exponential increase in model parameters,
efficient learning of these models using stochastic optimizers has become more
challenging. To address these concerns, we introduce the Dynamically
Differentially Private Projected SGD (D2P2-SGD) optimizer. In D2P2-SGD, we
combine two important ideas: (i) dynamic differential privacy (DDP) with
automatic gradient clipping and (ii) random projection with SGD, allowing
dynamic adjustment of the tradeoff between utility and privacy of the model. It
exhibits provably sub-linear convergence rates across different objective
functions, matching the best available rate. The theoretical analysis further
suggests that DDP leads to better utility at the cost of privacy, while random
projection enables more efficient model learning. Extensive experiments across
diverse datasets show that D2P2-SGD remarkably enhances accuracy while
maintaining privacy. Our code is available here.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.09285v1">The Impact of Device Type, Data Practices, and Use Case Scenarios on
  Privacy Concerns about Eye-tracked Augmented Reality in the United States and
  Germany</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-09-11T09:21:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Efe Bozkir, Babette Bühler, Xiaoyuan Wu, Enkelejda Kasneci, Lujo Bauer, Lorrie Faith Cranor</p>
    <p><b>Summary:</b> Augmented reality technology will likely be prevalent with more affordable
head-mounted displays. Integrating novel interaction modalities such as eye
trackers into head-mounted displays could lead to collecting vast amounts of
biometric data, which may allow inference of sensitive user attributes like
health status or sexual preference, posing privacy issues. While previous works
broadly examined privacy concerns about augmented reality, ours is the first to
extensively explore privacy concerns on behavioral data, particularly eye
tracking in augmented reality. We crowdsourced four survey studies in the
United States (n1 = 48, n2 = 525) and Germany (n3 = 48, n4 = 525) to understand
the impact of user attributes, augmented reality devices, use cases, data
practices, and country on privacy concerns. Our findings indicate that
participants are generally concerned about privacy when they know what
inferences can be made based on the collected data. Despite the more prominent
use of smartphones in daily life than augmented reality glasses, we found no
indications of differing privacy concerns depending on the device type. In
addition, our participants are more comfortable when a particular use case
benefits them and less comfortable when other humans can consume their data.
Furthermore, participants in the United States are less concerned about their
privacy than those in Germany. Based on our findings, we provide several
recommendations to practitioners and policymakers for privacy-aware augmented
reality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.09103v1">AgriSentinel: Privacy-Enhanced Embedded-LLM Crop Disease Alerting System</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-09-11T02:29:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chanti Raju Mylay, Bobin Deng, Zhipeng Cai, Honghui Xu</p>
    <p><b>Summary:</b> Crop diseases pose significant threats to global food security, agricultural
productivity, and sustainable farming practices, directly affecting farmers'
livelihoods and economic stability. To address the growing need for effective
crop disease management, AI-based disease alerting systems have emerged as
promising tools by providing early detection and actionable insights for timely
intervention. However, existing systems often overlook critical aspects such as
data privacy, market pricing power, and farmer-friendly usability, leaving
farmers vulnerable to privacy breaches and economic exploitation. To bridge
these gaps, we propose AgriSentinel, the first Privacy-Enhanced Embedded-LLM
Crop Disease Alerting System. AgriSentinel incorporates a differential privacy
mechanism to protect sensitive crop image data while maintaining classification
accuracy. Its lightweight deep learning-based crop disease classification model
is optimized for mobile devices, ensuring accessibility and usability for
farmers. Additionally, the system includes a fine-tuned, on-device large
language model (LLM) that leverages a curated knowledge pool to provide farmers
with specific, actionable suggestions for managing crop diseases, going beyond
simple alerting. Comprehensive experiments validate the effectiveness of
AgriSentinel, demonstrating its ability to safeguard data privacy, maintain
high classification performance, and deliver practical, actionable disease
management strategies. AgriSentinel offers a robust, farmer-friendly solution
for automating crop disease alerting and management, ultimately contributing to
improved agricultural decision-making and enhanced crop productivity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.09097v1">DP-FedLoRA: Privacy-Enhanced Federated Fine-Tuning for On-Device Large
  Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-09-11T02:16:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Honghui Xu, Shiva Shrestha, Wei Chen, Zhiyuan Li, Zhipeng Cai</p>
    <p><b>Summary:</b> As on-device large language model (LLM) systems become increasingly
prevalent, federated fine-tuning enables advanced language understanding and
generation directly on edge devices; however, it also involves processing
sensitive, user-specific data, raising significant privacy concerns within the
federated learning framework. To address these challenges, we propose
DP-FedLoRA, a privacy-enhanced federated fine-tuning framework that integrates
LoRA-based adaptation with differential privacy in a communication-efficient
setting. Each client locally clips and perturbs its LoRA matrices using
Gaussian noise to satisfy ($\epsilon$, $\delta$)-differential privacy. We
further provide a theoretical analysis demonstrating the unbiased nature of the
updates and deriving bounds on the variance introduced by noise, offering
practical guidance for privacy-budget calibration. Experimental results across
mainstream benchmarks show that DP-FedLoRA delivers competitive performance
while offering strong privacy guarantees, paving the way for scalable and
privacy-preserving LLM deployment in on-device environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.09091v1">Towards Confidential and Efficient LLM Inference with Dual Privacy
  Protection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-09-11T01:54:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Honglan Yu, Yibin Wang, Feifei Dai, Dong Liu, Haihui Fan, Xiaoyan Gu</p>
    <p><b>Summary:</b> CPU-based trusted execution environments (TEEs) and differential privacy (DP)
have gained wide applications for private inference. Due to high inference
latency in TEEs, researchers use partition-based approaches that offload linear
model components to GPUs. However, dense nonlinear layers of large language
models (LLMs) result in significant communication overhead between TEEs and
GPUs. DP-based approaches apply random noise to protect data privacy, but this
compromises LLM performance and semantic understanding. To overcome the above
drawbacks, this paper proposes CMIF, a Confidential and efficient Model
Inference Framework. CMIF confidentially deploys the embedding layer in the
client-side TEE and subsequent layers on GPU servers. Meanwhile, it optimizes
the Report-Noisy-Max mechanism to protect sensitive inputs with a slight
decrease in model performance. Extensive experiments on Llama-series models
demonstrate that CMIF reduces additional inference overhead in TEEs while
preserving user data privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.08995v1">When FinTech Meets Privacy: Securing Financial LLMs with Differential
  Private Fine-Tuning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-09-10T20:43:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sichen Zhu, Hoyeung Leung, Xiaoyi Wang, Jia Wei, Honghui Xu</p>
    <p><b>Summary:</b> The integration of Large Language Models (LLMs) into financial technology
(FinTech) has revolutionized the analysis and processing of complex financial
data, driving advancements in real-time decision-making and analytics. With the
growing trend of deploying AI models on edge devices for financial
applications, ensuring the privacy of sensitive financial data has become a
significant challenge. To address this, we propose DPFinLLM, a
privacy-enhanced, lightweight LLM specifically designed for on-device financial
applications. DPFinLLM combines a robust differential privacy mechanism with a
streamlined architecture inspired by state-of-the-art models, enabling secure
and efficient processing of financial data. This proposed DPFinLLM can not only
safeguard user data from privacy breaches but also ensure high performance
across diverse financial tasks. Extensive experiments on multiple financial
sentiment datasets validate the effectiveness of DPFinLLM, demonstrating its
ability to achieve performance comparable to fully fine-tuned models, even
under strict privacy constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.08804v1">Approximate Algorithms for Verifying Differential Privacy with Gaussian
  Distributions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Programming Languages-D91E36"> 
  <p><b>Published on:</b> 2025-09-10T17:37:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bishnu Bhusal, Rohit Chadha, A. Prasad Sistla, Mahesh Viswanathan</p>
    <p><b>Summary:</b> The verification of differential privacy algorithms that employ Gaussian
distributions is little understood. This paper tackles the challenge of
verifying such programs by introducing a novel approach to approximating
probability distributions of loop-free programs that sample from both discrete
and continuous distributions with computable probability density functions,
including Gaussian and Laplace. We establish that verifying
$(\epsilon,\delta)$-differential privacy for these programs is \emph{almost
decidable}, meaning the problem is decidable for all values of $\delta$ except
those in a finite set. Our verification algorithm is based on computing
probabilities to any desired precision by combining integral approximations,
and tail probability bounds. The proposed methods are implemented in the tool,
DipApprox, using the FLINT library for high-precision integral computations,
and incorporate optimizations to enhance scalability. We validate {\ourtool} on
fundamental privacy-preserving algorithms, such as Gaussian variants of the
Sparse Vector Technique and Noisy Max, demonstrating its effectiveness in both
confirming privacy guarantees and detecting violations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.08782v1">Extended Version: Security and Privacy Perceptions of Pakistani Facebook
  Matrimony Group Users</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B">
  <p><b>Published on:</b> 2025-09-10T17:12:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mah Jan Dorazahi, Deepthi Mungara, Yasemin Acar, Harshini Sri Ramulu</p>
    <p><b>Summary:</b> In Pakistan, where dating apps are subject to censorship, Facebook matrimony
groups -- also referred to as marriage groups -- serve as alternative virtual
spaces for members to search for potential life partners. To participate in
these groups, members often share sensitive personal information such as
photos, addresses, and phone numbers, which exposes them to risks such as
fraud, blackmail, and identity theft. To better protect users of Facebook
matrimony groups, we need to understand aspects related to user safety, such as
how users perceive risks, what influences their trust in sharing personal
information, and how they navigate security and privacy concerns when seeking
potential partners online. In this study, through 23 semi-structured
interviews, we explore how Pakistani users of Facebook matrimony groups
perceive and navigate risks of sharing personal information, and how cultural
norms and expectations influence their behavior in these groups.
  We find elevated privacy concerns among participants, leading them to share
limited personal information and creating mistrust among potential partners.
Many also expressed concerns about the authenticity of profiles and major
security risks, such as identity theft, harassment, and social judgment. Our
work highlights the challenges of safely navigating Facebook matrimony groups
in Pakistan and offers recommendations for such as implementing stronger
identity verification by group admins, enforcing stricter cybersecurity laws,
clear platform guidelines to ensure accountability, and technical feature
enhancements -- including restricting screenshots, picture downloads, and
implementing anonymous chats -- to protect user data and build trust.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.08722v1">SilentLedger: Privacy-Preserving Auditing for Blockchains with Complete
  Non-Interactivity</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-09-10T16:14:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zihan Liu, Xiaohu Wang, Chao Lin, Minghui Xu, Debiao He, Xinyi Huang</p>
    <p><b>Summary:</b> Privacy-preserving blockchain systems are essential for protecting
transaction data, yet they must also provide auditability that enables auditors
to recover participant identities and transaction amounts when warranted.
Existing designs often compromise the independence of auditing and
transactions, introducing extra interactions that undermine usability and
scalability. Moreover, many auditable solutions depend on auditors serving as
validators or recording nodes, which introduces risks to both data security and
system reliability.
  To overcome these challenges, we propose SilentLedger, a privacy-preserving
transaction system with auditing and complete non-interactivity. To support
public verification of authorization, we introduce a renewable anonymous
certificate scheme with formal semantics and a rigorous security model.
SilentLedger further employs traceable transaction mechanisms constructed from
established cryptographic primitives, enabling users to transact without
interaction while allowing auditors to audit solely from on-chain data. We
formally prove security properties including authenticity, anonymity,
confidentiality, and soundness, provide a concrete instantiation, and evaluate
performance under a standard 2-2 transaction model. Our implementation and
benchmarks demonstrate that SilentLedger achieves superior performance compared
with state-of-the-art solutions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.08720v1">PAnDA: Rethinking Metric Differential Privacy Optimization at Scale with
  Anchor-Based Approximation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-09-10T16:14:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruiyao Liu, Chenxi Qiu</p>
    <p><b>Summary:</b> Metric Differential Privacy (mDP) extends the local differential privacy
(LDP) framework to metric spaces, enabling more nuanced privacy protection for
data such as geo-locations. However, existing mDP optimization methods,
particularly those based on linear programming (LP), face scalability
challenges due to the quadratic growth in decision variables. In this paper, we
propose Perturbation via Anchor-based Distributed Approximation (PAnDA), a
scalable two-phase framework for optimizing metric differential privacy (mDP).
To reduce computational overhead, PAnDA allows each user to select a small set
of anchor records, enabling the server to solve a compact linear program over a
reduced domain. We introduce three anchor selection strategies, exponential
decay (PAnDA-e), power-law decay (PAnDA-p), and logistic decay (PAnDA-l), and
establish theoretical guarantees under a relaxed privacy notion called
probabilistic mDP (PmDP). Experiments on real-world geo-location datasets
demonstrate that PAnDA scales to secret domains with up to 5,000 records, two
times larger than prior LP-based methods, while providing theoretical
guarantees for both privacy and utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.08704v1">Tight Privacy Audit in One Run</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-09-10T15:55:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zihang Xiang, Tianhao Wang, Hanshen Xiao, Yuan Tian, Di Wang</p>
    <p><b>Summary:</b> In this paper, we study the problem of privacy audit in one run and show that
our method achieves tight audit results for various differentially private
protocols. This includes obtaining tight results for auditing
$(\varepsilon,\delta)$-DP algorithms where all previous work fails to achieve
in any parameter setups. We first formulate a framework for privacy audit
\textit{in one run} with refinement compared with previous work. Then, based on
modeling privacy by the $f$-DP formulation, we study the implications of our
framework to obtain a theoretically justified lower bound for privacy audit. In
the experiment, we compare with previous work and show that our audit method
outperforms the rest in auditing various differentially private algorithms. We
also provide experiments that give contrasting conclusions to previous work on
the parameter settings for privacy audits in one run.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.08554v1">Acceptability of AI Assistants for Privacy: Perceptions of Experts and
  Users on Personalized Privacy Assistants</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-09-10T12:59:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Meihe Xu, Aurelia Tamò-Larrieux, Arianna Rossi</p>
    <p><b>Summary:</b> Individuals increasingly face an overwhelming number of tasks and decisions.
To cope with the new reality, there is growing research interest in developing
intelligent agents that can effectively assist people across various aspects of
daily life in a tailored manner, with privacy emerging as a particular area of
application. Artificial intelligence (AI) assistants for privacy, such as
personalized privacy assistants (PPAs), have the potential to automatically
execute privacy decisions based on users' pre-defined privacy preferences,
sparing them the mental effort and time usually spent on each privacy decision.
This helps ensure that, even when users feel overwhelmed or resigned about
privacy, the decisions made by PPAs still align with their true preferences and
best interests. While research has explored possible designs of such agents,
user and expert perspectives on the acceptability of such AI-driven solutions
remain largely unexplored. In this study, we conducted five focus groups with
domain experts (n = 11) and potential users (n = 26) to uncover key themes
shaping the acceptance of PPAs. Factors influencing the acceptability of AI
assistants for privacy include design elements (such as information sources
used by the agent), external conditions (such as regulation and literacy
education), and systemic conditions (e.g., public or market providers and the
need to avoid monopoly) to PPAs. These findings provide theoretical extensions
to technology acceptance models measuring PPAs, insights on design, and policy
implications for PPAs, as well as broader implications for the design of AI
assistants.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.08387v1">Infinite Stream Estimation under Personalized $w$-Event Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2025-09-10T08:27:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Leilei Du, Peng Cheng, Lei Chen, Heng Tao Shen, Xuemin Lin, Wei Xi</p>
    <p><b>Summary:</b> Streaming data collection is indispensable for stream data analysis, such as
event monitoring. However, publishing these data directly leads to privacy
leaks. $w$-event privacy is a valuable tool to protect individual privacy
within a given time window while maintaining high accuracy in data collection.
Most existing $w$-event privacy studies on infinite data stream only focus on
homogeneous privacy requirements for all users. In this paper, we propose
personalized $w$-event privacy protection that allows different users to have
different privacy requirements in private data stream estimation. Specifically,
we design a mechanism that allows users to maintain constant privacy
requirements at each time slot, namely Personalized Window Size Mechanism
(PWSM). Then, we propose two solutions to accurately estimate stream data
statistics while achieving $w$-event level $\epsilon$ personalized differential
privacy ( ($w$, $\epsilon$)-EPDP), namely Personalized Budget Distribution
(PBD) and Peronalized Budget Absorption (PBA). PBD always provides at least the
same privacy budget for the next time step as the amount consumed in the
previous release. PBA fully absorbs the privacy budget from the previous $k$
time slots, while also borrowing from the privacy budget of the next $k$ time
slots, to increase the privacy budget for the current time slot. We prove that
both PBD and PBA outperform the state-of-the-art private stream estimation
methods while satisfying the privacy requirements of all users. We demonstrate
the efficiency and effectiveness of our PBD and PBA on both real and synthetic
data sets, compared with the recent uniformity $w$-event approaches, Budget
Distribution (BD) and Budget Absorption (BA). Our PBD achieves 68% less error
than BD on average on real data sets. Besides, our PBA achieves 24.9% less
error than BA on average on synthetic data sets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.08142v1">Privacy Preserving Semantic Communications Using Vision Language Models:
  A Segmentation and Generation Approach</a></h3>
  
  <p><b>Published on:</b> 2025-09-09T20:49:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haoran Chang, Mingzhe Chen, Huaxia Wang, Qianqian Zhang</p>
    <p><b>Summary:</b> Semantic communication has emerged as a promising paradigm for
next-generation wireless systems, improving the communication efficiency by
transmitting high-level semantic features. However, reliance on unimodal
representations can degrade reconstruction under poor channel conditions, and
privacy concerns of the semantic information attack also gain increasing
attention. In this work, a privacy-preserving semantic communication framework
is proposed to protect sensitive content of the image data. Leveraging a
vision-language model (VLM), the proposed framework identifies and removes
private content regions from input images prior to transmission. A shared
privacy database enables semantic alignment between the transmitter and
receiver to ensure consistent identification of sensitive entities. At the
receiver, a generative module reconstructs the masked regions using learned
semantic priors and conditioned on the received text embedding. Simulation
results show that generalizes well to unseen image processing tasks, improves
reconstruction quality at the authorized receiver by over 10% using text
embedding, and reduces identity leakage to the eavesdropper by more than 50%.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.08018v1">Enhancing Privacy Preservation and Reducing Analysis Time with Federated
  Transfer Learning in Digital Twins-based Computed Tomography Scan Analysis</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-09-09T04:54:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Avais Jan, Qasim Zia, Murray Patterson</p>
    <p><b>Summary:</b> The application of Digital Twin (DT) technology and Federated Learning (FL)
has great potential to change the field of biomedical image analysis,
particularly for Computed Tomography (CT) scans. This paper presents Federated
Transfer Learning (FTL) as a new Digital Twin-based CT scan analysis paradigm.
FTL uses pre-trained models and knowledge transfer between peer nodes to solve
problems such as data privacy, limited computing resources, and data
heterogeneity. The proposed framework allows real-time collaboration between
cloud servers and Digital Twin-enabled CT scanners while protecting patient
identity. We apply the FTL method to a heterogeneous CT scan dataset and assess
model performance using convergence time, model accuracy, precision, recall, F1
score, and confusion matrix. It has been shown to perform better than
conventional FL and Clustered Federated Learning (CFL) methods with better
precision, accuracy, recall, and F1-score. The technique is beneficial in
settings where the data is not independently and identically distributed
(non-IID), and it offers reliable, efficient, and secure solutions for medical
diagnosis. These findings highlight the possibility of using FTL to improve
decision-making in digital twin-based CT scan analysis, secure and efficient
medical image analysis, promote privacy, and open new possibilities for
applying precision medicine and smart healthcare systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.07131v1">SoK: Security and Privacy of AI Agents for Blockchain</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-09-08T18:32:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nicolò Romandini, Carlo Mazzocca, Kai Otsuki, Rebecca Montanari</p>
    <p><b>Summary:</b> Blockchain and smart contracts have garnered significant interest in recent
years as the foundation of a decentralized, trustless digital ecosystem,
thereby eliminating the need for traditional centralized authorities. Despite
their central role in powering Web3, their complexity still presents
significant barriers for non-expert users. To bridge this gap, Artificial
Intelligence (AI)-based agents have emerged as valuable tools for interacting
with blockchain environments, supporting a range of tasks, from analyzing
on-chain data and optimizing transaction strategies to detecting
vulnerabilities within smart contracts. While interest in applying AI to
blockchain is growing, the literature still lacks a comprehensive survey that
focuses specifically on the intersection with AI agents. Most of the related
work only provides general considerations, without focusing on any specific
domain. This paper addresses this gap by presenting the first Systematization
of Knowledge dedicated to AI-driven systems for blockchain, with a special
focus on their security and privacy dimensions, shedding light on their
applications, limitations, and future research directions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.07055v1">Sequentially Auditing Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2025-09-08T17:57:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tomás González, Mateo Dulce-Rubio, Aaditya Ramdas, Mónica Ribero</p>
    <p><b>Summary:</b> We propose a practical sequential test for auditing differential privacy
guarantees of black-box mechanisms. The test processes streams of mechanisms'
outputs providing anytime-valid inference while controlling Type I error,
overcoming the fixed sample size limitation of previous batch auditing methods.
Experiments show this test detects violations with sample sizes that are orders
of magnitude smaller than existing methods, reducing this number from 50K to a
few hundred examples, across diverse realistic mechanisms. Notably, it
identifies DP-SGD privacy violations in \textit{under} one training run, unlike
prior methods needing full model training.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.06444v1">HyFedRAG: A Federated Retrieval-Augmented Generation Framework for
  Heterogeneous and Privacy-Sensitive Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-09-08T08:44:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Cheng Qian, Hainan Zhang, Yongxin Tong, Hong-Wei Zheng, Zhiming Zheng</p>
    <p><b>Summary:</b> Centralized RAG pipelines struggle with heterogeneous and privacy-sensitive
data, especially in distributed healthcare settings where patient data spans
SQL, knowledge graphs, and clinical notes. Clinicians face difficulties
retrieving rare disease cases due to privacy constraints and the limitations of
traditional cloud-based RAG systems in handling diverse formats and edge
devices. To address this, we introduce HyFedRAG, a unified and efficient
Federated RAG framework tailored for Hybrid data modalities. By leveraging an
edge-cloud collaborative mechanism, HyFedRAG enables RAG to operate across
diverse data sources while preserving data privacy. Our key contributions are:
(1) We design an edge-cloud collaborative RAG framework built on Flower, which
supports querying structured SQL data, semi-structured knowledge graphs, and
unstructured documents. The edge-side LLMs convert diverse data into
standardized privacy-preserving representations, and the server-side LLMs
integrates them for global reasoning and generation. (2) We integrate
lightweight local retrievers with privacy-aware LLMs and provide three
anonymization tools that enable each client to produce semantically rich,
de-identified summaries for global inference across devices. (3) To optimize
response latency and reduce redundant computation, we design a three-tier
caching strategy consisting of local cache, intermediate representation cache,
and cloud inference cache. Experimental results on PMC-Patients demonstrate
that HyFedRAG outperforms existing baselines in terms of retrieval quality,
generation consistency, and system efficiency. Our framework offers a scalable
and privacy-compliant solution for RAG over structural-heterogeneous data,
unlocking the potential of LLMs in sensitive and diverse data environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.06368v1">From Perception to Protection: A Developer-Centered Study of Security
  and Privacy Threats in Extended Reality (XR)</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-09-08T06:48:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kunlin Cai, Jinghuai Zhang, Ying Li, Zhiyuan Wang, Xun Chen, Tianshi Li, Yuan Tian</p>
    <p><b>Summary:</b> The immersive nature of XR introduces a fundamentally different set of
security and privacy (S&P) challenges due to the unprecedented user
interactions and data collection that traditional paradigms struggle to
mitigate. As the primary architects of XR applications, developers play a
critical role in addressing novel threats. However, to effectively support
developers, we must first understand how they perceive and respond to different
threats. Despite the growing importance of this issue, there is a lack of
in-depth, threat-aware studies that examine XR S&P from the developers'
perspective. To fill this gap, we interviewed 23 professional XR developers
with a focus on emerging threats in XR. Our study addresses two research
questions aiming to uncover existing problems in XR development and identify
actionable paths forward.
  By examining developers' perceptions of S&P threats, we found that: (1) XR
development decisions (e.g., rich sensor data collection, user-generated
content interfaces) are closely tied to and can amplify S&P threats, yet
developers are often unaware of these risks, resulting in cognitive biases in
threat perception; and (2) limitations in existing mitigation methods, combined
with insufficient strategic, technical, and communication support, undermine
developers' motivation, awareness, and ability to effectively address these
threats. Based on these findings, we propose actionable and stakeholder-aware
recommendations to improve XR S&P throughout the XR development process. This
work represents the first effort to undertake a threat-aware,
developer-centered study in the XR domain -- an area where the immersive,
data-rich nature of the XR technology introduces distinctive challenges.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.06361v2">Speaker Privacy and Security in the Big Data Era: Protection and Defense
  against Deepfake</a></h3>
  
  <p><b>Published on:</b> 2025-09-08T06:22:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Liping Chen, Kong Aik Lee, Zhen-Hua Ling, Xin Wang, Rohan Kumar Das, Tomoki Toda, Haizhou Li</p>
    <p><b>Summary:</b> In the era of big data, remarkable advancements have been achieved in
personalized speech generation techniques that utilize speaker attributes,
including voice and speaking style, to generate deepfake speech. This has also
amplified global security risks from deepfake speech misuse, resulting in
considerable societal costs worldwide. To address the security threats posed by
deepfake speech, techniques have been developed focusing on both the protection
of voice attributes and the defense against deepfake speech. Among them, the
voice anonymization technique has been developed to protect voice attributes
from extraction for deepfake generation, while deepfake detection and
watermarking have been utilized to defend against the misuse of deepfake
speech. This paper provides a short and concise overview of the three
techniques, describing the methodologies, advancements, and challenges. A
comprehensive version, offering additional discussions, will be published in
the near future.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.06264v1">PLRV-O: Advancing Differentially Private Deep Learning via Privacy Loss
  Random Variable Optimization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-09-08T01:06:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qin Yang, Nicholas Stout, Meisam Mohammady, Han Wang, Ayesha Samreen, Christopher J Quinn, Yan Yan, Ashish Kundu, Yuan Hong</p>
    <p><b>Summary:</b> Differentially Private Stochastic Gradient Descent (DP-SGD) is a standard
method for enforcing privacy in deep learning, typically using the Gaussian
mechanism to perturb gradient updates. However, conventional mechanisms such as
Gaussian and Laplacian noise are parameterized only by variance or scale. This
single degree of freedom ties the magnitude of noise directly to both privacy
loss and utility degradation, preventing independent control of these two
factors. The problem becomes more pronounced when the number of composition
rounds T and batch size B vary across tasks, as these variations induce
task-dependent shifts in the privacy-utility trade-off, where small changes in
noise parameters can disproportionately affect model accuracy. To address this
limitation, we introduce PLRV-O, a framework that defines a broad search space
of parameterized DP-SGD noise distributions, where privacy loss moments are
tightly characterized yet can be optimized more independently with respect to
utility loss. This formulation enables systematic adaptation of noise to
task-specific requirements, including (i) model size, (ii) training duration,
(iii) batch sampling strategies, and (iv) clipping thresholds under both
training and fine-tuning settings. Empirical results demonstrate that PLRV-O
substantially improves utility under strict privacy constraints. On CIFAR-10, a
fine-tuned ViT achieves 94.03% accuracy at epsilon approximately 0.5, compared
to 83.93% with Gaussian noise. On SST-2, RoBERTa-large reaches 92.20% accuracy
at epsilon approximately 0.2, versus 50.25% with Gaussian.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.06142v2">RetinaGuard: Obfuscating Retinal Age in Fundus Images for Biometric
  Privacy Preserving</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-09-07T17:16:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhengquan Luo, Chi Liu, Dongfu Xiao, Zhen Yu, Yueye Wang, Tianqing Zhu</p>
    <p><b>Summary:</b> The integration of AI with medical images enables the extraction of implicit
image-derived biomarkers for a precise health assessment. Recently, retinal
age, a biomarker predicted from fundus images, is a proven predictor of
systemic disease risks, behavioral patterns, aging trajectory and even
mortality. However, the capability to infer such sensitive biometric data
raises significant privacy risks, where unauthorized use of fundus images could
lead to bioinformation leakage, breaching individual privacy. In response, we
formulate a new research problem of biometric privacy associated with medical
images and propose RetinaGuard, a novel privacy-enhancing framework that
employs a feature-level generative adversarial masking mechanism to obscure
retinal age while preserving image visual quality and disease diagnostic
utility. The framework further utilizes a novel multiple-to-one knowledge
distillation strategy incorporating a retinal foundation model and diverse
surrogate age encoders to enable a universal defense against black-box age
prediction models. Comprehensive evaluations confirm that RetinaGuard
successfully obfuscates retinal age prediction with minimal impact on image
quality and pathological feature representation. RetinaGuard is also flexible
for extension to other medical image derived biomarkers. RetinaGuard is also
flexible for extension to other medical image biomarkers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.06133v1">VehiclePassport: A GAIA-X-Aligned, Blockchain-Anchored
  Privacy-Preserving, Zero-Knowledge Digital Passport for Smart Vehicles</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">  
  <p><b>Published on:</b> 2025-09-07T16:40:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pradyumna Kaushal</p>
    <p><b>Summary:</b> Modern vehicles accumulate fragmented lifecycle records across OEMs, owners,
and service centers that are difficult to verify and prone to fraud. We propose
VehiclePassport, a GAIA-X-aligned digital passport anchored on blockchain with
zero-knowledge proofs (ZKPs) for privacy-preserving verification.
VehiclePassport immutably commits to manufacturing, telemetry, and service
events while enabling selective disclosure via short-lived JWTs and Groth16
proofs. Our open-source reference stack anchors hashes on Polygon zkEVM at
<$0.02 per event, validates proofs in <10 ms, and scales to millions of
vehicles. This architecture eliminates paper-based KYC, ensures GDPR-compliant
traceability, and establishes a trustless foundation for insurance, resale, and
regulatory applications in global mobility data markets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.05608v1">Cross-Service Threat Intelligence in LLM Services using
  Privacy-Preserving Fingerprints</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-09-06T05:57:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Waris Gill, Natalie Isak, Matthew Dressman</p>
    <p><b>Summary:</b> The widespread deployment of LLMs across enterprise services has created a
critical security blind spot. Organizations operate multiple LLM services
handling billions of queries daily, yet regulatory compliance boundaries
prevent these services from sharing threat intelligence about prompt injection
attacks, the top security risk for LLMs. When an attack is detected in one
service, the same threat may persist undetected in others for months, as
privacy regulations prohibit sharing user prompts across compliance boundaries.
  We present BinaryShield, the first privacy-preserving threat intelligence
system that enables secure sharing of attack fingerprints across compliance
boundaries. BinaryShield transforms suspicious prompts through a unique
pipeline combining PII redaction, semantic embedding, binary quantization, and
randomized response mechanism to potentially generate non-invertible
fingerprints that preserve attack patterns while providing privacy. Our
evaluations demonstrate that BinaryShield achieves an F1-score of 0.94,
significantly outperforming SimHash (0.77), the privacy-preserving baseline,
while achieving 64x storage reduction and 38x faster similarity search compared
to dense embeddings.</p>
  </details>
</div>


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
  <h3><a href="http://arxiv.org/abs/2509.05382v1">User Privacy and Large Language Models: An Analysis of Frontier
  Developers' Privacy Policies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-09-05T01:01:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jennifer King, Kevin Klyman, Emily Capstick, Tiffany Saade, Victoria Hsieh</p>
    <p><b>Summary:</b> Hundreds of millions of people now regularly interact with large language
models via chatbots. Model developers are eager to acquire new sources of
high-quality training data as they race to improve model capabilities and win
market share. This paper analyzes the privacy policies of six U.S. frontier AI
developers to understand how they use their users' chats to train models.
Drawing primarily on the California Consumer Privacy Act, we develop a novel
qualitative coding schema that we apply to each developer's relevant privacy
policies to compare data collection and use practices across the six companies.
We find that all six developers appear to employ their users' chat data to
train and improve their models by default, and that some retain this data
indefinitely. Developers may collect and train on personal information
disclosed in chats, including sensitive information such as biometric and
health data, as well as files uploaded by users. Four of the six companies we
examined appear to include children's chat data for model training, as well as
customer data from other products. On the whole, developers' privacy policies
often lack essential information about their practices, highlighting the need
for greater transparency and accountability. We address the implications of
users' lack of consent for the use of their chat data for model training, data
security issues arising from indefinite chat data retention, and training on
children's chat data. We conclude by providing recommendations to policymakers
and developers to address the data privacy challenges posed by LLM-powered
chatbots.</p>
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
  <h3><a href="http://arxiv.org/abs/2509.05377v1">Enhancing Gradient Variance and Differential Privacy in Quantum
  Federated Learning</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-09-04T15:29:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Duc-Thien Phan, Minh-Duong Nguyen, Quoc-Viet Pham, Huilong Pi</p>
    <p><b>Summary:</b> Upon integrating Quantum Neural Network (QNN) as the local model, Quantum
Federated Learning (QFL) has recently confronted notable challenges. Firstly,
exploration is hindered over sharp minima, decreasing learning performance.
Secondly, the steady gradient descent results in more stable and predictable
model transmissions over wireless channels, making the model more susceptible
to attacks from adversarial entities. Additionally, the local QFL model is
vulnerable to noise produced by the quantum device's intermediate noise states,
since it requires the use of quantum gates and circuits for training. This
local noise becomes intertwined with learning parameters during training,
impairing model precision and convergence rate. To address these issues, we
propose a new QFL technique that incorporates differential privacy and
introduces a dedicated noise estimation strategy to quantify and mitigate the
impact of intermediate quantum noise. Furthermore, we design an adaptive noise
generation scheme to alleviate privacy threats associated with the vanishing
gradient variance phenomenon of QNN and enhance robustness against device
noise. Experimental results demonstrate that our algorithm effectively balances
convergence, reduces communication costs, and mitigates the adverse effects of
intermediate quantum noise while maintaining strong privacy protection. Using
real-world datasets, we achieved test accuracy of up to 98.47\% for the MNIST
dataset and 83.85\% for the CIFAR-10 dataset while maintaining fast execution
times.</p>
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
  <h3><a href="http://arxiv.org/abs/2509.05376v1">Privacy Preservation and Identity Tracing Prevention in AI-Driven Eye
  Tracking for Interactive Learning Environments</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-09-04T13:08:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abdul Rehman, Are Dæhlen, Ilona Heldal, Jerry Chun-wei Lin</p>
    <p><b>Summary:</b> Eye-tracking technology can aid in understanding neurodevelopmental disorders
and tracing a person's identity. However, this technology poses a significant
risk to privacy, as it captures sensitive information about individuals and
increases the likelihood that data can be traced back to them. This paper
proposes a human-centered framework designed to prevent identity backtracking
while preserving the pedagogical benefits of AI-powered eye tracking in
interactive learning environments. We explore how real-time data anonymization,
ethical design principles, and regulatory compliance (such as GDPR) can be
integrated to build trust and transparency. We first demonstrate the potential
for backtracking student IDs and diagnoses in various scenarios using serious
game-based eye-tracking data. We then provide a two-stage privacy-preserving
framework that prevents participants from being tracked while still enabling
diagnostic classification. The first phase covers four scenarios: I) Predicting
disorder diagnoses based on different game levels. II) Predicting student IDs
based on different game levels. III) Predicting student IDs based on randomized
data. IV) Utilizing K-Means for out-of-sample data. In the second phase, we
present a two-stage framework that preserves privacy. We also employ Federated
Learning (FL) across multiple clients, incorporating a secure identity
management system with dummy IDs and administrator-only access controls. In the
first phase, the proposed framework achieved 99.3% accuracy for scenario 1, 63%
accuracy for scenario 2, and 99.7% accuracy for scenario 3, successfully
identifying and assigning a new student ID in scenario 4. In phase 2, we
effectively prevented backtracking and established a secure identity management
system with dummy IDs and administrator-only access controls, achieving an
overall accuracy of 99.40%.</p>
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
  <h3><a href="http://arxiv.org/abs/2509.05362v1">AI-in-the-Loop: Privacy Preserving Real-Time Scam Detection and
  Conversational Scambaiting by Leveraging LLMs and Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B">
  <p><b>Published on:</b> 2025-09-04T00:19:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ismail Hossain, Sai Puppala, Sajedul Talukder, Md Jahangir Alam</p>
    <p><b>Summary:</b> Scams exploiting real-time social engineering -- such as phishing,
impersonation, and phone fraud -- remain a persistent and evolving threat
across digital platforms. Existing defenses are largely reactive, offering
limited protection during active interactions. We propose a privacy-preserving,
AI-in-the-loop framework that proactively detects and disrupts scam
conversations in real time. The system combines instruction-tuned artificial
intelligence with a safety-aware utility function that balances engagement with
harm minimization, and employs federated learning to enable continual model
updates without raw data sharing. Experimental evaluations show that the system
produces fluent and engaging responses (perplexity as low as 22.3, engagement
$\approx$0.80), while human studies confirm significant gains in realism,
safety, and effectiveness over strong baselines. In federated settings, models
trained with FedAvg sustain up to 30 rounds while preserving high engagement
($\approx$0.80), strong relevance ($\approx$0.74), and low PII leakage
($\leq$0.0085). Even with differential privacy, novelty and safety remain
stable, indicating that robust privacy can be achieved without sacrificing
performance. The evaluation of guard models (LlamaGuard, LlamaGuard2/3,
MD-Judge) shows a straightforward pattern: stricter moderation settings reduce
the chance of exposing personal information, but they also limit how much the
model engages in conversation. In contrast, more relaxed settings allow longer
and richer interactions, which improve scam detection, but at the cost of
higher privacy risk. To our knowledge, this is the first framework to unify
real-time scam-baiting, federated privacy preservation, and calibrated safety
moderation into a proactive defense paradigm.</p>
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
  <h3><a href="http://arxiv.org/abs/2509.03294v2">A Comprehensive Guide to Differential Privacy: From Theory to User
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
  <h3><a href="http://arxiv.org/abs/2509.08835v1">Deep opacity and AI: A threat to XAI and to privacy protection
  mechanisms</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-30T11:15:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vincent C. Müller</p>
    <p><b>Summary:</b> It is known that big data analytics and AI pose a threat to privacy, and that
some of this is due to some kind of "black box problem" in AI. I explain how
this becomes a problem in the context of justification for judgments and
actions. Furthermore, I suggest distinguishing three kinds of opacity: 1) the
subjects do not know what the system does ("shallow opacity"), 2) the analysts
do not know what the system does ("standard black box opacity"), or 3) the
analysts cannot possibly know what the system might do ("deep opacity"). If the
agents, data subjects as well as analytics experts, operate under opacity, then
these agents cannot provide justifications for judgments that are necessary to
protect privacy, e.g., they cannot give "informed consent", or guarantee
"anonymity". It follows from these points that agents in big data analytics and
AI often cannot make the judgments needed to protect privacy. So I conclude
that big data analytics makes the privacy problems worse and the remedies less
effective. As a positive note, I provide a brief outlook on technical ways to
handle this situation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.05320v1">Privacy-Preserving Offloading for Large Language Models in 6G Vehicular
  Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-08-30T10:08:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ikhlasse Badidi, Nouhaila El Khiyaoui, Aya Riany, Badr Ben Elallid, Amine Abouaomar</p>
    <p><b>Summary:</b> The integration of Large Language Models (LLMs) in 6G vehicular networks
promises unprecedented advancements in intelligent transportation systems.
However, offloading LLM computations from vehicles to edge infrastructure poses
significant privacy risks, potentially exposing sensitive user data. This paper
presents a novel privacy-preserving offloading framework for LLM-integrated
vehicular networks. We introduce a hybrid approach combining federated learning
(FL) and differential privacy (DP) techniques to protect user data while
maintaining LLM performance. Our framework includes a privacy-aware task
partitioning algorithm that optimizes the trade-off between local and edge
computation, considering both privacy constraints and system efficiency. We
also propose a secure communication protocol for transmitting model updates and
aggregating results across the network. Experimental results demonstrate that
our approach achieves 75\% global accuracy with only a 2-3\% reduction compared
to non-privacy-preserving methods, while maintaining DP guarantees with an
optimal privacy budget of $\varepsilon = 0.8$. The framework shows stable
communication overhead of approximately 2.1MB per round with computation
comprising over 90\% of total processing time, validating its efficiency for
resource-constrained vehicular environments.</p>
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

