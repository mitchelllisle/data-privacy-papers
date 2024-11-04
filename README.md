
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
  <h3><a href="http://arxiv.org/abs/2410.21605v1">Accelerating Privacy-Preserving Medical Record Linkage: A Three-Party
  MPC Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2024-10-28T23:13:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Şeyma Selcan Mağara, Noah Dietrich, Ali Burak Ünal, Mete Akgün</p>
    <p><b>Summary:</b> Motivation: Record linkage is a crucial concept for integrating data from
multiple sources, particularly when datasets lack exact identifiers, and it has
diverse applications in real-world data analysis. Privacy-Preserving Record
Linkage (PPRL) ensures this integration occurs securely, protecting sensitive
information from unauthorized access. This is especially important in sectors
such as healthcare, where datasets include private identity information (IDAT)
governed by strict privacy laws. However, maintaining both privacy and
efficiency in large-scale record linkage poses significant challenges.
Consequently, researchers must develop advanced methods to protect data privacy
while optimizing processing performance. This paper presents a novel and
efficient PPRL method based on a secure 3-party computation (MPC) framework.
Our approach allows multiple parties to compute linkage results without
exposing their private inputs and significantly improves the speed of linkage
process compared to existing privacy-preserving solutions. Results: We
demonstrated that our method preserves the linkage quality of the
state-of-the-art PPRL method while achieving up to 14 times faster performance.
For example, linking a record against a database of 10,000 records takes just
8.74 seconds in a realistic network with 700 Mbps bandwidth and 60 ms latency.
Even on a slower internet connection with 100 Mbps bandwidth and 60 ms latency,
the linkage completes in 28 seconds, highlighting the scalability and
efficiency of our solution.</p>
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
  <h3><a href="http://arxiv.org/abs/2410.19548v2">FLiP: Privacy-Preserving Federated Learning based on the Principle of
  Least Privileg</a></h3>
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
  <h3><a href="http://arxiv.org/abs/2410.12514v1">Generating Synthetic Functional Data for Privacy-Preserving GPS
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


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.08756v1">Privacy-Preserving Optimal State Estimation with Low Complexity via
  Cramér-Rao Lower Bound Approach</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2024-10-11T12:15:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Liping Guo, Jimin Wang, Yanlong Zhao, Ji-Feng Zhang</p>
    <p><b>Summary:</b> This paper addresses the optimal state estimation problem for dynamic systems
while preserving private information against an adversary. To dominate the
adversary's estimation accuracy about private information in the mean square
error (MSE) sense, the Cram\'er-Rao lower bound (CRLB) is employed to evaluate
privacy level. The problem is formulated as a constrained optimization, which
minimizes the MSE of the state estimate with a constraint on privacy level,
achieving a trade-off between privacy and utility. To solve the constrained
optimization problem, an explicit expression for CRLB is first provided using
the information inequality. To overcome the increasing sizes of the involved
matrices over time, a low-complexity approach is then proposed to achieve
online calculation for CRLB, significantly reducing computational complexity.
Next, the optimization problem is relaxed to a semi-definite programming
problem, and a relaxed solution is provided. Finally, a privacy-preserving
state estimation algorithm with low complexity is developed and proved to
achieve differential privacy. Two illustrative examples, including a practical
case of building occupancy, demonstrate the effectiveness of the proposed
algorithm.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.08755v1">PILLAR: an AI-Powered Privacy Threat Modeling Tool</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2024-10-11T12:13:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Majid Mollaeefar, Andrea Bissoli, Silvio Ranise</p>
    <p><b>Summary:</b> The rapid evolution of Large Language Models (LLMs) has unlocked new
possibilities for applying artificial intelligence across a wide range of
fields, including privacy engineering. As modern applications increasingly
handle sensitive user data, safeguarding privacy has become more critical than
ever. To protect privacy effectively, potential threats need to be identified
and addressed early in the system development process. Frameworks like LINDDUN
offer structured approaches for uncovering these risks, but despite their
value, they often demand substantial manual effort, expert input, and detailed
system knowledge. This makes the process time-consuming and prone to errors.
Current privacy threat modeling methods, such as LINDDUN, typically rely on
creating and analyzing complex data flow diagrams (DFDs) and system
descriptions to pinpoint potential privacy issues. While these approaches are
thorough, they can be cumbersome, relying heavily on the precision of the data
provided by users. Moreover, they often generate a long list of threats without
clear guidance on how to prioritize them, leaving developers unsure of where to
focus their efforts. In response to these challenges, we introduce PILLAR
(Privacy risk Identification with LINDDUN and LLM Analysis Report), a new tool
that integrates LLMs with the LINDDUN framework to streamline and enhance
privacy threat modeling. PILLAR automates key parts of the LINDDUN process,
such as generating DFDs, classifying threats, and prioritizing risks. By
leveraging the capabilities of LLMs, PILLAR can take natural language
descriptions of systems and transform them into comprehensive threat models
with minimal input from users, reducing the workload on developers and privacy
experts while improving the efficiency and accuracy of the process.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.08555v1">Design of Secure, Privacy-focused, and Accessible E-Payment Applications
  for Older Adults</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-10-11T06:12:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sanchari Das</p>
    <p><b>Summary:</b> E-payments are essential for transactional convenience in today's digital
economy and are becoming increasingly important for older adults, emphasizing
the need for enhanced security, privacy, and usability. To address this, we
conducted a survey-based study with 400 older adults aged 65 and above to
evaluate a high-fidelity prototype of an e-payment mobile application, which
included features such as multi-factor authentication (MFA) and QR code-based
recipient addition. Based on our findings, we developed a tailored \b{eta}
version of the application to meet the specific needs of this demographic.
Notably, approximately 91% of participants preferred traditional
knowledge-based and single-mode authentication compared to expert-recommended
MFA. We concluded by providing recommendations aimed at developing inclusive
e-payment solutions that address the security, privacy, and usability
requirements of older adults.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.08553v1">Balancing Innovation and Privacy: Data Security Strategies in Natural
  Language Processing Applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-10-11T06:05:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shaobo Liu, Guiran Liu, Binrong Zhu, Yuanshuai Luo, Linxiao Wu, Rui Wang</p>
    <p><b>Summary:</b> This research addresses privacy protection in Natural Language Processing
(NLP) by introducing a novel algorithm based on differential privacy, aimed at
safeguarding user data in common applications such as chatbots, sentiment
analysis, and machine translation. With the widespread application of NLP
technology, the security and privacy protection of user data have become
important issues that need to be solved urgently. This paper proposes a new
privacy protection algorithm designed to effectively prevent the leakage of
user sensitive information. By introducing a differential privacy mechanism,
our model ensures the accuracy and reliability of data analysis results while
adding random noise. This method not only reduces the risk caused by data
leakage but also achieves effective processing of data while protecting user
privacy. Compared to traditional privacy methods like data anonymization and
homomorphic encryption, our approach offers significant advantages in terms of
computational efficiency and scalability while maintaining high accuracy in
data analysis. The proposed algorithm's efficacy is demonstrated through
performance metrics such as accuracy (0.89), precision (0.85), and recall
(0.88), outperforming other methods in balancing privacy and utility. As
privacy protection regulations become increasingly stringent, enterprises and
developers must take effective measures to deal with privacy risks. Our
research provides an important reference for the application of privacy
protection technology in the field of NLP, emphasizing the need to achieve a
balance between technological innovation and user privacy. In the future, with
the continuous advancement of technology, privacy protection will become a core
element of data-driven applications and promote the healthy development of the
entire industry.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.08462v1">Driving Privacy Forward: Mitigating Information Leakage within Smart
  Vehicles through Synthetic Data Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-10-11T02:28:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Krish Parikh</p>
    <p><b>Summary:</b> Smart vehicles produce large amounts of data, much of which is sensitive and
at risk of privacy breaches. As attackers increasingly exploit anonymised
metadata within these datasets to profile drivers, it's important to find
solutions that mitigate this information leakage without hindering innovation
and ongoing research. Synthetic data has emerged as a promising tool to address
these privacy concerns, as it allows for the replication of real-world data
relationships while minimising the risk of revealing sensitive information. In
this paper, we examine the use of synthetic data to tackle these challenges. We
start by proposing a comprehensive taxonomy of 14 in-vehicle sensors,
identifying potential attacks and categorising their vulnerability. We then
focus on the most vulnerable signals, using the Passive Vehicular Sensor (PVS)
dataset to generate synthetic data with a Tabular Variational Autoencoder
(TVAE) model, which included over 1 million data points. Finally, we evaluate
this against 3 core metrics: fidelity, utility, and privacy. Our results show
that we achieved 90.1% statistical similarity and 78% classification accuracy
when tested on its original intent while also preventing the profiling of the
driver. The code can be found at
https://github.com/krish-parikh/Synthetic-Data-Generation</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.08381v1">Assessing Privacy Policies with AI: Ethical, Legal, and Technical
  Challenges</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-10-10T21:36:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Irem Aydin, Hermann Diebel-Fischer, Vincent Freiberger, Julia Möller-Klapperich, Erik Buchmann, Michael Färber, Anne Lauber-Rönsberg, Birte Platow</p>
    <p><b>Summary:</b> The growing use of Machine Learning and Artificial Intelligence (AI),
particularly Large Language Models (LLMs) like OpenAI's GPT series, leads to
disruptive changes across organizations. At the same time, there is a growing
concern about how organizations handle personal data. Thus, privacy policies
are essential for transparency in data processing practices, enabling users to
assess privacy risks. However, these policies are often long and complex. This
might lead to user confusion and consent fatigue, where users accept data
practices against their interests, and abusive or unfair practices might go
unnoticed. LLMss can be used to assess privacy policies for users
automatically. In this interdisciplinary work, we explore the challenges of
this approach in three pillars, namely technical feasibility, ethical
implications, and legal compatibility of using LLMs to assess privacy policies.
Our findings aim to identify potential for future research, and to foster a
discussion on the use of LLM technologies for enabling users to fulfil their
important role as decision-makers in a constantly developing AI-driven digital
economy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.08302v1">A Framework to Audit Email Address Privacy and Analyze Email Marketing
  Practices of Online Services and Apps</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-10T18:44:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Scott Seidenberger, Oluwasijibomi Ajisegiri, Noah Pursell, Fazil Raja, Anindya Maiti</p>
    <p><b>Summary:</b> This study explores the widespread perception that personal data, such as
email addresses, may be shared or sold without informed user consent,
investigating whether these concerns are reflected in actual practices of
popular online services and apps. Over the course of a year, we collected and
analyzed the source, volume, frequency, and content of emails received by users
after signing up for the 150 most popular online services and apps across
various sectors. By examining patterns in email communications, we aim to
identify consistent strategies used across industries, including potential
signs of third-party data sharing. This analysis provides a critical evaluation
of how email marketing tactics may intersect with data-sharing practices, with
important implications for consumer privacy and regulatory oversight. Our study
findings, conducted post-CCPA and GDPR, indicate that while no third-party spam
email was detected, internal email marketing practices were pervasive, with
companies frequently sending promotional and CRM emails despite opt-out
preferences. The framework established in this work is designed to be scalable,
allowing for continuous monitoring, and can be extended to include a more
diverse set of apps and services for broader analysis, ultimately contributing
to improved user perception of data privacy practices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.08122v1">PP-GWAS: Privacy Preserving Multi-Site Genome-wide Association Studies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-10T17:07:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arjhun Swaminathan, Anika Hannemann, Ali Burak Ünal, Nico Pfeifer, Mete Akgün</p>
    <p><b>Summary:</b> Genome-wide association studies are pivotal in understanding the genetic
underpinnings of complex traits and diseases. Collaborative, multi-site GWAS
aim to enhance statistical power but face obstacles due to the sensitive nature
of genomic data sharing. Current state-of-the-art methods provide a
privacy-focused approach utilizing computationally expensive methods such as
Secure Multi-Party Computation and Homomorphic Encryption. In this context, we
present a novel algorithm PP-GWAS designed to improve upon existing standards
in terms of computational efficiency and scalability without sacrificing data
privacy. This algorithm employs randomized encoding within a distributed
architecture to perform stacked ridge regression on a Linear Mixed Model to
ensure rigorous analysis. Experimental evaluation with real world and synthetic
data indicates that PP-GWAS can achieve computational speeds twice as fast as
similar state-of-the-art algorithms while using lesser computational resources,
all while adhering to a robust security model that caters to an all-but-one
semi-honest adversary setting. We have assessed its performance using various
datasets, emphasizing its potential in facilitating more efficient and private
genomic analyses.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.07900v2">CL3: A Collaborative Learning Framework for the Medical Data Ensuring
  Data Privacy in the Hyperconnected Environment</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-10-10T13:29:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohamamd Zavid Parvez, Rafiqul Islam, Md Zahidul Islam</p>
    <p><b>Summary:</b> In a hyperconnected environment, medical institutions are particularly
concerned with data privacy when sharing and transmitting sensitive patient
information due to the risk of data breaches, where malicious actors could
intercept sensitive information. A collaborative learning framework, including
transfer, federated, and incremental learning, can generate efficient, secure,
and scalable models while requiring less computation, maintaining patient data
privacy, and ensuring an up-to-date model. This study aims to address the
detection of COVID-19 using chest X-ray images through a proposed collaborative
learning framework called CL3. Initially, transfer learning is employed,
leveraging knowledge from a pre-trained model as the starting global model.
Local models from different medical institutes are then integrated, and a new
global model is constructed to adapt to any data drift observed in the local
models. Additionally, incremental learning is considered, allowing continuous
adaptation to new medical data without forgetting previously learned
information. Experimental results demonstrate that the CL3 framework achieved a
global accuracy of 89.99% when using Xception with a batch size of 16 after
being trained for six federated communication rounds. A demo of the CL3
framework is available at
https://github.com/zavidparvez/CL3-Collaborative-Approach to ensure
reproducibility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.07772v1">Towards Quantifying The Privacy Of Redacted Text</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-10-10T10:00:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vaibhav Gusain, Douglas Leith</p>
    <p><b>Summary:</b> In this paper we propose use of a k-anonymity-like approach for evaluating
the privacy of redacted text. Given a piece of redacted text we use a state of
the art transformer-based deep learning network to reconstruct the original
text. This generates multiple full texts that are consistent with the redacted
text, i.e. which are grammatical, have the same non-redacted words etc, and
represents each of these using an embedding vector that captures sentence
similarity. In this way we can estimate the number, diversity and quality of
full text consistent with the redacted text and so evaluate privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.07632v1">Provable Privacy Attacks on Trained Shallow Neural Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-10T05:54:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guy Smorodinsky, Gal Vardi, Itay Safran</p>
    <p><b>Summary:</b> We study what provable privacy attacks can be shown on trained, 2-layer ReLU
neural networks. We explore two types of attacks; data reconstruction attacks,
and membership inference attacks. We prove that theoretical results on the
implicit bias of 2-layer neural networks can be used to provably reconstruct a
set of which at least a constant fraction are training points in a univariate
setting, and can also be used to identify with high probability whether a given
point was used in the training set in a high dimensional setting. To the best
of our knowledge, our work is the first to show provable vulnerabilities in
this setting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.11876v1">Rescriber: Smaller-LLM-Powered User-Led Data Minimization for Navigating
  Privacy Trade-offs in LLM-Based Conversational Agent</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-10T01:23:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jijie Zhou, Eryue Xu, Yaoyao Wu, Tianshi Li</p>
    <p><b>Summary:</b> The proliferation of LLM-based conversational agents has resulted in
excessive disclosure of identifiable or sensitive information. However,
existing technologies fail to offer perceptible control or account for users'
personal preferences about privacy-utility tradeoffs due to the lack of user
involvement. To bridge this gap, we designed, built, and evaluated Rescriber, a
browser extension that supports user-led data minimization in LLM-based
conversational agents by helping users detect and sanitize personal information
in their prompts. Our studies (N=12) showed that Rescriber helped users reduce
unnecessary disclosure and addressed their privacy concerns. Users' subjective
perceptions of the system powered by Llama3-8B were on par with that by GPT-4.
The comprehensiveness and consistency of the detection and sanitization emerge
as essential factors that affect users' trust and perceived protection. Our
findings confirm the viability of smaller-LLM-powered, user-facing, on-device
privacy controls, presenting a promising approach to address the privacy and
trust challenges of AI.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.07414v1">Bayes-Nash Generative Privacy Protection Against Membership Inference
  Attacks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-09T20:29:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tao Zhang, Rajagopal Venkatesaraman, Rajat K. De, Bradley A. Malin, Yevgeniy Vorobeychik</p>
    <p><b>Summary:</b> An ability to share data, even in aggregated form, is critical to advancing
both conventional and data science. However, insofar as such datasets are
comprised of individuals, their membership in these datasets is often viewed as
sensitive, with membership inference attacks (MIAs) threatening to violate
their privacy. We propose a Bayesian game model for privacy-preserving
publishing of data-sharing mechanism outputs (for example, summary statistics
for sharing genomic data). In this game, the defender minimizes a combination
of expected utility and privacy loss, with the latter being maximized by a
Bayes-rational attacker. We propose a GAN-style algorithm to approximate a
Bayes-Nash equilibrium of this game, and introduce the notions of Bayes-Nash
generative privacy (BNGP) and Bayes generative privacy (BGP) risk that aims to
optimally balance the defender's privacy and utility in a way that is robust to
the attacker's heterogeneous preferences with respect to true and false
positives. We demonstrate the properties of composition and post-processing for
BGP risk and establish conditions under which BNGP and pure differential
privacy (PDP) are equivalent. We apply our method to sharing summary
statistics, where MIAs can re-identify individuals even from aggregated data.
Theoretical analysis and empirical results demonstrate that our Bayesian
game-theoretic method outperforms state-of-the-art approaches for
privacy-preserving sharing of summary statistics.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.06814v1">Defending Membership Inference Attacks via Privacy-aware Sparsity Tuning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-10-09T12:13:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qiang Hu, Hengxiang Zhang, Hongxin Wei</p>
    <p><b>Summary:</b> Over-parameterized models are typically vulnerable to membership inference
attacks, which aim to determine whether a specific sample is included in the
training of a given model. Previous Weight regularizations (e.g., L1
regularization) typically impose uniform penalties on all parameters, leading
to a suboptimal tradeoff between model utility and privacy. In this work, we
first show that only a small fraction of parameters substantially impact the
privacy risk. In light of this, we propose Privacy-aware Sparsity Tuning
(PAST), a simple fix to the L1 Regularization, by employing adaptive penalties
to different parameters. Our key idea behind PAST is to promote sparsity in
parameters that significantly contribute to privacy leakage. In particular, we
construct the adaptive weight for each parameter based on its privacy
sensitivity, i.e., the gradient of the loss gap with respect to the parameter.
Using PAST, the network shrinks the loss gap between members and non-members,
leading to strong resistance to privacy attacks. Extensive experiments
demonstrate the superiority of PAST, achieving a state-of-the-art balance in
the privacy-utility trade-off.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.06587v1">Bots can Snoop: Uncovering and Mitigating Privacy Risks of Bots in Group
  Chats</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-09T06:37:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kai-Hsiang Chou, Yi-Min Lin, Yi-An Wang, Jonathan Weiping Li, Tiffany Hyun-Jin Kim, Hsu-Chun Hsiao</p>
    <p><b>Summary:</b> New privacy concerns arise with chatbots on group messaging platforms.
Chatbots may access information beyond their intended functionalities, such as
messages unintended for chatbots or sender's identities. Chatbot operators may
exploit such information to infer personal information and link users across
groups, potentially leading to personal data breaches, pervasive tracking, and
targeted advertising. Our analysis of conversation datasets shows that (1)
chatbots often access far more messages than needed, and (2) when a user joins
a new group with chatbots, there is a 3.4% chance that at least one of the
chatbots can recognize and associate the user with their previous interactions
in other groups. Although state-of-the-art group messaging protocols provide
robust end-to-end security and some platforms have implemented policies to
limit chatbot access, no platforms successfully combine these features. This
paper introduces SnoopGuard, a secure group messaging protocol that ensures
user privacy against chatbots while maintaining strong end-to-end security. Our
method offers selective message access, preventing chatbots from accessing
unrelated messages, and ensures sender anonymity within the group. SnoopGuard
achieves $O(\log n + m)$ message-sending complexity for a group of $n$ users
and $m$ chatbots, compared to $O(\log(n + m))$ in state-of-the-art protocols,
with acceptable overhead for enhanced privacy. Our prototype implementation
shows that sending a message in a group of 50 users and 10 chatbots takes about
30 milliseconds when integrated with Message Layer Security (MLS).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.06266v1">Near Exact Privacy Amplification for Matrix Mechanisms</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-08T18:05:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Christopher A. Choquette-Choo, Arun Ganesh, Saminul Haque, Thomas Steinke, Abhradeep Thakurta</p>
    <p><b>Summary:</b> We study the problem of computing the privacy parameters for DP machine
learning when using privacy amplification via random batching and noise
correlated across rounds via a correlation matrix $\textbf{C}$ (i.e., the
matrix mechanism). Past work on this problem either only applied to banded
$\textbf{C}$, or gave loose privacy parameters. In this work, we give a
framework for computing near-exact privacy parameters for any lower-triangular,
non-negative $\textbf{C}$. Our framework allows us to optimize the correlation
matrix $\textbf{C}$ while accounting for amplification, whereas past work could
not. Empirically, we show this lets us achieve smaller RMSE on prefix sums than
the previous state-of-the-art (SOTA). We also show that we can improve on the
SOTA performance on deep learning tasks. Our two main technical tools are (i)
using Monte Carlo accounting to bypass composition, which was the main
technical challenge for past work, and (ii) a "balls-in-bins" batching scheme
that enables easy privacy analysis and is closer to practical random batching
than Poisson sampling.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.05930v1">Fortify Your Foundations: Practical Privacy and Security for Foundation
  Model Deployments In The Cloud</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-10-08T11:33:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marcin Chrapek, Anjo Vahldiek-Oberwagner, Marcin Spoczynski, Scott Constable, Mona Vij, Torsten Hoefler</p>
    <p><b>Summary:</b> Foundation Models (FMs) display exceptional performance in tasks such as
natural language processing and are being applied across a growing range of
disciplines. Although typically trained on large public datasets, FMs are often
fine-tuned or integrated into Retrieval-Augmented Generation (RAG) systems,
which rely on private data. This access, along with their size and costly
training, heightens the risk of intellectual property theft. Moreover,
multimodal FMs may expose sensitive information. In this work, we examine the
FM threat model and discuss the practicality and comprehensiveness of various
approaches for securing against them, such as ML-based methods and trusted
execution environments (TEEs). We demonstrate that TEEs offer an effective
balance between strong security properties, usability, and performance.
Specifically, we present a solution achieving less than 10\% overhead versus
bare metal for the full Llama2 7B and 13B inference pipelines running inside
\intel\ SGX and \intel\ TDX. We also share our configuration files and insights
from our implementation. To our knowledge, our work is the first to show the
practicality of TEEs for securing FMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.05907v1">Privacy-Enhanced Over-the-Air Federated Learning via Client-Driven Power
  Balancing</a></h3>
  
  <p><b>Published on:</b> 2024-10-08T11:05:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bumjun Kim, Hyowoon Seo, Wan Choi</p>
    <p><b>Summary:</b> This paper introduces a novel privacy-enhanced over-the-air Federated
Learning (OTA-FL) framework using client-driven power balancing (CDPB) to
address privacy concerns in OTA-FL systems. In recent studies, a server
determines the power balancing based on the continuous transmission of channel
state information (CSI) from each client. Furthermore, they concentrate on
fulfilling privacy requirements in every global iteration, which can heighten
the risk of privacy exposure as the learning process extends. To mitigate these
risks, we propose two CDPB strategies -- CDPB-n (noisy) and CDPB-i (idle) --
allowing clients to adjust transmission power independently, without sharing
CSI. CDPB-n transmits noise during poor conditions, while CDPB-i pauses
transmission until conditions improve. To further enhance privacy and learning
efficiency, we show a mixed strategy, CDPB-mixed, which combines CDPB-n and
CDPB-i. Our experimental results show that CDPB outperforms traditional
approaches in terms of model accuracy and privacy guarantees, providing a
practical solution for enhancing OTA-FL in resource-constrained environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.05842v1">Privacy-aware Fully Model-Free Event-triggered Cloud-based HVAC Control</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2024-10-08T09:15:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhenan Feng, Ehsan Nekouei</p>
    <p><b>Summary:</b> Privacy is a major concern when computing-as-a-service (CaaS) platforms,
e.g., cloud-computing platforms, are utilized for building automation, as CaaS
platforms can infer sensitive information, such as occupancy, using the sensor
measurements of a building. Although the existing encrypted model-based control
algorithms can ensure the security and privacy of sensor measurements, they are
highly complex to implement and require high computational resources, which
result in a high cost of using CaaS platforms. To address these issues, in this
paper, we propose an encrypted fully model-free event-triggered cloud-based
HVAC control framework that ensures the privacy of occupancy information and
minimizes the communication and computation overhead associated with encrypted
HVAC control. To this end, we first develop a model-free controller for
regulating indoor temperature and CO2 levels. We then design a model-free
event-triggering unit which reduces the communication and computation costs of
encrypted HVAC control using an optimal triggering policy. Finally, we evaluate
the performance of the proposed encrypted fully model-free event-triggered
cloud-based HVAC control framework using the TRNSYS simulator, comparing it to
an encrypted model-based event-triggered control framework, which uses model
predictive control to regulate the indoor climate. Our numerical results
demonstrate that, compared to the encrypted model-based method, the proposed
fully model-free framework improves the control performance while reducing the
communication and computation costs. More specifically, it reduces the
communication between the system and the CaaS platform by 64% amount, and its
computation time is 75% less than that of the model-based control.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.05725v2">KnowledgeSG: Privacy-Preserving Synthetic Text Generation with Knowledge
  Distillation from Server</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-10-08T06:42:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenhao Wang, Xiaoyu Liang, Rui Ye, Jingyi Chai, Siheng Chen, Yanfeng Wang</p>
    <p><b>Summary:</b> The success of large language models (LLMs) facilitate many parties to
fine-tune LLMs on their own private data. However, this practice raises privacy
concerns due to the memorization of LLMs. Existing solutions, such as utilizing
synthetic data for substitution, struggle to simultaneously improve performance
and preserve privacy. They either rely on a local model for generation,
resulting in a performance decline, or take advantage of APIs, directly
exposing the data to API servers. To address this issue, we propose
KnowledgeSG, a novel client-server framework which enhances synthetic data
quality and improves model performance while ensuring privacy. We achieve this
by learning local knowledge from the private data with differential privacy
(DP) and distilling professional knowledge from the server. Additionally,
inspired by federated learning, we transmit models rather than data between the
client and server to prevent privacy leakage. Extensive experiments in medical
and financial domains demonstrate the effectiveness of KnowledgeSG. Our code is
now publicly available at https://github.com/wwh0411/KnowledgeSG.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.05653v1">A Blockchain-Enhanced Framework for Privacy and Data Integrity in
  Crowdsourced Drone Services</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-08T03:08:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Junaid Akram, Ali Anaissi</p>
    <p><b>Summary:</b> We present an innovative framework that integrates consumer-grade drones into
bushfire management, addressing both service improvement and data privacy
concerns under Australia's Privacy Act 1988. This system establishes a
marketplace where bushfire management authorities, as data consumers, access
critical information from drone operators, who serve as data providers. The
framework employs local differential privacy to safeguard the privacy of data
providers from all system entities, ensuring compliance with privacy standards.
Additionally, a blockchain-based solution facilitates fair data and fee
exchanges while maintaining immutable records for enhanced accountability.
Validated through a proof-of-concept implementation, the framework's
scalability and adaptability make it well-suited for large-scale, real-world
applications in bushfire management.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.05506v1">Privacy Vulnerabilities in Marginals-based Synthetic Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-10-07T21:24:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Steven Golob, Sikha Pentyala, Anuar Maratkhan, Martine De Cock</p>
    <p><b>Summary:</b> When acting as a privacy-enhancing technology, synthetic data generation
(SDG) aims to maintain a resemblance to the real data while excluding
personally-identifiable information. Many SDG algorithms provide robust
differential privacy (DP) guarantees to this end. However, we show that the
strongest class of SDG algorithms--those that preserve \textit{marginal
probabilities}, or similar statistics, from the underlying data--leak
information about individuals that can be recovered more efficiently than
previously understood. We demonstrate this by presenting a novel membership
inference attack, MAMA-MIA, and evaluate it against three seminal DP SDG
algorithms: MST, PrivBayes, and Private-GSD. MAMA-MIA leverages knowledge of
which SDG algorithm was used, allowing it to learn information about the hidden
data more accurately, and orders-of-magnitude faster, than other leading
attacks. We use MAMA-MIA to lend insight into existing SDG vulnerabilities. Our
approach went on to win the first SNAKE (SaNitization Algorithm under attacK
... $\varepsilon$) competition.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.05033v1">Extended Functional Representation Lemma: A Tool For Privacy, Semantic
  Representation, Caching, and Compression Design</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2024-10-07T13:33:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Amirreza Zamani, Mikael Skoglund</p>
    <p><b>Summary:</b> This paper provides an overview of a problem in information-theoretic privacy
mechanism design, addressing two scenarios in which private data is either
observable or hidden. In each scenario, different privacy measures are used,
including bounded mutual information and two types of per-letter privacy
constraints. Considering the first scenario, an agent observes useful data that
is correlated with private data, and wants to disclose the useful information
to a user. Due to the privacy concerns, direct disclosure is prohibited. Hence,
a privacy mechanism is designed to generate disclosed data which maximizes the
revealed information about the useful data while satisfying a privacy
constraint. In the second scenario, the agent has additionally access to the
private data. We discuss how the Functional Representation Lemma, the Strong
Functional Representation Lemma, and their extended versions are useful for
designing low-complexity privacy mechanisms that achieve optimal
privacy-utility trade-offs under certain constraints. Furthermore, another
privacy design problem is presented where part of the private attribute is more
private than the remaining part. Finally, we provide applications including
semantic communications, caching and delivery, and compression designs, where
the approach can be applied.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.05020v1">FRIDA: Free-Rider Detection using Privacy Attacks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-07T13:20:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pol G. Recasens, Ádám Horváth, Alberto Gutierrez-Torre, Jordi Torres, Josep Ll. Berral, Balázs Pejó</p>
    <p><b>Summary:</b> Federated learning is increasingly popular as it enables multiple parties
with limited datasets and resources to train a high-performing machine learning
model collaboratively. However, similarly to other collaborative systems,
federated learning is vulnerable to free-riders -- participants who do not
contribute to the training but still benefit from the shared model. Free-riders
not only compromise the integrity of the learning process but also slow down
the convergence of the global model, resulting in increased costs for the
honest participants.
  To address this challenge, we propose FRIDA: free-rider detection using
privacy attacks, a framework that leverages inference attacks to detect
free-riders. Unlike traditional methods that only capture the implicit effects
of free-riding, FRIDA directly infers details of the underlying training
datasets, revealing characteristics that indicate free-rider behaviour. Through
extensive experiments, we demonstrate that membership and property inference
attacks are effective for this purpose. Our evaluation shows that FRIDA
outperforms state-of-the-art methods, especially in non-IID settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.04754v1">A Comprehensive Study on GDPR-Oriented Analysis of Privacy Policies:
  Taxonomy, Corpus and GDPR Concept Classifiers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-07T05:19:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Peng Tang, Xin Li, Yuxin Chen, Weidong Qiu, Haochen Mei, Allison Holmes, Fenghua Li, Shujun Li</p>
    <p><b>Summary:</b> Machine learning based classifiers that take a privacy policy as the input
and predict relevant concepts are useful in different applications such as
(semi-)automated compliance analysis against requirements of the EU GDPR. In
all past studies, such classifiers produce a concept label per segment (e.g.,
sentence or paragraph) and their performances were evaluated by using a dataset
of labeled segments without considering the privacy policy they belong to.
However, such an approach could overestimate the performance in real-world
settings, where all segments in a new privacy policy are supposed to be unseen.
Additionally, we also observed other research gaps, including the lack of a
more complete GDPR taxonomy and the less consideration of hierarchical
information in privacy policies. To fill such research gaps, we developed a
more complete GDPR taxonomy, created the first corpus of labeled privacy
policies with hierarchical information, and conducted the most comprehensive
performance evaluation of GDPR concept classifiers for privacy policies. Our
work leads to multiple novel findings, including the confirmed
inappropriateness of splitting training and test sets at the segment level, the
benefits of considering hierarchical information, and the limitations of the
"one size fits all" approach, and the significance of testing cross-corpus
generalizability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.04606v1">Privacy's Peril: Unmasking the Unregulated Underground Market of Data
  Brokers and the Suggested Framework</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-06T19:51:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rabia Bajwa, Farah Tasnur Meem</p>
    <p><b>Summary:</b> The internet is a common place for businesses to collect and store as much
client data as possible and computer storage capacity has increased
exponentially due to this trend. Businesses utilize this data to enhance
customer satisfaction, generate revenue, boost sales, and increase profile.
However, the emerging sector of data brokers is plagued with legal challenges.
In part I, we will look at what a data broker is, how it collects information,
the data industry, and some of the difficulties it encounters. In Part II, we
will look at potential options for regulating data brokers. All options are
provided in light of the EU General Data Protection Regulation (GDPR). In Part
III, we shall present our analysis and findings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.04302v1">PANav: Toward Privacy-Aware Robot Navigation via Vision-Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E">
  <p><b>Published on:</b> 2024-10-05T22:54:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bangguo Yu, Hamidreza Kasaei, Ming Cao</p>
    <p><b>Summary:</b> Navigating robots discreetly in human work environments while considering the
possible privacy implications of robotic tasks presents significant challenges.
Such scenarios are increasingly common, for instance, when robots transport
sensitive objects that demand high levels of privacy in spaces crowded with
human activities. While extensive research has been conducted on robotic path
planning and social awareness, current robotic systems still lack the
functionality of privacy-aware navigation in public environments. To address
this, we propose a new framework for mobile robot navigation that leverages
vision-language models to incorporate privacy awareness into adaptive path
planning. Specifically, all potential paths from the starting point to the
destination are generated using the A* algorithm. Concurrently, the
vision-language model is used to infer the optimal path for privacy-awareness,
given the environmental layout and the navigational instruction. This approach
aims to minimize the robot's exposure to human activities and preserve the
privacy of the robot and its surroundings. Experimental results on the S3DIS
dataset demonstrate that our framework significantly enhances mobile robots'
privacy awareness of navigation in human-shared public environments.
Furthermore, we demonstrate the practical applicability of our framework by
successfully navigating a robotic platform through real-world office
environments. The supplementary video and code can be accessed via the
following link: https://sites.google.com/view/privacy-aware-nav.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.03925v1">C3PA: An Open Dataset of Expert-Annotated and Regulation-Aware Privacy
  Policies to Enable Scalable Regulatory Compliance Audits</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2024-10-04T21:04:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maaz Bin Musa, Steven M. Winston, Garrison Allen, Jacob Schiller, Kevin Moore, Sean Quick, Johnathan Melvin, Padmini Srinivasan, Mihailis E. Diamantis, Rishab Nithyanand</p>
    <p><b>Summary:</b> The development of tools and techniques to analyze and extract organizations
data habits from privacy policies are critical for scalable regulatory
compliance audits. Unfortunately, these tools are becoming increasingly limited
in their ability to identify compliance issues and fixes. After all, most were
developed using regulation-agnostic datasets of annotated privacy policies
obtained from a time before the introduction of landmark privacy regulations
such as EUs GDPR and Californias CCPA. In this paper, we describe the first
open regulation-aware dataset of expert-annotated privacy policies, C3PA (CCPA
Privacy Policy Provision Annotations), aimed to address this challenge. C3PA
contains over 48K expert-labeled privacy policy text segments associated with
responses to CCPA-specific disclosure mandates from 411 unique organizations.
We demonstrate that the C3PA dataset is uniquely suited for aiding automated
audits of compliance with CCPA-related disclosure mandates.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.03621v1">A Global Medical Data Security and Privacy Preserving Standards
  Identification Framework for Electronic Healthcare Consumers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-10-04T17:22:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vinaytosh Mishra, Kishu Gupta, Deepika Saxena, Ashutosh Kumar Singh</p>
    <p><b>Summary:</b> Electronic Health Records (EHR) are crucial for the success of digital
healthcare, with a focus on putting consumers at the center of this
transformation. However, the digitalization of healthcare records brings along
security and privacy risks for personal data. The major concern is that
different countries have varying standards for the security and privacy of
medical data. This paper proposed a novel and comprehensive framework to
standardize these rules globally, bringing them together on a common platform.
To support this proposal, the study reviews existing literature to understand
the research interest in this issue. It also examines six key laws and
standards related to security and privacy, identifying twenty concepts. The
proposed framework utilized K-means clustering to categorize these concepts and
identify five key factors. Finally, an Ordinal Priority Approach is applied to
determine the preferred implementation of these factors in the context of EHRs.
The proposed study provides a descriptive then prescriptive framework for the
implementation of privacy and security in the context of electronic health
records. Therefore, the findings of the proposed framework are useful for
professionals and policymakers in improving the security and privacy associated
with EHRs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.03407v1">Camel: Communication-Efficient and Maliciously Secure Federated Learning
  in the Shuffle Model of Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-04T13:13:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuangqing Xu, Yifeng Zheng, Zhongyun Hua</p>
    <p><b>Summary:</b> Federated learning (FL) has rapidly become a compelling paradigm that enables
multiple clients to jointly train a model by sharing only gradient updates for
aggregation, without revealing their local private data. In order to protect
the gradient updates which could also be privacy-sensitive, there has been a
line of work studying local differential privacy (LDP) mechanisms to provide a
formal privacy guarantee. With LDP mechanisms, clients locally perturb their
gradient updates before sharing them out for aggregation. However, such
approaches are known for greatly degrading the model utility, due to heavy
noise addition. To enable a better privacy-utility tradeoff, a recently
emerging trend is to apply the shuffle model of DP in FL, which relies on an
intermediate shuffling operation on the perturbed gradient updates to achieve
privacy amplification. Following this trend, in this paper, we present Camel, a
new communication-efficient and maliciously secure FL framework in the shuffle
model of DP. Camel first departs from existing works by ambitiously supporting
integrity check for the shuffle computation, achieving security against
malicious adversary. Specifically, Camel builds on the trending cryptographic
primitive of secret-shared shuffle, with custom techniques we develop for
optimizing system-wide communication efficiency, and for lightweight integrity
checks to harden the security of server-side computation. In addition, we also
derive a significantly tighter bound on the privacy loss through analyzing the
Renyi differential privacy (RDP) of the overall FL process. Extensive
experiments demonstrate that Camel achieves better privacy-utility trade-offs
than the state-of-the-art work, with promising performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.21986v1">From 5G to 6G: A Survey on Security, Privacy, and Standardization
  Pathways</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-04T03:03:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mengmeng Yang, Youyang Qu, Thilina Ranbaduge, Chandra Thapa, Nazatul Sultan, Ming Ding, Hajime Suzuki, Wei Ni, Sharif Abuadbba, David Smith, Paul Tyler, Josef Pieprzyk, Thierry Rakotoarivelo, Xinlong Guan, Sirine M'rabet</p>
    <p><b>Summary:</b> The vision for 6G aims to enhance network capabilities with faster data
rates, near-zero latency, and higher capacity, supporting more connected
devices and seamless experiences within an intelligent digital ecosystem where
artificial intelligence (AI) plays a crucial role in network management and
data analysis. This advancement seeks to enable immersive mixed-reality
experiences, holographic communications, and smart city infrastructures.
However, the expansion of 6G raises critical security and privacy concerns,
such as unauthorized access and data breaches. This is due to the increased
integration of IoT devices, edge computing, and AI-driven analytics. This paper
provides a comprehensive overview of 6G protocols, focusing on security and
privacy, identifying risks, and presenting mitigation strategies. The survey
examines current risk assessment frameworks and advocates for tailored 6G
solutions. We further discuss industry visions, government projects, and
standardization efforts to balance technological innovation with robust
security and privacy measures.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.03069v1">Interactive GDPR-Compliant Privacy Policy Generation for Software
  Applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2024-10-04T01:22:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pattaraporn Sangaroonsilp, Hoa Khanh Dam, Omar Haggag, John Grundy</p>
    <p><b>Summary:</b> Software applications are designed to assist users in conducting a wide range
of tasks or interactions. They have become prevalent and play an integral part
in people's lives in this digital era. To use those software applications,
users are sometimes requested to provide their personal information. As privacy
has become a significant concern and many data protection regulations exist
worldwide, software applications must provide users with a privacy policy
detailing how their personal information is collected and processed. We propose
an approach that generates a comprehensive and compliant privacy policy with
respect to the General Data Protection Regulation (GDPR) for diverse software
applications. To support this, we first built a library of privacy clauses
based on existing privacy policy analysis. We then developed an interactive
rule-based system that prompts software developers with a series of questions
and uses their answers to generate a customised privacy policy for a given
software application. We evaluated privacy policies generated by our approach
in terms of readability, completeness and coverage and compared them to privacy
policies generated by three existing privacy policy generators and a Generative
AI-based tool. Our evaluation results show that the privacy policy generated by
our approach is the most complete and comprehensive.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.02912v1">Fine-Tuning Language Models with Differential Privacy through Adaptive
  Noise Allocation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-10-03T19:02:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xianzhi Li, Ran Zmigrod, Zhiqiang Ma, Xiaomo Liu, Xiaodan Zhu</p>
    <p><b>Summary:</b> Language models are capable of memorizing detailed patterns and information,
leading to a double-edged effect: they achieve impressive modeling performance
on downstream tasks with the stored knowledge but also raise significant
privacy concerns. Traditional differential privacy based training approaches
offer robust safeguards by employing a uniform noise distribution across all
parameters. However, this overlooks the distinct sensitivities and
contributions of individual parameters in privacy protection and often results
in suboptimal models. To address these limitations, we propose ANADP, a novel
algorithm that adaptively allocates additive noise based on the importance of
model parameters. We demonstrate that ANADP narrows the performance gap between
regular fine-tuning and traditional DP fine-tuning on a series of datasets
while maintaining the required privacy constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.02547v1">Personalized Quantum Federated Learning for Privacy Image Classification</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-10-03T14:53:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jinjing Shi, Tian Chen, Shichao Zhang, Xuelong Li</p>
    <p><b>Summary:</b> Quantum federated learning has brought about the improvement of privacy image
classification, while the lack of personality of the client model may
contribute to the suboptimal of quantum federated learning. A personalized
quantum federated learning algorithm for privacy image classification is
proposed to enhance the personality of the client model in the case of an
imbalanced distribution of images. First, a personalized quantum federated
learning model is constructed, in which a personalized layer is set for the
client model to maintain the personalized parameters. Second, a personalized
quantum federated learning algorithm is introduced to secure the information
exchanged between the client and server.Third, the personalized federated
learning is applied to image classification on the FashionMNIST dataset, and
the experimental results indicate that the personalized quantum federated
learning algorithm can obtain global and local models with excellent
performance, even in situations where local training samples are imbalanced.
The server's accuracy is 100% with 8 clients and a distribution parameter of
100, outperforming the non-personalized model by 7%. The average client
accuracy is 2.9% higher than that of the non-personalized model with 2 clients
and a distribution parameter of 1. Compared to previous quantum federated
learning algorithms, the proposed personalized quantum federated learning
algorithm eliminates the need for additional local training while safeguarding
both model and data privacy.It may facilitate broader adoption and application
of quantum technologies, and pave the way for more secure, scalable, and
efficient quantum distribute machine learning solutions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.02371v1">NTU-NPU System for Voice Privacy 2024 Challenge</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-10-03T10:45:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nikita Kuzmin, Hieu-Thi Luong, Jixun Yao, Lei Xie, Kong Aik Lee, Eng Siong Chng</p>
    <p><b>Summary:</b> In this work, we describe our submissions for the Voice Privacy Challenge
2024. Rather than proposing a novel speech anonymization system, we enhance the
provided baselines to meet all required conditions and improve evaluated
metrics. Specifically, we implement emotion embedding and experiment with WavLM
and ECAPA2 speaker embedders for the B3 baseline. Additionally, we compare
different speaker and prosody anonymization techniques. Furthermore, we
introduce Mean Reversion F0 for B5, which helps to enhance privacy without a
loss in utility. Finally, we explore disentanglement models, namely $\beta$-VAE
and NaturalSpeech3 FACodec.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.02246v1">PFGuard: A Generative Framework with Privacy and Fairness Safeguards</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-10-03T06:37:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Soyeon Kim, Yuji Roh, Geon Heo, Steven Euijong Whang</p>
    <p><b>Summary:</b> Generative models must ensure both privacy and fairness for Trustworthy AI.
While these goals have been pursued separately, recent studies propose to
combine existing privacy and fairness techniques to achieve both goals.
However, naively combining these techniques can be insufficient due to
privacy-fairness conflicts, where a sample in a minority group may be amplified
for fairness, only to be suppressed for privacy. We demonstrate how these
conflicts lead to adverse effects, such as privacy violations and unexpected
fairness-utility tradeoffs. To mitigate these risks, we propose PFGuard, a
generative framework with privacy and fairness safeguards, which simultaneously
addresses privacy, fairness, and utility. By using an ensemble of multiple
teacher models, PFGuard balances privacy-fairness conflicts between fair and
private training stages and achieves high utility based on ensemble learning.
Extensive experiments show that PFGuard successfully generates synthetic data
on high-dimensional data while providing both fairness convergence and strict
DP guarantees - the first of its kind to our knowledge.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.01068v1">Convergent Privacy Loss of Noisy-SGD without Convexity and Smoothness</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-01T20:52:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Eli Chien, Pan Li</p>
    <p><b>Summary:</b> We study the Differential Privacy (DP) guarantee of hidden-state Noisy-SGD
algorithms over a bounded domain. Standard privacy analysis for Noisy-SGD
assumes all internal states are revealed, which leads to a divergent R'enyi DP
bound with respect to the number of iterations. Ye & Shokri (2022) and
Altschuler & Talwar (2022) proved convergent bounds for smooth (strongly)
convex losses, and raise open questions about whether these assumptions can be
relaxed. We provide positive answers by proving convergent R'enyi DP bound for
non-convex non-smooth losses, where we show that requiring losses to have
H\"older continuous gradient is sufficient. We also provide a strictly better
privacy bound compared to state-of-the-art results for smooth strongly convex
losses. Our analysis relies on the improvement of shifted divergence analysis
in multiple aspects, including forward Wasserstein distance tracking,
identifying the optimal shifts allocation, and the H"older reduction lemma. Our
results further elucidate the benefit of hidden-state analysis for DP and its
applicability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.00897v1">The Gradient of Health Data Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> 
  <p><b>Published on:</b> 2024-10-01T17:35:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Baihan Lin</p>
    <p><b>Summary:</b> In the era of digital health and artificial intelligence, the management of
patient data privacy has become increasingly complex, with significant
implications for global health equity and patient trust. This paper introduces
a novel "privacy gradient" approach to health data governance, offering a more
nuanced and adaptive framework than traditional binary privacy models. Our
multidimensional concept considers factors such as data sensitivity,
stakeholder relationships, purpose of use, and temporal aspects, allowing for
context-sensitive privacy protections. Through policy analyses, ethical
considerations, and case studies spanning adolescent health, integrated care,
and genomic research, we demonstrate how this approach can address critical
privacy challenges in diverse healthcare settings worldwide. The privacy
gradient model has the potential to enhance patient engagement, improve care
coordination, and accelerate medical research while safeguarding individual
privacy rights. We provide policy recommendations for implementing this
approach, considering its impact on healthcare systems, research
infrastructures, and global health initiatives. This work aims to inform
policymakers, healthcare leaders, and digital health innovators, contributing
to a more equitable, trustworthy, and effective global health data ecosystem in
the digital age.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.00836v1">Towards Fairness and Privacy: A Novel Data Pre-processing Optimization
  Framework for Non-binary Protected Attributes</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-10-01T16:17:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Manh Khoi Duong, Stefan Conrad</p>
    <p><b>Summary:</b> The reason behind the unfair outcomes of AI is often rooted in biased
datasets. Therefore, this work presents a framework for addressing fairness by
debiasing datasets containing a (non-)binary protected attribute. The framework
proposes a combinatorial optimization problem where heuristics such as genetic
algorithms can be used to solve for the stated fairness objectives. The
framework addresses this by finding a data subset that minimizes a certain
discrimination measure. Depending on a user-defined setting, the framework
enables different use cases, such as data removal, the addition of synthetic
data, or exclusive use of synthetic data. The exclusive use of synthetic data
in particular enhances the framework's ability to preserve privacy while
optimizing for fairness. In a comprehensive evaluation, we demonstrate that
under our framework, genetic algorithms can effectively yield fairer datasets
compared to the original data. In contrast to prior work, the framework
exhibits a high degree of flexibility as it is metric- and task-agnostic, can
be applied to both binary or non-binary protected attributes, and demonstrates
efficient runtime.</p>
  </details>
</div>

