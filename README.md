
<h2>2024-08</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2408.00639v1">Privacy-preserving datasets by capturing feature distributions with
  Conditional VAEs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> 
  <p><b>Published on:</b> 2024-08-01T15:26:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Francesco Di Salvo, David Tafler, Sebastian Doerrich, Christian Ledig</p>
    <p><b>Summary:</b> Large and well-annotated datasets are essential for advancing deep learning
applications, however often costly or impossible to obtain by a single entity.
In many areas, including the medical domain, approaches relying on data sharing
have become critical to address those challenges. While effective in increasing
dataset size and diversity, data sharing raises significant privacy concerns.
Commonly employed anonymization methods based on the k-anonymity paradigm often
fail to preserve data diversity, affecting model robustness. This work
introduces a novel approach using Conditional Variational Autoencoders (CVAEs)
trained on feature vectors extracted from large pre-trained vision foundation
models. Foundation models effectively detect and represent complex patterns
across diverse domains, allowing the CVAE to faithfully capture the embedding
space of a given data distribution to generate (sample) a diverse,
privacy-respecting, and potentially unbounded set of synthetic feature vectors.
Our method notably outperforms traditional approaches in both medical and
natural image domains, exhibiting greater dataset diversity and higher
robustness against perturbations while preserving sample privacy. These results
underscore the potential of generative models to significantly impact deep
learning applications in data-scarce and privacy-sensitive environments. The
source code is available at
https://github.com/francescodisalvo05/cvae-anonymization .</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2408.00382v1">Long-Term Conversation Analysis: Privacy-Utility Trade-off under Noise
  and Reverberation</a></h3>
  
  <p><b>Published on:</b> 2024-08-01T08:43:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jule Pohlhausen, Francesco Nespoli, Joerg Bitzer</p>
    <p><b>Summary:</b> Recordings in everyday life require privacy preservation of the speech
content and speaker identity. This contribution explores the influence of noise
and reverberation on the trade-off between privacy and utility for low-cost
privacy-preserving methods feasible for edge computing. These methods
compromise spectral and temporal smoothing, speaker anonymization using the
McAdams coefficient, sampling with a very low sampling rate, and combinations.
Privacy is assessed by automatic speech and speaker recognition, while our
utility considers voice activity detection and speaker diarization. Overall,
our evaluation shows that additional noise degrades the performance of all
models more than reverberation. This degradation corresponds to enhanced speech
privacy, while utility is less deteriorated for some methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2408.00294v1">RDP: Ranked Differential Privacy for Facial Feature Protection in
  Multiscale Sparsified Subspace</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2024-08-01T05:41:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lu Ou, Shaolin Liao, Shihui Gao, Guandong Huang, Zheng Qi</p>
    <p><b>Summary:</b> With the widespread sharing of personal face images in applications' public
databases, face recognition systems faces real threat of being breached by
potential adversaries who are able to access users' face images and use them to
intrude the face recognition systems. In this paper, we propose a novel privacy
protection method in the multiscale sparsified feature subspaces to protect
sensitive facial features, by taking care of the influence or weight ranked
feature coefficients on the privacy budget, named "Ranked Differential Privacy
(RDP)". After the multiscale feature decomposition, the lightweight Laplacian
noise is added to the dimension-reduced sparsified feature coefficients
according to the geometric superposition method. Then, we rigorously prove that
the RDP satisfies Differential Privacy. After that, the nonlinear Lagrange
Multiplier (LM) method is formulated for the constraint optimization problem of
maximizing the utility of the visualization quality protected face images with
sanitizing noise, under a given facial features privacy budget. Then, two
methods are proposed to solve the nonlinear LM problem and obtain the optimal
noise scale parameters: 1) the analytical Normalization Approximation (NA)
method with identical average noise scale parameter for real-time online
applications; and 2) the LM optimization Gradient Descent (LMGD) numerical
method to obtain the nonlinear solution through iterative updating for more
accurate offline applications. Experimental results on two real-world datasets
show that our proposed RDP outperforms other state-of-the-art methods: at a
privacy budget of 0.2, the PSNR (Peak Signal-to-Noise Ratio) of the RDP is
about ~10 dB higher than (10 times as high as) the highest PSNR of all compared
methods.</p>
  </details>
</div>



<h2>2024-07</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.21691v1">Explainable Artificial Intelligence for Quantifying Interfering and
  High-Risk Behaviors in Autism Spectrum Disorder in a Real-World Classroom
  Environment Using Privacy-Preserving Video Analysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-07-31T15:37:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Barun Das, Conor Anderson, Tania Villavicencio, Johanna Lantz, Jenny Foster, Theresa Hamlin, Ali Bahrami Rad, Gari D. Clifford, Hyeokhyen Kwon</p>
    <p><b>Summary:</b> Rapid identification and accurate documentation of interfering and high-risk
behaviors in ASD, such as aggression, self-injury, disruption, and restricted
repetitive behaviors, are important in daily classroom environments for
tracking intervention effectiveness and allocating appropriate resources to
manage care needs. However, having a staff dedicated solely to observing is
costly and uncommon in most educational settings. Recently, multiple research
studies have explored developing automated, continuous, and objective tools
using machine learning models to quantify behaviors in ASD. However, the
majority of the work was conducted under a controlled environment and has not
been validated for real-world conditions. In this work, we demonstrate that the
latest advances in video-based group activity recognition techniques can
quantify behaviors in ASD in real-world activities in classroom environments
while preserving privacy. Our explainable model could detect the episode of
problem behaviors with a 77% F1-score and capture distinctive behavior features
in different types of behaviors in ASD. To the best of our knowledge, this is
the first work that shows the promise of objectively quantifying behaviors in
ASD in a real-world environment, which is an important step toward the
development of a practical tool that can ease the burden of data collection for
classroom staff.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.21624v1">Grid-Based Decompositions for Spatial Data under Local Differential
  Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-31T14:17:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Berkay Kemal Balioglu, Alireza Khodaie, Ameer Taweel, Mehmet Emre Gursoy</p>
    <p><b>Summary:</b> Local differential privacy (LDP) has recently emerged as a popular privacy
standard. With the growing popularity of LDP, several recent works have applied
LDP to spatial data, and grid-based decompositions have been a common building
block in the collection and analysis of spatial data under DP and LDP. In this
paper, we study three grid-based decomposition methods for spatial data under
LDP: Uniform Grid (UG), PrivAG, and AAG. UG is a static approach that consists
of equal-sized cells. To enable data-dependent decomposition, PrivAG was
proposed by Yang et al. as the most recent adaptive grid method. To advance the
state-of-the-art in adaptive grids, in this paper we propose the Advanced
Adaptive Grid (AAG) method. For each grid cell, following the intuition that
the cell's intra-cell density distribution will be affected by its neighbors,
AAG performs uneven cell divisions depending on the neighboring cells'
densities. We experimentally compare UG, PrivAG, and AAG using three real-world
location datasets, varying privacy budgets, and query sizes. Results show that
AAG provides higher utility than PrivAG, demonstrating the superiority of our
proposed approach. Furthermore, UG's performance is heavily dependent on the
choice of grid size. When the grid size is chosen optimally in UG, AAG still
beats UG for small queries, but UG beats AAG for large (coarse-grained)
queries.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.21141v1">FL-DECO-BC: A Privacy-Preserving, Provably Secure, and
  Provenance-Preserving Federated Learning Framework with Decentralized Oracles
  on Blockchain for VANETs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-30T19:09:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sathwik Narkedimilli, Rayachoti Arun Kumar, N. V. Saran Kumar, Ramapathruni Praneeth Reddy, Pavan Kumar C</p>
    <p><b>Summary:</b> Vehicular Ad-Hoc Networks (VANETs) hold immense potential for improving
traffic safety and efficiency. However, traditional centralized approaches for
machine learning in VANETs raise concerns about data privacy and security.
Federated Learning (FL) offers a solution that enables collaborative model
training without sharing raw data. This paper proposes FL-DECO-BC as a novel
privacy-preserving, provably secure, and provenance-preserving federated
learning framework specifically designed for VANETs. FL-DECO-BC leverages
decentralized oracles on blockchain to securely access external data sources
while ensuring data privacy through advanced techniques. The framework
guarantees provable security through cryptographic primitives and formal
verification methods. Furthermore, FL-DECO-BC incorporates a
provenance-preserving design to track data origin and history, fostering trust
and accountability. This combination of features empowers VANETs with secure
and privacy-conscious machine-learning capabilities, paving the way for
advanced traffic management and safety applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.20830v1">Federated Knowledge Recycling: Privacy-Preserving Synthetic Data Sharing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-07-30T13:56:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Eugenio Lomurno, Matteo Matteucci</p>
    <p><b>Summary:</b> Federated learning has emerged as a paradigm for collaborative learning,
enabling the development of robust models without the need to centralise
sensitive data. However, conventional federated learning techniques have
privacy and security vulnerabilities due to the exposure of models, parameters
or updates, which can be exploited as an attack surface. This paper presents
Federated Knowledge Recycling (FedKR), a cross-silo federated learning approach
that uses locally generated synthetic data to facilitate collaboration between
institutions. FedKR combines advanced data generation techniques with a dynamic
aggregation process to provide greater security against privacy attacks than
existing methods, significantly reducing the attack surface. Experimental
results on generic and medical datasets show that FedKR achieves competitive
performance, with an average improvement in accuracy of 4.24% compared to
training models from local data, demonstrating particular effectiveness in data
scarcity scenarios.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.20640v1">Improved Bounds for Pure Private Agnostic Learning: Item-Level and
  User-Level Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-07-30T08:35:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bo Li, Wei Wang, Peng Ye</p>
    <p><b>Summary:</b> Machine Learning has made remarkable progress in a wide range of fields. In
many scenarios, learning is performed on datasets involving sensitive
information, in which privacy protection is essential for learning algorithms.
In this work, we study pure private learning in the agnostic model -- a
framework reflecting the learning process in practice. We examine the number of
users required under item-level (where each user contributes one example) and
user-level (where each user contributes multiple examples) privacy and derive
several improved upper bounds. For item-level privacy, our algorithm achieves a
near optimal bound for general concept classes. We extend this to the
user-level setting, rendering a tighter upper bound than the one proved by
Ghazi et al. (2023). Lastly, we consider the problem of learning thresholds
under user-level privacy and present an algorithm with a nearly tight user
complexity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.19828v1">Federated Learning based Latent Factorization of Tensors for
  Privacy-Preserving QoS Prediction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-29T09:30:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuai Zhong, Zengtong Tang, Di Wu</p>
    <p><b>Summary:</b> In applications related to big data and service computing, dynamic
connections tend to be encountered, especially the dynamic data of
user-perspective quality of service (QoS) in Web services. They are transformed
into high-dimensional and incomplete (HDI) tensors which include abundant
temporal pattern information. Latent factorization of tensors (LFT) is an
extremely efficient and typical approach for extracting such patterns from an
HDI tensor. However, current LFT models require the QoS data to be maintained
in a central place (e.g., a central server), which is impossible for
increasingly privacy-sensitive users. To address this problem, this article
creatively designs a federated learning based on latent factorization of
tensors (FL-LFT). It builds a data-density -oriented federated learning model
to enable isolated users to collaboratively train a global LFT model while
protecting user's privacy. Extensive experiments on a QoS dataset collected
from the real world verify that FL-LFT shows a remarkable increase in
prediction accuracy when compared to state-of-the-art federated learning (FL)
approaches.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.19703v1">Efficient Byzantine-Robust and Provably Privacy-Preserving Federated
  Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-29T04:55:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chenfei Nie, Qiang Li, Yuxin Yang, Yuede Ji, Binghui Wang</p>
    <p><b>Summary:</b> Federated learning (FL) is an emerging distributed learning paradigm without
sharing participating clients' private data. However, existing works show that
FL is vulnerable to both Byzantine (security) attacks and data reconstruction
(privacy) attacks. Almost all the existing FL defenses only address one of the
two attacks. A few defenses address the two attacks, but they are not efficient
and effective enough. We propose BPFL, an efficient Byzantine-robust and
provably privacy-preserving FL method that addresses all the issues.
Specifically, we draw on state-of-the-art Byzantine-robust FL methods and use
similarity metrics to measure the robustness of each participating client in
FL. The validity of clients are formulated as circuit constraints on similarity
metrics and verified via a zero-knowledge proof. Moreover, the client models
are masked by a shared random vector, which is generated based on homomorphic
encryption. In doing so, the server receives the masked client models rather
than the true ones, which are proven to be private. BPFL is also efficient due
to the usage of non-interactive zero-knowledge proof. Experimental results on
various datasets show that our BPFL is efficient, Byzantine-robust, and
privacy-preserving.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.19677v1">Navigating the United States Legislative Landscape on Voice Privacy:
  Existing Laws, Proposed Bills, Protection for Children, and Synthetic Data
  for AI</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36">  
  <p><b>Published on:</b> 2024-07-29T03:43:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Satwik Dutta, John H. L. Hansen</p>
    <p><b>Summary:</b> Privacy is a hot topic for policymakers across the globe, including the
United States. Evolving advances in AI and emerging concerns about the misuse
of personal data have pushed policymakers to draft legislation on trustworthy
AI and privacy protection for its citizens. This paper presents the state of
the privacy legislation at the U.S. Congress and outlines how voice data is
considered as part of the legislation definition. This paper also reviews
additional privacy protection for children. This paper presents a holistic
review of enacted and proposed privacy laws, and consideration for voice data,
including guidelines for processing children's data, in those laws across the
fifty U.S. states. As a groundbreaking alternative to actual human data,
ethically generated synthetic data allows much flexibility to keep AI
innovation in progress. Given the consideration of synthetic data in AI
legislation by policymakers to be relatively new, as compared to that of
privacy laws, this paper reviews regulatory considerations for synthetic data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.19401v1">Complete Security and Privacy for AI Inference in Decentralized Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-07-28T05:09:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hongyang Zhang, Yue Zhao, Claudio Angione, Harry Yang, James Buban, Ahmad Farhan, Fielding Johnston, Patrick Colangelo</p>
    <p><b>Summary:</b> The need for data security and model integrity has been accentuated by the
rapid adoption of AI and ML in data-driven domains including healthcare,
finance, and security. Large models are crucial for tasks like diagnosing
diseases and forecasting finances but tend to be delicate and not very
scalable. Decentralized systems solve this issue by distributing the workload
and reducing central points of failure. Yet, data and processes spread across
different nodes can be at risk of unauthorized access, especially when they
involve sensitive information. Nesa solves these challenges with a
comprehensive framework using multiple techniques to protect data and model
outputs. This includes zero-knowledge proofs for secure model verification. The
framework also introduces consensus-based verification checks for consistent
outputs across nodes and confirms model integrity. Split Learning divides
models into segments processed by different nodes for data privacy by
preventing full data access at any single point. For hardware-based security,
trusted execution environments are used to protect data and computations within
secure zones. Nesa's state-of-the-art proofs and principles demonstrate the
framework's effectiveness, making it a promising approach for securely
democratizing artificial intelligence.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.19364v1">Defogger: A Visual Analysis Approach for Data Exploration of Sensitive
  Data Protected by Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-28T02:14:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xumeng Wang, Shuangcheng Jiao, Chris Bryan</p>
    <p><b>Summary:</b> Differential privacy ensures the security of individual privacy but poses
challenges to data exploration processes because the limited privacy budget
incapacitates the flexibility of exploration and the noisy feedback of data
requests leads to confusing uncertainty. In this study, we take the lead in
describing corresponding exploration scenarios, including underlying
requirements and available exploration strategies. To facilitate practical
applications, we propose a visual analysis approach to the formulation of
exploration strategies. Our approach applies a reinforcement learning model to
provide diverse suggestions for exploration strategies according to the
exploration intent of users. A novel visual design for representing uncertainty
in correlation patterns is integrated into our prototype system to support the
proposed approach. Finally, we implemented a user study and two case studies.
The results of these studies verified that our approach can help develop
strategies that satisfy the exploration intent of users.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.19354v1">The Emerged Security and Privacy of LLM Agent: A Survey with Case
  Studies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-28T00:26:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Feng He, Tianqing Zhu, Dayong Ye, Bo Liu, Wanlei Zhou, Philip S. Yu</p>
    <p><b>Summary:</b> Inspired by the rapid development of Large Language Models (LLMs), LLM agents
have evolved to perform complex tasks. LLM agents are now extensively applied
across various domains, handling vast amounts of data to interact with humans
and execute tasks. The widespread applications of LLM agents demonstrate their
significant commercial value; however, they also expose security and privacy
vulnerabilities. At the current stage, comprehensive research on the security
and privacy of LLM agents is highly needed. This survey aims to provide a
comprehensive overview of the newly emerged privacy and security issues faced
by LLM agents. We begin by introducing the fundamental knowledge of LLM agents,
followed by a categorization and analysis of the threats. We then discuss the
impacts of these threats on humans, environment, and other agents.
Subsequently, we review existing defensive strategies, and finally explore
future trends. Additionally, the survey incorporates diverse case studies to
facilitate a more accessible understanding. By highlighting these critical
security and privacy issues, the survey seeks to stimulate future research
towards enhancing the security and privacy of LLM agents, thereby increasing
their reliability and trustworthiness in future applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.19147v1">Reexamination of the realtime protection for user privacy in practical
  quantum private query</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-27T02:19:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chun-Yan Wei, Xiao-Qiu Cai, Tian-Yin Wang</p>
    <p><b>Summary:</b> Quantum private query (QPQ) is the quantum version for symmetrically private
retrieval. However, the user privacy in QPQ is generally guarded in the
non-realtime and cheat sensitive way. That is, the dishonest database holder's
cheating to elicit user privacy can only be discovered after the protocol is
finished (when the user finds some errors in the retrieved database item). Such
delayed detection may cause very unpleasant results for the user in real-life
applications. Current efforts to protect user privacy in realtime in existing
QPQ protocols mainly use two techniques, i.e., adding an honesty checking on
the database or allowing the user to reorder the qubits. We reexamine these two
kinds of QPQ protocols and find neither of them can work well. We give concrete
cheating strategies for both participants and show that honesty checking of
inner participant should be dealt more carefully in for example the choosing of
checking qubits. We hope such discussion can supply new concerns when detection
of dishonest participant is considered in quantum multi-party secure
computations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.19119v1">Accuracy-Privacy Trade-off in the Mitigation of Membership Inference
  Attack in Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-26T22:44:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sayyed Farid Ahamed, Soumya Banerjee, Sandip Roy, Devin Quinn, Marc Vucovich, Kevin Choi, Abdul Rahman, Alison Hu, Edward Bowen, Sachin Shetty</p>
    <p><b>Summary:</b> Over the last few years, federated learning (FL) has emerged as a prominent
method in machine learning, emphasizing privacy preservation by allowing
multiple clients to collaboratively build a model while keeping their training
data private. Despite this focus on privacy, FL models are susceptible to
various attacks, including membership inference attacks (MIAs), posing a
serious threat to data confidentiality. In a recent study, Rezaei \textit{et
al.} revealed the existence of an accuracy-privacy trade-off in deep ensembles
and proposed a few fusion strategies to overcome it. In this paper, we aim to
explore the relationship between deep ensembles and FL. Specifically, we
investigate whether confidence-based metrics derived from deep ensembles apply
to FL and whether there is a trade-off between accuracy and privacy in FL with
respect to MIA. Empirical investigations illustrate a lack of a non-monotonic
correlation between the number of clients and the accuracy-privacy trade-off.
By experimenting with different numbers of federated clients, datasets, and
confidence-metric-based fusion strategies, we identify and analytically justify
the clear existence of the accuracy-privacy trade-off.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.18789v1">Granularity is crucial when applying differential privacy to text: An
  investigation for neural machine translation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-07-26T14:52:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Doan Nam Long Vu, Timour Igamberdiev, Ivan Habernal</p>
    <p><b>Summary:</b> Applying differential privacy (DP) by means of the DP-SGD algorithm to
protect individual data points during training is becoming increasingly popular
in NLP. However, the choice of granularity at which DP is applied is often
neglected. For example, neural machine translation (NMT) typically operates on
the sentence-level granularity. From the perspective of DP, this setup assumes
that each sentence belongs to a single person and any two sentences in the
training dataset are independent. This assumption is however violated in many
real-world NMT datasets, e.g. those including dialogues. For proper application
of DP we thus must shift from sentences to entire documents. In this paper, we
investigate NMT at both the sentence and document levels, analyzing the
privacy/utility trade-off for both scenarios, and evaluating the risks of not
using the appropriate privacy granularity in terms of leaking personally
identifiable information (PII). Our findings indicate that the document-level
NMT system is more resistant to membership inference attacks, emphasizing the
significance of using the appropriate granularity when working with DP.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.18564v1">Unveiling Privacy Vulnerabilities: Investigating the Role of Structure
  in Graph Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B">
  <p><b>Published on:</b> 2024-07-26T07:40:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hanyang Yuan, Jiarong Xu, Cong Wang, Ziqi Yang, Chunping Wang, Keting Yin, Yang Yang</p>
    <p><b>Summary:</b> The public sharing of user information opens the door for adversaries to
infer private data, leading to privacy breaches and facilitating malicious
activities. While numerous studies have concentrated on privacy leakage via
public user attributes, the threats associated with the exposure of user
relationships, particularly through network structure, are often neglected.
This study aims to fill this critical gap by advancing the understanding and
protection against privacy risks emanating from network structure, moving
beyond direct connections with neighbors to include the broader implications of
indirect network structural patterns. To achieve this, we first investigate the
problem of Graph Privacy Leakage via Structure (GPS), and introduce a novel
measure, the Generalized Homophily Ratio, to quantify the various mechanisms
contributing to privacy breach risks in GPS. Based on this insight, we develop
a novel graph private attribute inference attack, which acts as a pivotal tool
for evaluating the potential for privacy leakage through network structures
under worst-case scenarios. To protect users' private data from such
vulnerabilities, we propose a graph data publishing method incorporating a
learnable graph sampling technique, effectively transforming the original graph
into a privacy-preserving version. Extensive experiments demonstrate that our
attack model poses a significant threat to user privacy, and our graph data
publishing method successfully achieves the optimal privacy-utility trade-off
compared to baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.18503v1">Homomorphic Encryption-Enabled Federated Learning for Privacy-Preserving
  Intrusion Detection in Resource-Constrained IoV Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-26T04:19:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bui Duc Manh, Chi-Hieu Nguyen, Dinh Thai Hoang, Diep N. Nguyen</p>
    <p><b>Summary:</b> This paper aims to propose a novel framework to address the data privacy
issue for Federated Learning (FL)-based Intrusion Detection Systems (IDSs) in
Internet-of-Vehicles(IoVs) with limited computational resources. In particular,
in conventional FL systems, it is usually assumed that the computing nodes have
sufficient computational resources to process the training tasks. However, in
practical IoV systems, vehicles usually have limited computational resources to
process intensive training tasks, compromising the effectiveness of deploying
FL in IDSs. While offloading data from vehicles to the cloud can mitigate this
issue, it introduces significant privacy concerns for vehicle users (VUs). To
resolve this issue, we first propose a highly-effective framework using
homomorphic encryption to secure data that requires offloading to a centralized
server for processing. Furthermore, we develop an effective training algorithm
tailored to handle the challenges of FL-based systems with encrypted data. This
algorithm allows the centralized server to directly compute on quantum-secure
encrypted ciphertexts without needing decryption. This approach not only
safeguards data privacy during the offloading process from VUs to the
centralized server but also enhances the efficiency of utilizing FL for IDSs in
IoV systems. Our simulation results show that our proposed approach can achieve
a performance that is as close to that of the solution without encryption, with
a gap of less than 0.8%.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.18433v1">Investigating the Privacy Risk of Using Robot Vacuum Cleaners in Smart
  Environments</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-07-26T00:00:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Benjamin Ulsmaag, Jia-Chun Lin, Ming-Chang Lee</p>
    <p><b>Summary:</b> Robot vacuum cleaners have become increasingly popular and are widely used in
various smart environments. To improve user convenience, manufacturers also
introduced smartphone applications that enable users to customize cleaning
settings or access information about their robot vacuum cleaners. While this
integration enhances the interaction between users and their robot vacuum
cleaners, it results in potential privacy concerns because users' personal
information may be exposed. To address these concerns, end-to-end encryption is
implemented between the application, cloud service, and robot vacuum cleaners
to secure the exchanged information. Nevertheless, network header metadata
remains unencrypted and it is still vulnerable to network eavesdropping. In
this paper, we investigate the potential risk of private information exposure
through such metadata. A popular robot vacuum cleaner was deployed in a real
smart environment where passive network eavesdropping was conducted during
several selected cleaning events. Our extensive analysis, based on Association
Rule Learning, demonstrates that it is feasible to identify certain events
using only the captured Internet traffic metadata, thereby potentially exposing
private user information and raising privacy concerns.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.18353v1">Privacy-Preserving Model-Distributed Inference at the Edge</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-07-25T19:39:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fatemeh Jafarian Dehkordi, Yasaman Keshtkarjahromi, Hulya Seferoglu</p>
    <p><b>Summary:</b> This paper focuses on designing a privacy-preserving Machine Learning (ML)
inference protocol for a hierarchical setup, where clients own/generate data,
model owners (cloud servers) have a pre-trained ML model, and edge servers
perform ML inference on clients' data using the cloud server's ML model. Our
goal is to speed up ML inference while providing privacy to both data and the
ML model. Our approach (i) uses model-distributed inference (model
parallelization) at the edge servers and (ii) reduces the amount of
communication to/from the cloud server. Our privacy-preserving hierarchical
model-distributed inference, privateMDI design uses additive secret sharing and
linearly homomorphic encryption to handle linear calculations in the ML
inference, and garbled circuit and a novel three-party oblivious transfer are
used to handle non-linear functions. privateMDI consists of offline and online
phases. We designed these phases in a way that most of the data exchange is
done in the offline phase while the communication overhead of the online phase
is reduced. In particular, there is no communication to/from the cloud server
in the online phase, and the amount of communication between the client and
edge servers is minimized. The experimental results demonstrate that privateMDI
significantly reduces the ML inference time as compared to the baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.18157v1">Enhanced Privacy Bound for Shuffle Model with Personalized Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2024-07-25T16:11:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yixuan Liu, Yuhan Liu, Li Xiong, Yujie Gu, Hong Chen</p>
    <p><b>Summary:</b> The shuffle model of Differential Privacy (DP) is an enhanced privacy
protocol which introduces an intermediate trusted server between local users
and a central data curator. It significantly amplifies the central DP guarantee
by anonymizing and shuffling the local randomized data. Yet, deriving a tight
privacy bound is challenging due to its complicated randomization protocol.
While most existing work are focused on unified local privacy settings, this
work focuses on deriving the central privacy bound for a more practical setting
where personalized local privacy is required by each user. To bound the privacy
after shuffling, we first need to capture the probability of each user
generating clones of the neighboring data points. Second, we need to quantify
the indistinguishability between two distributions of the number of clones on
neighboring datasets. Existing works either inaccurately capture the
probability, or underestimate the indistinguishability between neighboring
datasets. Motivated by this, we develop a more precise analysis, which yields a
general and tighter bound for arbitrary DP mechanisms. Firstly, we derive the
clone-generating probability by hypothesis testing %from a randomizer-specific
perspective, which leads to a more accurate characterization of the
probability. Secondly, we analyze the indistinguishability in the context of
$f$-DP, where the convexity of the distributions is leveraged to achieve a
tighter privacy bound. Theoretical and numerical results demonstrate that our
bound remarkably outperforms the existing results in the literature.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.18096v1">Privacy Threats and Countermeasures in Federated Learning for Internet
  of Things: A Systematic Review</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-07-25T15:01:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Adel ElZemity, Budi Arief</p>
    <p><b>Summary:</b> Federated Learning (FL) in the Internet of Things (IoT) environments can
enhance machine learning by utilising decentralised data, but at the same time,
it might introduce significant privacy and security concerns due to the
constrained nature of IoT devices. This represents a research challenge that we
aim to address in this paper. We systematically analysed recent literature to
identify privacy threats in FL within IoT environments, and evaluate the
defensive measures that can be employed to mitigate these threats. Using a
Systematic Literature Review (SLR) approach, we searched five publication
databases (Scopus, IEEE Xplore, Wiley, ACM, and Science Direct), collating
relevant papers published between 2017 and April 2024, a period which spans
from the introduction of FL until now. Guided by the PRISMA protocol, we
selected 49 papers to focus our systematic review on. We analysed these papers,
paying special attention to the privacy threats and defensive measures --
specifically within the context of IoT -- using inclusion and exclusion
criteria tailored to highlight recent advances and critical insights. We
identified various privacy threats, including inference attacks, poisoning
attacks, and eavesdropping, along with defensive measures such as Differential
Privacy and Secure Multi-Party Computation. These defences were evaluated for
their effectiveness in protecting privacy without compromising the functional
integrity of FL in IoT settings. Our review underscores the necessity for
robust and efficient privacy-preserving strategies tailored for IoT
environments. Notably, there is a need for strategies against replay, evasion,
and model stealing attacks. Exploring lightweight defensive measures and
emerging technologies such as blockchain may help improve the privacy of FL in
IoT, leading to the creation of FL models that can operate under variable
network conditions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.17663v1">Explaining the Model, Protecting Your Data: Revealing and Mitigating the
  Data Privacy Risks of Post-Hoc Model Explanations via Membership Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-07-24T22:16:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Catherine Huang, Martin Pawelczyk, Himabindu Lakkaraju</p>
    <p><b>Summary:</b> Predictive machine learning models are becoming increasingly deployed in
high-stakes contexts involving sensitive personal data; in these contexts,
there is a trade-off between model explainability and data privacy. In this
work, we push the boundaries of this trade-off: with a focus on foundation
models for image classification fine-tuning, we reveal unforeseen privacy risks
of post-hoc model explanations and subsequently offer mitigation strategies for
such risks. First, we construct VAR-LRT and L1/L2-LRT, two new membership
inference attacks based on feature attribution explanations that are
significantly more successful than existing explanation-leveraging attacks,
particularly in the low false-positive rate regime that allows an adversary to
identify specific training set members with confidence. Second, we find
empirically that optimized differentially private fine-tuning substantially
diminishes the success of the aforementioned attacks, while maintaining high
model accuracy. We carry out a systematic empirical investigation of our 2 new
attacks with 5 vision transformer architectures, 5 benchmark datasets, 4
state-of-the-art post-hoc explanation methods, and 4 privacy strength settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.18982v1">Low-Latency Privacy-Preserving Deep Learning Design via Secure MPC</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-07-24T07:01:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ke Lin, Yasir Glani, Ping Luo</p>
    <p><b>Summary:</b> Secure multi-party computation (MPC) facilitates privacy-preserving
computation between multiple parties without leaking private information. While
most secure deep learning techniques utilize MPC operations to achieve feasible
privacy-preserving machine learning on downstream tasks, the overhead of the
computation and communication still hampers their practical application. This
work proposes a low-latency secret-sharing-based MPC design that reduces
unnecessary communication rounds during the execution of MPC protocols. We also
present a method for improving the computation of commonly used nonlinear
functions in deep learning by integrating multivariate multiplication and
coalescing different packets into one to maximize network utilization. Our
experimental results indicate that our method is effective in a variety of
settings, with a speedup in communication latency of $10\sim20\%$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.17021v1">The EU-US Data Privacy Framework: Is the Dragon Eating its Own Tail?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-07-24T06:00:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marcelo Corrales Compagnucci</p>
    <p><b>Summary:</b> The European Commission adequacy decision on the EU US Data Privacy
Framework, adopted on July 10th, 2023, marks a crucial moment in transatlantic
data protection. Following an Executive Order issued by President Biden in
October 2022, this decision confirms that the United States meets European
Union standards for personal data protection. The decision extends to all
transfers from the European Economic Area to US entities participating in the
framework, promoting privacy rights while facilitating data exchange. Key
aspects include oversight of US public authorities access to transferred data,
the introduction of a dual tier redress mechanism, and granting new rights to
EU individuals, encompassing data access and rectification. However, the
framework presents both promise and challenges in health data transfers. While
streamlining exchange and aligning legal standards, it grapples with the
complexities of divergent privacy laws. The recent bill for the introduction of
a US federal privacy law emphasizes the urgent need for ongoing reform.
Lingering concerns persist regarding the framework resilience, especially amid
potential legal battles before the Court of Justice of the EU. The history of
transatlantic data transfers between the EU and the US is riddled with
vulnerabilities, reminiscent of the Ouroboros, an ancient symbol of a serpent
or dragon eating its own tail, hinting at the looming possibility of the
framework facing invalidation once again. This article delves into the main
requirements of the framework and offers insights on how healthcare
organizations can navigate it effectively.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.16929v2">Synthetic Data, Similarity-based Privacy Metrics, and Regulatory
  (Non-)Compliance</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-07-24T01:45:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Georgi Ganev</p>
    <p><b>Summary:</b> In this paper, we argue that similarity-based privacy metrics cannot ensure
regulatory compliance of synthetic data. Our analysis and counter-examples show
that they do not protect against singling out and linkability and, among other
fundamental issues, completely ignore the motivated intruder test.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.16735v1">Theoretical Analysis of Privacy Leakage in Trustworthy Federated
  Learning: A Perspective from Linear Algebra and Optimization Theory</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2024-07-23T16:23:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaojin Zhang, Wei Chen</p>
    <p><b>Summary:</b> Federated learning has emerged as a promising paradigm for collaborative
model training while preserving data privacy. However, recent studies have
shown that it is vulnerable to various privacy attacks, such as data
reconstruction attacks. In this paper, we provide a theoretical analysis of
privacy leakage in federated learning from two perspectives: linear algebra and
optimization theory. From the linear algebra perspective, we prove that when
the Jacobian matrix of the batch data is not full rank, there exist different
batches of data that produce the same model update, thereby ensuring a level of
privacy. We derive a sufficient condition on the batch size to prevent data
reconstruction attacks. From the optimization theory perspective, we establish
an upper bound on the privacy leakage in terms of the batch size, the
distortion extent, and several other factors. Our analysis provides insights
into the relationship between privacy leakage and various aspects of federated
learning, offering a theoretical foundation for designing privacy-preserving
federated learning algorithms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.16729v1">PateGail: A Privacy-Preserving Mobility Trajectory Generator with
  Imitation Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-07-23T14:59:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Huandong Wang, Changzheng Gao, Yuchen Wu, Depeng Jin, Lina Yao, Yong Li</p>
    <p><b>Summary:</b> Generating human mobility trajectories is of great importance to solve the
lack of large-scale trajectory data in numerous applications, which is caused
by privacy concerns. However, existing mobility trajectory generation methods
still require real-world human trajectories centrally collected as the training
data, where there exists an inescapable risk of privacy leakage. To overcome
this limitation, in this paper, we propose PateGail, a privacy-preserving
imitation learning model to generate mobility trajectories, which utilizes the
powerful generative adversary imitation learning model to simulate the
decision-making process of humans. Further, in order to protect user privacy,
we train this model collectively based on decentralized mobility data stored in
user devices, where personal discriminators are trained locally to distinguish
and reward the real and generated human trajectories. In the training process,
only the generated trajectories and their rewards obtained based on personal
discriminators are shared between the server and devices, whose privacy is
further preserved by our proposed perturbation mechanisms with theoretical
proof to satisfy differential privacy. Further, to better model the human
decision-making process, we propose a novel aggregation mechanism of the
rewards obtained from personal discriminators. We theoretically prove that
under the reward obtained based on the aggregation mechanism, our proposed
model maximizes the lower bound of the discounted total rewards of users.
Extensive experiments show that the trajectories generated by our model are
able to resemble real-world trajectories in terms of five key statistical
metrics, outperforming state-of-the-art algorithms by over 48.03%. Furthermore,
we demonstrate that the synthetic trajectories are able to efficiently support
practical applications, including mobility prediction and location
recommendation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.16166v1">Robust Privacy Amidst Innovation with Large Language Models Through a
  Critical Assessment of the Risks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-07-23T04:20:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yao-Shun Chuang, Atiquer Rahman Sarkar, Noman Mohammed, Xiaoqian Jiang</p>
    <p><b>Summary:</b> This study examines integrating EHRs and NLP with large language models
(LLMs) to improve healthcare data management and patient care. It focuses on
using advanced models to create secure, HIPAA-compliant synthetic patient notes
for biomedical research. The study used de-identified and re-identified MIMIC
III datasets with GPT-3.5, GPT-4, and Mistral 7B to generate synthetic notes.
Text generation employed templates and keyword extraction for contextually
relevant notes, with one-shot generation for comparison. Privacy assessment
checked PHI occurrence, while text utility was tested using an ICD-9 coding
task. Text quality was evaluated with ROUGE and cosine similarity metrics to
measure semantic similarity with source notes. Analysis of PHI occurrence and
text utility via the ICD-9 coding task showed that the keyword-based method had
low risk and good performance. One-shot generation showed the highest PHI
exposure and PHI co-occurrence, especially in geographic location and date
categories. The Normalized One-shot method achieved the highest classification
accuracy. Privacy analysis revealed a critical balance between data utility and
privacy protection, influencing future data use and sharing. Re-identified data
consistently outperformed de-identified data. This study demonstrates the
effectiveness of keyword-based methods in generating privacy-protecting
synthetic clinical notes that retain data usability, potentially transforming
clinical data-sharing practices. The superior performance of re-identified over
de-identified data suggests a shift towards methods that enhance utility and
privacy by using dummy PHIs to perplex privacy attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.16164v1">Representation Magnitude has a Liability to Privacy Vulnerability</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-07-23T04:13:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xingli Fang, Jung-Eun Kim</p>
    <p><b>Summary:</b> The privacy-preserving approaches to machine learning (ML) models have made
substantial progress in recent years. However, it is still opaque in which
circumstances and conditions the model becomes privacy-vulnerable, leading to a
challenge for ML models to maintain both performance and privacy. In this
paper, we first explore the disparity between member and non-member data in the
representation of models under common training frameworks. We identify how the
representation magnitude disparity correlates with privacy vulnerability and
address how this correlation impacts privacy vulnerability. Based on the
observations, we propose Saturn Ring Classifier Module (SRCM), a plug-in
model-level solution to mitigate membership privacy leakage. Through a confined
yet effective representation space, our approach ameliorates models' privacy
vulnerability while maintaining generalizability. The code of this work can be
found here: \url{https://github.com/JEKimLab/AIES2024_SRCM}</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.15957v1">Escalation of Commitment: A Case Study of the United States Census
  Bureau Efforts to Implement Differential Privacy for the 2020 Decennial
  Census</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2024-07-22T18:13:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Krish Muralidhar, Steven Ruggles</p>
    <p><b>Summary:</b> In 2017, the United States Census Bureau announced that because of high
disclosure risk in the methodology (data swapping) used to produce tabular data
for the 2010 census, a different protection mechanism based on differential
privacy would be used for the 2020 census. While there have been many studies
evaluating the result of this change, there has been no rigorous examination of
disclosure risk claims resulting from the released 2010 tabular data. In this
study we perform such an evaluation. We show that the procedures used to
evaluate disclosure risk are unreliable and resulted in inflated disclosure
risk. Demonstration data products released using the new procedure were also
shown to have poor utility. However, since the Census Bureau had already
committed to a different procedure, they had no option except to escalate their
commitment. The result of such escalation is that the 2020 tabular data release
offers neither privacy nor accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.15407v1">A Solution toward Transparent and Practical AI Regulation: Privacy
  Nutrition Labels for Open-source Generative AI-based Applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2024-07-22T06:24:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Meixue Si, Shidong Pan, Dianshu Liao, Xiaoyu Sun, Zhen Tao, Wenchang Shi, Zhenchang Xing</p>
    <p><b>Summary:</b> The rapid development and widespread adoption of Generative Artificial
Intelligence-based (GAI) applications have greatly enriched our daily lives,
benefiting people by enhancing creativity, personalizing experiences, improving
accessibility, and fostering innovation and efficiency across various domains.
However, along with the development of GAI applications, concerns have been
raised about transparency in their privacy practices. Traditional privacy
policies often fail to effectively communicate essential privacy information
due to their complexity and length, and open-source community developers often
neglect privacy practices even more. Only 12.2% of examined open-source GAI
apps provide a privacy policy. To address this, we propose a regulation-driven
GAI Privacy Label and introduce Repo2Label, a novel framework for automatically
generating these labels based on code repositories. Our user study indicates a
common endorsement of the proposed GAI privacy label format. Additionally,
Repo2Label achieves a precision of 0.81, recall of 0.88, and F1-score of 0.84
based on the benchmark dataset, significantly outperforming the developer
self-declared privacy notices. We also discuss the common regulatory
(in)compliance of open-source GAI apps, comparison with other privacy notices,
and broader impacts to different stakeholders. Our findings suggest that
Repo2Label could serve as a significant tool for bolstering the privacy
transparency of GAI apps and make them more practical and responsible.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.15224v1">PUFFLE: Balancing Privacy, Utility, and Fairness in Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-07-21T17:22:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Luca Corbucci, Mikko A Heikkila, David Solans Noguero, Anna Monreale, Nicolas Kourtellis</p>
    <p><b>Summary:</b> Training and deploying Machine Learning models that simultaneously adhere to
principles of fairness and privacy while ensuring good utility poses a
significant challenge. The interplay between these three factors of
trustworthiness is frequently underestimated and remains insufficiently
explored. Consequently, many efforts focus on ensuring only two of these
factors, neglecting one in the process. The decentralization of the datasets
and the variations in distributions among the clients exacerbate the complexity
of achieving this ethical trade-off in the context of Federated Learning (FL).
For the first time in FL literature, we address these three factors of
trustworthiness. We introduce PUFFLE, a high-level parameterised approach that
can help in the exploration of the balance between utility, privacy, and
fairness in FL scenarios. We prove that PUFFLE can be effective across diverse
datasets, models, and data distributions, reducing the model unfairness up to
75%, with a maximum reduction in the utility of 17% in the worst-case scenario,
while maintaining strict privacy guarantees during the FL training.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.15220v1">Privacy-Preserving Multi-Center Differential Protein Abundance Analysis
  with FedProt</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-07-21T17:09:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuliya Burankova, Miriam Abele, Mohammad Bakhtiari, Christine von Törne, Teresa Barth, Lisa Schweizer, Pieter Giesbertz, Johannes R. Schmidt, Stefan Kalkhof, Janina Müller-Deile, Peter A van Veelen, Yassene Mohammed, Elke Hammer, Lis Arend, Klaudia Adamowicz, Tanja Laske, Anne Hartebrodt, Tobias Frisch, Chen Meng, Julian Matschinske, Julian Späth, Richard Röttger, Veit Schwämmle, Stefanie M. Hauck, Stefan Lichtenthaler, Axel Imhof, Matthias Mann, Christina Ludwig, Bernhard Kuster, Jan Baumbach, Olga Zolotareva</p>
    <p><b>Summary:</b> Quantitative mass spectrometry has revolutionized proteomics by enabling
simultaneous quantification of thousands of proteins. Pooling patient-derived
data from multiple institutions enhances statistical power but raises
significant privacy concerns. Here we introduce FedProt, the first
privacy-preserving tool for collaborative differential protein abundance
analysis of distributed data, which utilizes federated learning and additive
secret sharing. In the absence of a multicenter patient-derived dataset for
evaluation, we created two, one at five centers from LFQ E.coli experiments and
one at three centers from TMT human serum. Evaluations using these datasets
confirm that FedProt achieves accuracy equivalent to DEqMS applied to pooled
data, with completely negligible absolute differences no greater than $\text{$4
\times 10^{-12}$}$. In contrast, -log10(p-values) computed by the most accurate
meta-analysis methods diverged from the centralized analysis results by up to
25-27. FedProt is available as a web tool with detailed documentation as a
FeatureCloud App.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.14938v1">From Ad Identifiers to Global Privacy Control: The Status Quo and Future
  of Opting Out of Ad Tracking on Android</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-07-20T17:06:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sebastian Zimmeck, Nishant Aggarwal, Zachary Liu, Konrad Kollnig</p>
    <p><b>Summary:</b> Apps and their integrated third party libraries often collect a variety of
data from people to show them personalized ads. This practice is often
privacy-invasive. Since 2013, Google has therefore allowed users to limit ad
tracking on Android via system settings. Further, under the 2018 California
Consumer Privacy Act (CCPA), apps must honor opt-outs from ad tracking under
the Global Privacy Control (GPC). The efficacy of these two methods to limit ad
tracking has not been studied in prior work. Our legal and technical analysis
details how the GPC applies to mobile apps and how it could be integrated
directly into Android, thereby developing a reference design for GPC on
Android. Our empirical analysis of 1,896 top-ranked Android apps shows that
both the Android system-level opt-out and the GPC signal rarely restrict ad
tracking. In our view, deleting the AdID and opting out under the CCPA has the
same meaning. Thus, the current AdID setting and APIs should be evolved towards
GPC and integrated into Android's Privacy Sandbox.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.14719v1">Universal Medical Imaging Model for Domain Generalization with Data
  Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-07-20T01:24:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ahmed Radwan, Islam Osman, Mohamed S. Shehata</p>
    <p><b>Summary:</b> Achieving domain generalization in medical imaging poses a significant
challenge, primarily due to the limited availability of publicly labeled
datasets in this domain. This limitation arises from concerns related to data
privacy and the necessity for medical expertise to accurately label the data.
In this paper, we propose a federated learning approach to transfer knowledge
from multiple local models to a global model, eliminating the need for direct
access to the local datasets used to train each model. The primary objective is
to train a global model capable of performing a wide variety of medical imaging
tasks. This is done while ensuring the confidentiality of the private datasets
utilized during the training of these models. To validate the effectiveness of
our approach, extensive experiments were conducted on eight datasets, each
corresponding to a different medical imaging application. The client's data
distribution in our experiments varies significantly as they originate from
diverse domains. Despite this variation, we demonstrate a statistically
significant improvement over a state-of-the-art baseline utilizing masked image
modeling over a diverse pre-training dataset that spans different body parts
and scanning types. This improvement is achieved by curating information
learned from clients without accessing any labeled dataset on the server.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.14717v1">Differential Privacy of Cross-Attention with Provable Guarantee</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-20T01:02:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiuxiang Gu, Yingyu Liang, Zhenmei Shi, Zhao Song, Yufa Zhou</p>
    <p><b>Summary:</b> Cross-attention has become a fundamental module nowadays in many important
artificial intelligence applications, e.g., retrieval-augmented generation
(RAG), system prompt, guided stable diffusion, and many so on. Ensuring
cross-attention privacy is crucial and urgently needed because its key and
value matrices may contain sensitive information about companies and their
users, many of which profit solely from their system prompts or RAG data. In
this work, we design a novel differential privacy (DP) data structure to
address the privacy security of cross-attention with a theoretical guarantee.
In detail, let $n$ be the input token length of system prompt/RAG data, $d$ be
the feature dimension, $0 < \alpha \le 1$ be the relative error parameter, $R$
be the maximum value of the query and key matrices, $R_w$ be the maximum value
of the value matrix, and $r,s,\epsilon_s$ be parameters of polynomial kernel
methods. Then, our data structure requires $\widetilde{O}(ndr^2)$ memory
consumption with $\widetilde{O}(nr^2)$ initialization time complexity and
$\widetilde{O}(\alpha^{-1} r^2)$ query time complexity for a single token
query. In addition, our data structure can guarantee that the user query is
$(\epsilon, \delta)$-DP with $\widetilde{O}(n^{-1} \epsilon^{-1} \alpha^{-1/2}
R^{2s} R_w r^2)$ additive error and $n^{-1} (\alpha + \epsilon_s)$ relative
error between our output and the true answer. Furthermore, our result is robust
to adaptive queries in which users can intentionally attack the cross-attention
system. To our knowledge, this is the first work to provide DP for
cross-attention. We believe it can inspire more privacy algorithm design in
large generative models (LGMs).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.14710v2">Universally Harmonizing Differential Privacy Mechanisms for Federated
  Learning: Boosting Accuracy and Convergence</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-20T00:11:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuya Feng, Meisam Mohammady, Hanbin Hong, Shenao Yan, Ashish Kundu, Binghui Wang, Yuan Hong</p>
    <p><b>Summary:</b> Differentially private federated learning (DP-FL) is a promising technique
for collaborative model training while ensuring provable privacy for clients.
However, optimizing the tradeoff between privacy and accuracy remains a
critical challenge. To our best knowledge, we propose the first DP-FL framework
(namely UDP-FL), which universally harmonizes any randomization mechanism
(e.g., an optimal one) with the Gaussian Moments Accountant (viz. DP-SGD) to
significantly boost accuracy and convergence. Specifically, UDP-FL demonstrates
enhanced model performance by mitigating the reliance on Gaussian noise. The
key mediator variable in this transformation is the R\'enyi Differential
Privacy notion, which is carefully used to harmonize privacy budgets. We also
propose an innovative method to theoretically analyze the convergence for DP-FL
(including our UDP-FL ) based on mode connectivity analysis. Moreover, we
evaluate our UDP-FL through extensive experiments benchmarked against
state-of-the-art (SOTA) methods, demonstrating superior performance on both
privacy guarantees and model performance. Notably, UDP-FL exhibits substantial
resilience against different inference attacks, indicating a significant
advance in safeguarding sensitive data in federated learning environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.14641v1">Differential Privacy with Multiple Selections</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-19T19:34:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ashish Goel, Zhihao Jiang, Aleksandra Korolova, Kamesh Munagala, Sahasrajit Sarmasarkar</p>
    <p><b>Summary:</b> We consider the setting where a user with sensitive features wishes to obtain
a recommendation from a server in a differentially private fashion. We propose
a ``multi-selection'' architecture where the server can send back multiple
recommendations and the user chooses one from these that matches best with
their private features. When the user feature is one-dimensional -- on an
infinite line -- and the accuracy measure is defined w.r.t some increasing
function $\mathfrak{h}(.)$ of the distance on the line, we precisely
characterize the optimal mechanism that satisfies differential privacy. The
specification of the optimal mechanism includes both the distribution of the
noise that the user adds to its private value, and the algorithm used by the
server to determine the set of results to send back as a response and further
show that Laplace is an optimal noise distribution. We further show that this
optimal mechanism results in an error that is inversely proportional to the
number of results returned when the function $\mathfrak{h}(.)$ is the identity
function.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.13975v1">Personalized Privacy Protection Mask Against Unauthorized Facial
  Recognition</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-07-19T01:59:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ka-Ho Chow, Sihao Hu, Tiansheng Huang, Ling Liu</p>
    <p><b>Summary:</b> Face recognition (FR) can be abused for privacy intrusion. Governments,
private companies, or even individual attackers can collect facial images by
web scraping to build an FR system identifying human faces without their
consent. This paper introduces Chameleon, which learns to generate a
user-centric personalized privacy protection mask, coined as P3-Mask, to
protect facial images against unauthorized FR with three salient features.
First, we use a cross-image optimization to generate one P3-Mask for each user
instead of tailoring facial perturbation for each facial image of a user. It
enables efficient and instant protection even for users with limited computing
resources. Second, we incorporate a perceptibility optimization to preserve the
visual quality of the protected facial images. Third, we strengthen the
robustness of P3-Mask against unknown FR models by integrating focal
diversity-optimized ensemble learning into the mask generation process.
Extensive experiments on two benchmark datasets show that Chameleon outperforms
three state-of-the-art methods with instant protection and minimal degradation
of image quality. Furthermore, Chameleon enables cost-effective FR
authorization using the P3-Mask as a personalized de-obfuscation key, and it
demonstrates high resilience against adaptive adversaries.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.13881v1">Privacy-preserving gradient-based fair federated learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36"> 
  <p><b>Published on:</b> 2024-07-18T19:56:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Janis Adamek, Moritz Schulze Darup</p>
    <p><b>Summary:</b> Federated learning (FL) schemes allow multiple participants to
collaboratively train neural networks without the need to directly share the
underlying data.However, in early schemes, all participants eventually obtain
the same model. Moreover, the aggregation is typically carried out by a third
party, who obtains combined gradients or weights, which may reveal the model.
These downsides underscore the demand for fair and privacy-preserving FL
schemes. Here, collaborative fairness asks for individual model quality
depending on the individual data contribution. Privacy is demanded with respect
to any kind of data outsourced to the third party. Now, there already exist
some approaches aiming for either fair or privacy-preserving FL and a few works
even address both features. In our paper, we build upon these seminal works and
present a novel, fair and privacy-preserving FL scheme. Our approach, which
mainly relies on homomorphic encryption, stands out for exclusively using local
gradients. This increases the usability in comparison to state-of-the-art
approaches and thereby opens the door to applications in control.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.13725v1">Scalable Optimization for Locally Relevant Geo-Location Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-18T17:25:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chenxi Qiu, Ruiyao Liu, Primal Pappachan, Anna Squicciarini, Xinpeng Xie</p>
    <p><b>Summary:</b> Geo-obfuscation functions as a location privacy protection mechanism (LPPM),
enabling mobile users to share obfuscated locations with servers instead of
their exact locations. This technique protects users' location privacy during
server-side data breaches since the obfuscation process is irreversible. To
minimize the utility loss caused by data obfuscation, linear programming (LP)
is widely used. However, LP can face a polynomial explosion in decision
variables, making it impractical for large-scale geo-obfuscation applications.
In this paper, we propose a new LPPM called Locally Relevant Geo-obfuscation
(LR-Geo) to optimize geo-obfuscation using LP more efficiently. This is
accomplished by restricting the geo-obfuscation calculations for each user to
locally relevant (LR) locations near the user's actual location. To prevent LR
locations from inadvertently revealing a user's true whereabouts, users compute
the LP coefficients locally and upload only these coefficients to the server,
rather than the LR locations themselves. The server then solves the LP problem
using the provided coefficients. Additionally, we enhance the LP framework with
an exponential obfuscation mechanism to ensure that the obfuscation
distribution is indistinguishable across multiple users. By leveraging the
constraint structure of the LP formulation, we apply Benders' decomposition to
further boost computational efficiency. Our theoretical analysis confirms that,
even though geo-obfuscation is calculated independently for each user, it still
adheres to geo-indistinguishability constraints across multiple users with high
probability. Finally, experimental results using a real-world dataset
demonstrate that LR-Geo outperforms existing geo-obfuscation methods in terms
of computational time, data utility, and privacy protection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.13621v1">Differential Privacy Mechanisms in Neural Tangent Kernel Regression</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-18T15:57:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiuxiang Gu, Yingyu Liang, Zhizhou Sha, Zhenmei Shi, Zhao Song</p>
    <p><b>Summary:</b> Training data privacy is a fundamental problem in modern Artificial
Intelligence (AI) applications, such as face recognition, recommendation
systems, language generation, and many others, as it may contain sensitive user
information related to legal issues. To fundamentally understand how privacy
mechanisms work in AI applications, we study differential privacy (DP) in the
Neural Tangent Kernel (NTK) regression setting, where DP is one of the most
powerful tools for measuring privacy under statistical learning, and NTK is one
of the most popular analysis frameworks for studying the learning mechanisms of
deep neural networks. In our work, we can show provable guarantees for both
differential privacy and test accuracy of our NTK regression. Furthermore, we
conduct experiments on the basic image classification dataset CIFAR10 to
demonstrate that NTK regression can preserve good accuracy under a modest
privacy budget, supporting the validity of our analysis. To our knowledge, this
is the first work to provide a DP guarantee for NTK regression.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.13532v1">PriPL-Tree: Accurate Range Query for Arbitrary Distribution under Local
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2024-07-18T14:05:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Leixia Wang, Qingqing Ye, Haibo Hu, Xiaofeng Meng</p>
    <p><b>Summary:</b> Answering range queries in the context of Local Differential Privacy (LDP) is
a widely studied problem in Online Analytical Processing (OLAP). Existing LDP
solutions all assume a uniform data distribution within each domain partition,
which may not align with real-world scenarios where data distribution is
varied, resulting in inaccurate estimates. To address this problem, we
introduce PriPL-Tree, a novel data structure that combines hierarchical tree
structures with piecewise linear (PL) functions to answer range queries for
arbitrary distributions. PriPL-Tree precisely models the underlying data
distribution with a few line segments, leading to more accurate results for
range queries. Furthermore, we extend it to multi-dimensional cases with novel
data-aware adaptive grids. These grids leverage the insights from marginal
distributions obtained through PriPL-Trees to partition the grids adaptively,
adapting the density of underlying distributions. Our extensive experiments on
both real and synthetic datasets demonstrate the effectiveness and superiority
of PriPL-Tree over state-of-the-art solutions in answering range queries across
arbitrary data distributions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.13516v1">Optimal Mechanisms for Quantum Local Differential Privacy</a></h3>
  
  <p><b>Published on:</b> 2024-07-18T13:46:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ji Guan</p>
    <p><b>Summary:</b> In recent years, centralized differential privacy has been successfully
extended to quantum computing and information processing to safeguard privacy
and prevent leaks in neighboring relationships of quantum states. This paper
introduces a framework known as quantum local differential privacy (QLDP) and
initializes the algorithmic study of QLDP. QLDP utilizes a parameter $\epsilon$
to manage privacy leaks and ensure the privacy of individual quantum states.
The optimization of the QLDP value $\epsilon$, denoted as $\epsilon^*$, for any
quantum mechanism is addressed as an optimization problem. The introduction of
quantum noise is shown to provide privacy protections similar to classical
scenarios, with quantum depolarizing noise identified as the optimal unital
privatization mechanism within the QLDP framework. Unital mechanisms represent
a diverse set of quantum mechanisms that encompass frequently employed quantum
noise types. Quantum depolarizing noise optimizes both fidelity and trace
distance utilities, which are crucial metrics in the field of quantum
computation and information, and can be viewed as a quantum counterpart to
classical randomized response methods. Additionally, a composition theorem is
presented for the application of QLDP framework in distributed (spatially
separated) quantum systems, ensuring the validity (additivity of QLDP value)
irrespective of the states' independence, classical correlation, or
entanglement (quantum correlation). The study further explores the trade-off
between utility and privacy across different quantum noise mechanisms,
including unital and non-unital quantum noise mechanisms, through both
analytical and numerically experimental approaches. Meanwhile, this highlights
the optimization of quantum depolarizing noise in QLDP framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.13153v1">Preset-Voice Matching for Privacy Regulated Speech-to-Speech Translation
  Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> 
  <p><b>Published on:</b> 2024-07-18T04:42:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Daniel Platnick, Bishoy Abdelnour, Eamon Earl, Rahul Kumar, Zahra Rezaei, Thomas Tsangaris, Faraj Lagum</p>
    <p><b>Summary:</b> In recent years, there has been increased demand for speech-to-speech
translation (S2ST) systems in industry settings. Although successfully
commercialized, cloning-based S2ST systems expose their distributors to
liabilities when misused by individuals and can infringe on personality rights
when exploited by media organizations. This work proposes a regulated S2ST
framework called Preset-Voice Matching (PVM). PVM removes cross-lingual voice
cloning in S2ST by first matching the input voice to a similar prior consenting
speaker voice in the target-language. With this separation, PVM avoids cloning
the input speaker, ensuring PVM systems comply with regulations and reduce risk
of misuse. Our results demonstrate PVM can significantly improve S2ST system
run-time in multi-speaker settings and the naturalness of S2ST synthesized
speech. To our knowledge, PVM is the first explicitly regulated S2ST framework
leveraging similarly-matched preset-voices for dynamic S2ST tasks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.15868v1">A Survey on Differential Privacy for SpatioTemporal Data in
  Transportation Research</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">  
  <p><b>Published on:</b> 2024-07-18T03:19:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rahul Bhadani</p>
    <p><b>Summary:</b> With low-cost computing devices, improved sensor technology, and the
proliferation of data-driven algorithms, we have more data than we know what to
do with. In transportation, we are seeing a surge in spatiotemporal data
collection. At the same time, concerns over user privacy have led to research
on differential privacy in applied settings. In this paper, we look at some
recent developments in differential privacy in the context of spatiotemporal
data. Spatiotemporal data contain not only features about users but also the
geographical locations of their frequent visits. Hence, the public release of
such data carries extreme risks. To address the need for such data in research
and inference without exposing private information, significant work has been
proposed. This survey paper aims to summarize these efforts and provide a
review of differential privacy mechanisms and related software. We also discuss
related work in transportation where such mechanisms have been applied.
Furthermore, we address the challenges in the deployment and mass adoption of
differential privacy in transportation spatiotemporal data for downstream
analyses.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.12669v1">Enhancing the Utility of Privacy-Preserving Cancer Classification using
  Synthetic Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-07-17T15:52:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Richard Osuala, Daniel M. Lang, Anneliese Riess, Georgios Kaissis, Zuzanna Szafranowska, Grzegorz Skorupko, Oliver Diaz, Julia A. Schnabel, Karim Lekadir</p>
    <p><b>Summary:</b> Deep learning holds immense promise for aiding radiologists in breast cancer
detection. However, achieving optimal model performance is hampered by
limitations in availability and sharing of data commonly associated to patient
privacy concerns. Such concerns are further exacerbated, as traditional deep
learning models can inadvertently leak sensitive training information. This
work addresses these challenges exploring and quantifying the utility of
privacy-preserving deep learning techniques, concretely, (i) differentially
private stochastic gradient descent (DP-SGD) and (ii) fully synthetic training
data generated by our proposed malignancy-conditioned generative adversarial
network. We assess these methods via downstream malignancy classification of
mammography masses using a transformer model. Our experimental results depict
that synthetic data augmentation can improve privacy-utility tradeoffs in
differentially private model training. Further, model pretraining on synthetic
data achieves remarkable performance, which can be further increased with
DP-SGD fine-tuning across all privacy guarantees. With this first in-depth
exploration of privacy-preserving deep learning in breast imaging, we address
current and emerging clinical privacy requirements and pave the way towards the
adoption of private high-utility deep diagnostic models. Our reproducible
codebase is publicly available at https://github.com/RichardObi/mammo_dp.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.12589v1">Privacy-Preserving Adaptive Re-Identification without Image Transfer</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-07-17T14:12:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hamza Rami, Jhony H. Giraldo, Nicolas Winckler, Stéphane Lathuilière</p>
    <p><b>Summary:</b> Re-Identification systems (Re-ID) are crucial for public safety but face the
challenge of having to adapt to environments that differ from their training
distribution. Furthermore, rigorous privacy protocols in public places are
being enforced as apprehensions regarding individual freedom rise, adding
layers of complexity to the deployment of accurate Re-ID systems in new
environments. For example, in the European Union, the principles of ``Data
Minimization'' and ``Purpose Limitation'' restrict the retention and processing
of images to what is strictly necessary. These regulations pose a challenge to
the conventional Re-ID training schemes that rely on centralizing data on
servers. In this work, we present a novel setting for privacy-preserving
Distributed Unsupervised Domain Adaptation for person Re-ID (DUDA-Rid) to
address the problem of domain shift without requiring any image transfer
outside the camera devices. To address this setting, we introduce Fed-Protoid,
a novel solution that adapts person Re-ID models directly within the edge
devices. Our proposed solution employs prototypes derived from the source
domain to align feature statistics within edge devices. Those source prototypes
are distributed across the edge devices to minimize a distributed Maximum Mean
Discrepancy (MMD) loss tailored for the DUDA-Rid setting. Our experiments
provide compelling evidence that Fed-Protoid outperforms all evaluated methods
in terms of both accuracy and communication efficiency, all while maintaining
data privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.11274v1">Empirical Mean and Frequency Estimation Under Heterogeneous Privacy: A
  Worst-Case Analysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-07-15T22:46:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Syomantak Chaudhuri, Thomas A. Courtade</p>
    <p><b>Summary:</b> Differential Privacy (DP) is the current gold-standard for measuring privacy.
Estimation problems under DP constraints appearing in the literature have
largely focused on providing equal privacy to all users. We consider the
problems of empirical mean estimation for univariate data and frequency
estimation for categorical data, two pillars of data analysis in the industry,
subject to heterogeneous privacy constraints. Each user, contributing a sample
to the dataset, is allowed to have a different privacy demand. The dataset
itself is assumed to be worst-case and we study both the problems in two
different formulations -- the correlated and the uncorrelated setting. In the
former setting, the privacy demand and the user data can be arbitrarily
correlated while in the latter setting, there is no correlation between the
dataset and the privacy demand. We prove some optimality results, under both
PAC error and mean-squared error, for our proposed algorithms and demonstrate
superior performance over other baseline techniques experimentally.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.10094v1">Work-From-Home and Privacy: What Do Workers Face and What are They Doing
  About it?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-07-14T06:15:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Eman Alashwali, Joanne Peca, Mandy Lanyon, Lorrie Cranor</p>
    <p><b>Summary:</b> The COVID-19 pandemic has reshaped the way people work, normalizing the
practice of working from home (WFH). However, WFH can cause a blurring of
personal and professional boundaries, surfacing new privacy issues, especially
when workers take work meetings from their homes. As WFH arrangements are now
standard practice in many organizations, addressing the associated privacy
concerns should be a key part of creating healthy work environments for
workers. To this end, we conducted a scenario-based survey with 214 US-based
workers who currently work from home regularly. Our results suggest that
privacy invasions are commonly experienced while working from home and cause
discomfort to many workers. However, only a minority said that the discomfort
escalated to cause harm to them or others, and the harm was almost always
psychological. While scenarios that restrict worker autonomy (prohibit turning
off camera or microphone) are the least experienced scenarios, they are
associated with the highest reported discomfort. In addition, participants
reported measures that violated or would violate their employer's
autonomy-restricting rules to protect their privacy. We also find that
conference tool settings that can prevent privacy invasions are not widely used
compared to manual privacy-protective measures. Our findings provide better
understanding of the privacy challenges landscape that WFH workers face and how
they address them. Furthermore, our discussion raised open questions that can
inspire future work.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.10058v1">Learning to Refuse: Towards Mitigating Privacy Risks in LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-07-14T03:05:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhenhua Liu, Tong Zhu, Chuanyuan Tan, Wenliang Chen</p>
    <p><b>Summary:</b> Large language models (LLMs) exhibit remarkable capabilities in understanding
and generating natural language. However, these models can inadvertently
memorize private information, posing significant privacy risks. This study
addresses the challenge of enabling LLMs to protect specific individuals'
private data without the need for complete retraining. We propose \return, a
Real-world pErsonal daTa UnleaRNing dataset, comprising 2,492 individuals from
Wikipedia with associated QA pairs, to evaluate machine unlearning (MU) methods
for protecting personal data in a realistic scenario. Additionally, we
introduce the Name-Aware Unlearning Framework (NAUF) for Privacy Protection,
which enables the model to learn which individuals' information should be
protected without affecting its ability to answer questions related to other
unrelated individuals. Our extensive experiments demonstrate that NAUF achieves
a state-of-the-art average unlearning score, surpassing the best baseline
method by 5.65 points, effectively protecting target individuals' personal data
while maintaining the model's general capabilities.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.09809v1">Preserving the Privacy of Reward Functions in MDPs through Deception</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-07-13T09:03:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shashank Reddy Chirra, Pradeep Varakantham, Praveen Paruchuri</p>
    <p><b>Summary:</b> Preserving the privacy of preferences (or rewards) of a sequential
decision-making agent when decisions are observable is crucial in many physical
and cybersecurity domains. For instance, in wildlife monitoring, agents must
allocate patrolling resources without revealing animal locations to poachers.
This paper addresses privacy preservation in planning over a sequence of
actions in MDPs, where the reward function represents the preference structure
to be protected. Observers can use Inverse RL (IRL) to learn these preferences,
making this a challenging task.
  Current research on differential privacy in reward functions fails to ensure
guarantee on the minimum expected reward and offers theoretical guarantees that
are inadequate against IRL-based observers. To bridge this gap, we propose a
novel approach rooted in the theory of deception. Deception includes two
models: dissimulation (hiding the truth) and simulation (showing the wrong).
Our first contribution theoretically demonstrates significant privacy leaks in
existing dissimulation-based methods. Our second contribution is a novel
RL-based planning algorithm that uses simulation to effectively address these
privacy concerns while ensuring a guarantee on the expected reward. Experiments
on multiple benchmark problems show that our approach outperforms previous
methods in preserving reward function privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.09771v1">Protecting Data Buyer Privacy in Data Markets</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2024-07-13T04:45:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Minxing Zhang, Jian Pei</p>
    <p><b>Summary:</b> Data markets serve as crucial platforms facilitating data discovery,
exchange, sharing, and integration among data users and providers. However, the
paramount concern of privacy has predominantly centered on protecting privacy
of data owners and third parties, neglecting the challenges associated with
protecting the privacy of data buyers. In this article, we address this gap by
modeling the intricacies of data buyer privacy protection and investigating the
delicate balance between privacy and purchase cost. Through comprehensive
experimentation, our results yield valuable insights, shedding light on the
efficacy and efficiency of our proposed approaches.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.09324v1">Provable Privacy Advantages of Decentralized Federated Learning via
  Distributed Optimization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2024-07-12T15:01:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenrui Yu, Qiongxiu Li, Milan Lopuhaä-Zwakenberg, Mads Græsbøll Christensen, Richard Heusdens</p>
    <p><b>Summary:</b> Federated learning (FL) emerged as a paradigm designed to improve data
privacy by enabling data to reside at its source, thus embedding privacy as a
core consideration in FL architectures, whether centralized or decentralized.
Contrasting with recent findings by Pasquini et al., which suggest that
decentralized FL does not empirically offer any additional privacy or security
benefits over centralized models, our study provides compelling evidence to the
contrary. We demonstrate that decentralized FL, when deploying distributed
optimization, provides enhanced privacy protection - both theoretically and
empirically - compared to centralized approaches. The challenge of quantifying
privacy loss through iterative processes has traditionally constrained the
theoretical exploration of FL protocols. We overcome this by conducting a
pioneering in-depth information-theoretical privacy analysis for both
frameworks. Our analysis, considering both eavesdropping and passive adversary
models, successfully establishes bounds on privacy leakage. We show information
theoretically that the privacy loss in decentralized FL is upper bounded by the
loss in centralized FL. Compared to the centralized case where local gradients
of individual participants are directly revealed, a key distinction of
optimization-based decentralized FL is that the relevant information includes
differences of local gradients over successive iterations and the aggregated
sum of different nodes' gradients over the network. This information
complicates the adversary's attempt to infer private data. To bridge our
theoretical insights with practical applications, we present detailed case
studies involving logistic regression and deep neural networks. These examples
demonstrate that while privacy leakage remains comparable in simpler models,
complex models like deep neural networks exhibit lower privacy risks under
decentralized FL.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.09239v1">FedVAE: Trajectory privacy preserving based on Federated Variational
  AutoEncoder</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-07-12T13:10:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuchen Jiang, Ying Wu, Shiyao Zhang, James J. Q. Yu</p>
    <p><b>Summary:</b> The use of trajectory data with abundant spatial-temporal information is
pivotal in Intelligent Transport Systems (ITS) and various traffic system
tasks. Location-Based Services (LBS) capitalize on this trajectory data to
offer users personalized services tailored to their location information.
However, this trajectory data contains sensitive information about users'
movement patterns and habits, necessitating confidentiality and protection from
unknown collectors. To address this challenge, privacy-preserving methods like
K-anonymity and Differential Privacy have been proposed to safeguard private
information in the dataset. Despite their effectiveness, these methods can
impact the original features by introducing perturbations or generating
unrealistic trajectory data, leading to suboptimal performance in downstream
tasks. To overcome these limitations, we propose a Federated Variational
AutoEncoder (FedVAE) approach, which effectively generates a new trajectory
dataset while preserving the confidentiality of private information and
retaining the structure of the original features. In addition, FedVAE leverages
Variational AutoEncoder (VAE) to maintain the original feature space and
generate new trajectory data, and incorporates Federated Learning (FL) during
the training stage, ensuring that users' data remains locally stored to protect
their personal information. The results demonstrate its superior performance
compared to other existing methods, affirming FedVAE as a promising solution
for enhancing data privacy and utility in location-based applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.09004v1">Privacy-Preserving Collaborative Genomic Research: A Real-Life
  Deployment and Vision</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-12T05:43:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zahra Rahmani, Nahal Shahini, Nadav Gat, Zebin Yun, Yuzhou Jiang, Ofir Farchy, Yaniv Harel, Vipin Chaudhary, Mahmood Sharif, Erman Ayday</p>
    <p><b>Summary:</b> The data revolution holds significant promise for the health sector. Vast
amounts of data collected from individuals will be transformed into knowledge,
AI models, predictive systems, and best practices. One area of health that
stands to benefit greatly is the genomic domain. Progress in AI, machine
learning, and data science has opened new opportunities for genomic research,
promising breakthroughs in personalized medicine. However, increasing awareness
of privacy and cybersecurity necessitates robust solutions to protect sensitive
data in collaborative research. This paper presents a practical deployment of a
privacy-preserving framework for genomic research, developed in collaboration
with Lynx$.$MD, a platform for secure health data collaboration. The framework
addresses critical cybersecurity and privacy challenges, enabling the
privacy-preserving sharing and analysis of genomic data while mitigating risks
associated with data breaches. By integrating advanced privacy-preserving
algorithms, the solution ensures the protection of individual privacy without
compromising data utility. A unique feature of the system is its ability to
balance trade-offs between data sharing and privacy, providing stakeholders
tools to quantify privacy risks and make informed decisions. Implementing the
framework within Lynx$.$MD involves encoding genomic data into binary formats
and applying noise through controlled perturbation techniques. This approach
preserves essential statistical properties of the data, facilitating effective
research and analysis. Moreover, the system incorporates real-time data
monitoring and advanced visualization tools, enhancing user experience and
decision-making. The paper highlights the need for tailored privacy attacks and
defenses specific to genomic data. Addressing these challenges fosters
collaboration in genomic research, advancing personalized medicine and public
health.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.08977v1">CURE: Privacy-Preserving Split Learning Done Right</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-12T04:10:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Halil Ibrahim Kanpak, Aqsa Shabbir, Esra Genç, Alptekin Küpçü, Sinem Sav</p>
    <p><b>Summary:</b> Training deep neural networks often requires large-scale datasets,
necessitating storage and processing on cloud servers due to computational
constraints. The procedures must follow strict privacy regulations in domains
like healthcare. Split Learning (SL), a framework that divides model layers
between client(s) and server(s), is widely adopted for distributed model
training. While Split Learning reduces privacy risks by limiting server access
to the full parameter set, previous research has identified that intermediate
outputs exchanged between server and client can compromise client's data
privacy. Homomorphic encryption (HE)-based solutions exist for this scenario
but often impose prohibitive computational burdens.
  To address these challenges, we propose CURE, a novel system based on HE,
that encrypts only the server side of the model and optionally the data. CURE
enables secure SL while substantially improving communication and
parallelization through advanced packing techniques. We propose two packing
schemes that consume one HE level for one-layer networks and generalize our
solutions to n-layer neural networks. We demonstrate that CURE can achieve
similar accuracy to plaintext SL while being 16x more efficient in terms of the
runtime compared to the state-of-the-art privacy-preserving alternatives.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.08954v1">PriRoAgg: Achieving Robust Model Aggregation with Minimum Privacy
  Leakage for Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-12T03:18:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sizai Hou, Songze Li, Tayyebeh Jahani-Nezhad, Giuseppe Caire</p>
    <p><b>Summary:</b> Federated learning (FL) has recently gained significant momentum due to its
potential to leverage large-scale distributed user data while preserving user
privacy. However, the typical paradigm of FL faces challenges of both privacy
and robustness: the transmitted model updates can potentially leak sensitive
user information, and the lack of central control of the local training process
leaves the global model susceptible to malicious manipulations on model
updates. Current solutions attempting to address both problems under the
one-server FL setting fall short in the following aspects: 1) designed for
simple validity checks that are insufficient against advanced attacks (e.g.,
checking norm of individual update); and 2) partial privacy leakage for more
complicated robust aggregation algorithms (e.g., distances between model
updates are leaked for multi-Krum). In this work, we formalize a novel security
notion of aggregated privacy that characterizes the minimum amount of user
information, in the form of some aggregated statistics of users' updates, that
is necessary to be revealed to accomplish more advanced robust aggregation. We
develop a general framework PriRoAgg, utilizing Lagrange coded computing and
distributed zero-knowledge proof, to execute a wide range of robust aggregation
algorithms while satisfying aggregated privacy. As concrete instantiations of
PriRoAgg, we construct two secure and robust protocols based on
state-of-the-art robust algorithms, for which we provide full theoretical
analyses on security and complexity. Extensive experiments are conducted for
these protocols, demonstrating their robustness against various model integrity
attacks, and their efficiency advantages over baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.08529v3">Enhancing Privacy of Spatiotemporal Federated Learning against Gradient
  Inversion Attacks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-11T14:17:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lele Zheng, Yang Cao, Renhe Jiang, Kenjiro Taura, Yulong Shen, Sheng Li, Masatoshi Yoshikawa</p>
    <p><b>Summary:</b> Spatiotemporal federated learning has recently raised intensive studies due
to its ability to train valuable models with only shared gradients in various
location-based services. On the other hand, recent studies have shown that
shared gradients may be subject to gradient inversion attacks (GIA) on images
or texts. However, so far there has not been any systematic study of the
gradient inversion attacks in spatiotemporal federated learning. In this paper,
we explore the gradient attack problem in spatiotemporal federated learning
from attack and defense perspectives. To understand privacy risks in
spatiotemporal federated learning, we first propose Spatiotemporal Gradient
Inversion Attack (ST-GIA), a gradient attack algorithm tailored to
spatiotemporal data that successfully reconstructs the original location from
gradients. Furthermore, we design an adaptive defense strategy to mitigate
gradient inversion attacks in spatiotemporal federated learning. By dynamically
adjusting the perturbation levels, we can offer tailored protection for varying
rounds of training data, thereby achieving a better trade-off between privacy
and utility than current state-of-the-art methods. Through intensive
experimental analysis on three real-world datasets, we reveal that the proposed
defense strategy can well preserve the utility of spatiotemporal federated
learning with effective security protection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.08152v1">Privacy-Preserving Data Deduplication for Enhancing Federated Learning
  of Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-07-11T03:10:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aydin Abadi, Vishnu Asutosh Dasu, Sumanta Sarkar</p>
    <p><b>Summary:</b> Deduplication is a vital preprocessing step that enhances machine learning
model performance and saves training time and energy. However, enhancing
federated learning through deduplication poses challenges, especially regarding
scalability and potential privacy violations if deduplication involves sharing
all clients' data. In this paper, we address the problem of deduplication in a
federated setup by introducing a pioneering protocol, Efficient
Privacy-Preserving Multi-Party Deduplication (EP-MPD). It efficiently removes
duplicates from multiple clients' datasets without compromising data privacy.
EP-MPD is constructed in a modular fashion, utilizing two novel variants of the
Private Set Intersection protocol. Our extensive experiments demonstrate the
significant benefits of deduplication in federated learning of large language
models. For instance, we observe up to 19.61% improvement in perplexity and up
to 27.95% reduction in running time. EP-MPD effectively balances privacy and
performance in federated learning, making it a valuable solution for
large-scale applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.07737v1">Fine-Tuning Large Language Models with User-Level Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-07-10T15:07:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zachary Charles, Arun Ganesh, Ryan McKenna, H. Brendan McMahan, Nicole Mitchell, Krishna Pillutla, Keith Rush</p>
    <p><b>Summary:</b> We investigate practical and scalable algorithms for training large language
models (LLMs) with user-level differential privacy (DP) in order to provably
safeguard all the examples contributed by each user. We study two variants of
DP-SGD with: (1) example-level sampling (ELS) and per-example gradient
clipping, and (2) user-level sampling (ULS) and per-user gradient clipping. We
derive a novel user-level DP accountant that allows us to compute provably
tight privacy guarantees for ELS. Using this, we show that while ELS can
outperform ULS in specific settings, ULS generally yields better results when
each user has a diverse collection of examples. We validate our findings
through experiments in synthetic mean estimation and LLM fine-tuning tasks
under fixed compute budgets. We find that ULS is significantly better in
settings where either (1) strong privacy guarantees are required, or (2) the
compute budget is large. Notably, our focus on LLM-compatible training
algorithms allows us to scale to models with hundreds of millions of parameters
and datasets with hundreds of thousands of users.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.07262v1">Differential privacy and Sublinear time are incompatible sometimes</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-09T22:33:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jeremiah Blocki, Hendrik Fichtenberger, Elena Grigorescu, Tamalika Mukherjee</p>
    <p><b>Summary:</b> Differential privacy and sublinear algorithms are both rapidly emerging
algorithmic themes in times of big data analysis. Although recent works have
shown the existence of differentially private sublinear algorithms for many
problems including graph parameter estimation and clustering, little is known
regarding hardness results on these algorithms. In this paper, we initiate the
study of lower bounds for problems that aim for both differentially-private and
sublinear-time algorithms. Our main result is the incompatibility of both the
desiderata in the general case. In particular, we prove that a simple problem
based on one-way marginals yields both a differentially-private algorithm, as
well as a sublinear-time algorithm, but does not admit a ``strictly''
sublinear-time algorithm that is also differentially private.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.07066v2">Explainable Hyperdimensional Computing for Balancing Privacy and
  Transparency in Additive Manufacturing Monitoring</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-07-09T17:42:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fardin Jalil Piran, Prathyush P. Poduval, Hamza Errahmouni Barkam, Mohsen Imani, Farhad Imani</p>
    <p><b>Summary:</b> In-situ sensing, in conjunction with learning models, presents a unique
opportunity to address persistent defect issues in Additive Manufacturing (AM)
processes. However, this integration introduces significant data privacy
concerns, such as data leakage, sensor data compromise, and model inversion
attacks, revealing critical details about part design, material composition,
and machine parameters. Differential Privacy (DP) models, which inject noise
into data under mathematical guarantees, offer a nuanced balance between data
utility and privacy by obscuring traces of sensing data. However, the
introduction of noise into learning models, often functioning as black boxes,
complicates the prediction of how specific noise levels impact model accuracy.
This study introduces the Differential Privacy-HyperDimensional computing
(DP-HD) framework, leveraging the explainability of the vector symbolic
paradigm to predict the noise impact on the accuracy of in-situ monitoring,
safeguarding sensitive data while maintaining operational efficiency.
Experimental results on real-world high-speed melt pool data of AM for
detecting overhang anomalies demonstrate that DP-HD achieves superior
operational efficiency, prediction accuracy, and robust privacy protection,
outperforming state-of-the-art Machine Learning (ML) models. For example, when
implementing the same level of privacy protection (with a privacy budget set at
1), our model achieved an accuracy of 94.43%, surpassing the performance of
traditional models such as ResNet50 (52.30%), GoogLeNet (23.85%), AlexNet
(55.78%), DenseNet201 (69.13%), and EfficientNet B2 (40.81%). Notably, DP-HD
maintains high performance under substantial noise additions designed to
enhance privacy, unlike current models that suffer significant accuracy
declines under high privacy constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.18923v1">Towards a Novel Privacy-Preserving Distributed Multiparty Data
  Outsourcing Scheme for Cloud Computing with Quantum Key Distribution</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-09T15:53:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> D. Dhinakaran, D. Selvaraj, N. Dharini, S. Edwin Raja, C. Sakthi Lakshmi Priya</p>
    <p><b>Summary:</b> The intersection of cloud computing, blockchain technology, and the impending
era of quantum computing presents a critical juncture for data security. This
research addresses the escalating vulnerabilities by proposing a comprehensive
framework that integrates Quantum Key Distribution (QKD), CRYSTALS Kyber, and
Zero-Knowledge Proofs (ZKPs) for securing data in cloud-based blockchain
systems. The primary objective is to fortify data against quantum threats
through the implementation of QKD, a quantum-safe cryptographic protocol. We
leverage the lattice-based cryptographic mechanism, CRYSTALS Kyber, known for
its resilience against quantum attacks. Additionally, ZKPs are introduced to
enhance data privacy and verification processes within the cloud and blockchain
environment. A significant focus of this research is the performance evaluation
of the proposed framework. Rigorous analyses encompass encryption and
decryption processes, quantum key generation rates, and overall system
efficiency. Practical implications are scrutinized, considering factors such as
file size, response time, and computational overhead. The evaluation sheds
light on the framework's viability in real-world cloud environments,
emphasizing its efficiency in mitigating quantum threats. The findings
contribute a robust quantum-safe and ZKP-integrated security framework tailored
for cloud-based blockchain storage. By addressing critical gaps in theoretical
advancements, this research offers practical insights for organizations seeking
to secure their data against quantum threats. The framework's efficiency and
scalability underscore its practical feasibility, serving as a guide for
implementing enhanced data security in the evolving landscape of quantum
computing and blockchain integration within cloud environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.07926v1">Synthetic Data: Revisiting the Privacy-Utility Trade-off</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-07-09T14:48:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fatima Jahan Sarmin, Atiquer Rahman Sarkar, Yang Wang, Noman Mohammed</p>
    <p><b>Summary:</b> Synthetic data has been considered a better privacy-preserving alternative to
traditionally sanitized data across various applications. However, a recent
article challenges this notion, stating that synthetic data does not provide a
better trade-off between privacy and utility than traditional anonymization
techniques, and that it leads to unpredictable utility loss and highly
unpredictable privacy gain. The article also claims to have identified a breach
in the differential privacy guarantees provided by PATEGAN and PrivBayes. When
a study claims to refute or invalidate prior findings, it is crucial to verify
and validate the study. In our work, we analyzed the implementation of the
privacy game described in the article and found that it operated in a highly
specialized and constrained environment, which limits the applicability of its
findings to general cases. Our exploration also revealed that the game did not
satisfy a crucial precondition concerning data distributions, which contributed
to the perceived violation of the differential privacy guarantees offered by
PATEGAN and PrivBayes. We also conducted a privacy-utility trade-off analysis
in a more general and unconstrained environment. Our experimentation
demonstrated that synthetic data achieves a more favorable privacy-utility
trade-off compared to the provided implementation of k-anonymization, thereby
reaffirming earlier conclusions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.06778v1">A BERT-based Empirical Study of Privacy Policies' Compliance with GDPR</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-07-09T11:47:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lu Zhang, Nabil Moukafih, Hamad Alamri, Gregory Epiphaniou, Carsten Maple</p>
    <p><b>Summary:</b> Since its implementation in May 2018, the General Data Protection Regulation
(GDPR) has prompted businesses to revisit and revise their data handling
practices to ensure compliance. The privacy policy, which serves as the primary
means of informing users about their privacy rights and the data practices of
companies, has been significantly updated by numerous businesses post-GDPR
implementation. However, many privacy policies remain packed with technical
jargon, lengthy explanations, and vague descriptions of data practices and user
rights. This makes it a challenging task for users and regulatory authorities
to manually verify the GDPR compliance of these privacy policies. In this
study, we aim to address the challenge of compliance analysis between GDPR
(Article 13) and privacy policies for 5G networks. We manually collected
privacy policies from almost 70 different 5G MNOs, and we utilized an automated
BERT-based model for classification. We show that an encouraging 51$\%$ of
companies demonstrate a strong adherence to GDPR. In addition, we present the
first study that provides current empirical evidence on the readability of
privacy policies for 5G network. we adopted readability analysis toolset that
incorporates various established readability metrics. The findings empirically
show that the readability of the majority of current privacy policies remains a
significant challenge. Hence, 5G providers need to invest considerable effort
into revising these documents to enhance both their utility and the overall
user experience.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.06496v1">It's Our Loss: No Privacy Amplification for Hidden State DP-SGD With
  Non-Convex Loss</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-09T01:58:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Meenatchi Sundaram Muthu Selva Annamalai</p>
    <p><b>Summary:</b> Differentially Private Stochastic Gradient Descent (DP-SGD) is a popular
iterative algorithm used to train machine learning models while formally
guaranteeing the privacy of users. However the privacy analysis of DP-SGD makes
the unrealistic assumption that all intermediate iterates (aka internal state)
of the algorithm are released since in practice, only the final trained model,
i.e., the final iterate of the algorithm is released. In this hidden state
setting, prior work has provided tighter analyses, albeit only when the loss
function is constrained, e.g., strongly convex and smooth or linear. On the
other hand, the privacy leakage observed empirically from hidden state DP-SGD,
even when using non-convex loss functions suggest that there is in fact a gap
between the theoretical privacy analysis and the privacy guarantees achieved in
practice. Therefore, it remains an open question whether privacy amplification
for DP-SGD is possible in the hidden state setting for general loss functions.
  Unfortunately, this work answers the aforementioned research question
negatively. By carefully constructing a loss function for DP-SGD, we show that
for specific loss functions, the final iterate of DP-SGD alone leaks as much
information as the sequence of all iterates combined. Furthermore, we
empirically verify this result by evaluating the privacy leakage from the final
iterate of DP-SGD with our loss function and show that this matches the
theoretical upper bound guaranteed by DP exactly. Therefore, we show that the
current privacy analysis fo DP-SGD is tight for general loss functions and
conclude that no privacy amplification is possible for DP-SGD in general for
all (possibly non-convex) loss functions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.06495v1">Impact Evaluation on the European Privacy Laws governing generative-AI
  models -- Evidence in Relation between Internet Censorship and the Ban of
  ChatGPT in Italy</a></h3>
    
  <p><b>Published on:</b> 2024-07-09T01:56:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tatsuru Kikuchi</p>
    <p><b>Summary:</b> We proceed an impact evaluation on the European Privacy Laws governing
generative-AI models, especially, focusing on the effects of the Ban of ChatGPT
in Italy. We investigate on the causal relationship between Internet Censorship
Data and the Ban of ChatGPT in Italy during the period from March 27, 2023 to
April 11, 2023. We analyze the relation based on the hidden Markov model with
Poisson emissions. We find out that the HTTP Invalid Requests, which decreased
during those period, can be explained with seven-state model. Our findings
shows the apparent inability for the users in the internet accesses as a result
of EU regulations on the generative-AI.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.06443v1">Exposing Privacy Gaps: Membership Inference Attack on Preference Data
  for LLM Alignment</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-07-08T22:53:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qizhang Feng, Siva Rajesh Kasa, Hyokun Yun, Choon Hui Teo, Sravan Babu Bodapati</p>
    <p><b>Summary:</b> Large Language Models (LLMs) have seen widespread adoption due to their
remarkable natural language capabilities. However, when deploying them in
real-world settings, it is important to align LLMs to generate texts according
to acceptable human standards. Methods such as Proximal Policy Optimization
(PPO) and Direct Preference Optimization (DPO) have made significant progress
in refining LLMs using human preference data. However, the privacy concerns
inherent in utilizing such preference data have yet to be adequately studied.
In this paper, we investigate the vulnerability of LLMs aligned using human
preference datasets to membership inference attacks (MIAs), highlighting the
shortcomings of previous MIA approaches with respect to preference data. Our
study has two main contributions: first, we introduce a novel reference-based
attack framework specifically for analyzing preference data called PREMIA
(\uline{Pre}ference data \uline{MIA}); second, we provide empirical evidence
that DPO models are more vulnerable to MIA compared to PPO models. Our findings
highlight gaps in current privacy-preserving practices for LLM alignment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.05450v1">Understanding Professional Needs to Create Privacy-Preserving and Secure
  Emergent Digital Artworks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-07-07T17:21:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kathryn Lichlyter, Urvashi Kishnani, Kate Hollenbach, Sanchari Das</p>
    <p><b>Summary:</b> In recent years, immersive art installations featuring interactive artworks
have been on the rise. These installations are an integral part of museums and
art centers like selfie museums, teamLab Borderless, ARTECHOUSE, and Meow Wolf.
Moreover, immersive art have also been increasingly incorporated into
traditional museums as well. However, immersive art requires active user
participation and often captures information from viewers and participants
through cameras, sensors, microphones, embodied interaction devices,
surveillance, and kinetic mirrors. Therefore, we propose a new line of research
to examine the security and privacy postures of immersive artworks. In our
pilot study, we conducted a semi-structured interview with five experienced
practitioners from either the art (2) or cybersecurity (3) fields. Our aim was
to understand their current security and privacy practices, along with their
needs when it comes to immersive art. From their responses, we created a list
of security and privacy parameters, such as, providing opt-in mechanics for
data collection, knowledge of data collection tools such as proximity sensors,
and creating security awareness amongst participants by communicating security
protocols and threat models. These parameters allow us to build
privacy-preserving, secure, and accessible software for individuals working in
media arts, who often have no background on security and privacy. In the
future, we plan to utilize these parameters to develop software in response to
those needs and then host an art exhibition of immersive artworks utilizing the
platform.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.05446v1">Towards Perceived Security, Perceived Privacy, and the Universal Design
  of E-Payment Applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-07T17:15:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Urvashi Kishnani, Isabella Cardenas, Jailene Castillo, Rosalyn Conry, Lukas Rodwin, Rika Ruiz, Matthew Walther, Sanchari Das</p>
    <p><b>Summary:</b> With the growth of digital monetary transactions and cashless payments,
encouraged by the COVID-19 pandemic, use of e-payment applications is on the
rise. It is thus imperative to understand and evaluate the current posture of
e-payment applications from three major user-facing angles: security, privacy,
and usability. To this, we created a high-fidelity prototype of an e-payment
application that encompassed features that we wanted to test with users. We
then conducted a pilot study where we recruited 12 participants who tested our
prototype. We find that both security and privacy are important for users of
e-payment applications. Additionally, some participants perceive the strength
of security and privacy based on the usability of the application. We provide
recommendations such as universal design of e-payment applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.05237v1">Privacy of the last iterate in cyclically-sampled DP-SGD on nonconvex
  composite losses</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E">   
  <p><b>Published on:</b> 2024-07-07T02:35:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Weiwei Kong, Mónica Ribero</p>
    <p><b>Summary:</b> Differentially private stochastic gradient descent (DP-SGD) refers to a
family of optimization algorithms that provide a guaranteed level of
differential privacy (DP) through DP accounting techniques. However, current
accounting techniques make assumptions that diverge significantly from
practical DP-SGD implementations. For example, they may assume the loss
function is Lipschitz continuous and convex, sample the batches randomly with
replacement, or omit the gradient clipping step.
  In this work, we analyze the most commonly used variant of DP-SGD, in which
we sample batches cyclically with replacement, perform gradient clipping, and
only release the last DP-SGD iterate. More specifically - without assuming
convexity, smoothness, or Lipschitz continuity of the loss function - we
establish new R\'enyi differential privacy (RDP) bounds for the last DP-SGD
iterate under the mild assumption that (i) the DP-SGD stepsize is small
relative to the topological constants in the loss function, and (ii) the loss
function is weakly-convex. Moreover, we show that our bounds converge to
previously established convex bounds when the weak-convexity parameter of the
objective function approaches zero. In the case of non-Lipschitz smooth loss
functions, we provide a weaker bound that scales well in terms of the number of
DP-SGD iterations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.05045v1">Robust Skin Color Driven Privacy Preserving Face Recognition via
  Function Secret Sharing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-07-06T10:51:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dong Han, Yufan Jiang, Yong Li, Ricardo Mendes, Joachim Denzler</p>
    <p><b>Summary:</b> In this work, we leverage the pure skin color patch from the face image as
the additional information to train an auxiliary skin color feature extractor
and face recognition model in parallel to improve performance of
state-of-the-art (SOTA) privacy-preserving face recognition (PPFR) systems. Our
solution is robust against black-box attacking and well-established generative
adversarial network (GAN) based image restoration. We analyze the potential
risk in previous work, where the proposed cosine similarity computation might
directly leak the protected precomputed embedding stored on the server side. We
propose a Function Secret Sharing (FSS) based face embedding comparison
protocol without any intermediate result leakage. In addition, we show in
experiments that the proposed protocol is more efficient compared to the Secret
Sharing (SS) based protocol.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.04952v1">Granular Privacy Control for Geolocation with Vision Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-07-06T04:06:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ethan Mendes, Yang Chen, James Hays, Sauvik Das, Wei Xu, Alan Ritter</p>
    <p><b>Summary:</b> Vision Language Models (VLMs) are rapidly advancing in their capability to
answer information-seeking questions. As these models are widely deployed in
consumer applications, they could lead to new privacy risks due to emergent
abilities to identify people in photos, geolocate images, etc. As we
demonstrate, somewhat surprisingly, current open-source and proprietary VLMs
are very capable image geolocators, making widespread geolocation with VLMs an
immediate privacy risk, rather than merely a theoretical future concern. As a
first step to address this challenge, we develop a new benchmark, GPTGeoChat,
to test the ability of VLMs to moderate geolocation dialogues with users. We
collect a set of 1,000 image geolocation conversations between in-house
annotators and GPT-4v, which are annotated with the granularity of location
information revealed at each turn. Using this new dataset, we evaluate the
ability of various VLMs to moderate GPT-4v geolocation conversations by
determining when too much location information has been revealed. We find that
custom fine-tuned models perform on par with prompted API-based models when
identifying leaked location information at the country or city level; however,
fine-tuning on supervised data appears to be needed to accurately moderate
finer granularities, such as the name of a restaurant or building.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.04906v1">Privacy or Transparency? Negotiated Smartphone Access as a Signifier of
  Trust in Romantic Relationships</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-06T00:52:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Periwinkle Doerfler, Kieron Ivy Turk, Chris Geeng, Damon McCoy, Jeffrey Ackerman, Molly Dragiewicz</p>
    <p><b>Summary:</b> In this work, we analyze two large-scale surveys to examine how individuals
think about sharing smartphone access with romantic partners as a function of
trust in relationships. We find that the majority of couples have access to
each others' devices, but may have explicit or implicit boundaries on how this
access is to be used. Investigating these boundaries and related social norms,
we find that there is little consensus about the level of smartphone access
(i.e., transparency), or lack thereof (i.e., privacy) that is desirable in
romantic contexts. However, there is broad agreement that the level of access
should be mutual and consensual. Most individuals understand trust to be the
basis of their decisions about transparency and privacy. Furthermore, we find
individuals have crossed these boundaries, violating their partners' privacy
and betraying their trust. We examine how, when, why, and by whom these
betrayals occur. We consider the ramifications of these boundary violations in
the case of intimate partner violence. Finally, we provide recommendations for
design changes to enable technological enforcement of boundaries currently
enforced by trust, bringing access control in line with users' sharing
preferences.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.04776v1">Quantifying Privacy Risks of Public Statistics to Residents of
  Subsidized Housing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-07-05T18:00:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ryan Steed, Diana Qing, Zhiwei Steven Wu</p>
    <p><b>Summary:</b> As the U.S. Census Bureau implements its controversial new disclosure
avoidance system, researchers and policymakers debate the necessity of new
privacy protections for public statistics. With experiments on both published
statistics and synthetic data, we explore a particular privacy concern:
respondents in subsidized housing may deliberately not mention unauthorized
children and other household members for fear of being evicted. By combining
public statistics from the Decennial Census and the Department of Housing and
Urban Development, we demonstrate a simple, inexpensive reconstruction attack
that could identify subsidized households living in violation of occupancy
guidelines in 2010. Experiments on synthetic data suggest that a random
swapping mechanism similar to the Census Bureau's 2010 disclosure avoidance
measures does not significantly reduce the precision of this attack, while a
differentially private mechanism similar to the 2020 disclosure avoidance
system does. Our results provide a valuable example for policymakers seeking a
trustworthy, accurate census.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.04751v2">A Unified Learn-to-Distort-Data Framework for Privacy-Utility Trade-off
  in Trustworthy Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-05T08:15:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaojin Zhang, Mingcong Xu, Wei Chen</p>
    <p><b>Summary:</b> In this paper, we first give an introduction to the theoretical basis of the
privacy-utility equilibrium in federated learning based on Bayesian privacy
definitions and total variation distance privacy definitions. We then present
the \textit{Learn-to-Distort-Data} framework, which provides a principled
approach to navigate the privacy-utility equilibrium by explicitly modeling the
distortion introduced by the privacy-preserving mechanism as a learnable
variable and optimizing it jointly with the model parameters. We demonstrate
the applicability of our framework to a variety of privacy-preserving
mechanisms on the basis of data distortion and highlight its connections to
related areas such as adversarial training, input robustness, and unlearnable
examples. These connections enable leveraging techniques from these areas to
design effective algorithms for privacy-utility equilibrium in federated
learning under the \textit{Learn-to-Distort-Data} framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.03732v1">Collection, usage and privacy of mobility data in the enterprise and
  public administrations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-04T08:29:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alexandra Kapp</p>
    <p><b>Summary:</b> Human mobility data is a crucial resource for urban mobility management, but
it does not come without personal reference. The implementation of security
measures such as anonymization is thus needed to protect individuals' privacy.
Often, a trade-off arises as such techniques potentially decrease the utility
of the data and limit its use. While much research on anonymization techniques
exists, there is little information on the actual implementations by
practitioners, especially outside the big tech context. Within our study, we
conducted expert interviews to gain insights into practices in the field. We
categorize purposes, data sources, analysis, and modeling tasks to provide a
profound understanding of the context such data is used in. We survey
privacy-enhancing methods in use, which generally do not comply with
state-of-the-art standards of differential privacy. We provide groundwork for
further research on practice-oriented research by identifying privacy needs of
practitioners and extracting relevant mobility characteristics for future
standardized evaluations of privacy-enhancing methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.03496v1">Releasing Large-Scale Human Mobility Histograms with Differential
  Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2024-07-03T20:54:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Christopher Bian, Albert Cheu, Yannis Guzman, Marco Gruteser, Peter Kairouz, Ryan McKenna, Edo Roth</p>
    <p><b>Summary:</b> Environmental Insights Explorer (EIE) is a Google product that reports
aggregate statistics about human mobility, including various methods of transit
used by people across roughly 50,000 regions globally. These statistics are
used to estimate carbon emissions and provided to policymakers to inform their
decisions on transportation policy and infrastructure. Due to the inherent
sensitivity of this type of user data, it is crucial that the statistics
derived and released from it are computed with appropriate privacy protections.
In this work, we use a combination of federated analytics and differential
privacy to release these required statistics, while operating under strict
error constraints to ensure utility for downstream stakeholders. In this work,
we propose a new mechanism that achieves $ \epsilon \approx 2 $-DP while
satisfying these strict utility constraints, greatly improving over natural
baselines. We believe this mechanism may be of more general interest for the
broad class of group-by-sum workloads.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.03470v1">Prosody-Driven Privacy-Preserving Dementia Detection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2024-07-03T19:34:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dominika Woszczyk, Ranya Aloufi, Soteris Demetriou</p>
    <p><b>Summary:</b> Speaker embeddings extracted from voice recordings have been proven valuable
for dementia detection. However, by their nature, these embeddings contain
identifiable information which raises privacy concerns. In this work, we aim to
anonymize embeddings while preserving the diagnostic utility for dementia
detection. Previous studies rely on adversarial learning and models trained on
the target attribute and struggle in limited-resource settings. We propose a
novel approach that leverages domain knowledge to disentangle prosody features
relevant to dementia from speaker embeddings without relying on a dementia
classifier. Our experiments show the effectiveness of our approach in
preserving speaker privacy (speaker recognition F1-score .01%) while
maintaining high dementia detection score F1-score of 74% on the ADReSS
dataset. Our results are also on par with a more constrained
classifier-dependent system on ADReSSo (.01% and .66%), and have no impact on
synthesized speech naturalness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.03451v1">The Role of Privacy Guarantees in Voluntary Donation of Private Data for
  Altruistic Goals</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-07-03T18:50:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruizhe Wang, Roberta De Viti, Aarushi Dubey, Elissa M. Redmiles</p>
    <p><b>Summary:</b> Voluntary donation of private information for altruistic purposes, such as
advancing research, is common. However, concerns about data misuse and leakage
may deter individuals from donating their information. While prior research has
indicated that Privacy Enhancement Technologies (PETs) can alleviate these
concerns, the extent to which these techniques influence willingness to donate
data remains unclear.
  This study conducts a vignette survey (N=485) to examine people's willingness
to donate medical data for developing new treatments under four privacy
guarantees: data expiration, anonymization, use restriction, and access
control. The study explores two mechanisms for verifying these guarantees:
self-auditing and expert auditing, and evaluates the impact on two types of
data recipient entities: for-profit and non-profit institutions.
  Our findings reveal that the type of entity collecting data strongly
influences respondents' privacy expectations, which in part influence their
willingness to donate data. Respondents have such high expectations of the
privacy provided by non-profit entities that explicitly stating the privacy
protections provided makes little adjustment to those expectations. In
contrast, statements about privacy bring respondents' expectations of the
privacy provided by for-profit entities nearly in-line with non-profit
expectations. We highlight the risks of these respective results as well as the
need for future research to better align technical community and end-user
perceptions about the effectiveness of auditing PETs and to effectively set
expectations about the efficacy of PETs in the face of end-user concerns about
data breaches.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.03289v1">Correlated Privacy Mechanisms for Differentially Private Distributed
  Mean Estimation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2024-07-03T17:22:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sajani Vithana, Viveck R. Cadambe, Flavio P. Calmon, Haewon Jeong</p>
    <p><b>Summary:</b> Differentially private distributed mean estimation (DP-DME) is a fundamental
building block in privacy-preserving federated learning, where a central server
estimates the mean of $d$-dimensional vectors held by $n$ users while ensuring
$(\epsilon,\delta)$-DP. Local differential privacy (LDP) and distributed DP
with secure aggregation (SecAgg) are the most common notions of DP used in
DP-DME settings with an untrusted server. LDP provides strong resilience to
dropouts, colluding users, and malicious server attacks, but suffers from poor
utility. In contrast, SecAgg-based DP-DME achieves an $O(n)$ utility gain over
LDP in DME, but requires increased communication and computation overheads and
complex multi-round protocols to handle dropouts and malicious attacks. In this
work, we propose CorDP-DME, a novel DP-DME mechanism that spans the gap between
DME with LDP and distributed DP, offering a favorable balance between utility
and resilience to dropout and collusion. CorDP-DME is based on correlated
Gaussian noise, ensuring DP without the perfect conditional privacy guarantees
of SecAgg-based approaches. We provide an information-theoretic analysis of
CorDP-DME, and derive theoretical guarantees for utility under any given
privacy parameters and dropout/colluding user thresholds. Our results
demonstrate that (anti) correlated Gaussian DP mechanisms can significantly
improve utility in mean estimation tasks compared to LDP -- even in adversarial
settings -- while maintaining better resilience to dropouts and attacks
compared to distributed DP.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.02956v1">IncogniText: Privacy-enhancing Conditional Text Anonymization via
  LLM-based Private Attribute Randomization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-07-03T09:49:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ahmed Frikha, Nassim Walha, Krishna Kanth Nakka, Ricardo Mendes, Xue Jiang, Xuebing Zhou</p>
    <p><b>Summary:</b> In this work, we address the problem of text anonymization where the goal is
to prevent adversaries from correctly inferring private attributes of the
author, while keeping the text utility, i.e., meaning and semantics. We propose
IncogniText, a technique that anonymizes the text to mislead a potential
adversary into predicting a wrong private attribute value. Our empirical
evaluation shows a reduction of private attribute leakage by more than 90%.
Finally, we demonstrate the maturity of IncogniText for real-world applications
by distilling its anonymization capability into a set of LoRA parameters
associated with an on-device model.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.02766v1">Balancing Patient Privacy and Health Data Security: The Role of
  Compliance in Protected Health Information (PHI) Sharing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-03T02:49:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Md Al Amin, Hemanth Tummala, Rushabh Shah, Indrajit Ray</p>
    <p><b>Summary:</b> Protected Health Information (PHI) sharing significantly enhances patient
care quality and coordination, contributing to more accurate diagnoses,
efficient treatment plans, and a comprehensive understanding of patient
history. Compliance with strict privacy and security policies, such as those
required by laws like HIPAA, is critical to protect PHI. Blockchain technology,
which offers a decentralized and tamper-evident ledger system, hold promise in
policy compliance. This system ensures the authenticity and integrity of PHI
while facilitating patient consent management. In this work, we propose a
blockchain technology that integrates smart contracts to partially automate
consent-related processes and ensuring that PHI access and sharing follow
patient preferences and legal requirements.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.02747v1">Curvature Clues: Decoding Deep Learning Privacy with Input Loss
  Curvature</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-03T01:47:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Deepak Ravikumar, Efstathia Soufleri, Kaushik Roy</p>
    <p><b>Summary:</b> In this paper, we explore the properties of loss curvature with respect to
input data in deep neural networks. Curvature of loss with respect to input
(termed input loss curvature) is the trace of the Hessian of the loss with
respect to the input. We investigate how input loss curvature varies between
train and test sets, and its implications for train-test distinguishability. We
develop a theoretical framework that derives an upper bound on the train-test
distinguishability based on privacy and the size of the training set. This
novel insight fuels the development of a new black box membership inference
attack utilizing input loss curvature. We validate our theoretical findings
through experiments in computer vision classification tasks, demonstrating that
input loss curvature surpasses existing methods in membership inference
effectiveness. Our analysis highlights how the performance of membership
inference attack (MIA) methods varies with the size of the training set,
showing that curvature-based MIA outperforms other methods on sufficiently
large datasets. This condition is often met by real datasets, as demonstrated
by our results on CIFAR10, CIFAR100, and ImageNet. These findings not only
advance our understanding of deep neural network behavior but also improve the
ability to test privacy-preserving techniques in machine learning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.02268v1">Footprints of Data in a Classifier Model: The Privacy Issues and Their
  Mitigation through Data Obfuscation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-07-02T13:56:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Payel Sadhukhan, Tanujit Chakraborty</p>
    <p><b>Summary:</b> The avalanche of AI deployment and its security-privacy concerns are two
sides of the same coin. Article 17 of GDPR calls for the Right to Erasure; data
has to be obliterated from a system to prevent its compromise. Extant research
in this aspect focuses on effacing sensitive data attributes. However, several
passive modes of data compromise are yet to be recognized and redressed. The
embedding of footprints of training data in a prediction model is one such
facet; the difference in performance quality in test and training data causes
passive identification of data that have trained the model. This research
focuses on addressing the vulnerability arising from the data footprints. The
three main aspects are -- i] exploring the vulnerabilities of different
classifiers (to segregate the vulnerable and the non-vulnerable ones), ii]
reducing the vulnerability of vulnerable classifiers (through data obfuscation)
to preserve model and data privacy, and iii] exploring the privacy-performance
tradeoff to study the usability of the data obfuscation techniques. An
empirical study is conducted on three datasets and eight classifiers to explore
the above objectives. The results of the initial research identify the
vulnerability in classifiers and segregate the vulnerable and non-vulnerable
classifiers. The additional experiments on data obfuscation techniques reveal
their utility to render data and model privacy and also their capability to
chalk out a privacy-performance tradeoff in most scenarios. The results can aid
the practitioners with their choice of classifiers in different scenarios and
contexts.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.02226v1">RollupTheCrowd: Leveraging ZkRollups for a Scalable and
  Privacy-Preserving Reputation-based Crowdsourcing Platform</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-07-02T12:51:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ahmed Mounsf Rafik Bendada, Mouhamed Amine Bouchiha, Mourad Rabah, Yacine Ghamri-Doudane</p>
    <p><b>Summary:</b> Current blockchain-based reputation solutions for crowdsourcing fail to
tackle the challenge of ensuring both efficiency and privacy without
compromising the scalability of the blockchain. Developing an effective,
transparent, and privacy-preserving reputation model necessitates on-chain
implementation using smart contracts. However, managing task evaluation and
reputation updates alongside crowdsourcing transactions on-chain substantially
strains system scalability and performance. This paper introduces
RollupTheCrowd, a novel blockchain-powered crowdsourcing framework that
leverages zkRollups to enhance system scalability while protecting user
privacy. Our framework includes an effective and privacy-preserving reputation
model that gauges workers' trustworthiness by assessing their crowdsourcing
interactions. To alleviate the load on our blockchain, we employ an off-chain
storage scheme, optimizing RollupTheCrowd's performance. Utilizing smart
contracts and zero-knowledge proofs, our Rollup layer achieves a significant
20x reduction in gas consumption. To prove the feasibility of the proposed
framework, we developed a proof-of-concept implementation using cutting-edge
tools. The experimental results presented in this paper demonstrate the
effectiveness and scalability of RollupTheCrowd, validating its potential for
real-world application scenarios.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.02191v1">Attack-Aware Noise Calibration for Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">  
  <p><b>Published on:</b> 2024-07-02T11:49:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bogdan Kulynych, Juan Felipe Gomez, Georgios Kaissis, Flavio du Pin Calmon, Carmela Troncoso</p>
    <p><b>Summary:</b> Differential privacy (DP) is a widely used approach for mitigating privacy
risks when training machine learning models on sensitive data. DP mechanisms
add noise during training to limit the risk of information leakage. The scale
of the added noise is critical, as it determines the trade-off between privacy
and utility. The standard practice is to select the noise scale in terms of a
privacy budget parameter $\epsilon$. This parameter is in turn interpreted in
terms of operational attack risk, such as accuracy, or sensitivity and
specificity of inference attacks against the privacy of the data. We
demonstrate that this two-step procedure of first calibrating the noise scale
to a privacy budget $\epsilon$, and then translating $\epsilon$ to attack risk
leads to overly conservative risk assessments and unnecessarily low utility. We
propose methods to directly calibrate the noise scale to a desired attack risk
level, bypassing the intermediate step of choosing $\epsilon$. For a target
attack risk, our approach significantly decreases noise scale, leading to
increased utility at the same level of privacy. We empirically demonstrate that
calibrating noise to attack sensitivity/specificity, rather than $\epsilon$,
when training privacy-preserving ML models substantially improves model
accuracy for the same risk level. Our work provides a principled and practical
way to improve the utility of privacy-preserving ML without compromising on
privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.02027v1">Privacy Risks of General-Purpose AI Systems: A Foundation for
  Investigating Practitioner Perspectives</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-07-02T07:49:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stephen Meisenbacher, Alexandra Klymenko, Patrick Gage Kelley, Sai Teja Peddinti, Kurt Thomas, Florian Matthes</p>
    <p><b>Summary:</b> The rise of powerful AI models, more formally $\textit{General-Purpose AI
Systems}$ (GPAIS), has led to impressive leaps in performance across a wide
range of tasks. At the same time, researchers and practitioners alike have
raised a number of privacy concerns, resulting in a wealth of literature
covering various privacy risks and vulnerabilities of AI models. Works
surveying such risks provide differing focuses, leading to disparate sets of
privacy risks with no clear unifying taxonomy. We conduct a systematic review
of these survey papers to provide a concise and usable overview of privacy
risks in GPAIS, as well as proposed mitigation strategies. The developed
privacy framework strives to unify the identified privacy risks and mitigations
at a technical level that is accessible to non-experts. This serves as the
basis for a practitioner-focused interview study to assess technical
stakeholder perceptions of privacy risks and mitigations in GPAIS.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.01817v1">Race and Privacy in Broadcast Police Communications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-07-01T21:34:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pranav Narayanan Venkit, Christopher Graziul, Miranda Ardith Goodman, Samantha Nicole Kenny, Shomir Wilson</p>
    <p><b>Summary:</b> Radios are essential for the operations of modern police departments, and
they function as both a collaborative communication technology and a
sociotechnical system. However, little prior research has examined their usage
or their connections to individual privacy and the role of race in policing,
two growing topics of concern in the US. As a case study, we examine the
Chicago Police Department's (CPD's) use of broadcast police communications
(BPC) to coordinate the activity of law enforcement officers (LEOs) in the
city. From a recently assembled archive of 80,775 hours of BPC associated with
CPD operations, we analyze text transcripts of radio transmissions broadcast
9:00 AM to 5:00 PM on August 10th, 2018 in one majority Black, one majority
white, and one majority Hispanic area of the city (24 hours of audio) to
explore three research questions: (1) Do BPC reflect reported racial
disparities in policing? (2) How and when is gender, race/ethnicity, and age
mentioned in BPC? (3) To what extent do BPC include sensitive information, and
who is put at most risk by this practice? (4) To what extent can large language
models (LLMs) heighten this risk? We explore the vocabulary and speech acts
used by police in BPC, comparing mentions of personal characteristics to local
demographics, the personal information shared over BPC, and the privacy
concerns that it poses. Analysis indicates (a) policing professionals in the
city of Chicago exhibit disproportionate attention to Black members of the
public regardless of context, (b) sociodemographic characteristics like gender,
race/ethnicity, and age are primarily mentioned in BPC about event information,
and (c) disproportionate attention introduces disproportionate privacy risks
for Black members of the public.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.01334v2">Protecting Privacy in Classifiers by Token Manipulation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-07-01T14:41:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Re'em Harel, Yair Elboher, Yuval Pinter</p>
    <p><b>Summary:</b> Using language models as a remote service entails sending private information
to an untrusted provider. In addition, potential eavesdroppers can intercept
the messages, thereby exposing the information. In this work, we explore the
prospects of avoiding such data exposure at the level of text manipulation. We
focus on text classification models, examining various token mapping and
contextualized manipulation functions in order to see whether classifier
accuracy may be maintained while keeping the original text unrecoverable. We
find that although some token mapping functions are easy and straightforward to
implement, they heavily influence performance on the downstream task, and via a
sophisticated attacker can be reconstructed. In comparison, the contextualized
manipulation provides an improvement in performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.01167v1">Information Density Bounds for Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-07-01T10:38:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sara Saeidian, Leonhard Grosse, Parastoo Sadeghi, Mikael Skoglund, Tobias J. Oechtering</p>
    <p><b>Summary:</b> This paper explores the implications of guaranteeing privacy by imposing a
lower bound on the information density between the private and the public data.
We introduce an operationally meaningful privacy measure called pointwise
maximal cost (PMC) and demonstrate that imposing an upper bound on PMC is
equivalent to enforcing a lower bound on the information density. PMC
quantifies the information leakage about a secret to adversaries who aim to
minimize non-negative cost functions after observing the outcome of a privacy
mechanism. When restricted to finite alphabets, PMC can equivalently be defined
as the information leakage to adversaries aiming to minimize the probability of
incorrectly guessing randomized functions of the secret. We study the
properties of PMC and apply it to standard privacy mechanisms to demonstrate
its practical relevance. Through a detailed examination, we connect PMC with
other privacy measures that impose upper or lower bounds on the information
density. Our results highlight that lower bounding the information density is a
more stringent requirement than upper bounding it. Overall, our work
significantly bridges the gaps in understanding the relationships between
various privacy frameworks and provides insights for selecting a suitable
framework for a given application.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.00991v1">Pre-capture Privacy via Adaptive Single-Pixel Imaging</a></h3>
  
  <p><b>Published on:</b> 2024-07-01T06:05:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yoko Sogabe, Shiori Sugimoto, Ayumi Matsumoto, Masaki Kitahara</p>
    <p><b>Summary:</b> As cameras become ubiquitous in our living environment, invasion of privacy
is becoming a growing concern. A common approach to privacy preservation is to
remove personally identifiable information from a captured image, but there is
a risk of the original image being leaked. In this paper, we propose a
pre-capture privacy-aware imaging method that captures images from which the
details of a pre-specified anonymized target have been eliminated. The proposed
method applies a single-pixel imaging framework in which we introduce a
feedback mechanism called an aperture pattern generator. The introduced
aperture pattern generator adaptively outputs the next aperture pattern to
avoid sampling the anonymized target by exploiting the data already acquired as
a clue. Furthermore, the anonymized target can be set to any object without
changing hardware. Except for detailed features which have been removed from
the anonymized target, the captured images are of comparable quality to those
captured by a general camera and can be used for various computer vision
applications. In our work, we target faces and license plates and
experimentally show that the proposed method can capture clear images in which
detailed features of the anonymized target are eliminated to achieve both
privacy and utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.00873v1">Privacy-First Crowdsourcing: Blockchain and Local Differential Privacy
  in Crowdsourced Drone Services</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-07-01T00:46:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Junaid Akram, Ali Anaissi</p>
    <p><b>Summary:</b> We introduce a privacy-preserving framework for integrating consumer-grade
drones into bushfire management. This system creates a marketplace where
bushfire management authorities obtain essential data from drone operators. Key
features include local differential privacy to protect data providers and a
blockchain-based solution ensuring fair data exchanges and accountability. The
framework is validated through a proof-of-concept implementation, demonstrating
its scalability and potential for various large-scale data collection
scenarios. This approach addresses privacy concerns and compliance with
regulations like Australia's Privacy Act 1988, offering a practical solution
for enhancing bushfire detection and management through crowdsourced drone
services.</p>
  </details>
</div>



<h2>2024-06</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.00764v1">Characterizing Stereotypical Bias from Privacy-preserving Pre-Training</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-06-30T16:54:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stefan Arnold, Rene Gröbner, Annika Schreiner</p>
    <p><b>Summary:</b> Differential Privacy (DP) can be applied to raw text by exploiting the
spatial arrangement of words in an embedding space. We investigate the
implications of such text privatization on Language Models (LMs) and their
tendency towards stereotypical associations. Since previous studies documented
that linguistic proficiency correlates with stereotypical bias, one could
assume that techniques for text privatization, which are known to degrade
language modeling capabilities, would cancel out undesirable biases. By testing
BERT models trained on texts containing biased statements primed with varying
degrees of privacy, our study reveals that while stereotypical bias generally
diminishes when privacy is tightened, text privatization does not uniformly
equate to diminishing bias across all social domains. This highlights the need
for careful diagnosis of bias in LMs that undergo text privatization.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.00638v1">A Collocation-based Method for Addressing Challenges in Word-level
  Metric Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-06-30T09:37:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stephen Meisenbacher, Maulik Chevli, Florian Matthes</p>
    <p><b>Summary:</b> Applications of Differential Privacy (DP) in NLP must distinguish between the
syntactic level on which a proposed mechanism operates, often taking the form
of $\textit{word-level}$ or $\textit{document-level}$ privatization. Recently,
several word-level $\textit{Metric}$ Differential Privacy approaches have been
proposed, which rely on this generalized DP notion for operating in word
embedding spaces. These approaches, however, often fail to produce semantically
coherent textual outputs, and their application at the sentence- or
document-level is only possible by a basic composition of word perturbations.
In this work, we strive to address these challenges by operating
$\textit{between}$ the word and sentence levels, namely with
$\textit{collocations}$. By perturbing n-grams rather than single words, we
devise a method where composed privatized outputs have higher semantic
coherence and variable length. This is accomplished by constructing an
embedding model based on frequently occurring word groups, in which unigram
words co-exist with bi- and trigram collocations. We evaluate our method in
utility and privacy tests, which make a clear case for tokenization strategies
beyond the word level.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.00538v1">Privacy-Preserving and Trustworthy Deep Learning for Medical Imaging</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> 
  <p><b>Published on:</b> 2024-06-29T22:26:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kiarash Sedghighadikolaei, Attila A Yavuz</p>
    <p><b>Summary:</b> The shift towards efficient and automated data analysis through Machine
Learning (ML) has notably impacted healthcare systems, particularly Radiomics.
Radiomics leverages ML to analyze medical images accurately and efficiently for
precision medicine. Current methods rely on Deep Learning (DL) to improve
performance and accuracy (Deep Radiomics). Given the sensitivity of medical
images, ensuring privacy throughout the Deep Radiomics pipeline-from data
generation and collection to model training and inference-is essential,
especially when outsourced. Thus, Privacy-Enhancing Technologies (PETs) are
crucial tools for Deep Radiomics. Previous studies and systematization efforts
have either broadly overviewed PETs and their applications or mainly focused on
subsets of PETs for ML algorithms. In Deep Radiomics, where efficiency,
accuracy, and privacy are crucial, many PETs, while theoretically applicable,
may not be practical without specialized optimizations or hybrid designs.
Additionally, not all DL models are suitable for Radiomics. Consequently, there
is a need for specialized studies that investigate and systematize the
effective and practical integration of PETs into the Deep Radiomics pipeline.
This work addresses this research gap by (1) classifying existing PETs,
presenting practical hybrid PETS constructions, and a taxonomy illustrating
their potential integration with the Deep Radiomics pipeline, with comparative
analyses detailing assumptions, architectural suitability, and security, (2)
Offering technical insights, describing potential challenges and means of
combining PETs into the Deep Radiomics pipeline, including integration
strategies, subtilities, and potential challenges, (3) Proposing potential
research directions, identifying challenges, and suggesting solutions to
enhance the PETs in Deep Radiomics.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.00417v1">Obtaining $(ε,δ)$-differential privacy guarantees when using
  a Poisson mechanism to synthesize contingency tables</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-06-29T11:57:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> James Jackson, Robin Mitra, Brian Francis, Iain Dove</p>
    <p><b>Summary:</b> We show that differential privacy type guarantees can be obtained when using
a Poisson synthesis mechanism to protect counts in contingency tables.
Specifically, we show how to obtain $(\epsilon, \delta)$-probabilistic
differential privacy guarantees via the Poisson distribution's cumulative
distribution function. We demonstrate this empirically with the synthesis of an
administrative-type confidential database.</p>
  </details>
</div>

