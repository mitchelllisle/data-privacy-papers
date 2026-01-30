
<h2>2026-01</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.22104v1">Social Media Data for Population Mapping: A Bayesian Approach to Address Representativeness and Privacy Challenges</a></h3>
   
  <p><b>Published on:</b> 2026-01-29T18:36:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Paolo Andrich, Shengjie Lai, Halim Jun, Qianwen Duan, Zhifeng Cheng, Seth R. Flaxman, Andrew J. Tatem</p>
    <p><b>Summary:</b> Accurate and timely population data are essential for disaster response and humanitarian planning, but traditional censuses often cannot capture rapid demographic changes. Social media data offer a promising alternative for dynamic population monitoring, but their representativeness remains poorly understood and stringent privacy requirements limit their reliability. Here, we address these limitations in the context of the Philippines by calibrating Facebook user counts with the country's 2020 census figures. First, we find that differential privacy techniques commonly applied to social media-based population datasets disproportionately mask low-population areas. To address this, we propose a Bayesian imputation approach to recover missing values, restoring data coverage for $5.5\%$ of rural areas. Further, using the imputed social media data and leveraging predictors such as urbanisation level, demographic composition, and socio-economic status, we develop a statistical model for the proportion of Facebook users in each municipality, which links observed Facebook user numbers to the true population levels. Out-of-sample validation demonstrates strong result generalisability, with errors as low as ${\approx}18\%$ and ${\approx}24\%$ for urban and rural Facebook user proportions, respectively. We further demonstrate that accounting for overdispersion and spatial correlations in the data is crucial to obtain accurate estimates and appropriate credible intervals. Crucially, as predictors change over time, the models can be used to regularly update the population predictions, providing a dynamic complement to census-based estimates. These results have direct implications for humanitarian response in disaster-prone regions and offer a general framework for using biased social media signals to generate reliable and timely population data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.21859v1">Adaptive Privacy of Sequential Data Releases Under Collusion</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-01-29T15:29:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sophie Taylor, Praneeth Kumar Vippathalla, Justin Coon</p>
    <p><b>Summary:</b> The fundamental trade-off between privacy and utility remains an active area of research. Our contribution is motivated by two observations. First, privacy mechanisms developed for one-time data release cannot straightforwardly be extended to sequential releases. Second, practical databases are likely to be useful to multiple distinct parties. Furthermore, we can not rule out the possibility of data sharing between parties. With utility in mind, we formulate a privacy-utility trade-off problem to adaptively tackle sequential data requests made by different, potentially colluding entities. We consider both expected distortion and mutual information as measures to quantify utility, and use mutual information to measure privacy. We assume an attack model whereby illicit data sharing, which we call collusion, can occur between data receivers. We develop an adaptive algorithm for data releases that makes use of a modified Blahut-Arimoto algorithm. We show that the resulting data releases are optimal when expected distortion quantifies utility, and locally optimal when mutual information quantifies utility. Finally, we discuss how our findings may extend to applications in machine learning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.21719v1">LoRA and Privacy: When Random Projections Help (and When They Don't)</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2026-01-29T13:43:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yaxi Hu, Johanna Düngler, Bernhard Schölkopf, Amartya Sanyal</p>
    <p><b>Summary:</b> We introduce the (Wishart) projection mechanism, a randomized map of the form $S \mapsto M f(S)$ with $M \sim W_d(1/r I_d, r)$ and study its differential privacy properties. For vector-valued queries $f$, we prove non-asymptotic DP guarantees without any additive noise, showing that Wishart randomness alone can suffice. For matrix-valued queries, however, we establish a sharp negative result: in the noise-free setting, the mechanism is not DP, and we demonstrate its vulnerability by implementing a near perfect membership inference attack (AUC $> 0.99$). We then analyze a noisy variant and prove privacy amplification due to randomness and low rank projection, in both large- and small-rank regimes, yielding stronger privacy guarantees than additive noise alone. Finally, we show that LoRA-style updates are an instance of the matrix-valued mechanism, implying that LoRA is not inherently private despite its built-in randomness, but that low-rank fine-tuning can be more private than full fine-tuning at the same noise level. Preliminary experiments suggest that tighter accounting enables lower noise and improved accuracy in practice.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.21636v1">Sampling-Free Privacy Accounting for Matrix Mechanisms under Random Allocation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2026-01-29T12:40:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jan Schuchardt, Nikita Kalinin</p>
    <p><b>Summary:</b> We study privacy amplification for differentially private model training with matrix factorization under random allocation (also known as the balls-in-bins model). Recent work by Choquette-Choo et al. (2025) proposes a sampling-based Monte Carlo approach to compute amplification parameters in this setting. However, their guarantees either only hold with some high probability or require random abstention by the mechanism. Furthermore, the required number of samples for ensuring $(ε,δ)$-DP is inversely proportional to $δ$. In contrast, we develop sampling-free bounds based on Rényi divergence and conditional composition. The former is facilitated by a dynamic programming formulation to efficiently compute the bounds. The latter complements it by offering stronger privacy guarantees for small $ε$, where Rényi divergence bounds inherently lead to an over-approximation. Our framework applies to arbitrary banded and non-banded matrices. Through numerical comparisons, we demonstrate the efficacy of our approach across a broad range of matrix mechanisms used in research and practice.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.21265v1">A Quantum-Memory-Free Quantum Secure Direct Communication Protocol Based on Privacy Amplification of Coded Sequences</a></h3>
  
  <p><b>Published on:</b> 2026-01-29T04:55:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shang-Jen Su, Shi-Yuan Wang, Matthieu R. Bloch</p>
    <p><b>Summary:</b> We develop an information-theoretic analysis of Quantum-Memory-Free (QMF) Quantum Secure Direct Communication (QSDC) under collective attacks as an alternative to the conventional Quantum Key Distribution (QKD) protocol with one-time pads. Our main contributions are: 1) a QMF-QSDC protocol that only relies on universal hashing of coded sequences without wiretap coding; 2) a set of privacy amplification theorems for extracting secrecy from coded classical sequences against quantum side-information. These tools open the way to the design of robust QMF-QSDC protocols.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.20792v1">Jurisdiction as Structural Barrier: How Privacy Policy Organization May Reduce Visibility of Substantive Disclosures</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-01-28T17:29:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Thomas Brackin</p>
    <p><b>Summary:</b> Privacy policies are supposed to provide notice. But what if substantive information appears only where users skip it? We identify a structural pattern we call jurisdiction-siloed disclosure: information about data practices appearing in specific, actionable form only within regional compliance sections labeled "California Residents" or "EU/UK Users," while general sections use vague or qualified language for the same practices.
  Our audit of 123 major companies identifies 282 potential instances across 77 companies (62.6% of this purposive sample). A conservative estimate restricted to practice categories validated against OPP-115 human annotations finds 138 instances across 54 companies (44%); post-2018 categories central to our findings await independent validation. If users skip jurisdiction-labeled sections as information foraging theory predicts, users outside regulated jurisdictions would receive less specific information about practices affecting them--a transparency failure operating through document architecture rather than omission.
  We propose universal substantive disclosure: practices affecting all users should appear in the main policy body, with regional sections containing only procedural rights information. This standard finds support in analogous disclosure regimes (securities, truth-in-lending, nutritional labeling) where material information must reach all affected parties. Regulators could operationalize this through the FTC's "clear and conspicuous" standard and GDPR transparency principles.
  This work is hypothesis-generating: we establish that the structural pattern exists and ground the transparency concern in behavioral theory, but direct measurement of jurisdiction-specific section skipping remains the critical validation priority. We release our methodology and annotated dataset to enable replication.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.20716v1">Decentralized Identity in Practice: Benchmarking Latency, Cost, and Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2026-01-28T15:48:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abylay Satybaldy, Kamil Tylinski, Jiahua Xu</p>
    <p><b>Summary:</b> Decentralized Identifiers (DIDs) are increasingly deployed on distributed ledgers, yet systematic cross-platform evidence on their operational behavior remains limited. We present an empirical benchmarking study of three prominent ledger-based DID methods - Ethereum, Hedera, and XRP Ledger - using reference Software Development Kits (SDKs) under a unified experimental setup. We measure latency, transaction cost, and on-chain metadata exposure, normalizing latency by each platform's block or consensus interval and cost by its native value transfer fee. Privacy leakage is quantified using a Metadata-Leakage Score (MLS), an entropy-based measure expressed in bits per operation.
  Our results reveal distinct architectural trade-offs. Ethereum enables near-instant, off-chain DID creation, but incurs the highest latency and cost for on-chain lifecycle operations. XRPL delivers deterministic and stable latency with fixed, low fees, yet exhibits higher metadata leakage due to more verbose transaction payloads. Hedera achieves the lowest on-chain latency and low fees with minimal metadata leakage, while occasional variance arises from SDK-side processing and confirmation pipelines.
  Overall, the findings show that ledger architecture and SDK workflows play a major role in shaping DID latency, cost, and metadata exposure, complementing the effects of the underlying consensus mechanism. These results provide evidence-based insights to support informed selection and configuration of DID systems under performance and privacy constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.20325v1">UnlearnShield: Shielding Forgotten Privacy against Unlearning Inversion</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-01-28T07:42:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lulu Xue, Shengshan Hu, Wei Lu, Ziqi Zhou, Yufei Song, Jianhong Cheng, Minghui Li, Yanjun Zhang, Leo Yu Zhang</p>
    <p><b>Summary:</b> Machine unlearning is an emerging technique that aims to remove the influence of specific data from trained models, thereby enhancing privacy protection. However, recent research has uncovered critical privacy vulnerabilities, showing that adversaries can exploit unlearning inversion to reconstruct data that was intended to be erased. Despite the severity of this threat, dedicated defenses remain lacking. To address this gap, we propose UnlearnShield, the first defense specifically tailored to counter unlearning inversion. UnlearnShield introduces directional perturbations in the cosine representation space and regulates them through a constraint module to jointly preserve model accuracy and forgetting efficacy, thereby reducing inversion risk while maintaining utility. Experiments demonstrate that it achieves a good trade-off among privacy protection, accuracy, and forgetting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.20161v1">Supporting Informed Self-Disclosure: Design Recommendations for Presenting AI-Estimates of Privacy Risks to Users</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-01-28T01:35:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Isadora Krsek, Meryl Ye, Wei Xu, Alan Ritter, Laura Dabbish, Sauvik Das</p>
    <p><b>Summary:</b> People candidly discuss sensitive topics online under the perceived safety of anonymity; yet, for many, this perceived safety is tenuous, as miscalibrated risk perceptions can lead to over-disclosure. Recent advances in Natural Language Processing (NLP) afford an unprecedented opportunity to present users with quantified disclosure-based re-identification risk (i.e., "population risk estimates", PREs). How can PREs be presented to users in a way that promotes informed decision-making, mitigating risk without encouraging unnecessary self-censorship? Using design fictions and comic-boarding, we story-boarded five design concepts for presenting PREs to users and evaluated them through an online survey with N = 44 Reddit users. We found participants had detailed conceptions of how PREs may impact risk awareness and motivation, but envisioned needing additional context and support to effectively interpret and act on risks. We distill our findings into four key design recommendations for how best to present users with quantified privacy risks to support informed disclosure decision-making.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.19837v1">Self-Sovereign Identity and eIDAS 2.0: An Analysis of Control, Privacy, and Legal Implications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2026-01-27T17:43:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nacereddine Sitouah, Marco Esposito, Francesco Bruschi</p>
    <p><b>Summary:</b> European digital identity initiatives are grounded in regulatory frameworks designed to ensure interoperability and robust, harmonized security standards. The evolution of these frameworks culminates in eIDAS 2.0, whose origins trace back to the Electronic Signatures Directive 1999/93/EC, the first EU-wide legal foundation for the use of electronic signatures in cross-border electronic transactions. As technological capabilities advanced, the initial eIDAS 1.0 framework was increasingly criticized for its limitations and lack of comprehensiveness. Emerging decentralized approaches further exposed these shortcomings and introduced the possibility of integrating innovative identity paradigms, such as Self-Sovereign Identity (SSI) models.
  In this article, we analyse key provisions of the eIDAS 2.0 Regulation and its accompanying recitals, drawing on existing literature to identify legislative gaps and implementation challenges. Furthermore, we examine the European Digital Identity Architecture and Reference Framework (ARF), assessing its proposed guidelines and evaluating the extent to which its emerging implementations align with SSI principles.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.19575v2">Putting Privacy to the Test: Introducing Red Teaming for Research Data Anonymization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-01-27T13:04:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Luisa Jansen, Tim Ulmann, Robine Jordi, Malte Elson</p>
    <p><b>Summary:</b> Recently, the data protection practices of researchers in human-computer interaction and elsewhere have gained attention. Initial results suggest that researchers struggle with anonymization, partly due to a lack of clear, actionable guidance. In this work, we propose simulating re-identification attacks using the approach of red teaming versus blue teaming: a technique commonly employed in security testing, where one team tries to re-identify data, and the other team tries to prevent it. We discuss our experience applying this method to data collected in a mixed-methods study in human-centered privacy. We present usable materials for researchers to apply red teaming when anonymizing and publishing their studies' data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.19502v1">VisGuardian: A Lightweight Group-based Privacy Control Technique For Front Camera Data From AR Glasses in Home Environments</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-27T11:41:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuning Zhang, Qucheng Zang, Yongquan `Owen' Hu, Jiachen Du, Xueyang Wang, Yan Kong, Xinyi Fu, Suranga Nanayakkara, Xin Yi, Hewu Li</p>
    <p><b>Summary:</b> Always-on sensing of AI applications on AR glasses makes traditional permission techniques ill-suited for context-dependent visual data, especially within home environments. The home presents a highly challenging privacy context due to the high density of sensitive objects, and the frequent presence of non-consenting family members, and the intimate nature of daily routines, making it a critical focus area for scalable privacy control mechanisms. Existing fine-grained controls, while offering nuanced choices, are inefficient for managing multiple private objects. We propose VisGuardian, a fine-grained content-based visual permission technique for AR glasses. VisGuardian features a group-based control mechanism that enables users to efficiently manage permissions for multiple private objects. VisGuardian detects objects using YOLO and adopts a pre-classified schema to group them. By selecting a single object, users can efficiently obscure groups of related objects based on criteria including privacy sensitivity, object category, or spatial proximity. A technical evaluation shows VisGuardian achieves mAP50 of 0.6704 with only 14.0 ms latency and a 1.7% increase in battery consumption per hour. Furthermore, a user study (N=24) comparing VisGuardian to slider-based and object-based baselines found it to be significantly faster for setting permissions and was preferred by users for its efficiency, effectiveness, and ease of use.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.19956v1">VoxPrivacy: A Benchmark for Evaluating Interactional Privacy of Speech Language Models</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36">
  <p><b>Published on:</b> 2026-01-27T06:22:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuxiang Wang, Hongyu Liu, Dekun Chen, Xueyao Zhang, Zhizheng Wu</p>
    <p><b>Summary:</b> As Speech Language Models (SLMs) transition from personal devices to shared, multi-user environments such as smart homes, a new challenge emerges: the model is expected to distinguish between users to manage information flow appropriately. Without this capability, an SLM could reveal one user's confidential schedule to another, a privacy failure we term interactional privacy. Thus, the ability to generate speaker-aware responses becomes essential for SLM safe deployment. Current SLM benchmarks test dialogue ability but overlook speaker identity. Multi-speaker benchmarks check who said what without assessing whether SLMs adapt their responses. Privacy benchmarks focus on globally sensitive data (e.g., bank passwords) while neglecting contextual privacy-sensitive information (e.g., a user's private appointment). To address this gap, we introduce VoxPrivacy, the first benchmark designed to evaluate interactional privacy in SLMs. VoxPrivacy spans three tiers of increasing difficulty, from following direct secrecy commands to proactively protecting privacy. Our evaluation of nine SLMs on a 32-hour bilingual dataset reveals a widespread vulnerability: most open-source models perform close to random chance (around 50% accuracy) on conditional privacy decisions, while even strong closed-source systems fall short on proactive privacy inference. We further validate these findings on Real-VoxPrivacy, a human-recorded subset, confirming that failures observed on synthetic data persist in real speech. Finally, we demonstrate a viable path forward: by fine-tuning on a new 4,000-hour training set, we improve privacy-preserving abilities while maintaining robustness. To support future work, we release the VoxPrivacy benchmark, the large-scale training set, and the fine-tuned model to foster the development of safer and more context-aware SLMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.19206v1">Universal Operational Privacy in Distributed Quantum Sensing</a></h3>
  
  <p><b>Published on:</b> 2026-01-27T05:17:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Min Namkung, Dong-Hyun Kim, Seongjin Hong, Yong-Su Kim, Su-Yong Lee, Hyang-Tag Lim</p>
    <p><b>Summary:</b> Privacy is a fundamental requirement in distributed quantum sensing networks, where multiple clients estimate spatially distributed parameters using shared quantum resources while interacting with potentially untrusted servers. Despite its importance, existing privacy conditions rely on idealized quantum bounds and do not fully capture the operational constraints imposed by realistic measurements. Here, we introduce a universal operational privacy framework for distributed quantum sensing, formulated in terms of the experimentally accessible classical Fisher information matrix and applicable to arbitrary protocols characterized by singular information structures. The proposed condition provides a protocol-independent criterion ensuring that no information about individual parameters is accessible to untrusted parties. We further experimentally demonstrate that a distributed quantum sensing protocol employing fewer photons than the number of estimated parameters simultaneously satisfies the universal privacy condition and achieves Heisenberg-limited precision. Our results establish universal operational constraints governing privacy in distributed quantum sensing networks and provide a foundation for practical, privacy-preserving quantum sensing beyond full-rank regimes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.19154v1">Analysis of Shuffling Beyond Pure Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-27T03:35:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shun Takagi, Seng Pei Liew</p>
    <p><b>Summary:</b> Shuffling is a powerful way to amplify privacy of a local randomizer in private distributed data analysis, but existing analyses mostly treat the local differential privacy (DP) parameter $\varepsilon_0$ as the only knob and give generic upper bounds that can be loose and do not even characterize how shuffling amplifies privacy for basic mechanisms such as the Gaussian mechanism. We revisit the privacy blanket bound of Balle et al. (the blanket divergence) and develop an asymptotic analysis that applies to a broad class of local randomizers under mild regularity assumptions, without requiring pure local DP. Our key finding is that the leading term of the blanket divergence depends on the local mechanism only through a single scalar parameter $χ$, which we call the shuffle index. By applying this asymptotic analysis to both upper and lower bounds, we obtain a tight band for $δ_n$ in the shuffled mechanism's $(\varepsilon_n,δ_n)$-DP guarantee. Moreover, we derive a simple structural necessary and sufficient condition on the local randomizer under which the blanket-divergence-based upper and lower bounds coincide asymptotically. $k$-RR families with $k\ge3$ satisfy this condition, while for generalized Gaussian mechanisms the condition may not hold but the resulting band remains tight. Finally, we complement the asymptotic theory with an FFT-based algorithm for computing the blanket divergence at finite $n$, which offers rigorously controlled relative error and near-linear running time in $n$, providing a practical numerical analysis for shuffle DP.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.19126v1">How Entanglement Reshapes the Geometry of Quantum Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2026-01-27T02:50:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xi Wang, Parastoo Sadeghi, Guodong Shi</p>
    <p><b>Summary:</b> Quantum differential privacy provides a rigorous framework for quantifying privacy guarantees in quantum information processing. While classical correlations are typically regarded as adversarial to privacy, the role of their quantum analogue, entanglement, is not well understood. In this work, we investigate how quantum entanglement fundamentally shapes quantum local differential privacy (QLDP). We consider a bipartite quantum system whose input state has a prescribed level of entanglement, characterized by a lower bound on the entanglement entropy. Each subsystem is then processed by a local quantum mechanism and measured using local operations only, ensuring that no additional entanglement is generated during the process. Our main result reveals a sharp phase-transition phenomenon in the relation between entanglement and QLDP: below a mechanism-dependent entropy threshold, the optimal privacy leakage level mirrors that of unentangled inputs; beyond this threshold, the privacy leakage level decreases with the entropy, which strictly improves privacy guarantees and can even turn some non-private mechanisms into private ones. The phase-transition phenomenon gives rise to a nonlinear dependence of the privacy leakage level on the entanglement entropy, even though the underlying quantum mechanisms and measurements are linear. We show that the transition is governed by the intrinsic non-convex geometry of the set of entanglement-constrained quantum states, which we parametrize as a smooth manifold and analyze via Riemannian optimization. Our findings demonstrate that entanglement serves as a genuine privacy-enhancing resource, offering a geometric and operational foundation for designing robust privacy-preserving quantum protocols.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.19090v1">Privacy-Preserving Model Transcription with Differentially Private Synthetic Distillation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-01-27T01:51:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bochao Liu, Shiming Ge, Pengju Wang, Shikun Li, Tongliang Liu</p>
    <p><b>Summary:</b> While many deep learning models trained on private datasets have been deployed in various practical tasks, they may pose a privacy leakage risk as attackers could recover informative data or label knowledge from models. In this work, we present \emph{privacy-preserving model transcription}, a data-free model-to-model conversion solution to facilitate model deployment with a privacy guarantee. To this end, we propose a cooperative-competitive learning approach termed \emph{differentially private synthetic distillation} that learns to convert a pretrained model (teacher) into its privacy-preserving counterpart (student) via a trainable generator without access to private data. The learning collaborates with three players in a unified framework and performs alternate optimization: i)~the generator is learned to generate synthetic data, ii)~the teacher and student accept the synthetic data and compute differential private labels by flexible data or label noisy perturbation, and iii)~the student is updated with noisy labels and the generator is updated by taking the student as a discriminator for adversarial training. We theoretically prove that our approach can guarantee differential privacy and convergence. The transcribed student has good performance and privacy protection, while the resulting generator can generate private synthetic data for downstream tasks. Extensive experiments clearly demonstrate that our approach outperforms 26 state-of-the-arts.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.18661v1">Balancing Privacy and Robustness in Coded Computing Under Profiled Workers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-01-26T16:37:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rimpi Borah, J. Harshan, Aaditya Sharma</p>
    <p><b>Summary:</b> In distributed computing with untrusted workers, the assignment of evaluation indices plays a critical role in determining both privacy and robustness. In this work, we study how the placement of unreliable workers within the Numerically Stable Lagrange Coded Computing (NS-LCC) framework influences privacy and the ability to localize Byzantine errors. We derive analytical bounds that quantify how different evaluation-index assignments affect privacy against colluding curious workers and robustness against Byzantine corruption under finite-precision arithmetic. Using these bounds, we formulate optimization problems that identify privacy-optimal and robustness-optimal index placements and show that the resulting assignments are fundamentally different. This exposes that index choices that maximizes privacy degrade error-localization, and vice versa. To jointly navigate this trade-off, we propose a low-complexity greedy assignment strategy that closely approximates the optimal balance between privacy and robustness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.18612v1">Multimodal Privacy-Preserving Entity Resolution with Fully Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-01-26T15:53:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Susim Roy, Nalini Ratha</p>
    <p><b>Summary:</b> The canonical challenge of entity resolution within high-compliance sectors, where secure identity reconciliation is frequently confounded by significant data heterogeneity, including syntactic variations in personal identifiers, is a longstanding and complex problem. To this end, we introduce a novel multimodal framework operating with the voluminous data sets typical of government and financial institutions. Specifically, our methodology is designed to address the tripartite challenge of data volume, matching fidelity, and privacy. Consequently, the underlying plaintext of personally identifiable information remains computationally inaccessible throughout the matching lifecycle, empowering institutions to rigorously satisfy stringent regulatory mandates with cryptographic assurances of client confidentiality while achieving a demonstrably low equal error rate and maintaining computational tractability at scale.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.18511v1">Scaling up Privacy-Preserving ML: A CKKS Implementation of Llama-2-7B</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-26T14:17:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jaiyoung Park, Sejin Park, Jai Hyun Park, Jung Ho Ahn, Jung Hee Cheon, Guillaume Hanrot, Jung Woo Kim, Minje Park, Damien Stehlé</p>
    <p><b>Summary:</b> As large language models (LLMs) become ubiquitous, privacy concerns pertaining to inference inputs keep growing. In this context, fully homomorphic encryption (FHE) has emerged as a primary cryptographic solution to provide non-interactive confidential LLM inference. Existing solutions scale poorly with the input token length, and hence focus either on small models or larger models with a small number of input tokens. They also suffer from the existence of large outlier values. These values have a strong impact on the evaluation of non-linear layers, leading to large-degree polynomial approximation and thus heavy evaluation costs.
  We propose an FHE-based private LLM inference solution that allows thousands of input tokens with only a part of them being encrypted: this fits with a scenario where the context is benign and only part of the input is sensitive. To do so, we suggest an unbalanced chunked prefill framework that processes the private and public parts of the input tokens differently. Our framework contains plaintext-plaintext, plaintext-ciphertext and ciphertext-ciphertext computational components. We adopt different strategies and ingredients for each component. We also devise new homomorphic algorithms for specific matrix multiplication and polynomial evaluation tasks encountered during LLM inference.
  Furthermore, without retraining, we tailor the LLM inference algorithm to reduce the ranges of outlier values: we leverage machine learning strategies (token prepending and rotations) to mitigate the impact of the outliers on non-linear layers.
  Based on these ingredients, we describe a CKKS-based end-to-end implementation of Llama-2-7B private inference for up to 4096 input tokens, of which the last 128 are encrypted. On a cluster of 8~NVIDIA RTX-4090 GPUs, inference takes 85s for summarization and 33s for generation per output token.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.18497v1">BAIT: Visual-illusion-inspired Privacy Preservation for Mobile Data Visualization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-01-26T13:58:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sizhe Cheng, Songheng Zhang, Dong Ma, Yong Wang</p>
    <p><b>Summary:</b> With the prevalence of mobile data visualizations, there have been growing concerns about their privacy risks, especially shoulder surfing attacks. Inspired by prior research on visual illusion, we propose BAIT, a novel approach to automatically generate privacy-preserving visualizations by stacking a decoy visualization over a given visualization. It allows visualization owners at proximity to clearly discern the original visualization and makes shoulder surfers at a distance be misled by the decoy visualization, by adjusting different visual channels of a decoy visualization (e.g., shape, position, tilt, size, color and spatial frequency). We explicitly model human perception effect at different viewing distances to optimize the decoy visualization design. Privacy-preserving examples and two in-depth user studies demonstrate the effectiveness of BAIT in both controlled lab study and real-world scenarios.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.18842v2">GUIGuard: Toward a General Framework for Privacy-Preserving GUI Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-01-26T11:33:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yanxi Wang, Zhiling Zhang, Wenbo Zhou, Weiming Zhang, Jie Zhang, Qiannan Zhu, Yu Shi, Shuxin Zheng, Jiyan He</p>
    <p><b>Summary:</b> GUI agents enable end-to-end automation through direct perception of and interaction with on-screen interfaces. However, these agents frequently access interfaces containing sensitive personal information, and screenshots are often transmitted to remote models, creating substantial privacy risks. These risks are particularly severe in GUI workflows: GUIs expose richer, more accessible private information, and privacy risks depend on interaction trajectories across sequential scenes. We propose GUIGuard, a three-stage framework for privacy-preserving GUI agents: (1) privacy recognition, (2) privacy protection, and (3) task execution under protection. We further construct GUIGuard-Bench, a cross-platform benchmark with 630 trajectories and 13,830 screenshots, annotated with region-level privacy grounding and fine-grained labels of risk level, privacy category, and task necessity. Evaluations reveal that existing agents exhibit limited privacy recognition, with state-of-the-art models achieving only 13.3% accuracy on Android and 1.4% on PC. Under privacy protection, task-planning semantics can still be maintained, with closed-source models showing stronger semantic consistency than open-source ones. Case studies on MobileWorld show that carefully designed protection strategies achieve higher task accuracy while preserving privacy. Our results highlight privacy recognition as a critical bottleneck for practical GUI agents. Project: https://futuresis.github.io/GUIGuard-page/</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.18125v1">Understanding Users' Privacy Reasoning and Behaviors During Chatbot Use to Support Meaningful Agency in Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-01-26T04:13:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohammad Hadi Nezhad, Francisco Enrique Vicente Castro, Ivon Arroyo</p>
    <p><b>Summary:</b> Conversational agents (CAs) (e.g., chatbots) are increasingly used in settings where users disclose sensitive information, raising significant privacy concerns. Because privacy judgments are highly contextual, supporting users to engage in privacy-protective actions during chatbot interactions is essential. However, enabling meaningful engagement requires a deeper understanding of how users currently reason about and manage sensitive information during realistic chatbot use scenarios. To investigate this, we qualitatively examined computer science (undergraduate and masters) students' in-the-moment disclosure and protection behaviors, as well as the reasoning underlying these behaviors, across a range of realistic chatbot tasks. Participants used a simulated ChatGPT interface with and without a privacy notice panel that intercepts message submissions, highlights potentially sensitive information, and offers privacy protective actions. The panel supports anonymization through retracting, faking, and generalizing, and surfaces two of ChatGPT's built-in privacy controls to improve their discoverability. Drawing on interaction logs, think-alouds, and survey responses, we analyzed how the panel fostered privacy awareness, encouraged protective actions, and supported context-specific reasoning about what information to protect and how. We further discuss design opportunities for tools that provide users greater and more meaningful agency in protecting sensitive information during CA interactions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.18834v1">CanaryBench: Stress Testing Privacy Leakage in Cluster-Level Conversation Summaries</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-01-25T20:30:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Deep Mehta</p>
    <p><b>Summary:</b> Aggregate analytics over conversational data are increasingly used for safety monitoring, governance, and product analysis in large language model systems. A common practice is to embed conversations, cluster them, and publish short textual summaries describing each cluster. While raw conversations may never be exposed, these derived summaries can still pose privacy risks if they contain personally identifying information (PII) or uniquely traceable strings copied from individual conversations.
  We introduce CanaryBench, a simple and reproducible stress test for privacy leakage in cluster-level conversation summaries. CanaryBench generates synthetic conversations with planted secret strings ("canaries") that simulate sensitive identifiers. Because canaries are known a priori, any appearance of these strings in published summaries constitutes a measurable leak.
  Using TF-IDF embeddings and k-means clustering on 3,000 synthetic conversations (24 topics) with a canary injection rate of 0.60, we evaluate an intentionally extractive example snippet summarizer that models quote-like reporting. In this configuration, we observe canary leakage in 50 of 52 canary-containing clusters (cluster-level leakage rate 0.961538), along with nonzero regex-based PII indicator counts. A minimal defense combining a minimum cluster-size publication threshold (k-min = 25) and regex-based redaction eliminates measured canary leakage and PII indicator hits in the reported run while maintaining a similar cluster-coherence proxy. We position this work as a societal impacts contribution centered on privacy risk measurement for published analytics artifacts rather than raw user data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.17935v1">FedGraph-VASP: Privacy-Preserving Federated Graph Learning with Post-Quantum Security for Cross-Institutional Anti-Money Laundering</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B">
  <p><b>Published on:</b> 2026-01-25T18:14:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Daniel Commey, Matilda Nkoom, Yousef Alsenani, Sena G. Hounsinou, Garth V. Crosby</p>
    <p><b>Summary:</b> Virtual Asset Service Providers (VASPs) face a fundamental tension between regulatory compliance and user privacy when detecting cross-institutional money laundering. Current approaches require either sharing sensitive transaction data or operating in isolation, leaving critical cross-chain laundering patterns undetected. We present FedGraph-VASP, a privacy-preserving federated graph learning framework that enables collaborative anti-money laundering (AML) without exposing raw user data. Our key contribution is a Boundary Embedding Exchange protocol that shares only compressed, non-invertible graph neural network representations of boundary accounts. These exchanges are secured using post-quantum cryptography, specifically the NIST-standardized Kyber-512 key encapsulation mechanism combined with AES-256-GCM authenticated encryption. Experiments on the Elliptic Bitcoin dataset with realistic Louvain partitioning show that FedGraph-VASP achieves an F1-score of 0.508, outperforming the state-of-the-art generative baseline FedSage+ (F1 = 0.453) by 12.1 percent on binary fraud detection. We further show robustness under low-connectivity settings where generative imputation degrades performance, while approaching centralized performance (F1 = 0.620) in high-connectivity regimes. We additionally evaluate generalization on an Ethereum fraud detection dataset, where FedGraph-VASP (F1 = 0.635) is less effective under sparse cross-silo connectivity, while FedSage+ excels (F1 = 0.855), outperforming even local training (F1 = 0.785). These results highlight a topology-dependent trade-off: embedding exchange benefits connected transaction graphs, whereas generative imputation can dominate in highly modular sparse graphs. A privacy audit shows embeddings are only partially invertible (R^2 = 0.32), limiting exact feature recovery.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.17909v1">From Statistical Disclosure Control to Fair AI: Navigating Fundamental Tradeoffs in Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-25T17:07:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Adriana Watson</p>
    <p><b>Summary:</b> Differential privacy has become the gold standard for privacy-preserving machine learning systems. Unfortunately, subsequent work has primarily fixated on the privacy-utility tradeoff, leaving the subject of fairness constraints undervalued and under-researched. This paper provides a systematic treatment connecting three threads: (1) Dalenius's impossibility results for semantic privacy, (2) Dwork's differential privacy as an achievable alternative, and (3) emerging impossibility results from the addition of a fairness requirement. Through concrete examples and technical analysis, the three-way Pareto frontier between privacy, utility, and fairness is demonstrated to showcase the fundamental limits on what can be simultaneously achieved. In this work, these limits are characterized, the impact on minority groups is demonstrated, and practical guidance for navigating these tradeoffs are provided. This forms a unified framework synthesizing scattered results to help practitioners and policymakers make informed decisions when deploying private fair learning systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.17644v2">A Systemic Evaluation of Multimodal RAG Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-01-25T01:37:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ali Al-Lawati, Suhang Wang</p>
    <p><b>Summary:</b> The growing adoption of multimodal Retrieval-Augmented Generation (mRAG) pipelines for vision-centric tasks (e.g. visual QA) introduces important privacy challenges. In particular, while mRAG provides a practical capability to connect private datasets to improve model performance, it risks the leakage of private information from these datasets during inference. In this paper, we perform an empirical study to analyze the privacy risks inherent in the mRAG pipeline observed through standard model prompting. Specifically, we implement a case study that attempts to infer the inclusion of a visual asset, e.g. image, in the mRAG, and if present leak the metadata, e.g. caption, related to it. Our findings highlight the need for privacy-preserving mechanisms and motivate future research on mRAG privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.17569v1">Improving User Privacy in Personalized Generation: Client-Side Retrieval-Augmented Modification of Server-Side Generated Speculations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2026-01-24T19:46:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alireza Salemi, Hamed Zamani</p>
    <p><b>Summary:</b> Personalization is crucial for aligning Large Language Model (LLM) outputs with individual user preferences and background knowledge. State-of-the-art solutions are based on retrieval augmentation, where relevant context from a user profile is retrieved for LLM consumption. These methods deal with a trade-off between exposing retrieved private data to cloud providers and relying on less capable local models. We introduce $P^3$, an interactive framework for high-quality personalization without revealing private profiles to server-side LLMs. In $P^3$, a large server-side model generates a sequence of $k$ draft tokens based solely on the user query, while a small client-side model, with retrieval access to the user's private profile, evaluates and modifies these drafts to better reflect user preferences. This process repeats until an end token is generated. Experiments on LaMP-QA, a recent benchmark consisting of three personalized question answering datasets, show that $P^3$ consistently outperforms both non-personalized server-side and personalized client-side baselines, achieving statistically significant improvements of $7.4%$ to $9%$ on average. Importantly, $P^3$ recovers $90.3%$ to $95.7%$ of the utility of a ``leaky'' upper-bound scenario in which the full profile is exposed to the large server-side model. Privacy analyses, including linkability and attribute inference attacks, indicate that $P^3$ preserves the privacy of a non-personalized server-side model, introducing only marginal additional leakage ($1.5%$--$3.5%$) compared to submitting a query without any personal context. Additionally, the framework is efficient for edge deployment, with the client-side model generating only $9.2%$ of the total tokens. These results demonstrate that $P^3$ provides a practical, effective solution for personalized generation with improved privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.17373v1">"Privacy across the boundary": Examining Perceived Privacy Risk Across Data Transmission and Sharing Ranges of Smart Home Personal Assistants</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-01-24T08:42:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuning Zhang, Shixuan Li, Haobin Xing, Jiarui Liu, Yan Kong, Xin Yi, Hewu Li</p>
    <p><b>Summary:</b> As Smart Home Personal Assistants (SPAs) evolve into social agents, understanding user privacy necessitates interpersonal communication frameworks, such as Privacy Boundary Theory (PBT). To ground our investigation, our three-phase preliminary study (1) identified transmission and sharing ranges as key boundary-related risk factors, (2) categorized relevant SPA functions and data types, and (3) analyzed commercial practices, revealing widespread data sharing and non-transparent safeguards. A subsequent mixed-methods study (N=412 survey, N=40 interviews among the survey participants) assessed users' perceived privacy risks across data types, transmission ranges and sharing ranges. Results demonstrate a significant, non-linear escalation in perceived risk when data crosses two critical boundaries: the `public network' (transmission) and `third parties' (sharing). This boundary effect holds robustly across data types and demographics. Furthermore, risk perception is modulated by data attributes (e.g., social relational data), and contextual privacy calculus. Conversely, anonymization safeguards show limited efficacy especially for third-party sharing, a finding attributed to user distrust. These findings empirically ground PBT in the SPA context and inform design of boundary-aware privacy protection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.17368v1">A Scoping Review and Guidelines on Privacy Policy's Visualization from an HCI Perspective</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-01-24T08:22:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuning Zhang, Eve He, Sixing Tao, Yuting Yang, Ying Ma, Ailei Wang, Xin Yi, Hewu Li</p>
    <p><b>Summary:</b> Privacy Policies are a cornerstone of informed consent, yet a persistent gap exists between their legal intent and practical efficacy. Despite decades of Human-Computer Interaction (HCI) research proposing various visualizations, user comprehension remains low, and designs rarely see widespread adoption. To understand this landscape and chart a path forward, we synthesized 65 top-tier papers using a framework adapted from the user-centered design lifecycle. Our analysis presented findings of the field's evolution across four dimensions: (1) the trade-off between information load and decision efficacy, which demonstrates a shift from augmenting disclosures to prioritizing information condensation and cognitive load management to counter the inefficacy of comprehensive texts, (2) the co-evolutionary dynamic of design and automation, revealing that complex design ambitions such as context-awareness drove the need for advanced NLP, while recent LLM breakthroughs are enabling the semantic interpretation required to realize those designs, (3) the tension between generality and specificity, highlighting the divergence between standardized, cross-platform solutions and the increasing necessity for specialized, context-aware interaction patterns in IoT and immersive environments, and (4) balancing stakeholder opinions, which shows that visualization efficacy is constrained by the complex interplay of regulatory mandates, developer capabilities and provider incentives. We conclude by outlining four critical challenges for future research.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.17360v1">Robust Privacy: Inference-Time Privacy through Certified Robustness</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-24T08:13:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiankai Jin, Xiangzheng Zhang, Zhao Liu, Deyue Zhang, Quanchen Zou</p>
    <p><b>Summary:</b> Machine learning systems can produce personalized outputs that allow an adversary to infer sensitive input attributes at inference time. We introduce Robust Privacy (RP), an inference-time privacy notion inspired by certified robustness: if a model's prediction is provably invariant within a radius-$R$ neighborhood around an input $x$ (e.g., under the $\ell_2$ norm), then $x$ enjoys $R$-Robust Privacy, i.e., observing the prediction cannot distinguish $x$ from any input within distance $R$ of $x$. We further develop Attribute Privacy Enhancement (APE) to translate input-level invariance into an attribute-level privacy effect. In a controlled recommendation task where the decision depends primarily on a sensitive attribute, we show that RP expands the set of sensitive-attribute values compatible with a positive recommendation, expanding the inference interval accordingly. Finally, we empirically demonstrate that RP also mitigates model inversion attacks (MIAs) by masking fine-grained input-output dependence. Even at small noise levels ($σ=0.1$), RP reduces the attack success rate (ASR) from 73% to 4% with partial model performance degradation. RP can also partially mitigate MIAs (e.g., ASR drops to 44%) with no model performance degradation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.17183v1">Federated Proximal Optimization for Privacy-Preserving Heart Disease Prediction: A Controlled Simulation Study on Non-IID Clinical Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-01-23T21:18:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Farzam Asad, Junaid Saif Khan, Maria Tariq, Sundus Munir, Muhammad Adnan Khan</p>
    <p><b>Summary:</b> Healthcare institutions have access to valuable patient data that could be of great help in the development of improved diagnostic models, but privacy regulations like HIPAA and GDPR prevent hospitals from directly sharing data with one another. Federated Learning offers a way out to this problem by facilitating collaborative model training without having the raw patient data centralized. However, clinical datasets intrinsically have non-IID (non-independent and identically distributed) features brought about by demographic disparity and diversity in disease prevalence and institutional practices. This paper presents a comprehensive simulation research of Federated Proximal Optimization (FedProx) for Heart Disease prediction based on UCI Heart Disease dataset. We generate realistic non-IID data partitions by simulating four heterogeneous hospital clients from the Cleveland Clinic dataset (303 patients), by inducing statistical heterogeneity by demographic-based stratification. Our experimental results show that FedProx with proximal parameter mu=0.05 achieves 85.00% accuracy, which is better than both centralized learning (83.33%) and isolated local models (78.45% average) without revealing patient privacy. Through generous sheer ablation studies with statistical validation on 50 independent runs we demonstrate that proximal regularization is effective in curbing client drift in heterogeneous environments. This proof-of-concept research offers algorithmic insights and practical deployment guidelines for real-world federated healthcare systems, and thus, our results are directly transferable to hospital IT-administrators, implementing privacy-preserving collaborative learning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.16857v1">Perfect Privacy and Strong Stationary Times for Markovian Sources</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-01-23T16:04:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fangwei Ye, Zonghong Liu, Parimal Parag, Salim El Rouayheb</p>
    <p><b>Summary:</b> We consider the problem of sharing correlated data under a perfect information-theoretic privacy constraint. We focus on redaction (erasure) mechanisms, in which data are either withheld or released unchanged, and measure utility by the average cardinality of the released set, equivalently, the expected Hamming distortion. Assuming the data are generated by a finite time-homogeneous Markov chain, we study the protection of the initial state while maximizing the amount of shared data. We establish a connection between perfect privacy and window-based redaction schemes, showing that erasing data up to a strong stationary time preserves privacy under suitable conditions. We further study an optimal sequential redaction mechanism and prove that it admits an equivalent window interpretation. Interestingly, we show that both mechanisms achieve the optimal distortion while redacting only a constant average number of data points, independent of the data length~$N$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.16825v1">Privacy-Resolution Tradeoff for Adaptive Noisy Twenty Questions Estimation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-01-23T15:23:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chunsong Sun, Lin Zhou</p>
    <p><b>Summary:</b> We revisit noisy twenty questions estimation and study the privacy-resolution tradeoff for adaptive query procedures. Specifically, in twenty questions estimation, there are two players: an oracle and a questioner. The questioner aims to estimate target variables by posing queries to the oracle that knows the variables and using noisy responses to form reliable estimates. Typically, there are adaptive and non-adaptive query procedures. In adaptive querying, one designs the current query using previous queries and their noisy responses while in non-adaptive querying, all queries are posed simultaneously. Generally speaking, adaptive query procedures yield better performance. However, adaptive querying leads to privacy concerns, which were first studied by Tsitsiklis, Xu and Xu (COLT 2018) and by Xu, Xu and Yang (AISTATS 2021) for the noiseless case, where the oracle always provides correct answers to queries. In this paper, we generalize the above results to the more practical noisy case, by proposing a two-stage private query procedure, analyzing its non-asymptotic and second-order asymptotic achievable performance and discussing the impact of privacy concerns. Furthermore, when specialized to the noiseless case, our private query procedure achieves better performance than above-mentioned query procedures (COLT 2018, AISTATS 2021).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.16824v1">Privacy in Human-AI Romantic Relationships: Concerns, Boundaries, and Agency</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-01-23T15:23:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rongjun Ma, Shijing He, Jose Luis Martin-Navarro, Xiao Zhan, Jose Such</p>
    <p><b>Summary:</b> An increasing number of LLM-based applications are being developed to facilitate romantic relationships with AI partners, yet the safety and privacy risks in these partnerships remain largely underexplored. In this work, we investigate privacy in human-AI romantic relationships through an interview study (N=17), examining participants' experiences and privacy perceptions across stages of exploration, intimacy, and dissolution, alongside platforms they used. We found that these relationships took varied forms, from one-to-one to one-to-many, and were shaped by multiple actors, including creators, platforms, and moderators. AI partners were perceived as having agency, actively negotiating privacy boundaries with participants and sometimes encouraging disclosure of personal details. As intimacy deepened, these boundaries became more permeable, though some participants voiced concerns such as conversation exposure and sought to preserve anonymity. Overall, platform affordances and diverse romantic dynamics expand the privacy landscape, underscoring the need to rethink how privacy is constructed in human-AI intimacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.16658v1">Talking about privacy always feels like opening a can of worms. How Intimate Partners Navigate Boundary-Setting in Mobile Phone Without Words</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-01-23T11:21:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sima Amirkhani, Mahla Fatemeh Alizadeh, Farzaneh Gerami, Dave Randall, Gunnar Stevens</p>
    <p><b>Summary:</b> Mobile phones, as simultaneously personal and shared technologies, complicate how partners manage digital privacy in intimate relationships. While prior research has examined device-access practices, explicit privacy-rule negotiation, and toxic practices such as surveillance, little is known about how couples manage digital privacy without direct discussion in everyday relationships. To address this gap, we ask: How is digital privacy managed nonverbally and across different media on mobile phones? Drawing on 20 semi-structured interviews, we find that partners often regulate privacy practices through privacy silence -- the intentional avoidance of privacy-related conversations. We identify five motivations for leaving boundaries unspoken: perceiving privacy as unnecessary in intimacy, assuming implicit respect for boundaries, signaling trust and closeness, avoiding potential conflict or harm, and responding to broader societal and cultural expectations that discourage explicit privacy talk. We also identify a hierarchical grouping of content-specific privacy sensitivities, ranging from highly private domains such as financial data to lower-risk domains such as streaming accounts, and show how these priorities shift across relationship stages. These findings show how silence, culture, and content sensitivity shape everyday boundary-setting and underscore the relational and emotional dynamics underpinning mobile phone privacy management.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.16354v1">NOIR: Privacy-Preserving Generation of Code with Open-Source LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-01-22T22:39:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Khoa Nguyen, Khiem Ton, NhatHai Phan, Issa Khalil, Khang Tran, Cristian Borcea, Ruoming Jin, Abdallah Khreishah, My T. Thai</p>
    <p><b>Summary:</b> Although boosting software development performance, large language model (LLM)-powered code generation introduces intellectual property and data security risks rooted in the fact that a service provider (cloud) observes a client's prompts and generated code, which can be proprietary in commercial systems. To mitigate this problem, we propose NOIR, the first framework to protect the client's prompts and generated code from the cloud. NOIR uses an encoder and a decoder at the client to encode and send the prompts' embeddings to the cloud to get enriched embeddings from the LLM, which are then decoded to generate the code locally at the client. Since the cloud can use the embeddings to infer the prompt and the generated code, NOIR introduces a new mechanism to achieve indistinguishability, a local differential privacy protection at the token embedding level, in the vocabulary used in the prompts and code, and a data-independent and randomized tokenizer on the client side. These components effectively defend against reconstruction and frequency analysis attacks by an honest-but-curious cloud. Extensive analysis and results using open-source LLMs show that NOIR significantly outperforms existing baselines on benchmarks, including the Evalplus (MBPP and HumanEval, Pass@1 of 76.7 and 77.4), and BigCodeBench (Pass@1 of 38.7, only a 1.77% drop from the original LLM) under strong privacy against attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.16160v1">CONTEX-T: Contextual Privacy Exploitation via Transformer Spectral Analysis for IoT Device Fingerprinting</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-22T18:03:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nazmul Islam, Mohammad Zulkernine</p>
    <p><b>Summary:</b> The rapid expansion of internet of things (IoT) devices have created a pervasive ecosystem where encrypted wireless communications serve as the primary privacy and security protection mechanism. While encryption effectively protects message content, packet metadata and statistics inadvertently expose device identities and user contexts. Various studies have exploited raw packet statistics and their visual representations for device fingerprinting and identification. However, these approaches remain confined to the spatial domain with limited feature representation. Therefore, this paper presents CONTEX-T, a novel framework that exploits contextual privacy vulnerabilities using spectral representation of encrypted wireless traffic for IoT device characterization. The experiments show that spectral analysis provides new and rich feature representation for covert reconnaissance attacks, revealing a complex and expanding threat landscape that would require robust countermeasures for IoT security management. CONTEXT-T first transforms raw packet length sequences into time-frequency spectral representations and then utilizes transformer-based spectral analysis for the device identification. We systematically evaluated multiple spectral representation techniques and transformer-based models across encrypted traffic samples from various IoT devices. CONTEXT-T effectively exploited privacy vulnerabilities and achieved device classification accuracy exceeding 99% across all devices while remaining completely passive and undetectable.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.16080v1">Towards a Goal-Centric Assessment of Requirements Engineering Methods for Privacy by Design</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-01-22T16:22:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Oleksandr Kosenkov, Ehsan Zabardast, Jannik Fischbach, Tony Gorschek, Daniel Mendez</p>
    <p><b>Summary:</b> Implementing privacy by design (PbD) according to the General Data Protection Regulation (GDPR) is met with a growing number of requirements engineering (RE) approaches. However, the question of which RE method for PbD fits best the goals of organisations remains a challenge. We report our endeavor to close this gap by synthesizing a goal-centric approach for PbD methods assessment. We used literature review, interviews, and validation with practitioners to achieve the goal of our study. As practitioners do not approach PbD systematically, we suggest that RE methods for PbD should be assessed against organisational goals, rather than process characteristics only. We hope that, when further developed, the goal-centric approach could support the development, selection, and tailoring of RE practices for PbD.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.15697v1">Balancing Security and Privacy: The Pivotal Role of AI in Modern Healthcare Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-22T06:51:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Binu V P, Deepthy K Bhaskar, Minimol B</p>
    <p><b>Summary:</b> As digital threats continue to grow, organizations must find ways to enhance security while protecting user privacy. This paper explores how artificial intelligence (AI) plays a crucial role in achieving this balance. AI technologies can improve security by detecting threats, monitoring systems, and automating responses. However, using AI also raises privacy concerns that need careful consideration.We examine real-world examples from the healthcare sector to illustrate how organizations can implement AI solutions that strengthen security without compromising patient privacy. Additionally, we discuss the importance of creating transparent AI systems and adhering to privacy regulations.Ultimately, this paper provides insights and recommendations for integrating AI into healthcare security practices, helping organizations navigate the challenges of modern management while keeping patient data safe.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.15682v1">Tight Bounds for Gaussian Mean Estimation under Personalized Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2026-01-22T06:04:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wei Dong, Li Ge</p>
    <p><b>Summary:</b> We study mean estimation for Gaussian distributions under \textit{personalized differential privacy} (PDP), where each record has its own privacy budget. PDP is commonly considered in two variants: \textit{bounded} and \textit{unbounded} PDP. In bounded PDP, the privacy budgets are public and neighboring datasets differ by replacing one record. In unbounded PDP, neighboring datasets differ by adding or removing a record; consequently, an algorithm must additionally protect participation information, making both the dataset size and the privacy profile sensitive. Existing works have only studied mean estimation over bounded distributions under bounded PDP. Different from mean estimation for distributions with bounded range, where each element can be treated equally and we only need to consider the privacy diversity of elements, the challenge for Gaussian is that, elements can have very different contributions due to the unbounded support. we need to jointly consider the privacy information and the data values. Such a problem becomes even more challenging under unbounded PDP, where the privacy information is protected and the way to compute the weights becomes unclear. In this paper, we address these challenges by proposing optimal Gaussian mean estimators under both bounded and unbounded PDP, where in each setting we first derive lower bounds for both problems, following PDP mean estimators with the algorithmic upper bounds matching the corresponding lower bounds up to logarithmic factors.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.15595v1">Data-Free Privacy-Preserving for LLMs via Model Inversion and Selective Unlearning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-22T02:43:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xinjie Zhou, Zhihui Yang, Lechao Cheng, Sai Wu, Gang Chen</p>
    <p><b>Summary:</b> Large language models (LLMs) exhibit powerful capabilities but risk memorizing sensitive personally identifiable information (PII) from their training data, posing significant privacy concerns. While machine unlearning techniques aim to remove such data, they predominantly depend on access to the training data. This requirement is often impractical, as training data in real-world deployments is commonly proprietary or inaccessible. To address this limitation, we propose Data-Free Selective Unlearning (DFSU), a novel privacy-preserving framework that removes sensitive PII from an LLM without requiring its training data. Our approach first synthesizes pseudo-PII through language model inversion, then constructs token-level privacy masks for these synthetic samples, and finally performs token-level selective unlearning via a contrastive mask loss within a low-rank adaptation (LoRA) subspace. Extensive experiments on the AI4Privacy PII-Masking dataset using Pythia models demonstrate that our method effectively removes target PII while maintaining model utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.15220v1">Privacy Collapse: Benign Fine-Tuning Can Break Contextual Privacy in Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-01-21T17:53:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anmol Goel, Cornelius Emde, Sangdoo Yun, Seong Joon Oh, Martin Gubri</p>
    <p><b>Summary:</b> We identify a novel phenomenon in language models: benign fine-tuning of frontier models can lead to privacy collapse. We find that diverse, subtle patterns in training data can degrade contextual privacy, including optimisation for helpfulness, exposure to user information, emotional and subjective dialogue, and debugging code printing internal variables, among others. Fine-tuned models lose their ability to reason about contextual privacy norms, share information inappropriately with tools, and violate memory boundaries across contexts. Privacy collapse is a ``silent failure'' because models maintain high performance on standard safety and utility benchmarks whilst exhibiting severe privacy vulnerabilities. Our experiments show evidence of privacy collapse across six models (closed and open weight), five fine-tuning datasets (real-world and controlled data), and two task categories (agentic and memory-based). Our mechanistic analysis reveals that privacy representations are uniquely fragile to fine-tuning, compared to task-relevant features which are preserved. Our results reveal a critical gap in current safety evaluations, in particular for the deployment of specialised agents.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.15061v1">Differential Privacy Image Generation with Reconstruction Loss and Noise Injection Using an Error Feedback SGD</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-01-21T15:07:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qiwei Ma, Jun Zhang</p>
    <p><b>Summary:</b> Traditional data masking techniques such as anonymization cannot achieve the expected privacy protection while ensuring data utility for privacy-preserving machine learning. Synthetic data plays an increasingly important role as it generates a large number of training samples and prevents information leakage in real data. The existing methods suffer from the repeating trade-off processes between privacy and utility. We propose a novel framework for differential privacy generation, which employs an Error Feedback Stochastic Gradient Descent(EFSGD) method and introduces a reconstruction loss and noise injection mechanism into the training process. We generate images with higher quality and usability under the same privacy budget as the related work. Extensive experiments demonstrate the effectiveness and generalization of our proposed framework for both grayscale and RGB images. We achieve state-of-the-art results over almost all metrics on three benchmarks: MNIST, Fashion-MNIST, and CelebA.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.15042v1">Federated Transformer-GNN for Privacy-Preserving Brain Tumor Localization with Modality-Level Explainability</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-01-21T14:46:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Andrea Protani, Riccardo Taiello, Marc Molina Van Den Bosch, Luigi Serio</p>
    <p><b>Summary:</b> Deep learning models for brain tumor analysis require large and diverse datasets that are often siloed across healthcare institutions due to privacy regulations. We present a federated learning framework for brain tumor localization that enables multi-institutional collaboration without sharing sensitive patient data. Our method extends a hybrid Transformer-Graph Neural Network architecture derived from prior decoder-free supervoxel GNNs and is deployed within CAFEIN\textsuperscript{\textregistered}, CERN's federated learning platform designed for healthcare environments. We provide an explainability analysis through Transformer attention mechanisms that reveals which MRI modalities drive the model predictions. Experiments on the BraTS dataset demonstrate a key finding: while isolated training on individual client data triggers early stopping well before reaching full training capacity, federated learning enables continued model improvement by leveraging distributed data, ultimately matching centralized performance. This result provides strong justification for federated learning when dealing with complex tasks and high-dimensional input data, as aggregating knowledge from multiple institutions significantly benefits the learning process. Our explainability analysis, validated through rigorous statistical testing on the full test set (paired t-tests with Bonferroni correction), reveals that deeper network layers significantly increase attention to T2 and FLAIR modalities ($p<0.001$, Cohen's $d$=1.50), aligning with clinical practice.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.14980v1">Parallel Collaborative ADMM Privacy Computing and Adaptive GPU Acceleration for Distributed Edge Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-01-21T13:28:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mengchun Xia, Zhicheng Dong, Donghong Cai, Fang Fang, Lisheng Fan, Pingzhi Fan</p>
    <p><b>Summary:</b> Distributed computing has been widely applied in distributed edge networks for reducing the processing burden of high-dimensional data centralization, where a high-dimensional computational task is decomposed into multiple low-dimensional collaborative processing tasks or multiple edge nodes use distributed data to train a global model. However, the computing power of a single-edge node is limited, and collaborative computing will cause information leakage and excessive communication overhead. In this paper, we design a parallel collaborative distributed alternating direction method of multipliers (ADMM) and propose a three-phase parallel collaborative ADMM privacy computing (3P-ADMM-PC2) algorithm for distributed computing in edge networks, where the Paillier homomorphic encryption is utilized to protect data privacy during interactions. Especially, a quantization method is introduced, which maps the real numbers to a positive integer interval without affecting the homomorphic operations. To address the architectural mismatch between large-integer and Graphics Processing Unit (GPU) computing, we transform high-bitwidth computations into low-bitwidth matrix and vector operations. Thus the GPU can be utilized to implement parallel encryption and decryption computations with long keys. Finally, a GPU-accelerated 3P-ADMM-PC2 is proposed to optimize the collaborative computing tasks. Meanwhile, large-scale computational tasks are conducted in network topologies with varying numbers of edge nodes. Experimental results demonstrate that the proposed 3P-ADMM-PC2 has excellent mean square error performance, which is close to that of distributed ADMM without privacy-preserving. Compared to centralized ADMM and distributed ADMM implemented with Central Processing Unit (CPU) computation, the proposed scheme demonstrates a significant speedup ratio.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.17050v1">Single-Pixel Vision-Language Model for Intrinsic Privacy-Preserving Behavioral Intelligence</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-01-21T09:11:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hongjun An, Yiliang Song, Jiawei Shao, Zhe Sun, Xuelong Li</p>
    <p><b>Summary:</b> Adverse social interactions, such as bullying, harassment, and other illicit activities, pose significant threats to individual well-being and public safety, leaving profound impacts on physical and mental health. However, these critical events frequently occur in privacy-sensitive environments like restrooms, and changing rooms, where conventional surveillance is prohibited or severely restricted by stringent privacy regulations and ethical concerns. Here, we propose the Single-Pixel Vision-Language Model (SP-VLM), a novel framework that reimagines secure environmental monitoring. It achieves intrinsic privacy-by-design by capturing human dynamics through inherently low-dimensional single-pixel modalities and inferring complex behavioral patterns via seamless vision-language integration. Building on this framework, we demonstrate that single-pixel sensing intrinsically suppresses identity recoverability, rendering state-of-the-art face recognition systems ineffective below a critical sampling rate. We further show that SP-VLM can nonetheless extract meaningful behavioral semantics, enabling robust anomaly detection, people counting, and activity understanding from severely degraded single-pixel observations. Combining these findings, we identify a practical sampling-rate regime in which behavioral intelligence emerges while personal identity remains strongly protected. Together, these results point to a human-rights-aligned pathway for safety monitoring that can support timely intervention without normalizing intrusive surveillance in privacy-sensitive spaces.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.14725v1">Differential Privacy on Affine Manifolds: Geometrically Confined Privacy in Linear Dynamical Systems</a></h3>
  
  <p><b>Published on:</b> 2026-01-21T07:30:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zihao Ren, Lei Wang, Deming Yuan, Guodong Shi</p>
    <p><b>Summary:</b> In this paper, we present a comprehensive framework for differential privacy over affine manifolds and validate its usefulness in the contexts of differentially private cloud-based control and average consensus. We consider differential privacy mechanisms for linear queries when the input data are constrained to lie on affine manifolds, a structural property that is assumed to be available as prior knowledge to adversaries. In this setting, the definition of neighborhood adjacency must be formulated with respect to the intrinsic geometry of the manifolds. We demonstrate that such affine-manifold constraints can fundamentally alter the attainable privacy levels relative to the unconstrained case. In particular, we derive necessary and sufficient conditions under which differential privacy can be realized via structured noise injection mechanisms, wherein correlated Gaussian or Laplace noise distributions, rather than i.i.d. perturbations, are calibrated to the dataset. Based on these characterizations, we develop explicit noise calibration procedures that guarantee the tight realization of any prescribed privacy budget with a matching noise magnitude. Finally, we show that the proposed framework admits direct applications to linear dynamical systems ranging from differentially private cloud-based control to privacy-preserving average consensus, all of which naturally involve affine-manifold constraints. The established theoretical results are illustrated through numerical examples.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.14660v1">NeuroFilter: Privacy Guardrails for Conversational LLM Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-01-21T05:16:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Saswat Das, Ferdinando Fioretto</p>
    <p><b>Summary:</b> This work addresses the computational challenge of enforcing privacy for agentic Large Language Models (LLMs), where privacy is governed by the contextual integrity framework. Indeed, existing defenses rely on LLM-mediated checking stages that add substantial latency and cost, and that can be undermined in multi-turn interactions through manipulation or benign-looking conversational scaffolding. Contrasting this background, this paper makes a key observation: internal representations associated with privacy-violating intent can be separated from benign requests using linear structure. Using this insight, the paper proposes NeuroFilter, a guardrail framework that operationalizes contextual integrity by mapping norm violations to simple directions in the model's activation space, enabling detection even when semantic filters are bypassed. The proposed filter is also extended to capture threats arising during long conversations using the concept of activation velocity, which measures cumulative drift in internal representations across turns. A comprehensive evaluation across over 150,000 interactions and covering models from 7B to 70B parameters, illustrates the strong performance of NeuroFilter in detecting privacy attacks while maintaining zero false positives on benign prompts, all while reducing the computational inference cost by several orders of magnitude when compared to LLM-based agentic privacy defenses.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.14597v1">Optimality of Staircase Mechanisms for Vector Queries under Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2026-01-21T02:35:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> James Melbourne, Mario Diaz, Shahab Asoodeh</p>
    <p><b>Summary:</b> We study the optimal design of additive mechanisms for vector-valued queries under $ε$-differential privacy (DP). Given only the sensitivity of a query and a norm-monotone cost function measuring utility loss, we ask which noise distribution minimizes expected cost among all additive $ε$-DP mechanisms. Using convex rearrangement theory, we show that this infinite-dimensional optimization problem admits a reduction to a one-dimensional compact and convex family of radially symmetric distributions whose extreme points are the staircase distributions. As a consequence, we prove that for any dimension, any norm, and any norm-monotone cost function, there exists an $ε$-DP staircase mechanism that is optimal among all additive mechanisms. This result resolves a conjecture of Geng, Kairouz, Oh, and Viswanath, and provides a geometric explanation for the emergence of staircase mechanisms as extremal solutions in differential privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.13824v1">ELSA: Efficient LLM-Centric Split Aggregation for Privacy-Aware Hierarchical Federated Learning over Resource-Constrained Edge Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-20T10:33:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaohong Yang, Tong Xie, Minghui Liwang, Chikai Shang, Yang Lu, Zhenzhen Jiao, Liqun Fu, Seyyedali Hosseinalipour</p>
    <p><b>Summary:</b> Training large language models (LLMs) at the network edge faces fundamental challenges arising from device resource constraints, severe data heterogeneity, and heightened privacy risks. To address these, we propose ELSA (Efficient LLM-centric Split Aggregation), a novel framework that systematically integrates split learning (SL) and hierarchical federated learning (HFL) for distributed LLM fine-tuning over resource-constrained edge networks. ELSA introduces three key innovations. First, it employs a task-agnostic, behavior-aware client clustering mechanism that constructs semantic fingerprints using public probe inputs and symmetric KL divergence, further enhanced by prediction-consistency-based trust scoring and latency-aware edge assignment to jointly address data heterogeneity, client unreliability, and communication constraints. Second, it splits the LLM into three parts across clients and edge servers, with the cloud used only for adapter aggregation, enabling an effective balance between on-device computation cost and global convergence stability. Third, it incorporates a lightweight communication scheme based on computational sketches combined with semantic subspace orthogonal perturbation (SS-OP) to reduce communication overhead while mitigating privacy leakage during model exchanges. Experiments across diverse NLP tasks demonstrate that ELSA consistently outperforms state-of-the-art methods in terms of adaptability, convergence behavior, and robustness, establishing a scalable and privacy-aware solution for edge-side LLM fine-tuning under resource constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.13698v1">Does Privacy Always Harm Fairness? Data-Dependent Trade-offs via Chernoff Information Neural Estimation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2026-01-20T07:51:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arjun Nichani, Hsiang Hsu,  Chun-Fu,  Chen, Haewon Jeong</p>
    <p><b>Summary:</b> Fairness and privacy are two vital pillars of trustworthy machine learning. Despite extensive research on these individual topics, the relationship between fairness and privacy has received significantly less attention. In this paper, we utilize the information-theoretic measure Chernoff Information to highlight the data-dependent nature of the relationship among the triad of fairness, privacy, and accuracy. We first define Noisy Chernoff Difference, a tool that allows us to analyze the relationship among the triad simultaneously. We then show that for synthetic data, this value behaves in 3 distinct ways (depending on the distribution of the data). We highlight the data distributions involved in these cases and explore their fairness and privacy implications. Additionally, we show that Noisy Chernoff Difference acts as a proxy for the steepness of the fairness-accuracy curves. Finally, we propose a method for estimating Chernoff Information on data from unknown distributions and utilize this framework to examine the triad dynamic on real datasets. This work builds towards a unified understanding of the fairness-privacy-accuracy relationship and highlights its data-dependent nature.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.13342v1">Privacy Starts with UI: Privacy Patterns and Designer Perspectives in UI/UX Practice</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-01-19T19:24:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anxhela Maloku, Alexandra Klymenko, Stephen Meisenbacher, Florian Matthes</p>
    <p><b>Summary:</b> In the study of Human-Computer Interaction, privacy is often seen as a core issue, and it has been explored directly in connection with User Interface (UI) and User Experience (UX) design. We systematically investigate the key considerations and factors for privacy in UI/UX, drawing upon the extant literature and 15 semi-structured interviews with experts working in the field. These insights lead to the synthesis of 14 primary design considerations for privacy in UI/UX, as well as 14 key factors under four main axes affecting privacy work therein. From these findings, we produce our main research artifact, a UI/UX Privacy Pattern Catalog, which we validate in a series of two interactive workshops and one online survey with UI/UX practitioners. Our work not only systematizes a field growing in both attention and importance, but it also provides an actionable and expert-validated artifact to guide UI/UX designers in realizing privacy-preserving UI/UX design.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.13107v1">Content Leakage in LibriSpeech and Its Impact on the Privacy Evaluation of Speaker Anonymization</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36">
  <p><b>Published on:</b> 2026-01-19T14:44:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Carlos Franzreb, Arnab Das, Tim Polzehl, Sebastian Möller</p>
    <p><b>Summary:</b> Speaker anonymization aims to conceal a speaker's identity, without considering the linguistic content. In this study, we reveal a weakness of Librispeech, the dataset that is commonly used to evaluate anonymizers: the books read by the Librispeech speakers are so distinct, that speakers can be identified by their vocabularies. Even perfect anonymizers cannot prevent this identity leakage. The EdAcc dataset is better in this regard: only a few speakers can be identified through their vocabularies, encouraging the attacker to look elsewhere for the identities of the anonymized speakers. EdAcc also comprises spontaneous speech and more diverse speakers, complementing Librispeech and giving more insights into how anonymizers work.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.13003v1">PrivFly: A Privacy-Preserving Self-Supervised Framework for Rare Attack Detection in IoFT</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-19T12:30:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Safaa Menssouri, El Mehdi Amhoud</p>
    <p><b>Summary:</b> The Internet of Flying Things (IoFT) plays a vital role in modern applications such as aerial surveillance and smart mobility. However, it remains highly vulnerable to cyberattacks that threaten the confidentiality, integrity, and availability of sensitive data. Developing effective intrusion detection systems (IDS) for IoFT networks faces key challenges, including data imbalance, privacy concerns, and the limited capability of traditional models to detect rare but potentially damaging cyber threats. In this work, we propose PrivFly, a privacy-preserving IDS framework that integrates self-supervised representation learning and differential privacy (DP) to enhance detection performance in imbalanced IoFT network traffic. We propose a masked feature reconstruction module for self-supervised pretraining, improving feature representations and boosting rare-class detection. Differential privacy is applied during training to protect sensitive information without significantly compromising model performance. In addition, we conduct a SHapley additive explanations (SHAP)-based analysis to evaluate the impact of DP on feature importance and model behavior. Experimental results on the ECU-IoFT dataset show that PrivFly achieves up to 98% accuracy and 99% F1-score, effectively balancing privacy and detection performance for secure IoFT systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.12922v1">Your Privacy Depends on Others: Collusion Vulnerabilities in Individual Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-19T10:26:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Johannes Kaiser, Alexander Ziller, Eleni Triantafillou, Daniel Rückert, Georgios Kaissis</p>
    <p><b>Summary:</b> Individual Differential Privacy (iDP) promises users control over their privacy, but this promise can be broken in practice. We reveal a previously overlooked vulnerability in sampling-based iDP mechanisms: while conforming to the iDP guarantees, an individual's privacy risk is not solely governed by their own privacy budget, but critically depends on the privacy choices of all other data contributors. This creates a mismatch between the promise of individual privacy control and the reality of a system where risk is collectively determined. We demonstrate empirically that certain distributions of privacy preferences can unintentionally inflate the privacy risk of individuals, even when their formal guarantees are met. Moreover, this excess risk provides an exploitable attack vector. A central adversary or a set of colluding adversaries can deliberately choose privacy budgets to amplify vulnerabilities of targeted individuals. Most importantly, this attack operates entirely within the guarantees of DP, hiding this excess vulnerability. Our empirical evaluation demonstrates successful attacks against 62% of targeted individuals, substantially increasing their membership inference susceptibility. To mitigate this, we propose $(\varepsilon_i,δ_i,\overlineΔ)$-iDP a privacy contract that uses $Δ$-divergences to provide users with a hard upper bound on their excess vulnerability, while offering flexibility to mechanism design. Our findings expose a fundamental challenge to the current paradigm, demanding a re-evaluation of how iDP systems are designed, audited, communicated, and deployed to make excess risks transparent and controllable.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.12693v1">BlocksecRT-DETR: Decentralized Privacy-Preserving and Token-Efficient Federated Transformer Learning for Secure Real-Time Object Detection in ITS</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-19T03:29:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohoshin Ara Tahera, Sabbir Rahman, Shuvalaxmi Dass, Sharif Ullah, Mahmoud Abouyessef</p>
    <p><b>Summary:</b> Federated real-time object detection using transformers in Intelligent Transportation Systems (ITS) faces three major challenges: (1) missing-class non-IID data heterogeneity from geographically diverse traffic environments, (2) latency constraints on edge hardware for high-capacity transformer models, and (3) privacy and security risks from untrusted client updates and centralized aggregation. We propose BlockSecRT-DETR, a BLOCKchain-SECured Real-Time Object DEtection TRansformer framework for ITS that provides a decentralized, token-efficient, and privacy-preserving federated training solution using RT-DETR transformer, incorporating a blockchain-secured update validation mechanism for trustworthy aggregation. In this framework, challenges (1) and (2) are jointly addressed through a unified client-side design that integrates RT-DETR training with a Token Engineering Module (TEM). TEM prunes low-utility tokens, reducing encoder complexity and latency on edge hardware, while aggregated updates mitigate non-IID data heterogeneity across clients. To address challenge (3), BlockSecRT-DETR incorporates a decentralized blockchain-secured update validation mechanism that enables tamper-proof, privacy-preserving, and trust-free authenticated model aggregation without relying on a central server. We evaluated the proposed framework under a missing-class Non-IID partition of the KITTI dataset and conducted a blockchain case study to quantify security overhead. TEM improves inference latency by 17.2% and reduces encoder FLOPs by 47.8%, while maintaining global detection accuracy (89.20% mAP@0.5). The blockchain integration adds 400 ms per round, and the ledger size remains under 12 KB due to metadata-only on-chain storage.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.12447v1">Privacy-Preserving Federated Learning with Verifiable Fairness Guarantees</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-01-18T15:06:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohammed Himayath Ali, Mohammed Aqib Abdullah, Syed Muneer Hussin, Mohammed Mudassir Uddin, Shahnawaz Alam</p>
    <p><b>Summary:</b> Federated learning enables collaborative model training across distributed institutions without centralizing sensitive data; however, ensuring algorithmic fairness across heterogeneous data distributions while preserving privacy remains fundamentally unresolved. This paper introduces CryptoFair-FL, a novel cryptographic framework providing the first verifiable fairness guarantees for federated learning systems under formal security definitions. The proposed approach combines additively homomorphic encryption with secure multi-party computation to enable privacy-preserving verification of demographic parity and equalized odds metrics without revealing protected attribute distributions or individual predictions. A novel batched verification protocol reduces computational complexity from BigO(n^2) to BigO(n \log n) while maintaining (\dparam, \deltap)-differential privacy with dparam = 0.5 and deltap = 10^{-6}. Theoretical analysis establishes information-theoretic lower bounds on the privacy cost of fairness verification, demonstrating that the proposed protocol achieves near-optimal privacy-fairness tradeoffs. Comprehensive experiments across four benchmark datasets (MIMIC-IV healthcare records, Adult Income, CelebA, and a novel FedFair-100 benchmark) demonstrate that CryptoFair-FL reduces fairness violations from 0.231 to 0.031 demographic parity difference while incurring only 2.3 times computational overhead compared to standard federated averaging. The framework successfully defends against attribute inference attacks, maintaining adversarial success probability below 0.05 across all tested configurations. These results establish a practical pathway for deploying fairness-aware federated learning in regulated industries requiring both privacy protection and algorithmic accountability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.12394v1">Privacy via Modulation Rotation and Inter-Symbol Interference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-01-18T13:07:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Morteza Varasteh, Pegah Sharifi</p>
    <p><b>Summary:</b> Two physical-layer mechanisms for achieving user-side differential privacy in communication systems are proposed. Focusing on binary phase-shift keying (BPSK) modulation, differential privacy (DP) is first studied under a deterministic phase rotation applied on the BPSK modulation at the transmitter, while the receiver is assumed to be unaware of the rotation angle. In this setting, privacy is achieved through an effective reduction in the decision distance, resulting in a controlled increase in the bit error rate (BER) without explicit noise injection. Next, a BPSK transmission scheme with intentionally induced inter-symbol interference (ISI) is studied, where the receiver is likewise unaware of the deterministic timing offset that generates the ISI. Unlike the rotated BPSK scheme, the DP obtained via ISI is shown to depend explicitly on the input data distribution. In particular, numerical results demonstrate that, for a fixed ISI parameter, the privacy loss is maximized when the binary input symbols are equiprobable. While conventional DP mechanisms rely on artificially added noise, often incurring additional energy or communication costs, it is shown that structured modifications, such as modulation rotation or induced ISI inherent to realistic communication channels can itself provide DP guarantees. While the analysis focuses on deterministic transmitter modifications unknown to the receiver, it is noted that real-world devices naturally introduce unintentional rotations or ISI due to hardware nonidealities and implementation errors. These effects can therefore provide a level of privacy without requiring explicit noise injection. Hence, it is possible to avoid deliberately perturbing the data, instead leveraging inherent device imperfections to achieve privacy guarantees with no additional privacy cost.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.12331v1">Efficient Privacy-Preserving Retrieval Augmented Generation with Distance-Preserving Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-01-18T09:29:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Huanyi Ye, Jiale Guo, Ziyao Liu, Kwok-Yan Lam</p>
    <p><b>Summary:</b> RAG has emerged as a key technique for enhancing response quality of LLMs without high computational cost. In traditional architectures, RAG services are provided by a single entity that hosts the dataset within a trusted local environment. However, individuals or small organizations often lack the resources to maintain data storage servers, leading them to rely on outsourced cloud storage. This dependence on untrusted third-party services introduces privacy risks. Embedding-based retrieval mechanisms, commonly used in RAG systems, are vulnerable to privacy leakage such as vector-to-text reconstruction attacks and structural leakage via vector analysis. Several privacy-preserving RAG techniques have been proposed but most existing approaches rely on partially homomorphic encryption, which incurs substantial computational overhead. To address these challenges, we propose an efficient privacy-preserving RAG framework (ppRAG) tailored for untrusted cloud environments that defends against vector-to-text attack, vector analysis, and query analysis. We propose Conditional Approximate Distance-Comparison-Preserving Symmetric Encryption (CAPRISE) that encrypts embeddings while still allowing the cloud to compute similarity between an encrypted query and the encrypted database embeddings. CAPRISE preserves only the relative distance ordering between the encrypted query and each encrypted database embedding, without exposing inter-database distances, thereby enhancing both privacy and efficiency. To mitigate query analysis, we introduce DP by perturbing the query embedding prior to encryption, preventing the cloud from inferring sensitive patterns. Experimental results show that ppRAG achieves efficient processing throughput, high retrieval accuracy, strong privacy guarantees, making it a practical solution for resource-constrained users seeking secure cloud-augmented LLMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.12311v1">Cross-reality Location Privacy Protection in 6G-enabled Vehicular Metaverses: An LLM-enhanced Hybrid Generative Diffusion Model-based Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-18T08:40:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaofeng Luo, Jiayi He, Jiawen Kang, Ruichen Zhang, Zhaoshui He, Ekram Hossain, Dong In Kim</p>
    <p><b>Summary:</b> The emergence of 6G-enabled vehicular metaverses enables Autonomous Vehicles (AVs) to operate across physical and virtual spaces through space-air-ground-sea integrated networks. The AVs can deploy AI agents powered by large AI models as personalized assistants, on edge servers to support intelligent driving decision making and enhanced on-board experiences. However, such cross-reality interactions may cause serious location privacy risks, as adversaries can infer AV trajectories by correlating the location reported when AVs request LBS in reality with the location of the edge servers on which their corresponding AI agents are deployed in virtuality. To address this challenge, we design a cross-reality location privacy protection framework based on hybrid actions, including continuous location perturbation in reality and discrete privacy-aware AI agent migration in virtuality. In this framework, a new privacy metric, termed cross-reality location entropy, is proposed to effectively quantify the privacy levels of AVs. Based on this metric, we formulate an optimization problem to optimize the hybrid action, focusing on achieving a balance between location protection, service latency reduction, and quality of service maintenance. To solve the complex mixed-integer problem, we develop a novel LLM-enhanced Hybrid Diffusion Proximal Policy Optimization (LHDPPO) algorithm, which integrates LLM-driven informative reward design to enhance environment understanding with double Generative Diffusion Models-based policy exploration to handle high-dimensional action spaces, thereby enabling reliable determination of optimal hybrid actions. Extensive experiments on real-world datasets demonstrate that the proposed framework effectively mitigates cross-reality location privacy leakage for AVs while maintaining strong user immersion within 6G-enabled vehicular metaverse scenarios.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.12284v1">How Safe Is Your Data in Connected and Autonomous Cars: A Consumer Advantage or a Privacy Nightmare ?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-18T06:45:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Amit Chougule, Vinay Chamola, Norbert Herencsar, Fei Richard Yu</p>
    <p><b>Summary:</b> The rapid evolution of the automobile sector, driven by advancements in connected and autonomous vehicles (CAVs), has transformed how vehicles communicate, operate, and interact with their surroundings. Technologies such as Vehicle-to-Everything (V2X) communication enable autonomous cars to generate and exchange substantial amounts of data with real-world entities, enhancing safety, improving performance, and delivering personalized user experiences. However, this data-driven ecosystem introduces significant challenges, particularly concerning data privacy, security, and governance. The absence of transparency and comprehensive regulatory frameworks exacerbates issues of unauthorized data access, prolonged retention, and potential misuse, creating tension between consumer benefits and privacy risks. This review paper explores the multifaceted nature of data sharing in CAVs, analyzing its contributions to innovation and its associated vulnerabilities. It evaluates data-sharing mechanisms and communication technologies, highlights the benefits of data exchange across various use cases, examines privacy concerns and risks of data misuse, and critically reviews regulatory frameworks and their inadequacies in safeguarding user privacy. By providing a thorough analysis of the current state of data sharing in the automotive sector, the paper emphasizes the urgent need for robust policies and ethical data management practices. It calls for striking a balance between fostering technological advancements and ensuring secure, consumer-friendly solutions, paving the way for a trustworthy and innovative automotive future.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.12124v1">SynQP: A Framework and Metrics for Evaluating the Quality and Privacy Risk of Synthetic Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-01-17T17:51:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bing Hu, Yixin Li, Asma Bahamyirou, Helen Chen</p>
    <p><b>Summary:</b> The use of synthetic data in health applications raises privacy concerns, yet the lack of open frameworks for privacy evaluations has slowed its adoption. A major challenge is the absence of accessible benchmark datasets for evaluating privacy risks, due to difficulties in acquiring sensitive data. To address this, we introduce SynQP, an open framework for benchmarking privacy in synthetic data generation (SDG) using simulated sensitive data, ensuring that original data remains confidential. We also highlight the need for privacy metrics that fairly account for the probabilistic nature of machine learning models. As a demonstration, we use SynQP to benchmark CTGAN and propose a new identity disclosure risk metric that offers a more accurate estimation of privacy risks compared to existing approaches. Our work provides a critical tool for improving the transparency and reliability of privacy evaluations, enabling safer use of synthetic data in health-related applications. % In our quality evaluations, non-private models achieved near-perfect machine-learning efficacy \(\ge0.97\). Our privacy assessments (Table II) reveal that DP consistently lowers both identity disclosure risk (SD-IDR) and membership-inference attack risk (SD-MIA), with all DP-augmented models staying below the 0.09 regulatory threshold. Code available at https://github.com/CAN-SYNH/SynQP</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.12105v1">Privacy-Preserving Cohort Analytics for Personalized Health Platforms: A Differentially Private Framework with Stochastic Risk Modeling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">  
  <p><b>Published on:</b> 2026-01-17T16:59:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Richik Chakraborty, Lawrence Liu, Syed Hasnain</p>
    <p><b>Summary:</b> Personalized health analytics increasingly rely on population benchmarks to provide contextual insights such as ''How do I compare to others like me?'' However, cohort-based aggregation of health data introduces nontrivial privacy risks, particularly in interactive and longitudinal digital platforms. Existing privacy frameworks such as $k$-anonymity and differential privacy provide essential but largely static guarantees that do not fully capture the cumulative, distributional, and tail-dominated nature of re-identification risk in deployed systems.
  In this work, we present a privacy-preserving cohort analytics framework that combines deterministic cohort constraints, differential privacy mechanisms, and synthetic baseline generation to enable personalized population comparisons while maintaining strong privacy protections. We further introduce a stochastic risk modeling approach that treats re-identification risk as a random variable evolving over time, enabling distributional evaluation through Monte Carlo simulation. Adapting quantitative risk measures from financial mathematics, we define Privacy Loss at Risk (P-VaR) to characterize worst-case privacy outcomes under realistic cohort dynamics and adversary assumptions.
  We validate our framework through system-level analysis and simulation experiments, demonstrating how privacy-utility tradeoffs can be operationalized for digital health platforms. Our results suggest that stochastic risk modeling complements formal privacy guarantees by providing interpretable, decision-relevant metrics for platform designers, regulators, and clinical informatics stakeholders.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.11977v1">One-Shot Price Forecasting with Covariate-Guided Experts under Privacy Constraints</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-01-17T09:13:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ren He, Yinliang Xu, Jinfeng Wang, Jeremy Watson, Jian Song</p>
    <p><b>Summary:</b> Forecasting in power systems often involves multivariate time series with complex dependencies and strict privacy constraints across regions. Traditional forecasting methods require significant expert knowledge and struggle to generalize across diverse deployment scenarios. Recent advancements in pre-trained time series models offer new opportunities, but their zero-shot performance on domain-specific tasks remains limited. To address these challenges, we propose a novel MoE Encoder module that augments pretrained forecasting models by injecting a sparse mixture-of-experts layer between tokenization and encoding. This design enables two key capabilities: (1) trans forming multivariate forecasting into an expert-guided univariate task, allowing the model to effectively capture inter-variable relations, and (2) supporting localized training and lightweight parameter sharing in federated settings where raw data cannot be exchanged. Extensive experiments on public multivariate datasets demonstrate that MoE-Encoder significantly improves forecasting accuracy compared to strong baselines. We further simulate federated environments and show that transferring only MoE-Encoder parameters allows efficient adaptation to new regions, with minimal performance degradation. Our findings suggest that MoE-Encoder provides a scalable and privacy-aware extension to foundation time series models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.11398v1">Understanding Help Seeking for Digital Privacy, Safety, and Security</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-16T16:10:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kurt Thomas, Sai Teja Peddinti, Sarah Meiklejohn, Tara Matthews, Amelia Hassoun, Animesh Srivastava, Jessica McClearn, Patrick Gage Kelley, Sunny Consolvo, Nina Taft</p>
    <p><b>Summary:</b> The complexity of navigating digital privacy, safety, and security threats often falls directly on users. This leads to users seeking help from family and peers, platforms and advice guides, dedicated communities, and even large language models (LLMs). As a precursor to improving resources across this ecosystem, our community needs to understand what help seeking looks like in the wild. To that end, we blend qualitative coding with LLM fine-tuning to sift through over one billion Reddit posts from the last four years to identify where and for what users seek digital privacy, safety, or security help. We isolate three million relevant posts with 93% precision and recall and automatically annotate each with the topics discussed (e.g., security tools, privacy configurations, scams, account compromise, content moderation, and more). We use this dataset to understand the scope and scale of help seeking, the communities that provide help, and the types of help sought. Our work informs the development of better resources for users (e.g., user guides or LLM help-giving agents) while underscoring the inherent challenges of supporting users through complex combinations of threats, platforms, mitigations, context, and emotions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.11219v2">SDFLoRA: Selective Decoupled Federated LoRA for Privacy-preserving Fine-tuning with Heterogeneous Clients</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-01-16T11:53:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhikang Shen, Jianrong Lu, Haiyuan Wan, Jianhai Chen</p>
    <p><b>Summary:</b> Federated learning (FL) for large language models (LLMs) has attracted increasing attention as a privacy-preserving approach for adapting models over distributed data, where parameter-efficient methods such as Low-Rank Adaptation (LoRA) are widely adopted to reduce communication and memory costs. However, practical deployments often exhibit rank and data heterogeneity: clients operate under different low-rank budgets and data distributions, making direct aggregation of LoRA updates biased and unstable. Existing approaches either enforce a unified rank or align heterogeneous updates into a single shared subspace, which tends to mix transferable and client-specific directions and consequently undermines personalization. Moreover, under differential privacy (DP), perturbing such structurally mixed updates injects noise into directions that should remain purely local, leading to unnecessary utility degradation. To address these issues, we propose Selective Decoupled Federated LoRA (SDFLoRA), a structure-aware LoRA framework that decouples each client update into a shared component for aggregation and a private component that preserves client-specific semantics. Only the shared component participates in subspace alignment, while the private component remains local and uncommunicated, making the training DP-compatible and stabilizing aggregation under rank heterogeneity. By injecting noise only into the aggregated shareable update, this approach avoids perturbations to local directions and improves the utility-privacy trade-off. Experiments on multiple benchmarks demonstrate that SDFLoRA outperforms federated LoRA baselines and achieves a strong utility-privacy trade-off.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.11134v1">FSL-BDP: Federated Survival Learning with Bayesian Differential Privacy for Credit Risk Modeling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">  
  <p><b>Published on:</b> 2026-01-16T09:48:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sultan Amed, Tanmay Sen, Sayantan Banerjee</p>
    <p><b>Summary:</b> Credit risk models are a critical decision-support tool for financial institutions, yet tightening data-protection rules (e.g., GDPR, CCPA) increasingly prohibit cross-border sharing of borrower data, even as these models benefit from cross-institution learning. Traditional default prediction suffers from two limitations: binary classification ignores default timing, treating early defaulters (high loss) equivalently to late defaulters (low loss), and centralized training violates emerging regulatory constraints. We propose a Federated Survival Learning framework with Bayesian Differential Privacy (FSL-BDP) that models time-to-default trajectories without centralizing sensitive data. The framework provides Bayesian (data-dependent) differential privacy (DP) guarantees while enabling institutions to jointly learn risk dynamics. Experiments on three real-world credit datasets (LendingClub, SBA, Bondora) show that federation fundamentally alters the relative effectiveness of privacy mechanisms. While classical DP performs better than Bayesian DP in centralized settings, the latter benefits substantially more from federation (+7.0\% vs +1.4\%), achieving near parity of non-private performance and outperforming classical DP in the majority of participating clients. This ranking reversal yields a key decision-support insight: privacy mechanism selection should be evaluated in the target deployment architecture, rather than centralized benchmarks. These findings provide actionable guidance for practitioners designing privacy-preserving decision support systems in regulated, multi-institutional environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.10866v1">Adaptive Privacy Budgeting</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-15T21:32:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuting Liang, Ke Yi</p>
    <p><b>Summary:</b> We study the problem of adaptive privacy budgeting under generalized differential privacy. Consider the setting where each user $i\in [n]$ holds a tuple $x_i\in U:=U_1\times \dotsb \times U_T$, where $x_i(l)\in U_l$ represents the $l$-th component of their data. For every $l\in [T]$ (or a subset), an untrusted analyst wishes to compute some $f_l(x_1(l),\dots,x_n(l))$, while respecting the privacy of each user. For many functions $f_l$, data from the users are not all equally important, and there is potential to use the privacy budgets of the users strategically, leading to privacy savings that can be used to improve the utility of later queries. In particular, the budgeting should be adaptive to the outputs of previous queries, so that greater savings can be achieved on more typical instances. In this paper, we provide such an adaptive budgeting framework, with various applications demonstrating its applicability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.10701v1">Communication-Efficient and Privacy-Adaptable Mechanism -- a Federated Learning Scheme with Convergence Analysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-15T18:55:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chun Hei Michael Shiu, Chih Wei Ling</p>
    <p><b>Summary:</b> Federated learning enables multiple parties to jointly train learning models without sharing their own underlying data, offering a practical pathway to privacy-preserving collaboration under data-governance constraints. Continued study of federated learning is essential to address key challenges in it, including communication efficiency and privacy protection between parties. A recent line of work introduced a novel approach called the Communication-Efficient and Privacy-Adaptable Mechanism (CEPAM), which achieves both objectives simultaneously. CEPAM leverages the rejection-sampled universal quantizer (RSUQ), a randomized vector quantizer whose quantization error is equivalent to a prescribed noise, which can be tuned to customize privacy protection between parties. In this work, we theoretically analyze the privacy guarantees and convergence properties of CEPAM. Moreover, we assess CEPAM's utility performance through experimental evaluations, including convergence profiles compared with other baselines, and accuracy-privacy trade-offs between different parties.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.10413v1">LADFA: A Framework of Using Large Language Models and Retrieval-Augmented Generation for Personal Data Flow Analysis in Privacy Policies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-15T14:03:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haiyue Yuan, Nikolay Matyunin, Ali Raza, Shujun Li</p>
    <p><b>Summary:</b> Privacy policies help inform people about organisations' personal data processing practices, covering different aspects such as data collection, data storage, and sharing of personal data with third parties. Privacy policies are often difficult for people to fully comprehend due to the lengthy and complex legal language used and inconsistent practices across different sectors and organisations. To help conduct automated and large-scale analyses of privacy policies, many researchers have studied applications of machine learning and natural language processing techniques, including large language models (LLMs). While a limited number of prior studies utilised LLMs for extracting personal data flows from privacy policies, our approach builds on this line of work by combining LLMs with retrieval-augmented generation (RAG) and a customised knowledge base derived from existing studies. This paper presents the development of LADFA, an end-to-end computational framework, which can process unstructured text in a given privacy policy, extract personal data flows and construct a personal data flow graph, and conduct analysis of the data flow graph to facilitate insight discovery. The framework consists of a pre-processor, an LLM-based processor, and a data flow post-processor. We demonstrated and validated the effectiveness and accuracy of the proposed approach by conducting a case study that involved examining ten selected privacy policies from the automotive industry. Moreover, it is worth noting that LADFA is designed to be flexible and customisable, making it suitable for a range of text-based analysis tasks beyond privacy policy analysis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.10237v1">Fundamental Limitations of Favorable Privacy-Utility Guarantees for DP-SGD</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-15T09:50:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Murat Bilgehan Ertan, Marten van Dijk</p>
    <p><b>Summary:</b> Differentially Private Stochastic Gradient Descent (DP-SGD) is the dominant paradigm for private training, but its fundamental limitations under worst-case adversarial privacy definitions remain poorly understood. We analyze DP-SGD in the $f$-differential privacy framework, which characterizes privacy via hypothesis-testing trade-off curves, and study shuffled sampling over a single epoch with $M$ gradient updates. We derive an explicit suboptimal upper bound on the achievable trade-off curve. This result induces a geometric lower bound on the separation $κ$ which is the maximum distance between the mechanism's trade-off curve and the ideal random-guessing line. Because a large separation implies significant adversarial advantage, meaningful privacy requires small $κ$. However, we prove that enforcing a small separation imposes a strict lower bound on the Gaussian noise multiplier $σ$, which directly limits the achievable utility. In particular, under the standard worst-case adversarial model, shuffled DP-SGD must satisfy
  $σ\ge \frac{1}{\sqrt{2\ln M}}$ $\quad\text{or}\quad$ $κ\ge\ \frac{1}{\sqrt{8}}\!\left(1-\frac{1}{\sqrt{4π\ln M}}\right)$,
  and thus cannot simultaneously achieve strong privacy and high utility. Although this bound vanishes asymptotically as $M \to \infty$, the convergence is extremely slow: even for practically relevant numbers of updates the required noise magnitude remains substantial. We further show that the same limitation extends to Poisson subsampling up to constant factors. Our experiments confirm that the noise levels implied by this bound leads to significant accuracy degradation at realistic training settings, thus showing a critical bottleneck in DP-SGD under standard worst-case adversarial assumptions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.10045v1">Privacy Enhanced PEFT: Tensor Train Decomposition Improves Privacy Utility Tradeoffs under DP-SGD</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-15T03:41:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pradip Kunwar, Minh Vu, Maanak Gupta, Manish Bhattarai</p>
    <p><b>Summary:</b> Fine-tuning large language models on sensitive data poses significant privacy risks, as membership inference attacks can reveal whether individual records were used during training. While Differential Privacy (DP) provides formal protection, applying DP to conventional Parameter-Efficient Fine-Tuning (PEFT) methods such as Low-Rank Adaptation (LoRA) often incurs substantial utility loss. In this work, we show that a more structurally constrained PEFT architecture, Tensor Train Low-Rank Adaptation (TTLoRA), can improve the privacy-utility tradeoff by shrinking the effective parameter space while preserving expressivity. To this end, we develop TTLoRA-DP, a differentially private training framework for TTLoRA. Specifically, we extend the ghost clipping algorithm to Tensor Train cores via cached contraction states, enabling efficient Differentially Private Stochastic Gradient Descent (DP-SGD) with exact per-example gradient norm computation without materializing full per-example gradients. Experiments on GPT-2 fine-tuning over the Enron and Penn Treebank datasets show that TTLoRA-DP consistently strengthens privacy protection relative to LoRA-DP while maintaining comparable or better downstream utility. Moreover, TTLoRA exhibits lower membership leakage even without DP training, using substantially smaller adapters and requiring on average 7.6X fewer parameters than LoRA. Overall, our results demonstrate that TTLoRA offers a practical path to improving the privacy-utility tradeoff in parameter-efficient language model adaptation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.10004v1">SoK: Privacy-aware LLM in Healthcare: Threat Model, Privacy Techniques, Challenges and Recommendations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-15T02:28:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohoshin Ara Tahera, Karamveer Singh Sidhu, Shuvalaxmi Dass, Sajal Saha</p>
    <p><b>Summary:</b> Large Language Models (LLMs) are increasingly adopted in healthcare to support clinical decision-making, summarize electronic health records (EHRs), and enhance patient care. However, this integration introduces significant privacy and security challenges, driven by the sensitivity of clinical data and the high-stakes nature of medical workflows. These risks become even more pronounced across heterogeneous deployment environments, ranging from small on-premise hospital systems to regional health networks, each with unique resource limitations and regulatory demands. This Systematization of Knowledge (SoK) examines the evolving threat landscape across the three core LLM phases: Data preprocessing, Fine-tuning, and Inference within realistic healthcare settings. We present a detailed threat model that characterizes adversaries, capabilities, and attack surfaces at each phase, and we systematize how existing privacy-preserving techniques (PPTs) attempt to mitigate these vulnerabilities. While existing defenses show promise, our analysis identifies persistent limitations in securing sensitive clinical data across diverse operational tiers. We conclude with phase-aware recommendations and future research directions aimed at strengthening privacy guarantees for LLMs in regulated environments. This work provides a foundation for understanding the intersection of LLMs, threats, and privacy in healthcare, offering a roadmap toward more robust and clinically trustworthy AI systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.09946v1">Interpolation-Based Optimization for Enforcing lp-Norm Metric Differential Privacy in Continuous and Fine-Grained Domains</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-15T00:12:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chenxi Qiu</p>
    <p><b>Summary:</b> Metric Differential Privacy (mDP) generalizes Local Differential Privacy (LDP) by adapting privacy guarantees based on pairwise distances, enabling context-aware protection and improved utility. While existing optimization-based methods reduce utility loss effectively in coarse-grained domains, optimizing mDP in fine-grained or continuous settings remains challenging due to the computational cost of constructing dense perterubation matrices and satisfying pointwise constraints.
  In this paper, we propose an interpolation-based framework for optimizing lp-norm mDP in such domains. Our approach optimizes perturbation distributions at a sparse set of anchor points and interpolates distributions at non-anchor locations via log-convex combinations, which provably preserve mDP. To address privacy violations caused by naive interpolation in high-dimensional spaces, we decompose the interpolation process into a sequence of one-dimensional steps and derive a corrected formulation that enforces lp-norm mDP by design. We further explore joint optimization over perturbation distributions and privacy budget allocation across dimensions. Experiments on real-world location datasets demonstrate that our method offers rigorous privacy guarantees and competitive utility in fine-grained domains, outperforming baseline mechanisms. in high-dimensional spaces, we decompose the interpolation process into a sequence of one-dimensional steps and derive a corrected formulation that enforces lp-norm mDP by design. We further explore joint optimization over perturbation distributions and privacy budget allocation across dimensions. Experiments on real-world location datasets demonstrate that our method offers rigorous privacy guarantees and competitive utility in fine-grained domains, outperforming baseline mechanisms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.09498v1">Dobrushin Coefficients of Private Mechanisms Beyond Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-14T14:03:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Leonhard Grosse, Sara Saeidian, Tobias J. Oechtering, Mikael Skoglund</p>
    <p><b>Summary:</b> We investigate Dobrushin coefficients of discrete Markov kernels that have bounded pointwise maximal leakage (PML) with respect to all distributions with a minimum probability mass bounded away from zero by a constant $c>0$. This definition recovers local differential privacy (LDP) for $c\to 0$. We derive achievable bounds on contraction in terms of a kernels PML guarantees, and provide mechanism constructions that achieve the presented bounds. Further, we extend the results to general $f$-divergences by an application of Binette's inequality. Our analysis yields tighter bounds for mechanisms satisfying LDP and extends beyond the LDP regime to any discrete kernel.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.09460v1">SoK: Enhancing Cryptographic Collaborative Learning with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-14T13:09:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Francesco Capano, Jonas Böhler, Benjamin Weggenmann</p>
    <p><b>Summary:</b> In collaborative learning (CL), multiple parties jointly train a machine learning model on their private datasets. However, data can not be shared directly due to privacy concerns. To ensure input confidentiality, cryptographic techniques, e.g., multi-party computation (MPC), enable training on encrypted data. Yet, even securely trained models are vulnerable to inference attacks aiming to extract memorized data from model outputs. To ensure output privacy and mitigate inference attacks, differential privacy (DP) injects calibrated noise during training. While cryptography and DP offer complementary guarantees, combining them efficiently for cryptographic and differentially private CL (CPCL) is challenging. Cryptography incurs performance overheads, while DP degrades accuracy, creating a privacy-accuracy-performance trade-off that needs careful design considerations. This work systematizes the CPCL landscape. We introduce a unified framework that generalizes common phases across CPCL paradigms, and identify secure noise sampling as the foundational phase to achieve CPCL. We analyze trade-offs of different secure noise sampling techniques, noise types, and DP mechanisms discussing their implementation challenges and evaluating their accuracy and cryptographic overhead across CPCL paradigms. Additionally, we implement identified secure noise sampling options in MPC and evaluate their computation and communication costs in WAN and LAN. Finally, we propose future research directions based on identified key observations, gaps and possible enhancements in the literature.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.09232v1">Private Links, Public Leaks: Consequences of Frictionless User Experience on the Security and Privacy Posture of SMS-Delivered URLs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-14T07:12:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Muhammad Danish, Enrique Sobrados, Priya Kaushik, Bhupendra Acharya, Muhammad Saad, Abdullah Mueen, Sazzadur Rahaman, Afsah Anwar</p>
    <p><b>Summary:</b> Digital service providers often prioritize a frictionless user experience by adopting technologies that simplify access to their services. One widely used mechanism is the Short Message Service (SMS) to deliver links (URLs) that enable single-click access to online services with little to no resistance. However, SMS is inherently insecure, and numerous reports have documented message interception and data leaks. Thus, attributing excessive trust in such an insecure channel opens avenues for unintended access and exploitation by adversaries.
  In this paper, we present a comprehensive investigation of the implications of SMS-delivered URLs from the lens of public SMS gateways. We conduct the study on more than 322K unique SMS-delivered URLs extracted from more than 33 million messages across more than 30K phone numbers, revealing critical security and privacy vulnerabilities. We identify and validate critical Personally Identifiable Information (PII) exposure in 701 endpoints affecting 177 services. Our manual investigation of the root cause of the exposure reveals a weak authentication model which hinges upon tokenized bearer links as sufficient authorization proofs, thereby allowing anyone with the URL to access private user information, including social security number, date of birth, bank account number, and credit score. Additionally, we identify 125 services allowing mass enumeration of valid URLs due to low entropy within tokens, thereby cascading the privacy risks beyond the initially compromised users. Furthermore, we identify mismatches between the GUI and data fetched by the client, extending the scale of privacy leakages. Particularly, we identify 76 services that perform data overfetching. Finally, 18 services have acknowledged and addressed the weaknesses in their services, thereby enhancing the privacy of at least 120M users.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.09152v1">PrivacyReasoner: Can LLM Emulate a Human-like Privacy Mind?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-01-14T04:47:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yiwen Tu, Xuan Liu, Lianhui Qin, Haojian Jin</p>
    <p><b>Summary:</b> This paper introduces PRA, an AI-agent design for simulating how individual users form privacy concerns in response to real-world news. Moving beyond population-level sentiment analysis, PRA integrates privacy and cognitive theories to simulate user-specific privacy reasoning grounded in personal comment histories and contextual cues. The agent reconstructs each user's "privacy mind", dynamically activates relevant privacy memory through a contextual filter that emulates bounded rationality, and generates synthetic comments reflecting how that user would likely respond to new privacy scenarios. A complementary LLM-as-a-Judge evaluator, calibrated against an established privacy concern taxonomy, quantifies the faithfulness of generated reasoning. Experiments on real-world Hacker News discussions show that \PRA outperforms baseline agents in privacy concern prediction and captures transferable reasoning patterns across domains including AI, e-commerce, and healthcare.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.08953v1">Fairness risk and its privacy-enabled solution in AI-driven robotic applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-01-13T19:43:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Le Liu, Bangguo Yu, Nynke Vellinga, Ming Cao</p>
    <p><b>Summary:</b> Complex decision-making by autonomous machines and algorithms could underpin the foundations of future society. Generative AI is emerging as a powerful engine for such transitions. However, we show that Generative AI-driven developments pose a critical pitfall: fairness concerns. In robotic applications, although intuitions about fairness are common, a precise and implementable definition that captures user utility and inherent data randomness is missing. Here we provide a utility-aware fairness metric for robotic decision making and analyze fairness jointly with user-data privacy, deriving conditions under which privacy budgets govern fairness metrics. This yields a unified framework that formalizes and quantifies fairness and its interplay with privacy, which is tested in a robot navigation task. In view of the fact that under legal requirements, most robotic systems will enforce user privacy, the approach shows surprisingly that such privacy budgets can be jointly used to meet fairness targets. Addressing fairness concerns in the creative combined consideration of privacy is a step towards ethical use of AI and strengthens trust in autonomous robots deployed in everyday environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.08739v1">PrivGemo: Privacy-Preserving Dual-Tower Graph Retrieval for Empowering LLM Reasoning with Memory Augmentation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-01-13T17:14:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xingyu Tan, Xiaoyang Wang, Qing Liu, Xiwei Xu, Xin Yuan, Liming Zhu, Wenjie Zhang</p>
    <p><b>Summary:</b> Knowledge graphs (KGs) provide structured evidence that can ground large language model (LLM) reasoning for knowledge-intensive question answering. However, many practical KGs are private, and sending retrieved triples or exploration traces to closed-source LLM APIs introduces leakage risk. Existing privacy treatments focus on masking entity names, but they still face four limitations: structural leakage under semantic masking, uncontrollable remote interaction, fragile multi-hop and multi-entity reasoning, and limited experience reuse for stability and efficiency. To address these issues, we propose PrivGemo, a privacy-preserving retrieval-augmented framework for KG-grounded reasoning with memory-guided exposure control. PrivGemo uses a dual-tower design to keep raw KG knowledge local while enabling remote reasoning over an anonymized view that goes beyond name masking to limit both semantic and structural exposure. PrivGemo supports multi-hop, multi-entity reasoning by retrieving anonymized long-hop paths that connect all topic entities, while keeping grounding and verification on the local KG. A hierarchical controller and a privacy-aware experience memory further reduce unnecessary exploration and remote interactions. Comprehensive experiments on six benchmarks show that PrivGemo achieves overall state-of-the-art results, outperforming the strongest baseline by up to 17.1%. Furthermore, PrivGemo enables smaller models (e.g., Qwen3-4B) to achieve reasoning performance comparable to that of GPT-4-Turbo.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.10754v1">Chatting with Confidants or Corporations? Privacy Management with AI Companions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-01-13T15:15:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hsuen-Chi Chiu, Jeremy Foote</p>
    <p><b>Summary:</b> AI chatbots designed as emotional companions blur the boundaries between interpersonal intimacy and institutional software, creating a complex, multi-dimensional privacy environment. Drawing on Communication Privacy Management theory and Masur's horizontal (user-AI) and vertical (user-platform) privacy framework, we conducted in-depth interviews with fifteen users of companion AI platforms such as Replika and Character.AI. Our findings reveal that users blend interpersonal habits with institutional awareness: while the non-judgmental, always-available nature of chatbots fosters emotional safety and encourages self-disclosure, users remain mindful of institutional risks and actively manage privacy through layered strategies and selective sharing. Despite this, many feel uncertain or powerless regarding platform-level data control. Anthropomorphic design further blurs privacy boundaries, sometimes leading to unintentional oversharing and privacy turbulence. These results extend privacy theory by highlighting the unique interplay of emotional and institutional privacy management in human-AI companionship.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.08339v1">Blockchain-Enabled Renewable Energy Certificate Trading: A Secure and Privacy-Preserving Approach</a></h3>
  
  <p><b>Published on:</b> 2026-01-13T08:57:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wei-Jen Liu, Wei-Yu Chiu, Weiqi Hua</p>
    <p><b>Summary:</b> In the 21st century, transitioning to renewable energy sources is imperative, with fossil fuel reserves depleting rapidly and recognizing critical environmental issues such as climate change, air pollution, water pollution, and habitat destruction. Embracing renewable energy is not only an environmental necessity but also a strategic move with multiple benefits. By shifting to renewable energy sources and supporting their production through the acquisition of renewable energy certificates, we foster innovation and drive economic growth in the renewable energy sector. This, in turn, reduces greenhouse gas emissions, aligning with global efforts to mitigate climate change. Additionally, renewable energy certificates ensure compliance with regulations that mandate the use of renewable energy, enhancing legal adherence while promoting transparency and trust in energy sourcing. To monitor the uptake of renewable energy, governments have implemented Renewable Energy Certificates (RECs) as a tracking mechanism for the production and consumption of renewable energy. However, there are two main challenges to the existing REC schema: 1) The RECs have not been globally adopted due to inconsistent design; 2) The consumer privacy has not been well incorporated in the design of blockchain. In this study, we investigate the trading of RECs between suppliers and consumers using the directed acyclic graph (DAG) blockchain system and introduce a trading schema to help protect consumer information. Our results demonstrate lower transaction time by 41\% and energy consumption by 65\% compared to proof-of-stake.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.07997v1">Can Inherent Communication Noise Guarantee Privacy in Distributed Cooperative Control ?</a></h3>
  
  <p><b>Published on:</b> 2026-01-12T21:04:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuwen Ma, Sarah K. Spurgeon, Tao Li, Boli Chen</p>
    <p><b>Summary:</b> This paper investigates privacy-preserving distributed cooperative control for multi-agent systems within the framework of differential privacy. In cooperative control, communication noise is inevitable and is usually regarded as a disturbance that impairs coordination. This work revisits such noise as a potential privacy-enhancing factor. A linear quadratic regulator (LQR)-based framework is proposed for agents communicating over noisy channels, \textcolor{black}{where the noise variance depends on the relative state differences between neighbouring agents.} The resulting controller achieves formation while protecting the reference signals from inference attacks. It is analytically proven that the inherent communication noise can guarantee bounded $(ε,δ)$-differential privacy without adding dedicated privacy noise, while the \textcolor{black}{system cooperative tracking error} remains bounded and convergent in both the mean-square and almost-sure sense.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.07608v1">Recursive Binary Identification with Differential Privacy and Data Tampering Attacks</a></h3>
  
  <p><b>Published on:</b> 2026-01-12T14:58:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jimin Wang, Jieming Ke, Jin Guo, Yanlong Zhao</p>
    <p><b>Summary:</b> In this paper, we consider the parameter estimation in a bandwidth-constrained sensor network communicating through an insecure medium. The sensor performs a local quantization, and transmits a 1-bit message to an estimation center through a wireless medium where the transmission of information is vulnerable to attackers. Both eavesdroppers and data tampering attackers are considered in our setting. A differential privacy method is used to protect the sensitive information against eavesdroppers. Then, a recursive projection algorithm is proposed such that the estimation center achieves the almost sure convergence and mean-square convergence when quantized measurements, differential privacy, and data tampering attacks are considered in a uniform framework. A privacy analysis including the convergence rate with privacy or without privacy is given. Further, we extend the problem to multi-agent systems. For this case, a distributed recursive projection algorithm is proposed with guaranteed almost sure and mean square convergence. A simulation example is provided to illustrate the effectiveness of the proposed algorithms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.07523v1">Sparse Point-wise Privacy Leakage: Mechanism Design and Fundamental Limits</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-01-12T13:25:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Amirreza Zamani, Sajad Daei, Parastoo Sadeghi, Mikael Skoglund</p>
    <p><b>Summary:</b> We study an information-theoretic privacy mechanism design problem, where an agent observes useful data $Y$ that is arbitrarily correlated with sensitive data $X$, and design disclosed data $U$ generated from $Y$ (the agent has no direct access to $X$). We introduce \emph{sparse point-wise privacy leakage}, a worst-case privacy criterion that enforces two simultaneous constraints for every disclosed symbol $u\in\mathcal{U}$: (i) $u$ may be correlated with at most $N$ realizations of $X$, and (ii) the total leakage toward those realizations is bounded. In the high-privacy regime, we use concepts from information geometry to obtain a local quadratic approximation of mutual information which measures utility between $U$ and $Y$. When the leakage matrix $P_{X|Y}$ is invertible, this approximation reduces the design problem to a sparse quadratic maximization, known as the Rayleigh-quotient problem, with an $\ell_0$ constraint. We further show that, for the approximated problem, one can without loss of optimality restrict attention to a binary released variable $U$ with a uniform distribution. For small alphabet sizes, the exact sparsity-constrained optimum can be computed via combinatorial support enumeration, which quickly becomes intractable as the dimension grows. For general dimensions, the resulting sparse Rayleigh-quotient maximization is NP-hard and closely related to sparse principal component analysis (PCA). We propose a convex semidefinite programming (SDP) relaxation that is solvable in polynomial time and provides a tractable surrogate for the NP-hard design, together with a simple rounding procedure to recover a feasible leakage direction. We also identify a sparsity threshold beyond which the sparse optimum saturates at the unconstrained spectral value and the SDP relaxation becomes tight.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.07134v1">Proof of Reasoning for Privacy Enhanced Federated Blockchain Learning at the Edge</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-12T01:57:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> James Calo, Benny Lo</p>
    <p><b>Summary:</b> Consensus mechanisms are the core of any blockchain system. However, the majority of these mechanisms do not target federated learning directly nor do they aid in the aggregation step. This paper introduces Proof of Reasoning (PoR), a novel consensus mechanism specifically designed for federated learning using blockchain, aimed at preserving data privacy, defending against malicious attacks, and enhancing the validation of participating networks. Unlike generic blockchain consensus mechanisms commonly found in the literature, PoR integrates three distinct processes tailored for federated learning. Firstly, a masked autoencoder (MAE) is trained to generate an encoder that functions as a feature map and obfuscates input data, rendering it resistant to human reconstruction and model inversion attacks. Secondly, a downstream classifier is trained at the edge, receiving input from the trained encoder. The downstream network's weights, a single encoded datapoint, the network's output and the ground truth are then added to a block for federated aggregation. Lastly, this data facilitates the aggregation of all participating networks, enabling more complex and verifiable aggregation methods than previously possible. This three-stage process results in more robust networks with significantly reduced computational complexity, maintaining high accuracy by training only the downstream classifier at the edge. PoR scales to large IoT networks with low latency and storage growth, and adapts to evolving data, regulations, and network conditions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.06742v1">Federated Continual Learning for Privacy-Preserving Hospital Imaging Classification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-11T01:28:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anay Sinhal, Arpana Sinhal, Amit Sinhal</p>
    <p><b>Summary:</b> Deep learning models for radiology interpretation increasingly rely on multi-institutional data, yet privacy regulations and distribution shift across hospitals limit central data pooling. Federated learning (FL) allows hospitals to collaboratively train models without sharing raw images, but current FL algorithms typically assume a static data distribution. In practice, hospitals experience continual evolution in case mix, annotation protocols, and imaging devices, which leads to catastrophic forgetting when models are updated sequentially. Federated continual learning (FCL) aims to reconcile these challenges but existing methods either ignore the stringent privacy constraints of healthcare or rely on replay buffers and public surrogate datasets that are difficult to justify in clinical settings. We study FCL for chest radiography classification in a setting where hospitals are clients that receive temporally evolving streams of cases and labels. We introduce DP-FedEPC (Differentially Private Federated Elastic Prototype Consolidation), a method that combines elastic weight consolidation (EWC), prototype-based rehearsal, and client-side differential privacy within a standard FedAvg framework. EWC constrains updates along parameters deemed important for previous tasks, while a memory of latent prototypes preserves class structure without storing raw images. Differentially private stochastic gradient descent (DP-SGD) at each client adds calibrated Gaussian noise to clipped gradients, providing formal privacy guarantees for individual radiographs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.06710v1">Privacy-Preserving Data Processing in Cloud : From Homomorphic Encryption to Federated Analytics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-01-10T22:33:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gaurav Sarraf, Vibhor Pal</p>
    <p><b>Summary:</b> Privacy-preserving data processing refers to the methods and models that allow computing and analyzing sensitive data with a guarantee of confidentiality. As cloud computing and applications that rely on data continue to expand, there is an increasing need to protect personal, financial and healthcare information. Conventional centralized data processing methods expose sensitive data to risk of breaches, compelling the need to use decentralized and secure data methods. This paper gives a detailed review of privacy-saving mechanisms in the cloud platform, such as statistical approaches like differential privacy and cryptographic solutions like homomorphic encryption. Federated analytics and federated learning, two distributed learning frameworks, are also discussed. Their principles, applications, benefits, and limitations are reviewed, with roles of use in the fields of healthcare, finance, IoT, and industrial cases. Comparative analyses measure trade-offs in security, efficiency, scalability, and accuracy, and investigations are done of emerging hybrid frameworks to provide better privacy protection. Critical issues, including computational overhead, privacy-utility trade-offs, standardization, adversarial threats, and cloud integration are also addressed. This review examines in detail the recent privacy-protecting approaches in cloud computation and offers scholars and practitioners crucial information on secure and effective solutions to data processing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.06699v2">Incentive Mechanism Design for Privacy-Preserving Decentralized Blockchain Relayers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2026-01-10T21:49:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Boutaina Jebari, Khalil Ibrahimi, Hamidou Tembine, Mounir Ghogho</p>
    <p><b>Summary:</b> Public blockchains, though renowned for their transparency and immutability, suffer from significant privacy concerns. Network-level analysis and long-term observation of publicly available transactions can often be used to infer user identities. To mitigate this, several blockchain applications rely on relayers, which serve as intermediary nodes between users and smart contracts deployed on the blockchain. However, dependence on a single relayer not only creates a single point of failure but also introduces exploitable vulnerabilities that weaken the system's privacy guarantees. This paper proposes a decentralized relayer architecture that enhances privacy and reliability through game-theoretic incentive design. We model the interaction among relayers as a non-cooperative game and design an incentive mechanism in which probabilistic uploading emerges as a unique mixed Nash equilibrium. Using evolutionary game analysis, we demonstrate the equilibrium's stability against perturbations and coordinated deviations. Through numerical evaluations, we analyze how equilibrium strategies and system behavior evolve with key parameters such as the number of relayers, upload costs, rewards, and penalties. In particular, we show that even with high transaction costs, the system maintains reliability with an outage probability below 0.05 . Furthermore, our results highlight a fundamental trade-off between privacy, reliability, robustness, and cost in decentralized relayer systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.06641v1">Leveraging Soft Prompts for Privacy Attacks in Federated Prompt Tuning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-10T17:50:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Quan Minh Nguyen, Min-Seon Kim, Hoang M. Ngo, Trong Nghia Hoang, Hyuk-Yoon Kwon, My T. Thai</p>
    <p><b>Summary:</b> Membership inference attack (MIA) poses a significant privacy threat in federated learning (FL) as it allows adversaries to determine whether a client's private dataset contains a specific data sample. While defenses against membership inference attacks in standard FL have been well studied, the recent shift toward federated fine-tuning has introduced new, largely unexplored attack surfaces. To highlight this vulnerability in the emerging FL paradigm, we demonstrate that federated prompt-tuning, which adapts pre-trained models with small input prefixes to improve efficiency, also exposes a new vector for privacy attacks. We propose PromptMIA, a membership inference attack tailored to federated prompt-tuning, in which a malicious server can insert adversarially crafted prompts and monitors their updates during collaborative training to accurately determine whether a target data point is in a client's private dataset. We formalize this threat as a security game and empirically show that PromptMIA consistently attains high advantage in this game across diverse benchmark datasets. Our theoretical analysis further establishes a lower bound on the attack's advantage which explains and supports the consistently high advantage observed in our empirical results. We also investigate the effectiveness of standard membership inference defenses originally developed for gradient or output based attacks and analyze their interaction with the distinct threat landscape posed by PromptMIA. The results highlight non-trivial challenges for current defenses and offer insights into their limitations, underscoring the need for defense strategies that are specifically tailored to prompt-tuning in federated settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.06612v1">Cross-Border Data Security and Privacy Risks in Large Language Models and IoT Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-10T16:21:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chalitha Handapangoda</p>
    <p><b>Summary:</b> The reliance of Large Language Models and Internet of Things systems on massive, globally distributed data flows creates systemic security and privacy challenges. When data traverses borders, it becomes subject to conflicting legal regimes, such as the EU's General Data Protection Regulation and China's Personal Information Protection Law, compounded by technical vulnerabilities like model memorization. Current static encryption and data localization methods are fragmented and reactive, failing to provide adequate, policy-aligned safeguards. This research proposes a Jurisdiction-Aware, Privacy-by-Design architecture that dynamically integrates localized encryption, adaptive differential privacy, and real-time compliance assertion via cryptographic proofs. Empirical validation in a multi-jurisdictional simulation demonstrates this architecture reduced unauthorized data exposure to below five percent and achieved zero compliance violations. These security gains were realized while maintaining model utility retention above ninety percent and limiting computational overhead. This establishes that proactive, integrated controls are feasible for secure and globally compliant AI deployment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.06471v1">PRISP: Privacy-Safe Few-Shot Personalization via Lightweight Adaptation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-10T07:34:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Junho Park, Dohoon Kim, Taesup Moon</p>
    <p><b>Summary:</b> Large language model (LLM) personalization aims to adapt general-purpose models to individual users. Most existing methods, however, are developed under data-rich and resource-abundant settings, often incurring privacy risks. In contrast, realistic personalization typically occurs after deployment under (i) extremely limited user data, (ii) constrained computational resources, and (iii) strict privacy requirements. We propose PRISP, a lightweight and privacy-safe personalization framework tailored to these constraints. PRISP leverages a Text-to-LoRA hypernetwork to generate task-aware LoRA parameters from task descriptions, and enables efficient user personalization by optimizing a small subset of task-aware LoRA parameters together with minimal additional modules using few-shot user data. Experiments on a few-shot variant of the LaMP benchmark demonstrate that PRISP achieves strong overall performance compared to prior approaches, while reducing computational overhead and eliminating privacy risks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.06466v1">SecureDyn-FL: A Robust Privacy-Preserving Federated Learning Framework for Intrusion Detection in IoT Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-01-10T07:23:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Imtiaz Ali Soomro, Hamood Ur Rehman, S. Jawad Hussain ID, Adeel Iqbal, Waqas Khalid, Heejung Yu ID</p>
    <p><b>Summary:</b> The rapid proliferation of Internet of Things (IoT) devices across domains such as smart homes, industrial control systems, and healthcare networks has significantly expanded the attack surface for cyber threats, including botnet-driven distributed denial-of-service (DDoS), malware injection, and data exfiltration. Conventional intrusion detection systems (IDS) face critical challenges like privacy, scalability, and robustness when applied in such heterogeneous IoT environments. To address these issues, we propose SecureDyn-FL, a comprehensive and robust privacy-preserving federated learning (FL) framework tailored for intrusion detection in IoT networks. SecureDyn-FL is designed to simultaneously address multiple security dimensions in FL-based IDS: (1) poisoning detection through dynamic temporal gradient auditing, (2) privacy protection against inference and eavesdropping attacks through secure aggregation, and (3) adaptation to heterogeneous non-IID data via personalized learning. The framework introduces three core contributions: (i) a dynamic temporal gradient auditing mechanism that leverages Gaussian mixture models (GMMs) and Mahalanobis distance (MD) to detect stealthy and adaptive poisoning attacks, (ii) an optimized privacy-preserving aggregation scheme based on transformed additive ElGamal encryption with adaptive pruning and quantization for secure and efficient communication, and (iii) a dual-objective personalized learning strategy that improves model adaptation under non-IID data using logit-adjusted loss. Extensive experiments on the N-BaIoT dataset under both IID and non-IID settings, including scenarios with up to 50% adversarial clients, demonstrate that SecureDyn-FL consistently outperforms state-of-the-art FL-based IDS defenses.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.06385v1">Noise Reduction for Pufferfish Privacy: A Practical Noise Calibration Method</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-10T02:01:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenjin Yang, Ni Ding, Zijian Zhang, Jing Sun, Zhen Li, Yan Wu, Jiahang Sun, Haotian Lin, Yong Liu, Jincheng An, Liehuang Zhu</p>
    <p><b>Summary:</b> This paper introduces a relaxed noise calibration method to enhance data utility while attaining pufferfish privacy. This work builds on the existing $1$-Wasserstein (Kantorovich) mechanism by alleviating the existing overly strict condition that leads to excessive noise, and proposes a practical mechanism design algorithm as a general solution. We prove that a strict noise reduction by our approach always exists compared to $1$-Wasserstein mechanism for all privacy budgets $ε$ and prior beliefs, and the noise reduction (also represents improvement on data utility) gains increase significantly for low privacy budget situations--which are commonly seen in real-world deployments. We also analyze the variation and optimality of the noise reduction with different prior distributions. Moreover, all the properties of the noise reduction still exist in the worst-case $1$-Wasserstein mechanism we introduced, when the additive noise is largest. We further show that the worst-case $1$-Wasserstein mechanism is equivalent to the $\ell_1$-sensitivity method. Experimental results on three real-world datasets demonstrate $47\%$ to $87\%$ improvement in data utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.06357v1">Smart Privacy Policy Assistant: An LLM-Powered System for Transparent and Actionable Privacy Notices</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-01-09T23:42:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sriharshini Kalvakuntla, Luoxi Tang, Yuqiao Meng, Zhaohan Xi</p>
    <p><b>Summary:</b> Most users agree to online privacy policies without reading or understanding them, even though these documents govern how personal data is collected, shared, and monetized. Privacy policies are typically long, legally complex, and difficult for non-experts to interpret. This paper presents the Smart Privacy Policy Assistant, an LLM-powered system that automatically ingests privacy policies, extracts and categorizes key clauses, assigns human-interpretable risk levels, and generates clear, concise explanations. The system is designed for real-time use through browser extensions or mobile interfaces, surfacing contextual warnings before users disclose sensitive information or grant risky permissions. We describe the end-to-end pipeline, including policy ingestion, clause categorization, risk scoring, and explanation generation, and propose an evaluation framework based on clause-level accuracy, policy-level risk agreement, and user comprehension.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.06276v1">Automated Generation of Accurate Privacy Captions From Android Source Code Using Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2026-01-09T19:41:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vijayanta Jain, Sepideh Ghanavati, Sai Teja Peddinti, Collin McMillan</p>
    <p><b>Summary:</b> Privacy captions are short sentences that succinctly describe what personal information is used, how it is used, and why, within an app. These captions can be utilized in various notice formats, such as privacy policies, app rationales, and app store descriptions. However, inaccurate captions may mislead users and expose developers to regulatory fines. Existing approaches to generating privacy notices or just privacy captions include using questionnaires, templates, static analysis, or machine learning. However, these approaches either rely heavily on developers' inputs and thus strain their efforts, use limited source code context, leading to the incomplete capture of app privacy behaviors, or depend on potentially inaccurate privacy policies as a source for creating notices. In this work, we address these limitations by developing Privacy Caption Generator (PCapGen), an approach that - i) automatically identifies and extracts large and precise source code context that implements privacy behaviors in an app, ii) uses a Large Language Model (LLM) to describe coarse- and fine-grained privacy behaviors, and iii) generates accurate, concise, and complete privacy captions to describe the privacy behaviors of the app. Our evaluation shows PCapGen generates concise, complete, and accurate privacy captions as compared to the baseline approach. Furthermore, privacy experts choose PCapGen captions at least 71\% of the time, whereas LLMs-as-judge prefer PCapGen captions at least 76\% of the time, indicating strong performance of our approach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.05789v1">SAFE: Secure and Accurate Federated Learning for Privacy-Preserving Brain-Computer Interfaces</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-09T13:29:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tianwang Jia, Xiaoqing Chen, Dongrui Wu</p>
    <p><b>Summary:</b> Electroencephalogram (EEG)-based brain-computer interfaces (BCIs) are widely adopted due to their efficiency and portability; however, their decoding algorithms still face multiple challenges, including inadequate generalization, adversarial vulnerability, and privacy leakage. This paper proposes Secure and Accurate FEderated learning (SAFE), a federated learning-based approach that protects user privacy by keeping data local during model training. SAFE employs local batch-specific normalization to mitigate cross-subject feature distribution shifts and hence improves model generalization. It further enhances adversarial robustness by introducing perturbations in both the input space and the parameter space through federated adversarial training and adversarial weight perturbation. Experiments on five EEG datasets from motor imagery (MI) and event-related potential (ERP) BCI paradigms demonstrated that SAFE consistently outperformed 14 state-of-the-art approaches in both decoding accuracy and adversarial robustness, while ensuring privacy protection. Notably, it even outperformed centralized training approaches that do not consider privacy protection at all. To our knowledge, SAFE is the first algorithm to simultaneously achieve high decoding accuracy, strong adversarial robustness, and reliable privacy protection without using any calibration data from the target subject, making it highly desirable for real-world BCIs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.05635v2">Continual Pretraining on Encrypted Synthetic Data for Privacy-Preserving LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-01-09T08:44:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Honghao Liu, Xuhui Jiang, Chengjin Xu, Cehao Yang, Yiran Cheng, Lionel Ni, Jian Guo</p>
    <p><b>Summary:</b> Preserving privacy in sensitive data while pretraining large language models on small, domain-specific corpora presents a significant challenge. In this work, we take an exploratory step toward privacy-preserving continual pretraining by proposing an entity-based framework that synthesizes encrypted training data to protect personally identifiable information (PII). Our approach constructs a weighted entity graph to guide data synthesis and applies deterministic encryption to PII entities, enabling LLMs to encode new knowledge through continual pretraining while granting authorized access to sensitive data through decryption keys. Our results on limited-scale datasets demonstrate that our pretrained models outperform base models and ensure PII security, while exhibiting a modest performance gap compared to models trained on unencrypted synthetic data. We further show that increasing the number of entities and leveraging graph-based synthesis improves model performance, and that encrypted models retain instruction-following capabilities with long retrieved contexts. We discuss the security implications and limitations of deterministic encryption, positioning this work as an initial investigation into the design space of encrypted data pretraining for privacy-preserving LLMs. Our code is available at https://github.com/DataArcTech/SoE.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.05180v2">The Adverse Effects of Omitting Records in Differential Privacy: How Sampling and Suppression Degrade the Privacy--Utility Tradeoff (Long Version)</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-08T18:03:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Àlex Miranda-Pascual, Javier Parra-Arnau, Thorsten Strufe</p>
    <p><b>Summary:</b> Sampling is renowned for its privacy amplification in differential privacy (DP), and is often assumed to improve the utility of a DP mechanism by allowing a noise reduction. In this paper, we further show that this last assumption is flawed: When measuring utility at equal privacy levels, sampling as preprocessing consistently yields penalties due to utility loss from omitting records over all canonical DP mechanisms -- Laplace, Gaussian, exponential, and report noisy max -- , as well as recent applications of sampling, such as clustering.
  Extending this analysis, we investigate suppression as a generalized method of choosing, or omitting, records. Developing a theoretical analysis of this technique, we derive privacy bounds for arbitrary suppression strategies under unbounded approximate DP. We find that our tested suppression strategy also fails to improve the privacy--utility tradeoff. Surprisingly, uniform sampling emerges as one of the best suppression methods -- despite its still degrading effect. Our results call into question common preprocessing assumptions in DP practice.</p>
  </details>
</div>

