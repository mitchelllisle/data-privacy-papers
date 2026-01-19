
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
  <h3><a href="http://arxiv.org/abs/2512.16401v4">Navigating the Reality Gap: Privacy-Preserving On-Device Continual Adaptation of ASR for Clinical Telephony</a></h3>
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



<h2>2026-01</h2>

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
  <h3><a href="http://arxiv.org/abs/2601.05180v1">The Adverse Effects of Omitting Records in Differential Privacy: How Sampling and Suppression Degrade the Privacy-Utility Tradeoff (Long Version)</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-08T18:03:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Àlex Miranda-Pascual, Javier Parra-Arnau, Thorsten Strufe</p>
    <p><b>Summary:</b> Sampling is renowned for its privacy amplification in differential privacy (DP), and is often assumed to improve the utility of a DP mechanism by allowing a noise reduction. In this paper, we further show that this last assumption is flawed: When measuring utility at equal privacy levels, sampling as preprocessing consistently yields penalties due to utility loss from omitting records over all canonical DP mechanisms -- Laplace, Gaussian, exponential, and report noisy max -- as well as recent applications of sampling, such as clustering.
  Extending this analysis, we investigate suppression as a generalized method of choosing, or omitting, records. Developing a theoretical analysis of this technique, we derive privacy bounds for arbitrary suppression strategies under unbounded approximate DP. We find that our tested suppression strategy also fails to improve the privacy-utility tradeoff. Surprisingly, uniform sampling emerges as one of the best suppression methods -- despite its still degrading effect. Our results call into question common preprocessing assumptions in DP practice.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.04912v1">Decentralized Privacy-Preserving Federal Learning of Computer Vision Models on Edge Devices</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-01-08T13:10:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Damian Harenčák, Lukáš Gajdošech, Martin Madaras</p>
    <p><b>Summary:</b> Collaborative training of a machine learning model comes with a risk of sharing sensitive or private data. Federated learning offers a way of collectively training a single global model without the need to share client data, by sharing only the updated parameters from each client's local model. A central server is then used to aggregate parameters from all clients and redistribute the aggregated model back to the clients. Recent findings have shown that even in this scenario, private data can be reconstructed only using information about model parameters. Current efforts to mitigate this are mainly focused on reducing privacy risks on the server side, assuming that other clients will not act maliciously. In this work, we analyzed various methods for improving the privacy of client data concerning both the server and other clients for neural networks. Some of these methods include homomorphic encryption, gradient compression, gradient noising, and discussion on possible usage of modified federated learning systems such as split learning, swarm learning or fully encrypted models. We have analyzed the negative effects of gradient compression and gradient noising on the accuracy of convolutional neural networks used for classification. We have shown the difficulty of data reconstruction in the case of segmentation networks. We have also implemented a proof of concept on the NVIDIA Jetson TX2 module used in edge devices and simulated a federated learning process.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.04815v1">Privacy-Utility Trade-offs Under Multi-Level Point-Wise Leakage Constraints</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-01-08T10:47:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Amirreza Zamani, Parastoo Sadeghi, Mikael Skoglund</p>
    <p><b>Summary:</b> An information-theoretic privacy mechanism design is studied, where an agent observes useful data $Y$ which is correlated with the private data $X$. The agent wants to reveal the information to a user, hence, the agent utilizes a privacy mechanism to produce disclosed data $U$ that can be revealed. We assume that the agent has no direct access to $X$, i.e., the private data is hidden. We study privacy mechanism design that maximizes the disclosed information about $Y$, measured by the mutual information between $Y$ and $U$, while satisfying a point-wise constraint with different privacy leakage budgets. We introduce a new measure, called the \emph{multi-level point-wise leakage}, which allows us to impose different leakage levels for different realizations of $U$. In contrast to previous studies on point-wise measures, which use the same leakage level for each realization, we consider a more general scenario in which each data point can leak information up to a different threshold. As a result, this concept also covers cases in which some data points should not leak any information about the private data, i.e., they must satisfy perfect privacy. In other words, a combination of perfect privacy and non-zero leakage can be considered. When the leakage is sufficiently small, concepts from information geometry allow us to locally approximate the mutual information. We show that when the leakage matrix $P_{X|Y}$ is invertible, utilizing this approximation leads to a quadratic optimization problem that has closed-form solution under some constraints. In particular, we show that it is sufficient to consider only binary $U$ to attain the optimal utility. This leads to simple privacy designs with low complexity which are based on finding the maximum singular value and singular vector of a matrix.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.06200v1">Leveraging Membership Inference Attacks for Privacy Measurement in Federated Learning for Remote Sensing Images</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-01-08T08:58:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anh-Kiet Duong, Petra Gomez-Krämer, Hoàng-Ân Lê, Minh-Tan Pham</p>
    <p><b>Summary:</b> Federated Learning (FL) enables collaborative model training while keeping training data localized, allowing us to preserve privacy in various domains including remote sensing. However, recent studies show that FL models may still leak sensitive information through their outputs, motivating the need for rigorous privacy evaluation. In this paper, we leverage membership inference attacks (MIA) as a quantitative privacy measurement framework for FL applied to remote sensing image classification. We evaluate multiple black-box MIA techniques, including entropy-based attacks, modified entropy attacks, and the likelihood ratio attack, across different FL algorithms and communication strategies. Experiments conducted on two public scene classification datasets demonstrate that MIA effectively reveals privacy leakage not captured by accuracy alone. Our results show that communication-efficient FL strategies reduce MIA success rates while maintaining competitive performance. These findings confirm MIA as a practical metric and highlight the importance of integrating privacy measurement into FL system design for remote sensing applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.04641v1">DP-MGTD: Privacy-Preserving Machine-Generated Text Detection via Adaptive Differentially Private Entity Sanitization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-08T06:33:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lionel Z. Wang, Yusheng Zhao, Jiabin Luo, Xinfeng Li, Lixu Wang, Yinan Peng, Haoyang Li, XiaoFeng Wang, Wei Dong</p>
    <p><b>Summary:</b> The deployment of Machine-Generated Text (MGT) detection systems necessitates processing sensitive user data, creating a fundamental conflict between authorship verification and privacy preservation. Standard anonymization techniques often disrupt linguistic fluency, while rigorous Differential Privacy (DP) mechanisms typically degrade the statistical signals required for accurate detection. To resolve this dilemma, we propose \textbf{DP-MGTD}, a framework incorporating an Adaptive Differentially Private Entity Sanitization algorithm. Our approach utilizes a two-stage mechanism that performs noisy frequency estimation and dynamically calibrates privacy budgets, applying Laplace and Exponential mechanisms to numerical and textual entities respectively. Crucially, we identify a counter-intuitive phenomenon where the application of DP noise amplifies the distinguishability between human and machine text by exposing distinct sensitivity patterns to perturbation. Extensive experiments on the MGTBench-2.0 dataset show that our method achieves near-perfect detection accuracy, significantly outperforming non-private baselines while satisfying strict privacy guarantees.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.04488v2">Invisible Walls: Privacy-Preserving ISAC Empowered by Reconfigurable Intelligent Surfaces</a></h3>
  
  <p><b>Published on:</b> 2026-01-08T01:47:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yinghui He, Long Fan, Lei Xie, Dusit Niyato, Chau Yuen, Jun Luo</p>
    <p><b>Summary:</b> The environmental and target-related information inherently carried in wireless signals, such as channel state information (CSI), has brought increasing attention to integrated sensing and communication (ISAC). However, it also raises pressing concerns about privacy leakage through eavesdropping. While existing efforts have attempted to mitigate this issue, they either fail to account for the needs of legitimate communication and sensing users or rely on hardware with high complexity and cost. To overcome these limitations, we propose PrivISAC, a plug-and-play, low-cost solution that leverages RIS to protect user privacy while preserving ISAC performance. At the core of PrivISAC is a novel strategy in which each RIS row is assigned two distinct beamforming vectors, from which we deliberately construct a limited set of RIS configurations. During operation, exactly one configuration is randomly activated at each time slot to introduce additional perturbations, effectively masking sensitive sensing information from unauthorized eavesdroppers. To jointly ensure privacy protection and communication performance, we design the two vectors such that their responses remain nearly identical in the communication direction, thereby preserving stable, high-throughput transmission, while exhibiting pronounced differences in the sensing direction, which introduces sufficient perturbations to thwart eavesdroppers. Additionally, to enable legitimate sensing under such randomized configurations, we introduce a time-domain masking and demasking method that allows the authorized receiver to associate each CSI sample with its underlying configuration and eliminate configuration-induced discrepancies, thereby recovering valid CSI. We implement PrivISAC on commodity wireless devices and experiment results show that PrivISAC provides strong privacy protection while preserving high-quality legitimate ISAC.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.04403v1">Balancing Usability and Compliance in AI Smart Devices: A Privacy-by-Design Audit of Google Home, Alexa, and Siri</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-01-07T21:20:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Trevor De Clark, Yulia Bobkova, Ajay Kumar Shrestha</p>
    <p><b>Summary:</b> This paper investigates the privacy and usability of AI-enabled smart devices commonly used by youth, focusing on Google Home Mini, Amazon Alexa, and Apple Siri. While these devices provide convenience and efficiency, they also raise privacy and transparency concerns due to their always-listening design and complex data management processes. The study proposes and applies a combined framework of Heuristic Evaluation, Personal Information Protection and Electronic Documents Act (PIPEDA) Compliance Assessment, and Youth-Centered Usability Testing to assess whether these devices align with Privacy-by-Design principles and support meaningful user control. Results show that Google Home achieved the highest usability score, while Siri scored highest in regulatory compliance, indicating a trade-off between user convenience and privacy protection. Alexa demonstrated clearer task navigation but weaker transparency in data retention. Findings suggest that although youth may feel capable of managing their data, their privacy self-efficacy remains limited by technical design, complex settings, and unclear data policies. The paper concludes that enhancing transparency, embedding privacy guidance during onboarding, and improving policy alignment are critical steps toward ensuring that smart devices are both usable and compliant with privacy standards that protect young users.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.04399v1">Convenience vs. Control: A Qualitative Study of Youth Privacy with Smart Voice Assistants</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-01-07T21:15:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Molly Campbell, Trevor De Clark, Mohamad Sheikho Al Jasem, Sandhya Joshi, Ajay Kumar Shrestha</p>
    <p><b>Summary:</b> Smart voice assistants (SVAs) are embedded in the daily lives of youth, yet their privacy controls often remain opaque and difficult to manage. Through five semi-structured focus groups (N=26) with young Canadians (ages 16-24), we investigate how perceived privacy risks (PPR) and benefits (PPBf) intersect with algorithmic transparency and trust (ATT) and privacy self-efficacy (PSE) to shape privacy-protective behaviors (PPB). Our analysis reveals that policy overload, fragmented settings, and unclear data retention undermine self-efficacy and discourage protective actions. Conversely, simple transparency cues were associated with greater confidence without diminishing the utility of hands-free tasks and entertainment. We synthesize these findings into a qualitative model in which transparency friction erodes PSE, which in turn weakens PPB. From this model, we derive actionable design guidance for SVAs, including a unified privacy hub, plain-language "data nutrition" labels, clear retention defaults, and device-conditional micro-tutorials. This work foregrounds youth perspectives and offers a path for SVA governance and design that empowers young digital citizens while preserving convenience.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.04298v1">Privacy at Scale in Networked Healthcare</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2026-01-07T17:58:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> M. Amin Rahimian, Benjamin Panny, James Joshi</p>
    <p><b>Summary:</b> Digitized, networked healthcare promises earlier detection, precision therapeutics, and continuous care; yet, it also expands the surface for privacy loss and compliance risk. We argue for a shift from siloed, application-specific protections to privacy-by-design at scale, centered on decision-theoretic differential privacy (DP) across the full healthcare data lifecycle; network-aware privacy accounting for interdependence in people, sensors, and organizations; and compliance-as-code tooling that lets health systems share evidence while demonstrating regulatory due care. We synthesize the privacy-enhancing technology (PET) landscape in health (federated analytics, DP, cryptographic computation), identify practice gaps, and outline a deployable agenda involving privacy-budget ledgers, a control plane to coordinate PET components across sites, shared testbeds, and PET literacy, to make lawful, trustworthy sharing the default. We illustrate with use cases (multi-site trials, genomics, disease surveillance, mHealth) and highlight distributed inference as a workhorse for multi-institution learning under explicit privacy budgets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.03979v1">SoK: Privacy Risks and Mitigations in Retrieval-Augmented Generation Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-01-07T14:50:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Andreea-Elena Bodea, Stephen Meisenbacher, Alexandra Klymenko, Florian Matthes</p>
    <p><b>Summary:</b> The continued promise of Large Language Models (LLMs), particularly in their natural language understanding and generation capabilities, has driven a rapidly increasing interest in identifying and developing LLM use cases. In an effort to complement the ingrained "knowledge" of LLMs, Retrieval-Augmented Generation (RAG) techniques have become widely popular. At its core, RAG involves the coupling of LLMs with domain-specific knowledge bases, whereby the generation of a response to a user question is augmented with contextual and up-to-date information. The proliferation of RAG has sparked concerns about data privacy, particularly with the inherent risks that arise when leveraging databases with potentially sensitive information. Numerous recent works have explored various aspects of privacy risks in RAG systems, from adversarial attacks to proposed mitigations. With the goal of surveying and unifying these works, we ask one simple question: What are the privacy risks in RAG, and how can they be measured and mitigated? To answer this question, we conduct a systematic literature review of RAG works addressing privacy, and we systematize our findings into a comprehensive set of privacy risks, mitigation techniques, and evaluation strategies. We supplement these findings with two primary artifacts: a Taxonomy of RAG Privacy Risks and a RAG Privacy Process Diagram. Our work contributes to the study of privacy in RAG not only by conducting the first systematization of risks and mitigations, but also by uncovering important considerations when mitigating privacy risks in RAG systems and assessing the current maturity of proposed mitigations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.04280v1">A Privacy-Preserving Localization Scheme with Node Selection in Mobile Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-07T12:48:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Liangbo Xie, Mude Cai, Xiaolong Yang, Mu Zhou, Jiacheng Wang, Dusit Niyato</p>
    <p><b>Summary:</b> Localization in mobile networks has been widely applied in many scenarios. However, an entity responsible for location estimation exposes both the target and anchors to potential location leakage at any time, creating serious security risks. Although existing studies have proposed privacy-preserving localization algorithms, they still face challenges of insufficient positioning accuracy and excessive communication overhead. In this article, we propose a privacy-preserving localization scheme, named PPLZN. PPLZN protects protects the location privacy of both the target and anchor nodes in crowdsourced localization. Simulation results validate the effectiveness of PPLZN. Evidently, it can achieve accurate position estimation without location leakage and outperform state-of-the-art approaches in both positioning accuracy and communication overhead. In addition, PPLZN significantly reduces computational and communication overhead in large-scale deployments, making it well-fitted for practical privacy-preserving localization in resource-constrained networks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.04265v1">You Only Anonymize What Is Not Intent-Relevant: Suppressing Non-Intent Privacy Evidence</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-07T07:54:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Weihao Shen, Yaxin Xu, Shuang Li, Wei Chen, Yuqin Lan, Meng Yuan, Fuzhen Zhuang</p>
    <p><b>Summary:</b> Anonymizing sensitive information in user text is essential for privacy, yet existing methods often apply uniform treatment across attributes, which can conflict with communicative intent and obscure necessary information. This is particularly problematic when personal attributes are integral to expressive or pragmatic goals. The central challenge lies in determining which attributes to protect, and to what extent, while preserving semantic and pragmatic functions. We propose IntentAnony, a utility-preserving anonymization approach that performs intent-conditioned exposure control. IntentAnony models pragmatic intent and constructs privacy inference evidence chains to capture how distributed cues support attribute inference. Conditioned on intent, it assigns each attribute an exposure budget and selectively suppresses non-intent inference pathways while preserving intent-relevant content, semantic structure, affective nuance, and interactional function. We evaluate IntentAnony using privacy inference success rates, text utility metrics, and human evaluation. The results show an approximately 30% improvement in the overall privacy--utility trade-off, with notably stronger usability of anonymized text compared to prior state-of-the-art methods. Our code is available at https://github.com/Nevaeh7/IntentAnony.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.03587v1">Deontic Knowledge Graphs for Privacy Compliance in Multimodal Disaster Data Sharing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2026-01-07T05:02:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kelvin Uzoma Echenim, Karuna Pande Joshi</p>
    <p><b>Summary:</b> Disaster response requires sharing heterogeneous artifacts, from tabular assistance records to UAS imagery, under overlapping privacy mandates. Operational systems often reduce compliance to binary access control, which is brittle in time-critical workflows. We present a novel deontic knowledge graph-based framework that integrates a Disaster Management Knowledge Graph (DKG) with a Policy Knowledge Graph (PKG) derived from IoT-Reg and FEMA/DHS privacy drivers. Our release decision function supports three outcomes: Allow, Block, and Allow-with-Transform. The latter binds obligations to transforms and verifies post-transform compliance via provenance-linked derived artifacts; blocked requests are logged as semantic privacy incidents. Evaluation on a 5.1M-triple DKG with 316K images shows exact-match decision correctness, sub-second per-decision latency, and interactive query performance across both single-graph and federated workloads.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.03546v1">Value-Action Alignment in Large Language Models under Privacy-Prosocial Conflict</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-07T03:30:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guanyu Chen, Chenxiao Yu, Xiyang Hu</p>
    <p><b>Summary:</b> Large language models (LLMs) are increasingly used to simulate decision-making tasks involving personal data sharing, where privacy concerns and prosocial motivations can push choices in opposite directions. Existing evaluations often measure privacy-related attitudes or sharing intentions in isolation, which makes it difficult to determine whether a model's expressed values jointly predict its downstream data-sharing actions as in real human behaviors. We introduce a context-based assessment protocol that sequentially administers standardized questionnaires for privacy attitudes, prosocialness, and acceptance of data sharing within a bounded, history-carrying session. To evaluate value-action alignments under competing attitudes, we use multi-group structural equation modeling (MGSEM) to identify relations from privacy concerns and prosocialness to data sharing. We propose Value-Action Alignment Rate (VAAR), a human-referenced directional agreement metric that aggregates path-level evidence for expected signs. Across multiple LLMs, we observe stable but model-specific Privacy-PSA-AoDS profiles, and substantial heterogeneity in value-action alignment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.03508v2">A Critical Analysis of the Medibank Health Data Breach and Differential Privacy Solutions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-07T01:42:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhuohan Cui, Qianqian Lang, Zikun Song</p>
    <p><b>Summary:</b> This paper critically examines the 2022 Medibank health insurance data breach, which exposed sensitive medical records of 9.7 million individuals due to unencrypted storage, centralized access, and the absence of privacy-preserving analytics. To address these vulnerabilities, we propose an entropy-aware differential privacy (DP) framework that integrates Laplace and Gaussian mechanisms with adaptive budget allocation. The design incorporates TLS-encrypted database access, field-level mechanism selection, and smooth sensitivity models to mitigate re-identification risks. Experimental validation was conducted using synthetic Medibank datasets (N = 131,000) with entropy-calibrated DP mechanisms, where high-entropy attributes received stronger noise injection. Results demonstrate a 90.3% reduction in re-identification probability while maintaining analytical utility loss below 24%. The framework further aligns with GDPR Article 32 and Australian Privacy Principle 11.1, ensuring regulatory compliance. By combining rigorous privacy guarantees with practical usability, this work contributes a scalable and technically feasible solution for healthcare data protection, offering a pathway toward resilient, trustworthy, and regulation-ready medical analytics.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.03429v1">DeepLeak: Privacy Enhancing Hardening of Model Explanations Against Membership Leakage</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-06T21:34:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Firas Ben Hmida, Zain Sbeih, Philemon Hailemariam, Birhanu Eshete</p>
    <p><b>Summary:</b> Machine learning (ML) explainability is central to algorithmic transparency in high-stakes settings such as predictive diagnostics and loan approval. However, these same domains require rigorous privacy guaranties, creating tension between interpretability and privacy. Although prior work has shown that explanation methods can leak membership information, practitioners still lack systematic guidance on selecting or deploying explanation techniques that balance transparency with privacy.
  We present DeepLeak, a system to audit and mitigate privacy risks in post-hoc explanation methods. DeepLeak advances the state-of-the-art in three ways: (1) comprehensive leakage profiling: we develop a stronger explanation-aware membership inference attack (MIA) to quantify how much representative explanation methods leak membership information under default configurations; (2) lightweight hardening strategies: we introduce practical, model-agnostic mitigations, including sensitivity-calibrated noise, attribution clipping, and masking, that substantially reduce membership leakage while preserving explanation utility; and (3) root-cause analysis: through controlled experiments, we pinpoint algorithmic properties (e.g., attribution sparsity and sensitivity) that drive leakage.
  Evaluating 15 explanation techniques across four families on image benchmarks, DeepLeak shows that default settings can leak up to 74.9% more membership information than previously reported. Our mitigations cut leakage by up to 95% (minimum 46.5%) with only <=3.3% utility loss on average. DeepLeak offers a systematic, reproducible path to safer explainability in privacy-sensitive ML.</p>
  </details>
</div>


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
  <h3><a href="http://arxiv.org/abs/2601.02307v2">Differential Privacy for Transformer Embeddings of Text with Nonparametric Variational Information Bottleneck</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-05T17:49:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dina El Zein, James Henderson</p>
    <p><b>Summary:</b> We propose a privacy-preserving method for sharing text data by sharing noisy versions of their transformer embeddings. It has been shown that hidden representations learned by deep models can encode sensitive information from the input, making it possible for adversaries to recover the input data with considerable accuracy. This problem is exacerbated in transformer embeddings because they consist of multiple vectors, one per token. To mitigate this risk, we propose Nonparametric Variational Differential Privacy (NVDP), which ensures both useful data sharing and strong privacy protection. We take a differential privacy (DP) approach, integrating a nonparametric variational information bottleneck (NVIB) layer into the transformer architecture to inject noise into its multivector embeddings and thereby hide information, and measuring privacy protection with Rényi Divergence (RD) and its corresponding Bayesian Differential Privacy (BDP) guarantee. Training the NVIB layer calibrates the noise level according to the utility of the downstream task. We test NVDP on the General Language Understanding Evaluation (GLUE) benchmark and show that varying the noise level gives us a useful trade-off between privacy and accuracy. With lower noise levels, our model maintains high accuracy while offering strong privacy guarantees, effectively balancing privacy and utility.</p>
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
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-01T04:29:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joyjit Roy</p>
    <p><b>Summary:</b> Automated negotiations in insurance and business-to-business (B2B) commerce encounter substantial challenges. Current systems force a trade-off between convenience and privacy by routing sensitive financial data through centralized servers, increasing security risks, and diminishing user trust. This study introduces a device-native autonomous Artificial Intelligence (AI) agent system for privacy-preserving negotiations. The proposed system operates exclusively on user hardware, enabling real-time bargaining while maintaining sensitive constraints locally. It integrates zero-knowledge proofs to ensure privacy and employs distilled world models to support advanced on-device reasoning. The architecture incorporates six technical components within an agentic AI workflow. Agents autonomously plan negotiation strategies, conduct secure multi-party bargaining, and generate cryptographic audit trails without exposing user data to external servers. The system is evaluated in insurance and B2B procurement scenarios across diverse device configurations. Results show an average success rate of 87%, a 2.4x latency improvement over cloud baselines, and strong privacy preservation through zero-knowledge proofs. User studies show 27% higher trust scores when decision trails are available. These findings establish a foundation for trustworthy autonomous agents in privacy-sensitive financial domains.</p>
  </details>
</div>

