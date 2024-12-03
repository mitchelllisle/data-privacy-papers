
<h2>2024-10</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.24066v1">Cough-E: A multimodal, privacy-preserving cough detection algorithm for
  the edge</a></h3>
   
  <p><b>Published on:</b> 2024-10-31T16:00:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stefano Albini, Lara Orlandic, Jonathan Dan, Jérôme Thevenot, Tomas Teijeiro, Denisa Andreea Constantinescu, David Atienza</p>
    <p><b>Summary:</b> Continuous cough monitors can greatly aid doctors in home monitoring and
treatment of respiratory diseases. Although many algorithms have been proposed,
they still face limitations in data privacy and short-term monitoring. Edge-AI
offers a promising solution by processing privacy-sensitive data near the
source, but challenges arise in deploying resource-intensive algorithms on
constrained devices. From a suitable selection of audio and kinematic signals,
our methodology aims at the optimal selection of features via Recursive Feature
Elimination with Cross-Validation (RFECV), which exploits the explainability of
the selected XGB model. Additionally, it analyzes the use of Mel spectrogram
features, instead of the more common MFCC. Moreover, a set of hyperparameters
for a multimodal implementation of the classifier is explored. Finally, it
evaluates the performance based on clinically relevant event-based metrics. We
apply our methodology to develop Cough-E, an energy-efficient, multimodal and
edge AI cough detection algorithm. It exploits audio and kinematic data in two
distinct classifiers, jointly cooperating for a balanced energy and performance
trade-off. We demonstrate that our algorithm can be executed in real-time on an
ARM Cortex M33 microcontroller. Cough-E achieves a 70.56\% energy saving when
compared to the audio-only approach, at the cost of a 1.26\% relative
performance drop, resulting in a 0.78 F1-score. Both Cough-E and the edge-aware
model optimization methodology are publicly available as open-source code. This
approach demonstrates the benefits of the proposed hardware-aware methodology
to enable privacy-preserving cough monitors on the edge, paving the way to
efficient cough monitoring.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.23759v1">Converting BPMN Diagrams to Privacy Calculus</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Logic in Computer Science-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> 
  <p><b>Published on:</b> 2024-10-31T09:25:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Georgios V. Pitsiladis, Petros S. Stefaneas</p>
    <p><b>Summary:</b> The ecosystem of Privacy Calculus is a formal framework for privacy
comprising (a) the Privacy Calculus, a Turing-complete language of
message-exchanging processes based on the pi-calculus, (b) a privacy policy
language, and (c) a type checker that checks adherence of Privacy Calculus
terms to privacy policies. BPMN is a standard for the graphical description of
business processes which aims to be understandable by all business users, from
those with no technical background to those implementing software. This paper
presents how (a subset of) BPMN diagrams can be converted to Privacy Calculus
terms, in the hope that it will serve as a small piece of larger workflows for
building privacy-preserving software. The conversion is described
mathematically in the paper, but has also been implemented as a software tool.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.22784v1">Contrastive Learning and Adversarial Disentanglement for
  Privacy-Preserving Task-Oriented Semantic Communications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">  
  <p><b>Published on:</b> 2024-10-30T07:59:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Omar Erak, Omar Alhussein, Wen Tong</p>
    <p><b>Summary:</b> Task-oriented semantic communication systems have emerged as a promising
approach to achieving efficient and intelligent data transmission, where only
information relevant to a specific task is communicated. However, existing
methods struggle to fully disentangle task-relevant and task-irrelevant
information, leading to privacy concerns and subpar performance. To address
this, we propose an information-bottleneck method, named CLAD (contrastive
learning and adversarial disentanglement). CLAD leverages contrastive learning
to effectively capture task-relevant features while employing adversarial
disentanglement to discard task-irrelevant information. Additionally, due to
the lack of reliable and reproducible methods to gain insight into the
informativeness and minimality of the encoded feature vectors, we introduce a
new technique to compute the information retention index (IRI), a comparative
metric used as a proxy for the mutual information between the encoded features
and the input, reflecting the minimality of the encoded features. The IRI
quantifies the minimality and informativeness of the encoded feature vectors
across different task-oriented communication techniques. Our extensive
experiments demonstrate that CLAD outperforms state-of-the-art baselines in
terms of task performance, privacy preservation, and IRI. CLAD achieves a
predictive performance improvement of around 2.5-3%, along with a 77-90%
reduction in IRI and a 57-76% decrease in adversarial accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.22673v1">Calibrating Practical Privacy Risks for Differentially Private Machine
  Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-30T03:52:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuechun Gu, Keke Chen</p>
    <p><b>Summary:</b> Differential privacy quantifies privacy through the privacy budget
$\epsilon$, yet its practical interpretation is complicated by variations
across models and datasets. Recent research on differentially private machine
learning and membership inference has highlighted that with the same
theoretical $\epsilon$ setting, the likelihood-ratio-based membership inference
(LiRA) attacking success rate (ASR) may vary according to specific datasets and
models, which might be a better indicator for evaluating real-world privacy
risks. Inspired by this practical privacy measure, we study the approaches that
can lower the attacking success rate to allow for more flexible privacy budget
settings in model training. We find that by selectively suppressing
privacy-sensitive features, we can achieve lower ASR values without
compromising application-specific data utility. We use the SHAP and LIME model
explainer to evaluate feature sensitivities and develop feature-masking
strategies. Our findings demonstrate that the LiRA $ASR^M$ on model $M$ can
properly indicate the inherent privacy risk of a dataset for modeling, and it's
possible to modify datasets to enable the use of larger theoretical $\epsilon$
settings to achieve equivalent practical privacy protection. We have conducted
extensive experiments to show the inherent link between ASR and the dataset's
privacy risk. By carefully selecting features to mask, we can preserve more
data utility with equivalent practical privacy protection and relaxed
$\epsilon$ settings. The implementation details are shared online at the
provided GitHub URL
\url{https://anonymous.4open.science/r/On-sensitive-features-and-empirical-epsilon-lower-bounds-BF67/}.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.22651v1">FT-PrivacyScore: Personalized Privacy Scoring Service for Machine
  Learning Participation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-30T02:41:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuechun Gu, Jiajie He, Keke Chen</p>
    <p><b>Summary:</b> Training data privacy has been a top concern in AI modeling. While methods
like differentiated private learning allow data contributors to quantify
acceptable privacy loss, model utility is often significantly damaged. In
practice, controlled data access remains a mainstream method for protecting
data privacy in many industrial and research environments. In controlled data
access, authorized model builders work in a restricted environment to access
sensitive data, which can fully preserve data utility with reduced risk of data
leak. However, unlike differential privacy, there is no quantitative measure
for individual data contributors to tell their privacy risk before
participating in a machine learning task. We developed the demo prototype
FT-PrivacyScore to show that it's possible to efficiently and quantitatively
estimate the privacy risk of participating in a model fine-tuning task. The
demo source code will be available at
\url{https://github.com/RhincodonE/demo_privacy_scoring}.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.22623v1">PV-VTT: A Privacy-Centric Dataset for Mission-Specific Anomaly Detection
  and Natural Language Interpretation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-10-30T01:02:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ryozo Masukawa, Sanggeon Yun, Yoshiki Yamaguchi, Mohsen Imani</p>
    <p><b>Summary:</b> Video crime detection is a significant application of computer vision and
artificial intelligence. However, existing datasets primarily focus on
detecting severe crimes by analyzing entire video clips, often neglecting the
precursor activities (i.e., privacy violations) that could potentially prevent
these crimes. To address this limitation, we present PV-VTT (Privacy Violation
Video To Text), a unique multimodal dataset aimed at identifying privacy
violations. PV-VTT provides detailed annotations for both video and text in
scenarios. To ensure the privacy of individuals in the videos, we only provide
video feature vectors, avoiding the release of any raw video data. This
privacy-focused approach allows researchers to use the dataset while protecting
participant confidentiality. Recognizing that privacy violations are often
ambiguous and context-dependent, we propose a Graph Neural Network (GNN)-based
video description model. Our model generates a GNN-based prompt with image for
Large Language Model (LLM), which deliver cost-effective and high-quality video
descriptions. By leveraging a single video frame along with relevant text, our
method reduces the number of input tokens required, maintaining descriptive
quality while optimizing LLM API-usage. Extensive experiments validate the
effectiveness and interpretability of our approach in video description tasks
and flexibility of our PV-VTT dataset.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.22488v1">Privacy-Preserving Dynamic Assortment Selection</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-10-29T19:28:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Young Hyun Cho, Will Wei Sun</p>
    <p><b>Summary:</b> With the growing demand for personalized assortment recommendations, concerns
over data privacy have intensified, highlighting the urgent need for effective
privacy-preserving strategies. This paper presents a novel framework for
privacy-preserving dynamic assortment selection using the multinomial logit
(MNL) bandits model. Our approach employs a perturbed upper confidence bound
method, integrating calibrated noise into user utility estimates to balance
between exploration and exploitation while ensuring robust privacy protection.
We rigorously prove that our policy satisfies Joint Differential Privacy (JDP),
which better suits dynamic environments than traditional differential privacy,
effectively mitigating inference attack risks. This analysis is built upon a
novel objective perturbation technique tailored for MNL bandits, which is also
of independent interest. Theoretically, we derive a near-optimal regret bound
of $\tilde{O}(\sqrt{T})$ for our policy and explicitly quantify how privacy
protection impacts regret. Through extensive simulations and an application to
the Expedia hotel dataset, we demonstrate substantial performance enhancements
over the benchmark method.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.22235v1">Auditing $f$-Differential Privacy in One Run</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-29T17:02:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Saeed Mahloujifar, Luca Melis, Kamalika Chaudhuri</p>
    <p><b>Summary:</b> Empirical auditing has emerged as a means of catching some of the flaws in
the implementation of privacy-preserving algorithms. Existing auditing
mechanisms, however, are either computationally inefficient requiring multiple
runs of the machine learning algorithms or suboptimal in calculating an
empirical privacy. In this work, we present a tight and efficient auditing
procedure and analysis that can effectively assess the privacy of mechanisms.
Our approach is efficient; similar to the recent work of Steinke, Nasr, and
Jagielski (2023), our auditing procedure leverages the randomness of examples
in the input dataset and requires only a single run of the target mechanism.
And it is more accurate; we provide a novel analysis that enables us to achieve
tight empirical privacy estimates by using the hypothesized $f$-DP curve of the
mechanism, which provides a more accurate measure of privacy than the
traditional $\epsilon,\delta$ differential privacy parameters. We use our
auditing procure and analysis to obtain empirical privacy, demonstrating that
our auditing procedure delivers tighter privacy estimates.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.22108v1">Protecting Privacy in Multimodal Large Language Models with MLLMU-Bench</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-10-29T15:07:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zheyuan Liu, Guangyao Dou, Mengzhao Jia, Zhaoxuan Tan, Qingkai Zeng, Yongle Yuan, Meng Jiang</p>
    <p><b>Summary:</b> Generative models such as Large Language Models (LLM) and Multimodal Large
Language models (MLLMs) trained on massive web corpora can memorize and
disclose individuals' confidential and private data, raising legal and ethical
concerns. While many previous works have addressed this issue in LLM via
machine unlearning, it remains largely unexplored for MLLMs. To tackle this
challenge, we introduce Multimodal Large Language Model Unlearning Benchmark
(MLLMU-Bench), a novel benchmark aimed at advancing the understanding of
multimodal machine unlearning. MLLMU-Bench consists of 500 fictitious profiles
and 153 profiles for public celebrities, each profile feature over 14
customized question-answer pairs, evaluated from both multimodal (image+text)
and unimodal (text) perspectives. The benchmark is divided into four sets to
assess unlearning algorithms in terms of efficacy, generalizability, and model
utility. Finally, we provide baseline results using existing generative model
unlearning algorithms. Surprisingly, our experiments show that unimodal
unlearning algorithms excel in generation and cloze tasks, while multimodal
unlearning approaches perform better in classification tasks with multimodal
inputs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.21675v1">BF-Meta: Secure Blockchain-enhanced Privacy-preserving Federated
  Learning for Metaverse</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-10-29T02:52:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenbo Liu, Handi Chen, Edith C. H. Ngai</p>
    <p><b>Summary:</b> The metaverse, emerging as a revolutionary platform for social and economic
activities, provides various virtual services while posing security and privacy
challenges. Wearable devices serve as bridges between the real world and the
metaverse. To provide intelligent services without revealing users' privacy in
the metaverse, leveraging federated learning (FL) to train models on local
wearable devices is a promising solution. However, centralized model
aggregation in traditional FL may suffer from external attacks, resulting in a
single point of failure. Furthermore, the absence of incentive mechanisms may
weaken users' participation during FL training, leading to degraded performance
of the trained model and reduced quality of intelligent services. In this
paper, we propose BF-Meta, a secure blockchain-empowered FL framework with
decentralized model aggregation, to mitigate the negative influence of
malicious users and provide secure virtual services in the metaverse. In
addition, we design an incentive mechanism to give feedback to users based on
their behaviors. Experiments conducted on five datasets demonstrate the
effectiveness and applicability of BF-Meta.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.21605v2">Accelerating Privacy-Preserving Medical Record Linkage: A Three-Party
  MPC Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2024-10-28T23:13:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Şeyma Selcan Mağara, Noah Dietrich, Ali Burak Ünal, Mete Akgün</p>
    <p><b>Summary:</b> Record linkage is a crucial concept for integrating data from multiple
sources, particularly when datasets lack exact identifiers, and it has diverse
applications in real-world data analysis. Privacy-Preserving Record Linkage
(PPRL) ensures this integration occurs securely, protecting sensitive
information from unauthorized access. This is especially important in sectors
such as healthcare, where datasets include private identity information (IDAT)
governed by strict privacy laws. However, maintaining both privacy and
efficiency in large-scale record linkage poses significant challenges.
Consequently, researchers must develop advanced methods to protect data privacy
while optimizing processing performance. This paper presents a novel and
efficient PPRL method based on a secure 3-party computation (MPC) framework.
Our approach allows multiple parties to compute linkage results without
exposing their private inputs and significantly improves the speed of linkage
process compared to existing privacy-preserving solutions. We demonstrated that
our method preserves the linkage quality of the state-of-the-art PPRL method
while achieving up to 14 times faster performance. For example, linking a
record against a database of 10,000 records takes just 8.74 seconds in a
realistic network with 700 Mbps bandwidth and 60 ms latency. Even on a slower
internet connection with 100 Mbps bandwidth and 60 ms latency, the linkage
completes in 28 seconds, highlighting the scalability and efficiency of our
solution.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.21177v1">Privacy-Preserving for Images in Satellite Communications: A
  Comprehensive Review of Chaos-Based Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-28T16:17:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Farrukh Bin Rashid, Windhya Rankothge, Somayeh Sadeghi, Hesamodin Mohammadian, Ali Ghorbani</p>
    <p><b>Summary:</b> In an era where global connectivity has become critical, satellite
communication is essential for businesses, governments, and individuals. Widely
used services with satellite communication such as climate change monitoring,
military surveillance and real-time event broadcasting, involve data in the
form of images rather text. Therefore, securing image transmission in satellite
communication using efficient and effective encryption approaches, has gained a
significant attention from academia as well as the industry. In this paper, we
specifically focus on chaos based image encryption as one of the key
privacy-preserving techniques for satellite communication. While there are
several privacy enhancing techniques for protecting image data but chaos based
encryption has distinct advantages such as high flexibility, high security,
less computational overheads, less computing power and ease of implementation.
First, we present a solid background about satellite communication and image
encryption in satellite communication, covering theoretical aspects of chaotic
systems and their practical usage for image encryption. Next we present a
comprehensive literature review on all state-of-the-art studies specifically
for chaos based satellite image encryption, with a detailed analysis of the
evaluation process, including evaluation parameters and conditions. Finally, we
discuss about existing challenges and open research problems for chaos based
satellite image encryption.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.20555v1">Privacy-Enhanced Adaptive Authentication: User Profiling with Privacy
  Guarantees</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-27T19:11:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yaser Baseri, Abdelhakim Senhaji Hafid, Dimitrios Makrakis</p>
    <p><b>Summary:</b> User profiling is a critical component of adaptive risk-based authentication,
yet it raises significant privacy concerns, particularly when handling
sensitive data. Profiling involves collecting and aggregating various user
features, potentially creating quasi-identifiers that can reveal identities and
compromise privacy. Even anonymized profiling methods remain vulnerable to
re-identification attacks through these quasi-identifiers. This paper
introduces a novel privacy-enhanced adaptive authentication protocol that
leverages Oblivious Pseudorandom Functions (OPRF), anonymous tokens, and
Differential Privacy (DP) to provide robust privacy guarantees. Our proposed
approach dynamically adjusts authentication requirements based on real-time
risk assessments, enhancing security while safeguarding user privacy. By
integrating privacy considerations into the core of adaptive risk-based
adaptive authentication, this approach addresses a gap often overlooked in
traditional models. Advanced cryptographic techniques ensure confidentiality,
integrity, and unlinkability of user data, while differential privacy
mechanisms minimize the impact of individual data points on overall analysis.
Formal security and privacy proofs demonstrate the protocol's resilience
against various threats and its ability to provide strong privacy guarantees.
Additionally, a comprehensive performance evaluation reveals that the
computational and communication overheads are manageable, making the protocol
practical for real-world deployment. By adhering to data protection regulations
such as GDPR and CCPA, our protocol not only enhances security but also fosters
user trust and compliance with legal standards.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.20259v1">FL-DABE-BC: A Privacy-Enhanced, Decentralized Authentication, and Secure
  Communication for Federated Learning Framework with Decentralized
  Attribute-Based Encryption and Blockchain for IoT Scenarios</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-26T19:30:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sathwik Narkedimilli, Amballa Venkata Sriram, Satvik Raghav</p>
    <p><b>Summary:</b> This study proposes an advanced Federated Learning (FL) framework designed to
enhance data privacy and security in IoT environments by integrating
Decentralized Attribute-Based Encryption (DABE), Homomorphic Encryption (HE),
Secure Multi-Party Computation (SMPC), and Blockchain technology. Unlike
traditional FL, our framework enables secure, decentralized authentication and
encryption directly on IoT devices using DABE, allowing sensitive data to
remain locally encrypted. Homomorphic Encryption permits computations on
encrypted data, and SMPC ensures privacy in collaborative computations, while
Blockchain technology provides transparent, immutable record-keeping for all
transactions and model updates. Local model weights are encrypted and
transmitted to fog layers for aggregation using HE and SMPC, then iteratively
refined by the central server using differential privacy to safeguard against
data leakage. This secure, privacy-preserving FL framework delivers a robust
solution for efficient model training and real-time analytics across
distributed IoT devices, offering significant advancements in secure
decentralized learning for IoT applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.19941v1">Privacy without Noisy Gradients: Slicing Mechanism for Generative Model
  Training</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-25T19:32:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kristjan Greenewald, Yuancheng Yu, Hao Wang, Kai Xu</p>
    <p><b>Summary:</b> Training generative models with differential privacy (DP) typically involves
injecting noise into gradient updates or adapting the discriminator's training
procedure. As a result, such approaches often struggle with hyper-parameter
tuning and convergence. We consider the slicing privacy mechanism that injects
noise into random low-dimensional projections of the private data, and provide
strong privacy guarantees for it. These noisy projections are used for training
generative models. To enable optimizing generative models using this DP
approach, we introduce the smoothed-sliced $f$-divergence and show it enjoys
statistical consistency. Moreover, we present a kernel-based estimator for this
divergence, circumventing the need for adversarial training. Extensive
numerical experiments demonstrate that our approach can generate synthetic data
of higher quality compared with baselines. Beyond performance improvement, our
method, by sidestepping the need for noisy gradients, offers data scientists
the flexibility to adjust generator architecture and hyper-parameters, run the
optimization over any number of epochs, and even restart the optimization
process -- all without incurring additional privacy costs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.19917v1">Collaborative Inference over Wireless Channels with Feature Differential
  Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2024-10-25T18:11:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohamed Seif, Yuqi Nie, Andrea J. Goldsmith, H. Vincent Poor</p>
    <p><b>Summary:</b> Collaborative inference among multiple wireless edge devices has the
potential to significantly enhance Artificial Intelligence (AI) applications,
particularly for sensing and computer vision. This approach typically involves
a three-stage process: a) data acquisition through sensing, b) feature
extraction, and c) feature encoding for transmission. However, transmitting the
extracted features poses a significant privacy risk, as sensitive personal data
can be exposed during the process. To address this challenge, we propose a
novel privacy-preserving collaborative inference mechanism, wherein each edge
device in the network secures the privacy of extracted features before
transmitting them to a central server for inference. Our approach is designed
to achieve two primary objectives: 1) reducing communication overhead and 2)
ensuring strict privacy guarantees during feature transmission, while
maintaining effective inference performance. Additionally, we introduce an
over-the-air pooling scheme specifically designed for classification tasks,
which provides formal guarantees on the privacy of transmitted features and
establishes a lower bound on classification accuracy.</p>
  </details>
</div>



<h2>2024-11</h2>

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
  <h3><a href="http://arxiv.org/abs/2411.12766v1">Exploiting the Uncoordinated Privacy Protections of Eye Tracking and VR
  Motion Data for Unauthorized User Identification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-11-17T22:16:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Samantha Aziz, Oleg Komogortsev</p>
    <p><b>Summary:</b> Virtual reality (VR) devices use a variety of sensors to capture a rich body
of user-generated data, which can be misused by malicious parties to covertly
infer information about the user. Privacy-enhancing techniques seek to reduce
the amount of personally identifying information in sensor data, but these
techniques are typically developed for a subset of data streams that are
available on the platform, without consideration for the auxiliary information
that may be readily available from other sensors. In this paper, we evaluate
whether body motion data can be used to circumvent the privacy protections
applied to eye tracking data to enable user identification on a VR platform,
and vice versa. We empirically show that eye tracking, headset tracking, and
hand tracking data are not only informative for inferring user identity on
their own, but contain complementary information that can increase the rate of
successful user identification. Most importantly, we demonstrate that applying
privacy protections to only a subset of the data available in VR can create an
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


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.05483v1">The Limits of Differential Privacy in Online Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-11-08T11:21:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bo Li, Wei Wang, Peng Ye</p>
    <p><b>Summary:</b> Differential privacy (DP) is a formal notion that restricts the privacy
leakage of an algorithm when running on sensitive data, in which
privacy-utility trade-off is one of the central problems in private data
analysis. In this work, we investigate the fundamental limits of differential
privacy in online learning algorithms and present evidence that separates three
types of constraints: no DP, pure DP, and approximate DP. We first describe a
hypothesis class that is online learnable under approximate DP but not online
learnable under pure DP under the adaptive adversarial setting. This indicates
that approximate DP must be adopted when dealing with adaptive adversaries. We
then prove that any private online learner must make an infinite number of
mistakes for almost all hypothesis classes. This essentially generalizes
previous results and shows a strong separation between private and non-private
settings since a finite mistake bound is always attainable (as long as the
class is online learnable) when there is no privacy requirement.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.05320v1">Privacy Protection Framework against Unauthorized Sensing in the 5.8 GHz
  ISM Band</a></h3>
  
  <p><b>Published on:</b> 2024-11-08T04:25:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zexin Fang, Bin Han, Hans D. Schotten</p>
    <p><b>Summary:</b> Unauthorized sensing activities pose an increasing threat to individual
privacy, particularly in the industrial, scientific, and medical (ISM) band
where regulatory frameworks remain limited. This paper presents a novel signal
process methodology to monitor and counter unauthorized sensing activities.
Specifically, we model the pedestrian trajectories as a random process. Then,
we leverage the Cram\'er-Rao bound (CRB) to evaluate sensing performance and
model it as sampling error of such a random process. Through simulation, we
verify the accuracy of monitoring unauthorized sensing activities in urban
scenarios, and validate the effectiveness of corresponding mitigation
strategies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.05167v1">EPIC: Enhancing Privacy through Iterative Collaboration</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-11-07T20:10:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Prakash Chourasia, Heramb Lonkar, Sarwan Ali, Murray Patterson</p>
    <p><b>Summary:</b> Advancements in genomics technology lead to a rising volume of viral (e.g.,
SARS-CoV-2) sequence data, resulting in increased usage of machine learning
(ML) in bioinformatics. Traditional ML techniques require centralized data
collection and processing, posing challenges in realistic healthcare scenarios.
Additionally, privacy, ownership, and stringent regulation issues exist when
pooling medical data into centralized storage to train a powerful deep learning
(DL) model. The Federated learning (FL) approach overcomes such issues by
setting up a central aggregator server and a shared global model. It also
facilitates data privacy by extracting knowledge while keeping the actual data
private. This work proposes a cutting-edge Privacy enhancement through
Iterative Collaboration (EPIC) architecture. The network is divided and
distributed between local and centralized servers. We demonstrate the EPIC
approach to resolve a supervised classification problem to estimate SARS-CoV-2
genomic sequence data lineage without explicitly transferring raw sequence
data. We aim to create a universal decentralized optimization framework that
allows various data holders to work together and converge to a single
predictive model. The findings demonstrate that privacy-preserving strategies
can be successfully used with aggregation approaches without materially
altering the degree of learning convergence. Finally, we highlight a few
potential issues and prospects for study in FL-based approaches to healthcare
applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.04710v1">Differential Privacy Overview and Fundamental Techniques</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-11-07T13:52:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ferdinando Fioretto, Pascal Van Hentenryck, Juba Ziani</p>
    <p><b>Summary:</b> This chapter is meant to be part of the book "Differential Privacy in
Artificial Intelligence: From Theory to Practice" and provides an introduction
to Differential Privacy. It starts by illustrating various attempts to protect
data privacy, emphasizing where and why they failed, and providing the key
desiderata of a robust privacy definition. It then defines the key actors,
tasks, and scopes that make up the domain of privacy-preserving data analysis.
Following that, it formalizes the definition of Differential Privacy and its
inherent properties, including composition, post-processing immunity, and group
privacy. The chapter also reviews the basic techniques and mechanisms commonly
used to implement Differential Privacy in its pure and approximate forms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.04509v1">FedDP: Privacy-preserving method based on federated learning for
  histopathology image segmentation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-11-07T08:02:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Liangrui Pan, Mao Huang, Lian Wang, Pinle Qin, Shaoliang Peng</p>
    <p><b>Summary:</b> Hematoxylin and Eosin (H&E) staining of whole slide images (WSIs) is
considered the gold standard for pathologists and medical practitioners for
tumor diagnosis, surgical planning, and post-operative assessment. With the
rapid advancement of deep learning technologies, the development of numerous
models based on convolutional neural networks and transformer-based models has
been applied to the precise segmentation of WSIs. However, due to privacy
regulations and the need to protect patient confidentiality, centralized
storage and processing of image data are impractical. Training a centralized
model directly is challenging to implement in medical settings due to these
privacy concerns.This paper addresses the dispersed nature and privacy
sensitivity of medical image data by employing a federated learning framework,
allowing medical institutions to collaboratively learn while protecting patient
privacy. Additionally, to address the issue of original data reconstruction
through gradient inversion during the federated learning training process,
differential privacy introduces noise into the model updates, preventing
attackers from inferring the contributions of individual samples, thereby
protecting the privacy of the training data.Experimental results show that the
proposed method, FedDP, minimally impacts model accuracy while effectively
safeguarding the privacy of cancer pathology image data, with only a slight
decrease in Dice, Jaccard, and Acc indices by 0.55%, 0.63%, and 0.42%,
respectively. This approach facilitates cross-institutional collaboration and
knowledge sharing while protecting sensitive data privacy, providing a viable
solution for further research and application in the medical field.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.04490v1">Smoke Screens and Scapegoats: The Reality of General Data Protection
  Regulation Compliance -- Privacy and Ethics in the Case of Replika AI</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-11-07T07:36:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joni-Roy Piispanen, Tinja Myllyviita, Ville Vakkuri, Rebekah Rousi</p>
    <p><b>Summary:</b> Currently artificial intelligence (AI)-enabled chatbots are capturing the
hearts and imaginations of the public at large. Chatbots that users can build
and personalize, as well as pre-designed avatars ready for users' selection,
all of these are on offer in applications to provide social companionship,
friends and even love. These systems, however, have demonstrated challenges on
the privacy and ethics front. This paper takes a critical approach towards
examining the intricacies of these issues within AI companion services. We
chose Replika as a case and employed close reading to examine the service's
privacy policy. We additionally analyze articles from public media about the
company and its practices to gain insight into the trustworthiness and
integrity of the information provided in the policy. The aim is to ascertain
whether seeming General Data Protection Regulation (GDPR) compliance equals
reliability of required information, or whether the area of GDPR compliance in
itself is one riddled with ethical challenges. The paper contributes to a
growing body of scholarship on ethics and privacy related matters in the sphere
of social chatbots. The results reveal that despite privacy notices, data
collection practices might harvest personal data without users' full awareness.
Cross-textual comparison reveals that privacy notice information does not fully
correspond with other information sources.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.05034v1">Mitigating Privacy Risks in LLM Embeddings from Embedding Inversion</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-11-06T14:42:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tiantian Liu, Hongwei Yao, Tong Wu, Zhan Qin, Feng Lin, Kui Ren, Chun Chen</p>
    <p><b>Summary:</b> Embeddings have become a cornerstone in the functionality of large language
models (LLMs) due to their ability to transform text data into rich, dense
numerical representations that capture semantic and syntactic properties. These
embedding vector databases serve as the long-term memory of LLMs, enabling
efficient handling of a wide range of natural language processing tasks.
However, the surge in popularity of embedding vector databases in LLMs has been
accompanied by significant concerns about privacy leakage. Embedding vector
databases are particularly vulnerable to embedding inversion attacks, where
adversaries can exploit the embeddings to reverse-engineer and extract
sensitive information from the original text data. Existing defense mechanisms
have shown limitations, often struggling to balance security with the
performance of downstream tasks. To address these challenges, we introduce
Eguard, a novel defense mechanism designed to mitigate embedding inversion
attacks. Eguard employs a transformer-based projection network and text mutual
information optimization to safeguard embeddings while preserving the utility
of LLMs. Our approach significantly reduces privacy risks, protecting over 95%
of tokens from inversion while maintaining high performance across downstream
tasks consistent with original embeddings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.03914v1">Game-Theoretic Machine Unlearning: Mitigating Extra Privacy Leakage</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-11-06T13:47:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hengzhu Liu, Tianqing Zhu, Lefeng Zhang, Ping Xiong</p>
    <p><b>Summary:</b> With the extensive use of machine learning technologies, data providers
encounter increasing privacy risks. Recent legislation, such as GDPR, obligates
organizations to remove requested data and its influence from a trained model.
Machine unlearning is an emerging technique designed to enable machine learning
models to erase users' private information. Although several efficient machine
unlearning schemes have been proposed, these methods still have limitations.
First, removing the contributions of partial data may lead to model performance
degradation. Second, discrepancies between the original and generated unlearned
models can be exploited by attackers to obtain target sample's information,
resulting in additional privacy leakage risks. To address above challenges, we
proposed a game-theoretic machine unlearning algorithm that simulates the
competitive relationship between unlearning performance and privacy protection.
This algorithm comprises unlearning and privacy modules. The unlearning module
possesses a loss function composed of model distance and classification error,
which is used to derive the optimal strategy. The privacy module aims to make
it difficult for an attacker to infer membership information from the unlearned
data, thereby reducing the privacy leakage risk during the unlearning process.
Additionally, the experimental results on real-world datasets demonstrate that
this game-theoretic unlearning algorithm's effectiveness and its ability to
generate an unlearned model with a performance similar to that of the retrained
one while mitigating extra privacy leakage risks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.03847v1">A Novel Access Control and Privacy-Enhancing Approach for Models in Edge
  Computing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-11-06T11:37:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Peihao Li</p>
    <p><b>Summary:</b> With the widespread adoption of edge computing technologies and the
increasing prevalence of deep learning models in these environments, the
security risks and privacy threats to models and data have grown more acute.
Attackers can exploit various techniques to illegally obtain models or misuse
data, leading to serious issues such as intellectual property infringement and
privacy breaches. Existing model access control technologies primarily rely on
traditional encryption and authentication methods; however, these approaches
exhibit significant limitations in terms of flexibility and adaptability in
dynamic environments. Although there have been advancements in model
watermarking techniques for marking model ownership, they remain limited in
their ability to proactively protect intellectual property and prevent
unauthorized access. To address these challenges, we propose a novel model
access control method tailored for edge computing environments. This method
leverages image style as a licensing mechanism, embedding style recognition
into the model's operational framework to enable intrinsic access control.
Consequently, models deployed on edge platforms are designed to correctly infer
only on license data with specific style, rendering them ineffective on any
other data. By restricting the input data to the edge model, this approach not
only prevents attackers from gaining unauthorized access to the model but also
enhances the privacy of data on terminal devices. We conducted extensive
experiments on benchmark datasets, including MNIST, CIFAR-10, and FACESCRUB,
and the results demonstrate that our method effectively prevents unauthorized
access to the model while maintaining accuracy. Additionally, the model shows
strong resistance against attacks such as forged licenses and fine-tuning.
These results underscore the method's usability, security, and robustness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.03730v1">NeurIPS 2023 Competition: Privacy Preserving Federated Learning Document
  VQA</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-11-06T07:51:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marlon Tobaben, Mohamed Ali Souibgui, Rubèn Tito, Khanh Nguyen, Raouf Kerkouche, Kangsoo Jung, Joonas Jälkö, Lei Kang, Andrey Barsky, Vincent Poulain d'Andecy, Aurélie Joseph, Aashiq Muhamed, Kevin Kuo, Virginia Smith, Yusuke Yamasaki, Takumi Fukami, Kenta Niwa, Iifan Tyou, Hiro Ishii, Rio Yokota, Ragul N, Rintu Kutum, Josep Llados, Ernest Valveny, Antti Honkela, Mario Fritz, Dimosthenis Karatzas</p>
    <p><b>Summary:</b> The Privacy Preserving Federated Learning Document VQA (PFL-DocVQA)
competition challenged the community to develop provably private and
communication-efficient solutions in a federated setting for a real-life use
case: invoice processing. The competition introduced a dataset of real invoice
documents, along with associated questions and answers requiring information
extraction and reasoning over the document images. Thereby, it brings together
researchers and expertise from the document analysis, privacy, and federated
learning communities. Participants fine-tuned a pre-trained, state-of-the-art
Document Visual Question Answering model provided by the organizers for this
new domain, mimicking a typical federated invoice processing setup. The base
model is a multi-modal generative language model, and sensitive information
could be exposed through either the visual or textual input modality.
Participants proposed elegant solutions to reduce communication costs while
maintaining a minimum utility threshold in track 1 and to protect all
information from each document provider using differential privacy in track 2.
The competition served as a new testbed for developing and testing private
federated learning methods, simultaneously raising awareness about privacy
within the document image analysis and recognition community. Ultimately, the
competition analysis provides best practices and recommendations for
successfully running privacy-focused federated learning challenges in the
future.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.03633v1">Privacy-Preserving Resilient Vector Consensus</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2024-11-06T03:17:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bing Liu, Chengcheng Zhao, Li Chai, Peng Cheng, Jiming Chen</p>
    <p><b>Summary:</b> This paper studies privacy-preserving resilient vector consensus in
multi-agent systems against faulty agents, where normal agents can achieve
consensus within the convex hull of their initial states while protecting state
vectors from being disclosed. Specifically, we consider a modification of an
existing algorithm known as Approximate Distributed Robust Convergence Using
Centerpoints (ADRC), i.e., Privacy-Preserving ADRC (PP-ADRC). Under PP-ADRC,
each normal agent introduces multivariate Gaussian noise to its state during
each iteration. We first provide sufficient conditions to ensure that all
normal agents' states can achieve mean square convergence under PP-ADRC. Then,
we analyze convergence accuracy from two perspectives, i.e., the Mahalanobis
distance of the final value from its expectation and the Hausdorff distance
based alteration of the convex hull caused by noise when only partial
dimensions are added with noise. Then, we employ concentrated geo-privacy to
characterize privacy preservation and conduct a thorough comparison with
differential privacy. Finally, numerical simulations demonstrate the
theoretical results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.03582v1">Privacy Preserving Mechanisms for Coordinating Airspace Usage in
  Advanced Air Mobility</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36"> 
  <p><b>Published on:</b> 2024-11-06T00:47:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chinmay Maheshwari, Maria G. Mendoza, Victoria Marie Tuck, Pan-Yang Su, Victor L. Qin, Sanjit A. Seshia, Hamsa Balakrishnan, Shankar Sastry</p>
    <p><b>Summary:</b> Advanced Air Mobility (AAM) operations are expected to transform air
transportation while challenging current air traffic management practices. By
introducing a novel market-based mechanism, we address the problem of on-demand
allocation of capacity-constrained airspace to AAM vehicles with heterogeneous
and private valuations. We model airspace and air infrastructure as a
collection of contiguous regions with constraints on the number of vehicles
that simultaneously enter, stay, or exit each region. Vehicles request access
to the airspace with trajectories spanning multiple regions at different times.
We use the graph structure of our airspace model to formulate the allocation
problem as a path allocation problem on a time-extended graph. To ensure the
cost information of AAM vehicles remains private, we introduce a novel
mechanism that allocates each vehicle a budget of "air-credits" and anonymously
charges prices for traversing the edges of the time-extended graph. We seek to
compute a competitive equilibrium that ensures that: (i) capacity constraints
are satisfied, (ii) a strictly positive resource price implies that the sector
capacity is fully utilized, and (iii) the allocation is integral and optimal
for each AAM vehicle given current prices, without requiring access to
individual vehicle utilities. However, a competitive equilibrium with integral
allocations may not always exist. We provide sufficient conditions for the
existence and computation of a fractional-competitive equilibrium, where
allocations can be fractional. Building on these theoretical insights, we
propose a distributed, iterative, two-step algorithm that: 1) computes a
fractional competitive equilibrium, and 2) derives an integral allocation from
this equilibrium. We validate the effectiveness of our approach in allocating
trajectories for two emerging urban air mobility services: drone delivery and
air taxis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.03053v1">Gradient-Guided Conditional Diffusion Models for Private Image
  Reconstruction: Analyzing Adversarial Impacts of Differential Privacy and
  Denoising</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-11-05T12:39:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tao Huang, Jiayang Meng, Hong Chen, Guolong Zheng, Xu Yang, Xun Yi, Hua Wang</p>
    <p><b>Summary:</b> We investigate the construction of gradient-guided conditional diffusion
models for reconstructing private images, focusing on the adversarial interplay
between differential privacy noise and the denoising capabilities of diffusion
models. While current gradient-based reconstruction methods struggle with
high-resolution images due to computational complexity and prior knowledge
requirements, we propose two novel methods that require minimal modifications
to the diffusion model's generation process and eliminate the need for prior
knowledge. Our approach leverages the strong image generation capabilities of
diffusion models to reconstruct private images starting from randomly generated
noise, even when a small amount of differentially private noise has been added
to the gradients. We also conduct a comprehensive theoretical analysis of the
impact of differential privacy noise on the quality of reconstructed images,
revealing the relationship among noise magnitude, the architecture of attacked
models, and the attacker's reconstruction capability. Additionally, extensive
experiments validate the effectiveness of our proposed methods and the accuracy
of our theoretical findings, suggesting new directions for privacy risk
auditing using conditional diffusion models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.02926v2">Privacy-Preserving Graph-Based Machine Learning with Fully Homomorphic
  Encryption for Collaborative Anti-Money Laundering</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-11-05T09:13:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fabrianne Effendi, Anupam Chattopadhyay</p>
    <p><b>Summary:</b> Combating money laundering has become increasingly complex with the rise of
cybercrime and digitalization of financial transactions. Graph-based machine
learning techniques have emerged as promising tools for Anti-Money Laundering
(AML) detection, capturing intricate relationships within money laundering
networks. However, the effectiveness of AML solutions is hindered by data silos
within financial institutions, limiting collaboration and overall efficacy.
This research presents a novel privacy-preserving approach for collaborative
AML machine learning, facilitating secure data sharing across institutions and
borders while preserving privacy and regulatory compliance. Leveraging Fully
Homomorphic Encryption (FHE), computations are directly performed on encrypted
data, ensuring the confidentiality of financial data. Notably, FHE over the
Torus (TFHE) was integrated with graph-based machine learning using Zama
Concrete ML. The research contributes two key privacy-preserving pipelines.
First, the development of a privacy-preserving Graph Neural Network (GNN)
pipeline was explored. Optimization techniques like quantization and pruning
were used to render the GNN FHE-compatible. Second, a privacy-preserving
graph-based XGBoost pipeline leveraging Graph Feature Preprocessor (GFP) was
successfully developed. Experiments demonstrated strong predictive performance,
with the XGBoost model consistently achieving over 99% accuracy, F1-score,
precision, and recall on the balanced AML dataset in both unencrypted and
FHE-encrypted inference settings. On the imbalanced dataset, the incorporation
of graph-based features improved the F1-score by 8%. The research highlights
the need to balance the trade-off between privacy and computational efficiency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.02622v1">Pseudo-Probability Unlearning: Towards Efficient and Privacy-Preserving
  Machine Unlearning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-11-04T21:27:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zihao Zhao, Yijiang Li, Yuchen Yang, Wenqing Zhang, Nuno Vasconcelos, Yinzhi Cao</p>
    <p><b>Summary:</b> Machine unlearning--enabling a trained model to forget specific data--is
crucial for addressing biased data and adhering to privacy regulations like the
General Data Protection Regulation (GDPR)'s "right to be forgotten". Recent
works have paid little attention to privacy concerns, leaving the data intended
for forgetting vulnerable to membership inference attacks. Moreover, they often
come with high computational overhead. In this work, we propose
Pseudo-Probability Unlearning (PPU), a novel method that enables models to
forget data efficiently and in a privacy-preserving manner. Our method replaces
the final-layer output probabilities of the neural network with
pseudo-probabilities for the data to be forgotten. These pseudo-probabilities
follow either a uniform distribution or align with the model's overall
distribution, enhancing privacy and reducing risk of membership inference
attacks. Our optimization strategy further refines the predictive probability
distributions and updates the model's weights accordingly, ensuring effective
forgetting with minimal impact on the model's overall performance. Through
comprehensive experiments on multiple benchmarks, our method achieves over 20%
improvements in forgetting error compared to the state-of-the-art.
Additionally, our method enhances privacy by preventing the forgotten set from
being inferred to around random guesses.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.03351v1">Tabular Data Synthesis with Differential Privacy: A Survey</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2024-11-04T06:32:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mengmeng Yang, Chi-Hung Chi, Kwok-Yan Lam, Jie Feng, Taolin Guo, Wei Ni</p>
    <p><b>Summary:</b> Data sharing is a prerequisite for collaborative innovation, enabling
organizations to leverage diverse datasets for deeper insights. In real-world
applications like FinTech and Smart Manufacturing, transactional data, often in
tabular form, are generated and analyzed for insight generation. However, such
datasets typically contain sensitive personal/business information, raising
privacy concerns and regulatory risks. Data synthesis tackles this by
generating artificial datasets that preserve the statistical characteristics of
real data, removing direct links to individuals. However, attackers can still
infer sensitive information using background knowledge. Differential privacy
offers a solution by providing provable and quantifiable privacy protection.
Consequently, differentially private data synthesis has emerged as a promising
approach to privacy-aware data sharing. This paper provides a comprehensive
overview of existing differentially private tabular data synthesis methods,
highlighting the unique challenges of each generation model for generating
tabular data under differential privacy constraints. We classify the methods
into statistical and deep learning-based approaches based on their generation
models, discussing them in both centralized and distributed environments. We
evaluate and compare those methods within each category, highlighting their
strengths and weaknesses in terms of utility, privacy, and computational
complexity. Additionally, we present and discuss various evaluation methods for
assessing the quality of the synthesized data, identify research gaps in the
field and directions for future research.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.01583v1">Trustworthy Federated Learning: Privacy, Security, and Beyond</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-11-03T14:18:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chunlu Chen, Ji Liu, Haowen Tan, Xingjian Li, Kevin I-Kai Wang, Peng Li, Kouichi Sakurai, Dejing Dou</p>
    <p><b>Summary:</b> While recent years have witnessed the advancement in big data and Artificial
Intelligence (AI), it is of much importance to safeguard data privacy and
security. As an innovative approach, Federated Learning (FL) addresses these
concerns by facilitating collaborative model training across distributed data
sources without transferring raw data. However, the challenges of robust
security and privacy across decentralized networks catch significant attention
in dealing with the distributed data in FL. In this paper, we conduct an
extensive survey of the security and privacy issues prevalent in FL,
underscoring the vulnerability of communication links and the potential for
cyber threats. We delve into various defensive strategies to mitigate these
risks, explore the applications of FL across different sectors, and propose
research directions. We identify the intricate security challenges that arise
within the FL frameworks, aiming to contribute to the development of secure and
efficient FL systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.01471v1">A Practical and Privacy-Preserving Framework for Real-World Large
  Language Model Services</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-11-03T07:40:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yu Mao, Xueping Liao, Wei Liu, Anjia Yang</p>
    <p><b>Summary:</b> Large language models (LLMs) have demonstrated exceptional capabilities in
text understanding and generation, and they are increasingly being utilized
across various domains to enhance productivity. However, due to the high costs
of training and maintaining these models, coupled with the fact that some LLMs
are proprietary, individuals often rely on online AI as a Service (AIaaS)
provided by LLM companies. This business model poses significant privacy risks,
as service providers may exploit users' trace patterns and behavioral data. In
this paper, we propose a practical and privacy-preserving framework that
ensures user anonymity by preventing service providers from linking requests to
the individuals who submit them. Our framework is built on partially blind
signatures, which guarantee the unlinkability of user requests. Furthermore, we
introduce two strategies tailored to both subscription-based and API-based
service models, ensuring the protection of both users' privacy and service
providers' interests. The framework is designed to integrate seamlessly with
existing LLM systems, as it does not require modifications to the underlying
architectures. Experimental results demonstrate that our framework incurs
minimal computation and communication overhead, making it a feasible solution
for real-world applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.01447v1">Privacy-Preserving Customer Churn Prediction Model in the Context of
  Telecommunication Industry</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-11-03T06:08:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joydeb Kumar Sana, M Sohel Rahman, M Saifur Rahman</p>
    <p><b>Summary:</b> Data is the main fuel of a successful machine learning model. A dataset may
contain sensitive individual records e.g. personal health records, financial
data, industrial information, etc. Training a model using this sensitive data
has become a new privacy concern when someone uses third-party cloud computing.
Trained models also suffer privacy attacks which leads to the leaking of
sensitive information of the training data. This study is conducted to preserve
the privacy of training data in the context of customer churn prediction
modeling for the telecommunications industry (TCI). In this work, we propose a
framework for privacy-preserving customer churn prediction (PPCCP) model in the
cloud environment. We have proposed a novel approach which is a combination of
Generative Adversarial Networks (GANs) and adaptive Weight-of-Evidence (aWOE).
Synthetic data is generated from GANs, and aWOE is applied on the synthetic
training dataset before feeding the data to the classification algorithms. Our
experiments were carried out using eight different machine learning (ML)
classifiers on three openly accessible datasets from the telecommunication
sector. We then evaluated the performance using six commonly employed
evaluation metrics. In addition to presenting a data privacy analysis, we also
performed a statistical significance test. The training and prediction
processes achieve data privacy and the prediction classifiers achieve high
prediction performance (87.1\% in terms of F-Measure for GANs-aWOE based
Na\"{\i}ve Bayes model). In contrast to earlier studies, our suggested approach
demonstrates a prediction enhancement of up to 28.9\% and 27.9\% in terms of
accuracy and F-measure, respectively.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.01357v2">WaKA: Data Attribution using K-Nearest Neighbors and Membership Privacy
  Principles</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-11-02T20:27:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Patrick Mesana, Clément Bénesse, Hadrien Lautraite, Gilles Caporossi, Sébastien Gambs</p>
    <p><b>Summary:</b> In this paper, we introduce WaKA (Wasserstein K-nearest-neighbors
Attribution), a novel attribution method that leverages principles from the
LiRA (Likelihood Ratio Attack) framework and k-nearest neighbors classifiers
(k-NN). WaKA efficiently measures the contribution of individual data points to
the model's loss distribution, analyzing every possible k-NN that can be
constructed using the training set, without requiring to sample subsets of the
training set. WaKA is versatile and can be used a posteriori as a membership
inference attack (MIA) to assess privacy risks or a priori for privacy
influence measurement and data valuation. Thus, WaKA can be seen as bridging
the gap between data attribution and membership inference attack (MIA) by
providing a unified framework to distinguish between a data point's value and
its privacy risk. For instance, we have shown that self-attribution values are
more strongly correlated with the attack success rate than the contribution of
a point to the model generalization. WaKA's different usage were also evaluated
across diverse real-world datasets, demonstrating performance very close to
LiRA when used as an MIA on k-NN classifiers, but with greater computational
efficiency. Additionally, WaKA shows greater robustness than Shapley Values for
data minimization tasks (removal or addition) on imbalanced datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.01344v1">Can Humans Oversee Agents to Prevent Privacy Leakage? A Study on Privacy
  Awareness, Preferences, and Trust in Language Model Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-11-02T19:15:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhiping Zhang, Bingcan Guo, Tianshi Li</p>
    <p><b>Summary:</b> Language model (LM) agents that act on users' behalf for personal tasks can
boost productivity, but are also susceptible to unintended privacy leakage
risks. We present the first study on people's capacity to oversee the privacy
implications of the LM agents. By conducting a task-based survey (N=300), we
investigate how people react to and assess the response generated by LM agents
for asynchronous interpersonal communication tasks, compared with a response
they wrote. We found that people may favor the agent response with more privacy
leakage over the response they drafted or consider both good, leading to an
increased harmful disclosure from 15.7% to 55.0%. We further uncovered distinct
patterns of privacy behaviors, attitudes, and preferences, and the nuanced
interactions between privacy considerations and other factors. Our findings
shed light on designing agentic systems that enable privacy-preserving
interactions and achieve bidirectional alignment on privacy preferences to help
users calibrate trust.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.01308v1">ECG-PPS: Privacy Preserving Disease Diagnosis and Monitoring System for
  Real-Time ECG Signal</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-11-02T17:03:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Beyazit Bestami Yuksel, Ayse Yilmazer Metin</p>
    <p><b>Summary:</b> This study introduces the development of a state of the art, real time ECG
monitoring and analysis system, incorporating cutting edge medical technology
and innovative data security measures. Our system performs three distinct
functions thaat real time ECG monitoring and disease detection, encrypted
storage and synchronized visualization, and statistical analysis on encrypted
data. At its core, the system uses a three lead ECG preamplifier connected
through a serial port to capture, display, and record real time ECG data. These
signals are securely stored in the cloud using robust encryption methods.
Authorized medical personnel can access and decrypt this data on their
computers, with AES encryption ensuring synchronized real time data tracking
and visualization. Furthermore, the system performs statistical operations on
the ECG data stored in the cloud without decrypting it, using Fully Homomorphic
Encryption (FHE). This enables privacy preserving data analysis while ensuring
the security and confidentiality of patient information. By integrating these
independent functions, our system significantly enhances the security and
efficiency of health monitoring. It supports critical tasks such as disease
detection, patient monitoring, and preliminary intervention, all while
upholding stringent data privacy standards. We provided detailed discussions on
the system's architecture, hardware configuration, software implementation, and
clinical performance. The results highlight the potential of this system to
improve patient care through secure and efficient ECG monitoring and analysis.
This work represents a significant leap forward in medical technology. By
incorporating FHE into both data transmission and storage processes, we ensure
continuous encryption of data throughout its lifecycle while enabling real time
disease diagnosis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.01140v2">Privacy-Preserving Federated Learning with Differentially Private
  Hyperdimensional Computing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-11-02T05:00:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fardin Jalil Piran, Zhiling Chen, Mohsen Imani, Farhad Imani</p>
    <p><b>Summary:</b> Federated Learning (FL) is essential for efficient data exchange in Internet
of Things (IoT) environments, as it trains Machine Learning (ML) models locally
and shares only model updates. However, FL is vulnerable to privacy threats
like model inversion and membership inference attacks, which can expose
sensitive training data. To address these privacy concerns, Differential
Privacy (DP) mechanisms are often applied. Yet, adding DP noise to black-box ML
models degrades performance, especially in dynamic IoT systems where
continuous, lifelong FL learning accumulates excessive noise over time. To
mitigate this issue, we introduce Federated HyperDimensional computing with
Privacy-preserving (FedHDPrivacy), an eXplainable Artificial Intelligence (XAI)
framework that combines the neuro-symbolic paradigm with DP. FedHDPrivacy
carefully manages the balance between privacy and performance by theoretically
tracking cumulative noise from previous rounds and adding only the necessary
incremental noise to meet privacy requirements. In a real-world case study
involving in-process monitoring of manufacturing machining operations,
FedHDPrivacy demonstrates robust performance, outperforming standard FL
frameworks-including Federated Averaging (FedAvg), Federated Stochastic
Gradient Descent (FedSGD), Federated Proximal (FedProx), Federated Normalized
Averaging (FedNova), and Federated Adam (FedAdam)-by up to 38%. FedHDPrivacy
also shows potential for future enhancements, such as multimodal data fusion.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.01076v2">Privacy Risks of Speculative Decoding in Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-11-01T23:14:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiankun Wei, Abdulrahman Abdulrazzag, Tianchen Zhang, Adel Muursepp, Gururaj Saileshwar</p>
    <p><b>Summary:</b> Speculative decoding in large language models (LLMs) accelerates token
generation by speculatively predicting multiple tokens cheaply and verifying
them in parallel, and has been widely deployed. In this paper, we provide the
first study demonstrating the privacy risks of speculative decoding. We observe
that input-dependent patterns of correct and incorrect predictions can be
leaked out to an adversary monitoring token generation times and packet sizes,
leading to privacy breaches. By observing the pattern of correctly and
incorrectly speculated tokens, we show that a malicious adversary can
fingerprint queries and learn private user inputs with more than $90\%$
accuracy across three different speculative decoding techniques - REST (almost
$100\%$ accuracy), LADE (up to $92\%$ accuracy), and BiLD (up to $95\%$
accuracy). We show that an adversary can also leak out confidential
intellectual property used to design these techniques, such as data from
data-stores used for prediction (in REST) at a rate of more than $25$ tokens
per second, or even hyper-parameters used for prediction (in LADE). We also
discuss mitigation strategies, such as aggregating tokens across multiple
iterations and padding packets with additional bytes, to avoid such privacy or
confidentiality breaches.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.01050v1">BACSA: A Bias-Aware Client Selection Algorithm for Privacy-Preserving
  Federated Learning in Wireless Healthcare Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-11-01T21:34:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sushilkumar Yadav, Irem Bor-Yaliniz</p>
    <p><b>Summary:</b> Federated Learning (FL) has emerged as a transformative approach in
healthcare, enabling collaborative model training across decentralized data
sources while preserving user privacy. However, performance of FL rapidly
degrades in practical scenarios due to the inherent bias in non Independent and
Identically distributed (non-IID) data among participating clients, which poses
significant challenges to model accuracy and generalization. Therefore, we
propose the Bias-Aware Client Selection Algorithm (BACSA), which detects user
bias and strategically selects clients based on their bias profiles. In
addition, the proposed algorithm considers privacy preservation, fairness and
constraints of wireless network environments, making it suitable for sensitive
healthcare applications where Quality of Service (QoS), privacy and security
are paramount. Our approach begins with a novel method for detecting user bias
by analyzing model parameters and correlating them with the distribution of
class-specific data samples. We then formulate a mixed-integer non-linear
client selection problem leveraging the detected bias, alongside wireless
network constraints, to optimize FL performance. We demonstrate that BACSA
improves convergence and accuracy, compared to existing benchmarks, through
evaluations on various data distributions, including Dirichlet and
class-constrained scenarios. Additionally, we explore the trade-offs between
accuracy, fairness, and network constraints, indicating the adaptability and
robustness of BACSA to address diverse healthcare applications.</p>
  </details>
</div>

