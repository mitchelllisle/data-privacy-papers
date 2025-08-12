
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


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.17199v1">Threshold-Protected Searchable Sharing: Privacy Preserving
  Aggregated-ANN Search for Collaborative RAG</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-23T04:45:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruoyang Rykie Guo</p>
    <p><b>Summary:</b> LLM-powered search services have driven data integration as a significant
trend. However, this trend's progress is fundamentally hindered, despite the
fact that combining individual knowledge can significantly improve the
relevance and quality of responses in specialized queries and make AI more
professional at providing services. Two key bottlenecks are private data
repositories' locality constraints and the need to maintain compatibility with
mainstream search techniques, particularly Hierarchical Navigable Small World
(HNSW) indexing for high-dimensional vector spaces. In this work, we develop a
secure and privacy-preserving aggregated approximate nearest neighbor search
(SP-A$^2$NN) with HNSW compatibility under a threshold-based searchable sharing
primitive. A sharable bitgraph structure is constructed and extended to support
searches and dynamical insertions over shared data without compromising the
underlying graph topology. The approach reduces the complexity of a search from
$O(n^2)$ to $O(n)$ compared to naive (undirected) graph-sharing approach when
organizing graphs in the identical HNSW manner.
  On the theoretical front, we explore a novel security analytical framework
that incorporates privacy analysis via reductions. The proposed
leakage-guessing proof system is built upon an entirely different interactive
game that is independent of existing coin-toss game design. Rather than being
purely theoretical, this system is rooted in existing proof systems but goes
beyond them to specifically address leakage concerns and standardize leakage
analysis -- one of the most critical security challenges with AI's rapid
development.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.21139v1">Learning-based Privacy-Preserving Graph Publishing Against Sensitive
  Link Inference Attacks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-23T04:19:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yucheng Wu, Yuncong Yang, Xiao Han, Leye Wang, Junjie Wu</p>
    <p><b>Summary:</b> Publishing graph data is widely desired to enable a variety of structural
analyses and downstream tasks. However, it also potentially poses severe
privacy leakage, as attackers may leverage the released graph data to launch
attacks and precisely infer private information such as the existence of hidden
sensitive links in the graph. Prior studies on privacy-preserving graph data
publishing relied on heuristic graph modification strategies and it is
difficult to determine the graph with the optimal privacy--utility trade-off
for publishing. In contrast, we propose the first privacy-preserving graph
structure learning framework against sensitive link inference attacks, named
PPGSL, which can automatically learn a graph with the optimal privacy--utility
trade-off. The PPGSL operates by first simulating a powerful surrogate attacker
conducting sensitive link attacks on a given graph. It then trains a
parameterized graph to defend against the simulated adversarial attacks while
maintaining the favorable utility of the original graph. To learn the
parameters of both parts of the PPGSL, we introduce a secure iterative training
protocol. It can enhance privacy preservation and ensure stable convergence
during the training process, as supported by the theoretical proof.
Additionally, we incorporate multiple acceleration techniques to improve the
efficiency of the PPGSL in handling large-scale graphs. The experimental
results confirm that the PPGSL achieves state-of-the-art privacy--utility
trade-off performance and effectively thwarts various sensitive link inference
attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.17180v1">A Privacy-Preserving Data Collection Method for Diversified Statistical
  Analysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-23T04:05:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hao Jiang, Quan Zhou, Dongdong Zhao, Shangshang Yang, Wenjian Luo, Xingyi Zhang</p>
    <p><b>Summary:</b> Data perturbation-based privacy-preserving methods have been widely adopted
in various scenarios due to their efficiency and the elimination of the need
for a trusted third party. However, these methods primarily focus on individual
statistical indicators, neglecting the overall quality of the collected data
from a distributional perspective. Consequently, they often fall short of
meeting the diverse statistical analysis requirements encountered in practical
data analysis. As a promising sensitive data perturbation method, negative
survey methods is able to complete the task of collecting sensitive information
distribution while protecting personal privacy. Yet, existing negative survey
methods are primarily designed for discrete sensitive information and are
inadequate for real-valued data distributions. To bridge this gap, this paper
proposes a novel real-value negative survey model, termed RVNS, for the first
time in the field of real-value sensitive information collection. The RVNS
model exempts users from the necessity of discretizing their data and only
requires them to sample a set of data from a range that deviates from their
actual sensitive details, thereby preserving the privacy of their genuine
information. Moreover, to accurately capture the distribution of sensitive
information, an optimization problem is formulated, and a novel approach is
employed to solve it. Rigorous theoretical analysis demonstrates that the RVNS
model conforms to the differential privacy model, ensuring robust privacy
preservation. Comprehensive experiments conducted on both synthetic and
real-world datasets further validate the efficacy of the proposed method.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.17066v1">Risk In Context: Benchmarking Privacy Leakage of Foundation Models in
  Synthetic Tabular Data Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2025-07-22T22:59:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jessup Byun, Xiaofeng Lin, Joshua Ward, Guang Cheng</p>
    <p><b>Summary:</b> Synthetic tabular data is essential for machine learning workflows,
especially for expanding small or imbalanced datasets and enabling
privacy-preserving data sharing. However, state-of-the-art generative models
(GANs, VAEs, diffusion models) rely on large datasets with thousands of
examples. In low-data settings, often the primary motivation for synthetic
data, these models can overfit, leak sensitive records, and require frequent
retraining. Recent work uses large pre-trained transformers to generate rows
via in-context learning (ICL), which needs only a few seed examples and no
parameter updates, avoiding retraining. But ICL repeats seed rows verbatim,
introducing a new privacy risk that has only been studied in text. The severity
of this risk in tabular synthesis-where a single row may identify a
person-remains unclear. We address this gap with the first benchmark of three
foundation models (GPT-4o-mini, LLaMA 3.3 70B, TabPFN v2) against four
baselines on 35 real-world tables from health, finance, and policy. We evaluate
statistical fidelity, downstream utility, and membership inference leakage.
Results show foundation models consistently have the highest privacy risk.
LLaMA 3.3 70B reaches up to 54 percentage points higher true-positive rate at
1% FPR than the safest baseline. GPT-4o-mini and TabPFN are also highly
vulnerable. We plot the privacy-utility frontier and show that CTGAN and
GPT-4o-mini offer better tradeoffs. A factorial study finds that three
zero-cost prompt tweaks-small batch size, low temperature, and using summary
statistics-can reduce worst-case AUC by 14 points and rare-class leakage by up
to 39 points while maintaining over 90% fidelity. Our benchmark offers a
practical guide for safer low-data synthesis with foundation models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.16788v1">AUTOPSY: A Framework for Tackling Privacy Challenges in the Automotive
  Industry</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-22T17:32:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sebastian Pape, Anis Bkakria, Maurice Heymann, Badreddine Chah, Abdeljalil Abbas-Turki, Sarah Syed-Winkler, Matthias Hiller, Reda Yaich</p>
    <p><b>Summary:</b> With the General Data Protection Regulation (GDPR) in place, all domains have
to ensure compliance with privacy legislation. However, compliance does not
necessarily result in a privacy-friendly system as for example getting users'
consent to process their data does not improve the privacy-friendliness of the
system. Therefore, the goal of the AUTOPSY project was to support the privacy
engineering process in the automotive domain by providing several building
blocks which technically improve the privacy-friendliness of modern, i.e.,
connected and (partially) automated vehicles. This paper presents the results
of the AUTOPSY project: a system model to identify relevant entities and
locations to apply privacy enhancing technologies (PETs); the privacy manager
aiming at more control of the data flow from the vehicle, a PET selection
approach based on GDPR principles, and an architectural framework for
automotive privacy. Furthermore, we built a demonstrator for location-based
services to evaluate the architectural framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.16391v2">Ironman: Accelerating Oblivious Transfer Extension for
  Privacy-Preserving AI with Near-Memory Processing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Hardware Architecture-04E762">
  <p><b>Published on:</b> 2025-07-22T09:35:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chenqi Lin, Kang Yang, Tianshi Xu, Ling Liang, Yufei Wang, Zhaohui Chen, Runsheng Wang, Mingyu Gao, Meng Li</p>
    <p><b>Summary:</b> With the wide application of machine learning (ML), privacy concerns arise
with user data as they may contain sensitive information. Privacy-preserving ML
(PPML) based on cryptographic primitives has emerged as a promising solution in
which an ML model is directly computed on the encrypted data to provide a
formal privacy guarantee. However, PPML frameworks heavily rely on the
oblivious transfer (OT) primitive to compute nonlinear functions. OT mainly
involves the computation of single-point correlated OT (SPCOT) and learning
parity with noise (LPN) operations. As OT is still computed extensively on
general-purpose CPUs, it becomes the latency bottleneck of modern PPML
frameworks.
  In this paper, we propose a novel OT accelerator, dubbed Ironman, to
significantly increase the efficiency of OT and the overall PPML framework. We
observe that SPCOT is computation-bounded, and thus propose a hardware-friendly
SPCOT algorithm with a customized accelerator to improve SPCOT computation
throughput. In contrast, LPN is memory-bandwidth-bounded due to irregular
memory access patterns. Hence, we further leverage the near-memory processing
(NMP) architecture equipped with memory-side cache and index sorting to improve
effective memory bandwidth. With extensive experiments, we demonstrate Ironman
achieves a 39.2-237.4 times improvement in OT throughput across different NMP
configurations compared to the full-thread CPU implementation. For different
PPML frameworks, Ironman demonstrates a 2.1-3.4 times reduction in end-to-end
latency for both CNN and Transformer models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.16372v1">Depth Gives a False Sense of Privacy: LLM Internal States Inversion</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-22T09:15:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tian Dong, Yan Meng, Shaofeng Li, Guoxing Chen, Zhen Liu, Haojin Zhu</p>
    <p><b>Summary:</b> Large Language Models (LLMs) are increasingly integrated into daily routines,
yet they raise significant privacy and safety concerns. Recent research
proposes collaborative inference, which outsources the early-layer inference to
ensure data locality, and introduces model safety auditing based on inner
neuron patterns. Both techniques expose the LLM's Internal States (ISs), which
are traditionally considered irreversible to inputs due to optimization
challenges and the highly abstract representations in deep layers. In this
work, we challenge this assumption by proposing four inversion attacks that
significantly improve the semantic similarity and token matching rate of
inverted inputs. Specifically, we first develop two white-box
optimization-based attacks tailored for low-depth and high-depth ISs. These
attacks avoid local minima convergence, a limitation observed in prior work,
through a two-phase inversion process. Then, we extend our optimization attack
under more practical black-box weight access by leveraging the transferability
between the source and the derived LLMs. Additionally, we introduce a
generation-based attack that treats inversion as a translation task, employing
an inversion model to reconstruct inputs. Extensive evaluation of short and
long prompts from medical consulting and coding assistance datasets and 6 LLMs
validates the effectiveness of our inversion attacks. Notably, a 4,112-token
long medical consulting prompt can be nearly perfectly inverted with 86.88 F1
token matching from the middle layer of Llama-3 model. Finally, we evaluate
four practical defenses that we found cannot perfectly prevent ISs inversion
and draw conclusions for future mitigation design.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.16872v1">CompLeak: Deep Learning Model Compression Exacerbates Privacy Leakage</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-22T08:02:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Na Li, Yansong Gao, Hongsheng Hu, Boyu Kuang, Anmin Fu</p>
    <p><b>Summary:</b> Model compression is crucial for minimizing memory storage and accelerating
inference in deep learning (DL) models, including recent foundation models like
large language models (LLMs). Users can access different compressed model
versions according to their resources and budget. However, while existing
compression operations primarily focus on optimizing the trade-off between
resource efficiency and model performance, the privacy risks introduced by
compression remain overlooked and insufficiently understood.
  In this work, through the lens of membership inference attack (MIA), we
propose CompLeak, the first privacy risk evaluation framework examining three
widely used compression configurations that are pruning, quantization, and
weight clustering supported by the commercial model compression framework of
Google's TensorFlow-Lite (TF-Lite) and Facebook's PyTorch Mobile. CompLeak has
three variants, given available access to the number of compressed models and
original model. CompLeakNR starts by adopting existing MIA methods to attack a
single compressed model, and identifies that different compressed models
influence members and non-members differently. When the original model and one
compressed model are available, CompLeakSR leverages the compressed model as a
reference to the original model and uncovers more privacy by combining meta
information (e.g., confidence vector) from both models. When multiple
compressed models are available with/without accessing the original model,
CompLeakMR innovatively exploits privacy leakage info from multiple compressed
versions to substantially signify the overall privacy leakage. We conduct
extensive experiments on seven diverse model architectures (from ResNet to
foundation models of BERT and GPT-2), and six image and textual benchmark
datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.16247v1">PRAC3 (Privacy, Reputation, Accountability, Consent, Credit,
  Compensation): Long Tailed Risks of Voice Actors in AI Data-Economy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-07-22T05:39:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tanusree Sharma, Yihao Zhou, Visar Berisha</p>
    <p><b>Summary:</b> Early large-scale audio datasets, such as LibriSpeech, were built with
hundreds of individual contributors whose voices were instrumental in the
development of speech technologies, including audiobooks and voice assistants.
Yet, a decade later, these same contributions have exposed voice actors to a
range of risks. While existing ethical frameworks emphasize Consent, Credit,
and Compensation (C3), they do not adequately address the emergent risks
involving vocal identities that are increasingly decoupled from context,
authorship, and control. Drawing on qualitative interviews with 20 professional
voice actors, this paper reveals how the synthetic replication of voice without
enforceable constraints exposes individuals to a range of threats. Beyond
reputational harm, such as re-purposing voice data in erotic content, offensive
political messaging, and meme culture, we document concerns about
accountability breakdowns when their voice is leveraged to clone voices that
are deployed in high-stakes scenarios such as financial fraud, misinformation
campaigns, or impersonation scams. In such cases, actors face social and legal
fallout without recourse, while very few of them have a legal representative or
union protection. To make sense of these shifting dynamics, we introduce the
PRAC3 framework, an expansion of C3 that foregrounds Privacy, Reputation,
Accountability, Consent, Credit, and Compensation as interdependent pillars of
data used in the synthetic voice economy. This framework captures how privacy
risks are amplified through non-consensual training, how reputational harm
arises from decontextualized deployment, and how accountability can be
reimagined AI Data ecosystems. We argue that voice, as both a biometric
identifier and creative labor, demands governance models that restore creator
agency, ensure traceability, and establish enforceable boundaries for ethical
reuse.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.16134v1">DP2Guard: A Lightweight and Byzantine-Robust Privacy-Preserving
  Federated Learning Scheme for Industrial IoT</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-07-22T01:06:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Baofu Han, Bing Li, Yining Qi, Raja Jurdak, Kaibin Huang, Chau Yuen</p>
    <p><b>Summary:</b> Privacy-Preserving Federated Learning (PPFL) has emerged as a secure
distributed Machine Learning (ML) paradigm that aggregates locally trained
gradients without exposing raw data. To defend against model poisoning threats,
several robustness-enhanced PPFL schemes have been proposed by integrating
anomaly detection. Nevertheless, they still face two major challenges: (1) the
reliance on heavyweight encryption techniques results in substantial
communication and computation overhead; and (2) single-strategy defense
mechanisms often fail to provide sufficient robustness against adaptive
adversaries. To overcome these challenges, we propose DP2Guard, a lightweight
PPFL framework that enhances both privacy and robustness. DP2Guard leverages a
lightweight gradient masking mechanism to replace costly cryptographic
operations while ensuring the privacy of local gradients. A hybrid defense
strategy is proposed, which extracts gradient features using singular value
decomposition and cosine similarity, and applies a clustering algorithm to
effectively identify malicious gradients. Additionally, DP2Guard adopts a trust
score-based adaptive aggregation scheme that adjusts client weights according
to historical behavior, while blockchain records aggregated results and trust
scores to ensure tamper-proof and auditable training. Extensive experiments
conducted on two public datasets demonstrate that DP2Guard effectively defends
against four advanced poisoning attacks while ensuring privacy with reduced
communication and computation costs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.16124v1">Benchmarking LLM Privacy Recognition for Social Robot Decision Making</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-22T00:36:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dakota Sullivan, Shirley Zhang, Jennica Li, Heather Kirkorian, Bilge Mutlu, Kassem Fawaz</p>
    <p><b>Summary:</b> Social robots are embodied agents that interact with people while following
human communication norms. These robots interact using verbal and non-verbal
cues, and share the physical environments of people. While social robots have
previously utilized rule-based systems or probabilistic models for user
interaction, the rapid evolution of large language models (LLMs) presents new
opportunities to develop LLM-empowered social robots for enhanced human-robot
interaction. To fully realize these capabilities, however, robots need to
collect data such as audio, fine-grained images, video, and locations. As a
result, LLMs often process sensitive personal information, particularly within
home environments. Given the tension between utility and privacy risks,
evaluating how current LLMs manage sensitive data is critical. Specifically, we
aim to explore the extent to which out-of-the-box LLMs are privacy-aware in the
context of household social robots. In this study, we present a set of
privacy-relevant scenarios crafted through the lens of Contextual Integrity
(CI). We first survey users' privacy preferences regarding in-home social robot
behaviors and then examine how their privacy orientation affects their choices
of these behaviors (N = 450). We then provide the same set of scenarios and
questions to state-of-the-art LLMs (N = 10) and find that the agreement between
humans and LLMs is low. To further investigate the capabilities of LLMs as a
potential privacy controller, we implement four additional prompting strategies
and compare their results. Finally, we discuss the implications and potential
of AI privacy awareness in human-robot interaction.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.16034v1">Improved Semantic Segmentation from Ultra-Low-Resolution RGB Images
  Applied to Privacy-Preserving Object-Goal Navigation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-07-21T19:53:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xuying Huang, Sicong Pan, Olga Zatsarynna, Juergen Gall, Maren Bennewitz</p>
    <p><b>Summary:</b> User privacy in mobile robotics has become a critical concern. Existing
methods typically prioritize either the performance of downstream robotic tasks
or privacy protection, with the latter often constraining the effectiveness of
task execution. To jointly address both objectives, we study semantic-based
robot navigation in an ultra-low-resolution setting to preserve visual privacy.
A key challenge in such scenarios is recovering semantic segmentation from
ultra-low-resolution RGB images. In this work, we introduce a novel fully
joint-learning method that integrates an agglomerative feature extractor and a
segmentation-aware discriminator to solve ultra-low-resolution semantic
segmentation, thereby enabling privacy-preserving, semantic object-goal
navigation. Our method outperforms different baselines on ultra-low-resolution
semantic segmentation and our improved segmentation results increase the
success rate of the semantic object-goal navigation in a real-world
privacy-constrained scenario.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.15997v1">"We Need a Standard": Toward an Expert-Informed Privacy Label for
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> 
  <p><b>Published on:</b> 2025-07-21T18:32:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Onyinye Dibia, Mengyi Lu, Prianka Bhattacharjee, Joseph P. Near, Yuanyuan Feng</p>
    <p><b>Summary:</b> The increasing adoption of differential privacy (DP) leads to public-facing
DP deployments by both government agencies and companies. However, real-world
DP deployments often do not fully disclose their privacy guarantees, which vary
greatly between deployments. Failure to disclose certain DP parameters can lead
to misunderstandings about the strength of the privacy guarantee, undermining
the trust in DP. In this work, we seek to inform future standards for
communicating the privacy guarantees of DP deployments. Based on
semi-structured interviews with 12 DP experts, we identify important DP
parameters necessary to comprehensively communicate DP guarantees, and describe
why and how they should be disclosed. Based on expert recommendations, we
design an initial privacy label for DP to comprehensively communicate privacy
guarantees in a standardized format.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.15836v1">Optimizing Canaries for Privacy Auditing with Metagradient Descent</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-21T17:47:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Matteo Boglioni, Terrance Liu, Andrew Ilyas, Zhiwei Steven Wu</p>
    <p><b>Summary:</b> In this work we study black-box privacy auditing, where the goal is to lower
bound the privacy parameter of a differentially private learning algorithm
using only the algorithm's outputs (i.e., final trained model). For DP-SGD (the
most successful method for training differentially private deep learning
models), the canonical approach auditing uses membership inference-an auditor
comes with a small set of special "canary" examples, inserts a random subset of
them into the training set, and then tries to discern which of their canaries
were included in the training set (typically via a membership inference
attack). The auditor's success rate then provides a lower bound on the privacy
parameters of the learning algorithm. Our main contribution is a method for
optimizing the auditor's canary set to improve privacy auditing, leveraging
recent work on metagradient optimization. Our empirical evaluation demonstrates
that by using such optimized canaries, we can improve empirical lower bounds
for differentially private image classification models by over 2x in certain
instances. Furthermore, we demonstrate that our method is transferable and
efficient: canaries optimized for non-private SGD with a small model
architecture remain effective when auditing larger models trained with DP-SGD.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.15460v3">Privacy-Preserving Multimodal News Recommendation through Federated
  Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-07-21T10:14:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mehdi Khalaj, Shahrzad Golestani Najafabadi, Julita Vassileva</p>
    <p><b>Summary:</b> Personalized News Recommendation systems (PNR) have emerged as a solution to
information overload by predicting and suggesting news items tailored to
individual user interests. However, traditional PNR systems face several
challenges, including an overreliance on textual content, common neglect of
short-term user interests, and significant privacy concerns due to centralized
data storage. This paper addresses these issues by introducing a novel
multimodal federated learning-based approach for news recommendation. First, it
integrates both textual and visual features of news items using a multimodal
model, enabling a more comprehensive representation of content. Second, it
employs a time-aware model that balances users' long-term and short-term
interests through multi-head self-attention networks, improving recommendation
accuracy. Finally, to enhance privacy, a federated learning framework is
implemented, enabling collaborative model training without sharing user data.
The framework divides the recommendation model into a large server-maintained
news model and a lightweight user model shared between the server and clients.
The client requests news representations (vectors) and a user model from the
central server, then computes gradients with user local data, and finally sends
their locally computed gradients to the server for aggregation. The central
server aggregates gradients to update the global user model and news model. The
updated news model is further used to infer news representation by the server.
To further safeguard user privacy, a secure aggregation algorithm based on
Shamir's secret sharing is employed. Experiments on a real-world news dataset
demonstrate strong performance compared to existing systems, representing a
significant advancement in privacy-preserving personalized news recommendation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.15124v1">Comprehensive Privacy Risk Assessment in Social Networks Using User
  Attributes Social Graphs and Text Analysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B">
  <p><b>Published on:</b> 2025-07-20T21:18:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Md Jahangir Alam, Ismail Hossain, Sai Puppala, Sajedul Talukder</p>
    <p><b>Summary:</b> The rise of social networking platforms has amplified privacy threats as
users increasingly share sensitive information across profiles, content, and
social connections. We present a Comprehensive Privacy Risk Scoring (CPRS)
framework that quantifies privacy risk by integrating user attributes, social
graph structures, and user-generated content. Our framework computes risk
scores across these dimensions using sensitivity, visibility, structural
similarity, and entity-level analysis, then aggregates them into a unified risk
score. We validate CPRS on two real-world datasets: the SNAP Facebook Ego
Network (4,039 users) and the Koo microblogging dataset (1M posts, 1M
comments). The average CPRS is 0.478 with equal weighting, rising to 0.501 in
graph-sensitive scenarios. Component-wise, graph-based risks (mean 0.52)
surpass content (0.48) and profile attributes (0.45). High-risk attributes
include email, date of birth, and mobile number. Our user study with 100
participants shows 85% rated the dashboard as clear and actionable, confirming
CPRS's practical utility. This work enables personalized privacy risk insights
and contributes a holistic, scalable methodology for privacy management. Future
directions include incorporating temporal dynamics and multimodal content for
broader applicability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.14985v1">Metaverse Security and Privacy Research: A Systematic Review</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-07-20T14:42:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Argianto Rahartomo, Leonel Merino, Mohammad Ghafari</p>
    <p><b>Summary:</b> The rapid growth of metaverse technologies, including virtual worlds,
augmented reality, and lifelogging, has accelerated their adoption across
diverse domains. This rise exposes users to significant new security and
privacy challenges due to sociotechnical complexity, pervasive connectivity,
and extensive user data collection in immersive environments. We present a
systematic review of the literature published between 2013 and 2024, offering a
comprehensive analysis of how the research community has addressed
metaverse-related security and privacy issues over the past decade. We organize
the studies by method, examined the security and privacy properties, immersive
components, and evaluation strategies. Our investigation reveals a sharp
increase in research activity in the last five years, a strong focus on
practical and user-centered approaches, and a predominant use of benchmarking,
human experimentation, and qualitative methods. Authentication and
unobservability are the most frequently studied properties. However, critical
gaps remain in areas such as policy compliance, accessibility,
interoperability, and back-end infrastructure security. We emphasize the
intertwined technical complexity and human factors of the metaverse and call
for integrated, interdisciplinary approaches to securing inclusive and
trustworthy immersive environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.14853v2">A Privacy-Centric Approach: Scalable and Secure Federated Learning
  Enabled by Hybrid Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-07-20T07:46:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Khoa Nguyen, Tanveer Khan, Hossein Abdinasibfar, Antonis Michalas</p>
    <p><b>Summary:</b> Federated Learning (FL) enables collaborative model training without sharing
raw data, making it a promising approach for privacy-sensitive domains. Despite
its potential, FL faces significant challenges, particularly in terms of
communication overhead and data privacy. Privacy-preserving Techniques (PPTs)
such as Homomorphic Encryption (HE) have been used to mitigate these concerns.
However, these techniques introduce substantial computational and communication
costs, limiting their practical deployment. In this work, we explore how Hybrid
Homomorphic Encryption (HHE), a cryptographic protocol that combines symmetric
encryption with HE, can be effectively integrated with FL to address both
communication and privacy challenges, paving the way for scalable and secure
decentralized learning system.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.03703v1">Privacy Risks of LLM-Empowered Recommender Systems: An Inversion Attack
  Perspective</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-20T05:03:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yubo Wang, Min Tang, Nuo Shen, Shujie Cui, Weiqing Wang</p>
    <p><b>Summary:</b> The large language model (LLM) powered recommendation paradigm has been
proposed to address the limitations of traditional recommender systems, which
often struggle to handle cold start users or items with new IDs. Despite its
effectiveness, this study uncovers that LLM empowered recommender systems are
vulnerable to reconstruction attacks that can expose both system and user
privacy. To examine this threat, we present the first systematic study on
inversion attacks targeting LLM empowered recommender systems, where
adversaries attempt to reconstruct original prompts that contain personal
preferences, interaction histories, and demographic attributes by exploiting
the output logits of recommendation models. We reproduce the vec2text framework
and optimize it using our proposed method called Similarity Guided Refinement,
enabling more accurate reconstruction of textual prompts from model generated
logits. Extensive experiments across two domains (movies and books) and two
representative LLM based recommendation models demonstrate that our method
achieves high fidelity reconstructions. Specifically, we can recover nearly 65
percent of the user interacted items and correctly infer age and gender in 87
percent of the cases. The experiments also reveal that privacy leakage is
largely insensitive to the victim model's performance but highly dependent on
domain consistency and prompt complexity. These findings expose critical
privacy vulnerabilities in LLM empowered recommender systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.14713v1">Privacy-Preserving Drone Navigation Through Homomorphic Encryption for
  Collision Avoidance</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2025-07-19T18:16:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Allan Luedeman, Nicholas Baum, Andrew Quijano, Kemal Akkaya</p>
    <p><b>Summary:</b> As drones increasingly deliver packages in neighborhoods, concerns about
collisions arise. One solution is to share flight paths within a specific zip
code, but this compromises business privacy by revealing delivery routes. For
example, it could disclose which stores send packages to certain addresses. To
avoid exposing path information, we propose using homomorphic encryption-based
comparison to compute path intersections. This allows drones to identify
potential collisions without revealing path and destination details, allowing
them to adjust altitude to avoid crashes. We implemented and tested our
approach on resource-limited virtual machines to mimic the computational power
of drones. Our results demonstrate that our method is significantly faster and
requires less network communication compared to a garbled circuit-based
approach. We also provide a security analysis of the approach against potential
attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.14629v1">VMask: Tunable Label Privacy Protection for Vertical Federated Learning
  via Layer Masking</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-19T13:51:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Juntao Tan, Lan Zhang, Zhonghao Hu, Kai Yang, Peng Ran, Bo Li</p>
    <p><b>Summary:</b> Though vertical federated learning (VFL) is generally considered to be
privacy-preserving, recent studies have shown that VFL system is vulnerable to
label inference attacks originating from various attack surfaces. Among these
attacks, the model completion (MC) attack is currently the most powerful one.
Existing defense methods against it either sacrifice model accuracy or incur
impractical computational overhead. In this paper, we propose VMask, a novel
label privacy protection framework designed to defend against MC attack from
the perspective of layer masking. Our key insight is to disrupt the strong
correlation between input data and intermediate outputs by applying the secret
sharing (SS) technique to mask layer parameters in the attacker's model. We
devise a strategy for selecting critical layers to mask, reducing the overhead
that would arise from naively applying SS to the entire model. Moreover, VMask
is the first framework to offer a tunable privacy budget to defenders, allowing
for flexible control over the levels of label privacy according to actual
requirements. We built a VFL system, implemented VMask on it, and extensively
evaluated it using five model architectures and 13 datasets with different
modalities, comparing it to 12 other defense methods. The results demonstrate
that VMask achieves the best privacy-utility trade-off, successfully thwarting
the MC attack (reducing the label inference accuracy to a random guessing
level) while preserving model performance (e.g., in Transformer-based model,
the averaged drop of VFL model accuracy is only 0.09%). VMask's runtime is up
to 60,846 times faster than cryptography-based methods, and it only marginally
exceeds that of standard VFL by 1.8 times in a large Transformer-based model,
which is generally acceptable.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.14519v1">Towards Efficient Privacy-Preserving Machine Learning: A Systematic
  Review from Protocol, Model, and System Perspectives</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-19T07:45:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenxuan Zeng, Tianshi Xu, Yi Chen, Yifan Zhou, Mingzhe Zhang, Jin Tan, Cheng Hong, Meng Li</p>
    <p><b>Summary:</b> Privacy-preserving machine learning (PPML) based on cryptographic protocols
has emerged as a promising paradigm to protect user data privacy in cloud-based
machine learning services. While it achieves formal privacy protection, PPML
often incurs significant efficiency and scalability costs due to orders of
magnitude overhead compared to the plaintext counterpart. Therefore, there has
been a considerable focus on mitigating the efficiency gap for PPML. In this
survey, we provide a comprehensive and systematic review of recent PPML studies
with a focus on cross-level optimizations. Specifically, we categorize existing
papers into protocol level, model level, and system level, and review progress
at each level. We also provide qualitative and quantitative comparisons of
existing works with technical insights, based on which we discuss future
research directions and highlight the necessity of integrating optimizations
across protocol, model, and system levels. We hope this survey can provide an
overarching understanding of existing approaches and potentially inspire future
breakthroughs in the PPML field. As the field is evolving fast, we also provide
a public GitHub repository to continuously track the developments, which is
available at https://github.com/PKU-SEC-Lab/Awesome-PPML-Papers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.13981v1">Evaluation of Human Visual Privacy Protection: A Three-Dimensional
  Framework and Benchmark Dataset</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-07-18T14:43:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sara Abdulaziz, Giacomo D'Amicantonio, Egor Bondarev</p>
    <p><b>Summary:</b> Recent advances in AI-powered surveillance have intensified concerns over the
collection and processing of sensitive personal data. In response, research has
increasingly focused on privacy-by-design solutions, raising the need for
objective techniques to evaluate privacy protection. This paper presents a
comprehensive framework for evaluating visual privacy-protection methods across
three dimensions: privacy, utility, and practicality. In addition, it
introduces HR-VISPR, a publicly available human-centric dataset with biometric,
soft-biometric, and non-biometric labels to train an interpretable privacy
metric. We evaluate 11 privacy protection methods, ranging from conventional
techniques to advanced deep-learning methods, through the proposed framework.
The framework differentiates privacy levels in alignment with human visual
perception, while highlighting trade-offs between privacy, utility, and
practicality. This study, along with the HR-VISPR dataset, serves as an
insightful tool and offers a structured evaluation framework applicable across
diverse contexts.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.13926v1">Developers Insight On Manifest v3 Privacy and Security Webextensions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-07-18T14:00:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Libor Polčák, Giorgio Maone, Michael McMahon, Martin Bednář</p>
    <p><b>Summary:</b> Webextensions can improve web browser privacy, security, and user experience.
The APIs offered by the browser to webextensions affect possible functionality.
Currently, Chrome transitions to a modified set of APIs called Manifest v3.
This paper studies the challenges and opportunities of Manifest v3 with an
in-depth structured qualitative research. Even though some projects observed
positive effects, a majority expresses concerns over limited benefits to users,
removal of crucial APIs, or the need to find workarounds. Our findings indicate
that the transition affects different types of webextensions differently; some
can migrate without losing functionality, while other projects remove
functionality or decline to update. The respondents identified several critical
missing APIs, including reliable APIs to inject content scripts, APIs for
storing confidential content, and others.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.13639v1">Differential Privacy in Kernelized Contextual Bandits via Random
  Projections</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-07-18T03:54:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nikola Pavlovic, Sudeep Salgia, Qing Zhao</p>
    <p><b>Summary:</b> We consider the problem of contextual kernel bandits with stochastic
contexts, where the underlying reward function belongs to a known Reproducing
Kernel Hilbert Space. We study this problem under an additional constraint of
Differential Privacy, where the agent needs to ensure that the sequence of
query points is differentially private with respect to both the sequence of
contexts and rewards. We propose a novel algorithm that achieves the
state-of-the-art cumulative regret of
$\widetilde{\mathcal{O}}(\sqrt{\gamma_TT}+\frac{\gamma_T}{\varepsilon_{\mathrm{DP}}})$
and
$\widetilde{\mathcal{O}}(\sqrt{\gamma_TT}+\frac{\gamma_T\sqrt{T}}{\varepsilon_{\mathrm{DP}}})$
over a time horizon of $T$ in the joint and local models of differential
privacy, respectively, where $\gamma_T$ is the effective dimension of the
kernel and $\varepsilon_{\mathrm{DP}} > 0$ is the privacy parameter. The key
ingredient of the proposed algorithm is a novel private kernel-ridge regression
estimator which is based on a combination of private covariance estimation and
private random projections. It offers a significantly reduced sensitivity
compared to its classical counterpart while maintaining a high prediction
accuracy, allowing our algorithm to achieve the state-of-the-art performance
guarantees.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.13286v2">Privacy-Preserving Fusion for Multi-Sensor Systems Under Multiple Packet
  Dropouts</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2025-07-17T16:50:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jie Huang, Jason J. R. Liu, Xiao He</p>
    <p><b>Summary:</b> Wireless sensor networks (WSNs) are critical components in modern
cyber-physical systems, enabling efficient data collection and fusion through
spatially distributed sensors. However, the inherent risks of eavesdropping and
packet dropouts in such networks pose significant challenges to secure state
estimation. In this paper, we address the privacy-preserving fusion estimation
(PPFE) problem for multi-sensor systems under multiple packet dropouts and
eavesdropping attacks. To mitigate these issues, we propose a distributed
encoding-based privacy-preserving mechanism (PPM) within a control-theoretic
framework, ensuring data privacy during transmission while maintaining the
performance of legitimate state estimation. A centralized fusion filter is
developed, accounting for the coupling effects of packet dropouts and the
encoding-based PPM. Boundedness conditions for the legitimate user's estimation
error covariance are derived via a modified algebraic Riccati equation.
Additionally, by demonstrating the divergence of the eavesdropper's mean
estimation error, the proposed PPFE algorithm's data confidentiality is
rigorously analyzed. Simulation results for an Internet-based three-tank system
validate the effectiveness of the proposed approach, highlighting its potential
to enhance privacy without compromising estimation accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.12932v1">Enkidu: Universal Frequential Perturbation for Real-Time Audio Privacy
  Protection against Voice Deepfakes</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Multimedia-5BC0EB">
  <p><b>Published on:</b> 2025-07-17T09:12:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhou Feng, Jiahao Chen, Chunyi Zhou, Yuwen Pu, Qingming Li, Tianyu Du, Shouling Ji</p>
    <p><b>Summary:</b> The rapid advancement of voice deepfake technologies has raised serious
concerns about user audio privacy, as attackers increasingly exploit publicly
available voice data to generate convincing fake audio for malicious purposes
such as identity theft, financial fraud, and misinformation campaigns. While
existing defense methods offer partial protection, they face critical
limitations, including weak adaptability to unseen user data, poor scalability
to long audio, rigid reliance on white-box knowledge, and high computational
and temporal costs during the encryption process. To address these challenges
and defend against personalized voice deepfake threats, we propose Enkidu, a
novel user-oriented privacy-preserving framework that leverages universal
frequential perturbations generated through black-box knowledge and few-shot
training on a small amount of user data. These highly malleable
frequency-domain noise patches enable real-time, lightweight protection with
strong generalization across variable-length audio and robust resistance to
voice deepfake attacks, all while preserving perceptual quality and speech
intelligibility. Notably, Enkidu achieves over 50 to 200 times processing
memory efficiency (as low as 0.004 gigabytes) and 3 to 7000 times runtime
efficiency (real-time coefficient as low as 0.004) compared to six
state-of-the-art countermeasures. Extensive experiments across six mainstream
text-to-speech models and five cutting-edge automated speaker verification
models demonstrate the effectiveness, transferability, and practicality of
Enkidu in defending against both vanilla and adaptive voice deepfake attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.12730v1">A Privacy-Preserving Semantic-Segmentation Method Using
  Domain-Adaptation Technique</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-17T02:14:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Homare Sueyoshi, Kiyoshi Nishikawa, Hitoshi Kiya</p>
    <p><b>Summary:</b> We propose a privacy-preserving semantic-segmentation method for applying
perceptual encryption to images used for model training in addition to test
images. This method also provides almost the same accuracy as models without
any encryption. The above performance is achieved using a domain-adaptation
technique on the embedding structure of the Vision Transformer (ViT). The
effectiveness of the proposed method was experimentally confirmed in terms of
the accuracy of semantic segmentation when using a powerful
semantic-segmentation model with ViT called Segmentation Transformer.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.12652v1">Federated Learning in Open- and Closed-Loop EMG Decoding: A Privacy and
  Performance Perspective</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-07-16T21:59:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kai Malcolm, César Uribe, Momona Yamagami</p>
    <p><b>Summary:</b> Invasive and non-invasive neural interfaces hold promise as high-bandwidth
input devices for next-generation technologies. However, neural signals
inherently encode sensitive information about an individual's identity and
health, making data sharing for decoder training a critical privacy challenge.
Federated learning (FL), a distributed, privacy-preserving learning framework,
presents a promising solution, but it remains unexplored in closed-loop
adaptive neural interfaces. Here, we introduce FL-based neural decoding and
systematically evaluate its performance and privacy using high-dimensional
electromyography signals in both open- and closed-loop scenarios. In open-loop
simulations, FL significantly outperformed local learning baselines,
demonstrating its potential for high-performance, privacy-conscious neural
decoding. In contrast, closed-loop user studies required adapting FL methods to
accommodate single-user, real-time interactions, a scenario not supported by
standard FL. This modification resulted in local learning decoders surpassing
the adapted FL approach in closed-loop performance, yet local learning still
carried higher privacy risks. Our findings highlight a critical
performance-privacy tradeoff in real-time adaptive applications and indicate
the need for FL methods specifically designed for co-adaptive, single-user
applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.12098v1">A Privacy-Preserving Framework for Advertising Personalization
  Incorporating Federated Learning and Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-07-16T10:07:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiang Li, Yifan Lin, Yuanzhe Zhang</p>
    <p><b>Summary:</b> To mitigate privacy leakage and performance issues in personalized
advertising, this paper proposes a framework that integrates federated learning
and differential privacy. The system combines distributed feature extraction,
dynamic privacy budget allocation, and robust model aggregation to balance
model accuracy, communication overhead, and privacy protection. Multi-party
secure computing and anomaly detection mechanisms further enhance system
resilience against malicious attacks. Experimental results demonstrate that the
framework achieves dual optimization of recommendation accuracy and system
efficiency while ensuring privacy, providing both a practical solution and a
theoretical foundation for applying privacy protection technologies in
advertisement recommendation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.11943v1">Effective Fine-Tuning of Vision Transformers with Low-Rank Adaptation
  for Privacy-Preserving Image Classification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-07-16T06:18:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haiwei Lin, Shoko Imaizumi, Hitoshi Kiya</p>
    <p><b>Summary:</b> We propose a low-rank adaptation method for training privacy-preserving
vision transformer (ViT) models that efficiently freezes pre-trained ViT model
weights. In the proposed method, trainable rank decomposition matrices are
injected into each layer of the ViT architecture, and moreover, the patch
embedding layer is not frozen, unlike in the case of the conventional low-rank
adaptation methods. The proposed method allows us not only to reduce the number
of trainable parameters but to also maintain almost the same accuracy as that
of full-time tuning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.11908v1">Unveiling Usability Challenges in Web Privacy Controls</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-16T04:47:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rahat Masood, Sunday Oyinlola Ogundoyin, Muhammad Ikram, Alex Ye</p>
    <p><b>Summary:</b> With the increasing concerns around privacy and the enforcement of data
privacy laws, many websites now provide users with privacy controls. However,
locating these controls can be challenging, as they are frequently hidden
within multiple settings and layers. Moreover, the lack of standardization
means these controls can vary widely across services. The technical or
confusing terminology used to describe these controls further complicates
users' ability to understand and use them effectively. This paper presents a
large-scale empirical analysis investigating usability challenges of web
privacy controls across 18,628 websites. While aiming for a multi-scenario
view, our automated data collection faced significant hurdles, particularly in
simulating sign-up and authenticated user visits, leading to more focused
insights on guest visit scenarios and challenges in automated capture of
dynamic user interactions. Our heuristic evaluation of three different user
visit scenarios identifies significant website usability issues. Our results
show that privacy policies are most common across all visit scenarios, with
nudges and notices being prevalent in sign-up situations. We recommend
designing privacy controls that: enhance awareness through pop-up nudges and
notices; offer a table of contents as navigational aids and customized settings
links in policies for more informed choice; and ensure accessibility via direct
links to privacy settings from nudges.</p>
  </details>
</div>



<h2>2025-08</h2>

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
  <h3><a href="http://arxiv.org/abs/2508.00287v1">Privacy-Preserving Driver Drowsiness Detection with Spatial
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

