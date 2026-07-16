
<h2>2026-07</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.13754v1">PriEval-Protect: A Unified Framework for Privacy Evaluation and Protection in Healthcare Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-15T12:12:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ilef Chebil, Asma El Hadj, Souheib Yousfi, Aroua Hedhili, Layth Sliman</p>
    <p><b>Summary:</b> Safeguarding patient privacy while enabling meaningful healthcare data use remains critical under GDPR and HIPAA. Existing compliance methods are manual, error-prone, and separate policy audits from data-level assessments. This paper presents PriEval-Protect, a two-phase framework for unified privacy risk evaluation and mitigation. The evaluation phase combines regulatory compliance scoring using a fine-tuned legal LLM with RAG, and technical analysis via encryption type, data architecture, and metrics including similarity, uncertainty, adversary success, and information gain/loss. A composite risk score uses weighted aggregation via Analytic Hierarchy Process. The protection phase recommends countermeasures including federated learning and differential privacy based on assessed risk. Results on hospital documents and datasets demonstrate regulation-aligned, explainable assessments, bridging legal conformance and data-level risk analysis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.13541v1">When T2I Synthetic Data Backfires: Amplified Privacy Risks in Real-Synthetic Mix Training</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-07-15T07:44:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Na Li, Boyu Kuang, Hongsheng Hu, Liquan Chen, Hyoungshick Kim, Yansong Gao, Anmin Fu</p>
    <p><b>Summary:</b> To overcome data scarcity and privacy constraints in data collection, it has become standard practice across academia and industry to augment real training data with text-to-image (T2I)-generated synthetic data, a paradigm we term Real-Synthetic Mix-Training (RSMT). While substituting synthetic data for sensitive real samples is widely regarded as a means to mitigate privacy exposure of the substituted data, the risk to the remaining real samples that actively participate in training has remained largely unexamined.
  This work reveals, for the first time, that RSMT can substantially amplify privacy leakage of these real training samples. We establish a theoretical framework, RSMT Memorization Amplification, proving that incorporating synthetic data displaces real samples toward peripheral regions of the mixed feature space, in turn forcing the model to memorize them more aggressively. Guided by this foundation, we propose RSMixLeak to systematically assess this risk through membership inference attacks (MIAs). RSMixLeak comprises two variants depending on the adversary's capability. The non-adversarial variant audits a benign RSMT pipeline with an honest T2I provider, establishing a lower bound on the leakage induced by the intrinsic gap between real and T2I-generated data. The adversarial variant considers an adversary who controls the T2I model or contributes crafted data to the T2I provider, and deliberately enlarges this distributional gap on a target class via either high-level semantic attribute binding or imperceptible pixel-level coating, further amplifying leakage on real training data while improving downstream model utility. Motivated by these findings, we further propose a lightweight leakage propensity indicator computable from real data alone that reliably identifies high-risk datasets unsuitable for entering RSMT, as a self-assessable mitigation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.13441v1">ReBound: Reuse-Aware Privacy For Interactive Decision Support</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2026-07-15T04:57:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nada Lahjouji, Shufan Zhang, Xi He, Sharad Mehrotra</p>
    <p><b>Summary:</b> Differentially private decision support frameworks answer complex aggregate threshold queries with formal bounds on false negative and false positive rates, but treat each query independently with no memory of past results. In practice, analysts work interactively, issuing sequences of related queries that refine bounds, adjust thresholds, or derive new functions from previous ones. We propose ReBound, a framework that reuses cached results from previous queries to answer new queries at reduced or zero additional privacy cost while maintaining formal utility guarantees. ReBound introduces a reuse framework for multiple refinement types, a cache graph structure for efficient lookup of reusable results, and a negotiation mechanism for when requested bounds cannot be met within budget.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.13328v1">Privacy Preserving Recommender Systems Balancing Personalization with Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-07-14T23:21:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ranjeet K Jha, Venkata Suresh Gummadilli</p>
    <p><b>Summary:</b> Personalized recommendation systems are central to modern e-commerce and retail platforms, but they typically rely on centralized storage of detailed user interaction data, creating significant privacy and regulatory challenges. With increasing requirements from regulations such as GDPR, CCPA, and CPRA, organizations must develop recommendation systems that preserve user privacy without substantially degrading recommendation quality.
  This work presents and evaluates a privacy-preserving recommendation framework that combines federated learning, differential privacy, cohort-level modeling, and privacy-aware intelligent agents. The framework keeps raw user data decentralized while introducing mathematically bounded noise to model updates. Experiments were conducted on synthetic retail datasets that emulate customer clickstream and purchase behavior. Recommendation quality was evaluated using Click-Through Rate (CTR), Precision@K, Recall@K, and Normalized Discounted Cumulative Gain (NDCG@K) across multiple differential privacy budgets.
  We evaluate matrix factorization, neural collaborative filtering, and GRU4Rec under varying privacy constraints and analyze the trade-off between privacy and utility. An interactive Streamlit dashboard was developed to visualize recommendation performance, ranking stability, privacy-utility trade-offs, and fairness metrics. Results show that the proposed framework maintains competitive recommendation quality at moderate privacy budgets (approximately $ε\approx 5$), demonstrating that strong privacy guarantees can be achieved with limited impact on recommendation effectiveness.
  This work provides a practical framework for deploying privacy-preserving recommendation systems that balance personalization, regulatory compliance, and business objectives, offering a scalable approach for next-generation AI-driven retail platforms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.13015v1">Privacy Attacks on Stable Marriage</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2026-07-14T17:55:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stephan A. Fahrenkrog-Petersen, Aleksander Figiel, Darya Melnyk, Tijana Milentijević, Stefan Schmid</p>
    <p><b>Summary:</b> The stable marriage problem appears in many privacy-sensitive domains, for example in the National Resident Matching Program in the US. In such applications, preserving the privacy of users' preference lists is essential to prevent strategic manipulation, discourage misreporting, and comply with data protection regulations.
  In this work, we investigate privacy attacks on stable marriage algorithms. Assuming that the attacker (e.g., the hospitals) can repeatedly interact with the stable marriage algorithm, we demonstrate how such interactions can reveal private preferences of the non-malicious side (e.g., the residents). We show that the widely applied Gale-Shapley Matching Algorithm, where the proposers' side is malicious, is vulnerable to privacy attacks and all honest agents' preferences can be revealed. We further investigate which preference distributions of the honest, non-malicious side are susceptible to privacy attacks and show that the Gale-Shapley Matching Algorithm where the honest side proposes can preserve privacy in non-susceptible preference distributions. We extend our results to the decentralized setting and show that the attacker's side can infer all preference orderings. In an experimental evaluation, we test privacy attacks on synthetic and real-world data and show that real-world data is indeed susceptible to privacy attacks. This work underlines a need for new privacy-preserving stable marriage algorithms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.13122v1">Designing a GDPR-Compliant Security Architecture for Remote Elderly Care Systems: A Privacy-by-Design Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-07-14T17:14:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Md. Rahid Parvez, Mikael Soini</p>
    <p><b>Summary:</b> IoMT-based remote elderly care systems generate continuous streams of sensitive health data, yet existing security architectures have not simultaneously addressed three interdependent challenges: GDPR-compliant edge-layer pseudonymisation, elderly-specific zero-interaction usability as a binding architectural constraint, and integrated STRIDE-based threat validation within a single unified design. This paper presents the Secure Edge Gateway (SEG) framework - a software-simulation-validated integrated IoMT security architecture for elderly care designed to resolve all three dimensions of this tripartite gap simultaneously. An ESP32-WROOM-32 residential gateway enforces MAC address whitelisting, HMAC-SHA256 cryptographic pseudonymisation before any network transmission, AES-128-CBC payload encryption, and TLS 1.3 transport security, in compliance with GDPR Articles 25 and 32. The framework is validated through software-based simulation, full STRIDE threat modelling across all six categories, attack tree analysis, GDPR compliance mapping across nine regulatory obligations, and a Data Protection Impact Assessment (DPIA) under Article 35. Published benchmarks confirm MQTT consumes 6-8% less energy than HTTP in comparable IoT deployments, and edge processing achieves sub-50 ms response latency versus 200-700 ms for cloud-only systems. The results demonstrate that GDPR compliance and operational efficiency are complementary - not competing - objectives in resource-constrained IoMT deployments for elderly care.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.12354v1">Reducing information dependency does not cause training data privacy. Adversarially non-robust features do</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-07-14T05:06:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rasmus Torp, Shailen K. Smith, Adam Breuer</p>
    <p><b>Summary:</b> In this paper, we challenge the prevailing view that information dependency (including rote memorization) drives training data exposure to image reconstruction attacks. We show that extensive exposure can persist without rote memorization and is instead caused by a tunable connection to adversarial robustness. We begin by presenting three surprising results: (1) recent defenses that inhibit reconstruction by Model Inversion Attacks (MIAs), which evaluate leakage under an idealized attacker, do not reduce standard measures of information dependency (HSIC); (2) models that maximally memorize their training datasets remain robust to MIA reconstruction; and (3) models trained without seeing 97% of the training pixels, where recent information-theoretic bounds give arbitrarily strong privacy guarantees under standard assumptions, can still be devastatingly reconstructed by MIA.
  To explain these findings, we provide causal evidence that privacy under MIA arises from what the adversarial examples literature calls ``non-robust'' features (generalizable but imperceptible and unstable features). We further show that recent MIA defenses obtain their privacy improvements by unintentionally shifting models toward such features. To establish this causal relationship, we introduce Anti Adversarial Training (AT-AT), a training regime that intentionally learns non-robust features to obtain both superior reconstruction defense and higher accuracy than state-of-the-art defenses. Our results revise the prevailing understanding of training data exposure and reveal a new privacy-robustness tradeoff.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.12288v1">$\mathrm{P}^{3}$CDA: Privacy-Preserving and Provably Secure Cross Domain Authentication Scheme for Internet of Drones</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-14T02:48:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chengqi Hou, Beibei Li, Ziqing Zhu, Yang You, Licheng Wang</p>
    <p><b>Summary:</b> With the rapid expansion of the Internet of Drones (IoD) and the increasing mobility of drones, cross-domain interactions among geographically distributed domains have become inevitable. Cross-domain authentication is therefore a fundamental security requirement for IoD. However, existing authentication schemes often struggle to simultaneously achieve strong security, high efficiency, and identity privacy, making them unsuitable for the stringent requirements of highly dynamic and resource-constrained IoD environments. To address this challenge, we propose $\mathrm{P}^{3}$CDA, a privacy-preserving and provably secure cross-domain authentication scheme. First, we design an efficient pseudonym management mechanism that supports adaptive pseudonym generation as well as batch registration, verification, and revocation. Second, we propose a structurally enhanced Merkle Hash Tree (MHT) that supports batch pseudonym updates, thereby reducing the pseudonym storage overhead of drones. Building on these components, we develop a cryptographic accumulator-based cross-domain authentication protocol that enables anonymous authentication with authorized pseudonyms while preserving the traceability and efficient revocation of malicious drones. We rigorously analyze the security of $\mathrm{P}^{3}$CDA and formally prove its security under the Canetti--Krawczyk (CK) adversary model. Extensive experiments demonstrate that $\mathrm{P}^{3}$CDA achieves lower computational, communication, and storage overhead than state-of-the-art schemes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.13093v1">Efficient and Privacy Aware Edge Cloud Collaborative Inference for Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-07-14T01:17:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yi Li, Chen Li, Jiexiong Liu</p>
    <p><b>Summary:</b> On-device LLM inference faces a trilemma of response latency, limited hardware resources and user privacy. Full cloud inference delivers strong computing power but exposes user prompts and dialogue data, while standalone on-device inference is unfeasible for most consumer and embedded edge devices. This paper presents a privacy-centric edge-cloud collaborative LLM inference framework built on endpoint-authenticated KV cache. Local endpoints handle input preprocessing, embedding computation, adaptive feature optimization, KV cache authentication, speculative decoding and low-dimensional model head calculation, while the cloud conducts authenticated decoder inference, KV cache management, token verification and high-dimensional vocabulary projection. Endpoints fuse partial outputs, apply language-adaptive masking and sample target tokens. All transmitted data and truncated logits are quantized and AES-GCM encrypted for privacy, with core lightweight modules, draft parameters and cache access policies kept local to avoid leakage. The framework supports heterogeneous devices including CPU-only, GPU-equipped and embedded devices via optimized streaming, batching and quantized ONNX deployment. Evaluations demonstrate that the framework reduces per-token latency by up to 46.1\% and downlink payloads by up to 67.4\% over baseline split inference, retaining comparable performance to full cloud inference.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.12246v1">Proximity Features: Privacy-Compliant Cold-Start Personalization at Airbnb</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-07-14T01:17:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wei Jiang, Bin Xu, Hui Gao, Bharathi Thangamani, Weiwei Guo, Sundar Srinivasavaradhan, Tracy Yu, Huiji Gao, Michael Kinoti</p>
    <p><b>Summary:</b> Personalization in two-sided marketplaces relies heavily on user-level features, yet for platforms with infrequent, high-consideration purchases, a large fraction of users lack sufficient history for effective recommendation, spanning both paid and organic channels. At Airbnb, a substantial share of search requests comes from logged-out or first-time users, with this challenge especially pronounced on paid-channel landing pages, leaving traditional user-level features unavailable for a large fraction of traffic. Privacy regulations and increasing restrictions on third-party cookies further limit identifier-based tracking for non-essential use cases. This paper introduces Proximity Features, a privacy-compliant feature system that groups users by geographic proximity using geo-IP data and an adaptive clustering algorithm, producing aggregated user-level signals for groups of approximately 1,000 nearby users without requiring a persistent individual identifier at inference time. Privacy is preserved by design: the pipeline operates on consented, aggregated data only within consent-gated privacy controls.
  The system is deployed in production at Airbnb, serving multiple surfaces including marketing landing pages and destination recommendation, with engagement emails integration under way. Online A/B experiments demonstrate statistically significant lifts in bookings, with the largest gains observed among users with absent or stale history.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.13088v1">Securing LLMs in the Wild: Privacy and Security Challenges at the Edge</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-07-13T16:45:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ren-Yi Huang, Mingchen Li, Dumindu Samaraweera, Morris Chang</p>
    <p><b>Summary:</b> Large Language Models (LLMs) are rapidly moving from research settings into the wild, deployed on enterprise infrastructure, personal devices, and edge platforms. While cloud deployments offer scalable compute, concerns over data sovereignty, compliance, latency, and third-party dependence are driving organizations toward edge and on-premise LLMs. This shift introduces new security and privacy challenges: limited compute and memory force aggressive optimizations, including quantization, pruning, model partitioning, and parameter-efficient adaptation, each of which can introduce vulnerabilities and reshape the threat landscape. We describe this tension as the Security-Efficiency Paradox, mechanisms that improve efficiency may weaken robustness, expose new attack surfaces, or increase privacy risks. We examine how compression can degrade safety alignment, how partitioned inference enables reconstruction attacks, and how continuous local adaptation may cause privacy leakage and model drift. To analyze these risks, we introduce a deployment-centric taxonomy organized around three architectural constraints: the Memory Wall, the Quadratic Wall, and the Compute Wall. We derive a unified constraint model that quantifies when unsafe optimizations become unavoidable, linking each wall to specific attack surfaces. Building on this model, we propose the Secure Operational Efficiency Score (SOES), a holistic metric balancing task accuracy, jailbreak resistance, and privacy against energy, memory, and latency, enabling practitioners to configure edge LLMs under real-world hardware limits. We further present a practical decision procedure and targeted mitigations for each optimization-induced vulnerability. Together, these contributions provide a co-designed framework for jointly evaluating security, privacy, and efficiency, laying a foundation for securing edge-native intelligent systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.11600v1">Privacy-Aware Collaborative and Distributed Bayesian Optimization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2026-07-13T14:25:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aditya Rane, Sathwik Yamana, Paritosh Ramanan, Srikanthan Ramesh, Akash Deep</p>
    <p><b>Summary:</b> We propose a collaborative meta-learning framework for distributed Bayesian optimization matching centralized performance without raw-data exchange. We show gradient sharing leaks client observations, with leakage worsening as the search converges and queries concentrate near the optimum. We evaluate a differentially private defense and characterize its privacy-utility trade-off.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.11302v1">Information geometric quantification of effective privacy in quantum metrology</a></h3>
  
  <p><b>Published on:</b> 2026-07-13T09:18:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Luca Bianchi, Shimpei Yamaguchi, Wojciech Roga, Davide Bacco, Masahiro Takeoka</p>
    <p><b>Summary:</b> Privacy of a quantum metrological protocol concerns the extent to which single parameters can be kept inaccessible to an observer or to other users of the network. In this work, an information geometric framework is developed to quantify privacy and accessibility of functions of parameters effectively, that is, up to a finite accuracy in state discrimination. Both quantities are defined by measuring volumes in the parameter space induced by the underlying quantum states. This construction subsumes previous definitions of privacy based on the degeneracy of quantum Fisher information, naturally encompassing imperfect implementations. Using extended-GHZ states as a representative example of a quantum network scenario, privacy and accessibility are characterized by quantum correlations and accuracy, providing scaling laws depending on imperfect measurements and entanglement.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.10709v1">PromptGraph: Graph-Guided Prompt Sanitization for Balancing Privacy and Utility in LLM Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-07-12T11:04:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chen Gu, Hui Wan, Donghui Hu, Hui Wang, Zhuoer Gu</p>
    <p><b>Summary:</b> Large Language Model (LLM) services introduce a fundamental privacy challenge. Sensitive information may be inferred not only from explicit identifiers, such as names or phone numbers, but also from contextual associations among otherwise innocuous spans. Existing sanitizers typically assign privacy or utility signals to individual spans without explicitly modeling pairwise relationships among them. In this paper, we propose PromptGraph, a graph-guided prompt-sanitization approach for privacy-preserving LLM inference. PromptGraph estimates privacy leakage at the span level and utility-relevant contextual dependencies between pairs of spans. It represents each prompt as an attributed graph, in which nodes carry span-level privacy scores and edges encode contextual dependencies needed to preserve utility. The sanitization objective selects a protected span set that maximizes privacy gain while penalizing the loss of contextual dependencies. This formulation explicitly balances privacy and utility when contextual evidence is hidden. Protected spans are sanitized locally, and returned placeholders are restored only after passing local consistency checks. We conduct extensive experiments showing that PromptGraph achieves a more favorable balance between privacy and utility than prompt-privacy baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.10467v2">Toward Production-Ready Federated Learning in Healthcare: Privacy, Orchestration, and Governance in MLOps</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-07-11T20:14:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sakshi Gorkhali, Jonesh Shrestha</p>
    <p><b>Summary:</b> Healthcare organizations often cannot freely centralize patient data because medical records are sensitive, regulated, and institutionally controlled. Federated learning offers a practical alternative by allowing hospitals and clinics to train a shared model while keeping raw data local. However, federated learning is not automatically production-ready or private by default. Model updates can still leak information, and decentralized training introduces operational challenges in deployment, monitoring, rollback, debugging, and governance. This paper examines how MLOps practices and the emerging idea of Federated Learning Operations (FLOps) can make federated healthcare machine learning systems scalable, reliable, and trustworthy. It answers three research questions: how containerization and orchestration support federated deployment, how privacy-preserving mechanisms affect trade-offs among privacy, utility, scalability, and operational complexity, and which post-deployment practices are most important for long-term governance. The central argument is that federated healthcare ML requires more than privacy-preserving algorithms. It needs an integrated MLOps architecture that combines reproducible deployment, secure orchestration, model versioning, audit logging, drift monitoring, heterogeneity management, and clear governance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.10329v1">Imperceptible and Reversible Adversarial Examples against Vision-Language Models for Privacy Protection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-07-11T14:13:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qi Lu, Ziqi Zhou, Yufei Song, Zijing Li, Lulu Xue, Minghui Li, Shengshan Hu, Leo Yu Zhang</p>
    <p><b>Summary:</b> Vision Language Models (VLMs) offer powerful multimodal ability but also expose users to text-based privacy attacks where adversaries crawl online photos and query VLMs to extract sensitive attributes. Existing reversible adversarial example (RAE) methods protect images in purely visual tasks but fail in multimodal settings, and current adversarial examples on VLMs rely on high frequency noise that severely degrades visual quality. We propose CloakDiff, the first framework for reversible, high fidelity privacy protection against text-based query attacks in VLMs. CloakDiff produces imperceptible adversarial examples by combining diffusion based adversarial editing with an invertible network that embeds the original image for lossless recovery. It perturbs both pixel space embeddings and manipulates latent cross attention maps to ensure strong cross-model and cross-prompt transferability while preserving global visual structure. To further enhance fidelity, we design EDM Heuristic Sampling, a principled diffusion schedule for adversarial guidance. Experiments on multiple datasets and VLMs demonstrate that CloakDiff delivers multimodal privacy preservation with high visual quality and reversibility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.09391v1">Federated Learning Architecture: Data Privacy and System Security Approaches</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-10T13:15:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Cagdas Karatas, Hibanur Karadogan, Ahmet Yasin Ertug, Busra Buyuktanir, Kazim Yildiz, Gozde Karatas Baydogmus</p>
    <p><b>Summary:</b> This study explores the integration of homomorphic encryption and differential privacy techniques to enhance data privacy and security in Federated Learning (FL) systems. FL allows data to remain on local devices, eliminating the need for centralized data collection; however, sensitive information may still be leaked during model updates. To address this issue, homomorphic encryption enables computations on encrypted data, while differential privacy prevents the extraction of individual information through statistical techniques applied to model outputs. The proposed architecture was tested on the Framingham, Pima Indians Diabetes, and Bank Marketing datasets, revealing that enhanced privacy can be achieved without significantly compromising model accuracy. Furthermore, the impact of data heterogeneity among clients on model performance was analyzed, and it was concluded that strategies such as the careful selection of differential privacy parameters and training settings, along with the use of larger datasets, can improve the efficiency of FL. The findings demonstrate that privacy-preserving and high-performance artificial intelligence systems can be securely applied in sensitive domains such as healthcare and finance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.09022v1">Privacy Detective: A Narrative Game that Cultivates Student Developers' Privacy Awareness by Harnessing Legal Documents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-07-10T01:07:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shao-Yu Chu, Jennifer Forsyth, Xu Wang, Haojian Jin</p>
    <p><b>Summary:</b> Developers' choices about what data a system collects, how it is used and shared, and what defaults govern user choices directly shape users' privacy experiences. Yet, developers often make problematic privacy-related design decisions without realizing the potential consequences. We introduce Privacy Detective, a narrative investigation game that leverages real-world legal documents to train developers' privacy awareness. In the game, players search for privacy violation evidence derived from legal documents and organize this evidence into privacy violation reports using curated templates. We evaluated Privacy Detective in a between-subjects study with student developers, comparing it against a baseline in which participants read raw FTC legal documents. Participants in the game condition identified more true violations than the baseline group, flagged fewer non-issues, and provided more complete justifications for the violations they reported.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.08809v1">Privacy-Preserving Intent Fulfilment and Assurance for 6G RAN</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-07-09T17:13:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joss Armstrong</p>
    <p><b>Summary:</b> Intent-based network management is the emerging paradigm for 6G service lifecycle automation, with the 3GPP intent management framework (TS~28.312) defining creation, translation, fulfilment, and assurance stages. Existing fulfilment and assurance approaches require deep packet inspection, per-flow state tracking, or access to vendor-internal node telemetry to verify that provisioned resources satisfy expressed intents. These requirements conflict with regulatory constraints (GDPR, ePrivacy Directive) in multi-tenant networks and with vendor opacity in multi-vendor O-RAN deployments.
  We present an architecture for privacy-preserving intent fulfilment and assurance in which a coordinator provisions resources from declared intent categories without traffic inspection, and verifies fulfilment using only aggregate standardised PM counters at the O1 interface. A data-processing inequality argument shows that the resource allocation reveals at most $\log_2 K$ bits about traffic content, where $K$ is the number of intent categories. We define two architectural privacy properties, intent-traffic unlinkability and node-opaque verification, and show that both hold by construction. Node-opacity does not sacrifice detection power: the aggregate verifier weakly dominates the per-agent verifier under a homogeneity condition.
  We map the architecture to the 3GPP intent lifecycle and the O-RAN Non-RT RIC, identifying the concrete interfaces, data objects, and deployment points at which the mechanism operates. On production PM counter data from four operator networks, increasing intent-category granularity sharpens provisioning but weakens assurance, consistent with the theoretical prediction that the privacy ceiling is a structural side effect of the detection constraint rather than a separate design parameter.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.08659v1">EdgeRefine: Privacy-Utility Balance for Graphs via Jaccard Sampling under Edge Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-07-09T16:28:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenxiu Ding, Muzhi Liu, Zheng Yan, Mingjun Wang, Yifan Zhao, Qiao Liu</p>
    <p><b>Summary:</b> Graph Neural Networks (GNNs) have shown considerable success in learning from graph-structured data, but their use in privacy-sensitive areas remains difficult because graph structure can leak sensitive link information. To satisfy edge-level differential privacy, a common approach is to inject noise into all elements of the graph's adjacency matrix, thereby obfuscating the existence of any single edge. However, stronger privacy requires more noise, and excessive noise reduces utility, making the privacy-utility balance a major barrier to practical privacy-preserving graph learning.
  To address this issue, we propose EdgeRefine, a local differential privacy framework that improves this trade-off through adaptive edge refinement. EdgeRefine first estimates edge-existence probabilities using Jaccard similarity and ranks edges for noisy edge removal. To ensure the sparsity and reliability of the final graph, it uses the privacy budget $ε$ to determine the ratio of true to false edges, samples them separately based on this probability ranking, and controls the total number of edges with a separate sampling rate $k$. Extensive experiments show that EdgeRefine achieves accuracy comparable to the noise-free baseline and substantially outperforms other privacy-preserving methods across datasets and GNN architectures. Under privacy budget $ε= 2.5$, EdgeRefine improves node classification accuracy over state-of-the-art baselines by 17.8\% on ACM under GAT and 19.7\% on Cora under GCN. In graph classification, it achieves an average accuracy degradation of around 5\% compared to the noise-free baseline. Under graph reconstruction attacks, EdgeRefine maintains relative absolute error levels above 1 across all privacy budgets, averaging 1.962 on Cora and 1.472 on AMAP, indicating strong resilience against privacy leakage.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.08595v1">Federated Deep Learning for Privacy-Preserving Cardiovascular Disease Risk Prediction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-07-09T15:29:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hyunho Mo, Djura Smits, Mahlet A. Birhanu, Maarten J. G. Leening, Daniel Bos, Pim van der Harst, Esther E. Bron</p>
    <p><b>Summary:</b> Cardiovascular disease risk prediction models often rely on data from a single institution or centrally pooled datasets. Extending these models across institutions could be limited by privacy regulations and constraints on sharing patient-level data. Federated learning enables collaborative model development without transferring sensitive patient data, but its application in healthcare remains challenging because datasets often differ in size, population characteristics, and outcome definitions. In this study, we present a federated deep learning approach for privacy-preserving cardiovascular disease risk prediction that integrates two population-based cohorts with different characteristics: Lifelines, including 148,230 participants meeting the study inclusion criteria with self-reported outcomes, and the Rotterdam Study, including a smaller cohort of 10,155 participants with digitally linked clinical outcomes. Model performance was primarily evaluated on the Rotterdam Study because of its complete follow-up. Deep survival models trained using federated learning achieved higher predictive performance than models trained locally without federation. For the Rotterdam Study, the C-statistic increased from 0.728 (95% CI: 0.717-0.739) to 0.739 (95% CI: 0.728-0.749). For Lifelines, the C-statistic increased from 0.783 (95% CI: 0.775-0.791) to 0.787 (95% CI: 0.780-0.792). These findings suggest that federated deep learning across heterogeneous cohorts can improve cardiovascular disease risk prediction while preserving the privacy of individual-level patient data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.08440v1">Coded Task Offloading for Fluid Computing: A Privacy-Aware Approach under D2D Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-07-09T13:02:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Diego Cajaraville-Aboy, Manuel Fernández-Veiga, Ana Fernández-Vilas, Rebeca P. Díaz-Redondo</p>
    <p><b>Summary:</b> Fluid Computing aims to support distributed applications execution across heterogeneous cloud, edge, and device resources, motivating task execution mechanisms that adapt to dynamic and privacy-sensitive environments under runtime conditions. In this context, current task offloading schemes rarely address privacy risks and information leakage under adversarial execution settings; furthermore, most coded computing proposals focus on straggler mitigation without considering system-level objectives such as energy awareness. This paper proposes a coded task offloading scheme for D2D networks under stochastic task arrivals and queue-based dynamics. The proposal combines task offloading techniques with linear secret sharing schemes, where tasks are encoded into redundant shares to support threshold-based recovery, straggler mitigation, and privacy preservation while enhancing system performance. Then, we formulate a privacy-aware offloading problem that jointly optimizes delay and energy while penalizing the theoretical privacy leakage of coded tasks under noisy leakage observations. The problem is solved using a branch-and-bound solver alongside a lightweight heuristic scheduler, both of which are evaluated through a discrete-event simulator. Results show that coded offloading improves the delay--energy trade-off with respect to classical full and parallel offloading schemes, while the heuristic achieves near-optimal performance, outperforming baseline and state-of-the-art solvers. The results also show how privacy leakage penalties reshape offloading decisions, exposing an inherent delay--energy--privacy trade-off.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.08402v1">Swapping Faces, Saving Features: A Dual-Purpose Pipeline for Pedestrian Privacy in ITS</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E">
  <p><b>Published on:</b> 2026-07-09T12:27:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Roba H. Farouk, Catherine M. Elias</p>
    <p><b>Summary:</b> Large-scale and diverse datasets are needed to train AI models to take real-time decisions for autonomous vehicles (AVs), an intelligent transportation system (ITS) application. Pedestrian intention and trajectory prediction are critical models used in AVs, requiring datasets involving diverse pedestrian images. Unrestricted access to these datasets imposes serious security risks, like identity theft and pedestrian tracking. The challenge is to apply privacy preservation procedures while maintaining the image attributes needed to train the models. Existing privacy methods may preserve the pedestrian's privacy, but degrade the image usability, which hinders the models' effectiveness. This work's focus is to implement a five-stage pipeline to protect pedestrians' privacy through face swapping while keeping the essential facial attributes intact. It should be tailored to satisfy the privacy needs of the Egy-DRiVeS dataset. Moreover, Roop and Ghost-v2 face-swapping models are evaluated. Provenly, Roop outperforms Ghost-v2 in various aspects, as will be discussed. Consequently, Roop is the face-swapping model to be used in the pipeline to strike the balance between pedestrian privacy via identity concealment and data usability via facial attribute preservation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.08282v1">Multi-Agent Firewall Architecture for Privacy Protection of Sensitive Data in Interactions with Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2026-07-09T09:23:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hugo García Cuesta, Pablo Mateo Torrejón, Alfonso Sánchez-Macián</p>
    <p><b>Summary:</b> While Large Language Models (LLMs) have become essential productivity tools, their integration into workflows without adequate safeguards creates significant risks. This paper proposes an open-source, privacy-focused, user-facing firewall designed to secure both web-based and programmatic LLM interactions. The architecture combines a browser extension and a proxy for total traffic interception across both HTTP(S) and WebSocket communications. At its core, a flexible multi-agent pipeline delivers data leakage prevention through a hybrid approach combining deterministic detectors with LLM-driven semantic analysis, proprietary code leakage prevention, and extensible components designed for future security enhancements such as prompt injection evasion. The framework's layered architecture enables deployment across heterogeneous environments, allowing organizations to balance computational cost, detection depth and latency. Evaluation results demonstrate it achieves F1 scores of up to 94.93% on optimal configurations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.08092v1">Equivariant Quantum Clustering with Differential Privacy: Parameter-Efficient Privacy-Preserving Analysis Across Heterogeneous Sensitive Datasets</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-07-09T04:01:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> B. M. Taslimul Haq, Md Arifur Rahman, Tawfiq Al Islam Foysal, Abdullah Al Noman, Abir Ahmed</p>
    <p><b>Summary:</b> Privacy-preserving clustering is critical for analyzing sensitive data in healthcare, cybersecurity, and enterprise applications, where maintaining data confidentiality must be balanced with analytical performance. This paper presents Equivariant Quantum Clustering (EQC), a parameter-efficient framework that integrates symmetry-aware quantum circuits with differential privacy to improve the privacy-utility tradeoff. EQC employs p4m equivariant parameter sharing to reduce circuit complexity while preserving informative feature representations. The framework is evaluated on three privacy-sensitive datasets: NSL-KDD, CERT Insider Threat v6.2, and a synthetic MIMIC-III clinical dataset. On the NSL-KDD benchmark, EQC achieves 79.3% clustering accuracy while reducing membership inference attack success to 38.3% under a privacy budget of ε = 1.0 and δ = 10^-5, outperforming representative classical and quantum baselines. Ablation studies indicate that the performance gains primarily arise from parameter-efficient circuit design combined with differential privacy. The results demonstrate that EQC provides a practical quantum-ready framework for secure and privacy-preserving clustering across heterogeneous sensitive datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.08801v2">A Seed for Privacy -- semi-automatic privacy-revealing data detection in databases and data streams</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-09T03:21:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> He Gu, Thomas Plagemann, Vera Goebel</p>
    <p><b>Summary:</b> Sharing databases and data streams imposes the danger of revealing private information in the form of complex events which can comprise individual data elements and their combinations. Identifying these privacy-revealing complex events is crucial for preserving privacy while maintaining data utility. However, data producers often lack the expertise to comprehensively identify these events, which undermines many state-of-the-art privacy-preserving mechanisms that rely on accurate event labeling. To address this challenge, we developed pArborist - a tool that can semi-automatically create a set of queries to identify and label privacy-revealing complex events in both static datasets and dynamic data streams, guided by the privacy requirements of the data producer. pArborist uses the schema of the database or data stream combined with initial input from the data producer, i.e., seed queries. From each seed query, pArborist grows a tree containing all possible syntactically correct queries, constrained by an upper limit on computational resources. Following this growing phase, the tree is refined by eliminating queries that lack correlation to the seed or are conditionally independent of the seed. Our evaluation indicates that pArborist achieves overall recall of 90% and precision of 93% in finding privacy-revealing queries, and this significantly surpasses the state-of-the-art approach FQID. In data stream processing experiments, pArborist introduces a delay of approximately 1.3 ms following an average warm-up period of 920 ms. The experiments also show that pArborist can automatically detect privacy-revealing complex events according to GDPR.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.07775v1">Idiobionics: The Unification of Privacy and Intelligent Robotic Prostheses</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E">
  <p><b>Published on:</b> 2026-07-08T17:18:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kwesi Afari Darfoor, Patrick M. Pilarski, Bailey Kacsmar</p>
    <p><b>Summary:</b> The human body is at the center of a growing family of technologies designed to tightly and persistently couple biological and digital systems. Robotic prostheses are a representative example of this tight coupling. Also referred to as bionic limbs, robotic prostheses are devices that support people who have lost limbs in pursuing daily life activities such as walking and grasping objects. Bionic limbs are now perceptive and responsive owing to their integration with advanced sensors and artificial intelligence-based control approaches. Consequently, such robotic prostheses can now be viewed as semiautonomous wearable robotic systems that can co-adapt with their users. However, the same sensing and control advancements that increase the capability of robotic prostheses also introduce threat vectors that could be exploited by malicious entities to violate the privacy of users. To fully realize the benefits of next-generation bionic limbs, we maintain it is important to directly understand and address these privacy risks and the barriers they might present to user adoption. This paper therefore introduces a new line of inquiry we term idiobionics to holistically investigate issues at the intersection of privacy and intelligent bionic limbs. As the main contribution of this paper, we define idiobionics, ground it in related literature, and provide preliminary evidence showing and discussing potential adversarial attacks that could exploit intelligent bionic limb designs. We then contribute a curated list of open research questions within idiobionics that are relevant to researchers in wearable robotics and other human-facing autonomous systems. We expect that idiobionics research will help unlock the full potential of robotic prostheses and related bionic devices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.07635v2">Unlearning to Protect: A Distilled Reinforcement Learning Framework with Privacy-Preserving Feature Unlearning and XAI for IoT Security</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-08T16:52:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Md. Nahid Hasan, Md. Golam Rabiul Alam</p>
    <p><b>Summary:</b> Botnets pose a significant cybersecurity threat, enabling attacks such as DDoS, data theft, and service disruptions on IoT devices. These devices often lack built-in botnet traffic filtering, leaving them highly exposed. Existing AI-based solutions improve detection capabilities but have limitations: (i) they are too heavy for IoT deployment, and (ii) they lack unlearning capabilities to forget sensitive or outdated features without retraining. To address these challenges, we propose DiRLU, a lightweight, reinforcement learning driven framework, while ensuring privacy by selectively unlearning sensitive or outdated features without requiring retraining. The framework leverages knowledge distillation to transfer knowledge from a teacher model into a lightweight student model, with both models trained using A2C. A post-hoc unlearning mechanism modifies weights to remove targeted features, while restored features show negligible performance loss, confirming reversibility. Unlike many benchmark models that used only 5% of the BoT-IoT dataset, this research leverages 25%, allowing us to develop a strong teacher model. Both the teacher and student models were trained using the A2C reinforcement learning algorithm, achieving impressive results, with the student model achieving 99.60% accuracy and a 99.80% F1 score. To enhance transparency, we integrated Explainable AI (XAI), particularly LIME, which helps interpret the model's decisions and identify the key features influencing its predictions. Moreover, DiRLU requires only 2,370 FLOPS, approximately 3.87x more efficient than the state-of-the-art model, highlighting its efficiency for edge deployment. DiRLU combines efficiency with privacy, aligning with GDPR standards (right to be forgotten) to provide practical and scalable IoT security solution.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.07371v2">zk-ScalHard: Scalable and Hardware-Rooted Privacy-Preserving Authentication for Secure OTA Updates in Zonal SDVs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-08T13:05:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shrikant Tangade, Bansi Pambhar, Valeria Loscri, Mauro Conti</p>
    <p><b>Summary:</b> The automotive industry is transitioning to Zonal-oriented Architectures (ZoA) for Software-Defined Vehicles (SDVs), enabling frequent over-the-air (OTA) updates for 100+ Electronic Control Units (ECUs). While OTA updates improve efficiency, they introduce safety-critical security risks. Current standards like Uptane and AUTOSAR Adaptive rely on Public-Key Infrastructure (PKI). However, PKI-based authentication creates bandwidth bottlenecks in in-vehicle and vehicle-to-cloud (V2I) communication as ECU density increases. It also risks exposing sensitive vehicle configurations and passenger privacy due to centralized architectures. Next-generation Zonal SDVs require decentralized, scalable authentication with data privacy. To address this, we propose zk-ScalHard, a hardware-rooted, privacy-preserving authentication protocol. We introduce a decentralized, hierarchical trust-promotion model utilizing Silicon Physical Unclonable Functions (PUFs) and two novel Zero-Knowledge Proof (ZKP) circuits: (1) Zonal Identity and Integrity (ZIDI) and (2) High-Performance Computing Aggregation (HPCA). These circuits employ multi-party computation (MPC) and recursive aggregation to achieve decentralization and scalability. The integration of ZKPs and PUFs ensures 100% vehicle-level data sovereignty. Benchmarked against Uptane, zk-ScalHard achieves constant O(1) communication and verification complexity, improving upon the linear O(n) complexity of current systems. Evaluation shows a 99.2% reduction in authentication bandwidth and a 99.9% reduction in the temporal attack surface. Our results demonstrate that zk-ScalHard provides a scalable, secure, and GDPR-compliant architecture for future Zonal SDVs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.07209v1">Continual Learning With Participation Privacy: An Auditable Buffering-Aggregation Recipe</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-07-08T09:44:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> T-H. Hubert Chan, Elaine Shi, Mengshi Zhao, Mingxun Zhou</p>
    <p><b>Summary:</b> Modern federated and streaming learning systems often release intermediate models, so privacy must hold for the full trajectory under adaptive interaction. Motivated by participation privacy, we study single-edit neighboring user streams, where one insertion/deletion shifts all subsequent updates and defeats standard Hamming-neighbor continual-release analyses. We give an auditable modular recipe. A randomized buffering wrapper emits bins of size $[U,2U]$, reducing single-edit streams to a Hamming-style per-bin update stream with explicit backlog/delay guarantees, where $U$ is calibrated by the privacy parameters $(\varepsilon,δ)$. We then prove a certification theorem identifying when a non-adaptive Hamming-neighbor DP proof for a continual primitive lifts to adaptive inputs: the primitive must use fresh per-round randomness and have a stable one-round privacy profile under common adaptive context. Together, these ingredients yield trajectory-level $(\varepsilon,δ)$-DP for single-edit streams using standard primitives (e.g., tree prefix sums), with an explicit privacy--latency link via $U$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.06963v1">Large Language Models (LLMs) and Generative AI in Cybersecurity and Privacy: A Survey of Dual-Use Risks, AI-Generated Malware, Explainability, and Defensive Strategies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-07-08T03:40:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kiarash Ahi, Saeed Valizadeh</p>
    <p><b>Summary:</b> Large Language Models (LLMs) and generative AI (GenAI) systems, such as ChatGPT, Claude, Gemini, LLaMA, Copilot, Stable Diffusion by OpenAI, Anthropic, Google, Meta, Microsoft, Stability AI, respectively, are revolutionizing cybersecurity, enabling both automated defense and sophisticated attacks. These technologies power real-time threat detection, phishing defense, secure code generation, and vulnerability exploitation at unprecedented scales. Following a rapid surge where LLM-generated malware grew to account for an estimated 50% of detected threats by 2025, up from just 2% in 2021, navigating this highly automated threat landscape in 2026 demands next-generation security frameworks. This paper presents a comprehensive survey of the beneficial and malicious applications of LLMs in cybersecurity, including zero-day detection, DevSecOps, federated learning, synthetic content analysis, and explainable AI (XAI). Drawing on a review of over 70 academic papers, industry reports, and technical documents, this work synthesizes insights from real-world case studies across platforms like Google Play Protect, Microsoft Defender, Amazon Web Services (AWS), Apple App Store, OpenAI Plugin Stores, Hugging Face Spaces, and GitHub, alongside emerging initiatives like the SAFE Framework and AI-driven anomaly detection. We conclude with practical recommendations for responsible and transparent LLM deployment and trustworthy AI, including model watermarking, adversarial defense, and cross-industry collaboration, setting a new benchmark for rigorous, holistic cybersecurity research at the intersection of AI and threat defense, and offering a roadmap for secure, scalable LLM systems that serves as a critical reference for researchers, engineers, and security leaders navigating the complex challenges of AI-driven cybersecurity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.06860v1">Auditable Machine Unlearning for Privacy-Compliant Ransomware Detection Using Multi-Shard SISA and Deep Reinforcement Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-07T23:23:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jannatul Ferdous, Rafiqul Islam, Md Zahidul Islam</p>
    <p><b>Summary:</b> Ransomware poses an escalating cybersecurity threat as attackers continuously modify behavioral patterns to evade static defenses. Although existing machine learning-based detectors often achieve strong predictive performance, they generally assume fixed training data and do not support the selective removal of previously learned samples. This limitation conflicts with privacy regulations such as the GDPR and CCPA, which require the removal of sensitive user data upon request. To address this challenge, we propose an auditable ransomware detection and unlearning framework that integrates deep reinforcement learning with multi-shard SISA retraining. In the proposed system, a Double Deep Q-Network (DDQN) learns a reward-guided detection policy from behavioral features under asymmetric security costs, while multi-shard SISA enables privacy-compliant selective sample removal through shard-level retraining. The framework was evaluated using four criteria: utility preservation, oracle-based forgetting validation, membership inference auditing, and computational efficiency. On a balanced Windows 11 behavioral dataset comprising 2,000 samples and 103 features, the baseline DDQN detector achieved an F1 score of 0.9925 and an AUC of 0.9983. The experimental results show that single-shard unlearning maintains minimal utility degradation and low oracle disagreement, whereas moderate shard counts (M = 5-10) provide the best efficiency-performance trade-off, reducing retraining time to 5-30 s compared with 80-330 s for full retraining. In addition, the membership inference scores remain close to 0.5 across most configurations, indicating limited privacy leakage after unlearning. These findings demonstrate that a privacy-compliant ransomware detection framework can jointly achieve high detection performance, auditable deletion verification, and efficient sample removal.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.06815v1">Behavioral Privacy Leakage in Agentic Negotiation: Formalizing and Mitigating Inference Attacks via Randomized Policies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-07T21:22:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Barkha Rani</p>
    <p><b>Summary:</b> Autonomous negotiation agents are increasingly deployed in high-stakes settings such as insurance and procurement. While cryptographic techniques protect explicitly disclosed constraint values, they fail to address a subtler threat: behavioral privacy leakage, where an adversary infers private constraints from observable negotiation dynamics such as concession trajectories, timing, and convergence patterns. This paper investigates behavioral differential privacy in multi-round negotiation protocols. We design an adaptive stochastic negotiation policy that jointly guarantees $(\varepsilon, δ)$-differential privacy, almost-sure convergence of the offer sequence (reaching agreement when the counterparty's reservation value permits), and high negotiation utility. Evaluated on 3,000 synthetic bilateral negotiations, our mechanism reduces adversarial inference accuracy by 43-50% while maintaining a negotiation success rate and utility above 90%, demonstrating that strong privacy guarantees can be achieved without significant loss of performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.06687v1">Exploring the Interaction of Explanation Styles, Context, and Trust of AI Privacy Redaction in AI-mediated Interactions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-07-07T18:04:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Roshni Kaushik, Maarten Sap, Koichi Onoue</p>
    <p><b>Summary:</b> AI-mediated communication is increasingly being utilized to help facilitate interactions; however, in privacy sensitive domains, an AI mediator has the additional challenge of considering how to preserve privacy. In these contexts, a mediator may redact or withhold information, raising questions about how users perceive these interventions and whether explanations of system behavior can improve trust. In this work, we investigate how explanations of redaction operations can affect user trust in AI-mediated communication. We devise a scenario where a validated system removes sensitive content from messages and generates explanations of varying detail to communicate its decisions to recipients. We then conduct a user study with 180 participants that studies how user trust and preferences vary for cases with different amounts of redacted content and different levels of explanation detail. Our results show that participants believed our system was more effective at preserving privacy when explanations were provided (p<0.05, Cohen's d ~ 0.3). We also found that contextual factors had an impact; participants relied more on explanations and found them more helpful when the system performed extensive redactions (p<0.05, Cohen's f ~ 0.2). We also found that explanation preferences depended on individual differences as well, and factors such as age and baseline familiarity with AI affected user trust in our system. These findings highlight the importance and challenge of balancing transparency and privacy in AI-mediated communications and suggest that adaptive, context-aware explanations are essential for designing privacy-aware, trustworthy AI systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.06371v1">The Impact of Security and Privacy Controls on Users' Emotional Engagement with Generative AI Chatbots</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-07-07T15:10:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jabari Kwesi, Jiaxun Cao, Hailee Cunningham, Pardis Emami-Naeini</p>
    <p><b>Summary:</b> Chatbots powered by generative AI (e.g., OpenAI's ChatGPT and Google's Gemini) are increasingly being appropriated for emotional support and companionship. These tools offer a suite of security and privacy (S&P) controls, including model training opt-outs and memory toggles, yet how the presence of these controls influences users' attitudes toward emotionally sensitive disclosure remains understudied. We conducted a mixed-methods vignette study with 354 U.S. participants to examine how S&P controls influence users' willingness to engage with generative AI chatbots for emotional support, their perceptions of how protected they are when using these systems, and their perceptions of how effective the chatbots are for providing support. Controls enabling deletion of disclosures had the largest positive impact: these offerings outperformed technically sophisticated controls such as local-only processing and model training opt-outs, where participants expressed difficulty understanding the underlying mechanisms. Yet trust remains fragile, and participants often doubted S&P controls would function as promised. We conclude with actionable recommendations informed by our results to bridge users' comprehension gaps, build credible assurances, and properly calibrate barriers for users in distress.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.06320v1">Dithered Gaussian Mechanism for Randomness-Efficient Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-07-07T14:20:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nikita P. Kalinin, Rasmus Pagh</p>
    <p><b>Summary:</b> We present the dithered Gaussian mechanism, a novel alternative to the discrete Gaussian mechanism for differential privacy that discretizes the private output rather than the noise distribution itself. By interpreting this discretization as post-processing of the Gaussian mechanism, our construction directly inherits the privacy guarantees of the standard Gaussian mechanism while avoiding vulnerabilities caused by finite-precision floating-point outputs. We show that the mechanism is provably randomness-efficient: by sampling the discretized output values directly, the number of high-quality random bits required for privacy can be reduced significantly and made independent of the noise level. This is achieved by separating the randomness into two sources: a high-quality source used for the privacy-critical sampling step, and a high-performance public source, possibly known to the adversary, that supplies the additional randomness needed for randomized discretization. This separation enables the use of cryptographically secure randomness without substantial performance loss. As an application, we study model training with DP-SGD and show that cryptographically secure noise generation with reduced exposure to floating-point vulnerabilities can be achieved with modest practical overhead.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.06307v1">Quantum Probabilistic Local Differential Privacy: Structural Properties and Sample Complexity Bounds</a></h3>
  
  <p><b>Published on:</b> 2026-07-07T14:11:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xian Shi</p>
    <p><b>Summary:</b> Differential privacy provides a rigorous framework for quantifying privacy leakage in data analysis, while its quantum extensions have become increasingly relevant with the development of quantum computing and quantum machine learning. In this work, we introduce and study quantum probabilistic local differential privacy, a relaxation of quantum local differential privacy in which the privacy constraint is allowed to fail on a spectral violation event with low probability. This quantity can be interpreted as the probability under the quantum superoperation of a quantum privacy-loss violation, and is closely related to the acceptance probability of the quantum Neyman-Pearson test at a small threshold. We investigate the basic structural properties of this privacy notion and clarify its relationship with existing forms of quantum differential privacy. We show the properties of quantum probabilistic local differential privacy under tensor-product composition and unitary post-processing, while it is in general neither convex nor closed under post-processing by arbitrary quantum channels. We further characterize when depolarizing noise satisfies quantum probabilistic local differential privacy under several representative scenarios. Finally, we connect quantum probabilistic privacy constraints with statistical inference by deriving a lower bound on probabilistically privatized contraction coefficients in terms of the hockey-stick divergence. As an application, we obtain sample complexity bounds of probabilistically privated asymmetric and symmetric quantum hypothesis testing. These results provide a systematic foundation for studying probabilistic privacy guarantees in quantum information processing and their operational consequences for private quantum statistical inference.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.06141v1">The Masks We (Think We) Wear: Privacy Threats of Browser-Extension Wallets in the Web3 Ecosystem</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-07T11:08:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Weihong Wang, Yana Dimova, Victor Vansteenkiste, Tom Van Goethem, Tom Van Cutsem</p>
    <p><b>Summary:</b> Cryptocurrency wallets are the primary interface for managing pseudonymous blockchain addresses, viewing balances, and interacting with Web3 applications. Although users typically assume that their addresses remain independent of each other unless intentionally revealed, modern wallets routinely communicate with both blockchain infrastructure and decentralized applications (dApps), generating network-side and web-side signals that may undermine this assumption.
  In this paper, we identify and formalize five privacy threats that arise directly from wallets interacting with the network and the web browser. Using large-scale dynamic measurements of 85 of the most popular Chrome Web Store browser-extension wallets (representing 35.16 million users), we observe that routine remote procedure call (RPC) operations leak structural links between a user's addresses; that the majority of Ethereum wallets implement permission revocation inconsistently and continue to expose previously revoked addresses across sessions; and that many wallets inject their provider interfaces into cross-origin iframes, enabling passive cross-site tracking beyond dApps and potentially real-world identity deanonymization without user interaction.
  Taken together, our results show that these wallet behaviors leak sensitive information that can be used to link multiple addresses to the same user, track wallet users across sessions and sites, and connect their browsing activity to their on-chain wealth.
  We discuss practical mitigations and show that many of these threats can be substantially reduced through improved wallet implementation, stronger privacy considerations in ecosystem standards, and stricter controls over provider exposure. Our results highlight the need for standardized, privacy-preserving wallet architectures.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.06127v2">Measuring the practice of shared-decision making (OPTION12): An Investigation into Open-sourced Smaller LLMs (OS-sLLMs) for Better Privacy and Sustainability</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-07-07T10:37:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tamara Wit, Lifeng Han, Carly Heipon, David Lindevelt, Anne Stiggelbout, Suzan Verberne</p>
    <p><b>Summary:</b> We present LLM4SDM, the first study of open-source smaller language models (OS-sLLMs) for automated assessment of shared decision making (SDM) using the Observer OPTION12 framework. Unlike previous work that relies on large commercial models and the shorter OPTION5 instrument, our study focuses on privacy-preserving locally deployable models and Dutch melanoma consultation transcripts. Using expert-annotated clinical consultations, we evaluate three general-domain and two medical-domain OS-sLLMs during a development-phase pilot study. Results show that general-domain models outperform medical-domain models, which exhibit substantial hallucination and instruction-following failures. Gemma3:12b achieves the strongest agreement with human annotations (Pearson r=0.51, Spearman \r{ho}=0.59). Item-level and qualitative analyses reveal systematic challenges related to temporal discourse reasoning, conversational role attribution, and evidence grounding. We further introduce a Judge-LLM consensus framework designed to support disagreement resolution among multiple models. Our findings suggest that while current OS-sLLMs cannot replace human annotators, they offer a promising foundation for privacy-preserving human-in-the-loop SDM assessment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.06037v1">REAN: Reconstruction-aware ECG Anonymization Based on Privacy--Utility Orthogonality</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-07-07T09:12:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Taerin Ki, Sunghwan Park, Junyoung Park, Jaewoo Lee</p>
    <p><b>Summary:</b> A shared electrocardiogram (ECG) is itself a biometric fingerprint that can re-identify a patient and reveal personal information. Recent ECG anonymizers transform the signal before sharing to reduce privacy leakage. However, existing methods still face a privacy--utility trade-off, in which preserving privacy often compromises utility while preserving utility reveals personal information. We propose \emph{REAN} (\emph{RE}construction-aware ECG \emph{AN}onymizer), a raw ECG signal anonymizer, to address this privacy--utility trade-off. REAN reconstructs the signal using a 1-D U-Net trained with losses from frozen privacy and utility classifiers to reduce privacy leakage while preserving utility. The privacy and utility gradients are near-orthogonal ($\approx$93.8$^\circ$), so reducing privacy leakage leaves utility almost unchanged. On four public PhysioNet databases, REAN achieves the strongest privacy--utility balance among raw ECG signal baselines. It drives re-identification to chance (0.96$\to$0.00), keeps arrhythmia macro-AUROC at the clean level (Clean 0.9982 vs.\ REAN 0.9991), and maintains re-identification protection under unseen privacy-classifier architectures.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.05996v1">Unlearnable Faces: Privacy Protection Surviving Extraction Pipeline</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-07-07T08:30:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Byunghoon Oh, Sunghwan Park, Jaewoo Lee</p>
    <p><b>Summary:</b> Unlearnable examples keep publicly shared photos from being learned by unauthorized face-recognition models. An imperceptible perturbation, added before sharing, makes any model trained on the protected photos fail on clean faces. The perturbation is crafted on the shared image, however the attacker trains on the face it extracts, cropped and resized to the recognizer input, and under this extraction the protection collapses. We propose LPID, which builds the extraction into the unlearnable-example objective. LPID confines the perturbation to the extracted face region and optimizes it through a differentiable model of the extraction, concentrating its energy in the frequency band the extraction preserves. Because this robustness is a property of the transform rather than of any identity, LPID is re-optimized per album and protects even users it has never seen. LPID attains the lowest attacker accuracy of all methods in every setting we evaluate, holding the attacker below $10\%$ under crop+resize extraction on identities unseen at protection time, while remaining imperceptible at $32.7$\,dB PSNR and $0.161$ LPIPS.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.06608v1">Security and Privacy in Agentic AI: Grand Challenges and Future Directions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-07-07T05:45:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Adam Jenkins, Agnieszka Kitkowska, Caterina Maidhof, Diego Paracuellos, Francesco Sovrano, Gonzalo Gabriel Mendez, Guillermo Suarez-Tangil, Hana Kopecka, Isabel Wagner, Isabel Barbera, Javier Carnerero-Cano, Jide Edu, Jose Luis Martin-Navarro, Jose Such, Josep Domingo-Ferrer, Juan Carlos Carrillo, Kopo Marvin Ramokapane, Mark Cote, Pablo Vellosillo, Ramon Ruiz-Dolz, Rongjun Ma, Ruba Abu-Salma, Sameer Patil, William Seymour, Xiao Zhan</p>
    <p><b>Summary:</b> We present key challenges and future research directions in the security and privacy of agentic AI, based on a horizon-scanning exercise that brought together thirty leading international experts from academia, industry, and government to engage in focused discussions and collaborative exercises on the emerging risks associated with the growing agency of AI.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.05802v1">Failure Privacy and Safe Collective Expression</a></h3>
   
  <p><b>Published on:</b> 2026-07-07T03:55:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Matthew Cashman</p>
    <p><b>Summary:</b> Widely held views can go unspoken when speaking out alone invites retaliation. I recast such silence as a problem of safe coalition formation. When safety comes in numbers, there is a largest group that could speak safely. Open organizing must stay safe every step the way, making for a cascade of speaking up that stops short of that largest group. Social assurance contracts need safety only at the destination, and get there by keeping commitments private until enough people have joined: a tunnel to the largest safe group. If no member may ever regret joining, such failure privacy is necessary, not merely sufficient.</p>
  </details>
</div>


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
  <h3><a href="http://arxiv.org/abs/2607.04209v2">Ball Differential Privacy: How to Mitigate Data Reconstruction with Less Noise</a></h3>
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
  <h3><a href="http://arxiv.org/abs/2606.26373v4">Hybrid privacy-aware semantic search: SVD-truncated document geometry and CKKS-encrypted query reranking under a restricted threat model</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2026-06-24T20:50:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sergey Kurilenko</p>
    <p><b>Summary:</b> Semantic search creates an asymmetric disclosure problem: query embeddings may reveal user intent, while returning exact provider vectors distributes reusable representations. We evaluate a deliberately restricted hybrid design. A public corpus-fitted SVD basis and PQ index support client-side candidate selection; candidate IDs are disclosed, while the projected query is encrypted with CKKS. A block-SIMD kernel scores 100 plaintext provider vectors and returns one ciphertext. At 672 dimensions, median server time falls from 1689.1 to 224.5 ms and response size by a factor of 99.5; provider-only saturation reaches 25.99 requests/s with 16 workers. In a frozen post-exploratory revision-analysis subset, disjoint from validation and containing 3,235 canonical BEIR queries, five of six collections satisfy a +/-0.002 nDCG@10 equivalence rule between actual CKKS and plaintext reranking of the same shortlist, while ArguAna is inconclusive. Projection controls favor SVD over random and coordinate truncation. Leakage audits show that disclosed candidate sets are highly linkable and reproduce part of the exact neighbourhood, while public PQ reveals approximate corpus geometry. The design therefore conditionally hides numerical query slots, but does not provide semantic-query, document, unlinkability, circuit, or access-pattern privacy.</p>
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

