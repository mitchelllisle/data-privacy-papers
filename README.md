
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
  <h3><a href="http://arxiv.org/abs/2610.29929v2">Privacy Preference Controls for Agentic Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-10-21T16:03:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shreya Kochar, Peeranat Sugsavanvit, Vidur Gupta, Joseph A. Calandrino, Deepak Kumar, Brett Frischmann, Sebastian Zimmeck</p>
    <p><b>Summary:</b> In response to vast and widespread online tracking, regulators and technologists alike have worked to develop laws and tools that allow people to express their privacy preferences. These measures seek to offer users greater control over the sale and sharing of personal information, putting agency in their hands to protect their privacy. However, the web is undergoing a seismic shift, away from strictly user-driven behavior towards agentic behavior, where AI agents take autonomous actions on behalf of users. In this study, we ask: What should privacy preference controls look like in the agentic web and agentic systems more generally? To answer this question, we develop a taxonomy of enforceable privacy preferences for agentic systems. Our taxonomy is informed both by laws and empirical studies of existing privacy tools as well as an audit of 30 leading AI assistants and agent platforms. To explore how our taxonomy can be implemented, we design and develop eight open-source prototypes that mirror real-world agentic applications and demonstrate how major aspects of our taxonomy can be structurally integrated in agentic protocols, such as the Model Control Protocol and Agent2Agent protocol. Ultimately, our study seeks to provide the groundwork for ensuring end-user privacy and autonomy is not lost in the newly arriving agentic world.</p>
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


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.27817v1">Privacy-preserving inference on hosted models: a learned input-embedding transform for frozen Qwen3.8-27B</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-10-20T08:08:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mahendra Roopa, Srikanth Roopa</p>
    <p><b>Summary:</b> Every prompt sent to a hosted language model is readable by whoever runs it. We study whether the prompt can remain on the client while the host receives transformed vectors that stand in for it. A language model converts text to vectors exactly once, with a public lookup table; we perform that step locally and pass the vectors through a small trained network (55.6M parameters) before they leave the perimeter. The host runs a frozen 27B model (Qwen3.8-27B) on the transformed vectors and never receives text or token ids. We train the transform against the frozen model as a fixed judge, combining a forward-KL utility term with an auxiliary term that pushes each vector away from its original direction. On 1,490 MMLU questions held out from training, the transform costs 1.5 points of accuracy (80.7% vs. 82.3%), breaking 68 of the 1,226 questions the unmodified model answers correctly (5.5%), while 30.1% of content tokens no longer decode to their original token under a nearest-neighbour lookup.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.27710v3">Privacy Accounting for Empirical Denoisers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2026-10-20T06:30:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> William Cheng, Dongjun Kim, Mijung Park</p>
    <p><b>Summary:</b> Diffusion models have emerged as the foundation of modern generative systems, yet their high memorization capacity raises privacy concerns. While differentially private (DP) training provides formal guarantees, it comes at a cost in sample quality. In this work, we study a complementary question: how much privacy loss is incurred during the sampling process itself? Directly analyzing modern neural denoisers is challenging because their sensitivity to a single training example is generally intractable. To overcome this challenge, we construct and analyze a clipped privacy-accountable empirical denoiser, a training-free estimator of the Bayes-optimal denoiser, whose per-step sensitivity can be computed explicitly, allowing each denoising step to be a Gaussian mechanism. This perspective enables privacy accounting under Gaussian DP when each training example contributes to each denoising step, and under $f$-DP trade-off functions when each generated sample uses a single randomly subsampled block of the training data. We report every $(\varepsilon, δ)$ guarantee as a certified upper bound from a privacy loss distribution accountant, and use a cumulant-based Edgeworth approximation as a fast diagnostic, characterizing where it is reliable and where it becomes anti-conservative. We also analyze the privacy loss along the denoising trajectory and show that it grows steeply near the critical window in which semantic content is formed. This observation motivates hybrid samplers that use the private empirical denoiser through the formative steps where it remains a faithful proxy for the neural denoiser, then switch to a public neural denoiser for the remaining refinement. Our results on CIFAR-10 and CelebA-64 show that the privacy of diffusion models depends not only on the training procedure, but also on sampling-time design choices such as subsampling, stopping time, and hybrid denoising.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.27615v1">DISTA-LP: Privacy-Preserving Distributed Linear Programming for Metric Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-20T04:28:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Michael Oluwole, Ruiyao Liu, Aleksander Stevens, Chenxi Qiu</p>
    <p><b>Summary:</b> Linear-programming (LP) mechanisms for metric differential privacy (mDP) enable fine-grained, task-aware utility control, but they are computationally expensive and become privacy-fragile in distributed settings: uploading user-specific LP coefficient matrices (e.g., distance and loss blocks) to a central solver can itself leak sensitive information. We present DISTA-LP, a privacy-preserving distributed mDP optimization framework that replaces raw coefficient uploads with compact surrogate parameterizations and releases only calibrated, perturbed parameter vectors, thereby reducing both upload-stage leakage and problem dimensionality. On the server side, DISTA-LP reconstructs approximate coefficients and solves a scalable mastersubproblem formulation via Benders decomposition. To certify end-to-end privacy, we introduce a probabilistic mDP (PmDP) auditor that empirically quantifies the privacy loss induced by parameter release, allocates the required privacy budget prior to optimization, and composes it with the downstream mechanism to obtain an end-to-end mDP guarantee. Experiments on large realworld road-network datasets (Rome, New York City, and London) show that DISTA-LP achieves near-zero mDP violation rates, substantially reduces computation time compared to monolithic and hybrid baselines, and matches or improves utility, thereby demonstrating stronger upload privacy and significantly improved scalability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.27470v1">Privacy-Preserving Personalized Federated Learning (PPP-FL) for Medical Imaging</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-10-20T01:41:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Md Morshedul Islam, Hossain Shahriar, Alfredo Cuzzocrea</p>
    <p><b>Summary:</b> Federated learning (FL) is a distributed machine learning paradigm that reduces transmission costs, mitigates cross-border data sharing restrictions, and enhances privacy by keeping raw data on local devices. Clients in FL systems train local models and share only updates, which are aggregated by a central server. While this setup limits direct data exposure, FL remains vulnerable to privacy attacks. Existing attack and defense strategies have largely been developed for centralized systems, and adapting them to FL introduces new challenges due to its unique architecture and training workflow. In this work, we first propose a model inversion attack on FL systems using Deep Convolutional Generative Adversarial Networks (DCGANs) in the context of large-scale medical imaging. Our method operates under realistic assumptions about the attacker's knowledge and capabilities. We then examine the effect of client-side differential privacy (DP) in mitigating privacy leakage and incorporate personalized FL to improve model performance under DP settings. Experiments on the Brain MRI ND-5 dataset show that DCGAN-based attacks can reconstruct semantically meaningful synthetic images, revealing significant risks to the privacy of training data. Applying DP reduces attack success but introduces an accuracy trade-off, which is further overcome by personalized FL at each client side. We also evaluate how different aggregation algorithms affect both attack vulnerability and defense effectiveness, underscoring the critical role of aggregation strategies. The proposed attack-and-defense framework is model-agnostic and applicable to a wide range of FL-based systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.27441v1">Privacy-Preserving Robustness-Guided Testing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Logic in Computer Science-662E9B">
  <p><b>Published on:</b> 2026-10-20T00:42:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Charles Koll, Houssam Abbas, Mike Rosulek</p>
    <p><b>Summary:</b> In industries like semi-conductors and aerospace, it is common for the design company to contract out part of the testing process to a Testing-as-a-Service (TaaS) company. In such a setup, both parties want to keep their intellectual property private (i.e. unknown to the other party): namely the design and its output traces for the designer, and the detailed correctness specifications for the tester. We demonstrate a practical way for conducting provably private TaaS using a cryptographically secure multi-party computation protocol. We do so for the common setup where the specification is in Signal Temporal Logic, and testing is done using robustness-guided falsification. Our implementation carefully separates the steps of falsification, and manages to be $\textit{maximally secure}$, in the sense that the parties learn the absolutely minimum necessary for falsification. For up to a 100-dimensional input search space, the generation of one test takes less than 80 msec, and the overhead of the privacy-preserving protocol is less than 6x. These numbers mean that privacy-preserving TaaS is practical, thus enabling TaaS in security-sensitive industries.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.27323v1">Steering Vision-Language Models for Visual-Contextual Privacy in Location Disclosure</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-10-19T21:41:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenyue Chen, Yuhan Cheng, Ruixin Yang, Ethan Mendes, Alan Ritter, Jingwei Sun, Hai Li, Yiran Chen</p>
    <p><b>Summary:</b> Vision-language models (VLMs) can infer sensitive information such as geolocation from subtle visual cues, creating privacy risks when responses disclose more detail than the visual context warrants. We study visual-contextual privacy in geolocation disclosure, where a VLM should reveal location information only at the granularity appropriate to the visual context depicted in the image. We first show that this contextually appropriate granularity is recoverable from pre-generation hidden states, even when generated responses are misaligned, with disclosure levels exhibiting an ordered structure along a common hidden-state direction. Motivated by this, we propose an inference-time route-and-steer framework: an ordinal granularity router maps visual-contextual privacy representations to a disclosure route, and a disclosure-level-conditioned steering module applies route-specific hidden-state interventions during decoding. Across four VLM backbones, our method improves visual-context-aware disclosure alignment, better balances over- and under-disclosure, and incurs only modest changes on general capability benchmarks. It further transfers to another dataset with a distinct data distribution and privacy-risk taxonomy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.27213v1">Profile-DP: Differential Privacy for User-Controlled Profile Release in Personalized LLM Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-10-19T19:44:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mingchen Li, Zifan Peng, Kewei Sha, Lavinia F Pieptea, Heng Fan, Junhua Ding, Meikang Qiu, Yunhe Feng</p>
    <p><b>Summary:</b> Personalized large language models (LLMs) increasingly rely on profile-conditioned inference, pairing public requests with rich, user-specific facts. This paradigm exposes the user profile itself, together with the user's explicit sharing preferences. We introduce Profile-DP, a policy-aware local differential privacy framework designed specifically for user-profile release in personalized LLM inference. Profile-DP provably bounds the release of user-withheld facts while treating public instructions, profile schemas, and authorized facts as public side information. By generating a privatized profile that composes with the public instruction prior to answer generation, our framework decouples formal privacy guarantees from downstream model behavior. We develop two finite-domain mechanisms satisfying Profile-DP: DP-SLOT independently perturbs protected attributes, while DP-BLOCK uses public semantic decisions to coordinate their release and jointly sample related attributes. A positive, public compatibility prior connects these attributes while preserving a profile-level privacy bound. On PEEP, DP-BLOCK leads the utility composite among DP methods at all 13 structured budgets and is closest to the ideal privacy--utility point in 18 of 26 format--budget settings under our composite weighting. Direct measurements reveal complementary strengths: DP-BLOCK discloses less, while DP-SLOT retains more authorized facts. These results make policy-aware profile release a practical basis for studying privacy and personalization.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.27026v2">BR-MoE: Budgeted Semantic Release for Privacy-Preserving Traffic Analytics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-10-19T15:00:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abdolazim Rezaei</p>
    <p><b>Summary:</b> Traffic cameras support useful analysis, but their outputs can reveal private information. Replacing images with text reduces direct visual exposure. It does not place a formal bound on disclosure. The published reinforcement learning and mixture-of-experts framework refines scene descriptions through relevance, coverage, and brevity rewards. It does not account for repeated releases under a fixed privacy budget. This paper proposes budgeted semantic release as an extension of that framework. Four scene experts first process isolated video chunks. Their outputs are mapped to a fixed, bounded semantic schema. A reinforcement learning controller selects which expert summaries to release and how much privacy budget to spend. The controller uses public task requests and previous private releases. A separate privacy filter enforces the total budget. Calibrated noise is added before the summaries are converted to text. Under explicit chunk isolation and bounded-event assumptions, the complete release transcript satisfies an event-level differential privacy bound. The design also supports reuse of previous summaries without new disclosure. An evaluation protocol covers traffic utility, privacy attacks, release freshness, and computational cost. Illustrative tables show the intended reporting format. They do not establish empirical gains. The proposed contribution is a task-aware release interface with auditable privacy accounting for repeated traffic descriptions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.26460v1">Differential privacy with adjustable preservation of multivariate relationships</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-19T14:11:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nicolas Ruiz</p>
    <p><b>Summary:</b> This paper derives an exact attenuation formula for multivariate cross-moments under differential privacy achieved through randomized response. From a proposed alternative formulation of randomization matrices compliant with differential privacy guarantees we show that, under attribute-level randomization and where the randomization of the whole distribution is characterized by Kronecker products, any cross-moment of the anonymized dataset involving distinct attributes is equal to the original cross-moment multiplied by attenuation parameters, themselves determined by the part of the overall privacy budget allocated to each attribute. This characterization enables explicit and transparent controls of multivariate relationships preservations in differential privacy through privacy budget allocation. A simple numerical illustration demonstrates that identical total budgets can yield substantially different covariance-preservation profiles. The results also make the multiplicative loss of higher-order interactions explicit and thus can support mechanism design guided by analytical priorities.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.27021v1">Reliable Estimation of Differential Privacy under Selection Bias</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2026-10-19T13:59:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Valentin Dorseuil, Meenatchi Sundaram Muthu Selva Annamalai, Jamal Atif, Olivier Cappé, Nicolas Papernot</p>
    <p><b>Summary:</b> Statistical privacy audits are essential for verifying the theoretical privacy guarantees of differentially private (DP) mechanisms. Auditors typically use Membership Inference Attacks (MIAs) to estimate a lower bound on the true privacy leakage of DP mechanisms at a specified confidence level, which should not exceed the theoretical privacy upper bound guaranteed by DP. However, we found that many auditing implementations in prior work introduce a selection bias when running MIAs, which leads to statistically invalid and overestimated lower bounds. Because most audits are not tight, this bias has thus far gone unnoticed: the estimated lower bounds remained well below the theoretical upper bounds. Nevertheless, accurately evaluating this lower bound is critical, as a flawed statistical assessment could lead to false alarms on correct mechanisms or an incorrect evaluation of the guarantee's tightness. This work employs tools from the statistical literature to correct this bias. We present an overview of the different correction methods and assess their respective advantages. Furthermore, we perform a comprehensive re-analysis of results returned by prior audit implementations and show that without statistical correction, these audits violate the theoretical upper bounds up to four times more often than their claimed confidence level implies. With correction applied, the resulting lower bounds are statistically valid, and violations occur at no more than the nominal rate.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.26385v1">Basis Selection For Analog Coded Computing Under Differential Privacy Constraints</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-10-19T13:35:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aaditya Sharma, Rimpi Borah, J. Harshan</p>
    <p><b>Summary:</b> In analog coded computing, encoding basis functions are typically chosen to guarantee exact reconstruction and improve numerical stability. However, the same basis functions also determine the statistical geometry of the observations available to colluding workers, and hence directly influence the privacy of the underlying data. This suggests that basis selection should not be viewed solely as a reconstruction or numerical conditioning problem, but rather as a joint privacy and accuracy co-design problem. Motivated by this observation, we revisit Analog Lagrange Coded Computing (ALCC) and show that the full orthogonality constraints imposed by the conventional Lagrange basis are stronger than what is required for exact recovery. We retain only the interpolation constraints necessary for the data bearing basis functions and require the noise bearing basis functions merely to vanish at the data recovery points. This yields a parameterized family of generalized polynomial encoding bases that preserves exact reconstruction while introducing additional design degrees of freedom. We then derive a basis-dependent characterization of differential privacy for colluding workers and formulate a privacy-calibrated numerical optimization problem that jointly selects the data and noise basis functions to reduce reconstruction error while satisfying a prescribed \((ε,δ)\)-DP requirement. The resulting framework therefore treats the encoding basis itself as a privacy-design variable, rather than selecting a fixed closed-form basis a priori. The same design philosophy is also compatible with alternative privacy metrics such as mutual-information leakage. Numerical results show that, at the same privacy level, optimized basis functions substantially reduce floating-point reconstruction error relative to conventional ALCC.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.25937v1">RAGLeak: Supply-Chain Privacy Backdoors in Retrieval-Augmented Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-19T07:32:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuchen Chen, Wei Cheng, Yuan Xiao, Junda He, Jieke Shi, PingPing OuYang, Quanjun Zhang, Chunrong Fang, David Lo, Zhenyu Chen</p>
    <p><b>Summary:</b> Retrieval-Augmented Generation (RAG) enables large language models to access external knowledge during inference, but its reliance on external knowledge bases also introduces new attack surfaces. Existing data extraction attacks against RAG systems rely on either prompt injection, which heavily depends on the generator's instruction-following capability, or backdoors that reproduce or paraphrase retrieved documents but struggle to balance extraction fidelity and stealthiness. In this paper, we propose RAGLeak, a supply-chain privacy backdoor attack that decouples information leakage from direct textual exposure. When triggered, the generator reversibly obfuscates retrieved private documents for high-fidelity recovery by an auxiliary LLM. Across three model families and three application domains, RAGLeak achieves up to $100\%$ ASR with limited impact on benign utility and at most a $10$-percentage-point ASR drop under representative detection-based defenses. The backdoor remains effective after clean fine-tuning and across model scales and versions, revealing an underexplored supply-chain privacy risk in RAG systems. The source code is available at https://anonymous.4open.science/r/RAGLeak-4B67.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.25773v1">When Care Expands and Control Declines: Understanding Digital Privacy in End-of-Life Care</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-10-19T04:38:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yibo Meng, Bingyi Liu, Lionel Z. Wang, Zhuoran Lu</p>
    <p><b>Summary:</b> Terminally ill patients generate extensive digital health data through hospital portals, physiological monitoring devices, consumer health applications, and end-of-life care platforms. Yet their ability to control this data is systematically undermined by the structural conditions of terminal care. Through semi-structured in-depth interviews with 21 terminally ill patients, 11 family caregivers, and 8 physicians recruited from tertiary hospitals, this study examines the digital privacy circumstances and subjective attitudes of patients in end-of-life contexts. Thematic analysis reveals five structural dimensions of digital privacy challenge: continuous bodily digitization without meaningful informed consent; cognitive decline driving involuntary proxy control of accounts; inferential data generation exceeding patients' epistemic boundaries; dissolution of individual privacy boundaries amid relational network restructuring; and the absence of institutional governance over post-mortem data. Patient privacy attitudes span three profiles: fundamental absence of privacy awareness, sustained active management under severe tool constraints, and perception of problems followed by resigned abandonment. Interviews with caregivers and physicians reveal benevolent substitution in the name of care needs, expansion of access beyond the initial task, and unresolved boundaries under absent institutional guidance. These findings reveal a compounding privacy vulnerability unique to end-of-life contexts and call for privacy-by-design principles, granular permission mechanisms, and institutional governance frameworks tailored to the needs of dying patients.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.25639v1">Privacy-Preserving Robust Monitoring of Dense-Time Temporal Logic</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Logic in Computer Science-662E9B">
  <p><b>Published on:</b> 2026-10-19T01:32:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Charles Koll, Mike Rosulek, Houssam Abbas</p>
    <p><b>Summary:</b> Motivated by the use of third-party testing, this paper presents a privacy-preserving implementation of the robustness monitoring of Signal Temporal Logic (STL). STL is a specification language for systems whose output traces have real-valued timestamps -- most prominently, cyber-physical systems. Its robust semantics, which assign real rather than binary truth values, are an essential ingredient of systems testing and runtime monitoring. In a number of system testing scenarios, the designer and the tester are separate parties. This testing-as-a-service model is common in software, avionics, and semiconductors, and is growing in importance in the red-teaming of machine learning models. In such a model, the designer seeks to preserve the privacy (or secrecy) of its design, while the tester seeks to preserve the privacy of its collateral, including the detailed specification suite. This paper presents a secure multi-party implementation of the robust semantics using arithmetic circuits. This implementation allows one party, which provides a secret trace, and a second party which provides a secret formula, to jointly compute the robustness without either party being able to learn the other party's secret input. We present a number of algorithmic modifications to the robustness computation to enable an efficient multi-party robustness computation. We also present new, semi-linear, robust semantics for STL that take advantage of the efficiencies of arithmetic circuits. The experimental results demonstrate that not only is this privacy-preserving monitor efficient on its own, but also that it can be used in a testing loop without affecting the speed at which bugs are found during robustness-guided system testing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.25636v1">Formalization of Rényi Differential Privacy in Isabelle/HOL (Draft version)</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Logic in Computer Science-662E9B">
  <p><b>Published on:</b> 2026-10-19T01:27:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tetsuya Sato</p>
    <p><b>Summary:</b> Differential privacy (DP) is a gold-standard definition of privacy designed to evaluate the privacy guarantee of databases. Rényi differential privacy (RDP) is an important variant of DP that gives tight evaluations of machine learning algorithms. These formulations are easy to understand, but evaluating privacy for actual databases is complicated. Even a small change in the database can break its privacy, and evaluations of DP and RDP themselves are complicated. In particular, RDP evaluations in recent studies have become much harder. Therefore, formal verification of them has been studied for over a decade.
  In this paper, we propose an Isabelle/HOL library for formalizing Rényi differential privacy in a general setting. We first formalize RDP for continuous distributions. As a technical basis, we formalize several properties of convex functions and $f$-divergences for nonnegative convex functions. We formalize basic properties of RDP, conversion laws from RDP to DP, the moment accountants in DP, and the Gaussian mechanism and its RDP. Finally, we discuss the stochastic gradient descent mechanism with Gaussian noise and formalize a rough evaluation of its RDP and DP.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.25286v1">PRICE: Privacy-Preserving Image Classification in Mobile Edge-Cloud Computing with Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-18T14:06:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Duc-Huy Nguyen, Bui Duc Manh, Chi-Hieu Nguyen, Dinh Thai Hoang, Diep N. Nguyen, Van-Dinh Nguyen, Quoc-Viet Pham</p>
    <p><b>Summary:</b> Cloud-assisted image classification enables many mobile AI applications, but transmitting raw images to the cloud raises significant privacy concerns. Homomorphic encryption (HE) allows computation over encrypted data; however, existing end-to-end HE-based inference pipelines incur prohibitive latency and computational overhead, limiting their feasibility for latency-sensitive mobile systems. This paper addresses how to enable efficient encrypted image classification in mobile edge-cloud environments without sacrificing accuracy. We propose PRICE, a three-tier edge-cloud architecture that partitions deep neural network inference between a trusted edge and an untrusted cloud. The edge performs lightweight feature extraction in plaintext, while only compact embeddings are encrypted using the Cheon-Kim-Kim-Song (CKKS) scheme and offloaded to the cloud for encrypted final-layer inference. This design avoids homomorphic evaluation of deep backbone layers, significantly reducing computation depth, ciphertext size, and end-to-end latency. To further improve efficiency, we develop RowHyDiag, a row-packed hybrid diagonal encoding with hoisted-rotation-aware encrypted matrix-vector computation, which minimizes rotation operations and improves slot utilization. Extensive experiments on real devices across five datasets demonstrate that, under the evaluated 128-bit-security configurations, RowHyDiag achieves up to 31.8$\times$ faster cloud inference, 85.3$\times$ fewer rotations, and 83.0$\times$ lower setup payload than the conventional Halevi-Shoup diagonal method. RowHyDiag also outperforms the PEGASUS linear-transformation baseline, providing 1.1-4.5$\times$ faster cloud inference and 1.2-3.4$\times$ lower setup payload. The results show that PRICE enables deployment-ready, low-latency encrypted inference for mobile edge-cloud systems under a trusted-edge threat model.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.25161v1">Indistinguishable Agents: Training Agent Privacy as Twin-World Indistinguishability</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-10-18T10:37:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiaming He, Guanyu Hou, Yi Yu, Xudong Jiang</p>
    <p><b>Summary:</b> LLM agents search, shop and send messages for their users, and every action is seen by some party. Existing privacy training rewards agents for not mentioning protected items, yet an observer can infer a private fact from what the agent does. Since an observer learns a fact only if its view changes with the fact, we propose \methodfull (\method), which trains on twin worlds that differ only in the private fact. A frozen distinguisher scores each observer's view by its log-likelihood ratio for the true world, and paired GRPO trains the agent on task success minus this ratio. We prove that this objective controls the Bayes success of every observer on every channel. On shopping and messaging tasks \method removes the leakage that disclosure judges and query-level rewards miss, while the agent still completes its tasks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.25094v1">Towards End-to-End Privacy-Preserving AI for Real-Time ECG Monitoring</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-18T07:58:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Beyazit Bestami Yuksel</p>
    <p><b>Summary:</b> Healthcare artificial intelligence is shifting from centralized archives toward distributed pipelines that combine wearables, edge processing, cloud analytics, and multi-institutional learning. In this regime, electrocardiogram (ECG) streams cross multiple trust boundaries, so privacy cannot be reduced to a single transmission control. Existing privacy-enhancing technologies typically secure isolated stages and leave gaps between acquisition, analysis, and institutional collaboration.
  This doctoral research develops a unified lifecycle framework for end-to-end privacy-preserving ECG AI. Rather than introducing another privacy mechanism, it orchestrates complementary privacy-enhancing technologies across the clinical ECG lifecycle, allocating each mechanism to the trust boundary where its security, computational, and operational properties are most appropriate. Three interoperable modules instantiate the framework: AES with CKKS-based homomorphic statistics for secure monitoring; adaptive chaotic protection for low-latency edge transmission; and federated learning with homomorphic aggregation under heterogeneous partitions. Across prototype monitoring, signal-security analysis, and simulated collaboration, the programme shows that privacy layers can be composed without collapsing diagnostic utility, while exposing overhead and fidelity limits that constrain clinical translation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.24841v1">PCHMR: Empowering and Benchmarking Human Mesh Recovery in Privacy-Constrained Real-World Settings</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-10-17T19:46:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zeyu Cao, Qingxuan Wu, Zhiyang Dou, Rui Xu, Yuan Liu, Javier Fernandez-Marques, Nicholas D. Lane, Taku Komura, Wenping Wang</p>
    <p><b>Summary:</b> Fine-tuning directly on user-side data is an effective way to improve the performance of widely adopted data-driven human mesh recovery (HMR) models. However, doing so for existing HMR methods often assumes aggregating user-side data from real-world HMR-deployed devices to a central training server, posing a significant privacy risk as sensitive human images are transmitted. How can human mesh recovery be evaluated and improved in privacy-constrained real-world settings? We study this question through a benchmark in which state-of-the-art HMR models are trained with federated learning and a secure-aggregation variant, neither of which centralizes raw images, and evaluated across a wide range of client-scale and data-heterogeneity settings. We document that common HMR training pipelines are built around centralized data access and quantify how representative HMR backbones behave when that assumption is removed. Furthermore, to study the data bottleneck of privacy-constrained HMR training, we propose DePoser, a local annotation and fine-tuning pipeline enhanced with depth foundation models, with which collaboratively trained HMR models can be locally tailored to the end user's distribution. On in-the-wild data, fine-tuning on DePoser annotations improves personalization accuracy, measured against DePoser-generated pseudo-ground truth. This benchmark aims to support future work on privacy-constrained HMR models and their real-world deployment and evaluation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.24748v1">Collaborative Hand Drawing to Conceptualize Usable Privacy and Security Research Problems: Students' Perspectives (Extended Version)</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-10-17T15:30:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Eman Alashwali, Joud Alraimi, Maryam Almaghrabi</p>
    <p><b>Summary:</b> In this paper, we explore students' perspectives on incorporating hand drawing to conceptualize usable privacy and security research problems. We surveyed 64 female students who participated in an in-class collaborative hand drawing activity to conceptualize usable privacy and security research problems as part of a group-based student research project on usable privacy and security in an information and computer security course for undergraduate students. Our survey responses suggest that students perceived the drawing exercise positively. That is, they found it helpful in several aspects, enjoyable, and they recommend it to other students taking the course. The students also said that they would like to have such an exercise in other courses, such as Principles of Human-Computer Interaction and Fundamentals of Data Networks. Only three students mentioned downsides of the exercise, namely doubts about their drawing skills. Our results provide useful insights for educators seeking to enhance the student learning experience.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.24389v1">From Neglect to Resignation: Understanding the Evolution of Mobile Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-10-17T02:44:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yibo Meng, Ziqi Liu, Lionel Z. Wang, Shuning Zhang, Xiaolan Ding</p>
    <p><b>Summary:</b> This decade-long longitudinal qualitative study follows 31 smartphone users in China across four interview waves (2014-2023) to examine how mobile privacy understanding evolves alongside shifting computing infrastructures. Findings reveal three stages shaped by distinct interactional mechanisms: early functional acceptance of permission-based data access, growing vigilance triggered by behavioral tracking feedback loops, and eventual resignation as AI-driven inference made ecosystem-level profiling feel inescapable. Rather than a stable attitude, digital resignation emerges through cumulative infrastructure exposure, as each new system layer retroactively reinterpreted earlier permissions and exhausted users' capacity for self-management. The study challenges permission-centric design assumptions and proposes inference visibility, context isolation, and automated privacy agency as system-level responses.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.24359v1">Can Agents Keep Secrets They Were Never Told? Benchmarking Latent Privacy Risks Across Sessions with MemJoin</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-17T01:20:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qishun Yang, Shu Yang, Difei Xu, Di Wang, Meng Ding</p>
    <p><b>Summary:</b> To support sustained interactions and personalized assistance, agents use long-term memory to retain and combine user information across sessions. Reusing such memories can lead an agent to state a sensitive relation while completing an ordinary task that does not require it. The relation to protect and the combination of clues that reveal it may remain hidden at memory write time, when later records and tasks are still unknown. In this paper, we introduce MemJoin, a privacy benchmark of 288 synthetic analysis cases in which the complete history entails a sensitive relation, but every individual session is insufficient. We evaluate six memory systems with the same answer-generating model, alongside full-history and no-history controls. Each system writes and updates memories in session order and later retrieves context for an ordinary task, while target annotations remain with the evaluator. We separately check which target attribute values appear in stored records and retrieved context, and whether the final answer states the complete, person-linked relation. In a separate paired test on a prespecified subset, removing shared identifiers and other connecting clues can change complete-relation output while all checked target attribute values remain visible. These findings show why checking attribute visibility alone is insufficient to evaluate what records from different sessions reveal together.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.24278v1">Dataset Inference for Data Provenance and Privacy Auditing in Tabular Foundation Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-16T22:16:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dariush Wahdany, Jesse Cresswell, Naiqing Guan, Atiyeh Ashari Ghomi, Franziska Boenisch, Adam Dziedzic</p>
    <p><b>Summary:</b> Tabular foundation models (TFMs) are increasingly deployed through black-box APIs and trained on large collections of real-world tabular datasets. As this training paradigm becomes more widely adopted, private or proprietary datasets may be incorporated into pre-training corpora, yet there are currently no dedicated methods for determining whether a given tabular dataset was used to train a TFM. As a solution, we introduce the first dataset inference method for TFMs, aiming to infer whether a suspect dataset was part of a model's pre-training data. We systematically analyze a broad collection of candidate signals that can be observed from a black-box TFM via input manipulation and find that individual signals provide only weak evidence of training data membership. However, by combining multiple complementary signals, we can infer dataset membership for several state-of-the-art TFMs trained on real tabular data, achieving up to 0.99 ROCAUC dependent on the TFM. We then study factors that influence dataset identification, including pre-training data composition, model capacity, and the use of real vs. synthetic data. Our results show that our dataset inference method is a practical auditing tool for detecting privacy leakage and the use of proprietary datasets in TFMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.23798v2">Task-aware Kernel Stein certificates for Rényi differential privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-16T17:24:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Leoni Carla Wirth, Tara Trauthwein, Gesine Reinert</p>
    <p><b>Summary:</b> Rènyi differential privacy, based on Rènyi divergence, has become a notion of choice for privacy guarantees. However, outside the Gaussian setting, Rènyi divergence can be difficult to compute. In particular, Rènyi differential privacy guarantees that exploit task-specific information, as in Rènyi Pufferfish privacy, can be challenging. Here we use kernel Stein discrepancies based on escort distributions to provide certificates for Rènyi differential privacy. By designing the kernel to focus on the relevant privacy directions, we also derive task-aware privacy certificates. We provide exact identities for Gaussian and Laplace mechanisms and bounds for exponential mechanisms, with separate task-aware guarantees. A real data set example illustrates how the protected comparison set and the released subspace jointly determine the resulting certificates.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.23668v1">TUPLE-Bench: Evaluating and Mitigating Privacy-Utility Trade-offs in Typed Decision Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-10-16T16:00:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yiqu Yang, Qiaoyuan Zheng, Yang Tian, Yu Fan, Elliott Ash</p>
    <p><b>Summary:</b> Typed decision models often return more than a selected category. They also expose probabilities for each candidate and, sometimes, a separate confidence score. These fields support downstream decisions but may reveal information beyond a recipient's authorization. We introduce TUPLE-Bench (Typed decision models' Utility and Privacy Leakage Evaluation Benchmark), a benchmark of paired synthetic cases in which recipients may learn a coarse operational category but not its fine-grained cause. Across nine models, instructions to withhold the cause fail to protect it: 91.88%-99.93% of responses reveal the cause through direct selection or residual scores. Even when causes are excluded from the candidate set, full outputs enable 62.85%-75.35% recovery on held-out cases, compared with 51.04%-57.64% using only the selected category (50% chance). Full outputs also reduce mean downstream cost in all 27 model-task comparisons. However, confidence fields increase leakage without consistently reducing cost. We further introduce workflow-constrained privacy quantization (WCPQ), which reduces secret recovery while preserving the behavior and cost of specified downstream workflows. Our findings highlight the need to audit decision interfaces field by field and workflow by workflow.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.22800v2">Veil-Then-Reveal: Protecting PII Privacy via Reversible Pseudo-Anonymization in Zero-Trust User--LLM Interaction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-10-16T01:24:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohamed Elmahallawy, Mohamed Shaaban, Thomas E. Carroll</p>
    <p><b>Summary:</b> Large language models (LLMs) increasingly process sensitive documents and personal information, yet sending prompts containing personally identifiable information (PII) to remote providers exposes data subjects and organizations to risks from logging, retention, model training, and unintended disclosure. Existing anonymization methods often mask or remove PII, while conventional encryption eliminates the lexical and structural cues needed for effective LLM processing. We present Veil-then-Reveal (VtR), a user-side PII pseudo-anonymization framework for privacy-preserving LLM interaction under a zero-trust threat model. VtR treats remote LLM providers as untrusted and sends only pseudo-anonymized prompts, keeping plaintext PII on the user. VtR first detects PII and replaces it with realistic, same-type, in-vocabulary surrogates before prompts leave the user's device, preserving their linguistic and structural properties. It combines format-preserving encryption (FPE) for structured PII, such as phone and credit-card numbers, with a keyed-hash dictionary and secure vault for semantic PII, such as names, locations, and organizations. Session-specific mappings provide cross-session unlinkability, while user-side restoration reversibly replaces surrogates with their original values in LLM responses. We further introduce a rank-class FPE strategy for dates that preserves format and ambiguity while reducing cipher evaluations. Evaluation on three datasets containing 11,322 annotated PII instances achieves 97.9% detection recall, 95.2% protection of detected values, and 99.9% round trip; 100% of echoed surrogates end-to-end round-trip restoration.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.22722v2">LLM-Attack Suite: A Unified Red-Team Framework for Privacy Evaluation of Split and Distributed LLM Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-15T22:53:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Georgios Politis, Evangelos Pappas</p>
    <p><b>Summary:</b> Split language models keep input text on a client but send intermediate representations to a server. Attacks can reconstruct text from these messages. Comparing privacy evaluations is difficult when attackers see different messages, know different model weights or use different datasets and recovery measures. We present LLM-Attack Suite, a framework that records these choices and lets researchers check, compare and extend an evaluation. Compatible attacks reuse recorded messages, and their predictions are saved for independent scoring. The scoring rule requires a linked undefended reference before a defence can pass. Reports also identify attacks that remain untested. In a controlled GPT-2 experiment, adding gradients returned during training increased token recovery from 94.20% to 97.38% and exact-document recovery from 13.71% to 37.77%. The 95% interval for the token gain lay above the two-percentage-point threshold fixed before testing. This experiment is shared with a companion study; here it tests how the evaluation responds to a change in attacker access. Further studies measure how corpus choice and compression defences affect recovery, compare an adapted published attack with its reference implementation, and test the measurement code. The framework reports implementation checks separately from measured attack effectiveness. Each privacy claim should state the attacker, dataset and scoring rule, report its controls and identify untested attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.22659v1">Exploring The Empirical Privacy Landscape of Synthetic Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-10-15T21:22:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zihao Zhao, Avi Schwarzschild, Casey Meehan, Katherine Lee, Zhili Feng, Dylan Sam</p>
    <p><b>Summary:</b> Methods for training language models on sensitive data differ in how they balance capability gains against the risk of leaking private information. In this paper, we present a controlled comparison of data-level and training-level interventions for navigating the capability-privacy tradeoff on synthetic medical records with canaries to probe for leakage. Direct finetuning performs best on capability metrics but leads to the most privacy leakage, while DP-SGD reduces leakage at substantial cost to capabilities. Generating synthetic data from these records offers a more favorable balance, particularly when guided by a uniqueness-aware instruction to replace private details. Relative to naive paraphrasing, privacy-aware rewriting improves privacy protection across a variety of different rewriting models. We also find that more capable rewriting models generally reduce the risks of downstream privacy leakage, although held-out fit does not improve monotonically and increased test-time compute yields inconsistent gains. Overall, these results highlight privacy-aware rewriting as a promising direction for achieving a more favorable trade-off between capabilities and empirical privacy compared to other training-level methods, and our evaluation framework supports comparisons of future models and methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.22278v1">Subgraph Counting with Local Node Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-15T17:39:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sofya Raskhodnikova, Adam Smith, Connor Wagaman, Anatoly Zavyalov</p>
    <p><b>Summary:</b> We study the problem of approximately counting subgraphs under local node differential privacy (LNDP), a recently introduced model that enforces strong privacy guarantees in analyses of distributed social networks. We design a noninteractive $(\varepsilon,0)$-LNDP algorithm that, given any public $k$-node template graph $H$, counts occurrences of $H$ in a sensitive undirected $n$-node graph with additive error $O(n^{k-\frac{1}{2}}/\varepsilon^{k-1})$, for any constant $k$. We complement this algorithm with a lower bound showing that every noninteractive $(\varepsilon,δ)$-LNDP algorithm for counting copies of any $k$-node template graph with maximum degree greater than $1$ must have error $Ω(n^{k - \frac{1}{2}})$. Thus, our algorithm achieves optimal error for counting constant-size subgraphs, up to $\mathrm{poly}(1/\varepsilon)$ factors.
  Our results substantially expand the types of network statistics known to be approximable under LNDP: prior work considered only functions of the degree distribution. In addition, our lower bound yields the first known $\mathrm{poly}(n)$ gap between central and local node differential privacy when accuracy is required for all input graphs. Previous separations either only involved $\mathrm{poly}(1/\varepsilon)$ factors or only applied to promise problems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.21799v1">Behavioral Forgetting Is Not Privacy in Machine Unlearning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-10-15T12:48:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tyler Lizzo, Larry Heck</p>
    <p><b>Summary:</b> Machine unlearning aims to remove targeted information from large language models, but existing evaluations often measure forgetting only on a designated benchmark distribution. We argue that such behavioral forgetting is an insufficient standard for privacy-oriented unlearning, and that evaluation should instead test whether forgetting persists across the access paths through which the same information may be recovered. We demonstrate this with a controlled case study of cross-lingual querying: across multiple multilingual model families, forgetting varies substantially when semantically equivalent information is queried in different languages and scripts. A single access path is therefore enough to expose a real gap between behavioral forgetting and information inaccessibility, motivating broader evaluation of access-path generalization and adversarial recoverability alongside in-distribution forgetting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.21547v1">Federated Art Chase: Privacy Leakage and Data Poisoning in Federated Fine-Tuning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-15T09:11:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vasileios Perifanis, Nikolaos Pavlidis</p>
    <p><b>Summary:</b> Federated learning (FL) is increasingly used to adapt a pretrained, centrally fine-tuned model to data that remain on user devices, beyond training a model from scratch. In this report, prepared for the 4th Federated Machine Learning International Summer School, we study the privacy and integrity of this approach with a reproducible pipeline. An ImageNet-pretrained MobileNetV4-Conv-Small model is fine-tuned centrally on ten Quick, Draw! classes (97.50% test accuracy) and then adapted with head-only FedAvg over ten non-IID clients, which raises client training accuracy from 90.34% to 91.49% while preserving global accuracy. We evaluate four adversarial scenarios. First, from a single one-step client update, an honest-but-curious server recovers the complete private label set, but its reconstructions follow class prototypes rather than the private drawings (mean SSIM 0.130). Second, from a one-round FedAvg aggregate, label-count recovery falls from 87.5% with one client to 75.0% with five and ten clients, below the 80.0% of an uninformed uniform guess. Third, under FedAvg, a backdoor injected by 30%, 50%, and 100% of the clients reaches an attack success rate (ASR) of 21.9%, 31.3%, and 54.7% at a cost of at most 0.8 percentage points of clean accuracy, whereas label flipping is effective only when most of the source-class data are relabeled. Fourth, FLTrust with a root set retained from centralized fine-tuning lowers the backdoor ASR to 1.8% and 4.0% at 30% and 50% malicious clients and the label-flipping ASR from 12.6% to 0.8% without measurable clean-accuracy loss, but provides no protection when every client is malicious. The report closes with a live session in which participants draw, fine-tune, and poison the model through Indigma's FedMaestro orchestrator. Code and executed notebooks, runnable on Google Colab, are at https://github.com/Indigma-Innovations/fl-summer-school.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.21361v1">Hierarchical Building-Floo-Room Framework for Privacy-Preserving Autonomous Delivery in Large-Scale Buildings</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E">
  <p><b>Published on:</b> 2026-10-15T06:39:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xu Xiaoji, Luo Rui, Chen Jinhua, Xiang Changying, Zhang Leihan, Liao Zhongyuan</p>
    <p><b>Summary:</b> Autonomous delivery in large scale buildings requires coordinated planning across multiple spatial levels, including building, floor, and room, while ensuring scheduling efficiency. Existing methods often focus solely on algorithmic development, neglecting integration with physical robotic platforms, and rarely validate performance in real world scenarios. Many approaches also overlook hierarchical building structures and room level privacy constraints, limiting practical applicability. To address these challenges, this paper presents a hierarchical delivery framework based on a Building-Floor-Room abstraction, which decomposes the problem across multiple levels to significantly reduce optimization complexity. We formulate a building aware extension of the capacitated vehicle routing problem (CVRP) that explicitly models inter building and inter floor connectivity, room level access constraints, and privacy sensitive areas, enabling globally feasible and privacy compliant task assignment and routing. Based on this hierarchical model, the framework can evaluate delivery efficiency across different building layouts and optimize depot placement for specific configurations. At the execution level, we introduce a novel hardware design for non interactive, privacy preserving delivery, supported by reachability aware distances and a closed loop mapping, localization, and navigation system, ensuring consistency between planned routes and physical navigation. The proposed framework is validated on a real multi sensor robotic platform, demonstrating reliable multi floor delivery with improved path rationality and overall efficiency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.21333v2">QuasiLeak-Bench: Evaluating LLM-Based Privacy Detectors on Policy-Conditioned Quasi-Evidence Group Recovery</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-15T06:20:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yufan Zhu, Yangfan Jiang, Yang Fei, Shizheng Hou, Shubhankar Mohapatra, Xiaokui Xiao</p>
    <p><b>Summary:</b> Natural language messages often contain quasi-identifiers that are weak in isolation but can jointly reveal an individual's private attributes. We call such a jointly revealing set of cues a quasi-evidence group. Existing privacy benchmarks focus on explicit identifiers, attribute inference, or task-driven disclosures, leaving inference from quasi-evidence groups largely unmeasured. In practice, whether exposing such a quasi-evidence group violates privacy also depends on sender-specified disclosure policies. We introduce QuasiLeak-Bench, a benchmark for policy-conditioned quasi-evidence group recovery, which evaluates whether detectors recover complete quasi-evidence groups and flag the disclosures the given policy prohibits. To obtain reliable ground truth at scale, a reverse-construction pipeline first selects weak quasi-identifiers, composes them into quasi-evidence groups verified to jointly reveal a target attribute, and generates documents around this evidence, followed by automated quality control. Experiments show that existing privacy detectors transfer poorly to QuasiLeak-Bench, and locally deployable LLM-based detectors fall far behind proprietary models, mainly because they miss most quasi-evidence groups altogether. However, a 4B model fine-tuned on our training split surpasses the strongest prompted model on held-out documents, showing that the task is learnable.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.21308v1">PocketTSLM: Deploying an On-Device Soft-Prompt Time-Series Language Model for Privacy-Preserving Smartphone Reasoning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-10-15T05:56:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Max Rosenblattl, Nikhil Krishnaswamy, Leon Nissen, Manuel Milling, Nicolas Zumarraga, Ning Wang, Thomas Kaar, Robert Jakob, Björn W. Schuller, Elgar Fleisch, Patrick Langer, Paul Schmiedmayer</p>
    <p><b>Summary:</b> Consumer phones and wearables increasingly collect physiological time-series data, yet most mobile systems treat these streams as summaries or text rather than as temporal evidence. This representation is poorly matched to personal health systems that need to retrieve, route, or summarize sensor evidence while preserving temporal structure. Cloud-hosted time-series language models avoid smartphone limits, but they repeatedly move sensitive physiology off the device and add latency and per-query compute cost. Mobile model alternatives that aggregate time-series data into statistical features or serialize raw samples as text either compress temporal structure or exhaust the context and memory budgets of small on-device models. We present PocketTSLM, a mobile-native deployment of OpenTSLM SoftPrompt, the soft-prompt variant of the OpenTSLM time-series language model. PocketTSLM runs fully on a consumer smartphone by injecting encoded time-series windows as embeddings instead of tokenizing time series as text. A numerical parity protocol verifies identical greedy-decoded token sequences between the Swift port and a Python reference using Apple's MLX machine-learning framework. Answers also match the PyTorch reference, although rationale wording can differ. An on-device context-economics benchmark compares the soft-prompt path with a text-serialized baseline on the same backbone. In our benchmark format, soft-prompting uses approximately 12 times fewer time-series tokens and reduces prompt-prefill cost. PocketTSLM processes 30-second Sleep-EDF electroencephalography clips for sleep staging and a 1,000-sample (10 s) 12-lead electrocardiogram clip from ECG-QA. In comparison, text-serialized baselines exceed the phone's context or memory budget at longer time-series windows. All inference runs entirely on the device, with no health data transmitted during inference.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.21245v2">From One Query to Many: A Critical Survey of Privacy Accounting in RAG</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-15T04:41:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhiyuan Zhang</p>
    <p><b>Summary:</b> Retrieval-augmented generation (RAG) enables large language models to leverage external knowledge but introduces privacy risks when the retrieved corpus contains sensitive information. Differential privacy (DP) offers formal protection, yet interpreting and comparing privacy guarantees across existing DP-RAG methods remains challenging. In particular, a privacy budget reported for a single response does not directly characterize privacy loss over repeated queries, and even identical values of $\varepsilon$ may represent different guarantees depending on the protected data unit, accounting horizon, and observable outputs. This survey critically examines how privacy accounting evolves from single-query generation to multi-query RAG systems. We categorize existing approaches into query-time privatization, multi-query accounting, and one-time corpus privatization. We analyze their underlying assumptions and privacy--utility trade-offs. Rather than ranking methods by $\varepsilon$ alone, we propose a framework that interprets a DP-RAG guarantee along three dimensions: privacy granularity, accounting scope, and release boundaries. We conclude that an $\eps$ is a claim only together with the three slots: the protected unit, the accounting scope, and the release boundary.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.21048v1">SHIP: Structured and Hierarchical Insight with Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-15T00:48:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kai Chen, Guisi Ni, Albert Cheu, Kassem Fawaz, Yuzheng Hu, Ryan McKenna, Peter Kairouz</p>
    <p><b>Summary:</b> Extracting insights from textual data while protecting user privacy is increasingly important. Existing methods produce private insights in diverse forms for different analytical purposes, making their utility difficult to assess and compare. In this work, we formulate differentially private (DP) insights as reusable representations for answering analytical queries, providing a common basis for utility assessment. Answering these queries, however, requires fine-grained details and cross-attribute statistics that existing representations may omit. To capture this information, we introduce Structured and Hierarchical Insight with Privacy (SHIP), which automatically maps queries to attributes, builds a hierarchical hybrid taxonomy, and releases a DP synthetic table for further analysis. We also develop an evaluation protocol based primarily on QA performance and structured fidelity. Our experiments demonstrate SHIP's strong performance on both measures relative to existing private insight baselines, while identifying queries that remain challenging for structured representations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.21033v1">Efficient Agnostic Learning of Univariate Densities Under Local Differential Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-15T00:08:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohammad Afzali, Hassan Ashtiani, Sivan Sabato</p>
    <p><b>Summary:</b> We propose a general framework for non-interactive locally differentially private (LDP) learning of structured univariate distributions that can be approximated by piece-wise polynomials. This gives the first sample-efficient LDP learners for several distribution classes, including mixtures of log-concave distributions, such as Gaussian mixture models (GMMs). These learners also provide agnostic guarantees and are computationally efficient. We also prove a lower bound for learning GMMs under LDP, improving on the standard pure-DP packing lower bounds of Bun et al. [BKSW19]. To obtain our general learning framework, we develop an efficient non-interactive LDP algorithm for synthetic data generation over large domains, which may be of independent interest. We then use it together with a deterministic adaptation of the non-private piecewise polynomial learner of Acharya et al. [ADLS17].</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.20796v2">Privacy-Preserving Text Inference for Health-Misinformation Classification and Semantic Retrieval</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-14T18:41:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jasleen Kaur, Chloé Cachet, Koray Karabina, Jean Belo Klamti, Philippe Lamontagne</p>
    <p><b>Summary:</b> Health-misinformation analysis presents a dual challenge: misleading claims can affect public well-being, while systems designed to detect them may expose sensitive user-submitted text. This motivates privacy-preserving inference for public-health applications in which user queries may contain confidential medical information and trained models and reference databases are maintained on organizational servers. We design a privacy-preserving text inference framework based on CKKS homomorphic encryption for health-misinformation classification and semantic retrieval. The classification pipeline fuses BioBERT embeddings, PCA-reduced MPNet embeddings, and SVD-reduced TF-IDF features, while the retrieval pipeline combines MPNet embeddings with ISCC-SCT semantic fingerprints through late fusion. We evaluate predictive performance and benchmark plaintext versus ciphertext-based execution. The hybrid classifier achieved an accuracy of 0.971 and a macro-F1 score of 0.950, with identical reported metrics under plaintext and ciphertext-based inference. The hybrid late-fusion similarity model achieved a Pearson correlation of 0.8691 with human sentence-pair similarity scores on STS-B. For ciphertext-based retrieval, we evaluated naive and optimized implementations. The optimized implementation uses CKKS single instruction, multiple data (SIMD) packing to compute and return multiple similarity scores together, reducing single-query latency over 7,128 indexed items from 222.028 to 5.168 seconds and communication overhead from 6.11 GB to 2.13 MB. These findings demonstrate the technical feasibility of privacy-preserving text inference for health-misinformation applications and characterize its predictive utility and efficiency trade-offs.</p>
  </details>
</div>



<h2>2026-11</h2>

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

