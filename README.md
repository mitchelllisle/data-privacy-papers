
<h2>2024-04</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.01619v1">Making Privacy-preserving Federated Graph Analytics with Strong
  Guarantees Practical (for Certain Queries)</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B">
  <p><b>Published on:</b> 2024-04-02T04:01:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kunlong Liu, Trinabh Gupta</p>
    <p><b>Summary:</b> Privacy-preserving federated graph analytics is an emerging area of research.
The goal is to run graph analytics queries over a set of devices that are
organized as a graph while keeping the raw data on the devices rather than
centralizing it. Further, no entity may learn any new information except for
the final query result. For instance, a device may not learn a neighbor's data.
The state-of-the-art prior work for this problem provides privacy guarantees
for a broad set of queries in a strong threat model where the devices can be
malicious. However, it imposes an impractical overhead: each device locally
requires over 8.79 hours of cpu time and 5.73 GiBs of network transfers per
query. This paper presents Colo, a new, low-cost system for privacy-preserving
federated graph analytics that requires minutes of cpu time and a few MiBs in
network transfers, for a particular subset of queries. At the heart of Colo is
a new secure computation protocol that enables a device to securely and
efficiently evaluate a graph query in its local neighborhood while hiding
device data, edge data, and topology data. An implementation and evaluation of
Colo shows that for running a variety of COVID-19 queries over a population of
1M devices, it requires less than 8.4 minutes of a device's CPU time and 4.93
MiBs in network transfers - improvements of up to three orders of magnitude.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.01283v1">Evaluating Privacy Perceptions, Experience, and Behavior of Software
  Development Teams</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-04-01T17:55:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maxwell Prybylo, Sara Haghighi, Sai Teja Peddinti, Sepideh Ghanavati</p>
    <p><b>Summary:</b> With the increase in the number of privacy regulations, small development
teams are forced to make privacy decisions on their own. In this paper, we
conduct a mixed-method survey study, including statistical and qualitative
analysis, to evaluate the privacy perceptions, practices, and knowledge of
members involved in various phases of software development (SDLC). Our survey
includes 362 participants from 23 countries, encompassing roles such as product
managers, developers, and testers. Our results show diverse definitions of
privacy across SDLC roles, emphasizing the need for a holistic privacy approach
throughout SDLC. We find that software teams, regardless of their region, are
less familiar with privacy concepts (such as anonymization), relying on
self-teaching and forums. Most participants are more familiar with GDPR and
HIPAA than other regulations, with multi-jurisdictional compliance being their
primary concern. Our results advocate the need for role-dependent solutions to
address the privacy challenges, and we highlight research directions and
educational takeaways to help improve privacy-aware software development.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.01270v1">Decentralized Collaborative Learning Framework with External Privacy
  Leakage Analysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-04-01T17:46:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tsuyoshi Idé, Dzung T. Phan, Rudy Raymond</p>
    <p><b>Summary:</b> This paper presents two methodological advancements in decentralized
multi-task learning under privacy constraints, aiming to pave the way for
future developments in next-generation Blockchain platforms. First, we expand
the existing framework for collaborative dictionary learning (CollabDict),
which has previously been limited to Gaussian mixture models, by incorporating
deep variational autoencoders (VAEs) into the framework, with a particular
focus on anomaly detection. We demonstrate that the VAE-based anomaly score
function shares the same mathematical structure as the non-deep model, and
provide comprehensive qualitative comparison. Second, considering the
widespread use of "pre-trained models," we provide a mathematical analysis on
data privacy leakage when models trained with CollabDict are shared externally.
We show that the CollabDict approach, when applied to Gaussian mixtures,
adheres to a Renyi differential privacy criterion. Additionally, we propose a
practical metric for monitoring internal privacy breaches during the learning
process.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.01231v1">Privacy Backdoors: Enhancing Membership Inference through Poisoning
  Pre-trained Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-04-01T16:50:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuxin Wen, Leo Marchyok, Sanghyun Hong, Jonas Geiping, Tom Goldstein, Nicholas Carlini</p>
    <p><b>Summary:</b> It is commonplace to produce application-specific models by fine-tuning large
pre-trained models using a small bespoke dataset. The widespread availability
of foundation model checkpoints on the web poses considerable risks, including
the vulnerability to backdoor attacks. In this paper, we unveil a new
vulnerability: the privacy backdoor attack. This black-box privacy attack aims
to amplify the privacy leakage that arises when fine-tuning a model: when a
victim fine-tunes a backdoored model, their training data will be leaked at a
significantly higher rate than if they had fine-tuned a typical model. We
conduct extensive experiments on various datasets and models, including both
vision-language models (CLIP) and large language models, demonstrating the
broad applicability and effectiveness of such an attack. Additionally, we carry
out multiple ablation studies with different fine-tuning methods and inference
strategies to thoroughly analyze this new threat. Our findings highlight a
critical privacy concern within the machine learning community and call for a
reevaluation of safety protocols in the use of open-source pre-trained models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.00847v1">Collaborative Learning of Anomalies with Privacy (CLAP) for Unsupervised
  Video Anomaly Detection: A New Baseline</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-04-01T01:25:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anas Al-lahham, Muhammad Zaigham Zaheer, Nurbek Tastan, Karthik Nandakumar</p>
    <p><b>Summary:</b> Unsupervised (US) video anomaly detection (VAD) in surveillance applications
is gaining more popularity recently due to its practical real-world
applications. As surveillance videos are privacy sensitive and the availability
of large-scale video data may enable better US-VAD systems, collaborative
learning can be highly rewarding in this setting. However, due to the extremely
challenging nature of the US-VAD task, where learning is carried out without
any annotations, privacy-preserving collaborative learning of US-VAD systems
has not been studied yet. In this paper, we propose a new baseline for anomaly
detection capable of localizing anomalous events in complex surveillance videos
in a fully unsupervised fashion without any labels on a privacy-preserving
participant-based distributed training configuration. Additionally, we propose
three new evaluation protocols to benchmark anomaly detection approaches on
various scenarios of collaborations and data availability. Based on these
protocols, we modify existing VAD datasets to extensively evaluate our approach
as well as existing US SOTA methods on two large-scale datasets including
UCF-Crime and XD-Violence. All proposed evaluation protocols, dataset splits,
and codes are available here: https://github.com/AnasEmad11/CLAP</p>
  </details>
</div>



<h2>2024-03</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.00777v1">Privacy-preserving Optics for Enhancing Protection in Face
  De-identification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2024-03-31T19:28:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jhon Lopez, Carlos Hinojosa, Henry Arguello, Bernard Ghanem</p>
    <p><b>Summary:</b> The modern surge in camera usage alongside widespread computer vision
technology applications poses significant privacy and security concerns.
Current artificial intelligence (AI) technologies aid in recognizing relevant
events and assisting in daily tasks in homes, offices, hospitals, etc. The need
to access or process personal information for these purposes raises privacy
concerns. While software-level solutions like face de-identification provide a
good privacy/utility trade-off, they present vulnerabilities to sniffing
attacks. In this paper, we propose a hardware-level face de-identification
method to solve this vulnerability. Specifically, our approach first learns an
optical encoder along with a regression model to obtain a face heatmap while
hiding the face identity from the source image. We also propose an
anonymization framework that generates a new face using the privacy-preserving
image, face heatmap, and a reference face image from a public dataset as input.
We validate our approach with extensive simulations and hardware experiments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.00696v1">Privacy Re-identification Attacks on Tabular GANs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-03-31T14:14:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abdallah Alshantti, Adil Rasheed, Frank Westad</p>
    <p><b>Summary:</b> Generative models are subject to overfitting and thus may potentially leak
sensitive information from the training data. In this work. we investigate the
privacy risks that can potentially arise from the use of generative adversarial
networks (GANs) for creating tabular synthetic datasets. For the purpose, we
analyse the effects of re-identification attacks on synthetic data, i.e.,
attacks which aim at selecting samples that are predicted to correspond to
memorised training samples based on their proximity to the nearest synthetic
records. We thus consider multiple settings where different attackers might
have different access levels or knowledge of the generative model and
predictive, and assess which information is potentially most useful for
launching more successful re-identification attacks. In doing so we also
consider the situation for which re-identification attacks are formulated as
reconstruction attacks, i.e., the situation where an attacker uses evolutionary
multi-objective optimisation for perturbing synthetic samples closer to the
training space. The results indicate that attackers can indeed pose major
privacy risks by selecting synthetic samples that are likely representative of
memorised training samples. In addition, we notice that privacy threats
considerably increase when the attacker either has knowledge or has black-box
access to the generative models. We also find that reconstruction attacks
through multi-objective optimisation even increase the risk of identifying
confidential samples.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.00673v1">A Survey of Privacy-Preserving Model Explanations: Privacy Risks,
  Attacks, and Countermeasures</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-03-31T12:44:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Thanh Tam Nguyen, Thanh Trung Huynh, Zhao Ren, Thanh Toan Nguyen, Phi Le Nguyen, Hongzhi Yin, Quoc Viet Hung Nguyen</p>
    <p><b>Summary:</b> As the adoption of explainable AI (XAI) continues to expand, the urgency to
address its privacy implications intensifies. Despite a growing corpus of
research in AI privacy and explainability, there is little attention on
privacy-preserving model explanations. This article presents the first thorough
survey about privacy attacks on model explanations and their countermeasures.
Our contribution to this field comprises a thorough analysis of research papers
with a connected taxonomy that facilitates the categorisation of privacy
attacks and countermeasures based on the targeted explanations. This work also
includes an initial investigation into the causes of privacy leaks. Finally, we
discuss unresolved issues and prospective research directions uncovered in our
analysis. This survey aims to be a valuable resource for the research community
and offers clear insights for those new to this domain. To support ongoing
research, we have established an online resource repository, which will be
continuously updated with new and relevant findings. Interested readers are
encouraged to access our repository at
https://github.com/tamlhp/awesome-privex.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.00600v2">AI Act and Large Language Models (LLMs): When critical issues and
  privacy impact require human and ethical oversight</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-03-31T08:14:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nicola Fabiano</p>
    <p><b>Summary:</b> The imposing evolution of artificial intelligence systems and, specifically,
of Large Language Models (LLM) makes it necessary to carry out assessments of
their level of risk and the impact they may have in the area of privacy,
personal data protection and at an ethical level, especially on the weakest and
most vulnerable. This contribution addresses human oversight, ethical
oversight, and privacy impact assessment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.00473v1">Privacy Backdoors: Stealing Data with Corrupted Pretrained Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-03-30T20:43:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shanglun Feng, Florian Tramèr</p>
    <p><b>Summary:</b> Practitioners commonly download pretrained machine learning models from open
repositories and finetune them to fit specific applications. We show that this
practice introduces a new risk of privacy backdoors. By tampering with a
pretrained model's weights, an attacker can fully compromise the privacy of the
finetuning data. We show how to build privacy backdoors for a variety of
models, including transformers, which enable an attacker to reconstruct
individual finetuning samples, with a guaranteed success! We further show that
backdoored models allow for tight privacy attacks on models trained with
differential privacy (DP). The common optimistic practice of training DP models
with loose privacy guarantees is thus insecure if the model is not trusted.
Overall, our work highlights a crucial and overlooked supply chain attack on
machine learning privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.00235v1">Information Security and Privacy in the Digital World: Some Selected
  Topics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-03-30T03:52:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jaydip Sen, Joceli Mayer, Subhasis Dasgupta, Subrata Nandi, Srinivasan Krishnaswamy, Pinaki Mitra, Mahendra Pratap Singh, Naga Prasanthi Kundeti, Chandra Sekhara Rao MVP, Sudha Sree Chekuri, Seshu Babu Pallapothu, Preethi Nanjundan, Jossy P. George, Abdelhadi El Allahi, Ilham Morino, Salma AIT Oussous, Siham Beloualid, Ahmed Tamtaoui, Abderrahim Bajit</p>
    <p><b>Summary:</b> In the era of generative artificial intelligence and the Internet of Things,
while there is explosive growth in the volume of data and the associated need
for processing, analysis, and storage, several new challenges are faced in
identifying spurious and fake information and protecting the privacy of
sensitive data. This has led to an increasing demand for more robust and
resilient schemes for authentication, integrity protection, encryption,
non-repudiation, and privacy-preservation of data. The chapters in this book
present some of the state-of-the-art research works in the field of
cryptography and security in computing and communications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.20120v1">Privacy-Preserving Data Aggregation Techniques for Enhanced Efficiency
  and Security in Wireless Sensor Networks: A Comprehensive Analysis and
  Evaluation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-03-29T11:09:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ayush Rastogi, Harsh Rastogi, Yash Rastogi, Divyansh Dubey</p>
    <p><b>Summary:</b> In this paper, we present a multidimensional, highly effective method for
aggregating data for wireless sensor networks while maintaining privacy. The
suggested system is resistant to data loss and secure against both active and
passive privacy compromising attacks, such as the coalition attack from a rogue
base station and kidnapped sensor nodes. With regard to cluster size, it
achieves consistent communication overhead, which is helpful in large-scale
WSNs. Due to its constant size communication overhead, the suggested strategy
outperforms the previous privacy-preserving data aggregation scheme not only in
terms of privacy preservation but also in terms of communication complexity and
energy costs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.19178v1">Enhancing Trust and Privacy in Distributed Networks: A Comprehensive
  Survey on Blockchain-based Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-03-28T07:08:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ji Liu, Chunlu Chen, Yu Li, Lin Sun, Yulun Song, Jingbo Zhou, Bo Jing, Dejing Dou</p>
    <p><b>Summary:</b> While centralized servers pose a risk of being a single point of failure,
decentralized approaches like blockchain offer a compelling solution by
implementing a consensus mechanism among multiple entities. Merging distributed
computing with cryptographic techniques, decentralized technologies introduce a
novel computing paradigm. Blockchain ensures secure, transparent, and
tamper-proof data management by validating and recording transactions via
consensus across network nodes. Federated Learning (FL), as a distributed
machine learning framework, enables participants to collaboratively train
models while safeguarding data privacy by avoiding direct raw data exchange.
Despite the growing interest in decentralized methods, their application in FL
remains underexplored. This paper presents a thorough investigation into
Blockchain-based FL (BCFL), spotlighting the synergy between blockchain's
security features and FL's privacy-preserving model training capabilities.
First, we present the taxonomy of BCFL from three aspects, including
decentralized, separate networks, and reputation-based architectures. Then, we
summarize the general architecture of BCFL systems, providing a comprehensive
perspective on FL architectures informed by blockchain. Afterward, we analyze
the application of BCFL in healthcare, IoT, and other privacy-sensitive areas.
Finally, we identify future research directions of BCFL.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.18357v1">Minimax density estimation in the adversarial framework under local
  differential privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> 
  <p><b>Published on:</b> 2024-03-27T08:49:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mélisande Albert, Juliette Chevallier, Béatrice Laurent, Ousmane Sacko</p>
    <p><b>Summary:</b> We consider the problem of nonparametric density estimation under privacy
constraints in an adversarial framework. To this end, we study minimax rates
under local differential privacy over Sobolev spaces. We first obtain a lower
bound which allows us to quantify the impact of privacy compared with the
classical framework. Next, we introduce a new Coordinate block privacy
mechanism that guarantees local differential privacy, which, coupled with a
projection estimator, achieves the minimax optimal rates.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.18326v1">Privacy-Preserving Distributed Nonnegative Matrix Factorization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2024-03-27T08:07:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ehsan Lari, Reza Arablouei, Stefan Werner</p>
    <p><b>Summary:</b> Nonnegative matrix factorization (NMF) is an effective data representation
tool with numerous applications in signal processing and machine learning.
However, deploying NMF in a decentralized manner over ad-hoc networks
introduces privacy concerns due to the conventional approach of sharing raw
data among network agents. To address this, we propose a privacy-preserving
algorithm for fully-distributed NMF that decomposes a distributed large data
matrix into left and right matrix factors while safeguarding each agent's local
data privacy. It facilitates collaborative estimation of the left matrix factor
among agents and enables them to estimate their respective right factors
without exposing raw data. To ensure data privacy, we secure information
exchanges between neighboring agents utilizing the Paillier cryptosystem, a
probabilistic asymmetric algorithm for public-key cryptography that allows
computations on encrypted data without decryption. Simulation results conducted
on synthetic and real-world datasets demonstrate the effectiveness of the
proposed algorithm in achieving privacy-preserving distributed NMF over ad-hoc
networks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.18205v1">Exploring the Privacy Protection Capabilities of Chinese Large Language
  Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-03-27T02:31:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuqi Yang, Xiaowen Huang, Jitao Sang</p>
    <p><b>Summary:</b> Large language models (LLMs), renowned for their impressive capabilities in
various tasks, have significantly advanced artificial intelligence. Yet, these
advancements have raised growing concerns about privacy and security
implications. To address these issues and explain the risks inherent in these
models, we have devised a three-tiered progressive framework tailored for
evaluating privacy in language systems. This framework consists of
progressively complex and in-depth privacy test tasks at each tier. Our primary
objective is to comprehensively evaluate the sensitivity of large language
models to private information, examining how effectively they discern, manage,
and safeguard sensitive data in diverse scenarios. This systematic evaluation
helps us understand the degree to which these models comply with privacy
protection guidelines and the effectiveness of their inherent safeguards
against privacy breaches. Our observations indicate that existing Chinese large
language models universally show privacy protection shortcomings. It seems that
at the moment this widespread issue is unavoidable and may pose corresponding
privacy risks in applications based on these models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.17648v1">Healthcare Data Governance, Privacy, and Security -- A Conceptual
  Framework</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-03-26T12:29:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Amen Faridoon, M. Tahar Kechadi</p>
    <p><b>Summary:</b> The abundance of data has transformed the world in every aspect. It has
become the core element in decision making, problem solving, and innovation in
almost all areas of life, including business, science, healthcare, education,
and many others. Despite all these advances, privacy and security remain
critical concerns of the healthcare industry. It is important to note that
healthcare data can also be a liability if it is not managed correctly. This
data mismanagement can have severe consequences for patients and healthcare
organisations, including patient safety, legal liability, damage to reputation,
financial loss, and operational inefficiency. Healthcare organisations must
comply with a range of regulations to protect patient data. We perform a
classification of data governance elements or components in a manner that
thoroughly assesses the healthcare data chain from a privacy and security
standpoint. After deeply analysing the existing literature, we propose a
conceptual privacy and security driven healthcare data governance framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.17572v1">Enhancing Privacy in Federated Learning through Local Training</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E">
  <p><b>Published on:</b> 2024-03-26T10:25:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nicola Bastianello, Changxin Liu, Karl H. Johansson</p>
    <p><b>Summary:</b> In this paper we propose the federated private local training algorithm
(Fed-PLT) for federated learning, to overcome the challenges of (i) expensive
communications and (ii) privacy preservation. We address (i) by allowing for
both partial participation and local training, which significantly reduce the
number of communication rounds between the central coordinator and computing
agents. The algorithm matches the state of the art in the sense that the use of
local training demonstrably does not impact accuracy. Additionally, agents have
the flexibility to choose from various local training solvers, such as
(stochastic) gradient descent and accelerated gradient descent. Further, we
investigate how employing local training can enhance privacy, addressing point
(ii). In particular, we derive differential privacy bounds and highlight their
dependence on the number of local training epochs. We assess the effectiveness
of the proposed algorithm by comparing it to alternative techniques,
considering both theoretical analysis and numerical results from a
classification task.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.17414v1">The Privacy Policy Permission Model: A Unified View of Privacy Policies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-03-26T06:12:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maryam Majedi, Ken Barker</p>
    <p><b>Summary:</b> Organizations use privacy policies to communicate their data collection
practices to their clients. A privacy policy is a set of statements that
specifies how an organization gathers, uses, discloses, and maintains a
client's data. However, most privacy policies lack a clear, complete
explanation of how data providers' information is used. We propose a modeling
methodology, called the Privacy Policy Permission Model (PPPM), that provides a
uniform, easy-to-understand representation of privacy policies, which can
accurately and clearly show how data is used within an organization's practice.
Using this methodology, a privacy policy is captured as a diagram. The diagram
is capable of highlighting inconsistencies and inaccuracies in the privacy
policy. The methodology supports privacy officers in properly and clearly
articulating an organization's privacy policy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.17303v1">Two Birds with One Stone: Differential Privacy by Low-power SRAM Memory</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-03-26T01:14:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jianqing Liu, Na Gong, Hritom Das</p>
    <p><b>Summary:</b> The software-based implementation of differential privacy mechanisms has been
shown to be neither friendly for lightweight devices nor secure against
side-channel attacks. In this work, we aim to develop a hardware-based
technique to achieve differential privacy by design. In contrary to the
conventional software-based noise generation and injection process, our design
realizes local differential privacy (LDP) by harnessing the inherent hardware
noise into controlled LDP noise when data is stored in the memory.
Specifically, the noise is tamed through a novel memory design and power
downscaling technique, which leads to double-faceted gains in privacy and power
efficiency. A well-round study that consists of theoretical design and analysis
and chip implementation and experiments is presented. The results confirm that
the developed technique is differentially private, saves 88.58% system power,
speeds up software-based DP mechanisms by more than 10^6 times, while only
incurring 2.46% chip overhead and 7.81% estimation errors in data recovery.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.17296v1">Hawk: Accurate and Fast Privacy-Preserving Machine Learning Using Secure
  Lookup Table Computation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-03-26T00:51:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hamza Saleem, Amir Ziashahabi, Muhammad Naveed, Salman Avestimehr</p>
    <p><b>Summary:</b> Training machine learning models on data from multiple entities without
direct data sharing can unlock applications otherwise hindered by business,
legal, or ethical constraints. In this work, we design and implement new
privacy-preserving machine learning protocols for logistic regression and
neural network models. We adopt a two-server model where data owners
secret-share their data between two servers that train and evaluate the model
on the joint data. A significant source of inefficiency and inaccuracy in
existing methods arises from using Yao's garbled circuits to compute non-linear
activation functions. We propose new methods for computing non-linear functions
based on secret-shared lookup tables, offering both computational efficiency
and improved accuracy.
  Beyond introducing leakage-free techniques, we initiate the exploration of
relaxed security measures for privacy-preserving machine learning. Instead of
claiming that the servers gain no knowledge during the computation, we contend
that while some information is revealed about access patterns to lookup tables,
it maintains epsilon-dX-privacy. Leveraging this relaxation significantly
reduces the computational resources needed for training. We present new
cryptographic protocols tailored to this relaxed security paradigm and define
and analyze the leakage. Our evaluations show that our logistic regression
protocol is up to 9x faster, and the neural network training is up to 688x
faster than SecureML. Notably, our neural network achieves an accuracy of 96.6%
on MNIST in 15 epochs, outperforming prior benchmarks that capped at 93.4%
using the same architecture.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.17225v1">Measuring Compliance with the California Consumer Privacy Act Over Space
  and Time</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-03-25T21:57:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Van Tran, Aarushi Mehrotra, Marshini Chetty, Nick Feamster, Jens Frankenreiter, Lior Strahilevitz</p>
    <p><b>Summary:</b> The widespread sharing of consumers personal information with third parties
raises significant privacy concerns. The California Consumer Privacy Act (CCPA)
mandates that online businesses offer consumers the option to opt out of the
sale and sharing of personal information. Our study automatically tracks the
presence of the opt-out link longitudinally across multiple states after the
California Privacy Rights Act (CPRA) went into effect. We categorize websites
based on whether they are subject to CCPA and investigate cases of potential
non-compliance. We find a number of websites that implement the opt-out link
early and across all examined states but also find a significant number of
CCPA-subject websites that fail to offer any opt-out methods even when CCPA is
in effect. Our findings can shed light on how websites are reacting to the CCPA
and identify potential gaps in compliance and opt-out method designs that
hinder consumers from exercising CCPA opt-out rights.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.16797v2">Privacy Preservation by Intermittent Transmission in Cooperative LQG
  Control Systems</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2024-03-25T14:14:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenhao Lin, Yuqing Ni, Wen Yang, Chao Yang</p>
    <p><b>Summary:</b> In this paper, we study a cooperative linear quadratic Gaussian (LQG) control
system with a single user and a server. In this system, the user runs a process
and employs the server to meet the needs of computation. However, the user
regards its state trajectories as privacy. Therefore, we propose a privacy
scheme, in which the user sends data to the server intermittently. By this
scheme, the server's received information of the user is reduced, and
consequently the user's privacy is preserved. In this paper, we consider a
periodic transmission scheme. We analyze the performance of privacy
preservation and LQG control of different transmission periods. Under the given
threshold of the control performance loss, a trade-off optimization problem is
proposed. Finally, we give the solution to the optimization problem.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.16773v1">Privacy-Protected Spatial Autoregressive Model</a></h3>
   
  <p><b>Published on:</b> 2024-03-25T13:51:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Danyang Huang, Ziyi Kong, Shuyuan Wu, Hansheng Wang</p>
    <p><b>Summary:</b> Spatial autoregressive (SAR) models are important tools for studying network
effects. However, with an increasing emphasis on data privacy, data providers
often implement privacy protection measures that make classical SAR models
inapplicable. In this study, we introduce a privacy-protected SAR model with
noise-added response and covariates to meet privacy-protection requirements.
However, in this scenario, the traditional quasi-maximum likelihood estimator
becomes infeasible because the likelihood function cannot be formulated. To
address this issue, we first consider an explicit expression for the likelihood
function with only noise-added responses. However, the derivatives are biased
owing to the noise in the covariates. Therefore, we develop techniques that can
correct the biases introduced by noise. Correspondingly, a Newton-Raphson-type
algorithm is proposed to obtain the estimator, leading to a corrected
likelihood estimator. To further enhance computational efficiency, we introduce
a corrected least squares estimator based on the idea of bias correction. These
two estimation methods ensure both data security and the attainment of
statistically valid estimators. Theoretical analysis of both estimators is
carefully conducted, and statistical inference methods are discussed. The
finite sample performances of different methods are demonstrated through
extensive simulations and the analysis of a real dataset.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.16591v3">Deciphering the Interplay between Local Differential Privacy, Average
  Bayesian Privacy, and Maximum Bayesian Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-03-25T10:06:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaojin Zhang, Yulin Fei, Wei Chen</p>
    <p><b>Summary:</b> The swift evolution of machine learning has led to emergence of various
definitions of privacy due to the threats it poses to privacy, including the
concept of local differential privacy (LDP). Although widely embraced and
utilized across numerous domains, this conventional approach to measure privacy
still exhibits certain limitations, spanning from failure to prevent
inferential disclosure to lack of consideration for the adversary's background
knowledge. In this comprehensive study, we introduce Bayesian privacy and delve
into the intricate relationship between LDP and its Bayesian counterparts,
unveiling novel insights into utility-privacy trade-offs. We introduce a
framework that encapsulates both attack and defense strategies, highlighting
their interplay and effectiveness. The relationship between LDP and Maximum
Bayesian Privacy (MBP) is first revealed, demonstrating that under uniform
prior distribution, a mechanism satisfying $\xi$-LDP will satisfy $\xi$-MBP and
conversely $\xi$-MBP also confers 2$\xi$-LDP. Our next theoretical contribution
are anchored in the rigorous definitions and relationships between Average
Bayesian Privacy (ABP) and Maximum Bayesian Privacy (MBP), encapsulated by
equations $\epsilon_{p,a} \leq \frac{1}{\sqrt{2}}\sqrt{(\epsilon_{p,m} +
\epsilon)\cdot(e^{\epsilon_{p,m} + \epsilon} - 1)}$. These relationships
fortify our understanding of the privacy guarantees provided by various
mechanisms. Our work not only lays the groundwork for future empirical
exploration but also promises to facilitate the design of privacy-preserving
algorithms, thereby fostering the development of trustworthy machine learning
solutions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.16473v1">Plaintext-Free Deep Learning for Privacy-Preserving Medical Image
  Analysis via Frequency Information Embedding</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-03-25T06:56:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mengyu Sun, Ziyuan Yang, Maosong Ran, Zhiwen Wang, Hui Yu, Yi Zhang</p>
    <p><b>Summary:</b> In the fast-evolving field of medical image analysis, Deep Learning
(DL)-based methods have achieved tremendous success. However, these methods
require plaintext data for training and inference stages, raising privacy
concerns, especially in the sensitive area of medical data. To tackle these
concerns, this paper proposes a novel framework that uses surrogate images for
analysis, eliminating the need for plaintext images. This approach is called
Frequency-domain Exchange Style Fusion (FESF). The framework includes two main
components: Image Hidden Module (IHM) and Image Quality Enhancement
Module~(IQEM). The~IHM performs in the frequency domain, blending the features
of plaintext medical images into host medical images, and then combines this
with IQEM to improve and create surrogate images effectively. During the
diagnostic model training process, only surrogate images are used, enabling
anonymous analysis without any plaintext data during both training and
inference stages. Extensive evaluations demonstrate that our framework
effectively preserves the privacy of medical images and maintains diagnostic
accuracy of DL models at a relatively high level, proving its effectiveness
across various datasets and DL-based models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.16149v1">A Survey on Consumer IoT Traffic: Security and Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-03-24T13:43:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yan Jia, Yuxin Song, Zihou Liu, Qingyin Tan, Fangming Wang, Yu Zhang, Zheli Liu</p>
    <p><b>Summary:</b> For the past few years, the Consumer Internet of Things (CIoT) has entered
public lives. While CIoT has improved the convenience of people's daily lives,
it has also brought new security and privacy concerns. In this survey, we try
to figure out what researchers can learn about the security and privacy of CIoT
by traffic analysis, a popular method in the security community. From the
security and privacy perspective, this survey seeks out the new characteristics
in CIoT traffic analysis, the state-of-the-art progress in CIoT traffic
analysis, and the challenges yet to be solved. We collected 310 papers from
January 2018 to December 2023 related to CIoT traffic analysis from the
security and privacy perspective and summarized the process of CIoT traffic
analysis in which the new characteristics of CIoT are identified. Then, we
detail existing works based on five application goals: device fingerprinting,
user activity inference, malicious traffic analysis, security analysis, and
measurement. At last, we discuss the new challenges and future research
directions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.15208v1">VPAS: Publicly Verifiable and Privacy-Preserving Aggregate Statistics on
  Distributed Datasets</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-03-22T13:50:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohammed Alghazwi, Dewi Davies-Batista, Dimka Karastoyanova, Fatih Turkmen</p>
    <p><b>Summary:</b> Aggregate statistics play an important role in extracting meaningful insights
from distributed data while preserving privacy. A growing number of application
domains, such as healthcare, utilize these statistics in advancing research and
improving patient care.
  In this work, we explore the challenge of input validation and public
verifiability within privacy-preserving aggregation protocols. We address the
scenario in which a party receives data from multiple sources and must verify
the validity of the input and correctness of the computations over this data to
third parties, such as auditors, while ensuring input data privacy. To achieve
this, we propose the "VPAS" protocol, which satisfies these requirements. Our
protocol utilizes homomorphic encryption for data privacy, and employs
Zero-Knowledge Proofs (ZKP) and a blockchain system for input validation and
public verifiability. We constructed VPAS by extending existing verifiable
encryption schemes into secure protocols that enable N clients to encrypt,
aggregate, and subsequently release the final result to a collector in a
verifiable manner.
  We implemented and experimentally evaluated VPAS with regard to encryption
costs, proof generation, and verification. The findings indicate that the
overhead associated with verifiability in our protocol is 10x lower than that
incurred by simply using conventional zkSNARKs. This enhanced efficiency makes
it feasible to apply input validation with public verifiability across a wider
range of applications or use cases that can tolerate moderate computational
overhead associated with proof generation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.15045v1">DP-Dueling: Learning from Preference Feedback without Compromising User
  Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-03-22T09:02:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aadirupa Saha, Hilal Asi</p>
    <p><b>Summary:</b> We consider the well-studied dueling bandit problem, where a learner aims to
identify near-optimal actions using pairwise comparisons, under the constraint
of differential privacy. We consider a general class of utility-based
preference matrices for large (potentially unbounded) decision spaces and give
the first differentially private dueling bandit algorithm for active learning
with user preferences. Our proposed algorithms are computationally efficient
with near-optimal performance, both in terms of the private and non-private
regret bound. More precisely, we show that when the decision space is of finite
size $K$, our proposed algorithm yields order optimal $O\Big(\sum_{i =
2}^K\log\frac{KT}{\Delta_i} + \frac{K}{\epsilon}\Big)$ regret bound for pure
$\epsilon$-DP, where $\Delta_i$ denotes the suboptimality gap of the $i$-th
arm. We also present a matching lower bound analysis which proves the
optimality of our algorithms. Finally, we extend our results to any general
decision space in $d$-dimensions with potentially infinite arms and design an
$\epsilon$-DP algorithm with regret $\tilde{O} \left( \frac{d^6}{\kappa
\epsilon } + \frac{ d\sqrt{T }}{\kappa} \right)$, providing privacy for free
when $T \gg d$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.15510v1">Privacy-Preserving End-to-End Spoken Language Understanding</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2024-03-22T03:41:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yinggui Wang, Wei Huang, Le Yang</p>
    <p><b>Summary:</b> Spoken language understanding (SLU), one of the key enabling technologies for
human-computer interaction in IoT devices, provides an easy-to-use user
interface. Human speech can contain a lot of user-sensitive information, such
as gender, identity, and sensitive content. New types of security and privacy
breaches have thus emerged. Users do not want to expose their personal
sensitive information to malicious attacks by untrusted third parties. Thus,
the SLU system needs to ensure that a potential malicious attacker cannot
deduce the sensitive attributes of the users, while it should avoid greatly
compromising the SLU accuracy. To address the above challenge, this paper
proposes a novel SLU multi-task privacy-preserving model to prevent both the
speech recognition (ASR) and identity recognition (IR) attacks. The model uses
the hidden layer separation technique so that SLU information is distributed
only in a specific portion of the hidden layer, and the other two types of
information are removed to obtain a privacy-secure hidden layer. In order to
achieve good balance between efficiency and privacy, we introduce a new
mechanism of model pre-training, namely joint adversarial training, to further
enhance the user privacy. Experiments over two SLU datasets show that the
proposed method can reduce the accuracy of both the ASR and IR attacks close to
that of a random guess, while leaving the SLU performance largely unaffected.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.14905v1">Adaptive Coded Federated Learning: Privacy Preservation and Straggler
  Mitigation</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-03-22T01:51:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chengxi Li, Ming Xiao, Mikael Skoglund</p>
    <p><b>Summary:</b> In this article, we address the problem of federated learning in the presence
of stragglers. For this problem, a coded federated learning framework has been
proposed, where the central server aggregates gradients received from the
non-stragglers and gradient computed from a privacy-preservation global coded
dataset to mitigate the negative impact of the stragglers. However, when
aggregating these gradients, fixed weights are consistently applied across
iterations, neglecting the generation process of the global coded dataset and
the dynamic nature of the trained model over iterations. This oversight may
result in diminished learning performance. To overcome this drawback, we
propose a new method named adaptive coded federated learning (ACFL). In ACFL,
before the training, each device uploads a coded local dataset with additive
noise to the central server to generate a global coded dataset under privacy
preservation requirements. During each iteration of the training, the central
server aggregates the gradients received from the non-stragglers and the
gradient computed from the global coded dataset, where an adaptive policy for
varying the aggregation weights is designed. Under this policy, we optimize the
performance in terms of privacy and learning, where the learning performance is
analyzed through convergence analysis and the privacy performance is
characterized via mutual information differential privacy. Finally, we perform
simulations to demonstrate the superiority of ACFL compared with the
non-adaptive methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.14450v1">Maximal $α$-Leakage for Quantum Privacy Mechanisms</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2024-03-21T14:58:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bo-Yu Yang, Hsuan Yu, Hao-Chung Cheng</p>
    <p><b>Summary:</b> In this work, maximal $\alpha$-leakage is introduced to quantify how much a
quantum adversary can learn about any sensitive information of data upon
observing its disturbed version via a quantum privacy mechanism. We first show
that an adversary's maximal expected $\alpha$-gain using optimal measurement is
characterized by measured conditional R\'enyi entropy. This can be viewed as a
parametric generalization of K\"onig et al.'s famous guessing probability
formula [IEEE Trans. Inf. Theory, 55(9), 2009]. Then, we prove that the
$\alpha$-leakage and maximal $\alpha$-leakage for a quantum privacy mechanism
are determined by measured Arimoto information and measured R\'enyi capacity,
respectively. Various properties of maximal $\alpha$-leakage, such as data
processing inequality and composition property are established as well.
Moreover, we show that regularized $\alpha$-leakage and regularized maximal
$\alpha$-leakage for identical and independent quantum privacy mechanisms
coincide with $\alpha$-tilted sandwiched R\'enyi information and sandwiched
R\'enyi capacity, respectively.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.14428v1">FHAUC: Privacy Preserving AUC Calculation for Federated Learning using
  Fully Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-03-21T14:36:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Cem Ata Baykara, Ali Burak Ünal, Mete Akgün</p>
    <p><b>Summary:</b> Ensuring data privacy is a significant challenge for machine learning
applications, not only during model training but also during evaluation.
Federated learning has gained significant research interest in recent years as
a result. Current research on federated learning primarily focuses on
preserving privacy during the training phase. However, model evaluation has not
been adequately addressed, despite the potential for significant privacy leaks
during this phase as well. In this paper, we demonstrate that the
state-of-the-art AUC computation method for federated learning systems, which
utilizes differential privacy, still leaks sensitive information about the test
data while also requiring a trusted central entity to perform the computations.
More importantly, we show that the performance of this method becomes
completely unusable as the data size decreases. In this context, we propose an
efficient, accurate, robust, and more secure evaluation algorithm capable of
computing the AUC in horizontal federated learning systems. Our approach not
only enhances security compared to the current state-of-the-art but also
surpasses the state-of-the-art AUC computation method in both approximation
performance and computational robustness, as demonstrated by experimental
results. To illustrate, our approach can efficiently calculate the AUC of a
federated learning system involving 100 parties, achieving 99.93% accuracy in
just 0.68 seconds, regardless of data size, while providing complete data
privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.14111v1">HETAL: Efficient Privacy-preserving Transfer Learning with Homomorphic
  Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-03-21T03:47:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Seewoo Lee, Garam Lee, Jung Woo Kim, Junbum Shin, Mun-Kyu Lee</p>
    <p><b>Summary:</b> Transfer learning is a de facto standard method for efficiently training
machine learning models for data-scarce problems by adding and fine-tuning new
classification layers to a model pre-trained on large datasets. Although
numerous previous studies proposed to use homomorphic encryption to resolve the
data privacy issue in transfer learning in the machine learning as a service
setting, most of them only focused on encrypted inference. In this study, we
present HETAL, an efficient Homomorphic Encryption based Transfer Learning
algorithm, that protects the client's privacy in training tasks by encrypting
the client data using the CKKS homomorphic encryption scheme. HETAL is the
first practical scheme that strictly provides encrypted training, adopting
validation-based early stopping and achieving the accuracy of nonencrypted
training. We propose an efficient encrypted matrix multiplication algorithm,
which is 1.8 to 323 times faster than prior methods, and a highly precise
softmax approximation algorithm with increased coverage. The experimental
results for five well-known benchmark datasets show total training times of
567-3442 seconds, which is less than an hour.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.14724v1">Six Levels of Privacy: A Framework for Financial Synthetic Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2024-03-20T20:41:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tucker Balch, Vamsi K. Potluru, Deepak Paramanand, Manuela Veloso</p>
    <p><b>Summary:</b> Synthetic Data is increasingly important in financial applications. In
addition to the benefits it provides, such as improved financial modeling and
better testing procedures, it poses privacy risks as well. Such data may arise
from client information, business information, or other proprietary sources
that must be protected. Even though the process by which Synthetic Data is
generated serves to obscure the original data to some degree, the extent to
which privacy is preserved is hard to assess. Accordingly, we introduce a
hierarchy of ``levels'' of privacy that are useful for categorizing Synthetic
Data generation methods and the progressively improved protections they offer.
While the six levels were devised in the context of financial applications,
they may also be appropriate for other industries as well. Our paper includes:
A brief overview of Financial Synthetic Data, how it can be used, how its value
can be assessed, privacy risks, and privacy attacks. We close with details of
the ``Six Levels'' that include defenses against those attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.13743v1">Quantum-Secure Certificate-Less Conditional Privacy-Preserving
  Authentication for VANET</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-03-20T16:50:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Girraj Kumar Verma, Nahida Majeed Wani, Prosanta Gope</p>
    <p><b>Summary:</b> Vehicular Ad-hoc Networks (VANETs) marked a pronounced change in the
Intelligent Transport System and Smart Cities through seamless vehicle
communication to intensify safety and efficacy. However, a few authentication
schemes have been devised in the literature to ensure the authenticity of the
source and information in the post-quantum era. The most popular base for such
construction is lattice-based cryptography. However, existing lattice-based
authentication schemes fall short of addressing the potential challenges of the
leakage of the master secret key and key-escrow problem. By ingeniously
addressing both issues, the paper proposes the \emph{first} quantum secure
authentication scheme to eliminate the flaws while maintaining the system's
overall efficiency intact. Compared to the state-of-the-art schemes, the
provable security and overall performance assessment highlight the suitability
of the proposed approach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.13346v2">A Control-Recoverable Added-Noise-based Privacy Scheme for LQ Control in
  Networked Control Systems</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2024-03-20T07:10:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xuening Tang, Xianghui Cao, Wei Xing Zheng</p>
    <p><b>Summary:</b> As networked control systems continue to evolve, ensuring the privacy of
sensitive data becomes an increasingly pressing concern, especially in
situations where the controller is physically separated from the plant. In this
paper, we propose a secure control scheme for computing linear quadratic
control in a networked control system utilizing two networked controllers, a
privacy encoder and a control restorer. Specifically, the encoder generates two
state signals blurred with random noise and sends them to the controllers,
while the restorer reconstructs the correct control signal. The proposed design
effectively preserves the privacy of the control system's state without
sacrificing the control performance. We theoretically quantify the
privacy-preserving performance in terms of the state estimation error of the
controllers and the disclosure probability. Additionally, the proposed
privacy-preserving scheme is also proven to satisfy differential privacy.
Moreover, we extend the proposed privacy-preserving scheme and evaluation
method to cases where collusion between two controllers occurs. Finally, we
verify the validity of our proposed scheme through simulations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.13041v1">Provable Privacy with Non-Private Pre-Processing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2024-03-19T17:54:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yaxi Hu, Amartya Sanyal, Bernhard Schölkopf</p>
    <p><b>Summary:</b> When analysing Differentially Private (DP) machine learning pipelines, the
potential privacy cost of data-dependent pre-processing is frequently
overlooked in privacy accounting. In this work, we propose a general framework
to evaluate the additional privacy cost incurred by non-private data-dependent
pre-processing algorithms. Our framework establishes upper bounds on the
overall privacy guarantees by utilising two new technical notions: a variant of
DP termed Smooth DP and the bounded sensitivity of the pre-processing
algorithms. In addition to the generic framework, we provide explicit overall
privacy guarantees for multiple data-dependent pre-processing algorithms, such
as data imputation, quantization, deduplication and PCA, when used in
combination with several DP algorithms. Notably, this framework is also simple
to implement, allowing direct integration into existing DP pipelines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.12710v1">Selective, Interpretable, and Motion Consistent Privacy Attribute
  Obfuscation for Action Recognition</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-03-19T13:17:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Filip Ilic, He Zhao, Thomas Pock, Richard P. Wildes</p>
    <p><b>Summary:</b> Concerns for the privacy of individuals captured in public imagery have led
to privacy-preserving action recognition. Existing approaches often suffer from
issues arising through obfuscation being applied globally and a lack of
interpretability. Global obfuscation hides privacy sensitive regions, but also
contextual regions important for action recognition. Lack of interpretability
erodes trust in these new technologies. We highlight the limitations of current
paradigms and propose a solution: Human selected privacy templates that yield
interpretability by design, an obfuscation scheme that selectively hides
attributes and also induces temporal consistency, which is important in action
recognition. Our approach is architecture agnostic and directly modifies input
imagery, while existing approaches generally require architecture training. Our
approach offers more flexibility, as no retraining is required, and outperforms
alternatives on three widely used datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.12457v1">Privacy-Preserving Face Recognition Using Trainable Feature Subtraction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-03-19T05:27:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuxi Mi, Zhizhou Zhong, Yuge Huang, Jiazhen Ji, Jianqing Xu, Jun Wang, Shaoming Wang, Shouhong Ding, Shuigeng Zhou</p>
    <p><b>Summary:</b> The widespread adoption of face recognition has led to increasing privacy
concerns, as unauthorized access to face images can expose sensitive personal
information. This paper explores face image protection against viewing and
recovery attacks. Inspired by image compression, we propose creating a visually
uninformative face image through feature subtraction between an original face
and its model-produced regeneration. Recognizable identity features within the
image are encouraged by co-training a recognition model on its high-dimensional
feature representation. To enhance privacy, the high-dimensional representation
is crafted through random channel shuffling, resulting in randomized
recognizable images devoid of attacker-leverageable texture details. We distill
our methodologies into a novel privacy-preserving face recognition method,
MinusFace. Experiments demonstrate its high recognition accuracy and effective
privacy protection. Its code is available at https://github.com/Tencent/TFace.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.12313v1">Improving LoRA in Privacy-preserving Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-03-18T23:20:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Youbang Sun, Zitao Li, Yaliang Li, Bolin Ding</p>
    <p><b>Summary:</b> Low-rank adaptation (LoRA) is one of the most popular task-specific
parameter-efficient fine-tuning (PEFT) methods on pre-trained language models
for its good performance and computational efficiency. LoRA injects a product
of two trainable rank decomposition matrices over the top of each frozen
pre-trained model module. However, when applied in the setting of
privacy-preserving federated learning (FL), LoRA may become unstable due to the
following facts: 1) the effects of data heterogeneity and multi-step local
updates are non-negligible, 2) additive noise enforced on updating gradients to
guarantee differential privacy (DP) can be amplified and 3) the final
performance is susceptible to hyper-parameters. A key factor leading to these
phenomena is the discordance between jointly optimizing the two low-rank
matrices by local clients and separately aggregating them by the central
server. Thus, this paper proposes an efficient and effective version of LoRA,
Federated Freeze A LoRA (FFA-LoRA), to alleviate these challenges and further
halve the communication cost of federated fine-tuning LLMs. The core idea of
FFA-LoRA is to fix the randomly initialized non-zero matrices and only
fine-tune the zero-initialized matrices. Compared to LoRA, FFA-LoRA is
motivated by practical and theoretical benefits in privacy-preserved FL. Our
experiments demonstrate that FFA-LoRA provides more consistent performance with
better computational efficiency over vanilla LoRA in various FL tasks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.11795v1">Low-Cost Privacy-Aware Decentralized Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-03-18T13:53:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sayan Biswas, Davide Frey, Romaric Gaudel, Anne-Marie Kermarrec, Dimitri Lerévérend, Rafael Pires, Rishi Sharma, François Taïani</p>
    <p><b>Summary:</b> This paper introduces ZIP-DL, a novel privacy-aware decentralized learning
(DL) algorithm that relies on adding correlated noise to each model update
during the model training process. This technique ensures that the added noise
almost neutralizes itself during the aggregation process due to its
correlation, thus minimizing the impact on model accuracy. In addition, ZIP-DL
does not require multiple communication rounds for noise cancellation,
addressing the common trade-off between privacy protection and communication
overhead. We provide theoretical guarantees for both convergence speed and
privacy guarantees, thereby making ZIP-DL applicable to practical scenarios.
Our extensive experimental study shows that ZIP-DL achieves the best trade-off
between vulnerability and accuracy. In particular, ZIP-DL (i) reduces the
effectiveness of a linkability attack by up to 52 points compared to baseline
DL, and (ii) achieves up to 37 more accuracy points for the same vulnerability
under membership inference attacks against a privacy-preserving competitor</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.11519v1">Efficient and Privacy-Preserving Federated Learning based on Full
  Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-03-18T07:13:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuqi Guo, Lin Li, Zhongxiang Zheng, Hanrui Yun, Ruoyan Zhang, Xiaolin Chang, Zhixuan Gao</p>
    <p><b>Summary:</b> Since the first theoretically feasible full homomorphic encryption (FHE)
scheme was proposed in 2009, great progress has been achieved. These
improvements have made FHE schemes come off the paper and become quite useful
in solving some practical problems. In this paper, we propose a set of novel
Federated Learning Schemes by utilizing the latest homomorphic encryption
technologies, so as to improve the security, functionality and practicality at
the same time. Comparisons have been given in four practical data sets
separately from medical, business, biometric and financial fields, covering
both horizontal and vertical federated learning scenarios. The experiment
results show that our scheme achieves significant improvements in security,
efficiency and practicality, compared with classical horizontal and vertical
federated learning schemes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.11445v1">Budget Recycling Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> 
  <p><b>Published on:</b> 2024-03-18T03:43:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bo Jiang, Jian Du, Sagar Shamar, Qiang Yan</p>
    <p><b>Summary:</b> Differential Privacy (DP) mechanisms usually {force} reduction in data
utility by producing ``out-of-bound'' noisy results for a tight privacy budget.
We introduce the Budget Recycling Differential Privacy (BR-DP) framework,
designed to provide soft-bounded noisy outputs for a broad range of existing DP
mechanisms. By ``soft-bounded," we refer to the mechanism's ability to release
most outputs within a predefined error boundary, thereby improving utility and
maintaining privacy simultaneously. The core of BR-DP consists of two
components: a DP kernel responsible for generating a noisy answer per
iteration, and a recycler that probabilistically recycles/regenerates or
releases the noisy answer. We delve into the privacy accounting of BR-DP,
culminating in the development of a budgeting principle that optimally
sub-allocates the available budget between the DP kernel and the recycler.
Furthermore, we introduce algorithms for tight BR-DP accounting in composition
scenarios, and our findings indicate that BR-DP achieves reduced privacy
leakage post-composition compared to DP. Additionally, we explore the concept
of privacy amplification via subsampling within the BR-DP framework and propose
optimal sampling rates for BR-DP across various queries. We experiment with
real data, and the results demonstrate BR-DP's effectiveness in lifting the
utility-privacy tradeoff provided by DP mechanisms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.11343v1">Federated Transfer Learning with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">   
  <p><b>Published on:</b> 2024-03-17T21:04:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mengchu Li, Ye Tian, Yang Feng, Yi Yu</p>
    <p><b>Summary:</b> Federated learning is gaining increasing popularity, with data heterogeneity
and privacy being two prominent challenges. In this paper, we address both
issues within a federated transfer learning framework, aiming to enhance
learning on a target data set by leveraging information from multiple
heterogeneous source data sets while adhering to privacy constraints. We
rigorously formulate the notion of \textit{federated differential privacy},
which offers privacy guarantees for each data set without assuming a trusted
central server. Under this privacy constraint, we study three classical
statistical problems, namely univariate mean estimation, low-dimensional linear
regression, and high-dimensional linear regression. By investigating the
minimax rates and identifying the costs of privacy for these problems, we show
that federated differential privacy is an intermediate privacy model between
the well-established local and central models of differential privacy. Our
analyses incorporate data heterogeneity and privacy, highlighting the
fundamental costs of both in federated learning and underscoring the benefit of
knowledge transfer across data sets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.11171v1">A Tip for IOTA Privacy: IOTA Light Node Deanonymization via Tip
  Selection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-03-17T11:12:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hojung Yang, Suhyeon Lee, Seungjoo Kim</p>
    <p><b>Summary:</b> IOTA is a distributed ledger technology that uses a Directed Acyclic Graph
(DAG) structure called the Tangle. It is known for its efficiency and is widely
used in the Internet of Things (IoT) environment. Tangle can be configured by
utilizing the tip selection process. Due to performance issues with light
nodes, full nodes are being asked to perform the tip selections of light nodes.
However, in this paper, we demonstrate that tip selection can be exploited to
compromise users' privacy. An adversary full node can associate a transaction
with the identity of a light node by comparing the light node's request with
its ledger. We show that these types of attacks are not only viable in the
current IOTA environment but also in IOTA 2.0 and the privacy improvement being
studied. We also provide solutions to mitigate these attacks and propose ways
to enhance anonymity in the IOTA network while maintaining efficiency and
scalability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.11088v1">Programming Frameworks for Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Programming Languages-D91E36">
  <p><b>Published on:</b> 2024-03-17T04:44:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marco Gaboardi, Michael Hay, Salil Vadhan</p>
    <p><b>Summary:</b> Many programming frameworks have been introduced to support the development
of differentially private software applications. In this chapter, we survey
some of the conceptual ideas underlying these frameworks in a way that we hope
will be helpful for both practitioners and researchers. For practitioners, the
survey can provide a starting point for understanding what features may be
valuable when selecting a programming framework. For researchers, it can help
organize existing work in a unified way and provide context for understanding
new features in future frameworks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.11064v1">Double-Private Distributed Estimation Algorithm Using Differential
  Privacy and a Key-Like Proportionate Matrix with Its Performance Analysis</a></h3>
  
  <p><b>Published on:</b> 2024-03-17T02:41:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mehdi Korki, Fatemehsadat Hosseiniamin, Hadi Zayyani, Mehdi Bekrani</p>
    <p><b>Summary:</b> In this brief, we present an enhanced privacy-preserving distributed
estimation algorithm, referred to as the ``Double-Private Algorithm," which
combines the principles of both differential privacy (DP) and cryptography. The
proposed algorithm enhances privacy by introducing DP noise into the
intermediate estimations of neighboring nodes. Additionally, we employ an
inverse of a closed-form reproducible proportionate gain matrix as the
cryptographic key matrix to fortify the privacy protection within the proposed
double private algorithm. \textcolor{blue}{We improve the algorithm by
transmitting alternative variable vectors instead of raw measurements,
resulting in enhanced key matrix reconstruction performance. This innovative
approach mitigate noise impact, enhancing overall algorithm effectiveness.} We
also establish an upper bound for the norm of the error between the non-private
Diffusion Least Mean Square (DLMS) algorithm and our double private algorithm.
Further, we determine a sufficient condition for the step-size to ensure the
mean convergence of the proposed algorithm. Simulation results demonstrate the
effectiveness of the proposed algorithm, particularly its ability to attain the
final Mean Square Deviation (MSD) comparable to that of the non-private DLMS.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.10920v1">Batch-oriented Element-wise Approximate Activation for
  Privacy-Preserving Neural Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-03-16T13:26:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Peng Zhang, Ao Duan, Xianglu Zou, Yuhong Liu</p>
    <p><b>Summary:</b> Privacy-Preserving Neural Networks (PPNN) are advanced to perform inference
without breaching user privacy, which can serve as an essential tool for
medical diagnosis to simultaneously achieve big data utility and privacy
protection. As one of the key techniques to enable PPNN, Fully Homomorphic
Encryption (FHE) is facing a great challenge that homomorphic operations cannot
be easily adapted for non-linear activation calculations. In this paper,
batch-oriented element-wise data packing and approximate activation are
proposed, which train linear low-degree polynomials to approximate the
non-linear activation function - ReLU. Compared with other approximate
activation methods, the proposed fine-grained, trainable approximation scheme
can effectively reduce the accuracy loss caused by approximation errors.
Meanwhile, due to element-wise data packing, a large batch of images can be
packed and inferred concurrently, leading to a much higher utility ratio of
ciphertext slots. Therefore, although the total inference time increases
sharply, the amortized time for each image actually decreases, especially when
the batch size increases. Furthermore, knowledge distillation is adopted in the
training process to further enhance the inference accuracy. Experiment results
show that when ciphertext inference is performed on 4096 input images, compared
with the current most efficient channel-wise method, the inference accuracy is
improved by 1.65%, and the amortized inference time is reduced by 99.5%.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.10676v1">Secure Distributed Storage: Optimal Trade-Off Between Storage Rate and
  Privacy Leakage</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-03-15T20:50:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Remi A. Chou, Joerg Kliewer</p>
    <p><b>Summary:</b> Consider the problem of storing data in a distributed manner over $T$
servers. Specifically, the data needs to (i) be recoverable from any $\tau$
servers, and (ii) remain private from any $z$ colluding servers, where privacy
is quantified in terms of mutual information between the data and all the
information available at any $z$ colluding servers. For this model, our main
results are (i) the fundamental trade-off between storage size and the level of
desired privacy, and (ii) the optimal amount of local randomness necessary at
the encoder. As a byproduct, our results provide an optimal lower bound on the
individual share size of ramp secret sharing schemes under a more general
leakage symmetry condition than the ones previously considered in the
literature.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.10408v1">SocialGenPod: Privacy-Friendly Generative AI Social Web Applications
  with Decentralised Personal Data Stores</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B"> 
  <p><b>Published on:</b> 2024-03-15T15:43:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vidminas Vizgirda, Rui Zhao, Naman Goel</p>
    <p><b>Summary:</b> We present SocialGenPod, a decentralised and privacy-friendly way of
deploying generative AI Web applications. Unlike centralised Web and data
architectures that keep user data tied to application and service providers, we
show how one can use Solid -- a decentralised Web specification -- to decouple
user data from generative AI applications. We demonstrate SocialGenPod using a
prototype that allows users to converse with different Large Language Models,
optionally leveraging Retrieval Augmented Generation to generate answers
grounded in private documents stored in any Solid Pod that the user is allowed
to access, directly or indirectly. SocialGenPod makes use of Solid access
control mechanisms to give users full control of determining who has access to
data stored in their Pods. SocialGenPod keeps all user data (chat history, app
configuration, personal documents, etc) securely in the user's personal Pod;
separate from specific model or application providers. Besides better privacy
controls, this approach also enables portability across different services and
applications. Finally, we discuss challenges, posed by the large compute
requirements of state-of-the-art models, that future research in this area
should address. Our prototype is open-source and available at:
https://github.com/Vidminas/socialgenpod/.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.10307v1">Chernoff Information as a Privacy Constraint for Adversarial
  Classification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2024-03-15T13:47:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ayşe Ünsal, Melek Önen</p>
    <p><b>Summary:</b> This work studies a privacy metric based on Chernoff information,
\textit{Chernoff differential privacy}, due to its significance in
characterization of classifier performance. Adversarial classification, as any
other classification problem is built around minimization of the (average or
correct detection) probability of error in deciding on either of the classes in
the case of binary classification. Unlike the classical hypothesis testing
problem, where the false alarm and mis-detection probabilities are handled
separately resulting in an asymmetric behavior of the best error exponent, in
this work, we focus on the Bayesian setting and characterize the relationship
between the best error exponent of the average error probability and
$\varepsilon-$differential privacy. Accordingly, we re-derive Chernoff
differential privacy in terms of $\varepsilon-$differential privacy using the
Radon-Nikodym derivative and show that it satisfies the composition property.
Subsequently, we present numerical evaluation results, which demonstrates that
Chernoff information outperforms Kullback-Leibler divergence as a function of
the privacy parameter $\varepsilon$, the impact of the adversary's attack and
global sensitivity for the problem of adversarial classification in Laplace
mechanisms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.10116v1">Instance-optimal Clipping for Summation Problems in the Shuffle Model of
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2024-03-15T09:04:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wei Dong, Qiyao Luo, Giulia Fanti, Elaine Shi, Ke Yi</p>
    <p><b>Summary:</b> Differentially private mechanisms achieving worst-case optimal error bounds
(e.g., the classical Laplace mechanism) are well-studied in the literature.
However, when typical data are far from the worst case,
\emph{instance-specific} error bounds -- which depend on the largest value in
the dataset -- are more meaningful. For example, consider the sum estimation
problem, where each user has an integer $x_i$ from the domain $\{0,1,\dots,U\}$
and we wish to estimate $\sum_i x_i$. This has a worst-case optimal error of
$O(U/\varepsilon)$, while recent work has shown that the clipping mechanism can
achieve an instance-optimal error of $O(\max_i x_i \cdot \log\log U
/\varepsilon)$. Under the shuffle model, known instance-optimal protocols are
less communication-efficient. The clipping mechanism also works in the shuffle
model, but requires two rounds: Round one finds the clipping threshold, and
round two does the clipping and computes the noisy sum of the clipped data. In
this paper, we show how these two seemingly sequential steps can be done
simultaneously in one round using just $1+o(1)$ messages per user, while
maintaining the instance-optimal error bound. We also extend our technique to
the high-dimensional sum estimation problem and sparse vector aggregation
(a.k.a. frequency estimation under user-level differential privacy). Our
experiments show order-of-magnitude improvements of our protocols in terms of
error compared with prior work.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.09836v1">Empowering Healthcare through Privacy-Preserving MRI Analysis</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-03-14T19:51:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Al Amin, Kamrul Hasan, Saleh Zein-Sabatto, Deo Chimba, Liang Hong, Imtiaz Ahmed, Tariqul Islam</p>
    <p><b>Summary:</b> In the healthcare domain, Magnetic Resonance Imaging (MRI) assumes a pivotal
role, as it employs Artificial Intelligence (AI) and Machine Learning (ML)
methodologies to extract invaluable insights from imaging data. Nonetheless,
the imperative need for patient privacy poses significant challenges when
collecting data from diverse healthcare sources. Consequently, the Deep
Learning (DL) communities occasionally face difficulties detecting rare
features. In this research endeavor, we introduce the Ensemble-Based Federated
Learning (EBFL) Framework, an innovative solution tailored to address this
challenge. The EBFL framework deviates from the conventional approach by
emphasizing model features over sharing sensitive patient data. This unique
methodology fosters a collaborative and privacy-conscious environment for
healthcare institutions, empowering them to harness the capabilities of a
centralized server for model refinement while upholding the utmost data privacy
standards.Conversely, a robust ensemble architecture boasts potent feature
extraction capabilities, distinguishing itself from a single DL model. This
quality makes it remarkably dependable for MRI analysis. By harnessing our
groundbreaking EBFL methodology, we have achieved remarkable precision in the
classification of brain tumors, including glioma, meningioma, pituitary, and
non-tumor instances, attaining a precision rate of 94% for the Global model and
an impressive 96% for the Ensemble model. Our models underwent rigorous
evaluation using conventional performance metrics such as Accuracy, Precision,
Recall, and F1 Score. Integrating DL within the Federated Learning (FL)
framework has yielded a methodology that offers precise and dependable
diagnostics for detecting brain tumors.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.09562v1">PreCurious: How Innocent Pre-Trained Language Models Turn into Privacy
  Traps</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-03-14T16:54:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruixuan Liu, Tianhao Wang, Yang Cao, Li Xiong</p>
    <p><b>Summary:</b> The pre-training and fine-tuning paradigm has demonstrated its effectiveness
and has become the standard approach for tailoring language models to various
tasks. Currently, community-based platforms offer easy access to various
pre-trained models, as anyone can publish without strict validation processes.
However, a released pre-trained model can be a privacy trap for fine-tuning
datasets if it is carefully designed. In this work, we propose PreCurious
framework to reveal the new attack surface where the attacker releases the
pre-trained model and gets a black-box access to the final fine-tuned model.
PreCurious aims to escalate the general privacy risk of both membership
inference and data extraction. The key intuition behind PreCurious is to
manipulate the memorization stage of the pre-trained model and guide
fine-tuning with a seemingly legitimate configuration. The effectiveness of
defending against privacy attacks on a fine-tuned model seems promising, as
empirical and theoretical evidence suggests that parameter-efficient and
differentially private fine-tuning techniques are invulnerable to privacy
attacks. But PreCurious demonstrates the possibility of breaking up
invulnerability in a stealthy manner compared to fine-tuning on a benign model.
By further leveraging a sanitized dataset, PreCurious can extract originally
unexposed secrets under differentially private fine-tuning. Thus, PreCurious
raises warnings for users who download pre-trained models from unknown sources,
rely solely on tutorials or common-sense defenses, and previously release
sanitized datasets even after perfect scrubbing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.09450v1">Shake to Leak: Fine-tuning Diffusion Models Can Amplify the Generative
  Privacy Risk</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-03-14T14:48:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhangheng Li, Junyuan Hong, Bo Li, Zhangyang Wang</p>
    <p><b>Summary:</b> While diffusion models have recently demonstrated remarkable progress in
generating realistic images, privacy risks also arise: published models or APIs
could generate training images and thus leak privacy-sensitive training
information. In this paper, we reveal a new risk, Shake-to-Leak (S2L), that
fine-tuning the pre-trained models with manipulated data can amplify the
existing privacy risks. We demonstrate that S2L could occur in various standard
fine-tuning strategies for diffusion models, including concept-injection
methods (DreamBooth and Textual Inversion) and parameter-efficient methods
(LoRA and Hypernetwork), as well as their combinations. In the worst case, S2L
can amplify the state-of-the-art membership inference attack (MIA) on diffusion
models by $5.4\%$ (absolute difference) AUC and can increase extracted private
samples from almost $0$ samples to $16.3$ samples on average per target domain.
This discovery underscores that the privacy risk with diffusion models is even
more severe than previously recognized. Codes are available at
https://github.com/VITA-Group/Shake-to-Leak.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.09351v1">LDPRecover: Recovering Frequencies from Poisoning Attacks against Local
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-03-14T12:57:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xinyue Sun, Qingqing Ye, Haibo Hu, Jiawei Duan, Tianyu Wo, Jie Xu, Renyu Yang</p>
    <p><b>Summary:</b> Local differential privacy (LDP), which enables an untrusted server to
collect aggregated statistics from distributed users while protecting the
privacy of those users, has been widely deployed in practice. However, LDP
protocols for frequency estimation are vulnerable to poisoning attacks, in
which an attacker can poison the aggregated frequencies by manipulating the
data sent from malicious users. Therefore, it is an open challenge to recover
the accurate aggregated frequencies from poisoned ones.
  In this work, we propose LDPRecover, a method that can recover accurate
aggregated frequencies from poisoning attacks, even if the server does not
learn the details of the attacks. In LDPRecover, we establish a genuine
frequency estimator that theoretically guides the server to recover the
frequencies aggregated from genuine users' data by eliminating the impact of
malicious users' data in poisoned frequencies. Since the server has no idea of
the attacks, we propose an adaptive attack to unify existing attacks and learn
the statistics of the malicious data within this adaptive attack by exploiting
the properties of LDP protocols. By taking the estimator and the learning
statistics as constraints, we formulate the problem of recovering aggregated
frequencies to approach the genuine ones as a constraint inference (CI)
problem. Consequently, the server can obtain accurate aggregated frequencies by
solving this problem optimally. Moreover, LDPRecover can serve as a frequency
recovery paradigm that recovers more accurate aggregated frequencies by
integrating attack details as new constraints in the CI problem. Our evaluation
on two real-world datasets, three LDP protocols, and untargeted and targeted
poisoning attacks shows that LDPRecover is both accurate and widely applicable
against various poisoning attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.09322v1">Privacy Preserving Anomaly Detection on Homomorphic Encrypted Data from
  IoT Sensors</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-03-14T12:11:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anca Hangan, Dragos Lazea, Tudor Cioara</p>
    <p><b>Summary:</b> IoT devices have become indispensable components of our lives, and the
advancement of AI technologies will make them even more pervasive, increasing
the vulnerability to malfunctions or cyberattacks and raising privacy concerns.
Encryption can mitigate these challenges; however, most existing anomaly
detection techniques decrypt the data to perform the analysis, potentially
undermining the encryption protection provided during transit or storage.
Homomorphic encryption schemes are promising solutions as they enable the
processing and execution of operations on IoT data while still encrypted,
however, these schemes offer only limited operations, which poses challenges to
their practical usage. In this paper, we propose a novel privacy-preserving
anomaly detection solution designed for homomorphically encrypted data
generated by IoT devices that efficiently detects abnormal values without
performing decryption. We have adapted the Histogram-based anomaly detection
technique for TFHE scheme to address limitations related to the input size and
the depth of computation by implementing vectorized support operations. These
operations include addition, value placement in buckets, labeling abnormal
buckets based on a threshold frequency, labeling abnormal values based on their
range, and bucket labels. Evaluation results show that the solution effectively
detects anomalies without requiring data decryption and achieves consistent
results comparable to the mechanism operating on plain data. Also, it shows
robustness and resilience against various challenges commonly encountered in
IoT environments, such as noisy sensor data, adversarial attacks, communication
failures, and device malfunctions. Moreover, the time and computational
overheads determined for several solution configurations, despite being large,
are reasonable compared to those reported in existing literature.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.09752v1">Explainable Machine Learning-Based Security and Privacy Protection
  Framework for Internet of Medical Things Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-03-14T11:57:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ayoub Si-ahmed, Mohammed Ali Al-Garadi, Narhimene Boustia</p>
    <p><b>Summary:</b> The Internet of Medical Things (IoMT) transcends traditional medical
boundaries, enabling a transition from reactive treatment to proactive
prevention. This innovative method revolutionizes healthcare by facilitating
early disease detection and tailored care, particularly in chronic disease
management, where IoMT automates treatments based on real-time health data
collection. Nonetheless, its benefits are countered by significant security
challenges that endanger the lives of its users due to the sensitivity and
value of the processed data, thereby attracting malicious interests. Moreover,
the utilization of wireless communication for data transmission exposes medical
data to interception and tampering by cybercriminals. Additionally, anomalies
may arise due to human errors, network interference, or hardware malfunctions.
In this context, anomaly detection based on Machine Learning (ML) is an
interesting solution, but it comes up against obstacles in terms of
explicability and protection of privacy. To address these challenges, a new
framework for Intrusion Detection Systems (IDS) is introduced, leveraging
Artificial Neural Networks (ANN) for intrusion detection while utilizing
Federated Learning (FL) for privacy preservation. Additionally, eXplainable
Artificial Intelligence (XAI) methods are incorporated to enhance model
explanation and interpretation. The efficacy of the proposed framework is
evaluated and compared with centralized approaches using multiple datasets
containing network and medical data, simulating various attack types impacting
the confidentiality, integrity, and availability of medical and physiological
data. The results obtained offer compelling evidence that the FL method
performs comparably to the centralized method, demonstrating high performance.
Additionally, it affords the dual advantage of safeguarding privacy and
providing model explanation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.09173v1">Bridging Quantum Computing and Differential Privacy: A Survey on Quantum
  Computing Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-03-14T08:40:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yusheng Zhao, Hui Zhong, Xinyue Zhang, Chi Zhang, Miao Pan</p>
    <p><b>Summary:</b> Quantum computing has attracted significant attention in areas such as
cryptography, cybersecurity, and drug discovery. Due to the advantage of
parallel processing, quantum computing can speed up the response to complex
challenges and the processing of large-scale datasets. However, since quantum
computing usually requires sensitive datasets, privacy breaches have become a
vital concern. Differential privacy (DP) is a promising privacy-preserving
method in classical computing and has been extended to the quantum domain in
recent years. In this survey, we categorize the existing literature based on
whether internal inherent noise or external artificial noise is used as a
source to achieve DP in quantum computing. We explore how these approaches are
applied at different stages of a quantum algorithm (i.e., state preparation,
quantum circuit, and quantum measurement). We also discuss challenges and
future directions for DP in quantum computing. By summarizing recent
advancements, we hope to provide a comprehensive, up-to-date overview for
researchers venturing into this field.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.09172v1">SHAN: Object-Level Privacy Detection via Inference on Scene
  Heterogeneous Graph</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-03-14T08:32:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhuohang Jiang, Bingkui Tong, Xia Du, Ahmed Alhammadi, Jizhe Zhou</p>
    <p><b>Summary:</b> With the rise of social platforms, protecting privacy has become an important
issue. Privacy object detection aims to accurately locate private objects in
images. It is the foundation of safeguarding individuals' privacy rights and
ensuring responsible data handling practices in the digital age. Since privacy
of object is not shift-invariant, the essence of the privacy object detection
task is inferring object privacy based on scene information. However, privacy
object detection has long been studied as a subproblem of common object
detection tasks. Therefore, existing methods suffer from serious deficiencies
in accuracy, generalization, and interpretability. Moreover, creating
large-scale privacy datasets is difficult due to legal constraints and existing
privacy datasets lack label granularity. The granularity of existing privacy
detection methods remains limited to the image level. To address the above two
issues, we introduce two benchmark datasets for object-level privacy detection
and propose SHAN, Scene Heterogeneous graph Attention Network, a model
constructs a scene heterogeneous graph from an image and utilizes
self-attention mechanisms for scene inference to obtain object privacy. Through
experiments, we demonstrated that SHAN performs excellently in privacy object
detection tasks, with all metrics surpassing those of the baseline model.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.10558v1">Adaptive Hybrid Masking Strategy for Privacy-Preserving Face Recognition
  Against Model Inversion Attack</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-03-14T02:17:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuanqing Huang, Yinggui Wang, Jianshu Li, Le Yang, Kai Song, Lei Wang</p>
    <p><b>Summary:</b> The utilization of personal sensitive data in training face recognition (FR)
models poses significant privacy concerns, as adversaries can employ model
inversion attacks (MIA) to infer the original training data. Existing defense
methods, such as data augmentation and differential privacy, have been employed
to mitigate this issue. However, these methods often fail to strike an optimal
balance between privacy and accuracy. To address this limitation, this paper
introduces an adaptive hybrid masking algorithm against MIA. Specifically, face
images are masked in the frequency domain using an adaptive MixUp strategy.
Unlike the traditional MixUp algorithm, which is predominantly used for data
augmentation, our modified approach incorporates frequency domain mixing.
Previous studies have shown that increasing the number of images mixed in MixUp
can enhance privacy preservation but at the expense of reduced face recognition
accuracy. To overcome this trade-off, we develop an enhanced adaptive MixUp
strategy based on reinforcement learning, which enables us to mix a larger
number of images while maintaining satisfactory recognition accuracy. To
optimize privacy protection, we propose maximizing the reward function (i.e.,
the loss function of the FR system) during the training of the strategy
network. While the loss function of the FR network is minimized in the phase of
training the FR network. The strategy network and the face recognition network
can be viewed as antagonistic entities in the training process, ultimately
reaching a more balanced trade-off. Experimental results demonstrate that our
proposed hybrid masking scheme outperforms existing defense algorithms in terms
of privacy preservation and recognition accuracy against MIA.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.08624v1">Towards a Privacy and Security-Aware Framework for Ethical AI: Guiding
  the Development and Assessment of AI Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-03-13T15:39:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Daria Korobenko, Anastasija Nikiforova, Rajesh Sharma</p>
    <p><b>Summary:</b> As artificial intelligence continues its unprecedented global expansion,
accompanied by a proliferation of benefits, an increasing apprehension about
the privacy and security implications of AI-enabled systems emerges. The
pivotal question of effectively controlling AI development at both
jurisdictional and organizational levels has become a prominent theme in
contemporary discourse. While the European Parliament and Council have taken a
decisive step by reaching a political agreement on the EU AI Act, the first
comprehensive AI law, organizations still find it challenging to adapt to the
fast-evolving AI landscape, lacking a universal tool for evaluating the privacy
and security dimensions of their AI models and systems. In response to this
critical challenge, this study conducts a systematic literature review spanning
the years 2020 to 2023, with a primary focus on establishing a unified
definition of key concepts in AI Ethics, particularly emphasizing the domains
of privacy and security. Through the synthesis of knowledge extracted from the
SLR, this study presents a conceptual framework tailored for privacy- and
security-aware AI systems. This framework is designed to assist diverse
stakeholders, including organizations, academic institutions, and governmental
bodies, in both the development and critical assessment of AI systems.
Essentially, the proposed framework serves as a guide for ethical
decision-making, fostering an environment wherein AI is developed and utilized
with a strong commitment to ethical principles. In addition, the study unravels
the key issues and challenges surrounding the privacy and security dimensions,
delineating promising avenues for future research, thereby contributing to the
ongoing dialogue on the globalization and democratization of AI ethics.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.08507v1">MobileAtlas: Geographically Decoupled Measurements in Cellular Networks
  for Security and Privacy Research</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-03-13T13:15:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gabriel Karl Gegenhuber, Wilfried Mayer, Edgar Weippl, Adrian Dabrowski</p>
    <p><b>Summary:</b> Cellular networks are not merely data access networks to the Internet. Their
distinct services and ability to form large complex compounds for roaming
purposes make them an attractive research target in their own right. Their
promise of providing a consistent service with comparable privacy and security
across roaming partners falls apart at close inspection.
  Thus, there is a need for controlled testbeds and measurement tools for
cellular access networks doing justice to the technology's unique structure and
global scope. Particularly, such measurements suffer from a combinatorial
explosion of operators, mobile plans, and services. To cope with these
challenges, we built a framework that geographically decouples the SIM from the
cellular modem by selectively connecting both remotely. This allows testing any
subscriber with any operator at any modem location within minutes without
moving parts. The resulting GSM/UMTS/LTE measurement and testbed platform
offers a controlled experimentation environment, which is scalable and
cost-effective. The platform is extensible and fully open-sourced, allowing
other researchers to contribute locations, SIM cards, and measurement scripts.
  Using the above framework, our international experiments in commercial
networks revealed exploitable inconsistencies in traffic metering, leading to
multiple phreaking opportunities, i.e., fare-dodging. We also expose
problematic IPv6 firewall configurations, hidden SIM card communication to the
home network, and fingerprint dial progress tones to track victims across
different roaming networks and countries with voice calls.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.08181v1">Differential Privacy in Nonlinear Dynamical Systems with Tracking
  Performance Guarantees</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36"> 
  <p><b>Published on:</b> 2024-03-13T02:10:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dhrubajit Chowdhury, Raman Goyal, Shantanu Rane</p>
    <p><b>Summary:</b> We introduce a novel approach to make the tracking error of a class of
nonlinear systems differentially private in addition to guaranteeing the
tracking error performance. We use funnel control to make the tracking error
evolve within a performance funnel that is pre-specified by the user. We make
the performance funnel differentially private by adding a bounded continuous
noise generated from an Ornstein-Uhlenbeck-type process. Since the funnel
controller is a function of the performance funnel, the noise adds randomized
perturbation to the control input. We show that, as a consequence of the
differential privacy of the performance funnel, the tracking error is also
differentially private. As a result, the tracking error is bounded by the noisy
funnel boundary while maintaining privacy. We show a simulation result to
demonstrate the framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.08115v1">Legally Binding but Unfair? Towards Assessing Fairness of Privacy
  Policies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> 
  <p><b>Published on:</b> 2024-03-12T22:53:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vincent Freiberger, Erik Buchmann</p>
    <p><b>Summary:</b> Privacy policies are expected to inform data subjects about their data
protection rights. They should explain the data controller's data management
practices, and make facts such as retention periods or data transfers to third
parties transparent. Privacy policies only fulfill their purpose, if they are
correctly perceived, interpreted, understood, and trusted by the data subject.
Amongst others, this requires that a privacy policy is written in a fair way,
e.g., it does not use polarizing terms, does not require a certain education,
or does not assume a particular social background. In this work-in-progress
paper, we outline our approach to assessing fairness in privacy policies. To
this end, we identify from fundamental legal sources and fairness research, how
the dimensions informational fairness, representational fairness and
ethics/morality are related to privacy policies. We propose options to
automatically assess policies in these fairness dimensions, based on text
statistics, linguistic methods and artificial intelligence. Finally, we conduct
initial experiments with German privacy policies to provide evidence that our
approach is applicable. Our experiments indicate that there are indeed issues
in all three dimensions of fairness. For example, our approach finds out if a
policy discriminates against individuals with impaired reading skills or
certain demographics, and identifies questionable ethics. This is important, as
future privacy policies may be used in a corpus for legal artificial
intelligence models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.07842v1">Quantifying and Mitigating Privacy Risks for Tabular Generative Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-03-12T17:27:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chaoyi Zhu, Jiayi Tang, Hans Brouwer, Juan F. Pérez, Marten van Dijk, Lydia Y. Chen</p>
    <p><b>Summary:</b> Synthetic data from generative models emerges as the privacy-preserving
data-sharing solution. Such a synthetic data set shall resemble the original
data without revealing identifiable private information. The backbone
technology of tabular synthesizers is rooted in image generative models,
ranging from Generative Adversarial Networks (GANs) to recent diffusion models.
Recent prior work sheds light on the utility-privacy tradeoff on tabular data,
revealing and quantifying privacy risks on synthetic data. We first conduct an
exhaustive empirical analysis, highlighting the utility-privacy tradeoff of
five state-of-the-art tabular synthesizers, against eight privacy attacks, with
a special focus on membership inference attacks. Motivated by the observation
of high data quality but also high privacy risk in tabular diffusion, we
propose DP-TLDM, Differentially Private Tabular Latent Diffusion Model, which
is composed of an autoencoder network to encode the tabular data and a latent
diffusion model to synthesize the latent tables. Following the emerging f-DP
framework, we apply DP-SGD to train the auto-encoder in combination with batch
clipping and use the separation value as the privacy metric to better capture
the privacy gain from DP algorithms. Our empirical evaluation demonstrates that
DP-TLDM is capable of achieving a meaningful theoretical privacy guarantee
while also significantly enhancing the utility of synthetic data. Specifically,
compared to other DP-protected tabular generative models, DP-TLDM improves the
synthetic quality by an average of 35% in data resemblance, 15% in the utility
for downstream tasks, and 50% in data discriminability, all while preserving a
comparable level of privacy risk.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.07838v1">MPCPA: Multi-Center Privacy Computing with Predictions Aggregation based
  on Denoising Diffusion Probabilistic Model</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-03-12T17:21:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guibo Luo, Hanwen Zhang, Xiuling Wang, Mingzhi Chen, Yuesheng Zhu</p>
    <p><b>Summary:</b> Privacy-preserving computing is crucial for multi-center machine learning in
many applications such as healthcare and finance. In this paper a Multi-center
Privacy Computing framework with Predictions Aggregation (MPCPA) based on
denoising diffusion probabilistic model (DDPM) is proposed, in which
conditional diffusion model training, DDPM data generation, a classifier, and
strategy of prediction aggregation are included. Compared to federated
learning, this framework necessitates fewer communications and leverages
high-quality generated data to support robust privacy computing. Experimental
validation across multiple datasets demonstrates that the proposed framework
outperforms classic federated learning and approaches the performance of
centralized learning with original data. Moreover, our approach demonstrates
robust security, effectively addressing challenges such as image memorization
and membership inference attacks. Our experiments underscore the efficacy of
the proposed framework in the realm of privacy computing, with the code set to
be released soon.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.07817v1">UniHand: Privacy-preserving Universal Handover for Small-Cell Networks
  in 5G-enabled Mobile Communication with KCI Resilience</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-03-12T16:56:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rabiah Alnashwan, Prosanta Gope, Benjamin Dowling</p>
    <p><b>Summary:</b> Introducing Small Cell Networks (SCN) has significantly improved wireless
link quality, spectrum efficiency and network capacity, which has been viewed
as one of the key technologies in the fifth-generation (5G) mobile network.
However, this technology increases the frequency of handover (HO) procedures
caused by the dense deployment of cells in the network with reduced cell
coverage, bringing new security and privacy issues. The current 5G-AKA and HO
protocols are vulnerable to security weaknesses, such as the lack of forward
secrecy and identity confusion attacks. The high HO frequency of HOs might
magnify these security and privacy concerns in the 5G mobile network. This work
addresses these issues by proposing a secure privacy-preserving universal HO
scheme ($\UniHand$) for SCNs in 5G mobile communication. $\UniHand$ can achieve
mutual authentication, strong anonymity, perfect forward secrecy,
key-escrow-free and key compromise impersonation (KCI) resilience. To the best
of our knowledge, this is the \textit{first} scheme to achieve secure,
privacy-preserving universal HO with \textit{KCI} resilience for roaming users
in 5G environment. We demonstrate that our proposed scheme is resilient against
all the essential security threats by performing a comprehensive formal
security analysis and conducting relevant experiments to show the
cost-effectiveness of the proposed scheme.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.07772v1">Privacy Guarantees in Posterior Sampling under Contamination</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">  
  <p><b>Published on:</b> 2024-03-12T15:58:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shenggang Hu, Louis Aslett, Hongsheng Dai, Murray Pollock, Gareth O. Roberts</p>
    <p><b>Summary:</b> In recent years, differential privacy has been adopted by tech-companies and
governmental agencies as the standard for measuring privacy in algorithms. We
study the level of differential privacy in Bayesian posterior sampling setups.
As opposed to the common privatization approach of injecting Laplace/Gaussian
noise into the output, Huber's contamination model is considered, where we
replace at random the data points with samples from a heavy-tailed
distribution. We derived bounds for the differential privacy level
$(\epsilon,\delta)$ for our approach while lifting the common restriction on
assuming bounded observation and parameter space seen in the existing
literature. We further consider the effect of sample size on privacy level and
the convergence rate of $(\epsilon,\delta)$ to zero. Asymptotically, the
contamination approach is fully private at no cost of information loss. We also
provide some examples depicting inference models that our setup is applicable
to with a theoretical estimation of convergence rate.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.07588v1">Visual Privacy Auditing with Diffusion Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-03-12T12:18:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kristian Schwethelm, Johannes Kaiser, Moritz Knolle, Daniel Rueckert, Georgios Kaissis, Alexander Ziller</p>
    <p><b>Summary:</b> Image reconstruction attacks on machine learning models pose a significant
risk to privacy by potentially leaking sensitive information. Although
defending against such attacks using differential privacy (DP) has proven
effective, determining appropriate DP parameters remains challenging. Current
formal guarantees on data reconstruction success suffer from overly theoretical
assumptions regarding adversary knowledge about the target data, particularly
in the image domain. In this work, we empirically investigate this discrepancy
and find that the practicality of these assumptions strongly depends on the
domain shift between the data prior and the reconstruction target. We propose a
reconstruction attack based on diffusion models (DMs) that assumes adversary
access to real-world image priors and assess its implications on privacy
leakage under DP-SGD. We show that (1) real-world data priors significantly
influence reconstruction success, (2) current reconstruction bounds do not
model the risk posed by data priors well, and (3) DMs can serve as effective
auditing tools for visualizing privacy leakage.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.07506v1">Robustness, Security, Privacy, Explainability, Efficiency, and Usability
  of Large Language Models for Code</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2024-03-12T10:43:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhou Yang, Zhensu Sun, Terry Zhuo Yue, Premkumar Devanbu, David Lo</p>
    <p><b>Summary:</b> Large language models for code (LLM4Code), which demonstrate strong
performance (e.g., high accuracy) in processing source code, have significantly
transformed software engineering. Many studies separately investigate the
non-functional properties of LM4Code, but there is no systematic review of how
these properties are evaluated and enhanced. This paper fills this gap by
thoroughly examining 146 relevant studies, thereby presenting the first
systematic literature review to identify seven important properties beyond
accuracy, including robustness, security, privacy, explainability, efficiency,
and usability. We discuss the current state-of-the-art methods and trends,
identify gaps in existing research, and present promising directions for future
study.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.07288v1">Efficient and Model-Agnostic Parameter Estimation Under
  Privacy-Preserving Post-randomization Data</a></h3>
  
  <p><b>Published on:</b> 2024-03-12T03:41:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qinglong Tian, Jiwei Zhao</p>
    <p><b>Summary:</b> Protecting individual privacy is crucial when releasing sensitive data for
public use. While data de-identification helps, it is not enough. This paper
addresses parameter estimation in scenarios where data are perturbed using the
Post-Randomization Method (PRAM) to enhance privacy. Existing methods for
parameter estimation under PRAM data suffer from limitations like being
parameter-specific, model-dependent, and lacking efficiency guarantees. We
propose a novel, efficient method that overcomes these limitations. Our method
is applicable to general parameters defined through estimating equations and
makes no assumptions about the underlying data model. We further prove that the
proposed estimator achieves the semiparametric efficiency bound, making it
optimal in terms of asymptotic variance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.07218v1">SoK: Can Trajectory Generation Combine Privacy and Utility?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-03-12T00:25:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Erik Buchholz, Alsharif Abuadbba, Shuo Wang, Surya Nepal, Salil S. Kanhere</p>
    <p><b>Summary:</b> While location trajectories represent a valuable data source for analyses and
location-based services, they can reveal sensitive information, such as
political and religious preferences. Differentially private publication
mechanisms have been proposed to allow for analyses under rigorous privacy
guarantees. However, the traditional protection schemes suffer from a limiting
privacy-utility trade-off and are vulnerable to correlation and reconstruction
attacks. Synthetic trajectory data generation and release represent a promising
alternative to protection algorithms. While initial proposals achieve
remarkable utility, they fail to provide rigorous privacy guarantees. This
paper proposes a framework for designing a privacy-preserving trajectory
publication approach by defining five design goals, particularly stressing the
importance of choosing an appropriate Unit of Privacy. Based on this framework,
we briefly discuss the existing trajectory protection approaches, emphasising
their shortcomings. This work focuses on the systematisation of the
state-of-the-art generative models for trajectories in the context of the
proposed framework. We find that no existing solution satisfies all
requirements. Thus, we perform an experimental study evaluating the
applicability of six sequential generative models to the trajectory domain.
Finally, we conclude that a generative trajectory model providing semantic
guarantees remains an open research question and propose concrete next steps
for future research.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.06672v1">Provable Mutual Benefits from Federated Learning in Privacy-Sensitive
  Domains</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-03-11T12:43:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nikita Tsoy, Anna Mihalkova, Teodora Todorova, Nikola Konstantinov</p>
    <p><b>Summary:</b> Cross-silo federated learning (FL) allows data owners to train accurate
machine learning models by benefiting from each others private datasets.
Unfortunately, the model accuracy benefits of collaboration are often
undermined by privacy defenses. Therefore, to incentivize client participation
in privacy-sensitive domains, a FL protocol should strike a delicate balance
between privacy guarantees and end-model accuracy. In this paper, we study the
question of when and how a server could design a FL protocol provably
beneficial for all participants. First, we provide necessary and sufficient
conditions for the existence of mutually beneficial protocols in the context of
mean estimation and convex stochastic optimization. We also derive protocols
that maximize the total clients' utility, given symmetric privacy preferences.
Finally, we design protocols maximizing end-model accuracy and demonstrate
their benefits in synthetic experiments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.06172v1">Understanding Parents' Perceptions and Practices Toward Children's
  Security and Privacy in Virtual Reality</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-03-10T10:54:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiaxun Cao, Abhinaya S B, Anupam Das, Pardis Emami-Naeini</p>
    <p><b>Summary:</b> Recent years have seen a sharp increase in underage users of virtual reality
(VR), where security and privacy (S\&P) risks such as data surveillance and
self-disclosure in social interaction have been increasingly prominent. Prior
work shows children largely rely on parents to mitigate S\&P risks in their
technology use. Therefore, understanding parents' S\&P knowledge, perceptions,
and practices is critical for identifying the gaps for parents, technology
designers, and policymakers to enhance children's S\&P. While such empirical
knowledge is substantial in other consumer technologies, it remains largely
unknown in the context of VR. To address the gap, we conducted in-depth
semi-structured interviews with 20 parents of children under the age of 18 who
use VR at home. Our findings highlight parents generally lack S\&P awareness
due to the perception that VR is still in its infancy. To protect their
children's interaction with VR, parents currently primarily rely on active
strategies such as verbal education about S\&P. Passive strategies such as
parental controls in VR are not commonly used among our interviewees, mainly
due to their perceived technical constraints. Parents also highlight that a
multi-stakeholder ecosystem must be established towards more S\&P support for
children in VR. Based on the findings, we propose actionable S\&P
recommendations for critical stakeholders, including parents, educators, VR
companies, and governments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.06131v1">FedPIT: Towards Privacy-preserving and Few-shot Federated Instruction
  Tuning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-03-10T08:41:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhuo Zhang, Jingyuan Zhang, Jintao Huang, Lizhen Qu, Hongzhi Zhang, Zenglin Xu</p>
    <p><b>Summary:</b> Instruction tuning has proven essential for enhancing the performance of
large language models (LLMs) in generating human-aligned responses. However,
collecting diverse, high-quality instruction data for tuning poses challenges,
particularly in privacy-sensitive domains. Federated instruction tuning (FedIT)
has emerged as a solution, leveraging federated learning from multiple data
owners while preserving privacy. Yet, it faces challenges due to limited
instruction data and vulnerabilities to training data extraction attacks. To
address these issues, we propose a novel federated algorithm, FedPIT, which
utilizes LLMs' in-context learning capability to self-generate task-specific
synthetic data for training autonomously. Our method employs parameter-isolated
training to maintain global parameters trained on synthetic data and local
parameters trained on augmented local data, effectively thwarting data
extraction attacks. Extensive experiments on real-world medical data
demonstrate the effectiveness of FedPIT in improving federated few-shot
performance while preserving privacy and robustness against data heterogeneity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.05864v1">PAPER-HILT: Personalized and Adaptive Privacy-Aware Early-Exit for
  Reinforcement Learning in Human-in-the-Loop Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">  
  <p><b>Published on:</b> 2024-03-09T10:24:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mojtaba Taherisadr, Salma Elmalaki</p>
    <p><b>Summary:</b> Reinforcement Learning (RL) has increasingly become a preferred method over
traditional rule-based systems in diverse human-in-the-loop (HITL) applications
due to its adaptability to the dynamic nature of human interactions. However,
integrating RL in such settings raises significant privacy concerns, as it
might inadvertently expose sensitive user information. Addressing this, our
paper focuses on developing PAPER-HILT, an innovative, adaptive RL strategy
through exploiting an early-exit approach designed explicitly for privacy
preservation in HITL environments. This approach dynamically adjusts the
tradeoff between privacy protection and system utility, tailoring its operation
to individual behavioral patterns and preferences. We mainly highlight the
challenge of dealing with the variable and evolving nature of human behavior,
which renders static privacy models ineffective. PAPER-HILT's effectiveness is
evaluated through its application in two distinct contexts: Smart Home
environments and Virtual Reality (VR) Smart Classrooms. The empirical results
demonstrate PAPER-HILT's capability to provide a personalized equilibrium
between user privacy and application utility, adapting effectively to
individual user needs and preferences. On average for both experiments, utility
(performance) drops by 24%, and privacy (state prediction) improves by 31%.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.05794v1">Privacy-Preserving Diffusion Model Using Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-03-09T04:56:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yaojian Chen, Qiben Yan</p>
    <p><b>Summary:</b> In this paper, we introduce a privacy-preserving stable diffusion framework
leveraging homomorphic encryption, called HE-Diffusion, which primarily focuses
on protecting the denoising phase of the diffusion process. HE-Diffusion is a
tailored encryption framework specifically designed to align with the unique
architecture of stable diffusion, ensuring both privacy and functionality. To
address the inherent computational challenges, we propose a novel
min-distortion method that enables efficient partial image encryption,
significantly reducing the overhead without compromising the model's output
quality. Furthermore, we adopt a sparse tensor representation to expedite
computational operations, enhancing the overall efficiency of the
privacy-preserving diffusion process. We successfully implement HE-based
privacy-preserving stable diffusion inference. The experimental results show
that HE-Diffusion achieves 500 times speedup compared with the baseline method,
and reduces time cost of the homomorphically encrypted inference to the minute
level. Both the performance and accuracy of the HE-Diffusion are on par with
the plaintext counterpart. Our approach marks a significant step towards
integrating advanced cryptographic techniques with state-of-the-art generative
models, paving the way for privacy-preserving and efficient image generation in
critical applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.05692v2">Privacy-Preserving Sharing of Data Analytics Runtime Metrics for
  Performance Modeling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-03-08T22:03:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jonathan Will, Dominik Scheinert, Jan Bode, Cedric Kring, Seraphin Zunzer, Lauritz Thamsen</p>
    <p><b>Summary:</b> Performance modeling for large-scale data analytics workloads can improve the
efficiency of cluster resource allocations and job scheduling. However, the
performance of these workloads is influenced by numerous factors, such as job
inputs and the assigned cluster resources. As a result, performance models
require significant amounts of training data. This data can be obtained by
exchanging runtime metrics between collaborating organizations. Yet, not all
organizations may be inclined to publicly disclose such metadata.
  We present a privacy-preserving approach for sharing runtime metrics based on
differential privacy and data synthesis. Our evaluation on performance data
from 736 Spark job executions indicates that fully anonymized training data
largely maintains performance prediction accuracy, particularly when there is
minimal original data available. With 30 or fewer available original data
samples, the use of synthetic training data resulted only in a one percent
reduction in performance model accuracy on average.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.05344v1">Federated Learning Method for Preserving Privacy in Face Recognition
  System</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-03-08T14:21:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Enoch Solomon, Abraham Woubie</p>
    <p><b>Summary:</b> The state-of-the-art face recognition systems are typically trained on a
single computer, utilizing extensive image datasets collected from various
number of users. However, these datasets often contain sensitive personal
information that users may hesitate to disclose. To address potential privacy
concerns, we explore the application of federated learning, both with and
without secure aggregators, in the context of both supervised and unsupervised
face recognition systems. Federated learning facilitates the training of a
shared model without necessitating the sharing of individual private data,
achieving this by training models on decentralized edge devices housing the
data. In our proposed system, each edge device independently trains its own
model, which is subsequently transmitted either to a secure aggregator or
directly to the central server. To introduce diverse data without the need for
data transmission, we employ generative adversarial networks to generate
imposter data at the edge. Following this, the secure aggregator or central
server combines these individual models to construct a global model, which is
then relayed back to the edge devices. Experimental findings based on the
CelebA datasets reveal that employing federated learning in both supervised and
unsupervised face recognition systems offers dual benefits. Firstly, it
safeguards privacy since the original data remains on the edge devices.
Secondly, the experimental results demonstrate that the aggregated model yields
nearly identical performance compared to the individual models, particularly
when the federated model does not utilize a secure aggregator. Hence, our
results shed light on the practical challenges associated with
privacy-preserving face image training, particularly in terms of the balance
between privacy and accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.05275v1">vSPACE: Voting in a Scalable, Privacy-Aware and Confidential Election</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-03-08T12:56:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Se Elnour, William J Buchanan, Paul Keating, Mwrwan Abubakar, Sirag Elnour</p>
    <p><b>Summary:</b> The vSPACE experimental proof-of-concept (PoC) on the TrueElect[Anon][Creds]
protocol presents a novel approach to secure, private, and scalable elections,
extending the TrueElect and ElectAnon protocols with the integration of
AnonCreds SSI (Self-Sovereign Identity). Such a protocol PoC is situated within
a Zero-Trust Architecture (ZTA) and leverages confidential computing,
continuous authentication, multi-party computation (MPC), and well-architected
framework (WAF) principles to address the challenges of cybersecurity, privacy,
and trust over IP (ToIP) protection. Employing a Kubernetes confidential
cluster within an Enterprise-Scale Landing Zone (ESLZ), vSPACE integrates
Distributed Ledger Technology (DLT) for immutable and certifiable audit trails.
The Infrastructure as Code (IaC) model ensures rapid deployment, consistent
management, and adherence to security standards, making vSPACE a future-proof
solution for digital voting systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.05271v2">DID:RING: Ring Signatures using Decentralised Identifiers For
  Privacy-Aware Identity</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-03-08T12:49:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dimitrios Kasimatis, Sam Grierson, William J. Buchanan, Chris Eckl, Pavlos Papadopoulos, Nikolaos Pitropakis, Craig Thomson, Baraq Ghaleb</p>
    <p><b>Summary:</b> Decentralised identifiers have become a standardised element of digital
identity architecture, with supra-national organisations such as the European
Union adopting them as a key component for a unified European digital identity
ledger. This paper delves into enhancing security and privacy features within
decentralised identifiers by integrating ring signatures as an alternative
verification method. This allows users to identify themselves through digital
signatures without revealing which public key they used. To this end, the study
proposed a novel decentralised identity method showcased in a decentralised
identifier-based architectural framework. Additionally, the investigation
assesses the repercussions of employing this new method in the verification
process, focusing specifically on privacy and security aspects. Although ring
signatures are an established asset of cryptographic protocols, this paper
seeks to leverage their capabilities in the evolving domain of digital
identities.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.05156v2">On Protecting the Data Privacy of Large Language Models (LLMs): A Survey</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-03-08T08:47:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Biwei Yan, Kun Li, Minghui Xu, Yueyan Dong, Yue Zhang, Zhaochun Ren, Xiuzhen Cheng</p>
    <p><b>Summary:</b> Large language models (LLMs) are complex artificial intelligence systems
capable of understanding, generating and translating human language. They learn
language patterns by analyzing large amounts of text data, allowing them to
perform writing, conversation, summarizing and other language tasks. When LLMs
process and generate large amounts of data, there is a risk of leaking
sensitive information, which may threaten data privacy. This paper concentrates
on elucidating the data privacy concerns associated with LLMs to foster a
comprehensive understanding. Specifically, a thorough investigation is
undertaken to delineate the spectrum of data privacy threats, encompassing both
passive privacy leakage and active privacy attacks within LLMs. Subsequently,
we conduct an assessment of the privacy protection mechanisms employed by LLMs
at various stages, followed by a detailed examination of their efficacy and
constraints. Finally, the discourse extends to delineate the challenges
encountered and outline prospective directions for advancement in the realm of
LLM privacy protection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.05114v1">APPLE: Adversarial Privacy-aware Perturbations on Latent Embedding for
  Unfairness Mitigation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-03-08T07:22:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zikang Xu, Fenghe Tang, Quan Quan, Qingsong Yao, S. Kevin Zhou</p>
    <p><b>Summary:</b> Ensuring fairness in deep-learning-based segmentors is crucial for health
equity. Much effort has been dedicated to mitigating unfairness in the training
datasets or procedures. However, with the increasing prevalence of foundation
models in medical image analysis, it is hard to train fair models from scratch
while preserving utility. In this paper, we propose a novel method, Adversarial
Privacy-aware Perturbations on Latent Embedding (APPLE), that can improve the
fairness of deployed segmentors by introducing a small latent feature perturber
without updating the weights of the original model. By adding perturbation to
the latent vector, APPLE decorates the latent vector of segmentors such that no
fairness-related features can be passed to the decoder of the segmentors while
preserving the architecture and parameters of the segmentor. Experiments on two
segmentation datasets and five segmentors (three U-Net-like and two SAM-like)
illustrate the effectiveness of our proposed method compared to several
unfairness mitigation methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.05598v1">Privacy Amplification for the Gaussian Mechanism via Bounded Support</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-03-07T21:22:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shengyuan Hu, Saeed Mahloujifar, Virginia Smith, Kamalika Chaudhuri, Chuan Guo</p>
    <p><b>Summary:</b> Data-dependent privacy accounting frameworks such as per-instance
differential privacy (pDP) and Fisher information loss (FIL) confer
fine-grained privacy guarantees for individuals in a fixed training dataset.
These guarantees can be desirable compared to vanilla DP in real world settings
as they tightly upper-bound the privacy leakage for a $\textit{specific}$
individual in an $\textit{actual}$ dataset, rather than considering worst-case
datasets. While these frameworks are beginning to gain popularity, to date,
there is a lack of private mechanisms that can fully leverage advantages of
data-dependent accounting. To bridge this gap, we propose simple modifications
of the Gaussian mechanism with bounded support, showing that they amplify
privacy guarantees under data-dependent accounting. Experiments on model
training with DP-SGD show that using bounded support Gaussian mechanisms can
provide a reduction of the pDP bound $\epsilon$ by as much as 30% without
negative effects on model utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.04867v1">Group Privacy Amplification and Unified Amplification by Subsampling for
  Rényi Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2024-03-07T19:36:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jan Schuchardt, Mihail Stoian, Arthur Kosmala, Stephan Günnemann</p>
    <p><b>Summary:</b> Differential privacy (DP) has various desirable properties, such as
robustness to post-processing, group privacy, and amplification by subsampling,
which can be derived independently of each other. Our goal is to determine
whether stronger privacy guarantees can be obtained by considering multiple of
these properties jointly. To this end, we focus on the combination of group
privacy and amplification by subsampling. To provide guarantees that are
amenable to machine learning algorithms, we conduct our analysis in the
framework of R\'enyi-DP, which has more favorable composition properties than
$(\epsilon,\delta)$-DP. As part of this analysis, we develop a unified
framework for deriving amplification by subsampling guarantees for R\'enyi-DP,
which represents the first such framework for a privacy accounting method and
is of independent interest. We find that it not only lets us improve upon and
generalize existing amplification results for R\'enyi-DP, but also derive
provably tight group privacy amplification guarantees stronger than existing
principles. These results establish the joint study of different DP properties
as a promising research direction.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.04485v1">Privacy in Cloud Computing through Immersion-based Coding</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-03-07T13:38:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haleh Hayati, Nathan van de Wouw, Carlos Murguia</p>
    <p><b>Summary:</b> Cloud computing enables users to process and store data remotely on
high-performance computers and servers by sharing data over the Internet.
However, transferring data to clouds causes unavoidable privacy concerns. Here,
we present a synthesis framework to design coding mechanisms that allow sharing
and processing data in a privacy-preserving manner without sacrificing data
utility and algorithmic performance. We consider the setup where the user aims
to run an algorithm in the cloud using private data. The cloud then returns
some data utility back to the user (utility refers to the service that the
algorithm provides, e.g., classification, prediction, AI models, etc.). To
avoid privacy concerns, the proposed scheme provides tools to co-design: 1)
coding mechanisms to distort the original data and guarantee a prescribed
differential privacy level; 2) an equivalent-but-different algorithm (referred
here to as the target algorithm) that runs on distorted data and produces
distorted utility; and 3) a decoding function that extracts the true utility
from the distorted one with a negligible error. Then, instead of sharing the
original data and algorithm with the cloud, only the distorted data and target
algorithm are disclosed, thereby avoiding privacy concerns. The proposed scheme
is built on the synergy of differential privacy and system immersion tools from
control theory. The key underlying idea is to design a higher-dimensional
target algorithm that embeds all trajectories of the original algorithm and
works on randomly encoded data to produce randomly encoded utility. We show
that the proposed scheme can be designed to offer any level of differential
privacy without degrading the algorithm's utility. We present two use cases to
illustrate the performance of the developed tools: privacy in
optimization/learning algorithms and a nonlinear networked control system.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.04468v1">A Survey of Graph Neural Networks in Real world: Imbalance, Noise,
  Privacy and OOD Challenges</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B">
  <p><b>Published on:</b> 2024-03-07T13:10:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wei Ju, Siyu Yi, Yifan Wang, Zhiping Xiao, Zhengyang Mao, Hourun Li, Yiyang Gu, Yifang Qin, Nan Yin, Senzhang Wang, Xinwang Liu, Xiao Luo, Philip S. Yu, Ming Zhang</p>
    <p><b>Summary:</b> Graph-structured data exhibits universality and widespread applicability
across diverse domains, such as social network analysis, biochemistry,
financial fraud detection, and network security. Significant strides have been
made in leveraging Graph Neural Networks (GNNs) to achieve remarkable success
in these areas. However, in real-world scenarios, the training environment for
models is often far from ideal, leading to substantial performance degradation
of GNN models due to various unfavorable factors, including imbalance in data
distribution, the presence of noise in erroneous data, privacy protection of
sensitive information, and generalization capability for out-of-distribution
(OOD) scenarios. To tackle these issues, substantial efforts have been devoted
to improving the performance of GNN models in practical real-world scenarios,
as well as enhancing their reliability and robustness. In this paper, we
present a comprehensive survey that systematically reviews existing GNN models,
focusing on solutions to the four mentioned real-world challenges including
imbalance, noise, privacy, and OOD in practical scenarios that many existing
reviews have not considered. Specifically, we first highlight the four key
challenges faced by existing GNNs, paving the way for our exploration of
real-world GNN models. Subsequently, we provide detailed discussions on these
four aspects, dissecting how these solutions contribute to enhancing the
reliability and robustness of GNN models. Last but not least, we outline
promising directions and offer future perspectives in the field.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.04451v1">Membership Inference Attacks and Privacy in Topic Modeling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-03-07T12:43:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nico Manzonelli, Wanrong Zhang, Salil Vadhan</p>
    <p><b>Summary:</b> Recent research shows that large language models are susceptible to privacy
attacks that infer aspects of the training data. However, it is unclear if
simpler generative models, like topic models, share similar vulnerabilities. In
this work, we propose an attack against topic models that can confidently
identify members of the training data in Latent Dirichlet Allocation. Our
results suggest that the privacy risks associated with generative modeling are
not restricted to large neural models. Additionally, to mitigate these
vulnerabilities, we explore differentially private (DP) topic modeling. We
propose a framework for private topic modeling that incorporates DP vocabulary
selection as a pre-processing step, and show that it improves privacy while
having limited effects on practical utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.04124v1">Privacy-preserving Fine-tuning of Large Language Models through Flatness</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> 
  <p><b>Published on:</b> 2024-03-07T00:44:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tiejin Chen, Longchao Da, Huixue Zhou, Pingzhi Li, Kaixiong Zhou, Tianlong Chen, Hua Wei</p>
    <p><b>Summary:</b> The privacy concerns associated with the use of Large Language Models (LLMs)
have grown recently with the development of LLMs such as ChatGPT. Differential
Privacy (DP) techniques are explored in existing work to mitigate their privacy
risks at the cost of generalization degradation. Our paper reveals that the
flatness of DP-trained models' loss landscape plays an essential role in the
trade-off between their privacy and generalization. We further propose a
holistic framework to enforce appropriate weight flatness, which substantially
improves model generalization with competitive privacy preservation. It
innovates from three coarse-to-grained levels, including perturbation-aware
min-max optimization on model weights within a layer, flatness-guided sparse
prefix-tuning on weights across layers, and weight knowledge distillation
between DP \& non-DP weights copies. Comprehensive experiments of both
black-box and white-box scenarios are conducted to demonstrate the
effectiveness of our proposal in enhancing generalization and maintaining DP
characteristics. For instance, on text classification dataset QNLI, DP-Flat
achieves similar performance with non-private full fine-tuning but with DP
guarantee under privacy budget $\epsilon=3$, and even better performance given
higher privacy budgets. Codes are provided in the supplement.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.04024v1">Enhancing chest X-ray datasets with privacy-preserving large language
  models and multi-type annotations: a data-driven approach for improved
  classification</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-03-06T20:10:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ricardo Bigolin Lanfredi, Pritam Mukherjee, Ronald Summers</p>
    <p><b>Summary:</b> In chest X-ray (CXR) image analysis, rule-based systems are usually employed
to extract labels from reports, but concerns exist about label quality. These
datasets typically offer only presence labels, sometimes with binary
uncertainty indicators, which limits their usefulness. In this work, we present
MAPLEZ (Medical report Annotations with Privacy-preserving Large language model
using Expeditious Zero shot answers), a novel approach leveraging a locally
executable Large Language Model (LLM) to extract and enhance findings labels on
CXR reports. MAPLEZ extracts not only binary labels indicating the presence or
absence of a finding but also the location, severity, and radiologists'
uncertainty about the finding. Over eight abnormalities from five test sets, we
show that our method can extract these annotations with an increase of 5
percentage points (pp) in F1 score for categorical presence annotations and
more than 30 pp increase in F1 score for the location annotations over
competing labelers. Additionally, using these improved annotations in
classification supervision, we demonstrate substantial advancements in model
quality, with an increase of 1.7 pp in AUROC over models trained with
annotations from the state-of-the-art approach. We share code and annotations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.03612v1">Using the Dual-Privacy Framework to Understand Consumers' Perceived
  Privacy Violations Under Different Firm Practices in Online Advertising</a></h3>
   
  <p><b>Published on:</b> 2024-03-06T11:06:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kinshuk Jerath, Klaus M. Miller</p>
    <p><b>Summary:</b> In response to privacy concerns about collecting and using personal data, the
online advertising industry has been developing privacy-enhancing technologies
(PETs), e.g., under Google's Privacy Sandbox initiative. In this research, we
use the dual-privacy framework, which postulates that consumers have intrinsic
and instrumental preferences for privacy, to understand consumers' perceived
privacy violations (PPVs) for current and proposed online advertising
practices. The key idea is that different practices differ in whether
individual data leaves the consumer's machine or not and in how they track and
target consumers; these affect, respectively, the intrinsic and instrumental
components of privacy preferences differently, leading to different PPVs for
different practices. We conducted online studies focused on consumers in the
United States to elicit PPVs for various advertising practices. Our findings
confirm the intuition that tracking and targeting consumers under the industry
status quo of behavioral targeting leads to high PPV. New technologies or
proposals that ensure that data are kept on the consumer's machine lower PPV
relative to behavioral targeting but, importantly, this decrease is small.
Furthermore, group-level targeting does not differ significantly from
individual-level targeting in reducing PPV. Under contextual targeting, where
there is no tracking, PPV is significantly reduced. Interestingly, with respect
to PPV, consumers are indifferent between seeing untargeted ads and no ads when
they are not being tracked. We find that consumer perceptions of privacy
violations under different tracking and targeting practices may differ from
what technical definitions suggest. Therefore, rather than relying solely on
technical perspectives, a consumer-centric approach to privacy is needed, based
on, for instance, the dual-privacy framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.03610v1">Paying for Privacy: Pay-or-Tracking Walls</a></h3>
   
  <p><b>Published on:</b> 2024-03-06T10:59:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Timo Mueller-Tribbensee, Klaus M. Miller, Bernd Skiera</p>
    <p><b>Summary:</b> Prestigious news publishers, and more recently, Meta, have begun to request
that users pay for privacy. Specifically, users receive a notification banner,
referred to as a pay-or-tracking wall, that requires them to (i) pay money to
avoid being tracked or (ii) consent to being tracked. These walls have invited
concerns that privacy might become a luxury. However, little is known about
pay-or-tracking walls, which prevents a meaningful discussion about their
appropriateness. This paper conducts several empirical studies and finds that
top EU publishers use pay-or-tracking walls. Their implementations involve
various approaches, including bundling the pay option with advertising-free
access or additional content. The price for not being tracked exceeds the
advertising revenue that publishers generate from a user who consents to being
tracked. Notably, publishers' traffic does not decline when implementing a
pay-or-tracking wall and most users consent to being tracked; only a few users
pay. In short, pay-or-tracking walls seem to provide the means for expanding
the practice of tracking. Publishers profit from pay-or-tracking walls and may
observe a revenue increase of 16.4% due to tracking more users than under a
cookie consent banner.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.03600v1">A Privacy-Preserving Framework with Multi-Modal Data for Cross-Domain
  Recommendation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-03-06T10:40:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Li Wang, Lei Sang, Quangui Zhang, Qiang Wu, Min Xu</p>
    <p><b>Summary:</b> Cross-domain recommendation (CDR) aims to enhance recommendation accuracy in
a target domain with sparse data by leveraging rich information in a source
domain, thereby addressing the data-sparsity problem. Some existing CDR methods
highlight the advantages of extracting domain-common and domain-specific
features to learn comprehensive user and item representations. However, these
methods can't effectively disentangle these components as they often rely on
simple user-item historical interaction information (such as ratings, clicks,
and browsing), neglecting the rich multi-modal features. Additionally, they
don't protect user-sensitive data from potential leakage during knowledge
transfer between domains. To address these challenges, we propose a
Privacy-Preserving Framework with Multi-Modal Data for Cross-Domain
Recommendation, called P2M2-CDR. Specifically, we first design a multi-modal
disentangled encoder that utilizes multi-modal information to disentangle more
informative domain-common and domain-specific embeddings. Furthermore, we
introduce a privacy-preserving decoder to mitigate user privacy leakage during
knowledge transfer. Local differential privacy (LDP) is utilized to obfuscate
the disentangled embeddings before inter-domain exchange, thereby enhancing
privacy protection. To ensure both consistency and differentiation among these
obfuscated disentangled embeddings, we incorporate contrastive learning-based
domain-inter and domain-intra losses. Extensive Experiments conducted on four
real-world datasets demonstrate that P2M2-CDR outperforms other
state-of-the-art single-domain and cross-domain baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.03592v1">Wildest Dreams: Reproducible Research in Privacy-preserving Neural
  Network Training</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-03-06T10:25:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tanveer Khan, Mindaugas Budzys, Khoa Nguyen, Antonis Michalas</p>
    <p><b>Summary:</b> Machine Learning (ML), addresses a multitude of complex issues in multiple
disciplines, including social sciences, finance, and medical research. ML
models require substantial computing power and are only as powerful as the data
utilized. Due to high computational cost of ML methods, data scientists
frequently use Machine Learning-as-a-Service (MLaaS) to outsource computation
to external servers. However, when working with private information, like
financial data or health records, outsourcing the computation might result in
privacy issues. Recent advances in Privacy-Preserving Techniques (PPTs) have
enabled ML training and inference over protected data through the use of
Privacy-Preserving Machine Learning (PPML). However, these techniques are still
at a preliminary stage and their application in real-world situations is
demanding. In order to comprehend discrepancy between theoretical research
suggestions and actual applications, this work examines the past and present of
PPML, focusing on Homomorphic Encryption (HE) and Secure Multi-party
Computation (SMPC) applied to ML. This work primarily focuses on the ML model's
training phase, where maintaining user data privacy is of utmost importance. We
provide a solid theoretical background that eases the understanding of current
approaches and their limitations. In addition, we present a SoK of the most
recent PPML frameworks for model training and provide a comprehensive
comparison in terms of the unique properties and performances on standard
benchmarks. Also, we reproduce the results for some of the papers and examine
at what level existing works in the field provide support for open science. We
believe our work serves as a valuable contribution by raising awareness about
the current gap between theoretical advancements and real-world applications in
PPML, specifically regarding open-source availability, reproducibility, and
usability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.03337v1">Fine-Grained Privacy Guarantees for Coverage Problems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-03-05T21:40:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Laxman Dhulipala, George Z. Li</p>
    <p><b>Summary:</b> We introduce a new notion of neighboring databases for coverage problems such
as Max Cover and Set Cover under differential privacy. In contrast to the
standard privacy notion for these problems, which is analogous to node-privacy
in graphs, our new definition gives a more fine-grained privacy guarantee,
which is analogous to edge-privacy. We illustrate several scenarios of Set
Cover and Max Cover where our privacy notion is desired one for the
application.
  Our main result is an $\epsilon$-edge differentially private algorithm for
Max Cover which obtains an $(1-1/e-\eta,\tilde{O}(k/\epsilon))$-approximation
with high probability. Furthermore, we show that this result is nearly tight:
we give a lower bound show that an additive error of $\Omega(k/\epsilon)$ is
necessary under edge-differential privacy. Via group privacy properties, this
implies a new algorithm for $\epsilon$-node differentially private Max Cover
which obtains an $(1-1/e-\eta,\tilde{O}(fk/\epsilon))$-approximation, where $f$
is the maximum degree of an element in the set system. When $f\ll k$, this
improves over the best known algorithm for Max Cover under pure (node)
differential privacy, which obtains an
$(1-1/e,\tilde{O}(k^2/\epsilon))$-approximation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.03126v1">A Federated Deep Learning Approach for Privacy-Preserving Real-Time
  Transient Stability Predictions in Power Systems</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2024-03-05T17:12:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maeshal Hijazi, Payman Dehghanian</p>
    <p><b>Summary:</b> Maintaining the privacy of power system data is essential for protecting
sensitive information and ensuring the operation security of critical
infrastructure. Therefore, the adoption of centralized deep learning (DL)
transient stability assessment (TSA) frameworks can introduce risks to electric
utilities. This is because these frameworks make utility data susceptible to
cyber threats and communication issues when transmitting data to a central
server for training a single TSA model. Additionally, the centralized approach
demands significant computational resources, which may not always be readily
available. In light of these challenges, this paper introduces a federated
DL-based TSA framework designed to identify the operating states of the power
system. Instead of local utilities transmitting their data to a central server
for centralized model training, they independently train their own TSA models
using their respective datasets. Subsequently, the parameters of each local TSA
model are sent to a central server for model aggregation, and the resulting
model is shared back with the local clients. This approach not only preserves
the integrity of local utility data, making it resilient against cyber threats
but also reduces the computational demands for local TSA model training. The
proposed approach is tested on four local clients each having the IEEE 39-bus
test system.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.03048v1">Design of Stochastic Quantizers for Privacy Preservation</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2024-03-05T15:31:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Le Liu, Yu Kawano, Ming Cao</p>
    <p><b>Summary:</b> In this paper, we examine the role of stochastic quantizers for privacy
preservation. We first employ a static stochastic quantizer and investigate its
corresponding privacy-preserving properties. Specifically, we demonstrate that
a sufficiently large quantization step guarantees $(0, \delta)$ differential
privacy. Additionally, the degradation of control performance caused by
quantization is evaluated as the tracking error of output regulation. These two
analyses characterize the trade-off between privacy and control performance,
determined by the quantization step. This insight enables us to use
quantization intentionally as a means to achieve the seemingly conflicting two
goals of maintaining control performance and preserving privacy at the same
time; towards this end, we further investigate a dynamic stochastic quantizer.
Under a stability assumption, the dynamic stochastic quantizer can enhance
privacy, more than the static one, while achieving the same control
performance. We further handle the unstable case by additionally applying input
Gaussian noise.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2403.02694v1">Privacy-Aware Semantic Cache for Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> 
  <p><b>Published on:</b> 2024-03-05T06:23:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Waris Gill, Mohamed Elidrisi, Pallavi Kalapatapu, Ali Anwar, Muhammad Ali Gulzar</p>
    <p><b>Summary:</b> Large Language Models (LLMs) like ChatGPT, Google Bard, Claude, and Llama 2
have revolutionized natural language processing and search engine dynamics.
However, these models incur exceptionally high computational costs. For
instance, GPT-3 consists of 175 billion parameters and inference on these
models also demands billions of floating-point operations. Caching is a natural
solution to reduce LLM inference costs on repeated queries. However, existing
caching methods are incapable of finding semantic similarities among LLM
queries, leading to unacceptable false hit-and-miss rates.
  This paper introduces MeanCache, a semantic cache for LLMs that identifies
semantically similar queries to determine cache hit or miss. Using MeanCache,
the response to a user's semantically similar query can be retrieved from a
local cache rather than re-querying the LLM, thus reducing costs, service
provider load, and environmental impact. MeanCache leverages Federated Learning
(FL) to collaboratively train a query similarity model in a distributed manner
across numerous users without violating privacy. By placing a local cache in
each user's device and using FL, MeanCache reduces the latency and costs and
enhances model performance, resulting in lower cache false hit rates. Our
experiments, benchmarked against the GPTCache, reveal that MeanCache attains an
approximately 17% higher F-score and a 20% increase in precision during
semantic cache hit-and-miss decisions. Furthermore, MeanCache reduces the
storage requirement by 83% and accelerates semantic cache hit-and-miss
decisions by 11%, while still surpassing GPTCache.</p>
  </details>
</div>

