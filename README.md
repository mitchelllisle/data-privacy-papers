
<h2>2025-11</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.01115v2">Sliced Rényi Pufferfish Privacy: Directional Additive Noise Mechanism and Private Learning with Gradient Clipping</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-30T22:22:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tao Zhang, Yevgeniy Vorobeychik</p>
    <p><b>Summary:</b> We study privatization mechanism design and privacy accounting in the Pufferfish family, addressing two practical gaps of Renyi Pufferfish Privacy (RPP): high-dimensional optimal transport (OT) calibration and the absence of a general, mechanism-agnostic composition rule for iterative learning. We introduce Sliced Renyi Pufferfish Privacy (SRPP), which replaces high-dimensional comparisons by directional ones over a set of unit vectors, enabling geometry-aware and tractable guarantees. To calibrate noise without high-dimensional OT, we propose sliced Wasserstein mechanisms that compute per-direction (1-D) sensitivities, yielding closed-form, statistically stable, and anisotropic calibrations. We further define SRPP Envelope (SRPE) as computable upper bounds that are tightly implementable by these sliced Wasserstein mechanisms. For iterative deep learning algorithms, we develop a decompose-then-compose SRPP-SGD scheme with gradient clipping based on a History-Uniform Cap (HUC), a pathwise bound on one-step directional changes that is uniform over optimization history, and a mean-square variant (ms-HUC) that leverages subsampling randomness to obtain on-average SRPP guarantees with improved utility. The resulting HUC and ms-HUC accountants aggregate per-iteration, per-direction Renyi costs and integrate naturally with moments-accountant style analyses. Finally, when multiple mechanisms are trained and privatized independently under a common slicing geometry, our analysis yields graceful additive composition in both worst-case and mean-square regimes. Our experiments indicate that the proposed SRPP-based methods achieve favorable privacy-utility trade-offs in both static and iterative settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.01109v1">How do we measure privacy in text? A survey of text anonymization metrics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-11-30T22:12:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yaxuan Ren, Krithika Ramesh, Yaxing Yao, Anjalie Field</p>
    <p><b>Summary:</b> In this work, we aim to clarify and reconcile metrics for evaluating privacy protection in text through a systematic survey. Although text anonymization is essential for enabling NLP research and model development in domains with sensitive data, evaluating whether anonymization methods sufficiently protect privacy remains an open challenge. In manually reviewing 47 papers that report privacy metrics, we identify and compare six distinct privacy notions, and analyze how the associated metrics capture different aspects of privacy risk. We then assess how well these notions align with legal privacy standards (HIPAA and GDPR), as well as user-centered expectations grounded in HCI studies. Our analysis offers practical guidance on navigating the landscape of privacy evaluation approaches further and highlights gaps in current practices. Ultimately, we aim to facilitate more robust, comparable, and legally aware privacy evaluations in text anonymization.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.00849v1">Topological Federated Clustering via Gravitational Potential Fields under Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-11-30T11:41:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yunbo Long, Jiaquan Zhang, Xi Chen, Alexandra Brintrup</p>
    <p><b>Summary:</b> Clustering non-independent and identically distributed (non-IID) data under local differential privacy (LDP) in federated settings presents a critical challenge: preserving privacy while maintaining accuracy without iterative communication. Existing one-shot methods rely on unstable pairwise centroid distances or neighborhood rankings, degrading severely under strong LDP noise and data heterogeneity. We present Gravitational Federated Clustering (GFC), a novel approach to privacy-preserving federated clustering that overcomes the limitations of distance-based methods under varying LDP. Addressing the critical challenge of clustering non-IID data with diverse privacy guarantees, GFC transforms privatized client centroids into a global gravitational potential field where true cluster centers emerge as topologically persistent singularities. Our framework introduces two key innovations: (1) a client-side compactness-aware perturbation mechanism that encodes local cluster geometry as "mass" values, and (2) a server-side topological aggregation phase that extracts stable centroids through persistent homology analysis of the potential field's superlevel sets. Theoretically, we establish a closed-form bound between the privacy budget $ε$ and centroid estimation error, proving the potential field's Lipschitz smoothing properties exponentially suppress noise in high-density regions. Empirically, GFC outperforms state-of-the-art methods on ten benchmarks, especially under strong LDP constraints ($ε< 1$), while maintaining comparable performance at lower privacy budgets. By reformulating federated clustering as a topological persistence problem in a synthetic physics-inspired space, GFC achieves unprecedented privacy-accuracy trade-offs without iterative communication, providing a new perspective for privacy-preserving distributed learning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.00734v1">Infinitely divisible privacy and beyond I: resolution of the $s^2=2k$ conjecture</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Probability-5BC0EB"> 
  <p><b>Published on:</b> 2025-11-30T05:09:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aaradhya Pandey, Arian Maleki, Sanjeev Kulkarni</p>
    <p><b>Summary:</b> Differential privacy is increasingly formalized through the lens of hypothesis testing via the robust and interpretable $f$-DP framework, where privacy guarantees are encoded by a baseline Blackwell trade-off function $f_{\infty} = T(P_{\infty}, Q_{\infty})$ involving a pair of distributions $(P_{\infty}, Q_{\infty})$. The problem of choosing the right privacy metric in practice leads to a central question: what is a statistically appropriate baseline $f_{\infty}$ given some prior modeling assumptions? The special case of Gaussian differential privacy (GDP) showed that, under compositions of nearly perfect mechanisms, these trade-off functions exhibit a central limit behavior with a Gaussian limit experiment. Inspired by Le Cam's theory of limits of statistical experiments, we answer this question in full generality in an infinitely divisible setting.
  We show that suitable composition experiments $(P_n^{\otimes n}, Q_n^{\otimes n})$ converge to a binary limit experiment $(P_{\infty}, Q_{\infty})$ whose log-likelihood ratio $L = \log(dQ_{\infty} / dP_{\infty})$ is infinitely divisible under $P_{\infty}$. Thus any limiting trade-off function $f_{\infty}$ is determined by an infinitely divisible law $P_{\infty}$, characterized by its Levy--Khintchine triplet, and its Esscher tilt defined by $dQ_{\infty}(x) = e^{x} dP_{\infty}(x)$. This characterizes all limiting baseline trade-off functions $f_{\infty}$ arising from compositions of nearly perfect differentially private mechanisms. Our framework recovers GDP as the purely Gaussian case and yields explicit non-Gaussian limits, including Poisson examples. It also positively resolves the empirical $s^2 = 2k$ phenomenon observed in the GDP paper and provides an optimal mechanism for count statistics achieving asymmetric Poisson differential privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.00638v1">Privacy Preserving Diffusion Models for Mixed-Type Tabular Data Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-11-29T21:23:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Timur Sattarov, Marco Schreyer, Damian Borth</p>
    <p><b>Summary:</b> We introduce DP-FinDiff, a differentially private diffusion framework for synthesizing mixed-type tabular data. DP-FinDiff employs embedding-based representations for categorical features, reducing encoding overhead and scaling to high-dimensional datasets. To adapt DP-training to the diffusion process, we propose two privacy-aware training strategies: an adaptive timestep sampler that aligns updates with diffusion dynamics, and a feature-aggregated loss that mitigates clipping-induced bias. Together, these enhancements improve fidelity and downstream utility without weakening privacy guarantees. On financial and medical datasets, DP-FinDiff achieves 16-42% higher utility than DP baselines at comparable privacy levels, demonstrating its promise for safe and effective data sharing in sensitive domains.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.00614v1">Hierarchical Decentralized Multi-Agent Coordination with Privacy-Preserving Knowledge Sharing: Extending AgentNet for Scalable Autonomous Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-11-29T20:07:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Goutham Nalagatla</p>
    <p><b>Summary:</b> Decentralized multi-agent systems have shown promise in enabling autonomous collaboration among LLM-based agents. While AgentNet demonstrated the feasibility of fully decentralized coordination through dynamic DAG topologies, several limitations remain: scalability challenges with large agent populations, communication overhead, lack of privacy guarantees, and suboptimal resource allocation. We propose AgentNet++, a hierarchical decentralized framework that extends AgentNet with multilevel agent organization, privacy-preserving knowledge sharing via differential privacy and secure aggregation, adaptive resource management, and theoretical convergence guarantees. Our approach introduces cluster-based hierarchies where agents self-organize into specialized groups, enabling efficient task routing and knowledge distillation while maintaining full decentralization. We provide formal analysis of convergence properties and privacy bounds, and demonstrate through extensive experiments on complex multi-agent tasks that AgentNet++ achieves 23% higher task completion rates, 40% reduction in communication overhead, and maintains strong privacy guarantees compared to AgentNet and other baselines. Our framework scales effectively to 1000+ agents while preserving the emergent intelligence properties of the original AgentNet.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.00595v1">IslandRun: Privacy-Aware Multi-Objective Orchestration for Distributed AI Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-29T18:52:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bala Siva Sai Akhil Malepati</p>
    <p><b>Summary:</b> Modern AI inference faces an irreducible tension: no single computational resource simultaneously maximizes performance, preserves privacy, minimizes cost, and maintains trust. Existing orchestration frameworks optimize single dimensions (Kubernetes prioritizes latency, federated learning preserves privacy, edge computing reduces network distance), creating solutions that struggle under real-world heterogeneity. We present IslandRun, a multi-objective orchestration system that treats computational resources as autonomous "islands" spanning personal devices, private edge servers, and public cloud. Our key insights: (1) request-level heterogeneity demands policy-constrained multi-objective optimization, (2) data locality enables routing compute to data rather than data to compute, and (3) typed placeholder sanitization preserves context semantics across trust boundaries. IslandRun introduces agent-based routing, tiered island groups with differential trust, and reversible anonymization. This establishes a new paradigm for privacy-aware, decentralized inference orchestration across heterogeneous personal computing ecosystems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.00434v1">Privacy-Preserving Generative Modeling and Clinical Validation of Longitudinal Health Records for Chronic Disease</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2025-11-29T10:16:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Benjamin D. Ballyk, Ankit Gupta, Sujay Konda, Kavitha Subramanian, Chris Landon, Ahmed Ammar Naseer, Georg Maierhofer, Sumanth Swaminathan, Vasudevan Venkateshwaran</p>
    <p><b>Summary:</b> Data privacy is a critical challenge in modern medical workflows as the adoption of electronic patient records has grown rapidly. Stringent data protection regulations limit access to clinical records for training and integrating machine learning models that have shown promise in improving diagnostic accuracy and personalized care outcomes. Synthetic data offers a promising alternative; however, current generative models either struggle with time-series data or lack formal privacy guaranties. In this paper, we enhance a state-of-the-art time-series generative model to better handle longitudinal clinical data while incorporating quantifiable privacy safeguards. Using real data from chronic kidney disease and ICU patients, we evaluate our method through statistical tests, a Train-on-Synthetic-Test-on-Real (TSTR) setup, and expert clinical review. Our non-private model (Augmented TimeGAN) outperforms transformer- and flow-based models on statistical metrics in several datasets, while our private model (DP-TimeGAN) maintains a mean authenticity of 0.778 on the CKD dataset, outperforming existing state-of-the-art models on the privacy-utility frontier. Both models achieve performance comparable to real data in clinician evaluations, providing robust input data necessary for developing models for complex chronic conditions without compromising data privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.00307v2">Adversarial Signed Graph Learning with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-11-29T04:02:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haobin Ke, Sen Zhang, Qingqing Ye, Xun Ran, Haibo Hu</p>
    <p><b>Summary:</b> Signed graphs with positive and negative edges can model complex relationships in social networks. Leveraging on balance theory that deduces edge signs from multi-hop node pairs, signed graph learning can generate node embeddings that preserve both structural and sign information. However, training on sensitive signed graphs raises significant privacy concerns, as model parameters may leak private link information. Existing protection methods with differential privacy (DP) typically rely on edge or gradient perturbation for unsigned graph protection. Yet, they are not well-suited for signed graphs, mainly because edge perturbation tends to cascading errors in edge sign inference under balance theory, while gradient perturbation increases sensitivity due to node interdependence and gradient polarity change caused by sign flips, resulting in larger noise injection. In this paper, motivated by the robustness of adversarial learning to noisy interactions, we present ASGL, a privacy-preserving adversarial signed graph learning method that preserves high utility while achieving node-level DP. We first decompose signed graphs into positive and negative subgraphs based on edge signs, and then design a gradient-perturbed adversarial module to approximate the true signed connectivity distribution. In particular, the gradient perturbation helps mitigate cascading errors, while the subgraph separation facilitates sensitivity reduction. Further, we devise a constrained breadth-first search tree strategy that fuses with balance theory to identify the edge signs between generated node pairs. This strategy also enables gradient decoupling, thereby effectively lowering gradient sensitivity. Extensive experiments on real-world datasets show that ASGL achieves favorable privacy-utility trade-offs across multiple downstream tasks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.00272v1">Teleportation-Based Defenses for Privacy in Approximate Machine Unlearning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-29T01:50:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohammad M Maheri, Xavier Cadet, Peter Chin, Hamed Haddadi</p>
    <p><b>Summary:</b> Approximate machine unlearning aims to efficiently remove the influence of specific data points from a trained model, offering a practical alternative to full retraining. However, it introduces privacy risks: an adversary with access to pre- and post-unlearning models can exploit their differences for membership inference or data reconstruction. We show these vulnerabilities arise from two factors: large gradient norms of forget-set samples and the close proximity of unlearned parameters to the original model. To demonstrate their severity, we propose unlearning-specific membership inference and reconstruction attacks, showing that several state-of-the-art methods (e.g., NGP, SCRUB) remain vulnerable. To mitigate this leakage, we introduce WARP, a plug-and-play teleportation defense that leverages neural network symmetries to reduce forget-set gradient energy and increase parameter dispersion while preserving predictions. This reparameterization obfuscates the signal of forgotten data, making it harder for attackers to distinguish forgotten samples from non-members or recover them via reconstruction. Across six unlearning algorithms, our approach achieves consistent privacy gains, reducing adversarial advantage (AUC) by up to 64% in black-box and 92% in white-box settings, while maintaining accuracy on retained data. These results highlight teleportation as a general tool for reducing attack success in approximate unlearning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.23200v1">Quantifying the Privacy-Utility Trade-off in GPS-based Daily Stress Recognition using Semantic Features</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-11-28T14:04:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hoang Khang Phan, Nhat Tan Le</p>
    <p><b>Summary:</b> Psychological stress is a widespread issue that significantly impacts student well-being and academic performance. Effective remote stress recognition is crucial, yet existing methods often rely on wearable devices or GPS-based clustering techniques that pose privacy risks. In this study, we introduce a novel, end-to-end privacy-enhanced framework for semantic location encoding using a self-hosted OSM engine and an LLM-bootstrapped static map. We rigorously quantify the privacy-utility trade-off and demonstrate (via LOSO validation) that our Privacy-Aware (PA) model achieves performance statistically indistinguishable from a non-private model, proving that utility does not require sacrificing privacy. Feature importance analysis highlights that recreational activity time, working time, and travel time play a significant role in stress recognition.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.22791v1">An Efficient Privacy-preserving Intrusion Detection Scheme for UAV Swarm Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-11-27T22:37:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kanchon Gharami, Shafika Showkat Moni</p>
    <p><b>Summary:</b> The rapid proliferation of unmanned aerial vehicles (UAVs) and their applications in diverse domains, such as surveillance, disaster management, agriculture, and defense, have revolutionized modern technology. While the potential benefits of swarm-based UAV networks are growing significantly, they are vulnerable to various security attacks that can jeopardize the overall mission success by degrading their performance, disrupting decision-making, and compromising the trajectory planning process. The Intrusion Detection System (IDS) plays a vital role in identifying potential security attacks to ensure the secure operation of UAV swarm networks. However, conventional IDS primarily focuses on binary classification with resource-intensive neural networks and faces challenges, including latency, privacy breaches, increased performance overhead, and model drift. This research aims to address these challenges by developing a novel lightweight and federated continuous learning-based IDS scheme. Our proposed model facilitates decentralized training across diverse UAV swarms to ensure data heterogeneity and privacy. The performance evaluation of our model demonstrates significant improvements, with classification accuracies of 99.45% on UKM-IDS, 99.99% on UAV-IDS, 96.85% on TLM-UAV dataset, and 98.05% on Cyber-Physical datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.22788v1">PRISM: Privacy-Aware Routing for Adaptive Cloud-Edge LLM Inference via Semantic Sketch Collaboration</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-11-27T22:32:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Junfei Zhan, Haoxun Shen, Zheng Lin, Tengjiao He</p>
    <p><b>Summary:</b> Large Language Models (LLMs) demonstrate impressive capabilities in natural language understanding and generation, but incur high communication overhead and privacy risks in cloud deployments, while facing compute and memory constraints when confined to edge devices. Cloud-edge inference has emerged as a promising paradigm for improving privacy in LLM services by retaining sensitive computations on local devices. However, existing cloud-edge inference approaches apply uniform privacy protection without considering input sensitivity, resulting in unnecessary perturbation and degraded utility even for non-sensitive tokens. To address this limitation, we propose Privacy-aware Routing for Inference with Semantic Modulation (PRISM), a context-aware framework that dynamically balances privacy and inference quality. PRISM executes in four stages: (1) the edge device profiles entity-level sensitivity; (2) a soft gating module on the edge selects an execution mode - cloud, edge, or collaboration; (3) for collaborative paths, the edge applies adaptive two-layer local differential privacy based on entity risks; and (4) the cloud LLM generates a semantic sketch from the perturbed prompt, which is then refined by the edge-side small language model (SLM) using local context. Our results show that PRISM consistently achieves superior privacy-utility trade-offs across various scenarios, reducing energy consumption and latency to 40-50% of baseline methods such as Uniform and Selective LDP, while maintaining high output quality under strong privacy constraints. These findings are validated through comprehensive evaluations involving realistic prompts, actual energy measurements, and heterogeneous cloud-edge model deployments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.22554v1">Privacy-preserving fall detection at the edge using Sony IMX636 event-based vision sensor and Intel Loihi 2 neuromorphic processor</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Neural and Evolutionary Computing-5BC0EB">
  <p><b>Published on:</b> 2025-11-27T15:44:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lyes Khacef, Philipp Weidel, Susumu Hogyoku, Harry Liu, Claire Alexandra Bräuer, Shunsuke Koshino, Takeshi Oyakawa, Vincent Parret, Yoshitaka Miyatani, Mike Davies, Mathis Richter</p>
    <p><b>Summary:</b> Fall detection for elderly care using non-invasive vision-based systems remains an important yet unsolved problem. Driven by strict privacy requirements, inference must run at the edge of the vision sensor, demanding robust, real-time, and always-on perception under tight hardware constraints. To address these challenges, we propose a neuromorphic fall detection system that integrates the Sony IMX636 event-based vision sensor with the Intel Loihi 2 neuromorphic processor via a dedicated FPGA-based interface, leveraging the sparsity of event data together with near-memory asynchronous processing. Using a newly recorded dataset under diverse environmental conditions, we explore the design space of sparse neural networks deployable on a single Loihi 2 chip and analyze the tradeoffs between detection F1 score and computational cost. Notably, on the Pareto front, our LIF-based convolutional SNN with graded spikes achieves the highest computational efficiency, reaching a 55x synaptic operations sparsity for an F1 score of 58%. The LIF with graded spikes shows a gain of 6% in F1 score with 5x less operations compared to binary spikes. Furthermore, our MCUNet feature extractor with patched inference, combined with the S4D state space model, achieves the highest F1 score of 84% with a synaptic operations sparsity of 2x and a total power consumption of 90 mW on Loihi 2. Overall, our smart security camera proof-of-concept highlights the potential of integrating neuromorphic sensing and processing for edge AI applications where latency, energy consumption, and privacy are critical.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.22515v1">Privacy-Utility-Bias Trade-offs for Privacy-Preserving Recommender Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-11-27T14:50:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shiva Parsarad, Isabel Wagner</p>
    <p><b>Summary:</b> Recommender systems (RSs) output ranked lists of items, such as movies or restaurants, that users may find interesting, based on the user's past ratings and ratings from other users. RSs increasingly incorporate differential privacy (DP) to protect user data, raising questions about how privacy mechanisms affect both recommendation accuracy and fairness. We conduct a comprehensive, cross-model evaluation of two DP mechanisms, differentially private stochastic gradient descent (DPSGD) and local differential privacy (LDP), applied to four recommender systems (Neural Collaborative Filtering (NCF), Bayesian Personalized Ranking (BPR), Singular Value Decomposition (SVD), and Variational Autoencoder (VAE)) on the MovieLens-1M and Yelp datasets. We find that stronger privacy consistently reduces utility, but not uniformly. NCF under DPSGD shows the smallest accuracy loss (under 10 percent at epsilon approximately 1), whereas SVD and BPR experience larger drops, especially for users with niche preferences. VAE is the most sensitive to privacy, with sharp declines for sparsely represented groups. The impact on bias metrics is similarly heterogeneous. DPSGD generally reduces the gap between recommendations of popular and less popular items, whereas LDP preserves existing patterns more closely. These results highlight that no single DP mechanism is uniformly superior; instead, each provides trade-offs under different privacy regimes and data conditions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.22441v1">GEO-Detective: Unveiling Location Privacy Risks in Images with LLM Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-11-27T13:27:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xinyu Zhang, Yixin Wu, Boyang Zhang, Chenhao Lin, Chao Shen, Michael Backes, Yang Zhang</p>
    <p><b>Summary:</b> Images shared on social media often expose geographic cues. While early geolocation methods required expert effort and lacked generalization, the rise of Large Vision Language Models (LVLMs) now enables accurate geolocation even for ordinary users. However, existing approaches are not optimized for this task. To explore the full potential and associated privacy risks, we present Geo-Detective, an agent that mimics human reasoning and tool use for image geolocation inference. It follows a procedure with four steps that adaptively selects strategies based on image difficulty and is equipped with specialized tools such as visual reverse search, which emulates how humans gather external geographic clues. Experimental results show that GEO-Detective outperforms baseline large vision language models (LVLMs) overall, particularly on images lacking visible geographic features. In country level geolocation tasks, it achieves an improvement of over 11.1% compared to baseline LLMs, and even at finer grained levels, it still provides around a 5.2% performance gain. Meanwhile, when equipped with external clues, GEO-Detective becomes more likely to produce accurate predictions, reducing the "unknown" prediction rate by more than 50.6%. We further explore multiple defense strategies and find that Geo-Detective exhibits stronger robustness, highlighting the need for more effective privacy safeguards.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.22180v1">Personalized 3D Spatiotemporal Trajectory Privacy Protection with Differential and Distortion Geo-Perturbation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-27T07:41:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Minghui Min, Yulu Li, Gang Li, Meng Li, Hongliang Zhang, Miao Pan, Dusit Niyato, Zhu Han</p>
    <p><b>Summary:</b> The rapid advancement of location-based services (LBSs) in three-dimensional (3D) domains, such as smart cities and intelligent transportation, has raised concerns over 3D spatiotemporal trajectory privacy protection. However, existing research has not fully addressed the risk of attackers exploiting the spatiotemporal correlation of 3D spatiotemporal trajectories and the impact of height information, both of which can potentially lead to significant privacy leakage. To address these issues, this paper proposes a personalized 3D spatiotemporal trajectory privacy protection mechanism, named 3DSTPM. First, we analyze the characteristics of attackers that exploit spatiotemporal correlations between locations in a trajectory and present the attack model. Next, we exploit the complementary characteristics of 3D geo-indistinguishability (3D-GI) and distortion privacy to find a protection location set (PLS) that obscures the real location for all possible locations. To address the issue of privacy accumulation caused by continuous trajectory queries, we propose a Window-based Adaptive Privacy Budget Allocation (W-APBA), which dynamically allocates privacy budgets to all locations in the current PLS based on their predictability and sensitivity. Finally, we perturb the real location using the allocated privacy budget by the PF (Permute-and-Flip) mechanism, effectively balancing privacy protection and Quality of Service (QoS). Simulation results demonstrate that the proposed 3DSTPM effectively reduces QoS loss while meeting the user's personalized privacy protection needs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.22117v1">Privacy-preserving formal concept analysis: A homomorphic encryption-based concept construction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computational Complexity-5BC0EB">
  <p><b>Published on:</b> 2025-11-27T05:16:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qiangqiang Chen, Yunfeng Ke, Shen Li, Jinhai Li</p>
    <p><b>Summary:</b> Formal Concept Analysis (FCA) is extensively used in knowledge extraction, cognitive concept learning, and data mining. However, its computational demands on large-scale datasets often require outsourcing to external computing services, raising concerns about the leakage of sensitive information. To address this challenge, we propose a novel approach to enhance data security and privacy in FCA-based computations. Specifically, we introduce a Privacy-preserving Formal Context Analysis (PFCA) framework that combines binary data representation with homomorphic encryption techniques. This method enables secure and efficient concept construction without revealing private data. Experimental results and security analysis confirm the effectiveness of our approach in preserving privacy while maintaining computational performance. These findings have important implications for privacy-preserving data mining and secure knowledge discovery in large-scale FCA applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.22099v1">Decomposed Trust: Exploring Privacy, Adversarial Robustness, Fairness, and Ethics of Low-Rank LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-11-27T04:40:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Daniel Agyei Asante, Md Mokarram Chowdhury, Yang Li</p>
    <p><b>Summary:</b> Large language models (LLMs) have driven major advances across domains, yet their massive size hinders deployment in resource-constrained settings. Model compression addresses this challenge, with low-rank factorization emerging as a particularly effective method for reducing size, memory, and computation while maintaining accuracy. However, while these compressed models boast of benign performance and system-level advantages, their trustworthiness implications remain poorly understood. In this paper, we present the first comprehensive study of how low-rank factorization affects LLM trustworthiness across privacy, adversarial robustness, fairness, and ethical alignment. We evaluate multiple LLMs of different sizes and variants compressed with diverse low-rank algorithms, revealing key insights: (1) low-rank compression preserves or improves training data privacy but weakens PII protection during conversation; (2) adversarial robustness is generally preserved and often enhanced, even under deep compression; (3) ethical reasoning degrades in zero-shot settings but partially recovers with few-shot prompting; (4) fairness declines under compression. Beyond compression, we investigate how model scale and fine-tuning affect trustworthiness, as both are important in low-rank methods. To guide trustworthy compression strategies, we end our paper with a gradient-based attribution analysis to identify which layers in LLMs contribute most to adversarial robustness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.21876v1">Differential privacy from axioms</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-11-26T19:53:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guy Blanc, William Pires, Toniann Pitassi</p>
    <p><b>Summary:</b> Differential privacy (DP) is the de facto notion of privacy both in theory and in practice. However, despite its popularity, DP imposes strict requirements which guard against strong worst-case scenarios. For example, it guards against seemingly unrealistic scenarios where an attacker has full information about all but one point in the data set, and still nothing can be learned about the remaining point. While preventing such a strong attack is desirable, many works have explored whether average-case relaxations of DP are easier to satisfy [HWR13,WLF16,BF16,LWX23].
  In this work, we are motivated by the question of whether alternate, weaker notions of privacy are possible: can a weakened privacy notion still guarantee some basic level of privacy, and on the other hand, achieve privacy more efficiently and/or for a substantially broader set of tasks? Our main result shows the answer is no: even in the statistical setting, any reasonable measure of privacy satisfying nontrivial composition is equivalent to DP. To prove this, we identify a core set of four axioms or desiderata: pre-processing invariance, prohibition of blatant non-privacy, strong composition, and linear scalability. Our main theorem shows that any privacy measure satisfying our axioms is equivalent to DP, up to polynomial factors in sample complexity. We complement this result by showing our axioms are minimal: removing any one of our axioms enables ill-behaved measures of privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.21804v1">Beyond Membership: Limitations of Add/Remove Adjacency in Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-11-26T18:55:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gauri Pradhan, Joonas Jälkö, Santiago Zanella-Bèguelin, Antti Honkela</p>
    <p><b>Summary:</b> Training machine learning models with differential privacy (DP) limits an adversary's ability to infer sensitive information about the training data. It can be interpreted as a bound on adversary's capability to distinguish two adjacent datasets according to chosen adjacency relation. In practice, most DP implementations use the add/remove adjacency relation, where two datasets are adjacent if one can be obtained from the other by adding or removing a single record, thereby protecting membership. In many ML applications, however, the goal is to protect attributes of individual records (e.g., labels used in supervised fine-tuning). We show that privacy accounting under add/remove overstates attribute privacy compared to accounting under the substitute adjacency relation, which permits substituting one record. To demonstrate this gap, we develop novel attacks to audit DP under substitute adjacency, and show empirically that audit results are inconsistent with DP guarantees reported under add/remove, yet remain consistent with the budget accounted under the substitute adjacency relation. Our results highlight that the choice of adjacency when reporting DP guarantees is critical when the protection target is per-record attributes rather than membership.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.21196v1">Privacy-Constrained Signals</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2025-11-26T09:21:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhang Xu, Wei Zhao</p>
    <p><b>Summary:</b> This paper provides a unified approach to characterize the set of all feasible signals subject to privacy constraints. The Blackwell frontier of feasible signals can be decomposed into minimum informative signals achieving the Blackwell frontier of privacy variables, and conditionally privacy-preserving signals. A complete characterization of the minimum informative signals is then provided. We apply the framework to ex-post privacy (including differential and inferential privacy) and to constraints on posterior means of arbitrary statistics.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.21181v1">Privacy in Federated Learning with Spiking Neural Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-11-26T08:55:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dogukan Aksu, Jesus Martinez del Rincon, Ihsen Alouani</p>
    <p><b>Summary:</b> Spiking neural networks (SNNs) have emerged as prominent candidates for embedded and edge AI. Their inherent low power consumption makes them far more efficient than conventional ANNs in scenarios where energy budgets are tightly constrained. In parallel, federated learning (FL) has become the prevailing training paradigm in such settings, enabling on-device learning while limiting the exposure of raw data. However, gradient inversion attacks represent a critical privacy threat in FL, where sensitive training data can be reconstructed directly from shared gradients. While this vulnerability has been widely investigated in conventional ANNs, its implications for SNNs remain largely unexplored. In this work, we present the first comprehensive empirical study of gradient leakage in SNNs across diverse data domains. SNNs are inherently non-differentiable and are typically trained using surrogate gradients, which we hypothesized would be less correlated with the original input and thus less informative from a privacy perspective. To investigate this, we adapt different gradient leakage attacks to the spike domain. Our experiments reveal a striking contrast with conventional ANNs: whereas ANN gradients reliably expose salient input content, SNN gradients yield noisy, temporally inconsistent reconstructions that fail to recover meaningful spatial or temporal structure. These results indicate that the combination of event-driven dynamics and surrogate-gradient training substantially reduces gradient informativeness. To the best of our knowledge, this work provides the first systematic benchmark of gradient inversion attacks for spiking architectures, highlighting the inherent privacy-preserving potential of neuromorphic computation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.21020v1">Road Network-Aware Personalized Trajectory Protection with Differential Privacy under Spatiotemporal Correlations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-26T03:33:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Minghui Min, Jiahui Liu, Mingge Cao, Shiyin Li, Hongliang Zhang, Miao Pan, Zhu Han</p>
    <p><b>Summary:</b> Location-Based Services (LBSs) offer significant convenience to mobile users but pose significant privacy risks, as attackers can infer sensitive personal information through spatiotemporal correlations in user trajectories. Since users' sensitivity to location data varies based on factors such as stay duration, access frequency, and semantic sensitivity, implementing personalized privacy protection is imperative. This paper proposes a Personalized Trajectory Privacy Protection Mechanism (PTPPM) to address these challenges. Our approach begins by modeling an attacker's knowledge of a user's trajectory spatiotemporal correlations, which enables the attacker to identify possible location sets and disregard low-probability location sets. To combat this, we integrate geo-indistinguishability with distortion privacy, allowing users to customize their privacy preferences through a configurable privacy budget and expected inference error bound. This approach provides the theoretical framework for constructing a Protection Location Set (PLS) that obscures users' actual locations. Additionally, we introduce a Personalized Privacy Budget Allocation Algorithm (PPBA), which assesses the sensitivity of locations based on trajectory data and allocates privacy budgets accordingly. This algorithm considers factors such as location semantics and road network constraints. Furthermore, we propose a Permute-and-Flip mechanism that generates perturbed locations while minimizing perturbation distance, thus balancing privacy protection and Quality of Service (QoS). Simulation results demonstrate that our mechanism outperforms existing benchmarks, offering superior privacy protection while maintaining user QoS requirements.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.20983v1">Privacy-Preserving Federated Vision Transformer Learning Leveraging Lightweight Homomorphic Encryption in Medical AI</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-26T02:27:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Al Amin, Kamrul Hasan, Liang Hong, Sharif Ullah</p>
    <p><b>Summary:</b> Collaborative machine learning across healthcare institutions promises improved diagnostic accuracy by leveraging diverse datasets, yet privacy regulations such as HIPAA prohibit direct patient data sharing. While federated learning (FL) enables decentralized training without raw data exchange, recent studies show that model gradients in conventional FL remain vulnerable to reconstruction attacks, potentially exposing sensitive medical information. This paper presents a privacy-preserving federated learning framework combining Vision Transformers (ViT) with homomorphic encryption (HE) for secure multi-institutional histopathology classification. The approach leverages the ViT CLS token as a compact 768-dimensional feature representation for secure aggregation, encrypting these tokens using CKKS homomorphic encryption before transmission to the server. We demonstrate that encrypting CLS tokens achieves a 30-fold communication reduction compared to gradient encryption while maintaining strong privacy guarantees. Through evaluation on a three-client federated setup for lung cancer histopathology classification, we show that gradients are highly susceptible to model inversion attacks (PSNR: 52.26 dB, SSIM: 0.999, NMI: 0.741), enabling near-perfect image reconstruction. In contrast, the proposed CLS-protected HE approach prevents such attacks while enabling encrypted inference directly on ciphertexts, requiring only 326 KB of encrypted data transmission per aggregation round. The framework achieves 96.12 percent global classification accuracy in the unencrypted domain and 90.02 percent in the encrypted domain.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.20791v1">Beyond the Legal Lens: A Sociotechnical Taxonomy of Lived Privacy Incidents and Harms</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-11-25T19:31:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kirsten Chapman, Garrett Smith, Kaitlyn Klabacka, Harrison Winslow, Louise Barkhuus, Cori Faklaris, Sauvik Das, Pamela Wisniewski, Bart Piet Knijnenburg, Heather Lipford, Xinru Page</p>
    <p><b>Summary:</b> To understand how privacy incidents lead to harms, HCI researchers have historically leveraged legal frameworks. However, these frameworks expect acute, tangible harms and thus may not cover the full range of human experience relevant to modern-day digital privacy. To address this gap, our research builds upon these existing frameworks to develop a more comprehensive representation of people's lived experiences with privacy harms. We analyzed 369 privacy incidents reported by individuals from the general public. We found a broader range of privacy incidents and harms than accounted for in existing legal frameworks. The majority of reported privacy harms were not based on tangible harm, but on fear and loss of psychological safety. We also characterize the actors, motives, and information associated with various incidents. This work contributes a new framework for understanding digital privacy harms that can be utilized both in research and practice.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.20637v1">Behavioural Sciences and the Regulation of Privacy on the Internet</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-11-25T18:55:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Frederik Zuiderveen Borgesius</p>
    <p><b>Summary:</b> This chapter examines the policy implications of behavioural sciences insights for the regulation of privacy on the Internet, by focusing in particular on behavioural targeting. This marketing technique involves tracking people's online behaviour to use the collected information to show people individually targeted advertisements. Enforcing data protection law may not be enough to protect privacy in this area. I argue that, if society is better off when certain behavioural targeting practices do not happen, policymakers should consider banning them.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.20744v1">Scoping Electronic Communication Privacy Rules: Data, Services and Values</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-25T18:55:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joris van Hoboken, Frederik Zuiderveen Borgesius</p>
    <p><b>Summary:</b> We use electronic communication networks for more than simply traditional telecommunications: we access the news, buy goods online, file our taxes, contribute to public debate, and more. As a result, a wider array of privacy interests is implicated for users of electronic communications networks and services. This development calls into question the scope of electronic communications privacy rules. This paper analyses the scope of these rules, taking into account the rationale and the historic background of the European electronic communications privacy framework. We develop a framework for analysing the scope of electronic communications privacy rules using three approaches: (i) a service-centric approach, (ii) a data-centric approach, and (iii) a value-centric approach. We discuss the strengths and weaknesses of each approach. The current e-Privacy Directive contains a complex blend of the three approaches, which does not seem to be based on a thorough analysis of their strengths and weaknesses. The upcoming review of the directive announced by the European Commission provides an opportunity to improve the scoping of the rules.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.20497v1">Quantifying the Privacy Implications of High-Fidelity Synthetic Network Traffic</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-11-25T17:04:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Van Tran, Shinan Liu, Tian Li, Nick Feamster</p>
    <p><b>Summary:</b> To address the scarcity and privacy concerns of network traffic data, various generative models have been developed to produce synthetic traffic. However, synthetic traffic is not inherently privacy-preserving, and the extent to which it leaks sensitive information, and how to measure such leakage, remain largely unexplored. This challenge is further compounded by the diversity of model architectures, which shape how traffic is represented and synthesized. We introduce a comprehensive set of privacy metrics for synthetic network traffic, combining standard approaches like membership inference attacks (MIA) and data extraction attacks with network-specific identifiers and attributes. Using these metrics, we systematically evaluate the vulnerability of different representative generative models and examine the factors that influence attack success. Our results reveal substantial variability in privacy risks across models and datasets. MIA success ranges from 0% to 88%, and up to 100% of network identifiers can be recovered from generated traffic, highlighting serious privacy vulnerabilities. We further identify key factors that significantly affect attack outcomes, including training data diversity and how well the generative model fits the training data. These findings provide actionable guidance for designing and deploying generative models that minimize privacy leakage, establishing a foundation for safer synthetic network traffic generation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.20252v1">Hey there! You are using WhatsApp: Enumerating Three Billion Accounts for Security and Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-11-25T12:27:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gabriel K. Gegenhuber, Philipp É. Frenzel, Maximilian Günther, Johanna Ullrich, Aljosha Judmayer</p>
    <p><b>Summary:</b> WhatsApp, with 3.5 billion active accounts as of early 2025, is the world's largest instant messaging platform. Given its massive user base, WhatsApp plays a critical role in global communication.
  To initiate conversations, users must first discover whether their contacts are registered on the platform. This is achieved by querying WhatsApp's servers with mobile phone numbers extracted from the user's address book (if they allowed access). This architecture inherently enables phone number enumeration, as the service must allow legitimate users to query contact availability. While rate limiting is a standard defense against abuse, we revisit the problem and show that WhatsApp remains highly vulnerable to enumeration at scale. In our study, we were able to probe over a hundred million phone numbers per hour without encountering blocking or effective rate limiting.
  Our findings demonstrate not only the persistence but the severity of this vulnerability. We further show that nearly half of the phone numbers disclosed in the 2021 Facebook data leak are still active on WhatsApp, underlining the enduring risks associated with such exposures. Moreover, we were able to perform a census of WhatsApp users, providing a glimpse on the macroscopic insights a large messaging service is able to generate even though the messages themselves are end-to-end encrypted. Using the gathered data, we also discovered the re-use of certain X25519 keys across different devices and phone numbers, indicating either insecure (custom) implementations, or fraudulent activity.
  In this updated version of the paper, we also provide insights into the collaborative remediation process through which we confirmed that the underlying rate-limiting issue had been resolved.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.20125v1">N2E: A General Framework to Reduce Node-Differential Privacy to Edge-Differential Privacy for Graph Analytics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2025-11-25T09:46:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yihua Hu, Hao Ding, Wei Dong</p>
    <p><b>Summary:</b> Differential privacy (DP) has been widely adopted to protect sensitive information in graph analytics. While edge-DP, which protects privacy at the edge level, has been extensively studied, node-DP, offering stronger protection for entire nodes and their incident edges, remains largely underexplored due to its technical challenges. A natural way to bridge this gap is to develop a general framework for reducing node-DP graph analytical tasks to edge-DP ones, enabling the reuse of existing edge-DP mechanisms. A straightforward solution based on group privacy divides the privacy budget by a given degree upper bound, but this leads to poor utility when the bound is set conservatively large to accommodate worst-case inputs. To address this, we propose node-to-edge (N2E), a general framework that reduces any node-DP graph analytical task to an edge-DP one, with the error dependency on the graph's true maximum degree. N2E introduces two novel techniques: a distance-preserving clipping mechanism that bounds edge distance between neighboring graphs after clipping, and the first node-DP mechanism for maximum degree approximation, enabling tight, privacy-preserving clipping thresholds. By instantiating N2E with existing edge-DP mechanisms, we obtain the first node-DP solutions for tasks such as maximum degree estimation. For edge counting, our method theoretically matches the error of the state-of-the-art, which is provably optimal, and significantly outperforms existing approaches for degree distribution estimation. Experimental results demonstrate that our framework achieves up to a 2.5x reduction in error for edge counting and up to an 80x reduction for degree distribution estimation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.19958v2">GFT-GCN: Privacy-Preserving 3D Face Mesh Recognition with Spectral Diffusion</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-11-25T06:07:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hichem Felouat, Hanrui Wang, Isao Echizen</p>
    <p><b>Summary:</b> 3D face recognition offers a robust biometric solution by capturing facial geometry, providing resilience to variations in illumination, pose changes, and presentation attacks. Its strong spoof resistance makes it suitable for high-security applications, but protecting stored biometric templates remains critical. We present GFT-GCN, a privacy-preserving 3D face recognition framework that combines spectral graph learning with diffusion-based template protection. Our approach integrates the Graph Fourier Transform (GFT) and Graph Convolutional Networks (GCN) to extract compact, discriminative spectral features from 3D face meshes. To secure these features, we introduce a spectral diffusion mechanism that produces irreversible, renewable, and unlinkable templates. A lightweight client-server architecture ensures that raw biometric data never leaves the client device. Experiments on the BU-3DFE and FaceScape datasets demonstrate high recognition accuracy and strong resistance to reconstruction attacks. Results show that GFT-GCN effectively balances privacy and performance, offering a practical solution for secure 3D face authentication.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.20710v1">Are Neuro-Inspired Multi-Modal Vision-Language Models Resilient to Membership Inference Privacy Leakage?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-24T22:32:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> David Amebley, Sayanton Dibbo</p>
    <p><b>Summary:</b> In the age of agentic AI, the growing deployment of multi-modal models (MMs) has introduced new attack vectors that can leak sensitive training data in MMs, causing privacy leakage. This paper investigates a black-box privacy attack, i.e., membership inference attack (MIA) on multi-modal vision-language models (VLMs). State-of-the-art research analyzes privacy attacks primarily to unimodal AI-ML systems, while recent studies indicate MMs can also be vulnerable to privacy attacks. While researchers have demonstrated that biologically inspired neural network representations can improve unimodal model resilience against adversarial attacks, it remains unexplored whether neuro-inspired MMs are resilient against privacy attacks. In this work, we introduce a systematic neuroscience-inspired topological regularization (tau) framework to analyze MM VLMs resilience against image-text-based inference privacy attacks. We examine this phenomenon using three VLMs: BLIP, PaliGemma 2, and ViT-GPT2, across three benchmark datasets: COCO, CC3M, and NoCaps. Our experiments compare the resilience of baseline and neuro VLMs (with topological regularization), where the tau > 0 configuration defines the NEURO variant of VLM. Our results on the BLIP model using the COCO dataset illustrate that MIA attack success in NEURO VLMs drops by 24% mean ROC-AUC, while achieving similar model utility (similarities between generated and reference captions) in terms of MPNet and ROUGE-2 metrics. This shows neuro VLMs are comparatively more resilient against privacy attacks, while not significantly compromising model utility. Our extensive evaluation with PaliGemma 2 and ViT-GPT2 models, on two additional datasets: CC3M and NoCaps, further validates the consistency of the findings. This work contributes to the growing understanding of privacy risks in MMs and provides evidence on neuro VLMs privacy threat resilience.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.19750v1">DISCO: A Browser-Based Privacy-Preserving Framework for Distributed Collaborative Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-11-24T22:16:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Julien T. T. Vignoud, Valérian Rousset, Hugo El Guedj, Ignacio Aleman, Walid Bennaceur, Batuhan Faik Derinbay, Eduard Ďurech, Damien Gengler, Lucas Giordano, Felix Grimberg, Franziska Lippoldt, Christina Kopidaki, Jiafan Liu, Lauris Lopata, Nathan Maire, Paul Mansat, Martin Milenkoski, Emmanuel Omont, Güneş Özgün, Mina Petrović, Francesco Posa, Morgan Ridel, Giorgio Savini, Marcel Torne, Lucas Trognon, Alyssa Unell, Olena Zavertiaieva, Sai Praneeth Karimireddy, Tahseen Rabbani, Mary-Anne Hartley, Martin Jaggi</p>
    <p><b>Summary:</b> Data is often impractical to share for a range of well considered reasons, such as concerns over privacy, intellectual property, and legal constraints. This not only fragments the statistical power of predictive models, but creates an accessibility bias, where accuracy becomes inequitably distributed to those who have the resources to overcome these concerns. We present DISCO: an open-source DIStributed COllaborative learning platform accessible to non-technical users, offering a means to collaboratively build machine learning models without sharing any original data or requiring any programming knowledge. DISCO's web application trains models locally directly in the browser, making our tool cross-platform out-of-the-box, including smartphones. The modular design of \disco offers choices between federated and decentralized paradigms, various levels of privacy guarantees and several approaches to weight aggregation strategies that allow for model personalization and bias resilience in the collaborative training. Code repository is available at https://github.com/epfml/disco and a showcase web interface at https://discolab.ai</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.21758v1">A Longitudinal Measurement of Privacy Policy Evolution for Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-11-24T12:40:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhen Tao, Shidong Pan, Zhenchang Xing, Emily Black, Talia Gillis, Chunyang Chen</p>
    <p><b>Summary:</b> Large language model (LLM) services have been rapidly integrated into people's daily lives as chatbots and agentic systems. They are nourished by collecting rich streams of data, raising privacy concerns around excessive collection of sensitive personal information. Privacy policies are the fundamental mechanism for informing users about data practices in modern information privacy paradigm. Although traditional web and mobile policies are well studied, the privacy policies of LLM providers, their LLM-specific content, and their evolution over time remain largely underexplored. In this paper, we present the first longitudinal empirical study of privacy policies for mainstream LLM providers worldwide. We curate a chronological dataset of 74 historical privacy policies and 115 supplemental privacy documents from 11 LLM providers across 5 countries up to August 2025, and extract over 3,000 sentence-level edits between consecutive policy versions. We compare LLM privacy policies to those of other software formats, propose a taxonomy tailored to LLM privacy policies, annotate policy edits and align them with a timeline of key LLM ecosystem events. Results show they are substantially longer, demand college-level reading ability, and remain highly vague. Our taxonomy analysis reveals patterns in how providers disclose LLM-specific practices and highlights regional disparities in coverage. Policy edits are concentrated in first-party data collection and international/specific-audience sections, and that product releases and regulatory actions are the primary drivers, shedding light on the status quo and the evolution of LLM privacy policies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.19015v1">A General Framework for Per-record Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-24T11:44:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xinghe Chen, Dajun Sun, Quanqing Xu, Wei Dong</p>
    <p><b>Summary:</b> Differential Privacy (DP) is a widely adopted standard for privacy-preserving data analysis, but it assumes a uniform privacy budget across all records, limiting its applicability when privacy requirements vary with data values. Per-record Differential Privacy (PrDP) addresses this by defining the privacy budget as a function of each record, offering better alignment with real-world needs. However, the dependency between the privacy budget and the data value introduces challenges in protecting the budget's privacy itself. Existing solutions either handle specific privacy functions or adopt relaxed PrDP definitions. A simple workaround is to use the global minimum of the privacy function, but this severely degrades utility, as the minimum is often set extremely low to account for rare records with high privacy needs. In this work, we propose a general and practical framework that enables any standard DP mechanism to support PrDP, with error depending only on the minimal privacy requirement among records actually present in the dataset. Since directly revealing this minimum may leak information, we introduce a core technique called privacy-specified domain partitioning, which ensures accurate estimation without compromising privacy. We also extend our framework to the local DP setting via a novel technique, privacy-specified query augmentation. Using our framework, we present the first PrDP solutions for fundamental tasks such as count, sum, and maximum estimation. Experimental results show that our mechanisms achieve high utility and significantly outperform existing Personalized DP (PDP) methods, which can be viewed as a special case of PrDP with relaxed privacy protection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.18965v1">REFLECTing SPERET: Measuring and Promoting Ethics and Privacy Reflexivity in Eye-Tracking Research</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-11-24T10:31:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Susanne Hindennach, Mayar Elfares, Céline Gressel, Andreas Bulling</p>
    <p><b>Summary:</b> The proliferation of eye tracking in high-stakes domains - such as healthcare, marketing and surveillance - underscores the need for researchers to be ethically aware when employing this technology. Although privacy and ethical guidelines have emerged in recent years, empirical research on how scholars reflect on their own work remains scarce. To address this gap, we present two complementary instruments developed with input from more than 70 researchers: REFLECT, a qualitative questionnaire, and SPERET (Latin for "hope"), a quantitative psychometric scale that measures privacy and ethics reflexivity in eye tracking. Our findings reveal a research community that is concerned about user privacy, cognisant of methodological constraints, such as sample bias, and that possesses a nuanced sense of ethical responsibility evolving with project maturity. Together, these tools and our analyses offer a systematic examination and a hopeful outlook on reflexivity in eye-tracking research, promoting more privacy and ethics-conscious practice.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.18876v1">Fairness Meets Privacy: Integrating Differential Privacy and Demographic Parity in Multi-class Classification</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-11-24T08:31:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lilian Say, Christophe Denis, Rafael Pinot</p>
    <p><b>Summary:</b> The increasing use of machine learning in sensitive applications demands algorithms that simultaneously preserve data privacy and ensure fairness across potentially sensitive sub-populations. While privacy and fairness have each been extensively studied, their joint treatment remains poorly understood. Existing research often frames them as conflicting objectives, with multiple studies suggesting that strong privacy notions such as differential privacy inevitably compromise fairness. In this work, we challenge that perspective by showing that differential privacy can be integrated into a fairness-enhancing pipeline with minimal impact on fairness guarantees. We design a postprocessing algorithm, called DP2DP, that enforces both demographic parity and differential privacy. Our analysis reveals that our algorithm converges towards its demographic parity objective at essentially the same rate (up logarithmic factor) as the best non-private methods from the literature. Experiments on both synthetic and real datasets confirm our theoretical results, showing that the proposed algorithm achieves state-of-the-art accuracy/fairness/privacy trade-offs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.18583v2">Differential privacy with dependent data</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">
  <p><b>Published on:</b> 2025-11-23T18:56:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Valentin Roth, Marco Avella-Medina</p>
    <p><b>Summary:</b> Dependent data underlies many statistical studies in the social and health sciences, which often involve sensitive or private information. Differential privacy (DP) and in particular \textit{user-level} DP provide a natural formalization of privacy requirements for processing dependent data where each individual provides multiple observations to the dataset. However, dependence introduced, e.g., through repeated measurements challenges the existing statistical theory under DP-constraints. In \iid{} settings, noisy Winsorized mean estimators have been shown to be minimax optimal for standard (\textit{item-level}) and \textit{user-level} DP estimation of a mean $μ\in \R^d$. Yet, their behavior on potentially dependent observations has not previously been studied. We fill this gap and show that Winsorized mean estimators can also be used under dependence for bounded and unbounded data, and can lead to asymptotic and finite sample guarantees that resemble their \iid{} counterparts under a weak notion of dependence. For this, we formalize dependence via log-Sobolev inequalities on the joint distribution of observations. This enables us to adapt the stable histogram by Karwa and Vadhan (2018) to a non-\iid{} setting, which we then use to estimate the private projection intervals of the Winsorized estimator. The resulting guarantees for our item-level mean estimator extend to \textit{user-level} mean estimation and transfer to the local model via a randomized response histogram. Using the mean estimators as building blocks, we provide extensions to random effects models, longitudinal linear regression and nonparametric regression. Therefore, our work constitutes a first step towards a systematic study of DP for dependent data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.19498v1">Hierarchical Dual-Strategy Unlearning for Biomedical and Healthcare Intelligence Using Imperfect and Privacy-Sensitive Medical Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-23T15:28:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yi Zhang, Tianxiang Xu, Zijian Li, Chao Zhang, Kunyu Zhang, Zhan Gao, Meinuo Li, Xiaohan Zhang, Qichao Qi, Bing Chen</p>
    <p><b>Summary:</b> Large language models (LLMs) exhibit exceptional performance but pose substantial privacy risks due to training data memorization, particularly within healthcare contexts involving imperfect or privacy-sensitive patient information. We present a hierarchical dual-strategy framework for selective knowledge unlearning that precisely removes specialized knowledge while preserving fundamental medical competencies. Our approach synergistically integrates geometric-constrained gradient updates to selectively modulate target parameters with concept-aware token-level interventions that distinguish between preservation-critical and unlearning-targeted tokens via a unified four-level medical concept hierarchy. Comprehensive evaluations on the MedMCQA (surgical) and MHQA (anxiety, depression, trauma) datasets demonstrate superior performance, achieving an 82.7% forgetting rate and 88.5% knowledge preservation. Notably, our framework maintains robust privacy guarantees while requiring modification of only 0.1% of parameters, addressing critical needs for regulatory compliance, auditability, and ethical standards in clinical research.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.18268v1">Privacy Concerns and ChatGPT: Exploring Online Discourse through the Lens of Information Practice on Reddit</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B">
  <p><b>Published on:</b> 2025-11-23T03:37:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> S M Mehedi Zaman, Saubhagya Joshi, Yiyi Wu</p>
    <p><b>Summary:</b> As millions of people use ChatGPT for tasks such as education, writing assistance, and health advice, concerns have grown about how personal prompts and data are stored and used. This study explores how Reddit users collectively negotiate and respond to these privacy concerns. Posts were collected from three major subreddits -- r/Chatgpt, r/privacy, and r/OpenAI -- between November 2022 and May 2025. An iterative keyword search followed by manual screening resulted in a final dataset of 426 posts and 1,900 comments. Using information practice as the theoretical lens, we conducted a qualitative thematic analysis to identify collective practices of risk negotiation, validated with BERTopic topic modeling to ensure thematic saturation. Findings revealed risk signaling, norm-setting, and resignation as dominant discourses, and collective troubleshooting and advocacy for privacy-preserving alternatives as key adaptive practices. Reddit functions as a site of collective sense-making where users surface risks, establish informal norms, and share strategies for mitigating privacy threats, offering insights for AI design and privacy literacy initiatives.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.18025v1">Correlated-Sequence Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-11-22T11:28:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yifan Luo, Meng Zhang, Jin Xu, Junting Chen, Jianwei Huang</p>
    <p><b>Summary:</b> Data streams collected from multiple sources are rarely independent. Values evolve over time and influence one another across sequences. These correlations improve prediction in healthcare, finance, and smart-city control yet violate the record-independence assumption built into most Differential Privacy (DP) mechanisms. To restore rigorous privacy guarantees without sacrificing utility, we introduce Correlated-Sequence Differential Privacy (CSDP), a framework specifically designed for preserving privacy in correlated sequential data. CSDP addresses two linked challenges: quantifying the extra information an attacker gains from joint temporal and cross-sequence links, and adding just enough noise to hide that information while keeping the data useful. We model multivariate streams as a Coupling Markov Chain, yielding the derived loose leakage bound expressed with a few spectral terms and revealing a counterintuitive result: stronger coupling can actually decrease worst-case leakage by dispersing perturbations across sequences. Guided by these bounds, we build the Freshness-Regulated Adaptive Noise (FRAN) mechanism--combining data aging, correlation-aware sensitivity scaling, and Laplace noise--that runs in linear time. Tests on two-sequence datasets show that CSDP improves the privacy-utility trade-off by approximately 50% over existing correlated-DP methods and by two orders of magnitude compared to the standard DP approach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.17989v1">Privacy Auditing of Multi-domain Graph Pre-trained Model under Membership Inference Attacks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-22T09:04:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiayi Luo, Qingyun Sun, Yuecen Wei, Haonan Yuan, Xingcheng Fu, Jianxin Li</p>
    <p><b>Summary:</b> Multi-domain graph pre-training has emerged as a pivotal technique in developing graph foundation models. While it greatly improves the generalization of graph neural networks, its privacy risks under membership inference attacks (MIAs), which aim to identify whether a specific instance was used in training (member), remain largely unexplored. However, effectively conducting MIAs against multi-domain graph pre-trained models is a significant challenge due to: (i) Enhanced Generalization Capability: Multi-domain pre-training reduces the overfitting characteristics commonly exploited by MIAs. (ii) Unrepresentative Shadow Datasets: Diverse training graphs hinder the obtaining of reliable shadow graphs. (iii) Weakened Membership Signals: Embedding-based outputs offer less informative cues than logits for MIAs. To tackle these challenges, we propose MGP-MIA, a novel framework for Membership Inference Attacks against Multi-domain Graph Pre-trained models. Specifically, we first propose a membership signal amplification mechanism that amplifies the overfitting characteristics of target models via machine unlearning. We then design an incremental shadow model construction mechanism that builds a reliable shadow model with limited shadow graphs via incremental learning. Finally, we introduce a similarity-based inference mechanism that identifies members based on their similarity to positive and negative samples. Extensive experiments demonstrate the effectiveness of our proposed MGP-MIA and reveal the privacy risks of multi-domain graph pre-training.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.17747v1">AEGIS: Preserving privacy of 3D Facial Avatars with Adversarial Perturbations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-11-21T19:57:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dawid Wolkiewicz, Anastasiya Pechko, Przemysław Spurek, Piotr Syga</p>
    <p><b>Summary:</b> The growing adoption of photorealistic 3D facial avatars, particularly those utilizing efficient 3D Gaussian Splatting representations, introduces new risks of online identity theft, especially in systems that rely on biometric authentication. While effective adversarial masking methods have been developed for 2D images, a significant gap remains in achieving robust, viewpoint-consistent identity protection for dynamic 3D avatars. To address this, we present AEGIS, the first privacy-preserving identity masking framework for 3D Gaussian Avatars that maintains the subject's perceived characteristics. Our method aims to conceal identity-related facial features while preserving the avatar's perceptual realism and functional integrity. AEGIS applies adversarial perturbations to the Gaussian color coefficients, guided by a pre-trained face verification network, ensuring consistent protection across multiple viewpoints without retraining or modifying the avatar's geometry. AEGIS achieves complete de-identification, reducing face retrieval and verification accuracy to 0%, while maintaining high perceptual quality (SSIM = 0.9555, PSNR = 35.52 dB). It also preserves key facial attributes such as age, race, gender, and emotion, demonstrating strong privacy protection with minimal visual distortion.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.16940v1">MultiPriv: Benchmarking Individual-Level Privacy Reasoning in Vision-Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-21T04:33:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiongtao Sun, Hui Li, Jiaming Zhang, Yujie Yang, Kaili Liu, Ruxin Feng, Wen Jun Tan, Wei Yang Bryan Lim</p>
    <p><b>Summary:</b> Modern Vision-Language Models (VLMs) demonstrate sophisticated reasoning, escalating privacy risks beyond simple attribute perception to individual-level linkage. Current privacy benchmarks are structurally insufficient for this new threat, as they primarily evaluate privacy perception while failing to address the more critical risk of privacy reasoning: a VLM's ability to infer and link distributed information to construct individual profiles. To address this critical gap, we propose \textbf{MultiPriv}, the first benchmark designed to systematically evaluate individual-level privacy reasoning in VLMs. We introduce the \textbf{Privacy Perception and Reasoning (PPR)} framework and construct a novel, bilingual multimodal dataset to support it. The dataset uniquely features a core component of synthetic individual profiles where identifiers (e.g., faces, names) are meticulously linked to sensitive attributes. This design enables nine challenging tasks evaluating the full PPR spectrum, from attribute detection to cross-image re-identification and chained inference. We conduct a large-scale evaluation of over 50 foundational and commercial VLMs. Our analysis reveals: (1) Many VLMs possess significant, unmeasured reasoning-based privacy risks. (2) Perception-level metrics are poor predictors of these reasoning risks, revealing a critical evaluation gap. (3) Existing safety alignments are inconsistent and ineffective against such reasoning-based attacks. MultiPriv exposes systemic vulnerabilities and provides the necessary framework for developing robust, privacy-preserving VLMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.16377v1">Optimal Fairness under Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2025-11-20T14:00:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hrad Ghoukasian, Shahab Asoodeh</p>
    <p><b>Summary:</b> We investigate how to optimally design local differential privacy (LDP) mechanisms that reduce data unfairness and thereby improve fairness in downstream classification. We first derive a closed-form optimal mechanism for binary sensitive attributes and then develop a tractable optimization framework that yields the corresponding optimal mechanism for multi-valued attributes. As a theoretical contribution, we establish that for discrimination-accuracy optimal classifiers, reducing data unfairness necessarily leads to lower classification unfairness, thus providing a direct link between privacy-aware pre-processing and classification fairness. Empirically, we demonstrate that our approach consistently outperforms existing LDP mechanisms in reducing data unfairness across diverse datasets and fairness metrics, while maintaining accuracy close to that of non-private models. Moreover, compared with leading pre-processing and post-processing fairness methods, our mechanism achieves a more favorable accuracy-fairness trade-off while simultaneously preserving the privacy of sensitive attributes. Taken together, these results highlight LDP as a principled and effective pre-processing fairness intervention technique.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.15634v1">Rényi Differential Privacy for Heavy-Tailed SDEs via Fractional Poincaré Inequalities</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-11-19T17:18:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Benjamin Dupuis, Mert Gürbüzbalaban, Umut Şimşekli, Jian Wang, Sinan Yildirim, Lingjiong Zhu</p>
    <p><b>Summary:</b> Characterizing the differential privacy (DP) of learning algorithms has become a major challenge in recent years. In parallel, many studies suggested investigating the behavior of stochastic gradient descent (SGD) with heavy-tailed noise, both as a model for modern deep learning models and to improve their performance. However, most DP bounds focus on light-tailed noise, where satisfactory guarantees have been obtained but the proposed techniques do not directly extend to the heavy-tailed setting. Recently, the first DP guarantees for heavy-tailed SGD were obtained. These results provide $(0,δ)$-DP guarantees without requiring gradient clipping. Despite casting new light on the link between DP and heavy-tailed algorithms, these results have a strong dependence on the number of parameters and cannot be extended to other DP notions like the well-established Rényi differential privacy (RDP). In this work, we propose to address these limitations by deriving the first RDP guarantees for heavy-tailed SDEs, as well as their discretized counterparts. Our framework is based on new Rényi flow computations and the use of well-established fractional Poincaré inequalities. Under the assumption that such inequalities are satisfied, we obtain DP guarantees that have a much weaker dependence on the dimension compared to prior art.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.15434v1">Small Language Models for Phishing Website Detection: Cost, Performance, and Privacy Trade-Offs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-11-19T13:45:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Georg Goldenits, Philip Koenig, Sebastian Raubitzek, Andreas Ekelhart</p>
    <p><b>Summary:</b> Phishing websites pose a major cybersecurity threat, exploiting unsuspecting users and causing significant financial and organisational harm. Traditional machine learning approaches for phishing detection often require extensive feature engineering, continuous retraining, and costly infrastructure maintenance. At the same time, proprietary large language models (LLMs) have demonstrated strong performance in phishing-related classification tasks, but their operational costs and reliance on external providers limit their practical adoption in many business environments. This paper investigates the feasibility of small language models (SLMs) for detecting phishing websites using only their raw HTML code. A key advantage of these models is that they can be deployed on local infrastructure, providing organisations with greater control over data and operations. We systematically evaluate 15 commonly used Small Language Models (SLMs), ranging from 1 billion to 70 billion parameters, benchmarking their classification accuracy, computational requirements, and cost-efficiency. Our results highlight the trade-offs between detection performance and resource consumption, demonstrating that while SLMs underperform compared to state-of-the-art proprietary LLMs, they can still provide a viable and scalable alternative to external LLM services. By presenting a comparative analysis of costs and benefits, this work lays the foundation for future research on the adaptation, fine-tuning, and deployment of SLMs in phishing detection systems, aiming to balance security effectiveness and economic practicality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.15278v1">Privacy-Preserving IoT in Connected Aircraft Cabin</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2025-11-19T09:41:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nilesh Vyas, Benjamin Zhao, Aygün Baltaci, Gustavo de Carvalho Bertoli, Hassan Asghar, Markus Klügel, Gerrit Schramm, Martin Kubisch, Dali Kaafar</p>
    <p><b>Summary:</b> The proliferation of IoT devices in shared, multi-vendor environments like the modern aircraft cabin creates a fundamental conflict between the promise of data collaboration and the risks to passenger privacy, vendor intellectual property (IP), and regulatory compliance. While emerging standards like the Cabin Secure Media-Independent Messaging (CSMIM) protocol provide a secure communication backbone, they do not resolve data governance challenges at the application layer, leaving a privacy gap that impedes trust. This paper proposes and evaluates a framework that closes this gap by integrating a configurable layer of Privacy-Enhancing Technologies (PETs) atop a CSMIM-like architecture. We conduct a rigorous, empirical analysis of two pragmatic PETs: Differential Privacy (DP) for statistical sharing, and an additive secret sharing scheme (ASS) for data obfuscation. Using a high-fidelity testbed with resource-constrained hardware, we quantify the trade-offs between data privacy, utility, and computing performance. Our results demonstrate that the computational overhead of PETs is often negligible compared to inherent network and protocol latencies. We prove that architectural choices, such as on-device versus virtualized processing, have a far greater impact on end-to-end latency and computational performance than the PETs themselves. The findings provide a practical roadmap for system architects to select and configure appropriate PETs, enabling the design of trustworthy collaborative IoT ecosystems in avionics and other critical domains.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.14936v1">How to Train Private Clinical Language Models: A Comparative Study of Privacy-Preserving Pipelines for ICD-9 Coding</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-11-18T21:51:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mathieu Dufour, Andrew Duncan</p>
    <p><b>Summary:</b> Large language models trained on clinical text risk exposing sensitive patient information, yet differential privacy (DP) methods often severely degrade the diagnostic accuracy needed for deployment. Despite rapid progress in DP optimisation and text generation, it remains unclear which privacy-preserving strategy actually works best for clinical language tasks. We present the first systematic head-to-head comparison of four training pipelines for automated diagnostic coding from hospital discharge summaries. All pipelines use identical 1B-parameter models and matched privacy budgets to predict ICD-9 codes. At moderate and relaxed privacy budgets ($\varepsilon \in \{4, 6\}$), knowledge distillation from DP-trained teachers outperforms both direct DP-SGD and DP-synthetic data training, recovering up to 63\% of the non-private performance whilst maintaining strong empirical privacy (membership-inference AUC $\approx$ 0.5). These findings expose large differences in the privacy-utility trade-off across architectures and identify knowledge distillation as the most practical route to privacy-preserving clinical NLP.</p>
  </details>
</div>



<h2>2025-12</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.11482v1">Towards Privacy-Preserving Code Generation: Differentially Private Code Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-12-12T11:31:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Melih Catal, Pooja Rani, Harald C. Gall</p>
    <p><b>Summary:</b> Large language models specialized for code (CodeLLMs) have demonstrated remarkable capabilities in generating code snippets, documentation, and test cases. However, despite their promising capabilities, CodeLLMs can inadvertently memorize and reproduce snippets from their training data, which poses risks of privacy breaches and intellectual property violations. These risks restrict the deployment of CodeLLMs in sensitive domains and limit their training datasets to publicly available sources. To mitigate the memorization risk without compromising their task performance, we apply Differential Privacy (DP) to CodeLLMs. To the best of our knowledge, this is the first comprehensive study that systematically evaluates the effectiveness of DP in CodeLLMs. DP adds calibrated noise to the training process to protect individual data points while still allowing the model to learn useful patterns. To this end, we first identify and understand the driving reasons of the memorization behaviour of the CodeLLMs during their fine-tuning. Then, to address this issue, we empirically evaluate the effect of DP on mitigating memorization while preserving code generation capabilities. Our findings show that DP substantially reduces memorization in CodeLLMs across all the tested snippet types. The snippet types most prone to memorization are also the most effectively mitigated by DP. Furthermore, we observe that DP slightly increases perplexity but preserves, and can even enhance, the code generation capabilities of CodeLLMs, which makes it feasible to apply DP in practice without significantly compromising model utility. Finally, we analyze the impact of DP on training efficiency and energy consumption, finding that DP does not significantly affect training time or energy usage, making it a practical choice for privacy-preserving CodeLLMs training.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.10618v1">Analyzing developer discussions on EU and US privacy legislation compliance in GitHub repositories</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-12-11T13:16:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Georgia M. Kapitsaki, Maria Papoutsoglou, Christoph Treude, Ioanna Theophilou</p>
    <p><b>Summary:</b> Context: Privacy legislation has impacted the way software systems are developed, prompting practitioners to update their implementations. Specifically, the EU General Data Protection Regulation (GDPR) and the California Consumer Privacy Act (CCPA) have forced the community to focus on users' data privacy. Despite the vast amount of data on developer issues available in GitHub repositories, there is a lack of empirical evidence on the issues developers of Open Source Software discuss to comply with privacy legislation. Method: In this work, we examine such discussions by mining and analyzing 32,820 issues from GitHub repositories. We partially analyzed the dataset automatically to identify law user rights and principles indicated, and manually analyzed a sample of 1,186 issues based on the type of concern addressed. Results: We devised 24 discussion categories placed in six clusters: features/bugs, consent-related, documentation, data storing/sharing, adaptability, and general compliance. Our results show that developers mainly focus on specific user rights from the legislation (right to erasure, right to opt-out, right to access), addressing other rights less frequently, while most discussions concern user consent, user rights functionality, bugs and cookies management. Conclusion: The created taxonomy can help practitioners understand which issues are discussed for law compliance, so that they ensure they address them first in their systems. In addition, the educational community can reshape curricula to better educate future engineers on the privacy law concerns raised, and the research community can identify gaps and areas for improvement to support and accelerate data privacy law compliance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.10426v1">Differential Privacy for Secure Machine Learning in Healthcare IoT-Cloud Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-12-11T08:37:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> N Mangala, Murtaza Rangwala, S Aishwarya, B Eswara Reddy, Rajkumar Buyya, KR Venugopal, SS Iyengar, LM Patnaik</p>
    <p><b>Summary:</b> Healthcare has become exceptionally sophisticated, as wearables and connected medical devices are revolutionising remote patient monitoring, emergency response, medication management, diagnosis, and predictive and prescriptive analytics. Internet of Things and Cloud computing integrated systems (IoT-Cloud) facilitate sensing, automation, and processing for these healthcare applications. While real-time response is crucial for alleviating patient emergencies, protecting patient privacy is extremely important in data-driven healthcare. In this paper, we propose a multi-layer IoT, Edge and Cloud architecture to enhance the speed of response for emergency healthcare by distributing tasks based on response criticality and permanence of storage. Privacy of patient data is assured by proposing a Differential Privacy framework across several machine learning models such as K-means, Logistic Regression, Random Forest and Naive Bayes. We establish a comprehensive threat model identifying three adversary classes and evaluate Laplace, Gaussian, and hybrid noise mechanisms across varying privacy budgets, with supervised algorithms achieving up to 86% accuracy. The proposed hybrid Laplace-Gaussian noise mechanism with adaptive budget allocation provides a balanced approach, offering moderate tails and better privacy-utility trade-offs for both low and high dimension datasets. At the practical threshold of $\varepsilon = 5.0$, supervised algorithms achieve 82-84% accuracy while reducing attribute inference attacks by up to 18% and data reconstruction correlation by 70%. Blockchain security further ensures trusted communication through time-stamping, traceability, and immutability for analytics applications. Edge computing demonstrates 8$\times$ latency reduction for emergency scenarios, validating the hierarchical architecture for time-critical operations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.10372v1">D2M: A Decentralized, Privacy-Preserving, Incentive-Compatible Data Marketplace for Collaborative Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-12-11T07:38:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yash Srivastava, Shalin Jain, Sneha Awathare, Nitin Awathare</p>
    <p><b>Summary:</b> The rising demand for collaborative machine learning and data analytics calls for secure and decentralized data sharing frameworks that balance privacy, trust, and incentives. Existing approaches, including federated learning (FL) and blockchain-based data markets, fall short: FL often depends on trusted aggregators and lacks Byzantine robustness, while blockchain frameworks struggle with computation-intensive training and incentive integration.
  We present \prot, a decentralized data marketplace that unifies federated learning, blockchain arbitration, and economic incentives into a single framework for privacy-preserving data sharing. \prot\ enables data buyers to submit bid-based requests via blockchain smart contracts, which manage auctions, escrow, and dispute resolution. Computationally intensive training is delegated to \cone\ (\uline{Co}mpute \uline{N}etwork for \uline{E}xecution), an off-chain distributed execution layer. To safeguard against adversarial behavior, \prot\ integrates a modified YODA protocol with exponentially growing execution sets for resilient consensus, and introduces Corrected OSMD to mitigate malicious or low-quality contributions from sellers. All protocols are incentive-compatible, and our game-theoretic analysis establishes honesty as the dominant strategy.
  We implement \prot\ on Ethereum and evaluate it over benchmark datasets -- MNIST, Fashion-MNIST, and CIFAR-10 -- under varying adversarial settings. \prot\ achieves up to 99\% accuracy on MNIST and 90\% on Fashion-MNIST, with less than 3\% degradation up to 30\% Byzantine nodes, and 56\% accuracy on CIFAR-10 despite its complexity. Our results show that \prot\ ensures privacy, maintains robustness under adversarial conditions, and scales efficiently with the number of participants, making it a practical foundation for real-world decentralized data sharing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.10341v1">A Privacy-Preserving Cloud Architecture for Distributed Machine Learning at Scale</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-12-11T06:46:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vinoth Punniyamoorthy, Ashok Gadi Parthi, Mayilsamy Palanigounder, Ravi Kiran Kodali, Bikesh Kumar, Kabilan Kannan</p>
    <p><b>Summary:</b> Distributed machine learning systems require strong privacy guarantees, verifiable compliance, and scalable deployment across heterogeneous and multi-cloud environments. This work introduces a cloud-native privacy-preserving architecture that integrates federated learning, differential privacy, zero-knowledge compliance proofs, and adaptive governance powered by reinforcement learning. The framework supports secure model training and inference without centralizing sensitive data, while enabling cryptographically verifiable policy enforcement across institutions and cloud platforms. A full prototype deployed across hybrid Kubernetes clusters demonstrates reduced membership-inference risk, consistent enforcement of formal privacy budgets, and stable model performance under differential privacy. Experimental evaluation across multi-institution workloads shows that the architecture maintains utility with minimal overhead while providing continuous, risk-aware governance. The proposed framework establishes a practical foundation for deploying trustworthy and compliant distributed machine learning systems at scale.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.10102v1">Hierarchical Instance Tracking to Balance Privacy Preservation with Accessible Information</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-12-10T21:48:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Neelima Prasad, Jarek Reynolds, Neel Karsanbhai, Tanusree Sharma, Lotus Zhang, Abigale Stangl, Yang Wang, Leah Findlater, Danna Gurari</p>
    <p><b>Summary:</b> We propose a novel task, hierarchical instance tracking, which entails tracking all instances of predefined categories of objects and parts, while maintaining their hierarchical relationships. We introduce the first benchmark dataset supporting this task, consisting of 2,765 unique entities that are tracked in 552 videos and belong to 40 categories (across objects and parts). Evaluation of seven variants of four models tailored to our novel task reveals the new dataset is challenging. Our dataset is available at https://vizwiz.org/tasks-and-datasets/hierarchical-instance-tracking/</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.09463v1">Privacy-Preserving Computer Vision for Industry: Three Case Studies in Human-Centric Manufacturing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-12-10T09:33:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sander De Coninck, Emilio Gamba, Bart Van Doninck, Abdellatif Bey-Temsamani, Sam Leroux, Pieter Simoens</p>
    <p><b>Summary:</b> The adoption of AI-powered computer vision in industry is often constrained by the need to balance operational utility with worker privacy. Building on our previously proposed privacy-preserving framework, this paper presents its first comprehensive validation on real-world data collected directly by industrial partners in active production environments. We evaluate the framework across three representative use cases: woodworking production monitoring, human-aware AGV navigation, and multi-camera ergonomic risk assessment. The approach employs learned visual transformations that obscure sensitive or task-irrelevant information while retaining features essential for task performance. Through both quantitative evaluation of the privacy-utility trade-off and qualitative feedback from industrial partners, we assess the framework's effectiveness, deployment feasibility, and trust implications. Results demonstrate that task-specific obfuscation enables effective monitoring with reduced privacy risks, establishing the framework's readiness for real-world adoption and providing cross-domain recommendations for responsible, human-centric AI deployment in industry.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.09309v1">A Distributed Framework for Privacy-Enhanced Vision Transformers on the Edge</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-12-10T04:37:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zihao Ding, Mufeng Zhu, Zhongze Tang, Sheng Wei, Yao Liu</p>
    <p><b>Summary:</b> Nowadays, visual intelligence tools have become ubiquitous, offering all kinds of convenience and possibilities. However, these tools have high computational requirements that exceed the capabilities of resource-constrained mobile and wearable devices. While offloading visual data to the cloud is a common solution, it introduces significant privacy vulnerabilities during transmission and server-side computation. To address this, we propose a novel distributed, hierarchical offloading framework for Vision Transformers (ViTs) that addresses these privacy challenges by design. Our approach uses a local trusted edge device, such as a mobile phone or an Nvidia Jetson, as the edge orchestrator. This orchestrator partitions the user's visual data into smaller portions and distributes them across multiple independent cloud servers. By design, no single external server possesses the complete image, preventing comprehensive data reconstruction. The final data merging and aggregation computation occurs exclusively on the user's trusted edge device. We apply our framework to the Segment Anything Model (SAM) as a practical case study, which demonstrates that our method substantially enhances content privacy over traditional cloud-based approaches. Evaluations show our framework maintains near-baseline segmentation performance while substantially reducing the risk of content reconstruction and user data exposure. Our framework provides a scalable, privacy-preserving solution for vision tasks in the edge-cloud continuum.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.08870v1">Fed-SE: Federated Self-Evolution for Privacy-Constrained Multi-Environment LLM Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-12-09T18:04:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiang Chen, Yuling Shi, Qizhen Lan, Yuchao Qiu, Xiaodong Gu</p>
    <p><b>Summary:</b> LLM agents are widely deployed in complex interactive tasks, yet privacy constraints often preclude centralized optimization and co-evolution across dynamic environments. While Federated Learning (FL) has proven effective on static datasets, its extension to the open-ended self-evolution of agents remains underexplored. Directly applying standard FL is challenging: heterogeneous tasks and sparse, trajectory-level rewards introduce severe gradient conflicts, destabilizing the global optimization process. To bridge this gap, we propose Fed-SE, a Federated Self-Evolution framework for LLM agents. Fed-SE establishes a local evolution-global aggregation paradigm. Locally, agents employ parameter-efficient fine-tuning on filtered, high-return trajectories to achieve stable gradient updates. Globally, Fed-SE aggregates updates within a low-rank subspace that disentangles environment-specific dynamics, effectively reducing negative transfer across clients. Experiments across five heterogeneous environments demonstrate that Fed-SE improves average task success rates by approximately 18% over federated baselines, validating its effectiveness in robust cross-environment knowledge transfer in privacy-constrained deployments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.08862v1">Secure and Privacy-Preserving Federated Learning for Next-Generation Underground Mine Safety</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-12-09T17:53:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohamed Elmahallawy, Sanjay Madria, Samuel Frimpong</p>
    <p><b>Summary:</b> Underground mining operations depend on sensor networks to monitor critical parameters such as temperature, gas concentration, and miner movement, enabling timely hazard detection and safety decisions. However, transmitting raw sensor data to a centralized server for machine learning (ML) model training raises serious privacy and security concerns. Federated Learning (FL) offers a promising alternative by enabling decentralized model training without exposing sensitive local data. Yet, applying FL in underground mining presents unique challenges: (i) Adversaries may eavesdrop on shared model updates to launch model inversion or membership inference attacks, compromising data privacy and operational safety; (ii) Non-IID data distributions across mines and sensor noise can hinder model convergence. To address these issues, we propose FedMining--a privacy-preserving FL framework tailored for underground mining. FedMining introduces two core innovations: (1) a Decentralized Functional Encryption (DFE) scheme that keeps local models encrypted, thwarting unauthorized access and inference attacks; and (2) a balancing aggregation mechanism to mitigate data heterogeneity and enhance convergence. Evaluations on real-world mining datasets demonstrate FedMining's ability to safeguard privacy while maintaining high model accuracy and achieving rapid convergence with reduced communication and computation overhead. These advantages make FedMining both secure and practical for real-time underground safety monitoring.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.08809v1">PrivTune: Efficient and Privacy-Preserving Fine-Tuning of Large Language Models via Device-Cloud Collaboration</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-12-09T17:03:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yi Liu, Weixiang Han, Chengjun Cai, Xingliang Yuan, Cong Wang</p>
    <p><b>Summary:</b> With the rise of large language models, service providers offer language models as a service, enabling users to fine-tune customized models via uploaded private datasets. However, this raises concerns about sensitive data leakage. Prior methods, relying on differential privacy within device-cloud collaboration frameworks, struggle to balance privacy and utility, exposing users to inference attacks or degrading fine-tuning performance. To address this, we propose PrivTune, an efficient and privacy-preserving fine-tuning framework via Split Learning (SL). The key idea of PrivTune is to inject crafted noise into token representations from the SL bottom model, making each token resemble the $n$-hop indirect neighbors. PrivTune formulates this as an optimization problem to compute the optimal noise vector, aligning with defense-utility goals. On this basis, it then adjusts the parameters (i.e., mean) of the $d_χ$-Privacy noise distribution to align with the optimization direction and scales the noise according to token importance to minimize distortion. Experiments on five datasets (covering both classification and generation tasks) against three embedding inversion and three attribute inference attacks show that, using RoBERTa on the Stanford Sentiment Treebank dataset, PrivTune reduces the attack success rate to 10% with only a 3.33% drop in utility performance, outperforming state-of-the-art baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.08503v1">Disrupting Hierarchical Reasoning: Adversarial Protection for Geographic Privacy in Multimodal Reasoning Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-12-09T11:35:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiaming Zhang, Che Wang, Yang Cao, Longtao Huang, Wei Yang Bryan Lim</p>
    <p><b>Summary:</b> Multi-modal large reasoning models (MLRMs) pose significant privacy risks by inferring precise geographic locations from personal images through hierarchical chain-of-thought reasoning. Existing privacy protection techniques, primarily designed for perception-based models, prove ineffective against MLRMs' sophisticated multi-step reasoning processes that analyze environmental cues. We introduce \textbf{ReasonBreak}, a novel adversarial framework specifically designed to disrupt hierarchical reasoning in MLRMs through concept-aware perturbations. Our approach is founded on the key insight that effective disruption of geographic reasoning requires perturbations aligned with conceptual hierarchies rather than uniform noise. ReasonBreak strategically targets critical conceptual dependencies within reasoning chains, generating perturbations that invalidate specific inference steps and cascade through subsequent reasoning stages. To facilitate this approach, we contribute \textbf{GeoPrivacy-6K}, a comprehensive dataset comprising 6,341 ultra-high-resolution images ($\geq$2K) with hierarchical concept annotations. Extensive evaluation across seven state-of-the-art MLRMs (including GPT-o3, GPT-5, Gemini 2.5 Pro) demonstrates ReasonBreak's superior effectiveness, achieving a 14.4\% improvement in tract-level protection (33.8\% vs 19.4\%) and nearly doubling block-level protection (33.5\% vs 16.8\%). This work establishes a new paradigm for privacy protection against reasoning-based threats.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.08310v1">Privacy-Preserving Identifier Checking in 5G</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-12-09T07:17:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marcel D. S. K. Gräfenstein, Stefan Köpsell, Maryam Zarezadeh</p>
    <p><b>Summary:</b> Device identifiers like the International Mobile Equipment Identity (IMEI) are crucial for ensuring device integrity and meeting regulations in 4G and 5G networks. However, sharing these identifiers with Mobile Network Operators (MNOs) brings significant privacy risks by enabling long-term tracking and linking of user activities across sessions. In this work, we propose a privacy-preserving identifier checking method in 5G. This paper introduces a protocol for verifying device identifiers without exposing them to the network while maintaining the same functions as the 3GPP-defined Equipment Identity Register (EIR) process. The proposed solution modifies the PEPSI protocol for a Private Set Membership (PSM) setting using the BFV homomorphic encryption scheme. This lets User Equipment (UE) prove that its identifier is not on an operator's blacklist or greylist while ensuring that the MNO only learns the outcome of the verification. The protocol allows controlled deanonymization through an authorized Law Enforcement (LE) hook, striking a balance between privacy and accountability. Implementation results show that the system can perform online verification within five seconds and requires about 15 to 16 MB of communication per session. This confirms its practical use under post-quantum security standards. The findings highlight the promise of homomorphic encryption for managing identifiers while preserving privacy in 5G, laying the groundwork for scalable and compliant verification systems in future 6G networks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.08263v1">Geometry-Aligned Differential Privacy for Location-Safe Federated Radio Map Construction</a></h3>
  
  <p><b>Published on:</b> 2025-12-09T05:40:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jijia Tian, Wangqian Chen, Junting Chen, Pooi-Yuen Kam</p>
    <p><b>Summary:</b> Radio maps that describe spatial variations in wireless signal strength are widely used to optimize networks and support aerial platforms. Their construction requires location-labeled signal measurements from distributed users, raising fundamental concerns about location privacy. Even when raw data are kept local, the shared model updates can reveal user locations through their spatial structure, while naive noise injection either fails to hide this leakage or degrades model accuracy. This work analyzes how location leakage arises from gradients in a virtual-environment radio map model and proposes a geometry-aligned differential privacy mechanism with heterogeneous noise tailored to both confuse localization and cover gradient spatial patterns. The approach is theoretically supported with a convergence guarantee linking privacy strength to learning accuracy. Numerical experiments show the approach increases attacker localization error from 30 m to over 180 m, with only 0.2 dB increase in radio map construction error compared to a uniform-noise baseline.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.08185v1">A Practical Framework for Evaluating Medical AI Security: Reproducible Assessment of Jailbreaking and Privacy Vulnerabilities Across Clinical Specialties</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-12-09T02:28:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jinghao Wang, Ping Zhang, Carter Yagemann</p>
    <p><b>Summary:</b> Medical Large Language Models (LLMs) are increasingly deployed for clinical decision support across diverse specialties, yet systematic evaluation of their robustness to adversarial misuse and privacy leakage remains inaccessible to most researchers. Existing security benchmarks require GPU clusters, commercial API access, or protected health data -- barriers that limit community participation in this critical research area. We propose a practical, fully reproducible framework for evaluating medical AI security under realistic resource constraints. Our framework design covers multiple medical specialties stratified by clinical risk -- from high-risk domains such as emergency medicine and psychiatry to general practice -- addressing jailbreaking attacks (role-playing, authority impersonation, multi-turn manipulation) and privacy extraction attacks. All evaluation utilizes synthetic patient records requiring no IRB approval. The framework is designed to run entirely on consumer CPU hardware using freely available models, eliminating cost barriers. We present the framework specification including threat models, data generation methodology, evaluation protocols, and scoring rubrics. This proposal establishes a foundation for comparative security assessment of medical-specialist models and defense mechanisms, advancing the broader goal of ensuring safe and trustworthy medical AI systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.08104v1">AgentCrypt: Advancing Privacy and (Secure) Computation in AI Agent Collaboration</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-12-08T23:20:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Harish Karthikeyan, Yue Guo, Leo de Castro, Antigoni Polychroniadou, Leo Ardon, Udari Madhushani Sehwag, Sumitra Ganesh, Manuela Veloso</p>
    <p><b>Summary:</b> As AI agents increasingly operate in real-world, multi-agent environments, ensuring reliable and context-aware privacy in agent communication is critical, especially to comply with evolving regulatory requirements. Traditional access controls are insufficient, as privacy risks often arise after access is granted; agents may use information in ways that compromise privacy, such as messaging humans, sharing context with other agents, making tool calls, persisting data, or generating derived private information. Existing approaches often treat privacy as a binary constraint, whether data is shareable or not, overlooking nuanced, role-specific, and computation-dependent privacy needs essential for regulatory compliance.
  Agents, including those based on large language models, are inherently probabilistic and heuristic. There is no formal guarantee of how an agent will behave for any query, making them ill-suited for operations critical to security. To address this, we introduce AgentCrypt, a four-tiered framework for fine-grained, encrypted agent communication that adds a protection layer atop any AI agent platform. AgentCrypt spans unrestricted data exchange (Level 1) to fully encrypted computation using techniques such as homomorphic encryption (Level 4). Crucially, it guarantees the privacy of tagged data is always maintained, prioritizing privacy above correctness.
  AgentCrypt ensures privacy across diverse interactions and enables computation on otherwise inaccessible data, overcoming barriers such as data silos. We implemented and tested it with Langgraph and Google ADK, demonstrating versatility across platforms. We also introduce a benchmark dataset simulating privacy-critical tasks at all privacy levels, enabling systematic evaluation and fostering the development of regulatable machine learning systems for secure agent communication and computation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.08096v1">Selling Privacy in Blockchain Transactions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB">
  <p><b>Published on:</b> 2025-12-08T23:13:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Georgios Chionas, Olga Gorelkina, Piotr Krysta, Rida Laraki</p>
    <p><b>Summary:</b> We study methods to enhance privacy in blockchain transactions from an economic angle. We consider mechanisms for privacy-aware users whose utility depends not only on the outcome of the mechanism but also negatively on the exposure of their economic preferences. Specifically, we study two auction-theoretic settings with privacy-aware users. First, we analyze an order flow auction, where a user auctions off to specialized agents, called searchers, the right to execute her transaction while maintaining a degree of privacy. We examine how the degree of privacy affects the revenue of the auction and, broadly, the net utility of the privacy-aware user. In this new setting, we describe the optimal auction, which is a sealed-bid auction. Subsequently, we analyze a variant of a Dutch auction in which the user gradually decreases the price and the degree of privacy until the transaction is sold. We compare the revenue of this auction to that of the optimal one as a function of the number of communication rounds. Then, we introduce a two-sided market - a privacy marketplace - with multiple users selling their transactions under their privacy preferences to multiple searchers. We propose a posted-price mechanism for the two-sided market that guarantees constant approximation of the optimal social welfare while maintaining incentive compatibility (from both sides of the market) and budget balance. This work builds on the emerging line of research that attempts to improve the performance of economic mechanisms by appending cryptographic primitives to them.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.08025v1">"Your Privacy is Your Responsibility": Understanding How Users Collectively Navigate the Complexity of Privacy on Quora</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-12-08T20:35:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Varun Shiri, Maggie Xiong, Jin L. C. Guo, Jinghui Cheng</p>
    <p><b>Summary:</b> In the current technology environment, users are often in a vulnerable position when it comes to protecting their privacy. Previous efforts to promote privacy protection have largely focused on top-down approaches such as regulation and technology design, missing opportunities to understand how to empower users through bottom-up, collective approaches. Our paper addresses this by analyzing what and how privacy-related topics are discussed on Quora. We identified a wide range of interconnected privacy topics brought up by the users, including privacy risks and dangers, protection strategies, organizational practices, and existing laws and regulations. Our results highlight the interplay among the individual, technological, organizational, and societal factors affecting users' privacy attitudes. Moreover, we provide implications for designing community-based tools to better support users' collective efforts in navigating privacy, tools that incorporate users' diverse privacy-related behaviors and preferences, simplify information access and sharing, and connect designers and developers with the user community.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.07814v2">Understanding Privacy Risks in Code Models Through Training Dynamics: A Causal Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-12-08T18:47:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hua Yang, Alejandro Velasco, Sen Fang, Bowen Xu, Denys Poshyvanyk</p>
    <p><b>Summary:</b> Large language models for code (LLM4Code) have greatly improved developer productivity but also raise privacy concerns due to their reliance on open-source repositories containing abundant personally identifiable information (PII). Prior work shows that commercial models can reproduce sensitive PII, yet existing studies largely treat PII as a single category and overlook the heterogeneous risks among different types. We investigate whether distinct PII types vary in their likelihood of being learned and leaked by LLM4Code, and whether this relationship is causal. Our methodology includes building a dataset with diverse PII types, fine-tuning representative models of different scales, computing training dynamics on real PII data, and formulating a structural causal model to estimate the causal effect of learnability on leakage. Results show that leakage risks differ substantially across PII types and correlate with their training dynamics: easy-to-learn instances such as IP addresses exhibit higher leakage, while harder types such as keys and passwords leak less frequently. Ambiguous types show mixed behaviors. This work provides the first causal evidence that leakage risks are type-dependent and offers guidance for developing type-aware and learnability-aware defenses for LLM4Code.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.07725v1">Privacy Practices of Browser Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-12-08T17:16:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alisha Ukani, Hamed Haddadi, Ali Shahin Shamsabadi, Peter Snyder</p>
    <p><b>Summary:</b> This paper presents a systematic evaluation of the privacy behaviors and attributes of eight recent, popular browser agents. Browser agents are software that automate Web browsing using large language models and ancillary tooling. However, the automated capabilities that make browser agents powerful also make them high-risk points of failure. Both the kinds of tasks browser agents are designed to execute, along with the kinds of information browser agents are entrusted with to fulfill those tasks, mean that vulnerabilities in these tools can result in enormous privacy harm.
  This work presents a framework of five broad factors (totaling 15 distinct measurements) to measure the privacy risks in browser agents. Our framework assesses i. vulnerabilities in the browser agent's components, ii. how the browser agent protects against website behaviors, iii. whether the browser agent prevents cross-site tracking, iv. how the agent responds to privacy-affecting prompts, and v. whether the tool leaks personal information to sites. We apply our framework to eight browser agents and identify 30 vulnerabilities, ranging from disabled browser privacy features to "autocompleting" sensitive personal information in form fields. We have responsibly disclosed our findings, and plan to release our dataset and other artifacts.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.07166v1">When Privacy Meets Recovery: The Overlooked Half of Surrogate-Driven Privacy Preservation for MLLM Editing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-12-08T04:59:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Siyuan Xu, Yibing Liu, Peilin Chen, Yung-Hui Li, Shiqi Wang, Sam Kwong</p>
    <p><b>Summary:</b> Privacy leakage in Multimodal Large Language Models (MLLMs) has long been an intractable problem. Existing studies, though effectively obscure private information in MLLMs, often overlook the evaluation of the authenticity and recovery quality of user privacy. To this end, this work uniquely focuses on the critical challenge of how to restore surrogate-driven protected data in diverse MLLM scenarios. We first bridge this research gap by contributing the SPPE (Surrogate Privacy Protected Editable) dataset, which includes a wide range of privacy categories and user instructions to simulate real MLLM applications. This dataset offers protected surrogates alongside their various MLLM-edited versions, thus enabling the direct assessment of privacy recovery quality. By formulating privacy recovery as a guided generation task conditioned on complementary multimodal signals, we further introduce a unified approach that reliably reconstructs private content while preserving the fidelity of MLLM-generated edits. The experiments on both SPPE and InstructPix2Pix further show that our approach generalizes well across diverse visual content and editing tasks, achieving a strong balance between privacy protection and MLLM usability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.06971v1">Prediction with Expert Advice under Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> 
  <p><b>Published on:</b> 2025-12-07T19:31:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ben Jacobsen, Kassem Fawaz</p>
    <p><b>Summary:</b> We study the classic problem of prediction with expert advice under the constraint of local differential privacy (LDP). In this context, we first show that a classical algorithm naturally satisfies LDP and then design two new algorithms that improve it: RW-AdaBatch and RW-Meta. For RW-AdaBatch, we exploit the limited-switching behavior induced by LDP to provide a novel form of privacy amplification that grows stronger on easier data, analogous to the shuffle model in offline learning. Drawing on the theory of random walks, we prove that this improvement carries essentially no utility cost. For RW-Meta, we develop a general method for privately selecting between experts that are themselves non-trivial learning algorithms, and we show that in the context of LDP this carries no extra privacy cost. In contrast, prior work has only considered data-independent experts. We also derive formal regret bounds that scale inversely with the degree of independence between experts. Our analysis is supplemented by evaluation on real-world data reported by hospitals during the COVID-19 pandemic; RW-Meta outperforms both the classical baseline and a state-of-the-art \textit{central} DP algorithm by 1.5-3$\times$ on the task of predicting which hospital will report the highest density of COVID patients each week.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.06747v1">PrivLLMSwarm: Privacy-Preserving LLM-Driven UAV Swarms for Secure IoT Surveillance</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-12-07T09:20:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jifar Wakuma Ayana, Huang Qiming</p>
    <p><b>Summary:</b> Large Language Models (LLMs) are emerging as powerful enablers for autonomous reasoning and natural-language coordination in unmanned aerial vehicle (UAV) swarms operating within Internet of Things (IoT) environments. However, existing LLM-driven UAV systems process sensitive operational data in plaintext, exposing them to privacy and security risks. This work introduces PrivLLMSwarm, a privacy-preserving framework that performs secure LLM inference for UAV swarm coordination through Secure Multi-Party Computation (MPC). The framework incorporates MPC-optimized transformer components with efficient approximations of nonlinear activations, enabling practical encrypted inference on resource-constrained aerial platforms. A fine-tuned GPT-based command generator, enhanced through reinforcement learning in simulation, provides reliable instructions while maintaining confidentiality. Experimental evaluation in urban-scale simulations demonstrates that PrivLLMSwarm achieves high semantic accuracy, low encrypted inference latency, and robust formation control under privacy constraints. Comparative analysis shows PrivLLMSwarm offers a superior privacy-utility balance compared to differential privacy, federated learning, and plaintext baselines. To support reproducibility, the full implementation including source code, MPC components, and a synthetic dataset is publicly available. PrivLLMSwarm establishes a practical foundation for secure, LLM-enabled UAV swarms in privacy-sensitive IoT applications including smart-city monitoring and emergency response.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.06711v1">Parameter-Efficient Fine-Tuning with Differential Privacy for Robust Instruction Adaptation in Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-12-07T08:01:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yulin Huang, Yaxuan Luan, Jinxu Guo, Xiangchen Song, Yuchen Liu</p>
    <p><b>Summary:</b> This study addresses the issues of privacy protection and efficiency in instruction fine-tuning of large-scale language models by proposing a parameter-efficient method that integrates differential privacy noise allocation with gradient clipping in a collaborative optimization framework. The method keeps the backbone model frozen and updates parameters through a low-dimensional projection subspace, while introducing clipping and adaptive noise allocation during gradient computation. This design reduces privacy budget consumption and ensures training stability and robustness. The unified framework combines gradient constraints, noise allocation, and parameter projection, effectively mitigating performance fluctuations and privacy risks in multi-task instruction scenarios. Experiments are conducted across hyperparameter, environment, and data sensitivity dimensions. Results show that the method outperforms baseline models in accuracy, privacy budget, and parameter efficiency, and maintains stable performance under diverse and uncertain data conditions. The findings enrich the theoretical integration of differential privacy and parameter-efficient fine-tuning and demonstrate its practical adaptability in instruction tasks, providing a feasible solution for secure training in complex instruction environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.06534v1">"Having Confidence in My Confidence Intervals": How Data Users Engage with Privacy-Protected Wikipedia Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-12-06T18:59:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Harold Triedman, Jayshree Sarathy, Priyanka Nanayakkara, Rachel Cummings, Gabriel Kaptchuk, Sean Kross, Elissa M. Redmiles</p>
    <p><b>Summary:</b> In response to calls for open data and growing privacy threats, organizations are increasingly adopting privacy-preserving techniques such as differential privacy (DP) that inject statistical noise when generating published datasets. These techniques are designed to protect privacy of data subjects while enabling useful analyses, but their reception by data users is under-explored. We developed documentation that presents the noise characteristics of two Wikipedia pageview datasets: one using rounding (heuristic privacy) and another using DP (formal privacy). After incorporating expert feedback (n=5), we used these documents to conduct a task-based contextual inquiry (n=15) exploring how data users--largely unfamiliar with these methods--perceive, interact with, and interpret privacy-preserving noise during data analysis.
  Participants readily used simple uncertainty metrics from the documentation, but struggled when asked to compute confidence intervals across multiple noisy estimates. They were better able to devise simulation-based approaches for computing uncertainty with DP data compared to rounded data. Surprisingly, several participants incorrectly believed DP's stronger utility implied weaker privacy protections. Based on our findings, we offer design recommendations for documentation and tools to better support data users working with privacy-noised data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.06380v1">Protecting Bystander Privacy via Selective Hearing in LALMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-12-06T10:24:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiao Zhan, Guangzhi Sun, Jose Such, Phil Woodland</p>
    <p><b>Summary:</b> Large audio language models (LALMs) are increasingly deployed in real-world settings where they inevitably capture speech from unintended nearby bystanders, raising privacy risks that existing benchmarks and defences largely overlook. We introduce SH-Bench, the first benchmark designed to evaluate selective hearing: a model's ability to attend to an intended main speaker while refusing to process or reveal information about incidental bystander speech. SH-Bench contains 3,968 multi-speaker audio mixtures spanning both real-world and synthetic scenarios, paired with 77k multiple-choice questions that probe models under general and selective operating modes. We propose Selective Efficacy (SE), a unified metric capturing both multi-speaker comprehension and bystander-privacy protection. Our evaluation of state-of-the-art open-source and proprietary LALMs reveals substantial privacy leakage, with strong audio understanding failing to translate into selective protection of bystander privacy. To mitigate this gap, we introduce Bystander Privacy Fine-Tuning (BPFT), a training pipeline that teaches models to refuse bystander-related queries without degrading main-speaker comprehension. BPFT yields substantial gains which improve SE by up to 15.9% over Gemini 2.5 Pro, demonstrating that selective hearing is learnable but far from achieved in current LALMs. SH-Bench and BPFT provide the first systematic framework for measuring and improving bystander privacy in audio foundation models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.06253v2">Privacy Loss of Noise Perturbation via Concentration Analysis of A Product Measure</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-12-06T02:55:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuainan Liu, Tianxi Ji, Zhongshuo Fang, Lu Wei, Pan Li</p>
    <p><b>Summary:</b> Noise perturbation is one of the most fundamental approaches for achieving $(ε,δ)$-differential privacy (DP) guarantees when releasing the result of a query or function $f(\cdot)\in\mathbb{R}^M$ evaluated on a sensitive dataset $\mathbf{x}$. In this approach, calibrated noise $\mathbf{n}\in\mathbb{R}^M$ is used to obscure the difference vector $f(\mathbf{x})-f(\mathbf{x}')$, where $\mathbf{x}'$ is known as a neighboring dataset. A DP guarantee is obtained by studying the tail probability bound of a privacy loss random variable (PLRV), defined as the Radon-Nikodym derivative between two distributions. When $\mathbf{n}$ follows a multivariate Gaussian distribution, the PLRV is characterized as a specific univariate Gaussian. In this paper, we propose a novel scheme to generate $\mathbf{n}$ by leveraging the fact that the perturbation noise is typically spherically symmetric (i.e., the distribution is rotationally invariant around the origin). The new noise generation scheme allows us to investigate the privacy loss from a geometric perspective and express the resulting PLRV using a product measure, $W\times U$; measure $W$ is related to a radius random variable controlling the magnitude of $\mathbf{n}$, while measure $U$ involves a directional random variable governing the angle between $\mathbf{n}$ and the difference $f(\mathbf{x})-f(\mathbf{x}')$. We derive a closed-form moment bound on the product measure to prove $(ε,δ)$-DP. Under the same $(ε,δ)$-DP guarantee, our mechanism yields a smaller expected noise magnitude than the classic Gaussian noise in high dimensions, thereby significantly improving the utility of the noisy result $f(\mathbf{x})+\mathbf{n}$. To validate this, we consider convex and non-convex empirical risk minimization (ERM) problems in high dimensional space and apply the proposed product noise to achieve privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.06062v1">When Privacy Isn't Synthetic: Hidden Data Leakage in Generative AI Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-12-05T18:52:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> S. M. Mustaqim, Anantaa Kotal, Paul H. Yi</p>
    <p><b>Summary:</b> Generative models are increasingly used to produce privacy-preserving synthetic data as a safe alternative to sharing sensitive training datasets. However, we demonstrate that such synthetic releases can still leak information about the underlying training samples through structural overlap in the data manifold. We propose a black-box membership inference attack that exploits this vulnerability without requiring access to model internals or real data. The attacker repeatedly queries the generative model to obtain large numbers of synthetic samples, performs unsupervised clustering to identify dense regions of the synthetic distribution, and then analyzes cluster medoids and neighborhoods that correspond to high-density regions in the original training data. These neighborhoods act as proxies for training samples, enabling the adversary to infer membership or reconstruct approximate records. Our experiments across healthcare, finance, and other sensitive domains show that cluster overlap between real and synthetic data leads to measurable membership leakage-even when the generator is trained with differential privacy or other noise mechanisms. The results highlight an under-explored attack surface in synthetic data generation pipelines and call for stronger privacy guarantees that account for distributional neighborhood inference rather than sample-level memorization alone, underscoring its role in privacy-preserving data publishing. Implementation and evaluation code are publicly available at:github.com/Cluster-Medoid-Leakage-Attack.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.05730v1">De mythe van geïnformeerde toestemming: online privacybescherming kan beter [Informed Consent: We Can Do Better to Defend Privacy]</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-12-05T14:08:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Frederik Zuiderveen Borgesius</p>
    <p><b>Summary:</b> We need to rethink our approach to defend privacy on the internet. Currently, policymakers focus heavily on the idea of informed consent as a means to defend privacy. For instance, in many countries the law requires firms to obtain an individual's consent before they use data about her; with such informed consent requirements, the law aims to empower people to make privacy choices in their best interests. But behavioural studies cast doubt on this approach's effectiveness, as people tend to click OK to almost any request they see on their screens. To improve privacy protection, this article argues for a combined approach of protecting and empowering the individual. This article discusses practical problems with informed consent as a means to protect privacy, and illustrates the problems with current data privacy rules regarding behavioural targeting. First, the privacy problems of behavioural targeting, and the central role of informed consent in privacy law are discussed. Following that, practical problems with informed consent are highlighted. Then, the article argues that policymakers should give more attention to rules that protect, rather than empower, people.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.05729v1">Informed Consent: We Can Do Better to Defend Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-12-05T14:08:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Frederik Zuiderveen Borgesius</p>
    <p><b>Summary:</b> We need to rethink our approach to defend privacy on the internet. Currently, policymakers focus heavily on the idea of informed consent as a means to defend privacy. For instance, in many countries the law requires firms to obtain an individual's consent before they use data about her; with such informed consent requirements, the law aims to empower people to make privacy choices in their best interests. But behavioural studies cast doubt on this approach's effectiveness, as people tend to click OK to almost any request they see on their screens. To improve privacy protection, this article argues for a combined approach of protecting and empowering the individual. This article discusses practical problems with informed consent as a means to protect privacy, and illustrates the problems with current data privacy rules regarding behavioural targeting. First, the privacy problems of behavioural targeting, and the central role of informed consent in privacy law are discussed. Following that, practical problems with informed consent are highlighted. Then, the article argues that policymakers should give more attention to rules that protect, rather than empower, people.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.05728v1">Open Data, Privacy, and Fair Information Principles: Towards a Balancing Framework</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-12-05T14:08:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Frederik Zuiderveen Borgesius, Jonathan Gray, Mireille van Eechoud</p>
    <p><b>Summary:</b> Open data are held to contribute to a wide variety of social and political goals, including strengthening transparency, public participation and democratic accountability, promoting economic growth and innovation, and enabling greater public sector efficiency and cost savings. However, releasing government data that contain personal information may threaten privacy and related rights and interests. In this Article we ask how these privacy interests can be respected, without unduly hampering benefits from disclosing public sector information. We propose a balancing framework to help public authorities address this question in different contexts. The framework takes into account different levels of privacy risks for different types of data. It also separates decisions about access and re-use, and highlights a range of different disclosure routes. A circumstance catalogue lists factors that might be considered when assessing whether, under which conditions, and how a dataset can be released. While open data remains an important route for the publication of government information, we conclude that it is not the only route, and there must be clear and robust public interest arguments in order to justify the disclosure of personal information as open data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.05473v1">Privacy-Preserving Fully Distributed Gaussian Process Regression</a></h3>
  
  <p><b>Published on:</b> 2025-12-05T07:05:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yeongjun Jang, Kaoru Teranishi, Jihoon Suh, Takashi Tanaka</p>
    <p><b>Summary:</b> Although distributed Gaussian process regression (GPR) enables multiple agents with separate datasets to jointly learn a model of the target function, its collaborative nature poses risks of private data leakage. To address this, we propose a privacy-preserving fully distributed GPR protocol based on secure multi-party computation (SMPC) that preserves the confidentiality of each agent's local dataset. Building upon a secure distributed average consensus algorithm, the protocol guarantees that each agent's local model practically converges to the same global model that would be obtained by the standard distributed GPR. Further, we adopt the paradigm of simulation based security to provide formal privacy guarantees, and extend the proposed protocol to enable kernel hyperparameter optimization, which is critical yet often overlooked in the literature. Experimental results demonstrate the effectiveness and practical applicability of the proposed method.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.05459v1">PrivCode: When Code Generation Meets Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-12-05T06:27:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zheng Liu, Chen Gong, Terry Yue Zhuo, Kecen Li, Weichen Yu, Matt Fredrikson, Tianhao Wang</p>
    <p><b>Summary:</b> Large language models (LLMs) have presented outstanding performance in code generation and completion. However, fine-tuning these models on private datasets can raise privacy and proprietary concerns, such as the leakage of sensitive personal information. Differentially private (DP) code generation provides theoretical guarantees for protecting sensitive code by generating synthetic datasets that preserve statistical properties while reducing privacy leakage concerns. However, DP code generation faces significant challenges due to the strict syntactic dependencies and the privacy-utility trade-off.
  We propose PrivCode, the first DP synthesizer specifically designed for code datasets. It incorporates a two-stage framework to improve both privacy and utility. In the first stage, termed "privacy-sanitizing", PrivCode generates DP-compliant synthetic code by training models using DP-SGD while introducing syntactic information to preserve code structure. The second stage, termed "utility-boosting", fine-tunes a larger pre-trained LLM on the synthetic privacy-free code to mitigate the utility loss caused by DP, enhancing the utility of the generated code. Extensive experiments on four LLMs show that PrivCode generates higher-utility code across various testing tasks under four benchmarks. The experiments also confirm its ability to protect sensitive data under varying privacy budgets. We provide the replication package at the anonymous link.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.05065v2">Personalizing Agent Privacy Decisions via Logical Entailment</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-12-04T18:24:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> James Flemings, Ren Yi, Octavian Suciu, Kassem Fawaz, Murali Annavaram, Marco Gruteser</p>
    <p><b>Summary:</b> Personal language model-based agents are becoming more widespread for completing tasks on behalf of users; however, this raises serious privacy questions regarding whether these models will appropriately disclose user data. While prior work has evaluated language models on data-sharing scenarios based on general privacy norms, we focus on personalizing language models' privacy decisions, grounding their judgments directly in prior user privacy decisions. Our findings suggest that general privacy norms are insufficient for effective personalization of privacy decisions. Furthermore, we find that eliciting privacy judgments from the model through In-context Learning (ICL) is unreliable to due misalignment with the user's prior privacy judgments and opaque reasoning traces, which make it difficult for the user to interpret the reasoning behind the model's decisions. To address these limitations, we propose ARIEL (Agentic Reasoning with Individualized Entailment Logic), a framework that jointly leverages a language model and rule-based logic for structured data-sharing reasoning. ARIEL is based on formulating personalization of data sharing as an entailment, whether a prior user judgment on a data-sharing request implies the same judgment for an incoming request. Our experimental evaluations on advanced models and publicly-available datasets demonstrate that ARIEL can reduce the F1 score error by $\textbf{39.1%}$ over language model-based reasoning (ICL), demonstrating that ARIEL is effective at correctly judging requests where the user would approve data sharing. Overall, our findings suggest that combining LLMs with strict logical entailment is a highly effective strategy for enabling personalized privacy judgments for agents.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.05053v1">A Randomized Scheduling Framework for Privacy-Preserving Multi-robot Rendezvous given Prior Information</a></h3>
  
  <p><b>Published on:</b> 2025-12-04T18:07:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Le Liu, Yu Kawano, Ming Cao</p>
    <p><b>Summary:</b> Privacy has become a critical concern in modern multi-robot systems, driven by both ethical considerations and operational constraints. As a result, growing attention has been directed toward privacy-preserving coordination in dynamical multi-robot systems. This work introduces a randomized scheduling mechanism for privacy-preserving robot rendezvous. The proposed approach achieves improved privacy even at lower communication rates, where privacy is quantified via pointwise maximal leakage. We show that lower transmission rates provide stronger privacy guarantees and prove that rendezvous is still achieved under the randomized scheduling mechanism. Numerical simulations are provided to demonstrate the effectiveness of the method.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.04852v1">Ask Safely: Privacy-Aware LLM Query Generation for Knowledge Graphs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2025-12-04T14:37:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mauro Dalle Lucca Tosi, Jordi Cabot</p>
    <p><b>Summary:</b> Large Language Models (LLMs) are increasingly used to query knowledge graphs (KGs) due to their strong semantic understanding and extrapolation capabilities compared to traditional approaches. However, these methods cannot be applied when the KG contains sensitive data and the user lacks the resources to deploy a local generative LLM. To address this issue, we propose a privacy-aware query generation approach for KGs. Our method identifies sensitive information in the graph based on its structure and omits such values before requesting the LLM to translate natural language questions into Cypher queries. Experimental results show that our approach preserves the quality of the generated queries while preventing sensitive data from being transmitted to third-party services.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.04316v2">ConsentDiff at Scale: Longitudinal Audits of Web Privacy Policy Changes and UI Frictions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-12-03T23:05:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haoze Guo</p>
    <p><b>Summary:</b> Web privacy is experienced via two public artifacts: site utterances in policy texts, and the actions users are required to take during consent interfaces. In the extensive cross-section audits we've studied, there is a lack of longitudinal data detailing how these artifacts are changing together, and if interfaces are actually doing what they promise in policy. ConsentDiff provides that longitudinal view. We build a reproducible pipeline that snapshots sites every month, semantically aligns policy clauses to track clause-level churn, and classifies consent-UI patterns by pulling together DOM signals with cues provided by screenshots. We introduce a novel weighted claim-UI alignment score, connecting common policy claims to observable predicates, and enabling comparisons over time, regions, and verticals. Our measurements suggest continued policy churn, systematic changes to eliminate a higher-friction banner design, and significantly higher alignment where rejecting is visible and lower friction.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.04225v1">GOPHER: Optimization-based Phenotype Randomization for Genome-Wide Association Studies with Differential Privacy</a></h3>
  
  <p><b>Published on:</b> 2025-12-03T19:44:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anupama Nandi, Seth Neel, Hyunghoon Cho</p>
    <p><b>Summary:</b> Genome-wide association studies (GWAS) are an essential tool in biomedical research for identifying genetic factors linked to health and disease. However, publicly releasing GWAS summary statistics poses well-recognized privacy risks, including the potential to infer an individual's participation in the study or to reveal sensitive phenotypic information (e.g., disease status). While differential privacy (DP) offers a rigorous mathematical framework for mitigating these risks, existing DP techniques for GWAS either introduce excessive noise or restrict the release to a limited set of results. In this work, we present practical DP mechanisms for releasing the complete set of genome-wide association statistics with privacy guarantees. We demonstrate the accuracy of the privacy-preserving statistics released by our mechanisms on a range of GWAS datasets from the UK Biobank, utilizing both real and simulated phenotypes. We introduce two key techniques to overcome the limitations of prior approaches: (1) an optimization-based randomization mechanism that directly minimizes the expected error in GWAS results to enhance utility, and (2) the use of personalized priors, derived from predictive models privately trained on a subset of the dataset, to enable sample-specific optimization which further reduces the amount of noise introduced by DP. Overall, our work provides practical tools for accurately releasing comprehensive GWAS results with provable protection of study participants.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.03793v1">The enshittification of online search? Privacy and quality of Google, Bing and Apple in coding advice</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-12-03T13:42:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Konrad Kollnig</p>
    <p><b>Summary:</b> Even though currently being challenged by ChatGPT and other large-language models (LLMs), Google Search remains one of the primary means for many individuals to find information on the internet. Interestingly, the way that we retrieve information on the web has hardly changed ever since Google was established in 1998, raising concerns as to Google's dominance in search and lack of competition. If the market for search was sufficiently competitive, then we should probably see a steady increase in search quality over time as well as alternative approaches to the Google's approach to search. However, hardly any research has so far looked at search quality, which is a key facet of a competitive market, especially not over time.
  In this report, we conducted a relatively large-scale quantitative comparison of search quality of 1,467 search queries relating to coding advice in October 2023. We focus on coding advice because the study of general search quality is difficult, with the aim of learning more about the assessment of search quality and motivating follow-up research into this important topic. We evaluate the search quality of Google Search, Microsoft Bing, and Apple Search, with a special emphasis on Apple Search, a widely used search engine that has never been explored in previous research. For the assessment of search quality, we use two independent metrics of search quality: 1) the number of trackers on the first search result, as a measure of privacy in web search, and 2) the average rank of the first Stack Overflow search result, under the assumption that Stack Overflow gives the best coding advice. Our results suggest that the privacy of search results is higher on Bing than on Google and Apple. Similarly, the quality of coding advice -- as measured by the average rank of Stack Overflow -- was highest on Bing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.03791v1">CCN: Decentralized Cross-Chain Channel Networks Supporting Secure and Privacy-Preserving Multi-Hop Interactions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-12-03T13:41:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Minghui Xu, Yihao Guo, Yanqiang Zhang, Zhiguang Shan, Guangyong Shang, Zhen Ma, Bin Xiao, Xiuzhen Cheng</p>
    <p><b>Summary:</b> Cross-chain technology enables interoperability among otherwise isolated blockchains, supporting interactions across heterogeneous networks. Similar to how multi-hop communication became fundamental in the evolution of the Internet, the demand for multi-hop cross-chain interactions is gaining increasing attention. However, this growing demand introduces new security and privacy challenges. On the security side, multi-hop interactions depend on the availability of multiple participating nodes. If any node becomes temporarily offline during execution, the protocol may fail to complete correctly, leading to settlement failure or fund loss. On the privacy side, the need for on-chain transparency to validate intermediate states may unintentionally leak linkable information, compromising the unlinkability of user interactions. In this paper, we propose the Cross-Chain Channel Network (CCN), a decentralized network designed to support secure and privacy-preserving multi-hop cross-chain transactions. Through experimental evaluation, we identify two critical types of offline failures, referred to as active and passive offline cases, which have not been adequately addressed by existing solutions. To mitigate these issues, we introduce R-HTLC, a core protocol within CCN. R-HTLC incorporates an hourglass mechanism and a multi-path refund strategy to ensure settlement correctness even when some nodes go offline during execution. Importantly, CCN addresses not only the correctness under offline conditions but also maintains unlinkability in such adversarial settings. To overcome this, CCN leverages zero-knowledge proofs and off-chain coordination, ensuring that interaction relationships remain indistinguishable even when certain nodes are temporarily offline.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.03694v1">SRPG: Semantically Reconstructed Privacy Guard for Zero-Trust Privacy in Educational Multi-Agent Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2025-12-03T11:36:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuang Guo, Zihui Li</p>
    <p><b>Summary:</b> Multi-Agent Systems (MAS) with large language models (LLMs) enable personalized education but risk leaking minors personally identifiable information (PII) via unstructured dialogue. Existing privacy methods struggle to balance security and utility: role-based access control fails on unstructured text, while naive masking destroys pedagogical context. We propose SRPG, a privacy guard for educational MAS, using a Dual-Stream Reconstruction Mechanism: a strict sanitization stream ensures zero PII leakage, and a context reconstruction stream (LLM driven) recovers mathematical logic. This decouples instructional content from private data, preserving teaching efficacy. Tests on MathDial show SRPG works across models; with GPT-4o, it achieves 0.0000 Attack Success Rate (ASR) (zero leakage) and 0.8267 Exact Match, far outperforming the zero trust Pure LLM baseline (0.2138). SRPG effectively protects minors privacy without sacrificing mathematical instructional quality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.03669v1">Towards Privacy-Preserving Range Queries with Secure Learned Spatial Index over Encrypted Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2025-12-03T10:59:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zuan Wang, Juntao Lu, Jiazhuang Wu, Youliang Tian, Wei Song, Qiuxian Li, Duo Zhang</p>
    <p><b>Summary:</b> With the growing reliance on cloud services for large-scale data management, preserving the security and privacy of outsourced datasets has become increasingly critical. While encrypting data and queries can prevent direct content exposure, recent research reveals that adversaries can still infer sensitive information via access pattern and search path analysis. However, existing solutions that offer strong access pattern privacy often incur substantial performance overhead. In this paper, we propose a novel privacy-preserving range query scheme over encrypted datasets, offering strong security guarantees while maintaining high efficiency. To achieve this, we develop secure learned spatial index (SLS-INDEX), a secure learned index that integrates the Paillier cryptosystem with a hierarchical prediction architecture and noise-injected buckets, enabling data-aware query acceleration in the encrypted domain. To further obfuscate query execution paths, SLS-INDEXbased Range Queries (SLRQ) employs a permutation-based secure bucket prediction protocol. Additionally, we introduce a secure point extraction protocol that generates candidate results to reduce the overhead of secure computation. We provide formal security analysis under realistic leakage functions and implement a prototype to evaluate its practical performance. Extensive experiments on both real-world and synthetic datasets demonstrate that SLRQ significantly outperforms existing solutions in query efficiency while ensuring dataset, query, result, and access pattern privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.03358v1">Scaling Trust in Quantum Federated Learning: A Multi-Protocol Privacy Design</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-12-03T01:45:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dev Gurung, Shiva Raj Pokhrel</p>
    <p><b>Summary:</b> Quantum Federated Learning (QFL) promises to revolutionize distributed machine learning by combining the computational power of quantum devices with collaborative model training. Yet, privacy of both data and models remains a critical challenge. In this work, we propose a privacy-preserving QFL framework where a network of $n$ quantum devices trains local models and transmits them to a central server under a multi-layered privacy protocol. Our design leverages Singular Value Decomposition (SVD), Quantum Key Distribution (QKD), and Analytic Quantum Gradient Descent (AQGD) to secure data preparation, model sharing, and training stages. Through theoretical analysis and experiments on contemporary quantum platforms and datasets, we demonstrate that the framework robustly safeguards data and model confidentiality while maintaining training efficiency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.03238v1">How to DP-fy Your Data: A Practical Guide to Generating Synthetic Data With Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2025-12-02T21:14:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Natalia Ponomareva, Zheng Xu, H. Brendan McMahan, Peter Kairouz, Lucas Rosenblatt, Vincent Cohen-Addad, Cristóbal Guzmán, Ryan McKenna, Galen Andrew, Alex Bie, Da Yu, Alex Kurakin, Morteza Zadimoghaddam, Sergei Vassilvitskii, Andreas Terzis</p>
    <p><b>Summary:</b> High quality data is needed to unlock the full potential of AI for end users. However finding new sources of such data is getting harder: most publicly-available human generated data will soon have been used. Additionally, publicly available data often is not representative of users of a particular system -- for example, a research speech dataset of contractors interacting with an AI assistant will likely be more homogeneous, well articulated and self-censored than real world commands that end users will issue. Therefore unlocking high-quality data grounded in real user interactions is of vital interest. However, the direct use of user data comes with significant privacy risks. Differential Privacy (DP) is a well established framework for reasoning about and limiting information leakage, and is a gold standard for protecting user privacy. The focus of this work, \emph{Differentially Private Synthetic data}, refers to synthetic data that preserves the overall trends of source data,, while providing strong privacy guarantees to individuals that contributed to the source dataset. DP synthetic data can unlock the value of datasets that have previously been inaccessible due to privacy concerns and can replace the use of sensitive datasets that previously have only had rudimentary protections like ad-hoc rule-based anonymization.
  In this paper we explore the full suite of techniques surrounding DP synthetic data, the types of privacy protections they offer and the state-of-the-art for various modalities (image, tabular, text and decentralized). We outline all the components needed in a system that generates DP synthetic data, from sensitive data handling and preparation, to tracking the use and empirical privacy testing. We hope that work will result in increased adoption of DP synthetic data, spur additional research and increase trust in DP synthetic data approaches.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.03207v1">Technical Report: The Need for a (Research) Sandstorm through the Privacy Sandbox</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-12-02T20:14:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yohan Beugin, Patrick McDaniel</p>
    <p><b>Summary:</b> The Privacy Sandbox, launched in 2019, is a series of proposals from Google to reduce ``cross-site and cross-app tracking while helping to keep online content and services free for all''. Over the years, Google implemented, experimented, and deprecated some of these APIs into their own products (Chrome, Android, etc.) which raised concerns about the potential of these mechanisms to fundamentally disrupt the advertising, mobile, and web ecosystems. As a result, it is paramount for researchers to understand the consequences that these new technologies, and future ones, will have on billions of users if and when deployed. In this report, we outline our call for privacy, security, usability, and utility evaluations of these APIs, our efforts materialized through the creation and operation of Privacy Sandstorm (https://privacysandstorm.github.io); a research portal to systematically gather resources (overview, analyses, artifacts, etc.) about such proposals. We find that our inventory provides a better visibility and broader perspective on the research findings in that space than what Google lets show through official channels.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.02369v1">SAGE: Style-Adaptive Generalization for Privacy-Constrained Semantic Segmentation Across Domains</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-12-02T03:20:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qingmei Li, Yang Zhang, Peifeng Zhang, Haohuan Fu, Juepeng Zheng</p>
    <p><b>Summary:</b> Domain generalization for semantic segmentation aims to mitigate the degradation in model performance caused by domain shifts. However, in many real-world scenarios, we are unable to access the model parameters and architectural details due to privacy concerns and security constraints. Traditional fine-tuning or adaptation is hindered, leading to the demand for input-level strategies that can enhance generalization without modifying model weights. To this end, we propose a \textbf{S}tyle-\textbf{A}daptive \textbf{GE}neralization framework (\textbf{SAGE}), which improves the generalization of frozen models under privacy constraints. SAGE learns to synthesize visual prompts that implicitly align feature distributions across styles instead of directly fine-tuning the backbone. Specifically, we first utilize style transfer to construct a diverse style representation of the source domain, thereby learning a set of style characteristics that can cover a wide range of visual features. Then, the model adaptively fuses these style cues according to the visual context of each input, forming a dynamic prompt that harmonizes the image appearance without touching the interior of the model. Through this closed-loop design, SAGE effectively bridges the gap between frozen model invariance and the diversity of unseen domains. Extensive experiments on five benchmark datasets demonstrate that SAGE achieves competitive or superior performance compared to state-of-the-art methods under privacy constraints and outperforms full fine-tuning baselines in all settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.02301v1">Quantum Vanguard: Server Optimized Privacy Fortified Federated Intelligence for Future Vehicles</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-12-02T00:43:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dev Gurung, Shiva Raj Pokhrel</p>
    <p><b>Summary:</b> This work presents vQFL (vehicular Quantum Federated Learning), a new framework that leverages quantum machine learning techniques to tackle key privacy and security issues in autonomous vehicular networks. Furthermore, we propose a server-side adapted fine-tuning method, ft-VQFL,to achieve enhanced and more resilient performance. By integrating quantum federated learning with differential privacy and quantum key distribution (QKD), our quantum vanguard approach creates a multi-layered defense against both classical and quantum threats while preserving model utility. Extensive experimentation with industry-standard datasets (KITTI, Waymo, and nuScenes) demonstrates that vQFL maintains accuracy comparable to standard QFL while significantly improving privacy guaranties and communication security. Our implementation using various quantum models (VQC, QCNN, and SamplerQNN) reveals minimal performance overhead despite the added security measures. This work establishes a crucial foundation for quantum-resistant autonomous vehicle systems that can operate securely in the post-quantum era while efficiently processing the massive data volumes (20-40TB/day per vehicle) generated by modern autonomous fleets. The modular design of the framework allows for seamless integration with existing vehicular networks, positioning vQFL as an essential component for future intelligent transportation infrastructure.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.03100v1">Ensemble Privacy Defense for Knowledge-Intensive LLMs against Membership Inference Attacks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-12-01T18:12:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haowei Fu, Bo Ni, Han Xu, Kunpeng Liu, Dan Lin, Tyler Derr</p>
    <p><b>Summary:</b> Retrieval-Augmented Generation (RAG) and Supervised Finetuning (SFT) have become the predominant paradigms for equipping Large Language Models (LLMs) with external knowledge for diverse, knowledge-intensive tasks. However, while such knowledge injection improves performance, it also exposes new attack surfaces. Membership Inference Attacks (MIAs), which aim to determine whether a given data sample was included in a model's training set, pose serious threats to privacy and trust in sensitive domains. To this end, we first systematically evaluate the vulnerability of RAG- and SFT-based LLMs to various MIAs. Then, to address the privacy risk, we further introduce a novel, model-agnostic defense framework, Ensemble Privacy Defense (EPD), which aggregates and evaluates the outputs of a knowledge-injected LLM, a base LLM, and a dedicated judge model to enhance resistance against MIAs. Comprehensive experiments show that, on average, EPD reduces MIA success by up to 27.8\% for SFT and 526.3\% for RAG compared to inference-time baseline, while maintaining answer quality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.01832v1">A Privacy-Preserving Information-Sharing Protocol for Federated Authentication</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-12-01T16:13:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Francesco Buccafurri, Carmen Licciardi</p>
    <p><b>Summary:</b> This paper presents a privacy-preserving protocol for identity registration and information sharing in federated authentication systems. The goal is to enable Identity Providers (IdPs) to detect duplicate or fraudulent identity enrollments without revealing users personal data or enabling cross-domain correlation. The protocol relies on Oblivious Pseudorandom Functions (OPRFs) combined with domain-specific transformations, ensuring that each IdP generates independent pseudonymous identifiers derived from a shared cryptographic service while maintaining full input confidentiality. A central authority maintains a blind registry that records successful and failed identity verifications using only pseudonymous identifiers, allowing global consistency checks without exposing sensitive information or linking users across domains. The proposed construction provides a general and abstract framework suitable for a wide range of federated authentication systems, achieving strong privacy guarantees while supporting effective fraud-prevention mechanisms during identity registration.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.01748v1">SA-ADP: Sensitivity-Aware Adaptive Differential Privacy for Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-12-01T14:50:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stella Etuk, Ashraf Matrawy</p>
    <p><b>Summary:</b> Despite advances in the use of large language models (LLMs) in downstream tasks, their ability to memorize information has raised privacy concerns. Therefore, protecting personally identifiable information (PII) during LLM training remains a fundamental challenge. Conventional methods like Differential Privacy-Stochastic Gradient Descent (DP-SGD) provide robust privacy protection via uniform noising, protecting PII regardless of its distinct sensitivity. This comes at the expense of the model's utility, leading to a trade-off. In this paper, we propose SA-ADP, a sensitivity-aware approach that allocates noise based on the sensitivity of individual PII. We evaluated our method on four datasets (ABCD, CUSTOMERSIM, Wikitext-2, and UNSW-NB15 ). Our results show that SA-ADP achieves results comparable to the baseline (No-DP) and the conventional DP-SGD. This means that our method did not degrade the model's utility while still maintaining strong privacy protection.</p>
  </details>
</div>

