
<h2>2025-06</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.21308v1">Balancing Privacy and Utility in Correlated Data: A Study of Bayesian
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">  
  <p><b>Published on:</b> 2025-06-26T14:25:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Martin Lange, Patricia Guerra-Balboa, Javier Parra-Arnau, Thorsten Strufe</p>
    <p><b>Summary:</b> Privacy risks in differentially private (DP) systems increase significantly
when data is correlated, as standard DP metrics often underestimate the
resulting privacy leakage, leaving sensitive information vulnerable. Given the
ubiquity of dependencies in real-world databases, this oversight poses a
critical challenge for privacy protections. Bayesian differential privacy (BDP)
extends DP to account for these correlations, yet current BDP mechanisms
indicate notable utility loss, limiting its adoption.
  In this work, we address whether BDP can be realistically implemented in
common data structures without sacrificing utility -- a key factor for its
applicability. By analyzing arbitrary and structured correlation models,
including Gaussian multivariate distributions and Markov chains, we derive
practical utility guarantees for BDP. Our contributions include theoretical
links between DP and BDP and a novel methodology for adapting DP mechanisms to
meet the BDP requirements. Through evaluations on real-world databases, we
demonstrate that our novel theorems enable the design of BDP mechanisms that
maintain competitive utility, paving the way for practical privacy-preserving
data practices in correlated settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.20981v1">PrivacyGo: Privacy-Preserving Ad Measurement with Multidimensional
  Intersection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-26T03:54:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jian Du, Haohao Qian, Shikun Zhang, Wen-jie Lu, Donghang Lu, Yongchuan Niu, Bo Jiang, Yongjun Zhao, Qiang Yan</p>
    <p><b>Summary:</b> This paper tackles the challenging and practical problem of multi-identifier
private user profile matching for privacy-preserving ad measurement, a
cornerstone of modern advertising analytics. We introduce a comprehensive
cryptographic framework leveraging reversed Oblivious Pseudorandom Functions
(OPRF) and novel blind key rotation techniques to support secure matching
across multiple identifiers. Our design prevents cross-identifier linkages and
includes a differentially private mechanism to obfuscate intersection sizes,
mitigating risks such as membership inference attacks.
  We present a concrete construction of our protocol that achieves both strong
privacy guarantees and high efficiency. It scales to large datasets, offering a
practical and scalable solution for privacy-centric applications like secure ad
conversion tracking. By combining rigorous cryptographic principles with
differential privacy, our work addresses a critical need in the advertising
industry, setting a new standard for privacy-preserving ad measurement
frameworks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.20872v1">Empowering Digital Agriculture: A Privacy-Preserving Framework for Data
  Sharing and Collaborative Research</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-25T22:46:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Osama Zafar, Rosemarie Santa González, Mina Namazi, Alfonso Morales, Erman Ayday</p>
    <p><b>Summary:</b> Data-driven agriculture, which integrates technology and data into
agricultural practices, has the potential to improve crop yield, disease
resilience, and long-term soil health. However, privacy concerns, such as
adverse pricing, discrimination, and resource manipulation, deter farmers from
sharing data, as it can be used against them. To address this barrier, we
propose a privacy-preserving framework that enables secure data sharing and
collaboration for research and development while mitigating privacy risks. The
framework combines dimensionality reduction techniques (like Principal
Component Analysis (PCA)) and differential privacy by introducing Laplacian
noise to protect sensitive information. The proposed framework allows
researchers to identify potential collaborators for a target farmer and train
personalized machine learning models either on the data of identified
collaborators via federated learning or directly on the aggregated
privacy-protected data. It also allows farmers to identify potential
collaborators based on similarities. We have validated this on real-life
datasets, demonstrating robust privacy protection against adversarial attacks
and utility performance comparable to a centralized system. We demonstrate how
this framework can facilitate collaboration among farmers and help researchers
pursue broader research objectives. The adoption of the framework can empower
researchers and policymakers to leverage agricultural data responsibly, paving
the way for transformative advances in data-driven agriculture. By addressing
critical privacy challenges, this work supports secure data integration,
fostering innovation and sustainability in agricultural systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.20737v1">MAGPIE: A dataset for Multi-AGent contextual PrIvacy Evaluation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-06-25T18:04:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gurusha Juneja, Alon Albalak, Wenyue Hua, William Yang Wang</p>
    <p><b>Summary:</b> The proliferation of LLM-based agents has led to increasing deployment of
inter-agent collaboration for tasks like scheduling, negotiation, resource
allocation etc. In such systems, privacy is critical, as agents often access
proprietary tools and domain-specific databases requiring strict
confidentiality. This paper examines whether LLM-based agents demonstrate an
understanding of contextual privacy. And, if instructed, do these systems
preserve inference time user privacy in non-adversarial multi-turn
conversation. Existing benchmarks to evaluate contextual privacy in LLM-agents
primarily assess single-turn, low-complexity tasks where private information
can be easily excluded. We first present a benchmark - MAGPIE comprising 158
real-life high-stakes scenarios across 15 domains. These scenarios are designed
such that complete exclusion of private data impedes task completion yet
unrestricted information sharing could lead to substantial losses. We then
evaluate the current state-of-the-art LLMs on (a) their understanding of
contextually private data and (b) their ability to collaborate without
violating user privacy. Empirical experiments demonstrate that current models,
including GPT-4o and Claude-2.7-Sonnet, lack robust understanding of contextual
privacy, misclassifying private data as shareable 25.2\% and 43.6\% of the
time. In multi-turn conversations, these models disclose private information in
59.9\% and 50.5\% of cases even under explicit privacy instructions.
Furthermore, multi-agent systems fail to complete tasks in 71\% of scenarios.
These results underscore that current models are not aligned towards both
contextual privacy preservation and collaborative task-solving.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.20463v1">Analyzing Security and Privacy Challenges in Generative AI Usage
  Guidelines for Higher Education</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-06-25T14:12:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bei Yi Ng, Jiarui Li, Xinyuan Tong, Kevin Ye, Gauthami Yenne, Varun Chandrasekaran, Jingjie Li</p>
    <p><b>Summary:</b> Educators and learners worldwide are embracing the rise of Generative
Artificial Intelligence (GenAI) as it reshapes higher education. However, GenAI
also raises significant privacy and security concerns, as models and
privacy-sensitive user data, such as student records, may be misused by service
providers. Unfortunately, end-users often have little awareness of or control
over how these models operate. To address these concerns, universities are
developing institutional policies to guide GenAI use while safeguarding
security and privacy. This work examines these emerging policies and
guidelines, with a particular focus on the often-overlooked privacy and
security dimensions of GenAI integration in higher education, alongside other
academic values. Through a qualitative analysis of GenAI usage guidelines from
universities across 12 countries, we identify key challenges and opportunities
institutions face in providing effective privacy and security protections,
including the need for GenAI safeguards tailored specifically to the academic
context.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.20413v1">Client Clustering Meets Knowledge Sharing: Enhancing Privacy and
  Robustness in Personalized Peer-to-Peer Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-25T13:27:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohammad Mahdi Maheri, Denys Herasymuk, Hamed Haddadi</p>
    <p><b>Summary:</b> The growing adoption of Artificial Intelligence (AI) in Internet of Things
(IoT) ecosystems has intensified the need for personalized learning methods
that can operate efficiently and privately across heterogeneous,
resource-constrained devices. However, enabling effective personalized learning
in decentralized settings introduces several challenges, including efficient
knowledge transfer between clients, protection of data privacy, and resilience
against poisoning attacks. In this paper, we address these challenges by
developing P4 (Personalized, Private, Peer-to-Peer) -- a method designed to
deliver personalized models for resource-constrained IoT devices while ensuring
differential privacy and robustness against poisoning attacks. Our solution
employs a lightweight, fully decentralized algorithm to privately detect client
similarity and form collaborative groups. Within each group, clients leverage
differentially private knowledge distillation to co-train their models,
maintaining high accuracy while ensuring robustness to the presence of
malicious clients. We evaluate P4 on popular benchmark datasets using both
linear and CNN-based architectures across various heterogeneity settings and
attack scenarios. Experimental results show that P4 achieves 5% to 30% higher
accuracy than leading differentially private peer-to-peer approaches and
maintains robustness with up to 30% malicious clients. Additionally, we
demonstrate its practicality by deploying it on resource-constrained devices,
where collaborative training between two clients adds only ~7 seconds of
overhead.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.20290v1">Don't Hash Me Like That: Exposing and Mitigating Hash-Induced Unfairness
  in Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-25T09:48:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Berkay Kemal Balioglu, Alireza Khodaie, Mehmet Emre Gursoy</p>
    <p><b>Summary:</b> Local differential privacy (LDP) has become a widely accepted framework for
privacy-preserving data collection. In LDP, many protocols rely on hash
functions to implement user-side encoding and perturbation. However, the
security and privacy implications of hash function selection have not been
previously investigated. In this paper, we expose that the hash functions may
act as a source of unfairness in LDP protocols. We show that although users
operate under the same protocol and privacy budget, differences in hash
functions can lead to significant disparities in vulnerability to inference and
poisoning attacks. To mitigate hash-induced unfairness, we propose Fair-OLH
(F-OLH), a variant of OLH that enforces an entropy-based fairness constraint on
hash function selection. Experiments show that F-OLH is effective in mitigating
hash-induced unfairness under acceptable time overheads.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.20234v1">Communication-Efficient Publication of Sparse Vectors under Differential
  Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-25T08:25:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Quentin Hillebrand, Vorapong Suppakitpaisarn, Tetsuo Shibuya</p>
    <p><b>Summary:</b> In this work, we propose a differentially private algorithm for publishing
matrices aggregated from sparse vectors. These matrices include social network
adjacency matrices, user-item interaction matrices in recommendation systems,
and single nucleotide polymorphisms (SNPs) in DNA data. Traditionally,
differential privacy in vector collection relies on randomized response, but
this approach incurs high communication costs. Specifically, for a matrix with
$N$ users, $n$ columns, and $m$ nonzero elements, conventional methods require
$\Omega(n \times N)$ communication, making them impractical for large-scale
data. Our algorithm significantly reduces this cost to $O(\varepsilon m)$,
where $\varepsilon$ is the privacy budget. Notably, this is even lower than the
non-private case, which requires $\Omega(m \log n)$ communication. Moreover, as
the privacy budget decreases, communication cost further reduces, enabling
better privacy with improved efficiency. We theoretically prove that our method
yields results identical to those of randomized response, and experimental
evaluations confirm its effectiveness in terms of accuracy, communication
efficiency, and computational complexity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.20207v1">User Understanding of Privacy Permissions in Mobile Augmented Reality:
  Perceptions and Misconceptions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-06-25T07:52:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Viktorija Paneva, Verena Winterhalter, Franziska Augustinowski, Florian Alt</p>
    <p><b>Summary:</b> Mobile Augmented Reality (AR) applications leverage various sensors to
provide immersive user experiences. However, their reliance on diverse data
sources introduces significant privacy challenges. This paper investigates user
perceptions and understanding of privacy permissions in mobile AR apps through
an analysis of existing applications and an online survey of 120 participants.
Findings reveal common misconceptions, including confusion about how
permissions relate to specific AR functionalities (e.g., location and
measurement of physical distances), and misinterpretations of permission labels
(e.g., conflating camera and gallery access). We identify a set of actionable
implications for designing more usable and transparent privacy mechanisms
tailored to mobile AR technologies, including contextual explanations, modular
permission requests, and clearer permission labels. These findings offer
actionable guidance for developers, researchers, and policymakers working to
enhance privacy frameworks in mobile AR.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.20101v1">Secure Multi-Key Homomorphic Encryption with Application to
  Privacy-Preserving Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-25T03:28:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiahui Wu, Tiecheng Sun, Fucai Luo, Haiyan Wang, Weizhe Zhang</p>
    <p><b>Summary:</b> Multi-Key Homomorphic Encryption (MKHE), proposed by Lopez-Alt et al. (STOC
2012), allows for performing arithmetic computations directly on ciphertexts
encrypted under distinct keys. Subsequent works by Chen and Dai et al. (CCS
2019) and Kim and Song et al. (CCS 2023) extended this concept by proposing
multi-key BFV/CKKS variants, referred to as the CDKS scheme. These variants
incorporate asymptotically optimal techniques to facilitate secure computation
across multiple data providers. In this paper, we identify a critical security
vulnerability in the CDKS scheme when applied to multiparty secure computation
tasks, such as privacy-preserving federated learning (PPFL). In particular, we
show that CDKS may inadvertently leak plaintext information from one party to
others. To mitigate this issue, we propose a new scheme, SMHE (Secure Multi-Key
Homomorphic Encryption), which incorporates a novel masking mechanism into the
multi-key BFV and CKKS frameworks to ensure that plaintexts remain confidential
throughout the computation. We implement a PPFL application using SMHE and
demonstrate that it provides significantly improved security with only a modest
overhead in homomorphic evaluation. For instance, our PPFL model based on
multi-key CKKS incurs less than a 2\times runtime and communication traffic
increase compared to the CDKS-based PPFL model. The code is publicly available
at https://github.com/JiahuiWu2022/SMHE.git.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.19836v1">Machine Learning with Privacy for Protected Attributes</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-24T17:53:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Saeed Mahloujifar, Chuan Guo, G. Edward Suh, Kamalika Chaudhuri</p>
    <p><b>Summary:</b> Differential privacy (DP) has become the standard for private data analysis.
Certain machine learning applications only require privacy protection for
specific protected attributes. Using naive variants of differential privacy in
such use cases can result in unnecessary degradation of utility. In this work,
we refine the definition of DP to create a more general and flexible framework
that we call feature differential privacy (FDP). Our definition is
simulation-based and allows for both addition/removal and replacement variants
of privacy, and can handle arbitrary and adaptive separation of protected and
non-protected features. We prove the properties of FDP, such as adaptive
composition, and demonstrate its implications for limiting attribute inference
attacks. We also propose a modification of the standard DP-SGD algorithm that
satisfies FDP while leveraging desirable properties such as amplification via
sub-sampling. We apply our framework to various machine learning tasks and show
that it can significantly improve the utility of DP-trained models when public
features are available. For example, we train diffusion models on the AFHQ
dataset of animal faces and observe a drastic improvement in FID compared to
DP, from 286.7 to 101.9 at $\epsilon=8$, assuming that the blurred version of a
training image is available as a public feature. Overall, our work provides a
new approach to private data analysis that can help reduce the utility cost of
DP while still providing strong privacy guarantees.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.19563v1">PrivacyXray: Detecting Privacy Breaches in LLMs through Semantic
  Consistency and Probability Certainty</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-06-24T12:22:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jinwen He, Yiyang Lu, Zijin Lin, Kai Chen, Yue Zhao</p>
    <p><b>Summary:</b> Large Language Models (LLMs) are widely used in sensitive domains, including
healthcare, finance, and legal services, raising concerns about potential
private information leaks during inference. Privacy extraction attacks, such as
jailbreaking, expose vulnerabilities in LLMs by crafting inputs that force the
models to output sensitive information. However, these attacks cannot verify
whether the extracted private information is accurate, as no public datasets
exist for cross-validation, leaving a critical gap in private information
detection during inference. To address this, we propose PrivacyXray, a novel
framework detecting privacy breaches by analyzing LLM inner states. Our
analysis reveals that LLMs exhibit higher semantic coherence and probabilistic
certainty when generating correct private outputs. Based on this, PrivacyXray
detects privacy breaches using four metrics: intra-layer and inter-layer
semantic similarity, token-level and sentence-level probability distributions.
PrivacyXray addresses critical challenges in private information detection by
overcoming the lack of open-source private datasets and eliminating reliance on
external data for validation. It achieves this through the synthesis of
realistic private data and a detection mechanism based on the inner states of
LLMs. Experiments show that PrivacyXray achieves consistent performance, with
an average accuracy of 92.69% across five LLMs. Compared to state-of-the-art
methods, PrivacyXray achieves significant improvements, with an average
accuracy increase of 20.06%, highlighting its stability and practical utility
in real-world applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.19486v1">Recalling The Forgotten Class Memberships: Unlearned Models Can Be Noisy
  Labelers to Leak Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-24T10:21:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhihao Sui, Liang Hu, Jian Cao, Dora D. Liu, Usman Naseem, Zhongyuan Lai, Qi Zhang</p>
    <p><b>Summary:</b> Machine Unlearning (MU) technology facilitates the removal of the influence
of specific data instances from trained models on request. Despite rapid
advancements in MU technology, its vulnerabilities are still underexplored,
posing potential risks of privacy breaches through leaks of ostensibly
unlearned information. Current limited research on MU attacks requires access
to original models containing privacy data, which violates the critical
privacy-preserving objective of MU. To address this gap, we initiate an
innovative study on recalling the forgotten class memberships from unlearned
models (ULMs) without requiring access to the original one. Specifically, we
implement a Membership Recall Attack (MRA) framework with a teacher-student
knowledge distillation architecture, where ULMs serve as noisy labelers to
transfer knowledge to student models. Then, it is translated into a Learning
with Noisy Labels (LNL) problem for inferring the correct labels of the
forgetting instances. Extensive experiments on state-of-the-art MU methods with
multiple real datasets demonstrate that the proposed MRA strategy exhibits high
efficacy in recovering class memberships of unlearned instances. As a result,
our study and evaluation have established a benchmark for future research on MU
vulnerabilities.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.19393v1">ZK-SERIES: Privacy-Preserving Authentication using Temporal Biometric
  Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-24T07:45:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Daniel Reijsbergen, Eyasu Getahun Chekole, Howard Halim, Jianying Zhou</p>
    <p><b>Summary:</b> Biometric authentication relies on physiological or behavioral traits that
are inherent to a user, making them difficult to lose, forge or forget.
Biometric data with a temporal component enable the following authentication
protocol: recent readings of the underlying biometrics are encoded as time
series and compared to a set of base readings. If the distance between the new
readings and the base readings falls within an acceptable threshold, then the
user is successfully authenticated. Various methods exist for comparing time
series data, such as Dynamic Time Warping (DTW) and the Time Warp Edit Distance
(TWED), each offering advantages and drawbacks depending on the context.
Moreover, many of these techniques do not inherently preserve privacy, which is
a critical consideration in biometric authentication due to the complexity of
resetting biometric credentials.
  In this work, we propose ZK-SERIES to provide privacy and efficiency to a
broad spectrum of time series-based authentication protocols. ZK-SERIES uses
the same building blocks, i.e., zero-knowledge multiplication proofs and
efficiently batched range proofs, to ensure consistency across all protocols.
Furthermore, it is optimized for compatibility with low-capacity devices such
as smartphones. To assess the effectiveness of our proposed technique, we
primarily focus on two case studies for biometric authentication: shake-based
and blow-based authentication. To demonstrate ZK-SERIES's practical
applicability even in older and less powerful smartphones, we conduct
experiments on a 5-year-old low-spec smartphone using real data for two case
studies alongside scalability assessments using artificial data. Our
experimental results indicate that the privacy-preserving authentication
protocol can be completed within 1.3 seconds on older devices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.19889v1">Retrieval-Confused Generation is a Good Defender for Privacy Violation
  Attack of Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-06-24T07:28:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wanli Peng, Xin Chen, Hang Fu, XinYu He, Xue Yiming, Juan Wen</p>
    <p><b>Summary:</b> Recent advances in large language models (LLMs) have made a profound impact
on our society and also raised new security concerns. Particularly, due to the
remarkable inference ability of LLMs, the privacy violation attack (PVA),
revealed by Staab et al., introduces serious personal privacy issues. Existing
defense methods mainly leverage LLMs to anonymize the input query, which
requires costly inference time and cannot gain satisfactory defense
performance. Moreover, directly rejecting the PVA query seems like an effective
defense method, while the defense method is exposed, promoting the evolution of
PVA. In this paper, we propose a novel defense paradigm based on
retrieval-confused generation (RCG) of LLMs, which can efficiently and covertly
defend the PVA. We first design a paraphrasing prompt to induce the LLM to
rewrite the "user comments" of the attack query to construct a disturbed
database. Then, we propose the most irrelevant retrieval strategy to retrieve
the desired user data from the disturbed database. Finally, the "data comments"
are replaced with the retrieved user data to form a defended query, leading to
responding to the adversary with some wrong personal attributes, i.e., the
attack fails. Extensive experiments are conducted on two datasets and eight
popular LLMs to comprehensively evaluate the feasibility and the superiority of
the proposed defense method.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.19360v2">SoK: Can Synthetic Images Replace Real Data? A Survey of Utility and
  Privacy of Synthetic Image Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-06-24T06:41:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yunsung Chung, Yunbei Zhang, Nassir Marrouche, Jihun Hamm</p>
    <p><b>Summary:</b> Advances in generative models have transformed the field of synthetic image
generation for privacy-preserving data synthesis (PPDS). However, the field
lacks a comprehensive survey and comparison of synthetic image generation
methods across diverse settings. In particular, when we generate synthetic
images for the purpose of training a classifier, there is a pipeline of
generation-sampling-classification which takes private training as input and
outputs the final classifier of interest. In this survey, we systematically
categorize existing image synthesis methods, privacy attacks, and mitigations
along this generation-sampling-classification pipeline. To empirically compare
diverse synthesis approaches, we provide a benchmark with representative
generative methods and use model-agnostic membership inference attacks (MIAs)
as a measure of privacy risk. Through this study, we seek to answer critical
questions in PPDS: Can synthetic data effectively replace real data? Which
release strategy balances utility and privacy? Do mitigations improve the
utility-privacy tradeoff? Which generative models perform best across different
scenarios? With a systematic evaluation of diverse methods, our study provides
actionable insights into the utility-privacy tradeoffs of synthetic data
generation methods and guides the decision on optimal data releasing strategies
for real-world applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.19268v2">HARPT: A Corpus for Analyzing Consumers' Trust and Privacy Concerns in
  Mobile Health Apps</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-24T02:59:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Timoteo Kelly, Abdulkadir Korkmaz, Samuel Mallet, Connor Souders, Sadra Aliakbarpour, Praveen Rao</p>
    <p><b>Summary:</b> We present HARPT, a large-scale annotated corpus of mobile health app store
reviews aimed at advancing research in user privacy and trust. The dataset
comprises over 480,000 user reviews labeled into seven categories that capture
critical aspects of trust in applications, trust in providers and privacy
concerns. Creating HARPT required addressing multiple complexities, such as
defining a nuanced label schema, isolating relevant content from large volumes
of noisy data, and designing an annotation strategy that balanced scalability
with accuracy. This strategy integrated rule-based filtering, iterative manual
labeling with review, targeted data augmentation, and weak supervision using
transformer-based classifiers to accelerate coverage. In parallel, a carefully
curated subset of 7,000 reviews was manually annotated to support model
development and evaluation. We benchmark a broad range of classification
models, demonstrating that strong performance is achievable and providing a
baseline for future research. HARPT is released as a public resource to support
work in health informatics, cybersecurity, and natural language processing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.19260v1">Network Structures as an Attack Surface: Topology-Based Privacy Leakage
  in Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2025-06-24T02:42:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Murtaza Rangwala, Richard O. Sinnott, Rajkumar Buyya</p>
    <p><b>Summary:</b> Federated learning systems increasingly rely on diverse network topologies to
address scalability and organizational constraints. While existing privacy
research focuses on gradient-based attacks, the privacy implications of network
topology knowledge remain critically understudied. We conduct the first
comprehensive analysis of topology-based privacy leakage across realistic
adversarial knowledge scenarios, demonstrating that adversaries with varying
degrees of structural knowledge can infer sensitive data distribution patterns
even under strong differential privacy guarantees. Through systematic
evaluation of 4,720 attack instances, we analyze six distinct adversarial
knowledge scenarios: complete topology knowledge and five partial knowledge
configurations reflecting real-world deployment constraints. We propose three
complementary attack vectors: communication pattern analysis, parameter
magnitude profiling, and structural position correlation, achieving success
rates of 84.1%, 65.0%, and 47.2% under complete knowledge conditions.
Critically, we find that 80% of realistic partial knowledge scenarios maintain
attack effectiveness above security thresholds, with certain partial knowledge
configurations achieving performance superior to the baseline complete
knowledge scenario. To address these vulnerabilities, we propose and
empirically validate structural noise injection as a complementary defense
mechanism across 808 configurations, demonstrating up to 51.4% additional
attack reduction when properly layered with existing privacy techniques. These
results establish that network topology represents a fundamental privacy
vulnerability in federated learning systems while providing practical pathways
for mitigation through topology-aware defense mechanisms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.17185v1">A Common Pool of Privacy Problems: Legal and Technical Lessons from a
  Large-Scale Web-Scraped Machine Learning Dataset</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-06-20T17:40:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rachel Hong, Jevan Hutson, William Agnew, Imaad Huda, Tadayoshi Kohno, Jamie Morgenstern</p>
    <p><b>Summary:</b> We investigate the contents of web-scraped data for training AI systems, at
sizes where human dataset curators and compilers no longer manually annotate
every sample. Building off of prior privacy concerns in machine learning
models, we ask: What are the legal privacy implications of web-scraped machine
learning datasets? In an empirical study of a popular training dataset, we find
significant presence of personally identifiable information despite
sanitization efforts. Our audit provides concrete evidence to support the
concern that any large-scale web-scraped dataset may contain personal data. We
use these findings of a real-world dataset to inform our legal analysis with
respect to existing privacy and data protection laws. We surface various
privacy risks of current data curation practices that may propagate personal
information to downstream models. From our findings, we argue for reorientation
of current frameworks of "publicly available" information to meaningfully limit
the development of AI built upon indiscriminate scraping of the internet.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.17012v1">A Novel Approach to Differential Privacy with Alpha Divergence</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-20T14:10:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yifeng Liu, Zehua Wang</p>
    <p><b>Summary:</b> As data-driven technologies advance swiftly, maintaining strong privacy
measures becomes progressively difficult. Conventional $(\epsilon,
\delta)$-differential privacy, while prevalent, exhibits limited adaptability
for many applications. To mitigate these constraints, we present alpha
differential privacy (ADP), an innovative privacy framework grounded in alpha
divergence, which provides a more flexible assessment of privacy consumption.
This study delineates the theoretical underpinnings of ADP and contrasts its
performance with competing privacy frameworks across many scenarios. Empirical
assessments demonstrate that ADP offers enhanced privacy guarantees in small to
moderate iteration contexts, particularly where severe privacy requirements are
necessary. The suggested method markedly improves privacy-preserving methods,
providing a flexible solution for contemporary data analysis issues in a
data-centric environment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.16578v1">SafeTriage: Facial Video De-identification for Privacy-Preserving Stroke
  Triage</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-06-19T20:02:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tongan Cai, Haomiao Ni, Wenchao Ma, Yuan Xue, Qian Ma, Rachel Leicht, Kelvin Wong, John Volpi, Stephen T. C. Wong, James Z. Wang, Sharon X. Huang</p>
    <p><b>Summary:</b> Effective stroke triage in emergency settings often relies on clinicians'
ability to identify subtle abnormalities in facial muscle coordination. While
recent AI models have shown promise in detecting such patterns from patient
facial videos, their reliance on real patient data raises significant ethical
and privacy challenges -- especially when training robust and generalizable
models across institutions. To address these concerns, we propose SafeTriage, a
novel method designed to de-identify patient facial videos while preserving
essential motion cues crucial for stroke diagnosis. SafeTriage leverages a
pretrained video motion transfer (VMT) model to map the motion characteristics
of real patient faces onto synthetic identities. This approach retains
diagnostically relevant facial dynamics without revealing the patients'
identities. To mitigate the distribution shift between normal population
pre-training videos and patient population test videos, we introduce a
conditional generative model for visual prompt tuning, which adapts the input
space of the VMT model to ensure accurate motion transfer without needing to
fine-tune the VMT model backbone. Comprehensive evaluation, including
quantitative metrics and clinical expert assessments, demonstrates that
SafeTriage-produced synthetic videos effectively preserve stroke-relevant
facial patterns, enabling reliable AI-based triage. Our evaluations also show
that SafeTriage provides robust privacy protection while maintaining diagnostic
accuracy, offering a secure and ethically sound foundation for data sharing and
AI-driven clinical analysis in neurological disorders.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.16460v1">Black-Box Privacy Attacks on Shared Representations in Multitask
  Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-19T16:56:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> John Abascal, Nicolás Berrios, Alina Oprea, Jonathan Ullman, Adam Smith, Matthew Jagielski</p>
    <p><b>Summary:</b> Multitask learning (MTL) has emerged as a powerful paradigm that leverages
similarities among multiple learning tasks, each with insufficient samples to
train a standalone model, to solve them simultaneously while minimizing data
sharing across users and organizations. MTL typically accomplishes this goal by
learning a shared representation that captures common structure among the tasks
by embedding data from all tasks into a common feature space. Despite being
designed to be the smallest unit of shared information necessary to effectively
learn patterns across multiple tasks, these shared representations can
inadvertently leak sensitive information about the particular tasks they were
trained on.
  In this work, we investigate what information is revealed by the shared
representations through the lens of inference attacks. Towards this, we propose
a novel, black-box task-inference threat model where the adversary, given the
embedding vectors produced by querying the shared representation on samples
from a particular task, aims to determine whether that task was present when
training the shared representation. We develop efficient, purely black-box
attacks on machine learning models that exploit the dependencies between
embeddings from the same task without requiring shadow models or labeled
reference data. We evaluate our attacks across vision and language domains for
multiple use cases of MTL and demonstrate that even with access only to fresh
task samples rather than training data, a black-box adversary can successfully
infer a task's inclusion in training. To complement our experiments, we provide
theoretical analysis of a simplified learning setting and show a strict
separation between adversaries with training samples and fresh samples from the
target task's distribution.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.16347v1">Emission Impossible: privacy-preserving carbon emissions claims</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-19T14:23:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jessica Man, Sadiq Jaffer, Patrick Ferris, Martin Kleppmann, Anil Madhavapeddy</p>
    <p><b>Summary:</b> Information and Communication Technologies (ICT) have a significant climate
impact, and data centres account for a large proportion of the carbon emissions
from ICT. To achieve sustainability goals, it is important that all parties
involved in ICT supply chains can track and share accurate carbon emissions
data with their customers, investors, and the authorities. However, businesses
have strong incentives to make their numbers look good, whilst less so to
publish their accounting methods along with all the input data, due to the risk
of revealing sensitive information. It would be uneconomical to use a trusted
third party to verify the data for every report for each party in the chain. As
a result, carbon emissions reporting in supply chains currently relies on
unverified data. This paper proposes a methodology that applies cryptography
and zero-knowledge proofs for carbon emissions claims that can be subsequently
verified without the knowledge of the private input data. The proposed system
is based on a zero-knowledge Succinct Non-interactive ARguments of Knowledge
(zk-SNARK) protocol, which enables verifiable emissions reporting mechanisms
across a chain of energy suppliers, cloud data centres, cloud services
providers, and customers, without any company needing to disclose commercially
sensitive information. This allows customers of cloud services to accurately
account for the emissions generated by their activities, improving data quality
for their own regulatory reporting. Cloud services providers would also be held
accountable for producing accurate carbon emissions data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.16196v1">Efficient and Privacy-Preserving Soft Prompt Transfer for LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-19T10:25:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xun Wang, Jing Xu, Franziska Boenisch, Michael Backes, Christopher A. Choquette-Choo, Adam Dziedzic</p>
    <p><b>Summary:</b> Prompting has become a dominant paradigm for adapting large language models
(LLMs). While discrete (textual) prompts are widely used for their
interpretability, soft (parameter) prompts have recently gained traction in
APIs. This is because they can encode information from more training samples
while minimizing the user's token usage, leaving more space in the context
window for task-specific input. However, soft prompts are tightly coupled to
the LLM they are tuned on, limiting their generalization to other LLMs. This
constraint is particularly problematic for efficiency and privacy: (1) tuning
prompts on each LLM incurs high computational costs, especially as LLMs
continue to grow in size. Additionally, (2) when the LLM is hosted externally,
soft prompt tuning often requires sharing private data with the LLM provider.
For instance, this is the case with the NVIDIA NeMo API. To address these
issues, we propose POST (Privacy Of Soft prompt Transfer), a framework that
enables private tuning of soft prompts on a small model and subsequently
transfers these prompts to a larger LLM. POST uses knowledge distillation to
derive a small model directly from the large LLM to improve prompt
transferability, tunes the soft prompt locally, optionally with differential
privacy guarantees, and transfers it back to the larger LLM using a small
public dataset. Our experiments show that POST reduces computational costs,
preserves privacy, and effectively transfers high-utility soft prompts.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.17336v1">Privacy-Preserving LLM Interaction with Socratic Chain-of-Thought
  Reasoning and Homomorphically Encrypted Vector Databases</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-06-19T07:13:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yubeen Bae, Minchan Kim, Jaejin Lee, Sangbum Kim, Jaehyung Kim, Yejin Choi, Niloofar Mireshghallah</p>
    <p><b>Summary:</b> Large language models (LLMs) are increasingly used as personal agents,
accessing sensitive user data such as calendars, emails, and medical records.
Users currently face a trade-off: They can send private records, many of which
are stored in remote databases, to powerful but untrusted LLM providers,
increasing their exposure risk. Alternatively, they can run less powerful
models locally on trusted devices. We bridge this gap. Our Socratic
Chain-of-Thought Reasoning first sends a generic, non-private user query to a
powerful, untrusted LLM, which generates a Chain-of-Thought (CoT) prompt and
detailed sub-queries without accessing user data. Next, we embed these
sub-queries and perform encrypted sub-second semantic search using our
Homomorphically Encrypted Vector Database across one million entries of a
single user's private data. This represents a realistic scale of personal
documents, emails, and records accumulated over years of digital activity.
Finally, we feed the CoT prompt and the decrypted records to a local language
model and generate the final response. On the LoCoMo long-context QA benchmark,
our hybrid framework, combining GPT-4o with a local Llama-3.2-1B model,
outperforms using GPT-4o alone by up to 7.1 percentage points. This
demonstrates a first step toward systems where tasks are decomposed and split
between untrusted strong LLMs and weak local ones, preserving user privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.17332v1">P2MFDS: A Privacy-Preserving Multimodal Fall Detection System for
  Elderly People in Bathroom Environments</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-06-19T05:22:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haitian Wang, Yiren Wang, Xinyu Wang, Yumeng Miao, Yuliang Zhang, Yu Zhang, Atif Mansoor</p>
    <p><b>Summary:</b> By 2050, people aged 65 and over are projected to make up 16 percent of the
global population. As aging is closely associated with increased fall risk,
particularly in wet and confined environments such as bathrooms where over 80
percent of falls occur. Although recent research has increasingly focused on
non-intrusive, privacy-preserving approaches that do not rely on wearable
devices or video-based monitoring, these efforts have not fully overcome the
limitations of existing unimodal systems (e.g., WiFi-, infrared-, or
mmWave-based), which are prone to reduced accuracy in complex environments.
These limitations stem from fundamental constraints in unimodal sensing,
including system bias and environmental interference, such as multipath fading
in WiFi-based systems and drastic temperature changes in infrared-based
methods. To address these challenges, we propose a Privacy-Preserving
Multimodal Fall Detection System for Elderly People in Bathroom Environments.
First, we develop a sensor evaluation framework to select and fuse
millimeter-wave radar with 3D vibration sensing, and use it to construct and
preprocess a large-scale, privacy-preserving multimodal dataset in real
bathroom settings, which will be released upon publication. Second, we
introduce P2MFDS, a dual-stream network combining a CNN-BiLSTM-Attention branch
for radar motion dynamics with a multi-scale CNN-SEBlock-Self-Attention branch
for vibration impact detection. By uniting macro- and micro-scale features,
P2MFDS delivers significant gains in accuracy and recall over state-of-the-art
approaches. Code and pretrained models will be made available at:
https://github.com/HaitianWang/P2MFDS-A-Privacy-Preserving-Multimodal-Fall-Detection-Network-for-Elderly-Individuals-in-Bathroom.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.15924v1">FARFETCH'D: A Side-Channel Analysis Framework for Privacy Applications
  on Confidential Virtual Machines</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-18T23:58:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruiyi Zhang, Albert Cheu, Adria Gascon, Daniel Moghimi, Phillipp Schoppmann, Michael Schwarz, Octavian Suciu</p>
    <p><b>Summary:</b> Confidential virtual machines (CVMs) based on trusted execution environments
(TEEs) enable new privacy-preserving solutions. Yet, they leave side-channel
leakage outside their threat model, shifting the responsibility of mitigating
such attacks to developers. However, mitigations are either not generic or too
slow for practical use, and developers currently lack a systematic, efficient
way to measure and compare leakage across real-world deployments. In this
paper, we present FARFETCH'D, an open-source toolkit that offers configurable
side-channel tracing primitives on production AMD SEV-SNP hardware and couples
them with statistical and machine-learning-based analysis pipelines for
automated leakage estimation. We apply FARFETCH'D to three representative
workloads that are deployed on CVMs to enhance user privacy - private
information retrieval, private heavy hitters, and Wasm user-defined functions -
and uncover previously unnoticed leaks, including a covert channel that
exfiltrated data at 497 kbit/s. The results show that FARFETCH'D pinpoints
vulnerabilities and guides low-overhead mitigations based on oblivious memory
and differential privacy, giving practitioners a practical path to deploy CVMs
with meaningful confidentiality guarantees.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.15854v1">Privacy-Preserving in Connected and Autonomous Vehicles Through Vision
  to Text Transformation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-18T20:02:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abdolazim Rezaei, Mehdi Sookhak, Ahmad Patooghy</p>
    <p><b>Summary:</b> Connected and Autonomous Vehicles (CAVs) rely on a range of devices that
often process privacy-sensitive data. Among these, roadside units play a
critical role particularly through the use of AI-equipped (AIE) cameras for
applications such as violation detection. However, the privacy risks associated
with captured imagery remain a major concern, as such data can be misused for
identity theft, profiling, or unauthorized commercial purposes. While
traditional techniques such as face blurring and obfuscation have been applied
to mitigate privacy risks, individual privacy remains at risk, as individuals
can still be tracked using other features such as their clothing. This paper
introduces a novel privacy-preserving framework that leverages feedback-based
reinforcement learning (RL) and vision-language models (VLMs) to protect
sensitive visual information captured by AIE cameras. The main idea is to
convert images into semantically equivalent textual descriptions, ensuring that
scene-relevant information is retained while visual privacy is preserved. A
hierarchical RL strategy is employed to iteratively refine the generated text,
enhancing both semantic accuracy and privacy. Evaluation results demonstrate
significant improvements in both privacy protection and textual quality, with
the Unique Word Count increasing by approximately 77\% and Detail Density by
around 50\% compared to existing approaches.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.15349v1">Enhancing One-run Privacy Auditing with Quantile Regression-Based
  Membership Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-18T11:03:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Terrance Liu, Matteo Boglioni, Yiwei Fu, Shengyuan Hu, Pratiksha Thaker, Zhiwei Steven Wu</p>
    <p><b>Summary:</b> Differential privacy (DP) auditing aims to provide empirical lower bounds on
the privacy guarantees of DP mechanisms like DP-SGD. While some existing
techniques require many training runs that are prohibitively costly, recent
work introduces one-run auditing approaches that effectively audit DP-SGD in
white-box settings while still being computationally efficient. However, in the
more practical black-box setting where gradients cannot be manipulated during
training and only the last model iterate is observed, prior work shows that
there is still a large gap between the empirical lower bounds and theoretical
upper bounds. Consequently, in this work, we study how incorporating approaches
for stronger membership inference attacks (MIA) can improve one-run auditing in
the black-box setting. Evaluating on image classification models trained on
CIFAR-10 with DP-SGD, we demonstrate that our proposed approach, which utilizes
quantile regression for MIA, achieves tighter bounds while crucially
maintaining the computational efficiency of one-run methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.15307v1">SecFwT: Efficient Privacy-Preserving Fine-Tuning of Large Language
  Models Using Forward-Only Passes</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-18T09:36:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jinglong Luo, Zhuo Zhang, Yehong Zhang, Shiyu Liu, Ye Dong, Xun Zhou, Hui Wang, Yue Yu, Zenglin Xu</p>
    <p><b>Summary:</b> Large language models (LLMs) have transformed numerous fields, yet their
adaptation to specialized tasks in privacy-sensitive domains, such as
healthcare and finance, is constrained by the scarcity of accessible training
data due to stringent privacy requirements. Secure multi-party computation
(MPC)-based privacy-preserving machine learning offers a powerful approach to
protect both model parameters and user data, but its application to LLMs has
been largely limited to inference, as fine-tuning introduces significant
computational challenges, particularly in privacy-preserving backward
propagation and optimizer operations. This paper identifies two primary
obstacles to MPC-based privacy-preserving fine-tuning of LLMs: (1) the
substantial computational overhead of backward and optimizer processes, and (2)
the inefficiency of softmax-based attention mechanisms in MPC settings. To
address these challenges, we propose SecFwT, the first MPC-based framework
designed for efficient, privacy-preserving LLM fine-tuning. SecFwT introduces a
forward-only tuning paradigm to eliminate backward and optimizer computations
and employs MPC-friendly Random Feature Attention to approximate softmax
attention, significantly reducing costly non-linear operations and
computational complexity. Experimental results demonstrate that SecFwT delivers
substantial improvements in efficiency and privacy preservation, enabling
scalable and secure fine-tuning of LLMs for privacy-critical applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.15258v2">Privacy-Preserving Chest X-ray Classification in Latent Space with
  Homomorphically Encrypted Neural Inference</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-06-18T08:35:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jonghun Kim, Gyeongdeok Jo, Sinyoung Ra, Hyunjin Park</p>
    <p><b>Summary:</b> Medical imaging data contain sensitive patient information requiring strong
privacy protection. Many analytical setups require data to be sent to a server
for inference purposes. Homomorphic encryption (HE) provides a solution by
allowing computations to be performed on encrypted data without revealing the
original information. However, HE inference is computationally expensive,
particularly for large images (e.g., chest X-rays). In this study, we propose
an HE inference framework for medical images that uses VQGAN to compress images
into latent representations, thereby significantly reducing the computational
burden while preserving image quality. We approximate the activation functions
with lower-degree polynomials to balance the accuracy and efficiency in
compliance with HE requirements. We observed that a downsampling factor of
eight for compression achieved an optimal balance between performance and
computational cost. We further adapted the squeeze and excitation module, which
is known to improve traditional CNNs, to enhance the HE framework. Our method
was tested on two chest X-ray datasets for multi-label classification tasks
using vanilla CNN backbones. Although HE inference remains relatively slow and
introduces minor performance differences compared with unencrypted inference,
our approach shows strong potential for practical use in medical images</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.15224v1">Facility Location Problem under Local Differential Privacy without
  Super-set Assumption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-18T08:08:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kevin Pfisterer, Quentin Hillebrand, Vorapong Suppakitpaisarn</p>
    <p><b>Summary:</b> In this paper, we introduce an adaptation of the facility location problem
and analyze it within the framework of local differential privacy (LDP). Under
this model, we ensure the privacy of client presence at specific locations.
When n is the number of points, Gupta et al. established a lower bound of
$\Omega(\sqrt{n})$ on the approximation ratio for any differentially private
algorithm applied to the original facility location problem. As a result,
subsequent works have adopted the super-set assumption, which may, however,
compromise user privacy. We show that this lower bound does not apply to our
adaptation by presenting an LDP algorithm that achieves a constant
approximation ratio with a relatively small additive factor. Additionally, we
provide experimental results demonstrating that our algorithm outperforms the
straightforward approach on both synthetically generated and real-world
datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.15201v2">Privacy-Shielded Image Compression: Defending Against Exploitation from
  Vision-Language Pretrained Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-06-18T07:29:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xuelin Shen, Jiayin Xu, Kangsheng Yin, Wenhan Yang</p>
    <p><b>Summary:</b> The improved semantic understanding of vision-language pretrained (VLP)
models has made it increasingly difficult to protect publicly posted images
from being exploited by search engines and other similar tools. In this
context, this paper seeks to protect users' privacy by implementing defenses at
the image compression stage to prevent exploitation. Specifically, we propose a
flexible coding method, termed Privacy-Shielded Image Compression (PSIC), that
can produce bitstreams with multiple decoding options. By default, the
bitstream is decoded to preserve satisfactory perceptual quality while
preventing interpretation by VLP models. Our method also retains the original
image compression functionality. With a customizable input condition, the
proposed scheme can reconstruct the image that preserves its full semantic
information. A Conditional Latent Trigger Generation (CLTG) module is proposed
to produce bias information based on customizable conditions to guide the
decoding process into different reconstructed versions, and an
Uncertainty-Aware Encryption-Oriented (UAEO) optimization function is designed
to leverage the soft labels inferred from the target VLP model's uncertainty on
the training data. This paper further incorporates an adaptive multi-objective
optimization strategy to obtain improved encrypting performance and perceptual
quality simultaneously within a unified training process. The proposed scheme
is plug-and-play and can be seamlessly integrated into most existing Learned
Image Compression (LIC) models. Extensive experiments across multiple
downstream tasks have demonstrated the effectiveness of our design.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.15112v1">PDLRecover: Privacy-preserving Decentralized Model Recovery with Machine
  Unlearning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-18T03:30:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiangman Li, Xiaodong Wu, Jianbing Ni, Mohamed Mahmoud, Maazen Alsabaan</p>
    <p><b>Summary:</b> Decentralized learning is vulnerable to poison attacks, where malicious
clients manipulate local updates to degrade global model performance. Existing
defenses mainly detect and filter malicious models, aiming to prevent a limited
number of attackers from corrupting the global model. However, restoring an
already compromised global model remains a challenge. A direct approach is to
remove malicious clients and retrain the model using only the benign clients.
Yet, retraining is time-consuming, computationally expensive, and may
compromise model consistency and privacy.
  We propose PDLRecover, a novel method to recover a poisoned global model
efficiently by leveraging historical model information while preserving
privacy. The main challenge lies in protecting shared historical models while
enabling parameter estimation for model recovery. By exploiting the linearity
of approximate Hessian matrix computation, we apply secret sharing to protect
historical updates, ensuring local models are not leaked during transmission or
reconstruction. PDLRecover introduces client-side preparation, periodic
recovery updates, and a final exact update to ensure robustness and convergence
of the recovered model. Periodic updates maintain accurate curvature
information, and the final step ensures high-quality convergence. Experiments
show that the recovered global model achieves performance comparable to a fully
retrained model but with significantly reduced computation and time cost.
Moreover, PDLRecover effectively prevents leakage of local model parameters,
ensuring both accuracy and privacy in recovery.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.15106v2">Local Differential Privacy for Distributed Stochastic Aggregative
  Optimization with Guaranteed Optimality</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2025-06-18T03:22:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ziqin Chen, Yongqiang Wang</p>
    <p><b>Summary:</b> Distributed aggregative optimization underpins many cooperative optimization
and multi-agent control systems, where each agent's objective function depends
both on its local optimization variable and an aggregate of all agents'
optimization variables. Existing distributed aggregative optimization
approaches typically require access to accurate gradients of the objective
functions, which, however, are often hard to obtain in real-world applications.
For example, in machine learning, gradients are commonly contaminated by two
main sources of noise: the randomness inherent in sampled data, and the
additional variability introduced by mini-batch computations. In addition to
the issue of relying on accurate gradients, existing distributed aggregative
optimization approaches require agents to share explicit information, which
could breach the privacy of participating agents. We propose an algorithm that
can solve both problems with existing distributed aggregative optimization
approaches: not only can the proposed algorithm guarantee mean-square
convergence to an exact optimal solution when the gradients are subject to
noise, it also simultaneously ensures rigorous differential privacy, with the
cumulative privacy budget guaranteed to be finite even when the number of
iterations tends to infinity. To the best of our knowledge, this is the first
algorithm able to guarantee both accurate convergence and rigorous differential
privacy in distributed aggregative optimization. Besides characterizing the
convergence rates under nonconvex/convex/strongly convex conditions, we also
rigorously quantify the cost of differential privacy in terms of convergence
rates. Experimental results on personalized machine learning using benchmark
datasets confirm the efficacy of the proposed algorithm.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.14620v1">Differential Privacy and Survey Sampling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> 
  <p><b>Published on:</b> 2025-06-17T15:17:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Daniel Bernard Bonnéry, Julien Jamme</p>
    <p><b>Summary:</b> The Horvitz-Thompson estimate of a total can be seen as as differentially
private mechanism applied to this population total. We provide forumlae to
compute the $\epsilon$ and $\delta$ parameter for this specific mecanism,
coupled or not coupled with the addition of a Laplace or a Gaussian noise. This
allows to determine the scale of the Laplace privacy mechanism to be added to
reach a specified level of privacy, expressed in terms of $\epsilon,\delta$
differential privacy. In particular, we provide simple formulae for the special
case of simple random sampling on binary data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.14576v1">SoK: Privacy-Enhancing Technologies in Artificial Intelligence</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-17T14:32:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nouha Oualha</p>
    <p><b>Summary:</b> As artificial intelligence (AI) continues to permeate various sectors,
safeguarding personal and sensitive data has become increasingly crucial. To
address these concerns, privacy-enhancing technologies (PETs) have emerged as a
suite of digital tools that enable data collection and processing while
preserving privacy. This paper explores the current landscape of data privacy
in the context of AI, reviews the integration of PETs within AI systems, and
assesses both their achievements and the challenges that remain.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.14251v1">Convergence-Privacy-Fairness Trade-Off in Personalized Federated
  Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-06-17T07:15:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiyu Zhao, Qimei Cui, Weicai Li, Wei Ni, Ekram Hossain, Quan Z. Sheng, Xiaofeng Tao, Ping Zhang</p>
    <p><b>Summary:</b> Personalized federated learning (PFL), e.g., the renowned Ditto, strikes a
balance between personalization and generalization by conducting federated
learning (FL) to guide personalized learning (PL). While FL is unaffected by
personalized model training, in Ditto, PL depends on the outcome of the FL.
However, the clients' concern about their privacy and consequent perturbation
of their local models can affect the convergence and (performance) fairness of
PL. This paper presents PFL, called DP-Ditto, which is a non-trivial extension
of Ditto under the protection of differential privacy (DP), and analyzes the
trade-off among its privacy guarantee, model convergence, and performance
distribution fairness. We also analyze the convergence upper bound of the
personalized models under DP-Ditto and derive the optimal number of global
aggregations given a privacy budget. Further, we analyze the performance
fairness of the personalized models, and reveal the feasibility of optimizing
DP-Ditto jointly for convergence and fairness. Experiments validate our
analysis and demonstrate that DP-Ditto can surpass the DP-perturbed versions of
the state-of-the-art PFL models, such as FedAMP, pFedMe, APPLE, and FedALA, by
over 32.71% in fairness and 9.66% in accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.13972v1">Membership Inference Attacks as Privacy Tools: Reliability, Disparity
  and Ensemble</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-16T20:22:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhiqi Wang, Chengyu Zhang, Yuetian Chen, Nathalie Baracaldo, Swanand Kadhe, Lei Yu</p>
    <p><b>Summary:</b> Membership inference attacks (MIAs) pose a significant threat to the privacy
of machine learning models and are widely used as tools for privacy assessment,
auditing, and machine unlearning. While prior MIA research has primarily
focused on performance metrics such as AUC, accuracy, and TPR@low FPR - either
by developing new methods to enhance these metrics or using them to evaluate
privacy solutions - we found that it overlooks the disparities among different
attacks. These disparities, both between distinct attack methods and between
multiple instantiations of the same method, have crucial implications for the
reliability and completeness of MIAs as privacy evaluation tools. In this
paper, we systematically investigate these disparities through a novel
framework based on coverage and stability analysis. Extensive experiments
reveal significant disparities in MIAs, their potential causes, and their
broader implications for privacy evaluation. To address these challenges, we
propose an ensemble framework with three distinct strategies to harness the
strengths of state-of-the-art MIAs while accounting for their disparities. This
framework not only enables the construction of more powerful attacks but also
provides a more robust and comprehensive methodology for privacy evaluation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.13882v1">Toward Practical Privacy in XR: Empirical Analysis of Multimodal
  Anonymization Mechanisms</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-06-16T18:01:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Azim Ibragimov, Ethan Wilson, Kevin R. B. Butler, Eakta Jain</p>
    <p><b>Summary:</b> As extended reality (XR) systems become increasingly immersive and
sensor-rich, they enable the collection of fine-grained behavioral signals such
as eye and body telemetry. These signals support personalized and responsive
experiences and may also contain unique patterns that can be linked back to
individuals. However, privacy mechanisms that naively pair unimodal mechanisms
(e.g., independently apply privacy mechanisms for eye and body privatization)
are often ineffective at preventing re-identification in practice. In this
work, we systematically evaluate real-time privacy mechanisms for XR, both
individually and in pair, across eye and body modalities. To preserve
usability, all mechanisms were tuned based on empirically grounded thresholds
for real-time interaction. We evaluated four eye and ten body mechanisms across
multiple datasets, comprising up to 407 participants. Our results show that
while obfuscating eye telemetry alone offers moderate privacy gains, body
telemetry perturbation is substantially more effective. When carefully paired,
multimodal mechanisms reduce re-identification rate from 80.3% to 26.3% in
casual XR applications (e.g., VRChat and Job Simulator) and from 84.8% to 26.1%
in competitive XR applications (e.g., Beat Saber and Synth Riders), all without
violating real-time usability requirements. These findings underscore the
potential of modality-specific and context-aware privacy strategies for
protecting behavioral data in XR environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.13561v1">Perfect Privacy for Discriminator-Based Byzantine-Resilient Federated
  Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2025-06-16T14:47:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yue Xia, Christoph Hofmeister, Maximilian Egger, Rawad Bitar</p>
    <p><b>Summary:</b> Federated learning (FL) shows great promise in large-scale machine learning
but introduces new privacy and security challenges. We propose ByITFL and
LoByITFL, two novel FL schemes that enhance resilience against Byzantine users
while keeping the users' data private from eavesdroppers. To ensure privacy and
Byzantine resilience, our schemes build on having a small representative
dataset available to the federator and crafting a discriminator function
allowing the mitigation of corrupt users' contributions. ByITFL employs
Lagrange coded computing and re-randomization, making it the first
Byzantine-resilient FL scheme with perfect Information-Theoretic (IT) privacy,
though at the cost of a significant communication overhead. LoByITFL, on the
other hand, achieves Byzantine resilience and IT privacy at a significantly
reduced communication cost, but requires a Trusted Third Party, used only in a
one-time initialization phase before training. We provide theoretical
guarantees on privacy and Byzantine resilience, along with convergence
guarantees and experimental results validating our findings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.13170v1">Dual Protection Ring: User Profiling Via Differential Privacy and
  Service Dissemination Through Private Information Retrieval</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-16T07:33:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Imdad Ullah, Najm Hassan, Tariq Ahamed Ahangar, Zawar Hussain Shah, Mehregan Mahdavi Andrew Levula</p>
    <p><b>Summary:</b> User profiling is crucial in providing personalised services, as it relies on
analysing user behaviour and preferences to deliver targeted services. This
approach enhances user experience and promotes heightened engagement.
Nevertheless, user profiling also gives rise to noteworthy privacy
considerations due to the extensive tracking and monitoring of personal data,
potentially leading to surveillance or identity theft. We propose a dual-ring
protection mechanism to protect user privacy by examining various threats to
user privacy, such as behavioural attacks, profiling fingerprinting and
monitoring, profile perturbation, etc., both on the user and service provider
sides. We develop user profiles that contain sensitive private attributes and
an equivalent profile based on differential privacy for evaluating personalised
services. We determine the entropy of the resultant profiles during each update
to protect profiling attributes and invoke various processes, such as data
evaporation, to artificially increase entropy or destroy private profiling
attributes. Furthermore, we use different variants of private information
retrieval (PIR) to retrieve personalised services against differentially
private profiles. We implement critical components of the proposed model via a
proof-of-concept mobile app to demonstrate its applicability over a specific
case study of advertising services, which can be generalised to other services.
Our experimental results show that the observed processing delays with
different PIR schemes are similar to the current advertising systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.13052v2">Buy it Now, Track Me Later: Attacking User Privacy via Wi-Fi AP Online
  Auctions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-16T02:42:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Steven Su, Erik Rye, Dave Levin, Robert Beverly</p>
    <p><b>Summary:</b> Static and hard-coded layer-two network identifiers are well known to present
security vulnerabilities and endanger user privacy. In this work, we introduce
a new privacy attack against Wi-Fi access points listed on secondhand
marketplaces. Specifically, we demonstrate the ability to remotely gather a
large quantity of layer-two Wi-Fi identifiers by programmatically querying the
eBay marketplace and applying state-of-the-art computer vision techniques to
extract IEEE 802.11 BSSIDs from the seller's posted images of the hardware. By
leveraging data from a global Wi-Fi Positioning System (WPS) that geolocates
BSSIDs, we obtain the physical locations of these devices both pre- and
post-sale. In addition to validating the degree to which a seller's location
matches the location of the device, we examine cases of device movement -- once
the device is sold and then subsequently re-used in a new environment. Our work
highlights a previously unrecognized privacy vulnerability and suggests, yet
again, the strong need to protect layer-two network identifiers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.13009v1">Rectifying Privacy and Efficacy Measurements in Machine Unlearning: A
  New Inference Attack Perspective</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-16T00:30:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nima Naderloui, Shenao Yan, Binghui Wang, Jie Fu, Wendy Hui Wang, Weiran Liu, Yuan Hong</p>
    <p><b>Summary:</b> Machine unlearning focuses on efficiently removing specific data from trained
models, addressing privacy and compliance concerns with reasonable costs.
Although exact unlearning ensures complete data removal equivalent to
retraining, it is impractical for large-scale models, leading to growing
interest in inexact unlearning methods. However, the lack of formal guarantees
in these methods necessitates the need for robust evaluation frameworks to
assess their privacy and effectiveness. In this work, we first identify several
key pitfalls of the existing unlearning evaluation frameworks, e.g., focusing
on average-case evaluation or targeting random samples for evaluation,
incomplete comparisons with the retraining baseline. Then, we propose RULI
(Rectified Unlearning Evaluation Framework via Likelihood Inference), a novel
framework to address critical gaps in the evaluation of inexact unlearning
methods. RULI introduces a dual-objective attack to measure both unlearning
efficacy and privacy risks at a per-sample granularity. Our findings reveal
significant vulnerabilities in state-of-the-art unlearning methods, where RULI
achieves higher attack success rates, exposing privacy risks underestimated by
existing methods. Built on a game-based foundation and validated through
empirical evaluations on both image and text data (spanning tasks from
classification to generation), RULI provides a rigorous, scalable, and
fine-grained methodology for evaluating unlearning techniques.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.12846v1">Privacy-Preserving Federated Learning against Malicious Clients Based on
  Verifiable Functional Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-06-15T13:38:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nina Cai, Jinguang Han</p>
    <p><b>Summary:</b> Federated learning is a promising distributed learning paradigm that enables
collaborative model training without exposing local client data, thereby
protect data privacy. However, it also brings new threats and challenges. The
advancement of model inversion attacks has rendered the plaintext transmission
of local models insecure, while the distributed nature of federated learning
makes it particularly vulnerable to attacks raised by malicious clients. To
protect data privacy and prevent malicious client attacks, this paper proposes
a privacy-preserving federated learning framework based on verifiable
functional encryption, without a non-colluding dual-server setup or additional
trusted third-party. Specifically, we propose a novel decentralized verifiable
functional encryption (DVFE) scheme that enables the verification of specific
relationships over multi-dimensional ciphertexts. This scheme is formally
treated, in terms of definition, security model and security proof.
Furthermore, based on the proposed DVFE scheme, we design a privacy-preserving
federated learning framework VFEFL that incorporates a novel robust aggregation
rule to detect malicious clients, enabling the effective training of
high-accuracy models under adversarial settings. Finally, we provide formal
analysis and empirical evaluation of the proposed schemes. The results
demonstrate that our approach achieves the desired privacy protection,
robustness, verifiability and fidelity, while eliminating the reliance on
non-colluding dual-server settings or trusted third parties required by
existing methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.12749v2">Free Privacy Protection for Wireless Federated Learning: Enjoy It or
  Suffer from It?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-15T07:13:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Weicai Li, Tiejun Lv, Xiyu Zhao, Xin Yuan, Wei Ni</p>
    <p><b>Summary:</b> Inherent communication noises have the potential to preserve privacy for
wireless federated learning (WFL) but have been overlooked in digital
communication systems predominantly using floating-point number standards,
e.g., IEEE 754, for data storage and transmission. This is due to the
potentially catastrophic consequences of bit errors in floating-point numbers,
e.g., on the sign or exponent bits. This paper presents a novel channel-native
bit-flipping differential privacy (DP) mechanism tailored for WFL, where
transmit bits are randomly flipped and communication noises are leveraged, to
collectively preserve the privacy of WFL in digital communication systems. The
key idea is to interpret the bit perturbation at the transmitter and bit errors
caused by communication noises as a bit-flipping DP process. This is achieved
by designing a new floating-point-to-fixed-point conversion method that only
transmits the bits in the fraction part of model parameters, hence eliminating
the need for transmitting the sign and exponent bits and preventing the
catastrophic consequence of bit errors. We analyze a new metric to measure the
bit-level distance of the model parameters and prove that the proposed
mechanism satisfies (\lambda,\epsilon)-R\'enyi DP and does not violate the WFL
convergence. Experiments validate privacy and convergence analysis of the
proposed mechanism and demonstrate its superiority to the state-of-the-art
Gaussian mechanisms that are channel-agnostic and add Gaussian noise for
privacy protection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.12699v2">SoK: The Privacy Paradox of Large Language Models: Advancements, Privacy
  Risks, and Mitigation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-06-15T03:14:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yashothara Shanmugarasa, Ming Ding, M. A. P Chamikara, Thierry Rakotoarivelo</p>
    <p><b>Summary:</b> Large language models (LLMs) are sophisticated artificial intelligence
systems that enable machines to generate human-like text with remarkable
precision. While LLMs offer significant technological progress, their
development using vast amounts of user data scraped from the web and collected
from extensive user interactions poses risks of sensitive information leakage.
Most existing surveys focus on the privacy implications of the training data
but tend to overlook privacy risks from user interactions and advanced LLM
capabilities. This paper aims to fill that gap by providing a comprehensive
analysis of privacy in LLMs, categorizing the challenges into four main areas:
(i) privacy issues in LLM training data, (ii) privacy challenges associated
with user prompts, (iii) privacy vulnerabilities in LLM-generated outputs, and
(iv) privacy challenges involving LLM agents. We evaluate the effectiveness and
limitations of existing mitigation mechanisms targeting these proposed privacy
challenges and identify areas for further research.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.12523v1">Privacy-preserving and reward-based mechanisms of proof of engagement</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> 
  <p><b>Published on:</b> 2025-06-14T14:33:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Matteo Marco Montanari, Alessandro Aldini</p>
    <p><b>Summary:</b> Proof-of-Attendance (PoA) mechanisms are typically employed to demonstrate a
specific user's participation in an event, whether virtual or in-person. The
goal of this study is to extend such mechanisms to broader contexts where the
user wishes to digitally demonstrate her involvement in a specific activity
(Proof-of-Engagement, PoE). This work explores different solutions, including
DLTs as well as established technologies based on centralized systems. The main
aspects we consider include the level of privacy guaranteed to users, the scope
of PoA/PoE (both temporal and spatial), the transferability of the proof, and
the integration with incentive mechanisms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.12328v1">Information-theoretic Estimation of the Risk of Privacy Leaks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-14T03:39:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kenneth Odoh</p>
    <p><b>Summary:</b> Recent work~\cite{Liu2016} has shown that dependencies between items in a
dataset can lead to privacy leaks. We extend this concept to privacy-preserving
transformations, considering a broader set of dependencies captured by
correlation metrics. Specifically, we measure the correlation between the
original data and their noisy responses from a randomizer as an indicator of
potential privacy breaches. This paper aims to leverage information-theoretic
measures, such as the Maximal Information Coefficient (MIC), to estimate
privacy leaks and derive novel, computationally efficient privacy leak
estimators. We extend the $\rho_1$-to-$\rho_2$
formulation~\cite{Evfimievski2003} to incorporate entropy, mutual information,
and the degree of anonymity for a more comprehensive measure of privacy risk.
Our proposed hybrid metric can identify correlation dependencies between
attributes in the dataset, serving as a proxy for privacy leak vulnerabilities.
This metric provides a computationally efficient worst-case measure of privacy
loss, utilizing the inherent characteristics of the data to prevent privacy
breaches.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.12241v1">Privacy Reasoning in Ambiguous Contexts</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-13T21:42:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ren Yi, Octavian Suciu, Adria Gascon, Sarah Meiklejohn, Eugene Bagdasarian, Marco Gruteser</p>
    <p><b>Summary:</b> We study the ability of language models to reason about appropriate
information disclosure - a central aspect of the evolving field of agentic
privacy. Whereas previous works have focused on evaluating a model's ability to
align with human decisions, we examine the role of ambiguity and missing
context on model performance when making information-sharing decisions. We
identify context ambiguity as a crucial barrier for high performance in privacy
assessments. By designing Camber, a framework for context disambiguation, we
show that model-generated decision rationales can reveal ambiguities and that
systematically disambiguating context based on these rationales leads to
significant accuracy improvements (up to 13.3\% in precision and up to 22.3\%
in recall) as well as reductions in prompt sensitivity. Overall, our results
indicate that approaches for context disambiguation are a promising way forward
to enhance agentic privacy reasoning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.11687v1">Differential Privacy in Machine Learning: From Symbolic AI to LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Neural and Evolutionary Computing-5BC0EB">
  <p><b>Published on:</b> 2025-06-13T11:30:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Francisco Aguilera-Martínez, Fernando Berzal</p>
    <p><b>Summary:</b> Machine learning models should not reveal particular information that is not
otherwise accessible. Differential privacy provides a formal framework to
mitigate privacy risks by ensuring that the inclusion or exclusion of any
single data point does not significantly alter the output of an algorithm, thus
limiting the exposure of private information. This survey paper explores the
foundational definitions of differential privacy, reviews its original
formulations and tracing its evolution through key research contributions. It
then provides an in-depth examination of how DP has been integrated into
machine learning models, analyzing existing proposals and methods to preserve
privacy when training ML models. Finally, it describes how DP-based ML
techniques can be evaluated in practice. %Finally, it discusses the broader
implications of DP, highlighting its potential for public benefit, its
real-world applications, and the challenges it faces, including vulnerabilities
to adversarial attacks. By offering a comprehensive overview of differential
privacy in machine learning, this work aims to contribute to the ongoing
development of secure and responsible AI systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.11679v1">LLMs on support of privacy and security of mobile apps: state of the art
  and research directions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-06-13T11:17:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tran Thanh Lam Nguyen, Barbara Carminati, Elena Ferrari</p>
    <p><b>Summary:</b> Modern life has witnessed the explosion of mobile devices. However, besides
the valuable features that bring convenience to end users, security and privacy
risks still threaten users of mobile apps. The increasing sophistication of
these threats in recent years has underscored the need for more advanced and
efficient detection approaches. In this chapter, we explore the application of
Large Language Models (LLMs) to identify security risks and privacy violations
and mitigate them for the mobile application ecosystem. By introducing
state-of-the-art research that applied LLMs to mitigate the top 10 common
security risks of smartphone platforms, we highlight the feasibility and
potential of LLMs to replace traditional analysis methods, such as dynamic and
hybrid analysis of mobile apps. As a representative example of LLM-based
solutions, we present an approach to detect sensitive data leakage when users
share images online, a common behavior of smartphone users nowadays. Finally,
we discuss open research challenges.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.12106v1">Enhancing Privacy: The Utility of Stand-Alone Synthetic CT and MRI for
  Tumor and Bone Segmentation</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-06-13T08:17:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> André Ferreira, Kunpeng Xie, Caroline Wilpert, Gustavo Correia, Felix Barajas Ordonez, Tiago Gil Oliveira, Maike Bode, Robert Siepmann, Frank Hölzle, Rainer Röhrig, Jens Kleesiek, Daniel Truhn, Jan Egger, Victor Alves, Behrus Puladi</p>
    <p><b>Summary:</b> AI requires extensive datasets, while medical data is subject to high data
protection. Anonymization is essential, but poses a challenge for some regions,
such as the head, as identifying structures overlap with regions of clinical
interest. Synthetic data offers a potential solution, but studies often lack
rigorous evaluation of realism and utility. Therefore, we investigate to what
extent synthetic data can replace real data in segmentation tasks. We employed
head and neck cancer CT scans and brain glioma MRI scans from two large
datasets. Synthetic data were generated using generative adversarial networks
and diffusion models. We evaluated the quality of the synthetic data using MAE,
MS-SSIM, Radiomics and a Visual Turing Test (VTT) performed by 5 radiologists
and their usefulness in segmentation tasks using DSC. Radiomics indicates high
fidelity of synthetic MRIs, but fall short in producing highly realistic CT
tissue, with correlation coefficient of 0.8784 and 0.5461 for MRI and CT
tumors, respectively. DSC results indicate limited utility of synthetic data:
tumor segmentation achieved DSC=0.064 on CT and 0.834 on MRI, while bone
segmentation a mean DSC=0.841. Relation between DSC and correlation is
observed, but is limited by the complexity of the task. VTT results show
synthetic CTs' utility, but with limited educational applications. Synthetic
data can be used independently for the segmentation task, although limited by
the complexity of the structures to segment. Advancing generative models to
better tolerate heterogeneous inputs and learn subtle details is essential for
enhancing their realism and expanding their application potential.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.11434v1">Auditing Data Provenance in Real-world Text-to-Image Diffusion Models
  for Privacy and Copyright Protection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-06-13T03:16:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jie Zhu, Leye Wang</p>
    <p><b>Summary:</b> Text-to-image diffusion model since its propose has significantly influenced
the content creation due to its impressive generation capability. However, this
capability depends on large-scale text-image datasets gathered from web
platforms like social media, posing substantial challenges in copyright
compliance and personal privacy leakage. Though there are some efforts devoted
to explore approaches for auditing data provenance in text-to-image diffusion
models, existing work has unrealistic assumptions that can obtain model
internal knowledge, e.g., intermediate results, or the evaluation is not
reliable. To fill this gap, we propose a completely black-box auditing
framework called Feature Semantic Consistency-based Auditing (FSCA). It
utilizes two types of semantic connections within the text-to-image diffusion
model for auditing, eliminating the need for access to internal knowledge. To
demonstrate the effectiveness of our FSCA framework, we perform extensive
experiments on LAION-mi dataset and COCO dataset, and compare with eight
state-of-the-art baseline approaches. The results show that FSCA surpasses
previous baseline approaches across various metrics and different data
distributions, showcasing the superiority of our FSCA. Moreover, we introduce a
recall balance strategy and a threshold adjustment strategy, which collectively
allows FSCA to reach up a user-level accuracy of 90% in a real-world auditing
scenario with only 10 samples/user, highlighting its strong auditing potential
in real-world applications. Our code is made available at
https://github.com/JiePKU/FSCA.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.09690v1">Knockoffs Inference under Privacy Constraints</a></h3>
   
  <p><b>Published on:</b> 2025-06-11T13:06:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhanrui Cai, Yingying Fan, Lan Gao</p>
    <p><b>Summary:</b> Model-X knockoff framework offers a model-free variable selection method that
ensures finite sample false discovery rate (FDR) control. However, the
complexity of generating knockoff variables, coupled with the model-free
assumption, presents significant challenges for protecting data privacy in this
context. In this paper, we propose a comprehensive framework for knockoff
inference within the differential privacy paradigm. Our proposed method
guarantees robust privacy protection while preserving the exact FDR control
entailed by the original model-X knockoff procedure. We further conduct power
analysis and establish sufficient conditions under which the noise added for
privacy preservation does not asymptotically compromise power. Through various
applications, we demonstrate that the differential privacy knockoff
(DP-knockoff) method can be effectively utilized to safeguard privacy during
variable selection with FDR control in both low and high dimensional settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.17269v1">Digital Privacy Everywhere</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-11T09:25:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Paritosh Ranjan, Surajit Majumder, Prodip Roy</p>
    <p><b>Summary:</b> The increasing proliferation of digital and mobile devices equipped with
cameras, microphones, GPS, and other privacy invasive components has raised
significant concerns for businesses operating in sensitive or policy restricted
environments. Current solutions rely on passive enforcement, such as signage or
verbal instructions, which are largely ineffective. This paper presents Digital
Privacy Everywhere (DPE), a comprehensive and scalable system designed to
actively enforce custom privacy policies for digital devices within predefined
physical boundaries. The DPE architecture includes a centralized management
console, field verification units (FVUs), enforcement modules for mobile
devices (EMMDs), and an External Geo Ownership Service (EGOS). These components
collaboratively detect, configure, and enforce privacy settings such as
disabling cameras, microphones, or radios across various premises like
theaters, hospitals, financial institutions, and educational facilities. The
system ensures privacy compliance in real time while maintaining a seamless
user experience and operational scalability across geographies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.10042v1">Multiverse Privacy Theory for Contextual Risks in Complex User-AI
  Interactions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-06-11T05:02:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ece Gumusel</p>
    <p><b>Summary:</b> In an era of increasing interaction with artificial intelligence (AI), users
face evolving privacy decisions shaped by complex, uncertain factors. This
paper introduces Multiverse Privacy Theory, a novel framework in which each
privacy decision spawns a parallel universe, representing a distinct potential
outcome based on user choices over time. By simulating these universes, this
theory provides a foundation for understanding privacy through the lens of
contextual integrity, evolving preferences, and probabilistic decision-making.
Future work will explore its application using real-world, scenario-based
survey data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.09387v1">Epass: Efficient and Privacy-Preserving Asynchronous Payment on
  Blockchain</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-11T04:32:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Weijie Wang, Jinwen Liang, Chuan Zhang, Ximeng Liu, Liehuang Zhu, Song Guo</p>
    <p><b>Summary:</b> Buy Now Pay Later (BNPL) is a rapidly proliferating e-commerce model,
offering consumers to get the product immediately and defer payments.
Meanwhile, emerging blockchain technologies endow BNPL platforms with digital
currency transactions, allowing BNPL platforms to integrate with digital
wallets. However, the transparency of transactions causes critical privacy
concerns because malicious participants may derive consumers' financial
statuses from on-chain asynchronous payments. Furthermore, the newly created
transactions for deferred payments introduce additional time overheads, which
weaken the scalability of BNPL services. To address these issues, we propose an
efficient and privacy-preserving blockchain-based asynchronous payment scheme
(Epass), which has promising scalability while protecting the privacy of
on-chain consumer transactions. Specifically, Epass leverages locally
verifiable signatures to guarantee the privacy of consumer transactions against
malicious acts. Then, a privacy-preserving asynchronous payment scheme can be
further constructed by leveraging time-release encryption to control trapdoors
of redactable blockchain, reducing time overheads by modifying transactions for
deferred payment. We give formal definitions and security models, generic
structures, and formal proofs for Epass. Extensive comparisons and experimental
analysis show that \textsf{Epass} achieves KB-level communication costs, and
reduces time overhead by more than four times in comparisons with locally
verifiable signatures and Go-Ethereum private test networks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.09312v1">What is the Cost of Differential Privacy for Deep Learning-Based
  Trajectory Generation?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-11T00:59:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Erik Buchholz, Natasha Fernandes, David D. Nguyen, Alsharif Abuadbba, Surya Nepal, Salil S. Kanhere</p>
    <p><b>Summary:</b> While location trajectories offer valuable insights, they also reveal
sensitive personal information. Differential Privacy (DP) offers formal
protection, but achieving a favourable utility-privacy trade-off remains
challenging. Recent works explore deep learning-based generative models to
produce synthetic trajectories. However, current models lack formal privacy
guarantees and rely on conditional information derived from real data during
generation. This work investigates the utility cost of enforcing DP in such
models, addressing three research questions across two datasets and eleven
utility metrics. (1) We evaluate how DP-SGD, the standard DP training method
for deep learning, affects the utility of state-of-the-art generative models.
(2) Since DP-SGD is limited to unconditional models, we propose a novel DP
mechanism for conditional generation that provides formal guarantees and assess
its impact on utility. (3) We analyse how model types - Diffusion, VAE, and GAN
- affect the utility-privacy trade-off. Our results show that DP-SGD
significantly impacts performance, although some utility remains if the
datasets is sufficiently large. The proposed DP mechanism improves training
stability, particularly when combined with DP-SGD, for unstable models such as
GANs and on smaller datasets. Diffusion models yield the best utility without
guarantees, but with DP-SGD, GANs perform best, indicating that the best
non-private model is not necessarily optimal when targeting formal guarantees.
In conclusion, DP trajectory generation remains a challenging task, and formal
guarantees are currently only feasible with large datasets and in constrained
use cases.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.12088v1">Risks & Benefits of LLMs & GenAI for Platform Integrity, Healthcare
  Diagnostics, Cybersecurity, Privacy & AI Safety: A Comprehensive Survey,
  Roadmap & Implementation Blueprint</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-06-10T18:03:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kiarash Ahi</p>
    <p><b>Summary:</b> Large Language Models (LLMs) and generative AI (GenAI) systems such as
ChatGPT, Claude, Gemini, LLaMA, and Copilot, developed by OpenAI, Anthropic,
Google, Meta, and Microsoft are reshaping digital platforms and app ecosystems
while introducing key challenges in cybersecurity, privacy, and platform
integrity. Our analysis shows alarming trends: LLM-assisted malware is
projected to rise from 2% in 2021 to 50% by 2025; AI-generated Google reviews
grew from 1.2% in 2021 to 12.21% in 2023, with an expected 30% by 2025; AI scam
reports surged 456%; and misinformation sites increased over 1500%, with a
50-60% increase in deepfakes in 2024. Concurrently, as LLMs have facilitated
code development, mobile app submissions grew from 1.8 million in 2020 to 3.0
million in 2024, with 3.6 million expected by 2025. To address AI threats,
platforms from app stores like Google Play and Apple to developer hubs like
GitHub Copilot, and social platforms like TikTok and Facebook, to marketplaces
like Amazon are deploying AI and LLM-based defenses. This highlights the dual
nature of these technologies as both the source of new threats and the
essential tool for their mitigation. Integrating LLMs into clinical diagnostics
also raises concerns about accuracy, bias, and safety, needing strong
governance. Drawing on a comprehensive analysis of 455 references, this paper
presents a survey of LLM and GenAI risks. We propose a strategic roadmap and
operational blueprint integrating policy auditing (CCPA, GDPR), fraud
detection, and compliance automation, and an advanced LLM-DA stack with modular
components including multi LLM routing, agentic memory, and governance layers
to enhance platform integrity. We also provide actionable insights,
cross-functional best practices, and real-world case studies. These
contributions offer paths to scalable trust, safety, and responsible innovation
across digital platforms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.08918v1">Quantifying Mix Network Privacy Erosion with Generative Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-10T15:43:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vasilios Mavroudis, Tariq Elahi</p>
    <p><b>Summary:</b> Modern mix networks improve over Tor and provide stronger privacy guarantees
by robustly obfuscating metadata. As long as a message is routed through at
least one honest mixnode, the privacy of the users involved is safeguarded.
However, the complexity of the mixing mechanisms makes it difficult to estimate
the cumulative privacy erosion occurring over time. This work uses a generative
model trained on mixnet traffic to estimate the loss of privacy when users
communicate persistently over a period of time. We train our large-language
model from scratch on our specialized network traffic ``language'' and then use
it to measure the sender-message unlinkability in various settings (e.g. mixing
strategies, security parameters, observation window). Our findings reveal
notable differences in privacy levels among mix strategies, even when they have
similar mean latencies. In comparison, we demonstrate the limitations of
traditional privacy metrics, such as entropy and log-likelihood, in fully
capturing an adversary's potential to synthesize information from multiple
observations. Finally, we show that larger models exhibit greater sample
efficiency and superior capabilities implying that further advancements in
transformers will consequently enhance the accuracy of model-based privacy
estimates.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.08654v1">A Privacy-Preserving Federated Learning Framework for Generalizable CBCT
  to Synthetic CT Translation in Head and Neck</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-10T10:10:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ciro Benito Raggio, Paolo Zaffino, Maria Francesca Spadea</p>
    <p><b>Summary:</b> Shortened Abstract
  Cone-beam computed tomography (CBCT) has become a widely adopted modality for
image-guided radiotherapy (IGRT). However, CBCT suffers from increased noise,
limited soft-tissue contrast, and artifacts, resulting in unreliable Hounsfield
unit values and hindering direct dose calculation. Synthetic CT (sCT)
generation from CBCT addresses these issues, especially using deep learning
(DL) methods. Existing approaches are limited by institutional heterogeneity,
scanner-dependent variations, and data privacy regulations that prevent
multi-center data sharing.
  To overcome these challenges, we propose a cross-silo horizontal federated
learning (FL) approach for CBCT-to-sCT synthesis in the head and neck region,
extending our FedSynthCT framework. A conditional generative adversarial
network was collaboratively trained on data from three European medical centers
in the public SynthRAD2025 challenge dataset.
  The federated model demonstrated effective generalization across centers,
with mean absolute error (MAE) ranging from $64.38\pm13.63$ to $85.90\pm7.10$
HU, structural similarity index (SSIM) from $0.882\pm0.022$ to $0.922\pm0.039$,
and peak signal-to-noise ratio (PSNR) from $32.86\pm0.94$ to $34.91\pm1.04$ dB.
Notably, on an external validation dataset of 60 patients, comparable
performance was achieved (MAE: $75.22\pm11.81$ HU, SSIM: $0.904\pm0.034$, PSNR:
$33.52\pm2.06$ dB) without additional training, confirming robust
generalization despite protocol, scanner differences and registration errors.
  These findings demonstrate the technical feasibility of FL for CBCT-to-sCT
synthesis while preserving data privacy and offer a collaborative solution for
developing generalizable models across institutions without centralized data
sharing or site-specific fine-tuning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.08347v2">Differentially Private Relational Learning with Entity-level Privacy
  Guarantees</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-10T02:03:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yinan Huang, Haoteng Yin, Eli Chien, Rongzhe Wei, Pan Li</p>
    <p><b>Summary:</b> Learning with relational and network-structured data is increasingly vital in
sensitive domains where protecting the privacy of individual entities is
paramount. Differential Privacy (DP) offers a principled approach for
quantifying privacy risks, with DP-SGD emerging as a standard mechanism for
private model training. However, directly applying DP-SGD to relational
learning is challenging due to two key factors: (i) entities often participate
in multiple relations, resulting in high and difficult-to-control sensitivity;
and (ii) relational learning typically involves multi-stage, potentially
coupled (interdependent) sampling procedures that make standard privacy
amplification analyses inapplicable. This work presents a principled framework
for relational learning with formal entity-level DP guarantees. We provide a
rigorous sensitivity analysis and introduce an adaptive gradient clipping
scheme that modulates clipping thresholds based on entity occurrence frequency.
We also extend the privacy amplification results to a tractable subclass of
coupled sampling, where the dependence arises only through sample sizes. These
contributions lead to a tailored DP-SGD variant for relational data with
provable privacy guarantees. Experiments on fine-tuning text encoders over
text-attributed network-structured relational data demonstrate the strong
utility-privacy trade-offs of our approach. Our code is available at
https://github.com/Graph-COM/Node_DP.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.08330v1">Distortion Search, A Web Search Privacy Heuristic</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-10T01:35:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kato Mivule, Kenneth Hopkinson</p>
    <p><b>Summary:</b> Search engines have vast technical capabilities to retain Internet search
logs for each user and thus present major privacy vulnerabilities to both
individuals and organizations in revealing user intent. Additionally, many of
the web search privacy enhancing tools available today require that the user
trusts a third party, which make confidentiality of user intent even more
challenging. The user is left at the mercy of the third party without the
control over his or her own privacy. In this article, we suggest a user-centric
heuristic, Distortion Search, a web search query privacy methodology that works
by the formation of obfuscated search queries via the permutation of query
keyword categories, and by strategically applying k-anonymised web navigational
clicks on URLs and Ads to generate a distorted user profile and thus providing
specific user intent and query confidentiality. We provide empirical results
via the evaluation of distorted web search queries in terms of retrieved search
results and the resulting web ads from search engines. Preliminary experimental
results indicate that web search query and specific user intent privacy might
be achievable from the user side without the involvement of the search engine
or other third parties.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.08185v2">Agentic Surgical AI: Surgeon Style Fingerprinting and Privacy Risk
  Quantification via Discrete Diffusion in a Vision-Language-Action Framework</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-06-09T19:49:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Huixin Zhan, Jason H. Moore</p>
    <p><b>Summary:</b> Surgeons exhibit distinct operating styles shaped by training, experience,
and motor behavior-yet most surgical AI systems overlook this personalization
signal. We propose a novel agentic modeling approach for surgeon-specific
behavior prediction in robotic surgery, combining a discrete diffusion
framework with a vision-language-action (VLA) pipeline. Gesture prediction is
framed as a structured sequence denoising task, conditioned on multimodal
inputs including surgical video, intent language, and personalized embeddings
of surgeon identity and skill. These embeddings are encoded through natural
language prompts using third-party language models, allowing the model to
retain individual behavioral style without exposing explicit identity. We
evaluate our method on the JIGSAWS dataset and demonstrate that it accurately
reconstructs gesture sequences while learning meaningful motion fingerprints
unique to each surgeon. To quantify the privacy implications of
personalization, we perform membership inference attacks and find that more
expressive embeddings improve task performance but simultaneously increase
susceptibility to identity leakage. These findings demonstrate that while
personalized embeddings improve performance, they also increase vulnerability
to identity leakage, revealing the importance of balancing personalization with
privacy risk in surgical modeling. Code is available at:
https://github.com/huixin-zhan-ai/Surgeon_style_fingerprinting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.10024v1">Private Memorization Editing: Turning Memorization into a Defense to
  Strengthen Data Privacy in Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-06-09T17:57:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Elena Sofia Ruzzetti, Giancarlo A. Xompero, Davide Venditti, Fabio Massimo Zanzotto</p>
    <p><b>Summary:</b> Large Language Models (LLMs) memorize, and thus, among huge amounts of
uncontrolled data, may memorize Personally Identifiable Information (PII),
which should not be stored and, consequently, not leaked. In this paper, we
introduce Private Memorization Editing (PME), an approach for preventing
private data leakage that turns an apparent limitation, that is, the LLMs'
memorization ability, into a powerful privacy defense strategy. While attacks
against LLMs have been performed exploiting previous knowledge regarding their
training data, our approach aims to exploit the same kind of knowledge in order
to make a model more robust. We detect a memorized PII and then mitigate the
memorization of PII by editing a model knowledge of its training data. We
verify that our procedure does not affect the underlying language model while
making it more robust against privacy Training Data Extraction attacks. We
demonstrate that PME can effectively reduce the number of leaked PII in a
number of configurations, in some cases even reducing the accuracy of the
privacy attacks to zero.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.07957v1">Understanding the Error Sensitivity of Privacy-Aware Computing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Hardware Architecture-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-09T17:27:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Matías Mazzanti, Esteban Mocskos, Augusto Vega, Pradip Bose</p>
    <p><b>Summary:</b> Homomorphic Encryption (HE) enables secure computation on encrypted data
without decryption, allowing a great opportunity for privacy-preserving
computation. In particular, domains such as healthcare, finance, and
government, where data privacy and security are of utmost importance, can
benefit from HE by enabling third-party computation and services on sensitive
data. In other words, HE constitutes the "Holy Grail" of cryptography: data
remains encrypted all the time, being protected while in use.
  HE's security guarantees rely on noise added to data to make relatively
simple problems computationally intractable. This error-centric intrinsic HE
mechanism generates new challenges related to the fault tolerance and
robustness of HE itself: hardware- and software-induced errors during HE
operation can easily evade traditional error detection and correction
mechanisms, resulting in silent data corruption (SDC).
  In this work, we motivate a thorough discussion regarding the sensitivity of
HE applications to bit faults and provide a detailed error characterization
study of CKKS (Cheon-Kim-Kim-Song). This is one of the most popular HE schemes
due to its fixed-point arithmetic support for AI and machine learning
applications. We also delve into the impact of the residue number system (RNS)
and the number theoretic transform (NTT), two widely adopted HE optimization
techniques, on CKKS' error sensitivity. To the best of our knowledge, this is
the first work that looks into the robustness and error sensitivity of
homomorphic encryption and, as such, it can pave the way for critical future
work in this area.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.07868v1">Securing Unbounded Differential Privacy Against Timing Attacks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-09T15:35:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zachary Ratliff, Salil Vadhan</p>
    <p><b>Summary:</b> Recent works have started to theoretically investigate how we can protect
differentially private programs against timing attacks, by making the joint
distribution the output and the runtime differentially private (JOT-DP).
However, the existing approaches to JOT-DP have some limitations, particularly
in the setting of unbounded DP (which protects the size of the dataset and
applies to arbitrarily large datasets). First, the known conversion of pure DP
programs to pure JOT-DP programs in the unbounded setting (a) incurs a constant
additive increase in error probability (and thus does not provide vanishing
error as $n\to\infty$) (b) produces JOT-DP programs that fail to preserve the
computational efficiency of the original pure DP program and (c) is analyzed in
a toy computational model in which the runtime is defined to be the number of
coin flips. In this work, we overcome these limitations. Specifically, we show
that the error required for pure JOT-DP in the unbounded setting depends on the
model of computation. In a randomized RAM model where the dataset size $n$ is
given (or can be computed in constant time) and we can generate random numbers
(not just random bits) in constant time, polynomially small error probability
is necessary and sufficient. If $n$ is not given or we only have a random-bit
generator, an (arbitrarily small) constant error probability is necessary and
sufficient. The aforementioned positive results are proven by efficient
procedures to convert any pure JOT-DP program $P$ in the upper-bounded setting
to a pure JOT-DP program $P'$ in the unbounded setting, such that the output
distribution of $P'$ is $\gamma$-close in total variation distance to that of
$P$, where $\gamma$ is either an arbitrarily small constant or polynomially
small, depending on the model of computation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.07605v2">TimberStrike: Dataset Reconstruction Attack Revealing Privacy Leakage in
  Federated Tree-Based Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-09T10:06:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marco Di Gennaro, Giovanni De Lucia, Stefano Longari, Stefano Zanero, Michele Carminati</p>
    <p><b>Summary:</b> Federated Learning has emerged as a privacy-oriented alternative to
centralized Machine Learning, enabling collaborative model training without
direct data sharing. While extensively studied for neural networks, the
security and privacy implications of tree-based models remain underexplored.
This work introduces TimberStrike, an optimization-based dataset reconstruction
attack targeting horizontally federated tree-based models. Our attack, carried
out by a single client, exploits the discrete nature of decision trees by using
split values and decision paths to infer sensitive training data from other
clients. We evaluate TimberStrike on State-of-the-Art federated gradient
boosting implementations across multiple frameworks, including Flower, NVFlare,
and FedTree, demonstrating their vulnerability to privacy breaches. On a
publicly available stroke prediction dataset, TimberStrike consistently
reconstructs between 73.05% and 95.63% of the target dataset across all
implementations. We further analyze Differential Privacy, showing that while it
partially mitigates the attack, it also significantly degrades model
performance. Our findings highlight the need for privacy-preserving mechanisms
specifically designed for tree-based Federated Learning systems, and we provide
preliminary insights into their design.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.07555v2">Synthesize Privacy-Preserving High-Resolution Images via Private Textual
  Intermediaries</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-06-09T08:48:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haoxiang Wang, Zinan Lin, Da Yu, Huishuai Zhang</p>
    <p><b>Summary:</b> Generating high fidelity, differentially private (DP) synthetic images offers
a promising route to share and analyze sensitive visual data without
compromising individual privacy. However, existing DP image synthesis methods
struggle to produce high resolution outputs that faithfully capture the
structure of the original data. In this paper, we introduce a novel method,
referred to as Synthesis via Private Textual Intermediaries (SPTI), that can
generate high resolution DP images with easy adoption. The key idea is to shift
the challenge of DP image synthesis from the image domain to the text domain by
leveraging state of the art DP text generation methods. SPTI first summarizes
each private image into a concise textual description using image to text
models, then applies a modified Private Evolution algorithm to generate DP
text, and finally reconstructs images using text to image models. Notably, SPTI
requires no model training, only inference with off the shelf models. Given a
private dataset, SPTI produces synthetic images of substantially higher quality
than prior DP approaches. On the LSUN Bedroom dataset, SPTI attains an FID less
than or equal to 26.71 under epsilon equal to 1.0, improving over Private
Evolution FID of 40.36. Similarly, on MM CelebA HQ, SPTI achieves an FID less
than or equal to 33.27 at epsilon equal to 1.0, compared to 57.01 from DP fine
tuning baselines. Overall, our results demonstrate that Synthesis via Private
Textual Intermediaries provides a resource efficient and proprietary model
compatible framework for generating high resolution DP synthetic images,
greatly expanding access to private visual datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.07102v1">Decentralized Optimization with Amplified Privacy via Efficient
  Communication</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2025-06-08T12:14:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wei Huo, Changxin Liu, Kemi Ding, Karl Henrik Johansson, Ling Shi</p>
    <p><b>Summary:</b> Decentralized optimization is crucial for multi-agent systems, with
significant concerns about communication efficiency and privacy. This paper
explores the role of efficient communication in decentralized stochastic
gradient descent algorithms for enhancing privacy preservation. We develop a
novel algorithm that incorporates two key features: random agent activation and
sparsified communication. Utilizing differential privacy, we demonstrate that
these features reduce noise without sacrificing privacy, thereby amplifying the
privacy guarantee and improving accuracy. Additionally, we analyze the
convergence and the privacy-accuracy-communication trade-off of the proposed
algorithm. Finally, we present experimental results to illustrate the
effectiveness of our algorithm.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.06742v1">LADSG: Label-Anonymized Distillation and Similar Gradient Substitution
  for Label Privacy in Vertical Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-07T10:10:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zeyu Yan, Yifei Yao, Xuanbing Wen, Juli Zhang, Kai Fan</p>
    <p><b>Summary:</b> Vertical federated learning (VFL) has become a key paradigm for collaborative
machine learning, enabling multiple parties to train models over distributed
feature spaces while preserving data privacy. Despite security protocols that
defend against external attacks - such as gradient masking and encryption,
which prevent unauthorized access to sensitive data - recent label inference
attacks from within the system have emerged. These attacks exploit gradients
and semantic embeddings to reconstruct private labels, bypassing traditional
defenses. For example, the passive label inference attack can reconstruct tens
of thousands of participants' private data using just 40 auxiliary labels,
posing a significant security threat. Existing defenses address single leakage
pathways, such as gradient leakage or label exposure. As attack strategies
evolve, their limitations become clear, especially against hybrid attacks that
combine multiple vectors. To address this, we propose Label-Anonymized Defense
with Substitution Gradient (LADSG), a unified defense framework that integrates
gradient substitution, label anonymization, and anomaly detection. LADSG
mitigates both gradient and label leakage while maintaining the scalability and
efficiency of VFL. Experiments on six real-world datasets show that LADSG
reduces label inference attack success rates by 30-60%, with minimal
computational overhead, underscoring the importance of lightweight defenses in
securing VFL.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.06591v1">Privacy Perspectives and Practices of Chinese Smart Home Product Teams</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-06-06T23:49:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shijing He, Yaxiong Lei, Xiao Zhan, Chi Zhang, Juan Ye, Ruba Abu-Salma, Jose Such</p>
    <p><b>Summary:</b> Previous research has explored the privacy needs and concerns of device
owners, primary users, and different bystander groups with regard to smart home
devices like security cameras, smart speakers, and hubs, but little is known
about the privacy views and practices of smart home product teams, particularly
those in non-Western contexts. This paper presents findings from 27
semi-structured interviews with Chinese smart home product team members,
including product/project managers, software/hardware engineers, user
experience (UX) designers, legal/privacy experts, and marketers/operation
specialists. We examine their privacy perspectives, practices, and risk
mitigation strategies. Our results show that participants emphasized compliance
with Chinese data privacy laws, which typically prioritized national security
over individual privacy rights. China-specific cultural, social, and legal
factors also influenced participants' ethical considerations and attitudes
toward balancing user privacy and security with convenience. Drawing on our
findings, we propose a set of recommendations for smart home product teams,
along with socio-technical and legal interventions to address smart home
privacy issues-especially those belonging to at-risk groups-in Chinese
multi-user smart homes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.06530v1">Breaking the Gaussian Barrier: Residual-PAC Privacy for Automatic
  Privatization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-06T20:52:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tao Zhang, Yevgeniy Vorobeychik</p>
    <p><b>Summary:</b> The Probably Approximately Correct (PAC) Privacy framework [1] provides a
powerful instance-based methodology for certifying privacy in complex
data-driven systems. However, existing PAC Privacy algorithms rely on a
Gaussian mutual information upper bound. We show that this is in general too
conservative: the upper bound obtained by these algorithms is tight if and only
if the perturbed mechanism output is jointly Gaussian with independent Gaussian
noise. To address the inefficiency inherent in the Gaussian-based approach, we
introduce Residual PAC Privacy, an f-divergence-based measure that quantifies
the privacy remaining after adversarial inference. When instantiated with
Kullback-Leibler divergence, Residual-PAC Privacy is governed by conditional
entropy. Moreover, we propose Stackelberg Residual-PAC (SR-PAC) privatization
mechanisms for RPAC Privacy, a game-theoretic framework that selects optimal
noise distributions through convex bilevel optimization. Our approach achieves
tight privacy budget utilization for arbitrary data distributions. Moreover, it
naturally composes under repeated mechanisms and provides provable privacy
guarantees with higher statistical efficiency. Numerical experiments
demonstrate that SR-PAC certifies the target privacy budget while consistently
improving utility compared to existing methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.06124v1">PrivTru: A Privacy-by-Design Data Trustee Minimizing Information Leakage</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-06T14:33:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lukas Gehring, Florian Tschorsch</p>
    <p><b>Summary:</b> Data trustees serve as intermediaries that facilitate secure data sharing
between independent parties. This paper offers a technical perspective on Data
trustees, guided by privacy-by-design principles. We introduce PrivTru, an
instantiation of a data trustee that provably achieves optimal privacy
properties. Therefore, PrivTru calculates the minimal amount of information the
data trustee needs to request from data sources to respond to a given query.
Our analysis shows that PrivTru minimizes information leakage to the data
trustee, regardless of the trustee's prior knowledge, while preserving the
utility of the data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.06062v2">Minoritised Ethnic People's Security and Privacy Concerns and Responses
  towards Essential Online Services</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> 
  <p><b>Published on:</b> 2025-06-06T13:17:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aunam Quyoum, Mark Wong, Sebati Ghosh, Siamak F. Shahandashti</p>
    <p><b>Summary:</b> Minoritised ethnic people are marginalised in society, and therefore at a
higher risk of adverse online harms, including those arising from the loss of
security and privacy of personal data. Despite this, there has been very little
research focused on minoritised ethnic people's security and privacy concerns,
attitudes, and behaviours. In this work, we provide the results of one of the
first studies in this regard. We explore minoritised ethnic people's
experiences of using essential online services across three sectors: health,
social housing, and energy, their security and privacy-related concerns, and
responses towards these services. We conducted a thematic analysis of 44
semi-structured interviews with people of various reported minoritised
ethnicities in the UK. Privacy concerns and lack of control over personal data
emerged as a major theme, with many interviewees considering privacy as their
most significant concern when using online services. Several creative tactics
to exercise some agency were reported, including selective and inconsistent
disclosure of personal data. A core concern about how data may be used was
driven by a fear of repercussions, including penalisation and discrimination,
influenced by prior experiences of institutional and online racism. The
increased concern and potential for harm resulted in minoritised ethnic people
grappling with a higher-stakes dilemma of whether to disclose personal
information online or not. Furthermore, trust in institutions, or lack thereof,
was found to be embedded throughout as a basis for adapting behaviour. We draw
on our results to provide lessons learned for the design of more inclusive,
marginalisation-aware, and privacy-preserving online services.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.05908v1">QualitEye: Public and Privacy-preserving Gaze Data Quality Verification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-06-06T09:27:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mayar Elfares, Pascal Reisert, Ralf Küsters, Andreas Bulling</p>
    <p><b>Summary:</b> Gaze-based applications are increasingly advancing with the availability of
large datasets but ensuring data quality presents a substantial challenge when
collecting data at scale. It further requires different parties to collaborate,
therefore, privacy concerns arise. We propose QualitEye--the first method for
verifying image-based gaze data quality. QualitEye employs a new semantic
representation of eye images that contains the information required for
verification while excluding irrelevant information for better domain
adaptation. QualitEye covers a public setting where parties can freely exchange
data and a privacy-preserving setting where parties cannot reveal their raw
data nor derive gaze features/labels of others with adapted private set
intersection protocols. We evaluate QualitEye on the MPIIFaceGaze and
GazeCapture datasets and achieve a high verification performance (with a small
overhead in runtime for privacy-preserving versions). Hence, QualitEye paves
the way for new gaze analysis methods at the intersection of machine learning,
human-computer interaction, and cryptography.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.05743v1">When Better Features Mean Greater Risks: The Performance-Privacy
  Trade-Off in Contrastive Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-06-06T05:03:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruining Sun, Hongsheng Hu, Wei Luo, Zhaoxi Zhang, Yanjun Zhang, Haizhuan Yuan, Leo Yu Zhang</p>
    <p><b>Summary:</b> With the rapid advancement of deep learning technology, pre-trained encoder
models have demonstrated exceptional feature extraction capabilities, playing a
pivotal role in the research and application of deep learning. However, their
widespread use has raised significant concerns about the risk of training data
privacy leakage. This paper systematically investigates the privacy threats
posed by membership inference attacks (MIAs) targeting encoder models, focusing
on contrastive learning frameworks. Through experimental analysis, we reveal
the significant impact of model architecture complexity on membership privacy
leakage: As more advanced encoder frameworks improve feature-extraction
performance, they simultaneously exacerbate privacy-leakage risks. Furthermore,
this paper proposes a novel membership inference attack method based on the
p-norm of feature vectors, termed the Embedding Lp-Norm Likelihood Attack
(LpLA). This method infers membership status, by leveraging the statistical
distribution characteristics of the p-norm of feature vectors. Experimental
results across multiple datasets and model architectures demonstrate that LpLA
outperforms existing methods in attack performance and robustness, particularly
under limited attack knowledge and query volumes. This study not only uncovers
the potential risks of privacy leakage in contrastive learning frameworks, but
also provides a practical basis for privacy protection research in encoder
models. We hope that this work will draw greater attention to the privacy risks
associated with self-supervised learning models and shed light on the
importance of a balance between model utility and training data privacy. Our
code is publicly available at: https://github.com/SeroneySun/LpLA_code.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.05683v3">Multi-Modal Multi-Task Federated Foundation Models for Next-Generation
  Extended Reality Systems: Towards Privacy-Preserving Distributed Intelligence
  in AR/VR/MR</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Multimedia-5BC0EB">
  <p><b>Published on:</b> 2025-06-06T02:23:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fardis Nadimi, Payam Abdisarabshali, Kasra Borazjani, Jacob Chakareski, Seyyedali Hosseinalipour</p>
    <p><b>Summary:</b> Extended reality (XR) systems, which consist of virtual reality (VR),
augmented reality (AR), and mixed reality (XR), offer a transformative
interface for immersive, multi-modal, and embodied human-computer interaction.
In this paper, we envision that multi-modal multi-task (M3T) federated
foundation models (FedFMs) can offer transformative capabilities for XR systems
through integrating the representational strength of M3T foundation models
(FMs) with the privacy-preserving model training principles of federated
learning (FL). We present a modular architecture for FedFMs, which entails
different coordination paradigms for model training and aggregations. Central
to our vision is the codification of XR challenges that affect the
implementation of FedFMs under the SHIFT dimensions: (1) Sensor and modality
diversity, (2) Hardware heterogeneity and system-level constraints, (3)
Interactivity and embodied personalization, (4) Functional/task variability,
and (5) Temporality and environmental variability. We illustrate the
manifestation of these dimensions across a set of emerging and anticipated
applications of XR systems. Finally, we propose evaluation metrics, dataset
requirements, and design tradeoffs necessary for the development of
resource-aware FedFMs in XR. This perspective aims to chart the technical and
conceptual foundations for context-aware privacy-preserving intelligence in the
next generation of XR systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.05503v1">On Differential Privacy for Adaptively Solving Search Problems via
  Sketching</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2025-06-05T18:40:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shiyuan Feng, Ying Feng, George Z. Li, Zhao Song, David P. Woodruff, Lichen Zhang</p>
    <p><b>Summary:</b> Recently differential privacy has been used for a number of streaming, data
structure, and dynamic graph problems as a means of hiding the internal
randomness of the data structure, so that multiple possibly adaptive queries
can be made without sacrificing the correctness of the responses. Although
these works use differential privacy to show that for some problems it is
possible to tolerate $T$ queries using $\widetilde{O}(\sqrt{T})$ copies of a
data structure, such results only apply to numerical estimation problems, and
only return the cost of an optimization problem rather than the solution
itself. In this paper, we investigate the use of differential privacy for
adaptive queries to search problems, which are significantly more challenging
since the responses to queries can reveal much more about the internal
randomness than a single numerical query. We focus on two classical search
problems: nearest neighbor queries and regression with arbitrary turnstile
updates. We identify key parameters to these problems, such as the number of
$c$-approximate near neighbors and the matrix condition number, and use
different differential privacy techniques to design algorithms returning the
solution vector with memory and time depending on these parameters. We give
algorithms for each of these problems that achieve similar tradeoffs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.05290v1">Big Bird: Privacy Budget Management for W3C's Privacy-Preserving
  Attribution API</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-05T17:45:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pierre Tholoniat, Alison Caulfield, Giorgio Cavicchioli, Mark Chen, Nikos Goutzoulias, Benjamin Case, Asaf Cidon, Roxana Geambasu, Mathias Lécuyer, Martin Thomson</p>
    <p><b>Summary:</b> Privacy-preserving advertising APIs like Privacy-Preserving Attribution (PPA)
are designed to enhance web privacy while enabling effective ad measurement.
PPA offers an alternative to cross-site tracking with encrypted reports
governed by differential privacy (DP), but current designs lack a principled
approach to privacy budget management, creating uncertainty around critical
design decisions. We present Big Bird, a privacy budget manager for PPA that
clarifies per-site budget semantics and introduces a global budgeting system
grounded in resource isolation principles. Big Bird enforces utility-preserving
limits via quota budgets and improves global budget utilization through a novel
batched scheduling algorithm. Together, these mechanisms establish a robust
foundation for enforcing privacy protections in adversarial environments. We
implement Big Bird in Firefox and evaluate it on real-world ad data,
demonstrating its resilience and effectiveness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.05101v1">Privacy Amplification Through Synthetic Data: Insights from Linear
  Regression</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2025-06-05T14:44:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Clément Pierquin, Aurélien Bellet, Marc Tommasi, Matthieu Boussard</p>
    <p><b>Summary:</b> Synthetic data inherits the differential privacy guarantees of the model used
to generate it. Additionally, synthetic data may benefit from privacy
amplification when the generative model is kept hidden. While empirical studies
suggest this phenomenon, a rigorous theoretical understanding is still lacking.
In this paper, we investigate this question through the well-understood
framework of linear regression. First, we establish negative results showing
that if an adversary controls the seed of the generative model, a single
synthetic data point can leak as much information as releasing the model
itself. Conversely, we show that when synthetic data is generated from random
inputs, releasing a limited number of synthetic data points amplifies privacy
beyond the model's inherent guarantees. We believe our findings in linear
regression can serve as a foundation for deriving more general bounds in the
future.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.04978v1">Evaluating the Impact of Privacy-Preserving Federated Learning on CAN
  Intrusion Detection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-05T12:49:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gabriele Digregorio, Elisabetta Cainazzo, Stefano Longari, Michele Carminati, Stefano Zanero</p>
    <p><b>Summary:</b> The challenges derived from the data-intensive nature of machine learning in
conjunction with technologies that enable novel paradigms such as V2X and the
potential offered by 5G communication, allow and justify the deployment of
Federated Learning (FL) solutions in the vehicular intrusion detection domain.
In this paper, we investigate the effects of integrating FL strategies into the
machine learning-based intrusion detection process for on-board vehicular
networks. Accordingly, we propose a FL implementation of a state-of-the-art
Intrusion Detection System (IDS) for Controller Area Network (CAN), based on
LSTM autoencoders. We thoroughly evaluate its detection efficiency and
communication overhead, comparing it to a centralized version of the same
algorithm, thereby presenting it as a feasible solution.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.05421v2">TRIDENT -- A Three-Tier Privacy-Preserving Propaganda Detection Model in
  Mobile Networks using Transformers, Adversarial Learning, and Differential
  Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-06-05T02:38:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Al Nahian Bin Emran, Dhiman Goswami, Md Hasan Ullah Sadi, Sanchari Das</p>
    <p><b>Summary:</b> The proliferation of propaganda on mobile platforms raises critical concerns
around detection accuracy and user privacy. To address this, we propose TRIDENT
- a three-tier propaganda detection model implementing transformers,
adversarial learning, and differential privacy which integrates syntactic
obfuscation and label perturbation to mitigate privacy leakage while
maintaining propaganda detection accuracy. TRIDENT leverages multilingual
back-translation to introduce semantic variance, character-level noise, and
entity obfuscation for differential privacy enforcement, and combines these
techniques into a unified defense mechanism. Using a binary propaganda
classification dataset, baseline transformer models (BERT, GPT-2) we achieved
F1 scores of 0.89 and 0.90. Applying TRIDENT's third-tier defense yields a
reduced but effective cumulative F1 of 0.83, demonstrating strong privacy
protection across mobile ML deployments with minimal degradation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.04036v1">Privacy and Security Threat for OpenAI GPTs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-06-04T14:58:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wei Wenying, Zhao Kaifa, Xue Lei, Fan Ming</p>
    <p><b>Summary:</b> Large language models (LLMs) demonstrate powerful information handling
capabilities and are widely integrated into chatbot applications. OpenAI
provides a platform for developers to construct custom GPTs, extending
ChatGPT's functions and integrating external services. Since its release in
November 2023, over 3 million custom GPTs have been created. However, such a
vast ecosystem also conceals security and privacy threats. For developers,
instruction leaking attacks threaten the intellectual property of instructions
in custom GPTs through carefully crafted adversarial prompts. For users,
unwanted data access behavior by custom GPTs or integrated third-party services
raises significant privacy concerns. To systematically evaluate the scope of
threats in real-world LLM applications, we develop three phases instruction
leaking attacks target GPTs with different defense level. Our widespread
experiments on 10,000 real-world custom GPTs reveal that over 98.8% of GPTs are
vulnerable to instruction leaking attacks via one or more adversarial prompts,
and half of the remaining GPTs can also be attacked through multiround
conversations. We also developed a framework to assess the effectiveness of
defensive strategies and identify unwanted behaviors in custom GPTs. Our
findings show that 77.5% of custom GPTs with defense strategies are vulnerable
to basic instruction leaking attacks. Additionally, we reveal that 738 custom
GPTs collect user conversational information, and identified 8 GPTs exhibiting
data access behaviors that are unnecessary for their intended functionalities.
Our findings raise awareness among GPT developers about the importance of
integrating specific defensive strategies in their instructions and highlight
users' concerns about data privacy when using LLM-based applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.03870v1">Evaluating Apple Intelligence's Writing Tools for Privacy Against Large
  Language Model-Based Inference Attacks: Insights from Early Datasets</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-04T12:01:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohd. Farhan Israk Soumik, Syed Mhamudul Hasan, Abdur R. Shahid</p>
    <p><b>Summary:</b> The misuse of Large Language Models (LLMs) to infer emotions from text for
malicious purposes, known as emotion inference attacks, poses a significant
threat to user privacy. In this paper, we investigate the potential of Apple
Intelligence's writing tools, integrated across iPhone, iPad, and MacBook, to
mitigate these risks through text modifications such as rewriting and tone
adjustment. By developing early novel datasets specifically for this purpose,
we empirically assess how different text modifications influence LLM-based
detection. This capability suggests strong potential for Apple Intelligence's
writing tools as privacy-preserving mechanisms. Our findings lay the groundwork
for future adaptive rewriting systems capable of dynamically neutralizing
sensitive emotional content to enhance user privacy. To the best of our
knowledge, this research provides the first empirical analysis of Apple
Intelligence's text-modification tools within a privacy-preservation context
with the broader goal of developing on-device, user-centric privacy-preserving
mechanisms to protect against LLMs-based advanced inference attacks on deployed
systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.03618v1">GCFL: A Gradient Correction-based Federated Learning Framework for
  Privacy-preserving CPSS</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-06-04T06:52:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiayi Wan, Xiang Zhu, Fanzhen Liu, Wei Fan, Xiaolong Xu</p>
    <p><b>Summary:</b> Federated learning, as a distributed architecture, shows great promise for
applications in Cyber-Physical-Social Systems (CPSS). In order to mitigate the
privacy risks inherent in CPSS, the integration of differential privacy with
federated learning has attracted considerable attention. Existing research
mainly focuses on dynamically adjusting the noise added or discarding certain
gradients to mitigate the noise introduced by differential privacy. However,
these approaches fail to remove the noise that hinders convergence and correct
the gradients affected by the noise, which significantly reduces the accuracy
of model classification. To overcome these challenges, this paper proposes a
novel framework for differentially private federated learning that balances
rigorous privacy guarantees with accuracy by introducing a server-side gradient
correction mechanism. Specifically, after clients perform gradient clipping and
noise perturbation, our framework detects deviations in the noisy local
gradients and employs a projection mechanism to correct them, mitigating the
negative impact of noise. Simultaneously, gradient projection promotes the
alignment of gradients from different clients and guides the model towards
convergence to a global optimum. We evaluate our framework on several benchmark
datasets, and the experimental results demonstrate that it achieves
state-of-the-art performance under the same privacy budget.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.02998v1">A Multi-Agent Framework for Mitigating Dialect Biases in Privacy Policy
  Question-Answering Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-06-03T15:32:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Đorđe Klisura, Astrid R Bernaga Torres, Anna Karen Gárate-Escamilla, Rajesh Roshan Biswal, Ke Yang, Hilal Pataci, Anthony Rios</p>
    <p><b>Summary:</b> Privacy policies inform users about data collection and usage, yet their
complexity limits accessibility for diverse populations. Existing Privacy
Policy Question Answering (QA) systems exhibit performance disparities across
English dialects, disadvantaging speakers of non-standard varieties. We propose
a novel multi-agent framework inspired by human-centered design principles to
mitigate dialectal biases. Our approach integrates a Dialect Agent, which
translates queries into Standard American English (SAE) while preserving
dialectal intent, and a Privacy Policy Agent, which refines predictions using
domain expertise. Unlike prior approaches, our method does not require
retraining or dialect-specific fine-tuning, making it broadly applicable across
models and domains. Evaluated on PrivacyQA and PolicyQA, our framework improves
GPT-4o-mini's zero-shot accuracy from 0.394 to 0.601 on PrivacyQA and from
0.352 to 0.464 on PolicyQA, surpassing or matching few-shot baselines without
additional training data. These results highlight the effectiveness of
structured agent collaboration in mitigating dialect biases and underscore the
importance of designing NLP systems that account for linguistic diversity to
ensure equitable access to privacy information.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.02965v2">PC-MoE: Memory-Efficient and Privacy-Preserving Collaborative Training
  for Mixture-of-Experts LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-03T15:00:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ze Yu Zhang, Bolin Ding, Bryan Kian Hsiang Low</p>
    <p><b>Summary:</b> Mixture-of-Experts (MoE) has been gaining popularity due to its successful
adaptation to large language models (LLMs). In this work, we introduce
Privacy-preserving Collaborative Mixture-of-Experts (PC-MoE), which leverages
the sparsity of the MoE architecture for memory-efficient decentralized
collaborative LLM training, enabling multiple parties with limited GPU-memory
and data resources to collectively train more capable LLMs than they could
achieve individually. At the same time, this approach protects training data
privacy of each participant by keeping training data, as well as parts of the
forward pass signal and gradients locally within each party. By design, PC-MoE
synergistically combines the strengths of distributed computation with strong
confidentiality assurances. Unlike most privacy-preserving schemes, which pay
for confidentiality with lower task accuracy, our framework breaks that
trade-off: across seven popular LLM benchmarks, it almost matches (and
sometimes exceeds) the performance and convergence rate of a fully centralized
model, enjoys near 70% peak GPU RAM reduction, while being fully robust against
reconstruction attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.02725v1">Recursive Privacy-Preserving Estimation Over Markov Fading Channels</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2025-06-03T10:33:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jie Huang, Fanlin Jia, Xiao He</p>
    <p><b>Summary:</b> In industrial applications, the presence of moving machinery, vehicles, and
personnel, contributes to the dynamic nature of the wireless channel. This time
variability induces channel fading, which can be effectively modeled using a
Markov fading channel (MFC). In this paper, we investigate the problem of
secure state estimation for systems that communicate over a MFC in the presence
of an eavesdropper. The objective is to enable a remote authorized user to
accurately estimate the states of a dynamic system, while considering the
potential interception of the sensor's packet through a wiretap channel. To
prevent information leakage, a novel co-design strategy is established, which
combines a privacy-preserving mechanism with a state estimator. To implement
our encoding scheme, a nonlinear mapping of the innovation is introduced based
on the weighted reconstructed innovation previously received by the legitimate
user. Corresponding to this encoding scheme, we design a recursive
privacy-preserving filtering algorithm to achieve accurate estimation. The
boundedness of estimation error dynamics at the legitimate user's side is
discussed and the divergence of the eavesdropper's estimation error is
analyzed, which demonstrates the effectiveness of our co-design strategy in
ensuring secrecy. Furthermore, a simulation example of a three-tank system is
provided to demonstrate the effectiveness and feasibility of our
privacy-preserving estimation method.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.02711v1">Privacy Leaks by Adversaries: Adversarial Iterations for Membership
  Inference Attack</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-03T10:09:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jing Xue, Zhishen Sun, Haishan Ye, Luo Luo, Xiangyu Chang, Ivor Tsang, Guang Dai</p>
    <p><b>Summary:</b> Membership inference attack (MIA) has become one of the most widely used and
effective methods for evaluating the privacy risks of machine learning models.
These attacks aim to determine whether a specific sample is part of the model's
training set by analyzing the model's output. While traditional membership
inference attacks focus on leveraging the model's posterior output, such as
confidence on the target sample, we propose IMIA, a novel attack strategy that
utilizes the process of generating adversarial samples to infer membership. We
propose to infer the member properties of the target sample using the number of
iterations required to generate its adversarial sample. We conduct experiments
across multiple models and datasets, and our results demonstrate that the
number of iterations for generating an adversarial sample is a reliable feature
for membership inference, achieving strong performance both in black-box and
white-box attack scenarios. This work provides a new perspective for evaluating
model privacy and highlights the potential of adversarial example-based
features for privacy leakage assessment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.02563v1">Privacy-Preserving Federated Convex Optimization: Balancing
  Partial-Participation and Efficiency via Noise Cancellation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-03T07:48:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Roie Reshef, Kfir Yehuda Levy</p>
    <p><b>Summary:</b> This paper tackles the challenge of achieving Differential Privacy (DP) in
Federated Learning (FL) under partial-participation, where only a subset of the
machines participate in each time-step. While previous work achieved optimal
performance in full-participation settings, these methods struggled to extend
to partial-participation scenarios. Our approach fills this gap by introducing
a novel noise-cancellation mechanism that preserves privacy without sacrificing
convergence rates or computational efficiency. We analyze our method within the
Stochastic Convex Optimization (SCO) framework and show that it delivers
optimal performance for both homogeneous and heterogeneous data distributions.
This work expands the applicability of DP in FL, offering an efficient and
practical solution for privacy-preserving learning in distributed systems with
partial participation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.02422v1">Enhancing Convergence, Privacy and Fairness for Wireless Personalized
  Federated Learning: Quantization-Assisted Min-Max Fair Scheduling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-03T04:13:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiyu Zhao, Qimei Cui, Ziqiang Du, Weicai Li, Xi Yu, Wei Ni, Ji Zhang, Xiaofeng Tao, Ping Zhang</p>
    <p><b>Summary:</b> Personalized federated learning (PFL) offers a solution to balancing
personalization and generalization by conducting federated learning (FL) to
guide personalized learning (PL). Little attention has been given to wireless
PFL (WPFL), where privacy concerns arise. Performance fairness of PL models is
another challenge resulting from communication bottlenecks in WPFL. This paper
exploits quantization errors to enhance the privacy of WPFL and proposes a
novel quantization-assisted Gaussian differential privacy (DP) mechanism. We
analyze the convergence upper bounds of individual PL models by considering the
impact of the mechanism (i.e., quantization errors and Gaussian DP noises) and
imperfect communication channels on the FL of WPFL. By minimizing the maximum
of the bounds, we design an optimal transmission scheduling strategy that
yields min-max fairness for WPFL with OFDMA interfaces. This is achieved by
revealing the nested structure of this problem to decouple it into subproblems
solved sequentially for the client selection, channel allocation, and power
control, and for the learning rates and PL-FL weighting coefficients.
Experiments validate our analysis and demonstrate that our approach
substantially outperforms alternative scheduling strategies by 87.08%, 16.21%,
and 38.37% in accuracy, the maximum test loss of participating clients, and
fairness (Jain's index), respectively.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.02410v1">Testing for large-dimensional covariance matrix under differential
  privacy</a></h3>
  
  <p><b>Published on:</b> 2025-06-03T03:53:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shiwei Sang, Yicheng Zeng, Xuehu Zhu, Shurong Zheng</p>
    <p><b>Summary:</b> The increasing prevalence of high-dimensional data across various
applications has raised significant privacy concerns in statistical inference.
In this paper, we propose a differentially private integrated statistic for
testing large-dimensional covariance structures, enabling accurate statistical
insights while safeguarding privacy. First, we analyze the global sensitivity
of sample eigenvalues for sub-Gaussian populations, where our method bypasses
the commonly assumed boundedness of data covariates. For sufficiently large
sample size, the privatized statistic guarantees privacy with high probability.
Furthermore, when the ratio of dimension to sample size, $d/n \to y \in (0,
\infty)$, the privatized test is asymptotically distribution-free with
well-known critical values, and detects the local alternative hypotheses
distinct from the null at the fastest rate of $1/\sqrt{n}$. Extensive numerical
studies on synthetic and real data showcase the validity and powerfulness of
our proposed method.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.02156v2">Mitigating Data Poisoning Attacks to Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-02T18:37:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaolin Li, Ninghui Li, Boyang Wang, Wenhai Sun</p>
    <p><b>Summary:</b> The distributed nature of local differential privacy (LDP) invites data
poisoning attacks and poses unforeseen threats to the underlying LDP-supported
applications. In this paper, we propose a comprehensive mitigation framework
for popular frequency estimation, which contains a suite of novel defenses,
including malicious user detection, attack pattern recognition, and damaged
utility recovery. In addition to existing attacks, we explore new adaptive
adversarial activities for our mitigation design. For detection, we present a
new method to precisely identify bogus reports and thus LDP aggregation can be
performed over the ``clean'' data. When the attack behavior becomes stealthy
and direct filtering out malicious users is difficult, we further propose a
detection that can effectively recognize hidden adversarial patterns, thus
facilitating the decision-making of service providers. These detection methods
require no additional data and attack information and incur minimal
computational cost. Our experiment demonstrates their excellent performance and
substantial improvement over previous work in various settings. In addition, we
conduct an empirical analysis of LDP post-processing for corrupted data
recovery and propose a new post-processing method, through which we reveal new
insights into protocol recommendations in practice and key design principles
for future research.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.01907v1">SMOTE-DP: Improving Privacy-Utility Tradeoff with Synthetic Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2025-06-02T17:27:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yan Zhou, Bradley Malin, Murat Kantarcioglu</p>
    <p><b>Summary:</b> Privacy-preserving data publication, including synthetic data sharing, often
experiences trade-offs between privacy and utility. Synthetic data is generally
more effective than data anonymization in balancing this trade-off, however,
not without its own challenges. Synthetic data produced by generative models
trained on source data may inadvertently reveal information about outliers.
Techniques specifically designed for preserving privacy, such as introducing
noise to satisfy differential privacy, often incur unpredictable and
significant losses in utility. In this work we show that, with the right
mechanism of synthetic data generation, we can achieve strong privacy
protection without significant utility loss. Synthetic data generators
producing contracting data patterns, such as Synthetic Minority Over-sampling
Technique (SMOTE), can enhance a differentially private data generator,
leveraging the strengths of both. We prove in theory and through empirical
demonstration that this SMOTE-DP technique can produce synthetic data that not
only ensures robust privacy protection but maintains utility in downstream
learning tasks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.01425v1">CSVAR: Enhancing Visual Privacy in Federated Learning via Adaptive
  Shuffling Against Overfitting</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-02T08:30:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhuo Chen, Zhenya Ma, Yan Zhang, Donghua Cai, Ye Zhang, Qiushi Li, Yongheng Deng, Ye Guo, Ju Ren,  Xuemin,  Shen</p>
    <p><b>Summary:</b> Although federated learning preserves training data within local privacy
domains, the aggregated model parameters may still reveal private
characteristics. This vulnerability stems from clients' limited training data,
which predisposes models to overfitting. Such overfitting enables models to
memorize distinctive patterns from training samples, thereby amplifying the
success probability of privacy attacks like membership inference. To enhance
visual privacy protection in FL, we present CSVAR(Channel-Wise Spatial Image
Shuffling with Variance-Guided Adaptive Region Partitioning), a novel image
shuffling framework to generate obfuscated images for secure data transmission
and each training epoch, addressing both overfitting-induced privacy leaks and
raw image transmission risks. CSVAR adopts region-variance as the metric to
measure visual privacy sensitivity across image regions. Guided by this, CSVAR
adaptively partitions each region into multiple blocks, applying fine-grained
partitioning to privacy-sensitive regions with high region-variances for
enhancing visual privacy protection and coarse-grained partitioning to
privacy-insensitive regions for balancing model utility. In each region, CSVAR
then shuffles between blocks in both the spatial domains and chromatic channels
to hide visual spatial features and disrupt color distribution. Experimental
evaluations conducted on diverse real-world datasets demonstrate that CSVAR is
capable of generating visually obfuscated images that exhibit high perceptual
ambiguity to human eyes, simultaneously mitigating the effectiveness of
adversarial data reconstruction attacks and achieving a good trade-off between
visual privacy protection and model utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.01325v1">Understanding the Identity-Transformation Approach in OIDC-Compatible
  Privacy-Preserving SSO Services</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-02T05:11:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jingqiang Lin, Baitao Zhang, Wei Wang, Quanwei Cai, Jiwu Jing, Huiyang He</p>
    <p><b>Summary:</b> OpenID Connect (OIDC) enables a user with commercial-off-the-shelf browsers
to log into multiple websites, called relying parties (RPs), by her username
and credential set up in another trusted web system, called the identity
provider (IdP). Identity transformations are proposed in UppreSSO to provide
OIDC-compatible SSO services, preventing both IdP-based login tracing and
RP-based identity linkage. While security and privacy of SSO services in
UppreSSO have been proved, several essential issues of this
identity-transformation approach are not well studied. In this paper, we
comprehensively investigate the approach as below. Firstly, several suggestions
for the efficient integration of identity transformations in OIDC-compatible
SSO are explained. Then, we uncover the relationship between
identity-transformations in SSO and oblivious pseudo-random functions (OPRFs),
and present two variations of the properties required for SSO security as well
as the privacy requirements, to analyze existing OPRF protocols. Finally, new
identity transformations different from those designed in UppreSSO, are
constructed based on OPRFs, satisfying different variations of SSO security
requirements. To the best of our knowledge, this is the first time to uncover
the relationship between identity transformations in OIDC-compatible
privacy-preserving SSO services and OPRFs, and prove the SSO-related properties
(i.e., key-identifier freeness, RP designation and user identification) of OPRF
protocols, in addition to the basic properties of correctness, obliviousness
and pseudo-randomness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.11069v1">Regularized Federated Learning for Privacy-Preserving Dysarthric and
  Elderly Speech Recognition</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36">
  <p><b>Published on:</b> 2025-06-02T01:34:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tao Zhong, Mengzhe Geng, Shujie Hu, Guinan Li, Xunying Liu</p>
    <p><b>Summary:</b> Accurate recognition of dysarthric and elderly speech remains challenging to
date. While privacy concerns have driven a shift from centralized approaches to
federated learning (FL) to ensure data confidentiality, this further
exacerbates the challenges of data scarcity, imbalanced data distribution and
speaker heterogeneity. To this end, this paper conducts a systematic
investigation of regularized FL techniques for privacy-preserving dysarthric
and elderly speech recognition, addressing different levels of the FL process
by 1) parameter-based, 2) embedding-based and 3) novel loss-based
regularization. Experiments on the benchmark UASpeech dysarthric and
DementiaBank Pitt elderly speech corpora suggest that regularized FL systems
consistently outperform the baseline FedAvg system by statistically significant
WER reductions of up to 0.55\% absolute (2.13\% relative). Further increasing
communication frequency to one exchange per batch approaches centralized
training performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.02063v1">Privacy-Aware, Public-Aligned: Embedding Risk Detection and Public
  Values into Scalable Clinical Text De-Identification for Trusted Research
  Environments</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-01T17:45:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arlene Casey, Stuart Dunbar, Franz Gruber, Samuel McInerney, Matúš Falis, Pamela Linksted, Katie Wilde, Kathy Harrison, Alison Hamilton, Christian Cole</p>
    <p><b>Summary:</b> Clinical free-text data offers immense potential to improve population health
research such as richer phenotyping, symptom tracking, and contextual
understanding of patient care. However, these data present significant privacy
risks due to the presence of directly or indirectly identifying information
embedded in unstructured narratives. While numerous de-identification tools
have been developed, few have been tested on real-world, heterogeneous datasets
at scale or assessed for governance readiness. In this paper, we synthesise our
findings from previous studies examining the privacy-risk landscape across
multiple document types and NHS data providers in Scotland. We characterise how
direct and indirect identifiers vary by record type, clinical setting, and data
flow, and show how changes in documentation practice can degrade model
performance over time. Through public engagement, we explore societal
expectations around the safe use of clinical free text and reflect these in the
design of a prototype privacy-risk management tool to support transparent,
auditable decision-making. Our findings highlight that privacy risk is
context-dependent and cumulative, underscoring the need for adaptable, hybrid
de-identification approaches that combine rule-based precision with contextual
understanding. We offer a comprehensive view of the challenges and
opportunities for safe, scalable reuse of clinical free-text within Trusted
Research Environments and beyond, grounded in both technical evidence and
public perspectives on responsible data use.</p>
  </details>
</div>

