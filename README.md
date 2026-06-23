
<h2>2026-05</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.01386v1">GuidaPA: Privacy-Preserving Chatbot for Public Administration via Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-31T18:20:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Daniel M. Jimenez-Gutierrez, Albenzio Cirillo, Raffaele Nicolussi, Alessio Beltrame, Andrea Vitaletti</p>
    <p><b>Summary:</b> We present GuidaPA, a privacy-preserving chatbot for the Italian Public Administration (PA) trained via Federated Learning (FL) on documentation from two national PA platforms, SIGESON and SIDFORS. Our corpus includes approximately 8 pages of SIGESON manuals and 31 pages of SIDFORS manuals/FAQs; while this study uses public documentation as a safe proxy, the intended deployment extends to restricted internal sources (e.g., tickets, officer manuals, database extracts) that can not be centrally pooled due to regulatory and organizational constraints. GuidaPA integrates role-based access control, secure client-side preprocessing, explicit monitoring of non-IID effects, and parameter-efficient federated fine-tuning of large language models. Using QLoRA (4-bit) over 15 federated rounds with an 80/20 train-test split per client, we evaluate answer quality with ROUGE, BLEU-4, and METEOR. The best federated model achieves ROUGE-1/2/L of 61.10/55.77/59.44, BLEU-4 of 45.02, and METEOR of 63.94-close to private centralized fine-tuning while keeping data on-site. Compared to the general-purpose baseline, domain fine-tuning improves ROUGE-1 from 41.45 to 62.18 and BLEU-4 from 26.97 to 50.90. Overall, the results indicate that FL can deliver high-quality conversational AI for public services without centralized data sharing</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.01225v1">Privacy-Preserving Smart Surveillance with Cross-Dataset Violence Detection and Decentralized Evidence Governance</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-31T13:16:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hasan Coşkun, Furkan Çolhak, Andrea Kulakov, Vesna Dimitrova</p>
    <p><b>Summary:</b> AI-enabled surveillance can accelerate public-safety response, yet most systems still leave recorded evidence under centralized administrative control. This paper proposes a privacy-preserving smart surveillance framework that separates incident detection from evidence disclosure. A lightweight MobileNetV2-based video classifier detects violent clips, while each recorded incident segment is immediately encrypted and made accessible only through threshold-based approval. The decryption key is split with Shamir's Secret Sharing, member shares are protected with public-key cryptography, and voting is supported by time-limited tokens, two-factor authentication, signatures, and audit logs. This study evaluates MobileNetV2+LSTM, MobileNetV2+BiLSTM, and MobileNetV2+temporal CNN heads on SCVD, RWF-2000, and Real-Life Violence Situations under seven in-domain and cross-dataset scenarios. The best all-source model, MobileNetV2+BiLSTM, reaches 93.5% test accuracy and ROC-AUC 0.980% on the merged held-out set, while lower RWF-2000 slice performance confirms persistent dataset shift.</p>
  </details>
</div>



<h2>2026-06</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.23230v1">Privacy-Preserving Person Re-Identification from Temporal Sequences with Transformer and Hungarian Optimization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-06-22T12:18:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Raphaël Delécluse, Hazem Wannous, Laurent Guimas</p>
    <p><b>Summary:</b> Person re-identification (Re-ID) is a crucial task in surveillance and human behavior analysis, often used in public spaces such as transport hubs. Traditional RGB-based Re-ID methods raise privacy concerns and are highly sensitive to lighting variations and occlusion. In this paper, we propose a novel Re-ID approach that leverages depth images, which inherently obscures facial and other identifiable features, making it a privacy-preserving solution. Our method addresses the association problem between multiple views of individuals by applying the Hungarian algorithm, optimizing the matching process through minimization of the global cost across the distance matrix. We further enhance the approach by introducing temporal sequences of frames as input to a Transformer encoder architecture, which exploits both RGB and depth modalities. This architecture captures dynamic movement patterns, improving feature extraction and re-identification accuracy. Additionally, we employ batch hard triplet loss to enhance discriminative feature learning by focusing on the hardest samples. We evaluate both depth-only and RGB-D models on several top-view datasets, including TVPR2, GODPR, and BIWI RGBD-ID. Our results demonstrate that depth-only re-identification can achieve competitive performance compared to state-of-the-art methods, as measured by standard metrics such as Cumulative Matching Characteristics (CMC) and Mean Average Precision (mAP), while prioritizing privacy preservation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.23217v1">MuPPET: A Benchmark for Contextual Privacy of LLM Assistants in Multi-Party Conversations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-22T12:06:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Elena Sofia Ruzzetti, Cornelius Emde, Sangdoo Yun, Seong Joon Oh, Martin Gubri</p>
    <p><b>Summary:</b> LLM agents are increasingly deployed in multi-party environments, handling sensitive personal data on behalf of individual users, for instance in group chats. When such an agent discloses private information, it reaches every group member at once. This risk is structurally harder to control than in one-to-one settings, as every piece of private information must be appropriate for every recipient in the group. Yet all existing contextual privacy benchmarks consider only single-interlocutor settings, leaving multi-party privacy risks unmeasured. We introduce MuPPET (Multi-Party Privacy Exposure Testing), a benchmark for contextual privacy in multi-party conversations. Our experiments show that models leak substantially more in multi-party settings than one-to-one evaluations suggest. Frontier models are vulnerable, and smaller open-weights models, often preferred for local deployment with sensitive data, even more so. Existing contextual privacy defences offer only partial protection, degrade utility, and do not resolve the underlying party-tracking problem.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.23096v1">Minimax Quantile Lower Bounds for Interactive Statistical Decision Making with Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-06-22T09:41:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Raghav Bongole, Amirreza Zamani, Tobias J. Oechtering, Mikael Skoglund</p>
    <p><b>Summary:</b> Minimax risk and regret are expectation-based criteria and do not capture rare but consequential failures. To address this concern, we develop a $δ$-explicit minimax-quantile theory for interactive statistical decision making (ISDM). We first provide structural relations between minimax quantiles, lower minimax quantiles, and minimax risk. This includes a quantile-to-expectation conversion and an equivalence between strict and lower minimax quantiles outside a countable set of confidence levels. We then derive two converse tools for ISDM: a high-probability interactive Fano's method and a high-probability interactive Le Cam's method. Then, we show that mutual-information (MI) privacy can be handled in the same framework by restricting the admissible decision class. For coordinatewise Gaussian privatization, we derive a two-point template that isolates the privacy-induced variance inflation. We instantiate this template for Gaussian mean estimation, and use the same two-point strategy directly for two-armed Gaussian bandits. We then derive a minimax quantile lower bound for the $K$-armed Gaussian bandit problem, showing that the interactive Fano method captures the exploration cost over multiple possible best arms. The resulting lower bounds are explicit in the confidence level $δ$ and in the privacy budget for the private problems. They yield $\log(1/δ)/n$ scaling for squared-error Gaussian mean estimation, $\sqrt{T\log(1/δ)}$ scaling for two-armed bounded-mean Gaussian bandits, and $\sqrt{KT\log(1/δ)}$-type scaling for the $K$-armed bandits, with privacy appearing through a Gaussian variance-inflation factor for the private problems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.22928v1">HADES: Privacy-Preserving Federated Learning via Selective Feature Encryption and Hybrid Model Fusion</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-22T07:05:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ergün Batuhan Kaynak, Kerem Bayramoglu, Sinem Sav</p>
    <p><b>Summary:</b> In this paper, we address the challenge of privacy-preserving training in federated learning (FL) by introducing a novel framework that selectively encrypts only the most privacy-sensitive features while leaving the remaining data and the corresponding model portion unencrypted. We propose HADES, a hybrid system that identifies and encrypts the most critical features, ensuring both privacy protection and computational efficiency. Unlike fully encrypted FL training pipelines, which suffer from high computational overhead, HADES integrates an encrypted and non-encrypted training pipeline via a fusion mechanism, enabling seamless interaction between encrypted and plaintext model representations. To achieve this, we use PCA to identify and encrypt the most privacy-sensitive features, which significantly reduces reconstruction attack success in FL. Building on this insight, we design a hybrid FL system that trains an end-to-end encrypted network via multiparty homomorphic encryption (MHE) on the selected features while simultaneously training a plaintext network on the remaining features. These two networks are then integrated using a fusion mechanism. We also introduce a general packing scheme that eliminates redundant rotations by considering the entire neural network architecture. Finally, we demonstrate that HADES matches the accuracy of vanilla FL while preserving privacy and achieving optimized runtime through selective encryption.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.22699v1">Catching Lies Without Sending the Video: Privacy-Preserving Multimodal Deception Detection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Multimedia-5BC0EB">
  <p><b>Published on:</b> 2026-06-21T22:30:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nikita Sharma, Pranav Sara, Karan Singla</p>
    <p><b>Summary:</b> Frontier multimodal models can guess whether a person is lying from a testimony video. To do so, they stream that raw face and voice to a third-party model. We ask whether the heavy media is needed at all. On the Real-life Trial Deception dataset, Whissle on-device speech and vision stack extracts a compact digest: transcript, emotion, age, gender, intent distributions, a deception intent filter, fluency and rhythm, per-frame facial behaviour, and prosody. Under speaker-independent evaluation, we report three findings. A small classifier on this digest reaches AUC 0.741, matching Gemini 2.5 Pro on full video. Handing the digest to a frontier LLM reaches AUC 0.755 with Claude Opus 4.8 at 7.8X fewer input tokens, with no media leaving the device. The reported 75% accuracy is a speaker-leakage artifact. We release code and experiments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.22311v1">Semantic Non-Assembly: Privacy by Architectural Inertness Under Component Exposure</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-06-21T02:40:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sam Ryan</p>
    <p><b>Summary:</b> Existing privacy frameworks emphasize confidentiality, access control, appropriate information flow, or statistical disclosure limitation. We introduce a complementary class of privacy guarantee (Semantic Non-Assembly) in which privacy is characterized not by the difficulty of achieving exposure but by the information yield of exposure when it occurs. SNA prevents evaluation of a designated predicate by preventing any sub-threshold coalition from assembling a sufficient assignment to its input domain. An architecture satisfies Semantic Non-Assembly when no coalition of fewer than a defined threshold of components can assemble such an assignment: complete exposure and decryption of any sub-threshold component yields no actionable data. In the base protocol, the guarantee is structural: it operates through architecture, not policy, and its privacy properties degrade predictably under component compromise rather than collapsing at a single point. The reference instantiation combines this structural guarantee with audited organizational constraints, as characterized in Appendix A. This paper formalizes the guarantee and establishes four ProVerif-verified properties: Device Non-Correlation, Registry Observer Non-Identification, Submission Server Blindness, and Active Defense Gate correctness, the first three through a two-channel provenance architecture. The Birthmark Standard instantiates the guarantee on constrained capture hardware, demonstrating deployability where ZK-based approaches are computationally infeasible. All formal properties and scope limitations are documented in Appendix A.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.21757v1">AdaPrivate-TS: Private Thompson Sampling for Contextual Bandits with Privacy Amplification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2026-06-19T21:18:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohammadreza Riyazat, Eranga Ukwatta</p>
    <p><b>Summary:</b> We present AdaPrivate-TS, a differentially private contextual bandit algorithm that combines Thompson Sampling with batched zCDP composition. Our key insight is that differential privacy noise inflates the posterior covariance in a structured way: adding Gaussian noise $N(0,σ^2 I)$ to $b$ yields sampling covariance $v^2 A^{-1} + σ^2 A^{-2}$, which Thompson Sampling interprets as increased uncertainty rather than pure corruption. Under event-level privacy (protecting individual interactions) with stochastic contexts, we prove that the privacy cost is only $O(\sqrt{d}\,\log T/\sqrtρ)$, logarithmic in $T$, because parallel composition amortizes noise across batches. Additionally, we explore privacy amplification via Poisson subsampling, which can reduce effective noise at stringent privacy budgets. Experiments on synthetic and real-world datasets demonstrate: (1) AdaPrivate-TS achieves 93-99% of non-private performance at $\varepsilon \in [0.5, 5]$, outperforming UCB by 0.5-3.7% and up to 18% with tuned adaptive exploration at extreme $\varepsilon$; (2) privacy amplification provides additional 2-5% gains at low $\varepsilon$; (3) on MovieLens and Jester, AdaPrivate-TS achieves the best overall performance among event-level baselines, dominating at $\varepsilon \geq 2$; (4) under DP-SVD private features, TS's advantage over UCB grows to +11%, confirming noise-as-uncertainty is not limited to reward privacy. We provide rigorous proofs for privacy guarantees under interactive zCDP composition and comprehensive evaluation including convergence curves, 12-seed CIs, and DP-SVD feature ablation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.21710v1">PrivacyAlign: Contextual Privacy Alignment for LLM Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2026-06-19T19:50:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Manveer Singh Tamber, Abhay Puri, Marc-Etienne Brunet, Perouz Taslakian, Jimmy Lin, Spandana Gella</p>
    <p><b>Summary:</b> AI agents acting on behalf of users are constantly making decisions, and for users to trust their agents, those decisions must align with what they actually want. Privacy is an important alignment problem for agents: every message, post, or tool call an agent makes is a contextual judgment about what is appropriate to share, with whom, and under which conditions. Because such judgments depend on social expectations and norms, human judgment does not merely label privacy violations but also helps define them. While existing work relies on unreliable proxies for both training and evaluation, we place human judgment at the center of agentic privacy alignment. We introduce PrivacyAlign, a dataset of 1,350 samples with 3,516 detailed annotations from 599 unique annotators across diverse scenarios where current LLMs actually leak, and use it to ground both alignment training and automated evaluation in human privacy norms. Building on these annotations, we first show that conditioning LLM judges on human annotations and explanations for reference responses to the same prompt makes their judgments more reliable. We then introduce annotation-conditioned reward modeling, which uses these annotations to score new responses during RL, and show that small open-weight agents trained with this reward better align with human privacy norms, with strong gains on PrivacyAlign and existing privacy benchmarks for agents.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.21524v1">Prophet Inequalities under Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB">
  <p><b>Published on:</b> 2026-06-19T15:22:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Achraf Azize, Mathieu Molina, Hugo Richard, Vianney Perchet</p>
    <p><b>Summary:</b> Many online decision platforms, from hiring marketplaces to auctions, face a tension between efficient decision-making and the protection of participants' privacy. Personal information, such as a candidate's test score or a bidder's valuation linked to protected data, is sensitive, and fear of data resale or reputational harm can make participants reluctant to share it. Furthermore, platforms can be untrusted or even incentivized to resell data, making local privacy guarantees that do not rely on a trusted centralized curator preferable. We initiate the study of optimal stopping and prophet inequalities under local differential privacy (LDP). Each of $n$ independent arriving values is observed only through reports generated by an $\varepsilon$-LDP mechanism. The decision maker must design the $\varepsilon$-LDP mechanisms, and choose an irrevocable stopping time to maximise the expected selected true value. We characterize the optimal online stopping rule under LDP and show that simple binary mechanisms suffice: an optimal LDP stopping rule can be implemented via a randomized-response-type report and a dynamic-programming threshold rule. We then quantify performance via tight competitive ratios against two benchmarks. Relative to the optimal non-private online policy, we prove a tight worst-case competitive ratio of $e^{\varepsilon}/(n - 1 + e^{\varepsilon})$, interpolating between $1/n$ (full privacy) and $1$ (no privacy). Relative to an LDP prophet, who designs $\varepsilon$-LDP mechanisms but observes the full privatized sequence before deciding what to select, we prove a tight competitive ratio of $(1 + e^{-\varepsilon})/2$, interpolating between $1$ (full privacy) and the classical $1/2$ bound (no privacy). Notably, increasing privacy shrinks the LDP prophet's advantage faster than it degrades online performance, closing the performance gap.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.21513v1">Privacy-Preserving Federated Temporal Graph Learning with Digital Twin--Guided Adaptive Deception for Cyber-Resilient IoMT</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-06-19T15:09:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Syed Zeeshan Haider, Anwar Shah, Muneeb Arif, Hamza Iftikhar, Waqas Ali</p>
    <p><b>Summary:</b> The rapid proliferation of IoT and IoMT devices introduces critical cybersecurity vulnerabilities in healthcare and industrial environments where resource-constrained devices operate under strict latency and data-privacy regulations. This paper presents the Federated Temporal Graph Convolutional Network with Advantage Actor-Critic (Federated TGCN-A2C), a privacy-preserving defense architecture integrating four mechanisms: a PyG-based Temporal GCN using GCNConv layers with global mean pooling and a learned anomaly gate for flow-level threat classification; LSTM-based Digital Twins generating per-device anomaly scores gating the classifier via learned sigmoid coupling; a Federated A2C agent selecting among ALLOW, ISOLATE, and HONEYPOT-REDIRECT actions based on a seven-dimensional state capturing confidence, entropy, anomaly magnitude, and traffic composition; and an enhanced honeypot layer converting suspicious traffic into threat intelligence with adaptive thresholds. Federated aggregation employs EMA-smoothed per-client validation losses as inverse-weighted FedAvg coefficients to stabilize global model updates under non-IID distributions, with cosine-annealed learning rates per round. Evaluated on CICDDoS 2019 and TON-IoT benchmarks, the framework achieves 99.48% and 99.61% test accuracy with weighted-F1 scores of 0.9948 and 0.9961, converging within 25 and 10 federated rounds, outperforming Fed-Inforce-Fusion by 0.21 percentage points while covering three additional attack categories. All sixteen CICDDoS 2019 classes achieve F1 of at least 0.9237 and all ten TON-IoT classes achieve F1 of at least 0.9488, including the severely imbalanced MITM category. Post-hoc explainability via SHAP, LIME, Grad-CAM, and counterfactual analysis confirms decisions are grounded in semantically meaningful flow features, supporting regulatory accountability in clinical deployments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.21338v1">"What Happens Locally, Leaks Globally": Detecting Privacy Leakage Risks in MCP Servers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-19T11:35:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Biwei Yan, Minghui Xu, Yijun Yang, Boyang Ma, Xuelong Dai, Jingku Li, Yue Zhang</p>
    <p><b>Summary:</b> The Model Context Protocol (MCP) has rapidly become the de facto standard for connecting large language models (LLMs) to external resources, but it also introduces a class of privacy risks that existing tools are ill-equipped to detect. Unlike conventional exfiltration bugs, leakage in MCP servers is largely protocol-induced: credentials, API keys, and Personally Identifiable Information (PII) cross the local/LLM boundary simply by being returned, logged, or raised inside a tool handler, with no explicit outbound request in the source code. We present MCPPrivacyDetector, a context-aware cross-language static analysis framework that detects such leakage in multilingual MCP servers. MCPPrivacyDetector lifts heterogeneous code implemented across different programming language (e.g., Python) into a unified program representation, applies context-aware semantic filtering to isolate genuinely sensitive values and protocol-specific implicit sinks (e.g., @mcp.tool handlers), and performs taint analysis to enumerate feasible flows. Applied to 10,655 real-world MCP servers, MCPPrivacyDetector finds leakage rates above 10%. Case studies confirm concrete exposures including leaked Bearer tokens, propagated API keys, and plaintext authentication credentials, arguing for systematic, protocol-aware safeguards in the emerging LLM agent toolchain.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.20553v1">From Efficiency to Leakage -- Privacy Backdoor in Federated Language Model Fine-Tuning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-18T17:58:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shanghao Shi, Chaoyu Zhang, Heng Jin, Yang Xiao, Yevgeniy Vorobeychik, William Yeoh, Ning Zhang, Y. Thomas Hou, Wenjing Lou</p>
    <p><b>Summary:</b> Federated learning (FL) enables multiple parties to collaboratively fine-tune language models for domain-specific tasks without sharing raw data. Since full model fine-tuning is often prohibitively expensive for FL clients, parameter-efficient fine-tuning (PEFT) has become the de facto approach in practice, freezing the base model and training only a small set of adapters. In this paper, we show that a malicious parameter server can stealthily corrupt a PEFT adapter into a privacy backdoor that implicitly memorizes the client's training samples as isolated per-sample parameter updates stored in separate neurons, without degrading model utility. Concretely, our attack, NeuroImprint, assigns a dedicated memorization neuron to each training sample and constrains that each neuron is updated at most once along the local fine-tuning trajectory. This design mitigates both cross-sample collisions and cross-step mixing introduced by large local batches and stateful optimizers (e.g., Adam/AdamW) in language-model fine-tuning. After fine-tuning, the resulting isolated per-sample updates can be analytically inverted in closed form to recover text embeddings, which are then deterministically mapped back to token sequences. To understand the generality of our method, we implemented NeuroImprint on multiple language models (BERT, GPT-2, Qwen2, and Llama3.2) and evaluated it across four fine-tuning datasets spanning diverse domains. The results demonstrate that our attack can reconstruct 59% to 79% of all finetuning samples with high semantic fidelity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.20546v1">Predictability as a Fine-Grained Measure for Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-06-18T17:55:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Linda Lu, Karthik Sridharan</p>
    <p><b>Summary:</b> Differential privacy (DP) ensures rigorous individual-level privacy guarantees against even the most knowledgeable attackers, but its worst-case nature can impose a costly privacy-accuracy tradeoff. We introduce privacy via predictability, a fine-grained framework that explicitly incorporates the attacker's core knowledge, a compromised portion of the dataset generated by a stochastic process, and a specified family of queries. Predictability measures privacy leakage as the incremental gain in an attacker's ability to predict sensitive information about unknown individuals after observing the algorithm's output, beyond what can already be inferred from the compromised data. We show that predictability and DP are generally incomparable: each can be small while the other is large. However, in the worst-case regime where all but one individual is compromised, and all binary queries are considered sensitive, predictability implies mutual-information DP. More generally, predictability provides a finer-grained privacy metric tailored to specific sensitive information and specific attacker models. We introduce a general framework, using the generalized method of moments (GMM), to analyze asymptotic predictability when the compromised data is generated by a stationary, ergodic, mixing process. Using this analysis, we derive a predictability-calibrated output perturbation scheme for ERM. Our approach is complementary to DP and can be used alongside DP to provide fine-grained privacy control.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.20344v1">Quantum ring all-reduce: communication and privacy advantages for distributed learning</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-06-18T15:13:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> María Gragera Garcés, Lirandë Pira</p>
    <p><b>Summary:</b> Machine learning models have scaled to unprecedented sizes, making training across distributed devices the de facto standard in the field. In this work, we explore how quantum communications can make distributed training both more communication-efficient and information-theoretically private, for both classical and quantum learning models. Ring all-reduce is the foundational communication primitive for large-scale distributed training. We present a quantum version that reduces per-link online communication by a provably optimal factor of two using pre-shared entanglement and superdense coding, without requiring the learning model or gradient computation to change. Beyond bandwidth, the primitive enables privacy guarantees that are information-theoretically impossible for any classical protocol, achieving composable ε-secure aggregation, via verified entanglement, at a 2x overhead in GHZ copies. Our hybrid quantum-classical communication architecture yields simultaneous communication and security advantages for large scale distributed training, regardless of whether the learning itself is quantum or classical. Finally, we characterise quantum advantages in gradient conflict detection for server-to-client communication under bandwidth constraints, a setting that arises after ring all-reduce is completed, when full gradient broadcast to external clients is infeasible. Two variants of the problem admit different separations. For margin-based alignment testing (\textsc{GapIP}_τ), the quantum advantage is quadratic in the margin parameter: \widetilde{O}(τ^{-1}\log P) qubits versus \widetilde{O}(\min(\τ^{-2},P)) bits. For sign-consistency auditing against a private parameter matching (\textsc{TieAudit}_ε), the advantage represents an exponential separation in communication complexity: Ω(\sqrt{P}) bits whereas O(ε^{-2}\log P) qubits suffice.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.20760v1">Privacy-Preserving Compliance on Public Ledgers via Selective Disclosure Authorization Schemes</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-18T09:38:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Supriya Khadka, Sanchari Das</p>
    <p><b>Summary:</b> Public distributed ledgers enforce integrity through radical transparency, creating tension with data minimization principles required for regulatory compliance. While Zero-Knowledge Proofs (ZKPs) offer a theoretical privacy solution, existing constructions often overlook adversarial constraints in smart contract environments. Specifically, the asynchronous decoupling of off-chain proof generation from on-chain submission introduces front-running and proof-reuse risks in public mempools. In this work, we formalize Selective Disclosure Authorization Schemes (SDAS), a cryptographic primitive for granular and revocable compliance checks on public ledgers without revealing the underlying witness. We define a security model for SDAS, introducing Ledger-Bound Attribute Unlinkability and Context-Aware Sender Binding to capture how valid proofs remain bound to their intended authorization context. To validate sender binding, we present ZK-Compliance, an Ethereum-based instantiation that operationalizes a user-controlled "Grant, Verify, Revoke" lifecycle. We implement the sender-binding component using a 14-constraint Circom circuit that anchors the zero-knowledge proof to the executing on-chain sender address. Our Sepolia evaluation confirms practical viability: browser-based proof generation executes in under 200 ms, and on-chain verification costs 240,512 gas, neutralizing proof reuse by different callers while preserving strict attribute privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.19620v1">G-Lox: Group-Adaptive, Privacy-Preserving Bridge Distribution with Two-Party Computation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-17T21:55:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Baigang Chen, Nicholas Hopper</p>
    <p><b>Summary:</b> We present G-Lox (group-adaptive Lox), a bridge-distribution system that preserves Lox-style distributor blindness while enabling hidden, stateful group-level adaptation. G-Lox places adaptive assignment logic behind a two-server privacy wall, so no single server learns group identifiers or group-to-bridge assignments. Private state access and state-dependent updates use two-server DPF/FSS protocols and secure two-party computation, supporting blockage reporting, transport-aware reassignment, and privacy-preserving group splitting.
  We evaluate G-Lox through system measurements and policy simulation. In our C++/EMP implementation over real TCP sockets, private state access has low client-visible overhead: across state sizes up to 2^16, communication remains in the low-KiB range per iteration. At M=1024, the client sends 1,968 bytes, receives 1,280 bytes, and completes an iteration in about 0.25 s. Simulations with group-specific blocking and Sybil enumeration show that G-Lox improves robustness over Lox- and rBridge-like baselines among systems that maintain broad issuance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.18996v2">TRAP: Benchmark for Task-completion and Resistance to Active Privacy-extraction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-17T12:17:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Moon Ye-Bin, Nam Hyeon-Woo, Baek Seong-Eun, Yejin Yeo, Tae-Hyun Oh</p>
    <p><b>Summary:</b> Agents are increasingly deployed in document-intensive workflows where sensitive private information is not an edge case but a routine input, e.g., an agent booking a flight needs passport numbers. In such settings, the agent must use private information to complete tasks accurately while never exposing it in its responses, because it cannot verify who is actually at the keyboard. These two obligations are in fundamental tension. A model capable enough to use private information for task completion can, by the same capability, be induced to reveal it. To evaluate the trade-off of task accuracy and privacy leakage, we introduce Task-completion and Resistance to Active Privacy-extraction (TRAP). Each scenario includes a document containing private information, a task query that requires the agent to invoke the correct tool using private fields, and an attack query that attempts to elicit the same information in natural language. Evaluating 22 models spanning frontier proprietary and open-source models at multiple scales, we find that all model families exhibit non-trivial leakage, and that instruction-following ability correlates with leakage rate. Existing prompt-based defenses reduce leakage but at significant cost to task accuracy. Prompt optimization fails to escape this trade-off. We demonstrate that this failure is not incidental. For any softmax-based model, no soft-constraint defense, e.g., prompt-based defenses, can jointly achieve high task success with zero leakage probability. Motivated by this impossibility result, we propose structural private field isolation, which replaces private fields with hash keys before they reach the model. This approach largely prevents leakage while keeping task accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.20732v1">Balanced Workforce: Governance-by-Design for Privacy-Preserving Inter-Firm Workforce Leasing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-06-17T10:50:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Melody Amaizu, Martin Stojkovski, Ariton Verush</p>
    <p><b>Summary:</b> Workforce demand is uneven across organizations. Project-based companies may simultaneously face skill shortages in one unit while other firms hold underutilized employees with relevant expertise. Conventional hiring, contracting, and temporary agency models address parts of this problem, but they also create legal, ethical, organizational, and data-governance risks. This paper reframes a seminar project called Balanced Workforce into a governance-by-design framework for privacy-preserving inter-firm workforce leasing. The proposed Balanced Workforce Leasing Service (BWLS) enables companies to list temporary talent availability, discover anonymized skill profiles, negotiate assignments, and document agreements through locally deployed connectors and a minimal central coordination layer. The framework combines socio-technical governance, enterprise architecture, business model design, e3value-based value exchange modeling, and privacy-by-design principles. The paper presents the system concept, stakeholder model, process phases, architecture, business model, value network, and legal, ethical, and operational risk analysis. It argues that workforce leasing platforms should not be designed only as marketplaces. They require consent mechanisms, traceability, role-based access control, data minimization, contractual safeguards, dispute handling, and institutional accountability. The contribution is a structured framework and design artifact for future research on governed digital labor infrastructures. The paper does not claim deployment results or empirical validation; instead, it provides a design framework that can be evaluated through expert review, stakeholder workshops, prototype testing, and regulatory analysis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.18518v1">PSyGenTAB: A Privacy-Preserving Framework for Synthetic Clinical Tabular Data Generation via Constrained Optimization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-16T22:14:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arshia Ilaty, Hossein Shirazi, Manasi Chitale, Kedar Hegde, Dhanalakshmi Ramesh, Rashmi S. Manjunath, Amir Rahmani, Hajar Homayouni</p>
    <p><b>Summary:</b> The development of medical AI is constrained by limited access to high-quality clinical data due to institutional silos and strict privacy regulations such as HIPAA and GDPR. Synthetic data generation offers a potential solution, but existing methods lack principled mechanisms to explicitly manage the privacy-utility trade-off, often degrading clinically meaningful patterns or risking patient re-identification. We present PSyGenTAB, a privacy-preserving generative framework that formulates synthetic healthcare data generation as a constrained optimization problem solved using the Augmented Lagrangian Method. By embedding configurable privacy constraints directly into model training, PSyGenTAB enforces minimum privacy thresholds while maximizing clinical data utility. Across multiple clinically motivated benchmarks, PSyGenTAB preserves inter-feature clinical relationships and minority-class diagnostic patterns essential for reliable health AI. Downstream evaluation using Train-on-Synthetic, Test-on-Real and Train-on-Real, Test-on-Synthetic protocols shows that models trained on synthetic data achieve performance comparable to those trained on real patient records. Privacy auditing further demonstrates reduced exact record reproduction and strong resilience to membership inference attacks. These results establish PSyGenTAB as a principled framework for balancing privacy protection and clinical utility in synthetic healthcare data, supporting secure cross-institutional AI development.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.18062v1">Security and Privacy Prompts in the Wild: What Users Ask LLMs and How LLMs Respond</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-06-16T15:37:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hobin Kim, Xiaoyuan Wu, Omer Akgul, Lujo Bauer, Nicolas Christin</p>
    <p><b>Summary:</b> Large language models (LLMs) are widely used to fulfill users' information needs; users ask LLMs about the weather, pose educational questions, and consult them for legal assistance. One particularly understudied area is digital security and privacy (S&P), where users may seek LLMs' help on how to secure their online accounts or protect their computers from cyber attacks. To the best of our knowledge, no prior study has collected or analyzed the S&P questions users ask LLMs; prior research on LLM response quality relied on expert-authored S&P misconceptions or FAQs rather than user queries. Drawing from WildChat, a dataset of 3.2M user-LLM conversations collected in the wild, our study identifies 14,727 S&P prompts and categorizes them into nine categories covering a wide range of S&P topics. From the S&P prompts, we sampled 450 and performed a thematic analysis to characterize the S&P questions users ask LLMs. Separate from the thematic analysis, we curated 270 advice-seeking S&P prompts, where users ask for recommendations, guidance, or specific S&P information. We measured LLM response quality and consistency when posing the prompt to LLMs 10 times. We found that commercial LLMs outperform open-weight models (GPT 5.5 provided "good enough" responses on 98% of prompts; Llama 4 on 47%). However, among prompts that received high-quality responses on average, commercial models sometimes produce contradictory responses across runs, risking confusing or misleading users.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.17995v1">Differential Privacy of Gaussian Process Posterior Sampling</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-06-16T14:43:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tomasz Maciazek</p>
    <p><b>Summary:</b> We study the privacy of releasing posterior sample paths from a Gaussian process (GP) when the entire training set including covariates and responses is private. Unlike standard differential-privacy (DP) mechanisms that add external noise, posterior sampling is random by construction. We show that this intrinsic randomness yields DP guarantees by deriving explicit Rényi-DP bounds for GP posterior sample-path release. The bounds separate posterior-mean leakage from data-dependent posterior-covariance leakage showing that meaningful privacy depends sharply on effective ridge regularisation. We apply membership-inference attacks to show that empirical leakage follows the predicted dependence on regularisation, posterior variance and the number of released posterior sample-paths. Utility experiments on downstream posterior-sampling tasks identify noisy-observation regimes where privacy-compatible regularisation preserves useful decisions with modest utility loss. When stronger privacy is needed, the intrinsic guarantee can be sharpened by adding calibrated GP noise, providing an explicit additional privacy knob.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.17421v1">Bifrost: Hybrid TEE-FHE Inference for Privacy-Preserving Transformer and LLM Serving</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-16T02:06:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chenghao Chen, Kailun Qin, Xiaolin Zhang, Chi Zhang, Dawu Gu</p>
    <p><b>Summary:</b> Cloud-hosted transformer and large language model (LLM) inference creates a direct confidentiality problem: user prompts may contain sensitive code, business data, personal information, or regulated documents, yet remote serving exposes intermediate state to the cloud software stack and accelerator runtime. Fully homomorphic encryption (FHE) keeps accelerator-side execution ciphertext-only, but end-to-end LLM inference remains expensive because linear layers are interleaved with non-linear, cache-state, and refresh-sensitive operators. CPU trusted execution environments (TEEs) can execute those operators natively, but a CPU TEE alone does not define how an untrusted accelerator should participate.
  We present Bifrost, a hybrid TEE-FHE serving architecture in which secrets are provisioned only to an attested CPU TEE, while the accelerator, device memory, driver/runtime stack, and host software remain outside the trusted computing base. Bifrost uses FHE as a secure delegation mechanism for projection and feed-forward linear layers on accelerator-backed CKKS, while non-linear operators, attention-side control logic, KV-state transitions, and decrypt-then-encrypt refresh execute inside the CPU TEE.
  Bifrost+ further applies a prefill/decode split: prompt-side KV state is built inside the CPU TEE, and only decode-side state enters the hybrid ciphertext path. In an estimator-style comparison matching Euston's methodology, Bifrost reduces projected latency by 9.25x on GPT-2 (1.5B) and 9.91x on LLaMA 3 (8B). In direct CKKS/FHE deployments, Bifrost+ reduces TTFT by 14.6-45.8x on GPT-2 (124M) and 15.3-53.4x on Qwen3 (0.6B). The systems lesson is selective encrypted execution: use FHE only where ciphertext-only accelerator delegation is required, and keep non-linear, refresh, and prompt-side work inside the CPU TEE.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.17387v1">Supporting the Adoption of Privacy-Enhancing Technologies through Requirements Engineering</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2026-06-16T00:49:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Oleksandr Kosenkov, Vadym Honcharenko, Abhinava Singh, Volodymyr Spirin, Danica Vranjanin</p>
    <p><b>Summary:</b> In recent decades, privacy-enhancing technologies (PETs) have been recognized as a means of meeting regulatory and user privacy requirements in software systems that process personal data. Despite substantial research efforts, support from regulators, contributions by large technology companies such as Google and Microsoft, and growing interest among software practitioners, the practical adoption of PETs remains limited. Existing research consistently identifies recurring challenges to PETs adoption in SE, such as technical complexity and insufficient training. Despite ongoing research efforts, these challenges largely remain unresolved in practice.
  In this industrial challenge paper, we apply a practical, requirements engineering (RE)-driven perspective to examine challenges to PET adoption across multiple stakeholder groups (PET developers, integrators, and adopters) as well as across different disciplinary perspectives (engineering, law, and business).
  We argue that RE can facilitate the adoption of PETs by systematically addressing each of the complementary engineering, business, and legal viewpoints on privacy. Neglecting challenges in any of these viewpoints (e.g., the impact of PETs on software architecture, their business implications, and their contribution to regulatory compliance) can increase the impediments or even lead to implementation failure. In practice, explicit specification of these viewpoints within RE can enable meaningful coordination among stakeholders to more effectively realize the benefits of PETs in software engineering.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.17297v1">Scalable K-clique Estimation with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2026-06-15T21:06:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dung Nguyen, Ritwick Mishra, Anil Vullikanti</p>
    <p><b>Summary:</b> Counts of $k$-cliques are commonly used metrics in subgraph mining. Since graphs often have sensitive data, there also has been a lot of work on $k$-clique counts with differential privacy. However, these metrics have very high global sensitivity, and so more sophisticated techniques have been developed for counting $k$-cliques with privacy. Smooth sensitivity and ladder functions were developed for reducing the noise magnitude for private estimates of these metrics. However, these are computationally very inefficient to estimate. No polynomial time algorithms are known for smooth sensitivity of $k$-cliques for $k>3$, while the time complexity of ladder functions is lower bounded by the time for exact counts, which does not scale very well.
  In this paper, we develop a new highly scalable algorithm for estimating $k$-clique counts with differential privacy. Our algorithm adapts the ladder function to serve as a smooth upper bound on its local sensitivity, and utilizes the approximation sensitivity framework to calibrate noise with magnitude proportional to an approximation of the bound. This gives us a significant improvement in the running time. Experiments show that our method is several orders of magnitude faster than the ladder function based estimates of $k$-clique counts, while the accuracy is similar. Our algorithm is the first to scale to graphs with millions of edges, and for larger $k$, for which the ladder function algorithm doesn't complete.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.17035v1">Your Privacy My Cloak: Backdoor Attacks on Differentially Private Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-15T17:53:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaolin Li, Ning Wang, Ninghui Li, Wenhai Sun</p>
    <p><b>Summary:</b> Prior research suggests that differential privacy (DP) inherently enhances the robustness of federated learning (FL) against backdoor attacks. In this paper, we challenge this assumption. Through an empirical analysis of two baseline attack strategies, we uncover a fundamental tension in DP-FL: while bypassing DP allows state-of-the-art defenses to detect and filter malicious updates, complying with DP inadvertently masks their distinguishing statistical characteristics. Consequently, existing defenses become ineffective as DP reduces the raw backdoor signal. Building on this masking effect, we propose RING, a novel attack that explicitly exploits DP to conceal malicious contributions while maximizing attack impact. By collaboratively crafting adversarial perturbations, compromised clients reconstruct a strong backdoor signal during aggregation without triggering anomaly detection. RING operates as a perturbation layer that is agnostic to the underlying backdoor technique, making it broadly applicable and composable with existing attacks -- a property that significantly amplifies the threat it poses to DP-FL. Extensive evaluations across four image and text datasets under non-iid distributions show that RING achieves an average attack success rate of 90.3% against six state-of-the-art defenses under a moderate privacy budget, an improvement of up to 26.08x over baseline strategies. Finally, we evaluate potential countermeasures and find that mitigating this threat incurs significant utility trade-offs, exposing a fundamental security gap in the deployment of differentially private FL.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.16943v1">Di5Guise: 5G Privacy with vSIM</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-06-15T16:44:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shirin Ebadi, Zach Moolman, Eric Keller, Tamara Lehman</p>
    <p><b>Summary:</b> SIM cards have been the key building block of user authenticationand security in cellular networks. While they are meant to serve as privacy protecting elements in cellular communications, they can be the root cause of privacy loss. Current eSIMs come with a fixed device profile--comprising a secret key, a certificate, and a unique eUICC identifier--that permanently binds every subscriber profile provisioned on the device to that device profile. This binding enables an attacker with the vantage point of a cellular operator to correlate subscriber identities back to a single device, piecing together a complete pattern of life--online activities, movement patterns, and real-world identity--even when users rotate subscriber identities or employ traffic obfuscation techniques. To mitigate this concern, we introduce Di5Guise, a privacy-enhancing architecture that breaks this correlation at its root by decoupling the device identity from the subscriber identity. Central to Di5Guise is vSIM, a virtualized SIM card that enables dynamic device profile provisioning, allowing each subscriber profile to be associated with a distinct, unlinkable device profile. Di5Guise establishes trust with the operator by ensuring that vSIM is running on secure hardware in a trustworthy state. We prototype Di5Guise on a Field Programmable Gate Array (FPGA) board and integrate it with srsRAN to demonstrate full compatibility with existing 5G infrastructure. Using a complex user correlation model, we show that Di5Guise reduces user re-identification accuracy from 93% to 49% when combined with obfuscation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.16878v3">Integrated Marketing Attribution: A Bayesian Framework for Privacy-Safe Granular Measurement Anchored in MMM</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-06-15T15:52:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Meghana R. Bhat, Ankit Umare, Utsav Aggarwal, Richard Vecsler, Arunkumar Mani, Karthik Nair, Chandhu Nair</p>
    <p><b>Summary:</b> Retail marketing measurement increasingly requires granular campaign-level insights without relying on user-level tracking. However, the two dominant approaches, Marketing Mix Modeling (MMM) and Multi-Touch Attribution (MTA), often produce fragmented insights. MMM is privacy-safe and robust for channel-level planning but is too coarse for campaign optimization, while MTA provides granular attribution but has become less reliable under increasing privacy restrictions. We propose Integrated Marketing Attribution (IMA), a unified framework that combines MMM with channel specific Bayesian attribution models to derive campaign-level effects from aggregated data. By leveraging MMM-informed priors, IMA delivers granular, privacy-safe attribution while preserving consistency with MMM.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.16801v1">The Art of Mixology: Mixup-based Obfuscation for Privacy-Preserving Split Learning in Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-06-15T14:42:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chen Chen, Xiang Gao, Xianshun Wang, Chengran Li, Shengyu Xia, Xueluan Gong, Linru Zhang, Qian Wang, Kwok-Yan Lam</p>
    <p><b>Summary:</b> Split learning provides a practical paradigm for resource-constrained users to train Large Language Models (LLMs) by offloading computation-intensive layers to a server while keeping raw data local. However, existing privacy-preserving split learning methods still face a difficult trade-off among utility, privacy, efficiency, and stability. Specifically, these methods often suffer from substantial utility degradation, remain vulnerable to advanced data reconstruction attacks, incur prohibitive computational and communication overhead, or exhibit unstable performance across different tasks. In this paper, we propose MIXGUARD, a novel mixup-based privacy-preserving split learning framework for LLMs. MIXGUARD introduces token-level obfuscation, representation-level obfuscation, and adaptive gradient perturbation mechanisms, which operate jointly to preserve useful learning signals while preventing privacy leakage to the server. Technically, MIXGUARD first constructs a lightweight calibration model on a public dataset to refine the approximated target representation, and then applies this model during privacy-preserving fine-tuning on private data. We conduct extensive experiments on four classification tasks and four text generation tasks across multiple LLM families, model sizes, architectures, and fine-tuning strategies. The results show that MIXGUARD preserves model utility comparable to non-split training baselines, consistently achieves stronger privacy protection than existing split learning defense methods against state-of-the-art data reconstruction attacks, and remains robust under adaptive attack settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.16788v1">SoK: Security and Privacy of Foundation-Model-Powered Robots</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E">
  <p><b>Published on:</b> 2026-06-15T14:32:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xueluan Gong, Chen Chen, Jinxin Liu, Qian Wang, Kwok-Yan Lam</p>
    <p><b>Summary:</b> Foundation models are reshaping robotics by enabling robots to interpret open-ended instructions, reason over multimodal contexts, and operate in complex, open-world environments. However, their integration also introduces security and privacy (S&P) risks that extend beyond the FMs themselves to embodied execution pipelines, supporting ecosystems, and broader governance impacts. Existing literature reviews provide valuable insights but often focus on specific FM types, risk categories, mitigation strategies, or trust boundaries. Consequently, the field lacks a unified structure for analyzing where risks originate, how they propagate across robotic systems, and where mitigations should intervene. To address this gap, we propose a progressive F-E-S-G structural boundary framework for analyzing the S&P of FM-powered robots. The framework comprises four layers: the Foundation model layer (F), Embodied system layer (E), Supporting ecosystem layer (S), and Governance impact layer (G). Building on this structure, we develop a multi-level taxonomy that organizes prior studies along three levels: F-E-S-G trust boundary, security-privacy concerns, and risk-mitigation perspectives. We further annotate each study using fine-grained coding attributes, including target, lifecycle stage, mechanism, system access, and effect. Guided by this framework and taxonomy, we systematize 96 papers. Our analysis uncovers multiple threat patterns, defense mismatches, and evaluation gaps that are difficult to identify from a single-boundary perspective. Based on these findings, we identify open challenges and future directions to provide a research agenda for developing secure, privacy-preserving, and responsibly governed FM-powered robotic systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.16763v1">Cross-Silo De-Anonymization Under Local Differential Privacy: Threat Model, Phase Transition, and Coordination Necessity</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-06-15T14:15:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ziniu Liu, Aiping Li</p>
    <p><b>Summary:</b> When a person's records appear in k independent data silos, each protected by (epsilon, delta)-differential privacy, standard composition yields a valid (k*epsilon, k*delta)-DP guarantee for the joint output. This worst-case bound, however, does not answer the concrete inference question: at what k can an adversary actually identify a target person? This paper develops the information-theoretic framework needed to answer that question.
  We introduce cross-silo person-level DP (XSP-DP), a Pufferfish-style privacy notion whose adjacency relation captures all records of a single person across all silos simultaneously, and verify that the standard basic composition bound carries over to this adjacency model. Within this framework we prove that de-anonymization undergoes a phase transition at k* = Theta(log n / epsilon^2) (population size n, per-silo RR parameter epsilon): a Fano lower bound shows any estimator fails for k << k*, while a matching maximum-likelihood upper bound shows the attack succeeds for k >> k*. An explicit XOR + randomized-response construction demonstrates information synergy: each silo's output is individually uninformative about the target, yet the joint mutual information is strictly positive. For non-coordinated binary randomized-response mechanisms, we prove that de-anonymization is inevitable once k exceeds the threshold, establishing that cross-silo coordination is necessary.
  These results provide a baseline threat model and Theta-level threshold for cross-silo inference attacks under local DP.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.16488v1">An Energy-Driven Framework for Privacy-Aware Synthetic Data Generation</a></h3>
  
  <p><b>Published on:</b> 2026-06-15T09:55:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pierpaolo Massoli, Fabio Spagnuolo</p>
    <p><b>Summary:</b> The increasing demand for access to microdata in official statistics and data-intensive applications raises important challenges concerning disclosure risk, inferential validity and preservation of statistical utility. This paper proposes an interpretable energy-driven framework for privacy-aware synthetic data generation in mixed-type data. The proposed methodology combines discriminative modelling, Bayesian-Network proposal mechanisms, Metropolis--Hastings sampling and post-generation optimization within a constrained probabilistic framework. Unlike perturbation-based approaches, privacy-aware behaviour is achieved through constrained stochastic exploration guided by explicit plausibility, privacy, diversity and structural-coherence penalties. The framework is specifically designed for mixed-type tabular data characterized by sparse configurations, heterogeneous variable types and complex multivariate dependency structures. The generation process is formulated as a multi-objective sampling problem balancing statistical fidelity and disclosure-risk while preserving predictive utility. An extensive empirical evaluation is conducted using a mixed-type individual-level dataset containing demographic, behavioural and health-related variables. The validation strategy combines statistical fidelity diagnostics, predictive analyses, diversity measures, nearest-neighbour risk analysis, membership inference attacks and Split Conformal Prediction. The empirical results suggest that the proposed framework is capable of preserving a substantial portion of the predictive and multivariate structure of the original data while limiting exact memorization phenomena and maintaining favourable privacy-aware behaviour. The proposed methodology provides an interpretable framework for synthetic data generation under competing utility and privacy constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.16461v1">Privacy from Symmetry: Orthogonally Equivariant Transformers for LLM Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-06-15T09:31:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alexander Yukhimchuk, Andrey Shulga, Mladen Kolar, Martin Takáč</p>
    <p><b>Summary:</b> Running large language models locally is often impractical, pushing inference on sensitive text to third-party providers. Split inference partially mitigates this by keeping tokens on the client and sending only hidden representations, but these representations can still be recovered via nearest-neighbor search against the public embedding table. We propose an orthogonal obfuscation procedure in which the client multiplies embeddings by a secret orthogonal matrix before transmission. To enable correct inference under arbitrary rotations, we introduce ConjFormer, a transformer variant that is exactly $\mathrm{O}(d)$-equivariant via a lightweight normalization change (scalar RMSNorm) together with blockwise orthogonal conjugation of all linear weights. As a result, the server performs the full forward pass entirely in the rotated basis and never observes unrotated hidden states. Experiments on GPT-2 and Llama 3.2 1B models fine-tuned on PubMed show that orthogonal obfuscation eliminates direct cosine nearest-neighbor inversion and reduces token recovery from over 35% top-10 to at most 1.3%, while increasing perplexity by only 0.4% after fine-tuning. These results indicate that enforcing symmetry at the architectural level can provide a practical defense for privacy-preserving LLM inference without noise injection or heavy cryptographic machinery.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.15947v1">The Privacy Externality of Disclosing Correlated Data</a></h3>
  
  <p><b>Published on:</b> 2026-06-14T18:05:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rui Sun</p>
    <p><b>Summary:</b> A firm that discloses data about one customer moves a downstream seller's belief about every correlated customer, pricing third parties it never transacts with. This privacy externality equals the change in downstream deadweight loss, is signed by which side of the pricing threshold a customer is on, and falls hardest on those just carried across. Disclosure is privately optimal on an open set of imperfect correlations; incentive compatibility prices it through a distorted allocation and rations the discount at the top under a continuum of types. Selling tips disclosure past a liquidity threshold; consent dominates both data minimization and laissez-faire.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.15940v1">Causal-Privacy Audit Workflow for Synthetic and Distilled Data in Dropout Support</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-06-14T17:44:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hanghang Zheng, Xiwei Zhuang, Zhong Wang, Hong Liu, Xiao Chen, Jingwen He, Xia Li</p>
    <p><b>Summary:</b> Synthetic and distilled student data are increasingly used to enable privacy-conscious learning analytics, yet their suitability for decision-facing institutional support remains uncertain. In dropout support, generated data must preserve not only predictive utility or distributional resemblance, but also the financial-status evidence used to guide advising, payment-plan assistance, and scholarship-related decisions. Method: This study introduces CaP-Eval, a decision-facing causal-privacy audit workflow for evaluating generated student data under a fixed estimand, timing-aware adjustment design, estimator set, and empirical privacy-governance screen. The workflow compares original, distilled, adversarial synthetic, statistical synthetic, and DPGNet privacy-oriented generated data on predictive utility, treatment-effect fidelity, robustness to alternative estimators, and local training-record proximity. Results: DPGNet and distilled data preserved the original financial-status treatment-effect structure more reliably than the adversarial and Gaussian Copula baselines. DPGNet preserved full direction and rank agreement across epsilon levels; epsilon = 10 produced the smallest non-original IPW and DML deviations, while epsilon = 1 and epsilon = 5 amplified several financial-status contrasts. Distilled data remained highly faithful but retained the strongest local training-record proximity signal. TabularGNet preserved qualitative directions with moderate attenuation, and Gaussian Copula compressed effect magnitudes. Conclusions: Predictive utility, privacy orientation, empirical disclosure signals, and causal fidelity diverged; generated student data require joint audits of direction, magnitude, overlap, and release-governance risk before decision use.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.15335v1">Privacy-Preserving Text Sanitization for Distributed Agents Collaboration via Disentangled Representations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-13T14:55:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xuan Liu, Hefeng Zhou, Sicheng Chen, Chao Yang, Xingcheng Xu, Jingjing Qu, Jiong Lou, Jie LI, Xia Hu</p>
    <p><b>Summary:</b> When distributed agents exchange text across organizational boundaries, privacy leakage arises not only from explicit identifiers but also from distributional signatures such as formatting conventions, vocabulary choices, and syntactic patterns. We propose DiSan(Disentangled Sanitization), a privacy-preserving sanitization framework and a built-in component of Intern-Shannon for multi-agent collaboration. DiSan uses a two-stream encoder to factorize text into a source-invariant role subspace that preserves task semantics and a source-identifying style subspace that remains local. Federated proto-type alignment and adversarial regularization enable joint training without centralizing raw text. Experiments show that identifier-level masking is insufficient: masking 19.2% of tokens reduces TF-IDF stylometric attribution by only 18.6%. By contrast, DiSan reduces answer-level PII exposure by 20 times while maintaining 83% answer faithfulness on a distributed multi-agent RAG benchmark, and lowers Enron stylometric attribution by 73.2% under TF-IDF and 70.6% under a neural probe.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.14518v1">Behavioral Audit of Machine Unlearning Has a Privacy Cost</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-06-12T14:49:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Liou Tang, James Joshi, Ashish Kundu</p>
    <p><b>Summary:</b> The removal of learned data from Machine Learning models through Machine Unlearning (MU) has been widely studied; however, there has yet to be an agreed-upon scheme for auditing MU. Existing work has shown that a dishonest model owner can falsify evidence to avoid executing MU, while curious auditors (and adversaries) can infer the privacy-sensitive properties of the model and its training data even with limited access. Yet auditing of MU under mutual distrust between the model owner and the auditor remains unexplored. We provide an information-theoretic proof for this scenario: for convex ML models, a generic audit scheme that relies solely on querying the model for \textit{behavioral} signals cannot identify insufficiently unlearned models without revealing membership information of the retained set. Therefore, auditing MU under the assumption of a dishonest model owner and an honest-but-curious auditor faces an inherent privacy-audit tradeoff. Our empirical results on convex models strongly supports this result, while further experiments demonstrate that this privacy-audit tension persists in non-convex models. Our results call for a more careful consideration of the privacy-audit tension under a realistic auditor threat model, and serve as a foundation for more scrutiny of designs of privacy-preserving audit schemes for the MU pipeline. We also release our code implementation at https://github.com/LiouTang/Behavioral-Unlearn-Audit.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.14453v1">Redistricting from the Bottom Up: Sampling Communities of Interest with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-06-12T13:39:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Atticus McWhorter, Caroline Hammond, Nianqiao Phyllis Ju, Daryl DeFord</p>
    <p><b>Summary:</b> Independent Redistricting Commissions (IRCs) are a promising tool for bottom-up redistricting, but their public testimony processes are vulnerable to adversarial manipulation. We propose using differential privacy to draw redistricting plans that incorporate community of interest (COI) testimonies while remaining robust to adversarial input. Treating individual testimonies as data points, we use the marked edge walk to sample from differentially private distributions of redistricting plans via the exponential mechanism. We introduce two score functions and demonstrate that both can be targeted by MEW across a range of privacy budgets. Applying this method to Missouri's mid-cycle redistricting using 808 COI testimonies, we show that COI-informed sampling outperforms an uninformed baseline and the enacted plan. An adversarial experiment demonstrates that the method can be robust to attacks under certain privacy budgets and may perform better in practice than formal group privacy guarantees imply. We also find that stronger COI preservation tends to spread minority and Democratic representation more evenly across districts.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.13949v1">Minim: Privacy-Aware Minimal View for Agents via Trusted Local Sanitization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-11T22:27:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hexuan Yu, Chaoyu Zhang, Heng Jin, Shanghao Shi, Ning Zhang, Y. Thomas Hou, Wenjing Lou</p>
    <p><b>Summary:</b> Modern LLM-powered autonomous agents increasingly rely on rich user interface (UI) state observations to achieve reliable action grounding in complex digital environments. However, many deployments transmit the full UI state to remote inference servers even when most elements are irrelevant to the current task, which can leak sensitive but unnecessary context such as authentication codes, private notifications, and background application states. We propose MINIM, a trusted local broker that performs privacy-aware minimization on the client side before any observation leaves the device. Grounded in Contextual Integrity (CI), MINIM learns a dual-score representation for each UI element by predicting an inherent sensitivity score (s) and a task-conditioned necessity score (n). These scores drive a ternary disclosure policy that keeps essential elements, abstracts sensitive attributes when needed, and removes task-irrelevant content. We optimize a CI-aware objective that penalizes necessity errors more strongly on high-risk content, enabling aggressive pruning while preserving task-critical information. Experiments on real-world UI observations derived from WebArena show that MINIM substantially reduces task-irrelevant sensitive leakage while preserving task-critical semantic context and the interactive affordances required for reliable agent actions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.12845v1">A Privacy-Preserving Framework Using Remote Data Science for Inter-Institutional Student Retention Prediction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-06-11T03:18:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> John Fields, K M Sajjadul Islam, Ruchitha Thota, Victor Chen, Praveen Madiraju</p>
    <p><b>Summary:</b> This study explores privacy-preserving machine learning (PPML) techniques using the PySyft platform to enable collaborative prediction of student retention between institutions. We developed a remote data science (RDS) framework with a semi-air-gapped architecture consisting of high-side and low-side servers, allowing researchers from three universities to build predictive models on sensitive student data without direct data access. Using historical data from a small private university (N=720), we evaluated three synthetic data generation approaches and validated the framework through inter-institutional collaboration. The results demonstrate consistent classification performance across institutions (Macro F1: 0.690--0.695) while maintaining strict Family Educational Rights and Privacy Act (FERPA) compliance. We also propose Data-Type-Aware Templates, a novel synthetic data method that prioritizes privacy over distributional fidelity. Our findings confirm that RDS-based PPML is technically feasible for educational settings and offers a practical alternative to federated learning for small-scale inter-institutional collaborations. The code is available at https://github.com/jtfields/NAIRR240195-Privacy-Preserving-Machine-Learning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.12733v2">Let's Ask Gauss: Improved One-Run Privacy Auditing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-06-10T22:44:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Adya Agrawal, Yu Wei, Jaspal Singh, Malik Magdon-Ismail, Vassilis Zikas</p>
    <p><b>Summary:</b> Privacy auditing provides an important safeguard by estimating the actual information leaked by a model, thus ensuring that theoretical privacy guarantees hold in practice. We study empirical privacy auditing for differentially private (DP) machine learning, focusing on efficient one-run methods for mechanisms such as DP-SGD. Prior one-run approaches threshold training examples or "canaries" into binary membership guesses, which discards useful information. We show that, in the white-box DP-SGD setting, canary-aligned signals naturally form a sequence of random variables whose normalized sum is asymptotically Gaussian. Leveraging this distributional perspective, we develop a DP-auditing framework that leads to tighter privacy lower bounds from a single training run.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.12679v1">Fed-FBD: Federated Functional Block Diversification for Isolation, Privacy, and Surgical Unlearning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2026-06-10T21:06:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Weijie Chen, Alan B. McMillan</p>
    <p><b>Summary:</b> Federated learning (FL) enables collaborative model training without sharing raw patient data, but standard approaches such as FedAvg treat each client as a black box and provide no mechanism for isolating an adversarial contributor, auditing per-client influence, or honoring a departed participant's right to be forgotten. We present Fed-FBD (Federated Functional Block Diversification), a modular federated architecture that decomposes a ResNet backbone into six functional blocks (the stem, four residual groups, and the classification head) and maintains a warehouse of N color variants, each assembled from independently tracked and contributor-stamped blocks. Fed-FBD provides three capabilities absent in FedAvg: (i) architecturally guaranteed block-level isolation, so that an adversarial or mislabelled client cannot contaminate the clean colous; (ii) privacy-by-design, where membership inference advantage is already indistinguishable from chance before any privacy mechanism is applied; and (iii) surgical machine unlearning of a departed participant's contribution at sub-second cost and without retraining. Experiments on six MedMNIST-2D datasets, PathMNIST at 224x224, and CIFAR-10 show that Fed-FBD trades a modest 0.3%-3.1% IID accuracy gap on the adequately sized datasets for these guarantees, remains within 0.8%-4.0% of FedAvg at Dirichlet alpha=1.0 on three of four datasets, and confines all six adversarial attacks we study to the poisoned client's own blocks with at most +/-0.01 AUC drift on the clean colors.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.12666v2">CAPED: Context-Aware Privacy Exposure Defense for Mobile GUI Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-10T20:48:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Siyu Shen, Fenghao Xu, Wenrui Diao, Kehuan Zhang</p>
    <p><b>Summary:</b> Screenshot-based mobile GUI agents can operate ordinary smartphone apps through the same visual interface as a human user, but this capability also turns every screen observation into a privacy boundary. During normal task execution, screenshots may expose contacts, messages, photos, files, recommendations, health cues, and other sensitive context that is unrelated to the user's request. We call this problem incidental visual privacy exposure. It is difficult to address with existing defenses: text anonymization misses many visual and inferential cues, while generic privacy masking can remove the evidence and controls that a GUI agent needs to complete the task.
  This paper presents CAPED, a context-aware pre-upload exposure control layer for mobile GUI agents. CAPED is designed as a phone-side protection layer: before screenshots are released to a remote multimodal agent, it extracts task requirements, uses screen context as a privacy prior, parses visible UI elements, and selectively exposes only content needed for the current task while masking incidental private content. We evaluate CAPED on AndroidWorld for broad task utility and with a controlled 28-task seeded privacy evaluation used as a measurement instrument for trajectory-level incidental leakage. In this seeded evaluation, Full CAPED reduces success-conditioned weighted seeded leakage from 0.766 under raw screenshots to 0.268 while preserving high task utility. A broader AndroidWorld run shows a remaining prototype-level utility cost, but the results show that task-driven selective exposure can reduce incidental visual leakage before screenshots are released to a remote GUI agent.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.12341v1">OCELOT: Inference-Leakage Budgets for Privacy-Preserving LLM Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-10T17:13:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jin Xie, Songze Li</p>
    <p><b>Summary:</b> Large language model (LLM) agents increasingly act on a user's behalf -- reading personal files, calling tools, transacting with external services -- possibly leaking personally identifiable information (PII) across trust boundaries at every step. Privacy here is a property not of a single output but of an entire trajectory, and three properties make it hard: leakage is cumulative, as individually innocuous releases accumulate across honest-but-curious or colluding sinks into inferences about a protected secret; bidirectional, as a malicious observation can inject instructions that turn the agent's own reasoning model against the user; and task-dependent, as the same field is necessary for one recipient yet gratuitous for another. Per-release contextual-integrity filters, information-flow controls, and posterior-leakage monitors each address part of this but none controls cumulative, inference-based leakage at runtime. We recast agent privacy as \emph{posterior-risk control} and present OCELOT, a runtime mediator that budgets how much an adversary's belief about a secret may improve across a trajectory, rather than filtering outputs. Its mechanism, \emph{Witness-Verified Declassification}, separates judgment from trust: an untrusted, locally fine-tuned defender model inspects each candidate release and emits structured evidence -- labeled atoms and proposed declassification operators -- which a deterministic verifier audits, charging a certified min-entropy cost for the chosen variant and authorizing the least-disclosing useful release under a sink-trust-weighted budget recorded on a tamper-evident ledger. Across diverse agent benchmarks and recent defenses, OCELOT attains significantly lower leakage at higher task utility, resists adaptive injection, jailbreak, cumulative inference, and sink collusion, and adds only modest overhead.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.14783v1">The Vision Encoder as a Privacy Boundary: Visual-Token Side Channels in Encoder-Free Vision-Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-10T10:39:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chenyu Zhou, Qiliang Jiang, Shuning Wu, Xu Zhou</p>
    <p><b>Summary:</b> A vision encoder compresses image pixels into semantic embeddings, implicitly acting as a privacy boundary by preserving semantic content while attenuating pixel-local detail required for exact text recovery. Encoder-free vision-language models (VLMs) remove this boundary by routing image patches directly into the language-model token stream, thereby exposing an architectural privacy attack surface: intermediate visual tokens become a pre-output side channel. Under a token-access adversary, decoders invert visual-token streams from two encoder-free VLMs, Gemma4 and Fuyu, recovering recognizable image structure and readable held-out access codes, whereas matched encoder-based controls localize target regions but recover no exact strings. Within-model ablations show that the operative factor is spatial sampling fidelity of the visual-token grid, especially character-direction sampling density, rather than token or value count. The leakage is not limited to exported tokens: Gemma4 layer-0 key-value cache tensors are directly invertible, placing the side channel within KV caches commonly persisted by production serving stacks for decoding efficiency. The attack survives clutter, realistic document degradation, and zero-shot transfer to public document images, and it resists value-level defenses such as additive noise and quantization. Effective mitigation must therefore reduce spatial sampling, making removal of the vision encoder a first-class privacy decision in VLM deployment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.11556v1">Privacy-Preserving Federated Autoencoder for ECG Anomaly Detection on Edge Devices</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-06-10T01:33:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kaan Arda Akyol, Jakub Kacper Szeląg, Aydin Abadi, Maha Alghamdi, Ghadah Albalawi, Ghouse Ibrahim Kaleelullah, Hilal Tutus, Sarah Al Subaiei, Shardul Kapse, Syed Mohammed Raheeb, Mujeeb Ahmed, Rehmat Ullah</p>
    <p><b>Summary:</b> Continuous electrocardiography (ECG) monitoring could surface rhythm abnormalities before they escalate into cardiovascular events. However, a deployable system must satisfy three requirements simultaneously: legal-grade privacy (GDPR, HIPAA), real-time inference on constrained edge hardware, and detection quality under non-IID cross-hospital data.
  We design and evaluate an end-to-end federated system addressing all three for unsupervised 12-lead ECG anomaly detection on PTB-XL dataset, combining three autoencoder families (VanillaAE, ConvAE, VAE), Flower-based federated averaging (FedAvg) across ten simulated hospitals, client-side differentially private SGD (DP-SGD) with a Rényi-DP accountant, and 8-bit integer (INT8) post-training quantization with Raspberry Pi 4 benchmarking. Our main contributions are: an empirical characterization of how these mechanisms compose, practical DP-specific recommendations, and technical and security insights for a clinically sensitive setting. Federated learning matches or exceeds the centralized baseline across all architectures (ConvAE federated area under the ROC curve, AUROC, $0.782$), and an $\varepsilon$ sweep identifies $\varepsilon=4$ as the recommended clinical operating point. INT8 quantization roughly halves model size and cuts Pi 4 latency by up to $44%$ with $<0.12%$ AUROC loss. Crucially, DP and quantization penalties are empirically independent, so practitioners need not trade a strong privacy guarantee for a compact edge footprint. To our knowledge, this is the first system combining federated learning, formal $(\varepsilon,δ)$-DP, unsupervised reconstruction-based detection, and quantized AArch64 deployment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.11539v1">PriME-Deal: Privacy-Preserving Bilateral Data Trading with Efficient Matchmaking and Auditable Fair Exchange on Blockchain</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-10T00:49:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jie Zhang, Xiaohong Li, Shanshan Xu, Hanwei Wu, Ruitao Feng, Guangdong Bai</p>
    <p><b>Summary:</b> Bilateral attribute-based access control for data trading must hide policies, provide cryptographic fairness, and avoid trusted third parties. Existing solutions either leak policy information, incur super-linear costs, or rely on trusted dispute resolution. We present PriME-Deal, a non-interactive protocol that simultaneously achieves policy-hiding bilateral matching, efficient threshold access control, and auditable fair exchange on public blockchains. The seller embeds a secret token under the buyer policy into an oblivious key-value store with pseudorandom masking; the buyer reconstructs the token locally via tag-based probing, eliminating combinatorial enumeration, and proves correctness in zero-knowledge. Fair exchange is enforced through a collateralized on-chain reveal with a cryptographic audit that penalizes misbehaviour without trusted parties.
  We prove security in the Universal Composability framework under standard assumptions. Compared with the state-of-the-art threshold fuzzy IB-ME scheme, the seller's publishing time is reduced by two orders of magnitude (e.g., 8.76s vs. 690s for a policy of 500 attributes). For a typical configuration of (200,20,5), the buyer completes token reconstruction and proof generation in 8.9s, with the zero-knowledge proof taking under 0.6s and remaining constant across all parameter scales. The on-chain cost is approximately 28.6M gas, well within Ethereum's block limit. PriME-Deal thus delivers the first practical privacy-preserving data trading protocol that combines linear seller overhead, bilateral policy hiding, and auditable fairness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.11272v1">Federated continual learning: A comprehensive survey on lifelong and privacy-preserving learning over distributed and non-stationary data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-09T08:35:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Masoume Gholizade, Fabrizio Ruffini, Pietro Ducange, Francesco Marcelloni</p>
    <p><b>Summary:</b> Federated Learning (FL) enables collaborative and privacy-preserving model training across distributed clients, but most existing FL systems implicitly assume data stationarity. In real-world settings-such as healthcare, industrial IoT (IIOT), cybersecurity, and smart cities-data streams are inherently non-stationary, leading classical FL methods to suffer from performance degradation, instability, and catastrophic forgetting.
  Continual Learning (CL) addresses learning under evolving data distributions but has been largely studied in centralized settings, overlooking key constraints of federated systems, including privacy, limited communication, and client heterogeneity. Federated Continual Learning (FCL) emerges at the intersection of FL and CL, aiming to support lifelong, adaptive, and privacy-aware learning over distributed and non-stationary data.
  This survey provides a comprehensive and systematic overview of FCL. We first present a formal definition of the FCL problem and clarify its distinctive characteristics. We then analyze the limitations of classical FL under non-stationary conditions, highlighting how CL principles support long-term adaptation. To organize the rapidly growing literature, we propose a multi-dimensional taxonomy of FCL approaches. Furthermore, we review representative application domains and data modalities, summarize commonly used evaluation metrics, and discuss experimental perspectives for assessing long-term performance and forgetting. Finally, we highlight key open challenges, including handling extreme heterogeneity under temporal drift, designing scalable and privacy-preserving memory mechanisms, and establishing standardized benchmarks. This survey aims to serve as a reference and a roadmap for advancing FCL toward robust and deployable real-world systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.10502v1">When VR Meets BCI: (Un)Observable Brainwave-aware Privacy Reconstruction in the Metaverse via Unrestricted Inbuilt Motion Sensors</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-09T07:28:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tao Ni, Zehua Sun, Qingchuan Zhao, Wei-Bin Lee, Cong Wang</p>
    <p><b>Summary:</b> Metaverse devices, such as virtual reality (VR), have seen substantial development and widespread applications in numerous areas. Although recent studies have revealed privacy leakages in VR, these vulnerabilities were limited in the scope of observable behaviors in virtual scenes (e.g., what a user is seeing). In this work, we uncover the feasibility of going beyond the scope of observable user behaviors to unobservable brain EEG-correlated representations (e.g., what a user is perceiving) by leveraging unrestricted motion sensors in VR headsets to reconstruct brain EEG signals, a seemingly neglected but promising vector. The insight is that the inbuilt motion sensors (e.g., accelerometers) in the VR headset can capture subtle vibrations induced by pupillary responses, which are highly correlated with users' visual stimuli and in-brain perceptions.
  Therefore, we design and implement BraVeSpy to systematically investigate and demonstrate the feasibility of this severe privacy leakage originating from brain EEG-correlated representations reconstructed from variations of inbuilt motion sensors. Our extensive evaluation results from different VR devices show that BraVeSpy, for the first time in the Metaverse, can reveal unobservable privacy, where we successfully unveiled perceptive images in the brain with 52.0%-67.2% accuracy. In particular, we also find that BraVeSpy outperforms the current approaches that are limited to coarse-grained inference of observable behaviors and achieves over 85.0% accuracy in inferring user activity-related sensitive information, such as fingerprinting websites, apps, and streaming videos, and over 96.0% accuracy in user de-anonymization, gaze movement tracking, and virtual keystroke inference.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.10481v1">Advancing the State-of-the-Art in Empirical Privacy Auditing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2026-06-09T06:50:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nicole Mitchell, Galen Andrew, Arun Ganesh, Brendan McMahan, Peter Kairouz</p>
    <p><b>Summary:</b> Parameter-efficient fine-tuning of large language models (LLMs) can exhibit problematic memorization of individual training examples. Empirical privacy auditing (EPA) quantifies this risk by measuring realistic data leakage on membership inference (MI) or reconstruction attacks. A key challenge in EPA is designing ``canary'' examples that are mixed with the privacy-sensitive training data. We propose generating synthetic canaries via high-temperature sampling ($T \geq 0.8$) from LLMs, using prompts tailored to the privacy-sensitive training data. These canaries act as high-influence outliers, ensuring high identifiability and hence strong audits. Further, since the canaries are themselves non-private, they are inspectable and can be inserted with repetition without jeopardizing the privacy of the real data. An important use of models fine-tuned on privacy-sensitive data is the generation of synthetic data. This also comes with privacy risk. We introduce a powerful synthetic data audit based on fine-tuning an auxiliary model on the synthetic data. Auditing the auxiliary model for the original canaries then provides a strong estimate of the privacy leakage through the synthetic data. Finally, leveraging our strong auditing methodologies, we perform a systematic investigation into the interacting effects of model capacity and canary entropy on memorization.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.10333v1">Privacy-Preserving Credit Risk Prediction with Alternative Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-09T02:27:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hongzhe Zhang, Jiarong Xu, Jing He, Xiao Fang</p>
    <p><b>Summary:</b> Credit risk prediction is a critical problem in the consumer credit industry. Traditionally, financial institutions construct credit risk prediction models using borrowers' demographic, financial, and credit history data, collectively referred to as traditional data. Recent studies have demonstrated that alternative data, such as borrowers' mobile phone communication data, enable lenders to acquire fuller and more accurate profiles of borrowers' creditworthiness, thereby improving credit risk prediction performance. Nevertheless, alternative data are held by external entities independent of financial institutions. Directly sharing alternative data with financial institutions infringe on consumer privacy, yet existing credit risk prediction studies largely overlook this issue. To address this gap, we define a new problem, namely privacy-preserving credit risk prediction with alternative data, which simultaneously considers three practical constraints: the privacy-preserving constraint that protects consumer privacy, the model-confidentiality constraint that learns and stores the model centrally at the financial institution, and the lossless constraint that maintains the performance of the learned model. To solve this problem, we develop PrivacyCredit, a novel privacy-preserving machine learning method. We then theoretically demonstrate the privacy-preserving, model-confidential, and lossless properties of PrivacyCredit. Through extensive experiments using a real-world credit dataset linked with alternative data, we demonstrate the predictive value of securely incorporating alternative data into credit risk prediction and show that PrivacyCredit achieves the same predictive performance as the model learned from the insecure plaintext combination of traditional and alternative data. We further evaluate its model-confidentiality property and computational efficiency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.10173v1">Local Is Not a Sufficient Privacy Boundary: Governing OS-Integrated On-Device AI</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-08T21:07:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jonghyun Chung, Sanket Badhe</p>
    <p><b>Summary:</b> As AI systems move into operating systems, privacy no longer turns only on whether a model runs locally. A local assistant may assemble email, calendar entries, files, screenshots, notifications, and app intents; retain embeddings or summaries; invoke tools; emit telemetry; or route difficult requests to cloud infrastructure. Local inference reduces some exposure, but it answers only one question: where computation occurs. It does not answer who may assemble context, what derived state persists, which actions are authorized, or how updates change the system's authority. We develop an OS-centered privacy framework for on-device AI that treats privacy as an institutional accountability problem rather than a deployment attribute. The framework specifies a threat model, a six-part privacy risk taxonomy, privacy-by-architecture controls, and a four-level audit rubric. We demonstrate the rubric through a documentation-bounded comparison of Apple Intelligence/Foundation Models, Android AICore/Gemini Nano, and Microsoft Recall. Meaningful privacy in on-device AI depends on constrained information flow, bounded authority, visible user control, and auditable governance across the operating-system lifecycle.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.10097v1">Secrets Best Not Shared: DNS Privacy Enhancements for the Constrained IoT</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-06-08T19:22:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Martine S. Lenders, Thomas C. Schmidt, Matthias Wählisch</p>
    <p><b>Summary:</b> Attackers often identify DNS traffic to disrupt or compromise Internet services. While prior work has focused on encrypting queries using DNS over TLS, HTTPS, or QUIC to counter such attacks, we consider IETF protocols designed for resource-constrained IoT devices and empirically analyze the potential of obfuscating DNS traffic in addition to encryption. We create a dataset of machine-to-machine-compatible data objects along with the corresponding DNS resolution processes, evaluating 296 deployment scenarios of resolving host names, including DNS over the Constrained Application Layer Protocol (CoAP) and an onion routing flavor of CoAP under varying link-layer conditions. We compare them to DNS over HTTPS. Using Random Forest and a header field analysis, we identify fields that leak most information. Our findings show that DNS over CoAP with equalized packet lengths, block-wise transfer, and header compression reduces the accuracy of identifying DNS frames to 86% and further to 77% with payload compression. Our approach outperforms DNS over HTTPS, where classifiers always identify DNS frames based on IP addresses. The dataset is publicly available.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.09590v1">Clinically Grounded Privacy Evaluation of Medical LMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-08T15:02:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sasha Ronaghi, Sana Tonekaboni, Lena Stempfle, Vivian Utti, Jordan Li Cahoon, Nathaniel Hendrix, Ayin Vala, Marzyeh Ghassemi, Emily Alsentzer</p>
    <p><b>Summary:</b> Medical language models (LMs) can memorize and reproduce protected health information, but privacy evaluations often focus on recovery of training text rather than disclosure under realistic threat models. We introduce a clinically grounded framework that evaluates leakage along a graded axis of adversarial access, ranging from publicly inferable demographics to leaked note fragments. At each tier, we measure verbatim memorization of patient-specific text and semantic leakage of sensitive diagnoses. Applying the framework to an LM pretrained on 378k clinical notes, we find that routine encounter metadata (i.e. name, date of birth, provider, practice, visit date) elicits high rates of verbatim memorization across a patient's timeline and sensitive-diagnosis recovery (AUROC 0.91 for abortion, 0.81 for HIV). At the same time, exact-match memorization can overstate disclosure: 36% of memorized tokens reflect templated documentation. Our work highlights the risks of training on longitudinal clinical data, providing a practical framework for contextual privacy evaluation of medical LMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.09582v1">On Choosing the $μ$ Parameter in Gaussian Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2026-06-08T14:56:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bogdan Kulynych, Antti Honkela</p>
    <p><b>Summary:</b> Recent work argues for using Gaussian differential privacy (GDP) to report the privacy guarantees in privacy-preserving machine learning. We provide principled mappings from pure-DP $\varepsilon$ to GDP $μ$ by matching the worst-case success of a strong-adversary membership inference attack in terms of three metrics: multiplicative advantage at fixed FPR, precision at fixed recall, and the standard privacy profile. We tabulate $μ$ values across a useful range of parameters and recommend $μ\approx \varepsilon/5$ as a conservative general-purpose conversion.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.09402v1">Fully Oblivious Differential Privacy for Frequency Estimation in the Augmented Shuffle Model with Trusted Processors</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-08T12:21:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Takao Murakami, Yuichi Sei, Reo Eriguchi</p>
    <p><b>Summary:</b> In the shuffle model of DP (Differential Privacy), a shuffler randomly permutes users' data to achieve high accuracy and privacy. Recent studies show that most existing shuffle protocols are vulnerable to collusion attacks by the data collector and users. They address this issue by introducing the augmented shuffle model that incorporates random sampling and dummy data addition into the shuffler. However, it remains open how to ensure the shuffler follows the protocol and does not collude with the data collector in this model.
  We address this trust issue by thoroughly exploring the augmented shuffle model with TEEs (Trusted Execution Environments). We first introduce a new privacy notion, FODP (Fully Oblivious DP), which strengthens DP to prevent various TEE side-channel attacks based on external/internal memory access patterns and control flows. We propose a general framework for FODP algorithms based on memory-size obfuscation and three concrete algorithms within it. We also improve the efficiency of our algorithms by using the count-min sketch and optimizing the number of hashes. We evaluate our algorithms on Intel SGX and demonstrate their effectiveness through comparisons with nine baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.09401v1">Benchmarking Empirical Privacy Protection for Adaptations of Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-08T12:21:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bartłomiej Marek, Lorenzo Rossi, Vincent Hanke, Xun Wang, Michael Backes, Franziska Boenisch, Adam Dziedzic</p>
    <p><b>Summary:</b> Recent work has applied differential privacy (DP) to adapt large language models (LLMs) for sensitive applications, offering theoretical guarantees. However, its practical effectiveness remains unclear, partly due to LLM pretraining, where overlaps and interdependencies with adaptation data can undermine privacy despite DP efforts. To analyze this issue in practice, we investigate privacy risks under DP adaptations in LLMs using state-of-the-art attacks such as robust membership inference and canary data extraction. We benchmark these risks by systematically varying the adaptation data distribution, from exact overlaps with pretraining data, through in-distribution (IID) cases, to entirely out-of-distribution (OOD) examples. Additionally, we evaluate how different adaptation methods and different privacy regimes impact the vulnerability. Our results show that distribution shifts strongly influence privacy vulnerability: the closer the adaptation data is to the pretraining distribution, the higher the practical privacy risk at the same theoretical guarantee, even without direct data overlap. We find that parameter-efficient fine-tuning methods, such as LoRA, achieve the highest empirical privacy protection for OOD data. Our benchmark identifies key factors for achieving practical privacy in DP LLM adaptation, providing actionable insights for deploying customized models in sensitive settings. Looking forward, we propose a structured framework for holistic privacy assessment beyond adaptation privacy, to identify and evaluate risks across the full pretrain-adapt pipeline of LLMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.09125v1">Unveiling Privacy Risks in Multi-modal Large Language Models: Task-specific Vulnerabilities and Mitigation Challenges</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-08T07:19:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tiejin Chen, Pingzhi Li, Kaixiong Zhou, Tianlong Chen, Hua Wei</p>
    <p><b>Summary:</b> Privacy risks in text-only Large Language Models (LLMs) are well studied, particularly their tendency to memorize and leak sensitive information. However, Multi-modal Large Language Models (MLLMs), which process both text and images, introduce unique privacy challenges that remain underexplored. Compared to text-only models, MLLMs can extract and expose sensitive information embedded in images, posing new privacy risks. We reveal that some MLLMs are susceptible to privacy breaches, leaking sensitive data embedded in images or stored in memory. Specifically, in this paper, we (1) introduce MM-Privacy, a comprehensive dataset designed to assess privacy risks across various multi-modal tasks and scenarios, where we define Disclosure Risks and Retention Risks. (2) systematically evaluate different MLLMs using MM-Privacy and demonstrate how models leak sensitive data across various tasks, and (3) provide additional insights into the role of task inconsistency in privacy risks, emphasizing the urgent need for mitigation strategies. Our findings highlight privacy concerns in MLLMs, underscoring the necessity of safeguards to prevent data exposure. Our dataset and code can be found here.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.09946v2">SPARX: Secure and Privacy-Aware Approximate CNN Acceleration with Edge RISC-V SoC</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Hardware Architecture-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-06-08T07:02:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sonu Kumar, Akash Sankhe, Mukul Lokhande, Santosh Kumar Vishvakarma</p>
    <p><b>Summary:</b> Edge-AI systems increasingly require real-time CNN inference under strict energy, performance, security, and privacy constraints. Approximate computing improves hardware efficiency by exploiting the error resilience of neural network workloads; however, most approximate CNN accelerators do not jointly consider secure, privacy-aware edge deployment. This paper presents SPARX, a Secure and Privacy-Aware Approximate CNN Acceleration framework integrated within a heterogeneous RV32IMC RISC-V System-on-Chip (SoC). SPARX combines a custom RISC-V instruction extension, an approximate logarithmic CNN acceleration unit, a lightweight differential-noise-based privacy engine, and a challenge-response authentication mechanism. To guide arithmetic selection, an approximation-aware decision framework is introduced that uses the Approximation Severity Index (ASI), Approximation Efficiency (AE), Quality of Approximation (QoA), Approximation Figure-of-Merit (AFOM), and Hardware Acceleration Efficiency (HAE). Evaluation across 11 state-of-the-art approximate MAC architectures identifies the Iterative Logarithmic Multiplier (ILM) as the most suitable design, achieving 51.7% area reduction, 81.5% power reduction, and 2.13x throughput improvement compared with an accurate radix-4 Booth MAC, while only reducing ResNet-20/CIFAR-10 accuracy by 2.82 percentage points. FPGA implementation on a Xilinx VC707 platform achieves 58.4 GOPS/W energy efficiency at 250 MHz, while 28-nm CMOS physical implementation validates ASIC feasibility</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.08681v1">Asymptotic Optimality of the High-Dimensional Gaussian Mechanism and Improved Low-Dimensional Mechanisms for Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-07T15:33:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yu Wei, Alexander Bienstock, Antigoni Polychroniadou</p>
    <p><b>Summary:</b> The additive noise mechanism is a foundational tool for differential privacy (DP) of $T$-dimensional real-valued vector queries. The Gaussian mechanism, utilizing Gaussian noise, is the mostly widely used such mechanism, due to its simplicity and strong privacy guarantees. In this work, we provide justification for this choice, showing that as the dimension $T\to\infty$, no additive-noise mechanism can asymptotically improve on the Gaussian mechanism's privacy--utility tradeoff for the strong privacy settings typically used.We also develop a new family of \emph{Spherical Generalized Gamma} DP mechanisms, which contains both the Gaussian mechanism and the recently studied $\ell_2$ mechanism (Joseph \emph{et al.}, ICML 2025). We identify members of this family that outperform both the Gaussian and $\ell_2$ mechanisms in certain low-dimensional settings, and show tight composition of all mechanisms in this family, answering an open question of Joseph \emph{et al.}~regarding the $\ell_2$ mechanism.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.08521v1">Exploring CKKS Parameter Trade-offs for Privacy-Preserving Personalized Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-07T08:58:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kamolchanok Saengtong, Phanwadee Sinthong, Norrathep Rattanavipanon</p>
    <p><b>Summary:</b> Privacy-preserving Personalized Federated Learning (PFL) enables clients to collaboratively train personalized models without exposing raw data, but exchanged model updates remain vulnerable to inference attacks from honest-but-curious servers. Homomorphic Encryption (HE) addresses this by allowing server-side aggregation directly on encrypted updates, with the CKKS scheme being particularly suitable due to its native support for approximate floating-point arithmetic. However, no prior work has examined how to configure CKKS for PFL deployments, leaving practitioners without principled guidance on parameter selection that directly affects privacy, precision, and computational cost. This paper presents pFedCKKS, a generic framework integrating CKKS into PFL, and provides the first systematic parameter selection guide for practitioners. We derive the full CKKS parameter constraints under 128-bit security for the PFL setting, showing the selection problem reduces to choosing just two values: the inner and outer ciphertext prime. Implemented using the Flower framework and TenSEAL library, pFedCKKS is evaluated on the FEMNIST, CelebA and Sentiment140 datasets with FedFinetune, Ditto and FedPer which represents PFL algorithms. Experimental results reveal an empirical trade-off between precision and computational/communication costs. This allows us to draw a concrete guideline for selecting proper CKKS parameters that balance efficiency and accuracy in real-world deployments of pFedCKKS.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.08252v1">Quantifying and Defending against the Privacy Risk in Logit-based Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-06-06T16:40:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sheng Wan, Dashan Gao, Hanlin Gu, Lixin Fan, Daning Hu, Qiang Yang</p>
    <p><b>Summary:</b> Federated learning aims to protect data privacy by collaboratively learning a model without sharing private data among clients. Unlike traditional parameter-based FL methods that exchange model weights or gradients during training, emerging logit-based FL approaches share model outputs (logits) on public data. This strategy promotes model heterogeneity, reduces communication overhead, and enhances clients' privacy. However, the potential privacy risks associated with these logit-based methods have been largely overlooked. This research presents the first theoretical and empirical analysis of a hidden privacy risk in logit-based FL methods - the risk that a semi-honest server (adversary) may learn clients' private models from logits. To quantify and address this threat, we develop the Adaptive Model Stealing Attack (AdaMSA) by leveraging historical logits during training. Notably, we observe that this inherent privacy risk persists even when public data is unrelated to private data, emphasizing the urgency to address privacy vulnerabilities in logit-based FL methods. Moreover, our theoretical analysis establishes the bounds of this privacy risk. We then propose a simple but effective defense strategy that perturbs the transmitted logits in the direction that minimizes the privacy risk while maximally preserving the training performance. The experimental results validate our analysis and demonstrate the effectiveness of AdaMSA and our defense strategy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.09908v1">IDP-Bench: Benchmarking ability of LLMs to protect personal information in interdependent privacy contexts</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-06T07:59:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ayana Hussain, Soumya Sharma, Golnoosh Farnadi, Nicholas Vincent, Héber Hwang Arcolezi, Ulrich Aïvodji</p>
    <p><b>Summary:</b> Large language models (LLMs) are becoming widely deployed as personal AI assistants with access to sensitive user data, making privacy a major challenge for their design and evaluation. Prior work focuses mainly on individual-level risks, overlooking \textbf{interdependent privacy (IDP)}--where one person's data may be revealed by others without their knowledge or consent. We address this gap by introducing \textbf{IDP-Bench}: the first LLM benchmark for IDP scenarios, grounded in the Contextual Integrity (CI) framework. We evaluate eight open-source LLMs on their understanding of IDP scenarios across three levels of IDP reasoning using two LLM judges. Results show strong co-ownership recognition (6/8 models exceed 90\%) but persistent weaknesses in identifying CI parameters (information attribute, primary subject) and IDP-specific parameters such as secondary subjects, where 7/8 models score below 74\%. Models also struggle to judge sharing appropriateness (5/8 scoring below 77\%). While the ability to judge the appropriateness of sharing improves with scale, performance tends to decline in smaller models, and prompt sensitivity remains high on IDP-specific questions--highlighting the need for more targeted study of IDP in LLM privacy research. Data \& code available \href{https://github.com/tisl-lab/Interdependent_Privacy_Bench}{here}.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.07883v2">DP4SQL: Differentially Private SQL with Flexible Privacy Policies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2026-06-05T22:35:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Andrew Cascio, KinChin Tong, Daniel Kifer, Zeyu Ding, Danfeng Zhang</p>
    <p><b>Summary:</b> The plausible deniability model of differential privacy for single-table datasets is well-understood. However, applying differential privacy to relational databases is much trickier: each application needs flexibility in specifying the pieces of information about an entity, spread across multiple relations, that require plausible deniability guarantees. Existing differentially private SQL systems only support rigid privacy policies. Even seemingly small changes, such as specifying that some tables need to protect the existence of records while others only need to protect the record contents, require significant manual effort in updating their privacy accountants and proving their correctness.
  One example of a challenge is the presence of partially public data. Public columns in a table (e.g., faculty names in a university dataset and partial course enrollment information) can cause some queries to require more noise (compared to fully private data), while others require less noise. This kind of reasoning is not supported in existing systems. Another example is when different parts of records (e.g., demographics, financial data) require different levels of privacy protection. Again, existing differentially private SQL systems need to rewrite their rules for calculating query stability in order to support such a feature. This paper presents DP4SQL, a differentially private SQL system that allows data curators to better customize the plausible deniability requirements for their relational databases. This avoids the drawbacks of the "one-size-fits-all" systems that would either underprotect the data or inject too much noise into query answers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.09460v2">A 65-nm Privacy-Preserving Neuromorphic Encoder With 7.13-nJ Efficiency, 2.38-Mb/mm^2 Item-Memory Density, and Federated Learning Support</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Hardware Architecture-04E762">
  <p><b>Published on:</b> 2026-06-05T16:50:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Boyang Cheng, Jianbo Liu, Steven Davis, Zephan M. Enciso, Likai Pei, Xueji Zhao, Muya Chang, Ningyuan Cao</p>
    <p><b>Summary:</b> The increasing demand for privacy-preserving personal data analytics in smart assistants, wearable health monitors, and context-aware systems calls for hardware that is both energy-efficient and secure. This work presents a 65-nm privacy-preserving neuromorphic encoder that leverages transistor-level process variation as physically unclonable entropy for hyperdimensional computing. The proposed 2T-2T entropy cell enables compact, device-specific, and write-free item memory, allowing privacy-preserving bio-signal encoding without storing random basis vectors in conventional memory. The fabricated prototype achieves 7.13 nJ per encoding, 2.38 Mb/mm^2 item-memory density, 76.44 nJ per prediction, and 357.32 nJ per training update. It also supports in-situ decision-making, continual learning, and federated learning for multi-user deployment and cold-start personalization. Evaluations across bio-signal datasets demonstrate 93.2% accuracy on EMG and 96.1% accuracy on UCI-HAR, while reducing hypervector dimensionality by 14.3x compared with binary hyperdimensional computing. These results demonstrate an energy-efficient and privacy-preserving neuromorphic hardware platform for secure edge biomedical intelligence.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.07443v1">Sort, Partition, Randomize: Optimal Binary Hypothesis Testing under Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-05T16:41:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Elena Ghazi, Jawad Nasser, Flavio Calmon, Ibrahim Issa</p>
    <p><b>Summary:</b> We study optimal design of $\varepsilon$-locally differentially private mechanisms for binary hypothesis testing. Each observation is drawn from one of two known distributions $P_0,P_1$ on a finite alphabet of size $k$, privatized by a mechanism $Q$, and then used to infer which distribution generated the data. We measure testing utility using an $f$-divergence, including total variation, KL, and hockey-stick divergences, between the two induced output distributions. Previous work established structural properties of optimal mechanisms, but only yielded exponential-time algorithms. We prove a sharp structure: for every $\varepsilon$ and every $f$-divergence objective, after sorting the alphabet by likelihood ratio, there exists an optimal mechanism that partitions the sorted alphabet into contiguous blocks and applies randomized response to the block label. We call this class Sort-Partition-Randomize (SPR). This characterization yields an exact dynamic program that computes an optimal mechanism in $O(k^3)$ time, and more generally in $O(\ell k^2)$ time with an $\ell$-output budget. Our results make it possible to efficiently compute and characterize the exact optimum across the full privacy range, beyond asymptotic privacy regimes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.07175v1">Seeing Without Exposing: Adaptive Privacy Control for Open-World, Context-Hungry MLLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-06-05T11:41:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Siyuan Xu, Yibing Liu, Peilin Chen, Yung-Hui Li, Shiqi Wang, Sam Kwong</p>
    <p><b>Summary:</b> Multimodal large language models (MLLMs) have raised new privacy challenges. On the data side, user-provided inputs often include unpredictable sensitive information; while on the downstream task side, model reasoning depends on rich visual context that may itself be privacy-sensitive. Existing privacy protection methods, however, rely on predefined sensitive categories and fixed obfuscation strategies, struggling to tackle such challenges in MLLMs. To address this dilemma, we propose Anchored Privacy Drifting (APD), a training-free method that drifts privacy-sensitive elements toward semantically equivalent alternatives while anchoring contextual cues to the source image. To systematically evaluate this dual objective of privacy protection and contextual preservation, we introduce AdaptShield, a comprehensive benchmark covering 22 privacy categories, which combines conventional privacy metrics with MLLM-based assessments of contextual utility. Extensive experiments show that our method achieves balanced improvements in both privacy sanitization and content retention, with average gains of 10.4% on textual categories and 8.5% under MLLM-based evaluation across four MLLM series, i.e., Qwen2.5, Qwen3, InternVL3, and InternVL3.5.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.07171v1">When Recovery Matters: The Blind Spot of Surrogate Privacy in MLLM Editing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-06-05T11:40:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Siyuan Xu, Yibing Liu, Peilin Chen, Yung-Hui LI, Shiqi Wang, Sam Kwong</p>
    <p><b>Summary:</b> Multimodal Large Language Models (MLLMs) enable flexible instruction-driven image editing, but privacy risks arise when user images expose diverse and user-specific private content. Canonical privacy protection strategies typically substitute sensitive regions with surrogate content before cloud editing. Yet, the resulting output is often an edited surrogate rather than the desired edited source image, neglecting the local recovery in both design and evaluation scope. To this end, we introduce SPPE (Surrogate-based Privacy-Preserving Editing), the first recovery-oriented benchmark covering 36 fine-grained privacy categories and 65 editing instructions. It defines two complementary tasks: 1) editability assessment, which estimates before cloud interaction whether a surrogate can induce an edit consistent with the original image; and 2) surrogate-to-source edit recovery, which evaluates whether the edited surrogate can be transferred back to the private source with the edit effect preserved. We address each task with a dedicated method: ERMA predicts surrogate editability through instruction-aware multimodal relation modeling, while \method performs cycle-consistent recovery by using the surrogate editing pair as visual edit evidence and the source image as a source-preserving anchor. Experiments on SPPE and InstructPix2Pix show consistent improvements on both tasks. For editability assessment, ERMA improves over the best-performing baselines by 13.9% in SRCC and 12.3% in PLCC. For surrogate-to-source edit recovery, C2E-S2SER outperforms SOER across all 8 source integrity and edit consistency metrics on SPPE.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.07150v3">From Privacy to Workflow Integrity: Communication-Graph Metadata in Autonomous Agent Interoperability</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-06-05T11:07:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bijaya Dangol</p>
    <p><b>Summary:</b> Agent-interoperability protocols such as A2A and MCP standardize what agents say to one another but assume address-based transport. Whether over HTTP(S) or a content-protecting binding such as MLS-based SLIM, these transports protect message content yet leave the communication graph exposed: which agent contacts which, when, and how often. In agent systems this graph is more consequential than a privacy framing suggests. Endpoints are capability-labeled, workflows are structured and chained, and interactions are coupled to actions, so an observer recovers more than past relationships: it can recognize a recurring pending workflow from its opening and, at machine speed, act on it before it completes. The threat is one of workflow integrity, not privacy alone. We give a threat model for the communication graph and locate what makes its metadata distinctively consequential: not stronger fingerprinting but exposure across independent trust domains, coupled to autonomous action. We define transport- and bootstrap-layer privacy properties, give them an indistinguishability-game semantics, evaluate transports, and give an A2A case study where a metadata-protecting binding surfaces its implicit identity assumptions. On a corpus of real multi-agent A2A traffic from the official reference agents, on a live A2A binding, and with a generative model as a controlled instrument, a label-blind classifier recovers a task's class from passive metadata at 6x chance, and from only its opening; a defense-aware adversary does not overturn this, and only the full set of properties drives recovery toward chance. Acting on the leak is distinct from recoverability: under a fixed budget an adversary captures 0.63 of a clairvoyant attacker's advantage on the corpus (0.41 from a workflow's opening), governed by top-ranked precision rather than overall accuracy, so integrity and privacy come apart under defense.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.06784v1">What Your Posts Reveal: A Benchmark and Agentic Framework for User-Level Privacy Leakage on Social Media</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-06-05T00:02:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zifan Peng, Yini Huang, Aiwen Lu, Qiming Ye, Peixian Zhang, Jingyi Zheng, Yule Liu, Xuechao Wang, Xinlei He, Jiaheng Wei</p>
    <p><b>Summary:</b> Public social media posts can reveal private information through weak cues scattered across text, images, or metadata. Such leakage is often cumulative and cross-post: cues that appear harmless in isolation may jointly expose a user's home, workplace, or routine. However, current research lacks a unified benchmark for user-level multimodal privacy leakage and an evaluation metric that captures exposure severity beyond binary accuracy.
  To address these gaps, we propose SopriBench, a synthetic benchmark guided by leakage patterns abstracted from a private reference corpus of Rednote and Instagram accounts, covering 50 user profiles and 1,569 images with attributes, contextual sensitivity, granularity, leakage type, inference difficulty, and supporting evidence. We further introduce the Privacy Exposure Score (PES), which weights value granularity by contextual sensitivity. Inspired by abductive reasoning, we introduce Argus, a training-free agentic framework for cumulative leakage inference. Argus forms hypotheses from accumulated evidence, verifies supporting evidence, and aggregates cross-post cues into privacy profiles, achieving 0.55 PES, a 25% improvement over the strongest baseline, with the largest gain on cross-post leakage.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.06354v1">Credential Disclosure in (EU) Digital Identity Wallets: Privacy Risks and Practical Mitigations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-04T16:22:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sheila Zingg, Daniele Lain, Yoshimichi Nakatsuka, Kari Kostiainen, Stefan Bechtold, Srdjan Čapkun</p>
    <p><b>Summary:</b> The European Union will introduce the EUDI Wallet by late 2026, which allows users to hold digital credentials (i.e., representations of physical official identity documents) on their devices. This will allow users to securely and privately disclose identity attributes to websites. Although such a system has many benefits, it also introduces risks caused by poor credential disclosure decisions. In this paper, we (i) conduct a large-scale survey on credential disclosure with users and experts and (ii) evaluate the effectiveness and feasibility of our Credential Assistant that displays expert recommendations and user opinions. Our results show that users are likely to overshare (e.g., ~20% of users disclosed their official ID to news websites). This indicates that users struggle to protect their privacy, which will impact the usability of the EUDI Wallet and lead to privacy violations, identity theft, and other abuses of leaked credentials. Finally, we show that our Credential Assistant significantly reduces users' credential disclosure mistakes from ~15% to ~7%. However, it does not fully eliminate poor credential disclosure decisions, indicating that stronger interventions may be necessary, especially for sensitive attributes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.06334v1">Quantifying the Privacy of Counterfactuals by Leveraging Membership Inference Attacks Against Synthetic Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-06-04T16:08:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maryam Babaei, Yingke Wang, Hadrien Lautraite, Heber H. Arcolezi, Ulrich Aivodji, Sebastien Gambs</p>
    <p><b>Summary:</b> Counterfactuals are typically used in high-stakes decision areas to explain a machine learning model by showing how changes to the user profiles result in the desired outcome. However, explaining the model's decisions through counterfactuals can also be exploited by an adversary to conduct privacy attacks against the model or its training data. Drawing on the analogy that counterfactuals provide realistic substitutes for real training data, similar to synthetic data, we demonstrate in this paper how it is possible to successfully perform privacy attacks on counterfactuals by drawing on the attacks developed against synthetic data. More precisely, we investigate the effectiveness of the membership inference attacks designed for synthetic data on various types of counterfactuals. Additionally, while existing membership inference attacks against counterfactuals usually require to be able to query the model, we show how it is possible to perform successful membership inference attacks using only a set of counterfactuals, with no access to the model from which they are generated. Our results demonstrate that model developers should be more cautious when releasing counterfactuals to various users, as it can lead to a privacy breach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.05902v1">PriSrv+: Privacy and Usability-Enhanced Wireless Service Discovery with Fast and Expressive Matchmaking Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-04T09:07:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yang Yang, Guomin Yang, Yingjiu Li, Pengfei Wu, Rui Shi, Minming Huang, Jian Weng, HweeHwa Pang, Robert H. Deng</p>
    <p><b>Summary:</b> Service discovery is a fundamental process in wireless networks, enabling devices to find and communicate with services dynamically, and is critical for the seamless operation of modern systems like 5G and IoT. This paper introduces PriSrv+, an advanced privacy and usability-enhanced service discovery protocol for modern wireless networks and resource-constrained environments. PriSrv+ builds upon PriSrv (NDSS'24), by addressing critical limitations in expressiveness, privacy, scalability, and efficiency, while maintaining compatibility with widely-used wireless protocols such as mDNS, BLE, and Wi-Fi.
  A key innovation in PriSrv+ is the development of Fast and Expressive Matchmaking Encryption (FEME), the first matchmaking encryption scheme capable of supporting expressive access control policies with an unbounded attribute universe, allowing any arbitrary string to be used as an attribute. FEME significantly enhances the flexibility of service discovery while ensuring robust message and attribute privacy. Compared to PriSrv, PriSrv+ optimizes cryptographic operations, achieving 7.62* faster for encryption and 6.23* faster for decryption, and dramatically reduces ciphertext sizes by 87.33%. In addition, PriSrv+ reduces communication costs by 87.33% for service broadcast and 86.64% for anonymous mutual authentication compared with PriSrv. Formal security proofs confirm the security of FEME and PriSrv+. Extensive evaluations on multiple platforms demonstrate that PriSrv+ achieves superior performance, scalability, and efficiency compared to existing state-of-the-art protocols.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.05821v1">PriSrv: Privacy-Enhanced and Highly Usable Service Discovery in Wireless Communications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-04T08:00:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yang Yang, Robert H. Deng, Guomin Yang, Yingjiu Li, HweeHwa Pang, Minming Huang, Rui Shi, Jian Weng</p>
    <p><b>Summary:</b> Service discovery is essential in wireless communications. However, existing protocols provide limited privacy protection, leaking sensitive device information and opening routes to network attacks. This paper proposes a private service discovery protocol, called PriSrv, which enables both service providers and clients to specify fine-grained authentication policies before establishing connections. PriSrv achieves this via a dual-layer matching architecture: an outer layer filters mismatched entities using public attributes, while an inner layer handles mutual authentication using selectively disclosed private attributes. As a core component, we introduce the primitive of anonymous credential-based matchmaking encryption (ACME), which enables dual-layer matching in a single step to achieve bilateral policy control, selective attribute disclosure, and multi-show unlinkability. To instantiate ACME, we design a fast anonymous credential (FAC) scheme providing constant-size credentials and efficient verification. We demonstrate PriSrv's interoperability by integrating it with popular wireless frameworks including EAP, mDNS, BLE, and AirDrop. Detailed formal security proofs and extensive performance evaluations across desktop, laptop, smartphone, and Raspberry Pi platforms demonstrate that PriSrv provides enhanced privacy guarantees with high usability, achieving secure discovery in less than one second on mainstream mobile devices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.05596v1">Multi-Objective Submodular Maximization with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-04T02:18:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ting Hou, Yanhao Wang, Yiping Wang, Cen Chen, Minghao Zhao, Fan Dang</p>
    <p><b>Summary:</b> In this paper, we study multi-objective submodular maximization (MOSM) subject to a cardinality constraint under differential privacy (DP). Specifically, we aim to select a set of at most $k \in \mathbb{Z}_{+}$ elements to maximize the minimum of $d > 1$ monotone submodular functions while satisfying $\varepsilon$-DP. Although extensive studies have been conducted on both differentially private single-objective submodular maximization on sensitive data and non-private MOSM, to the best of our knowledge, there has not yet been any prior work on MOSM with DP. We propose two novel algorithms: the first extends the classic greedy algorithm and the second employs a truncation technique, both of which are integrated with DP mechanisms for privacy protection and achieve approximation guarantees for MOSM. Finally, we conduct numerical experiments on two submodular maximization applications, namely maximum coverage and facility location, in multi-objective settings to validate the efficacy and efficiency of our proposed algorithms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.05561v1">InfoShield: Privacy-Preserving Speech Representations for Mental Health Screening via Information-Theoretic Optimization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-04T01:16:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xueyang Wu, Siyuan Liu, Kezhuo Yang, Guang Ling</p>
    <p><b>Summary:</b> Speech-based mental health screening offers scalable depression detection, yet clinical deployment faces a significant barrier: users' privacy concerns about demographic information exposure. Current techniques struggle to resolve this conflict. Adversarial training often fails against unseen threats, whereas Differential Privacy tends to compromise diagnostic performance by injecting noise across all features. This paper presents InfoShield, which minimizes mutual information between speech representations and sensitive attributes while preserving depression classification accuracy. We identify that standard MINE estimators struggle with sequential speech due to temporal-static misalignment, and introduce TimeAwareMINE with cross-modal attention to align acoustic frames with attribute embeddings. Experiments on the Androids Corpus show InfoShield reduces gender inference from 92.6\% to 55.5\% and age inference from 55.7\% to 30.3\% with limited utility loss (6\% F1 reduction), achieving F1=0.784 compared to prior SOTA's 0.723.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.05129v1">Preserving Data Privacy in Learning Causal Structure with Fully Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-06-03T17:33:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jian Yang, Yuan Tong, Qinbin Li, Zeyi Wen, Xiaofang Zhou</p>
    <p><b>Summary:</b> Preserving data privacy is an important topic in structural data management and data mining. However, the issue of privacy leakage in distributed causal structure learning is a persistent challenge, especially in cases where data transmission and computation are required. In this paper, we propose a method based on fully homomorphic encryption (FHE) that performs calculations on ciphertexts, keeping data encrypted in transition and computation. Nevertheless, adopting FHE to causal structure learning is challenging due to the high computation cost and limited support on division as well as logarithm operations in FHE. To tackle this challenge, we propose a series of novel techniques including (i) circuit simplification for better efficiency, (ii) approximation of division and logarithm through Newton-Raphson Reciprocal and Taylor expansion, and (iii) a batching technique with SIMD-acceleration to enhance the whole learning process. Additionally, our method can be easily extended beyond FHE by demonstration of its portability to support differential privacy. Empirical results show that our method achieves high consistency and comparable causal structure with the plaintext version in the datasets tested. Last, our method is efficient and practical to complete learning causal structures in tens of minutes even under the privacy protection of FHE.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.05273v1">Online Safety Regulation Increases Privacy Risk: Evidence from the UK Online Safety Act</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-03T17:24:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dhyey Mehta, Eldar Jalilzade, Maksim Kalameyets, Rebecca Owens, Marc Juarez, Stergios Aidinlis, Lei Shi, Tuğrulcan Elmas</p>
    <p><b>Summary:</b> Governments worldwide are increasingly regulating digital platforms to reduce online harms, particularly those affecting children. However, access restrictions can alter user behaviour and introduce new privacy and security risks. The UK Online Safety Act (OSA), passed in October 2023, illustrates this trend: it extends age-assurance and safety requirements to social media, search, and pornography services, and rolled out in phases. Ofcom's illegal content enforcement duties came into force in March 2025, and mandatory age verification for adult content took effect in July 2025. This phased rollout enables real-time observation of behavioural responses to regulation. To address this, we analyse Reddit discourse across VPN and UK Politics communities and conduct a privacy-policy risk analysis of 69 unique VPN services.
  We find that each of these three milestones produced significant stepwise increases in VPN-related discussion on Reddit: among UK-based users, posts and comments explicitly about VPN use in a regulatory or privacy context rose by +100%, +217%, and +415% respectively. UK Politics communities showed even larger effects, with OSA-related political discourse rising by +213%, +545%, and +464%, respectively, among UK-based users. UK VPN search interest on Google rose by +89% at the age-verification deadline. Users primarily framed this response around privacy, surveillance, and distrust of age-verification intermediaries rather than simple access-seeking. Demand increased across low, medium, and high-risk VPNs, but the proportional distribution remained broadly stable. These findings suggest that online safety regulation can create secondary privacy costs even when it does not disproportionately shift attention toward higher-risk providers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.05055v1">"A Glimpse, Not a Gaze": Using Generative AI to Balance Privacy and Awareness in Inter-generational Caregiving</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-06-03T16:14:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zixi Christina Li, Keiko Katsuragawa, James R. Wallace</p>
    <p><b>Summary:</b> As older adults increasingly prefer to age in place, their adult children often assume the role of informal caregivers. This dynamic creates a distinct tension between the adult child's need for awareness and the older adult's fundamental right to privacy. Traditional monitoring technologies, such as raw video feeds, often compromise the older adult's autonomy. To address this challenge, this study explores the use of generative Artificial Intelligence (GenAI) to create abstract, privacy-preserving ``visual summaries'' of daily activities. We design a 10-day Experience Sampling Method (ESM) study with dyads consisting of older adults and their adult children. Through daily smartphone prompts, participants report their current context and evaluate pre-generated AI sketches, indicating their willingness to share or receive these images. Follow-up interviews will further investigate participants' boundary-setting behaviours. This research aims to quantify the privacy mismatch between generations and provide actionable design guidelines for applying visual abstraction in AI-mediated caregiving tools, ultimately supporting inter-generational connection while protecting user dignity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.05004v1">SharedRequest: Privacy-Preserving Model-Agnostic Inference for Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-03T15:23:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Peihua Mai, Xuanrong Gao, Youlong Ding, Xianglong Du, Wei Liu, Yan Pang</p>
    <p><b>Summary:</b> With the widespread deployment of public large language models (LLMs) such as ChatGPT, protecting user prompt privacy has become an increasingly critical issue. Existing privacy-preserving inference methods sacrifice either utility or efficiency, and often require model-specific modifications that limit their compatibility. In this paper, we propose SharedRequest, a model-agnostic framework for privacy-preserving LLM inference that reformulates privacy protection at the batch level rather than the individual-prompt level. The key idea is to obscure sensitive information by mixing original prompts with noisy variants, while grouping semantically equivalent instructions to amortize the inference cost over a large batch of queries with minimal impact on LLM response quality. This design is independent of the LLM architecture, requiring no access to model parameters or architectural modification. Empirical results demonstrate that SharedRequest achieves over $20\%$ higher utility compared to prior differential privacy baselines, and its shared-prompt mechanism reduces query cost by up to $5\times$ compared to non-batched inference.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.04411v1">Pepper: High-bandwidth and Scalable Anonymous Broadcast with Cryptographic Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-03T03:38:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chenghao Li, Haoyuan Wang, Xianghang Mi</p>
    <p><b>Summary:</b> We present Pepper, a high-bandwidth anonymous broadcast protocol that provides cryptographic sender anonymity against global adversaries. Pepper builds on a two-server DC-net architecture but introduces three key innovations: a self-contained anonymous registration subprotocol using verifiable distributed point functions, support for batch messaging via distributed multi-point functions, and a lightweight access control mechanism based on secret-shared proofs. Unlike prior systems, Pepper eliminates the need for external dialing services and allows each broadcaster to send multiple messages per epoch with a single audit, significantly improving throughput for large data transfers. Our implementation demonstrates that Pepper achieves millisecond-level registration audits, scales efficiently to thousands of channels, and delivers 1.2--20$\times$ higher effective messaging rates than state-of-the-art alternatives. Furthermore, Pepper is designed for practical deployment, with natural compatibility for co-deployment alongside Tor and federated social networks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.04399v1">DPDL: Towards Differential Privacy Preservation in Decentralized Stochastic Learning on Non-IID Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-03T03:27:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yunsheng Yuan, Xue Xiao, Lina Wang, Feng Li</p>
    <p><b>Summary:</b> In the paradigm of decentralized learning, a group of agents collaborate to train a global model using distributed datasets without a central server. Although the power of collaboration has been verified by many state-of-the-art studies, it entails extensive gradient information exchanging among the agents and thus induces high risk of privacy leakage for the individual agents. Moreover, in real-world applications, the training data are usually non-identically and independently distributed across the agents, inducing more challenges to enable privacy-preserved decentralized learning. To address these issues, we propose a privacy-preserved decentralized learning algorithm with non-IID data, DPDL, which leverages the notion of Differential Privacy (DP) in cross-gradient aggregation through a similarity-based calibration technique. Specifically, in each round, each agent perturbs the cross-gradients (i.e., the derivatives of its neighbors' local model in its private local data) by Gaussian noise mechanism before sharing them with its neighbors; it then adopt cosine similarity to calibrate the received perturbed cross-gradients such that the aggregation of the calibrated cross-gradients can be utilized to effectively update local model in a momentum-like manner. Our rigorous theoretical analysis not only reveals the minimum noise level required to achieve a specific level of privacy preservation, but also illustrates that our algorithm still achieves a linear speedup in training with non-IID data. We finally conduct extensive experiments on real-world dataset to validate the effectiveness of our algorithm in defending privacy attacks and in training accurate models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.04384v1">Revisiting Privacy Amplification by Subsampling in Selective Release DPSGD</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2026-06-03T03:00:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaobo Huang, Fang Xie</p>
    <p><b>Summary:</b> Machine learning's reliance on sensitive data necessitates privacy-preserving techniques like Differentially Private Stochastic Gradient Descent (DPSGD). However, DPSGD suffers from substantial utility degradation and slow convergence due to gradient clipping and noise injection. Prior works have attempted to improve DPSGD from various perspectives; notably, the Differentially Private Selective Update and Release (DPSUR) algorithm has achieved remarkable model utility. However, the privacy accounting in DPSUR overlooks the variation in sampling probability introduced by the selective release mechanism, which compromises the rigor of its privacy guarantees. To address these limitations, we re-evaluate the privacy analysis of the selective release mechanism and propose a novel algorithm: Differentially Private Selective Release based on Clipped Gradients (DPSR-CG). Through a rigorous, newly derived privacy analysis and extensive experiments on multiple datasets (MNIST, CIFAR-10, IMDB, and FMNIST), we demonstrate that our DPSR-CG mechanism maintains strict privacy guarantees while achieving exceptional model performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.04338v1">Federated Learning for Multi-Center Sepsis Early Prediction with Privacy-Preserving</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-03T01:35:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xixi Tian, Di Wu, Xiang Liu, Yiziting Zhu, Yujie Li, Xin Shu, Bin Yi</p>
    <p><b>Summary:</b> Privacy-sensitive and distributed characteristics of multi-center medical data bring severe obstacles to centralized modeling for accurate early prediction of sepsis. Federated learning (FL) has attracted growing attention as a promising framework for collaborative model development, as it allows multiple institutions to jointly train predictive models without directly sharing or centralizing raw data. Nevertheless, its practical performance, robustness, and privacy-preserving benefits remain insufficiently evaluated using real-world clinical datasets. To bridge this gap, this study systematically examines the application of federated learning to multi-center sepsis prediction. The experimental dataset consists of 648 clinically screened samples collected from three tertiary hospitals in China, with rigorous inclusion and exclusion criteria. We establish a centralized training paradigm as the performance baseline, and then implement a horizontal federated learning framework for distributed collaborative modeling. Extensive experimental results demonstrate that the federated learning-based model achieves highly comparable prediction accuracy to the centralized counterpart, while fundamentally avoiding privacy leakage. Further privacy security analysis verifies that malicious attackers cannot reconstruct the original patient data from the transmitted model parameters, indicating strong resistance against data reconstruction attacks. This work not only validates the practicality and security of federated learning in clinical sepsis prediction, but also provides a reliable and feasible solution for privacy-preserving multi-center medical collaboration.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.03878v1">Privacy-Robust Incrementality Measurement for Advertising Systems under Signal Loss</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-06-02T16:46:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Prashant Shekhar, Caroline Howard</p>
    <p><b>Summary:</b> Advertising platforms use randomized lift tests to measure incrementality, but privacy-preserving reporting systems degrade the observed signal through match-rate loss, linkability loss, attribution-window loss, aggregation-threshold suppression, randomized reporting noise, and segment-heterogeneous signal loss. This paper formulates privacy-constrained advertising measurement as a robust causal decision problem under the mentioned signal losses. Given a randomized experiment and an ambiguity set for privacy-induced degradation, the framework projects the observation-compatible fiber of clean/unfiltered experimental worlds onto the incrementality functional and returns certified, rejected, and unresolved decisions. The main result gives a sharp decision frontier. Reports outside the frontier support uniformly valid certification or rejection, whereas reports inside it contain too little information for any method to uniformly distinguish above-threshold incrementality from non-incrementality. Supporting results give finite-sample certification, sample-complexity guarantees, a minimax lower bound showing that signal loss reduces effective information, and a reporting-granularity tradeoff. On 2.0M Criteo Uplift rows and the 64K-row Hillstrom email experiment, clean conversion lift is positive in both datasets, with lifts 0.00112 and 0.00495, respectively. Population certification survives mild degradation in Criteo and severe degradation in Hillstrom, while all considered finite-sample stress settings in both datasets remain unresolved after simultaneous uncertainty and reporting noise are included. Overall, the research contributes a decision-theoretic layer for privacy-aware incrementality measurement whose output is the strongest causal-claim justified by degraded ads signals.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.03714v1">Don't Trust Us: A privacy-by-design android malware detection pipeline</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-02T14:36:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Emmanuele Massidda, Diego Soi, Giorgio Giacinto</p>
    <p><b>Summary:</b> Android malware detection increasingly relies on collecting and processing sensitive user data, including device identifiers, network artifacts, and runtime traces, while privacy is too often treated as a secondary concern. Existing privacy-aware approaches typically enforce privacy after data collection, for example, through anonymization, encryption, or federated learning, yet still require access to user information and therefore demand a high level of user trust in systems that already operate with privileged access to device activity. We argue that this requirement should be removed rather than managed. Android malware detection should be privacy-aware by design, so that effective analysis does not depend on sensitive data being accessed in the first place. To this end, we first formalize a set of design requirements for privacy-by-design detection and then implement each requirement in a comprehensive pipeline. First, static analysis is performed to extract relevant data from each APK, following the Drebin representation, which is then submitted to an SVM after vectorization. The model is equipped with a dual-reject threshold rule that either commits to a confident decision or defers uncertain samples to a dynamic analysis stage within a sandboxed environment, so that genuine user information never enters the analysis loop. Results confirm that, on a temporally split dataset spanning from 2024 to 2025, the pipeline achieves an F1 score of 0.87 with the first static analysis stage, deferring only 6.7% of test samples to secondary dynamic analysis. Additionally, dynamic sandboxing helps recognize applications' maliciousness with high confidence without extracting any sensitive data. These results demonstrate that strong detection performance is achievable without sacrificing user privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.04069v1">Bayesian Membership Privacy for Graph Neural Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-06-02T14:33:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sinan Yıldırım, Megha Khosla</p>
    <p><b>Summary:</b> Existing privacy analyses for Graph Neural Networks (GNNs) largely inherit assumptions from non-graph settings, overlooking structural correlations and stochastic training-graph sampling. In particular, node-dependent priors make type-I and type-II errors alone insufficient to characterize the best membership inference test. To address this, we introduce Bayesian Membership Privacy (BMP), a sampling-aware formulation of node-level membership privacy that incorporates node-dependent priors and treats graph sampling probabilities as part of the adversary's knowledge. BMP casts membership inference as a Bayesian hypothesis test and accordingly quantifies membership privacy in terms of posterior membership probability. We explore theoretical properties of BMP in relation to the existing definitions in the literature. We further propose a practical, sampling-aware auditing mechanism to estimate the parameters of BMP as a measure of node-level privacy leakage in GNNs. We conduct experiments on benchmark graph datasets and show that BMP yields fine-grained privacy insights that are not visible through global attack accuracy alone.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.03711v1">Ghost: Plausible Yet Unlearnable Trajectories via On-Manifold Substitution for Next-POI Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2026-06-02T14:31:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhenyu Yu, Jihong Guan, Shuigeng Zhou</p>
    <p><b>Summary:</b> A publisher who releases check-in trajectories inadvertently publishes a strong predictor of every user's future locations. We address this risk by generating unlearnable trajectories, perturbed sequences that yield victim models with degraded next-Point-of-Interest (next-POI) accuracy on clean test inputs. Direct ports of image-domain unlearnable examples fail on two counts. The published data must remain geographically and semantically plausible, and the perturbation must resist purification adversaries that exploit the structure of randomized defences. We propose Ghost, a manifold-aligned framework whose perturbations look like plausible human check-in sequences yet leave no learnable signal behind. Ghost steers each substitution onto the real-trajectory manifold through a frozen trajectory language model, so a denoising-bridge adversary has nothing to invert and a context-free frequency-table adversary recovers a near-uniform distribution. Across two standard benchmarks, and four attacker postures, Ghost achieves protection-gap competitive with the strongest deterministic baseline (PGD) while attaining the lowest restored accuracy under the bigram adaptive purification adversary on both datasets, and lies within one per-cell standard deviation of PGD on the protection-versus-purification-resistance plane. Ablations confirm the manifold prior subsumes the entropy-floor knob of prior randomized defences, with the frequency-table adversary's survival gap remaining within 0.04 even when twenty percent of the pairs are leaked.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.04067v1">Need to Know: Contextual-Integrity-Grounded Query Rewriting for Privacy-Conscious LLM Delegation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-02T14:28:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xinyue Huang, Xiaochun Cao, Wenyuan Yang</p>
    <p><b>Summary:</b> As LLMs become increasingly woven into everyday workflows, user queries sent to cloud hosted LLMs routinely mix task-essential content with task non-essential sensitive disclosures, yet type based PII redaction is context agnostic and may raise two issues: over disclosing untyped sensitive context and over removing answer bearing spans. We recast privacy preserving query rewriting under Contextual Integrity: a span should be forwarded only if it is necessary for the task. We introduce DelegateCI-Bench, the first task based Contextual Integrity benchmark for privacy-conscious delegation, comprising 3,167 samples that combine high quality synthetic data spanning 11 tasks and 20 task types, WildChat based real user queries, and a medical challenge set with dense sensitive information. Building on this benchmark, we propose a CI-guided reinforcement learning framework that converts essential and non-essential sensitive spans into verifiable optimization signals, and train a query rewriter to preserve task critical information while suppressing unnecessary sensitive disclosure. Experiments show that our learned rewriter achieves the best privacy-utility tradeoff, achieving up to +10.1 average utility over on-device baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.03571v1">Channel Chart Location Privacy Based on Geo-Indistinguishability</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-06-02T12:39:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Atsu Kokuvi Angélo Passah, Rodrigo C. de Lamare, Arsenia Chorti</p>
    <p><b>Summary:</b> Channel charting enables location-based services (LBSs) without requiring explicit position information by using pseudo-locations from the channel chart. While this property implies inherent privacy advantages, it does not provide formal privacy guarantees. In this work, we address location privacy in channel charting referred to as chart location indistinguishability (CLI), which extends geo-indistinguishability (GI) to channel charting representations. In order to achieve CLI, a standard planar Laplace mechanism is investigated and a geometry-aware Mahalanobis norm planar Laplace (MNPL) mechanism is devised. The proposed MNPL mechanism perturbs the channel chart by injecting noise aligned with the local structure of the chart. In the CLI framework with MNPL, privacy is defined in latent channel chart manifolds using locally adaptive covariance derived from chart neighborhoods, while preserving manifold topology under privacy constraints. In addition, differential privacy is considered as a privacy baseline. The proposed approach is evaluated across multiple channel charting schemes. The performance is assessed using utility metrics such as quality loss (QL) and range query error (RQE), as well as geometry-aware metrics including trustworthiness (TW) and continuity (CT). Numerical results demonstrate that the proposed privacy mechanism provides strong privacy guarantees while preserving the channel chart for LBSs tasks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.03513v1">Privacy-Preserving High-Resolution Image Gradient Computation Based on Fully Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-02T11:32:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yufei Zhou</p>
    <p><b>Summary:</b> With growing emphasis on privacy protection, homomorphic encryption (HE) has emerged as a core method for privacy-preserving image processing, as it enables operations directly on encrypted data. However, existing research predominantly focuses on low-resolution image processing, and techniques for privacy-preserving high-resolution image processing remain underexplored. As the image size increases, the HE parameters must be adjusted accordingly, and directly applying existing methods can lead to significant computational overhead. In this work, we propose a multi-ciphertext privacy-preserving framework for large images, enabling efficient image encryption and computation under the semi-honest model. Specifically, we divide the large image into multiple sub-images, which allows us to maintain smaller HE parameters and reduce key size. By parallel processing the sub-image ciphertexts and introducing a new bootstrapping placement strategy, we significantly reduce encryption overhead and enhance user experience. On the server side, we optimize the large image convolution operation through a repeated packing technique and implement the Sobel operator computation based on HE. To improve gradient direction calculation for the Sobel operator, we introduce a new polynomial approximation method for the reciprocal function based on the sign function, which can be applied to other HE-based protocols.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.03399v1">Selective Token-Level Cryptographic Redaction for Privacy-Preserving Clinical Deployment of Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-02T09:40:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Farhan Sheth, Ziyuan Yang, Yongying Lan, Si Yong Yeo</p>
    <p><b>Summary:</b> While large language models (LLMs) are increasingly used for clinical applications, many existing pipelines require sending raw sensitive health information to remote servers for processing, which heightens the risk of privacy leakage. A natural approach to mitigate this risk is to encrypt the data before transmission. However, straightforward solutions such as encrypting the entire dataset introduce prohibitive computational, alignment, and communication overheads, rendering large-scale practical deployment infeasible. To preserve privacy while maintaining usability, we present Healthcare Encryption & Redaction via Adaptive Linguistic Decomposition (HERALD), a token-level cryptographic redaction framework designed to achieve this balance by encrypting only sensitive tokens while preserving the surrounding context for downstream model utility. HERALD combines medical named-entity recognizer (NER) with part-of-speech (POS) driven policies to select candidate tokens, performs targeted lemmatization to stabilize surface forms, and substitutes each protected token with a deterministic ciphertext wrapped in explicit delimiters. Notably, HERALD is model-agnostic and operates entirely on the client side, ensuring that sensitive content remains encrypted throughout storage, transmission, and processing without requiring changes to downstream models. We evaluated HERALD on both classification and medical question answering (MQA) tasks on public datasets. Across different tasks, experiments illustrate that fully secured baselines suffer significant utility loss, whereas HERALD consistently recovers performance close to plaintext. Overall, HERALD provides a novel utilization pipeline.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.03248v1">Investigating Novice Researchers' Perceptions of Research Privacy Within LLM-Assisted Workflows</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-06-02T07:10:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuning Zhang, Changxi Wen, Eve He, Ying Ma, Robert Xiao, Xin Yi, Hewu Li</p>
    <p><b>Summary:</b> Large Language Model (LLMs)-assisted scholarly workflows introduce critical privacy and intellectual property risks. As a uniquely vulnerable cohort driven by publication pressure and a lack of institutional support, novice researchers rely heavily on public LLMs, compelling them to navigate high-stakes privacy-publication trade-offs. To investigate these concerns, we conducted semi-structured interviews with 44 researchers across diverse disciplines. Our findings reveal that the fear of idea leakage paradoxically accelerates, rather than deters, reliance on LLMs, as researchers utilize them to expedite publication. They also held misconceptions that their ideas lacked the unique value to attract targeted attacks, and that their inputs would be safely diluted within massive datasets, preventing reconstruction. From interviews, we identified five types of mitigations including input fragmentation and adversarial probing, though we found that participants largely perceived these measures as ineffective. We outline implications including implementing institution-level sandboxed isolation, scenario-based privacy pedagogy, and verifiable data-deletion audits for transparency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.03190v1">Focused on the User, Overlooking the Risks: Security and Privacy Understandings, Practices and Challenges of Independent Chinese AI Agent Developers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-06-02T05:49:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuning Zhang, Mingyao Xu, Zhixin Huang, Yutong Jiang, Rongjun Ma, Yuting Yang, Xin Yi, Kanye Ye Wang, Hewu Li</p>
    <p><b>Summary:</b> The proliferation of AI agents empowers independent developers, defined as individual or small groups who self-initiate projects rather than fulfill client-based contracts, to create sophisticated autonomous systems, but also introduces novel security and privacy (S&P) challenges beyond traditional corporate structures. We conducted an interview study (N=28) with Chinese developers, whose extensive use of global LLM services offer valuable insights into this population. We investigate their understandings, practices and challenges of S&P challenges in their developed AI agent products. We revealed that independent developers frequently think and act from their users' perspective. They focused on user-facing safety risks such as harmful content while exhibiting low awareness of security vulnerabilities. Consequently, developers rely almost exclusively on ad-hoc, manually crafted safeguards and informal communication, with an absence of formal tools or processes for S&P practices. We found these actions are driven by various inhibitors, primarily a lack of formal training on S&P related skills, accessible security tools and actionable guidance from platforms. Our work contributed the first exploration of independent AI agent developers' S&P understanding, outlining opportunities for tailored security tooling.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.02958v1">Echelon: Auditable Aggregate-Only Language-Model Adaptation Across Privacy Boundaries</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-01T23:28:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hina Dixit, Punit Kumar, Irene Tenison, Nevasini Sasikumar</p>
    <p><b>Summary:</b> Cross-organization language-model adaptation increasingly faces hard governance constraints: in many deployments, device-level model state-parameters, activations, optimizer state, and per-device updates-cannot be exported outside an administrative boundary. Existing distributed and federated stacks typically assume cross-site model exchange and then retrofit privacy mechanisms, which complicates compliance and makes auditing brittle. We present Echelon, a boundary-first training architecture that enforces device-level model-state non-export as a systems invariant. Devices train locally inside each boundary; the only cross-boundary payloads are securely aggregated boundary-level deltas plus O(1) coordination metadata, exposed through a concrete audit surface. Restricting exchange to aggregates changes the optimization problem: the system must remain stable under WAN delay, heterogeneous participation, churn, and non-IID data even though the global plane never sees per-device updates. Echelon combines buffered semi-asynchronous secure aggregation, staleness-aware weighting, participation windows, proximal local objectives, and a drift-aware outer synchronization controller. In 1B-parameter LoRA adaptation across M= 2 boundaries, a budget-matched contest over three seeds (24.88M tokens) reaches validation loss 3.887 +/-0.010 and is best or tied-best among tuned low-communication baselines under fixed-token, fixed-bytes, fixed-wall-clock, and fixed-sync-count budgets. In OpenWebText stress tests, Echelon sustains 2,139-2,176 tokens/s across evaluated WAN and non-IID treatments, Echelon-DA improves time-to-target under WAN latency relative to a privacy-parityDiLoCo+SA baseline, and quality degrades by at most 2.2% under 200ms emulated latency or severe non-IID partitioning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.02563v1">IntraShuffler: A Privacy Preserving Framework for Heterogeneous DP Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-06-01T17:54:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Farhin Farhad Riya, Olivera Kotevska, Jinyuan Stella Sun</p>
    <p><b>Summary:</b> Heterogeneous Differential Privacy (HDP) in Federated Learning (FL) allows clients to select individual privacy budgets ($\varepsilon_i$) according to institutional policies and data sensitivity. In practice, many HDP-FL systems employ $\varepsilon$-aware server aggregation to improve model utility by re-weighting client updates according to their declared privacy budgets. However, gradient updates in FL retain structural patterns induced by non-independent and identically-distributed (non-IID) data, and these additional signals exposed by $\varepsilon$-aware aggregation create new opportunities for inference by an honest-but-curious server. In this work, we first show that a server equipped with gradient denoising and surrogate modeling can mount a \emph{Privacy Inference Attack} that infers distributional attributes of clients and links updates from the same client across training rounds, measured via surrogate inference accuracy and linkage success, under realistic knowledge constraints.
  The Shuffle-Model has been widely studied as a defense against such inference risks by anonymizing update sources, but it is fundamentally incompatible with HDP-FL $\varepsilon$-aware aggregation. To address this challenge, we propose \textbf{IntraShuffler}, a middleware defense framework designed for HDP-FL systems. IntraShuffler introduces a privacy-aware shuffling mechanism that groups clients into privacy-compatible buckets and performs parameter-level shuffling within each bucket to disrupt persistent gradient structure while preserving $\varepsilon$-aware aggregation. Experiments across four different datasets show that IntraShuffler reduces gradient recoverability by over 60% and decreases surrogate inference accuracy from 0.78 to 0.33 while maintaining comparable model utility across multiple FL aggregation rules.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.02483v1">Ghost Tool Calls: Issue-Time Privacy for Speculative Agent Tools</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-06-01T16:53:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bardia Mohammadi, Lars Klein, Akhil Arora, Laurent Bindschaedler</p>
    <p><b>Summary:</b> Tool-augmented language agents speculatively issue likely future tool calls to hide latency, but those calls leak inferred user intent to external services before the agent commits to the branch. Every external observer that received the call retains the disclosure after the agent abandons the branch. Timing is the issue, not authorization: no commit-time cleanup, read-only restriction, or access-control allow-list unsends what an observer already holds. We call these invocations ghost tool calls and propose Speculative Tool Privacy Contracts, a runtime abstraction that treats observation before commitment as a first-class effect, distinct from state mutation. We implement the contracts in a prototype runtime and evaluate twelve policies across three corpora. Speculative dispatch increases what an observer can infer about user intent; post-hoc filters, read-only restrictions, and access-control allow-lists leave that inference intact; only issue-time policies that change or suppress the speculative call's argument or destination projection before dispatch reduce it.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.02348v1">Privacy-preserving Information Sharing in Oligopoly Competitions</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB">
  <p><b>Published on:</b> 2026-06-01T14:58:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuxin Liu, M. Amin Rahimian</p>
    <p><b>Summary:</b> Information sharing among competing suppliers can improve decision-making under uncertainty, yet strategic concerns regarding rival exploitation often deter voluntary disclosure. We study information-sharing mechanisms in a Cournot oligopoly with uncertain demand, where a platform aggregates suppliers' signals through privacy-preserving channels and may also possess an exogenous external signal. The central challenge is to balance strategic safety with informational utility: privacy noise reduces the exposure of individual signals, but also lowers the value of the shared information pool. We first characterize a baseline setting in which access to aggregated information is contingent on participation. In a two-firm market without an external signal, firms refuse to share regardless of the privacy level. In an \(n\)-firm market, sharing may arise even without privacy safeguards because non-participating firms lose access to the aggregated signal. Building on this baseline, we show that privacy protection alone is insufficient to incentivize disclosure; it must be combined with a sufficiently informative external signal. We further show that firms with more accurate private signals require stronger privacy protection. Overall, our results characterize the sharing-feasible region and highlight the complementarity between privacy design and the external information environment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.01908v1">Private and Stable Test-Time Adaptation with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-06-01T08:45:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zefeng Li, Qiaoyue Tang, Mathias Lecuyer, Evan Shelhamer</p>
    <p><b>Summary:</b> Test-time adaptation (TTA) can reduce error on new and different data by updating the model on these inputs during inference. However, these updates raise the issue of privacy w.r.t. the testing data, because the model parameters now depend on all past inputs. To control this privacy risk, we cast multiple popular TTA methods (Tent, EATA, SAR, DeYO, and COME) into differential privacy (DP) forms that apply per-sample gradient clipping and Gaussian noise for all updates. On ImageNet-C, our DP-TTA methods provide adequate privacy at small cost to accuracy, and in the low-privacy regime the clipping mechanism of DP can even improve the accuracy and stability of adaptation in the continual setting. These improvements to privacy and accuracy come at only modest computational overhead. These first results on private TTA raise awareness of the issue, inform the development of more private test-time updates, and identify per-sample clipping as an effective technique for improving the accuracy and stability of adaptation.</p>
  </details>
</div>

