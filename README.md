
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
  <h3><a href="http://arxiv.org/abs/2507.23291v1">Evaluating the Dynamics of Membership Privacy in Deep Learning</a></h3>
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
  <h3><a href="http://arxiv.org/abs/2507.17228v1">P3SL: Personalized Privacy-Preserving Split Learning on Heterogeneous
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
  <h3><a href="http://arxiv.org/abs/2507.14853v1">A Privacy-Centric Approach: Scalable and Secure Federated Learning
  Enabled by Hybrid Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-07-20T07:46:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Khoa Nguyen, Tanveer Khan, Antonis Michalas</p>
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
  <h3><a href="http://arxiv.org/abs/2507.13286v1">Privacy-Preserving Fusion for Multi-Sensor Systems Under Multiple Packet
  Dropouts</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2025-07-17T16:50:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jie Huang, Jason J. R. Liu</p>
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


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.14214v1">Let's Measure the Elephant in the Room: Facilitating Personalized
  Automated Analysis of Privacy Policies at Scale</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-07-15T20:19:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rui Zhao, Vladyslav Melnychuk, Jun Zhao, Jesse Wright, Nigel Shadbolt</p>
    <p><b>Summary:</b> In modern times, people have numerous online accounts, but they rarely read
the Terms of Service or Privacy Policy of those sites despite claiming
otherwise. This paper introduces PoliAnalyzer, a neuro-symbolic system that
assists users with personalized privacy policy analysis. PoliAnalyzer uses
Natural Language Processing (NLP) to extract formal representations of data
usage practices from policy texts. In favor of deterministic, logical inference
is applied to compare user preferences with the formal privacy policy
representation and produce a compliance report. To achieve this, we extend an
existing formal Data Terms of Use policy language to model privacy policies as
app policies and user preferences as data policies. In our evaluation using our
enriched PolicyIE dataset curated by legal experts, PoliAnalyzer demonstrated
high accuracy in identifying relevant data usage practices, achieving F1-score
of 90-100% across most tasks. Additionally, we demonstrate how PoliAnalyzer can
model diverse user data-sharing preferences, derived from prior research as 23
user profiles, and perform compliance analysis against the top 100 most-visited
websites. This analysis revealed that, on average, 95.2% of a privacy policy's
segments do not conflict with the analyzed user preferences, enabling users to
concentrate on understanding the 4.8% (636 / 13205) that violates preferences,
significantly reducing cognitive burden. Further, we identified common
practices in privacy policies that violate user expectations - such as the
sharing of location data with 3rd parties. This paper demonstrates that
PoliAnalyzer can support automated personalized privacy policy analysis at
scale using off-the-shelf NLP tools. This sheds light on a pathway to help
individuals regain control over their data and encourage societal discussions
on platform data practices to promote a fairer power dynamic.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.11649v2">ZKP-FedEval: Verifiable and Privacy-Preserving Federated Evaluation
  using Zero-Knowledge Proofs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2025-07-15T18:34:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Daniel Commey, Benjamin Appiah, Griffith S. Klogo, Garth V. Crosby</p>
    <p><b>Summary:</b> Federated Learning (FL) enables collaborative model training on decentralized
data without exposing raw data. However, the evaluation phase in FL may leak
sensitive information through shared performance metrics. In this paper, we
propose a novel protocol that incorporates Zero-Knowledge Proofs (ZKPs) to
enable privacy-preserving and verifiable evaluation for FL. Instead of
revealing raw loss values, clients generate a succinct proof asserting that
their local loss is below a predefined threshold. Our approach is implemented
without reliance on external APIs, using self-contained modules for federated
learning simulation, ZKP circuit design, and experimental evaluation on both
the MNIST and Human Activity Recognition (HAR) datasets. We focus on a
threshold-based proof for a simple Convolutional Neural Network (CNN) model
(for MNIST) and a multi-layer perceptron (MLP) model (for HAR), and evaluate
the approach in terms of computational overhead, communication cost, and
verifiability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.22908v1">A Privacy-Preserving Federated Framework with Hybrid Quantum-Enhanced
  Learning for Financial Fraud Detection</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2025-07-15T17:29:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abhishek Sawaika, Swetang Krishna, Tushar Tomar, Durga Pritam Suggisetti, Aditi Lal, Tanmaya Shrivastav, Nouhaila Innan, Muhammad Shafique</p>
    <p><b>Summary:</b> Rapid growth of digital transactions has led to a surge in fraudulent
activities, challenging traditional detection methods in the financial sector.
To tackle this problem, we introduce a specialised federated learning framework
that uniquely combines a quantum-enhanced Long Short-Term Memory (LSTM) model
with advanced privacy preserving techniques. By integrating quantum layers into
the LSTM architecture, our approach adeptly captures complex
cross-transactional patters, resulting in an approximate 5% performance
improvement across key evaluation metrics compared to conventional models.
Central to our framework is "FedRansel", a novel method designed to defend
against poisoning and inference attacks, thereby reducing model degradation and
inference accuracy by 4-8%, compared to standard differential privacy
mechanisms. This pseudo-centralised setup with a Quantum LSTM model, enhances
fraud detection accuracy and reinforces the security and confidentiality of
sensitive financial data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.11324v2">A Review of Privacy Metrics for Privacy-Preserving Synthetic Data
  Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2025-07-15T13:56:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Frederik Marinus Trudslev, Matteo Lissandrini, Juan Manuel Rodriguez, Martin Bøgsted, Daniele Dell'Aglio</p>
    <p><b>Summary:</b> Privacy Preserving Synthetic Data Generation (PP-SDG) has emerged to produce
synthetic datasets from personal data while maintaining privacy and utility.
Differential privacy (DP) is the property of a PP-SDG mechanism that
establishes how protected individuals are when sharing their sensitive data. It
is however difficult to interpret the privacy budget ($\varepsilon$) expressed
by DP. To make the actual risk associated with the privacy budget more
transparent, multiple privacy metrics (PMs) have been proposed to assess the
privacy risk of the data. These PMs are utilized in separate studies to assess
newly introduced PP-SDG mechanisms. Consequently, these PMs embody the same
assumptions as the PP-SDG mechanism they were made to assess. Therefore, a
thorough definition of how these are calculated is necessary. In this work, we
present the assumptions and mathematical formulations of 17 distinct privacy
metrics.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.11187v1">Striking the Perfect Balance: Preserving Privacy While Boosting Utility
  in Collaborative Medical Prediction Platforms</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-07-15T10:41:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shao-Bo Lin, Xiaotong Liu, Yao Wang</p>
    <p><b>Summary:</b> Online collaborative medical prediction platforms offer convenience and
real-time feedback by leveraging massive electronic health records. However,
growing concerns about privacy and low prediction quality can deter patient
participation and doctor cooperation. In this paper, we first clarify the
privacy attacks, namely attribute attacks targeting patients and model
extraction attacks targeting doctors, and specify the corresponding privacy
principles. We then propose a privacy-preserving mechanism and integrate it
into a novel one-shot distributed learning framework, aiming to simultaneously
meet both privacy requirements and prediction performance objectives. Within
the framework of statistical learning theory, we theoretically demonstrate that
the proposed distributed learning framework can achieve the optimal prediction
performance under specific privacy requirements. We further validate the
developed privacy-preserving collaborative medical prediction platform through
both toy simulations and real-world data experiments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.10946v1">Solving Linear Programs with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2025-07-15T03:22:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alina Ene, Huy Le Nguyen, Ta Duy Nguyen, Adrian Vladu</p>
    <p><b>Summary:</b> We study the problem of solving linear programs of the form $Ax\le b$,
$x\ge0$ with differential privacy. For homogeneous LPs $Ax\ge0$, we give an
efficient $(\epsilon,\delta)$-differentially private algorithm which with
probability at least $1-\beta$ finds in polynomial time a solution that
satisfies all but
$O(\frac{d^{2}}{\epsilon}\log^{2}\frac{d}{\delta\beta}\sqrt{\log\frac{1}{\rho_{0}}})$
constraints, for problems with margin $\rho_{0}>0$. This improves the bound of
$O(\frac{d^{5}}{\epsilon}\log^{1.5}\frac{1}{\rho_{0}}\mathrm{poly}\log(d,\frac{1}{\delta},\frac{1}{\beta}))$
by [Kaplan-Mansour-Moran-Stemmer-Tur, STOC '25]. For general LPs $Ax\le b$,
$x\ge0$ with potentially zero margin, we give an efficient
$(\epsilon,\delta)$-differentially private algorithm that w.h.p drops
$O(\frac{d^{4}}{\epsilon}\log^{2.5}\frac{d}{\delta}\sqrt{\log dU})$
constraints, where $U$ is an upper bound for the entries of $A$ and $b$ in
absolute value. This improves the result by Kaplan et al. by at least a factor
of $d^{5}$. Our techniques build upon privatizing a rescaling perceptron
algorithm by [Hoberg-Rothvoss, IPCO '17] and a more refined iterative procedure
for identifying equality constraints by Kaplan et al.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.10786v2">"Is it always watching? Is it always listening?" Exploring Contextual
  Privacy and Security Concerns Toward Domestic Social Robots</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-07-14T20:27:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Henry Bell, Jabari Kwesi, Hiba Laabadli, Pardis Emami-Naeini</p>
    <p><b>Summary:</b> Equipped with artificial intelligence (AI) and advanced sensing capabilities,
social robots are gaining interest among consumers in the United States. These
robots seem like a natural evolution of traditional smart home devices.
However, their extensive data collection capabilities, anthropomorphic
features, and capacity to interact with their environment make social robots a
more significant security and privacy threat. Increased risks include data
linkage, unauthorized data sharing, and the physical safety of users and their
homes. It is critical to investigate U.S. users' security and privacy needs and
concerns to guide the design of social robots while these devices are still in
the early stages of commercialization in the U.S. market. Through 19
semi-structured interviews, we identified significant security and privacy
concerns, highlighting the need for transparency, usability, and robust privacy
controls to support adoption. For educational applications, participants
worried most about misinformation, and in medical use cases, they worried about
the reliability of these devices. Participants were also concerned with the
data inference that social robots could enable. We found that participants
expect tangible privacy controls, indicators of data collection, and
context-appropriate functionality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.10695v1">Exploring User Security and Privacy Attitudes and Concerns Toward the
  Use of General-Purpose LLM Chatbots for Mental Health</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-07-14T18:10:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jabari Kwesi, Jiaxun Cao, Riya Manchanda, Pardis Emami-Naeini</p>
    <p><b>Summary:</b> Individuals are increasingly relying on large language model (LLM)-enabled
conversational agents for emotional support. While prior research has examined
privacy and security issues in chatbots specifically designed for mental health
purposes, these chatbots are overwhelmingly "rule-based" offerings that do not
leverage generative AI. Little empirical research currently measures users'
privacy and security concerns, attitudes, and expectations when using
general-purpose LLM-enabled chatbots to manage and improve mental health.
Through 21 semi-structured interviews with U.S. participants, we identified
critical misconceptions and a general lack of risk awareness. Participants
conflated the human-like empathy exhibited by LLMs with human-like
accountability and mistakenly believed that their interactions with these
chatbots were safeguarded by the same regulations (e.g., HIPAA) as disclosures
with a licensed therapist. We introduce the concept of "intangible
vulnerability," where emotional or psychological disclosures are undervalued
compared to more tangible forms of information (e.g., financial or
location-based data). To address this, we propose recommendations to safeguard
user mental health disclosures with general-purpose LLM-enabled chatbots more
effectively.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.10489v1">SynthGuard: Redefining Synthetic Data Generation with a Scalable and
  Privacy-Preserving Workflow Framework</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-14T17:11:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Eduardo Brito, Mahmoud Shoush, Kristian Tamm, Paula Etti, Liina Kamm</p>
    <p><b>Summary:</b> The growing reliance on data-driven applications in sectors such as
healthcare, finance, and law enforcement underscores the need for secure,
privacy-preserving, and scalable mechanisms for data generation and sharing.
Synthetic data generation (SDG) has emerged as a promising approach but often
relies on centralized or external processing, raising concerns about data
sovereignty, domain ownership, and compliance with evolving regulatory
standards. To overcome these issues, we introduce SynthGuard, a framework
designed to ensure computational governance by enabling data owners to maintain
control over SDG workflows. SynthGuard supports modular and privacy-preserving
workflows, ensuring secure, auditable, and reproducible execution across
diverse environments. In this paper, we demonstrate how SynthGuard addresses
the complexities at the intersection of domain-specific needs and scalable SDG
by aligning with requirements for data sovereignty and regulatory compliance.
Developed iteratively with domain expert input, SynthGuard has been validated
through real-world use cases, demonstrating its ability to balance security,
privacy, and scalability while ensuring compliance. The evaluation confirms its
effectiveness in implementing and executing SDG workflows and integrating
privacy and utility assessments across various computational environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.10474v1">Privacy-Preserving Multi-Stage Fall Detection Framework with
  Semi-supervised Federated Learning and Robotic Vision Confirmation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E">
  <p><b>Published on:</b> 2025-07-14T16:55:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Seyed Alireza Rahimi Azghadi, Truong-Thanh-Hung Nguyen, Helene Fournier, Monica Wachowicz, Rene Richard, Francis Palma, Hung Cao</p>
    <p><b>Summary:</b> The aging population is growing rapidly, and so is the danger of falls in
older adults. A major cause of injury is falling, and detection in time can
greatly save medical expenses and recovery time. However, to provide timely
intervention and avoid unnecessary alarms, detection systems must be effective
and reliable while addressing privacy concerns regarding the user. In this
work, we propose a framework for detecting falls using several complementary
systems: a semi-supervised federated learning-based fall detection system
(SF2D), an indoor localization and navigation system, and a vision-based human
fall recognition system. A wearable device and an edge device identify a fall
scenario in the first system. On top of that, the second system uses an indoor
localization technique first to localize the fall location and then navigate a
robot to inspect the scenario. A vision-based detection system running on an
edge device with a mounted camera on a robot is used to recognize fallen
people. Each of the systems of this proposed framework achieves different
accuracy rates. Specifically, the SF2D has a 0.81% failure rate equivalent to
99.19% accuracy, while the vision-based fallen people detection achieves 96.3%
accuracy. However, when we combine the accuracy of these two systems with the
accuracy of the navigation system (95% success rate), our proposed framework
creates a highly reliable performance for fall detection, with an overall
accuracy of 99.99%. Not only is the proposed framework safe for older adults,
but it is also a privacy-preserving solution for detecting falls.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.10640v1">SENSOR: An ML-Enhanced Online Annotation Tool to Uncover Privacy
  Concerns from User Reviews in Social-Media Applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B"> 
  <p><b>Published on:</b> 2025-07-14T14:58:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Labiba Farah, Mohammad Ridwan Kabir, Shohel Ahmed, MD Mohaymen Ul Anam, Md. Sakibul Islam</p>
    <p><b>Summary:</b> The widespread use of social media applications has raised significant
privacy concerns, often highlighted in user reviews. These reviews also provide
developers with valuable insights into improving apps by addressing issues and
introducing better features. However, the sheer volume and nuanced nature of
reviews make manual identification and prioritization of privacy-related
concerns challenging for developers. Previous studies have developed software
utilities to automatically classify user reviews as privacy-relevant,
privacy-irrelevant, bug reports, feature requests, etc., using machine
learning. Notably, there is a lack of focus on classifying reviews specifically
as privacy-related feature requests, privacy-related bug reports, or
privacy-irrelevant. This paper introduces SENtinel SORt (SENSOR), an automated
online annotation tool designed to help developers annotate and classify user
reviews into these categories. For automating the annotation of such reviews,
this paper introduces the annotation model, GRACE (GRU-based Attention with
CBOW Embedding), using Gated Recurrent Units (GRU) with Continuous Bag of Words
(CBOW) and Attention mechanism. Approximately 16000 user reviews from seven
popular social media apps on Google Play Store, including Instagram, Facebook,
WhatsApp, Snapchat, X (formerly Twitter), Facebook Lite, and Line were
analyzed. Two annotators manually labelled the reviews, achieving a Cohen's
Kappa value of 0.87, ensuring a labeled dataset with high inter-rater agreement
for training machine learning models. Among the models tested, GRACE
demonstrated the best performance (macro F1-score: 0.9434, macro ROC-AUC:
0.9934, and accuracy: 95.10%) despite class imbalance. SENSOR demonstrates
significant potential to assist developers with extracting and addressing
privacy-related feature requests or bug reports from user reviews, enhancing
user privacy and trust.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.10627v1">Crypto-Assisted Graph Degree Sequence Release under Local Differential
  Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2025-07-14T07:04:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaojian Zhang, Junqing Wang, Kerui Chen, Peiyuan Zhao, Huiyuan Bai</p>
    <p><b>Summary:</b> Given a graph $G$ defined in a domain $\mathcal{G}$, we investigate locally
differentially private mechanisms to release a degree sequence on $\mathcal{G}$
that accurately approximates the actual degree distribution. Existing solutions
for this problem mostly use graph projection techniques based on edge deletion
process, using a threshold parameter $\theta$ to bound node degrees. However,
this approach presents a fundamental trade-off in threshold parameter
selection. While large $\theta$ values introduce substantial noise in the
released degree sequence, small $\theta$ values result in more edges removed
than necessary. Furthermore, $\theta$ selection leads to an excessive
communication cost. To remedy existing solutions' deficiencies, we present
CADR-LDP, an efficient framework incorporating encryption techniques and
differentially private mechanisms to release the degree sequence. In CADR-LDP,
we first use the crypto-assisted Optimal-$\theta$-Selection method to select
the optimal parameter with a low communication cost. Then, we use the LPEA-LOW
method to add some edges for each node with the edge addition process in local
projection. LPEA-LOW prioritizes the projection with low-degree nodes, which
can retain more edges for such nodes and reduce the projection error.
Theoretical analysis shows that CADR-LDP satisfies $\epsilon$-node local
differential privacy. The experimental results on eight graph datasets show
that our solution outperforms existing methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.09699v1">Interpreting Differential Privacy in Terms of Disclosure Risk</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-13T16:20:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zeki Kazan, Sagar Sharma, Wanrong Zhang, Bo Jiang, Qiang Yan</p>
    <p><b>Summary:</b> As the use of differential privacy (DP) becomes widespread, the development
of effective tools for reasoning about the privacy guarantee becomes
increasingly critical. In pursuit of this goal, we demonstrate novel
relationships between DP and measures of statistical disclosure risk. We
suggest how experts and non-experts can use these results to explain the DP
guarantee, interpret DP composition theorems, select and justify privacy
parameters, and identify worst-case adversary prior probabilities.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.09678v1">Conformal Prediction for Privacy-Preserving Machine Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> 
  <p><b>Published on:</b> 2025-07-13T15:29:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alexander David Balinsky, Dominik Krzeminski, Alexander Balinsky</p>
    <p><b>Summary:</b> We investigate the integration of Conformal Prediction (CP) with supervised
learning on deterministically encrypted data, aiming to bridge the gap between
rigorous uncertainty quantification and privacy-preserving machine learning.
Using AES-encrypted variants of the MNIST dataset, we demonstrate that CP
methods remain effective even when applied directly in the encrypted domain,
owing to the preservation of data exchangeability under fixed-key encryption.
We test traditional $p$-value-based against $e$-value-based conformal
predictors. Our empirical evaluation reveals that models trained on
deterministically encrypted data retain the ability to extract meaningful
structure, achieving 36.88\% test accuracy -- significantly above random
guessing (9.56\%) observed with per-instance encryption. Moreover,
$e$-value-based CP achieves predictive set coverage of over 60\% with 4.3
loss-threshold calibration, correctly capturing the true label in 4888 out of
5000 test cases. In contrast, the $p$-value-based CP yields smaller predictive
sets but with reduced coverage accuracy. These findings highlight both the
promise and limitations of CP in encrypted data settings and underscore
critical trade-offs between prediction set compactness and reliability. %Our
work sets a foundation for principled uncertainty quantification in secure,
privacy-aware learning systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.09453v1">SmartphoneDemocracy: Privacy-Preserving E-Voting on Decentralized
  Infrastructure using Novel European Identity</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-07-13T02:39:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Michał Jóźwik, Johan Pouwelse</p>
    <p><b>Summary:</b> The digitization of democratic processes promises greater accessibility but
presents challenges in terms of security, privacy, and verifiability. Existing
electronic voting systems often rely on centralized architectures, creating
single points of failure and forcing too much trust in authorities, which
contradicts democratic principles. This research addresses the challenge of
creating a secure, private e-voting system with minimized trust dependencies
designed for the most versatile personal device: the smartphone. We introduce
SmartphoneDemocracy, a novel e-voting protocol that combines three key
technologies: the emerging European Digital Identity (EUDI) Wallet for
Sybil-resistant identity verification, Zero-Knowledge Proofs for
privacy-preserving validation, and a peer-to-peer blockchain (TrustChain) for a
resilient, serverless public bulletin board. Our protocol enables voters to
register and cast ballots anonymously and verifiably directly from their
smartphones. We provide a detailed protocol design, a security analysis against
a defined threat model, and a performance evaluation demonstrating that the
computational and network overhead is feasible for medium- to large-scale
elections. By developing and prototyping this system, we demonstrate a viable
path to empower citizens with a trustworthy, accessible, and user-controlled
digital voting experience.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.09067v2">Quantum-Resilient Privacy Ledger (QRPL): A Sovereign Digital Currency
  for the Post-Quantum Era</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-11T23:02:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Serhan W. Bahar</p>
    <p><b>Summary:</b> The emergence of quantum computing presents profound challenges to existing
cryptographic infrastructures, whilst the development of central bank digital
currencies (CBDCs) has raised concerns regarding privacy preservation and
excessive centralisation in digital payment systems. This paper proposes the
Quantum-Resilient Privacy Ledger (QRPL) as an innovative token-based digital
currency architecture that incorporates National Institute of Standards and
Technology (NIST)-standardised post-quantum cryptography (PQC) with hash-based
zero-knowledge proofs to ensure user sovereignty, scalability, and transaction
confidentiality. Key contributions include adaptations of ephemeral proof
chains for unlinkable transactions, a privacy-weighted Proof-of-Stake (PoS)
consensus to promote equitable participation, and a novel zero-knowledge
proof-based mechanism for privacy-preserving selective disclosure. QRPL aims to
address critical shortcomings in prevailing CBDC designs, including risks of
pervasive surveillance, with a 10-20 second block time to balance security and
throughput in future monetary systems. While conceptual, empirical prototypes
are planned. Future work includes prototype development to validate these
models empirically.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.09051v2">SAGE: A Context-Aware Approach for Mining Privacy Requirements Relevant
  Reviews from Mental Health Apps</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-07-11T21:53:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aakash Sorathiya, Gouri Ginde</p>
    <p><b>Summary:</b> Mental health (MH) apps often require sensitive user data to customize
services for mental wellness needs. However, such data collection practices in
some MH apps raise significant privacy concerns for users. These concerns are
often mentioned in app reviews, but other feedback categories, such as
reliability and usability, tend to take precedence. This poses a significant
challenge in automatically identifying privacy requirements-relevant reviews
(privacy reviews) that can be utilized to extract privacy requirements and
address users' privacy concerns. Thus, this study introduces SAGE, a
context-aware approach to automatically mining privacy reviews from MH apps
using Natural Language Inference (NLI) with MH domain-specific privacy
hypotheses (provides domain-specific context awareness) and a GPT model
(eliminates the need for fine-tuning). The quantitative evaluation of SAGE on a
dataset of 204K app reviews achieved an F1 score of 0.85 without any
fine-tuning, outperforming the fine-tuned baseline classifiers BERT and T5.
Furthermore, SAGE extracted 748 privacy reviews previously overlooked by
keyword-based methods, demonstrating its effectiveness through qualitative
evaluation. These reviews can later be refined into actionable privacy
requirement artifacts.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.08978v1">Characterizing Security and Privacy Teaching Standards for Schools in
  the United States</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-07-11T19:20:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Katherine Limes, Nathan Malkin, Kelsey R. Fulton</p>
    <p><b>Summary:</b> Increasingly, students begin learning aspects of security and privacy during
their primary and secondary education (grades K-12 in the United States).
Individual U.S. states and some national organizations publish teaching
standards -- guidance that outlines expectations for what students should learn
-- which often form the basis for course curricula. However, research has not
yet examined what is covered by these standards and whether the topics align
with what the broader security and privacy community thinks students should
know. To shed light on these questions, we started by collecting computer
science teaching standards from all U.S. states and eight national
organizations. After manually examining a total of 11,954 standards, we labeled
3,778 of them as being related to security and privacy, further classifying
these into 103 topics. Topics ranged from technical subjects like encryption,
network security, and embedded systems to social subjects such as laws, ethics,
and appropriate online behavior. Subsequently, we interviewed 11 security and
privacy professionals to examine how the teaching standards align with their
expectations. We found that, while the specific topics they mentioned mostly
overlapped with those of existing standards, professionals placed a greater
emphasis on threat modeling and security mindset.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.10582v1">Transforming Sensitive Documents into Quantitative Data: An AI-Based
  Preprocessing Toolchain for Structured and Privacy-Conscious Analysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> 
  <p><b>Published on:</b> 2025-07-11T11:58:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anders Ledberg, Anna Thalén</p>
    <p><b>Summary:</b> Unstructured text from legal, medical, and administrative sources offers a
rich but underutilized resource for research in public health and the social
sciences. However, large-scale analysis is hampered by two key challenges: the
presence of sensitive, personally identifiable information, and significant
heterogeneity in structure and language. We present a modular toolchain that
prepares such text data for embedding-based analysis, relying entirely on
open-weight models that run on local hardware, requiring only a
workstation-level GPU and supporting privacy-sensitive research.
  The toolchain employs large language model (LLM) prompting to standardize,
summarize, and, when needed, translate texts to English for greater
comparability. Anonymization is achieved via LLM-based redaction, supplemented
with named entity recognition and rule-based methods to minimize the risk of
disclosure. We demonstrate the toolchain on a corpus of 10,842 Swedish court
decisions under the Care of Abusers Act (LVM), comprising over 56,000 pages.
Each document is processed into an anonymized, standardized summary and
transformed into a document-level embedding. Validation, including manual
review, automated scanning, and predictive evaluation shows the toolchain
effectively removes identifying information while retaining semantic content.
As an illustrative application, we train a predictive model using embedding
vectors derived from a small set of manually labeled summaries, demonstrating
the toolchain's capacity for semi-automated content analysis at scale.
  By enabling structured, privacy-conscious analysis of sensitive documents,
our toolchain opens new possibilities for large-scale research in domains where
textual data was previously inaccessible due to privacy and heterogeneity
constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.08412v1">Enforcing Speech Content Privacy in Environmental Sound Recordings using
  Segment-wise Waveform Reversal</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> 
  <p><b>Published on:</b> 2025-07-11T08:48:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Modan Tailleur, Mathieu Lagrange, Pierre Aumond, Vincent Tourre</p>
    <p><b>Summary:</b> Environmental sound recordings often contain intelligible speech, raising
privacy concerns that limit analysis, sharing and reuse of data. In this paper,
we introduce a method that renders speech unintelligible while preserving both
the integrity of the acoustic scene, and the overall audio quality. Our
approach involves reversing waveform segments to distort speech content. This
process is enhanced through a voice activity detection and speech separation
pipeline, which allows for more precise targeting of speech.
  In order to demonstrate the effectivness of the proposed approach, we
consider a three-part evaluation protocol that assesses: 1) speech
intelligibility using Word Error Rate (WER), 2) sound sources detectability
using Sound source Classification Accuracy-Drop (SCAD) from a widely used
pre-trained model, and 3) audio quality using the Fr\'echet Audio Distance
(FAD), computed with our reference dataset that contains unaltered speech.
Experiments on this simulated evaluation dataset, which consists of linear
mixtures of speech and environmental sound scenes, show that our method
achieves satisfactory speech intelligibility reduction (97.9% WER), minimal
degradation of the sound sources detectability (2.7% SCAD), and high perceptual
quality (FAD of 1.40). An ablation study further highlights the contribution of
each component of the pipeline. We also show that incorporating random splicing
to our speech content privacy enforcement method can enhance the algorithm's
robustness to attempt to recover the clean speech, at a slight cost of audio
quality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.08158v1">Beyond the Worst Case: Extending Differential Privacy Guarantees to
  Realistic Adversaries</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-10T20:36:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marika Swanberg, Meenatchi Sundaram Muthu Selva Annamalai, Jamie Hayes, Borja Balle, Adam Smith</p>
    <p><b>Summary:</b> Differential Privacy (DP) is a family of definitions that bound the
worst-case privacy leakage of a mechanism. One important feature of the
worst-case DP guarantee is it naturally implies protections against adversaries
with less prior information, more sophisticated attack goals, and complex
measures of a successful attack. However, the analytical tradeoffs between the
adversarial model and the privacy protections conferred by DP are not well
understood thus far. To that end, this work sheds light on what the worst-case
guarantee of DP implies about the success of attackers that are more
representative of real-world privacy risks.
  In this paper, we present a single flexible framework that generalizes and
extends the patchwork of bounds on DP mechanisms found in prior work. Our
framework allows us to compute high-probability guarantees for DP mechanisms on
a large family of natural attack settings that previous bounds do not capture.
One class of such settings is the approximate reconstruction of multiple
individuals' data, such as inferring nearly entire columns of a tabular data
set from noisy marginals and extracting sensitive information from DP-trained
language models.
  We conduct two empirical case studies to illustrate the versatility of our
bounds and compare them to the success of state-of-the-art attacks.
Specifically, we study attacks that extract non-uniform PII from a DP-trained
language model, as well as multi-column reconstruction attacks where the
adversary has access to some columns in the clear and attempts to reconstruct
the remaining columns for each person's record. We find that the absolute
privacy risk of attacking non-uniform data is highly dependent on the
adversary's prior probability of success. Our high probability bounds give us a
nuanced understanding of the privacy leakage of DP mechanisms in a variety of
previously understudied attack settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.07700v1">Rethinking the Privacy of Text Embeddings: A Reproducibility Study of
  "Text Embeddings Reveal (Almost) As Much As Text"</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2025-07-10T12:27:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dominykas Seputis, Yongkang Li, Karsten Langerak, Serghei Mihailov</p>
    <p><b>Summary:</b> Text embeddings are fundamental to many natural language processing (NLP)
tasks, extensively applied in domains such as recommendation systems and
information retrieval (IR). Traditionally, transmitting embeddings instead of
raw text has been seen as privacy-preserving. However, recent methods such as
Vec2Text challenge this assumption by demonstrating that controlled decoding
can successfully reconstruct original texts from black-box embeddings. The
unexpectedly strong results reported by Vec2Text motivated us to conduct
further verification, particularly considering the typically non-intuitive and
opaque structure of high-dimensional embedding spaces. In this work, we
reproduce the Vec2Text framework and evaluate it from two perspectives: (1)
validating the original claims, and (2) extending the study through targeted
experiments. First, we successfully replicate the original key results in both
in-domain and out-of-domain settings, with only minor discrepancies arising due
to missing artifacts, such as model checkpoints and dataset splits.
Furthermore, we extend the study by conducting a parameter sensitivity
analysis, evaluating the feasibility of reconstructing sensitive inputs (e.g.,
passwords), and exploring embedding quantization as a lightweight privacy
defense. Our results show that Vec2Text is effective under ideal conditions,
capable of reconstructing even password-like sequences that lack clear
semantics. However, we identify key limitations, including its sensitivity to
input sequence length. We also find that Gaussian noise and quantization
techniques can mitigate the privacy risks posed by Vec2Text, with quantization
offering a simpler and more widely applicable solution. Our findings emphasize
the need for caution in using text embeddings and highlight the importance of
further research into robust defense mechanisms for NLP systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.08882v1">Less Stress, More Privacy: Stress Detection on Anonymized Speech of Air
  Traffic Controllers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">  
  <p><b>Published on:</b> 2025-07-10T11:48:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Janaki Viswanathan, Alexander Blatt, Konrad Hagemann, Dietrich Klakow</p>
    <p><b>Summary:</b> Air traffic control (ATC) demands multi-tasking under time pressure with high
consequences of an error. This can induce stress. Detecting stress is a key
point in maintaining the high safety standards of ATC. However, processing ATC
voice data entails privacy restrictions, e.g. the General Data Protection
Regulation (GDPR) law. Anonymizing the ATC voice data is one way to comply with
these restrictions. In this paper, different architectures for stress detection
for anonymized ATCO speech are evaluated. Our best networks reach a stress
detection accuracy of 93.6% on an anonymized version of the Speech Under
Simulated and Actual Stress (SUSAS) dataset and an accuracy of 80.1% on our
anonymized ATC simulation dataset. This shows that privacy does not have to be
an impediment in building well-performing deep-learning-based models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.07565v2">Secure Cooperative Gradient Coding: Optimality, Reliability, and Global
  Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2025-07-10T09:10:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shudi Weng, Chao Ren, Yizhou Zhao, Ming Xiao, Mikael Skoglund</p>
    <p><b>Summary:</b> This paper studies privacy-sensitive federated learning (FL) under unreliable
communication, with a focus on secure aggregation and straggler mitigation. To
preserve user privacy without compromising the utility of the global model,
secure aggregation emerges as a promising approach by coordinating the use of
privacy-preserving noise (secret keys) across participating clients. However,
the unreliable communication will randomly disrupt the key coordination and
disable the exact recovery of the global model in secure aggregation.
Furthermore, unreliable communication can distort the optimization trajectory,
causing the global model to deviate further from the intended global optimum.To
address these challenges, we propose Secure Cooperative Gradient Coding
(SecCoGC), a practical solution that achieves accurate aggregation with
arbitrarily strong privacy guarantees and is inherently robust to communication
uncertainties. To ensure fairness in privacy protection, we further introduce
Fair-SecCoGC, an extension of SecCoGC that enforces equitable privacy
preservation across all clients. Notably, Fair-SecCoGC achieves optimal privacy
under a per-key total power constraint. We formally formulate the problem of
secure aggregation in the real field and present both general and
computationally efficient methods for secret key construction. Our privacy
analysis covers both Local Mutual Information Privacy (LMIP) and Local
Differential Privacy (LDP) across all protocol layers, accounting for
intermittent networks and correlation among secret keys. In addition, we
characterize the system reliability and convergence properties of the proposed
scheme. Experimental results demonstrate that SecCoGC achieves strong
resilience to unreliable communication while maintaining arbitrarily strong
privacy guarantees, yielding test accuracy improvements of 20% to 70% over
existing privacy-preserving methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.08050v1">An Enhanced Privacy-preserving Federated Few-shot Learning Framework for
  Respiratory Disease Diagnosis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-10T07:47:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ming Wang, Zhaoyang Duan, Dong Xue, Fangzhou Liu, Zhongheng Zhang</p>
    <p><b>Summary:</b> The labor-intensive nature of medical data annotation presents a significant
challenge for respiratory disease diagnosis, resulting in a scarcity of
high-quality labeled datasets in resource-constrained settings. Moreover,
patient privacy concerns complicate the direct sharing of local medical data
across institutions, and existing centralized data-driven approaches, which
rely on amounts of available data, often compromise data privacy. This study
proposes a federated few-shot learning framework with privacy-preserving
mechanisms to address the issues of limited labeled data and privacy protection
in diagnosing respiratory diseases. In particular, a meta-stochastic gradient
descent algorithm is proposed to mitigate the overfitting problem that arises
from insufficient data when employing traditional gradient descent methods for
neural network training. Furthermore, to ensure data privacy against gradient
leakage, differential privacy noise from a standard Gaussian distribution is
integrated into the gradients during the training of private models with local
data, thereby preventing the reconstruction of medical images. Given the
impracticality of centralizing respiratory disease data dispersed across
various medical institutions, a weighted average algorithm is employed to
aggregate local diagnostic models from different clients, enhancing the
adaptability of a model across diverse scenarios. Experimental results show
that the proposed method yields compelling results with the implementation of
differential privacy, while effectively diagnosing respiratory diseases using
data from different structures, categories, and distributions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.08878v1">Towards Privacy-Preserving and Personalized Smart Homes via Tailored
  Small Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-10T05:36:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xinyu Huang, Leming Shen, Zijing Ma, Yuanqing Zheng</p>
    <p><b>Summary:</b> Large Language Models (LLMs) have showcased remarkable generalizability in
language comprehension and hold significant potential to revolutionize
human-computer interaction in smart homes. Existing LLM-based smart home
assistants typically transmit user commands, along with user profiles and home
configurations, to remote servers to obtain personalized services. However,
users are increasingly concerned about the potential privacy leaks to the
remote servers. To address this issue, we develop HomeLLaMA, an on-device
assistant for privacy-preserving and personalized smart home serving with a
tailored small language model (SLM). HomeLLaMA learns from cloud LLMs to
deliver satisfactory responses and enable user-friendly interactions. Once
deployed, HomeLLaMA facilitates proactive interactions by continuously updating
local SLMs and user profiles. To further enhance user experience while
protecting their privacy, we develop PrivShield to offer an optional
privacy-preserving LLM-based smart home serving for those users, who are
unsatisfied with local responses and willing to send less-sensitive queries to
remote servers. For evaluation, we build a comprehensive benchmark DevFinder to
assess the service quality. Extensive experiments and user studies (M=100)
demonstrate that HomeLLaMA can provide personalized services while
significantly enhancing user privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.07320v1">Optimizing Communication and Device Clustering for Clustered Federated
  Learning with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-07-09T22:44:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dongyu Wei, Xiaoren Xu, Shiwen Mao, Mingzhe Chen</p>
    <p><b>Summary:</b> In this paper, a secure and communication-efficient clustered federated
learning (CFL) design is proposed. In our model, several base stations (BSs)
with heterogeneous task-handling capabilities and multiple users with
non-independent and identically distributed (non-IID) data jointly perform CFL
training incorporating differential privacy (DP) techniques. Since each BS can
process only a subset of the learning tasks and has limited wireless resource
blocks (RBs) to allocate to users for federated learning (FL) model parameter
transmission, it is necessary to jointly optimize RB allocation and user
scheduling for CFL performance optimization. Meanwhile, our considered CFL
method requires devices to use their limited data and FL model information to
determine their task identities, which may introduce additional communication
overhead. We formulate an optimization problem whose goal is to minimize the
training loss of all learning tasks while considering device clustering, RB
allocation, DP noise, and FL model transmission delay. To solve the problem, we
propose a novel dynamic penalty function assisted value decomposed multi-agent
reinforcement learning (DPVD-MARL) algorithm that enables distributed BSs to
independently determine their connected users, RBs, and DP noise of the
connected users but jointly minimize the training loss of all learning tasks
across all BSs. Different from the existing MARL methods that assign a large
penalty for invalid actions, we propose a novel penalty assignment scheme that
assigns penalty depending on the number of devices that cannot meet
communication constraints (e.g., delay), which can guide the MARL scheme to
quickly find valid actions, thus improving the convergence speed. Simulation
results show that the DPVD-MARL can improve the convergence rate by up to 20%
and the ultimate accumulated rewards by 15% compared to independent Q-learning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.07258v1">FedP3E: Privacy-Preserving Prototype Exchange for Non-IID IoT Malware
  Detection in Cross-Silo Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-09T20:07:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rami Darwish, Mahmoud Abdelsalam, Sajad Khorsandroo, Kaushik Roy</p>
    <p><b>Summary:</b> As IoT ecosystems continue to expand across critical sectors, they have
become prominent targets for increasingly sophisticated and large-scale malware
attacks. The evolving threat landscape, combined with the sensitive nature of
IoT-generated data, demands detection frameworks that are both
privacy-preserving and resilient to data heterogeneity. Federated Learning (FL)
offers a promising solution by enabling decentralized model training without
exposing raw data. However, standard FL algorithms such as FedAvg and FedProx
often fall short in real-world deployments characterized by class imbalance and
non-IID data distributions -- particularly in the presence of rare or disjoint
malware classes. To address these challenges, we propose FedP3E
(Privacy-Preserving Prototype Exchange), a novel FL framework that supports
indirect cross-client representation sharing while maintaining data privacy.
Each client constructs class-wise prototypes using Gaussian Mixture Models
(GMMs), perturbs them with Gaussian noise, and transmits only these compact
summaries to the server. The aggregated prototypes are then distributed back to
clients and integrated into local training, supported by SMOTE-based
augmentation to enhance representation of minority malware classes. Rather than
relying solely on parameter averaging, our prototype-driven mechanism enables
clients to enrich their local models with complementary structural patterns
observed across the federation -- without exchanging raw data or gradients.
This targeted strategy reduces the adverse impact of statistical heterogeneity
with minimal communication overhead. We evaluate FedP3E on the N-BaIoT dataset
under realistic cross-silo scenarios with varying degrees of data imbalance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.07210v1">WatchWitch: Interoperability, Privacy, and Autonomy for the Apple Watch</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-09T18:33:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nils Rollshausen, Alexander Heinrich, Matthias Hollick, Jiska Classen</p>
    <p><b>Summary:</b> Smartwatches such as the Apple Watch collect vast amounts of intimate health
and fitness data as we wear them. Users have little choice regarding how this
data is processed: The Apple Watch can only be used with Apple's iPhones, using
their software and their cloud services. We are the first to publicly
reverse-engineer the watch's wireless protocols, which led to discovering
multiple security issues in Apple's proprietary implementation. With
WatchWitch, our custom Android reimplementation, we break out of Apple's walled
garden -- demonstrating practical interoperability with enhanced privacy
controls and data autonomy. We thus pave the way for more consumer choice in
the smartwatch ecosystem, offering users more control over their devices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.06969v1">Unifying Re-Identification, Attribute Inference, and Data Reconstruction
  Risks in Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> 
  <p><b>Published on:</b> 2025-07-09T15:59:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bogdan Kulynych, Juan Felipe Gomez, Georgios Kaissis, Jamie Hayes, Borja Balle, Flavio du Pin Calmon, Jean Louis Raisaro</p>
    <p><b>Summary:</b> Differentially private (DP) mechanisms are difficult to interpret and
calibrate because existing methods for mapping standard privacy parameters to
concrete privacy risks -- re-identification, attribute inference, and data
reconstruction -- are both overly pessimistic and inconsistent. In this work,
we use the hypothesis-testing interpretation of DP ($f$-DP), and determine that
bounds on attack success can take the same unified form across
re-identification, attribute inference, and data reconstruction risks. Our
unified bounds are (1) consistent across a multitude of attack settings, and
(2) tunable, enabling practitioners to evaluate risk with respect to arbitrary
(including worst-case) levels of baseline risk. Empirically, our results are
tighter than prior methods using $\varepsilon$-DP, R\'enyi DP, and concentrated
DP. As a result, calibrating noise using our bounds can reduce the required
noise by 20% at the same risk level, which yields, e.g., more than 15pp
accuracy increase in a text classification task. Overall, this unifying
perspective provides a principled framework for interpreting and calibrating
the degree of protection in DP against specific levels of re-identification,
attribute inference, or data reconstruction risk.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.08864v1">Privacy-Utility-Fairness: A Balanced Approach to Vehicular-Traffic
  Management System</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2025-07-09T13:49:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Poushali Sengupta, Sabita Maharjan, frank Eliassen, Yan Zhang</p>
    <p><b>Summary:</b> Location-based vehicular traffic management faces significant challenges in
protecting sensitive geographical data while maintaining utility for traffic
management and fairness across regions. Existing state-of-the-art solutions
often fail to meet the required level of protection against linkage attacks and
demographic biases, leading to privacy leakage and inequity in data analysis.
In this paper, we propose a novel algorithm designed to address the challenges
regarding the balance of privacy, utility, and fairness in location-based
vehicular traffic management systems. In this context, utility means providing
reliable and meaningful traffic information, while fairness ensures that all
regions and individuals are treated equitably in data use and decision-making.
Employing differential privacy techniques, we enhance data security by
integrating query-based data access with iterative shuffling and calibrated
noise injection, ensuring that sensitive geographical data remains protected.
We ensure adherence to epsilon-differential privacy standards by implementing
the Laplace mechanism. We implemented our algorithm on vehicular location-based
data from Norway, demonstrating its ability to maintain data utility for
traffic management and urban planning while ensuring fair representation of all
geographical areas without being overrepresented or underrepresented.
Additionally, we have created a heatmap of Norway based on our model,
illustrating the privatized and fair representation of the traffic conditions
across various cities. Our algorithm provides privacy in vehicular traffic</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.06652v1">Federated Learning Inspired Fuzzy Systems: Decentralized Rule Updating
  for Privacy and Scalable Decision Making</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-07-09T08:34:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arthur Alexander Lim, Zhen Bin It, Jovan Bowen Heng, Tee Hui Teo</p>
    <p><b>Summary:</b> Fuzzy systems are a way to allow machines, systems and frameworks to deal
with uncertainty, which is not possible in binary systems that most computers
use. These systems have already been deployed for certain use cases, and fuzzy
systems could be further improved as proposed in this paper. Such technologies
to draw inspiration from include machine learning and federated learning.
Machine learning is one of the recent breakthroughs of technology and could be
applied to fuzzy systems to further improve the results it produces. Federated
learning is also one of the recent technologies that have huge potential, which
allows machine learning training to improve by reducing privacy risk, reducing
burden on networking infrastructure, and reducing latency of the latest model.
Aspects from federated learning could be used to improve federated learning,
such as applying the idea of updating the fuzzy rules that make up a key part
of fuzzy systems, to further improve it over time. This paper discusses how
these improvements would be implemented in fuzzy systems, and how it would
improve fuzzy systems. It also discusses certain limitations on the potential
improvements. It concludes that these proposed ideas and improvements require
further investigation to see how far the improvements are, but the potential is
there to improve fuzzy systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.06619v1">Steps Adaptive Decay DPSGD: Enhancing Performance on Imbalanced Datasets
  with Differential Privacy with HAM10000</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2025-07-09T07:46:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaobo Huang, Fang Xie</p>
    <p><b>Summary:</b> When applying machine learning to medical image classification, data leakage
is a critical issue. Previous methods, such as adding noise to gradients for
differential privacy, work well on large datasets like MNIST and CIFAR-100, but
fail on small, imbalanced medical datasets like HAM10000. This is because the
imbalanced distribution causes gradients from minority classes to be clipped
and lose crucial information, while majority classes dominate. This leads the
model to fall into suboptimal solutions early. To address this, we propose
SAD-DPSGD, which uses a linear decaying mechanism for noise and clipping
thresholds. By allocating more privacy budget and using higher clipping
thresholds in the initial training phases, the model avoids suboptimal
solutions and enhances performance. Experiments show that SAD-DPSGD outperforms
Auto-DPSGD on HAM10000, improving accuracy by 2.15% under $\epsilon = 3.0$ ,
$\delta = 10^{-3}$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.08853v1">Clio-X: AWeb3 Solution for Privacy-Preserving AI Access to Digital
  Archives</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Digital Libraries-D91E36"> 
  <p><b>Published on:</b> 2025-07-09T05:30:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Victoria L. Lemieux, Rosa Gil, Faith Molosiwa, Qihong Zhou, Binming Li, Roberto Garcia, Luis De La Torre Cubillo, Zehua Wang</p>
    <p><b>Summary:</b> As archives turn to artificial intelligence to manage growing volumes of
digital records, privacy risks inherent in current AI data practices raise
critical concerns about data sovereignty and ethical accountability. This paper
explores how privacy-enhancing technologies (PETs) and Web3 architectures can
support archives to preserve control over sensitive content while still being
able to make it available for access by researchers. We present Clio-X, a
decentralized, privacy-first Web3 digital solution designed to embed PETs into
archival workflows and support AI-enabled reference and access. Drawing on a
user evaluation of a medium-fidelity prototype, the study reveals both interest
in the potential of the solution and significant barriers to adoption related
to trust, system opacity, economic concerns, and governance. Using Rogers'
Diffusion of Innovation theory, we analyze the sociotechnical dimensions of
these barriers and propose a path forward centered on participatory design and
decentralized governance through a Clio-X Decentralized Autonomous
Organization. By integrating technical safeguards with community-based
oversight, Clio-X offers a novel model to ethically deploy AI in cultural
heritage contexts.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.06508v1">Subgraph Counting under Edge Local Differential Privacy Based on Noisy
  Adjacency Matrix</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-09T03:13:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jintao Guo, Ying Zhou, Chao Li, Guixun Luo</p>
    <p><b>Summary:</b> When analyzing connection patterns within graphs, subgraph counting serves as
an effective and fundamental approach. Edge-local differential privacy
(edge-LDP) and shuffle model have been employed to achieve subgraph counting
under a privacy-preserving situation. Existing algorithms are plagued by high
time complexity, excessive download costs, low accuracy, or dependence on
trusted third parties. To address the aforementioned challenges, we propose the
Noisy Adjacency Matrix (NAM), which combines differential privacy with the
adjacency matrix of the graph. NAM offers strong versatility and scalability,
making it applicable to a wider range of DP variants, DP mechanisms, and graph
types. Based on NAM, we designed five algorithms (TriOR, TriTR, TriMTR, QuaTR,
and 2STAR) to count three types of subgraphs: triangles, quadrangles, and
2-stars. Theoretical and experimental results demonstrate that in triangle
counting, TriOR maximizes accuracy with reduced time complexity among one-round
algorithms, TriTR achieves optimal accuracy, TriMTR achieves the highest
accuracy under low download costs, and QuaTR stands as the first quadrangle
counting algorithm under pure edge-LDP. We implement edge-LDP for noisy data
via a confidence interval-inspired method, providing DP guarantees on
randomized data. Our 2STAR algorithm achieves the highest accuracy in 2-star
counting and can be derived as a byproduct of two-round triangle or quadrangle
counting algorithms, enabling efficient joint estimation of triangle,
quadrangle, and 2-star counts within two query rounds.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.06350v1">An Architecture for Privacy-Preserving Telemetry Scheme</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-07-08T19:20:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kenneth Odoh</p>
    <p><b>Summary:</b> We present a privacy-preserving telemetry aggregation scheme. Our underlying
frequency estimation routine works within the framework of differential
privacy. The design philosophy follows a client-server architecture.
Furthermore, the system uses a local differential privacy scheme where data
gets randomized on the client before submitting the request to the resource
server. This scheme allows for data analysis on de-identified data by carefully
adding noise to prevent re-identification attacks, thereby facilitating public
data release without compromising the identifiability of the individual record.
This work further enhances privacy guarantees by leveraging Oblivious HTTP
(OHTTP) to achieve increased privacy protection for data in transit that
addresses pre-existing privacy vulnerabilities in raw HTTP. We provide an
implementation that focuses on frequency estimation with a histogram of a known
dictionary. Our resulting formulation based on OHTTP has provided stricter
privacy safeguards when compared to trusting an organization to manually delete
identifying information from the client's request in the ingestor as deployed
in reference work~\cite{apple2017}. Code available at
https://github.com/kenluck2001/miscellaneous/tree/master/src/Privacy-Preserving-Telemetry.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.06008v1">The Impact of Event Data Partitioning on Privacy-aware Process Discovery</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2025-07-08T14:13:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jungeun Lim, Stephan A. Fahrenkrog-Petersen, Xixi Lu, Jan Mendling, Minseok Song</p>
    <p><b>Summary:</b> Information systems support the execution of business processes. The event
logs of these executions generally contain sensitive information about
customers, patients, and employees. The corresponding privacy challenges can be
addressed by anonymizing the event logs while still retaining utility for
process discovery. However, trading off utility and privacy is difficult: the
higher the complexity of event log, the higher the loss of utility by
anonymization. In this work, we propose a pipeline that combines anonymization
and event data partitioning, where event abstraction is utilized for
partitioning. By leveraging event abstraction, event logs can be segmented into
multiple parts, allowing each sub-log to be anonymized separately. This
pipeline preserves privacy while mitigating the loss of utility. To validate
our approach, we study the impact of event partitioning on two anonymization
techniques using three real-world event logs and two process discovery
techniques. Our results demonstrate that event partitioning can bring
improvements in process discovery utility for directly-follows-based
anonymization techniques.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.05875v1">Post-Processing in Local Differential Privacy: An Extensive Evaluation
  and Benchmark Platform</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-08T10:59:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alireza Khodaie, Berkay Kemal Balioglu, Mehmet Emre Gursoy</p>
    <p><b>Summary:</b> Local differential privacy (LDP) has recently gained prominence as a powerful
paradigm for collecting and analyzing sensitive data from users' devices.
However, the inherent perturbation added by LDP protocols reduces the utility
of the collected data. To mitigate this issue, several post-processing (PP)
methods have been developed. Yet, the comparative performance of PP methods
under diverse settings remains underexplored. In this paper, we present an
extensive benchmark comprising 6 popular LDP protocols, 7 PP methods, 4 utility
metrics, and 6 datasets to evaluate the behaviors and optimality of PP methods
under diverse conditions. Through extensive experiments, we show that while PP
can substantially improve utility when the privacy budget is small (i.e.,
strict privacy), its benefit diminishes as the privacy budget grows. Moreover,
our findings reveal that the optimal PP method depends on multiple factors,
including the choice of LDP protocol, privacy budget, data characteristics
(such as distribution and domain size), and the specific utility metric. To
advance research in this area and assist practitioners in identifying the most
suitable PP method for their setting, we introduce LDP$^3$, an open-source
benchmark platform. LDP$^3$ contains all methods used in our experimental
analysis, and it is designed in a modular, extensible, and multi-threaded way
for future use and development.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.05872v1">LDP$^3$: An Extensible and Multi-Threaded Toolkit for Local Differential
  Privacy Protocols and Post-Processing Methods</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-08T10:51:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Berkay Kemal Balioglu, Alireza Khodaie, Mehmet Emre Gursoy</p>
    <p><b>Summary:</b> Local differential privacy (LDP) has become a prominent notion for
privacy-preserving data collection. While numerous LDP protocols and
post-processing (PP) methods have been developed, selecting an optimal
combination under different privacy budgets and datasets remains a challenge.
Moreover, the lack of a comprehensive and extensible LDP benchmarking toolkit
raises difficulties in evaluating new protocols and PP methods. To address
these concerns, this paper presents LDP$^3$ (pronounced LDP-Cube), an
open-source, extensible, and multi-threaded toolkit for LDP researchers and
practitioners. LDP$^3$ contains implementations of several LDP protocols, PP
methods, and utility metrics in a modular and extensible design. Its modular
design enables developers to conveniently integrate new protocols and PP
methods. Furthermore, its multi-threaded nature enables significant reductions
in execution times via parallelization. Experimental evaluations demonstrate
that: (i) using LDP$^3$ to select a good protocol and post-processing method
substantially improves utility compared to a bad or random choice, and (ii) the
multi-threaded design of LDP$^3$ brings substantial benefits in terms of
efficiency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.08843v1">Can We Predict Your Next Move Without Breaking Your Privacy?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-08T08:13:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arpita Soni, Sahil Tripathi, Gautam Siddharth Kashyap, Manaswi Kulahara, Mohammad Anas Azeez, Zohaib Hasan Siddiqui, Nipun Joshi, Jiechao Gao</p>
    <p><b>Summary:</b> We propose FLLL3M--Federated Learning with Large Language Models for Mobility
Modeling--a privacy-preserving framework for Next-Location Prediction (NxLP).
By retaining user data locally and leveraging LLMs through an efficient outer
product mechanism, FLLL3M ensures high accuracy with low resource demands. It
achieves SOT results on Gowalla (Acc@1: 12.55, MRR: 0.1422), WeePlace (10.71,
0.1285), Brightkite (10.42, 0.1169), and FourSquare (8.71, 0.1023), while
reducing parameters by up to 45.6% and memory usage by 52.7%.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.05610v2">On the Inherent Privacy of Zeroth Order Projected Gradient Descent</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2025-07-08T02:38:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Devansh Gupta, Meisam Razaviyayn, Vatsal Sharan</p>
    <p><b>Summary:</b> Differentially private zeroth-order optimization methods have recently gained
popularity in private fine tuning of machine learning models due to their
reduced memory requirements. Current approaches for privatizing zeroth-order
methods rely on adding Gaussian noise to the estimated zeroth-order gradients.
However, since the search direction in the zeroth-order methods is inherently
random, researchers including Tang et al. (2024) and Zhang et al. (2024a) have
raised an important question: is the inherent noise in zeroth-order estimators
sufficient to ensure the overall differential privacy of the algorithm? This
work settles this question for a class of oracle-based optimization algorithms
where the oracle returns zeroth-order gradient estimates. In particular, we
show that for a fixed initialization, there exist strongly convex objective
functions such that running (Projected) Zeroth-Order Gradient Descent (ZO-GD)
is not differentially private. Furthermore, we show that even with random
initialization and without revealing (initial and) intermediate iterates, the
privacy loss in ZO-GD can grow superlinearly with the number of iterations when
minimizing convex objective functions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.05415v1">Layered, Overlapping, and Inconsistent: A Large-Scale Analysis of the
  Multiple Privacy Policies and Controls of U.S. Banks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-07T18:55:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lu Xian, Van Tran, Lauren Lee, Meera Kumar, Yichen Zhang, Florian Schaub</p>
    <p><b>Summary:</b> Privacy policies are often complex. An exception is the two-page standardized
notice that U.S. financial institutions must provide under the
Gramm-Leach-Bliley Act (GLBA). However, banks now operate websites, mobile
apps, and other services that involve complex data sharing practices that
require additional privacy notices and do-not-sell opt-outs. We conducted a
large-scale analysis of how U.S. banks implement privacy policies and controls
in response to GLBA; other federal privacy policy requirements; and the
California Consumer Privacy Act (CCPA), a key example for U.S. state privacy
laws. We focused on the disclosure and control of a set of especially
privacy-invasive practices: third-party data sharing for marketing-related
purposes. We collected privacy policies for the 2,067 largest U.S. banks,
45.3\% of which provided multiple policies. Across disclosures and controls
within the \textit{same} bank, we identified frequent, concerning
inconsistencies -- such as banks indicating in GLBA notices that they do not
share with third parties but disclosing sharing elsewhere, or using third-party
marketing/advertising cookies without disclosure. This multiplicity of
policies, with the inconsistencies it causes, may create consumer confusion and
undermine the transparency goals of the very laws that require them. Our
findings call into question whether current policy requirements, such as the
GLBA notice, are achieving their intended goals in today's online banking
landscape. We discuss potential avenues for reforming and harmonizing privacy
policies and control requirements across federal and state laws.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.05391v1">Controlling What You Share: Assessing Language Model Adherence to
  Privacy Preferences</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-07T18:22:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guillem Ramírez, Alexandra Birch, Ivan Titov</p>
    <p><b>Summary:</b> Large language models (LLMs) are primarily accessed via commercial APIs, but
this often requires users to expose their data to service providers. In this
paper, we explore how users can stay in control of their data by using privacy
profiles: simple natural language instructions that say what should and should
not be revealed. We build a framework where a local model uses these
instructions to rewrite queries, only hiding details deemed sensitive by the
user, before sending them to an external model, thus balancing privacy with
performance. To support this research, we introduce PEEP, a multilingual
dataset of real user queries annotated to mark private content and paired with
synthetic privacy profiles. Our experiments with lightweight LLMs show they can
follow these instructions to some extent, but also face consistent challenges,
highlighting the need for models that better understand and comply with
user-defined privacy preferences.</p>
  </details>
</div>



<h2>2025-08</h2>

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

