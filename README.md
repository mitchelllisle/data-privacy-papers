
<h2>2026-08</h2>

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
  <h3><a href="http://arxiv.org/abs/2608.28950v1">The Web-CLI: Verifiable Privacy for Tools, Models, and Inference Engines in the Browser</a></h3>
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
  <h3><a href="http://arxiv.org/abs/2608.28198v1">Performative Privacy: When Differential Privacy Maximizes Utility</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> 
  <p><b>Published on:</b> 2026-08-28T11:13:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Uddalak Mukherjee, Edwige Cyffers, Yann Chevaleyre</p>
    <p><b>Summary:</b> Privacy-preserving learning is often motivated by the idea that protecting users' data can preserve trust and thus participation, improving utility in the long term. However, this claim has not been formalized so far. In parallel, performative learning provides a framework for studying learning systems whose deployment affects the data they later observe. In this work, we bring these two perspectives together and introduce \emph{performative privacy}, where data leakage reduces future participation. We study a simple model where agents repeatedly contribute data for mean estimation but may leave the system when their data is leaked. Privacy is implemented through differentially private mechanisms, creating a trade-off between estimation noise and future participation. We show, through a theoretical study of the dynamics and numerical experiments, that a finite privacy budget can outperform non-private estimation in the long term when the feedback loop between leakage and participation is sufficiently strong. This provides first evidence that differential privacy can be optimal not only as a protection mechanism, but also from the perspective of long-term utility.</p>
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
  <h3><a href="http://arxiv.org/abs/2608.17147v1">Picture the Epsilon: Pursuing Identity-Level Privacy Guarantees for Images</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-17T21:30:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arman Zareian Jahromi, Vishnu Bondalakunta, Mohammad Akbar Bin Shah, Naimul Haque, Shuangqing Wei, George T. Amariucai</p>
    <p><b>Summary:</b> Image-to-image face generators are widely used, and visual dissimilarity between their outputs and source images is sometimes treated as evidence of privacy. Auditing whether these systems satisfy formal identity-level (epsilon, delta)-differential privacy requires choosing among several distinct routes for converting embedding-space observations into estimates or bounds on the differential privacy parameter epsilon. We present a comparative study of four such audits applicable to pre-trained, black-box face generators: a Gaussian-mechanism reading of per-identity sensitivity (GaussMech); a per-dimension kernel-density log-ratio aggregated by basic composition (KDE-LR); an analytical population-level lower bound on pure-DP epsilon derived from the maximum mean discrepancy via the total variation distance (MMD-TV); and a hypothesis-testing evaluation of a cross-validated classifier's out-of-fold ROC (ROC-HT). For each method we make explicit its assumptions, hyperparameter dependence, finite-sample limitations, and the regime in which its epsilon estimate is informative. Applied to FaceFusion and InstantID across multiple identity encoders and reference datasets, the audits consistently reveal substantial identity distinguishability while reporting markedly different epsilon estimates that reflect each method's distinct assumptions and finite-sample treatment. In this high-distinguishability regime, the experiments do not support a reliable ranking of the four methods. Their relative trade-offs should be evaluated on partially private mechanisms, which we identify as the natural next study. The resulting framework places these audits in a shared identity-level audit setting and clarifies how their assumptions and finite-sample treatments shape the resulting differential privacy estimates.</p>
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


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.13270v1">Exploiting Phase Noise for Sensing Privacy in ISAC Systems</a></h3>
  
  <p><b>Published on:</b> 2026-08-13T14:07:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Musa Furkan Keskin, Kawon Han, Henk Wymeersch, Christos Masouros</p>
    <p><b>Summary:</b> We investigate sensing privacy in orthogonal frequency-division multiplexing (OFDM) integrated sensing and communication (ISAC) systems under the impact of phase noise (PN) arising from local oscillator (LO) imperfections. Specifically, we consider an ISAC scenario comprising a legitimate monostatic ISAC transceiver (Alice), an eavesdropper performing unauthorized bistatic sensing (Eve) and a communication user (UE), each equipped with a non-ideal LO. To characterize sensing performance in the presence of PN, we carry out a misspecified Cramér-Rao bound (MCRB) analysis of monostatic and bistatic range estimation at Alice and Eve, whose differential PN processes are self-correlated (delay-dependent) and cross-correlated (delay-independent) due to the use of a shared and an independent LO, respectively. Simulation results reveal three-way trade-offs among legitimate monostatic sensing at Alice, unauthorized bistatic sensing at Eve and communication to the UE under PN, governed by the LO quality at Alice. Through the LO asymmetry between Alice and Eve, worsening LO quality at Alice can significantly enlarge sensing privacy gap in her favor, especially for nearby targets, with only a moderate reduction in data rate in noise-limited regimes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.12911v1">Beyond Visual Evidence: Revealing and Mitigating Relational Privacy Leakage in Document MLLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Multimedia-5BC0EB">
  <p><b>Published on:</b> 2026-08-13T07:53:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Beining Xu, Hairui Wang, Jiaxin Wang, Changsheng Chen, Anirban Chakraborty</p>
    <p><b>Summary:</b> While the privacy risks of multimodal large language models (MLLMs) have drawn significant attention, the unique vulnerabilities of domain-specific MLLMs remain largely underexplored. Focusing on document understanding MLLMs for identity document processing, this paper investigates the privacy issues inherent in Key Information Extraction (KIE) tasks. We reveal that when input images lack sufficient visual evidence, these models often rely on memorized field relations from training data to infer missing content, thereby leaking multiple correlated fields containing sensitive personal information. To mitigate this risk, we make three key contributions.First, we propose the Dynamic Relational Unlearning Framework (DRUF) which comprises a Relational Decoupling Unlearning (RDU) module and a dynamic set update mechanism. It suppresses the leakage of high-risk field pairs while preserving KIE performance.Second, we introduce DocPrivacyBench, a novel benchmark to systematically evaluate a model's susceptibility to privacy leakage under conditions of absent or minimal visual evidence.Third, we evaluate three MLLMs and six unlearning methods using this benchmark, assessing both post-unlearning leakage suppression and utility preservation.Our results demonstrate that existing MLLMs consistently exhibit privacy leakage when visual evidence is scarce, particularly on noisier datasets. In contrast, DRUF outperforms the strongest baseline by improving leakage suppression by 4.8 percentage points, effectively mitigating privacy risks while maintaining robust document information extraction performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.12675v1">Privacy-Preserving RAG by Concealing Sensitive Information from External LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-13T00:23:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Saleh Almohaimeed, Saad Almohaimeed, Mousa Jari, Fahad Alotaibi, Khalid A. Alobaid</p>
    <p><b>Summary:</b> Retrieval-Augmented Generation (RAG) is widely used to improve the performance of Large Language Models (LLMs) in answering user queries. Existing privacy research on RAG has focused on preventing unauthorized users from accessing sensitive data. However, another important problem that is often overlooked in RAG privacy research is that external generators have access to the query and the retrieved documents, which may contain confidential information that could potentially be misused or accessed for unintended purposes. In this paper, we introduce the Sensitive Entity Alias Generator (SEAG), a privacy-preserving framework that empowers users to utilize powerful third-party generators without disclosing sensitive information. SEAG introduces a lightweight model that locates sensitive entities, generates corresponding aliases, and constructs an entity replacement table. The table is used to replace sensitive words in the user's query and in the retrieved documents before they are forwarded to an external generator. For this purpose, two datasets were constructed: one for fine-tuning SEAG models to generate entity replacement tables, and another for evaluating the entire SEAG framework. The experimental results demonstrate the success of the SEAG framework. As for the User metric, which measures the ability of the model to provide a correct response to the user while hiding sensitive information from the external generator, all SEAG models achieved over 80% accuracy. Additional analysis further evaluated the ability of SEAG models Qwen-3, LLaMA-3.2, and Phi-4 to hide all sensitive entities within given documents. The results show good performance with total accuracies of 77.83%, 76.73%, and 74.91%, respectively.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.12511v1">SoK: From Generation to Consumption of Privacy Documents in Software Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-08-12T18:39:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shidong Pan, Clark LaChance, Zhen Tao, Sepideh Ghanavati</p>
    <p><b>Summary:</b> Privacy documents (e.g., privacy policies) are a central mechanism through which digital services disclose data practices and seek user consent. Over the past decades, research on privacy documents has expanded significantly, encompassing not only traditional privacy policies but also short notices (e.g., privacy labels) and interface-level transparency mechanisms. As this research area continues to grow, it has become increasingly difficult to obtain a coherent view of how privacy documents are created, analyzed, evaluated, and maintained across their lifecycle. This SoK provides a unified, lifecycle-oriented view of privacy documents from a software engineering perspective. We systematically review and analyze 290 papers published between 2010 and 2025, organizing them around five research questions that examine how privacy documents are (1) defined and scoped, (2) generated, (3) analyzed and extracted, (4) checked for inconsistencies and noncompliance, and (5) evaluated and improved for usability. Building on our findings, we identify 15 key research trends and 21 open opportunities. We further chart four broader research directions that highlight (i) emerging challenges in AI-centric platforms, (ii) the need for diverse and up-to-date data foundations, (iii) LLM-based unified policy-code analysis, and (iv) dual usability for end-users and developers. We hope this SoK provides a shared foundation for future research on privacy policies and privacy documents.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.14724v1">Privacy-Preserving Dataset Curation for Kuala Lumpur Urban Traffic: Grounded Vision-Language Detection with Spatial Vehicle-Context Filtering</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-12T13:45:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohammed Abdul Al Arafat Tanzin, Rudzidatul Akmam Dziyauddin</p>
    <p><b>Summary:</b> The rapid advancement of intelligent transportation systems and autonomous driving relies heavily on multi-modal urban traffic datasets. However, curating high-fidelity video imagery in complex tropical urban environments---specifically Kuala Lumpur, Malaysia---presents severe challenges for Personally Identifiable Information (PII) anonymization due to high motorcycle density, dark acrylic license plates, dynamic camera tilt, and extreme tropical glare. We propose an automated anonymization framework tailored for the Kuala Lumpur Road Dataset, captured via a mobile cycling platform at 2 FPS. We document how legacy Haar cascades and YOLOv8 fail under these conditions---generating false positives on background elements while missing rotated or occluded targets. Our architecture resolves this by integrating Grounding DINO---a zero-shot open-set vision-language transformer---with a novel Spatial Vehicle Region of Interest (ROI) Containment Engine. By requiring license plate centroids to reside within validated vehicle boundaries, the pipeline suppresses environmental false positives while automatically obfuscating faces, heads, and license plates. An initial evaluation on 1,266 frames demonstrates a $\sim$95\% success rate, with remaining failures restricted to small, heavily occluded, oblique, or ambiguous targets. Coupled with temporal persistence mechanisms and an automated quality-control auditor, the framework minimizes privacy-related false negatives while preserving scene context for downstream vision tasks. While formal legal compliance depends on broader governance procedures, this publicly available pipeline and demonstration notebook provide an auditable preprocessing stage for privacy-aware dataset curation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.11645v2">Cloak of Invisibility: Real-Time Privacy-Preserving Volumetric Video Streaming</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-08-12T04:44:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hossein Khalili, Philip Do, Alexander Vilesov, Achuta Kadambi, Kittipat Apicharttrisorn, Nader Sehatbakhsh</p>
    <p><b>Summary:</b> Volumetric video streaming turns privacy into a 3D, multi-view problem. Unlike ordinary video, where sensitive content can often be redacted frame by frame, RGB-D volumetric pipelines capture people, rooms, and personal objects from multiple cameras and fuse them into a shared 3D representation. A private object missed in one view, or only partially removed before fusion, can therefore reappear in the reconstructed scene. This creates a privacy challenge for 3D telepresence, education, entertainment, and immersive applications: private content should be removed before raw visual and geometric data leave the camera side, while the public part of the scene should remain useful for real-time reconstruction. Existing volumetric streaming systems mainly optimize reconstruction, data movement, and latency, while privacy-preserving vision methods are designed for single-camera, single-frame images and do not directly address calibrated multi-view RGB-D fusion. We present InViStream, a real-time "privacy-from-source" system designed for this setting. InViStream addresses three challenges in volumetric capture: private objects may appear differently across views, RGB masking alone can leave geometric privacy leakage in depth, and public/private instances of the same class must be separated consistently before cloud-side fusion. To address these challenges, InViStream combines object detection with depth-aware masking, propagates public/private decisions across calibrated views, and fuses only sanitized point clouds. We evaluate InViStream on synthetic and real RGB-D scenes, including offices, conference rooms, living rooms, and settings with multiple public and private people and objects. InViStream achieves synthetic Dice/Recall of 0.799/0.891 and real Dice/Recall of 0.792/0.908, with synthetic SSIM above 0.98 and real-time streaming above 30 FPS.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.11337v1">Association-based Privacy Attacks in Wireless Protocols: Formal Modeling and Mitigation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-08-11T18:41:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohit Kumar Jangid, Felix Engelmann, Zhiqiang Lin</p>
    <p><b>Summary:</b> With the surge in privacy-sensitive data from sources such as social media and IoT devices, there is a pressing need for formal, automated methods to assess privacy risks within these intricate systems. This paper formally investigates root sources of pairing-based privacy threats exploited using replay/relay techniques in wireless communication. Our research harnesses condition-oblivious responses, replay-resistance, and distance bounding measures vital for protocols utilizing shared keys in allowlists for authenticated reconnections. Particularly, the paper uses formal modeling of notable wireless networks, like the Wi-Fi P2P persistent group formation and the Bluetooth Low Energy reconnection procedure, to illustrate the root causes and countermeasures. Our model rigorously validates the proposed solution against association inference attacks, along with existing formalizations of well-authentication, frame opacity, and no-desynchronization. The ensuing analysis reveals not only uncharted privacy realms in wireless communication but also identifies old and new vulnerabilities. Our proposed design changes are acknowledged by Wi-Fi Alliance and Bluetooth SIG, paving the way for future advancements in resilient, privacy-preserving wireless protocols.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.11003v1">Information Bottleneck under Perfect Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-11T14:50:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Junle Zhong, Mohamad Assaad, Sreejith Sreekumar</p>
    <p><b>Summary:</b> In this work, we study the information bottleneck under perfect privacy, with particular emphasis on the active-rate regime, where the representation-rate constraint is binding and directly limits the achievable utility. The goal is to construct a representation that preserves utility-relevant information while remaining statistically independent of a sensitive variable. This exact independence requirement introduces an additional constraint beyond the classical rate-relevance tradeoff and must be explicitly incorporated into the optimization. To this end, we develop an alternating direction method of multipliers (ADMM)-based method tailored to the resulting problem structure. Under suitable regularity conditions, we establish global convergence of the generated sequence, characterize its convergence rate through the Kurdyka-Lojasiewicz exponent, and extend the analysis to inexact block updates.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.10891v1">Benchmarking Time Series Generation Methods for Privacy-Preserving Forecasting</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-11T13:09:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Luis Amorim, Vitor Cerqueira, Moises Santos, Paulo J. Azevedo, Carlos Soares</p>
    <p><b>Summary:</b> Time series forecasting in privacy-sensitive domains often requires training models on released data rather than original observations. Synthetic time series generation has been developed primarily for data augmentation, where generated series supplement the original training set. How well these methods perform when fully replacing the original data - and how much privacy risk the released series carry - remains underexplored. We address this gap through a benchmark evaluating synthetic generation methods and noise-based anonymization baselines under a Train on Synthetic, Test on Real (TSTR) protocol. We jointly assess forecasting performance and distance-based empirical privacy risk across seven datasets, characterizing the trade-off between these objectives. We also introduce Grasynda-P, a privacy-motivated extension of the graph-based generator Grasynda, incorporating matrix ensembling and kernel density estimation. Our results show that: (1) no generation method fully substitutes for original training data; (2) noise-based anonymization yields the strongest privacy but the worst forecasting performance; (3) simple transformation-based generators outperform deep generative models for forecasting in this setting; and (4) Grasynda-P lies on the Pareto frontier, achieving competitive forecasting with stronger privacy separation than other generators. This benchmark establishes a reference point for evaluating and developing new privacy-aware synthetic time series generation methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.21410v1">Position: Robot Privacy as Embodied Boundary Work. Connecting Capabilities, Contexts, and Design Responses in Everyday Robotics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-08-11T10:03:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Liwen He, Shuning Zhang, Chengwen Zhang, Xin Yi, Chun Yu, Jihong Jeung, Xin Tong</p>
    <p><b>Summary:</b> Robots are increasingly entering everyday environments where privacy is shaped not only by data practices, but also by spatial, bodily, social, and relational boundaries. Their embodied capabilities allow them to reshape these boundaries through situated action, challenging privacy framings centered on data flows, interface settings, or one-time consent. Prior work has examined robot privacy through sensing, data collection, telepresence, transparency, consent, bystander awareness, and multi-stakeholder governance. Building on this work, we propose embodied boundary privacy as a capability-by-context framing for examining how physically present robots may reshape privacy boundaries in situated interaction. Specifically, this framing organizes privacy risks across seven robot capabilities and five deployment contexts, asking how embodied capabilities enable boundary crossings and how situated contexts shape who is affected, how these crossings are interpreted, and when they become contested. We use this perspective to outline design and research implications for embodied privacy mechanisms, including boundary checkpoints, viewpoint-aware sensing control, remote-presence disclosure, object- and body-level access rules, constraints on socially persuasive privacy influence, and local interruption rights. We encourage HRI research, design, and governance to treat robot movement, orientation, proximity, object access, remote presence, and social expression as privacy-relevant actions whose meaning depends on context.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.10318v1">In Defense of Using Worst-case Privacy Disclosure as Privacy Evaluation Metric of Voice Anonymization</a></h3>
  
  <p><b>Published on:</b> 2026-08-10T23:40:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xin Wang, Xiaoxiao Miao</p>
    <p><b>Summary:</b> The voice anonymization community mainly uses Equal Error Rate (EER) to evaluate the performance of voice identity protection. While alternative metrics such as privacy-ZEBRA and a rank-based metric have been proposed, their underlying assumptions and differences may not be well known, especially to newcomers. This paper is motivated to fill the gap. Based on the concept of Shannon's perfect secrecy (or privacy), this paper positions itself as a defense of the privacy-ZEBRA framework. While no new metric is proposed, this paper explains how an `ideal' system in terms of EER may fail to gauge the information leakage on individual speakers in the log-likelihood ratio (LLR) space. The paper also shows how the rank-based metric can be cast into a metric that follows the same principle of perfect secrecy and how their best solutions are equivalent. Furthermore, the paper explains how the method of estimating LLRs may affect the evaluation results. These discussions are, to the best of the authors' knowledge, not explored or explained in detail in existing papers. Last but not least, the findings are demonstrated on simulated and VoicePrivacy Challenge data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.09328v1">MaxModShift: Model Privacy via Designed Shifts</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2026-08-10T09:08:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nomaan A. Kherani, Urbashi Mitra</p>
    <p><b>Summary:</b> Model learning by an eavesdropper is treated as an estimation problem in a federated environment. The Fisher Information Matrix for the eavesdropper's estimation problem is driven to singularity through a signaling design; this ensures that the eavesdropper cannot learn the model. Herein, the innovation of prior designs is that model shifts are designed to maximize the difference in the model learned by Eve and the central server while satisfying a transmission power constraint for the agents. Two shift schemes are provided. MaxModShift outperforms a prior ModShift design while requiring lesser transmission power. Compared to a noise injection scheme, MaxModShift performs better while requiring a lower bandwidth secret channel and a reduced average power consumption.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.09164v2">CIDER: A Dataset of Contextual Disclosure Boundaries for Privacy Preference Alignment</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-08-10T06:17:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bingcan Guo, Eryue Xu, Jijie Zhou, Zhiping Zhang, Tianshi Li</p>
    <p><b>Summary:</b> Aligning large language models (LLMs) with human privacy preferences requires capturing individuals' disclosure boundaries beyond general privacy norms. However, a gap remains in eliciting such nuanced preferences to evaluate alignment in realistic settings. We introduce CIDER, a dataset of 14,850 human annotations from 169 users, forming 1,650 contextual disclosure boundary sets across 60 interpersonal communication scenarios involving information sharing that violates privacy norms. Each boundary represents a real user's disclosure decisions over 9 sharing variants in a scenario, for a given communication role and AI-mediated condition. We formulate a task in which models predict a user's disclosure decision from historical boundaries, with varying levels of contextual information. Across 12 open and proprietary models, in-context personalization improves prediction accuracy by up to 11.41 percentage points using only 6 historical examples. Larger models such as GPT-5.4 (with medium reasoning effort) and Claude Sonnet 4.6 are better at leveraging semantic context to understand user-specific, context-dependent disclosure preferences for more accurate predictions, while smaller models tend to rely on structured heuristics based on disclosure granularity and identifiability. Personalization generally improves prediction accuracy, but the improvement is often accompanied by imbalanced shifts in false-positive and false-negative rates across models, with only Claude Sonnet 4.6 achieving balanced improvements in both. Our findings reveal both the promise and limitations of inference-time personalization for privacy preference modeling and position CIDER as a resource for advancing personalized privacy alignment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.09140v1">Beyond Direct Identifiers: Probabilistic Privacy Risk Estimation for Privacy-Conscious LLM Query Delegation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-08-10T05:38:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Li Siyan, Zhou Yu, Julia Hirschberg</p>
    <p><b>Summary:</b> Recent work on protecting privacy during user-LLM interactions often focuses on direct, explicit identifiers: the personally-identifiable information (PII) captured by standard detectors. One such approach is Privacy-Conscious Delegation (PCD), where a local LLM acts as an intermediary. However, privacy risk does not stem solely from explicit identifiers but also PII-free self-disclosures, leaving users identifiable through combinations of quasi-identifying traits. We investigate a probabilistic variant of PCD, where we augment its objectives with an LLM-driven probabilistic estimation of k-anonymity. To facilitate this, we first create the PUPA-SD dataset, which contains naturalistic user queries with self-disclosure. Our preliminary results indicate that optimizing PAPILLON on PUPA-SD improves quality on unseen conversations across a variety of local models and produces the best privacy-utility balance for Llama-3.2-3B, while smaller models struggle to jointly optimize quality and privacy. We propose k-anonymity as a useful auxiliary metric for tackling PCD.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.09049v1">Security and Privacy Taxonomy Generation from Mobile App Reviews</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-08-10T02:55:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Moghis Fereidouni, Vinaik Chhetri, Umar Farooq, A. B. Siddique</p>
    <p><b>Summary:</b> Mobile app reviews are a rich, continuously renewing source of how users experience privacy and security, yet existing taxonomies of these concerns are hand-crafted and cannot keep pace with the evolving nature of the data. Automating taxonomy construction is the natural response, but scalability is the core challenge: current LLM- and clustering-based methods are developed for scientific corpora of a few thousand documents and do not extend to app review collections numbering in the hundreds of thousands. We address this gap in two ways. First, we filter app reviews for privacy- and security-related content, yielding a comprehensive corpus of over 600K reviews. Second, we introduce TaxoScale, a pipeline that handles taxonomy construction at this scale by extending an expert-defined taxonomy via Recursive Hierarchical Clustering and LLM-based node naming. TaxoScale outperforms strong automatic-taxonomy baselines on path, level, coverage, and novelty metrics, and discovers novel branches absent from prior taxonomies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.09001v1">Mind the Hook: Source-Level Auditing of Privacy Defenses in Retrieval-Augmented Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-10T01:40:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yanhang Li, Zhichao Fan, Zexin Zhuang</p>
    <p><b>Summary:</b> Black-box privacy scores for retrieval-augmented generation (RAG) are difficult to interpret unless the audited defense's active pipeline hook is known. We propose an active-path audit: inventory source-level hooks over retrieval, retrieved content, and generation; map each metric to the leakage channel it observes; and validate generated-text effects with exact-match canaries. In our benchmark reimplementations, the DP-style defenses modify retrieval scores only: their generation hooks are TODO-flagged stubs that return responses unchanged. This active path explains why they affect membership-inference behavior but track No-Defense on generated-text named-entity leakage, measured by NEL_strict. By contrast, the end-to-end LPRAG path is canary-validated on the email channel, recovering 53/150 canaries under No-Defense and 0/150 under LPRAG. These findings concern our reimplementations on our stack, not released defenses or defense families; the contribution is a methodology and case study, not a universal ranking</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.08341v1">Differential Privacy for Markov Chain State Trajectories</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-08T21:34:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alexander Benvenuti, Matthew Hale</p>
    <p><b>Summary:</b> Data-driven systems may require state trajectories of Markov chains to function because these trajectories contain information that is useful to the system, e.g., a product's credit risk, a user's physical location, or a user's internet browsing behavior. However, sharing such state trajectories can reveal sensitive information about users, which presents a privacy threat. Therefore, we develop a new framework for privatizing the state trajectories in a Markov chain using differential privacy. Our framework privatizes state trajectories online, in the sense that a private state trajectory is generated at the same time as the sensitive one it approximates. We treat Markov chains as weighted directed graphs whose edge weights are the negative logarithms of the transition probabilities. Then, each state in a private state trajectory is chosen by minimizing its distance to the corresponding state in the sensitive state trajectory, where the notion of distance is equal to the total edge weight along a shortest path. We prove that with high probability the private state trajectory remains close to the sensitive one, which maintains high utility for downstream uses of private data. Additionally, we prove that private state trajectories are consistently in the typical set of state trajectories generated by the underlying Markov chain, which means that private state trajectories have similar statistical properties to actual state trajectories produced by the underlying Markov chain. Numerical simulations show that under $3$-differential privacy, the mechanism we introduce exhibits up to an $80\%$ decrease in entropy compared to the state of the art, which illustrates that private state trajectories generated by our framework more closely resemble their corresponding sensitive state trajectory while maintaining the same level of privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.08245v1">Privacy-Preserving Data Drift Detection and Recovery for Large-Scale LLM Applications via Proxy Representations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-08-08T17:15:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Michael Levit, Josh Ledgard, Haoyu Dong, Vishwas Suryanarayanan, Eyal Kolman, Sharon Tan, Qiang Gan, Vishal Chowdhary</p>
    <p><b>Summary:</b> LLM applications deployed at scale face a fundamental challenge: privacy constraints prevent direct inspection of user interactions, making it difficult to obtain any representative evaluation dataset or to track the ongoing evolution of production traffic. We present ProxyDrift, a framework that (i) identifies and measures drift between production traffic and offline evaluation sets, and (ii) constructs and refreshes those evaluation sets accordingly; all without access to raw user data. Our approach operates entirely on non-PII proxy representations: structured, multi-dimensional descriptors derived from LLM-based classification of user interactions. We introduce (1) a chance-calibrated, redundancy-aware (RA) alignment score that aggregates per-dimension drift measurements via mutual information; (2) a conditional sampler that generates synthetic proxies respecting inter-dimensional dependencies; (3) a roundtrip consistency analysis that exposes generator/classifier disagreements and guides proxy taxonomy refinement; and (4) a feedback-linkage analysis that ties per-dimension and per-value proxy distributions to user satisfaction, surfacing actionable failure and success modes. Serving hundreds of millions of users, ProxyDrift enables continuous drift monitoring and targeted synthetic data generation without exposing sensitive user data. Experiments confirm strong roundtrip consistency, discriminator-level indistinguishability of synthetic queries from human queries, and tight end-to-end alignment (RA~0.9) with production.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.08129v1">Understanding Security and Privacy Perceptions of Content Creators Regarding AI Labels of AI-Generated Content</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-08-08T13:32:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuning Zhang, Hui Wang, Rongjun Ma, Xin Yi, Kanye Ye Wang, Robert Xiao, Hewu Li</p>
    <p><b>Summary:</b> AI labels, typically implemented via underlying tracing mechanisms such as watermarks and metadata, are crucial for protecting Artificial Intelligence-Generated Content (AIGC) against security threats like disinformation and evasion. However, the perceived devaluation of AI-assisted work discourages creators from disclosing AI use, incentivizing efforts to bypass labeling and compromising downstream traceability. Yet, how AIGC creators perceive the security and privacy (S\&P) implications of these labels, and how their behaviors impact technical resilience remain underexplored. To this end, we conducted semi-structured interviews with 21 AIGC creators and measured images across 6 image generation platforms against 16 self-reported manipulation settings. Our findings reveal that creators conflate binary AI labels with granular traceability, and express strong fears of de-anonymization via platform identifiers. Driven by fears of algorithmic traffic suppression and reputational risks, they defensively removed digital traces. Through empirical tests, we show that targeted modifications like coarse quantization significantly degrade detection. AI detection capabilities are also inconsistent across platforms, and suffer from false positives even for human-authored images. Based on these insights, we advocate for workflow-resilient implicit AI labels that align technical guarantees with creators' incentives.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.07705v1">Protecting patient privacy in clinical foundation models: Technical and legal perspectives</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-07T18:48:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sana Tonekaboni, Lena Stempfle, Sasha Ronaghi, Corinna Coupette, I. Glenn Cohen, Emily Alsentzer, Marzyeh Ghassemi</p>
    <p><b>Summary:</b> Clinical foundation models trained on large-scale patient data are increasingly used for decision support, screening, and public health. As deployment expands, privacy risk increasingly arises from model-mediated leakage, yet its prevalence and severity remain poorly quantified. Models can disclose sensitive training artifacts, enabling patient re-identification in ways not captured by data-handling controls alone. Existing frameworks, including HIPAA and GDPR, offer limited guidance for such indirect threats. We propose a practical framework for assessing privacy risk in clinical foundation models and illustrate realistic leakage scenarios across deployment settings, map them to legal regimes, and outline complementary technical and legal mitigations. Our analysis provides a context-aware risk assessment grounded in realistic usage to preserve the value of medical foundation models while rigorously safeguarding patient privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.07378v1">LSEAD: A Privacy-Preserving LLM-Based Speech Analysis Framework for Early Alzheimer's Disease Screening</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-07T16:21:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xin Wang, Yingchao Huang, Yuhan Su, Shanshan Yao, Wei Peng</p>
    <p><b>Summary:</b> Early diagnosis of Alzheimer's disease (AD) is critical for enabling timely interventions that may slow disease progression and improve patient outcomes. There is a growing need for AD detection methods that are non-invasive and cost-effective, especially in real-world clinical settings with diverse patient populations and recording conditions. Speech-based screening addresses these needs by using natural speech collected without specialized equipment. Recent advances in large language models (LLMs) have improved speech analysis by providing rich linguistic representations and strong generalization. In this study, we propose LSEAD, a speech-based AD detection framework using pretrained open-source LLMs. Speech recordings are automatically transcribed, and text embeddings are extracted using locally deployed LLMs. Principal component analysis (PCA) is applied to reduce dimensionality before classification. Because the framework relies only on speech transcripts and locally deployed models, it supports privacy-preserving AD risk assessment without external data exchange. We evaluate LSEAD on the ADReSS20 and ADReSSo2021 benchmark datasets. Experimental results show that LLM-based embeddings generalize well across datasets and improve AD classification accuracy by up to 5 percent over existing methods, especially for early-stage detection. These results demonstrate that LSEAD provides a practical, secure, and scalable approach for early AD screening.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.07206v1">Sub-Sampling for Positioning Privacy in ISAC: Deception by Aliasing via Sparse Arrays and Pilots</a></h3>
  
  <p><b>Published on:</b> 2026-08-07T13:19:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> L. Yashvanth, Christos Masouros, Suraj Srivastava, Aditya K. Jagannatham, Lajos Hanzo</p>
    <p><b>Summary:</b> Integrated sensing and communications (ISAC) enables simultaneous communication and sensing using shared spectrum and hardware resources in wireless systems. However, securing the sensing functionality against unauthorized receivers remains a fundamental challenge. In this paper, we propose a sub-sampling based sensing-privacy framework for communication-centric (CC)-ISAC systems that jointly exploits sparse arrays and sparse pilot allocations to induce controlled aliasing in the spatial and frequency domains, respectively. By interpreting antenna arrays and pilot subcarriers as spatial and frequency sampling mechanisms, respectively, we show that spatial-frequency undersampling naturally distorts the range-angle multiple-input multiple-output (MIMO) ambiguity function (AF) observed by an unauthorized receiver. To this end, we first derive a closed-form expression for the range-angle MIMO-AF, and subsequently characterize the ghost targets that arise due to spatial and frequency-domain aliasing. Next, we establish a sufficient condition under which these ambiguities jointly translate into positioning ambiguity and show that, for sufficiently large spatial and frequency sub-sampling factors, an unauthorized receiver inevitably positions a target at incorrect ghost positions. Finally, we show that the proposed sub-sampling framework preserves the native legitimate ISAC performance without introducing additional trade-offs. Numerical results verify the analysis and show that sparse arrays and sparse pilots naturally enable sensing and positioning privacy through deception by aliasing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.06888v2">Correlation Geometry of Quantum Sensor Networks: Local-Global Information Flow and Local Privacy</a></h3>
  
  <p><b>Published on:</b> 2026-08-07T07:21:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gong-Chu Li, Lei Chen, Xu-Song Hong, Hua-Qing Xu, Yuancheng Liu, Si-Qi Zhang, Jia-Hao Zhao, Geng Chen, Chuan-Feng Li, Guang-Can Guo</p>
    <p><b>Summary:</b> Quantum sensor networks (QSN) typically encode N unknown parameters while targeting a single linear combination, rendering the N-1 remaining parameters as nuisance directions. To rigorously quantify estimation precision under such nuisances, we use the effective quantum Fisher information (EQFI) and establish a ``barrel-effect'' bottleneck: the global EQFI cannot exceed the weakest weighted local sensing capacity. To elucidate the information allocation mechanism underlying this bottleneck, we derive an exact local--global phase map that delineates how the trade-off between local and global EQFI depends dynamically on quantum correlations, and accordingly we identify concrete conditions for saturating the bottleneck bound. Notably, this geometric map uncovers a counterintuitive ``overcorrelated'' regime where excessive correlations actively degrade both local and global performance. Finally, we apply the phase map to intrinsic local privacy and identify the condition under which every local parameter is inaccessible while the desired global combination remains estimable. Overall, our work provides a principled methodology for engineering optimal network states in quantum sensing architectures.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.05737v1">ABC: Numerical Data Collection under Local Differential Privacy without Prior Knowledge</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-06T08:19:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Incheol Baek, Hyungbin Kim, Yon Dohn Chung</p>
    <p><b>Summary:</b> Local Differential Privacy (LDP) provides strong privacy guarantees for collecting numerical data. A fundamental challenge, however, is that existing LDP mechanisms require a predefined data domain, which is often unknown in practice. This lack of prior knowledge creates a critical dilemma for the data collector: if the chosen domain is too narrow, values outside the range are clipped, leading to information loss. Conversely, if the domain is too wide, excessive noise is added during the privatization process, which degrades the quality of collected data. This highlights the need for methods that can dynamically estimate the data domain.
  In this work, we propose an adaptive LDP framework that addresses this problem. In our method, each user sends two pieces of information: their perturbed numerical data, and a privatized signal indicating if their original value was clipped by the current domain. By aggregating these signals, our proposed method, Adaptive Bounding of Clipping regions (ABC) method, iteratively adjusts the domain to fit the underlying data distribution without prior knowledge. Our theoretical analysis shows that the estimated data domain converges to an appropriate range.
  In the empirical evaluation, the results demonstrate that our framework significantly improves the quality of numerical data collection across various datasets and underlying LDP mechanisms. We also show that the estimated range successfully converges in practice and our approach is robust to its hyperparameters through comprehensive ablation studies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.05474v1">Exploring Privacy Leakage and Data Disclosure Violations in the MacOS Application Ecosystem</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-05T23:46:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jyotirmay Chauhan, Kostas Solomos, Mir Masood Ali, Jason Polakis</p>
    <p><b>Summary:</b> The systematic and excessive data collection practices of tech companies have rendered online privacy both a necessity and a sought-after commodity. However, while the privacy risks of the web, mobile, and IoT ecosystems have been extensively examined, desktop environments have been largely overlooked. As desktop apps continue to be widely used, they remain a critical yet understudied dimension of user privacy. In this paper, we address this gap by presenting the first, to our knowledge, comprehensive study of the mechanisms designed to regulate and disclose data collection and sharing practices in the macOS ecosystem. We adopt an app-development-centric view, and shed light on the interactions between the various macOS mechanisms that mediate apps' data access. Driven by our findings, we develop NutriScan, an analysis framework that incorporates both static and dynamic analysis techniques to create a consolidated view of macOS apps' data practices and disclosures. We use our system to dynamically analyze 1K macOS apps, and find that 85% of them access user-data APIs without disclosing it. 49.7% also exfiltrate data to advertising entities and hosting providers, 12.5% of which do so without a corresponding disclosure. We find that desktop apps are being leveraged by online trackers to enrich user profiles and device fingerprints, thus shedding new light on the true scope of the online tracking ecosystem. Our analysis reveals how the macOS app ecosystem is comprised of disjoint mechanisms with divergent data abstractions, thus increasing complexity for developers while also facilitating undisclosed privacy-invasive practices. Accordingly, we propose a series of mitigations that aim to both streamline the data disclosure process for developers and improve Apple's app vetting process.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.05115v1">Robust and Efficient Motion Reasoning for Privacy-Aware Classroom Incident Recognition</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-05T17:46:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Paritosh Parmar, Landy Lan, Hong Yang, Chen Yi, Chiat Pin Tay</p>
    <p><b>Summary:</b> Can computer vision help make classrooms safer? In this pilot study, we investigate privacy-aware and computationally efficient classroom incident recognition from CCTV-style observations. This setting remains underexplored, with limited benchmarks and few methods designed for the privacy, efficiency, and generalization demands of real-world deployment. We introduce a novel hybrid benchmark combining generative CCTV-style videos with real-world classroom pose data, and propose a lightweight, but robust motion-reasoning framework motivated by the observation that many incidents differ more in motion direction, speed, acceleration, and intensity than in pose alone. To that end, our method first constructs hierarchical kinematic representations of human actions. Our method then distills hierarchical, multi-order kinematic reasoning from a large teacher into a much smaller single-order student, enabling efficient per-person inference while preserving expressive motion understanding. Experiments show that our model outperforms substantially larger baselines at less than one-tenth of their computational cost, while also demonstrating stronger out-of-domain motion reasoning and zero-shot synthetic-to-real generalization. We will publicly release the benchmark, codebase, and supporting tools to facilitate further research in privacy-aware classroom safety.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.04501v1">Privacy-Preserving Action Recognition: Taxonomy, Methods, and Privacy-Utility Trade-offs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-08-05T06:38:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sareer Ul Amin, Muhammad Ayaz, Muhammad Munsif, Sanghyun Seo</p>
    <p><b>Summary:</b> Video surveillance in public safety, healthcare, and smart environments has made continuous human monitoring routine, raising real risks to personal identity and appearance. Privacy-preserving action recognition (PPAR) tackles the tension between the utility of video understanding and this exposure, and has drawn fast-growing interest. However, existing surveys remain narrow. Most catalog a single mechanism family, predate recent adversarial and hybrid work, or barely address evaluation. The result is a fragmented literature with incompatible threat models, inconsistent metrics, and no shared evaluation standard. We address this with a PRISMA-guided review of 32 peer-reviewed papers (2018--2026) drawn from 885 screened records. Methods sort into five families, namely adversarial learning (52%), skeleton-based (20%), cryptographic (12%), differential privacy (8%), and hybrid (8%), each with distinct privacy, utility, and efficiency trade-offs. Evaluation is the weak point. Only 10% of papers adopt a formal privacy definition, 65% rely on ad-hoc metrics, and 40% report an inconsistently defined cMAP. The trade-offs are steep. Skeleton methods reach about 85% accuracy but drop appearance, adversarial methods hold near 80% utility at moderate privacy (cMAP 0.9 to 0.3--0.5), and differential privacy often falls below 70%. Harder conditions stay under-tested, with fewer than 15% of papers checking cross-dataset generalization, under 10% testing adaptive attackers, and real-time edge deployment nearly untouched. We contribute a two-dimensional privacy-space taxonomy, a formal threat model, a comparative trade-off analysis, the PPAR Unified Evaluation Protocol, and a roadmap centered on benchmark standardization. With this grounding, we argue PPAR can move from prototypes toward deployment, with lessons extending to face recognition and medical imaging.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.04255v1">PriDyG: Privacy-preserving Dynamic Graph Inference with LLM-GNN Collaboration</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-04T22:23:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuyang Xia, Ruixuan Liu, Li Xiong</p>
    <p><b>Summary:</b> Graph inference over relational data can expose sensitive edge information, and this risk becomes more severe in dynamic graphs, where repeated model updates cause privacy loss to accumulate. We formulate Edge-level Differentially Private Dynamic Graph Inference (EDG) and propose PriDyG, a private inference framework that combines GNN-based structural learning with LLM-based semantic reasoning. PriDyG introduces incremental private multi-hop aggregation, which buffers newly arrived edges and processes each edge exactly once. By parallel composition, the total privacy cost equals that of a single static release, independent of the number or schedule of model updates. Compared with geometrically decaying budget allocation, incremental aggregation avoids exponentially increasing noise while preserving exact one-hop signals and at least half of two-hop information transfers. PriDyG further complements privatized GNN outputs with LLM predictions derived solely from node text, incurring no additional edge-level privacy cost. Experiments on four benchmarks for node classification and link prediction show that PriDyG consistently outperforms geometrically decaying baselines under the same privacy budget and matches the utility of naive per-update retraining while reducing cumulative privacy cost by up to three orders of magnitude.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.03940v1">Echoes in the Digital Abyss: Examining the Bubble Surrounding Security and Privacy Discourse in Social Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-08-04T17:10:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Reagan Dennison, Saanvi Sharma, Noshir Contractor, Sruti Bhagavatula</p>
    <p><b>Summary:</b> The dissemination of security and privacy education and guidance has been and still remains a challenge today. Social networks represent a potential avenue for sharing best practices, and experimentally they have been found to be effective at this task. While this appears promising, in the real world, security and privacy discussions would need to reach a wide range of people to be effective, avoiding the "interest bubbles" that commonly occur. We sought to understand how the communities surrounding security and privacy discourse operate, with a focus on what challenges need to be overcome to enable security and privacy discourse and advice to reach a wider audience.
  Indeed, we found that in-the-wild security and privacy discussions in social networks portray quite a different picture than in experimental settings. We built and analyzed the structure of a graph containing over 13 million users on the "X" platform (formerly "Twitter"), including 10,159 users who posted about security and privacy and their followers. Prior work has shown that users are more likely to consider information within social media if their like-minded social ties have visibly engaged with it. Our findings indicate that the users generating or participating in security discussions largely already belong to highly clustered technology and security- and privacy-related interest communities, which suggests that the people who are not already in the "inner circle" of relevant interests are likely not exposed effectively to these discussions. We conclude with reflections and ideas on increasing the reach of security and privacy guidance in social networks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.03737v1">Dependency Triad: A Metric to Quantify the Dependencies Between Attributes for Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-08-04T14:30:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sandaru Jayawardana, Sennur Ulukus, Ming Ding, Kanchana Thilakarathna</p>
    <p><b>Summary:</b> Collecting multidimensional user data is essential for extracting rich insights across various applications. Local Differential Privacy (LDP) has emerged as a de facto standard for mitigating privacy risks in such scenarios. A key challenge in privacy-preserving multidimensional data collection lies in inter-attribute dependencies, as they can inadvertently reveal correlated information and increase privacy vulnerabilities. Therefore, accurately measuring correlation-induced privacy leakage (CPL) is essential for privacy analysis and privacy-utility trade-off. However, existing CPL analysis solutions either require accurate prior knowledge or face scalability challenges for large numbers of attributes and high-cardinality attributes. These limit their practical applicability in real data. To address this research gap, we propose a novel metric, ``Dependency Triad'' (DT), which summarizes the pairwise dependency information relevant to CPL using three parameters and yields a \emph{constant-time} conservative estimator of pairwise CPL. DT explicitly models uncertainty in prior distributional knowledge through its parameters, delivering robust leakage estimates. Moreover, its robustness to sparse distributions makes it particularly suitable for high-cardinality attributes, while the pairwise formulation serves as a tractable building block for assessing total leakage in multidimensional settings. Extensive experiments on both synthetic and real datasets demonstrate that DT consistently estimates CPL across diverse dependency regimes and prior uncertainties.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.03700v1">When Agents Learn to Be You: Benchmarking Privacy Leakage, Impersonation Risk, and Defenses in Persona Skills</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-08-04T14:04:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yongli Xiang, Zhifang Zhang, Bojun Yang, Ziming Hong, Lei Feng, Miao Xu, Tongliang Liu</p>
    <p><b>Summary:</b> Persona skills distill personal interaction histories into portable and executable artifacts for downstream agents. While enabling flexible personalization, this process concentrates fragmented personal signals, amplifies their impact through reuse, and challenges defenses designed for individual records or retrieval-based memory. To systematically investigate the safety of the persona-skill pipeline, we introduce AntiSkillBench, an end-to-end benchmark for evaluating risks and defenses across the persona-skill pipeline. It comprises: (i) a dataset of 7,500 persona-grounded dialogue traces, constructed from 50 behaviorally rich profiles spanning diverse task scenarios; (ii) an evaluation suite that measures skill-level privacy leakage and agent-level attribute disclosure and behavioral impersonation across three skill-distillation strategies; and (iii) a defense evaluation covering four configurations across online and post-hoc interventions, including active risk suppression and passive provenance protection. Experiments across three frontier agents show that persona-skill risks persist across agent backbones and distillation protocols, extending from explicit attributes to communication styles and personality traits. Existing defenses exhibit limited and distillation-dependent effectiveness, failing to generalize across risk and distillation strategies. These results highlight AntiSkillBench as a challenging benchmark for developing privacy-preserving and authenticity-aware persona skills.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.03130v1">DP-MemView: A Memory Interface for Attribute-Level Transcript Privacy in Long-Term LLM Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-04T05:00:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jong Wook Kim, Byoungjae Min, Kennedy Edemacu, Yoonhyuk Choi, Sae-Hong Cho, Beakcheol Jang</p>
    <p><b>Summary:</b> Long-term memory enables persistent personalization in LLM agents, but repeated memory-conditioned responses can cumulatively reveal protected attributes even when they are never stated explicitly. We formalize this threat as adaptive transcript privacy and introduce DP-MemView, a differentially private interface that privately selects public response-conditioning views and exposes those views---rather than raw memory---to the response LLM. Each private selection is charged to every protected attribute whose memory group intersects the read set. Per-attribute ledgers block any selection that would exceed its cap and return a fixed generic view instead. Under an explicit interface contract, we prove pure B_a-DP for the entire adaptive transcript. We also extend the result to stores that differ across multiple protected groups and bound how much observing the transcript can change an adversary's prior odds. We evaluate the online and preallocated modes with three response LLMs on a controlled adjacent-store benchmark and a public-corpus transfer track. Both modes keep transcript distinguishability near chance while preserving target-required personalization and overall response quality. Further diagnostics show that removing key safeguards causes mismatched output support, missing ledger charges, revealing side channels, or growing long-horizon leakage.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.02774v1">Privacy-Preserving AI Verification via Minimal Information Disclosure</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-08-03T18:18:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sleem Abdelghafar, Gabriel Kulp</p>
    <p><b>Summary:</b> AI verification crosses a trust boundary: a verifier must learn enough to establish an authorized claim, yet the same evidence can reveal sensitive details about the model, workload, or hardware. We introduce minimal information disclosure (MID), which designs and quantifies the information content of verifier-facing evidence itself. MID measures collateral leakage with conditional mutual information: what the release reveals about the protected property after the authorized result is known. MID is general by design: it can accommodate different verification goals, protected properties, evidence sources, and deployment constraints. To demonstrate MID's practicality, we evaluate it on four physical measurements and six verification tasks spanning execution type, hardware identity, compute scale, and model identity. These experiments use three mechanism-design variables--the evidence channel, collection policy, and release transformation--but MID is not limited to these choices and can accommodate other deployable mechanisms. Across these tasks, MID produces three releases with perfect held-out verification and zero measured collateral leakage, while the remaining tasks yield explicit privacy--utility frontiers. MID also supports ZKP-certified releases: we demonstrate our proposed linear-projection mechanism using a Groth16 zk-SNARK.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.01539v1">SP2UBI: Secure and Privacy-Preserving Usage-Based Insurance</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-02T23:20:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mobin Aghamirkarimi, Matin Aghamirkarimi, Farid Zaredar, Morteza Amini</p>
    <p><b>Summary:</b> The transition from traditional auto insurance, whose basis is defined by a set of static parameters, like the age of driver and number of accidents, to Usage-Based Insurance, whose pricing is based on driving behavior, was boosted by Intelligent Transportation Systems. At the same time, the analysis of high-resolution telematics data might reveal users' behavior and habits, which is associated with significant privacy concerns. The majority of privacy-preserving UBI systems are subject to policyholders' data leaks at some point during the life cycle of their protocol. Moreover, it is challenging to ensure data integrity against possible intentional or unintentional sensor anomalies (like sensor spoofing or malfunctioning) since the approaches used in this case require privacy-compromising audits and do not consider the oracle problem. In order to address the issues, we propose SP2UBI, a privacy-preserving UBI solution which guarantees mutual confidentiality. SP2UBI collects the telematics data in coarse-grained, statistical form without any spatiotemporal identifiers so that it is impossible to reconstruct fine-grained mobility traces. By utilizing the Torus Fully Homomorphic Encryption scheme, which incurs low computational overhead, computations are performed directly over encrypted data. This way, the insurer calculates risk factors without accessing any sensitive information, while parameters of its risk model are confidential. In order to protect data integrity against sensor level manipulation, SP2UBI incorporates a speed verification system assisted by Integrated Sensing and Communications (ISAC) technology which is capable of detecting fraud while preserving user privacy. Experimental evaluation shows that one round of protocol execution takes 41.2 ms, showing that our framework is lightweight and preserves more privacy guarantees compared to state-of-the-art solutions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.01412v1">Bridging Differential Privacy and Random Triangles</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-08-02T17:47:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tianxi Ji</p>
    <p><b>Summary:</b> The classical analysis of the Gaussian mechanism in differential privacy reduces privacy loss for a pair of neighboring datasets to a scalar random variable. While this scalar characterization is sufficient for privacy accounting, each perturbation instance also induces a high-dimensional random triangle formed by the sensitivity vector and the two corresponding noise vectors. In this work, we develop two complementary geometric representations of these random triangles.
  The first representation maps the normalized squared edge lengths to a simplex. We derive its exact joint density, characterize its elliptical support, and reconstruct the classical privacy loss random variable from the simplex coordinates. The second representation maps the spectral shape of each normalized triangle to a hemisphere. We derive the corresponding density and coordinate mappings, recover the same privacy loss, and characterize an equatorial drift together with band concentration as the dimension increases. These results provide two exact geometric coordinate systems that complement the scalar privacy loss and connect differential privacy with the probabilistic analysis of random shapes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.01311v1">RH-RAG: Trustworthy Long-Form Generation for Privacy-Constrained Settings</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-08-02T15:27:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Raj Shekhar Singh</p>
    <p><b>Summary:</b> Generating long-form content from extensive internal reports remains challenging for organizations operating under strict privacy and security constraints, where proprietary cloud-based LLM APIs are often not viable. While locally deployed open-weight models offer a privacy-preserving alternative, existing retrieval-augmented generation (RAG) approaches on smaller models frequently lack effective global planning and accumulate factual inconsistencies over long outputs. To address these limitations, we present RH-RAG, a multi-agent framework for secure and trustworthy long form generation using local language models. RH-RAG decomposes generation into three coordinated stages: a Planner Agent that constructs a global document outline from high-level semantic summaries, a Writer Agent that incrementally generates coherent section-wise content using bounded coherence memory, and a Checker Agent that mitigates hallucinations through natural language inference-based factual verification and an attestation-driven revision loop. The framework further employs a dual-level retrieval index that supports efficient planning and fine-grained contextual generation on consumer-grade hardware. Evaluations across literary, financial, and legal domains demonstrate that RH-RAG consistently improves factual grounding, semantic coherence, and document-level alignment compared to standard and hierarchical RAG baselines, while achieving reliability competitive with proprietary cloud-based systems without compromising data privacy.</p>
  </details>
</div>

