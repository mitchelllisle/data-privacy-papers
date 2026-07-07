
<h2>2026-07</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.05251v1">Privacy-Preserving Robustness Verification for Neural Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Logic in Computer Science-662E9B">
  <p><b>Published on:</b> 2026-07-06T15:59:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nianyun Song, Xiaokun Luan, Yu Guo, Rongfang Bie, Meng Sun, Xiyue Zhang</p>
    <p><b>Summary:</b> Neural network verification and data privacy are inherently in tension: verification demands full access to model parameters and input data, yet both are increasingly restricted by privacy regulations and intellectual property constraints. This tension has left robustness verification impractical in privacy-sensitive domains. In this work, we address this gap with SecureCROWN, the first framework for privacy-preserving neural network robustness verification. Built upon secure two-party computation (2PC), our framework enables a model owner and a data owner to jointly compute certified robustness bounds -- revealing only the final result while provably protecting both parties' private data under the semi-honest security model. A key challenge is securely computing the conditional operations in Linear Bound Propagation, where the data-dependent branching is incompatible with standard secure computation protocols. We eliminate branching by formulating conditional logic as continuous arithmetic operations. Additionally, we introduce a Newton--Raphson refinement method to improve numerical stability. Extensive analysis and experiments show that SecureCROWN strictly matches plaintext verification results, while completing in 0.1--200s across varied model sizes and communication settings (LAN/WAN), demonstrating the feasibility of privacy-preserving neural network verification.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.05111v1">From Multiplicity to Vulnerability: Privacy Amplification Risk from One-Dataset-Multiple-Model Exposure</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-06T14:04:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qirui Huang, Na Li, Hongsheng Hu, Zhi Zhang, Anmin Fu, Yansong Gao</p>
    <p><b>Summary:</b> To efficiently exploit a valuable data source (e.g., facial or medical images), it is frequently harnessed to fulfill multiple learning objectives (e.g., facial recognition, age estimation, and race classification). Each trained model is then deployed as an independent API service for corresponding inference. However, the privacy risk introduced by this one-dataset-multiple-model (ODMM) paradigm is completely overlooked by the community.
  For the first time, this work reveals that the ODMM setting substantially amplifies privacy leakage. We establish a theoretical framework that proves that privacy leakage accumulates as more ODMM models are exposed, a phenomenon we term ODMM privacy composition. Guided by this theoretical foundation, we propose PRIME (Privacy Amplification RIsk from One-Dataset-Multiple-Model Exposure) to systematically assess this risk and quantify the resulting leakage using membership inference attacks (MIAs). Under black-box access to ODMM models, we design an aggregation mechanism that collectively captures carefully identified privacy signals leaked by individual ODMM models, and construct an attack meta-classifier over the aggregated meta-information to infer the membership status of a given sample jointly. Our results provide strong evidence that dataset reuse across ODMM models strikingly jeopardizes privacy, which is consistently evident across five privacy-sensitive image and textual benchmark datasets and diverse model architectures (from ResNet and ViT to Qwen3-1.7B), spanning three domains: facial analysis, medical imaging, and textual attribution analysis. While mitigations such as differential privacy can reduce the effectiveness of PRIME with trade-offs, our attack still consistently outperforms single-task MIAs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.04698v1">F-ACVAE: A Federated Adaptive Conditional Variational Auto-Encoder for Privacy-Preserving Intrusion Detection in IoT Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-06T05:58:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohammad Ansarimehr, Somayeh Changiz, Ehsan Baghishani, Ali Mousavi</p>
    <p><b>Summary:</b> The rapid proliferation of Internet of things (IoT) devices has significantly expanded the cyber-attack surface, necessitating robust and privacy-preserving intrusion detection systems (IDS). However, centralized learning approaches often suffer from severe performance degradation due to high-dimensional traffic data, extreme class imbalance, and highly non-independent and identically distributed (non-IID) data across heterogeneous edge devices. To address these challenges, this paper proposes F-ACVAE, a federated adaptive conditional variational autoencoder framework that enables collaborative model training across distributed IoT devices without sharing raw data. F-ACVAE incorporates selective parameter aggregation, where local encoders remain private while globally shared components are synchronized to preserve discriminative latent structures. To further enhance stability under extreme non-IID settings and feature distribution shifts, we introduce a novel constrained momentum Gaussian aggregation (CMGA) strategy that combines update clamping with momentum-based smoothing to mitigate client drift. Extensive experiments on the N-BaIoT dataset demonstrate that F-ACVAE achieves an average accuracy and macro F1-score of 99\%, outperforming state-of-the-art baselines. Moreover, the selective aggregation mechanism reduces communication overhead by approximately 62\%, making the framework particularly suitable for resource-constrained IoT environments. These results highlight the effectiveness of F-ACVAE in achieving high detection performance while ensuring privacy preservation and communication efficiency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.04209v1">Ball Differential Privacy: How to Mitigate Data Reconstruction with Less Noise</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-05T09:59:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joseph Margaryan, Nirupam Gupta</p>
    <p><b>Summary:</b> Vector embeddings of raw records, while not human-readable, do not preserve record privacy: an adversary can reconstruct training records from a released model even when that model is a simple convex classifier. Differential privacy (DP) is the principled defense, but its noise is calibrated to worst-case indistinguishability, hiding arbitrary single-record substitutions, including those far outside the set of plausible alternatives relevant to a reconstruction adversary. The result is noise far larger than what reconstruction robustness requires, degrading accuracy without a corresponding security benefit.
  We propose Ball-DP: enforcing epsilon-delta indistinguishability over single-record substitutions restricted to a ball of radius r under a distance metric d in the embedding space. A deployment facing only local reconstruction threats can choose a small r, thereby reducing noise and recovering accuracy. The radius makes the scope of the privacy claim explicit against reconstruction attacks; standard DP is recovered when r covers the entire admissible record domain. We provide noise calibrations for regularized convex learning problems under Ball-DP, and derive corresponding reconstruction-robustness certificates, called Ball-ReRo, that upper-bound an attacker's reconstruction success. By deriving the optimal finite-prior MAP reconstruction attack, we empirically audit Ball-ReRo certificates on seven benchmark learning tasks. Our experiments show that calibrating noise to Ball-DP improves utility, considerably exceeding the dilution of reconstruction robustness in high-privacy regimes, i.e., when epsilon is small.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.04004v1">Setting the Privacy Budget in Differential Privacy by Bounding Adversaries' Odds of Learning Sensitive Information</a></h3>
  
  <p><b>Published on:</b> 2026-07-04T19:57:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruwimal Y. Pathiraja, Jerome P. Reiter</p>
    <p><b>Summary:</b> Differential privacy is a mathematical definition of what it means to protect data subjects' privacy in data releases. Differential privacy depends on a parameter $ε$ known as the privacy budget. The value of $\varepsilon$ determines the nature of the privacy guarantee, with smaller values generally offering more privacy. However, reducing $\varepsilon$ also tends to decrease the accuracy of results protected with differentially private algorithms. Setting a value for $\varepsilon$ that satisfactorily balances this risk/accuracy trade off is complicated in practice, and there is not a standard approach to doing so. In part this is because practitioners may struggle to understand the privacy guarantee afforded by $\varepsilon$. We present an approach to interpreting and setting $\varepsilon$ in which (i) the practitioner establishes bounds on the posterior odds that adversaries can learn sensitive information, and (ii) the practitioner converts these bounds to values of $\varepsilon$. We illustrate the approach using data from a case control study.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.02932v1">PromptPET: Privacy-Utility Optimized Prompt Obfuscation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-07-03T03:59:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ke Yang, Olivia Figueira, Umar Iqbal, Athina Markopoulou</p>
    <p><b>Summary:</b> Privacy is an important challenge when users interact with AI chatbots, since users may share sensitive information, explicitly or implicitly, and AI chatbots can use this information for user profiling. In this paper, we aim to protect user privacy via a user-side mechanism that transforms sensitive information in a user prompt, while preserving enough information to elicit a useful response from the chatbot. This approach faces an inherent tradeoff between protecting privacy (i.e., avoiding profiling) and preserving utility (i.e., getting personalized and task-specific responses). To that end, we consider, evaluate, and compare four different obfuscation actions, namely redaction, abstraction, replacement, and a novel noising/denoising scheme that we introduce. Additional novel insights include: utilizing a data type taxonomy to both identify and obfuscate sensitive information and explicitly taking into account the utility of chat responses in making the obfuscation decision. First, we systematically optimize and evaluate each obfuscation action independently in terms of the privacy-utility tradeoff it achieves. Second, we propose PROMPTPET, an LLM-based agent that selects the best obfuscation action for each sensitive part of the prompt, using a reinforcement-learning inspired rule optimizer, applied for the first time in this context. Using a real-world chat dataset, we show that PROMPTPET matches the best privacy-utility tradeoff attainable by any single obfuscation action and significantly outperforms prior state-of-the-art approaches.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.02903v1">TIER: Trajectory-Invariant Explanation Regularization for Membership Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-07-03T02:59:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Varun Sharma, Kar Wai Fok, Vrizlynn L. L. Thing</p>
    <p><b>Summary:</b> Explainability is central to building trustworthy AI, yet explanation interfaces can inadvertently provide adversaries with an expanded privacy-related attack surfaces. Recent studies show that advanced membership-inference attacks succeed by exploiting confidence-drop trajectories, induced through attribution-guided perturbations, as discriminative features, rather than directly using confidence scores or explanation vectors. Existing defenses against membership inference fail to directly mitigate such explanation-driven attacks. In this work, we investigate whether, during training, a model's own gradients can be leveraged as defense signals against such attacks, thereby aligning explanation profiles between members and non-members. To this end, we propose a Trajectory-Invariant Explanation Regularization (TIER) defense that penalizes erratic fluctuations in confidence drops simulated through gradient-guided perturbations and simultaneously minimizes the distributional shifts via KL-divergence. Unlike conventional adversarial training, which emphasizes label robustness, our approach targets explanation robustness by enforcing self-consistency through KL-divergence and reducing the variance of confidence drops between members and non-members. Extensive experiments confirm that our method effectively mitigates these attacks, delivering privacy protection while maintaining model utility and explanation fidelity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.02814v1">SovereignNegotiation-Bench: Evaluating User-Owned Personal Agents In Delegated Bargaining Under Privacy, Consent, Evidence, And Institutional Pressure</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-07-02T23:03:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dylan Zongmin Liu</p>
    <p><b>Summary:</b> Personal agents will increasingly negotiate on behalf of users: splitting costs with other personal agents, appealing platform decisions, escalating support disputes, requesting refunds, changing subscriptions, and negotiating deadlines or reimbursements. Existing negotiation benchmarks emphasize agreement, surplus, or strategic competence, but a user-owned agent can reach an agreement while harming the user through privacy leakage, consent violation, unsupported advocacy, over-concession, failed escalation, or poor auditability. We introduce SovereignNegotiation-Bench, a trace-level multi-turn benchmark for delegated personal-agent negotiation under private utilities, disclosure constraints, evidence requirements, and institutional asymmetry. The benchmark separates agent-visible observable state from evaluator-only labels and evaluates agreement success jointly with user utility, privacy, consent, evidence grounding, concession discipline, escalation, and auditability. We report an artifact-backed validation over 240 scenarios, 4 model families, 14 baselines, 13,440 frozen-prompt live trajectories, 61,135 parsed action rows, and a blinded 3-annotator audit over 300 items. The strongest agreement-maximizing baseline achieves the highest agreement rate but low user utility and high privacy/consent risk; FullSovereign does not maximize agreement, but obtains the best sovereign negotiation score by preserving utility, minimizing leakage, grounding claims, and reducing unauthorized commitments. The results show that agreement success is insufficient for user-owned negotiation agents.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.02187v1">Privacy-Preserving and Verifiable Approximate Distributed Coded Computing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-02T13:57:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xavier Martínez-Luaña, Alba Gude-Santos, Manuel Fernández-Veiga, Rebeca P. Díaz-Redondo</p>
    <p><b>Summary:</b> Distributed machine learning enables collaborative model training without centralizing data, but it also exposes learning processes to privacy leakage and malicious manipulation. Existing defenses typically address these threats in isolation and are often tailored to specific learning paradigms or model architectures, limiting their applicability in realistic deployments. In particular, federated learning and decentralized learning exhibit distinct adversarial surfaces that are rarely addressed within a unified framework. In this paper, we present a model-agnostic framework for adversary-resistant distributed learning that jointly addresses privacy preservation and malicious behavior across both federated and decentralized settings. Our approach combines paradigm-specific defense mechanisms with GPBACC, a privacy-enhancing coded computing technique applicable to arbitrary machine learning models. For federated learning, we integrate robust aggregation strategies to mitigate the impact of malicious participants, while for decentralized learning we employ approximate decode-and-compare and group testing techniques to enable lightweight verification and adversary isolation without relying on a trusted aggregator. Crucially, we evaluate the proposed framework through an explicit, attack-driven analysis. We implement representative privacy attacks and malicious behaviors, and empirically demonstrate that the combination of GPBACC with robust aggregation and verification mechanisms significantly reduces privacy leakage and improves resilience against active adversaries. These results suggest that privacy-enhancing coded computing, when combined with appropriate adversary-resistance strategies, provides a practical and deployable foundation for secure distributed machine learning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.02038v2">Hierarchical Anti-Aesthetics: Protecting Facial Privacy against Customized Diffusion Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-07-02T11:05:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Songping Wang, Yueming Lyu, Shiqi Liu, Chen Zhao, Ziyuan Chen, Ning Li, Jing Dong, Caifeng Shan</p>
    <p><b>Summary:</b> The rise of customized diffusion models has fueled a boom in personalized visual content creation, but it also introduces serious risks of malicious misuse, thereby posing threats to personal privacy. Image aesthetics are strongly correlated with human perception of image quality. Motivated by this observation, we address facial privacy protection from a novel aesthetic perspective by degrading the generation quality of maliciously customized models, thus reducing facial identity leakage. Specifically, we propose a Hierarchical Anti-Aesthetics (HAA) framework that exploits aesthetic cues at multiple perceptual levels. HAA consists of two key branches: (1) Global Anti-Aesthetics, which degrades overall aesthetics and generation quality by constructing a global anti-aesthetic reward mechanism and a corresponding loss; and (2) Local Anti-Aesthetics, which disrupts facial identity by using a local anti-aesthetic reward mechanism and loss to guide adversarial perturbations toward facial regions. By integrating both branches, HAA achieves anti-aesthetic degradation from a global to a local level during customized generation. Extensive experiments show that HAA outperforms existing methods in identity removal, providing an effective tool for protecting facial privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.01492v1">Unveiling the Non-Monotonic Effect of Privacy on Generalization under Byzantine Robustness</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2026-07-01T21:42:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Thomas Boudou, Batiste Le Bars, Nirupam Gupta, Aurélien Bellet</p>
    <p><b>Summary:</b> Recent work has established a fundamental trilemma between Byzantine robustness, local differential privacy (LDP), and optimization error in distributed learning. We show that this trilemma does not universally extend to generalization error, but instead depends critically on the privacy regime. Specifically, in the high-noise regime (strong privacy), we prove that increasing privacy reduces the generalization error, i.e., there is no tension between robustness and privacy. In the low-noise regime (weaker privacy), however, the tension between robustness and privacy reappears and increasing privacy indeed degrades generalization. Our theory explains this surprising non-monotonic behavior of the generalization error via matching lower and upper bounds on the algorithmic stability of Byzantine-robust distributed learning under LDP constraints. We corroborate and further analyze these theoretical findings with empirical evaluations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.02611v1">Privacy-Preserving Industrial Ergonomics: mmWave-Based Automated REBA Scoring and Pose Estimation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-07-01T15:41:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xuhan Zhang, Zhuangzhuang Dai, Luis J. Mans, Victor Chang</p>
    <p><b>Summary:</b> Work-related Musculoskeletal Disorders (WMSDs) require continuous ergonomic assessments. While Rapid Entire Body Assessment (REBA) is a gold-standard observation tool, manual monitoring is labor-intensive, and vision-based automation leads to privacy concerns. This paper proposes a novel end-to-end multi-task learning framework for privacy-preserving ergonomic assessment using millimetre-wave (mmWave) radar. A spatio-temporal backbone reconstructs 3D human skeletons, which serves as the biomechanical foundation for a subsequent regression head to generate REBA risk scores. To overcome the sparsity of radar point clouds, we utilise a multi-objective loss function incorporating biomechanical limits and temporal smoothness constraints. Furthermore, we implement an oversampling strategy to address the imbalance of high-risk postures in existing datasets. Experimental results on MMFi dataset demonstrate that our framework achieves a Categorical Accuracy of 77.78% and real-time performance with an inference latency of 5.70 ms. Our method reaches a High-risk REBA MAE of 0.93, which significantly outperforms both direct regression and two-stage pipelines in high-risk scenarios, providing a robust solution for non-invasive industrial ergonomic assessment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.01019v1">Toward a Unified Security and Privacy Framework for AI-Native 6G Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-01T14:52:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bidushi Barua, Ahsan Khan, Kangfeng Ye, Panagiotis Papanastasiou, Yifan Liu, Mohit Bidikar, Anthony Moulds, Julie McCann, Poonam Yadav</p>
    <p><b>Summary:</b> Sixth Generation (6G) communication networks are expected to evolve into AI-native, highly autonomous ecosystems that integrate communication, computing, sensing, and artificial intelligence. While these capabilities enable unprecedented connectivity and intelligent services, they also create a highly heterogeneous security and privacy landscape that cannot be addressed through isolated, technology-specific solutions. This paper presents a comprehensive survey of security and privacy in AI-native 6G networks from a cross-layer perspective. We first examine the fragmentation of existing security and privacy approaches across emerging technologies, network architectures, AI systems, and standardization efforts, motivating the need for a unified security and privacy framework. Building upon this framework, we develop a cross-layer threat taxonomy encompassing infrastructure, network and architectural, AI, privacy, and security management domains, and analyze representative threats across key AI-native 6G technologies. Furthermore, we map these threats to corresponding cross-layer countermeasures, including standards harmonization as a security function, and identify critical research gaps and future priorities for secure, interoperable, and trustworthy AI-native 6G ecosystems. Finally, we discuss future research directions toward realizing secure, privacy-preserving, resilient, and globally interoperable 6G networks. This survey provides researchers, practitioners, and standardization communities with a holistic foundation for the design, evaluation, and deployment of trustworthy AI-native 6G systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.00978v1">Privacy-Preserving Depth-Only Open-Vocabulary 3D Semantic Segmentation Via Uncertainty-Guided Test-Time Optimization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E">
  <p><b>Published on:</b> 2026-07-01T14:12:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xuying Huang, Sicong Pan, Maren Bennewitz</p>
    <p><b>Summary:</b> Privacy-preserving perception is a critical requirement for deploying 3D scene understanding systems in real-world indoor environments, yet it remains underexplored in open-vocabulary 3D semantic segmentation. Existing methods typically rely on obtaining rich semantic cues from RGB images, which may expose privacy-sensitive visual information. Depth-only 3D geometry provides a privacy-preserving alternative, but the absence of appearance-based semantic cues makes open-vocabulary predictions highly uncertain and less reliable. Under this setting, we propose to convert uncertainty into a guidance signal to identify unreliable semantic responses and use semantic priors from foundation models to regularize their refinement. We present UTTO, an uncertainty-guided test-time optimization framework for depth-only open-vocabulary 3D semantic segmentation. Without additional training, experiments on ScanNet20, ScanNet40, and ScanNet200 demonstrate that UTTO consistently improves depth-only open-vocabulary 3D segmentation and outperforms representative baselines under privacy-preserving conditions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.00772v1">No Country for Old Privacy: The Evolving Challenges of Anonymity in Bitcoin</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-01T10:57:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ben Hawkins, Joshua Levett, Siamak F. Shahandashti</p>
    <p><b>Summary:</b> We present a longitudinal measurement study on the adoption of detectable, second-generation anonymisation protocols in the Bitcoin network, including CoinJoin, CoinSwap, CoinShuffle and Stealth Addresses. By implementing and refining a suite of heuristic filters, we identify over 5.94 million CoinJoin and 23.3 million CoinSwap transactions. Besides, the use of CoinShuffle was unexpectedly found to be closely aligned with the Wasabi wallet operation period. Our analysis reveals consistently low adoption rates, with these protocols constituting less than 1% of network transactions, and a sharp decline in detectable usage following key regulatory events. Furthermore, we find no evidence of standardised Stealth Address adoption, indicating a failure to converge on a common privacy standard. This study provides a comprehensive picture of a niche ecosystem whose on-chain visibility has been largely suppressed, strongly suggesting the migration of privacy-seeking users to less transparent and less detectable methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.00693v1">The Rise and Fall of Google's Privacy Sandbox</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-01T09:43:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rachid Youssef Grib, Alberto Verna, Nikhil Jha, Martino Trevisan, Marco Mellia</p>
    <p><b>Summary:</b> On October 17th, 2025, Google announced the retirement of most Privacy Sandbox APIs, concluding nearly five years of experimentation with its alternative to privacy-invasive data collection on the Web. Designed to balance privacy with advertising functionality and cross-site tracking, the initiative faced repeated redesigns and limited ecosystem support.
  In this work, we present the first longitudinal, consent-aware measurement of the Privacy Sandbox's deployment across the Web. Using a custom call listener and weekly crawls of the top-10,000 websites, we monitor the usage of all major APIs in the months preceding their retirement. Adoption had already stagnated well before Google's announcement: most APIs were used by only a handful of actors, whose activity declined steadily throughout our study. Even the APIs that Google plans to maintain show no sign of growth. The sole exception is Cookies Having Independent Partitioned State (CHIPS). Overall, the demise of the Privacy Sandbox leaves unresolved the challenge of enabling privacy-preserving interest-based advertising.</p>
  </details>
</div>



<h2>2026-06</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.31973v1">Semantic Leakage and Privacy Preservation in Relay-Assisted Semantic Communications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2026-06-30T17:15:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yalin E. Sagduyu, Tugba Erpek, Aylin Yener, Sennur Ulukus</p>
    <p><b>Summary:</b> Semantic communication (SemCom) has emerged as a promising paradigm in which the transmission of task-relevant information is prioritized over raw data, enabling efficient and robust communication under resource and channel constraints. In this paper, the privacy implications of relay-assisted SemCom systems are studied, where the intermediate relay node operates directly on learned latent representations. It is shown that the relay, even without access to source data, can reliably infer semantic meaning and reconstruct signals with performance comparable to that of the legitimate receiver, revealing a fundamental privacy vulnerability of semantic representations. To address this issue, an iterative adversarial training framework is proposed in which a strong, adaptively trained eavesdropper at the relay is explicitly accounted for. The proposed approach alternates between optimizing the relay's eavesdropping function and the legitimate system, resulting in representations that preserve semantic decoding performance at the intended receiver while degrading semantic inference at the relay. The semantic accuracy gap between the legitimate receiver and the eavesdropper is significantly enlarged across channel conditions. Importantly, this protection is achieved in a stealthy manner, with high reconstruction fidelity maintained while semantic leakage is selectively suppressed.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.31164v1">Seeing Through the Weights: Privacy Leakage in Scene Coordinate Regression</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-06-30T05:54:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Oleksii Nasypanyi, Jaemin Cho, Utku Ozbulak, Byungkon Kang, Francois Rameau</p>
    <p><b>Summary:</b> Scene Coordinate Regression (SCR) methods are increasingly adopted for visual localization. In these approaches, the scene is implicitly encoded within a neural network that regresses a 3D world coordinate for each image pixel. Because the scene is represented only through the network parameters and not stored explicitly as images or maps, such methods are often assumed to be privacy-preserving. In this work, we show that this assumption is incorrect in practice.
  Specifically, we introduce a query-based attack that reconstructs the 3D geometry of the training environment from an SCR model under different levels of model access. To do so, we repeatedly query the model with batches of proxy images unrelated to the target scene to obtain dense pixel-wise 3D coordinates. Reliable points are identified through their stability under small input perturbations and can be further refined in a white-box setting. These stable points are accumulated across independent query batches to recover the scene geometry. From the recovered 3D representation, we also invert the network features to synthesize images from arbitrary viewpoints, revealing additional appearance information.
  Experiments on indoor and outdoor datasets demonstrate that substantial portions of training environments can be reconstructed with high geometric fidelity. Beyond geometry, we also recover an approximate color appearance, which exposes recognizable layout and potentially sensitive scene elements. This directly contradicts claims in the literature that SCR representations are privacy-preserving by design, and reveals a real risk when such systems are deployed in private or security-critical spaces. The project page is available at https://jaeminch0.github.io/seeing-through-the-weights-privacy-leakage-in-scene-coordinate-regression.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.30329v2">Cohort-amortized personalization: navigating the privacy-utility frontier for virtual brain twins</a></h3>
  
  <p><b>Published on:</b> 2026-06-29T14:10:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Amirhossein Esmaeili, Marmaduke Woodman, Nina Baldy, Abolfazl Ziaeemehr, Julia Makhalova, Huifang Wang, Daniele Marinazzo, Svenja Caspers, Fabrice Bartolomei, Meysam Hashemi, Viktor Jirsa</p>
    <p><b>Summary:</b> Personalized generative brain models require individual neuroimaging data that privacy constraints and re-identification risk make difficult to share, while per-subject fitting procedures cost hours of compute -- limiting clinical translation and multi-site collaboration. We introduce cohort-amortized personalization (CAP), which replaces data sharing with model sharing: a neural density estimator is trained on simulations from a mechanistic whole-brain model under a low-rank cohort prior, and only the compact estimator is distributed, so new subjects are personalized in seconds on their own data alone. To make this prior both compact and atlas-independent, a cross-atlas autoencoder (CrossCoder) maps connectomes from 20 anatomical atlases into a shared latent space, enabling deployment across sites with heterogeneous atlases. We validate CAP on two cohorts: 21 patients with drug-resistant epilepsy (epileptogenic-zone localization F1=0.56) and 832 subjects from the 1000BRAINS aging cohort (predicted age r=0.44); in both, CAP matches or exceeds per-subject inference with hours-to-seconds speed-up. Because the shared artifact couples a cohort prior to a mechanistic simulator, it can serve as a mechanistic surrogate supporting in-silico experimentation and synthetic-cohort generation without raw-data access -- a governance-audited alternative we term synthetic access, allowing for wider adoption of personalized modeling in more diverse settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.29835v1">A Sieve-Accelerated Quadrature Method for Exact Privacy Accounting in the 2020 U.S. Decennial Census</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Numerical Analysis-D91E36">  
  <p><b>Published on:</b> 2026-06-29T06:19:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Buxin Su, Weijie Su, Chendi Wang</p>
    <p><b>Summary:</b> In 2020, the U.S. Census Bureau adopted differential privacy for the Decennial Census by injecting integer-valued Gaussian noise into published census tabulations. Exactly evaluating the privacy guarantees of these data releases would enable the Bureau to determine the absolute minimum noise required to satisfy a given privacy budget, preventing the injection of unnecessary excess noise and thereby substantially enhancing the statistical utility of the data for downstream applications such as federal funding allocation and political redistricting. In this paper, we introduce a computationally efficient and mathematically rigorous quadrature method to evaluate the exact privacy profile of practical, large-scale census releases under the composition of heterogeneous discrete Gaussian mechanisms. Mathematically, this problem reduces to evaluating the tail probabilities of high-dimensional convolutions of integer-valued random variables sampled from heterogeneous discrete Gaussian distributions under exceptionally stringent numerical error tolerances (e.g., $10^{-35}$). By recasting the exact privacy accounting as a numerical integration problem via the discrete Fourier transform, we explicitly exploit the exponential convergence of the trapezoidal rule for complex analytic, periodic characteristic functions. Furthermore, to overcome the computational bottleneck of evaluating highly oscillatory integrands in high dimensions, we develop a sieve algorithm that identifies and prunes negligible quadrature nodes, accelerating the computation by three orders of magnitude. Taken together, these numerical innovations enable the first exact, assumption-free privacy accounting for the 2020 Census Demographic and Housing Characteristics File, achieving a 1,824-fold speedup over prior methods while maintaining census-mandated error tolerances.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.29673v1">Privacy-Preserving Decentralized Cooperative Localization with Range-Only Measurements: A Convex Optimization Based Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E"> 
  <p><b>Published on:</b> 2026-06-29T00:39:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nitesh Kumar, Reyshwanth Ganeshan, Sixu Li, Sivakumar Rathinam, Swaroop Darbha</p>
    <p><b>Summary:</b> Cooperative localization using range-based measurements is critical for multi-robot systems operating in GPS-denied and unstructured environments. However, traditional cooperative approaches require sharing explicit spatial coordinates across the network, presenting a severe security vulnerability in privacy-sensitive missions. While recent literature has explored privacy-preserving alternatives, these methods typically rely on accuracy-degrading noise injection or computationally prohibitive cryptographic protocols. To overcome these limitations, we propose a novel, natively privacy-preserving Decentralized Cooperative Localization (DCL) framework based on convex optimization. Discarding probabilistic noise models, we assume strictly bounded measurement noise and formulate the localization problem via Semi-Definite Programming (SDP) to compute a Maximum-Volume Inscribed Ellipsoid (MVE). Our approach introduces novel intersection-plane constraints derived from landmark measurements to significantly tighten individual spatial bounds. To incorporate inter-robot range measurements securely, we uniquely decompose coupling constraints into localized Linear Matrix Inequalities (LMIs). Agents achieve fleet-wide spatial consensus by iteratively exchanging only abstract dual variables, completely avoiding the transmission of explicit primal position estimates. Extensive 3D Monte Carlo simulations demonstrate that our DCL framework outperforms existing SDP-based localization method in accuracy, while guaranteeing operational privacy and maintaining highly scalable, parallelizable computation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.29567v1">SurrogateShield: Beyond Redaction for High-Utility, Privacy-Preserving LLM Interactions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-06-28T19:14:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sherwin Vishesh Jathanna</p>
    <p><b>Summary:</b> LLM-based assistants transmit user queries verbatim to third-party API endpoints that lie outside the user's audit or control. When those queries contain personally identifiable information (PII), the data persists on remote infrastructure subject to breach, subpoena, or policy change. Placeholder redaction (the prevailing mitigation) suppresses PII at the cost of semantic coherence, producing structurally degraded queries and correspondingly degraded responses.
  We present SurrogateShield, a client-side proxy that substitutes detected PII with locally generated, type-consistent surrogate values prior to transmission and restores originals in the response. No real PII crosses the network boundary. Detection runs through a three-stage cascade (PatternScan, EntityTrace, and ContextGuard) covering 22 PII types and quasi-identifier combinations grounded in Sweeney's k-anonymity framework. Surrogate-to-original mappings are sealed in an AES-256-GCM encrypted per-conversation ShadowMap that never leaves the device.
  Evaluations on a 1,124-query corpus demonstrate that the cascade reliably detects PII, achieving an overall F1 score of 98.87%. Surrogate substitution substantially outperforms placeholder redaction in semantic utility, yielding a 13.26 pp improvement in BERTScore (roberta-large), from 81.59% to 94.85%. Within this corpus, the local pipeline restricted real PII transmission across all tested query types; in a 100-query adversarial trial, a prompted LLM adversary recovered no original values from surrogate-substituted messages.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.29417v1">Bit-ViP: Leveraging Bit-planes to Preserve Visual Privacy in Images through Obfuscation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2026-06-28T14:28:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vishesh Kumar Tanwar, Ashish Gupta, Sanjay Madria, Sajal K. Das</p>
    <p><b>Summary:</b> The unprecedented growth of computer vision applications, such as surveillance systems and social media, raises security and visual privacy concerns, especially when data is stored on cloud servers. Image obfuscation offers a way to preserve visual privacy while maintaining an adequate level of usability; thus, it has been a topic of great interest in recent years. However, prior obfuscation schemes are either vulnerable to malicious attacks, such as model inversion to reconstruct original images from obfuscated images, or generate non-trainable obfuscated images, making them unusable for achieving reasonable accuracy. This paper proposes a novel bit-plane-based image obfuscation scheme, {\em Bit-ViP}, to preserve visual privacy for image-based recognition tasks. The Bit-ViP scheme produces secure, usable images by incorporating an innovative end-to-end obfuscation function. While doing so, the obfuscated image would contain non-invertible noise (generated by Lorenz's chaotic system and differential privacy), making it hard for an adversary to reconstruct the original image. We conduct extensive experiments on two popular activity recognition datasets, namely UCF101 and HMDB51, to validate the effectiveness of Bit-ViP. In the face of attacks on reconstruction, pixel frequency, information entropy, and pixel inter-correlation, we present a rigorous security analysis demonstrating tangible improvements over existing schemes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.29412v2">Privacy-Aware State Estimation: From Coarse to Precise Privacy Protection</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-06-28T14:20:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhongyao Hu, Jason J. R. Liu, Jun Shang, Zhan Shu</p>
    <p><b>Summary:</b> This paper addresses the problem of achieving both coarse and precise privacy in state estimation. Coarse privacy forces the eavesdropper's total mean-square error (MSE) to infinity, but errors along certain confidential directions may remain bounded. This motivates precise privacy, which additionally drives the MSE along prescribed directions to infinity. For coarse privacy, an analytical transformation is established, preserving the user's optimality and driving the eavesdropper's total MSE to infinity at a polynomial-exponential rate. A stochastic intermittent encryption scheme is further developed, and an explicit lower bound on the encryption probability is derived to guarantee divergence. For precise privacy, by analyzing the behavior of the Riccati equation on the unobservable subspace, we prove that the eavesdropper's directional MSE becomes unbounded if and only if the direction's unstable component lies outside the observable subspace. Finally, a systematic method is proposed to exclude target vectors from the observable subspace, forcing the directional MSE to infinity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.29393v1">The Role of Online Forums in Developer Understanding of Privacy Law -- A Reddit Case Study</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2026-06-28T13:33:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sara. Haghighi, Clark LaChance, Ali Pourghasemi Fatideh, Travis Breaux, Sepideh Ghanavati</p>
    <p><b>Summary:</b> Software practitioners use online forums to navigate complex and often ambiguous legal privacy requirements, yet little is known about their professional backgrounds, what challenges they face, and how they use and assess the credibility of the advice received, or how they resolve ambiguities in posts. We report the findings of a survey of 223 Reddit users from regulatory-focused subreddits, complemented by a qualitative analysis of 2,248 posts and responses. Our results show that, despite holding privacy-related certifications, most participants frequently use forums to seek legal advice. Key challenges reported or identified include implementing a data protection impact assessment, reporting a data breach, and obtaining cookie consent. Reddit users often assess credibility by reviewing respondents' post history, verifying sources cited, trusting advice from recognized experts, and following up for clarity before responding. We highlight research and educational directions to bridge gaps in support needed for regulatory compliance guidance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.28479v1">Decomposing Memorization Reduction in Privacy-Preserving Fine-Tuning of SLMs for CSIRTs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-26T17:35:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Cristhian Kapelinski, Diego Kreutz</p>
    <p><b>Summary:</b> CSIRTs increasingly fine tune language models on vulnerability scan records, but these records expose internal network topology and create privacy risks under regulations such as GDPR and LGPD. We present the first empirical study of how DP SGD and HMAC pseudonymization interact when fine tuning small language models with 1B to 3B parameters on structured CSIRT data. We evaluate 96 LoRA adapters across four SLMs and four training regimes, including raw fine tuning, QLoRA with large batch training, and DP SGD with epsilon equal to 2 and 8. We also audit memorization using 20 planted canaries, four extraction attacks, and a dual attack targeting HMAC pseudonymized identifiers.
  Our results show three main findings. First, matched update controls reproduce the observed reduction in memorization by reducing the number of optimizer updates alone, accounting for 66 percent to 132 percent of the measured effect, with a mean of 100 percent across three seeds and four models. In this setting, DP SGD provides the formal privacy guarantee but does not produce additional measurable reductions in memorization. Second, HMAC pseudonymization removes the original identifiers from the exposure surface, reducing exposure by 40 percent to 61 percent, while pseudonymized identifiers remain close to the expected random baseline and do not become a secondary memorization target. Third, F1 scores remain between 0.19 and 0.28 across all 96 adapters using four shot prompting, indicating that, under the evaluated training budget, 1B to 3B SLMs do not achieve operationally useful performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.28061v1">ToolPrivacyBench: Benchmarking Purpose-Bound Privacy in Tool-Using LLM Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-26T13:08:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shijing Hu, Liang Liu, Zhu Meng, Zhicheng Zhao</p>
    <p><b>Summary:</b> Large language models (LLMs) have increasingly moved from standalone text generation systems to agents that invoke external tools, access environments, and execute multi-step tasks. However, conventional function-calling benchmarks mainly evaluate task completion and API correctness, while privacy evaluation benchmarks typically focus on final responses or privacy judgments. Neither perspective captures purpose-bound information flow across an executed multi-tool trajectory. Motivated by this limitation in current agent evaluation, ToolPrivacyBench audits whether task-private atoms are routed only to authorized tools and downstream sinks, thereby evaluating both task completion and privacy over-disclosure during tool use. The benchmark contains 2,150 cases, including 1,150 fully synthetic privacy-sensitive business workflows and 1,000 cases adapted from existing multi-tool and function-calling benchmarks. Each case is represented by a policy knowledge base. After an agent executes against mock business backends, the evaluator compares recorded tool arguments and backend audit logs with this policy knowledge base. The evaluation covers nine widely used agents to characterize purpose-bound privacy over-disclosure. The results show that successful tool execution does not imply appropriate privacy disclosure: an agent may complete a task while transmitting unnecessary private information through intermediate tool calls. ToolPrivacyBench therefore formalizes a need-to-know disclosure boundary, under which each tool should receive only the information necessary for its stated purpose, and uses trajectory-level auditing to identify privacy over-disclosure in multi-tool workflows.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.27936v1">Agentic AI-Powered Re-Identification: An Emerging, Scalable Threat to Mobility Microdata Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> 
  <p><b>Published on:</b> 2026-06-26T10:27:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Oscar Thees, Roman Müller, Matthias Templ</p>
    <p><b>Summary:</b> The widespread collection of fine-grained location data by commercial data brokers creates a re-identification risk that is not widely recognised by the public. While prior research has established that mobility traces are highly unique and that individuals can, in principle, be identified from a handful of spatio-temporal points, such attacks have historically required significant manual effort from skilled analysts, limiting their practical scale.
  In this feasibility study, we demonstrate in a real world setting that agentic AI fundamentally changes this threat model. We present an end-to-end pipeline in which large language model agents autonomously search the open web, cross-reference public records and social media, and resolve raw coordinate sequences to candidate identities - without human intervention. We evaluate the pipeline on a spatio-temporal dataset containing simulated location points anchored at and around true home and work addresses, focusing on a high-risk disclosure scenario. Our results demonstrate that, from spatio-temporal data and public sources alone, our agentic AI successfully re-identified 18 of the 25 re-identifiable individuals (72%) and 18 of 43 cases overall (41.9%).
  We discuss implications for Statistical Disclosure Control (SDC) practice and outline the near-future escalation that data custodians and regulators must anticipate. De facto anonymity - an implicit foundation of SDC practice - is shifting. Agentic AI strengthens the case that re-identification is reasonably likely by any means under the GDPR Recital-26 standard, at costs of minutes-and-dollars per target.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.27849v1">Differential Privacy over Hamming Codes</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-06-26T08:42:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Borzoo Rassouli, Morteza Varasteh</p>
    <p><b>Summary:</b> We consider the transmission of the outputs of counting queries over a binary symmetric channel (BSC), where Hamming codes are employed as the channel encoder. Since the channel is inherently noisy, this transmission already provides a degree of privacy protection ``for free'', albeit at the cost of reduced utility in the form of decoding errors. A natural question is whether this privacy can be further improved (i) without any additional real-time obfuscation of the data, such as injecting artificial noise prior to transmission, and (ii) without increasing the end-to-end error probability. In this work, we answer this question in the affirmative by deriving an optimal codeword arrangement that strictly improves differential privacy guarantees while incurring no real-time computational overhead and no degradation in utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.27558v1">Productionized Fairness Measurement Under Privacy Constraints</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-25T21:20:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Osonde A. Osoba, Yuzi He, Saikrishna Badrinarayanan, Varun Mithal, Sakshi Jain, Natesh S. Pillai</p>
    <p><b>Summary:</b> Fairness measurements in the form of disaggregated evaluations often rely on demographic signals that are legally constrained or culturally sensitive. Race and ethnicity signals are among the more difficult signals to curate and use for this task. This paper presents Privacy-Preserving Probabilistic Race/Ethnicity Estimation (PPRE) as a method for enabling fairness measurements with respect to race/ethnicity for U.S.\ LinkedIn members in a privacy-preserving manner. PPRE applies privacy technologies (specifically: secure two-party computation, differential privacy, and additive homomorphic encryption) on top of two race/ethnicity demographic signal sources (the Bayesian Improved Surname Geocoding estimator and a sparse golden survey set of self-reported demographics) to power a fairness measurement solution with respect to US-based race/ethnicity demographics. We detail its privacy guarantees and demonstrate its application on candidate- and viewer-side fairness measurements. We close with a transferable framework for institutions seeking to implement similar privacy-preserving measurement infrastructure.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.26664v1">TGHE: Template-based Graph Homomorphic Encryption for Privacy-Preserving GNN Inference in Edge-Cloud Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-25T06:55:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ngoc Bao Anh Le, Thai T. Vu, John Le, Heath Cooper, Jun Shen</p>
    <p><b>Summary:</b> Existing homomorphic encryption (HE)-based GNN systems adopt a graph-centric paradigm that couples per-query cost to global graph size, limiting evaluations to at most ~20k nodes and making them incompatible with dynamic, large-scale financial graphs. We propose TGHE (Template-based Graph Homomorphic Encryption), an ego-centric framework that resolves this by exploiting a template phenomenon: local computation trees in transaction graphs converge into a small set of structural shapes. TGHE canonicalizes ego-graphs at the edge and packs structurally identical trees into shared CKKS ciphertexts for SIMD-parallel encrypted inference, with two long-tail optimizers (Approximate Template Fitting and Topology Collapse) ensuring full SIMD coverage. On DGraphFin (3.7M nodes, 4.3M edges), TGHE-Collapse achieves a 66.9x speedup over the sequential encrypted baseline with less than 0.002 AUC loss.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.26627v1">Agents That Know Too Much: A Data-Centric Survey of Privacy in LLM Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-25T05:44:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nada Lahjouji, Ashwin Gerard Colaco</p>
    <p><b>Summary:</b> Large language model agents increasingly query databases, search document collections, call external APIs, remember past interactions, and act on a user's behalf. As they move from answering questions to operating over sensitive data, privacy becomes harder to enforce. An agent touches many data sources, runs multi-step workflows, keeps state across sessions, and acts with delegated permissions. Sensitive information can therefore leak not only through its final answer but through the queries it issues, the intermediate results it handles, the memory it writes, and the messages it exchanges with other agents. We survey the privacy of LLM agents from a data-centric view, organizing the field around the data an agent touches rather than by attack type, and we use data agent as shorthand for an LLM agent that works with data. Research on these risks is active but scattered across retrieval-augmented generation, text-to-SQL interfaces, agent memory, prompt injection, access control, and contextual privacy. This survey brings that work together: we taxonomize the data sources an agent touches, the privacy risks each source creates, and the governance mechanisms that address them; we map the benchmarks used to measure these risks and identify what is missing; and we set out the open problems. Two findings recur: among governance mechanisms only information-flow control covers both compositional and cross-session inference leakage, the two least-protected risks; and no benchmark drives an agent across its data surfaces under one privacy policy, the instrument the field most lacks. Our goal is a reference that situates the scattered literature and gives future work a common framing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.26412v1">What Browsers Do in the Shaders: A Measurement Study of WebGPU Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-24T22:11:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Igor Santos-Grueiro</p>
    <p><b>Summary:</b> WebGPU lets ordinary web pages run GPU workloads through a validated programming model. Validation protects memory safety, but shared browser, driver, OS, and GPU state can still expose privacy-relevant signals. We present WGPULens, a framework for measuring those signals across controlled scenarios, browser-native co-residency, a participant field study, public page loads, and mitigation policies. Our framework separates measurements: controlled scenarios support leakage, boundary, and mitigation claims; participant runs support deployment, compatibility, and fingerprintability; and a Tranco crawl measures WebGPU exposure in real-world pages.
  Our controlled results identify persistent pipeline compilation state as the clearest surface. Cold/warm pipeline probes reveal prior compilation state across selected origin, profile, and browser placements. Controlled browser/native experiments also show native GPU activity can be inferred from browser-visible observables under labeled workloads. Other resource probes provide weaker positive results and negative controls.
  The participant field study shows active WebGPU behavior is highly distinctive within the sample, with deterministic components stable within runs and lower exact stability across repeated visits. A page-load crawl finds WebGPU use mainly as adapter probing and static support code, with no observed page-load shader, pipeline, queue, query, or map activity. Mitigation pilots identify source-level key separation as a proxy for evaluating pipeline-cache partitioning. Overall, WGPULens shows that WebGPU privacy analysis must be surface-specific: browsers need to measure which GPU state crosses which boundary, which browser-visible signals reveal it, and what the corresponding mitigations cost.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.26403v1">ProfileFoundry: A Synthetic Person-Object Substrate for Privacy, Memory, and Tool-Use Evaluation in LLM Agent</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-06-24T21:43:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sriram Selvam, Anneswa Ghosh</p>
    <p><b>Summary:</b> Foundation-model research increasingly needs data about people: user state, personal histories, relationships, contact-like fields, documents, and longitudinal updates. Real user data is difficult to share, perturb, audit, or redistribute responsibly, while independently generated fake fields rarely preserve the cross-field and temporal consistency needed for controlled evaluation. We present PROFILEFOUNDRY, a deterministic generator and fixed reference release of 100,000 adult synthetic Person Objects across eight locales. Each object combines a typed current snapshot, household, family, and employer links, snapshot-aligned events, normalized relational views, and generation provenance. The release contains 709,228 events, 40,338 households, 52,491 employers, and 518,564 directed relationship edges. We report evidence in separate categories: selected population-marginal comparisons, per-object invariant checks, release-wide referential and temporal closure, and coincidence/provenance screens. PROFILEFOUNDRY is not a population-fidelity model, a rendered-text corpus, or a formal privacy mechanism. Instead, it is a responsible synthetic source layer for constructing downstream foundation-model evaluations involving memory, privacy, document understanding, record linkage, and agent state while keeping the synthetic person behind each artifact inspectable</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.26390v1">Lessons from the Adoption and Deprecation of the Privacy Sandbox Web APIs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-24T21:22:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yohan Beugin, Paul Barford, Patrick McDaniel</p>
    <p><b>Summary:</b> While several web actors have been trying to reduce web tracking for years, it remains unclear how to achieve both desirable levels of utility and privacy. In 2019, Google launched the Privacy Sandbox initiative to balance that trade-off and find privacy alternatives to common use cases such as advertising. Yet, in late 2025, Google canceled the project and deprecated most of the newly introduced APIs. Despite its end, the Privacy Sandbox represents a unique opportunity to learn about how the ecosystem reacted to the proposed changes and make observations about why and how it failed. In this paper, we present a longitudinal measurement and analysis study of the Privacy Sandbox APIs to characterize their adoption and deprecation over the past seven years by different web actors. Leveraging historical HTTP Archive crawls and public Chrome telemetry data, we offer the largest study of its kind into the prevalence of each Privacy Sandbox feature, during their entire respective lifetime (5+ years for some), on popular websites (CrUX top 100k), and as experienced by Chrome users during their browsing journey. Our results showcase an adoption that remained limited and uneven across the years; only few web actors implemented very specific APIs, and in disparate manners. We motivate our interpretation of these results by considering the incentives (interest, resources, timeline, etc.) and risks (potential trade-offs, privacy violations, and legal exposure, etc.) for these actors. Finally, our analysis also yields actionable recommendations for the next generation of web privacy proposals. More broadly, the Privacy Sandbox illustrates the limitations and disparities across browsers of ``fix it in the browser'' remedies: today, tracking and third-party cookies limitations in Chrome still remain largely opt-in, while they have been enabled by default on other browsers like Brave, Firefox, or Safari.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.26373v3">Hybrid privacy-aware semantic search: SVD-truncated document geometry and CKKS-encrypted query reranking under a restricted threat model</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2026-06-24T20:50:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sergey Kurilenko</p>
    <p><b>Summary:</b> Dense embeddings power semantic search and Retrieval-Augmented Generation, yet a leaked vector database leaks the text behind it, since embeddings invert with high fidelity. The textbook defences are extreme--homomorphic search is sound but far too slow at million-document scale, while privacy noise degrades ranking before it protects. We study a middle path built on an asymmetry: each static document vector is SVD-truncated and then rotated by a secret orthogonal transform held only by the data owner, while the dynamic query is protected cryptographically under CKKS, so an honest-but-curious server sees neither query values nor scores; the CKKS parameters are fixed by a small reproducible benchmark. We prove a tight lower bound on the reconstruction error of any decoder confined to the protected subspace. On a one-million-document, five-encoder corpus the wrapper preserves retrieval quality at sub-second latency--a mild linear denoiser on self-retrieval that reverses into a 2--8-point nDCG@10 cost on graded relevance--while an off-the-shelf inversion attack collapses to the floor. We then map the boundary: a known-plaintext attacker recovers the rotation by orthogonal Procrustes from about as many leaked pairs as the retained dimension, and the public quantization codes leak neighbour structure. The same geometry doubles as a privacy-preserving data-loss-prevention primitive for LLM firewalls, matching a plaintext detector at near parity. We state the limits plainly: query confidentiality is cryptographic, but document protection is an empirical obfuscation layer, not a cryptographic primitive.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.26073v1">Bayesian Nonparametric Privacy-Preserving Synthetic Data Generation: I. Discrete Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">
  <p><b>Published on:</b> 2026-06-24T17:47:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maria Chiara Menicucci, Mario Beraha, Stefano Favaro, Riccardo Lazzarini</p>
    <p><b>Summary:</b> Synthetic data generation is a powerful approach to privacy-preserving statistical analysis, where data-release mechanisms are governed by a privacy-utility tradeoff: they should provide privacy guarantees while preserving the statistical utility of confidential data. We develop a Bayesian nonparametric framework for private synthetic data generation tailored to discrete data. Specifically, the confidential data are modeled as a random sample from an unknown discrete distribution endowed with a Pitman-Yor process prior, and synthetic data are generated from the corresponding posterior-predictive distribution. Since the Pitman-Yor process defines an almost surely discrete random probability measure, the resulting mechanism is naturally suited to data with ties and settings involving a potentially large, unknown, or growing number of categories. We study differential privacy guarantees of the Pitman-Yor posterior-predictive mechanism across the three regimes of the discount parameter $σ\in(-\infty,1)$. For $σ\in(0,1)$, we establish an instance-level $(\varepsilon,δ)$-differential privacy guarantee. For $σ=0$ and $σ<0$, corresponding respectively to the Dirichlet process prior and to a parametric Dirichlet-Multinomial model, stronger guarantees are obtained, under suitable conditions on the released sample size. We also investigate statistical utility, or informativity, of the released data via the expected $1$-Wasserstein distance between the empirical distribution of the synthetic data and the "true" data-generating distribution. For $σ<0$ and $σ=0$, we prove consistency of the empirical distribution in this metric and derive explicit convergence rates, making precise the privacy-utility tradeoff: stronger privacy guarantees impose more restrictive choices of the released sample size, slowing down convergence to the "true" data-generating distribution.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.26021v1">Privacy Vulnerabilities of Attention Layers in Tabular Foundation Models and Protection of High-Risk Queries</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-24T16:42:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tânia Carvalho, Maxime Cordy</p>
    <p><b>Summary:</b> Tabular foundation models are commonly assumed to present limited privacy concerns as they are often pre-trained on large collections of synthetic data. However, these models leverage in-context learning, where sensitive records may be provided directly at inference time as labelled context examples. In this paper, we demonstrate that predictions generated via the attention mechanism leak sufficient information to enable effective Membership Inference Attacks (MIAs). To highlight this vulnerability, we propose AMIA (Attention-based Membership Inference Attack), a shadow-model-free attack that exploits the concentration of transformer attention patterns. Our results show that attention mechanisms reveal strong membership signals, which exceed classical confidence-based attacks, achieving an average gain of 7.7\%, specially in low false-positive regimes. To mitigate this risk, we introduce an inference-time defence inspired by $k$-anonymity principles. This approach reduces the uniqueness of context-key representations without introducing random noise or retraining the model. By targeting only high-risk queries identified through AMIA scores, the defence substantially reduces membership leakage of this attack by an average of 50\% and 25\% against confidence-based attacks, while preserving predictive utility with only 3.9\% performance degradation. Beyond showing that context examples are vulnerable, we further demonstrate that fine-tuning introduces an additional source of privacy risk. In particular, samples whose prediction confidence increases after fine-tuning become more susceptible to MIAs, indicating that fine-tuning can amplify memorisation and expose sensitive training information through confidence shifts.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.25788v1">Can Machine Learning Break Wi-Fi Privacy? A Study on MAC Address Randomization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-24T13:07:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marta Puig, Costas Michaelides, Lucia Pintor, Boris Bellalta, Francesc Wilhelmi</p>
    <p><b>Summary:</b> Medium Access Control (MAC) address randomization has been widely adopted during the IEEE 802.11 network discovery phase as a countermeasure against passive tracking. This paper exposes vulnerabilities in these privacy protocols by demonstrating that devices remain identifiable using Machine Learning (ML)-based fingerprinting. To study the potential tracking capabilities of a passive attacker, we evaluate different eavesdropping scenarios and configurations. To this end, we extract unencrypted hardware specifications from Probe Frames, which we combine with the Inter-Probe Frame Arrival Time (IFAT) and Simulated Received Signal Strength Indication (SRSSI) signals. A core contribution of this paper is the bitwise decomposition of the High Throughput (HT) capabilities information field, which improves device identification accuracy. We evaluate this de-randomization approach using three unsupervised clustering algorithms (K-Means, DBSCAN, and OPTICS) across a dataset of 22 devices from six manufacturers. Our results show that DBSCAN, when using decomposed HT capabilities information and three SRSSI measurements, achieves a global accuracy up to 89.6%. This suggests that the existing MAC randomization solutions are insufficient and underscores the need for enhancing privacy within Wi-Fi standardization.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.25627v1">TL++: Accuracy and Privacy Preserving Traversal Learning for Distributed Intelligent Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-06-24T09:34:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Erdenebileg Batbaatar, Young Yoon</p>
    <p><b>Summary:</b> Distributed intelligent systems increasingly need to train across data silos without centralizing raw data. Federated learning keeps data local but can suffer under heterogeneous partitions and requires repeated full-model exchange. Split learning reduces communication through cut-layer activations, but standard protocols generally do not recover centralized mini-batch gradient behavior and may expose activations and gradients in plaintext. We present TL++, a two-mode traversal-learning framework that constructs virtual batches across nodes to recover centralized mini-batch gradient behavior under explicit synchronization assumptions. Base mode exchanges cut-layer activations and gradients rather than full models. Secure mode secret-shares each cut-layer activation and gradient between an orchestrator and a non-colluding helper, preventing either server from observing plaintext cut-layer tensors. This protection is limited to a semi-honest two-server setting; labels and loss-related outputs remain visible to the orchestrator. In the lightweight secure path evaluated here, exactness requires a linear or affine server path, while nonlinear operations require nonlinear MPC or approximation. We formalize TL++, analyze communication and computation costs, and evaluate it against federated and split-learning baselines on CIFAR-10 and BioGPT/PubMedQA using full fine-tuning and LoRA. On CIFAR-10, TL++ base cut 1 and exact secure cut 3 achieve accuracies of 91.41% (SD 0.19) and 90.93% (SD 0.17), respectively, exceeding the strongest measured non-TL++ baseline by more than 12 percentage points. TL++ base cut 1 also reduces per-step communication by 13.1-fold relative to full-model synchronization. PubMedQA results similarly favor TL++. Overall, TL++ approaches centralized-training performance while reducing communication and providing activation-level secret sharing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.25533v1">Security and Privacy in Retrieval-Augmented Generation: Architectures, Threats, Defenses, and Future Directions for Building Trustworthy Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-06-24T08:08:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Balamurugan Palanisamy, G S S Chalapathi, Vikas Hassija, Rajkumar Buyya</p>
    <p><b>Summary:</b> Retrieval-Augmented Generation (RAG) has emerged as a dominant paradigm for enhancing large language models with external knowledge. By coupling retrieval mechanisms with generative models, RAG systems improve factual grounding and adaptability across domains. However, integrating retrieval pipelines introduces new security and privacy risks that extend beyond conventional language modeling threats. Sensitive information may be exposed through retrieval indices, query logs, context construction, or federated updates, while adversarial manipulation of knowledge bases can undermine trust in generated outputs. This survey provides a comprehensive examination of privacy and security challenges across RAG systems deployed in centralized, on-device (Micro-RAG), federated, and hybrid paradigms. We present a unified taxonomy of threat surfaces spanning the retrieval, context construction, and generation stages and systematically analyze attack classes, including membership inference, index inference, poisoning, gradient leakage, and collusion. We further review architectural, algorithmic, and cryptographic defenses, highlighting privacy-utility trade-offs and deployment considerations. Finally, we outline open research challenges toward building trustworthy, secure, and resilient RAG systems for real-world applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.25349v1">General Techniques for Reducing Key-Switching Overhead in Privacy-Preserving Two-Party Transformer Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-24T03:33:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenshao Yang, Zhenhua Liu, Dongdong Yao</p>
    <p><b>Summary:</b> In secure two-party Transformer inference, linear layers are typically evaluated using Fully Homomorphic Encryption (FHE) through plaintext-ciphertext or ciphertext-ciphertext matrix multiplications, where key switching primarily occurs and dominates computational overhead in both FHE-based and hybrid FHE-MPC systems. Existing optimizations rely heavily on packing-specific algorithms, limiting their general applicability.
  Targeting this overhead from a packing-independent perspective, we propose a preprocessing-assisted method for secure attention computation. By decomposing attention into precomputable operations and online interactions, this method reduces online inference-phase key switching without modifying existing packing strategies.
  However, the first method shifting key switching offline introduces additional storage requirements. To address this, we propose storage-communication trade-off techniques that replace large precomputed ciphertexts with modest online communication, enabling flexible deployment under varying resource constraints.
  While ciphertext-ciphertext matrix multiplication is offloaded to the preprocessing phase in hybrid schemes and the first layer of FHE-based schemes, these operations still persist in the offline stage and subsequent FHE layers. To further optimize it, we propose a fused key-switch technique targeting the multiplication-followed-by-rotation pattern, which frequently arises in existing RNS-CKKS matrix multiplication schemes. By combining relinearization and rotation into a single procedure, this technique reduces the associated computation costs.
  Analytical evaluations demonstrate that our proposed techniques significantly reduce online key-switch overhead and provide flexible trade-offs between storage and communication without requiring modifications to existing packing strategies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.25248v1">Sponsored Group Signature and its Application to Privacy-preserving Guest Access in Smart Environments</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-06-24T00:12:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sepideh Avizheh, Reihaneh Safavi-Naini, Shiwei Sun</p>
    <p><b>Summary:</b> Group signatures are privacy preserving signature schemes in which a group member can anonymously sign messages on behalf of the group, while providing accountability, by allowing the signature of a misbehaving group member be ``opened'' and the identity of the signer be revealed. In group signature members are admitted to the group by a (trusted) group manager. We motivate the need for a flexible mechanism in applications, such as privacy preserving access in smart environments, and propose a two-level member-join group signature that we call SPonsored Group Signature (SPGS) where group members of level 1 can ``sponsor'' new members, in level 2, to join the group. This relaxation of user join comes with additional accountability mechanisms: we require that the signature of a sponsored member can be opened to the identity of the sponsor (that is sponsor is responsible for the sponsored member), and while all signatures are anonymous, for the sponsored members, the signatures are linkable. This allows a sponsor to efficiently identify an undesirable sponsored member. We formalize SPGS scheme, define its security using a game-based approach, and give a generic construction of SPGS that uses a (dynamic) group signature scheme, a commitment scheme, and a knowledge-sound non-interactive zero knowledge proof of knowledge, and prove its security. We also give an instantiation of our construction. To show applicability of SPGS in practice, we consider the problem of providing guest access in a smart building, and introduce Anonymous Guest Access Token (AGAT) that allows a temporary guest to anonymously access (a subset of) the building resources. We show how SPGS can be used (together with an IND-CPA secure public key encryption scheme) to give a direct construction for AGAT, and show the efficiency of our guest access protocol when it is instantiated with existing schemes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.25216v1">Homomorphic Encryptions for Privacy Preserving Vision</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-06-23T22:28:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Preey Shah, Rohan Virani, Sanjari Srivastava</p>
    <p><b>Summary:</b> Legal requirements might prevent organizations from sharing sensitive data like medical or financial details of consumers which prevents them from leveraging cloud based ML-as-a-service solutions provided by third party providers, which are quickly gaining popularity these days. In this project, we aim to perform inference tasks in Computer Vision in a privacy-preserving manner, i.e, by only looking at encrypted data. Recent advances in fully homomorphic encryption make this possible. A fully homomorphic encryption allows an arbitrary sequence of additive and multiplicative operations to be performed on encrypted data directly. Applying homomorphic encryptions to CNNs requires modifying the conventional CNN layers, so that they adhere to the encryption scheme. Our aim was to explore the best methods to create CNNs which can classify encrypted images directly. We used Microsoft SEAL for performing homomorphic encryption. The performance of these "encryption based CNNs" should be comparable with baseline accuracies of the same CNNs trained on unencrypted data, and the aim was to achieve as low of a hit on inference-time performance as possible. We successfully obtained minimal drop in classification accuracy for various datasets. We used MNIST as our baseline, which is popularly used in related research work and then explored more complex datasets like Kuzushiji MNIST, Fashion-MNIST and CIFAR-10 as a part of our contribution. Additionally, we also added support for more complex operations on top of TenSEAL, like processing colored images (multi-channel input), applying multiple convolutional layers and performing average pooling.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.24819v1">HelpBench: Assessing the Ability of LLMs to Provide Privacy, Safety, and Security Advice</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-23T17:05:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sarah Meiklejohn, Sunny Consolvo, Patrick Gage Kelley, Tara Matthews, Sai Teja Peddinti, Renee Shelby, Lenin Simicich, Kurt Thomas</p>
    <p><b>Summary:</b> This paper introduces HelpBench, a benchmark for assessing whether LLMs are capable of providing accurate help in response to questions about digital privacy, safety, and security. We curated 450 questions representing authentic user situations and developed rubrics for each question to evaluate the factual accuracy and tone of a response. Example questions touch on how to regain access to lost or suspended accounts, how to balance the trade-offs of hardware security keys versus other forms of two-factor authentication, whether a suspicious email is likely a scam, or whether an abuser might be able to track an individual based on their device peripherals. We then developed and applied an auto-rater to evaluate responses from 18 state-of-the-art LLMs. Our results indicate that while models provide high-quality advice (with scores of 82% on average), one in ten responses from models scores less than 65%, reflecting inaccurate and even harmful advice. Addressing these failures is critical for models to serve as trustworthy sources of assistance for digital privacy, safety, and security needs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.24623v1">Privacy-Preserving RAG via Multi-Agent Semantic Rewriting: Achieving Confidentiality Without Compromising Contextual Fidelity</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-23T14:21:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuanhe Zhao, Tianyu Zhang, Huafei Xing, Derek F. Wong, Jianbin Li, Tao Fang</p>
    <p><b>Summary:</b> Retrieval-Augmented Generation enhances large language models by incorporating external knowledge, but deploying it in sensitive scenarios risks privacy leakage via malicious prompts. To address this, we propose a multi-agent framework that sanitizes retrieved content through semantic rewriting. By employing three specialized agents for privacy extraction, semantic analysis, and reconstruction, our approach collaboratively removes sensitive identifiers while preserving the semantic core. We evaluate the framework on the ChatDoctor and Wiki-PII datasets across six large language models. Experimental results demonstrate a significant reduction in privacy leakage under targeted attacks. For instance, we reduced targeted information exposure in LLaMA-3-8B from 144 instances in the baseline to just 1. Furthermore, we maintain strong contextual fidelity with a BLEU-1 score of 0.122, outperforming the existing SAGE method's 0.117. Finally, the framework operates as an asynchronous preprocessing module, introducing no additional latency to online inference, as all rewriting is executed as a one-time offline preprocessing step. To promote reproducibility, the source code of this work is publicly available at https://github.com/foursoils/Privacy-Preserving-RAG.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.24408v1">Natural Identifiers for Privacy and Data Audits in Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-06-23T10:45:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lorenzo Rossi, Bartłomiej Marek, Franziska Boenisch, Adam Dziedzic</p>
    <p><b>Summary:</b> Assessing the privacy of large language models (LLMs) presents significant challenges. In particular, most existing methods for auditing differential privacy require the insertion of specially crafted canary data during training, making them impractical for auditing already-trained models without costly retraining. Additionally, dataset inference, which audits whether a suspect dataset was used to train a model, is infeasible without access to a private non-member held-out dataset. Yet, such held-out datasets are often unavailable or difficult to construct for real-world cases since they have to be from the same distribution (IID) as the suspect data. These limitations severely hinder the ability to conduct scalable, post-hoc audits. To enable such audits, this work introduces natural identifiers (NIDs) as a novel solution to the above-mentioned challenges. NIDs are structured random strings, such as cryptographic hashes and shortened URLs, naturally occurring in common LLM training datasets. Their format enables the generation of unlimited additional random strings from the same distribution, which can act as alternative canaries for audits and as same-distribution held-out data for dataset inference. Our evaluation highlights that indeed, using NIDs, we can facilitate post-hoc differential privacy auditing without any retraining and enable dataset inference for any suspect dataset containing NIDs without the need for a private non-member held-out dataset.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.24379v1">ComputeFHE: A Privacy-Preserving General-Purpose Computation Library</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-06-23T10:11:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Faris Serdar Tasel, Efe Ciftci</p>
    <p><b>Summary:</b> Fully Homomorphic Encryption (FHE) enables computations to be performed directly on encrypted data while preserving data confidentiality. However, its practical applications remain limited by high computational costs and development complexity. This paper presents ComputeFHE, an open-source C++ library that facilitates the development of privacy-preserving applications based on the TFHE cryptosystem. The library provides encrypted integer and fixed-point data types together with arithmetic, logical, comparison, conditional, and oblivious array-access operations which allow developers to implement algorithms using a familiar imperative programming paradigm. ComputeFHE supports both conventional TFHE arithmetic based on standard two-input logic gates and an optimized Arithmetic Logic Unit (ALU) architecture utilizing FHE-friendly logic primitives. Experimental results demonstrate significant reductions in the number of required bootstrapping operations, achieving performance improvements of up to 3.9x for selected operations. In addition, the library includes a simulation mode that enables testing, debugging, and complexity analysis without performing actual cryptographic computations while providing circuit complexity and bootstrapping costs. Built on top of OpenFHE, ComputeFHE offers a practical and accessible framework for developing and evaluating privacy-preserving algorithms and applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.24941v1">EmotionAI: A Privacy-Preserving Computational Intelligence Pipeline for Speech-Emotion-Grounded Conversational Analysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-22T20:45:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wai Laam Mak, Isibor Kennedy Ihianle, Pedro Machado</p>
    <p><b>Summary:</b> Reviewing recorded interviews for affective cues such as composure, hesitation and agitation is slow and subjective, and cloud services that could automate it require sensitive audio to leave the device. EmotionAI is a fully local Computational Intelligence (CI) pipeline that couples Speech Emotion Recognition (SER) with generative reasoning. Speaker diarisation, Whisper Automatic Speech Recognition (ASR) and a wav2vec2 emotion classifier produce per-segment affective evidence, which is then passed to an adversarial three-model local Large Language Model (LLM) panel for timestamp-grounded and citation-constrained question answering. Zero-shot evaluation on the RAVDESS four-class English subset (n = 672) exposes cross-corpus fragility rather than classifier superiority: the deployed classifier scores 48.8% accuracy, above random (24.9%) and majority (28.6%) baselines but below an in-domain MFCC + logistic-regression comparator (71.0%). The complete pipeline runs in a mean 157 s on CPU (real-time factor approximately 1.33) with zero external calls. The contribution is not state-of-the-art SER but an auditable, privacy-preserving integration of imperfect affective evidence into grounded conversational analysis, together with an honest empirical account of where cross-corpus transfer and human-centred validation still fall short.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.24938v1">Privacy-preserving federated tensor decomposition of single-cell immune data: recovering multicellular programs across institutions</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-22T18:15:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Axel Faes, Stephanie M. van den Berg, Maryam Amir Haeri</p>
    <p><b>Summary:</b> Tensor decomposition of donor $\times$ cell-type $\times$ gene single-cell data recovers
  \emph{multicellular programs}: coordinated axes of inter-individual transcriptional variation that
  span cell types and stratify disease. Yet immune single-cell atlases are increasingly
  multi-institution, multi-ancestry, and governed, so patient cells often cannot be pooled. We present
  a federated estimator: each site computes a local program subspace, and a coordinator merges these by
  stacked SVD under federated global-mean centering, provably equivalent (up to truncation) to the
  centralised decomposition. This centering makes the merge robust to site-label confounding (program
  AUC $0.957$ vs.\ $0.861$ for naive per-site centering). Only program subspaces leave a site, and
  aggregation is compatible with secure aggregation. On a 261-donor systemic lupus erythematosus atlas
  it recovers the canonical interferon program (ISG enrichment AUC $0.998$; case--control separation
  $0.958$; bootstrap $Δ\text{AUC}=-0.000$, 95\% CI $[-0.004,+0.012]$ vs.\ centralised), across
  institution-scale and multi-ancestry partitions, and across three \emph{real} COVID-19 sites
  (subspace correlation $0.989$). It recovers the program when \emph{no site observes all cell types}
  (correlation $1.000$, exact by construction), which fixed-feature federated PCA cannot. On an
  interstitial-lung-disease atlas the recovered program predicts disease better than the best single
  cell type (AUC $0.96$ vs.\ $0.91$; gap 95\% CI excludes zero) and the advantage survives federation;
  a liver cohort is consistent ($p=0.005$). Membership-inference shows secure aggregation cuts attack
  AUC from $0.91$ to $0.61$. The method enables cross-institution, cross-ancestry recovery of
  multicellular immune programs without sharing cells.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.23796v1">A no-go theorem for privacy in distributed sensing using Gaussian states</a></h3>
  
  <p><b>Published on:</b> 2026-06-22T18:00:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jason L. Pereira, Damian Markham</p>
    <p><b>Summary:</b> In the discrete variable setting, entangled resource states allow a set of parties to learn a global function of a set of spatially separated systems, whilst keeping the local parameters of those systems completely private. In the continuous variable setting, distributed sensing has been carried out using Gaussian resource states, but without the same guarantees about privacy. Here, we show that perfect privacy is impossible to achieve for any distributed sensing protocol that uses Gaussian states as a resource. We also introduce a measure of relative privacy, bounding the degree to which any Gaussian distributed sensing protocol can keep local parameters hidden.</p>
  </details>
</div>


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
  <h3><a href="http://arxiv.org/abs/2606.20344v2">Quantum ring all-reduce: communication and privacy advantages for distributed learning</a></h3>
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
  <h3><a href="http://arxiv.org/abs/2606.16943v2">Di5Guise: 5G Privacy with vSIM</a></h3>
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
  <h3><a href="http://arxiv.org/abs/2606.16488v2">An Energy-Driven Framework for Privacy-Aware Synthetic Data Generation</a></h3>
  
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

