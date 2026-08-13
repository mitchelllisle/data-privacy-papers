
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
  <h3><a href="http://arxiv.org/abs/2607.27015v2">Reliability Functions of Quantum Soft Covering and Privacy Amplification via a Mixed-Order Rényi Divergence</a></h3>
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
  <h3><a href="http://arxiv.org/abs/2607.12354v2">Reducing information dependency does not cause training data privacy. Adversarially non-robust features do</a></h3>
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



<h2>2026-08</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.11645v1">Cloak of Invisibility: Real-Time Privacy-Preserving Volumetric Video Streaming</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-08-12T04:44:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hossein Khalili, Philip Do, Alexander Vilesov, Kittipat Apicharttrisorn, Nader Sehatbakhsh</p>
    <p><b>Summary:</b> Volumetric video streaming turns privacy into a 3D, multi-view problem. Unlike ordinary video, where sensitive content can often be redacted frame by frame, RGB-D volumetric pipelines capture people, rooms, and personal objects from multiple cameras and fuse them into a shared 3D representation. A private object missed in one view, or only partially removed before fusion, can therefore reappear in the reconstructed scene. This creates a privacy challenge for 3D telepresence, education, entertainment, and immersive applications: private content should be removed before raw visual and geometric data leave the camera side, while the public part of the scene should remain useful for real-time reconstruction. Existing volumetric streaming systems mainly optimize reconstruction, data movement, and latency, while privacy-preserving vision methods are designed for single-camera, single-frame images and do not directly address calibrated multi-view RGB-D fusion. We present InViStream, a real-time "privacy-from-source" system designed for this setting. InViStream addresses three challenges in volumetric capture: private objects may appear differently across views, RGB masking alone can leave geometric privacy leakage in depth, and public/private instances of the same class must be separated consistently before cloud-side fusion. To address these challenges, InViStream combines object detection with depth-aware masking, propagates public/private decisions across calibrated views, and fuses only sanitized point clouds. We evaluate InViStream on synthetic and real RGB-D scenes, including offices, conference rooms, living rooms, and settings with multiple public and private people and objects. InViStream achieves synthetic Dice/Recall of 0.799/0.891 and real Dice/Recall of 0.792/0.908, with synthetic SSIM above 0.98 and real-time streaming above 30 FPS.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.11337v1">Association-based Privacy Attacks in Wireless Protocols: Formal Modeling and Mitigation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-08-11T18:41:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohit Kumar Jangid, Felix Engelmann, Zhiqiang Lin</p>
    <p><b>Summary:</b> With the surge in privacy-sensitive data from sources such as social media and IoT devices, there is a pressing need for formal, automated methods to assess privacy risks within these intricate systems. This paper formally investigates root sources of pairing-based privacy threats exploited using replay/relay techniques in wireless communication. Our research harnesses condition-oblivious responses, replay-resistance, and distance bounding measures vital for protocols utilizing shared keys in allowlists for authenticated reconnections. Particularly, the paper uses formal modeling of notable wireless networks, like the Wi-Fi P2P persistent group formation and the Bluetooth Low Energy reconnection procedure, to illustrate the root causes and countermeasures. Our model rigorously validates the proposed solution against association inference attacks, along with existing formalizations of well-authentication, frame opacity, and no-desynchronization. The ensuing analysis reveals not only uncharted privacy realms in wireless communication but also identifies old and new vulnerabilities. Our proposed design changes are acknowledged by Wi-Fi Alliance and Bluetooth SIG, paving the way for future advancements in resilient, privacy-preserving wireless protocols.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.11003v1">Information Bottleneck under Perfect Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-11T14:50:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Junle Zhong, Mohamad Assaad, Sreejith Sreekumar</p>
    <p><b>Summary:</b> In this work, we study the information bottleneck under perfect privacy, with particular emphasis on the active-rate regime, where the representation-rate constraint is binding and directly limits the achievable utility. The goal is to construct a representation that preserves utility-relevant information while remaining statistically independent of a sensitive variable. This exact independence requirement introduces an additional constraint beyond the classical rate-relevance tradeoff and must be explicitly incorporated into the optimization. To this end, we develop an alternating direction method of multipliers (ADMM)-based method tailored to the resulting problem structure. Under suitable regularity conditions, we establish global convergence of the generated sequence, characterize its convergence rate through the Kurdyka-Lojasiewicz exponent, and extend the analysis to inexact block updates.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.10891v1">Benchmarking Time Series Generation Methods for Privacy-Preserving Forecasting</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-11T13:09:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Luis Amorim, Vitor Cerqueira, Moises Santos, Paulo J. Azevedo, Carlos Soares</p>
    <p><b>Summary:</b> Time series forecasting in privacy-sensitive domains often requires training models on released data rather than original observations. Synthetic time series generation has been developed primarily for data augmentation, where generated series supplement the original training set. How well these methods perform when fully replacing the original data - and how much privacy risk the released series carry - remains underexplored. We address this gap through a benchmark evaluating synthetic generation methods and noise-based anonymization baselines under a Train on Synthetic, Test on Real (TSTR) protocol. We jointly assess forecasting performance and distance-based empirical privacy risk across seven datasets, characterizing the trade-off between these objectives. We also introduce Grasynda-P, a privacy-motivated extension of the graph-based generator Grasynda, incorporating matrix ensembling and kernel density estimation. Our results show that: (1) no generation method fully substitutes for original training data; (2) noise-based anonymization yields the strongest privacy but the worst forecasting performance; (3) simple transformation-based generators outperform deep generative models for forecasting in this setting; and (4) Grasynda-P lies on the Pareto frontier, achieving competitive forecasting with stronger privacy separation than other generators. This benchmark establishes a reference point for evaluating and developing new privacy-aware synthetic time series generation methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.10318v1">In Defense of Using Worst-case Privacy Disclosure as Privacy Evaluation Metric of Voice Anonymization</a></h3>
  
  <p><b>Published on:</b> 2026-08-10T23:40:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xin Wang, Xiaoxiao Miao</p>
    <p><b>Summary:</b> The voice anonymization community mainly uses Equal Error Rate (EER) to evaluate the performance of voice identity protection. While alternative metrics such as privacy-ZEBRA and a rank-based metric have been proposed, their underlying assumptions and differences may not be well known, especially to newcomers. This paper is motivated to fill the gap. Based on the concept of Shannon's perfect secrecy (or privacy), this paper positions itself as a defense of the privacy-ZEBRA framework. While no new metric is proposed, this paper explains how an `ideal' system in terms of EER may fail to gauge the information leakage on individual speakers in the log-likelihood ratio (LLR) space. The paper also shows how the rank-based metric can be cast into a metric that follows the same principle of perfect secrecy and how their best solutions are equivalent. Furthermore, the paper explains how the method of estimating LLRs may affect the evaluation results. These discussions are, to the best of the authors' knowledge, not explored or explained in detail in existing papers. Last but not least, the findings are demonstrated on simulated and VoicePrivacy Challenge data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.09328v1">MaxModShift: Model Privacy via Designed Shifts</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2026-08-10T09:08:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nomaan A. Kherani, Urbashi Mitra</p>
    <p><b>Summary:</b> Model learning by an eavesdropper is treated as an estimation problem in a federated environment. The Fisher Information Matrix for the eavesdropper's estimation problem is driven to singularity through a signaling design; this ensures that the eavesdropper cannot learn the model. Herein, the innovation of prior designs is that model shifts are designed to maximize the difference in the model learned by Eve and the central server while satisfying a transmission power constraint for the agents. Two shift schemes are provided. MaxModShift outperforms a prior ModShift design while requiring lesser transmission power. Compared to a noise injection scheme, MaxModShift performs better while requiring a lower bandwidth secret channel and a reduced average power consumption.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.09164v1">CIDER: A Dataset of Contextual Disclosure Boundaries for Privacy Preference Alignment</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-08-10T06:17:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bingcan Guo, Eryue Xu, Jijie Zhou, Zhiping Zhang, Tianshi Li</p>
    <p><b>Summary:</b> Aligning large language models (LLMs) with human privacy preferences requires capturing individuals' disclosure boundaries beyond general privacy norms. However, a gap remains in eliciting such nuanced preferences to evaluate alignment in realistic settings. We introduce CIDER, a dataset of 14,850 human annotations from 169 users, forming 1,650 contextual disclosure boundary sets across 60 interpersonal communication scenarios involving information sharing that violates privacy norms. Each boundary represents a real user's disclosure decisions over 9 sharing variants in a scenario, for a given communication role and AI-mediated condition. We formulate a task in which models predict a user's disclosure decision from historical boundaries, with varying levels of contextual information. Across 12 open and proprietary models, in-context personalization improves prediction accuracy by up to 11.41 percentage points using only 6 historical examples. Larger models such as GPT-5.4 (with medium reasoning effort) and Claude Sonnet 4.6 are better at leveraging semantic context to understand user-specific, context-dependent disclosure preferences for more accurate predictions, while smaller models tend to rely on structured heuristics based on disclosure granularity and identifiability. Personalization generally improves prediction accuracy, but the improvement is often accompanied by imbalanced shifts in false-positive and false-negative rates across models, with only Claude Sonnet 4.6 achieving balanced improvements in both. Our findings reveal both the promise and limitations of inference-time personalization for privacy preference modeling and position CIDER as a resource for advancing personalized privacy alignment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.09140v1">Beyond Direct Identifiers: Probabilistic Privacy Risk Estimation for Privacy-Conscious LLM Query Delegation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-08-10T05:38:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Li Siyan, Zhou Yu, Julia Hirschberg</p>
    <p><b>Summary:</b> Recent work on protecting privacy during user-LLM interactions often focuses on direct, explicit identifiers: the personally-identifiable information (PII) captured by standard detectors. One such approach is Privacy-Conscious Delegation (PCD), where a local LLM acts as an intermediary. However, privacy risk does not stem solely from explicit identifiers but also PII-free self-disclosures, leaving users identifiable through combinations of quasi-identifying traits. We investigate a probabilistic variant of PCD, where we augment its objectives with an LLM-driven probabilistic estimation of k-anonymity. To facilitate this, we first create the PUPA-SD dataset, which contains naturalistic user queries with self-disclosure. Our preliminary results indicate that optimizing PAPILLON on PUPA-SD improves quality on unseen conversations across a variety of local models and produces the best privacy-utility balance for Llama-3.2-3B, while smaller models struggle to jointly optimize quality and privacy. We propose k-anonymity as a useful auxiliary metric for tackling PCD.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.09049v1">Security and Privacy Taxonomy Generation from Mobile App Reviews</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-08-10T02:55:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Moghis Fereidouni, Vinaik Chhetri, Umar Farooq, A. B. Siddique</p>
    <p><b>Summary:</b> Mobile app reviews are a rich, continuously renewing source of how users experience privacy and security, yet existing taxonomies of these concerns are hand-crafted and cannot keep pace with the evolving nature of the data. Automating taxonomy construction is the natural response, but scalability is the core challenge: current LLM- and clustering-based methods are developed for scientific corpora of a few thousand documents and do not extend to app review collections numbering in the hundreds of thousands. We address this gap in two ways. First, we filter app reviews for privacy- and security-related content, yielding a comprehensive corpus of over 600K reviews. Second, we introduce TaxoScale, a pipeline that handles taxonomy construction at this scale by extending an expert-defined taxonomy via Recursive Hierarchical Clustering and LLM-based node naming. TaxoScale outperforms strong automatic-taxonomy baselines on path, level, coverage, and novelty metrics, and discovers novel branches absent from prior taxonomies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.09001v1">Mind the Hook: Source-Level Auditing of Privacy Defenses in Retrieval-Augmented Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-10T01:40:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yanhang Li, Zhichao Fan, Zexin Zhuang</p>
    <p><b>Summary:</b> Black-box privacy scores for retrieval-augmented generation (RAG) are difficult to interpret unless the audited defense's active pipeline hook is known. We propose an active-path audit: inventory source-level hooks over retrieval, retrieved content, and generation; map each metric to the leakage channel it observes; and validate generated-text effects with exact-match canaries. In our benchmark reimplementations, the DP-style defenses modify retrieval scores only: their generation hooks are TODO-flagged stubs that return responses unchanged. This active path explains why they affect membership-inference behavior but track No-Defense on generated-text named-entity leakage, measured by NEL_strict. By contrast, the end-to-end LPRAG path is canary-validated on the email channel, recovering 53/150 canaries under No-Defense and 0/150 under LPRAG. These findings concern our reimplementations on our stack, not released defenses or defense families; the contribution is a methodology and case study, not a universal ranking</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.08341v1">Differential Privacy for Markov Chain State Trajectories</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-08T21:34:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alexander Benvenuti, Matthew Hale</p>
    <p><b>Summary:</b> Data-driven systems may require state trajectories of Markov chains to function because these trajectories contain information that is useful to the system, e.g., a product's credit risk, a user's physical location, or a user's internet browsing behavior. However, sharing such state trajectories can reveal sensitive information about users, which presents a privacy threat. Therefore, we develop a new framework for privatizing the state trajectories in a Markov chain using differential privacy. Our framework privatizes state trajectories online, in the sense that a private state trajectory is generated at the same time as the sensitive one it approximates. We treat Markov chains as weighted directed graphs whose edge weights are the negative logarithms of the transition probabilities. Then, each state in a private state trajectory is chosen by minimizing its distance to the corresponding state in the sensitive state trajectory, where the notion of distance is equal to the total edge weight along a shortest path. We prove that with high probability the private state trajectory remains close to the sensitive one, which maintains high utility for downstream uses of private data. Additionally, we prove that private state trajectories are consistently in the typical set of state trajectories generated by the underlying Markov chain, which means that private state trajectories have similar statistical properties to actual state trajectories produced by the underlying Markov chain. Numerical simulations show that under $3$-differential privacy, the mechanism we introduce exhibits up to an $80\%$ decrease in entropy compared to the state of the art, which illustrates that private state trajectories generated by our framework more closely resemble their corresponding sensitive state trajectory while maintaining the same level of privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.08245v1">Privacy-Preserving Data Drift Detection and Recovery for Large-Scale LLM Applications via Proxy Representations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-08-08T17:15:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Michael Levit, Josh Ledgard, Haoyu Dong, Vishwas Suryanarayanan, Eyal Kolman, Sharon Tan, Qiang Gan, Vishal Chowdhary</p>
    <p><b>Summary:</b> LLM applications deployed at scale face a fundamental challenge: privacy constraints prevent direct inspection of user interactions, making it difficult to obtain any representative evaluation dataset or to track the ongoing evolution of production traffic. We present ProxyDrift, a framework that (i) identifies and measures drift between production traffic and offline evaluation sets, and (ii) constructs and refreshes those evaluation sets accordingly; all without access to raw user data. Our approach operates entirely on non-PII proxy representations: structured, multi-dimensional descriptors derived from LLM-based classification of user interactions. We introduce (1) a chance-calibrated, redundancy-aware (RA) alignment score that aggregates per-dimension drift measurements via mutual information; (2) a conditional sampler that generates synthetic proxies respecting inter-dimensional dependencies; (3) a roundtrip consistency analysis that exposes generator/classifier disagreements and guides proxy taxonomy refinement; and (4) a feedback-linkage analysis that ties per-dimension and per-value proxy distributions to user satisfaction, surfacing actionable failure and success modes. Serving hundreds of millions of users, ProxyDrift enables continuous drift monitoring and targeted synthetic data generation without exposing sensitive user data. Experiments confirm strong roundtrip consistency, discriminator-level indistinguishability of synthetic queries from human queries, and tight end-to-end alignment (RA~0.9) with production.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.08129v1">Understanding Security and Privacy Perceptions of Content Creators Regarding AI Labels of AI-Generated Content</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-08-08T13:32:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuning Zhang, Hui Wang, Rongjun Ma, Xin Yi, Kanye Ye Wang, Robert Xiao, Hewu Li</p>
    <p><b>Summary:</b> AI labels, typically implemented via underlying tracing mechanisms such as watermarks and metadata, are crucial for protecting Artificial Intelligence-Generated Content (AIGC) against security threats like disinformation and evasion. However, the perceived devaluation of AI-assisted work discourages creators from disclosing AI use, incentivizing efforts to bypass labeling and compromising downstream traceability. Yet, how AIGC creators perceive the security and privacy (S\&P) implications of these labels, and how their behaviors impact technical resilience remain underexplored. To this end, we conducted semi-structured interviews with 21 AIGC creators and measured images across 6 image generation platforms against 16 self-reported manipulation settings. Our findings reveal that creators conflate binary AI labels with granular traceability, and express strong fears of de-anonymization via platform identifiers. Driven by fears of algorithmic traffic suppression and reputational risks, they defensively removed digital traces. Through empirical tests, we show that targeted modifications like coarse quantization significantly degrade detection. AI detection capabilities are also inconsistent across platforms, and suffer from false positives even for human-authored images. Based on these insights, we advocate for workflow-resilient implicit AI labels that align technical guarantees with creators' incentives.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.07705v1">Protecting patient privacy in clinical foundation models: Technical and legal perspectives</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-07T18:48:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sana Tonekaboni, Lena Stempfle, Sasha Ronaghi, Corinna Coupette, I. Glenn Cohen, Emily Alsentzer, Marzyeh Ghassemi</p>
    <p><b>Summary:</b> Clinical foundation models trained on large-scale patient data are increasingly used for decision support, screening, and public health. As deployment expands, privacy risk increasingly arises from model-mediated leakage, yet its prevalence and severity remain poorly quantified. Models can disclose sensitive training artifacts, enabling patient re-identification in ways not captured by data-handling controls alone. Existing frameworks, including HIPAA and GDPR, offer limited guidance for such indirect threats. We propose a practical framework for assessing privacy risk in clinical foundation models and illustrate realistic leakage scenarios across deployment settings, map them to legal regimes, and outline complementary technical and legal mitigations. Our analysis provides a context-aware risk assessment grounded in realistic usage to preserve the value of medical foundation models while rigorously safeguarding patient privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.07378v1">LSEAD: A Privacy-Preserving LLM-Based Speech Analysis Framework for Early Alzheimer's Disease Screening</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-07T16:21:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xin Wang, Yingchao Huang, Yuhan Su, Shanshan Yao, Wei Peng</p>
    <p><b>Summary:</b> Early diagnosis of Alzheimer's disease (AD) is critical for enabling timely interventions that may slow disease progression and improve patient outcomes. There is a growing need for AD detection methods that are non-invasive and cost-effective, especially in real-world clinical settings with diverse patient populations and recording conditions. Speech-based screening addresses these needs by using natural speech collected without specialized equipment. Recent advances in large language models (LLMs) have improved speech analysis by providing rich linguistic representations and strong generalization. In this study, we propose LSEAD, a speech-based AD detection framework using pretrained open-source LLMs. Speech recordings are automatically transcribed, and text embeddings are extracted using locally deployed LLMs. Principal component analysis (PCA) is applied to reduce dimensionality before classification. Because the framework relies only on speech transcripts and locally deployed models, it supports privacy-preserving AD risk assessment without external data exchange. We evaluate LSEAD on the ADReSS20 and ADReSSo2021 benchmark datasets. Experimental results show that LLM-based embeddings generalize well across datasets and improve AD classification accuracy by up to 5 percent over existing methods, especially for early-stage detection. These results demonstrate that LSEAD provides a practical, secure, and scalable approach for early AD screening.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.07206v1">Sub-Sampling for Positioning Privacy in ISAC: Deception by Aliasing via Sparse Arrays and Pilots</a></h3>
  
  <p><b>Published on:</b> 2026-08-07T13:19:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> L. Yashvanth, Christos Masouros, Suraj Srivastava, Aditya K. Jagannatham, Lajos Hanzo</p>
    <p><b>Summary:</b> Integrated sensing and communications (ISAC) enables simultaneous communication and sensing using shared spectrum and hardware resources in wireless systems. However, securing the sensing functionality against unauthorized receivers remains a fundamental challenge. In this paper, we propose a sub-sampling based sensing-privacy framework for communication-centric (CC)-ISAC systems that jointly exploits sparse arrays and sparse pilot allocations to induce controlled aliasing in the spatial and frequency domains, respectively. By interpreting antenna arrays and pilot subcarriers as spatial and frequency sampling mechanisms, respectively, we show that spatial-frequency undersampling naturally distorts the range-angle multiple-input multiple-output (MIMO) ambiguity function (AF) observed by an unauthorized receiver. To this end, we first derive a closed-form expression for the range-angle MIMO-AF, and subsequently characterize the ghost targets that arise due to spatial and frequency-domain aliasing. Next, we establish a sufficient condition under which these ambiguities jointly translate into positioning ambiguity and show that, for sufficiently large spatial and frequency sub-sampling factors, an unauthorized receiver inevitably positions a target at incorrect ghost positions. Finally, we show that the proposed sub-sampling framework preserves the native legitimate ISAC performance without introducing additional trade-offs. Numerical results verify the analysis and show that sparse arrays and sparse pilots naturally enable sensing and positioning privacy through deception by aliasing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.06888v1">Correlation Geometry of Quantum Sensor Networks: Local-Global Information Flow and Local Privacy</a></h3>
  
  <p><b>Published on:</b> 2026-08-07T07:21:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gong-Chu Li, Lei Chen, Xu-Song Hong, Hua-Qing Xu, Yuancheng Liu, Si-Qi Zhang, Jia-Hao Zhao, Geng Chen, Chuan-Feng Li, Guang-Can Guo</p>
    <p><b>Summary:</b> Quantum sensor networks typically encode N unknown parameters while targeting a single linear combination, rendering the N-1 remaining parameters as nuisance directions. To rigorously quantify estimation precision under such nuisances, we introduce the concept of effective quantum Fisher information (EQFI) and develop an exact EQFI-based phase map that systematically describes the allocation between local and global EQFI. Leveraging this geometric framework, we identify a fundamental bottleneck termed the "barrel effect": the global EQFI is strictly bounded by the weakest weighted local sensing capacity among all nodes. We further establish concrete conditions for saturating this bound. Crucially, this geometric map delineates how the trade-off between local and global EQFI depends dynamically on quantum correlations, and uncovers a counterintuitive "overcorrelated" regime where excessive correlations actively degrade both local and global performance. Finally, we apply the phase map to intrinsic local privacy and identify the condition under which every local parameter is inaccessible while the desired global combination remains estimable. Overall, our work provides a principled methodology for engineering optimal network states in quantum sensing architectures.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.05737v1">ABC: Numerical Data Collection under Local Differential Privacy without Prior Knowledge</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-06T08:19:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Incheol Baek, Hyungbin Kim, Yon Dohn Chung</p>
    <p><b>Summary:</b> Local Differential Privacy (LDP) provides strong privacy guarantees for collecting numerical data. A fundamental challenge, however, is that existing LDP mechanisms require a predefined data domain, which is often unknown in practice. This lack of prior knowledge creates a critical dilemma for the data collector: if the chosen domain is too narrow, values outside the range are clipped, leading to information loss. Conversely, if the domain is too wide, excessive noise is added during the privatization process, which degrades the quality of collected data. This highlights the need for methods that can dynamically estimate the data domain.
  In this work, we propose an adaptive LDP framework that addresses this problem. In our method, each user sends two pieces of information: their perturbed numerical data, and a privatized signal indicating if their original value was clipped by the current domain. By aggregating these signals, our proposed method, Adaptive Bounding of Clipping regions (ABC) method, iteratively adjusts the domain to fit the underlying data distribution without prior knowledge. Our theoretical analysis shows that the estimated data domain converges to an appropriate range.
  In the empirical evaluation, the results demonstrate that our framework significantly improves the quality of numerical data collection across various datasets and underlying LDP mechanisms. We also show that the estimated range successfully converges in practice and our approach is robust to its hyperparameters through comprehensive ablation studies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.05474v1">Exploring Privacy Leakage and Data Disclosure Violations in the MacOS Application Ecosystem</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-05T23:46:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jyotirmay Chauhan, Kostas Solomos, Mir Masood Ali, Jason Polakis</p>
    <p><b>Summary:</b> The systematic and excessive data collection practices of tech companies have rendered online privacy both a necessity and a sought-after commodity. However, while the privacy risks of the web, mobile, and IoT ecosystems have been extensively examined, desktop environments have been largely overlooked. As desktop apps continue to be widely used, they remain a critical yet understudied dimension of user privacy. In this paper, we address this gap by presenting the first, to our knowledge, comprehensive study of the mechanisms designed to regulate and disclose data collection and sharing practices in the macOS ecosystem. We adopt an app-development-centric view, and shed light on the interactions between the various macOS mechanisms that mediate apps' data access. Driven by our findings, we develop NutriScan, an analysis framework that incorporates both static and dynamic analysis techniques to create a consolidated view of macOS apps' data practices and disclosures. We use our system to dynamically analyze 1K macOS apps, and find that 85% of them access user-data APIs without disclosing it. 49.7% also exfiltrate data to advertising entities and hosting providers, 12.5% of which do so without a corresponding disclosure. We find that desktop apps are being leveraged by online trackers to enrich user profiles and device fingerprints, thus shedding new light on the true scope of the online tracking ecosystem. Our analysis reveals how the macOS app ecosystem is comprised of disjoint mechanisms with divergent data abstractions, thus increasing complexity for developers while also facilitating undisclosed privacy-invasive practices. Accordingly, we propose a series of mitigations that aim to both streamline the data disclosure process for developers and improve Apple's app vetting process.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.05115v1">Robust and Efficient Motion Reasoning for Privacy-Aware Classroom Incident Recognition</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-05T17:46:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Paritosh Parmar, Landy Lan, Hong Yang, Chen Yi, Chiat Pin Tay</p>
    <p><b>Summary:</b> Can computer vision help make classrooms safer? In this pilot study, we investigate privacy-aware and computationally efficient classroom incident recognition from CCTV-style observations. This setting remains underexplored, with limited benchmarks and few methods designed for the privacy, efficiency, and generalization demands of real-world deployment. We introduce a novel hybrid benchmark combining generative CCTV-style videos with real-world classroom pose data, and propose a lightweight, but robust motion-reasoning framework motivated by the observation that many incidents differ more in motion direction, speed, acceleration, and intensity than in pose alone. To that end, our method first constructs hierarchical kinematic representations of human actions. Our method then distills hierarchical, multi-order kinematic reasoning from a large teacher into a much smaller single-order student, enabling efficient per-person inference while preserving expressive motion understanding. Experiments show that our model outperforms substantially larger baselines at less than one-tenth of their computational cost, while also demonstrating stronger out-of-domain motion reasoning and zero-shot synthetic-to-real generalization. We will publicly release the benchmark, codebase, and supporting tools to facilitate further research in privacy-aware classroom safety.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.04501v1">Privacy-Preserving Action Recognition: Taxonomy, Methods, and Privacy-Utility Trade-offs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-08-05T06:38:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sareer Ul Amin, Muhammad Ayaz, Muhammad Munsif, Sanghyun Seo</p>
    <p><b>Summary:</b> Video surveillance in public safety, healthcare, and smart environments has made continuous human monitoring routine, raising real risks to personal identity and appearance. Privacy-preserving action recognition (PPAR) tackles the tension between the utility of video understanding and this exposure, and has drawn fast-growing interest. However, existing surveys remain narrow. Most catalog a single mechanism family, predate recent adversarial and hybrid work, or barely address evaluation. The result is a fragmented literature with incompatible threat models, inconsistent metrics, and no shared evaluation standard. We address this with a PRISMA-guided review of 32 peer-reviewed papers (2018--2026) drawn from 885 screened records. Methods sort into five families, namely adversarial learning (52%), skeleton-based (20%), cryptographic (12%), differential privacy (8%), and hybrid (8%), each with distinct privacy, utility, and efficiency trade-offs. Evaluation is the weak point. Only 10% of papers adopt a formal privacy definition, 65% rely on ad-hoc metrics, and 40% report an inconsistently defined cMAP. The trade-offs are steep. Skeleton methods reach about 85% accuracy but drop appearance, adversarial methods hold near 80% utility at moderate privacy (cMAP 0.9 to 0.3--0.5), and differential privacy often falls below 70%. Harder conditions stay under-tested, with fewer than 15% of papers checking cross-dataset generalization, under 10% testing adaptive attackers, and real-time edge deployment nearly untouched. We contribute a two-dimensional privacy-space taxonomy, a formal threat model, a comparative trade-off analysis, the PPAR Unified Evaluation Protocol, and a roadmap centered on benchmark standardization. With this grounding, we argue PPAR can move from prototypes toward deployment, with lessons extending to face recognition and medical imaging.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.04255v1">PriDyG: Privacy-preserving Dynamic Graph Inference with LLM-GNN Collaboration</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-04T22:23:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuyang Xia, Ruixuan Liu, Li Xiong</p>
    <p><b>Summary:</b> Graph inference over relational data can expose sensitive edge information, and this risk becomes more severe in dynamic graphs, where repeated model updates cause privacy loss to accumulate. We formulate Edge-level Differentially Private Dynamic Graph Inference (EDG) and propose PriDyG, a private inference framework that combines GNN-based structural learning with LLM-based semantic reasoning. PriDyG introduces incremental private multi-hop aggregation, which buffers newly arrived edges and processes each edge exactly once. By parallel composition, the total privacy cost equals that of a single static release, independent of the number or schedule of model updates. Compared with geometrically decaying budget allocation, incremental aggregation avoids exponentially increasing noise while preserving exact one-hop signals and at least half of two-hop information transfers. PriDyG further complements privatized GNN outputs with LLM predictions derived solely from node text, incurring no additional edge-level privacy cost. Experiments on four benchmarks for node classification and link prediction show that PriDyG consistently outperforms geometrically decaying baselines under the same privacy budget and matches the utility of naive per-update retraining while reducing cumulative privacy cost by up to three orders of magnitude.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.03940v1">Echoes in the Digital Abyss: Examining the Bubble Surrounding Security and Privacy Discourse in Social Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-08-04T17:10:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Reagan Dennison, Saanvi Sharma, Noshir Contractor, Sruti Bhagavatula</p>
    <p><b>Summary:</b> The dissemination of security and privacy education and guidance has been and still remains a challenge today. Social networks represent a potential avenue for sharing best practices, and experimentally they have been found to be effective at this task. While this appears promising, in the real world, security and privacy discussions would need to reach a wide range of people to be effective, avoiding the "interest bubbles" that commonly occur. We sought to understand how the communities surrounding security and privacy discourse operate, with a focus on what challenges need to be overcome to enable security and privacy discourse and advice to reach a wider audience.
  Indeed, we found that in-the-wild security and privacy discussions in social networks portray quite a different picture than in experimental settings. We built and analyzed the structure of a graph containing over 13 million users on the "X" platform (formerly "Twitter"), including 10,159 users who posted about security and privacy and their followers. Prior work has shown that users are more likely to consider information within social media if their like-minded social ties have visibly engaged with it. Our findings indicate that the users generating or participating in security discussions largely already belong to highly clustered technology and security- and privacy-related interest communities, which suggests that the people who are not already in the "inner circle" of relevant interests are likely not exposed effectively to these discussions. We conclude with reflections and ideas on increasing the reach of security and privacy guidance in social networks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.03737v1">Dependency Triad: A Metric to Quantify the Dependencies Between Attributes for Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-08-04T14:30:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sandaru Jayawardana, Sennur Ulukus, Ming Ding, Kanchana Thilakarathna</p>
    <p><b>Summary:</b> Collecting multidimensional user data is essential for extracting rich insights across various applications. Local Differential Privacy (LDP) has emerged as a de facto standard for mitigating privacy risks in such scenarios. A key challenge in privacy-preserving multidimensional data collection lies in inter-attribute dependencies, as they can inadvertently reveal correlated information and increase privacy vulnerabilities. Therefore, accurately measuring correlation-induced privacy leakage (CPL) is essential for privacy analysis and privacy-utility trade-off. However, existing CPL analysis solutions either require accurate prior knowledge or face scalability challenges for large numbers of attributes and high-cardinality attributes. These limit their practical applicability in real data. To address this research gap, we propose a novel metric, ``Dependency Triad'' (DT), which summarizes the pairwise dependency information relevant to CPL using three parameters and yields a \emph{constant-time} conservative estimator of pairwise CPL. DT explicitly models uncertainty in prior distributional knowledge through its parameters, delivering robust leakage estimates. Moreover, its robustness to sparse distributions makes it particularly suitable for high-cardinality attributes, while the pairwise formulation serves as a tractable building block for assessing total leakage in multidimensional settings. Extensive experiments on both synthetic and real datasets demonstrate that DT consistently estimates CPL across diverse dependency regimes and prior uncertainties.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.03700v1">When Agents Learn to Be You: Benchmarking Privacy Leakage, Impersonation Risk, and Defenses in Persona Skills</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-08-04T14:04:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yongli Xiang, Zhifang Zhang, Bojun Yang, Ziming Hong, Lei Feng, Miao Xu, Tongliang Liu</p>
    <p><b>Summary:</b> Persona skills distill personal interaction histories into portable and executable artifacts for downstream agents. While enabling flexible personalization, this process concentrates fragmented personal signals, amplifies their impact through reuse, and challenges defenses designed for individual records or retrieval-based memory. To systematically investigate the safety of the persona-skill pipeline, we introduce AntiSkillBench, an end-to-end benchmark for evaluating risks and defenses across the persona-skill pipeline. It comprises: (i) a dataset of 7,500 persona-grounded dialogue traces, constructed from 50 behaviorally rich profiles spanning diverse task scenarios; (ii) an evaluation suite that measures skill-level privacy leakage and agent-level attribute disclosure and behavioral impersonation across three skill-distillation strategies; and (iii) a defense evaluation covering four configurations across online and post-hoc interventions, including active risk suppression and passive provenance protection. Experiments across three frontier agents show that persona-skill risks persist across agent backbones and distillation protocols, extending from explicit attributes to communication styles and personality traits. Existing defenses exhibit limited and distillation-dependent effectiveness, failing to generalize across risk and distillation strategies. These results highlight AntiSkillBench as a challenging benchmark for developing privacy-preserving and authenticity-aware persona skills.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.03130v1">DP-MemView: A Memory Interface for Attribute-Level Transcript Privacy in Long-Term LLM Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-04T05:00:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jong Wook Kim, Byoungjae Min, Kennedy Edemacu, Yoonhyuk Choi, Sae-Hong Cho, Beakcheol Jang</p>
    <p><b>Summary:</b> Long-term memory enables persistent personalization in LLM agents, but repeated memory-conditioned responses can cumulatively reveal protected attributes even when they are never stated explicitly. We formalize this threat as adaptive transcript privacy and introduce DP-MemView, a differentially private interface that privately selects public response-conditioning views and exposes those views---rather than raw memory---to the response LLM. Each private selection is charged to every protected attribute whose memory group intersects the read set. Per-attribute ledgers block any selection that would exceed its cap and return a fixed generic view instead. Under an explicit interface contract, we prove pure B_a-DP for the entire adaptive transcript. We also extend the result to stores that differ across multiple protected groups and bound how much observing the transcript can change an adversary's prior odds. We evaluate the online and preallocated modes with three response LLMs on a controlled adjacent-store benchmark and a public-corpus transfer track. Both modes keep transcript distinguishability near chance while preserving target-required personalization and overall response quality. Further diagnostics show that removing key safeguards causes mismatched output support, missing ledger charges, revealing side channels, or growing long-horizon leakage.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.02774v1">Privacy-Preserving AI Verification via Minimal Information Disclosure</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-08-03T18:18:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sleem Abdelghafar, Gabriel Kulp</p>
    <p><b>Summary:</b> AI verification crosses a trust boundary: a verifier must learn enough to establish an authorized claim, yet the same evidence can reveal sensitive details about the model, workload, or hardware. We introduce minimal information disclosure (MID), which designs and quantifies the information content of verifier-facing evidence itself. MID measures collateral leakage with conditional mutual information: what the release reveals about the protected property after the authorized result is known. MID is general by design: it can accommodate different verification goals, protected properties, evidence sources, and deployment constraints. To demonstrate MID's practicality, we evaluate it on four physical measurements and six verification tasks spanning execution type, hardware identity, compute scale, and model identity. These experiments use three mechanism-design variables--the evidence channel, collection policy, and release transformation--but MID is not limited to these choices and can accommodate other deployable mechanisms. Across these tasks, MID produces three releases with perfect held-out verification and zero measured collateral leakage, while the remaining tasks yield explicit privacy--utility frontiers. MID also supports ZKP-certified releases: we demonstrate our proposed linear-projection mechanism using a Groth16 zk-SNARK.</p>
  </details>
</div>


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

