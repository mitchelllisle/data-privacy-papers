
<h2>2026-09</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.37667v1">Where Privacy Belongs: Placement Diagnosis and Certified Selection for Private Counterfactual Explanations on Graphs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-29T14:23:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuxiang Yao, Zijun Zhao</p>
    <p><b>Summary:</b> Counterfactual explanations for graph neural networks (GNNs) find the minimal intervention that flips a node's prediction--but computing one requires reading sensitive graph structure, and releasing it discloses that structure. Both existing placements fail. Privatizing the graph before explaining corrupts the target on exactly the borderline nodes needing recourse, manufacturing spurious flips that flip the privatized graph but not the true one. Explaining on the clean graph and perturbing the released explanation resists certification: re-auditing the standard heuristic shows an implied full-release budget of 573--753 on Cora and 256 on CiteSeer--orders of magnitude beyond its advertised budget--with worst-case single-entry leakage at AUC 1.0. We propose PrivCFS, which replaces certification-by-optimization with certification-by-construction: counterfactual selection over a fixed, data-independent candidate universe--edge interventions from a public prior graph, feature interventions from a public schema--whose no-op semantics give neighboring graphs the same output support. A validity-gated, clipped utility of global sensitivity $Δu \le 1$ released through the exponential mechanism gives pure $\varepsilon$-DP for the complete released object, composable over queries--to our knowledge the first such guarantee on graphs. Privacy noise is the cheapest stage: at $\varepsilon$=8 the release retains 94--97% of its support-restricted non-private optimum on the recourse population and 83--95% on the general one; the optimal edge-inference audit attains AUC 0.50 on average and 0.59 worst-pair, versus the heuristic's worst entry 1.0; and transfers to a 15K-node graph at 0.96 valid rate. The dominant cost is a measurable, monotone price in public disclosure, readable off one table before any budget is spent--turning explanation privacy from an accounting risk into a purchasable decision.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.37344v1">A Sharp Transition in Data Reconstruction under Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> 
  <p><b>Published on:</b> 2026-09-29T12:12:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Max Cairney-Leeming, Simone Bombari, Marco Mondelli</p>
    <p><b>Summary:</b> Data reconstruction attacks have empirically been successful in recovering training samples from learned models, raising privacy concerns and motivating defenses with guarantees that remain valid against future threats. While differential privacy (DP) provides formal protection, choosing the privacy budget remains a challenge: small budgets severely reduce utility, but it is hard to quantify how large the budget can be without allowing accurate reconstruction. In this work, we study informed attackers who aim to reconstruct a single $d$-dimensional training sample from a $ρ$-zero-concentrated DP model, knowing all other training data. Our main contribution is to establish a sharp transition at $ρ\asymp d$ for data reconstruction: on the one hand, we derive entropy-based lower bounds for any private mechanism and any attack, characterizing a set of target priors for which reconstruction is information-theoretically impossible for $ρ\ll d$; on the other hand, we analyze a simple attack on private linear regression with output perturbation, showing that reconstruction is practically feasible for $ρ\gg d$. Remarkably, the transition moves to $ρ\asymp s$ for data lying in an $s$-dimensional subspace, demonstrating that the privacy budget guaranteeing adequate protection must be assessed in terms of the effective dimension of the data. We validate our findings via experiments on synthetic data and natural images (CIFAR-10, ImageNet).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.36153v1">Privacy-Friendly Cohort Determination: Sealed, CSP-Independent In-Browser ML Inference of Professional Segments for Identity-Less Advertising</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-28T19:24:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Om Shankar Tiwari, Navnit Shukla, Guanyu Wang, Akshay Jain</p>
    <p><b>Summary:</b> B2B advertising targets a viewer's professional attributes (employer size and industry, function, seniority) and has obtained them by matching identities across sites. Safari and Firefox block third-party cookies, Google retired the Privacy Sandbox cohort APIs in 2025, and reverse-IP firmographics decay under remote work. We present SIF (Sealed Inference Frame), which infers coarse professional cohorts on the device and emits only a locally differentially private, taxonomy-coded label into the OpenRTB bid stream, with no cross-site identifier. It rests on a property of the web platform we make precise: a navigated cross-origin iframe is the only way third-party code obtains a policy it controls, so inference runs in WebAssembly even where the publisher's CSP forbids it, and a nested worker served with default-src 'none' gives the model no network. Even a malicious model leaks at most about 5 bits per site per week. Labels pass through a memoised k-ary randomised response keyed to the publisher's first-party identifier, which gives $\varepsilon$-local differential privacy, defeats averaging, and links requests no better than the identifier already sent. An org-conditional k-anonymity rule suppresses cells, more strictly on corporate networks than at home. Cohorts ride OpenRTB user.data in a LinkedIn-aligned taxonomy, and attribution uses LinkedIn's click-scoped li_fat_id without bridging identities. We report a crawl of CSP deployment on 7,969 top sites and 431 B2B publishers, Heavy-Ad budgets, closed-form privacy-utility trade-offs, a re-identification simulation, and an assessment of which attributes are predictable at all: company type and size are, seniority largely is not. On-device is a design property, not a consent exemption.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.35951v1">When Privacy Becomes a Weapon: Understanding Doxxing and Privacy Vulnerabilities in Mainland China's Social Media Ecosystem</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-09-28T17:29:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiao Zhan, Shijing He, Chi Zhang, Jose Such</p>
    <p><b>Summary:</b> Doxxing, the malicious disclosure of personal information, has become a pervasive privacy threat. Yet existing research remains predominantly Western-centric, limiting our understanding of how doxxing unfolds in contexts where mandatory identity systems, platform governance, and cultural logics fundamentally reshape privacy risks and harm trajectories. We address this gap through semi-structured interviews with 18 doxxing survivors in mainland China, synthesizing their experiences into a framework conceptualizing how doxxing operates in this context. Our findings reveal both patterns echoing prior Western findings, such as platform amplification mechanisms that resonate with Western findings, and China-specific dynamics shaped by the interplay of regulatory mandates (compulsory identity linkage) and cultural logics including nationalist discourse, fandom culture, Confucian values, and low privacy literacy. Survivors' experiences further reveal how doxxing reshapes understanding of privacy: from preference to precondition, from momentary disclosure to temporal vulnerability, and from individual control to structural powerlessness. These insights challenge agency-centered privacy frameworks and suggest that effective protection requires constraining systemic vulnerabilities rather than relying solely on user empowerment. We conclude by proposing multifaceted recommendations spanning legal reform, platform design, and social initiatives.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.35534v1">Privacy-Aware ISAC for Full-Duplex Monostatic Systems Using Movable Antennas</a></h3>
  
  <p><b>Published on:</b> 2026-09-28T16:17:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yasas Savinda, Mohammadali Mohammadi, Himal A. Suraweera, Henk Wymeersch</p>
    <p><b>Summary:</b> This work investigates sensing privacy in full-duplex (FD) monostatic integrated sensing and communication (ISAC) systems with movable antennas (MAs). The proposed approach jointly optimizes beamforming and antenna trajectories to create a deceptive dummy DD-bin response at a passive sensing eavesdropper (Eve), while satisfying a true-bin sensing-quality requirement at the base station (BS). The resulting problem is highly non-convex. {To address this, a stage-wise alternating local-search framework is developed to obtain suboptimal solutions. Within this framework, we maximize the worst-case margin between dummy and true delay-Doppler (DD)-bin detector-oriented SINR surrogates over a discretized uncertainty region for Eve, incorporating detector-aligned dummy-bin refinement and true-bin preservation.} Simulation results show that the proposed MA-enabled design suppresses Eve's true-target DD-bin selection and increases dummy-bin selection probability compared with benchmark schemes, while maintaining reliable BS sensing performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.35937v1">PrivacySkills: How Privacy Guidance Shapes Source Selection in LLM Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-09-28T15:22:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lucas Biechy, Cédric Eichler, Héber H. Arcolezi, Nicolas Anciaux</p>
    <p><b>Summary:</b> While prior work has documented privacy failures in LLM agents, it remains unclear how the presentation of privacy guidance influences their choice of information sources. We introduce PrivacySkills, a controlled framework for evaluating how agents choose among acquisition pathways that provide the same task-relevant value: consulting publicly available personal information, accessing confidential sources, or interacting with the user. The evaluation framework comprises 55 synthetic tasks spanning 11 categories of personal information, with 169 associated skills that describe the available acquisition pathways. We consider privacy guidance through system-level instructions, skill-level metadata labels, or both. Separately, we vary user availability and urgency framing. With users available and no privacy guidance, agents access confidential sources in 30% of valid runs on average across five open-weight models, despite sufficient alternatives. This rate increases to 45% when users are unavailable, whereas urgency framing has no detectable effect. System-level privacy instructions alone have limited effects on confidential access, while skill-level intrusiveness labels produce a modest reduction (24% on average), but combining the two roughly halves confidential access. Our findings motivate incorporating privacy annotations into skill specifications and evaluating their effectiveness alongside system-level instructions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.35234v1">Poster: Towards ProofWeave: A Privacy-Minimised, Integrity-Anchored Evidence Plane for Continuous Agentic Assurance</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-28T14:11:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guy Lupo, Nguyen Hung Nguyen, Viet Vo, Chamikara M. A. P., Guangdong Bai</p>
    <p><b>Summary:</b> Agentic AI systems increasingly act via tools, memory, delegation, and external services. Existing observability and provenance mechanisms can reconstruct events post hoc, but they rarely show, at the time of the record, whether each policy-relevant action was checked by the intended control before execution. This leaves a trust-observability gap for continuous monitoring, detection, and response: later assurance may rest on evidence that is incomplete, privacy-leaking, mutable, or detached from the policy context that governed the event. What's missing in the literature is contemporaneous, policy-bound evidence that the intended control was evaluated under the policy in force at the time.
  We introduce ProofWeave, a record-time chain-of-evidence concept for agentic AI assurance. At each policy-relevant action boundary, ProofWeave generates a privacy-minimised and integrity-anchored evidence transaction that binds (i) agent intent or action, (ii) control response, and (iii) a policy-at-time snapshot. Each transaction is committed to an append-only ledger and materialised into a derived proof graph. A bounded Weaver Agent translates policy intent into proof obligations, while deterministic validators check evidence completeness, privacy minimisation, policy binding, and integrity.
  In the minimal scenario, an agent attempts to transmit a secret to an unapproved external sink. The audit compares a logs-only correlation baseline with ProofWeave across verdict latency, join ambiguity, privacy exposure, tamper detection, and resistance to graph-only proof injection. ProofWeave reduces candidate bindings per verdict from up to `10,201` to one, validation operations from up to `10,201` to approximately `26`, and assurance evidence storage from `0.79`MiB to `0.15`MiB per project.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.35233v1">EP-Mem: Elastic Privacy Memory for Social Relationship-Aware LLM Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-09-28T14:10:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fengzhou Sun, Yuan Zhang, Xintong Yu, Jinyao Yan</p>
    <p><b>Summary:</b> Large language model (LLM) agents face critical privacy risks when acting as delegates in human-agent-human communication. To prevent such breaches, agents must understand users' social relationships and adhere to context-dependent social information disclosure boundaries. Current studies on agent memory privacy focus on instantaneous interactions, leaving the long-term relational disclosure problem unexplored. In this paper, we propose EP-Mem, an Elastic Privacy Memory architecture that reframes privacy as user-owned boundary control across social roles. EP-Mem introduces (1) token-level memory driven by user-configurable a privacy policy that stratifies persons and events, combining domain-level default circulation rules with fact-level whitelist/blacklist exceptions; and (2) a pluggable sidecar with a privacy engine that aligns disclosure controls with memory across summary, detail, and boundary granularities, enforced throughout generation, storage, and retrieval. We construct EP-Bench, to our knowledge the first long-term multi-party benchmark with cross-session correlated events for policy-conditioned relational disclosure. Experiments show that EP-Mem achieves 94.0% privacy classification accuracy, improves disclosure-permission judgment from 22% to 68%, and reduces privacy leakage by 75.6%, while maintaining retrieval performance and cross-benchmark generalization.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.34768v2">Privacy-Preserving Full-Body Meshing from mmWave Radar via Mesh Foundation Model Supervision</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-09-28T09:49:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuxing Zhang, Yongquan Ni, Zhenyu Ding, Yawen Lin</p>
    <p><b>Summary:</b> Millimeter-wave (mmWave) radar enables privacy-preserving human perception, but the extreme sparsity of point clouds from commercial single-chip sensors (mean ~6.5 points/frame; ~28% empty frames) has confined prior art to body-part keypoints or discrete action classification. We present a cross-modal teacher-student framework that lifts commercial radar to full-body, per-frame, metric 3D mesh reconstruction with per-joint uncertainty. Three innovations: (1) a mesh-foundation-model teacher - SAM 3D Body produces whole-body MHR ground truth (70 joints, 18,439 mesh vertices) from a single RGB frame with zero training, slashing annotation cost by orders of magnitude; (2) StudentPoseFormer - set encoding with masked attention pooling, a temporal Transformer, and a CVAE multi-hypothesis head that outputs both the pose mean and per-joint variance, honestly reporting where the radar cannot see; and (3) a multi-stage ground-truth quality pipeline (confidence gating, depth validation, temporal smoothing, bone-length consistency, bad-frame rejection) plus systematic information-lever ablations. On the public MM-Fi benchmark (same TI IWR6843 sensor, cross-subject), our full configuration reaches 7.45 cm 12-joint MPJPE, with ablations proving the causal value of point accumulation (k = 3, -0.34 cm), Doppler (-0.85 cm; -2 cm at the wrist on fast actions), and velocity loss (-0.27 cm). On our own synchronized radar + RGB-D corpus with block-level held-out splits, the pipeline achieves 21.47 cm end-to-end (per-joint hierarchy from 4.8 cm at the hip to 34.7 cm at the wrist - matching physical information limits), could be improved to 15 cm with ~30k diverse samples, and a scaling law shows sample diversity, not volume, is the binding constraint. Deployment inference is radar-only - no camera, no image.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.34411v1">Coherence Rather Than Error Rate Governs Privacy in Multi-Tenant Quantum Computing</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-28T06:25:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Farhad Farokhi</p>
    <p><b>Summary:</b> Multi-tenant computing enables providers of commercial cloud quantum processors to rent disjoint sectors of a device to independent users. Average gate error, which cloud quantum computing providers report, does not determine how much one tenant learns about another. We propose an information-theoretic notion of information leakage across co-tenancy boundaries stemming from quantum state distinguishability. We measure this leakage on commercially-available 156-qubit (IBM Kingston) and 20-qubit (IQM Garnet) devices. Boundaries with identical benchmarked error can offer significantly different amount of information leakage because standard reported measures of error are blind to coherent-versus-stochastic nature of the error while the proposed notion of information leakage is not. A uniform Pauli randomisation implemented over the victim's whole register is used as a defence mechanism to reduce the information leakage to zero. The defence theoretically does not incur a fidelity cost, but the experiments show a non-trivial degradation caused by accumulation of errors. We provide a specific call-for-action to the providers of quantum cloud computing to report information leakage in addition to standard error rates in their device datasheet to enable users to compute privacy and security risks prior to engagement with the device.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.34220v1">mmHRI: Towards Privacy-Preserving Human-Robot Interaction with Millimeter-Wave Radar</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-09-28T03:24:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Junqiao Fan, Yuxuan Hu, Bofan Lyu, Yanshuo Lu, Pengfei Liu, Jiarui Zhang, Fangqiang Ding, Lihua Xie, Gen Li, Jianfei Yang</p>
    <p><b>Summary:</b> Assistive robots increasingly operate in many human-centered environments and perform various human-robot interaction (HRI) tasks, such as object delivery. However, most existing HRI systems rely on RGB cameras that continuously observe humans to respond to non-verbal commands, such as hand gestures. This raises privacy concerns in privacy- critical environments, such as hospital wards or restaurants, where direct camera observation of humans is restricted. To develop privacy-preserving HRI, we leverage millimeter-wave (mmWave) radar, which can sense human motion through privacy barriers without identifiable imagery. We propose mmHRI, the first multi-modal robot manipulation framework that achieves mmWave radar-guided privacy-preserving HRI. mmHRI introduces two key designs to mitigate the sparsity and temporal inconsistency of radar data in cluttered robot manipulation environments. First, we propose a dual-stream architecture that jointly learns from unfiltered raw radar tensors and radar point clouds to estimate both human actions and 3D poses. To mitigate signal inconsistency, mmHRI further incorporates a memory-based state-space model (MSSM) that retains historical radar features to reduce abrupt changes in pose/action. These estimated human states are then converted into structured textual robot instructions, which control a vision-language-action (VLA) policy for closed-loop robot manipulation and human-aware reactions. Our evaluation covers human action recognition and closed-loop delivery and retrieval. In the privacy-preserving curtain setting, mmHRI achieves 85.09% action-recognition accuracy, outperforming existing radar-based alternatives. Robot trials further demonstrate successful delivery and retrieval under visual occlusion, with stable task performance across unseen subjects, clutter configurations, and environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.33985v1">The Privacy Fallacy of Crowdsourced Fine-Tuning: Extracting Proprietary Data via Topic-Based Poisoning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-27T22:36:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sae Furukawa, Alina Oprea</p>
    <p><b>Summary:</b> Supervised fine-tuning (SFT) is widely used to adapt large language models to downstream tasks. Crowdsourcing user conversations is an established approach to collecting SFT data at scale while reducing the need for costly manual annotation. However, it also allows untrusted users to contribute data to the fine-tuning pipeline. We investigate an underexplored privacy risk arising from this setting: can a malicious user poison a small fraction of the crowdsourced data to amplify extraction of previously unseen instructions contributed by other users? We show that this is possible using only black-box, output-only access to the deployed model. Experiments across four models and two datasets demonstrate substantial increases in training-data extraction: with only 50 poisoned examples, near-verbatim extraction reaches $3.71\times$ the rate without poisoning for Qwen2.5-14B on OpenMathInstruct and $3.08\times$ for Llama-3.1-8B on AceReason. Data filtering also proves largely ineffective in detecting poisoned samples: even the best-performing method achieves only 0.378 in F-1 score, leaving the majority of poisoned samples undetected. These findings demonstrate that seemingly benign crowdsourced contributions can amplify leakage of other records while remaining difficult to identify through data filtering.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.33754v1">Collaborative Synthetic Data for Privacy-Preserving Financial Fraud Detection Across Organizational Silos</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-09-27T16:53:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Simeon Allmendinger, Domenique Zipperling, Burhanettin Bahadir Kibar, Niklas K{ü}hl</p>
    <p><b>Summary:</b> Organizations seek analytical value from AI, yet relevant data are often fragmented across organizations and constrained by privacy. This is acute in financial fraud detection, where rare fraud cases and imbalanced local datasets limit decision-relevant analytics. Federated learning enables collaboration without direct data sharing but does not resolve minority-class scarcity. Synthetic data generation can help, yet lightweight methods are interpolation-bound, while generative models require substantial data and computation. Existing collaborative generative approaches often rely on federated learning, imposing considerable organization-side training burdens. In this paper, we examine CollaFuse as a collaborative diffusion-based alternative for fraud detection and evaluate it across five fraud datasets. Compared with classical oversampling, local generative baselines, and centralized diffusion benchmarks, CollaFuse does not achieve the highest local fidelity but improves downstream fraud detection more consistently across most datasets. These findings suggest that synthetic data create analytical value less through local realism than through transferable cross-organizational structure.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.33312v1">When Privacy Moves ML-Mediated Decisions On Device: Information and Incentive Misalignment in Auctions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-27T07:25:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dipankar Sarkar</p>
    <p><b>Summary:</b> Moving ML-mediated decision making onto privacy-preserving clients decentralises the economic decision along with the inference. Shared budget constraints then depend on information that cannot be globally current, creating an information-structure failure that conventional pacing is not designed to solve. We study this information misalignment in an auction-logic-faithful on-device simulation with 36 campaigns and 50 devices. Accounting is in dimensionless integer score units; no currency semantics are claimed. Across 30 paired demand paths, proportional Even pacing overspends 17.77% after one tick of staleness and 1,669.31% after 50 ticks under the original 20-times budget pressure. The effect does not depend on that severe a budget: at two-times pressure, 50-tick overspend remains 106.95%. A visible-budget no-sale guard makes zero-lag compliance exact at this score-unit granularity, yet leaves 11.88% overspend at one tick because other devices' debits remain invisible. A declared bursty, heterogeneous-device sweep retains a strictly increasing mean lag curve. We derive a finite-window expected excess-debit bound under conditional charge caps and find positive paired slack in every bounded-value cell. A second, incentive misalignment arises when the ML/pacing score transformation is allowed to change payment units: 98.23% of rival auctions at one tick admit a profitable deviation. An executable implementation-level counterexample isolates the runner-up's multiplier in the winner's price. Critical-base-bid payment is per-auction DSIC conditional on current multipliers, but does not establish dynamic truthfulness and does not repair base-value ranking disagreement.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.33004v1">On the Usage of Verifiable Credentials in Privacy-Preserving Federated Analytics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2026-09-26T22:57:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Andreea-Elena Drăgnoiu, Ruxandra F. Olimid</p>
    <p><b>Summary:</b> Privacy-Preserving Federated Analytics enables multiple nodes to collaboratively derive statistical insights without exchanging raw data. However, ensuring node authenticity and data validation (avoiding concerns such as identity tracking, data linkage, or data leakage) remain fundamental challenges. This paper offers some insights into the feasibility of defining an authenticated, integrity-preserving data model by coupling FPPA with Verifiable Credentials defined within the Self-Sovereign Identity framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.32835v1">FinancialAuditBench: Benchmark Construction under Differential Privacy Using Real-World Priors</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-09-26T18:07:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jerry Huang, Sarvesh Babu, Matt Van Buren, Alexander Wang, Pranav Pillai, Arush Jain, James P. Burton, Julia Hockenmaier</p>
    <p><b>Summary:</b> As AI agents are becoming widely adopted in the financial services industry, careful measurement is essential to understand where they can be reliably deployed and where oversight and professional review remain necessary. Such measurement, however, is constrained by limited access to proprietary or privacy-sensitive data. Existing benchmarks therefore often rely on publicly available data, human- and/or LLM-authored tasks, or simplified settings. We introduce FinancialAuditBench, a benchmark for evaluating agents on financial statement audit tasks, along with a framework for systematically generating synthetic engagements. Our task generation framework leverages differentially private aggregate statistics from historical audits along with audit expertise contributed through over 1,100 hours of benchmark development and review. FinancialAuditBench consists of 90 tasks spanning workpaper completion and review across six synthetic audit engagements, each containing an average of 179 files. Evaluation on eleven frontier models shows that while agents complete substantial portions of staff-level audit tasks well, they sometimes perform inappropriate procedures or produce incorrect documentation. Beyond financial auditing, our framework offers an approach for systematically generating synthetic tasks for model evaluation and training in privacy-sensitive domains.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.32706v1">Learning to Refer: Client-Resolved Generation for Privacy-Aware Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-09-26T15:13:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jeongho Yoon, Chanhee Park, Yongchan Chun, Duong Tuan Thanh, Sungbin Han, Chanjun Park, Hyeonseok Moon, Heuiseok Lim</p>
    <p><b>Summary:</b> Cloud-based large language models (LLMs) require users to disclose plaintext data to service providers, creating privacy risks in sensitive domains. Existing privacy-preserving approaches often trade utility for protection, incur substantial computational or communication overhead, remain vulnerable to reconstruction from intermediate representations, or protect only a subset of the training and inference pipeline. We introduce Client-Resolved Generation (CRG), a genera- tion interface that separates server-side generation from the lexical realization of input-derived content. The client transmits only pooled and noise-perturbed rep- resentations, while input-derived output content is represented using request-local positional references and resolved to its original strings only on the client. This interface protects private input and input-derived output content during both train- ing and inference while allowing the service provider to keep its proprietary model parameters hidden from the client. At the same time, exact lexical reuse remains possible without directly exposing the reused content on the provider-visible gen- eration path. We evaluate CRG on medical and document-grounded QA, sensi- tive identifier transfer, and tool calling, together with reconstruction and raw-logit leakage analyses. On SealTools, CRG improves complete-call exact match from 57.3% to 79.9% over the input-privacy framework PPFT, with larger gains as more required output content can be resolved through references. Together, these results show that CRG provides a practical interface for privacy-sensitive cloud LLMs by reducing plaintext exposure across both input and output pathways while preserv- ing task utility and server-side model confidentiality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.32293v1">TRAP: Understanding and Mitigating Privacy Memorization in Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-26T06:36:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Muhammed Ustaomeroglu, Ziyue Xu, Hanshen Xiao, Peter Cnudde, Guannan Qu, Holger R. Roth</p>
    <p><b>Summary:</b> Fine-tuning a language model on sensitive records can leave it able to reproduce them. We ask when this memorization arises and how to prevent it without knowing in advance which spans are sensitive. Our starting point is that most memorization scores and attacks share one statistical core: whether the model assigns a token more probability than some reference would. Taking as the reference a model trained on the complementary half of the same corpus gives the Target Reference Advantage (TRA), a per-token signal that separates what a model fit to a particular record from what it learned across records, and is cheap and differentiable. We then study what drives memorization during fine-tuning: it keeps growing well past the validation minimum, is larger on small datasets and at higher learning rates, and higher when the underlying task is harder. Early stopping removes much of it, but because it is chosen by aggregate validation loss it helps least for rare, hard-to-predict spans embedded in otherwise learnable text, which is exactly what sensitive information tends to be. We therefore introduce TRAP, a one-sided penalty on tokenwise TRA that acts only where the target model pulls ahead of its reference. On student essays with annotated personal information and clinical cases with patient identifiers, TRAP brings memorization near the level of an untrained model at little utility cost, where generic regularizers barely move and differential privacy gives up most of what fine-tuning bought.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.32030v1">Who Governs Data in the AI Era? A Computational Analysis of the U.S. Privacy Workforce in Job Postings</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-25T21:52:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ramazan Yener, Muhammad Hassan, Masooda Bashir</p>
    <p><b>Summary:</b> Privacy protection now spans legal, technical, and managerial duties, and demand for privacy professionals is growing across sectors. However, little is known about how employers define these roles. We analyze 1,143 U.S. privacy job postings from LinkedIn and Indeed. We examine job titles, salaries, competencies, certifications, education, experience, regulatory references, and AI-related language by using rule-based text mining. We also apply Topic Modeling (BERTopic) to the same postings and identify 18 latent themes which we grouped them into four categories. Our findings show that privacy roles are hybrid and they combine legal knowledge, technical skills, and interpersonal competence. Artificial intelligence appears in more than half of postings, with AI language spread across compliance, legal, governance and security themes. Our research indicates that AI governance responsibilities are often embedded within existing privacy roles, contributing to the rise of hybrid positions alongside dedicated AI governance roles.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.31310v1">Revisiting Certified Defense with Differential Privacy on Vision Transformers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2026-09-25T14:17:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jun Yan, Weiquan Huang, Qixian Zhang, Yan Bai, Shutai Zhang</p>
    <p><b>Summary:</b> Certified defenses that incorporate differential privacy have proven effective on Convolutional Neural Networks (CNNs), furnishing rigorous robustness guarantees against norm-bounded adversaries. However, the certified robustness behavior of Pixel Differential Privacy (PixelDP) remains largely unexplored with the self-attention architecture now dominating the deep-learning landscape. Given that the Transformer has a profound impact on our daily applications from the digital world to the physical world, it is crucial to study certified robustness through differential-privacy-style stability. To fill this research gap, we revisit this construction in Vision Transformers and identify a failure mode that is largely hidden in the convolutional setting. When noise is injected after the patch embedding, the Laplace mechanism with the inherited grouped $\ell_1$ sensitivity bound collapses to chance-level accuracy across noise scales, whereas the Gaussian mechanism remains trainable. This contrast isolates the source of failure: not the injected noise itself, but the geometry of the sensitivity constraint. We show that the attenuation induced by the inherited $Δ_{1,1}$ projection increases with layer width and kernel size according to a random-matrix scale $C/(\sqrt{M}+\sqrt{N})$. Replacing the $\ell_1$-type constraint with a spectral-norm constraint eliminates the collapse across datasets and architectures, but creates a fundamental obstacle: the repaired models no longer satisfy the sensitivity condition required by the standard Laplace certificate. We resolve this mismatch by deriving a dimension-free $(\varepsilon,\ δ)$-privacy guarantee for the Laplace mechanism under $\ell_2$ sensitivity through concentration of the privacy loss.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.31262v1">Deduplication-while-Training: A Resilient Paradigm for Privacy-Preserving Cross-Client Deduplication in Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-09-25T13:39:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rongxi Wang, Guanxiong Ha, Chunfu Jia, Yongsheng Lin, Minfen Gao, Hanmiaomiao Wang</p>
    <p><b>Summary:</b> Cross-client duplicate data in large language model training corpora degrades the efficiency of federated learning (FL) while exacerbating model memorization and privacy risks. Privacy-preserving cross-client deduplication effectively mitigates this issue by eliminating duplicate training data. However, existing schemes all follow a "Deduplication-before-Training" paradigm. This serially coupled paradigm incurs high fault-tolerance costs and lacks support for dynamic client joining.
  To this end, we propose an unexplored paradigm called "Deduplication-while-Training (DwT)", which enables concurrent deduplication and training. DwT transforms cross-client deduplication from a one-time, globally synchronous preprocessing operation into a continuous online service with state management, concurrent claiming, and failure recovery. By enabling state synchronization and task takeover, it minimizes the impact of client disconnections on the overall training progress while supporting the dynamic joining of clients. We design DwT-FL, a privacy-preserving deduplication system, to support DwT. By designing a concurrent state-claim mechanism and a hot-cold dual-queue scheduling strategy, DwT-FL enables the parallel execution of secure deduplication and model training, while effectively handling client disconnections and dynamic joins. Experimental evaluations demonstrate that, compared to the state-of-the-art scheme, DwT-FL significantly reduces the time overhead of failure recovery and dynamic joining by up to 93.04% and 94.18%, respectively. This provides an efficient and elastic concurrent deduplication scheme for dynamic and unstable FL environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.30692v1">LUMO (Lightweight Unified Multilingual Orchestrator): A Privacy Preserving Offline Voice Assistant</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-25T01:57:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Md. Mehedi Hasan Naeem, Mst. Kamrunnahar Ruma, Nafiza Anjum, Shakila Sultana, Md. Sujan Ali</p>
    <p><b>Summary:</b> Reliable voice interaction is essential in environments with limited internet connectivity and strong privacy. However, most existing voice assistants depend on cloud-based services, which leads to latency issues, dependency on internet access, and privacy vulnerabilities. This research presents LUMO (Lightweight Unified Multilingual Orchestrator), a privacy preserving offline voice assistant designed for edge computing environments. This system integrates local Automatic Speech Recognition (ASR), locally deployed quantized Large Language Model (LLM), and Text-to-Speech (TTS) synthesis into a fully offline pipeline running on a Raspberry Pi 5 with 8 GB RAM.
  To enable efficient operation on resource constrained hardware, the language model is compressed using 4-bit GGUF quantization, which reduces memory usage while preserving practical conversational capability. Existing edge based voice assistants Mycroft provides partial offline functionality without a generative LLM, with an approximate latency of ~5 s and power consumption of ~12 W, while Rhasspy supports full offline operation but lacks generative capabilities, with ~3 s latency and ~11 W power usage. In contrast, LUMO achieves a Word Error Rate (WER) of 6.8% for short English utterances in low noise conditions, an end-to-end response latency of 2.0-4.0 s, and a lower peak power consumption of approximately 9.0 W. The system also achieves effective offline recognition for Bangla speech, supporting multilingual accessibility in low resource settings. By operating entirely offline, LUMO provides strong data privacy, reduced need for cloud connectivity, and suitability for privacy sensitive edge execution such as rural healthcare, education, and disaster response scenarios.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.30554v1">Privacy-Preserving Prompted Policy Search for Robotic Control</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E"> 
  <p><b>Published on:</b> 2026-09-24T21:03:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ali Irshayyid, Feng Lin, Chong Li, Jun Chen</p>
    <p><b>Summary:</b> Large language models (LLMs) have recently demonstrated promising capabilities as in-context policy optimizers for Reinforcement Learning (RL), enabling policy search driven by both numerical reward signals and natural language reasoning. However, deploying such methods in practice requires transmitting raw policy parameters and rewards history to cloud-based LLM APIs, exposing proprietary control strategies to third-party service providers. To address this issue, this paper introduces Privacy-Preserving Prompted Policy Search (PP-ProPS), a framework that enables LLM-guided policy optimization while keeping policy and environmental parameters confidential. PP-ProPS encodes policy parameters and reward values using secret client-side transformations before they are included in each API request, ensuring that the LLM provider observes only encoded policy parameters and scaled reward information. Furthermore, unlike Vanilla ProPS, the proposed framework does not require the true optimal episodic return to be known or disclosed to the LLM. Beyond protecting the optimization data, PP-ProPS improves the search process in two ways. First, it provides the LLM with individual reward components instead of only a single total return, offering more informative feedback about each candidate policy. Second, it uses a bounded history that prevents the prompt from growing indefinitely, improving search with high-dimensional policies and supporting the use of open-weight LLMs. The proposed PP-ProPS is evaluated on both continuous and discrete control problems spanning Multi-Joint dynamics with Contact (MuJoCo) locomotion, classic control, highway driving, and robotic arm manipulation. Compared to Vanilla ProPS, the proposed PP-ProPS outperforms ProPS in seven of the ten evaluated tasks, and surpasses conventional RL methods including PPO, SAC, and TRPO, in five of the six tasks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.29453v1">Decoupled Learning and Selection in Slate Recommendation for Privacy and Stability Under Noisy Scores</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2026-09-24T12:09:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sam Urmian, Qinyi Liu, Mohammad Khalil</p>
    <p><b>Summary:</b> We formalize slate recommendation as a randomized score learner followed by deterministic selection. First, an appropriately scoped differential-privacy guarantee passes through selection and its audit trace by post-processing. End-to-end privacy holds only when selector inputs are public or independent, previous private outputs, or separately privacy-accounted; fixing raw state or candidate information instead yields only a conditional guarantee. Second, we derive a logged margin certificate: bounded score-induced objective movement below half the smallest greedy decision margin guarantees that the ordered slate is unchanged.
  Controlled fixed-margin tests show near-linear exponent scaling, with an empirical slope of $-0.220$ (95% CI $[-0.231,-0.210]$) against the independent-noise reference $-1/4$. Real-anchor experiments on OULAD, MovieLens-25M, and Amazon Musical Instruments show that greater anchor weight reduces score-noise-induced ranking churn. OULAD and EdNet certificate checks validate the implementation of the logged inequality, while closed-loop simulations show bounded target drift and setting-dependent downstream utility. The contribution is therefore a privacy-scope contract and a certifiable score-to-slate stability mechanism, not a universal utility claim.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.31763v1">SMARtCARE: Privacy-Preserving Agentic AI Systems for Bounded-Autonomy Clinical Decision Support</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2026-09-24T02:44:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Srini Ramaswamy, Deveeshree Nayak</p>
    <p><b>Summary:</b> Long-context clinical AI systems can miss relevant patient history when prior admissions fall outside the active reasoning context. In ICU monitoring, this can cause early vital-sign drift to appear nonspecific even when it resembles a prior deterioration pattern. SMARtCARE addresses this gap through a four-state clinical decision-support architecture: Stable, Meta-cognitive, Assisted, and Regulated (Revoked). Rather than automatically retrieving prior records, SMARtCARE uses a lossy six-channel fingerprint of the patient's prior trajectory. When current drift matches that fingerprint and the prior record is absent from context, the system raises a Meta-cognitive escalation for clinician review; full retrieval occurs only through clinician action in the Assisted state. A patient-identity guard is designed to enforce correct attribution across data loading, logging, and audit layers. Evaluation combines a synthetic Monte Carlo study that validates the state-transition logic and estimator stability, not clinical performance, with real-data runs on both the MIMIC-III and MIMIC-IV Clinical Database Demos. On MIMIC-III, one prior-pattern recurrence was identified among 14 two-admission patients; on MIMIC-IV, the same pipeline produced no fingerprint matches among 9 two-admission patients, which illustrates a key limitation of a fixed canonical pattern library. Across both runs all logged decisions were fully traceable and correctly attributed. The results support SMARtCARE as a traceable, privacy-aware mechanism for surfacing middle-context risk; they are not a clinical efficacy claim.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.28685v1">"A Necessary Evil": Teenagers' Sensemaking of Privacy and Safety Settings on Social Media</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-09-23T18:26:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jingxin Dong, Lingyun Chen, Chen Ling, Colin M. Gray</p>
    <p><b>Summary:</b> Social media platforms are embedded in teenagers' daily lives, supporting friendship and identity while exposing teenagers to unwanted contact and privacy harms. Previous scholarship has documented how attention capture strategies and dark patterns shape social media use, and we extend this work to better understand platform settings that ostensibly provide privacy and safety protection. We report on think-aloud sessions with 11 teenagers aged 14 to 17 who completed six privacy and safety tasks on Instagram, TikTok, Snapchat, and YouTube. We show how participants worked out what a setting meant through their routines, boundaries, and prior experiences, how they accommodated protections softer and less predictable than expected, and how they treated the platform as the authority on what protection should look like. We argue that feature-by-feature evaluation cannot establish whether teenagers are protected, and that platforms should carry the obligation to show that a protective action took effect and is durable.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.28672v1">Available but Not Usable: Dark Patterns and Interaction Cost in Social Media Privacy and Safety Settings for Teens</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-09-23T18:13:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jingxin Dong, Lingyun Chen, Chen Ling, Colin M. Gray</p>
    <p><b>Summary:</b> Social media platforms are central to teenagers' lives, and their designs can expose users to privacy, safety, and wellbeing harms. Platforms increasingly offer protective settings, though the presence of a control reveals little about whether teenagers can find, use, and benefit from it over time. We paired an expert evaluation of six privacy and safety tasks across TikTok, Instagram, Snapchat, and YouTube with moderated think aloud sessions in which 11 teenagers aged 14 to 17 attempted the tasks. Interaction cost and dark patterns analysis allowed us to compare the complexity designed into each task with the effort participants incurred as they located, configured, and interpreted controls. Recurring dark patterns appeared across tasks, and most participant attempts exceeded the expert baseline. Protective settings therefore risk being insufficiently usable or durable in practice, and we propose a wayfinding audit that integrates expert evaluation, usability testing, interaction cost, and dark pattern analysis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.28360v1">Privacy-Preserving Semantic Segmentation from High-Resolution Depth and Ultra-Low-Resolution RGB</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E">
  <p><b>Published on:</b> 2026-09-23T16:31:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xuying Huang, Swithinraj Moses Daniel, Sicong Pan, Sebastian Houben, Maren Bennewitz</p>
    <p><b>Summary:</b> As mobile robots become increasingly integrated into everyday environments, privacy risks arising from onboard cameras have become a growing concern. Ultra-low-resolution (ULR) RGB can mitigate visual privacy exposure at the source, but ULR appearance alone substantially limits semantic and spatial understanding. We therefore introduce a privacy-preserving asymmetric sensing setting that combines high-resolution (HR) depth with ULR RGB, preserving dense geometry while restricting fine-grained visual information. To address the severe information imbalance between HR depth and ULR RGB, we propose a joint 2D framework using HR geometry to guide semantic-oriented RGB reconstruction and RGB-D segmentation. Despite reliable frame-level predictions, consistent scene-level understanding remains challenging under the asymmetric HR depth--ULR RGB setting. We therefore develop an end-to-end 2D-to-3D pipeline that consolidates 2D semantic features for 3D segmentation. Experiments on ScanNet show that our method achieves the best 2D and 3D segmentation performance among privacy-preserving approaches and delivers the strongest zero-shot transfer to SUN RGB-D and SceneNN. Privacy recoverability analysis shows that our proposed HR depth--ULR RGB input reduces the recoverability of sensitive data, and real-robot experiments demonstrate the utility of the resulting 3D semantics for object-goal navigation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.28297v1">Contraction and Statistical Inference under Privacy for Uniformly Bounded Distributions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">
  <p><b>Published on:</b> 2026-09-23T15:43:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Leonhard Grosse, Sara Saeidian, Tobias J. Oechtering, Mikael Skoglund</p>
    <p><b>Summary:</b> We investigate $c$-interior pointwise maximal leakage (PML) as a tool for contraction analyses and disclosure control. Based on the strong adversarial threat models from maximal leakage, $c$-interior PML generalizes local differential privacy (LDP) to data-generating distributions with densities uniformly bounded away from zero by $c>0$. Viewing $c$-interior PML as an algebraic constraint on a kernel yields more flexible (and often tighter) contraction analyses than standard LDP. We provide tight bounds on the Dobrushin coefficient, and bound the contraction coefficient of the Hockeystick-divergence. We further derive strong data processing inequalities on $f$-divergences under $c$-interior PML constraints when the input distributions to the divergence are restricted to be in the $c$-interior. These results extend beyond the regime of pure LDP to cover a larger class of kernels, including, e.g., arbitrary stochastic matrices. We apply the results to minimax theory and provide asymptotically optimal strategies under $c$-interior PML constraints for binary hypothesis testing and mean estimation. The results show that disclosure control with PML allows analysts to reason about systems in a more differentiated manner: For example, it allows us to quantify the privacy leakage of deterministic systems, and can give precise adversarial guarantees with respect to arbitrary distributional assumptions. Interestingly, a recurring theme in the disclosure analyses is that if the privacy problem is relatively regular (if the density bound $c$ is large), private inference can be possible without incurring any additional cost in terms of sample complexity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.28137v1">"We'll Fix It Later": Education, AI, and the Deferral of Privacy in EdTech</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-09-23T13:59:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Meghna Manoj Nair, Rachel Greenstadt</p>
    <p><b>Summary:</b> Educational technology (EdTech) platforms collect highly sensitive student data, including behavioral logs, disability records, and academic histories. However, privacy considerations are often postponed rather than treated as a foundational design requirement. We present a mixed-methods study combining 12 semi-structured interviews with EdTech professionals and a privacy policy audit of 48 platforms coded across five dimensions, with strong inter-rater reliability (mean Cohen's Kappa = 0.781). Our interviews reveal a recurring organizational pattern in which privacy is recognized as important but deferred across the product lifecycle as organizations prioritize product functionality, growth, funding, and immediate educational outcomes. Responsibility is often delegated to cloud providers, policy documents, or downstream institutions, while limited privacy-related feedback gives organizations little pressure to change these practices. The policy analysis reflects these patterns: platforms describe what data they collect relatively well but provide substantially less information about how that data is subsequently governed. Thirty-three percent make no meaningful Artificial Intelligence (AI) disclosure despite visible AI features, and 73% provide only generic accountability and breach-response language. K-12 platforms perform better on children's consent where regulation creates explicit requirements, but this advantage does not extend to AI governance or accountability. These findings suggest that meaningful improvement requires enforceable institutional and regulatory mechanisms rather than voluntary privacy commitments alone.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.27617v1">Finite-Sample Binary Hypothesis Testing via Rényi Divergences: Strong Converse and Local Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">
  <p><b>Published on:</b> 2026-09-23T09:41:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Roberto Bruno, Adrien Vandenbroucque, Amedeo Roberto Esposito</p>
    <p><b>Summary:</b> We study asymmetric simple binary hypothesis testing between $H_0:P_0^{n}$ and $H_1:P_1^{n}$, based on $n$ independent and identically distributed observations. Leveraging a variational representation of Rényi divergence of order $α$, we derive our main result: a finite-sample converse with $α>1$. The bound uses both directions of the divergence $D_α(P_1\|P_0)$ and $D_α(P_0\|P_1)$, tensorises under product measures, and contains familiar data-processing converses as boundary cases. For comparison, we apply the same variational approach to general $f$-divergences and specialise it to total variation, $E_γ$, Hellinger, and Kullback Leibler divergences, thereby recovering familiar converses within a unified framework. Together with an achievability bound involving Rényi divergence with $α\in (0,1)$, the main converse recovers the phase transition of the optimal Type II error under the exponentially decaying Type I error constraint $\varepsilon_n=e^{-nr}$. Under regularity conditions, the optimal Type II error vanishes exponentially when $r<D(P_1\|P_0)$ and converges exponentially fast to one when $r>D(P_1\|P_0)$. We also derive sample-complexity bounds and extend both the converse and achievability analyses to locally differentially private observations, quantifying the cost of privacy and recovering the non-private achievability bound as the privacy constraint vanishes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.27406v1">Only Pay What You Must Spend: On-Demand Privacy Budget Payment for Differentially Private RAG</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Digital Libraries-D91E36">
  <p><b>Published on:</b> 2026-09-23T06:20:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhonghao Sun, Zhiliang Tian, Xinyue Fang, Shuo Ma, Juhua Zhang, Yiping Song, Dongsheng Li</p>
    <p><b>Summary:</b> Deploying large language models (LLMs) on sensitive data via Retrieval-Augmented Generation (RAG) introduces severe privacy risks. Recent studies apply Differential Privacy (DP) to LLMs with RAG for formal privacy guarantees. However, existing DP-RAG frameworks rapidly exhaust the privacy budget. Although recent efforts attempt to save the budget by narrowing the retrieval scope or sparsifying private generation, these methods themselves cumulatively consume the budget, whereas they could actually rely merely on public information or at a negligible one-time privacy cost. This mismatch fails to align budget expenditure with the model's actual reliance on private data, causing substantial waste on operations that require no private access. To address this, we propose SparsePay-RAG, adopting "only pay what you must spend" as its core principle. Using public information as a zero-privacy prior, it charges the privacy budget only for the private increment. Specifically, SparsePay-RAG narrows the retrieval scope via public topic-guided clustering, adaptively controls private access frequency without privacy cost through isotonic cross-layer trajectory fitting, and compresses per-access budget via DP contrastive decoding. Under strong privacy constraints, experiments show SparsePay-RAG achieves superior privacy-utility trade-offs over baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.27100v1">Cryptographic Security Is Not Enough: Privacy Gaps in the Renegade Decentralized Dark Pool</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-22T21:54:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Prerna Arote, Adrian Saiz, Oriol Saguillo, Lucianna Kiffer</p>
    <p><b>Summary:</b> Dark pools are designed to provide pre-trade privacy, liveness, and post-trade confidentiality - concealing order flow before execution and limiting information leakage after. Decentralized dark pools, such as Renegade, aim to replicate these properties without custodial risk, using secure multi-party computation (MPC) and zero-knowledge proofs for private order matching and verifiable settlement.
  We show that Renegade's cryptographic guarantees do not deliver these dark pool properties in practice. MPC-with-abort ensures correctness but not fairness: a party may learn the match result and abort without penalty, breaking pre-trade privacy. We demonstrate that the protocol's discovery layer further leaks trading intent before MPC even begins, and that sustained probing via selective abort can probabilistically reconstruct counterparty order history, threatening post-trade confidentiality. We also show that the absence of input-consistency checks prior to MPC execution enables a griefing attack using invalid state commitments requiring no real token holdings that continuously locks honest users' wallets and wastes compute, breaking liveness under sustained conditions.
  We further analyze over 700,000 Renegade transactions on Base and probe the P2P layer, finding that the network is effectively centralized: 88% of traffic routes through a handful of relayers, with only four nodes sustaining the P2P layer. Since relayers hold their users' wallet state in plaintext, this concentration means the system operates as a centralized orderbook in practice - reproducing off-chain the information asymmetry that dark pools are designed to eliminate.
  Together, our results show that cryptographic privacy does not imply dark pool security: pre-trade privacy, liveness, and post-trade confidentiality each require additional protocol-level guarantees beyond MPC correctness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.28537v1">Privacy Leakage Through AI-mediated Analysis of Smartphone Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-09-22T20:24:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sarah Radway, Zoe Robert, Matthew Soto, Julianna Cimillo, Sebastian Diaz, Meg Marco, James Mickens</p>
    <p><b>Summary:</b> Over the past thirty years, the online advertising industry built a large-scale data collection ecosystem, with the goal of tracking a user's online activity to infer their demographics and interests. Traditionally, the ecosystem relied upon the collation and analysis of highly-structured text data like user IP addresses, GPS coordinates, e-commerce purchase histories, and visited URLs. However, recent ML models can parse not only structured text, but also multimedia files and unstructured text inputs---meaning a user's photos, videos, inboxes, and calendars are now ripe for automated analysis. The privacy risks are particularly acute in the context of smartphone apps. A user's phone already acts as a natural collation point for sensitive user information, but users may not understand that permitting an app to, for example, access a user's photo does not just give the app access to the bytes in the photo: the app also receives access to inferences about the user that are enabled by the photo.
  To explore these privacy risks, we built Priva-See, an LLM-based inference system for app-collected user data; Priva-See reflects our best understanding of how real-life adtech companies would leverage machine learning to build user profiles. Through an IRB-approved user study, 465 participants deployed Priva-See on their phones; Priva-See made privacy-invasive inferences despite having access to only a subset of a user's data. We see the experience significantly impacted participant willingness to share permissions data moving forward. Based on the observed privacy violations, we suggest changes to how smartphone OSes should gather user consent for data access, to better inform users about downstream data usage capability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.26680v1">Decoding the Legalese: A Scalable and Quantitative Framework for Analyzing Corporate Privacy Policies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-09-22T16:38:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiaming Tang, Chenlan Wang, Mingyan Liu, Armin Sarabi</p>
    <p><b>Summary:</b> Even though privacy policies are the primary mechanism organizations use to disclose how they collect, process, and share personal data, they are difficult for average users to interpret, perhaps by design, due to their verbosity and dense legal language. Importantly, there is a lack of standardized metrics that characterize key qualities of a privacy policy beyond regulatory requirements. Recent advances in large language models (LLMs) make it feasible to automatically structure and analyze these documents at scale. In this study, we develop and evaluate an end-to-end, LLM-enabled system that converts raw privacy policies into fine-grained structured representations and a set of quantitative measures. Our pipeline applies a detailed taxonomy to extract specific data elements and governing practices, capturing relational links that connect each practice to the data elements it references. We apply our framework to a diverse corpus of 10,000 website privacy policies, yielding, to the best of our knowledge, the most comprehensive dataset of its kind to date. Building on our structured representations, we introduce the first standardized and repeatable quantitative metrics for evaluating privacy policies along four dimensions: completeness, transparency, commitment to user protection, and emphasis on business-driven data practices. This allows us to compare policies within and across industry sectors, and to assess the tension between user protection and business interests.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.26623v1">A Data-Interventional Framework for Auditing Privacy and Fairness in Generative Medical Imaging</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-09-22T15:55:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mischa Dombrowski, Bernhard Kainz</p>
    <p><b>Summary:</b> Diffusion-based synthetic data generation offers a promising route for sharing medical imaging data without releasing sensitive patient records. However, generative models face a fundamental tension between privacy and fairness: they may memorize rare training samples, leading to privacy risks, or fail to reproduce underrepresented features, resulting in unfair synthetic distributions. While prior work has largely focused on either memorization or fairness in isolation, their interaction remains insufficiently understood. In this work, we introduce a data-interventional framework to systematically analyze privacy and fairness in diffusion models. We discuss synthetic anatomical fingerprints (SAFs), rare and manually injected image features, as controlled probes to study whether models generalize sensitive attributes across identities, memorize training samples, or suppress rare signals entirely. Across multiple conditioning modalities, we observe a consistent behavior: models either forget these fingerprints or memorize the entire image in which they appear, but do not generalize them to novel images. To support large-scale auditing where explicit sample extraction is infeasible, we further introduce the indicator metric t', which estimates a model's susceptibility to memorization by exploiting the internal structure of the diffusion process. By comparing conditioning signals of varying surprisal, we reveal a clear relationship between conditioning rarity and memorization behavior. Highly surprising conditioning signals act as retrieval keys that amplify memorization, whereas low-surprisal conditioning signals systematically suppress rare features, even when these appear repeatedly in the training data. Our findings provide actionable insights and concrete mitigation strategies for safe and fair synthetic medical data sharing. Code is available at https://github.com/MischaD/Privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.26508v1">Gap-Free Streaming PCA Beyond Rank-One Updates: Near-Optimal Rates and Applications to Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> 
  <p><b>Published on:</b> 2026-09-22T14:38:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anming Gu, Syamantak Kumar, Kevin Tian, Chutong Yang</p>
    <p><b>Summary:</b> Streaming principal component analysis (PCA) seeks to recover a leading spectral subspace in a single pass over a data stream. We give a new analysis of the ubiquitous Oja's algorithm [Oja82] for the most general, gap-free variant of this problem, where no eigengap assumptions are made on the underlying mean matrix, complemented by a nearly-matching lower bound. Prior works achieving near-optimal rates for streaming PCA either required gap assumptions [JJK+16, HNWW21], or were limited to rank-one updates [AZL17, Lia23]. Our proof only uses a second moment bound on the individual stochastic updates, bypassing the almost sure bounds needed by prior near-optimal analyses, and the analogous offline matrix Bernstein bound. We also extend our result to a Rayleigh quotient notion of approximate PCA, addressing an open question of [JJK+16]. As our main application, we give gap-free differentially private PCA guarantees for sub-Gaussian data, settling Conjecture 1.1 of [Bro26] up to logarithmic factors.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.26365v1">Privacy-Preserving Coordinated Operation of Power Grids and AI Data Centers: A Checkpoint-Aware Three-Phase Scheme</a></h3>
  
  <p><b>Published on:</b> 2026-09-22T13:07:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ziang Liu, Ruizhang Yang, Xin Cui, Francis Yunhe Hou</p>
    <p><b>Summary:</b> The rapid growth of large language model training and serving is driving AI data centers (AIDCs) toward gigawatt scale. Unlike conventional commercial loads, AIDCs possess significant operational flexibility through dynamic voltage and frequency scaling (DVFS) of training and inference workloads, while periodic model checkpointing can induce abrupt power drops and rebounds that erode operating reserves and increase transmission congestion risks. Coordinating AIDC operation with grid scheduling under these unique operational characteristics is challenging because grid and AIDC operators are generally unwilling to share proprietary data and decision-making authority. This paper proposes a hierarchical privacy-preserving coordinated operation scheme between the power grid and AIDCs to address this gap. The proposed scheme contains three phases. In Phase I, the grid operator computes a certified inner approximation of the AIDCs security region for subsequent coordination. In Phase II, the AIDC operator coordinates training and inference AIDCs to optimize workload allocation within the certified security region and generate power schedules and checkpoint alerts. In Phase III, the grid operator solves a checkpoint-aware two-stage robust optimal power flow (OPF) considering renewable generation and checkpoint uncertainties. By exchanging only compact interface information, the framework preserves the privacy of both grid and AIDCs, avoids frequent iterative communication, and enables secure coordination with guaranteed feasibility. Numerical studies on a modified IEEE 14-bus system and a modified NYISO system demonstrate the effectiveness, robustness, and security of the proposed framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.26295v1">On the security and privacy of LLMs in Mobility</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-09-22T12:09:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mauro Conti, Lorenzo Perinello, Umberto Salviati</p>
    <p><b>Summary:</b> The mobility sector is undergoing a paradigm shift driven by advances in Generative Artificial Intelligence. With a global market valued at approximately 2.9 trillion dollars annually, considering only cars, the integration of these technologies has the potential to impact more than 1.5 billion vehicles worldwide. As Large Language Models (LLMs) are increasingly adopted in mobility, concerns about cybersecurity, privacy, and reliability emerge. Accordingly, this paper surveys current applications and assesses these challenges. Since the European AI Act classifies transportation AI as high risk, we derive nine technical classes from its requirements to assess current research and future deployments. Our findings show that research mainly studies GPT and Llama models (over 50\% of reviewed works) and traffic applications while largely neglecting security, privacy, and reliability. This gap extends to AI Act compliance: among 35 reviewed works, only one includes a partial vulnerability assessment and one a partial risk management system. We identify a clear gap between strong optimization performance and regulatory adherence, suggesting compliance is limited less by technology than by a focus on static performance over lifecycle safety, and underscoring an urgent need for security-by-design in safety-critical intelligent transportation systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.25941v1">UE-Side Location Privacy for 5G NR Uplink Positioning: Mechanisms and Trade-offs</a></h3>
  
  <p><b>Published on:</b> 2026-09-22T09:47:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Giulia Focarelli, Alireza Pourafzal, Henk Wymeersch, Stefania Bartoletti</p>
    <p><b>Summary:</b> Future 5G-Advanced and 6G networks increasingly reuse uplink communication waveforms for positioning and sensing. This raises privacy concerns, as user equipments (UEs) may unintentionally reveal precise timing information even when positioning services are not explicitly requested. While prior works show generic orthogonal frequency division multiplexing (OFDM) pilots can be manipulated to degrade time-of-arrival (ToA) estimation without compromising data links, this paper extends these concepts to a realistic 5G new radio (NR) up-link framework including Sounding Reference Signal (SRS), Demodulation Reference Signal (DMRS), Physical Uplink Shared Channel (PUSCH), and standardized 3GPP channel models. We investigate several UE-side privacy mechanisms: optimized pilot distortion, artificial noise, artificial multipath, and delay spoofing. Through 3GPP-compliant sample-level simulations, we assess their impact via localization, communication, and consistency-based detection metrics. The resulting analysis highlights the trade-offs among privacy, communication reliability, and detectability, providing key insights into waveform-level obfuscation for future integrated sensing and communication (ISAC) systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.25798v1">Secure ISAC with Sensing Privacy under Eavesdropper Uncertainty</a></h3>
  
  <p><b>Published on:</b> 2026-09-22T07:34:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pigi P. Papanikolaou, Dimitrios Bozanis, Sotiris A. Tegos, Christos Masouros, George K. Karagiannidis</p>
    <p><b>Summary:</b> This paper investigates the joint protection of confidential data and legitimate-user directional information in integrated sensing and communication (ISAC) networks. We consider a multiuser downlink in which passive multi-antenna eavesdroppers (Eves) attempt to decode confidential signals while exploiting legitimate-user reflections for unauthorized angular sensing. To address both threats, we develop a robust covariance-design framework that jointly limits Eve decoding, maintains the transmitter's accuracy in estimating the Eves' directions and shifts the dominant passive-sensing response toward prescribed deceptive directions. A Bayesian angular prior and the corresponding Bayesian Cramer-Rao bound (BCRB) characterize the transmitter's eavesdropper-angle estimation accuracy. Angular uncertainty is represented through geometry-consistent samples, such that each candidate Eve direction jointly determines the corresponding transmitter-Eve channel, user-Eve bearing, and deceptive direction. The resulting design balances worst-user secrecy, sensing accuracy, sensing privacy, and deception power. Robust Eve-decoding constraints are handled through finite sufficient conditions with intersample margins, while continuous ghost dominance is enforced using interval sum-of-squares (SOS) constraints. The resulting nonconvex problem is addressed through successive convex approximation (SCA) and semidefinite relaxation. Numerical results show that the proposed design effectively preserves secrecy and sensing privacy under Eve-angle uncertainty, provides controlled angular deception in single- and multiple-Eve scenarios, and outperforms benchmarks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.25484v1">Learning Defensive Policies against Diverse Inference Attacks for Smart Meter Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-21T23:27:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruichang Zhang, Mustafa A. Mustafa</p>
    <p><b>Summary:</b> Smart meter (SM) data provides fine-grained visibility into household energy consumption, but also exposes users to privacy risks. Inference attacks, known as non-intrusive load monitoring (NILM), can perform appliance-level inference from aggregate signals and recover sensitive behavioral patterns. In practice, attacker models are unknown and heterogeneous, making robust defense challenging. We formulate SM privacy protection as a black-box inference defense problem, aiming to reduce the recoverability of appliance-level information while generalizing across diverse and unseen attackers. We propose a proxy-guided hierarchical reinforcement learning framework that learns battery-based load-shaping policies to inject realistic but misleading appliance-level signatures into the aggregate signal, thereby disrupting the structured patterns exploited by NILM. A self-supervised aggregate-structure privacy probe provides a reconstruction-error-based surrogate reward for disrupting recoverable load structure, while a signature library makes the perturbations appliance-relevant and physically realizable through battery control. We provide theoretical rationale showing that proxy-guided optimization improves inference robustness under attacker diversity. Experiments on real-world datasets UK-DALE and REDD demonstrate strong cross-model and cross-appliance generalization. Across six unseen NILM attackers, covering four appliances on UK-DALE and five on REDD, our proposed defense increases average appliance-level RMSE by 107% and 166%, respectively, while reducing F1 score by 79% and 80%.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.25352v2">SSP-Bench: A Hybrid Data Generation Framework for Safety, Security, and Privacy Evaluation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2026-09-21T19:44:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fatih Deniz, Yazan Boshmaf, Issa Khalil</p>
    <p><b>Summary:</b> Evaluation of large language models (LLMs) for safety, security, and privacy (SSP) relies heavily on static benchmarks, which suffer from score saturation, data contamination, and aggregation artifacts, and fail to capture sensitivity to linguistic variation. As a result, models that perform well on fixed test sets often fail under semantically equivalent rephrasings. We introduce SSP-Bench, a dynamic benchmarking framework that generates evaluation instances on demand while preserving domain consistency. The framework ensures label validity through externally grounded sources, enforces scope via service-specific validation, and calibrates difficulty using a multi-model steering panel. Benchmark construction is formulated as a multi-objective optimization problem over difficulty, separability, novelty, and diversity. Across 24 models and four SSP services, SSP-Bench reveals systematic failures of static evaluation, including near-zero correlation in safety rankings due to construct mixing, strong safety--over-refusal coupling, and hidden within-family regressions. These results show that static benchmarks can misrepresent model behavior, motivating dynamic, deployment-relevant evaluation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.24656v1">5G-Shark: A Network Security Auditor for 5G Subscriber Privacy and Unauthenticated Signalling Resilience</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-09-21T14:24:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Oscar Lasierra, Gines Garcia-Aviles, Antonio Skarmeta, Xavier Costa-Pérez</p>
    <p><b>Summary:</b> The fifth generation of mobile networks was standardised with an explicit mandate to close long-standing privacy and security gaps, mandating the concealment of the subscriber's permanent identity, resistance to generational downgrade, and protection against location tracking. Assessing whether these guarantees hold in operational networks, however, requires separating two sources of residual exposure that prior studies do not distinguish and do not evaluate in the wild: protocol-design limitations, which remain exploitable even against a fully specification-compliant deployment, and implementation gaps, which arise from incomplete or non-compliant implementations. We present 5G-Shark, a security assessment tool and methodology that turns a legitimate mobility procedure against the subscriber. Rather than relying on active jamming or malformed-packet injection, 5G-Shark manipulates the standardised cell-reselection criterion to pull a target User Equipment onto a self-created rogue cell, establishing an attack vantage with minimal service disruption. Then, the proposed methodology effectively performs the required interactions to expose the security risks of the system under test, classifying them into the aforementioned categories. Built solely from open-source stacks and Software Defined Radio hardware and evaluated against commercial 5G Standalone deployments, 5G-Shark requests subscriber identifiers, forces Radio Access Technology downgrade via crafted Registration Reject codes, and induces denial-of-service states. For each vector, we attribute the root cause to protocol design or deployment non-compliance. We further provide empirical evidence that in several commercial deployments, temporary identifiers are re-allocated in near-sequential steps that keep successive values linkable, a weakness that enables persistent user tracking despite correct subscriber ID concealment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.24537v1">MIRAGE: Full-Body Bystander Privacy for Smart Glasses with Consent-Based Restoration</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-21T13:09:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Muhammad Umair, Muhammad Danial Maqbool, Fatima Arshad Cheema, Kapal Dev, Muhammad Hamad Alizai, Muhammad Ali Siddiqi, Naveed Anwar Bhatti</p>
    <p><b>Summary:</b> Video recording on smart glasses exposes more than faces. Continuous capture reveals full-body biometric signatures, including gait, posture, and silhouette, that enable person re-identification (ReID) even after conventional face sanitization.
  We present MIRAGE, a three-tier architecture for privacy-preserving smart glasses that enforces full-body privacy, supports synthetic full-body replacement, and retains encrypted recovery material for consent-based restoration. We implement MIRAGE on a Raspberry Pi~5 (a CPU-only proxy for smart-glasses compute), companion phones, and a cloud generative backend. Compared to prior systems, MIRAGE achieves 0.948 AP and 0.976 AR while accurately detecting the complete visible body. Its bounding box masking reduces learned silhouette-based ReID to essentially random guessing, with 10.86% Rank-1 accuracy compared with an 11.12% measured chance level. Even against an adaptive adversary retrained on MIRAGE's sanitized pose signals, Rank-1 gait identification drops from 90.25% to 26.20%, removing 72.5% of the adversary's identification advantage.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.24173v1">Zero-Knowledge Remote Adversarial Attack against Wi-Fi-based Human Activity Recognition for Privacy Protection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762"> 
  <p><b>Published on:</b> 2026-09-21T06:43:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Byungjun Kim, Amogh Panchagatti, Peter Gerstoft, Xinyu Zhang, Minsung Kim</p>
    <p><b>Summary:</b> The growing capability of Wi-Fi devices to identify human activities using channel state information (CSI) raises privacy concerns. To counter this threat, we propose GRAW, an adversary system, acting as a privacy defender, that degrades the human activity recognition (HAR) system at the user device by perturbing the router's signals that the device uses to estimate CSI. GRAW employs generative adversarial imitation learning (GAIL) to construct perturbation signals, and thereby eliminates the need for any information on the target HAR systems and their inputs (i.e., zero-knowledge operation). We evaluate GRAW against seven representative HAR models, using datasets collected in five environments, including our own dataset. We observe that GRAW is the only remote attack scheme that degrades every tested HAR model to a random-selection level. At the same perturbation level, GRAW achieves an attack success ratio up to 76.7% higher than comparison methods, while maintaining over 99% packet success rate on regular Wi-Fi communication. We demonstrate the feasibility of GRAW through real-time, over-the-air experiments with software-defined radios.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.23827v1">Pattern-level Differential Privacy for High-utility Complex Event Processing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2026-09-20T19:23:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> He Gu, Thomas Plagemann, Vera Goebel, Maik Benndorf, Boris Koldehofe</p>
    <p><b>Summary:</b> Current privacy-preserving mechanisms (PPMs) in Complex Event Processing (CEP) systems are unnecessarily restrictive, reducing the utility of data received by data consumers. This article presents a novel approach to preserve privacy in CEP systems, improving the utility of detected event patterns by dynamically adapting the noise added to an unprotected data stream. We introduce a new guarantee named pattern-level differential privacy (DP), which enables us to apply and compare the strength of PPMs at the pattern level. We propose new pattern-level PPMs yielding pattern-level DP and analyze different trust settings of these PPMs and their requirements for context knowledge in the CEP system, e.g., the deployed queries. Our evaluation is based on three datasets (two real-world, one synthetic) and shows that the proposed PPMs increase data utility while preserving the same privacy level as the state-of-the-art PPMs. We use simulations to study the performance of our proposed PPMs in various practical scenarios. Furthermore, we demonstrate that computational complexity is not an obstacle to deployment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.23521v1">Feature Suppression and Differential Privacy for Residential Traffic Classification: A Two-Home Federated Study</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-09-20T10:17:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Márton Pál Lipcsey-Magyar, Adrian Pekar</p>
    <p><b>Summary:</b> Residential traffic classification supports service management, but learning across homes must account for heterogeneous traffic and privacy constraints. Privacy-aware training may impose uneven costs across traffic categories. We study this tradeoff in simulated two-client federated learning using 1.62 million preprocessed gateway-collected flows across six categories. We compare a full-feature baseline, feature suppression (FS), and differentially private stochastic gradient descent (DP-SGD) under one fixed record-level privacy setting. FS-mild excludes four timing features from 16 model inputs; it provides no formal privacy guarantee. With size-proportional aggregation, FS-mild achieves higher combined macro-F1 and worst-group F1 (the minimum per-class F1 across homes) than DP-SGD in all five seeds at both model capacities under stratified and temporal splits. The tested DP-SGD configuration incurs pronounced minority-category losses, especially in the smaller home, but FS-mild does not uniformly improve on the full-feature baseline. On stratified-split models, loss-based and shadow-model membership probes show near-chance aggregate discrimination without a consistent ranking across probes; this does not establish equivalent privacy. These findings support FS as an input-minimization baseline, not a substitute for formal privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.23403v1">Alignment and Divergence between Humans and AI in Interpersonal Privacy Decisions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-09-20T06:30:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hanxiang Zeng, Shuning Zhang, Xinyuan Zhou, Tianqi Song, Yuhan Yuan, Yuting Yang, Shuai Ma, Xin Yi</p>
    <p><b>Summary:</b> AI assistants increasingly mediate interpersonal communication on behalf of their primary user, but they risk violating the privacy expectations of third-party information owners. Resolving these tensions requires understanding how humans anticipate interpersonal privacy boundaries. Therefore, we conducted a dyadic study (N=76) and a matched evaluation of AI models across 18 information types and 3 recipient relationships. We found that data owners' privacy judgments are highly contextual and relationship dependent. While familiar data co-owners show meaningful alignment with owners' expectations, they significantly overestimate the need for permission. Interestingly, greater familiarity within the owner-co-owner dyad was associated with both higher disclosure acceptability and lower co-owner misalignment, whereas our exploratory four-item empathy measure was not. In contrast, AI models significantly underperform human co-owners in anticipating the data acceptability, even when provided with within-dyad examples. These findings underscore a core HCI design challenge to develop privacy-aware AI that respects multi-stakeholder information boundaries.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.25103v1">Physical-Layer Sensing Privacy via Constellation Shaping for OFDM-ISAC Systems: Theory, Design, and Experiments</a></h3>
  
  <p><b>Published on:</b> 2026-09-20T02:29:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kawon Han, Kaitao Meng, Christos Masouros</p>
    <p><b>Summary:</b> The integration of sensing into communication networks introduces a new privacy risk, as a passive eavesdropper (Eve) may exploit ISAC data signals as signals of opportunity to perform unauthorized sensing of targets. In this paper, we develop a sensing-privacy-enhancing geometric constellation shaping (GCS) framework for OFDM-ISAC systems. The key observation is that constellation-dependent ranging performance is receiver-specific. For matched filtering at Eve, the ranging MSE is governed by the constellation kurtosis $\kurt$, whereas reciprocal filtering at the legitimate receiver (Alice) is governed by the inverse second-order moment $\ism$. Based on closed-form MSE expressions, we define sensing privacy as the ranging MSE gap between Eve and Alice and characterize its dependence on these two moments. The analysis shows that positive skewness of the symbol-power distribution is necessary for a positive intrinsic moment gap, namely $\kurt-\ism$. We further derive an exact skewness-based decomposition of the intrinsic moment gap and a canonical two-ring characterization, providing analytical guidelines for privacy-enhancing constellation geometries. We then formulate Eve-aware and Eve-agnostic GCS designs that balance sensing privacy and communication reliability through the minimum Euclidean distance (MED), with the Eve-agnostic design depending only on the intrinsic moment gap. Numerical results demonstrate scalable privacy--communication trade-offs, while over-the-air experiments show that the proposed constellation shaping substantially increases the ranging error gap between Eve and Alice with only a small communication throughput loss.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.23193v1">LLMs as Linguistic Chameleons: Decoupling Semantics and Structure for Privacy-Preserving Communication</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-09-19T19:41:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuzhu Mao, Liang Zhao</p>
    <p><b>Summary:</b> As Large Language Model (LLM) APIs become increasingly integrated into privacy-sensitive workflows, ensuring inference-time privacy without compromising task utility remains a major challenge. Existing approaches preserve most of the original semantic content to maintain downstream performance, but this also leaves exploitable cues for reconstructing the original text. This work investigates semantic decoupling, which replaces original semantics with alternative content while preserving the structure needed for LLM reasoning. Based on this idea, we propose CROSS-MAP, a bidirectional framework that maps private inputs into a different semantic domain before inference and recovers the corresponding outputs afterward. Local models are trained with multi-objective optimization to maximize semantic divergence in the mapping stage while minimizing semantic inconsistency in the recovery stage. Experiments show that CROSS-MAP reduces reconstruction success across multiple attack settings while outperforming existing baselines in utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.22900v1">SMS-delivered network-initiated SUPL on Pixel 8: a privacy assessment</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-09-19T09:16:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Douglas Leith</p>
    <p><b>Summary:</b> A SUPL\_INIT message is a network-initiated trigger that can be sent to a handset using an SMS to unilaterally start a location session: on receipt, the handset is instructed to determine its own position and report it, together with an identifier such as its IMSI, to a server specified in the message, without any action by the phone's user. The concern motivating this investigation is whether such a message could be used to silently exfiltrate a handset's location and subscriber identity to a server under an attacker's control. We investigated this on a Google Pixel 8 handset, which uses a Samsung Exynos modem and a Broadcom GPS/GNSS subsystem. We find no privacy issue: the handset never sends location data to an attacker-chosen server as a result of an unsolicited SUPL\_INIT delivered by SMS.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.22720v1">When Disability Disclosure Travels: Memory, Privacy, and Contextual Integrity in Conversational AI</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-09-19T03:11:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Atieh Taheri, Mahya Tazike, Patrick Carrington, Jeffrey P. Bigham</p>
    <p><b>Summary:</b> Conversational AI assistants remember what people tell them, and for disabled people, that often includes disability. We interviewed 12 adults with disabilities in the United States who use LLM-based assistants such as ChatGPT, Claude, and Gemini about when, how, and why they disclose disability to these systems and how this compares with disclosing to people. Using contextual integrity as an analytic lens, we found that participants disclosed by need rather than by name, translating disability into task-scoped instructions; that the same disclosure was judged against two recipients, a non-judging interlocutor and a data-holding company, producing opposite norms; and that memory features relieved the burden of repeated disclosure while letting disability information drift into contexts where it did not belong. Participants did extensive boundary work to restore context and wanted control over scope, provenance, retention, and access rather than per-utterance toggles. We discuss implications for the design of conversational AI assistants.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.25082v1">Federating Quantum and Classical Computing: A Privacy-Preserving Hybrid Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-09-18T20:53:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Carlos Cano, Daniel M. Jimenez-Gutierrez, Diego Sal, Georgios Kellaris, Joaquin del Rio, Oleksii Sliusarenko, Xabi Uribe-Etxebarria</p>
    <p><b>Summary:</b> Quantum machine learning (QML) is increasingly recognized as one of the most promising near-term applications of quantum computing, viewed as a next-frontier candidate beyond purely classical approaches. Hybrid quantum-classical models operationalize this potential by embedding a parameterized quantum circuit within a model where all other components remain classical-a design already applied to chemistry simulation, financial modeling, and image classification. However, their deployment in privacy-sensitive, multi-party settings is constrained by the need to avoid centralizing raw data and by the requirement that modern quantum circuits remain parameter-efficient to stay trainable at scale.
  In this paper, we address these constraints by evaluating federated learning (FL) as a means of combining a hybrid quantum-classical active party with a classical passive party, using Sherpa.ai's Blind Vertical FL (SBVFL) protocol to avoid centralizing raw data, while drastically reducing communication. We construct the split multiplicative periodic parity (SMPP) benchmark, following common QML design practice. On this task, our simulations show that SBVFL raises accuracy from 0.7227 to 0.8757 compared to local training, closely approaching non-private centralized accuracy, and that the hybrid quantum-classical model achieves this with substantially fewer trainable parameters than the classical neural networks and random forest alternatives. These results show that FL enables high-performing, privacy-preserving quantum-classical collaboration without centralizing raw data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.21686v1">CIPL: A Channel-Aware Framework for Recoverable Privacy Leakage in LLM Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-09-18T12:23:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tao Huang, Guosen Wu, Guolong Zheng, Jiayang Meng, Chen Hou, Xu Yang, Xuechao Yang, Feng Xia</p>
    <p><b>Summary:</b> Privacy leakage in LLM agents is commonly evaluated within individual components such as memory, retrieval, or tool-use pipelines, which makes it difficult to distinguish internal exposure from information that an external observer can actually recover. We present CIPL (Channel Inversion for Privacy Leakage), a channel-aware evaluation framework for black-box privacy leakage in LLM agents. CIPL represents a target through sensitive source, selection, assembly, execution, observation, and extraction stages and evaluates the transition from selected sensitive units to attacker-recoverable output under a shared protocol. Experiments across memory-based, retrieval-mediated, and tool-mediated targets, together with a BrowserUse live-agent case study, show that storage labels alone do not determine recoverability. Memory targets form a near-saturated reference case, retrieval-mediated leakage is frequently partial, and tool-mediated and live-agent leakage varies strongly with observation surface, prompt-to-channel alignment, retrieval depth, and provider behavior. A stratified semantic audit further identifies attacker-useful disclosures that canonical exact matching misses. CIPL therefore provides a common framework for comparing how internal sensitive dependence is realized as externally recoverable leakage across heterogeneous agent pipelines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.21363v1">Hiding in Plain Sight: A Diffusion-based Mitigation of Geolocation Privacy Leakage in Vision-Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-18T06:24:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yining Wang, Xi Li, Mi Zhang, Xiaohan Zhang, Xiaoyu You, Zhenxing Qian, Mi Wen</p>
    <p><b>Summary:</b> Multimodal large reasoning models (MLRMs) have demonstrated remarkable capabilities in complex visual understanding. However, this very power introduces a critical yet underexplored privacy threat: adversaries can exploit MLRMs to precisely infer users' geographic locations from casually shared photographs, by performing structured reasoning over subtle visual cues such as architectural styles, vegetation, and lighting conditions. In this work, we present a systematic study of MLRM-driven geolocation privacy leakage. We first reveal that refusal-based safeguards are critically insufficient, as carefully crafted jailbreak prompts can raise model response rates to 100%. We further identify that existing defenses, which inject imperceptible perturbations into shared images, suffer from structural limitations intrinsic to their pixel-space optimization, resulting in degraded black-box transferability and pronounced visual artifacts. Motivated by these findings, we propose a diffusion-based framework that provides targeted, proactive defense against geolocation privacy leakage. By injecting perturbations into the latent space of a diffusion model during reverse sampling, our method operates directly on high-level semantic representations, thereby resolving the effectiveness-utility bottlenecks by construction. We further ground our optimization with GeoCLIP, a model explicitly aligned with GPS coordinates, as a surrogate to pinpoint and disrupt the geographic signals that MLRMs exploit for location inference. This targeted semantic disruption yields significantly stronger black-box transferability while preserving perceptual image quality, offering a seamless integration on social media platforms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.21340v1">Conformal Privacy Auditing: Calibrated Re-identification Attacks with Statistical Guarantees</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-09-18T05:49:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuo Huang, Gholamreza Haffari, Xingliang Yuan, Ting Yu, Lizhen Qu</p>
    <p><b>Summary:</b> Empirical identity leakage from released text is increasingly driven by attackers that combine large language models (LLMs) with auxiliary knowledge to link documents to individuals. Existing audits typically report success rates for specific attack pipelines but lack finite-sample statistical guarantees, while training-time protections such as differential privacy are difficult to translate into release-time decisions for individual natural-language documents. We introduce Conformal Privacy Auditing(CPA), a distribution-free calibration framework that provides a statistical certificate of re-identification risk for each released document against LLM-empowered adversaries. CPA outputs a conformal ambiguity set of candidate identities that is guaranteed to contain the true identity with user-chosen confidence under exchangeability, together with an interpretable leakage proxy derived from set size. CPA supports both logit-access and sampling-only attackers, enabling audits of open-source models and proprietary API models in a unified framework. Across multiple release benchmarks and attacker configurations, CPA achieves calibrated coverage and reveals sharp shifts in certified identifiability as auxiliary knowledge, LLM augmentation, and release mechanisms vary, providing a statistically grounded basis for reporting and comparing release-time linkage risk across attacker configurations, datasets, and release mechanisms alike.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.21338v1">Asymptotic Anytime-Valid Quantile Inference under Local Differential Privacy</a></h3>
  
  <p><b>Published on:</b> 2026-09-18T05:49:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Leheng Cai, Qirui Hu, Shuyuan Wu</p>
    <p><b>Summary:</b> Sequential quantile inference is difficult under local differential privacy because every record is randomized before reaching the analyst and the limiting quantile variance depends on an unknown density. We develop an online procedure that combines randomized response with dynamically chained parallel stochastic gradient descent (P-SGD). The resulting Polyak--Ruppert estimator admits a strong Gaussian approximation. A cross-chain quadratic statistic, computed entirely from private iterates, consistently estimates the limiting variance without a separate online density estimator. These results yield asymptotic confidence sequences and, under polynomial chain growth, asymptotic time-uniform coverage. Arm-wise constructions support locally private quantile best-arm identification, time-uniform simple-regret bounds, and sequential A/B tests of quantile treatment effects. Simulations and salary-data analyses illustrate the finite-sample behavior and practical use of the proposed methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.20561v1">Empirical Analysis of Randomness Quality in Differential Privacy Mechanisms</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-17T15:26:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Cesare Gerolimetto Fabrello, Valeria Rossi, Alberto Trombetta, Massimo Caccia</p>
    <p><b>Summary:</b> Differential Privacy (DP) relies on carefully calibrated random noise to protect individual privacy in statistical analyses. While theoretical work has analyzed DP under weakened randomness assumptions, the practical consequences of entropy degradation remain poorly understood. We present a systematic empirical investigation of how randomness quality affects differential privacy mechanisms using IBM's DiffPrivLib. We introduce progressively degraded entropy sources characterized by established test suites, starting from high-quality quantum True Random Number Generators (TRNGs) and cryptographically secure Pseudo-Random Number Generators (PRNGs) down to systematically manipulated sources with controlled entropy degradation. Through repeated experiments over one million queries on a reference database and complementary statistical tests, we directly analyze empirical Privacy Loss Random Variable distributions. Our results demonstrate that DP mechanisms reliably detect deviations when approximately 1 bit in every 8 to 16 is manipulated, with detection sensitivity varying significantly between bit-level biases and temporal correlations. We demonstrate that statistical detection of distributional anomalies does not necessarily correspond to actual privacy guarantee violations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.20133v1">Private communication from Pauli channels with no privacy</a></h3>
  
  <p><b>Published on:</b> 2026-09-17T12:26:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Uthirakalyani G, Pritam Halder, David Elkouss</p>
    <p><b>Summary:</b> A channel capacity quantifies the communication capability of a noisy physical process. In contrast to communication channels in the classical world, quantum theory makes this capability contextual. We show that two Pauli two-qubit channels, each with zero private classical capacity, can be used to transmit private information when used together. One is a two-qubit Pauli channel whose environment can reconstruct the receiver output up to matrix transposition; the other is an antidegradable channel. We obtain a similar result when the second channel is the 50% qubit erasure channel. A simple binary code built from rank-three mixtures of Bell states activates private communication. The main ingredient in our construction is a transpose-antidegradable channel that is not antidegradable.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.19740v1">Federated Learning Framework for Privacy-Preserving Kidney Stone Detection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-17T06:06:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Najiyya Younas, Omar Abdulkader, Yaser Ali Shah, Muhammad Jawad Ikram, Jebran Khan, Amaad Khalil</p>
    <p><b>Summary:</b> Recent innovations in deep learning have significantly enhanced the diagnosis of medical images, although they are based on the use of centralized data storage that pose severe threats to patient privacy and medical data security. To address this issue, this research proposes a Federated Learning (FL) model that is coupled with an optimized YOLOv8 network to detect the kidney stones on a computed tomography (CT) image and at the same time, protect privacy of the patients. The suggested system can help various medical organizations to jointly train a common model without exchanging the information about the patients. This is to ensure that data protection laws like GDPR and HIPAA are adhered to. The residual feature fusion and DropBlock regularization among other architectural improvements are also included in YOLOv8 to enhance detection robustness and minimize overfitting. Experimental analysis carried out on a distributed CT dataset demonstrated that the federated YOLOv8 model has a mAP at 50 of 0.733 and is able to keep the data confidential. Moreover, its lean design facilitates fast edge deployment and real-time inference across a clinical setting. Altogether, these findings indicate that Federated Learning is a safe and efficient solution to AI-assisted diagnosis in contemporary healthcare when combined with the use of sophisticated object detection models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.19456v1">Beyond Private Training: The New Landscape of AI Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2026-09-16T21:46:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sean Culatana, Kang Li</p>
    <p><b>Summary:</b> Retrieval-augmented systems increasingly rely on vector indexes that may retain deleted items in their search graph. Existing deletion interfaces can prevent deleted identifiers from appearing in returned results while still computing distances to their embeddings during graph traversal. We formalize this distinction as output safety versus traversal safety, and introduce TSD-AUDIT, a framework for auditing and enforcing traversal-safe deletion in graph-based approximate nearest-neighbor retrieval. On Faiss IndexHNSWFlat, native filtering leaves the number of distance computations unchanged relative to unfiltered search; at a 70% deletion rate, trace-faithful replay detects deleted-vector scoring in all 100 audited queries. Code inspection of hnswlib's mark_deleted path reveals the same scoring-before-liveness pattern. TSD-AUDIT enforces an alive-before-scoring invariant, repairs connectivity using only live candidates, and emits per-query scored-trace certificates that an independent verifier can check against the deletion snapshot. Under region-targeted deletion, TSD-AUDIT improves Recall@10 over native filtering by 4.3--42.2 percentage points across deletion fractions from 0.5 to 0.9, while remaining comparable under random deletion. These results show that output-only deletion audits can miss process-level exposure: auditing deletion in vector retrieval requires accounting for the vectors scored during search, not only the identifiers returned.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.20884v1">The Right Tool for the Job: On the Selection of Mitigations for GenAI Privacy Threats</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-16T21:36:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jonah Bellemans, Qianying Liao, Laurens Sion, Lieven Desmet, Wouter Joosen</p>
    <p><b>Summary:</b> Generative Artificial Intelligence (GenAI) has rapidly evolved from an experimental technology into a foundational component of modern software systems. However, as its adoption grows, protecting sensitive personal data becomes increasingly challenging. Specifically, GenAI systems not only amplify traditional privacy threats but also introduce new inference-based risks, such as constructing detailed user profiles from seemingly harmless inputs. In response, privacy threat modeling frameworks are beginning to capture GenAI-specific privacy threats with finer granularity. At the same time, a growing number of mitigation techniques have been proposed to address these threats. However, although knowledge of both threats and mitigations continues to mature, the problem- and solution-space have developed largely independently.
  This position paper argues that the primary challenge in GenAI privacy engineering is not the lack of knowledge about privacy threats or mitigation techniques, but the missing bridge between them. We decompose this gap into three sub-problems: (i) lack of fine-grained threat-to-mitigation mapping for GenAI systems, (ii) inapplicable solution-space assumptions in the GenAI context, and (iii) prioritization difficulty under GenAI constraints. We derive four recommendations for future mitigation-selection approaches, and outline a suggested approach that extends established threat-to-mitigation mapping methods to GenAI-specific threat characteristics. We propose a research agenda toward more systematic privacy mitigation selection for GenAI-based systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.19337v1">Personalized Federated Hierarchical Gaussian Processes for Privacy-Preserving Modeling of Heterogeneous Distributed Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-16T19:06:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xianjian Xie, Hao Yan</p>
    <p><b>Summary:</b> We present Personalized Federated Hierarchical Gaussian Processes (pFedHGP) for probabilistic regression and classification when data are distributed across heterogeneous clients. Each client's latent function decomposes into (i) a shared global component, (ii) a client-specific deviation that shares the global kernel structure, and (iii) a flexible local residual. Sparse inducing-variable approximations and federated variational inference keep raw data local while the server synchronizes only low-dimensional statistics for the shared component. Full predictive distributions support uncertainty-aware decisions. In application studies, pFedHGP attains perfect fault classification in press tonnage monitoring using 13.77% of labeled cycles and recovers geographic zones in federated air-quality modeling without centralizing station-level time series. An Instantaneous Linear Mixing Model viewpoint links the hierarchy to multi-output Gaussian processes for correlated sensors.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.19304v1">Decaf: A privacy preserving speech codec using speaker disentanglement and canonical voice conversion</a></h3>
  
  <p><b>Published on:</b> 2026-09-16T18:12:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Md Shakhrul Iman Siam, Dushyant Sharma, Stanislav Yu. Kruchinin, Peter Skala</p>
    <p><b>Summary:</b> We present DECAF, a privacy preserving neural speech codec that obfuscates a speaker's voice while preserving linguistic content while maintaining automatic speech recognition (ASR) performance at very low bitrates, inspired by decaffeination. At the transmitter end, speech is encoded into speaker independent content embeddings, which are compressed using residual vector quantization and transmitted without any speaker related information. At the receiver, a canonical speaker embedding, shared a priori between endpoints, is used for waveform reconstruction, enabling deterministic and consistent obfuscation of a speaker's voice. The proposed framework leverages an information bottleneck applied to self supervised representations, along with a separate speaker embedding branch, to achieve effective speaker content disentanglement. We further incorporate a CTC-based auxiliary objective, encouraging content representations that are well aligned with downstream ASR tasks. We show that DECAF operating at a bit rate of 0.5 kbps achieves an Equal Error Rate (EER) of up to 43.5% for a speaker verification system, while maintaining competitive ASR performance, yielding a relative reduction in word error rate of 33.2% compared to a state of the art method.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.18864v2">ASLEval: Measuring Privacy Exposure Displacement in LLM Agent Sessions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-09-16T16:03:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guosen Wu, Huizhen Huang, Guoxiong Long, Tao Huang, Chen Hou</p>
    <p><b>Summary:</b> Privacy evaluations of tool-using LLM agents often inspect a designated action, final response, or attacker report. These local proxies can miss unauthorized exposure elsewhere in a multi-step session and lack common ground truth across outlets, reports, and tool paths. We introduce privacy exposure displacement, the mismatch between a local evaluation proxy and target-grounded session exposure, and ASLEval, an authorization-aware framework that pre-registers a hidden target set, measures all declared visible exits, and reserves internal traces for diagnosis. Across multiple enterprise-style environments and independently implemented runtimes, we observe three recurring patterns. An expected-outlet-only view misses 46.9% of exposure recovered by the visible-exit union; attacker self-reports combine omissions with high false discovery; and schema-aligned internal evidence usually precedes visible exposure at the request/probe level. Reducing model-visible returns changes this path but can eliminate normal-task success. Independent human review supports the adjudication pipeline while identifying harder console and candidate cases. These findings motivate benchmarks that declare the complete visible boundary, ground claims in pre-specified targets and authorization, and report privacy together with task utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.19226v1">PAPC: Platform Mediation for Privacy-Propagation Externalities in AI-Mediated Workflows</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-09-16T14:40:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tao Huang, Guosen Wu, Chen Hou, Guolong Zheng</p>
    <p><b>Summary:</b> AI-mediated platforms coordinate work through LLM agents acting for different principals. In these workflows, privacy loss can be created before a final answer appears: a memory write, shared-workspace update, inter-agent message, or tool event may impose downstream exposure cost on another principal. We model this failure mode as a privacy-propagation externality, where the cost of a raw disclosure depends on topology and fanout as well as content. We present PAPC, a platform-mediated mechanism that intercepts information-moving events before they update shared state or external channels. PAPC combines policy, provenance, topology/fanout, privilege, and content signals to allow an event, release a policy-safe abstraction, quarantine raw content, block a transition, or narrow onward rights. The model explains why final-output control misses intermediate exposure costs and why high-fanout objects amplify propagation. Across retrieval-memory and multi-agent workflow benchmarks, PAPC preserves deterministic task completion and eliminates measured exact raw-value and external raw-value exposure. The results position event-level mediation as a platform-governance primitive for agent-mediated online work.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.18526v1">The Illusion of Local Privacy: Confidentiality Boundary Failures in Consumer LLM Serving Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-16T11:53:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Youssef Hamdi Zafan Ibrahim, Muhammad Ikram, Mohammed Khalaf Salama</p>
    <p><b>Summary:</b> Running large language models (LLMs) locally is often considered more private than cloud-hosted inference because user prompts remain on the device. We ask whether keeping inference local is, by itself, sufficient to keep those prompts confidential. Our results show that it is not: prompt confidentiality also depends on how the surrounding serving software handles prompt data before, during, and after inference. We examine four boundaries at which prompt confidentiality can fail in consumer local-LLM serving systems: model loading, runtime memory, wrapper-level persistence, and the serving interface. To study these boundaries, we develop LLAnalyzer, a measurement framework that tests each boundary separately and traces observed failures to the responsible software component. Applying LLAnalyzer to four open-weight model families and two consumer deployment platforms, we find markedly different behaviour across boundaries. In a 24-hour AFL++ campaign with more than 12 million executions, we observe no parser crashes or successful malformed GGUF loads within the explored state space. Runtime memory tells a different story: we recover prompts after inference because multiple plaintext representations survive in allocator-managed memory, and sanitisation reduces this residue without eliminating it. We also find that consumer wrappers can extend prompt lifetime through plaintext persistence. At the serving boundary, we uncover a previously undocumented authorization flaw in llama.cpp that allows one authenticated client to restore another tenant's saved conversation state; the attack succeeds in 200/200 controlled trials. Separately, shared prompt-prefix caching exposes a remote timing oracle that remains distinguishable under WAN conditions. We argue that local LLM systems need explicit guarantees for prompt lifetime, persistent storage, and tenant isolation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.18459v1">SEEK: Secure and Efficient Encrypted Keyword Search For Privacy-Preserving Messaging Protocols</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2026-09-16T10:54:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Soumyadyuti Ghosh, Michail Maniatakos</p>
    <p><b>Summary:</b> Encrypted communication protects sensitive user data but can facilitate harmful or unlawful exchanges, creating a trade-off between detecting dangerous messages and preserving end-user privacy. To address this, we propose SEEK, a practical and efficient encrypted keyword-search protocol for privacy-preserving messaging that combines homomorphic encryption with secure two-party computation (2PC). SEEK first partitions messages into ciphertext fragments with the minimum sufficient overlap, then homomorphically correlates them using encrypted keyword trapdoors. For long messages, this design can reduce sender-side encryption and upload overhead by up to two orders of magnitude over state-of-the-art baselines. It supports ASCII case-insensitive matching with one fixed-size encrypted trapdoor and one homomorphic multiplication per fragment, yielding up to 5.47x faster correlation computation than the strongest fragmentation-based baselines. SEEK then invokes 2PC-based selected decoding, blinded zero testing, and secure aggregation, revealing only the keyword presence-or-absence bit while hiding the keyword, its length, message contents, match counts, and locations. SEEK achieves 100% accuracy under case variations that result in exact-matching failures, without requiring additional trapdoors or online communication. We further realize SEEK as an end-to-end web and cross-platform mobile application. Prototype evaluation on a weekly messaging history yields an online computation time of 1.92 s per search, demonstrating the practical feasibility and efficiency of SEEK.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.17525v1">You Shall Not Pass into Ring-0! A User Privacy-Friendly Anti-Cheat Architecture for Personal Computers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-15T17:56:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Santosh Gokul Narayanan, Giovanni Paladino, Chuqi Zhang, Sangho Lee, Zhenkai Liang, Adil Ahmad</p>
    <p><b>Summary:</b> Kernel-level anti-cheats are effective against malicious player behavior in competitive video games, but raise significant user privacy concerns regarding installing unverifiable components at privileged modes (i.e., ring-0 in x86). While existing research has focused on improving the effectiveness of anti-cheats, the user privacy concern has been largely ignored. Tirith is an anti-cheat architecture that addresses this problem using two key ideas. First, instead of running video games within regular processes that players (as root admins) have control over, Tirith executes video games in Protected Virtual Machines that naturally sandbox computations from untrusted admins. Second, to monitor user behavior outside the sandbox (e.g., see if they are running malicious drivers), Tirith leverages a virtualization monitor that is trusted by both players and developers. Together, these ideas remove the need to run untrusted kernel-level anti-cheats, while providing the same level of protection compared to such solutions against a wide-range of common cheating mechanisms. The main challenge we face in implementing these ideas, however, is that the existing software stack for virtual machines is not designed to run video games and creates significant security and performance problems. We address these problems by proposing a security-focused Library OS kernel for games and an efficient graphics sharing pipeline for near-native rendering and display performance. In summary, without compromising on cheating behavior detection or performance, this work makes user privacy a first-class citizen in personal computers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.16915v1">ROSETTA: Efficient and Accurate Privacy-Preserving LLM Decoding via Hybrid CKKS/TFHE Evaluation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-15T09:51:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiangrui Yu, Baosheng Zhang, Liang Kong, Lin Ding, Yi Chen, Ye Yu, Mingzhe Zhang, Meng Li</p>
    <p><b>Summary:</b> Generative large language models (LLMs) have achieved state-of-the-art performance on many real-world tasks such as code generation and question answering. These models predominantly rely on an autoregressive decoding strategy that generates output tokens sequentially. However, their pervasive deployment raises serious privacy concerns, motivating private inference frameworks based on fully homomorphic encryption (FHE). A major limitation of existing FHE frameworks is their inefficiency in evaluating nonlinear operations, which incur substantial overhead and dominate the decode stage.
  In this paper, we propose ROSETTA, a hybrid CKKS/TFHE framework that overcomes this limitation. We first observe that nonlinear operations in the decode stage exhibit heterogeneous workload patterns, which can be handled effectively via a hybrid approach. We then realize this with two key contributions: 1) an adaptive segmented lookup-table protocol based on TFHE that enables efficient and accurate evaluation of nonlinear operations; and 2) a scheme-aware operator-selection framework that automatically assigns each nonlinear operator to CKKS or TFHE to minimize end-to-end decoding latency. We demonstrate that ROSETTA achieves up to $4.8\times$ Softmax speedup and $1.5$--$2.1\times$ end-to-end speedup over the SOTA framework CacheMir.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.16762v1">Equitable Partition Realizability for Dynamics-preserving and Privacy-aware Network Reconstruction</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2026-09-15T07:37:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Riccardo Porcedda</p>
    <p><b>Summary:</b> Degree-sequence realizability is the combinatorial basis of configuration models, but degree constraints alone do not ensure the preservation of graph dynamics. Hence, configuration models are unable to recover centrality measures, unless these are strongly correlated with the degree sequence. To address this matter, we introduce EP-realizability, the analogue problem induced by an equitable partition (EP): given the EP of a graph, decide whether the partition is realized by a simple undirected loopless graph and therefore construct such a graph. After defining the problem, we solve it by reducing it to sub-problems related to Havel--Hakimi and the Gale--Ryser theorem. We also face the challenge of solving the problem with an Approximate Equitable Partition ($\varepsilon$-EP), so that it is possible to reconstruct a network starting from partial and more privacy-preserving information. We evaluate privacy with edge overlap, deriving also, for our proposed $\varepsilon$-EP-realizability solution, a predictor for this metric. Experiments on Karate, Cora, CiteSeer and PubMed datasets show that our algorithm achieves a favourable and tunable privacy--utility trade-off, comparing the results with Havel--Hakimi algorithm, Newman's configuration model and a stochastic block model. Finally, both with real data and random graphs, we show that our algorithm has approximately linear time complexity with respect to the number of edges.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.16402v1">Privacy-Preserving Coordinated Operation of Multi-Player Industrial Network Using Secure Aggregation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computational Engineering, Finance, and Science-5BC0EB">
  <p><b>Published on:</b> 2026-09-14T22:15:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Akshdeep Singh Ahluwalia, Zachary Wilson, Jeffrey E. Arbogast, Can Li</p>
    <p><b>Summary:</b> Electrified chemical industries with operational flexibility can reduce operating costs by shifting production and distribution decisions in response to time-varying electricity prices. However, chemical plants operate within process networks where coordinated demand response can exploit flexibility across multiple stakeholders. Centralized coordination requires access to stakeholders' local scheduling models and proprietary operational data, often incompatible with data-privacy requirements. Distributed optimization with an independent central coordinator (ICC) avoids direct model sharing, but iterative exchange of coupling variables can still reveal private model parameters.
  We propose a privacy-preserving distributed coordination framework for coordinated demand response in industrial networks. The framework integrates secure aggregation with an ICC-based alternating direction method of multipliers (ADMM) algorithm, so plant-level messages are numerically masked and become useful to the ICC only after aggregation. We test the framework on a multi-plant industrial gas network in which three air-separation units jointly schedule production and shipments to shared customer regions. To support stable participation, we incorporate a two-phase revenue-sharing mechanism that reallocates savings so every plant improves relative to its decentralized status quo. In a 31-day rolling-horizon simulation with synthetic data representing heterogeneous electricity prices and demand, the coordinated policy reduces total network cost by 19.77% relative to decentralized operation and achieves a full-month cost within 3.08% of a centralized social-welfare-maximization benchmark. We further quantify a conservative worst-case collusion mode, showing how unmasked iterates and auxiliary information can expose private objective parameters.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.16232v1">Toward Governance-Aware Autonomous GIS: A Narrative Review of Ethical and Privacy Risks in LLM-Enabled GeoAI</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-09-14T18:58:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maya Subramanian, Devika Jain</p>
    <p><b>Summary:</b> Geospatial artificial intelligence (GeoAI) powered by large language models (LLMs) is expanding the capacity to query, generate, and interpret spatial information through natural-language interfaces and agentic autonomous GIS workflows. This capability creates governance challenges that general AI ethics discussions do not fully capture, including passive location inference from mobility traces, spatially structured bias amplification driven by spatial autocorrelation and scale effects, hallucinated spatial facts, and uncertainty compounding across multimodal geospatial inputs. This narrative review identifies eight recurring issues in LLM-enabled GeoAI: data provenance and consent, spatial privacy and inference risk, algorithmic bias and spatial inequity, spatial mechanisms as structural risk (spatial autocorrelation, the modifiable areal unit problem, and scale effects), LLM-specific technical risks, explainability, policy and regulatory gaps, and public enablement and workforce development. For each issue, we characterize the underlying mechanism, ground it in an illustrative example from the literature, and assess the current state of technical or institutional responses, ranging from largely unaddressed to actively debated or subject to emerging policy. Building on this synthesis, we propose a governance-aware architecture for LLM-enabled autonomous GIS that maps each issue to enforceable controls and auditable artifacts across the geospatial data lifecycle, illustrated through a worked flood-response routing scenario. The review highlights a persistent evidence gap: proposed responses remain largely conceptual, and field-tested evaluations of governance controls for LLM-enabled GeoAI remain limited. We close by outlining a research agenda emphasizing empirical validation, spatially specific interpretability tools, and workforce training aligned with these emerging risks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.15950v1">Privacy-Aligned Personalized Federated Learning with Compact Adaptation and Variable-Length Gaussian Communication</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-14T17:48:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yilin Xu, Chun Hei Michael Shiu, Chih Wei Ling, Linqi Song</p>
    <p><b>Summary:</b> Record-level differential privacy exposes a structural misalignment in personalized federated learning when client-specific variation is low-dimensional while training repeatedly releases high-dimensional updates. In this paper, we address this misalignment by releasing a private client context once and confining repeated adaptation to a fixed coefficient space. Beyond dimensionality reduction, the factorized generator induces an adaptive optimization geometry that reshapes noisy updates, and controlled ablations show that most of its private-training gain is retained by radial evolution. To further reduce the communication cost, we realize the Gaussian mechanism for coefficient updates directly through variable-length quantization with finite expected code length, so that the quantization error itself serves as the required privacy perturbation rather than extra distortion. Across MNIST and CIFAR-10, our design matches or outperforms full-model private adaptation across privacy budgets and client heterogeneity, while reducing protected uplink by a factor of 2.67 at \(\varepsilon=16\) on CIFAR-10 with comparable future-client accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.15885v1">Privacy-enhanced federated learning via asynchronous aggregation and local differential perturbation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computational Engineering, Finance, and Science-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2026-09-14T17:12:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhen Zhong, Shini Yang, Liesheng Wei</p>
    <p><b>Summary:</b> This study proposes a privacy-enhanced federated learning framework to address secure collaborative training in distributed data environments. The framework integrates Dynamic Differential Privacy (DDP), lightweight Homomorphic Encryption (HE), and Local Differential Privacy (LDP) mechanisms to ensure data privacy protection during model training. Additionally, the framework employs an asynchronous aggregation strategy with version control to support distributed training in asynchronous environments. Experimental validation on the CIFAR-10 and Purchase-100 benchmark datasets demonstrates that the method maintains high classification accuracy (up to 82.6%) even under stringent privacy constraints (ε = 0.1), while reducing communication overhead by 21.3% compared to FedAvg. Experimental results demonstrate that this framework effectively balances privacy protection and model performance in distributed machine learning scenarios, providing a scalable technical foundation for large-scale distributed collaborative computing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.15875v1">Private Information Retrieval With Arbitrary Privacy Requirements: Introduction and Capacity Results</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762"> 
  <p><b>Published on:</b> 2026-09-14T17:03:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohamed Nomeir, Shreya Meel, Sennur Ulukus</p>
    <p><b>Summary:</b> In this paper, we introduce the problem of private information retrieval (PIR) under arbitrary privacy requirements, in a graph-based storage system. This formulation is motivated by the server storage limitations, abundance of data (messages) and heterogeneous data privacy requirements. Under the arbitrary privacy requirement, each message has to be retrieved privately from a pre-specified subset of servers, where the subset always includes the servers storing it. Thus, each server is associated with a privacy set, which pre-specifies the message indices that should be privately retrieved from it. This setting is a generalization of the classical PIR setting, where the required message index needs to be kept private from all servers, i.e., there, the privacy set of each server comprises all message indices. Our setting is also a bridge between the newly formulated local PIR (LPIR) setting and the classical PIR setting, where in the former, the privacy set is exactly the set of stored message indices. In this paper, we derive general lower and upper bounds on the PIR capacity for general graphs, under certain privacy requirements, that capture the essence of both LPIR and classical PIR. Then, we focus on path and cyclic storage graphs under these and more fine-grained settings, for which we derive capacity results for certain cases, and establish lower and upper bounds for others. Their low degree allows for a more in-depth understanding of the new privacy formulation and admits more privacy requirement settings compared to other simple graphs. Finally, we introduce a new graph structure, the pyramid storage graph, to model server storage. Although this graph has never been investigated in the literature in any PIR context, it enjoys a nice symmetric structure for message storage and replication patterns.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.15871v1">LLM-Based Schema-Aware Split Learning for Privacy-Preserving Mental Distress Prediction Across Heterogeneous Surveys</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-14T16:59:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Md Khalid Syfullah, Alvi Ataur Khalil</p>
    <p><b>Summary:</b> Rising societal and lifestyle complexity has been linked to a growing prevalence of mental distress worldwide. Educational institutions, workplaces, clinics, etc. collect large volumes of mental health survey data to understand and reduce this burden. Collaborative analysis of such data could yield effective generalizable predictive models. Privacy constraints and varied survey designs (i.e., different questions, scales, and formats) hinder direct integration. We propose a schema-aware split learning (SL) framework that preserves privacy, using a large language model (LLM) as a shared semantic encoder to harmonize heterogeneous survey schemas across institutions. We serialize each survey record into a natural-language description, unifying disparate survey schemas into a common format. The LLM is fine-tuned for mental distress assessment via Low-Rank Adaptation (LoRA) and partitioned across client and server. Clients retain the raw survey responses locally and run only a lightweight front-end, so original records never leave the institution that collected them. The resource-intensive backbone runs on the server, minimizing client-side computation. Using LLaMA-3.2-3B-Instruct, the framework attains an average ANLS of 0.708 with only 2,000 training samples, surpasses federated learning (FL) in eight of nine settings, and cuts per-client computation by three orders of magnitude, while generalizing to unseen datasets. Overall, it enables accurate, privacy-preserving, and resource-efficient collaborative learning from heterogeneous mental health survey data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.15671v1">Don't Send What You Don't Need: Question-Guided Token Pruning as a Privacy Defense for Vision-Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-14T14:48:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Md Khalid Syfullah, Alvi Ataur Khalil</p>
    <p><b>Summary:</b> Visual Question Answering (VQA) with Vision-Language Models (VLMs) is increasingly used in privacy-sensitive and bandwidth-constrained settings. Federated Learning (FL), Split Learning (SL), and U-Shaped Split Learning (USL) keep raw data local, but transmitting all visual tokens across a model partition remains costly and can expose private information. We propose QPriv-VL, a question-guided, privacy-aware token-pruning framework for FL, SL, and USL that prunes visual tokens before transmission based on task utility and privacy sensitivity. Its core component is a lightweight Dynamic Threshold Predictor (DTP) that jointly estimates a sample-specific pruning ratio and a token-level retention mask in one forward pass. DTP combines question relevance, computed from cross-modal similarity between visual patches and the pooled question embedding, with a sensitivity signal derived from frozen DINOv2 features. This allows the model to suppress potentially sensitive regions while preserving patches useful for answering the question, without requiring sensitivity labels. We evaluate QPriv-VL on GQA, OK-VQA, VQAv2, SLAKE, VQA-RAD, and PathVQA against four privacy attack families: FSHA, FORA, iDLG, and attribute-inference membership inference attacks. DTP matches or outperforms fixed-ratio pruning while using substantially fewer transmitted tokens. On VQA-RAD, it reduces membership-inference attack success from 0.99 to 0.76-0.79, lowers FSHA and FORA reconstruction PSNR relative to fixed-ratio pruning, and preserves competitive VQA accuracy using about 40% of the original visual-token budget. A sensitivity exclusion ratio of 1.20 +/- 0.18 indicates preferential removal of privacy-sensitive patches, while explainability analysis shows that retention adapts to question semantics rather than generic visual saliency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.16095v1">RAG-CT: Mitigating Privacy Risks on Retrieval-Augmented Generation Systems via Scanning Prompt Distribution</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-14T14:44:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xingyu Lyu, Jiayimei Wang, Jianfeng He, Ning Wang, Yidan Hu, Yimin Chen</p>
    <p><b>Summary:</b> Retrieval-Augmented Generation (RAG) has emerged as a powerful paradigm for improving the quality of generated contents of Large Language Models (LLMs) by grounding responses in external knowledge, thus reducing hallucinations and factual errors. However, recent studies have highlighted a critical vulnerability: adversaries can exploit the retrieval process to extract personally identifiable information (PII) from the underlying corpus. To mitigate this risk, we propose a novel defense, RAG-CT, that identifies malicious queries by analyzing their entropy and margin distributions and using a score-based detection method. Extensive experiments with four state-of-the-art attack strategies and four defense baselines on two datasets show that our approach significantly reduces PII leakage while outperforming existing defenses. This work provides a lightweight yet effective mechanism to protect RAG systems against PII leakage without requiring modifications to the underlying LLM or retriever.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.15039v2">SpliTEE: Fast and Private LLM Inference by Coupling GPU-Assisted Trusted Execution Environments with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-14T04:55:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shashie Dilhara Batan Arachchige, Robin Carpentier, Hassan Jameel Asghar, Dali Kaafar</p>
    <p><b>Summary:</b> User prompts provided to large language models (LLMs) may contain sensitive or private information that can be misused by remotely deployed models, such as through inadvertent memorization during retraining. One way to protect user prompts is to execute the LLM inside a trusted execution environment (TEE), with the guarantee that the service provider has no access to computations performed within or information exchanged with the TEE. However, current TEEs are primarily CPU-based and significantly slower than GPUs optimized for LLM inference. To circumvent this, Tramer and Boneh (2019) proposed Slalom, which splits neural network inference between a TEE and an untrusted GPU and encrypts intermediate inputs sent to the GPU. We extend this split-inference architecture to LLM inference and instead protect intermediate inputs using differential privacy. We show that masking intermediate representations is necessary by showing that a prompt-reconstruction attack can recover prompts from these representations with nearly 80% accuracy. Our main contribution is a global sensitivity analysis of key LLM functions, which bounds the required scale of differentially private noise. Unlike encryption, differential privacy avoids quantization, allowing the LLM to remain in the floating-point domain. We also derive an upper bound on floating-point error from masking and noise cancellation in the TEE as a function of the privacy parameter epsilon. We implement our architecture using Intel TDX and evaluate it with two LLMs: Llama-3.2-3B and Qwen3-4B. Our split execution is nearly twice as fast as fully CPU-based inference inside TDX and 5-15 seconds faster than encryption-based Slalom while achieving higher accuracy. Finally, we demonstrate that prompt reconstruction, even with knowledge of the differential privacy mechanism, cannot recover more information than is contained in an unrelated prompt.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.14778v1">Privacy Preserving Gossip Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E">
  <p><b>Published on:</b> 2026-09-13T20:37:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Erkan Bayram, Mohamed-Ali Belabbas, Tamer Başar</p>
    <p><b>Summary:</b> We propose a decentralized privacy-preserving learning algorithm in which each agent holds a single private sample and a shared model. Samples are learned sequentially, and each update must preserve the endpoint mappings at previously learned samples while protecting private data. This gives each agent three roles: (i) a learner that updates the model parameters, (ii) a teacher whose sample is learned at the current iteration, and (iii) a protected agent whose sample has already been learned. We build on Tuning without Forgetting (TwF) method to preserve previously learned mappings and show that TwF provides an indistinguishability guarantee for the learner whenever the set of protected agents contains another sample with the same label. For the teacher, we formulate a minimax optimal control problem that models the differential privacy noise as a worst-case disturbance to prevent performance loss while maintaining the same level of privacy for the gradient. For the protected agents, we compute the projections locally and aggregate them using a private push-sum gossip protocol. We prove geometric convergence of the decentralized gossip algorithm and of the distributed projection for TwF.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.14745v1">PIMENTO: A Privacy Framework for Querying Text</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-13T19:17:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mushtari Sadia, Ang Chen, Amrita Roy Chowdhury</p>
    <p><b>Summary:</b> Currently, there are two state-of-the-art, complementary privacy guarantees: contextual integrity (CI) for what may flow, and differential privacy (DP) for what may be inferred. Yet neither maps cleanly onto natural language, leaving existing approaches unable to provide these guarantees for analytics over unstructured text. We address this gap with Pimento, a framework that takes three forms of natural language: text corpus, queries, and privacy policies; and grounds them into a relational database, creating a common substrate on which both guarantees can be enforced formally. With this design, we not only provide end to end privacy guarantees, but also improvement to utility through three key contributions: DP aware Text-to-SQL, which searches for correct queries requiring the least DP noise; CI aware Text-to-SQL, which compiles natural language policies into executable CI rules over the database; and a new privacy definition we call contextual differential privacy, which redefines the traditional DP neighborhood under CI, and yields a tighter smooth sensitivity bound. Across new benchmarks, Pimento selects the best query in 75.3% of cases (upto +45 points over baselines) and achieves zero leakage under correct policy grounding. To our knowledge, Pimento is the first framework to provide formal privacy guarantees for natural language analytics under CI, DP, and their composition.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.14697v1">Vulnerabilities in Personalization: Assessing Health Privacy Risks in ChatGPT Logs and Memory</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-09-13T17:53:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> S M Mehedi Zaman, Md Mozammel Hoque</p>
    <p><b>Summary:</b> As conversational LLMs become deeply embedded in daily life, users frequently disclose sensitive personal health information during routine interactions. We present a large-scale computational audit analyzing 179,057 conversations across India, Nigeria, Brazil, and Pakistan (N = 1,057) to evaluate personal health disclosures and background memory synthesis in ChatGPT. We find that 21.31% of audited conversations contain personal health data, with 3.62% posing high-to-extreme privacy risks involving stigmatized conditions, direct identifiers, and precise locations. When evaluating the memory entries of ChatGPT, we uncover a stark disconnect between corporate framing and system behavior: over 95% of profile entries are implicitly extracted without explicit user prompts or consent. Furthermore, background memory synthesis selectively condenses temporary, symptom-level disclosures into permanent diagnostic traits, stripping contextual integrity and amplifying re-identification risks. We conclude with sociotechnical design guidelines to restore user agency and consent-driven boundaries in stateful AI systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.14125v1">A Graph-Based Framework for Extending Metric Differential Privacy Mechanisms</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-12T20:09:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruiyao Liu, Chenxi Qiu</p>
    <p><b>Summary:</b> Metric differential privacy (mDP) is well suited to structured secret domains, but directly constructing utility-aware mechanisms over large or fine-grained domains is often computationally prohibitive. We study extension-based mDP design, where a mechanism is first specified on a finite set of seed records and then extended to a larger target domain. To our knowledge, this is the first work to systematically formulate extension as a general design paradigm for mDP rather than a method-specific construction. We present a graph-based extension framework, identify three requirements for correctness, local mDP constraints, overlap consistency, and successor-level mDP preservation, and show that, under these conditions, the induced global mechanism is well defined and satisfies $ε$-mDP on the target domain. We further instantiate the framework with a tree-based extension algorithm for multi-resolution grids, where multi-dimensional extension is realized through one-dimensional interpolation and dimension-wise composition. Experiments on road-map datasets demonstrate that our approach achieves a strong utility-scalability trade-off while preserving exact mDP guarantees.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.14003v1">Confuse the Model, Control the Flow: Understanding and Mitigating Privacy Leakage from LLM Agents with Information Flow Control</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-09-12T15:31:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Minsun Shim, Ramisha Raida Karim, Ruthwik Jakkula, Kaiwen Zhou, Xin Liu, Xin Eric Wang, Zhou Li</p>
    <p><b>Summary:</b> Personal AI agents built on large language models (LLMs) are increasingly given access to a user's private data and communications in order to provide personalized assistance. This access creates a persistent privacy risk: the agent must decide whether a given sensitive information should be disclosed to a particular party. Existing defenses address this by making the agent's backend LLM more privacy-preserving through stronger system prompts, training, or explicit consent-checking procedures, but this approach has a structural challenge: whenever enforcement is a judgment the LLM makes over the same conversational context an adversary controls, the enforcement mechanism and the attack surface coincide. We demonstrate this against existing defenses with three new attacks that require only ordinary agent interaction and no prompt injection: Collaborative Workspace Lure reframes an extraction attempt as collaborative work; Semantic Obfuscation Attack induces disclosure through omission rather than through anything the agent writes; and Channel Decoupling Attack splits the extraction request and the disclosure across independent channels. All three achieve substantially higher leak rates than the attacks these defenses were originally designed to withstand. Guided by this observation, we present FLOWSEAL, a defense that enforces confidentiality through a tool-level interceptor outside the LLM's context, grounded in data provenance and an information-flow-control lattice with controlled declassification. Evaluated across three benchmarks, five prompt-based baselines, and eight attacks, including a real agent executing live tool calls through MCP, FLOWSEAL reduces leak rates to near zero (e.g., 52.2% to 0.5% against Collaborative Workspace Lure) while preserving task utility, regardless of the underlying LLM backend.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.13873v1">PriMobiBench: Characterizing Visual Privacy Leakage in VLM-Driven Mobile GUI Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-12T10:55:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qihang Cen, Tianshuo Cong, Da Song, Xinlei He, Jiaxing Song, Ke Xu, Qi Li</p>
    <p><b>Summary:</b> Mobile GUI agents increasingly rely on Vision-Language Models (VLMs) to automate smartphone tasks by interpreting screenshot streams. However, this design introduces serious and underexplored privacy risks, including direct leakage of sensitive on-screen information and unintended user profiling. The absence of standardized benchmarks makes it difficult to quantify these risks in realistic mobile agent workflows. To address this gap, we propose PriMobiBench, the first benchmark for systematically evaluating privacy leakage and visual profiling in screenshot-driven mobile agents. It provides a unified pipeline for data generation, agent trajectory construction, and multi-model evaluation. We also introduce MobiLeak, a dataset of execution traces from 16 apps, covering 25 privacy attributes with 2,960 embedded privacy instances. Our results reveal substantial risks: (1) VLMs can directly extract sensitive information with up to 82.5% success rate; (2) beyond explicit leakage, they can infer user profiles from aggregated visual evidence with approximately 70% success. We further propose a mitigation that masks privacy-sensitive but task-irrelevant UI elements before cloud processing, reducing profiling success by up to 58% with only approximately 8% performance loss. Overall, our work provides the first systematic benchmark for visual privacy risks in mobile GUI agents, demonstrates that both leakage and profiling are feasible at a highly concerning level, and offers a practical direction for mitigation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.13823v1">Semantic Privacy Protection with Utility Preservation for 3D Point Clouds</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-09-12T09:15:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jinchang zhang, Jiakai Lin, David Crandall, Guoyu Lu</p>
    <p><b>Summary:</b> Point cloud data face serious semantic privacy risks during acquisition, transmission, and cross-institutional sharing. Existing methods mostly rely on geometric perturbation or destructive encryption, which can reduce the recognizability of the original class but often impair downstream usability. This paper proposes a class-transfer-based semantic encryption framework for point clouds, aiming to conceal original class information while preserving task utility and supporting authorized recovery. Specifically, we construct a unified latent space with a shared-backbone Normalizing Flow, and combine LoRA and FiLM to achieve parameter-efficient class-conditional adaptation. We further introduce diffusion-guided flow alignment to regularize the latent distribution, construct an energy-based category transition graph, and obtain an optimal class-transfer table through global matching. Then, a latent-space Neural ODE continuously evolves source-class latents into target-class latents, which are decoded into target-class point clouds through the inverse flow. We adopt attacker-oriented metrics, including New-Class Recognition Rate (NCRR), Original-Class Leakage Rate (OCLR), and Original Label Recovery Rate (OLRR), to evaluate privacy and utility. Experiments on classification and segmentation benchmarks show that the proposed method achieves controllable semantic transformation, effectively reduces original-class semantic leakage, preserves downstream learnability in the protected domain, and supports reliable authorized reconstruction.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.13499v1">Canaries in the Bank: Auditing User-Level Privacy in Private Evolution</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-11T20:04:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sai Aparna Aketi, Enayat Ullah, Shripad Gade</p>
    <p><b>Summary:</b> Private Evolution (PE) generates high-fidelity synthetic data in federated settings without exposing users' raw data. It aggregates clipped user votes over a shared candidate bank into a differentially private histogram, with noise calibrated to the worst-case user contribution. However, it is unclear whether an adversary can realize this worst-case privacy loss while following the PE protocol. We introduce a protocol-aware empirical audit in which the server commits to a single shared candidate bank and replaces roughly 1% of its entries with probes derived from a known, non-private canary. We evaluate eight attacks, including an unchanged-bank baseline, exact copies, plausible paraphrases, and high-entropy synthetic nonces. Experiments on Yelp and Sentiment140 show that natural-text attacks remain substantially below the theoretical DP bound, while nonce-based attacks yield considerably stronger bounds and come closest to the mechanism's privacy ceiling. These results quantify the gap between formal worst-case privacy and leakage achievable through protocol-valid candidate-bank manipulation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.13418v1">High quantum local differential privacy breaks entanglement</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-09-11T18:29:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sujeet Bhalerao, Theshani Nuradha, Felix Leditzky</p>
    <p><b>Summary:</b> Differential privacy provides a mathematical framework for guaranteeing privacy for sensitive data. In quantum information processing, the interaction of privacy constraints with quantum resources such as entanglement remains a question of interest. Given that the utility of many protocols, and often the presence of a quantum advantage, relies on quantum resources such as entanglement, it is crucial to understand when a privacy requirement for a quantum channel is compatible with the channel's ability to preserve entanglement. We study this question for quantum local differential privacy (QLDP). Our main result shows that every $\varepsilon$-QLDP channel with a $d$-dimensional input is entanglement-breaking whenever $\varepsilon\leq\log\frac{d}{d-1}$. We also prove an approximate version for $(\varepsilon,δ)$-QLDP, where channels in the same high-privacy regime are close in diamond norm to an entanglement-breaking channel. We further prove a composition result for a collection of private quantum channels having entangled inputs and global measurements in the high-privacy regime. Finally, we apply our results to private quantum learning theory. We prove that any learning protocol using arbitrary quantum memory on copies of the output of an entanglement-breaking channel can be simulated by a protocol that measures the corresponding unprocessed input copies one at a time while storing only classical information. Combining this result with our high-privacy entanglement-breaking theorem, we show that under sufficiently private local noise, a learning protocol with quantum memory for purity testing and bipartite product testing is subject to the sample complexity lower bounds for protocols with single-copy measurements on the noiseless tasks. We also obtain stronger sample complexity lower bounds when a single highly private channel acts on the entire multipartite input.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.13393v1">Privacy-Preserving Deep Joint Source-Channel Coding with In-Loop Concept Erasure</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-11T18:02:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rami Eid, Maria Slim, Mariette Awad, Hadi Sarieddeen</p>
    <p><b>Summary:</b> Deep joint source-channel coding (DeepJSCC) transmits learned semantic features efficiently but can leak sensitive attributes such as gender, race, or speaker identity. We propose LEAPSC (LEACE-in-the-loop privacy for semantic communication), whose core contribution is the integration of in-loop least-squares concept erasure (LEACE) within a variational information bottleneck (VIB) encoder. By periodically refitting the projection operator during training, LEAPSC couples the encoder dynamics to the erasure mechanism, driving attribute-conditional mean differences toward zero within each task-label group on the fitting sample. Additional components, namely conditional value-at-risk (CVaR) tail-sensitive privacy, feature-wise linear modulation (FiLM) signal-to-noise ratio conditioning, and Lagrangian dual ascent, improve robustness across channel conditions and over the high-leakage tail of samples. On CelebA, FairFace, and Google Speech Commands, LEAPSC reaches task accuracy of 0.862, 0.755, and 0.925 respectively, with attacker accuracy at or below the label-only floor on CelebA (0.548 vs. floor 0.580) and within 2 percentage points (pp) of chance elsewhere, improving over an information-bottleneck adversarial baseline (IBAL) at a matched 52-epoch budget by +3.6, +2.5, and +1.3 pp (Welch's t-test, p=0.019 on CelebA).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.12571v1">PIA-Bench: Towards Automated Privacy Impact Assessment with Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-11T08:16:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiamin Zheng, Hao-Ping Lee, Luo Mai, Jingjie Li</p>
    <p><b>Summary:</b> Privacy impact assessment (PIA) is a critical instrument for institutions to proactively identify privacy risks and develop mitigation strategies before system deployment. While mandated across regulatory and institutional contexts, executing PIA requires extensive privacy and technical expertise, posing a particular challenge for teams without access to such resources. Prior work shows the potential of leveraging large language models (LLMs) to assist practitioners' privacy decisions, but little is known about how accurately and reliably LLMs can automate PIA. To this end, we develop PIA-Bench, the first open benchmark for evaluating LLMs on real-world PIAs. We first audited 499 expert-authored PIAs published by US federal agencies and curated 73 structured PIAs, comprising a total of 451 privacy risk and 831 mitigation items, to evaluate LLMs' ability to assess privacy risks and propose mitigations of complex systems. Our results show that off-the-shelf LLMs produce meaningful assessments and identify avenues for future improvement. Finally, we call for improving domain-specific workflows for LLM agents, developing accountable LLM infrastructure, and designing new quality standards for PIAs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.12508v1">Differential Privacy Meets Fixed Parameter Tractability: Algorithms and Lower Bounds</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-11T07:13:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pritish Kamath, Ravi Kumar, Pasin Manurangsi</p>
    <p><b>Summary:</b> We study combinatorial optimization problems under the constraint of $ε$-differential privacy ($ε$-DP). Given the strong lower bounds for explicitly outputting solutions, we work within the implicit representation framework of Gupta et al. (SODA 2010), where a private polynomial-time randomized "encoder" generates a representation of a solution, and a "decoder" uses this representation along with the input to extract a valid final solution.
  In this work, we generalize this framework by allowing the encoder to run in fixed-parameter tractable time. This circumvents approximation barriers inherent to polynomial-time algorithms and obtains improved guarantees for many fundamental combinatorial optimization problems.
  Finally, we establish the first representation-independent lower bounds for our framework. Assuming a non-uniform variant of the Gap Exponential Time Hypothesis, for sufficiently small $ε> 0$, we prove that no $ε$-DP encoder-decoder pair can achieve certain approximation guarantees, if the decoder runs in subexponential time. We further provide representation-dependent lower bounds that hold even for larger $ε$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.12415v1">Why User Studies and Participant Experience Reporting Matter for VR Motion Privacy?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-11T04:08:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Azim Ibragimov, Eric D. Ragan</p>
    <p><b>Summary:</b> Public VR game leaderboards contain tracked motion recordings uploaded by hundreds of thousands of users. Once uploaded, these recordings are accessible to anyone and create privacy risks (i.e., identification and profiling). Prior work has proposed mechanisms that modify tracked movement to reduce these risks. Their utility is commonly evaluated through physical deviation, where smaller deviations indicate better utility, while user studies are less common. However, it remains unclear how well physical deviation explains users' acceptance of a mechanism compared to user studies. We examine this through a user study of three VR motion privacy mechanisms at five physical deviation levels. We find that user studies explain substantially more variation in mechanism acceptance than physical deviation, although physical deviation remains significant. We also find that prior VR experience and exposure to VR privacy mechanisms significantly affect acceptance. We recommend combining physical deviation with user studies and reporting participants' prior experience.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.12378v2">An Open-Source End-to-End FHE Implementation for Privacy-Preserving Llama 3 8B Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-11T02:51:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuhang Fan, Yusi Chen, Kanyu Ye, Zhuoran Ji</p>
    <p><b>Summary:</b> Cloud LLM services typically require users to send prompts to a model provider, creating a privacy risk. Fully homomorphic encryption (FHE) lets a server perform inference without decrypting the input, but representing data as ciphertexts adds storage and computational overhead. In CKKS-based LLM inference, the packing scheme maps logical tensors to ciphertexts and slots. It therefore determines the ciphertext count and the homomorphic cost of linear layers, and it constrains how data pass between linear layers, attention, and nonlinear computation. As models and sequences grow, inefficient layouts accumulate encoding, compute, and layout-conversion overhead.
  We present Odin, an FHE inference system that co-designs ciphertext packing and model execution for Llama. Starting from a THOR-style baseline whose bottleneck is weight encoding, Odin uses a feature-major cross-layer layout to unify residual connections and layer interfaces, and builds transient intra-operator layouts for linear projections and attention. This reduces redundant plaintext encoding of weights in wide projections. Within attention, QK^T produces scores that Softmax can consume directly, and PV consumes the resulting probabilities, avoiding intermediate repacking. For nonlinear ops, we use minimax polynomial approximation with input-range control and joint error allocation guided by model quality, reducing polynomial degree and multiplicative depth. To our knowledge, Odin is the first open-source end-to-end GPU CKKS implementation of Llama-3.
  With Llama-3-8B weights and a 128-token input, Odin evaluates all 32 Transformer layers on a single NVIDIA H100 80 GB GPU. Server-side end-to-end FHE evaluation takes 366.4 s and 58.9 GiB peak device memory. Under the same model, input, CKKS parameters, and hardware, THOR takes 1651.9 s, a 4.51x speedup.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.12320v1">AIM: A Privacy-Aware Interoperable Memory Framework for Multi-Agent Multi-User LLM Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-11T01:00:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zachary Johnson, Nigel Boachie Kumankumah, Somya Chatterjee, Tejas Sathyamurthi, Min Chen, Xinyi Alice Li, Xiao Wang, Emily Morgan Gelchie, Jessica Lin, Sadid A. Hasan, Sulaiman Vesal</p>
    <p><b>Summary:</b> Traditional large language models (LLMs) are scoped to individual user sessions, limiting their knowledge to a single conversation and preventing them from learning user preferences that evolve over time. Existing agentic memory systems address this limitation but generally operate at the individual-user level, restricting the public knowledge that could be shared across users to improve downstream responses. We introduce AIM (Agentic Interoperable Memory), a unified, privacy-aware memory framework that enables multi-agent, multi-user LLM systems to persistently manage private and shared memory. AIM dynamically classifies information as private, scoped to one user and inaccessible to others, or public, accessible to all users. It enforces index-level access controls so that private memories are retrievable only by their owner, protecting sensitive data while allowing beneficial shared knowledge to improve coordination and consistency. We also introduce MUMBench (Multi-User Memory Benchmark), a dataset of multi-user interactions containing private and shareable information across four domains. To our knowledge, MUMBench is the first public dataset designed to evaluate multiple memory operations, including retrieval, creation, update, and deletion, in a multi-user environment. Across three independent runs on MUMBench, AIM achieves 96.0% visibility classification accuracy, 58.8% strict operation accuracy, and 70.5% state-aware operation accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.12067v1">Scalable Discrete-to-Continuous Channel Simulation for Compression and Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-09-10T18:01:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joseph Rowan, Buu Phan, Ashish J. Khisti</p>
    <p><b>Summary:</b> Channel simulation has recently emerged as a useful component in machine learning systems where samples from a prescribed probability distribution are to be compressed. Yet, general channel simulation algorithms often suffer from high computational costs, random stopping times or, in the worst case, can require generating an infinite number of shared random samples. We introduce a scheme for both exact and approximate simulation of discrete-to-continuous channels which conversely uses a fixed number of random samples, and therefore has a runtime independent of the channel and the input. Unlike existing channel simulation schemes which generate a sequence of independent samples from a proposal distribution, our approach generates one sample, or alternatively a fixed number of samples, from each potential target distribution. We then apply a latent permutation to the samples before performing sample selection using an exponential race. Our scheme provides a flexible tradeoff between the number of generated samples and the compression rate. Using polar and multilevel coding, we scale our approach to handle long blocklengths in $O(n \log n)$ time in order to benefit from reduced per-symbol overhead. We conclude by demonstrating applications to variable-rate compression with stochastic VQ-VAEs and communication-efficient differentially private distributed mean estimation via exact simulation of the Gaussian mechanism.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.11794v1">Second-Order Expansion of Privacy Amplification Under f-Divergence Criteria</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-09-10T16:47:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mario Berta, Hao-Chung Cheng, Marco Tomamichel</p>
    <p><b>Summary:</b> We derive the second-order asymptotics of randomness extraction from memoryless sources with side information under security criteria based on a broad class of Csiszàr f-divergences, treating both a fixed reference side-information marginal and optimization over that marginal. The conditional varentropy decomposes into fluctuations of the conditional entropy across different values of the side information and the average variance of the conditional surprisal for each value. Without marginal optimization, these contributions yield a Gaussian-mixture second-order profile. With marginal optimization, they combine into the total conditional varentropy, yielding a single Gaussian profile. As corollaries, we obtain second-order expansions for Rényi-entropy criteria of all orders $α\in (0,1)$ and recover the known expansion for total variation distance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.11780v1">Predicting Privacy Leakage from Weight Spectral Density</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Neural and Evolutionary Computing-5BC0EB">
  <p><b>Published on:</b> 2026-09-10T16:34:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Richard J. Preen, Jim Smith</p>
    <p><b>Summary:</b> Membership inference attacks (MIAs) are widely used to audit the privacy disclosure risk of machine learning models, however current state-of-the-art attacks require training computationally expensive shadow models, making large-scale privacy evaluation impractical. In this work, we investigate whether inexpensive spectral metrics derived from the heavy-tailed self-regularisation framework can serve as proxies for MIA vulnerability. We evaluate several WeightWatcher spectral metrics on image and tabular classification tasks and compare their relationship with MIA privacy leakage against conventional measures of generalisation. Across datasets, stable rank exhibits a strong positive correlation with overall MIA success, while Log alpha-Norm shows a consistent negative correlation with MIA vulnerability at the low false-positive regime. These associations are observed to be stronger than those obtained using the generalisation gap. The results indicate that neural network spectra may contain information about privacy leakage that is not fully captured by conventional measures of overfitting, motivating spectral analysis as a promising direction for scalable privacy auditing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.11777v1">Differentially Private EEG Feature Anonymization: A Privacy-Utility Case Study in Clinical Neurophysiology</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2026-09-10T16:31:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Noman Sadiq, Mohsen Toorani</p>
    <p><b>Summary:</b> Clinical electroencephalography (EEG) data are valuable for healthcare research and for developing artificial intelligence (AI)-based clinical decision-support systems, but EEG recordings and derived features may contain sensitive patient-specific information. This creates privacy risks when data are reused, analyzed, or shared across clinical and research environments. Conventional anonymization methods are often insufficient for high-dimensional biomedical signals, since removing direct identifiers does not necessarily prevent re-identification, linkage, or inference risks. At the same time, strong privacy protection may distort clinically relevant signal characteristics and reduce data utility. This paper studies subject-level differential privacy for protecting clinical EEG-derived feature representations using Gaussian and Laplace perturbations. The proposed framework considers three deployment scenarios: client-side anonymization, centralized server-side anonymization, and decentralized local training. Following EEG preprocessing and feature extraction, Gaussian and Laplace perturbations are applied to the resulting patient-level EEG feature representations. The Laplace experiments evaluate the implemented noise scales, while the scales required for formal full-vector calibration are derived separately. The effects of both perturbations are assessed using statistical utility measures and a downstream machine-learning-based utility check. The results show that differentially private perturbation can be integrated into EEG processing workflows, but the selected mechanism, privacy parameters, and sensitivity calibration strongly influence data utility. The study highlights the practical privacy-utility trade-off in DP-based EEG feature anonymization and the challenges of preserving downstream utility in small and imbalanced clinical EEG datasets.</p>
  </details>
</div>

