
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


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.19548v3">Privacy-Preserving Federated Learning via Dataset Distillation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-10-25T13:20:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> ShiMao Xu, Xiaopeng Ke, Xing Su, Shucheng Li, Hao Wu, Sheng Zhong, Fengyuan Xu</p>
    <p><b>Summary:</b> Federated Learning (FL) allows users to share knowledge instead of raw data
to train a model with high accuracy. Unfortunately, during the training, users
lose control over the knowledge shared, which causes serious data privacy
issues. We hold that users are only willing and need to share the essential
knowledge to the training task to obtain the FL model with high accuracy.
However, existing efforts cannot help users minimize the shared knowledge
according to the user intention in the FL training procedure. This work
proposes FLiP, which aims to bring the principle of least privilege (PoLP) to
FL training. The key design of FLiP is applying elaborate information reduction
on the training data through a local-global dataset distillation design. We
measure the privacy performance through attribute inference and membership
inference attacks. Extensive experiments show that FLiP strikes a good balance
between model accuracy and privacy protection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.19338v1">Privacy-preserving server-supported decryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-25T06:47:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Peeter Laud, Alisa Pankova, Jelizaveta Vakarjuk</p>
    <p><b>Summary:</b> In this paper, we consider encryption systems with two-out-of-two threshold
decryption, where one of the parties (the client) initiates the decryption and
the other one (the server) assists. Existing threshold decryption schemes
disclose to the server the ciphertext that is being decrypted. We give a
construction, where the identity of the ciphertext is not leaked to the server,
and the client's privacy is thus preserved. While showing the security of this
construction, we run into the issue of defining the security of a scheme with
blindly assisted decryption. We discuss previously proposed security
definitions for similar cryptographic functionalities and argue why they do not
capture the expected meaning of security. We propose an ideal functionality for
the encryption with server-supported blind threshold decryption in the
universal composability model, carefully balancing between the meaning of
privacy, and the ability to implement it. We construct a protocol and show that
it is a secure implementation of the proposed functionality in the random
oracle model.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.18824v1">PSY: Posterior Sampling Based Privacy Enhancer in Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-24T15:15:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yulian Sun, Li Duan, Yong Li</p>
    <p><b>Summary:</b> Privacy vulnerabilities in LLMs, such as leakage from memorization, have been
constantly identified, and various mitigation proposals have been proposed.
LoRA is usually used in fine-tuning LLMs and a good entry point to insert
privacy-enhancing modules. In this ongoing research, we introduce PSY, a
Posterior Sampling based PrivacY enhancer that can be used in LoRA. We propose
a simple yet effective realization of PSY using posterior sampling, which
effectively prevents privacy leakage from intermediate information and, in
turn, preserves the privacy of data owners. We evaluate LoRA extended with PSY
against state-of-the-art membership inference and data extraction attacks. The
experiments are executed on three different LLM architectures fine-tuned on
three datasets with LoRA. In contrast to the commonly used differential privacy
method, we find that our proposed modification consistently reduces the attack
success rate. Meanwhile, our method has almost no negative impact on model
fine-tuning or final performance. Most importantly, PSY reveals a promising
path toward privacy enhancement with latent space extensions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.18749v1">Does Differential Privacy Impact Bias in Pretrained NLP Models?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-10-24T13:59:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Md. Khairul Islam, Andrew Wang, Tianhao Wang, Yangfeng Ji, Judy Fox, Jieyu Zhao</p>
    <p><b>Summary:</b> Differential privacy (DP) is applied when fine-tuning pre-trained large
language models (LLMs) to limit leakage of training examples. While most DP
research has focused on improving a model's privacy-utility tradeoff, some find
that DP can be unfair to or biased against underrepresented groups. In this
work, we show the impact of DP on bias in LLMs through empirical analysis.
Differentially private training can increase the model bias against protected
groups w.r.t AUC-based bias metrics. DP makes it more difficult for the model
to differentiate between the positive and negative examples from the protected
groups and other groups in the rest of the population. Our results also show
that the impact of DP on bias is not only affected by the privacy protection
level but also the underlying distribution of the dataset.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.18717v1">Low-Latency Video Anonymization for Crowd Anomaly Detection: Privacy vs.
  Performance</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-10-24T13:22:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mulugeta Weldezgina Asres, Lei Jiao, Christian Walter Omlin</p>
    <p><b>Summary:</b> Recent advancements in artificial intelligence promise ample potential in
monitoring applications with surveillance cameras. However, concerns about
privacy and model bias have made it challenging to utilize them in public.
Although de-identification approaches have been proposed in the literature,
aiming to achieve a certain level of anonymization, most of them employ deep
learning models that are computationally demanding for real-time edge
deployment. In this study, we revisit conventional anonymization solutions for
privacy protection and real-time video anomaly detection (VAD) applications. We
propose a novel lightweight adaptive anonymization for VAD (LA3D) that employs
dynamic adjustment to enhance privacy protection. We evaluated the approaches
on publicly available privacy and VAD data sets to examine the strengths and
weaknesses of the different anonymization techniques and highlight the
promising efficacy of our approach. Our experiment demonstrates that LA3D
enables substantial improvement in the privacy anonymization capability without
majorly degrading VAD efficacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.18666v2">DreamClear: High-Capacity Real-World Image Restoration with Privacy-Safe
  Dataset Curation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-10-24T11:57:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuang Ai, Xiaoqiang Zhou, Huaibo Huang, Xiaotian Han, Zhengyu Chen, Quanzeng You, Hongxia Yang</p>
    <p><b>Summary:</b> Image restoration (IR) in real-world scenarios presents significant
challenges due to the lack of high-capacity models and comprehensive datasets.
To tackle these issues, we present a dual strategy: GenIR, an innovative data
curation pipeline, and DreamClear, a cutting-edge Diffusion Transformer
(DiT)-based image restoration model. GenIR, our pioneering contribution, is a
dual-prompt learning pipeline that overcomes the limitations of existing
datasets, which typically comprise only a few thousand images and thus offer
limited generalizability for larger models. GenIR streamlines the process into
three stages: image-text pair construction, dual-prompt based fine-tuning, and
data generation & filtering. This approach circumvents the laborious data
crawling process, ensuring copyright compliance and providing a cost-effective,
privacy-safe solution for IR dataset construction. The result is a large-scale
dataset of one million high-quality images. Our second contribution,
DreamClear, is a DiT-based image restoration model. It utilizes the generative
priors of text-to-image (T2I) diffusion models and the robust perceptual
capabilities of multi-modal large language models (MLLMs) to achieve
photorealistic restoration. To boost the model's adaptability to diverse
real-world degradations, we introduce the Mixture of Adaptive Modulator (MoAM).
It employs token-wise degradation priors to dynamically integrate various
restoration experts, thereby expanding the range of degradations the model can
address. Our exhaustive experiments confirm DreamClear's superior performance,
underlining the efficacy of our dual strategy for real-world image restoration.
Code and pre-trained models are available at:
https://github.com/shallowdream204/DreamClear.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.18418v1">Knowledge-Assisted Privacy Preserving in Semantic Communication</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-24T04:05:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xuesong Liu, Yao Sun, Runze Cheng, Le Xia, Hanaa Abumarshoud, Lei Zhang, Muhammad Ali Imran</p>
    <p><b>Summary:</b> Semantic communication (SC) offers promising advancements in data
transmission efficiency and reliability by focusing on delivering true meaning
rather than solely binary bits of messages. However, privacy concerns in SC
might become outstanding. Eavesdroppers equipped with advanced semantic coding
models and extensive knowledge could be capable of correctly decoding and
reasoning sensitive semantics from just a few stolen bits. To this end, this
article explores utilizing knowledge to enhance data privacy in SC networks.
Specifically, we first identify the potential attacks in SC based on the
analysis of knowledge. Then, we propose a knowledge-assisted privacy preserving
SC framework, which consists of a data transmission layer for precisely
encoding and decoding source messages, and a knowledge management layer
responsible for injecting appropriate knowledge into the transmission pair.
Moreover, we elaborate on the transceiver design in the proposed SC framework
to explain how knowledge should be utilized properly. Finally, some challenges
of the proposed SC framework are discussed to expedite the practical
implementation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.18404v1">Enhancing Feature-Specific Data Protection via Bayesian Coordinate
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-10-24T03:39:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maryam Aliakbarpour, Syomantak Chaudhuri, Thomas A. Courtade, Alireza Fallah, Michael I. Jordan</p>
    <p><b>Summary:</b> Local Differential Privacy (LDP) offers strong privacy guarantees without
requiring users to trust external parties. However, LDP applies uniform
protection to all data features, including less sensitive ones, which degrades
performance of downstream tasks. To overcome this limitation, we propose a
Bayesian framework, Bayesian Coordinate Differential Privacy (BCDP), that
enables feature-specific privacy quantification. This more nuanced approach
complements LDP by adjusting privacy protection according to the sensitivity of
each feature, enabling improved performance of downstream tasks without
compromising privacy. We characterize the properties of BCDP and articulate its
connections with standard non-Bayesian privacy frameworks. We further apply our
BCDP framework to the problems of private mean estimation and ordinary
least-squares regression. The BCDP-based approach obtains improved accuracy
compared to a purely LDP-based approach, without compromising on privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.17468v1">Formal Privacy Guarantees with Invariant Statistics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-10-22T22:50:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Young Hyun Cho, Jordan Awan</p>
    <p><b>Summary:</b> Motivated by the 2020 US Census products, this paper extends differential
privacy (DP) to address the joint release of DP outputs and nonprivate
statistics, referred to as invariant. Our framework, Semi-DP, redefines
adjacency by focusing on datasets that conform to the given invariant, ensuring
indistinguishability between adjacent datasets within invariant-conforming
datasets. We further develop customized mechanisms that satisfy Semi-DP,
including the Gaussian mechanism and the optimal $K$-norm mechanism for
rank-deficient sensitivity spaces. Our framework is applied to contingency
table analysis which is relevant to the 2020 US Census, illustrating how
Semi-DP enables the release of private outputs given the one-way margins as the
invariant. Additionally, we provide a privacy analysis of the 2020 US Decennial
Census using the Semi-DP framework, revealing that the effective privacy
guarantees are weaker than advertised.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.17459v1">Data Obfuscation through Latent Space Projection (LSP) for
  Privacy-Preserving AI Governance: Case Studies in Medical Diagnosis and
  Finance Fraud Detection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> 
  <p><b>Published on:</b> 2024-10-22T22:31:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mahesh Vaijainthymala Krishnamoorthy</p>
    <p><b>Summary:</b> As AI systems increasingly integrate into critical societal sectors, the
demand for robust privacy-preserving methods has escalated. This paper
introduces Data Obfuscation through Latent Space Projection (LSP), a novel
technique aimed at enhancing AI governance and ensuring Responsible AI
compliance. LSP uses machine learning to project sensitive data into a latent
space, effectively obfuscating it while preserving essential features for model
training and inference. Unlike traditional privacy methods like differential
privacy or homomorphic encryption, LSP transforms data into an abstract,
lower-dimensional form, achieving a delicate balance between data utility and
privacy. Leveraging autoencoders and adversarial training, LSP separates
sensitive from non-sensitive information, allowing for precise control over
privacy-utility trade-offs. We validate LSP's effectiveness through experiments
on benchmark datasets and two real-world case studies: healthcare cancer
diagnosis and financial fraud analysis. Our results show LSP achieves high
performance (98.7% accuracy in image classification) while providing strong
privacy (97.3% protection against sensitive attribute inference), outperforming
traditional anonymization and privacy-preserving methods. The paper also
examines LSP's alignment with global AI governance frameworks, such as GDPR,
CCPA, and HIPAA, highlighting its contribution to fairness, transparency, and
accountability. By embedding privacy within the machine learning pipeline, LSP
offers a promising approach to developing AI systems that respect privacy while
delivering valuable insights. We conclude by discussing future research
directions, including theoretical privacy guarantees, integration with
federated learning, and enhancing latent space interpretability, positioning
LSP as a critical tool for ethical AI advancement.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.17353v1">Preserving Privacy in Cloud-based Data-Driven Stabilization</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2024-10-22T18:44:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Teimour Hosseinalizadeh, Nima Monshizadeh</p>
    <p><b>Summary:</b> In the recent years, we have observed three significant trends in control
systems: a renewed interest in data-driven control design, the abundance of
cloud computational services and the importance of preserving privacy for the
system under control. Motivated by these factors, this work investigates
privacy-preserving outsourcing for the design of a stabilizing controller for
unknown linear time-invariant systems.The main objective of this research is to
preserve the privacy for the system dynamics by designing an outsourcing
mechanism. To achieve this goal, we propose a scheme that combines
transformation-based techniques and robust data-driven control design methods.
The scheme preserves the privacy of both the open-loop and closed-loop system
matrices while stabilizing the system under control.The scheme is applicable to
both data with and without disturbance and is lightweight in terms of
computational overhead. Numerical investigations for a case study demonstrate
the impacts of our mechanism and its role in hindering malicious adversaries
from achieving their goals.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.19012v1">Privacy-Computation trade-offs in Private Repetition and Metaselection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-10-22T18:33:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kunal Talwar</p>
    <p><b>Summary:</b> A Private Repetition algorithm takes as input a differentially private
algorithm with constant success probability and boosts it to one that succeeds
with high probability. These algorithms are closely related to private
metaselection algorithms that compete with the best of many private algorithms,
and private hyperparameter tuning algorithms that compete with the best
hyperparameter settings for a private learning algorithm. Existing algorithms
for these tasks pay either a large overhead in privacy cost, or a large
overhead in computational cost. In this work, we show strong lower bounds for
problems of this kind, showing in particular that for any algorithm that
preserves the privacy cost up to a constant factor, the failure probability can
only fall polynomially in the computational overhead. This is in stark contrast
with the non-private setting, where the failure probability falls exponentially
in the computational overhead. By carefully combining existing algorithms for
metaselection, we prove computation-privacy tradeoffs that nearly match our
lower bounds.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.17127v1">PAPILLON: PrivAcy Preservation from Internet-based and Local Language
  MOdel ENsembles</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-10-22T16:00:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Li Siyan, Vethavikashini Chithrra Raghuram, Omar Khattab, Julia Hirschberg, Zhou Yu</p>
    <p><b>Summary:</b> Users can divulge sensitive information to proprietary LLM providers, raising
significant privacy concerns. While open-source models, hosted locally on the
user's machine, alleviate some concerns, models that users can host locally are
often less capable than proprietary frontier models. Toward preserving user
privacy while retaining the best quality, we propose Privacy-Conscious
Delegation, a novel task for chaining API-based and local models. We utilize
recent public collections of user-LLM interactions to construct a natural
benchmark called PUPA, which contains personally identifiable information
(PII). To study potential approaches, we devise PAPILLON, a multi-stage LLM
pipeline that uses prompt optimization to address a simpler version of our
task. Our best pipeline maintains high response quality for 85.5% of user
queries while restricting privacy leakage to only 7.5%. We still leave a large
margin to the generation quality of proprietary LLMs for future work. Our data
and code will be available at https://github.com/siyan-sylvia-li/PAPILLON.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.17098v1">Masked Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">  
  <p><b>Published on:</b> 2024-10-22T15:22:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> David Schneider, Sina Sajadmanesh, Vikash Sehwag, Saquib Sarfraz, Rainer Stiefelhagen, Lingjuan Lyu, Vivek Sharma</p>
    <p><b>Summary:</b> Privacy-preserving computer vision is an important emerging problem in
machine learning and artificial intelligence. The prevalent methods tackling
this problem use differential privacy or anonymization and obfuscation
techniques to protect the privacy of individuals. In both cases, the utility of
the trained model is sacrificed heavily in this process. In this work, we
propose an effective approach called masked differential privacy (MaskDP),
which allows for controlling sensitive regions where differential privacy is
applied, in contrast to applying DP on the entire input. Our method operates
selectively on the data and allows for defining non-sensitive spatio-temporal
regions without DP application or combining differential privacy with other
privacy techniques within data samples. Experiments on four challenging action
recognition datasets demonstrate that our proposed techniques result in better
utility-privacy trade-offs compared to standard differentially private training
in the especially demanding $\epsilon<1$ regime.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.16975v1">Publishing Neural Networks in Drug Discovery Might Compromise Training
  Data Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-10-22T12:55:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fabian P. Krüger, Johan Östman, Lewis Mervin, Igor V. Tetko, Ola Engkvist</p>
    <p><b>Summary:</b> This study investigates the risks of exposing confidential chemical
structures when machine learning models trained on these structures are made
publicly available. We use membership inference attacks, a common method to
assess privacy that is largely unexplored in the context of drug discovery, to
examine neural networks for molecular property prediction in a black-box
setting. Our results reveal significant privacy risks across all evaluated
datasets and neural network architectures. Combining multiple attacks increases
these risks. Molecules from minority classes, often the most valuable in drug
discovery, are particularly vulnerable. We also found that representing
molecules as graphs and using message-passing neural networks may mitigate
these risks. We provide a framework to assess privacy risks of classification
models and molecular representations. Our findings highlight the need for
careful consideration when sharing neural networks trained on proprietary
chemical structures, informing organisations and researchers about the
trade-offs between data confidentiality and model openness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.16705v1">Privacy-hardened and hallucination-resistant synthetic data generation
  with logic-solvers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-10-22T05:20:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mark A. Burgess, Brendan Hosking, Roc Reguant, Anubhav Kaphle, Mitchell J. O'Brien, Letitia M. F. Sng, Yatish Jain, Denis C. Bauer</p>
    <p><b>Summary:</b> Machine-generated data is a valuable resource for training Artificial
Intelligence algorithms, evaluating rare workflows, and sharing data under
stricter data legislations. The challenge is to generate data that is accurate
and private. Current statistical and deep learning methods struggle with large
data volumes, are prone to hallucinating scenarios incompatible with reality,
and seldom quantify privacy meaningfully. Here we introduce Genomator, a logic
solving approach (SAT solving), which efficiently produces private and
realistic representations of the original data. We demonstrate the method on
genomic data, which arguably is the most complex and private information.
Synthetic genomes hold great potential for balancing underrepresented
populations in medical research and advancing global data exchange. We
benchmark Genomator against state-of-the-art methodologies (Markov generation,
Restricted Boltzmann Machine, Generative Adversarial Network and Conditional
Restricted Boltzmann Machines), demonstrating an 84-93% accuracy improvement
and 95-98% higher privacy. Genomator is also 1000-1600 times more efficient,
making it the only tested method that scales to whole genomes. We show the
universal trade-off between privacy and accuracy, and use Genomator's tuning
capability to cater to all applications along the spectrum, from provable
private representations of sensitive cohorts, to datasets with
indistinguishable pharmacogenomic profiles. Demonstrating the production-scale
generation of tuneable synthetic data can increase trust and pave the way into
the clinic.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.16672v1">DEAN: Deactivating the Coupled Neurons to Mitigate Fairness-Privacy
  Conflicts in Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-10-22T04:08:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chen Qian, Dongrui Liu, Jie Zhang, Yong Liu, Jing Shao</p>
    <p><b>Summary:</b> Ensuring awareness of fairness and privacy in Large Language Models (LLMs) is
critical. Interestingly, we discover a counter-intuitive trade-off phenomenon
that enhancing an LLM's privacy awareness through Supervised Fine-Tuning (SFT)
methods significantly decreases its fairness awareness with thousands of
samples. To address this issue, inspired by the information theory, we
introduce a training-free method to \textbf{DEA}ctivate the fairness and
privacy coupled \textbf{N}eurons (\textbf{DEAN}), which theoretically and
empirically decrease the mutual information between fairness and privacy
awareness. Extensive experimental results demonstrate that DEAN eliminates the
trade-off phenomenon and significantly improves LLMs' fairness and privacy
awareness simultaneously, \eg improving Qwen-2-7B-Instruct's fairness awareness
by 12.2\% and privacy awareness by 14.0\%. More crucially, DEAN remains robust
and effective with limited annotated data or even when only malicious
fine-tuning data is available, whereas SFT methods may fail to perform properly
in such scenarios. We hope this study provides valuable insights into
concurrently addressing fairness and privacy concerns in LLMs and can be
integrated into comprehensive frameworks to develop more ethical and
responsible AI systems. Our code is available at
\url{https://github.com/ChnQ/DEAN}.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.16423v1">Position: Challenges and Opportunities for Differential Privacy in the
  U.S. Federal Government</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-10-21T18:46:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Amol Khanna, Adam McCormick, Andre Nguyen, Chris Aguirre, Edward Raff</p>
    <p><b>Summary:</b> In this article, we seek to elucidate challenges and opportunities for
differential privacy within the federal government setting, as seen by a team
of differential privacy researchers, privacy lawyers, and data scientists
working closely with the U.S. government. After introducing differential
privacy, we highlight three significant challenges which currently restrict the
use of differential privacy in the U.S. government. We then provide two
examples where differential privacy can enhance the capabilities of government
agencies. The first example highlights how the quantitative nature of
differential privacy allows policy security officers to release multiple
versions of analyses with different levels of privacy. The second example,
which we believe is a novel realization, indicates that differential privacy
can be used to improve staffing efficiency in classified applications. We hope
that this article can serve as a nontechnical resource which can help frame
future action from the differential privacy community, privacy regulators,
security officers, and lawmakers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.16410v1">Subword Embedding from Bytes Gains Privacy without Sacrificing Accuracy
  and Complexity</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-10-21T18:25:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mengjiao Zhang, Jia Xu</p>
    <p><b>Summary:</b> While NLP models significantly impact our lives, there are rising concerns
about privacy invasion. Although federated learning enhances privacy, attackers
may recover private training data by exploiting model parameters and gradients.
Therefore, protecting against such embedding attacks remains an open challenge.
To address this, we propose Subword Embedding from Bytes (SEB) and encode
subwords to byte sequences using deep neural networks, making input text
recovery harder. Importantly, our method requires a smaller memory with $256$
bytes of vocabulary while keeping efficiency with the same input length. Thus,
our solution outperforms conventional approaches by preserving privacy without
sacrificing efficiency or accuracy. Our experiments show SEB can effectively
protect against embedding-based attacks from recovering original sentences in
federated learning. Meanwhile, we verify that SEB obtains comparable and even
better results over standard subword embedding methods in machine translation,
sentiment analysis, and language modeling with even lower time and space
complexity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.16137v2">Privacy as Social Norm: Systematically Reducing Dysfunctional Privacy
  Concerns on Social Media</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-10-21T16:03:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> JaeWon Kim, Soobin Cho, Robert Wolfe, Jishnu Hari Nair, Alexis Hiniker</p>
    <p><b>Summary:</b> Privacy is essential to fully enjoying the benefits of social media. While
fear around privacy risks can sometimes motivate privacy management, the
negative impact of such fear, particularly when it is perceived as
unaddressable (i.e., "dysfunctional" fear), can significantly harm teen
well-being. In a co-design study with 136 participants aged 13-18, we explored
how teens can protect their privacy without experiencing heightened fear. We
identified seven different sources of dysfunctional fear, such as `fear of a
hostile environment' and `fear of overstepping privacy norms.' We also
evaluated ten designs, co-created with teen participants, that address these
fears. Our findings suggest that social media platforms can mitigate
dysfunctional fear without compromising privacy by creating a culture where
privacy protection is the norm through default privacy-protective features.
However, we also found that even the most effective privacy features are not
likely to be adopted unless they balance the multifaceted and diverse needs of
teens. Individual teens have different needs -- for example, public and private
account users have different needs -- and teens often want to enjoy the
benefits they get from slightly reducing privacy and widening their social
reach. Given these considerations, augmenting default privacy features by
allowing them to be toggled on and off will allow individual users to choose
their own balance while still maintaining a privacy-focused norm.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.15954v1">TS-ACL: A Time Series Analytic Continual Learning Framework for
  Privacy-Preserving and Class-Incremental Pattern Recognition</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> 
  <p><b>Published on:</b> 2024-10-21T12:34:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kejia Fan, Jiaxu Li, Songning Lai, Linpu Lv, Anfeng Liu, Jianheng Tang, Houbing Herbert Song, Huiping Zhuang</p>
    <p><b>Summary:</b> Class-incremental Learning (CIL) in Time Series Classification (TSC) aims to
incrementally train models using the streaming time series data that arrives
continuously. The main problem in this scenario is catastrophic forgetting,
i.e., training models with new samples inevitably leads to the forgetting of
previously learned knowledge. Among existing methods, the replay-based methods
achieve satisfactory performance but compromise privacy, while exemplar-free
methods protect privacy but suffer from low accuracy. However, more critically,
owing to their reliance on gradient-based update techniques, these existing
methods fundamentally cannot solve the catastrophic forgetting problem. In TSC
scenarios with continuously arriving data and temporally shifting
distributions, these methods become even less practical. In this paper, we
propose a Time Series Analytic Continual Learning framework, called TS-ACL.
Inspired by analytical learning, TS-ACL transforms neural network updates into
gradient-free linear regression problems, thereby fundamentally mitigating
catastrophic forgetting. Specifically, employing a pre-trained and frozen
feature extraction encoder, TS-ACL only needs to update its analytic classifier
recursively in a lightweight manner that is highly suitable for real-time
applications and large-scale data processing. Additionally, we theoretically
demonstrate that the model obtained recursively through the TS-ACL is exactly
equivalent to a model trained on the complete dataset in a centralized manner,
thereby establishing the property of absolute knowledge memory. Extensive
experiments validate the superior performance of our TS-ACL.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.15942v1">A Low-Cost Privacy-Preserving Digital Wallet for Humanitarian Aid
  Distribution</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-21T12:15:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Eva Luvison, Sylvain Chatel, Justinas Sukaitis, Vincent Graf Narbel, Carmela Troncoso, Wouter Lueks</p>
    <p><b>Summary:</b> Humanitarian organizations distribute aid to people affected by armed
conflicts or natural disasters. Digitalization has the potential to increase
the efficiency and fairness of aid-distribution systems, and recent work by
Wang et al. has shown that these benefits are possible without creating privacy
harms for aid recipients. However, their work only provides a solution for one
particular aid-distribution scenario in which aid recipients receive a
pre-defined set of goods. Yet, in many situations it is desirable to enable
recipients to decide which items they need at each moment to satisfy their
specific needs. We formalize these needs into functional, deployment, security,
and privacy requirements, and design a privacy-preserving digital wallet for
aid distribution. Our smart-card-based solution enables aid recipients to spend
a pre-defined budget at different vendors to obtain the items that they need.
We prove our solution's security and privacy properties, and show it is
practical at scale.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.15386v1">Formalization of Differential Privacy in Isabelle/HOL</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Logic in Computer Science-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Programming Languages-D91E36">
  <p><b>Published on:</b> 2024-10-20T13:06:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tetsuya Sato, Yasuhiko Minamide</p>
    <p><b>Summary:</b> Differential privacy is a statistical definition of privacy that has
attracted the interest of both academia and industry. Its formulations are easy
to understand, but the differential privacy of databases is complicated to
determine. One of the reasons for this is that small changes in database
programs can break their differential privacy. Therefore, formal verification
of differential privacy has been studied for over a decade.
  In this paper, we propose an Isabelle/HOL library for formalizing
differential privacy in a general setting. To our knowledge, it is the first
formalization of differential privacy that supports continuous probability
distributions. First, we formalize the standard definition of differential
privacy and its basic properties. Second, we formalize the Laplace mechanism
and its differential privacy. Finally, we formalize the differential privacy of
the report noisy max mechanism.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.15369v1">Ethical AI in Retail: Consumer Privacy and Fairness</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-10-20T12:00:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anthonette Adanyin</p>
    <p><b>Summary:</b> The adoption of artificial intelligence (AI) in retail has significantly
transformed the industry, enabling more personalized services and efficient
operations. However, the rapid implementation of AI technologies raises ethical
concerns, particularly regarding consumer privacy and fairness. This study aims
to analyze the ethical challenges of AI applications in retail, explore ways
retailers can implement AI technologies ethically while remaining competitive,
and provide recommendations on ethical AI practices. A descriptive survey
design was used to collect data from 300 respondents across major e-commerce
platforms. Data were analyzed using descriptive statistics, including
percentages and mean scores. Findings shows a high level of concerns among
consumers regarding the amount of personal data collected by AI-driven retail
applications, with many expressing a lack of trust in how their data is
managed. Also, fairness is another major issue, as a majority believe AI
systems do not treat consumers equally, raising concerns about algorithmic
bias. It was also found that AI can enhance business competitiveness and
efficiency without compromising ethical principles, such as data privacy and
fairness. Data privacy and transparency were highlighted as critical areas
where retailers need to focus their efforts, indicating a strong demand for
stricter data protection protocols and ongoing scrutiny of AI systems. The
study concludes that retailers must prioritize transparency, fairness, and data
protection when deploying AI systems. The study recommends ensuring
transparency in AI processes, conducting regular audits to address biases,
incorporating consumer feedback in AI development, and emphasizing consumer
data privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.15044v1">Adanonymizer: Interactively Navigating and Balancing the Duality of
  Privacy and Output Performance in Human-LLM Interaction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-10-19T09:04:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuning Zhang, Xin Yi, Haobin Xing, Lyumanshan Ye, Yongquan Hu, Hewu Li</p>
    <p><b>Summary:</b> Current Large Language Models (LLMs) cannot support users to precisely
balance privacy protection and output performance during individual
consultations. We introduce Adanonymizer, an anonymization plug-in that allows
users to control this balance by navigating a trade-off curve. A survey (N=221)
revealed a privacy paradox, where users frequently disclosed sensitive
information despite acknowledging privacy risks. The study further demonstrated
that privacy risks were not significantly correlated with model output
performance, highlighting the potential to navigate this trade-off.
Adanonymizer normalizes privacy and utility ratings by type and automates the
pseudonymization of sensitive terms based on user preferences, significantly
reducing user effort. Its 2D color palette interface visualizes the
privacy-utility trade-off, allowing users to adjust the balance by manipulating
a point. An evaluation (N=36) compared Adanonymizer with ablation methods and
differential privacy techniques, where Adanonymizer significantly reduced
modification time, achieved better perceived model performance and overall user
preference.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.14960v1">Dual-Technique Privacy & Security Analysis for E-Commerce Websites
  Through Automated and Manual Implementation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-10-19T03:25:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Urvashi Kishnani, Sanchari Das</p>
    <p><b>Summary:</b> As e-commerce continues to expand, the urgency for stronger privacy and
security measures becomes increasingly critical, particularly on platforms
frequented by younger users who are often less aware of potential risks. In our
analysis of 90 US-based e-commerce websites, we employed a dual-technique
approach, combining automated tools with manual evaluations. Tools like
CookieServe and PrivacyCheck revealed that 38.5% of the websites deployed over
50 cookies per session, many of which were categorized as unnecessary or
unclear in function, posing significant risks to users' Personally Identifiable
Information (PII). Our manual assessment further uncovered critical gaps in
standard security practices, including the absence of mandatory multi-factor
authentication (MFA) and breach notification protocols. Additionally, we
observed inadequate input validation, which compromises the integrity of user
data and transactions. Based on these findings, we recommend targeted
improvements to privacy policies, enhanced transparency in cookie usage, and
the implementation of stronger authentication protocols. These measures are
essential for ensuring compliance with CCPA and COPPA, thereby fostering more
secure online environments, particularly for younger users.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.14931v1">"Ghost of the past": identifying and resolving privacy leakage from
  LLM's memory through proactive user interaction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-10-19T01:35:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuning Zhang, Lyumanshan Ye, Xin Yi, Jingyu Tang, Bo Shui, Haobin Xing, Pengfei Liu, Hewu Li</p>
    <p><b>Summary:</b> Memories, encompassing past inputs in context window and retrieval-augmented
generation (RAG), frequently surface during human-LLM interactions, yet users
are often unaware of their presence and the associated privacy risks. To
address this, we propose MemoAnalyzer, a system for identifying, visualizing,
and managing private information within memories. A semi-structured interview
(N=40) revealed that low privacy awareness was the primary challenge, while
proactive privacy control emerged as the most common user need. MemoAnalyzer
uses a prompt-based method to infer and identify sensitive information from
aggregated past inputs, allowing users to easily modify sensitive content.
Background color temperature and transparency are mapped to inference
confidence and sensitivity, streamlining privacy adjustments. A 5-day
evaluation (N=36) comparing MemoAnalyzer with the default GPT setting and a
manual modification baseline showed MemoAnalyzer significantly improved privacy
awareness and protection without compromising interaction speed. Our study
contributes to privacy-conscious LLM design, offering insights into privacy
protection for Human-AI interactions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.14787v1">Privacy for Free in the Over-Parameterized Regime</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-10-18T18:01:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Simone Bombari, Marco Mondelli</p>
    <p><b>Summary:</b> Differentially private gradient descent (DP-GD) is a popular algorithm to
train deep learning models with provable guarantees on the privacy of the
training data. In the last decade, the problem of understanding its performance
cost with respect to standard GD has received remarkable attention from the
research community, which formally derived upper bounds on the excess
population risk $R_{P}$ in different learning settings. However, existing
bounds typically degrade with over-parameterization, i.e., as the number of
parameters $p$ gets larger than the number of training samples $n$ -- a regime
which is ubiquitous in current deep-learning practice. As a result, the lack of
theoretical insights leaves practitioners without clear guidance, leading some
to reduce the effective number of trainable parameters to improve performance,
while others use larger models to achieve better results through scale. In this
work, we show that in the popular random features model with quadratic loss,
for any sufficiently large $p$, privacy can be obtained for free, i.e.,
$\left|R_{P} \right| = o(1)$, not only when the privacy parameter $\varepsilon$
has constant order, but also in the strongly private setting $\varepsilon =
o(1)$. This challenges the common wisdom that over-parameterization inherently
hinders performance in private learning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.14607v1">Evaluating Privacy Measures in Healthcare Apps Predominantly Used by
  Older Adults</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-10-18T17:01:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Suleiman Saka, Sanchari Das</p>
    <p><b>Summary:</b> The widespread adoption of telehealth systems has led to a significant
increase in the use of healthcare apps among older adults, but this rapid
growth has also heightened concerns about the privacy of their health
information. While HIPAA in the US and GDPR in the EU establish essential
privacy protections for health information, limited research exists on the
effectiveness of healthcare app privacy policies, particularly those used
predominantly by older adults. To address this, we evaluated 28 healthcare apps
across multiple dimensions, including regulatory compliance, data handling
practices, and privacy-focused usability. To do this, we created a Privacy Risk
Assessment Framework (PRAF) and used it to evaluate the privacy risks
associated with these healthcare apps designed for older adults. Our analysis
revealed significant gaps in compliance with privacy standards to such, only
25% of apps explicitly state compliance with HIPAA, and only 18% mention GDPR.
Surprisingly, 79% of these applications lack breach protocols, putting older
adults at risk in the event of a data breach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.14023v1">Identifying Privacy Personas</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-10-17T20:49:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Olena Hrynenko, Andrea Cavallaro</p>
    <p><b>Summary:</b> Privacy personas capture the differences in user segments with respect to
one's knowledge, behavioural patterns, level of self-efficacy, and perception
of the importance of privacy protection. Modelling these differences is
essential for appropriately choosing personalised communication about privacy
(e.g. to increase literacy) and for defining suitable choices for privacy
enhancing technologies (PETs). While various privacy personas have been derived
in the literature, they group together people who differ from each other in
terms of important attributes such as perceived or desired level of control,
and motivation to use PET. To address this lack of granularity and
comprehensiveness in describing personas, we propose eight personas that we
derive by combining qualitative and quantitative analysis of the responses to
an interactive educational questionnaire. We design an analysis pipeline that
uses divisive hierarchical clustering and Boschloo's statistical test of
homogeneity of proportions to ensure that the elicited clusters differ from
each other based on a statistical measure. Additionally, we propose a new
measure for calculating distances between questionnaire responses, that
accounts for the type of the question (closed- vs open-ended) used to derive
traits. We show that the proposed privacy personas statistically differ from
each other. We statistically validate the proposed personas and also compare
them with personas in the literature, showing that they provide a more granular
and comprehensive understanding of user segments, which will allow to better
assist users with their privacy needs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.13753v1">DPFedBank: Crafting a Privacy-Preserving Federated Learning Framework
  for Financial Institutions with Policy Pillars</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computational Engineering, Finance, and Science-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-10-17T16:51:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Peilin He, Chenkai Lin, Isabella Montoya</p>
    <p><b>Summary:</b> In recent years, the financial sector has faced growing pressure to adopt
advanced machine learning models to derive valuable insights while preserving
data privacy. However, the highly sensitive nature of financial data presents
significant challenges to sharing and collaboration. This paper presents
DPFedBank, an innovative framework enabling financial institutions to
collaboratively develop machine learning models while ensuring robust data
privacy through Local Differential Privacy (LDP) mechanisms. DPFedBank is
designed to address the unique privacy and security challenges associated with
financial data, allowing institutions to share insights without exposing
sensitive information. By leveraging LDP, the framework ensures that data
remains confidential even during collaborative processes, providing a crucial
solution for privacy-aware machine learning in finance. We conducted an
in-depth evaluation of the potential vulnerabilities within this framework and
developed a comprehensive set of policies aimed at mitigating these risks. The
proposed policies effectively address threats posed by malicious clients,
compromised servers, inherent weaknesses in existing Differential
Privacy-Federated Learning (DP-FL) frameworks, and sophisticated external
adversaries. Unlike existing DP-FL approaches, DPFedBank introduces a novel
combination of adaptive LDP mechanisms and advanced cryptographic techniques
specifically tailored for financial data, which significantly enhances privacy
while maintaining model utility. Key security enhancements include the
implementation of advanced authentication protocols, encryption techniques for
secure data exchange, and continuous monitoring systems to detect and respond
to malicious activities in real-time.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.13752v2">Privacy-Preserving Decentralized AI with Confidential Computing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-10-17T16:50:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dayeol Lee, Jorge António, Hisham Khan</p>
    <p><b>Summary:</b> This paper addresses privacy protection in decentralized Artificial
Intelligence (AI) using Confidential Computing (CC) within the Atoma Network, a
decentralized AI platform designed for the Web3 domain. Decentralized AI
distributes AI services among multiple entities without centralized oversight,
fostering transparency and robustness. However, this structure introduces
significant privacy challenges, as sensitive assets such as proprietary models
and personal data may be exposed to untrusted participants. Cryptography-based
privacy protection techniques such as zero-knowledge machine learning (zkML)
suffers prohibitive computational overhead. To address the limitation, we
propose leveraging Confidential Computing (CC). Confidential Computing
leverages hardware-based Trusted Execution Environments (TEEs) to provide
isolation for processing sensitive data, ensuring that both model parameters
and user data remain secure, even in decentralized, potentially untrusted
environments. While TEEs face a few limitations, we believe they can bridge the
privacy gap in decentralized AI. We explore how we can integrate TEEs into
Atoma's decentralized framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.13387v2">CLEAR: Towards Contextual LLM-Empowered Privacy Policy Analysis and Risk
  Generation for Large Language Model Applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-10-17T09:39:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chaoran Chen, Daodao Zhou, Yanfang Ye, Toby Jia-jun Li, Yaxing Yao</p>
    <p><b>Summary:</b> The rise of end-user applications powered by large language models (LLMs),
including both conversational interfaces and add-ons to existing graphical user
interfaces (GUIs), introduces new privacy challenges. However, many users
remain unaware of the risks. This paper explores methods to increase user
awareness of privacy risks associated with LLMs in end-user applications. We
conducted five co-design workshops to uncover user privacy concerns and their
demand for contextual privacy information within LLMs. Based on these insights,
we developed CLEAR (Contextual LLM-Empowered Privacy Policy Analysis and Risk
Generation), a just-in-time contextual assistant designed to help users
identify sensitive information, summarize relevant privacy policies, and
highlight potential risks when sharing information with LLMs. We evaluated the
usability and usefulness of CLEAR across in two example domains: ChatGPT and
the Gemini plugin in Gmail. Our findings demonstrated that CLEAR is easy to use
and improves user understanding of data practices and privacy risks. We also
discussed LLM's duality in posing and mitigating privacy risks, offering design
and policy implications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.13221v1">Investigating Effective Speaker Property Privacy Protection in Federated
  Learning for Speech Emotion Recognition</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36">
  <p><b>Published on:</b> 2024-10-17T05:03:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chao Tan, Sheng Li, Yang Cao, Zhao Ren, Tanja Schultz</p>
    <p><b>Summary:</b> Federated Learning (FL) is a privacy-preserving approach that allows servers
to aggregate distributed models transmitted from local clients rather than
training on user data. More recently, FL has been applied to Speech Emotion
Recognition (SER) for secure human-computer interaction applications. Recent
research has found that FL is still vulnerable to inference attacks. To this
end, this paper focuses on investigating the security of FL for SER concerning
property inference attacks. We propose a novel method to protect the property
information in speech data by decomposing various properties in the sound and
adding perturbations to these properties. Our experiments show that the
proposed method offers better privacy-utility trade-offs than existing methods.
The trade-offs enable more effective attack prevention while maintaining
similar FL utility levels. This work can guide future work on privacy
protection methods in speech processing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.12926v1">DEeR: Deviation Eliminating and Noise Regulating for Privacy-preserving
  Federated Low-rank Adaptation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-10-16T18:11:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Meilu Zhu, Axiu Mao, Jun Liu, Yixuan Yuan</p>
    <p><b>Summary:</b> Integrating low-rank adaptation (LoRA) with federated learning (FL) has
received widespread attention recently, aiming to adapt pretrained foundation
models (FMs) to downstream medical tasks via privacy-preserving decentralized
training. However, owing to the direct combination of LoRA and FL, current
methods generally undergo two problems, i.e., aggregation deviation, and
differential privacy (DP) noise amplification effect. To address these
problems, we propose a novel privacy-preserving federated finetuning framework
called \underline{D}eviation \underline{E}liminating and Nois\underline{e}
\underline{R}egulating (DEeR). Specifically, we firstly theoretically prove
that the necessary condition to eliminate aggregation deviation is guaranteing
the equivalence between LoRA parameters of clients. Based on the theoretical
insight, a deviation eliminator is designed to utilize alternating minimization
algorithm to iteratively optimize the zero-initialized and non-zero-initialized
parameter matrices of LoRA, ensuring that aggregation deviation always be zeros
during training. Furthermore, we also conduct an in-depth analysis of the noise
amplification effect and find that this problem is mainly caused by the
``linear relationship'' between DP noise and LoRA parameters. To suppress the
noise amplification effect, we propose a noise regulator that exploits two
regulator factors to decouple relationship between DP and LoRA, thereby
achieving robust privacy protection and excellent finetuning performance.
Additionally, we perform comprehensive ablated experiments to verify the
effectiveness of the deviation eliminator and noise regulator. DEeR shows
better performance on public medical datasets in comparison with
state-of-the-art approaches. The code is available at
https://github.com/CUHK-AIM-Group/DEeR.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.12514v2">Generating Synthetic Functional Data for Privacy-Preserving GPS
  Trajectories</a></h3>
  
  <p><b>Published on:</b> 2024-10-16T12:47:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arianna Burzacchi, Lise Bellanger, Klervi Le Gall, Aymeric Stamm, Simone Vantini</p>
    <p><b>Summary:</b> This research presents FDASynthesis, a novel algorithm designed to generate
synthetic GPS trajectory data while preserving privacy. After pre-processing
the input GPS data, human mobility traces are modeled as multidimensional
curves using Functional Data Analysis (FDA). Then, the synthesis process
identifies the K-nearest trajectories and averages their Square-Root Velocity
Functions (SRVFs) to generate synthetic data. This results in synthetic
trajectories that maintain the utility of the original data while ensuring
privacy. Although applied for human mobility research, FDASynthesis is highly
adaptable to different types of functional data, offering a scalable solution
in various application domains.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.13905v1">P4GCN: Vertical Federated Social Recommendation with Privacy-Preserving
  Two-Party Graph Convolution Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-10-16T12:29:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zheng Wang, Wanwan Wang, Yimin Huang, Zhaopeng Peng, Ziqi Yang, Cheng Wang, Xiaoliang Fan</p>
    <p><b>Summary:</b> In recent years, graph neural networks (GNNs) have been commonly utilized for
social recommendation systems. However, real-world scenarios often present
challenges related to user privacy and business constraints, inhibiting direct
access to valuable social information from other platforms. While many existing
methods have tackled matrix factorization-based social recommendations without
direct social data access, developing GNN-based federated social recommendation
models under similar conditions remains largely unexplored. To address this
issue, we propose a novel vertical federated social recommendation method
leveraging privacy-preserving two-party graph convolution networks (P4GCN) to
enhance recommendation accuracy without requiring direct access to sensitive
social information. First, we introduce a Sandwich-Encryption module to ensure
comprehensive data privacy during the collaborative computing process. Second,
we provide a thorough theoretical analysis of the privacy guarantees,
considering the participation of both curious and honest parties. Extensive
experiments on four real-world datasets demonstrate that P4GCN outperforms
state-of-the-art methods in terms of recommendation accuracy. The code is
available at https://github.com/WwZzz/P4GCN.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.12418v1">Privacy-Preserving Synthetically Augmented Knowledge Graphs with
  Semantic Utility</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-16T10:04:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Luigi Bellomarini, Costanza Catalano, Andrea Coletta, Michela Iezzi, Pierangela Samarati</p>
    <p><b>Summary:</b> Knowledge Graphs (KGs) have recently gained relevant attention in many
application domains, from healthcare to biotechnology, from logistics to
finance. Financial organisations, central banks, economic research entities,
and national supervision authorities apply ontological reasoning on KGs to
address crucial business tasks, such as economic policymaking, banking
supervision, anti-money laundering, and economic research. Reasoning allows for
the generation of derived knowledge capturing complex business semantics and
the set up of effective business processes. A major obstacle in KGs sharing is
represented by privacy considerations since the identity of the data subjects
and their sensitive or company-confidential information may be improperly
exposed.
  In this paper, we propose a novel framework to enable KGs sharing while
ensuring that information that should remain private is not directly released
nor indirectly exposed via derived knowledge, while maintaining the embedded
knowledge of the KGs to support business downstream tasks. Our approach
produces a privacy-preserving synthetic KG as an augmentation of the input one
via the introduction of structural anonymisation. We introduce a novel privacy
measure for KGs, which considers derived knowledge and a new utility metric
that captures the business semantics we want to preserve, and propose two novel
anonymization algorithms. Our extensive experimental evaluation, with both
synthetic graphs and real-world datasets, confirms the effectiveness of our
approach achieving up to a 70% improvement in the privacy of entities compared
to existing methods not specifically designed for KGs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.12402v1">De-Identification of Medical Imaging Data: A Comprehensive Tool for
  Ensuring Patient Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-10-16T09:31:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Moritz Rempe, Lukas Heine, Constantin Seibold, Fabian Hörst, Jens Kleesiek</p>
    <p><b>Summary:</b> Medical data employed in research frequently comprises sensitive patient
health information (PHI), which is subject to rigorous legal frameworks such as
the General Data Protection Regulation (GDPR) or the Health Insurance
Portability and Accountability Act (HIPAA). Consequently, these types of data
must be pseudonymized prior to utilisation, which presents a significant
challenge for many researchers. Given the vast array of medical data, it is
necessary to employ a variety of de-identification techniques. To facilitate
the anonymization process for medical imaging data, we have developed an
open-source tool that can be used to de-identify DICOM magnetic resonance
images, computer tomography images, whole slide images and magnetic resonance
twix raw data. Furthermore, the implementation of a neural network enables the
removal of text within the images. The proposed tool automates an elaborate
anonymization pipeline for multiple types of inputs, reducing the need for
additional tools used for de-identification of imaging data. We make our code
publicly available at
https://github.com/code-lukas/medical_image_deidentification.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.12336v1">Privacy by Design: Bringing User Awareness to Privacy Risks in Internet
  of Things</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-10-16T07:57:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Usama Younus, Rie Kamikubo</p>
    <p><b>Summary:</b> This paper aims to cover and summarize the field of IoT and related privacy
concerns through the lens of privacy by design. With the ever-increasing
incorporation of technology within our daily lives and an ever-growing active
research into smart devices and technologies, privacy concerns are inevitable.
We intend to briefly cover the broad topic of privacy in the IoT space, the
inherent challenges and risks in such systems, and a few recent techniques that
intend to resolve these issues on the subdomain level and a system scale level.
We then proceed to approach this situation through design thinking and
privacy-by-design, given that most of the prior efforts are based on resolving
privacy concerns on technical grounds with system-level design. We participated
in a co-design workshop for the privacy of a content creation platform and used
those findings to deploy a survey-based mechanism to tackle some key concern
areas for user groups and formulate design principles for privacy that promote
transparent, user-centered, and awareness-provoking privacy design.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.12309v1">Correction to Local Information Privacy and Its Applications to Data
  Aggregation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-16T07:22:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bo Jiang, Ming Li, Ravi Tandon</p>
    <p><b>Summary:</b> In our previous works, we defined Local Information Privacy (LIP) as a
context-aware privacy notion and presented the corresponding privacy-preserving
mechanism. Then we claim that the mechanism satisfies epsilon-LIP for any
epsilon>0 for arbitrary Px. However, this claim is not completely correct. In
this document, we provide a correction to the valid range of privacy parameters
of our previously proposed LIP mechanism. Further, we propose efficient
algorithms to expand the range of valid privacy parameters. Finally, we discuss
the impact of updated results on our original paper's experiments, the
rationale of the proposed correction and corrected results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.12045v1">Differential Privacy on Trust Graphs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B">
  <p><b>Published on:</b> 2024-10-15T20:31:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Badih Ghazi, Ravi Kumar, Pasin Manurangsi, Serena Wang</p>
    <p><b>Summary:</b> We study differential privacy (DP) in a multi-party setting where each party
only trusts a (known) subset of the other parties with its data. Specifically,
given a trust graph where vertices correspond to parties and neighbors are
mutually trusting, we give a DP algorithm for aggregation with a much better
privacy-utility trade-off than in the well-studied local model of DP (where
each party trusts no other party). We further study a robust variant where each
party trusts all but an unknown subset of at most $t$ of its neighbors (where
$t$ is a given parameter), and give an algorithm for this setting. We
complement our algorithms with lower bounds, and discuss implications of our
work to other tasks in private learning and analytics.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.11906v1">Empowering Users in Digital Privacy Management through Interactive
  LLM-Based Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-15T02:16:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bolun Sun, Yifan Zhou, Haiyun Jiang</p>
    <p><b>Summary:</b> This paper presents a novel application of large language models (LLMs) to
enhance user comprehension of privacy policies through an interactive dialogue
agent. We demonstrate that LLMs significantly outperform traditional models in
tasks like Data Practice Identification, Choice Identification, Policy
Summarization, and Privacy Question Answering, setting new benchmarks in
privacy policy analysis. Building on these findings, we introduce an innovative
LLM-based agent that functions as an expert system for processing website
privacy policies, guiding users through complex legal language without
requiring them to pose specific questions. A user study with 100 participants
showed that users assisted by the agent had higher comprehension levels (mean
score of 2.6 out of 3 vs. 1.8 in the control group), reduced cognitive load
(task difficulty ratings of 3.2 out of 10 vs. 7.8), increased confidence in
managing privacy, and completed tasks in less time (5.5 minutes vs. 15.8
minutes). This work highlights the potential of LLM-based agents to transform
user interaction with privacy policies, leading to more informed consent and
empowering users in the digital services landscape.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.09721v1">"I inherently just trust that it works": Investigating Mental Models of
  Open-Source Libraries for Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-10-13T04:24:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Patrick Song, Jayshree Sarathy, Michael Shoemate, Salil Vadhan</p>
    <p><b>Summary:</b> Differential privacy (DP) is a promising framework for privacy-preserving
data science, but recent studies have exposed challenges in bringing this
theoretical framework for privacy into practice. These tensions are
particularly salient in the context of open-source software libraries for DP
data analysis, which are emerging tools to help data stewards and analysts
build privacy-preserving data pipelines for their applications. While there has
been significant investment into such libraries, we need further inquiry into
the role of these libraries in promoting understanding of and trust in DP, and
in turn, the ways in which design of these open-source libraries can shed light
on the challenges of creating trustworthy data infrastructures in practice. In
this study, we use qualitative methods and mental models approaches to analyze
the differences between conceptual models used to design open-source DP
libraries and mental models of DP held by users. Through a two-stage study
design involving formative interviews with 5 developers of open-source DP
libraries and user studies with 17 data analysts, we find that DP libraries
often struggle to bridge the gaps between developer and user mental models. In
particular, we highlight the tension DP libraries face in maintaining rigorous
DP implementations and facilitating user interaction. We conclude by offering
practical recommendations for further development of DP libraries.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.09506v1">Distribution-Aware Mean Estimation under User-level Local Differential
  Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2024-10-12T11:57:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Corentin Pla, Hugo Richard, Maxime Vono</p>
    <p><b>Summary:</b> We consider the problem of mean estimation under user-level local
differential privacy, where $n$ users are contributing through their local pool
of data samples. Previous work assume that the number of data samples is the
same across users. In contrast, we consider a more general and realistic
scenario where each user $u \in [n]$ owns $m_u$ data samples drawn from some
generative distribution $\mu$; $m_u$ being unknown to the statistician but
drawn from a known distribution $M$ over $\mathbb{N}^\star$. Based on a
distribution-aware mean estimation algorithm, we establish an $M$-dependent
upper bounds on the worst-case risk over $\mu$ for the task of mean estimation.
We then derive a lower bound. The two bounds are asymptotically matching up to
logarithmic factors and reduce to known bounds when $m_u = m$ for any user $u$.</p>
  </details>
</div>



<h2>2024-11</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2411.07806v1">Federated Low-Rank Adaptation with Differential Privacy over Wireless
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
  <h3><a href="http://arxiv.org/abs/2411.07468v1">Privacy-Preserving Verifiable Neural Network Inference Service</a></h3>
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
  <h3><a href="http://arxiv.org/abs/2411.06317v1">Harpocrates: Oblivious Privacy in a Statically Typed World</a></h3>
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
  <h3><a href="http://arxiv.org/abs/2411.01357v1">WaKA: Data Attribution using K-Nearest Neighbors and Membership Privacy
  Principles</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-11-02T20:27:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Patrick Mesana, Clément Bénesse, Hadrien Lautraite, Gilles Caporossi, Sébastien Gambs</p>
    <p><b>Summary:</b> In this paper, we introduce WaKA (Wasserstein K-nearest neighbors
Attribution), a novel attribution method that leverages principles from the
LiRA (Likelihood Ratio Attack) framework and applies them to \( k \)-nearest
neighbors classifiers (\( k \)-NN). WaKA efficiently measures the contribution
of individual data points to the model's loss distribution, analyzing every
possible \( k \)-NN that can be constructed using the training set, without
requiring sampling or shadow model training. WaKA can be used \emph{a
posteriori} as a membership inference attack (MIA) to assess privacy risks, and
\emph{a priori} for data minimization and privacy influence measurement. Thus,
WaKA can be seen as bridging the gap between data attribution and membership
inference attack (MIA) literature by distinguishing between the value of a data
point and its privacy risk. For instance, we show that self-attribution values
are more strongly correlated with the attack success rate than the contribution
of a point to model generalization. WaKA's different usages were also evaluated
across diverse real-world datasets, demonstrating performance very close to
LiRA when used as an MIA on \( k \)-NN classifiers, but with greater
computational efficiency.</p>
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
  <h3><a href="http://arxiv.org/abs/2411.01140v1">Privacy-Preserving Federated Learning with Differentially Private
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

