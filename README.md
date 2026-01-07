
<h2>2025-12</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.24899v1">MTSP-LDP: A Framework for Multi-Task Streaming Data Publication under Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-12-31T14:52:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chang Liu, Junzhou Zhao</p>
    <p><b>Summary:</b> The proliferation of streaming data analytics in data-driven applications raises critical privacy concerns, as directly collecting user data may compromise personal privacy. Although existing $w$-event local differential privacy (LDP) mechanisms provide formal guarantees without relying on trusted third parties, their practical deployment is hindered by two key limitations. First, these methods are designed primarily for publishing simple statistics at each timestamp, making them inherently unsuitable for complex queries. Second, they handle data at each timestamp independently, failing to capture temporal correlations and consequently degrading the overall utility. To address these issues, we propose MTSP-LDP, a novel framework for \textbf{M}ulti-\textbf{T}ask \textbf{S}treaming data \textbf{P}ublication under $w$-event LDP. MTSP-LDP adopts an \emph{Optimal Privacy Budget Allocation} algorithm to dynamically allocate privacy budgets by analyzing temporal correlations within each window. It then constructs a \emph{data-adaptive private binary tree structure} to support complex queries, which is further refined by cross-timestamp grouping and smoothing operations to enhance estimation accuracy. Furthermore, a unified \emph{Budget-Free Multi-Task Processing} mechanism is introduced to support a variety of streaming queries without consuming additional privacy budget. Extensive experiments on real-world datasets demonstrate that MTSP-LDP consistently achieves high utility across various streaming tasks, significantly outperforming existing methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.24848v1">PrivacyBench: A Conversational Benchmark for Evaluating Privacy in Personalized AI</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-12-31T13:16:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Srija Mukhopadhyay, Sathwik Reddy, Shruthi Muthukumar, Jisun An, Ponnurangam Kumaraguru</p>
    <p><b>Summary:</b> Personalized AI agents rely on access to a user's digital footprint, which often includes sensitive data from private emails, chats and purchase histories. Yet this access creates a fundamental societal and privacy risk: systems lacking social-context awareness can unintentionally expose user secrets, threatening digital well-being. We introduce PrivacyBench, a benchmark with socially grounded datasets containing embedded secrets and a multi-turn conversational evaluation to measure secret preservation. Testing Retrieval-Augmented Generation (RAG) assistants reveals that they leak secrets in up to 26.56% of interactions. A privacy-aware prompt lowers leakage to 5.12%, yet this measure offers only partial mitigation. The retrieval mechanism continues to access sensitive data indiscriminately, which shifts the entire burden of privacy preservation onto the generator. This creates a single point of failure, rendering current architectures unsafe for wide-scale deployment. Our findings underscore the urgent need for structural, privacy-by-design safeguards to ensure an ethical and inclusive web for everyone.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.24452v1">Privacy-Preserving Semantic Communications via Multi-Task Learning and Adversarial Perturbations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-12-30T20:19:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yalin E. Sagduyu, Tugba Erpek, Aylin Yener, Sennur Ulukus</p>
    <p><b>Summary:</b> Semantic communications conveys task-relevant meaning rather than focusing solely on message reconstruction, improving bandwidth efficiency and robustness for next-generation wireless systems. However, learned semantic representations can still leak sensitive information to unintended receivers (eavesdroppers). This paper presents a deep learning-based semantic communication framework that jointly supports multiple receiver tasks while explicitly limiting semantic leakage to an eavesdropper. The legitimate link employs a learned encoder at the transmitter, while the receiver trains decoders for semantic inference and data reconstruction. The security problem is formulated via an iterative min-max optimization in which an eavesdropper is trained to improve its semantic inference, while the legitimate transmitter-receiver pair is trained to preserve task performance while reducing the eavesdropper's success. We also introduce an auxiliary layer that superimposes a cooperative, adversarially crafted perturbation on the transmitted waveform to degrade semantic leakage to an eavesdropper. Performance is evaluated over Rayleigh fading channels with additive white Gaussian noise using MNIST and CIFAR-10 datasets. Semantic accuracy and reconstruction quality improve with increasing latent dimension, while the min-max mechanism reduces the eavesdropper's inference performance significantly without degrading the legitimate receiver. The perturbation layer is successful in reducing semantic leakage even when the legitimate link is trained only for its own task. This comprehensive framework motivates semantic communication designs with tunable, end-to-end privacy against adaptive adversaries in realistic wireless settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.24041v1">Exposed: Shedding Blacklight on Online Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-12-30T07:31:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lucas Shen, Gaurav Sood</p>
    <p><b>Summary:</b> To what extent are users surveilled on the web, by what technologies, and by whom? We answer these questions by combining passively observed, anonymized browsing data of a large, representative sample of Americans with domain-level data on tracking from Blacklight. We find that nearly all users ($ > 99\%$) encounter at least one ad tracker or third-party cookie over the observation window. More invasive techniques like session recording, keylogging, and canvas fingerprinting are less widespread, but over half of the users visited a site employing at least one of these within the first 48 hours of the start of tracking. Linking trackers to their parent organizations reveals that a single organization, usually Google, can track over $50\%$ of web activity of more than half the users. Demographic differences in exposure are modest and often attenuate when we account for browsing volume. However, disparities by age and race remain, suggesting that what users browse, not just how much, shapes their surveillance risk.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.23535v1">A Privacy Protocol Using Ephemeral Intermediaries and a Rank-Deficient Matrix Power Function (RDMPF)</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2025-12-29T15:19:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Eduardo Salazar</p>
    <p><b>Summary:</b> This paper presents a private transfer architecture for the Internet Computer (ICP) that decouples deposit and retrieval through two short-lived intermediaries, with sealed storage and attested teardown by an ephemeral witness. The protocol uses a non-interactive RDMPF-based encapsulation to derive per-transfer transport keys. A public notice hint is computed from the capsule to enable discovery without fingerprinting the recipient's key. Retrieval is authorized by a short proof of decapsulation that reveals no identities. All transaction intermediaries are ephemeral and issue certified destruction intents and proofs, allowing a noticeboard to publish auditable finalization records. The design provides sender identity privacy with respect to the recipient, content confidentiality against intermediaries, forward secrecy for transport keys after staged destruction, verifiable liveness and finality. We formalize the basic interfaces, provide the security arguments for encapsulation correctness, hint privacy, authorization soundness and timeout reclaim.
  In terms of implementation, it has been recently brought into production on the ICP under the name ICPP. It has been subject to exhaustive testing and incorporates a few enhancements, focusing on the operational possibilities offered by ICP's technology. This work hence serves as a broad reference for the protocol now publicly accessible.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.23235v1">FairGFL: Privacy-Preserving Fairness-Aware Federated Learning with Overlapping Subgraphs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-12-29T06:31:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zihao Zhou, Shusen Yang, Fangyuan Zhao, Xuebin Ren</p>
    <p><b>Summary:</b> Graph federated learning enables the collaborative extraction of high-order information from distributed subgraphs while preserving the privacy of raw data. However, graph data often exhibits overlap among different clients. Previous research has demonstrated certain benefits of overlapping data in mitigating data heterogeneity. However, the negative effects have not been explored, particularly in cases where the overlaps are imbalanced across clients. In this paper, we uncover the unfairness issue arising from imbalanced overlapping subgraphs through both empirical observations and theoretical reasoning. To address this issue, we propose FairGFL (FAIRness-aware subGraph Federated Learning), a novel algorithm that enhances cross-client fairness while maintaining model utility in a privacy-preserving manner. Specifically, FairGFL incorporates an interpretable weighted aggregation approach to enhance fairness across clients, leveraging privacy-preserving estimation of their overlapping ratios. Furthermore, FairGFL improves the tradeoff between model utility and fairness by integrating a carefully crafted regularizer into the federated composite loss function. Through extensive experiments on four benchmark graph datasets, we demonstrate that FairGFL outperforms four representative baseline algorithms in terms of both model utility and fairness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.22307v1">LLA: Enhancing Security and Privacy for Generative Models with Logic-Locked Accelerators</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-12-26T05:47:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> You Li, Guannan Zhao, Yuhao Ju, Yunqi He, Jie Gu, Hai Zhou</p>
    <p><b>Summary:</b> We introduce LLA, an effective intellectual property (IP) protection scheme for generative AI models. LLA leverages the synergy between hardware and software to defend against various supply chain threats, including model theft, model corruption, and information leakage. On the software side, it embeds key bits into neurons that can trigger outliers to degrade performance and applies invariance transformations to obscure the key values. On the hardware side, it integrates a lightweight locking module into the AI accelerator while maintaining compatibility with various dataflow patterns and toolchains. An accelerator with a pre-stored secret key acts as a license to access the model services provided by the IP owner. The evaluation results show that LLA can withstand a broad range of oracle-guided key optimization attacks, while incurring a minimal computational overhead of less than 0.1% for 7,168 key bits.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.23743v1">Hybrid-Code: A Privacy-Preserving, Redundant Multi-Agent Framework for Reliable Local Clinical Coding</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-12-26T02:27:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yunguo Yu</p>
    <p><b>Summary:</b> Clinical coding automation using cloud-based Large Language Models (LLMs) poses privacy risks and latency bottlenecks, rendering them unsuitable for on-premise healthcare deployment. We introduce Hybrid-Code, a hybrid neuro-symbolic multi-agent framework for local clinical coding that ensures production reliability through redundancy and verification. Our system comprises two agents: a Coder that attempts language model-based semantic reasoning using BioMistral-7B but falls back to deterministic keyword matching when model output is unreliable, ensuring pipeline completion; and an Auditor that verifies codes against a 257-code knowledge base and clinical evidence. Evaluating on 1,000 MIMIC-III discharge summaries, we demonstrate no hallucinated codes among accepted outputs within the knowledge base, 24.47% verification rate, and 34.11% coverage (95% CI: 31.2%--37.0%) with 86%+ language model utilization. The Auditor filtered invalid format codes and provided evidence-based quality control (75.53% rejection rate) while ensuring no patient data leaves the hospital firewall. The hybrid architecture -- combining language model semantic understanding (when successful), deterministic fallback (when the model fails), and symbolic verification (always active) -- ensures both reliability and privacy preservation, addressing critical barriers to AI adoption in healthcare. Our key finding is that reliability through redundancy is more valuable than pure model performance in production healthcare systems, where system failures are unacceptable.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.21700v1">Inference in the $p_0$ model for directed networks under local differential privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">  
  <p><b>Published on:</b> 2025-12-25T14:51:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xueying Sun, Ting Yan, Binyan Jiang</p>
    <p><b>Summary:</b> We explore the edge-flipping mechanism, a type of input perturbation, to release the directed graph under edge-local differential privacy. By using the noisy bi-degree sequence from the output graph, we construct the moment equations to estimate the unknown parameters in the $p_0$ model, which is an exponential family distribution with the bi-degree sequence as the natural sufficient statistic. We show that the resulting private estimator is asymptotically consistent and normally distributed under some conditions. In addition, we compare the performance of input and output perturbation mechanisms for releasing bi-degree sequences in terms of parameter estimation accuracy and privacy protection. Numerical studies demonstrate our theoretical findings and compare the performance of the private estimates obtained by different types of perturbation methods. We apply the proposed method to analyze the UC Irvine message network.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.21048v1">zkFL-Health: Blockchain-Enabled Zero-Knowledge Federated Learning for Medical AI Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-12-24T08:29:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Savvy Sharma, George Petrovic, Sarthak Kaushik</p>
    <p><b>Summary:</b> Healthcare AI needs large, diverse datasets, yet strict privacy and governance constraints prevent raw data sharing across institutions. Federated learning (FL) mitigates this by training where data reside and exchanging only model updates, but practical deployments still face two core risks: (1) privacy leakage via gradients or updates (membership inference, gradient inversion) and (2) trust in the aggregator, a single point of failure that can drop, alter, or inject contributions undetected. We present zkFL-Health, an architecture that combines FL with zero-knowledge proofs (ZKPs) and Trusted Execution Environments (TEEs) to deliver privacy-preserving, verifiably correct collaborative training for medical AI. Clients locally train and commit their updates; the aggregator operates within a TEE to compute the global update and produces a succinct ZK proof (via Halo2/Nova) that it used exactly the committed inputs and the correct aggregation rule, without revealing any client update to the host. Verifier nodes validate the proof and record cryptographic commitments on-chain, providing an immutable audit trail and removing the need to trust any single party. We outline system and threat models tailored to healthcare, the zkFL-Health protocol, security/privacy guarantees, and a performance evaluation plan spanning accuracy, privacy risk, latency, and cost. This framework enables multi-institutional medical AI with strong confidentiality, integrity, and auditability, key properties for clinical adoption and regulatory compliance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.20814v1">FedMPDD: Communication-Efficient Federated Learning with Privacy Preservation Attributes via Projected Directional Derivative</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-12-23T22:25:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohammadreza Rostami, Solmaz S. Kia</p>
    <p><b>Summary:</b> This paper introduces \texttt{FedMPDD} (\textbf{Fed}erated Learning via \textbf{M}ulti-\textbf{P}rojected \textbf{D}irectional \textbf{D}erivatives), a novel algorithm that simultaneously optimizes bandwidth utilization and enhances privacy in Federated Learning. The core idea of \texttt{FedMPDD} is to encode each client's high-dimensional gradient by computing its directional derivatives along multiple random vectors. This compresses the gradient into a much smaller message, significantly reducing uplink communication costs from $\mathcal{O}(d)$ to $\mathcal{O}(m)$, where $m \ll d$. The server then decodes the aggregated information by projecting it back onto the same random vectors. Our key insight is that averaging multiple projections overcomes the dimension-dependent convergence limitations of a single projection. We provide a rigorous theoretical analysis, establishing that \texttt{FedMPDD} converges at a rate of $\mathcal{O}(1/\sqrt{K})$, matching the performance of FedSGD. Furthermore, we demonstrate that our method provides some inherent privacy against gradient inversion attacks due to the geometric properties of low-rank projections, offering a tunable privacy-utility trade-off controlled by the number of projections. Extensive experiments on benchmark datasets validate our theory and demonstrates our results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.20323v3">Differentially Private Feature Release for Wireless Sensing: Adaptive Privacy Budget Allocation on CSI Spectrograms</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-12-23T12:45:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ipek Sena Yilmaz, Onur G. Tuncer, Zeynep E. Aksoy, Zeynep Yağmur Baydemir</p>
    <p><b>Summary:</b> Wi-Fi/RF-based human sensing has achieved remarkable progress with deep learning, yet practical deployments increasingly require feature sharing for cloud analytics, collaborative training, or benchmark evaluation. Releasing intermediate representations such as CSI spectrograms can inadvertently expose sensitive information, including user identity, location, and membership, motivating formal privacy guarantees. In this paper, we study differentially private (DP) feature release for wireless sensing and propose an adaptive privacy budget allocation mechanism tailored to the highly non-uniform structure of CSI time-frequency representations. Our pipeline converts CSI to bounded spectrogram features, applies sensitivity control via clipping, estimates task-relevant importance over the time-frequency plane, and allocates a global privacy budget across spectrogram blocks before injecting calibrated Gaussian noise. Experiments on multi-user activity sensing (WiMANS), multi-person 3D pose estimation (Person-in-WiFi 3D), and respiration monitoring (Resp-CSI) show that adaptive allocation consistently improves the privacy-utility frontier over uniform perturbation under the same privacy budget. Our method yields higher accuracy and lower error while substantially reducing empirical leakage in identity and membership inference attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.20234v1">Achieving Flexible and Secure Authentication with Strong Privacy in Decentralized Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-12-23T10:49:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bin Xie, Rui Song, Xuyuan Cai</p>
    <p><b>Summary:</b> Anonymous credentials (ACs) are a crucial cryptographic tool for privacy-preserving authentication in decentralized networks, allowing holders to prove eligibility without revealing their identity. However, a major limitation of standard ACs is the disclosure of the issuer's identity, which can leak sensitive contextual information about the holder. Issuer-hiding ACs address this by making a credential's origin indistinguishable among a set of approved issuers. Despite this advancement, existing solutions suffer from practical limitations that hinder their deployment in decentralized environments: unflexible credential models that restrict issuer and holder autonomy, flawed revocation mechanisms that compromise security, and weak attribute hiding that fails to meet data minimization principles. This paper introduces a new scheme called IRAC to overcome these challenges. We propose a flexible credential model that employs vector commitments with a padding strategy to unify credentials from heterogeneous issuers, enabling privacy-preserving authentication without enforcing a global static attribute set or verifier-defined policies. Furthermore, we design a secure decentralized revocation mechanism where holders prove non-revocation by demonstrating their credential's hash lies within a gap in the issuer's sorted revocation list, effectively decoupling revocation checks from verifier policies while maintaining issuer anonymity. IRAC also strengthens attribute hiding by utilizing zk-SNARKs and vector commitments, allowing holders to prove statements about their attributes without disclosing the attributes themselves or the credential structure. Security analysis and performance evaluations demonstrate its practical feasibility for decentralized networks, where presenting a credential can be finished in 1s.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.21358v1">Composition Theorems for f-Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2025-12-23T08:21:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Natasha Fernandes, Annabelle McIver, Parastoo Sadeghi</p>
    <p><b>Summary:</b> "f differential privacy" (fDP) is a recent definition for privacy privacy which can offer improved predictions of "privacy loss". It has been used to analyse specific privacy mechanisms, such as the popular Gaussian mechanism. In this paper we show how fDP's foundation in statistical hypothesis testing implies equivalence to the channel model of Quantitative Information Flow. We demonstrate this equivalence by a Galois connection between two partially ordered sets. This equivalence enables novel general composition theorems for fDP, supporting improved analysis for complex privacy designs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.19019v1">Optimizer Dynamics at the Edge of Stability with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-12-22T04:16:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ayana Hussain, Ricky Fang</p>
    <p><b>Summary:</b> Deep learning models can reveal sensitive information about individual training examples, and while differential privacy (DP) provides guarantees restricting such leakage, it also alters optimization dynamics in poorly understood ways. We study the training dynamics of neural networks under DP by comparing Gradient Descent (GD), and Adam to their privacy-preserving variants. Prior work shows that these optimizers exhibit distinct stability dynamics: full-batch methods train at the Edge of Stability (EoS), while mini-batch and adaptive methods exhibit analogous edge-of-stability behavior. At these regimes, the training loss and the sharpness--the maximum eigenvalue of the training loss Hessian--exhibit certain characteristic behavior. In DP training, per-example gradient clipping and Gaussian noise modify the update rule, and it is unclear whether these stability patterns persist. We analyze how clipping and noise change sharpness and loss evolution and show that while DP generally reduces the sharpness and can prevent optimizers from fully reaching the classical stability thresholds, patterns from EoS and analogous adaptive methods stability regimes persist, with the largest learning rates and largest privacy budgets approaching, and sometimes exceeding, these thresholds. These findings highlight the unpredictability introduced by DP in neural network optimization.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.18809v1">FedVideoMAE: Efficient Privacy-Preserving Federated Video Moderation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Multimedia-5BC0EB">
  <p><b>Published on:</b> 2025-12-21T17:01:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ziyuan Tao, Chuanzhi Xu, Sandaru Jayawardana, Wei Bao, Kanchana Thilakarathna, Teng Joon Lim</p>
    <p><b>Summary:</b> The rapid growth of short-form video platforms increases the need for privacy-preserving moderation, as cloud-based pipelines expose raw videos to privacy risks, high bandwidth costs, and inference latency. To address these challenges, we propose an on-device federated learning framework for video violence detection that integrates self-supervised VideoMAE representations, LoRA-based parameter-efficient adaptation, and defense-in-depth privacy protection. Our approach reduces the trainable parameter count to 5.5M (~3.5% of a 156M backbone) and incorporates DP-SGD with configurable privacy budgets and secure aggregation. Experiments on RWF-2000 with 40 clients achieve 77.25% accuracy without privacy protection and 65-66% under strong differential privacy, while reducing communication cost by $28.3\times$ compared to full-model federated learning. The code is available at: {https://github.com/zyt-599/FedVideoMAE}</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.18646v1">Volley Revolver: A Novel Matrix-Encoding Method for Privacy-Preserving Deep Learning (Inference++)</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-12-21T08:40:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> John Chiang</p>
    <p><b>Summary:</b> Privacy-preserving inference of convolutional neural networks (CNNs) using homomorphic encryption has emerged as a promising approach for enabling secure machine learning in untrusted environments. In our previous work, we introduced a matrix-encoding strategy that allows convolution and matrix multiplication to be efficiently evaluated over encrypted data, enabling practical CNN inference without revealing either the input data or the model parameters. The core idea behind this strategy is to construct a three-dimensional representation within ciphertexts that preserves the intrinsic spatial structure of both input image data and model weights, rather than flattening them into conventional two-dimensional encodings. However, this approach can operate efficiently $only$ when the number of available plaintext slots within a ciphertext is sufficient to accommodate an entire input image, which becomes a critical bottleneck when processing high-resolution images. In this paper, we address this fundamental limitation by proposing an improved encoding and computation framework that removes the requirement that a single encrypted ciphertext must fully contain one input image. Our method reformulates the data layout and homomorphic operations to partition high-resolution inputs across multiple ciphertexts while preserving the algebraic structure required for efficient convolution and matrix multiplication. As a result, our approach enables privacy-preserving CNN inference to scale naturally beyond the slot-capacity constraints of prior methods, making homomorphic evaluation of CNNs practical for higher-resolution and more complex datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.18632v1">Multi-user Pufferfish Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-12-21T08:06:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ni Ding, Songpei Lu, Wenjing Yang, Zijian Zhang</p>
    <p><b>Summary:</b> This paper studies how to achieve individual indistinguishability by pufferfish privacy in aggregated query to a multi-user system. It is assumed that each user reports realization of a random variable. We study how to calibrate Laplace noise, added to the query answer, to attain pufferfish privacy when user changes his/her reported data value, leaves the system and is replaced by another use with different randomness. Sufficient conditions are derived for all scenarios for attaining statistical indistinguishability on four sets of secret pairs. They are derived using the existing Kantorovich method (Wasserstain metric of order $1$). These results can be applied to attain indistinguishability when a certain class of users is added or removed from a tabular data. It is revealed that attaining indifference in individual's data is conditioned on the statistics of this user only. For binary (Bernoulli distributed) random variables, the derived sufficient conditions can be further relaxed to reduce the noise and improve data utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.18432v1">Federated Learning Based Decentralized Adaptive Intelligent Transmission Protocol for Privacy Preserving 6G Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-12-20T17:18:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ansar Ahmed</p>
    <p><b>Summary:</b> The move to 6th Generation (6G) wireless networks creates new issues with privacy, scalability, and adaptability. The data-intensive nature of 6G is not handled well by older, centralized network models. A shift toward more secure and decentralized systems is therefore required. A new framework called the Federated Learning-based Decentralized Adaptive Intelligent Transmission Protocol (AITP) is proposed to meet these challenges. The AITP uses the distributed learning of Federated Learning (FL) within a decentralized system. Transmission parameters can be adjusted intelligently in real time. User privacy is maintained by keeping raw data on local edge devices. The protocol's performance was evaluated with mathematical modeling and detailed simulations. It was shown to be superior to traditional non-adaptive and centralized AI methods across several key metrics. These included latency, network throughput, energy efficiency, and robustness. The AITP is presented as a foundational technology for future 6G networks that supports a user-centric, privacy-first design. This study is a step forward for privacy-preserving research in 6G.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.18296v1">Privacy Data Pricing: A Stackelberg Game Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB"> 
  <p><b>Published on:</b> 2025-12-20T09:59:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lijun Bo, Weiqiang Chang</p>
    <p><b>Summary:</b> Data markets are emerging as key mechanisms for trading personal and organizational data. Traditional data pricing studies -- such as query-based or arbitrage-free pricing models -- mainly emphasize price consistency and profit maximization but often neglect privacy constraints and strategic interactions. The widespread adoption of differential privacy (DP) introduces a fundamental privacy-utility trade-off: noise protects individuals' privacy but reduces data accuracy and market value. This paper develops a Stackelberg game framework for pricing DP data, where the market maker (leader) sets the price function and the data buyer (follower) selects the optimal query precision under DP constraints. We derive the equilibrium strategies for both parties under a balanced pricing function where the pricing decision variable enters linearly into the original pricing model. We obtain closed-form solutions for the optimal variance and pricing level, and determine the boundary conditions for market participation. Furthermore, we extend the analysis to Stackelberg games involving nonlinear power pricing functions. The model bridges DP and economic mechanism design, offering a unified foundation for incentive-compatible and privacy-conscious data pricing in data markets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.18295v1">AL-GNN: Privacy-Preserving and Replay-Free Continual Graph Learning via Analytic Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-12-20T09:55:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xuling Zhang, Jindong Li, Yifei Zhang, Menglin Yang</p>
    <p><b>Summary:</b> Continual graph learning (CGL) aims to enable graph neural networks to incrementally learn from a stream of graph structured data without forgetting previously acquired knowledge. Existing methods particularly those based on experience replay typically store and revisit past graph data to mitigate catastrophic forgetting. However, these approaches pose significant limitations, including privacy concerns, inefficiency. In this work, we propose AL GNN, a novel framework for continual graph learning that eliminates the need for backpropagation and replay buffers. Instead, AL GNN leverages principles from analytic learning theory to formulate learning as a recursive least squares optimization process. It maintains and updates model knowledge analytically through closed form classifier updates and a regularized feature autocorrelation matrix. This design enables efficient one pass training for each task, and inherently preserves data privacy by avoiding historical sample storage. Extensive experiments on multiple dynamic graph classification benchmarks demonstrate that AL GNN achieves competitive or superior performance compared to existing methods. For instance, it improves average performance by 10% on CoraFull and reduces forgetting by over 30% on Reddit, while also reducing training time by nearly 50% due to its backpropagation free design.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.18207v1">FedWiLoc: Federated Learning for Privacy-Preserving WiFi Indoor Localization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">  
  <p><b>Published on:</b> 2025-12-20T04:10:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kanishka Roy, Tahsin Fuad Hasan, Chenfeng Wu, Eshwar Vangala, Roshan Ayyalasomayajula</p>
    <p><b>Summary:</b> Current data-driven Wi-Fi-based indoor localization systems face three critical challenges: protecting user privacy, achieving accurate predictions in dynamic multipath environments, and generalizing across different deployments. Traditional Wi-Fi localization systems often compromise user privacy, particularly when facing compromised access points (APs) or man-in-the-middle attacks. As IoT devices proliferate in indoor environments, developing solutions that deliver accurate localization while robustly protecting privacy has become imperative. We introduce FedWiLoc, a privacy-preserving indoor localization system that addresses these challenges through three key innovations. First, FedWiLoc employs a split architecture where APs process Channel State Information (CSI) locally and transmit only privacy-preserving embedding vectors to user devices, preventing raw CSI exposure. Second, during training, FedWiLoc uses federated learning to collaboratively train the model across APs without centralizing sensitive user data. Third, we introduce a geometric loss function that jointly optimizes angle-of-arrival predictions and location estimates, enforcing geometric consistency to improve accuracy in challenging multipath conditions. Extensive evaluation across six diverse indoor environments spanning over 2,000 sq. ft. demonstrates that FedWiLoc outperforms state-of-the-art methods by up to 61.9% in median localization error while maintaining strong privacy guarantees throughout both training and inference.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.18035v1">Towards Benchmarking Privacy Vulnerabilities in Selective Forgetting with Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-12-19T20:04:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wei Qian, Chenxu Zhao, Yangyi Li, Mengdi Huai</p>
    <p><b>Summary:</b> The rapid advancements in artificial intelligence (AI) have primarily focused on the process of learning from data to acquire knowledgeable learning systems. As these systems are increasingly deployed in critical areas, ensuring their privacy and alignment with human values is paramount. Recently, selective forgetting (also known as machine unlearning) has shown promise for privacy and data removal tasks, and has emerged as a transformative paradigm shift in the field of AI. It refers to the ability of a model to selectively erase the influence of previously seen data, which is especially important for compliance with modern data protection regulations and for aligning models with human values. Despite its promise, selective forgetting raises significant privacy concerns, especially when the data involved come from sensitive domains. While new unlearning-induced privacy attacks are continuously proposed, each is shown to outperform its predecessors using different experimental settings, which can lead to overly optimistic and potentially unfair assessments that may disproportionately favor one particular attack over the others. In this work, we present the first comprehensive benchmark for evaluating privacy vulnerabilities in selective forgetting. We extensively investigate privacy vulnerabilities of machine unlearning techniques and benchmark privacy leakage across a wide range of victim data, state-of-the-art unlearning privacy attacks, unlearning methods, and model architectures. We systematically evaluate and identify critical factors related to unlearning-induced privacy leakage. With our novel insights, we aim to provide a standardized tool for practitioners seeking to deploy customized unlearning applications with faithful privacy assessments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.17254v1">Practical Framework for Privacy-Preserving and Byzantine-robust Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-12-19T05:52:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Baolei Zhang, Minghong Fang, Zhuqing Liu, Biao Yi, Peizhao Zhou, Yuan Wang, Tong Li, Zheli Liu</p>
    <p><b>Summary:</b> Federated Learning (FL) allows multiple clients to collaboratively train a model without sharing their private data. However, FL is vulnerable to Byzantine attacks, where adversaries manipulate client models to compromise the federated model, and privacy inference attacks, where adversaries exploit client models to infer private data. Existing defenses against both backdoor and privacy inference attacks introduce significant computational and communication overhead, creating a gap between theory and practice. To address this, we propose ABBR, a practical framework for Byzantine-robust and privacy-preserving FL. We are the first to utilize dimensionality reduction to speed up the private computation of complex filtering rules in privacy-preserving FL. Additionally, we analyze the accuracy loss of vector-wise filtering in low-dimensional space and introduce an adaptive tuning strategy to minimize the impact of malicious models that bypass filtering on the global model. We implement ABBR with state-of-the-art Byzantine-robust aggregation rules and evaluate it on public datasets, showing that it runs significantly faster, has minimal communication overhead, and maintains nearly the same Byzantine-resilience as the baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.17251v1">AlignDP: Hybrid Differential Privacy with Rarity-Aware Protection for LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-12-19T05:36:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Madhava Gaikwad</p>
    <p><b>Summary:</b> Large language models are exposed to risks of extraction, distillation, and unauthorized fine-tuning. Existing defenses use watermarking or monitoring, but these act after leakage. We design AlignDP, a hybrid privacy lock that blocks knowledge transfer at the data interface. The key idea is to separate rare and non-rare fields. Rare fields are shielded by PAC indistinguishability, giving effective zero-epsilon local DP. Non-rare fields are privatized with RAPPOR, giving unbiased frequency estimates under local DP. A global aggregator enforces composition and budget. This two-tier design hides rare events and adds controlled noise to frequent events. We prove limits of PAC extension to global aggregation, give bounds for RAPPOR estimates, and analyze utility trade-off. A toy simulation confirms feasibility: rare categories remain hidden, frequent categories are recovered with small error.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.17239v1">Privacy-Preserving Synthetic Dataset of Individual Daily Trajectories for City-Scale Mobility Analytics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-12-19T04:59:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jun'ichi Ozaki, Ryosuke Susuta, Takuhiro Moriyama, Yohei Shida</p>
    <p><b>Summary:</b> Urban mobility data are indispensable for urban planning, transportation demand forecasting, pandemic modeling, and many other applications; however, individual mobile phone-derived Global Positioning System traces cannot generally be shared with third parties owing to severe re-identification risks. Aggregated records, such as origin-destination (OD) matrices, offer partial insights but fail to capture the key behavioral properties of daily human movement, limiting realistic city-scale analyses.
  This study presents a privacy-preserving synthetic mobility dataset that reconstructs daily trajectories from aggregated inputs. The proposed method integrates OD flows with two complementary behavioral constraints: (1) dwell-travel time quantiles that are available only as coarse summary statistics and (2) the universal law for the daily distribution of the number of visited locations. Embedding these elements in a multi-objective optimization framework enables the reproduction of realistic distributions of human mobility while ensuring that no personal identifiers are required.
  The proposed framework is validated in two contrasting regions of Japan: (1) the 23 special wards of Tokyo, representing a dense metropolitan environment; and (2) Fukuoka Prefecture, where urban and suburban mobility patterns coexist. The resulting synthetic mobility data reproduce dwell-travel time and visit frequency distributions with high fidelity, while deviations in OD consistency remain within the natural range of daily fluctuations.
  The results of this study establish a practical synthesis pathway under real-world constraints, providing governments, urban planners, and industries with scalable access to high-resolution mobility data for reliable analytics without the need for sensitive personal records, and supporting practical deployments in policy and commercial domains.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.16851v1">PrivateXR: Defending Privacy Attacks in Extended Reality Through Explainable AI-Guided Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-12-18T18:23:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ripan Kumar Kundu, Istiak Ahmed, Khaza Anuarul Hoque</p>
    <p><b>Summary:</b> The convergence of artificial AI and XR technologies (AI XR) promises innovative applications across many domains. However, the sensitive nature of data (e.g., eye-tracking) used in these systems raises significant privacy concerns, as adversaries can exploit these data and models to infer and leak personal information through membership inference attacks (MIA) and re-identification (RDA) with a high success rate. Researchers have proposed various techniques to mitigate such privacy attacks, including differential privacy (DP). However, AI XR datasets often contain numerous features, and applying DP uniformly can introduce unnecessary noise to less relevant features, degrade model accuracy, and increase inference time, limiting real-time XR deployment. Motivated by this, we propose a novel framework combining explainable AI (XAI) and DP-enabled privacy-preserving mechanisms to defend against privacy attacks. Specifically, we leverage post-hoc explanations to identify the most influential features in AI XR models and selectively apply DP to those features during inference. We evaluate our XAI-guided DP approach on three state-of-the-art AI XR models and three datasets: cybersickness, emotion, and activity classification. Our results show that the proposed method reduces MIA and RDA success rates by up to 43% and 39%, respectively, for cybersickness tasks while preserving model utility with up to 97% accuracy using Transformer models. Furthermore, it improves inference time by up to ~2x compared to traditional DP approaches. To demonstrate practicality, we deploy the XAI-guided DP AI XR models on an HTC VIVE Pro headset and develop a user interface (UI), namely PrivateXR, allowing users to adjust privacy levels (e.g., low, medium, high) while receiving real-time task predictions, protecting user privacy during XR gameplay.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.16401v3">Navigating the Reality Gap: Privacy-Preserving On-Device Continual Adaptation of ASR for Clinical Telephony</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-12-18T10:56:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Darshil Chauhan, Adityasinh Solanki, Vansh Patel, Kanav Kapoor, Ritvik Jain, Aditya Bansal, Pratik Narang, Dhruv Kumar</p>
    <p><b>Summary:</b> Automatic Speech Recognition (ASR) holds immense potential to assist in clinical documentation and patient report generation, particularly in resource-constrained regions. However, deployment is currently hindered by a technical deadlock: a severe "Reality Gap" between laboratory performance and noisy, real-world clinical audio, coupled with strict privacy and resource constraints. Such adaptation is essential for clinical telephony systems, where patient speech is highly variable and transcription errors can directly impact downstream clinical workflows. We quantify this gap, showing that a robust multilingual model (IndicWav2Vec) degrades up to a 40.94% WER on rural clinical telephony speech from India, rendering it unusable. We demonstrate consistent improvements on these helpline interactions without transmitting raw patient data off-device via an on-device continual adaptation framework using Low-Rank Adaptation (LoRA). We conduct an investigative study of stabilization strategies, characterizing the trade-offs between data-driven and parameter-driven approaches. Our results demonstrate that multi-domain Experience Replay (ER) yields the primary performance gains, achieving a 17.1% relative improvement in target WER and reducing catastrophic forgetting by 55% compared to naive adaptation. Furthermore, we investigate a stabilized importance estimation strategy (Absolute Fisher) to ensure robust convergence against the high-variance gradients common in clinical telephony speech. Finally, we verify via a domain-specific spot check that acoustic adaptation is a fundamental prerequisite for usability in healthcare settings which cannot be bypassed by language models alone.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.16394v1">SoK: Reviewing Two Decades of Security, Privacy, Accessibility, and Usability Studies on Internet of Things for Older Adults</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-12-18T10:43:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Suleiman Saka, Sanchari Das</p>
    <p><b>Summary:</b> The Internet of Things (IoT) has the potential to enhance older adults' independence and quality of life, but it also exposes them to security, privacy, accessibility, and usability (SPAU) risks. We conducted a systematic review of 44 peer-reviewed studies published between 2004 and 2024 using a five-phase screening pipeline. From each study, we extracted data on study design, IoT type, SPAU measures, and identified research gaps. We introduce the SPAU-IoT Framework, which comprises 27 criteria across four dimensions: security (e.g., resilience to cyber threats, secure authentication, encrypted communication, secure-by-default settings, and guardianship features), privacy (e.g., data minimization, explicit consent, and privacy-preserving analytics), accessibility (e.g., compliance with ADA/WCAG standards and assistive-technology compatibility), and usability (e.g., guided interaction, integrated assistance, and progressive learning). Applying this framework revealed that more than 70% of studies implemented authentication and encryption mechanisms, whereas fewer than 50% addressed accessibility or usability concerns. We further developed a threat model that maps IoT assets, networks, and backend servers to exploit vectors such as phishing, caregiver exploitation, and weak-password attacks, explicitly accounting for age-related vulnerabilities including cognitive decline and sensory impairment. Our results expose a systemic lack of integrated SPAU approaches in existing IoT research and translate these gaps into actionable, standards-aligned design guidelines for IoT systems designed for older adults.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.16284v1">Empirical Evaluation of Structured Synthetic Data Privacy Metrics: Novel experimental framework</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-12-18T08:09:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Milton Nicolás Plasencia Palacios, Alexander Boudewijn, Sebastiano Saccani, Andrea Filippo Ferraris, Diana Sofronieva, Giuseppe D'Acquisto, Filiberto Brozzetti, Daniele Panfilo, Luca Bortolussi</p>
    <p><b>Summary:</b> Synthetic data generation is gaining traction as a privacy enhancing technology (PET). When properly generated, synthetic data preserve the analytic utility of real data while avoiding the retention of information that would allow the identification of specific individuals. However, the concept of data privacy remains elusive, making it challenging for practitioners to evaluate and benchmark the degree of privacy protection offered by synthetic data. In this paper, we propose a framework to empirically assess the efficacy of tabular synthetic data privacy quantification methods through controlled, deliberate risk insertion. To demonstrate this framework, we survey existing approaches to synthetic data privacy quantification and the related legal theory. We then apply the framework to the main privacy quantification methods with no-box threat models on publicly available datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.16265v1">Privacy-Aware Sharing of Raw Spatial Sensor Data for Cooperative Perception</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E">
  <p><b>Published on:</b> 2025-12-18T07:27:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bangya Liu, Chengpo Yan, Chenghao Jiang, Suman Banerjee, Akarsh Prabhakara</p>
    <p><b>Summary:</b> Cooperative perception between vehicles is poised to offer robust and reliable scene understanding. Recently, we are witnessing experimental systems research building testbeds that share raw spatial sensor data for cooperative perception. While there has been a marked improvement in accuracies and is the natural way forward, we take a moment to consider the problems with such an approach for eventual adoption by automakers. In this paper, we first argue that new forms of privacy concerns arise and discourage stakeholders to share raw sensor data. Next, we present SHARP, a research framework to minimize privacy leakage and drive stakeholders towards the ambitious goal of raw data based cooperative perception. Finally, we discuss open questions for networked systems, mobile computing, perception researchers, industry and government in realizing our proposed framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.16126v1">Dual-View Inference Attack: Machine Unlearning Amplifies Privacy Exposure</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-12-18T03:24:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lulu Xue, Shengshan Hu, Linqiang Qian, Peijin Guo, Yechao Zhang, Minghui Li, Yanjun Zhang, Dayong Ye, Leo Yu Zhang</p>
    <p><b>Summary:</b> Machine unlearning is a newly popularized technique for removing specific training data from a trained model, enabling it to comply with data deletion requests. While it protects the rights of users requesting unlearning, it also introduces new privacy risks. Prior works have primarily focused on the privacy of data that has been unlearned, while the risks to retained data remain largely unexplored. To address this gap, we focus on the privacy risks of retained data and, for the first time, reveal the vulnerabilities introduced by machine unlearning under the dual-view setting, where an adversary can query both the original and the unlearned models. From an information-theoretic perspective, we introduce the concept of {privacy knowledge gain} and demonstrate that the dual-view setting allows adversaries to obtain more information than querying either model alone, thereby amplifying privacy leakage. To effectively demonstrate this threat, we propose DVIA, a Dual-View Inference Attack, which extracts membership information on retained data using black-box queries to both models. DVIA eliminates the need to train an attack model and employs a lightweight likelihood ratio inference module for efficient inference. Experiments across different datasets and model architectures validate the effectiveness of DVIA and highlight the privacy risks inherent in the dual-view setting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.16086v1">Privacy Blur: Quantifying Privacy and Utility for Image Data Release</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-12-18T02:01:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Saeed Mahloujifar, Narine Kokhlikyan, Chuan Guo, Kamalika Chaudhuri</p>
    <p><b>Summary:</b> Image data collected in the wild often contains private information such as faces and license plates, and responsible data release must ensure that this information stays hidden. At the same time, released data should retain its usefulness for model-training. The standard method for private information obfuscation in images is Gaussian blurring. In this work, we show that practical implementations of Gaussian blurring are reversible enough to break privacy. We then take a closer look at the privacy-utility tradeoffs offered by three other obfuscation algorithms -- pixelization, pixelization and noise addition (DP-Pix), and cropping. Privacy is evaluated by reversal and discrimination attacks, while utility by the quality of the learnt representations when the model is trained on data with obfuscated faces. We show that the most popular industry-standard method, Gaussian blur is the least private of the four -- being susceptible to reversal attacks in its practical low-precision implementations. In contrast, pixelization and pixelization plus noise addition, when used at the right level of granularity, offer both privacy and utility for a number of computer vision tasks. We make our proposed methods together with suggested parameters available in a software package called Privacy Blur.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.15981v1">Improved Lower Bounds for Privacy under Continual Release</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2025-12-17T21:26:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bardiya Aryanfard, Monika Henzinger, David Saulpic, A. R. Sricharan</p>
    <p><b>Summary:</b> We study the problem of continually releasing statistics of an evolving dataset under differential privacy. In the event-level setting, we show the first polynomial lower bounds on the additive error for insertions-only graph problems such as maximum matching, degree histogram and $k$-core. This is an exponential improvement on the polylogarithmic lower bounds of Fichtenberger et al.[ESA 2021] for the former two problems, and are the first continual release lower bounds for the latter. Our results run counter to the intuition that the difference between insertions-only vs fully dynamic updates causes the gap between polylogarithmic and polynomial additive error. We show that for maximum matching and $k$-core, allowing small multiplicative approximations is what brings the additive error down to polylogarithmic.
  Beyond graph problems, our techniques also show that polynomial additive error is unavoidable for Simultaneous Norm Estimation in the insertions-only setting. When multiplicative approximations are allowed, we circumvent this lower bound by giving the first continual mechanism with polylogarithmic additive error under $(1+ζ)$ multiplicative approximations, for $ζ>0$, for estimating all monotone symmetric norms simultaneously.
  In the item-level setting, we show polynomial lower bounds on the product of the multiplicative and the additive error of continual mechanisms for a large range of graph problems. To the best of our knowledge, these are the first lower bounds for any differentially private continual release mechanism with multiplicative error. To obtain this, we prove a new lower bound on the product of multiplicative and additive error for 1-Way-Marginals, from which we reduce to continual graph problems. This generalizes the lower bounds of Hardt and Talwar[STOC 2010] and Bun et al.[STOC 2014] on the additive error for mechanisms with no multiplicative error.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.15945v1">Privacy Discourse and Emotional Dynamics in Mental Health Information Interaction on Reddit</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-12-17T20:12:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jai Kruthunz Naveen Kumar, Aishwarya Umeshkumar Surani, Harkirat Singh, Sanchari Das</p>
    <p><b>Summary:</b> Reddit is a major venue for mental-health information interaction and peer support, where privacy concerns increasingly surface in user discourse. Thus, we analyze privacy-related discussions across 14 mental-health and regulatory subreddits, comprising 10,119 posts and 65,385 comments collected with a custom web scraper. Using lexicon-based sentiment analysis, we quantify emotional alignment between communities via cosine similarity of sentiment distributions, observing high similarity for Bipolar and ADHD (0.877), Anxiety and Depression (0.849), and MentalHealthSupport and MentalIllness (0.989) subreddits. We also construct keyword dictionaries to tag privacy-related themes (e.g., HIPAA, GDPR) and perform temporal analysis from 2020 to 2025, finding a 50% increase in privacy discourse with intermittent regulatory spikes. A chi-square test of independence across subreddit domains indicates significant distributional differences. The results characterize how privacy-oriented discussion co-varies with user sentiment in online mental-health communities.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.15335v1">Bits for Privacy: Evaluating Post-Training Quantization via Membership Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-12-17T11:28:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chenxiang Zhang, Tongxi Qu, Zhong Li, Tian Zhang, Jun Pang, Sjouke Mauw</p>
    <p><b>Summary:</b> Deep neural networks are widely deployed with quantization techniques to reduce memory and computational costs by lowering the numerical precision of their parameters. While quantization alters model parameters and their outputs, existing privacy analyses primarily focus on full-precision models, leaving a gap in understanding how bit-width reduction can affect privacy leakage. We present the first systematic study of the privacy-utility relationship in post-training quantization (PTQ), a versatile family of methods that can be applied to pretrained models without further training. Using membership inference attacks as our evaluation framework, we analyze three popular PTQ algorithms-AdaRound, BRECQ, and OBC-across multiple precision levels (4-bit, 2-bit, and 1.58-bit) on CIFAR-10, CIFAR-100, and TinyImageNet datasets. Our findings consistently show that low-precision PTQs can reduce privacy leakage. In particular, lower-precision models demonstrate up to an order of magnitude reduction in membership inference vulnerability compared to their full-precision counterparts, albeit at the cost of decreased utility. Additional ablation studies on the 1.58-bit quantization level show that quantizing only the last layer at higher precision enables fine-grained control over the privacy-utility trade-off. These results offer actionable insights for practitioners to balance efficiency, utility, and privacy protection in real-world deployments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.15123v1">TrajSyn: Privacy-Preserving Dataset Distillation from Federated Model Trajectories for Server-Side Adversarial Training</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-12-17T06:29:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mukur Gupta, Niharika Gupta, Saifur Rahman, Shantanu Pal, Chandan Karmakar</p>
    <p><b>Summary:</b> Deep learning models deployed on edge devices are increasingly used in safety-critical applications. However, their vulnerability to adversarial perturbations poses significant risks, especially in Federated Learning (FL) settings where identical models are distributed across thousands of clients. While adversarial training is a strong defense, it is difficult to apply in FL due to strict client-data privacy constraints and the limited compute available on edge devices. In this work, we introduce TrajSyn, a privacy-preserving framework that enables effective server-side adversarial training by synthesizing a proxy dataset from the trajectories of client model updates, without accessing raw client data. We show that TrajSyn consistently improves adversarial robustness on image classification benchmarks with no extra compute burden on the client device.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.14388v1">Black-Box Auditing of Quantum Model: Lifted Differential Privacy with Quantum Canaries</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-12-16T13:26:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Baobao Song, Shiva Raj Pokhrel, Athanasios V. Vasilakos, Tianqing Zhu, Gang Li</p>
    <p><b>Summary:</b> Quantum machine learning (QML) promises significant computational advantages, yet models trained on sensitive data risk memorizing individual records, creating serious privacy vulnerabilities. While Quantum Differential Privacy (QDP) mechanisms provide theoretical worst-case guarantees, they critically lack empirical verification tools for deployed models. We introduce the first black-box privacy auditing framework for QML based on Lifted Quantum Differential Privacy, leveraging quantum canaries (strategically offset-encoded quantum states) to detect memorization and precisely quantify privacy leakage during training. Our framework establishes a rigorous mathematical connection between canary offset and trace distance bounds, deriving empirical lower bounds on privacy budget consumption that bridge the critical gap between theoretical guarantees and practical privacy verification. Comprehensive evaluations across both simulated and physical quantum hardware demonstrate our framework's effectiveness in measuring actual privacy loss in QML models, enabling robust privacy verification in QML systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.14337v1">The Cost of Adaptation under Differential Privacy: Optimal Adaptive Federated Density Estimation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">
  <p><b>Published on:</b> 2025-12-16T12:06:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> T. Tony Cai, Abhinav Chakraborty, Lasse Vuursteen</p>
    <p><b>Summary:</b> Privacy-preserving data analysis has become a central challenge in modern statistics. At the same time, a long-standing goal in statistics is the development of adaptive procedures -- methods that achieve near-optimal performance across diverse function classes without prior knowledge of underlying smoothness or complexity. While adaptation is often achievable at no extra cost in the classical non-private setting, this naturally raises a fundamental question: to what extent is adaptation still possible under privacy constraints?
  We address this question in the context of density estimation under federated differential privacy (FDP), a framework that encompasses both central and local DP models. We establish sharp results that characterize the cost of adaptation under FDP for both global and pointwise estimation, revealing fundamental differences from the non-private case. We then propose an adaptive FDP estimator that achieves explicit performance guarantees by introducing a new noise mechanism, enabling one-shot adaptation via post-processing. This approach strictly improves upon existing adaptive DP methods. Finally, we develop new lower bound techniques that capture the limits of adaptive inference under privacy and may be of independent interest beyond this problem.
  Our findings reveal a sharp contrast between private and non-private settings. For global estimation, where adaptation can be achieved for free in the classical non-private setting, we prove that under FDP an intrinsic adaptation cost is unavoidable. For pointwise estimation, where a logarithmic penalty is already known to arise in the non-private setting, we show that FDP introduces an additional logarithmic factor, thereby compounding the cost of adaptation. Taken together, these results provide the first rigorous characterization of the adaptive privacy-accuracy trade-off.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.14767v1">Privacy-Preserving Feature Valuation in Vertical Federated Learning Using Shapley-CMI and PSI Permutation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-12-16T08:01:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Unai Laskurain, Aitor Aguirre-Ortuzar, Urko Zurutuza</p>
    <p><b>Summary:</b> Federated Learning (FL) is an emerging machine learning paradigm that enables multiple parties to collaboratively train models without sharing raw data, ensuring data privacy. In Vertical FL (VFL), where each party holds different features for the same users, a key challenge is to evaluate the feature contribution of each party before any model is trained, particularly in the early stages when no model exists. To address this, the Shapley-CMI method was recently proposed as a model-free, information-theoretic approach to feature valuation using Conditional Mutual Information (CMI). However, its original formulation did not provide a practical implementation capable of computing the required permutations and intersections securely. This paper presents a novel privacy-preserving implementation of Shapley-CMI for VFL. Our system introduces a private set intersection (PSI) server that performs all necessary feature permutations and computes encrypted intersection sizes across discretized and encrypted ID groups, without the need for raw data exchange. Each party then uses these intersection results to compute Shapley-CMI values, computing the marginal utility of their features. Initial experiments confirm the correctness and privacy of the proposed system, demonstrating its viability for secure and efficient feature contribution estimation in VFL. This approach ensures data confidentiality, scales across multiple parties, and enables fair data valuation without requiring the sharing of raw data or training models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.13880v1">Privacy-Enhancing Infant Cry Classification with Federated Transformers and Denoising Regularization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36">
  <p><b>Published on:</b> 2025-12-15T20:33:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Geofrey Owino, Bernard Shibwabo</p>
    <p><b>Summary:</b> Infant cry classification can aid early assessment of infant needs. However, deployment of such solutions is limited by privacy concerns around audio data, sensitivity to background noise, and domain shift across recording environments. We present an end-to-end infant cry analysis pipeline that integrates a denoising autoencoder (DAE), a convolutional tokenizer, and a Transformer encoder trained using communication-efficient federated learning (FL). The system performs on-device denoising, adaptive segmentation, post hoc calibration, and energy-based out-of-distribution (OOD) abstention. Federated training employs a regularized control variate update with 8-bit adapter deltas under secure aggregation. Using the Baby Chillanto and Donate-a-Cry datasets with ESC-50 noise overlays, the model achieves a macro F1 score of 0.938, an AUC of 0.962, and an Expected Calibration Error (ECE) of 0.032, while reducing per-round client upload from approximately 36 to 42 MB to 3.3 MB. Real-time edge inference on an NVIDIA Jetson Nano (4 GB, TensorRT FP16) achieves 96 ms per one-second spectrogram frame. These results demonstrate a practical path toward privacy-preserving, noise-robust, and communication-efficient infant cry classification suitable for federated deployment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.13439v1">Balancing Timeliness and Privacy in Discrete-Time Updating Systems</a></h3>
  
  <p><b>Published on:</b> 2025-12-15T15:34:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nitya Sathyavageeswaran, Anand D. Sarwate, Narayan B. Mandayam, Roy D. Yates</p>
    <p><b>Summary:</b> We study the trade-off between Age of Information (AoI) and maximal leakage (MaxL) in discrete-time status updating systems. A source generates time-stamped update packets that are processed by a server that delivers them to a monitor. An adversary, who eavesdrops on the server-monitor link, wishes to infer the timing of the underlying source update sequence. The server must balance the timeliness of the status information at the monitor against the timing information leaked to the adversary. We consider a model with Bernoulli source updates under two classes of Last-Come-First-Served (LCFS) service policies: (1) Coupled policies that tie the server's deliveries to the update arrival process in a preemptive queue; (2) Decoupled (dumping) policies in which the server transmits its freshest update according to a schedule that is independent of the update arrivals. For each class, we characterize the structure of the optimal policy that minimizes AoI for a given MaxL rate. Our analysis reveals that decoupled dumping policies offer a superior age-leakage trade-off to coupled policies. When subject to a MaxL constraint, we prove that the optimal dumping strategy is achieved by dithering between two adjacent deterministic dump periods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.13405v1">Improving Privacy Protection in the area of Behavioural Targeting</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-12-15T14:53:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Frederik Johannes Zuiderveen Borgesius</p>
    <p><b>Summary:</b> This PhD thesis discusses how European law could improve privacy protection in the area of behavioural targeting. Behavioural targeting, also referred to as online profiling, involves monitoring people's online behaviour, and using the collected information to show people individually targeted advertisements. To protect privacy in the area of behavioural targeting, the EU lawmaker mainly relies on the consent requirement for the use of tracking technologies in the e-Privacy Directive, and on general data protection law. With informed consent requirements, the law aims to empower people to make choices in their best interests. But behavioural studies cast doubt on the effectiveness of the empowerment approach as a privacy protection measure. Many people click "I agree" to any statement that is presented to them. Therefore, to mitigate privacy problems such as chilling effects, this study argues for a combined approach of protecting and empowering the individual. Compared to the current approach, the lawmaker should focus more on protecting people. The PhD thesis is a legal study, but it also incorporates insights from other disciplines, such as computer science, behavioural economics, and media studies. This study is among the first to discuss the implications of behavioural research for European data protection policy. The topic of whether data protection law should apply to pseudonymous data is discussed in depth. The study contains a detailed analysis of the role of informed consent in data protection law, and gives much attention to the tension between protecting and empowering the individual within data protection law.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.14756v1">Examining Software Developers' Needs for Privacy Enforcing Techniques: A survey</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-12-15T13:20:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ioanna Theophilou, Georgia M. Kapitsaki</p>
    <p><b>Summary:</b> Data privacy legislation, such as GDPR and CCPA/CPRA, has rendered data privacy law compliance a requirement of all software systems. Developers need to implement various kinds of functionalities to cover law needs, including user rights and law principles. As data compliance is tightly coupled with legal knowledge, it is not always easy to perform such integrations in software systems. Prior studies have focused on developers' understanding of privacy principles, such as Privacy by Design, and have examined privacy techniques used in the software industry. Nevertheless, emerging developer needs that can assist in privacy law compliance have not been examined but are useful in understanding what development automation tools, such as Generative AI, need to cover to make the compliance process more straightforward and seamless within the development process. In this work, we present a survey that examines the above needs with the participation of 68 developers, while we have examined which factors affect practitioners' needs. Most developers express a need for more automated tools, while privacy experience increases practitioners' concerns for privacy tools. Our results can assist practitioners in better positioning their development activities within privacy law compliance and point to an urgent need for privacy facilitators.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.12914v1">CTIGuardian: A Few-Shot Framework for Mitigating Privacy Leakage in Fine-Tuned LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-12-15T01:59:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shashie Dilhara Batan Arachchige, Benjamin Zi Hao Zhao, Hassan Jameel Asghar, Dinusha Vatsalan, Dali Kaafar</p>
    <p><b>Summary:</b> Large Language Models (LLMs) are often fine-tuned to adapt their general-purpose knowledge to specific tasks and domains such as cyber threat intelligence (CTI). Fine-tuning is mostly done through proprietary datasets that may contain sensitive information. Owners expect their fine-tuned model to not inadvertently leak this information to potentially adversarial end users. Using CTI as a use case, we demonstrate that data-extraction attacks can recover sensitive information from fine-tuned models on CTI reports, underscoring the need for mitigation. Retraining the full model to eliminate this leakage is computationally expensive and impractical. We propose an alternative approach, which we call privacy alignment, inspired by safety alignment in LLMs. Just like safety alignment teaches the model to abide by safety constraints through a few examples, we enforce privacy alignment through few-shot supervision, integrating a privacy classifier and a privacy redactor, both handled by the same underlying LLM. We evaluate our system, called CTIGuardian, using GPT-4o mini and Mistral-7B Instruct models, benchmarking against Presidio, a named entity recognition (NER) baseline. Results show that CTIGuardian provides a better privacy-utility trade-off than NER based models. While we demonstrate its effectiveness on a CTI use case, the framework is generic enough to be applicable to other sensitive domains.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.12856v1">Forgetful but Faithful: A Cognitive Memory Architecture and Benchmark for Privacy-Aware Generative Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-12-14T21:40:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Saad Alqithami</p>
    <p><b>Summary:</b> As generative agents become increasingly sophisticated and deployed in long-term interactive scenarios, their memory management capabilities emerge as a critical bottleneck for both performance and privacy. Current approaches either maintain unlimited memory stores, leading to computational intractability and privacy concerns, or employ simplistic forgetting mechanisms that compromise agent coherence and functionality. This paper introduces the Memory-Aware Retention Schema (MaRS), a novel framework for human-centered memory management in generative agents, coupled with six theoretically-grounded forgetting policies that balance performance, privacy, and computational efficiency. We present the Forgetful but Faithful Agent (FiFA) benchmark, a comprehensive evaluation framework that assesses agent performance across narrative coherence, goal completion, social recall accuracy, privacy preservation, and cost efficiency. Through extensive experimentation involving 300 evaluation runs across multiple memory budgets and agent configurations, we demonstrate that our hybrid forgetting policy achieves superior performance (composite score: 0.911) while maintaining computational tractability and privacy guarantees. Our work establishes new benchmarks for memory-budgeted agent evaluation and provides practical guidelines for deploying generative agents in resource-constrained, privacy-sensitive environments. The theoretical foundations, implementation framework, and empirical results contribute to the emerging field of human-centered AI by addressing fundamental challenges in agent memory management that directly impact user trust, system scalability, and regulatory compliance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.12840v1">PRIVEE: Privacy-Preserving Vertical Federated Learning Against Feature Inference Attacks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-12-14T21:05:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sindhuja Madabushi, Ahmad Faraz Khan, Haider Ali, Ananthram Swami, Rui Ning, Hongyi Wu, Jin-Hee Cho</p>
    <p><b>Summary:</b> Vertical Federated Learning (VFL) enables collaborative model training across organizations that share common user samples but hold disjoint feature spaces. Despite its potential, VFL is susceptible to feature inference attacks, in which adversarial parties exploit shared confidence scores (i.e., prediction probabilities) during inference to reconstruct private input features of other participants. To counter this threat, we propose PRIVEE (PRIvacy-preserving Vertical fEderated lEarning), a novel defense mechanism named after the French word privée, meaning "private." PRIVEE obfuscates confidence scores while preserving critical properties such as relative ranking and inter-score distances. Rather than exposing raw scores, PRIVEE shares only the transformed representations, mitigating the risk of reconstruction attacks without degrading model prediction accuracy. Extensive experiments show that PRIVEE achieves a threefold improvement in privacy protection compared to state-of-the-art defenses, while preserving full predictive performance against advanced feature inference attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.12586v1">StegaVAR: Privacy-Preserving Video Action Recognition via Steganographic Domain Analysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-12-14T07:44:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lixin Chen, Chaomeng Chen, Jiale Zhou, Zhijian Wu, Xun Lin</p>
    <p><b>Summary:</b> Despite the rapid progress of deep learning in video action recognition (VAR) in recent years, privacy leakage in videos remains a critical concern. Current state-of-the-art privacy-preserving methods often rely on anonymization. These methods suffer from (1) low concealment, where producing visually distorted videos that attract attackers' attention during transmission, and (2) spatiotemporal disruption, where degrading essential spatiotemporal features for accurate VAR. To address these issues, we propose StegaVAR, a novel framework that embeds action videos into ordinary cover videos and directly performs VAR in the steganographic domain for the first time. Throughout both data transmission and action analysis, the spatiotemporal information of hidden secret video remains complete, while the natural appearance of cover videos ensures the concealment of transmission. Considering the difficulty of steganographic domain analysis, we propose Secret Spatio-Temporal Promotion (STeP) and Cross-Band Difference Attention (CroDA) for analysis within the steganographic domain. STeP uses the secret video to guide spatiotemporal feature extraction in the steganographic domain during training. CroDA suppresses cover interference by capturing cross-band semantic differences. Experiments demonstrate that StegaVAR achieves superior VAR and privacy-preserving performance on widely used datasets. Moreover, our framework is effective for multiple steganographic models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.12471v1">Privacy-Aware Ambient Audio Sensing for Healthy Indoor Spaces</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36">
  <p><b>Published on:</b> 2025-12-13T21:55:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bhawana Chhaglani</p>
    <p><b>Summary:</b> Indoor airborne transmission poses a significant health risk, yet current monitoring solutions are invasive, costly, or fail to address it directly. My research explores the untapped potential of ambient audio sensing to estimate key transmission risk factors such as ventilation, aerosol emissions, and occupant distribution non-invasively and in real time. I develop privacy-preserving systems that leverage existing microphones to monitor the whole spectrum of indoor air quality which can have a significant effect on an individual's health. This work lays the foundation for privacy-aware airborne risk monitoring using everyday devices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.12224v1">Cluster-guided LLM-Based Anonymization of Software Analytics Data: Studying Privacy-Utility Trade-offs in JIT Defect Prediction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-12-13T07:37:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maaz Khan, Gul Sher Khan, Ahsan Raza, Pir Sami Ullah, Abdul Ali Bangash</p>
    <p><b>Summary:</b> The increasing use of machine learning (ML) for Just-In-Time (JIT) defect prediction raises concerns about privacy leakage from software analytics data. Existing anonymization methods, such as tabular transformations and graph perturbations, often overlook contextual dependencies among software metrics, leading to suboptimal privacy-utility tradeoffs. Leveraging the contextual reasoning of Large Language Models (LLMs), we propose a cluster-guided anonymization technique that preserves contextual and statistical relationships within JIT datasets. Our method groups commits into feature-based clusters and employs an LLM to generate context-aware parameter configurations for each commit cluster, defining alpha-beta ratios and churn mixture distributions used for anonymization. Our evaluation on six projects (Cassandra, Flink, Groovy, Ignite, OpenStack, and Qt) shows that our LLM-based approach achieves privacy level 2 (IPR >= 80 percent), improving privacy by 18 to 25 percent over four state-of-the-art graph-based anonymization baselines while maintaining comparable F1 scores. Our results demonstrate that LLMs can act as adaptive anonymization engines when provided with cluster-specific statistical information about similar data points, enabling context-sensitive and privacy-preserving software analytics without compromising predictive accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.14746v1">BLINDSPOT: Enabling Bystander-Controlled Privacy Signaling for Camera-Enabled Devices</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2025-12-12T19:12:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jad Al Aaraj, Athina Markopoulou</p>
    <p><b>Summary:</b> Camera-equipped mobile devices, such as phones, smart glasses, and AR headsets, pose a privacy challenge for bystanders, who currently lack effective real-time mechanisms to control the capture of their picture, video, including their face. We present BlindSpot, an on-device system that enables bystanders to manage their own privacy by signaling their privacy preferences in real-time without previously sharing any sensitive information. Our main contribution is the design and comparative evaluation of three distinct signaling modalities: a hand gesture mechanism, a significantly improved visible light communication (VLC) protocol, and a novel ultra-wideband (UWB) communication protocol. For all these modalities, we also design a validation mechanism that uses geometric consistency checks to verify the origin of a signal relative to the sending bystander, and defend against impersonation attacks. We implement the complete system (BlindSpot) on a commodity smartphone and conduct a comprehensive evaluation of each modality's accuracy and latency across various distances, lighting conditions, and user movements. Our results demonstrate the feasibility of these novel bystander signaling techniques and their trade-offs in terms of system performance and convenience.</p>
  </details>
</div>


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
  <h3><a href="http://arxiv.org/abs/2512.15759v1">Semantic-Constrained Federated Aggregation: Convergence Theory and Privacy-Utility Bounds for Knowledge-Enhanced Distributed Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-12-12T04:29:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jahidul Arafat</p>
    <p><b>Summary:</b> Federated learning enables collaborative model training across distributed data sources but suffers from slow convergence under non-IID data conditions. Existing solutions employ algorithmic modifications treating all client updates identically, ignoring semantic validity. We introduce Semantic-Constrained Federated Aggregation (SCFA), a theoretically-grounded framework incorporating domain knowledge constraints into distributed optimization. We prove SCFA achieves convergence rate O(1/sqrt(T) + rho) where rho represents constraint violation rate, establishing the first convergence theory for constraint-based federated learning. Our analysis shows constraints reduce effective data heterogeneity by 41% and improve privacy-utility tradeoffs through hypothesis space reduction by factor theta=0.37. Under (epsilon,delta)-differential privacy with epsilon=10, constraint regularization maintains utility within 3.7% of non-private baseline versus 12.1% degradation for standard federated learning, representing 2.7x improvement. We validate our framework on manufacturing predictive maintenance using Bosch production data with 1.18 million samples and 968 sensor features, constructing knowledge graphs encoding 3,000 constraints from ISA-95 and MASON ontologies. Experiments demonstrate 22% faster convergence, 41.3% model divergence reduction, and constraint violation thresholds where rho<0.05 maintains 90% optimal performance while rho>0.18 causes catastrophic failure. Our theoretical predictions match empirical observations with R^2>0.90 across convergence, privacy, and violation-performance relationships.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.15754v1">A Survey on Reconfigurable Intelligent Surfaces in Practical Systems: Security and Privacy Perspectives</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762"> 
  <p><b>Published on:</b> 2025-12-12T00:54:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ziyu Chen, Yitong Shen, Jingzhe Zhang, Yao Zheng, Yili Ren, Xuyu Wang, Shiwen Mao, Hanqing Guo</p>
    <p><b>Summary:</b> Reconfigurable Intelligent Surfaces (RIS) have emerged as a transformative technology capable of reshaping wireless environments through dynamic manipulation of electromagnetic waves. While extensive research has explored their theoretical benefits for communication and sensing, practical deployments in smart environments such as homes, vehicles, and industrial settings remain limited and under-examined, particularly from security and privacy perspectives. This survey provides a comprehensive examination of RIS applications in real-world systems, with a focus on the security and privacy threats, vulnerabilities, and defensive strategies relevant to practical use. We analyze scenarios with two types of systems (with and without legitimate RIS) and two types of attackers (with and without malicious RIS), and demonstrate how RIS may introduce new attacks to practical systems, including eavesdropping, jamming, and spoofing attacks. In response, we review defenses against RIS-related attacks in these systems, such as applying additional security algorithms, disrupting attackers, and early detection of unauthorized RIS. We also discuss scenarios in which the legitimate user applies an additional RIS to defend against attacks. To support future research, we also provide a collection of open-source tools, datasets, demos, and papers at: https://awesome-ris-security.github.io/. By highlighting RIS's functionality and its security/privacy challenges and opportunities, this survey aims to guide researchers and engineers toward the development of secure, resilient, and privacy-preserving RIS-enabled practical wireless systems and environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.14737v1">Zero-Knowledge Audit for Internet of Agents: Privacy-Preserving Communication Verification with Model Context Protocol</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-12-11T19:18:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guanlin Jing, Huayi Qi</p>
    <p><b>Summary:</b> Existing agent communication frameworks face critical limitations in providing verifiable audit trails without compromising the privacy and confidentiality of agent interactions. The protection of agent communication privacy while ensuring auditability emerges as a fundamental challenge for applications requiring accurate billing, compliance verification, and accountability in regulated environments.
  We introduce a framework for auditing agent communications that keeps messages private while still checking they follow expected rules. It pairs zero-knowledge proofs with the existing Model Context Protocol (MCP) so messages can be verified without revealing their contents. The approach runs in lightweight networks, stays compatible with standard MCP exchanges, and adds asynchronous audit verification to confirm format and general message types without exposing specifics.
  The framework enables mutual audits between agents: one side can check communication content and quality while the other verifies usage metrics, all without revealing sensitive information. We formalize security goals and show that zk-MCP provides data authenticity and communication privacy, achieving efficient verification with negligible latency overhead. We fully implement the framework, including Circom-based zero-knowledge proof generation and an audit protocol integrated with MCP's bidirectional channel, and, to our knowledge, this is the first privacy-preserving audit system for agent communications that offers verifiable mutual auditing without exposing message content or compromising agent privacy.</p>
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
  <h3><a href="http://arxiv.org/abs/2512.10426v2">Differential Privacy for Secure Machine Learning in Healthcare IoT-Cloud Systems</a></h3>
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
  <h3><a href="http://arxiv.org/abs/2512.08809v2">PrivTune: Efficient and Privacy-Preserving Fine-Tuning of Large Language Models via Device-Cloud Collaboration</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-12-09T17:03:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yi Liu, Weixiang Han, Chengjun Cai, Xingliang Yuan, Cong Wang</p>
    <p><b>Summary:</b> With the rise of large language models, service providers offer language models as a service, enabling users to fine-tune customized models via uploaded private datasets. However, this raises concerns about sensitive data leakage. Prior methods, relying on differential privacy within device-cloud collaboration frameworks, struggle to balance privacy and utility, exposing users to inference attacks or degrading fine-tuning performance. To address this, we propose PrivTune, an efficient and privacy-preserving fine-tuning framework via Split Learning (SL). The key idea of PrivTune is to inject crafted noise into token representations from the SL bottom model, making each token resemble the $n$-hop indirect neighbors. PrivTune formulates this as an optimization problem to compute the optimal noise vector, aligning with defense-utility goals. On this basis, it then adjusts the parameters (i.e., mean) of the $d_χ$-Privacy noise distribution to align with the optimization direction and scales the noise according to token importance to minimize distortion. Experiments on five datasets (covering both classification and generation tasks) against three embedding inversion and three attribute inference attacks show that, using RoBERTa on the Stanford Sentiment Treebank dataset, PrivTune reduces the attack success rate to 10% with only a 3.33% drop in utility performance, outperforming state-of-the-art baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.13717v1">Federated Few-Shot Learning for Epileptic Seizure Detection Under Privacy Constraints</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-12-09T16:01:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ekaterina Sysoykova, Bernhard Anzengruber-Tanase, Michael Haslgrubler, Philipp Seidl, Alois Ferscha</p>
    <p><b>Summary:</b> Many deep learning approaches have been developed for EEG-based seizure detection; however, most rely on access to large centralized annotated datasets. In clinical practice, EEG data are often scarce, patient-specific distributed across institutions, and governed by strict privacy regulations that prohibit data pooling. As a result, creating usable AI-based seizure detection models remains challenging in real-world medical settings. To address these constraints, we propose a two-stage federated few-shot learning (FFSL) framework for personalized EEG-based seizure detection. The method is trained and evaluated on the TUH Event Corpus, which includes six EEG event classes. In Stage 1, a pretrained biosignal transformer (BIOT) is fine-tuned across non-IID simulated hospital sites using federated learning, enabling shared representation learning without centralizing EEG recordings. In Stage 2, federated few-shot personalization adapts the classifier to each patient using only five labeled EEG segments, retaining seizure-specific information while still benefiting from cross-site knowledge. Federated fine-tuning achieved a balanced accuracy of 0.43 (centralized: 0.52), Cohen's kappa of 0.42 (0.49), and weighted F1 of 0.69 (0.74). In the FFSL stage, client-specific models reached an average balanced accuracy of 0.77, Cohen's kappa of 0.62, and weighted F1 of 0.73 across four sites with heterogeneous event distributions. These results suggest that FFSL can support effective patient-adaptive seizure detection under realistic data-availability and privacy constraints.</p>
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
  <h3><a href="http://arxiv.org/abs/2512.08096v2">Selling Privacy in Blockchain Transactions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB">
  <p><b>Published on:</b> 2025-12-08T23:13:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Georgios Chionas, Olga Gorelkina, Piotr Krysta, Rida Laraki</p>
    <p><b>Summary:</b> We study methods to enhance statistical privacy in blockchain transactions. We analyze economic mechanisms for privacy-aware transaction owners whose utility depends not only on the outcome of the mechanism but also negatively on the exposure of their economic preferences. First, we consider an order flow auction, where a user auctions off to specialized agents, called searchers, the right to execute her transaction while maintaining a degree of privacy. We examine how the degree of privacy affects the revenue of the auction and, broadly, the net utility of the privacy-aware user. In this new setting, we characterize the optimal auction, which is a sealed-bid auction. Subsequently, we analyze a variant of a Dutch auction in which the user gradually decreases the price and the degree of privacy until the transaction is sold. We compare the revenue of this auction to that of the optimal one as a function of the number of communication rounds. Then, we introduce a two-sided market - a privacy marketplace - with multiple users selling their transactions under their privacy preferences to multiple searchers. We propose a posted-price mechanism for the two-sided market that guarantees constant approximation of the optimal social welfare while maintaining incentive compatibility (from both sides of the market) and budget balance. This work builds on the emerging literature on privacy-preserving mechanism design, integrating statistical privacy guarantees into economic protocols to capture the impact of information leakage on blockchain users' utility.</p>
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
  <h3><a href="http://arxiv.org/abs/2512.06380v2">Protecting Bystander Privacy via Selective Hearing in Audio LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-12-06T10:24:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiao Zhan, Guangzhi Sun, Jose Such, Phil Woodland</p>
    <p><b>Summary:</b> Audio Large language models (LLMs) are increasingly deployed in the real world, where they inevitably capture speech from unintended nearby bystanders, raising privacy risks that existing benchmarks and defences did not consider. We introduce SH-Bench, the first benchmark designed to evaluate selective hearing: a model's ability to attend to an intended main speaker while refusing to process or reveal information about incidental bystander speech. SH-Bench contains 3,968 multi-speaker audio mixtures, including both real-world and synthetic scenarios, paired with 77k multiple-choice questions that probe models under general and selective operating modes. In addition, we propose Selective Efficacy (SE), a novel metric capturing both multi-speaker comprehension and bystander-privacy protection. Our evaluation of state-of-the-art open-source and proprietary LLMs reveals substantial bystander privacy leakage, with strong audio understanding failing to translate into selective protection of bystander privacy. To mitigate this gap, we also present Bystander Privacy Fine-Tuning (BPFT), a novel training pipeline that teaches models to refuse bystander-related queries without degrading main-speaker comprehension. We show that BPFT yields substantial gains, achieving an absolute 47% higher bystander accuracy under selective mode and an absolute 16% higher SE compared to Gemini 2.5 Pro, which is the best audio LLM without BPFT. Together, SH-Bench and BPFT provide the first systematic framework for measuring and improving bystander privacy in audio LLMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2512.06253v5">Privacy Loss of Noise Perturbation via Concentration Analysis of A Product Measure</a></h3>
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



<h2>2026-01</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.02855v1">Context-aware Privacy Bounds for Linear Queries</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-06T09:34:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Heng Zhao, Sara Saeidian, Tobias J. Oechtering</p>
    <p><b>Summary:</b> Linear queries, as the basis of broad analysis tasks, are often released through privacy mechanisms based on differential privacy (DP), the most popular framework for privacy protection. However, DP adopts a context-free definition that operates independently of the data-generating distribution. In this paper, we revisit the privacy analysis of the Laplace mechanism through the lens of pointwise maximal leakage (PML). We demonstrate that the distribution-agnostic definition of the DP framework often mandates excessive noise. To address this, we incorporate an assumption about the prior distribution by lower-bounding the probability of any single record belonging to any specific class. With this assumption, we derive a tight, context-aware leakage bound for general linear queries, and prove that our derived bound is strictly tighter than the standard DP guarantee and converges to the DP guarantee as this probability lower bound approaches zero. Numerical evaluations demonstrate that by exploiting this prior knowledge, the required noise scale can be reduced while maintaining privacy guarantees.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.02720v1">Privacy-Preserving AI-Enabled Decentralized Learning and Employment Records System</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-01-06T05:18:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuqiao Xu, Mina Namazi, Sahith Reddy Jalapally, Osama Zafar, Youngjin Yoo, Erman Ayday</p>
    <p><b>Summary:</b> Learning and Employment Record (LER) systems are emerging as critical infrastructure for securely compiling and sharing educational and work achievements. Existing blockchain-based platforms leverage verifiable credentials but typically lack automated skill-credential generation and the ability to incorporate unstructured evidence of learning. In this paper,a privacy-preserving, AI-enabled decentralized LER system is proposed to address these gaps. Digitally signed transcripts from educational institutions are accepted, and verifiable self-issued skill credentials are derived inside a trusted execution environment (TEE) by a natural language processing pipeline that analyzes formal records (e.g., transcripts, syllabi) and informal artifacts. All verification and job-skill matching are performed inside the enclave with selective disclosure, so raw credentials and private keys remain enclave-confined. Job matching relies solely on attested skill vectors and is invariant to non-skill resume fields, thereby reducing opportunities for screening bias.The NLP component was evaluated on sample learner data; the mapping follows the validated Syllabus-to-O*NET methodology,and a stability test across repeated runs observed <5% variance in top-ranked skills. Formal security statements and proof sketches are provided showing that derived credentials are unforgeable and that sensitive information remains confidential. The proposed system thus supports secure education and employment credentialing, robust transcript verification,and automated, privacy-preserving skill extraction within a decentralized framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.02307v1">Differential Privacy for Transformer Embeddings of Text with Nonparametric Variational Information Bottleneck</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-05T17:49:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dina El Zein, James Henderson</p>
    <p><b>Summary:</b> We propose a privacy-preserving method for sharing text data by sharing noisy versions of their transformer embeddings. It has been shown that hidden representations learned by deep models can encode sensitive information from the input, making it possible for adversaries to recover the input data with considerable accuracy. This problem is exacerbated in transformer embeddings because they consist of multiple vectors, one per token. To mitigate this risk, we propose Nonparametric Variational Differential Privacy (NVDP), which ensures both useful data sharing and strong privacy protection. We take a differential privacy approach, integrating a Nonparametric Variational Information Bottleneck (NVIB) layer into the transformer architecture to inject noise into its multi-vector embeddings and thereby hide information, and measuring privacy protection with Rényi divergence and its corresponding Bayesian Differential Privacy (BDP) guarantee. Training the NVIB layer calibrates the noise level according to utility. We test NVDP on the GLUE benchmark and show that varying the noise level gives us a useful tradeoff between privacy and accuracy. With lower noise levels, our model maintains high accuracy while offering strong privacy guarantees, effectively balancing privacy and utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.02245v1">MOZAIK: A Privacy-Preserving Analytics Platform for IoT Data Using MPC and FHE</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-05T16:25:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Michiel Van Kenhove, Erik Pohle, Leonard Schild, Martin Zbudila, Merlijn Sebrechts, Filip De Turck, Bruno Volckaert, Aysajan Abidin</p>
    <p><b>Summary:</b> The rapid increase of Internet of Things (IoT) systems across several domains has led to the generation of vast volumes of sensitive data, presenting significant challenges in terms of storage and data analytics. Cloud-assisted IoT solutions offer storage, scalability, and computational resources, but introduce new security and privacy risks that conventional trust-based approaches fail to adequately mitigate. To address these challenges, this paper presents MOZAIK, a novel end-to-end privacy-preserving confidential data storage and distributed processing architecture tailored for IoT-to-cloud scenarios. MOZAIK ensures that data remains encrypted throughout its lifecycle, including during transmission, storage, and processing. This is achieved by employing a cryptographic privacy-enhancing technology known as computing on encrypted data (COED). Two distinct COED techniques are explored, specifically secure multi-party computation (MPC) and fully homomorphic encryption (FHE). The paper includes a comprehensive analysis of the MOZAIK architecture, including a proof-of-concept implementation and performance evaluations. The evaluation results demonstrate the feasibility of the MOZAIK system and indicate the cost of an end-to-end privacy-preserving system compared to regular plaintext alternatives. All components of the MOZAIK platform are released as open-source software alongside this publication, with the aim of advancing secure and privacy-preserving data processing practices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.01993v1">MindChat: A Privacy-preserving Large Language Model for Mental Health Support</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-01-05T10:54:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dong Xue, Jicheng Tu, Ming Wang, Xin Yan, Fangzhou Liu, Jie Hu</p>
    <p><b>Summary:</b> Large language models (LLMs) have shown promise for mental health support, yet training such models is constrained by the scarcity and sensitivity of real counseling dialogues. In this article, we present MindChat, a privacy-preserving LLM for mental health support, together with MindCorpus, a synthetic multi-turn counseling dataset constructed via a multi-agent role-playing framework. To synthesize high-quality counseling data, the developed dialogue-construction framework employs a dual closed-loop feedback design to integrate psychological expertise and counseling techniques through role-playing: (i) turn-level critique-and-revision to improve coherence and counseling appropriateness within a session, and (ii) session-level strategy refinement to progressively enrich counselor behaviors across sessions. To mitigate privacy risks under decentralized data ownership, we fine-tune the base model using federated learning with parameter-efficient LoRA adapters and incorporate differentially private optimization to reduce membership and memorization risks. Experiments on synthetic-data quality assessment and counseling capability evaluation show that MindCorpus improves training effectiveness and that MindChat is competitive with existing general and counseling-oriented LLM baselines under both automatic LLM-judge and human evaluation protocols, while exhibiting reduced privacy leakage under membership inference attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.01737v1">Local Layer-wise Differential Privacy in Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-05T02:23:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yunbo Li, Jiaping Gui, Fanchao Meng, Yue Wu</p>
    <p><b>Summary:</b> Federated Learning (FL) enables collaborative model training without direct data sharing, yet it remains vulnerable to privacy attacks such as model inversion and membership inference. Existing differential privacy (DP) solutions for FL often inject noise uniformly across the entire model, degrading utility while providing suboptimal privacy-utility tradeoffs. To address this, we propose LaDP, a novel layer-wise adaptive noise injection mechanism for FL that optimizes privacy protection while preserving model accuracy. LaDP leverages two key insights: (1) neural network layers contribute unevenly to model utility, and (2) layer-wise privacy leakage can be quantified via KL divergence between local and global model distributions. LaDP dynamically injects noise into selected layers based on their privacy sensitivity and importance to model performance.
  We provide a rigorous theoretical analysis, proving that LaDP satisfies $(ε, δ)$-DP guarantees and converges under bounded noise. Extensive experiments on CIFAR-10/100 datasets demonstrate that LaDP reduces noise injection by 46.14% on average compared to state-of-the-art (SOTA) methods while improving accuracy by 102.99%. Under the same privacy budget, LaDP outperforms SOTA solutions like Dynamic Privacy Allocation LDP and AdapLDP by 25.18% and 6.1% in accuracy, respectively. Additionally, LaDP robustly defends against reconstruction attacks, increasing the FID of the reconstructed private data by $>$12.84% compared to all baselines. Our work advances the practical deployment of privacy-preserving FL with minimal utility loss.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.01710v1">Publishing Below-Threshold Triangle Counts under Local Weight Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2026-01-05T01:10:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kevin Pfisterer, Quentin Hillebrand, Vorapong Suppakitpaisarn</p>
    <p><b>Summary:</b> We propose an algorithm for counting below-threshold triangles in weighted graphs under local weight differential privacy. While prior work focused on unweighted graphs, many real-world networks naturally include edge weights. We study the setting where the graph topology is public known and the privacy of the influence of an individual on the edge weights is protected. This captures realistic scenarios such as road networks and telecommunication networks. Our approach consists of two rounds of communication. In the first round, each node publishes their incident weight information under local weight differential privacy while in the second round, the nodes locally count below-threshold triangles, for which we introduce a biased and unbiased variant. We further propose two different improvements. We present a pre-computation step that reduces the covariance and thereby lowers the expected error. Secondly, we develop an algorithm for computing the smooth-sensitivity, which significantly reduces the running time compared to a straightforward approach. Finally, we provide experimental results that demonstrate the differences between the biased and unbiased variants and the effectiveness of the proposed improvements.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.01668v1">EHRSummarizer: A Privacy-Aware, FHIR-Native Architecture for Structured Clinical Summarization of Electronic Health Records</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-01-04T21:10:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Houman Kazemzadeh, Nima Minaifar, Kamyar Naderi, Sho Tabibzadeh</p>
    <p><b>Summary:</b> Clinicians routinely navigate fragmented electronic health record (EHR) interfaces to assemble a coherent picture of a patient's problems, medications, recent encounters, and longitudinal trends. This work describes EHRSummarizer, a privacy-aware, FHIR-native reference architecture that retrieves a targeted set of high-yield FHIR R4 resources, normalizes them into a consistent clinical context package, and produces structured summaries intended to support structured chart review. The system can be configured for data minimization, stateless processing, and flexible deployment, including local inference within an organization's trust boundary. To mitigate the risk of unsupported or unsafe behavior, the summarization stage is constrained to evidence present in the retrieved context package, is intended to indicate missing or unavailable domains where feasible, and avoids diagnostic or treatment recommendations. Prototype demonstrations on synthetic and test FHIR environments illustrate end-to-end behavior and output formats; however, this manuscript does not report clinical outcomes or controlled workflow studies. We outline an evaluation plan centered on faithfulness, omission risk, temporal correctness, usability, and operational monitoring to guide future institutional assessments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.01239v1">IO-RAE: Information-Obfuscation Reversible Adversarial Example for Audio Privacy Protection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Multimedia-5BC0EB"> 
  <p><b>Published on:</b> 2026-01-03T17:08:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiajie Zhu, Xia Du, Xiaoyuan Liu, Jizhe Zhou, Qizhen Xu, Zheng Lin, Chi-Man Pun</p>
    <p><b>Summary:</b> The rapid advancements in artificial intelligence have significantly accelerated the adoption of speech recognition technology, leading to its widespread integration across various applications. However, this surge in usage also highlights a critical issue: audio data is highly vulnerable to unauthorized exposure and analysis, posing significant privacy risks for businesses and individuals. This paper introduces an Information-Obfuscation Reversible Adversarial Example (IO-RAE) framework, the pioneering method designed to safeguard audio privacy using reversible adversarial examples. IO-RAE leverages large language models to generate misleading yet contextually coherent content, effectively preventing unauthorized eavesdropping by humans and Automatic Speech Recognition (ASR) systems. Additionally, we propose the Cumulative Signal Attack technique, which mitigates high-frequency noise and enhances attack efficacy by targeting low-frequency signals. Our approach ensures the protection of audio data without degrading its quality or our ability. Experimental evaluations demonstrate the superiority of our method, achieving a targeted misguidance rate of 96.5% and a remarkable 100% untargeted misguidance rate in obfuscating target keywords across multiple ASR models, including a commercial black-box system from Google. Furthermore, the quality of the recovered audio, measured by the Perceptual Evaluation of Speech Quality score, reached 4.45, comparable to high-quality original recordings. Notably, the recovered audio processed by ASR systems exhibited an error rate of 0%, indicating nearly lossless recovery. These results highlight the practical applicability and effectiveness of our IO-RAE framework in protecting sensitive audio privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.00715v1">PDPL Metric: Validating a Scale to Measure Personal Data Privacy Literacy Among University Students</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-01-02T15:12:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Brady D. Lund, Nathan Brown, Ana Roeschley, Gahangir Hossain</p>
    <p><b>Summary:</b> Personal data privacy literacy (PDPL) refers to a collection of digital literacy skills related to an individuals ability to understand, evaluate, and manage the collection, use, and protection of personal data in online and digital environments. This study introduces and validates a new psychometric scale (PDPL Metric) designed to measure data privacy literacy among university students, focusing on six key privacy constructs: perceived risk of data misuse, expectations of informed consent, general privacy concern, privacy management awareness, privacy-utility trade-off acceptance, and perceived importance of data security. A 24-item questionnaire was developed and administered to students at U.S.-based research universities. Principal components analysis confirmed the unidimensionality and internal consistency of each construct, and a second-order analysis supported the integration of all six into a unified PDPL construct. No differences in PDPL were found based on basic demographic variables like academic level and gender, although a difference was found based on domestic/international status. The findings of this study offer a validated framework for assessing personal data privacy literacy within the higher education context and support the integration of the core constructs into higher education programs, organizational policies, and digital literacy initiatives on university campuses.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.00418v1">Secure, Verifiable, and Scalable Multi-Client Data Sharing via Consensus-Based Privacy-Preserving Data Distribution</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-01T18:12:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Prajwal Panth, Sahaj Raj Malla</p>
    <p><b>Summary:</b> We propose the Consensus-Based Privacy-Preserving Data Distribution (CPPDD) framework, a lightweight and post-setup autonomous protocol for secure multi-client data aggregation. The framework enforces unanimous-release confidentiality through a dual-layer protection mechanism that combines per-client affine masking with priority-driven sequential consensus locking. Decentralized integrity is verified via step (sigma_S) and data (sigma_D) checksums, facilitating autonomous malicious deviation detection and atomic abort without requiring persistent coordination. The design supports scalar, vector, and matrix payloads with O(N*D) computation and communication complexity, optional edge-server offloading, and resistance to collusion under N-1 corruptions. Formal analysis proves correctness, Consensus-Dependent Integrity and Fairness (CDIF) with overwhelming-probability abort on deviation, and IND-CPA security assuming a pseudorandom function family. Empirical evaluations on MNIST-derived vectors demonstrate linear scalability up to N = 500 with sub-millisecond per-client computation times. The framework achieves 100% malicious deviation detection, exact data recovery, and three-to-four orders of magnitude lower FLOPs compared to MPC and HE baselines. CPPDD enables atomic collaboration in secure voting, consortium federated learning, blockchain escrows, and geo-information capacity building, addressing critical gaps in scalability, trust minimization, and verifiable multi-party computation for regulated and resource-constrained environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.00385v1">Exploring the Integration of Differential Privacy in Cybersecurity Analytics: Balancing Data Utility and Privacy in Threat Intelligence</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-01T16:31:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Brahim Khalil Sedraoui, Abdelmadjid Benmachiche, Amina Makhlouf, Chaouki Chemam</p>
    <p><b>Summary:</b> To resolve the acute problem of privacy protection and guarantee that data can be used in the context of threat intelligence, this paper considers the implementation of Differential Privacy (DP) in cybersecurity analytics. DP, which is a sound mathematical framework, ensures privacy by adding a controlled noise to data outputs and thus avoids sensitive information disclosure even with auxiliary datasets. The use of DP in Security Information and Event Management (SIEM) systems is highlighted, and it can be seen that DP has the capability to protect event log and threat data analysis without interfering with the analytical efficiency. The utility versus privacy trade-offs linked to the maximization of the epsilon parameter, which is one of the critical components of DP mechanisms, is pointed out. The article shows the transformative power of DP in promoting safe sharing of data and joint threat intelligence through real-world systems and case studies. Finally, this paper makes DP one of the key strategies to improve privacy-preserving analytics in the field of cybersecurity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.00382v1">Unseen Risks of Clinical Speech-to-Text Systems: Transparency, Privacy, and Reliability Challenges in AI-Driven Documentation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-01-01T16:18:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nelly Elsayed</p>
    <p><b>Summary:</b> AI-driven speech-to-text (STT) documentation systems are increasingly adopted in clinical settings to reduce documentation burden and improve workflow efficiency. However, their rapid deployment has outpaced understanding of the associated socio-technical risks, including transparency, reliability, patient autonomy, workflow alignment, and organizational governance. A clearer analysis of these risks is needed to support safe and equitable integration into healthcare practice. This study synthesizes interdisciplinary evidence from technical performance research, regulatory and ethical standards, clinical workflow analyses, and organizational policy guidance. The synthesis was used to develop a multi-layered socio-technical conceptual framework for evaluating and governing STT systems. Findings show that STT systems operate within tightly coupled socio-technical environments in which model performance, clinician oversight, patient rights, workflow design, and institutional governance are interdependent. The study offers a structured socio-technical governance framework and an implementation roadmap that outlines readiness assessment, vendor evaluation, pilot deployment, clinician training, ongoing monitoring, and iterative improvement. The framework emphasizes safeguards that protect patient autonomy, documentation integrity, and institutional trust while enabling the efficient and beneficial use of STT technologies. This work provides actionable guidance for healthcare organizations seeking to adopt STT systems responsibly and equitably.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.00372v1">LLM-Powered Analysis of IoT User Reviews: Tracking and Ranking Security and Privacy Concerns</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-01T15:24:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Taufiq Islam Protick, Sai Teja Peddinti, Nina Taft, Anupam Das</p>
    <p><b>Summary:</b> Being able to understand the security and privacy (S&P) concerns of IoT users brings benefits to both developers and users. To learn about users' views, we examine Amazon IoT reviews - one of the biggest IoT markets. This work presents a state-of-the-art methodology to identify and categorize reviews in which users express S&P concerns. We developed an automated pipeline by fine-tuning GPT-3.5-Turbo to build two models: the Classifier-Rationalizer-Categorizer and the Thematic Mapper. By leveraging dynamic few-shot prompting and the model's large context size, our pipeline achieved over 97% precision and recall, significantly outperforming keyword-based and classical ML methods. We applied our pipeline to 91K Amazon reviews about fitness trackers, smart speakers and cameras, over multiple years. We found that on average 5% contained S&P concerns, while security camera exhibited the highest prevalence at 10%. Our method detected significantly more S&P-relevant reviews than prior works: 15x more for fitness trackers, 29% more for smart speakers, and 70% more for cameras. Our longitudinal analysis reveals that concerns like surveillance and data control have persisted for years, suggesting limited industry progress. We demonstrate that across all device types, users consistently demand more precise control over what data is collected and shared. We uncover challenges in multi-user and multi-device interactions, identifying two previously unreported themes concerning inadequate controls for account separation and data access. These findings, ranging from broad persistent trends to specific instances of customer loss, offer actionable insights for developers to improve user satisfaction and trust.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.00337v1">When Does Quantum Differential Privacy Compose?</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-01-01T13:24:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Daniel Alabi, Theshani Nuradha</p>
    <p><b>Summary:</b> Composition is a cornerstone of classical differential privacy, enabling strong end-to-end guarantees for complex algorithms through composition theorems (e.g., basic and advanced). In the quantum setting, however, privacy is defined operationally against arbitrary measurements, and classical composition arguments based on scalar privacy-loss random variables no longer apply. As a result, it has remained unclear when meaningful composition guarantees can be obtained for quantum differential privacy (QDP).
  In this work, we clarify both the limitations and possibilities of composition in the quantum setting. We first show that classical-style composition fails in full generality for POVM-based approximate QDP: even quantum channels that are individually perfectly private can completely lose privacy when combined through correlated joint implementations. We then identify a setting in which clean composition guarantees can be restored. For tensor-product channels acting on product neighboring inputs, we introduce a quantum moments accountant based on an operator-valued notion of privacy loss and a matrix moment-generating function. Although the resulting Rényi-type divergence does not satisfy a data-processing inequality, we prove that controlling its moments suffices to bound measured Rényi divergence, yielding operational privacy guarantees against arbitrary measurements. This leads to advanced-composition-style bounds with the same leading-order behavior as in the classical theory.
  Our results demonstrate that meaningful composition theorems for quantum differential privacy require carefully articulated structural assumptions on channels, inputs, and adversarial measurements, and provide a principled framework for understanding which classical ideas do and do not extend to the quantum setting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.00911v1">Device-Native Autonomous Agents for Privacy-Preserving Negotiations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-01T04:29:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joyjit Roy</p>
    <p><b>Summary:</b> Automated negotiations in insurance and business-to-business (B2B) commerce encounter substantial challenges. Current systems force a trade-off between convenience and privacy by routing sensitive financial data through centralized servers, increasing security risks, and diminishing user trust. This study introduces a device-native autonomous Artificial Intelligence (AI) agent system for privacy-preserving negotiations. The proposed system operates exclusively on user hardware, enabling real-time bargaining while maintaining sensitive constraints locally. It integrates zero-knowledge proofs to ensure privacy and employs distilled world models to support advanced on-device reasoning. The architecture incorporates six technical components within an agentic AI workflow. Agents autonomously plan negotiation strategies, conduct secure multi-party bargaining, and generate cryptographic audit trails without exposing user data to external servers. The system is evaluated in insurance and B2B procurement scenarios across diverse device configurations. Results show an average success rate of 87%, a 2.4x latency improvement over cloud baselines, and strong privacy preservation through zero-knowledge proofs. User studies show 27% higher trust scores when decision trails are available. These findings establish a foundation for trustworthy autonomous agents in privacy-sensitive financial domains.</p>
  </details>
</div>

