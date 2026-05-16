
<h2>2026-05</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.14591v1">Privacy Auditing with Zero (0) Training Run</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-14T09:00:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tudor Cebere, Mathieu Even, Linus Bleistein, Aurélien Bellet</p>
    <p><b>Summary:</b> Privacy auditing provides empirical lower bounds on the differential privacy parameters of learning algorithms. Existing methods, however, require interventional access to the training pipeline, either to retrain multiple times or to randomize data inclusion. This is often infeasible for large deployed systems such as foundation models. We introduce Zero-Run privacy auditing, a post-hoc framework for auditing models using two fixed datasets: examples known to be training-set members and examples known to be non-members. In this observational regime, membership is no longer randomized; instead, member and non-member data often differ in distribution, so membership inference scores may reflect a distribution shift rather than algorithmic leakage. Drawing on ideas from causal inference, we formalize this confounding effect and propose two complementary corrections that yield valid privacy audits. Our first approach models the combined effect of distribution shift and algorithmic leakage as an adaptive composition, producing conservative global corrections. Our second approach conditions on observed data and adjusts pointwise membership guesses, yielding sharper instance-dependent bounds. Experiments on synthetic data and large-scale models show that Zero-Run auditing enables practical privacy evaluation when retraining or controlled data insertion is infeasible.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.14289v1">MetaMoE: Diversity-Aware Proxy Selection for Privacy-Preserving Mixture-of-Experts Unification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-14T02:48:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Weisen Jiang, Shuhao Chen, Sinno Jialin Pan</p>
    <p><b>Summary:</b> Mixture-of-Experts (MoE) models scale capacity by combining specialized experts, but most existing approaches assume centralized access to training data. In practice, data are distributed across clients and cannot be shared due to privacy constraints, making unified MoE training challenging. We propose MetaMoE, a privacy-preserving framework that unifies independently trained, domain-specialized experts into a single MoE using public proxy data as surrogates for inaccessible private data. Central to MetaMoE is diversity-aware proxy selection, which selects client-domain-relevant and diverse samples from public data to effectively approximate private data distributions and supervise router learning. These proxies are further used to align expert training, improving expert coordination at unification time, while a context-aware router enhances expert selection across heterogeneous inputs. Experiments on computer vision and natural language processing benchmarks demonstrate that MetaMoE consistently outperforms recent privacy-preserving MoE unification methods. Code is available at https://github.com/ws-jiang/MetaMoE.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.14123v1">Keyed Nonlinear Transform: Lightweight Privacy-Enhancing Feature Sharing for Medical Image Analysis</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-05-13T21:17:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haebom Lee, Gyeongjung Kim</p>
    <p><b>Summary:</b> Feature sharing via split inference offers a lightweight alternative to federated learning for resource-constrained hospitals, but transmitted features still leak patient identity information and lack practical mechanisms for controlled feature sharing. We propose Keyed Nonlinear Transform (KNT), a drop-in feature transformation that applies key-conditioned obfuscation to intermediate representations. KNT reduces re-identification AUC from 0.635 to 0.586, corresponding to a 36% reduction in above-chance identity signal, while introducing only 0.15 ms CPU overhead, without backbone retraining, and preserving classification performance within 1.0 pp. Our analysis shows that KNT's nonlinear transform prevents closed-form inversion and shifts recovery to iterative gradient-based optimization under full key compromise, substantially increasing inversion difficulty. The same transform generalizes to dense prediction tasks, incurring only a 4.4 pp Dice reduction on skin-lesion segmentation without retraining. These results position KNT as a practical and efficient privacy layer for split inference deployments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.14119v1">Privacy Preserving Multi Agent Path Finding</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2026-05-13T21:08:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rotem Lev Lehman, Roni Stern, Guy Shani</p>
    <p><b>Summary:</b> In the multi-agent path finding (MAPF) problem, a group of agents search in a graph for a path for each agent where no two paths collide. While in all applications of MAPF the agents must not collide with each other, in some of them the agents may not wish to share their paths due to privacy constraints. In this work, we formulate two types of privacy constraints for MAPF and propose algorithms that preserve them. The first type of privacy we consider is planning-level privacy, which means that during planning, the agents cannot identify exactly the planned location of the other agents. We propose a general framework for obtaining planning-level privacy, which works by adding mock agents to the planning process. The second type of privacy we consider is execution-level privacy, which is relevant when agents have limited sensing capabilities. Execution-level privacy is preserved if none of the agents is allowed to sense the location of the other agents during execution. We show how to adapt two popular MAPF algorithms, namely PIBT and LaCAM, such that they preserve execution-level privacy. Lastly, we propose a post-processing technique that allows the agents to reduce the sum of costs of the returned solution without losing any privacy. We also implemented our algorithms and evaluated them empirically, showing that the proposed post-processing technique indeed improved cost significantly.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.14113v1">ProtoMedAgent: Multimodal Clinical Interpretability via Privacy-Aware Agentic Workflows</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2026-05-13T20:57:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alvaro Lopez Pellicer, Plamen Angelov, Marwan Bukhari, Yi Li, Eduardo Soares, Jemma Kerns</p>
    <p><b>Summary:</b> While interpretable prototype networks offer compelling case-based reasoning for clinical diagnostics, their raw continuous outputs lack the semantic structure required for medical documentation. Bridging this gap via standard Retrieval-Augmented Generation (RAG) routinely triggers ``retrieval sycophancy,'' where Large Language Models (LLMs) hallucinate post-hoc rationalizations to align with visual predictions. We introduce ProtoMedAgent, a framework that formalizes multimodal clinical reporting as an iterative, zero-gradient test-time optimization problem over a strict neuro-symbolic bottleneck. Operating on a frozen prototype backbone, we distill latent visual and tabular features into a discrete semantic memory. Online generation is strictly constrained by exact set-theoretic differentials and a reflective Scribe-Critic loop, mathematically precluding unsupported narrative claims. To safely bound data disclosure, we introduce a semantic privacy gate governed by $k$-anonymity and $\ell$-diversity. Evaluated on a 4,160-patient clinical cohort, ProtoMedAgent achieves 91.2\% Comparison Set Faithfulness where it fundamentally outperforms standard RAG (46.2\%). ProtoMedAgent additionally leverages a binding $\ell$-diversity phase transition to systematically reduce artifact-level membership inference risks by an absolute 9.8\%.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.13503v1">Limits of Personalizing Differential Privacy Budgets</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-13T13:24:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Edwige Cyffers, Juba Ziani</p>
    <p><b>Summary:</b> A key technical difficulty in differential privacy is selecting a privacy budget that satisfies privacy requirements while maximizing utility. A natural and well-studied workaround is to use personalized privacy budgets, which may differ across agents. In this paper, we show that personalized budgets come with major limitations and that for mean estimation, the dominant factor is not full personalization, but rather choosing the right effective privacy budget. This can be achieved through a simple thresholding operator that we describe. Compared with this thresholding baseline, the gains obtained by fully personalized mechanisms are limited. In particular, we precisely quantify the constant-factor improvement in settings with mixed private and public datasets and in private datasets with two levels of privacy requirements. We also establish upper bounds and identify regimes of maximal gain for arbitrary privacy requirements.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.13418v1">DP-KFC: Data-Free Preconditioning for Privacy-Preserving Deep Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-13T12:14:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marc Molina Van den Bosch, Riccardo Taiello, Albert Sund Aillet, Andrea Protani, Miguel Angel Gonzalez Ballester, Luigi Serio</p>
    <p><b>Summary:</b> Differentially private optimization suffers from a fundamental geometric mismatch: deep networks have highly anisotropic loss landscapes, yet DP-SGD injects isotropic noise. Second-order preconditioning can resolve this, but estimating curvature typically requires private data (consuming privacy budget) or public data (introducing distribution shift). We show that the Fisher Information Matrix decouples into architectural sensitivity, recoverable via synthetic noise, and input correlations, approximable from modality-specific frequency statistics. We propose DP-KFC, which constructs KFAC preconditioners by probing networks with structured synthetic noise, requiring neither private nor public data. Empirically, DP-KFC consistently outperforms DP-SGD and adaptive baselines across diverse modalities in strong privacy regimes ($\varepsilon \leq 3$). DP-KFC matches private-data preconditioners while public-data variants degrade by up to $4.8\%$, showing that curvature can be estimated without consuming privacy budget or introducing distribution shift. This enables privacy-preserving learning in specialized domains (e.g., medical applications) where regulatory constraints make data scarce.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.13265v1">LightSplit: Practical Privacy-Preserving Split Learning via Orthogonal Projections</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-13T09:45:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mert Cihangiroglu, Alessandro Pegoraro, Phillip Rieger, Antonino Nocera, Ahmad-Reza Sadeghi</p>
    <p><b>Summary:</b> Split learning (SL) enables collaborative training by partitioning a neural network across clients and a central server, but the cut-layer interface introduces a key challenge: high-dimensional activations incur substantial communication overhead while exposing representations vulnerable to reconstruction attacks. Existing approaches typically address efficiency or privacy in isolation, relying on additional mechanisms such as sparsification, quantization, or noise injection. We propose LightSplit, which limits information exposure and reduces communication overhead by applying a lightweight fixed orthogonal random projection at the cut layer. Based on Shannon's information theory, this projection acts as an information bottleneck that restricts instance-specific information and suppresses exploitable per-sample signals. By transmitting low-dimensional projections instead of raw activations, the server operates on lifted representations without requiring architectural modifications, ensuring compatibility with existing SL architectures. By avoiding additional trainable components on the client, the method remains lightweight and suitable for edge devices while preserving end-to-end differentiability via exact gradient propagation. As the projection is non-invertible, part of the original representation is irreversibly discarded at the client, LightSplit reduces the information available for reconstruction and limits information exposure. We extensively evaluate LightSplit on state-of-the-art benchmarks in both IID and non-IID settings across varying projection dimensions and client scales. Our results show that the method retains more than 95% of the baseline accuracy at up to 32x reduction in transmitted dimensionality while maintaining stable training dynamics.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.12147v1">PrivacySIM: Evaluating LLM Simulation of User Privacy Behavior</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-12T14:05:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> James Flemings, Murali Annavaram</p>
    <p><b>Summary:</b> Large language models (LLMs) are increasingly used to simulate human behavior, but their ability to simulate $individual$ privacy decisions is not well understood. In this paper, we address the problem of evaluating whether a core set of user persona attributes can drive LLMs to simulate individual-level privacy behavior. We introduce PrivacySIM, an evaluation suite that benchmarks LLM simulation of user privacy behavior against the ground-truth responses of 1,000 users. These users are drawn from five published user studies on privacy spanning LLM healthcare consultations, conversational agents, and chatbots. Drawing on these user studies, we hypothesize three persona facets as plausible predictors of privacy decision-making: demographics, previous experiences, and stated privacy attitudes. We condition nine frontier LLMs on subsets of these three facets and measure how often each model's response to a data-sharing scenario matches the user's actual response. Our findings show that (1) privacy persona conditioning consistently improves simulation quality over no-persona conditioning, but even the strongest model (40.4\% accuracy) remains far from faithfully simulating individual privacy decisions. (2) A user's stated privacy attitudes alone may not be the best predictor because they often diverge from the user's actual privacy behavior. (3) Users with high AI/chatbot experience but low stated privacy attitudes are the most challenging to simulate. PrivacySIM is a first step toward understanding and improving the capabilities of LLMs to simulate user privacy decisions. We release PrivacySIM to enable further evaluation of LLM privacy simulation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.12566v1">On Privacy-Preserving Image Transmission in Low-Altitude Networks: A Swin Transformer-Based Framework with Federated Learning</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-12T09:18:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kexin Zhang, Lixin Li, Yuna Yan, Xin Zhang, Wensheng Lin, Rui Li, Dongwei Zhao, Zhu Han</p>
    <p><b>Summary:</b> The rapid development of low-altitude economy has driven the proliferation of Unmanned Aerial Vehicle (UAV) applications, including logistics, inspection, and emergency response. However, transmitting high-volume image data from UAVs to ground stations faces significant challenges due to limited bandwidth and stringent privacy requirements. To address these issues, a Semantic Communication (SC) framework based on Federated Learning (FL) is proposed for efficient and privacy-preserving image transmission. A Swin Transformer-based Semantic Communication (STSC) architecture is designed to extract multi-scale semantic features under constrained bandwidth conditions. Dedicated communication and computing nodes are deployed on UAVs to enhance real-time coverage and flexibility. Meanwhile, a FL mechanism enables global model training across distributed devices without sharing raw data, thus preserving user privacy. Simulation experiments conducted on the CIFAR-10 dataset demonstrate that the proposed STSC framework achieves at least 5.7 dB improvement in Peak Signal-to-Noise Ratio (PSNR) compared to DeepJSCC baselines, while also showing superior convergence and generalization performance. The framework effectively integrates UAV-assisted deployment with SC and privacy protection, offering a practical solution for bandwidth-constrained image transmission in low-altitude networks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.11386v1">Revisiting Privacy Preservation in Brain-Computer Interfaces: Conceptual Boundaries, Risk Pathways, and a Protection-Strength Grading Framework</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-12T01:17:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lei Sun, Xiuqing Mao, Shuai Zhang, Qingyu Zeng, Min Zhao, Jiyuan Li, Wenle Dong</p>
    <p><b>Summary:</b> Brain-computer interfaces (BCIs) are moving rapidly from laboratory research into clinical, edge, and real-world settings. Under ISO/IEC 8663:2025, a BCI is a direct communication link between central nervous system activity and external software or hardware systems. This link expands privacy risk beyond raw neural-signal leakage: neural data, derived representations, model assets, and decoded outputs can be re-associated with individuals across collection, transmission, storage, training, inference, and feedback, or used to infer information beyond what a task requires. Starting from the general BCI paradigm, this review deffnes privacy-protection boundaries, protection objects, and the relationship between user data privacy and model privacy within a shared risk pathway. It then proposes a three-dimensional framework - protection object, lifecycle stage, and dominant protection-strength level - to classify existing work into four levels of protection strength. Finally, mental privacy and neuroethical risks are treated as open issues, emphasizing that BCI privacy protection should not only obscure data but also disentangle task-irrelevant sensitive information while preserving downstream utility. Keywords: Brain-computer interface, Neural data privacy, User data privacy, Model privacy, Disentanglement of task-irrelevant sensitive information, Protection-strength grading, Neuroethical risks</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.11195v1">How Does Differential Privacy Affect Social Bias in LLMs? A Systematic Evaluation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-05-11T20:03:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Eduardo Tenorio, Karuna Bhaila, Xintao Wu</p>
    <p><b>Summary:</b> Large language models (LLMs) trained on web-scale corpora can memorize sensitive training data, posing significant privacy risks. Differential privacy (DP) has emerged as a principled framework that limits the influence of individual data points during training, yet the relationship between differential privacy and social bias in LLMs remains poorly understood. To investigate this, we present a systematic evaluation of social bias in a pretrained LLM trained with DP-SGD, comparing a DP model against non-DP baselines across four complementary paradigms: sentence scoring, text completion, tabular classification, and question answering. We find that DP reduces bias in sentence scoring tasks, where bias is measured through controlled likelihood comparisons, yet this improvement does not generalize across all tasks. Our results reveal a discrepancy between logit-level bias and output-level bias. Moreover, decreasing memorization does not necessarily reduce unfairness, underscoring the importance of multi-paradigm evaluation when assessing fairness in LLMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.10879v1">Private Information Retrieval With Arbitrary Privacy Requirements for Graph-Based Storage</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762"> 
  <p><b>Published on:</b> 2026-05-11T17:27:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohamed Nomeir, Shreya Meel, Sennur Ulukus</p>
    <p><b>Summary:</b> We reformulate the definition of privacy in the private information retrieval (PIR) problem to accommodate flexible privacy requirements. We focus on graph-replicated PIR, with a generalized privacy requirement, instead of requiring all messages to be private from all servers, during retrieval. Towards this, we define a privacy requirement set for each server, which can be an arbitrary subset of all message indices, as long as the stored message indices are in their privacy requirement set. Since both the storage and privacy requirement sets have many possibilities, we focus on two specific storage settings, namely the path and cyclic graphs. We consider several privacy settings for each of them, which are not necessarily the same, to give different examples for privacy sets. Of particular interest are the privacy sets that comprise the indices of messages stored at servers within a neighborhood range. The neighborhood range parameter allows a transition from the recently introduced local PIR [1] to the standard graph-replicated PIR. In these cases, we derive bounds on the capacity or find the exact capacity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.10872v1">Local Private Information Retrieval: A New Privacy Perspective for Graph-Based Replicated Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762"> 
  <p><b>Published on:</b> 2026-05-11T17:25:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shreya Meel, Mohamed Nomeir, Sennur Ulukus</p>
    <p><b>Summary:</b> We rethink the definition of privacy in multi-server, graph-replicated private information retrieval (PIR) systems, and introduce a novel setting where the user's privacy is governed by the servers' storage structure. In particular, while retrieving a message from a server, the user is concerned with hiding their desired message index from the server, only if the server stores the corresponding message. We coin this privacy requirement as local user privacy and the resulting PIR problem as local PIR on the graph. Our goal is to measure the gain in communication efficiency of local PIR, compared to that of canonical PIR, by establishing its capacity, i.e., the maximum number of message symbols retrieved, per downloaded symbol. To this end, we observe a remarkable gain in the local PIR capacity of graphs, that are disjoint union of distinct graphs, which is multiplicative, compared to the PIR capacity, when the individual graphs are identical. For connected graphs, we propose schemes to establish capacity lower bounds for edge-transitive and bipartite graphs, which are greater than the best-known PIR capacity bounds. Finally, we derive the exact local PIR capacity for the cyclic graph, and the path graph with an odd number of vertices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.10812v1">Democratizing Measurement of Critical Mobile Infrastructure: Security and Privacy in an Increasingly Centralized Communication Ecosystem</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-05-11T16:33:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gabriel K. Gegenhuber</p>
    <p><b>Summary:</b> Cellular networks serve as the backbone of global communication, providing critical access to telephony and the Internet, often in regions lacking alternatives. However, the growing complexity of these networks, driven by architectural innovations (e.g., Voice over IP, eSIMs) and commercial dynamics (e.g., roaming, virtual operators, zero-rating), remains poorly understood due to the lack of open, scalable, and geographically diverse measurement tools and independent measurement studies.
  Moreover, access to mobile networks today is no longer limited to the traditional radio interface. Technologies like Voice-over-WiFi (VoWiFi) offer alternative connectivity paths via third-party Internet infrastructure, extending operator reach into environments with limited cellular coverage. At the same time, over-the-top (OTT) messaging services such as WhatsApp and Signal have become central to modern communication, accounting for a substantial share of global messaging and voice traffic while bypassing traditional operator-controlled channels entirely.
  This dissertation addresses these challenges by introducing new approaches for independent, scalable, and reproducible measurements of mobile communication systems without requiring cooperation from network or platform operators. We design, implement, and open-source measurement platforms that enable controlled experiments across cellular radio networks, operator-provided services, and OTT messaging applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.10499v2">Privacy-preserving Chunk Scheduling in a BitTorrent Implementation of Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-05-11T12:57:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Naicheng Li, Javad Dogani, Rui Wang, Kaitai Liang, Nikolaos Laoutaris</p>
    <p><b>Summary:</b> Traditional federated learning (FL) relies on a central aggregator server, which can create performance bottlenecks and privacy risks. Decentralized mix-and-forward designs remove the server, but repeated local mixing can attenuate global information under heterogeneity and expose peer-to-peer neighborhoods as a privacy attack surface. To preserve FedAvg-style aggregation semantics over updates reconstructable by the round deadline while scaling dissemination, we present FLTorrent, a BitTorrent-based dissemination layer for serverless FL with a short warm-up. Warm-up hardens within-round source unlinkability, a dissemination-layer goal orthogonal to content protections such as DP or secure aggregation, via pre-round obfuscation, randomized lags, and coordination-only non-owner-first scheduling with the tracker off the data path, before switching to vanilla BitTorrent swarming. We upper-bound the per-transfer attribution posterior by the fraction of owner chunks in a sender's eligible cover set, and derive a tighter high-probability bound that improves with early non-owner mass. A simple heuristic, GreedyFastestFirst, attains about 92% of a bandwidth-optimal max-flow upper bound, while warm-up remains a stable about 12% share of a round across 100-500 peers. Under an observation-only local adversary, FLTorrent drives attribution success close to neighborhood-level random guessing for typical nodes, improves with network size, and remains robust under collusion. In LLM-scale dissemination stress tests over 7-10 Gbps access links, FLTorrent adds only about 6-10% round-time overhead relative to BitTorrent-only. Overall, FLTorrent shows that within-round unlinkability and BitTorrent-level efficiency can co-exist with predictable, low overheads at scale.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.10404v1">Position: Life-Logging Video Streams Make the Privacy-Utility Trade-off Inevitable</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-05-11T11:42:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tianyuan Zou, Liang Yue, Yang Liu, Ya-Qin Zhang, Sijie Cheng</p>
    <p><b>Summary:</b> With the growing prevalence of always-on hardware such as smart glasses, body cameras, and home security systems, life-logging visual sensing is becoming inevitable, forming the backbone of persistent, always-on AI systems. Meanwhile, recent advances in proactive agents and world models signal a fundamental shift from episodic, prompt-driven tools to next-generation AI systems that continuously perceive and react to the physical world. Although life-logging video streams can substantially improve utility of these promising systems, they also introduce significant privacy risks by revealing sensitive information, such as behavioral patterns, emotional states, and social interactions, beyond what isolated images expose. If unresolved, these risks may undermine public trust and hinder the sustainable development of always-on AI technologies. Existing privacy protections are either attack-specific or incur substantial utility loss, and fail to consider the entire data exploitation pipeline. We therefore posit that the privacy-utility trade-off in life-logging video streams is a foundational challenge for next-generation AI systems that demands further investigation. We call for novel pipeline-aware privacy-preserving designs that jointly optimize utility and privacy for long-horizon life-logging visual data. In parallel, formal privacy leakage metrics and standardized benchmarks remain important open directions for future research.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.10229v1">VPD-100K: Towards Generalizable and Fine-grained Visual Privacy Protection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-05-11T09:06:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaobin Hu, Enpu Zuo, Lanping Hu, Kaiwen Yang, Dianshu Liao, Tianyi Zhang, Bo Yin, Yinsi Zhou, Shidong Pan, Xiaoyu Sun</p>
    <p><b>Summary:</b> Privacy protection has become a critical requirement in the era of ubiquitous visual data sharing, imposing higher demands on efficient and robust privacy detection algorithms. However, current robust detection models are severely hindered by the lack of comprehensive datasets. Existing privacy-oriented datasets often suffer from limited scale, coarse-grained annotations, and narrow domain coverage, failing to capture the intricate details of sensitive information in realworld environments. To bridge this gap, we present a large-scale, fine-grained Visual Privacy Dataset (VPD-100K), designed to facilitate generalized privacy detection. We establish a holistic taxonomy comprising four primary domains: Human Presence, On-Screen Personally Identifiable Information (PII), Physical Identifiers, and Location Indicators, containing 100,000 images annotated with 33 fine-grained classes and over 190,000 object instances. Statistical analysis reveals that our dataset features long-tailed distributions, small object scales, and high visual complexity. These characteristics make the dataset particularly valuable for demanding, unconstrained applications such as live streaming, where actors frequently face unintentional, realtime information leakage. Furthermore, we design an effective frequency-enhanced lightweight module consisting of frequency-domain attention fusion and adaptive spectral gating mechanism that breaks the limitations of spatial pixel intensity to better capture the subtle details of sensitive information. Extensive experiments conducted on both diverse image and streaming videos benchmarks consistently demonstrate the effectiveness of our VPD-100K dataset and the wellcurated frequency mechanism. The code and dataset are available at https://vpd-100k.github.io/.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.10200v1">Convex Optimization with Local Label Differential Privacy: Tight Bounds in All Privacy Regimes</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2026-05-11T08:47:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lynn Chua, Badih Ghazi, Ravi Kumar, Pasin Manurangsi, Ziteng Sun, Chiyuan Zhang</p>
    <p><b>Summary:</b> We study the problem of Stochastic Convex Optimization (SCO) under the constraint of local Label Differential Privacy (L-LDP). In this setting, the features are considered public, but the corresponding labels are sensitive and must be randomized by each user locally before being sent to an untrusted analyzer. Prior work for SCO under L-LDP (Ghazi et al., 2021) established an excess population risk bound with a \emph{linear} dependence on the size of the label space, $K$: $O\left({\frac{K}{ε\sqrt{n}}}\right)$ in the high-privacy regime ($ε\leq 1$) and $O\left({\frac{K}{e^ε \sqrt{n}}}\right)$ in the medium-privacy regime ($1 \leq ε\leq \ln K$). This left open whether this linear cost is fundamental to the L-LDP model. In this note, we resolve this question. First, we present a novel and efficient non-interactive L-LDP algorithm that achieves an excess risk of $O\left({\sqrt{\frac{K}{εn}}}\right)$ in the high-privacy regime ($ε\leq 1$) and $O\left({\sqrt{\frac{K}{e^ε n}}}\right)$ in the medium-privacy regime ($1 \leq ε\leq \ln K$). This quadratically improves the dependency on the label space size from $O(K)$ to $O(\sqrt{K})$. Second, we prove a matching information-theoretic lower bound across all privacy regimes for any sufficiently large $n$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.09921v1">Rényi Rate-Distortion-Perception-Privacy Tradeoff under Indirect Observation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-05-11T03:15:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiahui Wei, Marios Kountouris</p>
    <p><b>Summary:</b> We introduce a Rényi Rate-Distortion-Perception-Privacy (R-RDPP) framework for indirect source coding. A latent source~$S$ is correlated with a private attribute~$U$, and the encoder observes only a noisy view~$X$ such that $(S,U) - X - Y$ holds at the decoder output~$Y$. The communication cost is measured by Sibson's $α$-mutual information $\Ialp$, the privacy leakage by $\Ibeta$, the semantic distortion between $S$ and $Y$, and the realism constraint at the semantic marginal $P_S$. We characterize the scalar Gaussian RDPP tradeoff, revealing that standard privacy metrics inherently penalize legitimate semantic recovery. To resolve this, we introduce a conditional privacy measure that quantifies only the residual leakage. In addition, we refine the achievability bounds for $α> 1$ via the Poisson functional representation. By deriving the exact geometric-mixture distribution of the Poisson index, we obtain exact closed-form expressions for integer-order Rényi entropies and sharper computable bounds in regimes where the resulting expression improves the logarithmic-moment approach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.09890v1">Deep Learning under Fractional-Order Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-11T02:29:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohammad Partohaghighi, Roummel Marcia</p>
    <p><b>Summary:</b> Differentially private stochastic gradient descent (DP-SGD) is a standard approach to privacy-preserving learning based on per-example clipping, subsampling, Gaussian perturbation, and privacy accounting. Classical DP-SGD releases a noisy version of the current clipped subsampled gradient sum. We propose Fractional-Order Differentially Private Stochastic Gradient Descent (\textbf{FO-DP-SGD}), a mechanism-level extension that replaces this current-only query, before Gaussian noise is added, with a fractional recursive query combining the current clipped sum with a finite-window, power-law-weighted aggregation of previously released private sum-level outputs. This injects fractional memory into the release mechanism while preserving the standard \emph{sum-then-noise-then-divide} structure.
  Under add/remove adjacency with Poisson subsampling, the current-step sensitivity analysis shows that the only newly data-dependent term is the scaled current clipped sum. Hence, conditioned on the private history, the effective \(\ell_2\)-sensitivity is at most \(βC\), where \(C\) is the clipping threshold and \(β\in(0,1]\) controls the current-step contribution. Thus, FO-DP-SGD admits standard per-step Rényi differential privacy accounting via a Poisson-subsampled Gaussian mechanism with effective noise-to-sensitivity ratio \(σ/β\), and composes to yield overall \((\varepsilon,δ)\)-differential privacy guarantees.
  FO-DP-SGD provides a framework for studying long-memory effects in private optimization. The fractional order, memory window, and mixing coefficient govern the trade-off among current-step sensitivity, signal retention, and private-history influence. Experiments on SVHN, CIFAR-10, and CIFAR-100 show improved test accuracy and privacy--utility performance over DP-SGD and private baselines including DP-Adam, DP-IS, SA-DP-SGD, ADP-AdamW, DP-SAT, and DP-Adam-AC.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.09823v1">CalBench: Evaluating Coordination-Privacy Trade-offs in Multi-Agent LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-10T23:56:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chelsea Zou, Yiheng Yao, Selena She, Robert D. Hawkins</p>
    <p><b>Summary:</b> We introduce CalBench, a controlled evaluation environment for studying multi-agent coordination through calendar scheduling. In CalBench, N agents each manage a private calendar containing pre-existing commitments and must coordinate to schedule a stream of M incoming meetings while minimizing disruption costs. Because agents observe only their own calendars, successful scheduling requires communication across private information boundaries. Each scenario is generated with an oracle solution, enabling precise measurement of coordination quality via realized-to-optimal cost, as well as a Distributed Constraint Optimization (DCOP) baseline to provide a fair comparison under the same private-information constraints. CalBench enables precise verification of task success, communication efficiency, and fairness in the distribution of disruption costs. Our environment also studies privacy-preserving coordination by augmenting calendar entries with private semantic contexts of varying sensitivity and measuring whether agents reveal task-irrelevant private information during negotiation. Unlike multi-agent benchmarks where a single capable agent can often substitute for the group, CalBench is inherently decentralized: no agent has access to another agent's private calendar, yet agents must still reach mutually consistent decisions over shared meeting scheduling. CalBench therefore provides a practical and verifiable setting for studying coordination protocols, communication efficiency, negotiation strategies, fairness, and privacy leakage in multi-agent systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.09561v1">Sparse Discrete Laplace and Gaussian Mechanisms under Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-05-10T14:24:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Amirreza Zamani, Sajad Daei, Parastoo Sadeghi, Mikael Skoglund</p>
    <p><b>Summary:</b> We study sparse locally private channels of the form $M(y\mid x)\propto w(x,y) 1\{y\in S(x)\},$ where the admissible output set $S(x)$ is allowed to depend on the private input $x$ and is assumed to be small. Here, we consider the sparse discrete-Laplace family with kernel $w(x,y)=e^{-λd(x,y)}$ and the sparse Gaussian family with kernel $w(x,y)=e^{-d(x,y)^2/(2σ^2)}$. For both families we give exact characterizations of pure and approximate local differential privacy. For pure $\varepsilon$-local differential privacy, we show that input-dependent sparse supports are obtained when all supports coincide. For $(\varepsilon,δ)$-local differential privacy, we derive exact formulas for the privacy defect in terms of support leakage and excess privacy loss on the overlap region. We then specialize the analysis to radius-truncated sparse discrete-Laplace and radius-truncated sparse Gaussian mechanisms and obtain explicit privacy-sparsity tradeoffs in terms of the support size $s$. In particular, we show that nontrivial approximate local privacy requires a minimum support size, whereas larger supports reduce support leakage but increase distortion. For the Gaussian family, the overlap term exhibits an additional quadratic dependence on the support radius, which implies a sharper tradeoff between privacy and sparsity. These results identify the support cardinality as the intrinsic complexity parameter of the mechanism and yield an optimal design principle: choose the smallest support size that satisfies the target privacy constraint.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.09530v3">MemPrivacy: Privacy-Preserving Personalized Memory Management for Edge-Cloud Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-05-10T13:31:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yining Chen, Jihao Zhao, Bo Tang, Haofen Wang, Yue Zhang, Fei Huang, Feiyu Xiong, Zhiyu Li</p>
    <p><b>Summary:</b> As LLM-powered agents are increasingly deployed in edge-cloud environments, personalized memory has become a key enabler of long-term adaptation and user-centric interaction. However, cloud-assisted memory management exposes sensitive user information, while existing privacy protection methods typically rely on aggressive masking that removes task-relevant semantics and consequently degrades memory utility and personalization quality. To address this challenge, We propose MemPrivacy, which identifies privacy-sensitive spans on edge devices, replaces them with semantically structured type-aware placeholders for cloud-side memory processing, and restores the original values locally when needed. By decoupling privacy protection from semantic destruction, MemPrivacy minimizes sensitive data exposure while retaining the information required for effective memory formation and retrieval. We also construct MemPrivacy-Bench for systematic evaluation, a dataset covering 200 users and over 155k privacy instances, and introduce a four-level privacy taxonomy for configurable protection policies. Experiments show that MemPrivacy achieves strong performance in privacy information extraction, substantially surpassing strong general-purpose models such as GPT-5.2 and Gemini-3.1-Pro, while also reducing inference latency. Across multiple widely used memory systems, MemPrivacy limits utility loss to within 1.6%, outperforming baseline masking strategies. Overall, MemPrivacy offers an effective balance between privacy protection and personalized memory utility for edge-cloud agents, enabling secure, practical, and user-transparent deployment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.09232v1">Privacy-Preserving Distributed Learning in IoT Systems: A Unified Threat Model and Evaluation Framework</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-10T00:22:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> John Cartmell, Alexander Williams</p>
    <p><b>Summary:</b> The increasing deployment of Internet-of-Things (IoT) devices has accelerated the use of distributed learning frameworks, where data remains local while model updates are shared across decentralized systems. Although this reduces centralized data collection, it introduces privacy risks through the exchange of gradients, model parameters, and intermediate representations. A variety of privacy-preserving techniques have been proposed to address these risks, including differential privacy, cryptographic methods, and lightweight system-level approaches. However, existing surveys often evaluate these methods in isolation and lack a unified framework for comparing their effectiveness under realistic attack models and IoT resource constraints.
  This paper presents a structured analysis of privacy-preserving techniques for distributed learning in IoT environments. A unified threat model is introduced that captures model inversion, membership inference, gradient leakage, and communication-based attacks. Building on this model, an evaluation framework is developed to compare methods in terms of both privacy robustness and system-level efficiency, including computational, memory, and communication overhead.
  Using this framework, representative approaches including differential privacy, homomorphic encryption, secure multi-party computation, distributed selective stochastic gradient descent, and Bloom Filter-based methods are analyzed. The results highlight a fundamental trade-off between privacy strength and system efficiency. In particular, Bloom Filter-based encodings are shown to provide lightweight privacy through collision-induced ambiguity while maintaining low computational and communication overhead. The paper provides a unified perspective on privacy-preserving design choices for distributed learning in IoT systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.09198v1">Rushed by Discomfort, Trapped by Immersion: Users' Experiences and Responses to Privacy Deceptive Design in Commercial VR Applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-05-09T22:34:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hilda Hadan, Michaela Valiquette, Lennart E. Nacke, Leah Zhang-Kennedy</p>
    <p><b>Summary:</b> Commercial Virtual Reality (VR) transforms people's virtual experiences but introduces deceptive design opportunities that threaten user privacy. Although privacy deceptive patterns on 2D platforms are well-documented, their impacts in VR remain understudied. We surveyed 481 users' experiences and responses to privacy deceptive patterns across eight commercial VR scenarios. We found that VR deceptive design can exploit both cognitive vulnerabilities and bodily strain, a phenomenon we define as Ergonomic Susceptibility, and that VR's sensory-rich experiences can make users more likely to accept invasive data disclosure framed as immersion-preserving. Users recognized manipulation but their prior non-VR exposure can foster privacy resignation. Our study shows ergonomics is a critical factor in future privacy-preserving VR design, and urges VR researchers, designers, and policymakers to develop ethical design and privacy management solutions that account for VR's unique multimodal, immersive, and ergonomic properties, building immersive experiences that respect user privacy and mitigate manipulative data practices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.09054v1">Personalized w-Event Privacy for Infinite Stream Estimation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2026-05-09T16:56:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Leilei Du, Xu Zhou, Peng Cheng, Lei Chen, Xuemin Lin, Wei Xi, Kenli Li</p>
    <p><b>Summary:</b> In applications such as event monitoring, log analysis, and video querying, $w$-event privacy protects individual data within a sliding time window while supporting accurate stream statistics. Existing studies on infinite data streams mainly assume homogeneous privacy requirements for all users, which cannot capture user-specific privacy preferences. This paper studies personalized $w$-event privacy for private data stream estimation. We first design the Personalized Window Size Mechanism (PWSM), which supports personalized privacy requirements at each time slot. Based on PWSM, we propose Personalized Budget Distribution (PBD) and Personalized Budget Absorption (PBA) to estimate streaming statistics under $\boldsymbol{w}$-Event $\boldsymbol{\mathcal{E}}$ Personalized Differential Privacy (($\boldsymbol{w}$, $\boldsymbol{\mathcal{E}}$)-EPDP). PBD guarantees that the budget reserved for the next time step is no smaller than the budget consumed in the previous release, while PBA improves the current budget by absorbing unused budgets from the previous $k$ time slots and borrowing from the next $k$ time slots. We further develop Dynamic Personalized Budget Distribution (DPBD) and Dynamic Personalized Budget Absorption (DPBA), which allow users to dynamically adjust privacy requirements while satisfying $(τ, \boldsymbol{w}_B, \boldsymbol{w}_F)$-Event $(\boldsymbol{\mathcal{E}}_B, \boldsymbol{\mathcal{E}}_F)$-Personalized Differential Privacy. We prove that all proposed methods achieve the corresponding personalized differential privacy guarantees and derive their error upper bounds. Experiments show that our methods reduce estimation error by at least $53.6\%$ compared with state-of-the-art algorithms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.08651v1">Privacy-Aware Video Anomaly Detection through Orthogonal Subspace Projection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-09T03:46:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lei Wang, Wenxiang Diao, Andrew Busch, Jun Zhou, Yongsheng Gao</p>
    <p><b>Summary:</b> Video anomaly detection (VAD) systems often prioritize accuracy while overlooking privacy concerns, limiting their suitability for real-world deployment. We propose the Orthogonal Projection Layer (OPL), a lightweight module that removes task-irrelevant variations to produce representations focused on anomaly-relevant cues. To address privacy risks in human-centered scenarios, we introduce Guided OPL (G-OPL), which suppresses facial attributes using weak supervision from face-presence signals while preserving non-identifying features such as pose and motion. A cosine alignment objective enforces consistent capture and removal of facial information without identity labels or adversarial training. We further present a privacy-aware evaluation framework that jointly assesses detection performance and privacy preservation, and enables analysis of how sensitive information is filtered. Experiments show that embedding privacy constraints into model design reduces sensitive information while maintaining or improving detection accuracy, supporting projection-based architectures as a principled approach for privacy-aware VAD.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.08646v1">PAAC: Privacy-Aware Agentic Device-Cloud Collaboration</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-05-09T03:29:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Liangqi Yuan, Wenzhi Fang, Shiqiang Wang, Christopher G. Brinton</p>
    <p><b>Summary:</b> Large language model (LLM) agents face a structural tension: cloud agents provide strong reasoning but expose user data, while on-device agents preserve privacy at the cost of overall capability. Existing device-cloud designs treat this boundary as a compute split rather than a trust boundary suited to agentic workloads, and existing sanitizers force a choice between policy flexibility and the structural fidelity tool calls require. In this work, we develop PAAC, a privacy-aware agentic framework that aligns planner--executor decomposition with the device-cloud boundary so that role specialization itself becomes the privacy mechanism. The cloud agent reasons over typed placeholder tokens that preserve each sensitive value's reasoning role while discarding its content, while the on-device agent identifies sensitive spans and distills each step's execution outcome into compact key findings. Sanitization confines the on-device LLM to proposing which spans to mask, while a deterministic registry performs all substitution and reversal, keeping actions directly executable on device. On three agentic benchmarks under strict privacy settings, PAAC dominates the Pareto frontier of privacy and accuracy, improving average accuracy by 15-36\% and reducing average leakage by 2-6$\times$ over state-of-the-art device-cloud baselines, with the largest margins on privacy targets outside fixed entity taxonomies. We find consistent improvements on 17 additional benchmarks spanning 10 domains, including math, science, and finance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.08324v1">FQPDR: Federated Quantum Neural Network for Privacy-preserving Early Detection of Diabetic Retinopathy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-08T16:49:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Debashis De, Mahua Nandy Pal, Dipankar Hazra</p>
    <p><b>Summary:</b> Diabetic Retinopathy (DR) is a common complication of diabetes that can lead to blindness of people. Detecting DR at the earliest stage is essential to prevent irreversible eye damage. Microaneurysm dots are the first signs of DR. As the dots are tiny and of low contrast, detecting mild DR is a very challenging task. Federated learning (FL) preserves data privacy, which is a major concern for medical image processing. FL is a collaborative learning method, which shares only the model parameters with a server, without sharing the patient data to a central server. Inspired by classical FL, we propose a federated learning-based quantum neural network (federated QNN) for this task. We implemented the models with limited samples and few learnable parameters from the E-ophtha and Retina MNIST datasets. The crossevaluation efficiency of the proposed federated quantum neural network system for privacy-preserving early detection of diabetic retinopathy (FQPDR) in Kaggle dataset images indicates the robustness of the light weight learning models. FQPDR performances are inspiring while considering existing non-FL and FL methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.07930v1">INO-SGD: Addressing Utility Imbalance under Individualized Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-08T16:04:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiao Tian, Jue Fan, Rachael Hwee Ling Sim, Bryan Kian Hsiang Low</p>
    <p><b>Summary:</b> Differential privacy (DP) is widely employed in machine learning to protect confidential or sensitive training data from being revealed. As data owners gain greater control over their data due to personal data ownership, they are more likely to set their own privacy requirements, necessitating individualized DP (IDP) to fulfil such requests. In particular, owners of data from more sensitive subsets, such as positive cases of stigmatized diseases, likely set stronger privacy requirements, as leakage of such data could incur more serious societal impact. However, existing IDP algorithms induce a critical utility imbalance problem: Data from owners with stronger privacy requirements may be severely underrepresented in the trained model, resulting in poorer performance on similar data from subsequent users during deployment. In this paper, we analyze this problem and propose the INO-SGD algorithm, which strategically down-weights data within each batch to improve performance on the more private data across all iterations. Notably, our algorithm is specially designed to satisfy IDP, while existing techniques addressing utility imbalance neither satisfy IDP nor can be easily adapted to do so. Lastly, we demonstrate the empirical feasibility of our approach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.08288v1">UMEDA: Unified Multi-modal Efficient Data Fusion for Privacy-Preserving Graph Federated Learning via Spectral-Gated Attention and Diffusion-Based Operator Alignment</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-05-08T08:15:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shih-Yu Lai, Hirozumi Yamaguchi, Shang-Tse Chen, Yu-Lun Liu, Bing-Yu Chen</p>
    <p><b>Summary:</b> Device-free localization trains models from heterogeneous wireless and visual sensors (e.g., Wi-Fi, LiDAR) distributed across edge devices. Federated learning offers a privacy-respecting framework, but is brittle when clients differ in sensor modality and resolution, when their data distributions drift, and when privacy noise destroys the structural signal needed for localization. We propose UMEDA, a graph federated learning framework in which clients form nodes of a global graph that share a continuous integral operator, and aggregation is reformulated as spectral signal processing on this operator. Each client encodes its local sensors with a linear-attention layer whose kernel spectrum is low-rank filtered, suppressing modality-specific residuals so clients with different sensors align in a common low-rank subspace. The server then aggregates client updates via a diffusion model over the kernel's spectral coefficients, treating updates as discretizations of a shared operator rather than topology-bound weights -- this absorbs varying graph sizes and missing modalities without node-wise correspondence. To balance privacy and utility, we add an anisotropic differential-privacy mechanism that projects noise preferentially into the null space of the signal subspace, preserving dominant eigendirections while ensuring formal $(ε, δ)$-DP under gradient clipping. On MM-Fi and the RELI11D out-of-distribution benchmark, UMEDA outperforms state-of-the-art federated baselines in accuracy, convergence, and communication efficiency, particularly under high modality heterogeneity and tight privacy budgets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.07185v1">Metaphors as Scaffolds: Spatial, Embodied, Fantastical, and Relational Framings for Youth Usable Privacy Design</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-05-08T03:24:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> JaeWon Kim, Alexis Hiniker</p>
    <p><b>Summary:</b> Mainstream usable privacy design frames privacy as administrative work -- settings, toggles, consent checkboxes -- abstracted from the relational, contextual, and embodied registers in which youth reason about disclosure. Drawing on a cross-project reading of three prior studies with youth aged 13--24, we examine how the metaphors that scaffold a privacy interaction shape the reasoning young users bring to it. \textit{Spatial} metaphors reduce cognitive load by recruiting intuitions about navigating physical space. \textit{Embodied} metaphors furnish a shared moral vocabulary that makes implicit norms about public and private space negotiable among users. \textit{Fantastical} metaphors recast privacy management as discoverable play, raising engagement with the granular controls that nuanced self-presentation requires. \textit{Relational} metaphors, by contrast, can lead youth past their own stated boundaries when felt intimacy masks institutional data flow, a risk already visible in AI companion products. Metaphor selection, we argue, is best understood as a first-order ethical design decision for youth privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.06847v1">Privacy Perceptions in Sensor-Powered Smart Vehicle Cabins</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-05-07T18:49:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> BoRui Li, Bofan Yu, Xing-Dong Yang</p>
    <p><b>Summary:</b> As car cabins evolve with the integration of diverse sensors, traditional car cabins are transforming into smart environments. This shift raises important questions about how privacy is understood and managed in such spaces. In this work, we investigate privacy perceptions from the perspectives of both vehicle owners (i.e., people who purchase and own cars) and non-owners (i.e., people who temporarily use cars, such as family members, friends, or renters). Through semi-structured interviews with eighteen participants, we identified key factors that influence these groups' views on privacy. Our findings reveal factors that commonly influence privacy preferences for both owners and non-owners, as well as factors that have a stronger impact on one group over the other. Drawing on these insights, we discuss design implications for future designs to better support and balance the diverse privacy needs of multiple stakeholders in smart car cabins.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.06835v1">On Privacy Leakage in Tabular Diffusion Models: Influential Factors, Attacker Knowledge, and Metrics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-07T18:42:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Masoumeh Shafieinejad, D. B. Emerson, Behnoosh Zamanlooy, Elaheh Bassak, Fatemeh Tavakoli, Sara Kodeiri, Marcelo Lotif, Xi He</p>
    <p><b>Summary:</b> Tabular data plays an important role in many fields and industries, including those with elevated privacy considerations and risks. As such, there is a rising interest in generating high-quality synthetic proxies for real tabular data as a means of reducing privacy risk and proprietary data exposure. With tabular diffusion models (TDMs) demonstrating leading performance in synthesizing such data, understanding and measuring the privacy risks associated with these models is imperative. Leveraging state-of-the-art membership inference attacks for TDMs in both black- and white-box settings, this work quantifies the impact of training setup, synthesis choices, and attacker knowledge on privacy leakage. Moreover, the results demonstrate that adversaries need not have perfect knowledge of the training setup, identical data distributions, or massive compute resources to construct successful attacks. Finally, the pitfalls associated with applying heuristic privacy metrics, such as distance-to-closest record, are revealed.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.06596v1">FedAttr: Towards Privacy-preserving Client-Level Attribution in Federated LLM Fine-tuning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-07T17:21:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Su Zhang, Junfeng Guo, Heng Huang</p>
    <p><b>Summary:</b> Watermark radioactivity testing type of methods can detect whether a model was trained on watermarked documents, and have become key tools for protecting data ownership in the fine-tuning of large language models (LLMs). Existing works have proved their effectiveness in centralized LLM fine-tuning. However, this type of method faces several challenges and remains underexplored in federated learning (FL), a widely-applied paradigm for fine-tuning LLMs collaboratively on private data across different users. FL mainly ensures privacy through secure aggregation (SA), which allows the server to aggregate updates while keeping clients' updates private. This mechanism preserves privacy but makes it difficult to identify which client trained on watermarked documents. In this work, we propose FedAttr, a new client-level attribution protocol for FL. FedAttr identifies which clients trained on watermarked data via a paired-subset-difference mechanism, while preserving the privacy guarantees of SA and FL performance. FedAttr proceeds in three steps: (i) estimate each client's update by differencing two SA queries, (ii) score the estimate with the watermark detector via differential scoring, and (iii) combine scores across rounds via Stouffer method. We theoretically show that FedAttr produces an unbiased estimator of each client's update with bounded mutual information leakage (i.e., $O(d^*/N)$ per-round update). Moreover, FedAttr empirically achieves 100% TPR and 0% FPR, outperforming all baselines by at least 44.4% in TPR or 19.1% in FPR, with only 6.3% overhead relative to FL training time. Ablation studies confirm that FedAttr is robust to protocol parameters and configurations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.06502v1">Privacy by Postprocessing the Discrete Laplace Mechanism</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-07T16:19:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Quentin Hillebrand, Jacob Imola, Rasmus Pagh, Sia Sejer</p>
    <p><b>Summary:</b> We show that an "old dog", the classical discrete Laplace (aka.~geometric) mechanism, can "perform new tricks":
  1. It can be post-processed to yield a simple, unbiased estimator of any subexponential function $f$ of the original data, giving a simple, discrete, multivariate version of the recent unbiasing result for the Laplace mechanism by Calmon et al. (FORC '25).
  2. It can be post-processed to output the same distribution as the Laplace mechanism or the Staircase mechanism with identical privacy parameters.
  Thus, the discrete Laplace mechanism is a versatile mechanism that should be preferred over the Laplace and Staircase mechanisms whenever the data is discrete (or can be made discrete while controlling $\ell_1$-sensitivity).
  We show bounds on the variance of our estimator, compared to the mean square error of the biased estimator that simply evaluates the $f$ on the output of the mechanism. Though our unbiased estimator has exponential running time for worst-case functions, we show that it can often be computed in linear or polynomial time for some common functions exhibiting structure. We showcase the properties of our methods empirically with several use cases including profile and entropy estimation, as well as distributed/federated data analysis applications in which unbiasedness is key to accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.06232v1">Profiling for Pennies: Unveiling the Privacy Iceberg of LLM Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-07T13:21:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiahao Chen, Qi Zhang, Ruixiao Lin, Chunyi Zhou, Tianyu Du, Qingming Li, Tong Zhang, Junhao Li, Yuwen Pu, Shouling Ji</p>
    <p><b>Summary:</b> Large Language Models (LLMs) have revolutionized how information are collected, aggregated, and reasoned. However, this enables a novel and accessible vector of privacy intrusion: the automated and in-depth personal profiling; this engenders a chilling effect of "peepers everywhere". Existing research primarily unfolds from the training pipeline of LLM, emphasizing the exposure of Personally Identifiable Information (PII) through memorization, while privacy studies from a human-centric perspective remain underexplored. To fill this void, we empirically investigate privacy perception in the real world through the lens of human awareness and the practices of LLM-integrated platforms, revealing a significant dissonance: platforms fail to technically or policy-wise address public privacy concerns. To facilitate a systematic and quantifiable study of privacy risk, we propose the PrivacyIceberg, which categorizes real-world human privacy risks into three tiers: explicitly searched, contextually inferred, and deeply aggregated, based on the sophistication of LLM exploitation. We developed IcebergExplorer to audit privacy exposure, utilizing minimal PII as a search seed to reconstruct high-fidelity profiles, achieving over 90% factual accuracy within 10 minutes at a cost under $3, for real-world scenarios. Additionally, we identify six root causes contributing to such privacy disclosures and propose multi-stakeholder countermeasures for LLM vendors, individuals, and data publishers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.05905v1">Quadratic Objective Perturbation: Curvature-Based Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E">
  <p><b>Published on:</b> 2026-05-07T09:16:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Daniel Cortild, Coralia Cartis</p>
    <p><b>Summary:</b> Objective perturbation is a standard mechanism in differentially private empirical risk minimization. In particular, Linear Objective Perturbation (LOP) enforces privacy by adding a random linear term, while strong convexity and stability are ensured by an additional deterministic quadratic term. However, this approach requires the strong assumption of bounded gradients of the loss function, which excludes many modern machine learning models. In this work, we introduce Quadratic Objective Perturbation (QOP), which perturbs the objective with a random quadratic form. This perturbation induces strong convexity and enforces stability of the problem through curvature, thereby enabling privacy and allowing sensitivity to be controlled through spectral properties of the perturbation rather than assumptions on the gradients. As a result, we obtain $(\varepsilon, δ)$-differential privacy under weaker assumptions, in the interpolation regime. Furthermore, we extend the analysis to account for approximate solutions, showing that privacy guarantees are preserved under inexact solves. Additionally, we derive utility guarantees in terms of empirical excess risk, and provide a theoretical and numerical comparison to LOP, highlighting the advantages of curvature-based perturbations. Finally, we discuss algorithmic aspects and show that the resulting problems can be solved efficiently using modern splitting schemes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.05769v1">Adaptive Selection of LoRA Components in Privacy-Preserving Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-05-07T07:01:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Myoungjun Kim, Sangwoo Park, Yoseob Han, Jin-Hyun Ahn</p>
    <p><b>Summary:</b> Differentially private federated fine-tuning of large models with LoRA suffers from aggregation error caused by LoRA's multiplicative structure, which is further amplified by DP noise and degrades both stability and accuracy. Existing remedies apply a single update mode uniformly across all layers and all communication rounds (or alternate them on a fixed schedule), ignoring both the structural asymmetry between the two LoRA factors and the round-wise dynamics of training. We propose AS-LoRA, an adaptive framework defined by three axes (i) layer-wise freedom, in which each layer independently selects its active component, (ii) round-wise adaptivity, in which the selection updates over communication rounds, and (iii) a curvature-aware score derived from a second-order approximation of the loss. Theoretically, AS-LoRA eliminates the reconstruction-error floor of layer-tied schedules, accelerates convergence, implicitly biases solutions toward flatter minima, and incurs no additional privacy cost. Across GLUE, SQuAD, CIFAR-100, and Tiny-ImageNet under strict DP budgets and non-IID partitions, AS-LoRA improves over the federated LoRA baselines by up to $+7.5$ pp on GLUE and $+12.5$ pp on MNLI-mm for example, while matching or exceeding SVD-based aggregation methods at $33\text{--}180 \times$ lower aggregation cost and with negligible communication overhead. Code for the proposed method is available at https://anonymous.4open.science/r/as_lora-F75F/.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.05751v1">A Privacy-Preserving Machine Learning Framework for Edge Intelligence: An Empirical Analysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-05-07T06:43:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Quoc Lap Trieu, Bahman Javadi, Jim Basilakis</p>
    <p><b>Summary:</b> As Edge Intelligence (EI) becomes increasingly prevalent in domains such as smart healthcare, manufacturing, and critical infrastructure, ensuring data privacy while maintaining system efficiency is a growing challenge. This paper presents a new privacy-preserving machine learning (PPML) framework tailored for EI applications, including a four-layer system architecture and training and inference algorithms. We focus on three leading approaches: Differential Privacy (DP), Secure Multi-party Computation (SMC), and Fully Homomorphic Encryption (FHE), and assess their impact on key performance metrics, including model accuracy, response time, and energy consumption. Results from real implementation and extensive trace-based simulations of inference tasks show that DP generally preserves throughput and latency close to plaintext baselines, while accuracy drops with model complexity (up to 35 percent on AlexNet and under 18 percent on LeNet for FordA). SMC performance is driven by communication; network bandwidth and round complexity determine end-to-end latency. For AlexNet, increasing link capacity from 250 Mbps to 500 Mbps reduces latency by about 30 percent. FHE is highly sensitive to model structure and numerical precision bit width, with tighter parameters imposing substantial compute overhead; we observe roughly a 1000 times increase in response time compared to DP. Beyond efficiency, DP shifts the privacy-utility-extractability frontier by reducing the attacker's data efficiency in black-box model stealing, whereas SMC and FHE, while protecting inputs and parameters during inference, require complementary output controls to achieve similar resistance to extraction. These findings provide critical insights into the trade-offs between privacy, performance, and resource efficiency in edge computing scenarios.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.05723v1">$α$-Wasserstein Mechanism for Rényi Pufferfish Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-07T06:12:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ni Ding, Wenjin Yang, Zijian Zhang</p>
    <p><b>Summary:</b> This paper introduces the $α$-Wasserstein mechanism for achieving Rényi Pufferfish Privacy using Laplace and Gaussian noise. By leveraging Hölder's inequality, we demonstrate that the scale parameter of the Laplace mechanism can be calibrated via an upper bound on the $W_α$ metric to satisfy $(α, ε)$-Rényi Pufferfish Privacy for $α\in (1, \infty]$. We show that at the limit $α= \infty$, this framework recovers the established $W_\infty$ mechanism for $ε$-pufferfish privacy. This result is subsequently extended to the exponential mechanism. Furthermore, we propose a $W_α$ mechanism for Gaussian noise for $α\in (1, \infty)$, demonstrating that it generalizes existing results within the Rényi Differential Privacy framework. Experimental evaluations reveal that our $α$-Wasserstein mechanism significantly reduces noise power compared to the conventional $W_\infty$-based approach, with the Gaussian mechanism providing superior utility over the Laplace mechanism. Notably, the mechanisms derived in this work achieve exact $(α, ε)$-Rényi Pufferfish Privacy without requiring additional relaxations, such as $δ$-approximations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.05692v1">CFE-PPAR: Compression-friendly encryption for privacy-preserving action recognition leveraging video transformers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-07T05:32:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haiwei Lin, Shoko Imaizumi, Hitoshi Kiya</p>
    <p><b>Summary:</b> Privacy-preserving action recognition (PPAR) enables machines to understand human activities in videos without revealing sensitive visual content. Among the various strategies for PPAR, encryption-based methods achieve strong privacy protection while maintaining high recognition performance. However, these methods lead to a catastrophic decrease in recognition performance and visual quality when the encrypted videos are compressed. That is, the previous methods are not compression-friendly. To address these issues, in this paper, we propose the first compression-friendly encryption method for PPAR, called CFE-PPAR. In CFE-PPAR, videos encrypted with secret keys can be directly recognized by a video transformer, which uses parameters transformed by the same keys as those used for video encryption. In experiments, it is verified that CFE-PPAR outperforms previous methods on the UCF101 and HMDB51 datasets under Motion-JPEG and H.264 compression.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.05459v1">Privacy Without Losing Place: A Paradigm for Private Retrieval in Spatial RAGs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-06T21:33:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kennedy Edemacu, Mohammad Mahdi Shokri, Vinay M. Shashidhar, Jong Wook Kim</p>
    <p><b>Summary:</b> This work introduces PAS -- Privacy Anchor Substitution, a structured mechanism for enabling user location privacy in spatial retrieval-augmented generation (RAG) systems. Unlike conventional differential privacy methods that directly perturb user locations, PAS represents location with relative anchor encoding consisting of an anchor, direction bin, and distance bin, allowing seamless integration with modern RAG pipelines. We evaluate PAS on a synthetic urban dataset and show that it achieves impressive coarse privacy guarantees, with approximately 370-400m adversarial location error, while retaining more than half of the baseline retrieval performance. Despite the slight drop in retrieval performance, the downstream generation quality under PAS remains comparatively robust, indicating that large language models can compensate for imperfect spatial retrieval. Furthermore, we provide empirical analysis showing that PAS exhibits non-monotonic privacy-utility relationship with respect to privacy parameters. We attribute this to geometric bias induced by anchor discretization, making it different from continuous noise mechanisms such as geo-indistinguishability. Our results show that structured spatial representations offer a practical approach to privacy in location based reasoning in RAG systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.05340v2">How Far Are VLMs from Privacy Awareness in the Physical World? An Empirical Study</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-06T18:10:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Junran Wang, Xinjie Shen, Zehao Jin, Pan Li</p>
    <p><b>Summary:</b> As Vision-Language Models (VLMs) are increasingly deployed as autonomous cognitive cores for embodied assistants, evaluating their privacy awareness in physical environments becomes critical. Unlike digital chatbots, these agents operate in intimate spaces, such as homes and hospitals, where they possess the physical agency to observe and manipulate privacy-sensitive information and artifacts. However, current benchmarks remain limited to unimodal, text-based representations that cannot capture the demands of real-world settings. To bridge this gap, we present ImmersedPrivacy, an interactive audio-visual evaluation framework that simulates realistic physical environments using a Unity-based simulator. ImmersedPrivacy evaluates physically grounded privacy awareness across three progressive tiers that test a model's ability to identify sensitive items in cluttered scenes, adapt to shifting social contexts, and resolve conflicts between explicit commands and inferred privacy constraints. Our evaluation of 12 state-of-the-art models reveals consistent deficits. In cluttered scenes, all models exhibit monotonic performance decay as scene complexity grows due to perceptual deficit. When social context shifts, no model exceed 65% selection accuracy. Under conflicting commands, the best model gemini-3.1-pro perfectly balances task completion and privacy preservation in only 51% of cases. These findings reveal that current VLMs in the physical world suffer from perceptual fragility and fail to let their knowledge of privacy cues govern their situated behavior. Our code and data is available at https://github.com/immersed-privacy/immersed-privacy .</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.05277v1">GLiNER Guard: Unified Encoder Family for Production LLM Safety and Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-06T15:22:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bogdan Minko, Sabrina Sadiekh, Evgeniy Kokuykin</p>
    <p><b>Summary:</b> Production LLM systems require both safety moderation and PII detection under strict latency and cost constraints. This creates a trade-off: autoregressive moderators are accurate but expensive, while lightweight encoders are faster but less capable. We present GLiNER Guard (GLiGuard), a unified encoder that performs safety classification and PII detection in a single forward pass, simplifying safety pipelines. We introduce three variants: compact uni- and bi-encoders (145-147M) for high-throughput serving, and GLiGuard Omni (209M) for stronger moderation quality. Under dynamic batching on a single A100, the compact model reaches 193 requests/sec with P99 latency below 1s, achieving 1.6x higher throughput than GLiNER2. Omni remains competitive with much larger moderators on public safety benchmarks. We also release PII-Bench, a span-level benchmark for evaluating PII detection in end-to-end pipelines. Overall, encoder-based guardrails offer a practical low-cost alternative for always-on moderation. Models and benchmarks are released on HuggingFace.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.05017v1">Position: Embodied AI Requires a Privacy-Utility Trade-off</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E">
  <p><b>Published on:</b> 2026-05-06T15:16:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaoliang Fan, Jiarui Chen, Zhuodong Liu, Ziqi Yang, Peixuan Xu, Ruimin Shen, Junhui Liu, Jianzhong Qi, Cheng Wang</p>
    <p><b>Summary:</b> Embodied AI (EAI) systems are rapidly transitioning from simulations into real-world domestic and other sensitive environments. However, recent EAI solutions have largely demonstrated advancements within isolated stages such as instruction, perception, planning and interaction, without considering their coupled privacy implications in high-frequency deployments where privacy leakage is often irreversible. This position paper argues that optimizing these components independently creates a systemic privacy crisis when deployed in sensitive settings, thereby advancing the position that privacy in EAI is a life cycle-level architectural constraint rather than a stage-local feature. To address these challenges, we propose Secure Privacy Integration in Next-generation Embodied AI (SPINE), a unified privacy-aware framework that treats privacy as a dynamic control signal governing cross-stage coupling throughout the entire EAI life cycle. SPINE decomposes the EAI pipeline into various stages and establishes a multi-criterion privacy classification matrix to orchestrate contextual sensitivity across stage boundaries. We conduct preliminary simulation and real-world case studies to conceptually validate how privacy constraints propagate downstream to reshape system behavior, illustrating the insufficiency of fragmented privacy patches and motivating future research directions into secure yet functional embodied AI systems. We detail the SPINE framework and case studies at https://github.com/rminshen03/EAI_Privacy_Position.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.04977v1">ICPR 2026 Competition on Privacy-Preserving Person Re-Identification from Top-View RGB-Depth Camera (TVRID)</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-05-06T14:31:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Raphaël Delécluse, Hazem Wannous, Laurent Guimas</p>
    <p><b>Summary:</b> This companion paper reports the ICPR 2026 TVRID competition on privacy-aware top-view person re-identification. We present the competition setting, the released RGB-Depth dataset, and a summary of final results with descriptions of the top entries. TVRID contains 86 identities captured by four synchronized overhead Intel RealSense D455 cameras, with paired RGB/Depth streams and structured geometric variation across flat, ascent, descent, and oblique viewpoints. The evaluation protocol includes three tracks: RGB Re-ID, Depth Re-ID, and RGB$\leftrightarrow$Depth cross-modal retrieval. Submissions are ranked using mAP and CMC-1 under a unified server-side evaluation. The final results show a clear difficulty ordering (RGB $>$ Depth $>$ Cross-Modal), highlighting both the challenge of modality-constrained retrieval and the feasibility of strong performance with modality-invariant learning. By releasing the dataset at https://zenodo.org/records/17909410, the evaluation scripts at https://github.com/RaphaelDel/ICPR-TVRID, and the accompanying documentation, TVRID establishes a reproducible benchmark for top-view, depth-based, and cross-modal person re-id.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.04911v1">Breaking the Quality-Privacy Tradeoff in Tabular Data Generation via In-Context Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-06T13:38:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xinyan Han, Yan Lu, Xiaoyu Lin, Yuanyuan Jiang, Yuanrui Wang, Xuanyue Li, Wenchao Zou, Xingxuan Zhang</p>
    <p><b>Summary:</b> Tabular data synthesis aims to generate high-quality data while preserving privacy. However, we find that existing tabular generative models exhibit a clear tradeoff in the small-data regime: improving data quality typically comes at the cost of increased memorization of training samples, thereby weakening privacy protection. This tradeoff arises because small training sets make it difficult for dataset-specific generative models to distinguish generalizable structure from sample-specific patterns. To address this, we propose DiffICL, which formulates tabular data generation as an in-context learning problem. Instead of fitting each dataset from scratch,DiffICL leverages pretrained structural priors learned from a large collection of datasets, enabling it to infer data distributions from limited context rather than memorizing individual samples. We evaluate DiffICL on 14 real-world datasets. Results show that DiffICL improves both data quality and privacy, and generate synthetic data that provides effective data augmentation. Our findings suggest that the quality-privacy tradeoff can be improved through better training paradigms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.05266v1">Differential Privacy in the Extensive-Form Bandit Problem</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-06T09:19:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stephen Pasteris, Rahul Savani, Theodore Turocy</p>
    <p><b>Summary:</b> We consider the extensive-form bandit problem, where on each trial the learner (a user coordinated by a server) plays an extensive-form game against an oblivious adversary, observing the information sets it finds itself in as well as the resulting payoff/loss. We give an algorithm for this problem that satisfies $ε$-local differential privacy and attains a regret of $\tilde{O}(\sqrt{A\ln(S)T}/ε)$, where $A$ is the total number of actions that the learner can possibly take, $S$ is the number of the learner's possible reduced strategies, and $T$ is the number of trials. On each trial, the time complexity of our algorithm is, up to a factor logarithmic in the maximum number of actions at an infoset, equal to the time required for the server to transmit the reduced strategy to the user. We note that local differential privacy is the strongest version of differential privacy and, to the best of our knowledge, this is the first work to study differential privacy of any form in the extensive-form bandit problem.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.04519v1">FL-Sailer: Efficient and Privacy-Preserving Federated Learning for Scalable Single-Cell Epigenetic Data Analysis via Adaptive Sampling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2026-05-06T05:56:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guangyi Zhang, Yi Dai, Yiyun He, Junhao Liu</p>
    <p><b>Summary:</b> Single-cell ATAC-seq (scATAC-seq) enables high-resolution mapping of chromatin accessibility, yet privacy regulations and data size constraints hinder multi-institutional sharing. Federated learning (FL) offers a privacy-preserving alternative, but faces three fundamental barriers in scATAC-seq analysis: ultra-high dimensionality, extreme sparsity, and severe cross-institutional heterogeneity. We propose FL-Sailer, the first FL framework designed for scATAC-seq data. FL-Sailer integrates two key innovations: (i) adaptive leverage score sampling, which selects biologically interpretable features while reducing dimensionality by 80%, and (ii) an invariant VAE architecture, which disentangles biological signals from technical confounders via mutual information minimization. We provide a convergence guarantee, showing that FL-Sailer converges to an approximate solution of the original high-dimensional problem with bounded error. Extensive experiments on synthetic and real epigenomic datasets demonstrate that FL-Sailer not only enables previously infeasible multi-institutional collaborations but also surpasses centralized methods by leveraging adaptive sampling as an implicit regularizer to suppress technical noise. Our work establishes that federated learning, when tailored to domain-specific challenges, can become a superior paradigm for collaborative epigenomic research.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.04221v1">Self-Prompting Small Language Models for Privacy-Sensitive Clinical Information Extraction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-05T19:03:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yao-Shun Chuang, Tushti Mody, Uday Pratap Singh, Shirindokht Shiraz, Chun-Teh Lee, Ryan Brandon, Muhammad F Walji, Xiaoqian Jiang, Bunmi Tokede</p>
    <p><b>Summary:</b> Clinical named entity recognition from dental progress notes is challenging because documentation is highly unstructured, domain-specific, and often privacy-sensitive. We developed a locally deployable framework that enables small language models to self-generate, verify, refine, and evaluate entity-specific prompts for extracting multiple clinical entities from dental notes. Using 1,200 annotated notes, we evaluated candidate open-weight models with multi-prompt ensemble inference and further adapted selected models using QLoRA-based supervised fine-tuning and direct preference optimization. Model performance varied substantially, highlighting the need for task-specific evaluation rather than reliance on generic benchmarks. Qwen2.5-14B-Instruct achieved the strongest baseline performance. After DPO, Qwen2.5-14B-Instruct and Llama-3.1-8B-Instruct achieved micro/macro F1 scores of 0.864/0.837 and 0.806/0.797, respectively. These findings suggest that automated prompt optimization combined with lightweight preference-based post-training can support scalable clinical information extraction using locally deployed small language models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.04029v1">Stayin' Aligned Over Time: Towards Longitudinal Human-LLM Alignment via Contextual Reflection and Privacy-Preserving Behavioral Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-05-05T17:51:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Simret Araya Gebreegziabher, Allison E Sproul, Yinuo Yang, Chaoran Chen, Diego Gómez-Zará, Toby Jia-Jun Li</p>
    <p><b>Summary:</b> Current human-AI alignment and evaluation methods for large language models (LLMs) often rely on preference signals collected immediately after an interaction. This practice implicitly treats preference as static, even though many LLM-mediated decisions unfold over time and may be re-evaluated differently after real-world consequences and observed outcomes. Therefore, we argue for a methodological shift from single-moment preference elicitation to longitudinal, context-situated alignment measurement. We present a methodological framework for collecting temporally grounded alignment signals by combining (1) in-situ preference capture, (2) context-triggered follow-up preference reflection, and (3) privacy-preserving behavioral traces that help interpret preference change. As an instantiation of this methodology, we introduce BITE, a browser-based system that detects consequential LLM interactions, prompts reflection across later decision points, and supports progressive, user-controlled consent for sharing behavioral data. Through a two week longitudinal deployment study with 8 participants, our approach surfaced differences between immediate and later user preferences in accuracy, relevance and other dimensions of the LLM output. Our findings highlight the limitations of single-moment preference datasets and underscore the importance of longitudinal methods for alignment evaluation in everyday use.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.03945v1">Integrating Feature Correlation in Differential Privacy with Applications in DP-ERM</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2026-05-05T16:32:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tianyu Wang, Luhao Zhang, Rachel Cummings</p>
    <p><b>Summary:</b> Standard differential privacy imposes uniform privacy constraints across all features, overlooking the inherent distinction between sensitive and insensitive features in practice. In this paper, we introduce a relaxed definition of differential privacy that accounts for such heterogeneity, allowing certain features to be treated as insensitive even when correlated with sensitive ones. We propose a correlation-aware framework, $\textsf{CorrDP}$, which relaxes privacy for insensitive features while accounting for their correlations with sensitive features, with the correlations quantified using total variation distance. We design algorithms for differentially private empirical risk minimization (DP-ERM) under the $\textsf{CorrDP}$ framework, incorporating distance-dependent noise into gradients for improved theoretical utility guarantees. When the correlation distance is unknown, we estimate it from the dataset and show that it achieves a comparable privacy-utility guarantee. We perform experiments on synthetic and real-world datasets and show that $\textsf{CorrDP}$-based DP-ERM algorithms consistently outperform the standard DP framework in the presence of insensitive features.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.03188v1">Dependency-Aware Privacy for Multi-turn Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-04T22:13:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Divyam Anshumaan, Sarthak Choudhary, Nils Palumbo, Somesh Jha</p>
    <p><b>Summary:</b> LLM agents release private data across multi-service interactions. Existing prompt sanitizers based on metric differential privacy treat each release independently, so adversaries combining releases across turns can recover private attributes; privacy degrades with every release.
  This degradation is fundamental: when private attributes are the \emph{roots} of a computation graph, independently noising a derived value amplifies the root's distinguishability by up to the deriving function's Lipschitz constant $L$, which can far exceed the nominal privacy parameter for nonlinear functions in medical and financial workflows.
  RootGuard sanitizes root values once and computes subsequent releases deterministically from the noised roots. By the post-processing theorem, the privacy guarantee depends only on the initial root sanitization, regardless of the adversary's functions or number of turns, and derived values inherit privacy at zero marginal cost. RootGuard further exploits structural domain knowledge (e.g., BMI from height and weight, or a known target function) to allocate budget across roots, improving the privacy-utility tradeoff.
  A worst-case adversary forcing $t$ turns increases the total budget $B = t \cdot \varepsilon$. RootGuard distributes this larger budget across roots, while independent noising spends $\varepsilon$ per release and gives the adversary $t$ observations to combine via MAP reconstruction. This yields a \emph{double asymmetry}: more turns aid RootGuard while weakening independent noising.
  On eight NHANES medical diagnostic templates, RootGuard achieves $2.3$--$3.0\times$ lower target error than independent noising at $\varepsilon = 0.1$ (7.6\% vs.\ 17.1\% wMAPE at $B = (2k{+}1)\varepsilon$). Under MAP reconstruction, more queries strengthen attacks against independent noising while RootGuard remains invariant.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.03069v1">Distributed Deep Variational Approach for Privacy-preserving Data Release</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-04T18:41:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zahir Alsulaimawi, Huaping Liu</p>
    <p><b>Summary:</b> Federated learning (FL) lets distributed nodes train a shared model without exchanging their raw data, but in privacy-sensitive deployments medical sensors, IoT devices, wearables the protection offered by keeping data local is incomplete: gradients, model updates, and the released representations themselves can leak sensitive attributes. We propose the \emph{Gaussian Privacy Protector} (GPP), a data-release framework for continuous, high-dimensional inputs that learns a stochastic encoder mapping raw data to a low-dimensional sanitized representation. The encoder is trained against a variational lower bound on the mutual information between the released representation and a designated sensitive attribute, while a separate cross-entropy term preserves a designated utility attribute, with a Lagrange multiplier $β$ controlling the trade-off. We then extend GPP to the federated setting, in which each client trains a local encoder, sensitive labels never leave the client, and the aggregator receives only sanitized representations giving instance-level privacy protection in addition to the standard ``raw data stays local'' guarantee of FL. We evaluate GPP on MNIST (digit-sum utility, parity sensitive), CelebA (smiling vs.\ gender), and HAPT-Recognition (activity vs.\ subject identity). Across all three benchmarks, GPP attains utility within roughly one percentage point of an unconstrained autoencoder baseline while reducing the adversary's AUC to near random guessing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.02886v1">CityOS: Privacy Architecture for Urban Sensing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Operating Systems-04E762">
  <p><b>Published on:</b> 2026-05-04T17:54:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Giorgio Cavicchioli, Mark Chen, Navid Salami Pargoo, Shuren Xia, Xiaotian Zhou, Roxana Geambasu, Jason Nieh, Jorge Ortiz</p>
    <p><b>Summary:</b> Cities are rapidly deploying sensing infrastructure -- cameras, environmental sensors, and connected kiosks -- that continuously observe public spaces, yet they lack a system architecture governing how applications access, aggregate, and retain this data, creating privacy risks and preventing consistent policy enforcement. We present CityOS, an operating system for urban sensing that mediates application access to sensor data through a three-tier API inspired by structured, privacy-conscious web interfaces. The tiers expand the spatial scope of data access while imposing progressively stronger privacy constraints: On-Scene supports real-time sensing with raw data confined to the local context; Single-Locality Aggregation enables differentially private longitudinal statistics at a fixed location; and Cross-Locality Aggregation supports citywide analytics via aggregation across locations, with user devices enforcing per-user privacy budgets. CityOS runs as an edge runtime that executes untrusted applications in ephemeral containers, enforcing these policies and providing transparency via broadcasts of differential privacy loss. We implement CityOS and applications across all tiers -- including pedestrian safety alerts, real-time and forecast parking availability, traffic dashboards, and subway trajectory measurement -- and show that it supports practical streetscape applications while enforcing strong privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.04108v1">MuCALD-SplitFed: Causal-Latent Diffusion for Privacy-Preserving Multi-Task Split-Federated Medical Image Segmentation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-05-04T16:43:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chamani Shiranthika, Hadi Hadizadeh, Parvaneh Saeedi</p>
    <p><b>Summary:</b> Federated Learning enables decentralized training by aggregating model updates across clients without sharing raw data, while Split Federated Learning further partitions the model between clients and a server to reduce computation and communication at the client side. However, decentralized medical institutions rarely operate on a single shared task, making standard Federated and SplitFed collaborations poorly aligned with real clinical workflows. Multi-task FL extends these frameworks by allowing clients to handle different tasks, but often introduces instability and privacy vulnerabilities. This study proposes \textbf{MuCALD-SplitFed}, a multi-task SplitFed framework that integrates causal representation learning and latent diffusion. Experiments show MuCALD-SplitFed consistently improves segmentation, while baseline SplitFed fails to converge. The proposed approach further reduces information leakage at split points, mitigating reconstruction-based and membership inference attacks. Additionally, MuCALD SplitFed outperforms state-of-the-art personalized FL and multi-task FL approaches. The code repository is: https://github.com/ChamaniS/MuCALD_SplitFed.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.02724v1">Period-conscious Time-series Reconstruction under Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Multimedia-5BC0EB">
  <p><b>Published on:</b> 2026-05-04T15:25:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yaxuan Wang, Tianxin Li, Enji Liang, Yue Fu, Yanran Wang</p>
    <p><b>Summary:</b> Periodic patterns are fundamental cues in multimedia signals and systems, including repetitive motion in video (e.g., gait cycles), rhythmic and pitch-related structure in audio, and recurring textures in image sequences. When such user-generated streams are collected from edge devices, local differential privacy (LDP) is appealing because it perturbs data before upload; however, the injected noise can corrupt spectral peaks and induce phase drift, making period estimation unreliable and degrading reconstruction quality. We propose \textbf{CPR} (\textit{Cycle and Phase Recovery}), a period-aware reconstruction framework for periodic time series under LDP. CPR performs multi-scale period probing and multi-consensus selection to suppress noise-induced spectral interference, then aggregates perturbed samples at matched within-cycle phase positions to stabilize phase alignment across cycles. To recover the underlying per-phase values, CPR combines EM-based denoising with kernel density estimation, improving robustness under tight privacy budgets. Experiments on two real-world periodic datasets demonstrate that CPR better preserves periodic structure and consistently achieves lower reconstruction error than representative LDP baselines, especially in the low-$ε$ regime.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.02553v1">Noisy Networks, Nosy Neighbors: Simple Privacy Attacks Against Residential Wireless Traffic</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-04T13:01:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arne Roszeitis, Bartosz Burgiel, Victor Jüttner, Erik Buchmann</p>
    <p><b>Summary:</b> Smart devices, such as light bulbs, TVs, fridges, etc., equipped with computing capabilities and wireless communication, are part of everyday life in many households. Previous work has already shown that a passive eavesdropper can derive private information, household routines, etc., from the network traffic of smart devices. However, existing attacks rely on capable adversaries with specialized machine learning expertise, labeled training data and reference devices, leaving it unclear how vulnerable ordinary households are to less sophisticated attackers. In this paper, we investigate the extent to which a ,,casual attacker'' with straightforward IT skills and no specialized cybersecurity or ML tooling can reproduce such privacy attacks. Operating from an adjacent room in a real-world apartment building, we constrain our adversary to use only three off-the-shelf Raspberry Pis, Wireshark, and basic Python scripts. Through a three-week study, we demonstrate that this casual attacker can manually identify devices, recognize user states, track smartphone movements through walls via RSSI triangulation, and successfully extract detailed daily routines, including sleep patterns of guests. Our findings show that smart-home privacy leakage is a threat even from low-resourced, straightforward adversaries, e.g., neighbors.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.02372v1">Privacy Preserving Machine Learning Workflow: from Anonymization to Personalized Differential Privacy Budgets in Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-04T09:15:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Judith Sáinz-Pardo Díaz, Álvaro López García</p>
    <p><b>Summary:</b> The growing development of artificial intelligence based solutions, together with privacy legislation, has driven the rise of the so-called privacy preserving machine learning architectures, such as federated learning. While federated learning enables model training on decentralized data preventing their sharing and centralization, it still faces several challenges related to data integrity and privacy. This paper presents a comprehensive privacy preserving federated learning workflow for sensitive tabular data, including anonymization and differential privacy techniques. We also introduce a formal definition for the concept of client drift, together with ways of detecting it to mitigate poisoning attacks. Then, we detail a complete methodology for assigning personalized privacy budgets for global differential privacy to the different clients participating in the network, based on a re-identification risk metric. The proposed methodology is presented and tested on an openly available dataset of medical records. Within the experimental setup we show that the approach based on personalized budgets, compared to the architecture including global differential privacy with fixed privacy budget, achieves a better model performance in terms of two error metrics.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.02319v1">Optimal Privacy-Utility Trade-Offs in LDP: Functional and Geometric Perspectives</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-05-04T08:15:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Seung-Hyun Nam, Hyun-Young Park, Si-Hyeon Lee</p>
    <p><b>Summary:</b> Local differential privacy (LDP) has emerged as a gold-standard framework for privacy-preserving data analysis. However, characterizing the optimal privacy-utility trade-off (PUT) and the corresponding optimal LDP channels remains largely fragmented, relying on problem-specific, case-by-case analyses. In this work, we develop a unified theoretical framework that systematically characterizes the optimal PUT and optimal LDP channels for general privacy-preserving statistical decision-making problems. We first identify key functional properties of Bayesian and minimax risks as functions of the LDP channel, including the data processing inequality (DPI), direct-sum quasi-convexity (or additivity), concavity, and symmetry invariance. Leveraging these properties, we reduce the optimization domain required to compute the optimal PUT. Additionally, building on convex geometric insights, we establish a one-to-one correspondence between maximal LDP channels under the Blackwell order and a finite-dimensional polytope, yielding an exact geometric characterization. This result renders the optimal PUT computationally tractable via vertex enumeration or linear programming. Furthermore, when the underlying problem exhibits symmetries characterized by a transitive group action, we derive an exact analytic expression for the optimal PUT, leading to closed-form solutions without numerical optimization. Our framework applies broadly beyond risk minimization, encompassing the maximization of information-theoretic measures such as mutual information, $f$-divergences, and Fisher information over LDP channels. We demonstrate the efficacy of our theoretical framework by recovering or strengthening several known results, and deriving exact analytic expressions for the optimal PUTs in specific tasks that were previously unaddressed.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.02297v1">Graph Federated Unlearning for Privacy Preservation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-04T07:42:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruotong Ma, Wentao Yu, Qizhou Wang, Jie Yang, Chen Gong</p>
    <p><b>Summary:</b> Graph federated learning (GFL) facilitates decentralized training on distributed graph data while keeping sensitive user information local, aligning with policies such as GDPR and CCPA that grant users the right to freely join or withdraw from learning systems. However, even decentralized, user information can persist after quitting, potentially propagating to central servers and then redistributing to malicious clients. This privacy leakage during user withdrawal, despite its importance, has received seldom attention in GFL. To fill the gap, we explore the potential of machine unlearning (MU) to thoroughly remove user information. However, classical MU methods are known to degrade overall performance, a problem that is exacerbated in GFL due to local message passing and global model collaboration. To this end, we make two adjustments to mitigate this challenge for GFL. First, we ensure unlearning updates that minimally affect overall performance, steering them in directions orthogonal to the gradients from learning other data. Second, we introduce virtual clients, maintained by the central server, to preserve graph topology and global embeddings without recovering information of removed entities. We conduct comprehensive experiments under a representative user-withdrawal scenario and propose a novel membership inference framework to rigorously evaluate and validate the reliability of our privacy preservation. The experimental results demonstrate the effectiveness of our approach, which also surpasses the performance of seven state-of-the-art baseline methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.02255v1">On the Privacy of LLMs: An Ablation Study</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-04T06:06:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Karima Makhlouf, Lamiaa Basyoni, Syed Khaderi, Gabriel Marquez, Peter Sotomango, Mahmoud Awawdah, Sami Zhioua</p>
    <p><b>Summary:</b> Large language models (LLMs) are increasingly deployed in interactive and retrieval-augmented settings, raising significant privacy concerns. While attacks such as Membership Inference (MIA), Attribute Inference (AIA), Data Extraction (DEA), and Backdoor Attacks (BA) have been studied, they are typically analyzed in isolation, leaving a gap in understanding their behavior under common system factors. In this paper, we introduce a unified threat model and notation, reproduce a representative set of privacy attacks, and conduct a structured ablation study to evaluate the impact of key factors such as model architecture, scale, dataset characteristics, and retrieval configuration. Our analysis reveals clear differences across attack types. Membership inference attacks, particularly mask-based variants, exhibit strong and reliable signals, while backdoor attacks achieve consistently high success rates due to their trigger-based nature. In contrast, attribute inference and data extraction attacks remain more challenging, resulting in lower accuracy, yet they pose significant risks as they target sensitive personal information. Overall, these results highlight that privacy risks in LLM systems are highly context-dependent and driven by design choices, emphasizing the need for holistic evaluation and informed deployment practices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.08152v1">Privacy-Preserving Federated Learning: Integrating Zero-Knowledge Proofs in Scalable Distributed Architectures</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-04T04:20:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Divya Gupta</p>
    <p><b>Summary:</b> The intersection of Artificial Intelligence (AI) and distributed systems has given rise to Federated Learning (FL), a paradigm that enables decentralized model training without compromising local data privacy. As organizational data silos grow, deploying complex machine learning models across highly distributed edge networks becomes a critical infrastructural challenge. Standard FL implementations suffer from severe vulnerabilities related to adversarial gradient updates and computational bottlenecks at the aggregation layer. This paper presents a novel, end-to-end distributed architecture that hardens FL pipelines using advanced cryptographic verification and optimized big data processing frameworks. We introduce a Zero-Knowledge Proof (ZKP) wrapper that cryptographically validates node computations before global aggregation, neutralizing model poisoning attacks without inspecting raw gradients. Additionally, we evaluate the system's performance using extreme gradient boosting models optimized for distributed edge execution. We formalize the mathematical transformation of the machine learning loss functions into Rank-1 Constraint Systems (R1CS) suitable for succinct verification. Extensive experimental results demonstrate that our hybrid architecture achieves a 94.2\% accuracy retention under adversarial conditions while maintaining scalable throughput across 1,000 parallel distributed nodes, effectively bridging the gap between rigorous cryptographic security and high-performance distributed AI.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.02169v2">Heterogeneous Model Fusion for Privacy-Aware Multi-Camera Surveillance via Synthetic Domain Adaptation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-04T02:58:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Peggy Joy Lu, Wei-Yu Chen, Yao-Tsung Huang, Vincent Shin-Mu Tseng</p>
    <p><b>Summary:</b> We propose HeroCrystal, a novel privacy-preserving framework for multi-camera domain-adaptive object detection, addressing challenges such as data privacy, class imbalance, and heterogeneous architectures. Our framework consists of three key stages. In the Generated Stage, we introduce a one-shot, target-aware diffusion-based generation module that learns visual style from a single target-domain image while leveraging prompt-based control to synthesize specific object instances. Unlike conventional style transfer-based methods that require large target datasets and ignore semantic-level discrepancies, our approach enables privacy-preserving augmentation to reduce ethical concerns, and introduces controllable rare object generation to mitigate long-tailed category degradation. In the Federated Stage, we employ probabilistic Faster R-CNN on the client side to improve localization accuracy, and a dynamic model contrastive strategy to suppress domain-specific bias. The server side performs model fusion across heterogeneous architectures without accessing raw data. Finally, in the Distilled Stage, we propose an inconsistent categories integration algorithm to resolve label inconsistency and architecture heterogeneity across clients. Extensive experiments on multiple cross-domain detection benchmarks demonstrate that our method outperforms existing multi-source domain adaptation and federated learning baselines under multi-class, privacy-preserving settings. Our method improves mAP by +2.1% over prior privacy-preserving approaches and achieves a new state-of-the-art mAP of 33.4%, highlighting the effectiveness of HeroCrystal in enabling practical multi-camera AI surveillance systems.
  The source code is publicly available at https://github.com/ccuvislab/HeroCrystal.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.02077v1">Obscura: Privacy-Preserving Protocol for the Algorand Blockchain Using LSAG Ring Signatures</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-03T22:33:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Navid Azimi</p>
    <p><b>Summary:</b> While public blockchains provide transparent and auditable transaction histories, they inherently compromise user privacy. Existing privacy-enhancing protocols, such as those deployed on Ethereum, typically rely on succinct zero-knowledge proofs (zk-SNARKs) to obscure the transaction graph. However, implementing comparable cryptographic guarantees on high-throughput blockchains like Algorand is challenging due to strict per-call execution budgets and the state contention introduced by global Merkle accumulators. This paper presents Obscura, a decentralized, non-custodial privacy protocol tailored for constrained smart contract environments. Obscura achieves transaction anonymity using Linkable Spontaneous Anonymous Group (LSAG) signatures over the BN254 elliptic curve, verified entirely on-chain. To overcome limitations of the Algorand Virtual Machine (AVM), we introduce a novel state model that leverages Algorand's Box Storage for $O(1)$ commitment membership checks, eliminating the need for global Merkle accumulators, and a dynamic opcode-budget expansion mechanism via pooled inner application calls. Our implementation demonstrates that signer-ambiguous privacy is practical and efficient on Algorand without relying on trusted setups or succinct proofs. Obscura provides a robust privacy layer for transparent ledgers, bridging the gap between high-throughput blockchain architectures and the dual requirements of cryptographic privacy and selective auditability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.02977v1">Contrastive Privacy: A Semantic Approach to Measuring Privacy of AI-based Sanitization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-03T21:33:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> George Bissias, Eugene Bagdasarian, Brian Neil Levine</p>
    <p><b>Summary:</b> To sanitize specific concepts from imagery and text, privacy mechanisms with formal guarantees are often eschewed in practice in favor of more intuitive techniques. AI-based sanitization is poised to grow in popularity because it can work with the semantics of natural language concepts; e.g., a prompt to "remove faces, clothing, and body shape". Many approaches exist commercially and as prior work. But, the evaluation of such approaches has been bespoke and without formal guarantees.
  To fill this gap, we propose contrastive privacy, a formal definition of privacy that provides a systematic and quantitative test of sanitized media that has a semantic interpretation. It is independent of the model and mechanism used and operates across multiple media modalities. Contrastive privacy provides guarantees under ideal conditions; and we show how to operationalize the definition with imperfect measures of semantics, provided by models like CLIP, that can connect concepts latently. Notably, the algorithm contrasts sanitized media with other images from the same corpus to arrive at a determination; no manual labeling is involved.
  In our experiments, we apply our privacy test to both images and text using frontier models: some generate concepts to sanitize and others perform the sanitization. With our test we quantify sanitization success across 34 combinations of models on images, and for 15 models on text. The approach not only quantifies success overall, it identifies specific failures from a sanitized corpus. Further, it is independent of the mechanism used for sanitization, whether by darkening pixels, blurring, or applying more advanced means of obfuscation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.02016v2">What's on Your Mind? Exploring Privacy of Mental Health Apps</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-05-03T18:42:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chloe Georgiou, Hans Lu, Emiliano De Cristofaro, Gene Tsudik</p>
    <p><b>Summary:</b> Therapy and life-coaching apps have been rapidly growing in number, flavors, and popularity. However, their users routinely share highly sensitive and personal information, such as traumas, fantasies, desires, relationship difficulties, and other mental health concerns. This prompts the need for an empirical analysis of privacy practices in this ecosystem, and particularly the alignment between these apps' privacy policies and their actual behavior. In this paper, we present a comprehensive analysis of 25 popular Android mental health and life-coaching apps, combining static analysis, dynamic network capture, and LLM-assisted privacy policy extraction validated against manual annotation.
  Our findings highlight serious concerns and substantial transparency gaps. First, every app embeds at least one tracker SDK that its privacy policy does not name, and 68% of apps fail to disclose at least half of the trackers detected in their APKs; Talkie alone embeds 20 while naming none. Second, we identify 16 permission-policy contradictions across 13 apps, i.e., a dangerous permission is declared in the manifest but omitted from the policy, including 6 apps that request camera or microphone access without disclosing photo, video, or audio collection. Third, 48% of apps disclose third-party AI processing (e.g., via OpenAI, Anthropic, Groq), with one app sending journal entries to all three simultaneously, while 7 apps use only generic language that leaves recipients unidentified. Taken together, our findings demonstrate that current disclosure practices fall short of the transparency required for meaningful informed consent. We argue for a significantly updated regulatory framework governing therapy apps in the spirit of the professional and ethical standards that bind licensed human therapists.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.02005v1">Privy: From Fine Print to Fair Practice in Privacy Rights Exercise</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-05-03T18:24:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qi Sun, Ziyang Li, Yinzhi Cao, Yaxing Yao</p>
    <p><b>Summary:</b> Privacy regulations such as the CCPA and GDPR grant individuals rights over their personal data, yet it remains challenging for most users to exercise them in practice due to vague policy interpretation and unapproachable settings on web interfaces. We introduce Privy, an LLM-powered browser assistant that guides users through exercising their privacy rights on websites. Privy automatically analyzes a website's privacy policy and surfaces the specific rights available as action labels in a side panel. When a user selects a right, Privy provides step-by-step guidance and navigation, presenting direct links, generating email templates, or guiding form completion. Users can also request on-demand policy evidence and rights education to enhance their literacy. A technical evaluation across 14 websites shows that Privy extracts rights with high precision (0.979) and completes 96.3\% of privacy tasks in an average of 3.2 steps. A user study (N=15) also demonstrates the overall high-level of perceived helpfulness among users. Our findings suggest that comprehension and usability are not two separate challenges but a single interaction problem, and that effective privacy support requires integration of policy understanding and privacy actions. We offer design suggestions for future privacy assistants.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.01987v1">Misclassification Rate and Privacy-Utility Trade-offs in Graph Convolutional Networks via Subsampling Stability</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-03T17:42:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yexin Zhang, Zhongtian Ma, Qiaosheng Zhang, Zhen Wang</p>
    <p><b>Summary:</b> We study differential privacy (DP) in Graph Convolutional Networks (GCNs) through the framework of \textit{subsampling stability}. We derive upper bounds on the misclassification rate that depend explicitly on the subsampling probability $p_s$. Furthermore, we characterize the \textit{privacy--utility trade-off} by identifying feasible ranges of $p_s$; if $p_s$ is too large, the stability-based privacy condition becomes difficult to satisfy, yielding vacuous guarantees, whereas if it is too small, accuracy deteriorates. Our results provide the first rigorous theoretical framework for understanding subsampling stability in GCNs under DP.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.01810v1">Federated Semi-Supervised Graph Neural Networks with Prototype-Guided Pseudo-Labeling for Privacy-Preserving Gestational Diabetes Mellitus Prediction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-03T10:26:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> G. Victor Daniela, A. Mallikarjuna Reddya, Uday Kumar Addankia, Sridhar Reddy Gogua, Sravanth Kumar Ramakuria</p>
    <p><b>Summary:</b> Gestational Diabetes Mellitus (GDM) is a high-prevalence pregnancy complication that requires accurate early risk stratification to reduce maternal and fetal morbidity. However, real-world clinical deployment of machine learning is hindered by two coupled constraints: (i) label scarcity, where a large fraction of electronic health records (EHR) lack confirmed diagnostic labels, and (ii) data privacy, which prevents sharing patient-level data across hospitals. This paper proposes FedTGNN-SS, a privacy-preserving federated semi-supervised framework for clinical tabular EHR. Each hospital builds a local k-nearest-neighbor patient similarity graph and trains a topology-adaptive GNN encoder. To robustly exploit unlabeled records, FedTGNN-SS combines (1) prototype-guided pseudo-labeling with neighborhood agreement, (2) adaptive graph refinement that periodically updates the k-NN graph using learned embeddings, (3) clinical-aware consistency augmentation applied only to continuous variables, and (4) privacy-safe prototype sharing that exchanges only class-level centroids. Across three diabetes-related datasets (GDM: N = 3,525; Pima: N = 768; Early Stage: N = 520) under 10\%-80\% missing labels per silo, FedTGNN-SS achieves 56 significant wins ($p < 0.05$) against 11 federated baselines and attains strong AUROC under extreme scarcity (Pima: 0.8037 at 80\% missing, Early Stage: 0.9634 at 80\% missing).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.01679v1">Class-Aware Adaptive Differential Privacy in Deep Learning for Sensor-Based Fall Detection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-03T02:34:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joydeb Kumar Sana</p>
    <p><b>Summary:</b> Fall detection is a critical task in healthcare, particularly for elderly people. Timely fall detection and treatment can prevent severe injuries. Sensor-based activity data can be used to detect fall. However, this data are highly sensitive and raises significant privacy concerns. Existing privacy approaches apply uniform noise across all training samples, which affects the prediction performance. To address this limitation, we propose a Class-Aware Adaptive Differential Privacy (CA-ADP) framework integrated with a hybrid 3D Convolutional Neural Network and Bidirectional Long Short-Term Memory (3D CNN-BiLSTM) architecture. The CA-ADP mechanism dynamically adjusts the magnitude of noise added to gradients based on the class composition of each mini-batch. This process ensures privacy while mitigates performance degradation. We formally analyze the $(ε,δ)$-Differential Privacy guarantee and provide a privacy-utility trade-off analysis. The proposed method is evaluated on three public benchmark datasets, namely SisFall, UP-Fall, and MobiAct. The experimental results show that the proposed privacy model achieves improvements of 3.3\%, 8.5\%, and 7.5\% over the conventional privacy-based model in terms of F-score for the SisFall, UP-Fall, and MobiAct datasets, respectively. Comparisons with prior studies show that the CA-AD based framework achieves competitive performance and provides formal privacy guarantees, which are largely overlooked in existing studies. Wilcoxon signed-rank tests confirm that the proposed mechanism consistently outperforms conventional differential privacy. Those results establish the proposed CA-ADP framework as an effective approach to privacy-preserving fall detection in real-world healthcare settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.01217v1">Asymmetric Invertible Threat: Learning Reversible Privacy Defense for Face Recognition</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-05-02T03:18:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiabei Zhang, Ziyuan Yang, Andrew Beng Jin Teoh, Yi Zhang</p>
    <p><b>Summary:</b> Face Recognition systems are widely deployed in real-world applications, but they also raise privacy concerns due to unauthorized collection and misuse of facial data. Existing adversarial privacy protection methods rely on input-space perturbations to obfuscate identity information, yet their protection can degrade when adversaries learn restoration or purification mappings that partially invert the transformation. We study this setting as an asymmetric adversarial attack, in which reverse manipulation becomes feasible because existing defense paradigms do not control reversibility. To address this problem, we propose Asymmetric Reversible Face Protection (ARFP), a restoration-aware extension of personalized face cloaking that integrates privacy protection, keyed recovery, and tamper indication in a single framework. ARFP consists of three components: Key-Conditioned Manifold Binding, which ties the protection transformation to a user-provided key; Adversarial Restoration-Aware Training, which introduces a surrogate restoration adversary during training to improve robustness against evaluated inverse purification attacks; and Authorized Reversible Restoration, which supports recovery with the correct key while providing nonce-based tamper indication. Extensive experiments under the threat models considered in this work show that ARFP improves resistance to the evaluated restoration attacks while preserving authorized recovery utility. These results provide empirical evidence of key-sensitive recovery behavior and tamper awareness in the tested settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.01204v1">FLRSP: Privacy-Preserving Federated Learning Using Randomly Selected Model Parameters</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-02T02:43:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hiroto Sawada, Shoko Imaizumi, Hitoshi Kiya</p>
    <p><b>Summary:</b> In this paper, we propose a method for privacy-preserving federated learning that uses randomly selected model parameters to update global models. High-quality deep neural networks (DNN) models require a huge amount of training data in general, but model training raises privacy concerns when dealing with sensitive or personal information. Federated learning is a distributed machine learning framework in which multiple clients and a server train a model collaboratively. However, if the shared updates are compromised, an attacker may reconstruct the original training data. In addition, previous methods for improving robustness generally reduce the accuracy. To overcome these issues, in our method called federated learning using randomly selected model parameters (FLRSP), model parameters computed in each local server are randomly selected and shared to update a global model in a central server. In experiments, image classification tasks were carried out on the ResNet34 architecture and the Vision Transformer (ViT) under the use of Federated Stochastic Gradient Descent (FedSGD) and Federated Averaging (FedAvg), and the results demonstrated our method's effectiveness in terms of image classification accuracy and robustness against state-of-the-art attacks compared with previous methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.01137v1">Metric-Normalized Posterior Leakage (mPL): Attacker-Aligned Privacy for Joint Consumption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-01T22:27:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gaoyi Chen, Minghao Li, Weishi Shi, Yan Huang, Yusheng Wei, Sourabh Yadav, Chenxi Qiu</p>
    <p><b>Summary:</b> Metric differential privacy (mDP) strengthens local differential privacy (LDP) by scaling noise to semantic distance, but many machine learning (ML) systems are consumed under joint observation, where model-agnostic, per-record guarantees can miss leakage from evidence aggregation. We introduce metric-normalized posterior leakage (mPL), an attacker-aligned, distance-calibrated measure of posterior-odds shift induced by releases, and show that for single or independent releases, uniformly bounding mPL is equivalent to mDP. Under joint observation, however, satisfying mDP may still leave mPL high because learned aggregators compound evidence across correlated items. To make control practical, we formalize probabilistically bounded mPL (PBmPL), which limits how often mPL may exceed a target budget, and we operationalize it via Adaptive mPL (AmPL), a trust-and-verify framework that perturbs, audits with a learned attacker, and adapts parameters (with optional Bayesian remapping) to balance privacy and utility. In a word-embedding case study, neural adversaries violate mPL under joint consumption despite per-record mDP perturbations, whereas AmPL substantially lowers the frequency of such violations with low utility loss, indicating PBmPL as a practical, certifiable protection for joint-consumption settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.01129v1">Revisiting Privacy Leakage in Machine Unlearning: Membership Inference Beyond the Forgotten Set</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-01T21:57:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jie Fu, Nima Naderloui, Da Zhong, Yuan Hong, Wendy Hui Wang</p>
    <p><b>Summary:</b> Machine unlearning (MU) has emerged as a key mechanism for ensuring data privacy and regulatory compliance by enabling models to forget specific training samples. However, recent studies have shown that the removal of data can inadvertently introduce privacy leakages to the retain set,i.e., data that remain in the model after unlearning. In this paper, we extend the scope of privacy analysis in unlearning to the often-overlooked retained data. We introduce TC-UMIA, the first tri-class unlearning membership inference attack. TC-UMIA is a population-level inference framework that leverages model predictions before and after unlearning to distinguish among the forget, retain, and unseen set. Extensive experiments on five state-of-the-art unlearning algorithms and six real-world datasets demonstrate that: (i) unlearning can introduce additional privacy risks to the retain set, making it more susceptible to membership inference attacks; (ii) TC-UMIA is effective across a wide range of model architectures, datasets, and MU approaches. Beyond launching the attack, we rigorously evaluate three defense mechanisms, namely label-only outputs, dropout, and differential privacy, to mitigate the privacy risks posed by TC- UMIA. Our results reveal a fundamental trade-off between privacy protection and model accuracy, with the dropout approach offering the most favorable balance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.00796v1">When RAG Chatbots Expose Their Backend: An Anonymized Case Study of Privacy and Security Risks in Patient-Facing Medical AI</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-05-01T17:29:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alfredo Madrid-García, Miguel Rujas</p>
    <p><b>Summary:</b> Background: Patient-facing medical chatbots based on retrieval-augmented generation (RAG) are increasingly promoted to deliver accessible, grounded health information. AI-assisted development lowers the barrier to building them, but they still demand rigorous security, privacy, and governance controls. Objective: To report an anonymized, non-destructive security assessment of a publicly accessible patient-facing medical RAG chatbot and identify governance lessons for safe deployment of generative AI in health. Methods: We used a two-stage strategy. First, Claude Opus 4.6 supported exploratory prompt-based testing and structured vulnerability hypotheses. Second, candidate findings were manually verified using Chrome Developer Tools, inspecting browser-visible network traffic, payloads, API schemas, configuration objects, and stored interaction data. Results: The LLM-assisted phase identified a critical vulnerability: sensitive system and RAG configuration appeared exposed through client-server communication rather than restricted server-side. Manual verification confirmed that ordinary browser inspection allowed collection of the system prompt, model and embedding configuration, retrieval parameters, backend endpoints, API schema, document and chunk metadata, knowledge-base content, and the 1,000 most recent patient-chatbot conversations. The deployment also contradicted its privacy assurances: full conversation records, including health-related queries, were retrievable without authentication. Conclusions: Serious privacy and security failures in patient-facing RAG chatbots can be identified with standard browser tools, without specialist skills or authentication; independent review should be a prerequisite for deployment. Commercial LLMs accelerated this assessment, including under a false developer persona; assistance available to auditors is equally available to adversaries.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.00562v1">Depth-Guided Privacy-Preserving Visual Localization Using 3D Sphere Clouds</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-05-01T10:59:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Heejoon Moon, Jongwoo Lee, Jeonggon Kim, Je Hyeong Hong</p>
    <p><b>Summary:</b> The emergence of deep neural networks capable of revealing high-fidelity scene details from sparse 3D point clouds has raised significant privacy concerns in visual localization involving private maps. Lifting map points to randomly oriented 3D lines is a well-known approach for obstructing undesired recovery of the scene images, but these lines are vulnerable to a density-based attack that can recover the point cloud geometry by observing the neighborhood statistics of lines. With the aim of nullifying this attack, we present a new privacy-preserving scene representation called \emph{sphere cloud}, which is constructed by lifting all points to 3D lines crossing the centroid of the map, resembling points on the unit sphere. Since lines are most dense at the map centroid, the sphere cloud mislead the density-based attack algorithm to incorrectly yield points at the centroid, effectively neutralizing the attack. Nevertheless, this advantage comes at the cost of i) a new type of attack that may directly recover images from this cloud representation and ii) unresolved translation scale for camera pose estimation. To address these issues, we introduce a simple yet effective cloud construction strategy to thwart new attack and propose an efficient localization framework to guide the translation scale by utilizing absolute depth maps acquired from on-device time-of-flight (ToF) sensors. Experimental results on public RGB-D datasets demonstrate sphere cloud achieves competitive privacy-preserving ability and localization runtime while not excessively compensating the pose estimation accuracy compared to other depth-guided localization methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.00535v1">From Pilot to Precoding Design: Blind Angular Spoofing For Location Privacy in MIMO Systems</a></h3>
  
  <p><b>Published on:</b> 2026-05-01T09:24:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Priyanka Maity, Lorenzo Italiano, Alireza Pourafzal, Gonzalo Seco-Granados, Hui Chen, Monica Nicoli, Henk Wymeersch</p>
    <p><b>Summary:</b> This paper studies location privacy in uplink MIMO systems, where a user equipment seeks to spoof the angular signature observed by a single base station performing localization. We propose a blind analog precoder design that manipulates the perceived angle-of-arrival and angle-of-departure configuration without requiring channel-gain knowledge. The method enforces consistency between the received signal and a desired spoofed angular subspace, and is solved using an alternating optimization algorithm under practical amplitude constraints. Simulations in a multipath scenario show that the proposed approach achieves near-perfect angular spoofing and clearly outperforms pilot-only blind spoofing, which exhibits an error floor. The results also show a trade-off between spoofing accuracy and communication rate, depending on the chosen virtual geometry.</p>
  </details>
</div>



<h2>2026-04</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.00283v1">A Privacy-Preserving Approach to Conformance Checking</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2026-04-30T22:47:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Luis Rodríguez-Flores, Luciano García-Bañuelos, Abel Armas-Cervantes, Astrid Rivera-Partida</p>
    <p><b>Summary:</b> Conformance checking, one of the main process mining operations, aims to identify discrepancies between a process model and an event log. The model represents the expected behaviour, whereas the event log represents the actual process behaviour as captured in information systems records. Traditionally, the process model and the event log are both accessible to the business analyst performing the conformance checking. However, in some contexts, it is necessary to keep either the model or the log private to protect critical or sensitive information. In this paper, we propose a secure approach to conformance checking based on string processing algorithms and homomorphic encryption, where the process model and event log ar not visible to either the model's or event log's owner. The proposed technique is based on alignments, a well-known formalism used for conformance checking. An evaluation is performed using a synthetic and a real-world event log, showing that conformance checking can be securely computed at the expense of high memory and processing requirements.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.00076v1">zkSBOM: Privacy-Preserving SBOM Sharing with Zero-Knowledge Sets</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2026-04-30T13:54:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tom Sorger, Eric Cornelissen, Aman Sharma, Javier Ron, Musard Balliu, Martin Monperrus</p>
    <p><b>Summary:</b> Software Bills of Materials (SBOMs) are increasingly mandated by regulators, yet existing sharing mechanisms impose a binary choice between full disclosure and full opacity. This exposes software suppliers to attacks that can be deduced from the SBOM only, such as the presence of a vulnerable dependency. Conversely, software consumers can be fooled by software suppliers who modify or misrepresent published SBOMs. We present zkSBOM, a privacy-preserving SBOM sharing mechanism designed to address these threats. zkSBOM uses zero-knowledge sets to cryptographically commit to the components within an SBOM. Software consumers can query for known vulnerabilities and receive a cryptographic proof confirming whether the artifact described by the SBOM is affected, without revealing any additional SBOM content. We conduct a security analysis of zkSBOM by quantifying expected leakage from inclusion and exclusion proofs. We demonstrate real-world feasibility by applying it to realistic scenarios and evaluating its operation requirements. Our evaluation demonstrates that zkSBOM is a strong, secure, and privacy-preserving mechanism for SBOM sharing, protecting software suppliers and software consumers from one another.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.27833v1">Taming Noise-Induced Prototype Degradation for Privacy-Preserving Personalized Federated Fine-Tuning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-04-30T13:20:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuhua Wang, Qinnan Zhang, Xiaodong Li, Huan Zhang, Yifan Sun, Wangjie Qiu, Hainan Zhang, Yongxin Tong, Zhiming Zheng</p>
    <p><b>Summary:</b> Prototype-based Personalized Federated Learning (ProtoPFL) enables efficient multi-domain adaptation by communicating compact class prototypes, but directly sharing them poses privacy risks. A common defense involves per-example $\ell_2$ clipping before prototype computation to bound sensitivity, followed by isotropic Gaussian noise to enforce Local Differential Privacy (LDP). However, Isotropic Gaussian Prototype Perturbation (IGPP) typically over-perturbs discriminative dimensions and struggles to balance the clipping threshold with representation fidelity. In this paper, we propose VPDR, a client-side privacy plug-in that seamlessly integrates into existing ProtoPFLs. Motivated by the observation that dimension-wise class variance reflects discriminability, we introduce Variance-adaptive Prototype Perturbation (VPP), which allocates less noise to discriminative subspaces, preserving semantic separability while ensuring privacy. We further develop Distillation-guided Clipping Regularization (DCR), which enables feature norms to adaptively concentrate near the predefined clipping threshold while maintaining prediction consistency. Theoretical analysis shows that our groupwise mechanism provides privacy guarantees no weaker than the isotropic baseline under the same privacy constraints. Extensive experiments on multi-domain benchmarks demonstrate that VPDR achieves a superior privacy-utility trade-off, outperforming IGPP in personalized federated fine-tuning without sacrificing robustness against realistic attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.27598v2">Privacy-Preserving Federated Learning via Differential Privacy and Homomorphic Encryption for Cardiovascular Disease Risk Modeling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-04-30T08:49:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gaurang Sharma, Juha Pajula, Aada Illikainen, Markus Rautell, Noora Lipsonen, Petri Alhainen, Mika Hilvo</p>
    <p><b>Summary:</b> Protecting sensitive health data while enabling collaborative analysis is a central challenge in healthcare. Traditional machine learning (ML) requires institutions to pool anonymized patient records, centralizing analytical development and privacy risks at a single site. Privacy-enhancing technologies (PETs), including Differential Privacy (DP) and Homomorphic Encryption (HE), can mitigate these risks. However, they are mainly studied in conventional data-sharing settings and often introduce trade-offs, including reduced model utility, higher computational cost, and increased implementation complexity. Federated Learning (FL) reduces data centralization by enabling institutions to train models locally and share only model updates. Nevertheless, FL does not eliminate privacy risks, as shared parameters or gradients may still reveal sensitive information. Integrating DP or HE into FL can strengthen privacy guarantees, yet their comparative performance and deployment implications in real-world healthcare settings remain unclear. We systematically evaluated DP and HE integration in FL under real-world conditions, comparing them with standard FL and centralized ML (cML) to quantify privacy-utility trade-offs in multi-institutional settings. Using nationwide Swedish healthcare data, we evaluated cardiovascular disease risk prediction using logistic regression (LR) and neural network (NN) learners. FL with HE achieved performance comparable to cML but introduced measurable cryptographic overhead, particularly in the NN implementation. FL with DP incurred lower computational cost; however, LR was more sensitive to calibrated noise than the NN, resulting in greater performance degradation. Our findings provide practical guidance for deploying privacy-preserving FL in fragmented healthcare systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.27550v1">APPSI-139: A Parallel Corpus of English Application Privacy Policy Summarization and Interpretation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-04-30T07:58:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pengyun Zhu, Qiheng Sun, Long Wen, Yanbo Wang, Yang Cao, Junxu Liu, Deyi Xiong, Jinfei Liu, Zhibo Wang, Kui Ren</p>
    <p><b>Summary:</b> Privacy policies are essential for users to understand how service providers handle their personal data. However, these documents are often long and complex, as well as filled with technobabble and legalese, causing users to unknowingly accept terms that may even contradict the law. While summarizing and interpreting these privacy policies is crucial, there is a lack of high-quality English parallel corpus optimized for legal clarity and readability. To address this issue, we introduce APPSI-139, a high-quality English privacy policy corpus meticulously annotated by domain experts, specifically designed for summarization and interpretation tasks. The corpus includes 139 English privacy policies, 15,692 rewritten parallel corpora, and 36,351 fine-grained annotation labels across 11 data practice categories. Concurrently, we propose TCSI-pp-V2, a hybrid privacy policy summarization and interpretation framework that employs an alternating training strategy and coordinates multiple expert modules to effectively balance computational efficiency and accuracy. Experimental results show that the hybrid summarization system built on APPSI-139 corpus and the TCSI-pp-V2 framework outperform large language models, such as GPT-4o and LLaMA-3-70B, in terms of readability and reliability. The source code and dataset are available at https://github.com/EnlightenedAI/APPSI-139.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.26838v1">Solving Positive Linear Programs with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2026-04-29T16:02:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alina Ene, Huy Le Nguyen, Ta Duy Nguyen, Adrian Vladu</p>
    <p><b>Summary:</b> We study differentially private approximation algorithms for positive linear programs (LPs with nonnegative coefficients and variables), focusing on the fundamental families of packing, covering, and mixed packing-covering formulations. We focus on the high-sensitivity, constraint-private regime of Hsu-Roth-Roughgarden-Ullman (ICALP 2014), where neighboring instances may differ by an arbitrary single constraint, so one cannot hope to approximately satisfy every constraint under privacy. We give private solvers that return approximate solutions while violating only a controlled number of constraints. Our algorithms improve the prior instance-dependent guarantees, and also yield new data-independent bounds that depend only on the dimension. Our techniques involve a dense multiplicative weights update method developed from a regularized dual viewpoint, which we analyze in a way that exploits structure specific to positive LPs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.27014v1">Fidelity, Diversity, and Privacy: A Multi-Dimensional LLM Evaluation for Clinical Data Augmentation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-29T11:32:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guillermo Iglesias, Gema Bello-Orgaz, María Navas-Loro, Cristian Ramirez-Atencia, Mercè Salvador Robert, Enrique Baca-Garcia</p>
    <p><b>Summary:</b> The scarcity of high-quality annotated medical data, particularly in mental health, poses a significant bottleneck for training robust machine learning models. Privacy regulations restrict data sharing, making synthetic data generation a promising alternative. The use of Large Language Models (LLMs) in a data augmentation pipeline could be leveraged as an alternative in this field. In the proposed methodology, DeepSeek-R1, OpenBioLLM-Llama3 and Qwen 3.5 are used to generate synthetic mental health evaluation reports conditioned on specific International Classification of Diseases, Tenth Revision (ICD-10) codes. Because naive text generation can lead to mode collapse or privacy breaches (memorization), a comprehensive evaluation framework is introduced. The generated diagnostic texts are assessed across three dimensions: semantic fidelity, lexical diversity, and privacy/plagiarism. The results demonstrate that all models can generate clinically coherent, diverse, and privacy-safe synthetic reports, significantly expanding the available training data for clinical natural language processing tasks without compromising patient confidentiality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.26525v2">PRAG: End-to-End Privacy-Preserving Retrieval-Augmented Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-29T10:46:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhijun Li, Minghui Xu, Huayi Qi, Wenxuan Yu, Tingchuang Zhang, Qiao Zhang, GuangYong Shang, Zhen Ma, Xiuzhen Cheng</p>
    <p><b>Summary:</b> Retrieval-Augmented Generation (RAG) is essential for enhancing Large Language Models (LLMs) with external knowledge, but its reliance on cloud environments exposes sensitive data to privacy risks. Existing privacy-preserving solutions often sacrifice retrieval quality due to noise injection or only provide partial encryption. We propose PRAG, an end-to-end privacy-preserving RAG system that achieves end-to-end confidentiality for both documents and queries without sacrificing the scalability of cloud-hosted RAG. PRAG features a dual-mode architecture: a non-interactive PRAG-I utilizes homomorphic-friendly approximations for low-latency retrieval, while an interactive PRAG-II leverages client assistance to match the accuracy of non-private RAG. To ensure robust semantic ordering, we introduce Operation-Error Estimation (OEE), a mechanism that stabilizes ranking against homomorphic noise. Experiments on large-scale datasets demonstrate that PRAG achieves competitive recall (72.45%-74.45%), practical retrieval latency, and strong resilience against graph reconstruction attacks while maintaining end-to-end confidentiality. This work confirms the feasibility of secure, high-performance RAG at scale.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.26390v2">Meta-Learning and Targeted Differential Privacy to Improve the Accuracy-Privacy Trade-off in Recommendations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-04-29T08:00:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Peter Müllner, Dominik Kowald, Markus Schedl, Elisabeth Lex</p>
    <p><b>Summary:</b> Balancing differential privacy (DP) with recommendation accuracy is a key challenge in privacy-preserving recommender systems, since DP-noise degrades accuracy. We address this trade-off at both the data and model levels. At the data level, we apply DP only to the most stereotypical user data likely to reveal sensitive attributes, such as gender or age, to reduce unnecessary perturbation; we refer to this as targeted DP. At the model level, we use meta-learning to improve robustness to remaining DP-noise. This achieves a better trade-off between accuracy and privacy than standard approaches: Meta-learning improves accuracy and targeted DP leads to lower empirical privacy risk compared to uniformly applied DP and full DP baselines. Overall, our findings show that selectively applying DP at the data level together with meta-learning at the model level can effectively balance recommendation accuracy and user privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.26184v1">Privacy-Preserving Clothing Classification using Vision Transformer for Thermal Comfort Estimation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-29T00:18:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tatsuya Chuman, Yousuke Udagawa, Hitoshi Kiya</p>
    <p><b>Summary:</b> A privacy-preserving clothing classification scheme is presented to enable secure occupant-centric control (OCC) systems. Although the utilization of camera images for HVAC control has been widely studied to optimize thermal comfort, privacy protection of occupant images has not been considered in prior works. While various privacy-preserving methods have been proposed for image classification, applying conventional schemes results in severe accuracy degradation. In this paper, we introduce a privacy-preserving classification method using Vision Transformer (ViT) applied to clothing insulation estimation. In an experiment using the DeepFashion dataset categorized by clothing insulation, while the conventional pixel-based method suffers a severe accuracy drop, our scheme maintains a high accuracy on encrypted images, showing no degradation from plain images across all categories.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.26073v1">Privacy-Preserving Federated Learning Framework for Distributed Chemical Process Optimization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> 
  <p><b>Published on:</b> 2026-04-28T19:26:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Teetat Pipattaratonchai, Aueaphum Aueawatthanaphisut</p>
    <p><b>Summary:</b> Industrial chemical plants often operate under strict data confidentiality constraints, making centralized data-driven process modeling difficult. Federated learning (FL) provides a promising solution by enabling collaborative model training across distributed facilities without sharing raw operational data. This paper proposes a privacy-preserving federated learning framework for distributed chemical process optimization using data collected from multiple geographically separated plants. Each plant locally trains a neural-network-based process model using its own time-series sensor data, while only model parameters are transmitted to a central aggregation server through secure aggregation mechanisms. This design allows cross-plant knowledge sharing while maintaining strict data locality and industrial confidentiality. Experimental evaluation was conducted using process datasets from three independent chemical plants operating under heterogeneous conditions. The results demonstrate rapid convergence of the federated model, with the global mean squared error decreasing from approximately 2369 to below 50 within the first five communication rounds and stabilizing around 35 after 40 rounds. In comparison with local-only training, the proposed federated framework significantly improves prediction accuracy across all plants, while achieving performance comparable to centralized training. The findings indicate that federated learning provides an effective and scalable solution for collaborative industrial analytics, enabling privacy-preserving predictive modeling and process optimization across distributed chemical production facilities.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.00036v1">Cross-level Privacy Preserving Utility Mining</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2026-04-28T06:41:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiahong Cai, Wensheng Gan, Philip S. Yu</p>
    <p><b>Summary:</b> Privacy-preserving utility mining (PPUM) aims to hide sensitive high-utility patterns while preserving the utility of the sanitized database. In practice, however, many datasets are associated with taxonomic information, which makes the identification and processing of generalized items more challenging. To address this, we investigate the cross-level privacy-preserving utility mining (CLPPUM) problem and propose a method for protecting generalized items. Based on different victim item selection strategies, we develop three CLPPUM algorithms: minimum RGISU first (Min-RF), maximum RGISU first (Max-RF), and best NSC first (Best-NSCF). Furthermore, to enable efficient victim item identification, a novel dictionary structure named GI-dic is designed to accelerate the computation of required utility metrics. Experimental results on multiple datasets demonstrate that the proposed algorithms successfully hide all sensitive cross-level high-utility itemsets without introducing artificial itemsets. The results also show that our method performs well on sparse datasets, and both Min-RF and Best-NSCF consistently outperform Max-RF. Overall, Min-RF achieves the best performance, particularly when the minimum utility threshold is low and the dataset is dense.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.24982v1">"We Wanted to Do Better Than the Law": Exploring UI/UX Designers' Privacy Advocacy in Practice</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-04-27T20:37:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Keyu Yao, Jinghui Cheng, Jin L. C. Guo</p>
    <p><b>Summary:</b> Designers hold primary responsibility for shaping the user interface (UI) and user experience (UX) of a product. This role goes beyond aesthetics and usability, extending to the privacy outcomes of user experience, which often emerge through collaboration with other stakeholders such as developers, product managers, and marketing teams. Previous studies on enhancing privacy for technological products primarily focused on the roles of developers -- understanding their needs and challenges -- but limited effort is devoted to examining how UI/UX designers consider and approach privacy in their work. Through 12 semi-structured interviews with privacy-advocating UI/UX designers, we explore the perceptions, influencing factors, challenges, and adaptive methods they use regarding privacy implementation. We pay special attention to how these challenges and adaptations play out in team-based settings where decisions are negotiated together. Our study reveals how personal and contextual factors shape designers' value of privacy, the collaborative nature of the challenges designers face when trying to prioritize privacy, and how they navigate tensions between business goals, team dynamics, and technical development. Based on our findings, we discuss implications for advocating a user-centered approach for supporting privacy-aware design, suggestions for organizational-level changes and bridging knowledge gaps through designer-centric tools and community building.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.24724v2">Data-Driven Privacy-Preserving Modeling and Frequency Regulation with Aggregated Electric Vehicles via Bilinear Hidden Markov Model</a></h3>
  
  <p><b>Published on:</b> 2026-04-27T17:34:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yiping Liu, Xiaozhe Wang, Geza Joos</p>
    <p><b>Summary:</b> Vehicle-to-Grid (V2G) technology allows bidirectional power flow for real-time grid support, making electric vehicles (EVs) well-suited for ancillary services such as frequency regulation. However, existing methods for flexibility estimation and coordinating aggregated EVs often rely on individual EV traveling information (e.g., arrival/departure time) and/or characteristic parameters (e.g., charging efficiency, battery capacity) as well as real-time state-of-charge (SOC), which raises privacy concerns and faces data quality issues. To address these challenges, this paper proposes a data-driven, privacy-preserving modeling and control framework for frequency regulation using aggregated EVs. The proposed method can provide accurate estimation for power outputs and flexibility of aggregated EVs and carry out effective frequency regulation without any individual EV information. Simulation results validate the accuracy and effectiveness of the proposed method, which also outperforms the model-based and federated learning-based method under SOC data inaccuracies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.24468v1">A Survey on Split Learning for LLM Fine-Tuning: Models, Systems, and Privacy Optimizations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-04-27T13:36:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zihan Liu, Yizhen Wang, Rui Wang, Xiu Tang, Sai Wu</p>
    <p><b>Summary:</b> Fine-tuning unlocks large language models (LLMs) for specialized applications, but its high computational cost often puts it out of reach for resource-constrained organizations. While cloud platforms could provide the needed resources, data privacy concerns make sharing sensitive information with third parties risky. A promising solution is split learning for LLM fine-tuning, which divides the model between clients and a server, allowing collaborative and secure training through exchanged intermediate data, thus enabling resource-constrained participants to adapt LLMs safely. % In light of this, a growing body of literature has emerged to advance this paradigm, introducing varied model methods, system optimizations, and privacy defense-attack techniques for split learning. To bring clarity and direction to the field, a comprehensive survey is needed to classify, compare, and critique these diverse approaches. This paper fills the gap by presenting the first extensive survey dedicated to split learning for LLM fine-tuning. We propose a unified, fine-grained training pipeline to pinpoint key operational components and conduct a systematic review of state-of-the-art work across three core dimensions: model-level optimization, system-level efficiency, and privacy preservation. Through this structured taxonomy, we establish a foundation for advancing scalable, robust, and secure collaborative LLM adaptation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.24326v1">X-NegoBox: An Explainable Privacy-Budget Negotiation Framework for Secure Peer-to-Peer Energy Data Exchange</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-04-27T11:18:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Poushali Sengupta, Sabita Maharjan, Frank Eliassen, Yan Zhang</p>
    <p><b>Summary:</b> The decentralization of modern energy systems is transforming consumers into prosumers who continuously exchange data with aggregators, peers, and market operators. While such data is essential for peer-to-peer trading, demand response, and distributed forecasting, it can reveal sensitive household patterns and introduce privacy risks. Existing data sharing mechanisms rely on fixed policies or predefined differential privacy budgets, limiting their ability to adapt to variations in reliability, data sensitivity, and request purpose. As a result, prosumers rarely receive explanations for why a request is accepted, rejected, or modified, reducing trust and participation.
  To address these limitations, we propose X-NegoBox, an explainable negotiation framework for adaptive privacy budgeting and transparent decision making. Each prosumer data is managed locally within a private DataBox, where raw data remain confined. Incoming requests are processed by an Autonomous Privacy Budget Negotiation Protocol (APBNP), which determines an appropriate privacy budget based on trust, feature sensitivity, declared purpose, historical behavior, and risk-aware pricing. When needed, APBNP generates privacy-preserving counter-offers, such as reduced resolution or duration.
  An Explainable Agreement Layer (X-Contract) produces human- and machine-readable justifications for each decision. After agreement, requester code executes locally in a sandbox, and only sanitized outputs are shared. Experiments on realistic energy market settings show reduced privacy leakage, higher acceptance rates, and improved interpretability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.24203v1">Agentic Witnessing: Pragmatic and Scalable TEE-Enabled Privacy-Preserving Auditing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2026-04-27T09:07:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Antony Rowstron</p>
    <p><b>Summary:</b> Auditing the semantic properties of proprietary data creates a fundamental tension: verification requires transparent access, while proprietary rights demand confidentiality. While Zero-Knowledge Proofs (ZKPs) ensure privacy, they are typically limited to precise algebraic constraints and are ill-suited for verifying qualitative, unstructured properties, such as the logic within a codebase. We propose {\em Agentic Witnessing}, a framework that moves verification from attested execution to {\em attested reasoning}. The system is composed of three agents: a Verifier (who wants to check properties of a dataset), a Prover (who owns the dataset) and an Auditor (that inspects the dataset). The Verifier is allowed to ask a limited number of simple binary true/false questions to the auditor. By isolating an LLM-based Auditor within a Trusted Execution Environment (TEE), the system enables the Verifier to query a Prover's private data via simple Boolean queries, without exposing the raw dataset. The Auditor uses the Model Context Protocol (MCP) to dynamically inspect the target dataset, producing a yes/no verdict accompanied by a cryptographic transcript: a signed hash chain binding the reasoning trace to both the original dataset and the TEE's hardware root of trust. We demonstrate this architecture by automating the artifact evaluation process for 21 peer-reviewed computer science papers with released codebases on GitHub (e.g. Does the codebase implement the system described in the paper?). We verified five high-level properties of these codebases described in the corresponding publications, treating the source code as private. Our results show that TEE-enabled agentic auditing provides a mechanism for privacy-preserving oversight, effectively decoupling qualitative verification from the need for data disclosure.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.24066v1">Listen to the Voices of Everyday Users: Democratizing Privacy Ratings for Sensitive Data Access in Mobile Apps</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-04-27T05:47:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Liu Wang, Tianshu Zhou, Haoyu Wang, Yi Wang</p>
    <p><b>Summary:</b> Mobile apps frequently request excessive data access, raising significant privacy concerns. While regulations like GDPR emphasize data minimization, they provide limited guidance on concretely defining and enforcing necessary data access. Existing regulatory mechanisms primarily rely on expert-driven audits that face challenges in scalability, neutrality, and alignment with user expectations. In this paper, we propose a novel paradigm--democratizing privacy assessment, inspired by prior work on user-centric privacy perceptions--which repositions users as active evaluators in the privacy auditing process, recognizing that user perceptions of data usage play a crucial role in assessing the appropriateness and necessity of data access. To operationalize this paradigm, we introduce DePRa, a prototype system developed through participatory design, featuring contextual explanation provision, category-based representative selection, an intuitive rating interface, and preference-based rating adjustment. We evaluated DePRa with 200 everyday mobile app users, analyzing how effectively it captures user opinions on sensitive data access, comparing their privacy ratings with expert assessments, and exploring risk preference-based score calibration. Our findings show the feasibility and promise of democratized privacy assessment, highlighting its potential to complement expert auditing and support inclusive privacy evaluation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.23847v1">Privacy-preserving Meta-analysis through Low-Rank Basis Hunting</a></h3>
  
  <p><b>Published on:</b> 2026-04-26T19:32:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenqi Shi, Kosuke Imai, Yi Zhang</p>
    <p><b>Summary:</b> A central challenge of meta-analysis is that the populations underlying existing studies often differ from the target population in unknown ways. We study the problem of predicting function-valued quantities, such as regression and conditional average treatment effect functions, for a new target population using only study-level covariates and estimates. We propose MetaHunt, a new meta-analysis methodology based on a shared low-rank structure, in which the true function from each study lies within the convex hull of a small set of latent basis functions. To recover these basis functions, we extend the Successive Projection Algorithm to the functional setting, incorporating a denoised basis-hunting step. We establish consistency of the recovered basis functions under mild regularity conditions. We then model the relationship between study-level covariates and the corresponding mixing weights using flexible semi-parametric or non-parametric methods. MetaHunt is privacy-preserving and enables meta-analytic prediction based on study-level information alone, even when individual-level data are unavailable to analysts. In addition, for each study, functions of interest can be estimated using possibly different machine learning algorithms. For uncertainty quantification, we construct prediction intervals via conformal prediction. We show that, under exchangeability and mild estimation-error conditions, these intervals achieve asymptotically valid marginal coverage. We demonstrate the effectiveness of MetaHunt through both simulation studies and empirical applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.23795v1">LLM-CEG: Extending the Classification Error Gauge Framework for Privacy Auditing of Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-26T16:39:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kato Mivule</p>
    <p><b>Summary:</b> This paper extends the Classification Error Gauge (x-CEG) framework, originally developed for measuring the privacy-utility trade-off in tabular datasets, to privacy auditing of Large Language Models (LLMs). We propose LLM-CEG, a systematic framework that employs membership inference attack (MIA) success rates as an empirical privacy gauge and model perplexity as a utility gauge, iteratively adjusting differential privacy parameters until both thresholds are jointly satisfied. A proof-of-concept prototype fine-tunes DistilGPT-2 on a synthetic clinical PII dataset under four privacy regimes using DP-SGD. Results indicate that DP-SGD reduces MIA attacker advantage by 71.5% while simultaneously improving out-of-distribution utility by 47-50% relative to the overfitted baseline, suggesting that differential privacy may act as implicit regularization under narrow fine-tuning conditions. We further extend the SIED engineering framework to the LLM context as LLM-SIED, providing an auditable, regulator-aligned process for privacy-compliant LLM deployment.</p>
  </details>
</div>

