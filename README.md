
<h2>2026-09</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.00822v1">TRACE: Privacy-Preserving Next-Best-View Selection over Distributed 3D Gaussian-Splat Maps</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E">
  <p><b>Published on:</b> 2026-09-30T23:32:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Amirhossein Mollaei Khass, Athanasios Cosse, Qiyu Sun, Nader Motee</p>
    <p><b>Summary:</b> Share the light, not the map. We study next-best-view selection for a team of robots, each of which builds its own 3D Gaussian Splatting map and keeps it private. A robot picks the view with the largest expected information gain (EIG) about the splats along its own path. This gain depends on the other maps. Their splats occlude its own and shine behind them, so the gain has to be evaluated against the pooled map. No robot has this map. We show that the coupling passes through only two ray quantities, the transmittance in front of a splat and the radiance behind it, and that both are sums over the hits of the ray. Hence, they decompose across the robots, and each robot sums them over depth bins in its own map, along the rays of a candidate view, and sends the sums with their pose derivatives. The robot planning the view turns them into its EIG and gradient on SO(3). Transmittance and Radiance Aggregates, communicated for the EIG, give the protocol its name: TRACE. No robot shares its splats, and the message size does not grow with a map. We prove that the reconstruction is exact unless a depth bin behind a splat mixes hits of two robots, and we bound the error otherwise. Over 100 next-best-view decisions in Habitat-Sim, TRACE picks a heading within 15 degrees of the centralized one in 83.3% of the cases, and its views reach 97.9% of the centralized EIG.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.39787v2">Privacy Foundations for Multi-Institutional Scientific Artificial Intelligence</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-30T14:08:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Olivera Kotevska, Sumit Jha, Aur'elien Bellet, Rui Hu, Nathaniel D. Bastian, Rafael Ferreira da Silva, Ravi Madduri, Kibaek Kim</p>
    <p><b>Summary:</b> Scientific artificial intelligence (AI), spanning foundation models (FMs) to federated data-analysis pipelines, is becoming shared infrastructure across national laboratories, universities, hospitals, and industrial partners. This collaboration creates privacy risks whose natural unit is often an institution's participation, research strategy, or technical capability rather than a single record. Differential privacy (DP), federated learning (FL), secure computation, trusted execution, and provenance each protect parts of the stack, but their guarantees rarely compose across mixed-trust institutions, access tiers, and autonomous agents. This perspective recasts privacy for scientific AI as an assurance problem defined by six elements: protected asset, observer, channel, permitted disclosure, guarantee, and evidence. We demonstrate the framing through a claim register for a composite cross-institutional scenario and use it to assess the model lifecycle. Two of the resulting gaps are specific to leadership-class facilities: scheduler, allocation, and telemetry metadata expose an institution's resource posture, and instrument-attached control loops leak research strategy through timing and contention on shared accelerators. We identify six research priorities: institution-level guarantees, agent-communication privacy, cross-tier information flow, privacy-compatible reproducibility, leadership-scale accounting, and instrument side channels. The contribution is a common form for stating, comparing, and auditing claims whose guarantees otherwise remain fragmented across the scientific AI stack.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.39362v1">Link Inference Attack on Privacy-Preserving Knowledge Graphs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-30T09:18:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Emna Bouguerra, Ibtissam Harrouche, Ferran Alborch, Melek Önen</p>
    <p><b>Summary:</b> Knowledge Graphs (KGs) are widely used to store and share structured information across sensitive domains such as healthcare, fi- nance, and social networks. A common privacy practice is to delete sen- sitive relations before publishing the graph, under the assumption that removing edges is sufficient to prevent their recovery. In this paper, we challenge this assumption and show that even when a relation is fully or partially hidden, its existence leaves structural traces in the public graph that can be exploited to recover it with high accuracy. To this end, we propose a link inference attack that operates on the topology of the public graph, and evaluate it under two privacy scenarios that differ in how the adversary exploits the knowledge available to him. In the first setting where the adversary exploits all topological information, the attack achieves near-perfect discrimination (AP = 0.949, ROC-AUC = 0.999), while in the more realistic one where the adversary makes use of some semantic information, it recovers up to 74% of hidden edges. Build- ing on these results, we further conduct a structural analysis to identify which topological properties of the graph drive the attack success, re- vealing that privacy risk is not uniform across entities and that certain structural patterns make specific relations significantly more vulnerable to inference than others.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.38934v1">PrivCert: Certifying Statement Support under Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-30T04:12:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tsubasa Takahashi, Takumi Hiraoka</p>
    <p><b>Summary:</b> Differentially private (DP) text generation can protect individual records, but privacy alone does not specify what evidence a released statement carries about the underlying data. We identify this as an evidence gap: a private report may contain plausible claims without indicating whether they are strongly supported by the private dataset. We introduce PrivCert, a framework for privacy-preserving reporting that makes statement support explicit through privacy-preserving certificates and emit-or-abstain decisions. As a canonical instantiation, PrivCert-PF (Proposal-and-Filter) separates data-independent candidate discovery from private support certification, emitting only statements whose support passes a private evidence test. We provide theoretical grounding for this framework by characterizing the limits of implicit evidence under DP, deriving a sharp privacy--honesty frontier for single-statement certification, and establishing a worst-case cost for fine-grained multi-statement certification. Experiments on synthetic tasks and TAB, WildChat, and Yelp show that explicit certification maintains low unsupported emission, while free-text DP baselines frequently produce low-support claims under the same declared support semantics. We further show that the PrivCert contract can be realized with histogram, sparse-vector, and Gaussian mechanisms, and use DP synthetic data to illustrate an important boundary: support in a private proxy does not automatically certify support in the original data. Together, these results position privacy-preserving reporting as an evidence-design problem: not only how to generate private text, but what a private report can substantiate about its underlying data.</p>
  </details>
</div>



<h2>2026-10</h2>

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
  <h3><a href="http://arxiv.org/abs/2610.22800v1">Veil-Then-Reveal: Protecting PII Privacy via Reversible Pseudo-Anonymization in Zero-Trust User--LLM Interaction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-10-16T01:24:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohamed Shaaban, Mohamed Elmahallawy, Thomas E. Carroll</p>
    <p><b>Summary:</b> Large language models (LLMs) increasingly process sensitive documents and personal information, yet sending prompts containing personally identifiable information (PII) to remote providers exposes data subjects and organizations to risks from logging, retention, model training, and unintended disclosure. Existing anonymization methods often mask or remove PII, while conventional encryption eliminates the lexical and structural cues needed for effective LLM processing. We present Veil-then-Reveal (VtR), a user-side PII pseudo-anonymization framework for privacy-preserving LLM interaction under a zero-trust threat model. VtR treats remote LLM providers as untrusted and sends only pseudo-anonymized prompts, keeping plaintext PII on the user. VtR first detects PII and replaces it with realistic, same-type, in-vocabulary surrogates before prompts leave the user's device, preserving their linguistic and structural properties. It combines format-preserving encryption (FPE) for structured PII, such as phone and credit-card numbers, with a keyed-hash dictionary and secure vault for semantic PII, such as names, locations, and organizations. Session-specific mappings provide cross-session unlinkability, while user-side restoration reversibly replaces surrogates with their original values in LLM responses. We further introduce a rank-class FPE strategy for dates that preserves format and ambiguity while reducing cipher evaluations. Evaluation on three datasets containing 11,322 annotated PII instances achieves 97.9% detection recall, 95.2% protection of detected values, and 99.9% round trip; 100% of echoed surrogates end-to-end round-trip restoration.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.22722v1">The LLM-Attacker: A Unified Red-Team Framework for Privacy Evaluation of Split and Distributed LLM Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-15T22:53:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Georgios Politis, Evangelos Pappas</p>
    <p><b>Summary:</b> Split language models keep input text on a client but send intermediate representations to a server. Attacks can reconstruct text from these messages. Comparing privacy evaluations is difficult when attackers see different messages, know different model weights or use different datasets and recovery measures. We present LLM-Attacker, a framework that records these choices and lets researchers check, compare and extend an evaluation. Compatible attacks reuse recorded messages, and their predictions are saved for independent scoring. The scoring rule requires a linked undefended reference before a defence can pass. Reports also identify attacks that remain untested. In a controlled GPT-2 experiment, adding gradients returned during training increased token recovery from 94.20% to 97.38% and exact-document recovery from 13.71% to 37.77%. The 95% interval for the token gain lay above the two-percentage-point threshold fixed before testing. This experiment is shared with a companion study; here, it tests how the evaluation responds to a change in attacker access. Further studies measure how corpus choice and compression defences affect recovery, compare an adapted published attack with its reference implementation, and test the measurement code. The framework reports implementation checks separately from measured attack effectiveness. Each privacy claim should state the attacker, dataset and scoring rule, report its controls and identify untested attacks.</p>
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
  <h3><a href="http://arxiv.org/abs/2610.21245v1">From One Query to Many: A Critical Survey of Privacy Accounting in RAG</a></h3>
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


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.20494v1">Quantifying privacy risks in foundation model representations of brain MRI</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-10-14T17:03:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Imen Bajar, Héber Hwang Arcolezi, Antoine Boutet, Carole Frindel, Mohamed Maouche</p>
    <p><b>Summary:</b> Pretrained representations are increasingly used to share and reuse information from medical images without exposing the original scans, but it is unclear how much patient-specific information these representations retain. We investigate this question for brain magnetic resonance imaging (MRI) by evaluating five frozen pretrained encoders spanning different architectures, pretraining objectives, and training domains on two longitudinal T1-weighted datasets, OASIS-2 and MIRIAD. Under an attacker model with access to released embeddings, the corresponding public encoder, and auxiliary MRI scans, we evaluate patient linkage and sensitive-attribute inference. Across the evaluated representations, we observe substantial subject-specific information: rank-1 patient linkage reaches up to 99\% on MIRIAD and exceeds 90\% on OASIS-2 for the highest-risk representation, despite the absence of an identification objective during encoder training. We further show that the released embeddings retain information about a demographic attribute, with recorded-sex prediction reaching balanced accuracy of 90.9\% on OASIS-2 and 95.5\% on MIRIAD. Overall, our results demonstrate that replacing raw brain MRI with learned embeddings does not, by itself, eliminate patient-linkage or attribute-inference risk, and is therefore insufficient on its own to establish anonymity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.20055v1">GeoCloak: An Agentic Framework for Semantics-Preserving Geolocation Privacy via Peripheral Clue Manipulation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-14T11:56:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yixin Wu, Mingjie Li, Yun Shen, Michael Backes, Yang Zhang</p>
    <p><b>Summary:</b> The rapid advancement of large vision language models (LVLMs) has made geolocation inference from images highly accurate and accessible. This poses serious privacy risks: a passive adversary with black-box LVLM access can infer a user's location from a single photo with no metadata. Existing protection methods rely almost exclusively on adversarial perturbation, which introduces perceptible visual artifacts and utility degradation. We identify the visual-geolocation asymmetry: geolocation-decisive clues, such as street signs, tend to be visually peripheral but dominate location inference. Exploiting this asymmetry, we propose GeoCloak, an agentic framework for semantics-preserving geolocation privacy protection. It acts as a clue-aware planner that analyzes each image to identify geolocation-relevant clues, dispatches targeted semantic edits to directly suppress peripheral clues, and autonomously configures adversarial perturbation to further suppress residual geolocation features, all under iterative utility-aware feedback. We evaluate GeoCloak on four diverse datasets spanning 108 countries and 576 cities against five LVLMs and three inference methods. GeoCloak reduces overall city-level accuracy from 41.2% to 9.9%, approximately half of the best-performing baseline, while achieving substantially superior utility preservation both qualitatively and quantitatively. We hope this work takes a meaningful step toward practical, semantics-preserving geolocation privacy protection, giving users greater control over the location information inadvertently embedded in their shared images.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.19826v1">Simultaneous Secure Communications and Sensing Privacy with Full Duplex MIMO Radios</a></h3>
  
  <p><b>Published on:</b> 2026-10-14T09:01:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ioannis Gavras, George C. Alexandropoulos</p>
    <p><b>Summary:</b> This paper proposes a Full Duplex (FD) framework for safeguarding Integrated Sensing and Communications (ISAC) against a passive multi-antenna Eavesdropper (Eve). The adversary is modeled as both a communication and sensing threat, seeking to decode uplink data streams and estimate the surrounding scene. Eve's threat is quantified through two worst-case requirements over a location uncertainty region: a minimum secrecy rate for data confidentiality and a minimum eavesdropping Cramer-Rao Bound (CRB) for sensing privacy. We derive the eavesdropping information measures governing both data interception and scene inference, showcasing that transmitting Artificial Noise (AN) can degrade Eve's capabilities through the inverse interference-plus-noise covariance. Exploiting the underlying structure of the problem, we characterize finite-power local and robust feasibility conditions for target secrecy-privacy pairs. The analysis showcases that AN is fundamentally subspace-limited: increasing power is beneficial only along Eve's communication channel and sensing-derivative directions illuminated by the effective AN subspace. Finally, we formulate an AN power allocation problem that is solved via monotone branch-and-bound, and numerical evaluations quantify the AN power required to guarantee joint secrecy and sensing privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.19573v1">On Inherent Privacy of Posterior Sampling: A Unified Rényi-Divergence Framework</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">
  <p><b>Published on:</b> 2026-10-14T04:40:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruyu Zhou, Fang Liu</p>
    <p><b>Summary:</b> Differential Privacy (DP) provides a rigorous framework for quantifying privacy guarantees. While most methods achieve DP by injecting calibrated random noise, the intrinsic randomness of certain procedures such as sampling can yield DP guarantees ``for free''. In this work, we develop a unified Rényi divergence framework to characterize the inherent DP guarantees of sampling from a Bayesian posterior distribution. We show that the privacy loss incurred by One-Posterior-Sampling (OPS) is governed by posterior exponential moments of the single-record log-likelihood ratio, and establish explicit DP guarantees under uniformly bounded, sub-Gaussian, or sub-exponential tail regimes. We apply the framework to representative Bayesian models, including categorical likelihoods with arbitrary priors, Gaussian-Gaussian conjugate pair, generalized linear models from the exponential family and linear regression with Gaussian likelihood, both with Gaussian priors on the regression coefficients. Our results elucidate sample size, model structure, neighboring relations in DP (bounded or unbounded), and how prior if applicable, jointly determine the inherent DP guarantees of OPS. Furthermore, our results recover the existing DP guarantees for OPS as special cases -- often with tighter privacy loss bounds -- and substantially broaden the class of Bayesian models for which the inherent DP guarantees of OPS can be rigorously characterized.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.19456v1">Weak Private Information Retrieval for Graph-based Storage under $ε$-privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-10-14T02:42:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jayesh Seshadri, Prasad Krishnan</p>
    <p><b>Summary:</b> The problem of Private Information Retrieval (PIR) across graph-based replicated systems has seen a surge of interest in recent literature. In such systems, servers are modeled as the vertices of a graph, and each file is represented by an edge connecting the pair of servers that store it. While previous research on Graph-PIR (G-PIR) has focused mostly on perfect information-theoretic privacy, relaxing this constraint has the potential for significantly higher retrieval rates. In this work, we consider the setting of Graph-based Weak Private Information Retrieval (G-WPIR), under an $ε$-privacy metric. We adapt an existing G-WPIR scheme for arbitrary graphs to analyze its performance under the $ε$-privacy metric. Additionally, we establish a lower bound on the expected download cost for arbitrary graphs under the $ε$-privacy metric and derive from it an explicit rate upper bound for complete graphs. Finally, we show the achievable rate-privacy trade-offs for two specific graph classes---complete graphs and complete bipartite graphs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.19335v1">Differentially Private Learning of Markov Chains: Near-Optimal Sample Complexity for Item and User Level Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-14T00:21:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Devansh Gupta, Cristóbal Guzman, Enayat Ullah</p>
    <p><b>Summary:</b> Sequential data such as documents, conversations, and trajectories are naturally partitioned across users, motivating privacy guarantees that protect each user's entire trajectory. We initiate the study of privately estimating the transition matrix of a discrete ergodic Markov chain from N independent trajectories of length T, with arbitrary initial distributions, under maximum row-wise ell 1 error. Besides N, T, and the number of states, our bounds depend on the minimum stationary probability and the pseudo-spectral gap, which govern state coverage and mixing. Under item-level privacy, we give upper and lower bounds that separate the costs of sampling, state occupancy and mixing, and privacy. Under user-level privacy, we reduce the problem for sufficiently long trajectories to private product distribution estimation. Along the way, we establish optimal user-level private bounds for estimating products of discrete distributions, which may be of independent interest. In the user level setting, our bounds are nearly tight in the large T regime, whereas in the item-level setting, our bounds as tight up-to a non-private term.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.19325v1">AutoPoly-HE: Autonomous Design of Polynomial Activations for Privacy-Preserving Encrypted Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-14T00:05:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zeinab Elkhatib, Kamrul Hasan, Ali Sekmen, Imtiaz Ahmed, Tariqul Islam</p>
    <p><b>Summary:</b> Privacy-preserving machine learning has become critical for deploying artificial intelligence in sensitive domains such as healthcare, finance, and infrastructure monitoring. Homomorphic encryption (HE) enables secure inference on encrypted data. Despite its advantages, HE is not compatible with nonlinear activation functions found in machine learning models. Existing methods mitigate this problem by manually designing polynomial approximations for these activation functions. However, these functions do not account for the differences in dataset characteristics or model architecture. Furthermore, these functions are also limited to the accuracies of convolutional neural network (CNN) models. In this work, we propose an autonomous framework that selects polynomial activation functions tailored to each dataset and model. Using this framework, we analyze the interdependence between polynomial activation design and model architecture by evaluating several CNN ResNet and Vision Transformer models across multiple datasets. Experimental results demonstrate that the proposed framework generalizes across multiple architectures, including ResNet-18, ResNet-34, ResNet-50, ViT-S/16, ViT-B/16, and ViT-L/16. Across all datasets, transformer-based models maintain higher accuracy under polynomial approximation, while convolutional models exhibit increased degradation as task complexity grows. In addition, latency analysis reveals that the proposed CLS token based inference pipeline significantly reduces computational overhead by eliminating depth-dependent operations, shifting the primary cost to encryption and decryption. These findings demonstrate that the proposed method not only adapts polynomial activations across architectures, but also enables efficientencrypted inference through both activation design and pipeline optimization.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.18366v1">Understanding the "Why": Investigating the Design of Privacy Support Tools (PSTs) through the Lens of Psychological Needs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-10-13T13:27:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sara Hahn, Verena Zimmermann, Simon Althaus, Andreas Heinemann, Ephraim Zimmer, Alina Stöver, Nina Gerber</p>
    <p><b>Summary:</b> Privacy Support Tools (PSTs) help users control their digital data, but face low adoption due to resignation and overwhelm. While current regulations aim to enhance privacy control, users still struggle to manage their privacy. To address this, we explore how PSTs can be designed for long-term adoption by applying the theoretical lens of psychological needs, as their fulfillment motivates users to use a digital product. We conducted in-depth interviews with 15 users and identified Security, Autonomy, and Competence as key psychological needs. From our results, we derive implications and recommendations for the need-sensitive design of PSTs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.18294v1">Which Optimizer Leaks Most? Optimizer Implicit Bias as a Training-Data Privacy Controller</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-10-13T12:42:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sagi Habani, Yehonathan Refael, Ofir Lindenbaum</p>
    <p><b>Summary:</b> Releasing a neural network checkpoint can leak information about its training data, and existing reconstruction results rely on gradient-descent training. We ask whether the choice of optimizer affects the ability to recover the training data. Extending work connecting Karush--Kuhn--Tucker conditions to training-data reconstruction, we show that the implicit biases of popular optimizers (SGD, Adam, Muon) leave very different fingerprints of the training data. We argue that the key distinction is the \emph{weight-specificity} of these implicit biases, namely how much continuous information about the final weights the optimizer-dependent target of the stationarity conditions encodes. The limiting stationarity conditions for models trained with SGD and Muon retain enough weight-specific information to reconstruct training examples in practice. For Adam in the $\ell_\infty$ implicit-bias regime, the optimizer-dependent part of these conditions encodes only a discrete pattern of maximal coordinates and their signs, and at nondegenerate KKT points the conditions are too few to identify the training set to first order. Experiments on MNIST and CIFAR-10 support these claims: models trained with Muon can yield stronger reconstructions at much lower training cost than models trained with SGD, although this advantage depends on the training regime and architecture, and models trained with Adam appear consistently more resistant to the evaluated attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.18054v2">Privacy-Preserving GNN Inference on Financial Transaction Graphs via Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-13T09:43:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> H. Çağrı Bilgi, Kemal Mutluergil, Ceren Yıldırım, Kubilay Atasu, Erkay Savas</p>
    <p><b>Summary:</b> Anti-money laundering (AML) in financial networks requires modeling transaction patterns that span multiple institutions. In practice, however, banks cannot share account and transaction features due to strict privacy regulations. We propose a privacy-preserving graph neural network (GNN) inference framework tailored to this multi-bank setting. A central server holds the graph connectivity and pretrained model weights in plaintext, while each bank keeps its transaction features encrypted. Inference is then carried out entirely on encrypted features under the CKKS homomorphic encryption scheme, so that no plaintext transaction features or predictions are exposed to the server. The key to making this practical is an edge-centric GNN architecture, wherein message passing is expressed through operations on node--edge incidence matrices. This formulation not only preserves the edge-attributed multigraph structure of transaction networks but also reduces every aggregation step to plaintext--ciphertext matrix products. Since CKKS can evaluate only polynomial circuits, we also approximate each nonlinearity with a composite polynomial of the sign function, which we calibrate per activation site. On the IBM AML benchmark, our model achieves performance competitive with plaintext baselines, and with a consumer-grade GPU, classifies each queried transaction end-to-end in as little as 5.31 seconds, while per-transaction latency can be amortized to 1.65 seconds when optimized for throughput.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.18007v1">Cost-Efficient Privacy Enforcement for Email-Generating LLM Agents under Strategic Information Requests</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-10-13T09:06:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qikun Cai, Tao Huang, Chen Hou</p>
    <p><b>Summary:</b> LLM agents now act as delegated communication intermediaries: they read private context, draft messages, and send externally visible emails on behalf of a user. Existing checker-repair defenses can reduce inappropriate disclosure, but they rely on repeated calls to a remote action LLM (the model that drafts and repairs the email) and a remote checker LLM whenever a draft fails validation. This creates a cost problem as well as a privacy problem, especially when a requester strategically asks for exact values, raw records, source evidence, or other details that induce leakage-heavy drafts. We propose local contract-conditioned rewriting as a cost-efficient enforcement layer for email-generating agents. The mechanism intercepts an outgoing draft, constructs an information-release contract that specifies what to preserve, generalize, and forbid, rewrites the draft with a local Gemma rewriter, and selectively invokes a final PrivacyChecker. Across extensive email tasks under normal prompts and attack prompts that operationalize strategic information requests, Gemma + Checker reduces normal-prompt leakage from 11.41% to 4.03% while improving UsableRate (satisfied or partially satisfied outputs) from 85.2% to 92.6%. Under the strategic attack-prompt condition, it reduces leakage from 28.19% to 18.79% and reduces checker-only cost amplification from 1.32x to 1.02x. Offline replay ablation shows that the full contract reduces leakage relative to generic Gemma rewriting by 36.3% under normal prompts and 54.1% under attack prompts. These results support a local-first privacy enforcement design: move repair to a cheaper trusted local layer when possible, but retain the checker as the final semantic gate for high-risk sends.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.17323v1">SSM-Attack: Learning Where to Perturb for Black-Box Face Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-12T19:28:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tunahan Parlayıcı, Erchan Aptoula, Yücel Saygın</p>
    <p><b>Summary:</b> Face recognition systems are deployed widely enough that a photograph shared online can be matched without its subject's consent. Generator-based protection methods rely on heavy pretrained backbones, multi-stage inference or visible semantic edits. We introduce SSM-Attack, a black-box face privacy framework built on Selective State Space Models. Rather than synthesizing the perturbation, the state-space model predicts in one linear-time pass a spatial allocation of the perturbation budget, marking which facial locations carry identity evidence; a short projected refinement then sets the values within this per-pixel budget. Against published benchmark results, SSM-Attack attains the highest average black-box attack success rate on all three evaluation sets: 87.10 percent on CelebA-HQ, 86.90 on LADN and 81.15 on FFHQ, the last from a network that never saw that dataset. The allocation network holds 5.73 million parameters, or 16.13 million with the frozen networks used by its quality terms. Under the same cap of 0.10 on the maximum per-pixel change, allocation improves structural similarity by 0.044, peak signal-to-noise ratio by 1.62 decibels and Frechet Inception Distance by 11.2 points over a uniform map while spending 37 percent of its capacity. Strong facial privacy protection therefore does not require a large generative prior; it requires knowing where to spend a small one.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.17088v1">The Right to Be Forgotten under Correlation: Privacy-Utility Tradeoffs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-12T16:48:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Luis Massny, Rawad Bitar, Fangwei Ye, Salim El Rouayheb</p>
    <p><b>Summary:</b> We study privacy-preserving algorithms that redact information from a correlated dataset. The goal is to reduce the information leakage about sensitive parts. We analytically characterize the optimal tradeoff between privacy (leakage through correlation) and utility (number of redactions) for local mechanisms and binary Markovian correlations. Our result shows how to decompose the mechanism design problem into a sequence of local mechanism design problems and reveals their sequential relation. The optimal mechanism is the solution to a Finite-Horizon Deterministic Markov Decision Process.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.16872v1">Toward Realistic Privacy Risk in FL-Enabled OT Intrusion Detection Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-12T14:35:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Assunta Imperatrice, Luigi ROmano</p>
    <p><b>Summary:</b> In Operational Technology (OT) environments, Federated Learning (FL) is increasingly adopted to train Intrusion Detection Systems (IDSs) without sharing raw operational data across facilities. However, model updates may still leak sensitive information about industrial processes, creating privacy risks that remain largely invisible within current OT security architectures. Existing reference models, including the Purdue hierarchy, do not explicitly represent the FL learning lifecycle, making privacy leakage difficult to observe and evaluate. To address this gap, we introduce the ML Plane, a novel architectural abstraction that integrates FL workflows within OT systems, enabling visibility of learning-related information flows that are not explicitly represented in traditional OT architectures. Building on the proposed ML Plane, we outline a privacy auditing framework for FL-enabled OT systems. The framework uses Federated Membership Inference Attacks (FedMIA) as an initial assessment mechanism and is being instantiated within a Smart Grid testbed to support the future evaluation of privacy risks under realistic OT deployment constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.16556v1">Design of Privacy-Preserving Estimators Under Prior Information Exposure</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-10-12T10:35:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Le Liu, Yu Kawano, Ming Cao</p>
    <p><b>Summary:</b> State estimation is widely used in networked dynamical systems, but released estimates may inadvertently reveal sensitive information about private state variables. Existing privacy-preserving estimation frameworks often do not explicitly account for adversarial prior knowledge. Motivated by this gap, we study privacy-preserving state estimation for discrete-time linear stochastic systems under prior information exposure using pointwise maximal leakage (PML). We first reveal a privacy anti-optimality property of the Kalman filter: in the absence of additive release noise, the steady-state Kalman filter maximizes PML privacy leakage among the considered class of stable linear estimators. We further establish a nontrivial lower bound on the steady-state estimation error enforced by $(\varepsilon,δ)$-PML privacy. We then derive sufficient release-noise conditions that guarantee $(\varepsilon,δ)$-PML privacy, first for the Kalman filter and then for stable linear estimators. Finally, a convex semidefinite program is formulated for a joint design of the estimator gain and release noise covariance, providing a tractable privacy-preserving estimator with an explicit upper bound on the steady-state estimation error. Simulations on a source--load power system demonstrate the proposed privacy--utility tradeoff.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.16458v1">Differential Privacy Protected Preference Alignment on Survey Derived Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-12T09:18:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiuyuan Qi, Yi Wang, Wenjie Wang</p>
    <p><b>Summary:</b> Preference alignment enables language models to better reflect human values, but the preference data contains sensitive information, especially when derived from surveys about political beliefs, social norms, religion, gender attitudes, and cultural values. This paper studies privacy-preserving alignment on questionnaire-derived data from the World Values Survey, where supervision takes the form of ordinal labels rather than standard pairwise rankings. Existing efforts mainly focus on general privacy protections upon model training, while data-specific methods for survey data remain unexplored. We first show the vulnerability of aligned models, then formulate the task as rating prediction and introduce label differential privacy. Building on this formulation, we construct a differential private pipeline utilizing three privacy mechanisms: randomized response, exponential mechanism, and DP-SGD. Experiments show that simple label-level mechanisms outperform gradient-level methods, and proper aggregation function for preprocessing also make large contribution. The new fine-grained private comparison motivates explorations toward language model alignment with formal privacy guarantees.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.16414v1">Purpose IR: Compiling User Purpose for Privacy-Preserving Agent Workflow State</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-12T08:48:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dongsheng Chen, Xiangyu Zhao, Lei Ma, Xin Yao, Xuetao Wei</p>
    <p><b>Summary:</b> LLM-agent workflows routinely transform rich observations into plans, summaries, memories, handoffs, and other reusable state. This creates a privacy boundary that task relevance alone does not capture: an observation may be needed as evidence for a task without its full semantics being authorized to persist. We call this mismatch the purpose-to-state semantic gap. The key distinction is that evidence authority is not release authority. We introduce Purpose IR, a bounded typed intermediate representation that compiles natural-language user purpose into an executable semantic boundary for reusable agent state. A Purpose program is an acyclic semantic dataflow graph in which evidence leaves specify task-required semantics, typed dependencies constrain authorized derivations, and declared sinks determine which values or actions may cross the reusable-state boundary. A deterministic compiler constructs and validates the authoritative program, while a typed runtime reconstructs reusable state only from validated sink outputs. Under explicit execution contracts, this design yields release confinement and purpose noninterference, characterizing what factual semantics may be released and which observation differences must become irrelevant to reusable state. Across 1,200 cases spanning LangGraph, CrewAI, and MobileRun, Purpose IR achieves 99.6% Privacy, 83.3% Task, and 83.3% Privacy-Compliant Success (PCS), outperforming the strongest high-privacy baseline by 27.5 PCS points. On 493 PrivacyLens trajectories, it achieves the highest Safe Action Rate at 77.3%, 10.4 points above the next-best method, extending the same boundary from reusable state to downstream actions. These results show that privacy-preserving agent state requires more than filtering sensitive or task-irrelevant content: it requires an explicit, executable representation of what the user's purpose authorizes to survive.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.16384v2">Risk-aware Road-network Trajectory Synthesis under Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2026-10-12T08:36:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hongzhen Xiang, Chenxu Wang, Yumeng Song, Tao Qin, Yushuai Li, Pinghui Wang, Wei Wang, Tianyi Li</p>
    <p><b>Summary:</b> Road-network trajectory synthesis under local differential privacy (LDP) enables mobility data analysis without uploading raw trajectories to an untrusted server. Existing locally private trajectory synthesis methods mainly model whole trajectories, point sequences, or grid-level mobility patterns. However, they cannot handle non-uniform privacy risks caused by local road-network and trajectory contexts, such as endpoints, long-stay-associated regions, and low-out-degree branches. They also do not directly protect conditional next-hop choices on road networks, where a user's selected successor may reveal sensitive local movement intentions. To address these challenges, we propose TrajRACE, a locally private synthesis framework for road-network trajectories. TrajRACE uses start, segment-count, and transition reports to represent trajectories. For each transition, it keeps the current road segment as a public aggregation context and perturbs the true successor among legal successors on the client side. It then assigns risk-aware protection strengths to transitions according to local road-network and trajectory contexts. Finally, the server recovers population-level start, segment-count, and conditional transition statistics from heterogeneous privatized reports, and generates synthetic trajectories that follow the public road-network topology. Experiments on three road-network trajectory datasets demonstrate the effectiveness of TrajRACE in improving synthetic-data utility across distributional, query-based, and pattern-level metrics, while providing stronger protection for high-risk local transitions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.16196v1">Towards Privacy-Preserving ASR: Speaker-Level Machine Unlearning</a></h3>
  
  <p><b>Published on:</b> 2026-10-12T05:25:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Seaone Ok, Seungu Han, Eungbeom Kim, Kyogu Lee</p>
    <p><b>Summary:</b> Automatic Speech Recognition (ASR) systems are commonly designed to transcribe linguistic content independently of speaker identity. However, speaker-specific information can persist within the latent representations of ASR models, raising privacy concerns when training data includes sensitive individuals. While machine unlearning has been studied in several speech tasks, applying speaker unlearning to ASR remains challenging due to the strong entanglement of linguistic and speaker-related information in speech representations. In this work, we conduct a layer-wise analysis of Self-Supervised Learning (SSL) based ASR representations, revealing that speaker identity is primarily encoded in intermediate encoder layers. Based on this observation, we explore a feature-level unlearning strategy that targets these identity structures. Experiments on the VCTK corpus show that the proposed approach removes the influence of specific speakers while maintaining robust transcription performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.15982v1">Adaptive Confidence Sets for Nonparametric Density Estimation under Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">
  <p><b>Published on:</b> 2026-10-11T23:31:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aditya Khan, Thibault Randrianarisoa</p>
    <p><b>Summary:</b> In nonparametric density estimation without privacy constraints, it is known that a confidence set whose coverage holds uniformly over a `rough' class of regularity $r\geq0$ can simultaneously attain, in $L^2$-diameter, the minimax rate over a smaller, smoother class of regularity $s>r$ if and only if $s \le 2r$. We study such adaptive honest confidence sets under non-interactive $α$-local differential privacy (LDP) constraints. Our main result is that, for bounded $α$, such `smooth-rate adaptation' is now possible if and only if $s \le 4r/3$. In this smaller range we construct an honest private confidence set whose diameter is of the private minimax order on each of the two classes. As in the non-private case, the threshold arises because an honest set cannot, at a smooth density, be narrower than the separation rate arising in a related testing problem. Under LDP we prove that this private testing rate is of order $(nα^2)^{-2r/(4r+3)}$, which is at most the private estimation rate $(nα^2)^{-s/(2s+2)}$ over the smooth class exactly when $s \le 4r/3$. For $s > 4r/3$, however, we show that smooth-rate adaptation becomes possible once one discards from the rough class the densities that lie outside the smooth class but within an $L^2$-radius of the order of the private testing rate.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.15972v1">Exact Privacy--Distortion Design of Support-Constrained Randomized Response</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-10-11T23:05:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Amirreza Zamani, Parastoo Sadeghi, Mikael Skoglund</p>
    <p><b>Summary:</b> Full-support local randomizers can incur unnecessary reporting distortion on ordered alphabets. We study randomized response whose output is restricted to a radius-$t$ neighborhood of the private input. Input-dependent supports create privacy leakage at their boundaries, so ordinary likelihood-ratio calibration is no longer sufficient. Under approximate local privacy restricted to input pairs at distance at most $H$, we derive the exact hockey-stick defect of the mechanism. We then solve the joint design of the truthful probability, off-truth probability, and support radius. The fixed-radius optimum is available in closed form, while the global optimum requires only a one-dimensional integer search. We characterize both the privacy floor and its inverse, namely the smallest defect attainable under a reporting-distortion budget. We further prove that stringent approximate privacy forces the support size to scale as $Ω(H/δ)$. Deterministic evaluations illustrate the resulting tradeoff.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.15865v1">Penetrating the Reality Wall: Long-Range and Through-Wall AR/VR Privacy Eavesdropping via Wireless Power Side Channel</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-11T19:37:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tao Ni, Zehua Sun, Yihe Zhou, Yuefeng Du, Qingchuan Zhao, Cong Wang</p>
    <p><b>Summary:</b> Over the past decade, Metaverse technology (AR/VR) has seen widespread adoption in numerous areas, including gaming, social networking, and online collaboration. Although recent studies have exposed vulnerabilities in VR systems, they often apply methods (e.g., pre-installed malicious apps or scripts) from conventional mobile platforms directly, demonstrating impractical attacks that fail to investigate unique privacy leakages specific to VR platforms. In this paper, we present an orthogonal attempt to analyze the attack surface of the power side channel on AR/VR's network connection by capturing the through-wall wireless power in the network transmission medium (e.g., Wi-Fi signals) non-intrusively in a comparatively long distance (e.g., 5.0m-8.0m) and further reconstructing multi-level privacy-aware user behaviors.
  We propose MetaSpy to validate the feasibility and practicality of our disclosed wireless power-based traffic analysis attack. It first captures through-wall wireless power transmitted from the Wi-Fi router of an adjacent room, identifies the device type, then infers (i) user interactions such as browsing websites, running AR/VR apps, and performing various in-app activities, (ii) unseen VR-specific activities in VR games (e.g., Population: ONE), and (iii) avatar-based user re-identification and virtual keystroke inference corresponding to head movements. We evaluated the effectiveness of MetaSpy in four commercial-off-the-shelf (COTS) VR headsets, and the empirical results demonstrate its competitive accuracy in unveiling multi-level user privacy within virtual scenes in through-wall settings at a longer distance (1.8x-80x) than most of the recent studies, and it shows resilience to a series of external interference and impact factors. In addition, we also propose and evaluate effective countermeasures to protect data confidentiality in AR/VR wireless transmission.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.15847v1">Residual-Information Generalization Bounds Under Selective Privacy: Extended Version</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-10-11T18:58:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Amirreza Zamani, Parastoo Sadeghi, Mikael Skoglund</p>
    <p><b>Summary:</b> Information-theoretic generalization bounds usually control dependence on the task sample, whereas selective privacy may constrain only a different, private coordinate. We study i.i.d. pairs $(X,Y)$, where a learner observes $(X^n,Y^n)$, leaks at most $ε_n$ nats about $X^n$, and incurs loss on $Y$. A chain-rule transfer converts this mismatched constraint into the closed-form universal certificate $I(W;Y^n)\leq\min\{nH(Y),nH(Y\mid X)+ε_n\}$. Combining the certificate with mutual-information generalization yields a bound governed by residual task uncertainty and normalized privacy leakage. We derive complementary task-compression and individual-sample refinements, identify a sharp obstruction showing why selective privacy alone need not give a vanishing certificate, and invert the bound to obtain the exact leakage allowance for a prescribed generalization tolerance. We prove exact information-level achievability for deterministic-task and independent-residual source families and show that the resulting $\sqrt{ε_n/n}$ generalization rate is tight up to a universal constant. We also give a fixed-horizon adaptive application in which conditional leakage costs add.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.15804v1">Privacy Conductor: An Architectural Enforcement of Contextual Integrity in LLM-Based Document Retrieval</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-11T17:48:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ryan Thornton, Mir Mehedi A. Pritom, Maanak Gupta, Jessee Roberts</p>
    <p><b>Summary:</b> Large language model (LLM) that retrieve internal documents within an organization must decide who may receive them. Existing approaches based on Contextual Integrity ask the model to make that decision, so access depends on probabilistic reasoning. We present Privacy Conductor, an architecture that removes the decision from the model: a deterministic gate enforces a policy written by an authority, and the model receives only what the requester may already see. On a synthetic clinical corpus of 2,520 requester--document flows, the gate reproduces its policy exactly, so the remaining risk lies in the document labels it reads. As label source is of primary importance, we compare LLM and human generated labels. Across seven configurations of six models from two model families, LLM-written labels degrade the policy in every case. Models assign a document's sensitivity tier correctly on 78--86% of documents, but reproduce its access-control list on as few as 23%. Relabeling the same documents five times with an identical request changes 13 to 124 access decisions per configuration, a result that does not depend on our own labels. On 214 flows from HIPAA court cases, the most accurate configuration (87.8%) still permits 11 of the 20 disclosures the law prohibits. LLMs can describe what a document contains, but not decide who should receive it. Hence, we recommend privacy policy should be authored by accountable personnel and enforced outside the model.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.15379v1">LiveAnon: Improving Privacy and Utility in Streaming Speaker Anonymization with Codec Language Models</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36">
  <p><b>Published on:</b> 2026-10-11T06:05:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yejin Kim, Kyungsu Kim, Seungu Han, Kyogu Lee</p>
    <p><b>Summary:</b> Speaker anonymization (SA) aims to conceal speaker identity while preserving linguistic content and emotion, but existing streaming systems often lose emotion information through discrete content bottlenecks or require emotion-specific modeling. We present LiveAnon, a voice-conversion-based streaming SA system that directly conditions an autoregressive codec language model on hidden features from a pretrained streaming ASR encoder, preserving emotion without emotion-specific supervision. To reduce codec-generation latency, we introduce capped RVQ decoding, which preserves dependencies among coarse codebooks while predicting the remaining codebooks in parallel. Under VPC24, LiveAnon improves intelligibility and emotion preservation over fixed-target Stream-Voice-Anon (SVA), a strong prior streaming SA system, matches emotion-prompted SVA in emotion preservation, and achieves the strongest semi-informed privacy among streaming systems. Under VPC26, it ranks second across all metrics among the evaluated anonymization systems, demonstrating a strong privacy-utility balance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.14846v1">Towards Privacy-Preserving Thermal Human Perception from Dataset to Deployment</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> 
  <p><b>Published on:</b> 2026-10-10T11:59:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kailai Sun, Yue Cui, Xinwei Wang, Zijie Gao, Baoshen Guo, Zhiqing Hong, Irfan Qaisar, Xu Yang, Yueting Li, Dian Fan, Qianchuan Zhao</p>
    <p><b>Summary:</b> Indoor human perception is the foundation for smart homes and healthcare. However, RGB cameras raise privacy concerns in private indoor environments, while low-resolution thermal cameras provide limited spatial and semantic information. Large-scale indoor thermal datasets and real-world deployments remain limited. Here, we introduce Indoor RGB-T, a large-scale paired RGB--thermal dataset for indoor human perception. The dataset covers 20 indoor rooms and contains 90,576 80x62 thermal frames, 87,016 temporally matched RGB--thermal pairs, and 115,557 annotated human bounding boxes. We establish benchmarks for robust thermal occupant-state detection with 0.75 mAP and occupancy estimation with an accuracy of 0.847 in unseen rooms. We further evaluate RGB-to-thermal and thermal-to-RGB translation, achieving a temperature MAE of 0.654 C and an R2 of 0.923. Finally, we deploy the thermal perception model on a commercial sleep-monitoring system in the real world. Field testing with 100 participants and deployment of approximately 1,000 devices further demonstrate its practical feasibility. We identify practical challenges that motivate future research directions, including environmental thermal interference, sensing range and multi-person occlusion. The code, trained models and partial dataset are available at https://github.com/kailaisun/RGBT and https://huggingface.co/skl24/RGBT.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.14643v1">AegisVox: Factorized Privacy and Clinical Preservation for Long-Form Speech</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-10-10T06:53:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Praphul Singh, Akshat Agarwal, Ratul Ghosh, Aashna Kanuga, Devashish Khatwani, Anurag Dwarakanath, Sri Gadde, Krishnaram Kenthapadi</p>
    <p><b>Summary:</b> Clinical speech reveals identity through both spoken identifiers and voice, yet its pauses, delivery, and speaker roles can also carry useful clinical evidence. Protecting that speech therefore requires more than preserving its words. We present AegisVox, a factorized framework that assigns consistent surrogate voices and edits identifier-bearing turns using document-consistent replacements. Across 390 public simulated or non-patient conversations totaling 63.6 hours, a matched comparison of two speech renderers separates replacement realization from retained identifiers, speaker linkage, and clinical preservation. Text-to-speech rendering realizes 535/601 planned replacements versus 453/601 for the codec-based speech editor. However, similar aggregate clinical preservation conceals more model-labeled contradictions, and conversation-wide speaker scores conceal greater edited-speech linkage under a score-direction sensitivity analysis. Fresh transcription of original audio provides a reference for interpreting the clinical measurement chain; an independent judge tests sensitivity to model-based assessment. Better replacement realization can therefore coexist with worse clinical or speaker-linkage measurements. AegisVox supports use-specific evaluation of those tradeoffs, not a guarantee of identifier removal or clinical safety.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.14432v1">Minimax Wasserstein Testing under Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">
  <p><b>Published on:</b> 2026-10-10T00:56:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bonwoo Lee, Ilmun Kim, Cheolwoo Park</p>
    <p><b>Summary:</b> We study Wasserstein-$p$ goodness-of-fit and two-sample testing under differential privacy. For general compact metric spaces, we establish upper and lower bounds on the minimax separation radii in terms of covering numbers, matching up to logarithmic factors. On the hypercube $[0,1]^d$, these bounds match up to constant factors for two-sample testing in all dimensions and for goodness-of-fit testing whenever $d\neq 4p$, thereby closing logarithmic gaps in existing non-private results. At the critical case $(d,p)=(4,1)$, we further show that a logarithmic factor is unavoidable by establishing matching minimax bounds for non-private Wasserstein-$1$ goodness-of-fit testing under a bounded-density assumption. Finally, for unbounded domains, we establish minimax-optimal separation rates up to logarithmic factors under an exponential tail condition.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.13768v1">From Pixels to Privacy-Sensitive Features: An Information-Theoretic Framework for Reconstruction Bounds</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-09T15:52:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Henry Bourne, Robert F. Allison</p>
    <p><b>Summary:</b> What can an adversary recover from a model trained with DP-SGD? Its $(\varepsilon,δ)$ guarantee does not answer this question directly. We derive a distortion bound that can be computed before training and applies even to an adversary who observes the parameter trajectory during training, knows every other training record and the population distribution from which the training records are drawn. The analyst may choose the representation in which error is measured, allowing the bound to target the aspects of reconstruction that are privacy-sensitive in a given application. Our information-theoretic framework separates two contributions: the information about a record revealed by training, measured through conditional mutual information, and the uncertainty already present in the data distribution, measured through source entropy. Rate-distortion theory combines them into a lower bound on the expected error of every reconstruction attack. For DP-SGD, the leakage bound depends only on the sampling rates and noise multipliers, while the source entropy is lower-bounded from a sample with finite-sample confidence. An orthogonal block construction keeps the resulting bound informative for high-dimensional images. We instantiate the framework in pixel space and in LPIPS feature space, obtaining, to our knowledge, the first lower bound on reconstruction distortion measured directly by LPIPS. On a range of image datasets the bounds establish non-trivial unavoidable expected reconstruction error within heuristically recommended privacy-budget ranges and beyond. Experiments compare the bounds with strong reconstruction attacks and identify the principal sources of the remaining slack.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.13685v1">On Privacy Mechanism Design Under a Bounded $α$-Lift Leakage Constraint with $χ^2$-Utility</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-10-09T14:51:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Amirreza Zamani, Mohammad Amin Zarrabian, Parastoo Sadeghi, Mikael Skoglund</p>
    <p><b>Summary:</b> We study the design of a statistical privacy mechanism under a bounded $α$-lift leakage constraint. An agent observes useful data $Y$, which is arbitrarily correlated with private data $X$, and releases $U$. The goal is to maximize Pearson $χ^2$-information $χ^2(Y;U)$ while satisfying the point-wise privacy constraint. This utility is an $f$-information that is nonnegative, obeys data processing, and measures the aggregate normalized change from the prior $P_Y$ to the posteriors $P_{Y|U=u}$. The main benefit of this choice is that $χ^2(Y;U)$ is exactly quadratic in the posterior perturbations; hence, no local approximation of the utility is required. For the nonlinear $α$-lift constraint, we derive a uniform Taylor-remainder bound that remains valid for the optimizing, $ε$-dependent perturbation. When $P_{X|Y}$ is invertible, this yields a closed-form quadratic surrogate, an explicitly scaled binary mechanism that satisfies the original $α$-lift constraint, a computable sufficient range for $ε$, and an $O(ε^{3/2})$ bound on the utility gap. For $α=2$, the solution is exact over an explicit range. We transfer these results to point-wise Rényi-divergence privacy, including an exact-feasible mechanism, an explicit privacy-budget range, and matching gap bounds. We also give an exact formulation for arbitrary leakage matrices and evaluate exact-feasible mechanisms numerically.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.12712v1">Better Batches, Better Privacy: Random Allocation for DP-BandMF</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-08T20:47:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ryan McKenna, Arun Ganesh</p>
    <p><b>Summary:</b> The current state of the art for batch selection and noise addition in differentially private training is a combination of DP-BandMF (informally, DP-SGD where the noise added in two different steps can be correlated if the steps are within $b$ of each other) and privacy amplification by sampling via Monte Carlo accounting. First, whereas prior batch selection strategies for DP-BandMF were inspired by Poisson sampling, random allocation is known to outperform Poisson sampling for DP-SGD. We therefore propose and analyze new batch selection strategies for DP-BandMF inspired by random allocation, improving RMSE by up to $1.85\times$ over previous work. Second, Monte Carlo accounting typically requires drawing $Ω(1/δ)$ samples from a privacy loss distribution, making accounting costly. We increase sampling and scoring throughput by two orders of magnitude through a carefully optimized GPU implementation. Finally, previous work chose the DP-BandMF strategy matrix and the batch selection strategy independently. We give a simple framework for choosing these parameters jointly, reducing RMSE by up to $13.4\%$ over fixed strategy matrices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.12535v1">SoK: Privacy-Preserving Order Matching</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-08T13:23:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Prerna Arote, Adrian Saiz, Lucianna Kiffer</p>
    <p><b>Summary:</b> Privacy-preserving order matching enables traders to discover and execute compatible orders while limiting disclosure of sensitive trading information. Existing systems span financial markets and blockchain-based asset exchanges and employ diverse market structures, privacy mechanisms, and trust assumptions, making their privacy guarantees difficult to compare. We present a systematization of privacy-preserving order matching covering 22 protocol families. We organize the order lifecycle into four phases: order representation and submission, order discovery and collection, order-matching, and settlement, and characterize each phase by protected and exposed information, access roles, privacy mechanisms, and trust assumptions. Our analysis shows that privacy is not a single protocol-level property: protecting selected order attributes or individual phases does not necessarily prevent leakage elsewhere in the lifecycle. We identify recurring trade-offs among privacy, functionality, trust, and verifiability, highlighting the challenge of achieving end-to-end privacy across the complete order lifecycle.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.11511v1">EIFL: Efficiently Protecting Global Model Privacy and Integrity Against an Untrusted Server in Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-08T08:47:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zehui Liao, Qiang Li, Binghui Wang</p>
    <p><b>Summary:</b> Federated learning (FL) typically adopts a server-client architecture, where the server aggregates clients' local models (i.e., the input) and returns the aggregated global model (i.e., the output) to clients. An untrusted server may return a tampered global model to compromise the output integrity. Some existing schemes focus on verifying the output integrity. However, these schemes mostly rely on clients pre-negotiating a set of identical auxiliary information among themselves and keeping it confidential from the server. This dependency creates a verification vulnerability: if the auxiliary information is leaked, the verification method may be circumvented. Additionally, in some privacy-sensitive scenarios (e.g., commercial federated learning), the global model may need to be kept confidential from an untrusted server. However, only a few works achieve the output privacy while addressing verification vulnerability, at the cost of prohibitive computation and communication overhead. To address these challenges simultaneously, we propose a novel provably privacy-preserving FL method called EIFL. Specifically, we adopt a two-stage aggregation and combine it with symmetric encryption to protect the output privacy. To address the verification vulnerability, we propose an efficient verification method based on vector inner product for output integrity, and a random vector generation method for clients to agree on auxiliary information. EIFL innovatively binds the auxiliary information to the output integrity, and eliminates the need to keep the auxiliary information confidential from the server. Moreover, EIFL is robust against client dropout during the verification phase through a simple resending operation. Evaluation results validate the advantages of EIFL over state-of-the-art schemes in terms of computation and communication overhead.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.11218v1">BRACE: Differential Privacy for Dense Associative Memory with LSR Energy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-08T04:13:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chang Qu, Zhaoyang Shi</p>
    <p><b>Summary:</b> Dense associative memory (DAM) provides an energy-based framework for memory retrieval with close connections to attention mechanisms in modern artificial intelligence. Despite growing interest in differential privacy for AI, the privacy of DAM retrieval dynamics remains relatively unexplored. In this paper, we develop a differential privacy framework for log-sum-ReLU (LSR) dense associative memory, whose finite-support retrieval dynamics pose distinctive challenges for privacy-preserving computation. We propose the Boundary-Responsive Adaptive Correction Evolution (BRACE) algorithm, a differentially private retrieval mechanism for LSR-DAM that adaptively corrects boundary-sensitive perturbations to control their cumulative effect over the retrieval trajectory. In theory, we prove that our method is minimax optimal by deriving dimension-independent terminal and full-trajectory retrieval error rates, with optimal dependence on the inverse temperature and, in the growing-horizon regime, the retrieval horizon. We further establish central limit theorems that enable uncertainty quantification for private retrieval by characterizing its asymptotic distribution and the additional variability introduced by privacy. Numerical experiments compare our proposed method with baseline differential privacy approaches and evaluate its retrieval accuracy. Together, our results provide a theoretical foundation for optimal privacy-preserving retrieval and uncertainty quantification in energy-based associative memory systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.14071v1">Loose Lips: Understanding Privacy Leakage in Agentic Dialogue</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-10-07T23:25:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Soumya Sharma, Ayana Hussain, Heber Hwang Arcolezi, Ulrich Aïvodji, Spandana Gella, Adriana Romero-Soriano, Golnoosh Farnadi</p>
    <p><b>Summary:</b> As LLM agents are increasingly deployed in high-stakes enterprise settings, understanding how they handle sensitive information in agentic dialogue has become critical. Privacy leakage in such settings requires reasoning about whether information flows respect the contextual norms under which they originated. We extend CIMemories to CIMEMORIES DIALOGUE, a benchmark of 4,410 two-agent dialogue instances grounded in Contextual Integrity theory. Using this benchmark, we systematically evaluate 7 open-weight models from the Qwen3 and Llama 3.1 families across conversation lengths of 1 and 6 turns under three prompting conditions. We find that task capability and privacy leakage are fundamentally coupled: more capable models are systematically leakier, with no model in our evaluation able to decouple the two. Thinking models consistently leak more than their non-thinking counterparts, a pattern we attribute to the extended reasoning surface created by chain-of-thought. Leakage compounds with conversation length, rising up to 3x from 1 to 6 turns. Our results suggest that the coupling between task capability and privacy leakage is not an artifact of misconfiguration but a structural feature of current agentic systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.10702v1">Combining Error Verification and Privacy Amplification in Quantum Key Distribution</a></h3>
  
  <p><b>Published on:</b> 2026-10-07T18:00:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Devashish Tupkary, Zhiyao Wang, Ernest Y. -Z. Tan</p>
    <p><b>Summary:</b> Quantum Key Distribution (QKD) protocols typically involve two separate steps of error-verification and privacy amplification. Both steps involve the application of a hash function sampled from a suitable hash family to classical data. A potentially simpler alternative is to implement a single-step hashing procedure, announce and compare a fixed number of bits of its output for error-verification, and retain the remaining bits as the final output key. This reduces the complexity of classical postprocessing, the amount of classical communication, and the amount of randomness needed in the protocol. While this construction has appeared in the literature, a suitable mathematical justification is lacking. In this work, we show that the security of such protocols, under certain simple conditions, follows from a slightly modified notion of secrecy of the protocol without the final error-verification step. In particular, we show that for most entropy-based proofs, the combined protocol can be implemented with no change to the key rate, and a minor change to the security parameter.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.10002v1">The Price of Privacy: Randomness Complexity of Graph-Based Multi-Secret Sharing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-07T12:59:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Piotr Marszalik</p>
    <p><b>Summary:</b> We study the randomness required to share possibly correlated secret bits among parties connected by a graph. A dealer places shares on the edges so that each party can recover its own secret from its incident shares and learn nothing about the others beyond what its own secret reveals. Anilkumar et al. completely determined the minimum randomness required for three binary secrets. We extend this study to four secrets and obtain results for arbitrary numbers of secrets on general graphs. For four parties on a complete graph, we determine the minimum number of random states for every set of permitted secret combinations: the possible values are one, two, three and four. We also characterize when one random bit suffices on an arbitrary graph.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.10616v1">When Routing Reveals Membership: Privacy Leakage from MoE Router Telemetry</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-07T07:26:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yixin Tan, Jiayang Liu, Lu Sun, Yuke Hu, Zheng Li, Rui Wen</p>
    <p><b>Summary:</b> Mixture-of-Experts (MoE) language models produce routing information during inference that may be logged or exposed for monitoring, debugging, load analysis, and safety auditing. Unlike ordinary model outputs, this telemetry reveals a view of the model's internal computation, raising a privacy question: can it reveal whether an example was used to fine-tune the deployed model? We introduce a router-augmented membership inference attack that combines conventional output-side signals with aggregated routing features and applies a membership classifier learned from independently fine-tuned shadow models to the target model. Across three MoE architectures and three data domains, router telemetry consistently improves membership inference over a strong output-signal ensemble, increasing TPR at 1\% FPR by 2.7--9.4 percentage points across all nine settings. The leakage persists across full fine-tuning, frozen-router training, LoRA, and instruction tuning, and remains observable with only discrete expert selections, restricted telemetry, or a single shadow model. Mechanistic analysis further shows that the leakage does not require router-specific memorization: fine-tuning introduces membership information into hidden representations, while the router exposes a projection of this signal even when its parameters are frozen. Perturbing the telemetry reduces this additional leakage only as its fidelity degrades. Our results show that router telemetry can turn an operational signal into an additional privacy surface for fine-tuned MoE models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.09288v1">FaceKit: a Toolkit for Interpretable Facial Phenotyping, Synthetic Image Generation and Privacy Analysis in Rare Diseases</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-10-07T01:43:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hongzhuo Chen, Zhanliang Wang, Florent Pollet, Mian Umair Ahsan, Joshua Bie, Tzung-Chien Hsieh, Peter Krawitz, Cong Liu, Wendy K Chung, Chunhua Weng, Gamze Gürsoy, Kai Wang</p>
    <p><b>Summary:</b> Many rare genetic diseases are associated with recognizable craniofacial features. However, traditional approaches for describing facial morphology rely largely on qualitative clinical observation and free-text descriptions, which are often subjective, non-standardized, and difficult to reproduce across observers and institutions. Although the Human Phenotype Ontology (HPO) provides controlled terms for describing facial features, these terms are typically categorical rather than quantitative and may vary depending on examiner experience and interpretation. Here, we present FaceKit, a computational framework for quantitative facial phenotyping from frontal facial photographs. FaceKit extracts standardized measurements of facial landmarks and derived 120 morphological features, then reports feature-level z-scores representing deviation from population reference distributions. The reference distributions are built from the FairFace dataset spanning diverse ancestral groups. We evaluated FaceKit on a curated subset of the GestaltMatcher Database covering 50 rare-disease cohorts. In addition to quantitative facial analysis, FaceKit includes synthetic facial image generation to support rare disease model development and data augmentation. We also performed privacy evaluation to assess whether synthetic images reveal identifiable information from real patient photographs and could compromise patient privacy. Across disease case studies, FaceKit-derived quantitative measurements captured known facial features associated with rare genetic disorders and provided objective support for clinical phenotyping. Together, these results establish FaceKit as a useful tool for quantitative phenotyping, and has the potential to improve rare disease diagnosis, support genotype-phenotype studies, and enable more reproducible clinical characterization across diverse patient populations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.08414v2">Image Bitstream Fine-grained Understanding for Privacy-Friendly AIoT</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-10-06T14:18:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhen Yu, Wenyang Liu, Kejun Wu, Chengwang Xiao, Renjie Qiao, Chengtao Cai</p>
    <p><b>Summary:</b> Image Bitstream Fine-grained Understanding (IBFU) aims to directly perform fine-grained classification and semantic description generation from encoded image byte sequences. In contrast to conventional pixel-domain visual understanding, IBFU conducts semantic analysis without fully decoding images into the pixel domain. Since pixel-level visual content is not explicitly reconstructed during inference, this paradigm reduces visual exposure within the processing pipeline and suits privacy-friendly Artificial Intelligence of Things (AIoT) applications. In this paper, we propose Bitstream Fine-grained Generator (BFG), a novel foundation model tailored for IBFU. BFG consists of two main components: a Bitstream Semantic Encoder (BSeE) and a Fine-grained Semantic Generator (FSeG). BSeE directly models semantic representations from encoded image bitstreams without explicit pixel reconstruction, while FSeG transforms the extracted bitstream semantics into detailed natural-language descriptions through autoregressive generation. To train BFG and comprehensively evaluate IBFU in practical AIoT scenarios, where image bitstreams may suffer corruption during transmission and storage, we construct a large-scale Corrupted-bitstream Fine-grained Understanding dataset (CFU-D), containing both intact bitstreams and corrupted variants across multiple corruption types and severity levels. Experiments show that BFG maintains stable fine-grained caption generation under bitstream corruption. For example, the performance only has slight change from 0.6339 to 0.6077 in terms of average CIDEr score on Stanford Dogs Caption dataset, while vision-language models, such as Qwen-VL-Chat, BLIP-2, GLM, Gemini, and GPT suffer severe performance decrease. This paper provides a practical paradigm for privacy-friendly fine-grained understanding in AIoT.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.08255v1">HE-OFT: Privacy-Preserving One-Shot Federated Fine-Tuning under Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-06T12:35:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Halil İbrahim Kanpak, Sinem Sav, Alptekin Küpçü</p>
    <p><b>Summary:</b> Many organizations adapt large pretrained models to their own tasks by fine-tuning on private data. Several of these parties often hold data for the same task and wish to fine-tune a model together without pooling that data. Federated learning (FL) enables joint fine-tuning, but reconstruction attacks on shared intermediate values (the model or its gradients) remain a privacy risk. A one-shot protocol that exchanges one encrypted contribution exposes no intermediate value. Such a protocol still gives the trained model to every participant, which is not permitted where the model is a regulated or proprietary asset. We present HE-OFT, the first cryptographically secure one-shot federated fine-tuning protocol in which no party receives the trained model. Each client fine-tunes a low-rank adapter and a classifier head on a frozen public backbone and keeps the adapter. The client uploads one encrypted head displacement, which the server combines under multiparty CKKS and never decrypts. A quorum of clients returns only the predicted label to the querier. On four text classification tasks and one vision task, HE-OFT reaches 61 to 79 per cent accuracy, against 20 to 48 per cent for a client training alone. HE-OFT keeps 85 to 96 per cent of the accuracy of a disclosed model. A test-time query takes 443.1 to 1713.1 s on one core, or 56.1 to 255.1 s with level restoration on a GPU. Restoring levels at the server cuts the traffic per query from up to 1.6 GiB to 13.5 MiB.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.08174v1">FBAN: A Fully Homomorphic Encryption Compatible Bottleneck Attention Network for Privacy-Preserving Behavioral Authentication</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-06T11:28:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jichao Xiong, Atsuko Miyaji, Jiageng Chen</p>
    <p><b>Summary:</b> Continuous authentication (CA) strengthens session security by repeatedly verifying the user during device interaction, yet it inherently relies on highly sensitive behavioral traces (e.g., fine-grained touch dynamics) that are often outsourced to cloud/edge services for scalable inference. This raises a fundamental privacy-in-use challenge: protecting behavioral features during computation, not only in transit or at rest. Fully homomorphic encryption (FHE) offers a principled solution, but deploying modern CA models under FHE remains difficult due to non-linearities and attention-style operations that incur high ciphertext cost.
  We propose FBAN, a TFHE-compatible Bottleneck Attention Network and an end-to-end encrypted CA framework. FBAN is designed for integer-only execution via a two-stage pipeline (floating-point pretraining followed by quantization-aware training) and is compiled into TFHE circuits for homomorphic inference. We further specify a client-server protocol with session-bound blinding and decrypt-and-return verification, enabling the server to authenticate users without observing raw behavioral features. We provide a cryptographic security analysis against an honest-but-curious server under TFHE IND-CPA security, and formalize resistance to replay and impersonation without the TFHE secret key. Experiments on two public touchscreen datasets demonstrate that FBAN achieves strong authentication utility under encrypted inference while maintaining a lightweight model footprint, with TFHE parameters instantiated at $\geq 128$-bit security.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.07976v1">Quantifying the Privacy Posture of Operator-Side 5G/O-RAN Profiles</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-10-06T08:42:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nikolaos Kekatos, Apostolos Valiakos, Alexios Lekidis, Elpiniki Papageorgiou</p>
    <p><b>Summary:</b> Operator-side network profiles derived from 5G/ORAN traffic carry personal data such as ephemeral subscriber identifiers, slice-level KPIs, and control-plane signalling, and must be anonymised before release to a federated-learning aggregator, threat-intelligence exchange, or ML training pipeline. We study how much re-identification risk remains after standard operator-side anonymisation. We quantify privacy posture with k-anonymity, l-diversity and t-closeness, aggregate them into a composite Privacy-Posture Index (PPI), and measure residual re-identification across eight transformation configurations on internal PCAP captures and the public Idaho Labs 5GAD corpus, under a full-QI syntactic bound and two simulated adversaries. The evaluation is modest in scale, and we read its trends as indicative rather than definitive. Three findings emerge. Pseudonymisation alone leaves re-identification unchanged; material privacy gains arise when quasi-identifiers are coarsened through generalisation, optionally combined with suppression. A downstream classification task then shows that suppression-heavy releases retain majority-class utility but sacrifice much of their minority-class recall, a cost the aggregate metrics hide. Finally, the standard kmin-based PPI correlates only modestly with the disclosure bound and not at all with the partial-knowledge attack, whereas a mean-class-size variant PPI correlates strongly with all three disclosure/attack measures; we therefore read PPI as a regulator-facing summary, not a security bound. The profiles are produced by passive operator-side monitoring with rule-based DPI; our contribution is the privacy-quantification layer that computes these metrics, applies the transformation policy, and exposes both through an inspectable dashboard.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.07677v1">Adaptive Model Inversion Attacks Generalize a Privacy-Robustness Tradeoff</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-06T03:11:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shailen Smith, Rasmus Torp, Adam Breuer</p>
    <p><b>Summary:</b> In this paper, we show that standard evaluations of high-resolution Model Inversion Attacks (MIAs) significantly underestimate training-data privacy leakage. State-of-the-art privacy defenses, standard training techniques such as MixUp and Adversarial Training, and undefended models all leak training images at rates 1.16 to 6.59 times higher on FaceScrub under simple adaptive changes to the attack, with the largest increases among defenses reporting the strongest privacy. We further show that measured leakage depends on the feature basis of the external classifier used to evaluate reconstructions: for the same reconstructed images, an adversarially trained Inception evaluator identifies the targeted identity at different rates than the standard Inception evaluator. Our results suggest that standard MIA evaluation can mistake optimization and measurement failures for privacy.
  These underestimated leakage rates also concealed a broader relationship between privacy and adversarial robustness. Once we adapt the attack and vary the evaluator, reconstruction leakage closely tracks adversarial robustness across recent defenses and standard training regimes, suggesting that robustness provides an attack-agnostic proxy for reconstruction vulnerability that applies far more broadly than previously theorized. This raises an open question: can a practical defense reduce training-data reconstruction without paying a corresponding cost in adversarial robustness?</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.07399v1">Fed-BRDECS: Privacy-Preserving and Heterogeneity-Aware Federated Deep Embedded Clustering</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-05T21:11:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haemin Park, Diego Klabjan, Martin W. Braun, Xiuqi Li, Balakrishnan Ananthanarayanan</p>
    <p><b>Summary:</b> Federated deep clustering seeks to learn clustering-friendly representations from decentralized unlabeled data while preserving client privacy. However, Deep Embedded Clustering (DEC)-style objectives depend on global soft-assignment statistics that require clients to reveal their sensitive information. We propose Fed-BRDECS, a privacy-preserving and heterogeneity-aware federated deep embedded clustering framework. Fed-BRDECS replaces the globally normalized clustering objective with a locally computable sample-stability loss, avoiding the transmission of local soft-assignment distributions. To tackle non-IID client distributions, we introduce prediction-balanced sampling, which oversamples locally rare predicted clusters without requiring ground-truth labels, and centroid-level restarting, which periodically refreshes biased or inactive centroids. Experiments on image and text clustering benchmarks show that Fed-BRDECS consistently outperforms representative federated clustering and deep clustering baselines under both IID and non-IID partitions. We further demonstrate its applicability to federated time-series anomaly detection, where it improves reconstruction-based detectors without adding inference-time cost.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.07258v1">Lineage-Aware Memory Governance: A Derivation-Gated Framework for Privacy-Preserving Column-Level Access Control in Enterprise AI Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-05T18:56:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Venkata M Sangaraju, Sudhir Vissa</p>
    <p><b>Summary:</b> Enterprise AI agents that share a memory store face two unaddressed risks: sensitive data can leak through legitimately computed results the requester could not derive, and departments can silently compute a same-named key performance indicator (KPI) through conflicting logic. Existing agent-memory systems (e.g., MemGPT, Zep, A-MEM) gate retrieval by content, ownership, and role, not derivation, missing a cached insight that embeds a forbidden column. We introduce the Analytical Memory Unit (AMU), a memory schema that attaches a full derivation (lineage) graph to every cached result, gated by a retrieval policy that serves a hit only when the requester is authorised for every column touched. Provided lineage recording is complete, we prove by construction that the policy blocks retrieval of results derived from a sensitive column outside the requester's permissions, at O(n) worst case -- a conditional design guarantee, not an empirical claim, that excludes derived features encoding sensitive information without naming their source. Eliminating measured leakage required 75-90% recorded lineage completeness, so we treat 90% as a conservative deployment target. Across six experiments, lineage-gated retrieval removes the 18.8-25.5% cross-department leakage naive content-gated memory suffers, keeping 81.5-82.6% of memory reuse at 13.8 microsecond worst-case overhead. A real-agent proof-of-concept with LLM-generated SQL is consistent with the guarantee: zero leaks over 9 round-trips, two conflicts caught automatically -- though a feasibility demonstration, not evidence of production viability. This offers a practical governance layer for shared agent memory, complementing source-layer access control and supporting EU AI Act compliance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.07238v1">The Cost of Differential Privacy in Linear-Quadratic Dynamic Games</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E">
  <p><b>Published on:</b> 2026-10-05T18:43:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chih-Yuan Chiu, Matthew Hale</p>
    <p><b>Summary:</b> Multi-agent coordination often requires strategic agents to share sensitive information about their states or objectives, creating a tension between performance and privacy. Our paper studies this tradeoff in stochastic linear-quadratic (LQ) dynamic games with heterogeneous agent objectives. In our framework, agents share noise-perturbed state and reference information with a cloud computer that computes feedback Nash equilibrium strategies, with the injected noise calibrated to provide differential privacy. We derive an analytical expression for each agent's infinite-horizon steady-state cost of privacy relative to the non-private game. Then, we prove that when agents' objectives are sufficiently aligned, the injection of privacy noise necessarily incurs a positive performance cost. In contrast, we characterize a class of games with sufficiently misaligned objectives across agents for which an agent's cost of privacy can be strictly negative. Thus, counterintuitively, noise can simultaneously protect privacy and improve the equilibrium performance of an agent when the objectives of interacting agents are sufficiently misaligned. Finally, we present numerical experiments which corroborate our theoretical contributions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.07212v1">Reward-Driven Learning under Prompt-Level Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-05T18:26:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiachen Zhao, Antonia Januszewicz, Taeho Jung</p>
    <p><b>Summary:</b> Reinforcement learning with verifiable rewards (RLVR) trains a language model on problems that may themselves be confidential, and the trained model can reveal which problems it saw. We study RLVR under prompt-level differential privacy: the released weights must be (ε,δ)-differentially private with respect to the presence of any one training problem. Taking the group of responses to one prompt as the privacy record, our method aggregates their gradients, clips the prompt's contribution once, adds Gaussian noise, and composes the privacy loss across updates, so the budget depends on neither the number of responses per prompt nor the clipping norm; to our knowledge this is the first differential privacy guarantee for RLVR training. We train Qwen2.5-1.5B-Instruct with LoRA at a per-run budget of ε=8 and compare, on the same prompts and at the same budget, a control that removes only the reward signal and two private supervised fine-tuning recipes. The reward signal improves accuracy over the control by 2.65 points on MATH and 3.24 on GSM8K, in every seed; the improvement survives a format-robust scorer, at 1.3 points on MATH, and is not explained by response length. At the same budget the private model outperforms both supervised recipes on MATH and GSM8K by 2.3 to 3.8 points, retains 85--90% of the gain of non-private GRPO on these tasks, and on MATH the noise of an eightfold tighter budget costs at most 1.2 points. The reward effect also carries to CommonsenseQA, an exploratory non-mathematical task. Verifier feedback thus remains a usable learning signal under prompt-level privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.06454v1">AgentPrivArena: Evaluating and Auditing Real-world AI Agent Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-10-05T14:55:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shouju Wang, Haopeng Zhang</p>
    <p><b>Summary:</b> The rapid advancement of LLM agents has enabled systems to autonomously perform complex tasks through external tools, but their growing access to personal data introduces significant privacy risks. Existing benchmarks primarily evaluate LLM agent privacy through simulated trajectories and outcome-based metrics, limiting their ability to capture privacy risks arising during multi-step agent execution. In this work, we introduce AgentPrivArena, a framework for evaluating privacy risks in realistic LLM agent workflows. AgentPrivArena integrates authentic MCP tools and self-hosted services within a reproducible execution environment. We further propose trajectory-level privacy metrics that quantify unnecessary information access beyond final response leakage. Building on this framework, we introduce AgentPrivAudit, a runtime auditing approach for monitoring privacy violations during agent execution. Extensive experiments on state-of-the-art LLM agents reveal substantial privacy risks overlooked by existing evaluation paradigms, highlighting the importance of trajectory-level auditing for trustworthy agent deployment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.05867v1">Learning Sparse Support under Differential Privacy: Adaptive Algorithms and Minimax Limits</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">
  <p><b>Published on:</b> 2026-10-05T06:32:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jia Gu, T. Tony Cai</p>
    <p><b>Summary:</b> We study exact support recovery under $(ε,δ)$-differential privacy in sparse high-dimensional linear regression. We introduce Saturated Propose-test-release, a general mechanism that privately releases the output of a discrete selector with probability one once its stability certificate reaches a finite threshold. Exploiting the coordinatewise geometry of the LASSO, we construct a computable support-stability score. The resulting computationally efficient Saturated LASSO satisfies worst-case $(ε,δ)$-differential privacy and achieves exact support recovery with high probability under explicit regularity and beta-min conditions. Maximizing sparsity-indexed certificates yields an adaptive procedure requiring no sparsity knowledge and having exactly the same finite-sample exact-recovery risk as the oracle fixed-sparsity procedure under common public tuning parameters. We also establish a minimax lower bound explicitly tracking $δ$: under its recovery conditions, Saturated LASSO is minimax optimal up to logarithmic factors in $n$ and $1/δ$ uniformly over $0 < δ\leq ε/16$; in the broad moderate-$δ$ regime, it further matches the lower-bound $δ$-dependence. A complementary information-theoretic construction with known sparsity attains the lower-bound rates up to constant factors under independent Gaussian design, at exponential computational cost. Simulations and a semi-synthetic study using public American Community Survey covariates illustrate the numerical performance of the proposed procedures.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.05561v1">Beyond Monolithic Perturbation: Heterogeneous Mechanism Design for Multi-Attribute Metric Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-04T21:48:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruiyao Liu, Michael Oluwole, Chenxi Qiu</p>
    <p><b>Summary:</b> Multi-attribute user records are inherently heterogeneous, often combining continuous, categorical, and binary attributes, and they frequently exhibit strong cross-attribute dependencies. Designing high-utility metric differential privacy (mDP) mechanisms for such records is challenging. Simple predefined mechanisms, such as distance-based noise, may be poorly aligned with task-specific utility loss, whereas fully optimization-based mechanisms can be computationally prohibitive for multi-attribute records.
  We propose Dependency-aware Heterogeneous Data Perturbation (DepHDP)}, a framework for multi-attribute mDP that combines dependency-aware attribute grouping with heterogeneous perturbation design. Rather than applying a one-size-fits-all mechanism, DepHDP selects an appropriate perturbation strategy for each attribute or attribute group, choosing between efficient predefined mechanisms, such as Laplace or Exponential mechanisms, and optimization-based designs. This selection is guided by both domain size and a predefined-noise adequacy criterion, which quantifies whether task-induced utility loss can be well explained by perturbation magnitude. To support scalable end-to-end optimization, DepHDP estimates group-level utility loss through sampling and lightweight surrogate modeling, and jointly optimizes privacy-budget allocation and group-wise mechanism design under a global $\ell_p$-metric mDP constraint. Across three case studies, DepHDP improves privacy--utility trade-offs over uniform baselines at lower computational cost than full-record OPT on evaluated domains.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.05475v1">Poor Privacy Practices Of The Apple App Store: Cookies, Advertising and Tracking Of Users</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-10-04T19:34:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Douglas Leith</p>
    <p><b>Summary:</b> We analyse the data that the Apple App Store sends to and receives from Apple servers. We find that multiple cookies are sent by Apple servers and stored on the handset. Adverts with tracking identifiers are also stored on the handset, and we observe that adverts are selected by Apple servers using GDPR special category personal data such as sexuality, religious beliefs and health. User interactions with the Apple App Store (apps and adverts viewed, buttons clicked, searches made etc) are transmitted to Apple servers alongside identifiers linking this data to the individual user and device. We show that much of this data storage and transmission is not essential for the service requested by the user, namely to view, search and install apps. No consent is sought for any of this data storage and processing, and there is no opt out.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.05453v1">The Poisoned Conversation: Privacy-Leaking Watermarks in Unified Multimodal Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-04T18:53:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tobias Braun, Jonas Henry Grebe, Emil Sivic, Patrick Mohr Gordillo, Hossein Shakibania, Marcus Rohrbach, Anna Rohrbach</p>
    <p><b>Summary:</b> Multimodal models are increasingly shifting toward unified architectures that understand and generate text, images, and other modalities within a shared conversational context. This design enables fluid interaction across modalities, but it also changes the privacy threat model: Information revealed in one part of a conversation may remain accessible when the model later generates content in another modality. This risk is particularly concerning in settings where users rely on locally deployed models for privacy, assuming that sensitive interactions remain confined to their device. We introduce Privacy-Leaking Watermarks (PLWs): invisible, trigger-dependent watermarks that a malicious model provider can condition on prior chat history. With this adversarial intervention, the usual separation breaks: a sensitive keyword or semantic cue mentioned earlier in the conversation can cause a later, unrelated image to carry a hidden yet detectable watermark. PLWs pose a novel threat to users of unified multimodal models: A poisoned model can retain utility while covertly turning image generation into a channel for privacy leakage, even when deployed locally. Across 13 sensitive-attribute triggers and two model families, PLWs reach up to 100.0% TPR at 1% FPR. For example, across all tested conversational separations, OmniGen2 detects every prior disclosure of depression while falsely flagging only 1% of images generated without such a disclosure.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.06998v1">Order-Optimal Coded Caching With File and Demand Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-10-04T08:18:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Han Fang, Nan Liu, Wei Kang</p>
    <p><b>Summary:</b> We study coded caching with joint file and demand privacy: each user recovers its requested file while learning nothing about the remaining files and the other users' requests jointly. Let $N$ and $K$ be the numbers of files and users, and let $M$ and $R$ denote the cache memory and delivery rate, both normalized by the file size. For every $N,K\ge2$ and every feasible cache size, we give a scheme whose worst-case delivery rate is at most $9/2$ times the optimum. To reduce the memory used for file shares, the scheme secret-shares $N-1$ differences relative to a reference file. Cached masks supply the correction needed to recover the requested file from its difference. For each integer $t\in\{0,\ldots,K-1\}$, the scheme achieves $M=1+(N-1)t/(K-t)$ and $R=K/(t+1)$. To lower-bound the delivery rate, we compare the joint cache entropy of user groups under alternative demand vectors, using one fixed user's privacy constraint. Two choices of groups determine the optimal delivery rate up to constants at the scale $\min\{K,1+(N-1)/(M-1)\}$ for $M>1$. At $M=1$, the exact optimum is $K$. A complementary bound on joint broadcast entropy gives the minimum memory for unit delivery rate, $1+(N-1)(K-1)$, and the exact tradeoff on an interval ending at that memory. All schemes and bounds apply to repeated as well as distinct requests.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.04985v1">Hidden Risks of Jev: An Empirical Study of Security, Privacy, and Dual Use</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-10-04T06:09:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shang Wang, Tianqing Zhu, Huajie Chen, Jiayang Li, Meng Yang, Bo Liu</p>
    <p><b>Summary:</b> Jev turns natural-language questions into typed answers and probabilities with low latency and cost, enabling applications to route requests and select tools. While this interface allows Jev to integrate naturally into application workflows as a decision layer, the security and privacy implications of this emerging use remain largely unexplored. To address this gap, we conduct the first systematic study of these implications using the official Jev API and NanoJev, a local model with controllable training data and updates, focusing on three research questions: (1) What security threats arise when Jev is deployed as an application decision layer? (2) What private information can Jev reveal despite returning constrained typed outputs? (3) How can Jev's general-purpose decision capability be used for beneficial purposes or misused?
  Jev's decisions depend on application state and may be influenced by user-provided inputs. We therefore adapt prompt injection and adversarial suffixes to manipulate its decisions. Open-source Jev distribution and updates introduce supply-chain risks, which we examine by implanting backdoors in NanoJev through training data poisoning. Since Jev's outputs reflect both application state and information learned during training, we further adapt membership, private attribute, and internal knowledge inference attacks to recover sensitive information despite its constrained output format. Finally, Jev can serve as a general-purpose decision oracle for defensive and malicious workflows. We examine this dual use through four detection tasks covering prompt injection, jailbreak inputs, harmful content, and AI-generated text, alongside misuse scenarios involving jailbreak and model extraction. Our empirical evaluation shows that Jev remains vulnerable to the examined security and privacy threats, while its decision capability can support beneficial and malicious uses.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.04600v1">Asymptotically Optimal Best Arm Identification with Fixed-Budget under Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-10-03T15:38:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Keqin Chen, Jie Bian, Yulian Wu, Vincent Y. F. Tan</p>
    <p><b>Summary:</b> Best arm identification under differential privacy is a pure-exploration problem in which both statistical efficiency and privacy protection must be achieved simultaneously. We study fixed-budget best arm identification for bandits under pure $ε$-differential privacy, where the learner must recommend an arm after a prescribed sampling budget while protecting the full transcript. We prove that the optimal exponential decay rate of the error probability is upper bounded by an instance-dependent privacy-aware transportation exponent that differs from the analogous quantity used to characterize the stopping time in fixed-confidence analysis by Jourdan and Azize [2025]. Guided by this exponent, we propose AO-Pri-BAI, an adaptive algorithm that maintains private running estimates through Laplace-tree mechanisms and learns a sampling design through a min--max interaction between hard alternatives and arm allocations. We prove that AO-Pri-BAI satisfies pure $ε$-differential privacy. We also establish that the exponent of the failure probability of AO-Pri-BAI matches the privacy-aware benchmark. Numerical studies show that even in the non-asymptotic setting, AO-Pri-BAI outperforms benchmark algorithms on various instances, complementing the theoretical analyses.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.04060v1">Auditing the Privacy of Synthetic Gene Expression Data: A Unified Weighted-Distance Framework for No-Box Membership Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-02T21:14:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Owen Tucker, Lily Wang, Harutoshi Okumura, Ruixuan Liu, Li Xiong</p>
    <p><b>Summary:</b> Synthetic gene expression data is increasingly proposed as a privacy-preserving substitute for controlled-access genomic repositories, but its safety depends on empirical auditing. Membership inference attacks (MIAs) provide that audit by testing whether a patient's gene expression profile was used to train a generative model. We report a red-team study on synthetic gene expression data derived from bulk RNA-seq profiles in The Cancer Genome Atlas, released by the ELSA Health 2026 Challenge. We unify five no-box attacks under a single weighted-distance framework in which each variant differs only in how it weights genes: uniformly (baseline), by variance, by synthetic-versus-reference KL divergence, by spectral residualization removing dominant principal components, and by curated pathway membership. Against a conditional variational autoencoder, spectral residualization raises AUC from 0.8251 to 0.8951 and TPR at 1% FPR from 0.3842 to 0.5970 on pan-cancer TCGA. Biological pathway priors did not transfer across targets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.04042v2">Assessing Acceptance and Privacy Preferences of Third-party Financial Data Sharing in Bipolar Disorder</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-10-02T20:50:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jeff Brozena, Johnna Blair, Dahlia Mukherjee, Erika F. H. Saunders, Thomas Richardson, Mark Matthews, Saeed Abdullah</p>
    <p><b>Summary:</b> Bipolar disorder is strongly associated with financial instability. We examine how different interventions motivate individuals with bipolar disorder to share financial data with others. This approach can inform the development of tools for digital monitoring and intervention designed to promote financial stability in this population. 500 individuals with BD completed a pre-registered factorial vignette survey to examine level of comfort with hypothetical scenarios involving third-party financial interventions during symptomatic and euthymic periods. Scenario components were systematically varied between third-party actors, mood states, and intervention types. Participants rated sharing comfort on a 0-10 point scale. Multilevel models tested differences alongside clinical and financial histories, relational trust, and personality. Participants were most comfortable involving care partners in financial planning. They were more comfortable with temporary spending restrictions during symptomatic states than euthymic periods, underscoring the importance of accurate mood detection for intervention delivery. Prior financial help-seeking behavior and higher relational trust predicted greater comfort. Bankruptcy experience --- declared by 11.4% and considered by 31.7% --- was associated with increased comfort with spending restrictions. Individuals with psychiatric advance directives (8%) were significantly more comfortable sharing spending behaviors than those without. Comfort with financial interventions was higher among those with prior financial challenges or help-seeking histories. Participants distinguished between symptomatic and euthymic periods, favoring targeted, time-limited restrictions over general monitoring. These findings extend prior work on financial data sharing for illness self-management.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.02943v1">Kinematics-Induced Multimodal 3D Human Pose Estimation with Subject-Level Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-10-02T07:37:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kaushik Bhargav Sivangi, Fani Deligianni</p>
    <p><b>Summary:</b> Multimodal 3D Human Pose Estimation (3D HPE) combines complementary information from RGB, LiDAR, and mmWave radar, but models trained on correlated observations from the same individuals, raise privacy risks overlooked by record level analysis. We present a unified framework for multimodal 3D HPE that couples kinematics-induced sensor fusion with subject level privacy auditing and private training. First, our multimodal model aligns modality specific joint representation, injects skeletal structure and adaptively aggregates complementary sensor evidence for accurate pose prediction. Second, we formulate a black-box subject membership inference attack for 3D HPE, complemented by an empirical pointwise maximal leakage analysis, which characterizes how individual attack score outcomes change inference about the membership outcome. Third, we instantiate user-level differential privacy via Action Temporal Stratification, a population weighted within-subject sampling strategy that enforces action and temporal coverage. We evaluate our framework on the MM-Fi dataset across three diverse experimental protocols. Source-code will be released upon acceptance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.02716v1">Differential Privacy of Gradient Descent on Perturbed Objectives</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2026-10-02T02:52:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Austin Watkins, Raman Arora</p>
    <p><b>Summary:</b> Objective perturbation adds a random linear term to a regularized empirical risk and releases the exact perturbed minimizer. We study the finite computation obtained by releasing the $N$-th iterate of deterministic gradient descent on $w\mapsto F(w;S)+\langle z,w\rangle$, where $z\sim\mathcal N(0,σ^2I_d)$ is drawn once before optimization. For strongly convex and smooth objectives with Lipschitz Hessian, we prove an explicit condition under which the map $z\mapsto w_N$ is a $C^1$-diffeomorphism on the bounded domains used in the privacy argument, with a quantitative lower bound on the smallest singular value of its Jacobian. This permits a direct change-of-variables analysis of the finite iterate. For generalized linear models, the resulting privacy-profile bound has no explicit ambient-dimension factor once the iteration condition holds, and its finite-iteration correction decreases geometrically. By letting the free truncation parameter grow slowly with $N$, we recover the corresponding exact-minimizer certificate in the limit. We also bound the expected excess empirical risk by $dσ^2/(2μ)$ plus a geometrically decreasing optimization term, and transfer the result to population risk without an additional multiplicative condition-number factor in the leading statistical terms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.02504v1">HXAI: Hierarchical Privacy-Preserving Explainable AI in Distributed Energy Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-10-01T21:26:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Poushali Sengupta, Sabita Maharjan, Frank Eliassen, Yan Zhang</p>
    <p><b>Summary:</b> Balancing electricity demand and supply is increasingly difficult due to the inherent intermittency of renewable power generation and the stochastic power consumption. Grid operators require fine-grained, decision-relevant insights into household energy consumption to manage peak loads and design responsive tariffs, but increased transparency at this level raises significant privacy concerns. Traditional methods for explainable AI (XAI) can reveal sensitive information, while standard privacy techniques often reduce the usefulness of explanations. To address this issue, we introduce HXAI, a hierarchical framework that preserves privacy while enabling reasonable explainable analysis for grid-level demand management. HXAI consists of two main components: (1) a local model that generates fine-grained explanations within a secure, private environment, and (2) a zonal model that aggregates these explanations to support grid-level analysis while enforcing privacy through flexible privacy-budget management. We explicitly limit cumulative privacy exposure under repeated operator queries and show that the proposed framework preserves decision-relevant information without compromising household privacy. Experiments on both simulated and real-world energy datasets demonstrate that HXAI provides useful insights for zonal load management while ensuring that appliance-level consumption remains local and is never transmitted to grid operators. Our results show that preserving the semantic structure of explanations, rather than minimizing numerical error, is the key to XAI under differential privacy. This framework provides a way to achieve both privacy and explainability in energy management.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.02414v1">Unifying Privacy Accounting: Information Equivalence and Information Loss</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">
  <p><b>Published on:</b> 2026-10-01T19:37:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Buxin Su, Qiaoshi Yang, Yiding Su, Chendi Wang</p>
    <p><b>Summary:</b> Differential privacy (DP) admits several notions, but the choice among them may affect both privacy analysis and utility. In this paper, we consider four mainstream curve-based privacy notions within a unified information-theoretic framework. For a fixed ordered pair of output distributions, we establish information equivalence among the two directional privacy profiles of $(\varepsilon,δ)$-DP, the pair of hypothesis-testing trade-off functions, and the extended privacy-loss distribution. The exact Rényi differential privacy (RDP) curve joins this equivalence class whenever it is finite at some order greater than one. Under this mild condition, choosing among these notions changes only their semantic interpretation and computational requirements. In contrast, taking the maximum of the directional privacy profiles or compressing the RDP curve into a single zero-concentrated differential privacy (zCDP) parameter can lose information. We quantify the information loss between the exact RDP curve and its zCDP bound for standard noise mechanisms. This gap is zero for Gaussian noise but generally positive for Gaussian-mixture, Laplace, discrete Gaussian, and Poisson-subsampled Gaussian mechanisms. Moreover, this gap grows linearly with the number of independently composed mechanisms. Our information-theoretic perspective has practical consequences. At the same certified privacy level, retaining the full RDP curve rather than using zCDP reduces the required noise variance by up to $45\%$ for Gaussian-mixture noise in workloads comparable in size to the American Community Survey. For DP-SGD on Fashion-MNIST under Poisson subsampling, an RDP-based privacy accountant improves test accuracy by up to $8.73$ percentage points compared to a zCDP-based accountant when both are calibrated to the same $(\varepsilon,δ)$ guarantee.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.02374v1">"I'm trying not to get hacked:" How Adults with Intellectual and Developmental Disabilities Navigate Security and Privacy Notifications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-10-01T18:53:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hailey L. Johnson, Julia Nonnenkamp, Bilge Mutlu, Rahul Chatterjee</p>
    <p><b>Summary:</b> Security and privacy notifications, such as login alerts, spam email warnings, and cookie consent requests, play a critical role in shaping users' responses to digital risks. Yet most notifications overlook cognitive accessibility, limiting their effectiveness for people with intellectual and developmental disabilities (IDD). We investigate how adults with IDD perceive and respond to common security and privacy notifications across mobile and web applications. Through a formative user study with seven adults with IDD, we identify three factors shaping understanding and decision-making: (1) interpretation is influenced by task and interface context; (2) unfamiliar terms, both technical and non-technical, are grounded in everyday concepts; and (3) uncertainty about outcomes leads to hesitation, avoidance, diagnostic exploration, or support-seeking. These findings lead to three design implications: (1) address context-dependent language misunderstandings beyond jargon simplification; (2) make action-outcome connections transparent; and (3) enable interdependent decision-making. Together, these insights aim to inform the design of more cognitively accessible security and privacy notifications that better support safe and supported user action.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.02113v1">Quantum Advantage for Two-Party Differential Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-10-01T17:32:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Daniel Alabi, Emil T. Khabiboulline</p>
    <p><b>Summary:</b> We introduce information-theoretically private quantum protocols for two-party Hamming distance when both parties must output the same estimate. Classically, for input length $n$, information-theoretic protocols require $Ω(\sqrt{n})$ error under pure differential privacy and $Ω(\sqrt{n}/\log n)$ error under strong approximate differential privacy, whereas computational security permits $O(1)$ error. In Klauck's honest, nonpreemptive, message-preserving model, we give an $O(n)$-communication quantum protocol with pure $\varepsilon$ quantum differential privacy (QDP) and expected error at most $\frac{2}{\sinh \varepsilon}+γ$, for every $γ>0$. For approximate $(\varepsilon, δ)$ QDP, an exact hockey-stick divergence calculation yields strictly smaller error, while preserving the $O(1)$-versus-$Ω(\sqrt{n}/\log n)$ separation for $δ=o(1/n)$. Thus, quantum communication achieves $O(1)$ information-theoretic error, matching the accuracy available classically only under computational assumptions.
  The main construction uses a guarded coherent round trip and an equal-Gram rigidity principle that prevents an honest player from retaining input-dependent complementary information. We separate this model from weaker prescribed-channel privacy, which already admits an exact classical realization, and from fully retention-robust security, against which measurement-and-abort attacks remain possible. Therefore, we identify preservation of non-orthogonal quantum messages as a resource for privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.01650v1">Combining Homomorphic Encryption and Differential Privacy in Federated Learning for Model Inspection and Availability</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-01T13:13:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ceren Yıldırım, Kamer Kaya, Sinan Yıldırım, Erkay Savaş</p>
    <p><b>Summary:</b> The increasing prevalence of decentralized data has led to a growing interest in federated learning, which enables collaborative model training without clients sharing their sensitive local data. However, FL alone does not sufficiently protect sensitive training data and is generally coupled with privacy-preserving techniques, such as differential privacy and homomorphic encryption. Although powerful, these techniques address separate concerns via different mechanisms, so relying on just one might prove insufficient or impractical for addressing challenges associated with federated learning. In this work, we propose a privacy-preserving federated learning framework that combines homomorphic encryption-based training with differential privacy-based model inspection and release. We adopt a Markov chain Monte Carlo-based Bayesian privacy estimation method to estimate the privacy of our proposed framework. Our results show that this method improves both model utility and estimated privacy over the baseline method that relies solely on differential privacy for training. In our experiments with the FEMNIST dataset, by the end of training, our method reaches a test loss of $1.09$, compared to $2.37$ for the differential privacy-only approach, while providing stronger estimated privacy protection, with the estimated posterior mean of the privacy parameter $ε$ of $4.32$, compared to $7.26$ for the differential privacy-only approach. We also show that intermittent model monitoring can preserve the encrypted training trajectory while, under our evaluated experimental setting, providing estimated privacy comparable to or stronger than the differential privacy-only approach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.01365v1">Sleeping Secrets: How Fine-Tuning Reawakens Privacy Risks in Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-01T09:36:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jianhong Li, Jiahao Chen, Yuwen Pu, Chunyi Zhou, Oubo Ma, Zhou Feng, Hangtao Zhang, Jichao Bi, Chunqiang Hu</p>
    <p><b>Summary:</b> Beyond adapting Large Language Models (LLMs) to specialized applications, fine-tuning has recently been shown to recover private information that is no longer accessible through direct queries. Previous fine-tuning recovery attacks, however, require genuine private supervision drawn from the same distribution, i.e., the previous training dataset. We argue that such recovery remains possible without such impractical knowledge. We show that LLM-generated candidates can provide sufficient supervision to recover previously learned private associations. Based on this, we propose ReGap, a data-free attack that recovers private associations using task structure, filters them by answer-token likelihood, and updates the target model via low-rank adaptation. Specifically, ReGap requires neither target answers nor auxiliary genuine private supervision. Across six GPT-2, OPT, and Qwen3 models, ReGap improves target-association recovery by 6-21 percentage points over the post-training target model. Recovery remains substantial even when the adaptation identities are disjoint from all memorized and evaluation identities, with no exact target answers appearing in the generated or selected supervision. Moreover, the same trained adapters increase recovery from 42\% to 63\% on a previously exposed checkpoint, but produce no gain on a matched checkpoint that never encountered the targets. This contrast shows that adaptation alone is insufficient to explain the observed recovery and that prior target exposure strongly affects post-adaptation recoverability. Our findings highlight that routine model customization can reawaken latent privacy risks, warranting urgent attention from the academic and industrial communities.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.01009v1">Helol Tunnel: Covert Channel Exploitation of TLS Extensibility & Privacy Features</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-01T03:55:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Reza Soosahabi, Rakesh Seal</p>
    <p><b>Summary:</b> Covert channels exploiting network protocols for data exfiltration and command-and-control (C2) are integral parts of modern cyberattacks. In search of a significant covert channel within the fabric of the Internet, we targeted the combinatorial properties of the Client Hello (CHLO) packets in the ubiquitous Transport Layer Security (TLS) protocol. The proposed Helol tunnel is a novel covert approach to embedding information in TLS Client Hello packets, which involves the strategic rearrangement of their cryptographic information elements. To sustain TLS protocol extensibility, the recent anti-ossification TLS compliance measures encourage the interactive middleboxes and next-generation firewalls (NGFWs) to preserve the parameter configuration in the Client Hello packets. Furthermore, to improve user privacy, popular Internet applications are varying their TLS CHLO parameter configurations to resist TLS fingerprinting by third-party network entities. We demonstrate the strength of the Helol tunnel to exploit these recent developments to evade NGFWs with interactive proxy and comprehensive threat protection. We also numerically show the efficacy of Helol tunneling over state-of-the-art covert channels that exploit TLS through the use of real traffic captures and public TLS fingerprinting data.</p>
  </details>
</div>

