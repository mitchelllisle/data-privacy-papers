
<h2>2025-10</h2>

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

