
<h2>2025-10</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.26523v1">Interdependent Privacy in Smart Homes: Hunting for Bystanders in Privacy
  Policies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-30T14:16:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuaishuai Liu, Gergely Acs, Gergely Biczók</p>
    <p><b>Summary:</b> Smart home devices such as video doorbells and security cameras are becoming
increasingly common in everyday life. While these devices offer convenience and
safety, they also raise new privacy concerns: how these devices affect others,
like neighbors, visitors, or people passing by. This issue is generally known
as interdependent privacy, where one person's actions (or inaction) may impact
the privacy of others, and, specifically, bystander privacy in the context of
smart homes. Given lax data protection regulations in terms of shared physical
spaces and amateur joint data controllers, we expect that the privacy policies
of smart home products reflect the missing regulatory incentives. This paper
presents a focused privacy policy analysis of 20 video doorbell and smart
camera products, concentrating explicitly on the bystander aspect. We show that
although some of the vendors acknowledge bystanders, they address it only to
the extent of including disclaimers, shifting the ethical responsibility for
collecting the data of non-users to the device owner. In addition, we identify
and examine real-world cases related to bystander privacy, demonstrating how
current deployments can impact non-users. Based on our findings, we analyze
vendor privacy policies in light of existing legal frameworks and technical
capabilities, and we provide practical recommendations for both policy language
and system design to enhance transparency and empower both bystanders and
device owners.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.26148v1">STAR: A Privacy-Preserving, Energy-Efficient Edge AI Framework for Human
  Activity Recognition via Wi-Fi CSI in Mobile and Pervasive Computing
  Environments</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-10-30T05:08:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kexing Liu</p>
    <p><b>Summary:</b> Human Activity Recognition (HAR) via Wi-Fi Channel State Information (CSI)
presents a privacy-preserving, contactless sensing approach suitable for smart
homes, healthcare monitoring, and mobile IoT systems. However, existing methods
often encounter computational inefficiency, high latency, and limited
feasibility within resource-constrained, embedded mobile edge environments.
This paper proposes STAR (Sensing Technology for Activity Recognition), an
edge-AI-optimized framework that integrates a lightweight neural architecture,
adaptive signal processing, and hardware-aware co-optimization to enable
real-time, energy-efficient HAR on low-power embedded devices. STAR
incorporates a streamlined Gated Recurrent Unit (GRU)-based recurrent neural
network, reducing model parameters by 33% compared to conventional LSTM models
while maintaining effective temporal modeling capability. A multi-stage
pre-processing pipeline combining median filtering, 8th-order Butterworth
low-pass filtering, and Empirical Mode Decomposition (EMD) is employed to
denoise CSI amplitude data and extract spatial-temporal features. For on-device
deployment, STAR is implemented on a Rockchip RV1126 processor equipped with an
embedded Neural Processing Unit (NPU), interfaced with an ESP32-S3-based CSI
acquisition module. Experimental results demonstrate a mean recognition
accuracy of 93.52% across seven activity classes and 99.11% for human presence
detection, utilizing a compact 97.6k-parameter model. INT8 quantized inference
achieves a processing speed of 33 MHz with just 8% CPU utilization, delivering
sixfold speed improvements over CPU-based execution. With sub-second response
latency and low power consumption, the system ensures real-time,
privacy-preserving HAR, offering a practical, scalable solution for mobile and
pervasive computing environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.26102v1">PEEL: A Poisoning-Exposing Encoding Theoretical Framework for Local
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-30T03:29:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lisha Shuai, Jiuling Dong, Nan Zhang, Shaofeng Tan, Haokun Zhang, Zilong Song, Gaoya Dong, Xiaolong Yang</p>
    <p><b>Summary:</b> Local Differential Privacy (LDP) is a widely adopted privacy-protection model
in the Internet of Things (IoT) due to its lightweight, decentralized, and
scalable nature. However, it is vulnerable to poisoning attacks, and existing
defenses either incur prohibitive resource overheads or rely on domain-specific
prior knowledge, limiting their practical deployment. To address these
limitations, we propose PEEL, a Poisoning-Exposing Encoding theoretical
framework for LDP, which departs from resource- or prior-dependent
countermeasures and instead leverages the inherent structural consistency of
LDP-perturbed data. As a non-intrusive post-processing module, PEEL amplifies
stealthy poisoning effects by re-encoding LDP-perturbed data via
sparsification, normalization, and low-rank projection, thereby revealing both
output and rule poisoning attacks through structural inconsistencies in the
reconstructed space. Theoretical analysis proves that PEEL, integrated with
LDP, retains unbiasedness and statistical accuracy, while being robust to
expose both output and rule poisoning attacks. Moreover, evaluation results
show that LDP-integrated PEEL not only outperforms four state-of-the-art
defenses in terms of poisoning exposure accuracy but also significantly reduces
client-side computational costs, making it highly suitable for large-scale IoT
deployments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.25932v1">FakeZero: Real-Time, Privacy-Preserving Misinformation Detection for
  Facebook and X</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-10-29T20:11:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Soufiane Essahli, Oussama Sarsar, Imane Fouad, Anas Motii, Ahmed Bentajer</p>
    <p><b>Summary:</b> Social platforms distribute information at unprecedented speed, which in turn
accelerates the spread of misinformation and threatens public discourse. We
present FakeZero, a fully client-side, cross-platform browser extension that
flags unreliable posts on Facebook and X (formerly Twitter) while the user
scrolls. All computation, DOM scraping, tokenisation, Transformer inference,
and UI rendering run locally through the Chromium messaging API, so no personal
data leaves the device.FakeZero employs a three-stage training curriculum:
baseline fine-tuning and domain-adaptive training enhanced with focal loss,
adversarial augmentation, and post-training quantisation. Evaluated on a
dataset of 239,000 posts, the DistilBERT-Quant model (67.6 MB) reaches 97.1%
macro-F1, 97.4% accuracy, and an AUROC of 0.996, with a median latency of
approximately 103 ms on a commodity laptop. A memory-efficient TinyBERT-Quant
variant retains 95.7% macro-F1 and 96.1% accuracy while shrinking the model to
14.7 MB and lowering latency to approximately 40 ms, showing that high-quality
fake-news detection is feasible under tight resource budgets with only modest
performance loss.By providing inline credibility cues, the extension can serve
as a valuable tool for policymakers seeking to curb the spread of
misinformation across social networks. With user consent, FakeZero also opens
the door for researchers to collect large-scale datasets of fake news in the
wild, enabling deeper analysis and the development of more robust detection
techniques.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.25670v1">Spectral Perturbation Bounds for Low-Rank Approximation with
  Applications to Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Numerical Analysis-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Numerical Analysis-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Spectral Theory-D91E36">
  <p><b>Published on:</b> 2025-10-29T16:36:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Phuc Tran, Nisheeth K. Vishnoi, Van H. Vu</p>
    <p><b>Summary:</b> A central challenge in machine learning is to understand how noise or
measurement errors affect low-rank approximations, particularly in the spectral
norm. This question is especially important in differentially private low-rank
approximation, where one aims to preserve the top-$p$ structure of a
data-derived matrix while ensuring privacy. Prior work often analyzes Frobenius
norm error or changes in reconstruction quality, but these metrics can over- or
under-estimate true subspace distortion. The spectral norm, by contrast,
captures worst-case directional error and provides the strongest utility
guarantees. We establish new high-probability spectral-norm perturbation bounds
for symmetric matrices that refine the classical Eckart--Young--Mirsky theorem
and explicitly capture interactions between a matrix $A \in \mathbb{R}^{n
\times n}$ and an arbitrary symmetric perturbation $E$. Under mild eigengap and
norm conditions, our bounds yield sharp estimates for $\|(A + E)_p - A_p\|$,
where $A_p$ is the best rank-$p$ approximation of $A$, with improvements of up
to a factor of $\sqrt{n}$. As an application, we derive improved utility
guarantees for differentially private PCA, resolving an open problem in the
literature. Our analysis relies on a novel contour bootstrapping method from
complex analysis and extends it to a broad class of spectral functionals,
including polynomials and matrix exponentials. Empirical results on real-world
datasets confirm that our bounds closely track the actual spectral error under
diverse perturbation regimes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.25477v1">A Study on Privacy-Preserving Scholarship Evaluation Based on
  Decentralized Identity and Zero-Knowledge Proofs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-29T12:56:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yi Chen, Bin Chen, Peichang Zhang, Da Che</p>
    <p><b>Summary:</b> Traditional centralized scholarship evaluation processes typically require
students to submit detailed academic records and qualification information,
which exposes them to risks of data leakage and misuse, making it difficult to
simultaneously ensure privacy protection and transparent auditability. To
address these challenges, this paper proposes a scholarship evaluation system
based on Decentralized Identity (DID) and Zero-Knowledge Proofs (ZKP). The
system aggregates multidimensional ZKPs off-chain, and smart contracts verify
compliance with evaluation criteria without revealing raw scores or
computational details. Experimental results demonstrate that the proposed
solution not only automates the evaluation efficiently but also maximally
preserves student privacy and data integrity, offering a practical and
trustworthy technical paradigm for higher education scholarship programs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.25277v1">A Privacy-Preserving Ecosystem for Developing Machine Learning
  Algorithms Using Patient Data: Insights from the TUM.ai Makeathon</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-10-29T08:37:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Simon Süwer, Mai Khanh Mai, Christoph Klein, Nicola Götzenberger, Denis Dalić, Andreas Maier, Jan Baumbach</p>
    <p><b>Summary:</b> The integration of clinical data offers significant potential for the
development of personalized medicine. However, its use is severely restricted
by the General Data Protection Regulation (GDPR), especially for small cohorts
with rare diseases. High-quality, structured data is essential for the
development of predictive medical AI. In this case study, we propose a novel,
multi-stage approach to secure AI training: (1) The model is designed on a
simulated clinical knowledge graph (cKG). This graph is used exclusively to
represent the structural characteristics of the real cKG without revealing any
sensitive content. (2) The model is then integrated into the FeatureCloud (FC)
federated learning framework, where it is prepared in a single-client
configuration within a protected execution environment. (3) Training then takes
place within the hospital environment on the real cKG, either under the direct
supervision of hospital staff or via a fully automated pipeline controlled by
the hospital. (4) Finally, verified evaluation scripts are executed, which only
return aggregated performance metrics. This enables immediate performance
feedback without sensitive patient data or individual predictions, leaving the
clinic. A fundamental element of this approach involves the incorporation of a
cKG, which serves to organize multi-omics and patient data within the context
of real-world hospital environments. This approach was successfully validated
during the TUM.ai Makeathon 2024 (TUMaiM24) challenge set by the Dr. von Hauner
Children's Hospital (HCH-LMU): 50 students developed models for patient
classification and diagnosis without access to real data. Deploying secure
algorithms via federated frameworks, such as the FC framework, could be a
practical way of achieving privacy-preserving AI in healthcare.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.24498v1">Design and Optimization of Cloud Native Homomorphic Encryption Workflows
  for Privacy-Preserving ML Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-10-28T15:13:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tejaswini Bollikonda</p>
    <p><b>Summary:</b> As machine learning (ML) models become increasingly deployed through cloud
infrastructures, the confidentiality of user data during inference poses a
significant security challenge. Homomorphic Encryption (HE) has emerged as a
compelling cryptographic technique that enables computation on encrypted data,
allowing predictions to be generated without decrypting sensitive inputs.
However, the integration of HE within large scale cloud native pipelines
remains constrained by high computational overhead, orchestration complexity,
and model compatibility issues.
  This paper presents a systematic framework for the design and optimization of
cloud native homomorphic encryption workflows that support privacy-preserving
ML inference. The proposed architecture integrates containerized HE modules
with Kubernetes-based orchestration, enabling elastic scaling and parallel
encrypted computation across distributed environments. Furthermore,
optimization strategies including ciphertext packing, polynomial modulus
adjustment, and operator fusion are employed to minimize latency and resource
consumption while preserving cryptographic integrity. Experimental results
demonstrate that the proposed system achieves up to 3.2times inference
acceleration and 40% reduction in memory utilization compared to conventional
HE pipelines. These findings illustrate a practical pathway for deploying
secure ML-as-a-Service (MLaaS) systems that guarantee data confidentiality
under zero-trust cloud conditions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.24233v1">PRIVET: Privacy Metric Based on Extreme Value Theory</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-10-28T09:42:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Antoine Szatkownik, Aurélien Decelle, Beatriz Seoane, Nicolas Bereux, Léo Planche, Guillaume Charpiat, Burak Yelmen, Flora Jay, Cyril Furtlehner</p>
    <p><b>Summary:</b> Deep generative models are often trained on sensitive data, such as genetic
sequences, health data, or more broadly, any copyrighted, licensed or protected
content. This raises critical concerns around privacy-preserving synthetic
data, and more specifically around privacy leakage, an issue closely tied to
overfitting. Existing methods almost exclusively rely on global criteria to
estimate the risk of privacy failure associated to a model, offering only
quantitative non interpretable insights. The absence of rigorous evaluation
methods for data privacy at the sample-level may hinder the practical
deployment of synthetic data in real-world applications. Using extreme value
statistics on nearest-neighbor distances, we propose PRIVET, a generic
sample-based, modality-agnostic algorithm that assigns an individual privacy
leak score to each synthetic sample. We empirically demonstrate that PRIVET
reliably detects instances of memorization and privacy leakage across diverse
data modalities, including settings with very high dimensionality, limited
sample sizes such as genetic data and even under underfitting regimes. We
compare our method to existing approaches under controlled settings and show
its advantage in providing both dataset level and sample level assessments
through qualitative and quantitative outputs. Additionally, our analysis
reveals limitations in existing computer vision embeddings to yield
perceptually meaningful distances when identifying near-duplicate samples.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.24072v1">Covert Surveillance in Smart Devices: A SCOUR Framework Analysis of
  Youth Privacy Implications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-10-28T05:10:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Austin Shouli, Yulia Bobkova, Ajay Kumar Shrestha</p>
    <p><b>Summary:</b> This paper investigates how smart devices covertly capture private
conversations and discusses in more in-depth the implications of this for youth
privacy. Using a structured review guided by the PRISMA methodology, the
analysis focuses on privacy concerns, data capture methods, data storage and
sharing practices, and proposed technical mitigations. To structure and
synthesize findings, we introduce the SCOUR framework, encompassing
Surveillance mechanisms, Consent and awareness, Operational data flow, Usage
and exploitation, and Regulatory and technical safeguards. Findings reveal that
smart devices have been covertly capturing personal data, especially with smart
toys and voice-activated smart gadgets built for youth. These issues are
worsened by unclear data collection practices and insufficient transparency in
smart device applications. Balancing privacy and utility in smart devices is
crucial, as youth are becoming more aware of privacy breaches and value their
personal data more. Strategies to improve regulatory and technical safeguards
are also provided. The review identifies research gaps and suggests future
directions. The limitations of this literature review are also explained. The
findings have significant implications for policy development and the
transparency of data collection for smart devices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.24807v1">Learning to Attack: Uncovering Privacy Risks in Sequential Data Releases</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-10-28T04:32:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ziyao Cui, Minxing Zhang, Jian Pei</p>
    <p><b>Summary:</b> Privacy concerns have become increasingly critical in modern AI and data
science applications, where sensitive information is collected, analyzed, and
shared across diverse domains such as healthcare, finance, and mobility. While
prior research has focused on protecting privacy in a single data release, many
real-world systems operate under sequential or continuous data publishing,
where the same or related data are released over time. Such sequential
disclosures introduce new vulnerabilities, as temporal correlations across
releases may enable adversaries to infer sensitive information that remains
hidden in any individual release. In this paper, we investigate whether an
attacker can compromise privacy in sequential data releases by exploiting
dependencies between consecutive publications, even when each individual
release satisfies standard privacy guarantees. To this end, we propose a novel
attack model that captures these sequential dependencies by integrating a
Hidden Markov Model with a reinforcement learning-based bi-directional
inference mechanism. This enables the attacker to leverage both earlier and
later observations in the sequence to infer private information. We instantiate
our framework in the context of trajectory data, demonstrating how an adversary
can recover sensitive locations from sequential mobility datasets. Extensive
experiments on Geolife, Porto Taxi, and SynMob datasets show that our model
consistently outperforms baseline approaches that treat each release
independently. The results reveal a fundamental privacy risk inherent to
sequential data publishing, where individually protected releases can
collectively leak sensitive information when analyzed temporally. These
findings underscore the need for new privacy-preserving frameworks that
explicitly model temporal dependencies, such as time-aware differential privacy
or sequential data obfuscation strategies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.23931v1">Differential Privacy: Gradient Leakage Attacks in Federated Learning
  Environments</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">  
  <p><b>Published on:</b> 2025-10-27T23:33:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Miguel Fernandez-de-Retana, Unai Zulaika, Rubén Sánchez-Corcuera, Aitor Almeida</p>
    <p><b>Summary:</b> Federated Learning (FL) allows for the training of Machine Learning models in
a collaborative manner without the need to share sensitive data. However, it
remains vulnerable to Gradient Leakage Attacks (GLAs), which can reveal private
information from the shared model updates. In this work, we investigate the
effectiveness of Differential Privacy (DP) mechanisms - specifically, DP-SGD
and a variant based on explicit regularization (PDP-SGD) - as defenses against
GLAs. To this end, we evaluate the performance of several computer vision
models trained under varying privacy levels on a simple classification task,
and then analyze the quality of private data reconstructions obtained from the
intercepted gradients in a simulated FL environment. Our results demonstrate
that DP-SGD significantly mitigates the risk of gradient leakage attacks,
albeit with a moderate trade-off in model utility. In contrast, PDP-SGD
maintains strong classification performance but proves ineffective as a
practical defense against reconstruction attacks. These findings highlight the
importance of empirically evaluating privacy mechanisms beyond their
theoretical guarantees, particularly in distributed learning scenarios where
information leakage may represent an unassumable critical threat to data
security and privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.23463v2">Differential Privacy as a Perk: Federated Learning over Multiple-Access
  Fading Channels with a Multi-Antenna Base Station</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2025-10-27T16:01:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hao Liang, Haifeng Wen, Kaishun Wu, Hong Xing</p>
    <p><b>Summary:</b> Federated Learning (FL) is a distributed learning paradigm that preserves
privacy by eliminating the need to exchange raw data during training. In its
prototypical edge instantiation with underlying wireless transmissions enabled
by analog over-the-air computing (AirComp), referred to as \emph{over-the-air
FL (AirFL)}, the inherent channel noise plays a unique role of \emph{frenemy}
in the sense that it degrades training due to noisy global aggregation while
providing a natural source of randomness for privacy-preserving mechanisms,
formally quantified by \emph{differential privacy (DP)}. It remains,
nevertheless, challenging to effectively harness such channel impairments, as
prior arts, under assumptions of either simple channel models or restricted
types of loss functions, mostly considering (local) DP enhancement with a
single-round or non-convergent bound on privacy loss. In this paper, we study
AirFL over multiple-access fading channels with a multi-antenna base station
(BS) subject to user-level DP requirements. Despite a recent study, which
claimed in similar settings that artificial noise (AN) must be injected to
ensure DP in general, we demonstrate, on the contrary, that DP can be gained as
a \emph{perk} even \emph{without} employing any AN. Specifically, we derive a
novel bound on DP that converges under general bounded-domain assumptions on
model parameters, along with a convergence bound with general smooth and
non-convex loss functions. Next, we optimize over receive beamforming and power
allocations to characterize the optimal convergence-privacy trade-offs, which
also reveal explicit conditions in which DP is achievable without compromising
training. Finally, our theoretical findings are validated by extensive
numerical results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.23427v1">PrivacyGuard: A Modular Framework for Privacy Auditing in Machine
  Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-10-27T15:33:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Luca Melis, Matthew Grange, Iden Kalemaj, Karan Chadha, Shengyuan Hu, Elena Kashtelyan, Will Bullock</p>
    <p><b>Summary:</b> The increasing deployment of Machine Learning (ML) models in sensitive
domains motivates the need for robust, practical privacy assessment tools.
PrivacyGuard is a comprehensive tool for empirical differential privacy (DP)
analysis, designed to evaluate privacy risks in ML models through
state-of-the-art inference attacks and advanced privacy measurement techniques.
To this end, PrivacyGuard implements a diverse suite of privacy attack --
including membership inference , extraction, and reconstruction attacks --
enabling both off-the-shelf and highly configurable privacy analyses. Its
modular architecture allows for the seamless integration of new attacks, and
privacy metrics, supporting rapid adaptation to emerging research advances. We
make PrivacyGuard available at
https://github.com/facebookresearch/PrivacyGuard.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.23274v1">Privacy-Preserving Semantic Communication over Wiretap Channels with
  Learnable Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2025-10-27T12:34:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Weixuan Chen, Qianqian Yang, Shuo Shao, Shunpu Tang, Zhiguo Shi, Shui Yu</p>
    <p><b>Summary:</b> While semantic communication (SemCom) improves transmission efficiency by
focusing on task-relevant information, it also raises critical privacy
concerns. Many existing secure SemCom approaches rely on restrictive or
impractical assumptions, such as favorable channel conditions for the
legitimate user or prior knowledge of the eavesdropper's model. To address
these limitations, this paper proposes a novel secure SemCom framework for
image transmission over wiretap channels, leveraging differential privacy (DP)
to provide approximate privacy guarantees. Specifically, our approach first
extracts disentangled semantic representations from source images using
generative adversarial network (GAN) inversion method, and then selectively
perturbs private semantic representations with approximate DP noise. Distinct
from conventional DP-based protection methods, we introduce DP noise with
learnable pattern, instead of traditional white Gaussian or Laplace noise,
achieved through adversarial training of neural networks (NNs). This design
mitigates the inherent non-invertibility of DP while effectively protecting
private information. Moreover, it enables explicitly controllable security
levels by adjusting the privacy budget according to specific security
requirements, which is not achieved in most existing secure SemCom approaches.
Experimental results demonstrate that, compared with the previous DP-based
method and direct transmission, the proposed method significantly degrades the
reconstruction quality for the eavesdropper, while introducing only slight
degradation in task performance. Under comparable security levels, our approach
achieves an LPIPS advantage of 0.06-0.29 and an FPPSR advantage of 0.10-0.86
for the legitimate user compared with the previous DP-based method.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.23024v1">A Multi-Store Privacy Measurement of Virtual Reality App Ecosystem</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-10-27T05:42:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chuan Yan, Zeng Li, Kunlin Cai, Liuhuo Wan, Ruomai Ren, Yiran Shen, Guangdong Bai</p>
    <p><b>Summary:</b> Virtual Reality (VR) has gained increasing traction among various domains in
recent years, with major companies such as Meta, Pico, and Microsoft launching
their application stores to support third-party developers in releasing their
applications (or simply apps). These apps offer rich functionality but
inherently collect privacy-sensitive data, such as user biometrics, behaviors,
and the surrounding environment. Nevertheless, there is still a lack of
domain-specific regulations to govern the data handling of VR apps, resulting
in significant variations in their privacy practices among app stores.
  In this work, we present the first comprehensive multi-store study of privacy
practices in the current VR app ecosystem, covering a large-scale dataset
involving 6,565 apps collected from five major app stores. We assess both
declarative and behavioral privacy practices of VR apps, using a multi-faceted
approach based on natural language processing, reverse engineering, and static
analysis. Our assessment reveals significant privacy compliance issues across
all stores, underscoring the premature status of privacy protection in this
rapidly growing ecosystem. For instance, one third of apps fail to declare
their use of sensitive data, and 21.5\% of apps neglect to provide valid
privacy policies. Our work sheds light on the status quo of privacy protection
within the VR app ecosystem for the first time. Our findings should raise an
alert to VR app developers and users, and encourage store operators to
implement stringent regulations on privacy compliance among VR apps.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.22387v1">Privacy-Aware Federated nnU-Net for ECG Page Digitization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-10-25T18:10:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nader Nemati</p>
    <p><b>Summary:</b> Deep neural networks can convert ECG page images into analyzable waveforms,
yet centralized training often conflicts with cross-institutional privacy and
deployment constraints. A cross-silo federated digitization framework is
presented that trains a full-model nnU-Net segmentation backbone without
sharing images and aggregates updates across sites under realistic non-IID
heterogeneity (layout, grid style, scanner profile, noise).
  The protocol integrates three standard server-side aggregators--FedAvg,
FedProx, and FedAdam--and couples secure aggregation with central, user-level
differential privacy to align utility with formal guarantees. Key features
include: (i) end-to-end full-model training and synchronization across clients;
(ii) secure aggregation so the server only observes a clipped, weighted sum
once a participation threshold is met; (iii) central Gaussian DP with Renyi
accounting applied post-aggregation for auditable user-level privacy; and (iv)
a calibration-aware digitization pipeline comprising page normalization, trace
segmentation, grid-leakage suppression, and vectorization to twelve-lead
signals.
  Experiments on ECG pages rendered from PTB-XL show consistently faster
convergence and higher late-round plateaus with adaptive server updates
(FedAdam) relative to FedAvg and FedProx, while approaching centralized
performance. The privacy mechanism maintains competitive accuracy while
preventing exposure of raw images or per-client updates, yielding deployable,
auditable guarantees suitable for multi-institution settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.21946v1">$δ$-STEAL: LLM Stealing Attack with Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">  
  <p><b>Published on:</b> 2025-10-24T18:19:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kieu Dang, Phung Lai, NhatHai Phan, Yelong Shen, Ruoming Jin, Abdallah Khreishah</p>
    <p><b>Summary:</b> Large language models (LLMs) demonstrate remarkable capabilities across
various tasks. However, their deployment introduces significant risks related
to intellectual property. In this context, we focus on model stealing attacks,
where adversaries replicate the behaviors of these models to steal services.
These attacks are highly relevant to proprietary LLMs and pose serious threats
to revenue and financial stability. To mitigate these risks, the watermarking
solution embeds imperceptible patterns in LLM outputs, enabling model
traceability and intellectual property verification. In this paper, we study
the vulnerability of LLM service providers by introducing $\delta$-STEAL, a
novel model stealing attack that bypasses the service provider's watermark
detectors while preserving the adversary's model utility. $\delta$-STEAL
injects noise into the token embeddings of the adversary's model during
fine-tuning in a way that satisfies local differential privacy (LDP)
guarantees. The adversary queries the service provider's model to collect
outputs and form input-output training pairs. By applying LDP-preserving noise
to these pairs, $\delta$-STEAL obfuscates watermark signals, making it
difficult for the service provider to determine whether its outputs were used,
thereby preventing claims of model theft. Our experiments show that
$\delta$-STEAL with lightweight modifications achieves attack success rates of
up to $96.95\%$ without significantly compromising the adversary's model
utility. The noise scale in LDP controls the trade-off between attack
effectiveness and model utility. This poses a significant risk, as even robust
watermarks can be bypassed, allowing adversaries to deceive watermark detectors
and undermine current intellectual property protection methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.21668v1">Privacy Guarantee for Nash Equilibrium Computation of Aggregative Games
  Based on Pointwise Maximal Leakage</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2025-10-24T17:24:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhaoyang Cheng, Guanpu Chen, Tobias J. Oechtering, Mikael Skoglund</p>
    <p><b>Summary:</b> Privacy preservation has served as a key metric in designing Nash equilibrium
(NE) computation algorithms. Although differential privacy (DP) has been widely
employed for privacy guarantees, it does not exploit prior distributional
knowledge of datasets and is ineffective in assessing information leakage for
correlated datasets. To address these concerns, we establish a pointwise
maximal leakage (PML) framework when computing NE in aggregative games. By
incorporating prior knowledge of players' cost function datasets, we obtain a
precise and computable upper bound of privacy leakage with PML guarantees. In
the entire view, we show PML refines DP by offering a tighter privacy
guarantee, enabling flexibility in designing NE computation. Also, in the
individual view, we reveal that the lower bound of PML can exceed the upper
bound of DP by constructing specific correlated datasets. The results emphasize
that PML is a more proper privacy measure than DP since the latter fails to
adequately capture privacy leakage in correlated datasets. Moreover, we conduct
experiments with adversaries who attempt to infer players' private information
to illustrate the effectiveness of our framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.21601v1">PTMF: A Privacy Threat Modeling Framework for IoT with Expert-Driven
  Threat Propagation Analysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-24T16:06:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Emmanuel Dare Alalade, Ashraf Matrawy</p>
    <p><b>Summary:</b> Previous studies on PTA have focused on analyzing privacy threats based on
the potential areas of occurrence and their likelihood of occurrence. However,
an in-depth understanding of the threat actors involved, their actions, and the
intentions that result in privacy threats is essential. In this paper, we
present a novel Privacy Threat Model Framework (PTMF) that analyzes privacy
threats through different phases.
  The PTMF development is motivated through the selected tactics from the MITRE
ATT\&CK framework and techniques from the LINDDUN privacy threat model, making
PTMF a privacy-centered framework. The proposed PTMF can be employed in various
ways, including analyzing the activities of threat actors during privacy
threats and assessing privacy risks in IoT systems, among others. In this
paper, we conducted a user study on 12 privacy threats associated with IoT by
developing a questionnaire based on PTMF and recruited experts from both
industry and academia in the fields of security and privacy to gather their
opinions. The collected data were analyzed and mapped to identify the threat
actors involved in the identification of IoT users (IU) and the remaining 11
privacy threats. Our observation revealed the top three threat actors and the
critical paths they used during the IU privacy threat, as well as the remaining
11 privacy threats. This study could provide a solid foundation for
understanding how and where privacy measures can be proactively and effectively
deployed in IoT systems to mitigate privacy threats based on the activities and
intentions of threat actors within these systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.21591v1">Privacy by Design: Aligning GDPR and Software Engineering Specifications
  with a Requirements Engineering Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-10-24T15:59:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Oleksandr Kosenkov, Ehsan Zabardast, Davide Fucci, Daniel Mendez, Michael Unterkalmsteiner</p>
    <p><b>Summary:</b> Context: Consistent requirements and system specifications are essential for
the compliance of software systems towards the General Data Protection
Regulation (GDPR). Both artefacts need to be grounded in the original text and
conjointly assure the achievement of privacy by design (PbD). Objectives: There
is little understanding of the perspectives of practitioners on specification
objectives and goals to address PbD. Existing approaches do not account for the
complex intersection between problem and solution space expressed in GDPR. In
this study we explore the demand for conjoint requirements and system
specification for PbD and suggest an approach to address this demand. Methods:
We reviewed secondary and related primary studies and conducted interviews with
practitioners to (1) investigate the state-of-practice and (2) understand the
underlying specification objectives and goals (e.g., traceability). We
developed and evaluated an approach for requirements and systems specification
for PbD, and evaluated it against the specification objectives. Results: The
relationship between problem and solution space, as expressed in GDPR, is
instrumental in supporting PbD. We demonstrate how our approach, based on the
modeling GDPR content with original legal concepts, contributes to
specification objectives of capturing legal knowledge, supporting specification
transparency, and traceability. Conclusion: GDPR demands need to be addressed
throughout different levels of abstraction in the engineering lifecycle to
achieve PbD. Legal knowledge specified in the GDPR text should be captured in
specifications to address the demands of different stakeholders and ensure
compliance. While our results confirm the suitability of our approach to
address practical needs, we also revealed specific needs for the future
effective operationalization of the approach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.20721v1">User Perceptions of Privacy and Helpfulness in LLM Responses to
  Privacy-Sensitive Scenarios</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-10-23T16:38:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaoyuan Wu, Roshni Kaushik, Wenkai Li, Lujo Bauer, Koichi Onoue</p>
    <p><b>Summary:</b> Large language models (LLMs) have seen rapid adoption for tasks such as
drafting emails, summarizing meetings, and answering health questions. In such
uses, users may need to share private information (e.g., health records,
contact details). To evaluate LLMs' ability to identify and redact such private
information, prior work developed benchmarks (e.g., ConfAIde, PrivacyLens) with
real-life scenarios. Using these benchmarks, researchers have found that LLMs
sometimes fail to keep secrets private when responding to complex tasks (e.g.,
leaking employee salaries in meeting summaries). However, these evaluations
rely on LLMs (proxy LLMs) to gauge compliance with privacy norms, overlooking
real users' perceptions. Moreover, prior work primarily focused on the
privacy-preservation quality of responses, without investigating nuanced
differences in helpfulness. To understand how users perceive the
privacy-preservation quality and helpfulness of LLM responses to
privacy-sensitive scenarios, we conducted a user study with 94 participants
using 90 scenarios from PrivacyLens. We found that, when evaluating identical
responses to the same scenario, users showed low agreement with each other on
the privacy-preservation quality and helpfulness of the LLM response. Further,
we found high agreement among five proxy LLMs, while each individual LLM had
low correlation with users' evaluations. These results indicate that the
privacy and helpfulness of LLM responses are often specific to individuals, and
proxy LLMs are poor estimates of how real users would perceive these responses
in privacy-sensitive scenarios. Our results suggest the need to conduct
user-centered studies on measuring LLMs' ability to help users while preserving
privacy. Additionally, future research could investigate ways to improve the
alignment between proxy LLMs and users for better estimation of users'
perceived privacy and utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.20300v1">Privacy Protection of Automotive Location Data Based on
  Format-Preserving Encryption of Geographical Coordinates</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-23T07:39:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haojie Ji, Long Jin, Haowen Li, Chongshi Xin, Te Hu</p>
    <p><b>Summary:</b> There are increasing risks of privacy disclosure when sharing the automotive
location data in particular functions such as route navigation, driving
monitoring and vehicle scheduling. These risks could lead to the attacks
including user behavior recognition, sensitive location inference and
trajectory reconstruction. In order to mitigate the data security risk caused
by the automotive location sharing, this paper proposes a high-precision
privacy protection mechanism based on format-preserving encryption (FPE) of
geographical coordinates. The automotive coordinate data key mapping mechanism
is designed to reduce to the accuracy loss of the geographical location data
caused by the repeated encryption and decryption. The experimental results
demonstrate that the average relative distance retention rate (RDR) reached
0.0844, and the number of hotspots in the critical area decreased by 98.9%
after encryption. To evaluate the accuracy loss of the proposed encryption
algorithm on automotive geographical location data, this paper presents the
experimental analysis of decryption accuracy, and the result indicates that the
decrypted coordinate data achieves a restoration accuracy of 100%. This work
presents a high-precision privacy protection method for automotive location
data, thereby providing an efficient data security solution for the sensitive
data sharing in autonomous driving.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.20243v1">HHEML: Hybrid Homomorphic Encryption for Privacy-Preserving Machine
  Learning on Edge</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-10-23T05:51:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yu Hin Chan, Hao Yang, Shiyu Shen, Xingyu Fan, Shengzhe Lyu, Patrick S. Y. Hung, Ray C. C. Cheung</p>
    <p><b>Summary:</b> Privacy-preserving machine learning (PPML) is an emerging topic to handle
secure machine learning inference over sensitive data in untrusted
environments. Fully homomorphic encryption (FHE) enables computation directly
on encrypted data on the server side, making it a promising approach for PPML.
However, it introduces significant communication and computation overhead on
the client side, making it impractical for edge devices. Hybrid homomorphic
encryption (HHE) addresses this limitation by combining symmetric encryption
(SE) with FHE to reduce the computational cost on the client side, and
combining with an FHE-friendly SE can also lessen the processing overhead on
the server side, making it a more balanced and efficient alternative. Our work
proposes a hardware-accelerated HHE architecture built around a lightweight
symmetric cipher optimized for FHE compatibility and implemented as a dedicated
hardware accelerator. To the best of our knowledge, this is the first design to
integrate an end-to-end HHE framework with hardware acceleration. Beyond this,
we also present several microarchitectural optimizations to achieve higher
performance and energy efficiency. The proposed work is integrated into a full
PPML pipeline, enabling secure inference with significantly lower latency and
power consumption than software implementations. Our contributions validate the
feasibility of low-power, hardware- accelerated HHE for edge deployment and
provide a hardware- software co-design methodology for building scalable,
secure machine learning systems in resource-constrained environments.
Experiments on a PYNQ-Z2 platform with the MNIST dataset show over a 50x
reduction in client-side encryption latency and nearly a 2x gain in hardware
throughput compared to existing FPGA-based HHE accelerators.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.21858v1">Privacy-preserving Decision-focused Learning for Multi-energy Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-23T04:20:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yangze Zhou, Ruiyang Yao, Dalin Qin, Yixiong Jia, Yi Wang</p>
    <p><b>Summary:</b> Decision-making for multi-energy system (MES) dispatch depends on accurate
load forecasting. Traditionally, load forecasting and decision-making for MES
are implemented separately. Forecasting models are typically trained to
minimize forecasting errors, overlooking their impact on downstream
decision-making. To address this, decision-focused learning (DFL) has been
studied to minimize decision-making costs instead. However, practical adoption
of DFL in MES faces significant challenges: the process requires sharing
sensitive load data and model parameters across multiple sectors, raising
serious privacy issues. To this end, we propose a privacy-preserving DFL
framework tailored for MES. Our approach introduces information masking to
safeguard private data while enabling recovery of decision variables and
gradients required for model training. To further enhance security for DFL, we
design a safety protocol combining matrix decomposition and homomorphic
encryption, effectively preventing collusion and unauthorized data access.
Additionally, we developed a privacy-preserving load pattern recognition
algorithm, enabling the training of specialized DFL models for heterogeneous
load patterns. Theoretical analysis and comprehensive case studies, including
real-world MES data, demonstrate that our framework not only protects privacy
but also consistently achieves lower average daily dispatch costs compared to
existing methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.20157v1">ADP-VRSGP: Decentralized Learning with Adaptive Differential Privacy via
  Variance-Reduced Stochastic Gradient Push</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-10-23T03:14:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaoming Wu, Teng Liu, Xin Wang, Ming Yang, Jiguo Yu</p>
    <p><b>Summary:</b> Differential privacy is widely employed in decentralized learning to
safeguard sensitive data by introducing noise into model updates. However,
existing approaches that use fixed-variance noise often degrade model
performance and reduce training efficiency. To address these limitations, we
propose a novel approach called decentralized learning with adaptive
differential privacy via variance-reduced stochastic gradient push (ADP-VRSGP).
This method dynamically adjusts both the noise variance and the learning rate
using a stepwise-decaying schedule, which accelerates training and enhances
final model performance while providing node-level personalized privacy
guarantees. To counteract the slowed convergence caused by large-variance noise
in early iterations, we introduce a progressive gradient fusion strategy that
leverages historical gradients. Furthermore, ADP-VRSGP incorporates
decentralized push-sum and aggregation techniques, making it particularly
suitable for time-varying communication topologies. Through rigorous
theoretical analysis, we demonstrate that ADP-VRSGP achieves robust convergence
with an appropriate learning rate, significantly improving training stability
and speed. Experimental results validate that our method outperforms existing
baselines across multiple scenarios, highlighting its efficacy in addressing
the challenges of privacy-preserving decentralized learning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.20007v1">zk-Agreements: A Privacy-Preserving Way to Establish Deterministic Trust
  in Confidential Agreements</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">  
  <p><b>Published on:</b> 2025-10-22T20:11:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> To-Wen Liu, Matthew Green</p>
    <p><b>Summary:</b> Digital transactions currently exceed trillions of dollars annually, yet
traditional paper-based agreements remain a bottleneck for automation,
enforceability, and dispute resolution. Natural language contracts introduce
ambiguity, require manual processing, and lack computational verifiability, all
of which hinder efficient digital commerce. Computable legal contracts,
expressed in machine-readable formats, offer a potential solution by enabling
automated execution and verification. Blockchain-based smart contracts further
strengthen enforceability and accelerate dispute resolution; however, current
implementations risk exposing sensitive agreement terms on public ledgers,
raising serious privacy and competitive intelligence concerns that limit
enterprise adoption.
  We introduce zk-agreements, a protocol designed to transition from
paper-based trust to cryptographic trust while preserving confidentiality. Our
design combines zero-knowledge proofs to protect private agreement terms,
secure two-party computation to enable private compliance evaluation, and smart
contracts to guarantee automated enforcement. Together, these components
achieve both privacy preservation and computational enforceability, resolving
the fundamental tension between transparency and confidentiality in
blockchain-based agreements.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.19979v1">SecureInfer: Heterogeneous TEE-GPU Architecture for Privacy-Critical
  Tensors for Large Language Model Deployment</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-10-22T19:17:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tushar Nayan, Ziqi Zhang, Ruimin Sun</p>
    <p><b>Summary:</b> With the increasing deployment of Large Language Models (LLMs) on mobile and
edge platforms, securing them against model extraction attacks has become a
pressing concern. However, protecting model privacy without sacrificing the
performance benefits of untrusted AI accelerators, such as GPUs, presents a
challenging trade-off. In this paper, we initiate the study of high-performance
execution on LLMs and present SecureInfer, a hybrid framework that leverages a
heterogeneous Trusted Execution Environments (TEEs)-GPU architecture to isolate
privacy-critical components while offloading compute-intensive operations to
untrusted accelerators. Building upon an outsourcing scheme, SecureInfer adopts
an information-theoretic and threat-informed partitioning strategy:
security-sensitive components, including non-linear layers, projection of
attention head, FNN transformations, and LoRA adapters, are executed inside an
SGX enclave, while other linear operations (matrix multiplication) are
performed on the GPU after encryption and are securely restored within the
enclave. We implement a prototype of SecureInfer using the LLaMA-2 model and
evaluate it across performance and security metrics. Our results show that
SecureInfer offers strong security guarantees with reasonable performance,
offering a practical solution for secure on-device model inference.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.19934v1">Mitigating Privacy-Utility Trade-off in Decentralized Federated Learning
  via $f$-Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">   
  <p><b>Published on:</b> 2025-10-22T18:01:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiang Li, Buxin Su, Chendi Wang, Qi Long, Weijie J. Su</p>
    <p><b>Summary:</b> Differentially private (DP) decentralized Federated Learning (FL) allows
local users to collaborate without sharing their data with a central server.
However, accurately quantifying the privacy budget of private FL algorithms is
challenging due to the co-existence of complex algorithmic components such as
decentralized communication and local updates. This paper addresses privacy
accounting for two decentralized FL algorithms within the $f$-differential
privacy ($f$-DP) framework. We develop two new $f$-DP-based accounting methods
tailored to decentralized settings: Pairwise Network $f$-DP (PN-$f$-DP), which
quantifies privacy leakage between user pairs under random-walk communication,
and Secret-based $f$-Local DP (Sec-$f$-LDP), which supports structured noise
injection via shared secrets. By combining tools from $f$-DP theory and Markov
chain concentration, our accounting framework captures privacy amplification
arising from sparse communication, local iterations, and correlated noise.
Experiments on synthetic and real datasets demonstrate that our methods yield
consistently tighter $(\epsilon,\delta)$ bounds and improved utility compared
to R\'enyi DP-based approaches, illustrating the benefits of $f$-DP in
decentralized privacy accounting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.19537v1">Privacy-Preserving Spiking Neural Networks: A Deep Dive into Encryption
  Parameter Optimisation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-22T12:43:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mahitha Pulivathi, Ana Fontes Rodrigues, Isibor Kennedy Ihianle, Andreas Oikonomou, Srinivas Boppu, Pedro Machado</p>
    <p><b>Summary:</b> Deep learning is widely applied to modern problems through neural networks,
but the growing computational and energy demands of these models have driven
interest in more efficient approaches. Spiking Neural Networks (SNNs), the
third generation of neural networks, mimic the brain's event-driven behaviour,
offering improved performance and reduced power use. At the same time, concerns
about data privacy during cloud-based model execution have led to the adoption
of cryptographic methods. This article introduces BioEncryptSNN, a spiking
neural network based encryption-decryption framework for secure and
noise-resilient data protection. Unlike conventional algorithms, BioEncryptSNN
converts ciphertext into spike trains and exploits temporal neural dynamics to
model encryption and decryption, optimising parameters such as key length,
spike timing, and synaptic connectivity. Benchmarked against AES-128, RSA-2048,
and DES, BioEncryptSNN preserved data integrity while achieving up to 4.1x
faster encryption and decryption than PyCryptodome's AES implementation. The
framework demonstrates scalability and adaptability across symmetric and
asymmetric ciphers, positioning SNNs as a promising direction for secure,
energy-efficient computing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.19026v1">Fusion of Machine Learning and Blockchain-based Privacy-Preserving
  Approach for Health Care Data in the Internet of Things</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-21T19:09:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Behnam Rezaei Bezanjani, Seyyed Hamid Ghafouri, Reza Gholamrezaei</p>
    <p><b>Summary:</b> In recent years, the rapid integration of Internet of Things (IoT) devices
into the healthcare sector has brought about revolutionary advancements in
patient care and data management. While these technological innovations hold
immense promise, they concurrently raise critical security concerns,
particularly in safeguarding medical data against potential cyber threats. The
sensitive nature of health-related information requires robust measures to
ensure the confidentiality, integrity, and availability of patient data in
IoT-enabled medical environments. Addressing the imperative need for enhanced
security in IoT-based healthcare systems, we propose a comprehensive method
encompassing three distinct phases. In the first phase, we implement
Blockchain-Enabled Request and Transaction Encryption to strengthen data
transaction security, providing an immutable and transparent framework. In the
second phase, we introduce a Request Pattern Recognition Check that leverages
diverse data sources to identify and block potential unauthorized access
attempts. Finally, the third phase incorporates Feature Selection and a BiLSTM
network to enhance the accuracy and efficiency of intrusion detection using
advanced machine learning techniques. We compared the simulation results of the
proposed method with three recent related methods: AIBPSF-IoMT, OMLIDS-PBIoT,
and AIMMFIDS. The evaluation criteria include detection rate, false alarm rate,
precision, recall, and accuracy - crucial benchmarks for assessing the overall
performance of intrusion detection systems. Our findings show that the proposed
method outperforms existing approaches across all evaluated criteria,
demonstrating its effectiveness in improving the security of IoT-based
healthcare systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.18568v1">Privacy-Preserving Healthcare Data in IoT: A Synergistic Approach with
  Deep Learning and Blockchain</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-21T12:21:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Behnam Rezaei Bezanjani, Seyyed Hamid Ghafouri, Reza Gholamrezaei</p>
    <p><b>Summary:</b> The integration of Internet of Things (IoT) devices in healthcare has
revolutionized patient care by enabling real-time monitoring, personalized
treatments, and efficient data management. However, this technological
advancement introduces significant security risks, particularly concerning the
confidentiality, integrity, and availability of sensitive medical data.
Traditional security measures are often insufficient to address the unique
challenges posed by IoT environments, such as heterogeneity, resource
constraints, and the need for real-time processing. To tackle these challenges,
we propose a comprehensive three-phase security framework designed to enhance
the security and reliability of IoT-enabled healthcare systems. In the first
phase, the framework assesses the reliability of IoT devices using a
reputation-based trust estimation mechanism, which combines device behavior
analytics with off-chain data storage to ensure scalability. The second phase
integrates blockchain technology with a lightweight proof-of-work mechanism,
ensuring data immutability, secure communication, and resistance to
unauthorized access. The third phase employs a lightweight Long Short-Term
Memory (LSTM) model for anomaly detection and classification, enabling
real-time identification of cyber threats. Simulation results demonstrate that
the proposed framework outperforms existing methods, achieving a 2% increase in
precision, accuracy, and recall, a 5% higher attack detection rate, and a 3%
reduction in false alarm rate. These improvements highlight the framework's
ability to address critical security concerns while maintaining scalability and
real-time performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.18493v1">One Size Fits All? A Modular Adaptive Sanitization Kit (MASK) for
  Customizable Privacy-Preserving Phone Scam Detection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">  
  <p><b>Published on:</b> 2025-10-21T10:30:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kangzhong Wang, Zitong Shen, Youqian Zhang, Michael MK Cheung, Xiapu Luo, Grace Ngai, Eugene Yujun Fu</p>
    <p><b>Summary:</b> Phone scams remain a pervasive threat to both personal safety and financial
security worldwide. Recent advances in large language models (LLMs) have
demonstrated strong potential in detecting fraudulent behavior by analyzing
transcribed phone conversations. However, these capabilities introduce notable
privacy risks, as such conversations frequently contain sensitive personal
information that may be exposed to third-party service providers during
processing. In this work, we explore how to harness LLMs for phone scam
detection while preserving user privacy. We propose MASK (Modular Adaptive
Sanitization Kit), a trainable and extensible framework that enables dynamic
privacy adjustment based on individual preferences. MASK provides a pluggable
architecture that accommodates diverse sanitization methods - from traditional
keyword-based techniques for high-privacy users to sophisticated neural
approaches for those prioritizing accuracy. We also discuss potential modeling
approaches and loss function designs for future development, enabling the
creation of truly personalized, privacy-aware LLM-based detection systems that
balance user trust and detection effectiveness, even beyond phone scam context.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.18379v1">Uniformity Testing under User-Level Local Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Discrete Mathematics-04E762">
  <p><b>Published on:</b> 2025-10-21T07:52:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Clément L. Canonne, Abigail Gentle, Vikrant Singhal</p>
    <p><b>Summary:</b> We initiate the study of distribution testing under \emph{user-level} local
differential privacy, where each of $n$ users contributes $m$ samples from the
unknown underlying distribution. This setting, albeit very natural, is
significantly more challenging that the usual locally private setting, as for
the same parameter $\varepsilon$ the privacy guarantee must now apply to a full
batch of $m$ data points. While some recent work consider distribution
\emph{learning} in this user-level setting, nothing was known for even the most
fundamental testing task, uniformity testing (and its generalization, identity
testing).
  We address this gap, by providing (nearly) sample-optimal user-level LDP
algorithms for uniformity and identity testing. Motivated by practical
considerations, our main focus is on the private-coin, symmetric setting, which
does not require users to share a common random seed nor to have been assigned
a globally unique identifier.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.18109v1">PrivaDE: Privacy-preserving Data Evaluation for Blockchain-based Data
  Marketplaces</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-10-20T21:14:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wan Ki Wong, Sahel Torkamani, Michele Ciampi, Rik Sarkar</p>
    <p><b>Summary:</b> Evaluating the relevance of data is a critical task for model builders
seeking to acquire datasets that enhance model performance. Ideally, such
evaluation should allow the model builder to assess the utility of candidate
data without exposing proprietary details of the model. At the same time, data
providers must be assured that no information about their data - beyond the
computed utility score - is disclosed to the model builder.
  In this paper, we present PrivaDE, a cryptographic protocol for
privacy-preserving utility scoring and selection of data for machine learning.
While prior works have proposed data evaluation protocols, our approach
advances the state of the art through a practical, blockchain-centric design.
Leveraging the trustless nature of blockchains, PrivaDE enforces
malicious-security guarantees and ensures strong privacy protection for both
models and datasets. To achieve efficiency, we integrate several techniques -
including model distillation, model splitting, and cut-and-choose
zero-knowledge proofs - bringing the runtime to a practical level. Furthermore,
we propose a unified utility scoring function that combines empirical loss,
predictive entropy, and feature-space diversity, and that can be seamlessly
integrated into active-learning workflows. Evaluation shows that PrivaDE
performs data evaluation effectively, achieving online runtimes within 15
minutes even for models with millions of parameters.
  Our work lays the foundation for fair and automated data marketplaces in
decentralized machine learning ecosystems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.17480v1">Unified Privacy Guarantees for Decentralized Learning via Matrix
  Factorization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-10-20T12:24:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aurélien Bellet, Edwige Cyffers, Davide Frey, Romaric Gaudel, Dimitri Lerévérend, François Taïani</p>
    <p><b>Summary:</b> Decentralized Learning (DL) enables users to collaboratively train models
without sharing raw data by iteratively averaging local updates with neighbors
in a network graph. This setting is increasingly popular for its scalability
and its ability to keep data local under user control. Strong privacy
guarantees in DL are typically achieved through Differential Privacy (DP), with
results showing that DL can even amplify privacy by disseminating noise across
peer-to-peer communications. Yet in practice, the observed privacy-utility
trade-off often appears worse than in centralized training, which may be due to
limitations in current DP accounting methods for DL. In this paper, we show
that recent advances in centralized DP accounting based on Matrix Factorization
(MF) for analyzing temporal noise correlations can also be leveraged in DL. By
generalizing existing MF results, we show how to cast both standard DL
algorithms and common trust models into a unified formulation. This yields
tighter privacy accounting for existing DP-DL algorithms and provides a
principled way to develop new ones. To demonstrate the approach, we introduce
MAFALDA-SGD, a gossip-based DL algorithm with user-level correlated noise that
outperforms existing methods on synthetic and real-world graphs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.17372v1">Beyond Real Faces: Synthetic Datasets Can Achieve Reliable Recognition
  Performance without Privacy Compromise</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-10-20T10:08:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Paweł Borsukiewicz, Fadi Boutros, Iyiola E. Olatunji, Charles Beumier, Wendkûuni C. Ouedraogo, Jacques Klein, Tegawendé F. Bissyandé</p>
    <p><b>Summary:</b> The deployment of facial recognition systems has created an ethical dilemma:
achieving high accuracy requires massive datasets of real faces collected
without consent, leading to dataset retractions and potential legal liabilities
under regulations like GDPR. While synthetic facial data presents a promising
privacy-preserving alternative, the field lacks comprehensive empirical
evidence of its viability. This study addresses this critical gap through
extensive evaluation of synthetic facial recognition datasets. We present a
systematic literature review identifying 25 synthetic facial recognition
datasets (2018-2025), combined with rigorous experimental validation. Our
methodology examines seven key requirements for privacy-preserving synthetic
data: identity leakage prevention, intra-class variability, identity
separability, dataset scale, ethical data sourcing, bias mitigation, and
benchmark reliability. Through experiments involving over 10 million synthetic
samples, extended by a comparison of results reported on five standard
benchmarks, we provide the first comprehensive empirical assessment of
synthetic data's capability to replace real datasets. Best-performing synthetic
datasets (VariFace, VIGFace) achieve recognition accuracies of 95.67% and
94.91% respectively, surpassing established real datasets including
CASIA-WebFace (94.70%). While those images remain private, publicly available
alternatives Vec2Face (93.52%) and CemiFace (93.22%) come close behind. Our
findings reveal that they ensure proper intra-class variability while
maintaining identity separability. Demographic bias analysis shows that, even
though synthetic data inherits limited biases, it offers unprecedented control
for bias mitigation through generation parameters. These results establish
synthetic facial data as a scientifically viable and ethically imperative
alternative for facial recognition research.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.17348v1">Optimal Best Arm Identification under Differential Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-10-20T09:46:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marc Jourdan, Achraf Azize</p>
    <p><b>Summary:</b> Best Arm Identification (BAI) algorithms are deployed in data-sensitive
applications, such as adaptive clinical trials or user studies. Driven by the
privacy concerns of these applications, we study the problem of
fixed-confidence BAI under global Differential Privacy (DP) for Bernoulli
distributions. While numerous asymptotically optimal BAI algorithms exist in
the non-private setting, a significant gap remains between the best lower and
upper bounds in the global DP setting. This work reduces this gap to a small
multiplicative constant, for any privacy budget $\epsilon$. First, we provide a
tighter lower bound on the expected sample complexity of any $\delta$-correct
and $\epsilon$-global DP strategy. Our lower bound replaces the
Kullback-Leibler (KL) divergence in the transportation cost used by the
non-private characteristic time with a new information-theoretic quantity that
optimally trades off between the KL divergence and the Total Variation distance
scaled by $\epsilon$. Second, we introduce a stopping rule based on these
transportation costs and a private estimator of the means computed using an
arm-dependent geometric batching. En route to proving the correctness of our
stopping rule, we derive concentration results of independent interest for the
Laplace distribution and for the sum of Bernoulli and Laplace distributions.
Third, we propose a Top Two sampling rule based on these transportation costs.
For any budget $\epsilon$, we show an asymptotic upper bound on its expected
sample complexity that matches our lower bound to a multiplicative constant
smaller than $8$. Our algorithm outperforms existing $\delta$-correct and
$\epsilon$-global DP BAI algorithms for different values of $\epsilon$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.17162v1">ALPINE: A Lightweight and Adaptive Privacy-Decision Agent Framework for
  Dynamic Edge Crowdsensing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-10-20T05:03:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guanjie Cheng, Siyang Liu, Junqin Huang, Xinkui Zhao, Yin Wang, Mengying Zhu, Linghe Kong, Shuiguang Deng</p>
    <p><b>Summary:</b> Mobile edge crowdsensing (MECS) systems continuously generate and transmit
user data in dynamic, resource-constrained environments, exposing users to
significant privacy threats. In practice, many privacy-preserving mechanisms
build on differential privacy (DP). However, static DP mechanisms often fail to
adapt to evolving risks, for example, shifts in adversarial capabilities,
resource constraints and task requirements, resulting in either excessive noise
or inadequate protection. To address this challenge, we propose ALPINE, a
lightweight, adaptive framework that empowers terminal devices to autonomously
adjust differential privacy levels in real time. ALPINE operates as a
closed-loop control system consisting of four modules: dynamic risk perception,
privacy decision via twin delayed deep deterministic policy gradient (TD3),
local privacy execution and performance verification from edge nodes. Based on
environmental risk assessments, we design a reward function that balances
privacy gains, data utility and energy cost, guiding the TD3 agent to
adaptively tune noise magnitude across diverse risk scenarios and achieve a
dynamic equilibrium among privacy, utility and cost. Both the collaborative
risk model and pretrained TD3-based agent are designed for low-overhead
deployment. Extensive theoretical analysis and real-world simulations
demonstrate that ALPINE effectively mitigates inference attacks while
preserving utility and cost, making it practical for large-scale edge
applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.16744v1">Cryptanalysis of a Privacy-Preserving Ride-Hailing Service from NSS 2022</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-19T08:05:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Srinivas Vivek</p>
    <p><b>Summary:</b> Ride-Hailing Services (RHS) match a ride request initiated by a rider with a
suitable driver responding to the ride request. A Privacy-Preserving RHS
(PP-RHS) aims to facilitate ride matching while ensuring the privacy of riders'
and drivers' location data w.r.t. the Service Provider (SP). At NSS 2022, Xie
et al. proposed a PP-RHS. In this work, we demonstrate a passive attack on
their PP-RHS protocol. Our attack allows the SP to completely recover the
locations of the rider as well as that of the responding drivers in every ride
request. Further, our attack is very efficient as it is independent of the
security parameter.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.16687v1">High-Dimensional Privacy-Utility Dynamics of Noisy Stochastic Gradient
  Descent on Least Squares</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-10-19T02:28:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shurong Lin, Eric D. Kolaczyk, Adam Smith, Elliot Paquette</p>
    <p><b>Summary:</b> The interplay between optimization and privacy has become a central theme in
privacy-preserving machine learning. Noisy stochastic gradient descent (SGD)
has emerged as a cornerstone algorithm, particularly in large-scale settings.
These variants of gradient methods inject carefully calibrated noise into each
update to achieve differential privacy, the gold standard notion of rigorous
privacy guarantees. Prior work primarily provides various bounds on statistical
risk and privacy loss for noisy SGD, yet the \textit{exact} behavior of the
process remains unclear, particularly in high-dimensional settings. This work
leverages a diffusion approach to analyze noisy SGD precisely, providing a
continuous-time perspective that captures both statistical risk evolution and
privacy loss dynamics in high dimensions. Moreover, we study a variant of noisy
SGD that does not require explicit knowledge of gradient sensitivity, unlike
existing work that assumes or enforces sensitivity through gradient clipping.
Specifically, we focus on the least squares problem with $\ell_2$
regularization.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.16331v1">Efficient and Privacy-Preserving Binary Dot Product via Multi-Party
  Computation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computational Complexity-5BC0EB">
  <p><b>Published on:</b> 2025-10-18T03:35:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fatemeh Jafarian Dehkordi, Elahe Vedadi, Alireza Feizbakhsh, Yasaman Keshtkarjahromi, Hulya Seferoglu</p>
    <p><b>Summary:</b> Striking a balance between protecting data privacy and enabling collaborative
computation is a critical challenge for distributed machine learning. While
privacy-preserving techniques for federated learning have been extensively
developed, methods for scenarios involving bitwise operations, such as
tree-based vertical federated learning (VFL), are still underexplored.
Traditional mechanisms, including Shamir's secret sharing and multi-party
computation (MPC), are not optimized for bitwise operations over binary data,
particularly in settings where each participant holds a different part of the
binary vector. This paper addresses the limitations of existing methods by
proposing a novel binary multi-party computation (BiMPC) framework. The BiMPC
mechanism facilitates privacy-preserving bitwise operations, with a particular
focus on dot product computations of binary vectors, ensuring the privacy of
each individual bit. The core of BiMPC is a novel approach called Dot Product
via Modular Addition (DoMA), which uses regular and modular additions for
efficient binary dot product calculation. To ensure privacy, BiMPC uses random
masking in a higher field for linear computations and a three-party oblivious
transfer (triot) protocol for non-linear binary operations. The privacy
guarantees of the BiMPC framework are rigorously analyzed, demonstrating its
efficiency and scalability in distributed settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.16083v1">PassREfinder-FL: Privacy-Preserving Credential Stuffing Risk Prediction
  via Graph-Based Federated Learning for Representing Password Reuse between
  Websites</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-17T14:59:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jaehan Kim, Minkyoo Song, Minjae Seo, Youngjin Jin, Seungwon Shin, Jinwoo Kim</p>
    <p><b>Summary:</b> Credential stuffing attacks have caused significant harm to online users who
frequently reuse passwords across multiple websites. While prior research has
attempted to detect users with reused passwords or identify malicious login
attempts, existing methods often compromise usability by restricting password
creation or website access, and their reliance on complex account-sharing
mechanisms hinders real-world deployment. To address these limitations, we
propose PassREfinder-FL, a novel framework that predicts credential stuffing
risks across websites. We introduce the concept of password reuse relations --
defined as the likelihood of users reusing passwords between websites -- and
represent them as edges in a website graph. Using graph neural networks (GNNs),
we perform a link prediction task to assess credential reuse risk between
sites. Our approach scales to a large number of arbitrary websites by
incorporating public website information and linking newly observed websites as
nodes in the graph. To preserve user privacy, we extend PassREfinder-FL with a
federated learning (FL) approach that eliminates the need to share user
sensitive information across administrators. Evaluation on a real-world dataset
of 360 million breached accounts from 22,378 websites shows that
PassREfinder-FL achieves an F1-score of 0.9153 in the FL setting. We further
validate that our FL-based GNN achieves a 4-11% performance improvement over
other state-of-the-art GNN models through an ablation study. Finally, we
demonstrate that the predicted results can be used to quantify password reuse
likelihood as actionable risk scores.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.15186v1">MAGPIE: A benchmark for Multi-AGent contextual PrIvacy Evaluation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-10-16T23:12:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gurusha Juneja, Jayanth Naga Sai Pasupulati, Alon Albalak, Wenyue Hua, William Yang Wang</p>
    <p><b>Summary:</b> A core challenge for autonomous LLM agents in collaborative settings is
balancing robust privacy understanding and preservation alongside task
efficacy. Existing privacy benchmarks only focus on simplistic, single-turn
interactions where private information can be trivially omitted without
affecting task outcomes. In this paper, we introduce MAGPIE (Multi-AGent
contextual PrIvacy Evaluation), a novel benchmark of 200 high-stakes tasks
designed to evaluate privacy understanding and preservation in multi-agent
collaborative, non-adversarial scenarios. MAGPIE integrates private information
as essential for task resolution, forcing agents to balance effective
collaboration with strategic information control. Our evaluation reveals that
state-of-the-art agents, including GPT-5 and Gemini 2.5-Pro, exhibit
significant privacy leakage, with Gemini 2.5-Pro leaking up to 50.7% and GPT-5
up to 35.1% of the sensitive information even when explicitly instructed not
to. Moreover, these agents struggle to achieve consensus or task completion and
often resort to undesirable behaviors such as manipulation and power-seeking
(e.g., Gemini 2.5-Pro demonstrating manipulation in 38.2% of the cases). These
findings underscore that current LLM agents lack robust privacy understanding
and are not yet adequately aligned to simultaneously preserve privacy and
maintain effective collaboration in complex environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.15112v1">AndroByte: LLM-Driven Privacy Analysis through Bytecode Summarization
  and Dynamic Dataflow Call Graph Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-16T20:10:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mst Eshita Khatun, Lamine Noureddine, Zhiyong Sui, Aisha Ali-Gombe</p>
    <p><b>Summary:</b> With the exponential growth in mobile applications, protecting user privacy
has become even more crucial. Android applications are often known for
collecting, storing, and sharing sensitive user information such as contacts,
location, camera, and microphone data often without the user's clear consent or
awareness raising significant privacy risks and exposure. In the context of
privacy assessment, dataflow analysis is particularly valuable for identifying
data usage and potential leaks. Traditionally, this type of analysis has relied
on formal methods, heuristics, and rule-based matching. However, these
techniques are often complex to implement and prone to errors, such as taint
explosion for large programs. Moreover, most existing Android dataflow analysis
methods depend heavily on predefined list of sinks, limiting their flexibility
and scalability. To address the limitations of these existing techniques, we
propose AndroByte, an AI-driven privacy analysis tool that leverages LLM
reasoning on bytecode summarization to dynamically generate accurate and
explainable dataflow call graphs from static code analysis. AndroByte achieves
a significant F\b{eta}-Score of 89% in generating dynamic dataflow call graphs
on the fly, outperforming the effectiveness of traditional tools like FlowDroid
and Amandroid in leak detection without relying on predefined propagation rules
or sink lists. Moreover, AndroByte's iterative bytecode summarization provides
comprehensive and explainable insights into dataflow and leak detection,
achieving high, quantifiable scores based on the G-Eval metric.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.16054v1">PrivacyPAD: A Reinforcement Learning Framework for Dynamic Privacy-Aware
  Delegation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-10-16T19:38:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zheng Hui, Yijiang River Dong, Sanhanat Sivapiromrat, Ehsan Shareghi, Nigel Collier</p>
    <p><b>Summary:</b> When users submit queries to Large Language Models (LLMs), their prompts can
often contain sensitive data, forcing a difficult choice: Send the query to a
powerful proprietary LLM providers to achieving state-of-the-art performance
and risk data exposure, or relying on smaller, local models guarantees data
privacy but often results in a degradation of task performance. Prior
approaches have relied on static pipelines that use LLM rewriting, which
shatters linguistic coherence and indiscriminately removes privacy-sensitive
information, including task-critical content. We reformulate this challenge
(Privacy-Conscious Delegation) as a sequential decision-making problem and
introduce a novel reinforcement learning (RL) framework called PrivacyPAD to
solve it. Our framework trains an agent to dynamically route text chunks,
learning a policy that optimally balances the trade-off between privacy leakage
and task performance. It implicitly distinguishes between replaceable
Personally Identifiable Information (PII) (which it shields locally) and
task-critical PII (which it strategically sends to the remote model for maximal
utility). To validate our approach in complex scenarios, we also introduce a
new medical dataset with high PII density. Our framework achieves a new
state-of-the-art on the privacy-utility frontier, demonstrating the necessity
of learned, adaptive policies for deploying LLMs in sensitive environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.15083v1">SMOTE and Mirrors: Exposing Privacy Leakage from Synthetic Minority
  Oversampling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-16T18:55:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Georgi Ganev, Reza Nazari, Rees Davison, Amir Dizche, Xinmin Wu, Ralph Abbey, Jorge Silva, Emiliano De Cristofaro</p>
    <p><b>Summary:</b> The Synthetic Minority Over-sampling Technique (SMOTE) is one of the most
widely used methods for addressing class imbalance and generating synthetic
data. Despite its popularity, little attention has been paid to its privacy
implications; yet, it is used in the wild in many privacy-sensitive
applications. In this work, we conduct the first systematic study of privacy
leakage in SMOTE: We begin by showing that prevailing evaluation practices,
i.e., naive distinguishing and distance-to-closest-record metrics, completely
fail to detect any leakage and that membership inference attacks (MIAs) can be
instantiated with high accuracy. Then, by exploiting SMOTE's geometric
properties, we build two novel attacks with very limited assumptions:
DistinSMOTE, which perfectly distinguishes real from synthetic records in
augmented datasets, and ReconSMOTE, which reconstructs real minority records
from synthetic datasets with perfect precision and recall approaching one under
realistic imbalance ratios. We also provide theoretical guarantees for both
attacks. Experiments on eight standard imbalanced datasets confirm the
practicality and effectiveness of these attacks. Overall, our work reveals that
SMOTE is inherently non-private and disproportionately exposes minority
records, highlighting the need to reconsider its use in privacy-sensitive
applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.14894v1">Secure Sparse Matrix Multiplications and their Applications to
  Privacy-Preserving Machine Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-10-16T17:12:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marc Damie, Florian Hahn, Andreas Peter, Jan Ramon</p>
    <p><b>Summary:</b> To preserve privacy, multi-party computation (MPC) enables executing Machine
Learning (ML) algorithms on secret-shared or encrypted data. However, existing
MPC frameworks are not optimized for sparse data. This makes them unsuitable
for ML applications involving sparse data, e.g., recommender systems or
genomics. Even in plaintext, such applications involve high-dimensional sparse
data, that cannot be processed without sparsity-related optimizations due to
prohibitively large memory requirements.
  Since matrix multiplication is central in ML algorithms, we propose MPC
algorithms to multiply secret sparse matrices. On the one hand, our algorithms
avoid the memory issues of the "dense" data representation of classic secure
matrix multiplication algorithms. On the other hand, our algorithms can
significantly reduce communication costs (some experiments show a factor 1000)
for realistic problem sizes. We validate our algorithms in two ML applications
in which existing protocols are impractical.
  An important question when developing MPC algorithms is what assumptions can
be made. In our case, if the number of non-zeros in a row is a sensitive piece
of information then a short runtime may reveal that the number of non-zeros is
small. Existing approaches make relatively simple assumptions, e.g., that there
is a universal upper bound to the number of non-zeros in a row. This often
doesn't align with statistical reality, in a lot of sparse datasets the amount
of data per instance satisfies a power law. We propose an approach which allows
adopting a safe upper bound on the distribution of non-zeros in rows/columns of
sparse matrices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.14312v1">Terrarium: Revisiting the Blackboard for Multi-Agent Safety, Privacy,
  and Security Studies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2025-10-16T05:19:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mason Nakamura, Abhinav Kumar, Saaduddin Mahmud, Sahar Abdelnabi, Shlomo Zilberstein, Eugene Bagdasarian</p>
    <p><b>Summary:</b> A multi-agent system (MAS) powered by large language models (LLMs) can
automate tedious user tasks such as meeting scheduling that requires
inter-agent collaboration. LLMs enable nuanced protocols that account for
unstructured private data, user constraints, and preferences. However, this
design introduces new risks, including misalignment and attacks by malicious
parties that compromise agents or steal user data. In this paper, we propose
the Terrarium framework for fine-grained study on safety, privacy, and security
in LLM-based MAS. We repurpose the blackboard design, an early approach in
multi-agent systems, to create a modular, configurable testbed for multi-agent
collaboration. We identify key attack vectors such as misalignment, malicious
agents, compromised communication, and data poisoning. We implement three
collaborative MAS scenarios with four representative attacks to demonstrate the
framework's flexibility. By providing tools to rapidly prototype, evaluate, and
iterate on defenses and designs, Terrarium aims to accelerate progress toward
trustworthy multi-agent systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.14151v1">Privacy-Preserving and Incentive-Driven Relay-Based Framework for
  Cross-Domain Blockchain Interoperability</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-10-15T22:59:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Saeed Moradi, Koosha Esmaeilzadeh Khorasani, Sara Rouhani</p>
    <p><b>Summary:</b> Interoperability is essential for transforming blockchains from isolated
networks into collaborative ecosystems, unlocking their full potential. While
significant progress has been made in public blockchain interoperability,
bridging permissioned and permissionless blockchains poses unique challenges
due to differences in access control, architectures, and security requirements.
This paper introduces a blockchain-agnostic framework to enable
interoperability between permissioned and permissionless networks. Leveraging
cryptographic techniques, the framework ensures secure data exchanges. Its
lightweight architectural design simplifies implementation and maintenance,
while the integration of Clover and Dandelion++ protocols enhances transaction
anonymity. Performance evaluations demonstrate the framework's effectiveness in
achieving secure and efficient interoperability by measuring the forwarding
time, the throughput, the availability, and their collusion impact of the
system across heterogeneous blockchain ecosystems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.13528v1">Experiments \& Analysis of Privacy-Preserving SQL Query Sanitization
  Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2025-10-15T13:21:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Loïs Ecoffet, Veronika Rehn-Sonigo, Jean-François Couchot, Catuscia Palamidessi</p>
    <p><b>Summary:</b> Analytical SQL queries are essential for extracting insights from relational
databases but concurrently introduce significant privacy risks by potentially
exposing sensitive information. To mitigate these risks, numerous query
sanitization systems have been developed, employing diverse approaches that
create a complex landscape for both researchers and practitioners. These
systems vary fundamentally in their design, including the underlying privacy
model, such as k-anonymity or Differential Privacy; the protected privacy unit,
whether at the tuple- or user-level; and the software architecture, which can
be proxy-based or integrated. This paper provides a systematic classification
of state-of-the-art SQL sanitization systems based on these qualitative
criteria and the scope of queries they support. Furthermore, we present a
quantitative analysis of leading systems, empirically measuring the trade-offs
between data utility, query execution overhead, and privacy guarantees across a
range of analytical queries. This work offers a structured overview and
performance assessment intended to clarify the capabilities and limitations of
current privacy-preserving database technologies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.13512v1">Offline and Online KL-Regularized RLHF under Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-10-15T13:04:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yulian Wu, Rushil Thareja, Praneeth Vepakomma, Francesco Orabona</p>
    <p><b>Summary:</b> In this paper, we study the offline and online settings of reinforcement
learning from human feedback (RLHF) with KL-regularization -- a widely used
objective function in large language model alignment -- under the $\epsilon$
local differential privacy ($\epsilon$-LDP) model on the label of the human
preference. In the offline setting, we design an algorithm based on the
principle of pessimism and derive a new suboptimality gap of
$\tilde{O}(1/[(e^\epsilon-1)^2 n])$ on the KL-regularized objective under
single-policy concentrability. We also prove its optimality by providing a
matching lower bound where $n$ is the sample size.
  In the online setting, we are the first one to theoretically investigate the
problem of KL-regularized RLHF with LDP. We design an optimism-based algorithm
and derive a logarithmic regret bound of $O(d_{\mathcal{F}}\log
(N_{\mathcal{F}}\cdot T) /(e^\epsilon-1)^2 )$, where $T$ is the total time
step, $N_{\mathcal{F}}$ is cardinality of the reward function space
$\mathcal{F}$ and $d_{\mathcal{F}}$ is a variant of eluder dimension for RLHF.
As a by-product of our analysis, our results also imply the first analysis for
online KL-regularized RLHF without privacy. We implement our algorithm in the
offline setting to verify our theoretical results and release our open source
code at: https://github.com/rushil-thareja/PPKL-RLHF-Official.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.13468v1">Privacy, freedom of expression, and the right to be forgotten in Europe</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-10-15T12:13:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stefan Kulk, Frederik Zuiderveen Borgesius</p>
    <p><b>Summary:</b> In this chapter we discuss the relation between privacy and freedom of
expression in Europe. In principle, the two rights have equal weight in Europe
- which right prevails depends on the circumstances of a case. We use the
Google Spain judgment of the Court of Justice of the European Union, sometimes
called the 'right to be forgotten' judgment, to illustrate the difficulties
when balancing the two rights. The court decided in Google Spain that people
have, under certain conditions, the right to have search results for their name
delisted. We discuss how Google and Data Protection Authorities deal with such
delisting requests in practice. Delisting requests illustrate that balancing
privacy and freedom of expression interests will always remain difficult.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.13136v1">Privacy-Aware Framework of Robust Malware Detection in Indoor Robots:
  Hybrid Quantum Computing and Deep Neural Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-15T04:25:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tan Le, Van Le, Sachin Shetty</p>
    <p><b>Summary:</b> Indoor robotic systems within Cyber-Physical Systems (CPS) are increasingly
exposed to Denial of Service (DoS) attacks that compromise localization,
control and telemetry integrity. We propose a privacy-aware malware detection
framework for indoor robotic systems, which leverages hybrid quantum computing
and deep neural networks to counter DoS threats in CPS, while preserving
privacy information. By integrating quantum-enhanced feature encoding with
dropout-optimized deep learning, our architecture achieves up to 95.2%
detection accuracy under privacy-constrained conditions. The system operates
without handcrafted thresholds or persistent beacon data, enabling scalable
deployment in adversarial environments. Benchmarking reveals robust
generalization, interpretability and resilience against training instability
through modular circuit design. This work advances trustworthy AI for secure,
autonomous CPS operations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.12908v1">Local Differential Privacy for Federated Learning with Fixed Memory
  Usage and Per-Client Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-14T18:32:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rouzbeh Behnia, Jeremiah Birrell, Arman Riasi, Reza Ebrahimi, Kaushik Dutta, Thang Hoang</p>
    <p><b>Summary:</b> Federated learning (FL) enables organizations to collaboratively train models
without sharing their datasets. Despite this advantage, recent studies show
that both client updates and the global model can leak private information,
limiting adoption in sensitive domains such as healthcare. Local differential
privacy (LDP) offers strong protection by letting each participant privatize
updates before transmission. However, existing LDP methods were designed for
centralized training and introduce challenges in FL, including high resource
demands that can cause client dropouts and the lack of reliable privacy
guarantees under asynchronous participation. These issues undermine model
generalizability, fairness, and compliance with regulations such as HIPAA and
GDPR. To address them, we propose L-RDP, a DP method designed for LDP that
ensures constant, lower memory usage to reduce dropouts and provides rigorous
per-client privacy guarantees by accounting for intermittent participation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.12780v1">Content Anonymization for Privacy in Long-form Audio</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-10-14T17:52:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Cristina Aggazzotti, Ashi Garg, Zexin Cai, Nicholas Andrews</p>
    <p><b>Summary:</b> Voice anonymization techniques have been found to successfully obscure a
speaker's acoustic identity in short, isolated utterances in benchmarks such as
the VoicePrivacy Challenge. In practice, however, utterances seldom occur in
isolation: long-form audio is commonplace in domains such as interviews, phone
calls, and meetings. In these cases, many utterances from the same speaker are
available, which pose a significantly greater privacy risk: given multiple
utterances from the same speaker, an attacker could exploit an individual's
vocabulary, syntax, and turns of phrase to re-identify them, even when their
voice is completely disguised. To address this risk, we propose new content
anonymization approaches. Our approach performs a contextual rewriting of the
transcripts in an ASR-TTS pipeline to eliminate speaker-specific style while
preserving meaning. We present results in a long-form telephone conversation
setting demonstrating the effectiveness of a content-based attack on
voice-anonymized speech. Then we show how the proposed content-based
anonymization methods can mitigate this risk while preserving speech utility.
Overall, we find that paraphrasing is an effective defense against
content-based attacks and recommend that stakeholders adopt this step to ensure
anonymity in long-form audio.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.12549v1">Privacy-Preserving Distributed Estimation with Limited Data Rate</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2025-10-14T14:13:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jieming Ke, Jimin Wang, Ji-Feng Zhang</p>
    <p><b>Summary:</b> This paper focuses on the privacy-preserving distributed estimation problem
with a limited data rate, where the observations are the sensitive information.
Specifically, a binary-valued quantizer-based privacy-preserving distributed
estimation algorithm is developed, which improves the algorithm's
privacy-preserving capability and simultaneously reduces the communication
costs. The algorithm's privacy-preserving capability, measured by the Fisher
information matrix, is dynamically enhanced over time. Notably, the Fisher
information matrix of the output signals with respect to the sensitive
information converges to zero at a polynomial rate, and the improvement in
privacy brought by the quantizers is quantitatively characterized as a
multiplicative effect. Regarding the communication costs, each sensor transmits
only 1 bit of information to its neighbours at each time step. Additionally,
the assumption on the negligible quantization error for real-valued messages is
not required. While achieving the requirements of privacy preservation and
reducing communication costs, the algorithm ensures that its estimates converge
almost surely to the true value of the unknown parameter by establishing a
co-design guideline for the time-varying privacy noises and step-sizes. A
polynomial almost sure convergence rate is obtained, and then the trade-off
between privacy and convergence rate is established. Numerical examples
demonstrate the main results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.12153v2">VeilAudit: Breaking the Deadlock Between Privacy and Accountability
  Across Blockchains</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-14T05:16:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Minhao Qiao, Hai Dong, Iqbal Gondal</p>
    <p><b>Summary:</b> Cross chain interoperability in blockchain systems exposes a fundamental
tension between user privacy and regulatory accountability. Existing solutions
enforce an all or nothing choice between full anonymity and mandatory identity
disclosure, which limits adoption in regulated financial settings. We present
VeilAudit, a cross chain auditing framework that introduces Auditor Only
Linkability, which allows auditors to link transaction behaviors that originate
from the same anonymous entity without learning its identity. VeilAudit
achieves this with a user generated Linkable Audit Tag that embeds a zero
knowledge proof to attest to its validity without exposing the user master
wallet address, and with a special ciphertext that only designated auditors can
test for linkage. To balance privacy and compliance, VeilAudit also supports
threshold gated identity revelation under due process. VeilAudit further
provides a mechanism for building reputation in pseudonymous environments,
which enables applications such as cross chain credit scoring based on
verifiable behavioral history. We formalize the security guarantees and develop
a prototype that spans multiple EVM chains. Our evaluation shows that the
framework is practical for today multichain environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.13890v1">A Survey on Collaborating Small and Large Language Models for
  Performance, Cost-effectiveness, Cloud-edge Privacy, and Trustworthiness</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">  
  <p><b>Published on:</b> 2025-10-14T04:16:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fali Wang, Jihai Chen, Shuhua Yang, Ali Al-Lawati, Linli Tang, Hui Liu, Suhang Wang</p>
    <p><b>Summary:</b> Large language models (LLMs) have advanced many domains and applications but
face high fine-tuning costs, inference latency, limited edge deployability, and
reliability concerns. Small language models (SLMs), compact, efficient, and
adaptable, offer complementary remedies. Recent work explores collaborative
frameworks that fuse SLMs' specialization and efficiency with LLMs'
generalization and reasoning to meet diverse objectives across tasks and
deployment scenarios. Motivated by these developments, this paper presents a
systematic survey of SLM-LLM collaboration organized by collaboration
objectives. We propose a taxonomy with four goals: performance enhancement,
cost-effectiveness, cloud-edge privacy, and trustworthiness. Within this
framework, we review representative methods, summarize design paradigms, and
outline open challenges and future directions toward efficient, secure, and
scalable SLM-LLM collaboration.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.12031v1">Security and Privacy Assessment of U.S. and Non-U.S. Android E-Commerce
  Applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-14T00:30:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Urvashi Kishnani, Sanchari Das</p>
    <p><b>Summary:</b> E-commerce mobile applications are central to global financial transactions,
making their security and privacy crucial. In this study, we analyze 92
top-grossing Android e-commerce apps (58 U.S.-based and 34 international) using
MobSF, AndroBugs, and RiskInDroid. Our analysis shows widespread SSL and
certificate weaknesses, with approximately 92% using unsecured HTTP connections
and an average MobSF security score of 40.92/100. Over-privileged permissions
were identified in 77 apps. While U.S. apps exhibited fewer manifest, code, and
certificate vulnerabilities, both groups showed similar network-related issues.
We advocate for the adoption of stronger, standardized, and user-focused
security practices across regions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.11895v1">High-Probability Bounds For Heterogeneous Local Differential Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-10-13T19:54:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maryam Aliakbarpour, Alireza Fallah, Swaha Roy, Ria Stevens</p>
    <p><b>Summary:</b> We study statistical estimation under local differential privacy (LDP) when
users may hold heterogeneous privacy levels and accuracy must be guaranteed
with high probability. Departing from the common in-expectation analyses, and
for one-dimensional and multi-dimensional mean estimation problems, we develop
finite sample upper bounds in $\ell_2$-norm that hold with probability at least
$1-\beta$. We complement these results with matching minimax lower bounds,
establishing the optimality (up to constants) of our guarantees in the
heterogeneous LDP regime. We further study distribution learning in
$\ell_\infty$-distance, designing an algorithm with high-probability guarantees
under heterogeneous privacy demands. Our techniques offer principled guidance
for designing mechanisms in settings with user-specific privacy levels.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.11640v1">Continual Release of Densest Subgraphs: Privacy Amplification &
  Sublinear Space via Subsampling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-10-13T17:20:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Felix Zhou</p>
    <p><b>Summary:</b> We study the sublinear space continual release model for edge-differentially
private (DP) graph algorithms, with a focus on the densest subgraph problem
(DSG) in the insertion-only setting. Our main result is the first continual
release DSG algorithm that matches the additive error of the best static DP
algorithms and the space complexity of the best non-private streaming
algorithms, up to constants. The key idea is a refined use of subsampling that
simultaneously achieves privacy amplification and sparsification, a connection
not previously formalized in graph DP. Via a simple black-box reduction to the
static setting, we obtain both pure and approximate-DP algorithms with $O(\log
n)$ additive error and $O(n\log n)$ space, improving both accuracy and space
complexity over the previous state of the art. Along the way, we introduce
graph densification in the graph DP setting, adding edges to trigger earlier
subsampling, which removes the extra logarithmic factors in error and space
incurred by prior work [ELMZ25]. We believe this simple idea may be of
independent interest.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.11514v2">Toward Efficient and Privacy-Aware eHealth Systems: An Integrated
  Sensing, Computing, and Semantic Communication Approach</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2025-10-13T15:21:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yinchao Yang, Yahao Ding, Zhaohui Yang, Chongwen Huang, Zhaoyang Zhang, Dusit Niyato, Mohammad Shikh-Bahaei</p>
    <p><b>Summary:</b> Real-time and contactless monitoring of vital signs, such as respiration and
heartbeat, alongside reliable communication, is essential for modern healthcare
systems, especially in remote and privacy-sensitive environments. Traditional
wireless communication and sensing networks fall short in meeting all the
stringent demands of eHealth, including accurate sensing, high data efficiency,
and privacy preservation. To overcome the challenges, we propose a novel
integrated sensing, computing, and semantic communication (ISCSC) framework. In
the proposed system, a service robot utilises radar to detect patient positions
and monitor their vital signs, while sending updates to the medical devices.
Instead of transmitting raw physiological information, the robot computes and
communicates semantically extracted health features to medical devices. This
semantic processing improves data throughput and preserves the clinical
relevance of the messages, while enhancing data privacy by avoiding the
transmission of sensitive data. Leveraging the estimated patient locations, the
robot employs an interacting multiple model (IMM) filter to actively track
patient motion, thereby enabling robust beam steering for continuous and
reliable monitoring. We then propose a joint optimisation of the beamforming
matrices and the semantic extraction ratio, subject to computing capability and
power budget constraints, with the objective of maximising both the semantic
secrecy rate and sensing accuracy. Simulation results validate that the ISCSC
framework achieves superior sensing accuracy, improved semantic transmission
efficiency, and enhanced privacy preservation compared to conventional joint
sensing and communication methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.11347v1">Multi-View Graph Feature Propagation for Privacy Preservation and
  Feature Sparsity</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-10-13T12:42:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Etzion Harari, Moshe Unger</p>
    <p><b>Summary:</b> Graph Neural Networks (GNNs) have demonstrated remarkable success in node
classification tasks over relational data, yet their effectiveness often
depends on the availability of complete node features. In many real-world
scenarios, however, feature matrices are highly sparse or contain sensitive
information, leading to degraded performance and increased privacy risks.
Furthermore, direct exposure of information can result in unintended data
leakage, enabling adversaries to infer sensitive information. To address these
challenges, we propose a novel Multi-view Feature Propagation (MFP) framework
that enhances node classification under feature sparsity while promoting
privacy preservation. MFP extends traditional Feature Propagation (FP) by
dividing the available features into multiple Gaussian-noised views, each
propagating information independently through the graph topology. The
aggregated representations yield expressive and robust node embeddings. This
framework is novel in two respects: it introduces a mechanism that improves
robustness under extreme sparsity, and it provides a principled way to balance
utility with privacy. Extensive experiments conducted on graph datasets
demonstrate that MFP outperforms state-of-the-art baselines in node
classification while substantially reducing privacy leakage. Moreover, our
analysis demonstrates that propagated outputs serve as alternative imputations
rather than reconstructions of the original features, preserving utility
without compromising privacy. A comprehensive sensitivity analysis further
confirms the stability and practical applicability of MFP across diverse
scenarios. Overall, MFP provides an effective and privacy-aware framework for
graph learning in domains characterized by missing or sensitive features.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.11299v2">How to Get Actual Privacy and Utility from Privacy Models: the
  k-Anonymity and Differential Privacy Families</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">  
  <p><b>Published on:</b> 2025-10-13T11:41:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Josep Domingo-Ferrer, David Sánchez</p>
    <p><b>Summary:</b> Privacy models were introduced in privacy-preserving data publishing and
statistical disclosure control with the promise to end the need for costly
empirical assessment of disclosure risk. We examine how well this promise is
kept by the main privacy models. We find they may fail to provide adequate
protection guarantees because of problems in their definition or incur
unacceptable trade-offs between privacy protection and utility preservation.
Specifically, k-anonymity may not entirely exclude disclosure if enforced with
deterministic mechanisms or without constraints on the confidential values. On
the other hand, differential privacy (DP) incurs unacceptable utility loss for
small budgets and its privacy guarantee becomes meaningless for large budgets.
In the latter case, an ex post empirical assessment of disclosure risk becomes
necessary, undermining the main appeal of privacy models. Whereas the utility
preservation of DP can only be improved by relaxing its privacy guarantees, we
argue that a semantic reformulation of k-anonymity can offer more robust
privacy without losing utility with respect to traditional syntactic
k-anonymity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.11116v1">N-output Mechanism: Estimating Statistical Information from Numerical
  Data under Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-13T08:06:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Incheol Baek, Yon Dohn Chung</p>
    <p><b>Summary:</b> Local Differential Privacy (LDP) addresses significant privacy concerns in
sensitive data collection. In this work, we focus on numerical data collection
under LDP, targeting a significant gap in the literature: existing LDP
mechanisms are optimized for either a very small ($|\Omega| \in \{2, 3\}$) or
infinite output spaces. However, no generalized method for constructing an
optimal mechanism for an arbitrary output size $N$ exists. To fill this gap, we
propose the \textbf{N-output mechanism}, a generalized framework that maps
numerical data to one of $N$ discrete outputs.
  We formulate the mechanism's design as an optimization problem to minimize
estimation variance for any given $N \geq 2$ and develop both numerical and
analytical solutions. This results in a mechanism that is highly accurate and
adaptive, as its design is determined by solving an optimization problem for
any chosen $N$. Furthermore, we extend our framework and existing mechanisms to
the task of distribution estimation. Empirical evaluations show that the
N-output mechanism achieves state-of-the-art accuracy for mean, variance, and
distribution estimation with small communication costs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.10805v1">Therapeutic AI and the Hidden Risks of Over-Disclosure: An Embedded
  AI-Literacy Framework for Mental Health Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-10-12T20:50:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Soraya S. Anvari, Rina R. Wehbe</p>
    <p><b>Summary:</b> Large Language Models (LLMs) are increasingly deployed in mental health
contexts, from structured therapeutic support tools to informal chat-based
well-being assistants. While these systems increase accessibility, scalability,
and personalization, their integration into mental health care brings privacy
and safety challenges that have not been well-examined. Unlike traditional
clinical interactions, LLM-mediated therapy often lacks a clear structure for
what information is collected, how it is processed, and how it is stored or
reused. Users without clinical guidance may over-disclose personal information,
which is sometimes irrelevant to their presenting concern, due to misplaced
trust, lack of awareness of data risks, or the conversational design of the
system. This overexposure raises privacy concerns and also increases the
potential for LLM bias, misinterpretation, and long-term data misuse. We
propose a framework embedding Artificial Intelligence (AI) literacy
interventions directly into mental health conversational systems, and outline a
study plan to evaluate their impact on disclosure safety, trust, and user
experience.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.10316v1">An information theorist's tour of differential privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> 
  <p><b>Published on:</b> 2025-10-11T18:54:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anand D. Sarwate, Flavio P. Calmon, Oliver Kosut, Lalitha Sankar</p>
    <p><b>Summary:</b> Since being proposed in 2006, differential privacy has become a standard
method for quantifying certain risks in publishing or sharing analyses of
sensitive data. At its heart, differential privacy measures risk in terms of
the differences between probability distributions, which is a central topic in
information theory. A differentially private algorithm is a channel between the
underlying data and the output of the analysis. Seen in this way, the
guarantees made by differential privacy can be understood in terms of
properties of this channel. In this article we examine a few of the key
connections between information theory and the formulation/application of
differential privacy, giving an ``operational significance'' for relevant
information measures.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.09985v1">Prismo: A Decision Support System for Privacy-Preserving ML Framework
  Selection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2025-10-11T03:27:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nges Brian Njungle, Eric Jahns, Luigi Mastromauro, Edwin P. Kayang, Milan Stojkov, Michel A. Kinsy</p>
    <p><b>Summary:</b> Machine learning has become a crucial part of our lives, with applications
spanning nearly every aspect of our daily activities. However, using personal
information in machine learning applications has sparked significant security
and privacy concerns about user data. To address these challenges, different
privacy-preserving machine learning (PPML) frameworks have been developed to
protect sensitive information in machine learning applications. These
frameworks generally attempt to balance design trade-offs such as computational
efficiency, communication overhead, security guarantees, and scalability.
Despite the advancements, selecting the optimal framework and parameters for
specific deployment scenarios remains a complex and critical challenge for
privacy and security application developers.
  We present Prismo, an open-source recommendation system designed to aid in
selecting optimal parameters and frameworks for different PPML application
scenarios. Prismo enables users to explore a comprehensive space of PPML
frameworks through various properties based on user-defined objectives. It
supports automated filtering of suitable candidate frameworks by considering
parameters such as the number of parties in multi-party computation or
federated learning and computation cost constraints in homomorphic encryption.
Prismo models every use case into a Linear Integer Programming optimization
problem, ensuring tailored solutions are recommended for each scenario. We
evaluate Prismo's effectiveness through multiple use cases, demonstrating its
ability to deliver best-fit solutions in different deployment scenarios.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.09443v2">The Impact of Sanctions on decentralised Privacy Tools: A Case Study of
  Tornado Cash</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B">
  <p><b>Published on:</b> 2025-10-10T14:55:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Raffaele Cristodaro, Benjamin Kraner, Claudio J. Tessone</p>
    <p><b>Summary:</b> This paper investigates the impact of sanctions on Tornado Cash, a smart
contract protocol designed to enhance transaction privacy. Following the U.S.
Department of the Treasury's sanctions against Tornado Cash in August 2022,
platform activity declined sharply. We document a significant and sustained
reduction in transaction volume, user diversity, and overall protocol
utilization after the sanctions were imposed. Our analysis draws on transaction
data from three major blockchains: Ethereum, BNB Smart Chain, and Polygon. We
further examine developments following the partial lifting and eventual removal
of sanctions by the U.S. Office of Foreign Assets Control (OFAC) in March 2025.
Although activity partially recovered, the rebound remained limited. The
Tornado Cash case illustrates how regulatory interventions can affect
decentralized protocols, while also highlighting the challenges of fully
enforcing such measures in decentralized environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.09253v1">Zero-shot image privacy classification with Vision-Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Multimedia-5BC0EB">
  <p><b>Published on:</b> 2025-10-10T10:50:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alina Elena Baia, Alessio Xompero, Andrea Cavallaro</p>
    <p><b>Summary:</b> While specialized learning-based models have historically dominated image
privacy prediction, the current literature increasingly favours adopting large
Vision-Language Models (VLMs) designed for generic tasks. This trend risks
overlooking the performance ceiling set by purpose-built models due to a lack
of systematic evaluation. To address this problem, we establish a zero-shot
benchmark for image privacy classification, enabling a fair comparison. We
evaluate the top-3 open-source VLMs, according to a privacy benchmark, using
task-aligned prompts and we contrast their performance, efficiency, and
robustness against established vision-only and multi-modal methods.
Counter-intuitively, our results show that VLMs, despite their
resource-intensive nature in terms of high parameter count and slower
inference, currently lag behind specialized, smaller models in privacy
prediction accuracy. We also find that VLMs exhibit higher robustness to image
perturbations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.09155v1">Federated Data Analytics for Cancer Immunotherapy: A Privacy-Preserving
  Collaborative Platform for Patient Management</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-10-10T08:57:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mira Raheem, Michael Papazoglou, Bernd Krämer, Neamat El-Tazi, Amal Elgammal</p>
    <p><b>Summary:</b> Connected health is a multidisciplinary approach focused on health
management, prioritizing pa-tient needs in the creation of tools, services, and
treatments. This paradigm ensures proactive and efficient care by facilitating
the timely exchange of accurate patient information among all stake-holders in
the care continuum. The rise of digital technologies and process innovations
promises to enhance connected health by integrating various healthcare data
sources. This integration aims to personalize care, predict health outcomes,
and streamline patient management, though challeng-es remain, particularly in
data architecture, application interoperability, and security. Data analytics
can provide critical insights for informed decision-making and health
co-creation, but solutions must prioritize end-users, including patients and
healthcare professionals. This perspective was explored through an agile System
Development Lifecycle in an EU-funded project aimed at developing an integrated
AI-generated solution for managing cancer patients undergoing immunotherapy.
This paper contributes with a collaborative digital framework integrating
stakeholders across the care continuum, leveraging federated big data analytics
and artificial intelligence for improved decision-making while ensuring
privacy. Analytical capabilities, such as treatment recommendations and adverse
event predictions, were validated using real-life data, achieving 70%-90%
accuracy in a pilot study with the medical partners, demonstrating the
framework's effectiveness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.09114v2">On the Fairness of Privacy Protection: Measuring and Mitigating the
  Disparity of Group Privacy Risks for Differentially Private Machine Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-10-10T08:09:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhi Yang, Changwu Huang, Ke Tang, Xin Yao</p>
    <p><b>Summary:</b> While significant progress has been made in conventional fairness-aware
machine learning (ML) and differentially private ML (DPML), the fairness of
privacy protection across groups remains underexplored. Existing studies have
proposed methods to assess group privacy risks, but these are based on the
average-case privacy risks of data records. Such approaches may underestimate
the group privacy risks, thereby potentially underestimating the disparity
across group privacy risks. Moreover, the current method for assessing the
worst-case privacy risks of data records is time-consuming, limiting their
practical applicability. To address these limitations, we introduce a novel
membership inference game that can efficiently audit the approximate worst-case
privacy risks of data records. Experimental results demonstrate that our method
provides a more stringent measurement of group privacy risks, yielding a
reliable assessment of the disparity in group privacy risks. Furthermore, to
promote privacy protection fairness in DPML, we enhance the standard DP-SGD
algorithm with an adaptive group-specific gradient clipping strategy, inspired
by the design of canaries in differential privacy auditing studies. Extensive
experiments confirm that our algorithm effectively reduces the disparity in
group privacy risks, thereby enhancing the fairness of privacy protection in
DPML.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.09715v1">A Scalable, Privacy-Preserving Decentralized Identity and Verifiable
  Data Sharing Framework based on Zero-Knowledge Proofs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2025-10-10T06:06:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hui Yuan</p>
    <p><b>Summary:</b> With the proliferation of decentralized applications (DApps), the conflict
between the transparency of blockchain technology and user data privacy has
become increasingly prominent. While Decentralized Identity (DID) and
Verifiable Credentials (VCs) provide a standardized framework for user data
sovereignty, achieving trusted identity verification and data sharing without
compromising privacy remains a significant challenge. This paper proposes a
novel, comprehensive framework that integrates DIDs and VCs with efficient
Zero-Knowledge Proof (ZKP) schemes to address this core issue. The key
contributions of this framework are threefold: first, it constructs a set of
strong privacy-preserving protocols based on zk-STARKs, allowing users to prove
that their credentials satisfy specific conditions (e.g., "age is over 18")
without revealing any underlying sensitive data. Second, it designs a scalable,
privacy-preserving credential revocation mechanism based on cryptographic
accumulators, effectively solving credential management challenges in
large-scale scenarios. Finally, it integrates a practical social key recovery
scheme, significantly enhancing system usability and security. Through a
prototype implementation and performance evaluation, this paper quantitatively
analyzes the framework's performance in terms of proof generation time,
verification overhead, and on-chain costs. Compared to existing
state-of-the-art systems based on zk-SNARKs, our framework, at the cost of a
larger proof size, significantly improves prover efficiency for complex
computations and provides stronger security guarantees, including no trusted
setup and post-quantum security. Finally, a case study in the decentralized
finance (DeFi) credit scoring scenario demonstrates the framework's immense
potential for unlocking capital efficiency and fostering a trusted data
economy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.08813v1">The Model's Language Matters: A Comparative Privacy Analysis of LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-09T20:59:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abhishek K. Mishra, Antoine Boutet, Lucas Magnana</p>
    <p><b>Summary:</b> Large Language Models (LLMs) are increasingly deployed across multilingual
applications that handle sensitive data, yet their scale and linguistic
variability introduce major privacy risks. Mostly evaluated for English, this
paper investigates how language structure affects privacy leakage in LLMs
trained on English, Spanish, French, and Italian medical corpora. We quantify
six linguistic indicators and evaluate three attack vectors: extraction,
counterfactual memorization, and membership inference. Results show that
privacy vulnerability scales with linguistic redundancy and tokenization
granularity: Italian exhibits the strongest leakage, while English shows higher
membership separability. In contrast, French and Spanish display greater
resilience due to higher morphological complexity. Overall, our findings
provide the first quantitative evidence that language matters in privacy
leakage, underscoring the need for language-aware privacy-preserving mechanisms
in LLM deployments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.08355v1">ExPrESSO: Zero-Knowledge backed Extensive Privacy Preserving Single
  Sign-on</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-09T15:42:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kaustabh Barman, Fabian Piper, Sanjeet Raj Pandey, Axel Kuepper</p>
    <p><b>Summary:</b> User authentication is one of the most important aspects for secure
communication between services and end-users over the Internet. Service
providers leverage Single-Sign On (SSO) to make it easier for their users to
authenticate themselves. However, standardized systems for SSO, such as OIDC,
do not guarantee user privacy as identity providers can track user activities.
We propose a zero-knowledge-based mechanism that integrates with OIDC to let
users authenticate through SSO without revealing information about the service
provider. Our system leverages Groth's zk-SNARK to prove membership of
subscribed service providers without revealing their identity. We adopt a
decentralized and verifiable approach to set up the prerequisites of our
construction that further secures and establishes trust in the system. We set
up high security targets and achieve them with minimal storage and latency
cost, proving that our research can be adopted for production.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.08247v1">The Right to Communications Confidentiality in Europe: Protecting
  Privacy, Freedom of Expression, and Trust</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-10-09T14:05:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Frederik J. Zuiderveen Borgesius, Wilfred Steenbruggen</p>
    <p><b>Summary:</b> In the European Union, the General Data Protection Regulation (GDPR) provides
comprehensive rules for the processing of personal data. In addition, the EU
lawmaker intends to adopt specific rules to protect confidentiality of
communications, in a separate ePrivacy Regulation. Some have argued that there
is no need for such additional rules for communications confidentiality. This
Article discusses the protection of the right to confidentiality of
communications in Europe. We look at the right's origins to assess the
rationale for protecting it. We also analyze how the right is currently
protected under the European Convention on Human Rights and under EU law. We
show that at its core the right to communications confidentiality protects
three individual and collective values: privacy, freedom of expression, and
trust in communication services. The right aims to ensure that individuals and
organizations can safely entrust communication to service providers. Initially,
the right protected only postal letters, but it has gradually developed into a
strong safeguard for the protection of confidentiality of communications,
regardless of the technology used. Hence, the right does not merely serve
individual privacy interests, but also other more collective interests that are
crucial for the functioning of our information society. We conclude that
separate EU rules to protect communications confidentiality, next to the GDPR,
are justified and necessary.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.09691v1">Evaluation of Differential Privacy Mechanisms on Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">  
  <p><b>Published on:</b> 2025-10-09T11:32:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tejash Varsani</p>
    <p><b>Summary:</b> Federated learning is distributed model training across several clients
without disclosing raw data. Despite advancements in data privacy, risks still
remain. Differential Privacy (DP) is a technique to protect sensitive data by
adding noise to model updates, usually controlled by a fixed privacy budget.
However, this approach can introduce excessive noise, particularly when the
model converges, which compromises performance. To address this problem,
adaptive privacy budgets have been investigated as a potential solution. This
work implements DP methods using Laplace and Gaussian mechanisms with an
adaptive privacy budget, extending the SelecEval simulator. We introduce an
adaptive clipping approach in the Gaussian mechanism, ensuring that gradients
of the model are dynamically updated rather than using a fixed sensitivity. We
conduct extensive experiments with various privacy budgets, IID and non-IID
datasets, and different numbers of selected clients per round. While our
experiments were limited to 200 training rounds, the results suggest that
adaptive privacy budgets and adaptive clipping can help maintain model accuracy
while preserving privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.07976v1">The impact of abstract and object tags on image privacy classification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-10-09T09:09:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Darya Baranouskaya, Andrea Cavallaro</p>
    <p><b>Summary:</b> Object tags denote concrete entities and are central to many computer vision
tasks, whereas abstract tags capture higher-level information, which is
relevant for tasks that require a contextual, potentially subjective scene
understanding. Object and abstract tags extracted from images also facilitate
interpretability. In this paper, we explore which type of tags is more suitable
for the context-dependent and inherently subjective task of image privacy.
While object tags are generally used for privacy classification, we show that
abstract tags are more effective when the tag budget is limited. Conversely,
when a larger number of tags per image is available, object-related information
is as useful. We believe that these findings will guide future research in
developing more accurate image privacy classifiers, informed by the role of tag
types and quantity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.07457v1">Comparison of Fully Homomorphic Encryption and Garbled Circuit
  Techniques in Privacy-Preserving Machine Learning Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-10-08T19:03:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kalyan Cheerla, Lotfi Ben Othmane, Kirill Morozov</p>
    <p><b>Summary:</b> Machine Learning (ML) is making its way into fields such as healthcare,
finance, and Natural Language Processing (NLP), and concerns over data privacy
and model confidentiality continue to grow. Privacy-preserving Machine Learning
(PPML) addresses this challenge by enabling inference on private data without
revealing sensitive inputs or proprietary models. Leveraging Secure Computation
techniques from Cryptography, two widely studied approaches in this domain are
Fully Homomorphic Encryption (FHE) and Garbled Circuits (GC). This work
presents a comparative evaluation of FHE and GC for secure neural network
inference. A two-layer neural network (NN) was implemented using the CKKS
scheme from the Microsoft SEAL library (FHE) and the TinyGarble2.0 framework
(GC) by IntelLabs. Both implementations are evaluated under the semi-honest
threat model, measuring inference output error, round-trip time, peak memory
usage, communication overhead, and communication rounds. Results reveal a
trade-off: modular GC offers faster execution and lower memory consumption,
while FHE supports non-interactive inference.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.07452v1">PATCH: Mitigating PII Leakage in Language Models with Privacy-Aware
  Targeted Circuit PatcHing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-10-08T18:58:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anthony Hughes, Vasisht Duddu, N. Asokan, Nikolaos Aletras, Ning Ma</p>
    <p><b>Summary:</b> Language models (LMs) may memorize personally identifiable information (PII)
from training data, enabling adversaries to extract it during inference.
Existing defense mechanisms such as differential privacy (DP) reduce this
leakage, but incur large drops in utility. Based on a comprehensive study using
circuit discovery to identify the computational circuits responsible PII
leakage in LMs, we hypothesize that specific PII leakage circuits in LMs should
be responsible for this behavior. Therefore, we propose PATCH (Privacy-Aware
Targeted Circuit PatcHing), a novel approach that first identifies and
subsequently directly edits PII circuits to reduce leakage. PATCH achieves
better privacy-utility trade-off than existing defenses, e.g., reducing recall
of PII leakage from LMs by up to 65%. Finally, PATCH can be combined with DP to
reduce recall of residual leakage of an LM to as low as 0.01%. Our analysis
shows that PII leakage circuits persist even after the application of existing
defense mechanisms. In contrast, PATCH can effectively mitigate their impact.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.07176v1">Exposing LLM User Privacy via Traffic Fingerprint Analysis: A Study of
  Privacy Risks in LLM Agent Interactions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-08T16:16:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yixiang Zhang, Xinhao Deng, Zhongyi Gu, Yihao Chen, Ke Xu, Qi Li, Jianping Wu</p>
    <p><b>Summary:</b> Large Language Models (LLMs) are increasingly deployed as agents that
orchestrate tasks and integrate external tools to execute complex workflows. We
demonstrate that these interactive behaviors leave distinctive fingerprints in
encrypted traffic exchanged between users and LLM agents. By analyzing traffic
patterns associated with agent workflows and tool invocations, adversaries can
infer agent activities, distinguish specific agents, and even profile sensitive
user attributes. To highlight this risk, we develop AgentPrint, which achieves
an F1-score of 0.866 in agent identification and attains 73.9% and 69.1% top-3
accuracy in user attribute inference for simulated- and real-user settings,
respectively. These results uncover an overlooked risk: the very interactivity
that empowers LLM agents also exposes user privacy, underscoring the urgent
need for technical countermeasures alongside regulatory and policy safeguards.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.07136v1">Spectral Graph Clustering under Differential Privacy: Balancing Privacy,
  Accuracy, and Efficiency</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B"> 
  <p><b>Published on:</b> 2025-10-08T15:30:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohamed Seif, Antti Koskela, H. Vincent Poor, Andrea J. Goldsmith</p>
    <p><b>Summary:</b> We study the problem of spectral graph clustering under edge differential
privacy (DP). Specifically, we develop three mechanisms: (i) graph perturbation
via randomized edge flipping combined with adjacency matrix shuffling, which
enforces edge privacy while preserving key spectral properties of the graph.
Importantly, shuffling considerably amplifies the guarantees: whereas flipping
edges with a fixed probability alone provides only a constant epsilon edge DP
guarantee as the number of nodes grows, the shuffled mechanism achieves
(epsilon, delta) edge DP with parameters that tend to zero as the number of
nodes increase; (ii) private graph projection with additive Gaussian noise in a
lower-dimensional space to reduce dimensionality and computational complexity;
and (iii) a noisy power iteration method that distributes Gaussian noise across
iterations to ensure edge DP while maintaining convergence. Our analysis
provides rigorous privacy guarantees and a precise characterization of the
misclassification error rate. Experiments on synthetic and real-world networks
validate our theoretical analysis and illustrate the practical privacy-utility
trade-offs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.06326v1">Composable privacy of networked quantum sensing</a></h3>
  
  <p><b>Published on:</b> 2025-10-07T18:00:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Naomi R. Solomons, Damian Markham</p>
    <p><b>Summary:</b> Networks of sensors are a promising scheme to deliver the benefits of quantum
technologies in coming years, offering enhanced precision and accuracy for
distributed metrology through the use of large entangled states. Recent work
has additionally explored the privacy of these schemes, meaning that local
parameters can be kept secret while a joint function of these is estimated by
the network. In this work, we use the abstract cryptography framework to relate
the two proposed definitions of quasi-privacy, showing that both are
composable, which enables the protocol to be securely included as a sub-routine
to other schemes. We give an explicit example that estimating the mean of a set
of parameters using GHZ states is composably fully secure.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.05959v1">Distributed Platoon Control Under Quantization: Stability Analysis and
  Privacy Preservation</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2025-10-07T14:16:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kaixiang Zhang, Zhaojian Li, Wei Lin</p>
    <p><b>Summary:</b> Distributed control of connected and automated vehicles has attracted
considerable interest for its potential to improve traffic efficiency and
safety. However, such control schemes require sharing privacy-sensitive vehicle
data, which introduces risks of information leakage and potential malicious
activities. This paper investigates the stability and privacy-preserving
properties of distributed platoon control under two types of quantizers:
deterministic and probabilistic. For deterministic quantization, we show that
the resulting control strategy ensures the system errors remain uniformly
ultimately bounded. Moreover, in the absence of auxiliary information, an
eavesdropper cannot uniquely infer sensitive vehicle states. In contrast, the
use of probabilistic quantization enables asymptotic convergence of the vehicle
platoon in expectation with bounded variance. Importantly, probabilistic
quantizers can satisfy differential privacy guarantees, thereby preserving
privacy even when the eavesdropper possesses arbitrary auxiliary information.
We further analyze the trade-off between control performance and privacy by
formulating an optimization problem that characterizes the impact of the
quantization step on both metrics. Numerical simulations are provided to
illustrate the performance differences between the two quantization strategies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.05860v1">Automated Boilerplate: Prevalence and Quality of Contract Generators in
  the Context of Swiss Privacy Policies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-10-07T12:30:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Luka Nenadic, David Rodriguez</p>
    <p><b>Summary:</b> It has become increasingly challenging for firms to comply with a plethora of
novel digital regulations. This is especially true for smaller businesses that
often lack both the resources and know-how to draft complex legal documents.
Instead of seeking costly legal advice from attorneys, firms may turn to
cheaper alternative legal service providers such as automated contract
generators. While these services have a long-standing presence, there is little
empirical evidence on their prevalence and output quality.
  We address this gap in the context of a 2023 Swiss privacy law revision. To
enable a systematic evaluation, we create and annotate a multilingual benchmark
dataset that captures key compliance obligations under Swiss and EU privacy
law. Using this dataset, we validate a novel GPT-5-based method for large-scale
compliance assessment of privacy policies, allowing us to measure the impact of
the revision. We observe compliance increases indicating an effect of the
revision. Generators, explicitly referenced by 18% of local websites, are
associated with substantially higher levels of compliance, with increases of up
to 15 percentage points compared to privacy policies without generator use.
These findings contribute to three debates: the potential of LLMs for
cross-lingual legal analysis, the Brussels Effect of EU regulations, and,
crucially, the role of automated tools in improving compliance and contractual
quality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.05807v1">Privacy-Preserving On-chain Permissioning for KYC-Compliant
  Decentralized Applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-07T11:24:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fabian Piper, Karl Wolf, Jonathan Heiss</p>
    <p><b>Summary:</b> Decentralized applications (dApps) in Decentralized Finance (DeFi) face a
fundamental tension between regulatory compliance requirements like Know Your
Customer (KYC) and maintaining decentralization and privacy. Existing
permissioned DeFi solutions often fail to adequately protect private attributes
of dApp users and introduce implicit trust assumptions, undermining the
blockchain's decentralization. Addressing these limitations, this paper
presents a novel synthesis of Self-Sovereign Identity (SSI), Zero-Knowledge
Proofs (ZKPs), and Attribute-Based Access Control to enable privacy-preserving
on-chain permissioning based on decentralized policy decisions. We provide a
comprehensive framework for permissioned dApps that aligns decentralized trust,
privacy, and transparency, harmonizing blockchain principles with regulatory
compliance. Our framework supports multiple proof types (equality, range,
membership, and time-dependent) with efficient proof generation through a
commit-and-prove scheme that moves credential authenticity verification outside
the ZKP circuit. Experimental evaluation of our KYC-compliant DeFi
implementation shows considerable performance improvement for different proof
types compared to baseline approaches. We advance the state-of-the-art through
a holistic approach, flexible proof mechanisms addressing diverse real-world
requirements, and optimized proof generation enabling practical deployment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.05803v1">The Five Safes as a Privacy Context</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-10-07T11:19:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> James Bailie, Ruobin Gong</p>
    <p><b>Summary:</b> The Five Safes is a framework used by national statistical offices (NSO) for
assessing and managing the disclosure risk of data sharing. This paper makes
two points: Firstly, the Five Safes can be understood as a specialization of a
broader concept $\unicode{x2013}$ contextual integrity $\unicode{x2013}$ to the
situation of statistical dissemination by an NSO. We demonstrate this by
mapping the five parameters of contextual integrity onto the five dimensions of
the Five Safes. Secondly, the Five Safes contextualizes narrow, technical
notions of privacy within a holistic risk assessment. We demonstrate this with
the example of differential privacy (DP). This contextualization allows NSOs to
place DP within their Five Safes toolkit while also guiding the design of DP
implementations within the broader privacy context, as delineated by both their
regulation and the relevant social norms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.05535v1">Permutation-Invariant Representation Learning for Robust and
  Privacy-Preserving Feature Selection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-10-07T02:53:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rui Liu, Tao Zhe, Yanjie Fu, Feng Xia, Ted Senator, Dongjie Wang</p>
    <p><b>Summary:</b> Feature selection eliminates redundancy among features to improve downstream
task performance while reducing computational overhead. Existing methods often
struggle to capture intricate feature interactions and adapt across diverse
application scenarios. Recent advances employ generative intelligence to
alleviate these drawbacks. However, these methods remain constrained by
permutation sensitivity in embedding and reliance on convexity assumptions in
gradient-based search. To address these limitations, our initial work
introduces a novel framework that integrates permutation-invariant embedding
with policy-guided search. Although effective, it still left opportunities to
adapt to realistic distributed scenarios. In practice, data across local
clients is highly imbalanced, heterogeneous and constrained by strict privacy
regulations, limiting direct sharing. These challenges highlight the need for a
framework that can integrate feature selection knowledge across clients without
exposing sensitive information. In this extended journal version, we advance
the framework from two perspectives: 1) developing a privacy-preserving
knowledge fusion strategy to derive a unified representation space without
sharing sensitive raw data. 2) incorporating a sample-aware weighting strategy
to address distributional imbalance among heterogeneous local clients.
Extensive experiments validate the effectiveness, robustness, and efficiency of
our framework. The results further demonstrate its strong generalization
ability in federated learning scenarios. The code and data are publicly
available: https://anonymous.4open.science/r/FedCAPS-08BF.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.05288v1">DP-Adam-AC: Privacy-preserving Fine-Tuning of Localizable Language
  Models Using Adam Optimization with Adaptive Clipping</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-06T18:56:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruoxing Yang</p>
    <p><b>Summary:</b> Large language models (LLMs) such as ChatGPT have evolved into powerful and
ubiquitous tools. Fine-tuning on small datasets allows LLMs to acquire
specialized skills for specific tasks efficiently. Although LLMs provide great
utility in both general and task-specific use cases, they are limited by two
security-related concerns. First, traditional LLM hardware requirements make
them infeasible to run locally on consumer-grade devices. A remote network
connection with the LLM provider's server is usually required, making the
system vulnerable to network attacks. Second, fine-tuning an LLM for a
sensitive task may involve sensitive data. Non-private fine-tuning algorithms
produce models vulnerable to training data reproduction attacks. Our work
addresses these security concerns by enhancing differentially private
optimization algorithms and applying them to fine-tune localizable language
models. We introduce adaptable gradient clipping along with other engineering
enhancements to the standard DP-Adam optimizer to create DP-Adam-AC. We use our
optimizer to fine-tune examples of two localizable LLM designs, small language
model (Qwen2.5-0.5B) and 1.58 bit quantization (Bitnet-b1.58-2B). We
demonstrate promising improvements in loss through experimentation with two
synthetic datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.05068v1">Multi-Agent Distributed Optimization With Feasible Set Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">  
  <p><b>Published on:</b> 2025-10-06T17:45:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shreya Meel, Sennur Ulukus</p>
    <p><b>Summary:</b> We consider the problem of decentralized constrained optimization with
multiple agents $E_1,\ldots,E_N$ who jointly wish to learn the optimal solution
set while keeping their feasible sets $\mathcal{P}_1,\ldots,\mathcal{P}_N$
private from each other. We assume that the objective function $f$ is known to
all agents and each feasible set is a collection of points from a universal
alphabet $\mathcal{P}_{alph}$. A designated agent (leader) starts the
communication with the remaining (non-leader) agents, and is the first to
retrieve the solution set. The leader searches for the solution by sending
queries to and receiving answers from the non-leaders, such that the
information on the individual feasible sets revealed to the leader should be no
more than nominal, i.e., what is revealed from learning the solution set alone.
We develop achievable schemes for obtaining the solution set at nominal
information leakage, and characterize their communication costs under two
communication setups between agents. In this work, we focus on two kinds of
network setups: i) ring, where each agent communicates with two adjacent
agents, and ii) star, where only the leader communicates with the remaining
agents. We show that, if the leader first learns the joint feasible set through
an existing private set intersection (PSI) protocol and then deduces the
solution set, the information leaked to the leader is greater than nominal.
Moreover, we draw connection of our schemes to threshold PSI (ThPSI), which is
a PSI-variant where the intersection is revealed only when its cardinality is
larger than a threshold value. Finally, for various realizations of $f$ mapped
uniformly at random to a fixed range of values, our schemes are more
communication-efficient with a high probability compared to retrieving the
entire feasible set through PSI.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.04527v2">Quantum capacity amplification via privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">   <img alt="Category Badge" src="https://img.shields.io/badge/Mathematical Physics-F9C80E">
  <p><b>Published on:</b> 2025-10-06T06:35:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Peixue Wu, Yunkai Wang</p>
    <p><b>Summary:</b> We investigate superadditivity of quantum capacity through private channels
whose Choi-Jamiolkowski operators are private states. This perspective links
the security structure of private states to quantum capacity and clarifies the
role of the shield system: information encoded in the shield system that would
otherwise leak to the environment can be recycled when paired with an assisting
channel, thereby boosting capacity. Our main contributions are threefold:
Firstly, we develop a general framework that provides a sufficient condition
for capacity amplification, which is formulated in terms of the assisting
channel's Holevo information. As examples, we give explicit, dimension and
parameter dependent amplification thresholds for erasure and depolarizing
channels. Secondly, assuming the Spin alignment conjecture, we derive a
single-letter expression for the quantum capacity of a family of private
channels that are neither degradable, anti-degradable, nor PPT; as an
application, we construct channels with vanishing quantum capacity yet
unbounded private capacity. Thirdly, we further analyze approximate private
channels: we give an alternative proof of superactivation that extends its
validity to a broader parameter regime, and, by combining amplification bounds
with continuity estimates, we establish a metric separation showing that
channels exhibiting capacity amplification have nonzero diamond distance from
the set of anti-degradable channels, indicating that existing approximate
(anti-)degradability bounds are not tight. We also revisit the computability of
the regularized quantum capacity and modestly suggest that this fundamental
question still remains open.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.06267v1">RareGraph-Synth: Knowledge-Guided Diffusion Models for Generating
  Privacy-Preserving Synthetic Patient Trajectories in Ultra-Rare Diseases</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> 
  <p><b>Published on:</b> 2025-10-06T03:59:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Khartik Uppalapati, Shakeel Abdulkareem, Bora Yimenicioglu</p>
    <p><b>Summary:</b> We propose RareGraph-Synth, a knowledge-guided, continuous-time diffusion
framework that generates realistic yet privacy-preserving synthetic
electronic-health-record (EHR) trajectories for ultra-rare diseases.
RareGraph-Synth unifies five public resources: Orphanet/Orphadata, the Human
Phenotype Ontology (HPO), the GARD rare-disease KG, PrimeKG, and the FDA
Adverse Event Reporting System (FAERS) into a heterogeneous knowledge graph
comprising approximately 8 M typed edges. Meta-path scores extracted from this
8-million-edge KG modulate the per-token noise schedule in the forward
stochastic differential equation, steering generation toward biologically
plausible lab-medication-adverse-event co-occurrences while retaining
score-based diffusion model stability. The reverse denoiser then produces
timestamped sequences of lab-code, medication-code, and adverse-event-flag
triples that contain no protected health information. On simulated
ultra-rare-disease cohorts, RareGraph-Synth lowers categorical Maximum Mean
Discrepancy by 40 percent relative to an unguided diffusion baseline and by
greater than 60 percent versus GAN counterparts, without sacrificing downstream
predictive utility. A black-box membership-inference evaluation using the
DOMIAS attacker yields AUROC approximately 0.53, well below the 0.55
safe-release threshold and substantially better than the approximately 0.61
plus or minus 0.03 observed for non-KG baselines, demonstrating strong
resistance to re-identification. These results suggest that integrating
biomedical knowledge graphs directly into diffusion noise schedules can
simultaneously enhance fidelity and privacy, enabling safer data sharing for
rare-disease research.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.04465v1">Autonomy Matters: A Study on Personalization-Privacy Dilemma in LLM
  Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-06T03:38:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhiping Zhang, Yi Evie Zhang, Freda Shi, Tianshi Li</p>
    <p><b>Summary:</b> Large Language Model (LLM) agents require personal information for
personalization in order to better act on users' behalf in daily tasks, but
this raises privacy concerns and a personalization-privacy dilemma. Agent's
autonomy introduces both risks and opportunities, yet its effects remain
unclear. To better understand this, we conducted a 3$\times$3 between-subjects
experiment ($N=450$) to study how agent's autonomy level and personalization
influence users' privacy concerns, trust and willingness to use, as well as the
underlying psychological processes. We find that personalization without
considering users' privacy preferences increases privacy concerns and decreases
trust and willingness to use. Autonomy moderates these effects: Intermediate
autonomy flattens the impact of personalization compared to No- and Full
autonomy conditions. Our results suggest that rather than aiming for perfect
model alignment in output generation, balancing autonomy of agent's action and
user control offers a promising path to mitigate the personalization-privacy
dilemma.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.04261v1">VortexPIA: Indirect Prompt Injection Attack against LLMs for Efficient
  Extraction of User Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-05T15:58:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yu Cui, Sicheng Pan, Yifei Liu, Haibin Zhang, Cong Zuo</p>
    <p><b>Summary:</b> Large language models (LLMs) have been widely deployed in Conversational AIs
(CAIs), while exposing privacy and security threats. Recent research shows that
LLM-based CAIs can be manipulated to extract private information from human
users, posing serious security threats. However, the methods proposed in that
study rely on a white-box setting that adversaries can directly modify the
system prompt. This condition is unlikely to hold in real-world deployments.
The limitation raises a critical question: can unprivileged attackers still
induce such privacy risks in practical LLM-integrated applications? To address
this question, we propose \textsc{VortexPIA}, a novel indirect prompt injection
attack that induces privacy extraction in LLM-integrated applications under
black-box settings. By injecting token-efficient data containing false
memories, \textsc{VortexPIA} misleads LLMs to actively request private
information in batches. Unlike prior methods, \textsc{VortexPIA} allows
attackers to flexibly define multiple categories of sensitive data. We evaluate
\textsc{VortexPIA} on six LLMs, covering both traditional and reasoning LLMs,
across four benchmark datasets. The results show that \textsc{VortexPIA}
significantly outperforms baselines and achieves state-of-the-art (SOTA)
performance. It also demonstrates efficient privacy requests, reduced token
consumption, and enhanced robustness against defense mechanisms. We further
validate \textsc{VortexPIA} on multiple realistic open-source LLM-integrated
applications, demonstrating its practical effectiveness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.04153v1">ObCLIP: Oblivious CLoud-Device Hybrid Image Generation with Privacy
  Preservation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-10-05T11:09:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haoqi Wu, Wei Dai, Ming Xu, Li Wang, Qiang Yan</p>
    <p><b>Summary:</b> Diffusion Models have gained significant popularity due to their remarkable
capabilities in image generation, albeit at the cost of intensive computation
requirement. Meanwhile, despite their widespread deployment in inference
services such as Midjourney, concerns about the potential leakage of sensitive
information in uploaded user prompts have arisen. Existing solutions either
lack rigorous privacy guarantees or fail to strike an effective balance between
utility and efficiency. To bridge this gap, we propose ObCLIP, a plug-and-play
safeguard that enables oblivious cloud-device hybrid generation. By oblivious,
each input prompt is transformed into a set of semantically similar candidate
prompts that differ only in sensitive attributes (e.g., gender, ethnicity). The
cloud server processes all candidate prompts without knowing which one is the
real one, thus preventing any prompt leakage. To mitigate server cost, only a
small portion of denoising steps is performed upon the large cloud model. The
intermediate latents are then sent back to the client, which selects the
targeted latent and completes the remaining denoising using a small device
model. Additionally, we analyze and incorporate several cache-based
accelerations that leverage temporal and batch redundancy, effectively reducing
computation cost with minimal utility degradation. Extensive experiments across
multiple datasets demonstrate that ObCLIP provides rigorous privacy and
comparable utility to cloud models with slightly increased server cost.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.05172v2">Learning More with Less: A Generalizable, Self-Supervised Framework for
  Privacy-Preserving Capacity Estimation with EV Charging Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-10-05T08:58:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anushiya Arunan, Yan Qin, Xiaoli Li, U-Xuan Tan, H. Vincent Poor, Chau Yuen</p>
    <p><b>Summary:</b> Accurate battery capacity estimation is key to alleviating consumer concerns
about battery performance and reliability of electric vehicles (EVs). However,
practical data limitations imposed by stringent privacy regulations and labeled
data shortages hamper the development of generalizable capacity estimation
models that remain robust to real-world data distribution shifts. While
self-supervised learning can leverage unlabeled data, existing techniques are
not particularly designed to learn effectively from challenging field data --
let alone from privacy-friendly data, which are often less feature-rich and
noisier. In this work, we propose a first-of-its-kind capacity estimation model
based on self-supervised pre-training, developed on a large-scale dataset of
privacy-friendly charging data snippets from real-world EV operations. Our
pre-training framework, snippet similarity-weighted masked input
reconstruction, is designed to learn rich, generalizable representations even
from less feature-rich and fragmented privacy-friendly data. Our key innovation
lies in harnessing contrastive learning to first capture high-level
similarities among fragmented snippets that otherwise lack meaningful context.
With our snippet-wise contrastive learning and subsequent similarity-weighted
masked reconstruction, we are able to learn rich representations of both
granular charging patterns within individual snippets and high-level
associative relationships across different snippets. Bolstered by this rich
representation learning, our model consistently outperforms state-of-the-art
baselines, achieving 31.9% lower test error than the best-performing benchmark,
even under challenging domain-shifted settings affected by both manufacturer
and age-induced distribution shifts. Source code is available at
https://github.com/en-research/GenEVBattery.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.04027v1">Multi-Class Support Vector Machine with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-05T04:25:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jinseong Park, Yujin Choi, Jaewook Lee</p>
    <p><b>Summary:</b> With the increasing need to safeguard data privacy in machine learning
models, differential privacy (DP) is one of the major frameworks to build
privacy-preserving models. Support Vector Machines (SVMs) are widely used
traditional machine learning models due to their robust margin guarantees and
strong empirical performance in binary classification. However, applying DP to
multi-class SVMs is inadequate, as the standard one-versus-rest (OvR) and
one-versus-one (OvO) approaches repeatedly query each data sample when building
multiple binary classifiers, thus consuming the privacy budget proportionally
to the number of classes. To overcome this limitation, we explore all-in-one
SVM approaches for DP, which access each data sample only once to construct
multi-class SVM boundaries with margin maximization properties. We propose a
novel differentially Private Multi-class SVM (PMSVM) with weight and gradient
perturbation methods, providing rigorous sensitivity and convergence analyses
to ensure DP in all-in-one SVMs. Empirical results demonstrate that our
approach surpasses existing DP-SVM methods in multi-class scenarios.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.03996v1">FHEON: A Configurable Framework for Developing Privacy-Preserving Neural
  Networks Using Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-05T02:12:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nges Brian Njungle, Eric Jahns, Michel A. Kinsy</p>
    <p><b>Summary:</b> The widespread adoption of Machine Learning as a Service raises critical
privacy and security concerns, particularly about data confidentiality and
trust in both cloud providers and the machine learning models. Homomorphic
Encryption (HE) has emerged as a promising solution to this problems, allowing
computations on encrypted data without decryption. Despite its potential,
existing approaches to integrate HE into neural networks are often limited to
specific architectures, leaving a wide gap in providing a framework for easy
development of HE-friendly privacy-preserving neural network models similar to
what we have in the broader field of machine learning. In this paper, we
present FHEON, a configurable framework for developing privacy-preserving
convolutional neural network (CNN) models for inference using HE. FHEON
introduces optimized and configurable implementations of privacy-preserving CNN
layers including convolutional layers, average pooling layers, ReLU activation
functions, and fully connected layers. These layers are configured using
parameters like input channels, output channels, kernel size, stride, and
padding to support arbitrary CNN architectures. We assess the performance of
FHEON using several CNN architectures, including LeNet-5, VGG-11, VGG- 16,
ResNet-20, and ResNet-34. FHEON maintains encrypted-domain accuracies within
+/- 1% of their plaintext counterparts for ResNet-20 and LeNet-5 models.
Notably, on a consumer-grade CPU, the models build on FHEON achieved 98.5%
accuracy with a latency of 13 seconds on MNIST using LeNet-5, and 92.2%
accuracy with a latency of 403 seconds on CIFAR-10 using ResNet-20.
Additionally, FHEON operates within a practical memory budget requiring not
more than 42.3 GB for VGG-16.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.03860v1">Privacy Enhancement in Over-the-Air Federated Learning via Adaptive
  Receive Scaling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">  
  <p><b>Published on:</b> 2025-10-04T16:15:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Faeze Moradi Kalarde, Ben Liang, Min Dong, Yahia A. Eldemerdash Ahmed, Ho Ting Cheng</p>
    <p><b>Summary:</b> In Federated Learning (FL) with over-the-air aggregation, the quality of the
signal received at the server critically depends on the receive scaling
factors. While a larger scaling factor can reduce the effective noise power and
improve training performance, it also compromises the privacy of devices by
reducing uncertainty. In this work, we aim to adaptively design the receive
scaling factors across training rounds to balance the trade-off between
training convergence and privacy in an FL system under dynamic channel
conditions. We formulate a stochastic optimization problem that minimizes the
overall R\'enyi differential privacy (RDP) leakage over the entire training
process, subject to a long-term constraint that ensures convergence of the
global loss function. Our problem depends on unknown future information, and we
observe that standard Lyapunov optimization is not applicable. Thus, we develop
a new online algorithm, termed AdaScale, based on a sequence of novel per-round
problems that can be solved efficiently. We further derive upper bounds on the
dynamic regret and constraint violation of AdaSacle, establishing that it
achieves diminishing dynamic regret in terms of time-averaged RDP leakage while
ensuring convergence of FL training to a stationary point. Numerical
experiments on canonical classification tasks show that our approach
effectively reduces RDP and DP leakages compared with state-of-the-art
benchmarks without compromising learning performance.</p>
  </details>
</div>

