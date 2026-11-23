
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



<h2>2026-11</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.27340v1">CoGITAtion: Collaborative Gaze-based Interpretable Task-adaptive Representation for Privacy-sensitive Applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-11-20T09:14:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mayar Elfares, Yasmine Elfares, Andreas Bulling</p>
    <p><b>Summary:</b> Gaze-based analysis provides rich behavioural information for privacy-sensitive applications, but deployment is challenged by heterogeneous, scarce, and distributed data. We present CoGITAtion (Collaborative Gaze-based Interpretable Task-Adaptive Representation), a framework for privacy-preserving inference over vertically distributed gaze data. CoGITAtion transforms variable-length gaze recordings into compact, interpretable gaze-transition graphs and descriptors computed locally by each data owner. Task-adaptive models accommodate heterogeneous and missing feature blocks through task and availability gating, avoiding unnecessary private computation. Results show that shared components capture patterns that generalise across tasks, while task-specific components provide capacity without increasing model size. Public availability gating further reduces encrypted computation by removing branches determined by publicly known task and owner availability without altering predictions. Overall, CoGITAtion enables gaze model reuse, efficient privacy-preserving deployment, and robust inference under incomplete owner availability while retaining interpretable gaze representations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.27114v1">Federated and Balanced $k$-means: Communication Efficiency, Privacy, and Heterogeneity</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2026-11-20T04:39:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Feiteng Nie, Shengkun Zhu, Sheng Wang, Yuan Sun, Feiping Nie, Wei Song, Zhiyong Peng</p>
    <p><b>Summary:</b> Collaborating on data across organizations in healthcare and finance demands methods that preserve privacy while enabling effective analysis. Vertical Federated Learning (VFL) facilitates clustering across data where different parties hold different features of the same entities without sharing raw data. However, existing VFL clustering methods suffer from two key limitations: vulnerability to information leakage and the creation of imbalanced clusters. To address these limitations, we propose Fabric, a balanced and privacy-preserving federated $k$-means algorithm. Our method decomposes the balanced clustering problem into independent subproblems for each client, using the Alternating Direction Method of Multipliers (ADMM) to efficiently handle the balance constraints. Under the semi-honest model, Fabric provides provable privacy guarantees by injecting calibrated noise into local objective evaluations. Extensive evaluations on ten real-world datasets show that Fabric achieves a superior utility-privacy trade-off compared with state-of-the-art methods and converges faster. Specifically, Fabric reduces SSE by 29.1\% on average and improves balance performance by 1.41$\times$, while being 26$\times$ faster on average.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.27046v1">Actions Speak Louder than Words: Stateful Privacy Sniffing of LLM Agents via Behavioral Covert Channels in Web Interactions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-11-20T03:17:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruichao Liang, Wenzhong Deng, Jing Chen, Yuqing Li, Kaixuan Li, Cong Wu, Yang Liu</p>
    <p><b>Summary:</b> LLM agents increasingly rely on Web interaction, issuing searches, following links, and reading pages, to complete complex user tasks. Since each action is driven by the agent's private context, including the user's prompt, dialogue history, memory, and connected data, it also opens a new privacy exposure surface. Prior attacks either passively analyze network traffic, which yields only coarse correlations, or hijack the agent through indirect prompt injection, which must place sensitive content in an outgoing field and is blocked by content-level defenses. Whether an attacker can actively recover fine-grained private context without any explicit transmission thus remains insufficiently understood.
  Our insight is that an agent's benign Web decisions themselves leak private context, as what it chooses to visit encodes whether, which, and in what order it acts, forming a behavioral covert channel. Building on this, we design SNOOP, a stateful hierarchical probing framework that narrows a coarse-to-fine hypothesis tree per task and reconstructs user queries and profiles from the agent's observable paths. Across four agents and three LLM backbones on 500 StackExchange queries and 378 multi-turn iKAT dialogues, SNOOP recovers query concepts with an average F1 of 0.89 and user profiles with an F1 of 0.80, while four representative agent defenses change its recovery by less than 0.03 F1. Since no sensitive content is ever transmitted, content-level inspection cannot detect this leakage; we therefore propose Selection-Obfuscated Retrieval (SOR), which acquires resources under a fixed budget independent of private context and confines the agent's selection to a local snapshot, cutting SNOOP's F1 to 0.39 without additional LLM inference.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.26983v1">Privacy Protection in Self-Evolving Personal Agents: Persistent Memory and Cross-Carrier Transfer</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-11-20T02:03:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zibin Lin, Taotao Wang, Shengli Zhang</p>
    <p><b>Summary:</b> Personal agents carry private experience into later decisions through persistent memory. This thematic survey compares memory admission, maintenance, release, and withdrawal by protected change, observer, and validation setting. Direct evidence in the screened corpus comes from controlled memory workflows. Three worked scenarios follow one private fact through booking, feedback-driven learning, and withdrawal. We show when prompt revision and memory reads compose, when skills inherit a private head's bound, and why reader non-use does not establish cleanup of learned state. Diagnostic experiments measure the utility costs of wider label protection and broad memory deletion, and test how missing lineage obscures descendants.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.26936v1">SecretAgent: A Multi-Agent Framework for Privacy Protection against Vision Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2026-11-20T00:46:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Minda Zhao, Yue Zhang, Mengyu Wang</p>
    <p><b>Summary:</b> Vision-language models (VLMs) can infer private information from shared images, including locations, personally identifiable information (PII), and personal attributes such as age and sex, even from medical images. Adversarial perturbations can protect such information against black-box VLMs, but existing methods overlook image quality and introduce visible artifacts into the images they protect. We present SecretAgent, the first general multi-agent framework that protects image privacy against VLMs while preserving visual fidelity. LLM agents iteratively locate the visual evidence that reveals private information and adapt an invisible perturbation to the target VLM's answers and to an appearance reviewer agent, which rejects any candidate with visible artifacts. We instantiate SecretAgent with two complementary variants: SecretAgent-Gradient optimizes the perturbation through six surrogate encoders for cross-model transferability, and the gradient-free SecretAgent-Tool composes procedural noise and achieves the best perceptual fidelity on three of the five datasets. Experiments on four privacy applications (geolocation, PII, facial, and medical) across five datasets and six VLMs show that SecretAgent preserves image quality substantially better than existing methods while achieving state-of-the-art privacy protection in every application, and that its protection transfers to other VLMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.26747v1">SkillPrivus: Uncovering PRIVacy of USe Harms in Agentic Skills</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-11-19T19:43:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mariana Fernandez-Espinosa, Ivoline Ngong, Keerthiram Murugesan, Karthikeyan Natesan Ramamurthy</p>
    <p><b>Summary:</b> Agent skills extend AI assistants through installable instructions and code that can access users' files, accounts, and data. Even when performing their advertised tasks, skills may infer sensitive attributes, retain unnecessary information, or disclose data to unexpected recipients. We study these potential privacy-of-use harms through SkillPrivus, a static audit framework that analyzes skills before installation without executing them. SkillPrivus extracts data operations from code and natural-language instructions, grounds them in source evidence, and adapts Contextual Integrity to assess their appropriateness. Applied to 726 real skills from public marketplaces, 563 of which handle personal data, SkillPrivus flags at least one potential violation in 307 of these skills (54.5%), and its judgments agree with three blind human annotators on 83.2% of resolvable moves. The flagged behaviors include sensitive inferences, information use beyond the stated task, and disclosures to unexpected recipients, suggesting that privacy harms can arise from ordinary skill functionality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.26709v1">Federated KPI Aggregation with Local Privacy Constraints and Coordinated OLAP Roll-Ups</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2026-11-19T19:09:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Felix Härer</p>
    <p><b>Summary:</b> Cross-organizational KPI analysis can require aggregated results from independently administered data warehouses without centralizing detailed records. To limit disclosure from small local groups, a site can require a minimum number of contributing records before releasing a KPI value for a group. If each site applies this rule independently, different local contributions may be suppressed and the combined KPI can become incomplete. This paper investigates whether OLAP granularity can be coordinated before local query results are released so that all sites satisfy their local minimum-cohort rules and contribute at the same analytical level. The proposed method selects the least-generalized common roll-up accepted by every site. Site agents coordinate current capabilities and approved local execution across independently administered sites, with privacy checks and aggregate computation remaining deterministic local functions. In a four-site prototype, coordinated roll-up retained all contributions and reproduced the corresponding centralized result, compared with 78.3% retained under independent suppression. A capability-change experiment showed fewer candidate checks and replies and no unsupported requests when current site-agent state was used. The results demonstrate the feasibility of federated KPI aggregation under local privacy constraints through coordinated granularity selection and agent-based coordination.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.25800v1">Personalized Privacy-Aware MARL Offloading in the Edge-Cloud Continuum</a></h3>
  
  <p><b>Published on:</b> 2026-11-19T09:24:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Muhammad Rafid, Golshan Famitafreshi, Kostas Ramantas, Luis Alonso, Christos Verikoukis</p>
    <p><b>Summary:</b> Task offloading in End-Edge-Cloud computing enables resource-constrained User Devices (UDs) to execute computation-intensive applications with reduced latency and energy consumption. However, existing task offloading schemes generally overlook the heterogeneous privacy requirements of users, leading to inefficient privacy-aware offloading decisions. In this paper, we propose a personalized privacy-aware task offloading framework, where the privacy requirement of each task is quantified through a User-Centric Privacy (UCP) model that considers task sensitivity, user privacy preferences, and task urgency. The task offloading problem is formulated as a Markov Decision Process (MDP) to jointly optimize the offloading ratio and the target computing server while minimizing the long-term system cost under latency, energy, and privacy constraints. To efficiently solve the resulting high-dimensional continuous optimization problem, we develop an Advantage-Weighted Actor-Critic (AWAC)-enhanced Proximal Policy Optimization (PPO)-based Multi-Agent Reinforcement Learning (MARL) algorithm under the Centralized Training and Decentralized Execution (CTDE) paradigm. Simulation results demonstrate that the proposed framework achieves lower average system cost, lower energy consumption, and higher task success rate than representative baselines under diverse privacy requirements.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.25775v1">Entanglement-Assisted Quantum Differential Privacy</a></h3>
  
  <p><b>Published on:</b> 2026-11-19T09:10:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chenjian Li, Ji Guan, Mingsheng Ying</p>
    <p><b>Summary:</b> Differential privacy has been successfully extended to quantum computing and information processing, where sensitive data are encoded in quantum states and protected by quantum noise mechanisms that keep the outcomes of any measurement on neighboring states nearly indistinguishable. In the quantum setting, however, the state submitted to a quantum computer may be entangled with a hidden reference system secretly held by an adversary. Such entanglement cannot be detected from the submitted state alone, and it poses a challenge with no counterpart in the classical setting. Existing frameworks of quantum differential privacy consider only measurements on the released state, leaving this scenario largely unexplored.
  In this paper, we identify the entanglement attack: an adversary submits one half of an entangled state to a quantum computer that runs a privacy mechanism, keeps the other half, and finally measures both halves jointly. We show that this attack may completely break a mechanism that satisfies quantum differential privacy with a finite parameter, driving its privacy parameter to infinity. To counter it, we propose entanglement-assisted quantum differential privacy (EA-QDP), a privacy framework that is native to quantum entanglement and remains valid against such attacks. We characterize exactly when a mechanism has a finite EA-QDP parameter, and show that the optimal parameter $\varepsilon^*_{\mathrm{EA}}$ of any quantum mechanism can be computed by a semidefinite programming problem (SDP). Building on this, we quantify the extra privacy leakage caused by entanglement and show that it can be bounded by choosing appropriate mechanisms, with the depolarizing channel being our recommended choice. Finally, we demonstrate both the attack and its countermeasure on simulated and physical quantum hardware, and the experimental results agree with our theoretical predictions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.25425v1">Instance-Optimal Moment Estimation in the Add-Remove Model of Differential Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-11-19T03:06:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shokichi Takakura</p>
    <p><b>Summary:</b> In this paper, we study the problem of estimating empirical means, variances, and covariances under pure differential privacy in the add-remove model. While existing mechanisms achieve optimal worst-case error, they may not be optimal for individual datasets. To measure the performance of mechanisms on individual datasets, we introduce instance-dependent error metrics and prove sharp lower bounds on them. Then, we design mechanisms that achieve these lower bounds and demonstrate that they achieve asymptotically better utility compared to existing methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.25374v1">Efficient Privacy-Preserving High-Dimensional Approximate Nearest Neighbor Search</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2026-11-19T02:13:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lyu Xu, Guozhong Li, Qichen Wang</p>
    <p><b>Summary:</b> In the AI era, approximate nearest neighbor (ANN) search on vector databases is critical as it supports similarity retrieval over high-dimensional vectors, which is essential for many large language model (LLM) applications. To reduce costs and improve scalability, vector databases are often outsourced to cloud servers, raising privacy concerns for users whose query vectors contain sensitive information. In this work, we study the problem of asymmetric privacy-preserving ANN search, where the vector database is public but user queries must remain private from an untrusted cloud server. To solve this problem, we propose ObliSC, an efficient privacy-preserving search framework that protects query privacy against access-pattern leakage. ObliSC consists of (i) a search base that retrieves ANNs with a strong privacy guarantee of full obliviousness; and (ii) parallel optimization strategies that accelerate candidate retrieval and refinement while preserving full obliviousness and retrieval quality. Experiments on six standard ANN benchmarks show that ObliSC not only achieves efficiency and result quality competitive with baseline methods but also maintains a lightweight index compared with the evaluated privacy-preserving approaches.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.25063v1">Functional Estimation under Local Differential Privacy: General Lower Bounds and Applications to Entropy and Power Sums</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">
  <p><b>Published on:</b> 2026-11-18T19:08:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yann Issartel</p>
    <p><b>Summary:</b> We study the estimation of functionals of discrete distributions under local differential privacy (LDP). Even for well-studied examples like Shannon entropy and power sums, the existing bounds left open how the minimax risk scales with the alphabet size, the sample size, and the privacy parameter. To understand these dependences, we establish two general minimax lower bounds for the broader class of additive functionals. The first lower bound links the difficulty of estimating a functional to how well it can be approximated by polynomials of a given degree. The second complements the first by capturing how sensitive the functional is to small changes in the underlying distribution. To illustrate the effectiveness of these two bounds, we apply them to the estimation of Shannon entropy and power sums. In both cases, they close the existing polynomial gaps and, perhaps surprisingly, show that simple plug-in type estimators already achieve the optimal polynomial rates.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.23551v1">Federated Differential Privacy with Batch Contamination</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> 
  <p><b>Published on:</b> 2026-11-17T21:59:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jason K. C. Ng, Thomas B. Berrett, Yi Yu</p>
    <p><b>Summary:</b> We study mean estimation under federated differential privacy (FDP) constraints and batch contamination, considering both Gaussian and heavy-tailed distributions. In the homogeneous setting, where sample sizes and privacy budgets are constant across servers, we show that the costs of privacy and contamination disentangle. Under a bounded $v$th moment condition, with $v \in (1, \infty)$, the cost of batch contamination is of order $(\varepsilon/n)^{2-2/v}\vee \varepsilon^2/n$, where $\varepsilon$ is the contamination level and $n$ is the per-batch sample size. This reveals a phase transition at $\varepsilon\asymp n^{1-v/2}$, for $v > 2$, which is the first of its kind in the literature. We develop a two-stage procedure that achieves the minimax rate up to poly-logarithmic factors. A key component is a private smoothed voting procedure tailored to the FDP setting that provides optimal sensitivity control. For heterogeneous batch sample sizes and privacy budgets, we introduce a batch partitioning framework that groups batches with comparable per-batch sample sizes and privacy budgets. Surprisingly, the minimax rate is determined, up to poly-logarithmic factors, by the most informative group of batches. Consequently, in some regimes, it is minimax optimal to use only an arbitrarily small proportion of the data set. Heterogeneity also introduces interactions between the costs of privacy and contamination, in contrast to their disentanglement in the homogeneous setting. For unknown contamination level, we propose an adaptive, near-minimax optimal Lepski-type extension for the heterogeneous Gaussian setting, designed specifically to prevent privacy leakage by ensuring no repeated use of data points.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.22223v1">GapLeak: When Privacy-Preserving LLM-based Web Agents Become a Privacy Risk</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-11-17T05:06:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chaklam Cheong, Tiancong Cao, Qi Li, Zelin Zhang, Jianbing Ni, Rongxing Lu, Mohammad Zulkernine</p>
    <p><b>Summary:</b> Large Language Model (LLM)-based web agents rely on data minimization and least privilege to protect user privacy. We show that these principles are necessary but insufficient: they constrain authorized sources, but not higher-sensitivity sources that remain reachable. A website can request a field unavailable from authorized sources, creating an information gap. To complete the task, a goal-driven agent may escalate to reachable but unauthorized sources and disclose accumulated sensitive information. We formalize this vulnerability as GapLeak, where an adversary exploits a legitimate web form without prompt injection or other malicious instructions.
  We evaluate GapLeak on three web-agent frameworks and six LLMs from Anthropic, Google, and OpenAI across recruitment, e-commerce, travel, and healthcare. GapLeak induces an average unauthorized disclosure of approximately 37%. The information gap is the primary driver: eliminating it reduces disclosure by more than 50%. Existing instruction-level defenses based on least privilege partially mitigate the vulnerability but often reduce task success. We propose submission-time verification, which filters unauthorized content before form submission, eliminating over 96% of unauthorized disclosures while preserving task success.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.22200v1">MIRAGE: Motion Identity Reduction via Autoregressive Generative Encoding for Privacy-Preserving Skeleton-based Motion Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-11-17T04:39:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Thomas Carr, Xujun Che, Depeng Xu, Shuhan Yuan, Aidong Lu</p>
    <p><b>Summary:</b> Skeleton motion identifies people through body proportions and movement style, and skeleton streams are increasingly passed to third-party analytics that run action classifiers trained on raw data. A prior adversarial anonymizer adds a per-frame residual in the raw coordinate space but sees one frame at a time; motion retargeting needs a target skeleton and complete sequences, which rules out online use. We present MIRAGE, a target-free, causal anonymizer that adds an identity-reducing residual to each incoming frame in the raw coordinate space, computed by attention over past frames. One causal, optionally windowed mask governs every attention in a rotary-position encoder-decoder, and key/value caches let the trained function run frame by frame; on all 56,578 NTU 60 sequences, batched and streaming outputs differ by at most 7.2e-6 m. Reported results use an unbounded window, so per-stream state grows with stream length. We evaluate against a passive adversary that applies raw-trained identity models and an adaptive adversary that trains on the anonymizer's output, treating the adaptive adversary as the headline, on NTU RGB+D 60 over five generator seeds, alongside the per-frame residual anonymizer of Moon et al. trained identically. When consumers retrain on the released data, MIRAGE keeps 83.9% action recognition (raw 89.1%; Moon et al. 88.7%) while a retrained identity classifier reaches 43.4% re-identification (RI) over 40 subjects, against 69.4% for Moon et al. and 75.4% on raw data. The strongest adaptive attacker still reaches 49.3% (chance 2.5%), so MIRAGE reduces identity leakage; it does not anonymize. Against raw-trained (frozen) classifiers, MIRAGE lowers RI below the strongest retargeting baseline (10.36% vs. 22.09%), but frozen action recognition falls to 37.04% (vs. 75.82%), so at full residual scale it is not a drop-in replacement for raw input to existing frozen models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.21955v1">SCAN: Site-Aware Collaborative Privacy-Preserving Adaptation of Vision-Language Models for Neurological Disease Classification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> 
  <p><b>Published on:</b> 2026-11-16T22:36:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nikhil J. Dhinagar, Rishab Pendam, Harmony S. Cen, Sophia I. Thomopoulos, John P. John, Mahir H. Khan, Sook-Lei Liew, Erik Kaestner, Carrie McDonald, Paul M. Thompson</p>
    <p><b>Summary:</b> Worldwide neuroimaging data could strengthen diagnostic foundation models, but privacy rules often prevent centralizing brain MRI scans. We present SCAN, a site-aware collaborative adaptation framework for Neurological Disease Classification that lets new sites adapt a 3D medical vision-language model (VLM) without retraining or sharing patient scans. Each site keeps exact class prototypes for local prediction and can share privacy-protected class summaries: norm-bounded sums and counts perturbed once with calibrated noise. Using 7,641 scans from 67 sites across 12 countries, covering Alzheimer's disease (AD), stroke, epilepsy and controls, we assess local adaptation, cross-site benefits, and effects on existing sites. At seven unseen sites, the frozen VLM's zero-shot AUCs were 0.833-0.945 for AD and stroke. Training-free local prototypes improved epilepsy AUC at three sites from 0.598/0.625/0.508 to 0.684/0.729/0.762 and AD AUC at one site from 0.833 to 0.863, nearly matching a classifier trained at each site (mean AUC 0.757 vs. 0.759). With differential privacy ($ε$ = 4), new sites contributed without materially reducing accuracy at existing sites (AUC change $\leq$0.2%), although gains from sharing were limited, and membership attacks performed near chance. SCAN offers hospitals a worldwide framework to adapt and share brain MRI VLMs without exchanging scans or retraining.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.21923v1">Wrong Input, Wrong Threshold: Re-evaluating Adversarial Facial Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-11-16T21:37:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tunahan Parlayıcı, Erchan Aptoula, Yücel Saygın</p>
    <p><b>Summary:</b> Published face-privacy methods report protection above 90% against black-box recognition models. That number comes from an evaluation protocol with two independent defects, reported in a measure that cannot size either one. The input is wrong: methods published since 2022 feed the network the whole photograph, or a detector's box, where deployed systems detect, align to a landmark template and crop. Re-scoring the same files through a realistic front end costs a standard transfer attack 56% of its dodging protection and a budget-allocating attack 7%, with no image regenerated. The measure is wrong: that loss is a difference of success rates, so it saturates, moving by 8.2x over a budget sweep while the effect beneath it moves by 1.34x. We therefore report the paired cosine shift, in which both thresholds cancel algebraically, so the input defect holds without committing to a calibration. Measured that way it is 2.2x and 10.7x larger on three unseen recognizers, and at matched budget it reverses the L-infinity transfer ranking: the one surveyed method that aligns at evaluation gains 0.18 where MI-FGSM loses 0.05. The cause is a resampling mismatch, not perturbation lost outside the crop; optimising through a differentiable alignment operator largely removes it, adding +24 to +58 points on unseen recognizers and a commercial system, with a residual on one of them. The thresholds are wrong: the four constants inherited since 2021 hold the false-accept rate near its nominal 1% on aligned crops but admit 2.3-5.4% on whole images, with an opposite-signed bias across dodging and impersonation, the two tasks reported side by side. Differentiable alignment and gallery scoring are not new: the first generation of this literature used both, and we show what dropping them cost.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.21590v1">The Provenance-Privacy Paradox: Can Private Cloud Compute (PCC) Prove That Apple Reference Images Are Not Used for Learning?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-11-16T18:56:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohammad I. Husain, Viet Nguyen</p>
    <p><b>Summary:</b> Apple Reference Image (ARI) combines camera-sensor signatures, Secure Enclave attestation (SEP), cryptographic timestamp bounds, Private Cloud Compute (PCC), and a final post-quantum signature to establish photographic provenance. PCC is central to this process because it validates the secure digital negative and develops authenticated raw sensor measurements into a reference JPEG. Although the secure digital negative is encrypted during transmission, the authorized PCC workload must process the raw pixels in plaintext. This requirement creates a provenance-privacy paradox: cloud processing strengthens the provenance guarantee while giving an Apple-authorized, machine-learning-capable workload access to valuable, hardware-authenticated raw imagery. We argue that workload attestation and transparency-log inclusion verify software identity and authorization but do not, by themselves, prove that an authorized workload cannot learn from or retain information derived from the photograph.
  We implement this counterexample in a Python- and Docker-based experimental testbed that models relevant ARI and PCC functions. Across 27 public-domain photographs, a baseline workload and a learning-enabled workload both passed the same verification checks and returned byte-for-byte identical JPEGs. However, the learning-enabled workload retained a first-layer gradient of approximately 48 KB from which its 64 x 64 input was reconstructed with a maximum absolute per-pixel error of 6 x 10^-8. The additional processing overhead was small relative to image decoding and processing. These results do not demonstrate that Apple currently trains on ARI photographs or reproduce production PCC, but identify non-learning and non-retention as independently verifiable assurance requirements.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.21494v1">Location Privacy for ISAC Systems: Rate, Sensing, and Privacy Tradeoff</a></h3>
  
  <p><b>Published on:</b> 2026-11-16T17:59:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Umair Ali Khan, Lester Ho, Holger Claussen, Mark F. Flanagan, Chinmoy Kundu</p>
    <p><b>Summary:</b> In this paper, we design a beamformer for transmitter location privacy in an integrated sensing and communication (ISAC) system, where the transmitter communicates with a receiver while sensing a point target. We adopt the direction-of-arrival obfuscation power ratio (DoA-OPR), the ratio of the received power in a prescribed fake direction to that in the actual direction, as the location privacy metric. To design the beamformer, we formulate an achievable rate maximization problem subject to constraints on total transmit power, target sensing, location privacy, and the number of data streams. The resulting problem is nonconvex and is addressed through an eigenmode-selection and power-allocation framework. To reduce the computational complexity of the solution, we develop strategies that eliminate infeasible candidate solutions. Furthermore, we propose a fake angle selection technique in which the transmit power for target sensing aids location privacy. Numerical results illustrate the achievable rate-sensing-privacy tradeoff and show that the proposed fake angle selection technique performs better than the random fake angle selection technique.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.21694v1">TIBECG: Temporal Information Bottleneck for Lead-Specific Demographic Privacy in ECG Waveform Release</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2026-11-16T11:24:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tsai-Min Chen, Jun Seita</p>
    <p><b>Summary:</b> Transmitting an electrocardiogram (ECG) waveform can expose demographic information beyond an intended diagnostic task. We evaluate TIBECG, an architectural temporal information bottleneck, on individual leads extracted from hospital twelve-lead recordings. A 2,302,337-parameter processor varies its latent length while retaining the same nine-score consistency objective, without age or sex labels in protector fitting. Across 6,386 recordings, ten folds, 12 leads and 21 lengths, retrospective selections retained at least 95% of each lead's clean macro-F1. Their weaker age/sex interval gain exceeded the best eligible conventional transformation on all leads, by a median 22.08 percentage points. The implemented sampling-rate comparison shows that direct downsampling usually suppresses demographic inference more strongly but at a larger loss of diagnostic utility, whereas TIBECG favors utility preservation. Selection stability also varies by lead. Lower latent Kullback-Leibler (KL) divergence does not reliably rank residual sex leakage at a fixed length. These findings support lead-specific evaluation of waveform processing, not validated consumer deployment or expert-readable reconstruction. When the waveform-input diagnostic classifier is hosted as part of a proprietary cloud service rather than deployed on the device, waveform transmission is required to obtain its scores.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.20389v1">Where the Evidence Lives: Measuring Privacy and Diagnosability of Exported AI-Agent Traces</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-11-16T01:34:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chang Xu, Hao Wang, Gedi Zhou, Junyuan Tan</p>
    <p><b>Summary:</b> Execution traces help diagnose AI-agent failures, but sharing them can expose customer identities. For example, detecting that an agent handled the wrong customer's records requires knowing whether the records belong to the requested customer, but not necessarily knowing who that customer is. Our executable benchmark measures what a trace export reveals and whether a proposed repair restores the correct output in synthetic multi-tenant workflows. Conventional redaction can remove evidence needed for repair while leaving encoded identifiers recoverable. Two exports preserve ownership comparisons by reporting the match as a comparison fact or by using pseudonyms consistent within each execution. Both preserve the original diagnostic program's repairs. The tested identifier matchers identify no requested customer from either export. An independently written program produces correct outputs on 39 of 42 faulty cases with comparison facts and on all 42 with execution-scoped pseudonyms. Row counts still expose identities. With prior knowledge of customers' row counts, an attacker uniquely identifies the requested customer in 97 of 240 executions under each of the 15 export policies. Removing selected counters from the comparison-fact export stops this attack and preserves the original program's repairs. The benchmark lets engineers test what their diagnostic program can repair and what an attacker can still infer from the same export.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.20223v1">Understanding Users' Security, Privacy, and Trust Concerns in Healthcare AI Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-11-15T19:43:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tushar Nayan, Mohammed Al Duniawi, Song Fang, Aokun Chen, Arjun Arunasalam, Ruimin Sun</p>
    <p><b>Summary:</b> Artificial intelligence is increasingly integrated into healthcare systems, from clinical information retrieval to workflow automation and decision support, which introduces new security, privacy, and trust risks with direct implications for patient care. While prior work has examined these risks from technical and regulatory perspectives, less is known about how these risks are naturally discussed in online communities. To address this gap, we conduct a large-scale analysis of 14 medical communities on Reddit and extract 6,514 relevant posts. Through systematic qualitative coding and LLM-assisted classification, we investigate concerns expressed in healthcare AI discussions, their prevalence, and how they evolve over time. Our analysis reveals that users perceive healthcare AI as expanding traditional healthcare trust boundaries and attack surfaces through integrations with electronic health records, third-party services, cloud platforms, and automated clinical workflows. Posts express concerns about over-privileged access to sensitive records, opaque data flows, unauthorized secondary use, and unsafe automation can amplify the consequences of errors and misuse. We identify four attitudes toward these risks: exploring questions of accountability and harm, cautiously accepting AI with stronger safeguards, skepticism about system trustworthiness, and resignation to growing data exposure and automation. Longitudinal analysis shows that SP&T discussions have increased significantly, with shifts coinciding with major healthcare AI deployments, privacy incidents, and regulatory developments. These findings illuminate changing trust relationships and data-governance challenges, informing the design and governance of safer, more transparent, and accountable healthcare AI systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.18925v1">Privacy-Preserving Clustering Algorithm and Parameter Selection for Collaborative Population Stratification Using Distributed PCA</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-11-13T20:27:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maryam Ghasemian, Lynette Hammond Gerido, Erman Ayday</p>
    <p><b>Summary:</b> We propose a privacy-preserving selection layer for collaborative population stratification workflows, enabling an honest-but-curious server to recommend a strong clustering algorithm-hyperparameter configuration from privacy protected shares. Instead of using a fixed workflow such as PCA followed by K-Means with a preset number of clusters, the framework compares multiple clustering methods and parameter settings under privacy constraints. To avoid relying on a public reference basis, we construct a shared low-dimensional representation through a distributed-PCA (DPCA) procedure in which each party computes local top-$r$ principal-component information and the server aggregates only low-rank summaries to recover a global basis. Building on this representation, the framework supports three LDP-protected pipelines: PCA then Noise, Noise then PCA, and Noise-Only. The server evaluates clustering methods and parameter settings using internal validation metrics and recommends a top-performing configuration from the perturbed data; this step is pure post-processing.
  Experiments on openSNP and 1000 Genomes show that the server-side selection layer reliably identifies strong settings from LDP-protected data. Across both datasets, the PCA-based pipelines outperform Noise-Only in clustering utility, communication cost, and runtime, and show lower membership-inference attack (MIA) power at small privacy budgets. Overall, they provide the best utility--scalability trade-off in our setting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.18513v1">MeReader: An Offline, Privacy-Preserving, Progress-Aware AI Assistant for Narrative eBook Reading</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-11-13T18:29:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohammed Efaz, Udo Bub, Itilekha Podder</p>
    <p><b>Summary:</b> This paper introduces MeReader, a privacy-preserving, offline and progress-aware AI assistant designed to function as a contextual companion for narrative reading on consumer hardware. Unlike conventional Large Language Model (LLM)-based systems that process documents/books online in an all-texts-at-once type of way, thereby risking narrative spoilers, MeReader confines both retrieval and generation to the reader's distinct position in the text. The system integrates a hybrid retrieval architecture, combining vector similarity, BM25, and summary embeddings, to ensure high fidelity to the reader's current context. We evaluate the system across classical English books using both quantitative comprehension metrics and qualitative LLM-based independent judging. The results identify a quality-latency frontier, showing that mid-sized local models (2b-4b) can achieve comprehension parity with larger counterparts (5b+) while maintaining acceptable response quality. Importantly, the proposed progress-aware boundary mechanism is shown to prevent future content leakage without compromising retrieval quality and correctness. These findings suggest that a localized, privacy-centric approach can augment, rather than replace, the digital reading experience, offering a good alternative to cloud-dependent services. Therein, there remains a lack of amalgamate systems which combine progress-aware, privacy-preserving, and narrative eBook reading with AI support. It is in this very gap that the development of MeReader came to be; synthesizing said strands into an offline, book-constrained assistant focused on enhancing comprehension without compromising narrative continuity or user privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.18385v1">Voice-Based Conversational Agents as AI Care Assistants: Evaluating Personalization, Intervention Delivery Fidelity, and Privacy Expectations in Older Adults' Care</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-11-13T16:27:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Thalia Viranda, Shupeng Wang, Jia Bo, Yuchen Yang, Hongjiao Zhang, Andrea Cuadra, Daniel A. Adler, Walter Boot, Sara Czaja, Deborah Estrin, Tanzeem Choudhury</p>
    <p><b>Summary:</b> Generative AI enables voice-based conversational agents to play more active roles in older adults' care, including personalizing support and operating alongside clinicians and care partners. This shift creates two challenges: how to personalize support while faithfully delivering evidence-based interventions, and how to manage personal-data use and sharing across AI and care stakeholders. We designed and evaluated ARC, a voice-based conversational agent that operationalizes multidomain lifestyle intervention through sessions with predefined goals, participant context, and evidence-based components. In a 3-day remote study, 80 older adults completed 473 sessions across six session types (9,183 turns; averaging 19.4 turns and 6 minutes per session). Participants reported favorable usability, acceptability, and use intentions. System-level analyses showed strong domain-level but modest participant-specific contextual reuse, no significant personalization-fidelity association, and fidelity limitations centered on incomplete delivery of intervention components rather than off-protocol drift. Within care relationships, expectations for personal-data use and sharing varied by data type and recipient. Our findings support feasibility of conversational delivery of multidomain lifestyle intervention, offer methods and system-design insights for longitudinal evaluation, and motivate an evaluation agenda for generative AI health interventions: user-experience and outcome measures should be complemented by evidence of whether intended intervention processes were delivered as designed.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.18312v2">On the Same Track: Privacy Leaks in Electric Rail Transport via Magnetic Fields</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-11-13T15:31:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stefan Czybik, Pia Hanfeld, Konrad Rieck</p>
    <p><b>Summary:</b> Inertial sensors of smartphones are a well-known privacy risk, as they allow inferring sensitive user movements and activity without explicit permissions. Among these sensors, the magnetometer has received little attention, as it is assumed to measure mainly the Earth's magnetic field. In this paper, we show that electric trains generate distinctive magnetic fields that can be captured by a smartphone magnetometer. Apps deployed on the device can access these signals without user permission, enabling two novel attacks on passenger privacy: First, we are able to determine whether the user is riding an electric train (transport mode detection). Second, we can infer whether other victims are aboard the same train due to shared patterns in the magnetic field (colocation prediction). In an empirical evaluation across 217 train rides, we demonstrate that both attacks are effective, confirming a real-world threat. We discuss countermeasures and argue that magnetometer access should require explicit user permission in mobile operating systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.18293v1">PrivacyPR: A Dataset of Real-World Privacy Fixes for Benchmarking Privacy-Aware Code Review</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2026-11-13T15:18:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hua Yang, Aditya Bhardwaj, Shidong Pan, Bowen Xu</p>
    <p><b>Summary:</b> Coding agents increasingly review code, yet whether they catch the privacy defects that laws such as the GDPR require software to avoid remains largely untested, partly because few datasets connect real privacy defects to their accepted fixes and review context. We present PrivacyPR, a dataset of 4,131 merged GitHub pull requests (PRs) from 1,469 repositories, created between June 2018 and January 2024. Each PR includes its commits, diffs, review discussion, and LLM-generated labels for privacy relevance, fix type, and GDPR principles. PrivacyPR provides 1,169 high-confidence privacy fixes and 1,643 non-fix PRs, together with Verified, a manually checked split of 250 privacy fixes and 250 non-fix PRs, and Small, a 100 + 100 subset for evaluation. On Verified, both annotators endorsed 72% of the LLM's GDPR-principle assignments. Beyond supporting empirical study of how privacy defects arise and are fixed, PrivacyPR provides a benchmark for privacy-aware code review on real, developer-accepted fixes. Its evaluation harness reverts each fix to reintroduce the defect. On Small, two coding agents detect only 42-51% of defects under a generic review prompt, but 88-91% when explicitly asked to check privacy, while flagging 11-15% of non-fix PRs. These results show that privacy defects can be detected by coding agents, but that detection depends strongly on review intent and comes with false alarms. Data, code, reviews, judge verdicts, and an extensible evaluation harness are publicly available at https://doi.org/10.5281/zenodo.23744765.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.17596v1">Tractable Importance Sampling for Monte Carlo Privacy Accounting</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-11-12T23:33:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Galen Andrew, Arun Ganesh</p>
    <p><b>Summary:</b> Evaluating tight Differential Privacy (DP) parameters for DP matrix factorization with privacy amplification by sampling requires analyzing high-dimensional, correlated Gaussian mixtures. Because integrating these mixture distributions to find the exact privacy failure probability ($δ$) is analytically intractable, these mechanisms are typically analyzed using Monte Carlo accounting. However, standard sampling suffers from prohibitive variance when estimating small $δ$ associated with strict privacy guarantees, which in turn requires a large sample complexity, making Monte Carlo accounting inefficient. We demonstrate that Monte Carlo accounting can be made much more efficient via importance sampling. We give a shifted importance sampling proposal distribution parameterized by a stretch factor $α> 1$. We prove a closed-form bound $B(α) < 1$ on the support of the importance-weighted estimator that holds identically for both directions of the hockey-stick divergence, show that $B$ is log-convex so that the optimal $α$ is a one-dimensional root-finding problem, and show that the resulting estimator seamlessly plugs into the KL-Hoeffding verification protocol used by past work, with a sample complexity reduced by exactly a factor of $1/B(α^*)$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.17554v1">Online Allocation with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-11-12T22:15:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jianyi Yang, Xingyu Zhou, Mostafa Mushsharat, Shaolei Ren</p>
    <p><b>Summary:</b> We study private online allocation problems, where allocation decisions must satisfy differential privacy (DP) to protect sensitive user information while optimizing performance under limited resources. We first formalize differential privacy notions suited to different privacy requirements in online allocation and establish the fundamental performance limits of any algorithm under these definitions. Based on these insights, we propose PPOA, a privacy-preserving meta algorithm for online allocation, and establish sufficient conditions under which PPOA preserves Joint DP (JDP) or Local DP (LDP) while achieving asymptotically near-optimal performance. Building on these conditions, PPOA can be instantiated into a variety of concrete algorithms. In particular, we present the specific designs, which include PPOA-DMD that preserves JDP and LDP and PPOA-FTRL that preserves JDP. We analyze their performance under both adversarial and stochastic settings and characterize the fundamental trade-offs between DP and allocation performance. Finally, we demonstrate the superior performance of the proposed algorithms via numerical experiments on AI model routing in battery-powered edge systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2611.17490v1">Learning Recommendations under Imperfect Human Compliance with Record-Level Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-11-12T20:24:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuwen Ma, Nicola Bastianello, Sarah Spurgeon, Boli Chen</p>
    <p><b>Summary:</b> This paper investigates human-in-the-loop recommendation systems, where effectiveness relies on human compliance and privacy concerns restrict the use of historical response data. The pro posed framework models the implemented action as a random response to the recommendation and formulates the recommendation mechanism as a decision-dependent optimisation problem under an unknown compliance distribution. A batched Gaussian process upper confidence bound algorithm is then adapted to learn from locally perturbed historical actions, providing privacy for individual raw records. The analysis establishes record-level differential privacy and derives high-probability simple regret bounds when the compliance distribution is unknown. These bounds characterise how privacy noise, batch size, and behavioural information affect the guaranteed quality of the learned recommendation. In particular, a known upper bound on the non-compliance rate enables the rec ommendation space to be screened before any private data are queried. Simulations of a fixed-state car-following problem with synthetic historical driver responses demonstrate the effectiveness of the proposed algorithm and verify the theoretical findings.</p>
  </details>
</div>


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

