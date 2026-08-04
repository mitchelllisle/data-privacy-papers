
<h2>2026-07</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.00282v1">Reflection, Education, Consistency: Towards Best Ethics Practices At Security And Privacy Conferences</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-07-31T20:41:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Florian Hantke, Rafael Mrowczynski, Til Dralle, Ben Stock</p>
    <p><b>Summary:</b> Research ethics is a controversial and emotionally charged topic in the security and privacy community, sparking discussions at conferences and on social media. In recent years, some of the leading conferences have introduced interventions such as mandatory ethics sections, with mixed reactions within the community. Program committee chairs and steering committees increasingly emphasize ethics, yet there is limited empirical validation on ethics procedures and interventions, as well as no explicitly communicated goals.
  To support a shared understanding in our community and guide informed decisions at the conference level, we examined past ethics policies at the top-four conferences and conducted in-depth semi-structured interviews with senior and junior (n=20) community members, including some (former) chairs of program and research ethics committees. In these, we explored reasons for and goals of ethics procedures and discussed existing ethics interventions as well as possible new approaches proposed by our team.
  While the community appears to be evolving toward the identified goals, i.e., raising ethical awareness and preventing the publication of unethical work, we identified the lack of ethical education within the community itself as a major obstacle to further progress on this matter. Ethical education is often passed to the universities. Interviewees also mentioned challenges with the complexity of ethics policies and the lack of consistency across different conferences, as well as policies changing year-to-year. Several participants warned that over-regulation may lead to backlash, encouraging mere compliance, such as people turning to LLMs for ethics sections rather than undertaking in-depth consideration. In response, we suggest a coordinated, community-wide ethics steering effort and take a first step by introducing an open ethics wiki.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.29100v1">StraightDP: Geometry-Aware Differential Privacy for Rectified-Flow Transformers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-07-31T07:27:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xujun Che, Depeng Xu, Xintao Wu</p>
    <p><b>Summary:</b> Differentially private (DP) training of text-conditioned generative models suffers a utility cliff at strong privacy. We revisit this problem through the geometry of rectified flows: along the straight interpolation between noise and data, the Bayes-optimal velocity is governed to leading order at the noise end by a few class-conditional moments, and increasingly sample-specific structure matters toward the data end. StraightDP exploits this heterogeneity end to end. A small budget share releases whitened class-conditional moments once, to be distilled into the weights or injected at sampling time. The rest is spent by pre-declared DP-SGD toward the data end, beyond the moments' reach. At $\varepsilon=1$ on MNIST, the released moments alone already attain $0.76$ downstream accuracy with prototype-like samples and an FID of $237$, and uniform DP-SGD attains $0.21$. The pipeline built on the release reaches $0.81$ accuracy at FID $56$ in a public latent space. Constraining per-token stream norms of the multimodal backbone leaves the pretraining loss unchanged yet improves downstream accuracy in the extreme-noise pixel-space regime, and its accuracy effect becomes monotonically more favorable as privacy strengthens. The released moments also port to frozen SD3-medium, where sampling-time injection beats DP-LoRA training at a fraction of the budget.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.29019v1">GoldenRetriever: Non-Interactive Homomorphic Encrypted Retrieval for Privacy-Preserving RAG</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2026-07-31T04:44:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yang Gao, Gang Quan, Scott Piersall, Qian Lou, Dongdong Wang, Liqiang Wang</p>
    <p><b>Summary:</b> Retrieval-Augmented Generation (RAG) enhances large language models by incorporating external knowledge, but existing pipelines typically operate on plaintext data, raising significant privacy concerns. Prior work on privacy-preserving retrieval leverages cryptographic techniques such as homomorphic encryption (HE) and private information retrieval (PIR), but often relies on interactive protocols or ranking-based selection mechanisms that incur high latency and potential information leakage. In this paper, we propose a practical non-interactive encrypted retrieval framework for RAG based on threshold selection. Instead of performing expensive top-$k$ ranking under encryption, our approach selects documents whose similarity scores exceed a predefined threshold, reducing computational complexity from quadratic to linear in the corpus size. We implement this design using CKKS-based homomorphic computation, enabling fully encrypted similarity evaluation and document selection without revealing query content, intermediate scores, or selected indices. To bridge the gap between approximate encrypted computation and discrete token reconstruction, we introduce a precision-stable mask polarization method that ensures accurate recovery of selected documents. Experiments on standard retrieval benchmarks demonstrate that our approach achieves competitive retrieval effectiveness while significantly reducing latency compared to ranking-based encrypted methods. These results highlight threshold-based selection as a practical foundation for scalable and secure RAG systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.28878v1">YazSes: An Offline, Privacy-First, Cross-Platform Hold-to-Talk Voice-Dictation System</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2026-07-30T22:43:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohsen Seyedkazemi Ardebili</p>
    <p><b>Summary:</b> Cloud voice-dictation services deliver strong accuracy but require streaming a user's speech to a remote provider, an unacceptable trade-off in privacy-sensitive professions and offline or air-gapped settings; the leading on-device alternatives are either platform-locked or aimed at expert scripting rather than plug-and-play dictation. We present YazSes, an open-source (Apache-2.0) hold-to-talk voice dictation daemon that runs entirely on-device, with a single codebase targeting Linux, macOS, and Windows through a protocol-based platform abstraction. YazSes transcribes speech locally with faster-whisper (CPU, int8) and injects the result into the focused application; a fast regex command grammar, backed by an optional small-language-model router, maps utterances to editor and terminal actions. Nothing leaves the machine: recording is push-to-talk rather than always-listening, there is no telemetry, and an opt-in personalization loop keeps its corpus encrypted on-device and proposes configuration changes instead of shipping data out. We describe the system architecture -- a staged pipeline behind a protocol-based platform abstraction with a JSON-RPC control plane -- and its privacy and threat model. We evaluate the shipping Python implementation on a single commodity Linux laptop; the macOS and Windows backends are implemented and unit-tested but not end-to-end evaluated here. On 200 LibriSpeech test-clean utterances spanning 40 speakers, word error rate ranges from 4.82% (tiny.en) to 2.59% (small.en) at a real-time factor of 0.520 for small.en, decoding faster than real time on CPU with no GPU. The command grammar reaches 100% action accuracy with a 0.0% false-positive rate on plain dictation at 0.021 ms per call, and the non-decode pipeline adds 0.289 ms of overhead. The system and the reproducible benchmark harness behind every number in this paper are public.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.28841v1">CyberNeuro: A Privacy-Preserving Agentic Workbench for Cohort-Scale Neuroimage and Clinical Data Analysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2026-07-30T21:10:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ran Ren, Junhong Tong, Yunxi Kong, Yiyao Chen, Yucheng Li, Kunhao Zhou, Shaoqi Wang, Yuxiang Tao, Shuheng Cao, Zhihao Fan, Marissa DiPiero, Tingting Dan, Guorong Wu</p>
    <p><b>Summary:</b> Despite tremendous success in neuroimaging methodology, making large-scale, high-dimensional datasets ready for AI/ML applications remains a critical operational bottleneck. Conventional workflows require extensive manual effort across metadata curation, pipeline execution, post-processing quality control, and data management, a burden that disproportionately excludes laboratories with limited manpower and computational infrastructure. To address this real-world barrier, there is an urgent need for scalable, cost-effective computational platforms that democratize advanced neuroimaging analytics and accelerate discoveries in mental health and clinical translation. Capitalizing on multi-agent LLM breakthroughs, we introduce CyberNeuro, an agentic workbench with a tailored local LLM-model ('WandaMind') for automated neuroimaging and health-data analysis. Driven by four dedicated agents (Planner, Validator, Dispatcher, and Reporter) communicating via a secure MCP bridge and a pinned execution layer, CyberNeuro enables researchers to execute complex workflows using natural language while maintaining clinical-grade data privacy. On the public NeuroBench suite, CyberNeuro increases held-out domain accuracy from 40% to 69% over the baseline model. Beyond automated metrics, the platform integrates a human-in-the-loop verification panel to ensure rigorous biomedical quality control. Across the same end-to-end 10-batch cohort workflow suite, the local WandaMind configuration completed all tasks with an estimated aggregate token count of about 10.6% using WandaMind and 61.7% using cloud providers of token usage, compared to Neuroclaw, respectively. The platform and its production-ready modules are available at https://wanda-cyberbench.com.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.28191v1">Secure Aggregation for Privacy-Preserving Federated Learning on Clinical EEG Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-07-30T13:28:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pouya Rajabi, Mohsen Toorani</p>
    <p><b>Summary:</b> Federated learning enables multiple institutions to train shared models without exchanging raw clinical EEG data, but it does not fully prevent privacy leakage from individual model updates. This paper presents a privacy-preserving federated learning framework for clinical EEG data using masking-based secure aggregation as the core protection mechanism. The framework combines graph-based communication, threshold secret sharing, dropout-resilient aggregation, local update clipping, an optional Bloom filter-based privacy-preserving record-linkage initialization module, and auxiliary-notary-based verifiability. It supports both semi-honest and malicious aggregation settings and is implemented using the Flower federated learning framework. The secure-aggregation variants are evaluated in a simulated cross-silo healthcare setting using TUH EEG-derived data under different client configurations. Under the stated assumptions, the secure variants hide individual updates from the aggregation server. The results show that these variants remain compatible with federated model training, although malicious-setting safeguards and lightweight consistency-checking mechanisms introduce additional computation, communication, and round-duration overhead. The semi-honest variant provides the lowest overhead among the secure configurations, while malicious and auxiliary-notary variants offer stronger consistency, integrity, and lightweight verification support at higher cost.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.27940v2">TriShield: Zero-Utility-Loss Defense Against Privacy Backdoors in Federated Language Model Fine-Tuning via Orthogonal Gradient Projection and Optimizer State Entanglement</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-07-30T09:49:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Cheng Wei</p>
    <p><b>Summary:</b> Federated fine-tuning of large language models (LLMs) enables collaborative training without exposing raw data. However, a recent attack, NeuroImprint, demonstrates that a malicious parameter server can corrupt a PEFT adapter into a privacy backdoor: by assigning a dedicated memorization neuron to each training sample and ensuring each neuron updates at most once, the server can analytically reconstruct 59%--79% of client training data with high semantic fidelity. Existing defenses---including local differential privacy (LDP) and gradient clipping---either fail against this attack or impose unacceptable utility degradation. We present \textbf{TriShield}, a three-layer deterministic defense that completely prevents NeuroImprint-style reconstruction with zero model utility loss and no additional communication rounds. TriShield consists of: (1) a Parameter Artifact Detector that identifies memory-neuron signatures in distributed model parameters before local training begins; (2) a Stateful Virtual Iteration} mechanism that forces Adam/AdamW's momentum state to irreversibly entangle gradients across virtual steps, invalidating NeuroImprint's closed-form inversion; and (3) a Zero-Utility Orthogonal Projection operator that projects all local gradient updates onto the main-task semantic subspace computed via SVD, physically eliminating any gradient components that carry private memorization. We prove theoretically that after Layers 2 and 3, the mutual information between the uploaded gradient and any individual training sample is zero. Experiments on GPT-2 (117M) and Llama-Guard-3-1B verify that TriShield reduces NeuroImprint reconstruction rate to 0% across all tested attack variants, while maintaining or improving training accuracy, with less than 5% additional GPU computation overhead.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.27886v2">Don't Trust the AI Ecosystem: Analyzing Privacy Leakage in Compromised Open-Source Components</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-30T09:02:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jin-Seong Kim, Han-Ju Lee, Seok-Won Hong, Takeshi Takahashi, Chansu Han, Tomohiro Morikawa, Seok-Hwan Choi</p>
    <p><b>Summary:</b> Existing model inversion (MI) attacks predominantly rely on post-training optimization to recover private data from model outputs. However, these methods are fundamentally constrained by the target model's generalization bottleneck, often yielding generic features rather than specific identities, particularly on high-dimensional datasets. In this paper, we introduce GradLock, a novel training-time injection attack that stealthily injects sensitive training data directly into the model parameters. Operating within a compromised supply chain context, GradLock leverages stateless deterministic indexing to establish isolated data vaults and employs dynamic gradient locking to prevent payload degradation during the optimization process. This mechanism allows the adversary to extract pixel-perfect data from the final model without retaining access to the training environment. Extensive experiments on MNIST, Imagenette, and CelebA demonstrate that GradLock achieves near-lossless reconstruction (SSIM ~ 1.0) and instant extraction (< 1.0s). Compared to existing training-time injection methods, our approach exhibits superior robustness against standard deployment optimizations, including quantization, pruning, and fine-tuning. Furthermore, a user deployment study reveals that 93.3% of participants failed to detect the malicious logic, highlighting a severe blind spot in the security of modern AI supply chains.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.27815v1">Robust Estimation of Sparse Numerical Vectors under Local Differential Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-07-30T07:55:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Puning Zhao, Zhikun Zhang, Shaowei Wang, Sheng Yue, Bangzhou Xin, Tianhang Zheng, Pengfei Zhang, Xiaochun Cao</p>
    <p><b>Summary:</b> Local differential privacy (LDP) protocols are vulnerable to poisoning attacks. Existing research have proposed efficient defense strategies for single-item users. However, in practice, a user may possess multiple items. The defense against poisoning attacks for multi-item users is challenging, because due to larger output spaces, the adversary can conduct more powerful attacks without being detected. In this paper, we address the robust sparse vector mean estimation problem, in which each user has a vector with $m$ nonzero coordinates. We propose Randomized Projection with Clipping (RPC). Firstly, the server sends a random binary vector to each user. The user then projects its local data on the vector, and clip the value to restrict the attacker's capability. To handle clipping bias, we propose a correction method based on a careful analysis that gives an exact expression of the bias. As a result, bias-variance tradeoff is no longer needed, thus the clipping threshold can be further reduced to shrink the output space and enhance robustness. We provide a rigorous theoretical guarantee of the estimation error under all possible attacks. Numerical experiments show that under trusted environments, our new method achieves comparable or better performance than existing methods, indicating that our method is already an efficient estimator in its own right. Under untrusted environments, our method is also significantly more robust to poisoning attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.27015v1">Reliability Functions of Quantum Soft Covering and Privacy Amplification via a Mixed-Order Rényi Divergence</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2026-07-29T15:14:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shi-Bing Li, Hongsen Qiu, Xinyu Zhang</p>
    <p><b>Summary:</b> In this paper, we introduce a novel mixed-order Rényi divergence and investigate its fundamental properties. Using this divergence, we define a family of mixed-order order-two Rényi mutual information and Rényi conditional entropy. We derive exact reliability functions of quantum soft covering and privacy amplification under the sandwiched Rényi divergence with order $α\in[2,\infty)$. The former is jointly characterized by the sandwiched and mixed-order order-two Rényi mutual information quantities, while the latter is characterized by the corresponding conditional entropies. These results provide operational interpretations of the proposed mixed-order Rényi divergence. To the best of our knowledge, this is the first exact characterization of the reliability function for quantum soft covering.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.26390v3">Impossible to hide secret ...: Uncovering Security and Privacy Issues in LLM-native IDEs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2026-07-29T01:49:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mostafijur Rahman Akhond, Md Afif Al Mamun, Gias Uddin, Song Wang</p>
    <p><b>Summary:</b> LLM-native IDEs (Integrated Development Environments), aka LIDEs, are designed from the ground up to work with Large Language Models (LLMs). LIDEs have found remarkable success in Software Engineering (SE) tasks such as coding, debugging, and program comprehension. LIDEs are software systems, and, like any system, they can exhibit vulnerabilities. In this paper, we study the security and privacy issues that developers reported while using popular LIDEs in their development tasks. We collected 1.1M posts from 29 popular subreddits related to LIDEs. We identified 446 posts and analyzed over 6K comments to the posts that discussed security and privacy issues in almost all popular LIDEs, such as Cursor, Copilot, Codex, etc. Using a mix of qualitative and quantitative methods, we constructed a taxonomy of the reported security and privacy issues. Our results show that most issues in LIDEs stem from system-level design choices, rather than the underlying LLMs, such as user data access, unchecked autonomous actions, etc. To overcome these issues, developers frequently relied on external safeguards like code sandboxing and manual reviewing, highlighting prevalent mistrust among developers about LIDEs. We share lessons from our study to support future design of secure and privacy-aware LIDEs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.26388v2">Sensitivity and Differential Privacy in Metric Voting with Distortion below Three</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2026-07-29T01:46:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shinsaku Sakaue, Kaito Fujii, Soh Kumabe, Yuichi Yoshida</p>
    <p><b>Summary:</b> Voting rules aggregate individual preferences into collective decisions, but the rankings they receive contain only ordinal information. The metric distortion framework studies ordinal voting rules in settings where voters and candidates are embedded in an unknown metric space. Deterministic rules have optimal worst-case distortion $3$, while recent randomized rules break the $3$ barrier. We study whether such improvements can coexist with low worst-case sensitivity with respect to the Wasserstein distance of lotteries under one-voter deletion and approximate differential privacy under one-voter replacement. On the sensitivity side, we give a randomized rule with distortion at most $3-\varepsilon$ for an absolute constant $\varepsilon>0$ and, for $m$ candidates and $n$ voters, a worst-case sensitivity bound of $O((\log m+1)/n)$. On the privacy side, for every $δ\in(0,1)$ and all $n$ above an absolute constant, we construct a variant rule whose mechanism releasing a single sampled winner has distortion at most $3-\varepsilon$ and is $(O((\log m+\log(1/δ)+1)/n),δ)$-differentially private. Both constructions use the same family of Gibbs distributions over constant-size candidate lists, with only the temperature parameter differing between the sensitivity and differential-privacy guarantees. Our analysis builds on the biased-metric viewpoint behind the recent improvement over the $3$ barrier and proves a stability property for the biased-metric ratio.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.26283v1">HeteroPROPMT: A Real-time and Privacy-Preserving Heterogeneous Collaborative Perception Framework</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E">
  <p><b>Published on:</b> 2026-07-28T21:24:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Armin Maleki, Hayder Radha</p>
    <p><b>Summary:</b> Collaborative Perception (CP) improves autonomous systems' awareness of their surroundings by sharing sensor data, intermediate features, and detection results. In real-world deployments, however, collaborating vehicles often use heterogeneous sensors, perception models, datasets, and training domains, creating feature-space shifts that degrade downstream fusion and detection. Existing approaches typically retrain fusion and detection components or introduce modality-specific feature interpreters. These methods scale poorly to newly joining agents and often require access to proprietary metadata, raising privacy concerns. We propose HeteroPROMPT, a real-time and privacy-preserving framework for heterogeneous collaborative perception. HeteroPROMPT rapidly aligns each heterogeneous agent's features with an ego-centric unified feature space through modular prompts and lightweight learning-based tuning, while keeping agent encoders and the collaborative fusion and detection stacks frozen. Its visual prompt-based training and inference modulate Bird's Eye View (BEV) features across channels and spatial locations with low computational overhead. For metadata-free deployment, an autoencoder learns a compact unified representation and extracts modality cues from shared features, enabling real-time modality classification and routing to the appropriate HeteroPROMPT modules without exposing proprietary agent information. Experiments on the OPV2V-H and V2XSet datasets show that HeteroPROMPT improves Average Precision over state-of-the-art heterogeneous CP methods while using orders of magnitude fewer trainable parameters. This offers a scalable and practical CP solution. The proposed modality classifier also predicts the joining agent's modality from compact features with greater than 99.99 percent accuracy during deployment. Code will be available at https://github.com/arminmaleki007/HeteroPROMPT.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.26207v1">Where Physics Meets Privacy: Federated PINNs for Privacy-Preserving Brain Tumor Biomechanical Modeling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-07-28T19:15:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mahmuda Akter Sristy, Md Al-Mahfuz Chowdhury, Momota Ahsana Meem, Sajid Ahamed, Kazi Irfan Subhan</p>
    <p><b>Summary:</b> Brain tumors such as glioma, meningioma, and pituitary adenoma alter the mechanical behavior of soft brain tissue, yet common diagnostic methods rely on static imaging that cannot capture tumor growth, tissue displacement, or changes in stiffness over time. Deep learning models for this task typically require pooling patient data at one site, which conflicts with privacy rules such as GDPR and HIPAA and limits generalization across institutions, a challenge that is pronounced in neuro oncology given patient diversity. This study presents a federated physics informed neural network combining federated learning with a physics informed loss built on the equations of linear elasticity. Three simulated clinical sites each train a local network on patient specific MRI data using a physics informed loss, and only model weights are shared with a central server through the FedAvg protocol over one hundred rounds, keeping raw data at its site of origin. The federated model reached an overall accuracy of 91.4%, against 90.0% for a non federated baseline trained on pooled data, an average AUC of 0.985 across tumor classes, and a rise in pituitary tumor accuracy from 85.6 to 94.5%. Training produced smooth, divergence free displacement fields consistent with expected tissue deformation, showing that federated training can be paired with physics based constraints without a meaningful loss in performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.25968v1">E-MagDiP: Electro-Magnetic based Differential Privacy for EEG based Community Sensing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-07-28T16:50:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ayanga Imesha Kumari Kalupahana, Vishruti Ranjan, Li-Shiuan Peh</p>
    <p><b>Summary:</b> EEG-based community sensing programs are emerging globally as a tool to leverage aggregated brain data to gain insights into attentiveness of students and employees. But these programs raise privacy concerns because EEG signals contain sensitive personal information. Differential Privacy (DP) can protect individuals while preserving aggregate statistics yet applying DP to EEG data is challenging as it requires user-level noise generation, which increases power and latency. Besides, most commercial EEG headsets cannot be modified to add such noise. We propose E-MagDiP, a framework that uses an external radio to transmit RF signals onto EEG headsets, perturbing signals at acquisition to induce DP noise. To the best of our knowledge, E-MagDiP is the first framework to use RF signals for privacy instead of attacks, enabling practical DP for EEG community sensing without any user-level modification.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.25564v1">To What Extent Can Inherent Communication Noise Guarantee Privacy in Distributed Cooperative Control?</a></h3>
  
  <p><b>Published on:</b> 2026-07-28T10:52:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuwen Ma, Sarah Spurgeon, Tao Li, Boli Chen</p>
    <p><b>Summary:</b> This paper proposes a differentially private distributed cooperative control scheme for multi-agent systems (MAS). Unlike conventional approaches that actively inject artificial noise for privacy protection, this work investigates whether inherent communication noise can itself serve as a natural privacy mechanism. A physically motivated communication-noise model is developed for mobile MAS by incorporating transmitter perturbation, receiver noise, path-loss attenuation, and log-normal shadowing. The resulting effective noise variance depends on inter-agent state differences, thereby capturing the distance-dependent signal perturbation arising in practice. Based on this model, a distributed finite-horizon Linear Quadratic Regulator (LQR) mechanism is designed to achieve formation tracking while protecting agents' private control preferences. Rather than protecting the full local cost function, the proposed privacy formulation focuses on the ratio of the LQR weighting matrices, which captures the trade-off between tracking accuracy and control effort when the quadratic cost structure is publicly known. A set-theoretic sensitivity analysis shows that this weighting-ratio adjacency formulation yields less conservative privacy bounds than gradient-based protection under the considered addition/removal adjacency relation. Theoretical analysis demonstrates that, under suitable design conditions, the proposed mechanism provides bounded cumulative (ε,δ)-differential privacy guarantees for the weighting ratios over an infinite horizon without artificial noise injection. Meanwhile, the cooperative tracking error is shown to converge almost surely and in mean square to a finite random limit, with its expectation remaining bounded. Numerical examples validate the theoretical results and illustrate the resulting privacy-performance trade-off.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.25107v1">MOSAIC-FL, a micro-service based privacy-preserving framework with application to genomics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-07-27T22:09:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Paul Largillier, Karl Paygambar, Cédric Gouy-Pailler, Vincent Meyer, Mallek Mziou, Oana Stan</p>
    <p><b>Summary:</b> Security and privacy are primordial requirements for Federated Learning (FL), especially in fields such as healthcare and genomics where sensitive information has to be analyzed. Our FL framework is designed to address these challenges while proposing a modular, flexible and micro-service architecture. More precisely, it integrates an efficient gRPC communication layer and a Finite State Machine to ensure robust component synchronization and threat detection, while relying on a fault-tolerant secure aggregation protocol using a Threshold variant of the CKKS homomorphic cryptosystem. This allows blind model aggregation by an orchestration server, requiring a minimum of $t$-out-of-$N$ active clients for decryption while minimizing communication overhead thanks to both cryptographic and network protocols. We ensure IND-CPA-D security through noise flooding and mitigate the recent key-recovery attack on synchronized decryptors by renewing the collective key material at every round. We demonstrate the framework's effectiveness through diverse use cases, ranging from standard image recognition (EMNIST) to complex genomic classification including breast cancer subtyping on TCGA, evaluating system performance across different threshold values and model scales.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.24556v1">BettiSplit: Topology-Guided Privacy-Aware Split Learning Against Feature Inversion and Gradient Leakage</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-27T15:29:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Akarsh K. Nair, Muhammad Arifur Rahman, David Brown, Mufti Mahmud</p>
    <p><b>Summary:</b> Split learning enables collaborative model training by partitioning neural networks across clients and servers. However, improper split placement can lead to severe privacy leakage through intermediate representations. In this work, we propose a topology-guided framework for privacy-aware split learning based on the persistent Betti complexity of smashed activations. Through comprehensive layer-wise analysis, we show that privacy risk in split learning is highly non-uniform across layers and exhibits sharp transition regions that are not captured by architectural depth alone. In particular, feature inversion fidelity increases from negligible reconstruction to as high as 0.98 SSIM at deeper, privacy-critical split points. We further demonstrate that Betti complexity consistently identifies representation regimes associated with elevated feature-space privacy leakage across architectures and datasets. Leveraging this observation, we introduce BettiSafe, a topology-guided split selection strategy that identifies privacy-sensitive layers without requiring explicit attack execution. BettiSafe improves resistance to feature inversion by 2 to 5 times compared to depth-based heuristics while preserving classification accuracy. In addition, Betti-based regularisation increases inversion difficulty by nearly 5 x without degrading model utility, enabling a favourable privacy utility tradeoff. Overall, our results highlight topological complexity as a promising structural descriptor for secure, adaptive, and representation-aware split learning in real-world collaborative systems</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.23984v1">Beyond GDPR: Examining Disclosure Gaps in Mobile AR Privacy Policies under U.S. State Privacy Laws</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-27T04:23:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hong Chen, Xueling Zhang, Hong-Ning Dai, Huashan Chen, Qin Yu, Tiange Xie, Duohe Ma, Feng Liu</p>
    <p><b>Summary:</b> Mobile Augmented Reality (MAR) apps can collect and process highly sensitive data such as spatial maps and biometrics, yet their privacy policies remain largely understudied. Prior audits of app privacy policies have typically focused on a single legal framework, such as the GDPR. Meanwhile, 20 U.S. states have comprehensive privacy laws in effect, creating a fragmented and rapidly evolving set of privacy policy obligations. To date, no study has systematically audited privacy policies against this emerging body of state-level legislation.
  In this paper, we present the first large-scale audit of MAR privacy policies under U.S. state privacy laws. We construct a dataset covering the MAR ecosystem, including 8,013 Google Play MAR app metadata records worldwide, and a U.S.-based subset with 6,620 APKs and 6,426 privacy policy files. We further derive an auditable disclosure taxonomy with 5 baseline requirements, 10 triggered requirements, and 4 logic chains, and build a validated four-stage automated pipeline that produces traceable, evidence-grounded disclosure judgments.
  Our audit reveals widespread disclosure gaps: 44.62\% of audited policies exhibit severe disclosure omissions, with each missing more than eight requirements, and four privacy-policy requirements have violation rates above 90\%. These findings suggest that MAR privacy disclosures are not keeping pace with the growing complexity of U.S. state privacy regulation. We release our dataset, taxonomy, and auditing pipeline to support future research on scalable privacy compliance auditing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.23974v1">Sharp Minimax Rates for Smooth Two-Sample Testing under Central Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">
  <p><b>Published on:</b> 2026-07-27T03:54:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ilmun Kim</p>
    <p><b>Summary:</b> We establish sharp minimax limits for two-sample testing of Hölder-smooth densities under central differential privacy. Given two independent samples, the goal is to decide whether the underlying distributions are identical or separated in $L_1$ distance, while releasing only an $\varepsilon$-differentially private decision. We show that privacy changes the classical smooth-testing boundary through multiple regimes: the optimal separation radius is the maximum of four terms, consisting of the classical nonprivate rate and three distinct privacy-induced barriers. Which barrier is active depends on the privacy budget and the smoothness-to-dimension ratio, yielding a sharp phase diagram. Our upper bound discretizes the samples, applies a private discrete two-sample test to the resulting histograms, and chooses the bin resolution to balance approximation bias, sampling fluctuations, and privacy noise. The procedure also admits a permutation-calibrated implementation with finite-sample type~I error control. For the lower bounds, we combine smooth perturbation constructions with privacy-specific coupling and transport inequalities, showing that all four terms are unavoidable. Finally, when the smoothness is unknown, we develop a multiscale private test that attains the optimal adaptive rate and prove a matching lower bound. Adaptation costs exactly an iterated-logarithmic factor, and this cost appears only in the classical nonprivate term.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.23236v1">FedSLIM: Privacy-Preserving Federated MDL-Based Descriptive Pattern Mining Across Data Silos</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-07-25T14:45:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Samar Samir Khalil, Noha S. Tawfik, Marco Spruit</p>
    <p><b>Summary:</b> Federated learning has achieved considerable success for predictive modelling, yet federated descriptive analytics remains largely unexplored. Existing federated pattern mining approaches are predominantly support-based and do not optimise a principled global objective such as Minimum Description Length (MDL). We introduce FedSLIM, the first federated MDL-based framework for descriptive pattern mining. Building on the SLIM principle, FedSLIM enables collaborative optimisation of compact pattern models across distributed databases without sharing raw transactions. We propose two complementary variants that balance privacy, communication, and optimisation fidelity under different deployment assumptions. To evaluate federated MDL mining, we introduce fidelity and discovery-oriented metrics that quantify agreement with a centralised baseline and assess recovery of globally informative patterns. Experiments on multiple real-world datasets under IID and non-IID partitioning show that both variants preserve high-quality compression structure while requiring orders of magnitude less search than the centralised baseline. We further reveal a local-global discovery gap in distributed MDL mining, where globally compressive patterns may be undiscoverable through isolated local optimisation. Both variants recover globally informative patterns absent from all standalone local models, demonstrating the benefits of federated optimisation beyond independent local mining. These results establish federated MDL mining as a practical foundation for privacy-preserving descriptive analytics across distributed data silos.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.23029v1">Multi-Agent Privacy Game in Federated Learning: A Unified Mean-Field View</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-07-25T04:03:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kun Zhao, Xu Chen</p>
    <p><b>Summary:</b> Federated learning enables collaborative model training across distributed clients without centralising their data, yet privacy remains a persistent concern because the shared model updates can leak information about local datasets. Existing privacy-preserving methods either inject calibrated noise into client updates, limiting their composition guarantees, or formulate client privacy choices as a multi-agent game whose Nash equilibrium becomes intractable as the number of clients grows. We bridge these two lines of work by formulating privacy-preserving federated learning as a mean-field privacy game: each client strategically chooses its own privacy budget while interacting with the population only through a single mean-field statistic. The mean-field limit yields a tractable equilibrium for arbitrarily many clients, accommodates heterogeneous client preferences, and inherits an exponentially decaying privacy guarantee through a log-Sobolev contraction. The framework recovers the entropic privacy baseline as the homogeneous special case and the multi-agent privacy game as the finite-population case. Experiments on quadratic regression, logistic regression, and MNIST demonstrate that the proposed framework attains the privacy-utility trade-off of the entropic baseline while delivering a personalized privacy guarantee that the homogeneous baseline cannot express.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.22450v1">A Maximum Entropy Implementation of Differential Privacy Under Linear Invariants</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2026-07-24T16:13:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ryan Lafferty, Anindya Roy</p>
    <p><b>Summary:</b> Differential privacy is the standard for ensuring data privacy and is widely used in major data publications, including reporting results from the U.S. decennial census. Common implementation of differential privacy uses independent Gaussian or Laplace noise addition to the database. However, there could be aggregate (linear) queries to the database that are excluded from the privacy budget, for example, state totals that can not be perturbed due to constitutional mandates. Any implementation of a differential privacy is required to honor these constraints, also referred to as invariants. Under aggregation constraints, the noise vector is no longer independent and the traditional differential privacy guarantees have to be re-evaluated. We propose a high entropy differential privacy implementation that maintains the aggregation invariants with probability one or exponentially close to one and derive the privacy guarantees for the implementation under the invariants. The theoretical proof covers a partial solution to an open question about the null space of correlation matrices. Moreover, the methodology has general use in the context of sampling from normal mixture models under linear equality constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.22270v1">Comparing and Conceptualizing Data Protection Requirements Worldwide for Privacy Regulatory Compliance</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2026-07-24T13:08:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Claudia Negri-Ribalta, Lorena Sanchez Chamorro, Ioana Visescu, Muriel Frank, Anastasia Sergeeva, Alberto García, Rene Noel</p>
    <p><b>Summary:</b> The growing digitalization of society has intensified the collection, processing, and sharing of personal data, increasingly moving across national borders and regulatory jurisdictions, prompting a proliferation of data protection frameworks worldwide. These transborder personal data flows (TPDF) are essential to today's economy, but organizations managing them must reconcile data protection requirements that differ, sometimes subtly, across jurisdictions. For requirements engineering, this is the central challenge: regulatory data protection requirements (RDPRs) are complex and not directly translatable into software requirements, especially when frameworks impose similar, non-identical, or contradictory obligations. Identifying which requirements are shared and which diverge is therefore critical to managing TPDF, and addressing them late in the software development lifecycle (SDLC) causes costly rework, making early identification essential for compliance and stakeholder communication. This paper identifies and conceptualizes common RDPRs worldwide from the perspective of data protection legal experts, answering: (SQ1) which requirements are common across regulations and how are they conceptualized, and (SQ2) which requirements diverge and how do they differ conceptually. We combine deductive qualitative analysis of interviews with 70 legal experts from G20 economies and other countries and systematic content analysis of these economies' data protection regulations. We identify common requirements, such as consent, and divergent ones, such as the right to be forgotten. Given their impact across the SDLC and enterprise architecture, we translate these findings into a set of Data Protection Officer DPO (DPO) stories, using the user story notation, classified by SDLC phase and enterprise architecture layer, to help organizations manage TPDF compliance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.22230v1">trasgoDP: An Open Source Framework for Releasing Noised Tabular Microdata under Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2026-07-24T11:56:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Judith Sáinz-Pardo Díaz, Álvaro López García</p>
    <p><b>Summary:</b> trasgoDP is a modular, open-source, and easy-to-use Python framework for releasing tabular microdata under ε-local differential privacy guarantees, as well as location data under geo-indistinguishability assumptions, designed to be installed and integrated within standard data science workflows. The software enables systematic exploration of privacy-utility trade-offs across multiple mechanisms, data types, and ε values. While differential privacy has been extensively studied for aggregate data, its application to row-wise microdata release remains underexploited in terms of reusable software tools, a gap that is even more pronounced in the case of metric privacy and location-based data. trasgoDP implements local-DP mechanisms for numerical and categorical attributes (Laplace, Gaussian, Exponential, and Randomized Response), a geo-indistinguishability mechanism for location data, and a set of utility metrics, including a novel correlation-loss measure, to quantify information loss as a function of the allocated privacy budget. The objective of this work is to provide the research community with a reproducible, open-source baseline for evaluating tabular and location-based data publication methodologies under formal local differential privacy guarantees.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.21417v1">Towards Privacy-Preserving Federated Prompt Tuning under Data Heterogeneity: A Subspace-Decomposed Expert Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-07-23T15:22:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuhua Wang, Xiaodong Li, Yihao Guo, Yuxiang Jia, Qinnan Zhang, Yifan Sun, Hainan Zhang, Yongxin Tong, Zhiming Zheng</p>
    <p><b>Summary:</b> Federated prompt tuning (FPT) enables collaborative adaptation of vision--language models (VLMs) using lightweight prompts. Existing methods often address heterogeneity and privacy through a split-prompt design under local differential privacy (DP), combining a shared prompt for global transfer with private prompts for local adaptation. However, a single shared prompt may over-smooth diverse transferable knowledge, weakening the balance between personalization and generalization. Multi-expert prompts (MEPs) can better capture this diversity, but enlarge the communicated space, increasing DP noise and communication cost while making robust expert composition more difficult. We propose FedSEPT, a privacy-preserving Fed}erated Subspace-decomposed Expert Prompt Tuning. Specifically, we employ Subspace-decomposed Expert Modeling (SEM) to parameterize multiple prompt experts with shared low-rank factors, a fixed public basis, and private residuals, thereby confining communication and DP perturbation to a compact factor space while enabling direct server aggregation in a common coordinate system. We further design Instance-aware Expert Fusion (IEF), which adaptively combines semantically complementary experts via on-device routing and performs efficient logit-level fusion using cached expert-specific text features. Extensive experiments on 11 heterogeneous benchmarks show that, under the same privacy constraints, FedSEPT achieves a better trade-off between local adaptation and global generalization than strong baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.21393v1">From Read Speech to Spoken Digits: A Task-Specific Evaluation of Speech Privacy With Informed Attackers</a></h3>
  
  <p><b>Published on:</b> 2026-07-23T14:55:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jule Pohlhausen, Anjana Rajasekhar, Anna Leschanowsky, Joerg Bitzer</p>
    <p><b>Summary:</b> Protecting speech privacy in real-life audio recordings is a growing concern. This contribution evaluates the effectiveness of three obfuscation techniques in protecting linguistic speech content, using digit recognition as a task-specific and practically motivated evaluation scenario. As a first baseline, a general-purpose speech recognition model and a digit-specific classifier were applied as informed attackers to recognise both single digits and concatenated digit sequences. Our experimental results demonstrate significant differences in recognition performance across digit modality, speech rate, and attack model. These findings emphasize the need for more comprehensive and application-oriented evaluation methods to ensure speech privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.20727v1">Edit-Neighboring Data Streams and Privacy under Continual Observation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-22T20:54:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joel Daniel Andersson, Anamay Chaturvedi, Monika Henzinger, Roodabeh Safavi</p>
    <p><b>Summary:</b> Differential privacy under Continual Observation (CO) quantifies the loss in privacy that occurs when outputs generated using a stream of sensitive input data are published in the online setting. In this paper, we consider a more stringent notion of privacy compared to prior work wherein an individual's participation may shift the entire stream by a time-step. We define a new notion of edit-neighboring streams that captures this scenario.
  Our findings are as follows. First, we prove that on a stream of length $T$, every additive-noise mechanism incurs error $\tildeΩ(\min\{T^{1/3}/\varepsilon^{2/3}, T\})$ when required to be $\varepsilon$-DP under CO for edit-neighboring streams. This includes state-of-the-art continual counters constructed via the factorization mechanism that in the standard neighboring setting incur only polylogarithmic additive error. Second, we construct the first mechanisms with polylogarithmic additive error for our more stringent notion of privacy. We show that we can recover the same additive error as in the standard notion of privacy albeit with worse constant coefficients for both arbitrary input streams and sparse streams. Third, we show that the notion of edit-neighboring streams inhabits a `sweet-spot' in terms of generality and additive error incurred. More precisely, we show that the even more general notion of prefix-sum neighboring streams---which arises naturally in reductions for problems under CO---must incur additive error scaling as $\tildeΩ(\min\{T^{1/3}/\varepsilon^{2/3}, T\})$ for any mechanism that is $\varepsilon$-DP under continual observation. Finally, we show empirically on synthetic data that when compared with prior work, our mechanism achieves a superior trade-off between the success probability of a simple distinguishing attack, and the additive error incurred by the respective mechanisms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.20692v1">DS@GT ARC at ImageCLEFmed GANs 2026: Geometric Filtering for Privacy-Preserving CT Slice Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-07-22T19:46:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Eric Regina, Richard Arnaud, Samir Hadi Cisneros</p>
    <p><b>Summary:</b> We present a privacy-preserving framework for synthetic lung CT slice generation developed for the Image-CLEFmed GANs 2026 challenge. The approach combines Optimal Transport Conditional Flow Matching with privacy-oriented training and a post-generation "Supervisor" pipeline that filters generated candidates in learned geometric latent spaces using autoencoder embeddings, Determinantal Point Processes, and Stein Kernel Thinning. Official results show a strong realism-privacy trade-off, with the best-performing model achieving a Privacy Preservation Score of 0.549 and competitive visual fidelity with an FID of 0.3290. While the proposed geometric filtering substantially reduces nearest-neighbor memorization and membership-inference leakage, persistent patient re-identification scores indicate that preventing direct image copying is not sufficient to remove deeper patient-specific anatomical identity, highlighting an important frontier for future privacy-preserving medical image generation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.19580v1">End-to-End Differential Privacy in Training Deep Neural Network Classifiers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-21T21:15:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Huaiyuan Rao, Calvin Hawkins, Alexander Benvenuti, Matthew Hale</p>
    <p><b>Summary:</b> Differentially private machine learning enables model training on sensitive data while ensuring that individual data is unlikely to be recoverable from the parameters of the resulting model. However, existing work often privatizes both training inputs and their labels, and these protections may be conservative when labels are public or can be safely made public. Therefore, in this work we propose a novel private training framework that instead privatizes training inputs while keeping labels public. We consider neural networks with softmax output layers, and thus the mapping from training inputs to the output of the softmax layer is a mapping onto the unit simplex. We randomize softmax outputs during training by applying the Dirichlet mechanism to enforce differential privacy for the training inputs, hence the ``end-to-end'' label. Because training data is reused across multiple training epochs, we use the notion of \Renyi differential privacy to formulate tight bounds on the strength of privacy provided by the Dirichlet mechanism across repeated uses. We show empirically that we attain new state-of-the-art accuracy when training from scratch on CIFAR10, MNIST, MedMNIST, FashionMNIST, and SVHN across all privacy budgets evaluated. Notably, when implementing $(ε, δ)$-differential privacy with $δ=10^{-5}$, we improve the prior state-of-the-art accuracy from $78.37\%$ to $88.17\%$ at $ε=4$ on CIFAR10, and our approach has $82.96\%$ accuracy even for $ε=1$, which significantly outperforms prior work.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.19532v1">Trustworthy Privacy-Preserving Multimodal Federated Learning for Personalised Breast Cancer Prediction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-07-21T19:26:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruth Amey, Muhammad Arifur Rahman, Taha Osman, Nicholas Shopland, Andy Burton, Mufti Mahmud, David J. Brown</p>
    <p><b>Summary:</b> Federated learning has emerged as a potential solution to privacy concerns associated with using sensitive health data for training predictive models, particularly in personalised cancer care. This research investigates whether federated learning can support the development of robust models for predicting tumour progression in breast cancer patients while addressing four critical deployment pillars: transparency, scalability, security, and fairness. This study evaluates a federated learning framework using multimodal data, including clinical information, tumour characteristics, biomarker data, and patient demographics, alongside medical imaging data such as MRI scans, to model changes in tumour characteristics over time. The performance of the federated approach was compared with that of a centralised model trained on aggregated data. The report then further examines strategies to enhance secure model updates, maintain performance across patient subgroups, and support scalability across institutions. The findings assess whether federated learning can achieve predictive performance comparable to centralised learning while preserving data locality. These results contribute to understanding the feasibility of privacy-preserving, multimodal predictive modelling and support future applications such as digital twins to assist clinicians and patients in personalised treatment planning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.19146v1">Sarus: Privacy-Preserving Multi-Vendor Perception Fusion via Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-07-21T14:38:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Munawar Hasan, Apostol Vassilev</p>
    <p><b>Summary:</b> Cooperative perception enables autonomous vehicles (AVs) to improve situational awareness by aggregating detection outputs from multiple agents and sensing platforms, often via a shared fusion service in multi-vendor deployments. However, sharing such outputs at inference time exposes proprietary model behavior and sensitive environmental information, creating significant privacy and security concerns. In this paper, we present Sarus, a privacy-preserving framework for multi-vendor perception fusion via homomorphic encryption (HE), enabling aggregation without revealing individual vendor outputs. Each vendor encodes detections as compact Gaussian moment vectors over a shared spatial lattice and transmits encrypted payloads to a fusion server, which aggregates them directly in the encrypted domain. The fused result is then decrypted and reconstructed into final detections through class-wise bin merging.
  We analyze the computational complexity, showing linear scaling for vendor payload construction and $O(BV)$ server-side fusion with the number of occupied bins $B$ and vendors $V$, while postprocessing scales as $O(B + \sum_{c\in \mathcal{C}} B_c^2)$, where $\mathcal{C}$ denotes the set of object classes and $B_c$ is the number of occupied bins for class $c$. Experiments demonstrate linear scaling in practice with only a bounded constant-factor overhead from HE, with decryption dominating postprocessing cost. Experiments on the KITTI dataset using camera (YOLOv8) and LiDAR (PointPillars, PV-RCNN) detectors show that Sarus improves scene-level coverage by effectively aggregating complementary detections, particularly in distance-dependent regimes where individual modalities degrade. These results indicate that privacy-preserving multi-vendor perception fusion is feasible for real-time deployment when statistical compression and spatial sparsity are jointly exploited.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.18424v1">Enabling Multilingual Privacy Policy Audits: Large-Scale Analysis of Spanish Mobile Apps</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-07-20T18:13:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marcos Moran, David Rodriguez, Luka Nenadic, Norman Sadeh, Jose M. Del Alamo</p>
    <p><b>Summary:</b> Automated analyses of privacy policies enable large-scale assessments of transparency in digital ecosystems, yet existing auditing pipelines remain predominantly English-centric. This limits their ability to systematically evaluate multilingual environments, as in the European Union, where many services disclose privacy practices only in local languages. This paper examines whether large language models (LLMs) can extend privacy policy analysis beyond English without requiring language-specific adaptation, thus empowering large-scale auditing in linguistically diverse app ecosystems.
  We assemble an evaluation corpus spanning all 24 official EU languages from translated versions of two established expert-annotated datasets (OPP-115 and MAPP) and assess translation fidelity through automated metrics and targeted legal-expert review. Our LLM-based classifier for identifying categories of personal data collection achieves stable cross-lingual performance, with macro-F1 scores ranging between 0.91 and 0.94.
  We then leverage this capability in a large-scale audit of 2,611 Android applications from the Spanish Google Play Store. Combining multilingual privacy policy analysis with the evaluation of corresponding privacy labels and runtime network traffic exposes an important linguistic barrier: public-sector apps predominantly provide privacy policies in Spanish, whereas popular commercial apps mostly provide them in English. We reveal systematic discrepancies between declared and observed practices, especially in public-sector apps. Overall, our results indicate how English-only privacy audits can systematically obfuscate transparency gaps in multilingual environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.18169v2">RRAM-DP: Device-Calibrated Differential Privacy for In-Memory Edge Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2026-07-20T17:11:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kwunhang Wong, Jichang Yang, Karl M. H. Lai, Hegan Chen, Songqi Wang, Wei Xuan, Ning Lin, Han Wang, Xiaojuan Qi, Zhongrui Wang</p>
    <p><b>Summary:</b> Edge Artificial Intelligence of Things (AIoT) systems often collect sensitive data in situ, raising serious privacy concerns. Resistive-switching random-access memory (RRAM) is an attractive substrate for efficient AIoT thanks to its multi-bit storage and compute-in-memory (CiM) capabilities, while its inherently stochastic write behavior provides a natural source of randomness that can be leveraged for differential privacy (DP) protection. Yet how to transform this device-level randomness-typically viewed as detrimental to accuracy-into a principled randomized mechanism while preserving model utility remains underexplored. We propose RRAM-DP, a hardware-algorithm co-design that relaxes RRAM write-verify operations to inject calibrated noise for inherently (epsilon, delta)-DP with formal DP analysis; together with pretraining techniques, it renders a novel private, high-utility CiM training paradigm. On CIFAR-10/100, STS-B, and SST-2, RRAM-DP-SGD incurs at best only a 3.8% accuracy drop at (epsilon=2, delta=O(1/n))-DP relative to non-private SGD. At the same privacy level, RRAM-DP-SGD delivers up to 57x and 3.2x energy savings and 2.7x and 1.8x speedups over A100 and DiVa-GEMM, respectively. These results point toward efficient, privacy-preserving in-memory training on RRAM at the edge.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.18021v1">Optimal Domain-Aware Privacy Mechanisms for Synthetic Data Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-20T14:54:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sajani Vithana, Sangwon Jung, Haoyang Hu, Viveck R. Cadambe, Flavio P. Calmon, Haewon Jeong</p>
    <p><b>Summary:</b> Differential privacy (DP) imposes fundamental trade-offs between privacy and statistical fidelity in synthetic data generation. While access to public data has been shown to improve these trade-offs empirically, existing approaches use public data only indirectly, through pre-processing (e.g., using pre-trained generative models) or post-processing steps (e.g., matching target statistics estimated from public datasets), while relying on domain-agnostic DP mechanisms. In this work, we lay the theoretical framework to study the principled incorporation of public data into DP mechanisms themselves. We consider normalized histograms as distribution estimators and characterize the asymptotically optimal domain-aware privacy mechanism within a specific class of DP mechanisms. We introduce PubMix, a public-data-aware DP mechanism that can be used in histogram-based data synthesis pipelines. Our experiments demonstrate that PubMix significantly improves synthetic data generation quality compared to domain-agnostic privacy mechanisms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.17958v1">Privacy-preserving causal mediation analysis using distributed electronic health record networks</a></h3>
  
  <p><b>Published on:</b> 2026-07-20T13:59:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hyojung Jang, Rotana Radwan, Malcolm Risk, Yao Lee, Jiang Bian, Xu Shi, Serena Guo, Lili Zhao</p>
    <p><b>Summary:</b> Electronic health record (EHR) networks provide unprecedented opportunities to study treatment mechanisms at scale, but mediation analyses across institutions are often hindered by privacy and governance constraints that restrict sharing of patient-level data. We developed a privacy-preserving federated mediation framework that enables estimation of natural direct and indirect effects without exchanging individual-level records across participating sites. The proposed approach integrates renewable learning with counterfactual causal mediation analysis, allowing institutions to collaboratively investigate treatment mechanisms using only low-dimensional summary statistics. Both simulation studies and the real-world application demonstrated that the federated estimator closely reproduced pooled-data results while preserving patient privacy. We applied the method to 32,146 patients in the Indiana Network for Patient Care to evaluate the extent to which body mass index (BMI) mediates the effect of GLP-1 receptor agonist on glycated hemoglobin (HbA1c) reduction. The BMI-mediated pathway accounted for only a small proportion of the overall treatment effect, suggesting that most glycemic improvement occurred through mechanisms other than weight loss.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.17504v1">DecoyFace: Beyond Obfuscation via Controllable and Imperceptible Identity Misdirection for Privacy-Preserving Face Recognition</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-07-20T03:19:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhihan Ren, Lijun He, Xinyao Wang, Xinzhu Fu, Fan Li</p>
    <p><b>Summary:</b> Split face recognition reduces client-side computation but exposes intermediate features to feature inversion attacks and unauthorized analysis by honest-but-curious (HBC) servers. Existing privacy-preserving face recognition methods mainly aim to resist unauthorized reconstruction, typically producing features whose inversion yields visibly degraded results, which may reveal the existence of protection and motivate adaptive attacks. To address this issue, we propose DecoyFace, an imperceptible decoy-oriented framework that steers unauthorized reconstruction toward a plausible but incorrect identity while preserving recognition utility. The key idea is to decompose the intermediate representation into a reconstruction-sensitive subspace and its complementary subspace. The client injects decoy identity cues into the reconstruction-sensitive subspace, while limited recognition-relevant evidence from the true sample is retained in the complementary subspace. On the server side, an authorized canonicalization module suppresses decoy-dominant components and recovers a recognition-friendly representation. This design addresses both attacker-side inversion from intercepted features and HBC server-side reconstruction from canonicalized representations. Experiments show that DecoyFace preserves competitive recognition accuracy while substantially reducing identity leakage to 2.93% under U-Net attacks and 0.74% under Flow-Matching attacks while yielding visually plausible and imperceptible reconstructions, with over 99.78% face validity on LFW dataset.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.17218v1">SpexPay: A Privacy-Preserving Pay-As-You-Go System for Dynamic Spectrum Sharing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-19T12:20:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohaimin Al Barat, Hexuan Yu, Shaoyu Li, Yang Xiao, Yi Shi, Eric W. Burger, Y. Thomas Hou, Wenjing Lou</p>
    <p><b>Summary:</b> Dynamic Spectrum Sharing (DSS) is a cornerstone of next-generation wireless systems, yet existing solutions such as Spectrum Access Systems (SAS) rely on centralized administrators that expose sensitive operational metadata and lack cryptographic transaction accountability. Though SAS administrators, such as Google, have introduced pay-as-you-go pricing models, these approaches still face significant privacy and accountability challenges as DSS evolves toward a more open and large-scale spectrum marketplace. We present SpexPay, a privacy-preserving and auditable pay-as-you-go spectrum usage framework that enforces fine-grained, usage-linked payments without revealing user identities. Spexpay integrates BBS+ verifiable credentials, unlinkable session pseudonyms, and selective-disclosure proofs to enforce privacy-preserving access authorization, while leveraging Solidity-based smart contracts to realize automated and non-repudiable escrow settlement. By recording only pseudonymous usage evidence and hash-chained metering data on-chain, the system achieves strong unlinkability while preserving verifiable accountability and auditability. A full prototype demonstrates low end-to-end latency ($\approx$150 ms) and modest on-chain cost ($\approx$603K gas or $\approx$\$0.9), showing that SpexPay is practical for real-world DSS deployments. We also evaluated the user-side cryptographic operations on a Raspberry Pi 5 to assess scalability and suitability for edge-class hardware. Our code and artifacts are publicly available at https://github.com/iambarat/SpexPay.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.17098v1">Multi-Level Privacy-Preserving Dementia Detection from Speech via Targeted Adversarial Obfuscation and Representation Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-19T06:48:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Henriette Flore Kenne, Raphael Anaadumba, Mohammad Arif Ul Alam</p>
    <p><b>Summary:</b> Speech recordings used for dementia detection inherently expose speaker identity, raising critical privacy concerns. Existing methods typically address only singular threats and fail to resolve the privacy--utility trade-off. We propose a multi-level framework designed to neutralize two distinct eavesdropping vectors. At the signal level, a Cumulative Signal Attack (CSA) concentrates perturbations in keyword-aligned regions to maximize transcription error (Word Error Rate WER = 1.00) while preserving vital prosodic biomarkers. At the feature level, a Gradient Reversal Layer (GRL) with Mutual Information (MI)-guided noise injection suppresses speaker-discriminative dimensions while retaining dementia-relevant diagnostic structure. Evaluated on the DementiaBank Pitt Corpus, our framework achieves near-chance speaker identification (Equal Error Rate EER = 0.59, F1 = 0.003) while maintaining strong dementia classification performance (F1 = 0.78, AUC = 0.86).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.17075v2">A Systematic Evaluation of Traditional Privacy Policy Analysis Tools Against LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-07-19T04:50:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Madhav Aryal, Sudipa Saha, Sunil Manandhar, Anshuman Chhabra, Kaushal Kafle</p>
    <p><b>Summary:</b> The advent of LLMs has significantly changed the research on privacy policy and data compliance analysis by enabling tasks that previously required specialized, domain-specific tools. However, it remains unclear to what extent LLMs can truly replicate the diverse functionalities, and the wide range of methodologies and analysis offered by prior work. In this paper, we conduct the first systematic evaluation of whether off-the-shelf LLMs can replace specialized privacy analysis tools. We study six representative tools spanning three major functionalities: contradiction detection, regulatory compliance analysis, and privacy policy summarization and aggregation, and across three intermediate tasks: structured data extraction using tuples, Semantic Role Labeling (SRL) and manual privacy policy labeling. We compare the performance of two state-of-the-art LLMs (GPT-5.2 and Gemini-2.5 in various configurations) against the tools by directly prompting the models to perform corresponding functionalities and tasks on a custom dataset of 10 privacy policies, allowing us to assess whether off-the-shelf models can produce tool-specific functionalities without further engineering or domain-specific training, major limitations in prior work. Our results show that LLMs consistently match or exceed the capabilities of existing tools across the functionalities. In manual labeling of first-party collection entities, LLMs achieved an average precision of 81.8% and recall of 70.9%, while for labeling of third-party sharing entities, they achieved an average precision of 91.4% and recall of 70.8% compared to the OPP-115 dataset. Overall, our findings indicate that LLMs can effectively perform a broad range of functionalities and tasks in privacy policy and regulation analysis that previously required specialized tools.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.16710v1">Towards Inference-Aware Privacy Guidance for Data Preparation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2026-07-18T08:55:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vishal Chakraborty, Felix Naumann</p>
    <p><b>Summary:</b> Data preparation often begins with sensitive data and produces a releasable artifact for analysis, sharing, or model training. Existing workflows are primarily guided by utility: a curator drops attributes, coarsens values, filters populations, and suppresses tuples until the resulting dataset appears useful and safe. Privacy, when considered, is usually evaluated only on the final release.
  We propose privacy-aware data preparation as an interactive guidance problem. We model a preparation plan as a sequence of deterministic curation operators and ask how each step changes the evidence available to an observer with prior knowledge about a target. Our semantics is based on compatibility sets, which capture the source tuples still plausible for the target after a released representation is observed. This view separates operators that remove evidence from those that remove ambiguity, explains why privacy effects can be non-monotone, and supports prefix-level feedback under a disclosure budget. The result is an inference-aware foundation for guiding curators throughout data preparation, rather than judging privacy only after the final artifact is produced. We conclude by identifying the key challenges in building interactive, inference-aware data preparation systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.16620v1">Privacy Cost as Equity Input: A Group Fairness Criterion for Differentially Private Machine Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-07-18T03:41:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rakshit Naidu</p>
    <p><b>Summary:</b> Differential privacy (DP) is increasingly deployed to limit membership inference risk in machine-learning systems. Prior work has shown that DP-SGD can widen accuracy disparities across demographic groups, but this framing treats fairness as a purely outcome-side concern. We argue that privacy cost, the information leakage borne by each group, is itself a form of harm, and adopt a compensatory-fairness framework in which a group that involuntarily bears greater privacy exposure is owed proportionally greater benefit from the system. From this principle we derive the \emph{Privacy-Cost Equity Ratio} (PCER), a group fairness metric defined as a group's positive prediction rate normalized by its per-group overfitting gap. By a standard membership inference bound, this overfitting gap upper-bounds each group's vulnerability to inference attacks, making PCER a conservative measure of benefit relative to exposure. PCER needs only per-group train and test accuracy (no shadow models), making it a practical post-hoc audit tool. We evaluate PCER alongside standard fairness metrics across six benchmark--attribute combinations spanning tabular and NLP domains, under DP-SGD at a range of privacy budgets, and validate the overfitting-gap proxy against a direct threshold membership-inference attack. The results reveal patterns that outcome-based metrics miss. On COMPAS, PCER uncovers a persistent double disadvantage: the protected group bears both greater privacy exposure and worse predictive outcomes, something demographic parity gap masks entirely. Sensitivity analysis shows very strong privacy guarantees collapse both groups' overfitting to a numerical floor, rendering exposure-based audits uninformative in that regime. Together, these findings show that fairness audits of privacy-preserving systems must account for who bears the cost of protection, not only who benefits from its outcomes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.22695v1">PANOPTICON: A PII-Based Assemblage of Naturalistic Output Tokens for Investigating Privacy Leakage Within LLM Context Window</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-17T17:23:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ryan Thornton, Mir Mehedi Ahsan Pritom, Maanak Gupta</p>
    <p><b>Summary:</b> Large Language Models (LLMs) are capable of generalizing human language for the completion of never-before-seen tasks, leading to widespread deployment. While this automation provides clear utility, completing these tasks often requires the insertion of Personally Identifiable Information (PII), strings of information that uniquely identify some individual, raising privacy concerns. However, ethics has prevented the curation of a public, authentic dataset of PII. Without an appropriate dataset, it is difficult to quantify privacy risks. Thus, we introduce the PANOPTICON pipeline and dataset. The dataset, generated by Meta's Llama-3.1-8B-Instruct model, contains 67, 718 prompts, intended for the models context window, containing PII spans derived from 9,674 publicly available synthetic user profiles. We measure lexical diversity and S-BERT diversity of the created dataset to evaluate realism. Finally, we present a case study showcasing the utility of PANOPTICON data for understanding Prompt Inversion Attacks (PIAs). PANOPTICON thus emerges as the first benchmark dataset for studying PIAs over private corpora, providing a foundation for future LLM privacy research.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.16351v1">Privacy-Aware Synthetic Video Benchmarking and Relational Evaluation for Worker-Under-Suspended-Load Detection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-07-17T06:20:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anshu Singh, Alejandro Seif</p>
    <p><b>Summary:</b> Publicly shareable construction-video benchmarks remain scarce, especially for safety-critical hazards that are rare, dangerous to stage, and difficult to release. We study worker under suspended load, a relational hazard that depends on worker-load geometry and temporal persistence rather than object detection alone. We introduce SynthSite, a focused synthetic video benchmark of 55 clips spanning varied load configurations, viewpoints, clutter, occlusions, and surveillance conditions, together with a privacy-aware hybrid generation workflow that supports both publicly shareable benchmark creation and privacy-constrained synthetic video generation.
  We then ask whether worker appearance can be suppressed without undermining downstream hazard recognition. Under five whole-body privacy conditions, we evaluate worker and load retention, localization stability, and clip-level hazard recognition. We find that structure-preserving obfuscations retain substantially more downstream utility than appearance-smoothing baselines, and that preserving a raw visual reference alone does not guarantee the strongest agreement with human hazard labels. These findings suggest that privacy evaluation for construction safety analytics should assess not only appearance suppression, but also preservation of the geometric cues required for hazard reasoning. Our dataset and code are available at https://huggingface.co/datasets/govtech/SynthSite .</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.15134v1">Platform Choice, Trust, and Privacy in the Consumer AI Assistant Market</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> 
  <p><b>Published on:</b> 2026-07-16T15:41:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jennifer Zou</p>
    <p><b>Summary:</b> We study how a representative sample of United States adult AI-assistant users (n=1,999; June 2026) choose among platforms, allocate tasks across them, evaluate provider trustworthiness, and value data-handling features. Estimates are weighted to the AI-user population using external adoption benchmarks. Four patterns emerge. The market is concentrated but internally differentiated: ChatGPT is the primary assistant for 58% of users and Gemini for 25%, yet smaller platforms hold defensible task niches--Claude captures a third of coding tasks despite a 7% overall share. Task allocation is thus organized by platform far more than by user, and technical use falls steeply with age. Trust is earned through use rather than reputation: Claude is ranked most trustworthy in every head-to-head among users of both platforms, and shows by far the largest gap between how its users and non-users rate it. Finally, privacy concern is near-universal but action is gated by knowledge, not concern; in a choice experiment users pay most to keep humans--not models--out of their conversations ($11.20/month), with valuations rising in task sensitivity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.14811v1">Is External Database Protection Static in Retrieval-Augmented Generation? Rethinking Privacy Preservation under Dynamic Queries</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-16T10:28:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gang Zhang, Mingyu Tian, Xukun Luan, Yuanchi Ma, Jinyan Liu</p>
    <p><b>Summary:</b> Retrieval-augmented generation (RAG) enhances large language models via external document retrieval, but retrieved contexts may leak sensitive information. Current privacy protection methods typically rely on a document-level static risk assumption, treating all retrieved documents as having the same privacy leakage risk. However, this assumption overlooks a fundamental characteristic of RAG: the privacy risk of a document is highly dependent on the user's query, making privacy leakage inherently query-driven and dynamic. To address this challenge, we propose a Prompt-Aware Dynamic Hierarchical Differential Privacy framework (PA-HDP) for privacy-preserving RAG. PA-HDP first performs a prompt-aware risk hierarchy to dynamically assess privacy risks under different queries. It then applies adaptive sensitive entity replacement and exponential mechanism-based text selection to provide differentiated privacy protection while preserving semantic utility. By protecting only the content that is truly sensitive under a given query, PA-HDP minimizes unnecessary modifications to the retrieval corpus. Extensive experiments on benchmark datasets demonstrate that PA-HDP significantly reduces privacy leakage while maintaining high retrieval quality, achieving a better privacy-utility trade-off than prior methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.14607v1">Auditing Fairness-Privacy Trade-offs: Subpopulation-Level Effects of Fairness-Enhancing Algorithms</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-07-16T06:10:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Umid Suleymanov, Ilhama Novruzova, Khalid Mammadov, Natavan Hasanova, Murat Kantarcioglu</p>
    <p><b>Summary:</b> Machine learning (ML) models deployed in sensitive domains such as healthcare, law enforcement, and finance must satisfy not only utility requirements but also fairness and privacy guarantees. While prior work has largely examined how privacy-preserving techniques affect fairness, the inverse question-how fairness-enhancing algorithms influence privacy leakage-remains underexplored. We present the first comprehensive study of how fairness interventions affect membership inference privacy risks at the subpopulation level. By adapting the Likelihood Ratio Attack (LiRA) for subgroup auditing, we uncover privacy disparities that aggregate evaluations obscure. We further analyze how Differential Privacy (DP) interacts with fairness-enhancing methods across different categories, showing that DP's privacy benefits and utility costs are unevenly distributed across subpopulations. Our results demonstrate that fairness interventions do not uniformly increase privacy risk; their impact depends on model architecture, subgroup size, and mitigation strategy. These findings reveal that fairness, privacy, and utility must be jointly evaluated at the subpopulation level, and we introduce the first unified empirical framework to support such auditing in practice.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.14442v1">Disclosure Divergence: Measuring Privacy Policy and Data Safety Misalignment at Scale</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-16T00:34:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mst Eshita Khatun, Lamine Noureddine, Sideeq Bello, Aisha Ali-Gombe</p>
    <p><b>Summary:</b> With the rapid growth of mobile applications, user data privacy has become an increasing concern. While privacy policies describe how apps collect and share data, platforms such as Google Play provide Data Safety labels intended to summarize these practices. Because these disclosure channels are declared separately, they may present inconsistent representations of app data practices, creating uncertainty for users and regulators. In this work, we conducted a large-scale empirical study of disclosure consistency across 6,051 Android apps. Using an LLM-based extraction framework and a unified schema over 14 Google Play data categories and two operations (collection and sharing), we measure per-app and per-category consistency and introduce a sensitivity-weighted risk score that emphasizes high-risk data types. We find that misalignment disproportionately affects sensitive categories such as personal information and device identifiers, with sharing disclosures exhibiting lower consistency than collection disclosures. Elevated privac risk is concentrated in app categories associated with persistent monitoring and communication. Overall, our findings highlight structural gaps in current disclosure mechanisms and underscore the need for stronger verification and greater transparency in platform-level privacy reporting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.14406v1">Better Privacy Guarantees for Larger Groups</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-07-15T22:44:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jack Fitzsimons</p>
    <p><b>Summary:</b> Pujol and Desfontaines asked whether a private histogram can allow more error on larger counts and use that slack to protect members of larger groups more strongly. We study this question for fixed disjoint groups under add-or-remove-one adjacency. The privacy budget $v(n)$ depends on the affected count, is nonincreasing, and must bound both Rényi-divergence directions at every order. This is the count-dependent form of zero-concentrated differential privacy (zCDP) studied here. The original strict relative-error condition is impossible at count zero. We therefore make the boundary tolerance explicit by requiring $\mathbb{E}\lvert\widehat{x}_i-x_i\rvert < r\max\{x_i,1\}$, without changing the requirement at any positive count. Our main result determines the best dependence on group size. For the upper bound, we directly specialize an existing shifted-transformation framework. The resulting shifted-log Gaussian mechanism has a certified budget $v(n)=O_r(n^{-2})$. Conversely, for every fixed $0<r<1$, any mechanism satisfying the same positive-count utility requirement and count-dependent zCDP must have $v(n)=Ω_r(n^{-2})$. Thus the inverse-square rate is optimal under the repaired formulation. A many-count information argument further places the leading coefficient in the large-count-then-small-error limit between $π/(4e^2)$ and $1/π$, a factor below three. At $r=1$, a data-independent release meets the repaired criterion with zero privacy loss.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.14205v1">Privacy Leakage in Federated Learning in Radiology Reports: A Comparative Evaluation of Tokenizer-Driven Privacy Risks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-15T17:57:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Santhosh Parampottupadam, Andres Martinez, Dimitrios Bounias, Sinem Sav, Klaus Maier-Hein, Ralf Floca</p>
    <p><b>Summary:</b> Federated learning (FL) enables multi-institutional training on clinical text without sharing raw data, but gradient inversion can reconstruct sensitive information from shared model updates. The extent of this leakage for radiology reports, and the role of tokenizer design, remains unclear. We quantify gradient-based text reconstruction in FL and compare privacy risk across three tokenizers with the model architecture held fixed. Six FL clients trained a GPT-2-style transformer (sequence length 32) on public radiology corpora (368,751 diagnostic reports, 98,206 discharge summaries, 1,500 MIMIC-CXR free-text reports) using the GPT-2, RadBERT, and LLaMA-2 tokenizers at batch sizes of 64, 128, and 256. Assuming an active malicious server that modifies the shared architecture before distribution, we applied analytic gradient inversion and measured reconstruction fidelity over five runs. Exact sentence reconstruction ranged from 31% to 44% across tokenizers (30.6-43.5% across the 27 tokenizer x dataset x batch-size cells). At batch size 64 on the Discharge dataset, accuracy was 42.1% (GPT-2), 42.3% (RadBERT), and 39.4% (LLaMA-2), decreasing to 37.3%, 37.2%, and 34.3% at batch size 256. S-BLEU declined as batch size grew (GPT-2: 0.44 to 0.33; RadBERT: 0.48 to 0.35). RadBERT yielded the highest reconstruction fidelity and recovered the most clinical terms (18.1% of a 1,440-term reference vocabulary, vs 12.5% for GPT-2 and 9.4% for LLaMA-2), yet no tokenizer prevented leakage. Substantial portions of report text are therefore recoverable from FL gradients even at larger batch sizes and with domain-specific tokenizers. Tokenizer design influences leakage severity and is a privacy-relevant decision, not only a utility one; safeguards such as secure aggregation and differential privacy are likely necessary to meet HIPAA and GDPR requirements for FL in radiology NLP.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.13754v1">PriEval-Protect: A Unified Framework for Privacy Evaluation and Protection in Healthcare Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-15T12:12:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ilef Chebil, Asma El Hadj, Souheib Yousfi, Aroua Hedhili, Layth Sliman</p>
    <p><b>Summary:</b> Safeguarding patient privacy while enabling meaningful healthcare data use remains critical under GDPR and HIPAA. Existing compliance methods are manual, error-prone, and separate policy audits from data-level assessments. This paper presents PriEval-Protect, a two-phase framework for unified privacy risk evaluation and mitigation. The evaluation phase combines regulatory compliance scoring using a fine-tuned legal LLM with RAG, and technical analysis via encryption type, data architecture, and metrics including similarity, uncertainty, adversary success, and information gain/loss. A composite risk score uses weighted aggregation via Analytic Hierarchy Process. The protection phase recommends countermeasures including federated learning and differential privacy based on assessed risk. Results on hospital documents and datasets demonstrate regulation-aligned, explainable assessments, bridging legal conformance and data-level risk analysis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.13541v1">When T2I Synthetic Data Backfires: Amplified Privacy Risks in Real-Synthetic Mix Training</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-07-15T07:44:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Na Li, Boyu Kuang, Hongsheng Hu, Liquan Chen, Hyoungshick Kim, Yansong Gao, Anmin Fu</p>
    <p><b>Summary:</b> To overcome data scarcity and privacy constraints in data collection, it has become standard practice across academia and industry to augment real training data with text-to-image (T2I)-generated synthetic data, a paradigm we term Real-Synthetic Mix-Training (RSMT). While substituting synthetic data for sensitive real samples is widely regarded as a means to mitigate privacy exposure of the substituted data, the risk to the remaining real samples that actively participate in training has remained largely unexamined.
  This work reveals, for the first time, that RSMT can substantially amplify privacy leakage of these real training samples. We establish a theoretical framework, RSMT Memorization Amplification, proving that incorporating synthetic data displaces real samples toward peripheral regions of the mixed feature space, in turn forcing the model to memorize them more aggressively. Guided by this foundation, we propose RSMixLeak to systematically assess this risk through membership inference attacks (MIAs). RSMixLeak comprises two variants depending on the adversary's capability. The non-adversarial variant audits a benign RSMT pipeline with an honest T2I provider, establishing a lower bound on the leakage induced by the intrinsic gap between real and T2I-generated data. The adversarial variant considers an adversary who controls the T2I model or contributes crafted data to the T2I provider, and deliberately enlarges this distributional gap on a target class via either high-level semantic attribute binding or imperceptible pixel-level coating, further amplifying leakage on real training data while improving downstream model utility. Motivated by these findings, we further propose a lightweight leakage propensity indicator computable from real data alone that reliably identifies high-risk datasets unsuitable for entering RSMT, as a self-assessable mitigation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.13441v1">ReBound: Reuse-Aware Privacy For Interactive Decision Support</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2026-07-15T04:57:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nada Lahjouji, Shufan Zhang, Xi He, Sharad Mehrotra</p>
    <p><b>Summary:</b> Differentially private decision support frameworks answer complex aggregate threshold queries with formal bounds on false negative and false positive rates, but treat each query independently with no memory of past results. In practice, analysts work interactively, issuing sequences of related queries that refine bounds, adjust thresholds, or derive new functions from previous ones. We propose ReBound, a framework that reuses cached results from previous queries to answer new queries at reduced or zero additional privacy cost while maintaining formal utility guarantees. ReBound introduces a reuse framework for multiple refinement types, a cache graph structure for efficient lookup of reusable results, and a negotiation mechanism for when requested bounds cannot be met within budget.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.13328v1">Privacy Preserving Recommender Systems Balancing Personalization with Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-07-14T23:21:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ranjeet K Jha, Venkata Suresh Gummadilli</p>
    <p><b>Summary:</b> Personalized recommendation systems are central to modern e-commerce and retail platforms, but they typically rely on centralized storage of detailed user interaction data, creating significant privacy and regulatory challenges. With increasing requirements from regulations such as GDPR, CCPA, and CPRA, organizations must develop recommendation systems that preserve user privacy without substantially degrading recommendation quality.
  This work presents and evaluates a privacy-preserving recommendation framework that combines federated learning, differential privacy, cohort-level modeling, and privacy-aware intelligent agents. The framework keeps raw user data decentralized while introducing mathematically bounded noise to model updates. Experiments were conducted on synthetic retail datasets that emulate customer clickstream and purchase behavior. Recommendation quality was evaluated using Click-Through Rate (CTR), Precision@K, Recall@K, and Normalized Discounted Cumulative Gain (NDCG@K) across multiple differential privacy budgets.
  We evaluate matrix factorization, neural collaborative filtering, and GRU4Rec under varying privacy constraints and analyze the trade-off between privacy and utility. An interactive Streamlit dashboard was developed to visualize recommendation performance, ranking stability, privacy-utility trade-offs, and fairness metrics. Results show that the proposed framework maintains competitive recommendation quality at moderate privacy budgets (approximately $ε\approx 5$), demonstrating that strong privacy guarantees can be achieved with limited impact on recommendation effectiveness.
  This work provides a practical framework for deploying privacy-preserving recommendation systems that balance personalization, regulatory compliance, and business objectives, offering a scalable approach for next-generation AI-driven retail platforms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.13015v1">Privacy Attacks on Stable Marriage</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2026-07-14T17:55:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stephan A. Fahrenkrog-Petersen, Aleksander Figiel, Darya Melnyk, Tijana Milentijević, Stefan Schmid</p>
    <p><b>Summary:</b> The stable marriage problem appears in many privacy-sensitive domains, for example in the National Resident Matching Program in the US. In such applications, preserving the privacy of users' preference lists is essential to prevent strategic manipulation, discourage misreporting, and comply with data protection regulations.
  In this work, we investigate privacy attacks on stable marriage algorithms. Assuming that the attacker (e.g., the hospitals) can repeatedly interact with the stable marriage algorithm, we demonstrate how such interactions can reveal private preferences of the non-malicious side (e.g., the residents). We show that the widely applied Gale-Shapley Matching Algorithm, where the proposers' side is malicious, is vulnerable to privacy attacks and all honest agents' preferences can be revealed. We further investigate which preference distributions of the honest, non-malicious side are susceptible to privacy attacks and show that the Gale-Shapley Matching Algorithm where the honest side proposes can preserve privacy in non-susceptible preference distributions. We extend our results to the decentralized setting and show that the attacker's side can infer all preference orderings. In an experimental evaluation, we test privacy attacks on synthetic and real-world data and show that real-world data is indeed susceptible to privacy attacks. This work underlines a need for new privacy-preserving stable marriage algorithms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.13122v1">Designing a GDPR-Compliant Security Architecture for Remote Elderly Care Systems: A Privacy-by-Design Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-07-14T17:14:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Md. Rahid Parvez, Mikael Soini</p>
    <p><b>Summary:</b> IoMT-based remote elderly care systems generate continuous streams of sensitive health data, yet existing security architectures have not simultaneously addressed three interdependent challenges: GDPR-compliant edge-layer pseudonymisation, elderly-specific zero-interaction usability as a binding architectural constraint, and integrated STRIDE-based threat validation within a single unified design. This paper presents the Secure Edge Gateway (SEG) framework - a software-simulation-validated integrated IoMT security architecture for elderly care designed to resolve all three dimensions of this tripartite gap simultaneously. An ESP32-WROOM-32 residential gateway enforces MAC address whitelisting, HMAC-SHA256 cryptographic pseudonymisation before any network transmission, AES-128-CBC payload encryption, and TLS 1.3 transport security, in compliance with GDPR Articles 25 and 32. The framework is validated through software-based simulation, full STRIDE threat modelling across all six categories, attack tree analysis, GDPR compliance mapping across nine regulatory obligations, and a Data Protection Impact Assessment (DPIA) under Article 35. Published benchmarks confirm MQTT consumes 6-8% less energy than HTTP in comparable IoT deployments, and edge processing achieves sub-50 ms response latency versus 200-700 ms for cloud-only systems. The results demonstrate that GDPR compliance and operational efficiency are complementary - not competing - objectives in resource-constrained IoMT deployments for elderly care.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.12354v1">Reducing information dependency does not cause training data privacy. Adversarially non-robust features do</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-07-14T05:06:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rasmus Torp, Shailen K. Smith, Adam Breuer</p>
    <p><b>Summary:</b> In this paper, we challenge the prevailing view that information dependency (including rote memorization) drives training data exposure to image reconstruction attacks. We show that extensive exposure can persist without rote memorization and is instead caused by a tunable connection to adversarial robustness. We begin by presenting three surprising results: (1) recent defenses that inhibit reconstruction by Model Inversion Attacks (MIAs), which evaluate leakage under an idealized attacker, do not reduce standard measures of information dependency (HSIC); (2) models that maximally memorize their training datasets remain robust to MIA reconstruction; and (3) models trained without seeing 97% of the training pixels, where recent information-theoretic bounds give arbitrarily strong privacy guarantees under standard assumptions, can still be devastatingly reconstructed by MIA.
  To explain these findings, we provide causal evidence that privacy under MIA arises from what the adversarial examples literature calls ``non-robust'' features (generalizable but imperceptible and unstable features). We further show that recent MIA defenses obtain their privacy improvements by unintentionally shifting models toward such features. To establish this causal relationship, we introduce Anti Adversarial Training (AT-AT), a training regime that intentionally learns non-robust features to obtain both superior reconstruction defense and higher accuracy than state-of-the-art defenses. Our results revise the prevailing understanding of training data exposure and reveal a new privacy-robustness tradeoff.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.12288v1">$\mathrm{P}^{3}$CDA: Privacy-Preserving and Provably Secure Cross Domain Authentication Scheme for Internet of Drones</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-14T02:48:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chengqi Hou, Beibei Li, Ziqing Zhu, Yang You, Licheng Wang</p>
    <p><b>Summary:</b> With the rapid expansion of the Internet of Drones (IoD) and the increasing mobility of drones, cross-domain interactions among geographically distributed domains have become inevitable. Cross-domain authentication is therefore a fundamental security requirement for IoD. However, existing authentication schemes often struggle to simultaneously achieve strong security, high efficiency, and identity privacy, making them unsuitable for the stringent requirements of highly dynamic and resource-constrained IoD environments. To address this challenge, we propose $\mathrm{P}^{3}$CDA, a privacy-preserving and provably secure cross-domain authentication scheme. First, we design an efficient pseudonym management mechanism that supports adaptive pseudonym generation as well as batch registration, verification, and revocation. Second, we propose a structurally enhanced Merkle Hash Tree (MHT) that supports batch pseudonym updates, thereby reducing the pseudonym storage overhead of drones. Building on these components, we develop a cryptographic accumulator-based cross-domain authentication protocol that enables anonymous authentication with authorized pseudonyms while preserving the traceability and efficient revocation of malicious drones. We rigorously analyze the security of $\mathrm{P}^{3}$CDA and formally prove its security under the Canetti--Krawczyk (CK) adversary model. Extensive experiments demonstrate that $\mathrm{P}^{3}$CDA achieves lower computational, communication, and storage overhead than state-of-the-art schemes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.13093v4">Efficient and Privacy Aware Edge Cloud Collaborative Inference for Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-07-14T01:17:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Cheng Li, Jiexiong Liu, Yixuan Chen, Yi Li</p>
    <p><b>Summary:</b> On-device LLM inference faces a trilemma of response latency, limited hardware resources and user privacy. Full cloud inference delivers strong computing power but exposes user prompts and dialogue data, while standalone on-device inference is unfeasible for most consumer and embedded edge devices. This paper presents a privacy-centric edge-cloud collaborative LLM inference framework built on endpoint-authenticated KV cache. Local endpoints handle input preprocessing, embedding computation, adaptive feature optimization, KV cache authentication, speculative decoding and low-dimensional model head calculation, while the cloud conducts authenticated decoder inference, KV cache management, token verification and high-dimensional vocabulary projection. Endpoints fuse partial outputs, apply language-adaptive masking and sample target tokens. All transmitted data and truncated logits are quantized and AES-GCM encrypted for privacy, with core lightweight modules, draft parameters and cache access policies kept local to avoid leakage. The framework supports heterogeneous devices including CPU-only, GPU-equipped and embedded devices via optimized streaming, batching and quantized ONNX deployment. Evaluations demonstrate that the framework reduces per-token latency by up to 46.1\% and downlink payloads by up to 67.4\% over baseline split inference, retaining comparable performance to full cloud inference.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.12246v1">Proximity Features: Privacy-Compliant Cold-Start Personalization at Airbnb</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-07-14T01:17:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wei Jiang, Bin Xu, Hui Gao, Bharathi Thangamani, Weiwei Guo, Sundar Srinivasavaradhan, Tracy Yu, Huiji Gao, Michael Kinoti</p>
    <p><b>Summary:</b> Personalization in two-sided marketplaces relies heavily on user-level features, yet for platforms with infrequent, high-consideration purchases, a large fraction of users lack sufficient history for effective recommendation, spanning both paid and organic channels. At Airbnb, a substantial share of search requests comes from logged-out or first-time users, with this challenge especially pronounced on paid-channel landing pages, leaving traditional user-level features unavailable for a large fraction of traffic. Privacy regulations and increasing restrictions on third-party cookies further limit identifier-based tracking for non-essential use cases. This paper introduces Proximity Features, a privacy-compliant feature system that groups users by geographic proximity using geo-IP data and an adaptive clustering algorithm, producing aggregated user-level signals for groups of approximately 1,000 nearby users without requiring a persistent individual identifier at inference time. Privacy is preserved by design: the pipeline operates on consented, aggregated data only within consent-gated privacy controls.
  The system is deployed in production at Airbnb, serving multiple surfaces including marketing landing pages and destination recommendation, with engagement emails integration under way. Online A/B experiments demonstrate statistically significant lifts in bookings, with the largest gains observed among users with absent or stale history.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.16300v1">FedDP-PALD: A Privacy-Preserving Federated Latent Diffusion Framework with Prototype Aggregation for Medical Data Synthesis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-07-13T21:04:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Md. Sajeebul Islam Sk., Khan Enaet Hossain, Md. Mehedi Hasan Shawon</p>
    <p><b>Summary:</b> Medical images and physiological signals provide valuable information for accurate diagnosis. Developing diagnostic models often requires patient data from multiple institutions, although strict privacy regulations limit the sharing of sensitive clinical records. Federated learning enables multiple hospitals to train a shared model without exchanging raw data. However, existing methods face two problems: the information exchanged during training can reveal whether a patient's data were used, and synthetic data meant to replace real records often fail to preserve their predictive structure, which limits clinical use. To address this issue, we propose FedDP-PALD, a privacy-preserving federated latent diffusion framework for multimodal medical data synthesis under formal privacy guarantees. It jointly processes chest X-ray images and electrocardiogram (ECG) signals through gated multi-head attention with modality-availability masks, remaining effective even when a modality is missing. We also introduce Differentially Private Prototype Mixture Aggregation (DP-PMA), which clips class-level latent prototypes and adds calibrated Gaussian noise before combining them on the server to maintain $(ε, δ)$ differential privacy. We evaluate FedDP-PALD on PneumoniaMNIST, ChestMNIST, and MIT-BIH datasets, where differential privacy reduced summary-level attack AUROC from 0.6229 $\pm$ 0.0026 to between 0.5016 and 0.5093 for privacy budgets from $ε= 1$ to $ε= 8$. On the test data, synthetic-latent training achieved an F1 score of 0.8993 $\pm$ 0.0006 and an AUROC of 0.9057 $\pm$ 0.0503, close to the 0.9747 $\pm$ 0.0132 real-latent training. These results show that FedDP-PALD generates private synthetic representations that preserve useful decision performance while strongly resisting membership inference.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.13088v1">Securing LLMs in the Wild: Privacy and Security Challenges at the Edge</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-07-13T16:45:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ren-Yi Huang, Mingchen Li, Dumindu Samaraweera, Morris Chang</p>
    <p><b>Summary:</b> Large Language Models (LLMs) are rapidly moving from research settings into the wild, deployed on enterprise infrastructure, personal devices, and edge platforms. While cloud deployments offer scalable compute, concerns over data sovereignty, compliance, latency, and third-party dependence are driving organizations toward edge and on-premise LLMs. This shift introduces new security and privacy challenges: limited compute and memory force aggressive optimizations, including quantization, pruning, model partitioning, and parameter-efficient adaptation, each of which can introduce vulnerabilities and reshape the threat landscape. We describe this tension as the Security-Efficiency Paradox, mechanisms that improve efficiency may weaken robustness, expose new attack surfaces, or increase privacy risks. We examine how compression can degrade safety alignment, how partitioned inference enables reconstruction attacks, and how continuous local adaptation may cause privacy leakage and model drift. To analyze these risks, we introduce a deployment-centric taxonomy organized around three architectural constraints: the Memory Wall, the Quadratic Wall, and the Compute Wall. We derive a unified constraint model that quantifies when unsafe optimizations become unavoidable, linking each wall to specific attack surfaces. Building on this model, we propose the Secure Operational Efficiency Score (SOES), a holistic metric balancing task accuracy, jailbreak resistance, and privacy against energy, memory, and latency, enabling practitioners to configure edge LLMs under real-world hardware limits. We further present a practical decision procedure and targeted mitigations for each optimization-induced vulnerability. Together, these contributions provide a co-designed framework for jointly evaluating security, privacy, and efficiency, laying a foundation for securing edge-native intelligent systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.11600v1">Privacy-Aware Collaborative and Distributed Bayesian Optimization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2026-07-13T14:25:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aditya Rane, Sathwik Yamana, Paritosh Ramanan, Srikanthan Ramesh, Akash Deep</p>
    <p><b>Summary:</b> We propose a collaborative meta-learning framework for distributed Bayesian optimization matching centralized performance without raw-data exchange. We show gradient sharing leaks client observations, with leakage worsening as the search converges and queries concentrate near the optimum. We evaluate a differentially private defense and characterize its privacy-utility trade-off.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.11302v1">Information geometric quantification of effective privacy in quantum metrology</a></h3>
  
  <p><b>Published on:</b> 2026-07-13T09:18:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Luca Bianchi, Shimpei Yamaguchi, Wojciech Roga, Davide Bacco, Masahiro Takeoka</p>
    <p><b>Summary:</b> Privacy of a quantum metrological protocol concerns the extent to which single parameters can be kept inaccessible to an observer or to other users of the network. In this work, an information geometric framework is developed to quantify privacy and accessibility of functions of parameters effectively, that is, up to a finite accuracy in state discrimination. Both quantities are defined by measuring volumes in the parameter space induced by the underlying quantum states. This construction subsumes previous definitions of privacy based on the degeneracy of quantum Fisher information, naturally encompassing imperfect implementations. Using extended-GHZ states as a representative example of a quantum network scenario, privacy and accessibility are characterized by quantum correlations and accuracy, providing scaling laws depending on imperfect measurements and entanglement.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.10709v1">PromptGraph: Graph-Guided Prompt Sanitization for Balancing Privacy and Utility in LLM Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-07-12T11:04:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chen Gu, Hui Wan, Donghui Hu, Hui Wang, Zhuoer Gu</p>
    <p><b>Summary:</b> Large Language Model (LLM) services introduce a fundamental privacy challenge. Sensitive information may be inferred not only from explicit identifiers, such as names or phone numbers, but also from contextual associations among otherwise innocuous spans. Existing sanitizers typically assign privacy or utility signals to individual spans without explicitly modeling pairwise relationships among them. In this paper, we propose PromptGraph, a graph-guided prompt-sanitization approach for privacy-preserving LLM inference. PromptGraph estimates privacy leakage at the span level and utility-relevant contextual dependencies between pairs of spans. It represents each prompt as an attributed graph, in which nodes carry span-level privacy scores and edges encode contextual dependencies needed to preserve utility. The sanitization objective selects a protected span set that maximizes privacy gain while penalizing the loss of contextual dependencies. This formulation explicitly balances privacy and utility when contextual evidence is hidden. Protected spans are sanitized locally, and returned placeholders are restored only after passing local consistency checks. We conduct extensive experiments showing that PromptGraph achieves a more favorable balance between privacy and utility than prompt-privacy baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.10467v2">Toward Production-Ready Federated Learning in Healthcare: Privacy, Orchestration, and Governance in MLOps</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-07-11T20:14:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sakshi Gorkhali, Jonesh Shrestha</p>
    <p><b>Summary:</b> Healthcare organizations often cannot freely centralize patient data because medical records are sensitive, regulated, and institutionally controlled. Federated learning offers a practical alternative by allowing hospitals and clinics to train a shared model while keeping raw data local. However, federated learning is not automatically production-ready or private by default. Model updates can still leak information, and decentralized training introduces operational challenges in deployment, monitoring, rollback, debugging, and governance. This paper examines how MLOps practices and the emerging idea of Federated Learning Operations (FLOps) can make federated healthcare machine learning systems scalable, reliable, and trustworthy. It answers three research questions: how containerization and orchestration support federated deployment, how privacy-preserving mechanisms affect trade-offs among privacy, utility, scalability, and operational complexity, and which post-deployment practices are most important for long-term governance. The central argument is that federated healthcare ML requires more than privacy-preserving algorithms. It needs an integrated MLOps architecture that combines reproducible deployment, secure orchestration, model versioning, audit logging, drift monitoring, heterogeneity management, and clear governance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.10329v1">Imperceptible and Reversible Adversarial Examples against Vision-Language Models for Privacy Protection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-07-11T14:13:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qi Lu, Ziqi Zhou, Yufei Song, Zijing Li, Lulu Xue, Minghui Li, Shengshan Hu, Leo Yu Zhang</p>
    <p><b>Summary:</b> Vision Language Models (VLMs) offer powerful multimodal ability but also expose users to text-based privacy attacks where adversaries crawl online photos and query VLMs to extract sensitive attributes. Existing reversible adversarial example (RAE) methods protect images in purely visual tasks but fail in multimodal settings, and current adversarial examples on VLMs rely on high frequency noise that severely degrades visual quality. We propose CloakDiff, the first framework for reversible, high fidelity privacy protection against text-based query attacks in VLMs. CloakDiff produces imperceptible adversarial examples by combining diffusion based adversarial editing with an invertible network that embeds the original image for lossless recovery. It perturbs both pixel space embeddings and manipulates latent cross attention maps to ensure strong cross-model and cross-prompt transferability while preserving global visual structure. To further enhance fidelity, we design EDM Heuristic Sampling, a principled diffusion schedule for adversarial guidance. Experiments on multiple datasets and VLMs demonstrate that CloakDiff delivers multimodal privacy preservation with high visual quality and reversibility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.09391v1">Federated Learning Architecture: Data Privacy and System Security Approaches</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-10T13:15:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Cagdas Karatas, Hibanur Karadogan, Ahmet Yasin Ertug, Busra Buyuktanir, Kazim Yildiz, Gozde Karatas Baydogmus</p>
    <p><b>Summary:</b> This study explores the integration of homomorphic encryption and differential privacy techniques to enhance data privacy and security in Federated Learning (FL) systems. FL allows data to remain on local devices, eliminating the need for centralized data collection; however, sensitive information may still be leaked during model updates. To address this issue, homomorphic encryption enables computations on encrypted data, while differential privacy prevents the extraction of individual information through statistical techniques applied to model outputs. The proposed architecture was tested on the Framingham, Pima Indians Diabetes, and Bank Marketing datasets, revealing that enhanced privacy can be achieved without significantly compromising model accuracy. Furthermore, the impact of data heterogeneity among clients on model performance was analyzed, and it was concluded that strategies such as the careful selection of differential privacy parameters and training settings, along with the use of larger datasets, can improve the efficiency of FL. The findings demonstrate that privacy-preserving and high-performance artificial intelligence systems can be securely applied in sensitive domains such as healthcare and finance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.09022v1">Privacy Detective: A Narrative Game that Cultivates Student Developers' Privacy Awareness by Harnessing Legal Documents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-07-10T01:07:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shao-Yu Chu, Jennifer Forsyth, Xu Wang, Haojian Jin</p>
    <p><b>Summary:</b> Developers' choices about what data a system collects, how it is used and shared, and what defaults govern user choices directly shape users' privacy experiences. Yet, developers often make problematic privacy-related design decisions without realizing the potential consequences. We introduce Privacy Detective, a narrative investigation game that leverages real-world legal documents to train developers' privacy awareness. In the game, players search for privacy violation evidence derived from legal documents and organize this evidence into privacy violation reports using curated templates. We evaluated Privacy Detective in a between-subjects study with student developers, comparing it against a baseline in which participants read raw FTC legal documents. Participants in the game condition identified more true violations than the baseline group, flagged fewer non-issues, and provided more complete justifications for the violations they reported.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.08809v1">Privacy-Preserving Intent Fulfilment and Assurance for 6G RAN</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-07-09T17:13:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joss Armstrong</p>
    <p><b>Summary:</b> Intent-based network management is the emerging paradigm for 6G service lifecycle automation, with the 3GPP intent management framework (TS~28.312) defining creation, translation, fulfilment, and assurance stages. Existing fulfilment and assurance approaches require deep packet inspection, per-flow state tracking, or access to vendor-internal node telemetry to verify that provisioned resources satisfy expressed intents. These requirements conflict with regulatory constraints (GDPR, ePrivacy Directive) in multi-tenant networks and with vendor opacity in multi-vendor O-RAN deployments.
  We present an architecture for privacy-preserving intent fulfilment and assurance in which a coordinator provisions resources from declared intent categories without traffic inspection, and verifies fulfilment using only aggregate standardised PM counters at the O1 interface. A data-processing inequality argument shows that the resource allocation reveals at most $\log_2 K$ bits about traffic content, where $K$ is the number of intent categories. We define two architectural privacy properties, intent-traffic unlinkability and node-opaque verification, and show that both hold by construction. Node-opacity does not sacrifice detection power: the aggregate verifier weakly dominates the per-agent verifier under a homogeneity condition.
  We map the architecture to the 3GPP intent lifecycle and the O-RAN Non-RT RIC, identifying the concrete interfaces, data objects, and deployment points at which the mechanism operates. On production PM counter data from four operator networks, increasing intent-category granularity sharpens provisioning but weakens assurance, consistent with the theoretical prediction that the privacy ceiling is a structural side effect of the detection constraint rather than a separate design parameter.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.08659v2">EdgeRefine: Privacy-Utility Balance for Graphs via Jaccard Sampling under Edge Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-07-09T16:28:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenxiu Ding, Muzhi Liu, Zheng Yan, Mingjun Wang, Yifan Zhao, Qiao Liu</p>
    <p><b>Summary:</b> Graph Neural Networks (GNNs) have shown considerable success in learning from graph-structured data, but their use in privacy-sensitive areas remains difficult because graph structure can leak sensitive link information. To satisfy edge-level differential privacy, a common approach is to inject noise into all elements of the graph's adjacency matrix, thereby obfuscating the existence of any single edge. However, stronger privacy requires more noise, and excessive noise reduces utility, making the privacy-utility balance a major barrier to practical privacy-preserving graph learning.
  To address this issue, we propose EdgeRefine, a local differential privacy framework that improves this trade-off through adaptive edge refinement. EdgeRefine first estimates edge-existence probabilities using Jaccard similarity and ranks edges for noisy edge removal. To ensure the sparsity and reliability of the final graph, it uses the privacy budget $ε$ to determine the ratio of true to false edges, samples them separately based on this probability ranking, and controls the total number of edges with a separate sampling rate $k$. Extensive experiments show that EdgeRefine achieves accuracy comparable to the noise-free baseline and substantially outperforms other privacy-preserving methods across datasets and GNN architectures. Under privacy budget $ε= 2.5$, EdgeRefine improves node classification accuracy over state-of-the-art baselines by 17.8\% on ACM under GAT and 19.7\% on Cora under GCN. In graph classification, it achieves an average accuracy degradation of around 5\% compared to the noise-free baseline. Under graph reconstruction attacks, EdgeRefine maintains relative absolute error levels above 1 across all privacy budgets, averaging 1.962 on Cora and 1.472 on AMAP, indicating strong resilience against privacy leakage.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.08595v1">Federated Deep Learning for Privacy-Preserving Cardiovascular Disease Risk Prediction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-07-09T15:29:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hyunho Mo, Djura Smits, Mahlet A. Birhanu, Maarten J. G. Leening, Daniel Bos, Pim van der Harst, Esther E. Bron</p>
    <p><b>Summary:</b> Cardiovascular disease risk prediction models often rely on data from a single institution or centrally pooled datasets. Extending these models across institutions could be limited by privacy regulations and constraints on sharing patient-level data. Federated learning enables collaborative model development without transferring sensitive patient data, but its application in healthcare remains challenging because datasets often differ in size, population characteristics, and outcome definitions. In this study, we present a federated deep learning approach for privacy-preserving cardiovascular disease risk prediction that integrates two population-based cohorts with different characteristics: Lifelines, including 148,230 participants meeting the study inclusion criteria with self-reported outcomes, and the Rotterdam Study, including a smaller cohort of 10,155 participants with digitally linked clinical outcomes. Model performance was primarily evaluated on the Rotterdam Study because of its complete follow-up. Deep survival models trained using federated learning achieved higher predictive performance than models trained locally without federation. For the Rotterdam Study, the C-statistic increased from 0.728 (95% CI: 0.717-0.739) to 0.739 (95% CI: 0.728-0.749). For Lifelines, the C-statistic increased from 0.783 (95% CI: 0.775-0.791) to 0.787 (95% CI: 0.780-0.792). These findings suggest that federated deep learning across heterogeneous cohorts can improve cardiovascular disease risk prediction while preserving the privacy of individual-level patient data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.08440v1">Coded Task Offloading for Fluid Computing: A Privacy-Aware Approach under D2D Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-07-09T13:02:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Diego Cajaraville-Aboy, Manuel Fernández-Veiga, Ana Fernández-Vilas, Rebeca P. Díaz-Redondo</p>
    <p><b>Summary:</b> Fluid Computing aims to support distributed applications execution across heterogeneous cloud, edge, and device resources, motivating task execution mechanisms that adapt to dynamic and privacy-sensitive environments under runtime conditions. In this context, current task offloading schemes rarely address privacy risks and information leakage under adversarial execution settings; furthermore, most coded computing proposals focus on straggler mitigation without considering system-level objectives such as energy awareness. This paper proposes a coded task offloading scheme for D2D networks under stochastic task arrivals and queue-based dynamics. The proposal combines task offloading techniques with linear secret sharing schemes, where tasks are encoded into redundant shares to support threshold-based recovery, straggler mitigation, and privacy preservation while enhancing system performance. Then, we formulate a privacy-aware offloading problem that jointly optimizes delay and energy while penalizing the theoretical privacy leakage of coded tasks under noisy leakage observations. The problem is solved using a branch-and-bound solver alongside a lightweight heuristic scheduler, both of which are evaluated through a discrete-event simulator. Results show that coded offloading improves the delay--energy trade-off with respect to classical full and parallel offloading schemes, while the heuristic achieves near-optimal performance, outperforming baseline and state-of-the-art solvers. The results also show how privacy leakage penalties reshape offloading decisions, exposing an inherent delay--energy--privacy trade-off.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.08402v1">Swapping Faces, Saving Features: A Dual-Purpose Pipeline for Pedestrian Privacy in ITS</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E">
  <p><b>Published on:</b> 2026-07-09T12:27:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Roba H. Farouk, Catherine M. Elias</p>
    <p><b>Summary:</b> Large-scale and diverse datasets are needed to train AI models to take real-time decisions for autonomous vehicles (AVs), an intelligent transportation system (ITS) application. Pedestrian intention and trajectory prediction are critical models used in AVs, requiring datasets involving diverse pedestrian images. Unrestricted access to these datasets imposes serious security risks, like identity theft and pedestrian tracking. The challenge is to apply privacy preservation procedures while maintaining the image attributes needed to train the models. Existing privacy methods may preserve the pedestrian's privacy, but degrade the image usability, which hinders the models' effectiveness. This work's focus is to implement a five-stage pipeline to protect pedestrians' privacy through face swapping while keeping the essential facial attributes intact. It should be tailored to satisfy the privacy needs of the Egy-DRiVeS dataset. Moreover, Roop and Ghost-v2 face-swapping models are evaluated. Provenly, Roop outperforms Ghost-v2 in various aspects, as will be discussed. Consequently, Roop is the face-swapping model to be used in the pipeline to strike the balance between pedestrian privacy via identity concealment and data usability via facial attribute preservation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.08282v1">Multi-Agent Firewall Architecture for Privacy Protection of Sensitive Data in Interactions with Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2026-07-09T09:23:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hugo García Cuesta, Pablo Mateo Torrejón, Alfonso Sánchez-Macián</p>
    <p><b>Summary:</b> While Large Language Models (LLMs) have become essential productivity tools, their integration into workflows without adequate safeguards creates significant risks. This paper proposes an open-source, privacy-focused, user-facing firewall designed to secure both web-based and programmatic LLM interactions. The architecture combines a browser extension and a proxy for total traffic interception across both HTTP(S) and WebSocket communications. At its core, a flexible multi-agent pipeline delivers data leakage prevention through a hybrid approach combining deterministic detectors with LLM-driven semantic analysis, proprietary code leakage prevention, and extensible components designed for future security enhancements such as prompt injection evasion. The framework's layered architecture enables deployment across heterogeneous environments, allowing organizations to balance computational cost, detection depth and latency. Evaluation results demonstrate it achieves F1 scores of up to 94.93% on optimal configurations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.08092v1">Equivariant Quantum Clustering with Differential Privacy: Parameter-Efficient Privacy-Preserving Analysis Across Heterogeneous Sensitive Datasets</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-07-09T04:01:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> B. M. Taslimul Haq, Md Arifur Rahman, Tawfiq Al Islam Foysal, Abdullah Al Noman, Abir Ahmed</p>
    <p><b>Summary:</b> Privacy-preserving clustering is critical for analyzing sensitive data in healthcare, cybersecurity, and enterprise applications, where maintaining data confidentiality must be balanced with analytical performance. This paper presents Equivariant Quantum Clustering (EQC), a parameter-efficient framework that integrates symmetry-aware quantum circuits with differential privacy to improve the privacy-utility tradeoff. EQC employs p4m equivariant parameter sharing to reduce circuit complexity while preserving informative feature representations. The framework is evaluated on three privacy-sensitive datasets: NSL-KDD, CERT Insider Threat v6.2, and a synthetic MIMIC-III clinical dataset. On the NSL-KDD benchmark, EQC achieves 79.3% clustering accuracy while reducing membership inference attack success to 38.3% under a privacy budget of ε = 1.0 and δ = 10^-5, outperforming representative classical and quantum baselines. Ablation studies indicate that the performance gains primarily arise from parameter-efficient circuit design combined with differential privacy. The results demonstrate that EQC provides a practical quantum-ready framework for secure and privacy-preserving clustering across heterogeneous sensitive datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.08801v2">A Seed for Privacy -- semi-automatic privacy-revealing data detection in databases and data streams</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-09T03:21:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> He Gu, Thomas Plagemann, Vera Goebel</p>
    <p><b>Summary:</b> Sharing databases and data streams imposes the danger of revealing private information in the form of complex events which can comprise individual data elements and their combinations. Identifying these privacy-revealing complex events is crucial for preserving privacy while maintaining data utility. However, data producers often lack the expertise to comprehensively identify these events, which undermines many state-of-the-art privacy-preserving mechanisms that rely on accurate event labeling. To address this challenge, we developed pArborist - a tool that can semi-automatically create a set of queries to identify and label privacy-revealing complex events in both static datasets and dynamic data streams, guided by the privacy requirements of the data producer. pArborist uses the schema of the database or data stream combined with initial input from the data producer, i.e., seed queries. From each seed query, pArborist grows a tree containing all possible syntactically correct queries, constrained by an upper limit on computational resources. Following this growing phase, the tree is refined by eliminating queries that lack correlation to the seed or are conditionally independent of the seed. Our evaluation indicates that pArborist achieves overall recall of 90% and precision of 93% in finding privacy-revealing queries, and this significantly surpasses the state-of-the-art approach FQID. In data stream processing experiments, pArborist introduces a delay of approximately 1.3 ms following an average warm-up period of 920 ms. The experiments also show that pArborist can automatically detect privacy-revealing complex events according to GDPR.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.07775v1">Idiobionics: The Unification of Privacy and Intelligent Robotic Prostheses</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E">
  <p><b>Published on:</b> 2026-07-08T17:18:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kwesi Afari Darfoor, Patrick M. Pilarski, Bailey Kacsmar</p>
    <p><b>Summary:</b> The human body is at the center of a growing family of technologies designed to tightly and persistently couple biological and digital systems. Robotic prostheses are a representative example of this tight coupling. Also referred to as bionic limbs, robotic prostheses are devices that support people who have lost limbs in pursuing daily life activities such as walking and grasping objects. Bionic limbs are now perceptive and responsive owing to their integration with advanced sensors and artificial intelligence-based control approaches. Consequently, such robotic prostheses can now be viewed as semiautonomous wearable robotic systems that can co-adapt with their users. However, the same sensing and control advancements that increase the capability of robotic prostheses also introduce threat vectors that could be exploited by malicious entities to violate the privacy of users. To fully realize the benefits of next-generation bionic limbs, we maintain it is important to directly understand and address these privacy risks and the barriers they might present to user adoption. This paper therefore introduces a new line of inquiry we term idiobionics to holistically investigate issues at the intersection of privacy and intelligent bionic limbs. As the main contribution of this paper, we define idiobionics, ground it in related literature, and provide preliminary evidence showing and discussing potential adversarial attacks that could exploit intelligent bionic limb designs. We then contribute a curated list of open research questions within idiobionics that are relevant to researchers in wearable robotics and other human-facing autonomous systems. We expect that idiobionics research will help unlock the full potential of robotic prostheses and related bionic devices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.07635v2">Unlearning to Protect: A Distilled Reinforcement Learning Framework with Privacy-Preserving Feature Unlearning and XAI for IoT Security</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-08T16:52:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Md. Nahid Hasan, Md. Golam Rabiul Alam</p>
    <p><b>Summary:</b> Botnets pose a significant cybersecurity threat, enabling attacks such as DDoS, data theft, and service disruptions on IoT devices. These devices often lack built-in botnet traffic filtering, leaving them highly exposed. Existing AI-based solutions improve detection capabilities but have limitations: (i) they are too heavy for IoT deployment, and (ii) they lack unlearning capabilities to forget sensitive or outdated features without retraining. To address these challenges, we propose DiRLU, a lightweight, reinforcement learning driven framework, while ensuring privacy by selectively unlearning sensitive or outdated features without requiring retraining. The framework leverages knowledge distillation to transfer knowledge from a teacher model into a lightweight student model, with both models trained using A2C. A post-hoc unlearning mechanism modifies weights to remove targeted features, while restored features show negligible performance loss, confirming reversibility. Unlike many benchmark models that used only 5% of the BoT-IoT dataset, this research leverages 25%, allowing us to develop a strong teacher model. Both the teacher and student models were trained using the A2C reinforcement learning algorithm, achieving impressive results, with the student model achieving 99.60% accuracy and a 99.80% F1 score. To enhance transparency, we integrated Explainable AI (XAI), particularly LIME, which helps interpret the model's decisions and identify the key features influencing its predictions. Moreover, DiRLU requires only 2,370 FLOPS, approximately 3.87x more efficient than the state-of-the-art model, highlighting its efficiency for edge deployment. DiRLU combines efficiency with privacy, aligning with GDPR standards (right to be forgotten) to provide practical and scalable IoT security solution.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.07371v2">zk-ScalHard: Scalable and Hardware-Rooted Privacy-Preserving Authentication for Secure OTA Updates in Zonal SDVs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-08T13:05:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shrikant Tangade, Bansi Pambhar, Valeria Loscri, Mauro Conti</p>
    <p><b>Summary:</b> The automotive industry is transitioning to Zonal-oriented Architectures (ZoA) for Software-Defined Vehicles (SDVs), enabling frequent over-the-air (OTA) updates for 100+ Electronic Control Units (ECUs). While OTA updates improve efficiency, they introduce safety-critical security risks. Current standards like Uptane and AUTOSAR Adaptive rely on Public-Key Infrastructure (PKI). However, PKI-based authentication creates bandwidth bottlenecks in in-vehicle and vehicle-to-cloud (V2I) communication as ECU density increases. It also risks exposing sensitive vehicle configurations and passenger privacy due to centralized architectures. Next-generation Zonal SDVs require decentralized, scalable authentication with data privacy. To address this, we propose zk-ScalHard, a hardware-rooted, privacy-preserving authentication protocol. We introduce a decentralized, hierarchical trust-promotion model utilizing Silicon Physical Unclonable Functions (PUFs) and two novel Zero-Knowledge Proof (ZKP) circuits: (1) Zonal Identity and Integrity (ZIDI) and (2) High-Performance Computing Aggregation (HPCA). These circuits employ multi-party computation (MPC) and recursive aggregation to achieve decentralization and scalability. The integration of ZKPs and PUFs ensures 100% vehicle-level data sovereignty. Benchmarked against Uptane, zk-ScalHard achieves constant O(1) communication and verification complexity, improving upon the linear O(n) complexity of current systems. Evaluation shows a 99.2% reduction in authentication bandwidth and a 99.9% reduction in the temporal attack surface. Our results demonstrate that zk-ScalHard provides a scalable, secure, and GDPR-compliant architecture for future Zonal SDVs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.07209v1">Continual Learning With Participation Privacy: An Auditable Buffering-Aggregation Recipe</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-07-08T09:44:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> T-H. Hubert Chan, Elaine Shi, Mengshi Zhao, Mingxun Zhou</p>
    <p><b>Summary:</b> Modern federated and streaming learning systems often release intermediate models, so privacy must hold for the full trajectory under adaptive interaction. Motivated by participation privacy, we study single-edit neighboring user streams, where one insertion/deletion shifts all subsequent updates and defeats standard Hamming-neighbor continual-release analyses. We give an auditable modular recipe. A randomized buffering wrapper emits bins of size $[U,2U]$, reducing single-edit streams to a Hamming-style per-bin update stream with explicit backlog/delay guarantees, where $U$ is calibrated by the privacy parameters $(\varepsilon,δ)$. We then prove a certification theorem identifying when a non-adaptive Hamming-neighbor DP proof for a continual primitive lifts to adaptive inputs: the primitive must use fresh per-round randomness and have a stable one-round privacy profile under common adaptive context. Together, these ingredients yield trajectory-level $(\varepsilon,δ)$-DP for single-edit streams using standard primitives (e.g., tree prefix sums), with an explicit privacy--latency link via $U$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.06963v1">Large Language Models (LLMs) and Generative AI in Cybersecurity and Privacy: A Survey of Dual-Use Risks, AI-Generated Malware, Explainability, and Defensive Strategies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-07-08T03:40:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kiarash Ahi, Saeed Valizadeh</p>
    <p><b>Summary:</b> Large Language Models (LLMs) and generative AI (GenAI) systems, such as ChatGPT, Claude, Gemini, LLaMA, Copilot, Stable Diffusion by OpenAI, Anthropic, Google, Meta, Microsoft, Stability AI, respectively, are revolutionizing cybersecurity, enabling both automated defense and sophisticated attacks. These technologies power real-time threat detection, phishing defense, secure code generation, and vulnerability exploitation at unprecedented scales. Following a rapid surge where LLM-generated malware grew to account for an estimated 50% of detected threats by 2025, up from just 2% in 2021, navigating this highly automated threat landscape in 2026 demands next-generation security frameworks. This paper presents a comprehensive survey of the beneficial and malicious applications of LLMs in cybersecurity, including zero-day detection, DevSecOps, federated learning, synthetic content analysis, and explainable AI (XAI). Drawing on a review of over 70 academic papers, industry reports, and technical documents, this work synthesizes insights from real-world case studies across platforms like Google Play Protect, Microsoft Defender, Amazon Web Services (AWS), Apple App Store, OpenAI Plugin Stores, Hugging Face Spaces, and GitHub, alongside emerging initiatives like the SAFE Framework and AI-driven anomaly detection. We conclude with practical recommendations for responsible and transparent LLM deployment and trustworthy AI, including model watermarking, adversarial defense, and cross-industry collaboration, setting a new benchmark for rigorous, holistic cybersecurity research at the intersection of AI and threat defense, and offering a roadmap for secure, scalable LLM systems that serves as a critical reference for researchers, engineers, and security leaders navigating the complex challenges of AI-driven cybersecurity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.06860v1">Auditable Machine Unlearning for Privacy-Compliant Ransomware Detection Using Multi-Shard SISA and Deep Reinforcement Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-07T23:23:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jannatul Ferdous, Rafiqul Islam, Md Zahidul Islam</p>
    <p><b>Summary:</b> Ransomware poses an escalating cybersecurity threat as attackers continuously modify behavioral patterns to evade static defenses. Although existing machine learning-based detectors often achieve strong predictive performance, they generally assume fixed training data and do not support the selective removal of previously learned samples. This limitation conflicts with privacy regulations such as the GDPR and CCPA, which require the removal of sensitive user data upon request. To address this challenge, we propose an auditable ransomware detection and unlearning framework that integrates deep reinforcement learning with multi-shard SISA retraining. In the proposed system, a Double Deep Q-Network (DDQN) learns a reward-guided detection policy from behavioral features under asymmetric security costs, while multi-shard SISA enables privacy-compliant selective sample removal through shard-level retraining. The framework was evaluated using four criteria: utility preservation, oracle-based forgetting validation, membership inference auditing, and computational efficiency. On a balanced Windows 11 behavioral dataset comprising 2,000 samples and 103 features, the baseline DDQN detector achieved an F1 score of 0.9925 and an AUC of 0.9983. The experimental results show that single-shard unlearning maintains minimal utility degradation and low oracle disagreement, whereas moderate shard counts (M = 5-10) provide the best efficiency-performance trade-off, reducing retraining time to 5-30 s compared with 80-330 s for full retraining. In addition, the membership inference scores remain close to 0.5 across most configurations, indicating limited privacy leakage after unlearning. These findings demonstrate that a privacy-compliant ransomware detection framework can jointly achieve high detection performance, auditable deletion verification, and efficient sample removal.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.06815v1">Behavioral Privacy Leakage in Agentic Negotiation: Formalizing and Mitigating Inference Attacks via Randomized Policies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-07T21:22:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Barkha Rani</p>
    <p><b>Summary:</b> Autonomous negotiation agents are increasingly deployed in high-stakes settings such as insurance and procurement. While cryptographic techniques protect explicitly disclosed constraint values, they fail to address a subtler threat: behavioral privacy leakage, where an adversary infers private constraints from observable negotiation dynamics such as concession trajectories, timing, and convergence patterns. This paper investigates behavioral differential privacy in multi-round negotiation protocols. We design an adaptive stochastic negotiation policy that jointly guarantees $(\varepsilon, δ)$-differential privacy, almost-sure convergence of the offer sequence (reaching agreement when the counterparty's reservation value permits), and high negotiation utility. Evaluated on 3,000 synthetic bilateral negotiations, our mechanism reduces adversarial inference accuracy by 43-50% while maintaining a negotiation success rate and utility above 90%, demonstrating that strong privacy guarantees can be achieved without significant loss of performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.19403v1">Recovering Clinical Utility Under Differential Privacy: Empirical Validation of Adaptive Federated Aggregation on Heterogeneous Cardiovascular Datasets</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-07-07T18:51:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rodrigo Tertulino, Laercio Alencar, Ricardo Almeida</p>
    <p><b>Summary:</b> Validating federated learning frameworks on real clinical data is an essential step between proof-of-concept demonstrations in controlled synthetic environments and deployment in real multicenter healthcare settings. A prior architectural study by the same authors (Tertulino and Alencar, 2026) demonstrated, on a synthetic six-feature benchmark, that server-side adaptive optimization acts as a temporal denoiser for Differential Privacy noise, answering an open challenge identified in the original pipeline work (Tertulino, 2025). That study used synthetically generated data and explicitly identified real-world validation as a priority future direction. The present work addresses this gap by validating the FedCVR framework on five publicly available real cardiovascular datasets (Framingham, Cleveland, Hungarian, Switzerland, and Long Beach VA), harmonized to the 13-attribute UCI Heart Disease schema and configured as a heterogeneous federated scenario with leave-one-institution-out cross-validation. Results demonstrate that FedCVR preserves its adaptive advantage on real data, achieving an F1-Score of 79.2% and AUC of 0.96 under the operational privacy budget (noise multiplier = 0.8, privacy budget epsilon approximately 4.2), while statistically outperforming standard FedAvg on all evaluated metrics (paired t-tests, all p <= 0.003, significant under the Bonferroni-corrected threshold). The measured privacy cost on real data confirms the graceful degradation pattern observed in the synthetic experiments, providing empirical evidence of the framework's clinical viability in genuine multicenter contexts.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.06687v1">Exploring the Interaction of Explanation Styles, Context, and Trust of AI Privacy Redaction in AI-mediated Interactions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-07-07T18:04:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Roshni Kaushik, Maarten Sap, Koichi Onoue</p>
    <p><b>Summary:</b> AI-mediated communication is increasingly being utilized to help facilitate interactions; however, in privacy sensitive domains, an AI mediator has the additional challenge of considering how to preserve privacy. In these contexts, a mediator may redact or withhold information, raising questions about how users perceive these interventions and whether explanations of system behavior can improve trust. In this work, we investigate how explanations of redaction operations can affect user trust in AI-mediated communication. We devise a scenario where a validated system removes sensitive content from messages and generates explanations of varying detail to communicate its decisions to recipients. We then conduct a user study with 180 participants that studies how user trust and preferences vary for cases with different amounts of redacted content and different levels of explanation detail. Our results show that participants believed our system was more effective at preserving privacy when explanations were provided (p<0.05, Cohen's d ~ 0.3). We also found that contextual factors had an impact; participants relied more on explanations and found them more helpful when the system performed extensive redactions (p<0.05, Cohen's f ~ 0.2). We also found that explanation preferences depended on individual differences as well, and factors such as age and baseline familiarity with AI affected user trust in our system. These findings highlight the importance and challenge of balancing transparency and privacy in AI-mediated communications and suggest that adaptive, context-aware explanations are essential for designing privacy-aware, trustworthy AI systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.06371v1">The Impact of Security and Privacy Controls on Users' Emotional Engagement with Generative AI Chatbots</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-07-07T15:10:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jabari Kwesi, Jiaxun Cao, Hailee Cunningham, Pardis Emami-Naeini</p>
    <p><b>Summary:</b> Chatbots powered by generative AI (e.g., OpenAI's ChatGPT and Google's Gemini) are increasingly being appropriated for emotional support and companionship. These tools offer a suite of security and privacy (S&P) controls, including model training opt-outs and memory toggles, yet how the presence of these controls influences users' attitudes toward emotionally sensitive disclosure remains understudied. We conducted a mixed-methods vignette study with 354 U.S. participants to examine how S&P controls influence users' willingness to engage with generative AI chatbots for emotional support, their perceptions of how protected they are when using these systems, and their perceptions of how effective the chatbots are for providing support. Controls enabling deletion of disclosures had the largest positive impact: these offerings outperformed technically sophisticated controls such as local-only processing and model training opt-outs, where participants expressed difficulty understanding the underlying mechanisms. Yet trust remains fragile, and participants often doubted S&P controls would function as promised. We conclude with actionable recommendations informed by our results to bridge users' comprehension gaps, build credible assurances, and properly calibrate barriers for users in distress.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.06320v1">Dithered Gaussian Mechanism for Randomness-Efficient Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-07-07T14:20:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nikita P. Kalinin, Rasmus Pagh</p>
    <p><b>Summary:</b> We present the dithered Gaussian mechanism, a novel alternative to the discrete Gaussian mechanism for differential privacy that discretizes the private output rather than the noise distribution itself. By interpreting this discretization as post-processing of the Gaussian mechanism, our construction directly inherits the privacy guarantees of the standard Gaussian mechanism while avoiding vulnerabilities caused by finite-precision floating-point outputs. We show that the mechanism is provably randomness-efficient: by sampling the discretized output values directly, the number of high-quality random bits required for privacy can be reduced significantly and made independent of the noise level. This is achieved by separating the randomness into two sources: a high-quality source used for the privacy-critical sampling step, and a high-performance public source, possibly known to the adversary, that supplies the additional randomness needed for randomized discretization. This separation enables the use of cryptographically secure randomness without substantial performance loss. As an application, we study model training with DP-SGD and show that cryptographically secure noise generation with reduced exposure to floating-point vulnerabilities can be achieved with modest practical overhead.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.06307v1">Quantum Probabilistic Local Differential Privacy: Structural Properties and Sample Complexity Bounds</a></h3>
  
  <p><b>Published on:</b> 2026-07-07T14:11:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xian Shi</p>
    <p><b>Summary:</b> Differential privacy provides a rigorous framework for quantifying privacy leakage in data analysis, while its quantum extensions have become increasingly relevant with the development of quantum computing and quantum machine learning. In this work, we introduce and study quantum probabilistic local differential privacy, a relaxation of quantum local differential privacy in which the privacy constraint is allowed to fail on a spectral violation event with low probability. This quantity can be interpreted as the probability under the quantum superoperation of a quantum privacy-loss violation, and is closely related to the acceptance probability of the quantum Neyman-Pearson test at a small threshold. We investigate the basic structural properties of this privacy notion and clarify its relationship with existing forms of quantum differential privacy. We show the properties of quantum probabilistic local differential privacy under tensor-product composition and unitary post-processing, while it is in general neither convex nor closed under post-processing by arbitrary quantum channels. We further characterize when depolarizing noise satisfies quantum probabilistic local differential privacy under several representative scenarios. Finally, we connect quantum probabilistic privacy constraints with statistical inference by deriving a lower bound on probabilistically privatized contraction coefficients in terms of the hockey-stick divergence. As an application, we obtain sample complexity bounds of probabilistically privated asymmetric and symmetric quantum hypothesis testing. These results provide a systematic foundation for studying probabilistic privacy guarantees in quantum information processing and their operational consequences for private quantum statistical inference.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.06141v1">The Masks We (Think We) Wear: Privacy Threats of Browser-Extension Wallets in the Web3 Ecosystem</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-07-07T11:08:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Weihong Wang, Yana Dimova, Victor Vansteenkiste, Tom Van Goethem, Tom Van Cutsem</p>
    <p><b>Summary:</b> Cryptocurrency wallets are the primary interface for managing pseudonymous blockchain addresses, viewing balances, and interacting with Web3 applications. Although users typically assume that their addresses remain independent of each other unless intentionally revealed, modern wallets routinely communicate with both blockchain infrastructure and decentralized applications (dApps), generating network-side and web-side signals that may undermine this assumption.
  In this paper, we identify and formalize five privacy threats that arise directly from wallets interacting with the network and the web browser. Using large-scale dynamic measurements of 85 of the most popular Chrome Web Store browser-extension wallets (representing 35.16 million users), we observe that routine remote procedure call (RPC) operations leak structural links between a user's addresses; that the majority of Ethereum wallets implement permission revocation inconsistently and continue to expose previously revoked addresses across sessions; and that many wallets inject their provider interfaces into cross-origin iframes, enabling passive cross-site tracking beyond dApps and potentially real-world identity deanonymization without user interaction.
  Taken together, our results show that these wallet behaviors leak sensitive information that can be used to link multiple addresses to the same user, track wallet users across sessions and sites, and connect their browsing activity to their on-chain wealth.
  We discuss practical mitigations and show that many of these threats can be substantially reduced through improved wallet implementation, stronger privacy considerations in ecosystem standards, and stricter controls over provider exposure. Our results highlight the need for standardized, privacy-preserving wallet architectures.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2607.06127v2">Measuring the practice of shared-decision making (OPTION12): An Investigation into Open-sourced Smaller LLMs (OS-sLLMs) for Better Privacy and Sustainability</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-07-07T10:37:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tamara Wit, Lifeng Han, Carly Heipon, David Lindevelt, Anne Stiggelbout, Suzan Verberne</p>
    <p><b>Summary:</b> We present LLM4SDM, the first study of open-source smaller language models (OS-sLLMs) for automated assessment of shared decision making (SDM) using the Observer OPTION12 framework. Unlike previous work that relies on large commercial models and the shorter OPTION5 instrument, our study focuses on privacy-preserving locally deployable models and Dutch melanoma consultation transcripts. Using expert-annotated clinical consultations, we evaluate three general-domain and two medical-domain OS-sLLMs during a development-phase pilot study. Results show that general-domain models outperform medical-domain models, which exhibit substantial hallucination and instruction-following failures. Gemma3:12b achieves the strongest agreement with human annotations (Pearson r=0.51, Spearman \r{ho}=0.59). Item-level and qualitative analyses reveal systematic challenges related to temporal discourse reasoning, conversational role attribution, and evidence grounding. We further introduce a Judge-LLM consensus framework designed to support disagreement resolution among multiple models. Our findings suggest that while current OS-sLLMs cannot replace human annotators, they offer a promising foundation for privacy-preserving human-in-the-loop SDM assessment.</p>
  </details>
</div>



<h2>2026-08</h2>

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


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.01290v1">FedChronos: Federated Fine-Tuning of Time-Series Foundation Models for Privacy-Preserving Commodity Price Forecasting</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-08-02T14:59:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Amit Sharma, Nitin Auluck, Akramul Azim</p>
    <p><b>Summary:</b> Time-series foundation models (TSFMs) such as Chronos have demonstrated strong forecasting capabilities across domains, yet adapting them to institutionally fragmented settings, where data cannot be centralized due to regulatory, competitive, or sovereignty constraints, remains unexplored. We introduce FedChronos, a framework for federated parameter-efficient fine-tuning of an already pre-trained TSFM, a setting that existing federated time-series work has not addressed, since prior methods either pre-train from scratch or align prototypes rather than adapt a fixed backbone. Our approach applies Low-Rank Adaptation (LoRA) to the Chronos-T5 backbone and trains across distributed clients using FedAvg and FedProx, transmitting only lightweight adapter weights (384~KB per round, an 86$\times$ reduction over full-model exchange). We evaluate FedChronos on daily commodity prices from 15 Indian agricultural markets across 9 states, a naturally non-IID federated setting, and find that naïve LoRA fine-tuning overfits substantially on small per-client datasets, dropping below zero-shot performance. We further observe that differential privacy (DP) noise can act as implicit regularization and counteract this overfitting: in our experiments the strongest configuration ($\varepsilon = 5$) reduces mean absolute percentage error (MAPE) by 31% over zero-shot and 26% over the best traditional baseline, while bounding each round's information leakage via per-round $(\varepsilon, δ)$-differential privacy. Because the model is compact and the updates are small, the approach also suits edge AI deployments where both the network link and the client device are constrained. Overall, our findings suggest that privacy and accuracy can be complementary rather than competing objectives in federated TSFM fine-tuning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.01192v1">A Unified Benchmark for Privacy-preserving Vector Search</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Performance-F9C80E">
  <p><b>Published on:</b> 2026-08-02T12:16:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anne-Marie Kermarrec, Rafael Pires, Mathis Randl, Martijn de Vos</p>
    <p><b>Summary:</b> Vector search powers semantic search, recommendation systems, and retrieval-augmented generation (RAG). By design, the service answering a query sees both the query embedding and, usually, the corpus against which it is matched. This is a privacy breach for both the user issuing the query and the owner of the corpus. A family of cryptographic schemes (e.g., SAP, EMVP, BNTM, Tip-toe) addresses that leak. However, as each scheme is published and evaluated on its own corpus, threat model, parameter choices, hardware, and metric conventions, the numbers cannot be compared directly. Consequently, a practitioner asking which one to deploy today has no defensible way to choose. We close that gap with a uniform experimental comparison, including a Plaintext baseline and four cryptographic backends running over the same workload, hardware, and metric definitions. Under that ruler, the schemes spread across a Pareto frontier in privacy, performance, and recall rather than imposing a flat penalty on performance. We find that the performance of SAP matches Plaintext, EMVP delivers cryptographic indistinguishability at a 4x throughput cost on CPU, BNTM adds malicious-server verifiability at a further 22x median-latency cost, and Tiptoe hides the cluster choice itself, but incurs a 190x per-query cost compared to Plaintext. GPU acceleration pays off for Plaintext and SAP but not for EMVP or BNTM. All our experiment artifacts are publicly available for reproducibility</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.01148v1">Latency-Optimal Adaptive Split Inference for Privacy-Preserving Cloud-Edge-End Collaboration</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-08-02T10:59:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yi Li, Peng Zhang, Man Ho Au</p>
    <p><b>Summary:</b> Internet of Things (IoT) end devices are increasingly expected to support privacy-sensitive batch inference, yet their limited computational resources often make full local execution of convolutional neural networks impractical. This paper presents a latency-optimal adaptive split inference framework for privacy-preserving cloud-edge-end collaboration. The end device acts as the trust anchor, executes the plaintext model prefix, encrypts the split activation using fully homomorphic encryption (FHE), and keeps the secret key locally, while the edge and cloud execute assigned model segments only on FHE ciphertexts. We formulate collaborative encrypted inference as a split-pair selection problem over an end-side split point and an edge-side termination point. The proposed planner jointly models plaintext prefix execution, encryption, communication, edge-side FHE execution, and cloud-side FHE completion, and supports both convolution-level and block-level split granularities. Experiments on CIFAR-10 and PathMNIST show that the proposed convolution-level collaborative scheme achieves amortized end-to-end speedups of approximately 12.9 times over full-cloud FHE and 3.9 times over the block-level alternative, while preserving the corresponding plaintext-model accuracy. Including modeled communication, the amortized latencies are 1033.279 s/sample on CIFAR-10 and 1023.429 s/sample on PathMNIST.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.01020v1">Inverting the Hidden: Unveiling Multimodal Privacy Leakage in Collaborative LVLM Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-02T05:56:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuaifan Jin, Zhibo Wang, Qiyuan Wang, Yiting Han, Yajie Zhou, Yuanfan Zhang, Jiahui Hu, Xiaoyi Pang</p>
    <p><b>Summary:</b> Collaborative inference deploys Large Vision-Language Models (LVLMs) by partitioning computation between edge devices and the cloud. While withholding raw inputs supposedly ensures privacy, transmitting intermediate hidden states exposes a critical attack surface. However, it remains unclear whether deep-layer LVLM hidden states retain recoverable private information, given that visual content has been projected into the language embedding space. To address this concern, we theoretically analyze LVLM hidden-state recoverability and show that, under regularity assumptions and a positive semantic--nuisance margin, privacy-relevant visual semantics remain identifiable and stably recoverable. Motivated by this analysis, we propose RASR, a novel coarse-to-fine multimodal reconstruction attack. RASR obtains initial image and text reconstructions through modality-specific inverse paths that follow their respective forward processing pipelines in reverse, and then uses hidden-state consistency to refine both reconstructions. Evaluations on Qwen3-VL-8B-Instruct and LLaVA-1.5-7B across five datasets demonstrate that RASR reduces image reconstruction MSE by \(\sim\)50\% compared to the strongest baselines, while achieving up to 99\% token accuracy for text recovery. These results show that privacy-sensitive visual and textual information can be recovered even from deep-layer LVLM hidden states, exposing the privacy risks of collaborative inference.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.00872v1">Similarity Weighted Aggregation with Global Differential Privacy for Federated Brain Lesion Segmentation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-08-01T21:23:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Muhammad Irfan Khan, Eero Lehtonen, Joni Obradovic, Elina Kontio, Esa Alhoniemi, Suleiman A. Khan, Mojtaba Jafaritadi</p>
    <p><b>Summary:</b> Federated Learning (FL) enables collaborative training of machine learning models across multiple institutions without sharing sensitive data, making it particularly suitable for medical imaging applications. However, heterogeneous data distributions across institutions and potential information leakage through model updates remain important challenges. In this work, we propose DP-SimAgg, a privacy-preserving federated learning framework that integrates similarity-weighted aggregation with a server-side differential privacy mechanism. The proposed method applies L2 clipping to bound collaborator updates, computes similarity-based aggregation weights to mitigate the effects of non-IID data distributions, and injects calibrated Gaussian noise at the central server, providing per-round privacy guarantees under the assumed sensitivity bound. The framework is implemented using Intel's OpenFL platform and evaluated on the FeTS 2022 dataset consisting of 1251 multi-modal MRI scans for brain tumor segmentation. Experimental results demonstrate that DP-SimAgg maintains competitive segmentation performance while providing privacy protection. Under a strict per-round privacy budget (epsilon = 1, cumulative epsilon_total = 20 over 20 rounds), the method achieves Dice scores of 0.6357, 0.5305, and 0.5274 for the enhancing tumor (ET), tumor core (TC), and whole tumor (WT) regions, respectively. With a more relaxed per-round budget (epsilon = 10, cumulative epsilon_total = 200), performance approaches that of the non-private baseline while incorporating a central Gaussian mechanism with per-round (epsilon, delta)-DP accounting under the assumed sensitivity bound. These results highlight the potential of DP-SimAgg for enabling privacy-preserving collaborative learning in medical imaging applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.00826v1">XR-PRISM: Data-Driven Privacy and Risk Impact Scoring Metric for Extended Reality in Healthcare</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-08-01T19:04:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nafisa Anjum, M. Rasel Mahmud</p>
    <p><b>Summary:</b> Extended Reality (XR) technologies are transforming healthcare through immersive training, remote consultation, and patient rehabilitation. However, their extensive sensing capabilities and complex data pipelines introduce distinct security, privacy, and safety risks. Existing research lacks a unified quantitative framework for assessing and prioritizing these risks. We review 65 peer-reviewed studies on XR security and privacy published from 2017 to 2024, synthesizing a four-layer threat taxonomy consisting of Device, Network, User, and Cloud layers, along with a corresponding catalog of defenses. Building on this analysis, we introduce XR-PRISM, a six-factor weighted Privacy and Risk Impact Scoring Metric that integrates threat likelihood, system vulnerability, attack surface, safety impact, privacy impact, and control effectiveness into a single actionable risk score. Our analysis shows that more than 70% of the identified countermeasures lack standardized risk evaluation, while fewer than 15% of the documented attacks require a high level of expertise to execute. XR-PRISM provides researchers and practitioners with a transparent, data-driven method for comparing, prioritizing, and mitigating security and privacy risks in healthcare XR deployments.</p>
  </details>
</div>

