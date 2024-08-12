
<h2>2024-08</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2408.05212v1">Preserving Privacy in Large Language Models: A Survey on Current Threats
  and Solutions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-08-10T05:41:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Michele Miranda, Elena Sofia Ruzzetti, Andrea Santilli, Fabio Massimo Zanzotto, Sébastien Bratières, Emanuele Rodolà</p>
    <p><b>Summary:</b> Large Language Models (LLMs) represent a significant advancement in
artificial intelligence, finding applications across various domains. However,
their reliance on massive internet-sourced datasets for training brings notable
privacy issues, which are exacerbated in critical domains (e.g., healthcare).
Moreover, certain application-specific scenarios may require fine-tuning these
models on private data. This survey critically examines the privacy threats
associated with LLMs, emphasizing the potential for these models to memorize
and inadvertently reveal sensitive information. We explore current threats by
reviewing privacy attacks on LLMs and propose comprehensive solutions for
integrating privacy mechanisms throughout the entire learning pipeline. These
solutions range from anonymizing training datasets to implementing differential
privacy during training or inference and machine unlearning after training. Our
comprehensive review of existing literature highlights ongoing challenges,
available tools, and future directions for preserving privacy in LLMs. This
work aims to guide the development of more secure and trustworthy AI systems by
providing a thorough understanding of privacy preservation methods and their
effectiveness in mitigating risks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2408.05092v1">PriPHiT: Privacy-Preserving Hierarchical Training of Deep Neural
  Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">  
  <p><b>Published on:</b> 2024-08-09T14:33:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yamin Sepehri, Pedram Pad, Pascal Frossard, L. Andrea Dunbar</p>
    <p><b>Summary:</b> The training phase of deep neural networks requires substantial resources and
as such is often performed on cloud servers. However, this raises privacy
concerns when the training dataset contains sensitive content, e.g., face
images. In this work, we propose a method to perform the training phase of a
deep learning model on both an edge device and a cloud server that prevents
sensitive content being transmitted to the cloud while retaining the desired
information. The proposed privacy-preserving method uses adversarial early
exits to suppress the sensitive content at the edge and transmits the
task-relevant information to the cloud. This approach incorporates noise
addition during the training phase to provide a differential privacy guarantee.
We extensively test our method on different facial datasets with diverse face
attributes using various deep learning architectures, showcasing its
outstanding performance. We also demonstrate the effectiveness of privacy
preservation through successful defenses against different white-box and deep
reconstruction attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2408.04931v1">Privacy-Preserved Taxi Demand Prediction System Utilizing Distributed
  Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-08-09T08:24:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ren Ozeki, Haruki Yonekura, Hamada Rizk, Hirozumi Yamaguchi</p>
    <p><b>Summary:</b> Accurate taxi-demand prediction is essential for optimizing taxi operations
and enhancing urban transportation services. However, using customers' data in
these systems raises significant privacy and security concerns. Traditional
federated learning addresses some privacy issues by enabling model training
without direct data exchange but often struggles with accuracy due to varying
data distributions across different regions or service providers. In this
paper, we propose CC-Net: a novel approach using collaborative learning
enhanced with contrastive learning for taxi-demand prediction. Our method
ensures high performance by enabling multiple parties to collaboratively train
a demand-prediction model through hierarchical federated learning. In this
approach, similar parties are clustered together, and federated learning is
applied within each cluster. The similarity is defined without data exchange,
ensuring privacy and security. We evaluated our approach using real-world data
from five taxi service providers in Japan over fourteen months. The results
demonstrate that CC-Net maintains the privacy of customers' data while
improving prediction accuracy by at least 2.2% compared to existing techniques.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2408.04888v1">Locally Private Histograms in All Privacy Regimes</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Discrete Mathematics-04E762">
  <p><b>Published on:</b> 2024-08-09T06:22:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Clément L. Canonne, Abigail Gentle</p>
    <p><b>Summary:</b> Frequency estimation, a.k.a. histograms, is a workhorse of data analysis, and
as such has been thoroughly studied under differentially privacy. In
particular, computing histograms in the local model of privacy has been the
focus of a fruitful recent line of work, and various algorithms have been
proposed, achieving the order-optimal $\ell_\infty$ error in the high-privacy
(small $\varepsilon$) regime while balancing other considerations such as time-
and communication-efficiency. However, to the best of our knowledge, the
picture is much less clear when it comes to the medium- or low-privacy regime
(large $\varepsilon$), despite its increased relevance in practice. In this
paper, we investigate locally private histograms, and the very related
distribution learning task, in this medium-to-low privacy regime, and establish
near-tight (and somewhat unexpected) bounds on the $\ell_\infty$ error
achievable. Our theoretical findings emerge from a novel analysis, which
appears to improve bounds across the board for the locally private histogram
problem. We back our theoretical findings by an empirical comparison of
existing algorithms in all privacy regimes, to assess their typical performance
and behaviour beyond the worst-case setting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2408.04684v1">Moving beyond privacy and airspace safety: Guidelines for just drones in
  policing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-08-08T09:04:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mateusz Dolata, Gerhard Schwabe</p>
    <p><b>Summary:</b> The use of drones offers police forces potential gains in efficiency and
safety. However, their use may also harm public perception of the police if
drones are refused. Therefore, police forces should consider the perception of
bystanders and broader society to maximize drones' potential. This article
examines the concerns expressed by members of the public during a field trial
involving 52 test participants. Analysis of the group interviews suggests that
their worries go beyond airspace safety and privacy, broadly discussed in
existing literature and regulations. The interpretation of the results
indicates that the perceived justice of drone use is a significant factor in
acceptance. Leveraging the concept of organizational justice and data
collected, we propose a catalogue of guidelines for just operation of drones to
supplement the existing policy. We present the organizational justice
perspective as a framework to integrate the concerns of the public and
bystanders into legal work. Finally, we discuss the relevance of justice for
the legitimacy of the police's actions and provide implications for research
and practice.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2408.04315v1">Federated Cubic Regularized Newton Learning with
  Sparsification-amplified Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36"> 
  <p><b>Published on:</b> 2024-08-08T08:48:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wei Huo, Changxin Liu, Kemi Ding, Karl Henrik Johansson, Ling Shi</p>
    <p><b>Summary:</b> This paper investigates the use of the cubic-regularized Newton method within
a federated learning framework while addressing two major concerns that
commonly arise in federated learning: privacy leakage and communication
bottleneck. We introduce a federated learning algorithm called Differentially
Private Federated Cubic Regularized Newton (DP-FCRN). By leveraging
second-order techniques, our algorithm achieves lower iteration complexity
compared to first-order methods. We also incorporate noise perturbation during
local computations to ensure privacy. Furthermore, we employ sparsification in
uplink transmission, which not only reduces the communication costs but also
amplifies the privacy guarantee. Specifically, this approach reduces the
necessary noise intensity without compromising privacy protection. We analyze
the convergence properties of our algorithm and establish the privacy
guarantee. Finally, we validate the effectiveness of the proposed algorithm
through experiments on a benchmark dataset.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2408.04188v1">Trustworthy Semantic-Enabled 6G Communication: A Task-oriented and
  Privacy-preserving Perspective</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36"> 
  <p><b>Published on:</b> 2024-08-08T03:16:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuaishuai Guo, Anbang Zhang, Yanhu Wang, Chenyuan Feng, Tony Q. S. Quek</p>
    <p><b>Summary:</b> Trustworthy task-oriented semantic communication (ToSC) emerges as an
innovative approach in the 6G landscape, characterized by the transmission of
only vital information that is directly pertinent to a specific task. While
ToSC offers an efficient mode of communication, it concurrently raises concerns
regarding privacy, as sophisticated adversaries might possess the capability to
reconstruct the original data from the transmitted features. This article
provides an in-depth analysis of privacy-preserving strategies specifically
designed for ToSC relying on deep neural network-based joint source and channel
coding (DeepJSCC). The study encompasses a detailed comparative assessment of
trustworthy feature perturbation methods such as differential privacy and
encryption, alongside intrinsic security incorporation approaches like
adversarial learning to train the JSCC and learning-based vector quantization
(LBVQ). This comparative analysis underscores the integration of advanced
explainable learning algorithms into communication systems, positing a new
benchmark for privacy standards in the forthcoming 6G era.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2408.03897v1">Speech privacy-preserving methods using secret key for convolutional
  neural network models and their robustness evaluation</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36">
  <p><b>Published on:</b> 2024-08-07T16:51:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shoko Niwa, Sayaka Shiota, Hitoshi Kiya</p>
    <p><b>Summary:</b> In this paper, we propose privacy-preserving methods with a secret key for
convolutional neural network (CNN)-based models in speech processing tasks. In
environments where untrusted third parties, like cloud servers, provide
CNN-based systems, ensuring the privacy of speech queries becomes essential.
This paper proposes encryption methods for speech queries using secret keys and
a model structure that allows for encrypted queries to be accepted without
decryption. Our approach introduces three types of secret keys: Shuffling,
Flipping, and random orthogonal matrix (ROM). In experiments, we demonstrate
that when the proposed methods are used with the correct key, identification
performance did not degrade. Conversely, when an incorrect key is used, the
performance significantly decreased. Particularly, with the use of ROM, we show
that even with a relatively small key space, high privacy-preserving
performance can be maintained many speech processing tasks. Furthermore, we
also demonstrate the difficulty of recovering original speech from encrypted
queries in various robustness evaluations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2408.03578v1">Unraveling Privacy Threat Modeling Complexity: Conceptual Privacy
  Analysis Layers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-08-07T06:30:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kim Wuyts, Avi Douglen</p>
    <p><b>Summary:</b> Analyzing privacy threats in software products is an essential part of
software development to ensure systems are privacy-respecting; yet it is still
a far from trivial activity. While there have been many advancements in the
past decade, they tend to focus on describing 'what' the threats are. What
isn't entirely clear yet is 'how' to actually find these threats. Privacy is a
complex domain. We propose to use four conceptual layers (feature, ecosystem,
business context, and environment) to capture this privacy complexity. These
layers can be used as a frame to structure and specify the privacy analysis
support in a more tangible and actionable way, thereby improving applicability
of the analysis process.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2408.03185v1">MaskAnyone Toolkit: Offering Strategies for Minimizing Privacy Risks and
  Maximizing Utility in Audio-Visual Data Archiving</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Multimedia-5BC0EB">
  <p><b>Published on:</b> 2024-08-06T13:35:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Babajide Alamu Owoyele, Martin Schilling, Rohan Sawahn, Niklas Kaemer, Pavel Zherebenkov, Bhuvanesh Verma, Wim Pouw, Gerard de Melo</p>
    <p><b>Summary:</b> This paper introduces MaskAnyone, a novel toolkit designed to navigate some
privacy and ethical concerns of sharing audio-visual data in research.
MaskAnyone offers a scalable, user-friendly solution for de-identifying
individuals in video and audio content through face-swapping and voice
alteration, supporting multi-person masking and real-time bulk processing. By
integrating this tool within research practices, we aim to enhance data
reproducibility and utility in social science research. Our approach draws on
Design Science Research, proposing that MaskAnyone can facilitate safer data
sharing and potentially reduce the storage of fully identifiable data. We
discuss the development and capabilities of MaskAnyone, explore its integration
into ethical research practices, and consider the broader implications of
audio-visual data masking, including issues of consent and the risk of misuse.
The paper concludes with a preliminary evaluation framework for assessing the
effectiveness and ethical integration of masking tools in such research
settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2408.02927v1">HARMONIC: Harnessing LLMs for Tabular Data Synthesis and Privacy
  Protection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-08-06T03:21:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuxin Wang, Duanyu Feng, Yongfu Dai, Zhengyu Chen, Jimin Huang, Sophia Ananiadou, Qianqian Xie, Hao Wang</p>
    <p><b>Summary:</b> Data serves as the fundamental foundation for advancing deep learning,
particularly tabular data presented in a structured format, which is highly
conducive to modeling. However, even in the era of LLM, obtaining tabular data
from sensitive domains remains a challenge due to privacy or copyright
concerns. Hence, exploring how to effectively use models like LLMs to generate
realistic and privacy-preserving synthetic tabular data is urgent. In this
paper, we take a step forward to explore LLMs for tabular data synthesis and
privacy protection, by introducing a new framework HARMONIC for tabular data
generation and evaluation. In the tabular data generation of our framework,
unlike previous small-scale LLM-based methods that rely on continued
pre-training, we explore the larger-scale LLMs with fine-tuning to generate
tabular data and enhance privacy. Based on idea of the k-nearest neighbors
algorithm, an instruction fine-tuning dataset is constructed to inspire LLMs to
discover inter-row relationships. Then, with fine-tuning, LLMs are trained to
remember the format and connections of the data rather than the data itself,
which reduces the risk of privacy leakage. In the evaluation part of our
framework, we develop specific privacy risk metrics DLT for LLM synthetic data
generation, as well as performance evaluation metrics LLE for downstream LLM
tasks. Our experiments find that this tabular data generation framework
achieves equivalent performance to existing methods with better privacy, which
also demonstrates our evaluation framework for the effectiveness of synthetic
data and privacy risks in LLM scenarios.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2408.02750v1">Privacy-Safe Iris Presentation Attack Detection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> 
  <p><b>Published on:</b> 2024-08-05T18:09:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mahsa Mitcheff, Patrick Tinsley, Adam Czajka</p>
    <p><b>Summary:</b> This paper proposes a framework for a privacy-safe iris presentation attack
detection (PAD) method, designed solely with synthetically-generated,
identity-leakage-free iris images. Once trained, the method is evaluated in a
classical way using state-of-the-art iris PAD benchmarks. We designed two
generative models for the synthesis of ISO/IEC 19794-6-compliant iris images.
The first model synthesizes bona fide-looking samples. To avoid ``identity
leakage,'' the generated samples that accidentally matched those used in the
model's training were excluded. The second model synthesizes images of irises
with textured contact lenses and is conditioned by a given contact lens brand
to have better control over textured contact lens appearance when forming the
training set. Our experiments demonstrate that models trained solely on
synthetic data achieve a lower but still reasonable performance when compared
to solutions trained with iris images collected from human subjects. This is
the first-of-its-kind attempt to use solely synthetic data to train a
fully-functional iris PAD solution, and despite the performance gap between
regular and the proposed methods, this study demonstrates that with the
increasing fidelity of generative models, creating such privacy-safe iris PAD
methods may be possible. The source codes and generative models trained for
this work are offered along with the paper.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2408.02373v1">Operationalizing Contextual Integrity in Privacy-Conscious Assistants</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-08-05T10:53:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sahra Ghalebikesabi, Eugene Bagdasaryan, Ren Yi, Itay Yona, Ilia Shumailov, Aneesh Pappu, Chongyang Shi, Laura Weidinger, Robert Stanforth, Leonard Berrada, Pushmeet Kohli, Po-Sen Huang, Borja Balle</p>
    <p><b>Summary:</b> Advanced AI assistants combine frontier LLMs and tool access to autonomously
perform complex tasks on behalf of users. While the helpfulness of such
assistants can increase dramatically with access to user information including
emails and documents, this raises privacy concerns about assistants sharing
inappropriate information with third parties without user supervision. To steer
information-sharing assistants to behave in accordance with privacy
expectations, we propose to operationalize $\textit{contextual integrity}$
(CI), a framework that equates privacy with the appropriate flow of information
in a given context. In particular, we design and evaluate a number of
strategies to steer assistants' information-sharing actions to be CI compliant.
Our evaluation is based on a novel form filling benchmark composed of synthetic
data and human annotations, and it reveals that prompting frontier LLMs to
perform CI-based reasoning yields strong results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2408.01711v1">Privacy in networks of quantum sensors</a></h3>
  
  <p><b>Published on:</b> 2024-08-03T08:39:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Majid Hassani, Santiago Scheiner, Matteo G. A. Paris, Damian Markham</p>
    <p><b>Summary:</b> We treat privacy in a network of quantum sensors where accessible information
is limited to specific functions of the network parameters, and all other
information remains private. We develop an analysis of privacy in terms of a
manipulation of the quantum Fisher information matrix, and find the optimal
state achieving maximum privacy in the estimation of linear combination of the
unknown parameters in a network of quantum sensors. We also discuss the effect
of uncorrelated noise on the privacy of the network. Moreover, we illustrate
our results with an example where the goal is to estimate the average value of
the unknown parameters in the network. In this example, we also introduce the
notion of quasi-privacy ($\epsilon$-privacy), quantifying how close the state
is to being private.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2408.01609v1">Fed-RD: Privacy-Preserving Federated Learning for Financial Crime
  Detection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computational Engineering, Finance, and Science-5BC0EB">
  <p><b>Published on:</b> 2024-08-03T00:07:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Md. Saikat Islam Khan, Aparna Gupta, Oshani Seneviratne, Stacy Patterson</p>
    <p><b>Summary:</b> We introduce Federated Learning for Relational Data (Fed-RD), a novel
privacy-preserving federated learning algorithm specifically developed for
financial transaction datasets partitioned vertically and horizontally across
parties. Fed-RD strategically employs differential privacy and secure
multiparty computation to guarantee the privacy of training data. We provide
theoretical analysis of the end-to-end privacy of the training algorithm and
present experimental results on realistic synthetic datasets. Our results
demonstrate that Fed-RD achieves high model accuracy with minimal degradation
as privacy increases, while consistently surpassing benchmark results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2408.01228v1">The Phantom Menace: Unmasking Privacy Leakages in Vision-Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-08-02T12:36:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Simone Caldarella, Massimiliano Mancini, Elisa Ricci, Rahaf Aljundi</p>
    <p><b>Summary:</b> Vision-Language Models (VLMs) combine visual and textual understanding,
rendering them well-suited for diverse tasks like generating image captions and
answering visual questions across various domains. However, these capabilities
are built upon training on large amount of uncurated data crawled from the web.
The latter may include sensitive information that VLMs could memorize and leak,
raising significant privacy concerns. In this paper, we assess whether these
vulnerabilities exist, focusing on identity leakage. Our study leads to three
key findings: (i) VLMs leak identity information, even when the vision-language
alignment and the fine-tuning use anonymized data; (ii) context has little
influence on identity leakage; (iii) simple, widely used anonymization
techniques, like blurring, are not sufficient to address the problem. These
findings underscore the urgent need for robust privacy protection strategies
when deploying VLMs. Ethical awareness and responsible development practices
are essential to mitigate these risks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2408.01040v1">Privacy-Preserving Split Learning with Vision Transformers using
  Patch-Wise Random and Noisy CutMix</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-08-02T06:24:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Seungeun Oh, Sihun Baek, Jihong Park, Hyelin Nam, Praneeth Vepakomma, Ramesh Raskar, Mehdi Bennis, Seong-Lyun Kim</p>
    <p><b>Summary:</b> In computer vision, the vision transformer (ViT) has increasingly superseded
the convolutional neural network (CNN) for improved accuracy and robustness.
However, ViT's large model sizes and high sample complexity make it difficult
to train on resource-constrained edge devices. Split learning (SL) emerges as a
viable solution, leveraging server-side resources to train ViTs while utilizing
private data from distributed devices. However, SL requires additional
information exchange for weight updates between the device and the server,
which can be exposed to various attacks on private training data. To mitigate
the risk of data breaches in classification tasks, inspired from the CutMix
regularization, we propose a novel privacy-preserving SL framework that injects
Gaussian noise into smashed data and mixes randomly chosen patches of smashed
data across clients, coined DP-CutMixSL. Our analysis demonstrates that
DP-CutMixSL is a differentially private (DP) mechanism that strengthens privacy
protection against membership inference attacks during forward propagation.
Through simulations, we show that DP-CutMixSL improves privacy protection
against membership inference attacks, reconstruction attacks, and label
inference attacks, while also improving accuracy compared to DP-SL and
DP-MixSL.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2408.00950v1">PrivateGaze: Preserving User Privacy in Black-box Mobile Gaze Tracking
  Services</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-08-01T23:11:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lingyu Du, Jinyuan Jia, Xucong Zhang, Guohao Lan</p>
    <p><b>Summary:</b> Eye gaze contains rich information about human attention and cognitive
processes. This capability makes the underlying technology, known as gaze
tracking, a critical enabler for many ubiquitous applications and has triggered
the development of easy-to-use gaze estimation services. Indeed, by utilizing
the ubiquitous cameras on tablets and smartphones, users can readily access
many gaze estimation services. In using these services, users must provide
their full-face images to the gaze estimator, which is often a black box. This
poses significant privacy threats to the users, especially when a malicious
service provider gathers a large collection of face images to classify
sensitive user attributes. In this work, we present PrivateGaze, the first
approach that can effectively preserve users' privacy in black-box gaze
tracking services without compromising gaze estimation performance.
Specifically, we proposed a novel framework to train a privacy preserver that
converts full-face images into obfuscated counterparts, which are effective for
gaze estimation while containing no privacy information. Evaluation on four
datasets shows that the obfuscated image can protect users' private
information, such as identity and gender, against unauthorized attribute
classification. Meanwhile, when used directly by the black-box gaze estimator
as inputs, the obfuscated images lead to comparable tracking performance to the
conventional, unprotected full-face images.</p>
  </details>
</div>


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
  <h3><a href="http://arxiv.org/abs/2408.01428v1">Transferable Adversarial Facial Images for Privacy Protection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-07-18T02:16:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Minghui Li, Jiangxiong Wang, Hao Zhang, Ziqi Zhou, Shengshan Hu, Xiaobing Pei</p>
    <p><b>Summary:</b> The success of deep face recognition (FR) systems has raised serious privacy
concerns due to their ability to enable unauthorized tracking of users in the
digital world. Previous studies proposed introducing imperceptible adversarial
noises into face images to deceive those face recognition models, thus
achieving the goal of enhancing facial privacy protection. Nevertheless, they
heavily rely on user-chosen references to guide the generation of adversarial
noises, and cannot simultaneously construct natural and highly transferable
adversarial face images in black-box scenarios. In light of this, we present a
novel face privacy protection scheme with improved transferability while
maintain high visual quality. We propose shaping the entire face space directly
instead of exploiting one kind of facial characteristic like makeup information
to integrate adversarial noises. To achieve this goal, we first exploit global
adversarial latent search to traverse the latent space of the generative model,
thereby creating natural adversarial face images with high transferability. We
then introduce a key landmark regularization module to preserve the visual
identity information. Finally, we investigate the impacts of various kinds of
latent spaces and find that $\mathcal{F}$ latent space benefits the trade-off
between visual naturalness and adversarial transferability. Extensive
experiments over two datasets demonstrate that our approach significantly
enhances attack transferability while maintaining high visual quality,
outperforming state-of-the-art methods by an average 25% improvement in deep FR
models and 10% improvement on commercial FR APIs, including Face++, Aliyun, and
Tencent.</p>
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

