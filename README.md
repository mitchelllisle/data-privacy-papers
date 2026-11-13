
<h2>2026-10</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.01353v1">Infinite Quantiles Inference under Local Differential Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-31T23:48:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yi Liu, Qirui Hu</p>
    <p><b>Summary:</b> We study simultaneous quantile inference under local differential privacy for a number of target probabilities that grows with the sample size. Each user participates once, so learning unknown quantile locations and calibrating their joint uncertainty must share the same private information. We fuse complementary cumulative distribution function (CDF) scores from a single tree report using their exact covariance; the variance at the correct anchor is no larger than that of either score, and anchor error incurs only quadratic excess variance. Three consecutive cohorts then localize the quantiles, estimate their densities, and supply fresh scores for a one-step correction and joint multiplier calibration. Under mild conditions, a uniform representation controls localization and density errors and yields asymptotically valid simultaneous coverage. A fixed-privacy regime permits every polynomially growing target grid. Simulations show consistent same-report precision gains, while comparisons with CDF-band inversion expose the sample cost of learning target locations. Census microdata illustrates how the resulting joint intervals support wage-percentile ratios.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.01218v1">Optimal Conversion from Zero-Concentrated to Gaussian Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">
  <p><b>Published on:</b> 2026-10-31T19:39:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yu-Wei Chen, Aaradhya Pandey, Jordan Awan</p>
    <p><b>Summary:</b> Gaussian differential privacy (GDP) and zero-concentrated differential privacy (zCDP) are two competing privacy accounting frameworks, but they share similar minimax lower bounds in various estimation problems. Moreover, it is known that a mechanism satisfying $μ$-GDP satisfies $(μ^2/2)$-zCDP, whereas the converse fails to hold at the same calibration. In this paper, we establish the optimal reverse conversion, showing that every $ρ$-zCDP mechanism satisfies $μ_{\mathrm{zCDP}}(ρ)$-GDP, where $μ_{\mathrm{zCDP}}(ρ)=2Φ^{-1}((1+e^{-t_ρ})^{-1})$ and $t_ρ$ uniquely solves the equation $ρ=t_ρ\tanh(t_ρ/2)$. We also obtain simplified bounds $\sqrt{πρ}\leqμ_{\mathrm{zCDP}}(ρ)\leq\sqrt{8ρ}$, with sharp constants, which imply equivalence of the two frameworks up to constants. This explains why their minimax risks agree up to a constant rescaling of the privacy budget. We show that the squared conversion is strictly convex, which implies that converting zCDP to GDP before applying composition or group privacy yields a tighter GDP guarantee than converting afterward. We also derive the sharp conversion from bounded-range and logistic DP mechanisms (e.g., exponential mechanism) to GDP, where converting before composition but after group privacy gives the tighter guarantee.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.01211v1">A Large-Scale Evaluation of Cookie Notice Privacy and Accessibility for Blind and Low Vision Users</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-31T19:12:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> James M. Clarke, Maryam Mehrnezhad</p>
    <p><b>Summary:</b> We present the first large-scale privacy and accessibility evaluation of cookie notices across 2,061 domains for blind and low vision (BLV) users. Using a Playwright-based crawler, a custom NVDA screen reader add-on, and the Lighthouse and WAVE accessibility tools, we measure UK GDPR/PECR compliance, tracker activity across pre-interaction, post-accept, and post-reject phases, and cookie notice accessibility for screen reader users. We find that 51 % of sites display a cookie notice, of which (at least) 50 % violate UK GDPR/PECR requirements. Accepting a notice produces a mean five-fold increase in tracker activity, and degrades page landmark structure on one in five sites. While 95 % of notices are readable by a screen reader, only 37 % carry a meaningful title, 39 % are announced immediately on page load, and 42 % use descriptive button labels. We reveal a systemic correlation: cookie notices failing legal privacy requirements disproportionately exhibit the weakest screen reader accessibility. This compounding privacy burden on BLV users demands urgent intervention from developers, regulators, and standards bodies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.00888v1">Differential Privacy for Generalized Entropy Indices of Income Inequality</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2026-10-31T12:46:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiahe Li, Jerome P. Reiter</p>
    <p><b>Summary:</b> The mean log deviation and the Theil index are two widely used measures of income inequality. The organization releasing these measures may be obligated to protect the confidentiality of the individual incomes used in the computations. In particular, the organization may wish to release versions of these measures with formal guarantees of privacy. The organization could do so by satisfying differential privacy; however, typical applications of differentially private algorithms are likely to add so much noise to the measures that they become unusable. We present differentially private algorithms for these indices with reasonable error properties. The algorithms rely on computing or approximating bounds on the smooth sensitivity, that is, the maximum absolute amount the inequality measures change when replacing any subset of the $n$ incomes in the reported data with arbitrarily chosen feasible values. For the mean log deviation, the algorithm runs in $O(n^2)$ time. For the Theil index, the algorithm runs in $O(n\log n)$ time. We illustrate the performance of each differentially private algorithm using individual-level and household-level income data from the Current Population Survey. We also examine repeated sampling properties of the algorithms using artificially generated data. The empirical results indicate when these differentially private algorithms can be expected to provide accurate estimates and when they are likely to introduce too much noise.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.42139v1">Counting on Dummies: Privacy Amplification with Observable Counts and Truncated Batches</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-30T17:58:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vitaly Feldman, Audra McMillan, Kunal Talwar</p>
    <p><b>Summary:</b> In many practical deployments of Differentially Private Stochastic Gradient Descent (DP-SGD), the server processes data in batches. Randomly sampling these batches allows for better privacy bounds via privacy amplification results. Most sampling schemes with provable privacy amplification, including Poisson sampling and random allocation, result in variable batch sizes. The privacy guarantee of these schemes requires that the batch sizes are not revealed. In distributed settings, the server performing the aggregation or any party observing the communication traffic may learn these batch sizes. Furthermore, in both centralized and distributed settings, memory and computation constraints may require each batch to be of some maximum size $s$, necessitating truncation of the batch when it exceeds this limit. It is known that this truncation can result in a significant increase in privacy loss. In this work, we address both of these challenges via a simple mechanism that uses a random number of \emph{dummy points} to privatize the batch size and maintain the privacy guarantee even under truncation. We demonstrate that our mechanism is easy to implement in a distributed setting, and provide a general analysis of this mechanism for both Poisson sampling and random allocation. Our analysis is designed to support efficient and relatively tight privacy accounting. It also effectively amplifies the privacy of the count releases by subsampling, making the expected number of dummy points asymptotically smaller than what is needed to directly privatize the (sensitivity-one) batch sizes with non-negative noise. For Poisson sampling with truncated batches, we demonstrate empirically that our mechanism achieves better privacy--efficiency tradeoffs than the direct accounting for truncation recently given by (Ganesh, 2025).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.42117v1">Fast Privacy Loss Accounting for Random Allocation via Multiscale FFT</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-30T17:51:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vitaly Feldman, Moshe Shenfeld</p>
    <p><b>Summary:</b> In the random allocation sampling scheme each user's data is used in $k$ steps chosen randomly and uniformly from a sequence of $t$ steps. This scheme is known to improve on Poisson sampling in private optimization and in communication-efficient aggregation. The existing privacy loss distribution (PLD) accountant for this scheme runs in time quadratic in the inverse of the accuracy parameter $α$ (Feldman and Shenfeld, 2026). We give an algorithm, \emph{multiscale FFT}, that represents likelihood ratios on a grid that is uniform within each dyadic interval and computes the exact rounding of every pairwise sum using FFTs within each interval. It keeps the guarantees of the accountant and improves the dependence of its running time on $α$ from $O(α^{-2})$ to $O(α^{-1}\log(1/α))$. In addition, we demonstrate that rounding can be performed via the mean-preserving connect-the-dots projection of (Doroshenko et al., 2026). This reduces the errors that rounding introduces in the mean of the privacy loss and in the $χ^2$ divergence of the computed pair from the order of $α$ to $O(α^2/\log(t))$. In our experiments, our algorithm achieves speedups of several orders of magnitude at high accuracy and gives improved privacy bounds for DP-SGD with PREAMBLE.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.41885v1">How Much Can Tool Calls Reveal About You? Privacy Leakage from Tool-Call Traces</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-10-30T15:30:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Donghang Duan, Qingyu Liu, Yifei Liu, Na Zou, Xia Hu, Dongrui Liu</p>
    <p><b>Summary:</b> Large language model (LLM)-based agents interact with external tools through protocols such as the Model Context Protocol (MCP), producing tool-call traces that may expose behavioral signals about users. In this work, we systematically study the risk of user-profile inference from MCP tool-call traces, where observers infer user attributes from protocol-valid tool interactions without access to user conversations. We introduce PrivacyTrace, a benchmark containing 1,000 synthetic user profiles and 4,000 agent trajectories across four domains, generated with real MCP tools from 25 servers. Experiments with four mainstream LLM attackers show that tool-call traces enable a 26.25% attack success rate for profile inference, compared with 17.97% from prior-based guessing. Further analysis reveals that tool arguments and returned results provide the main trace-grounded evidence, while linking traces across sessions further amplifies profiling risk. These findings demonstrate that MCP tool-call traces can act as effective behavioral side channels for user profiling, motivating the development of privacy-aware mechanisms for agent-tool interactions. Code and data are available at https://github.com/AI45Lab/PrivacyTrace.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.41642v1">TADP: Dual-Branch Temporally Adaptive Differential Privacy for Expression-Aware Video Anonymization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-10-30T12:16:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Feng Xu, Xun Li, Lars Petersson, Yulei Sui, David Ahmedt-Aristizabal, Dadong Wang</p>
    <p><b>Summary:</b> We present TADP, a temporally adaptive differential privacy (DP) framework for inference-time privacy-preserving video generation under fixed-length clip-replacement adjacency. TADP uses a dual-branch design to extract identity and expression representations, clips and privatizes both branches with temporally adaptive Gaussian mechanisms whose noise scales depend only on preceding privatized releases within the same clip and are bounded below by history-uniform calibrated minima, and accounts for their joint release via adaptive Rényi Differential Privacy (RDP) composition. The clip-level RDP guarantee is converted to $(\varepsilon,δ)$-differential privacy, while soft quantization and subsequent temporal processing are applied only after privatization as DP post-processing. Experiments on facial expression datasets show reduced identity leakage under evaluated attacks, usable perceptual quality and temporal stability, and high facial expression recognition utility relative to the evaluated privacy-preserving baselines. TADP formally satisfies clip-level DP and empirically provides a favorable privacy--utility trade-off under the evaluated threat models and datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.41441v1">GESIS Surf: An Open-Source Infrastructure for Privacy-Preserving Longitudinal Web Browsing Data Collection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-10-30T08:46:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mario Alberto Ramirez, Frank Mangold, Sebastian Stier</p>
    <p><b>Summary:</b> Understanding how people navigate digital media environments requires behavioral data beyond survey self-reports. However, existing infrastructures for collecting such data reproducibly, sustainably, and with strong privacy guarantees remain limited: commercial solutions lack transparency and data governance, while academic tools are typically designed for narrow, short-term use cases and do not support general-purpose academic panel data collections. We address this gap with GESIS Surf, a research infrastructure for large-scale longitudinal collection of web behavioral data in naturalistic environments. The system consists of a browser extension (Chrome and Firefox), a backend with a REST application programming interface (API), and a relational database. It passively captures user interactions, page metadata, and full HTML snapshots of each rendered page, embedding each observation within a hierarchical session model that preserves the structure of browsing behavior. GESIS Surf implements privacy-by-design through strict opt-in participation, per-domain collection rules, and client-side data minimization, ensuring that sensitive data are controlled at the point of collection. The system has been deployed with more than 1,000 participants in a large-scale academic panel infrastructure that includes surveys of participants, and supports reproducible, content-level, and structurally rich analysis of digital behavior. By combining hierarchical session modeling, content-level capture, and integrated privacy enforcement within a unified system, GESIS Surf provides a general-purpose infrastructure for studying digital behavior in a reproducible manner over time.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.41401v1">When Safety Checks Become Privacy Risks: A Privacy-Preserving Paradigm for LLM Agent Safety Auditing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-10-30T08:12:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yixiang Luo, Ziheng Ma, Ke Chang, Jian Wang, Jiqiang Liu</p>
    <p><b>Summary:</b> Large language model agents interact with online services through tool calls that may access private data or perform sensitive actions. Specialized providers can supply and maintain pre-execution safety auditing capabilities for agent operators. However, sending task descriptions, call arguments, and interaction histories to an external auditor may expose sensitive user information. In this work, we propose a paradigm for privacy-preserving safety auditing that separates delegated audit computation from plaintext access and execution authority. Grounded in a three-domain auditing model, the paradigm connects trusted representation construction, encrypted audit computation, and trusted decision and execution through explicit interfaces. These interfaces accommodate alternative representations and scorers, while encrypted computation protects audit inputs from a semi-honest auditor. We instantiate this paradigm in SealCall, a framework combining learned audit representations, CKKS-based encrypted similarity computation, and execution control bound to audited tool calls. Evaluated on 1,252 public binary candidates, SealCall achieves a mean F1 score of 0.840 under grouped nested evaluation, while preserving plaintext audit decisions in all measured cases. A representative configuration completes each encrypted scoring operation in 0.176 s.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.41369v1">BlindStep: A Secure One-Step Kernel for Privacy-Preserving Collaborative Reasoning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-30T07:36:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaoxian Liu, Xingyu Tan, Chen Chen, Xiaoyang Wang</p>
    <p><b>Summary:</b> A recurring step in two-party collaborative workflows combines a private candidate frontier with a partner's compatible evidence, scores the resulting candidates, and retains only a small frontier. Direct execution can expose intermediate candidates, local scores, or unauthorized evidence provenance. Existing MPC platforms and PSI protocols provide useful building blocks, but they do not define a unified post-alignment boundary for bounded-slot aggregation, fail-closed overflow handling, retained-frontier selection, and downstream disclosure. We present BlindStep, a fixed-shape MPC-online kernel for one such post-alignment step between two semi-honest parties. Given a frontend realizing the bounded-slot contract and an application enforcing the reveal policy $ρ$, BlindStep provides a per-invocation simulation-based guarantee in the $F_{\mathrm{align}}$-hybrid model: the kernel leaks only public setup parameters, fixed execution-shape metadata, a global overflow bit, and $ρ$-authorized Layer-2 disclosures. The guarantee excludes malicious security and multi-invocation composition, and treats frontend leakage and offline preprocessing separately.
  Within this kernel boundary, we implement six semi2k realizations in MP-SPDZ, crossing two sharing styles and three top-K strategies: H-variants compare over arithmetic shares, while B-variants convert packed ranking values to Boolean shares before selection. Under LAN, B-Queue is 6-7 times faster and uses about 40 times less communication than H-Queue at N = 256 and 2048. Against H-Sort on the same backend, B-Queue achieves speedups of 21 and 30 times and communication reductions of 204 and 290 times at N = 2048 and 8192, respectively. Under the evaluated N = 256, 100 ms RTT WAN profile, H-Sort becomes fastest, showing that round complexity can dominate backend choice for the measured MPC-online kernel.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.41034v1">Privacy-Constrained Function Computation in Distributed Databases</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-10-29T22:26:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vamoua Yachongka, Rémi A. Chou</p>
    <p><b>Summary:</b> Consider distributed databases that contain both sensitive (private) and non-sensitive (public) attributes. A user seeks to compute a function of public attributes and side information by interacting with the databases and downloading their responses. In this paper, we study the trade-offs among download cost, information leakage about the private attributes, and distortion between the computed function and its reconstruction, referred to as the capacity region. Our main contributions are as follows. For a single database, we provide a complete characterization of the capacity region for general discrete sources and characterize the capacity region of two different setups for Gaussian sources when the computed function is defined as the sum of the public attribute and side information. For distributed databases, we establish inner and outer bounds on the capacity region of discrete sources and we characterize the capacity region when the databases and the side information are mutually independent. As a special instance, we study lossless function computation, and results analogous to the lossy case are obtained.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.40938v1">DiRAFT: Privacy-Aware Financial Transcript Synthesis from Aggregate Discourse Priors</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-10-29T20:13:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yunbai Zhang, Yunyi Gao, Han-Tai Shiao</p>
    <p><b>Summary:</b> Using customer conversations to train and evaluate financial language models raises confidentiality concerns because non-public financial facts can remain after direct identifiers are masked. Synthetic transcripts offer an alternative data source, but their discourse fidelity and residual confidentiality risks require assessment. We introduce DiRAFT (Discourse Realization from Aggregate First-order Transitions), which extracts financial concept graphs and records the order in which concepts are first introduced. It pools adjacent concept transitions across training records and samples new graph plans from aggregate transition, starting-concept, and plan-length priors. A discourse layer guides text realization without supplying an individual source passage or graph. We assess privacy-related risks through two complementary evaluations: corpus-level structural overlap and source-grounded checks for specific non-public investor facts. The structural assessment covers two financial corpora and three generation backends. The confidential-fact assessment uses human review of 1,400 investor-call outputs across seven strategies and two backends. We also evaluate transition fidelity, content recoverability, and trajectory diversity. Stochastic sampling provides a favorable balance between transition fidelity and structural overlap, with consistent advantages over greedy and top-3 on investor calls. The confidential-fact assessment likewise detects fewer matches for stochastic sampling than these alternatives on both backends covered by the fact assessment. These complementary assessments provide empirical evidence on residual confidentiality risks without establishing a formal guarantee.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.40543v1">The Privacy and Security Risks of Edge LLM Optimization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-29T17:36:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mingchen Li, Ren-Yi Huang, Dumindu Samaraweera, Prashant Shekhar, J. Morris Chang</p>
    <p><b>Summary:</b> Edge deployment of Large Language Models requires optimization techniques that reduce memory, computation, and energy costs. However, preserving task performance does not necessarily preserve security. We argue that optimization is an information transformation that can alter representations, decision pathways, and trust boundaries, creating security drift and optimization-induced attack surfaces.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.39954v1">When to spend privacy: optimal allocation in private learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E">
  <p><b>Published on:</b> 2026-10-29T12:51:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Umberto Biccari, Yongcun Song</p>
    <p><b>Summary:</b> Privacy accounting bounds the cumulative privacy cost of Differentially Private Stochastic Gradient Descent but does not determine how to allocate a fixed budget across iterations. We formulate the complete Gaussian noise-variance schedule as an open-loop control under a composed zero-Concentrated Differential Privacy constraint, explicitly accounting for schedule selection. For expected quadratic terminal tracking, we prove that every local minimizer exhausts the certified budget, yielding an exact-budget simplex formulation. We introduce Privacy-Budget Adjoint Mirror Descent (PB-AMD), combining pathwise adjoint gradients with entropic updates that preserve positivity, charge floors, and the prescribed budget. Under regularity and coercivity assumptions, we establish existence and budget stability of optimal schedules, design-to-training utility stability, and deterministic, stochastic, and sample-average stationarity guarantees. A linear-quadratic reduction yields an explicit square-root allocation law. Experiments demonstrate tracking improvements over several allocation rules and predictive improvements over uniform allocation in a learning-rate restart setting, where learning-rate allocation performs similarly. Comparisons at a common stationarity tolerance show lower schedule-optimization times than projected gradient descent on the tested problems. The framework connects certified privacy accounting with optimization through nonlinear training dynamics.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.39754v1">Toward Complete Speaker Anonymization: a Streaming Cascaded System for Voice Privacy and PII Removal</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> 
  <p><b>Published on:</b> 2026-10-29T10:09:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stanisław Kacprzak, Thomas Thebaud, Najim Dehak</p>
    <p><b>Summary:</b> We present a cascade streaming voice privacy system, consisting of ASR, NLP, and TTS modules. By leveraging recent improvements in all three aspects of speech and language processing, we show that such a system is capable of achieving a result comparable to state-of-the-art offline voice privacy systems, while providing controllable capabilities of content protection beyond voice. With an estimated utterance-onset end-to-end latency of 717 ms, the presented system preserves speech content with 11% WER on Librispeech, while detecting PII with a 69% SLU F1 score and achieving up to 47.66% EER against a semi-informed attacker.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.39532v1">Judging Before Propagation: Task-Graph Contextual Integrity for Multi-Agent Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-10-29T07:31:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hengyu Wu, Blaise Delattre, Yang Cao</p>
    <p><b>Summary:</b> Multi-agent LLM systems increasingly rely on persistent memory and inter-agent communication. These capabilities create privacy risks that extend beyond individual interactions: a release appropriate in isolation may become inappropriate when combined with information previously disclosed to a recipient or propagated to downstream agents along the planned workflow. Existing Contextual Integrity (CI) mechanisms for agentic systems typically rely on local judgments that assess each disclosure in isolation, with or without regard to the recipient's history, but do not account for how information propagates downstream. However, compliance at the current boundary does not guarantee appropriateness across the workflow. We introduce Task-Graph Contextual Integrity (TG-CI), to our knowledge the first task-graph-native formalization of Contextual Integrity for multi-agent systems. TG-CI represents a workflow as a Multi-Agent Task Graph (MATG) and extends CI from atomic transfers to stateful, graph-level information flows by jointly considering an item's intended propagation scope and recipients' evolving disclosure states. We operationalize TG-CI through propagation-scoped authorization under two complementary policies: Full-Scope, which requires admissibility across the complete downstream scope, and Auto-Region, which confines each item to its maximal admissible region using lightweight frontier gates. We further introduce MAPLE-Bench, a benchmark of 144 cases across four scenarios that jointly vary MATG topology, disclosure history, compromised-agent placement, and item-level privacy policies. In our primary experimental configuration, TG-CI reduces the mean unauthorized disclosure count by 85.8-94.1% relative to the Local-History CI baseline, while retaining 93.6-96.1% of the baseline's task accuracy, with the two enforcement policies providing complementary privacy--cost--utility trade-offs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.40714v1">PrivacyFlow: Privacy in AI Agents through Information Flow Analysis and Consequence-Aware Risk Management</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-29T01:54:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Robin Staab, Tom Wollschläger, Vahab Mirrokni, Reza Shokri</p>
    <p><b>Summary:</b> Autonomous LLM agents executing multi-step workflows over personal data often misalign with user privacy expectations and leak sensitive, out-of-context information. Although Contextual Integrity (CI) formalizes this problem, existing benchmarks and defenses rarely operationalize CI for realistic multi-step task sequences in evolving environments. In this work, we first introduce agentic PrivacyBench, a benchmark of 5873 tasks in 986 task sequences with dynamic environment updates and CI-grounded allow-sets for sensitive information. We also introduce PrivacyFlow, a defense that separates deliberative privacy planning (System 2) from task execution (System 1), treating each sharing decision as a structured risk-management problem. Before execution, PrivacyFlow traces the provenance and purpose of each planned data flow, models recipient background knowledge, and simulates what external actors could infer. This allows us to model the downstream consequences of disclosure, including inference attacks and context-dependent harms. It then weighs the remaining disclosure risk against task utility and executes a minimized plan, blocks it, or consults the user. Across six models, PrivacyFlow significantly reduces step-level privacy failures and raises the share of completed task sequences without a detected privacy violation by 22--55 percentage points. We further highlight a new privacy--utility--autonomy tradeoff: allowing PrivacyFlow to proactively prompt the user in case of uncertainty can increase authorized task completion at the cost of shifting decision effort back to the user. Our results suggest that proactive CI reasoning can substantially improve agentic privacy and motivate further study of this tradeoff.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.39112v1">Communication and Privacy Trade-Offs in Distributed Storage With Shared Secret Keys</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-10-29T00:52:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maryam Keshvari, Remi A. Chou</p>
    <p><b>Summary:</b> We study distributed storage over public communication channels where privacy is realized using shared secret keys. Specifically, a user wishes to store a file across $L$ servers such that any subset of at least $t$ servers can reconstruct the file, while any subset of at most $z$ colluding servers learns no more than a fraction $α$ of the file. Unlike classical secret-sharing models that assume secure communication channels between the user and each server, we consider a setting where all transmissions occur over a public channel and the user shares an individual secret key of length $n$ bits with each server. For a fixed key length $n$, we characterize the trade-off between the privacy leakage parameter $α$ and the maximum file size that can be securely stored. Additionally, we determine the minimum local randomness, public communication, and storage required to achieve this optimal trade-off.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.38802v1">How Does Perceived Empathy From AI Chatbots Shape Users' Privacy Attitudes, Behaviors, and Needs?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-10-28T20:05:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiaxun Cao, Hiba Laabadli, Yuntong Xue, Jana Schaich Borg, Pardis Emami-Naeini</p>
    <p><b>Summary:</b> Prior research suggests that some dimensions of AI empathy may increase users' disclosure to chatbots, posing growing privacy risks as chatbots become more capable of empathic interaction. Yet this work often conceptualizes AI empathy narrowly, leaving users' own definitions and their broader privacy experiences unexplored. We interviewed 21 AI Chatbot users about what AI empathy meant to them and how it shaped their privacy attitudes, behaviors, and needs. Participants characterized empathy through five components--understanding, resonating, caring, expressing, and helping. Most participants viewed resonating and caring as essential components of human empathy but absent from AI empathy. Yet AI's contextual, in-depth understanding and helpfulness still encouraged highly sensitive disclosure. This highlights that AI empathy can endanger users' privacy without necessarily making AI seem human. Participants also desired varied forms and levels of empathy, each associated with distinct privacy needs. We offer actionable recommendations for designing privacy-enhancing mechanisms for empathic AI interactions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.38793v1">Trustworthy Distributed Machine Learning in Cloud-Edge-IoT Systems: A Heterogeneity-Aware Survey of Security, Privacy, and Robustness</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-28T20:00:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Long Dang, Ali Alfatemi, Kaiqi Xiong, Mohammed Aledhari, Abdellah Chehri, Shawqi Al-Maliki, Mohamed Rahouti</p>
    <p><b>Summary:</b> Distributed machine learning (DML), including conventional distributed training and federated learning (FL), enables collaborative model development across cloud-edge-IoT systems without fully centralizing raw data. However, distributing data, computation, updates, and orchestration increases the attack surface and introduces coupled challenges across privacy, robustness, reliability, fairness, and governance. This survey presents a security-centered, heterogeneity-aware roadmap for trustworthy DML, with FL treated as a prominent high-risk case. We first characterize the assets, adversaries, trust assumptions, and coordination patterns that define DML/FL security boundaries. We then analyze how statistical, system, and trust heterogeneity, including non-IID data, resource asymmetry, intermittent participation, and cross-silo/cross-device trust differences, affect convergence, fairness, attack detectability, and defense reliability. Next, we synthesize attack-defense interactions across poisoning, backdoors, Byzantine manipulation, privacy leakage, model extraction, network/orchestration attacks, Sybil behavior, and strategic participation. We further compare layered defenses, including robust aggregation, drift-aware optimization, differential privacy, secure aggregation, homomorphic encryption, secure multiparty computation, trusted execution environments, watermarking, provenance, authenticated communication, and monitoring. Finally, we discuss deployment, evaluation, governance, and open research guidelines, emphasizing reproducible, non-independent and identically distributed (non-IID) partitions, attack-aware benchmarks, privacy budgets, attack success rate, client-level disparity, latency, communication, memory, energy/carbon overhead, and auditable lifecycle artifacts.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.38756v1">Channel State Information-Free Angle Spoofing for Differential Localization Privacy</a></h3>
  
  <p><b>Published on:</b> 2026-10-28T19:36:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lei Lyu, Urbashi Mitra</p>
    <p><b>Summary:</b> This paper proposes a channel state information (CSI)-free angle spoofing strategy that remains effective even when the eavesdropper (Eve) uses differential statistics to estimate the location of the transmitter (Alice). Specifically, by designing a precoding matrix, Eve incorrectly estimates the angle differences of departure (ADoDs), thereby spoofing Alice's location. Meanwhile, the trusted user (Bob) can still infer Alice's true location with a modest amount of securely shared side information. Given the channel parameters estimated by Eve from the spoofed channel, the resulting localization bias introduced to the eavesdroppers under the spoofed geometric is analyzed. Eve's bias can be driven to infinity asymptotically in a key parameter of the precoder. Simulation results demonstrate that the proposed method introduces significant localization errors for Eve. When combined with a prior CSI-free spoofing strategy, further degraded performance is achieved by Eve.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.38645v1">Hyperentanglement-enabled Quantum Privacy Amplification for Classical-Quantum Coexistence in Fiber Networks</a></h3>
  
  <p><b>Published on:</b> 2026-10-28T10:55:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Domenico Ribezzo, Giulia Guarda, Alessandro Zavatta, Davide Bacco</p>
    <p><b>Summary:</b> Integrating quantum communication into existing fiber infrastructures requires coexisting with high-power classical traffic, which generates noise in the quantum channel. Spontaneous Raman Scattering (SpRS) is the dominant noise source, generating a broadband photon background that degrades quantum states and, in Quantum Key Distribution (QKD), can entirely suppress secure key generation. In this work, we implement single-copy entanglement distillation utilizing energy-time and frequency hyperentanglement, and we exploit it to perform Quantum Privacy Amplification (QPA) directly at a physical layer. Strict frequency anti-correlations of spontaneous parametric down-conversion are used to selectively discard uncorrelated Raman photons while preserving genuine entangled pairs, suppressing accidental coincidences by a factor $1/N$, where $N$ is the number of frequency channel pairs. Using passive borosilicate-glass photonic integrated circuits and standard DWDM demultiplexers over a 20~km single-mode fiber testbed, we demonstrate a 4~dB improvement in tolerance to classical laser launch power $P_C$ when QPA is performed, extending the secure key threshold from $P_C=-13.3$ dBm to $P_C=-9.3$ dBm. The result shows that off-the-shelf telecom components can be repurposed as physical-layer quantum privacy amplifiers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.38543v1">The State of the Practice in Privacy Impact Assessments: Understanding the Professionals' Perspectives, Experiences, and Current Procedures</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-28T09:45:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Samuel Wairimu, Leonardo Horn Iwaya, Ala Sarah Alaqra</p>
    <p><b>Summary:</b> Organisations frequently utilise Privacy Impact Assessments (PIAs), Data Protection Impact Assessments (DPIAs), or even Fundamental Rights Impact Assessments (FRIAs) to identify and evaluate potential risks and possible infringements of fundamental rights. While the adoption of PIAs and DPIAs has grown significantly in recent years, robust scientific evidence regarding their operational challenges, implementation strategies, and tangible benefits remains scarce. In particular, empirical research conducted post-enactment of the General Data Protection Regulation (GDPR) is notably limited -- especially studies that directly interview professionals about their PIA/DPIA practices or their engagement with FRIAs. To do so, in this paper we leveraged semi-structured interviews to elicit privacy professionals' perspectives on PIA/DPIA activities and analysed the responses using reflexive thematic analysis. As a result, this work provides a comprehensive thematic framework for the field, offering a rich and thick description of professionals' views and experiences. In total, 26 participants from 17 countries were interviewed, revealing how they plan and conduct PIAs/DPIAs, including how they assess trade-offs, the benefits and challenges they perceive, and how they view the interplay between PIAs/DPIAs and the EU AI Act. Among the main findings were low adherence to established DPIA methodologies; differences and similarities between PIAs and DPIAs; a perceived neglect of data subjects' interests during DPIA processes; discussions on building FRIAs on top of DPIAs; and the potential for holistic impact assessments, though accompanied by concerns regarding assessment fatigue. Thus, this study informs privacy professionals about real-world challenges and experiences of PIA/DPIA implementation, and guides researchers toward future research directions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.37527v1">Extending the W3C Data Privacy Vocabulary to Cover the German Health Data Use Act - Lessons Learned</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-10-27T16:48:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Julian Flake, Christian Henke, Alessandra S. Kuntz, Matthias Löbe, Harshvardhan J. Pandit, Christian Draeger</p>
    <p><b>Summary:</b> Finding, sharing, and reusing data requires common interoperable vocabularies to adequately describe machine-actionable data policies. Semantic Web standards are a proven way to express such information describing data access and reuse. Narrative descriptions get a stable and agreed meaning by formal definitions of terms that have a globally unique identifier. The Data Privacy Vocabulary (DPV) represents a community standard for privacy, data protection, and related topics. DPV uses modular namespaces to define jurisdictions, such as "EU", and to represent concepts from laws within that jurisdiction, such as the General Data Protection Regulation (GDPR) and the European Health Data Space (EHDS). In this work, we present the creation of a DPV extension representing the German Health Data Use Act (Gesundheitsdatennutzungsgesetz (GDNG)) that has been set into force in March 2024. The GDNG regulates sharing and using health data for secondary use, such as research purposes and policymaking. It builds the German legal foundation for the future EHDS as the European initiative and regulation providing rules for sharing of health data within Europe. The parallel development of the EHDS and GDNG extensions resulted in many shared concepts, which contributed to an overarching extension: the DPV sector health extension. It sets the foundation of aligned privacy terms for future EHDS member states looking to build a national vocabulary aligned with the EHDS. All extensions were released as draft extensions with the latest DPV version 2.3, released 25th of February 2026.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.37488v1">Revisiting Privacy Risks in Quantized Deep Neural Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-27T16:14:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jie Fu, Ren Li, Wendy Hui Wang</p>
    <p><b>Summary:</b> Model quantization has become a fundamental technique for enabling the efficient deployment of large-scale deep neural networks (DNNs) in data-intensive applications by reducing model size. Despite its widespread adoption, the impact of quantization on training data privacy --- particularly vulnerability to membership inference attacks (MIAs) --- remains largely unexplored. In this paper, we present the first comprehensive empirical study of privacy risks in quantized DNNs, evaluating eight state-of-the-art MIA attacks across six representative quantization methods. Our results reveal that practical quantization levels (4-8 bits) have limited impact on membership privacy risks, with quantized models remaining largely as vulnerable as their full-precision counterparts. Although aggressive low-bit quantization (e.g., 2-bit) can provide meaningful privacy gains, these benefits come at the cost of substantial utility degradation. To understand the underlying causes of these observations, we systematically analyze how different quantization strategies affect model behaviors and outputs, and how these changes influence privacy vulnerability. Beyond evaluating attack risks, we further investigate whether existing privacy defenses developed for full-precision DNNs can effectively protect QNNs. Our results show that these defenses provide only limited additional privacy protection when applied to quantized models, while further amplifying utility degradation. Our study provides practical guidance for privacy-aware deployment of quantized DNNs and motivates the development of new attack and defense mechanisms for QNNs. Our code and datasets are publicly available at https://github.com/JeffffffFu/Priv-QDNN.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.37424v1">Privacy-Preserving Over-the-Air Federated Learning over Cell-Free Massive MIMO System with User-Centric Clustering</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2026-10-27T15:37:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Manobendu Sarker, Soumaya Cherkaoui</p>
    <p><b>Summary:</b> This paper investigates cross-layer design for differentially private federated learning over cell-free massive MIMO networks with over-the-air (OTA) aggregation. Distributed access points (APs) collaboratively serve user equipments (UEs) through user-centric clustering, where clipped local model updates are perturbed with Gaussian noise and simultaneously transmitted over a shared uplink for OTA averaging at a central processing unit. Exploiting channel hardening, we show that thermal noise inherent in wireless reception can act as a privacy-masking resource, reducing or even eliminating the need for artificial noise. Based on this observation, we formulate a joint optimization problem over AP-UE associations, UE transmit powers, and artificial noise variances to minimize aggregation variance subject to per-UE zero-concentrated differential privacy constraints derived from an ergodic privacy accounting framework. Analysis reveals a regime-dependent structure: stringent privacy requirements favor low transmit powers and sparse AP associations to exploit thermal noise for privacy, whereas relaxed requirements favor larger clusters to improve aggregation quality. The resulting mixed-integer nonconvex problem is solved via alternating optimization combining difference-of-convex power allocation and greedy coordinate-descent clustering. Numerical results show up to 89% lower aggregation variance than conventional baselines and enable 97% test accuracy on MNIST with consistent gains on CIFAR-10. Under strict privacy budgets, competing schemes remain near random-chance performance, while under relaxed budgets they continue to lag significantly behind the proposed design.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.36711v1">PrivacyEvalClaw: A Tool-Augmented Deliberative Agent for Auditing Privacy Leakage in LLM Jailbreak Responses</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-27T06:27:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Krishna Kanth Nakka, Yujun Wang, Shijie Zhou, Tu Nguyen, Gabriele Gelardi, Xuebing Zhou</p>
    <p><b>Summary:</b> Reliable evaluation is a critical bottleneck in privacy red-teaming of large language models (LLMs): determining whether a jailbreak response actually reveals personal information can be difficult when disclosures are indirect, contextual, partial, or obfuscated. Existing evaluation approaches increasingly rely on guard models and LLM-as-Judges, yet these evaluators may interpret the same response differently. To better characterize this evaluation setting, we conduct a systematic study of privacy evaluators and find substantial disagreement, particularly in ambiguous cases that require additional evidence or targeted analysis to resolve. Motivated by these findings, we introduce \textsc{PrivacyEvalClaw}, a training-free deliberative agent for evaluating privacy leakage in LLM jailbreak responses. Rather than relying on isolated single-pass judgments, PrivacyEvalClaw treats evaluators and analysis modules as tools, adaptively gathers evidence, investigates uncertain disclosures, and reconciles conflicting signals before producing a final judgment. Our primary experiments use pairwise LLM-as-Judge evaluation of complete trajectories, showing that PrivacyEvalClaw achieves favorable win rates against competing baselines across outcome, process, and overall quality, while producing explicit reasoning traces that make the evaluation process more transparent and auditable.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.36626v1">Measuring Users' Security and Privacy Concerns About Third-Party Community Bots on Discord</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-10-27T04:31:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kofi Ampomah, Tu Le</p>
    <p><b>Summary:</b> Third-party community-based bots are central to how social platforms such as Discord work. They moderate content, manage roles, play music, and support AI-assisted conversations across millions of servers. Yet when a bot is installed in a server, it can access messages, user profiles, and server metadata concerning members who did not participate in the installation decision, with no standardized way to communicate the associated security and privacy implications. In this paper, we analyze 23,102 third-party Discord bots and 183,142 user reviews spanning 49 detected languages and five years of feedback (2021-2026). We employ LLM-based knowledge distillation and fine-tune a DeBERTa-based classifier to identify candidate security and privacy (S&P)-relevant reviews. After manually validating the complete classifier-positive set, we retain 8,832 reviews identified as S&P-relevant, representing an observed pipeline yield of 4.82%, and map them to a 31-theme S&P taxonomy extending prior work. Our results show that S&P-related reviews focus heavily on Data Sharing (30.5%) and Data Collection (16.2%). Confession and anonymity bots have pipeline-identified SPRRs above 50%, more than ten times the ecosystem-wide pipeline yield of 4.82%. Star ratings may obscure the frequency and valence of S&P-related discussion, while conventional metadata features, such as permission count and administrator status, show only weak associations with user-reported S&P concerns. We then build BotLens, a proof-of-concept auditing framework that combines review-derived S&P signals with bot metadata to provide on-demand decision support for the community-based bot ecosystem. BotLens exposes six tools through a Model Context Protocol server, supporting bot-level checkups, server-wide comparison, and integration with AI agents.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.36379v1">Evaluating Federated Vision-Language and Vision-Only Models for Privacy-Aware Breast Cancer Imaging</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-26T22:51:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Malithi Mithsara Wanniarachchi Kankanamge, Ning Yang, Sree Bash Debnath, Md Zobaer Islam, Abdur R. Shahid</p>
    <p><b>Summary:</b> Artificial intelligence (AI) shows promise for breast imaging, but limited labeled data, institutional data fragmentation, and privacy concerns hinder centralized training. We investigate a privacy-aware federated learning framework combining pretrained vision-language models (VLMs) with client-level differential privacy. We compare general-purpose CLIP models, biomedical BiomedCLIP, and an ImageNet-pretrained ViT-B/16 baseline on two public breast imaging datasets, with and without differential privacy. We also evaluate a CLIP ViT-B/16 ablation that removes the text pathway. Evaluation includes patient-level ROC-AUC with bootstrap 95% confidence intervals, baseline comparisons, threshold sensitivity, inter-model agreement, and communication cost. Under federated learning, all five models achieve high normal-versus-sick discrimination (ROC-AUC: 0.940-0.990). However, acquisition year alone achieves 0.974 on the same test partition, raising concerns about confounding rather than genuine pathology recognition. Benign-versus-malignant discrimination remains uncertain (ROC-AUC: 0.504-0.637), with all confidence intervals including 0.50. Removing the text pathway preserves classification accuracy while halving communication cost. Differential privacy reduces ROC-AUC by 0.375, attributable to perturbing the full model state rather than only trainable parameters. These findings highlight the importance of evaluating confounding, predictive reliability, privacy implementation, and deployment efficiency when developing federated AI systems for breast imaging.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.36243v1">Characterizing Privacy Leakage in Spiking Neural Networks: A Systematic Analysis of Temporal Dynamics, Stochasticity, Neuronal Dynamics and Learning Mechanisms</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Neural and Evolutionary Computing-5BC0EB">
  <p><b>Published on:</b> 2026-10-26T20:22:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ayana Moshruba, Maryam Parsa</p>
    <p><b>Summary:</b> Spiking neural networks (SNNs) encode information not only in whether neurons fire but also in when they fire, and this temporal dimension shapes what a trained network reveals about its training data. Biologically inspired firing patterns can reduce membership leakage in SNNs without changing the network architecture, which positions temporal dynamics as a design variable for privacy. A change in firing behavior, however, alters stochasticity, spike timing, neuronal response, and the learning problem at once, so harnessing this effect requires identifying which of these properties produces it. This study traces that origin by separating temporal representation, stochasticity, intrinsic neuron dynamics, and learning within a common experimental framework, evaluated under a black-box membership inference attack across image and tabular benchmarks. Varying the temporal representation shows that burst-like firing patterns reduce leakage relative to regular spiking, but at a cost in accuracy. Injecting randomness into the input, spike timing, and spike trains does not reproduce this reduction in leakage, which shows that the reduction arises from how spikes are arranged in time rather than from noise. The privacy benefit further depends on where these firing patterns originate. When neurons generate these patterns through their own adaptive dynamics, leakage falls while accuracy is preserved, so privacy no longer comes at the expense of performance. The learning algorithm then sets the baseline leakage. Under evolutionary training, the attack already performs near chance level, leaving temporal dynamics little room to improve privacy further. Privacy in SNNs is therefore not an inherent property of spikes but a product of how temporal activity is generated, processed, and learned, which offers a principled basis for designing neuromorphic systems that protect sensitive data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.36168v2">PrinGS: Privacy Preservation in Gaussian Splatting</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-10-26T19:02:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gaurav Behera, Abhinav Raundhal, Archisha Panda, Saumya Balina, Gargi Shroff, Ponnurangam Kumaraguru</p>
    <p><b>Summary:</b> 3D Gaussian Splatting (3DGS) has rapidly become the preferred representation for high-fidelity novel view synthesis and 3D scene reconstruction. However, the learned representation encodes sensitive visual information including human faces, license plates, documents, and computer screens, raising significant privacy concerns when trained splats are shared or deployed. In this work, we address the underexplored problem of privacy preservation in Gaussian Splatting by proposing a representation-level anonymization framework that directly anonymizes a trained splat. Given a trained splat and a user-provided reference view identifying sensitive content, our method localizes the corresponding regions in the underlying 3D representation and directly anonymizes them, ensuring that the sensitive information is absent from all subsequently rendered novel views while preserving the overall scene geometry and visual fidelity. We achieve this post-training anonymization in less than 1 second. Furthermore, we extend our framework with a privacy-by-design training strategy that prevents sensitive content from being embedded into the representation during optimization, enabling the generation of privacy-preserving splats directly from training images. Our method achieves a remarkably low Face Similarity Measure (FSM) of 9.79% at a retained Face Detection Rate (FDR) of 39.47% and makes sensitive text completely unreadable with an OCR Character Error Rate of 1.00. Our work aims to serve as the primary stepping stone towards privacy-aware 3D representations and motivates further research along these directions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.35729v1">A Category-Selective Encryption Framework for Privacy Protection of UAV Images</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-10-26T16:46:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ting Yan, Minghui Shang, Haolang Sun, Xu Wang, Yamin Han, Mingze He</p>
    <p><b>Summary:</b> Imagery captured by unmanned aerial vehicle (UAV) systems increasingly raises privacy concerns, as UAV aerial surveillance routinely captures sensitive objects such as pedestrians and vehicles alongside ordinary scene content. Existing privacy-preserving approaches typically employ class-agnostic saliency detection to indiscriminately obfuscate all visually salient regions, leading to unnecessary information loss and hindering downstream scene analysis. This paper proposes a category-selective encryption framework for privacy-preserving UAV surveillance. The core advance over prior class-agnostic approaches is semantic-level selectivity: the system first recognizes what is present in the scene via an 80-class detector, then encrypts only user-specified sensitive categories while leaving non-sensitive objects and background intact for downstream analytics. The framework supports two complementary encryption schemes: Thumbnail-Preserving Encryption (TPE), which applies adaptive pixelation with a learnable blend parameter and recovers content through a jointly trained Enhanced U-Net, and XOR stream cipher encryption, which offers parameter-free, mathematically exact reversibility. The architectural design, composite loss formulation, and joint training methodology are presented in detail, establishing a foundation for practical privacy-preserving UAV surveillance that balances protection strength and scene utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.34640v1">InferPriv: Evaluating Inferential Privacy Leakage in LLM Assistants</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-10-25T23:51:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pengrun Huang, Yiwei Fu, Luoxi Meng, Kamalika Chaudhuri</p>
    <p><b>Summary:</b> Large language model (LLM)-based personal agents are increasingly deployed to handle everyday tasks on users' behalf. These agents have access to private user information, while their tasks involve communicating with third parties; this raises a critical privacy concern that agents may inappropriately reveal sensitive user information to these recipients. Existing benchmarks primarily assess direct privacy leakage, where an agent explicitly states a pre-specified secret or attribute. However, they do not capture \textit{inferential leakage}, where the model leaves indirect cues in the reply that implicitly leaks sensitive attributes. We introduce \textsc{InferPriv}, a benchmark that measures whether an honest-but-curious recipient can infer a user's sensitive attributes from an LLM's reply on routine task. Evaluating five frontier models, we find that inferential leakage substantially exceeds direct leakage across models and prompts. Under a privacy-aware system prompt, GPT-6.1-Sol, Sonnet-5.5, and Gemini-3.8-Flash achieve near-zero direct leakage, yet the inferential leakage rate remains between 16.2--25.2\%. These findings suggest that evaluating explicit leakage alone can substantially understate the privacy risks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.34130v1">StickFigure: Enabling Pose-Only IoT Cameras for Privacy-Preserving Edge Vision</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-10-25T07:58:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aveline Xiaoyuan Han, Chenshu Wu</p>
    <p><b>Summary:</b> Indoor IoT cameras can support assisted living and activity-aware spaces, but exporting raw RGB frames raises privacy concerns by exposing facial, clothing, and household details that body-motion tasks often do not require. We present StickFigure, a pose-only IoT camera system that, during real-time monitoring, keeps raw frames local and ephemeral while exporting only compact skeleton streams sufficient for downstream human activity recognition (HAR). While pose estimation has matured on GPUs, extracting accurate pose streams on resource-constrained IoT cameras remains difficult. To overcome these challenges and enable on-device pose streams on (almost) any IoT camera, we present two core designs in StickFigure: an activation-aware pose backbone that allocates channel capacity after spatial downsampling and a lightweight hierarchical MLP refiner that selectively corrects elbow and wrist coordinates using intermediate visual features and kinematic context. We fully implement StickFigure and evaluate it on public benchmarks and real-world deployment. Compared with state-of-the-art MCU pose models, StickFigure achieves the highest pose accuracy and downstream HAR utility on both NTU RGB+D and Penn Action, while using 96.5% fewer parameters and 99.3% fewer MACs per frame than RTMPose-S-based baselines, achieving 0.107 s p95 latency on a representative STM32H753 MCU. We believe StickFigure establishes a new operating point for privacy-aware edge vision on massive IoT cameras.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.33712v1">Projection-Based Federated Learning on Compact Submanifolds with Geometry-Independent Differential Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-24T14:52:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Thibault Pautrel, Florent Bouchard, Guillaume Ginolhac, Ammar Mian, Aurélien Bellet</p>
    <p><b>Summary:</b> Federated learning trains a shared model across clients without exchanging their data, yet the updates they transmit still leak information about individual records. Enforcing differential privacy is harder still when the model parameters lie on a Riemannian manifold. Existing methods rebuild the noise added for privacy in the geometry of each new iterate, aggregate through intrinsic maps that often lack a closed form, and prove convergence only in restricted regimes. We introduce DP-RFedProj, a record-level differentially private federated learning method for compact submanifolds that aggregates through closed-form projections and privatises gradients in a fixed ambient geometry. Each client may run any stochastic first-order optimiser, take several local steps, and participate only intermittently. An explicit record-level $f$-DP guarantee holds for the entire training transcript, independently of the manifold, the aggregation scheme and the local optimiser. We establish convergence of DP-RFedProj when each client runs Riemannian SGD locally and the server aggregates by projected averaging, and show that privacy enters the rate through a term scaling with the manifold's intrinsic dimension rather than the ambient one. Synthetic experiments on federated PCA over the Grassmann manifold corroborate these findings. On EEG motor-imagery classification with SPDNet, whose weights lie on the Stiefel manifold, the method outperforms a Euclidean baseline at every privacy budget considered. In both experimental settings, our accounting requires five to six times less noise than that of the closest prior method for the same budget, which translates into higher utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.33206v1">A-GE: Privacy-Preserving Age Assurance via Fine-Grained Motion</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-23T18:52:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohammed Gharib, Giovanni Cascone, Martin Zizi</p>
    <p><b>Summary:</b> Age assurance faces a fundamental privacy dilemma: meaningful assurance typically requires revealing identity or other sensitive information, whereas privacy-preserving alternatives often provide little assurance. Existing approaches either disclose sensitive information directly or shift the disclosure and trust requirement to an identity provider, while self-declared age provides little meaningful assurance. Thus, a fundamental gap remains between establishing an age property and revealing information beyond what is necessary to establish that property. We present \textit{A-GE} (Age-Grounded Evidence), a privacy-preserving age assurance system that derives age-related evidence from fine-grained motion captured by commodity inertial measurement units (IMUs). A-GE exploits subtle motion dynamics that we hypothesize reflect underlying neuromuscular and physiological processes during ordinary device interaction. It requires neither identity information nor government identification and operates across available sensor sampling rates, including the approximately 60~Hz limit of web-based sensing, with configurable minimum-age thresholds ranging from 14 to 21 years. We evaluate A-GE on more than 600 participants, with separate participant-disjoint cohorts for model development and final evaluation. At a 16-year minimum-age threshold, A-GE achieves up to 93.8\% accuracy with a comparable F1 score across the evaluated configurations. We further demonstrate client-side deployment on Android, iOS, and the web, and examine unintended attribute inference and residual privacy risks, characterizing both the privacy benefits and limitations of deriving age evidence from commodity motion.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.32822v2">On the Limits of Sparse Linear Model with Shuffled Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-23T15:56:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yan Zhang, Jiong Tuo, Meng Ding, Yuheng Ma, Di Wang</p>
    <p><b>Summary:</b> Sparse linear regression is a fundamental problem in high-dimensional statistics, and its private counterparts leave a large gap between the central and the local model of differential privacy. Shuffled differential privacy (SDP) sits between the two, offering accuracy closer to the central model without the trust requirement of a central curator. This paper studies sparse linear regression under both non-interactive and interactive SDP protocols. In the non-interactive setting, any non-interactive $(ε,δ)$-SDP protocol is shown to incur an $\ell_2$-norm estimation error of $Ω( \frac{\sqrt{dk}}{nε} )$ with dimension $d$, sparsity $k$, and $n$ users, revealing an inherent dimensionality barrier. In addition, a non-interactive algorithm is proposed that achieves an $\ell_2$-norm upper bound of $\tilde{\mathcal{O}}( \sqrt{\frac{k}{n}} + \frac{d\sqrt{k}}{nε})$. To overcome this barrier, we turn to the interactive user-level setting, where each user holds $m$ samples. A two-round interactive algorithm is developed that first recovers the support through a heavy hitter step and then estimates the parameter, achieving an error of $\tilde{\mathcal{O}}( \sqrt{\frac{k}{nm}} + \frac{k}{n\sqrt{m}ε} )$ with no polynomial dependence on $d$. Furthermore, by extending the score attack framework to user-level data, a new lower bound $Ω( \sqrt{\frac{k\log(d/k)}{nm}} + \frac{k\log(d/k)}{n\sqrt{m}ε} )$ is established for any user-level $(ε,δ)$-DP, showing that the proposed algorithm is near-optimal with only a gap of the factor $\log(d/k)$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.32626v1">Privacy-Preserving Federated Loss Exploration for Vision-Based Perception under Non-IID Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-23T13:41:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nergiz Yuca, Christian Internò, Nikolay Matyunin, Markus Olhofer, Barbara Hammer, Stefan Katzenbeisser</p>
    <p><b>Summary:</b> Vision-based image classification models benefit from Federated Learning (FL) across vehicles, however learning accurate models from distributed vehicular cameras is challenging due to data heterogeneity and privacy concerns. To improve performance on non-IID data, advanced FL optimization approaches have emerged that share auxiliary insights, such as client gradient behaviors. While these gradient-guided optimized FL methods improve the model accuracy, their reliance on sharing additional gradient information introduces a previously unexplored privacy vulnerability. In our empirical privacy-leakage experiment, we show that a malicious server can infer clients' label sets from shared guidance matrices under heterogeneous client label distributions (simulated via Dirichlet-based label partitions), between 50% and 84% accuracy. To address this privacy leakage, we propose PPFLex that replaces the central server with three Secure Multi-Party Computation (MPC) servers to securely compute the global guidance matrix and perform federated averaging under semi-honest and malicious MPC server assumptions. We evaluate PPFLex on widely used traffic-sign classification datasets (e.g., GTSRB and BTSC) as representative autonomous vehicle perception benchmarks, comparing against baselines. Our results show that PPFLex achieves accuracy comparable to the plain-text FedLEx pipeline while preventing privacy leakage, incurring acceptable MPC overhead.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.32576v1">From Regulation to Engineering: Organizational Privacy Climate as Mediator</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2026-10-23T13:03:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Oshrat Ayalon, Eran Toch, Irit Hadar, Michael Birnhack</p>
    <p><b>Summary:</b> Data protection legislation aims to protect privacy rights by regulating how information systems store and process personal information. While such legislation defines legal obligations, translating regulatory requirements into engineering practice is far from straightforward. As new frameworks such as the EU AI Act emerge, understanding these mechanisms becomes increasingly relevant. To investigate them, we conducted an online survey of 156 U.S. information system developers, examining the role of organizational privacy climate in the association between developers' perceptions of the GDPR and their privacy engineering practices. Using structural equation modeling, we found that organizational privacy climate mediates the relation between developers' perceived GDPR importance and their privacy attitudes, which in turn are associated with their privacy engineering practices. The mediation chain - regulation, climate, attitudes, practices - complements the direct effect of regulation on practice, revealing the organizational and attitudinal pathway through which regulatory intent reaches engineering behavior. We discuss implications for the next generation of privacy and AI regulation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.31612v1">Efficient and Optimal Learning of Discrete Distributions with Person-Level Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2026-10-22T17:40:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gautam Kamath, Mahbod Majid, Ankur Moitra, Argyris Mouzakis, Jonathan Ullman</p>
    <p><b>Summary:</b> We study learning a discrete distribution under person-level differential privacy in the batched setting. Given $n$ users, each contributing $m$ i.i.d. samples from an unknown distribution $μ$ over $[k]$, we seek an estimate of $μ$ with total-variation error $α$. We give polynomial-time algorithms under both pure and approximate differential privacy. Under pure $(\varepsilon,0)$-DP, we achieve $n = \widetilde O(k/(α^2 m)+k/(α\sqrt{m}\varepsilon)+k/\varepsilon)$, the first polynomial-time pure-DP guarantee matching the information-theoretic optimum up to logarithmic factors. Under approximate $(\varepsilon,δ)$-DP, we achieve $n = \widetilde O(k/(α^2 m)+k/(α\sqrt{m}\varepsilon)+k+\log(1/δ)/\varepsilon)$. At $δ=2^{-Θ(k)}$, this is $\widetilde O(k)$ for fixed $α,\varepsilon,m$ and failure probability. Our algorithms use a new degree-6 sum-of-squares estimator for learning from untrusted batches. Its key ingredient is a trace-bounded diagonal majorizer for the difference between the empirical covariance of the repaired batch averages and the multinomial covariance predicted by their mean. We prove that clean data admit this certificate through semidefinite-programming duality and a new application of the stronger symmetric form of Grothendieck's inequality due to Friedland and Lim. The certificate preserves the mean-dependent variance of multinomial batch averages, yielding the near-optimal robust rate $O(η\sqrt{\log(1/η)/m})$ and providing the score required by the privacy reduction. We also prove a statistical query lower bound ruling out a uniformly smaller order of error under fixed polynomial SQ resource bounds.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.31549v1">Shift-aware score transport for privacy auditing without retraining</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-22T16:54:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yaohong Yang, Gauri Pradhan, Qi Chen, Samuel Kaski, Antti Honkela</p>
    <p><b>Summary:</b> Privacy auditing empirically assesses privacy leakage by using membership inference attacks to establish lower bounds on privacy loss. We consider an observational auditing setting in which the auditor cannot insert canaries, control data inclusion, or retrain the target model, and must instead rely on fixed sets of known members and non-members. This setting is relevant for large deployed models or when retraining is restricted by computational or access constraints. In this case, non-members available for auditing may differ in distribution from the training data, causing membership-inference scores to be skewed due to the distribution shift. We address this problem by estimating the counterfactual in-distribution non-member score distribution using the available out-of-distribution (OOD) non-members. Our proposed method learns the relationship between data representations and membership-inference scores from OOD non-members and transports it to the target covariate distribution. Because this transport may become unreliable under extrapolation or imperfect conditional invariance, we further introduce a conservative correction calibrated directly to the nominal transported privacy level. We construct controlled calibration tasks from the available non-member data to estimate how representation-space displacement inflates the audit, and use this estimate to correct the transport-induced audit error. Across multiple datasets with distribution shifts, our method yields substantially more stable privacy estimates while retaining tighter lower bounds than baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.31246v1">Weaponizing the Exit: Input Privacy Leakage via Exit Routing Manipulation in Multi-Exit Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-22T13:26:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yulong Tian, Lei Wang, Jincan Yang, Hao Wu, Hao Han, Fengyuan Xu, Sheng Zhong</p>
    <p><b>Summary:</b> Multi-exit networks improve inference efficiency by allowing inputs to terminate early at intermediate exits. We identify a privacy vulnerability in cloud deployments of these networks: a malicious Cloud Service Provider (CSP) can infer sensitive properties of individual user inputs solely from inference latency, without accessing inputs, intermediate states, or model outputs. The attack exploits the CSP's control over the model supply chain. Prior to deployment, the CSP supplies a specially crafted multi-exit network manipulated so that inputs carrying a target sensitive property are routed to a designated exit with high probability, while other inputs exit elsewhere. At serving time, the CSP infers the exit index from per-query latency, thereby determining whether each input possesses the target property without accessing inputs, outputs, or internal model states. We propose a training framework combining selective label smoothing and entropy-covariance optimization to control confidence distributions across exits and reduce premature termination. We conduct experiments on four datasets across ten target properties. The results demonstrate strong attack effectiveness and stealthiness. The attack achieves an average F1 score of 0.73, compared to 0.25 for the strongest baseline, while main task accuracy drops by less than 1.3\% and inference speedup degradation remains below 0.1 in most settings. Our code is available at https://github.com/kazefjj/Weaponizing_the_Exit.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.30439v1">Not Where You Think: Protecting Location Privacy Against Reasoning-Based Geolocation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-21T20:49:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shanghao Shi, Jian Xiao, Hao Li, Yuanhaur Chang, Yevgeniy Vorobeychik, Nathan Jacobs, Neal Patwari, Ning Zhang</p>
    <p><b>Summary:</b> Recent large reasoning models can infer where ordinary photos were taken using only visual information, creating a serious location privacy risk even when metadata and obvious geographic identifiers are removed. To understand the mechanism behind such fine-grained localization, we develop GeoTrace, a structured reasoning attack that exposes how models extract location-relevant visual clues and compose them through coarse-to-fine geographic reasoning. We evaluate GeoTrace on a worldwide benchmark of 525 ordinary images spanning natural, urban, residential, and human-centered scenes while excluding famous landmarks and direct location indicators. Our results show that GeoTrace localizes 25.71% of images within 1 km with Gemini-3-Flash and 16.95% with GPT-5-mini. More importantly, our analysis reveals a key insight in the visual clue chain: broad scene properties mainly support coarse localization, whereas precise localization disproportionately relies on small, distinctive, and editable local clues. Building on this insight, we develop GeoShift, a proactive user-side defense that breaks the visual clue chain before image release. Rather than simply removing geographic evidence, GeoShift preserves stable scene properties, selects a visually compatible false target location, and strategically rewrites high-impact geo-revealing clues to construct a coherent alternative geographic hypothesis. Experiments show that GeoShift reduces street-level localization from 16.95% to 2.48% under GPT-5-mini and from 25.71% to 3.81% under Gemini-3-Flash, while preserving visual quality and remaining effective against adaptive attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.30229v1">Automated screening of privacy risks in medical AI</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-21T17:52:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Konstantinos Vrettos, Eleftherios Tzanis, Haridimos Kondylakis, Evangelia E. Vassalou, Florence X. Doo, Michail E. Klontzas</p>
    <p><b>Summary:</b> Medical artificial intelligence (AI) models are often shared without their training data, assuming this protects the patients who contributed them. However, a model can reveal whether a patient's records were used in training, a privacy breach known as a membership inference attack. This risk is usually reported as a cohort average, which can appear negligible while individual patients are almost certainly exposed. Identifying potentially vulnerable records before developing a production model could make privacy assessment more practical. We measured each patient's vulnerability to membership inference attack, across 7,789 models trained on six clinical datasets in four modalities, including two adapted pretrained medical models. Training choices changed how many patients had high attack scores, but the patients who ranked highest by risk largely stayed the same across the configurations we tested. Stronger weight decay reduced the exposed cohort up to threefold, yet largely the same patients remained most at risk across training recipes, architectures and initializations, including foundation models. Therefore, we developed a lightweight screening tool that uses four small models to identify patients with high risk of exposure before production-model training. We also assessed if flagged patients could be protected without removing their data. Privacy screening should become incorporated into data preparation for clinical AI.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.29987v1">GhostFaceMPC: Privacy-Preserving Face Recognition with Multi-Party Computation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-21T16:28:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Davide Carnemolla, Dario Catalano, Mario Di Raimondo</p>
    <p><b>Summary:</b> Facial recognition has become central to modern authentication systems, security frameworks, and personalized services. However, its widespread adoption is hindered by severe privacy risks, particularly surrounding unauthorized access to sensitive biometric data. To address these challenges, this paper presents GhostFaceMPC, the first end-to-end, privacy-preserving face recognition system to evaluate a deep convolutional neural network extractor and matching under secure multi-party computation. GhostFaceMPC enables secure processing of facial data across all stages of a face recognition process, from feature extraction and storage to matching, without exposing raw images or biometric embeddings at any stage. We introduce a multi-party computation-friendly quantization of the GhostFaceNet model and circuit optimizations that make face recognition under multi-party computation practical. The code is available at https://github.com/crypto-unict/GhostFaceMPC.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.29929v4">Privacy Preference Controls for Agentic Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-10-21T16:03:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shreya Kochar, Peeranat Sugsavanvit, Vidur Gupta, Joseph A. Calandrino, Deepak Kumar, Brett Frischmann, Sebastian Zimmeck</p>
    <p><b>Summary:</b> In response to vast and widespread online tracking, regulators and technologists alike have worked to develop laws and tools that allow people to express their privacy preferences. These measures seek to offer users greater control over the sale and sharing of personal information, putting agency in their hands to protect their privacy. However, the web is undergoing a seismic shift, away from strictly user-driven behavior towards agentic behavior, where AI agents take autonomous actions on behalf of users. In this study, we ask: What should privacy preference controls look like in the agentic web and agentic systems more generally? To answer this question, we develop a taxonomy of enforceable privacy preferences for agentic systems. Our taxonomy is informed both by laws and empirical studies of existing privacy tools as well as an audit of 30 leading AI assistants and agent platforms. To explore how our taxonomy can be implemented, we design and develop eight open-source prototypes that mirror real-world agentic applications and demonstrate how major aspects of our taxonomy can be structurally integrated in agentic protocols, such as the Model Context Protocol and Agent2Agent protocol. Ultimately, our study seeks to provide the groundwork for ensuring end-user privacy and autonomy is not lost in the newly arriving agentic world.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.29925v1">Privacy in Context Is Being Overlooked in the Age of General-Purpose LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-10-21T16:01:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Prakhar Ganesh, Yash More, Marco Romanelli, Ferdinando Fioretto, Golnoosh Farnadi</p>
    <p><b>Summary:</b> As large language models (LLMs) continue to grow in scope and capability, privacy concerns are on the rise. Since users increasingly interact with a single general-purpose system across many distinct contexts, there is a natural tendency to pursue a one-size-fits-all solution to privacy. Unfortunately, this overlooks a crucial insight from decades of privacy research: privacy is inherently contextual. In this paper, we argue that existing work in prompt privacy is drifting towards attempts to design a unified framework, which is highly misleading and can foster a false sense of security. Furthermore, we argue that even future work in this direction needs to wrestle with fundamental tensions across various desirable properties of prompt privacy. Thus, such continued attempts towards a unified framework need to be reconsidered. We recommend three critical paths forward: application-specific deployment of LLMs, context-specific evaluation of privacy frameworks, and better privacy literacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.29772v1">Location-of-interest vs. Current-location Privacy in Multi-hop Communication</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-21T14:03:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ryan Vogt, Ioanis Nikolaidis, Mario A. Nascimento</p>
    <p><b>Summary:</b> Consider a standard multi-hop wireless radio network in which nodes relay messages for one another. While the contents of messages may be sensitive and thus encrypted, the very fact that two radios communicated can leak sensitive information about both the physical location of the origin and the physical location of the destination. We investigate the trade-off between protecting the privacy of a user's current location and the privacy of their location of interest, and how the user should choose dummy destinations to obfuscate their queries.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.29756v1">The Privacy Paradox Is a Misnomer: Data Under Structural Uncertainty</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-10-21T13:58:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ignacio Cofone</p>
    <p><b>Summary:</b> The infamous privacy paradox refers to the apparent inconsistency between people's stated concern for privacy and their readiness to disclose personal information. This phenomenon has sparked two largely disconnected literatures: one offering experimental evidence of inconsistent behavior, and another providing qualitative accounts and defending the importance of privacy. The Article presents an online field experiment that bridges those literatures and shows that the so-called paradox arises from a mischaracterization of the underlying behavior. The Article finds that it is structural uncertainty about risk that drives seemingly paradoxical privacy decisions. It does so by isolating discounting mechanisms and empirically testing whether observed privacy choices reflect temptation or rational responses to uncertainty. The results suggest that privacy behavior is not paradoxical but, rather, consistent with choices shaped by incomplete information. The Article then discusses the policy implications of this reframing. As privacy decisions stem from structural uncertainty, which operates as a market failure, regulation should aim to reduce that uncertainty. This supports regulation that prioritizes transparency (for people to assess the risks of data collection) and flexibility mechanisms that accommodate evolving contexts. Such reframing provides a new argument for the right to be forgotten, which allows people to revisit prior disclosures as new risks become apparent. By shifting the focus from individual inconsistency to structural uncertainty, the findings call for privacy law to better reflect the reality of people's decision-making environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.28991v1">Diffusion Sensitivity Geometry and Strong Duality for Optimal Privacy-Utility Tradeoffs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-20T23:37:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tue Do, Daniel Alabi</p>
    <p><b>Summary:</b> Existing approaches to differential privacy in diffusion models rely on loose sensitivity bounds and isotropic Gaussian noise, leading to unnecessary estimation error. We develop a framework for the optimal privacy-utility tradeoff of ideal diffusion denoisers, replacing conservative bounds with exact sensitivity characterizations and provably optimal noise calibration. First, we show that worst-case sensitivity over datasets of arbitrary size can be characterized exactly using only two records. For a data domain of size $m$, this reduces the analysis to at most $m(m-1)$ constraints, regardless of dataset size. Our characterization can be arbitrarily tighter than conventional diameter-based sensitivity bounds, revealing potentially unbounded improvements in noise calibration. Second, we obtain exact privacy guarantees for Rényi, approximate, and Gaussian differential privacy, as well as mutual-information privacy for binary records, avoiding the looseness of previous generic privacy conversions. Finally, we show that the minimum achievable weighted mean-squared error can be computed through a semidefinite program and prove strong duality, providing certificates of global optimality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.28835v1">Conditional Imaging for Privacy-Preserving Visual Sensing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> 
  <p><b>Published on:</b> 2026-10-20T19:02:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hengyu Lian, Debabrata Mandal, Anzhou Wen, Yujie Wang, Xi Peng, Praneeth Chakravarthula</p>
    <p><b>Summary:</b> Conventional visual sensing faces a fundamental dilemma: information that should remain private today may need to be recovered tomorrow. This challenge is becoming increasingly important as cameras become pervasive in our daily surroundings. Existing safeguards either protect visual content only after an image is formed or suppress information during capture in ways that prevent its later recovery. Here, we show through an information-theoretic analysis that privacy and recoverability cannot be achieved simultaneously in static optical systems. Information preserved in a measurement for later reconstruction also remains available to an observer of that measurement, limiting the privacy such systems can provide. To overcome this limitation, we introduce conditional imaging, an imaging approach that changes the optical state for every captured frame. The measurement alone conceals the scene, while knowledge of the corresponding physical system state enables its reconstruction. We analyze how the optical parameters determine the information that can be recovered and use this analysis to guide the design of a camera prototype. We evaluate the system on a captured dataset of human faces using increasingly powerful attempts to recover the scene, from direct visualization and computational inversion to learned reconstruction and identity recognition. Our experiments show that conditional imaging preserves identity in authorized reconstructions while withholding visual information from observers without access to the system state. By making the physical state of the camera part of the information needed for reconstruction, conditional imaging enables visual information to be protected at the point of capture while remaining recoverable for future authorized use.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.28315v2">Disclosure Begets Disclosure: A Self-Reinforcing Privacy Loop in LLM Agents with Persistent Memory</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-20T14:52:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Masahiro Kaneko, Hiromi Arai, Timothy Baldwin</p>
    <p><b>Summary:</b> Large language model (LLM) agents increasingly use persistent memory to personalize responses, and personal attributes in this memory pose a privacy risk if exposed. We ask how consulting memory during dialogue changes what users go on to say, and thus what the memory comes to reveal. In multi-session simulations, a simulated user with 24 personal attributes talks with a support agent that does or does not consult memory, and in both settings attributes are inferred from the full accumulated record. Across four support models, memory raises response quality but also empirical leakage, the share of attribute values correctly inferred from the record, by a margin that widens over sessions. The cause is a loop in ordinary, non-adversarial assistance. Memory-conditioned responses carry earlier values forward, often as presuppositions, and users affirm them or leave them uncorrected, so that cues and the agent's own guesses become recorded values. The loop reinforces itself, and removing the agent's mentions of an attribute lowers its later disclosure about twice as much as single-turn effects predict. Users cannot leave it on their own, since correcting a value discloses the attribute, declining to discuss it shifts later predictions toward sensitive values, and incorrect values left in place become entrenched. The loop is best weakened at the agent's response. Instructing the agent not to state or presuppose attributes brings leakage to about the no-memory level while keeping most of the quality gains, whereas filtering or anonymizing what users say or what is stored gives up much of them.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.28153v1">Lower bounds for Bayesian CVaR in interactive problems with local differential privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-10-20T12:57:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Raghav Bongole, Amirreza Zamani, Tobias J. Oechtering, Mikael Skoglund</p>
    <p><b>Summary:</b> We develop an information-theoretic method for lower bounding the prior-predictive conditional value-at-risk (CVaR) of loss in interactive statistical decision making (ISDM). A generalized Fano inequality replaces a single error event by a randomized binary statistic constructed from a bounded transform of the loss, reducing the problem to a Bernoulli $f$-divergence inequality. A bounded hinge transform yields a direct lower bound on Bayesian CVaR under a prior fixed in advance. We derive reverse-KL specializations and obtain explicit bounds for Gaussian mean estimation and Gaussian stochastic bandits. We then impose local differential privacy (LDP) at the observation stage of the same ISDM model. LDP contraction inequalities combined with the adaptive KL chain rule give explicit Bayesian CVaR lower bounds for Gaussian mean estimation with heterogeneous privacy parameters and Gaussian $K$-armed bandits.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.27982v1">Beyond the Frame: Redundancy, Not Trajectory, Carries the Privacy Leak in Video Unlearning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-10-20T10:24:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kavyansh Tyagi, Paolo Russo</p>
    <p><b>Summary:</b> Class unlearning for video segmentation aims to ensure that a removed category cannot be reconstructed from a deployed model's outputs. Current leakage evaluation algorithms inspect one frame at a time, and we show that this understates leakage by a wide margin: an attacker that averages a model's output field over a two-second clip recovers the forgotten class from every method we evaluate on VSPW and most on Virtual KITTI~2, including models whose per-frame predictions are visually indistinguishable from a retrain oracle (a model trained from scratch without the forgotten class). We attribute the recoverable signal to cross-frame redundancy rather than object trajectory, establish this with a time-shuffled control that leaves leakage intact, and introduce PACE, an unlearning method that suppresses redundancy directly using an exactly permutation-invariant pooled adversarial discriminator and a two-sided temporal consistency objective. Across VSPW and Virtual KITTI~2, PACE lowers pooled attacker AP to $18.79$ (\texttt{person}) and $12.10$ (\texttt{car}) on VSPW and $9.11$ (\texttt{car}) on Virtual KITTI~2, achieving on the latter the strongest suppression among verdict-safe methods retaining usable utility, while retaining $19.8$ mIoU on VSPW \texttt{car} against at most $8.3$ for any baseline achieving comparable erasure.</p>
  </details>
</div>



<h2>2026-11</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.16637v1">The Unseen Threat: How Complementary Combinations of Acoustic Features Compromise Speech Privacy</a></h3>
  
  <p><b>Published on:</b> 2026-11-12T11:12:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jule Pohlhausen, Jörg Bitzer</p>
    <p><b>Summary:</b> The interaction of acoustic features in leaking private information remains underexplored. This work focuses on time-domain features, i.e., broadband RMS level and pitch, alone and combined with temporally smoothed and subsampled Mel spectrograms. Privacy is assessed using informed automatic speech recognition and speaker-verification attacks, while utility for conversational analysis is evaluated using voice activity detection and speaker diarisation. RMS level and pitch alone exposed limited information, but fusion with 500 ms-smoothed Mel spectrograms enhanced utility while substantially increasing speech-content leakage. Specifically, the combination with RMS level showed that fine-grained temporal dynamics can amplify leakage from coarsely sampled spectral features. Speaker-identity protection remained limited for all tested features. Overall, these findings indicate that privacy assessments performed on individual acoustic features may underestimate leakage after feature fusion.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.16483v1">Privacy-Preserving Range Counting over Local Graph Statistics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2026-11-12T08:53:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gengda Zhao, Yizhang He, Dong Wen, Kai Wang, Ruijia Wu, Jianwei Wang</p>
    <p><b>Summary:</b> Range counting over vertex statistics supports contact analysis, community profiling, and reputation screening. However, releasing exact range counts can disclose sensitive edges to an adversary with background knowledge. We study this problem under edge local differential privacy (edge LDP), where each vertex randomizes its report before sending it to an untrusted curator. We develop a layered framework that connects statistic estimation, direct range estimation, and adaptive estimator selection. Statistic-estimation methods provide complementary scalar estimators with explicit loss analyses, while indicator-estimation methods privatize range indicators directly. We next propose Bounded Conditional Range Inversion (BCRI), which derives unbiased range estimates from reusable bounded geometric reports through an explicit local inverse. Its boundary-conditioned estimator achieves no larger expected L2 loss than the unbounded inverse, and histogram preprocessing supports constant-time queries. The same reports also provide a nonnegative, unbiased variance estimate for every answer. At the center of the framework, Adaptive Estimator Selection (AES) privately predicts bias, variance, and covariance to combine BCRI with a conditional estimator from the same transcript. Experiments on diverse real-world graph tasks demonstrate the accuracy, efficiency, and workload scalability of the proposed framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.16065v1">Tokenized Reward Systems for Federated Learning: The Privacy vs. Fairness Tradeoff</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-11-11T22:21:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Andreas Sendros, Nikolaos Pavlidis, Vasilios Perifanis, Pavlos S. Efraimidis</p>
    <p><b>Summary:</b> Federated learning (FL) systems increasingly rely on blockchain based reward mechanisms to incentivize participation while preserving data privacy. We design and empirically evaluate two complementary Solidity smart contracts for FL reward distribution: the first one that allocates rewards proportionally to a publicly disclosed quality score, and a privacy preserving variant that hides individual quality scores behind a zero-knowledge (ZK) proof of a threshold condition. Both contracts mint a non transferable, use-and-burn token maintaining a trustless incentive structure. We evaluate the two designs through MNIST training with adversarial behavior, including Sybil attacks, zero gradient and random noise, across three independent random seeds.
  Our results reveal a fundamental tradeoff between cryptographic privacy and incentive fairness. The privacy preserving architecture strictly degrades system robustness, doubling the adversary's average reward capture while introducing severe outcome variance. This vulnerability is driven by a structural self-inclusion bias within cosine-similarity scoring: as the global model converges, legitimate gradient updates naturally diminish, rendering them statistically indistinguishable from bounded noise. Adversaries exploit this dynamic to systematically breach the ZK threshold, triggering a late stage failure cascade that culminates in absolute adversary monopoly over the reward pool and the total exclusion of honest contributors. Alongside a closed-form theorem formalizing this privacy--Sybil resistance tradeoff, we map strict mainnet deployment boundaries via linear gas scaling models, explicitly incorporating the post-Fusaka EIP-7825 per transaction gas cap. Ultimately, while cryptographically secure, static threshold ZK gates fail as incentive layer fairness mechanisms under realistic FL convergence dynamics on standard benchmarks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.16048v1">Privacy Leakage from Recurrent State in LLM Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-11-11T21:57:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Weimin Fu, Shikun Liu, Qiying Li, Yuntao Liu, Pan Li, Xiaolong Guo</p>
    <p><b>Summary:</b> Personalized LLM services place private facts and application instructions into a prompt, then retain representations of that context for later inference. Latent-state LLMs compress part of this history into fixed-size recurrent state. The information preserved by its learned updates is implicit, and later computation can expose it even when an observer receives neither the private text nor the responses. We investigate privacy leakage from recurrent state through partial-state probing and physical observation of its use. Our methodology separates recoverable information, persistence through public dialogue, causal influence on later decisions, and leakage through power. Experiments with released hybrid implementations show that a small state observation supports multiple predictions about private facts and response rules, and that personal attributes generalize to unseen authors. The information remains inferable after public dialogue and changes later decision margins. Complete-read power recovers private facts under a fixed execution schedule. On a partitioned GPU, an unprivileged account infers age from whole-device power during public requests; a separate state-isolation experiment establishes the recurrent contribution to this channel. These findings extend context confidentiality to the lifetime and execution of retained state. They identify access-control responsibilities for serving systems, telemetry restrictions for GPU operators, and data-dependent power leakage for accelerator designers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.15770v1">Privacy-Preserving Spectrum Data Obfuscation in Next-Generation Spectrum Coexistence Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2026-11-11T17:49:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yalin E. Sagduyu, Tugba Erpek, Sastry Kompella, Joseph A. Molnar</p>
    <p><b>Summary:</b> In spectrum coexistence systems, the primary user (PU) activity must be partially disclosed for interference avoidance and coordination, while the exact spectrum occupancy information is often restricted due to security and regulatory constraints. To this end, subset-based disclosures can be employed in which the true frequency is included while ambiguity is introduced. This paper shows that naive randomized subset disclosures remain highly vulnerable to information leakage through inference, as temporal structure can be exploited to recover spectrum usage information. Under Markovian dynamics of the PU's spectrum usage, hidden Markov model (HMM) filtering with online learning is applied, while under periodic dynamics, period and phase estimations with phase-aligned statistics are used for inference. To address this vulnerability, structure-aware obfuscation strategies are introduced. For Markovian dynamics, history-based and belief-based schemes are designed to induce model mismatch and limit posterior concentration, while for periodic dynamics, cycle-dominance and decoy-based schemes are designed to manipulate phase-wise statistics and bias the inference process. These obfuscation schemes significantly hinder inference of spectrum information and offer principled disclosure solutions for spectrum coexistence systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.15097v1">GuardianAgentFlow: Multi-Agent Coordination for Web Privacy Protection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2026-11-11T06:19:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruiyi Yang, Gayathri Lihinikaduarachchi, Rahat Masood, Flora D. Salim, Salil S. Kanhere</p>
    <p><b>Summary:</b> Web agents need to use private context without unnecessarily disclosing it. Effective protection must distinguish between requests that may be sent after sanitization and those that must be withheld, while preserving the information needed for authorized tasks. We present GuardianAgentFlow, a multi-agent framework that mediates outgoing Web requests through an explicit release contract. A dedicated restriction check grounds permission in the user's instruction; a shared protection scope aligns rewriting with disclosure checking; and candidate-grounded feedback guides revision before transmission. Experiments on Web requests with human-reviewed intent labels show improved request-contract success, while controlled comparisons and role ablations identify the contributions of restriction handling, policy evidence, and candidate checking. Evaluations of action proposals from PrivacyLens and AgentDAM demonstrate complementary protection when mediation is composed with privacy-aware agents. Experiments with smaller mediation models show that the coordination benefit persists with reduced model capacity. Dedicated-server measurements show lower mediation latency than full-policy reasoning, while real-site browser tests quantify integration overhead.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.14254v1">Location Matters: Sparse Latent-Variance Attacks for Face Privacy against Diffusion Personalization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-11-10T16:03:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuting Yang, Shuxin Li, Linyan Dai, Xinwei Zhang, Dong Huang, Renyang Liu, See-Kiong Ng</p>
    <p><b>Summary:</b> Text-to-image diffusion models can learn and reproduce an individual's identity from only a few reference photos, creating risks of unauthorized and misleading content generation. Proactive defenses address this risk by adding adversarial perturbations to facial images before release, thereby disrupting identity acquisition during downstream personalization. However, existing methods typically rely on dense $L_\infty$-bounded perturbations, whose accumulated distortions can become visible around facial structures. Recent methods improve protected-image quality, but often at the cost of reduced protection effectiveness. In this paper, we propose Sparse Encoder Attack on Latent Variance (SEAL), a sparse adversarial protection framework that modifies only 5% of the spatial locations in a facial image. SEAL combines a differentiable top-k masking scheme that jointly optimizes perturbation locations and values with a variance-oriented objective over the frozen VAE encoder's latent distribution to disrupt identity-consistent representations. A saliency-guided dispersion penalty further discourages perturbation concentration in perceptually salient facial regions. Experiments on CelebA-HQ and VGGFace2 show that SEAL achieves the best protected-image quality among the compared methods, exceeding 41 dB PSNR with 0.97 SSIM and at most 0.07 LPIPS, while reducing identity similarity to at most 0.15 after diffusion personalization. These results demonstrate that sparse location optimization enables strong identity protection while preserving high visual quality. Code and data are available at https://github.com/Lvxan/SEAL</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.13997v1">Specify Privacy Yourself: Assessing Inference-Time Personalized Privacy Preservation Ability of Large Vision-Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-11-10T12:41:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xingqi Wang, Xiaoyuan Yi, Xing Xie, Jia Jia</p>
    <p><b>Summary:</b> Large Vision-Language Models (LVLMs) have demonstrated remarkable capabilities but raise significant privacy concerns due to their abilities to infer sensitive personal information from images with high precision. While current LVLMs are relatively well aligned to protect universal privacy, e.g., credit card data, we argue that privacy is inherently personalized and context-dependent. This work pivots towards a novel task: can LVLMs achieve Inference-Time Personalized Privacy Protection (ITP$^3$), allowing users to dynamically specify privacy boundaries through language specifications? To this end, we present SPY-Bench, the first systematic assessment of ITP$^3$ ability, which comprises (1) 32,700 unique samples with image-question pairs and personalized privacy instructions across 67 categories and 24 real-world scenarios, and (2) novel metrics grounded in user specifications and context awareness. Benchmarking the ITP$^3$ ability of 21 SOTA LVLMs, we reveal that: (i) most models, even the top-performing o4-mini, perform poorly, with only $\sim$24% compliance accuracy; (ii) they show quite limited contextual privacy understanding capability. Therefore, we implemented initial ITP$^3$ alignment methods, including a novel Noise Contrastive Alignment variant which achieves 96.88% accuracy while maintaining reasonable general performance. These results mark an initial step towards the ethical deployment of more controllable LVLMs. Code and data are available at https://github.com/achernarwang/specify-privacy-yourself</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.12570v1">Hidden in Plain Sight: Privacy-Enhanced Computing Through Register Renaming</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Hardware Architecture-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-11-09T15:31:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ahmed Nematallah, Stefanos Kaxiras</p>
    <p><b>Summary:</b> Privacy-Enhanced Computing (PEC) is a mechanism to hide program secrets from the outside world without paying the cost of fully-homomorphic encryption. Previous work has developed hardware mechanisms to achieve this goal but they require a dedicated processor enclave where all computations are done, requiring duplicate ALU resources and limiting the performance of PEC-utilizing applications due to not being able to access the full compute resources of the processor (e.g., multiple execution units and vector units), or not being able to execute PEC instructions in parallel and out-of-order.
  In this work, we introduce HPS-PEC (Hidden in Plain Sight PEC), a novel method of utilizing existing infrastructure in the CPU to achieve PEC with minor modifications to the architecture. We show that, across 25 VIP-Bench benchmarks and with a 7-cycle QARMA-64 cipher, HPS-PEC runs encrypted code at 3.41x the execution time of unprotected native code (geometric mean), of which 1.03x is the cost of data-oblivious code itself, and is 1.26x faster than a Sequestered Encryption (SE) unit while utilizing under a third of its dedicated area. Our method keeps plaintext out of reach of every instruction, as an enclave does given a correctly functioning renamer and register file, which every program already depends on.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.12367v1">An Agile Homomorphic Encryption and ML-KEM Scheme for Privacy-Preserving Health Data Processing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-11-09T13:14:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Daniel Resende, Nadia El Mrabet, Ulrich K{ü}hne</p>
    <p><b>Summary:</b> The storage and processing of health data raise serious privacy concerns; therefore, the data must be encrypted. Fully Homomorphic Encryption (FHE) allows computations on encrypted data, which makes it a very promising technology in this context. However, although the efficiency of FHE algorithms has improved in recent years, they remain very complex. The security of several prominent FHE schemes is based on variants of the Learning With Errors (LWE) problem, which is also the basis of Module-Lattice-Based Key-Encapsulation Mechanism (ML-KEM), the new post-quantum standard for asymmetric encryption. In this paper, we propose an agile cryptographic scheme -combining ML-KEM and BGV -that allows efficient implementations in an embedded use case. We describe the parameter selection for the proposed scheme and show its feasibility with a proof-of-concept implementation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.12064v1">A Privacy-Preserving UAV-Assisted Secure Wireless Communication and Computing System Based on Fully Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-11-09T08:39:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Quanxi Zhou, Wencan Mao, Ye Tao, Manabu Tsukada, Kensuke Fukuda, Yusheng Ji</p>
    <p><b>Summary:</b> With the advancement of beyond-5G networks, privacy-preserving communication and secure computation face critical challenges due to the openness of wireless channels. Existing security mechanisms protect data transmission but fail to secure the computation process itself. In this paper, we propose a UAV-assisted secure computing framework that integrates Cheon Kim Kim Song (CKKS) fully homomorphic encryption (FHE) with multi-party secure computation (MPC). Leveraging UAV flexibility, our framework decouples key distribution from encrypted computation, enabling secure encrypted weighted aggregation (EWA), encrypted matrix multiplication (EMM), and encrypted decision tree (EDT) inference. Experimental results show that our framework outperforms existing schemes: for EDT, it supports floating-point operations and achieves better time efficiency than Brakerski-Fan-Vercauteren (BFV); for EMM, it demonstrates superior time and space efficiency compared to Brakerski-Gentry-Vaikuntanathan (BGV) and Somewhat Homo- morphic Encryption (SHE); while for EWA, it ensures high numerical precision and robustness across varying data length.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.11567v1">Verifiable, Privacy-Preserving and Collaborative Multi-Objective Optimization with NSGA-II on Blockchain</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-11-08T19:29:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Goshgar Can Ismayilov</p>
    <p><b>Summary:</b> Collaborative multi-objective optimization allows independent problem solvers to contribute their solutions to a shared problem. However, their validity cannot be reliably verified in open settings if the parties are reluctant to disclose their solutions. Therefore, this paper proposes a novel zk-NSGA-II protocol for verifiable, privacy-preserving and collaborative multi-objective optimization on blockchain. To the best of our knowledge, this is the first work that executes Non-Dominated Sorting Genetic Algorithm II (NSGA-II) on the RISC Zero Zero-Knowledge Virtual Machine (zkVM) where evolutionary generations are certified by succinct proofs that are verified on-chain. Problem solvers maintain their own independent populations as the set of solutions in the decision space and their corresponding objective vectors in the objective space. They contribute to a global on-chain Pareto front by aggregating their local off-chain Pareto fronts according to the rule of non-domination which admits a contribution if it is non-dominated with respect to the existing contributions in the global front. To prevent fabricated contributions, population states across generations are linked through hash chains. The correctness of the zk-NSGA-II protocol is first evaluated on twelve problems from the ZDT and DTLZ benchmarks. Second, its feasibility is shown in a real-world portfolio optimization case study with the Hang Seng dataset. Performance on these problems is measured with nine different metrics across three complementary perspectives for optimization, zero-knowledge proof and blockchain. The empirical findings indicate that trustless collaborative multi-objective optimization is feasible with the existing zero-knowledge and blockchain technologies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.11564v1">From Sound to Occupancy: Privacy-Aware Audio Sensing for Buildings</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-11-08T19:11:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Myeongwon Chae, Seonghyuk Son</p>
    <p><b>Summary:</b> Occupancy-based controls regulate lighting and HVAC according to whether a space is in use. Passive infrared (PIR) sensors, the most common choice, respond to motion and can report an occupied room as vacant when its occupants remain still. Sound offers an alternative cue, since seated occupants type, turn pages and cough, but microphones raise privacy concerns. We therefore study a two-stage design: an on-device encoder maps each second of audio to a short embedding, and a server-side temporal model turns the stream of embeddings into an occupancy state. To our knowledge, no publicly available dataset pairs office audio with occupancy labels, so we evaluate the two stages separately on public data. The encoder is trained on synthetic scenes that mix empty-room recordings, room impulse responses, office sounds and read speech, and tested on unseen rooms, recordings and speakers for whether a second contains a sound made by a person. On 11 real office recordings (DCASE 2013) it reaches an AUC of 0.87, against 0.76 for log-mel statistics. Attacks on the transmitted embeddings recover at most 1% of the spoken words, against 94% from log-mel frames, but still identify the speaker among 40 in 69 to 77% of the utterances. Noise-floor normalization with adversarial training, an 8-dimensional embedding, or sending only class probabilities lowers this to 38 to 55% without hurting detection. On HPDmobile, which pairs home occupancy labels with an amplitude envelope of the audio, a causal temporal model pretrained with a hierarchical contrastive loss matches hand-crafted features (AUC 0.75) and does better when only one labelled day per home is available. These results make the two-stage design a practical basis for privacy-aware acoustic occupancy sensing, with speaker identity as the one leak still to close.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.11467v3">PLDP-IDS: Personalized Local Differential Privacy for Infinite Data Stream</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2026-11-08T16:00:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Leilei Du, Yikun Hu, Xu Zhou, Yang Cao, Peng Cheng, Wangze Ni, Kenli Li</p>
    <p><b>Summary:</b> Existing $w$-event local differential privacy (LDP) mechanisms for streaming data impose a uniform privacy window and budget, forcing all users to adopt the most stringent privacy requirement. We study personalized continual frequency estimation under LDP, where each user specifies her own window size and privacy budget, and identify two challenges. First, a single sampling size cannot balance sampling and perturbation errors for privacy groups with heterogeneous requirements. Second, borrowing estimates from groups with larger budgets reduces variance but introduces bias when privacy preferences correlate with the data. We first propose Optimal Population Selection (OPS) and two OPS-guided mechanisms, PLPD and PLPA, which use one privacy-compatible sampling size for all users. Since one size cannot fit all groups and pooling their estimates is biased under privacy--data correlation, we further develop PLPD$^+$ and PLPA$^+$, which combine group-aware population scheduling with bias-aware cross-group fusion while preserving personalized $w$-event LDP. Experiments on real-world and synthetic streams show that, compared with the direct personalized extension of LDP-IDS, PLPA$^+$ reduces the average mean squared error (AMSE) by 52.3\% and 40.8\% on average, respectively, and remains 4.3--5.1$\times$ more accurate than PLPA under strong privacy--data correlation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.11273v1">Task-adaptive anonymisation enables privacy-preserving sharing of clinical speech data</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-11-08T09:57:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ziyun Cui, Haoyu Niu, Wen Wu, Hao Sun, Sihan Zhang, Chang Lei, Yun Zhang, Chunyun Sun, Yang Luo, Liangliang Cao, Ji Wu, Runsen Chen, Lian Zhou, Yongsheng Tong, Chao Zhang</p>
    <p><b>Summary:</b> Clinical speech is increasingly used for disease screening and clinical assessment, but directly distributing speech recordings poses privacy risks because they contain both speaker-identifying voiceprints and sensitive spoken content. Existing speech anonymisation approaches are primarily developed for general speech applications or task-specific clinical speech and overlook that different clinical tasks rely on distinct speech characteristics, necessitating task-adaptive anonymisation strategies to protect patient privacy while preserving clinical utility. Here we introduce CASA, a clinically adaptive speech anonymisation agent that transforms anonymisation from a fixed processing procedure into a task-guided optimisation process, dynamically tailoring voiceprint and content anonymisation to task-specific privacy and clinical utility requirements. Through recursive self-improvement (RSI), CASA iteratively evaluates and refines anonymisation strategies against task-specific privacy and clinical utility requirements, while learning from these outcomes to guide more efficient planning in subsequent clinical tasks. CASA is validated across 14 clinical tasks encompassing five languages, diverse elicitation paradigms, and mental health, cognitive and voice disorders. CASA preserved disease-related classification performance while meeting speaker-anonymisation requirements across all clinical tasks, versus only 8/14 for the strongest fixed method. Assessments of resistance to speaker re-identification by external attackers and identification and redaction of sensitive personal information in clinical speech further demonstrated CASA's dual protection of speaker identity and sensitive spoken content. Clinical expert assessments further supported the preservation of clinically relevant information and the acceptability of anonymised speech for controlled research sharing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.10898v1">Optimal Byzantine-resilient Federated Learning with User-level Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E">
  <p><b>Published on:</b> 2026-11-07T18:43:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ming Xiang, Stratis Ioannidis, Edmund Yeh, Carlee Joe-Wong, Lili Su</p>
    <p><b>Summary:</b> Real-world deployment of federated learning (FL) requires resilience against adversarial clients and data privacy. Byzantine fault captures the worst-case behavior of adversarial clients, while differential privacy (DP) provides statistical guarantees against privacy loss. In particular, user-level DP guards a client's entire contribution and provides more realistic protection against information leakage. Despite intensive efforts, the minimax-optimal convergence bound of Byzantine-resilient FL with user-level DP remains open. We establish an information-theoretic lower bound for any Byzantine-resilient empirical risk minimization problem under user-level DP and heterogeneous clients. We propose ByzULDP, a central DP algorithm featuring a two-level momentum across the client and server. Client-side momentum mitigates stochastic gradient variance during robust aggregation. Unlike the fault-free case, naively combining non-linear Byzantine-resilient aggregation with central DP noise can be insufficient to guarantee convergence to a bounded neighborhood of a stationary point. Our key contribution is a server-side momentum that leverages a property specific to user-level DP, where privacy sensitivity depends on how client updates are constructed, to empower convergence. ByzULDP achieves the order-optimal convergence bound for strongly-convex objectives, with vanishing error terms decaying at the optimal $O(1/T)$ and $O(1/\sqrt{T})$ rates for strongly-convex and non-convex objectives, respectively. We corroborate our analysis with numerical experiments on real-world datasets across diverse privacy budgets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.10804v1">DICOMPUTE: An Economic and Privacy-Aware Framework for Distributed Artificial Intelligence Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-11-07T15:36:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Atul Khekade, Ritesh Kakkad, Anil Chinchawale, Omkar Mestry, Behnam Mohammadkhani</p>
    <p><b>Summary:</b> The prevailing design of large-scale artificial intelligence inference concentrates accelerators, model weights, and request processing in centralized computing facilities. Centralization offers important benefits in accelerator utilization, high-bandwidth interconnects, operational control, and serving efficiency. Yet centralized infrastructure is not always the least-cost or most governance-compatible choice for every inference workload. This paper develops a research framework for DICOMPUTE, a heterogeneous distributed inference architecture in which policy-constrained scheduling can allocate suitable requests across privately controlled, regional, and independently operated computing resources. We derive a full-cost comparison that accounts for capital amortization, energy, network transfer, orchestration, utilization, failures, and trust-related expenses; characterize conditions under which distributed inference can outperform centralized alternatives; and specify a privacy model separating data residency, transport confidentiality, execution confidentiality, and verifiable accounting. We propose falsifiable hypotheses and a reproducible experimental design, without presenting simulated examples as measured performance. Our central conclusion is conditional: distributed inference is most promising for divisible, latency-tolerant or locality-sensitive workloads on underutilized compatible hardware, while centralized clusters retain structural advantages for tightly coupled, memory-intensive, high-throughput inference. The framework is intended to support rigorous evaluation rather than to assert universal superiority.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.12960v1">IIT Patna at "ICPR 2026 TVRID Competition on Privacy-Preserving Person Re-Identification from Top-View RGB-Depth Camera"</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-11-07T09:22:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abhinav Kumar, Swagatam Pati, Advait Deshmukh, Aditya Mehrotra, Bibek Das, Kumari Priya, Utsav Kumar Nareti, Saba Akram, Chandranath Adak</p>
    <p><b>Summary:</b> Privacy-aware person re-identification (Re-ID) from top-view cameras replaces frontal appearance with anthropometric shape, while depth sensing further reduces color-based identity cues. The ICPR 2026 TVRID competition evaluates this setting using 86 identities captured by four synchronized Intel RealSense D455 cameras with RGB and Depth streams across flat, ascent, descent, and oblique viewpoints. Performance is measured using mAP and CMC@1 across within-camera in/out, ascent-descent, and flat-oblique scenarios. The competition had 147 registered participants and 33 final submissions. Three teams from IIT Patna participated: 'abhinavkumar03' and 'sjkdgfhl_' ranked 5th and 7th among 31 ranked participants, and 'vivek katuri' reached 77.67% CMC@1 / 85.20% mAP on the RGB track. This paper presents the methods of the two top-10 teams. Methodology 1 (abhinavkumar03) achieves 93.51% mAP and 90.42% CMC@1 on Depth, ranking 4th of 28, while Methodology 2 (sjkdgfhl_) reaches 99.63%/99.35% on RGB and 86.26%/80.34% on Depth. Both substantially outperform the 57.19% track-average Depth mAP, with Methodology 1 yielding a 7.3-point gain over Methodology 2. These results demonstrate the importance of depth representation and supervision for privacy-preserving Re-ID.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.10578v1">EgoVeil: Personalized Privacy Reasoning for Egocentric Video</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-11-07T08:35:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xue Wang, Yang Zhang</p>
    <p><b>Summary:</b> Recent advances in vision-language models (VLMs) enable AI systems to interpret egocentric video. Yet continuous visual capture raises privacy concerns because sensitive content is pervasive and varies across users and contexts. We present EgoVeil, a personalized privacy reasoning system that determines which visual content to obscure based on individual preferences while retaining context useful for downstream assistance. It converts localized visual regions into structured semantic observations and combines a privacy reasoner with an explicit user-specific memory for personalized privacy reasoning. This design supports personalization and continual adaptation as preference evidence accumulates. We evaluate on in-the-wild data from 10 smart-glasses users under a cross-user chronological protocol. EgoVeil achieves 91.93% balanced accuracy and 84.42% Mask recall, outperforming direct VLM baselines and other controlled privacy reasoning baselines. Our results show that personalized, adaptive privacy reasoning better aligns privacy preservation with individual preferences while retaining the visual context needed for effective smart-glasses assistance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.10528v1">PrivMark: Pixel-Space Steering against Privacy Leakage in Vision-Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-11-07T06:58:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruofan Xing, Arman Akbari, Weikai Lin, Yuhao Zhu, Xuan Zhang</p>
    <p><b>Summary:</b> Vision-language models (VLMs) routinely disclose soft-biometric attributes such as age, gender, and race in their text outputs, exposing demographic information from uploaded images to any downstream API user. Existing privacy defenses do not fit this setting: face de-identification leaves distributed soft-biometric cues intact, classifier-targeted adversarial perturbations do not transfer to open-ended generation, and stronger VLM-specific methods require retraining or runtime activation access unavailable to downstream APIs. We propose PrivMark, a framework that suppresses biometric leakage at the image level. By analyzing VLM activations, we identify two weakly aligned steering vector directions in hidden-state space, each tied to a distinct leakage behavior --- one corresponding to incidental attribute disclosure under open-ended descriptions, the other to compliance with direct biometric probes instead of refusal --- and encode both directions into a single bounded pixel perturbation, so the protected image alone enforces privacy with no invasive access to model internals at deployment. To support evaluation, we assemble BioleakBench, $1{,}600$ VQA pairs covering biometric privacy attributes under both free-form description and direct-probe protocols. Across three white-box source models, PrivMark achieves up to $85.9\%$ biometric suppression while retaining $75\%$ of clean OK-VQA utility, up to $1.4\times$ the privacy-utility tradeoff of the strongest pixel-only baseline. The same one-shot perturbations transfer consistently to seven unseen VLMs including closed-source APIs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.10185v1">GSynPEF: A Privacy Evaluation Framework for Synthetic Graphs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B">
  <p><b>Published on:</b> 2026-11-06T20:04:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yu Duan, Luca Baldesi, Carter T. Butts, Athina Markopoulou</p>
    <p><b>Summary:</b> It is often desirable to generate and release synthetic graphs, which resemble real-world data, in a privacy-preserving way. While substantial progress has been made in designing private graph synthesizers (PGS), opportunities remain for more explicit connections between synthesizer models and privacy evaluation, and better accounting for output variation. This paper proposes GSynPEF, a practical framework for empirical evaluation of privacy and utility in settings for which a real-world graph is given as input and output synthetic graph(s) are observed. Our framework links a broad class of graph synthesizers (both statistical and deep-learning based) with privacy metrics, expanding evaluation dimensions to practical utility and risk, through empirical analysis of multiple actual outputs. The framework accommodates both an Exact Solution scenario, where synthesizer behavior is directly observable, and a Monte Carlo Approximation scenario where only synthetic outputs from a black box synthesizer are available. Extensive experiments on four real-world datasets and seven widely used graph synthesizers demonstrate framework's versatility, enabling privacy evaluation for different attack goals (e.g., to infer an edge or node) and capabilities (e.g., observing one or multiple synthetic graphs). We analyze evaluation results by examining the relationship between graph statistics and synthesizer design choices, providing insights for data curators in PGS selection and researchers for improved PGS design.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.09799v1">On the Order of Privacy and Smoothing in Functional Mean Estimation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-11-06T17:53:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haotian Chen, Yu-Wei Chen, Qifan Song, Jordan Awan</p>
    <p><b>Summary:</b> Differential privacy (DP) is a leading framework for privacy protection, yet privacy mechanisms tailored to functional data analysis (FDA) remain relatively underexplored. For functional mean estimation, we investigate a fundamental question regarding the ordering of privatization and estimation by comparing two canonical pipelines: Fit-Then-Protect (FTP), which smooths trajectories before privatization, and Protect-Then-Fit (PTF), which privatizes observations at discrete time points before smoothing. When data are observed without error, we prove that FTP achieves strictly smaller mean squared error than PTF asymptotically (as the sample size increases) under the same $μ$-Gaussian differential privacy ($μ$-GDP) budget in both finite-dimensional Hilbert spaces and infinite-dimensional reproducing kernel Hilbert spaces (RKHS). Simulation studies support our theory and explore settings with observation error and fitting constraints, demonstrating that FTP outperforms PTF under small observation noise, whereas PTF can become preferable in high-noise settings. In addition to this comparison, we establish a novel GDP guarantee for Gaussian perturbations taking values in a Banach space, extending existing results beyond the RKHS setting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.10097v1">A Privacy-Aware Deep Learning Benchmark for Facial Emotion Recognition</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-11-06T17:10:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Larissa Palhares, Maria Machado, Hudson Bruno, Raphael Ramos, Andrew Vale, Barbara Barbosa, Inara Souza, Fabio Grassiotto</p>
    <p><b>Summary:</b> Facial Expression Recognition (FER) traditionally relies on raw RGB images, introducing privacy risks, sensitivity to illumination variations, and susceptibility to identity-confounding visual shortcuts. As an alternative, this work proposes a lightweight, privacy-aware pipeline using exclusively geometric representations-facial landmarks (478 points) and blendshapes (52 coefficients, ARKit standard)-eliminating persistent raw video storage. Six neural architectures trained from scratch on fused CREMA-D and RAVDESS datasets were benchmarked against an ImageNet-pretrained ResNet50 baseline under a 5-fold subject-independent cross-validation protocol. Geometric models consistently outperformed the pixel baseline on unseen subjects with 12-124 times fewer parameters, while demonstrating superior robustness on subtle emotional expressions such as sadness. Ablation studies reveal that blendshapes capture the primary discriminative signal, while landmarks provide essential complementary spatial topology. These results demonstrate that compact geometric representations preserve affective semantics, eliminate downstream transfer learning dependency on visual backbones, and enable efficient, privacy-aware emotion recognition.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.09652v1">Breaking the Privacy Promise: Gradient Inversion Attacks on Federated Low-Rank Adapted Vision Transformers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-11-06T16:02:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ritik K. Badiya, Siladittya Manna, Ashmit Sinha, M Yashwanth, Anirban Chakraborty</p>
    <p><b>Summary:</b> Parameter-efficient fine-tuning (PEFT) has been increasingly adopted to fine-tune pretrained models with low computational cost and is therefore also preferred in the federated learning paradigm to reduce computational and communication overhead. In this work, we investigate the sparsely explored problem of the risk of private data leakage in LoRA-adapted Vision Transformers (ViTs), where low-rank updates weaken the gradient signal available to a server with access to individual client updates. We show that quality of reconstruction is limited by two coupled ambiguities: reduced information in LoRA gradients and missing spatial cues from frozen positional embeddings. To address this, we propose a spatially anchored generative inversion framework that incorporates server-prescribed trainable positional embeddings into ViT blocks during fine-tuning at clients. The resulting positional gradients act as layer-wise spatial anchors, providing additional positional cues, while the generative prior keeps reconstructions on a realistic image manifold, reducing duplicate-data and patch-permutation artifacts, {which produce similar gradients as those produced when the target client images are used}. Adding our proposed spatial anchoring to GIAS improves PSNR by 10.14 dB, SSIM by 0.45, and LPIPS by 0.098 on CIFAR-10, as well as PSNR gains of 7.83 and 11.74 dB on high-resolution CelebA and CARS datasets, respectively, in the FedSGD setting. Such gains in reconstructed image quality metrics are also maintained at higher batch sizes and in FedAvg settings. These results indicate that LoRA-based PEFT does not, by itself, prevent data leakage in FL, and carefully incorporated positional embeddings can help in exposing private information.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.09455v1">Overview of the ImageCLEFmedical 2026 GANs task: Exploring fingerprint detection, privacy leakage, and synthetic medical image generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-11-06T13:26:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alexandra-Georgiana Andrei, Mihai Gabriel Constantin, Mihai Dogariu, Dzmitry Karpenka, Yuri Prokopchuk, Ahmedkhan Radzhabov, Dan-Cristian Stanciu, Liviu-Daniel Ştefan, Vassili Kovalev, Henning Müller, Bogdan Ionescu</p>
    <p><b>Summary:</b> The 2026 ImageCLEFmedical GANs Task Exploring Fingerprint Detection, Privacy Leakage, and Synthetic Medical Image Generation continues to investigate privacy and security concerns around using patient data to generate synthetic medical images, now in its fourth edition. This edition introduces three complementary subtasks: the first extends prior editions by asking participants to detect which real images were used in training a Generative Adversarial Network to produce given synthetic outputs; the second is a novel subtask requiring participants to identify which latent vector produced each synthetic image, probing the faithfulness and reversibility of the latent-to-image mapping; the third asks participants to generate privacy-preserving CT slices, quantifying the trade-off between image fidelity and patient privacy. Ground-truth annotations and benchmark datasets of real and GAN-generated lung CT slices are provided for all subtasks. Evaluation is based on Cohen's Kappa for Subtask 1, matching accuracy for Subtask 2, and a combination of FID and Privacy Preservation Score (PPS) for Subtask 3. Overall, 37 teams registered for the task, with 10 teams submitting runs across subtasks and 6 teams submitting working notes papers. This paper presents an overview of the task setup, datasets, evaluation metrics, and summarises the approaches and results of participating teams.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.09423v1">Agentic AI for Healthcare Claim Denial Analysis: A Policy-Grounded Framework for Privacy Preservation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-11-06T12:51:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sofia Campos, Carlos Martins, Pedro Pires, João Gama, Bruno Veloso, Pedro Santos</p>
    <p><b>Summary:</b> In the healthcare sector, claim denials impose significant financial and administrative burdens, emphasizing the need for automated and trustworthy decision-support systems. This paper proposes a modular Agentic Artificial Intelligence (AI) framework for healthcare claim denial analysis, integrating specialized agents for denial risk prediction, risk factor identification, diagnosis-procedure-medication code relationship analysis, and counterfactual analysis. The framework integrates predictive analytics, graph-based learning, a Hybrid Contextual Retrieval-Augmented Generation (RAG) pipeline grounded in healthcare policy documents, and a dedicated HIPAA Compliance Agent to support privacy protection. Evaluated on a synthetic healthcare claims dataset, the framework achieved 98% traceability of reported numerical findings, validated 214 of 216 policy citations, and removed all 280 identified sensitive identifiers without modifying the underlying analysis. These findings pave the way for further research into Agentic AI as a framework for explainable, policy-aware, and privacy-preserving healthcare claim denial management.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.09372v1">Enabling Privacy-Preserving Natural Language Access to Industrial Smart Meter Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2026-11-06T12:11:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Carlos Martín-Abellán, Mark Kröll</p>
    <p><b>Summary:</b> Energy management officers and grid operators increasingly rely on smart meter data for anomaly detection, performance monitoring, and strategic decision-making. However, extracting actionable insights from large-scale, heterogeneous telemetry databases requires advanced SQL and data engineering expertise, creating a critical bottleneck for non-technical personnel. Furthermore, the strict data privacy regulations and security constraints inherent to critical energy infrastructure often prohibit the routing of sensitive consumer data through cloud-based Large Language Models (LLMs). To address these challenges, we present OpenMeter, a schema-agnostic Multi-Agent System (MAS) designed to translate natural language queries into executable code and human-readable insights. This architecture lowers the technical barrier for day-to-day utility operations by empowering non-expert personnel to interact with complex databases through intuitive natural language dialogue, transforming raw telemetry into a highly valuable tool for routine grid workflows and strategic decisions. Multi-scenario ablation studies over this environment demonstrate that full multi-agent orchestration shows its largest observed accuracy gains on resource-constrained local hardware (+6.1 pp EX-R over the strongest single-agent configuration); at frontier scale, individual components retain value but should be enabled selectively, indicating that the cost of full orchestration is justified specifically where privacy demands local execution.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.10054v1">AYO: A Safe and Privacy-Preserving Platform for Studying Children's Interaction with LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-11-05T23:44:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Huiwen Alex Yang, Rachel Skwersky, Bill D. Thompson, Celeste Kidd</p>
    <p><b>Summary:</b> Children and adolescents are increasingly interacting with generative AI and large language models (LLMs), yet little is known about how these interactions may influence their development, beliefs, and behavior. Existing research has relied heavily on surveys, while direct study of children's interactions with LLMs presents substantial challenges related to safety, privacy, consent, and experimental control. We introduce AYO (AI Youth Open Science), an open-source platform designed for safe and systematic research on children's interactions with conversational AI. AYO provides a child-friendly interface, configurable age-based safety guardrails, researcher monitoring, and privacy-preserving data practices. These capabilities enable cross-sectional, longitudinal, and experimental research on how children use and respond to LLMs and how AI design may shape trust, epistemic judgment, curiosity, and other aspects of development. AYO provides the infrastructure to generate evidence that guides safer AI systems, educational practices, and policies for children growing up with AI.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.08749v1">How are viral trends different from educational and commercial uses of LLM image generation and editing? A privacy-preserving descriptive analysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-11-05T21:56:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Will Tucker-Ray, Marika Swanberg, Alexander Knop, Marvin Chow, Eric Culbertson, Julian Jacobs, Pritish Kamath, Ravi Kumar, Jason Mothersill, Mikhail Pravilov, Eugene Quan, Yurii Sushko</p>
    <p><b>Summary:</b> Gemini's Nano Banana models, first introduced in late 2025, led to a shift in the capabilities and use of image generation and editing. We utilize Urania, a Google-developed framework for generating insights about LLM chatbot interactions with rigorous differential privacy (DP) guarantees, to analyze use cases and intents, techniques and ways of prompting, without ever looking at a single image or individual prompt. We select a subsample of 2.1M conversations in early 2026 which utilized Nano Banana models, into roughly 800 clusters in five categories: (1) Social & Viral Sharing, (2) Brand & Marketing Collateral, (3) Educational & Technical Information Media, (4) Product Visualizations & E-commerce, and (5) Architectural & Spatial Designs. We then compare these clusters on 21 features of use, measuring aspects of prompts' (a) editing techniques, (b) artistic style requests, (c) composition, and (d) chatbot interactions. This allows us to describe a baseline of how people are using image generation and editing tools for different use cases---(including growing and emergent use cases which were not possible before Nano Banana)---in a privacy-preserving manner.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.10038v1">Towards a Privacy-Preserving Reliability-Aware Entity Resolution for Attributed Graphs [Vision] (Technical Report)</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2026-11-05T17:24:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abdessamad Imine, Xiang Lian, Kambiz Ghazinour</p>
    <p><b>Summary:</b> Entity resolution (ER) on attributed graphs aims to identify nodes across multiple graphs that correspond to the same real-world entity and merge them into an integrated graph. When input graphs vary in quality and contain sensitive information, ER faces a dual challenge: while reliability information is crucial for accurate graph data integration, its presence in the published integrated graph can heighten privacy risks. This paper presents a research vision that unifies reliability assessment and privacy preservation within a single graph ER process. We highlight the inherent tension between these two objectives, propose a three-level coupled framework, and outline the remaining research challenges to enable the publication of integrated graphs that are both accurate and privacy-preserving.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.07490v1">Statistical and Privacy Guarantees for Deep M-Regression via Stochastic Gradient Langevin Dynamics</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-11-05T05:52:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yeheng Ge, Jian Huang, Shuyuan Wu</p>
    <p><b>Summary:</b> In this article, we study deep nonparametric regression trained via stochastic gradient Langevin dynamics (SGLD), a variant of stochastic gradient descent that injects carefully calibrated Gaussian noise during optimization. Using a PAC-Bayesian analysis tailored to deep ReLU networks, we establish an excess-risk bound that simultaneously accounts for network approximation error, statistical complexity, and the algorithmic cost accumulated along the SGLD trajectory. Under a Bernstein condition and within a stable SGLD regime, the excess-risk bound contains a stochastic term whose coefficient is inversely proportional to the variance of injected noise, while the estimator retains the optimal rate for nonparametric regression under the Hölder smoothness condition up to logarithmic factors. This result provides an approximation-error-aware, rate-optimal statistical perspective on the widely observed generalization benefits of moderate SGLD noise. For per-sample clipped SGLD, we further establish an exact f-DP guarantee and the corresponding asymptotic $μ$-GDP guarantee for the proposed estimator. We establish statistical convergence rates and differential privacy guarantees for DNN estimators trained using SGLD, while explicitly accounting for both network approximation error and the effect of injected noise in the excess-risk bound. Extensive simulation studies and analyses of two real datasets examine the finite-sample predictive performance and privacy-utility behavior of the proposed procedure.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.06221v1">FedXCrop: Privacy-Preserving Crop Disease Detection via Federated Learning with Post-Aggregation Explainability under Non-IID Farm Distributions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-11-04T09:30:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kriti Saini, Manikandan P</p>
    <p><b>Summary:</b> Deep learning can classify crop diseases accurately from benchmark leaf images, but centralized training requires farms to share raw data, and predictions without explanations offer limited support for treatment decisions. We present FedXCrop, a federated crop disease classification pipeline that quantitatively evaluates explanations of the aggregated global model. A MobileNetV2 model trained centrally on PlantVillage achieved 99.38% test accuracy (standard deviation 0.05 over three seeds) on a fixed test set of 5,428 images across 38 classes. Federated models initialized with ImageNet weights were trained for 30 rounds across five clients. FedAvg achieved 98.81% accuracy with identically distributed clients and 98.81%, 98.59%, and 97.78% under Dirichlet label skew (alpha = 1, 0.5, and 0.1, respectively). FedProx was not significantly different from FedAvg at any heterogeneity level (McNemar p > 0.3). Grad-CAM and SmoothGrad explanations were evaluated on 380 test images. Both attributed more energy to the leaf than chance (0.70-0.78 versus 0.60), while Grad-CAM maps from federated and centralized models showed Spearman correlations of 0.74-0.76. Agreement decreased as heterogeneity increased, lesion localization was only modestly above chance, and a model-randomization test indicated that SmoothGrad maps depended substantially on image structure rather than learned parameters. In this setting, label skew reduced federated accuracy by 0.6-1.6 percentage points relative to centralized training. FedAvg largely preserved Grad-CAM behavior, while FedProx provided no measurable benefit.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.06100v1">Reconciling Privacy with Provenance for Language Model Watermarks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-11-04T07:45:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Elise L. Han, Tatsunori Hashimoto</p>
    <p><b>Summary:</b> Watermarking has great potential for regulating the use of language models (LMs), but its deployment has been marred by controversy, as many users argue that fine-grained tracking of LM usage violates their privacy. This tension reduces the effectiveness of watermarks, as users engage in evasion strategies such as paraphrasing that can remove much of the watermark signal. We show that provenance and privacy can be reconciled if we shift the goal of watermark design from tracking individuals to estimating aggregate usage. We develop locally differentially private watermarks which provably limit the evidence that any individual text can contribute to detection, while still enabling accurate estimation of population frequencies. We introduce the Red-Green Sequence (RGS) watermark, a private and computationally efficient watermark that achieves accurate frequency estimation at high privacy levels across various models, sample sizes and generation entropies in settings that reflect realistic deployment scenarios. On C4 language modeling tasks, we attain $0.0019$ MSE with $0.0038$ mean absolute bias at a low $\varepsilon$ of 1, while in more challenging settings such as an essay writing task with only 100 text samples, we still find errors on the order of $0.0113$ MSE with $0.004$ mean absolute bias at $\varepsilon=2$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.05816v1">GRIDSHIELD: Verifiable Grid Feasibility and Manipulation Resistance in Privacy-Preserving Peer-to-Peer Energy Trading</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-11-04T01:49:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abdullahil Kafi, Md Zahidul Islam, Alvi Ataur Khalil</p>
    <p><b>Summary:</b> Blockchain-based peer-to-peer (P2P) energy markets let neighbors trade directly, but concentrate unchecked power in the clearing operator. Most prior work addresses only part of this: network-aware clearing respects grid constraints but operates on plaintext allocations, while privacy-preserving designs hide bids yet either drop the network constraint, enforce it only inside an unauditable computation, or recover it at the cost of a per-circuit trusted setup. Neither considers what happens if an adversary captures the operator's clearing privilege to reorder trades for profit or curtail a rival. We present GRIDSHIELD, a P2P energy-trading system that clears sealed bids with an order-independent batch program, removing the welfare a compromised operator can extract by reordering trades, and proves the result grid-feasible via an aggregated congestion-feasibility proof (ACFP). Exploiting the additive homomorphism of Pedersen commitments, ACFP reconstructs each grid constraint directly from per-bus commitments, reducing feeder-wide feasibility verification over any public grid constraints to a single aggregated range proof over the hidden allocation, with a reveal-and-recompute challenge that catches feasible yet unfair clearings. We introduce congestion-responsibility fairness (CRF), a metric scoring curtailment against each party's physical responsibility for congestion rather than consumption. We evaluate GRIDSHIELD against three prior P2P energy-trading designs across four feeders, including a 240-node Midwest feeder with real hourly loads, on a live Hyperledger Fabric network benchmarked with Hyperledger Caliper. GRIDSHIELD proves an entire round feasible with a few-kilobyte proof and no trusted setup, rejects infeasible allocations two of the three compared designs accept, and sustains $\approx$1064 tx/s.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.05582v1">Exploring the Privacy--Size Tradeoff for Differentially Private Self-Attentive Variational Autoencoders</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computational Engineering, Finance, and Science-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-11-03T20:12:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rohit Sadavarte, Dhruvi Kothari, Sparsh Gupta, Eric Van Oeveren</p>
    <p><b>Summary:</b> Data tends to be most useful when it is shared, and the data most worth sharing is often the data that privacy obligations restrict. Synthetic data from a generator trained under differential privacy (DP) is one way to reconcile the two, but its utility depends on the privacy budget $\varepsilon$ and on how much data the generator sees - a parameter that most data sharing applications of synthetic data control. We present SAVANT, a self-attentive variational autoencoder for tabular data trained with DP-SGD that, to our knowledge, is the first to combine attention, a VAE, and DP in one tabular model. We evaluate it against two marginal mechanisms, PrivBayes and MST, jointly over the privacy budget and the dataset size on two public datasets, measuring the utility a downstream classifier loses by training on synthetic rather than real data. We find that, under the same DP guarantee, more data generally means more utility. For the marginal mechanisms it absorbs most of what a strict budget costs, and a noise-scaling argument suggests DP-SGD exchanges data fo budget at a worse rate. Two independent membership-inference attacks, judged against a measured null, found no aggregate membership signal.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.05208v1">Privacy for Free in Efficient Agnostic Halfspace Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2026-11-03T16:56:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Giorgio Racca, Amartya Sanyal, Vikrant Singhal</p>
    <p><b>Summary:</b> We provide the first computationally efficient, differentially private algorithms for agnostically learning halfspaces. In particular, we study three different settings of agnostic learning: improper learning under Gaussian and log-concave marginals; proper learning under Gaussian marginals; and semi-agnostic learning under Gaussian marginals. In all three aforementioned settings, the added cost in the sample complexity due to privacy matches the respective non-private sample complexity, implying that we get privacy for free.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.04941v1">Residual Attribute Leakage Is an Interface: Auditing Privacy Evaluation After Text De-identification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-11-03T14:08:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tuan Thanh Duong, Joongmin Shin, Jeongho Yoon, Junyoung Son, Heuiseok Lim</p>
    <p><b>Summary:</b> A privacy evaluation of de-identified text asks a language model (the adversary) to guess a person's protected attribute. We introduce a prior-normalised clipped leakage score of its confidence gain on the true value and audit the conclusions drawn from it. Each verdict depends on an evaluation interface (the queried person, answer options, prior, adversary model and scoring rule), which we vary on fixed releases of three corpora. In a stress test, an editor that writes the opposite-sex form at the same spans a redaction editor would redact misleads the adversary about most people, yet ranks first among editors scored on the same MedQA entries under this score, as under attack accuracy and proper scoring rules read as privacy. A relabelling-invariant reading of AUC ranks that editor sixth of eight, and a rule-aware adversary recovers the attribute from the same text. On ordinary releases most verdict changes are gains or losses of separability; of six choices varied over all pairs, only the adversary reverses comparisons (5 of its 124 changes), and the query can target the wrong person. SACC, a traceable editor we build as the instrument, lets us ablate two editing principles and show where its advantage does not hold.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.04064v1">Minimax signal detection in regression under differential privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> 
  <p><b>Published on:</b> 2026-11-02T23:16:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Elly K. H. Hung</p>
    <p><b>Summary:</b> We establish minimax separation rates across sparsity levels for regression signal detection under $(ε, δ)$-central differential privacy, considering linear regression with an unknown error distribution and generalised linear models (GLMs) with an unknown intercept. Without sparsity restrictions, the separation rates for linear regression and GLMs with binary responses match the private Gaussian mean testing rate up to polylogarithmic factors. For GLMs with more than two possible response outcomes, additional information in the marginal response distribution permits faster detection of sufficiently small signals when the dimension exceeds the sample size $n$. Our upper bounds are based on a reduction to private mean testing, tests of dependence between the response and sparse covariate projections, and a response-only test that is adjusted for the unknown intercept. The resulting procedure adapts to unknown sparsity and matches our lower bounds up to polylogarithmic factors. We also construct polynomial-time tests that attain these rates when $ε\gtrsim n^{-1/2}$, and compare their numerical performance with existing private procedures.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.03130v1">An Information Hierarchy of Privacy Filters and Odometers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-11-02T13:43:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sophie Taylor, Praneeth Vippathalla, Justin P. Coon</p>
    <p><b>Summary:</b> In sequential data analysis, privacy loss accumulates over time, and privacy filters and odometers are used to control and track this cumulative cost. We study how the information used by differential privacy filters and odometers fundamentally limits what they can achieve. We formalise three levels of information: spec-level information, fixed prior to the interaction; mechanism-level information, which includes the mechanisms instantiated during the interaction; and realisation-level information, which further includes the realised interaction. We classify privacy filters and odometers by the least informative level sufficient to determine their behaviour.
  Our main results establish strict and arbitrarily large separations in achievable performance across this information hierarchy. For privacy filters, moving up the hierarchy can yield an unbounded utility advantage, quantified by a clipped measure of the number of allowed releases. For privacy odometers, it can yield an arbitrarily large improvement in precision, quantified by the expected peak excess of the reported bound over the realised privacy loss. Further, although the information classes are distinct, we show that moving to a richer class need incur essentially no loss in performance.
  Finally, we show that randomisation provides a resource orthogonal to information: at every information level, it can yield an arbitrarily large utility improvement over deterministic filters. Thus, information access and randomisation can be viewed as fundamental resources governing privacy procedures in adaptive interactions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.03026v1">Improved regret bounds in tabular RL under local differential privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-11-02T12:21:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hugo Richard</p>
    <p><b>Summary:</b> We study regret minimization for time-homogeneous episodic tabular reinforcement learning with $S$ states and $A$ actions under non-interactive $ε$-local differential privacy (LDP). In each episode $k \in [K]$, the decision-maker sends a policy to a user, the user executes the policy for $H$ steps, and sends an $ε$-locally differentially private message back to the decision-maker. When $H=1$, the problem reduces to an LDP contextual bandit with $S$ contexts, $A$ arms and horizon $K$. We prove that the minimax regret is $\min\bigg(K, \frac{ \sqrt{\max( S, \exp(ε) + 1) S A K (\exp(ε) + 1)}}{\exp(ε) - 1}\bigg)$, up to constants and a $\sqrt{\log(A)}$ factor. The upper bound is achieved by an adaptation of EXP3 and a unary encoding mechanism. When $H > 1$, and for small $ε$, we show a lower bound in $Ω(HS\frac{\sqrt{A K}}ε)$ and an upper bound in $\tilde{O}(H^2 S^2 \frac{\sqrt{ AK}}ε)$. The upper bound is achieved by an algorithm based on UCBVI and a unary encoding mechanism. For small $ε$, these bounds improve the previously known lower bound by a factor $\sqrt{S}$ and the previously known upper bound by a factor of $H \sqrt{A}$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.02661v1">PriCBMs: Multi-granular Concept Bottleneck Vision-Language Models for Visual Privacy Recognition</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-11-02T07:21:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shenglei Pei, Haotian Sun, Pengfei Li, Bingxu Lu, Wenlong Yu</p>
    <p><b>Summary:</b> Widespread image sharing on social media has increased the need for visual privacy recognition to identify inadvertently exposed privacy information. However, multi-label visual privacy recognition presents two challenges. First, privacy categories represent high-level semantic attributes and do not have a one-to-one correspondence with visual objects. Different visual objects may involve the same privacy category, while the same type of object may contain different types of privacy-sensitive information. In this setting, direct prediction methods generally lack explicit guidance for identifying category-relevant privacy cues, leaving this process implicit in the learned image-to-label mapping and potentially limiting classification performance. Second, privacy cues are often distributed across image regions and may not be adequately represented by whole-image features. To address these challenges, we propose Privacy Concept Bottleneck Models (PriCBMs). By introducing privacy-related concepts as intermediate semantic representations, PriCBMs first identify category-relevant privacy cues through visual-concept matching and then predict privacy categories based on concept responses. This process makes privacy predictions more interpretable. To improve the quality of these concepts, we design a concept selection strategy based on target-category relevance, cross-category discriminability, and semantic diversity. Meanwhile, we introduce a global-region modeling module to capture localized privacy evidence while retaining global context. Experiments on VISPR and FineViP show that PriCBMs outperform evaluated competitors across all four multi-label metrics. Ablation studies and concept-quality analyses support the effectiveness of the proposed design. Code is available at https://github.com/sun2293674491-dotcom/PriCBMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.02014v1">One String to Rule Them All: Measuring Consent Under the IAB Global Privacy Platform</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-11-01T15:56:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Muhammad Abu Bakar Aziz, Christo Wilson</p>
    <p><b>Summary:</b> Many privacy regulations, including the California Consumer Privacy Act (CCPA), require websites to honor users' opt-out choices. To facilitate this process, industry has introduced technical standards such as the IAB Global Privacy Platform (GPP), which aims to standardize collection and transmission of user consent information across multiple jurisdictions. However, it remains unclear whether these standards consistently and correctly transmit user opt-out choices, or whether opt-out choices are respected by advertisers.
  In this study, we conduct an in-depth analysis of consent propagation under the GPP framework. We collect data from four web crawls across four experimental settings to analyze how widely the standard is adopted, the extent to which opt-out signals propagate from publishers to third parties, and whether these signals reach and alter third-party advertiser behavior. Our analysis reveals several inconsistencies in the implementation and adoption of the standard that result in user consent signals being lost and user opt-out choices not being respected by the advertisers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.01903v1">Federated Estimation of Loading Spaces in Tensor Factor Models under Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2026-11-01T13:45:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zetai Cen, Fan Wang, Haeran Cho</p>
    <p><b>Summary:</b> Tensor factor models provide low-dimensional representations of tensor-valued observations while preserving their multiway structure. When these observations are held by different clients, privacy constraints may prevent them from being pooled for centralized analysis. We study estimation of common loading spaces in Tucker tensor factor models under federated differential privacy, allowing heterogeneous sample sizes, privacy budgets, and factor strengths. The proposed method combines private stability testing, Huber aggregation, and Gaussian perturbation at each client with weighted aggregation at the server. We establish non-asymptotic upper bounds governed by a scaled harmonic mean of the squared local error rates, and prove minimax optimality up to logarithmic factors under strong factors, fixed factor ranks, and fixed noise variance. We further develop a private calibration procedure that selects the local tuning parameters and aggregation weights without knowledge of the noise level or client-specific factor strengths. The resulting adaptive estimator preserves the privacy guarantee and attains the error rate obtained with oracle tuning. We illustrate the finite-sample performance of the proposed estimators through simulation experiments and an application to a Meditation Traits EEG dataset.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.01853v1">Privacy-Preserving ECG-HRV Emotion Classification for Mood Swing Detection using Federated Learning on Constrained Edge Devices</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-11-01T12:45:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chidike Vincent, Muhammad Aslam Jarwar, Najam Ul Hasan, Laurence Hirsch, Jonathan Zasada-James, Hem Raj Dadra</p>
    <p><b>Summary:</b> This paper presents a privacy-preserving mood monitoring framework that classifies emotional states from ECG-derived heart rate variability (HRV) features. The framework is evaluated on three public datasets comprising 74 participants and further validated using a wearable device in a pilot study. Leave-One-Participant-Out cross-validation (LOPO-CV) is used to assess generalization to unseen individuals. A series of experiments investigates the impact of temporal windowing, HRV feature selection, and class balancing on both four-class valence-arousal and binary valence classification. Results show that class balancing substantially improves minority-class recall, while Logistic Regression consistently outperforms five alternative classifiers and achieves competitive performance against HRV-based baselines. Pilot validation using a Polar H10 wearable achieves 75% binary valence accuracy on an unseen individual without calibration, demonstrating the feasibility of real-world deployment. To preserve privacy, the framework is also implemented using federated learning on a six-node Raspberry Pi cluster. Federated Logistic Regression achieves performance comparable to centralized training without sharing raw physiological data. These results demonstrate the potential of interpretable and privacy-preserving mood monitoring for continuous mental health assessment in clinical and community settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.01373v1">Differentially Private Distributed Optimization via the Intrinsic Randomness of Zeroth-Order Estimators: Sampling Geometry, Convergence, and Privacy Guarantees</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E"> 
  <p><b>Published on:</b> 2026-11-01T00:14:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiajun Wang, Yujie Tang</p>
    <p><b>Summary:</b> Distributed zeroth-order optimization has gained increasing attention in applications where exact gradients are computationally expensive or unavailable. However, the iterative exchange of local decision variables makes distributed networks vulnerable to inference attacks. While differential privacy provides a rigorous framework for privacy protection, conventional approaches generally require additional random noise, which inevitably affects optimization accuracy. In this paper, we investigate whether the randomness inherent in zeroth-order estimation can itself provide privacy protection. We develop a distributed zeroth-order gradient descent method that integrates consensus updates with a ball-uniform two-point gradient estimator. Our theoretical analysis shows that our algorithm attains standard convergence guarantees in both online and offline optimization settings. We then characterize the relevant probability distributions of the associated privacy mechanism, and establish differential privacy guarantees for both the online and offline optimization settings. These results reveal the potential of intrinsic zeroth-order randomness for privacy protection.</p>
  </details>
</div>

