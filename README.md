
<h2>2025-07</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.00128v1">How Quantization Impacts Privacy Risk on LLMs for Code?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-07-31T19:28:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Md Nazmul Haque, Hua Yang, Zhou Yang, Bowen Xu</p>
    <p><b>Summary:</b> Large language models for code (LLMs4Code) rely heavily on massive training
data, including sensitive data, such as cloud service credentials of the
projects and personal identifiable information of the developers, raising
serious privacy concerns. Membership inference (MI) has recently emerged as an
effective tool for assessing privacy risk by identifying whether specific data
belong to a model's training set. In parallel, model compression techniques,
especially quantization, have gained traction for reducing computational costs
and enabling the deployment of large models. However, while quantized models
still retain knowledge learned from the original training data, it remains
unclear whether quantization affects their ability to retain and expose privacy
information. Answering this question is of great importance to understanding
privacy risks in real-world deployments. In this work, we conduct the first
empirical study on how quantization influences task performance and privacy
risk simultaneously in LLMs4Code. To do this, we implement widely used
quantization techniques (static and dynamic) to three representative model
families, namely Pythia, CodeGen, and GPTNeo. Our results demonstrate that
quantization has a significant impact on reducing the privacy risk relative to
the original model. We also uncover a positive correlation between task
performance and privacy risk, indicating an underlying tradeoff. Moreover, we
reveal the possibility that quantizing larger models could yield better balance
than using full-precision small models. Finally, we demonstrate that these
findings generalize across different architectures, model sizes and MI methods,
offering practical guidance for safeguarding privacy when deploying compressed
LLMs4Code.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.23569v1">Gaussian Splatting Feature Fields for Privacy-Preserving Visual
  Localization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-07-31T13:58:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maxime Pietrantoni, Gabriela Csurka, Torsten Sattler</p>
    <p><b>Summary:</b> Visual localization is the task of estimating a camera pose in a known
environment. In this paper, we utilize 3D Gaussian Splatting (3DGS)-based
representations for accurate and privacy-preserving visual localization. We
propose Gaussian Splatting Feature Fields (GSFFs), a scene representation for
visual localization that combines an explicit geometry model (3DGS) with an
implicit feature field. We leverage the dense geometric information and
differentiable rasterization algorithm from 3DGS to learn robust feature
representations grounded in 3D. In particular, we align a 3D scale-aware
feature field and a 2D feature encoder in a common embedding space through a
contrastive framework. Using a 3D structure-informed clustering procedure, we
further regularize the representation learning and seamlessly convert the
features to segmentations, which can be used for privacy-preserving visual
localization. Pose refinement, which involves aligning either feature maps or
segmentations from a query image with those rendered from the GSFFs scene
representation, is used to achieve localization. The resulting privacy- and
non-privacy-preserving localization pipelines, evaluated on multiple real-world
datasets, show state-of-the-art performances.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.23432v1">Scalable contribution bounding to achieve privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-07-31T11:14:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vincent Cohen-Addad, Alessandro Epasto, Jason Lee, Morteza Zadimoghaddam</p>
    <p><b>Summary:</b> In modern datasets, where single records can have multiple owners, enforcing
user-level differential privacy requires capping each user's total
contribution. This "contribution bounding" becomes a significant combinatorial
challenge. Existing sequential algorithms for this task are computationally
intensive and do not scale to the massive datasets prevalent today. To address
this scalability bottleneck, we propose a novel and efficient distributed
algorithm. Our approach models the complex ownership structure as a hypergraph,
where users are vertices and records are hyperedges. The algorithm proceeds in
rounds, allowing users to propose records in parallel. A record is added to the
final dataset only if all its owners unanimously agree, thereby ensuring that
no user's predefined contribution limit is violated. This method aims to
maximize the size of the resulting dataset for high utility while providing a
practical, scalable solution for implementing user-level privacy in large,
real-world systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.23291v2">Evaluating the Dynamics of Membership Privacy in Deep Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-31T07:09:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuetian Chen, Zhiqi Wang, Nathalie Baracaldo, Swanand Ravindra Kadhe, Lei Yu</p>
    <p><b>Summary:</b> Membership inference attacks (MIAs) pose a critical threat to the privacy of
training data in deep learning. Despite significant progress in attack
methodologies, our understanding of when and how models encode membership
information during training remains limited. This paper presents a dynamic
analytical framework for dissecting and quantifying privacy leakage dynamics at
the individual sample level. By tracking per-sample vulnerabilities on an
FPR-TPR plane throughout training, our framework systematically measures how
factors such as dataset complexity, model architecture, and optimizer choice
influence the rate and severity at which samples become vulnerable. Crucially,
we discover a robust correlation between a sample's intrinsic learning
difficulty, and find that the privacy risk of samples highly vulnerable in the
final trained model is largely determined early during training. Our results
thus provide a deeper understanding of how privacy risks dynamically emerge
during training, laying the groundwork for proactive, privacy-aware model
training strategies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.23229v1">Fine-Grained Privacy Extraction from Retrieval-Augmented Generation
  Systems via Knowledge Asymmetry Exploitation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-31T03:50:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yufei Chen, Yao Wang, Haibin Zhang, Tao Gu</p>
    <p><b>Summary:</b> Retrieval-augmented generation (RAG) systems enhance large language models
(LLMs) by integrating external knowledge bases, but this advancement introduces
significant privacy risks. Existing privacy attacks on RAG systems can trigger
data leakage but often fail to accurately isolate knowledge-base-derived
sentences within mixed responses. They also lack robustness when applied across
multiple domains. This paper addresses these challenges by presenting a novel
black-box attack framework that exploits knowledge asymmetry between RAG and
standard LLMs to achieve fine-grained privacy extraction across heterogeneous
knowledge landscapes. We propose a chain-of-thought reasoning strategy that
creates adaptive prompts to steer RAG systems away from sensitive content.
Specifically, we first decompose adversarial queries to maximize information
disparity and then apply a semantic relationship scoring to resolve lexical and
syntactic ambiguities. We finally train a neural network on these feature
scores to precisely identify sentences containing private information. Unlike
prior work, our framework generalizes to unseen domains through iterative
refinement without pre-defined knowledge. Experimental results show that we
achieve over 91% privacy extraction rate in single-domain and 83% in
multi-domain scenarios, reducing sensitive sentence exposure by over 65% in
case studies. This work bridges the gap between attack and defense in RAG
systems, enabling precise extraction of private information while providing a
foundation for adaptive mitigation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.22534v1">The Risks and Detection of Overestimated Privacy Protection in Voice
  Anonymisation</a></h3>
  
  <p><b>Published on:</b> 2025-07-30T10:02:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Michele Panariello, Sarina Meyer, Pierre Champion, Xiaoxiao Miao, Massimiliano Todisco, Ngoc Thang Vu, Nicholas Evans</p>
    <p><b>Summary:</b> Voice anonymisation aims to conceal the voice identity of speakers in speech
recordings. Privacy protection is usually estimated from the difficulty of
using a speaker verification system to re-identify the speaker
post-anonymisation. Performance assessments are therefore dependent on the
verification model as well as the anonymisation system. There is hence
potential for privacy protection to be overestimated when the verification
system is poorly trained, perhaps with mismatched data. In this paper, we
demonstrate the insidious risk of overestimating anonymisation performance and
show examples of exaggerated performance reported in the literature. For the
worst case we identified, performance is overestimated by 74% relative. We then
introduce a means to detect when performance assessment might be untrustworthy
and show that it can identify all overestimation scenarios presented in the
paper. Our solution is openly available as a fork of the 2024 VoicePrivacy
Challenge evaluation toolkit.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.02836v1">Agentic Privacy-Preserving Machine Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-07-30T08:20:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mengyu Zhang, Zhuotao Liu, Jingwen Huang, Xuanqi Liu</p>
    <p><b>Summary:</b> Privacy-preserving machine learning (PPML) is critical to ensure data privacy
in AI. Over the past few years, the community has proposed a wide range of
provably secure PPML schemes that rely on various cryptography primitives.
However, when it comes to large language models (LLMs) with billions of
parameters, the efficiency of PPML is everything but acceptable. For instance,
the state-of-the-art solution for confidential LLM inference represents at
least 10,000-fold slower performance compared to plaintext inference. The
performance gap is even larger when the context length increases. In this
position paper, we propose a novel framework named Agentic-PPML to make PPML in
LLMs practical. Our key insight is to employ a general-purpose LLM for intent
understanding and delegate cryptographically secure inference to specialized
models trained on vertical domains. By modularly separating language intent
parsing - which typically involves little or no sensitive information - from
privacy-critical computation, Agentic-PPML completely eliminates the need for
the LLMs to process the encrypted prompts, enabling practical deployment of
privacy-preserving LLM-centric services.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.22208v1">Quantum-Inspired Audio Unlearning: Towards Privacy-Preserving Voice
  Biometrics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> 
  <p><b>Published on:</b> 2025-07-29T20:12:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shreyansh Pathak, Sonu Shreshtha, Richa Singh, Mayank Vatsa</p>
    <p><b>Summary:</b> The widespread adoption of voice-enabled authentication and audio biometric
systems have significantly increased privacy vulnerabilities associated with
sensitive speech data. Compliance with privacy regulations such as GDPR's right
to be forgotten and India's DPDP Act necessitates targeted and efficient
erasure of individual-specific voice signatures from already-trained biometric
models. Existing unlearning methods designed for visual data inadequately
handle the sequential, temporal, and high-dimensional nature of audio signals,
leading to ineffective or incomplete speaker and accent erasure. To address
this, we introduce QPAudioEraser, a quantum-inspired audio unlearning
framework. Our our-phase approach involves: (1) weight initialization using
destructive interference to nullify target features, (2) superposition-based
label transformations that obscure class identity, (3) an
uncertainty-maximizing quantum loss function, and (4) entanglement-inspired
mixing of correlated weights to retain model knowledge. Comprehensive
evaluations with ResNet18, ViT, and CNN architectures across AudioMNIST, Speech
Commands, LibriSpeech, and Speech Accent Archive datasets validate
QPAudioEraser's superior performance. The framework achieves complete erasure
of target data (0% Forget Accuracy) while incurring minimal impact on model
utility, with a performance degradation on retained data as low as 0.05%.
QPAudioEraser consistently surpasses conventional baselines across
single-class, multi-class, sequential, and accent-level erasure scenarios,
establishing the proposed approach as a robust privacy-preserving solution.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.22153v1">Towards Privacy-preserving Photorealistic Self-avatars in Mixed Reality</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-29T18:37:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ethan Wilson, Vincent Bindschaedler, Sophie Jörg, Sean Sheikholeslam, Kevin Butler, Eakta Jain</p>
    <p><b>Summary:</b> Photorealistic 3D avatar generation has rapidly improved in recent years, and
realistic avatars that match a user's true appearance are more feasible in
Mixed Reality (MR) than ever before. Yet, there are known risks to sharing
one's likeness online, and photorealistic MR avatars could exacerbate these
risks. If user likenesses were to be shared broadly, there are risks for cyber
abuse or targeted fraud based on user appearances. We propose an alternate
avatar rendering scheme for broader social MR -- synthesizing realistic avatars
that preserve a user's demographic identity while being distinct enough from
the individual user to protect facial biometric information. We introduce a
methodology for privatizing appearance by isolating identity within the feature
space of identity-encoding generative models. We develop two algorithms that
then obfuscate identity: \epsmethod{} provides differential privacy guarantees
and \thetamethod{} provides fine-grained control for the level of identity
offset. These methods are shown to successfully generate de-identified virtual
avatars across multiple generative architectures in 2D and 3D. With these
techniques, it is possible to protect user privacy while largely preserving
attributes related to sense of self. Employing these techniques in public
settings could enable the use of photorealistic avatars broadly in MR,
maintaining high realism and immersion without privacy risk.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.21904v1">Privacy-Preserving Anonymization of System and Network Event Logs Using
  Salt-Based Hashing and Temporal Noise</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-29T15:16:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shreyas Bargale, Akshit Vakati Venkata, Jaimandeep Singh, Chester Rebeiro</p>
    <p><b>Summary:</b> System and network event logs are essential for security analytics, threat
detection, and operational monitoring. However, these logs often contain
Personally Identifiable Information (PII), raising significant privacy concerns
when shared or analyzed. A key challenge in log anonymization is balancing
privacy protection with the retention of sufficient structure for meaningful
analysis. Overly aggressive anonymization can destroy contextual integrity,
while weak techniques risk re-identification through linkage or inference
attacks. This paper introduces novel field-specific anonymization methods that
address this trade-off. For IP addresses, we propose a salt-based hashing
technique applied at the per-octet level, preserving both subnet and host
structure to enable correlation across various log entries while ensuring
non-reversibility. For port numbers, full-value hashing with range mapping
maintains interpretability. We also present an order-preserving timestamp
anonymization scheme using adaptive noise injection, which obfuscates exact
times without disrupting event sequences. An open-source tool implementing
these techniques has been released to support practical deployment and
reproducible research. Evaluations using entropy metrics, collision rates, and
residual leakage analysis demonstrate that the proposed approach effectively
protects privacy while preserving analytical utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.21769v1">Factorization by extremal privacy mechanisms: new insights into
  efficiency</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Probability-5BC0EB">  
  <p><b>Published on:</b> 2025-07-29T12:52:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chiara Amorino, Arnaud Gloter</p>
    <p><b>Summary:</b> We study the problem of efficiency under $\alpha$ local differential privacy
($\alpha$ LDP) in both discrete and continuous settings. Building on a
factorization lemma, which shows that any privacy mechanism can be decomposed
into an extremal mechanism followed by additional randomization, we reduce the
Fisher information maximization problem to a search over extremal mechanisms.
The representation of extremal mechanisms requires working in infinite
dimensional spaces and invokes advanced tools from convex and functional
analysis, such as Choquet's theorem. Our analysis establishes matching upper
and lower bounds on the Fisher information in the high privacy regime ($\alpha
\to 0$), and proves that the maximization problem always admits a solution for
any $\alpha$. As a concrete application, we consider the problem of estimating
the parameter of a uniform distribution on $[0, \theta]$ under $\alpha$ LDP.
Guided by our theoretical findings, we design an extremal mechanism that yields
a consistent and asymptotically efficient estimator in high privacy regime.
Numerical experiments confirm our theoretical results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.20688v1">Guard-GBDT: Efficient Privacy-Preserving Approximated GBDT Training on
  Vertical Dataset</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-28T10:16:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anxiao Song, Shujie Cui, Jianli Bai, Ke Cheng, Yulong Shen, Giovanni Russello</p>
    <p><b>Summary:</b> In light of increasing privacy concerns and stringent legal regulations,
using secure multiparty computation (MPC) to enable collaborative GBDT model
training among multiple data owners has garnered significant attention. Despite
this, existing MPC-based GBDT frameworks face efficiency challenges due to high
communication costs and the computation burden of non-linear operations, such
as division and sigmoid calculations. In this work, we introduce Guard-GBDT, an
innovative framework tailored for efficient and privacy-preserving GBDT
training on vertical datasets. Guard-GBDT bypasses MPC-unfriendly division and
sigmoid functions by using more streamlined approximations and reduces
communication overhead by compressing the messages exchanged during gradient
aggregation. We implement a prototype of Guard-GBDT and extensively evaluate
its performance and accuracy on various real-world datasets. The results show
that Guard-GBDT outperforms state-of-the-art HEP-XGB (CIKM'21) and SiGBDT (ASIA
CCS'24) by up to $2.71\times$ and $12.21 \times$ on LAN network and up to
$2.7\times$ and $8.2\times$ on WAN network. Guard-GBDT also achieves comparable
accuracy with SiGBDT and plaintext XGBoost (better than HEP-XGB ), which
exhibits a deviation of $\pm1\%$ to $\pm2\%$ only. Our implementation code is
provided at https://github.com/XidianNSS/Guard-GBDT.git.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.20573v1">Reminiscence Attack on Residuals: Exploiting Approximate Machine
  Unlearning for Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-07-28T07:12:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yaxin Xiao, Qingqing Ye, Li Hu, Huadi Zheng, Haibo Hu, Zi Liang, Haoyang Li, Yijie Jiao</p>
    <p><b>Summary:</b> Machine unlearning enables the removal of specific data from ML models to
uphold the right to be forgotten. While approximate unlearning algorithms offer
efficient alternatives to full retraining, this work reveals that they fail to
adequately protect the privacy of unlearned data. In particular, these
algorithms introduce implicit residuals which facilitate privacy attacks
targeting at unlearned data. We observe that these residuals persist regardless
of model architectures, parameters, and unlearning algorithms, exposing a new
attack surface beyond conventional output-based leakage. Based on this insight,
we propose the Reminiscence Attack (ReA), which amplifies the correlation
between residuals and membership privacy through targeted fine-tuning
processes. ReA achieves up to 1.90x and 1.12x higher accuracy than prior
attacks when inferring class-wise and sample-wise membership, respectively. To
mitigate such residual-induced privacy risk, we develop a dual-phase
approximate unlearning framework that first eliminates deep-layer unlearned
data traces and then enforces convergence stability to prevent models from
"pseudo-convergence", where their outputs are similar to retrained models but
still preserve unlearned residuals. Our framework works for both classification
and generation tasks. Experimental evaluations confirm that our approach
maintains high unlearning efficacy, while reducing the adaptive privacy attack
accuracy to nearly random guess, at the computational cost of 2-12% of full
retraining from scratch.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.20557v1">FED-PsyAU: Privacy-Preserving Micro-Expression Recognition via
  Psychological AU Coordination and Dynamic Facial Motion Modeling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-07-28T06:42:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jingting Li, Yu Qian, Lin Zhao, Su-Jing Wang</p>
    <p><b>Summary:</b> Micro-expressions (MEs) are brief, low-intensity, often localized facial
expressions. They could reveal genuine emotions individuals may attempt to
conceal, valuable in contexts like criminal interrogation and psychological
counseling. However, ME recognition (MER) faces challenges, such as small
sample sizes and subtle features, which hinder efficient modeling.
Additionally, real-world applications encounter ME data privacy issues, leaving
the task of enhancing recognition across settings under privacy constraints
largely unexplored. To address these issues, we propose a FED-PsyAU research
framework. We begin with a psychological study on the coordination of upper and
lower facial action units (AUs) to provide structured prior knowledge of facial
muscle dynamics. We then develop a DPK-GAT network that combines these
psychological priors with statistical AU patterns, enabling hierarchical
learning of facial motion features from regional to global levels, effectively
enhancing MER performance. Additionally, our federated learning framework
advances MER capabilities across multiple clients without data sharing,
preserving privacy and alleviating the limited-sample issue for each client.
Extensive experiments on commonly-used ME databases demonstrate the
effectiveness of our approach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.20537v1">Next-Generation Quantum Neural Networks: Enhancing Efficiency, Security,
  and Privacy</a></h3>
  
  <p><b>Published on:</b> 2025-07-28T05:43:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nouhaila Innan, Muhammad Kashif, Alberto Marchisio, Mohamed Bennai, Muhammad Shafique</p>
    <p><b>Summary:</b> This paper provides an integrated perspective on addressing key challenges in
developing reliable and secure Quantum Neural Networks (QNNs) in the Noisy
Intermediate-Scale Quantum (NISQ) era. In this paper, we present an integrated
framework that leverages and combines existing approaches to enhance QNN
efficiency, security, and privacy. Specifically, established optimization
strategies, including efficient parameter initialization, residual quantum
circuit connections, and systematic quantum architecture exploration, are
integrated to mitigate issues such as barren plateaus and error propagation.
Moreover, the methodology incorporates current defensive mechanisms against
adversarial attacks. Finally, Quantum Federated Learning (QFL) is adopted
within this framework to facilitate privacy-preserving collaborative training
across distributed quantum systems. Collectively, this synthesized approach
seeks to enhance the robustness and real-world applicability of QNNs, laying
the foundation for reliable quantum-enhanced machine learning applications in
finance, healthcare, and cybersecurity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.20060v1">ModShift: Model Privacy via Designed Shifts</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2025-07-26T21:00:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nomaan A. Kherani, Urbashi Mitra</p>
    <p><b>Summary:</b> In this paper, shifts are introduced to preserve model privacy against an
eavesdropper in federated learning. Model learning is treated as a parameter
estimation problem. This perspective allows us to derive the Fisher Information
matrix of the model updates from the shifted updates and drive them to
singularity, thus posing a hard estimation problem for Eve. The shifts are
securely shared with the central server to maintain model accuracy at the
server and participating devices. A convergence test is proposed to detect if
model updates have been tampered with and we show that our scheme passes this
test. Numerical results show that our scheme achieves a higher model shift when
compared to a noise injection scheme while requiring a lesser bandwidth secret
channel.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.19116v1">Graph Structure Learning with Privacy Guarantees for Open Graph Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-25T09:51:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Muhao Guo, Jiaqi Wu, Yang Weng, Yizheng Liao, Shengzhe Chen</p>
    <p><b>Summary:</b> Ensuring privacy in large-scale open datasets is increasingly challenging
under regulations such as the General Data Protection Regulation (GDPR). While
differential privacy (DP) provides strong theoretical guarantees, it primarily
focuses on noise injection during model training, neglecting privacy
preservation at the data publishing stage. Existing privacy-preserving data
publishing (PPDP) approaches struggle to balance privacy and utility,
particularly when data publishers and users are distinct entities. To address
this gap, we focus on the graph recovery problem and propose a novel
privacy-preserving estimation framework for open graph data, leveraging
Gaussian DP (GDP) with a structured noise-injection mechanism. Unlike
traditional methods that perturb gradients or model updates, our approach
ensures unbiased graph structure recovery while enforcing DP at the data
publishing stage. Moreover, we provide theoretical guarantees on estimation
accuracy and extend our method to discrete-variable graphs, a setting often
overlooked in DP research. Experimental results in graph learning demonstrate
robust performance, offering a viable solution for privacy-conscious graph
analysis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.18518v2">Transform Before You Query: A Privacy-Preserving Approach for Vector
  Retrieval with Embedding Space Alignment</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2025-07-24T15:41:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruiqi He, Zekun Fei, Jiaqi Li, Xinyuan Zhu, Biao Yi, Siyi Lv, Weijie Liu, Zheli Liu</p>
    <p><b>Summary:</b> Vector Database (VDB) can efficiently index and search high-dimensional
vector embeddings from unstructured data, crucially enabling fast semantic
similarity search essential for modern AI applications like generative AI and
recommendation systems. Since current VDB service providers predominantly use
proprietary black-box models, users are forced to expose raw query text to them
via API in exchange for the vector retrieval services. Consequently, if query
text involves confidential records from finance or healthcare domains, this
mechanism inevitably leads to critical leakage of user's sensitive information.
To address this issue, we introduce STEER (\textbf{S}ecure \textbf{T}ransformed
\textbf{E}mbedding v\textbf{E}ctor\textbf{ R}etrieval), a private vector
retrieval framework that leverages the alignment relationship between the
semantic spaces of different embedding models to derive approximate embeddings
for the query text. STEER performs the retrieval using the approximate
embeddings within the original VDB and requires no modifications to the server
side. Our theoretical and experimental analyses demonstrate that STEER
effectively safeguards query text privacy while maintaining the retrieval
accuracy. Even though approximate embeddings are approximations of the
embeddings from proprietary models, they still prevent the providers from
recovering the query text through Embedding Inversion Attacks (EIAs). Extensive
experimental results show that Recall@100 of STEER can basically achieve a
decrease of less than 5\%. Furthermore, even when searching within a text
corpus of millions of entries, STEER achieves a Recall@20 accuracy 20\% higher
than current baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.18365v3">RecPS: Privacy Risk Scoring for Recommender Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-24T12:46:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiajie He, Yuechun Gu, Keke Chen</p>
    <p><b>Summary:</b> Recommender systems (RecSys) have become an essential component of many web
applications. The core of the system is a recommendation model trained on
highly sensitive user-item interaction data. While privacy-enhancing techniques
are actively studied in the research community, the real-world model
development still depends on minimal privacy protection, e.g., via controlled
access. Users of such systems should have the right to choose \emph{not} to
share highly sensitive interactions. However, there is no method allowing the
user to know which interactions are more sensitive than others. Thus,
quantifying the privacy risk of RecSys training data is a critical step to
enabling privacy-aware RecSys model development and deployment. We propose a
membership-inference attack (MIA)- based privacy scoring method, RecPS, to
measure privacy risks at both the interaction and user levels. The RecPS
interaction-level score definition is motivated and derived from differential
privacy, which is then extended to the user-level scoring method. A critical
component is the interaction-level MIA method RecLiRA, which gives high-quality
membership estimation. We have conducted extensive experiments on well-known
benchmark datasets and RecSys models to show the unique features and benefits
of RecPS scoring in risk assessment and RecSys model unlearning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.18253v1">Countering Privacy Nihilism</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-24T09:52:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Severin Engelmann, Helen Nissenbaum</p>
    <p><b>Summary:</b> Of growing concern in privacy scholarship is artificial intelligence (AI), as
a powerful producer of inferences. Taken to its limits, AI may be presumed
capable of inferring "everything from everything," thereby making untenable any
normative scheme, including privacy theory and privacy regulation, which rests
on protecting privacy based on categories of data - sensitive versus
non-sensitive, private versus public. Discarding data categories as a normative
anchoring in privacy and data protection as a result of an unconditional
acceptance of AI's inferential capacities is what we call privacy nihilism. An
ethically reasoned response to AI inferences requires a sober consideration of
AI capabilities rather than issuing an epistemic carte blanche. We introduce
the notion of conceptual overfitting to expose how privacy nihilism turns a
blind eye toward flawed epistemic practices in AI development. Conceptual
overfitting refers to the adoption of norms of convenience that simplify the
development of AI models by forcing complex constructs to fit data that are
conceptually under-representative or even irrelevant. While conceptual
overfitting serves as a helpful device to counter normative suggestions
grounded in hyperbolic AI capability claims, AI inferences shake any privacy
regulation that hinges protections based on restrictions around data
categories. We propose moving away from privacy frameworks that focus solely on
data type, neglecting all other factors. Theories like contextual integrity
evaluate the normative value of privacy across several parameters, including
the type of data, the actors involved in sharing it, and the purposes for which
the information is used.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.18072v1">C-AAE: Compressively Anonymizing Autoencoders for Privacy-Preserving
  Activity Recognition in Healthcare Sensor Streams</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2025-07-24T03:55:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ryusei Fujimoto, Yugo Nakamura, Yutaka Arakawa</p>
    <p><b>Summary:</b> Wearable accelerometers and gyroscopes encode fine-grained behavioural
signatures that can be exploited to re-identify users, making privacy
protection essential for healthcare applications. We introduce C-AAE, a
compressive anonymizing autoencoder that marries an Anonymizing AutoEncoder
(AAE) with Adaptive Differential Pulse-Code Modulation (ADPCM). The AAE first
projects raw sensor windows into a latent space that retains activity-relevant
features while suppressing identity cues. ADPCM then differentially encodes
this latent stream, further masking residual identity information and shrinking
the bitrate. Experiments on the MotionSense and PAMAP2 datasets show that C-AAE
cuts user re-identification F1 scores by 10-15 percentage points relative to
AAE alone, while keeping activity-recognition F1 within 5 percentage points of
the unprotected baseline. ADPCM also reduces data volume by roughly 75 %,
easing transmission and storage overheads. These results demonstrate that C-AAE
offers a practical route to balancing privacy and utility in continuous,
sensor-based activity recognition for healthcare.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.18055v1">Privacy-Preserving Synthetic Review Generation with Diverse Writing
  Styles Using LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-07-24T03:12:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tevin Atwal, Chan Nam Tieu, Yefeng Yuan, Zhan Shi, Yuhong Liu, Liang Cheng</p>
    <p><b>Summary:</b> The increasing use of synthetic data generated by Large Language Models
(LLMs) presents both opportunities and challenges in data-driven applications.
While synthetic data provides a cost-effective, scalable alternative to
real-world data to facilitate model training, its diversity and privacy risks
remain underexplored. Focusing on text-based synthetic data, we propose a
comprehensive set of metrics to quantitatively assess the diversity (i.e.,
linguistic expression, sentiment, and user perspective), and privacy (i.e.,
re-identification risk and stylistic outliers) of synthetic datasets generated
by several state-of-the-art LLMs. Experiment results reveal significant
limitations in LLMs' capabilities in generating diverse and privacy-preserving
synthetic data. Guided by the evaluation results, a prompt-based approach is
proposed to enhance the diversity of synthetic reviews while preserving
reviewer privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.17516v1">Frequency Estimation of Correlated Multi-attribute Data under Local
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-23T13:52:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shafizur Rahman Seeam, Ye Zheng, Yidan Hu</p>
    <p><b>Summary:</b> Large-scale data collection, from national censuses to IoT-enabled smart
homes, routinely gathers dozens of attributes per individual. These
multi-attribute datasets are vital for analytics but pose significant privacy
risks. Local Differential Privacy (LDP) is a powerful tool to protect user data
privacy by allowing users to locally perturb their records before releasing to
an untrusted data aggregator. However, existing LDP mechanisms either split the
privacy budget across all attributes or treat each attribute independently,
ignoring natural inter-attribute correlations. This leads to excessive noise or
fragmented budgets, resulting in significant utility loss, particularly in
high-dimensional settings.
  To overcome these limitations, we propose Correlated Randomized Response
(Corr-RR), a novel LDP mechanism that leverages correlations among attributes
to substantially improve utility while maintaining rigorous LDP guarantees.
Corr-RR allocates the full privacy budget to perturb a single, randomly
selected attribute and reconstructs the remaining attributes using estimated
interattribute dependencies, without incurring additional privacy cost. To
enable this, Corr-RR operates in two phases: (1) a subset of users apply
standard LDP mechanisms to estimate correlations, and (2) each remaining user
perturbs one attribute and infers the others using the learned correlations. We
theoretically prove that Corr-RR satisfies $\epsilon$-LDP, and extensive
experiments on synthetic and real-world datasets demonstrate that Corr-RR
consistently outperforms state-of-the-art LDP mechanisms, particularly in
scenarios with many attributes and strong inter-attribute correlations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.21142v1">Privacy Artifact ConnecTor (PACT): Embedding Enterprise Artifacts for
  Compliance AI Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-23T08:00:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chenhao Fang, Yanqing Peng, Rajeev Rao, Matt Sarmiento, Wendy Summer, Arya Pudota, Alex Goncalves, Jordi Mola, Hervé Robert</p>
    <p><b>Summary:</b> Enterprise environments contain a heterogeneous, rapidly growing collection
of internal artifacts related to code, data, and many different tools. Critical
information for assessing privacy risk and ensuring regulatory compliance is
often embedded across these varied resources, each with their own arcane
discovery and extraction techniques. Therefore, large-scale privacy compliance
in adherence to governmental regulations requires systems to discern the
interconnected nature of diverse artifacts in a common, shared universe.
  We present Privacy Artifact ConnecT or (PACT), an embeddings-driven graph
that links millions of artifacts spanning multiple artifact types generated by
a variety of teams and projects. Powered by the state-of-the-art DRAGON
embedding model, PACT uses a contrastive learning objective with light
fine-tuning to link artifacts via their textual components such as raw
metadata, ownership specifics, and compliance context. Experimental results
show that PACT's fine-tuned model improves recall@1 from 18% to 53%, the query
match rate from 9.6% to 69.7% when paired with a baseline AI agent, and the
hitrate@1 from 25.7% to 44.9% for candidate selection in a standard recommender
system.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.17228v2">P3SL: Personalized Privacy-Preserving Split Learning on Heterogeneous
  Edge Devices</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-07-23T05:50:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wei Fan, JinYi Yoon, Xiaochang Li, Huajie Shao, Bo Ji</p>
    <p><b>Summary:</b> Split Learning (SL) is an emerging privacy-preserving machine learning
technique that enables resource constrained edge devices to participate in
model training by partitioning a model into client-side and server-side
sub-models. While SL reduces computational overhead on edge devices, it
encounters significant challenges in heterogeneous environments where devices
vary in computing resources, communication capabilities, environmental
conditions, and privacy requirements. Although recent studies have explored
heterogeneous SL frameworks that optimize split points for devices with varying
resource constraints, they often neglect personalized privacy requirements and
local model customization under varying environmental conditions. To address
these limitations, we propose P3SL, a Personalized Privacy-Preserving Split
Learning framework designed for heterogeneous, resource-constrained edge device
systems. The key contributions of this work are twofold. First, we design a
personalized sequential split learning pipeline that allows each client to
achieve customized privacy protection and maintain personalized local models
tailored to their computational resources, environmental conditions, and
privacy needs. Second, we adopt a bi-level optimization technique that empowers
clients to determine their own optimal personalized split points without
sharing private sensitive information (i.e., computational resources,
environmental conditions, privacy requirements) with the server. This approach
balances energy consumption and privacy leakage risks while maintaining high
model accuracy. We implement and evaluate P3SL on a testbed consisting of 7
devices including 4 Jetson Nano P3450 devices, 2 Raspberry Pis, and 1 laptop,
using diverse model architectures and datasets under varying environmental
conditions.</p>
  </details>
</div>



<h2>2025-08</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.13914v1">Development of a defacing algorithm to protect the privacy of head and
  neck cancer patients in publicly-accessible radiotherapy datasets</a></h3>
  
  <p><b>Published on:</b> 2025-08-19T15:14:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kayla O'Sullivan-Steben, Luc Galarneau, John Kildea</p>
    <p><b>Summary:</b> Introduction: The rise in public medical imaging datasets has raised concerns
about patient reidentification from head CT scans. However, existing defacing
algorithms often remove or distort Organs at Risk (OARs) and Planning Target
Volumes (PTVs) in head and neck cancer (HNC) patients, and ignore DICOM-RT
Structure Set and Dose data. Therefore, we developed and validated a novel
automated defacing algorithm that preserves these critical structures while
removing identifiable features from HNC CTs and DICOM-RT data.
  Methods: Eye contours were used as landmarks to automate the removal of CT
pixels above the inferior-most eye slice and anterior to the eye midpoint.
Pixels within PTVs were retained if they intersected with the removed region.
The body contour and dose map were reshaped to reflect the defaced image. We
validated our approach on 829 HNC CTs from 622 patients. Privacy protection was
evaluated by applying the FaceNet512 facial recognition algorithm before and
after defacing on 3D-rendered CT pairs from 70 patients. Research utility was
assessed by examining the impact of defacing on autocontouring performance
using LimbusAI and analyzing PTV locations relative to the defaced regions.
  Results: Before defacing, FaceNet512 matched 97% of patients' CTs. After
defacing, this rate dropped to 4%. LimbusAI effectively autocontoured organs in
the defaced CTs, with perfect Dice scores of 1 for OARs below the defaced
region, and excellent scores exceeding 0.95 for OARs on the same slices as the
crop. We found that 86% of PTVs were entirely below the cropped region, 9.1%
were on the same slice as the crop without overlap, and only 4.9% extended into
the cropped area.
  Conclusions: We developed a novel defacing algorithm that anonymizes HNC CT
scans and related DICOM-RT data while preserving essential structures, enabling
the sharing of HNC imaging datasets for Big Data and AI.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.13730v1">On the Security and Privacy of Federated Learning: A Survey with
  Attacks, Defenses, Frameworks, Applications, and Future Directions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-08-19T11:06:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Daniel M. Jimenez-Gutierrez, Yelizaveta Falkouskaya, Jose L. Hernandez-Ramos, Aris Anagnostopoulos, Ioannis Chatzigiannakis, Andrea Vitaletti</p>
    <p><b>Summary:</b> Federated Learning (FL) is an emerging distributed machine learning paradigm
enabling multiple clients to train a global model collaboratively without
sharing their raw data. While FL enhances data privacy by design, it remains
vulnerable to various security and privacy threats. This survey provides a
comprehensive overview of more than 200 papers regarding the state-of-the-art
attacks and defense mechanisms developed to address these challenges,
categorizing them into security-enhancing and privacy-preserving techniques.
Security-enhancing methods aim to improve FL robustness against malicious
behaviors such as byzantine attacks, poisoning, and Sybil attacks. At the same
time, privacy-preserving techniques focus on protecting sensitive data through
cryptographic approaches, differential privacy, and secure aggregation. We
critically analyze the strengths and limitations of existing methods, highlight
the trade-offs between privacy, security, and model performance, and discuss
the implications of non-IID data distributions on the effectiveness of these
defenses. Furthermore, we identify open research challenges and future
directions, including the need for scalable, adaptive, and energy-efficient
solutions operating in dynamic and heterogeneous FL environments. Our survey
aims to guide researchers and practitioners in developing robust and
privacy-preserving FL systems, fostering advancements safeguarding
collaborative learning frameworks' integrity and confidentiality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.13425v1">When Secure Aggregation Falls Short: Achieving Long-Term Privacy in
  Asynchronous Federated Learning for LEO Satellite Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-19T00:55:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohamed Elmahallawy, Tie Luo</p>
    <p><b>Summary:</b> Secure aggregation is a common technique in federated learning (FL) for
protecting data privacy from both curious internal entities (clients or server)
and external adversaries (eavesdroppers). However, in dynamic and
resource-constrained environments such as low Earth orbit (LEO) satellite
networks, traditional secure aggregation methods fall short in two aspects: (1)
they assume continuous client availability while LEO satellite visibility is
intermittent and irregular; (2) they consider privacy in each communication
round but have overlooked the possible privacy leakage through multiple rounds.
To address these limitations, we propose LTP-FLEO, an asynchronous FL framework
that preserves long-term privacy (LTP) for LEO satellite networks. LTP-FLEO
introduces (i) privacy-aware satellite partitioning, which groups satellites
based on their predictable visibility to the server and enforces joint
participation; (ii) model age balancing, which mitigates the adverse impact of
stale model updates; and (iii) fair global aggregation, which treats satellites
of different visibility durations in an equitable manner. Theoretical analysis
and empirical validation demonstrate that LTP-FLEO effectively safeguards both
model and data privacy across multi-round training, promotes fairness in line
with satellite contributions, accelerates global convergence, and achieves
competitive model accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.12832v2">Efficient and Verifiable Privacy-Preserving Convolutional Computation
  for CNN Inference with Untrusted Clouds</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-08-18T11:17:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jinyu Lu, Xinrong Sun, Yunting Tao, Tong Ji, Fanyu Kong, Guoqiang Yang</p>
    <p><b>Summary:</b> The widespread adoption of convolutional neural networks (CNNs) in
resource-constrained scenarios has driven the development of Machine Learning
as a Service (MLaaS) system. However, this approach is susceptible to privacy
leakage, as the data sent from the client to the untrusted cloud server often
contains sensitive information. Existing CNN privacy-preserving schemes, while
effective in ensuring data confidentiality through homomorphic encryption and
secret sharing, face efficiency bottlenecks, particularly in convolution
operations. In this paper, we propose a novel verifiable privacy-preserving
scheme tailored for CNN convolutional layers. Our scheme enables efficient
encryption and decryption, allowing resource-constrained clients to securely
offload computations to the untrusted cloud server. Additionally, we present a
verification mechanism capable of detecting the correctness of the results with
a success probability of at least $1-\frac{1}{\left|Z\right|}$. Extensive
experiments conducted on 10 datasets and various CNN models demonstrate that
our scheme achieves speedups ranging $26 \times$ ~ $\ 87\times$ compared to the
original plaintext model while maintaining accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.12539v1">The Hidden Cost of Correlation: Rethinking Privacy Leakage in Local
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2025-08-18T00:34:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sandaru Jayawardana, Sennur Ulukus, Ming Ding, Kanchana Thilakarathna</p>
    <p><b>Summary:</b> Local differential privacy (LDP) has emerged as a promising paradigm for
privacy-preserving data collection in distributed systems, where users
contribute multi-dimensional records with potentially correlated attributes.
Recent work has highlighted that correlation-induced privacy leakage (CPL)
plays a critical role in shaping the privacy-utility trade-off under LDP,
especially when correlations exist among attributes. Nevertheless, it remains
unclear to what extent the prevailing assumptions and proposed solutions are
valid and how significant CPL is in real-world data. To address this gap, we
first perform a comprehensive statistical analysis of five widely used LDP
mechanisms -- GRR, RAPPOR, OUE, OLH and Exponential mechanism -- to assess CPL
across four real-world datasets. We identify that many primary assumptions and
metrics in current approaches fall short of accurately characterising these
leakages. Moreover, current studies have been limited to a set of pure LDP
(i.e., {\delta = 0}) mechanisms. In response, we develop the first algorithmic
framework to theoretically quantify CPL for any general approximated LDP
(({\varepsilon},{\delta})-LDP) mechanism. We validate our theoretical results
against empirical statistical results and provide a theoretical explanation for
the observed statistical patterns. Finally, we propose two novel benchmarks to
validate correlation analysis algorithms and evaluate the utility vs CPL of LDP
mechanisms. Further, we demonstrate how these findings can be applied to
achieve an efficient privacy-utility trade-off in real-world data governance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.12158v1">LLM-as-a-Judge for Privacy Evaluation? Exploring the Alignment of Human
  and LLM Perceptions of Privacy in Textual Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-08-16T20:49:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stephen Meisenbacher, Alexandra Klymenko, Florian Matthes</p>
    <p><b>Summary:</b> Despite advances in the field of privacy-preserving Natural Language
Processing (NLP), a significant challenge remains the accurate evaluation of
privacy. As a potential solution, using LLMs as a privacy evaluator presents a
promising approach $\unicode{x2013}$ a strategy inspired by its success in
other subfields of NLP. In particular, the so-called $\textit{LLM-as-a-Judge}$
paradigm has achieved impressive results on a variety of natural language
evaluation tasks, demonstrating high agreement rates with human annotators.
Recognizing that privacy is both subjective and difficult to define, we
investigate whether LLM-as-a-Judge can also be leveraged to evaluate the
privacy sensitivity of textual data. Furthermore, we measure how closely LLM
evaluations align with human perceptions of privacy in text. Resulting from a
study involving 10 datasets, 13 LLMs, and 677 human survey participants, we
confirm that privacy is indeed a difficult concept to measure empirically,
exhibited by generally low inter-human agreement rates. Nevertheless, we find
that LLMs can accurately model a global human privacy perspective, and through
an analysis of human and LLM reasoning patterns, we discuss the merits and
limitations of LLM-as-a-Judge for privacy evaluation in textual data. Our
findings pave the way for exploring the feasibility of LLMs as privacy
evaluators, addressing a core challenge in solving pressing privacy issues with
innovative technical solutions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.12093v1">PP-STAT: An Efficient Privacy-Preserving Statistical Analysis Framework
  using Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-16T16:24:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hyunmin Choi</p>
    <p><b>Summary:</b> With the widespread adoption of cloud computing, the need for outsourcing
statistical analysis to third-party platforms is growing rapidly. However,
handling sensitive data such as medical records and financial information in
cloud environments raises serious privacy concerns. In this paper, we present
PP-STAT, a novel and efficient Homomorphic Encryption (HE)-based framework for
privacy-preserving statistical analysis. HE enables computations to be
performed directly on encrypted data without revealing the underlying
plaintext. PP-STAT supports advanced statistical measures, including Z-score
normalization, skewness, kurtosis, coefficient of variation, and Pearson
correlation coefficient, all computed securely over encrypted data. To improve
efficiency, PP-STAT introduces two key optimizations: (1) a Chebyshev-based
approximation strategy for initializing inverse square root operations, and (2)
a pre-normalization scaling technique that reduces multiplicative depth by
folding constant scaling factors into mean and variance computations. These
techniques significantly lower computational overhead and minimize the number
of expensive bootstrapping procedures. Our evaluation on real-world datasets
demonstrates that PP-STAT achieves high numerical accuracy, with mean relative
error (MRE) below 2.4x10-4. Notably, the encrypted Pearson correlation between
the smoker attribute and charges reaches 0.7873, with an MRE of 2.86x10-4.
These results confirm the practical utility of PP-STAT for secure and precise
statistical analysis in privacy-sensitive domains.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.11907v1">Deciphering the Interplay between Attack and Protection Complexity in
  Privacy-Preserving Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-16T04:39:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaojin Zhang, Mingcong Xu, Yiming Li, Wei Chen, Qiang Yang</p>
    <p><b>Summary:</b> Federated learning (FL) offers a promising paradigm for collaborative model
training while preserving data privacy. However, its susceptibility to gradient
inversion attacks poses a significant challenge, necessitating robust privacy
protection mechanisms. This paper introduces a novel theoretical framework to
decipher the intricate interplay between attack and protection complexities in
privacy-preserving FL. We formally define "Attack Complexity" as the minimum
computational and data resources an adversary requires to reconstruct private
data below a given error threshold, and "Protection Complexity" as the expected
distortion introduced by privacy mechanisms. Leveraging Maximum Bayesian
Privacy (MBP), we derive tight theoretical bounds for protection complexity,
demonstrating its scaling with model dimensionality and privacy budget.
Furthermore, we establish comprehensive bounds for attack complexity, revealing
its dependence on privacy leakage, gradient distortion, model dimension, and
the chosen privacy level. Our findings quantitatively illuminate the
fundamental trade-offs between privacy guarantees, system utility, and the
effort required for both attacking and defending. This framework provides
critical insights for designing more secure and efficient federated learning
systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.11797v1">AegisBlock: A Privacy-Preserving Medical Research Framework using
  Blockchain</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-08-15T20:43:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Calkin Garg, Omar Rios Cruz, Tessa Andersen, Gaby G. Dagher, Donald Winiecki, Min Long</p>
    <p><b>Summary:</b> Due to HIPAA and other privacy regulations, it is imperative to maintain
patient privacy while conducting research on patient health records. In this
paper, we propose AegisBlock, a patient-centric access controlled framework to
share medical records with researchers such that the anonymity of the patient
is maintained while ensuring the trustworthiness of the data provided to
researchers. AegisBlock allows for patients to provide access to their medical
data, verified by miners. A researcher submits a time-based range query to
request access to records from a certain patient, and upon patient approval,
access will be granted. Our experimental evaluation results show that
AegisBlock is scalable with respect to the number of patients and hospitals in
the system, and efficient with up to 50% of malicious miners.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.11742v1">Assessing User Privacy Leakage in Synthetic Packet Traces: An
  Attack-Grounded Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2025-08-15T17:54:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Minhao Jin, Hongyu He, Maria Apostolaki</p>
    <p><b>Summary:</b> Current synthetic traffic generators (SynNetGens) promise privacy but lack
comprehensive guarantees or empirical validation, even as their fidelity
steadily improves. We introduce the first attack-grounded benchmark for
assessing the privacy of SynNetGens directly from the traffic they produce. We
frame privacy as membership inference at the traffic-source level--a realistic
and actionable threat for data holders. To this end, we present TraceBleed, the
first attack that exploits behavioral fingerprints across flows using
contrastive learning and temporal chunking, outperforming prior membership
inference baselines by 172%. Our large-scale study across GAN-, diffusion-, and
GPT-based SynNetGens uncovers critical insights: (i) SynNetGens leak user-level
information; (ii) differential privacy either fails to stop these attacks or
severely degrades fidelity; and (iii) sharing more synthetic data amplifies
leakage by 59% on average. Finally, we introduce TracePatch, the first
SynNetGen-agnostic defense that combines adversarial ML with SMT constraints to
mitigate leakage while preserving fidelity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.11575v1">Activate Me!: Designing Efficient Activation Functions for
  Privacy-Preserving Machine Learning with Fully Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-15T16:31:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nges Brian Njungle, Michel A. Kinsy</p>
    <p><b>Summary:</b> The growing adoption of machine learning in sensitive areas such as
healthcare and defense introduces significant privacy and security challenges.
These domains demand robust data protection, as models depend on large volumes
of sensitive information for both training and inference. Fully Homomorphic
Encryption (FHE) presents a compelling solution by enabling computations
directly on encrypted data, maintaining confidentiality across the entire
machine learning workflow. However, FHE inherently supports only linear
operations, making it difficult to implement non-linear activation functions,
essential components of modern neural networks. This work focuses on designing,
implementing, and evaluating activation functions tailored for FHE-based
machine learning. We investigate two commonly used functions: the Square
function and Rectified Linear Unit (ReLU), using LeNet-5 and ResNet-20
architectures with the CKKS scheme from the OpenFHE library. For ReLU, we
assess two methods: a conventional low-degree polynomial approximation and a
novel scheme-switching technique that securely evaluates ReLU under FHE
constraints. Our findings show that the Square function performs well in
shallow networks like LeNet-5, achieving 99.4% accuracy with 128 seconds per
image. In contrast, deeper models like ResNet-20 benefit more from ReLU. The
polynomial approximation yields 83.8% accuracy with 1,145 seconds per image,
while our scheme-switching method improves accuracy to 89.8%, albeit with a
longer inference time of 1,697 seconds. These results underscore a critical
trade-off in FHE-based ML: faster activation functions often reduce accuracy,
whereas those preserving accuracy demand greater computational resources.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.11495v1">KV-Auditor: Auditing Local Differential Privacy for Correlated Key-Value
  Estimation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-15T14:17:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jingnan Xu, Leixia Wang, Xiaofeng Meng</p>
    <p><b>Summary:</b> To protect privacy for data-collection-based services, local differential
privacy (LDP) is widely adopted due to its rigorous theoretical bound on
privacy loss. However, mistakes in complex theoretical analysis or subtle
implementation errors may undermine its practical guarantee. To address this,
auditing is crucial to confirm that LDP protocols truly protect user data.
However, existing auditing methods, though, mainly target machine learning and
federated learning tasks based on centralized differentially privacy (DP), with
limited attention to LDP. Moreover, the few studies on LDP auditing focus
solely on simple frequency estimation task for discrete data, leaving
correlated key-value data - which requires both discrete frequency estimation
for keys and continuous mean estimation for values - unexplored.
  To bridge this gap, we propose KV-Auditor, a framework for auditing LDP-based
key-value estimation mechanisms by estimating their empirical privacy lower
bounds. Rather than traditional LDP auditing methods that relies on binary
output predictions, KV-Auditor estimates this lower bound by analyzing
unbounded output distributions, supporting continuous data. Specifically, we
classify state-of-the-art LDP key-value mechanisms into interactive and
non-interactive types. For non-interactive mechanisms, we propose horizontal
KV-Auditor for small domains with sufficient samples and vertical KV-Auditor
for large domains with limited samples. For interactive mechanisms, we design a
segmentation strategy to capture incremental privacy leakage across iterations.
Finally, we perform extensive experiments to validate the effectiveness of our
approach, offering insights for optimizing LDP-based key-value estimators.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.11419v1">Training-free Dimensionality Reduction via Feature Truncation: Enhancing
  Efficiency in Privacy-preserving Multi-Biometric Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-08-15T11:49:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Florian Bayer, Maximilian Russo, Christian Rathgeb</p>
    <p><b>Summary:</b> Biometric recognition is widely used, making the privacy and security of
extracted templates a critical concern. Biometric Template Protection schemes,
especially those utilizing Homomorphic Encryption, introduce significant
computational challenges due to increased workload. Recent advances in deep
neural networks have enabled state-of-the-art feature extraction for face,
fingerprint, and iris modalities. The ubiquity and affordability of biometric
sensors further facilitate multi-modal fusion, which can enhance security by
combining features from different modalities. This work investigates the
biometric performance of reduced multi-biometric template sizes. Experiments
are conducted on an in-house virtual multi-biometric database, derived from
DNN-extracted features for face, fingerprint, and iris, using the FRGC, MCYT,
and CASIA databases. The evaluated approaches are (i) explainable and
straightforward to implement under encryption, (ii) training-free, and (iii)
capable of generalization. Dimensionality reduction of feature vectors leads to
fewer operations in the Homomorphic Encryption (HE) domain, enabling more
efficient encrypted processing while maintaining biometric accuracy and
security at a level equivalent to or exceeding single-biometric recognition.
Our results demonstrate that, by fusing feature vectors from multiple
modalities, template size can be reduced by 67 % with no loss in Equal Error
Rate (EER) compared to the best-performing single modality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.11115v1">UWB-PostureGuard: A Privacy-Preserving RF Sensing System for Continuous
  Ergonomic Sitting Posture Monitoring</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> 
  <p><b>Published on:</b> 2025-08-14T23:40:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haotang Li, Zhenyu Qi, Sen He, Kebin Peng, Sheng Tan, Yili Ren, Tomas Cerny, Jiyue Zhao, Zi Wang</p>
    <p><b>Summary:</b> Improper sitting posture during prolonged computer use has become a
significant public health concern. Traditional posture monitoring solutions
face substantial barriers, including privacy concerns with camera-based systems
and user discomfort with wearable sensors. This paper presents
UWB-PostureGuard, a privacy-preserving ultra-wideband (UWB) sensing system that
advances mobile technologies for preventive health management through
continuous, contactless monitoring of ergonomic sitting posture. Our system
leverages commercial UWB devices, utilizing comprehensive feature engineering
to extract multiple ergonomic sitting posture features. We develop PoseGBDT to
effectively capture temporal dependencies in posture patterns, addressing
limitations of traditional frame-wise classification approaches. Extensive
real-world evaluation across 10 participants and 19 distinct postures
demonstrates exceptional performance, achieving 99.11% accuracy while
maintaining robustness against environmental variables such as clothing
thickness, additional devices, and furniture configurations. Our system
provides a scalable, privacy-preserving mobile health solution on existing
platforms for proactive ergonomic management, improving quality of life at low
costs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.10880v1">Searching for Privacy Risks in LLM Agents via Simulation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-08-14T17:49:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yanzhe Zhang, Diyi Yang</p>
    <p><b>Summary:</b> The widespread deployment of LLM-based agents is likely to introduce a
critical privacy threat: malicious agents that proactively engage others in
multi-turn interactions to extract sensitive information. These dynamic
dialogues enable adaptive attack strategies that can cause severe privacy
violations, yet their evolving nature makes it difficult to anticipate and
discover sophisticated vulnerabilities manually. To tackle this problem, we
present a search-based framework that alternates between improving attacker and
defender instructions by simulating privacy-critical agent interactions. Each
simulation involves three roles: data subject, data sender, and data recipient.
While the data subject's behavior is fixed, the attacker (data recipient)
attempts to extract sensitive information from the defender (data sender)
through persistent and interactive exchanges. To explore this interaction space
efficiently, our search algorithm employs LLMs as optimizers, using parallel
search with multiple threads and cross-thread propagation to analyze simulation
trajectories and iteratively propose new instructions. Through this process, we
find that attack strategies escalate from simple direct requests to
sophisticated multi-turn tactics such as impersonation and consent forgery,
while defenses advance from rule-based constraints to identity-verification
state machines. The discovered attacks and defenses transfer across diverse
scenarios and backbone models, demonstrating strong practical utility for
building privacy-aware agents.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.11716v1">Privacy-Aware Detection of Fake Identity Documents: Methodology,
  Benchmark, and Improved Detection Methods (FakeIDet2)</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> 
  <p><b>Published on:</b> 2025-08-14T17:30:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Javier Muñoz-Haro, Ruben Tolosana, Ruben Vera-Rodriguez, Aythami Morales, Julian Fierrez</p>
    <p><b>Summary:</b> Remote user verification in Internet-based applications is becoming
increasingly important nowadays. A popular scenario for it consists of
submitting a picture of the user's Identity Document (ID) to a service
platform, authenticating its veracity, and then granting access to the
requested digital service. An ID is well-suited to verify the identity of an
individual, since it is government issued, unique, and nontransferable.
However, with recent advances in Artificial Intelligence (AI), attackers can
surpass security measures in IDs and create very realistic physical and
synthetic fake IDs. Researchers are now trying to develop methods to detect an
ever-growing number of these AI-based fakes that are almost indistinguishable
from authentic (bona fide) IDs. In this counterattack effort, researchers are
faced with an important challenge: the difficulty in using real data to train
fake ID detectors. This real data scarcity for research and development is
originated by the sensitive nature of these documents, which are usually kept
private by the ID owners (the users) and the ID Holders (e.g., government,
police, bank, etc.). The main contributions of our study are: 1) We propose and
discuss a patch-based methodology to preserve privacy in fake ID detection
research. 2) We provide a new public database, FakeIDet2-db, comprising over
900K real/fake ID patches extracted from 2,000 ID images, acquired using
different smartphone sensors, illumination and height conditions, etc. In
addition, three physical attacks are considered: print, screen, and composite.
3) We present a new privacy-aware fake ID detection method, FakeIDet2. 4) We
release a standard reproducible benchmark that considers physical and synthetic
attacks from popular databases in the literature.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.10737v1">Privacy-enhancing Sclera Segmentation Benchmarking Competition: SSBC
  2025</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-08-14T15:16:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Matej Vitek, Darian Tomašević, Abhijit Das, Sabari Nathan, Gökhan Özbulak, Gözde Ayşe Tataroğlu Özbulak, Jean-Paul Calbimonte, André Anjos, Hariohm Hemant Bhatt, Dhruv Dhirendra Premani, Jay Chaudhari, Caiyong Wang, Jian Jiang, Chi Zhang, Qi Zhang, Iyyakutti Iyappan Ganapathi, Syed Sadaf Ali, Divya Velayudan, Maregu Assefa, Naoufel Werghi, Zachary A. Daniels, Leeon John, Ritesh Vyas, Jalil Nourmohammadi Khiarak, Taher Akbari Saeed, Mahsa Nasehi, Ali Kianfar, Mobina Pashazadeh Panahi, Geetanjali Sharma, Pushp Raj Panth, Raghavendra Ramachandra, Aditya Nigam, Umapada Pal, Peter Peer, Vitomir Štruc</p>
    <p><b>Summary:</b> This paper presents a summary of the 2025 Sclera Segmentation Benchmarking
Competition (SSBC), which focused on the development of privacy-preserving
sclera-segmentation models trained using synthetically generated ocular images.
The goal of the competition was to evaluate how well models trained on
synthetic data perform in comparison to those trained on real-world datasets.
The competition featured two tracks: $(i)$ one relying solely on synthetic data
for model development, and $(ii)$ one combining/mixing synthetic with (a
limited amount of) real-world data. A total of nine research groups submitted
diverse segmentation models, employing a variety of architectural designs,
including transformer-based solutions, lightweight models, and segmentation
networks guided by generative frameworks. Experiments were conducted across
three evaluation datasets containing both synthetic and real-world images,
collected under diverse conditions. Results show that models trained entirely
on synthetic data can achieve competitive performance, particularly when
dedicated training strategies are employed, as evidenced by the top performing
models that achieved $F_1$ scores of over $0.8$ in the synthetic data track.
Moreover, performance gains in the mixed track were often driven more by
methodological choices rather than by the inclusion of real data, highlighting
the promise of synthetic data for privacy-aware biometric development. The code
and data for the competition is available at:
https://github.com/dariant/SSBC_2025.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.10672v2">Hybrid Generative Fusion for Efficient and Privacy-Preserving Face
  Recognition Dataset Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-14T14:14:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Feiran Li, Qianqian Xu, Shilong Bao, Boyu Han, Zhiyong Yang, Qingming Huang</p>
    <p><b>Summary:</b> In this paper, we present our approach to the DataCV ICCV Challenge, which
centers on building a high-quality face dataset to train a face recognition
model. The constructed dataset must not contain identities overlapping with any
existing public face datasets. To handle this challenge, we begin with a
thorough cleaning of the baseline HSFace dataset, identifying and removing
mislabeled or inconsistent identities through a Mixture-of-Experts (MoE)
strategy combining face embedding clustering and GPT-4o-assisted verification.
We retain the largest consistent identity cluster and apply data augmentation
up to a fixed number of images per identity. To further diversify the dataset,
we generate synthetic identities using Stable Diffusion with prompt
engineering. As diffusion models are computationally intensive, we generate
only one reference image per identity and efficiently expand it using Vec2Face,
which rapidly produces 49 identity-consistent variants. This hybrid approach
fuses GAN-based and diffusion-based samples, enabling efficient construction of
a diverse and high-quality dataset. To address the high visual similarity among
synthetic identities, we adopt a curriculum learning strategy by placing them
early in the training schedule, allowing the model to progress from easier to
harder samples. Our final dataset contains 50 images per identity, and all
newly generated identities are checked with mainstream face datasets to ensure
no identity leakage. Our method achieves \textbf{1st place} in the competition,
and experimental results show that our dataset improves model performance
across 10K, 20K, and 100K identity scales. Code is available at
https://github.com/Ferry-Li/datacv_fr.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.10482v2">When Explainability Meets Privacy: An Investigation at the Intersection
  of Post-hoc Explainability and Differential Privacy in the Context of Natural
  Language Processing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-08-14T09:34:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mahdi Dhaini, Stephen Meisenbacher, Ege Erdogan, Florian Matthes, Gjergji Kasneci</p>
    <p><b>Summary:</b> In the study of trustworthy Natural Language Processing (NLP), a number of
important research fields have emerged, including that of explainability and
privacy. While research interest in both explainable and privacy-preserving NLP
has increased considerably in recent years, there remains a lack of
investigation at the intersection of the two. This leaves a considerable gap in
understanding of whether achieving both explainability and privacy is possible,
or whether the two are at odds with each other. In this work, we conduct an
empirical investigation into the privacy-explainability trade-off in the
context of NLP, guided by the popular overarching methods of Differential
Privacy (DP) and Post-hoc Explainability. Our findings include a view into the
intricate relationship between privacy and explainability, which is formed by a
number of factors, including the nature of the downstream task and choice of
the text privatization and explainability method. In this, we highlight the
potential for privacy and explainability to co-exist, and we summarize our
findings in a collection of practical recommendations for future work at this
important intersection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.10469v1">Enhanced Sparse Point Cloud Data Processing for Privacy-aware Human
  Action Recognition</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-14T09:09:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maimunatu Tunau, Vincent Gbouna Zakka, Zhuangzhuang Dai</p>
    <p><b>Summary:</b> Human Action Recognition (HAR) plays a crucial role in healthcare, fitness
tracking, and ambient assisted living technologies. While traditional vision
based HAR systems are effective, they pose privacy concerns. mmWave radar
sensors offer a privacy preserving alternative but present challenges due to
the sparse and noisy nature of their point cloud data. In the literature, three
primary data processing methods: Density-Based Spatial Clustering of
Applications with Noise (DBSCAN), the Hungarian Algorithm, and Kalman Filtering
have been widely used to improve the quality and continuity of radar data.
However, a comprehensive evaluation of these methods, both individually and in
combination, remains lacking. This paper addresses that gap by conducting a
detailed performance analysis of the three methods using the MiliPoint dataset.
We evaluate each method individually, all possible pairwise combinations, and
the combination of all three, assessing both recognition accuracy and
computational cost. Furthermore, we propose targeted enhancements to the
individual methods aimed at improving accuracy. Our results provide crucial
insights into the strengths and trade-offs of each method and their
integrations, guiding future work on mmWave based HAR systems</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.10373v1">Privacy-Preserving Approximate Nearest Neighbor Search on
  High-Dimensional Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2025-08-14T06:09:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yingfan Liu, Yandi Zhang, Jiadong Xie, Hui Li, Jeffrey Xu Yu, Jiangtao Cui</p>
    <p><b>Summary:</b> In the era of cloud computing and AI, data owners outsource ubiquitous
vectors to the cloud, which furnish approximate $k$-nearest neighbors
($k$-ANNS) services to users. To protect data privacy against the untrusted
server, privacy-preserving $k$-ANNS (PP-ANNS) on vectors has been a fundamental
and urgent problem. However, existing PP-ANNS solutions fall short of meeting
the requirements of data privacy, efficiency, accuracy, and minimal user
involvement concurrently. To tackle this challenge, we introduce a novel
solution that primarily executes PP-ANNS on a single cloud server to avoid the
heavy communication overhead between the cloud and the user. To ensure data
privacy, we introduce a novel encryption method named distance comparison
encryption, facilitating secure, efficient, and exact distance comparisons. To
optimize the trade-off between data privacy and search performance, we design a
privacy-preserving index that combines the state-of-the-art $k$-ANNS method
with an approximate distance computation method. Then, we devise a search
method using a filter-and-refine strategy based on the index. Moreover, we
provide the security analysis of our solution and conduct extensive experiments
to demonstrate its superiority over existing solutions. Based on our
experimental results, our method accelerates PP-ANNS by up to 3 orders of
magnitude compared to state-of-the-art methods, while not compromising the
accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.09882v1">Location Privacy-Enabled Beamforming in ISAC Scenarios</a></h3>
  
  <p><b>Published on:</b> 2025-08-13T15:32:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Umair Ali Khan, Lester Ho, Holger Claussen, Chinmoy Kundu</p>
    <p><b>Summary:</b> Integrated sensing and communication (ISAC) technology enables simultaneous
environmental perception and data transmission in wireless networks; however,
it also exposes user location to receivers. In this paper, we introduce a novel
beamforming framework guided by the proposed privacy metric direction of
arrival obfuscation ratio (DAOR) to protect transmitter location privacy in
ISAC scenarios. Unlike previous approaches, we do not suppress the
line-of-sight (LOS) component while reshaping the angular power distribution so
that a false direction appears dominant at the receiver. We derive closed-form
bounds on the feasible DAOR via generalized eigenvalue analysis and formulate
an achievable rate-maximization problem under the DAOR constraint. The
resulting problem is non-convex, which is efficiently solved using semidefinite
relaxation, eigenmode selection, and optimal power allocation. A suboptimal
design strategy is also proposed with reduced complexity. Numerical results
demonstrate that the proposed DAOR-based beamformer achieves a trade-off
between location privacy and communication rate without nullifying the LOS
path. Results also show that a suboptimal design achieves a near-optimal
communication rate with nearly an 85% reduction in computation time at a
signal-to-noise ratio (SNR) of 10 dB.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.09442v1">Shadow in the Cache: Unveiling and Mitigating Privacy Risks of KV-cache
  in LLM Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-08-13T02:48:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhifan Luo, Shuo Shao, Su Zhang, Lijing Zhou, Yuke Hu, Chenxu Zhao, Zhihao Liu, Zhan Qin</p>
    <p><b>Summary:</b> The Key-Value (KV) cache, which stores intermediate attention computations
(Key and Value pairs) to avoid redundant calculations, is a fundamental
mechanism for accelerating Large Language Model (LLM) inference. However, this
efficiency optimization introduces significant yet underexplored privacy risks.
This paper provides the first comprehensive analysis of these vulnerabilities,
demonstrating that an attacker can reconstruct sensitive user inputs directly
from the KV-cache. We design and implement three distinct attack vectors: a
direct Inversion Attack, a more broadly applicable and potent Collision Attack,
and a semantic-based Injection Attack. These methods demonstrate the
practicality and severity of KV-cache privacy leakage issues. To mitigate this,
we propose KV-Cloak, a novel, lightweight, and efficient defense mechanism.
KV-Cloak uses a reversible matrix-based obfuscation scheme, combined with
operator fusion, to secure the KV-cache. Our extensive experiments show that
KV-Cloak effectively thwarts all proposed attacks, reducing reconstruction
quality to random noise. Crucially, it achieves this robust security with
virtually no degradation in model accuracy and minimal performance overhead,
offering a practical solution for trustworthy LLM deployment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.09426v1">Security Analysis of ChatGPT: Threats and Privacy Risks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-13T02:03:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yushan Xiang, Zhongwen Li, Xiaoqi Li</p>
    <p><b>Summary:</b> As artificial intelligence technology continues to advance, chatbots are
becoming increasingly powerful. Among them, ChatGPT, launched by OpenAI, has
garnered widespread attention globally due to its powerful natural language
processing capabilities based on the GPT model, which enables it to engage in
natural conversations with users, understand various forms of linguistic
expressions, and generate useful information and suggestions. However, as its
application scope expands, user demand grows, and malicious attacks related to
it become increasingly frequent, the security threats and privacy risks faced
by ChatGPT are gradually coming to the forefront. In this paper, the security
of ChatGPT is mainly studied from two aspects, security threats and privacy
risks. The article systematically analyzes various types of vulnerabilities
involved in the above two types of problems and their causes. Briefly, we
discuss the controversies that ChatGPT may cause at the ethical and moral
levels. In addition, this paper reproduces several network attack and defense
test scenarios by simulating the attacker's perspective and methodology.
Simultaneously, it explores the feasibility of using ChatGPT for security
vulnerability detection and security tool generation from the defender's
perspective.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.09245v1">Beyond Blanket Masking: Examining Granularity for Privacy Protection in
  Images Captured by Blind and Low Vision Users</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-08-12T17:56:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jeffri Murrugarra-LLerena, Haoran Niu, K. Suzanne Barber, Hal Daumé III, Yang Trista Cao, Paola Cascante-Bonilla</p>
    <p><b>Summary:</b> As visual assistant systems powered by visual language models (VLMs) become
more prevalent, concerns over user privacy have grown, particularly for blind
and low vision users who may unknowingly capture personal private information
in their images. Existing privacy protection methods rely on coarse-grained
segmentation, which uniformly masks entire private objects, often at the cost
of usability. In this work, we propose FiGPriv, a fine-grained privacy
protection framework that selectively masks only high-risk private information
while preserving low-risk information. Our approach integrates fine-grained
segmentation with a data-driven risk scoring mechanism. We evaluate our
framework using the BIV-Priv-Seg dataset and show that FiG-Priv preserves +26%
of image content, enhancing the ability of VLMs to provide useful responses by
11% and identify the image content by 45%, while ensuring privacy protection.
Project Page: https://artcs1.github.io/VLMPrivacy/</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.09036v1">Can We Trust AI to Govern AI? Benchmarking LLM Performance on Privacy
  and AI Governance Exams</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-12T15:57:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zane Witherspoon, Thet Mon Aye, YingYing Hao</p>
    <p><b>Summary:</b> The rapid emergence of large language models (LLMs) has raised urgent
questions across the modern workforce about this new technology's strengths,
weaknesses, and capabilities. For privacy professionals, the question is
whether these AI systems can provide reliable support on regulatory compliance,
privacy program management, and AI governance. In this study, we evaluate ten
leading open and closed LLMs, including models from OpenAI, Anthropic, Google
DeepMind, Meta, and DeepSeek, by benchmarking their performance on
industry-standard certification exams: CIPP/US, CIPM, CIPT, and AIGP from the
International Association of Privacy Professionals (IAPP). Each model was
tested using official sample exams in a closed-book setting and compared to
IAPP's passing thresholds. Our findings show that several frontier models such
as Gemini 2.5 Pro and OpenAI's GPT-5 consistently achieve scores exceeding the
standards for professional human certification - demonstrating substantial
expertise in privacy law, technical controls, and AI governance. The results
highlight both the strengths and domain-specific gaps of current LLMs and offer
practical insights for privacy officers, compliance leads, and technologists
assessing the readiness of AI tools for high-stakes data governance roles. This
paper provides an overview for professionals navigating the intersection of AI
advancement and regulatory risk and establishes a machine benchmark based on
human-centric evaluations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.08785v1">Privacy-protected Retrieval-Augmented Generation for Knowledge Graph
  Question Answering</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-08-12T09:38:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yunfeng Ning, Mayi Xu, Jintao Wen, Qiankun Pi, Yuanyuan Zhu, Ming Zhong, Jiawei Jiang, Tieyun Qian</p>
    <p><b>Summary:</b> LLMs often suffer from hallucinations and outdated or incomplete knowledge.
RAG is proposed to address these issues by integrating external knowledge like
that in KGs into LLMs. However, leveraging private KGs in RAG systems poses
significant privacy risks due to the black-box nature of LLMs and potential
insecure data transmission, especially when using third-party LLM APIs lacking
transparency and control. In this paper, we investigate the privacy-protected
RAG scenario for the first time, where entities in KGs are anonymous for LLMs,
thus preventing them from accessing entity semantics. Due to the loss of
semantics of entities, previous RAG systems cannot retrieve question-relevant
knowledge from KGs by matching questions with the meaningless identifiers of
anonymous entities. To realize an effective RAG system in this scenario, two
key challenges must be addressed: (1) How can anonymous entities be converted
into retrievable information. (2) How to retrieve question-relevant anonymous
entities. Hence, we propose a novel ARoG framework including relation-centric
abstraction and structure-oriented abstraction strategies. For challenge (1),
the first strategy abstracts entities into high-level concepts by dynamically
capturing the semantics of their adjacent relations. It supplements meaningful
semantics which can further support the retrieval process. For challenge (2),
the second strategy transforms unstructured natural language questions into
structured abstract concept paths. These paths can be more effectively aligned
with the abstracted concepts in KGs, thereby improving retrieval performance.
To guide LLMs to effectively retrieve knowledge from KGs, the two strategies
strictly protect privacy from being exposed to LLMs. Experiments on three
datasets demonstrate that ARoG achieves strong performance and
privacy-robustness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.08749v2">Approximate DBSCAN under Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2025-08-12T08:55:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuan Qiu, Ke Yi</p>
    <p><b>Summary:</b> This paper revisits the DBSCAN problem under differential privacy (DP).
Existing DP-DBSCAN algorithms aim at publishing the cluster labels of the input
points. However, we show that both empirically and theoretically, this approach
cannot offer any utility in the published results. We therefore propose an
alternative definition of DP-DBSCAN based on the notion of spans. We argue that
publishing the spans actually better serves the purposes of visualization and
classification of DBSCAN. Then we present a linear-time DP-DBSCAN algorithm
achieving the sandwich quality guarantee in any constant dimensions, as well as
matching lower bounds on the approximation ratio. A key building block in our
algorithm is a linear-time algorithm for constructing a histogram under
pure-DP, which is of independent interest. Finally, we conducted experiments on
both synthetic and real-world datasets to verify the practical performance of
our DP-DBSCAN algorithm.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.09232v1">PETLP: A Privacy-by-Design Pipeline for Social Media Data in AI Research</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Multimedia-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2025-08-12T08:33:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nick Oh, Giorgos D. Vrakas, Siân J. M. Brooke, Sasha Morinière, Toju Duke</p>
    <p><b>Summary:</b> Social media data presents AI researchers with overlapping obligations under
the GDPR, copyright law, and platform terms -- yet existing frameworks fail to
integrate these regulatory domains, leaving researchers without unified
guidance. We introduce PETLP (Privacy-by-design Extract, Transform, Load, and
Present), a compliance framework that embeds legal safeguards directly into
extended ETL pipelines. Central to PETLP is treating Data Protection Impact
Assessments as living documents that evolve from pre-registration through
dissemination. Through systematic Reddit analysis, we demonstrate how
extraction rights fundamentally differ between qualifying research
organisations (who can invoke DSM Article 3 to override platform restrictions)
and commercial entities (bound by terms of service), whilst GDPR obligations
apply universally. We reveal why true anonymisation remains unachievable for
social media data and expose the legal gap between permitted dataset creation
and uncertain model distribution. By structuring compliance decisions into
practical workflows and simplifying institutional data management plans, PETLP
enables researchers to navigate regulatory complexity with confidence, bridging
the gap between legal requirements and research practice.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.08502v1">AirSignatureDB: Exploring In-Air Signature Biometrics in the Wild and
  its Privacy Concerns</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-08-11T22:24:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marta Robledo-Moreno, Ruben Vera-Rodriguez, Ruben Tolosana, Javier Ortega-Garcia, Andres Huergo, Julian Fierrez</p>
    <p><b>Summary:</b> Behavioral biometrics based on smartphone motion sensors are growing in
popularity for authentication purposes. In this study, AirSignatureDB is
presented: a new publicly accessible dataset of in-air signatures collected
from 108 participants under real-world conditions, using 83 different
smartphone models across four sessions. This dataset includes genuine samples
and skilled forgeries, enabling a comprehensive evaluation of system robustness
against realistic attack scenarios. Traditional and deep learning-based methods
for in-air signature verification are benchmarked, while analyzing the
influence of sensor modality and enrollment strategies. Beyond verification, a
first approach to reconstructing the three-dimensional trajectory of in-air
signatures from inertial sensor data alone is introduced. Using on-line
handwritten signatures as a reference, we demonstrate that the recovery of
accurate trajectories is feasible, challenging the long-held assumption that
in-air gestures are inherently traceless. Although this approach enables
forensic traceability, it also raises critical questions about the privacy
boundaries of behavioral biometrics. Our findings underscore the need for a
reevaluation of the privacy assumptions surrounding inertial sensor data, as
they can reveal user-specific information that had not previously been
considered in the design of in-air signature systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.08190v1">Differential Privacy for Regulatory Compliance in Cyberattack Detection
  on Critical Infrastructure Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-11T17:10:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Paritosh Ramanan, H. M. Mohaimanul Islam, Abhiram Reddy Alugula</p>
    <p><b>Summary:</b> Industrial control systems are a fundamental component of critical
infrastructure networks (CIN) such as gas, water and power. With the growing
risk of cyberattacks, regulatory compliance requirements are also increasing
for large scale critical infrastructure systems comprising multiple utility
stakeholders. The primary goal of regulators is to ensure overall system
stability with recourse to trustworthy stakeholder attack detection. However,
adhering to compliance requirements requires stakeholders to also disclose
sensor and control data to regulators raising privacy concerns. In this paper,
we present a cyberattack detection framework that utilizes differentially
private (DP) hypothesis tests geared towards enhancing regulatory confidence
while alleviating privacy concerns of CIN stakeholders. The hallmark of our
approach is a two phase privacy scheme that protects the privacy of covariance,
as well as the associated sensor driven test statistics computed as a means to
generate alarms. Theoretically, we show that our method induces a
misclassification error rate comparable to the non-DP cases while delivering
robust privacy guarantees. With the help of real-world datasets, we show the
reliability of our DP-detection outcomes for a wide variety of attack scenarios
for interdependent stakeholders.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.07960v1">VOIDFace: A Privacy-Preserving Multi-Network Face Recognition With
  Enhanced Security</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-08-11T13:15:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ajnas Muhammed, Iurri Medvedev, Nuno Gonçalves</p>
    <p><b>Summary:</b> Advancement of machine learning techniques, combined with the availability of
large-scale datasets, has significantly improved the accuracy and efficiency of
facial recognition. Modern facial recognition systems are trained using large
face datasets collected from diverse individuals or public repositories.
However, for training, these datasets are often replicated and stored in
multiple workstations, resulting in data replication, which complicates
database management and oversight. Currently, once a user submits their face
for dataset preparation, they lose control over how their data is used, raising
significant privacy and ethical concerns. This paper introduces VOIDFace, a
novel framework for facial recognition systems that addresses two major issues.
First, it eliminates the need of data replication and improves data control to
securely store training face data by using visual secret sharing. Second, it
proposes a patch-based multi-training network that uses this novel training
data storage mechanism to develop a robust, privacy-preserving facial
recognition system. By integrating these advancements, VOIDFace aims to improve
the privacy, security, and efficiency of facial recognition training, while
ensuring greater control over sensitive personal face data. VOIDFace also
enables users to exercise their Right-To-Be-Forgotten property to control their
personal data. Experimental evaluations on the VGGFace2 dataset show that
VOIDFace provides Right-To-Be-Forgotten, improved data control, security, and
privacy while maintaining competitive facial recognition performance. Code is
available at: https://github.com/ajnasmuhammed89/VOIDFace</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.07676v1">Multi-Hop Privacy Propagation for Differentially Private Federated
  Learning in Social Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB">
  <p><b>Published on:</b> 2025-08-11T06:53:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chenchen Lin, Xuehe Wang</p>
    <p><b>Summary:</b> Federated learning (FL) enables collaborative model training across
decentralized clients without sharing local data, thereby enhancing privacy and
facilitating collaboration among clients connected via social networks.
However, these social connections introduce privacy externalities: a client's
privacy loss depends not only on its privacy protection strategy but also on
the privacy decisions of others, propagated through the network via multi-hop
interactions. In this work, we propose a socially-aware privacy-preserving FL
mechanism that systematically quantifies indirect privacy leakage through a
multi-hop propagation model. We formulate the server-client interaction as a
two-stage Stackelberg game, where the server, as the leader, optimizes
incentive policies, and clients, as followers, strategically select their
privacy budgets, which determine their privacy-preserving levels by controlling
the magnitude of added noise. To mitigate information asymmetry in networked
privacy estimation, we introduce a mean-field estimator to approximate the
average external privacy risk. We theoretically prove the existence and
convergence of the fixed point of the mean-field estimator and derive
closed-form expressions for the Stackelberg Nash Equilibrium. Despite being
designed from a client-centric incentive perspective, our mechanism achieves
approximately-optimal social welfare, as revealed by Price of Anarchy (PoA)
analysis. Experiments on diverse datasets demonstrate that our approach
significantly improves client utilities and reduces server costs while
maintaining model performance, outperforming both Social-Agnostic (SA)
baselines and methods that account for social externalities.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.07672v1">Towards Aligning Personalized Conversational Recommendation Agents with
  Users' Privacy Preferences</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-08-11T06:51:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuning Zhang, Ying Ma, Jingruo Chen, Simin Li, Xin Yi, Hewu Li</p>
    <p><b>Summary:</b> The proliferation of AI agents, with their complex and context-dependent
actions, renders conventional privacy paradigms obsolete. This position paper
argues that the current model of privacy management, rooted in a user's
unilateral control over a passive tool, is inherently mismatched with the
dynamic and interactive nature of AI agents. We contend that ensuring effective
privacy protection necessitates that the agents proactively align with users'
privacy preferences instead of passively waiting for the user to control. To
ground this shift, and using personalized conversational recommendation agents
as a case, we propose a conceptual framework built on Contextual Integrity (CI)
theory and Privacy Calculus theory. This synthesis first reframes automatically
controlling users' privacy as an alignment problem, where AI agents initially
did not know users' preferences, and would learn their privacy preferences
through implicit or explicit feedback. Upon receiving the preference feedback,
the agents used alignment and Pareto optimization for aligning preferences and
balancing privacy and utility. We introduced formulations and instantiations,
potential applications, as well as five challenges.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.07667v1">1-2-3 Check: Enhancing Contextual Privacy in LLM via Multi-Agent
  Reasoning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-11T06:34:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenkai Li, Liwen Sun, Zhenxiang Guan, Xuhui Zhou, Maarten Sap</p>
    <p><b>Summary:</b> Addressing contextual privacy concerns remains challenging in interactive
settings where large language models (LLMs) process information from multiple
sources (e.g., summarizing meetings with private and public information). We
introduce a multi-agent framework that decomposes privacy reasoning into
specialized subtasks (extraction, classification), reducing the information
load on any single agent while enabling iterative validation and more reliable
adherence to contextual privacy norms. To understand how privacy errors emerge
and propagate, we conduct a systematic ablation over information-flow
topologies, revealing when and why upstream detection mistakes cascade into
downstream leakage. Experiments on the ConfAIde and PrivacyLens benchmark with
several open-source and closed-sourced LLMs demonstrate that our best
multi-agent configuration substantially reduces private information leakage
(\textbf{18\%} on ConfAIde and \textbf{19\%} on PrivacyLens with GPT-4o) while
preserving the fidelity of public content, outperforming single-agent
baselines. These results highlight the promise of principled information-flow
design in multi-agent systems for contextual privacy with LLMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.07664v1">Understanding Users' Privacy Perceptions Towards LLM's RAG-based Memory</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-08-11T06:26:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuning Zhang, Rongjun Ma, Ying Ma, Shixuan Li, Yiqun Xu, Xin Yi, Hewu Li</p>
    <p><b>Summary:</b> Large Language Models (LLMs) are increasingly integrating memory
functionalities to provide personalized and context-aware interactions.
However, user understanding, practices and expectations regarding these memory
systems are not yet well understood. This paper presents a thematic analysis of
semi-structured interviews with 18 users to explore their mental models of
LLM's Retrieval Augmented Generation (RAG)-based memory, current usage
practices, perceived benefits and drawbacks, privacy concerns and expectations
for future memory systems. Our findings reveal diverse and often incomplete
mental models of how memory operates. While users appreciate the potential for
enhanced personalization and efficiency, significant concerns exist regarding
privacy, control and the accuracy of remembered information. Users express a
desire for granular control over memory generation, management, usage and
updating, including clear mechanisms for reviewing, editing, deleting and
categorizing memories, as well as transparent insight into how memories and
inferred information are used. We discuss design implications for creating more
user-centric, transparent, and trustworthy LLM memory systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.07505v1">Enhancing Privacy in Decentralized Min-Max Optimization: A
  Differentially Private Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-08-10T23:24:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yueyang Quan, Chang Wang, Shengjie Zhai, Minghong Fang, Zhuqing Liu</p>
    <p><b>Summary:</b> Decentralized min-max optimization allows multi-agent systems to
collaboratively solve global min-max optimization problems by facilitating the
exchange of model updates among neighboring agents, eliminating the need for a
central server. However, sharing model updates in such systems carry a risk of
exposing sensitive data to inference attacks, raising significant privacy
concerns. To mitigate these privacy risks, differential privacy (DP) has become
a widely adopted technique for safeguarding individual data. Despite its
advantages, implementing DP in decentralized min-max optimization poses
challenges, as the added noise can hinder convergence, particularly in
non-convex scenarios with complex agent interactions in min-max optimization
problems. In this work, we propose an algorithm called DPMixSGD (Differential
Private Minmax Hybrid Stochastic Gradient Descent), a novel privacy-preserving
algorithm specifically designed for non-convex decentralized min-max
optimization. Our method builds on the state-of-the-art STORM-based algorithm,
one of the fastest decentralized min-max solutions. We rigorously prove that
the noise added to local gradients does not significantly compromise
convergence performance, and we provide theoretical bounds to ensure privacy
guarantees. To validate our theoretical findings, we conduct extensive
experiments across various tasks and models, demonstrating the effectiveness of
our approach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.07057v1">Rethinking Privacy Indicators in Extended Reality: Multimodal Design for
  Situationally Impaired Bystanders</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2025-08-09T17:48:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Syed Ibrahim Mustafa Shah Bukhari, Maha Sajid, Bo Ji, Brendan David-John</p>
    <p><b>Summary:</b> As Extended Reality (XR) devices become increasingly prevalent in everyday
settings, they raise significant privacy concerns for bystanders: individuals
in the vicinity of an XR device during its use, whom the device sensors may
accidentally capture. Current privacy indicators, such as small LEDs, often
presume that bystanders are attentive enough to interpret the privacy signals.
However, these cues can be easily overlooked when bystanders are distracted or
have limited vision. We define such individuals as situationally impaired
bystanders. This study explores XR privacy indicator designs that are effective
for situationally impaired bystanders. A focus group with eight participants
was conducted to design five novel privacy indicators. We evaluated these
designs through a user study with seven additional participants. Our results
show that visual-only indicators, typical in commercial XR devices, received
low ratings for perceived usefulness in impairment scenarios. In contrast,
multimodal indicators were preferred in privacy-sensitive scenarios with
situationally impaired bystanders. Ultimately, our results highlight the need
to move toward adaptable, multimodal, and situationally aware designs that
effectively support bystander privacy in everyday XR environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.07044v1">Balancing Privacy and Efficiency: Music Information Retrieval via
  Additive Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-09T17:00:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> William Zerong Wang, Dongfang Zhao</p>
    <p><b>Summary:</b> In the era of generative AI, ensuring the privacy of music data presents
unique challenges: unlike static artworks such as images, music data is
inherently temporal and multimodal, and it is sampled, transformed, and remixed
at an unprecedented scale. These characteristics make its core vector
embeddings, i.e, the numerical representations of the music, highly susceptible
to being learned, misused, or even stolen by models without accessing the
original audio files. Traditional methods like copyright licensing and digital
watermarking offer limited protection for these abstract mathematical
representations, thus necessitating a stronger, e.g., cryptographic, approach
to safeguarding the embeddings themselves. Standard encryption schemes, such as
AES, render data unintelligible for computation, making such searches
impossible. While Fully Homomorphic Encryption (FHE) provides a plausible
solution by allowing arbitrary computations on ciphertexts, its substantial
performance overhead remains impractical for large-scale vector similarity
searches. Given this trade-off, we propose a more practical approach using
Additive Homomorphic Encryption (AHE) for vector similarity search. The primary
contributions of this paper are threefold: we analyze threat models unique to
music information retrieval systems; we provide a theoretical analysis and
propose an efficient AHE-based solution through inner products of music
embeddings to deliver privacy-preserving similarity search; and finally, we
demonstrate the efficiency and practicality of the proposed approach through
empirical evaluation and comparison to FHE schemes on real-world MP3 files.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.06760v1">Understanding Privacy Norms Around LLM-Based Chatbots: A Contextual
  Integrity Perspective</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-08-09T00:22:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sarah Tran, Hongfan Lu, Isaac Slaughter, Bernease Herman, Aayushi Dangol, Yue Fu, Lufei Chen, Biniyam Gebreyohannes, Bill Howe, Alexis Hiniker, Nicholas Weber, Robert Wolfe</p>
    <p><b>Summary:</b> LLM-driven chatbots like ChatGPT have created large volumes of conversational
data, but little is known about how user privacy expectations are evolving with
this technology. We conduct a survey experiment with 300 US ChatGPT users to
understand emerging privacy norms for sharing chatbot data. Our findings reveal
a stark disconnect between user concerns and behavior: 82% of respondents rated
chatbot conversations as sensitive or highly sensitive - more than email or
social media posts - but nearly half reported discussing health topics and over
one-third discussed personal finances with ChatGPT. Participants expressed
strong privacy concerns (t(299) = 8.5, p < .01) and doubted their conversations
would remain private (t(299) = -6.9, p < .01). Despite this, respondents
uniformly rejected sharing personal data (search history, emails, device
access) for improved services, even in exchange for premium features worth
$200. To identify which factors influence appropriate chatbot data sharing, we
presented participants with factorial vignettes manipulating seven contextual
factors. Linear mixed models revealed that only the transmission factors such
as informed consent, data anonymization, or the removal of personally
identifiable information, significantly affected perceptions of appropriateness
and concern for data access. Surprisingly, contextual factors including the
recipient of the data (hospital vs. tech company), purpose (research vs.
advertising), type of content, and geographic location did not show significant
effects. Our results suggest that users apply consistent baseline privacy
expectations to chatbot data, prioritizing procedural safeguards over recipient
trustworthiness. This has important implications for emerging agentic AI
systems that assume user willingness to integrate personal data across
platforms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.06647v1">Privacy-Preserving Tabular Synthetic Data Generation Using TabularARGN</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-08-08T18:57:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Andrey Sidorenko, Paul Tiwald</p>
    <p><b>Summary:</b> Synthetic data generation has become essential for securely sharing and
analyzing sensitive data sets. Traditional anonymization techniques, however,
often fail to adequately preserve privacy. We introduce the Tabular
Auto-Regressive Generative Network (TabularARGN), a neural network architecture
specifically designed for generating high-quality synthetic tabular data. Using
a discretization-based auto-regressive approach, TabularARGN achieves high data
fidelity while remaining computationally efficient. We evaluate TabularARGN
against existing synthetic data generation methods, showing competitive results
in statistical similarity, machine learning utility, and detection robustness.
We further perform an in-depth privacy evaluation using systematic
membership-inference attacks, highlighting the robustness and effective
privacy-utility balance of our approach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.06301v1">FedMeNF: Privacy-Preserving Federated Meta-Learning for Neural Fields</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-08-08T13:24:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Junhyeog Yun, Minui Hong, Gunhee Kim</p>
    <p><b>Summary:</b> Neural fields provide a memory-efficient representation of data, which can
effectively handle diverse modalities and large-scale data. However, learning
to map neural fields often requires large amounts of training data and
computations, which can be limited to resource-constrained edge devices. One
approach to tackle this limitation is to leverage Federated Meta-Learning
(FML), but traditional FML approaches suffer from privacy leakage. To address
these issues, we introduce a novel FML approach called FedMeNF. FedMeNF
utilizes a new privacy-preserving loss function that regulates privacy leakage
in the local meta-optimization. This enables the local meta-learner to optimize
quickly and efficiently without retaining the client's private data. Our
experiments demonstrate that FedMeNF achieves fast optimization speed and
robust reconstruction performance, even with few-shot or non-IID data across
diverse data modalities, while preserving client data privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.06251v1">Synthetic Data Generation and Differential Privacy using Tensor
  Networks' Matrix Product States (MPS)</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2025-08-08T12:14:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alejandro Moreno R., Desale Fentaw, Samuel Palmer, Raúl Salles de Padua, Ninad Dixit, Samuel Mugel, Roman Orús, Manuel Radons, Josef Menter, Ali Abedi</p>
    <p><b>Summary:</b> Synthetic data generation is a key technique in modern artificial
intelligence, addressing data scarcity, privacy constraints, and the need for
diverse datasets in training robust models. In this work, we propose a method
for generating privacy-preserving high-quality synthetic tabular data using
Tensor Networks, specifically Matrix Product States (MPS). We benchmark the
MPS-based generative model against state-of-the-art models such as CTGAN, VAE,
and PrivBayes, focusing on both fidelity and privacy-preserving capabilities.
To ensure differential privacy (DP), we integrate noise injection and gradient
clipping during training, enabling privacy guarantees via R\'enyi Differential
Privacy accounting. Across multiple metrics analyzing data fidelity and
downstream machine learning task performance, our results show that MPS
outperforms classical models, particularly under strict privacy constraints.
This work highlights MPS as a promising tool for privacy-aware synthetic data
generation. By combining the expressive power of tensor network representations
with formal privacy mechanisms, the proposed approach offers an interpretable
and scalable alternative for secure data sharing. Its structured design
facilitates integration into sensitive domains where both data quality and
confidentiality are critical.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.06208v1">Graph Federated Learning for Personalized Privacy Recommendation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-08T10:44:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ce Na, Kai Yang, Dengzhao Fang, Yu Li, Jingtong Gao, Chengcheng Zhu, Jiale Zhang, Xiaobing Sun, Yi Chang</p>
    <p><b>Summary:</b> Federated recommendation systems (FedRecs) have gained significant attention
for providing privacy-preserving recommendation services. However, existing
FedRecs assume that all users have the same requirements for privacy
protection, i.e., they do not upload any data to the server. The approaches
overlook the potential to enhance the recommendation service by utilizing
publicly available user data. In real-world applications, users can choose to
be private or public. Private users' interaction data is not shared, while
public users' interaction data can be shared. Inspired by the issue, this paper
proposes a novel Graph Federated Learning for Personalized Privacy
Recommendation (GFed-PP) that adapts to different privacy requirements while
improving recommendation performance. GFed-PP incorporates the interaction data
of public users to build a user-item interaction graph, which is then used to
form a user relationship graph. A lightweight graph convolutional network (GCN)
is employed to learn each user's user-specific personalized item embedding. To
protect user privacy, each client learns the user embedding and the scoring
function locally. Additionally, GFed-PP achieves optimization of the federated
recommendation framework through the initialization of item embedding on
clients and the aggregation of the user relationship graph on the server.
Experimental results demonstrate that GFed-PP significantly outperforms
existing methods for five datasets, offering superior recommendation accuracy
without compromising privacy. This framework provides a practical solution for
accommodating varying privacy preferences in federated recommendation systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.06087v1">Adaptive Backtracking for Privacy Protection in Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2025-08-08T07:29:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhihao Yao, Yuxuan Gu, Xiachong Feng, Weitao Ma, Bo Li, Xiaocheng Feng</p>
    <p><b>Summary:</b> The preservation of privacy has emerged as a critical topic in the era of
artificial intelligence. However, current work focuses on user-oriented
privacy, overlooking severe enterprise data leakage risks exacerbated by the
Retrieval-Augmented Generation paradigm. To address this gap, our paper
introduces a novel objective: enterprise-oriented privacy concerns. Achieving
this objective requires overcoming two fundamental challenges: existing methods
such as data sanitization severely degrade model performance, and the field
lacks public datasets for evaluation. We address these challenges with several
solutions. (1) To prevent performance degradation, we propose ABack, a
training-free mechanism that leverages a Hidden State Model to pinpoint the
origin of a leakage intention and rewrite the output safely. (2) To solve the
lack of datasets, we construct PriGenQA, a new benchmark for enterprise privacy
scenarios in healthcare and finance. To ensure a rigorous evaluation, we move
beyond simple static attacks by developing a powerful adaptive attacker with
Group Relative Policy Optimization. Experiments show that against this superior
adversary, ABack improves the overall privacy utility score by up to 15\% over
strong baselines, avoiding the performance trade-offs of prior methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.09186v2">RL-MoE: An Image-Based Privacy Preserving Approach In Intelligent
  Transportation System</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-07T18:07:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abdolazim Rezaei, Mehdi Sookhak, Mahboobeh Haghparast</p>
    <p><b>Summary:</b> The proliferation of AI-powered cameras in Intelligent Transportation Systems
(ITS) creates a severe conflict between the need for rich visual data and the
right to privacy. Existing privacy-preserving methods, such as blurring or
encryption, are often insufficient due to creating an undesirable trade-off
where either privacy is compromised against advanced reconstruction attacks or
data utility is critically degraded. To resolve this challenge, we propose
RL-MoE, a novel framework that transforms sensitive visual data into
privacy-preserving textual descriptions, eliminating the need for direct image
transmission. RL-MoE uniquely combines a Mixture-of-Experts (MoE) architecture
for nuanced, multi-aspect scene decomposition with a Reinforcement Learning
(RL) agent that optimizes the generated text for a dual objective of semantic
accuracy and privacy preservation. Extensive experiments demonstrate that
RL-MoE provides superior privacy protection, reducing the success rate of
replay attacks to just 9.4\% on the CFP-FP dataset, while simultaneously
generating richer textual content than baseline methods. Our work provides a
practical and scalable solution for building trustworthy AI systems in
privacy-sensitive domains, paving the way for more secure smart city and
autonomous vehicle networks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.05518v1">Local Distance Query with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-07T15:48:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Weihong Sheng, Jiajun Chen, Bin Cai, Chunqiang Hu, Meng Han, Jiguo Yu</p>
    <p><b>Summary:</b> Differential Privacy (DP) is commonly employed to safeguard graph analysis or
publishing. Distance, a critical factor in graph analysis, is typically handled
using curator DP, where a trusted curator holds the complete neighbor lists of
all vertices and answers queries privately. However, in many real-world
scenarios, such a curator may not be present, posing a significant challenge
for implementing differentially private distance queries under Local
Differential Privacy (LDP). This paper proposes two approaches to address this
challenge. The first approach generates a synthetic graph by randomizing
responses and applies bitwise operations to reduce noise interference. However,
like other synthetic graph methods, this approach suffers from low utility. To
overcome this limitation, we propose a second approach, the first LDP method
specifically designed for distance queries, which captures the global graph
structure by continuously aggregating local distance vectors from neighboring
vertices. This process enables the accurate updating of global distances. We
demonstrate the effectiveness of our method through comprehensive theoretical
analysis and experimental evaluations on real-world datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.06577v1">Leveraging LLMs for Privacy-Aware Predictions in Participatory Budgeting</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-07T15:26:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Juan Zambrano, Clément Contet, Jairo Gudiño, Felipe Garrido-Lucero, Umberto Grandi, Cesar A Hidalgo</p>
    <p><b>Summary:</b> Participatory Budgeting (PB) empowers citizens to propose and vote on public
investment projects. Yet, despite its democratic potential, PB initiatives
often suffer from low participation rates, limiting their visibility and
perceived legitimacy. In this work, we aim to strengthen PB elections in two
key ways: by supporting project proposers in crafting better proposals, and by
helping PB organizers manage large volumes of submissions in a transparent
manner. We propose a privacy-preserving approach to predict which PB proposals
are likely to be funded, using only their textual descriptions and anonymous
historical voting records -- without relying on voter demographics or
personally identifiable information. We evaluate the performance of GPT 4 Turbo
in forecasting proposal outcomes across varying contextual scenarios, observing
that the LLM's prior knowledge needs to be complemented by past voting data to
obtain predictions reflecting real-world PB voting behavior. Our findings
highlight the potential of AI-driven tools to support PB processes by improving
transparency, planning efficiency, and civic engagement.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.05250v2">Privacy Disclosure of Similarity Rank in Speech and Language Processing</a></h3>
  
  <p><b>Published on:</b> 2025-08-07T10:40:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tom Bäckström, Mohammad Hassan Vali, My Nguyen, Silas Rech</p>
    <p><b>Summary:</b> Speaker, author, and other biometric identification applications often
compare a sample's similarity to a database of templates to determine the
identity. Given that data may be noisy and similarity measures can be
inaccurate, such a comparison may not reliably identify the true identity as
the most similar. Still, even the similarity rank based on an inaccurate
similarity measure can disclose private information about the true identity. We
propose a methodology for quantifying the privacy disclosure of such a
similarity rank by estimating its probability distribution. It is based on
determining the histogram of the similarity rank of the true speaker, or when
data is scarce, modeling the histogram with the beta-binomial distribution. We
express the disclosure in terms of entropy (bits), such that the disclosure
from independent features are additive. Our experiments demonstrate that all
tested speaker and author characterizations contain personally identifying
information (PII) that can aid in identification, with embeddings from speaker
recognition algorithms containing the most information, followed by phone
embeddings, linguistic embeddings, and fundamental frequency. Our initial
experiments show that the disclosure of PII increases with the length of test
samples, but it is bounded by the length of database templates. The provided
metric, similarity rank disclosure, provides a way to compare the disclosure of
PII between biometric features and merge them to aid identification. It can
thus aid in the holistic evaluation of threats to privacy in speech and other
biometric technologies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.04583v1">Measuring the Carbon Footprint of Cryptographic Privacy-Enhancing
  Technologies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-06T16:07:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marc Damie, Mihai Pop, Merijn Posthuma</p>
    <p><b>Summary:</b> Privacy-enhancing technologies (PETs) have attracted significant attention in
response to privacy regulations, driving the development of applications that
prioritize user data protection. At the same time, the information and
communication technology (ICT) sector faces growing pressure to reduce its
environmental footprint, particularly its carbon emissions. While numerous
studies have assessed the energy footprint of various ICT applications, the
environmental footprint of cryptographic PETs remains largely unexplored.
  Our work addresses this gap by proposing a standardized methodology for
evaluating the carbon footprint of PETs. To demonstrate this methodology, we
focus on PETs supporting client-server applications as they are the simplest to
deploy. In particular, we measure the energy consumption and carbon footprint
increase induced by five cryptographic PETs (compared to their non-private
equivalent): HTTPS web browsing, encrypted machine learning (ML) inference,
encrypted ML training, encrypted databases, and encrypted emails. Our findings
reveal significant variability in carbon footprint increases, ranging from a
twofold increase in HTTPS web browsing to a 100,000-fold increase in encrypted
ML.
  Our study provides essential data to help decision-makers assess
privacy-carbon trade-offs in such applications. Finally, we outline key
research directions for developing PETs that balance strong privacy protection
with environmental sustainability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.04542v1">Privacy Risk Predictions Based on Fundamental Understanding of Personal
  Data and an Evolving Threat Landscape</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B">
  <p><b>Published on:</b> 2025-08-06T15:30:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haoran Niu, K. Suzanne Barber</p>
    <p><b>Summary:</b> It is difficult for individuals and organizations to protect personal
information without a fundamental understanding of relative privacy risks. By
analyzing over 5,000 empirical identity theft and fraud cases, this research
identifies which types of personal data are exposed, how frequently exposures
occur, and what the consequences of those exposures are. We construct an
Identity Ecosystem graph--a foundational, graph-based model in which nodes
represent personally identifiable information (PII) attributes and edges
represent empirical disclosure relationships between them (e.g., the
probability that one PII attribute is exposed due to the exposure of another).
Leveraging this graph structure, we develop a privacy risk prediction framework
that uses graph theory and graph neural networks to estimate the likelihood of
further disclosures when certain PII attributes are compromised. The results
show that our approach effectively answers the core question: Can the
disclosure of a given identity attribute possibly lead to the disclosure of
another attribute?</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.04202v1">Unplug, Mute, Avoid: Investigating smart speaker users' privacy
  protection behaviours in Saudi Homes</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-08-06T08:32:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abdulrhman Alorini, Yufeng Wu, Abdullah Bin Sawad, Mukesh Prasad, A. Baki Kocaballi</p>
    <p><b>Summary:</b> Smart speakers are increasingly integrated into domestic life worldwide, yet
their privacy risks remain underexplored in non-Western cultural contexts. This
study investigates how Saudi Arabian users of smart speakers navigate privacy
concerns within collectivist, gendered, and often multigenerational households.
Using cultural probes followed by semi-structured interviews with 16
participants, we uncover everyday privacy-protective behaviours including
unplugging devices, muting microphones, and avoiding voice interactions
altogether. These practices are shaped not only by individual risk perceptions
but also by household norms, room configurations, and interpersonal dynamics.
We contribute empirical insights from an underrepresented region, theoretical
extensions to contextual integrity frameworks, and design directions for
culturally responsive voice interfaces. This work expands the global
conversation on smart speaker privacy and informs more inclusive HCI practices
in increasingly diverse smart home environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.03991v1">Galaxy: A Cognition-Centered Framework for Proactive,
  Privacy-Preserving, and Self-Evolving LLM Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-06T00:46:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chongyu Bao, Ruimin Dai, Yangbo Shen, Runyang Jian, Jinghan Zhang, Xiaolan Liu, Kunpeng Liu</p>
    <p><b>Summary:</b> Intelligent personal assistants (IPAs) such as Siri and Google Assistant are
designed to enhance human capabilities and perform tasks on behalf of users.
The emergence of LLM agents brings new opportunities for the development of
IPAs. While responsive capabilities have been widely studied, proactive
behaviors remain underexplored. Designing an IPA that is proactive,
privacy-preserving, and capable of self-evolution remains a significant
challenge. Designing such IPAs relies on the cognitive architecture of LLM
agents. This work proposes Cognition Forest, a semantic structure designed to
align cognitive modeling with system-level design. We unify cognitive
architecture and system design into a self-reinforcing loop instead of treating
them separately. Based on this principle, we present Galaxy, a framework that
supports multidimensional interactions and personalized capability generation.
Two cooperative agents are implemented based on Galaxy: KoRa, a
cognition-enhanced generative agent that supports both responsive and proactive
skills; and Kernel, a meta-cognition-based meta-agent that enables Galaxy's
self-evolution and privacy preservation. Experimental results show that Galaxy
outperforms multiple state-of-the-art benchmarks. Ablation studies and
real-world interaction cases validate the effectiveness of Galaxy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.03989v1">Dynamic User-controllable Privacy-preserving Few-shot Sensing Framework</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-06T00:44:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ajesh Koyatan Chathoth, Shuhao Yu, Stephen Lee</p>
    <p><b>Summary:</b> User-controllable privacy is important in modern sensing systems, as privacy
preferences can vary significantly from person to person and may evolve over
time. This is especially relevant in devices equipped with Inertial Measurement
Unit (IMU) sensors, such as smartphones and wearables, which continuously
collect rich time-series data that can inadvertently expose sensitive user
behaviors. While prior work has proposed privacy-preserving methods for sensor
data, most rely on static, predefined privacy labels or require large
quantities of private training data, limiting their adaptability and user
agency. In this work, we introduce PrivCLIP, a dynamic, user-controllable,
few-shot privacy-preserving sensing framework. PrivCLIP allows users to specify
and modify their privacy preferences by categorizing activities as sensitive
(black-listed), non-sensitive (white-listed), or neutral (gray-listed).
Leveraging a multimodal contrastive learning approach, PrivCLIP aligns IMU
sensor data with natural language activity descriptions in a shared embedding
space, enabling few-shot detection of sensitive activities. When a
privacy-sensitive activity is identified, the system uses a language-guided
activity sanitizer and a motion generation module (IMU-GPT) to transform the
original data into a privacy-compliant version that semantically resembles a
non-sensitive activity. We evaluate PrivCLIP on multiple human activity
recognition datasets and demonstrate that it significantly outperforms baseline
methods in terms of both privacy protection and data utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.03836v1">DP-NCB: Privacy Preserving Fair Bandits</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2025-08-05T18:34:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dhruv Sarkar, Nishant Pandey, Sayak Ray Chowdhury</p>
    <p><b>Summary:</b> Multi-armed bandit algorithms are fundamental tools for sequential
decision-making under uncertainty, with widespread applications across domains
such as clinical trials and personalized decision-making. As bandit algorithms
are increasingly deployed in these socially sensitive settings, it becomes
critical to protect user data privacy and ensure fair treatment across decision
rounds. While prior work has independently addressed privacy and fairness in
bandit settings, the question of whether both objectives can be achieved
simultaneously has remained largely open. Existing privacy-preserving bandit
algorithms typically optimize average regret, a utilitarian measure, whereas
fairness-aware approaches focus on minimizing Nash regret, which penalizes
inequitable reward distributions, but often disregard privacy concerns.
  To bridge this gap, we introduce Differentially Private Nash Confidence Bound
(DP-NCB)-a novel and unified algorithmic framework that simultaneously ensures
$\epsilon$-differential privacy and achieves order-optimal Nash regret,
matching known lower bounds up to logarithmic factors. The framework is
sufficiently general to operate under both global and local differential
privacy models, and is anytime, requiring no prior knowledge of the time
horizon. We support our theoretical guarantees with simulations on synthetic
bandit instances, showing that DP-NCB incurs substantially lower Nash regret
than state-of-the-art baselines. Our results offer a principled foundation for
designing bandit algorithms that are both privacy-preserving and fair, making
them suitable for high-stakes, socially impactful applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.03831v1">A Type System for Data Privacy Compliance in Active Object Languages</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Programming Languages-D91E36">
  <p><b>Published on:</b> 2025-08-05T18:21:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chinmayi Prabhu Baramashetru, Paola Giannini, Silvia Lizeth Tapia Tarifa, Olaf Owe</p>
    <p><b>Summary:</b> Data protection laws such as GDPR aim to give users unprecedented control
over their personal data. Compliance with these regulations requires
systematically considering information flow and interactions among entities
handling sensitive data. Privacy-by-design principles advocate embedding data
protection into system architectures as a default. However, translating these
abstract principles into concrete, explicit methods remains a significant
challenge. This paper addresses this gap by proposing a language-based approach
to privacy integration, combining static and runtime techniques. By employing
type checking and type inference in an active object language, the framework
enables the tracking of authorised data flows and the automatic generation of
constraints checked at runtime based on user consent. This ensures that
personal data is processed in compliance with GDPR constraints. The key
contribution of this work is a type system that gather the compliance checks
and the changes to users consent and integrates data privacy compliance
verification into system execution. The paper demonstrates the feasibility of
this approach through a soundness proof and several examples, illustrating how
the proposed language addresses common GDPR requirements, such as user consent,
purpose limitation, and data subject rights. This work advances the state of
the art in privacy-aware system design by offering a systematic and automated
method for integrating GDPR compliance into programming languages. This
capability has implications for building trustworthy systems in domains such as
healthcare or finance, where data privacy is crucial.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.03413v1">Smart Car Privacy: Survey of Attacks and Privacy Issues</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-05T12:59:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Akshay Madhav Deshmukh</p>
    <p><b>Summary:</b> Automobiles are becoming increasingly important in our day to day life.
Modern automobiles are highly computerized and hence potentially vulnerable to
attack. Providing many wireless connectivity for vehicles enables a bridge
between vehicles and their external environments. Such a connected vehicle
solution is expected to be the next frontier for automotive revolution and the
key to the evolution to next generation intelligent transportation systems.
Vehicular Ad hoc Networks (VANETs) are emerging mobile ad hoc network
technologies incorporating mobile routing protocols for inter-vehicle data
communications to support intelligent transportation systems. Thus security and
privacy are the major concerns in VANETs due to the mobility of the vehicles.
Thus designing security mechanisms to remove adversaries from the network
remarkably important in VANETs.
  This paper provides an overview of various vehicular network architectures.
The evolution of security in modern vehicles. Various security and privacy
attacks in VANETs with their defending mechanisms with examples and classify
these mechanisms. It also provides an overview of various privacy implication
that a vehicular network possess.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.03209v1">GeoShield: Safeguarding Geolocation Privacy from Vision-Language Models
  via Adversarial Perturbations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-05T08:37:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xinwei Liu, Xiaojun Jia, Yuan Xun, Simeng Qin, Xiaochun Cao</p>
    <p><b>Summary:</b> Vision-Language Models (VLMs) such as GPT-4o now demonstrate a remarkable
ability to infer users' locations from public shared images, posing a
substantial risk to geoprivacy. Although adversarial perturbations offer a
potential defense, current methods are ill-suited for this scenario: they often
perform poorly on high-resolution images and low perturbation budgets, and may
introduce irrelevant semantic content. To address these limitations, we propose
GeoShield, a novel adversarial framework designed for robust geoprivacy
protection in real-world scenarios. GeoShield comprises three key modules: a
feature disentanglement module that separates geographical and non-geographical
information, an exposure element identification module that pinpoints
geo-revealing regions within an image, and a scale-adaptive enhancement module
that jointly optimizes perturbations at both global and local levels to ensure
effectiveness across resolutions. Extensive experiments on challenging
benchmarks show that GeoShield consistently surpasses prior methods in
black-box settings, achieving strong privacy protection with minimal impact on
visual or semantic quality. To our knowledge, this work is the first to explore
adversarial perturbations for defending against geolocation inference by
advanced VLMs, providing a practical and effective solution to escalating
privacy concerns.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.03204v1">Current State in Privacy-Preserving Text Preprocessing for
  Domain-Agnostic NLP</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-08-05T08:26:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abhirup Sinha, Pritilata Saha, Tithi Saha</p>
    <p><b>Summary:</b> Privacy is a fundamental human right. Data privacy is protected by different
regulations, such as GDPR. However, modern large language models require a huge
amount of data to learn linguistic variations, and the data often contains
private information. Research has shown that it is possible to extract private
information from such language models. Thus, anonymizing such private and
sensitive information is of utmost importance. While complete anonymization may
not be possible, a number of different pre-processing approaches exist for
masking or pseudonymizing private information in textual data. This report
focuses on a few of such approaches for domain-agnostic NLP tasks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.03098v1">Privacy-Aware Decoding: Mitigating Privacy Leakage of Large Language
  Models in Retrieval-Augmented Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-08-05T05:22:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haoran Wang, Xiongxiao Xu, Baixiang Huang, Kai Shu</p>
    <p><b>Summary:</b> Retrieval-Augmented Generation (RAG) enhances the factual accuracy of large
language models (LLMs) by conditioning outputs on external knowledge sources.
However, when retrieval involves private or sensitive data, RAG systems are
susceptible to extraction attacks that can leak confidential information
through generated responses. We propose Privacy-Aware Decoding (PAD), a
lightweight, inference-time defense that adaptively injects calibrated Gaussian
noise into token logits during generation. PAD integrates confidence-based
screening to selectively protect high-risk tokens, efficient sensitivity
estimation to minimize unnecessary noise, and context-aware noise calibration
to balance privacy with generation quality. A \renyi Differential Privacy (RDP)
accountant rigorously tracks cumulative privacy loss, enabling explicit
per-response $(\varepsilon, \delta)$-DP guarantees for sensitive outputs.
Unlike prior approaches requiring retraining or corpus-level filtering, PAD is
model-agnostic and operates entirely at decoding time with minimal
computational overhead. Experiments on three real-world datasets demonstrate
that PAD substantially reduces private information leakage while preserving
response utility, outperforming existing retrieval- and post-processing-based
defenses. Our work takes an important step toward mitigating privacy risks in
RAG via decoding strategies, paving the way for universal and scalable privacy
solutions in sensitive domains. Our code is available:
https://github.com/wang2226/PAD.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.02551v1">PrivAR: Real-Time Privacy Protection for Location-Based Augmented
  Reality Applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-04T16:02:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shafizur Rahman Seeam, Ye Zheng, Zhengxiong Li, Yidan Hu</p>
    <p><b>Summary:</b> Location-based augmented reality (LB-AR) applications, such as Pok\'emon Go,
stream sub-second GPS updates to deliver responsive and immersive user
experiences. However, this high-frequency location reporting introduces serious
privacy risks. Protecting privacy in LB-AR is significantly more challenging
than in traditional location-based services (LBS), as it demands real-time
location protection with strong per-location and trajectory-level privacy
guaranteed while maintaining low latency and high quality of service (QoS).
Existing methods fail to meet these combined demands.
  To fill the gap, we present PrivAR, the first client-side privacy framework
for real-time LB-AR. PrivAR introduces two lightweight mechanisms: (i) Planar
Staircase Mechanism (PSM) which designs a staircase-shaped distribution to
generate noisy location with strong per-location privacy and low expected
error; and (ii) Thresholded Reporting with PSM (TR-PSM), a selective scheme
that releases a noisy location update only when a displacement exceeds a
private threshold, enabling many-to-one mappings for enhanced trace-level
privacy while preserving high QoS. We present theoretical analysis, extensive
experiments on two public datasets and our proprietary GeoTrace dataset, and
validate PrivAR on a Pok\'emon-Go-style prototype. Results show PrivAR improves
QoS (Gamescore) by up to 50%, while increasing attacker error by 1.8x over
baseline with an additional 0.06 milliseconds runtime overhead.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.02483v1">Revisiting the Privacy of Low-Frequency Speech Signals: Exploring
  Resampling Methods, Evaluation Scenarios, and Speaker Characteristics</a></h3>
  
  <p><b>Published on:</b> 2025-08-04T14:53:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jule Pohlhausen, Jörg Bitzer</p>
    <p><b>Summary:</b> While audio recordings in real life provide insights into social dynamics and
conversational behavior, they also raise concerns about the privacy of
personal, sensitive data. This article explores the effectiveness of
restricting recordings to low-frequency audio to protect spoken content. For
resampling the audio signals to different sampling rates, we compare the effect
of employing anti-aliasing filtering. Privacy enhancement is measured by an
increased word error rate of automatic speech recognition models. The impact on
utility performance is measured with voice activity detection models. Our
experimental results show that for clean recordings, models trained with a
sampling rate of up to 800 Hz transcribe the majority of words correctly. For
both models, we analyzed the impact of the speaker's sex and pitch, and we
demonstrated that missing anti-aliasing filters more strongly compromise speech
privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.02461v1">Experimental Evaluation of Post-Quantum Homomorphic Encryption for
  Privacy-Preserving V2X Communication</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-04T14:28:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abdullah Al Mamun, Kyle Yates, Antsa Rakotondrafara, Mashrur Chowdhury, Ryann Cartor, Shuhong Gao</p>
    <p><b>Summary:</b> Intelligent Transportation Systems (ITS) fundamentally rely on
vehicle-generated data for applications such as congestion monitoring and route
optimization, making the preservation of user privacy a critical challenge.
Homomorphic Encryption (HE) offers a promising solution by enabling computation
on encrypted data without revealing underlying content. This study presents the
first real-world experimental evaluation of three post-quantum secure HE
schemes, i.e., Brakerski-Fan-Vercauteren (BFV), Brakerski-Gentry-Vaikuntanathan
(BGV), and Cheon-Kim-Kim-Song (CKKS), for vehicular communication scenarios.
Two representative privacy-preserving use cases are considered: encrypted
vehicle counting and average speed aggregation. Experiments are conducted over
both Wi-Fi and Ethernet to assess performance under wireless and wired
vehicle-to-everything (V2X) settings. Results show that BFV and BGV are
suitable for latency-tolerant applications such as intersection monitoring and
regional traffic analysis, with total end-to-end latencies under 10 seconds.
While CKKS experiences higher overhead, it remains viable for periodic
encrypted aggregation of numerical data. The experimental results demonstrate
that HE can be feasibly deployed in ITS environments under 128-bit post-quantum
security, provided that scheme-specific latency constraints are considered.
This reinforces its potential to serve as a foundational tool for secure and
privacy-preserving V2X data processing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.02034v1">Protego: User-Centric Pose-Invariant Privacy Protection Against Face
  Recognition-Induced Digital Footprint Exposure</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-08-04T04:03:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ziling Wang, Shuya Yang, Jialin Lu, Ka-Ho Chow</p>
    <p><b>Summary:</b> Face recognition (FR) technologies are increasingly used to power large-scale
image retrieval systems, raising serious privacy concerns. Services like
Clearview AI and PimEyes allow anyone to upload a facial photo and retrieve a
large amount of online content associated with that person. This not only
enables identity inference but also exposes their digital footprint, such as
social media activity, private photos, and news reports, often without their
consent. In response to this emerging threat, we propose Protego, a
user-centric privacy protection method that safeguards facial images from such
retrieval-based privacy intrusions. Protego encapsulates a user's 3D facial
signatures into a pose-invariant 2D representation, which is dynamically
deformed into a natural-looking 3D mask tailored to the pose and expression of
any facial image of the user, and applied prior to online sharing. Motivated by
a critical limitation of existing methods, Protego amplifies the sensitivity of
FR models so that protected images cannot be matched even among themselves.
Experiments show that Protego significantly reduces retrieval accuracy across a
wide range of black-box FR models and performs at least 2x better than existing
methods. It also offers unprecedented visual coherence, particularly in video
settings where consistency and natural appearance are essential. Overall,
Protego contributes to the fight against the misuse of FR for mass surveillance
and unsolicited identity tracing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.01960v1">Non-Verbal Vocalisations and their Challenges: Emotion, Privacy,
  Sparseness, and Real Life</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">   
  <p><b>Published on:</b> 2025-08-03T23:59:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anton Batliner, Shahin Amiriparian, Björn W. Schuller</p>
    <p><b>Summary:</b> Non-Verbal Vocalisations (NVVs) are short `non-word' utterances without
proper linguistic (semantic) meaning but conveying connotations -- be this
emotions/affects or other paralinguistic information. We start this
contribution with a historic sketch: how they were addressed in psychology and
linguistics in the last two centuries, how they were neglected later on, and
how they came to the fore with the advent of emotion research. We then give an
overview of types of NVVs (formal aspects) and functions of NVVs, exemplified
with the typical NVV \textit{ah}. Interesting as they are, NVVs come, however,
with a bunch of challenges that should be accounted for: Privacy and general
ethical considerations prevent them of being recorded in real-life (private)
scenarios to a sufficient extent. Isolated, prompted (acted) exemplars do not
necessarily model NVVs in context; yet, this is the preferred strategy so far
when modelling NVVs, especially in AI. To overcome these problems, we argue in
favour of corpus-based approaches. This guarantees a more realistic modelling;
however, we are still faced with privacy and sparse data problems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.01898v1">Revenue Optimization in Wireless Video Caching Networks: A
  Privacy-Preserving Two-Stage Solution</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36"> 
  <p><b>Published on:</b> 2025-08-03T19:16:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yijing Zhang, Md-Ferdous Pervej, Andreas F. Molisch</p>
    <p><b>Summary:</b> Video caching can significantly improve delivery efficiency and enhance
quality of video streaming, which constitutes the majority of wireless
communication traffic. Due to limited cache size, caching strategies must be
designed to adapt to and dynamic user demand in order to maximize system
revenue. The system revenue depends on the benefits of delivering the requested
videos and costs for (a) transporting the files to the users and (b) cache
replacement. Since the cache content at any point in time impacts the
replacement costs in the future, demand predictions over multiple cache
placement slots become an important prerequisite for efficient cache planning.
Motivated by this, we introduce a novel two-stage privacy-preserving solution
for revenue optimization in wireless video caching networks. First, we train a
Transformer using privacy-preserving federated learning (FL) to predict
multi-slot future demands. Given that prediction results are never entirely
accurate, especially for longer horizons, we further combine global content
popularity with per-user prediction results to estimate the content demand
distribution. Then, in the second stage, we leverage these estimation results
to find caching strategies that maximize the long-term system revenue. This
latter problem takes on the form of a multi-stage knapsack problem, which we
then transform to a integer linear program. Our extensive simulation results
demonstrate that (i) our FL solution delivers nearly identical performance to
that of the ideal centralized solution and outperforms other existing caching
methods, and (ii) our novel revenue optimization approach provides deeper
system performance insights than traditional cache hit ratio (CHR)-based
optimization approaches.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.01798v1">A Survey on Privacy-Preserving Computing in the Automotive Domain</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-03T15:23:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nergiz Yuca, Nikolay Matyunin, Ektor Arzoglou, Nikolaos Athanasios Anagnostopoulos, Stefan Katzenbeisser</p>
    <p><b>Summary:</b> As vehicles become increasingly connected and autonomous, they accumulate and
manage various personal data, thereby presenting a key challenge in preserving
privacy during data sharing and processing. This survey reviews applications of
Secure Multi-Party Computation (MPC) and Homomorphic Encryption (HE) that
address these privacy concerns in the automotive domain. First, we identify the
scope of privacy-sensitive use cases for these technologies, by surveying
existing works that address privacy issues in different automotive contexts,
such as location-based services, mobility infrastructures, traffic management,
etc. Then, we review recent works that employ MPC and HE as solutions for these
use cases in detail. Our survey highlights the applicability of these
privacy-preserving technologies in the automotive context, while also
identifying challenges and gaps in the current research landscape. This work
aims to provide a clear and comprehensive overview of this emerging field and
to encourage further research in this domain.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.01749v1">Improving Noise Efficiency in Privacy-preserving Dataset Distillation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-03T13:15:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Runkai Zheng, Vishnu Asutosh Dasu, Yinong Oliver Wang, Haohan Wang, Fernando De la Torre</p>
    <p><b>Summary:</b> Modern machine learning models heavily rely on large datasets that often
include sensitive and private information, raising serious privacy concerns.
Differentially private (DP) data generation offers a solution by creating
synthetic datasets that limit the leakage of private information within a
predefined privacy budget; however, it requires a substantial amount of data to
achieve performance comparable to models trained on the original data. To
mitigate the significant expense incurred with synthetic data generation,
Dataset Distillation (DD) stands out for its remarkable training and storage
efficiency. This efficiency is particularly advantageous when integrated with
DP mechanisms, curating compact yet informative synthetic datasets without
compromising privacy. However, current state-of-the-art private DD methods
suffer from a synchronized sampling-optimization process and the dependency on
noisy training signals from randomly initialized networks. This results in the
inefficient utilization of private information due to the addition of excessive
noise. To address these issues, we introduce a novel framework that decouples
sampling from optimization for better convergence and improves signal quality
by mitigating the impact of DP noise through matching in an informative
subspace. On CIFAR-10, our method achieves a \textbf{10.0\%} improvement with
50 images per class and \textbf{8.3\%} increase with just \textbf{one-fifth}
the distilled set size of previous state-of-the-art methods, demonstrating
significant potential to advance privacy-preserving DD.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.01636v1">Privacy-Preserving Inference for Quantized BERT Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-03T07:52:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tianpei Lu, Bingsheng Zhang, Lekun Peng, Bowen Zheng, Lichun Li, Kui Ren</p>
    <p><b>Summary:</b> With the increasing deployment of generative machine learning models in
privacy-sensitive domains such as healthcare and personalized services,
ensuring secure inference has become a critical challenge. Secure multi-party
computation (MPC) enables privacy-preserving model inference but suffers from
high communication and computation overhead. The main bottleneck lies in the
expensive secure evaluation of floating-point operations. Quantization offers a
promising solution by converting floating-point operations into lower-precision
integer computations, significantly reducing overhead. However, existing
MPC-based quantized inference methods either rely on public quantization
parameters-posing privacy risks-or suffer from inefficiencies, particularly in
handling nonlinear functions such as activations and softmax. In this work, we
propose a fine-grained, layer-wise quantization scheme and support 1-bit weight
fully connected layers in a secure setting. We design a multi-input lookup
table protocol to evaluate softmax efficiently and securely. Furthermore, we
use dual secret sharing schemes and perform precision conversions via lookup
tables, eliminating truncation overhead entirely. Experimental evaluation on
BERT-base models demonstrates that our approach achieves up to $8\times$
speedup compared to Lu \emph{et al}. (NDSS 25), $9\times$ speedup compared to
Gupta \emph{et al}. (PETS 24) and $22 \times$ speedup compared to Knott
\emph{et al}. (NeurIPS 21).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.01587v1">Lifelong Person Re-identification via Privacy-Preserving Data Replay</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-08-03T05:00:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mingyu Wang, Haojie Liu, Zhiyong Li, Wei Jiang</p>
    <p><b>Summary:</b> Lifelong person re-identification (LReID) aims to incrementally accumulate
knowledge across a sequence of tasks under domain shifts. Recently,
replay-based methods have demonstrated strong effectiveness in LReID by
rehearsing past samples stored in an auxiliary memory. However, storing
historical exemplars raises concerns over data privacy. To avoid this,
exemplar-free approaches attempt to match the distribution of past data without
storing raw samples. Despite being privacy-friendly, these methods often suffer
from performance degradation due to the forgetting of specific past knowledge
representations. To this end, we propose to condense information from
sequential data into the pixel space in the replay memory, enabling
Privacy-Preserving Replay (Pr^2R). More specifically, by distilling the
training characteristics of multiple real images into a single image, the
condensed samples undergo pixel-level changes. This not only protects the
privacy of the original data but also makes the replay samples more
representative for sequential tasks. During the style replay phase, we align
the current domain to the previous one while simultaneously adapting the replay
samples to match the style of the current domain. This dual-alignment strategy
effectively mitigates both class-incremental challenges and forgetting caused
by domain shifts. Extensive experiments on multiple benchmarks show that the
proposed method significantly improves replay effectiveness while preserving
data privacy. Specifically, Pr^2R achieves 4% and 6% higher accuracy on
sequential tasks compared to the current state-of-the-art and other
replay-based methods, respectively.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.01207v1">Showcasing standards and approaches for cybersecurity, safety, and
  privacy issues in connected and autonomous vehicles</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-02T05:45:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ricardo M. Czekster</p>
    <p><b>Summary:</b> In the automotive industry there is a need to handle broad quality
deficiencies, eg, performance, maintainability, cybersecurity, safety, and
privacy, to mention a few. The idea is to prevent these issues from reaching
end-users, ie, road users and inadvertently, pedestrians, aiming to potentially
reduce accidents, and allow safe operation in dynamic attack surfaces, for the
benefit of a host of stakeholders. This paper aims to bridge cybersecurity,
safety, and privacy concerns in Connected and Autonomous Vehicles (CAV) with
respect to Risk Assessment (RA) and Threat Modelling (TM) altogether.
Practitioners know the vast literature on this topic given the sheer number of
recommendations, standards, best practices, and existing approaches, at times
impairing projects and fostering valuable and actionable threat analysis. In
this paper we collate key outcomes by highlighting latest standards and
approaches in RA and TM research to tackle complex attack surfaces as the ones
posed by automotive settings. We aim to provide the community with a list of
approaches to align expectations with stakeholders when deciding where and when
to focus threat related analysis in automotive solutions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.01140v1">Open Data Sharing in Clinical Research and Participants Privacy:
  Challenges and Opportunities in the Era of Artificial Intelligence</a></h3>
  
  <p><b>Published on:</b> 2025-08-02T01:46:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shahin Hallaj, Anna Heinke, Fritz Gerald P. Kalaw, Nayoon Gim, Marian Blazes, Julia Owen, Eamon Dysinger, Erik S. Benton, Benjamin A. Cordier, Nicholas G. Evans, Jennifer Li-Pook-Than, Michael P. Snyder, Camille Nebeker, Linda M. Zangwill, Sally L. Baxter, Shannon McWeeney, Cecilia S. Lee, Aaron Y. Lee, Bhavesh Patel</p>
    <p><b>Summary:</b> Sharing clinical research data is key for increasing the pace of medical
discoveries that improve human health. However, concern about study
participants' privacy, confidentiality, and safety is a major factor that
deters researchers from openly sharing clinical data, even after
deidentification. This concern is further heightened by the evolution of
artificial intelligence (AI) approaches that pose an ever-increasing threat to
the reidentification of study participants. Here, we discuss the challenges AI
approaches create that blur the lines between identifiable and non-identifiable
data. We present a concept of pseudo-reidentification, and discuss how these
challenges provide opportunities for rethinking open data sharing practices in
clinical research. We highlight the novel open data sharing approach we have
established as part of the Artificial Intelligence Ready and Exploratory Atlas
for Diabetes Insights project, one of the four Data Generation Projects funded
by the National Institutes of Health Common Fund's Bridge2AI Program.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.10918v1">Privacy Enhancement for Gaze Data Using a Noise-Infused Autoencoder</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-08-01T20:46:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Samantha Aziz, Oleg Komogortsev</p>
    <p><b>Summary:</b> We present a privacy-enhancing mechanism for gaze signals using a
latent-noise autoencoder that prevents users from being re-identified across
play sessions without their consent, while retaining the usability of the data
for benign tasks. We evaluate privacy-utility trade-offs across biometric
identification and gaze prediction tasks, showing that our approach
significantly reduces biometric identifiability with minimal utility
degradation. Unlike prior methods in this direction, our framework retains
physiologically plausible gaze patterns suitable for downstream use, which
produces favorable privacy-utility trade-off. This work advances privacy in
gaze-based systems by providing a usable and effective mechanism for protecting
sensitive gaze data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.00321v1">Evaluating the Efficacy of Large Language Models for Generating
  Fine-Grained Visual Privacy Policies in Homes</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-08-01T05:11:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuning Zhang, Ying Ma, Xin Yi, Hewu Li</p>
    <p><b>Summary:</b> The proliferation of visual sensors in smart home environments, particularly
through wearable devices like smart glasses, introduces profound privacy
challenges. Existing privacy controls are often static and coarse-grained,
failing to accommodate the dynamic and socially nuanced nature of home
environments. This paper investigates the viability of using Large Language
Models (LLMs) as the core of a dynamic and adaptive privacy policy engine. We
propose a conceptual framework where visual data is classified using a
multi-dimensional schema that considers data sensitivity, spatial context, and
social presence. An LLM then reasons over this contextual information to
enforce fine-grained privacy rules, such as selective object obfuscation, in
real-time. Through a comparative evaluation of state-of-the-art Vision Language
Models (including GPT-4o and the Qwen-VL series) in simulated home settings ,
our findings show the feasibility of this approach. The LLM-based engine
achieved a top machine-evaluated appropriateness score of 3.99 out of 5, and
the policies generated by the models received a top human-evaluated score of
4.00 out of 5.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.00287v2">Privacy-Preserving Driver Drowsiness Detection with Spatial
  Self-Attention and Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-08-01T03:12:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tran Viet Khoa, Do Hai Son, Mohammad Abu Alsheikh, Yibeltal F Alem, Dinh Thai Hoang</p>
    <p><b>Summary:</b> Driver drowsiness is one of the main causes of road accidents and is
recognized as a leading contributor to traffic-related fatalities. However,
detecting drowsiness accurately remains a challenging task, especially in
real-world settings where facial data from different individuals is
decentralized and highly diverse. In this paper, we propose a novel framework
for drowsiness detection that is designed to work effectively with
heterogeneous and decentralized data. Our approach develops a new Spatial
Self-Attention (SSA) mechanism integrated with a Long Short-Term Memory (LSTM)
network to better extract key facial features and improve detection
performance. To support federated learning, we employ a Gradient Similarity
Comparison (GSC) that selects the most relevant trained models from different
operators before aggregation. This improves the accuracy and robustness of the
global model while preserving user privacy. We also develop a customized tool
that automatically processes video data by extracting frames, detecting and
cropping faces, and applying data augmentation techniques such as rotation,
flipping, brightness adjustment, and zooming. Experimental results show that
our framework achieves a detection accuracy of 89.9% in the federated learning
settings, outperforming existing methods under various deployment scenarios.
The results demonstrate the effectiveness of our approach in handling
real-world data variability and highlight its potential for deployment in
intelligent transportation systems to enhance road safety through early and
reliable drowsiness detection.</p>
  </details>
</div>

