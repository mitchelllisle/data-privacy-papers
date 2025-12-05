
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
  <h3><a href="http://arxiv.org/abs/2512.00307v1">Adversarial Signed Graph Learning with Differential Privacy</a></h3>
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


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.14524v1">Compression with Privacy-Preserving Random Access</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2025-11-18T14:24:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Venkat Chandar, Aslan Tchamkerten, Shashank Vatedka</p>
    <p><b>Summary:</b> It is shown that an i.i.d. binary source sequence $X_1, \ldots, X_n$ can be losslessly compressed at any rate above entropy such that the individual decoding of any $X_i$ reveals \emph{no} information about the other bits $\{X_j : j \neq i\}$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.14084v1">Observational Auditing of Label Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-18T03:12:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Iden Kalemaj, Luca Melis, Maxime Boucher, Ilya Mironov, Saeed Mahloujifar</p>
    <p><b>Summary:</b> Differential privacy (DP) auditing is essential for evaluating privacy guarantees in machine learning systems. Existing auditing methods, however, pose a significant challenge for large-scale systems since they require modifying the training dataset -- for instance, by injecting out-of-distribution canaries or removing samples from training. Such interventions on the training data pipeline are resource-intensive and involve considerable engineering overhead. We introduce a novel observational auditing framework that leverages the inherent randomness of data distributions, enabling privacy evaluation without altering the original dataset. Our approach extends privacy auditing beyond traditional membership inference to protected attributes, with labels as a special case, addressing a key gap in existing techniques. We provide theoretical foundations for our method and perform experiments on Criteo and CIFAR-10 datasets that demonstrate its effectiveness in auditing label privacy guarantees. This work opens new avenues for practical privacy auditing in large-scale production environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.14045v1">GRPO Privacy Is at Risk: A Membership Inference Attack Against Reinforcement Learning With Verifiable Rewards</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-11-18T01:51:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yule Liu, Heyi Zhang, Jinyi Zheng, Zhen Sun, Zifan Peng, Tianshuo Cong, Yilong Yang, Xinlei He, Zhuo Ma</p>
    <p><b>Summary:</b> Membership inference attacks (MIAs) on large language models (LLMs) pose significant privacy risks across various stages of model training. Recent advances in Reinforcement Learning with Verifiable Rewards (RLVR) have brought a profound paradigm shift in LLM training, particularly for complex reasoning tasks. However, the on-policy nature of RLVR introduces a unique privacy leakage pattern: since training relies on self-generated responses without fixed ground-truth outputs, membership inference must now determine whether a given prompt (independent of any specific response) is used during fine-tuning. This creates a threat where leakage arises not from answer memorization.
  To audit this novel privacy risk, we propose Divergence-in-Behavior Attack (DIBA), the first membership inference framework specifically designed for RLVR. DIBA shifts the focus from memorization to behavioral change, leveraging measurable shifts in model behavior across two axes: advantage-side improvement (e.g., correctness gain) and logit-side divergence (e.g., policy drift). Through comprehensive evaluations, we demonstrate that DIBA significantly outperforms existing baselines, achieving around 0.8 AUC and an order-of-magnitude higher TPR@0.1%FPR. We validate DIBA's superiority across multiple settings--including in-distribution, cross-dataset, cross-algorithm, black-box scenarios, and extensions to vision-language models. Furthermore, our attack remains robust under moderate defensive measures.
  To the best of our knowledge, this is the first work to systematically analyze privacy vulnerabilities in RLVR, revealing that even in the absence of explicit supervision, training data exposure can be reliably inferred through behavioral traces.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.13576v1">Exploring the Effectiveness of Google Play Store's Privacy Transparency Channels</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-11-17T16:40:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anhao Xiang, Weiping Pei, Chuan Yue</p>
    <p><b>Summary:</b> With the requirements and emphases on privacy transparency placed by regulations such as GDPR and CCPA, the Google Play Store requires Android developers to more responsibly communicate their apps' privacy practices to potential users by providing the proper information via the data safety, privacy policy, and permission manifest privacy transparency channels. However, it is unclear how effective those channels are in helping users make informed decisions in the app selection and installation process. In this article, we conducted a study for 190 participants to interact with our simulated privacy transparency channels of mobile apps. We quantitatively analyzed (supplemented by qualitative analysis) participants' responses to five sets of questions. We found that data safety provides the most intuitive user interfaces, privacy policy is most informative and effective, while permission manifest excels at raising participants' concerns about an app's overall privacy risks. These channels complement each other and should all be improved.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.13502v1">Tight and Practical Privacy Auditing for Differentially Private In-Context Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-17T15:39:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuyang Xia, Ruixuan Liu, Li Xiong</p>
    <p><b>Summary:</b> Large language models (LLMs) perform in-context learning (ICL) by adapting to tasks from prompt demonstrations, which in practice often contain private or proprietary data. Although differential privacy (DP) with private voting is a pragmatic mitigation, DP-ICL implementations are error-prone, and worst-case DP bounds may substantially overestimate actual leakage, calling for practical auditing tools. We present a tight and efficient privacy auditing framework for DP-ICL systems that runs membership inference attacks and translates their success rates into empirical privacy guarantees using Gaussian DP. Our analysis of the private voting mechanism identifies vote configurations that maximize the auditing signal, guiding the design of audit queries that reliably reveal whether a canary demonstration is present in the context. The framework supports both black-box (API-only) and white-box (internal vote) threat models, and unifies auditing for classification and generation by reducing both to a binary decision problem. Experiments on standard text classification and generation benchmarks show that our empirical leakage estimates closely match theoretical DP budgets on classification tasks and are consistently lower on generation tasks due to conservative embedding-sensitivity bounds, making our framework a practical privacy auditor and verifier for real-world DP-ICL deployments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.13365v1">InfoDecom: Decomposing Information for Defending against Privacy Leakage in Split Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-11-17T13:36:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruijun Deng, Zhihui Lu, Qiang Duan</p>
    <p><b>Summary:</b> Split inference (SI) enables users to access deep learning (DL) services without directly transmitting raw data. However, recent studies reveal that data reconstruction attacks (DRAs) can recover the original inputs from the smashed data sent from the client to the server, leading to significant privacy leakage. While various defenses have been proposed, they often result in substantial utility degradation, particularly when the client-side model is shallow. We identify a key cause of this trade-off: existing defenses apply excessive perturbation to redundant information in the smashed data. To address this issue in computer vision tasks, we propose InfoDecom, a defense framework that first decomposes and removes redundant information and then injects noise calibrated to provide theoretically guaranteed privacy. Experiments demonstrate that InfoDecom achieves a superior utility-privacy trade-off compared to existing baselines. The code and the appendix are available at https://github.com/SASA-cloud/InfoDecom.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.13319v1">Whistledown: Combining User-Level Privacy with Conversational Coherence in LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-11-17T12:56:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chelsea McMurray, Hayder Tirmazi</p>
    <p><b>Summary:</b> Users increasingly rely on large language models (LLMs) for personal, emotionally charged, and socially sensitive conversations. However, prompts sent to cloud-hosted models can contain personally identifiable information (PII) that users do not want logged, retained, or leaked. We observe this to be especially acute when users discuss friends, coworkers, or adversaries, i.e., when they spill the tea. Enterprises face the same challenge when they want to use LLMs for internal communication and decision-making.
  In this whitepaper, we present Whistledown, a best-effort privacy layer that modifies prompts before they are sent to the LLM. Whistledown combines pseudonymization and $ε$-local differential privacy ($ε$-LDP) with transformation caching to provide best-effort privacy protection without sacrificing conversational utility. Whistledown is designed to have low compute and memory overhead, allowing it to be deployed directly on a client's device in the case of individual users. For enterprise users, Whistledown is deployed centrally within a zero-trust gateway that runs on an enterprise's trusted infrastructure. Whistledown requires no changes to the existing APIs of popular LLM providers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.12936v1">Privacy-Preserving Federated Learning from Partial Decryption Verifiable Threshold Multi-Client Functional Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-11-17T03:44:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Minjie Wang, Jinguang Han, Weizhi Meng</p>
    <p><b>Summary:</b> In federated learning, multiple parties can cooperate to train the model without directly exchanging their own private data, but the gradient leakage problem still threatens the privacy security and model integrity. Although the existing scheme uses threshold cryptography to mitigate the inference attack, it can not guarantee the verifiability of the aggregation results, making the system vulnerable to the threat of poisoning attack. We construct a partial decryption verifiable threshold multi client function encryption scheme, and apply it to Federated learning to implement the federated learning verifiable threshold security aggregation protocol (VTSAFL). VTSAFL empowers clients to verify aggregation results, concurrently minimizing both computational and communication overhead. The size of the functional key and partial decryption results of the scheme are constant, which provides efficiency guarantee for large-scale deployment. The experimental results on MNIST dataset show that vtsafl can achieve the same accuracy as the existing scheme, while reducing the total training time by more than 40%, and reducing the communication overhead by up to 50%. This efficiency is critical for overcoming the resource constraints inherent in Internet of Things (IoT) devices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.12841v1">SoK: Synthesizing Smart Home Privacy Protection Mechanisms Across Academic Proposals and Commercial Documentations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-11-17T00:08:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuning Zhang, Yijing Liu, Yuyu Liu, Ying Ma, Shixuan Li, Xin Yi, Qian Wu, Hewu Li</p>
    <p><b>Summary:</b> Pervasive data collection by Smart Home Devices (SHDs) demands robust Privacy Protection Mechanisms (PPMs). The effectiveness of many PPMs, particularly user-facing controls, depends on user awareness and adoption, which are shaped by manufacturers' public documentations. However, the landscape of academic proposals and commercial disclosures remains underexplored. To address this gap, we investigate: (1) What PPMs have academics proposed, and how are these PPMs evaluated? (2) What PPMs do manufacturers document and what factors affect these documentation? To address these questions, we conduct a two-phase study, synthesizing a systematic review of 117 academic papers with an empirical analysis of 86 SHDs' publicly disclosed documentations. Our review of academic literature reveals a strong focus on novel system- and algorithm-based PPMs. However, these proposals neglect deployment barriers (e.g., cost, interoperability), and lack real-world field validation and legal analysis. Concurrently, our analysis of commercial SHDs finds that advanced academic proposals are absent from public discourse. Industry postures are fundamentally reactive, prioritizing compliance via post-hoc data management (e.g., deletion options), rather than the preventative controls favored by academia. The documented protections correspondingly converge on a small set of practical mechanisms, such as physical buttons and localized processing. By synthesizing these findings, we advocate for research to analyze challenges, provide deployable frameworks, real-world field validation, and interoperability solutions to advance practical PPMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.12575v1">Beyond Pixels: Semantic-aware Typographic Attack for Geo-Privacy Protection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-11-16T12:27:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiayi Zhu, Yihao Huang, Yue Cao, Xiaojun Jia, Qing Guo, Felix Juefei-Xu, Geguang Pu, Bin Wang</p>
    <p><b>Summary:</b> Large Visual Language Models (LVLMs) now pose a serious yet overlooked privacy threat, as they can infer a social media user's geolocation directly from shared images, leading to unintended privacy leakage. While adversarial image perturbations provide a potential direction for geo-privacy protection, they require relatively strong distortions to be effective against LVLMs, which noticeably degrade visual quality and diminish an image's value for sharing. To overcome this limitation, we identify typographical attacks as a promising direction for protecting geo-privacy by adding text extension outside the visual content. We further investigate which textual semantics are effective in disrupting geolocation inference and design a two-stage, semantics-aware typographical attack that generates deceptive text to protect user privacy. Extensive experiments across three datasets demonstrate that our approach significantly reduces geolocation prediction accuracy of five state-of-the-art commercial LVLMs, establishing a practical and visually-preserving protection strategy against emerging geo-privacy threats.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.12377v1">On the Security and Privacy of AI-based Mobile Health Chatbots</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-11-15T22:49:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Samuel Wairimu, Leonardo Horn Iwaya</p>
    <p><b>Summary:</b> The rise of Artificial Intelligence (AI) has impacted the development of mobile health (mHealth) apps, most notably with the advent of AI-based chatbots used as ubiquitous ``companions'' for various services, from fitness to mental health assistants. While these mHealth chatbots offer clear benefits, such as personalized health information and predictive diagnoses, they also raise significant concerns regarding security and privacy. This study empirically assesses 16 AI-based mHealth chatbots identified from the Google Play Store. The empirical assessment follows a three-phase approach (manual inspection, static code analysis, and dynamic analysis) to evaluate technical robustness and how design and implementation choices impact end users. Our findings revealed security vulnerabilities (e.g., enabling Remote WebView debugging), privacy issues, and non-compliance with Google Play policies (e.g., failure to provide publicly accessible privacy policies). Based on our findings, we offer several recommendations to enhance the security and privacy of mHealth chatbots. These recommendations focus on improving data handling processes, disclosure, and user security. Therefore, this work also seeks to support mHealth developers and security/privacy engineers in designing more transparent, privacy-friendly, and secure mHealth chatbots.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.12295v1">Privacy-Preserving Prompt Injection Detection for LLMs Using Federated Learning and Embedding-Based NLP Classification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-15T17:11:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hasini Jayathilaka</p>
    <p><b>Summary:</b> Prompt injection attacks are an emerging threat to large language models (LLMs), enabling malicious users to manipulate outputs through carefully designed inputs. Existing detection approaches often require centralizing prompt data, creating significant privacy risks. This paper proposes a privacy-preserving prompt injection detection framework based on federated learning and embedding-based classification. A curated dataset of benign and adversarial prompts was encoded with sentence embedding and used to train both centralized and federated logistic regression models. The federated approach preserved privacy by sharing only model parameters across clients, while achieving detection performance comparable to centralized training. Results demonstrate that effective prompt injection detection is feasible without exposing raw data, making this one of the first explorations of federated security for LLMs. Although the dataset is limited in scale, the findings establish a strong proof-of-concept and highlight new directions for building secure and privacy-aware LLM systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.11811v2">Lessons Learned from Developing a Privacy-Preserving Multimodal Wearable for Local Voice-and-Vision Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">   
  <p><b>Published on:</b> 2025-11-14T19:04:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yonatan Tussa, Andy Heredia, Nirupam Roy</p>
    <p><b>Summary:</b> Many promising applications of multimodal wearables require continuous sensing and heavy computation, yet users reject such devices due to privacy concerns. This paper shares our experiences building an ear-mounted voice-and-vision wearable that performs local AI inference using a paired smartphone as a trusted personal edge. We describe the hardware-software co-design of this privacy-preserving system, including challenges in integrating a camera, microphone, and speaker within a 30-gram form factor, enabling wake word-triggered capture, and running quantized vision-language and large-language models entirely offline. Through iterative prototyping, we identify key design hurdles in power budgeting, connectivity, latency, and social acceptability. Our initial evaluation shows that fully local multimodal inference is feasible on commodity mobile hardware with interactive latency. We conclude with design lessons for researchers developing embedded AI systems that balance privacy, responsiveness, and usability in everyday settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.11347v2">Privacy Challenges and Solutions in Retrieval-Augmented Generation-Enhanced LLMs for Healthcare Chatbots: A Review of Applications, Risks, and Future Directions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-11-14T14:33:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shaowei Guan, Hin Chi Kwok, Ngai Fong Law, Gregor Stiglic, Harry Qin, Vivian Hui</p>
    <p><b>Summary:</b> Retrieval-augmented generation (RAG) has rapidly emerged as a transformative approach for integrating large language models into clinical and biomedical workflows. However, privacy risks, such as protected health information (PHI) exposure, remain inconsistently mitigated. This review provides a thorough analysis of the current landscape of RAG applications in healthcare, including (i) sensitive data type across clinical scenarios, (ii) the associated privacy risks, (iii) current and emerging data-privacy protection mechanisms and (iv) future direction for patient data privacy protection. We synthesize 23 articles on RAG applications in healthcare and systematically analyze privacy challenges through a pipeline-structured framework encompassing data storage, transmission, retrieval and generation stages, delineating potential failure modes, their underlying causes in threat models and system mechanisms, and their practical implications. Building on this analysis, we critically review 17 articles on privacy-preserving strategies for RAG systems. Our evaluation reveals critical gaps, including insufficient clinical validation, absence of standardized evaluation frameworks, and lack of automated assessment tools. We propose actionable directions based on these limitations and conclude with a call to action. This review provides researchers and practitioners with a structured framework for understanding privacy vulnerabilities in healthcare RAG and offers a roadmap toward developing systems that achieve both clinical effectiveness and robust privacy preservation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.11249v1">Bridging Local and Federated Data Normalization in Federated Learning: A Privacy-Preserving Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-14T12:48:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Melih Coşğun, Mert Gençtürk, Sinem Sav</p>
    <p><b>Summary:</b> Data normalization is a crucial preprocessing step for enhancing model performance and training stability. In federated learning (FL), where data remains distributed across multiple parties during collaborative model training, normalization presents unique challenges due to the decentralized and often heterogeneous nature of the data. Traditional methods rely on either independent client-side processing, i.e., local normalization, or normalizing the entire dataset before distributing it to parties, i.e., pooled normalization. Local normalization can be problematic when data distributions across parties are non-IID, while the pooled normalization approach conflicts with the decentralized nature of FL. In this paper, we explore the adaptation of widely used normalization techniques to FL and define the term federated normalization. Federated normalization simulates pooled normalization by enabling the collaborative exchange of normalization parameters among parties. Thus, it achieves performance on par with pooled normalization without compromising data locality. However, sharing normalization parameters such as the mean introduces potential privacy risks, which we further mitigate through a robust privacy-preserving solution. Our contributions include: (i) We systematically evaluate the impact of various federated and local normalization techniques in heterogeneous FL scenarios, (ii) We propose a novel homomorphically encrypted $k$-th ranked element (and median) calculation tailored for the federated setting, enabling secure and efficient federated normalization, (iii) We propose privacy-preserving implementations of widely used normalization techniques for FL, leveraging multiparty fully homomorphic encryption (MHE).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.11209v1">Towards Usable Privacy Management for IoT TAPs: Deriving Privacy Clusters and Preference Profiles</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-11-14T12:08:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Piero Romare, Farzaneh Karegar, Simone Fischer-Hübner</p>
    <p><b>Summary:</b> IoT Trigger-Action Platforms (TAPs) typically offer coarse-grained permission controls. Even when fine-grained controls are available, users are likely overwhelmed by the complexity of setting privacy preferences. This paper contributes to usable privacy management for TAPs by deriving privacy clusters and profiles for different types of users that can be semi-automatically assigned or suggested to them. We developed and validated a questionnaire, based on users' privacy concerns regarding confidentiality and control and their requirements towards transparency in TAPs. In an online study (N=301), where participants were informed about potential privacy risks, we clustered users by their privacy concerns and requirements into Basic, Medium and High Privacy clusters. These clusters were then characterized by the users' data sharing preferences, based on a factorial vignette approach, considering the data categories, the data recipient types, and the purpose of data sharing. Our findings show three distinct privacy profiles, providing a foundation for more usable privacy controls in TAPs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.10771v1">Privacy protection under the exposure of systems' prior information</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2025-11-13T19:47:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Le Liu, Yu Kawano, Ming Cao</p>
    <p><b>Summary:</b> For systems whose states implicate sensitive information, their privacy is of great concern. While notions like differential privacy have been successfully introduced to dynamical systems, it is still unclear how a system's privacy can be properly protected when facing the challenging yet frequently-encountered scenario where an adversary possesses prior knowledge, e.g., the steady state, of the system. This paper presents a new systematic approach to protect the privacy of a discrete-time linear time-invariant system against adversaries knowledgeable of the system's prior information. We employ a tailored \emph{pointwise maximal leakage (PML) privacy} criterion. PML characterizes the worst-case privacy performance, which is sharply different from that of the better-known mutual-information privacy. We derive necessary and sufficient conditions for PML privacy and construct tractable design procedures. Furthermore, our analysis leads to insight into how PML privacy, differential privacy, and mutual-information privacy are related. We then revisit Kalman filters from the perspective of PML privacy and derive a lower bound on the steady-state estimation-error covariance in terms of the PML parameters. Finally, the derived results are illustrated in a case study of privacy protection for distributed sensing in smart buildings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.10516v1">How Worrying Are Privacy Attacks Against Machine Learning?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-13T17:22:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Josep Domingo-Ferrer</p>
    <p><b>Summary:</b> In several jurisdictions, the regulatory framework on the release and sharing of personal data is being extended to machine learning (ML). The implicit assumption is that disclosing a trained ML model entails a privacy risk for any personal data used in training comparable to directly releasing those data. However, given a trained model, it is necessary to mount a privacy attack to make inferences on the training data. In this concept paper, we examine the main families of privacy attacks against predictive and generative ML, including membership inference attacks (MIAs), property inference attacks, and reconstruction attacks. Our discussion shows that most of these attacks seem less effective in the real world than what a prima face interpretation of the related literature could suggest.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.10423v2">Enhanced Privacy Leakage from Noise-Perturbed Gradients via Gradient-Guided Conditional Diffusion Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-13T15:43:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiayang Meng, Tao Huang, Hong Chen, Chen Hou, Guolong Zheng</p>
    <p><b>Summary:</b> Federated learning synchronizes models through gradient transmission and aggregation. However, these gradients pose significant privacy risks, as sensitive training data is embedded within them. Existing gradient inversion attacks suffer from significantly degraded reconstruction performance when gradients are perturbed by noise-a common defense mechanism. In this paper, we introduce gradient-guided conditional diffusion models for reconstructing private images from leaked gradients, without prior knowledge of the target data distribution. Our approach leverages the inherent denoising capability of diffusion models to circumvent the partial protection offered by noise perturbation, thereby improving attack performance under such defenses. We further provide a theoretical analysis of the reconstruction error bounds and the convergence properties of the attack loss, characterizing the impact of key factors-such as noise magnitude and attacked model architecture-on reconstruction quality. Extensive experiments demonstrate our attack's superior reconstruction performance with Gaussian noise-perturbed gradients, and confirm our theoretical findings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.10284v1">Beyond Verification: Abductive Explanations for Post-AI Assessment of Privacy Leakage</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-11-13T13:14:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Belona Sonna, Alban Grastien, Claire Benn</p>
    <p><b>Summary:</b> Privacy leakage in AI-based decision processes poses significant risks, particularly when sensitive information can be inferred. We propose a formal framework to audit privacy leakage using abductive explanations, which identifies minimal sufficient evidence justifying model decisions and determines whether sensitive information disclosed. Our framework formalizes both individual and system-level leakage, introducing the notion of Potentially Applicable Explanations (PAE) to identify individuals whose outcomes can shield those with sensitive features. This approach provides rigorous privacy guarantees while producing human understandable explanations, a key requirement for auditing tools. Experimental evaluation on the German Credit Dataset illustrates how the importance of sensitive literal in the model decision process affects privacy leakage. Despite computational challenges and simplifying assumptions, our results demonstrate that abductive reasoning enables interpretable privacy auditing, offering a practical pathway to reconcile transparency, model interpretability, and privacy preserving in AI decision-making.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.10226v1">Privacy Structure and Blackwell Frontier</a></h3>
  
  <p><b>Published on:</b> 2025-11-13T11:56:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhang Xu, Wei Zhao</p>
    <p><b>Summary:</b> This paper characterizes the set of feasible posterior distributions subject to graph-based inferential privacy constraint, including both differential and inferential privacy. This characterization can be done through enumerating all extreme points of the feasible posterior set. A connection between extreme posteriors and strongly connected semi-chains is then established. All these semi-chains can be constructed through successive unfolding operations on semi-chains with two partitions, which can be constructed through classical spanning tree algorithm. A sharper characterization of semi-chains with two partitions for differential privacy is provided.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.10001v1">Mailing address aliasing as a method to protect consumer privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-11-13T06:12:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Greg Hather, Daniel Aranki</p>
    <p><b>Summary:</b> During online commerce, a customer will typically share his or her mailing address with a merchant to allow product delivery. This creates privacy risks for the customer, where the information may be misused, sold, or leaked by multiple merchants. While physical and virtual PO boxes can reduce the privacy risk, these solutions have associated costs that prevent greater adoption. Here, we introduce the concept of mailing address aliasing, which may offer lower cost and greater control in some cases. With this approach, an alias address is created that maps to the customer's true address. The mapping is kept private from the merchant but shared with the carrier. We discuss the advantages and disadvantages of this approach compared with traditional methods for mailing address privacy. We find that mailing address aliasing is likely to reduce unsolicited mail to a greater extent than physical or virtual PO boxes. However, mailing address aliasing may not be compatible with all merchants' ordering systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.09882v1">Truth, Justice, and Secrecy: Cake Cutting Under Privacy Constraints</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2025-11-13T02:28:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yaron Salman, Tamir Tassa, Omer Lev, Roie Zivan</p>
    <p><b>Summary:</b> Cake-cutting algorithms, which aim to fairly allocate a continuous resource based on individual agent preferences, have seen significant progress over the past two decades. Much of the research has concentrated on fairness, with comparatively less attention given to other important aspects. Chen et al. (2010) introduced an algorithm that, in addition to ensuring fairness, was strategyproof -- meaning agents had no incentive to misreport their valuations. However, even in the absence of strategic incentives to misreport, agents may still hesitate to reveal their true preferences due to privacy concerns (e.g., when allocating advertising time between firms, revealing preferences could inadvertently expose planned marketing strategies or product launch timelines). In this work, we extend the strategyproof algorithm of Chen et al. by introducing a privacy-preserving dimension. To the best of our knowledge, we present the first private cake-cutting protocol, and, in addition, this protocol is also envy-free and strategyproof. Our approach replaces the algorithm's centralized computation with a novel adaptation of cryptographic techniques, enabling privacy without compromising fairness or strategyproofness. Thus, our protocol encourages agents to report their true preferences not only because they are not incentivized to lie, but also because they are protected from having their preferences exposed.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.09846v1">Real-Time Lightweight Gaze Privacy-Preservation Techniques Validated via Offline Gaze-Based Interaction Simulation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-13T01:01:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mehedi Hasan Raju, Oleg V. Komogortsev</p>
    <p><b>Summary:</b> This study examines the effectiveness of the real-time privacy-preserving techniques through an offline gaze-based interaction simulation framework. Those techniques aim to reduce the amount of identity-related information in eye-tracking data while improving the efficacy of the gaze-based interaction. Although some real-time gaze privatization methods were previously explored, their validation on the large dataset was not conducted. We propose a functional framework that allows to study the efficacy of real-time gaze privatization on an already collected offline dataset. The key metric used to assess the reduction of identity-related information is the identification rate, while improvements in gaze-based interactions are evaluated through signal quality during interaction. Our additional contribution is the employment of an extremely lightweight Kalman filter framework that reduces the amount of identity-related information in the gaze signal and improves gaze-based interaction performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.09775v1">Privacy-Preserving Explainable AIoT Application via SHAP Entropy Regularization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2025-11-12T22:13:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dilli Prasad Sharma, Xiaowei Sun, Liang Xue, Xiaodong Lin, Pulei Xiong</p>
    <p><b>Summary:</b> The widespread integration of Artificial Intelligence of Things (AIoT) in smart home environments has amplified the demand for transparent and interpretable machine learning models. To foster user trust and comply with emerging regulatory frameworks, the Explainable AI (XAI) methods, particularly post-hoc techniques such as SHapley Additive exPlanations (SHAP), and Local Interpretable Model-Agnostic Explanations (LIME), are widely employed to elucidate model behavior. However, recent studies have shown that these explanation methods can inadvertently expose sensitive user attributes and behavioral patterns, thereby introducing new privacy risks. To address these concerns, we propose a novel privacy-preserving approach based on SHAP entropy regularization to mitigate privacy leakage in explainable AIoT applications. Our method incorporates an entropy-based regularization objective that penalizes low-entropy SHAP attribution distributions during training, promoting a more uniform spread of feature contributions. To evaluate the effectiveness of our approach, we developed a suite of SHAP-based privacy attacks that strategically leverage model explanation outputs to infer sensitive information. We validate our method through comparative evaluations using these attacks alongside utility metrics on benchmark smart home energy consumption datasets. Experimental results demonstrate that SHAP entropy regularization substantially reduces privacy leakage compared to baseline models, while maintaining high predictive accuracy and faithful explanation fidelity. This work contributes to the development of privacy-preserving explainable AI techniques for secure and trustworthy AIoT applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.09696v1">Cooperative Local Differential Privacy: Securing Time Series Data in Distributed Environments</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-12T19:52:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bikash Chandra Singh, Md Jakir Hossain, Rafael Diaz, Sandip Roy, Ravi Mukkamala, Sachin Shetty</p>
    <p><b>Summary:</b> The rapid growth of smart devices such as phones, wearables, IoT sensors, and connected vehicles has led to an explosion of continuous time series data that offers valuable insights in healthcare, transportation, and more. However, this surge raises significant privacy concerns, as sensitive patterns can reveal personal details. While traditional differential privacy (DP) relies on trusted servers, local differential privacy (LDP) enables users to perturb their own data. However, traditional LDP methods perturb time series data by adding user-specific noise but exhibit vulnerabilities. For instance, noise applied within fixed time windows can be canceled during aggregation (e.g., averaging), enabling adversaries to infer individual statistics over time, thereby eroding privacy guarantees.
  To address these issues, we introduce a Cooperative Local Differential Privacy (CLDP) mechanism that enhances privacy by distributing noise vectors across multiple users. In our approach, noise is collaboratively generated and assigned so that when all users' perturbed data is aggregated, the noise cancels out preserving overall statistical properties while protecting individual privacy. This cooperative strategy not only counters vulnerabilities inherent in time-window-based methods but also scales effectively for large, real-time datasets, striking a better balance between data utility and privacy in multiuser environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.09400v1">Abstract Gradient Training: A Unified Certification Framework for Data Poisoning, Unlearning, and Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-11-12T15:15:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Philip Sosnin, Matthew Wicker, Josh Collyer, Calvin Tsay</p>
    <p><b>Summary:</b> The impact of inference-time data perturbation (e.g., adversarial attacks) has been extensively studied in machine learning, leading to well-established certification techniques for adversarial robustness. In contrast, certifying models against training data perturbations remains a relatively under-explored area. These perturbations can arise in three critical contexts: adversarial data poisoning, where an adversary manipulates training samples to corrupt model performance; machine unlearning, which requires certifying model behavior under the removal of specific training data; and differential privacy, where guarantees must be given with respect to substituting individual data points. This work introduces Abstract Gradient Training (AGT), a unified framework for certifying robustness of a given model and training procedure to training data perturbations, including bounded perturbations, the removal of data points, and the addition of new samples. By bounding the reachable set of parameters, i.e., establishing provable parameter-space bounds, AGT provides a formal approach to analyzing the behavior of models trained via first-order optimization methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.09094v1">RIS-based Communication Enhancement and Location Privacy Protection in UAV Networks</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2025-11-12T08:10:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ziqi Chen, Jun Du, Chunxiao Jiang, Tony Q. S. Quek, Zhu Han</p>
    <p><b>Summary:</b> With the explosive advancement of unmanned aerial vehicles (UAVs), the security of efficient UAV networks has become increasingly critical. Owing to the open nature of its communication environment, illegitimate malicious UAVs (MUs) can infer the position of the source UAV (SU) by analyzing received signals, thus compromising the SU location privacy. To protect the SU location privacy while ensuring efficient communication with legitimate receiving UAVs (RUs), we propose an Active Reconfigurable Intelligent Surface (ARIS)-assisted covert communication scheme based on virtual partitioning and artificial noise (AN). Specifically, we design a novel ARIS architecture integrated with an AN module. This architecture dynamically partitions its reflecting elements into multiple sub-regions: one subset is optimized to enhance the communication rate between the SU and RUs, while the other subset generates AN to interfere with the localization of the SU by MUs. We first derive the Cramér-Rao Lower Bound (CRLB) for the localization with received signal strength (RSS), based on which, we establish a joint optimization framework for communication enhancement and localization interference. Subsequently, we derive and validate the optimal ARIS partitioning and power allocation under average channel conditions. Finally, tailored optimization methods are proposed for the reflection precoding and AN design of the two partitions. Simulation results validate that, compared to baseline schemes, the proposed scheme significantly increases the localization error of the SU by MUs while maintaining efficient communication between the SU and RUs, thereby effectively protecting the SU location privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.09043v1">MedHE: Communication-Efficient Privacy-Preserving Federated Learning with Adaptive Gradient Sparsification for Healthcare</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-11-12T06:50:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Farjana Yesmin</p>
    <p><b>Summary:</b> Healthcare federated learning requires strong privacy guarantees while maintaining computational efficiency across resource-constrained medical institutions. This paper presents MedHE, a novel framework combining adaptive gradient sparsification with CKKS homomorphic encryption to enable privacy-preserving collaborative learning on sensitive medical data. Our approach introduces a dynamic threshold mechanism with error compensation for top-k gradient selection, achieving 97.5 percent communication reduction while preserving model utility. We provide formal security analysis under Ring Learning with Errors assumptions and demonstrate differential privacy guarantees with epsilon less than or equal to 1.0. Statistical testing across 5 independent trials shows MedHE achieves 89.5 percent plus or minus 0.8 percent accuracy, maintaining comparable performance to standard federated learning (p=0.32) while reducing communication from 1277 MB to 32 MB per training round. Comprehensive evaluation demonstrates practical feasibility for real-world medical deployments with HIPAA compliance and scalability to 100 plus institutions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.08998v1">Experiences Building Enterprise-Level Privacy-Preserving Federated Learning to Power AI for Science</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-11-12T05:39:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zilinghan Li, Aditya Sinha, Yijiang Li, Kyle Chard, Kibaek Kim, Ravi Madduri</p>
    <p><b>Summary:</b> Federated learning (FL) is a promising approach to enabling collaborative model training without centralized data sharing, a crucial requirement in scientific domains where data privacy, ownership, and compliance constraints are critical. However, building user-friendly enterprise-level FL frameworks that are both scalable and privacy-preserving remains challenging, especially when bridging the gap between local prototyping and distributed deployment across heterogeneous client computing infrastructures. In this paper, based on our experiences building the Advanced Privacy-Preserving Federated Learning (APPFL) framework, we present our vision for an enterprise-grade, privacy-preserving FL framework designed to scale seamlessly across computing environments. We identify several key capabilities that such a framework must provide: (1) Scalable local simulation and prototyping to accelerate experimentation and algorithm design; (2) seamless transition from simulation to deployment; (3) distributed deployment across diverse, real-world infrastructures, from personal devices to cloud clusters and HPC systems; (4) multi-level abstractions that balance ease of use and research flexibility; and (5) comprehensive privacy and security through techniques such as differential privacy, secure aggregation, robust authentication, and confidential computing. We further discuss architectural designs to realize these goals. This framework aims to bridge the gap between research prototypes and enterprise-scale deployment, enabling scalable, reliable, and privacy-preserving AI for science.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.08666v1">Privacy Beyond Pixels: Latent Anonymization for Privacy-Preserving Video Understanding</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-11-11T18:56:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joseph Fioresi, Ishan Rajendrakumar Dave, Mubarak Shah</p>
    <p><b>Summary:</b> We introduce a novel formulation of visual privacy preservation for video foundation models that operates entirely in the latent space. While spatio-temporal features learned by foundation models have deepened general understanding of video content, sharing or storing these extracted visual features for downstream tasks inadvertently reveals sensitive personal information like skin color, gender, or clothing. Current privacy preservation methods focus on input-pixel-level anonymization, which requires retraining the entire utility video model and results in task-specific anonymization, making them unsuitable for recent video foundational models. To address these challenges, we introduce a lightweight Anonymizing Adapter Module (AAM) that removes private information from video features while retaining general task utility. AAM can be applied in a plug-and-play fashion to frozen video encoders, minimizing the computational burden of finetuning and re-extracting features. Our framework employs three newly designed training objectives: (1) a clip-level self-supervised privacy objective to reduce mutual information between static clips, (2) a co-training objective to retain utility across seen tasks, and (3) a latent consistency loss for generalization on unseen tasks. Our extensive evaluations demonstrate a significant 35% reduction in privacy leakage while maintaining near-baseline utility performance across various downstream tasks: Action Recognition (Kinetics400, UCF101, HMDB51), Temporal Action Detection (THUMOS14), and Anomaly Detection (UCF-Crime). We also provide an analysis on anonymization for sensitive temporal attribute recognition. Additionally, we propose new protocols for assessing gender bias in action recognition models, showing that our method effectively mitigates such biases and promotes more equitable video understanding.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.08059v1">"I need to learn better searching tactics for privacy policy laws.'' Investigating Software Developers' Behavior When Using Sources on Privacy Issues</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-11-11T09:58:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stefan Albert Horstmann, Sandy Hong, Maziar Niazian, Cristiana Santos, Alena Naiakshina</p>
    <p><b>Summary:</b> Since the introduction of the European General Data Protection Regulation (GDPR) and the California Consumer Privacy Act (CCPA), software developers increasingly have to make privacy-related decisions during system design and implementation. However, past research showed that they often lack legal expertise and struggle with privacy-compliant development. To shed light on how effective current information sources are in supporting them with privacy-sensitive implementation, we conducted a qualitative study with 30 developers. Participants were presented with a privacy-sensitive scenario and asked to identify privacy issues and suggest measures using their knowledge, online resources, and an AI assistant. We observed developers' decision-making in think-aloud sessions and discussed it in follow-up interviews. We found that participants struggled with all three sources: personal knowledge was insufficient, web content was often too complex, and while AI assistants provided clear and user-tailored responses, they lacked contextual relevance and failed to identify scenario-specific issues. Our study highlights major shortcomings in existing support for privacy-related development tasks. Based on our findings, we discuss the need for more accessible, understandable, and actionable privacy resources for developers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.07818v1">Blockchain-Integrated Privacy-Preserving Medical Insurance Claim Processing Using Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-11T04:22:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Diya Mamoria, Harshit Jain, Aswani Kumar Cherukuri</p>
    <p><b>Summary:</b> This research proposes a decentralized and cryptographically secure framework to address the most acute issues of privacy, data security, and protection in the ecosystem of medical insurance claim processing. The scope of this study focuses on enabling the management of insurance claims in a transparent, privacy-protecting manner while maintaining the efficiency and trust level needed by the patients, healthcare providers, and insurers. To accomplish this, the proposed system adds blockchain technology to provide an unchangeable, decentralized, and auditable claim transactions ledger which enhances overall claim-related processes and trust among all stakeholders. To protect critical patient information, the framework employs homomorphic encryption a modern form of cryptography to allow authorized insurance providers to perform necessary operations like claim adjudication and reimbursement on encrypted medical records without any decryption during the process. This method significantly reduces the third-party processing privacy risk because patient data can be kept secret even when third-party processing is done. In addition, smart contracts improve automation of the most important procedures in the claim processing pipeline, which decreases manual, operational, and susceptibility towards human blunders or deceitful acts. The integration of these two transformative technologiesblockchain and homomorphic encryption represents the core contribution of this work, enabling the coexistence of transparency and privacy which are usually viewed as competing objectives in traditional systems. As a result, these technologies are expected to foster the creation of a reliable, effective, and privacy safeguarding architecture that could transform the medical claim submission systems paradigm.</p>
  </details>
</div>



<h2>2025-12</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.05065v1">Personalizing Agent Privacy Decisions via Logical Entailment</a></h3>
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
  <h3><a href="http://arxiv.org/abs/2512.04316v1">ConsentDiff at Scale: Longitudinal Audits of Web Privacy Policy Changes and UI Frictions</a></h3>
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

