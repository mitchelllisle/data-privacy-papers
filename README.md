
<h2>2024-01</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.12436v1">Wasserstein Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-01-23T02:08:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chengyi Yang, Jiayin Qi, Aimin Zhou</p>
    <p><b>Summary:</b> Differential privacy (DP) has achieved remarkable results in the field of
privacy-preserving machine learning. However, existing DP frameworks do not
satisfy all the conditions for becoming metrics, which prevents them from
deriving better basic private properties and leads to exaggerated values on
privacy budgets. We propose Wasserstein differential privacy (WDP), an
alternative DP framework to measure the risk of privacy leakage, which
satisfies the properties of symmetry and triangle inequality. We show and prove
that WDP has 13 excellent properties, which can be theoretical supports for the
better performance of WDP than other DP frameworks. In addition, we derive a
general privacy accounting method called Wasserstein accountant, which enables
WDP to be applied in stochastic gradient descent (SGD) scenarios containing
sub-sampling. Experiments on basic mechanisms, compositions and deep learning
show that the privacy budgets obtained by Wasserstein accountant are relatively
stable and less influenced by order. Moreover, the overestimation on privacy
budgets can be effectively alleviated. The code is available at
https://github.com/Hifipsysta/WDP.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.12393v1">A Learning-based Declarative Privacy-Preserving Framework for Federated
  Data Management</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-01-22T22:50:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hong Guan, Summer Gautier, Deepti Gupta, Rajan Hari Ambrish, Yancheng Wang, Harsha Lakamsani, Dhanush Giriyan, Saajan Maslanka, Chaowei Xiao, Yingzhen Yang, Jia Zou</p>
    <p><b>Summary:</b> It is challenging to balance the privacy and accuracy for federated query
processing over multiple private data silos. In this work, we will demonstrate
an end-to-end workflow for automating an emerging privacy-preserving technique
that uses a deep learning model trained using the Differentially-Private
Stochastic Gradient Descent (DP-SGD) algorithm to replace portions of actual
data to answer a query. Our proposed novel declarative privacy-preserving
workflow allows users to specify "what private information to protect" rather
than "how to protect". Under the hood, the system automatically chooses
query-model transformation plans as well as hyper-parameters. At the same time,
the proposed workflow also allows human experts to review and tune the selected
privacy-preserving mechanism for audit/compliance, and optimization purposes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.12391v1">Approximation of Pufferfish Privacy for Gaussian Priors</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-01-22T22:43:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ni Ding</p>
    <p><b>Summary:</b> This paper studies how to approximate pufferfish privacy when the adversary's
prior belief of the published data is Gaussian distributed. Using Monge's
optimal transport plan, we show that $(\epsilon, \delta)$-pufferfish privacy is
attained if the additive Laplace noise is calibrated to the differences in mean
and variance of the Gaussian distributions conditioned on every discriminative
secret pair. A typical application is the private release of the summation (or
average) query, for which sufficient conditions are derived for approximating
$\epsilon$-statistical indistinguishability in individual's sensitive data. The
result is then extended to arbitrary prior beliefs trained by Gaussian mixture
models (GMMs): calibrating Laplace noise to a convex combination of differences
in mean and variance between Gaussian components attains
$(\epsilon,\delta)$-pufferfish privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.11983v1">Lightweight Protection for Privacy in Offloaded Speech Understanding</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-01-22T14:36:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dongqi Cai, Shangguang Wang, Zeling Zhang, Felix Xiaozhu Lin, Mengwei Xu</p>
    <p><b>Summary:</b> Speech is a common input method for mobile embedded devices, but cloud-based
speech recognition systems pose privacy risks. Disentanglement-based encoders,
designed to safeguard user privacy by filtering sensitive information from
speech signals, unfortunately require substantial memory and computational
resources, which limits their use in less powerful devices. To overcome this,
we introduce a novel system, XXX, optimized for such devices. XXX is built on
the insight that speech understanding primarily relies on understanding the
entire utterance's long-term dependencies, while privacy concerns are often
linked to short-term details. Therefore, XXX focuses on selectively masking
these short-term elements, preserving the quality of long-term speech
understanding. The core of XXX is an innovative differential mask generator,
grounded in interpretable learning, which fine-tunes the masking process. We
tested XXX on the STM32H7 microcontroller, assessing its performance in various
potential attack scenarios. The results show that XXX maintains speech
understanding accuracy and privacy at levels comparable to existing encoders,
but with a significant improvement in efficiency, achieving up to 53.3$\times$
faster processing and a 134.1$\times$ smaller memory footprint.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.11857v1">Adversarial speech for voice privacy protection from Personalized Speech
  generation</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36">
  <p><b>Published on:</b> 2024-01-22T11:26:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shihao Chen, Liping Chen, Jie Zhang, KongAik Lee, Zhenhua Ling, Lirong Dai</p>
    <p><b>Summary:</b> The rapid progress in personalized speech generation technology, including
personalized text-to-speech (TTS) and voice conversion (VC), poses a challenge
in distinguishing between generated and real speech for human listeners,
resulting in an urgent demand in protecting speakers' voices from malicious
misuse. In this regard, we propose a speaker protection method based on
adversarial attacks. The proposed method perturbs speech signals by minimally
altering the original speech while rendering downstream speech generation
models unable to accurately generate the voice of the target speaker. For
validation, we employ the open-source pre-trained YourTTS model for speech
generation and protect the target speaker's speech in the white-box scenario.
Automatic speaker verification (ASV) evaluations were carried out on the
generated speech as the assessment of the voice protection capability. Our
experimental results show that we successfully perturbed the speaker encoder of
the YourTTS model using the gradient-based I-FGSM adversarial perturbation
method. Furthermore, the adversarial perturbation is effective in preventing
the YourTTS model from generating the speech of the target speaker. Audio
samples can be found in
https://voiceprivacy.github.io/Adeversarial-Speech-with-YourTTS.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.11836v1">Privacy-Preserving Data Fusion for Traffic State Estimation: A Vertical
  Federated Learning Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36"> 
  <p><b>Published on:</b> 2024-01-22T10:52:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qiqing Wang, Kaidi Yang</p>
    <p><b>Summary:</b> This paper proposes a privacy-preserving data fusion method for traffic state
estimation (TSE). Unlike existing works that assume all data sources to be
accessible by a single trusted party, we explicitly address data privacy
concerns that arise in the collaboration and data sharing between multiple data
owners, such as municipal authorities (MAs) and mobility providers (MPs). To
this end, we propose a novel vertical federated learning (FL) approach, FedTSE,
that enables multiple data owners to collaboratively train and apply a TSE
model without having to exchange their private data. To enhance the
applicability of the proposed FedTSE in common TSE scenarios with limited
availability of ground-truth data, we further propose a privacy-preserving
physics-informed FL approach, i.e., FedTSE-PI, that integrates traffic models
into FL. Real-world data validation shows that the proposed methods can protect
privacy while yielding similar accuracy to the oracle method without privacy
considerations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.11735v1">zkLogin: Privacy-Preserving Blockchain Authentication with Existing
  Credentials</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-01-22T07:23:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Foteini Baldimtsi, Konstantinos Kryptos Chalkias, Yan Ji, Jonas Lindstrøm, Deepak Maram, Ben Riva, Arnab Roy, Mahdi Sedaghat, Joy Wang</p>
    <p><b>Summary:</b> For many users, a private key based wallet serves as the primary entry point
to blockchains. Commonly recommended wallet authentication methods, such as
mnemonics or hardware wallets, can be cumbersome. This difficulty in user
onboarding has significantly hindered the adoption of blockchain-based
applications.
  We develop zkLogin, a novel technique that leverages identity tokens issued
by popular platforms (any OpenID Connect enabled platform e.g. Google,
Facebook, etc.) to authenticate transactions. At the heart of zkLogin lies a
signature scheme allowing the signer to \textit{sign using their existing
OpenID accounts} and nothing else. This improves the user experience
significantly as users do not need to remember a new secret and can reuse their
existing accounts.
  zkLogin provides strong security and privacy guarantees. By design, zkLogin
builds on top of the underlying platform's authentication mechanisms, and
derives its security from there. Unlike prior related works however, zkLogin
avoids the use of additional trusted parties (e.g., trusted hardware or
oracles) for its security guarantees. zkLogin leverages zero-knowledge proofs
(ZKP) to ensure that the link between a user's off-chain and on-chain
identities is hidden, even from the platform itself.
  We have implemented and deployed zkLogin on the Sui blockchain as an
alternative to traditional digital signature-based addresses. Due to the ease
of web3 on-boarding just with social login, without requiring mnemonics, many
hundreds of thousands zkLogin accounts have already been generated in various
industries such as gaming, DeFi, direct payments, NFT collections, ride
sharing, sports racing and many more.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.11592v1">Differential Privacy in Hierarchical Federated Learning: A Formal
  Analysis and Evaluation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-01-21T20:46:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Frank Po-Chen Lin, Christopher Brinton</p>
    <p><b>Summary:</b> While federated learning (FL) eliminates the transmission of raw data over a
network, it is still vulnerable to privacy breaches from the communicated model
parameters. In this work, we formalize Differentially Private Hierarchical
Federated Learning (DP-HFL), a DP-enhanced FL methodology that seeks to improve
the privacy-utility tradeoff inherent in FL. Building upon recent proposals for
Hierarchical Differential Privacy (HDP), one of the key concepts of DP-HFL is
adapting DP noise injection at different layers of an established FL hierarchy
-- edge devices, edge servers, and cloud servers -- according to the trust
models within particular subnetworks. We conduct a comprehensive analysis of
the convergence behavior of DP-HFL, revealing conditions on parameter tuning
under which the model training process converges sublinearly to a stationarity
gap, with this gap depending on the network hierarchy, trust model, and target
privacy level. Subsequent numerical evaluations demonstrate that DP-HFL obtains
substantial improvements in convergence speed over baselines for different
privacy budgets, and validate the impact of network configuration on training.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.11305v1">Progress in Privacy Protection: A Review of Privacy Preserving
  Techniques in Recommender Systems, Edge Computing, and Cloud Computing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-01-20T19:32:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Syed Raza Bashir, Shaina Raza, Vojislav Misic</p>
    <p><b>Summary:</b> As digital technology evolves, the increasing use of connected devices brings
both challenges and opportunities in the areas of mobile crowdsourcing, edge
computing, and recommender systems. This survey focuses on these dynamic
fields, emphasizing the critical need for privacy protection in our
increasingly data-oriented world. It explores the latest trends in these
interconnected areas, with a special emphasis on privacy and data security. Our
method involves an in-depth analysis of various academic works, which helps us
to gain a comprehensive understanding of these sectors and their shifting focus
towards privacy concerns. We present new insights and marks a significant
advancement in addressing privacy issues within these technologies. The survey
is a valuable resource for researchers, industry practitioners, and policy
makers, offering an extensive overview of these fields and their related
privacy challenges, catering to a wide audience in the modern digital era.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.11249v1">Evaluating if trust and personal information privacy concerns are
  barriers to using health insurance that explicitly utilizes AI</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> 
  <p><b>Published on:</b> 2024-01-20T15:02:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alex Zarifis, Peter Kawalek, Aida Azadegan</p>
    <p><b>Summary:</b> Trust and privacy have emerged as significant concerns in online
transactions. Sharing information on health is especially sensitive but it is
necessary for purchasing and utilizing health insurance. Evidence shows that
consumers are increasingly comfortable with technology in place of humans, but
the expanding use of AI potentially changes this. This research explores
whether trust and privacy concern are barriers to the adoption of AI in health
insurance. Two scenarios are compared: The first scenario has limited AI that
is not in the interface and its presence is not explicitly revealed to the
consumer. In the second scenario there is an AI interface and AI evaluation,
and this is explicitly revealed to the consumer. The two scenarios were modeled
and compared using SEM PLS-MGA. The findings show that trust is significantly
lower in the second scenario where AI is visible. Privacy concerns are higher
with AI but the difference is not statistically significant within the model.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.11225v1">Protecting Personalized Trajectory with Differential Privacy under
  Temporal Correlations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-01-20T12:59:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mingge Cao, Haopeng Zhu, Minghui Min, Yulu Li, Shiyin Li, Hongliang Zhang, Zhu Han</p>
    <p><b>Summary:</b> Location-based services (LBSs) in vehicular ad hoc networks (VANETs) offer
users numerous conveniences. However, the extensive use of LBSs raises concerns
about the privacy of users' trajectories, as adversaries can exploit temporal
correlations between different locations to extract personal information.
Additionally, users have varying privacy requirements depending on the time and
location. To address these issues, this paper proposes a personalized
trajectory privacy protection mechanism (PTPPM). This mechanism first uses the
temporal correlation between trajectory locations to determine the possible
location set for each time instant. We identify a protection location set (PLS)
for each location by employing the Hilbert curve-based minimum distance search
algorithm. This approach incorporates the complementary features of
geo-indistinguishability and distortion privacy. We put forth a novel
Permute-and-Flip mechanism for location perturbation, which maps its initial
application in data publishing privacy protection to a location perturbation
mechanism. This mechanism generates fake locations with smaller perturbation
distances while improving the balance between privacy and quality of service
(QoS). Simulation results show that our mechanism outperforms the benchmark by
providing enhanced privacy protection while meeting user's QoS requirements.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.11089v1">FedRKG: A Privacy-preserving Federated Recommendation Framework via
  Knowledge Graph Enhancement</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2024-01-20T02:38:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dezhong Yao, Tongtong Liu, Qi Cao, Hai Jin</p>
    <p><b>Summary:</b> Federated Learning (FL) has emerged as a promising approach for preserving
data privacy in recommendation systems by training models locally. Recently,
Graph Neural Networks (GNN) have gained popularity in recommendation tasks due
to their ability to capture high-order interactions between users and items.
However, privacy concerns prevent the global sharing of the entire user-item
graph. To address this limitation, some methods create pseudo-interacted items
or users in the graph to compensate for missing information for each client.
Unfortunately, these methods introduce random noise and raise privacy concerns.
In this paper, we propose FedRKG, a novel federated recommendation system,
where a global knowledge graph (KG) is constructed and maintained on the server
using publicly available item information, enabling higher-order user-item
interactions. On the client side, a relation-aware GNN model leverages diverse
KG relationships. To protect local interaction items and obscure gradients, we
employ pseudo-labeling and Local Differential Privacy (LDP). Extensive
experiments conducted on three real-world datasets demonstrate the competitive
performance of our approach compared to centralized algorithms while ensuring
privacy preservation. Moreover, FedRKG achieves an average accuracy improvement
of 4% compared to existing federated learning baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.10765v2">Starlit: Privacy-Preserving Federated Learning to Enhance Financial
  Fraud Detection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-01-19T15:37:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aydin Abadi, Bradley Doyle, Francesco Gini, Kieron Guinamard, Sasi Kumar Murakonda, Jack Liddell, Paul Mellor, Steven J. Murdoch, Mohammad Naseri, Hector Page, George Theodorakopoulos, Suzanne Weller</p>
    <p><b>Summary:</b> Federated Learning (FL) is a data-minimization approach enabling
collaborative model training across diverse clients with local data, avoiding
direct data exchange. However, state-of-the-art FL solutions to identify
fraudulent financial transactions exhibit a subset of the following
limitations. They (1) lack a formal security definition and proof, (2) assume
prior freezing of suspicious customers' accounts by financial institutions
(limiting the solutions' adoption), (3) scale poorly, involving either $O(n^2)$
computationally expensive modular exponentiation (where $n$ is the total number
of financial institutions) or highly inefficient fully homomorphic encryption,
(4) assume the parties have already completed the identity alignment phase,
hence excluding it from the implementation, performance evaluation, and
security analysis, and (5) struggle to resist clients' dropouts. This work
introduces Starlit, a novel scalable privacy-preserving FL mechanism that
overcomes these limitations. It has various applications, such as enhancing
financial fraud detection, mitigating terrorism, and enhancing digital health.
We implemented Starlit and conducted a thorough performance analysis using
synthetic data from a key player in global financial transactions. The
evaluation indicates Starlit's scalability, efficiency, and accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.09604v1">MedBlindTuner: Towards Privacy-preserving Fine-tuning on Biomedical
  Images with Transformers and Fully Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-01-17T21:30:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Prajwal Panzade, Daniel Takabi, Zhipeng Cai</p>
    <p><b>Summary:</b> Advancements in machine learning (ML) have significantly revolutionized
medical image analysis, prompting hospitals to rely on external ML services.
However, the exchange of sensitive patient data, such as chest X-rays, poses
inherent privacy risks when shared with third parties. Addressing this concern,
we propose MedBlindTuner, a privacy-preserving framework leveraging fully
homomorphic encryption (FHE) and a data-efficient image transformer (DEiT).
MedBlindTuner enables the training of ML models exclusively on FHE-encrypted
medical images. Our experimental evaluation demonstrates that MedBlindTuner
achieves comparable accuracy to models trained on non-encrypted images,
offering a secure solution for outsourcing ML computations while preserving
patient data privacy. To the best of our knowledge, this is the first work that
uses data-efficient image transformers and fully homomorphic encryption in this
domain.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.09519v1">Privacy Engineering in Smart Home (SH) Systems: A Comprehensive Privacy
  Threat Analysis and Risk Management Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-01-17T17:34:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Emmanuel Dare Alalade, Mohammed Mahyoub, Ashraf Matrawy</p>
    <p><b>Summary:</b> Addressing trust concerns in Smart Home (SH) systems is imperative due to the
limited study on preservation approaches that focus on analyzing and evaluating
privacy threats for effective risk management. While most research focuses
primarily on user privacy, device data privacy, especially identity privacy, is
almost neglected, which can significantly impact overall user privacy within
the SH system. To this end, our study incorporates privacy engineering (PE)
principles in the SH system that consider user and device data privacy. We
start with a comprehensive reference model for a typical SH system. Based on
the initial stage of LINDDUN PRO for the PE framework, we present a data flow
diagram (DFD) based on a typical SH reference model to better understand SH
system operations. To identify potential areas of privacy threat and perform a
privacy threat analysis (PTA), we employ the LINDDUN PRO threat model. Then, a
privacy impact assessment (PIA) was carried out to implement privacy risk
management by prioritizing privacy threats based on their likelihood of
occurrence and potential consequences. Finally, we suggest possible privacy
enhancement techniques (PETs) that can mitigate some of these threats. The
study aims to elucidate the main threats to privacy, associated risks, and
effective prioritization of privacy control in SH systems. The outcomes of this
study are expected to benefit SH stakeholders, including vendors, cloud
providers, users, researchers, and regulatory bodies in the SH systems domain.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.08935v1">Privacy Protected Contactless Cardio-respiratory Monitoring using
  Defocused Cameras during Sleep</a></h3>
  
  <p><b>Published on:</b> 2024-01-17T03:05:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yingen Zhu, Jia Huang, Hongzhou Lu, Wenjin Wang</p>
    <p><b>Summary:</b> The monitoring of vital signs such as heart rate (HR) and respiratory rate
(RR) during sleep is important for the assessment of sleep quality and
detection of sleep disorders. Camera-based HR and RR monitoring gained
popularity in sleep monitoring in recent years. However, they are all facing
with serious privacy issues when using a video camera in the sleeping scenario.
In this paper, we propose to use the defocused camera to measure vital signs
from optically blurred images, which can fundamentally eliminate the privacy
invasion as face is difficult to be identified in obtained blurry images. A
spatial-redundant framework involving living-skin detection is used to extract
HR and RR from the defocused camera in NIR, and a motion metric is designed to
exclude outliers caused by body motions. In the benchmark, the overall Mean
Absolute Error (MAE) for HR measurement is 4.4 bpm, for RR measurement is 5.9
bpm. Both have quality drops as compared to the measurement using a focused
camera, but the degradation in HR is much less, i.e. HR measurement has strong
correlation with the reference ($R \geq 0.90$). Preliminary experiments suggest
that it is feasible to use a defocused camera for cardio-respiratory monitoring
while protecting the privacy. Further improvement is needed for robust RR
measurement, such as by PPG-modulation based RR extraction.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.08458v1">Security and Privacy Issues and Solutions in Federated Learning for
  Digital Healthcare</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-01-16T16:07:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hyejun Jeong, Tai-Myoung Chung</p>
    <p><b>Summary:</b> The advent of Federated Learning has enabled the creation of a
high-performing model as if it had been trained on a considerable amount of
data. A multitude of participants and a server cooperatively train a model
without the need for data disclosure or collection. The healthcare industry,
where security and privacy are paramount, can substantially benefit from this
new learning paradigm, as data collection is no longer feasible due to
stringent data policies. Nonetheless, unaddressed challenges and insufficient
attack mitigation are hampering its adoption. Attack surfaces differ from
traditional centralized learning in that the server and clients communicate
between each round of training. In this paper, we thus present vulnerabilities,
attacks, and defenses based on the widened attack surfaces, as well as suggest
promising new research directions toward a more robust FL.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.08723v1">HierSFL: Local Differential Privacy-aided Split Federated Learning in
  Mobile Edge Computing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-01-16T09:34:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Minh K. Quan, Dinh C. Nguyen, Van-Dinh Nguyen, Mayuri Wijayasundara, Sujeeva Setunge, Pubudu N. Pathirana</p>
    <p><b>Summary:</b> Federated Learning is a promising approach for learning from user data while
preserving data privacy. However, the high requirements of the model training
process make it difficult for clients with limited memory or bandwidth to
participate. To tackle this problem, Split Federated Learning is utilized,
where clients upload their intermediate model training outcomes to a cloud
server for collaborative server-client model training. This methodology
facilitates resource-constrained clients' participation in model training but
also increases the training time and communication overhead. To overcome these
limitations, we propose a novel algorithm, called Hierarchical Split Federated
Learning (HierSFL), that amalgamates models at the edge and cloud phases,
presenting qualitative directives for determining the best aggregation
timeframes to reduce computation and communication expenses. By implementing
local differential privacy at the client and edge server levels, we enhance
privacy during local model parameter updates. Our experiments using CIFAR-10
and MNIST datasets show that HierSFL outperforms standard FL approaches with
better training accuracy, training time, and communication-computing
trade-offs. HierSFL offers a promising solution to mobile edge computing's
challenges, ultimately leading to faster content delivery and improved mobile
service quality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.08038v1">Calpric: Inclusive and Fine-grain Labeling of Privacy Policies with
  Crowdsourcing and Active Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-01-16T01:27:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenjun Qiu, David Lie, Lisa Austin</p>
    <p><b>Summary:</b> A significant challenge to training accurate deep learning models on privacy
policies is the cost and difficulty of obtaining a large and comprehensive set
of training data. To address these challenges, we present Calpric , which
combines automatic text selection and segmentation, active learning and the use
of crowdsourced annotators to generate a large, balanced training set for
privacy policies at low cost. Automated text selection and segmentation
simplifies the labeling task, enabling untrained annotators from crowdsourcing
platforms, like Amazon's Mechanical Turk, to be competitive with trained
annotators, such as law students, and also reduces inter-annotator agreement,
which decreases labeling cost. Having reliable labels for training enables the
use of active learning, which uses fewer training samples to efficiently cover
the input space, further reducing cost and improving class and data category
balance in the data set. The combination of these techniques allows Calpric to
produce models that are accurate over a wider range of data categories, and
provide more detailed, fine-grain labels than previous work. Our crowdsourcing
process enables Calpric to attain reliable labeled data at a cost of roughly
$0.92-$1.71 per labeled text segment. Calpric 's training process also
generates a labeled data set of 16K privacy policy text segments across 9 Data
categories with balanced positive and negative samples.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.08037v1">Understanding factors behind IoT privacy -- A user's perspective on RF
  sensors</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-01-16T01:13:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Akash Deep Singh, Brian Wang, Luis Garcia, Xiang Chen, Mani Srivastava</p>
    <p><b>Summary:</b> While IoT sensors in physical spaces have provided utility and comfort in our
lives, their instrumentation in private and personal spaces has led to growing
concerns regarding privacy. The existing notion behind IoT privacy is that the
sensors whose data can easily be understood and interpreted by humans (such as
cameras) are more privacy-invasive than sensors that are not
human-understandable, such as RF (radio-frequency) sensors. However, given
recent advancements in machine learning, we can not only make sensitive
inferences on RF data but also translate between modalities. Thus, the existing
notions of privacy for IoT sensors need to be revisited. In this paper, our
goal is to understand what factors affect the privacy notions of a non-expert
user (someone who is not well-versed in privacy concepts). To this regard, we
conduct an online study of 162 participants from the USA to find out what
factors affect the privacy perception of a user regarding an RF-based device or
a sensor. Our findings show that a user's perception of privacy not only
depends upon the data collected by the sensor but also on the inferences that
can be made on that data, familiarity with the device and its form factor as
well as the control a user has over the device design and its data policies.
When the data collected by the sensor is not human-interpretable, it is the
inferences that can be made on the data and not the data itself that users care
about when making informed decisions regarding device privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.07691v1">Privacy-Aware Single-Nucleotide Polymorphisms (SNPs) using Bilinear
  Group Accumulators in Batch Mode</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-01-15T13:59:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> William J Buchanan, Sam Grierson, Daniel Uribe</p>
    <p><b>Summary:</b> Biometric data is often highly sensitive, and a leak of this data can lead to
serious privacy breaches. Some of the most sensitive of this type of data
relates to the usage of DNA data on individuals. A leak of this type of data
without consent could lead to privacy breaches of data protection laws. Along
with this, there have been several recent data breaches related to the leak of
DNA information, including from 23andMe and Ancestry. It is thus fundamental
that a citizen should have the right to know if their DNA data is contained
within a DNA database and ask for it to be removed if they are concerned about
its usage. This paper outlines a method of hashing the core information
contained within the data stores - known as Single-Nucleotide Polymorphisms
(SNPs) - into a bilinear group accumulator in batch mode, which can then be
searched by a trusted entity for matches. The time to create the witness proof
and to verify were measured at 0.86 ms and 10.90 ms, respectively.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.10158v1">DISTINQT: A Distributed Privacy Aware Learning Framework for QoS
  Prediction for Future Mobile and Wireless Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-01-15T13:00:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nikolaos Koursioumpas, Lina Magoula, Ioannis Stavrakakis, Nancy Alonistioti, M. A. Gutierrez-Estevez, Ramin Khalili</p>
    <p><b>Summary:</b> Beyond 5G and 6G networks are expected to support new and challenging use
cases and applications that depend on a certain level of Quality of Service
(QoS) to operate smoothly. Predicting the QoS in a timely manner is of high
importance, especially for safety-critical applications as in the case of
vehicular communications. Although until recent years the QoS prediction has
been carried out by centralized Artificial Intelligence (AI) solutions, a
number of privacy, computational, and operational concerns have emerged.
Alternative solutions have been surfaced (e.g. Split Learning, Federated
Learning), distributing AI tasks of reduced complexity across nodes, while
preserving the privacy of the data. However, new challenges rise when it comes
to scalable distributed learning approaches, taking into account the
heterogeneous nature of future wireless networks. The current work proposes
DISTINQT, a privacy-aware distributed learning framework for QoS prediction.
Our framework supports multiple heterogeneous nodes, in terms of data types and
model architectures, by sharing computations across them. This, enables the
incorporation of diverse knowledge into a sole learning process that will
enhance the robustness and generalization capabilities of the final QoS
prediction model. DISTINQT also contributes to data privacy preservation by
encoding any raw input data into a non-linear latent representation before any
transmission. Evaluation results showcase that our framework achieves a
statistically identical performance compared to its centralized version and an
average performance improvement of up to 65% against six state-of-the-art
centralized baseline solutions in the Tele-Operated Driving use case.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.07464v1">Quantum Privacy Aggregation of Teacher Ensembles (QPATE) for
  Privacy-preserving Quantum Machine Learning</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-01-15T04:38:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> William Watkins, Heehwan Wang, Sangyoon Bae, Huan-Hsin Tseng, Jiook Cha, Samuel Yen-Chi Chen, Shinjae Yoo</p>
    <p><b>Summary:</b> The utility of machine learning has rapidly expanded in the last two decades
and presents an ethical challenge. Papernot et. al. developed a technique,
known as Private Aggregation of Teacher Ensembles (PATE) to enable federated
learning in which multiple teacher models are trained on disjoint datasets.
This study is the first to apply PATE to an ensemble of quantum neural networks
(QNN) to pave a new way of ensuring privacy in quantum machine learning (QML)
models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.07348v1">Generative AI in EU Law: Liability, Privacy, Intellectual Property, and
  Cybersecurity</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-01-14T19:16:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Claudio Novelli, Federico Casolari, Philipp Hacker, Giorgio Spedicato, Luciano Floridi</p>
    <p><b>Summary:</b> The advent of Generative AI, particularly through Large Language Models
(LLMs) like ChatGPT and its successors, marks a paradigm shift in the AI
landscape. Advanced LLMs exhibit multimodality, handling diverse data formats,
thereby broadening their application scope. However, the complexity and
emergent autonomy of these models introduce challenges in predictability and
legal compliance. This paper delves into the legal and regulatory implications
of Generative AI and LLMs in the European Union context, analyzing aspects of
liability, privacy, intellectual property, and cybersecurity. It critically
examines the adequacy of the existing and proposed EU legislation, including
the Artificial Intelligence Act (AIA) draft, in addressing the unique
challenges posed by Generative AI in general and LLMs in particular. The paper
identifies potential gaps and shortcomings in the legislative framework and
proposes recommendations to ensure the safe and compliant deployment of
generative models, ensuring they align with the EU's evolving digital landscape
and legal standards.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.07343v2">Privacy-Preserving Intrusion Detection in Software-defined VANET using
  Federated Learning with BERT</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-01-14T18:32:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shakil Ibne Ahsan, Phil Legg, S M Iftekharul Alam</p>
    <p><b>Summary:</b> The absence of robust security protocols renders the VANET (Vehicle ad-hoc
Networks) network open to cyber threats by compromising passengers and road
safety. Intrusion Detection Systems (IDS) are widely employed to detect network
security threats. With vehicles' high mobility on the road and diverse
environments, VANETs devise ever-changing network topologies, lack privacy and
security, and have limited bandwidth efficiency. The absence of privacy
precautions, End-to-End Encryption methods, and Local Data Processing systems
in VANET also present many privacy and security difficulties. So, assessing
whether a novel real-time processing IDS approach can be utilized for this
emerging technology is crucial. The present study introduces a novel approach
for intrusion detection using Federated Learning (FL) capabilities in
conjunction with the BERT model for sequence classification (FL-BERT). The
significance of data privacy is duly recognized. According to FL methodology,
each client has its own local model and dataset. They train their models
locally and then send the model's weights to the server. After aggregation, the
server aggregates the weights from all clients to update a global model. After
aggregation, the global model's weights are shared with the clients. This
practice guarantees the secure storage of sensitive raw data on individual
clients' devices, effectively protecting privacy. After conducting the
federated learning procedure, we assessed our models' performance using a
separate test dataset. The FL-BERT technique has yielded promising results,
opening avenues for further investigation in this particular area of research.
We reached the result of our approaches by comparing existing research works
and found that FL-BERT is more effective for privacy and security concerns. Our
results suggest that FL-BERT is a promising technique for enhancing attack
detection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.07316v1">Finding Privacy-relevant Source Code</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-01-14T15:38:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Feiyang Tang, Bjarte M. Østvold</p>
    <p><b>Summary:</b> Privacy code review is a critical process that enables developers and legal
experts to ensure compliance with data protection regulations. However, the
task is challenging due to resource constraints. To address this, we introduce
the concept of privacy-relevant methods - specific methods in code that are
directly involved in the processing of personal data. We then present an
automated approach to assist in code review by identifying and categorizing
these privacy-relevant methods in source code.
  Using static analysis, we identify a set of methods based on their
occurrences in 50 commonly used libraries. We then rank these methods according
to their frequency of invocation with actual personal data in the top 30 GitHub
applications. The highest-ranked methods are the ones we designate as
privacy-relevant in practice. For our evaluation, we examined 100 open-source
applications and found that our approach identifies fewer than 5% of the
methods as privacy-relevant for personal data processing. This reduces the time
required for code reviews. Case studies on Signal Desktop and Cal.com further
validate the effectiveness of our approach in aiding code reviewers to produce
enhanced reports that facilitate compliance with privacy regulations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.06894v1">On Coded Caching Systems with Offline Users, with and without Demand
  Privacy against Colluding Users</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2024-01-12T21:06:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yinbin Ma, Daniela Tuninetti</p>
    <p><b>Summary:</b> Coded caching is a technique that leverages locally cached contents at the
end users to reduce the network's peak-time communication load. Coded caching
has been shown to achieve significant performance gains compared to uncoded
schemes and is thus considered a promising technique to boost performance in
future networks by effectively trading off bandwidth for storage. The original
coded caching model introduced by Maddah-Ali and Niesen does not consider the
case where some users involved in the placement phase, may be offline during
the delivery phase. If so, the delivery may not start or it may be wasteful to
perform the delivery with fictitious demands for the offline users. In
addition, the active users may require their demand to be kept private. This
paper formally defines a coded caching system where some users are offline, and
investigates the optimal performance with and without demand privacy against
colluding users. For this novel coded caching model with offline users,
achievable and converse bounds are proposed. These bounds are shown to meet
under certain conditions, and otherwise to be to within a constant
multiplicative gap of one another. In addition, the proposed achievable schemes
have lower subpacketization and lower load compared to baseline schemes (that
trivially extend known schemes so as to accommodate for privacy) in some memory
regimes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.06883v1">Scaling While Privacy Preserving: A Comprehensive Synthetic Tabular Data
  Generation and Evaluation in Learning Analytics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-01-12T20:27:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qinyi Liu, Mohammad Khalil, Ronas Shakya, Jelena Jovanovic</p>
    <p><b>Summary:</b> Privacy poses a significant obstacle to the progress of learning analytics
(LA), presenting challenges like inadequate anonymization and data misuse that
current solutions struggle to address. Synthetic data emerges as a potential
remedy, offering robust privacy protection. However, prior LA research on
synthetic data lacks thorough evaluation, essential for assessing the delicate
balance between privacy and data utility. Synthetic data must not only enhance
privacy but also remain practical for data analytics. Moreover, diverse LA
scenarios come with varying privacy and utility needs, making the selection of
an appropriate synthetic data approach a pressing challenge. To address these
gaps, we propose a comprehensive evaluation of synthetic data, which
encompasses three dimensions of synthetic data quality, namely resemblance,
utility, and privacy. We apply this evaluation to three distinct LA datasets,
using three different synthetic data generation methods. Our results show that
synthetic data can maintain similar utility (i.e., predictive performance) as
real data, while preserving privacy. Furthermore, considering different privacy
and data utility requirements in different LA scenarios, we make customized
recommendations for synthetic data generation. This paper not only presents a
comprehensive evaluation of synthetic data but also illustrates its potential
in mitigating privacy concerns within the field of LA, thus contributing to a
wider application of synthetic data in LA and promoting a better practice for
open science.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.06657v1">Accelerating Tactile Internet with QUIC: A Security and Privacy
  Perspective</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2024-01-12T16:05:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jayasree Sengupta, Debasmita Dey, Simone Ferlin, Nirnay Ghosh, Vaibhav Bajpai</p>
    <p><b>Summary:</b> The Tactile Internet paradigm is set to revolutionize human society by
enabling skill-set delivery and haptic communication over ultra-reliable,
low-latency networks. The emerging sixth-generation (6G) mobile communication
systems are envisioned to underpin this Tactile Internet ecosystem at the
network edge by providing ubiquitous global connectivity. However, apart from a
multitude of opportunities of the Tactile Internet, security and privacy
challenges emerge at the forefront. We believe that the recently standardized
QUIC protocol, characterized by end-to-end encryption and reduced round-trip
delay would serve as the backbone of Tactile Internet. In this article, we
envision a futuristic scenario where a QUIC-enabled network uses the underlying
6G communication infrastructure to achieve the requirements for Tactile
Internet. Interestingly this requires a deeper investigation of a wide range of
security and privacy challenges in QUIC, that need to be mitigated for its
adoption in Tactile Internet. Henceforth, this article reviews the existing
security and privacy attacks in QUIC and their implication on users. Followed
by that, we discuss state-of-the-art attack mitigation strategies and
investigate some of their drawbacks with possible directions for future work</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.06601v1">A proposal to increase data utility on Global Differential Privacy data
  based on data use predictions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2024-01-12T14:34:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Henry C. Nunes, Marlon P. da Silva, Charles V. Neu, Avelino F. Zorzo</p>
    <p><b>Summary:</b> This paper presents ongoing research focused on improving the utility of data
protected by Global Differential Privacy(DP) in the scenario of summary
statistics. Our approach is based on predictions on how an analyst will use
statistics released under DP protection, so that a developer can optimise data
utility on further usage of the data in the privacy budget allocation. This
novel approach can potentially improve the utility of data without compromising
privacy constraints. We also propose a metric that can be used by the developer
to optimise the budget allocation process.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.05835v1">Privacy Analysis of Affine Transformations in Cloud-based MPC:
  Vulnerability to Side-knowledge</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2024-01-11T11:08:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Teimour Hosseinalizadeh, Nils Schlüter, Moritz Schulze Darup, Nima Monshizadeh</p>
    <p><b>Summary:</b> Search for the optimizer in computationally demanding model predictive
control (MPC) setups can be facilitated by Cloud as a service provider in
cyber-physical systems. This advantage introduces the risk that Cloud can
obtain unauthorized access to the privacy-sensitive parameters of the system
and cost function. To solve this issue, i.e., preventing Cloud from accessing
the parameters while benefiting from Cloud computation, random affine
transformations provide an exact yet light weight in computation solution. This
research deals with analyzing privacy preserving properties of these
transformations when they are adopted for MPC problems. We consider two common
strategies for outsourcing the optimization required in MPC problems, namely
separate and dense forms, and establish that random affine transformations
utilized in these forms are vulnerable to side-knowledge from Cloud.
Specifically, we prove that the privacy guarantees of these methods and their
extensions for separate form are undermined when a mild side-knowledge about
the problem in terms of structure of MPC cost function is available. In
addition, while we prove that outsourcing the MPC problem in the dense form
inherently leads to some degree of privacy for the system and cost function
parameters, we also establish that affine transformations applied to this form
are nevertheless prone to be undermined by a Cloud with mild side-knowledge.
Numerical simulations confirm our results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.05562v1">Brave: Byzantine-Resilient and Privacy-Preserving Peer-to-Peer Federated
  Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-01-10T22:07:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhangchen Xu, Fengqing Jiang, Luyao Niu, Jinyuan Jia, Radha Poovendran</p>
    <p><b>Summary:</b> Federated learning (FL) enables multiple participants to train a global
machine learning model without sharing their private training data.
Peer-to-peer (P2P) FL advances existing centralized FL paradigms by eliminating
the server that aggregates local models from participants and then updates the
global model. However, P2P FL is vulnerable to (i) honest-but-curious
participants whose objective is to infer private training data of other
participants, and (ii) Byzantine participants who can transmit arbitrarily
manipulated local models to corrupt the learning process. P2P FL schemes that
simultaneously guarantee Byzantine resilience and preserve privacy have been
less studied. In this paper, we develop Brave, a protocol that ensures
Byzantine Resilience And privacy-preserving property for P2P FL in the presence
of both types of adversaries. We show that Brave preserves privacy by
establishing that any honest-but-curious adversary cannot infer other
participants' private data by observing their models. We further prove that
Brave is Byzantine-resilient, which guarantees that all benign participants
converge to an identical model that deviates from a global model trained
without Byzantine adversaries by a bounded distance. We evaluate Brave against
three state-of-the-art adversaries on a P2P FL for image classification tasks
on benchmark datasets CIFAR10 and MNIST. Our results show that the global model
learned with Brave in the presence of adversaries achieves comparable
classification accuracy to a global model trained in the absence of any
adversary.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.05126v1">Efficient Fine-Tuning with Domain Adaptation for Privacy-Preserving
  Vision Transformer</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-01-10T12:46:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Teru Nagamori, Sayaka Shiota, Hitoshi Kiya</p>
    <p><b>Summary:</b> We propose a novel method for privacy-preserving deep neural networks (DNNs)
with the Vision Transformer (ViT). The method allows us not only to train
models and test with visually protected images but to also avoid the
performance degradation caused from the use of encrypted images, whereas
conventional methods cannot avoid the influence of image encryption. A domain
adaptation method is used to efficiently fine-tune ViT with encrypted images.
In experiments, the method is demonstrated to outperform conventional methods
in an image classification task on the CIFAR-10 and ImageNet datasets in terms
of classification accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.04423v1">Privacy-Preserving Sequential Recommendation with Collaborative
  Confusion</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2024-01-09T08:30:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wei Wang, Yujie Lin, Pengjie Ren, Zhumin Chen, Tsunenori Mine, Jianli Zhao, Qiang Zhao, Moyan Zhang, Xianye Ben, Yujun Li</p>
    <p><b>Summary:</b> Sequential recommendation has attracted a lot of attention from both academia
and industry, however the privacy risks associated to gathering and
transferring users' personal interaction data are often underestimated or
ignored. Existing privacy-preserving studies are mainly applied to traditional
collaborative filtering or matrix factorization rather than sequential
recommendation. Moreover, these studies are mostly based on differential
privacy or federated learning, which often leads to significant performance
degradation, or has high requirements for communication. In this work, we
address privacy-preserving from a different perspective. Unlike existing
research, we capture collaborative signals of neighbor interaction sequences
and directly inject indistinguishable items into the target sequence before the
recommendation process begins, thereby increasing the perplexity of the target
sequence. Even if the target interaction sequence is obtained by attackers, it
is difficult to discern which ones are the actual user interaction records. To
achieve this goal, we propose a CoLlaborative-cOnfusion seqUential recommenDer,
namely CLOUD, which incorporates a collaborative confusion mechanism to edit
the raw interaction sequences before conducting recommendation. Specifically,
CLOUD first calculates the similarity between the target interaction sequence
and other neighbor sequences to find similar sequences. Then, CLOUD considers
the shared representation of the target sequence and similar sequences to
determine the operation to be performed: keep, delete, or insert. We design a
copy mechanism to make items from similar sequences have a higher probability
to be inserted into the target sequence. Finally, the modified sequence is used
to train the recommender and predict the next item.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.04306v1">Renyi Differential Privacy in the Shuffle Model: Enhanced Amplification
  Bounds</a></h3>
  
  <p><b>Published on:</b> 2024-01-09T01:47:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> E Chen, Yang Cao, Yifei Ge</p>
    <p><b>Summary:</b> The shuffle model of Differential Privacy (DP) has gained significant
attention in privacy-preserving data analysis due to its remarkable tradeoff
between privacy and utility. It is characterized by adding a shuffling
procedure after each user's locally differentially private perturbation, which
leads to a privacy amplification effect, meaning that the privacy guarantee of
a small level of noise, say $\epsilon_0$, can be enhanced to
$O(\epsilon_0/\sqrt{n})$ (the smaller, the more private) after shuffling all
$n$ users' perturbed data. Most studies in the shuffle DP focus on proving a
tighter privacy guarantee of privacy amplification. However, the current
results assume that the local privacy budget $\epsilon_0$ is within a limited
range. In addition, there remains a gap between the tightest lower bound and
the known upper bound of the privacy amplification. In this work, we push
forward the state-of-the-art by making the following contributions. Firstly, we
present the first asymptotically optimal analysis of Renyi Differential Privacy
(RDP) in the shuffle model without constraints on $\epsilon_0$. Secondly, we
introduce hypothesis testing for privacy amplification through shuffling,
offering a distinct analysis technique and a tighter upper bound. Furthermore,
we propose a DP-SGD algorithm based on RDP. Experiments demonstrate that our
approach outperforms existing methods significantly at the same privacy level.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.04076v2">Security and Privacy Issues in Cloud Storage</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2024-01-08T18:27:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Norah Asiri</p>
    <p><b>Summary:</b> Even with the vast potential that cloud computing has, so far, it has not
been adopted by the consumers with the enthusiasm and pace that it be worthy;
this is a very reason statement why consumers still hesitated of using cloud
computing for their sensitive data and the threats that prevent the consumers
from shifting to use cloud computing in general and cloud storage in
particular. The cloud computing inherits the traditional potential security and
privacy threats besides its own issues due to its unique structures. Some
threats related to cloud computing are the insider malicious attacks from the
employees that even sometime the provider unconscious about, the lack of
transparency of agreement between consumer and provider, data loss, traffic
hijacking, shared technology and insecure application interface. Such threats
need remedies to make the consumer use its features in secure way. In this
review, we spot the light on the most security and privacy issues which can be
attributed as gaps that sometimes the consumers or even the enterprises are not
aware of. We also define the parties that involve in scenario of cloud
computing that also may attack the entire cloud systems. We also show the
consequences of these threats.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.03883v2">The Impact of Differential Privacy on Recommendation Accuracy and
  Popularity Bias</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2024-01-08T13:31:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Peter Müllner, Elisabeth Lex, Markus Schedl, Dominik Kowald</p>
    <p><b>Summary:</b> Collaborative filtering-based recommender systems leverage vast amounts of
behavioral user data, which poses severe privacy risks. Thus, often, random
noise is added to the data to ensure Differential Privacy (DP). However, to
date, it is not well understood, in which ways this impacts personalized
recommendations. In this work, we study how DP impacts recommendation accuracy
and popularity bias, when applied to the training data of state-of-the-art
recommendation models. Our findings are three-fold: First, we find that nearly
all users' recommendations change when DP is applied. Second, recommendation
accuracy drops substantially while recommended item popularity experiences a
sharp increase, suggesting that popularity bias worsens. Third, we find that DP
exacerbates popularity bias more severely for users who prefer unpopular items
than for users that prefer popular items.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.03552v1">Privacy-Preserving in Blockchain-based Federated Learning Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-01-07T17:23:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sameera K. M., Serena Nicolazzo, Marco Arazzi, Antonino Nocera, Rafidha Rehiman K. A., Vinod P, Mauro Conti</p>
    <p><b>Summary:</b> Federated Learning (FL) has recently arisen as a revolutionary approach to
collaborative training Machine Learning models. According to this novel
framework, multiple participants train a global model collaboratively,
coordinating with a central aggregator without sharing their local data. As FL
gains popularity in diverse domains, security, and privacy concerns arise due
to the distributed nature of this solution. Therefore, integrating this
strategy with Blockchain technology has been consolidated as a preferred choice
to ensure the privacy and security of participants.
  This paper explores the research efforts carried out by the scientific
community to define privacy solutions in scenarios adopting Blockchain-Enabled
FL. It comprehensively summarizes the background related to FL and Blockchain,
evaluates existing architectures for their integration, and the primary attacks
and possible countermeasures to guarantee privacy in this setting. Finally, it
reviews the main application scenarios where Blockchain-Enabled FL approaches
have been proficiently applied. This survey can help academia and industry
practitioners understand which theories and techniques exist to improve the
performance of FL through Blockchain to preserve privacy and which are the main
challenges and future directions in this novel and still under-explored
context. We believe this work provides a novel contribution respect to the
previous surveys and is a valuable tool to explore the current landscape,
understand perspectives, and pave the way for advancements or improvements in
this amalgamation of Blockchain and Federated Learning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.03218v2">MiniScope: Automated UI Exploration and Privacy Inconsistency Detection
  of MiniApps via Two-phase Iterative Hybrid Analysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2024-01-06T13:54:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shenao Wang, Yuekang Li, Kailong Wang, Yi Liu, Hui Li, Yang Liu, Haoyu Wang</p>
    <p><b>Summary:</b> The advent of MiniApps, operating within larger SuperApps, has revolutionized
user experiences by offering a wide range of services without the need for
individual app downloads. However, this convenience has raised significant
privacy concerns, as these MiniApps often require access to sensitive data,
potentially leading to privacy violations. Our research addresses the critical
gaps in the analysis of MiniApps' privacy practices, especially focusing on
WeChat MiniApps in the Android ecosystem. Despite existing privacy regulations
and platform guidelines, there is a lack of effective mechanisms to safeguard
user privacy fully. We introduce MiniScope, a novel two-phase hybrid analysis
approach, specifically designed for the MiniApp environment. This approach
overcomes the limitations of existing static analysis techniques by
incorporating dynamic UI exploration for complete code coverage and accurate
privacy practice identification. Our methodology includes modeling UI
transition states, resolving cross-package callback control flows, and
automated iterative UI exploration. This allows for a comprehensive
understanding of MiniApps' privacy practices, addressing the unique challenges
of sub-package loading and event-driven callbacks. Our empirical evaluation of
over 120K MiniApps using MiniScope demonstrates its effectiveness in
identifying privacy inconsistencies. The results reveal significant issues,
with 5.7% of MiniApps over-collecting private data and 33.4% overclaiming data
collection. These findings emphasize the urgent need for more precise privacy
monitoring systems and highlight the responsibility of SuperApp operators to
enforce stricter privacy measures.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.02453v1">Adaptive Differential Privacy in Federated Learning: A Priority-Based
  Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-01-04T03:01:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mahtab Talaei, Iman Izadi</p>
    <p><b>Summary:</b> Federated learning (FL) as one of the novel branches of distributed machine
learning (ML), develops global models through a private procedure without
direct access to local datasets. However, access to model updates (e.g.
gradient updates in deep neural networks) transferred between clients and
servers can reveal sensitive information to adversaries. Differential privacy
(DP) offers a framework that gives a privacy guarantee by adding certain
amounts of noise to parameters. This approach, although being effective in
terms of privacy, adversely affects model performance due to noise involvement.
Hence, it is always needed to find a balance between noise injection and the
sacrificed accuracy. To address this challenge, we propose adaptive noise
addition in FL which decides the value of injected noise based on features'
relative importance. Here, we first propose two effective methods for
prioritizing features in deep neural network models and then perturb models'
weights based on this information. Specifically, we try to figure out whether
the idea of adding more noise to less important parameters and less noise to
more important parameters can effectively save the model accuracy while
preserving privacy. Our experiments confirm this statement under some
conditions. The amount of noise injected, the proportion of parameters
involved, and the number of global iterations can significantly change the
output. While a careful choice of parameters by considering the properties of
datasets can improve privacy without intense loss of accuracy, a bad choice can
make the model performance worse.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.01589v1">The Security and Privacy of Mobile Edge Computing: An Artificial
  Intelligence Perspective</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-01-03T07:47:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Cheng Wang, Zenghui Yuan, Pan Zhou, Zichuan Xu, Ruixuan Li, Dapeng Oliver Wu</p>
    <p><b>Summary:</b> Mobile Edge Computing (MEC) is a new computing paradigm that enables cloud
computing and information technology (IT) services to be delivered at the
network's edge. By shifting the load of cloud computing to individual local
servers, MEC helps meet the requirements of ultralow latency, localized data
processing, and extends the potential of Internet of Things (IoT) for
end-users. However, the crosscutting nature of MEC and the multidisciplinary
components necessary for its deployment have presented additional security and
privacy concerns. Fortunately, Artificial Intelligence (AI) algorithms can cope
with excessively unpredictable and complex data, which offers a distinct
advantage in dealing with sophisticated and developing adversaries in the
security industry. Hence, in this paper we comprehensively provide a survey of
security and privacy in MEC from the perspective of AI. On the one hand, we use
European Telecommunications Standards Institute (ETSI) MEC reference
architecture as our based framework while merging the Software Defined Network
(SDN) and Network Function Virtualization (NFV) to better illustrate a
serviceable platform of MEC. On the other hand, we focus on new security and
privacy issues, as well as potential solutions from the viewpoints of AI.
Finally, we comprehensively discuss the opportunities and challenges associated
with applying AI to MEC security and privacy as possible future research
directions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.01575v1">Enhancing Generalization of Invisible Facial Privacy Cloak via Gradient
  Accumulation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-01-03T07:00:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xuannan Liu, Yaoyao Zhong, Weihong Deng, Hongzhi Shi, Xingchen Cui, Yunfeng Yin, Dongchao Wen</p>
    <p><b>Summary:</b> The blooming of social media and face recognition (FR) systems has increased
people's concern about privacy and security. A new type of adversarial privacy
cloak (class-universal) can be applied to all the images of regular users, to
prevent malicious FR systems from acquiring their identity information. In this
work, we discover the optimization dilemma in the existing methods -- the local
optima problem in large-batch optimization and the gradient information
elimination problem in small-batch optimization. To solve these problems, we
propose Gradient Accumulation (GA) to aggregate multiple small-batch gradients
into a one-step iterative gradient to enhance the gradient stability and reduce
the usage of quantization operations. Experiments show that our proposed method
achieves high performance on the Privacy-Commons dataset against black-box face
recognition models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.01294v1">Efficient Sparse Least Absolute Deviation Regression with Differential
  Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">  
  <p><b>Published on:</b> 2024-01-02T17:13:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Weidong Liu, Xiaojun Mao, Xiaofei Zhang, Xin Zhang</p>
    <p><b>Summary:</b> In recent years, privacy-preserving machine learning algorithms have
attracted increasing attention because of their important applications in many
scientific fields. However, in the literature, most privacy-preserving
algorithms demand learning objectives to be strongly convex and Lipschitz
smooth, which thus cannot cover a wide class of robust loss functions (e.g.,
quantile/least absolute loss). In this work, we aim to develop a fast
privacy-preserving learning solution for a sparse robust regression problem.
Our learning loss consists of a robust least absolute loss and an $\ell_1$
sparse penalty term. To fast solve the non-smooth loss under a given privacy
budget, we develop a Fast Robust And Privacy-Preserving Estimation (FRAPPE)
algorithm for least absolute deviation regression. Our algorithm achieves a
fast estimation by reformulating the sparse LAD problem as a penalized least
square estimation problem and adopts a three-stage noise injection to guarantee
the $(\epsilon,\delta)$-differential privacy. We show that our algorithm can
achieve better privacy and statistical accuracy trade-off compared with the
state-of-the-art privacy-preserving regression algorithms. In the end, we
conduct experiments to verify the efficiency of our proposed FRAPPE algorithm.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.01204v2">PPBFL: A Privacy Protected Blockchain-based Federated Learning Model</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-01-02T13:13:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yang Li, Chunhe Xia, Wanshuang Lin, Tianbo Wang</p>
    <p><b>Summary:</b> With the rapid development of machine learning and a growing concern for data
privacy, federated learning has become a focal point of attention. However,
attacks on model parameters and a lack of incentive mechanisms hinder the
effectiveness of federated learning. Therefore, we propose A Privacy Protected
Blockchain-based Federated Learning Model (PPBFL) to enhance the security of
federated learning and encourage active participation of nodes in model
training. Blockchain technology ensures the integrity of model parameters
stored in the InterPlanetary File System (IPFS), providing protection against
tampering. Within the blockchain, we introduce a Proof of Training Work (PoTW)
consensus algorithm tailored for federated learning, aiming to incentive
training nodes. This algorithm rewards nodes with greater computational power,
promoting increased participation and effort in the federated learning process.
A novel adaptive differential privacy algorithm is simultaneously applied to
local and global models. This safeguards the privacy of local data at training
clients, preventing malicious nodes from launching inference attacks.
Additionally, it enhances the security of the global model, preventing
potential security degradation resulting from the combination of numerous local
models. The possibility of security degradation is derived from the composition
theorem. By introducing reverse noise in the global model, a zero-bias estimate
of differential privacy noise between local and global models is achieved.
Furthermore, we propose a new mix transactions mechanism utilizing ring
signature technology to better protect the identity privacy of local training
clients. Security analysis and experimental results demonstrate that PPBFL,
compared to baseline methods, not only exhibits superior model performance but
also achieves higher security.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.01146v1">Privacy Preserving Personal Assistant with On-Device Diarization and
  Spoken Dialogue System for Home and Beyond</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-01-02T10:56:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gérard Chollet, Hugues Sansen, Yannis Tevissen, Jérôme Boudy, Mossaab Hariz, Christophe Lohr, Fathy Yassa</p>
    <p><b>Summary:</b> In the age of personal voice assistants, the question of privacy arises.
These digital companions often lack memory of past interactions, while relying
heavily on the internet for speech processing, raising privacy concerns. Modern
smartphones now enable on-device speech processing, making cloud-based
solutions unnecessary. Personal assistants for the elderly should excel at
memory recall, especially in medical examinations. The e-ViTA project developed
a versatile conversational application with local processing and speaker
recognition. This paper highlights the importance of speaker diarization
enriched with sensor data fusion for contextualized conversation preservation.
The use cases applied to the e-VITA project have shown that truly personalized
dialogue is pivotal for individual voice assistants. Secure local processing
and sensor data fusion ensure virtual companions meet individual user needs
without compromising privacy or data security.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.00973v1">Facebook Report on Privacy of fNIRS data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-01-01T23:30:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Md Imran Hossen, Sai Venkatesh Chilukoti, Liqun Shan, Vijay Srinivas Tida, Xiali Hei</p>
    <p><b>Summary:</b> The primary goal of this project is to develop privacy-preserving machine
learning model training techniques for fNIRS data. This project will build a
local model in a centralized setting with both differential privacy (DP) and
certified robustness. It will also explore collaborative federated learning to
train a shared model between multiple clients without sharing local fNIRS
datasets. To prevent unintentional private information leakage of such clients'
private datasets, we will also implement DP in the federated learning setting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.00794v1">Privacy-Preserving Data in IoT-based Cloud Systems: A Comprehensive
  Survey with AI Integration</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-01-01T15:48:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> D. Dhinakaran, S. M. Udhaya Sankar, D. Selvaraj, S. Edwin Raja</p>
    <p><b>Summary:</b> As the integration of Internet of Things devices with cloud computing
proliferates, the paramount importance of privacy preservation comes to the
forefront. This survey paper meticulously explores the landscape of privacy
issues in the dynamic intersection of IoT and cloud systems. The comprehensive
literature review synthesizes existing research, illuminating key challenges
and discerning emerging trends in privacy preserving techniques. The
categorization of diverse approaches unveils a nuanced understanding of
encryption techniques, anonymization strategies, access control mechanisms, and
the burgeoning integration of artificial intelligence. Notable trends include
the infusion of machine learning for dynamic anonymization, homomorphic
encryption for secure computation, and AI-driven access control systems. The
culmination of this survey contributes a holistic view, laying the groundwork
for understanding the multifaceted strategies employed in securing sensitive
data within IoT-based cloud environments. The insights garnered from this
survey provide a valuable resource for researchers, practitioners, and
policymakers navigating the complex terrain of privacy preservation in the
evolving landscape of IoT and cloud computing</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.00793v2">SecFormer: Towards Fast and Accurate Privacy-Preserving Inference for
  Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-01-01T15:40:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jinglong Luo, Yehong Zhang, Jiaqi Zhang, Xin Mu, Hui Wang, Yue Yu, Zenglin Xu</p>
    <p><b>Summary:</b> With the growing use of large language models hosted on cloud platforms to
offer inference services, privacy concerns are escalating, especially
concerning sensitive data like investment plans and bank account details.
Secure Multi-Party Computing (SMPC) emerges as a promising solution to protect
the privacy of inference data and model parameters. However, the application of
SMPC in Privacy-Preserving Inference (PPI) for large language models,
particularly those based on the Transformer architecture, often leads to
considerable slowdowns or declines in performance. This is largely due to the
multitude of nonlinear operations in the Transformer architecture, which are
not well-suited to SMPC and difficult to circumvent or optimize effectively. To
address this concern, we introduce an advanced optimization framework called
SecFormer, to achieve fast and accurate PPI for Transformer models. By
implementing model design optimization, we successfully eliminate the high-cost
exponential and maximum operations in PPI without sacrificing model
performance. Additionally, we have developed a suite of efficient SMPC
protocols that utilize segmented polynomials, Fourier series and Goldschmidt's
method to handle other complex nonlinear functions within PPI, such as GeLU,
LayerNorm, and Softmax. Our extensive experiments reveal that SecFormer
outperforms MPCFormer in performance, showing improvements of $5.6\%$ and
$24.2\%$ for BERT$_{\text{BASE}}$ and BERT$_{\text{LARGE}}$, respectively. In
terms of efficiency, SecFormer is 3.56 and 3.58 times faster than Puma for
BERT$_{\text{BASE}}$ and BERT$_{\text{LARGE}}$, demonstrating its effectiveness
and speed.</p>
  </details>
</div>



<h2>2023-12</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.00583v1">Improving the Privacy and Practicality of Objective Perturbation for
  Differentially Private Linear Learners</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-31T20:32:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rachel Redberg, Antti Koskela, Yu-Xiang Wang</p>
    <p><b>Summary:</b> In the arena of privacy-preserving machine learning, differentially private
stochastic gradient descent (DP-SGD) has outstripped the objective perturbation
mechanism in popularity and interest. Though unrivaled in versatility, DP-SGD
requires a non-trivial privacy overhead (for privately tuning the model's
hyperparameters) and a computational complexity which might be extravagant for
simple models such as linear and logistic regression. This paper revamps the
objective perturbation mechanism with tighter privacy analyses and new
computational tools that boost it to perform competitively with DP-SGD on
unconstrained convex generalized linear problems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.00879v1">SoK: Demystifying Privacy Enhancing Technologies Through the Lens of
  Software Developers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2023-12-30T12:24:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maisha Boteju, Thilina Ranbaduge, Dinusha Vatsalan, Nalin Asanka Gamagedara Arachchilage</p>
    <p><b>Summary:</b> In the absence of data protection measures, software applications lead to
privacy breaches, posing threats to end-users and software organisations.
Privacy Enhancing Technologies (PETs) are technical measures that protect
personal data, thus minimising such privacy breaches. However, for software
applications to deliver data protection using PETs, software developers should
actively and correctly incorporate PETs into the software they develop.
Therefore, to uncover ways to encourage and support developers to embed PETs
into software, this Systematic Literature Review (SLR) analyses 39 empirical
studies on developers' privacy practices. It reports the usage of six PETs in
software application scenarios. Then, it discusses challenges developers face
when integrating PETs into software, ranging from intrinsic challenges, such as
the unawareness of PETs, to extrinsic challenges, such as the increased
development cost. Next, the SLR presents the existing solutions to address
these challenges, along with the limitations of the solutions. Further, it
outlines future research avenues to better understand PETs from a developer
perspective and minimise the challenges developers face when incorporating PETs
into software.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.00870v1">Teach Large Language Models to Forget Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> 
  <p><b>Published on:</b> 2023-12-30T01:26:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ran Yan, Yujun Li, Wenqian Li, Peihua Mai, Yan Pang, Yinchuan Li</p>
    <p><b>Summary:</b> Large Language Models (LLMs) have proven powerful, but the risk of privacy
leakage remains a significant concern. Traditional privacy-preserving methods,
such as Differential Privacy and Homomorphic Encryption, are inadequate for
black-box API-only settings, demanding either model transparency or heavy
computational resources. We propose Prompt2Forget (P2F), the first framework
designed to tackle the LLM local privacy challenge by teaching LLM to forget.
The method involves decomposing full questions into smaller segments,
generating fabricated answers, and obfuscating the model's memory of the
original input. A benchmark dataset was crafted with questions containing
privacy-sensitive information from diverse fields. P2F achieves zero-shot
generalization, allowing adaptability across a wide range of use cases without
manual adjustments. Experimental results indicate P2F's robust capability to
obfuscate LLM's memory, attaining a forgetfulness score of around 90\% without
any utility loss. This represents an enhancement of up to 63\% when contrasted
with the naive direct instruction technique, highlighting P2F's efficacy in
mitigating memory retention of sensitive information within LLMs. Our findings
establish the first benchmark in the novel field of the LLM forgetting task,
representing a meaningful advancement in privacy preservation in the emerging
LLM domain.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.00058v1">Exploring the language of the sharing economy: Building trust and
  reducing privacy concern on Airbnb in German and English</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2023-12-29T19:28:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alex Zarifis, Richard Ingham, Julia Kroenung</p>
    <p><b>Summary:</b> The text in the profile of those offering their properties in England in
English and in Germany in German, are compared to explore whether trust is
built, and privacy concerns are reduced in the same way. Six methods of
building trust are used by the landlords: (1) the level of formality, (2)
distance and proximity, (3) emotiveness and humor, (4) being assertive and
passive aggressive, (5) conformity to the platform language style and
terminology and (6) setting boundaries. Privacy concerns are not usually
reduced directly as this is left to the platform. The findings indicate that
language has a limited influence and the platform norms and habits are the
biggest influence.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.17708v1">The six ways to build trust and reduce privacy concern in a Central Bank
  Digital Currency (CBDC)</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2023-12-29T17:52:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alex Zarifis, Xusen Cheng</p>
    <p><b>Summary:</b> Central Bank Digital Currencies (CBDCs) have been implemented by only a
handful of countries, but they are being explored by many more. CBDCs are
digital currencies issued and backed by a central bank. Consumer trust can
encourage or discourage the adoption of this currency, which is also a payment
system and a technology. This research attempts to understand consumer trust in
CBDCs so that the development and adoption stages are more effective and
satisfying for all the stakeholders.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.17667v1">AIJack: Security and Privacy Risk Simulator for Machine Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-29T16:10:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hideaki Takahashi</p>
    <p><b>Summary:</b> This paper introduces AIJack, an open-source library designed to assess
security and privacy risks associated with the training and deployment of
machine learning models. Amid the growing interest in big data and AI,
advancements in machine learning research and business are accelerating.
However, recent studies reveal potential threats, such as the theft of training
data and the manipulation of models by malicious attackers. Therefore, a
comprehensive understanding of machine learning's security and privacy
vulnerabilities is crucial for the safe integration of machine learning into
real-world products. AIJack aims to address this need by providing a library
with various attack and defense methods through a unified API. The library is
publicly available on GitHub (https://github.com/Koukyosyumei/AIJack).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.16954v1">Blockchain-based Privacy-Preserving Public Key Searchable Encryption
  with Strong Traceability</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-28T10:58:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yue Han, Jinguang Han, Weizhi Meng, Jianchang Lai, Ge Wu</p>
    <p><b>Summary:</b> Public key searchable encryption (PKSE) scheme allows data users to search
over encrypted data. To identify illegal users, many traceable PKSE schemes
have been proposed. However, existing schemes cannot trace the keywords which
illegal users searched and protect users' privacy simultaneously. In some
practical applications, tracing both illegal users' identities and the keywords
which they searched is quite important to against the abuse of data. It is a
challenge to bind users' identities and keywords while protecting their
privacy. Moreover, existing traceable PKSE schemes do not consider the
unforgeability and immutability of trapdoor query records, which can lead to
the occurrence of frame-up and denying. In this paper, to solve these problems,
we propose a blockchain-based privacy-preserving PKSE with strong traceability
(BP3KSEST) scheme. Our scheme provides the following features: (1) authorized
users can authenticate to trapdoor generation center and obtain trapdoors
without releasing their identities and keywords; (2) when data users misbehave
in the system, the trusted third party (TTP) can trace both their identities
and the keywords which they searched; (3) trapdoor query records are
unforgeable; (4) trapdoor query records are immutable because records are
stored in blockchain. Notably, this scheme is suitable to the scenarios where
privacy must be considered, e.g., electronic health record (EHR). We formalize
both the definition and security model of our BP3KSEST scheme, and present a
concrete construction. Furthermore, the security of the proposed scheme is
formally proven. Finally, the implementation and evaluation are conducted to
analyze its efficiency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.16554v1">A Theoretical Analysis of Efficiency Constrained Utility-Privacy
  Bi-Objective Optimization in Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2023-12-27T12:37:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hanlin Gu, Xinyuan Zhao, Yuxing Han, Yan Kang, Lixin Fan, Qiang Yang</p>
    <p><b>Summary:</b> Federated learning (FL) enables multiple clients to collaboratively learn a
shared model without sharing their individual data. Concerns about utility,
privacy, and training efficiency in FL have garnered significant research
attention. Differential privacy has emerged as a prevalent technique in FL,
safeguarding the privacy of individual user data while impacting utility and
training efficiency. Within Differential Privacy Federated Learning (DPFL),
previous studies have primarily focused on the utility-privacy trade-off,
neglecting training efficiency, which is crucial for timely completion.
Moreover, differential privacy achieves privacy by introducing controlled
randomness (noise) on selected clients in each communication round. Previous
work has mainly examined the impact of noise level ($\sigma$) and communication
rounds ($T$) on the privacy-utility dynamic, overlooking other influential
factors like the sample ratio ($q$, the proportion of selected clients). This
paper systematically formulates an efficiency-constrained utility-privacy
bi-objective optimization problem in DPFL, focusing on $\sigma$, $T$, and $q$.
We provide a comprehensive theoretical analysis, yielding analytical solutions
for the Pareto front. Extensive empirical experiments verify the validity and
efficacy of our analysis, offering valuable guidance for low-cost parameter
design in DPFL.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.15608v1">Federated learning-outcome prediction with multi-layer privacy
  protection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">  
  <p><b>Published on:</b> 2023-12-25T04:29:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yupei Zhang, Yuxin Li, Yifei Wang, Shuangshuang Wei, Yunan Xu, Xuequn Shang</p>
    <p><b>Summary:</b> Learning-outcome prediction (LOP) is a long-standing and critical problem in
educational routes. Many studies have contributed to developing effective
models while often suffering from data shortage and low generalization to
various institutions due to the privacy-protection issue. To this end, this
study proposes a distributed grade prediction model, dubbed FecMap, by
exploiting the federated learning (FL) framework that preserves the private
data of local clients and communicates with others through a global generalized
model. FecMap considers local subspace learning (LSL), which explicitly learns
the local features against the global features, and multi-layer privacy
protection (MPP), which hierarchically protects the private features, including
model-shareable features and not-allowably shared features, to achieve
client-specific classifiers of high performance on LOP per institution. FecMap
is then achieved in an iteration manner with all datasets distributed on
clients by training a local neural network composed of a global part, a local
part, and a classification head in clients and averaging the global parts from
clients on the server. To evaluate the FecMap model, we collected three
higher-educational datasets of student academic records from engineering
majors. Experiment results manifest that FecMap benefits from the proposed LSL
and MPP and achieves steady performance on the task of LOP, compared with the
state-of-the-art models. This study makes a fresh attempt at the use of
federated learning in the learning-analytical task, potentially paving the way
to facilitating personalized education with privacy protection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.15591v2">Privacy-Preserving Neural Graph Databases</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2023-12-25T02:32:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qi Hu, Haoran Li, Jiaxin Bai, Yangqiu Song</p>
    <p><b>Summary:</b> In the era of big data and rapidly evolving information systems, efficient
and accurate data retrieval has become increasingly crucial. Neural graph
databases (NGDBs) have emerged as a powerful paradigm that combines the
strengths of graph databases (graph DBs) and neural networks to enable
efficient storage, retrieval, and analysis of graph-structured data. The usage
of neural embedding storage and complex neural logical query answering provides
NGDBs with generalization ability. When the graph is incomplete, by extracting
latent patterns and representations, neural graph databases can fill gaps in
the graph structure, revealing hidden relationships and enabling accurate query
answering. Nevertheless, this capability comes with inherent trade-offs, as it
introduces additional privacy risks to the database. Malicious attackers can
infer more sensitive information in the database using well-designed
combinatorial queries, such as by comparing the answer sets of where Turing
Award winners born before 1950 and after 1940 lived, the living places of
Turing Award winner Hinton are probably exposed, although the living places may
have been deleted in the training due to the privacy concerns. In this work,
inspired by the privacy protection in graph embeddings, we propose a
privacy-preserving neural graph database (P-NGDB) to alleviate the risks of
privacy leakage in NGDBs. We introduce adversarial training techniques in the
training stage to force the NGDBs to generate indistinguishable answers when
queried with private information, enhancing the difficulty of inferring
sensitive information through combinations of multiple innocuous queries.
Extensive experiment results on three datasets show that P-NGDB can effectively
protect private information in the graph database while delivering high-quality
public answers responses to queries.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.15420v1">FedDMF: Privacy-Preserving User Attribute Prediction using Deep Matrix
  Factorization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-24T06:49:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ming Cheung</p>
    <p><b>Summary:</b> User attribute prediction is a crucial task in various industries. However,
sharing user data across different organizations faces challenges due to
privacy concerns and legal requirements regarding personally identifiable
information. Regulations such as the General Data Protection Regulation (GDPR)
in the European Union and the Personal Information Protection Law of the
People's Republic of China impose restrictions on data sharing. To address the
need for utilizing features from multiple clients while adhering to legal
requirements, federated learning algorithms have been proposed. These
algorithms aim to predict user attributes without directly sharing the data.
However, existing approaches typically rely on matching users across companies,
which can result in dishonest partners discovering user lists or the inability
to utilize all available features. In this paper, we propose a novel algorithm
for predicting user attributes without requiring user matching. Our approach
involves training deep matrix factorization models on different clients and
sharing only the item vectors. This allows us to predict user attributes
without sharing the user vectors themselves. The algorithm is evaluated using
the publicly available MovieLens dataset and demonstrate that it achieves
similar performance to the FedAvg algorithm, reaching 96% of a single model's
accuracy. The proposed algorithm is particularly well-suited for improving
customer targeting and enhancing the overall customer experience. This paper
presents a valuable contribution to the field of user attribute prediction by
offering a novel algorithm that addresses some of the most pressing privacy
concerns in this area.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.15383v1">SoK: Technical Implementation and Human Impact of Internet Privacy
  Regulations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2023-12-24T01:48:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Eleanor Birrell, Jay Rodolitz, Angel Ding, Jenna Lee, Emily McReynolds, Jevan Hutson, Ada Lerner</p>
    <p><b>Summary:</b> Growing recognition of the potential for exploitation of personal data and of
the shortcomings of prior privacy regimes has led to the passage of a multitude
of new online privacy regulations. Some of these laws -- notably the European
Union's General Data Protection Regulation (GDPR) and the California Consumer
Privacy Act (CCPA) -- have been the focus of large bodies of research by the
computer science community, while others have received less attention. In this
work, we analyze a set of Internet privacy and data protection regulations
drawn from around the world -- both those that have frequently been studied by
computer scientists and those that have not -- and develop a taxonomy of rights
granted and obligations imposed by these laws. We then leverage this taxonomy
to systematize 270 technical research papers published in computer science
venues that investigate the impact of these laws and explore how technical
solutions can complement legal protections. Finally, we analyze the results in
this space through an interdisciplinary lens and make recommendations for
future work at the intersection of computer science and legal privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.15375v1">An Empirical Study of Efficiency and Privacy of Federated Learning
  Algorithms</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2023-12-24T00:13:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sofia Zahri, Hajar Bennouri, Ahmed M. Abdelmoniem</p>
    <p><b>Summary:</b> In today's world, the rapid expansion of IoT networks and the proliferation
of smart devices in our daily lives, have resulted in the generation of
substantial amounts of heterogeneous data. These data forms a stream which
requires special handling. To handle this data effectively, advanced data
processing technologies are necessary to guarantee the preservation of both
privacy and efficiency. Federated learning emerged as a distributed learning
method that trains models locally and aggregates them on a server to preserve
data privacy. This paper showcases two illustrative scenarios that highlight
the potential of federated learning (FL) as a key to delivering efficient and
privacy-preserving machine learning within IoT networks. We first give the
mathematical foundations for key aggregation algorithms in federated learning,
i.e., FedAvg and FedProx. Then, we conduct simulations, using Flower Framework,
to show the \textit{efficiency} of these algorithms by training deep neural
networks on common datasets and show a comparison between the accuracy and loss
metrics of FedAvg and FedProx. Then, we present the results highlighting the
trade-off between maintaining privacy versus accuracy via simulations -
involving the implementation of the differential privacy (DP) method - in
Pytorch and Opacus ML frameworks on common FL datasets and data distributions
for both FedAvg and FedProx strategies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.15000v1">The Impact of Cloaking Digital Footprints on User Privacy and
  Personalization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2023-12-22T16:32:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sofie Goethals, Sandra Matz, Foster Provost, Yanou Ramon, David Martens</p>
    <p><b>Summary:</b> Our online lives generate a wealth of behavioral records -'digital
footprints'- which are stored and leveraged by technology platforms. This data
can be used to create value for users by personalizing services. At the same
time, however, it also poses a threat to people's privacy by offering a highly
intimate window into their private traits (e.g., their personality, political
ideology, sexual orientation). Prior work has proposed a potential remedy: The
cloaking of users' footprints. That is, platforms could allow users to hide
portions of their digital footprints from predictive algorithms to avoid
undesired inferences. While such an approach has been shown to offer privacy
protection in the moment, there are two open questions. First, it remains
unclear how well cloaking performs over time. As people constantly leave new
digital footprints, the algorithm might regain the ability to predict
previously cloaked traits. Second, cloaking digital footprints to avoid one
undesirable inference may degrade the performance of models for other,
desirable inferences (e.g., those driving desired personalized content). In the
light of these research gaps, our contributions are twofold: 1) We propose a
novel cloaking strategy that conceals 'metafeatures' (automatically generated
higher-level categories) and compares its effectiveness against existing
cloaking approaches, and 2) we test the spill-over effects of cloaking one
trait on the accuracy of inferences on other traits. A key finding is that the
effectiveness of cloaking degrades over times, but the rate at which it
degrades is significantly smaller when cloaking metafeatures rather than
individual footprints. In addition, our findings reveal the expected trade-off
between privacy and personalization: Cloaking an undesired trait also partially
conceals other desirable traits.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.14633v1">Evaluating the Security and Privacy Risk Postures of Virtual Assistants</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2023-12-22T12:10:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Borna Kalhor, Sanchari Das</p>
    <p><b>Summary:</b> Virtual assistants (VAs) have seen increased use in recent years due to their
ease of use for daily tasks. Despite their growing prevalence, their security
and privacy implications are still not well understood. To address this gap, we
conducted a study to evaluate the security and privacy postures of eight widely
used voice assistants: Alexa, Braina, Cortana, Google Assistant, Kalliope,
Mycroft, Hound, and Extreme. We used three vulnerability testing tools,
AndroBugs, RiskInDroid, and MobSF, to assess the security and privacy of these
VAs. Our analysis focused on five areas: code, access control, tracking, binary
analysis, and sensitive data confidentiality. The results revealed that these
VAs are vulnerable to a range of security threats, including not validating SSL
certificates, executing raw SQL queries, and using a weak mode of the AES
algorithm. These vulnerabilities could allow malicious actors to gain
unauthorized access to users' personal information. This study is a first step
toward understanding the risks associated with these technologies and provides
a foundation for future research to develop more secure and privacy-respecting
VAs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.14521v1">Tuning Quantum Computing Privacy through Quantum Error Correction</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2023-12-22T08:35:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hui Zhong, Keyi Ju, Manojna Sistla, Xinyue Zhang, Xiaoqi Qin, Xin Fu, Miao Pan</p>
    <p><b>Summary:</b> Quantum computing is a promising paradigm for efficiently solving large and
high-complexity problems. To protect quantum computing privacy, pioneering
research efforts proposed to redefine differential privacy (DP) in quantum
computing, i.e., quantum differential privacy (QDP), and harvest inherent
noises generated by quantum computing to implement QDP. However, such an
implementation approach is limited by the amount of inherent noises, which
makes the privacy budget of the QDP mechanism fixed and uncontrollable. To
address this issue, in this paper, we propose to leverage quantum error
correction (QEC) techniques to reduce quantum computing errors, while tuning
the privacy protection levels in QDP. In short, we gradually decrease the
quantum noise error rate by deciding whether to apply QEC operations on the
gate in a multiple single qubit gates circuit. We have derived a new
calculation formula for the general error rate and corresponding privacy
budgets after QEC operation. Then, we expand to achieve further noise reduction
using multi-level concatenated QEC operation. Through extensive numerical
simulations, we demonstrate that QEC is a feasible way to regulate the degree
of privacy protection in quantum computing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.16191v1">SoK: Taming the Triangle -- On the Interplays between Fairness,
  Interpretability and Privacy in Machine Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2023-12-22T08:11:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Julien Ferry, Ulrich Aïvodji, Sébastien Gambs, Marie-José Huguet, Mohamed Siala</p>
    <p><b>Summary:</b> Machine learning techniques are increasingly used for high-stakes
decision-making, such as college admissions, loan attribution or recidivism
prediction. Thus, it is crucial to ensure that the models learnt can be audited
or understood by human users, do not create or reproduce discrimination or
bias, and do not leak sensitive information regarding their training data.
Indeed, interpretability, fairness and privacy are key requirements for the
development of responsible machine learning, and all three have been studied
extensively during the last decade. However, they were mainly considered in
isolation, while in practice they interplay with each other, either positively
or negatively. In this Systematization of Knowledge (SoK) paper, we survey the
literature on the interactions between these three desiderata. More precisely,
for each pairwise interaction, we summarize the identified synergies and
tensions. These findings highlight several fundamental theoretical and
empirical conflicts, while also demonstrating that jointly considering these
different requirements is challenging when one aims at preserving a high level
of utility. To solve this issue, we also discuss possible conciliation
mechanisms, showing that a careful design can enable to successfully handle
these different concerns in practice.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.14407v1">AdvCloak: Customized Adversarial Cloak for Privacy Protection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2023-12-22T03:18:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xuannan Liu, Yaoyao Zhong, Xing Cui, Yuhang Zhang, Peipei Li, Weihong Deng</p>
    <p><b>Summary:</b> With extensive face images being shared on social media, there has been a
notable escalation in privacy concerns. In this paper, we propose AdvCloak, an
innovative framework for privacy protection using generative models. AdvCloak
is designed to automatically customize class-wise adversarial masks that can
maintain superior image-level naturalness while providing enhanced
feature-level generalization ability. Specifically, AdvCloak sequentially
optimizes the generative adversarial networks by employing a two-stage training
strategy. This strategy initially focuses on adapting the masks to the unique
individual faces via image-specific training and then enhances their
feature-level generalization ability to diverse facial variations of
individuals via person-specific training. To fully utilize the limited training
data, we combine AdvCloak with several general geometric modeling methods, to
better describe the feature subspace of source identities. Extensive
quantitative and qualitative evaluations on both common and celebrity datasets
demonstrate that AdvCloak outperforms existing state-of-the-art methods in
terms of efficiency and effectiveness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.14388v1">A Generalized Shuffle Framework for Privacy Amplification: Strengthening
  Privacy Guarantees and Enhancing Utility</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2023-12-22T02:31:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> E Chen, Yang Cao, Yifei Ge</p>
    <p><b>Summary:</b> The shuffle model of local differential privacy is an advanced method of
privacy amplification designed to enhance privacy protection with high utility.
It achieves this by randomly shuffling sensitive data, making linking
individual data points to specific individuals more challenging. However, most
existing studies have focused on the shuffle model based on
$(\epsilon_0,0)$-Locally Differentially Private (LDP) randomizers, with limited
consideration for complex scenarios such as $(\epsilon_0,\delta_0)$-LDP or
personalized LDP (PLDP). This hinders a comprehensive understanding of the
shuffle model's potential and limits its application in various settings. To
bridge this research gap, we propose a generalized shuffle framework that can
be applied to any $(\epsilon_i,\delta_i)$-PLDP setting with personalized
privacy parameters. This generalization allows for a broader exploration of the
privacy-utility trade-off and facilitates the design of privacy-preserving
analyses in diverse contexts. We prove that shuffled
$(\epsilon_i,\delta_i)$-PLDP process approximately preserves $\mu$-Gaussian
Differential Privacy with \mu = \sqrt{\frac{2}{\sum_{i=1}^{n}
\frac{1-\delta_i}{1+e^{\epsilon_i}}-\max_{i}{\frac{1-\delta_{i}}{1+e^{\epsilon_{i}}}}}}.
$
  This approach allows us to avoid the limitations and potential inaccuracies
associated with inequality estimations. To strengthen the privacy guarantee, we
improve the lower bound by utilizing hypothesis testing} instead of relying on
rough estimations like the Chernoff bound or Hoeffding's inequality.
Furthermore, extensive comparative evaluations clearly show that our approach
outperforms existing methods in achieving strong central privacy guarantees
while preserving the utility of the global model. We have also carefully
designed corresponding algorithms for average function, frequency estimation,
and stochastic gradient descent.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.13985v1">Rényi Pufferfish Privacy: General Additive Noise Mechanisms and
  Privacy Amplification by Iteration</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2023-12-21T16:18:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Clément Pierquin, Aurélien Bellet, Marc Tommasi, Matthieu Boussard</p>
    <p><b>Summary:</b> Pufferfish privacy is a flexible generalization of differential privacy that
allows to model arbitrary secrets and adversary's prior knowledge about the
data. Unfortunately, designing general and tractable Pufferfish mechanisms that
do not compromise utility is challenging. Furthermore, this framework does not
provide the composition guarantees needed for a direct use in iterative machine
learning algorithms. To mitigate these issues, we introduce a R\'enyi
divergence-based variant of Pufferfish and show that it allows us to extend the
applicability of the Pufferfish framework. We first generalize the Wasserstein
mechanism to cover a wide range of noise distributions and introduce several
ways to improve its utility. We also derive stronger guarantees against
out-of-distribution adversaries. Finally, as an alternative to composition, we
prove privacy amplification results for contractive noisy iterations and
showcase the first use of Pufferfish in private convex optimization. A common
ingredient underlying our results is the use and extension of shift reduction
lemmas.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.13813v1">How Does Connecting Online Activities to Advertising Inferences Impact
  Privacy Perceptions?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2023-12-21T13:05:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Florian M. Farke, David G. Balash, Maximilian Golla, Adam J. Aviv</p>
    <p><b>Summary:</b> Data dashboards are designed to help users manage data collected about them.
However, prior work showed that exposure to some dashboards, notably Google's
My Activity dashboard, results in significant decreases in perceived concern
and increases in perceived benefit from data collection, contrary to
expectations. We theorize that this result is due to the fact that data
dashboards currently do not sufficiently "connect the dots" of the data food
chain, that is, by connecting data collection with the use of that data. To
evaluate this, we designed a study where participants assigned advertising
interest labels to their own real activities, effectively acting as a
behavioral advertising engine to "connect the dots." When comparing pre- and
post-labeling task responses, we find no significant difference in concern with
Google's data collection practices, which indicates that participants' priors
are maintained after more exposure to the data food chain (differing from prior
work), suggesting that data dashboards that offer deeper perspectives of how
data collection is used have potential. However, these gains are offset when
participants are exposed to their true interest labels inferred by Google.
Concern for data collection dropped significantly as participants viewed
Google's labeling as generic compared to their own more specific labeling. This
presents a possible new paradox that must be overcome when designing data
dashboards, the generic paradox, which occurs when users misalign individual,
generic inferences from collected data as benign compared to the totality and
specificity of many generic inferences made about them.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.13712v1">Conciliating Privacy and Utility in Data Releases via Individual
  Differential Privacy and Microaggregation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-21T10:23:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jordi Soria-Comas, David Sánchez, Josep Domingo-Ferrer, Sergio Martínez, Luis Del Vasto-Terrientes</p>
    <p><b>Summary:</b> $\epsilon$-Differential privacy (DP) is a well-known privacy model that
offers strong privacy guarantees. However, when applied to data releases, DP
significantly deteriorates the analytical utility of the protected outcomes. To
keep data utility at reasonable levels, practical applications of DP to data
releases have used weak privacy parameters (large $\epsilon$), which dilute the
privacy guarantees of DP. In this work, we tackle this issue by using an
alternative formulation of the DP privacy guarantees, named
$\epsilon$-individual differential privacy (iDP), which causes less data
distortion while providing the same protection as DP to subjects. We enforce
iDP in data releases by relying on attribute masking plus a pre-processing step
based on data microaggregation. The goal of this step is to reduce the
sensitivity to record changes, which determines the amount of noise required to
enforce iDP (and DP). Specifically, we propose data microaggregation strategies
designed for iDP whose sensitivities are significantly lower than those used in
DP. As a result, we obtain iDP-protected data with significantly better utility
than with DP. We report on experiments that show how our approach can provide
strong privacy (small $\epsilon$) while yielding protected data that do not
significantly degrade the accuracy of secondary data analysis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.13389v1">Enhancing Trade-offs in Privacy, Utility, and Computational Efficiency
  through MUltistage Sampling Technique (MUST)</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2023-12-20T19:38:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xingyuan Zhao, Fang Liu</p>
    <p><b>Summary:</b> Applying a randomized algorithm to a subset of a dataset rather than the
entire dataset is a common approach to amplify its privacy guarantees in the
released information. We propose a class of subsampling methods named
MUltistage Sampling Technique (MUST) for privacy amplification (PA) in the
context of differential privacy (DP). We conduct comprehensive analyses of the
PA effects and utility for several 2-stage MUST procedures, namely, MUST.WO,
MUST.OW, and MUST.WW that respectively represent sampling with (W), without
(O), with (W) replacement from the original dataset in stage I and then
sampling without (O), with (W), with (W) replacement in stage II from the
subset drawn in stage I. We also provide the privacy composition analysis over
repeated applications of MUST via the Fourier accountant algorithm. Our
theoretical and empirical results suggest that MUST.OW and MUST.WW have
stronger PA in $\epsilon$ than the common one-stage sampling procedures
including Poisson sampling, sampling without replacement, and sampling with
replacement, while the results on $\delta$ vary case by case. We also prove
that MUST.WO is equivalent to sampling with replacement in PA. Furthermore, the
final subset generated by a MUST procedure is a multiset that may contain
multiple copies of the same data points due to sampling with replacement
involved, which enhances the computational efficiency of algorithms that
require complex function calculations on distinct data points (e.g., gradient
descent). Our utility experiments show that MUST delivers similar or improved
utility and stability in the privacy-preserving outputs compared to one-stage
subsampling methods at similar privacy loss. MUST can be seamlessly integrated
into stochastic optimization algorithms or procedures that involve parallel or
simultaneous subsampling (e.g., bagging and subsampling bootstrap) when DP
guarantees are necessary.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.13334v1">Transparency and Privacy: The Role of Explainable AI and Federated
  Learning in Financial Fraud Detection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-20T18:26:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tomisin Awosika, Raj Mani Shukla, Bernardi Pranggono</p>
    <p><b>Summary:</b> Fraudulent transactions and how to detect them remain a significant problem
for financial institutions around the world. The need for advanced fraud
detection systems to safeguard assets and maintain customer trust is paramount
for financial institutions, but some factors make the development of effective
and efficient fraud detection systems a challenge. One of such factors is the
fact that fraudulent transactions are rare and that many transaction datasets
are imbalanced; that is, there are fewer significant samples of fraudulent
transactions than legitimate ones. This data imbalance can affect the
performance or reliability of the fraud detection model. Moreover, due to the
data privacy laws that all financial institutions are subject to follow,
sharing customer data to facilitate a higher-performing centralized model is
impossible. Furthermore, the fraud detection technique should be transparent so
that it does not affect the user experience. Hence, this research introduces a
novel approach using Federated Learning (FL) and Explainable AI (XAI) to
address these challenges. FL enables financial institutions to collaboratively
train a model to detect fraudulent transactions without directly sharing
customer data, thereby preserving data privacy and confidentiality. Meanwhile,
the integration of XAI ensures that the predictions made by the model can be
understood and interpreted by human experts, adding a layer of transparency and
trust to the system. Experimental results, based on realistic transaction
datasets, reveal that the FL-based fraud detection system consistently
demonstrates high performance metrics. This study grounds FL's potential as an
effective and privacy-preserving tool in the fight against fraud.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.13312v1">Multi-label Learning from Privacy-Label</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-20T09:09:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhongnian Li, Haotian Ren, Tongfeng Sun, Zhichen Li</p>
    <p><b>Summary:</b> Multi-abel Learning (MLL) often involves the assignment of multiple relevant
labels to each instance, which can lead to the leakage of sensitive information
(such as smoking, diseases, etc.) about the instances. However, existing MLL
suffer from failures in protection for sensitive information. In this paper, we
propose a novel setting named Multi-Label Learning from Privacy-Label (MLLPL),
which Concealing Labels via Privacy-Label Unit (CLPLU). Specifically, during
the labeling phase, each privacy-label is randomly combined with a non-privacy
label to form a Privacy-Label Unit (PLU). If any label within a PLU is
positive, the unit is labeled as positive; otherwise, it is labeled negative,
as shown in Figure 1. PLU ensures that only non-privacy labels are appear in
the label set, while the privacy-labels remain concealed. Moreover, we further
propose a Privacy-Label Unit Loss (PLUL) to learn the optimal classifier by
minimizing the empirical risk of PLU. Experimental results on multiple
benchmark datasets demonstrate the effectiveness and superiority of the
proposed method.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.12216v1">Sharing is CAIRing: Characterizing Principles and Assessing Properties
  of Universal Privacy Evaluation for Synthetic Tabular Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2023-12-19T15:05:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tobias Hyrup, Anton Danholt Lautrup, Arthur Zimek, Peter Schneider-Kamp</p>
    <p><b>Summary:</b> Data sharing is a necessity for innovative progress in many domains,
especially in healthcare. However, the ability to share data is hindered by
regulations protecting the privacy of natural persons. Synthetic tabular data
provide a promising solution to address data sharing difficulties but does not
inherently guarantee privacy. Still, there is a lack of agreement on
appropriate methods for assessing the privacy-preserving capabilities of
synthetic data, making it difficult to compare results across studies. To the
best of our knowledge, this is the first work to identify properties that
constitute good universal privacy evaluation metrics for synthetic tabular
data. The goal of such metrics is to enable comparability across studies and to
allow non-technical stakeholders to understand how privacy is protected. We
identify four principles for the assessment of metrics: Comparability,
Applicability, Interpretability, and Representativeness (CAIR). To quantify and
rank the degree to which evaluation metrics conform to the CAIR principles, we
design a rubric using a scale of 1-4. Each of the four properties is scored on
four parameters, yielding 16 total dimensions. We study the applicability and
usefulness of the CAIR principles and rubric by assessing a selection of
metrics popular in other studies. The results provide granular insights into
the strengths and weaknesses of existing metrics that not only rank the metrics
but highlight areas of potential improvements. We expect that the CAIR
principles will foster agreement among researchers and organizations on which
universal privacy evaluation metrics are appropriate for synthetic tabular
data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.12183v2">Poincaré Differential Privacy for Hierarchy-Aware Graph Embedding</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-19T14:15:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuecen Wei, Haonan Yuan, Xingcheng Fu, Qingyun Sun, Hao Peng, Xianxian Li, Chunming Hu</p>
    <p><b>Summary:</b> Hierarchy is an important and commonly observed topological property in
real-world graphs that indicate the relationships between supervisors and
subordinates or the organizational behavior of human groups. As hierarchy is
introduced as a new inductive bias into the Graph Neural Networks (GNNs) in
various tasks, it implies latent topological relations for attackers to improve
their inference attack performance, leading to serious privacy leakage issues.
In addition, existing privacy-preserving frameworks suffer from reduced
protection ability in hierarchical propagation due to the deficiency of
adaptive upper-bound estimation of the hierarchical perturbation boundary. It
is of great urgency to effectively leverage the hierarchical property of data
while satisfying privacy guarantees. To solve the problem, we propose the
Poincar\'e Differential Privacy framework, named PoinDP, to protect the
hierarchy-aware graph embedding based on hyperbolic geometry. Specifically,
PoinDP first learns the hierarchy weights for each entity based on the
Poincar\'e model in hyperbolic space. Then, the Personalized Hierarchy-aware
Sensitivity is designed to measure the sensitivity of the hierarchical
structure and adaptively allocate the privacy protection strength. Besides, the
Hyperbolic Gaussian Mechanism (HGM) is proposed to extend the Gaussian
mechanism in Euclidean space to hyperbolic space to realize random
perturbations that satisfy differential privacy under the hyperbolic space
metric. Extensive experiment results on five real-world datasets demonstrate
the proposed PoinDP's advantages of effective privacy protection while
maintaining good performance on the node classification task.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.11845v1">A Summary of Privacy-Preserving Data Publishing in the Local Setting</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-19T04:23:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenjun Lin, Jiahao Qian, Wenwen Liu, Lang Wu</p>
    <p><b>Summary:</b> The exponential growth of collected, processed, and shared data has given
rise to concerns about individuals' privacy. Consequently, various laws and
regulations have been established to oversee how organizations handle and
safeguard data. One such method is Statistical Disclosure Control, which aims
to minimize the risk of exposing confidential information by de-identifying it.
This de-identification is achieved through specific privacy-preserving
techniques. However, a trade-off exists: de-identified data can often lead to a
loss of information, which might impact the accuracy of data analysis and the
predictive capability of models. The overarching goal remains to safeguard
individual privacy while preserving the data's interpretability, meaning its
overall usefulness. Despite advances in Statistical Disclosure Control, the
field continues to evolve, with no definitive solution that strikes an optimal
balance between privacy and utility. This survey delves into the intricate
processes of de-identification. We outline the current privacy-preserving
techniques employed in microdata de-identification, delve into privacy measures
tailored for various disclosure scenarios, and assess metrics for information
loss and predictive performance. Herein, we tackle the primary challenges posed
by privacy constraints, overview predominant strategies to mitigate these
challenges, categorize privacy-preserving techniques, offer a theoretical
assessment of current comparative research, and highlight numerous unresolved
issues in the domain.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.11712v1">A Simple and Practical Method for Reducing the Disparate Impact of
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2023-12-18T21:19:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lucas Rosenblatt, Julia Stoyanovich, Christopher Musco</p>
    <p><b>Summary:</b> Differentially private (DP) mechanisms have been deployed in a variety of
high-impact social settings (perhaps most notably by the U.S. Census). Since
all DP mechanisms involve adding noise to results of statistical queries, they
are expected to impact our ability to accurately analyze and learn from data,
in effect trading off privacy with utility. Alarmingly, the impact of DP on
utility can vary significantly among different sub-populations. A simple way to
reduce this disparity is with stratification. First compute an independent
private estimate for each group in the data set (which may be the intersection
of several protected classes), then, to compute estimates of global statistics,
appropriately recombine these group estimates. Our main observation is that
naive stratification often yields high-accuracy estimates of population-level
statistics, without the need for additional privacy budget. We support this
observation theoretically and empirically. Our theoretical results center on
the private mean estimation problem, while our empirical results center on
extensive experiments on private data synthesis to demonstrate the
effectiveness of stratification on a variety of private mechanisms. Overall, we
argue that this straightforward approach provides a strong baseline against
which future work on reducing utility disparities of DP mechanisms should be
compared.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.11126v1">Harnessing Inherent Noises for Privacy Preservation in Quantum Machine
  Learning</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2023-12-18T11:52:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Keyi Ju, Xiaoqi Qin, Hui Zhong, Xinyue Zhang, Miao Pan, Baoling Liu</p>
    <p><b>Summary:</b> Quantum computing revolutionizes the way of solving complex problems and
handling vast datasets, which shows great potential to accelerate the machine
learning process. However, data leakage in quantum machine learning (QML) may
present privacy risks. Although differential privacy (DP), which protects
privacy through the injection of artificial noise, is a well-established
approach, its application in the QML domain remains under-explored. In this
paper, we propose to harness inherent quantum noises to protect data privacy in
QML. Especially, considering the Noisy Intermediate-Scale Quantum (NISQ)
devices, we leverage the unavoidable shot noise and incoherent noise in quantum
computing to preserve the privacy of QML models for binary classification. We
mathematically analyze that the gradient of quantum circuit parameters in QML
satisfies a Gaussian distribution, and derive the upper and lower bounds on its
variance, which can potentially provide the DP guarantee. Through simulations,
we show that a target privacy protection level can be achieved by running the
quantum circuit a different number of times.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.11581v1">Protect Your Score: Contact Tracing With Differential Privacy Guarantees</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2023-12-18T11:16:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rob Romijnders, Christos Louizos, Yuki M. Asano, Max Welling</p>
    <p><b>Summary:</b> The pandemic in 2020 and 2021 had enormous economic and societal
consequences, and studies show that contact tracing algorithms can be key in
the early containment of the virus. While large strides have been made towards
more effective contact tracing algorithms, we argue that privacy concerns
currently hold deployment back. The essence of a contact tracing algorithm
constitutes the communication of a risk score. Yet, it is precisely the
communication and release of this score to a user that an adversary can
leverage to gauge the private health status of an individual. We pinpoint a
realistic attack scenario and propose a contact tracing algorithm with
differential privacy guarantees against this attack. The algorithm is tested on
the two most widely used agent-based COVID19 simulators and demonstrates
superior performance in a wide range of settings. Especially for realistic test
scenarios and while releasing each risk score with epsilon=1 differential
privacy, we achieve a two to ten-fold reduction in the infection rate of the
virus. To the best of our knowledge, this presents the first contact tracing
algorithm with differential privacy guarantees when revealing risk scores for
COVID19.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.11575v1">Blind-Touch: Homomorphic Encryption-Based Distributed Neural Network
  Inference for Privacy-Preserving Fingerprint Authentication</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-18T09:05:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hyunmin Choi, Simon Woo, Hyoungshick Kim</p>
    <p><b>Summary:</b> Fingerprint authentication is a popular security mechanism for smartphones
and laptops. However, its adoption in web and cloud environments has been
limited due to privacy concerns over storing and processing biometric data on
servers. This paper introduces Blind-Touch, a novel machine learning-based
fingerprint authentication system leveraging homomorphic encryption to address
these privacy concerns. Homomorphic encryption allows computations on encrypted
data without decrypting. Thus, Blind-Touch can keep fingerprint data encrypted
on the server while performing machine learning operations. Blind-Touch
combines three strategies to efficiently utilize homomorphic encryption in
machine learning: (1) It optimizes the feature vector for a distributed
architecture, processing the first fully connected layer (FC-16) in plaintext
on the client side and the subsequent layer (FC-1) post-encryption on the
server, thereby minimizing encrypted computations; (2) It employs a homomorphic
encryptioncompatible data compression technique capable of handling 8,192
authentication results concurrently; and (3) It utilizes a clustered server
architecture to simultaneously process authentication results, thereby
enhancing scalability with increasing user numbers. Blind-Touch achieves high
accuracy on two benchmark fingerprint datasets, with a 93.6% F1- score for the
PolyU dataset and a 98.2% F1-score for the SOKOTO dataset. Moreover,
Blind-Touch can match a fingerprint among 5,000 in about 0.65 seconds. With its
privacyfocused design, high accuracy, and efficiency, Blind-Touch is a
promising alternative to conventional fingerprint authentication for web and
cloud applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.10951v1">Viral Privacy: Contextual Integrity as a Lens to Understand Content
  Creators' Privacy Perceptions and Needs After Sudden Attention</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2023-12-18T06:04:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joseph S. Schafer, Annie Denton, Chloe Seelhoff, Jordyn Vo, Kate Starbird</p>
    <p><b>Summary:</b> When designing multi-stakeholder privacy systems, it is important to consider
how different groups of social media users have different goals and
requirements for privacy. Additionally, we must acknowledge that it is
important to keep in mind that even a single creator's needs can change as
their online visibility and presence shifts, and that robust multi-stakeholder
privacy systems should account for these shifts. Using the framework of
contextual integrity, we explain a theoretical basis for how to evaluate the
potential changing privacy needs of users as their profiles undergo a sudden
rise in online attention, and ongoing projects to understand these potential
shifts in perspectives.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.11564v1">Privacy-preserving transactive energy systems: Key topics and open
  research challenges</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2023-12-17T21:23:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Daniel Gerbi Duguma, Juliana Zhang, Meysam Aboutalebi, Shiliang Zhang, Catherine Banet, Cato Bjørkli, Chinmayi Baramashetru, Frank Eliassen, Hui Zhang, Jonathan Muringani, Josef Noll, Knut Inge Fostervold, Lars Böcker, Lee Andrew Bygrave, Matin Bagherpour, Maunya Doroudi Moghadam, Olaf Owe, Poushali Sengupta, Roman Vitenberg, Sabita Maharjan, Thiago Garrett, Yushuai Li, Zhengyu Shan</p>
    <p><b>Summary:</b> This manuscript aims to formalize and conclude the discussions initiated
during the PriTEM workshop 22-23 March 2023. We present important ideas and
discussion topics in the context of transactive energy systems. Moreover, the
conclusions from the discussions articulate potential aspects to be explored in
future studies on transactive energy management. Particularly, these
conclusions cover research topics in energy technology and energy informatics,
energy law, data law, energy market and socio-psychology that are relevant to
the seamless integration of renewable energy resources and the transactive
energy systems-in smart microgrids-focusing on distributed frameworks such as
peer-to-peer (P2P) energy trading. We clarify issues, identify barriers, and
suggest possible solutions to open questions in diversified topics, such as
block-chain interoperability, consumer privacy and data sharing, and
participation incentivization. Furthermore, we also elaborate challenges
associated with cross-disciplinary collaboration and coordination for
transactive energy systems, and enumerate the lessons learned from our work so
far.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.10789v1">Federated learning with differential privacy and an untrusted aggregator</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-17T18:26:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kunlong Liu, Trinabh Gupta</p>
    <p><b>Summary:</b> Federated learning for training models over mobile devices is gaining
popularity. Current systems for this task exhibit significant trade-offs
between model accuracy, privacy guarantee, and device efficiency. For instance,
Oort (OSDI 2021) provides excellent accuracy and efficiency but requires a
trusted central server. On the other hand, Orchard (OSDI 2020) provides good
accuracy and the rigorous guarantee of differential privacy over an untrusted
server, but creates huge overhead for the devices. This paper describes Aero, a
new federated learning system that significantly improves this trade-off. Aero
guarantees good accuracy, differential privacy over an untrusted server, and
keeps the device overhead low. The key idea of Aero is to tune system
architecture and design to a specific set of popular, federated learning
algorithms. This tuning requires novel optimizations and techniques, e.g., a
new protocol to securely aggregate updates from devices. An evaluation of Aero
demonstrates that it provides comparable accuracy to plain federated learning
(without differential privacy), and it improves efficiency (CPU and network)
over Orchard by up to $10^5\times$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.10698v1">HE-DKSAP: Privacy-Preserving Stealth Address Protocol via Additively
  Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-17T12:23:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuping Yan, George Shao, Dennis Song, Mason Song, Yaochu Jin</p>
    <p><b>Summary:</b> Blockchain transactions have gained widespread adoption across various
industries, largely attributable to their unparalleled transparency and robust
security features. Nevertheless, this technique introduces various privacy
concerns, including pseudonymity, Sybil attacks, and potential susceptibilities
to quantum computing, to name a few. In response to these challenges,
innovative privacy-enhancing solutions like zero-knowledge proofs, homomorphic
encryption, and stealth addresses (SA) have been developed. Among the various
schemes, SA stands out as it prevents the association of a blockchain
transaction's output with the recipient's public address, thereby ensuring
transactional anonymity. However, the basic SA schemes have exhibited
vulnerabilities to key leakage and quantum computing attacks. To address these
shortcomings, we present a pioneering solution - Homomorphic Encryption-based
Dual-Key Stealth Address Protocol (HE-DKSAP), which can be further extended to
Fully HE-DKSAP (FHE-DKSAP). By leveraging the power of homomorphic encryption,
HE-DKSAP introduces a novel approach to safeguarding transaction privacy and
preventing potential quantum computing attacks. This paper delves into the core
principles of HE-DKSAP, highlighting its capacity to enhance privacy,
scalability, and security in programmable blockchains. Through a comprehensive
exploration of its design architecture, security analysis, and practical
implementations, this work establishes a privacy-preserving, practical, and
efficient stealth address protocol via additively homomorphic encryption.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.10645v1">FedMKGC: Privacy-Preserving Federated Multilingual Knowledge Graph
  Completion</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2023-12-17T08:09:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wei Tang, Zhiqian Wu, Yixin Cao, Yong Liao, Pengyuan Zhou</p>
    <p><b>Summary:</b> Knowledge graph completion (KGC) aims to predict missing facts in knowledge
graphs (KGs), which is crucial as modern KGs remain largely incomplete. While
training KGC models on multiple aligned KGs can improve performance, previous
methods that rely on transferring raw data among KGs raise privacy concerns. To
address this challenge, we propose a new federated learning framework that
implicitly aggregates knowledge from multiple KGs without demanding raw data
exchange and entity alignment. We treat each KG as a client that trains a local
language model through textbased knowledge representation learning. A central
server then aggregates the model weights from clients. As natural language
provides a universal representation, the same knowledge thus has similar
semantic representations across KGs. As such, the aggregated language model can
leverage complementary knowledge from multilingual KGs without demanding raw
user data sharing. Extensive experiments on a benchmark dataset demonstrate
that our method substantially improves KGC on multilingual KGs, achieving
comparable performance to state-of-the-art alignment-based models without
requiring any labeled alignments or raw user data sharing. Our codes will be
publicly available.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.10380v1">PPIDSG: A Privacy-Preserving Image Distribution Sharing Scheme with GAN
  in Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2023-12-16T08:32:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuting Ma, Yuanzhi Yao, Xiaohua Xu</p>
    <p><b>Summary:</b> Federated learning (FL) has attracted growing attention since it allows for
privacy-preserving collaborative training on decentralized clients without
explicitly uploading sensitive data to the central server. However, recent
works have revealed that it still has the risk of exposing private data to
adversaries. In this paper, we conduct reconstruction attacks and enhance
inference attacks on various datasets to better understand that sharing trained
classification model parameters to a central server is the main problem of
privacy leakage in FL. To tackle this problem, a privacy-preserving image
distribution sharing scheme with GAN (PPIDSG) is proposed, which consists of a
block scrambling-based encryption algorithm, an image distribution sharing
method, and local classification training. Specifically, our method can capture
the distribution of a target image domain which is transformed by the block
encryption algorithm, and upload generator parameters to avoid classifier
sharing with negligible influence on model performance. Furthermore, we apply a
feature extractor to motivate model utility and train it separately from the
classifier. The extensive experimental results and security analyses
demonstrate the superiority of our proposed scheme compared to other
state-of-the-art defense methods. The code is available at
https://github.com/ytingma/PPIDSG.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.10108v1">Privacy-Aware Document Visual Question Answering</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2023-12-15T06:30:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rubèn Tito, Khanh Nguyen, Marlon Tobaben, Raouf Kerkouche, Mohamed Ali Souibgui, Kangsoo Jung, Lei Kang, Ernest Valveny, Antti Honkela, Mario Fritz, Dimosthenis Karatzas</p>
    <p><b>Summary:</b> Document Visual Question Answering (DocVQA) is a fast growing branch of
document understanding. Despite the fact that documents contain sensitive or
copyrighted information, none of the current DocVQA methods offers strong
privacy guarantees.
  In this work, we explore privacy in the domain of DocVQA for the first time.
We highlight privacy issues in state of the art multi-modal LLM models used for
DocVQA, and explore possible solutions.
  Specifically, we focus on the invoice processing use case as a realistic,
widely used scenario for document understanding, and propose a large scale
DocVQA dataset comprising invoice documents and associated questions and
answers. We employ a federated learning scheme, that reflects the real-life
distribution of documents in different businesses, and we explore the use case
where the ID of the invoice issuer is the sensitive information to be
protected.
  We demonstrate that non-private models tend to memorise, behaviour that can
lead to exposing private information. We then evaluate baseline training
schemes employing federated learning and differential privacy in this
multi-modal scenario, where the sensitive information might be exposed through
any of the two input modalities: vision (document image) or language (OCR
tokens).
  Finally, we design an attack exploiting the memorisation effect of the model,
and demonstrate its effectiveness in probing different DocVQA models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.10096v1">Open Government Data Programs and Information Privacy Concerns: A
  Literature Review</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2023-12-14T16:03:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mehdi Barati</p>
    <p><b>Summary:</b> This study presents a narrative review of the literature on privacy concerns
of Open Government Data (OGD) programs and identifies suggested technical,
procedural, and legal remedies. Peer-reviewed articles were identified and
analysed from major bibliographic databases, including Web of Science, Digital
ACM Library, IEEE Explore Digital Library and Science Direct. Included articles
focus on identifying individual information privacy concerns from the viewpoint
of OGD stakeholders or providing solutions for mitigating concerns and risks.
Papers that discussed and focused on general privacy issues or privacy concerns
of open data in general or open science privacy concerns were excluded. Three
streams of research were identified: 1) exploring privacy concerns and balance
with OGD value propositions, 2) proposing solutions for mitigating privacy
concerns, and 3) developing risk-based frameworks for the OGD program at
different governmental levels. Findings suggest that contradictions with Fair
Information Practices, reidentification risks, conflicts with OGD value
propositions, and smart city data practices are significant privacy concerns in
the literature. Proposed solutions include technical, legal, and procedural
measures to mitigate privacy concerns. Building on the findings, practical
implications and suggested future research directions are provided.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.08685v1">Privacy Amplification by Iteration for ADMM with (Strongly) Convex
  Objective Functions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E">
  <p><b>Published on:</b> 2023-12-14T06:52:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> T-H. Hubert Chan, Hao Xie, Mengshi Zhao</p>
    <p><b>Summary:</b> We examine a private ADMM variant for (strongly) convex objectives which is a
primal-dual iterative method. Each iteration has a user with a private function
used to update the primal variable, masked by Gaussian noise for local privacy,
without directly adding noise to the dual variable. Privacy amplification by
iteration explores if noises from later iterations can enhance the privacy
guarantee when releasing final variables after the last iteration. Cyffers et
al. [ICML 2023] explored privacy amplification by iteration for the proximal
ADMM variant, where a user's entire private function is accessed and noise is
added to the primal variable. In contrast, we examine a private ADMM variant
requiring just one gradient access to a user's function, but both primal and
dual variables must be passed between successive iterations. To apply Balle et
al.'s [NeurIPS 2019] coupling framework to the gradient ADMM variant, we tackle
technical challenges with novel ideas. First, we address the non-expansive
mapping issue in ADMM iterations by using a customized norm. Second, because
the dual variables are not masked with any noise directly, their privacy
guarantees are achieved by treating two consecutive noisy ADMM iterations as a
Markov operator. Our main result is that the privacy guarantee for the gradient
ADMM variant can be amplified proportionally to the number of iterations. For
strongly convex objective functions, this amplification exponentially increases
with the number of iterations. These amplification results align with the
previously studied special case of stochastic gradient descent.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.08210v1">Differential Privacy Preserving Quantum Computing via Projection
  Operator Measurements</a></h3>
  
  <p><b>Published on:</b> 2023-12-13T15:27:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuqing Li, Yusheng Zhao, Xinyue Zhang, Hui Zhong, Miao Pan, Chi Zhang</p>
    <p><b>Summary:</b> Quantum computing has been widely applied in various fields, such as quantum
physics simulations, quantum machine learning, and big data analysis. However,
in the domains of data-driven paradigm, how to ensure the privacy of the
database is becoming a vital problem. For classical computing, we can
incorporate the concept of differential privacy (DP) to meet the standard of
privacy preservation by manually adding the noise. In the quantum computing
scenario, researchers have extended classic DP to quantum differential privacy
(QDP) by considering the quantum noise. In this paper, we propose a novel
approach to satisfy the QDP definition by considering the errors generated by
the projection operator measurement, which is denoted as shot noises. Then, we
discuss the amount of privacy budget that can be achieved with shot noises,
which serves as a metric for the level of privacy protection. Furthermore, we
provide the QDP of shot noise in quantum circuits with depolarizing noise.
Through numerical simulations, we show that shot noise can effectively provide
privacy protection in quantum computing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.08413v1">Privacy Constrained Fairness Estimation for Decision Trees</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2023-12-13T14:54:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Florian van der Steen, Fré Vink, Heysem Kaya</p>
    <p><b>Summary:</b> The protection of sensitive data becomes more vital, as data increases in
value and potency. Furthermore, the pressure increases from regulators and
society on model developers to make their Artificial Intelligence (AI) models
non-discriminatory. To boot, there is a need for interpretable, transparent AI
models for high-stakes tasks. In general, measuring the fairness of any AI
model requires the sensitive attributes of the individuals in the dataset, thus
raising privacy concerns. In this work, the trade-offs between fairness,
privacy and interpretability are further explored. We specifically examine the
Statistical Parity (SP) of Decision Trees (DTs) with Differential Privacy (DP),
that are each popular methods in their respective subfield. We propose a novel
method, dubbed Privacy-Aware Fairness Estimation of Rules (PAFER), that can
estimate SP in a DP-aware manner for DTs. DP, making use of a third-party legal
entity that securely holds this sensitive data, guarantees privacy by adding
noise to the sensitive data. We experimentally compare several DP mechanisms.
We show that using the Laplacian mechanism, the method is able to estimate SP
with low error while guaranteeing the privacy of the individuals in the dataset
with high certainty. We further show experimentally and theoretically that the
method performs better for DTs that humans generally find easier to interpret.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.08144v1">Privacy-Preserving Distributed Optimisation using Stochastic PDMM</a></h3>
  
  <p><b>Published on:</b> 2023-12-13T13:46:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sebastian O. Jordan, Qiongxiu Li, Richard Heusdens</p>
    <p><b>Summary:</b> Privacy-preserving distributed processing has received considerable attention
recently. The main purpose of these algorithms is to solve certain signal
processing tasks over a network in a decentralised fashion without revealing
private/secret data to the outside world. Because of the iterative nature of
these distributed algorithms, computationally complex approaches such as
(homomorphic) encryption are undesired. Recently, an information theoretic
method called subspace perturbation has been introduced for synchronous update
schemes. The main idea is to exploit a certain structure in the update
equations for noise insertion such that the private data is protected without
compromising the algorithm's accuracy. This structure, however, is absent in
asynchronous update schemes. In this paper we will investigate such
asynchronous schemes and derive a lower bound on the noise variance after
random initialisation of the algorithm. This bound shows that the privacy level
of asynchronous schemes is always better than or at least equal to that of
synchronous schemes. Computer simulations are conducted to consolidate our
theoretical results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.07992v1">On the privacy of federated Clustering: A Cryptographic View</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-13T09:04:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qiongxiu Li, Lixia Luo</p>
    <p><b>Summary:</b> The privacy concern in federated clustering has attracted considerable
attention in past decades. Many privacy-preserving clustering algorithms
leverage cryptographic techniques like homomorphic encryption or secure
multiparty computation, to guarantee full privacy, i.e., no additional
information is leaked other than the final output. However, given the iterative
nature of clustering algorithms, consistently encrypting intermediate outputs,
such as centroids, hampers efficiency. This paper delves into this intricate
trade-off, questioning the necessity of continuous encryption in iterative
algorithms. Using the federated K-means clustering as an example, we
mathematically formulate the problem of reconstructing input private data from
the intermediate centroids as a classical cryptographic problem called hidden
subset sum problem (HSSP)-extended from an NP-complete problem called subset
sum problem (SSP). Through an in-depth analysis, we show that existing
lattice-based HSSP attacks fail in reconstructing the private data given the
knowledge of intermediate centroids, thus it is secure to reveal them for the
sake of efficiency. To the best of our knowledge, our work is the first to cast
federated clustering's privacy concerns as a cryptographic problem HSSP such
that a concrete and rigorous analysis can be conducted.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.07956v1">Topology-Dependent Privacy Bound For Decentralized Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2023-12-13T08:07:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qiongxiu Li, Wenrui Yu, Changlong Ji, Richard Heusdens</p>
    <p><b>Summary:</b> Decentralized Federated Learning (FL) has attracted significant attention due
to its enhanced robustness and scalability compared to its centralized
counterpart. It pivots on peer-to-peer communication rather than depending on a
central server for model aggregation. While prior research has delved into
various factors of decentralized FL such as aggregation methods and
privacy-preserving techniques, one crucial aspect affecting privacy is
relatively unexplored: the underlying graph topology. In this paper, we fill
the gap by deriving a stringent privacy bound for decentralized FL under the
condition that the accuracy is not compromised, highlighting the pivotal role
of graph topology. Specifically, we demonstrate that the minimum privacy loss
at each model aggregation step is dependent on the size of what we term as
'honest components', the maximally connected subgraphs once all untrustworthy
participants are excluded from the networks, which is closely tied to network
robustness. Our analysis suggests that attack-resilient networks will provide a
superior privacy guarantee. We further validate this by studying both Poisson
and power law networks, showing that the latter, being less robust against
attacks, indeed reveals more privacy. In addition to a theoretical analysis, we
consolidate our findings by examining two distinct privacy attacks: membership
inference and gradient inversion.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.07948v1">Zero-Knowledge Proof of Traffic: A Deterministic and Privacy-Preserving
  Cross Verification Mechanism for Cooperative Perception Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-13T07:53:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ye Tao, Ehsan Javanmardi, Pengfei Lin, Jin Nakazato, Yuze Jiang, Manabu Tsukada, Hiroshi Esaki</p>
    <p><b>Summary:</b> Cooperative perception is crucial for connected automated vehicles in
intelligent transportation systems (ITSs); however, ensuring the authenticity
of perception data remains a challenge as the vehicles cannot verify events
that they do not witness independently. Various studies have been conducted on
establishing the authenticity of data, such as trust-based statistical methods
and plausibility-based methods. However, these methods are limited as they
require prior knowledge such as previous sender behaviors or predefined rules
to evaluate the authenticity. To overcome this limitation, this study proposes
a novel approach called zero-knowledge Proof of Traffic (zk-PoT), which
involves generating cryptographic proofs to the traffic observations. Multiple
independent proofs regarding the same vehicle can be deterministically
cross-verified by any receivers without relying on ground truth, probabilistic,
or plausibility evaluations. Additionally, no private information is
compromised during the entire procedure. A full on-board unit software stack
that reflects the behavior of zk-PoT is implemented within a specifically
designed simulator called Flowsim. A comprehensive experimental analysis is
then conducted using synthesized city-scale simulations, which demonstrates
that zk-PoT's cross-verification ratio ranges between 80 % to 96 %, and 80 % of
the verification is achieved in 2 s, with a protocol overhead of approximately
25 %. Furthermore, the analyses of various attacks indicate that most of the
attacks could be prevented, and some, such as collusion attacks, can be
mitigated. The proposed approach can be incorporated into existing works,
including the European Telecommunications Standards Institute (ETSI) and the
International Organization for Standardization (ISO) ITS standards, without
disrupting the backward compatibility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.07947v1">Adaptive Differentially Quantized Subspace Perturbation (ADQSP): A
  Unified Framework for Privacy-Preserving Distributed Average Consensus</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-13T07:52:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qiongxiu Li, Jaron Skovsted Gundersen, Milan Lopuhaa-Zwakenberg, Richard Heusdens</p>
    <p><b>Summary:</b> Privacy-preserving distributed average consensus has received significant
attention recently due to its wide applicability. Based on the achieved
performances, existing approaches can be broadly classified into perfect
accuracy-prioritized approaches such as secure multiparty computation (SMPC),
and worst-case privacy-prioritized approaches such as differential privacy
(DP). Methods of the first class achieve perfect output accuracy but reveal
some private information, while methods from the second class provide privacy
against the strongest adversary at the cost of a loss of accuracy. In this
paper, we propose a general approach named adaptive differentially quantized
subspace perturbation (ADQSP) which combines quantization schemes with
so-called subspace perturbation. Although not relying on cryptographic
primitives, the proposed approach enjoys the benefits of both
accuracy-prioritized and privacy-prioritized methods and is able to unify them.
More specifically, we show that by varying a single quantization parameter the
proposed method can vary between SMPC-type performances and DP-type
performances. Our results show the potential of exploiting traditional
distributed signal processing tools for providing cryptographic guarantees. In
addition to a comprehensive theoretical analysis, numerical validations are
conducted to substantiate our results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.07371v1">Privacy-Aware Energy Consumption Modeling of Connected Battery Electric
  Vehicles using Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2023-12-12T15:40:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sen Yan, Hongyuan Fang, Ji Li, Tomas Ward, Noel O'Connor, Mingming Liu</p>
    <p><b>Summary:</b> Battery Electric Vehicles (BEVs) are increasingly significant in modern
cities due to their potential to reduce air pollution. Precise and real-time
estimation of energy consumption for them is imperative for effective itinerary
planning and optimizing vehicle systems, which can reduce driving range anxiety
and decrease energy costs. As public awareness of data privacy increases,
adopting approaches that safeguard data privacy in the context of BEV energy
consumption modeling is crucial. Federated Learning (FL) is a promising
solution mitigating the risk of exposing sensitive information to third parties
by allowing local data to remain on devices and only sharing model updates with
a central server. Our work investigates the potential of using FL methods, such
as FedAvg, and FedPer, to improve BEV energy consumption prediction while
maintaining user privacy. We conducted experiments using data from 10 BEVs
under simulated real-world driving conditions. Our results demonstrate that the
FedAvg-LSTM model achieved a reduction of up to 67.84\% in the MAE value of the
prediction results. Furthermore, we explored various real-world scenarios and
discussed how FL methods can be employed in those cases. Our findings show that
FL methods can effectively improve the performance of BEV energy consumption
prediction while maintaining user privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.07060v1">Layered Randomized Quantization for Communication-Efficient and
  Privacy-Preserving Distributed Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2023-12-12T08:27:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guangfeng Yan, Tan Li, Tian Lan, Kui Wu, Linqi Song</p>
    <p><b>Summary:</b> Next-generation wireless networks, such as edge intelligence and wireless
distributed learning, face two critical challenges: communication efficiency
and privacy protection. In this work, our focus is on addressing these issues
in a distributed learning framework. We consider a new approach that
simultaneously achieves communication efficiency and privacy protection by
exploiting the privacy advantage offered by quantization. Specifically, we use
a quantization scheme called \textbf{Gau}ssian \textbf{L}ayered
\textbf{R}andomized \textbf{Q}uantization (Gau-LRQ) that compresses the raw
model gradients using a layer multishift coupler. By adjusting the parameters
of Gau-LRQ, we shape the quantization error to follow the expected Gaussian
distribution, thus ensuring client-level differential privacy (CLDP). We
demonstrate the effectiveness of our proposed Gau-LRQ in the distributed
stochastic gradient descent (SGD) framework and theoretically quantify the
trade-offs between communication, privacy, and convergence performance. We
further improve the convergence performance by enabling dynamic private budget
and quantization bit allocation. We achieve this by using an optimization
formula that minimizes convergence error subject to the privacy budget
constraint. We evaluate our approach on multiple datasets, including MNIST,
CIFAR-10, and CIFAR-100, and show that our proposed method outperforms the
baselines in terms of learning performance under various privacy constraints.
Moreover, we observe that dynamic privacy allocation yields additional accuracy
improvements for the models compared to the fixed scheme.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.07055v1">Communication Cost Reduction for Subgraph Counting under Local
  Differential Privacy via Hash Functions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2023-12-12T08:12:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Quentin Hillebrand, Vorapong Suppakitpaisarn, Tetsuo Shibuya</p>
    <p><b>Summary:</b> We suggest the use of hash functions to cut down the communication costs when
counting subgraphs under edge local differential privacy. While various
algorithms exist for computing graph statistics, including the count of
subgraphs, under the edge local differential privacy, many suffer with high
communication costs, making them less efficient for large graphs. Though data
compression is a typical approach in differential privacy, its application in
local differential privacy requires a form of compression that every node can
reproduce. In our study, we introduce linear congruence hashing. With a
sampling rate of $s$, our method can cut communication costs by a factor of
$s^2$, albeit at the cost of increasing variance in the published graph
statistic by a factor of $s$. The experimental results indicate that, when
matched for communication costs, our method achieves a reduction in the
$\ell_2$-error for triangle counts by up to 1000 times compared to the
performance of leading algorithms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.06989v1">Task-Agnostic Privacy-Preserving Representation Learning for Federated
  Learning Against Attribute Inference Attacks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-12T05:17:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Caridad Arroyo Arevalo, Sayedeh Leila Noorbakhsh, Yun Dong, Yuan Hong, Binghui Wang</p>
    <p><b>Summary:</b> Federated learning (FL) has been widely studied recently due to its property
to collaboratively train data from different devices without sharing the raw
data. Nevertheless, recent studies show that an adversary can still be possible
to infer private information about devices' data, e.g., sensitive attributes
such as income, race, and sexual orientation. To mitigate the attribute
inference attacks, various existing privacy-preserving FL methods can be
adopted/adapted. However, all these existing methods have key limitations: they
need to know the FL task in advance, or have intolerable computational
overheads or utility losses, or do not have provable privacy guarantees.
  We address these issues and design a task-agnostic privacy-preserving
presentation learning method for FL ({\bf TAPPFL}) against attribute inference
attacks. TAPPFL is formulated via information theory. Specifically, TAPPFL has
two mutual information goals, where one goal learns task-agnostic data
representations that contain the least information about the private attribute
in each device's data, and the other goal ensures the learnt data
representations include as much information as possible about the device data
to maintain FL utility. We also derive privacy guarantees of TAPPFL against
worst-case attribute inference attacks, as well as the inherent tradeoff
between utility preservation and privacy protection. Extensive results on
multiple datasets and applications validate the effectiveness of TAPPFL to
protect data privacy, maintain the FL utility, and be efficient as well.
Experimental results also show that TAPPFL outperforms the existing
defenses\footnote{Source code and full version:
\url{https://github.com/TAPPFL}}.</p>
  </details>
</div>

