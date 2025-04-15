
<h2>2025-04</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.10456v1">Privacy-Preserving Distributed Link Predictions Among Peers in Online
  Classrooms Using Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B">
  <p><b>Published on:</b> 2025-04-14T17:43:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anurata Prabha Hridi, Muntasir Hoq, Zhikai Gao, Collin Lynch, Rajeev Sahay, Seyyedali Hosseinalipour, Bita Akram</p>
    <p><b>Summary:</b> Social interactions among classroom peers, represented as social learning
networks (SLNs), play a crucial role in enhancing learning outcomes. While SLN
analysis has recently garnered attention, most existing approaches rely on
centralized training, where data is aggregated and processed on a local/cloud
server with direct access to raw data. However, in real-world educational
settings, such direct access across multiple classrooms is often restricted due
to privacy concerns. Furthermore, training models on isolated classroom data
prevents the identification of common interaction patterns that exist across
multiple classrooms, thereby limiting model performance. To address these
challenges, we propose one of the first frameworks that integrates Federated
Learning (FL), a distributed and collaborative machine learning (ML) paradigm,
with SLNs derived from students' interactions in multiple classrooms' online
forums to predict future link formations (i.e., interactions) among students.
By leveraging FL, our approach enables collaborative model training across
multiple classrooms while preserving data privacy, as it eliminates the need
for raw data centralization. Recognizing that each classroom may exhibit unique
student interaction dynamics, we further employ model personalization
techniques to adapt the FL model to individual classroom characteristics. Our
results demonstrate the effectiveness of our approach in capturing both shared
and classroom-specific representations of student interactions in SLNs.
Additionally, we utilize explainable AI (XAI) techniques to interpret model
predictions, identifying key factors that influence link formation across
different classrooms. These insights unveil the drivers of social learning
interactions within a privacy-preserving, collaborative, and distributed ML
framework -- an aspect that has not been explored before.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.10267v1">Trade-offs in Privacy-Preserving Eye Tracking through Iris Obfuscation:
  A Benchmarking Study</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-04-14T14:29:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mengdi Wang, Efe Bozkir, Enkelejda Kasneci</p>
    <p><b>Summary:</b> Recent developments in hardware, computer graphics, and AI may soon enable
AR/VR head-mounted displays (HMDs) to become everyday devices like smartphones
and tablets. Eye trackers within HMDs provide a special opportunity for such
setups as it is possible to facilitate gaze-based research and interaction.
However, estimating users' gaze information often requires raw eye images and
videos that contain iris textures, which are considered a gold standard
biometric for user authentication, and this raises privacy concerns. Previous
research in the eye-tracking community focused on obfuscating iris textures
while keeping utility tasks such as gaze estimation accurate. Despite these
attempts, there is no comprehensive benchmark that evaluates state-of-the-art
approaches. Considering all, in this paper, we benchmark blurring, noising,
downsampling, rubber sheet model, and iris style transfer to obfuscate user
identity, and compare their impact on image quality, privacy, utility, and risk
of imposter attack on two datasets. We use eye segmentation and gaze estimation
as utility tasks, and reduction in iris recognition accuracy as a measure of
privacy protection, and false acceptance rate to estimate risk of attack. Our
experiments show that canonical image processing methods like blurring and
noising cause a marginal impact on deep learning-based tasks. While
downsampling, rubber sheet model, and iris style transfer are effective in
hiding user identifiers, iris style transfer, with higher computation cost,
outperforms others in both utility tasks, and is more resilient against spoof
attacks. Our analyses indicate that there is no universal optimal approach to
balance privacy, utility, and computation burden. Therefore, we recommend
practitioners consider the strengths and weaknesses of each approach, and
possible combinations of those to reach an optimal privacy-utility trade-off.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.10016v1">Quantifying Privacy Leakage in Split Inference via Fisher-Approximated
  Shannon Information Analysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-04-14T09:19:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruijun Deng, Zhihui Lu, Qiang Duan</p>
    <p><b>Summary:</b> Split inference (SI) partitions deep neural networks into distributed
sub-models, enabling privacy-preserving collaborative learning. Nevertheless,
it remains vulnerable to Data Reconstruction Attacks (DRAs), wherein
adversaries exploit exposed smashed data to reconstruct raw inputs. Despite
extensive research on adversarial attack-defense games, a shortfall remains in
the fundamental analysis of privacy risks. This paper establishes a theoretical
framework for privacy leakage quantification using information theory, defining
it as the adversary's certainty and deriving both average-case and worst-case
error bounds. We introduce Fisher-approximated Shannon information (FSInfo), a
novel privacy metric utilizing Fisher Information (FI) for operational privacy
leakage computation. We empirically show that our privacy metric correlates
well with empirical attacks and investigate some of the factors that affect
privacy leakage, namely the data distribution, model size, and overfitting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.09961v1">Privacy Meets Explainability: Managing Confidential Data and
  Transparency Policies in LLM-Empowered Science</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-04-14T07:58:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yashothara Shanmugarasa, Shidong Pan, Ming Ding, Dehai Zhao, Thierry Rakotoarivelo</p>
    <p><b>Summary:</b> As Large Language Models (LLMs) become integral to scientific workflows,
concerns over the confidentiality and ethical handling of confidential data
have emerged. This paper explores data exposure risks through LLM-powered
scientific tools, which can inadvertently leak confidential information,
including intellectual property and proprietary data, from scientists'
perspectives. We propose "DataShield", a framework designed to detect
confidential data leaks, summarize privacy policies, and visualize data flow,
ensuring alignment with organizational policies and procedures. Our approach
aims to inform scientists about data handling practices, enabling them to make
informed decisions and protect sensitive information. Ongoing user studies with
scientists are underway to evaluate the framework's usability, trustworthiness,
and effectiveness in tackling real-world privacy challenges.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.09952v1">Secrecy and Privacy in Multi-Access Combinatorial Topology</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2025-04-14T07:30:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mallikharjuna Chinnapadamala, B. Sundar Rajan</p>
    <p><b>Summary:</b> In this work, we consider the multi-access combinatorial topology with $C$
caches where each user accesses a unique set of $r$ caches. For this setup, we
consider secrecy, where each user should not know anything about the files it
did not request, and demand privacy, where each user's demand must be kept
private from other non-colluding users. We propose a scheme satisfying both
conditions and derive a lower bound based on cut-set arguments. Also, we prove
that our scheme is optimal when $r\geq C-1$, and it is order-optimal when the
cache memory size $M$ is greater than or equal to a certain threshold for
$r<C-1$. When $r=1$, in most of the memory region, our scheme achieves the same
rate as the one given by the secretive scheme for the dedicated cache setup by
Ravindrakumar et al. ( 'Private Coded Caching,' in \textit{IEEE Transactions on
Information Forensics and Security}, 2018), while satisfying both secrecy and
demand privacy conditions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.09517v1">RoboComm: A DID-based scalable and privacy-preserving Robot-to-Robot
  interaction over state channels</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E">
  <p><b>Published on:</b> 2025-04-13T11:10:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Roshan Singh, Sushant Pandey</p>
    <p><b>Summary:</b> In a multi robot system establishing trust amongst untrusted robots from
different organisations while preserving a robot's privacy is a challenge.
Recently decentralized technologies such as smart contract and blockchain are
being explored for applications in robotics. However, the limited transaction
processing and high maintenance cost hinder the widespread adoption of such
approaches. Moreover, blockchain transactions be they on public or private
permissioned blockchain are publically readable which further fails to preserve
the confidentiality of the robot's data and privacy of the robot.
  In this work, we propose RoboComm a Decentralized Identity based approach for
privacy-preserving interaction between robots. With DID a component of
Self-Sovereign Identity; robots can authenticate each other independently
without relying on any third-party service. Verifiable Credentials enable
private data associated with a robot to be stored within the robot's hardware,
unlike existing blockchain based approaches where the data has to be on the
blockchain. We improve throughput by allowing message exchange over state
channels. Being a blockchain backed solution RoboComm provides a trustworthy
system without relying on a single party. Moreover, we implement our proposed
approach to demonstrate the feasibility of our solution.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.09095v1">Privacy Preservation in Gen AI Applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-04-12T06:19:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Swetha S, Ram Sundhar K Shaju, Rakshana M, Ganesh R, Balavedhaa S, Thiruvaazhi U</p>
    <p><b>Summary:</b> The ability of machines to comprehend and produce language that is similar to
that of humans has revolutionized sectors like customer service, healthcare,
and finance thanks to the quick advances in Natural Language Processing (NLP),
which are fueled by Generative Artificial Intelligence (AI) and Large Language
Models (LLMs). However, because LLMs trained on large datasets may
unintentionally absorb and reveal Personally Identifiable Information (PII)
from user interactions, these capabilities also raise serious privacy concerns.
Deep neural networks' intricacy makes it difficult to track down or stop the
inadvertent storing and release of private information, which raises serious
concerns about the privacy and security of AI-driven data. This study tackles
these issues by detecting Generative AI weaknesses through attacks such as data
extraction, model inversion, and membership inference. A privacy-preserving
Generative AI application that is resistant to these assaults is then
developed. It ensures privacy without sacrificing functionality by using
methods to identify, alter, or remove PII before to dealing with LLMs. In order
to determine how well cloud platforms like Microsoft Azure, Google Cloud, and
AWS provide privacy tools for protecting AI applications, the study also
examines these technologies. In the end, this study offers a fundamental
privacy paradigm for generative AI systems, focusing on data security and moral
AI implementation, and opening the door to a more secure and conscientious use
of these tools.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.08616v1">Preserving Privacy Without Compromising Accuracy: Machine Unlearning for
  Handwritten Text Recognition</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-04-11T15:21:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lei Kang, Xuanshuo Fu, Lluis Gomez, Alicia Fornés, Ernest Valveny, Dimosthenis Karatzas</p>
    <p><b>Summary:</b> Handwritten Text Recognition (HTR) is essential for document analysis and
digitization. However, handwritten data often contains user-identifiable
information, such as unique handwriting styles and personal lexicon choices,
which can compromise privacy and erode trust in AI services. Legislation like
the ``right to be forgotten'' underscores the necessity for methods that can
expunge sensitive information from trained models. Machine unlearning addresses
this by selectively removing specific data from models without necessitating
complete retraining. Yet, it frequently encounters a privacy-accuracy tradeoff,
where safeguarding privacy leads to diminished model performance. In this
paper, we introduce a novel two-stage unlearning strategy for a multi-head
transformer-based HTR model, integrating pruning and random labeling. Our
proposed method utilizes a writer classification head both as an indicator and
a trigger for unlearning, while maintaining the efficacy of the recognition
head. To our knowledge, this represents the first comprehensive exploration of
machine unlearning within HTR tasks. We further employ Membership Inference
Attacks (MIA) to evaluate the effectiveness of unlearning user-identifiable
information. Extensive experiments demonstrate that our approach effectively
preserves privacy while maintaining model accuracy, paving the way for new
research directions in the document analysis community. Our code will be
publicly available upon acceptance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.08254v2">Understanding the Impact of Data Domain Extraction on Synthetic Data
  Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-04-11T04:35:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Georgi Ganev, Meenatchi Sundaram Muthu Selva Annamalai, Sofiane Mahiou, Emiliano De Cristofaro</p>
    <p><b>Summary:</b> Privacy attacks, particularly membership inference attacks (MIAs), are widely
used to assess the privacy of generative models for tabular synthetic data,
including those with Differential Privacy (DP) guarantees. These attacks often
exploit outliers, which are especially vulnerable due to their position at the
boundaries of the data domain (e.g., at the minimum and maximum values).
However, the role of data domain extraction in generative models and its impact
on privacy attacks have been overlooked. In this paper, we examine three
strategies for defining the data domain: assuming it is externally provided
(ideally from public data), extracting it directly from the input data, and
extracting it with DP mechanisms. While common in popular implementations and
libraries, we show that the second approach breaks end-to-end DP guarantees and
leaves models vulnerable. While using a provided domain (if representative) is
preferable, extracting it with DP can also defend against popular MIAs, even at
high privacy budgets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.07761v1">Exploring a Patch-Wise Approach for Privacy-Preserving Fake ID Detection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-04-10T14:01:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Javier Muñoz-Haro, Ruben Tolosana, Ruben Vera-Rodriguez, Aythami Morales, Julian Fierrez</p>
    <p><b>Summary:</b> In an increasingly digitalized world, verifying the authenticity of ID
documents has become a critical challenge for real-life applications such as
digital banking, crypto-exchanges, renting, etc. This study focuses on the
topic of fake ID detection, covering several limitations in the field. In
particular, no publicly available data from real ID documents exists, and most
studies rely on proprietary in-house databases that are not available due to
privacy reasons. In order to shed some light on this critical challenge that
makes difficult to advance in the field, we explore a trade-off between privacy
(i.e., amount of sensitive data available) and performance, proposing a novel
patch-wise approach for privacy-preserving fake ID detection. Our proposed
approach explores how privacy can be enhanced through: i) two levels of
anonymization for an ID document (i.e., fully- and pseudo-anonymized), and ii)
different patch size configurations, varying the amount of sensitive data
visible in the patch image. Also, state-of-the-art methods such as Vision
Transformers and Foundation Models are considered in the analysis. The
experimental framework shows that, on an unseen database (DLC-2021), our
proposal achieves 13.91% and 0% EERs at patch and ID document level, showing a
good generalization to other databases. In addition to this exploration,
another key contribution of our study is the release of the first publicly
available database that contains 48,400 patches from both real and fake ID
documents, along with the experimental framework and models, which will be
available in our GitHub.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.07578v1">Privacy-Preserving Vertical K-Means Clustering</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-04-10T09:20:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Federico Mazzone, Trevor Brown, Florian Kerschbaum, Kevin H. Wilson, Maarten Everts, Florian Hahn, Andreas Peter</p>
    <p><b>Summary:</b> Clustering is a fundamental data processing task used for grouping records
based on one or more features. In the vertically partitioned setting, data is
distributed among entities, with each holding only a subset of those features.
A key challenge in this scenario is that computing distances between records
requires access to all distributed features, which may be privacy-sensitive and
cannot be directly shared with other parties. The goal is to compute the joint
clusters while preserving the privacy of each entity's dataset. Existing
solutions using secret sharing or garbled circuits implement privacy-preserving
variants of Lloyd's algorithm but incur high communication costs, scaling as
O(nkt), where n is the number of data points, k the number of clusters, and t
the number of rounds. These methods become impractical for large datasets or
several parties, limiting their use to LAN settings only. On the other hand, a
different line of solutions rely on differential privacy (DP) to outsource the
local features of the parties to a central server. However, they often
significantly degrade the utility of the clustering outcome due to excessive
noise. In this work, we propose a novel solution based on homomorphic
encryption and DP, reducing communication complexity to O(n+kt). In our method,
parties securely outsource their features once, allowing a computing party to
perform clustering operations under encryption. DP is applied only to the
clusters' centroids, ensuring privacy with minimal impact on utility. Our
solution clusters 100,000 two-dimensional points into five clusters using only
73MB of communication, compared to 101GB for existing works, and completes in
just under 3 minutes on a 100Mbps network, whereas existing works take over 1
day. This makes our solution practical even for WAN deployments, all while
maintaining accuracy comparable to plaintext k-means algorithms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.07414v2">Decomposition-Based Optimal Bounds for Privacy Amplification via
  Shuffling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-04-10T03:11:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pengcheng Su, Haibo Cheng, Ping Wang</p>
    <p><b>Summary:</b> Shuffling has been shown to amplify differential privacy guarantees, offering
a stronger privacy-utility trade-off. To characterize and compute this
amplification, two fundamental analytical frameworks have been proposed: the
privacy blanket by Balle et al. (CRYPTO 2019) and the clone paradigm (including
both the standard clone and stronger clone) by Feldman et al. (FOCS 2021, SODA
2023). All these methods rely on decomposing local randomizers.
  In this work, we introduce a unified analysis framework--the general clone
paradigm--which encompasses all possible decompositions. We identify the
optimal decomposition within the general clone paradigm. Moreover, we develop a
simple and efficient algorithm to compute the exact value of the optimal
privacy amplification bounds via Fast Fourier Transform. Experimental results
demonstrate that the computed upper bounds for privacy amplification closely
approximate the lower bounds, highlighting the tightness of our approach.
Finally, using our algorithm, we conduct the first systematic analysis of the
joint composition of LDP protocols in the shuffle model.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.07362v1">Augmented Shuffle Protocols for Accurate and Robust Frequency Estimation
  under Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-04-10T01:06:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Takao Murakami, Yuichi Sei, Reo Eriguchi</p>
    <p><b>Summary:</b> The shuffle model of DP (Differential Privacy) provides high utility by
introducing a shuffler that randomly shuffles noisy data sent from users.
However, recent studies show that existing shuffle protocols suffer from the
following two major drawbacks. First, they are vulnerable to local data
poisoning attacks, which manipulate the statistics about input data by sending
crafted data, especially when the privacy budget epsilon is small. Second, the
actual value of epsilon is increased by collusion attacks by the data collector
and users.
  In this paper, we address these two issues by thoroughly exploring the
potential of the augmented shuffle model, which allows the shuffler to perform
additional operations, such as random sampling and dummy data addition.
Specifically, we propose a generalized framework for local-noise-free protocols
in which users send (encrypted) input data to the shuffler without adding
noise. We show that this generalized protocol provides DP and is robust to the
above two attacks if a simpler mechanism that performs the same process on
binary input data provides DP. Based on this framework, we propose three
concrete protocols providing DP and robustness against the two attacks. Our
first protocol generates the number of dummy values for each item from a
binomial distribution and provides higher utility than several state-of-the-art
existing shuffle protocols. Our second protocol significantly improves the
utility of our first protocol by introducing a novel dummy-count distribution:
asymmetric two-sided geometric distribution. Our third protocol is a special
case of our second protocol and provides pure epsilon-DP. We show the
effectiveness of our protocols through theoretical analysis and comprehensive
experiments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.07323v1">Prekey Pogo: Investigating Security and Privacy Issues in WhatsApp's
  Handshake Mechanism</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2025-04-09T22:53:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gabriel K. Gegenhuber, Philipp É. Frenzel, Maximilian Günther, Aljosha Judmayer</p>
    <p><b>Summary:</b> WhatsApp, the world's largest messaging application, uses a version of the
Signal protocol to provide end-to-end encryption (E2EE) with strong security
guarantees, including Perfect Forward Secrecy (PFS). To ensure PFS right from
the start of a new conversation -- even when the recipient is offline -- a
stash of ephemeral (one-time) prekeys must be stored on a server. While the
critical role of these one-time prekeys in achieving PFS has been outlined in
the Signal specification, we are the first to demonstrate a targeted depletion
attack against them on individual WhatsApp user devices. Our findings not only
reveal an attack that can degrade PFS for certain messages, but also expose
inherent privacy risks and serious availability implications arising from the
refilling and distribution procedure essential for this security mechanism.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.06697v1">"Sorry for bugging you so much." Exploring Developers' Behavior Towards
  Privacy-Compliant Implementation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-04-09T08:59:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stefan Albert Horstmann, Sandy Hong, David Klein, Raphael Serafini, Martin Degeling, Martin Johns, Veelasha Moonsamy, Alena Naiakshina</p>
    <p><b>Summary:</b> While protecting user data is essential, software developers often fail to
fulfill privacy requirements. However, the reasons why they struggle with
privacy-compliant implementation remain unclear. Is it due to a lack of
knowledge, or is it because of insufficient support? To provide foundational
insights in this field, we conducted a qualitative 5-hour programming study
with 30 professional software developers implementing 3 privacy-sensitive
programming tasks that were designed with GDPR compliance in mind. To explore
if and how developers implement privacy requirements, participants were divided
into 3 groups: control, privacy prompted, and privacy expert-supported. After
task completion, we conducted follow-up interviews. Alarmingly, almost all
participants submitted non-GDPR-compliant solutions (79/90). In particular,
none of the 3 tasks were solved privacy-compliant by all 30 participants, with
the non-prompted group having the lowest number of 3 out of 30
privacy-compliant solution attempts. Privacy prompting and expert support only
slightly improved participants' submissions, with 6/30 and 8/30
privacy-compliant attempts, respectively. In fact, all participants reported
severe issues addressing common privacy requirements such as purpose
limitation, user consent, or data minimization. Counterintuitively, although
most developers exhibited minimal confidence in their solutions, they rarely
sought online assistance or contacted the privacy expert, with only 4 out of 10
expert-supported participants explicitly asking for compliance confirmation.
Instead, participants often relied on existing implementations and focused on
implementing functionality and security first.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.06552v1">Understanding Users' Security and Privacy Concerns and Attitudes Towards
  Conversational AI Platforms</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-04-09T03:22:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mutahar Ali, Arjun Arunasalam, Habiba Farrukh</p>
    <p><b>Summary:</b> The widespread adoption of conversational AI platforms has introduced new
security and privacy risks. While these risks and their mitigation strategies
have been extensively researched from a technical perspective, users'
perceptions of these platforms' security and privacy remain largely unexplored.
In this paper, we conduct a large-scale analysis of over 2.5M user posts from
the r/ChatGPT Reddit community to understand users' security and privacy
concerns and attitudes toward conversational AI platforms. Our qualitative
analysis reveals that users are concerned about each stage of the data
lifecycle (i.e., collection, usage, and retention). They seek mitigations for
security vulnerabilities, compliance with privacy regulations, and greater
transparency and control in data handling. We also find that users exhibit
varied behaviors and preferences when interacting with these platforms. Some
users proactively safeguard their data and adjust privacy settings, while
others prioritize convenience over privacy risks, dismissing privacy concerns
in favor of benefits, or feel resigned to inevitable data sharing. Through
qualitative content and regression analysis, we discover that users' concerns
evolve over time with the evolving AI landscape and are influenced by
technological developments and major events. Based on our findings, we provide
recommendations for users, platforms, enterprises, and policymakers to enhance
transparency, improve data controls, and increase user trust and adoption.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.05849v1">On the Importance of Conditioning for Privacy-Preserving Data
  Augmentation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-04-08T09:27:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Julian Lorenz, Katja Ludwig, Valentin Haug, Rainer Lienhart</p>
    <p><b>Summary:</b> Latent diffusion models can be used as a powerful augmentation method to
artificially extend datasets for enhanced training. To the human eye, these
augmented images look very different to the originals. Previous work has
suggested to use this data augmentation technique for data anonymization.
However, we show that latent diffusion models that are conditioned on features
like depth maps or edges to guide the diffusion process are not suitable as a
privacy preserving method. We use a contrastive learning approach to train a
model that can correctly identify people out of a pool of candidates. Moreover,
we demonstrate that anonymization using conditioned diffusion models is
susceptible to black box attacks. We attribute the success of the described
methods to the conditioning of the latent diffusion model in the anonymization
process. The diffusion model is instructed to produce similar edges for the
anonymized images. Hence, a model can learn to recognize these patterns for
identification.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.05202v1">Infinitely Divisible Noise for Differential Privacy: Nearly Optimal
  Error in the High $\varepsilon$ Regime</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2025-04-07T15:50:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Charlie Harrison, Pasin Manurangsi</p>
    <p><b>Summary:</b> Differential privacy (DP) can be achieved in a distributed manner, where
multiple parties add independent noise such that their sum protects the overall
dataset with DP. A common technique here is for each party to sample their
noise from the decomposition of an infinitely divisible distribution. We
analyze two mechanisms in this setting: 1) the generalized discrete Laplace
(GDL) mechanism, whose distribution (which is closed under summation) follows
from differences of i.i.d. negative binomial shares, and 2) the multi-scale
discrete Laplace (MSDLap) mechanism, a novel mechanism following the sum of
multiple i.i.d. discrete Laplace shares at different scales.
  For $\varepsilon \geq 1$, our mechanisms can be parameterized to have
$O\left(\Delta^3 e^{-\varepsilon}\right)$ and $O\left(\min\left(\Delta^3
e^{-\varepsilon}, \Delta^2 e^{-2\varepsilon/3}\right)\right)$ MSE,
respectively, where $\Delta$ denote the sensitivity; the latter bound matches
known optimality results. We also show a transformation from the discrete
setting to the continuous setting, which allows us to transform both mechanisms
to the continuous setting and thereby achieve the optimal $O\left(\Delta^2
e^{-2\varepsilon / 3}\right)$ MSE. To our knowledge, these are the first
infinitely divisible additive noise mechanisms that achieve order-optimal MSE
under pure DP, so our work shows formally there is no separation in utility
when query-independent noise adding mechanisms are restricted to infinitely
divisible noise. For the continuous setting, our result improves upon the Arete
mechanism from [Pagh and Stausholm, ALT 2022] which gives an MSE of
$O\left(\Delta^2 e^{-\varepsilon/4}\right)$. Furthermore, we give an exact
sampler tuned to efficiently implement the MSDLap mechanism, and we apply our
results to improve a state of the art multi-message shuffle DP protocol in the
high $\varepsilon$ regime.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.04734v1">Teaching Data Science Students to Sketch Privacy Designs through
  Heuristics (Extended Technical Report)</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-04-07T05:12:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jinhe Wen, Yingxi Zhao, Wenqian Xu, Yaxing Yao, Haojian Jin</p>
    <p><b>Summary:</b> Recent studies reveal that experienced data practitioners often draw sketches
to facilitate communication around privacy design concepts. However, there is
limited understanding of how we can help novice students develop such
communication skills. This paper studies methods for lowering novice data
science students' barriers to creating high-quality privacy sketches. We first
conducted a need-finding study (N=12) to identify barriers students face when
sketching privacy designs. We then used a human-centered design approach to
guide the method development, culminating in three simple, text-based
heuristics. Our user studies with 24 data science students revealed that simply
presenting three heuristics to the participants at the beginning of the study
can enhance the coverage of privacy-related design decisions in sketches,
reduce the mental effort required for creating sketches, and improve the
readability of the final sketches.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.04388v1">Who's Watching You Zoom? Investigating Privacy of Third-Party Zoom Apps</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-04-06T06:48:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Saharsh Goenka, Adit Prabhu, Payge Sakurai, Mrinaal Ramachandran, Rakibul Hasan</p>
    <p><b>Summary:</b> Zoom serves millions of users daily and allows third-party developers to
integrate their apps with the Zoom client and reach those users. So far, these
apps' privacy and security aspects, which can access rich audio-visual data
(among others) from Zoom, have not been scientifically investigated. This paper
examines the evolution of the Zoom Marketplace over one year, identifying
trends in apps, their data collection behaviors, and the transparency of
privacy policies. Our findings include worrisome details about the increasing
over-collection of user data, non-transparency about purposes and sharing
behaviors, and possible non-compliance with relevant laws. We believe these
findings will inform future privacy and security research on this platform and
help improve Zoom's app review process and platform policy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.04033v1">Disparate Privacy Vulnerability: Targeted Attribute Inference Attacks
  and Defenses</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-04-05T02:58:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ehsanul Kabir, Lucas Craig, Shagufta Mehnaz</p>
    <p><b>Summary:</b> As machine learning (ML) technologies become more prevalent in
privacy-sensitive areas like healthcare and finance, eventually incorporating
sensitive information in building data-driven algorithms, it is vital to
scrutinize whether these data face any privacy leakage risks. One potential
threat arises from an adversary querying trained models using the public,
non-sensitive attributes of entities in the training data to infer their
private, sensitive attributes, a technique known as the attribute inference
attack. This attack is particularly deceptive because, while it may perform
poorly in predicting sensitive attributes across the entire dataset, it excels
at predicting the sensitive attributes of records from a few vulnerable groups,
a phenomenon known as disparate vulnerability. This paper illustrates that an
adversary can take advantage of this disparity to carry out a series of new
attacks, showcasing a threat level beyond previous imagination. We first
develop a novel inference attack called the disparity inference attack, which
targets the identification of high-risk groups within the dataset. We then
introduce two targeted variations of the attribute inference attack that can
identify and exploit a vulnerable subset of the training data, marking the
first instances of targeted attacks in this category, achieving significantly
higher accuracy than untargeted versions. We are also the first to introduce a
novel and effective disparity mitigation technique that simultaneously
preserves model performance and prevents any risk of targeted attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.03798v1">An Intelligent and Privacy-Preserving Digital Twin Model for
  Aging-in-Place</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">  
  <p><b>Published on:</b> 2025-04-04T05:37:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yongjie Wang, Jonathan Cyril Leung, Ming Chen, Zhiwei Zeng, Benny Toh Hsiang Tan, Yang Qiu, Zhiqi Shen</p>
    <p><b>Summary:</b> The population of older adults is steadily increasing, with a strong
preference for aging-in-place rather than moving to care facilities.
Consequently, supporting this growing demographic has become a significant
global challenge. However, facilitating successful aging-in-place is
challenging, requiring consideration of multiple factors such as data privacy,
health status monitoring, and living environments to improve health outcomes.
In this paper, we propose an unobtrusive sensor system designed for
installation in older adults' homes. Using data from the sensors, our system
constructs a digital twin, a virtual representation of events and activities
that occurred in the home. The system uses neural network models and decision
rules to capture residents' activities and living environments. This digital
twin enables continuous health monitoring by providing actionable insights into
residents' well-being. Our system is designed to be low-cost and
privacy-preserving, with the aim of providing green and safe monitoring for the
health of older adults. We have successfully deployed our system in two homes
over a time period of two months, and our findings demonstrate the feasibility
and effectiveness of digital twin technology in supporting independent living
for older adults. This study highlights that our system could revolutionize
elder care by enabling personalized interventions, such as lifestyle
adjustments, medical treatments, or modifications to the residential
environment, to enhance health outcomes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.03173v1">PPFPL: Cross-silo Privacy-preserving Federated Prototype Learning
  Against Data Poisoning Attacks on Non-IID Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-04-04T05:05:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hongliang Zhang, Jiguo Yu, Fenghua Xu, Chunqiang Hu, Yongzhao Zhang, Xiaofen Wang, Zhongyuan Yu, Xiaosong Zhang</p>
    <p><b>Summary:</b> Privacy-Preserving Federated Learning (PPFL) allows multiple clients to
collaboratively train a deep learning model by submitting hidden model updates.
Nonetheless, PPFL is vulnerable to data poisoning attacks due to the
distributed training nature of clients. Existing solutions have struggled to
improve the performance of cross-silo PPFL in poisoned Non-IID data. To address
the issues, this paper proposes a privacy-preserving federated prototype
learning framework, named PPFPL, which enhances the cross-silo FL performance
in poisoned Non-IID data while effectively resisting data poisoning attacks.
Specifically, we adopt prototypes as client-submitted model updates to
eliminate the impact of tampered data distribution on federated learning.
Moreover, we utilize two servers to achieve Byzantine-robust aggregation by
secure aggregation protocol, which greatly reduces the impact of malicious
clients. Theoretical analyses confirm the convergence of PPFPL, and
experimental results on publicly available datasets show that PPFPL is
effective for resisting data poisoning attacks with Non-IID conditions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.02149v1">Exploring the Privacy and Security Challenges Faced by Migrant Domestic
  Workers in Chinese Smart Homes</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-04-02T21:49:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shijing He, Xiao Zhan, Yaxiong Lei, Yueyan Liu, Ruba Abu-Salma, Jose Such</p>
    <p><b>Summary:</b> The growing use of smart home devices poses considerable privacy and security
challenges, especially for individuals like migrant domestic workers (MDWs) who
may be surveilled by their employers. This paper explores the privacy and
security challenges experienced by MDWs in multi-user smart homes through
in-depth semi-structured interviews with 26 MDWs and 5 staff members of
agencies that recruit and/or train domestic workers in China. Our findings
reveal that the relationships between MDWs, their employers, and agencies are
characterized by significant power imbalances, influenced by Chinese cultural
and social factors (such as Confucianism and collectivism), as well as legal
ones. Furthermore, the widespread and normalized use of surveillance
technologies in China, particularly in public spaces, exacerbates these power
imbalances, reinforcing a sense of constant monitoring and control. Drawing on
our findings, we provide recommendations to domestic worker agencies and
policymakers to address the privacy and security challenges facing MDWs in
Chinese smart homes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.02068v1">Privacy-Preserving Edge Computing from Pairing-Based Inner Product
  Functional Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-04-02T19:01:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Utsav Banerjee</p>
    <p><b>Summary:</b> Pairing-based inner product functional encryption provides an efficient
theoretical construction for privacy-preserving edge computing secured by
widely deployed elliptic curve cryptography. In this work, an efficient
software implementation framework for pairing-based function-hiding inner
product encryption (FHIPE) is presented using the recently proposed and widely
adopted BLS12-381 pairing-friendly elliptic curve. Algorithmic optimizations
provide $\approx 2.6 \times$ and $\approx 3.4 \times$ speedup in FHIPE
encryption and decryption respectively, and extensive performance analysis is
presented using a Raspberry Pi 4B edge device. The proposed optimizations
enable this implementation framework to achieve performance and ciphertext size
comparable to previous work despite being implemented on an edge device with a
slower processor and supporting a curve at much higher security level with a
larger prime field. Practical privacy-preserving edge computing applications
such as encrypted biomedical sensor data classification and secure wireless
fingerprint-based indoor localization are also demonstrated using the proposed
implementation framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.01820v1">Antenna Selection for Enhancing Privacy in Radar-Based Vital Sign
  Monitoring Systems</a></h3>
  
  <p><b>Published on:</b> 2025-04-02T15:28:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhihao Tao, Athina P. Petropulu</p>
    <p><b>Summary:</b> Radar-based vital sign monitoring (VSM) systems have become valuable for
non-contact health monitoring by detecting physiological activities, such as
respiration and heartbeat, remotely. However, the conventional phased array
used in VSM is vulnerable to privacy breaches, as an eavesdropper can extract
sensitive vital sign information by analyzing the reflected radar signals. In
this paper, we propose a novel approach to protect privacy in radar-based VSM
by modifying the radar transmitter hardware, specifically by strategically
selecting the transmit antennas from the available antennas in the transmit
array. By dynamically selecting which antennas connect or disconnect to the
radio frequency chain, the transmitter introduces additional phase noise to the
radar echoes, generating false frequencies in the power spectrum of the
extracted phases at the eavesdropper's receiver. The antenna activation pattern
is designed to maximize the variance of the phases introduced by antenna
selection, which effectively makes the false frequencies dominate the spectrum,
obscuring the actual vital sign frequencies. Meanwhile, the authorized
receiver, having knowledge of the antenna selection pattern, can compensate for
the phase noise and accurately extract the vital signs. Numerical experiments
are conducted to validate the effectiveness of the proposed approach in
enhancing privacy while maintaining vital sign monitoring.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.00952v1">Personalized Federated Training of Diffusion Models with Privacy
  Guarantees</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-04-01T16:45:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kumar Kshitij Patel, Weitong Zhang, Lingxiao Wang</p>
    <p><b>Summary:</b> The scarcity of accessible, compliant, and ethically sourced data presents a
considerable challenge to the adoption of artificial intelligence (AI) in
sensitive fields like healthcare, finance, and biomedical research.
Furthermore, access to unrestricted public datasets is increasingly constrained
due to rising concerns over privacy, copyright, and competition. Synthetic data
has emerged as a promising alternative, and diffusion models -- a cutting-edge
generative AI technology -- provide an effective solution for generating
high-quality and diverse synthetic data. In this paper, we introduce a novel
federated learning framework for training diffusion models on decentralized
private datasets. Our framework leverages personalization and the inherent
noise in the forward diffusion process to produce high-quality samples while
ensuring robust differential privacy guarantees. Our experiments show that our
framework outperforms non-collaborative training methods, particularly in
settings with high data heterogeneity, and effectively reduces biases and
imbalances in synthetic data, resulting in fairer downstream models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.00919v1">Nonparametric spectral density estimation using interactive mechanisms
  under local differential privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">  
  <p><b>Published on:</b> 2025-04-01T15:52:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Cristina Butucea, Karolina Klockmann, Tatyana Krivobokova</p>
    <p><b>Summary:</b> We address the problem of nonparametric estimation of the spectral density
for a centered stationary Gaussian time series under local differential privacy
constraints. Specifically, we propose new interactive privacy mechanisms for
three tasks: estimating a single covariance coefficient, estimating the
spectral density at a fixed frequency, and estimating the entire spectral
density function. Our approach achieves faster rates through a two-stage
process: we apply first the Laplace mechanism to the truncated value and then
use the former privatized sample to gain knowledge on the dependence mechanism
in the time series. For spectral densities belonging to H\"older and Sobolev
smoothness classes, we demonstrate that our estimators improve upon the
non-interactive mechanism of Kroll (2024) for small privacy parameter $\alpha$,
since the pointwise rates depend on $n\alpha^2$ instead of $n\alpha^4$.
Moreover, we show that the rate $(n\alpha^4)^{-1}$ is optimal for estimating a
covariance coefficient with non-interactive mechanisms. However, the $L_2$ rate
of our interactive estimator is slower than the pointwise rate. We show how to
use these estimators to provide a bona-fide locally differentially private
covariance matrix estimator.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.00890v1">Privacy-Preserving Transfer Learning for Community Detection using
  Locally Distributed Multiple Networks</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-04-01T15:19:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiao Guo, Xuming He, Xiangyu Chang, Shujie Ma</p>
    <p><b>Summary:</b> This paper develops a new spectral clustering-based method called TransNet
for transfer learning in community detection of network data. Our goal is to
improve the clustering performance of the target network using auxiliary source
networks, which are heterogeneous, privacy-preserved, and locally stored across
various sources. The edges of each locally stored network are perturbed using
the randomized response mechanism to achieve differential privacy. Notably, we
allow the source networks to have distinct privacy-preserving and heterogeneity
levels as often desired in practice. To better utilize the information from the
source networks, we propose a novel adaptive weighting method to aggregate the
eigenspaces of the source networks multiplied by adaptive weights chosen to
incorporate the effects of privacy and heterogeneity. We propose a
regularization method that combines the weighted average eigenspace of the
source networks with the eigenspace of the target network to achieve an optimal
balance between them. Theoretically, we show that the adaptive weighting method
enjoys the error-bound-oracle property in the sense that the error bound of the
estimated eigenspace only depends on informative source networks. We also
demonstrate that TransNet performs better than the estimator using only the
target network and the estimator using only the weighted source networks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.00874v1">P2NIA: Privacy-Preserving Non-Iterative Auditing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-04-01T15:04:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jade Garcia Bourrée, Hadrien Lautraite, Sébastien Gambs, Gilles Tredan, Erwan Le Merrer, Benoît Rottembourg</p>
    <p><b>Summary:</b> The emergence of AI legislation has increased the need to assess the ethical
compliance of high-risk AI systems. Traditional auditing methods rely on
platforms' application programming interfaces (APIs), where responses to
queries are examined through the lens of fairness requirements. However, such
approaches put a significant burden on platforms, as they are forced to
maintain APIs while ensuring privacy, facing the possibility of data leaks.
This lack of proper collaboration between the two parties, in turn, causes a
significant challenge to the auditor, who is subject to estimation bias as they
are unaware of the data distribution of the platform. To address these two
issues, we present P2NIA, a novel auditing scheme that proposes a mutually
beneficial collaboration for both the auditor and the platform. Extensive
experiments demonstrate P2NIA's effectiveness in addressing both issues. In
summary, our work introduces a privacy-preserving and non-iterative audit
scheme that enhances fairness assessments using synthetic or local data,
avoiding the challenges associated with traditional API-based audits.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.00858v1">Whispering Under the Eaves: Protecting User Privacy Against Commercial
  and LLM-powered Automatic Speech Recognition Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36">
  <p><b>Published on:</b> 2025-04-01T14:49:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Weifei Jin, Yuxin Cao, Junjie Su, Derui Wang, Yedi Zhang, Minhui Xue, Jie Hao, Jin Song Dong, Yixian Yang</p>
    <p><b>Summary:</b> The widespread application of automatic speech recognition (ASR) supports
large-scale voice surveillance, raising concerns about privacy among users. In
this paper, we concentrate on using adversarial examples to mitigate
unauthorized disclosure of speech privacy thwarted by potential eavesdroppers
in speech communications. While audio adversarial examples have demonstrated
the capability to mislead ASR models or evade ASR surveillance, they are
typically constructed through time-intensive offline optimization, restricting
their practicality in real-time voice communication. Recent work overcame this
limitation by generating universal adversarial perturbations (UAPs) and
enhancing their transferability for black-box scenarios. However, they
introduced excessive noise that significantly degrades audio quality and
affects human perception, thereby limiting their effectiveness in practical
scenarios. To address this limitation and protect live users' speech against
ASR systems, we propose a novel framework, AudioShield. Central to this
framework is the concept of Transferable Universal Adversarial Perturbations in
the Latent Space (LS-TUAP). By transferring the perturbations to the latent
space, the audio quality is preserved to a large extent. Additionally, we
propose target feature adaptation to enhance the transferability of UAPs by
embedding target text features into the perturbations. Comprehensive evaluation
on four commercial ASR APIs (Google, Amazon, iFlytek, and Alibaba), three voice
assistants, two LLM-powered ASR and one NN-based ASR demonstrates the
protection superiority of AudioShield over existing competitors, and both
objective and subjective evaluations indicate that AudioShield significantly
improves the audio quality. Moreover, AudioShield also shows high effectiveness
in real-time end-to-end scenarios, and demonstrates strong resilience against
adaptive countermeasures.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.00411v1">Forward Learning with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-04-01T04:14:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mingqian Feng, Zeliang Zhang, Jinyang Jiang, Yijie Peng, Chenliang Xu</p>
    <p><b>Summary:</b> Differential privacy (DP) in deep learning is a critical concern as it
ensures the confidentiality of training data while maintaining model utility.
Existing DP training algorithms provide privacy guarantees by clipping and then
injecting external noise into sample gradients computed by the backpropagation
algorithm. Different from backpropagation, forward-learning algorithms based on
perturbation inherently add noise during the forward pass and utilize
randomness to estimate the gradients. Although these algorithms are
non-privatized, the introduction of noise during the forward pass indirectly
provides internal randomness protection to the model parameters and their
gradients, suggesting the potential for naturally providing differential
privacy. In this paper, we propose a \blue{privatized} forward-learning
algorithm, Differential Private Unified Likelihood Ratio (DP-ULR), and
demonstrate its differential privacy guarantees. DP-ULR features a novel batch
sampling operation with rejection, of which we provide theoretical analysis in
conjunction with classic differential privacy mechanisms. DP-ULR is also
underpinned by a theoretically guided privacy controller that dynamically
adjusts noise levels to manage privacy costs in each training step. Our
experiments indicate that DP-ULR achieves competitive performance compared to
traditional differential privacy training algorithms based on backpropagation,
maintaining nearly the same privacy loss limits.</p>
  </details>
</div>



<h2>2025-03</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.00282v1">Federated Learning for Cross-Domain Data Privacy: A Distributed Approach
  to Secure Collaboration</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-03-31T23:04:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yiwei Zhang, Jie Liu, Jiawei Wang, Lu Dai, Fan Guo, Guohui Cai</p>
    <p><b>Summary:</b> This paper proposes a data privacy protection framework based on federated
learning, which aims to realize effective cross-domain data collaboration under
the premise of ensuring data privacy through distributed learning. Federated
learning greatly reduces the risk of privacy breaches by training the model
locally on each client and sharing only model parameters rather than raw data.
The experiment verifies the high efficiency and privacy protection ability of
federated learning under different data sources through the simulation of
medical, financial, and user data. The results show that federated learning can
not only maintain high model performance in a multi-domain data environment but
also ensure effective protection of data privacy. The research in this paper
provides a new technical path for cross-domain data collaboration and promotes
the application of large-scale data analysis and machine learning while
protecting privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.03730v1">Safeguarding Smart Inhaler Devices and Patient Privacy in Respiratory
  Health Monitoring</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-03-31T18:16:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Asaju Babajide, Almustapha Wakili, Michaela Barnett, Lucas Potter, Xavier-Lewis Palmer, Woosub Jung</p>
    <p><b>Summary:</b> The rapid development of Internet of Things (IoT) technology has
significantly impacted various market sectors. According to Li et al. (2024),
an estimated 75 billion devices will be on the market in 2025. The healthcare
industry is a target to improve patient care and ease healthcare provider
burdens. Chronic respiratory disease is likely to benefit from their inclusion,
with 545 million people worldwide recorded to suffer from patients using these
devices to track their dosage. At the same time, healthcare providers can
improve medication administration and monitor respiratory health (Soriano et
al., 2020). While IoT medical devices offer numerous benefits, they also have
security vulnerabilities that can expose patient data to cyberattacks. It's
crucial to prioritize security measures in developing and deploying IoT medical
devices, especially in personalized health monitoring systems for individuals
with respiratory conditions. Efforts are underway to assess the security risks
associated with intelligent inhalers and respiratory medical devices by
understanding usability behavior and technological elements to identify and
address vulnerabilities effectively. This work analyses usability behavior and
technical vulnerabilities, emphasizing the confidentiality of information
gained from Smart Inhalers. It then extrapolates to interrogate potential
vulnerabilities with Implantable Medical Devices (IMDs). Our work explores the
tensions in device development through the intersection of IoT technology and
respiratory health, particularly in the context of intelligent inhalers and
other breathing medical devices, calling for integrating robust security
measures into the development and deployment of IoT devices to safeguard
patient data and ensure the secure functioning of these critical healthcare
technologies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.24089v1">Initial State Privacy of Nonlinear Systems on Riemannian Manifolds</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2025-03-31T13:42:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Le Liu, Yu Kawano, Antai Xie, Ming Cao</p>
    <p><b>Summary:</b> In this paper, we investigate initial state privacy protection for
discrete-time nonlinear closed systems. By capturing Riemannian geometric
structures inherent in such privacy challenges, we refine the concept of
differential privacy through the introduction of an initial state adjacency set
based on Riemannian distances. A new differential privacy condition is
formulated using incremental output boundedness, enabling the design of
time-varying Laplacian noise to achieve specified privacy guarantees. The
proposed framework extends beyond initial state protection to also cover system
parameter privacy, which is demonstrated as a special application.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.23903v1">Privacy Preservation for Statistical Input in Dynamical Systems</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2025-03-31T09:54:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Le Liu, Yu Kawano, Ming Cao</p>
    <p><b>Summary:</b> This paper addresses the challenge of privacy preservation for statistical
inputs in dynamical systems. Motivated by an autonomous building application,
we formulate a privacy preservation problem for statistical inputs in linear
time-invariant systems. What makes this problem widely applicable is that the
inputs, rather than being assumed to be deterministic, follow a probability
distribution, inherently embedding privacy-sensitive information that requires
protection. This formulation also presents a technical challenge as
conventional differential privacy mechanisms are not directly applicable.
Through rigorous analysis, we develop strategy to achieve $(0, \delta)$
differential privacy through adding noise. Finally, the effectiveness of our
methods is demonstrated by revisiting the autonomous building application.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.23726v2">PDSL: Privacy-Preserved Decentralized Stochastic Learning with
  Heterogeneous Data Distribution</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-03-31T04:58:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lina Wang, Yunsheng Yuan, Chunxiao Wang, Feng Li</p>
    <p><b>Summary:</b> In the paradigm of decentralized learning, a group of agents collaborates to
learn a global model using distributed datasets without a central server.
However, due to the heterogeneity of the local data across the different
agents, learning a robust global model is rather challenging. Moreover, the
collaboration of the agents relies on their gradient information exchange,
which poses a risk of privacy leakage. In this paper, to address these issues,
we propose PDSL, a novel privacy-preserved decentralized stochastic learning
algorithm with heterogeneous data distribution. On one hand, we innovate in
utilizing the notion of Shapley values such that each agent can precisely
measure the contributions of its heterogeneous neighbors to the global learning
goal; on the other hand, we leverage the notion of differential privacy to
prevent each agent from suffering privacy leakage when it contributes gradient
information to its neighbors. We conduct both solid theoretical analysis and
extensive experiments to demonstrate the efficacy of our PDSL algorithm in
terms of privacy preservation and convergence.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.23533v1">To See or Not to See: A Privacy Threat Model for Digital Forensics in
  Crime Investigation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-03-30T17:34:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mario Raciti, Simone Di Mauro, Dimitri Van Landuyt, Giampaolo Bella</p>
    <p><b>Summary:</b> Digital forensics is a cornerstone of modern crime investigations, yet it
raises significant privacy concerns due to the collection, processing, and
storage of digital evidence. Despite that, privacy threats in digital forensics
crime investigations often remain underexplored, thereby leading to potential
gaps in forensic practices and regulatory compliance, which may then escalate
into harming the freedoms of natural persons. With this clear motivation, the
present paper applies the SPADA methodology for threat modelling with the goal
of incorporating privacy-oriented threat modelling in digital forensics. As a
result, we identify a total of 298 privacy threats that may affect digital
forensics processes through crime investigations. Furthermore, we demonstrate
an unexplored feature on how SPADA assists in handling domain-dependency during
threat elicitation. This yields a second list of privacy threats that are
universally applicable to any domain. We then present a comprehensive and
systematic privacy threat model for digital forensics in crime investigation.
Moreover, we discuss some of the challenges about validating privacy threats in
this domain, particularly given the variability of legal frameworks across
jurisdictions. We ultimately propose our privacy threat model as a tool for
ensuring ethical and legally compliant investigative practices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.23444v1">The Processing goes far beyond "the app" -- Privacy issues of
  decentralized Digital Contact Tracing using the example of the German
  Corona-Warn-App (CWA)</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2025-03-30T13:48:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rainer Rehak, Christian R. Kuehne</p>
    <p><b>Summary:</b> Since SARS-CoV-2 started spreading in Europe in early 2020, there has been a
strong call for technical solutions to combat or contain the pandemic, with
contact tracing apps at the heart of the debates. The EU's General Data
Protection Regulation (GDPR) requires controllers to carry out a data
protection impact assessment (DPIA) where their data processing is likely to
result in a high risk to the rights and freedoms (Art. 35 GDPR). A DPIA is a
structured risk analysis that identifies and evaluates possible consequences of
data processing relevant to fundamental rights in advance and describes the
measures envisaged to address these risks or expresses the inability to do so.
Based on the Standard Data Protection Model (SDM), we present the results of a
scientific and methodologically clear DPIA of the German German Corona-Warn-App
(CWA). It shows that even a decentralized architecture involves numerous
serious weaknesses and risks, including larger ones still left unaddressed in
current implementations. It also found that none of the proposed designs
operates on anonymous data or ensures proper anonymisation. It also showed that
informed consent would not be a legitimate legal ground for the processing. For
all points where data subjects' rights are still not sufficiently safeguarded,
we briefly outline solutions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.23292v1">FedCAPrivacy: Privacy-Preserving Heterogeneous Federated Learning with
  Anonymous Adaptive Clustering</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-03-30T03:16:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yunan Wei, Shengnan Zhao, Chuan Zhao, Zhe Liu, Zhenxiang Chen, Minghao Zhao</p>
    <p><b>Summary:</b> Federated learning (FL) is a distributed machine learning paradigm enabling
multiple clients to train a model collaboratively without exposing their local
data. Among FL schemes, clustering is an effective technique addressing the
heterogeneity issue (i.e., differences in data distribution and computational
ability affect training performance and effectiveness) via grouping
participants with similar computational resources or data distribution into
clusters. However, intra-cluster data exchange poses privacy risks, while
cluster selection and adaptation introduce challenges that may affect overall
performance. To address these challenges, this paper introduces anonymous
adaptive clustering, a novel approach that simultaneously enhances privacy
protection and boosts training efficiency. Specifically, an oblivious
shuffle-based anonymization method is designed to safeguard user identities and
prevent the aggregation server from inferring similarities through clustering.
Additionally, to improve performance, we introduce an iteration-based adaptive
frequency decay strategy, which leverages variability in clustering
probabilities to optimize training dynamics. With these techniques, we build
the FedCAPrivacy; experiments show that FedCAPrivacy achieves ~7X improvement
in terms of performance while maintaining high privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.23026v1">Federated Semantic Learning for Privacy-preserving Cross-domain
  Recommendation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2025-03-29T09:37:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ziang Lu, Lei Guo, Xu Yu, Zhiyong Cheng, Xiaohui Han, Lei Zhu</p>
    <p><b>Summary:</b> In the evolving landscape of recommender systems, the challenge of
effectively conducting privacy-preserving Cross-Domain Recommendation (CDR),
especially under strict non-overlapping constraints, has emerged as a key
focus. Despite extensive research has made significant progress, several
limitations still exist: 1) Previous semantic-based methods fail to deeply
exploit rich textual information, since they quantize the text into codes,
losing its original rich semantics. 2) The current solution solely relies on
the text-modality, while the synergistic effects with the ID-modality are
ignored. 3) Existing studies do not consider the impact of irrelevant semantic
features, leading to inaccurate semantic representation. To address these
challenges, we introduce federated semantic learning and devise FFMSR as our
solution. For Limitation 1, we locally learn items'semantic encodings from
their original texts by a multi-layer semantic encoder, and then cluster them
on the server to facilitate the transfer of semantic knowledge between domains.
To tackle Limitation 2, we integrate both ID and Text modalities on the
clients, and utilize them to learn different aspects of items. To handle
Limitation 3, a Fast Fourier Transform (FFT)-based filter and a gating
mechanism are developed to alleviate the impact of irrelevant semantic
information in the local model. We conduct extensive experiments on two
real-world datasets, and the results demonstrate the superiority of our FFMSR
method over other SOTA methods. Our source codes are publicly available at:
https://github.com/Sapphire-star/FFMSR.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.22993v2">Calculating Connection vs. Risk: Understanding How Youth Negotiate
  Digital Privacy and Security with Peers Online</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-03-29T06:54:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mamtaj Akter, Jinkyung Katie Park, Campbell Headrick, Xinru Page, Pamela J. Wisniewski</p>
    <p><b>Summary:</b> Youth, while tech-savvy and highly active on social media, are still
vulnerable to online privacy and security risks. Therefore, it is critical to
understand how they negotiate and manage social connections versus protecting
themselves in online contexts. In this work, we conducted a thematic analysis
of 1,318 private conversations on Instagram from 149 youth aged 13-21 to
understand the digital privacy and security topics they discussed, if and how
they engaged in risky privacy behaviors, and how they balanced the benefits and
risks (i.e., privacy calculus) of making these decisions. Overall, youth were
forthcoming when broaching a wide range of topics on digital privacy and
security, ranging from password management and account access challenges to
shared experiences of being victims of privacy risks. However, they also openly
engaged in risky behaviors, such as sharing personal account information with
peers and even perpetrating privacy and security risks against others.
Nonetheless, we found many of these behaviors could be explained by the unique
"privacy calculus" of youth, where they often prioritized social benefits over
potential risks; for instance, youth often shared account credentials with
peers to foster social connection and affirmation. As such, we provide a
nuanced understanding of youth decision-making regarding digital security and
privacy, highlighting both positive behaviors, tensions, and points of concern.
We encourage future research to continue to challenge the potentially untrue
narratives regarding youth and their digital privacy and security to unpack the
nuance of their privacy calculus that may differ from that of adults.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.01029v1">Who is Responsible When AI Fails? Mapping Causes, Entities, and
  Consequences of AI Privacy and Ethical Incidents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-03-28T21:57:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hilda Hadan, Reza Hadi Mogavi, Leah Zhang-Kennedy, Lennart E. Nacke</p>
    <p><b>Summary:</b> The rapid growth of artificial intelligence (AI) technologies has changed
decision-making in many fields. But, it has also raised major privacy and
ethical concerns. However, many AI incidents taxonomies and guidelines for
academia, industry, and government lack grounding in real-world incidents. We
analyzed 202 real-world AI privacy and ethical incidents. This produced a
taxonomy that classifies incident types across AI lifecycle stages. It accounts
for contextual factors such as causes, responsible entities, disclosure
sources, and impacts. Our findings show insufficient incident reporting from AI
developers and users. Many incidents are caused by poor organizational
decisions and legal non-compliance. Only a few legal actions and corrective
measures exist, while risk-mitigation efforts are limited. Our taxonomy
contributes a structured approach in reporting of future AI incidents. Our
findings demonstrate that current AI governance frameworks are inadequate. We
urgently need child-specific protections and AI policies on social media. They
must moderate and reduce the spread of harmful AI-generated content. Our
research provides insights for policymakers and practitioners, which lets them
design ethical AI. It also support AI incident detection and risk management.
Finally, it guides AI policy development. Improved policies will protect people
from harmful AI applications and support innovation in AI systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.22379v1">Spend Your Budget Wisely: Towards an Intelligent Distribution of the
  Privacy Budget in Differentially Private Text Rewriting</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-03-28T12:33:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stephen Meisenbacher, Chaeeun Joy Lee, Florian Matthes</p>
    <p><b>Summary:</b> The task of $\textit{Differentially Private Text Rewriting}$ is a class of
text privatization techniques in which (sensitive) input textual documents are
$\textit{rewritten}$ under Differential Privacy (DP) guarantees. The motivation
behind such methods is to hide both explicit and implicit identifiers that
could be contained in text, while still retaining the semantic meaning of the
original text, thus preserving utility. Recent years have seen an uptick in
research output in this field, offering a diverse array of word-, sentence-,
and document-level DP rewriting methods. Common to these methods is the
selection of a privacy budget (i.e., the $\varepsilon$ parameter), which
governs the degree to which a text is privatized. One major limitation of
previous works, stemming directly from the unique structure of language itself,
is the lack of consideration of $\textit{where}$ the privacy budget should be
allocated, as not all aspects of language, and therefore text, are equally
sensitive or personal. In this work, we are the first to address this
shortcoming, asking the question of how a given privacy budget can be
intelligently and sensibly distributed amongst a target document. We construct
and evaluate a toolkit of linguistics- and NLP-based methods used to allocate a
privacy budget to constituent tokens in a text document. In a series of privacy
and utility experiments, we empirically demonstrate that given the same privacy
budget, intelligent distribution leads to higher privacy levels and more
positive trade-offs than a naive distribution of $\varepsilon$. Our work
highlights the intricacies of text privatization with DP, and furthermore, it
calls for further work on finding more efficient ways to maximize the
privatization benefits offered by DP in text rewriting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.22232v2">Privacy-Preserving Secure Neighbor Discovery for Wireless Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2025-03-28T08:27:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ahmed Mohamed Hussain, Panos Papadimitratos</p>
    <p><b>Summary:</b> Traditional Neighbor Discovery (ND) and Secure Neighbor Discovery (SND) are
key elements for network functionality. SND is a hard problem, satisfying not
only typical security properties (authentication, integrity) but also
verification of direct communication, which involves distance estimation based
on time measurements and device coordinates. Defeating relay attacks, also
known as "wormholes", leading to stealthy Byzantine links and significant
degradation of communication and adversarial control, is key in many wireless
networked systems. However, SND is not concerned with privacy; it necessitates
revealing the identity and location of the device(s) participating in the
protocol execution. This can be a deterrent for deployment, especially
involving user-held devices in the emerging Internet of Things (IoT) enabled
smart environments. To address this challenge, we present a novel
Privacy-Preserving Secure Neighbor Discovery (PP-SND) protocol, enabling
devices to perform SND without revealing their actual identities and locations,
effectively decoupling discovery from the exposure of sensitive information. We
use Homomorphic Encryption (HE) for computing device distances without
revealing their actual coordinates, as well as employing a pseudonymous device
authentication to hide identities while preserving communication integrity.
PP-SND provides SND [1] along with pseudonymity, confidentiality, and
unlinkability. Our presentation here is not specific to one wireless
technology, and we assess the performance of the protocols (cryptographic
overhead) on a Raspberry Pi 4 and provide a security and privacy analysis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.22161v1">Traffic Modeling for Network Security and Privacy: Challenges Ahead</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-03-28T05:54:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dinil Mon Divakaran</p>
    <p><b>Summary:</b> Traffic analysis using machine learning and deep learning models has made
significant progress over the past decades. These models address various tasks
in network security and privacy, including detection of anomalies and attacks,
countering censorship, etc. They also reveal privacy risks to users as
demonstrated by the research on LLM token inference as well as fingerprinting
(and counter-fingerprinting) of user-visiting websites, IoT devices, and
different applications. However, challenges remain in securing our networks
from threats and attacks. After briefly reviewing the tasks and recent ML
models in network security and privacy, we discuss the challenges that lie
ahead.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.08751v1">Research on the Design of a Short Video Recommendation System Based on
  Multimodal Information and Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-03-27T22:56:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haowei Yang, Lei Fu, Qingyi Lu, Yue Fan, Tianle Zhang, Ruohan Wang</p>
    <p><b>Summary:</b> With the rapid development of short video platforms, recommendation systems
have become key technologies for improving user experience and enhancing
platform engagement. However, while short video recommendation systems leverage
multimodal information (such as images, text, and audio) to improve
recommendation effectiveness, they also face the severe challenge of user
privacy leakage. This paper proposes a short video recommendation system based
on multimodal information and differential privacy protection. First, deep
learning models are used for feature extraction and fusion of multimodal data,
effectively improving recommendation accuracy. Then, a differential privacy
protection mechanism suitable for recommendation scenarios is designed to
ensure user data privacy while maintaining system performance. Experimental
results show that the proposed method outperforms existing mainstream
approaches in terms of recommendation accuracy, multimodal fusion
effectiveness, and privacy protection performance, providing important insights
for the design of recommendation systems for short video platforms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.22010v1">Towards Privacy-Preserving Revocation of Verifiable Credentials with
  Time-Flexibility</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-03-27T21:58:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Francesco Buccafurri, Carmen Licciardi</p>
    <p><b>Summary:</b> Self-Sovereign Identity (SSI) is an emerging paradigm for authentication and
credential presentation that aims to give users control over their data and
prevent any kind of tracking by (even trusted) third parties. In the European
Union, the EUDI Digital Identity wallet is about to become a concrete
implementation of this paradigm. However, a debate is still ongoing, partially
reflecting some aspects that are not yet consolidated in the scientific state
of the art. Among these, an effective, efficient, and privacy-preserving
implementation of verifiable credential revocation remains a subject of
discussion. In this work-in-progress paper, we propose the basis of a novel
method that customizes the use of anonymous hierarchical identity-based
encryption to restrict the Verifier access to the temporal authorizations
granted by the Holder. This way, the Issuer cannot track the Holder's
credential presentations, and the Verifier cannot check revocation information
beyond what is permitted by the Holder.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.22749v1">Adaptive Clipping for Privacy-Preserving Few-Shot Learning: Enhancing
  Generalization with Limited Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-03-27T05:14:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kanishka Ranaweera, Dinh C. Nguyen, Pubudu N. Pathirana, David Smith, Ming Ding, Thierry Rakotoarivelo, Aruna Seneviratne</p>
    <p><b>Summary:</b> In the era of data-driven machine-learning applications, privacy concerns and
the scarcity of labeled data have become paramount challenges. These challenges
are particularly pronounced in the domain of few-shot learning, where the
ability to learn from limited labeled data is crucial. Privacy-preserving
few-shot learning algorithms have emerged as a promising solution to address
such pronounced challenges. However, it is well-known that privacy-preserving
techniques often lead to a drop in utility due to the fundamental trade-off
between data privacy and model performance. To enhance the utility of
privacy-preserving few-shot learning methods, we introduce a novel approach
called Meta-Clip. This technique is specifically designed for meta-learning
algorithms, including Differentially Private (DP) model-agnostic meta-learning,
DP-Reptile, and DP-MetaSGD algorithms, with the objective of balancing data
privacy preservation with learning capacity maximization. By dynamically
adjusting clipping thresholds during the training process, our Adaptive
Clipping method provides fine-grained control over the disclosure of sensitive
information, mitigating overfitting on small datasets and significantly
improving the generalization performance of meta-learning models. Through
comprehensive experiments on diverse benchmark datasets, we demonstrate the
effectiveness of our approach in minimizing utility degradation, showcasing a
superior privacy-utility trade-off compared to existing privacy-preserving
techniques. The adoption of Adaptive Clipping represents a substantial step
forward in the field of privacy-preserving few-shot learning, empowering the
development of secure and accurate models for real-world applications,
especially in scenarios where there are limited data availability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.21159v1">Multi-Objective Optimization for Privacy-Utility Balance in
  Differentially Private Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-03-27T04:57:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kanishka Ranaweera, David Smith, Pubudu N. Pathirana, Ming Ding, Thierry Rakotoarivelo, Aruna Seneviratne</p>
    <p><b>Summary:</b> Federated learning (FL) enables collaborative model training across
distributed clients without sharing raw data, making it a promising approach
for privacy-preserving machine learning. However, ensuring differential privacy
(DP) in FL presents challenges due to the trade-off between model utility and
privacy protection. Clipping gradients before aggregation is a common strategy
to limit privacy loss, but selecting an optimal clipping norm is non-trivial,
as excessively high values compromise privacy, while overly restrictive
clipping degrades model performance. In this work, we propose an adaptive
clipping mechanism that dynamically adjusts the clipping norm using a
multi-objective optimization framework. By integrating privacy and utility
considerations into the optimization objective, our approach balances privacy
preservation with model accuracy. We theoretically analyze the convergence
properties of our method and demonstrate its effectiveness through extensive
experiments on MNIST, Fashion-MNIST, and CIFAR-10 datasets. Our results show
that adaptive clipping consistently outperforms fixed-clipping baselines,
achieving improved accuracy under the same privacy constraints. This work
highlights the potential of dynamic clipping strategies to enhance
privacy-utility trade-offs in differentially private federated learning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.21154v1">Federated Learning with Differential Privacy: An Utility-Enhanced
  Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-03-27T04:48:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kanishka Ranaweera, Dinh C. Nguyen, Pubudu N. Pathirana, David Smith, Ming Ding, Thierry Rakotoarivelo, Aruna Seneviratne</p>
    <p><b>Summary:</b> Federated learning has emerged as an attractive approach to protect data
privacy by eliminating the need for sharing clients' data while reducing
communication costs compared with centralized machine learning algorithms.
However, recent studies have shown that federated learning alone does not
guarantee privacy, as private data may still be inferred from the uploaded
parameters to the central server. In order to successfully avoid data leakage,
adopting differential privacy (DP) in the local optimization process or in the
local update aggregation process has emerged as two feasible ways for achieving
sample-level or user-level privacy guarantees respectively, in federated
learning models. However, compared to their non-private equivalents, these
approaches suffer from a poor utility. To improve the privacy-utility
trade-off, we present a modification to these vanilla differentially private
algorithms based on a Haar wavelet transformation step and a novel noise
injection scheme that significantly lowers the asymptotic bound of the noise
variance. We also present a holistic convergence analysis of our proposed
algorithm, showing that our method yields better convergence performance than
the vanilla DP algorithms. Numerical experiments on real-world datasets
demonstrate that our method outperforms existing approaches in model utility
while maintaining the same privacy guarantees.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.21071v1">Purifying Approximate Differential Privacy with Randomized
  Post-processing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2025-03-27T01:10:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yingyu Lin, Erchi Wang, Yi-An Ma, Yu-Xiang Wang</p>
    <p><b>Summary:</b> We propose a framework to convert $(\varepsilon, \delta)$-approximate
Differential Privacy (DP) mechanisms into $(\varepsilon, 0)$-pure DP
mechanisms, a process we call ``purification''. This algorithmic technique
leverages randomized post-processing with calibrated noise to eliminate the
$\delta$ parameter while preserving utility. By combining the tighter utility
bounds and computational efficiency of approximate DP mechanisms with the
stronger guarantees of pure DP, our approach achieves the best of both worlds.
We illustrate the applicability of this framework in various settings,
including Differentially Private Empirical Risk Minimization (DP-ERM),
data-dependent DP mechanisms such as Propose-Test-Release (PTR), and query
release tasks. To the best of our knowledge, this is the first work to provide
a systematic method for transforming approximate DP into pure DP while
maintaining competitive accuracy and computational efficiency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.21010v1">Privacy in Immersive Extended Reality: Exploring User Perceptions,
  Concerns, and Coping Strategies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-03-26T21:58:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hilda Hadan, Derrick M. Wang, Lennart E. Nacke, Leah Zhang-Kennedy</p>
    <p><b>Summary:</b> Extended Reality (XR) technology is changing online interactions, but its
granular data collection sensors may be more invasive to user privacy than web,
mobile, and the Internet of Things technologies. Despite an increased interest
in studying developers' concerns about XR device privacy, user perceptions have
rarely been addressed. We surveyed 464 XR users to assess their awareness,
concerns, and coping strategies around XR data in 18 scenarios. Our findings
demonstrate that many factors, such as data types and sensitivity, affect
users' perceptions of privacy in XR. However, users' limited awareness of XR
sensors' granular data collection capabilities, such as involuntary body
signals of emotional responses, restricted the range of privacy-protective
strategies they used. Our results highlight a need to enhance users' awareness
of data privacy threats in XR, design privacy-choice interfaces tailored to XR
environments, and develop transparent XR data practices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.20846v1">Generating Synthetic Data with Formal Privacy Guarantees: State of the
  Art and the Road Ahead</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-03-26T16:06:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Viktor Schlegel, Anil A Bharath, Zilong Zhao, Kevin Yee</p>
    <p><b>Summary:</b> Privacy-preserving synthetic data offers a promising solution to harness
segregated data in high-stakes domains where information is compartmentalized
for regulatory, privacy, or institutional reasons. This survey provides a
comprehensive framework for understanding the landscape of privacy-preserving
synthetic data, presenting the theoretical foundations of generative models and
differential privacy followed by a review of state-of-the-art methods across
tabular data, images, and text. Our synthesis of evaluation approaches
highlights the fundamental trade-off between utility for down-stream tasks and
privacy guarantees, while identifying critical research gaps: the lack of
realistic benchmarks representing specialized domains and insufficient
empirical evaluations required to contextualise formal guarantees.
  Through empirical analysis of four leading methods on five real-world
datasets from specialized domains, we demonstrate significant performance
degradation under realistic privacy constraints ($\epsilon \leq 4$), revealing
a substantial gap between results reported on general domain benchmarks and
performance on domain-specific data. %Our findings highlight key challenges
including unaccounted privacy leakage, insufficient empirical verification of
formal guarantees, and a critical deficit of realistic benchmarks. These
challenges underscore the need for robust evaluation frameworks, standardized
benchmarks for specialized domains, and improved techniques to address the
unique requirements of privacy-sensitive fields such that this technology can
deliver on its considerable potential.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.20464v1">Modelling Privacy Compliance in Cross-border Data Transfers with
  Bigraphs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-03-26T11:50:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ebtihal Althubiti, Michele Sevegnani</p>
    <p><b>Summary:</b> Advancements in information technology have led to the sharing of users' data
across borders, raising privacy concerns, particularly when destination
countries lack adequate protection measures. Regulations like the European
General Data Protection Regulation (GDPR) govern international data transfers,
imposing significant fines on companies failing to comply. To achieve
compliance, we propose a privacy framework based on Milner's Bigraphical
Reactive Systems (BRSs), a formalism modelling spatial and non-spatial
relationships between entities. BRSs evolve over time via user-specified
rewriting rules, defined algebraically and diagrammatically. In this paper, we
rely on diagrammatic notations, enabling adoption by end-users and privacy
experts without formal modelling backgrounds. The framework comprises
predefined privacy reaction rules modelling GDPR requirements for international
data transfers, properties expressed in Computation Tree Logic (CTL) to
automatically verify these requirements with a model checker and sorting
schemes to statically ensure models are well-formed. We demonstrate the
framework's applicability by modelling WhatsApp's privacy policies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.20326v1">Modality-Independent Brain Lesion Segmentation with Privacy-aware
  Continual Learning</a></h3>
  
  <p><b>Published on:</b> 2025-03-26T08:53:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yousef Sadegheih, Pratibha Kumari, Dorit Merhof</p>
    <p><b>Summary:</b> Traditional brain lesion segmentation models for multi-modal MRI are
typically tailored to specific pathologies, relying on datasets with predefined
modalities. Adapting to new MRI modalities or pathologies often requires
training separate models, which contrasts with how medical professionals
incrementally expand their expertise by learning from diverse datasets over
time. Inspired by this human learning process, we propose a unified
segmentation model capable of sequentially learning from multiple datasets with
varying modalities and pathologies. Our approach leverages a privacy-aware
continual learning framework that integrates a mixture-of-experts mechanism and
dual knowledge distillation to mitigate catastrophic forgetting while not
compromising performance on newly encountered datasets. Extensive experiments
across five diverse brain MRI datasets and four dataset sequences demonstrate
the effectiveness of our framework in maintaining a single adaptable model,
capable of handling varying hospital protocols, imaging modalities, and disease
types. Compared to widely used privacy-aware continual learning methods such as
LwF, SI, EWC, and MiB, our method achieves an average Dice score improvement of
approximately 11%. Our framework represents a significant step toward more
versatile and practical brain lesion segmentation models, with implementation
available at \href{https://github.com/xmindflow/BrainCL}{GitHub}.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.19872v1">NickPay, an Auditable, Privacy-Preserving, Nickname-Based Payment System</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-03-25T17:36:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guillaume Quispe, Pierre Jouvelot, Gerard Memmi</p>
    <p><b>Summary:</b> In this paper, we describe the motivation, design, security properties, and a
prototype implementation of NickPay, a new privacy-preserving yet auditable
payment system built on top of the Ethereum blockchain platform. NickPay offers
a strong level of privacy to participants and prevents successive payment
transfers from being linked to their actual owners.
  It is providing the transparency that blockchains ensure and at the same
time, preserving the possibility for a trusted authority to access sensitive
information, e.g., for audit purposes or compliance with financial regulations.
  NickPay builds upon the Nicknames for Group Signatures (NGS) scheme, a new
signing system based on dynamic ``nicknames'' for signers that extends the
schemes of group signatures and signatures with flexible public keys.
  NGS enables identified group members to expose their flexible public keys,
thus allowing direct and natural applications such as auditable private payment
systems, NickPay being a blockchain-based prototype of these.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.19819v1">Domain-incremental White Blood Cell Classification with Privacy-aware
  Continual Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-03-25T16:30:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pratibha Kumari, Afshin Bozorgpour, Daniel Reisenbüchler, Edgar Jost, Martina Crysandt, Christian Matek, Dorit Merhof</p>
    <p><b>Summary:</b> White blood cell (WBC) classification plays a vital role in hematology for
diagnosing various medical conditions. However, it faces significant challenges
due to domain shifts caused by variations in sample sources (e.g., blood or
bone marrow) and differing imaging conditions across hospitals. Traditional
deep learning models often suffer from catastrophic forgetting in such dynamic
environments, while foundation models, though generally robust, experience
performance degradation when the distribution of inference data differs from
that of the training data. To address these challenges, we propose a generative
replay-based Continual Learning (CL) strategy designed to prevent forgetting in
foundation models for WBC classification. Our method employs lightweight
generators to mimic past data with a synthetic latent representation to enable
privacy-preserving replay. To showcase the effectiveness, we carry out
extensive experiments with a total of four datasets with different task
ordering and four backbone models including ResNet50, RetCCL, CTransPath, and
UNI. Experimental results demonstrate that conventional fine-tuning methods
degrade performance on previously learned tasks and struggle with domain
shifts. In contrast, our continual learning strategy effectively mitigates
catastrophic forgetting, preserving model performance across varying domains.
This work presents a practical solution for maintaining reliable WBC
classification in real-world clinical settings, where data distributions
frequently evolve.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.19453v1">Average consensus with resilience and privacy guarantees without losing
  accuracy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E">
  <p><b>Published on:</b> 2025-03-25T08:41:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guilherme Ramos, Daniel Silvestre, André M. H. Teixeira, Sérgio Pequito</p>
    <p><b>Summary:</b> This paper addresses the challenge of achieving private and resilient average
consensus among a group of discrete-time networked agents without compromising
accuracy. State-of-the-art solutions to attain privacy and resilient consensus
entail an explicit trade-off between the two with an implicit compromise on
accuracy. In contrast, in the present work, we propose a methodology that
avoids trade-offs between privacy, resilience, and accuracy. We design a
methodology that, under certain conditions, enables non-faulty agents, i.e.,
agents complying with the established protocol, to reach average consensus in
the presence of faulty agents, while keeping the non-faulty agents' initial
states private. For privacy, agents strategically add noise to obscure their
original state, while later withdrawing a function of it to ensure accuracy.
Besides, and unlikely many consensus methods, our approach does not require
each agent to compute the left-eigenvector of the dynamics matrix associated
with the eigenvalue one. Moreover, the proposed framework has a polynomial time
complexity relative to the number of agents and the maximum quantity of faulty
agents. Finally, we illustrate our method with examples covering diverse faulty
agents scenarios.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.18729v1">Two Types of Data Privacy Controls</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-03-24T14:37:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Eman Alashwali</p>
    <p><b>Summary:</b> Users share a vast amount of data while using web and mobile applications.
Most service providers such as email and social media providers provide users
with privacy controls, which aim to give users the means to control what, how,
when, and with whom, users share data. Nevertheless, it is not uncommon to hear
users say that they feel they have lost control over their data on the web.
  This article aims to shed light on the often overlooked difference between
two main types of privacy from a control perspective: privacy between a user
and other users, and privacy between a user and institutions. We argue why this
difference is important and what we need to do from here.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.18008v1">Personalized Language Models via Privacy-Preserving Evolutionary Model
  Merging</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Neural and Evolutionary Computing-5BC0EB">
  <p><b>Published on:</b> 2025-03-23T09:46:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kyuyoung Kim, Jinwoo Shin, Jaehyung Kim</p>
    <p><b>Summary:</b> Personalization in large language models (LLMs) seeks to tailor models to
individual user or user group preferences. Prompt-based methods augment queries
with user preference information, whereas training-based methods directly
encode preferences into model parameters for more effective personalization.
Despite achieving some success in personalizing LLMs, prior methods often fail
to directly optimize task-specific metrics and lack explicit
privacy-preservation mechanisms. To address these limitations, we propose
Privacy-Preserving Model Merging via Evolutionary Algorithms (PriME), a novel
approach to personalization that employs gradient-free methods to directly
optimize task-specific metrics while preserving user privacy. By incorporating
privacy preservation into optimization, PriME produces a personalized module
that effectively captures the target user's preferences while minimizing the
privacy risks for the users sharing their private information. Experiments on
the LaMP benchmark show that PriME outperforms both prompt-based and
training-based methods, achieving up to a 45% performance improvement over the
prior art. Further analysis shows that PriME achieves a significantly better
privacy-utility trade-off, highlighting the potential of evolutionary
approaches for privacy-preserving LLM personalization.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.17844v1">Privacy-Preserving Hamming Distance Computation with Property-Preserving
  Hashing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computational Complexity-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-03-22T19:35:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dongfang Zhao</p>
    <p><b>Summary:</b> We study the problem of approximating Hamming distance in sublinear time
under property-preserving hashing (PPH), where only hashed representations of
inputs are available. Building on the threshold evaluation framework of
Fleischhacker, Larsen, and Simkin (EUROCRYPT 2022), we present a sequence of
constructions with progressively improved complexity: a baseline binary search
algorithm, a refined variant with constant repetition per query, and a novel
hash design that enables constant-time approximation without oracle access. Our
results demonstrate that approximate distance recovery is possible under strong
cryptographic guarantees, bridging efficiency and security in similarity
estimation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.17553v1">Autonomous Radiotherapy Treatment Planning Using DOLA: A
  Privacy-Preserving, LLM-Based Optimization Agent</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-03-21T22:01:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Humza Nusrat, Bing Luo, Ryan Hall, Joshua Kim, Hassan Bagher-Ebadian, Anthony Doemer, Benjamin Movsas, Kundan Thind</p>
    <p><b>Summary:</b> Radiotherapy treatment planning is a complex and time-intensive process,
often impacted by inter-planner variability and subjective decision-making. To
address these challenges, we introduce Dose Optimization Language Agent (DOLA),
an autonomous large language model (LLM)-based agent designed for optimizing
radiotherapy treatment plans while rigorously protecting patient privacy. DOLA
integrates the LLaMa3.1 LLM directly with a commercial treatment planning
system, utilizing chain-of-thought prompting, retrieval-augmented generation
(RAG), and reinforcement learning (RL). Operating entirely within secure local
infrastructure, this agent eliminates external data sharing. We evaluated DOLA
using a retrospective cohort of 18 prostate cancer patients prescribed 60 Gy in
20 fractions, comparing model sizes (8 billion vs. 70 billion parameters) and
optimization strategies (No-RAG, RAG, and RAG+RL) over 10 planning iterations.
The 70B model demonstrated significantly improved performance, achieving
approximately 16.4% higher final scores than the 8B model. The RAG approach
outperformed the No-RAG baseline by 19.8%, and incorporating RL accelerated
convergence, highlighting the synergy of retrieval-based memory and
reinforcement learning. Optimal temperature hyperparameter analysis identified
0.4 as providing the best balance between exploration and exploitation. This
proof of concept study represents the first successful deployment of locally
hosted LLM agents for autonomous optimization of treatment plans within a
commercial radiotherapy planning system. By extending human-machine interaction
through interpretable natural language reasoning, DOLA offers a scalable and
privacy-conscious framework, with significant potential for clinical
implementation and workflow improvement.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.17428v1">Would you mind being watched by machines? Privacy concerns in data
  mining</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-03-21T12:01:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vincent C. Müller</p>
    <p><b>Summary:</b> Data mining is not an invasion of privacy because access to data is only by
machines, not by people: this is the argument that is investigated here. The
current importance of this problem is developed in a case study of data mining
in the USA for counterterrorism and other surveillance purposes. After a
clarification of the relevant nature of privacy, it is argued that access by
machines cannot warrant the access to further information, since the analysis
will have to be made either by humans or by machines that understand. It
concludes that the current data mining violates the right to privacy and should
be subject to the standard legal constraints for access to private information
by people.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.17011v1">Privacy Enhanced QKD Networks: Zero Trust Relay Architecture based on
  Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-03-21T10:20:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aitor Brazaola-Vicario, Oscar Lage, Julen Bernabé-Rodríguez, Eduardo Jacob, Jasone Astorga</p>
    <p><b>Summary:</b> Quantum key distribution (QKD) enables unconditionally secure symmetric key
exchange between parties. However, terrestrial fibre-optic links face inherent
distance constraints due to quantum signal degradation. Traditional solutions
to overcome these limits rely on trusted relay nodes, which perform
intermediate re-encryption of keys using one-time pad (OTP) encryption. This
approach, however, exposes keys as plaintext at each relay, requiring
significant trust and stringent security controls at every intermediate node.
These "trusted" relays become a security liability if compromised.
  To address this issue, we propose a zero-trust relay design that applies
fully homomorphic encryption (FHE) to perform intermediate OTP re-encryption
without exposing plaintext keys, effectively mitigating the risks associated
with potentially compromised or malicious relay nodes. Additionally, the
architecture enhances crypto-agility by incorporating external quantum random
number generators, thus decoupling key generation from specific QKD hardware
and reducing vulnerabilities tied to embedded key-generation modules.
  The solution is designed with the existing European Telecommunication
Standards Institute (ETSI) QKD standards in mind, enabling straightforward
integration into current infrastructures. Its feasibility has been successfully
demonstrated through a hybrid network setup combining simulated and
commercially available QKD equipment. The proposed zero-trust architecture thus
significantly advances the scalability and practical security of large-scale
QKD networks, greatly reducing reliance on fully trusted infrastructure.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.16640v1">Visualizing Privacy-Relevant Data Flows in Android Applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-03-20T18:47:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mugdha Khedkar, Michael Schlichtig, Santhosh Mohan, Eric Bodden</p>
    <p><b>Summary:</b> Android applications collecting data from users must protect it according to
the current legal frameworks. Such data protection has become even more
important since in 2018 the European Union rolled out the General Data
Protection Regulation (GDPR). Since app developers are not legal experts, they
find it difficult to integrate privacy-aware practices into source code
development. Despite these legal obligations, developers have limited tool
support to reason about data protection throughout their app development
process.
  This paper explores the use of static program slicing and software
visualization to analyze privacy-relevant data flows in Android apps. We
introduce SliceViz, a web tool that analyzes an Android app by slicing all
privacy-relevant data sources detected in the source code on the back-end. It
then helps developers by visualizing these privacy-relevant program slices.
  We conducted a user study with 12 participants demonstrating that SliceViz
effectively aids developers in identifying privacy-relevant properties in
Android apps.
  Our findings indicate that program slicing can be employed to identify and
reason about privacy-relevant data flows in Android applications. With further
usability improvements, developers can be better equipped to handle
privacy-sensitive information.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.16251v1">RESFL: An Uncertainty-Aware Framework for Responsible Federated Learning
  by Balancing Privacy, Fairness and Utility in Autonomous Vehicles</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2025-03-20T15:46:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dawood Wasif, Terrence J. Moore, Jin-Hee Cho</p>
    <p><b>Summary:</b> Autonomous vehicles (AVs) increasingly rely on Federated Learning (FL) to
enhance perception models while preserving privacy. However, existing FL
frameworks struggle to balance privacy, fairness, and robustness, leading to
performance disparities across demographic groups. Privacy-preserving
techniques like differential privacy mitigate data leakage risks but worsen
fairness by restricting access to sensitive attributes needed for bias
correction. This work explores the trade-off between privacy and fairness in
FL-based object detection for AVs and introduces RESFL, an integrated solution
optimizing both. RESFL incorporates adversarial privacy disentanglement and
uncertainty-guided fairness-aware aggregation. The adversarial component uses a
gradient reversal layer to remove sensitive attributes, reducing privacy risks
while maintaining fairness. The uncertainty-aware aggregation employs an
evidential neural network to weight client updates adaptively, prioritizing
contributions with lower fairness disparities and higher confidence. This
ensures robust and equitable FL model updates. We evaluate RESFL on the FACET
dataset and CARLA simulator, assessing accuracy, fairness, privacy resilience,
and robustness under varying conditions. RESFL improves detection accuracy,
reduces fairness disparities, and lowers privacy attack success rates while
demonstrating superior robustness to adversarial conditions compared to other
approaches.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.16233v1">Empirical Analysis of Privacy-Fairness-Accuracy Trade-offs in Federated
  Learning: A Step Towards Responsible AI</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2025-03-20T15:31:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dawood Wasif, Dian Chen, Sindhuja Madabushi, Nithin Alluru, Terrence J. Moore, Jin-Hee Cho</p>
    <p><b>Summary:</b> Federated Learning (FL) enables collaborative machine learning while
preserving data privacy but struggles to balance privacy preservation (PP) and
fairness. Techniques like Differential Privacy (DP), Homomorphic Encryption
(HE), and Secure Multi-Party Computation (SMC) protect sensitive data but
introduce trade-offs. DP enhances privacy but can disproportionately impact
underrepresented groups, while HE and SMC mitigate fairness concerns at the
cost of computational overhead. This work explores the privacy-fairness
trade-offs in FL under IID (Independent and Identically Distributed) and
non-IID data distributions, benchmarking q-FedAvg, q-MAML, and Ditto on diverse
datasets. Our findings highlight context-dependent trade-offs and offer
guidelines for designing FL systems that uphold responsible AI principles,
ensuring fairness, privacy, and equitable real-world applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.15972v1">TVineSynth: A Truncated C-Vine Copula Generator of Synthetic Tabular
  Data to Balance Privacy and Utility</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2025-03-20T09:16:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Elisabeth Griesbauer, Claudia Czado, Arnoldo Frigessi, Ingrid Hobæk Haff</p>
    <p><b>Summary:</b> We propose TVineSynth, a vine copula based synthetic tabular data generator,
which is designed to balance privacy and utility, using the vine tree structure
and its truncation to do the trade-off. Contrary to synthetic data generators
that achieve DP by globally adding noise, TVineSynth performs a controlled
approximation of the estimated data generating distribution, so that it does
not suffer from poor utility of the resulting synthetic data for downstream
prediction tasks. TVineSynth introduces a targeted bias into the vine copula
model that, combined with the specific tree structure of the vine, causes the
model to zero out privacy-leaking dependencies while relying on those that are
beneficial for utility. Privacy is here measured with membership (MIA) and
attribute inference attacks (AIA). Further, we theoretically justify how the
construction of TVineSynth ensures AIA privacy under a natural privacy measure
for continuous sensitive attributes. When compared to competitor models, with
and without DP, on simulated and on real-world data, TVineSynth achieves a
superior privacy-utility balance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.15966v1">Privacy-Preserving Utilization of Distribution System Flexibility for
  Enhanced TSO-DSO Interoperability: A Novel Machine Learning-Based Optimal
  Power Flow Approach</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2025-03-20T09:08:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Burak Dindar, Can Berk Saner, Hüseyin K. Çakmak, Veit Hagenmeyer</p>
    <p><b>Summary:</b> Due to the transformation of the power system, the effective use of
flexibility from the distribution system (DS) is becoming crucial for efficient
network management. Leveraging this flexibility requires interoperability among
stakeholders, including Transmission System Operators (TSOs) and Distribution
System Operators (DSOs). However, data privacy concerns among stakeholders
present significant challenges for utilizing this flexibility effectively. To
address these challenges, we propose a machine learning (ML)-based method in
which the technical constraints of the DSs are represented by ML models trained
exclusively on non-sensitive data. Using these models, the TSO can solve the
optimal power flow (OPF) problem and directly determine the dispatch of
flexibility-providing units (FPUs), in our case, distributed generators (DGs),
in a single round of communication. To achieve this, we introduce a novel
neural network (NN) architecture specifically designed to efficiently represent
the feasible region of the DSs, ensuring computational effectiveness.
Furthermore, we incorporate various PQ charts rather than idealized ones,
demonstrating that the proposed method is adaptable to a wide range of FPU
characteristics. To assess the effectiveness of the proposed method, we
benchmark it against the standard AC-OPF on multiple DSs with meshed
connections and multiple points of common coupling (PCCs) with varying voltage
magnitudes. The numerical results indicate that the proposed method achieves
performant results while prioritizing data privacy. Additionally, since this
method directly determines the dispatch of FPUs, it eliminates the need for an
additional disaggregation step. By representing the DSs technical constraints
through ML models trained exclusively on non-sensitive data, the transfer of
sensitive information between stakeholders is prevented.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.15870v1">FedSAF: A Federated Learning Framework for Enhanced Gastric Cancer
  Detection and Privacy Preservation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-03-20T05:48:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuxin Miao, Xinyuan Yang, Hongda Fan, Yichun Li, Yishu Hong, Xiechen Guo, Ali Braytee, Weidong Huang, Ali Anaissi</p>
    <p><b>Summary:</b> Gastric cancer is one of the most commonly diagnosed cancers and has a high
mortality rate. Due to limited medical resources, developing machine learning
models for gastric cancer recognition provides an efficient solution for
medical institutions. However, such models typically require large sample sizes
for training and testing, which can challenge patient privacy. Federated
learning offers an effective alternative by enabling model training across
multiple institutions without sharing sensitive patient data. This paper
addresses the limited sample size of publicly available gastric cancer data
with a modified data processing method. This paper introduces FedSAF, a novel
federated learning algorithm designed to improve the performance of existing
methods, particularly in non-independent and identically distributed (non-IID)
data scenarios. FedSAF incorporates attention-based message passing and the
Fisher Information Matrix to enhance model accuracy, while a model splitting
function reduces computation and transmission costs. Hyperparameter tuning and
ablation studies demonstrate the effectiveness of this new algorithm, showing
improvements in test accuracy on gastric cancer datasets, with FedSAF
outperforming existing federated learning methods like FedAMP, FedAvg, and
FedProx. The framework's robustness and generalization ability were further
validated across additional datasets (SEED, BOT, FashionMNIST, and CIFAR-10),
achieving high performance in diverse environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.15818v2">Computation-Efficient and Recognition-Friendly 3D Point Cloud Privacy
  Protection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-03-20T03:09:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haotian Ma, Lin Gu, Siyi Wu, Yingying Zhu</p>
    <p><b>Summary:</b> 3D point cloud has been widely used in applications such as self-driving
cars, robotics, CAD models, etc. To the best of our knowledge, these
applications raised the issue of privacy leakage in 3D point clouds, which has
not been studied well. Different from the 2D image privacy, which is related to
texture and 2D geometric structure, the 3D point cloud is texture-less and only
relevant to 3D geometric structure. In this work, we defined the 3D point cloud
privacy problem and proposed an efficient privacy-preserving framework named
PointFlowGMM that can support downstream classification and segmentation tasks
without seeing the original data. Using a flow-based generative model, the
point cloud is projected into a latent Gaussian mixture distributed subspace.
We further designed a novel angular similarity loss to obfuscate the original
geometric structure and reduce the model size from 767MB to 120MB without a
decrease in recognition performance. The projected point cloud in the latent
space is orthogonally rotated randomly to further protect the original
geometric structure, the class-to-class relationship is preserved after
rotation, thus, the protected point cloud can support the recognition task. We
evaluated our model on multiple datasets and achieved comparable recognition
results on encrypted point clouds compared to the original point clouds.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.15287v1">Distributed Generalized Linear Models: A Privacy-Preserving Approach</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">  
  <p><b>Published on:</b> 2025-03-19T15:07:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Daniel Tinoco, Raquel Menezes, Carlos Baquero</p>
    <p><b>Summary:</b> This paper presents a novel approach to classical linear regression, enabling
model computation from data streams or in a distributed setting while
preserving data privacy in federated environments. We extend this framework to
generalized linear models (GLMs), ensuring scalability and adaptability to
diverse data distributions while maintaining privacy-preserving properties. To
assess the effectiveness of our approach, we conduct numerical studies on both
simulated and real datasets, comparing our method with conventional maximum
likelihood estimation for GLMs using iteratively reweighted least squares. Our
results demonstrate the advantages of the proposed method in distributed and
federated settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.15238v1">Your Signal, Their Data: An Empirical Privacy Analysis of
  Wireless-scanning SDKs in Android</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-03-19T14:15:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aniketh Girish, Joel Reardon, Juan Tapiador, Srdjan Matic, Narseo Vallina-Rodriguez</p>
    <p><b>Summary:</b> Mobile apps frequently use Bluetooth Low Energy (BLE) and WiFi scanning
permissions to discover nearby devices like peripherals and connect to WiFi
Access Points (APs). However, wireless interfaces also serve as a covert proxy
for geolocation data, enabling continuous user tracking and profiling. This
includes technologies like BLE beacons, which are BLE devices broadcasting
unique identifiers to determine devices' indoor physical locations; such
beacons are easily found in shopping centres. Despite the widespread use of
wireless scanning APIs and their potential for privacy abuse, the interplay
between commercial mobile SDKs with wireless sensing and beaconing technologies
remains largely unexplored. In this work, we conduct the first systematic
analysis of 52 wireless-scanning SDKs, revealing their data collection
practices and privacy risks. We develop a comprehensive analysis pipeline that
enables us to detect beacon scanning capabilities, inject wireless events to
trigger app behaviors, and monitor runtime execution on instrumented devices.
Our findings show that 86% of apps integrating these SDKs collect at least one
sensitive data type, including device and user identifiers such as AAID, email,
along with GPS coordinates, WiFi and Bluetooth scan results. We uncover
widespread SDK-to-SDK data sharing and evidence of ID bridging, where
persistent and resettable identifiers are shared and synchronized within SDKs
embedded in applications to potentially construct detailed mobility profiles,
compromising user anonymity and enabling long-term tracking. We provide
evidence of key actors engaging in these practices and conclude by proposing
mitigation strategies such as stronger SDK sandboxing, stricter enforcement of
platform policies, and improved transparency mechanisms to limit unauthorized
tracking.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.15015v1">OFL: Opportunistic Federated Learning for Resource-Heterogeneous and
  Privacy-Aware Devices</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-03-19T09:12:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yunlong Mao, Mingyang Niu, Ziqin Dang, Chengxi Li, Hanning Xia, Yuejuan Zhu, Haoyu Bian, Yuan Zhang, Jingyu Hua, Sheng Zhong</p>
    <p><b>Summary:</b> Efficient and secure federated learning (FL) is a critical challenge for
resource-limited devices, especially mobile devices. Existing secure FL
solutions commonly incur significant overhead, leading to a contradiction
between efficiency and security. As a result, these two concerns are typically
addressed separately. This paper proposes Opportunistic Federated Learning
(OFL), a novel FL framework designed explicitly for resource-heterogenous and
privacy-aware FL devices, solving efficiency and security problems jointly. OFL
optimizes resource utilization and adaptability across diverse devices by
adopting a novel hierarchical and asynchronous aggregation strategy. OFL
provides strong security by introducing a differentially private and
opportunistic model updating mechanism for intra-cluster model aggregation and
an advanced threshold homomorphic encryption scheme for inter-cluster
aggregation. Moreover, OFL secures global model aggregation by implementing
poisoning attack detection using frequency analysis while keeping models
encrypted. We have implemented OFL in a real-world testbed and evaluated OFL
comprehensively. The evaluation results demonstrate that OFL achieves
satisfying model performance and improves efficiency and security,
outperforming existing solutions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.14877v1">Synthesizing Grid Data with Cyber Resilience and Privacy Guarantees</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2025-03-19T04:11:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shengyang Wu, Vladimir Dvorkin</p>
    <p><b>Summary:</b> Differential privacy (DP) provides a principled approach to synthesizing data
(e.g., loads) from real-world power systems while limiting the exposure of
sensitive information. However, adversaries may exploit synthetic data to
calibrate cyberattacks on the source grids. To control these risks, we propose
new DP algorithms for synthesizing data that provide the source grids with both
cyber resilience and privacy guarantees. The algorithms incorporate both normal
operation and attack optimization models to balance the fidelity of synthesized
data and cyber resilience. The resulting post-processing optimization is
reformulated as a robust optimization problem, which is compatible with the
exponential mechanism of DP to moderate its computational burden.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.15550v2">Zero-Knowledge Federated Learning: A New Trustworthy and
  Privacy-Preserving Distributed Learning Paradigm</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-03-18T06:21:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuxin Jin, Taotao Wang, Qing Yang, Long Shi, Shengli Zhang</p>
    <p><b>Summary:</b> Federated Learning (FL) has emerged as a promising paradigm in distributed
machine learning, enabling collaborative model training while preserving data
privacy. However, despite its many advantages, FL still contends with
significant challenges -- most notably regarding security and trust.
Zero-Knowledge Proofs (ZKPs) offer a potential solution by establishing trust
and enhancing system integrity throughout the FL process. Although several
studies have explored ZKP-based FL (ZK-FL), a systematic framework and
comprehensive analysis are still lacking. This article makes two key
contributions. First, we propose a structured ZK-FL framework that categorizes
and analyzes the technical roles of ZKPs across various FL stages and tasks.
Second, we introduce a novel algorithm, Verifiable Client Selection FL
(Veri-CS-FL), which employs ZKPs to refine the client selection process. In
Veri-CS-FL, participating clients generate verifiable proofs for the
performance metrics of their local models and submit these concise proofs to
the server for efficient verification. The server then selects clients with
high-quality local models for uploading, subsequently aggregating the
contributions from these selected clients. By integrating ZKPs, Veri-CS-FL not
only ensures the accuracy of performance metrics but also fortifies trust among
participants while enhancing the overall efficiency and security of FL systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.13872v1">Empirical Calibration and Metric Differential Privacy in Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-03-18T03:52:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pedro Faustini, Natasha Fernandes, Annabelle McIver, Mark Dras</p>
    <p><b>Summary:</b> NLP models trained with differential privacy (DP) usually adopt the DP-SGD
framework, and privacy guarantees are often reported in terms of the privacy
budget $\epsilon$. However, $\epsilon$ does not have any intrinsic meaning, and
it is generally not possible to compare across variants of the framework. Work
in image processing has therefore explored how to empirically calibrate noise
across frameworks using Membership Inference Attacks (MIAs). However, this kind
of calibration has not been established for NLP. In this paper, we show that
MIAs offer little help in calibrating privacy, whereas reconstruction attacks
are more useful. As a use case, we define a novel kind of directional privacy
based on the von Mises-Fisher (VMF) distribution, a metric DP mechanism that
perturbs angular distance rather than adding (isotropic) Gaussian noise, and
apply this to NLP architectures. We show that, even though formal guarantees
are incomparable, empirical privacy calibration reveals that each mechanism has
different areas of strength with respect to utility-privacy trade-offs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.13816v2">MOSAIC: Generating Consistent, Privacy-Preserving Scenes from Multiple
  Depth Views in Multi-Room Environments</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-03-18T01:50:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhixuan Liu, Haokun Zhu, Rui Chen, Jonathan Francis, Soonmin Hwang, Ji Zhang, Jean Oh</p>
    <p><b>Summary:</b> We introduce a novel diffusion-based approach for generating
privacy-preserving digital twins of multi-room indoor environments from depth
images only. Central to our approach is a novel Multi-view Overlapped Scene
Alignment with Implicit Consistency (MOSAIC) model that explicitly considers
cross-view dependencies within the same scene in the probabilistic sense.
MOSAIC operates through a novel inference-time optimization that avoids error
accumulation common in sequential or single-room constraint in panorama-based
approaches. MOSAIC scales to complex scenes with zero extra training and
provably reduces the variance during denoising processes when more overlapping
views are added, leading to improved generation quality. Experiments show that
MOSAIC outperforms state-of-the-art baselines on image fidelity metrics in
reconstructing complex multi-room environments. Project page is available at:
https://mosaic-cmubig.github.io</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.14539v1">Ethical Implications of AI in Data Collection: Balancing Innovation with
  Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-03-17T14:15:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shahmar Mirishli</p>
    <p><b>Summary:</b> This article examines the ethical and legal implications of artificial
intelligence (AI) driven data collection, focusing on developments from 2023 to
2024. It analyzes recent advancements in AI technologies and their impact on
data collection practices across various sectors. The study compares regulatory
approaches in the European Union, the United States, and China, highlighting
the challenges in creating a globally harmonized framework for AI governance.
Key ethical issues, including informed consent, algorithmic bias, and privacy
protection, are critically assessed in the context of increasingly
sophisticated AI systems. The research explores case studies in healthcare,
finance, and smart cities to illustrate the practical challenges of AI
implementation. It evaluates the effectiveness of current legal frameworks and
proposes solutions encompassing legal and policy recommendations, technical
safeguards, and ethical frameworks. The article emphasizes the need for
adaptive governance and international cooperation to address the global nature
of AI development while balancing innovation with the protection of individual
rights and societal values.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.13173v1">PAUSE: Low-Latency and Privacy-Aware Active User Selection for Federated
  Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2025-03-17T13:50:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ori Peleg, Natalie Lang, Stefano Rini, Nir Shlezinger, Kobi Cohen</p>
    <p><b>Summary:</b> Federated learning (FL) enables multiple edge devices to collaboratively
train a machine learning model without the need to share potentially private
data. Federated learning proceeds through iterative exchanges of model updates,
which pose two key challenges: First, the accumulation of privacy leakage over
time, and second, communication latency. These two limitations are typically
addressed separately: The former via perturbed updates to enhance privacy and
the latter using user selection to mitigate latency - both at the expense of
accuracy. In this work, we propose a method that jointly addresses the
accumulation of privacy leakage and communication latency via active user
selection, aiming to improve the trade-off among privacy, latency, and model
performance. To achieve this, we construct a reward function that accounts for
these three objectives. Building on this reward, we propose a multi-armed
bandit (MAB)-based algorithm, termed Privacy-aware Active User SElection
(PAUSE) which dynamically selects a subset of users each round while ensuring
bounded overall privacy leakage. We establish a theoretical analysis,
systematically showing that the reward growth rate of PAUSE follows that of the
best-known rate in MAB literature. To address the complexity overhead of active
user selection, we propose a simulated annealing-based relaxation of PAUSE and
analyze its ability to approximate the reward-maximizing policy under reduced
complexity. We numerically validate the privacy leakage, associated improved
latency, and accuracy gains of our methods for the federated training in
various scenarios.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.07107v1">Guarding Digital Privacy: Exploring User Profiling and Security
  Enhancements</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-03-17T10:56:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rishika Kohli, Shaifu Gupta, Manoj Singh Gaur</p>
    <p><b>Summary:</b> User profiling, the practice of collecting user information for personalized
recommendations, has become widespread, driving progress in technology.
However, this growth poses a threat to user privacy, as devices often collect
sensitive data without their owners' awareness. This article aims to
consolidate knowledge on user profiling, exploring various approaches and
associated challenges. Through the lens of two companies sharing user data and
an analysis of 18 popular Android applications in India across various
categories, including $\textit{Social, Education, Entertainment, Travel,
Shopping and Others}$, the article unveils privacy vulnerabilities. Further,
the article propose an enhanced machine learning framework, employing decision
trees and neural networks, that improves state-of-the-art classifiers in
detecting personal information exposure. Leveraging the XAI (explainable
artificial intelligence) algorithm LIME (Local Interpretable Model-agnostic
Explanations), it enhances interpretability, crucial for reliably identifying
sensitive data. Results demonstrate a noteworthy performance boost, achieving a
$75.01\%$ accuracy with a reduced training time of $3.62$ seconds for neural
networks. Concluding, the paper suggests research directions to strengthen
digital security measures.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.12958v1">FedSDP: Explainable Differential Privacy in Federated Learning via
  Shapley Values</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-03-17T09:14:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yunbo Li, Jiaping Gui, Yue Wu</p>
    <p><b>Summary:</b> Federated learning (FL) enables participants to store data locally while
collaborating in training, yet it remains vulnerable to privacy attacks, such
as data reconstruction. Existing differential privacy (DP) technologies inject
noise dynamically into the training process to mitigate the impact of excessive
noise. However, this dynamic scheduling is often grounded in factors indirectly
related to privacy, making it difficult to clearly explain the intricate
relationship between dynamic noise adjustments and privacy requirements. To
address this issue, we propose FedSDP, a novel and explainable DP-based privacy
protection mechanism that guides noise injection based on privacy contribution.
Specifically, FedSDP leverages Shapley values to assess the contribution of
private attributes to local model training and dynamically adjusts the amount
of noise injected accordingly. By providing theoretical insights into the
injection of varying scales of noise into local training, FedSDP enhances
interpretability. Extensive experiments demonstrate that FedSDP can achieve a
superior balance between privacy preservation and model performance, surpassing
state-of-the-art (SOTA) solutions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.15548v1">Privacy-Aware RAG: Secure and Isolated Knowledge Retrieval</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-03-17T07:45:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pengcheng Zhou, Yinglun Feng, Zhongliang Yang</p>
    <p><b>Summary:</b> The widespread adoption of Retrieval-Augmented Generation (RAG) systems in
real-world applications has heightened concerns about the confidentiality and
integrity of their proprietary knowledge bases. These knowledge bases, which
play a critical role in enhancing the generative capabilities of Large Language
Models (LLMs), are increasingly vulnerable to breaches that could compromise
sensitive information. To address these challenges, this paper proposes an
advanced encryption methodology designed to protect RAG systems from
unauthorized access and data leakage. Our approach encrypts both textual
content and its corresponding embeddings prior to storage, ensuring that all
data remains securely encrypted. This mechanism restricts access to authorized
entities with the appropriate decryption keys, thereby significantly reducing
the risk of unintended data exposure. Furthermore, we demonstrate that our
encryption strategy preserves the performance and functionality of RAG
pipelines, ensuring compatibility across diverse domains and applications. To
validate the robustness of our method, we provide comprehensive security proofs
that highlight its resilience against potential threats and vulnerabilities.
These proofs also reveal limitations in existing approaches, which often lack
robustness, adaptability, or reliance on open-source models. Our findings
suggest that integrating advanced encryption techniques into the design and
deployment of RAG systems can effectively enhance privacy safeguards. This
research contributes to the ongoing discourse on improving security measures
for AI-driven services and advocates for stricter data protection standards
within RAG architectures.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.12786v1">Privacy-Preserving Biometric Verification with Handwritten Random Digit
  String</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-03-17T03:47:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Peirong Zhang, Yuliang Liu, Songxuan Lai, Hongliang Li, Lianwen Jin</p>
    <p><b>Summary:</b> Handwriting verification has stood as a steadfast identity authentication
method for decades. However, this technique risks potential privacy breaches
due to the inclusion of personal information in handwritten biometrics such as
signatures. To address this concern, we propose using the Random Digit String
(RDS) for privacy-preserving handwriting verification. This approach allows
users to authenticate themselves by writing an arbitrary digit sequence,
effectively ensuring privacy protection. To evaluate the effectiveness of RDS,
we construct a new HRDS4BV dataset composed of online naturally handwritten
RDS. Unlike conventional handwriting, RDS encompasses unconstrained and
variable content, posing significant challenges for modeling consistent
personal writing style. To surmount this, we propose the Pattern Attentive
VErification Network (PAVENet), along with a Discriminative Pattern Mining
(DPM) module. DPM adaptively enhances the recognition of consistent and
discriminative writing patterns, thus refining handwriting style
representation. Through comprehensive evaluations, we scrutinize the
applicability of online RDS verification and showcase a pronounced
outperformance of our model over existing methods. Furthermore, we discover a
noteworthy forgery phenomenon that deviates from prior findings and discuss its
positive impact in countering malicious impostor attacks. Substantially, our
work underscores the feasibility of privacy-preserving biometric verification
and propels the prospects of its broader acceptance and application.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.13550v1">Towards Privacy-Preserving Data-Driven Education: The Potential of
  Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-03-16T14:37:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohammad Khalil, Ronas Shakya, Qinyi Liu</p>
    <p><b>Summary:</b> The increasing adoption of data-driven applications in education such as in
learning analytics and AI in education has raised significant privacy and data
protection concerns. While these challenges have been widely discussed in
previous works, there are still limited practical solutions. Federated learning
has recently been discoursed as a promising privacy-preserving technique, yet
its application in education remains scarce. This paper presents an
experimental evaluation of federated learning for educational data prediction,
comparing its performance to traditional non-federated approaches. Our findings
indicate that federated learning achieves comparable predictive accuracy.
Furthermore, under adversarial attacks, federated learning demonstrates greater
resilience compared to non-federated settings. We summarise that our results
reinforce the value of federated learning as a potential approach for balancing
predictive performance and privacy in educational contexts.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.12464v1">Learning Privacy from Visual Entities</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-03-16T11:39:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alessio Xompero, Andrea Cavallaro</p>
    <p><b>Summary:</b> Subjective interpretation and content diversity make predicting whether an
image is private or public a challenging task. Graph neural networks combined
with convolutional neural networks (CNNs), which consist of 14,000 to 500
millions parameters, generate features for visual entities (e.g., scene and
object types) and identify the entities that contribute to the decision. In
this paper, we show that using a simpler combination of transfer learning and a
CNN to relate privacy with scene types optimises only 732 parameters while
achieving comparable performance to that of graph-based methods. On the
contrary, end-to-end training of graph-based methods can mask the contribution
of individual components to the classification performance. Furthermore, we
show that a high-dimensional feature vector, extracted with CNNs for each
visual entity, is unnecessary and complexifies the model. The graph component
has also negligible impact on performance, which is driven by fine-tuning the
CNN to optimise image features for privacy nodes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.16516v1">Using LLMs for Automated Privacy Policy Analysis: Prompt Engineering,
  Fine-Tuning and Explainability</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-03-16T10:50:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuxin Chen, Peng Tang, Weidong Qiu, Shujun Li</p>
    <p><b>Summary:</b> Privacy policies are widely used by digital services and often required for
legal purposes. Many machine learning based classifiers have been developed to
automate detection of different concepts in a given privacy policy, which can
help facilitate other automated tasks such as producing a more reader-friendly
summary and detecting legal compliance issues. Despite the successful
applications of large language models (LLMs) to many NLP tasks in various
domains, there is very little work studying the use of LLMs for automated
privacy policy analysis, therefore, if and how LLMs can help automate privacy
policy analysis remains under-explored. To fill this research gap, we conducted
a comprehensive evaluation of LLM-based privacy policy concept classifiers,
employing both prompt engineering and LoRA (low-rank adaptation) fine-tuning,
on four state-of-the-art (SOTA) privacy policy corpora and taxonomies. Our
experimental results demonstrated that combining prompt engineering and
fine-tuning can make LLM-based classifiers outperform other SOTA methods,
\emph{significantly} and \emph{consistently} across privacy policy
corpora/taxonomies and concepts. Furthermore, we evaluated the explainability
of the LLM-based classifiers using three metrics: completeness, logicality, and
comprehensibility. For all three metrics, a score exceeding 91.1\% was observed
in our evaluation, indicating that LLMs are not only useful to improve the
classification performance, but also to enhance the explainability of detection
results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.12347v1">Synthesizing Privacy-Preserving Text Data via Finetuning without
  Finetuning Billion-Scale LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-03-16T04:00:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bowen Tan, Zheng Xu, Eric Xing, Zhiting Hu, Shanshan Wu</p>
    <p><b>Summary:</b> Synthetic data offers a promising path to train models while preserving data
privacy. Differentially private (DP) finetuning of large language models (LLMs)
as data generator is effective, but is impractical when computation resources
are limited. Meanwhile, prompt-based methods such as private evolution, depend
heavily on the manual prompts, and ineffectively use private information in
their iterative data selection process. To overcome these limitations, we
propose CTCL (Data Synthesis with ConTrollability and CLustering), a novel
framework for generating privacy-preserving synthetic data without extensive
prompt engineering or billion-scale LLM finetuning. CTCL pretrains a
lightweight 140M conditional generator and a clustering-based topic model on
large-scale public data. To further adapt to the private domain, the generator
is DP finetuned on private data for fine-grained textual information, while the
topic model extracts a DP histogram representing distributional information.
The DP generator then samples according to the DP histogram to synthesize a
desired number of data examples. Evaluation across five diverse domains
demonstrates the effectiveness of our framework, particularly in the strong
privacy regime. Systematic ablation validates the design of each framework
component and highlights the scalability of our approach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.12314v1">Empirical Privacy Variance</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-03-16T01:43:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuzheng Hu, Fan Wu, Ruicheng Xian, Yuhang Liu, Lydia Zakynthinou, Pritish Kamath, Chiyuan Zhang, David Forsyth</p>
    <p><b>Summary:</b> We propose the notion of empirical privacy variance and study it in the
context of differentially private fine-tuning of language models. Specifically,
we show that models calibrated to the same $(\varepsilon, \delta)$-DP guarantee
using DP-SGD with different hyperparameter configurations can exhibit
significant variations in empirical privacy, which we quantify through the lens
of memorization. We investigate the generality of this phenomenon across
multiple dimensions and discuss why it is surprising and relevant. Through
regression analysis, we examine how individual and composite hyperparameters
influence empirical privacy. The results reveal a no-free-lunch trade-off:
existing practices of hyperparameter tuning in DP-SGD, which focus on
optimizing utility under a fixed privacy budget, often come at the expense of
empirical privacy. To address this, we propose refined heuristics for
hyperparameter selection that explicitly account for empirical privacy, showing
that they are both precise and practically useful. Finally, we take preliminary
steps to understand empirical privacy variance. We propose two hypotheses,
identify limitations in existing techniques like privacy auditing, and outline
open questions for future research.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.12232v1">From Laboratory to Real World: A New Benchmark Towards Privacy-Preserved
  Visible-Infrared Person Re-Identification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-03-15T18:56:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yan Jiang, Hao Yu, Xu Cheng, Haoyu Chen, Zhaodong Sun, Guoying Zhao</p>
    <p><b>Summary:</b> Aiming to match pedestrian images captured under varying lighting conditions,
visible-infrared person re-identification (VI-ReID) has drawn intensive
research attention and achieved promising results. However, in real-world
surveillance contexts, data is distributed across multiple devices/entities,
raising privacy and ownership concerns that make existing centralized training
impractical for VI-ReID. To tackle these challenges, we propose L2RW, a
benchmark that brings VI-ReID closer to real-world applications. The rationale
of L2RW is that integrating decentralized training into VI-ReID can address
privacy concerns in scenarios with limited data-sharing regulation.
Specifically, we design protocols and corresponding algorithms for different
privacy sensitivity levels. In our new benchmark, we ensure the model training
is done in the conditions that: 1) data from each camera remains completely
isolated, or 2) different data entities (e.g., data controllers of a certain
region) can selectively share the data. In this way, we simulate scenarios with
strict privacy constraints which is closer to real-world conditions. Intensive
experiments with various server-side federated algorithms are conducted,
showing the feasibility of decentralized VI-ReID training. Notably, when
evaluated in unseen domains (i.e., new data entities), our L2RW, trained with
isolated data (privacy-preserved), achieves performance comparable to SOTAs
trained with shared data (privacy-unrestricted). We hope this work offers a
novel research entry for deploying VI-ReID that fits real-world scenarios and
can benefit the community.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.12226v1">Research on Large Language Model Cross-Cloud Privacy Protection and
  Collaborative Training based on Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-03-15T18:44:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ze Yang, Yihong Jin, Yihan Zhang, Juntian Liu, Xinhe Xu</p>
    <p><b>Summary:</b> The fast development of large language models (LLMs) and popularization of
cloud computing have led to increasing concerns on privacy safeguarding and
data security of cross-cloud model deployment and training as the key
challenges. We present a new framework for addressing these issues along with
enabling privacy preserving collaboration on training between distributed
clouds based on federated learning. Our mechanism encompasses cutting-edge
cryptographic primitives, dynamic model aggregation techniques, and cross-cloud
data harmonization solutions to enhance security, efficiency, and scalability
to the traditional federated learning paradigm. Furthermore, we proposed a
hybrid aggregation scheme to mitigate the threat of Data Leakage and to
optimize the aggregation of model updates, thus achieving substantial
enhancement on the model effectiveness and stability. Experimental results
demonstrate that the training efficiency, privacy protection, and model
accuracy of the proposed model compare favorably to those of the traditional
federated learning method.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.12225v1">Interpretation Gaps in LLM-Assisted Comprehension of Privacy Documents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2025-03-15T18:43:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rinku Dewri</p>
    <p><b>Summary:</b> This article explores the gaps that can manifest when using a large language
model (LLM) to obtain simplified interpretations of data practices from a
complex privacy policy. We exemplify these gaps to showcase issues in accuracy,
completeness, clarity and representation, while advocating for continued
research to realize an LLM's true potential in revolutionizing privacy
management through personal assistants and automated compliance checking.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.12220v2">PA-CFL: Privacy-Adaptive Clustered Federated Learning for
  Transformer-Based Sales Forecasting on Heterogeneous Retail Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-03-15T18:07:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yunbo Long, Liming Xu, Ge Zheng, Alexandra Brintrup</p>
    <p><b>Summary:</b> Federated learning (FL) enables retailers to share model parameters for
demand forecasting while maintaining privacy. However, heterogeneous data
across diverse regions, driven by factors such as varying consumer behavior,
poses challenges to the effectiveness of federated learning. To tackle this
challenge, we propose Privacy-Adaptive Clustered Federated Learning (PA-CFL)
tailored for demand forecasting on heterogeneous retail data. By leveraging
differential privacy and feature importance distribution, PA-CFL groups
retailers into distinct ``bubbles'', each forming its own federated learning
system to effectively isolate data heterogeneity. Within each bubble,
Transformer models are designed to predict local sales for each client. Our
experiments demonstrate that PA-CFL significantly surpasses FedAvg and
outperforms local learning in demand forecasting performance across all
participating clients. Compared to local learning, PA-CFL achieves a 5.4%
improvement in R^2, a 69% reduction in RMSE, and a 45% decrease in MAE. Our
approach enables effective FL through adaptive adjustments to diverse noise
levels and the range of clients participating in each bubble. By grouping
participants and proactively filtering out high-risk clients, PA-CFL mitigates
potential threats to the FL system. The findings demonstrate PA-CFL's ability
to enhance federated learning in time series prediction tasks with
heterogeneous data, achieving a balance between forecasting accuracy and
privacy preservation in retail applications. Additionally, PA-CFL's capability
to detect and neutralize poisoned data from clients enhances the system's
robustness and reliability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.12156v1">Efficient and Privacy-Preserved Link Prediction via Condensed Graphs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B">
  <p><b>Published on:</b> 2025-03-15T14:54:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yunbo Long, Liming Xu, Alexandra Brintrup</p>
    <p><b>Summary:</b> Link prediction is crucial for uncovering hidden connections within complex
networks, enabling applications such as identifying potential customers and
products. However, this research faces significant challenges, including
concerns about data privacy, as well as high computational and storage costs,
especially when dealing with large-scale networks. Condensed graphs, which are
much smaller than the original graphs while retaining essential information,
has become an effective solution to both maintain data utility and preserve
privacy. Existing methods, however, initialize synthetic graphs through random
node selection without considering node connectivity, and are mainly designed
for node classification tasks. As a result, their potential for
privacy-preserving link prediction remains largely unexplored. We introduce
HyDRO\textsuperscript{+}, a graph condensation method guided by algebraic
Jaccard similarity, which leverages local connectivity information to optimize
condensed graph structures. Extensive experiments on four real-world networks
show that our method outperforms state-of-the-art methods and even the original
networks in balancing link prediction accuracy and privacy preservation.
Moreover, our method achieves nearly 20* faster training and reduces storage
requirements by 452*, as demonstrated on the Computers dataset, compared to
link prediction on the original networks. This work represents the first
attempt to leverage condensed graphs for privacy-preserving link prediction
information sharing in real-world complex networks. It offers a promising
pathway for preserving link prediction information while safeguarding privacy,
advancing the use of graph condensation in large-scale networks with privacy
concerns.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.12045v2">Auditing Differential Privacy in the Black-Box Setting</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-03-15T08:34:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kaining Shi, Cong Ma</p>
    <p><b>Summary:</b> This paper introduces a novel theoretical framework for auditing differential
privacy (DP) in a black-box setting. Leveraging the concept of $f$-differential
privacy, we explicitly define type I and type II errors and propose an auditing
mechanism based on conformal inference. Our approach robustly controls the type
I error rate under minimal assumptions. Furthermore, we establish a fundamental
impossibility result, demonstrating the inherent difficulty of simultaneously
controlling both type I and type II errors without additional assumptions.
Nevertheless, under a monotone likelihood ratio (MLR) assumption, our auditing
mechanism effectively controls both errors. We also extend our method to
construct valid confidence bands for the trade-off function in the
finite-sample regime.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.11950v2">Privacy Ethics Alignment in AI: A Stakeholder-Centric Based Framework
  for Ethical AI</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-03-15T01:42:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ankur Barthwal, Molly Campbell, Ajay Kumar Shrestha</p>
    <p><b>Summary:</b> The increasing integration of Artificial Intelligence (AI) in digital
ecosystems has reshaped privacy dynamics, particularly for young digital
citizens navigating data-driven environments. This study explores evolving
privacy concerns across three key stakeholder groups, digital citizens (ages
16-19), parents/educators, and AI professionals, and assesses differences in
data ownership, trust, transparency, parental mediation, education, and
risk-benefit perceptions. Employing a grounded theory methodology, this
research synthesizes insights from 482 participants through structured surveys,
qualitative interviews, and focus groups. The findings reveal distinct privacy
expectations: Young users emphasize autonomy and digital freedom, while parents
and educators advocate for regulatory oversight and AI literacy programs. AI
professionals, in contrast, prioritize the balance between ethical system
design and technological efficiency. The data further highlights gaps in AI
literacy and transparency, emphasizing the need for comprehensive,
stakeholder-driven privacy frameworks that accommodate diverse user needs.
Using comparative thematic analysis, this study identifies key tensions in
privacy governance and develops the novel Privacy-Ethics Alignment in AI
(PEA-AI) model, which structures privacy decision-making as a dynamic
negotiation between stakeholders. By systematically analyzing themes such as
transparency, user control, risk perception, and parental mediation, this
research provides a scalable, adaptive foundation for AI governance, ensuring
that privacy protections evolve alongside emerging AI technologies and
youth-centric digital interactions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.11947v1">Ethical AI for Young Digital Citizens: A Call to Action on Privacy
  Governance</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-03-15T01:35:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Austin Shouli, Ankur Barthwal, Molly Campbell, Ajay Kumar Shrestha</p>
    <p><b>Summary:</b> The rapid expansion of Artificial Intelligence (AI) in digital platforms used
by youth has created significant challenges related to privacy, autonomy, and
data protection. While AI-driven personalization offers enhanced user
experiences, it often operates without clear ethical boundaries, leaving young
users vulnerable to data exploitation and algorithmic biases. This paper
presents a call to action for ethical AI governance, advocating for a
structured framework that ensures youth-centred privacy protections,
transparent data practices, and regulatory oversight. We outline key areas
requiring urgent intervention, including algorithmic transparency, privacy
education, parental data-sharing ethics, and accountability measures. Through
this approach, we seek to empower youth with greater control over their digital
identities and propose actionable strategies for policymakers, AI developers,
and educators to build a fairer and more accountable AI ecosystem.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.11920v1">Practical Implications of Implementing Local Differential Privacy for
  Smart grids</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-03-14T23:11:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Khadija Hafeez, Mubashir Husain Rehmani, Sumita Mishra, Donna OShea</p>
    <p><b>Summary:</b> Recent smart grid advancements enable near-realtime reporting of electricity
consumption, raising concerns about consumer privacy. Differential privacy (DP)
has emerged as a viable privacy solution, where a calculated amount of noise is
added to the data by a trusted third party, or individual users perturb their
information locally, and only send the randomized data to an aggregator for
analysis safeguarding users and aggregators privacy. However, the practical
implementation of a Local DP-based (LDP) privacy model for smart grids has its
own challenges. In this paper, we discuss the challenges of implementing an
LDP-based model for smart grids. We compare existing LDP mechanisms in smart
grids for privacy preservation of numerical data and discuss different methods
for selecting privacy parameters in the existing literature, their limitations
and the non-existence of an optimal method for selecting the privacy
parameters. We also discuss the challenges of translating theoretical models of
LDP into a practical setting for smart grids for different utility functions,
the impact of the size of data set on privacy and accuracy, and vulnerability
of LDP-based smart grids to manipulation attacks. Finally, we discuss future
directions in research for better practical applications in LDP based models
for smart grids.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2503.11850v1">Local Pan-Privacy for Federated Analytics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-03-14T20:18:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vitaly Feldman, Audra McMillan, Guy N. Rothblum, Kunal Talwar</p>
    <p><b>Summary:</b> Pan-privacy was proposed by Dwork et al. as an approach to designing a
private analytics system that retains its privacy properties in the face of
intrusions that expose the system's internal state. Motivated by federated
telemetry applications, we study local pan-privacy, where privacy should be
retained under repeated unannounced intrusions on the local state. We consider
the problem of monitoring the count of an event in a federated system, where
event occurrences on a local device should be hidden even from an intruder on
that device. We show that under reasonable constraints, the goal of providing
information-theoretic differential privacy under intrusion is incompatible with
collecting telemetry information. We then show that this problem can be solved
in a scalable way using standard cryptographic primitives.</p>
  </details>
</div>

