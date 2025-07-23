
<h2>2025-07</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.16788v1">AUTOPSY: A Framework for Tackling Privacy Challenges in the Automotive
  Industry</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-22T17:32:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sebastian Pape, Anis Bkakria, Maurice Heymann, Badreddine Chah, Abdeljalil Abbas-Turki, Sarah Syed-Winkler, Matthias Hiller, Reda Yaich</p>
    <p><b>Summary:</b> With the General Data Protection Regulation (GDPR) in place, all domains have
to ensure compliance with privacy legislation. However, compliance does not
necessarily result in a privacy-friendly system as for example getting users'
consent to process their data does not improve the privacy-friendliness of the
system. Therefore, the goal of the AUTOPSY project was to support the privacy
engineering process in the automotive domain by providing several building
blocks which technically improve the privacy-friendliness of modern, i.e.,
connected and (partially) automated vehicles. This paper presents the results
of the AUTOPSY project: a system model to identify relevant entities and
locations to apply privacy enhancing technologies (PETs); the privacy manager
aiming at more control of the data flow from the vehicle, a PET selection
approach based on GDPR principles, and an architectural framework for
automotive privacy. Furthermore, we built a demonstrator for location-based
services to evaluate the architectural framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.16391v1">Ironman: Accelerating Oblivious Transfer Extension for
  Privacy-Preserving AI with Near-Memory Processing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Hardware Architecture-04E762">
  <p><b>Published on:</b> 2025-07-22T09:35:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chenqi Lin, Kang Yang, Tianshi Xu, Ling Liang, Yufei Wang, Zhaohui Chen, Runsheng Wang, Mingyu Gao, Meng Li</p>
    <p><b>Summary:</b> With the wide application of machine learning (ML), privacy concerns arise
with user data as they may contain sensitive information. Privacy-preserving ML
(PPML) based on cryptographic primitives has emerged as a promising solution in
which an ML model is directly computed on the encrypted data to provide a
formal privacy guarantee. However, PPML frameworks heavily rely on the
oblivious transfer (OT) primitive to compute nonlinear functions. OT mainly
involves the computation of single-point correlated OT (SPCOT) and learning
parity with noise (LPN) operations. As OT is still computed extensively on
general-purpose CPUs, it becomes the latency bottleneck of modern PPML
frameworks.
  In this paper, we propose a novel OT accelerator, dubbed Ironman, to
significantly increase the efficiency of OT and the overall PPML framework. We
observe that SPCOT is computation-bounded, and thus propose a hardware-friendly
SPCOT algorithm with a customized accelerator to improve SPCOT computation
throughput. In contrast, LPN is memory-bandwidth-bounded due to irregular
memory access patterns. Hence, we further leverage the near-memory processing
(NMP) architecture equipped with memory-side cache and index sorting to improve
effective memory bandwidth. With extensive experiments, we demonstrate Ironman
achieves a 39.2-237.4 times improvement in OT throughput across different NMP
configurations compared to the full-thread CPU implementation. For different
PPML frameworks, Ironman demonstrates a 2.1-3.4 times reduction in end-to-end
latency for both CNN and Transformer models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.16372v1">Depth Gives a False Sense of Privacy: LLM Internal States Inversion</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-22T09:15:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tian Dong, Yan Meng, Shaofeng Li, Guoxing Chen, Zhen Liu, Haojin Zhu</p>
    <p><b>Summary:</b> Large Language Models (LLMs) are increasingly integrated into daily routines,
yet they raise significant privacy and safety concerns. Recent research
proposes collaborative inference, which outsources the early-layer inference to
ensure data locality, and introduces model safety auditing based on inner
neuron patterns. Both techniques expose the LLM's Internal States (ISs), which
are traditionally considered irreversible to inputs due to optimization
challenges and the highly abstract representations in deep layers. In this
work, we challenge this assumption by proposing four inversion attacks that
significantly improve the semantic similarity and token matching rate of
inverted inputs. Specifically, we first develop two white-box
optimization-based attacks tailored for low-depth and high-depth ISs. These
attacks avoid local minima convergence, a limitation observed in prior work,
through a two-phase inversion process. Then, we extend our optimization attack
under more practical black-box weight access by leveraging the transferability
between the source and the derived LLMs. Additionally, we introduce a
generation-based attack that treats inversion as a translation task, employing
an inversion model to reconstruct inputs. Extensive evaluation of short and
long prompts from medical consulting and coding assistance datasets and 6 LLMs
validates the effectiveness of our inversion attacks. Notably, a 4,112-token
long medical consulting prompt can be nearly perfectly inverted with 86.88 F1
token matching from the middle layer of Llama-3 model. Finally, we evaluate
four practical defenses that we found cannot perfectly prevent ISs inversion
and draw conclusions for future mitigation design.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.16247v1">PRAC3 (Privacy, Reputation, Accountability, Consent, Credit,
  Compensation): Long Tailed Risks of Voice Actors in AI Data-Economy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-07-22T05:39:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tanusree Sharma, Yihao Zhou, Visar Berisha</p>
    <p><b>Summary:</b> Early large-scale audio datasets, such as LibriSpeech, were built with
hundreds of individual contributors whose voices were instrumental in the
development of speech technologies, including audiobooks and voice assistants.
Yet, a decade later, these same contributions have exposed voice actors to a
range of risks. While existing ethical frameworks emphasize Consent, Credit,
and Compensation (C3), they do not adequately address the emergent risks
involving vocal identities that are increasingly decoupled from context,
authorship, and control. Drawing on qualitative interviews with 20 professional
voice actors, this paper reveals how the synthetic replication of voice without
enforceable constraints exposes individuals to a range of threats. Beyond
reputational harm, such as re-purposing voice data in erotic content, offensive
political messaging, and meme culture, we document concerns about
accountability breakdowns when their voice is leveraged to clone voices that
are deployed in high-stakes scenarios such as financial fraud, misinformation
campaigns, or impersonation scams. In such cases, actors face social and legal
fallout without recourse, while very few of them have a legal representative or
union protection. To make sense of these shifting dynamics, we introduce the
PRAC3 framework, an expansion of C3 that foregrounds Privacy, Reputation,
Accountability, Consent, Credit, and Compensation as interdependent pillars of
data used in the synthetic voice economy. This framework captures how privacy
risks are amplified through non-consensual training, how reputational harm
arises from decontextualized deployment, and how accountability can be
reimagined AI Data ecosystems. We argue that voice, as both a biometric
identifier and creative labor, demands governance models that restore creator
agency, ensure traceability, and establish enforceable boundaries for ethical
reuse.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.16134v1">DP2Guard: A Lightweight and Byzantine-Robust Privacy-Preserving
  Federated Learning Scheme for Industrial IoT</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-07-22T01:06:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Baofu Han, Bing Li, Yining Qi, Raja Jurdak, Kaibin Huang, Chau Yuen</p>
    <p><b>Summary:</b> Privacy-Preserving Federated Learning (PPFL) has emerged as a secure
distributed Machine Learning (ML) paradigm that aggregates locally trained
gradients without exposing raw data. To defend against model poisoning threats,
several robustness-enhanced PPFL schemes have been proposed by integrating
anomaly detection. Nevertheless, they still face two major challenges: (1) the
reliance on heavyweight encryption techniques results in substantial
communication and computation overhead; and (2) single-strategy defense
mechanisms often fail to provide sufficient robustness against adaptive
adversaries. To overcome these challenges, we propose DP2Guard, a lightweight
PPFL framework that enhances both privacy and robustness. DP2Guard leverages a
lightweight gradient masking mechanism to replace costly cryptographic
operations while ensuring the privacy of local gradients. A hybrid defense
strategy is proposed, which extracts gradient features using singular value
decomposition and cosine similarity, and applies a clustering algorithm to
effectively identify malicious gradients. Additionally, DP2Guard adopts a trust
score-based adaptive aggregation scheme that adjusts client weights according
to historical behavior, while blockchain records aggregated results and trust
scores to ensure tamper-proof and auditable training. Extensive experiments
conducted on two public datasets demonstrate that DP2Guard effectively defends
against four advanced poisoning attacks while ensuring privacy with reduced
communication and computation costs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.16124v1">Benchmarking LLM Privacy Recognition for Social Robot Decision Making</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-22T00:36:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dakota Sullivan, Shirley Zhang, Jennica Li, Heather Kirkorian, Bilge Mutlu, Kassem Fawaz</p>
    <p><b>Summary:</b> Social robots are embodied agents that interact with people while following
human communication norms. These robots interact using verbal and non-verbal
cues, and share the physical environments of people. While social robots have
previously utilized rule-based systems or probabilistic models for user
interaction, the rapid evolution of large language models (LLMs) presents new
opportunities to develop LLM-empowered social robots for enhanced human-robot
interaction. To fully realize these capabilities, however, robots need to
collect data such as audio, fine-grained images, video, and locations. As a
result, LLMs often process sensitive personal information, particularly within
home environments. Given the tension between utility and privacy risks,
evaluating how current LLMs manage sensitive data is critical. Specifically, we
aim to explore the extent to which out-of-the-box LLMs are privacy-aware in the
context of household social robots. In this study, we present a set of
privacy-relevant scenarios crafted through the lens of Contextual Integrity
(CI). We first survey users' privacy preferences regarding in-home social robot
behaviors and then examine how their privacy orientation affects their choices
of these behaviors (N = 450). We then provide the same set of scenarios and
questions to state-of-the-art LLMs (N = 10) and find that the agreement between
humans and LLMs is low. To further investigate the capabilities of LLMs as a
potential privacy controller, we implement four additional prompting strategies
and compare their results. Finally, we discuss the implications and potential
of AI privacy awareness in human-robot interaction.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.16034v1">Improved Semantic Segmentation from Ultra-Low-Resolution RGB Images
  Applied to Privacy-Preserving Object-Goal Navigation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-07-21T19:53:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xuying Huang, Sicong Pan, Olga Zatsarynna, Juergen Gall, Maren Bennewitz</p>
    <p><b>Summary:</b> User privacy in mobile robotics has become a critical concern. Existing
methods typically prioritize either the performance of downstream robotic tasks
or privacy protection, with the latter often constraining the effectiveness of
task execution. To jointly address both objectives, we study semantic-based
robot navigation in an ultra-low-resolution setting to preserve visual privacy.
A key challenge in such scenarios is recovering semantic segmentation from
ultra-low-resolution RGB images. In this work, we introduce a novel fully
joint-learning method that integrates an agglomerative feature extractor and a
segmentation-aware discriminator to solve ultra-low-resolution semantic
segmentation, thereby enabling privacy-preserving, semantic object-goal
navigation. Our method outperforms different baselines on ultra-low-resolution
semantic segmentation and our improved segmentation results increase the
success rate of the semantic object-goal navigation in a real-world
privacy-constrained scenario.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.15997v1">"We Need a Standard": Toward an Expert-Informed Privacy Label for
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> 
  <p><b>Published on:</b> 2025-07-21T18:32:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Onyinye Dibia, Mengyi Lu, Prianka Bhattacharjee, Joseph P. Near, Yuanyuan Feng</p>
    <p><b>Summary:</b> The increasing adoption of differential privacy (DP) leads to public-facing
DP deployments by both government agencies and companies. However, real-world
DP deployments often do not fully disclose their privacy guarantees, which vary
greatly between deployments. Failure to disclose certain DP parameters can lead
to misunderstandings about the strength of the privacy guarantee, undermining
the trust in DP. In this work, we seek to inform future standards for
communicating the privacy guarantees of DP deployments. Based on
semi-structured interviews with 12 DP experts, we identify important DP
parameters necessary to comprehensively communicate DP guarantees, and describe
why and how they should be disclosed. Based on expert recommendations, we
design an initial privacy label for DP to comprehensively communicate privacy
guarantees in a standardized format.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.15836v1">Optimizing Canaries for Privacy Auditing with Metagradient Descent</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-21T17:47:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Matteo Boglioni, Terrance Liu, Andrew Ilyas, Zhiwei Steven Wu</p>
    <p><b>Summary:</b> In this work we study black-box privacy auditing, where the goal is to lower
bound the privacy parameter of a differentially private learning algorithm
using only the algorithm's outputs (i.e., final trained model). For DP-SGD (the
most successful method for training differentially private deep learning
models), the canonical approach auditing uses membership inference-an auditor
comes with a small set of special "canary" examples, inserts a random subset of
them into the training set, and then tries to discern which of their canaries
were included in the training set (typically via a membership inference
attack). The auditor's success rate then provides a lower bound on the privacy
parameters of the learning algorithm. Our main contribution is a method for
optimizing the auditor's canary set to improve privacy auditing, leveraging
recent work on metagradient optimization. Our empirical evaluation demonstrates
that by using such optimized canaries, we can improve empirical lower bounds
for differentially private image classification models by over 2x in certain
instances. Furthermore, we demonstrate that our method is transferable and
efficient: canaries optimized for non-private SGD with a small model
architecture remain effective when auditing larger models trained with DP-SGD.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.15460v2">Privacy-Preserving Multimodal News Recommendation through Federated
  Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-07-21T10:14:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mehdi Khalaj, Shahrzad Golestani Najafabadi, Julita Vassileva</p>
    <p><b>Summary:</b> Personalized News Recommendation systems (PNR) have emerged as a solution to
information overload by predicting and suggesting news items tailored to
individual user interests. However, traditional PNR systems face several
challenges, including an overreliance on textual content, common neglect of
short-term user interests, and significant privacy concerns due to centralized
data storage. This paper addresses these issues by introducing a novel
multimodal federated learning-based approach for news recommendation. First, it
integrates both textual and visual features of news items using a multimodal
model, enabling a more comprehensive representation of content. Second, it
employs a time-aware model that balances users' long-term and short-term
interests through multi-head self-attention networks, improving recommendation
accuracy. Finally, to enhance privacy, a federated learning framework is
implemented, enabling collaborative model training without sharing user data.
The framework divides the recommendation model into a large server-maintained
news model and a lightweight user model shared between the server and clients.
The client requests news representations (vectors) and a user model from the
central server, then computes gradients with user local data, and finally sends
their locally computed gradients to the server for aggregation. The central
server aggregates gradients to update the global user model and news model. The
updated news model is further used to infer news representation by the server.
To further safeguard user privacy, a secure aggregation algorithm based on
Shamir's secret sharing is employed. Experiments on a real-world news dataset
demonstrate strong performance compared to existing systems, representing a
significant advancement in privacy-preserving personalized news recommendation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.15124v1">Comprehensive Privacy Risk Assessment in Social Networks Using User
  Attributes Social Graphs and Text Analysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B">
  <p><b>Published on:</b> 2025-07-20T21:18:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Md Jahangir Alam, Ismail Hossain, Sai Puppala, Sajedul Talukder</p>
    <p><b>Summary:</b> The rise of social networking platforms has amplified privacy threats as
users increasingly share sensitive information across profiles, content, and
social connections. We present a Comprehensive Privacy Risk Scoring (CPRS)
framework that quantifies privacy risk by integrating user attributes, social
graph structures, and user-generated content. Our framework computes risk
scores across these dimensions using sensitivity, visibility, structural
similarity, and entity-level analysis, then aggregates them into a unified risk
score. We validate CPRS on two real-world datasets: the SNAP Facebook Ego
Network (4,039 users) and the Koo microblogging dataset (1M posts, 1M
comments). The average CPRS is 0.478 with equal weighting, rising to 0.501 in
graph-sensitive scenarios. Component-wise, graph-based risks (mean 0.52)
surpass content (0.48) and profile attributes (0.45). High-risk attributes
include email, date of birth, and mobile number. Our user study with 100
participants shows 85% rated the dashboard as clear and actionable, confirming
CPRS's practical utility. This work enables personalized privacy risk insights
and contributes a holistic, scalable methodology for privacy management. Future
directions include incorporating temporal dynamics and multimodal content for
broader applicability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.14985v1">Metaverse Security and Privacy Research: A Systematic Review</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-07-20T14:42:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Argianto Rahartomo, Leonel Merino, Mohammad Ghafari</p>
    <p><b>Summary:</b> The rapid growth of metaverse technologies, including virtual worlds,
augmented reality, and lifelogging, has accelerated their adoption across
diverse domains. This rise exposes users to significant new security and
privacy challenges due to sociotechnical complexity, pervasive connectivity,
and extensive user data collection in immersive environments. We present a
systematic review of the literature published between 2013 and 2024, offering a
comprehensive analysis of how the research community has addressed
metaverse-related security and privacy issues over the past decade. We organize
the studies by method, examined the security and privacy properties, immersive
components, and evaluation strategies. Our investigation reveals a sharp
increase in research activity in the last five years, a strong focus on
practical and user-centered approaches, and a predominant use of benchmarking,
human experimentation, and qualitative methods. Authentication and
unobservability are the most frequently studied properties. However, critical
gaps remain in areas such as policy compliance, accessibility,
interoperability, and back-end infrastructure security. We emphasize the
intertwined technical complexity and human factors of the metaverse and call
for integrated, interdisciplinary approaches to securing inclusive and
trustworthy immersive environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.14853v1">A Privacy-Centric Approach: Scalable and Secure Federated Learning
  Enabled by Hybrid Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-07-20T07:46:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Khoa Nguyen, Tanveer Khan, Antonis Michalas</p>
    <p><b>Summary:</b> Federated Learning (FL) enables collaborative model training without sharing
raw data, making it a promising approach for privacy-sensitive domains. Despite
its potential, FL faces significant challenges, particularly in terms of
communication overhead and data privacy. Privacy-preserving Techniques (PPTs)
such as Homomorphic Encryption (HE) have been used to mitigate these concerns.
However, these techniques introduce substantial computational and communication
costs, limiting their practical deployment. In this work, we explore how Hybrid
Homomorphic Encryption (HHE), a cryptographic protocol that combines symmetric
encryption with HE, can be effectively integrated with FL to address both
communication and privacy challenges, paving the way for scalable and secure
decentralized learning system.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.14713v1">Privacy-Preserving Drone Navigation Through Homomorphic Encryption for
  Collision Avoidance</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2025-07-19T18:16:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Allan Luedeman, Nicholas Baum, Andrew Quijano, Kemal Akkaya</p>
    <p><b>Summary:</b> As drones increasingly deliver packages in neighborhoods, concerns about
collisions arise. One solution is to share flight paths within a specific zip
code, but this compromises business privacy by revealing delivery routes. For
example, it could disclose which stores send packages to certain addresses. To
avoid exposing path information, we propose using homomorphic encryption-based
comparison to compute path intersections. This allows drones to identify
potential collisions without revealing path and destination details, allowing
them to adjust altitude to avoid crashes. We implemented and tested our
approach on resource-limited virtual machines to mimic the computational power
of drones. Our results demonstrate that our method is significantly faster and
requires less network communication compared to a garbled circuit-based
approach. We also provide a security analysis of the approach against potential
attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.14629v1">VMask: Tunable Label Privacy Protection for Vertical Federated Learning
  via Layer Masking</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-19T13:51:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Juntao Tan, Lan Zhang, Zhonghao Hu, Kai Yang, Peng Ran, Bo Li</p>
    <p><b>Summary:</b> Though vertical federated learning (VFL) is generally considered to be
privacy-preserving, recent studies have shown that VFL system is vulnerable to
label inference attacks originating from various attack surfaces. Among these
attacks, the model completion (MC) attack is currently the most powerful one.
Existing defense methods against it either sacrifice model accuracy or incur
impractical computational overhead. In this paper, we propose VMask, a novel
label privacy protection framework designed to defend against MC attack from
the perspective of layer masking. Our key insight is to disrupt the strong
correlation between input data and intermediate outputs by applying the secret
sharing (SS) technique to mask layer parameters in the attacker's model. We
devise a strategy for selecting critical layers to mask, reducing the overhead
that would arise from naively applying SS to the entire model. Moreover, VMask
is the first framework to offer a tunable privacy budget to defenders, allowing
for flexible control over the levels of label privacy according to actual
requirements. We built a VFL system, implemented VMask on it, and extensively
evaluated it using five model architectures and 13 datasets with different
modalities, comparing it to 12 other defense methods. The results demonstrate
that VMask achieves the best privacy-utility trade-off, successfully thwarting
the MC attack (reducing the label inference accuracy to a random guessing
level) while preserving model performance (e.g., in Transformer-based model,
the averaged drop of VFL model accuracy is only 0.09%). VMask's runtime is up
to 60,846 times faster than cryptography-based methods, and it only marginally
exceeds that of standard VFL by 1.8 times in a large Transformer-based model,
which is generally acceptable.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.14519v1">Towards Efficient Privacy-Preserving Machine Learning: A Systematic
  Review from Protocol, Model, and System Perspectives</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-19T07:45:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenxuan Zeng, Tianshi Xu, Yi Chen, Yifan Zhou, Mingzhe Zhang, Jin Tan, Cheng Hong, Meng Li</p>
    <p><b>Summary:</b> Privacy-preserving machine learning (PPML) based on cryptographic protocols
has emerged as a promising paradigm to protect user data privacy in cloud-based
machine learning services. While it achieves formal privacy protection, PPML
often incurs significant efficiency and scalability costs due to orders of
magnitude overhead compared to the plaintext counterpart. Therefore, there has
been a considerable focus on mitigating the efficiency gap for PPML. In this
survey, we provide a comprehensive and systematic review of recent PPML studies
with a focus on cross-level optimizations. Specifically, we categorize existing
papers into protocol level, model level, and system level, and review progress
at each level. We also provide qualitative and quantitative comparisons of
existing works with technical insights, based on which we discuss future
research directions and highlight the necessity of integrating optimizations
across protocol, model, and system levels. We hope this survey can provide an
overarching understanding of existing approaches and potentially inspire future
breakthroughs in the PPML field. As the field is evolving fast, we also provide
a public GitHub repository to continuously track the developments, which is
available at https://github.com/PKU-SEC-Lab/Awesome-PPML-Papers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.13981v1">Evaluation of Human Visual Privacy Protection: A Three-Dimensional
  Framework and Benchmark Dataset</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-07-18T14:43:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sara Abdulaziz, Giacomo D'Amicantonio, Egor Bondarev</p>
    <p><b>Summary:</b> Recent advances in AI-powered surveillance have intensified concerns over the
collection and processing of sensitive personal data. In response, research has
increasingly focused on privacy-by-design solutions, raising the need for
objective techniques to evaluate privacy protection. This paper presents a
comprehensive framework for evaluating visual privacy-protection methods across
three dimensions: privacy, utility, and practicality. In addition, it
introduces HR-VISPR, a publicly available human-centric dataset with biometric,
soft-biometric, and non-biometric labels to train an interpretable privacy
metric. We evaluate 11 privacy protection methods, ranging from conventional
techniques to advanced deep-learning methods, through the proposed framework.
The framework differentiates privacy levels in alignment with human visual
perception, while highlighting trade-offs between privacy, utility, and
practicality. This study, along with the HR-VISPR dataset, serves as an
insightful tool and offers a structured evaluation framework applicable across
diverse contexts.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.13926v1">Developers Insight On Manifest v3 Privacy and Security Webextensions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-07-18T14:00:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Libor Polčák, Giorgio Maone, Michael McMahon, Martin Bednář</p>
    <p><b>Summary:</b> Webextensions can improve web browser privacy, security, and user experience.
The APIs offered by the browser to webextensions affect possible functionality.
Currently, Chrome transitions to a modified set of APIs called Manifest v3.
This paper studies the challenges and opportunities of Manifest v3 with an
in-depth structured qualitative research. Even though some projects observed
positive effects, a majority expresses concerns over limited benefits to users,
removal of crucial APIs, or the need to find workarounds. Our findings indicate
that the transition affects different types of webextensions differently; some
can migrate without losing functionality, while other projects remove
functionality or decline to update. The respondents identified several critical
missing APIs, including reliable APIs to inject content scripts, APIs for
storing confidential content, and others.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.13639v1">Differential Privacy in Kernelized Contextual Bandits via Random
  Projections</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-07-18T03:54:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nikola Pavlovic, Sudeep Salgia, Qing Zhao</p>
    <p><b>Summary:</b> We consider the problem of contextual kernel bandits with stochastic
contexts, where the underlying reward function belongs to a known Reproducing
Kernel Hilbert Space. We study this problem under an additional constraint of
Differential Privacy, where the agent needs to ensure that the sequence of
query points is differentially private with respect to both the sequence of
contexts and rewards. We propose a novel algorithm that achieves the
state-of-the-art cumulative regret of
$\widetilde{\mathcal{O}}(\sqrt{\gamma_TT}+\frac{\gamma_T}{\varepsilon_{\mathrm{DP}}})$
and
$\widetilde{\mathcal{O}}(\sqrt{\gamma_TT}+\frac{\gamma_T\sqrt{T}}{\varepsilon_{\mathrm{DP}}})$
over a time horizon of $T$ in the joint and local models of differential
privacy, respectively, where $\gamma_T$ is the effective dimension of the
kernel and $\varepsilon_{\mathrm{DP}} > 0$ is the privacy parameter. The key
ingredient of the proposed algorithm is a novel private kernel-ridge regression
estimator which is based on a combination of private covariance estimation and
private random projections. It offers a significantly reduced sensitivity
compared to its classical counterpart while maintaining a high prediction
accuracy, allowing our algorithm to achieve the state-of-the-art performance
guarantees.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.13286v1">Privacy-Preserving Fusion for Multi-Sensor Systems Under Multiple Packet
  Dropouts</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2025-07-17T16:50:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jie Huang, Jason J. R. Liu</p>
    <p><b>Summary:</b> Wireless sensor networks (WSNs) are critical components in modern
cyber-physical systems, enabling efficient data collection and fusion through
spatially distributed sensors. However, the inherent risks of eavesdropping and
packet dropouts in such networks pose significant challenges to secure state
estimation. In this paper, we address the privacy-preserving fusion estimation
(PPFE) problem for multi-sensor systems under multiple packet dropouts and
eavesdropping attacks. To mitigate these issues, we propose a distributed
encoding-based privacy-preserving mechanism (PPM) within a control-theoretic
framework, ensuring data privacy during transmission while maintaining the
performance of legitimate state estimation. A centralized fusion filter is
developed, accounting for the coupling effects of packet dropouts and the
encoding-based PPM. Boundedness conditions for the legitimate user's estimation
error covariance are derived via a modified algebraic Riccati equation.
Additionally, by demonstrating the divergence of the eavesdropper's mean
estimation error, the proposed PPFE algorithm's data confidentiality is
rigorously analyzed. Simulation results for an Internet-based three-tank system
validate the effectiveness of the proposed approach, highlighting its potential
to enhance privacy without compromising estimation accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.12932v1">Enkidu: Universal Frequential Perturbation for Real-Time Audio Privacy
  Protection against Voice Deepfakes</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Multimedia-5BC0EB">
  <p><b>Published on:</b> 2025-07-17T09:12:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhou Feng, Jiahao Chen, Chunyi Zhou, Yuwen Pu, Qingming Li, Tianyu Du, Shouling Ji</p>
    <p><b>Summary:</b> The rapid advancement of voice deepfake technologies has raised serious
concerns about user audio privacy, as attackers increasingly exploit publicly
available voice data to generate convincing fake audio for malicious purposes
such as identity theft, financial fraud, and misinformation campaigns. While
existing defense methods offer partial protection, they face critical
limitations, including weak adaptability to unseen user data, poor scalability
to long audio, rigid reliance on white-box knowledge, and high computational
and temporal costs during the encryption process. To address these challenges
and defend against personalized voice deepfake threats, we propose Enkidu, a
novel user-oriented privacy-preserving framework that leverages universal
frequential perturbations generated through black-box knowledge and few-shot
training on a small amount of user data. These highly malleable
frequency-domain noise patches enable real-time, lightweight protection with
strong generalization across variable-length audio and robust resistance to
voice deepfake attacks, all while preserving perceptual quality and speech
intelligibility. Notably, Enkidu achieves over 50 to 200 times processing
memory efficiency (as low as 0.004 gigabytes) and 3 to 7000 times runtime
efficiency (real-time coefficient as low as 0.004) compared to six
state-of-the-art countermeasures. Extensive experiments across six mainstream
text-to-speech models and five cutting-edge automated speaker verification
models demonstrate the effectiveness, transferability, and practicality of
Enkidu in defending against both vanilla and adaptive voice deepfake attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.12730v1">A Privacy-Preserving Semantic-Segmentation Method Using
  Domain-Adaptation Technique</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-17T02:14:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Homare Sueyoshi, Kiyoshi Nishikawa, Hitoshi Kiya</p>
    <p><b>Summary:</b> We propose a privacy-preserving semantic-segmentation method for applying
perceptual encryption to images used for model training in addition to test
images. This method also provides almost the same accuracy as models without
any encryption. The above performance is achieved using a domain-adaptation
technique on the embedding structure of the Vision Transformer (ViT). The
effectiveness of the proposed method was experimentally confirmed in terms of
the accuracy of semantic segmentation when using a powerful
semantic-segmentation model with ViT called Segmentation Transformer.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.12652v1">Federated Learning in Open- and Closed-Loop EMG Decoding: A Privacy and
  Performance Perspective</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-07-16T21:59:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kai Malcolm, César Uribe, Momona Yamagami</p>
    <p><b>Summary:</b> Invasive and non-invasive neural interfaces hold promise as high-bandwidth
input devices for next-generation technologies. However, neural signals
inherently encode sensitive information about an individual's identity and
health, making data sharing for decoder training a critical privacy challenge.
Federated learning (FL), a distributed, privacy-preserving learning framework,
presents a promising solution, but it remains unexplored in closed-loop
adaptive neural interfaces. Here, we introduce FL-based neural decoding and
systematically evaluate its performance and privacy using high-dimensional
electromyography signals in both open- and closed-loop scenarios. In open-loop
simulations, FL significantly outperformed local learning baselines,
demonstrating its potential for high-performance, privacy-conscious neural
decoding. In contrast, closed-loop user studies required adapting FL methods to
accommodate single-user, real-time interactions, a scenario not supported by
standard FL. This modification resulted in local learning decoders surpassing
the adapted FL approach in closed-loop performance, yet local learning still
carried higher privacy risks. Our findings highlight a critical
performance-privacy tradeoff in real-time adaptive applications and indicate
the need for FL methods specifically designed for co-adaptive, single-user
applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.12098v1">A Privacy-Preserving Framework for Advertising Personalization
  Incorporating Federated Learning and Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-07-16T10:07:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiang Li, Yifan Lin, Yuanzhe Zhang</p>
    <p><b>Summary:</b> To mitigate privacy leakage and performance issues in personalized
advertising, this paper proposes a framework that integrates federated learning
and differential privacy. The system combines distributed feature extraction,
dynamic privacy budget allocation, and robust model aggregation to balance
model accuracy, communication overhead, and privacy protection. Multi-party
secure computing and anomaly detection mechanisms further enhance system
resilience against malicious attacks. Experimental results demonstrate that the
framework achieves dual optimization of recommendation accuracy and system
efficiency while ensuring privacy, providing both a practical solution and a
theoretical foundation for applying privacy protection technologies in
advertisement recommendation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.11943v1">Effective Fine-Tuning of Vision Transformers with Low-Rank Adaptation
  for Privacy-Preserving Image Classification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-07-16T06:18:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haiwei Lin, Shoko Imaizumi, Hitoshi Kiya</p>
    <p><b>Summary:</b> We propose a low-rank adaptation method for training privacy-preserving
vision transformer (ViT) models that efficiently freezes pre-trained ViT model
weights. In the proposed method, trainable rank decomposition matrices are
injected into each layer of the ViT architecture, and moreover, the patch
embedding layer is not frozen, unlike in the case of the conventional low-rank
adaptation methods. The proposed method allows us not only to reduce the number
of trainable parameters but to also maintain almost the same accuracy as that
of full-time tuning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.11908v1">Unveiling Usability Challenges in Web Privacy Controls</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-16T04:47:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rahat Masood, Sunday Oyinlola Ogundoyin, Muhammad Ikram, Alex Ye</p>
    <p><b>Summary:</b> With the increasing concerns around privacy and the enforcement of data
privacy laws, many websites now provide users with privacy controls. However,
locating these controls can be challenging, as they are frequently hidden
within multiple settings and layers. Moreover, the lack of standardization
means these controls can vary widely across services. The technical or
confusing terminology used to describe these controls further complicates
users' ability to understand and use them effectively. This paper presents a
large-scale empirical analysis investigating usability challenges of web
privacy controls across 18,628 websites. While aiming for a multi-scenario
view, our automated data collection faced significant hurdles, particularly in
simulating sign-up and authenticated user visits, leading to more focused
insights on guest visit scenarios and challenges in automated capture of
dynamic user interactions. Our heuristic evaluation of three different user
visit scenarios identifies significant website usability issues. Our results
show that privacy policies are most common across all visit scenarios, with
nudges and notices being prevalent in sign-up situations. We recommend
designing privacy controls that: enhance awareness through pop-up nudges and
notices; offer a table of contents as navigational aids and customized settings
links in policies for more informed choice; and ensure accessibility via direct
links to privacy settings from nudges.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.14214v1">Let's Measure the Elephant in the Room: Facilitating Personalized
  Automated Analysis of Privacy Policies at Scale</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-07-15T20:19:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rui Zhao, Vladyslav Melnychuk, Jun Zhao, Jesse Wright, Nigel Shadbolt</p>
    <p><b>Summary:</b> In modern times, people have numerous online accounts, but they rarely read
the Terms of Service or Privacy Policy of those sites despite claiming
otherwise. This paper introduces PoliAnalyzer, a neuro-symbolic system that
assists users with personalized privacy policy analysis. PoliAnalyzer uses
Natural Language Processing (NLP) to extract formal representations of data
usage practices from policy texts. In favor of deterministic, logical inference
is applied to compare user preferences with the formal privacy policy
representation and produce a compliance report. To achieve this, we extend an
existing formal Data Terms of Use policy language to model privacy policies as
app policies and user preferences as data policies. In our evaluation using our
enriched PolicyIE dataset curated by legal experts, PoliAnalyzer demonstrated
high accuracy in identifying relevant data usage practices, achieving F1-score
of 90-100% across most tasks. Additionally, we demonstrate how PoliAnalyzer can
model diverse user data-sharing preferences, derived from prior research as 23
user profiles, and perform compliance analysis against the top 100 most-visited
websites. This analysis revealed that, on average, 95.2% of a privacy policy's
segments do not conflict with the analyzed user preferences, enabling users to
concentrate on understanding the 4.8% (636 / 13205) that violates preferences,
significantly reducing cognitive burden. Further, we identified common
practices in privacy policies that violate user expectations - such as the
sharing of location data with 3rd parties. This paper demonstrates that
PoliAnalyzer can support automated personalized privacy policy analysis at
scale using off-the-shelf NLP tools. This sheds light on a pathway to help
individuals regain control over their data and encourage societal discussions
on platform data practices to promote a fairer power dynamic.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.11649v2">ZKP-FedEval: Verifiable and Privacy-Preserving Federated Evaluation
  using Zero-Knowledge Proofs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2025-07-15T18:34:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Daniel Commey, Benjamin Appiah, Griffith S. Klogo, Garth V. Crosby</p>
    <p><b>Summary:</b> Federated Learning (FL) enables collaborative model training on decentralized
data without exposing raw data. However, the evaluation phase in FL may leak
sensitive information through shared performance metrics. In this paper, we
propose a novel protocol that incorporates Zero-Knowledge Proofs (ZKPs) to
enable privacy-preserving and verifiable evaluation for FL. Instead of
revealing raw loss values, clients generate a succinct proof asserting that
their local loss is below a predefined threshold. Our approach is implemented
without reliance on external APIs, using self-contained modules for federated
learning simulation, ZKP circuit design, and experimental evaluation on both
the MNIST and Human Activity Recognition (HAR) datasets. We focus on a
threshold-based proof for a simple Convolutional Neural Network (CNN) model
(for MNIST) and a multi-layer perceptron (MLP) model (for HAR), and evaluate
the approach in terms of computational overhead, communication cost, and
verifiability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.11324v2">A Review of Privacy Metrics for Privacy-Preserving Synthetic Data
  Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2025-07-15T13:56:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Frederik Marinus Trudslev, Matteo Lissandrini, Juan Manuel Rodriguez, Martin Bøgsted, Daniele Dell'Aglio</p>
    <p><b>Summary:</b> Privacy Preserving Synthetic Data Generation (PP-SDG) has emerged to produce
synthetic datasets from personal data while maintaining privacy and utility.
Differential privacy (DP) is the property of a PP-SDG mechanism that
establishes how protected individuals are when sharing their sensitive data. It
is however difficult to interpret the privacy budget ($\varepsilon$) expressed
by DP. To make the actual risk associated with the privacy budget more
transparent, multiple privacy metrics (PMs) have been proposed to assess the
privacy risk of the data. These PMs are utilized in separate studies to assess
newly introduced PP-SDG mechanisms. Consequently, these PMs embody the same
assumptions as the PP-SDG mechanism they were made to assess. Therefore, a
thorough definition of how these are calculated is necessary. In this work, we
present the assumptions and mathematical formulations of 17 distinct privacy
metrics.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.11187v1">Striking the Perfect Balance: Preserving Privacy While Boosting Utility
  in Collaborative Medical Prediction Platforms</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-07-15T10:41:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shao-Bo Lin, Xiaotong Liu, Yao Wang</p>
    <p><b>Summary:</b> Online collaborative medical prediction platforms offer convenience and
real-time feedback by leveraging massive electronic health records. However,
growing concerns about privacy and low prediction quality can deter patient
participation and doctor cooperation. In this paper, we first clarify the
privacy attacks, namely attribute attacks targeting patients and model
extraction attacks targeting doctors, and specify the corresponding privacy
principles. We then propose a privacy-preserving mechanism and integrate it
into a novel one-shot distributed learning framework, aiming to simultaneously
meet both privacy requirements and prediction performance objectives. Within
the framework of statistical learning theory, we theoretically demonstrate that
the proposed distributed learning framework can achieve the optimal prediction
performance under specific privacy requirements. We further validate the
developed privacy-preserving collaborative medical prediction platform through
both toy simulations and real-world data experiments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.10946v1">Solving Linear Programs with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2025-07-15T03:22:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alina Ene, Huy Le Nguyen, Ta Duy Nguyen, Adrian Vladu</p>
    <p><b>Summary:</b> We study the problem of solving linear programs of the form $Ax\le b$,
$x\ge0$ with differential privacy. For homogeneous LPs $Ax\ge0$, we give an
efficient $(\epsilon,\delta)$-differentially private algorithm which with
probability at least $1-\beta$ finds in polynomial time a solution that
satisfies all but
$O(\frac{d^{2}}{\epsilon}\log^{2}\frac{d}{\delta\beta}\sqrt{\log\frac{1}{\rho_{0}}})$
constraints, for problems with margin $\rho_{0}>0$. This improves the bound of
$O(\frac{d^{5}}{\epsilon}\log^{1.5}\frac{1}{\rho_{0}}\mathrm{poly}\log(d,\frac{1}{\delta},\frac{1}{\beta}))$
by [Kaplan-Mansour-Moran-Stemmer-Tur, STOC '25]. For general LPs $Ax\le b$,
$x\ge0$ with potentially zero margin, we give an efficient
$(\epsilon,\delta)$-differentially private algorithm that w.h.p drops
$O(\frac{d^{4}}{\epsilon}\log^{2.5}\frac{d}{\delta}\sqrt{\log dU})$
constraints, where $U$ is an upper bound for the entries of $A$ and $b$ in
absolute value. This improves the result by Kaplan et al. by at least a factor
of $d^{5}$. Our techniques build upon privatizing a rescaling perceptron
algorithm by [Hoberg-Rothvoss, IPCO '17] and a more refined iterative procedure
for identifying equality constraints by Kaplan et al.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.10786v2">"Is it always watching? Is it always listening?" Exploring Contextual
  Privacy and Security Concerns Toward Domestic Social Robots</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-07-14T20:27:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Henry Bell, Jabari Kwesi, Hiba Laabadli, Pardis Emami-Naeini</p>
    <p><b>Summary:</b> Equipped with artificial intelligence (AI) and advanced sensing capabilities,
social robots are gaining interest among consumers in the United States. These
robots seem like a natural evolution of traditional smart home devices.
However, their extensive data collection capabilities, anthropomorphic
features, and capacity to interact with their environment make social robots a
more significant security and privacy threat. Increased risks include data
linkage, unauthorized data sharing, and the physical safety of users and their
homes. It is critical to investigate U.S. users' security and privacy needs and
concerns to guide the design of social robots while these devices are still in
the early stages of commercialization in the U.S. market. Through 19
semi-structured interviews, we identified significant security and privacy
concerns, highlighting the need for transparency, usability, and robust privacy
controls to support adoption. For educational applications, participants
worried most about misinformation, and in medical use cases, they worried about
the reliability of these devices. Participants were also concerned with the
data inference that social robots could enable. We found that participants
expect tangible privacy controls, indicators of data collection, and
context-appropriate functionality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.10695v1">Exploring User Security and Privacy Attitudes and Concerns Toward the
  Use of General-Purpose LLM Chatbots for Mental Health</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-07-14T18:10:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jabari Kwesi, Jiaxun Cao, Riya Manchanda, Pardis Emami-Naeini</p>
    <p><b>Summary:</b> Individuals are increasingly relying on large language model (LLM)-enabled
conversational agents for emotional support. While prior research has examined
privacy and security issues in chatbots specifically designed for mental health
purposes, these chatbots are overwhelmingly "rule-based" offerings that do not
leverage generative AI. Little empirical research currently measures users'
privacy and security concerns, attitudes, and expectations when using
general-purpose LLM-enabled chatbots to manage and improve mental health.
Through 21 semi-structured interviews with U.S. participants, we identified
critical misconceptions and a general lack of risk awareness. Participants
conflated the human-like empathy exhibited by LLMs with human-like
accountability and mistakenly believed that their interactions with these
chatbots were safeguarded by the same regulations (e.g., HIPAA) as disclosures
with a licensed therapist. We introduce the concept of "intangible
vulnerability," where emotional or psychological disclosures are undervalued
compared to more tangible forms of information (e.g., financial or
location-based data). To address this, we propose recommendations to safeguard
user mental health disclosures with general-purpose LLM-enabled chatbots more
effectively.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.10489v1">SynthGuard: Redefining Synthetic Data Generation with a Scalable and
  Privacy-Preserving Workflow Framework</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-14T17:11:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Eduardo Brito, Mahmoud Shoush, Kristian Tamm, Paula Etti, Liina Kamm</p>
    <p><b>Summary:</b> The growing reliance on data-driven applications in sectors such as
healthcare, finance, and law enforcement underscores the need for secure,
privacy-preserving, and scalable mechanisms for data generation and sharing.
Synthetic data generation (SDG) has emerged as a promising approach but often
relies on centralized or external processing, raising concerns about data
sovereignty, domain ownership, and compliance with evolving regulatory
standards. To overcome these issues, we introduce SynthGuard, a framework
designed to ensure computational governance by enabling data owners to maintain
control over SDG workflows. SynthGuard supports modular and privacy-preserving
workflows, ensuring secure, auditable, and reproducible execution across
diverse environments. In this paper, we demonstrate how SynthGuard addresses
the complexities at the intersection of domain-specific needs and scalable SDG
by aligning with requirements for data sovereignty and regulatory compliance.
Developed iteratively with domain expert input, SynthGuard has been validated
through real-world use cases, demonstrating its ability to balance security,
privacy, and scalability while ensuring compliance. The evaluation confirms its
effectiveness in implementing and executing SDG workflows and integrating
privacy and utility assessments across various computational environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.10474v1">Privacy-Preserving Multi-Stage Fall Detection Framework with
  Semi-supervised Federated Learning and Robotic Vision Confirmation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E">
  <p><b>Published on:</b> 2025-07-14T16:55:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Seyed Alireza Rahimi Azghadi, Truong-Thanh-Hung Nguyen, Helene Fournier, Monica Wachowicz, Rene Richard, Francis Palma, Hung Cao</p>
    <p><b>Summary:</b> The aging population is growing rapidly, and so is the danger of falls in
older adults. A major cause of injury is falling, and detection in time can
greatly save medical expenses and recovery time. However, to provide timely
intervention and avoid unnecessary alarms, detection systems must be effective
and reliable while addressing privacy concerns regarding the user. In this
work, we propose a framework for detecting falls using several complementary
systems: a semi-supervised federated learning-based fall detection system
(SF2D), an indoor localization and navigation system, and a vision-based human
fall recognition system. A wearable device and an edge device identify a fall
scenario in the first system. On top of that, the second system uses an indoor
localization technique first to localize the fall location and then navigate a
robot to inspect the scenario. A vision-based detection system running on an
edge device with a mounted camera on a robot is used to recognize fallen
people. Each of the systems of this proposed framework achieves different
accuracy rates. Specifically, the SF2D has a 0.81% failure rate equivalent to
99.19% accuracy, while the vision-based fallen people detection achieves 96.3%
accuracy. However, when we combine the accuracy of these two systems with the
accuracy of the navigation system (95% success rate), our proposed framework
creates a highly reliable performance for fall detection, with an overall
accuracy of 99.99%. Not only is the proposed framework safe for older adults,
but it is also a privacy-preserving solution for detecting falls.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.10640v1">SENSOR: An ML-Enhanced Online Annotation Tool to Uncover Privacy
  Concerns from User Reviews in Social-Media Applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B"> 
  <p><b>Published on:</b> 2025-07-14T14:58:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Labiba Farah, Mohammad Ridwan Kabir, Shohel Ahmed, MD Mohaymen Ul Anam, Md. Sakibul Islam</p>
    <p><b>Summary:</b> The widespread use of social media applications has raised significant
privacy concerns, often highlighted in user reviews. These reviews also provide
developers with valuable insights into improving apps by addressing issues and
introducing better features. However, the sheer volume and nuanced nature of
reviews make manual identification and prioritization of privacy-related
concerns challenging for developers. Previous studies have developed software
utilities to automatically classify user reviews as privacy-relevant,
privacy-irrelevant, bug reports, feature requests, etc., using machine
learning. Notably, there is a lack of focus on classifying reviews specifically
as privacy-related feature requests, privacy-related bug reports, or
privacy-irrelevant. This paper introduces SENtinel SORt (SENSOR), an automated
online annotation tool designed to help developers annotate and classify user
reviews into these categories. For automating the annotation of such reviews,
this paper introduces the annotation model, GRACE (GRU-based Attention with
CBOW Embedding), using Gated Recurrent Units (GRU) with Continuous Bag of Words
(CBOW) and Attention mechanism. Approximately 16000 user reviews from seven
popular social media apps on Google Play Store, including Instagram, Facebook,
WhatsApp, Snapchat, X (formerly Twitter), Facebook Lite, and Line were
analyzed. Two annotators manually labelled the reviews, achieving a Cohen's
Kappa value of 0.87, ensuring a labeled dataset with high inter-rater agreement
for training machine learning models. Among the models tested, GRACE
demonstrated the best performance (macro F1-score: 0.9434, macro ROC-AUC:
0.9934, and accuracy: 95.10%) despite class imbalance. SENSOR demonstrates
significant potential to assist developers with extracting and addressing
privacy-related feature requests or bug reports from user reviews, enhancing
user privacy and trust.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.10627v1">Crypto-Assisted Graph Degree Sequence Release under Local Differential
  Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2025-07-14T07:04:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaojian Zhang, Junqing Wang, Kerui Chen, Peiyuan Zhao, Huiyuan Bai</p>
    <p><b>Summary:</b> Given a graph $G$ defined in a domain $\mathcal{G}$, we investigate locally
differentially private mechanisms to release a degree sequence on $\mathcal{G}$
that accurately approximates the actual degree distribution. Existing solutions
for this problem mostly use graph projection techniques based on edge deletion
process, using a threshold parameter $\theta$ to bound node degrees. However,
this approach presents a fundamental trade-off in threshold parameter
selection. While large $\theta$ values introduce substantial noise in the
released degree sequence, small $\theta$ values result in more edges removed
than necessary. Furthermore, $\theta$ selection leads to an excessive
communication cost. To remedy existing solutions' deficiencies, we present
CADR-LDP, an efficient framework incorporating encryption techniques and
differentially private mechanisms to release the degree sequence. In CADR-LDP,
we first use the crypto-assisted Optimal-$\theta$-Selection method to select
the optimal parameter with a low communication cost. Then, we use the LPEA-LOW
method to add some edges for each node with the edge addition process in local
projection. LPEA-LOW prioritizes the projection with low-degree nodes, which
can retain more edges for such nodes and reduce the projection error.
Theoretical analysis shows that CADR-LDP satisfies $\epsilon$-node local
differential privacy. The experimental results on eight graph datasets show
that our solution outperforms existing methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.09699v1">Interpreting Differential Privacy in Terms of Disclosure Risk</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-13T16:20:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zeki Kazan, Sagar Sharma, Wanrong Zhang, Bo Jiang, Qiang Yan</p>
    <p><b>Summary:</b> As the use of differential privacy (DP) becomes widespread, the development
of effective tools for reasoning about the privacy guarantee becomes
increasingly critical. In pursuit of this goal, we demonstrate novel
relationships between DP and measures of statistical disclosure risk. We
suggest how experts and non-experts can use these results to explain the DP
guarantee, interpret DP composition theorems, select and justify privacy
parameters, and identify worst-case adversary prior probabilities.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.09678v1">Conformal Prediction for Privacy-Preserving Machine Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> 
  <p><b>Published on:</b> 2025-07-13T15:29:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alexander David Balinsky, Dominik Krzeminski, Alexander Balinsky</p>
    <p><b>Summary:</b> We investigate the integration of Conformal Prediction (CP) with supervised
learning on deterministically encrypted data, aiming to bridge the gap between
rigorous uncertainty quantification and privacy-preserving machine learning.
Using AES-encrypted variants of the MNIST dataset, we demonstrate that CP
methods remain effective even when applied directly in the encrypted domain,
owing to the preservation of data exchangeability under fixed-key encryption.
We test traditional $p$-value-based against $e$-value-based conformal
predictors. Our empirical evaluation reveals that models trained on
deterministically encrypted data retain the ability to extract meaningful
structure, achieving 36.88\% test accuracy -- significantly above random
guessing (9.56\%) observed with per-instance encryption. Moreover,
$e$-value-based CP achieves predictive set coverage of over 60\% with 4.3
loss-threshold calibration, correctly capturing the true label in 4888 out of
5000 test cases. In contrast, the $p$-value-based CP yields smaller predictive
sets but with reduced coverage accuracy. These findings highlight both the
promise and limitations of CP in encrypted data settings and underscore
critical trade-offs between prediction set compactness and reliability. %Our
work sets a foundation for principled uncertainty quantification in secure,
privacy-aware learning systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.09453v1">SmartphoneDemocracy: Privacy-Preserving E-Voting on Decentralized
  Infrastructure using Novel European Identity</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-07-13T02:39:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Michał Jóźwik, Johan Pouwelse</p>
    <p><b>Summary:</b> The digitization of democratic processes promises greater accessibility but
presents challenges in terms of security, privacy, and verifiability. Existing
electronic voting systems often rely on centralized architectures, creating
single points of failure and forcing too much trust in authorities, which
contradicts democratic principles. This research addresses the challenge of
creating a secure, private e-voting system with minimized trust dependencies
designed for the most versatile personal device: the smartphone. We introduce
SmartphoneDemocracy, a novel e-voting protocol that combines three key
technologies: the emerging European Digital Identity (EUDI) Wallet for
Sybil-resistant identity verification, Zero-Knowledge Proofs for
privacy-preserving validation, and a peer-to-peer blockchain (TrustChain) for a
resilient, serverless public bulletin board. Our protocol enables voters to
register and cast ballots anonymously and verifiably directly from their
smartphones. We provide a detailed protocol design, a security analysis against
a defined threat model, and a performance evaluation demonstrating that the
computational and network overhead is feasible for medium- to large-scale
elections. By developing and prototyping this system, we demonstrate a viable
path to empower citizens with a trustworthy, accessible, and user-controlled
digital voting experience.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.09067v2">Quantum-Resilient Privacy Ledger (QRPL): A Sovereign Digital Currency
  for the Post-Quantum Era</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-11T23:02:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Serhan W. Bahar</p>
    <p><b>Summary:</b> The emergence of quantum computing presents profound challenges to existing
cryptographic infrastructures, whilst the development of central bank digital
currencies (CBDCs) has raised concerns regarding privacy preservation and
excessive centralisation in digital payment systems. This paper proposes the
Quantum-Resilient Privacy Ledger (QRPL) as an innovative token-based digital
currency architecture that incorporates National Institute of Standards and
Technology (NIST)-standardised post-quantum cryptography (PQC) with hash-based
zero-knowledge proofs to ensure user sovereignty, scalability, and transaction
confidentiality. Key contributions include adaptations of ephemeral proof
chains for unlinkable transactions, a privacy-weighted Proof-of-Stake (PoS)
consensus to promote equitable participation, and a novel zero-knowledge
proof-based mechanism for privacy-preserving selective disclosure. QRPL aims to
address critical shortcomings in prevailing CBDC designs, including risks of
pervasive surveillance, with a 10-20 second block time to balance security and
throughput in future monetary systems. While conceptual, empirical prototypes
are planned. Future work includes prototype development to validate these
models empirically.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.09051v2">SAGE: A Context-Aware Approach for Mining Privacy Requirements Relevant
  Reviews from Mental Health Apps</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-07-11T21:53:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aakash Sorathiya, Gouri Ginde</p>
    <p><b>Summary:</b> Mental health (MH) apps often require sensitive user data to customize
services for mental wellness needs. However, such data collection practices in
some MH apps raise significant privacy concerns for users. These concerns are
often mentioned in app reviews, but other feedback categories, such as
reliability and usability, tend to take precedence. This poses a significant
challenge in automatically identifying privacy requirements-relevant reviews
(privacy reviews) that can be utilized to extract privacy requirements and
address users' privacy concerns. Thus, this study introduces SAGE, a
context-aware approach to automatically mining privacy reviews from MH apps
using Natural Language Inference (NLI) with MH domain-specific privacy
hypotheses (provides domain-specific context awareness) and a GPT model
(eliminates the need for fine-tuning). The quantitative evaluation of SAGE on a
dataset of 204K app reviews achieved an F1 score of 0.85 without any
fine-tuning, outperforming the fine-tuned baseline classifiers BERT and T5.
Furthermore, SAGE extracted 748 privacy reviews previously overlooked by
keyword-based methods, demonstrating its effectiveness through qualitative
evaluation. These reviews can later be refined into actionable privacy
requirement artifacts.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.08978v1">Characterizing Security and Privacy Teaching Standards for Schools in
  the United States</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-07-11T19:20:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Katherine Limes, Nathan Malkin, Kelsey R. Fulton</p>
    <p><b>Summary:</b> Increasingly, students begin learning aspects of security and privacy during
their primary and secondary education (grades K-12 in the United States).
Individual U.S. states and some national organizations publish teaching
standards -- guidance that outlines expectations for what students should learn
-- which often form the basis for course curricula. However, research has not
yet examined what is covered by these standards and whether the topics align
with what the broader security and privacy community thinks students should
know. To shed light on these questions, we started by collecting computer
science teaching standards from all U.S. states and eight national
organizations. After manually examining a total of 11,954 standards, we labeled
3,778 of them as being related to security and privacy, further classifying
these into 103 topics. Topics ranged from technical subjects like encryption,
network security, and embedded systems to social subjects such as laws, ethics,
and appropriate online behavior. Subsequently, we interviewed 11 security and
privacy professionals to examine how the teaching standards align with their
expectations. We found that, while the specific topics they mentioned mostly
overlapped with those of existing standards, professionals placed a greater
emphasis on threat modeling and security mindset.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.10582v1">Transforming Sensitive Documents into Quantitative Data: An AI-Based
  Preprocessing Toolchain for Structured and Privacy-Conscious Analysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> 
  <p><b>Published on:</b> 2025-07-11T11:58:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anders Ledberg, Anna Thalén</p>
    <p><b>Summary:</b> Unstructured text from legal, medical, and administrative sources offers a
rich but underutilized resource for research in public health and the social
sciences. However, large-scale analysis is hampered by two key challenges: the
presence of sensitive, personally identifiable information, and significant
heterogeneity in structure and language. We present a modular toolchain that
prepares such text data for embedding-based analysis, relying entirely on
open-weight models that run on local hardware, requiring only a
workstation-level GPU and supporting privacy-sensitive research.
  The toolchain employs large language model (LLM) prompting to standardize,
summarize, and, when needed, translate texts to English for greater
comparability. Anonymization is achieved via LLM-based redaction, supplemented
with named entity recognition and rule-based methods to minimize the risk of
disclosure. We demonstrate the toolchain on a corpus of 10,842 Swedish court
decisions under the Care of Abusers Act (LVM), comprising over 56,000 pages.
Each document is processed into an anonymized, standardized summary and
transformed into a document-level embedding. Validation, including manual
review, automated scanning, and predictive evaluation shows the toolchain
effectively removes identifying information while retaining semantic content.
As an illustrative application, we train a predictive model using embedding
vectors derived from a small set of manually labeled summaries, demonstrating
the toolchain's capacity for semi-automated content analysis at scale.
  By enabling structured, privacy-conscious analysis of sensitive documents,
our toolchain opens new possibilities for large-scale research in domains where
textual data was previously inaccessible due to privacy and heterogeneity
constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.08412v1">Enforcing Speech Content Privacy in Environmental Sound Recordings using
  Segment-wise Waveform Reversal</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> 
  <p><b>Published on:</b> 2025-07-11T08:48:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Modan Tailleur, Mathieu Lagrange, Pierre Aumond, Vincent Tourre</p>
    <p><b>Summary:</b> Environmental sound recordings often contain intelligible speech, raising
privacy concerns that limit analysis, sharing and reuse of data. In this paper,
we introduce a method that renders speech unintelligible while preserving both
the integrity of the acoustic scene, and the overall audio quality. Our
approach involves reversing waveform segments to distort speech content. This
process is enhanced through a voice activity detection and speech separation
pipeline, which allows for more precise targeting of speech.
  In order to demonstrate the effectivness of the proposed approach, we
consider a three-part evaluation protocol that assesses: 1) speech
intelligibility using Word Error Rate (WER), 2) sound sources detectability
using Sound source Classification Accuracy-Drop (SCAD) from a widely used
pre-trained model, and 3) audio quality using the Fr\'echet Audio Distance
(FAD), computed with our reference dataset that contains unaltered speech.
Experiments on this simulated evaluation dataset, which consists of linear
mixtures of speech and environmental sound scenes, show that our method
achieves satisfactory speech intelligibility reduction (97.9% WER), minimal
degradation of the sound sources detectability (2.7% SCAD), and high perceptual
quality (FAD of 1.40). An ablation study further highlights the contribution of
each component of the pipeline. We also show that incorporating random splicing
to our speech content privacy enforcement method can enhance the algorithm's
robustness to attempt to recover the clean speech, at a slight cost of audio
quality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.08158v1">Beyond the Worst Case: Extending Differential Privacy Guarantees to
  Realistic Adversaries</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-10T20:36:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marika Swanberg, Meenatchi Sundaram Muthu Selva Annamalai, Jamie Hayes, Borja Balle, Adam Smith</p>
    <p><b>Summary:</b> Differential Privacy (DP) is a family of definitions that bound the
worst-case privacy leakage of a mechanism. One important feature of the
worst-case DP guarantee is it naturally implies protections against adversaries
with less prior information, more sophisticated attack goals, and complex
measures of a successful attack. However, the analytical tradeoffs between the
adversarial model and the privacy protections conferred by DP are not well
understood thus far. To that end, this work sheds light on what the worst-case
guarantee of DP implies about the success of attackers that are more
representative of real-world privacy risks.
  In this paper, we present a single flexible framework that generalizes and
extends the patchwork of bounds on DP mechanisms found in prior work. Our
framework allows us to compute high-probability guarantees for DP mechanisms on
a large family of natural attack settings that previous bounds do not capture.
One class of such settings is the approximate reconstruction of multiple
individuals' data, such as inferring nearly entire columns of a tabular data
set from noisy marginals and extracting sensitive information from DP-trained
language models.
  We conduct two empirical case studies to illustrate the versatility of our
bounds and compare them to the success of state-of-the-art attacks.
Specifically, we study attacks that extract non-uniform PII from a DP-trained
language model, as well as multi-column reconstruction attacks where the
adversary has access to some columns in the clear and attempts to reconstruct
the remaining columns for each person's record. We find that the absolute
privacy risk of attacking non-uniform data is highly dependent on the
adversary's prior probability of success. Our high probability bounds give us a
nuanced understanding of the privacy leakage of DP mechanisms in a variety of
previously understudied attack settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.07700v1">Rethinking the Privacy of Text Embeddings: A Reproducibility Study of
  "Text Embeddings Reveal (Almost) As Much As Text"</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2025-07-10T12:27:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dominykas Seputis, Yongkang Li, Karsten Langerak, Serghei Mihailov</p>
    <p><b>Summary:</b> Text embeddings are fundamental to many natural language processing (NLP)
tasks, extensively applied in domains such as recommendation systems and
information retrieval (IR). Traditionally, transmitting embeddings instead of
raw text has been seen as privacy-preserving. However, recent methods such as
Vec2Text challenge this assumption by demonstrating that controlled decoding
can successfully reconstruct original texts from black-box embeddings. The
unexpectedly strong results reported by Vec2Text motivated us to conduct
further verification, particularly considering the typically non-intuitive and
opaque structure of high-dimensional embedding spaces. In this work, we
reproduce the Vec2Text framework and evaluate it from two perspectives: (1)
validating the original claims, and (2) extending the study through targeted
experiments. First, we successfully replicate the original key results in both
in-domain and out-of-domain settings, with only minor discrepancies arising due
to missing artifacts, such as model checkpoints and dataset splits.
Furthermore, we extend the study by conducting a parameter sensitivity
analysis, evaluating the feasibility of reconstructing sensitive inputs (e.g.,
passwords), and exploring embedding quantization as a lightweight privacy
defense. Our results show that Vec2Text is effective under ideal conditions,
capable of reconstructing even password-like sequences that lack clear
semantics. However, we identify key limitations, including its sensitivity to
input sequence length. We also find that Gaussian noise and quantization
techniques can mitigate the privacy risks posed by Vec2Text, with quantization
offering a simpler and more widely applicable solution. Our findings emphasize
the need for caution in using text embeddings and highlight the importance of
further research into robust defense mechanisms for NLP systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.08882v1">Less Stress, More Privacy: Stress Detection on Anonymized Speech of Air
  Traffic Controllers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">  
  <p><b>Published on:</b> 2025-07-10T11:48:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Janaki Viswanathan, Alexander Blatt, Konrad Hagemann, Dietrich Klakow</p>
    <p><b>Summary:</b> Air traffic control (ATC) demands multi-tasking under time pressure with high
consequences of an error. This can induce stress. Detecting stress is a key
point in maintaining the high safety standards of ATC. However, processing ATC
voice data entails privacy restrictions, e.g. the General Data Protection
Regulation (GDPR) law. Anonymizing the ATC voice data is one way to comply with
these restrictions. In this paper, different architectures for stress detection
for anonymized ATCO speech are evaluated. Our best networks reach a stress
detection accuracy of 93.6% on an anonymized version of the Speech Under
Simulated and Actual Stress (SUSAS) dataset and an accuracy of 80.1% on our
anonymized ATC simulation dataset. This shows that privacy does not have to be
an impediment in building well-performing deep-learning-based models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.07565v2">Secure Cooperative Gradient Coding: Optimality, Reliability, and Global
  Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2025-07-10T09:10:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shudi Weng, Chao Ren, Yizhou Zhao, Ming Xiao, Mikael Skoglund</p>
    <p><b>Summary:</b> This paper studies privacy-sensitive federated learning (FL) under unreliable
communication, with a focus on secure aggregation and straggler mitigation. To
preserve user privacy without compromising the utility of the global model,
secure aggregation emerges as a promising approach by coordinating the use of
privacy-preserving noise (secret keys) across participating clients. However,
the unreliable communication will randomly disrupt the key coordination and
disable the exact recovery of the global model in secure aggregation.
Furthermore, unreliable communication can distort the optimization trajectory,
causing the global model to deviate further from the intended global optimum.To
address these challenges, we propose Secure Cooperative Gradient Coding
(SecCoGC), a practical solution that achieves accurate aggregation with
arbitrarily strong privacy guarantees and is inherently robust to communication
uncertainties. To ensure fairness in privacy protection, we further introduce
Fair-SecCoGC, an extension of SecCoGC that enforces equitable privacy
preservation across all clients. Notably, Fair-SecCoGC achieves optimal privacy
under a per-key total power constraint. We formally formulate the problem of
secure aggregation in the real field and present both general and
computationally efficient methods for secret key construction. Our privacy
analysis covers both Local Mutual Information Privacy (LMIP) and Local
Differential Privacy (LDP) across all protocol layers, accounting for
intermittent networks and correlation among secret keys. In addition, we
characterize the system reliability and convergence properties of the proposed
scheme. Experimental results demonstrate that SecCoGC achieves strong
resilience to unreliable communication while maintaining arbitrarily strong
privacy guarantees, yielding test accuracy improvements of 20% to 70% over
existing privacy-preserving methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.08050v1">An Enhanced Privacy-preserving Federated Few-shot Learning Framework for
  Respiratory Disease Diagnosis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-10T07:47:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ming Wang, Zhaoyang Duan, Dong Xue, Fangzhou Liu, Zhongheng Zhang</p>
    <p><b>Summary:</b> The labor-intensive nature of medical data annotation presents a significant
challenge for respiratory disease diagnosis, resulting in a scarcity of
high-quality labeled datasets in resource-constrained settings. Moreover,
patient privacy concerns complicate the direct sharing of local medical data
across institutions, and existing centralized data-driven approaches, which
rely on amounts of available data, often compromise data privacy. This study
proposes a federated few-shot learning framework with privacy-preserving
mechanisms to address the issues of limited labeled data and privacy protection
in diagnosing respiratory diseases. In particular, a meta-stochastic gradient
descent algorithm is proposed to mitigate the overfitting problem that arises
from insufficient data when employing traditional gradient descent methods for
neural network training. Furthermore, to ensure data privacy against gradient
leakage, differential privacy noise from a standard Gaussian distribution is
integrated into the gradients during the training of private models with local
data, thereby preventing the reconstruction of medical images. Given the
impracticality of centralizing respiratory disease data dispersed across
various medical institutions, a weighted average algorithm is employed to
aggregate local diagnostic models from different clients, enhancing the
adaptability of a model across diverse scenarios. Experimental results show
that the proposed method yields compelling results with the implementation of
differential privacy, while effectively diagnosing respiratory diseases using
data from different structures, categories, and distributions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.08878v1">Towards Privacy-Preserving and Personalized Smart Homes via Tailored
  Small Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-10T05:36:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xinyu Huang, Leming Shen, Zijing Ma, Yuanqing Zheng</p>
    <p><b>Summary:</b> Large Language Models (LLMs) have showcased remarkable generalizability in
language comprehension and hold significant potential to revolutionize
human-computer interaction in smart homes. Existing LLM-based smart home
assistants typically transmit user commands, along with user profiles and home
configurations, to remote servers to obtain personalized services. However,
users are increasingly concerned about the potential privacy leaks to the
remote servers. To address this issue, we develop HomeLLaMA, an on-device
assistant for privacy-preserving and personalized smart home serving with a
tailored small language model (SLM). HomeLLaMA learns from cloud LLMs to
deliver satisfactory responses and enable user-friendly interactions. Once
deployed, HomeLLaMA facilitates proactive interactions by continuously updating
local SLMs and user profiles. To further enhance user experience while
protecting their privacy, we develop PrivShield to offer an optional
privacy-preserving LLM-based smart home serving for those users, who are
unsatisfied with local responses and willing to send less-sensitive queries to
remote servers. For evaluation, we build a comprehensive benchmark DevFinder to
assess the service quality. Extensive experiments and user studies (M=100)
demonstrate that HomeLLaMA can provide personalized services while
significantly enhancing user privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.07320v1">Optimizing Communication and Device Clustering for Clustered Federated
  Learning with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-07-09T22:44:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dongyu Wei, Xiaoren Xu, Shiwen Mao, Mingzhe Chen</p>
    <p><b>Summary:</b> In this paper, a secure and communication-efficient clustered federated
learning (CFL) design is proposed. In our model, several base stations (BSs)
with heterogeneous task-handling capabilities and multiple users with
non-independent and identically distributed (non-IID) data jointly perform CFL
training incorporating differential privacy (DP) techniques. Since each BS can
process only a subset of the learning tasks and has limited wireless resource
blocks (RBs) to allocate to users for federated learning (FL) model parameter
transmission, it is necessary to jointly optimize RB allocation and user
scheduling for CFL performance optimization. Meanwhile, our considered CFL
method requires devices to use their limited data and FL model information to
determine their task identities, which may introduce additional communication
overhead. We formulate an optimization problem whose goal is to minimize the
training loss of all learning tasks while considering device clustering, RB
allocation, DP noise, and FL model transmission delay. To solve the problem, we
propose a novel dynamic penalty function assisted value decomposed multi-agent
reinforcement learning (DPVD-MARL) algorithm that enables distributed BSs to
independently determine their connected users, RBs, and DP noise of the
connected users but jointly minimize the training loss of all learning tasks
across all BSs. Different from the existing MARL methods that assign a large
penalty for invalid actions, we propose a novel penalty assignment scheme that
assigns penalty depending on the number of devices that cannot meet
communication constraints (e.g., delay), which can guide the MARL scheme to
quickly find valid actions, thus improving the convergence speed. Simulation
results show that the DPVD-MARL can improve the convergence rate by up to 20%
and the ultimate accumulated rewards by 15% compared to independent Q-learning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.07258v1">FedP3E: Privacy-Preserving Prototype Exchange for Non-IID IoT Malware
  Detection in Cross-Silo Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-09T20:07:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rami Darwish, Mahmoud Abdelsalam, Sajad Khorsandroo, Kaushik Roy</p>
    <p><b>Summary:</b> As IoT ecosystems continue to expand across critical sectors, they have
become prominent targets for increasingly sophisticated and large-scale malware
attacks. The evolving threat landscape, combined with the sensitive nature of
IoT-generated data, demands detection frameworks that are both
privacy-preserving and resilient to data heterogeneity. Federated Learning (FL)
offers a promising solution by enabling decentralized model training without
exposing raw data. However, standard FL algorithms such as FedAvg and FedProx
often fall short in real-world deployments characterized by class imbalance and
non-IID data distributions -- particularly in the presence of rare or disjoint
malware classes. To address these challenges, we propose FedP3E
(Privacy-Preserving Prototype Exchange), a novel FL framework that supports
indirect cross-client representation sharing while maintaining data privacy.
Each client constructs class-wise prototypes using Gaussian Mixture Models
(GMMs), perturbs them with Gaussian noise, and transmits only these compact
summaries to the server. The aggregated prototypes are then distributed back to
clients and integrated into local training, supported by SMOTE-based
augmentation to enhance representation of minority malware classes. Rather than
relying solely on parameter averaging, our prototype-driven mechanism enables
clients to enrich their local models with complementary structural patterns
observed across the federation -- without exchanging raw data or gradients.
This targeted strategy reduces the adverse impact of statistical heterogeneity
with minimal communication overhead. We evaluate FedP3E on the N-BaIoT dataset
under realistic cross-silo scenarios with varying degrees of data imbalance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.07210v1">WatchWitch: Interoperability, Privacy, and Autonomy for the Apple Watch</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-09T18:33:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nils Rollshausen, Alexander Heinrich, Matthias Hollick, Jiska Classen</p>
    <p><b>Summary:</b> Smartwatches such as the Apple Watch collect vast amounts of intimate health
and fitness data as we wear them. Users have little choice regarding how this
data is processed: The Apple Watch can only be used with Apple's iPhones, using
their software and their cloud services. We are the first to publicly
reverse-engineer the watch's wireless protocols, which led to discovering
multiple security issues in Apple's proprietary implementation. With
WatchWitch, our custom Android reimplementation, we break out of Apple's walled
garden -- demonstrating practical interoperability with enhanced privacy
controls and data autonomy. We thus pave the way for more consumer choice in
the smartwatch ecosystem, offering users more control over their devices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.06969v1">Unifying Re-Identification, Attribute Inference, and Data Reconstruction
  Risks in Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> 
  <p><b>Published on:</b> 2025-07-09T15:59:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bogdan Kulynych, Juan Felipe Gomez, Georgios Kaissis, Jamie Hayes, Borja Balle, Flavio du Pin Calmon, Jean Louis Raisaro</p>
    <p><b>Summary:</b> Differentially private (DP) mechanisms are difficult to interpret and
calibrate because existing methods for mapping standard privacy parameters to
concrete privacy risks -- re-identification, attribute inference, and data
reconstruction -- are both overly pessimistic and inconsistent. In this work,
we use the hypothesis-testing interpretation of DP ($f$-DP), and determine that
bounds on attack success can take the same unified form across
re-identification, attribute inference, and data reconstruction risks. Our
unified bounds are (1) consistent across a multitude of attack settings, and
(2) tunable, enabling practitioners to evaluate risk with respect to arbitrary
(including worst-case) levels of baseline risk. Empirically, our results are
tighter than prior methods using $\varepsilon$-DP, R\'enyi DP, and concentrated
DP. As a result, calibrating noise using our bounds can reduce the required
noise by 20% at the same risk level, which yields, e.g., more than 15pp
accuracy increase in a text classification task. Overall, this unifying
perspective provides a principled framework for interpreting and calibrating
the degree of protection in DP against specific levels of re-identification,
attribute inference, or data reconstruction risk.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.08864v1">Privacy-Utility-Fairness: A Balanced Approach to Vehicular-Traffic
  Management System</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2025-07-09T13:49:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Poushali Sengupta, Sabita Maharjan, frank Eliassen, Yan Zhang</p>
    <p><b>Summary:</b> Location-based vehicular traffic management faces significant challenges in
protecting sensitive geographical data while maintaining utility for traffic
management and fairness across regions. Existing state-of-the-art solutions
often fail to meet the required level of protection against linkage attacks and
demographic biases, leading to privacy leakage and inequity in data analysis.
In this paper, we propose a novel algorithm designed to address the challenges
regarding the balance of privacy, utility, and fairness in location-based
vehicular traffic management systems. In this context, utility means providing
reliable and meaningful traffic information, while fairness ensures that all
regions and individuals are treated equitably in data use and decision-making.
Employing differential privacy techniques, we enhance data security by
integrating query-based data access with iterative shuffling and calibrated
noise injection, ensuring that sensitive geographical data remains protected.
We ensure adherence to epsilon-differential privacy standards by implementing
the Laplace mechanism. We implemented our algorithm on vehicular location-based
data from Norway, demonstrating its ability to maintain data utility for
traffic management and urban planning while ensuring fair representation of all
geographical areas without being overrepresented or underrepresented.
Additionally, we have created a heatmap of Norway based on our model,
illustrating the privatized and fair representation of the traffic conditions
across various cities. Our algorithm provides privacy in vehicular traffic</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.06652v1">Federated Learning Inspired Fuzzy Systems: Decentralized Rule Updating
  for Privacy and Scalable Decision Making</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-07-09T08:34:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arthur Alexander Lim, Zhen Bin It, Jovan Bowen Heng, Tee Hui Teo</p>
    <p><b>Summary:</b> Fuzzy systems are a way to allow machines, systems and frameworks to deal
with uncertainty, which is not possible in binary systems that most computers
use. These systems have already been deployed for certain use cases, and fuzzy
systems could be further improved as proposed in this paper. Such technologies
to draw inspiration from include machine learning and federated learning.
Machine learning is one of the recent breakthroughs of technology and could be
applied to fuzzy systems to further improve the results it produces. Federated
learning is also one of the recent technologies that have huge potential, which
allows machine learning training to improve by reducing privacy risk, reducing
burden on networking infrastructure, and reducing latency of the latest model.
Aspects from federated learning could be used to improve federated learning,
such as applying the idea of updating the fuzzy rules that make up a key part
of fuzzy systems, to further improve it over time. This paper discusses how
these improvements would be implemented in fuzzy systems, and how it would
improve fuzzy systems. It also discusses certain limitations on the potential
improvements. It concludes that these proposed ideas and improvements require
further investigation to see how far the improvements are, but the potential is
there to improve fuzzy systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.06619v1">Steps Adaptive Decay DPSGD: Enhancing Performance on Imbalanced Datasets
  with Differential Privacy with HAM10000</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2025-07-09T07:46:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaobo Huang, Fang Xie</p>
    <p><b>Summary:</b> When applying machine learning to medical image classification, data leakage
is a critical issue. Previous methods, such as adding noise to gradients for
differential privacy, work well on large datasets like MNIST and CIFAR-100, but
fail on small, imbalanced medical datasets like HAM10000. This is because the
imbalanced distribution causes gradients from minority classes to be clipped
and lose crucial information, while majority classes dominate. This leads the
model to fall into suboptimal solutions early. To address this, we propose
SAD-DPSGD, which uses a linear decaying mechanism for noise and clipping
thresholds. By allocating more privacy budget and using higher clipping
thresholds in the initial training phases, the model avoids suboptimal
solutions and enhances performance. Experiments show that SAD-DPSGD outperforms
Auto-DPSGD on HAM10000, improving accuracy by 2.15% under $\epsilon = 3.0$ ,
$\delta = 10^{-3}$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.08853v1">Clio-X: AWeb3 Solution for Privacy-Preserving AI Access to Digital
  Archives</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Digital Libraries-D91E36"> 
  <p><b>Published on:</b> 2025-07-09T05:30:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Victoria L. Lemieux, Rosa Gil, Faith Molosiwa, Qihong Zhou, Binming Li, Roberto Garcia, Luis De La Torre Cubillo, Zehua Wang</p>
    <p><b>Summary:</b> As archives turn to artificial intelligence to manage growing volumes of
digital records, privacy risks inherent in current AI data practices raise
critical concerns about data sovereignty and ethical accountability. This paper
explores how privacy-enhancing technologies (PETs) and Web3 architectures can
support archives to preserve control over sensitive content while still being
able to make it available for access by researchers. We present Clio-X, a
decentralized, privacy-first Web3 digital solution designed to embed PETs into
archival workflows and support AI-enabled reference and access. Drawing on a
user evaluation of a medium-fidelity prototype, the study reveals both interest
in the potential of the solution and significant barriers to adoption related
to trust, system opacity, economic concerns, and governance. Using Rogers'
Diffusion of Innovation theory, we analyze the sociotechnical dimensions of
these barriers and propose a path forward centered on participatory design and
decentralized governance through a Clio-X Decentralized Autonomous
Organization. By integrating technical safeguards with community-based
oversight, Clio-X offers a novel model to ethically deploy AI in cultural
heritage contexts.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.06508v1">Subgraph Counting under Edge Local Differential Privacy Based on Noisy
  Adjacency Matrix</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-09T03:13:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jintao Guo, Ying Zhou, Chao Li, Guixun Luo</p>
    <p><b>Summary:</b> When analyzing connection patterns within graphs, subgraph counting serves as
an effective and fundamental approach. Edge-local differential privacy
(edge-LDP) and shuffle model have been employed to achieve subgraph counting
under a privacy-preserving situation. Existing algorithms are plagued by high
time complexity, excessive download costs, low accuracy, or dependence on
trusted third parties. To address the aforementioned challenges, we propose the
Noisy Adjacency Matrix (NAM), which combines differential privacy with the
adjacency matrix of the graph. NAM offers strong versatility and scalability,
making it applicable to a wider range of DP variants, DP mechanisms, and graph
types. Based on NAM, we designed five algorithms (TriOR, TriTR, TriMTR, QuaTR,
and 2STAR) to count three types of subgraphs: triangles, quadrangles, and
2-stars. Theoretical and experimental results demonstrate that in triangle
counting, TriOR maximizes accuracy with reduced time complexity among one-round
algorithms, TriTR achieves optimal accuracy, TriMTR achieves the highest
accuracy under low download costs, and QuaTR stands as the first quadrangle
counting algorithm under pure edge-LDP. We implement edge-LDP for noisy data
via a confidence interval-inspired method, providing DP guarantees on
randomized data. Our 2STAR algorithm achieves the highest accuracy in 2-star
counting and can be derived as a byproduct of two-round triangle or quadrangle
counting algorithms, enabling efficient joint estimation of triangle,
quadrangle, and 2-star counts within two query rounds.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.06350v1">An Architecture for Privacy-Preserving Telemetry Scheme</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-07-08T19:20:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kenneth Odoh</p>
    <p><b>Summary:</b> We present a privacy-preserving telemetry aggregation scheme. Our underlying
frequency estimation routine works within the framework of differential
privacy. The design philosophy follows a client-server architecture.
Furthermore, the system uses a local differential privacy scheme where data
gets randomized on the client before submitting the request to the resource
server. This scheme allows for data analysis on de-identified data by carefully
adding noise to prevent re-identification attacks, thereby facilitating public
data release without compromising the identifiability of the individual record.
This work further enhances privacy guarantees by leveraging Oblivious HTTP
(OHTTP) to achieve increased privacy protection for data in transit that
addresses pre-existing privacy vulnerabilities in raw HTTP. We provide an
implementation that focuses on frequency estimation with a histogram of a known
dictionary. Our resulting formulation based on OHTTP has provided stricter
privacy safeguards when compared to trusting an organization to manually delete
identifying information from the client's request in the ingestor as deployed
in reference work~\cite{apple2017}. Code available at
https://github.com/kenluck2001/miscellaneous/tree/master/src/Privacy-Preserving-Telemetry.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.06008v1">The Impact of Event Data Partitioning on Privacy-aware Process Discovery</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2025-07-08T14:13:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jungeun Lim, Stephan A. Fahrenkrog-Petersen, Xixi Lu, Jan Mendling, Minseok Song</p>
    <p><b>Summary:</b> Information systems support the execution of business processes. The event
logs of these executions generally contain sensitive information about
customers, patients, and employees. The corresponding privacy challenges can be
addressed by anonymizing the event logs while still retaining utility for
process discovery. However, trading off utility and privacy is difficult: the
higher the complexity of event log, the higher the loss of utility by
anonymization. In this work, we propose a pipeline that combines anonymization
and event data partitioning, where event abstraction is utilized for
partitioning. By leveraging event abstraction, event logs can be segmented into
multiple parts, allowing each sub-log to be anonymized separately. This
pipeline preserves privacy while mitigating the loss of utility. To validate
our approach, we study the impact of event partitioning on two anonymization
techniques using three real-world event logs and two process discovery
techniques. Our results demonstrate that event partitioning can bring
improvements in process discovery utility for directly-follows-based
anonymization techniques.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.05875v1">Post-Processing in Local Differential Privacy: An Extensive Evaluation
  and Benchmark Platform</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-08T10:59:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alireza Khodaie, Berkay Kemal Balioglu, Mehmet Emre Gursoy</p>
    <p><b>Summary:</b> Local differential privacy (LDP) has recently gained prominence as a powerful
paradigm for collecting and analyzing sensitive data from users' devices.
However, the inherent perturbation added by LDP protocols reduces the utility
of the collected data. To mitigate this issue, several post-processing (PP)
methods have been developed. Yet, the comparative performance of PP methods
under diverse settings remains underexplored. In this paper, we present an
extensive benchmark comprising 6 popular LDP protocols, 7 PP methods, 4 utility
metrics, and 6 datasets to evaluate the behaviors and optimality of PP methods
under diverse conditions. Through extensive experiments, we show that while PP
can substantially improve utility when the privacy budget is small (i.e.,
strict privacy), its benefit diminishes as the privacy budget grows. Moreover,
our findings reveal that the optimal PP method depends on multiple factors,
including the choice of LDP protocol, privacy budget, data characteristics
(such as distribution and domain size), and the specific utility metric. To
advance research in this area and assist practitioners in identifying the most
suitable PP method for their setting, we introduce LDP$^3$, an open-source
benchmark platform. LDP$^3$ contains all methods used in our experimental
analysis, and it is designed in a modular, extensible, and multi-threaded way
for future use and development.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.05872v1">LDP$^3$: An Extensible and Multi-Threaded Toolkit for Local Differential
  Privacy Protocols and Post-Processing Methods</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-08T10:51:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Berkay Kemal Balioglu, Alireza Khodaie, Mehmet Emre Gursoy</p>
    <p><b>Summary:</b> Local differential privacy (LDP) has become a prominent notion for
privacy-preserving data collection. While numerous LDP protocols and
post-processing (PP) methods have been developed, selecting an optimal
combination under different privacy budgets and datasets remains a challenge.
Moreover, the lack of a comprehensive and extensible LDP benchmarking toolkit
raises difficulties in evaluating new protocols and PP methods. To address
these concerns, this paper presents LDP$^3$ (pronounced LDP-Cube), an
open-source, extensible, and multi-threaded toolkit for LDP researchers and
practitioners. LDP$^3$ contains implementations of several LDP protocols, PP
methods, and utility metrics in a modular and extensible design. Its modular
design enables developers to conveniently integrate new protocols and PP
methods. Furthermore, its multi-threaded nature enables significant reductions
in execution times via parallelization. Experimental evaluations demonstrate
that: (i) using LDP$^3$ to select a good protocol and post-processing method
substantially improves utility compared to a bad or random choice, and (ii) the
multi-threaded design of LDP$^3$ brings substantial benefits in terms of
efficiency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.08843v1">Can We Predict Your Next Move Without Breaking Your Privacy?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-08T08:13:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arpita Soni, Sahil Tripathi, Gautam Siddharth Kashyap, Manaswi Kulahara, Mohammad Anas Azeez, Zohaib Hasan Siddiqui, Nipun Joshi, Jiechao Gao</p>
    <p><b>Summary:</b> We propose FLLL3M--Federated Learning with Large Language Models for Mobility
Modeling--a privacy-preserving framework for Next-Location Prediction (NxLP).
By retaining user data locally and leveraging LLMs through an efficient outer
product mechanism, FLLL3M ensures high accuracy with low resource demands. It
achieves SOT results on Gowalla (Acc@1: 12.55, MRR: 0.1422), WeePlace (10.71,
0.1285), Brightkite (10.42, 0.1169), and FourSquare (8.71, 0.1023), while
reducing parameters by up to 45.6% and memory usage by 52.7%.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.05610v2">On the Inherent Privacy of Zeroth Order Projected Gradient Descent</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2025-07-08T02:38:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Devansh Gupta, Meisam Razaviyayn, Vatsal Sharan</p>
    <p><b>Summary:</b> Differentially private zeroth-order optimization methods have recently gained
popularity in private fine tuning of machine learning models due to their
reduced memory requirements. Current approaches for privatizing zeroth-order
methods rely on adding Gaussian noise to the estimated zeroth-order gradients.
However, since the search direction in the zeroth-order methods is inherently
random, researchers including Tang et al. (2024) and Zhang et al. (2024a) have
raised an important question: is the inherent noise in zeroth-order estimators
sufficient to ensure the overall differential privacy of the algorithm? This
work settles this question for a class of oracle-based optimization algorithms
where the oracle returns zeroth-order gradient estimates. In particular, we
show that for a fixed initialization, there exist strongly convex objective
functions such that running (Projected) Zeroth-Order Gradient Descent (ZO-GD)
is not differentially private. Furthermore, we show that even with random
initialization and without revealing (initial and) intermediate iterates, the
privacy loss in ZO-GD can grow superlinearly with the number of iterations when
minimizing convex objective functions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.05415v1">Layered, Overlapping, and Inconsistent: A Large-Scale Analysis of the
  Multiple Privacy Policies and Controls of U.S. Banks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-07T18:55:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lu Xian, Van Tran, Lauren Lee, Meera Kumar, Yichen Zhang, Florian Schaub</p>
    <p><b>Summary:</b> Privacy policies are often complex. An exception is the two-page standardized
notice that U.S. financial institutions must provide under the
Gramm-Leach-Bliley Act (GLBA). However, banks now operate websites, mobile
apps, and other services that involve complex data sharing practices that
require additional privacy notices and do-not-sell opt-outs. We conducted a
large-scale analysis of how U.S. banks implement privacy policies and controls
in response to GLBA; other federal privacy policy requirements; and the
California Consumer Privacy Act (CCPA), a key example for U.S. state privacy
laws. We focused on the disclosure and control of a set of especially
privacy-invasive practices: third-party data sharing for marketing-related
purposes. We collected privacy policies for the 2,067 largest U.S. banks,
45.3\% of which provided multiple policies. Across disclosures and controls
within the \textit{same} bank, we identified frequent, concerning
inconsistencies -- such as banks indicating in GLBA notices that they do not
share with third parties but disclosing sharing elsewhere, or using third-party
marketing/advertising cookies without disclosure. This multiplicity of
policies, with the inconsistencies it causes, may create consumer confusion and
undermine the transparency goals of the very laws that require them. Our
findings call into question whether current policy requirements, such as the
GLBA notice, are achieving their intended goals in today's online banking
landscape. We discuss potential avenues for reforming and harmonizing privacy
policies and control requirements across federal and state laws.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.05391v1">Controlling What You Share: Assessing Language Model Adherence to
  Privacy Preferences</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-07T18:22:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guillem Ramírez, Alexandra Birch, Ivan Titov</p>
    <p><b>Summary:</b> Large language models (LLMs) are primarily accessed via commercial APIs, but
this often requires users to expose their data to service providers. In this
paper, we explore how users can stay in control of their data by using privacy
profiles: simple natural language instructions that say what should and should
not be revealed. We build a framework where a local model uses these
instructions to rewrite queries, only hiding details deemed sensitive by the
user, before sending them to an external model, thus balancing privacy with
performance. To support this research, we introduce PEEP, a multilingual
dataset of real user queries annotated to mark private content and paired with
synthetic privacy profiles. Our experiments with lightweight LLMs show they can
follow these instructions to some extent, but also face consistent challenges,
highlighting the need for models that better understand and comply with
user-defined privacy preferences.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.05175v1">Blind Targeting: Personalization under Third-Party Privacy Constraints</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">  
  <p><b>Published on:</b> 2025-07-07T16:30:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anya Shchetkina</p>
    <p><b>Summary:</b> Major advertising platforms recently increased privacy protections by
limiting advertisers' access to individual-level data. Instead of providing
access to granular raw data, the platforms only allow a limited number of
aggregate queries to a dataset, which is further protected by adding
differentially private noise. This paper studies whether and how advertisers
can design effective targeting policies within these restrictive privacy
preserving data environments. To achieve this, I develop a probabilistic
machine learning method based on Bayesian optimization, which facilitates
dynamic data exploration. Since Bayesian optimization was designed to sample
points from a function to find its maximum, it is not applicable to aggregate
queries and to targeting. Therefore, I introduce two innovations: (i) integral
updating of posteriors which allows to select the best regions of the data to
query rather than individual points and (ii) a targeting-aware acquisition
function that dynamically selects the most informative regions for the
targeting task. I identify the conditions of the dataset and privacy
environment that necessitate the use of such a "smart" querying strategy. I
apply the strategic querying method to the Criteo AI Labs dataset for uplift
modeling (Diemert et al., 2018) that contains visit and conversion data from
14M users. I show that an intuitive benchmark strategy only achieves 33% of the
non-privacy-preserving targeting potential in some cases, while my strategic
querying method achieves 97-101% of that potential, and is statistically
indistinguishable from Causal Forest (Athey et al., 2019): a state-of-the-art
non-privacy-preserving machine learning targeting method.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.04771v1">Efficient Unlearning with Privacy Guarantees</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-07-07T08:46:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Josep Domingo-Ferrer, Najeeb Jebreel, David Sánchez</p>
    <p><b>Summary:</b> Privacy protection laws, such as the GDPR, grant individuals the right to
request the forgetting of their personal data not only from databases but also
from machine learning (ML) models trained on them. Machine unlearning has
emerged as a practical means to facilitate model forgetting of data instances
seen during training. Although some existing machine unlearning methods
guarantee exact forgetting, they are typically costly in computational terms.
On the other hand, more affordable methods do not offer forgetting guarantees
and are applicable only to specific ML models. In this paper, we present
\emph{efficient unlearning with privacy guarantees} (EUPG), a novel machine
unlearning framework that offers formal privacy guarantees to individuals whose
data are being unlearned. EUPG involves pre-training ML models on data
protected using privacy models, and it enables {\em efficient unlearning with
the privacy guarantees offered by the privacy models in use}. Through empirical
evaluation on four heterogeneous data sets protected with $k$-anonymity and
$\epsilon$-differential privacy as privacy models, our approach demonstrates
utility and forgetting effectiveness comparable to those of exact unlearning
methods, while significantly reducing computational and storage costs. Our code
is available at https://github.com/najeebjebreel/EUPG.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.04528v1">Towards integration of Privacy Enhancing Technologies in Explainable
  Artificial Intelligence</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-06T20:45:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sonal Allana, Rozita Dara, Xiaodong Lin, Pulei Xiong</p>
    <p><b>Summary:</b> Explainable Artificial Intelligence (XAI) is a crucial pathway in mitigating
the risk of non-transparency in the decision-making process of black-box
Artificial Intelligence (AI) systems. However, despite the benefits, XAI
methods are found to leak the privacy of individuals whose data is used in
training or querying the models. Researchers have demonstrated privacy attacks
that exploit explanations to infer sensitive personal information of
individuals. Currently there is a lack of defenses against known privacy
attacks targeting explanations when vulnerable XAI are used in production and
machine learning as a service system. To address this gap, in this article, we
explore Privacy Enhancing Technologies (PETs) as a defense mechanism against
attribute inference on explanations provided by feature-based XAI methods. We
empirically evaluate 3 types of PETs, namely synthetic training data,
differentially private training and noise addition, on two categories of
feature-based XAI. Our evaluation determines different responses from the
mitigation methods and side-effects of PETs on other system properties such as
utility and performance. In the best case, PETs integration in explanations
reduced the risk of the attack by 49.47%, while maintaining model utility and
explanation quality. Through our evaluation, we identify strategies for using
PETs in XAI for maximizing benefits and minimizing the success of this privacy
attack on sensitive personal information.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.04185v1">From Legal Text to Tech Specs: Generative AI's Interpretation of Consent
  in Privacy Law</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-07-05T23:36:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aniket Kesari, Travis Breaux, Tom Norton, Sarah Santos, Anmol Singhal</p>
    <p><b>Summary:</b> Privacy law and regulation have turned to "consent" as the legitimate basis
for collecting and processing individuals' data. As governments have rushed to
enshrine consent requirements in their privacy laws, such as the California
Consumer Privacy Act (CCPA), significant challenges remain in understanding how
these legal mandates are operationalized in software. The opaque nature of
software development processes further complicates this translation. To address
this, we explore the use of Large Language Models (LLMs) in requirements
engineering to bridge the gap between legal requirements and technical
implementation. This study employs a three-step pipeline that involves using an
LLM to classify software use cases for compliance, generating LLM modifications
for non-compliant cases, and manually validating these changes against legal
standards. Our preliminary findings highlight the potential of LLMs in
automating compliance tasks, while also revealing limitations in their
reasoning capabilities. By benchmarking LLMs against real-world use cases, this
research provides insights into leveraging AI-driven solutions to enhance legal
compliance of software.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.04104v1">Human-Centered Interactive Anonymization for Privacy-Preserving Machine
  Learning: A Case for Human-Guided k-Anonymity</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-05T17:20:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sri Harsha Gajavalli</p>
    <p><b>Summary:</b> Privacy-preserving machine learning (ML) seeks to balance data utility and
privacy, especially as regulations like the GDPR mandate the anonymization of
personal data for ML applications. Conventional anonymization approaches often
reduce data utility due to indiscriminate generalization or suppression of data
attributes. In this study, we propose an interactive approach that incorporates
human input into the k-anonymization process, enabling domain experts to guide
attribute preservation based on contextual importance. Using the UCI Adult
dataset, we compare classification outcomes of interactive human-influenced
anonymization with traditional, fully automated methods. Our results show that
human input can enhance data utility in some cases, although results vary
across tasks and settings. We discuss limitations of our approach and suggest
potential areas for improved interactive frameworks in privacy-aware ML.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.03694v1">Willchain: Decentralized, Privacy-Preserving, Self-Executing, Digital
  Wills</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computational Engineering, Finance, and Science-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2025-07-04T16:23:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jovonni L. PHarr</p>
    <p><b>Summary:</b> This work presents a novel decentralized protocol for digital estate planning
that integrates advances distributed computing, and cryptography. The original
proof-of-concept was constructed using purely solidity contracts. Since then,
we have enhanced the implementation into a layer-1 protocol that uses modern
interchain communication to connect several heterogeneous chain types. A key
contribution of this research is the implementation of several modern
cryptographic primitives to support various forms of claims for information
validation. These primitives introduce an unmatched level of privacy to the
process of digital inheritance. We also demonstrate on a set of heterogeneous
smart contracts, following the same spec, on each chain to serve as entry
points, gateways, or bridge contracts that are invoked via a path from the will
module on our protocol, to the contract. This ensures a fair and secure
distribution of digital assets in accordance with the wishes of the decedent
without the requirement of moving their funds. This research further extends
its innovations with a user interaction model, featuring a check-in system and
account abstraction process, which enhances flexibility and user-friendliness
without compromising on security. By developing a dedicated permissionless
blockchain that is secured by a network of validators, and interchain relayers,
the proposed protocol signifies a transformation in the digital estate planning
industry and illustrates the potential of blockchain technology in
revolutionizing traditional legal and personal spheres. Implementing a
cryptoeconomic network at the core of inheritance planning allows for unique
incentive compatible economic mechanisms to be constructed.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.02727v1">Quantifying Classifier Utility under Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2025-07-03T15:42:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ye Zheng, Yidan Hu</p>
    <p><b>Summary:</b> Local differential privacy (LDP) provides a rigorous and quantifiable privacy
guarantee for personal data by introducing perturbation at the data source.
However, quantifying the impact of these perturbations on classifier utility
remains a theoretical challenge, particularly for complex or black-box
classifiers.
  This paper presents a framework for theoretically quantifying classifier
utility under LDP mechanisms. The key insight is that LDP perturbation is
concentrated around the original data with a specific probability, transforming
utility analysis of the classifier into its robustness analysis in this
concentrated region. Our framework connects the concentration analysis of LDP
mechanisms with the robustness analysis of classifiers. It treats LDP
mechanisms as general distributional functions and classifiers as black-box
functions, thus applicable to any LDP mechanism and classifier. A direct
application of our utility quantification is guiding the selection of LDP
mechanisms and privacy parameters for a given classifier. Notably, our analysis
shows that a piecewise-based mechanism leads to better utility compared to
alternatives in common scenarios.
  Using this framework alongside two novel refinement techniques, we conduct
case studies on utility quantification for typical mechanism-classifier
combinations. The results demonstrate that our theoretical utility
quantification aligns closely with empirical observations, particularly when
classifiers operate in lower-dimensional input spaces.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.02414v1">Privacy-preserving Preselection for Face Identification Based on Packing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-03T08:15:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rundong Xin, Taotao Wang, Jin Wang, Chonghe Zhao, Jing Wang</p>
    <p><b>Summary:</b> Face identification systems operating in the ciphertext domain have garnered
significant attention due to increasing privacy concerns and the potential
recovery of original facial data. However, as the size of ciphertext template
libraries grows, the face retrieval process becomes progressively more
time-intensive. To address this challenge, we propose a novel and efficient
scheme for face retrieval in the ciphertext domain, termed Privacy-Preserving
Preselection for Face Identification Based on Packing (PFIP). PFIP incorporates
an innovative preselection mechanism to reduce computational overhead and a
packing module to enhance the flexibility of biometric systems during the
enrollment stage. Extensive experiments conducted on the LFW and CASIA datasets
demonstrate that PFIP preserves the accuracy of the original face recognition
model, achieving a 100% hit rate while retrieving 1,000 ciphertext face
templates within 300 milliseconds. Compared to existing approaches, PFIP
achieves a nearly 50x improvement in retrieval efficiency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.03033v1">Preserving Privacy, Increasing Accessibility, and Reducing Cost: An
  On-Device Artificial Intelligence Model for Medical Transcription and Note
  Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-03T01:51:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Johnson Thomas, Ayush Mudgal, Wendao Liu, Nisten Tahiraj, Zeeshaan Mohammed, Dhruv Diddi</p>
    <p><b>Summary:</b> Background: Clinical documentation represents a significant burden for
healthcare providers, with physicians spending up to 2 hours daily on
administrative tasks. Recent advances in large language models (LLMs) offer
promising solutions, but privacy concerns and computational requirements limit
their adoption in healthcare settings. Objective: To develop and evaluate a
privacy-preserving, on-device medical transcription system using a fine-tuned
Llama 3.2 1B model capable of generating structured medical notes from medical
transcriptions while maintaining complete data sovereignty entirely in the
browser. Methods: We fine-tuned a Llama 3.2 1B model using Parameter-Efficient
Fine-Tuning (PEFT) with LoRA on 1,500 synthetic medical
transcription-to-structured note pairs. The model was evaluated against the
base Llama 3.2 1B on two datasets: 100 endocrinology transcripts and 140
modified ACI benchmark cases. Evaluation employed both statistical metrics
(ROUGE, BERTScore, BLEURT) and LLM-as-judge assessments across multiple
clinical quality dimensions. Results: The fine-tuned OnDevice model
demonstrated substantial improvements over the base model. On the ACI
benchmark, ROUGE-1 scores increased from 0.346 to 0.496, while BERTScore F1
improved from 0.832 to 0.866. Clinical quality assessments showed marked
reduction in major hallucinations (from 85 to 35 cases) and enhanced factual
correctness (2.81 to 3.54 on 5-point scale). Similar improvements were observed
on the internal evaluation dataset, with composite scores increasing from 3.13
to 4.43 (+41.5%). Conclusions: Fine-tuning compact LLMs for medical
transcription yields clinically meaningful improvements while enabling complete
on-device browser deployment. This approach addresses key barriers to AI
adoption in healthcare: privacy preservation, cost reduction, and accessibility
for resource-constrained environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.01808v1">Empowering Manufacturers with Privacy-Preserving AI Tools: A Case Study
  in Privacy-Preserving Machine Learning to Solve Real-World Problems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> 
  <p><b>Published on:</b> 2025-07-02T15:25:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaoyu Ji, Jessica Shorland, Joshua Shank, Pascal Delpe-Brice, Latanya Sweeney, Jan Allebach, Ali Shakouri</p>
    <p><b>Summary:</b> Small- and medium-sized manufacturers need innovative data tools but, because
of competition and privacy concerns, often do not want to share their
proprietary data with researchers who might be interested in helping. This
paper introduces a privacy-preserving platform by which manufacturers may
safely share their data with researchers through secure methods, so that those
researchers then create innovative tools to solve the manufacturers' real-world
problems, and then provide tools that execute solutions back onto the platform
for others to use with privacy and confidentiality guarantees. We illustrate
this problem through a particular use case which addresses an important problem
in the large-scale manufacturing of food crystals, which is that quality
control relies on image analysis tools. Previous to our research, food crystals
in the images were manually counted, which required substantial and
time-consuming human efforts, but we have developed and deployed a crystal
analysis tool which makes this process both more rapid and accurate. The tool
enables automatic characterization of the crystal size distribution and numbers
from microscope images while the natural imperfections from the sample
preparation are automatically removed; a machine learning model to count high
resolution translucent crystals and agglomeration of crystals was also
developed to aid in these efforts. The resulting algorithm was then packaged
for real-world use on the factory floor via a web-based app secured through the
originating privacy-preserving platform, allowing manufacturers to use it while
keeping their proprietary data secure. After demonstrating this full process,
future directions are also explored.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.01752v1">Tuning without Peeking: Provable Privacy and Generalization Bounds for
  LLM Post-Training</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-02T14:29:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ismail Labiad, Mathurin Videau, Matthieu Kowalski, Marc Schoenauer, Alessandro Leite, Julia Kempe, Olivier Teytaud</p>
    <p><b>Summary:</b> Gradient-based optimization is the workhorse of deep learning, offering
efficient and scalable training via backpropagation. However, its reliance on
large volumes of labeled data raises privacy and security concerns such as
susceptibility to data poisoning attacks and the risk of overfitting. In
contrast, black box optimization methods, which treat the model as an opaque
function, relying solely on function evaluations to guide optimization, offer a
promising alternative in scenarios where data access is restricted, adversarial
risks are high, or overfitting is a concern. However, black box methods also
pose significant challenges, including poor scalability to high-dimensional
parameter spaces, as prevalent in large language models (LLMs), and high
computational costs due to reliance on numerous model evaluations. This paper
introduces BBoxER, an evolutionary black-box method for LLM post-training that
induces an information bottleneck via implicit compression of the training
data. Leveraging the tractability of information flow, we provide strong
theoretical bounds on generalization, differential privacy, susceptibility to
data poisoning attacks, and robustness to extraction attacks. BBoxER operates
on top of pre-trained LLMs, offering a lightweight and modular enhancement
suitable for deployment in restricted or privacy-sensitive environments, in
addition to non-vacuous generalization guarantees. In experiments with LLMs, we
demonstrate empirically that Retrofitting methods are able to learn, showing
how a few iterations of BBoxER improve performance and generalize well on a
benchmark of reasoning datasets. This positions BBoxER as an attractive add-on
on top of gradient-based optimization.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.01581v1">A Privacy-Preserving Indoor Localization System based on Hierarchical
  Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2025-07-02T10:53:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Masood Jan, Wafa Njima, Xun Zhang</p>
    <p><b>Summary:</b> Location information serves as the fundamental element for numerous Internet
of Things (IoT) applications. Traditional indoor localization techniques often
produce significant errors and raise privacy concerns due to centralized data
collection. In response, Machine Learning (ML) techniques offer promising
solutions by capturing indoor environment variations. However, they typically
require central data aggregation, leading to privacy, bandwidth, and server
reliability issues. To overcome these challenges, in this paper, we propose a
Federated Learning (FL)-based approach for dynamic indoor localization using a
Deep Neural Network (DNN) model. Experimental results show that FL has the
nearby performance to Centralized Model (CL) while keeping the data privacy,
bandwidth efficiency and server reliability. This research demonstrates that
our proposed FL approach provides a viable solution for privacy-enhanced indoor
localization, paving the way for advancements in secure and efficient indoor
localization systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.01487v1">How to Securely Shuffle? A survey about Secure Shufflers for
  privacy-preserving computations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-07-02T08:48:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marc Damie, Florian Hahn, Andreas Peter, Jan Ramon</p>
    <p><b>Summary:</b> Ishai et al. (FOCS'06) introduced secure shuffling as an efficient building
block for private data aggregation. Recently, the field of differential privacy
has revived interest in secure shufflers by highlighting the privacy
amplification they can provide in various computations. Although several works
argue for the utility of secure shufflers, they often treat them as black
boxes; overlooking the practical vulnerabilities and performance trade-offs of
existing implementations. This leaves a central question open: what makes a
good secure shuffler?
  This survey addresses that question by identifying, categorizing, and
comparing 26 secure protocols that realize the necessary shuffling
functionality. To enable a meaningful comparison, we adapt and unify existing
security definitions into a consistent set of properties. We also present an
overview of privacy-preserving technologies that rely on secure shufflers,
offer practical guidelines for selecting appropriate protocols, and outline
promising directions for future work.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.01216v1">PAE MobiLLM: Privacy-Aware and Efficient LLM Fine-Tuning on the Mobile
  Device via Additive Side-Tuning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-01T22:27:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xingke Yang, Liang Li, Zhiyi Wan, Sicong Li, Hao Wang, Xiaoqi Qi, Jiang Liu, Tomoaki Ohtsuki, Xin Fu, Miao Pan</p>
    <p><b>Summary:</b> There is a huge gap between numerous intriguing applications fostered by
on-device large language model (LLM) fine-tuning (FT) from fresh mobile data
and the limited resources of a mobile device. While existing server-assisted
methods (e.g., split learning or side-tuning) may enable LLM FT on the local
mobile device, they suffer from heavy communication burdens of activation
transmissions, and may disclose data, labels or fine-tuned models to the
server. To address those issues, we develop PAE MobiLLM, a privacy-aware and
efficient LLM FT method which can be deployed on the mobile device via
server-assisted additive side-tuning. To further accelerate FT convergence and
improve computing efficiency, PAE MobiLLM integrates activation caching on the
server side, which allows the server to reuse historical activations and saves
the mobile device from repeatedly computing forward passes for the recurring
data samples. Besides, to reduce communication cost, PAE MobiLLM develops a
one-token (i.e., ``pivot'' token) activation shortcut that transmits only a
single activation dimension instead of full activation matrices to guide the
side network tuning. Last but not least, PAE MobiLLM introduces the additive
adapter side-network design which makes the server train the adapter modules
based on device-defined prediction differences rather than raw ground-truth
labels. In this way, the server can only assist device-defined side-network
computing, and learn nothing about data, labels or fine-tuned models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.00920v2">Privacy-Preserving Quantized Federated Learning with Diverse Precision</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2025-07-01T16:26:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dang Qua Nguyen, Morteza Hashemi, Erik Perrins, Sergiy A. Vorobyov, David J. Love, Taejoon Kim</p>
    <p><b>Summary:</b> Federated learning (FL) has emerged as a promising paradigm for distributed
machine learning, enabling collaborative training of a global model across
multiple local devices without requiring them to share raw data. Despite its
advancements, FL is limited by factors such as: (i) privacy risks arising from
the unprotected transmission of local model updates to the fusion center (FC)
and (ii) decreased learning utility caused by heterogeneity in model
quantization resolution across participating devices. Prior work typically
addresses only one of these challenges because maintaining learning utility
under both privacy risks and quantization heterogeneity is a non-trivial task.
In this paper, our aim is therefore to improve the learning utility of a
privacy-preserving FL that allows clusters of devices with different
quantization resolutions to participate in each FL round. Specifically, we
introduce a novel stochastic quantizer (SQ) that is designed to simultaneously
achieve differential privacy (DP) and minimum quantization error. Notably, the
proposed SQ guarantees bounded distortion, unlike other DP approaches. To
address quantization heterogeneity, we introduce a cluster size optimization
technique combined with a linear fusion approach to enhance model aggregation
accuracy. Numerical simulations validate the benefits of our approach in terms
of privacy protection and learning utility compared to the conventional
LaplaceSQ-FL algorithm.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.00596v1">Gaze3P: Gaze-Based Prediction of User-Perceived Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-01T09:26:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mayar Elfares, Pascal Reisert, Ralf Küsters, Andreas Bulling</p>
    <p><b>Summary:</b> Privacy is a highly subjective concept and perceived variably by different
individuals. Previous research on quantifying user-perceived privacy has
primarily relied on questionnaires. Furthermore, applying user-perceived
privacy to optimise the parameters of privacy-preserving techniques (PPT)
remains insufficiently explored. To address these limitations, we introduce
Gaze3P -- the first dataset specifically designed to facilitate systematic
investigations into user-perceived privacy. Our dataset comprises gaze data
from 100 participants and 1,000 stimuli, encompassing a range of private and
safe attributes. With Gaze3P, we train a machine learning model to implicitly
and dynamically predict perceived privacy from human eye gaze. Through
comprehensive experiments, we show that the resulting models achieve high
accuracy. Finally, we illustrate how predicted privacy can be used to optimise
the parameters of differentially private mechanisms, thereby enhancing their
alignment with user expectations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.00402v1">GRAND: Graph Release with Assured Node Differential Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">  
  <p><b>Published on:</b> 2025-07-01T03:39:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Suqing Liu, Xuan Bi, Tianxi Li</p>
    <p><b>Summary:</b> Differential privacy is a well-established framework for safeguarding
sensitive information in data. While extensively applied across various
domains, its application to network data -- particularly at the node level --
remains underexplored. Existing methods for node-level privacy either focus
exclusively on query-based approaches, which restrict output to pre-specified
network statistics, or fail to preserve key structural properties of the
network. In this work, we propose GRAND (Graph Release with Assured Node
Differential privacy), which is, to the best of our knowledge, the first
network release mechanism that releases entire networks while ensuring
node-level differential privacy and preserving structural properties. Under a
broad class of latent space models, we show that the released network
asymptotically follows the same distribution as the original network. The
effectiveness of the approach is evaluated through extensive experiments on
both synthetic and real-world datasets.</p>
  </details>
</div>



<h2>2025-06</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.00286v2">"Before, I Asked My Mom, Now I Ask ChatGPT": Visual Privacy Management
  with Generative AI for Blind and Low-Vision People</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2025-06-30T21:55:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tanusree Sharma, Yu-Yun Tseng, Lotus Zhang, Ayae Ide, Kelly Avery Mack, Leah Findlater, Danna Gurari, Yang Wang</p>
    <p><b>Summary:</b> Blind and low vision (BLV) individuals use Generative AI (GenAI) tools to
interpret and manage visual content in their daily lives. While such tools can
enhance the accessibility of visual content and so enable greater user
independence, they also introduce complex challenges around visual privacy. In
this paper, we investigate the current practices and future design preferences
of blind and low vision individuals through an interview study with 21
participants. Our findings reveal a range of current practices with GenAI that
balance privacy, efficiency, and emotional agency, with users accounting for
privacy risks across six key scenarios, such as self-presentation,
indoor/outdoor spatial privacy, social sharing, and handling professional
content. Our findings reveal design preferences, including on-device
processing, zero-retention guarantees, sensitive content redaction,
privacy-aware appearance indicators, and multimodal tactile mirrored
interaction methods. We conclude with actionable design recommendations to
support user-centered visual privacy through GenAI, expanding the notion of
privacy and responsible handling of others data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.00230v2">PPFL-RDSN: Privacy-Preserving Federated Learning-based Residual Dense
  Spatial Networks for Encrypted Lossy Image Reconstruction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-30T19:54:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Peilin He, James Joshi</p>
    <p><b>Summary:</b> Reconstructing high-quality images from low-resolution inputs using Residual
Dense Spatial Networks (RDSNs) is crucial yet challenging, particularly in
collaborative scenarios where centralized training poses significant privacy
risks, including data leakage and inference attacks, as well as high
computational costs. We propose a novel Privacy-Preserving Federated
Learning-based RDSN (PPFL-RDSN) framework specifically tailored for lossy image
reconstruction. PPFL-RDSN integrates Federated Learning (FL), local
differential privacy, and robust model watermarking techniques, ensuring data
remains secure on local devices, safeguarding sensitive information, and
maintaining model authenticity without revealing underlying data. Empirical
evaluations show that PPFL-RDSN achieves comparable performance to the
state-of-the-art centralized methods while reducing computational burdens, and
effectively mitigates security and privacy vulnerabilities, making it a
practical solution for secure and privacy-preserving collaborative computer
vision applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.02974v1">InvisibleInk: High-Utility and Low-Cost Text Generation with
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-30T18:00:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vishnu Vinod, Krishna Pillutla, Abhradeep Guha Thakurta</p>
    <p><b>Summary:</b> As major progress in LLM-based long-form text generation enables paradigms
such as retrieval-augmented generation (RAG) and inference-time scaling, safely
incorporating private information into the generation remains a critical open
question. We present InvisibleInk, a highly scalable long-form text generation
framework satisfying rigorous differential privacy guarantees with respect to
the sensitive references. It interprets sampling from the LLM's
next-token-distribution as the exponential mechanism over the LLM logits with
two innovations. First, we reduce the privacy cost by isolating and clipping
only the sensitive information in the model logits (relative to the public
logits). Second, we improve text quality by sampling from a small superset of
the top-$k$ private tokens. Empirical evaluations demonstrate a consistent
$8\times$ reduction in computation cost over state-of-the-art baselines to
generate long-form private text of the same utility across privacy levels. In
summary, InvisibleInk is able to generate private long-form text at less than
$10\times$ the computation cost of non-private generation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.24033v1">Poisoning Attacks to Local Differential Privacy for Ranking Estimation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-30T16:39:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pei Zhan, Peng Tang, Yangzhuo Li, Puwen Wei, Shanqing Guo</p>
    <p><b>Summary:</b> Local differential privacy (LDP) involves users perturbing their inputs to
provide plausible deniability of their data. However, this also makes LDP
vulnerable to poisoning attacks. In this paper, we first introduce novel
poisoning attacks for ranking estimation. These attacks are intricate, as fake
attackers do not merely adjust the frequency of target items. Instead, they
leverage a limited number of fake users to precisely modify frequencies,
effectively altering item rankings to maximize gains. To tackle this challenge,
we introduce the concepts of attack cost and optimal attack item (set), and
propose corresponding strategies for kRR, OUE, and OLH protocols. For kRR, we
iteratively select optimal attack items and allocate suitable fake users. For
OUE, we iteratively determine optimal attack item sets and consider the
incremental changes in item frequencies across different sets. Regarding OLH,
we develop a harmonic cost function based on the pre-image of a hash to select
that supporting a larger number of effective attack items. Lastly, we present
an attack strategy based on confidence levels to quantify the probability of a
successful attack and the number of attack iterations more precisely. We
demonstrate the effectiveness of our attacks through theoretical and empirical
evidence, highlighting the necessity for defenses against these attacks. The
source code and data have been made available at
https://github.com/LDP-user/LDP-Ranking.git.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.02968v1">Unveiling Privacy Policy Complexity: An Exploratory Study Using Graph
  Mining, Machine Learning, and Natural Language Processing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-06-30T14:55:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vijayalakshmi Ramasamy, Seth Barrett, Gokila Dorai, Jessica Zumbach</p>
    <p><b>Summary:</b> Privacy policy documents are often lengthy, complex, and difficult for
non-expert users to interpret, leading to a lack of transparency regarding the
collection, processing, and sharing of personal data. As concerns over online
privacy grow, it is essential to develop automated tools capable of analyzing
privacy policies and identifying potential risks. In this study, we explore the
potential of interactive graph visualizations to enhance user understanding of
privacy policies by representing policy terms as structured graph models. This
approach makes complex relationships more accessible and enables users to make
informed decisions about their personal data (RQ1). We also employ graph mining
algorithms to identify key themes, such as User Activity and Device
Information, using dimensionality reduction techniques like t-SNE and PCA to
assess clustering effectiveness. Our findings reveal that graph-based
clustering improves policy content interpretability. It highlights patterns in
user tracking and data sharing, which supports forensic investigations and
identifies regulatory non-compliance. This research advances AI-driven tools
for auditing privacy policies by integrating interactive visualizations with
graph mining. Enhanced transparency fosters accountability and trust.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.23866v3">Exploring Privacy and Security as Drivers for Environmental
  Sustainability in Cloud-Based Office Solutions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-06-30T13:58:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jason Kayembe, Iness Ben Guirat, Jan Tobias Mühlberg</p>
    <p><b>Summary:</b> In this paper, we explore the intersection of privacy, security, and
environmental sustainability in cloud-based office solutions, focusing on
quantifying user- and network-side energy use and associated carbon emissions.
We hypothesise that privacy-focused services are typically more
energy-efficient than those funded through data collection and advertising. To
evaluate this, we propose a framework that systematically measures
environmental costs based on energy usage and network data traffic during
well-defined, automated usage scenarios. To test our hypothesis, we first
analyse how underlying architectures and business models, such as monetisation
through personalised advertising, contribute to the environmental footprint of
these services. We then explore existing methodologies and tools for software
environmental impact assessment. We apply our framework to three mainstream
email services selected to reflect different privacy policies, from
ad-supported tracking-intensive models to privacy-focused designs: Microsoft
Outlook, Google Mail (Gmail), and Proton Mail. We extend this comparison to a
self-hosted email solution, evaluated with and without end-to-end encryption.
We show that the self-hosted solution, even with 14% of device energy and 15%
of emissions overheads from PGP encryption, remains the most energy-efficient,
saving up to 33% of emissions per session compared to Gmail. Among commercial
providers, Proton Mail is the most efficient, saving up to 0.1 gCO2 e per
session compared to Outlook, whose emissions can be further reduced by 2%
through ad-blocking.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.23622v1">Privacy-Preserving Federated Learning Scheme with Mitigating Model
  Poisoning Attacks: Vulnerabilities and Countermeasures</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-30T08:39:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiahui Wu, Fucai Luo, Tiecheng Sun, Haiyan Wang, Weizhe Zhang</p>
    <p><b>Summary:</b> The privacy-preserving federated learning schemes based on the setting of two
honest-but-curious and non-colluding servers offer promising solutions in terms
of security and efficiency. However, our investigation reveals that these
schemes still suffer from privacy leakage when considering model poisoning
attacks from malicious users. Specifically, we demonstrate that the
privacy-preserving computation process for defending against model poisoning
attacks inadvertently leaks privacy to one of the honest-but-curious servers,
enabling it to access users' gradients in plaintext. To address both privacy
leakage and model poisoning attacks, we propose an enhanced privacy-preserving
and Byzantine-robust federated learning (PBFL) scheme, comprising three
components: (1) a two-trapdoor fully homomorphic encryption (FHE) scheme to
bolster users' privacy protection; (2) a novel secure normalization judgment
method to preemptively thwart gradient poisoning; and (3) an innovative secure
cosine similarity measurement method for detecting model poisoning attacks
without compromising data privacy. Our scheme guarantees privacy preservation
and resilience against model poisoning attacks, even in scenarios with
heterogeneous, non-IID (Independently and Identically Distributed) datasets.
Theoretical analyses substantiate the security and efficiency of our scheme,
and extensive experiments corroborate the efficacy of our private attacks.
Furthermore, the experimental results demonstrate that our scheme accelerates
training speed while reducing communication overhead compared to the
state-of-the-art PBFL schemes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.23603v2">SoK: Semantic Privacy in Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-06-30T08:08:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Baihe Ma, Yanna Jiang, Xu Wang, Guangsheng Yu, Qin Wang, Caijun Sun, Chen Li, Xuelei Qi, Ying He, Wei Ni, Ren Ping Liu</p>
    <p><b>Summary:</b> As Large Language Models (LLMs) are increasingly deployed in sensitive
domains, traditional data privacy measures prove inadequate for protecting
information that is implicit, contextual, or inferable - what we define as
semantic privacy. This Systematization of Knowledge (SoK) introduces a
lifecycle-centric framework to analyze how semantic privacy risks emerge across
input processing, pretraining, fine-tuning, and alignment stages of LLMs. We
categorize key attack vectors and assess how current defenses, such as
differential privacy, embedding encryption, edge computing, and unlearning,
address these threats. Our analysis reveals critical gaps in semantic-level
protection, especially against contextual inference and latent representation
leakage. We conclude by outlining open challenges, including quantifying
semantic leakage, protecting multimodal inputs, balancing de-identification
with generation quality, and ensuring transparency in privacy enforcement. This
work aims to inform future research on designing robust, semantically aware
privacy-preserving techniques for LLMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.23583v1">Detect \& Score: Privacy-Preserving Misbehaviour Detection and
  Contribution Evaluation in Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-30T07:40:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marvin Xhemrishi, Alexandre Graell i Amat, Balázs Pejó</p>
    <p><b>Summary:</b> Federated learning with secure aggregation enables private and collaborative
learning from decentralised data without leaking sensitive client information.
However, secure aggregation also complicates the detection of malicious client
behaviour and the evaluation of individual client contributions to the
learning. To address these challenges, QI (Pejo et al.) and FedGT (Xhemrishi et
al.) were proposed for contribution evaluation (CE) and misbehaviour detection
(MD), respectively. QI, however, lacks adequate MD accuracy due to its reliance
on the random selection of clients in each training round, while FedGT lacks
the CE ability. In this work, we combine the strengths of QI and FedGT to
achieve both robust MD and accurate CE. Our experiments demonstrate superior
performance compared to using either method independently.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.23481v1">Evaluation of Geolocation Capabilities of Multimodal Large Language
  Models and Analysis of Associated Privacy Risks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> 
  <p><b>Published on:</b> 2025-06-30T03:05:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xian Zhang, Xiang Cheng</p>
    <p><b>Summary:</b> Objectives: The rapid advancement of Multimodal Large Language Models (MLLMs)
has significantly enhanced their reasoning capabilities, enabling a wide range
of intelligent applications. However, these advancements also raise critical
concerns regarding privacy and ethics. MLLMs are now capable of inferring the
geographic location of images -- such as those shared on social media or
captured from street views -- based solely on visual content, thereby posing
serious risks of privacy invasion, including doxxing, surveillance, and other
security threats.
  Methods: This study provides a comprehensive analysis of existing geolocation
techniques based on MLLMs. It systematically reviews relevant litera-ture and
evaluates the performance of state-of-the-art visual reasoning models on
geolocation tasks, particularly in identifying the origins of street view
imagery.
  Results: Empirical evaluation reveals that the most advanced visual large
models can successfully localize the origin of street-level imagery with up to
$49\%$ accuracy within a 1-kilometer radius. This performance underscores the
models' powerful capacity to extract and utilize fine-grained geographic cues
from visual data.
  Conclusions: Building on these findings, the study identifies key visual
elements that contribute to suc-cessful geolocation, such as text,
architectural styles, and environmental features. Furthermore, it discusses the
potential privacy implications associated with MLLM-enabled geolocation and
discuss several technical and policy-based coun-termeasures to mitigate
associated risks. Our code and dataset are available at
https://github.com/zxyl1003/MLLM-Geolocation-Evaluation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.23014v1">Generating Privacy Stories From Software Documentation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-06-28T20:55:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wilder Baldwin, Shashank Chintakuntla, Shreyah Parajuli, Ali Pourghasemi, Ryan Shanz, Sepideh Ghanavati</p>
    <p><b>Summary:</b> Research shows that analysts and developers consider privacy as a security
concept or as an afterthought, which may lead to non-compliance and violation
of users' privacy. Most current approaches, however, focus on extracting legal
requirements from the regulations and evaluating the compliance of software and
processes with them. In this paper, we develop a novel approach based on
chain-of-thought prompting (CoT), in-context-learning (ICL), and Large Language
Models (LLMs) to extract privacy behaviors from various software documents
prior to and during software development, and then generate privacy
requirements in the format of user stories. Our results show that most commonly
used LLMs, such as GPT-4o and Llama 3, can identify privacy behaviors and
generate privacy user stories with F1 scores exceeding 0.8. We also show that
the performance of these models could be improved through parameter-tuning. Our
findings provide insight into using and optimizing LLMs for generating privacy
requirements given software documents created prior to or throughout the
software development lifecycle.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.22789v1">WavShape: Information-Theoretic Speech Representation Learning for Fair
  and Privacy-Aware Audio Processing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> 
  <p><b>Published on:</b> 2025-06-28T07:03:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Oguzhan Baser, Ahmet Ege Tanriverdi, Kaan Kale, Sandeep P. Chinchali, Sriram Vishwanath</p>
    <p><b>Summary:</b> Speech embeddings often retain sensitive attributes such as speaker identity,
accent, or demographic information, posing risks in biased model training and
privacy leakage. We propose WavShape, an information-theoretic speech
representation learning framework that optimizes embeddings for fairness and
privacy while preserving task-relevant information. We leverage mutual
information (MI) estimation using the Donsker-Varadhan formulation to guide an
MI-based encoder that systematically filters sensitive attributes while
maintaining speech content essential for downstream tasks. Experimental results
on three known datasets show that WavShape reduces MI between embeddings and
sensitive attributes by up to 81% while retaining 97% of task-relevant
information. By integrating information theory with self-supervised speech
models, this work advances the development of fair, privacy-aware, and
resource-efficient speech systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.22787v1">What's Privacy Good for? Measuring Privacy as a Shield from Harms due to
  Personal Data Use</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-06-28T07:00:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sri Harsha Gajavalli, Junichi Koizumi, Rakibul Hasan</p>
    <p><b>Summary:</b> We propose a harm-centric conceptualization of privacy that asks: What harms
from personal data use can privacy prevent? The motivation behind this research
is limitations in existing privacy frameworks (e.g., Contextual Integrity) to
capture or categorize many of the harms that arise from modern technology's use
of personal data. We operationalize this conceptualization in an online study
with 400 college and university students. Study participants indicated their
perceptions of different harms (e.g., manipulation, discrimination, and
harassment) that may arise when artificial intelligence-based algorithms infer
personal data (e.g., demographics, personality traits, and cognitive
disability) and use it to identify students who are likely to drop out of a
course or the best job candidate. The study includes 14 harms and six types of
personal data selected based on an extensive literature review.
  Comprehensive statistical analyses of the study data show that the 14 harms
are internally consistent and collectively represent a general notion of
privacy harms. The study data also surfaces nuanced perceptions of harms, both
across the contexts and participants' demographic factors. Based on these
results, we discuss how privacy can be improved equitably. Thus, this research
not only contributes to enhancing the understanding of privacy as a concept but
also provides practical guidance to improve privacy in the context of education
and employment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.22752v1">Privacy-Preserving Methods for Bug Severity Prediction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-06-28T04:40:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Havvanur Dervişoğlu, Ruşen Halepmollası, Elif Eyvaz</p>
    <p><b>Summary:</b> Bug severity prediction is a critical task in software engineering as it
enables more efficient resource allocation and prioritization in software
maintenance. While AI-based analyses and models significantly require access to
extensive datasets, industrial applications face challenges due to data-sharing
constraints and the limited availability of labeled data. In this study, we
investigate method-level bug severity prediction using source code metrics and
Large Language Models (LLMs) with two widely used datasets. We compare the
performance of models trained using centralized learning, federated learning,
and synthetic data generation. Our experimental results, obtained using two
widely recognized software defect datasets, indicate that models trained with
federated learning and synthetic data achieve comparable results to centrally
trained models without data sharing. Our finding highlights the potential of
privacy-preserving approaches such as federated learning and synthetic data
generation to enable effective bug severity prediction in industrial context
where data sharing is a major challenge.
  The source code and dataset are available at our GitHub repository:
https://github.com/drvshavva/EASE2025-Privacy-Preserving-Methods-for-Bug-Severity-Prediction.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.22727v1">Convergent Privacy Framework with Contractive GNN Layers for Multi-hop
  Aggregations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-28T02:17:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yu Zheng, Chenang Li, Zhou Li, Qingsong Wang</p>
    <p><b>Summary:</b> Differential privacy (DP) has been integrated into graph neural networks
(GNNs) to protect sensitive structural information, e.g., edges, nodes, and
associated features across various applications. A common approach is to
perturb the message-passing process, which forms the core of most GNN
architectures. However, existing methods typically incur a privacy cost that
grows linearly with the number of layers (Usenix Security'23), ultimately
requiring excessive noise to maintain a reasonable privacy level. This
limitation becomes particularly problematic when deep GNNs are necessary to
capture complex and long-range interactions in graphs. In this paper, we
theoretically establish that the privacy budget can converge with respect to
the number of layers by applying privacy amplification techniques to the
message-passing process, exploiting the contractive properties inherent to
standard GNN operations. Motivated by this analysis, we propose a simple yet
effective Contractive Graph Layer (CGL) that ensures the contractiveness
required for theoretical guarantees while preserving model utility. Our
framework, CARIBOU, supports both training and inference, equipped with a
contractive aggregation module, a privacy allocation module, and a privacy
auditing module. Experimental evaluations demonstrate that CARIBOU
significantly improves the privacy-utility trade-off and achieves superior
performance in privacy auditing tasks.</p>
  </details>
</div>

