
<h2>2026-05</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.05017v1">Position: Embodied AI Requires a Privacy-Utility Trade-off</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E">
  <p><b>Published on:</b> 2026-05-06T15:16:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaoliang Fan, Jiarui Chen, Zhuodong Liu, Ziqi Yang, Peixuan Xu, Ruimin Shen, Junhui Liu, Jianzhong Qi, Cheng Wang</p>
    <p><b>Summary:</b> Embodied AI (EAI) systems are rapidly transitioning from simulations into real-world domestic and other sensitive environments. However, recent EAI solutions have largely demonstrated advancements within isolated stages such as instruction, perception, planning and interaction, without considering their coupled privacy implications in high-frequency deployments where privacy leakage is often irreversible. This position paper argues that optimizing these components independently creates a systemic privacy crisis when deployed in sensitive settings, thereby advancing the position that privacy in EAI is a life cycle-level architectural constraint rather than a stage-local feature. To address these challenges, we propose Secure Privacy Integration in Next-generation Embodied AI (SPINE), a unified privacy-aware framework that treats privacy as a dynamic control signal governing cross-stage coupling throughout the entire EAI life cycle. SPINE decomposes the EAI pipeline into various stages and establishes a multi-criterion privacy classification matrix to orchestrate contextual sensitivity across stage boundaries. We conduct preliminary simulation and real-world case studies to conceptually validate how privacy constraints propagate downstream to reshape system behavior, illustrating the insufficiency of fragmented privacy patches and motivating future research directions into secure yet functional embodied AI systems. We detail the SPINE framework and case studies at https://github.com/rminshen03/EAI_Privacy_Position.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.04977v1">ICPR 2026 Competition on Privacy-Preserving Person Re-Identification from Top-View RGB-Depth Camera (TVRID)</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-05-06T14:31:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Raphaël Delécluse, Hazem Wannous, Laurent Guimas</p>
    <p><b>Summary:</b> This companion paper reports the ICPR 2026 TVRID competition on privacy-aware top-view person re-identification. We present the competition setting, the released RGB-Depth dataset, and a summary of final results with descriptions of the top entries. TVRID contains 86 identities captured by four synchronized overhead Intel RealSense D455 cameras, with paired RGB/Depth streams and structured geometric variation across flat, ascent, descent, and oblique viewpoints. The evaluation protocol includes three tracks: RGB Re-ID, Depth Re-ID, and RGB$\leftrightarrow$Depth cross-modal retrieval. Submissions are ranked using mAP and CMC-1 under a unified server-side evaluation. The final results show a clear difficulty ordering (RGB $>$ Depth $>$ Cross-Modal), highlighting both the challenge of modality-constrained retrieval and the feasibility of strong performance with modality-invariant learning. By releasing the dataset at https://zenodo.org/records/17909410, the evaluation scripts at https://github.com/RaphaelDel/ICPR-TVRID, and the accompanying documentation, TVRID establishes a reproducible benchmark for top-view, depth-based, and cross-modal person re-id.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.04911v1">Breaking the Quality-Privacy Tradeoff in Tabular Data Generation via In-Context Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-06T13:38:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xinyan Han, Yan Lu, Xiaoyu Lin, Yuanyuan Jiang, Yuanrui Wang, Xuanyue Li, Wenchao Zou, Xingxuan Zhang</p>
    <p><b>Summary:</b> Tabular data synthesis aims to generate high-quality data while preserving privacy. However, we find that existing tabular generative models exhibit a clear tradeoff in the small-data regime: improving data quality typically comes at the cost of increased memorization of training samples, thereby weakening privacy protection. This tradeoff arises because small training sets make it difficult for dataset-specific generative models to distinguish generalizable structure from sample-specific patterns. To address this, we propose DiffICL, which formulates tabular data generation as an in-context learning problem. Instead of fitting each dataset from scratch,DiffICL leverages pretrained structural priors learned from a large collection of datasets, enabling it to infer data distributions from limited context rather than memorizing individual samples. We evaluate DiffICL on 14 real-world datasets. Results show that DiffICL improves both data quality and privacy, and generate synthetic data that provides effective data augmentation. Our findings suggest that the quality-privacy tradeoff can be improved through better training paradigms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.04519v1">FL-Sailer: Efficient and Privacy-Preserving Federated Learning for Scalable Single-Cell Epigenetic Data Analysis via Adaptive Sampling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2026-05-06T05:56:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guangyi Zhang, Yi Dai, Yiyun He, Junhao Liu</p>
    <p><b>Summary:</b> Single-cell ATAC-seq (scATAC-seq) enables high-resolution mapping of chromatin accessibility, yet privacy regulations and data size constraints hinder multi-institutional sharing. Federated learning (FL) offers a privacy-preserving alternative, but faces three fundamental barriers in scATAC-seq analysis: ultra-high dimensionality, extreme sparsity, and severe cross-institutional heterogeneity. We propose FL-Sailer, the first FL framework designed for scATAC-seq data. FL-Sailer integrates two key innovations: (i) adaptive leverage score sampling, which selects biologically interpretable features while reducing dimensionality by 80%, and (ii) an invariant VAE architecture, which disentangles biological signals from technical confounders via mutual information minimization. We provide a convergence guarantee, showing that FL-Sailer converges to an approximate solution of the original high-dimensional problem with bounded error. Extensive experiments on synthetic and real epigenomic datasets demonstrate that FL-Sailer not only enables previously infeasible multi-institutional collaborations but also surpasses centralized methods by leveraging adaptive sampling as an implicit regularizer to suppress technical noise. Our work establishes that federated learning, when tailored to domain-specific challenges, can become a superior paradigm for collaborative epigenomic research.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.04221v1">Self-Prompting Small Language Models for Privacy-Sensitive Clinical Information Extraction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-05T19:03:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yao-Shun Chuang, Tushti Mody, Uday Pratap Singh, Shirindokht Shiraz, Chun-Teh Lee, Ryan Brandon, Muhammad F Walji, Xiaoqian Jiang, Bunmi Tokede</p>
    <p><b>Summary:</b> Clinical named entity recognition from dental progress notes is challenging because documentation is highly unstructured, domain-specific, and often privacy-sensitive. We developed a locally deployable framework that enables small language models to self-generate, verify, refine, and evaluate entity-specific prompts for extracting multiple clinical entities from dental notes. Using 1,200 annotated notes, we evaluated candidate open-weight models with multi-prompt ensemble inference and further adapted selected models using QLoRA-based supervised fine-tuning and direct preference optimization. Model performance varied substantially, highlighting the need for task-specific evaluation rather than reliance on generic benchmarks. Qwen2.5-14B-Instruct achieved the strongest baseline performance. After DPO, Qwen2.5-14B-Instruct and Llama-3.1-8B-Instruct achieved micro/macro F1 scores of 0.864/0.837 and 0.806/0.797, respectively. These findings suggest that automated prompt optimization combined with lightweight preference-based post-training can support scalable clinical information extraction using locally deployed small language models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.04029v1">Stayin' Aligned Over Time: Towards Longitudinal Human-LLM Alignment via Contextual Reflection and Privacy-Preserving Behavioral Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-05-05T17:51:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Simret Araya Gebreegziabher, Allison E Sproul, Yinuo Yang, Chaoran Chen, Diego Gómez-Zará, Toby Jia-Jun Li</p>
    <p><b>Summary:</b> Current human-AI alignment and evaluation methods for large language models (LLMs) often rely on preference signals collected immediately after an interaction. This practice implicitly treats preference as static, even though many LLM-mediated decisions unfold over time and may be re-evaluated differently after real-world consequences and observed outcomes. Therefore, we argue for a methodological shift from single-moment preference elicitation to longitudinal, context-situated alignment measurement. We present a methodological framework for collecting temporally grounded alignment signals by combining (1) in-situ preference capture, (2) context-triggered follow-up preference reflection, and (3) privacy-preserving behavioral traces that help interpret preference change. As an instantiation of this methodology, we introduce BITE, a browser-based system that detects consequential LLM interactions, prompts reflection across later decision points, and supports progressive, user-controlled consent for sharing behavioral data. Through a two week longitudinal deployment study with 8 participants, our approach surfaced differences between immediate and later user preferences in accuracy, relevance and other dimensions of the LLM output. Our findings highlight the limitations of single-moment preference datasets and underscore the importance of longitudinal methods for alignment evaluation in everyday use.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.03945v1">Integrating Feature Correlation in Differential Privacy with Applications in DP-ERM</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2026-05-05T16:32:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tianyu Wang, Luhao Zhang, Rachel Cummings</p>
    <p><b>Summary:</b> Standard differential privacy imposes uniform privacy constraints across all features, overlooking the inherent distinction between sensitive and insensitive features in practice. In this paper, we introduce a relaxed definition of differential privacy that accounts for such heterogeneity, allowing certain features to be treated as insensitive even when correlated with sensitive ones. We propose a correlation-aware framework, $\textsf{CorrDP}$, which relaxes privacy for insensitive features while accounting for their correlations with sensitive features, with the correlations quantified using total variation distance. We design algorithms for differentially private empirical risk minimization (DP-ERM) under the $\textsf{CorrDP}$ framework, incorporating distance-dependent noise into gradients for improved theoretical utility guarantees. When the correlation distance is unknown, we estimate it from the dataset and show that it achieves a comparable privacy-utility guarantee. We perform experiments on synthetic and real-world datasets and show that $\textsf{CorrDP}$-based DP-ERM algorithms consistently outperform the standard DP framework in the presence of insensitive features.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.03188v1">Dependency-Aware Privacy for Multi-turn Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-04T22:13:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Divyam Anshumaan, Sarthak Choudhary, Nils Palumbo, Somesh Jha</p>
    <p><b>Summary:</b> LLM agents release private data across multi-service interactions. Existing prompt sanitizers based on metric differential privacy treat each release independently, so adversaries combining releases across turns can recover private attributes; privacy degrades with every release.
  This degradation is fundamental: when private attributes are the \emph{roots} of a computation graph, independently noising a derived value amplifies the root's distinguishability by up to the deriving function's Lipschitz constant $L$, which can far exceed the nominal privacy parameter for nonlinear functions in medical and financial workflows.
  RootGuard sanitizes root values once and computes subsequent releases deterministically from the noised roots. By the post-processing theorem, the privacy guarantee depends only on the initial root sanitization, regardless of the adversary's functions or number of turns, and derived values inherit privacy at zero marginal cost. RootGuard further exploits structural domain knowledge (e.g., BMI from height and weight, or a known target function) to allocate budget across roots, improving the privacy-utility tradeoff.
  A worst-case adversary forcing $t$ turns increases the total budget $B = t \cdot \varepsilon$. RootGuard distributes this larger budget across roots, while independent noising spends $\varepsilon$ per release and gives the adversary $t$ observations to combine via MAP reconstruction. This yields a \emph{double asymmetry}: more turns aid RootGuard while weakening independent noising.
  On eight NHANES medical diagnostic templates, RootGuard achieves $2.3$--$3.0\times$ lower target error than independent noising at $\varepsilon = 0.1$ (7.6\% vs.\ 17.1\% wMAPE at $B = (2k{+}1)\varepsilon$). Under MAP reconstruction, more queries strengthen attacks against independent noising while RootGuard remains invariant.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.03069v1">Distributed Deep Variational Approach for Privacy-preserving Data Release</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-04T18:41:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zahir Alsulaimawi, Huaping Liu</p>
    <p><b>Summary:</b> Federated learning (FL) lets distributed nodes train a shared model without exchanging their raw data, but in privacy-sensitive deployments medical sensors, IoT devices, wearables the protection offered by keeping data local is incomplete: gradients, model updates, and the released representations themselves can leak sensitive attributes. We propose the \emph{Gaussian Privacy Protector} (GPP), a data-release framework for continuous, high-dimensional inputs that learns a stochastic encoder mapping raw data to a low-dimensional sanitized representation. The encoder is trained against a variational lower bound on the mutual information between the released representation and a designated sensitive attribute, while a separate cross-entropy term preserves a designated utility attribute, with a Lagrange multiplier $β$ controlling the trade-off. We then extend GPP to the federated setting, in which each client trains a local encoder, sensitive labels never leave the client, and the aggregator receives only sanitized representations giving instance-level privacy protection in addition to the standard ``raw data stays local'' guarantee of FL. We evaluate GPP on MNIST (digit-sum utility, parity sensitive), CelebA (smiling vs.\ gender), and HAPT-Recognition (activity vs.\ subject identity). Across all three benchmarks, GPP attains utility within roughly one percentage point of an unconstrained autoencoder baseline while reducing the adversary's AUC to near random guessing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.02886v1">CityOS: Privacy Architecture for Urban Sensing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Operating Systems-04E762">
  <p><b>Published on:</b> 2026-05-04T17:54:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Giorgio Cavicchioli, Mark Chen, Navid Salami Pargoo, Shuren Xia, Xiaotian Zhou, Roxana Geambasu, Jason Nieh, Jorge Ortiz</p>
    <p><b>Summary:</b> Cities are rapidly deploying sensing infrastructure -- cameras, environmental sensors, and connected kiosks -- that continuously observe public spaces, yet they lack a system architecture governing how applications access, aggregate, and retain this data, creating privacy risks and preventing consistent policy enforcement. We present CityOS, an operating system for urban sensing that mediates application access to sensor data through a three-tier API inspired by structured, privacy-conscious web interfaces. The tiers expand the spatial scope of data access while imposing progressively stronger privacy constraints: On-Scene supports real-time sensing with raw data confined to the local context; Single-Locality Aggregation enables differentially private longitudinal statistics at a fixed location; and Cross-Locality Aggregation supports citywide analytics via aggregation across locations, with user devices enforcing per-user privacy budgets. CityOS runs as an edge runtime that executes untrusted applications in ephemeral containers, enforcing these policies and providing transparency via broadcasts of differential privacy loss. We implement CityOS and applications across all tiers -- including pedestrian safety alerts, real-time and forecast parking availability, traffic dashboards, and subway trajectory measurement -- and show that it supports practical streetscape applications while enforcing strong privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.04108v1">MuCALD-SplitFed: Causal-Latent Diffusion for Privacy-Preserving Multi-Task Split-Federated Medical Image Segmentation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-05-04T16:43:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chamani Shiranthika, Hadi Hadizadeh, Parvaneh Saeedi</p>
    <p><b>Summary:</b> Federated Learning enables decentralized training by aggregating model updates across clients without sharing raw data, while Split Federated Learning further partitions the model between clients and a server to reduce computation and communication at the client side. However, decentralized medical institutions rarely operate on a single shared task, making standard Federated and SplitFed collaborations poorly aligned with real clinical workflows. Multi-task FL extends these frameworks by allowing clients to handle different tasks, but often introduces instability and privacy vulnerabilities. This study proposes \textbf{MuCALD-SplitFed}, a multi-task SplitFed framework that integrates causal representation learning and latent diffusion. Experiments show MuCALD-SplitFed consistently improves segmentation, while baseline SplitFed fails to converge. The proposed approach further reduces information leakage at split points, mitigating reconstruction-based and membership inference attacks. Additionally, MuCALD SplitFed outperforms state-of-the-art personalized FL and multi-task FL approaches. The code repository is: https://github.com/ChamaniS/MuCALD_SplitFed.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.02724v1">Period-conscious Time-series Reconstruction under Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Multimedia-5BC0EB">
  <p><b>Published on:</b> 2026-05-04T15:25:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yaxuan Wang, Tianxin Li, Enji Liang, Yue Fu, Yanran Wang</p>
    <p><b>Summary:</b> Periodic patterns are fundamental cues in multimedia signals and systems, including repetitive motion in video (e.g., gait cycles), rhythmic and pitch-related structure in audio, and recurring textures in image sequences. When such user-generated streams are collected from edge devices, local differential privacy (LDP) is appealing because it perturbs data before upload; however, the injected noise can corrupt spectral peaks and induce phase drift, making period estimation unreliable and degrading reconstruction quality. We propose \textbf{CPR} (\textit{Cycle and Phase Recovery}), a period-aware reconstruction framework for periodic time series under LDP. CPR performs multi-scale period probing and multi-consensus selection to suppress noise-induced spectral interference, then aggregates perturbed samples at matched within-cycle phase positions to stabilize phase alignment across cycles. To recover the underlying per-phase values, CPR combines EM-based denoising with kernel density estimation, improving robustness under tight privacy budgets. Experiments on two real-world periodic datasets demonstrate that CPR better preserves periodic structure and consistently achieves lower reconstruction error than representative LDP baselines, especially in the low-$ε$ regime.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.02553v1">Noisy Networks, Nosy Neighbors: Simple Privacy Attacks Against Residential Wireless Traffic</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-04T13:01:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arne Roszeitis, Bartosz Burgiel, Victor Jüttner, Erik Buchmann</p>
    <p><b>Summary:</b> Smart devices, such as light bulbs, TVs, fridges, etc., equipped with computing capabilities and wireless communication, are part of everyday life in many households. Previous work has already shown that a passive eavesdropper can derive private information, household routines, etc., from the network traffic of smart devices. However, existing attacks rely on capable adversaries with specialized machine learning expertise, labeled training data and reference devices, leaving it unclear how vulnerable ordinary households are to less sophisticated attackers. In this paper, we investigate the extent to which a ,,casual attacker'' with straightforward IT skills and no specialized cybersecurity or ML tooling can reproduce such privacy attacks. Operating from an adjacent room in a real-world apartment building, we constrain our adversary to use only three off-the-shelf Raspberry Pis, Wireshark, and basic Python scripts. Through a three-week study, we demonstrate that this casual attacker can manually identify devices, recognize user states, track smartphone movements through walls via RSSI triangulation, and successfully extract detailed daily routines, including sleep patterns of guests. Our findings show that smart-home privacy leakage is a threat even from low-resourced, straightforward adversaries, e.g., neighbors.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.02372v1">Privacy Preserving Machine Learning Workflow: from Anonymization to Personalized Differential Privacy Budgets in Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-04T09:15:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Judith Sáinz-Pardo Díaz, Álvaro López García</p>
    <p><b>Summary:</b> The growing development of artificial intelligence based solutions, together with privacy legislation, has driven the rise of the so-called privacy preserving machine learning architectures, such as federated learning. While federated learning enables model training on decentralized data preventing their sharing and centralization, it still faces several challenges related to data integrity and privacy. This paper presents a comprehensive privacy preserving federated learning workflow for sensitive tabular data, including anonymization and differential privacy techniques. We also introduce a formal definition for the concept of client drift, together with ways of detecting it to mitigate poisoning attacks. Then, we detail a complete methodology for assigning personalized privacy budgets for global differential privacy to the different clients participating in the network, based on a re-identification risk metric. The proposed methodology is presented and tested on an openly available dataset of medical records. Within the experimental setup we show that the approach based on personalized budgets, compared to the architecture including global differential privacy with fixed privacy budget, achieves a better model performance in terms of two error metrics.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.02319v1">Optimal Privacy-Utility Trade-Offs in LDP: Functional and Geometric Perspectives</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-05-04T08:15:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Seung-Hyun Nam, Hyun-Young Park, Si-Hyeon Lee</p>
    <p><b>Summary:</b> Local differential privacy (LDP) has emerged as a gold-standard framework for privacy-preserving data analysis. However, characterizing the optimal privacy-utility trade-off (PUT) and the corresponding optimal LDP channels remains largely fragmented, relying on problem-specific, case-by-case analyses. In this work, we develop a unified theoretical framework that systematically characterizes the optimal PUT and optimal LDP channels for general privacy-preserving statistical decision-making problems. We first identify key functional properties of Bayesian and minimax risks as functions of the LDP channel, including the data processing inequality (DPI), direct-sum quasi-convexity (or additivity), concavity, and symmetry invariance. Leveraging these properties, we reduce the optimization domain required to compute the optimal PUT. Additionally, building on convex geometric insights, we establish a one-to-one correspondence between maximal LDP channels under the Blackwell order and a finite-dimensional polytope, yielding an exact geometric characterization. This result renders the optimal PUT computationally tractable via vertex enumeration or linear programming. Furthermore, when the underlying problem exhibits symmetries characterized by a transitive group action, we derive an exact analytic expression for the optimal PUT, leading to closed-form solutions without numerical optimization. Our framework applies broadly beyond risk minimization, encompassing the maximization of information-theoretic measures such as mutual information, $f$-divergences, and Fisher information over LDP channels. We demonstrate the efficacy of our theoretical framework by recovering or strengthening several known results, and deriving exact analytic expressions for the optimal PUTs in specific tasks that were previously unaddressed.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.02297v1">Graph Federated Unlearning for Privacy Preservation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-04T07:42:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruotong Ma, Wentao Yu, Qizhou Wang, Jie Yang, Chen Gong</p>
    <p><b>Summary:</b> Graph federated learning (GFL) facilitates decentralized training on distributed graph data while keeping sensitive user information local, aligning with policies such as GDPR and CCPA that grant users the right to freely join or withdraw from learning systems. However, even decentralized, user information can persist after quitting, potentially propagating to central servers and then redistributing to malicious clients. This privacy leakage during user withdrawal, despite its importance, has received seldom attention in GFL. To fill the gap, we explore the potential of machine unlearning (MU) to thoroughly remove user information. However, classical MU methods are known to degrade overall performance, a problem that is exacerbated in GFL due to local message passing and global model collaboration. To this end, we make two adjustments to mitigate this challenge for GFL. First, we ensure unlearning updates that minimally affect overall performance, steering them in directions orthogonal to the gradients from learning other data. Second, we introduce virtual clients, maintained by the central server, to preserve graph topology and global embeddings without recovering information of removed entities. We conduct comprehensive experiments under a representative user-withdrawal scenario and propose a novel membership inference framework to rigorously evaluate and validate the reliability of our privacy preservation. The experimental results demonstrate the effectiveness of our approach, which also surpasses the performance of seven state-of-the-art baseline methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.02255v1">On the Privacy of LLMs: An Ablation Study</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-04T06:06:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Karima Makhlouf, Lamiaa Basyoni, Syed Khaderi, Gabriel Marquez, Peter Sotomango, Mahmoud Awawdah, Sami Zhioua</p>
    <p><b>Summary:</b> Large language models (LLMs) are increasingly deployed in interactive and retrieval-augmented settings, raising significant privacy concerns. While attacks such as Membership Inference (MIA), Attribute Inference (AIA), Data Extraction (DEA), and Backdoor Attacks (BA) have been studied, they are typically analyzed in isolation, leaving a gap in understanding their behavior under common system factors. In this paper, we introduce a unified threat model and notation, reproduce a representative set of privacy attacks, and conduct a structured ablation study to evaluate the impact of key factors such as model architecture, scale, dataset characteristics, and retrieval configuration. Our analysis reveals clear differences across attack types. Membership inference attacks, particularly mask-based variants, exhibit strong and reliable signals, while backdoor attacks achieve consistently high success rates due to their trigger-based nature. In contrast, attribute inference and data extraction attacks remain more challenging, resulting in lower accuracy, yet they pose significant risks as they target sensitive personal information. Overall, these results highlight that privacy risks in LLM systems are highly context-dependent and driven by design choices, emphasizing the need for holistic evaluation and informed deployment practices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.02169v1">Heterogeneous Model Fusion for Privacy-Aware Multi-Camera Surveillance via Synthetic Domain Adaptation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-04T02:58:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Peggy Joy Lu, Wei-Yu Chen, Yao-Tsung Huang, Vincent Shin-Mu Tseng</p>
    <p><b>Summary:</b> We propose HeroCrystal, a novel privacy-preserving framework for multi-camera domain-adaptive object detection, addressing challenges such as data privacy, class imbalance, and heterogeneous architectures. Our framework consists of three key stages. In the Generated Stage, we introduce a one-shot, target-aware diffusion-based generation module that learns visual style from a single target-domain image while leveraging prompt-based control to synthesize specific object instances. Unlike conventional style transfer-based methods that require large target datasets and ignore semantic-level discrepancies, our approach enables privacy-preserving augmentation to reduce ethical concerns, and introduces controllable rare object generation to mitigate long-tailed category degradation. In the Federated Stage, we employ probabilistic Faster R-CNN on the client side to improve localization accuracy, and a dynamic model contrastive strategy to suppress domain-specific bias. The server side performs model fusion across heterogeneous architectures without accessing raw data. Finally, in the Distilled Stage, we propose an inconsistent categories integration algorithm to resolve label inconsistency and architecture heterogeneity across clients. Extensive experiments on multiple cross-domain detection benchmarks demonstrate that our method outperforms existing multi-source domain adaptation and federated learning baselines under multi-class, privacy-preserving settings. Our method improves mAP by +2.1% over prior privacy-preserving approaches and achieves a new state-of-the-art mAP of 33.4%, highlighting the effectiveness of HeroCrystal in enabling practical multi-camera AI surveillance systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.02077v1">Obscura: Privacy-Preserving Protocol for the Algorand Blockchain Using LSAG Ring Signatures</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-03T22:33:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Navid Azimi</p>
    <p><b>Summary:</b> While public blockchains provide transparent and auditable transaction histories, they inherently compromise user privacy. Existing privacy-enhancing protocols, such as those deployed on Ethereum, typically rely on succinct zero-knowledge proofs (zk-SNARKs) to obscure the transaction graph. However, implementing comparable cryptographic guarantees on high-throughput blockchains like Algorand is challenging due to strict per-call execution budgets and the state contention introduced by global Merkle accumulators. This paper presents Obscura, a decentralized, non-custodial privacy protocol tailored for constrained smart contract environments. Obscura achieves transaction anonymity using Linkable Spontaneous Anonymous Group (LSAG) signatures over the BN254 elliptic curve, verified entirely on-chain. To overcome limitations of the Algorand Virtual Machine (AVM), we introduce a novel state model that leverages Algorand's Box Storage for $O(1)$ commitment membership checks, eliminating the need for global Merkle accumulators, and a dynamic opcode-budget expansion mechanism via pooled inner application calls. Our implementation demonstrates that signer-ambiguous privacy is practical and efficient on Algorand without relying on trusted setups or succinct proofs. Obscura provides a robust privacy layer for transparent ledgers, bridging the gap between high-throughput blockchain architectures and the dual requirements of cryptographic privacy and selective auditability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.02977v1">Contrastive Privacy: A Semantic Approach to Measuring Privacy of AI-based Sanitization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-03T21:33:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> George Bissias, Eugene Bagdasarian, Brian Neil Levine</p>
    <p><b>Summary:</b> To sanitize specific concepts from imagery and text, privacy mechanisms with formal guarantees are often eschewed in practice in favor of more intuitive techniques. AI-based sanitization is poised to grow in popularity because it can work with the semantics of natural language concepts; e.g., a prompt to "remove faces, clothing, and body shape". Many approaches exist commercially and as prior work. But, the evaluation of such approaches has been bespoke and without formal guarantees.
  To fill this gap, we propose contrastive privacy, a formal definition of privacy that provides a systematic and quantitative test of sanitized media that has a semantic interpretation. It is independent of the model and mechanism used and operates across multiple media modalities. Contrastive privacy provides guarantees under ideal conditions; and we show how to operationalize the definition with imperfect measures of semantics, provided by models like CLIP, that can connect concepts latently. Notably, the algorithm contrasts sanitized media with other images from the same corpus to arrive at a determination; no manual labeling is involved.
  In our experiments, we apply our privacy test to both images and text using frontier models: some generate concepts to sanitize and others perform the sanitization. With our test we quantify sanitization success across 34 combinations of models on images, and for 15 models on text. The approach not only quantifies success overall, it identifies specific failures from a sanitized corpus. Further, it is independent of the mechanism used for sanitization, whether by darkening pixels, blurring, or applying more advanced means of obfuscation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.02016v1">What's on Your Mind? Exploring Privacy of Mental Health Apps</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-05-03T18:42:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chloe Georgiou, Hans Lu, Emiliano De Cristofaro, Gene Tsudik</p>
    <p><b>Summary:</b> Therapy and life-coaching apps have been rapidly growing in number, flavors, and popularity. However, their users routinely share highly sensitive and personal information, such as traumas, fantasies, desires, relationship difficulties, and other mental health concerns. This prompts the need for an empirical analysis of privacy practices in this ecosystem, and particularly the alignment between these apps' privacy policies and their actual behavior. In this paper, we present a comprehensive analysis of 25 popular Android mental health and life-coaching apps, combining static analysis, dynamic network capture, and LLM-assisted privacy policy extraction validated against manual annotation.
  Our findings highlight serious concerns and substantial transparency gaps. First, every app embeds at least one tracker SDK that its privacy policy does not name, and 68% of apps fail to disclose at least half of the trackers detected in their APKs; Talkie alone embeds 20 while naming none. Second, we identify 16 permission-policy contradictions across 13 apps, i.e., a dangerous permission is declared in the manifest but omitted from the policy, including 6 apps that request camera or microphone access without disclosing photo, video, or audio collection. Third, 48% of apps disclose third-party AI processing (e.g., via OpenAI, Anthropic, Groq), with one app sending journal entries to all three simultaneously, while 7 apps use only generic language that leaves recipients unidentified. Taken together, our findings demonstrate that current disclosure practices fall short of the transparency required for meaningful informed consent. We argue for a significantly updated regulatory framework governing therapy apps in the spirit of the professional and ethical standards that bind licensed human therapists.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.02005v1">Privy: From Fine Print to Fair Practice in Privacy Rights Exercise</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-05-03T18:24:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qi Sun, Ziyang Li, Yinzhi Cao, Yaxing Yao</p>
    <p><b>Summary:</b> Privacy regulations such as the CCPA and GDPR grant individuals rights over their personal data, yet it remains challenging for most users to exercise them in practice due to vague policy interpretation and unapproachable settings on web interfaces. We introduce Privy, an LLM-powered browser assistant that guides users through exercising their privacy rights on websites. Privy automatically analyzes a website's privacy policy and surfaces the specific rights available as action labels in a side panel. When a user selects a right, Privy provides step-by-step guidance and navigation, presenting direct links, generating email templates, or guiding form completion. Users can also request on-demand policy evidence and rights education to enhance their literacy. A technical evaluation across 14 websites shows that Privy extracts rights with high precision (0.979) and completes 96.3\% of privacy tasks in an average of 3.2 steps. A user study (N=15) also demonstrates the overall high-level of perceived helpfulness among users. Our findings suggest that comprehension and usability are not two separate challenges but a single interaction problem, and that effective privacy support requires integration of policy understanding and privacy actions. We offer design suggestions for future privacy assistants.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.01987v1">Misclassification Rate and Privacy-Utility Trade-offs in Graph Convolutional Networks via Subsampling Stability</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-03T17:42:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yexin Zhang, Zhongtian Ma, Qiaosheng Zhang, Zhen Wang</p>
    <p><b>Summary:</b> We study differential privacy (DP) in Graph Convolutional Networks (GCNs) through the framework of \textit{subsampling stability}. We derive upper bounds on the misclassification rate that depend explicitly on the subsampling probability $p_s$. Furthermore, we characterize the \textit{privacy--utility trade-off} by identifying feasible ranges of $p_s$; if $p_s$ is too large, the stability-based privacy condition becomes difficult to satisfy, yielding vacuous guarantees, whereas if it is too small, accuracy deteriorates. Our results provide the first rigorous theoretical framework for understanding subsampling stability in GCNs under DP.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.01810v1">Federated Semi-Supervised Graph Neural Networks with Prototype-Guided Pseudo-Labeling for Privacy-Preserving Gestational Diabetes Mellitus Prediction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-03T10:26:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> G. Victor Daniela, A. Mallikarjuna Reddya, Uday Kumar Addankia, Sridhar Reddy Gogua, Sravanth Kumar Ramakuria</p>
    <p><b>Summary:</b> Gestational Diabetes Mellitus (GDM) is a high-prevalence pregnancy complication that requires accurate early risk stratification to reduce maternal and fetal morbidity. However, real-world clinical deployment of machine learning is hindered by two coupled constraints: (i) label scarcity, where a large fraction of electronic health records (EHR) lack confirmed diagnostic labels, and (ii) data privacy, which prevents sharing patient-level data across hospitals. This paper proposes FedTGNN-SS, a privacy-preserving federated semi-supervised framework for clinical tabular EHR. Each hospital builds a local k-nearest-neighbor patient similarity graph and trains a topology-adaptive GNN encoder. To robustly exploit unlabeled records, FedTGNN-SS combines (1) prototype-guided pseudo-labeling with neighborhood agreement, (2) adaptive graph refinement that periodically updates the k-NN graph using learned embeddings, (3) clinical-aware consistency augmentation applied only to continuous variables, and (4) privacy-safe prototype sharing that exchanges only class-level centroids. Across three diabetes-related datasets (GDM: N = 3,525; Pima: N = 768; Early Stage: N = 520) under 10\%-80\% missing labels per silo, FedTGNN-SS achieves 56 significant wins ($p < 0.05$) against 11 federated baselines and attains strong AUROC under extreme scarcity (Pima: 0.8037 at 80\% missing, Early Stage: 0.9634 at 80\% missing).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.01679v1">Class-Aware Adaptive Differential Privacy in Deep Learning for Sensor-Based Fall Detection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-03T02:34:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joydeb Kumar Sana</p>
    <p><b>Summary:</b> Fall detection is a critical task in healthcare, particularly for elderly people. Timely fall detection and treatment can prevent severe injuries. Sensor-based activity data can be used to detect fall. However, this data are highly sensitive and raises significant privacy concerns. Existing privacy approaches apply uniform noise across all training samples, which affects the prediction performance. To address this limitation, we propose a Class-Aware Adaptive Differential Privacy (CA-ADP) framework integrated with a hybrid 3D Convolutional Neural Network and Bidirectional Long Short-Term Memory (3D CNN-BiLSTM) architecture. The CA-ADP mechanism dynamically adjusts the magnitude of noise added to gradients based on the class composition of each mini-batch. This process ensures privacy while mitigates performance degradation. We formally analyze the $(ε,δ)$-Differential Privacy guarantee and provide a privacy-utility trade-off analysis. The proposed method is evaluated on three public benchmark datasets, namely SisFall, UP-Fall, and MobiAct. The experimental results show that the proposed privacy model achieves improvements of 3.3\%, 8.5\%, and 7.5\% over the conventional privacy-based model in terms of F-score for the SisFall, UP-Fall, and MobiAct datasets, respectively. Comparisons with prior studies show that the CA-AD based framework achieves competitive performance and provides formal privacy guarantees, which are largely overlooked in existing studies. Wilcoxon signed-rank tests confirm that the proposed mechanism consistently outperforms conventional differential privacy. Those results establish the proposed CA-ADP framework as an effective approach to privacy-preserving fall detection in real-world healthcare settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.01217v1">Asymmetric Invertible Threat: Learning Reversible Privacy Defense for Face Recognition</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-05-02T03:18:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiabei Zhang, Ziyuan Yang, Andrew Beng Jin Teoh, Yi Zhang</p>
    <p><b>Summary:</b> Face Recognition systems are widely deployed in real-world applications, but they also raise privacy concerns due to unauthorized collection and misuse of facial data. Existing adversarial privacy protection methods rely on input-space perturbations to obfuscate identity information, yet their protection can degrade when adversaries learn restoration or purification mappings that partially invert the transformation. We study this setting as an asymmetric adversarial attack, in which reverse manipulation becomes feasible because existing defense paradigms do not control reversibility. To address this problem, we propose Asymmetric Reversible Face Protection (ARFP), a restoration-aware extension of personalized face cloaking that integrates privacy protection, keyed recovery, and tamper indication in a single framework. ARFP consists of three components: Key-Conditioned Manifold Binding, which ties the protection transformation to a user-provided key; Adversarial Restoration-Aware Training, which introduces a surrogate restoration adversary during training to improve robustness against evaluated inverse purification attacks; and Authorized Reversible Restoration, which supports recovery with the correct key while providing nonce-based tamper indication. Extensive experiments under the threat models considered in this work show that ARFP improves resistance to the evaluated restoration attacks while preserving authorized recovery utility. These results provide empirical evidence of key-sensitive recovery behavior and tamper awareness in the tested settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.01204v1">FLRSP: Privacy-Preserving Federated Learning Using Randomly Selected Model Parameters</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-02T02:43:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hiroto Sawada, Shoko Imaizumi, Hitoshi Kiya</p>
    <p><b>Summary:</b> In this paper, we propose a method for privacy-preserving federated learning that uses randomly selected model parameters to update global models. High-quality deep neural networks (DNN) models require a huge amount of training data in general, but model training raises privacy concerns when dealing with sensitive or personal information. Federated learning is a distributed machine learning framework in which multiple clients and a server train a model collaboratively. However, if the shared updates are compromised, an attacker may reconstruct the original training data. In addition, previous methods for improving robustness generally reduce the accuracy. To overcome these issues, in our method called federated learning using randomly selected model parameters (FLRSP), model parameters computed in each local server are randomly selected and shared to update a global model in a central server. In experiments, image classification tasks were carried out on the ResNet34 architecture and the Vision Transformer (ViT) under the use of Federated Stochastic Gradient Descent (FedSGD) and Federated Averaging (FedAvg), and the results demonstrated our method's effectiveness in terms of image classification accuracy and robustness against state-of-the-art attacks compared with previous methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.01137v1">Metric-Normalized Posterior Leakage (mPL): Attacker-Aligned Privacy for Joint Consumption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-01T22:27:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gaoyi Chen, Minghao Li, Weishi Shi, Yan Huang, Yusheng Wei, Sourabh Yadav, Chenxi Qiu</p>
    <p><b>Summary:</b> Metric differential privacy (mDP) strengthens local differential privacy (LDP) by scaling noise to semantic distance, but many machine learning (ML) systems are consumed under joint observation, where model-agnostic, per-record guarantees can miss leakage from evidence aggregation. We introduce metric-normalized posterior leakage (mPL), an attacker-aligned, distance-calibrated measure of posterior-odds shift induced by releases, and show that for single or independent releases, uniformly bounding mPL is equivalent to mDP. Under joint observation, however, satisfying mDP may still leave mPL high because learned aggregators compound evidence across correlated items. To make control practical, we formalize probabilistically bounded mPL (PBmPL), which limits how often mPL may exceed a target budget, and we operationalize it via Adaptive mPL (AmPL), a trust-and-verify framework that perturbs, audits with a learned attacker, and adapts parameters (with optional Bayesian remapping) to balance privacy and utility. In a word-embedding case study, neural adversaries violate mPL under joint consumption despite per-record mDP perturbations, whereas AmPL substantially lowers the frequency of such violations with low utility loss, indicating PBmPL as a practical, certifiable protection for joint-consumption settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.01129v1">Revisiting Privacy Leakage in Machine Unlearning: Membership Inference Beyond the Forgotten Set</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-01T21:57:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jie Fu, Nima Naderloui, Da Zhong, Yuan Hong, Wendy Hui Wang</p>
    <p><b>Summary:</b> Machine unlearning (MU) has emerged as a key mechanism for ensuring data privacy and regulatory compliance by enabling models to forget specific training samples. However, recent studies have shown that the removal of data can inadvertently introduce privacy leakages to the retain set,i.e., data that remain in the model after unlearning. In this paper, we extend the scope of privacy analysis in unlearning to the often-overlooked retained data. We introduce TC-UMIA, the first tri-class unlearning membership inference attack. TC-UMIA is a population-level inference framework that leverages model predictions before and after unlearning to distinguish among the forget, retain, and unseen set. Extensive experiments on five state-of-the-art unlearning algorithms and six real-world datasets demonstrate that: (i) unlearning can introduce additional privacy risks to the retain set, making it more susceptible to membership inference attacks; (ii) TC-UMIA is effective across a wide range of model architectures, datasets, and MU approaches. Beyond launching the attack, we rigorously evaluate three defense mechanisms, namely label-only outputs, dropout, and differential privacy, to mitigate the privacy risks posed by TC- UMIA. Our results reveal a fundamental trade-off between privacy protection and model accuracy, with the dropout approach offering the most favorable balance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.00796v1">When RAG Chatbots Expose Their Backend: An Anonymized Case Study of Privacy and Security Risks in Patient-Facing Medical AI</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-05-01T17:29:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alfredo Madrid-García, Miguel Rujas</p>
    <p><b>Summary:</b> Background: Patient-facing medical chatbots based on retrieval-augmented generation (RAG) are increasingly promoted to deliver accessible, grounded health information. AI-assisted development lowers the barrier to building them, but they still demand rigorous security, privacy, and governance controls. Objective: To report an anonymized, non-destructive security assessment of a publicly accessible patient-facing medical RAG chatbot and identify governance lessons for safe deployment of generative AI in health. Methods: We used a two-stage strategy. First, Claude Opus 4.6 supported exploratory prompt-based testing and structured vulnerability hypotheses. Second, candidate findings were manually verified using Chrome Developer Tools, inspecting browser-visible network traffic, payloads, API schemas, configuration objects, and stored interaction data. Results: The LLM-assisted phase identified a critical vulnerability: sensitive system and RAG configuration appeared exposed through client-server communication rather than restricted server-side. Manual verification confirmed that ordinary browser inspection allowed collection of the system prompt, model and embedding configuration, retrieval parameters, backend endpoints, API schema, document and chunk metadata, knowledge-base content, and the 1,000 most recent patient-chatbot conversations. The deployment also contradicted its privacy assurances: full conversation records, including health-related queries, were retrievable without authentication. Conclusions: Serious privacy and security failures in patient-facing RAG chatbots can be identified with standard browser tools, without specialist skills or authentication; independent review should be a prerequisite for deployment. Commercial LLMs accelerated this assessment, including under a false developer persona; assistance available to auditors is equally available to adversaries.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.00562v1">Depth-Guided Privacy-Preserving Visual Localization Using 3D Sphere Clouds</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-05-01T10:59:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Heejoon Moon, Jongwoo Lee, Jeonggon Kim, Je Hyeong Hong</p>
    <p><b>Summary:</b> The emergence of deep neural networks capable of revealing high-fidelity scene details from sparse 3D point clouds has raised significant privacy concerns in visual localization involving private maps. Lifting map points to randomly oriented 3D lines is a well-known approach for obstructing undesired recovery of the scene images, but these lines are vulnerable to a density-based attack that can recover the point cloud geometry by observing the neighborhood statistics of lines. With the aim of nullifying this attack, we present a new privacy-preserving scene representation called \emph{sphere cloud}, which is constructed by lifting all points to 3D lines crossing the centroid of the map, resembling points on the unit sphere. Since lines are most dense at the map centroid, the sphere cloud mislead the density-based attack algorithm to incorrectly yield points at the centroid, effectively neutralizing the attack. Nevertheless, this advantage comes at the cost of i) a new type of attack that may directly recover images from this cloud representation and ii) unresolved translation scale for camera pose estimation. To address these issues, we introduce a simple yet effective cloud construction strategy to thwart new attack and propose an efficient localization framework to guide the translation scale by utilizing absolute depth maps acquired from on-device time-of-flight (ToF) sensors. Experimental results on public RGB-D datasets demonstrate sphere cloud achieves competitive privacy-preserving ability and localization runtime while not excessively compensating the pose estimation accuracy compared to other depth-guided localization methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.00535v1">From Pilot to Precoding Design: Blind Angular Spoofing For Location Privacy in MIMO Systems</a></h3>
  
  <p><b>Published on:</b> 2026-05-01T09:24:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Priyanka Maity, Lorenzo Italiano, Alireza Pourafzal, Gonzalo Seco-Granados, Hui Chen, Monica Nicoli, Henk Wymeersch</p>
    <p><b>Summary:</b> This paper studies location privacy in uplink MIMO systems, where a user equipment seeks to spoof the angular signature observed by a single base station performing localization. We propose a blind analog precoder design that manipulates the perceived angle-of-arrival and angle-of-departure configuration without requiring channel-gain knowledge. The method enforces consistency between the received signal and a desired spoofed angular subspace, and is solved using an alternating optimization algorithm under practical amplitude constraints. Simulations in a multipath scenario show that the proposed approach achieves near-perfect angular spoofing and clearly outperforms pilot-only blind spoofing, which exhibits an error floor. The results also show a trade-off between spoofing accuracy and communication rate, depending on the chosen virtual geometry.</p>
  </details>
</div>



<h2>2026-04</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.00283v1">A Privacy-Preserving Approach to Conformance Checking</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2026-04-30T22:47:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Luis Rodríguez-Flores, Luciano García-Bañuelos, Abel Armas-Cervantes, Astrid Rivera-Partida</p>
    <p><b>Summary:</b> Conformance checking, one of the main process mining operations, aims to identify discrepancies between a process model and an event log. The model represents the expected behaviour, whereas the event log represents the actual process behaviour as captured in information systems records. Traditionally, the process model and the event log are both accessible to the business analyst performing the conformance checking. However, in some contexts, it is necessary to keep either the model or the log private to protect critical or sensitive information. In this paper, we propose a secure approach to conformance checking based on string processing algorithms and homomorphic encryption, where the process model and event log ar not visible to either the model's or event log's owner. The proposed technique is based on alignments, a well-known formalism used for conformance checking. An evaluation is performed using a synthetic and a real-world event log, showing that conformance checking can be securely computed at the expense of high memory and processing requirements.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.00076v1">zkSBOM: Privacy-Preserving SBOM Sharing with Zero-Knowledge Sets</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2026-04-30T13:54:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tom Sorger, Eric Cornelissen, Aman Sharma, Javier Ron, Musard Balliu, Martin Monperrus</p>
    <p><b>Summary:</b> Software Bills of Materials (SBOMs) are increasingly mandated by regulators, yet existing sharing mechanisms impose a binary choice between full disclosure and full opacity. This exposes software suppliers to attacks that can be deduced from the SBOM only, such as the presence of a vulnerable dependency. Conversely, software consumers can be fooled by software suppliers who modify or misrepresent published SBOMs. We present zkSBOM, a privacy-preserving SBOM sharing mechanism designed to address these threats. zkSBOM uses zero-knowledge sets to cryptographically commit to the components within an SBOM. Software consumers can query for known vulnerabilities and receive a cryptographic proof confirming whether the artifact described by the SBOM is affected, without revealing any additional SBOM content. We conduct a security analysis of zkSBOM by quantifying expected leakage from inclusion and exclusion proofs. We demonstrate real-world feasibility by applying it to realistic scenarios and evaluating its operation requirements. Our evaluation demonstrates that zkSBOM is a strong, secure, and privacy-preserving mechanism for SBOM sharing, protecting software suppliers and software consumers from one another.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.27833v1">Taming Noise-Induced Prototype Degradation for Privacy-Preserving Personalized Federated Fine-Tuning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-04-30T13:20:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuhua Wang, Qinnan Zhang, Xiaodong Li, Huan Zhang, Yifan Sun, Wangjie Qiu, Hainan Zhang, Yongxin Tong, Zhiming Zheng</p>
    <p><b>Summary:</b> Prototype-based Personalized Federated Learning (ProtoPFL) enables efficient multi-domain adaptation by communicating compact class prototypes, but directly sharing them poses privacy risks. A common defense involves per-example $\ell_2$ clipping before prototype computation to bound sensitivity, followed by isotropic Gaussian noise to enforce Local Differential Privacy (LDP). However, Isotropic Gaussian Prototype Perturbation (IGPP) typically over-perturbs discriminative dimensions and struggles to balance the clipping threshold with representation fidelity. In this paper, we propose VPDR, a client-side privacy plug-in that seamlessly integrates into existing ProtoPFLs. Motivated by the observation that dimension-wise class variance reflects discriminability, we introduce Variance-adaptive Prototype Perturbation (VPP), which allocates less noise to discriminative subspaces, preserving semantic separability while ensuring privacy. We further develop Distillation-guided Clipping Regularization (DCR), which enables feature norms to adaptively concentrate near the predefined clipping threshold while maintaining prediction consistency. Theoretical analysis shows that our groupwise mechanism provides privacy guarantees no weaker than the isotropic baseline under the same privacy constraints. Extensive experiments on multi-domain benchmarks demonstrate that VPDR achieves a superior privacy-utility trade-off, outperforming IGPP in personalized federated fine-tuning without sacrificing robustness against realistic attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.27598v2">Privacy-Preserving Federated Learning via Differential Privacy and Homomorphic Encryption for Cardiovascular Disease Risk Modeling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-04-30T08:49:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gaurang Sharma, Juha Pajula, Aada Illikainen, Markus Rautell, Noora Lipsonen, Petri Alhainen, Mika Hilvo</p>
    <p><b>Summary:</b> Protecting sensitive health data while enabling collaborative analysis is a central challenge in healthcare. Traditional machine learning (ML) requires institutions to pool anonymized patient records, centralizing analytical development and privacy risks at a single site. Privacy-enhancing technologies (PETs), including Differential Privacy (DP) and Homomorphic Encryption (HE), can mitigate these risks. However, they are mainly studied in conventional data-sharing settings and often introduce trade-offs, including reduced model utility, higher computational cost, and increased implementation complexity. Federated Learning (FL) reduces data centralization by enabling institutions to train models locally and share only model updates. Nevertheless, FL does not eliminate privacy risks, as shared parameters or gradients may still reveal sensitive information. Integrating DP or HE into FL can strengthen privacy guarantees, yet their comparative performance and deployment implications in real-world healthcare settings remain unclear. We systematically evaluated DP and HE integration in FL under real-world conditions, comparing them with standard FL and centralized ML (cML) to quantify privacy-utility trade-offs in multi-institutional settings. Using nationwide Swedish healthcare data, we evaluated cardiovascular disease risk prediction using logistic regression (LR) and neural network (NN) learners. FL with HE achieved performance comparable to cML but introduced measurable cryptographic overhead, particularly in the NN implementation. FL with DP incurred lower computational cost; however, LR was more sensitive to calibrated noise than the NN, resulting in greater performance degradation. Our findings provide practical guidance for deploying privacy-preserving FL in fragmented healthcare systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.27550v1">APPSI-139: A Parallel Corpus of English Application Privacy Policy Summarization and Interpretation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-04-30T07:58:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pengyun Zhu, Qiheng Sun, Long Wen, Yanbo Wang, Yang Cao, Junxu Liu, Deyi Xiong, Jinfei Liu, Zhibo Wang, Kui Ren</p>
    <p><b>Summary:</b> Privacy policies are essential for users to understand how service providers handle their personal data. However, these documents are often long and complex, as well as filled with technobabble and legalese, causing users to unknowingly accept terms that may even contradict the law. While summarizing and interpreting these privacy policies is crucial, there is a lack of high-quality English parallel corpus optimized for legal clarity and readability. To address this issue, we introduce APPSI-139, a high-quality English privacy policy corpus meticulously annotated by domain experts, specifically designed for summarization and interpretation tasks. The corpus includes 139 English privacy policies, 15,692 rewritten parallel corpora, and 36,351 fine-grained annotation labels across 11 data practice categories. Concurrently, we propose TCSI-pp-V2, a hybrid privacy policy summarization and interpretation framework that employs an alternating training strategy and coordinates multiple expert modules to effectively balance computational efficiency and accuracy. Experimental results show that the hybrid summarization system built on APPSI-139 corpus and the TCSI-pp-V2 framework outperform large language models, such as GPT-4o and LLaMA-3-70B, in terms of readability and reliability. The source code and dataset are available at https://github.com/EnlightenedAI/APPSI-139.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.26838v1">Solving Positive Linear Programs with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2026-04-29T16:02:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alina Ene, Huy Le Nguyen, Ta Duy Nguyen, Adrian Vladu</p>
    <p><b>Summary:</b> We study differentially private approximation algorithms for positive linear programs (LPs with nonnegative coefficients and variables), focusing on the fundamental families of packing, covering, and mixed packing-covering formulations. We focus on the high-sensitivity, constraint-private regime of Hsu-Roth-Roughgarden-Ullman (ICALP 2014), where neighboring instances may differ by an arbitrary single constraint, so one cannot hope to approximately satisfy every constraint under privacy. We give private solvers that return approximate solutions while violating only a controlled number of constraints. Our algorithms improve the prior instance-dependent guarantees, and also yield new data-independent bounds that depend only on the dimension. Our techniques involve a dense multiplicative weights update method developed from a regularized dual viewpoint, which we analyze in a way that exploits structure specific to positive LPs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.27014v1">Fidelity, Diversity, and Privacy: A Multi-Dimensional LLM Evaluation for Clinical Data Augmentation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-29T11:32:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guillermo Iglesias, Gema Bello-Orgaz, María Navas-Loro, Cristian Ramirez-Atencia, Mercè Salvador Robert, Enrique Baca-Garcia</p>
    <p><b>Summary:</b> The scarcity of high-quality annotated medical data, particularly in mental health, poses a significant bottleneck for training robust machine learning models. Privacy regulations restrict data sharing, making synthetic data generation a promising alternative. The use of Large Language Models (LLMs) in a data augmentation pipeline could be leveraged as an alternative in this field. In the proposed methodology, DeepSeek-R1, OpenBioLLM-Llama3 and Qwen 3.5 are used to generate synthetic mental health evaluation reports conditioned on specific International Classification of Diseases, Tenth Revision (ICD-10) codes. Because naive text generation can lead to mode collapse or privacy breaches (memorization), a comprehensive evaluation framework is introduced. The generated diagnostic texts are assessed across three dimensions: semantic fidelity, lexical diversity, and privacy/plagiarism. The results demonstrate that all models can generate clinically coherent, diverse, and privacy-safe synthetic reports, significantly expanding the available training data for clinical natural language processing tasks without compromising patient confidentiality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.26525v2">PRAG: End-to-End Privacy-Preserving Retrieval-Augmented Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-29T10:46:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhijun Li, Minghui Xu, Huayi Qi, Wenxuan Yu, Tingchuang Zhang, Qiao Zhang, GuangYong Shang, Zhen Ma, Xiuzhen Cheng</p>
    <p><b>Summary:</b> Retrieval-Augmented Generation (RAG) is essential for enhancing Large Language Models (LLMs) with external knowledge, but its reliance on cloud environments exposes sensitive data to privacy risks. Existing privacy-preserving solutions often sacrifice retrieval quality due to noise injection or only provide partial encryption. We propose PRAG, an end-to-end privacy-preserving RAG system that achieves end-to-end confidentiality for both documents and queries without sacrificing the scalability of cloud-hosted RAG. PRAG features a dual-mode architecture: a non-interactive PRAG-I utilizes homomorphic-friendly approximations for low-latency retrieval, while an interactive PRAG-II leverages client assistance to match the accuracy of non-private RAG. To ensure robust semantic ordering, we introduce Operation-Error Estimation (OEE), a mechanism that stabilizes ranking against homomorphic noise. Experiments on large-scale datasets demonstrate that PRAG achieves competitive recall (72.45%-74.45%), practical retrieval latency, and strong resilience against graph reconstruction attacks while maintaining end-to-end confidentiality. This work confirms the feasibility of secure, high-performance RAG at scale.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.26390v1">Meta-Learning and Targeted Differential Privacy to Improve the Accuracy-Privacy Trade-off in Recommendations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-04-29T08:00:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Peter Müllner, Dominik Kowald, Markus Schedl, Elisabeth Lex</p>
    <p><b>Summary:</b> Balancing differential privacy (DP) with recommendation accuracy is a key challenge in privacy-preserving recommender systems, since DP-noise degrades accuracy. We address this trade-off at both the data and model levels. At the data level, we apply DP only to the most stereotypical user data likely to reveal sensitive attributes, such as gender or age, to reduce unnecessary perturbation; we refer to this as targeted DP. At the model level, we use meta-learning to improve robustness to remaining DP-noise. This achieves a better trade-off between accuracy and privacy than standard approaches: Meta-learning improves accuracy and targeted DP leads to lower empirical privacy risk compared to uniformly applied DP and full DP baselines. Overall, our findings show that selectively applying DP at the data level together with meta-learning at the model level can effectively balance recommendation accuracy and user privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.26184v1">Privacy-Preserving Clothing Classification using Vision Transformer for Thermal Comfort Estimation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-29T00:18:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tatsuya Chuman, Yousuke Udagawa, Hitoshi Kiya</p>
    <p><b>Summary:</b> A privacy-preserving clothing classification scheme is presented to enable secure occupant-centric control (OCC) systems. Although the utilization of camera images for HVAC control has been widely studied to optimize thermal comfort, privacy protection of occupant images has not been considered in prior works. While various privacy-preserving methods have been proposed for image classification, applying conventional schemes results in severe accuracy degradation. In this paper, we introduce a privacy-preserving classification method using Vision Transformer (ViT) applied to clothing insulation estimation. In an experiment using the DeepFashion dataset categorized by clothing insulation, while the conventional pixel-based method suffers a severe accuracy drop, our scheme maintains a high accuracy on encrypted images, showing no degradation from plain images across all categories.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.26073v1">Privacy-Preserving Federated Learning Framework for Distributed Chemical Process Optimization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> 
  <p><b>Published on:</b> 2026-04-28T19:26:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Teetat Pipattaratonchai, Aueaphum Aueawatthanaphisut</p>
    <p><b>Summary:</b> Industrial chemical plants often operate under strict data confidentiality constraints, making centralized data-driven process modeling difficult. Federated learning (FL) provides a promising solution by enabling collaborative model training across distributed facilities without sharing raw operational data. This paper proposes a privacy-preserving federated learning framework for distributed chemical process optimization using data collected from multiple geographically separated plants. Each plant locally trains a neural-network-based process model using its own time-series sensor data, while only model parameters are transmitted to a central aggregation server through secure aggregation mechanisms. This design allows cross-plant knowledge sharing while maintaining strict data locality and industrial confidentiality. Experimental evaluation was conducted using process datasets from three independent chemical plants operating under heterogeneous conditions. The results demonstrate rapid convergence of the federated model, with the global mean squared error decreasing from approximately 2369 to below 50 within the first five communication rounds and stabilizing around 35 after 40 rounds. In comparison with local-only training, the proposed federated framework significantly improves prediction accuracy across all plants, while achieving performance comparable to centralized training. The findings indicate that federated learning provides an effective and scalable solution for collaborative industrial analytics, enabling privacy-preserving predictive modeling and process optimization across distributed chemical production facilities.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.00036v1">Cross-level Privacy Preserving Utility Mining</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2026-04-28T06:41:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiahong Cai, Wensheng Gan, Philip S. Yu</p>
    <p><b>Summary:</b> Privacy-preserving utility mining (PPUM) aims to hide sensitive high-utility patterns while preserving the utility of the sanitized database. In practice, however, many datasets are associated with taxonomic information, which makes the identification and processing of generalized items more challenging. To address this, we investigate the cross-level privacy-preserving utility mining (CLPPUM) problem and propose a method for protecting generalized items. Based on different victim item selection strategies, we develop three CLPPUM algorithms: minimum RGISU first (Min-RF), maximum RGISU first (Max-RF), and best NSC first (Best-NSCF). Furthermore, to enable efficient victim item identification, a novel dictionary structure named GI-dic is designed to accelerate the computation of required utility metrics. Experimental results on multiple datasets demonstrate that the proposed algorithms successfully hide all sensitive cross-level high-utility itemsets without introducing artificial itemsets. The results also show that our method performs well on sparse datasets, and both Min-RF and Best-NSCF consistently outperform Max-RF. Overall, Min-RF achieves the best performance, particularly when the minimum utility threshold is low and the dataset is dense.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.24982v1">"We Wanted to Do Better Than the Law": Exploring UI/UX Designers' Privacy Advocacy in Practice</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-04-27T20:37:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Keyu Yao, Jinghui Cheng, Jin L. C. Guo</p>
    <p><b>Summary:</b> Designers hold primary responsibility for shaping the user interface (UI) and user experience (UX) of a product. This role goes beyond aesthetics and usability, extending to the privacy outcomes of user experience, which often emerge through collaboration with other stakeholders such as developers, product managers, and marketing teams. Previous studies on enhancing privacy for technological products primarily focused on the roles of developers -- understanding their needs and challenges -- but limited effort is devoted to examining how UI/UX designers consider and approach privacy in their work. Through 12 semi-structured interviews with privacy-advocating UI/UX designers, we explore the perceptions, influencing factors, challenges, and adaptive methods they use regarding privacy implementation. We pay special attention to how these challenges and adaptations play out in team-based settings where decisions are negotiated together. Our study reveals how personal and contextual factors shape designers' value of privacy, the collaborative nature of the challenges designers face when trying to prioritize privacy, and how they navigate tensions between business goals, team dynamics, and technical development. Based on our findings, we discuss implications for advocating a user-centered approach for supporting privacy-aware design, suggestions for organizational-level changes and bridging knowledge gaps through designer-centric tools and community building.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.24724v2">Data-Driven Privacy-Preserving Modeling and Frequency Regulation with Aggregated Electric Vehicles via Bilinear Hidden Markov Model</a></h3>
  
  <p><b>Published on:</b> 2026-04-27T17:34:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yiping Liu, Xiaozhe Wang, Geza Joos</p>
    <p><b>Summary:</b> Vehicle-to-Grid (V2G) technology allows bidirectional power flow for real-time grid support, making electric vehicles (EVs) well-suited for ancillary services such as frequency regulation. However, existing methods for flexibility estimation and coordinating aggregated EVs often rely on individual EV traveling information (e.g., arrival/departure time) and/or characteristic parameters (e.g., charging efficiency, battery capacity) as well as real-time state-of-charge (SOC), which raises privacy concerns and faces data quality issues. To address these challenges, this paper proposes a data-driven, privacy-preserving modeling and control framework for frequency regulation using aggregated EVs. The proposed method can provide accurate estimation for power outputs and flexibility of aggregated EVs and carry out effective frequency regulation without any individual EV information. Simulation results validate the accuracy and effectiveness of the proposed method, which also outperforms the model-based and federated learning-based method under SOC data inaccuracies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.24468v1">A Survey on Split Learning for LLM Fine-Tuning: Models, Systems, and Privacy Optimizations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-04-27T13:36:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zihan Liu, Yizhen Wang, Rui Wang, Xiu Tang, Sai Wu</p>
    <p><b>Summary:</b> Fine-tuning unlocks large language models (LLMs) for specialized applications, but its high computational cost often puts it out of reach for resource-constrained organizations. While cloud platforms could provide the needed resources, data privacy concerns make sharing sensitive information with third parties risky. A promising solution is split learning for LLM fine-tuning, which divides the model between clients and a server, allowing collaborative and secure training through exchanged intermediate data, thus enabling resource-constrained participants to adapt LLMs safely. % In light of this, a growing body of literature has emerged to advance this paradigm, introducing varied model methods, system optimizations, and privacy defense-attack techniques for split learning. To bring clarity and direction to the field, a comprehensive survey is needed to classify, compare, and critique these diverse approaches. This paper fills the gap by presenting the first extensive survey dedicated to split learning for LLM fine-tuning. We propose a unified, fine-grained training pipeline to pinpoint key operational components and conduct a systematic review of state-of-the-art work across three core dimensions: model-level optimization, system-level efficiency, and privacy preservation. Through this structured taxonomy, we establish a foundation for advancing scalable, robust, and secure collaborative LLM adaptation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.24326v1">X-NegoBox: An Explainable Privacy-Budget Negotiation Framework for Secure Peer-to-Peer Energy Data Exchange</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-04-27T11:18:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Poushali Sengupta, Sabita Maharjan, Frank Eliassen, Yan Zhang</p>
    <p><b>Summary:</b> The decentralization of modern energy systems is transforming consumers into prosumers who continuously exchange data with aggregators, peers, and market operators. While such data is essential for peer-to-peer trading, demand response, and distributed forecasting, it can reveal sensitive household patterns and introduce privacy risks. Existing data sharing mechanisms rely on fixed policies or predefined differential privacy budgets, limiting their ability to adapt to variations in reliability, data sensitivity, and request purpose. As a result, prosumers rarely receive explanations for why a request is accepted, rejected, or modified, reducing trust and participation.
  To address these limitations, we propose X-NegoBox, an explainable negotiation framework for adaptive privacy budgeting and transparent decision making. Each prosumer data is managed locally within a private DataBox, where raw data remain confined. Incoming requests are processed by an Autonomous Privacy Budget Negotiation Protocol (APBNP), which determines an appropriate privacy budget based on trust, feature sensitivity, declared purpose, historical behavior, and risk-aware pricing. When needed, APBNP generates privacy-preserving counter-offers, such as reduced resolution or duration.
  An Explainable Agreement Layer (X-Contract) produces human- and machine-readable justifications for each decision. After agreement, requester code executes locally in a sandbox, and only sanitized outputs are shared. Experiments on realistic energy market settings show reduced privacy leakage, higher acceptance rates, and improved interpretability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.24203v1">Agentic Witnessing: Pragmatic and Scalable TEE-Enabled Privacy-Preserving Auditing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2026-04-27T09:07:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Antony Rowstron</p>
    <p><b>Summary:</b> Auditing the semantic properties of proprietary data creates a fundamental tension: verification requires transparent access, while proprietary rights demand confidentiality. While Zero-Knowledge Proofs (ZKPs) ensure privacy, they are typically limited to precise algebraic constraints and are ill-suited for verifying qualitative, unstructured properties, such as the logic within a codebase. We propose {\em Agentic Witnessing}, a framework that moves verification from attested execution to {\em attested reasoning}. The system is composed of three agents: a Verifier (who wants to check properties of a dataset), a Prover (who owns the dataset) and an Auditor (that inspects the dataset). The Verifier is allowed to ask a limited number of simple binary true/false questions to the auditor. By isolating an LLM-based Auditor within a Trusted Execution Environment (TEE), the system enables the Verifier to query a Prover's private data via simple Boolean queries, without exposing the raw dataset. The Auditor uses the Model Context Protocol (MCP) to dynamically inspect the target dataset, producing a yes/no verdict accompanied by a cryptographic transcript: a signed hash chain binding the reasoning trace to both the original dataset and the TEE's hardware root of trust. We demonstrate this architecture by automating the artifact evaluation process for 21 peer-reviewed computer science papers with released codebases on GitHub (e.g. Does the codebase implement the system described in the paper?). We verified five high-level properties of these codebases described in the corresponding publications, treating the source code as private. Our results show that TEE-enabled agentic auditing provides a mechanism for privacy-preserving oversight, effectively decoupling qualitative verification from the need for data disclosure.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.24066v1">Listen to the Voices of Everyday Users: Democratizing Privacy Ratings for Sensitive Data Access in Mobile Apps</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-04-27T05:47:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Liu Wang, Tianshu Zhou, Haoyu Wang, Yi Wang</p>
    <p><b>Summary:</b> Mobile apps frequently request excessive data access, raising significant privacy concerns. While regulations like GDPR emphasize data minimization, they provide limited guidance on concretely defining and enforcing necessary data access. Existing regulatory mechanisms primarily rely on expert-driven audits that face challenges in scalability, neutrality, and alignment with user expectations. In this paper, we propose a novel paradigm--democratizing privacy assessment, inspired by prior work on user-centric privacy perceptions--which repositions users as active evaluators in the privacy auditing process, recognizing that user perceptions of data usage play a crucial role in assessing the appropriateness and necessity of data access. To operationalize this paradigm, we introduce DePRa, a prototype system developed through participatory design, featuring contextual explanation provision, category-based representative selection, an intuitive rating interface, and preference-based rating adjustment. We evaluated DePRa with 200 everyday mobile app users, analyzing how effectively it captures user opinions on sensitive data access, comparing their privacy ratings with expert assessments, and exploring risk preference-based score calibration. Our findings show the feasibility and promise of democratized privacy assessment, highlighting its potential to complement expert auditing and support inclusive privacy evaluation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.23847v1">Privacy-preserving Meta-analysis through Low-Rank Basis Hunting</a></h3>
  
  <p><b>Published on:</b> 2026-04-26T19:32:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenqi Shi, Kosuke Imai, Yi Zhang</p>
    <p><b>Summary:</b> A central challenge of meta-analysis is that the populations underlying existing studies often differ from the target population in unknown ways. We study the problem of predicting function-valued quantities, such as regression and conditional average treatment effect functions, for a new target population using only study-level covariates and estimates. We propose MetaHunt, a new meta-analysis methodology based on a shared low-rank structure, in which the true function from each study lies within the convex hull of a small set of latent basis functions. To recover these basis functions, we extend the Successive Projection Algorithm to the functional setting, incorporating a denoised basis-hunting step. We establish consistency of the recovered basis functions under mild regularity conditions. We then model the relationship between study-level covariates and the corresponding mixing weights using flexible semi-parametric or non-parametric methods. MetaHunt is privacy-preserving and enables meta-analytic prediction based on study-level information alone, even when individual-level data are unavailable to analysts. In addition, for each study, functions of interest can be estimated using possibly different machine learning algorithms. For uncertainty quantification, we construct prediction intervals via conformal prediction. We show that, under exchangeability and mild estimation-error conditions, these intervals achieve asymptotically valid marginal coverage. We demonstrate the effectiveness of MetaHunt through both simulation studies and empirical applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.23795v1">LLM-CEG: Extending the Classification Error Gauge Framework for Privacy Auditing of Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-26T16:39:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kato Mivule</p>
    <p><b>Summary:</b> This paper extends the Classification Error Gauge (x-CEG) framework, originally developed for measuring the privacy-utility trade-off in tabular datasets, to privacy auditing of Large Language Models (LLMs). We propose LLM-CEG, a systematic framework that employs membership inference attack (MIA) success rates as an empirical privacy gauge and model perplexity as a utility gauge, iteratively adjusting differential privacy parameters until both thresholds are jointly satisfied. A proof-of-concept prototype fine-tunes DistilGPT-2 on a synthetic clinical PII dataset under four privacy regimes using DP-SGD. Results indicate that DP-SGD reduces MIA attacker advantage by 71.5% while simultaneously improving out-of-distribution utility by 47-50% relative to the overfitted baseline, suggesting that differential privacy may act as implicit regularization under narrow fine-tuning conditions. We further extend the SIED engineering framework to the LLM context as LLM-SIED, providing an auditable, regulator-aligned process for privacy-compliant LLM deployment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.23711v1">Spore: Efficient and Training-Free Privacy Extraction Attack on LLMs via Inference-Time Hybrid Probing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-26T13:54:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yu Cui, Ruiqing Yue, Hang Fu, Sicheng Pan, Zhuoyu Sun, Baohan Huang, Haibin Zhang, Cong Zuo, Licheng Wang</p>
    <p><b>Summary:</b> With the wide adoption of personal AI assistants such as OpenClaw, privacy leakage in user interaction contexts with large language model (LLM) agents has become a critical issue. Existing privacy attacks against LLMs primarily target training data, while research on inference-time contextual privacy risks in LLM agent memory remains limited. Moreover, prior methods often incur high attack costs, requiring multiple queries or relying on white-box assumptions, which limits their practicality in real-world deployments. To address these issues, we propose a training-free privacy extraction attack targeting LLM agent memory, which we name \textsc{Spore}. \textsc{Spore} is compatible with both black-box and gray-box settings. In the black-box setting, \textsc{Spore} can efficiently extract a small candidate set via a single query to recover the original private information. In the gray-box setting, \textsc{Spore} allows the attacker to leverage multi-ranked tokens for more accurate and faster privacy extraction. We provide an information-theoretic analysis of \textsc{Spore} and show that it achieves high query efficiency with substantial per query information leakage. Experiments on multiple frontier LLMs show that \textsc{Spore} outperforms attack success rate over existing state-of-the-art (SOTA) schemes. It also maintains low attack cost and remains stable across different model parameter settings. We further evaluate the robustness of \textsc{Spore} against existing defense mechanisms. Our results show that \textsc{Spore} consistently bypasses both detection and strong safety alignment, demonstrating resilient performance in diverse defensive settings and real-world safety threats.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.23688v1">Do Protective Perturbations Really Protect Portrait Privacy under Real-world Image Transformations?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-04-26T13:04:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruiqing Sun, Xingshan Yao, Zhijing Wu, Tian Lan, Chenhao Cui, Huiyang Zhao, Jialing Shi, Chen Yang, Xianling Mao</p>
    <p><b>Summary:</b> Proactive defense methods protect portrait images from unauthorized editing or talking face generation (TFG) by introducing pixel-level protective perturbations, and have already attracted increasing attention for privacy protection. In real-world scenarios, images inevitably undergo various transformations during cross-device display and dissemination--such as scale transformations and color compression--that directly alter pixel values. However, it remains unclear whether such pixel-level modifications affect the effectiveness of existing proactive defense methods that rely on pixel-level perturbations. To solve this problem, we conduct a systematic evaluation of representative proactive defenses under image transformation. The evaluated methods are selected to span different generation architectures such as diffusion and GAN-based models, as well as defense scopes covering both portrait and natural images, and are assessed using both qualitative and quantitative metrics for subjective and objective comparison. Experimental results indicate that defense methods based on pixel-level perturbations struggle to withstand common image transformations, posing a risk of defense failure in real-world applications. To further highlight this risk, we propose a simple yet effective purification framework by leveraging the vulnerabilities induced by real-world image transformations. Experimental results demonstrate that the proposed method can efficiently remove protective perturbations with low computational cost, highlighting previously overlooked risks to the research community.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.23649v1">Rényi Pufferfish Privacy with Gaussian-based Priors: From Single Gaussian to Mixture Model</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-26T10:37:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenjin Yang, Ni Ding, Zijian Zhang, Zhen Li, Jing Sun, Jincheng An, Yong Liu, Liehuang Zhu</p>
    <p><b>Summary:</b> Rényi Pufferfish Privacy (RPP) provides a Rényi divergence-based privacy framework for correlated data, but existing $\infty$-Wasserstein mechanisms are often conservative and sacrifice data utility. We study Gaussian mechanisms for RPP under Gaussian and Gaussian-mixture priors. For single Gaussian priors, we derive the exact Rényi divergence after Gaussian perturbation, obtain a relaxed closed-form sufficient condition for $(α,ε)$-RPP, and characterize the monotonicity of the calibrated noise with respect to the privacy budget $ε$ and the Rényi order $α$. To handle more general non-Gaussian and multimodal priors, we approximate secret-conditioned outputs with Gaussian mixture models and introduce an optimal-transport-based sufficient condition for RPP. Experiments on three UCI datasets with statistical (\textsc{RAW}, \textsc{MEAN}) and model-output (\textsc{BNN}, \textsc{GP}) queries show that our prior-aware mechanisms consistently require less noise than a recent RPP additive-noise baseline, achieving an average noise reduction of 48.9\%. These results show that our mechanisms can substantially improve the privacy-utility trade-off under RPP.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.23563v1">CyberCane: Neuro-Symbolic RAG for Privacy-Preserving Phishing Detection with Formal Ontology Reasoning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2026-04-26T07:08:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Safayat Bin Hakim, Aniqa Afzal, Qi Zhao, Vigna Majmundar, Pawel Sloboda, Houbing Herbert Song</p>
    <p><b>Summary:</b> Privacy-critical domains require phishing detection systems that satisfy contradictory constraints: near-zero false positives to prevent workflow disruption, transparent explanations for non-expert staff, strict regulatory compliance prohibiting sensitive data exposure to external APIs, and robustness against AI-generated attacks. Existing rule-based systems are brittle to novel campaigns, while LLM-based detectors violate privacy regulations through unredacted data transmission. We introduce CyberCane, a neuro-symbolic framework integrating deterministic symbolic analysis with privacy-preserving retrieval-augmented generation (RAG). Our dual-phase pipeline applies lightweight symbolic rules to email metadata, then escalates borderline cases to semantic classification via RAG with automated sensitive data redaction and retrieval from a phishing-only corpus. We further introduce PhishOnt, an OWL ontology enabling verifiable attack classification through formal reasoning chains. Evaluation on DataPhish2025 (12.3k emails; mixed human/LLM) and Nazario/SpamAssassin demonstrates a 78.6-point recall gain over symbolic-only detection on AI-generated threats, with precision exceeding 98% and FPR as low as 0.16%. Healthcare deployment projects a 542x ROI; tunable operating points support diverse risk tolerances, with open-source implementation at https://github.com/sbhakim/Cybercane.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.23426v1">Enhanced Privacy and Communication Efficiency in Non-IID Federated Learning with Adaptive Quantization and Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-04-25T19:43:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Emre Ardıç, Yakup Genç</p>
    <p><b>Summary:</b> Federated learning (FL) is a distributed machine learning method where multiple devices collaboratively train a model under the management of a central server without sharing underlying data. One of the key challenges of FL is the communication bottleneck caused by variations in connection speed and bandwidth across devices. Therefore, it is essential to reduce the size of transmitted data during training. Additionally, there is a potential risk of exposing sensitive information through the model or gradient analysis during training. To address both privacy and communication efficiency, we combine differential privacy (DP) and adaptive quantization methods. We use Laplacian-based DP to preserve privacy, which is relatively underexplored in FL and offers tighter privacy guarantees than Gaussian-based DP. We propose a simple and efficient global bit-length scheduler using round-based cosine annealing, along with a client-based scheduler that dynamically adapts based on client contribution estimated through dataset entropy analysis. We evaluate our approach through extensive experiments on CIFAR10, MNIST, and medical imaging datasets, using non-IID data distributions across varying client counts, bit-length schedulers, and privacy budgets. The results show that our adaptive quantization methods reduce total communicated data by up to 52.64% for MNIST, 45.06% for CIFAR10, and 31% to 37% for medical imaging datasets compared to 32-bit float training while maintaining competitive model accuracy and ensuring robust privacy through differential privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.23248v1">PrivacyAssist: A User-Centric Agent Framework for Detecting Privacy Inconsistencies in Android Apps</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-04-25T10:58:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tran Thanh Lam Nguyen, Edoardo Di Tullio, Barbara Carminati, Elena Ferrari</p>
    <p><b>Summary:</b> Mobile apps offer significant benefits, but their privacy protections often remain ineffective and confusing for users. While prior work mainly analyzes app privacy vulnerabilities, few approaches help users understand, set, and enforce their privacy preferences. This paper presents PrivacyAssist, a multi-agent LLM-based platform that detects inconsistencies between user-granted permissions and developers' declared sensitive data collection and sharing practices. Using Retrieval-Augmented Generation (RAG), PrivacyAssist provides concise explanations and real-time on-device warnings to support informed installation decisions. We evaluate PrivacyAssist with 200 users and 2,347 Android apps, finding that only 16% of apps are fully consistent between granted permissions and declared data practices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.23245v1">Training Machine Learning Models on Encrypted Data: A Privacy-Preserving Framework using Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-04-25T10:50:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alexandre Marques, Beatriz Sá, Rui Botelho, Pedro Pinto</p>
    <p><b>Summary:</b> The use of Machine Learning (ML) for data-driven decision-making often relies on access to sensitive datasets, which introduces privacy challenges. Traditional encryption methods protect data at rest or in transit but fail to secure it during processing, exposing it to unauthorized access. Homomorphic encryption emerges as a transformative solution, enabling computations on encrypted data without decryption, thus preserving confidentiality throughout the ML pipeline. This paper addresses the challenge of training ML models on encrypted data while maintaining accuracy and efficiency by proposing a proof-of-concept for a privacy-preserving framework that leverages Cheon-Kim-Kim-Song (CKKS) for approximate real-number arithmetic. Also, it demonstrates the feasibility of training K-Nearest Neighbors (KNN) and linear regression models on encrypted data, and evaluates encrypted inference for a basic Multilayer Perceptron (MLP) architecture. Experimental results show that models trained under Homomorphic encryption achieve performance metrics comparable to plaintext-trained models, validating the approach. However, challenges such as computational overhead, noise management, and limited support for non-polynomial operations persist. This work lays the groundwork for broader adoption of privacy-preserving ML in real-world applications, balancing security with computational feasibility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.22310v1">Revisiting Geometric Obfuscation with Dual Convergent Lines for Privacy-Preserving Image Queries in Visual Localization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-04-24T07:44:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jeonggon Kim, Heejoon Moon, Je Hyeong Hong</p>
    <p><b>Summary:</b> Privacy-Preserving Image Queries (PPIQ) are an emerging mechanism for cloud-based visual localization, enabling pose estimation from obfuscated features instead of private images or raw keypoints. However, the main approaches for PPIQ, primarily geometry-based and segmentation-based obfuscation, both suffer from vulnerabilities to recent privacy attacks. In particular, a fundamental limitation of geometry-based obfuscation is that the spatial distribution of obfuscated neighboring lines still effectively surrounds the original keypoint location, providing exploitable cues for recovering the original points. We revisit this geometric paradigm and introduce Dual Convergent Lines (DCL), a novel keypoint obfuscation method demonstrating strong resilience against such attack. DCL places two fixed anchors on a central partition line and lifts each keypoint to a line originating from one of them, with the active anchor determined by the keypoint's location. This arrangement invalidates the geometry-recovery attack by making its optimization ill-posed: Neighboring lines either misleadingly converge to one anchor, yielding a trivial solution, or become near-parallel at the partition boundary, yielding an unstable high-variance solution. Both outcomes thwart point recovery. DCL is also compatible with an existing line-based solver, enabling deployment in traditional localization pipelines. Experiments on both indoor and large-scale outdoor datasets demonstrate DCL's robustness against privacy attacks, efficiency, and scalability, while achieving practical localization performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.22157v1">PrivSTRUCT: Untangling Data Purpose Compliance of Privacy Policies in Google Play Store</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-04-24T02:12:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bhanuka Silva, Anirban Mahanti, Aruna Seneviratne, Suranga Senevirante</p>
    <p><b>Summary:</b> Existing research typically treats privacy policies as flat, uniform text, extracting information without regard for the document's logical hierarchy. Disregard for structural cues of section headings designed to guide the reader, often leads automated methods to entangle distinct data practices, particularly when linking sensitive data items to their specific purposes. To address this, we introduce PrivSTRUCT, a novel and systematic encoder and decoder combined framework that to untangle complex privacy disclosures. Benchmarking against the state-of-the-art tool PoliGrapher reveals that PrivSTRUCT robustly extracts more than x2 the number of data item and purpose excerpts while retaining developer-defined structural cues. By applying PrivSTRUCT to a large-scale dataset of 3,756 Android apps, we uncover a critical transparency gap: the probability of developers overstating a data purpose is 20.4% higher for first-party collection and 9.7% higher for third-party sharing when they rely on globally defined purposes rather than specific, locally scoped disclosures. Alarmingly, we find that sensitive third-party data flows such as sharing financial data for analytics are frequently diluted and entangled into generic or unrelated categories, highlighting a persistent failure in the current purpose disclosure landscape.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.22100v1">Implementation and Privacy Guarantees for Scalable Keyword Search on SOLID-based Decentralized Data with Granular Visibility Constraints</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2026-04-23T22:16:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohamed Ragab, Faria Ferooz, Mohammad Bahrani, Helen Oliver, Thanassis Tiropanis, Alexandra Poulovassilis, Adriane Chapman, George Roussos</p>
    <p><b>Summary:</b> In decentralized personal data ecosystems grounded in architectures such as Solid, users retain sovereignty over their data via personal online data stores (pods), hosted on Solid-compliant server infrastructures. In such environments, data remains under the control of pod owners, which complicates search due to distribution across numerous pods and user-specific access constraints. ESPRESSO is a decentralized framework for scalable keyword-based search across distributed Solid pods under user-defined visibility policies. It addresses key challenges of decentralized search by constructing WebID-scoped indexes within pods and employing privacy-aware metadata to enable efficient source selection and ranking across servers. This paper further introduces a formal threat model for ESPRESSO, analysing the security and privacy risks associated with the generation, aggregation, and use of indexes and metadata. These risks include unintended metadata leakage and the potential for adversaries to infer sensitive information about data that resides within personal data stores. The analysis identifies key design principles that limit metadata exposure while mitigating unauthorized inference. The proposed threat model provides a foundation for evaluating privacy-preserving decentralized search and informs the design of systems with stronger privacy guarantees.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.22076v1">PrivUn: Unveiling Latent Ripple Effects and Shallow Forgetting in Privacy Unlearning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-04-23T21:01:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaoyi Chen, Haoyuan Wang, Siyuan Tang, Sijia Liu, Liya Su, XiaoFeng Wang, Haixu Tang</p>
    <p><b>Summary:</b> Large language models (LLMs) often memorize private information during training, raising serious privacy concerns. While machine unlearning has emerged as a promising solution, its true effectiveness against privacy attacks remains unclear. To address this, we propose PrivUn, a new evaluation framework that systematically assesses unlearning robustness through three-tier attack scenarios: direct retrieval, in-context learning recovery, and fine-tuning restoration; combined with quantitative analysis using forgetting scores, association metrics, and forgetting depth assessment. Our study exposes significant weaknesses in current unlearning methods, revealing two key findings: 1) unlearning exhibits gradient-driven ripple effects: unlike traditional forgetting which follows semantic relations (e.g., knowledge graphs), privacy unlearning propagates across latent gradient-based associations; and 2) most methods suffer from shallow forgetting, failing to remove private information distributed across multiple deep model layers. To validate these insights, we explore two strategies: association-aware core-set selection that leverages gradient similarity, and multi-layer deep intervention through representational constraints. These strategies represent a paradigm shift from shallow forgetting to deep forgetting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.22025v1">Taste for Privacy: How Context, Identity, and Lived-Experience Shape Information Sharing Preferences</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-04-23T19:38:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Juniper Lovato, Laurent Hébert-Dufresne, Mohsen Ghasemizade, Jonathan St-Onge, Peter S. Dodds, Laura Bloomfield, Mikaela Irene Fudolig, Matthew Price, Christopher Danforth</p>
    <p><b>Summary:</b> Privacy preferences are not fixed individual traits, they depend on context and lived experiences. In this study, we analyze 2,912 survey responses from 782 college students collected over seven survey periods during 2023 and 2024. We ask about their usage of social media, the security settings of their accounts, and measure their comfort in sharing personally identifiable information (PII) across 17 different institutional contexts. Compared to past research, we observe a large shift towards private accounts, going from 1/3rd private in 2007 to 2/3rds in 2024, and find that participants' discomfort sharing PII with social media platforms strongly predicts their privacy settings. Beyond social media, we identify a stable ranking of institutional trust, though some institutions, like the police, show high variability reflecting divergent lived experiences. Traditionally marginalized groups and participants having faced adverse childhood experiences show more discomfort with institutions of power, especially in areas where they face greater vulnerability. We argue for context-adaptive privacy settings that recognize institutional relationships and demographic vulnerabilities, moving beyond one-size-fits-all consent frameworks toward contextually appropriate data governance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.21571v1">Separable Expert Architecture: Toward Privacy-Preserving LLM Personalization via Composable Adapters and Deletable User Proxies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-04-23T11:51:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chris Schneider, Philipp Schoenegger, Ben Bariach</p>
    <p><b>Summary:</b> Current model training approaches incorporate user information directly into shared weights, making individual data removal computationally infeasible without retraining. This paper presents a three-layer architecture that decouples personal data from shared weights by combining a static base model, composable domain-expert LoRA adapters that shape behavior without imparting user data, and per-user proxy artefacts whose deletion constitutes deterministic unlearning. Evaluation on Phi-3.5-mini and Llama-3.1-8B confirms per-user differentiation in which personal data influences outputs while remaining isolated, verified by a return to baseline after proxy removal (KL divergence of approximately 0.21 nats, 82-89% verification pass rate) and near-zero cross-user contamination. Because user-specific information never enters shared weights, the architecture mitigates model inversion, membership inference, and training-data extraction against shared model components by construction. The approach converts machine unlearning from an intractable weight-editing problem into a deterministic deletion operation that preserves personalization alongside privacy-enhancing guarantees and is compatible with differentially private stochastic gradient descent (DP-SGD) for privacy-preserving shared model improvement.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.21491v1">Benchmarking the Utility of Privacy-Preserving Cox Regression Under Data-Driven Clipping Bounds: A Multi-Dataset Simulation Study</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">  
  <p><b>Published on:</b> 2026-04-23T09:53:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Keita Fukuyama, Yukiko Mori, Tomohiro Kuroda, Hiroaki Kikuchi</p>
    <p><b>Summary:</b> Differential privacy (DP) is a mathematical framework that guarantees individual privacy; however, systematic evaluation of its impact on statistical utility in survival analyses remains limited. In this study, we systematically evaluated the impact of DP mechanisms (Laplace mechanism and Randomized Response) with data-driven clipping bounds on the Cox proportional hazards model, using 5 clinical datasets ($n = 168$--$6{,}524$), 15 levels of $\varepsilon$ (0.1--1000), and $B = 1{,}000$ Monte Carlo iterations. The data-driven clipping bounds used here are observed min/max and therefore do not provide formal $\varepsilon$-DP guarantees; the results represent an optimistic lower bound on utility degradation under formal DP. We compared three types of input perturbations (covariates only, all inputs, and the discrete-time model) with output perturbations (dfbeta-based sensitivity), using loss of significance rate (LSR), C-index, and coefficient bias as metrics. At standard DP levels ($\varepsilon \leq 1$), approximately 90% (90--94%) of the significant covariates lost significance, even in the largest dataset ($n = 6{,}524$), and the predictive performance approached random levels (test C-index $\approx 0.5$) under many conditions. Among the input perturbation approaches, perturbing only covariates preserved the risk-set structure and achieved the best recovery, whereas output perturbation (dfbeta-based sensitivity) maintained near-baseline performance at $\varepsilon \geq 5$. At $n \approx 3{,}000$, the significance recovered rapidly at $\varepsilon = 3$--10; however, in practice, $\varepsilon \geq 10$ (for predictive performance) to $\varepsilon \geq 30$--60 (for significance preservation) is required. In the moderate-to-high $\varepsilon$ range, false-positive rates increased for variables whose baseline $p$-values were near the significance threshold.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.21455v1">The Privacy Guardian Agent: Towards Trustworthy AI Privacy Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-04-23T09:13:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vincent Freiberger</p>
    <p><b>Summary:</b> The current "notice and consent" paradigm is broken: consent dialogues are often manipulative, and users cannot realistically read or understand every privacy policy. While recent LLM-based tools empower users seeking active control, many with limited time or motivation prefer full automation. However, fully autonomous solutions risk hallucinations and opaque decisions, undermining trust. I propose a middle ground - a Privacy Guardian Agent that automates routine consent choices using user profiles and contextual awareness while recognizing uncertainty. It escalates unclear or high-risk cases to the user, maintaining a human-in-the-loop only when necessary. To ensure agency and transparency, the agent's reasoning on its autonomous decisions is reviewable, allowing for user recourse. For problematic cases, even with minimal consent, it alerts the user and suggests switching to an alternative site. This approach aims to reduce consent fatigue while preserving trust and meaningful user autonomy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.21381v1">Privacy-Preserving Distributed Stochastic Optimization with Homomorphic Encryption and Heterogeneous Stepsizes</a></h3>
  
  <p><b>Published on:</b> 2026-04-23T07:51:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haoqiang Zhou, Chi Chen, Yongfeng Zhi, Huan Gao</p>
    <p><b>Summary:</b> Distributed stochastic optimization enables multi-agent collaboration in applications such as distributed learning and sensor networks, but also raises critical privacy concerns due to the involvement of sensitive data. While existing privacy-preserving approaches often face limitations in balancing accuracy with efficiency, we propose a novel distributed stochastic gradient descent algorithm that integrates Paillier homomorphic encryption with heterogeneous and time-varying random stepsizes. The proposed algorithm provides inherent privacy protection against both internal honest-but-curious agents and external eavesdroppers, without relying on any trusted neighbors. Furthermore, we incorporate an attenuation factor to effectively mitigate quantization error induced by the encryption process, ensuring almost sure convergence to the optimal solution while maintaining privacy preservation. Numerical simulations demonstrate the effectiveness and efficiency of the proposed approach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.20761v1">Geometric Renyi Differential Privacy: Ricci Curvature Characterized by Heat Diffusion Mechanisms</a></h3>
   
  <p><b>Published on:</b> 2026-04-22T16:48:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaotian Chang, Yangdi Jiang, Cyrus Mostajeran, Qirui Hu</p>
    <p><b>Summary:</b> In this paper, we develop a novel privacy mechanism for Riemannian manifold-valued data. Our key contribution lies in uncovering unexpected connections among geometric analysis, heat diffusion models, and differential privacy (DP). We characterize the Renyi divergence via dimension-free Harnack inequalities on Riemannian manifolds and establish Renyi differential privacy guarantees governed by Ricci curvature. For manifolds with nonnegative Ricci curvature, we propose a mechanism based on heat diffusion. In contrast, for general manifolds we introduce a Langevin-process-based approach that yields intrinsic mechanisms supporting normalization-free sampling and continuous privacy-utility trade-offs. We derive detailed utility analyses for both mechanisms. As a statistical application, we develop privacy-preserving estimation of the generalized Frechet mean, including nontrivial sensitivity analysis and phase transition characterizations. Numerical experiments further demonstrate the advantages of the proposed DP mechanisms over existing approaches.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.20596v1">Differentially Private Clustered Federated Learning with Privacy-Preserving Initialization and Normality-Driven Aggregation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-22T14:12:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jie Xu, Haaris Mehmood, Rogier Van Dalen, Karthikeyan Saravanan, Mete Ozay</p>
    <p><b>Summary:</b> Federated learning (FL) enables training of a global model while keeping raw data on end-devices. Despite this, FL has shown to leak private user information and thus in practice, it is often coupled with methods such as differential privacy (DP) and secure vector sum to provide formal privacy guarantees to its participants. In realistic cross-device deployments, the data are highly heterogeneous, so vanilla federated learning converges slowly and generalizes poorly. Clustered federated learning (CFL) mitigates this by segregating users into clusters, leading to lower intra-cluster data heterogeneity. Nevertheless, coupling CFL with DP remains challenging: the injected DP noise makes individual client updates excessively noisy, and the server is unable to initialize cluster centroids with the less noisy aggregated updates. To address this challenge, we propose PINA, a two-stage framework that first lets each client fine-tune a lightweight low-rank adaptation (LoRA) adapter and privately share a compressed sketch of the update. The server leverages these sketches to construct robust cluster centroids. In the second stage, PINA introduces a normality-driven aggregation mechanism that improves convergence and robustness. Our method retains the benefits of clustered FL while providing formal privacy guarantees against an untrusted server. Extensive evaluations show that our proposed method outperforms state-of-the-art DP-FL algorithms by an average of 2.9% in accuracy for privacy budgets (epsilon in {2, 8}).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.20274v2">Estimating Power-Law Exponent with Edge Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2026-04-22T07:20:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Adam Tan, Mohamed Hefny, Keval Vora</p>
    <p><b>Summary:</b> Many real-world graphs have degree distributions that are well approximated by a power-law, and the corresponding scaling parameter $α$ provides a compact summary of that structure which is useful for graph analysis and system optimization. When graphs contain sensitive relationship data, $α$ must be estimated without revealing information about individual edges. This paper studies power-law exponent estimation under edge differential privacy. Instead of first releasing a noisy degree distribution and then fitting a power-law model, we propose privatizing only the low-dimensional sufficient statistics needed to estimate $α$, thereby avoiding the high distortion introduced by traditional approaches. Using these released statistics, we support both discrete approximation and likelihood-based numerical optimization for efficient parameter estimation. We develop edge-DP algorithms for both centralized and local DP models, compare degree release and log-statistic release in the local setting, and evaluate the resulting methods on various graph datasets across multiple privacy budgets and tail-cutoff settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.20904v1">Reinforcing privacy reasoning in LLMs via normative simulacra from fiction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-04-21T19:16:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Matt Franchi, Madiha Zahrah Choksi, Harold Triedman, Helen Nissenbaum</p>
    <p><b>Summary:</b> Information handling practices of LLM agents are broadly misaligned with the contextual privacy expectations of their users. Contextual Integrity (CI) provides a principled framework, defining privacy as the appropriate flow of information within context-relative norms. However, existing approaches either double inference cost via supervisor-assistant architectures, or fine-tune on narrow task-specific data. We propose extracting normative simulacra (structured representations of norms and information flows) from fiction novels and using them to fine-tune LLMs via supervised learning followed by GRPO reinforcement learning. Our composite reward function combines programmatic signals, including task clarity (subsuming schema validity, construct discrimination, and extraction confidence), structural completeness, internal consistency, and context identification, with an LLM judge that evaluates whether the model's privacy reasoning is grounded in the held-out normative universe of the source text. To mitigate overfitting, we introduce per-completion contrastive scoring: each completion is evaluated against both the correct normative universe and a randomly selected wrong one, teaching the model to condition on context rather than memorize source-specific norms. We evaluate on five CI-aligned benchmarks spanning distinct societal contexts and ablate the contributions of RL and normative grounding. Across seven models, SFT introduces a conservative prior toward restricting information flow, improving recognition of privacy-relevant situations but not the correctness of privacy judgments. GRPO with normative grounding achieves the highest score on a law compliance benchmark and strongest correlation with crowdsourced human privacy expectations, demonstrating that fiction-derived normative simulacra can teach contextual privacy reasoning that transfers to real-world domains.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.19925v1">Behavioral Transfer in AI Agents: Evidence and Privacy Implications</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-04-21T19:11:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shilei Luo, Zhiqi Zhang, Hengchen Dai, Dennis Zhang</p>
    <p><b>Summary:</b> AI agents powered by large language models are increasingly acting on behalf of humans in social and economic environments. Prior research has focused on their task performance and effects on human outcomes, but less is known about the relationship between agents and the specific individuals who deploy them. We ask whether agents systematically reflect the behavioral characteristics of their human owners, functioning as behavioral extensions rather than producing generic outputs. We study this question using 10,659 matched human-agent pairs from Moltbook, a social media platform where each autonomous agent is publicly linked to its owner's Twitter/X account. By comparing agents' posts on Moltbook with their owners' Twitter/X activity across features spanning topics, values, affect, and linguistic style, we find systematic transfer between agents and their specific owners. This transfer persists among agents without explicit configuration, and pairs that align on one behavioral dimension tend to align on others. These patterns are consistent with transfer emerging through accumulated interaction between owners (or owners' computer environments) and their agents in everyday use. We further show that agents with stronger behavioral transfer are more likely to disclose owner-related personal information in public discourse, suggesting that the same owner-specific context that drives behavioral transfer may also create privacy risk during ordinary use. Taken together, our results indicate that AI agents do not simply generate content, but reflect owner-related context in ways that can propagate human behavioral heterogeneity into digital environments, with implications for privacy, platform design, and the governance of agentic systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.19653v2">A Dual Perspective on Synthetic Trajectory Generators: Utility Framework and Privacy Vulnerabilities</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-04-21T16:42:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aya Cherigui, Florent Guépin, Arnaud Legendre, Jean-François Couchot</p>
    <p><b>Summary:</b> Human mobility data are used in numerous applications, ranging from public health to urban planning. Human mobility is inherently sensitive, as it can contain information such as religious beliefs and political affiliations. Historically, it has been proposed to modify the information using techniques such as aggregation, obfuscation, or noise addition, to adequately protect privacy and eliminate concerns. As these methods come at a great cost in utility, new methods leveraging development in generative models, were introduced. The extent to which such methods answer the privacy-utility trade-off remains an open problem. In this paper, we introduced a first step towards solving it, by the introduction and application of a new framework for utility evaluation. Furthermore, we provide evidence that privacy evaluation remains a great challenge to consider and that it should be tackled through adversarial evaluation in accordance with the current EU regulation. We propose a new membership inference attack against a subcategory of generative models, even though this subcategory was deemed private due to its resistance over the trajectory user-linking problem.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.19422v1">Secure Storage and Privacy-Preserving Scanpath Comparison via Garbled Circuits in Eye Tracking</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-04-21T12:53:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Suleyman Ozdel, Amr Nader, Yasmeen Abdrabou, Enkelejda Kasneci</p>
    <p><b>Summary:</b> With the growing use of eye tracking on VR and mobile platforms, gaze data is increasing. While scanpath comparison is important to gaze behavior analysis, existing methods lack privacy-preserving capabilities for real-world use. We present a garbled-circuit (GC)-based approach enabling secure storage and privacy-preserving scanpath comparison under the semi-honest model. It supports two configurations: (1) a two-party setting where the data owner and processor jointly compute similarity scores without revealing their inputs, and (2) a server-assisted setting where encrypted scanpaths are stored and processed while the data owner remains offline. All decryption and comparison operations are executed inside the GC. Experiments on three eye-tracking datasets evaluate fidelity, runtime, and communication, and show secure results for MultiMatch, ScanMatch, and SubsMatch closely match plaintext outcomes, with manageable runtime and communication overhead. Tests under various network conditions indicate that the design remains feasible for real-world privacy-preserving scanpath analysis and can be extended to other GC-based behavioral algorithms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.19219v1">Sherpa.ai Privacy-Preserving Multi-Party Entity Alignment without Intersection Disclosure for Noisy Identifiers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-04-21T08:24:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Daniel M. Jimenez-Gutierrez, Enrique Zuazua, Georgios Kellaris, Joaquin Del Rio, Oleksii Sliusarenko, Xabi Uribe-Etxebarria</p>
    <p><b>Summary:</b> Federated Learning (FL) enables collaborative model training among multiple parties without centralizing raw data. There are two main paradigms in FL: Horizontal FL (HFL), where all participants share the same feature space but hold different samples, and Vertical FL (VFL), where parties possess complementary features for the same set of samples. A prerequisite for VFL training is privacy-preserving entity alignment (PPEA), which establishes a common index of samples across parties (alignment) without revealing which samples are shared between them. Conventional private set intersection (PSI) achieves alignment but leaks intersection membership, exposing sensitive relationships between datasets. The standard private set union (PSU) mitigates this risk by aligning on the union of identifiers rather than the intersection. However, existing approaches are often limited to two parties or lack support for typo-tolerant matching.
  In this paper, we introduce the Sherpa.ai multi-party PSU protocol for VFL, a PPEA method that hides intersection membership and enables both exact and noisy matching. The protocol generalizes two-party approaches to multiple parties with low communication overhead and offers two variants: an order-preserving version for exact alignment and an unordered version tolerant to typographical and formatting discrepancies. We prove correctness and privacy, analyze communication and computational (exponentiation) complexity, and formalize a universal index mapping from local records to a shared index space. This multi-party PSU offers a scalable, mathematically grounded protocol for PPEA in real-world VFL deployments, such as multi-institutional healthcare disease detection, collaborative risk modeling between banks and insurers, and cross-domain fraud detection between telecommunications and financial institutions, while preserving intersection privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.18819v1">Blockchain-Driven AI-Enhanced Post-Quantum Multivariate Identity-based Signature and Privacy-Preserving Data Aggregation Scheme for Fog-enabled Flying Ad-Hoc Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-20T20:40:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sufian Al majmaie, Ghazal Ghajari, Niraj Prasad Bhatta, Fathi Amsaad</p>
    <p><b>Summary:</b> The integration of Fog Computing with Flying Ad-Hoc Networks (FANETs) offers promising capabilities for decentralized, low-latency intelligence in UAV-based applications. However, the distributed nature, mobility, and resource constraints of FANETs expose them to significant security and privacy challenges, particularly against quantum threats. To address these issues, this work introduces a blockchain-based, AI-enhanced key management framework designed for fog-enabled FANETs. The proposed scheme employs a Post-Quantum Multivariate Identity-Based Signature Scheme (PQ-MISS) and Zero-Knowledge Proofs (ZKPs) to achieve secure key establishment, privacy-preserving data aggregation, and integrity verification. A polynomial composition-based encryption mechanism and an aggregate signature model support secure and efficient multi-device communication across fog and UAV layers. Fog servers construct partial blockchain blocks from validated UAV data. These blocks are completed and mined by Cloud Servers (CSs). AI algorithms then analyze the verified data to generate accurate predictions and insights. NS-3 simulations validate the efficiency of PQ-MISS in reducing communication overhead while improving the speed and reliability of data aggregation and verification. Comparative analysis demonstrates the proposed scheme's advantages over existing methods in computational cost, post-quantum security, and scalability, making it a robust solution for secure, intelligent, and future-ready FANET systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.18552v2">Do Privacy Policies Match with the Logs? An Empirical Study of Privacy Disclosure in Android Application Logs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2026-04-20T17:43:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhiyuan Chen, Love Jayesh Ahir, Ahmad Suleiman, Kundi Yao, Yiming Tang, Weiyi Shang, Daqing Hou</p>
    <p><b>Summary:</b> Privacy policies are intended to inform users about how software systems collect and handle data, yet they often remain vague or incomplete. This paper presents an empirical study of patterns in log-related statements within privacy policies and their alignment with privacy disclosures observed in Android application logs. We analyzed 1,000 Android apps across multiple categories, generating 86,836,964 log entries. Our findings reveal that while most applications (88.0%) provide privacy policies, only 28.5% explicitly mention logging practices. Among those that reference logging, most clearly describe what information is logged; however, 27.7% of log-related statements remain overly simplistic or vague, offering limited insight into actual data collection. We further observed widespread privacy leakages in application logs, with 67.6% of apps leaking sensitive information not mentioned in their policies. Alarmingly, only 0.4% of applications demonstrated consistent alignment between declared policy contents and actual logged data. These findings highlight that current privacy policies provide incomplete or ambiguous descriptions of logging practices, which frequently do not align with actual logging behaviors.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.18352v1">Tight Auditing of Differential Privacy in MST and AIM</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-04-20T14:45:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Georgi Ganev, Meenatchi Sundaram Muthu Selva Annamalai, Bogdan Kulynych</p>
    <p><b>Summary:</b> State-of-the-art Differentially Private (DP) synthetic data generators such as MST and AIM are widely used, yet tightly auditing their privacy guarantees remains challenging. We introduce a Gaussian Differential Privacy (GDP)-based auditing framework that measures privacy via the full false-positive/false-negative tradeoff. Applied to MST and AIM under worst-case settings, our method provides the first tight audits in the strong-privacy regime. For $(ε,δ)=(1,10^{-2})$, we obtain $μ_{emp}\approx0.43$ vs. implied $μ=0.45$, showing a small theory-practice gap.
  Our code is publicly available: https://github.com/sassoftware/dpmm.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.18302v1">Toward Zero-Egress Psychiatric AI: On-Device LLM Deployment for Privacy-Preserving Mental Health Decision Support</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-04-20T14:09:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Eranga Bandara, Asanga Gunaratna, Ross Gore, Anita H. Clayton, Christopher K. Rhea, Sachini Rajapakse, Isurunima Kularathna, Sachin Shetty, Ravi Mukkamala, Xueping Liang, Preston Samuel, Atmaram Yarlagadda</p>
    <p><b>Summary:</b> Privacy represents one of the most critical yet underaddressed barriers to AI adoption in mental healthcare -- particularly in high-sensitivity operational environments such as military, correctional, and remote healthcare settings, where the risk of patient data exposure can deter help-seeking behavior entirely. Existing AI-enabled psychiatric decision support systems predominantly rely on cloud-based inference pipelines, requiring sensitive patient data to leave the device and traverse external servers, creating unacceptable privacy and security risks in these contexts. In this paper, we propose a zero-egress, on-device AI platform for privacy-preserving psychiatric decision support, deployed as a cross-platform mobile application. The proposed system extends our prior work on fine-tuned LLM consortiums for psychiatric diagnosis standardization by fundamentally re-architecting the inference pipeline for fully local execution -- ensuring that no patient data is transmitted to, processed by, or stored on any external server at any stage. The platform integrates a consortium of three lightweight, fine-tuned, and quantized open-source LLMs -- Gemma, Phi-3.5-mini, and Qwen2 -- selected for their compact architectures and proven efficiency on resource-constrained mobile hardware. An on-device orchestration layer coordinates ensemble inference and consensus-based diagnostic reasoning, producing DSM-5-aligned assessments for conditions. The platform is designed to assist clinicians with differential diagnosis and evidence-linked symptom mapping, as well as to support patient-facing self-screening with appropriate clinical safeguards. Initial evaluation demonstrates that the proposed zero-egress deployment achieves diagnostic accuracy comparable to its server-side predecessor while sustaining real-time inference latency on commodity mobile hardware.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.18163v2">Audit-or-Cast: Enforcing Honest Elections with Privacy-Preserving Public Verification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-20T12:26:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aman Rojjha, Gaurang Tandon, Varul Srivastava, Kannan Srinathan</p>
    <p><b>Summary:</b> Electronic voting systems must balance public verifiability with voter privacy and coercion resistance. Existing cryptographic protocols typically achieve end-to-end verifiability by revealing vote distributions, relying on trusted clients, or enabling transferable receipts - design choices that often compromise trust or privacy in real-world deployments.
  We present ACE, a voting protocol that reconciles public auditability with strong privacy guarantees. The protocol combines a publicly verifiable, tally-hiding aggregation mechanism with an Audit-or-Cast challenge that enforces cast-as-intended even under untrusted client assumptions. Tallier-side re-randomization eliminates persistent links between voters and public records, yielding information-theoretic receipt-freeness assuming at least one honest tallier.
  We formalize the security of ACE and show that it simultaneously achieves end-to-end verifiability, publicly tally-hiding results, and strong receipt-freeness without trusted clients.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.17816v1">Privacy-Preserving Product-Quantized Approximate Nearest Neighbor Search Framework for Large-scale Datasets via A Hybrid of Fully Homomorphic Encryption and Trusted Execution Environment</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-20T05:14:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shozo Saeki, Minoru Kawahara, Hirohisa Aman</p>
    <p><b>Summary:</b> A nearest-neighbor framework is a fundamental tool for various applications involving Large Language Models (LLMs) and Visual Language Models (VLMs). Vectors used for nearest-neighbor searches have richer information for similarity searches. This information leads to security risks, such as embedding inversion and membership attacks. Therefore, Privacy-Preserving Approximate Nearest-Neighbor (PP-ANN) approaches are necessary for highly confidential data. However, conventional PP-ANN approaches based on a Trusted Execution Environment (TEE) or Fully Homomorphic Encryption (FHE) do not achieve practical security or performance. Additionally, conventional approaches focus on the search process rather than database generation for nearest-neighbor. To address these issues, we propose a Privacy-Preserving Product-Quantization Approximate Nearest Neighbor (PPPQ-ANN) framework. PPPQ-ANN provides a multi-layered security structure for vectors based on a hybrid of FHE and TEE. Additionally, PPPQ-ANN minimizes FHE ciphertext computations by combining Product-Quantization (PQ) with optimized data packing. We demonstrate the performance of PPPQ-ANN on million-scale datasets. As a result, PPPQ-ANN achieves database generation in less than 2 hours and more than 50 QPS in a sequential search while preserving privacy. Therefore, PPPQ-ANN optimizes the trade-off between security and performance by utilizing a hybrid of FHE and TEE, achieving practical performance while preserving privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.17796v3">Teaching Usable Privacy in HCI Education: Designing, Implementing, and Evaluating an Active Learning Graduate Course</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-04-20T04:36:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sanchari Das, Dhiman Goswami, Michelle Melo, Aditya Johri, Vivian G. Motti</p>
    <p><b>Summary:</b> As digital systems increasingly rely on pervasive data collection and inference, educating future designers and researchers about Usable Privacy has become a critical need for HCI. However, privacy education in higher education is often fragmented, theory-heavy, or detached from real-world applications. Thus, in this paper, we present the design, implementation, and evaluation of a 15-week graduate-level course on Usable Privacy that addresses this through active, practice-oriented pedagogy. The course integrates use cases, structured role playing, case-based discussions, guest lectures, and a multi-phase research project to support students in reasoning about privacy from multiple stakeholder perspectives. Grounded in contemporary privacy research and the Modern Privacy framework, the curriculum emphasizes both conceptual understanding and applied research skills. We report findings from two course offerings in consecutive years (2024-2025) using a mixed-methods evaluation that combines quantitative teaching evaluations with qualitative analysis of student reflections and instructor observations. Results indicate increased student engagement, improved ability to articulate trade-offs in privacy design, and stronger connections between theory and practice. To support adoption and replication, we also release detailed assignment descriptions and grading rubrics. This work contributes an empirically informed model for teaching Usable Privacy in HCI education and offers actionable guidance for educators seeking to integrate privacy into their curricula.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.17788v1">SoK: Analysis of Privacy Risks and Mitigation in Online Propaganda Detection through the PROMPT Framework</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B">
  <p><b>Published on:</b> 2026-04-20T04:26:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dhiman Goswami, Al Nahian Bin Emran, Md Hasan Ullah Sadi, Sanchari Das</p>
    <p><b>Summary:</b> Online propaganda detection pipelines expose measurable privacy risks at multiple stages including data collection, feature extraction, and model inference. We conduct a structured analysis of $162$ peer-reviewed studies and formalize the problem using the Propaganda Risk Online Mitigation and Privacy-preserving Tactics (PROMPT) framework. PROMPT models risks $R$ and mitigation strategies $S$ through a mapping $M: R\to S$ guided by a utility function $α\cdot \mathrm{PrivacyGain}(s_j) - β\cdot \mathrm{PerfLoss}(s_j) - γ\cdot \mathrm{Cost}(s_j)$, with tunable $(α,β,γ)$ enabling stakeholders to balance privacy, accuracy, and deployment costs. To assess practical adoption, we introduce a compliance score that quantifies the alignment of existing methods with GDPR, CCPA etc. requirements. Our evaluation shows that many widely used pipelines remain non-compliant, particularly in metadata handling and user-level aggregation. We further present empirical fine-tuning experiments on transformer-based encoders and decoders under synthetic perturbation, demonstrating a monotonic privacy-utility trade-off: with $q = 0.05$ performance decreased by 1-2% F$_1$, while at $q = 0.20$ the reduction reached 13-14%. These results establish quantitative baselines for privacy costs in propaganda detection. Our contributions include a formal risk-to-defense mapping, a compliance-oriented auditing metric, and experimental evidence of privacy-performance trade-offs, providing a technical foundation for building regulation-compliant and privacy-aware detection systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.17476v1">Privatar: Scalable Privacy-preserving Multi-user VR via Secure Offloading</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Hardware Architecture-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> 
  <p><b>Published on:</b> 2026-04-19T15:07:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jianming Tong, Hanshen Xiao, Krishna Kumar Nair, Hao Kang, Ashish Sirasao, Ziqi Zhang, G. Edward Suh, Tushar Krishna</p>
    <p><b>Summary:</b> Multi-user virtual reality enables immersive interaction. However, rendering avatars for numerous participants on each headset incurs prohibitive computational overhead, limiting scalability. We introduce a framework, Privatar, to offload avatar reconstruction from headset to untrusted devices within the same local network while safeguarding attacks against adversaries capable of intercepting offloaded data. Privatar's key insight is that domain-specific knowledge of avatar reconstruction enables provably private offloading at minimal cost. (1) System level. We observe avatar reconstruction is frequency-domain decomposable via BDCT with negligible quality drop, and propose Horizontal Partitioning (HP) to keep high-energy frequency components on-device and offloads only low-energy components. HP offloads local computation while reducing information leakage to low-energy subsets only. (2) Privacy level. For individually offloaded, multi-dimensional signals without aggregation, worst-case local Differential Privacy requires prohibitive noise, ruining utility. We observe users' expression statistical distribution are slowly changing over time and trackable online, and hence propose Distribution-Aware Minimal Perturbation. DAMP minimizes noise based on each user's expression distribution to significantly reduce its effects on utility, retaining formal privacy guarantee. Combined, HP provides empirical privacy against expression identification attacks. DAMP further augments it to offer a formal guarantee against arbitrary adversaries. On a Meta Quest Pro, Privatar supports 2.37x more concurrent users at 6.5% higher reconstruction loss and 9% energy overhead, providing a better throughout-loss Pareto frontier over quantization, sparsity and local construction baselines. Privatar provides both provable privacy guarantee and stays robust against both empirical and NN-based attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.17270v1">What Security and Privacy Transparency Users Need from Consumer-Facing Generative AI</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-04-19T05:57:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiaxun Cao, Yu Dong, Chunxi Zhan, Rithvik Neti, Sai Teja Peddinti, Pardis Emami-Naeini</p>
    <p><b>Summary:</b> Users increasingly rely on consumer-facing generative AI (GenAI) for tasks ranging from everyday needs to sensitive use cases. Yet, it remains unclear whether and how existing security and privacy (S&P) communications in GenAI tools shape users' adoption decisions and subsequent experiences. Understanding how users seek, interpret, and evaluate S&P information is critical for designing usable transparency that users can trust and act on. We conducted semi-structured interviews and design sessions with 21 U.S. GenAI users. We find that available S&P information rarely drove initial adoption in practice, as participants often perceived it as incomplete, ineffective, or lacking credibility. Instead, they relied on rough proxies, such as popularity, to infer S&P practices. After adoption, uncertainty about S&P practices constrained participants' willingness to use GenAI tools, particularly in high-stakes contexts, and, in some cases, contributed to discontinued use. Participants therefore called for transparency that supports decision-making and use, including trustworthy information (e.g., independent evaluations) and usable interfaces (e.g., on-demand disclosure). We synthesize participants' desired design practices into five dimensions to facilitate systematic future investigation into best practices. We conclude with recommendations for researchers, designers, and policymakers to improve S&P transparency in consumer-facing GenAI.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.17163v1">PPEDCRF: Dynamic-CRF-Guided Selective Perturbation for Background-Based Location Privacy in Video Sequences</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-04-18T22:52:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bo Ma, Weiqi Yan, Jinsong Wu</p>
    <p><b>Summary:</b> We propose PPEDCRF, a calibrated selective perturbation framework that protects \emph{background-based location privacy} in released video frames against gallery-based retrieval attackers. Even after GPS metadata are stripped, an adversary can geolocate a frame by matching its background visual cues to geo-tagged reference imagery; PPEDCRF mitigates this threat by estimating location-sensitive background regions with a dynamic conditional random field (DCRF), rescaling perturbation strength with a normalized control penalty (NCP), and injecting Gaussian noise only inside the inferred regions via a DP-style calibration rule.
  On a controlled paired-scene retrieval benchmark with eight attacker backbones and three noise seeds, PPEDCRF reduces ResNet18 Top-1 retrieval accuracy from 0.667 to $0.361\pm0.127$ at $σ_0=8$ while preserving $36.14\,$dB PSNR -- an ${\approx}6\,$dB quality advantage over global Gaussian noise. Transfer across the eight-backbone seed-averaged benchmark is broadly supportive (23 of 24 backbone-gallery cells show negative $Δ$), while appendix-scale confirmation identifies MixVPR as a remaining adverse-transfer exception. Matched-operating-point analysis shows that PPEDCRF and global Gaussian noise converge in Top-1 privacy at equal utility, so the practical benefit is spatially concentrated perturbation that preserves higher visual quality at any given noise scale rather than stronger matched-utility privacy. Code: https://github.com/mabo1215/PPEDCRF</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.17133v1">If Only My CGM Could Speak: A Privacy-Preserving Agent for Question Answering over Continuous Glucose Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-18T20:18:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yanjun Cui, Ali Emami, Temiloluwa Prioleau, Nikhil Singh</p>
    <p><b>Summary:</b> Continuous glucose monitors (CGMs) used in diabetes care collect rich personal health data that could improve day-to-day self-management. However, current patient platforms only offer static summaries which do not support inquisitive user queries. Large language models (LLMs) could enable free-form inquiries about continuous glucose data, but deploying them over sensitive health records raises privacy and accuracy concerns. In this paper, we present CGM-Agent, a privacy-preserving framework for question answering over personal glucose data. In our design, the LLM serves purely as a reasoning engine that selects analytical functions. All computation occurs locally, and personal health data never leaves the user's device. For evaluation, we construct a benchmark of 4,180 questions combining parameterized question templates with real user queries and ground truth derived from deterministic program execution. Evaluating 6 leading LLMs, we find that top models achieve 94\% value accuracy on synthetic queries and 88\% on ambiguous real-world queries. Errors stem primarily from intent and temporal ambiguity rather than computational failures. Additionally, lightweight models achieve competitive performance in our agent design, suggesting opportunities for low-cost deployment. We release our code and benchmark to support future work on trustworthy health agents.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.17129v1">The Privacy Placebo: Diagnosing Consent Burden through Performative Scrolling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-04-18T20:10:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haoze Guo, Ziqi Wei</p>
    <p><b>Summary:</b> While consent banners and privacy policies invite users to read and choose, many choices are shaped by repeated, low-yield interaction routines rather than deliberation. This paper studies performative scrolling: slow, low-information interaction that can signal attention to consent without substantially improving understanding. We present the Performative Scrolling Index (PSI), a reproducible interface-audit metric for measuring pre-choice burden before a meaningful non-accepting alternative becomes visible and actionable. PSI decomposes burden into four observable components: distance, time, focus loops, and hidden reveals. In this paper, PSI is the primary burden metric, while companion signals such as AAI, CSI, and divergence are used as secondary interpretive audit aids rather than standalone validated scales. We also provide a least-effort audit protocol, design-side invariants, a worked example, and a medium-scale live deployment across desktop and mobile conditions under pointer and keyboard traversal policies. Together, these analyses show how structural choices such as offscreen alternatives, fragmented disclosure, and staged modal flows can increase pre-choice friction without improving meaningful control. PSI is not a measure of comprehension or legal sufficiency; rather, it is a diagnostic of interface-side burden intended to support reproducible audits and redesigns.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.18633v1">Global Web, Local Privacy? An International Review of Web Tracking</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-04-18T19:12:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Harry Yu, Patton Yin, Sebastian Zimmeck</p>
    <p><b>Summary:</b> Web tracking by ad networks, social networks, and other third parties is privacy-invasive. To protect users' privacy an increasing number of countries are adopting new privacy laws. However, a major reason why their application on the web is so challenging is that privacy laws are local while the web is global. To that end, we evaluate websites' tracker connections for ten countries for two sets of sites -- the global Common Top 525 and the Country-specific Top 525 sites. We find that Australia and the US (California) -- two of the three opt-out jurisdictions in our study -- have the highest level of web tracking while opt-in jurisdictions generally have lower levels. We also find that the Common Top 525 sites have 50.5\% fewer average tracker connections when accessed from EU countries compared to non-EU countries. Further, simply not interacting with cookie banners decreases trackers by 48.5\% for Germany, as measured for a sample of 36 Common Top 525 sites. These results suggest that the General Data Protection Regulation and the ePrivacy Directive have a tangible effect in reducing tracking. As 28\% of Common Top 525 sites show cookie banners in all ten countries, our results suggest a moderate Brussels effect. However, against the backdrop of global US ad tech practices, EU law primarily acts as a Brussels shield. Generally, we think that strong enforcement of privacy laws is key to increase user privacy on the web.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.16834v1">Towards Deep Encrypted Training: Low-Latency, Memory-Efficient, and High-Throughput Inference for Privacy-Preserving Neural Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-04-18T04:54:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nges Brian Njungle, Eric Jahns, Michel A. Kinsy</p>
    <p><b>Summary:</b> Privacy-preserving machine learning (PPML) has become increasingly important in applications where sensitive data must remain confidential. Homomorphic Encryption (HE) enables computation directly on encrypted data, allowing neural network inference without revealing raw inputs. While prior works have largely focused on inference over a single encrypted image, batch processing of encrypted inputs lags behind, despite being critical for high-throughput inference scenarios and training-oriented workloads.
  In this work, we address this gap by developing optimized algorithms for batched HE-friendly neural networks. We also introduced a pipeline architecture designed to maximize resource efficiency for different batch size execution. We implemented these algorithms and evaluated our work using HE-friendly ResNet-20 and ResNet-34 models on encrypted CIFAR-10 and CIFAR-100 datasets, respectively.
  For ResNet-20, our approach achieves an amortized inference time of 8.86 seconds per image when processing a batch of 512 encrypted images, with a peak memory usage of 98.96 GB. These results represent a 1.78x runtime improvement and a 3.74x reduction in memory usage compared to the state-of-the-art design. For the deeper ResNet-34 model, we achieve an amortized inference time of 28.14 on a batch of 256 encrypted images using 246.78GB of RAM</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.16827v1">ParikkhaChain: Blockchain-Based Result Processing and Privacy-Preserving Academic Record Management for the Complete Examination Lifecycle</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-18T04:34:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rabib Jahin Ibn Momin, Ahmed Mahir Sultan Rumi, Rezwana Reaz</p>
    <p><b>Summary:</b> Academic examination systems worldwide continue to rely on centralised, opaque record-keeping that is often vulnerable to credential forgery, result tampering, examiner bias, and the absence of transparent re-evaluation pathways. Existing blockchain-based approaches in education focus predominantly on post-hoc certificate storage or online-only examination portals, leaving the complete onsite examination lifecycle, from conducting exams through scrutiny, largely unaddressed. This paper proposes ParikkhaChain, a blockchain-based framework that covers the entire examination lifecycle of an onsite examination system with three distinguishing contributions: (i) anonymous script evaluation through cryptographic hashing of answer scripts before examiner access, thereby eliminating identity-based bias; (ii) a transparent evaluation and scrutiny workflow backed by an immutable on-chain audit trail that records every mark submission and grade revision; and (iii) inclusion of privacy-preserving verification using zero-knowledge proofs and off-chain storage mechanisms. The system is architected around four Solidity smart contracts deployed on the Ethereum blockchain. The proposed architecture is the first initiative to our knowledge to support physical examination process, anonymous marking, and re-evaluation transparency. We successfully simulate full exam cycles of an onsite exam to grade-sheet generation using a working prototype on a large scale of 100 courses and hundreds of teachers and students. The experimental results show that the system can manage online examinations of hundreds of courses, students and faculties efficiently with great throughput, low storage, and transaction cost. Our codebase is available in open source form at https://github.com/AhmedRumi/CSE6608-ParikkhaChain</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.16760v1">Privacy-Aware Machine Unlearning with SISA for Reinforcement Learning-Based Ransomware Detection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-18T00:19:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jannatul Ferdous, Rafiqul Islam, Md Zahidul Islam</p>
    <p><b>Summary:</b> Ransomware detection systems increasingly rely on behavior-based machine learning to address evolving attack strategies. However, emerging privacy compliance, data governance, and responsible AI deployment demand not only accurate detection but also the ability to efficiently remove the influence of specific training samples without retraining the models from scratch. In this study, we present a privacy-aware machine unlearning evaluation framework for reinforcement learning (RL)-based ransomware detection built on Sharded, Isolated, Sliced, and Aggregated (SISA) training. The framework enables efficient data deletion by retraining only the affected model shards rather than the entire detector, reducing the retraining cost while preserving detection performance. We conduct a controlled comparative study using value-based RL agents, including Deep Q-Network (DQN) and Double Deep Q-Network (DDQN), under identical experimental settings with a cost-sensitive reward design and 5-fold cross-validation on Windows 11 ransomware dataset. Detection confidence is evaluated using a continuous Q-score margin, enabling ROC-AUC analysis beyond binary predictions. For unlearning, the dataset is partitioned into five shards with majority-vote aggregation, and a fast-unlearning path is evaluated by deleting 5% of the samples from a single shard and retraining only that shard. Results show that SISA-based unlearning incurs negligible utility degradation (<= 0.05 percent F1 drop) while substantially reducing retraining time relative to full SISA retraining. DDQN exhibits slightly improved stability and lower utility loss than DQN, while both agents maintain near identical in-distribution performance after unlearning. These findings indicate that SISA provides an efficient unlearning mechanism for RL-based ransomware detection, supporting privacy-aware deployment without compromising security effectiveness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.16612v1">FedLLM: A Privacy-Preserving Federated Large Language Model for Explainable Traffic Flow Prediction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-04-17T18:09:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Seerat Kaur, Sukhjit Singh Sehra, Dariush Ebrahimi</p>
    <p><b>Summary:</b> Traffic prediction plays a central role in intelligent transportation systems (ITS) by supporting real-time decision-making, congestion management, and long-term planning. However, many existing approaches face practical limitations. Most spatio-temporal models are trained on centralized data, rely on numerical representations, and offer limited explainability. Recent Large Language Model (LLM) methods improve reasoning capabilities but typically assume centralized data availability and do not fully capture the distributed and heterogeneous nature of real-world traffic systems. To address these challenges, this study proposes FedLLM (Federated LLM), a privacy-preserving and distributed framework for explainable multi-horizon short-term traffic flow prediction (15-60 minutes). The framework introduces four key contributions: 1) a Composite Selection Score (CSS) for data-driven freeway selection that captures structural diversity across traffic regions 2) a domain-adapted LLM fine-tuned on structured traffic prompts encoding spatial, temporal, and statistical context 3) FedLLM framework, that enables collaborative training across heterogeneous clients while exchanging only lightweight LoRA adapter parameters, 4) a structured prompt representation that supports contextual reasoning and cross-region generalization. The FedLLM design allows each client to learn from local traffic patterns while contributing to a shared global model through efficient parameter exchange, reducing communication overhead and keeping data private. This setup supports learning under non-IID traffic distributions. Experimental results show that FedLLM achieves improved predictive performance over centralized baselines, while producing structured and explainable outputs. These findings highlight the potential of combining FL with domain-adapted LLMs for scalable, privacy-aware, and explainable traffic prediction.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.16606v1">SafeLM: Unified Privacy-Aware Optimization for Trustworthy Federated Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-04-17T18:00:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Noor Islam S. Mohammad, Uluğ Bayazıt</p>
    <p><b>Summary:</b> Large language models (LLMs) are increasingly deployed in high-stakes domains, yet a unified treatment of their overlapping safety challenges remains lacking. We present SafeLM, a framework that jointly addresses four pillars of LLM safety: privacy, security, misinformation, and adversarial robustness. SafeLM combines federated training with gradient smartification and Paillier encryption for privacy, integrates defenses against training and inference-time attacks, employs contrastive grounding with calibrated decoding to reduce hallucinations, and introduces alignment-aware binarized aggregation to enhance robustness while maintaining bounded reconstruction quality. Across benchmarks on factuality, toxicity, and membership inference, SafeLM achieves 98.0% harmful content detection accuracy, reduces communication by 96.9%, and lowers gradient inversion PSNR from 31.7 dB to 15.1 dB. Ablations show that each component contributes independently, whereas their integration yields a strong privacy utility efficiency trade-off for deploying trustworthy LLMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.16128v1">PolicyGapper: Automated Detection of Inconsistencies Between Google Play Data Safety Sections and Privacy Policies Using LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-17T15:02:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Luca Ferrari, Billel Habbati, Meriem Guerar, Mariano Ceccato, Luca Verderame</p>
    <p><b>Summary:</b> Mobile application developers are required to disclose how they collect, use, and share user data in compliance with privacy regulations. To support transparency, major app marketplaces have introduced standardized disclosure mechanisms. In 2022, Google mandated the Data Safety Section (DSS) on Google Play, requiring developers to summarize their data practices. However, compiling accurate DSS disclosures is challenging, as they must remain consistent with the corresponding privacy policy (PP), and no automated tool currently verifies this alignment. Prior studies indicate that nearly 80% of popular apps contain incomplete or misleading DSS declarations. We present PolicyGapper, an LLM-based methodology for automatically detecting discrepancies between DSS disclosures and privacy policies. PolicyGapper operates in four stages: scraping, pre-processing, analysis, and post-processing, without requiring access to application binaries. We evaluate PolicyGapper on a dataset of 330 top-ranked apps spanning all 33 Google Play categories, collected in Q3 2025. The approach identifies 2,689 omitted disclosures, including 2,040 related to data collection and 649 to data sharing. Manual validation on a stratified 10% subset, repeated across three independent runs, yields an average Precision of 0.75, Recall of 0.77, Accuracy of 0.69, and F1-score of 0.76. To support reproducibility, we release a complete replication package, including the dataset, prompts, source code, and results available at https://github.com/Mobile-IoT-Security-Lab/PolicyGapper and https://doi.org/10.5281/zenodo.19628493.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.16068v1">A Novel Framework for Transmitter Privacy in Integrated Sensing and Communication</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-04-17T13:52:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vaibhav Kumar, Ahmad Bazzi, Christina Pöpper, Marwa Chafii</p>
    <p><b>Summary:</b> ISAC systems introduce new privacy risks because an unintended sensing node may exploit the shared radio waveform to infer transmitter-related information even when the communication payload remains secure. This paper investigates transmitter privacy, defined as limiting unauthorized inference of transmitter-related information through channel estimation, in a RIS-aided multi-antenna wireless system with a transmitter, a legitimate receiver, a malicious sensor, and a RIS. The malicious sensor is assumed to estimate the transmitter--sensor channel, and the resulting channel state information can then support unauthorized sensing, inference, or related signal processing. To mitigate this threat, we consider a privacy-oriented design in which the transmitter adopts superposition-based signaling with a message signal and transmit-side artificial noise, while the RIS shapes the propagation environment in a privacy-aware manner. The channel-estimation performance at the malicious sensor is first analyzed under imperfect prior knowledge, and both the true and predicted mean-square-error expressions are derived. Based on this analysis, we formulate a joint active--passive beamforming design problem that maximizes the malicious sensor's predicted channel-estimation error subject to a communication quality-of-service constraint, a transmit-power budget, and the unit-modulus constraints of the RIS. The resulting non-convex problem is handled through a numerically efficient alternating-optimization framework based on an augmented Lagrangian reformulation. Numerical results show that RIS-assisted propagation shaping can substantially degrade unauthorized channel estimation relative to the non-RIS case while preserving reliable communication, and further show that the privacy gains also improve a more direct sensing metric, namely the malicious sensor's angle-of-arrival estimation accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.15851v1">DPrivBench: Benchmarking LLMs' Reasoning for Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-17T09:03:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Erchi Wang, Pengrun Huang, Eli Chien, Om Thakkar, Kamalika Chaudhuri, Yu-Xiang Wang, Ruihan Wu</p>
    <p><b>Summary:</b> Differential privacy (DP) has a wide range of applications for protecting data privacy, but designing and verifying DP algorithms requires expert-level reasoning, creating a high barrier for non-expert practitioners. Prior works either rely on specialized verification languages that demand substantial domain expertise or remain semi-automated and require human-in-the-loop guidance. In this work, we investigate whether large language models (LLMs) can automate DP reasoning. We introduce DPrivBench, a benchmark in which each instance asks whether a function or algorithm satisfies a stated DP guarantee under specified assumptions. The benchmark is carefully designed to cover a broad range of DP topics, span diverse difficulty levels, and resist shortcut reasoning through trivial pattern matching. Experiments show that while the strongest models handle textbook mechanisms well, all models struggle with advanced algorithms, revealing substantial gaps in current DP reasoning capabilities. Through further analytic study and failure-mode analysis, we identify several promising directions for improving automated DP reasoning. Our benchmark provides a solid foundation for developing and evaluating such methods, and complements existing benchmarks for mathematical reasoning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.15728v1">Privacy-Preserving LLMs Routing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-04-17T06:02:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xidong Wu, Yukuan Zhang, Yuqiong Ji, Reza Shirkavand, Qian Lou, Shangqian Gao</p>
    <p><b>Summary:</b> Large language model (LLM) routing has emerged as a critical strategy to balance model performance and cost-efficiency by dynamically selecting services from various model providers. However, LLM routing adds an intermediate layer between users and LLMs, creating new privacy risks to user data. These privacy risks have not been systematically studied. Although cryptographic techniques such as Secure Multi-Party Computation (MPC) enable privacy-preserving computation, their protocol design and implementation remain under-explored, and naïve implementations typically incur prohibitive computational overhead. To address this, we propose a privacy-preserving LLM routing framework (PPRoute). PPRoute includes multiple strategies to speed up encoder inference and nearest neighbor search under the MPC and maintain the quality of LLM routing. First, PPRoute uses MPC-friendly operations to boost the encoder inference. Second, PPRoute uses a multiple-step model training algorithm to maintain routing quality despite the constraints of the encrypted domain. Third, PPRoute proposes an unsorted Top-k algorithm with $O(1)$ communication complexity for secure sorting in model search, significantly reducing communication latency. Across different datasets, PPRoute achieves the performance of plaintext counterparts, while achieving approximately a 20$\times$ speedup over naïve MPC implementations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.15596v2">Privacy, Prediction, and Allocation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-17T00:31:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ben Jacobsen, Nitin Kohli</p>
    <p><b>Summary:</b> Algorithmic predictions are increasingly used to inform the allocation of scarce resources. The promise of these methods is that, through machine learning, they can better identify the people who would benefit most from interventions. Recently, however, several works have called this assumption into question by demonstrating the existence of settings where simple, unit-level allocation strategies can meet or even exceed the performance of those based on individual-level targeting. Separately, other works have objected to individual-level targeting on privacy grounds, leading to an unusual situation where a single solution, unit-level targeting, is recommended for reasons of both privacy and utility. Motivated by the desire to fully understand the interplay of privacy and targeting levels, we initiate the study of aid allocation systems that satisfy differential privacy, synthesizing existing works on private optimization with the economic models of aid allocation used in the non-private literature. To this end, we investigate private variants of both individual and unit-level allocation strategies in both stochastic and distribution-free settings under a range of constraints on data availability. Through this analysis, we provide clean, interpretable bounds characterizing the tradeoffs between privacy, efficiency, and targeting precision in allocation.</p>
  </details>
</div>

