
<h2>2026-09</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.08476v1">When Topology Betrays Privacy: Lattice-Based Reconstruction Attacks on Secure Aggregation in Decentralized Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-08T09:20:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenrui Yu, Changlong Ji, Johannes Bjerva, Qiongxiu Li</p>
    <p><b>Summary:</b> Secure Aggregation (SA) is widely regarded as a strong defense against model-update leakage in Federated Learning (FL), as it reveals only aggregate results while hiding individual updates. In Decentralized Federated Learning (DFL), SA is commonly instantiated as local neighborhood aggregation, where each node obtains a weighted aggregate over its neighbors. We show that this locality creates a structural leakage surface: sparse decentralized topologies provide colluding semi-honest nodes with asymmetric aggregate views, exposing multiple hidden linear combinations of honest participants' private states. Reconstructing private states from these aggregate views is fundamentally challenging, as both the private states and the aggregation coefficients are hidden. We tackle this challenge by establishing a formal connection to the Hidden Subset Sum Problem, a long-studied problem in cryptography. Building on this formulation, we design a lattice-based reconstruction approach that combines lattice reduction with structural filtering to reconstruct protected model states. We evaluate our attack on image, tabular, and text tasks under sparse DFL topologies. Our results show that colluding semi-honest nodes can recover the original local updates of honest nodes, enabling downstream reconstruction of private training data. These findings demonstrate that SA alone does not guarantee privacy in DFL when local aggregation induces asymmetric observations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.08103v1">AVP-Inspect: Coordinated Cyber-Physical Testing for Privacy Analysis of COTS Apple Vision Pro Applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-08T01:24:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yichang Xiong, Vamsi Shankar Simhadri, Yue Xiao, Xiaokuan Zhang</p>
    <p><b>Summary:</b> XR devices introduce substantial privacy concerns due to their comprehensive data collection capabilities that surpass traditional computing platforms. While existing works have demonstrated privacy concerns on Android-based XR devices such as Meta Quest series by performing network traffic analysis, little attention has been paid to the Apple Vision Pro (AVP) devices, mainly due to the closed nature and the technical challenges associated with AVP devices. In this work, we make a bold attempt to detect privacy violations of AVP applications from network traffic through automatic testing on AVP devices. Our key insight is that effective AVP application testing requires coordinated control of both cyber (software) and physical (hardware) components, which we term Coordinated Cyber-Physical Testing. Building on this insight, we design and implement AVP-Inspect, an automatic dynamic analysis framework for AVP applications, overcoming significant challenges enforced by the closed-source nature of AVP ecosystem. AVP-Inspect consists of three components: an automatic device controller by building customized hardware devices, a 3D UI explorer by designing a new exploration engine, and a privacy violation detector by constructing a unified privacy taxonomy for AVP. We first evaluated AVP-Inspect on a manually constructed ground truth dataset, then performed a large-scale analysis on 324 AVP applications downloaded from the App Store, with each app tested for 20 minutes. We found that 188 (58.0%) of apps exhibit at least one violation, and more than 60% of the network traffic flows are not properly disclosed.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.07654v1">ZK-eSIM: A Privacy-Centric Zero-Knowledge Approach for eSIM Provisioning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-07T15:42:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Liza Ahmad, Quan Shi, Joshua Haworth, Yilu Dong, Prosanta Gope, Behzad Abdolmaleki, Syed Rafiul Hussain</p>
    <p><b>Summary:</b> GSMA Remote SIM Provisioning (RSP) enables over-the-air delivery of eSIM profiles, but it exposes long-lived identifiers during profile ordering and download. In particular, stable device identifiers (e.g., EID), profile identifiers, and long-lived certificate material enable mobile operators and profile-delivery infrastructure to link provisioning events to the same eUICC and, when combined with account records, to the same subscriber. This undermines subscriber anonymity and enables cross-session tracking. We present ZK-eSIM, a privacy-preserving redesign that achieves subscriber anonymity and provisioning-session unlinkability while retaining accountable traceability by exception. ZK-eSIM (i) replaces direct disclosure of device identifiers with a zero-knowledge proof of device validity and eligibility; (ii) enforces session unlinkability through short-lived, one-time pseudonymous credentials and per-session identifiers to prevent cross-session tracking; and (iii) provides privacy-preserving accountable traceability through a jointly authorised escrow mechanism, so that no single entity can unilaterally deanonymise a user. We formalise a multi-entity, honest-but-curious threat model and prove subscriber anonymity and the unlinkability of provisioning sessions under standard cryptographic assumptions. We implement a Java Card applet on a test eUICC to evaluate performance on commodity hardware with a modified LPA and SM-DP+ server. Our experiments quantify end-to-end cryptographic overhead relative to conventional RSP, confirming that ZK-eSIM adds only practical overhead, closing a critical privacy gap while preserving deployability within existing GSMA roles and interfaces.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.07623v1">Privacy Leakage from a Thousand Words: Millipixel Location Recovery from Dot Maps</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-09-07T15:25:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuntao Du, Tanishq Pauskar, Hao Wang, Jing Su, Ninghui Li</p>
    <p><b>Summary:</b> Dot maps, which visualize individual data points as dots over a geographic region, are widely used across diverse domains to represent spatial patterns in sensitive data. However, the understanding of the privacy risks associated with dot maps remains limited, particularly for maps covering large geographic areas. In this paper, we systematically analyze these risks and present AutoLocate, an automated framework for high-precision location recovery. At its core, AutoLocate exploits anti-aliasing artifacts introduced during map rendering, which inadvertently encode sub-pixel information about dot locations. AutoLocate formulates location recovery as a black-box optimization problem, iteratively refining estimated coordinates by minimizing perceptual discrepancies over these artifacts between the target map and rendered candidate maps. Extensive experiments on both real-world and synthetic datasets, across different attack scenarios and a broad range of map configurations (e.g., map scale, background, resolution), demonstrate the effectiveness of AutoLocate. In particular, it achieves average recovery errors as low as 1 meter (approximately 0.0002 pixel precision) on small-scale maps of the United States, over 200x more accurate than existing approaches. We also propose mitigation strategies and introduce a privacy risk assessment tool to help practitioners evaluate and reduce privacy leakage when publishing dot maps.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.07428v1">Masking Radar Cognition under Adversarial Surveillance: A Distributional Privacy Framework</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-07T12:32:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sreedevi K, Nandhini K, Anup Aprem, Deepthi P P</p>
    <p><b>Summary:</b> In this article, we propose an online electronic counter-countermeasure (ECCM) framework designed to conceal the strategic decision-making processes of a cognitive radar (CR) operating under adversarial surveillance. We model the CR under two distinct decision paradigms: a static constrained utility-maximizing behavior and a dynamic expected utility-maximizing behavior. The radar's utility function is modeled via a von Mises--Fisher (vMF) distribution, with the distributional parameter constituting the private information to be protected from adversarial inference. We adopt a distribution privacy framework to conceal this private information and provide formal distribution privacy guarantees for cognition masking. In this work, we develop cognition-hiding algorithms for both static constrained utility maximization (WDPCH-SU), and dynamic expected utility maximization (WDPCH-DU). Through rigorous mathematical analysis, we show that both WDPCH-SU and WDPCH-DU satisfy $ε$-distribution privacy ($ε$-DistP) against inference-based adversarial attacks and present the privacy--performance trade-off bounds, quantifying utility loss (in static setting) and expected utility deviation (in dynamic setting) as functions of $ε$. Numerical results show that WDPCH-SU gives about 15\% improvement in utility loss at maximum privacy compared to the existing methodology while WDPCH-DU achieves a greater reduction in adversarial Fisher information without requiring explicit Fisher information constraints, at a moderate, analytically bounded utility deviation. These results are highly promising in many 6G communication scenarios such as network slicing for automated driving and swarm UAV coordination, where it is essential to keep the resource allocation policy robust against privacy attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.07217v1">Enhancing Privacy, Neglecting Harms: An Analysis of Real-World Digital Privacy Incidents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-09-07T08:34:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shannon Veitch, C. Shem, Lena Csomor, Oleksandr Dudiy, Naone Kim, Khoi Le, Lina Saha, Alexander Viand, Anwar Hithnawi, Bailey Kacsmar</p>
    <p><b>Summary:</b> Privacy-enhancing technologies (PETs) have emerged as a technical means for providing individuals with greater control over their information. Yet despite the growing deployment of PETs, people continue to experience privacy harms. In this work, we revisit our understanding of privacy incidents and the realities of those experiencing privacy harms, to assess whether the goals and abilities of PETs are misaligned with the harms people face.
  For our study, we collect news articles that correspond to a sample of 257 real-world privacy incidents. We employ content analysis over the articles to develop a new information flow model that encompasses the complexity of data flows and their relation to resulting harms. We demonstrate that our model captures both established and novel aspects of privacy incidents and their mitigations. In particular, it captures why consent is often insufficient to prevent privacy violations, how harms emerge from complex interactions among multiple entities and actions, and reveals a flaw in our understanding of PETs: a focus on enabling functionalities still permits the harms inherent in those functionalities. Moreover, we find that the entities best positioned to implement harm-preventing measures for the incidents in our sample are the least incentivized to do so. Overall, our model and analysis identify limitations of privacy technology research for harm prevention and further identifies paths for transforming how we approach the advancement of these technologies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.07038v1">AdoDAS: A Privacy-Preserving Multimodal Challenge for Adolescent Depression, Anxiety, and Stress Assessment</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Multimedia-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36">
  <p><b>Published on:</b> 2026-09-07T04:49:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhaojie Luo, Junkun Wang, Tianhua Qi, Yuxuan Wu, Xin Zhao, Tetsuya Takiguchi, Tomoko Matsui, Kun Qian, Fei Wang, Shuqiong Wu, Zhengjun Yue, Hiroshi Ishiguro, Xinyuan Qian, Haizhou Li</p>
    <p><b>Summary:</b> Adolescent depression, anxiety, and stress (D/A/S) call for scalable tools that complement, rather than replace, professional evaluation. Under a privacy-preserving policy, the AdoDAS Grand Challenge withholds minors' raw recordings and distributes anonymized audio-visual representations and ASR-derived text. Its 6,000 participants provide 24,000 segments across one scripted-reading and three open-response sessions. Two tracks assess multi-task binary D/A/S screening and ordinal prediction of 21 DASS-21 item responses. From 191 registrations, the final leaderboards included 95 eligible screening teams and 64 item-prediction teams. Audio-visual baselines achieved 0.4604 mean F1 and 0.2675 mean Quadratic Weighted Kappa; leading submissions reached 0.5921 and 0.2776. Representative systems emphasize cross-session modelling, temporal multimodal fusion, psychometric structure, and task-aware calibration.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.07022v1">CIPHER: Benchmarking Cross-record Inference over Privacy-Hardened Evidence Records</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-09-07T04:21:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Suparno Roy Chowdhury, Manan Roy Choudhury, Dhruv Madhwal, Vivek Gupta</p>
    <p><b>Summary:</b> Reasoning over privacy-constrained records requires combining structured attributes with evidence from free-text narratives. We introduce CIPHER (Cross-record Inference over Privacy-Hardened Evidence Records), a benchmark of expert-validated questions from consumer-finance, clinical, and law-enforcement records. The questions cover common tabular operations and include executable SQL supervision. We evaluate retrieval, prompting, table-specialist, and hybrid symbolic-neural systems under native redaction and surrogate-based evidence restoration. All system families exhibit substantial failures even when supporting records are provided. Most errors arise from incorrect record selection and predicate interpretation rather than arithmetic execution. Privacy transformations have non-uniform effects, sometimes obscuring necessary evidence and sometimes reducing distraction. CIPHER provides a reproducible testbed for diagnosing these failures and assessing how transformations of sensitive text affect reasoning over hybrid records.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.06928v1">Emo-DVS: A Multimodal Benchmark for Privacy-Aware Emotion Recognition with Event Cameras</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-09-07T01:55:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiaqi Chen, Qinfu Xu, Hao Zhuang, Liyuan Pan</p>
    <p><b>Summary:</b> Emotion analysis is a fundamental task in computer vision, but its practical deployment remains constrained by the privacy risks inherent to conventional RGB cameras. Bio-inspired event cameras present a promising hardware-level solution because they capture asynchronous brightness changes, thereby reducing exposure of facial identity details while leveraging high dynamic range for robust perception under challenging illumination conditions. Despite these advantages, existing event-based methods struggle in complex real-world settings due to limited dataset scales, simple acquisition conditions, and reliance on single-modality visual cues. To address these, we establish a challenging tri-modal benchmark with event, audio, and text modalities and propose the Information-Guided Gated Fusion (IGF) framework, which first pre-trains an event encoder on the FAU subset of Emo-DVS to capture fine-grained facial dynamics, then employs adaptive modality gating to suppress modality-specific noise, and finally leverages mutual information maximization to align robust cross-modal representations. To alleviate data scarcity, we introduce Emo-DVS, the first large-scale event-based emotion analysis dataset, which couples dynamic illumination with the Facial Action Unit (FAU) subset and emotion subset. Extensive experiments demonstrate that IGF achieves state-of-the-art performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.06749v1">A Novel Semantic Manifold Alignment Attack against Embedding-to-Embedding Obfuscation in Privacy-Preserving LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-09-06T17:45:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sicong Li, Lingfeng Yao, Xingke Yang, Ke Tu, Chenhao Wu, Hao Wang, Jiang Liu, Phone Lin, Xin Fu, Miao Pan</p>
    <p><b>Summary:</b> With the widespread applications of large language models (LLMs), privacy-preserving inference has become increasingly essential for sensitive queries. To balance privacy and utility, a series of lightweight obfuscation approaches has recently been proposed, where users locally transform plaintext embeddings into the fixed ciphertext ones. While such Embedding-to-Embedding Obfuscation (E2EO) schemes demonstrate considerable resilience against traditional token frequency and embedding inversion attacks, the core mechanism behind remains to be the large-scale one-to-one substitution, which provides no cryptographic guarantees. In this paper, we propose Proxy Manifold Alignment (PMA), a novel attack against E2EO in privacy-preserving LLMs. Our key observation is that E2EO schemes keep the original semantic structure, so that the obfuscated vector stream can be regarded as an unknown tokenizer-language whose symbols are the vectors themselves. Therefore, the proposed ciphertext to plaintext reconstruction attack can be formulated as a translation task from the unknown tokenizer-language to plaintext. Specifically, by only accessing the obfuscated vector stream, the target tokenizer and a public corpus, the PMA attack first employs Word2Vec to model the co-occurrence patterns within the obfuscated stream and the public corpus independently, and constructs two proxy vector embeddings. Then, the attack aligns the underlying manifolds of these two embeddings based on structural similarity. Finally, it maps the obfuscated vectors back to plaintext. Experimental results demonstrate that PMA consistently achieves higher plaintext recovery than other state-of-the-art attack methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.05702v1">Characterizing Privacy Risks of Quantum Machine Learning with Emergent Quantum-Native Access</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-04T20:14:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Liou Tang, James Joshi, Ashish Kundu</p>
    <p><b>Summary:</b> Quantum Machine Learning (QML) has shown rapid advances by utilizing quantum computing for machine learning tasks. Meanwhile, the privacy risks accompanying QML is also starting to be studied, which inherit privacy leakage channels from "classical" ML and also quantum-unique risks. Existing work on privacy-preserving QML largely focuses on a QML-as-a-service scenario, which generally assumes that the QML model owner provides only classical bit outputs to queries, while users (and adversaries) have only classical computing abilities. However, this view is increasingly challenged in a quantum-native world of quantum-capable users/adversaries, which may have access to both quantum computing abilities and access to quantum information output from service providers.
  In this paper, we aim to bridge this gap by examining membership inference attacks against QML models by demonstrating that increasing quantum access and quantum computing abilities provides provable theoretical privacy leakage and empirical adversarial gain. However, the probabilistic nature of QML introduces a gap between theoretical and empirical adversarial advantage. These results show that existing research on privacy leakage on QML models underestimate privacy leakage in an emergent quantum-native access regimes, which we hope to establish a first step into examining potential privacy leakages for QML in the quantum-native world.These results show that existing research on privacy leakage in QML models underestimates privacy leakage in emergent quantum-native access regimes, and we hope to establish a first step in examining potential privacy leakages for QML in the quantum-native world.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.05340v1">Trust-Aware Adaptive Disclosure for Inference Privacy Preservation in Multi-Agent Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-04T16:44:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Puspanjali Ghoshal, Tobias J. Oechtering</p>
    <p><b>Summary:</b> Agent based systems are increasingly deployed in information critical systems including healthcare management systems, and smart grids. In this paper, we consider a multi-agent system where each agent has a latent goal that needs to be kept hidden from observing adversaries. More specifically, this paper studies privacy-preserving consensus in networked multi-agent systems under goal inference attacks. We propose a Trust-Aware Privacy Control framework that adapts message disclosure based on the dynamic trust relationships between agents. The proposed method controls information release using a trust-dependent stochastic policy. This enables a tradeoff between consensus performance and privacy preservation. Experiments demonstrate that the proposed method reduces adversarial goal inference accuracy compared to representative baselines, while maintaining competitive consensus utility, thereby highlighting the effectiveness of trust-aware mechanisms in privacy preservation of the agents in multi-agent systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.05119v1">Understanding the Privacy-Preserving Potential of HTTP/2 Against Webpage Fingerprinting</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-04T13:16:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bogdan Cebere, Prateek Kumar, Sylvain Chatel, Wouter Lueks, Christian Rossow</p>
    <p><b>Summary:</b> Website fingerprinting (WF) attacks can infer which webpage a user visits from encrypted HTTPS traffic alone, compromising privacy even without decryption. WF defenses commonly shape traffic through noise, padding, delays, or flow splitting, yet they are most often studied from the perspective of encapsulating protocols like Tor or VPN rather than at the application layer (HTTP).
  In this work, we focus on application-layer defenses enabled by the most widely deployed version of HTTP, HTTP/2. We demonstrate how known defenses can be emulated through HTTP/2 features at the client side (HTTPOS, LLaMA, FRONT, Tamaraw) and the server side (ALPaCA, Tamaraw). We further show that HTTP/2 features, such as proactive resource suggestion, multiplexing, and flow control, offer untapped potential for lightweight yet effective defenses deployable at both endpoints.
  We evaluate these defenses using a unified blueprint that calibrates defense parameters per dataset, then combines practical attacks, information-theoretic leakage estimates, and overhead measurements. For each defense, this framework identifies the strongest hyperparameter-tuned fingerprinting model and estimates the residual uncertainty induced by the defense using two information-theoretic leakage estimators, all while accounting for the defense's privacy-overhead trade-offs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.05095v1">CAT-LDP: Cloud-edge Adaptive Taxonomy under Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2026-09-04T12:49:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Junzhe Yang, Chang Xia, Xiyun Wang, Anren Sun, Wenbo Ding, Xinye Chen</p>
    <p><b>Summary:</b> Recommender systems are widely used in daily life, but their direct collection and use of user preference data can also lead to privacy leakage. Existing privacy-preserving recommendation methods often find it hard to balance user privacy and recommendation performance. This problem is more serious in implicit-feedback settings, where data sparsity further increases the loss of useful signals caused by privacy perturbation. To solve this problem, we propose CAT-LDP, a cloud-local collaborative recommendation framework under local differential privacy constraints. CAT-LDP combines a hierarchical taxonomy tree with an adaptive privacy budget allocation strategy to keep more useful signals in users' active categories while protecting user privacy. Specifically, users upload perturbed category profiles that satisfy LDP. Based on these profiles, the cloud performs coarse-grained candidate generation, and the local device then carries out fine-grained reranking by using unperturbed local history. Experiments on the Amazon Video Games dataset show that CAT-LDP consistently outperforms its fixed-budget ablation variant and representative baselines on HR@K and NDCG@K under different privacy budgets. The results show that combining category-space modeling with cloud-local task decoupling can effectively reduce noise amplification in long-tail sparse settings and provide a better balance between privacy and utility for implicit-feedback recommendation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.05034v1">Faster Learning under Relaxed Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> 
  <p><b>Published on:</b> 2026-09-04T11:55:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Cristina Butucea, Huiyun Tang, Marie-Luce Taupin</p>
    <p><b>Summary:</b> We consider density estimation under the relaxed local differential privacy condition that the privatized distributions are $α$-close in total variation distance. We show that adding independent noise with a convenient symmetrized Gamma distribution to each sensitive observation attains the $α$-TV-LDP. We prove that the deconvolution estimator of $r$-Sobolev smooth functions attains the pointwise rate $(nα)^{-\frac{2r-1}{2r}}$ up to log factors which is faster than $(nα^2)^{-\frac{2r-1}{2r+1}}$ under the classical $α$-LDP and closer to the nonprivate minimax rate $n^{-\frac{2r-1}{2r}}$. Next, we use a Goldenshluger-Lepski procedure to build a free of the smoothness adaptive procedure and show optimality of our rates in the convolution model of our privatisation scheme. We illustrate the benefits of this simple privacy mechanism by implementing a neural network estimator which does not need to add more noise in the optimization steps. Numerical results show significant improvement of the estimation rate over the Laplace and the private-SGD mechanisms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.04592v1">Hidden In Plain Gaze: Gaze Representations as Privacy Controls for Utility and Re-identification Risk in XR</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-04T00:47:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Cory Ilo, Brendan-David John, Doug A. Bowman</p>
    <p><b>Summary:</b> Intelligent extended reality (XR) systems increasingly use eye and head tracking to infer user intent, task, and attention, but the same signals can also reveal biometric identity. We study whether gaze data representation choice can serve as a lightweight privacy control at feature extraction, before adding perturbation or formal privacy mechanisms. Using the egocentric HoloAssist dataset, we compare three gaze representations under matched model capacity: raw gaze, spatial attention heatmaps, and engineered eye-movement features. We evaluate each representation on action recognition as task utility and closed-set user re-identification as privacy leakage. Representation choice substantially changes the privacy-utility tradeoff. Engineered features retain roughly 85% of raw gaze's action-recognition accuracy while reducing re-identification by about an order of magnitude, to roughly four times the chance rate across 206 identities. This reduction attenuates rather than eliminates identity leakage, and the differences across representations show that abstraction alone does not guarantee privacy. Engineered features expose interpretable and auditable structure, giving designers a transparent privacy lever that complements mechanisms such as differential privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.04382v1">Privacy Failure in Split-LLM Training, The Returned Gradient Nullifies the Decoys</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-03T18:43:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Georgios Politis, Evangelos Pappas</p>
    <p><b>Summary:</b> We present a systems-security case study of a two-node split-LLM training system whose privacy evaluation passed while leaving an observable channel untested. The Trusted Local Node (TLN) sends protected activations to the Untrusted Cloud Node (UCN), the UCN returns its output, and TLN, holding the private loss, returns the output gradient. The frame the UCN receives mixes real rows with decoys, and the loss ignores the decoys. Their gradients are exactly zero, so the pattern of zeros reveals which rows were real. We measure it with a protocol fixed in advance: a leak injected at known strength to prove the instrument can see one, a shuffled-label control to prove it does not report absent leaks, and a threshold set before the runs. Across nine seeds, the zeros identified the real rows on every frame, 4,096 of 4,096 per run. An attack on the frame contents recovered about one extra token per hundred over a constant-guess baseline (+0.65 to +1.50 percentage points); the shuffled controls recovered nothing. A second set of runs repeated this on a configuration that keeps model quality within budget, so the finding is not confined to a setting nobody would deploy. On both datasets, every such run passed the forward-channel privacy check and the quality check, yet failed that same check once the returned gradient was included. Clipping and noising each row of the gradient closed the leak for about 0.01 nats of held-out cross-entropy. The system is not thereby safe: five classes of attack, including those accumulating observations across training steps, were never measured.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.03659v1">Security and Privacy in the Musical Metaverse: Threat Analysis and Design Implications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-03T10:56:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Luca Turchet, Michał Kłosinski</p>
    <p><b>Summary:</b> The Musical Metaverse (MM) introduces immersive, real-time environments for collaborative musical interaction, characterized by ultra-low-latency constraints, continuous multimodal data streams, and heterogeneous devices. These properties create a distinctive security and privacy landscape that differs significantly from conventional XR or multimedia systems. This paper presents a multi-layer threat analysis of MM ecosystems, identifying key assets including live musical content, expressive interaction data, identity and session metadata, and intellectual property. Threats are analyzed across network, application, data/AI, device, intellectual property rights, and social layers, with particular attention to risks arising from expressive and neurophysiological data, which enable inference, re-identification, and potential privacy violations. We describe a stakeholder-driven survey involving 14 participants from 13 organizations, revealing that neurophysiological data leakage and real-time stream disruption are perceived as the most critical risks, followed by intellectual property infringement and avatar impersonation. We further evaluate the suitability of existing security protocols under strict latency constraints, showing that conventional approaches such as TLS over TCP are often incompatible with real-time musical interaction, while lightweight, stream-oriented mechanisms (e.g., SRTP, DTLS) provide a more suitable balance between security and performance. Based on these findings, we derive a set of design guidelines for MM systems, emphasizing latency-aware security, differentiation of interaction paths, data minimization, and edge-centric processing. The results support a security-by-design approach that enables trust and compliance without compromising real-time performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.03615v1">Auditing Patient Privacy in Medical Generative Models: Scalable Memorization Detection with DeepSSIM++</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-09-03T09:59:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Antonio Scardace, Francesco Guarnera, Sebastiano Battiato, Daniele Ravì</p>
    <p><b>Summary:</b> While deep generative models offer new opportunities for medical image synthesis and data sharing, their ability to memorize and reproduce training samples raises serious concerns about patient confidentiality. Detecting such memorization at scale remains challenging: traditional pixel-based metrics are sensitive to generation artifacts, whereas generic embedding-based metrics often lack the anatomical sensitivity required for medical data. To address this challenge, we introduce DeepSSIM++, a self-supervised similarity metric for scalable memorization auditing in medical generative models. By leveraging multi-scale feature aggregation and anatomy-preserving augmentations, DeepSSIM++ learns an embedding space where cosine similarity approximates the Structural Similarity Index (SSIM), eliminating the need for exact pixel-level registration. Compared with state-of-the-art baselines, DeepSSIM++ achieves an average Macro F1 improvement of 33 percentage points under ideal alignment and 46 percentage points under realistic spatial and intensity perturbations. Furthermore, it accelerates large-scale similarity computation by several orders of magnitude compared with analytical SSIM. By combining anatomical sensitivity and computational efficiency, DeepSSIM++ provides an open-source tool for scalable memorization auditing in medical generative AI. Code and data are publicly available at: https://github.com/brAIn-science/DeepSSIM.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.03420v1">Privacy, Robustness, and Fairness Trade-offs in Federated Intrusion Detection: Geometric Indistinguishability at the Aggregation Interface</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-03T06:27:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Adrita Rahman Tory, ABM Shawkat Ali, Md Abu Layek, Khondokar Fida Hasan</p>
    <p><b>Summary:</b> Federated learning enables privacy-conscious collaboration for network intrusion detection without centralizing sensitive traffic data, yet its deployment in operational environments must simultaneously satisfy three competing requirements: formal differential privacy guaranties, tolerance to Byzantine-adversarial participants, and reliable detection coverage across severely imbalanced attack categories. Existing literature treats these properties as independently composable, an assumption that this paper challenges both theoretically and empirically. In this paper, we study how these requirements interact in class-imbalanced federated NIDS and introduce geometric indistinguishability as a conceptual lens for a regime in which privacy-induced dispersion in client updates can make minority-class signals harder for robust aggregation to preserve. Using UNSW-NB15 as a case study, we evaluate DP-SGD combined with coordinate-wise median under label-flip and model-poisoning attacks, with threat coverage assessed across attack categories. Our results provide initial evidence that the joint use of privacy noise and robust aggregation can disproportionately degrade detection of rare attacks relative to majority classes. We also show that part of the observed collapse under strong privacy can arise from training miscalibration, while a residual performance floor may remain for ultra-rare categories even after epsilon-dependent tuning. These findings motivate studying privacy, robustness, and rare-attack coverage jointly rather than as independently composable properties, and suggest that aggregation-aware modeling and sample-aware evaluation are promising directions for trustworthy federated NIDS.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.03245v1">A Joint Power-Privacy Control Framework for Decentralized Learning over Heterogeneous Wireless Multicasting Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-09-03T00:56:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Amir Ziaeddini, Yauhen Yakimenka, Joerg Kliewer</p>
    <p><b>Summary:</b> In this paper, we propose a decentralized learning framework that incorporates both power control and privacy guarantees. Specifically, we enable a set of clients in a wireless multicast network to jointly train a common model while maintaining a prescribed per-iteration maximum privacy leakage level. The communication network is represented by a rowstochastic adjacency matrix, allowing us to capture asymmetric channel gains as well as heterogeneous maximum transmit power levels. Differential privacy is enforced through an explicit powersplitting strategy that allocates each node's limited maximum transmit power between model coefficients and injected Gaussian noise, thereby jointly controlling learning performance and privacy leakage. We further prove that the proposed algorithm achieves a cumulative regret bound of O(logT), whereTdenotes the time horizon. To evaluate the practical performance of our approach, we perform comprehensive experiments on the CIFAR-10 dataset under both IID and non-IID data distributions, considering different privacy levels, diverse numbers of clients, and various graph topologies. The results demonstrate strong performance across the considered settings and improved performance over existing methods, highlighting the effectiveness of the proposed algorithm under realistic wireless communication constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.03055v1">Seeing Less Is Not Seeing Safely: Privacy Leakage from Task-Scoped Robot Perception Exports</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-02T18:29:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuqiao Xu, Erman Ayday</p>
    <p><b>Summary:</b> Domestic robots rely on rich perception to operate in private homes, but privacy risk persists even when raw sensor data remain local. Structured representations exported to downstream planners, cloud services, logs, or learning pipelines can still reveal household information through semantics, geometry, spatial structure, and task targets. We introduce Task-Functional Perception Distillation (TFPD), a task-scoped representation-export framework that keeps rich perception local and profiles downstream exports according to task utility, direct exposure, and multiple residual inference risks. Using 120 AI2-THOR scenes with scene-disjoint train/validation/test splits, frozen attacker selection, and representation-aware held-out attacks, we evaluate navigation, collision checking, and object-goal execution. Three navigation exports achieve identical success (1.000) and mean path ratio (0.898), yet representation-level linkability ranges from 0.532 to 0.970. Replacing an explicit target label with a target region reduces target-category macro-F1 from 1.000 to 0.077 while preserving success at 0.995, while geometric coarsening reduces object-category macro-F1 from 0.704 to 0.556 at a measurable collision-utility cost. A ProcTHOR replication preserves the navigation task-equivalence/privacy-inequivalence finding while changing the relative ordering of normalized and topological exports. These results show that neither field removal nor stronger abstraction induces a universal privacy ordering and motivate task-specific, multi-risk evaluation of the complete public representation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.02700v1">The PIONEER Project: A PrIvacy companion for mOtivatioN and knowlEdge transfER</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-09-02T15:06:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Simon Althaus, Nina Gerber, Sara Hahn, Andreas Heinemann, Angela Menig, Max Mülhäuser, Christian Reuter, Ephraim Zimmer</p>
    <p><b>Summary:</b> Remaining control over their private data is one of the key challenges in this century for users. We know from prior work that users are often neither in a position to fully grasp the content of the usually complicated texts, nor are they motivated to spend the time necessary to do so. We report on the progress made by the PIONEER project on a privacy support tool that combines knowledge transfer and persuasive elements to increase users' privacy awareness and motivation; thus empowering them to more privacy sovereignty. Throughout the research and design process, we consider user group specifics that may result in different requirements, e.g., for children, adolescents, parents, or elderly people. We further target sustainable behavior change by addressing different states of change, precisely: spark initial motivation, facilitate the creation of new habits, and encourage habituation of these habits in the long term (volition). Finally, we provide a privacy support tool demonstrator that can be utilized for research and education purposes, e.g., in school contexts.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.02495v1">Big data, differential privacy, and national statistical organisations</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-09-02T12:01:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> James Bailie</p>
    <p><b>Summary:</b> Differential privacy (DP) has emerged in the computer science literature as a measure of the impact on an individual's privacy resulting from the publication of a statistical output such as a frequency table. This paper provides an introduction to DP for official statisticians and discuss its relevance, benefits, and challenges from a National Statistical Organisation (NSO) perspective. We motivate our study by examining how privacy is evolving in the era of big data and how this might prompt a shift from traditional statistical disclosure techniques used in official statistics--which are generally applied on a cell-by-cell or table-by-table basis--to formal privacy methods, like DP, which are applied from a perspective encompassing the totality of the outputs generated from a given dataset. We identify an important interplay between DP's holistic privacy risk measure and the difficulty for NSOs in implementing DP, showing that DP's major advantage is also DP's major challenge. This paper provides new work addressing two key DP research areas for NSOs: DP's application to survey data and its incorporation within the Five Safes framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.02971v2">Privacy Leakage in Federated Learning: Gradient-Based Client Identity Inference and Defenses for Inertial Sensing in Vehicular Edge Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-09-02T09:49:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ali Akarma, Toqeer Ali Syed, Muhammad Khan, Qurat-ul-ain Mastoi, Adeel Ahmad</p>
    <p><b>Summary:</b> As vehicular networks move toward 5G/6G edge intelligence, federated learning (FL) is widely promoted as a privacy-preserving way for vehicles and infrastructure to train shared models without exposing raw sensor data. Yet the updates clients transmit still leak enough information to identify who sent them, which threatens the anonymity that safety-critical V2X applications assume and adds to existing concerns over adversarial ML, model poisoning, and backdoor attacks. We study server-side client identity inference from transmitted weight deltas using inertial (IMU) measurements, evaluated on the UCI Human Activity Recognition (HAR) benchmark as an accessible proxy for the IMU streams produced onboard connected vehicles. Across five attack classifiers and five non-IID partitions, an honest-but-curious server recovers client identity with near-perfect accuracy (approximately 1.000) from undefended updates, confirming a concrete identifiability risk. We then quantify the privacy-utility trade-off of a lightweight clip-then-noise defense by sweeping Gaussian noise (sigma in {0.00, 0.05, 0.10, 0.20, 0.50, 1.00}) at fixed clipping (C=1.0), and report formal (epsilon, delta)-DP budgets through Renyi accounting. A practical region (sigma in [0.1, 0.2]) drives attack accuracy to near-random while costing under 5% relative FL accuracy. Ensemble FL supplies complementary structural privacy with a 1/K anonymity-set bound and no noise penalty. Results are supported by cryptographic (SHA-256) train/evaluation gradient disjointness, three seeds, and a count-normalized attacker-advantage metric. We position HAR explicitly as a proxy and discuss what validation on true vehicular telemetry would require.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.02376v1">Removing Speech, Keeping Activities: A Privacy Firewall for Acoustic Sensing in Assisted Living</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-09-02T09:48:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pavlos Nicolaou, Christos Efstratiou</p>
    <p><b>Summary:</b> Acoustic sensing offers a promising non-intrusive approach for monitoring daily activities of older adults, yet speech privacy concerns remain a critical barrier to real-world deployment. We present a privacy firewall pipeline based on a U-Net encoder-decoder, trained entirely on synthetic data, that removes speech from ambient audio while preserving environmental sounds indicative of daily activities. Activity recognition is performed using VGGish transfer learning with an SVM classifier. Evaluated on the ESC-50 and SINS datasets across multiple speech content levels, the proposed model reduced residual speech to 0% VAD-detectable speech (Silero Voice Activity Detection) under all tested conditions, outperforming Facebook Denoiser (6.55% residual), SepFormer (36.34%) and ConvTasNet (47.21%) on ESC-50 at the 100\% speech level. On ESC-50 at 40% speech level, classification performance recovers to 85% precision and 85% recall after speech removal, compared with 81%/75% before removal and an 84%/83% speech-free baseline. Evaluation on real-world participant home recordings collected with the AudioHive app showed 0% VAD-detectable speech after processing while maintaining 76% precision and recall. The pipeline enables privacy-preserving acoustic sensing without sacrificing activity recognition performance, addressing a key obstacle to the adoption of ambient monitoring in elderly care.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.02323v1">Quantum Workload Privacy Beyond Data Confidentiality</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2026-09-02T09:06:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shaunak Suresh Pawar, Samuel Punch, Krishnendu Guha</p>
    <p><b>Summary:</b> Remote quantum computing exposes a confidentiality gap. Standard privacy mechanisms protect quantum states and outputs, but not the scientific structure of a workload. This work reveals that hardware-aware compilation leaves observable signatures, such as routing overhead, circuit depth, and gate composition, that correlate with hidden modelling choices like partial differential equation boundary conditions, discretisation scale, and molecular geometry. The leakage arises from the mismatch between logical topology and fixed hardware connectivity, forcing problem-dependent SWAP insertion. We formalise this threat as Scientific-Intent Indistinguishability and prove that passive security is asymptotically unachievable under routing-optimal compilation. Experiments on a 156-qubit IBM Heron processor achieve near-perfect classification of boundary regimes and molecular geometries, with leakage generalising across solver families via routing-scaling exponents. Conventional gate-padding fails as a defence, causing fidelity drops without reducing adversarial advantage. Our results show that protecting quantum data alone is insufficient; execution-level confidentiality must become a first-class design requirement.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.02967v1">Privacy-Preserving Topology-Guided Safety for LLM-Based Multi-Agent Systems via Federated Graph Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2026-09-02T07:57:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jinxi Yu, Eric Hanchen Jiang, Levina Li, Dong Liu, Zhi Zhang, Wenxiao Zhao, Yanxuan Yu, Kai-Wei Chang, Ying Nian Wu</p>
    <p><b>Summary:</b> Topology-guided safeguards for LLM-based multi-agent systems (MAS) train a GNN over the inter-agent communication graph to localize risky agents and intervene on the topology---but they assume one operator can pool all labeled traces. Across organizations that assumption breaks: episodes contain private prompts, tool outputs, and proprietary workflows, and no silo alone sees the full attack distribution. We cast privacy-preserving MAS safeguarding as graph federated learning and instantiate FGLGuard: each operator fits an edge-featured graph attention detector on its own judge-labeled episode graphs and shares only model updates. The method couples a proximal local objective for non-IID clients, domain-balanced aggregation, over-refusal-constrained threshold calibration, corroborated upstream scoring, and a guarded rewrite for blocked answers. Federation is not optional: off-the-shelf transfer collapses under distribution shift (AUROC 0.51 to 0.70 only after in-domain retraining), so a deployable guard must adapt on each site's private traces. On Agent-SafetyBench, R-Judge, and AgentDojo, federated FGLGuard exceeds the in-domain centralized ceiling on all three benchmarks without pooling any data---where unsupervised anomaly guards and local-only training fail. One guard federated across four different-domain operators comes within 0.03 AUROC of multi-domain centralization, while any single-domain guard collapses on the others. Live FGLGuard cuts AgentDojo's ground-truth attack-success rate by 43% at near-unguarded utility, zero API cost, and negligible capability loss.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.02055v1">Privacy Washing: Detecting Internal Contradictions in Privacy Policies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-09-02T03:33:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Thomas Brackin</p>
    <p><b>Summary:</b> Privacy policies may contain internal contradictions in which commitments are undermined by practices documented elsewhere in the same policy. We operationalize this phenomenon, privacy washing, through a four-stage pipeline: statement extraction, compatibility filtering and natural language inference screening, multi-model judge verification, and thematic analysis, with contradictions confirmed by majority vote of a three-model LLM panel. Applied to two corpora of website privacy policies, 123 collected in 2026 (OPPT) and 115 collected in 2015 (OPP-115), the pipeline finds the same category patterns recurring across the 11-year gap, with third-party sharing contradictions the majority of confirmed cases in each primary run, consistent with structural factors in policy composition rather than necessarily intentional deception. At least one panel-confirmed contradiction appears in 12.2% of OPPT companies (15/123; 9.8% excluding legacy pairs) and 36.5% of OPP-115 companies (42/115). A stability re-run seven months later, with a fully separated configuration (new extraction models, judges from three Chinese providers absent from both corpora, matched filters, no judge-submission similarity threshold), reproduces the OPPT prevalence under the original protocol (13.0% vs. 12.2%), finds sub-threshold pairs confirm at rates of the same order as those above (raising prevalence to 20.3% and 40.9%), and shows the third-party majority is panel-sensitive while the recurrence of the same category pairs is not. Two caveats govern all figures: panel verdicts are not validated against human expert judgment, so precision is unknown and prevalence figures are lower bounds; and the two primary runs used different filter configurations, so their prevalence difference is not interpretable as a corpus or era effect (the matched re-run reduces the gap to roughly twofold but does not eliminate it).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.01944v1">Privacy Amplification Without Independence: How Far Negative Dependence Carries the Guarantees of Poisson Subsampling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-01T23:20:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xujun Che, Depeng Xu</p>
    <p><b>Summary:</b> Poisson subsampling is the default sampler in differentially private optimization because its independence makes privacy amplification tractable. Practical systems, however, are moving toward structured participation: random allocation (balls-in-bins), per-epoch allocation, random check-ins, schemes widely believed to be at least as private as Poisson subsampling at the matched rate. We isolate the probabilistic mechanism behind this belief and delimit it exactly, for Gaussian mechanisms up to correlated-noise matrix mechanisms.
  (1) If the participation indicator vector is negatively associated (NA), then at every integer Rényi order $α\ge2$, exactly at all finite parameters, its remove-direction Rényi divergence is dominated by that of the marginal-matched independent scheme. For fixed gradient sequences, this extends to the mechanism level whenever the noise strategy's Gram matrix is sign-balanced, an $O(t^2)$-checkable condition.
  (2) The integer-order restriction is essential. For random allocation with $k=1$, we prove a linear law for the Rényi-difference criterion: at large $t$, dominance reverses for every $α<3/2$, including KL divergence, while the crossing order tends to $3/2$ independently of $σ$.
  (3) We also localize the known failure of rate-matched Poisson domination exactly: below $(1-q)^t$, the hockey-stick ordering reverses, so substituting the Poisson pair into composition machinery is unsound. An upper-tail argument yields a finite crossover $γ_\star$, connecting this threshold picture to the Rényi boundary at $3/2$.
  Together, these results give a substitution map for privacy accounting: when Poisson-based computations remain sound for structured participation, where they fail, and what sound alternatives cost in deployment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.02947v1">Privacy-Preserving Heterogeneous Multi-LLM Federated Inference for Cognitive Diagnosis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-01T21:07:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yagna Manasa Boyapati, Chong Yu, Tianyu Jiang, Justin Zhan</p>
    <p><b>Summary:</b> Significant challenges remain in AI-driven educational systems in balancing privacy preservation with accurate cognitive diagnosis. To overcome this, we propose a federated inference framework in which several commercial LLM APIs collaborate without requiring access to raw student data or proprietary model internals. Using multiple federated entities, such as LLaMA-3.3-70B, GPT-4o-mini, and Claude-3-Haiku, our framework builds upon a heterogeneous multi-LLM architecture. The predictions generated by these entities are combined with epsilon-local differential privacy by adding Laplace noise locally to each entity's prediction output before aggregation, while residual-based aggregation mitigates model heterogeneity. Our approach is predicated on an honest-but-curious trust paradigm in which API providers are presumed not to abuse submitted queries, and our differential privacy mechanism shields the published diagnostic results from external inference. We conduct rigorous privacy-utility analysis showing strong privacy guarantees with minimal accuracy loss, and extensive real-world evaluations across three educational benchmarks confirm the framework's practical usability and cross-domain generalizability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.01273v1">Position: Privacy Is a Claim, Not a Property of Synthetic Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-01T14:06:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiachen Zhao, Antonia Januszewicz, Taeho Jung</p>
    <p><b>Summary:</b> Synthetic data has become a common component of machine learning research. While widely adopted, its use in privacy-sensitive contexts has quietly shifted from a claim of residual inference risk under stated assumptions to an appearance-based property inferred from data generation itself. In this position paper, we argue that this shift reflects an implicit change in community standards for what counts as sufficient privacy evidence, rather than a misunderstanding of well-established privacy principles. Drawing on an empirical analysis of recent publications across major ML venues, we show that synthetic data is frequently used in privacy-sensitive settings without explicit articulation of threat models, inference risks, or falsifiable privacy claims. As a result, privacy assurance often remains implicit, difficult to verify, and unevenly distributed, with heightened exposure for rare and minority records. We argue for treating privacy as an explicit, evidence-based scientific claim and recommend that ML venues adopt norms requiring privacy-relevant assertions to be clearly scoped, testable, and contestable.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.01096v2">CRSF: Collusion-Resilient Privacy-Preserving Sensor Fusion with Byzantine-Robust Participation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-01T11:38:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chao Yin, Haihong Tian, Zheng Yang, Haibin Zhang, Fabio Massacci, Chenglu Jin</p>
    <p><b>Summary:</b> Privacy-preserving sensor fusion enables an untrusted server to compute an aggregate result over distributed sensor measurements without learning either individual inputs or the final output. Recent garbled-circuit-based protocols provide an efficient realization of this functionality in a sensor--server--client architecture, but remain vulnerable to sensor--server collusion and Byzantine manipulation of sensor participation. These weaknesses can compromise honest-sensor privacy, incorrectly exclude honest sensors, and corrupt the computed fusion result, thereby undermining the security guarantees expected from the protocol.
  We present CRSF, a collusion-resilient sensor-fusion protocol that addresses these weaknesses while providing privacy, correctness with explicit abort, and liveness. CRSF introduces a Practical Byzantine Fault Tolerance (PBFT)-based agreement phase for sensor submissions and uses server-specific, status-dependent label release with threshold protection of circuit-input labels. This design prevents any Byzantine server from unilaterally manipulating sensor participation and prevents any admissible sensor-server coalition from obtaining enough secret material to compromise honest-sensor privacy.
  We implement CRSF and compare its online execution time with the most relevant state-of-the-art baseline. Our Google Cloud evaluation measures the total computation and communication cost of the online protocol under fault-free and representative faulty executions. Across a range of fault-tolerant fusion circuits and up to 261 sensors, CRSF demonstrates a highly practical trade-off between robust security and protocol performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.00711v1">SoK: Motion Data Privacy in Extended Reality</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-09-01T04:40:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Azim Ibragimov, Alina Vasina, Uliana Polshcha, Eric D. Ragan</p>
    <p><b>Summary:</b> Extended Reality (XR) provides immersive, interactive 3D experiences. To enable these experiences, the devices must track user motion so the system can respond to actions such as grabbing, looking at, or moving an object. However, motion tracking has raised privacy concerns since it records a person's motion patterns. These motion patterns have been studied extensively across various fields (i.e., gait identification and profiling) and have been shown to reveal sensitive information. With the adoption of XR, these patterns became easier to record and obtain than ever. This creates a fundamental privacy tension: motion tracking enables core XR functionality yet requires users to compromise their privacy. Prior systematization-of-knowledge (SoK) studies on XR privacy have examined the field broadly, with motion-related research distributed across several privacy domains rather than treated as a distinct area of study. However, XR motion privacy has gained significant momentum since the prior SoK, with the literature nearly quadrupling in size and thereby warranting a dedicated systematization of this topic. This SoK examines 134 relevant papers on privacy concerns in motion patterns recorded by XR headsets, including how adversaries can obtain users' motion patterns, the inferences they can draw from them, and methods for protecting users. Based on this review, we synthesize a taxonomy of motion modalities, representations, and inference risks; develop an XR motion threat model; systematize the attack and defense approaches in the XR motion literature; identify gaps in the literature; and provide guidelines for future studies evaluating motion privacy mechanisms. Together, our SoK clarifies the state of XR motion privacy and provides recommendations for future evaluations.</p>
  </details>
</div>



<h2>2026-08</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.00492v1">The Privacy-Hallucination Tradeoff in Differentially Private Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-08-31T23:39:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Krithika Ramesh, Krishna Pillutla, Danish Pruthi, Anjalie Field</p>
    <p><b>Summary:</b> Both privacy and factual accuracy are paramount in high-stakes domains like healthcare. Concerningly, we uncover and investigate a privacy-hallucination tradeoff in differentially private (DP) language models. First, we empirically show that models pre-trained or fine-tuned with DP tend to produce more hallucinations than non-DP counterparts, with increased severity as the privacy budget grows stricter. Second, we investigate model properties driving this tradeoff, demonstrating that DP mechanisms flatten output distributions, potentially redistributing probability mass toward factually incorrect alternatives. Third, through experiments where we control fact frequency in training data, we characterize how information frequency can reduce hallucination risks in DP models. Overall, our findings underscore the need for more nuanced privacy-preserving interventions that offer rigorous privacy guarantees without compromising factual accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.00390v1">NeuroPriv: Adversarial Representation Learning for Privacy in Wearable EEG Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-31T21:19:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sarmistha Sarna Gomasta, Bhawana Chhaglani, Prashant Shenoy</p>
    <p><b>Summary:</b> Wearable EEG systems may expose sensitive information beyond their intended health function, creating substantial risks to neuroprivacy. In this work, we show that commonly used EEG features can reveal participant identity and demographic attributes in addition to supporting the intended cognitive task. Wearable EEG is increasingly being explored for cognitive monitoring, neurological assessment, and longitudinal digital-health applications, yet many systems assume that transmitting compact spectral or spatial features instead of raw EEG provides sufficient privacy protection. Using EEGMAT as a motivating case study, we find that compact EEG features achieve a balanced accuracy of 0.788 for cognitive-state classification while enabling gender, age, and subject-identity inference with balanced accuracies of 0.858, 0.789, and 0.692, respectively. We further show that privacy-aware representation learning preserves task performance at 0.781 while reducing these inference accuracies to 0.563, 0.467, and 0.206. These findings motivate purpose-limited representations and explicit privacy auditing in wearable neurohealth systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.31138v1">Scale Analysis and Shape Selection for the Generalized Gaussian Mechanism under Approximate Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> 
  <p><b>Published on:</b> 2026-08-31T17:44:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiang Zhang, Mohamedou Ould Haye, Yiqiang Q. Zhao</p>
    <p><b>Summary:</b> Differential privacy provides a rigorous framework for protecting private information, typically achieved by adding random noise to query results. The generalized Gaussian family is a flexible class of additive noise distributions indexed by the shape parameter $p$ and includes the Laplace and Gaussian distributions as special cases $p=1$ and $p=2$, respectively. This paper studies the privacy-feasible scale estimation and the shape parameter selection of the generalized Gaussian mechanism (GGM) under $(\varepsilon,δ)$-differential privacy. For a given sensitivity vector $Δ$ and $p\in[1,\infty]$, let $b(p)$ denote the smallest value of the scale parameter for which the mechanism satisfies this privacy requirement. In the one-dimensional case, $b(p)$ can be implicitly characterized by a system of equations. For vector-valued queries, we construct a computable upper approximation of $b(p)$ that preserves the privacy guarantee. Shapes are compared under a scale-homogeneous utility criterion, with the $m$-th absolute moment as the main example. We develop an interval-wise shape search algorithm with an approximation guarantee that can be made arbitrarily precise. We also establish the invariance of the optimal shape under rescaling of the sensitivity vector and characterize its limiting behaviour under high privacy limits. Computational experiments show that optimizing shape parameters can improve utility by reducing the variance of each coordinate by 5% to 20% across a variety of cases, with some cases showing even greater reductions, while maintaining the same level of privacy protection. Task-specific experiments further show that shape optimization can improve task-level utility, reduce attacker success, or achieve both.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.30473v1">Bounds on the Posterior-to-Prior Ratios for Inclusion Belief under Bounded Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-31T09:01:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jan Reiter Sørensen, Heidi Søgaard Christensen, Rasmus Rask Kragh Jørgensen, Martin Bøgsted</p>
    <p><b>Summary:</b> Differential privacy has become the standard for generating privacy-protected data releases. However, differential privacy does not translate intuitively to disclosure risk. In particular, it remains unclear how much an adversary's belief about an individual's inclusion in a dataset can change after observing a protected release. To address this question, we derive upper and lower bounds on the posterior-to-prior ratios of inclusion beliefs under bounded probabilistic and approximate differential privacy. By assuming a worst-case adversary with all-but-one auxiliary information, i.e., knowledge of all except for one of the participants in a dataset, we obtain bounds that apply to any adversary. Because these bounds may fail with non-zero probability, we study the corresponding failure probability for the Gaussian mechanism. We derive a theoretical upper limit on this probability and compare it with Monte Carlo estimates across a wide range of parameter settings. The observed failure rate is several orders of magnitude smaller than its theoretical upper limit, indicating that the latter is highly conservative. These findings suggest that the inferential privacy guarantees provided by differentially private mechanisms may be substantially stronger in practice than what is implied by the theoretical upper limit.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.30141v1">Balancing Privacy, Utility, and Safety in LLM Alignment through Preference Optimization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-31T01:46:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dishu Yang, Jingjing Liu, Jize Li</p>
    <p><b>Summary:</b> Preference optimization is widely used to align large language models with human preferences, but preference-data composition may also influence privacy-relevant memorization. We examine whether adding synthetic privacy-preference pairs to Direct Preference Optimization (DPO) is associated with lower canary-based memorization signals without modifying the objective or introducing a formal privacy mechanism. We propose Privacy-Pressure Preference Mixing (P3M), a data-composition protocol that varies the amount of privacy-preference data while keeping helpfulness and harmlessness preference data fixed. We evaluate a non-privacy Baseline and privacy-mixing ratios of 0.5, 1.0, and 2.0 using Gemma 3 270M-IT across five random seeds and validate the same four conditions using 4-bit-quantized Gemma 2 2B-IT across three seeds. Overall, under the tested conditions, privacy-preference mixing is associated with lower mean canary suffix log-likelihood proxy values across both model settings and lower aggregate membership-inference attack performance relative to the Baseline in the mixed-source 2B evaluation. Specifically, across the privacy-aware 2B configurations, the mean area under the receiver operating characteristic curve (AUROC) ranges from 0.596 to 0.629, and the mean area under the precision-recall curve (AUPRC) ranges from 0.541 to 0.575, compared with 0.804 and 0.790, respectively, for the Baseline. However, the reduction in membership distinguishability does not hold uniformly across data sources. Moreover, the relationship between the privacy ratio and harmlessness preference accuracy varies by model setting, whereas helpfulness preference accuracy remains broadly stable. These findings suggest that P3M should be viewed as a lightweight empirical protocol for examining privacy-utility-safety trade-offs rather than as a formal privacy guarantee or a defense against extraction attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.29674v1">Creation begins with understanding: LLMs as strategy designers for privacy-preserving tabular data synthesis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-30T09:16:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jinmeng Li, Quan Zhang, Hangting Ye, He Zhao, Firas Laakom, Dandan Guo, Jürgen Schmidhuber</p>
    <p><b>Summary:</b> Sharing tabular data in high-stakes domains is constrained by privacy regulations. Synthetic data offer a promising alternative, but deep generative models are costly to train and difficult to audit, while LLM-based methods often serialize records as text, obscuring tabular structure and exposing sensitive data. We introduce Tabular Synthesis Strategy Designer (TabSSD), which uses an LLM to design synthesis procedures rather than directly generate records. TabSSD provides the LLM with tree-derived summaries of variable dependence rather than raw records, which produces Python programs for local execution and evaluation. Across twelve datasets, TabSSD strikes a favourable balance among statistical fidelity, predictive utility, and empirical privacy risk, achieving the best average rank across six metrics among ten methods. Moreover, it substantially reduces local computation and token consumption relative to the compared methods. By enabling human-guided refinement and eliminating user-side model tuning, TabSSD lowers the expertise and infrastructure barriers to transparent tabular data synthesis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.29111v1">Auditing and Mitigating Privacy Leakage in Cloud-Edge Collaborative Decoding</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-08-29T07:40:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kejia Zhang, Tianyuan Zou, Zixuan GU, Yang Liu</p>
    <p><b>Summary:</b> Applications such as personalized assistance and proprietary document analysis require large language models (LLMs) to generate outputs from private data. Yet powerful LLMs typically cannot be deployed on the resource-constrained devices where private data resides, and uploading private data to cloud-hosted LLMs exposes sensitive information. Recent work addresses this tension with a cloud-edge collaborative decoding paradigm, where private data are kept on the edge with a small language model (SLM) producing next-token distributions, which are fused with predictions from a cloud LLM operating solely on public data. In this paper, we systematically analyze the privacy risks of such a paradigm with a novel evaluation framework using constructed QA datasets, which show that such collaboration can expose substantial private-context information. To address such privacy leakage, we propose CoVeil, a defense mechanism which dynamically optimizes transmitted signals to suppress leakage during decoding time while preserving the collaborative quality. Extensive evaluations demonstrate that CoVeil consistently improves the privacy-utility trade-off over existing baselines by reducing data leakage by up to 87.2%, with minimal accuracy loss.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.28950v2">The Web-CLI: Verifiable Privacy for Tools, Models, and Inference Engines in the Browser</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2026-08-28T23:40:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tejaswi Gowda</p>
    <p><b>Summary:</b> We introduce the Web-CLI, a novel application architecture deploying powerful computational capabilities (command-line tools compiled to WebAssembly, models run through client-side inference runtimes, and GPU-accelerated engines) as zero-install, offline-capable browser applications that preserve full underlying capability. Unlike web-based alternatives that require server-side processing and expose user data to third parties, Web-CLI applications execute entirely on the client, providing a verifiable privacy guarantee by architecture rather than policy. We define the pattern and its four properties: fidelity, progressive disclosure, offline-first, and zero egress. We present four reference implementations across distinct domains: ffmpeg-webCLI, a browser-based video editor built on FFmpeg; whisper-webCLI, speech transcription via Transformers.js; chat-webCLI, WebLLM-based language model inference; and 3mf-webCLI, a deterministic tool segmenting 3D models into multi-material files for physical 3D printing. Together they demonstrate that the pattern generalizes across deterministic media processing, neural speech recognition, LLM inference, and geometry processing with a physical output, and we outline how it extends to AI-native interfaces in which a local language model becomes the command surface itself. We further report early, anecdotal signs of independent reuse by third-party tools, suggesting the pattern generalizes beyond its reference implementations. We evaluate the primary implementation against native FFmpeg on performance and feature parity, and argue that progressive disclosure lowers the barrier for non-technical users. We argue that for applications processing sensitive user data (medical, legal, journalistic, or personal), the Web-CLI should be the default architecture, as it makes data locality an independently verifiable technical property rather than a policy promise.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.28934v1">Revisiting the Provable-Auditable Privacy Gap of DP-SGD</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-28T23:07:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Saloni Modi, Srivi Balaji, Yusong Zhu, Gautam Kamath, Kevin Tian</p>
    <p><b>Summary:</b> Differential privacy (DP) has traditionally been used to provide theoretical upper bounds on an algorithm's stability to changing its training data. In modern private machine learning applications, achieving strong tradeoffs between utility and theoretical privacy is challenging, and thus one may optimistically hope that existing theoretical privacy analyses are loose. Recent work on privacy auditing has adopted a dual viewpoint, instead lower bounding the true privacy of an algorithm by constructing empirical distinguishing events. The auditing literature has thus far yielded a pessimistic outlook on the looseness of theoretical privacy bounds for DP-SGD, the de facto private training method in modern ML, as nearly-matching empirical lower bounds have been achieved under various threat models [NHSBTJCT23, AC24, CBP25].
  In this work, we propose the empirical privacy lower bound of an algorithm as a concrete metric to optimize for, complementary to the theoretical upper bound. We give a lightweight defense framework that generically augments optimization methods in the ML pipeline to have significantly-improved empirical privacy on standard benchmarks. Moreover, we show that our framework comes at no theoretical privacy cost when augmenting DP-SGD, unlike previously-proposed defenses against membership inference attacks. We evaluate our defense against a broad range of audit constructions, models, and datasets to demonstrate its flexibility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.28198v2">Performative Privacy: When Differential Privacy Maximizes Utility</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> 
  <p><b>Published on:</b> 2026-08-28T11:13:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Uddalak Mukherjee, Edwige Cyffers, Yann Chevaleyre</p>
    <p><b>Summary:</b> Privacy-preserving learning is often motivated by the idea that protecting users' data can preserve trust and thus participation, improving utility in the long term. However, this claim has not been formalized so far. In parallel, performative learning provides a framework for studying learning systems whose deployment affects the data they later observe. In this work, we bring these two perspectives together and introduce performative privacy, where data leakage reduces future participation. We study a simple model where agents repeatedly contribute data for mean estimation but may leave the system when their data is leaked. Privacy is implemented through differentially private mechanisms, creating a trade-off between estimation noise and future participation. We show, through a theoretical study of the dynamics and numerical experiments, that a finite privacy budget can outperform non-private estimation in the long term when the feedback loop between leakage and participation is sufficiently strong. This provides first evidence that differential privacy can be optimal not only as a protection mechanism, but also from the perspective of long-term utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.27954v2">Not to Break, but to Attest: Adversarial Probes for Privacy-Preserving LLM Verification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-28T05:51:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Cameron Wilding, Mina Shaker, Fatemeh Ganji</p>
    <p><b>Summary:</b> Post-deployment changes to large language models can alter behavior while leaving routine outputs largely unchanged, creating a challenge for AI governance when model weights are proprietary. We present a privacy-preserving zk-SNARK-based audit framework that searches for probes designed in the spirit of adversarial examples to amplify logit drift between an approved model and a modified deployment. Our framework explores complementary probe families under different access models. Token-based probes operate in a black-box setting and require only the input interface, tokenizer, and vocabulary. Embedding-based probes require gray-box access to the embedding interface. Stress probes rely on additional interface capabilities but do not require full white-box access to model weights or architecture. This range allows probe selection to balance sensitivity, access requirements, and deployment cost. We evaluate probe constructions across LLM architectures, model-tampering scenarios representative of post-deployment attacks, and GPU platforms. Importantly, our experimental results demonstrate that token-based probes consistently deliver the strongest mean sensitivity across models and GPU platforms, although operating in a black-box setting. Our Groth16 zk-SNARK workflow remains practical as the probe set scales from 1 to 50, where proving time increases from 1.02 to 1.78 seconds, verification remains near 0.84 seconds, and proof size remains constant.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.27914v1">A User-Centric Context-Aware Permission Governance Framework for Privacy Control in Default Mobile Applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-28T04:41:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Asmau Yetunde Adeniran, Adeniran Kolade Ademuwagun, Fatimah Adamu-Fika, Samaila Musa Abdullahi, Freeman Bitrus, Fortune Daberechi Ifeanyi</p>
    <p><b>Summary:</b> Mobile operating systems provide runtime permission controls intended to improve user control over sensitive data. However, default or pre-installed applications are deeply integrated into the system, may operate with elevated privileges, and are difficult for users to scrutinize. Existing permission models generally grant persistent or temporary access for an application session without distinguishing among individual features, leaving users uncertain about when and why data are accessed. This paper presents a context-sensitive, user-focused permission governance framework for default mobile applications. It introduces a feature-based authorization option, "Allow When Needed," that restricts access to the functionality requiring the data rather than the entire application session. A weighted scoring system estimates the privacy implications of user choices based on permission sensitivity and authorization type. A web-based simulation platform was developed to model 30 realistic permission-request situations across six commonly used default application types and support controlled early-stage evaluation before native implementation. The exploratory assessment combined a cross-sectional survey of 104 respondents examining permission awareness and behavior with formative usability testing involving eight participants interacting with the prototype. Survey findings indicate that users do not consistently examine default-application permissions and prefer contextual explanations before granting access. The results provide preliminary evidence that context-aware permission governance can improve user understanding and decision clarity. This simulation-based study represents an initial step toward evaluating feature-level authorization and privacy-feedback mechanisms before native mobile deployment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.27782v1">Memorization Is Not Extraction: Tight Differential-Privacy Bounds and Audit Blind Spots</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-27T23:28:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xujun Che, Depeng Xu, Shuhan Yuan</p>
    <p><b>Summary:</b> Memorization in large language models is measured through a zoo of definitions whose formal relations are unknown, and differential privacy (DP) is treated as a proxy against all of them at once. We pin down the exact DP constant for the two that carry the practical weight, counterfactual memorization and adaptive extraction, and show that they do not control each other. Under $f$-DP, every adaptive extraction protocol with list budget $m$ succeeds with probability at most $1-f(κ)$ for the oblivious baseline $κ$, and the bound is tight on a dense set of baselines: DP uniformly controls extraction exactly up to a threshold in how well the secret can be guessed a priori. Min-entropy certifies that baseline distribution-free, since $H_\infty\geε\log_2 e+\log_2(m/τ)$ holds extraction below a risk level $τ\le1/2$ under pure $ε$-DP for every prior, and is exact on uniform priors. On the memorization side, $f$-DP caps the counterfactual memorization of any bounded score at an advantage functional $η(f)$, equal to $\tanh(ε/2)$ under pure DP; for $k\ge2$ duplicated copies the naive $ε\mapsto kε$ bound $\tanh(kε/2)$ is unattainable, the exact constant being a closed-form staircase attained by geometric noisy counting. That cap is attained inside the local score class used in practice, and it is there that the two measures separate: one mechanism is memorized yet unextractable, another fully extractable yet exactly invisible to every loss-based score. The two-sided blind spot this opens for loss-based auditing and unlearning verification survives on billion-parameter models: a reserved-trigger release is recovered verbatim from one prompt while the audits practitioners deploy certify it clean.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.27766v1">Revisiting Continuous Noise Sampling for Multi-Party Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-27T22:57:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yucheng Fu, Tianhao Wang</p>
    <p><b>Summary:</b> Combining secure multi-party computation (MPC) with differential privacy (DP) enables multiple parties to release aggregate statistics without a trusted curator, and the core primitive is the protocol to sample noise from a continuous distribution under finite-precision arithmetic. In this paper, we revisit the continuous noise sampling protocols and present several improvements in both security and efficiency.
  We start by identifying a vulnerability in widely used sample-and-scale constructions. We demonstrate that the scaling operation in arithmetic circuits confines the noise to a sparse, publicly known set of values, so that an adversary can observe the released noisy queries and decide which dataset produced them. As concrete demonstrations, we instantiate attacks on two systems employing such ``flawed'' sampling protocols: Orchard (OSDI'20) for DP secure aggregation and DP-BREM$^+$ (USENIX Sec'25) for DP federated learning. We report a near-$100\%$ attack success rate on both systems, under any noise scaler $s\geq 2$ used in practice.
  The leakage we reveal is intrinsic to the scaling operation, and direct repairs either substantially sacrifice utility or add significant precision bits to make the sampling more expensive. To address the security and efficiency issues together, we turn to discrete sampling at the granularity of individual biased bits. We make several optimizations to the sampler and prove its security. Our implementation achieves $4\times \sim 612\times$ speedup over existing secure discrete samplers and orders-of-magnitude speedup over the insecure sample-and-scale paradigm, with negligible utility loss compared to the ideal continuous mechanism.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.27108v1">SecureDrive-FL: Joint Differential Privacy and Gradient-Aware Selective Homomorphic Encryption for Federated Driver Monitoring</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-27T13:24:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Baran Can Gül, Hanuma Siddhartha Tunuguntla, Anjana Arvind Naik, Abhishek Vijay Potekar, Nasser Jazdi, Michael Weyrich</p>
    <p><b>Summary:</b> Federated Learning (FL) enables privacy-aware distributed training, yet gradient updates remain exploitable: Man-in-the-Middle (MitM) interception exposes updates in transit, while model poisoning corrupts global convergence. We first introduce GASHE (Gradient-Aware Selective Homomorphic Encryption), a novel selective encryption strategy that dynamically identifies and encrypts only the gradient components exceeding a DP-calibrated sensitivity threshold, rather than encrypting all parameters uniformly as in static layer-based or full-parameter CKKS schemes. Building on GASHE, we introduce SecureDrive-FL, a federated driver monitoring framework that couples DP-SGD with GASHE to create the first closed-loop DP+HE privacy pipeline: DP-SGD calibration parameters directly derive the GASHE encryption mask, unifying training-time privacy and communication-time confidentiality. Evaluated on a ten-class distracted driver classification task under non-IID federated splits, SecureDrive-FL matches DP-SGD alone's poisoning resistance (73.6% vs. 74.0% accuracy, 3.9% Attack Success Rate for both) while additionally withstanding MitM interception, where DP-SGD alone collapses to near-random accuracy (78.2% vs. 10.4%), all under only approx. 8--10% additional runtime overhead relative to DP-SGD alone---under DP-SGD noise injection with per-round privacy parameter epsilon_0=4.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.27066v1">Beyond Classification: Task-Dependent Learnability under Privacy-Motivated Image Transformations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-27T12:52:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Leon Ranke, Wolfgang Hübner, Ronny Hug, Michael Arens, Jürgen Beyerer</p>
    <p><b>Summary:</b> Privacy-Enhancing Technologies (PETs) in computer vision often rely on noise or image perturbations to protect visual data while securely processing it, creating a trade-off between task performance and protection. This trade-off is commonly evaluated using image classification, which primarily captures semantic separability and remains robust despite significant geometric, spatial layout or local boundary alterations. As a result, it is too simplistic as a proxy for generic vision tasks. Exhaustive downstream-task evaluation, however, is computationally expensive because models must often be trained for each PET transformation and parameter setting. We therefore propose a compute-aware multi-task protocol for evaluating PETs in model training. It combines lightweight proxy tasks that target complementary aspects of visual structure while remaining simple and fast to compute. Across irreversible privacy transformations, key-based block primitives, and learnable image encryption schemes, we demonstrate that PETs with similar classification accuracy can differ substantially on other tasks. The outcomes highlight the need for PET evaluation protocols that move beyond classification-only reporting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.27037v1">Neighborhood Watch: Privacy Risks in Seeded Local Combination Synthetic Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-27T12:22:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hadrien Lautraite, Tristan Allard, Anne-Sophie Charest, Jean-François Rajotte, Sébastien Gambs</p>
    <p><b>Summary:</b> Synthetic data is seen as a promising solution for sharing data in sensitive contexts. However, recent work on privacy attacks have shown that there are still significant residual risks, especially for synthetic data generations methods that are not based on formal approaches such as differential privacy. In this paper, we investigate the privacy risks associated with local combination approaches for generating synthetic data in which synthetic profiles are built by combining real neighbouring profiles. More precisely, we focus on three methods from this family, namely SMOTE, Simulant and Avatar, which have been recently used as a way to share 'anonymised data' in the healthcare domain. In particular, we conduct an extensive privacy analysis through a diverse set of attacks: membership inference, linkage and reconstruction attacks. Our results demonstrate substantial privacy leakage for all three methods, raising serious doubts about whether their outputs should be regarded as anonymous in practice.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.26655v1">When Privacy Hurts Mergeability: Geometry-Aware Model Merging under Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-27T06:08:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jin Liu, Junkang Liu, Ning Xi, Yinbin Miao, Dawei Wei, Ke Cheng, Jianfeng Ma</p>
    <p><b>Summary:</b> Model merging promises to construct a single multi-task model from independently fine-tuned task models without accessing the original task data. This makes it attractive when task data cannot be centralized, but released task models may still leak private fine-tuning data. Differential privacy (DP) provides a principled mechanism for limiting such leakage, yet its effect on model merging remains poorly understood. In this paper, we study the geometry of differentially private model merging and identify two geometric obstacles that make private task models difficult to merge: \emph{local sharpness}, which makes task losses sensitive to the parameter displacement induced by merging, and \emph{reference drift}, which measures the displacement of private task models from the shared pretrained initialization and amplifies cross-task interference. Based on these observations, we propose \textbf{DP-Merging}, a geometry-aware framework that improves the mergeability of differentially private task models. DP-Merging uses a DP-compatible sharpness-aware objective to guide each private task model toward flatter loss regions, and a reference-based alignment regularizer to keep task models close to the shared pretrained initialization. We derive a merge-gap upper bound showing that reducing local curvature and reference drift tightens the bound on the loss increase induced by merging. Experiments on vision and language tasks across multiple privacy budgets show that DP-Merging consistently improves private merged-model performance while preserving the privacy guarantees of the underlying DP fine-tuning procedures.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.26324v1">Privacy Without Regret: Differentially Private Inference-Time Alignment</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-26T18:56:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ishi Jain, Nandini Bhattad, Sayak Ray Chowdhury</p>
    <p><b>Summary:</b> Best-of-N (BoN) sampling is the simplest and most widely deployed inference-time alignment strategy, but it suffers from two distinct problems: reward hacking, in which the selected response exploits errors in the proxy reward model, and the absence of any privacy protection for the sensitive human preference data used to train that reward model. We show that a single intervention-adding calibrated noise to reward scores before selection-resolves both. Our first result, Private Best-of-N (PrivBoN), establishes that Gumbel noise at an appropriate scale simultaneously provides $ε$-differential privacy and implements KL-regularized alignment. Whenever the privacy budget exceeds a critical threshold $ε^*$, the privacy-mandated noise is the regret-optimal regularization, and privacy imposes zero additional alignment cost-matching the information-theoretic skyline of Huang et al. (2025). Because $ε^*$ depends on an unknown coverage coefficient, we introduce Private Inference-Time Pessimism (PrivITP), which combines $χ^2$-regularized rejection sampling with a two-phase Gaussian mechanism. PrivITP achieves ex-post $(ε,δ)$-DP with a privacy cost independent of the number of responses $n$, cleanly decouples the regularization parameter from the privacy parameter, and attains the skyline up to a noise-inflation term. Experiments across several language models, datasets, and reward models confirm our results: PrivBoN and PrivITP are scaling-monotonic (unlike BoN, which degrades past a critical $n$), and PrivITP matches or outperforms PrivBoN at equivalent privacy levels, with the largest gains in the strong-privacy regime.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.25750v1">Toward Interpretable Privacy Guarantees in Face-Swapping Anonymization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-26T12:59:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vishnu Bondalakunta, Arman Zareian Jahromi, Shuangqing Wei, George Amariucai</p>
    <p><b>Summary:</b> Face-swapping has emerged as a promising approach to facial privacy protection, replacing a target individual's appearance with that of a donor while preserving non-facial context. The resulting images visually resemble the donor, and face recognition systems tend to suppress the target's match scores -- ostensibly satisfying privacy requirements. Empirical evaluation across a range of face-swapping models, however, reveals that significant target identity leakage still occurs. This raises a deeper question: why does leakage occur, and can it be predicted? We propose a linear stochastic model that treats face-swappers as transformations on the space of identity embeddings, providing an interpretable account of the leakage mechanism. The model is fit to empirical observations and used to derive testable predictions. The aim is to ground privacy assessments in principled, interpretable analysis, thus making formal privacy guarantees explainable -- and perfectible -- rather than purely observational.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.25727v1">Are LLM-Enhanced GNNs Privacy-Safe?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-26T12:42:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Longzhu He, Zelang Wen, Chaozhuo Li, Sen Su</p>
    <p><b>Summary:</b> Large language models (LLMs) have recently advanced graph neural networks (GNNs) by enriching node representations with semantic information, giving rise to LLM-enhanced GNNs that achieve substantial performance gains. However, their vulnerability to privacy attacks, in which adversaries infer sensitive information from model outputs, remains largely underexplored. To bridge this gap, we present a systematic evaluation of privacy risks in LLM-enhanced GNNs through a unified framework consisting of five stages: (1) dataset preparation, (2) victim model training, (3) privacy attack, (4) risk assessment, and (5) defense analysis. Specifically, we conduct experiments on six real-world text-attributed graph datasets covering diverse domains. We consider six representative privacy attack methods targeting three fundamental threats, namely link, label, and membership inference, and construct 42 victim model configurations by combining multiple LLM-based feature enhancers with representative GNN backbones. Extensive experiments show that, despite their utility improvements, LLM-enhanced GNNs consistently exhibit increased vulnerability to privacy attacks compared to shallow text representation baselines. Further analysis reveals that semantic enrichment amplifies link-, label-, and membership-related signals in the embedding space, making them more exploitable by inference attacks. Finally, we evaluate differential privacy as a defense strategy and show that, while it can partially mitigate privacy risks, it introduces significant utility degradation, highlighting a fundamental privacy-utility trade-off in LLM-enhanced graph learning. Overall, this work provides a comprehensive understanding of privacy risks in LLM-enhanced GNNs and offers practical insights for developing more secure and trustworthy graph learning systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.24847v1">On the privacy cost for dependent Gaussian data: spectral density estimation under local differential privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">
  <p><b>Published on:</b> 2026-08-25T17:34:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yann Issartel, François Roueff</p>
    <p><b>Summary:</b> We study the fundamental problem of estimating the dependence structure of a centered stationary Gaussian process under local differential privacy (LDP). In this setting, the spectral density characterizes the dependence structure of the data and is the quantity to be estimated. Our main contribution is to close the open $α^2$-versus-$α^4$ gap between the previously known lower and upper bounds on the minimax rate. Specifically, we establish a minimax lower bound showing that, over Sobolev-type classes of spectral densities, the effective sample size in the high-privacy regime is $Nα^4$, rather than the usual $Nα^2$ arising for independent observations. This additional privacy cost is caused by the temporal dependence between the observations rather than by their marginal distributions. The proof relies on a contraction bound for privatized dependent Gaussian observations. Our second contribution is a matching upper bound, free of the polylogarithmic losses present in previous work. Rather than applying a generic privatization scheme to classical estimators, we construct a problem-specific procedure attaining the rate identified by our lower bound. Beyond closing the gaps in spectral density estimation, we apply the tools developed for this problem to several related questions. We (i) close the logarithmic gap for fixed-lag autocovariance estimation, (ii) show that the $α^4$ cost arises locally around every spectral density bounded away from zero, and (iii) establish that classical asymptotic equivalence with an independent Gaussian experiment generally fails under LDP.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.24957v1">ToolMinimize: Auditing and Rewriting LLM Agent Tool Calls to Minimize Privacy Exposure</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2026-08-25T03:48:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenbiao Li, Yuqiao Xu</p>
    <p><b>Summary:</b> LLM agents routinely include privacy-sensitive data (PSD) in tool call arguments beyond what the invoked tools require, crossing trust boundaries to third-party services on every invocation. A controlled measurement on three production LLMs (GPT-4o, Claude 3.5 Sonnet, Llama-3.3-70B) shows that 81--88\% of tool calls include unnecessary PSD under default prompts; explicit privacy instructions still leave 36--76\% over-sharing. Existing defenses gate calls (allow/block) or label flows (information-flow control) but cannot \emph{rewrite} argument values, and PII detection tools miss implicit PSD like ``Memorial Sloan Kettering'' (a hospital name that implies a diagnosis). We present \system{}, a middleware that intercepts tool calls and rewrites their arguments to the minimum data necessary for tool functionality, combining schema-aware necessity analysis with four operations: removal, generalization, substitution, and truncation. Live validation on 307 tool calls across the three LLMs above reduces privacy cost by 81.2--92.0\% at 100\% argument-level task validity (TOST equivalence $p{<}0.001$ at $Δ{=}1.0$); on 25 unannotated Model Context Protocol (MCP) schemas, by 79.0\% with no \texttt{minimum\_necessary} metadata. An optional LLM content-necessity layer strips task-irrelevant PSD from otherwise-necessary free-text fields, raising live-LLM reduction to 85.1--95.6\% and author-schema reduction from 71.1\% to 90.9\%. Median latency is 1.77\,ms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.23382v2">Spectrum-Aware Bounds on Invertibility for Privacy-Enhancing Instance Encoding</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-24T15:30:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Seokjin Hwang, Yuting Li, Kiwan Maeng</p>
    <p><b>Summary:</b> Instance encoding is a popular empirical technique for privacy enhancement when sharing data to an untrusted server. It transforms sensitive data through an encoding process before sharing, with the hope that the encoding process retains utility but makes it hard to reconstruct the original data. However, most work offers no theoretical guarantee that the encoding process is actually irreversible. A recent work derived a mean-squared error (MSE) bound limiting any adversary's reconstruction accuracy, offering one of the first theoretical results in this domain. This bound, however, has three critical limitations: it is often too loose, only works with randomized encoders (excluding many deterministic encoders practitioners use), and only bounds MSE. We introduce a family of new bounds that (1) are tighter, (2) applicable even to fully deterministic encoders, and (3) can extend beyond MSE to other norm-based similarity metrics, by properly accounting for the encoder's spectral structure. We evaluate our bounds across a range of encoders, datasets, and attacks, showing they hold consistently and improve upon the existing bound.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.23012v1">Misanthrope: A Privacy-Preserving Keypoint Detector</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-08-24T09:14:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Francesco Vultaggio, Predrag Djindjic, Markus Gerke, Sebastian Tschiatschek, Phillipp Fanta-Jende</p>
    <p><b>Summary:</b> Image matching is a core component of applications such as Simultaneous Localization and Mapping (SLAM), Visual Localization, and Structure from Motion (SfM). However, the local image features central to this task are vulnerable to inversion attacks, which enable adversaries to reconstruct privacy-sensitive scene content from local features. These attacks pose a particular threat in distributed computing scenarios where the pre-computed features leave edge devices to be processed by remote servers. In this work, we introduce Misanthrope, a novel privacy-preserving keypoint detector trained through self-distillation to avoid detecting keypoints on people---a predominant source of privacy-sensitive content in most localization scenarios---thus mitigating inversion attacks at the source rather than through post-hoc obfuscation. We demonstrate how inverted images from traditional feature detection pipelines can be used to detect and re-identify people in the scene, while Misanthrope is able to mitigate these attacks. Furthermore, Misanthrope maintains image matching performance on par with the state of the art and even surpasses it in challenging settings where people act as distractors, such as phototourism and in-the-wild odometry. On the Image Matching Challenge 2021 Phototourism test set, Misanthrope is the top-performing sparse feature extractor in 7 out of 9 scenes. We make our model and its evaluation script available here: https://github.com/fratopa/misanthrope</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.22987v1">The Anonymity Gap: Understanding Real Privacy in Shielded UTXO-based Protocols for DeFi</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-24T08:50:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hanze Guo, Stefanos Chaliasos, Yebo Feng, Jiahua Xu</p>
    <p><b>Summary:</b> Shielded UTXO-based protocols are becoming a core form of privacy infrastructure for DeFi. Unlike mixers that organize privacy mainly around deposits and withdrawals, these protocols allow assets, once inside the shielded pool, to continue moving and being re-spent within the hidden state, and to become public only when users withdraw or interact with public DeFi protocols. Their anonymity is therefore no longer a flat pool-size problem, but a provenance problem that propagates across the note/UTXO, proof, and transaction layers. Yet, a unified analysis framework for this setting is still missing. We propose a layered system model and an analysis pipeline that uses prior history as the temporal baseline, applies cumulative pruning and cross-proof propagation to each proof's Commitment Set, and recursively traces the survivors through historical hidden-state transitions to derive the final transaction-level Anonymity Set Size.
  We evaluate our methodology on the complete on-chain histories of all four Railgun production deployments and five independent Hinkal pools across six EVM chains, analyzing 186,356 unshielding spend transactions. Using only public protocol traces and constraints, our non-heuristic analysis yields mean Anonymity Set Size reductions of 40.1%-59.0% relative to each deployment's temporal baseline; 3,679 transactions retain at most 10 addresses, including 1,228 singletons. Public token constraints are the strongest and most stable source of pruning in both protocols, while the effects of tree number, proof roots, and value constraints vary with protocol design and historical state. Together with representative cases, these results reveal interpretable anonymity-loss patterns and implications for user behavior and future protocol design.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.22645v1">Obscura-PQ: Post-Quantum Privacy-Preserving Protocol for the Algorand Blockchain Using Lattice-Based Linkable Ring Signatures</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-23T23:03:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Navid Azimi</p>
    <p><b>Summary:</b> Public blockchains expose the complete transaction graph, and the privacy protocols deployed to obscure it rely almost exclusively on elliptic-curve cryptography, whose discrete-logarithm foundations fall to Shor's algorithm. Because ledgers are immutable, every anonymity set published today under classical assumptions can be retroactively deanonymized by a future quantum adversary. Transitioning to post-quantum alternatives remains challenging, as strict smart-contract resource limits prohibit native on-chain verification of computationally intensive post-quantum proofs. To address these challenges, we present \emph{Obscura-PQ}, a decentralized, non-custodial post-quantum privacy protocol that verifies natively on the Algorand blockchain. Its core is a setup-free lattice linkable ring signature over the cyclotomic ring $\mathcal{R}_q = \mathbb{Z}_q[X]/(X^{512}+1)$. A deposit is a Ring-SIS binding commitment to a short secret; a withdrawal proves knowledge of a ring opening via an AOS/Borromean-style challenge chain over two response-sharing linear relations with rejection-sampled short responses, while publishing a deterministic Ring-LWE serial number for double-spend detection. We reduce double-spend soundness and linkability to Ring-SIS, theft resistance to Ring-SIS for honestly generated deposits, and anonymity to Ring-LWE and an explicit decisional linking assumption in the classical random-oracle model. To overcome strict on-chain opcode and storage limits, Obscura-PQ evaluates verification relations entirely in the NTT domain. We split forward NTTs across opcode-pooled execution phases and stream oversized proofs through refundable box storage, enabling $O(1)$ membership and double-spend checks. We provide a complete Algorand testnet implementation, demonstrating native on-chain verification of a post-quantum privacy protocol under strict smart-contract limits.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.22185v1">Residual Privacy Budgeting with Weighted Scarcity Allocation for Online Query Answering</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2026-08-23T02:48:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mina Khoshmehr, Fernando Beltran</p>
    <p><b>Summary:</b> In many practical deployments of differential privacy, queries do not arrive all at once. We study online differentially private query answering under a finite zero-concentrated differential privacy (zCDP) contract. In this setting, queries arrive sequentially, carry different accuracy thresholds, and may overlap with information already released. We formulate this setting as residual privacy budgeting: for each arriving query, the mechanism first credits reusable support from previous DP outputs and then spends new budget only on the remaining support required to satisfy the current threshold. The controller separates feasible cases, where the minimal residual support is allocated exactly, from scarcity cases, where a weighted shortfall-conservation optimiser assigns limited support according to query difficulty. We define the weight using the Query Influence Factor (QIF), a diagnostic signal for query difficulty and instability rather than query importance. For scalar Gaussian exact reuse, inverse-variance fusion justifies additive support. We prove zCDP composition, residual minimality, 1-competitiveness against the offline optimum in the feasible regime, and avoidable expenditure for allocators that ignore released history. A scarcity impossibility result shows that no online allocator can guarantee a competitive ratio better than 1/n in threshold satisfaction, contextualising the QIF scarcity layer as a design choice for an inherently hard online problem.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.21773v1">Privacy Preserving Semantic Communications in Wireless Edge Networks with Vision Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2026-08-22T04:42:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haoran Chang, Mingzhe Chen, Qianqian Zhang</p>
    <p><b>Summary:</b> Semantic communication has emerged as a promising paradigm for next-generation wireless systems by transmitting high-level semantic features rather than raw bits. However, collaborative devices and multimodal transmission increase privacy risks because sensitive information may leak through inter-device semantic fusion and cross-modal representations. To address this issue, we propose a privacy-preserving semantic communication framework for wireless edge networks. Leveraging a vision-language model (VLM), the framework extracts textual semantics from images and identifies privacy-sensitive entities using a privacy database maintained only at the edge server. Before image transmission, each device removes the identified private regions while preserving useful semantic content. The server then reconstructs the removed regions from the received masked images using textual embeddings and VLM-based semantic priors. To protect textual information, we design an encrypted semantic-channel transceiver using physical-layer keys generated from reciprocal wireless channels, without pre-shared keys. We also introduce a semantic information bottleneck to suppress redundant information across multiple devices. The framework is evaluated against a strong model-aware adversary that can intercept wireless transmissions and access edge-device model parameters but not server-side data. Simulation results show that the proposed method reduces privacy leakage by more than 50% compared with a semantic communication scheme without privacy protection, while the authorized server achieves a 48% improvement in perceptual reconstruction quality over the adversary. The estimated mutual information between transmitted representations approaches 0 bit, indicating effective suppression of cross-device semantic redundancy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.21209v1">Personalized Privacy Control in LLMs via Attention Head Intervention</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-21T15:22:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Junseok Kim, Nakyeong Yang, Kyomin Jung</p>
    <p><b>Summary:</b> The rise of agentic AI enables LLMs to access diverse user data, raising critical privacy concerns. Prior work on contextual privacy studies whether LLMs regulate information disclosure according to context-dependent norms. However, acceptable disclosure boundaries may vary across users even within the same context. To address this limitation, we introduce \textit{personalized privacy}, which incorporates user-specific disclosure preferences into privacy control. We further present P3Bench~(\textbf{P}ersonalized \textbf{P}rivacy \textbf{P}reservation \textbf{Bench}mark), a novel benchmark extending contextual privacy policies with personalized disclosure policies. Experiments show that prompt-based policies fail to reliably enforce personalized privacy policies, with Qwen2.5-7B and Gemma3-4B showing average policy ignorance ratios of 51.25\% and 74.28\%, respectively. Finally, to address this problem, we propose \textsc{Repair}, a robust inference-time attention head intervention method that adjusts disclosure behavior toward policy-consistent responses. Our method significantly improves adherence to user-specific privacy preferences by reducing cases where the model fails to follow the given policy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.21205v1">Workplace Surveillance and Insider Threat Risk Management: Legal Limits and Privacy Harms</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-21T15:20:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haywood Gelman, John D. Hastings, Suvineetha Herath, Quentin Covert</p>
    <p><b>Summary:</b> Workplace surveillance is used by organizations to protect corporate assets and monitor employee productivity. This research presents two central arguments on workplace surveillance: although surveillance serves legitimate organizational purposes, over-surveillance can violate legal requirements and data privacy principles; and a primary security objective of workplace surveillance is the detection of insider threats (InT). InT are comprised of individuals with authorized resource access whose intentional or unintentional actions may damage or compromise corporate assets. This paper investigates InT personas to understand behavioral and psychological detection criteria. Employee surveillance tools and techniques are reviewed to characterize the employee surveillance landscape. Workplace privacy laws, examples of over-surveillance, and the resulting privacy harms are addressed. The review identifies research gaps related to over-surveillance, including the generation of excessive alerts that may obscure meaningful InT indicators. The paper concludes with recommendations to improve workplace surveillance transparency, implement InT training programs to improve organizational detection capabilities, and tune InT tools to detect relevant psychological and behavioral indicators.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.21064v1">Privacy-Preserving Localization via Transmit Antenna Selection and Permutation</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-08-21T13:07:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yiyang Zhang, Yanmo Hu, Junyuan Gao, Shuowen Zhang, Jiannong Cao, Liang Liu</p>
    <p><b>Summary:</b> Integrated sensing and communication (ISAC) has been identified as one primary usage scenario in the sixth-generation (6G) network. While techniques to preserve information privacy, such as cryptography, have been widely investigated, how to preserve sensing privacy is still an open problem in the literature. This paper makes an early attempt to tackle the above issue. Specifically, we consider a localization system consisting of a multi-antenna transmitter, termed Alice, a single-antenna legitimate receiver, termed Bob, and a single-antenna illegitimate receiver, termed Eve. To allow Bob to estimate Alice's angle-of-departure (AOD) but prevent Eve from performing this task based on Alice's signals, this paper proposes a novel antenna selection and permutation based transmission strategy for Alice. Under this scheme, Alice carefully selects a subset of antennas and permutes their indices to establish a specific pilot-antenna mapping for transmission. Similar to cryptography for information privacy, such a mapping will serve as the secret key to preserve localization privacy. In the special case without noise at Bob and Eve, we manage to find out all the antenna selection and permutation solutions such that with this key (knowledge about the exact pilot-antenna mapping), Bob can uniquely estimate Alice's AOD, while without this key, Eve can estimate multiple AODs of Alice that can lead to its received signals. In the noisy case, numerical results are provided to show that our scheme can confuse Eve to make inaccurate AOD estimation as well.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.21009v1">Dorsal Hand Images for Immersive (XR) and Privacy-preserving Age Assurance and Child Safety</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-08-21T11:54:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Riccardo Bovo, George Loukas, Josh P. Davis</p>
    <p><b>Summary:</b> Ensuring that Extended Reality (XR) environments are age-appropriate is an important regulatory and safety challenge. However, current age assurance operates only at registration and cannot verify the age of the active user during a session. Face-based approaches, the dominant solution in social media and adult platforms, are impractical in XR, because they require removing the headset and taking a self-captured image, often on a mobile app. This both breaks immersion and introduces the privacy risk of sharing face pictures with third parties, which leaves XR platforms without a viable path to continuous, in-session and privacy-preserving age assurance. We propose the dorsal part of the hand as an alternative to the face, by exploiting the egocentric cameras that XR headsets inherently and naturally use to capture gesture interactions. To evaluate this, we collect an age- and sex-stratified, ethnodiverse dataset of 436 participants spanning the minor--adult boundary, captured under unconstrained lighting and orientation conditions. To characterise what is achievable with off-the-shelf methods at the minor--adult boundary, we evaluate standard neural network architectures for age assurance at the legally critical 18-year threshold. Analysis confirms performance is robust to skin-tone variation. On this dataset, the challenge-31 operating point achieves zero minor admission, making the system a viable first-stage filter for age assurance. These findings position dorsal hand morphometrics as an effective and more privacy-preserving biometric modality for in-session age assurance in XR.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.20789v1">Chat First, Worry Later: Understanding Individuals' Privacy Perceptions Using ChatGPT in a Work Context</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-08-21T07:03:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Christoph Nirschl, Magdalena Glas, Gerhard Messmann, Günther Pernul</p>
    <p><b>Summary:</b> Generative Artificial Intelligence (GenAI) tools like ChatGPT, which can generate human-like responses from vast amounts of textual data, are increasingly transforming work routines across various fields, including education, healthcare, and IT. This integration, however, raises privacy concerns and questions the readiness of both environments and individuals. To investigate this issue, we conducted a user study with $N=224$ participants from a range of different employment sectors that have integrated ChatGPT into their work routines. We examined how proficiency in the utilization of ChatGPT, general privacy concerns, and organizational policies for GenAI usage impact users' actual ChatGPT usage and how these factors interact. Our findings reveal organizational policies are significantly positively associated with privacy-related ChatGPT proficiency, however, the overall proficiency is low. Higher privacy concerns were found to negatively influence both the frequency of ChatGPT use and the diversity of its applications, especially among users in organizations without GenAI policies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.20712v1">Privacy-Preserving Object Detection for Vision Transformer-Based Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-08-21T03:40:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Homare Sueyoshi, Kiyoshi Nishikawa, Hitoshi Kiya</p>
    <p><b>Summary:</b> We propose a novel object detection method that enables us to protect sensitive visual information of test images. Previous studies considering visual information protection focus on image classification tasks. This paper proposes an object detection method using perceptual encryption for the first time. The proposed method can achieve almost the same accuracy as that of models without any protection by utilizing the embedding structure of the Vision Transformer (ViT) and a domain adaptation technique with keys. In experiments, the effectiveness of the proposed method is verified in terms of accuracy and visual protection under the use of ViTdet, which is a ViT-based object detection model.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.20554v1">aiXamine: Unified Black-Box Evaluation of Cross-Dimensional Trade-offs in LLM Safety, Security, and Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-20T20:33:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fatih Deniz, Yazan Boshmaf, Dorde Popovic, Issa Khalil</p>
    <p><b>Summary:</b> The critical failure modes in deployed large language models (LLMs) are cross-dimensional: a model can score 99.3 in safety alignment while refusing one in three benign queries, or improve across every capability metric while losing 21 points in privacy. Existing evaluation frameworks that assess safety, security, and privacy independently cannot detect these patterns. We introduce aiXamine, a unified black-box platform that evaluates LLM trustworthiness across safety, security, and privacy as interdependent properties. aiXamine orchestrates 46 tests across nine services through an automated red-teaming pipeline, producing hierarchical risk profiles, from prompt-level diagnostics to cross-service trade-off analytics, that enable reproducible comparison of proprietary and open-weight systems under identical conditions. Applying aiXamine to over 120 LLMs through more than 5,000 test runs, we conduct the largest joint safety, security, and privacy study to date and uncover three cross-dimensional phenomena invisible to single-axis evaluation. First, safety enforcement incurs a quantifiable safety tax: stronger alignment systematically increases over-refusal, forcing providers to choose between protection and utility. Second, privacy is near-orthogonal to other trustworthiness dimensions and not captured by standard alignment. Third, we identify and formally characterize distillation-induced robustness collapse: off-policy distillation without on-policy correction causes entropy collapse, catastrophically destroying robustness (56.9$\to$2.6) on the same base architecture. These findings, compounded by diminishing returns from scale and category-dependent safety behaviors, demonstrate that trustworthiness is inherently multi-dimensional: progress along one axis does not guarantee, and can actively undermine, progress along others, yet current alignment methods treat it as a single objective.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.20118v1">Privacy-Preserving Detection of Rare Disease-Associated Cell Subsets via Secure Multi-Party Computation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-20T14:49:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ş. Selcan Magara, Esther Havemann, Debora Jutz, Ali Burak Ünal, Mete Akgün</p>
    <p><b>Summary:</b> The detection of rare disease-associated cell subsets from high-dimensional single-cell measurements is critical for understanding diseases such as leukaemia and viral infections. CellCnn, a convolutional neural network (CNN) designed for this task, has demonstrated the ability to identify phenotype-associated cell populations at frequencies as low as 0.01\%. Training such models reliably requires patient cohorts that are larger and more diverse than any single institution can typically assemble, and the underlying single-cell data is too sensitive to share across institutional boundaries under existing privacy regulations. We propose a secure multi-party computation (MPC) framework that enables the training and inference of CellCnn entirely on secret-shared data. This ensures that neither the participants nor the computing servers ever observe raw patient data or intermediate values. Evaluated on benchmark single-cell datasets for cytomegalovirus infection (CMV) and acute myeloid leukaemia (AML), our implementation preserves accuracy close to its plaintext counterpart while outperforming the prior privacy-preserving baseline. In contrast to earlier privacy-preserving approaches that removed components such as ReLU activations and bias terms, our method retains these key parts of the CellCnn architecture and supports accurate analysis without exposing raw patient data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.20108v1">A Meta-Study on Replication Papers in Usable Security & Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-20T14:39:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Christian Mack, Benjamin Berens, Hanna Algedri, Tobias Hilt, Daniela Reimer, Peter Mayer, Melanie Volkamer</p>
    <p><b>Summary:</b> The field of usable security and privacy research is a young and expanding field, which is still developing standards for its research, e.g. regarding replications. We used a mixed-method approach, in order to get a better understanding of the current state of replications in the field of usable security and privacy: (1) we examine the Call for Papers of 13 venues spanning security, privacy, and human-computer interaction; (2) we conduct a systematic search for papers reporting replicated user studies published across these venues between 2016 and 2025, yielding 24 relevant publications; (3) we categorized these 24 papers employing the replication taxonomy proposed by Olszewski et al. (2025); (4) we distributed a survey to the authors of these papers to understand their motivations for conducting replications. Our analysis reveals four key insights: (A) Calls for Papers would benefit from clearer guidelines for authors and reviewers regarding replication work; (B) determining what modifications were made relative to the original study proves difficult when reading replication papers; (C) strict exact replications do not exist in our sample. Approximately two-thirds of the 24 studies altered multiple aspects of the original work; (D) temporal and contextual changes affecting results emerged as one of the most frequently cited motivations for replication. Based on these findings, we offer practical recommendations for venues, researchers, and peer reviewers to strengthen replication practices in usable security and privacy research.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.19944v2">A Privacy Budgeting Framework for Online Experimentation</a></h3>
  
  <p><b>Published on:</b> 2026-08-20T12:07:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gilian R. Ponte, Alina Ferecatu</p>
    <p><b>Summary:</b> Firms perform online experiments with multi-armed bandits to personalize what consumers are shown while balancing exploration and exploitation. However, third-parties can infer consumers' underlying segments from observing which banners, ads, or recommendations consumers receive. To control this inference, we propose a privacy risk budget that firms can set ex ante to bound such third party belief updating using differential privacy. To spend this privacy risk budget, we propose two strategies: a constant privacy risk strategy and a dynamic privacy risk strategy that spend privacy risk differently across visitor. We study how privacy risk budgets affect experimentation performance in two applications--website design and a recommendation system--under these strategies. For both strategies, we analytically find privacy risk budgets that optimally balance exploration and exploitation. We then extend the idea of an experiment-level privacy risk budget to a firm-wide privacy risk budget. We apply this firm-wide privacy risk budget in an empirical setting with 78 experiments. We find that the dynamic strategy is particularly valuable in longer and more complex experiments, and that optimizing the allocation of a firm-wide privacy risk budget across experiments substantially improves learning performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.19873v1">Evaluating Smart Home Device User Responses to their (Un)Confirmed Privacy Expectations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-08-20T10:35:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tania Khatun, Mahdieh Sheikh Rezaei, Danny Yuxing Huang, Oded Nov, Reza Ghaiumy Anaraky</p>
    <p><b>Summary:</b> Users of smart home devices are often unaware of how their devices handle personal data. We examine how revealing these data practices influences user trust, satisfaction, and coping behaviors, including decisions to block device communications. Using Expectation-Confirmation Theory, we conducted two complementary studies to balance ecological validity with experimental control. An in-situ field study used network monitoring to reveal actual device traffic, and an online experiment presented simulated reports with manipulated levels of advertising-related communications. Across both studies, when data practices aligned with user expectations, satisfaction increased, strengthening intentions to continue using the device. Defensive responses, however, followed different pathways: satisfaction predicted willingness to block in the in-situ field study, whereas collection concerns were the primary predictor of blocking in the experiment. Together, these findings show how transparency reshapes attitudes and behaviors among existing smart-home users, underscoring the role of expectation confirmation in real-world, continued-use contexts.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.19650v1">Enhancing Privacy in Federated Learning via Dual Obfuscation of Gradients and Training Images</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-20T05:36:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuki Itabashi, Hiroto Sawada, Mare Hirose, Shoko Imaizumi, Hitoshi Kiya</p>
    <p><b>Summary:</b> Federated learning enables collaborative model training while keeping data locally at each client; however, recent studies have shown that training data can be reconstructed from shared model updates. To address this issue, this paper proposes a dual obfuscation method that enhances robustness against image restoration attacks by jointly obfuscating updated information and training images. The proposed method combines a robustness enhancement technique based on random binary weights, which randomly sets a portion of gradient elements to zero, with an image encryption technique. These techniques provide complementary protection by reducing the amount of original gradient information available to an attacker and the visual interpretability of reconstructed images, respectively. Furthermore, the image encryption technique allows independent keys to be used for each client and each image, avoiding explicit key sharing. Experimental results on an image classification task using a Vision Transformer (ViT) show that the proposed method reduces the visual information recovered by Attention Privacy Leakage (APRIL) under the evaluated settings without causing additional degradation in classification performance beyond that caused by image encryption. Although the proposed combination does not provide an absolute security guarantee, the results demonstrate the potential benefit of combining gradient modification and image encryption for privacy-enhanced federated learning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.19649v1">Differential Privacy in Feature Reconstruction Aided Federated Learning for Agent's Semantic Communication Model Update</a></h3>
  
  <p><b>Published on:</b> 2026-08-20T05:35:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yoon Huh, Bumjun Kim, Wan Choi</p>
    <p><b>Summary:</b> This paper proposes a differentially private federated learning (FL) framework built upon an FL algorithm with semantic feature reconstruction (FedSFR) for training semantic communication modules for image transmission. By allowing clients with unfavorable uplink capacity to transmit low-dimensional semantic feature vectors extracted from locally trained joint source-channel coding (JSCC) encoders, FedSFR enhances communication efficiency and training stability under heterogeneous wireless conditions. To protect client privacy, we incorporate the oneshot Laplace mechanism and theoretically demonstrate that feature-based transmission achieves strictly stronger differential privacy (DP) guarantees than gradient-based transmission under an identical communication budget. In addition, a model selection mechanism is introduced to alleviate performance degradation caused by privacy-preserving perturbations. Experimental results on multiple datasets show that the proposed DP-aided FedSFR outperforms DP-enabled FedAvg in training stability and image reconstruction quality in heterogeneous wireless systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.19534v1">AEGIS: Attention-Embedding Gradient Isolation Shield - Triple-Channel Gradient Masking for Privacy-Preserving Federated LLM Fine-Tuning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-20T01:12:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ye Tao, Hong Shen, Hui Tian, Xin Wang, Can Wang</p>
    <p><b>Summary:</b> Gradient inversion attacks recover private training text from gradients shared in federated learning, posing a serious threat to collaborative model training. Through our analysis of transformer gradient structure, we identify three channels through which private token information leaks: the attention output projection gradient exposes a low-rank subspace that encodes input embeddings (Channel 1), the embedding gradient's row-norm sparsity directly reveals which tokens are present (Channel 2), and the MLP expansion gradient carries a recoverable subspace signal analogous to Channel 1 (Channel 3). State-of-the-art attacks exploit these channels analytically to achieve near-exact token recovery in seconds. Existing defences address at most one channel and either degrade model utility or leave the remaining structural signals intact.
  We introduce AEGIS (Attention-Embedding Gradient Isolation Shield), a lightweight defence that closes all three analytical channels with three backward-path operations requiring no architectural changes: freezing attention projection parameters eliminates Channel 1 by construction, calibrated noise injection into the embedding gradient destroys Channel 2's token-presence signal, and analogous per-block noise injection into the MLP expansion gradient masks Channel 3. The same masked gradient drives both the local optimiser step and the server export, so no clean signal is retained on either side.
  Evaluated across 11 models and six datasets, AEGIS reduces token recovery rates to near zero against a range of gradient inversion attacks, both analytical and optimisation-based, while preserving or improving model utility. We provide formal guarantees for Channels 1 and 2 and validate the full defence empirically against adaptive adversaries with complete knowledge of the mechanism.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.19462v1">A Federated Learning Framework for Privacy-Preserving Oral Cancer Screening on Smartphones</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-19T21:33:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lena D. Swamikannan, Akshay Bhagwan Sonawane, Jay S. Patel, C. S. Mani, Lakshmi Narayana, Lakshman Tamil</p>
    <p><b>Summary:</b> Data are the cornerstone of robust AI models. However, in the medical domain, access to reliable data is constrained by regulatory requirements and patient privacy, and clinical oral images are particularly difficult to obtain. Federated learning (FL) mitigates these constraints by enabling collaborative model development across decentralized datasets without centralizing or sharing patient data.
  This work presents a practical FL framework that supports geographically distributed collaboration among AI healthcare researchers and facilitates the development of robust models for oral cancer screening. Client devices were interconnected via Tailscale to provide secure networking and real-time communication. We implemented the FL workflow using the Flower framework for server-side aggregation, while client deployment and orchestration were configured manually; no enterprise FL platforms were used. To support a smartphone-based screening application, we evaluated lightweight, mobile-friendly architectures including MobileNetV2, MobileNetV3Large, and MobileNetV4-Conv-Small (MNv4-Conv-S). Across the global lightweight models aggregated using FedAvg, the MNv4-Conv-S based global model (GM-V4) achieved the best performance, reaching an AUC of 0.929 and an accuracy of 87%</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.19155v1">FedGuard-DC: Privacy-Preserving Federated Load Forecasting and Cyber-Attack Detection for Data-Center Loads in Transmission Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-19T17:40:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Md Kibria Saroare, Md Rubel Ahmed</p>
    <p><b>Summary:</b> The rapid growth of large data-center (DC) loads is creating new challenges for power-system visibility, privacy, and cyber-physical security. System operators need accurate short-term information about these fast-varying loads, while DC operators may avoid sharing raw megawatt measurements because they can reveal sensitive workload and utilization patterns. This paper presents FedGuard-DC, a federated learning (FL) framework for privacy-preserving DC load forecasting and local false-data-injection attack (FDIA) detection. Each DC trains a dual-head model on its own measurements, where a shared encoder supports both a forecasting head and a reconstruction head. A calibrated anomaly score combines forecast residual and reconstruction error to detect corrupted measurements locally. Raw measurements and absolute MW demand remain at each DC, while only model updates are shared with the global controller. Optional differential privacy and robust trimmed-mean aggregation are included to evaluate privacy-utility behavior and poisoned-client resilience. The framework is validated using EMT simulation data from four large DC loads rated between 150 and 350 MW integrated into the IEEE 39-bus New England system. Results show a 0.5 s-ahead normalized forecast RMSE of 0.023-0.038 pu, compared with 0.32-0.34 pu for persistence. FedGuard-DC detects FDIA with ROC-AUC of 0.979, F1 = 0.930, and precision of 0.988, while robust aggregation reduces the poisoned-client RMSE impact from 0.042 to 0.035 pu.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.19006v1">Introducing the Privacy-HSD Trade-off: Hate Speech Detection, but not at the Cost of Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-08-19T15:07:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stephen Meisenbacher, Vlad Garbuz, Chirill Donos, Maxim Dnestreanschii, Gabriel Creanga, Andreea-Elena Bodea, Thomas Lampert, Jana Diesner</p>
    <p><b>Summary:</b> Hate speech is a real and timely threat that affects a large portion of online users, especially youth and minority groups. While building reliable and robust automatic hate speech detection (HSD) systems is paramount, we argue that this must also be balanced with the individual right to privacy. Exploring the intersection of HSD and privacy, we demonstrate that HSD systems might unintentionally achieve performance at the cost of encoding authorship, posing a threat to privacy. Building on these findings, we establish the notion of a privacy-HSD trade-off, which demands a careful balance. We benchmark a series of text privatization methods, as well as our newly proposed domain-specific AgnoSpeech technique, showing that balancing privacy and HSD is difficult but feasible. The findings make a strong case for more research on the trade-offs between privacy and HSD, both of which have tangible implications for the safeguarding of online participation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.18749v1">Geometric Data Perturbation with Noisy-Anchor Alignment for Privacy-Preserving Collaborative Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-19T09:59:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Keiyu Nosaka, Yamato Suetake, Yuichi Takano, Yukihiko Okada, Akiko Yoshise</p>
    <p><b>Summary:</b> Geometric Data Perturbation (GDP) enables one-shot, privacy-preserving collaborative learning: each participant applies a distance-preserving transformation to its private data and uploads only the resulting representation to a central analyst. We study GDP under analyst-participant collusion, in which the analyst combines all uploaded representations with the private data and transformations disclosed by colluding participants to recover a non-colluding participant's private data. Participant-specific independent transformations resist this attack but map participants' data into incompatible representation spaces, degrading downstream model performance. Shared-anchor alignment from Data Collaboration (DC) analysis restores compatibility and improves utility, but we show that disclosing the DC anchor matrix enables exact recovery of non-colluding participants' private data even in the presence of collusion. Adding noise directly to the private-data representations mitigates this vulnerability but substantially reduces utility. We propose adding noise to the anchor representations instead. Each participant independently transforms its private data and the shared anchor matrix, perturbs only the resulting anchor representation, and uploads both representations in a single round. Using the noisy anchor representations, the analyst aligns the private-data representations by solving a Generalized Orthogonal Procrustes Problem. We characterize alignment and recovery errors, specialize a conservative sufficient condition for convergence of the alignment to our setting, and analyze three recovery attacks. Experiments on MNIST and CelebA show that, across the evaluated attacks and deployment settings, anchor noise achieves higher learning accuracy than private-data noise at comparable measured leakage, yielding a more favorable privacy-utility trade-off under the specified collusion model.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.18610v1">Denoising-Aware Inversion: Revealing Privacy Risks in Noise-Protected Text Embeddings</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-19T06:53:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yubo Wang, Shujie Cui, James Bailey, Hongzhi Yin, Wenyu Liang, Min Tang, Shiyue Qin, Weiqing Wang</p>
    <p><b>Summary:</b> Dense text embeddings are widely used in data mining, retrieval, and downstream machine learning systems due to their compact and semantically rich representations, but recent embedding inversion attacks have shown that they can expose substantial information about the original text, leading to serious privacy leakage risks. A common defense is to release perturbed embeddings by adding Gaussian noise, which is simple yet effective against standard inversion attacks and does not significantly degrade embedding utility for downstream tasks. However, it remains unclear whether such noise-protected embeddings are sufficiently safe against adaptive attackers that explicitly account for the perturbation process. In this paper, we study text embedding inversion in a noise-protected setting, where the attacker can observe only noisy embeddings and has no access to clean embedding targets. We first analyze why existing generative inversion methods fail under this setting and identify a "Double Noise Trap", which fundamentally prevents standard generative inversion models from achieving high-quality reconstruction. To address this challenge, we propose DAEI, a denoising-aware embedding inversion pipeline that combines a residual denoising autoencoder with generative text inversion where the denoiser is trained in an unsupervised manner using Stein's unbiased risk estimate to enable denoising from noisy observations alone. Extensive experiments show that DAEI achieves approximately 154\% relative improvement in BLEU over the existing generative inversion baseline, while also improving token-level F1 and ROUGE-L by 32--60\%. The promising inversion performance of DAEI challenges the prevailing assumption that simple Gaussian perturbation is sufficient to prevent sensitive information leakage from embedding representations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.18316v1">A Configurable Privacy-Preserving MRI Processing Workflow Using Deep Learning-Based Brain Extraction and Adaptive Anatomical Preservation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-08-18T20:59:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rayeef Ali Khan, Komal Raj Mahantesh</p>
    <p><b>Summary:</b> Structural Magnetic Resonance Imaging (MRI) is widely used in neuroimaging research and clinical practice, but structural MRI volumes may retain facial and cranial anatomical information that raises privacy concerns. Existing deep learning-based brain extraction methods generally produce a single fixed output, limiting flexibility when different applications require different balances between privacy and anatomical preservation. This paper presents a configurable privacy-preserving MRI processing workflow that extends deep learning-based brain extraction through adaptive anatomical preservation, interactive preservation selection, and integrated quality control. The workflow employs SynthStrip for automated brain extraction, followed by morphological mask expansion to generate configurable shell-based preservation levels. An Interactive Preservation Framework enables users to compare preservation configurations and select an appropriate output, while an integrated Quality Control Framework provides multi-plane visualisation and brain-mask overlay verification. The workflow was implemented in Python using open-source neuroimaging libraries within the Renku reproducible research environment and evaluated using structural T1-weighted MRI data from the publicly available IXI dataset. Experimental results demonstrate anatomically plausible brain extraction and configurable preservation outputs, supported by systematic visual verification. The principal contribution is a modular and reproducible MRI preprocessing framework that enhances deep learning-based brain extraction with configurable anatomical preservation, interactive user-guided processing, and integrated quality control. The workflow provides a practical foundation for privacy-oriented neuroimaging research and collaborative medical image analysis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.18274v1">Model Card for OpenAI Privacy Filter</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-18T19:48:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Charles de Bourcy, Sahra Ghalebikesabi, Avi Schwarzschild, Alex Gorbachev, Mihai Maruseac, Annie Chu, Vol Kyrylov, Tong Mu, Ally Bennett, Andy Nguyen, Casey Meehan, Jessica Gan Lee, Shane Bauer, Harold Nguyen, Rodolpho Eckhardt, Yuqi Liu, Charlie Oxborough, Marco Rougeth, Omar Chedid, Caio Costa, Yash Parikh, Yao Li, Congzheng Song, Om Thakkar, Vinnie Monaco</p>
    <p><b>Summary:</b> OpenAI Privacy Filter is a compact, bidirectional token-classification model for detecting and redacting personally identifiable information (PII) and secrets in unstructured text. The model is derived from an autoregressively pretrained checkpoint and converted into a bidirectional, banded-attention classifier that labels an input sequence in a single forward pass. A constrained Viterbi decoder produces coherent spans across eight privacy categories and exposes configurable operating points for precision-recall tradeoffs. Privacy Filter has 1.5 billion total parameters, 50 million active parameters per token, and a 128,000-token context window. It is designed for efficient local deployment and domain-specific fine-tuning. Privacy Filter is intended as a configurable data-minimization component within layered privacy workflows, not as an anonymization or compliance guarantee.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.17147v2">Picture the Epsilon: Pursuing Identity-Level Privacy Guarantees for Images</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-17T21:30:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arman Zareian Jahromi, Vishnu Bondalakunta, Mohammad Akbar Bin Shah, Naimul Haque, Shuangqing Wei, George T. Amariucai</p>
    <p><b>Summary:</b> Several methods for auditing privacy in embedding spaces report a number called "epsilon." The common name is misleading: one number may be a heuristic score, another may come from a valid population inequality but ignore sampling uncertainty, and a third may be a confidence bound. This paper asks when such a number is evidence about differential privacy. We study four approaches based on Gaussian calibration, marginal kernel-density ratios, maximum mean discrepancy (MMD), and classifier hypothesis tests. The first two are modeling diagnostics. The MMD and classifier approaches use valid population lower bounds, but only the classifier approach is given a separate test set and a finite-sample confidence calculation. To see how these distinctions matter, we build a synthetic benchmark in which the true privacy value is known. It includes pure-DP Laplace mechanisms, approximate-DP Gaussian mechanisms, an exact privacy null, two identity geometries, and three sample sizes. At the null, the Gaussian and kernel-density diagnostics remain large. A direct conversion of an empirical ROC curve often returns infinity even though the AUC is near chance and no threshold separates the samples perfectly. The MMD value increases as the distributions become easier to distinguish, but the sample estimate is small relative to the known reference and is not a lower confidence bound. By contrast, a classifier chosen on development data and evaluated on untouched test data gives simultaneous lower confidence bounds under the stated iid model. We also apply the methods to FaceFusion and InstantID. That case study shows how the methods behave on face data but does not calibrate them because the generators have no known privacy value. The main lesson is that an epsilon-like number is meaningful only together with its assumptions and its finite-sample interpretation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.17145v1">Protocol-Embedded Compliance for Privacy-Preserving, Non-Custodial Digital Payments</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-08-17T21:29:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Santiago De Simone, Geoffrey Goodell, Georgios Samakovitis</p>
    <p><b>Summary:</b> Received wisdom on payments infrastructure strongly supports the custodial, account-based model as a necessity for transaction integrity, auditability and verification; the set of fundamental primitives for regulated digital money exchange, the argument goes, necessitates designated identifiable entities that store and process credentials, perform KYC, and ultimately act as the 'single version of the truth' for compliance remediation and, most important, AML. In this paper, we propose this is not the case, by arguing that non-custodial, cash-like digital assets can embody such capabilities, in an arguably more secure manner.
  To that end, we present a reference architecture and core protocol rules for digital-value-exchange systems that preserve meaningful user privacy while enabling strong auditability. The protocol defines the conditions under which digital asset creation, transfer, and redemption are valid. The architecture specifies the allocation of actors, roles and components through which these rules operate, enabling independent verification of transaction compliance with applicable norms. Building upon the Unforgeable, Stateful, Oblivious (USO) asset model of Goodell et al., regulatory compliance data are embedded directly into the asset state as cryptographically signed attestations issued by independent entities. A transfer is valid only upon satisfaction of applicable compliance predicates and inclusion of the resulting signature within the asset state. Compliance enforcement is thus performed at the protocol level rather than through institutional custody or identity-based account control. We conclude that our proposed model can successfully interface with existing payment systems, making it possible to integrate non-custodial, compliance-verified transactions with legacy financial infrastructure.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.16551v1">What to Remember, What to Reveal: Privacy-Aware Memory for Conversational Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-17T13:23:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenjie Wang, Wenhe Si, Xinyue Xu, Yue Xu</p>
    <p><b>Summary:</b> Long-term memory enables personalized conversational agents to retain user information across sessions. However, existing memory architectures primarily optimize for utility while neglecting the risks of unnecessarily storing and reusing private attributes such as personally identifiable information (PII). Addressing privacy risks in personalized memory is challenging because simply removing sensitive values can undermine system utility. Therefore, privacy protection for memory agents should govern the full life cycle of sensitive values rather than only sanitizing individual records. To address this gap, we introduce Sanitized Privacy-Mapped Memory (SP-Mem), a privacy-aware memory architecture that decouples memory utility from exact private-value exposure. SP-Mem provides a full life-cycle privacy design that identifies and separates sensitive information from raw user inputs, stores sanitized content and exact private values in isolated structures, and selectively retrieves private values based on task requirements and user consent. We further introduce a privacy-aware memory benchmark that jointly evaluates response quality, privacy behavior, and inference cost. Extensive experiments across multiple LLM-based agents show that SP-Mem achieves stronger personalization while reducing unnecessary privacy exposure. Code and data are available at https://github.com/Jensassss/SP-Mem.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.16488v1">Efficient Privacy-Preserving Range Filtered Approximate Nearest Neighbor Search</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2026-08-17T12:28:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haoyu Wang, Yandi Zhang, Jiadong Xie, Yingfan Liu, Hui Li, Jeffrey Xu Yu, Jiangtao Cui</p>
    <p><b>Summary:</b> Range-filtered approximate nearest neighbor search (RFANNS) is an important primitive for vector databases; it retrieves vectors that are similar to a query and satisfy a numerical range predicate, but existing RFANNS indexes expose vectors, attributes, and queries in plaintext. This assumption is unsuitable for outsourced vector databases, where sensitive data and queries must be protected from an honest-but-curious cloud server. To the best of our knowledge, this is the first study that systematically formulates and evaluates privacy-preserving RFANNS over outsourced encrypted vector databases. Our approach separates range localization from encrypted vector search: an authorized user maps the query range to a compact set of nodes in a local N-ary attribute tree, and the server searches only the corresponding proximity graph sub-indices over encrypted vectors. To reduce expensive encrypted comparisons, we use a filter-and-refine pipeline that first retrieves coarse candidates with approximate distance-comparison-preserving encryption and then reranks a small candidate set with exact distance-comparison encryption. We then analyze the computation, storage, communication, and leakage of the protocol. Experiments on four widely used vector datasets show that our method improves the QPS-Recall trade-off over representative secure adaptations of existing RFANNS approaches, scaling effectively to large datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.16461v1">A Human-LLM Teaming Framework for Privacy Risk Analysis: An Illustration with CBDC-Based Welfare Schemes</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computational Engineering, Finance, and Science-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-08-17T11:59:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sourya Joyee De, Abdessamad Imine</p>
    <p><b>Summary:</b> Central Bank Digital Currency (CBDC)-based welfare schemes may be potentially privacy invasive as they process significant volumes of beneficiary personal data and lead to privacy harms such as surveillance, discrimination and stigmatization. Such welfare delivery schemes involve complex digital ecosystems and large number of stakeholders. Consequently, to examine their privacy risks, privacy risk assessments require extensive information gathering and synthesis, complex reasoning, scenario explorations, contextual evaluation and human judgement. Thus, they present ideal scenarios for human-LLM teaming, where effective integration of complementary human and LLM capabilities can yield an outcome far superior to either human-only or LLM-only assessments. In this paper, we propose a first human-LLM teaming framework for the systematic privacy risk analysis methodology called PRIAM. The framework specifies an iterative collaborative process in which the LLM processes large-scale documentary evidence to produce initial outputs, which are then interpreted and evaluated by human experts who direct their further refinement by the LLM and exercise their judgement to finalize the output. We illustrate the framework on the data characterization activity of PRIAM using a CBDC-based welfare scheme use case. The illustration demonstrates that while LLMs generate the initial data categories and assign initial values to data attributes, human experts evaluate and provide feedback to refine them, distinguishing documented evidence from inferences, identifying information gaps, and flagging unsupported or ambiguous outputs. This framework serves as a foundational contribution towards human-AI teaming for privacy risk assessments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.16452v2">Strong Converse Exponents of Quantum Soft Covering and Privacy Amplification</a></h3>
    <img alt="Category Badge" src="https://img.shields.io/badge/Operator Algebras-04E762">
  <p><b>Published on:</b> 2026-08-17T11:54:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shi-Bing Li, Hongsen Qiu, Xinyu Zhang</p>
    <p><b>Summary:</b> We determine the exact strong converse exponent of quantum soft covering under the sandwiched R{é}nyi divergence for all orders $α\in[\frac{1}{2},\infty)$. For $α\in[\frac{1}{2},1)$, the exponent is characterized by the two-parameter club-sandwiched mutual information, whereas for $α\in[1,\infty)$, it is characterized by the order-$α$ sandwiched R{é}nyi mutual information. We also determine the exact strong converse exponent of privacy amplification against quantum side information under the sandwiched R{é}nyi divergence for $α\in(2,\infty)$, expressed in terms of the corresponding order-$α$ sandwiched R{é}nyi conditional entropy. To the best of our knowledge, these results provide the first exact characterization of the strong converse exponent of quantum soft covering and the first precise operational interpretation of the two-parameter club-sandwiched mutual information in the quantum setting. The key ingredient is that we establish the exponential rate of the $K$-functional, which is instrumental in deriving the strong converse exponent of quantum soft covering for $α\in[\frac{1}{2},1)$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.16236v1">A Privacy Study of Sparse Collaborative Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-17T08:14:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maximilian Andreas Hoefler, Karsten Mueller, Wojciech Samek</p>
    <p><b>Summary:</b> Collaborative inference (CI) splits a model between an edge device and a server, whereby the client computes an intermediate activation, transmits it, and the server completes the computation. This raises two concerns, the communication cost of the transmission and the risk that it reveals private information about the input. Recent work reduces this cost by sparsifying activations and entropy-coding the result. Sparsity has also been argued to improve privacy, on the intuition that transmitting fewer values reveals less about the input. We test this claim by decomposing the sparse activation into the retained values and the set of positions they occupy, and by reconstructing inputs from each component in isolation. We find that sparsification reduces the leakage far less than it reduces the transmission cost, and that the remaining risk shifts to the positions, which prior analyses treat as side information for decoding. Across natural-image and face datasets, the positions alone constitute a serious privacy risk, enabling high-fidelity reconstructions and re-identification of individuals. The leakage from the positions persists even when both the transmission cost and the task utility are low. We conclude that the positions of sparse activations should be treated as sensitive transmitted data and audited carefully in the context of collaborative inference. Code is available at https://github.com/an7123/Privacy-Study-Sparse-CI.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.16026v1">SkillWatermark: An Embedded Skill Watermark of Progressive Privacy Inference via Benign Prompts</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-17T02:38:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yu Li, Liqi Zhuang, Dong Wei, Jiwen Luo, Hang Zhang, Meng Zhang, Xiaona Li, Weiqing Huang</p>
    <p><b>Summary:</b> Skills for large language model (LLM) agents have been widely deployed across diverse application domains. However, we observe that these skills generate specific traffic patterns during execution. In this paper, we design a pipeline that generates specific traffic patterns by inserting carefully designed skill descriptions, which we term skill watermarks, so that a passive network attacker can establish a covert channel to encode private information within observable traffic across multiple conversation turns. Specifically, we insert prompt constraint terms, referred to as watermarks, into the original skill descriptions and embed them within multi-turn conversations. The key information in the user's original prompt is thereby triggered by these watermarks, producing clearly observable encodings in the traffic. The adversary need only decode the traffic patterns to recover the encoded information. In particular, our modifications are benign in the sense that they do not directly exfiltrate any private data and do not execute any malicious instructions. Extensive experiments demonstrate that our watermarks produce highly consistent and distinguishable traffic patterns, and that the transformed skills pass existing LLM-based security auditing tools. This study highlights that generating specific traffic patterns can be exploited as a novel attack surface and offers critical insights for future security hardening.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.15506v1">Enhancing Sensing Privacy in ISAC Through Joint Signal and Artificial Noise Beamforming</a></h3>
  
  <p><b>Published on:</b> 2026-08-16T03:19:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ahmad Musallam, Husheng Li</p>
    <p><b>Summary:</b> Integrated sensing and communications (ISAC) is a promising feature in 6G networks. It is envisioned to enhance spectral efficiency and provide sensing and communication services that meet the stringent requirements of future applications. However, it also poses new security and privacy concerns by giving malicious attackers access to new information about the network. In this work, we focus on the sensing privacy of a monostatic ISAC system by investigating the capability of a sensing eavesdropper (EVE) with an unknown location, acting as a passive bistatic radar (PBR) to gain access to user location information. We then propose a joint transmit and artificial noise (AN) beamforming optimization problem to degrade EVE's performance. Finally, we propose an iterative algorithm to solve the proposed optimization problem and evaluate its performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.15276v1">Balancing Privacy and Compliance in DeFi: A Zero-Knowledge-Based Auditable Cross-Chain Framework</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-15T15:19:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Huiheng Li, Kainuo Feng, Jiahao Ding, Ziqi Ma</p>
    <p><b>Summary:</b> With the rise of decentralized finance (DeFi), cross-chain transactions, transfers of assets across different blockchain networks, face a fundamental conflict between user privacy and regulatory compliance. Unlike single-chain systems, cross-chain environments must balance privacy and auditability across heterogeneous architectures. Existing solutions, from transparent ledgers to anonymous cryptocurrencies, fail to reconcile these two requirements, hindering regulatory adoption. This research proposes an auditable cross-chain framework that integrates three building blocks. First, zero-knowledge proofs (ZKPs) verify transaction compliance (e.g., amount non-negativity, signature validity) without revealing transaction details. Second, a light-client mechanism enables trust-minimized cross-chain verification without relying on third-party relayers. Third, a threshold view-key mechanism based on distributed key generation (DKG) ensures that audit access is granted only to authorized entities under legal triggers such as the FATF Travel Rule and MiCA Regulation. For cross-border investigations, the framework adheres to national laws and the EU Directive on Mutual Legal Assistance. This work systematically combines ZKPs, threshold cryptography, and light-client verification into an auditable, privacy-preserving cross-chain protocol. It contributes to Regulatory Technology (RegTech) and provides a viable path toward compliant, interoperable decentralized finance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.14429v1">PriCoRec: A Privacy-Aware Cloud-Device Collaborative Framework for Ad Recommendation under Feature Constraints</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2026-08-14T16:11:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dairui Liu, Zhongyi Lu, Jitao Lu, Aghiles Salah, Mete Sertkan, Roger Zhe Li, Changhong Jin, Barry Smyth, Xingsheng Guo, Ruihai Dong</p>
    <p><b>Summary:</b> Privacy regulations increasingly restrict cloud processing of sensitive user data (e.g., age, gender), hindering traditional cloud-only recommendation models. To mitigate this challenge, we propose a Privacy-aware Collaborative cloud-device ads Recommendation framework (PriCoRec) which personalizes recommendations while keeping sensitive features on-device. While separating recommendation into cloud-based and on-device stages enables privacy-aware deployment, naive splitting suffers from degraded shortlist quality and inefficient on-device inference due to limited private features. We therefore design a collaborative framework that comprises a cloud-based pre-ranking stage using cloud-accessible features, and an on-device ranking stage that locally incorporates highly personalized features. We introduce a diversity regularizer to pre-ranking to improve candidate quality. Moreover, to control device power consumption and computational cost, we incorporate a cloud-guided training mechanism that enhances device model performance while keeping the model lightweight. Experiments demonstrate that the proposed framework maintains strong recommendation performance while keeping sensitive features on-device.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.14176v1">Physics-Bounded mmWave Sensing for Schedulable, Privacy-Preserving Human Pose Estimation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-08-14T10:43:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuntian Zheng, Hongyang He, Jiaqi Li, Xiaoman Lu, Doeon Kim, Jae-Ho Choi, Jin Zeng, Shuai He, Yu Guan</p>
    <p><b>Summary:</b> Millimeter-wave (mmWave) is a promising modality for human pose estimation (HPE) in mobile deployments with strong privacy requirements and limited resources, such as fall detection in bathrooms or activity monitoring in bedrooms, where cameras are inadmissible and computationally demanding processing is infeasible. Although mmWave signals naturally confine human reflections to compact, physically bounded regions, the algorithmic foundations of existing systems fail to provide deterministic execution and accuracy guarantees. They either process the full spectrum uniformly, resulting in unpredictable latency that varies across different scenes, or apply lossy compression that discards vital pose structures. To address this, we present PRISM, a framework that exploits the spatial concentration of RF reflections to achieve schedulable edge HPE. PRISM introduces three core components: 1) Physics-Bounded Integral Processing (PBIP), which restricts computation via constant-time integral queries; 2) Physics-Adaptive Instance Proposal (PAIP), which decomposes scenes involving multiple people into bounded local subproblems; and 3) Deadline-Aware Operation Profiles (DAOP), which provide offline-verified worst-case bounds for runtime quality-latency trade-offs. We evaluate PRISM on four public datasets spanning diverse radar configurations, reporting physical-bound and pose-accuracy measurements across this suite and examining deadline-aware scheduling on multi-person recordings together with an additional single-person set. Under single-threaded isolated execution, PRISM reduces 99th-percentile latency by 24\%--58\% relative to baselines that miss the deadline, records a 0.0\% miss rate on the evaluated traces, and attains the highest pose accuracy among deadline-feasible configurations, providing a practical route toward schedulable mmWave sensing on mobile edge hardware.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.14094v1">P2Skill: Privacy Preserving Skill Distillation for Cloud-Local LLM Inference Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-08-14T08:56:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Myunghoon Ryu, Geunpyo Park, Sungjoon Lee, XinYu Piao, Jong-Kook Kim</p>
    <p><b>Summary:</b> Cloud-local LLM inference systems have the potential to use the reasoning capability of large cloud models while protecting sensitive user data on personal devices. Cloud-bound requests must exclude personally identifiable information (PII) to prevent external data leakage. Existing privacy-preserving methods rely on prompt perturbation, entity masking, or model fine-tuning, but these approaches may distort contextual semantics or require additional training. This paper proposes P2Skill, a prompt-based skill distillation method in which a local small language model (SLM) autonomously performs decomposition, PII-aware routing, paraphrasing, and reconstruction by following the skill prompts. Skills are iteratively refined from execution failures by a cloud LLM, enabling the local SLM to generalize beyond memorized PII patterns, and therefore P2Skill requires no privacy-specific fine-tuning or learned auxiliary detectors. Evaluation on a four-domain benchmark shows that P2Skill achieves $1.69\times$ and $3.66\times$ higher privacy-preserved inference quality than previous baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.13914v1">Hybrid Quantum-inspired Kolmogorov-Arnold Networks for Privacy-Aware Federated Biosignal Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> 
  <p><b>Published on:</b> 2026-08-14T03:35:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chun-Hua Lin, Samuel Yen-Chi Chen, Yu-Chao Hsu, Kuo-Chung Peng, Jiun-Cheng Jiang, Chi-Sheng Chen, Tai-Yue Li, Nan-Yow Chen, En-Jui Kuo, Hsi-Sheng Goan</p>
    <p><b>Summary:</b> Electrocardiogram (ECG) recordings are sensitive biomedical data, limiting the ability of hospitals and wearable devices to share raw signals for centralized model training. Federated learning addresses this practical privacy constraint by enabling collaborative model training while keeping raw biosignal data at their respective sources. However, federated ECG classification remains challenging due to limited client-side samples, imbalanced arrhythmia labels, and non-independent and identically distributed (non-IID) data across clients. These constraints require classifiers that are both communication-efficient and robust to cross-client distribution shifts. In this work, we evaluate a hybrid quantum-inspired Kolmogorov-Arnold network (HQKAN) against a multilayer perceptron (MLP) for five-class arrhythmia classification on the MIT-BIH dataset and three-class classification on the INCART dataset under federated averaging (FedAvg). Across multiple client configurations, HQKAN improves most aggregate and minority-class metrics while using 37.35% fewer trainable parameters and reducing communication cost by 24.89% on MIT-BIH; on INCART, it achieves corresponding reductions of 44.81% and 36.41%. These results indicate that HQKAN offers a compact, communication-efficient and robust alternative to the MLP baseline for privacy-aware federated learning on biosignal data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.13773v1">CutClean: Neural Network Pruning for Privacy-Preserving Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-08-13T20:59:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Leonardo Magliolo, Vito Paolo Pastore, Giuseppe Valenzise, Enzo Tartaglione</p>
    <p><b>Summary:</b> Neural networks are increasingly deployed in high-stakes applications with growing privacy leakage concerns. We show that this privacy leakage can occur even in the absence of representation imbalances that lead to traditional dataset biases. This poses significant privacy risks when deploying models that process sensitive attributes. In this context, we propose CutClean, a privacy-aware pruning method that allows to reduce privacy information flow through the network, while increasing its sparsity. Our approach employs auxiliary linear privacy heads placed at each network's block to quantify information leakage, and further applies increasing levels of sparsity to remove the private attribute leakage, measured in terms of the accuracy of the privacy head attached to the last block. Experiments on synthetic and real-world datasets demonstrate that our approach effectively minimizes private information flow while achieving high sparsity rates and preserving classification target accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.13390v1">TeleGapper: On the (un)reliability of Privacy Policies in Telegram Mini apps</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-13T15:51:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Luca Ferrari, Mariano Ceccato, Luca Verderame</p>
    <p><b>Summary:</b> Telegram Mini Apps are Web applications embedded within the Telegram client, forming an ecosystem of third-party services within one of the world's most widely used messaging platforms. Despite their growing adoption and access to Telegram-provided context, their privacy properties remain largely unexplored. Unlike ecosystems such as WeChat, which rely on tightly controlled, proprietary execution frameworks, Telegram adopts a different model: Mini Apps run inside a WebView, combining platform-provided context with standard Web capabilities and unrestricted outbound networking. This enables applications to transmit sensitive information to analytics, advertising, tracking, or other third parties through ordinary Web requests, often with limited visibility.
  Privacy disclosures are therefore critical for transparency. Telegram allows Mini Apps either to define an application-specific privacy policy or to rely on a platform-provided default policy. While the latter reduces the developer's disclosure burden, it may lead to generic statements that do not accurately capture actual data practices of individual Mini Apps.
  In this paper, we present TeleGapper, a black-box dynamic analysis framework to assess the privacy posture of Mini Apps by capturing runtime network traffic, identifying third-party communications, and comparing observed data flows against disclosed privacy information. We evaluate 278 working Mini Apps collected from tApps Center, a community-driven catalogue for discovering third-party applications in Telegram. We find that 59.4% contact at least one undisclosed third party, 78.8% rely exclusively on Telegram's default privacy policy, and none provides a consent or opt-out mechanism. These findings expose a substantial transparency and compliance gap in a widely used yet understudied ecosystem.</p>
  </details>
</div>

