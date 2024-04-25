
<h2>2024-04</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.14983v1">Zero-Knowledge Location Privacy via Accurate Floating Point SNARKs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-04-23T12:38:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jens Ernstberger, Chengru Zhang, Luca Ciprian, Philipp Jovanovic, Sebastian Steinhorst</p>
    <p><b>Summary:</b> This paper introduces Zero-Knowledge Location Privacy (ZKLP), enabling users
to prove to third parties that they are within a specified geographical region
while not disclosing their exact location. ZKLP supports varying levels of
granularity, allowing for customization depending on the use case. To realize
ZKLP, we introduce the first set of Zero-Knowledge Proof (ZKP) circuits that
are fully compliant to the IEEE 754 standard for floating-point arithmetic.
  Our results demonstrate that our floating point implementation scales
efficiently, requiring only $69$ constraints per multiplication for $2^{15}$
single-precision floating-point multiplications. We utilize our floating point
implementation to realize the ZKLP paradigm. In comparison to the
state-of-the-art, we find that our optimized implementation has $14.1 \times$
less constraints utilizing single precision floating-point values, and $11.2
\times$ less constraints when utilizing double precision floating-point values.
We demonstrate the practicability of ZKLP by building a protocol for privacy
preserving peer-to-peer proximity testing - Alice can test if she is close to
Bob by receiving a single message, without either party revealing any other
information about their location. In such a configuration, Bob can create a
proof of (non-)proximity in $0.27 s$, whereas Alice can verify her distance to
about $250$ peers per second</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.14895v1">Bayesian Approaches to Collaborative Data Analysis with Strict Privacy
  Restrictions</a></h3>
   
  <p><b>Published on:</b> 2024-04-23T10:22:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Simon Busch-Moreno, Moritz U. G. Kraemer</p>
    <p><b>Summary:</b> Collaborative data analysis between countries is crucial for enabling fast
responses to increasingly multi-country disease outbreaks. Often, data early in
outbreaks are of sensitive nature and subject to strict privacy restrictions.
Thus, federated analysis, which implies decentralised collaborative analysis
where no raw data sharing is required, emerged as a novel approach solving
issues around data privacy and confidentiality. In the present study, we
propose two approaches to federated analysis, based on simple Bayesian
statistics and exploit this simplicity to make them feasible for rapid
collaboration without the risks of data leaks and data reidentification, as
they require neither data sharing nor direct communication between devices. The
first approach uses summaries from parameters' posteriors previously obtained
at a different location to update truncated normal distributions approximating
priors of a new model. The second approach uses the entire previously sampled
posterior, approximating via a multivariate normal distribution. We test these
models on simulated and on real outbreak data to estimate the incubation period
of infectious diseases. Results indicate that both approaches can recover
incubation period parameters accurately, but they differ in terms of
inferential capacity. The posterior summary approach shows higher stability and
precision, but it cannot capture posterior correlations, meaning it is
inferentially limited. The whole posterior approach can capture correlations,
but it shows less stability, and its applicability is limited to fewer prior
distributions. We discuss results in terms of the advantages of their
simplicity and privacy-preserving properties, and in terms of their limited
generalisability to more complex analytical models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.14693v1">Double Privacy Guard: Robust Traceable Adversarial Watermarking against
  Face Recognition</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> 
  <p><b>Published on:</b> 2024-04-23T02:50:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yunming Zhang, Dengpan Ye, Sipeng Shen, Caiyun Xie, Ziyi Liu, Jiacheng Deng, Long Tang</p>
    <p><b>Summary:</b> The wide deployment of Face Recognition (FR) systems poses risks of privacy
leakage. One countermeasure to address this issue is adversarial attacks, which
deceive malicious FR searches but simultaneously interfere the normal identity
verification of trusted authorizers. In this paper, we propose the first Double
Privacy Guard (DPG) scheme based on traceable adversarial watermarking. DPG
employs a one-time watermark embedding to deceive unauthorized FR models and
allows authorizers to perform identity verification by extracting the
watermark. Specifically, we propose an information-guided adversarial attack
against FR models. The encoder embeds an identity-specific watermark into the
deep feature space of the carrier, guiding recognizable features of the image
to deviate from the source identity. We further adopt a collaborative
meta-optimization strategy compatible with sub-tasks, which regularizes the
joint optimization direction of the encoder and decoder. This strategy enhances
the representation of universal carrier features, mitigating multi-objective
optimization conflicts in watermarking. Experiments confirm that DPG achieves
significant attack success rates and traceability accuracy on state-of-the-art
FR models, exhibiting remarkable robustness that outperforms the existing
privacy protection methods using adversarial attacks and deep watermarking, or
simple combinations of the two. Our work potentially opens up new insights into
proactive protection for FR privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.13426v1">Data Privacy Vocabulary (DPV) -- Version 2</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-04-20T17:24:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Harshvardhan J. Pandit, Beatriz Esteves, Georg P. Krog, Paul Ryan, Delaram Golpayegani, Julian Flake</p>
    <p><b>Summary:</b> The Data Privacy Vocabulary (DPV), developed by the W3C Data Privacy
Vocabularies and Controls Community Group (DPVCG), enables the creation of
machine-readable, interoperable, and standards-based representations for
describing the processing of personal data. The group has also published
extensions to the DPV to describe specific applications to support legislative
requirements such as the EU's GDPR. The DPV fills a crucial niche in the state
of the art by providing a vocabulary that can be embedded and used alongside
other existing standards such as W3C ODRL, and which can be customised and
extended for adapting to specifics of use-cases or domains. This article
describes the version 2 iteration of the DPV in terms of its contents,
methodology, current adoptions and uses, and future potential. It also
describes the relevance and role of DPV in acting as a common vocabulary to
support various regulatory (e.g. EU's DGA and AI Act) and community initiatives
(e.g. Solid) emerging across the globe.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.13407v1">A Framework for Managing Multifaceted Privacy Leakage While Optimizing
  Utility in Continuous LBS Interactions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-04-20T15:20:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anis Bkakria, Reda Yaich</p>
    <p><b>Summary:</b> Privacy in Location-Based Services (LBS) has become a paramount concern with
the ubiquity of mobile devices and the increasing integration of location data
into various applications. In this paper, we present several novel
contributions aimed at advancing the understanding and management of privacy
leakage in LBS. Our contributions provides a more comprehensive framework for
analyzing privacy concerns across different facets of location-based
interactions. Specifically, we introduce $(\epsilon, \delta)$-location privacy,
$(\epsilon, \delta, \theta)$-trajectory privacy, and $(\epsilon, \delta,
\theta)$-POI privacy, which offer refined mechanisms for quantifying privacy
risks associated with location, trajectory, and points of interest when
continuously interacting with LBS. Furthermore, we establish fundamental
connections between these privacy notions, facilitating a holistic approach to
privacy preservation in LBS. Additionally, we present a lower bound analysis to
evaluate the utility of the proposed privacy-preserving mechanisms, offering
insights into the trade-offs between privacy protection and data utility.
Finally, we instantiate our framework with the Plannar Isotopic Mechanism to
demonstrate its practical applicability while ensuring optimal utility and
quantifying privacy leakages across various dimensions. The conducted
evaluations provide a comprehensive insight into the efficacy of our framework
in capturing privacy loss on location, trajectory, and Points of Interest (POI)
while facilitating quantification of the ensured accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.13220v2">Security and Privacy Product Inclusion</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-04-20T00:36:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dave Kleidermacher, Emmanuel Arriaga, Eric Wang, Sebastian Porst, Roger Piqueras Jover</p>
    <p><b>Summary:</b> In this paper, we explore the challenges of ensuring security and privacy for
users from diverse demographic backgrounds. We propose a threat modeling
approach to identify potential risks and countermeasures for product inclusion
in security and privacy. We discuss various factors that can affect a user's
ability to achieve a high level of security and privacy, including low-income
demographics, poor connectivity, shared device usage, ML fairness, etc. We
present results from a global security and privacy user experience survey and
discuss the implications for product developers. Our work highlights the need
for a more inclusive approach to security and privacy and provides a framework
for researchers and practitioners to consider when designing products and
services for a diverse range of users.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.13194v1">Privacy-Preserving Debiasing using Data Augmentation and Machine
  Unlearning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-04-19T21:54:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhixin Pan, Emma Andrews, Laura Chang, Prabhat Mishra</p>
    <p><b>Summary:</b> Data augmentation is widely used to mitigate data bias in the training
dataset. However, data augmentation exposes machine learning models to privacy
attacks, such as membership inference attacks. In this paper, we propose an
effective combination of data augmentation and machine unlearning, which can
reduce data bias while providing a provable defense against known attacks.
Specifically, we maintain the fairness of the trained model with
diffusion-based data augmentation, and then utilize multi-shard unlearning to
remove identifying information of original data from the ML model for
protection against privacy attacks. Experimental evaluation across diverse
datasets demonstrates that our approach can achieve significant improvements in
bias reduction as well as robustness against state-of-the-art privacy attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.12837v1">Towards a decentralized data privacy protocol for self-sovereignty in
  the digital world</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2024-04-19T12:19:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rodrigo Falcão, Arghavan Hosseinzadeh</p>
    <p><b>Summary:</b> A typical user interacts with many digital services nowadays, providing these
services with their data. As of now, the management of privacy preferences is
service-centric: Users must manage their privacy preferences according to the
rules of each service provider, meaning that every provider offers its unique
mechanisms for users to control their privacy settings. However, managing
privacy preferences holistically (i.e., across multiple digital services) is
just impractical. In this vision paper, we propose a paradigm shift towards an
enriched user-centric approach for cross-service privacy preferences
management: the realization of a decentralized data privacy protocol.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.12730v1">PATE-TripleGAN: Privacy-Preserving Image Synthesis with Gaussian
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-04-19T09:22:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zepeng Jiang, Weiwei Ni, Yifan Zhang</p>
    <p><b>Summary:</b> Conditional Generative Adversarial Networks (CGANs) exhibit significant
potential in supervised learning model training by virtue of their ability to
generate realistic labeled images. However, numerous studies have indicated the
privacy leakage risk in CGANs models. The solution DPCGAN, incorporating the
differential privacy framework, faces challenges such as heavy reliance on
labeled data for model training and potential disruptions to original gradient
information due to excessive gradient clipping, making it difficult to ensure
model accuracy. To address these challenges, we present a privacy-preserving
training framework called PATE-TripleGAN. This framework incorporates a
classifier to pre-classify unlabeled data, establishing a three-party min-max
game to reduce dependence on labeled data. Furthermore, we present a hybrid
gradient desensitization algorithm based on the Private Aggregation of Teacher
Ensembles (PATE) framework and Differential Private Stochastic Gradient Descent
(DPSGD) method. This algorithm allows the model to retain gradient information
more effectively while ensuring privacy protection, thereby enhancing the
model's utility. Privacy analysis and extensive experiments affirm that the
PATE-TripleGAN model can generate a higher quality labeled image dataset while
ensuring the privacy of the training data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.12186v1">Privacy-Preserving UCB Decision Process Verification via zk-SNARKs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-04-18T13:49:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xikun Jiang, He Lyu, Chenhao Ying, Yibin Xu, Boris Düdder, Yuan Luo</p>
    <p><b>Summary:</b> With the increasingly widespread application of machine learning, how to
strike a balance between protecting the privacy of data and algorithm
parameters and ensuring the verifiability of machine learning has always been a
challenge. This study explores the intersection of reinforcement learning and
data privacy, specifically addressing the Multi-Armed Bandit (MAB) problem with
the Upper Confidence Bound (UCB) algorithm. We introduce zkUCB, an innovative
algorithm that employs the Zero-Knowledge Succinct Non-Interactive Argument of
Knowledge (zk-SNARKs) to enhance UCB. zkUCB is carefully designed to safeguard
the confidentiality of training data and algorithmic parameters, ensuring
transparent UCB decision-making. Experiments highlight zkUCB's superior
performance, attributing its enhanced reward to judicious quantization bit
usage that reduces information entropy in the decision-making process. zkUCB's
proof size and verification time scale linearly with the execution steps of
zkUCB. This showcases zkUCB's adept balance between data security and
operational efficiency. This approach contributes significantly to the ongoing
discourse on reinforcing data privacy in complex decision-making processes,
offering a promising solution for privacy-sensitive applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.11938v1">HyDiscGAN: A Hybrid Distributed cGAN for Audio-Visual Privacy
  Preservation in Multimodal Sentiment Analysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Multimedia-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> 
  <p><b>Published on:</b> 2024-04-18T06:38:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhuojia Wu, Qi Zhang, Duoqian Miao, Kun Yi, Wei Fan, Liang Hu</p>
    <p><b>Summary:</b> Multimodal Sentiment Analysis (MSA) aims to identify speakers' sentiment
tendencies in multimodal video content, raising serious concerns about privacy
risks associated with multimodal data, such as voiceprints and facial images.
Recent distributed collaborative learning has been verified as an effective
paradigm for privacy preservation in multimodal tasks. However, they often
overlook the privacy distinctions among different modalities, struggling to
strike a balance between performance and privacy preservation. Consequently, it
poses an intriguing question of maximizing multimodal utilization to improve
performance while simultaneously protecting necessary modalities. This paper
forms the first attempt at modality-specified (i.e., audio and visual) privacy
preservation in MSA tasks. We propose a novel Hybrid Distributed cross-modality
cGAN framework (HyDiscGAN), which learns multimodality alignment to generate
fake audio and visual features conditioned on shareable de-identified textual
data. The objective is to leverage the fake features to approximate real audio
and visual content to guarantee privacy preservation while effectively
enhancing performance. Extensive experiments show that compared with the
state-of-the-art MSA model, HyDiscGAN can achieve superior or competitive
performance while preserving privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.13087v1">Demystifying Legalese: An Automated Approach for Summarizing and
  Analyzing Overlaps in Privacy Policies and Terms of Service</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-04-17T19:53:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shikha Soneji, Mitchell Hoesing, Sujay Koujalgi, Jonathan Dodge</p>
    <p><b>Summary:</b> The complexities of legalese in terms and policy documents can bind
individuals to contracts they do not fully comprehend, potentially leading to
uninformed data sharing. Our work seeks to alleviate this issue by developing
language models that provide automated, accessible summaries and scores for
such documents, aiming to enhance user understanding and facilitate informed
decisions. We compared transformer-based and conventional models during
training on our dataset, and RoBERTa performed better overall with a remarkable
0.74 F1-score. Leveraging our best-performing model, RoBERTa, we highlighted
redundancies and potential guideline violations by identifying overlaps in
GDPR-required documents, underscoring the necessity for stricter GDPR
compliance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.11515v1">Embedding Privacy in Computational Social Science and Artificial
  Intelligence Research</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-04-17T16:07:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Keenan Jones, Fatima Zahrah, Jason R. C. Nurse</p>
    <p><b>Summary:</b> Privacy is a human right. It ensures that individuals are free to engage in
discussions, participate in groups, and form relationships online or offline
without fear of their data being inappropriately harvested, analyzed, or
otherwise used to harm them. Preserving privacy has emerged as a critical
factor in research, particularly in the computational social science (CSS),
artificial intelligence (AI) and data science domains, given their reliance on
individuals' data for novel insights. The increasing use of advanced
computational models stands to exacerbate privacy concerns because, if
inappropriately used, they can quickly infringe privacy rights and lead to
adverse effects for individuals - especially vulnerable groups - and society.
We have already witnessed a host of privacy issues emerge with the advent of
large language models (LLMs), such as ChatGPT, which further demonstrate the
importance of embedding privacy from the start. This article contributes to the
field by discussing the role of privacy and the primary issues that researchers
working in CSS, AI, data science and related domains are likely to face. It
then presents several key considerations for researchers to ensure participant
privacy is best preserved in their research design, data collection and use,
analysis, and dissemination of research results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.11470v1">A Federated Learning Approach to Privacy Preserving Offensive Language
  Identification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-04-17T15:23:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marcos Zampieri, Damith Premasiri, Tharindu Ranasinghe</p>
    <p><b>Summary:</b> The spread of various forms of offensive speech online is an important
concern in social media. While platforms have been investing heavily in ways of
coping with this problem, the question of privacy remains largely unaddressed.
Models trained to detect offensive language on social media are trained and/or
fine-tuned using large amounts of data often stored in centralized servers.
Since most social media data originates from end users, we propose a privacy
preserving decentralized architecture for identifying offensive language online
by introducing Federated Learning (FL) in the context of offensive language
identification. FL is a decentralized architecture that allows multiple models
to be trained locally without the need for data sharing hence preserving users'
privacy. We propose a model fusion approach to perform FL. We trained multiple
deep learning models on four publicly available English benchmark datasets
(AHSD, HASOC, HateXplain, OLID) and evaluated their performance in detail. We
also present initial cross-lingual experiments in English and Spanish. We show
that the proposed model fusion approach outperforms baselines in all the
datasets while preserving privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.11450v1">Real-Time Trajectory Synthesis with Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-04-17T14:55:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yujia Hu, Yuntao Du, Zhikun Zhang, Ziquan Fang, Lu Chen, Kai Zheng, Yunjun Gao</p>
    <p><b>Summary:</b> Trajectory streams are being generated from location-aware devices, such as
smartphones and in-vehicle navigation systems. Due to the sensitive nature of
the location data, directly sharing user trajectories suffers from privacy
leakage issues. Local differential privacy (LDP), which perturbs sensitive data
on the user side before it is shared or analyzed, emerges as a promising
solution for private trajectory stream collection and analysis. Unfortunately,
existing stream release approaches often neglect the rich spatial-temporal
context information within trajectory streams, resulting in suboptimal utility
and limited types of downstream applications. To this end, we propose RetraSyn,
a novel real-time trajectory synthesis framework, which is able to perform
on-the-fly trajectory synthesis based on the mobility patterns privately
extracted from users' trajectory streams. Thus, the downstream trajectory
analysis can be performed on the high-utility synthesized data with privacy
protection. We also take the genuine behaviors of real-world mobile travelers
into consideration, ensuring authenticity and practicality. The key components
of RetraSyn include the global mobility model, dynamic mobility update
mechanism, real-time synthesis, and adaptive allocation strategy. We conduct
extensive experiments on multiple real-world and synthetic trajectory datasets
under various location-based utility metrics, encompassing both streaming and
historical scenarios. The empirical results demonstrate the superiority and
versatility of our proposed framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.11388v1">Enhancing Data Privacy In Wireless Sensor Networks: Investigating
  Techniques And Protocols To Protect Privacy Of Data Transmitted Over Wireless
  Sensor Networks In Critical Applications Of Healthcare And National Security</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2024-04-17T13:48:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Akinsola Ahmed, Ejiofor Oluomachi, Akinde Abdullah, Njoku Tochukwu</p>
    <p><b>Summary:</b> The article discusses the emergence of Wireless Sensor Networks (WSNs) as a
groundbreaking technology in data processing and communication. It outlines how
WSNs, composed of dispersed autonomous sensors, are utilized to monitor
physical and environmental factors, transmitting data wirelessly for analysis.
The article explores various applications of WSNs in healthcare, national
security, emergency response, and infrastructure monitoring, highlighting their
roles in enhancing patient care, public health surveillance, border security,
disaster management, and military operations. Additionally, it examines the
foundational concepts of data privacy in WSNs, focusing on encryption
techniques, authentication mechanisms, anonymization techniques, and access
control mechanisms. The article also addresses vulnerabilities, threats, and
challenges related to data privacy in healthcare and national security
contexts, emphasizing regulatory compliance, ethical considerations, and
socio-economic factors. Furthermore, it introduces the Diffusion of Innovation
Theory as a framework for understanding the adoption of privacy-enhancing
technologies in WSNs. Finally, the article reviews empirical studies
demonstrating the efficacy of security solutions in preserving data privacy in
WSNs, offering insights into advancements in safeguarding sensitive
information.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.10995v1">Clipped SGD Algorithms for Privacy Preserving Performative Prediction:
  Bias Amplification and Remedies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-04-17T02:17:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qiang Li, Michal Yemini, Hoi-To Wai</p>
    <p><b>Summary:</b> Clipped stochastic gradient descent (SGD) algorithms are among the most
popular algorithms for privacy preserving optimization that reduces the leakage
of users' identity in model training. This paper studies the convergence
properties of these algorithms in a performative prediction setting, where the
data distribution may shift due to the deployed prediction model. For example,
the latter is caused by strategical users during the training of loan policy
for banks. Our contributions are two-fold. First, we show that the
straightforward implementation of a projected clipped SGD (PCSGD) algorithm may
converge to a biased solution compared to the performative stable solution. We
quantify the lower and upper bound for the magnitude of the bias and
demonstrate a bias amplification phenomenon where the bias grows with the
sensitivity of the data distribution. Second, we suggest two remedies to the
bias amplification effect. The first one utilizes an optimal step size design
for PCSGD that takes the privacy guarantee into account. The second one uses
the recently proposed DiceSGD algorithm [Zhang et al., 2024]. We show that the
latter can successfully remove the bias and converge to the performative stable
solution. Numerical experiments verify our analysis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.10767v1">Privacy Can Arise Endogenously in an Economic System with Learning
  Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB">
  <p><b>Published on:</b> 2024-04-16T17:51:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nivasini Ananthakrishnan, Tiffany Ding, Mariel Werner, Sai Praneeth Karimireddy, Michael I. Jordan</p>
    <p><b>Summary:</b> We study price-discrimination games between buyers and a seller where privacy
arises endogenously--that is, utility maximization yields equilibrium
strategies where privacy occurs naturally. In this game, buyers with a high
valuation for a good have an incentive to keep their valuation private, lest
the seller charge them a higher price. This yields an equilibrium where some
buyers will send a signal that misrepresents their type with some probability;
we refer to this as buyer-induced privacy. When the seller is able to publicly
commit to providing a certain privacy level, we find that their equilibrium
response is to commit to ignore buyers' signals with some positive probability;
we refer to this as seller-induced privacy. We then turn our attention to a
repeated interaction setting where the game parameters are unknown and the
seller cannot credibly commit to a level of seller-induced privacy. In this
setting, players must learn strategies based on information revealed in past
rounds. We find that, even without commitment ability, seller-induced privacy
arises as a result of reputation building. We characterize the resulting
seller-induced privacy and seller's utility under no-regret and
no-policy-regret learning algorithms and verify these results through
simulations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.10258v1">CO-oPS: A Mobile App for Community Oversight of Privacy and Security</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-04-16T03:25:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mamtaj Akter, Leena Alghamdi, Dylan Gillespie, Nazmus Miazi, Jess Kropczynski, Heather Lipford, Pamela Wisniewski</p>
    <p><b>Summary:</b> Smartphone users install numerous mobile apps that require access to
different information from their devices. Much of this information is very
sensitive, and users often struggle to manage these accesses due to their lack
of tech expertise and knowledge regarding mobile privacy. Thus, they often seek
help from others to make decisions regarding their mobile privacy and security.
We embedded these social processes in a mobile app titled "CO-oPS'' ("Community
Oversight for Privacy and Security"). CO-oPS allows trusted community members
to review one another's apps installed and permissions granted to those apps.
Community members can provide feedback to one another regarding their privacy
behaviors. Users are also allowed to hide some of their mobile apps that they
do not like others to see, ensuring their personal privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.10255v1">Privacy-Preserving Training-as-a-Service for On-Device Intelligence:
  Concept, Architectural Scheme, and Open Problems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-04-16T03:18:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhiyuan Wu, Sheng Sun, Yuwei Wang, Min Liu, Bo Gao, Tianliu He, Wen Wang</p>
    <p><b>Summary:</b> On-device intelligence (ODI) enables artificial intelligence (AI)
applications to run on end devices, providing real-time and customized AI
services without relying on remote servers. However, training models for
on-device deployment face significant challenges due to the decentralized and
privacy-sensitive nature of users' data, along with end-side constraints
related to network connectivity, computation efficiency, etc. Existing training
paradigms, such as cloud-based training, federated learning, and transfer
learning, fail to sufficiently address these practical constraints that are
prevalent for devices. To overcome these challenges, we propose
Privacy-Preserving Training-as-a-Service (PTaaS), a novel service computing
paradigm that provides privacy-friendly, customized AI model training for end
devices. PTaaS outsources the core training process to remote and powerful
cloud or edge servers, efficiently developing customized on-device models based
on uploaded anonymous queries, ensuring data privacy while reducing the
computation load on individual devices. We explore the definition, goals, and
design principles of PTaaS, alongside emerging technologies that support the
PTaaS paradigm. An architectural scheme for PTaaS is also presented, followed
by a series of open problems that set the stage for future research directions
in the field of PTaaS.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.09816v1">FedP3: Federated Personalized and Privacy-friendly Network Pruning under
  Model Heterogeneity</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-04-15T14:14:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kai Yi, Nidham Gazagnadou, Peter Richtárik, Lingjuan Lyu</p>
    <p><b>Summary:</b> The interest in federated learning has surged in recent research due to its
unique ability to train a global model using privacy-secured information held
locally on each client. This paper pays particular attention to the issue of
client-side model heterogeneity, a pervasive challenge in the practical
implementation of FL that escalates its complexity. Assuming a scenario where
each client possesses varied memory storage, processing capabilities and
network bandwidth - a phenomenon referred to as system heterogeneity - there is
a pressing need to customize a unique model for each client. In response to
this, we present an effective and adaptable federated framework FedP3,
representing Federated Personalized and Privacy-friendly network Pruning,
tailored for model heterogeneity scenarios. Our proposed methodology can
incorporate and adapt well-established techniques to its specific instances. We
offer a theoretical interpretation of FedP3 and its locally
differential-private variant, DP-FedP3, and theoretically validate their
efficiencies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.10029v1">Federated Learning on Riemannian Manifolds with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2024-04-15T12:32:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhenwei Huang, Wen Huang, Pratik Jawanpuria, Bamdev Mishra</p>
    <p><b>Summary:</b> In recent years, federated learning (FL) has emerged as a prominent paradigm
in distributed machine learning. Despite the partial safeguarding of agents'
information within FL systems, a malicious adversary can potentially infer
sensitive information through various means. In this paper, we propose a
generic private FL framework defined on Riemannian manifolds (PriRFed) based on
the differential privacy (DP) technique. We analyze the privacy guarantee while
establishing the convergence properties. To the best of our knowledge, this is
the first federated learning framework on Riemannian manifold with a privacy
guarantee and convergence results. Numerical simulations are performed on
synthetic and real-world datasets to showcase the efficacy of the proposed
PriRFed approach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.09724v1">Privacy-Preserving Federated Unlearning with Certified Client Removal</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-04-15T12:27:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ziyao Liu, Huanyi Ye, Yu Jiang, Jiyuan Shen, Jiale Guo, Ivan Tjuawinata, Kwok-Yan Lam</p>
    <p><b>Summary:</b> In recent years, Federated Unlearning (FU) has gained attention for
addressing the removal of a client's influence from the global model in
Federated Learning (FL) systems, thereby ensuring the ``right to be forgotten"
(RTBF). State-of-the-art methods for unlearning use historical data from FL
clients, such as gradients or locally trained models. However, studies have
revealed significant information leakage in this setting, with the possibility
of reconstructing a user's local data from their uploaded information.
Addressing this, we propose Starfish, a privacy-preserving federated unlearning
scheme using Two-Party Computation (2PC) techniques and shared historical
client data between two non-colluding servers. Starfish builds upon existing FU
methods to ensure privacy in unlearning processes. To enhance the efficiency of
privacy-preserving FU evaluations, we suggest 2PC-friendly alternatives for
certain FU algorithm operations. We also implement strategies to reduce costs
associated with 2PC operations and lessen cumulative approximation errors.
Moreover, we establish a theoretical bound for the difference between the
unlearned global model via Starfish and a global model retrained from scratch
for certified client removal. Our theoretical and experimental analyses
demonstrate that Starfish achieves effective unlearning with reasonable
efficiency, maintaining privacy and security in FL systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.09625v1">Privacy-Preserving Intrusion Detection using Convolutional Neural
  Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-04-15T09:56:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Martin Kodys, Zhongmin Dai, Vrizlynn L. L. Thing</p>
    <p><b>Summary:</b> Privacy-preserving analytics is designed to protect valuable assets. A common
service provision involves the input data from the client and the model on the
analyst's side. The importance of the privacy preservation is fuelled by legal
obligations and intellectual property concerns. We explore the use case of a
model owner providing an analytic service on customer's private data. No
information about the data shall be revealed to the analyst and no information
about the model shall be leaked to the customer. Current methods involve costs:
accuracy deterioration and computational complexity. The complexity, in turn,
results in a longer processing time, increased requirement on computing
resources, and involves data communication between the client and the server.
In order to deploy such service architecture, we need to evaluate the optimal
setting that fits the constraints. And that is what this paper addresses. In
this work, we enhance an attack detection system based on Convolutional Neural
Networks with privacy-preserving technology based on PriMIA framework that is
initially designed for medical data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.10026v1">Distributed Federated Learning-Based Deep Learning Model for Privacy MRI
  Brain Tumor Detection</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-04-15T09:07:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lisang Zhou, Meng Wang, Ning Zhou</p>
    <p><b>Summary:</b> Distributed training can facilitate the processing of large medical image
datasets, and improve the accuracy and efficiency of disease diagnosis while
protecting patient privacy, which is crucial for achieving efficient medical
image analysis and accelerating medical research progress. This paper presents
an innovative approach to medical image classification, leveraging Federated
Learning (FL) to address the dual challenges of data privacy and efficient
disease diagnosis. Traditional Centralized Machine Learning models, despite
their widespread use in medical imaging for tasks such as disease diagnosis,
raise significant privacy concerns due to the sensitive nature of patient data.
As an alternative, FL emerges as a promising solution by allowing the training
of a collective global model across local clients without centralizing the
data, thus preserving privacy. Focusing on the application of FL in Magnetic
Resonance Imaging (MRI) brain tumor detection, this study demonstrates the
effectiveness of the Federated Learning framework coupled with EfficientNet-B0
and the FedAvg algorithm in enhancing both privacy and diagnostic accuracy.
Through a meticulous selection of preprocessing methods, algorithms, and
hyperparameters, and a comparative analysis of various Convolutional Neural
Network (CNN) architectures, the research uncovers optimal strategies for image
classification. The experimental results reveal that EfficientNet-B0
outperforms other models like ResNet in handling data heterogeneity and
achieving higher accuracy and lower loss, highlighting the potential of FL in
overcoming the limitations of traditional models. The study underscores the
significance of addressing data heterogeneity and proposes further research
directions for broadening the applicability of FL in medical image analysis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.09536v1">Beyond Noise: Privacy-Preserving Decentralized Learning with Virtual
  Nodes</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-04-15T07:59:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sayan Biswas, Mathieu Even, Anne-Marie Kermarrec, Laurent Massoulie, Rafael Pires, Rishi Sharma, Martijn de Vos</p>
    <p><b>Summary:</b> Decentralized learning (DL) enables collaborative learning without a server
and without training data leaving the users' devices. However, the models
shared in DL can still be used to infer training data. Conventional privacy
defenses such as differential privacy and secure aggregation fall short in
effectively safeguarding user privacy in DL. We introduce Shatter, a novel DL
approach in which nodes create virtual nodes (VNs) to disseminate chunks of
their full model on their behalf. This enhances privacy by (i) preventing
attackers from collecting full models from other nodes, and (ii) hiding the
identity of the original node that produced a given model chunk. We
theoretically prove the convergence of Shatter and provide a formal analysis
demonstrating how Shatter reduces the efficacy of attacks compared to when
exchanging full models between participating nodes. We evaluate the convergence
and attack resilience of Shatter with existing DL algorithms, with
heterogeneous datasets, and against three standard privacy attacks, including
gradient inversion. Our evaluation shows that Shatter not only renders these
privacy attacks infeasible when each node operates 16 VNs but also exhibits a
positive impact on model convergence compared to standard DL. This enhanced
privacy comes with a manageable increase in communication volume.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.09481v1">SpamDam: Towards Privacy-Preserving and Adversary-Resistant SMS Spam
  Detection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-04-15T06:07:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yekai Li, Rufan Zhang, Wenxin Rong, Xianghang Mi</p>
    <p><b>Summary:</b> In this study, we introduce SpamDam, a SMS spam detection framework designed
to overcome key challenges in detecting and understanding SMS spam, such as the
lack of public SMS spam datasets, increasing privacy concerns of collecting SMS
data, and the need for adversary-resistant detection models. SpamDam comprises
four innovative modules: an SMS spam radar that identifies spam messages from
online social networks(OSNs); an SMS spam inspector for statistical analysis;
SMS spam detectors(SSDs) that enable both central training and federated
learning; and an SSD analyzer that evaluates model resistance against
adversaries in realistic scenarios. Leveraging SpamDam, we have compiled over
76K SMS spam messages from Twitter and Weibo between 2018 and 2023, forming the
largest dataset of its kind. This dataset has enabled new insights into recent
spam campaigns and the training of high-performing binary and multi-label
classifiers for spam detection. Furthermore, effectiveness of federated
learning has been well demonstrated to enable privacy-preserving SMS spam
detection. Additionally, we have rigorously tested the adversarial robustness
of SMS spam detection models, introducing the novel reverse backdoor attack,
which has shown effectiveness and stealthiness in practical tests.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.09430v1">On the Efficiency of Privacy Attacks in Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-04-15T03:04:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nawrin Tabassum, Ka-Ho Chow, Xuyu Wang, Wenbin Zhang, Yanzhao Wu</p>
    <p><b>Summary:</b> Recent studies have revealed severe privacy risks in federated learning,
represented by Gradient Leakage Attacks. However, existing studies mainly aim
at increasing the privacy attack success rate and overlook the high computation
costs for recovering private data, making the privacy attack impractical in
real applications. In this study, we examine privacy attacks from the
perspective of efficiency and propose a framework for improving the Efficiency
of Privacy Attacks in Federated Learning (EPAFL). We make three novel
contributions. First, we systematically evaluate the computational costs for
representative privacy attacks in federated learning, which exhibits a high
potential to optimize efficiency. Second, we propose three early-stopping
techniques to effectively reduce the computational costs of these privacy
attacks. Third, we perform experiments on benchmark datasets and show that our
proposed method can significantly reduce computational costs and maintain
comparable attack success rates for state-of-the-art privacy attacks in
federated learning. We provide the codes on GitHub at
https://github.com/mlsysx/EPAFL.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.09391v1">Privacy at a Price: Exploring its Dual Impact on AI Fairness</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-04-15T00:23:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mengmeng Yang, Ming Ding, Youyang Qu, Wei Ni, David Smith, Thierry Rakotoarivelo</p>
    <p><b>Summary:</b> The worldwide adoption of machine learning (ML) and deep learning models,
particularly in critical sectors, such as healthcare and finance, presents
substantial challenges in maintaining individual privacy and fairness. These
two elements are vital to a trustworthy environment for learning systems. While
numerous studies have concentrated on protecting individual privacy through
differential privacy (DP) mechanisms, emerging research indicates that
differential privacy in machine learning models can unequally impact separate
demographic subgroups regarding prediction accuracy. This leads to a fairness
concern, and manifests as biased performance. Although the prevailing view is
that enhancing privacy intensifies fairness disparities, a smaller, yet
significant, subset of research suggests the opposite view. In this article,
with extensive evaluation results, we demonstrate that the impact of
differential privacy on fairness is not monotonous. Instead, we observe that
the accuracy disparity initially grows as more DP noise (enhanced privacy) is
added to the ML process, but subsequently diminishes at higher privacy levels
with even more noise. Moreover, implementing gradient clipping in the
differentially private stochastic gradient descent ML method can mitigate the
negative impact of DP noise on fairness. This mitigation is achieved by
moderating the disparity growth through a lower clipping threshold.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.08261v1">QI-DPFL: Quality-Aware and Incentive-Boosted Federated Learning with
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB">
  <p><b>Published on:</b> 2024-04-12T06:18:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenhao Yuan, Xuehe Wang</p>
    <p><b>Summary:</b> Federated Learning (FL) has increasingly been recognized as an innovative and
secure distributed model training paradigm, aiming to coordinate multiple edge
clients to collaboratively train a shared model without uploading their private
datasets. The challenge of encouraging mobile edge devices to participate
zealously in FL model training procedures, while mitigating the privacy leakage
risks during wireless transmission, remains comparatively unexplored so far. In
this paper, we propose a novel approach, named QI-DPFL (Quality-Aware and
Incentive-Boosted Federated Learning with Differential Privacy), to address the
aforementioned intractable issue. To select clients with high-quality datasets,
we first propose a quality-aware client selection mechanism based on the Earth
Mover's Distance (EMD) metric. Furthermore, to attract high-quality data
contributors, we design an incentive-boosted mechanism that constructs the
interactions between the central server and the selected clients as a two-stage
Stackelberg game, where the central server designs the time-dependent reward to
minimize its cost by considering the trade-off between accuracy loss and total
reward allocated, and each selected client decides the privacy budget to
maximize its utility. The Nash Equilibrium of the Stackelberg game is derived
to find the optimal solution in each global iteration. The extensive
experimental results on different real-world datasets demonstrate the
effectiveness of our proposed FL framework, by realizing the goal of privacy
protection and incentive compatibility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.07437v1">Privacy preserving layer partitioning for Deep Neural Network models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-04-11T02:39:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kishore Rajasekar, Randolph Loh, Kar Wai Fok, Vrizlynn L. L. Thing</p>
    <p><b>Summary:</b> MLaaS (Machine Learning as a Service) has become popular in the cloud
computing domain, allowing users to leverage cloud resources for running
private inference of ML models on their data. However, ensuring user input
privacy and secure inference execution is essential. One of the approaches to
protect data privacy and integrity is to use Trusted Execution Environments
(TEEs) by enabling execution of programs in secure hardware enclave. Using TEEs
can introduce significant performance overhead due to the additional layers of
encryption, decryption, security and integrity checks. This can lead to slower
inference times compared to running on unprotected hardware. In our work, we
enhance the runtime performance of ML models by introducing layer partitioning
technique and offloading computations to GPU. The technique comprises two
distinct partitions: one executed within the TEE, and the other carried out
using a GPU accelerator. Layer partitioning exposes intermediate feature maps
in the clear which can lead to reconstruction attacks to recover the input. We
conduct experiments to demonstrate the effectiveness of our approach in
protecting against input reconstruction attacks developed using trained
conditional Generative Adversarial Network(c-GAN). The evaluation is performed
on widely used models such as VGG-16, ResNet-50, and EfficientNetB0, using two
datasets: ImageNet for Image classification and TON IoT dataset for
cybersecurity attack detection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.07345v1">Indoor Location Fingerprinting Privacy: A Comprehensive Survey</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-04-10T21:02:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Amir Fathalizadeh, Vahideh Moghtadaiee, Mina Alishahi</p>
    <p><b>Summary:</b> The pervasive integration of Indoor Positioning Systems (IPS) arises from the
limitations of Global Navigation Satellite Systems (GNSS) in indoor
environments, leading to the widespread adoption of Location-Based Services
(LBS). Specifically, indoor location fingerprinting employs diverse signal
fingerprints from user devices, enabling precise location identification by
Location Service Providers (LSP). Despite its broad applications across various
domains, indoor location fingerprinting introduces a notable privacy risk, as
both LSP and potential adversaries inherently have access to this sensitive
information, compromising users' privacy. Consequently, concerns regarding
privacy vulnerabilities in this context necessitate a focused exploration of
privacy-preserving mechanisms. In response to these concerns, this survey
presents a comprehensive review of Privacy-Preserving Mechanisms in Indoor
Location Fingerprinting (ILFPPM) based on cryptographic, anonymization,
differential privacy (DP), and federated learning (FL) techniques. We also
propose a distinctive and novel grouping of privacy vulnerabilities, adversary
and attack models, and available evaluation metrics specific to indoor location
fingerprinting systems. Given the identified limitations and research gaps in
this survey, we highlight numerous prospective opportunities for future
investigation, aiming to motivate researchers interested in advancing this
field. This survey serves as a valuable reference for researchers and provides
a clear overview for those beyond this specific research domain.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.06868v1">The 'Sandwich' meta-framework for architecture agnostic deep
  privacy-preserving transfer learning for non-invasive brainwave decoding</a></h3>
  
  <p><b>Published on:</b> 2024-04-10T09:47:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaoxi Wei, Jyotindra Narayan, A. Aldo Faisal</p>
    <p><b>Summary:</b> Machine learning has enhanced the performance of decoding signals indicating
human behaviour. EEG decoding, as an exemplar indicating neural activity and
human thoughts non-invasively, has been helpful in neural activity analysis and
aiding patients via brain-computer interfaces. However, training machine
learning algorithms on EEG encounters two primary challenges: variability
across data sets and privacy concerns using data from individuals and data
centres. Our objective is to address these challenges by integrating transfer
learning for data variability and federated learning for data privacy into a
unified approach. We introduce the Sandwich as a novel deep privacy-preserving
meta-framework combining transfer learning and federated learning. The Sandwich
framework comprises three components: federated networks (first layers) that
handle data set differences at the input level, a shared network (middle layer)
learning common rules and applying transfer learning, and individual
classifiers (final layers) for specific tasks of each data set. It enables the
central network (central server) to benefit from multiple data sets, while
local branches (local servers) maintain data and label privacy. We evaluated
the `Sandwich' meta-architecture in various configurations using the BEETL
motor imagery challenge, a benchmark for heterogeneous EEG data sets. Compared
with baseline models, our `Sandwich' implementations showed superior
performance. The best-performing model, the Inception Sandwich with deep set
alignment (Inception-SD-Deepset), exceeded baseline methods by 9%. The
`Sandwich' framework demonstrates significant advancements in federated deep
transfer learning for diverse tasks and data sets. It outperforms conventional
deep learning methods, showcasing the potential for effective use of larger,
heterogeneous data sets with enhanced privacy as a model-agnostic
meta-framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.06721v2">Poisoning Prevention in Federated Learning and Differential Privacy via
  Stateful Proofs of Execution</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-04-10T04:18:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Norrathep Rattanavipanon, Ivan De Oliveira Nunes</p>
    <p><b>Summary:</b> The rise in IoT-driven distributed data analytics, coupled with increasing
privacy concerns, has led to a demand for effective privacy-preserving and
federated data collection/model training mechanisms. In response, approaches
such as Federated Learning (FL) and Local Differential Privacy (LDP) have been
proposed and attracted much attention over the past few years. However, they
still share the common limitation of being vulnerable to poisoning attacks
wherein adversaries compromising edge devices feed forged (a.k.a. poisoned)
data to aggregation back-ends, undermining the integrity of FL/LDP results.
  In this work, we propose a system-level approach to remedy this issue based
on a novel security notion of Proofs of Stateful Execution (PoSX) for
IoT/embedded devices' software. To realize the PoSX concept, we design SLAPP: a
System-Level Approach for Poisoning Prevention. SLAPP leverages commodity
security features of embedded devices - in particular ARM TrustZoneM security
extensions - to verifiably bind raw sensed data to their correct usage as part
of FL/LDP edge device routines. As a consequence, it offers robust security
guarantees against poisoning. Our evaluation, based on real-world prototypes
featuring multiple cryptographic primitives and data collection schemes,
showcases SLAPP's security and low overhead.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.06686v1">Atlas-X Equity Financing: Unlocking New Methods to Securely Obfuscate
  Axe Inventory Data Based on Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-04-10T02:19:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Antigoni Polychroniadou, Gabriele Cipriani, Richard Hua, Tucker Balch</p>
    <p><b>Summary:</b> Banks publish daily a list of available securities/assets (axe list) to
selected clients to help them effectively locate Long (buy) or Short (sell)
trades at reduced financing rates. This reduces costs for the bank, as the list
aggregates the bank's internal firm inventory per asset for all clients of long
as well as short trades. However, this is somewhat problematic: (1) the bank's
inventory is revealed; (2) trades of clients who contribute to the aggregated
list, particularly those deemed large, are revealed to other clients. Clients
conducting sizable trades with the bank and possessing a portion of the
aggregated asset exceeding $50\%$ are considered to be concentrated clients.
This could potentially reveal a trading concentrated client's activity to their
competitors, thus providing an unfair advantage over the market.
  Atlas-X Axe Obfuscation, powered by new differential private methods, enables
a bank to obfuscate its published axe list on a daily basis while under
continual observation, thus maintaining an acceptable inventory Profit and Loss
(P&L) cost pertaining to the noisy obfuscated axe list while reducing the
clients' trading activity leakage. Our main differential private innovation is
a differential private aggregator for streams (time series data) of both
positive and negative integers under continual observation.
  For the last two years, Atlas-X system has been live in production across
three major regions-USA, Europe, and Asia-at J.P. Morgan, a major financial
institution, facilitating significant profitability. To our knowledge, it is
the first differential privacy solution to be deployed in the financial sector.
We also report benchmarks of our algorithm based on (anonymous) real and
synthetic data to showcase the quality of our obfuscation and its success in
production.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.06216v1">Privacy-preserving Scanpath Comparison for Pervasive Eye Tracking</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-04-09T11:07:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Suleyman Ozdel, Efe Bozkir, Enkelejda Kasneci</p>
    <p><b>Summary:</b> As eye tracking becomes pervasive with screen-based devices and head-mounted
displays, privacy concerns regarding eye-tracking data have escalated. While
state-of-the-art approaches for privacy-preserving eye tracking mostly involve
differential privacy and empirical data manipulations, previous research has
not focused on methods for scanpaths. We introduce a novel privacy-preserving
scanpath comparison protocol designed for the widely used Needleman-Wunsch
algorithm, a generalized version of the edit distance algorithm. Particularly,
by incorporating the Paillier homomorphic encryption scheme, our protocol
ensures that no private information is revealed. Furthermore, we introduce a
random processing strategy and a multi-layered masking method to obfuscate the
values while preserving the original order of encrypted editing operation
costs. This minimizes communication overhead, requiring a single communication
round for each iteration of the Needleman-Wunsch process. We demonstrate the
efficiency and applicability of our protocol on three publicly available
datasets with comprehensive computational performance analyses and make our
source code publicly accessible.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.06144v1">Differential Privacy for Anomaly Detection: Analyzing the Trade-off
  Between Privacy and Explainability</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-04-09T09:09:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fatima Ezzeddine, Mirna Saad, Omran Ayoub, Davide Andreoletti, Martin Gjoreski, Ihab Sbeity, Marc Langheinrich, Silvia Giordano</p>
    <p><b>Summary:</b> Anomaly detection (AD), also referred to as outlier detection, is a
statistical process aimed at identifying observations within a dataset that
significantly deviate from the expected pattern of the majority of the data.
Such a process finds wide application in various fields, such as finance and
healthcare. While the primary objective of AD is to yield high detection
accuracy, the requirements of explainability and privacy are also paramount.
The first ensures the transparency of the AD process, while the second
guarantees that no sensitive information is leaked to untrusted parties. In
this work, we exploit the trade-off of applying Explainable AI (XAI) through
SHapley Additive exPlanations (SHAP) and differential privacy (DP). We perform
AD with different models and on various datasets, and we thoroughly evaluate
the cost of privacy in terms of decreased accuracy and explainability. Our
results show that the enforcement of privacy through DP has a significant
impact on detection accuracy and explainability, which depends on both the
dataset and the considered AD model. We further show that the visual
interpretation of explanations is also influenced by the choice of the AD
algorithm.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.08686v1">Extractive text summarisation of Privacy Policy documents using machine
  learning approaches</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-04-09T04:54:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chanwoo Choi</p>
    <p><b>Summary:</b> This work demonstrates two Privacy Policy (PP) summarisation models based on
two different clustering algorithms: K-means clustering and Pre-determined
Centroid (PDC) clustering. K-means is decided to be used for the first model
after an extensive evaluation of ten commonly used clustering algorithms. The
summariser model based on the PDC-clustering algorithm summarises PP documents
by segregating individual sentences by Euclidean distance from each sentence to
the pre-defined cluster centres. The cluster centres are defined according to
General Data Protection Regulation (GDPR)'s 14 essential topics that must be
included in any privacy notices. The PDC model outperformed the K-means model
for two evaluation methods, Sum of Squared Distance (SSD) and ROUGE by some
margin (27% and 24% respectively). This result contrasts the K-means model's
better performance in the general clustering of sentence vectors before running
the task-specific evaluation. This indicates the effectiveness of operating
task-specific fine-tuning measures on unsupervised machine-learning models. The
summarisation mechanisms implemented in this paper demonstrates an idea of how
to efficiently extract essential sentences that should be included in any PP
documents. The summariser models could be further developed to an application
that tests the GDPR-compliance (or any data privacy legislation) of PP
documents.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.06001v2">Privacy Preserving Prompt Engineering: A Survey</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-04-09T04:11:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kennedy Edemacu, Xintao Wu</p>
    <p><b>Summary:</b> Pre-trained language models (PLMs) have demonstrated significant proficiency
in solving a wide range of general natural language processing (NLP) tasks.
Researchers have observed a direct correlation between the performance of these
models and their sizes. As a result, the sizes of these models have notably
expanded in recent years, persuading researchers to adopt the term large
language models (LLMs) to characterize the larger-sized PLMs. The size
expansion comes with a distinct capability called in-context learning (ICL),
which represents a special form of prompting and allows the models to be
utilized through the presentation of demonstration examples without
modifications to the model parameters. Although interesting, privacy concerns
have become a major obstacle in its widespread usage. Multiple studies have
examined the privacy risks linked to ICL and prompting in general, and have
devised techniques to alleviate these risks. Thus, there is a necessity to
organize these mitigation techniques for the benefit of the community. This
survey provides a systematic overview of the privacy protection methods
employed during ICL and prompting in general. We review, analyze, and compare
different methods under this paradigm. Furthermore, we provide a summary of the
resources accessible for the development of these frameworks. Finally, we
discuss the limitations of these frameworks and offer a detailed examination of
the promising areas that necessitate further exploration.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.05876v1">Privacy and Security of Women's Reproductive Health Apps in a Changing
  Legal Landscape</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2024-04-08T21:19:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shalini Saini, Nitesh Saxena</p>
    <p><b>Summary:</b> FemTech, a rising trend in mobile apps, empowers women to digitally manage
their health and family planning. However, privacy and security vulnerabilities
in period-tracking and fertility-monitoring apps present significant risks,
such as unintended pregnancies and legal consequences. Our approach involves
manual observations of privacy policies and app permissions, along with dynamic
and static analysis using multiple evaluation frameworks. Our research reveals
that many of these apps gather personally identifiable information (PII) and
sensitive healthcare data. Furthermore, our analysis identifies that 61% of the
code vulnerabilities found in the apps are classified under the top-ten Open
Web Application Security Project (OWASP) vulnerabilities. Our research
emphasizes the significance of tackling the privacy and security
vulnerabilities present in period-tracking and fertility-monitoring mobile
apps. By highlighting these crucial risks, we aim to initiate a vital
discussion and advocate for increased accountability and transparency of
digital tools for women's health. We encourage the industry to prioritize user
privacy and security, ultimately promoting a safer and more secure environment
for women's health management.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.05828v1">Privacy-Preserving Deep Learning Using Deformable Operators for Secure
  Task Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-04-08T19:46:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fabian Perez, Jhon Lopez, Henry Arguello</p>
    <p><b>Summary:</b> In the era of cloud computing and data-driven applications, it is crucial to
protect sensitive information to maintain data privacy, ensuring truly reliable
systems. As a result, preserving privacy in deep learning systems has become a
critical concern. Existing methods for privacy preservation rely on image
encryption or perceptual transformation approaches. However, they often suffer
from reduced task performance and high computational costs. To address these
challenges, we propose a novel Privacy-Preserving framework that uses a set of
deformable operators for secure task learning. Our method involves shuffling
pixels during the analog-to-digital conversion process to generate visually
protected data. Those are then fed into a well-known network enhanced with
deformable operators. Using our approach, users can achieve equivalent
performance to original images without additional training using a secret key.
Moreover, our method enables access control against unauthorized users.
Experimental results demonstrate the efficacy of our approach, showcasing its
potential in cloud-based scenarios and privacy-sensitive applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.05598v1">Hook-in Privacy Techniques for gRPC-based Microservice Communication</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2024-04-08T15:18:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Louis Loechel, Siar-Remzi Akbayin, Elias Grünewald, Jannis Kiesel, Inga Strelnikova, Thomas Janke, Frank Pallas</p>
    <p><b>Summary:</b> gRPC is at the heart of modern distributed system architectures. Based on
HTTP/2 and Protocol Buffers, it provides highly performant, standardized, and
polyglot communication across loosely coupled microservices and is increasingly
preferred over REST- or GraphQL-based service APIs in practice. Despite its
widespread adoption, gRPC lacks any advanced privacy techniques beyond
transport encryption and basic token-based authentication. Such advanced
techniques are, however, increasingly important for fulfilling regulatory
requirements. For instance, anonymizing or otherwise minimizing (personal) data
before responding to requests, or pre-processing data based on the purpose of
the access may be crucial in certain usecases. In this paper, we therefore
propose a novel approach for integrating such advanced privacy techniques into
the gRPC framework in a practically viable way. Specifically, we present a
general approach along with a working prototype that implements privacy
techniques, such as data minimization and purpose limitation, in a
configurable, extensible, and gRPC-native way utilizing a gRPC interceptor. We
also showcase how to integrate this contribution into a realistic example of a
food delivery use case. Alongside these implementations, a preliminary
performance evaluation shows practical applicability with reasonable overheads.
Altogether, we present a viable solution for integrating advanced privacy
techniques into real-world gRPC-based microservice architectures, thereby
facilitating regulatory compliance ``by design''.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.05257v1">Sensing-Resistance-Oriented Beamforming for Privacy Protection from ISAC
  Devices</a></h3>
  
  <p><b>Published on:</b> 2024-04-08T07:45:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Teng Ma, Yue Xiao, Xia Lei, Ming Xiao</p>
    <p><b>Summary:</b> With the evolution of integrated sensing and communication (ISAC) technology,
a growing number of devices go beyond conventional communication functions with
sensing abilities. Therefore, future networks are divinable to encounter new
privacy concerns on sensing, such as the exposure of position information to
unintended receivers. In contrast to traditional privacy preserving schemes
aiming to prevent eavesdropping, this contribution conceives a novel
beamforming design toward sensing resistance (SR). Specifically, we expect to
guarantee the communication quality while masking the real direction of the SR
transmitter during the communication. To evaluate the SR performance, a metric
termed angular-domain peak-to-average ratio (ADPAR) is first defined and
analyzed. Then, we resort to the null-space technique to conceal the real
direction, hence to convert the optimization problem to a more tractable form.
Moreover, semidefinite relaxation along with index optimization is further
utilized to obtain the optimal beamformer. Finally, simulation results
demonstrate the feasibility of the proposed SR-oriented beamforming design
toward privacy protection from ISAC receivers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.05130v1">Enabling Privacy-Preserving Cyber Threat Detection with Federated
  Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-04-08T01:16:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yu Bi, Yekai Li, Xuan Feng, Xianghang Mi</p>
    <p><b>Summary:</b> Despite achieving good performance and wide adoption, machine learning based
security detection models (e.g., malware classifiers) are subject to concept
drift and evasive evolution of attackers, which renders up-to-date threat data
as a necessity. However, due to enforcement of various privacy protection
regulations (e.g., GDPR), it is becoming increasingly challenging or even
prohibitive for security vendors to collect individual-relevant and
privacy-sensitive threat datasets, e.g., SMS spam/non-spam messages from mobile
devices. To address such obstacles, this study systematically profiles the
(in)feasibility of federated learning for privacy-preserving cyber threat
detection in terms of effectiveness, byzantine resilience, and efficiency. This
is made possible by the build-up of multiple threat datasets and threat
detection models, and more importantly, the design of realistic and
security-specific experiments.
  We evaluate FL on two representative threat detection tasks, namely SMS spam
detection and Android malware detection. It shows that FL-trained detection
models can achieve a performance that is comparable to centrally trained
counterparts. Also, most non-IID data distributions have either minor or
negligible impact on the model performance, while a label-based non-IID
distribution of a high extent can incur non-negligible fluctuation and delay in
FL training. Then, under a realistic threat model, FL turns out to be
adversary-resistant to attacks of both data poisoning and model poisoning.
Particularly, the attacking impact of a practical data poisoning attack is no
more than 0.14\% loss in model accuracy. Regarding FL efficiency, a
bootstrapping strategy turns out to be effective to mitigate the training delay
as observed in label-based non-IID scenarios.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.05049v1">PlateSegFL: A Privacy-Preserving License Plate Detection Using Federated
  Segmentation Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-04-07T19:10:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Md. Shahriar Rahman Anuvab, Mishkat Sultana, Md. Atif Hossain, Shashwata Das, Suvarthi Chowdhury, Rafeed Rahman, Dibyo Fabian Dofadar, Shahriar Rahman Rana</p>
    <p><b>Summary:</b> Automatic License Plate Recognition (ALPR) is an integral component of an
intelligent transport system with extensive applications in secure
transportation, vehicle-to-vehicle communication, stolen vehicles detection,
traffic violations, and traffic flow management. The existing license plate
detection system focuses on one-shot learners or pre-trained models that
operate with a geometric bounding box, limiting the model's performance.
Furthermore, continuous video data streams uploaded to the central server
result in network and complexity issues. To combat this, PlateSegFL was
introduced, which implements U-Net-based segmentation along with Federated
Learning (FL). U-Net is well-suited for multi-class image segmentation tasks
because it can analyze a large number of classes and generate a pixel-level
segmentation map for each class. Federated Learning is used to reduce the
quantity of data required while safeguarding the user's privacy. Different
computing platforms, such as mobile phones, are able to collaborate on the
development of a standard prediction model where it makes efficient use of
one's time; incorporates more diverse data; delivers projections in real-time;
and requires no physical effort from the user; resulting around 95% F1 score.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.05047v1">Initial Exploration of Zero-Shot Privacy Utility Tradeoffs in Tabular
  Data Using GPT-4</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-04-07T19:02:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bishwas Mandal, George Amariucai, Shuangqing Wei</p>
    <p><b>Summary:</b> We investigate the application of large language models (LLMs), specifically
GPT-4, to scenarios involving the tradeoff between privacy and utility in
tabular data. Our approach entails prompting GPT-4 by transforming tabular data
points into textual format, followed by the inclusion of precise sanitization
instructions in a zero-shot manner. The primary objective is to sanitize the
tabular data in such a way that it hinders existing machine learning models
from accurately inferring private features while allowing models to accurately
infer utility-related attributes. We explore various sanitization instructions.
Notably, we discover that this relatively simple approach yields performance
comparable to more complex adversarial optimization methods used for managing
privacy-utility tradeoffs. Furthermore, while the prompts successfully obscure
private features from the detection capabilities of existing machine learning
models, we observe that this obscuration alone does not necessarily meet a
range of fairness metrics. Nevertheless, our research indicates the potential
effectiveness of LLMs in adhering to these fairness metrics, with some of our
experimental results aligning with those achieved by well-established
adversarial optimization techniques.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.05043v1">Optimizing Privacy and Utility Tradeoffs for Group Interests Through
  Harmonization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-04-07T18:55:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bishwas Mandal, George Amariucai, Shuangqing Wei</p>
    <p><b>Summary:</b> We propose a novel problem formulation to address the privacy-utility
tradeoff, specifically when dealing with two distinct user groups characterized
by unique sets of private and utility attributes. Unlike previous studies that
primarily focus on scenarios where all users share identical private and
utility attributes and often rely on auxiliary datasets or manual annotations,
we introduce a collaborative data-sharing mechanism between two user groups
through a trusted third party. This third party uses adversarial privacy
techniques with our proposed data-sharing mechanism to internally sanitize data
for both groups and eliminates the need for manual annotation or auxiliary
datasets. Our methodology ensures that private attributes cannot be accurately
inferred while enabling highly accurate predictions of utility features.
Importantly, even if analysts or adversaries possess auxiliary datasets
containing raw data, they are unable to accurately deduce private features.
Additionally, our data-sharing mechanism is compatible with various existing
adversarially trained privacy techniques. We empirically demonstrate the
effectiveness of our approach using synthetic and real-world datasets,
showcasing its ability to balance the conflicting goals of privacy and utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.04861v2">Privacy-Preserving Traceable Functional Encryption for Inner Product</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-04-07T08:09:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Muyao Qiu, Jinguang Han</p>
    <p><b>Summary:</b> Functional encryption introduces a new paradigm of public key encryption that
decryption only reveals the function value of encrypted data. To curb key
leakage issues and trace users in FE-IP, a new primitive called traceable
functional encryption for inner product (TFE-IP) has been proposed. However,
the privacy protection of user's identities has not been considered in the
existing TFE-IP schemes. In order to balance privacy and accountability, we
propose the concept of privacy-preserving traceable functional encryption for
inner product (PPTFE-IP) and give a concrete construction. Our scheme provides
the following features: (1) To prevent key sharing, a user's key is bound with
both his/her identity and a vector; (2) The key generation center (KGC) and a
user execute a two-party secure computing protocol to generate a key without
the former knowing anything about the latter's identity; (3) Each user can
verify the correctness of his/her key; (4) A user can calculate the inner
product of the two vectors embedded in his/her key and in a ciphertext; (5)
Only the tracer can trace the identity embedded in a key. The security of our
scheme is formally reduced to well-known complexity assumptions, and the
implementation is conducted to evaluate its efficiency. The novelty of our
scheme is to protect users' privacy and provide traceability if required.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.04769v1">Safeguarding Voice Privacy: Harnessing Near-Ultrasonic Interference To
  Protect Against Unauthorized Audio Recording</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-04-07T00:49:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Forrest McKee, David Noever</p>
    <p><b>Summary:</b> The widespread adoption of voice-activated systems has modified routine
human-machine interaction but has also introduced new vulnerabilities. This
paper investigates the susceptibility of automatic speech recognition (ASR)
algorithms in these systems to interference from near-ultrasonic noise.
Building upon prior research that demonstrated the ability of near-ultrasonic
frequencies (16 kHz - 22 kHz) to exploit the inherent properties of
microelectromechanical systems (MEMS) microphones, our study explores
alternative privacy enforcement means using this interference phenomenon. We
expose a critical vulnerability in the most common microphones used in modern
voice-activated devices, which inadvertently demodulate near-ultrasonic
frequencies into the audible spectrum, disrupting the ASR process. Through a
systematic analysis of the impact of near-ultrasonic noise on various ASR
systems, we demonstrate that this vulnerability is consistent across different
devices and under varying conditions, such as broadcast distance and specific
phoneme structures. Our findings highlight the need to develop robust
countermeasures to protect voice-activated systems from malicious exploitation
of this vulnerability. Furthermore, we explore the potential applications of
this phenomenon in enhancing privacy by disrupting unauthorized audio recording
or eavesdropping. This research underscores the importance of a comprehensive
approach to securing voice-activated systems, combining technological
innovation, responsible development practices, and informed policy decisions to
ensure the privacy and security of users in an increasingly connected world.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.04706v1">Advances in Differential Privacy and Differentially Private Machine
  Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-04-06T18:49:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Saswat Das, Subhankar Mishra</p>
    <p><b>Summary:</b> There has been an explosion of research on differential privacy (DP) and its
various applications in recent years, ranging from novel variants and
accounting techniques in differential privacy to the thriving field of
differentially private machine learning (DPML) to newer implementations in
practice, like those by various companies and organisations such as census
bureaus. Most recent surveys focus on the applications of differential privacy
in particular contexts like data publishing, specific machine learning tasks,
analysis of unstructured data, location privacy, etc. This work thus seeks to
fill the gap for a survey that primarily discusses recent developments in the
theory of differential privacy along with newer DP variants, viz. Renyi DP and
Concentrated DP, novel mechanisms and techniques, and the theoretical
developments in differentially private machine learning in proper detail. In
addition, this survey discusses its applications to privacy-preserving machine
learning in practice and a few practical implementations of DP.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.04098v1">You Can Use But Cannot Recognize: Preserving Visual Privacy in Deep
  Neural Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-04-05T13:49:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qiushi Li, Yan Zhang, Ju Ren, Qi Li, Yaoxue Zhang</p>
    <p><b>Summary:</b> Image data have been extensively used in Deep Neural Network (DNN) tasks in
various scenarios, e.g., autonomous driving and medical image analysis, which
incurs significant privacy concerns. Existing privacy protection techniques are
unable to efficiently protect such data. For example, Differential Privacy (DP)
that is an emerging technique protects data with strong privacy guarantee
cannot effectively protect visual features of exposed image dataset. In this
paper, we propose a novel privacy-preserving framework VisualMixer that
protects the training data of visual DNN tasks by pixel shuffling, while not
injecting any noises. VisualMixer utilizes a new privacy metric called Visual
Feature Entropy (VFE) to effectively quantify the visual features of an image
from both biological and machine vision aspects. In VisualMixer, we devise a
task-agnostic image obfuscation method to protect the visual privacy of data
for DNN training and inference. For each image, it determines regions for pixel
shuffling in the image and the sizes of these regions according to the desired
VFE. It shuffles pixels both in the spatial domain and in the chromatic channel
space in the regions without injecting noises so that it can prevent visual
features from being discerned and recognized, while incurring negligible
accuracy loss. Extensive experiments on real-world datasets demonstrate that
VisualMixer can effectively preserve the visual privacy with negligible
accuracy loss, i.e., at average 2.35 percentage points of model accuracy loss,
and almost no performance degradation on model training.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.04006v1">From Theory to Comprehension: A Comparative Study of Differential
  Privacy and $k$-Anonymity</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-04-05T10:30:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Saskia Nuñez von Voigt, Luise Mehner, Florian Tschorsch</p>
    <p><b>Summary:</b> The notion of $\varepsilon$-differential privacy is a widely used concept of
providing quantifiable privacy to individuals. However, it is unclear how to
explain the level of privacy protection provided by a differential privacy
mechanism with a set $\varepsilon$. In this study, we focus on users'
comprehension of the privacy protection provided by a differential privacy
mechanism. To do so, we study three variants of explaining the privacy
protection provided by differential privacy: (1) the original mathematical
definition; (2) $\varepsilon$ translated into a specific privacy risk; and (3)
an explanation using the randomized response technique. We compare users'
comprehension of privacy protection employing these explanatory models with
their comprehension of privacy protection of $k$-anonymity as baseline
comprehensibility. Our findings suggest that participants' comprehension of
differential privacy protection is enhanced by the privacy risk model and the
randomized response-based model. Moreover, our results confirm our intuition
that privacy protection provided by $k$-anonymity is more comprehensible.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.03873v1">PrivShape: Extracting Shapes in Time Series under User-Level Local
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-04-05T03:22:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yulian Mao, Qingqing Ye, Haibo Hu, Qi Wang, Kai Huang</p>
    <p><b>Summary:</b> Time series have numerous applications in finance, healthcare, IoT, and smart
city. In many of these applications, time series typically contain personal
data, so privacy infringement may occur if they are released directly to the
public. Recently, local differential privacy (LDP) has emerged as the
state-of-the-art approach to protecting data privacy. However, existing works
on LDP-based collections cannot preserve the shape of time series. A recent
work, PatternLDP, attempts to address this problem, but it can only protect a
finite group of elements in a time series due to {\omega}-event level privacy
guarantee. In this paper, we propose PrivShape, a trie-based mechanism under
user-level LDP to protect all elements. PrivShape first transforms a time
series to reduce its length, and then adopts trie-expansion and two-level
refinement to improve utility. By extensive experiments on real-world datasets,
we demonstrate that PrivShape outperforms PatternLDP when adapted for offline
use, and can effectively extract frequent shapes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.03524v1">Approximate Gradient Coding for Privacy-Flexible Federated Learning with
  Non-IID Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">  
  <p><b>Published on:</b> 2024-04-04T15:29:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Okko Makkonen, Sampo Niemelä, Camilla Hollanti, Serge Kas Hanna</p>
    <p><b>Summary:</b> This work focuses on the challenges of non-IID data and stragglers/dropouts
in federated learning. We introduce and explore a privacy-flexible paradigm
that models parts of the clients' local data as non-private, offering a more
versatile and business-oriented perspective on privacy. Within this framework,
we propose a data-driven strategy for mitigating the effects of label
heterogeneity and client straggling on federated learning. Our solution
combines both offline data sharing and approximate gradient coding techniques.
Through numerical simulations using the MNIST dataset, we demonstrate that our
approach enables achieving a deliberate trade-off between privacy and utility,
leading to improved model convergence and accuracy while using an adaptable
portion of non-private data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.03514v1">Learn When (not) to Trust Language Models: A Privacy-Centric Adaptive
  Model-Aware Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-04-04T15:21:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chengkai Huang, Rui Wang, Kaige Xie, Tong Yu, Lina Yao</p>
    <p><b>Summary:</b> Retrieval-augmented large language models (LLMs) have been remarkably
competent in various NLP tasks. Despite their great success, the knowledge
provided by the retrieval process is not always useful for improving the model
prediction, since in some samples LLMs may already be quite knowledgeable and
thus be able to answer the question correctly without retrieval. Aiming to save
the cost of retrieval, previous work has proposed to determine when to do/skip
the retrieval in a data-aware manner by analyzing the LLMs' pretraining data.
However, these data-aware methods pose privacy risks and memory limitations,
especially when requiring access to sensitive or extensive pretraining data.
Moreover, these methods offer limited adaptability under fine-tuning or
continual learning settings. We hypothesize that token embeddings are able to
capture the model's intrinsic knowledge, which offers a safer and more
straightforward way to judge the need for retrieval without the privacy risks
associated with accessing pre-training data. Moreover, it alleviates the need
to retain all the data utilized during model pre-training, necessitating only
the upkeep of the token embeddings. Extensive experiments and in-depth analyses
demonstrate the superiority of our model-aware approach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.03509v1">Privacy-Enhancing Technologies for Artificial Intelligence-Enabled
  Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-04-04T15:14:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Liv d'Aliberti, Evan Gronberg, Joseph Kovba</p>
    <p><b>Summary:</b> Artificial intelligence (AI) models introduce privacy vulnerabilities to
systems. These vulnerabilities may impact model owners or system users; they
exist during model development, deployment, and inference phases, and threats
can be internal or external to the system. In this paper, we investigate
potential threats and propose the use of several privacy-enhancing technologies
(PETs) to defend AI-enabled systems. We then provide a framework for PETs
evaluation for a AI-enabled systems and discuss the impact PETs may have on
system-level variables.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.03442v1">Privacy Engineering From Principles to Practice: A Roadmap</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> 
  <p><b>Published on:</b> 2024-04-04T13:39:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Frank Pallas, Katharina Koerner, Isabel Barberá, Jaap-Henk Hoepman, Meiko Jensen, Nandita Rao Narla, Nikita Samarin, Max-R. Ulbricht, Isabel Wagner, Kim Wuyts, Christian Zimmermann</p>
    <p><b>Summary:</b> Privacy engineering is gaining momentum in industry and academia alike. So
far, manifold low-level primitives and higher-level methods and strategies have
successfully been established. Still, fostering adoption in real-world
information systems calls for additional aspects to be consciously considered
in research and practice.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.03324v1">A Comparative Analysis of Word-Level Metric Differential Privacy:
  Benchmarking The Privacy-Utility Trade-off</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-04-04T09:48:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stephen Meisenbacher, Nihildev Nandakumar, Alexandra Klymenko, Florian Matthes</p>
    <p><b>Summary:</b> The application of Differential Privacy to Natural Language Processing
techniques has emerged in relevance in recent years, with an increasing number
of studies published in established NLP outlets. In particular, the adaptation
of Differential Privacy for use in NLP tasks has first focused on the
$\textit{word-level}$, where calibrated noise is added to word embedding
vectors to achieve "noisy" representations. To this end, several
implementations have appeared in the literature, each presenting an alternative
method of achieving word-level Differential Privacy. Although each of these
includes its own evaluation, no comparative analysis has been performed to
investigate the performance of such methods relative to each other. In this
work, we conduct such an analysis, comparing seven different algorithms on two
NLP tasks with varying hyperparameters, including the $\textit{epsilon
($\varepsilon$)}$ parameter, or privacy budget. In addition, we provide an
in-depth analysis of the results with a focus on the privacy-utility trade-off,
as well as open-source our implementation code for further reproduction. As a
result of our analysis, we give insight into the benefits and challenges of
word-level Differential Privacy, and accordingly, we suggest concrete steps
forward for the research field.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.03165v2">Towards Collaborative Family-Centered Design for Online Safety, Privacy
  and Security</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-04-04T02:34:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mamtaj Akter, Zainab Agha, Ashwaq Alsoubai, Naima Ali, Pamela Wisniewski</p>
    <p><b>Summary:</b> Traditional online safety technologies often overly restrict teens and invade
their privacy, while parents often lack knowledge regarding their digital
privacy. As such, prior researchers have called for more collaborative
approaches on adolescent online safety and networked privacy. In this paper, we
propose family-centered approaches to foster parent-teen collaboration in
ensuring their mobile privacy and online safety while respecting individual
privacy, to enhance open discussion and teens' self-regulation. However,
challenges such as power imbalances and conflicts with family values arise when
implementing such approaches, making parent-teen collaboration difficult.
Therefore, attending the family-centered design workshop will provide an
invaluable opportunity for us to discuss these challenges and identify best
research practices for the future of collaborative online safety and privacy
within families.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.02696v1">Deep Privacy Funnel Model: From a Discriminative to a Generative
  Approach with an Application to Face Recognition</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-04-03T12:50:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Behrooz Razeghi, Parsa Rahimi, Sébastien Marcel</p>
    <p><b>Summary:</b> In this study, we apply the information-theoretic Privacy Funnel (PF) model
to the domain of face recognition, developing a novel method for
privacy-preserving representation learning within an end-to-end training
framework. Our approach addresses the trade-off between obfuscation and utility
in data protection, quantified through logarithmic loss, also known as
self-information loss. This research provides a foundational exploration into
the integration of information-theoretic privacy principles with representation
learning, focusing specifically on the face recognition systems. We
particularly highlight the adaptability of our framework with recent
advancements in face recognition networks, such as AdaFace and ArcFace. In
addition, we introduce the Generative Privacy Funnel ($\mathsf{GenPF}$) model,
a paradigm that extends beyond the traditional scope of the PF model, referred
to as the Discriminative Privacy Funnel ($\mathsf{DisPF}$). This
$\mathsf{GenPF}$ model brings new perspectives on data generation methods with
estimation-theoretic and information-theoretic privacy guarantees.
Complementing these developments, we also present the deep variational PF
(DVPF) model. This model proposes a tractable variational bound for measuring
information leakage, enhancing the understanding of privacy preservation
challenges in deep representation learning. The DVPF model, associated with
both $\mathsf{DisPF}$ and $\mathsf{GenPF}$ models, sheds light on connections
with various generative models such as Variational Autoencoders (VAEs),
Generative Adversarial Networks (GANs), and Diffusion models. Complementing our
theoretical contributions, we release a reproducible PyTorch package,
facilitating further exploration and application of these privacy-preserving
methodologies in face recognition systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2404.02327v1">Robust Constrained Consensus and Inequality-constrained Distributed
  Optimization with Guaranteed Differential Privacy and Accurate Convergence</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36"> 
  <p><b>Published on:</b> 2024-04-02T21:53:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yongqiang Wang, Angelia Nedic</p>
    <p><b>Summary:</b> We address differential privacy for fully distributed optimization subject to
a shared inequality constraint. By co-designing the distributed optimization
mechanism and the differential-privacy noise injection mechanism, we propose
the first distributed constrained optimization algorithm that can ensure both
provable convergence to a global optimal solution and rigorous
$\epsilon$-differential privacy, even when the number of iterations tends to
infinity. Our approach does not require the Lagrangian function to be strictly
convex/concave, and allows the global objective function to be non-separable.
As a byproduct of the co-design, we also propose a new constrained consensus
algorithm that can achieve rigorous $\epsilon$-differential privacy while
maintaining accurate convergence, which, to our knowledge, has not been
achieved before. Numerical simulation results on a demand response control
problem in smart grid confirm the effectiveness of the proposed approach.</p>
  </details>
</div>


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
  <h3><a href="http://arxiv.org/abs/2403.13041v3">Provable Privacy with Non-Private Pre-Processing</a></h3>
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

