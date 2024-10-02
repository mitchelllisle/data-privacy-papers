
<h2>2024-09</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.19988v1">Enhancing Security Using Random Binary Weights in Privacy-Preserving
  Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-30T06:28:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hiroto Sawada, Shoko Imaizumi, Hitoshi Kiya</p>
    <p><b>Summary:</b> In this paper, we propose a novel method for enhancing security in
privacy-preserving federated learning using the Vision Transformer. In
federated learning, learning is performed by collecting updated information
without collecting raw data from each client. However, the problem is that this
raw data may be inferred from the updated information. Conventional
data-guessing countermeasures (security enhancement methods) for addressing
this issue have a trade-off relationship between privacy protection strength
and learning efficiency, and they generally degrade model performance. In this
paper, we propose a novel method of federated learning that does not degrade
model performance and that is robust against data-guessing attacks on updated
information. In the proposed method, each client independently prepares a
sequence of binary (0 or 1) random numbers, multiplies it by the updated
information, and sends it to a server for model learning. In experiments, the
effectiveness of the proposed method is confirmed in terms of model performance
and resistance to the APRIL (Attention PRIvacy Leakage) restoration attack.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.19964v1">Comments on "Privacy-Enhanced Federated Learning Against Poisoning
  Adversaries"</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-09-30T05:34:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Thomas Schneider, Ajith Suresh, Hossein Yalame</p>
    <p><b>Summary:</b> In August 2021, Liu et al. (IEEE TIFS'21) proposed a privacy-enhanced
framework named PEFL to efficiently detect poisoning behaviours in Federated
Learning (FL) using homomorphic encryption. In this article, we show that PEFL
does not preserve privacy. In particular, we illustrate that PEFL reveals the
entire gradient vector of all users in clear to one of the participating
entities, thereby violating privacy. Furthermore, we clearly show that an
immediate fix for this issue is still insufficient to achieve privacy by
pointing out multiple flaws in the proposed system.
  Note: Although our privacy issues mentioned in Section II have been published
in January 2023 (Schneider et. al., IEEE TIFS'23), several subsequent papers
continued to reference Liu et al. (IEEE TIFS'21) as a potential solution for
private federated learning. While a few works have acknowledged the privacy
concerns we raised, several of subsequent works either propagate these errors
or adopt the constructions from Liu et al. (IEEE TIFS'21), thereby
unintentionally inheriting the same privacy vulnerabilities. We believe this
oversight is partly due to the limited visibility of our comments paper at
TIFS'23 (Schneider et. al., IEEE TIFS'23). Consequently, to prevent the
continued propagation of the flawed algorithms in Liu et al. (IEEE TIFS'21)
into future research, we also put this article to an ePrint.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.19756v1">Advances in Privacy Preserving Federated Learning to Realize a Truly
  Learning Healthcare System</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-09-29T20:02:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ravi Madduri, Zilinghan Li, Tarak Nandi, Kibaek Kim, Minseok Ryu, Alex Rodriguez</p>
    <p><b>Summary:</b> The concept of a learning healthcare system (LHS) envisions a self-improving
network where multimodal data from patient care are continuously analyzed to
enhance future healthcare outcomes. However, realizing this vision faces
significant challenges in data sharing and privacy protection.
Privacy-Preserving Federated Learning (PPFL) is a transformative and promising
approach that has the potential to address these challenges by enabling
collaborative learning from decentralized data while safeguarding patient
privacy. This paper proposes a vision for integrating PPFL into the healthcare
ecosystem to achieve a truly LHS as defined by the Institute of Medicine (IOM)
Roundtable.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.19413v1">Membership Privacy Evaluation in Deep Spiking Neural Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-09-28T17:13:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiaxin Li, Gorka Abad, Stjepan Picek, Mauro Conti</p>
    <p><b>Summary:</b> Artificial Neural Networks (ANNs), commonly mimicking neurons with non-linear
functions to output floating-point numbers, consistently receive the same
signals of a data point during its forward time. Unlike ANNs, Spiking Neural
Networks (SNNs) get various input signals in the forward time of a data point
and simulate neurons in a biologically plausible way, i.e., producing a spike
(a binary value) if the accumulated membrane potential of a neuron is larger
than a threshold. Even though ANNs have achieved remarkable success in multiple
tasks, e.g., face recognition and object detection, SNNs have recently obtained
attention due to their low power consumption, fast inference, and event-driven
properties. While privacy threats against ANNs are widely explored, much less
work has been done on SNNs. For instance, it is well-known that ANNs are
vulnerable to the Membership Inference Attack (MIA), but whether the same
applies to SNNs is not explored.
  In this paper, we evaluate the membership privacy of SNNs by considering
eight MIAs, seven of which are inspired by MIAs against ANNs. Our evaluation
results show that SNNs are more vulnerable (maximum 10% higher in terms of
balanced attack accuracy) than ANNs when both are trained with neuromorphic
datasets (with time dimension). On the other hand, when training ANNs or SNNs
with static datasets (without time dimension), the vulnerability depends on the
dataset used. If we convert ANNs trained with static datasets to SNNs, the
accuracy of MIAs drops (maximum 11.5% with a reduction of 7.6% on the test
accuracy of the target model). Next, we explore the impact factors of MIAs on
SNNs by conducting a hyperparameter study. Finally, we show that the basic data
augmentation method for static data and two recent data augmentation methods
for neuromorphic data can considerably (maximum reduction of 25.7%) decrease
MIAs' performance on SNNs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.19334v1">OnePath: Efficient and Privacy-Preserving Decision Tree Inference in the
  Cloud</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-28T12:35:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuai Yuan, Hongwei Li, Xinyuan Qian, Wenbo Jiang, Guowen Xu</p>
    <p><b>Summary:</b> The expansive storage capacity and robust computational power of cloud
servers have led to the widespread outsourcing of machine learning inference
services to the cloud. While this practice offers significant operational
benefits, it also poses substantial privacy risks, including the exposure of
proprietary models and sensitive user data. In this paper, we introduce
OnePath, a framework designed for secure and efficient decision tree inference
in cloud environments. Unlike existing schemes that require traversing all
internal nodes of a decision tree, our protocol securely identifies and
processes only the nodes on the prediction path, maintaining data privacy under
ciphertext throughout the inference process. This selective traversal enhances
both security and efficiency. To further optimize privacy and performance,
OnePath employs lightweight cryptographic techniques, such as functional
encryption, during the online phase of secure inference. Notably, our protocol
allows both providers and clients to perform secure inference without the need
to remain online continuously, a critical advantage for real-world
applications. We substantiate the security of our framework with formal proofs,
demonstrating that OnePath robustly protects the privacy of decision tree
classifiers and user data. Experimental results highlight the efficiency of our
approach, with our scheme processing query data in mere microseconds on the
tested dataset. Through OnePath, we provide a practical solution that balances
the needs for security and efficiency in cloud-based decision tree inference,
making it a promising option for a variety of applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.19306v1">CausalVE: Face Video Privacy Encryption via Causal Video Prediction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-09-28T10:34:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yubo Huang, Wenhao Feng, Xin Lai, Zixi Wang, Jingzehua Xu, Shuai Zhang, Hongjie He, Fan Chen</p>
    <p><b>Summary:</b> Advanced facial recognition technologies and recommender systems with
inadequate privacy technologies and policies for facial interactions increase
concerns about bioprivacy violations. With the proliferation of video and
live-streaming websites, public-face video distribution and interactions pose
greater privacy risks. Existing techniques typically address the risk of
sensitive biometric information leakage through various privacy enhancement
methods but pose a higher security risk by corrupting the information to be
conveyed by the interaction data, or by leaving certain biometric features
intact that allow an attacker to infer sensitive biometric information from
them. To address these shortcomings, in this paper, we propose a neural network
framework, CausalVE. We obtain cover images by adopting a diffusion model to
achieve face swapping with face guidance and use the speech sequence features
and spatiotemporal sequence features of the secret video for dynamic video
inference and prediction to obtain a cover video with the same number of frames
as the secret video. In addition, we hide the secret video by using reversible
neural networks for video hiding so that the video can also disseminate secret
data. Numerous experiments prove that our CausalVE has good security in public
video dissemination and outperforms state-of-the-art methods from a
qualitative, quantitative, and visual point of view.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.19301v1">Privacy Attack in Federated Learning is Not Easy: An Experimental Study</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-09-28T10:06:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hangyu Zhu, Liyuan Huang, Zhenping Xie</p>
    <p><b>Summary:</b> Federated learning (FL) is an emerging distributed machine learning paradigm
proposed for privacy preservation. Unlike traditional centralized learning
approaches, FL enables multiple users to collaboratively train a shared global
model without disclosing their own data, thereby significantly reducing the
potential risk of privacy leakage. However, recent studies have indicated that
FL cannot entirely guarantee privacy protection, and attackers may still be
able to extract users' private data through the communicated model gradients.
Although numerous privacy attack FL algorithms have been developed, most are
designed to reconstruct private data from a single step of calculated
gradients. It remains uncertain whether these methods are effective in
realistic federated environments or if they have other limitations. In this
paper, we aim to help researchers better understand and evaluate the
effectiveness of privacy attacks on FL. We analyze and discuss recent research
papers on this topic and conduct experiments in a real FL environment to
compare the performance of various attack methods. Our experimental results
reveal that none of the existing state-of-the-art privacy attack algorithms can
effectively breach private client data in realistic FL settings, even in the
absence of defense strategies. This suggests that privacy attacks in FL are
more challenging than initially anticipated.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.19092v1">Federated Online Prediction from Experts with Differential Privacy:
  Separations and Regret Speed-ups</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-09-27T18:43:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fengyu Gao, Ruiquan Huang, Jing Yang</p>
    <p><b>Summary:</b> We study the problems of differentially private federated online prediction
from experts against both stochastic adversaries and oblivious adversaries. We
aim to minimize the average regret on $m$ clients working in parallel over time
horizon $T$ with explicit differential privacy (DP) guarantees. With stochastic
adversaries, we propose a Fed-DP-OPE-Stoch algorithm that achieves
$\sqrt{m}$-fold speed-up of the per-client regret compared to the single-player
counterparts under both pure DP and approximate DP constraints, while
maintaining logarithmic communication costs. With oblivious adversaries, we
establish non-trivial lower bounds indicating that collaboration among clients
does not lead to regret speed-up with general oblivious adversaries. We then
consider a special case of the oblivious adversaries setting, where there
exists a low-loss expert. We design a new algorithm Fed-SVT and show that it
achieves an $m$-fold regret speed-up under both pure DP and approximate DP
constraints over the single-player counterparts. Our lower bound indicates that
Fed-SVT is nearly optimal up to logarithmic factors. Experiments demonstrate
the effectiveness of our proposed algorithms. To the best of our knowledge,
this is the first work examining the differentially private online prediction
from experts in the federated setting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.19078v1">Differential privacy for protecting patient data in speech disorder
  detection using deep learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> 
  <p><b>Published on:</b> 2024-09-27T18:25:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Soroosh Tayebi Arasteh, Mahshad Lotfinia, Paula Andrea Perez-Toro, Tomas Arias-Vergara, Juan Rafael Orozco-Arroyave, Maria Schuster, Andreas Maier, Seung Hee Yang</p>
    <p><b>Summary:</b> Speech pathology has impacts on communication abilities and quality of life.
While deep learning-based models have shown potential in diagnosing these
disorders, the use of sensitive data raises critical privacy concerns. Although
differential privacy (DP) has been explored in the medical imaging domain, its
application in pathological speech analysis remains largely unexplored despite
the equally critical privacy concerns. This study is the first to investigate
DP's impact on pathological speech data, focusing on the trade-offs between
privacy, diagnostic accuracy, and fairness. Using a large, real-world dataset
of 200 hours of recordings from 2,839 German-speaking participants, we observed
a maximum accuracy reduction of 3.85% when training with DP with a privacy
budget, denoted by {\epsilon}, of 7.51. To generalize our findings, we
validated our approach on a smaller dataset of Spanish-speaking Parkinson's
disease patients, demonstrating that careful pretraining on large-scale
task-specific datasets can maintain or even improve model accuracy under DP
constraints. We also conducted a comprehensive fairness analysis, revealing
that reasonable privacy levels (2<{\epsilon}<10) do not introduce significant
gender bias, though age-related disparities may require further attention. Our
results suggest that DP can effectively balance privacy and utility in speech
disorder detection, but also highlight the unique challenges in the speech
domain, particularly regarding the privacy-fairness trade-off. This provides a
foundation for future work to refine DP methodologies and address fairness
across diverse patient groups in real-world deployments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.18907v1">In-depth Analysis of Privacy Threats in Federated Learning for Medical
  Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-09-27T16:45:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Badhan Chandra Das, M. Hadi Amini, Yanzhao Wu</p>
    <p><b>Summary:</b> Federated learning is emerging as a promising machine learning technique in
the medical field for analyzing medical images, as it is considered an
effective method to safeguard sensitive patient data and comply with privacy
regulations. However, recent studies have revealed that the default settings of
federated learning may inadvertently expose private training data to privacy
attacks. Thus, the intensity of such privacy risks and potential mitigation
strategies in the medical domain remain unclear. In this paper, we make three
original contributions to privacy risk analysis and mitigation in federated
learning for medical data. First, we propose a holistic framework, MedPFL, for
analyzing privacy risks in processing medical data in the federated learning
environment and developing effective mitigation strategies for protecting
privacy. Second, through our empirical analysis, we demonstrate the severe
privacy risks in federated learning to process medical images, where
adversaries can accurately reconstruct private medical images by performing
privacy attacks. Third, we illustrate that the prevalent defense mechanism of
adding random noises may not always be effective in protecting medical images
against privacy attacks in federated learning, which poses unique and pressing
challenges related to protecting the privacy of medical data. Furthermore, the
paper discusses several unique research questions related to the privacy
protection of medical data in the federated learning environment. We conduct
extensive experiments on several benchmark medical image datasets to analyze
and mitigate the privacy risks associated with federated learning for medical
data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.18674v1">Image-guided topic modeling for interpretable privacy classification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-09-27T12:02:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alina Elena Baia, Andrea Cavallaro</p>
    <p><b>Summary:</b> Predicting and explaining the private information contained in an image in
human-understandable terms is a complex and contextual task. This task is
challenging even for large language models. To facilitate the understanding of
privacy decisions, we propose to predict image privacy based on a set of
natural language content descriptors. These content descriptors are associated
with privacy scores that reflect how people perceive image content. We generate
descriptors with our novel Image-guided Topic Modeling (ITM) approach. ITM
leverages, via multimodality alignment, both vision information and image
textual descriptions from a vision language model. We use the ITM-generated
descriptors to learn a privacy predictor, Priv$\times$ITM, whose decisions are
interpretable by design. Our Priv$\times$ITM classifier outperforms the
reference interpretable method by 5 percentage points in accuracy and performs
comparably to the current non-interpretable state-of-the-art model.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.18611v1">Differentially Private Non Parametric Copulas: Generating synthetic data
  with non parametric copulas under privacy guarantees</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">  
  <p><b>Published on:</b> 2024-09-27T10:18:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pablo A. Osorio-Marulanda, John Esteban Castro Ramirez, Mikel Hernández Jiménez, Nicolas Moreno Reyes, Gorka Epelde Unanue</p>
    <p><b>Summary:</b> Creation of synthetic data models has represented a significant advancement
across diverse scientific fields, but this technology also brings important
privacy considerations for users. This work focuses on enhancing a
non-parametric copula-based synthetic data generation model, DPNPC, by
incorporating Differential Privacy through an Enhanced Fourier Perturbation
method. The model generates synthetic data for mixed tabular databases while
preserving privacy. We compare DPNPC with three other models (PrivBayes,
DP-Copula, and DP-Histogram) across three public datasets, evaluating privacy,
utility, and execution time. DPNPC outperforms others in modeling multivariate
dependencies, maintaining privacy for small $\epsilon$ values, and reducing
training times. However, limitations include the need to assess the model's
performance with different encoding methods and consider additional privacy
attacks. Future research should address these areas to enhance
privacy-preserving synthetic data generation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.18601v1">Privacy-Preserving Quantum Annealing for Quadratic Unconstrained Binary
  Optimization (QUBO) Problems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-09-27T10:05:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Moyang Xie, Yuan Zhang, Sheng Zhong, Qun Li</p>
    <p><b>Summary:</b> Quantum annealers offer a promising approach to solve Quadratic Unconstrained
Binary Optimization (QUBO) problems, which have a wide range of applications.
However, when a user submits its QUBO problem to a third-party quantum
annealer, the problem itself may disclose the user's private information to the
quantum annealing service provider. To mitigate this risk, we introduce a
privacy-preserving QUBO framework and propose a novel solution method. Our
approach employs a combination of digit-wise splitting and matrix permutation
to obfuscate the QUBO problem's model matrix $Q$, effectively concealing the
matrix elements. In addition, based on the solution to the obfuscated version
of the QUBO problem, we can reconstruct the solution to the original problem
with high accuracy. Theoretical analysis and empirical tests confirm the
efficacy and efficiency of our proposed technique, demonstrating its potential
for preserving user privacy in quantum annealing services.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.18360v1">Architecture for Protecting Data Privacy in Decentralized Social
  Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-27T00:35:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Quang Cao, Katerina Vgena, Aikaterini-Georgia Mavroeidi, Christos Kalloniatis, Xun Yi, Son Hoang Dau</p>
    <p><b>Summary:</b> Centralized social networks have experienced a transformative impact on our
digital era communication, connection, and information-sharing information.
However, it has also raised significant concerns regarding users' privacy and
individual rights. In response to these concerns, this paper proposes a novel
Decentralized Social Network employing Blockchain technology and Decentralized
Storage Networks completed by Access Control Smart Contracts. The initial phase
comprises a comprehensive literature review, delving into decentralized social
networks, explaining the review methodology, and presenting the resulting
findings. Building upon these findings and an analysis of previous research
gaps, we propose a novel architecture for decentralized social networks. In
conclusion, the principal results highlight the benefit of our decentralized
social network to protect user privacy. Moreover, the users have all rights to
their posted information following the General Data Protection Regulation
(GDPR).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.18356v1">FedDCL: a federated data collaboration learning as a hybrid-type
  privacy-preserving framework based on federated learning and data
  collaboration</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-27T00:22:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Akira Imakura, Tetsuya Sakurai</p>
    <p><b>Summary:</b> Recently, federated learning has attracted much attention as a
privacy-preserving integrated analysis that enables integrated analysis of data
held by multiple institutions without sharing raw data. On the other hand,
federated learning requires iterative communication across institutions and has
a big challenge for implementation in situations where continuous communication
with the outside world is extremely difficult. In this study, we propose a
federated data collaboration learning (FedDCL), which solves such communication
issues by combining federated learning with recently proposed non-model
share-type federated learning named as data collaboration analysis. In the
proposed FedDCL framework, each user institution independently constructs
dimensionality-reduced intermediate representations and shares them with
neighboring institutions on intra-group DC servers. On each intra-group DC
server, intermediate representations are transformed to incorporable forms
called collaboration representations. Federated learning is then conducted
between intra-group DC servers. The proposed FedDCL framework does not require
iterative communication by user institutions and can be implemented in
situations where continuous communication with the outside world is extremely
difficult. The experimental results show that the performance of the proposed
FedDCL is comparable to that of existing federated learning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.18245v1">PDFed: Privacy-Preserving and Decentralized Asynchronous Federated
  Learning for Diffusion Models</a></h3>
  
  <p><b>Published on:</b> 2024-09-26T19:38:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kar Balan, Andrew Gilbert, John Collomosse</p>
    <p><b>Summary:</b> We present PDFed, a decentralized, aggregator-free, and asynchronous
federated learning protocol for training image diffusion models using a public
blockchain. In general, diffusion models are prone to memorization of training
data, raising privacy and ethical concerns (e.g., regurgitation of private
training data in generated images). Federated learning (FL) offers a partial
solution via collaborative model training across distributed nodes that
safeguard local data privacy. PDFed proposes a novel sample-based score that
measures the novelty and quality of generated samples, incorporating these into
a blockchain-based federated learning protocol that we show reduces private
data memorization in the collaboratively trained model. In addition, PDFed
enables asynchronous collaboration among participants with varying hardware
capabilities, facilitating broader participation. The protocol records the
provenance of AI models, improving transparency and auditability, while also
considering automated incentive and reward mechanisms for participants. PDFed
aims to empower artists and creators by protecting the privacy of creative
works and enabling decentralized, peer-to-peer collaboration. The protocol
positively impacts the creative economy by opening up novel revenue streams and
fostering innovative ways for artists to benefit from their contributions to
the AI space.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.18118v1">Slowly Scaling Per-Record Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-09-26T17:56:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Brian Finley, Anthony M Caruso, Justin C Doty, Ashwin Machanavajjhala, Mikaela R Meyer, David Pujol, William Sexton, Zachary Terner</p>
    <p><b>Summary:</b> We develop formal privacy mechanisms for releasing statistics from data with
many outlying values, such as income data. These mechanisms ensure that a
per-record differential privacy guarantee degrades slowly in the protected
records' influence on the statistics being released.
  Formal privacy mechanisms generally add randomness, or "noise," to published
statistics. If a noisy statistic's distribution changes little with the
addition or deletion of a single record in the underlying dataset, an attacker
looking at this statistic will find it plausible that any particular record was
present or absent, preserving the records' privacy. More influential records --
those whose addition or deletion would change the statistics' distribution more
-- typically suffer greater privacy loss. The per-record differential privacy
framework quantifies these record-specific privacy guarantees, but existing
mechanisms let these guarantees degrade rapidly (linearly or quadratically)
with influence. While this may be acceptable in cases with some moderately
influential records, it results in unacceptably high privacy losses when
records' influence varies widely, as is common in economic data.
  We develop mechanisms with privacy guarantees that instead degrade as slowly
as logarithmically with influence. These mechanisms allow for the accurate,
unbiased release of statistics, while providing meaningful protection for
highly influential records. As an example, we consider the private release of
sums of unbounded establishment data such as payroll, where our mechanisms
extend meaningful privacy protection even to very large establishments. We
evaluate these mechanisms empirically and demonstrate their utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17886v1">Upper-Body Pose-based Gaze Estimation for Privacy-Preserving 3D Gaze
  Target Detection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-09-26T14:35:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Andrea Toaiari, Vittorio Murino, Marco Cristani, Cigdem Beyan</p>
    <p><b>Summary:</b> Gaze Target Detection (GTD), i.e., determining where a person is looking
within a scene from an external viewpoint, is a challenging task, particularly
in 3D space. Existing approaches heavily rely on analyzing the person's
appearance, primarily focusing on their face to predict the gaze target. This
paper presents a novel approach to tackle this problem by utilizing the
person's upper-body pose and available depth maps to extract a 3D gaze
direction and employing a multi-stage or an end-to-end pipeline to predict the
gazed target. When predicted accurately, the human body pose can provide
valuable information about the head pose, which is a good approximation of the
gaze direction, as well as the position of the arms and hands, which are linked
to the activity the person is performing and the objects they are likely
focusing on. Consequently, in addition to performing gaze estimation in 3D, we
are also able to perform GTD simultaneously. We demonstrate state-of-the-art
results on the most comprehensive publicly accessible 3D gaze target detection
dataset without requiring images of the person's face, thus promoting privacy
preservation in various application contexts. The code is available at
https://github.com/intelligolabs/privacy-gtd-3D.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17744v1">Privacy for Quantum Annealing. Attack on Spin Reversal Transformations
  in the case of cryptanalysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-26T11:17:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mateusz Leśniak, Michał Wroński</p>
    <p><b>Summary:</b> This paper demonstrates that applying spin reversal transformations (SRT),
commonly known as a sufficient method for privacy enhancing in problems solved
using quantum annealing, does not guarantee privacy for all possible problems.
We show how to recover the original problem from the Ising problem obtained
using SRT when the resulting problem in Ising form represents the algebraic
attack on the $E_0$ stream cipher. A small example is used to illustrate how to
retrieve the original problem from the one transformed by SRT. Moreover, it is
shown that our method is efficient even for full-scale problems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17742v1">TADAR: Thermal Array-based Detection and Ranging for Privacy-Preserving
  Human Sensing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-09-26T11:17:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xie Zhang, Chenshu Wu</p>
    <p><b>Summary:</b> Human sensing has gained increasing attention in various applications. Among
the available technologies, visual images offer high accuracy, while sensing on
the RF spectrum preserves privacy, creating a conflict between imaging
resolution and privacy preservation. In this paper, we explore thermal array
sensors as an emerging modality that strikes an excellent resolution-privacy
balance for ubiquitous sensing. To this end, we present TADAR, the first
multi-user Thermal Array-based Detection and Ranging system that estimates the
inherently missing range information, extending thermal array outputs from 2D
thermal pixels to 3D depths and empowering them as a promising modality for
ubiquitous privacy-preserving human sensing. We prototype TADAR using a single
commodity thermal array sensor and conduct extensive experiments in different
indoor environments. Our results show that TADAR achieves a mean F1 score of
88.8% for multi-user detection and a mean accuracy of 32.0 cm for multi-user
ranging, which further improves to 20.1 cm for targets located within 3 m. We
conduct two case studies on fall detection and occupancy estimation to showcase
the potential applications of TADAR. We hope TADAR will inspire the vast
community to explore new directions of thermal array sensing, beyond wireless
and acoustic sensing. TADAR is open-sourced on GitHub:
https://github.com/aiot-lab/TADAR.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17705v1">On the Output Redundancy of LTI Systems: A Geometric Approach with
  Application to Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2024-09-26T10:21:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guitao Yang, Alexander J. Gallo, Angelo Barboni, Riccardo M. G. Ferrari, Andrea Serrani, Thomas Parisini</p>
    <p><b>Summary:</b> This paper examines the properties of output-redundant systems, that is,
systems possessing a larger number of outputs than inputs, through the lenses
of the geometric approach of Wonham et al. We begin by formulating a simple
output allocation synthesis problem, which involves ``concealing" input
information from a malicious eavesdropper having access to the system output,
while still allowing for a legitimate user to reconstruct it. It is shown that
the solvability of this problem requires the availability of a redundant set of
outputs. This very problem is instrumental to unveiling the fundamental
geometric properties of output-redundant systems, which form the basis for our
subsequent constructions and results. As a direct application, we demonstrate
how output allocation can be employed to effectively protect the information of
input information from certain output eavesdroppers with guaranteed results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17700v1">Demystifying Privacy in 5G Stand Alone Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2024-09-26T10:14:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stavros Eleftherakis, Timothy Otim, Giuseppe Santaromita, Almudena Diaz Zayas, Domenico Giustiniano, Nicolas Kourtellis</p>
    <p><b>Summary:</b> Ensuring user privacy remains critical in mobile networks, particularly with
the rise of connected devices and denser 5G infrastructure. Privacy concerns
have persisted across 2G, 3G, and 4G/LTE networks. Recognizing these concerns,
the 3rd Generation Partnership Project (3GPP) has made privacy enhancements in
5G Release 15. However, the extent of operator adoption remains unclear,
especially as most networks operate in 5G Non Stand Alone (NSA) mode, relying
on 4G Core Networks. This study provides the first qualitative and experimental
comparison between 5G NSA and Stand Alone (SA) in real operator networks,
focusing on privacy enhancements addressing top eight pre-5G attacks based on
recent academic literature. Additionally, it evaluates the privacy levels of
OpenAirInterface (OAI), a leading open-source software for 5G, against real
network deployments for the same attacks. The analysis reveals two new 5G
privacy vulnerabilities, underscoring the need for further research and
stricter standards.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17642v1">AI Delegates with a Dual Focus: Ensuring Privacy and Strategic
  Self-Disclosure</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-09-26T08:45:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xi Chen, Zhiyang Zhang, Fangkai Yang, Xiaoting Qin, Chao Du, Xi Cheng, Hangxin Liu, Qingwei Lin, Saravan Rajmohan, Dongmei Zhang, Qi Zhang</p>
    <p><b>Summary:</b> Large language model (LLM)-based AI delegates are increasingly utilized to
act on behalf of users, assisting them with a wide range of tasks through
conversational interfaces. Despite their advantages, concerns arise regarding
the potential risk of privacy leaks, particularly in scenarios involving social
interactions. While existing research has focused on protecting privacy by
limiting the access of AI delegates to sensitive user information, many social
scenarios require disclosing private details to achieve desired outcomes,
necessitating a balance between privacy protection and disclosure. To address
this challenge, we conduct a pilot study to investigate user preferences for AI
delegates across various social relations and task scenarios, and then propose
a novel AI delegate system that enables privacy-conscious self-disclosure. Our
user study demonstrates that the proposed AI delegate strategically protects
privacy, pioneering its use in diverse and dynamic social interactions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17623v1">Fully Dynamic Graph Algorithms with Edge Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-26T08:17:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sofya Raskhodnikova, Teresa Anna Steiner</p>
    <p><b>Summary:</b> We study differentially private algorithms for analyzing graphs in the
challenging setting of continual release with fully dynamic updates, where
edges are inserted and deleted over time, and the algorithm is required to
update the solution at every time step. Previous work has presented
differentially private algorithms for many graph problems that can handle
insertions only or deletions only (called partially dynamic algorithms) and
obtained some hardness results for the fully dynamic setting. The only
algorithms in the latter setting were for the edge count, given by
Fichtenberger, Henzinger, and Ost (ESA 21), and for releasing the values of all
graph cuts, given by Fichtenberger, Henzinger, and Upadhyay (ICML 23). We
provide the first differentially private and fully dynamic graph algorithms for
several other fundamental graph statistics (including the triangle count, the
number of connected components, the size of the maximum matching, and the
degree histogram), analyze their error and show strong lower bounds on the
error for all algorithms in this setting. We study two variants of edge
differential privacy for fully dynamic graph algorithms: event-level and
item-level. We give upper and lower bounds on the error of both event-level and
item-level fully dynamic algorithms for several fundamental graph problems. No
fully dynamic algorithms that are private at the item-level (the more stringent
of the two notions) were known before. In the case of item-level privacy, for
several problems, our algorithms match our lower bounds.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17578v1">Expanding Perspectives on Data Privacy: Insights from Rural Togo</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-09-26T06:47:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zoe Kahn, Meyebinesso Farida Carelle Pere, Emily Aiken, Nitin Kohli, Joshua E. Blumenstock</p>
    <p><b>Summary:</b> Passively collected "big" data sources are increasingly used to inform
critical development policy decisions in low- and middle-income countries.
While prior work highlights how such approaches may reveal sensitive
information, enable surveillance, and centralize power, less is known about the
corresponding privacy concerns, hopes, and fears of the people directly
impacted by these policies -- people sometimes referred to as experiential
experts. To understand the perspectives of experiential experts, we conducted
semi-structured interviews with people living in rural villages in Togo shortly
after an entirely digital cash transfer program was launched that used machine
learning and mobile phone metadata to determine program eligibility. This paper
documents participants' privacy concerns surrounding the introduction of big
data approaches in development policy. We find that the privacy concerns of our
experiential experts differ from those raised by privacy and development domain
experts. To facilitate a more robust and constructive account of privacy, we
discuss implications for policies and designs that take seriously the privacy
concerns raised by both experiential experts and domain experts.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17538v1">On the Implicit Relation Between Low-Rank Adaptation and Differential
  Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-09-26T04:56:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Saber Malekmohammadi, Golnoosh Farnadi</p>
    <p><b>Summary:</b> A significant approach in natural language processing involves large-scale
pre-training on general domain data followed by adaptation to specific tasks or
domains. As models grow in size, full fine-tuning all parameters becomes
increasingly impractical. To address this, some methods for low-rank task
adaptation of language models have been proposed, e.g. LoRA and FLoRA. These
methods keep the pre-trained model weights fixed and incorporate trainable
low-rank decomposition matrices into some layers of the transformer
architecture, called adapters. This approach significantly reduces the number
of trainable parameters required for downstream tasks compared to full
fine-tuning all parameters. In this work, we look at low-rank adaptation from
the lens of data privacy. We show theoretically that the low-rank adaptation
used in LoRA and FLoRA is equivalent to injecting some random noise into the
batch gradients w.r.t the adapter parameters coming from their full
fine-tuning, and we quantify the variance of the injected noise. By
establishing a Berry-Esseen type bound on the total variation distance between
the noise distribution and a Gaussian distribution with the same variance, we
show that the dynamics of LoRA and FLoRA are very close to differentially
private full fine-tuning the adapters, which suggests that low-rank adaptation
implicitly provides privacy w.r.t the fine-tuning data. Finally, using
Johnson-Lindenstrauss lemma, we show that when augmented with gradient
clipping, low-rank adaptation is almost equivalent to differentially private
full fine-tuning adapters with a fixed noise scale.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17535v1">Privacy-Preserving Redaction of Diagnosis Data through Source Code
  Analysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-26T04:41:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lixi Zhou, Lei Yu, Jia Zou, Hong Min</p>
    <p><b>Summary:</b> Protecting sensitive information in diagnostic data such as logs, is a
critical concern in the industrial software diagnosis and debugging process.
While there are many tools developed to automatically redact the logs for
identifying and removing sensitive information, they have severe limitations
which can cause either over redaction and loss of critical diagnostic
information (false positives), or disclosure of sensitive information (false
negatives), or both. To address the problem, in this paper, we argue for a
source code analysis approach for log redaction. To identify a log message
containing sensitive information, our method locates the corresponding log
statement in the source code with logger code augmentation, and checks if the
log statement outputs data from sensitive sources by using the data flow graph
built from the source code. Appropriate redaction rules are further applied
depending on the sensitiveness of the data sources to preserve the privacy
information in the logs. We conducted experimental evaluation and comparison
with other popular baselines. The results demonstrate that our approach can
significantly improve the detection precision of the sensitive information and
reduce both false positives and negatives.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17509v1">BioZero: An Efficient and Privacy-Preserving Decentralized Biometric
  Authentication Protocol on Open Blockchain</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-26T03:37:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Junhao Lai, Taotao Wang, Shengli Zhang, Qing Yang, Soung Chang Liew</p>
    <p><b>Summary:</b> Digital identity plays a vital role in enabling secure access to resources
and services in the digital world. Traditional identity authentication methods,
such as password-based and biometric authentications, have limitations in terms
of security, privacy, and scalability. Decentralized authentication approaches
leveraging blockchain technology have emerged as a promising solution. However,
existing decentralized authentication methods often rely on indirect identity
verification (e.g. using passwords or digital signatures as authentication
credentials) and face challenges such as Sybil attacks. In this paper, we
propose BioZero, an efficient and privacy-preserving decentralized biometric
authentication protocol that can be implemented on open blockchain. BioZero
leverages Pedersen commitment and homomorphic computation to protect user
biometric privacy while enabling efficient verification. We enhance the
protocol with non-interactive homomorphic computation and employ zero-knowledge
proofs for secure on-chain verification. The unique aspect of BioZero is that
it is fully decentralized and can be executed by blockchain smart contracts in
a very efficient way. We analyze the security of BioZero and validate its
performance through a prototype implementation. The results demonstrate the
effectiveness, efficiency, and security of BioZero in decentralized
authentication scenarios. Our work contributes to the advancement of
decentralized identity authentication using biometrics.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17315v1">KIPPS: Knowledge infusion in Privacy Preserving Synthetic Data
  Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-25T19:50:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anantaa Kotal, Anupam Joshi</p>
    <p><b>Summary:</b> The integration of privacy measures, including differential privacy
techniques, ensures a provable privacy guarantee for the synthetic data.
However, challenges arise for Generative Deep Learning models when tasked with
generating realistic data, especially in critical domains such as Cybersecurity
and Healthcare. Generative Models optimized for continuous data struggle to
model discrete and non-Gaussian features that have domain constraints.
Challenges increase when the training datasets are limited and not diverse. In
such cases, generative models create synthetic data that repeats sensitive
features, which is a privacy risk. Moreover, generative models face
difficulties comprehending attribute constraints in specialized domains. This
leads to the generation of unrealistic data that impacts downstream accuracy.
To address these issues, this paper proposes a novel model, KIPPS, that infuses
Domain and Regulatory Knowledge from Knowledge Graphs into Generative Deep
Learning models for enhanced Privacy Preserving Synthetic data generation. The
novel framework augments the training of generative models with supplementary
context about attribute values and enforces domain constraints during training.
This added guidance enhances the model's capacity to generate realistic and
domain-compliant synthetic data. The proposed model is evaluated on real-world
datasets, specifically in the domains of Cybersecurity and Healthcare, where
domain constraints and rules add to the complexity of the data. Our experiments
evaluate the privacy resilience and downstream accuracy of the model against
benchmark methods, demonstrating its effectiveness in addressing the balance
between privacy preservation and data accuracy in complex domains.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17283v1">Investigating Privacy Attacks in the Gray-Box Setting to Enhance
  Collaborative Learning Schemes</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-25T18:49:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Federico Mazzone, Ahmad Al Badawi, Yuriy Polyakov, Maarten Everts, Florian Hahn, Andreas Peter</p>
    <p><b>Summary:</b> The notion that collaborative machine learning can ensure privacy by just
withholding the raw data is widely acknowledged to be flawed. Over the past
seven years, the literature has revealed several privacy attacks that enable
adversaries to extract information about a model's training dataset by
exploiting access to model parameters during or after training. In this work,
we study privacy attacks in the gray-box setting, where the attacker has only
limited access - in terms of view and actions - to the model. The findings of
our investigation provide new insights for the development of
privacy-preserving collaborative learning solutions. We deploy SmartCryptNN, a
framework that tailors homomorphic encryption to protect the portions of the
model posing higher privacy risks. Our solution offers a trade-off between
privacy and efficiency, which varies based on the extent and selection of the
model components we choose to protect. We explore it on dense neural networks,
where through extensive evaluation of diverse datasets and architectures, we
uncover instances where a favorable sweet spot in the trade-off can be achieved
by safeguarding only a single layer of the network. In one of such instances,
our approach trains ~4 times faster compared to fully encrypted solutions,
while reducing membership leakage by 17.8 times compared to plaintext
solutions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17144v1">Differential Privacy Regularization: Protecting Training Data Through
  Loss Function Regularization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Neural and Evolutionary Computing-5BC0EB">
  <p><b>Published on:</b> 2024-09-25T17:59:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Francisco Aguilera-Martínez, Fernando Berzal</p>
    <p><b>Summary:</b> Training machine learning models based on neural networks requires large
datasets, which may contain sensitive information. The models, however, should
not expose private information from these datasets. Differentially private SGD
[DP-SGD] requires the modification of the standard stochastic gradient descent
[SGD] algorithm for training new models. In this short paper, a novel
regularization strategy is proposed to achieve the same goal in a more
efficient manner.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17201v1">Immersion and Invariance-based Coding for Privacy-Preserving Federated
  Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-09-25T15:04:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haleh Hayati, Carlos Murguia, Nathan van de Wouw</p>
    <p><b>Summary:</b> Federated learning (FL) has emerged as a method to preserve privacy in
collaborative distributed learning. In FL, clients train AI models directly on
their devices rather than sharing data with a centralized server, which can
pose privacy risks. However, it has been shown that despite FL's partial
protection of local data privacy, information about clients' data can still be
inferred from shared model updates during training. In recent years, several
privacy-preserving approaches have been developed to mitigate this privacy
leakage in FL, though they often provide privacy at the cost of model
performance or system efficiency. Balancing these trade-offs presents a
significant challenge in implementing FL schemes. In this manuscript, we
introduce a privacy-preserving FL framework that combines differential privacy
and system immersion tools from control theory. The core idea is to treat the
optimization algorithms used in standard FL schemes (e.g., gradient-based
algorithms) as a dynamical system that we seek to immerse into a
higher-dimensional system (referred to as the target optimization algorithm).
The target algorithm's dynamics are designed such that, first, the model
parameters of the original algorithm are immersed in its parameters; second, it
operates on distorted parameters; and third, it converges to an encoded version
of the true model parameters from the original algorithm. These encoded
parameters can then be decoded at the server to retrieve the original model
parameters. We demonstrate that the proposed privacy-preserving scheme can be
tailored to offer any desired level of differential privacy for both local and
global model parameters, while maintaining the same accuracy and convergence
rate as standard FL algorithms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.16777v1">PhD Forum: Efficient Privacy-Preserving Processing via Memory-Centric
  Computing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Hardware Architecture-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-09-25T09:37:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mpoki Mwaisela</p>
    <p><b>Summary:</b> Privacy-preserving computation techniques like homomorphic encryption (HE)
and secure multi-party computation (SMPC) enhance data security by enabling
processing on encrypted data. However, the significant computational and
CPU-DRAM data movement overhead resulting from the underlying cryptographic
algorithms impedes the adoption of these techniques in practice. Existing
approaches focus on improving computational overhead using specialized hardware
like GPUs and FPGAs, but these methods still suffer from the same
processor-DRAM overhead. Novel hardware technologies that support in-memory
processing have the potential to address this problem. Memory-centric
computing, or processing-in-memory (PIM), brings computation closer to data by
introducing low-power processors called data processing units (DPUs) into
memory. Besides its in-memory computation capability, PIM provides extensive
parallelism, resulting in significant performance improvement over
state-of-the-art approaches. We propose a framework that uses recently
available PIM hardware to achieve efficient privacy-preserving computation. Our
design consists of a four-layer architecture: (1) an application layer that
decouples privacy-preserving applications from the underlying protocols and
hardware; (2) a protocol layer that implements existing secure computation
protocols (HE and MPC); (3) a data orchestration layer that leverages data
compression techniques to mitigate the data transfer overhead between DPUs and
host memory; (4) a computation layer which implements DPU kernels on which
secure computation algorithms are built.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.16688v2">Cycle Counting under Local Differential Privacy for Degeneracy-bounded
  Graphs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2024-09-25T07:23:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Quentin Hillebrand, Vorapong Suppakitpaisarn, Tetsuo Shibuya</p>
    <p><b>Summary:</b> We propose an algorithm for counting the number of cycles under local
differential privacy for degeneracy-bounded input graphs. Numerous studies have
focused on counting the number of triangles under the privacy notion,
demonstrating that the expected $\ell_2$-error of these algorithms is
$\Omega(n^{1.5})$, where $n$ is the number of nodes in the graph. When
parameterized by the number of cycles of length four ($C_4$), the best existing
triangle counting algorithm has an error of $O(n^{1.5} + \sqrt{C_4}) = O(n^2)$.
In this paper, we introduce an algorithm with an expected $\ell_2$-error of
$O(\delta^{1.5} n^{0.5} + \delta^{0.5} d_{\max}^{0.5} n^{0.5})$, where $\delta$
is the degeneracy and $d_{\max}$ is the maximum degree of the graph. For
degeneracy-bounded graphs ($\delta \in \Theta(1)$) commonly found in practical
social networks, our algorithm achieves an expected $\ell_2$-error of
$O(d_{\max}^{0.5} n^{0.5}) = O(n)$. Our algorithm's core idea is a precise
count of triangles following a preprocessing step that approximately sorts the
degree of all nodes. This approach can be extended to approximate the number of
cycles of length $k$, maintaining a similar $\ell_2$-error, namely
$O(\delta^{(k-2)/2} d_{\max}^{0.5} n^{(k-2)/2} + \delta^{k/2} n^{(k-2)/2})$ or
$O(d_{\max}^{0.5} n^{(k-2)/2}) = O(n^{(k-1)/2})$ for degeneracy-bounded graphs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.16621v1">Entailment-Driven Privacy Policy Classification with LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-09-25T05:07:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bhanuka Silva, Dishanika Denipitiyage, Suranga Seneviratne, Anirban Mahanti, Aruna Seneviratne</p>
    <p><b>Summary:</b> While many online services provide privacy policies for end users to read and
understand what personal data are being collected, these documents are often
lengthy and complicated. As a result, the vast majority of users do not read
them at all, leading to data collection under uninformed consent. Several
attempts have been made to make privacy policies more user friendly by
summarising them, providing automatic annotations or labels for key sections,
or by offering chat interfaces to ask specific questions. With recent advances
in Large Language Models (LLMs), there is an opportunity to develop more
effective tools to parse privacy policies and help users make informed
decisions. In this paper, we propose an entailment-driven LLM based framework
to classify paragraphs of privacy policies into meaningful labels that are
easily understood by users. The results demonstrate that our framework
outperforms traditional LLM methods, improving the F1 score in average by
11.2%. Additionally, our framework provides inherently explainable and
meaningful predictions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.16340v1">Future-Proofing Medical Imaging with Privacy-Preserving Federated
  Learning and Uncertainty Quantification: A Review</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-09-24T16:55:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nikolas Koutsoubis, Asim Waqas, Yasin Yilmaz, Ravi P. Ramachandran, Matthew Schabath, Ghulam Rasool</p>
    <p><b>Summary:</b> Artificial Intelligence (AI) has demonstrated significant potential in
automating various medical imaging tasks, which could soon become routine in
clinical practice for disease diagnosis, prognosis, treatment planning, and
post-treatment surveillance. However, the privacy concerns surrounding patient
data present a major barrier to the widespread adoption of AI in medical
imaging, as large, diverse training datasets are essential for developing
accurate, generalizable, and robust Artificial intelligence models. Federated
Learning (FL) offers a solution that enables organizations to train AI models
collaboratively without sharing sensitive data. federated learning exchanges
model training information, such as gradients, between the participating sites.
Despite its promise, federated learning is still in its developmental stages
and faces several challenges. Notably, sensitive information can still be
inferred from the gradients shared during model training. Quantifying AI
models' uncertainty is vital due to potential data distribution shifts
post-deployment, which can affect model performance. Uncertainty quantification
(UQ) in FL is particularly challenging due to data heterogeneity across
participating sites. This review provides a comprehensive examination of FL,
privacy-preserving FL (PPFL), and UQ in FL. We identify key gaps in current FL
methodologies and propose future research directions to enhance data privacy
and trustworthiness in medical imaging applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.16106v2">Scenario of Use Scheme: Threat Model Specification for Speaker Privacy
  Protection in the Medical Domain</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36">
  <p><b>Published on:</b> 2024-09-24T14:07:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mehtab Ur Rahman, Martha Larson, Louis ten Bosch, Cristian Tejedor-García</p>
    <p><b>Summary:</b> Speech recordings are being more frequently used to detect and monitor
disease, leading to privacy concerns. Beyond cryptography, protection of speech
can be addressed by approaches, such as perturbation, disentanglement, and
re-synthesis, that eliminate sensitive information of the speaker, leaving the
information necessary for medical analysis purposes. In order for such privacy
protective approaches to be developed, clear and systematic specifications of
assumptions concerning medical settings and the needs of medical professionals
are necessary. In this paper, we propose a Scenario of Use Scheme that
incorporates an Attacker Model, which characterizes the adversary against whom
the speaker's privacy must be defended, and a Protector Model, which specifies
the defense. We discuss the connection of the scheme with previous work on
speech privacy. Finally, we present a concrete example of a specified Scenario
of Use and a set of experiments about protecting speaker data against gender
inference attacks while maintaining utility for Parkinson's detection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.15868v3">Privacy Evaluation Benchmarks for NLP Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-09-24T08:41:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wei Huang, Yinggui Wang, Cen Chen</p>
    <p><b>Summary:</b> By inducing privacy attacks on NLP models, attackers can obtain sensitive
information such as training data and model parameters, etc. Although
researchers have studied, in-depth, several kinds of attacks in NLP models,
they are non-systematic analyses. It lacks a comprehensive understanding of the
impact caused by the attacks. For example, we must consider which scenarios can
apply to which attacks, what the common factors are that affect the performance
of different attacks, the nature of the relationships between different
attacks, and the influence of various datasets and models on the effectiveness
of the attacks, etc. Therefore, we need a benchmark to holistically assess the
privacy risks faced by NLP models. In this paper, we present a privacy attack
and defense evaluation benchmark in the field of NLP, which includes the
conventional/small models and large language models (LLMs). This benchmark
supports a variety of models, datasets, and protocols, along with standardized
modules for comprehensive evaluation of attacks and defense strategies. Based
on the above framework, we present a study on the association between auxiliary
data from different domains and the strength of privacy attacks. And we provide
an improved attack method in this scenario with the help of Knowledge
Distillation (KD). Furthermore, we propose a chained framework for privacy
attacks. Allowing a practitioner to chain multiple attacks to achieve a
higher-level attack objective. Based on this, we provide some defense and
enhanced attack strategies. The code for reproducing the results can be found
at https://github.com/user2311717757/nlp_doctor.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.15656v1">Identified-and-Targeted: The First Early Evidence of the
  Privacy-Invasive Use of Browser Fingerprinting for Online Tracking</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-24T01:39:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zengrui Liu, Jimmy Dani, Shujiang Wu, Yinzhi Cao, Nitesh Saxena</p>
    <p><b>Summary:</b> While advertising has become commonplace in today's online interactions,
there is a notable dearth of research investigating the extent to which browser
fingerprinting is harnessed for user tracking and targeted advertising. Prior
studies only measured whether fingerprinting-related scripts are being run on
the websites but that in itself does not necessarily mean that fingerprinting
is being used for the privacy-invasive purpose of online tracking because
fingerprinting might be deployed for the defensive purposes of bot/fraud
detection and user authentication. It is imperative to address the mounting
concerns regarding the utilization of browser fingerprinting in the realm of
online advertising.
  To understand the privacy-invasive use of fingerprinting for user tracking,
this paper introduces a new framework ``FPTrace'' (fingerprinting-based
tracking assessment and comprehensive evaluation framework) designed to
identify alterations in advertisements resulting from adjustments in browser
fingerprinting settings. Our approach involves emulating genuine user
interactions, capturing advertiser bid data, and closely monitoring HTTP
information. Using FPTrace we conduct a large-scale measurement study to
identify whether browser fingerprinting is being used for the purpose of user
tracking and ad targeting. The results we have obtained provide robust evidence
supporting the utilization of browser fingerprinting for the purposes of
advertisement tracking and targeting. This is substantiated by significant
disparities in bid values and a reduction in HTTP records subsequent to changes
in fingerprinting. In conclusion, our research unveils the widespread
employment of browser fingerprinting in online advertising, prompting critical
considerations regarding user privacy and data security within the digital
advertising landscape.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.15561v1">Analyzing Privacy Implications of Data Collection in Android Automotive
  OS</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-23T21:35:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bulut Gözübüyük, Brian Tang, Kang G. Shin, Mert D. Pesé</p>
    <p><b>Summary:</b> Modern vehicles have become sophisticated computation and sensor systems, as
evidenced by advanced driver assistance systems, in-car infotainment, and
autonomous driving capabilities. They collect and process vast amounts of data
through various embedded subsystems. One significant player in this landscape
is Android Automotive OS (AAOS), which has been integrated into over 100M
vehicles and has become a dominant force in the in-vehicle infotainment market.
With this extensive data collection, privacy has become increasingly crucial.
The volume of data gathered by these systems raises questions about how this
information is stored, used, and protected, making privacy a critical issue for
manufacturers and consumers. However, very little has been done on vehicle data
privacy. This paper focuses on the privacy implications of AAOS, examining the
exact nature and scope of data collection and the corresponding privacy
policies from the original equipment manufacturers (OEMs). We develop a novel
automotive privacy analysis tool called PriDrive which employs three
methodological approaches: network traffic inspection, and both static and
dynamic analyses of Android images using rooted emulators from various OEMs.
These methodologies are followed by an assessment of whether the collected data
types were properly disclosed in OEMs and 3rd party apps' privacy policies (to
identify any discrepancies or violations). Our evaluation on three different
OEM platforms reveals that vehicle speed is collected at a sampling rate of
roughly 25 Hz. Other properties such as model info, climate & AC, and seat data
are collected in a batch 30 seconds into vehicle startup. In addition, several
vehicle property types were collected without disclosure in their respective
privacy policies. For example, OEM A's policies only covers 110 vehicle
properties or 13.02% of the properties found in our static analysis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.14919v1">Voice Conversion-based Privacy through Adversarial Information Hiding</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> 
  <p><b>Published on:</b> 2024-09-23T11:16:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jacob J Webber, Oliver Watts, Gustav Eje Henter, Jennifer Williams, Simon King</p>
    <p><b>Summary:</b> Privacy-preserving voice conversion aims to remove only the attributes of
speech audio that convey identity information, keeping other speech
characteristics intact. This paper presents a mechanism for privacy-preserving
voice conversion that allows controlling the leakage of identity-bearing
information using adversarial information hiding. This enables a deliberate
trade-off between maintaining source-speech characteristics and modification of
speaker identity. As such, the approach improves on voice-conversion techniques
like CycleGAN and StarGAN, which were not designed for privacy, meaning that
converted speech may leak personal information in unpredictable ways. Our
approach is also more flexible than ASR-TTS voice conversion pipelines, which
by design discard all prosodic information linked to textual content.
Evaluations show that the proposed system successfully modifies perceived
speaker identity whilst well maintaining source lexical content.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.14879v1">Privacy Policy Analysis through Prompt Engineering for LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2024-09-23T10:23:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arda Goknil, Femke B. Gelderblom, Simeon Tverdal, Shukun Tokas, Hui Song</p>
    <p><b>Summary:</b> Privacy policies are often obfuscated by their complexity, which impedes
transparency and informed consent. Conventional machine learning approaches for
automatically analyzing these policies demand significant resources and
substantial domain-specific training, causing adaptability issues. Moreover,
they depend on extensive datasets that may require regular maintenance due to
changing privacy concerns.
  In this paper, we propose, apply, and assess PAPEL (Privacy Policy Analysis
through Prompt Engineering for LLMs), a framework harnessing the power of Large
Language Models (LLMs) through prompt engineering to automate the analysis of
privacy policies. PAPEL aims to streamline the extraction, annotation, and
summarization of information from these policies, enhancing their accessibility
and comprehensibility without requiring additional model training. By
integrating zero-shot, one-shot, and few-shot learning approaches and the
chain-of-thought prompting in creating predefined prompts and prompt templates,
PAPEL guides LLMs to efficiently dissect, interpret, and synthesize the
critical aspects of privacy policies into user-friendly summaries. We
demonstrate the effectiveness of PAPEL with two applications: (i) annotation
and (ii) contradiction analysis. We assess the ability of several LLaMa and GPT
models to identify and articulate data handling practices, offering insights
comparable to existing automated analysis approaches while reducing training
efforts and increasing the adaptability to new analytical needs. The
experiments demonstrate that the LLMs PAPEL utilizes (LLaMA and Chat GPT
models) achieve robust performance in privacy policy annotation, with F1 scores
reaching 0.8 and above (using the OPP-115 gold standard), underscoring the
effectiveness of simpler prompts across various advanced language models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.14798v1">PrivaMatch: A Privacy-Preserving DNA Matching Scheme for Forensic
  Investigation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-23T08:22:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sankha Das</p>
    <p><b>Summary:</b> DNA fingerprinting and matching for identifying suspects has been a common
practice in criminal investigation. Such proceedings involve multiple parties
such as investigating agencies, suspects and forensic labs. A major challenge
in such settings is to carry out the matching process between the suspects' DNA
samples and the samples obtained from the crime scene without compromising the
privacy of the suspects' DNA profiles. Additionally, it is necessary that
sensitive details pertaining to the investigation such as the identities of the
suspects and evidence obtained from the crime scene must be kept private to the
investigating agency. We present a novel DNA matching scheme, termed as
PrivaMatch, which addresses multiple concerns about privacy of the suspects'
DNA profiles and the crime scene evidence. In the proposed scheme, the
investigating agencies oblivious transfer and zero-knowledge proofs to
privately obtain the DNA profiles of the suspects from the forensic lab's
database.In addition, we present a clever data obfuscation technique using
homomorphic encryption and modular arithmetic for the investigating agency to
privately obtain the DNA profile of the crime scene's sample, keeping the
profile oblivious from the forensic lab. The DNA profile of the crime scene
sample is operated on using a homomorphic cryptosystem such that neither of the
parties (e.g., the investigation agency, forensic labs, DNA database owners)
learns about the private data of the other parties. The proposed scheme is
analysed formally and the practicality of its security strengths is verified
using simulations under standard assumptions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.14499v1">A Review of Scalable and Privacy-Preserving Multi-Agent Frameworks for
  Distributed Energy Resource Control</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E">
  <p><b>Published on:</b> 2024-09-22T15:52:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiang Huo, Hao Huang, Katherine R. Davis, H. Vincent Poor, Mingxi Liu</p>
    <p><b>Summary:</b> Distributed energy resources (DERs) are gaining prominence due to their
advantages in improving energy efficiency, reducing carbon emissions, and
enhancing grid resilience. Despite the increasing deployment, the potential of
DERs has yet to be fully explored and exploited. A fundamental question
restrains the management of numerous DERs in large-scale power systems, "How
should DER data be securely processed and DER operations be efficiently
optimized?" To address this question, this paper considers two critical issues,
namely privacy for processing DER data and scalability in optimizing DER
operations, then surveys existing and emerging solutions from a multi-agent
framework perspective. In the context of scalability, this paper reviews
state-of-the-art research that relies on parallel control, optimization, and
learning within distributed and/or decentralized information exchange
structures, while in the context of privacy, it identifies privacy preservation
measures that can be synthesized into the aforementioned scalable structures.
Despite research advances in these areas, challenges remain because these
highly interdisciplinary studies blend a wide variety of scalable computing
architectures and privacy preservation techniques from different fields, making
them difficult to adapt in practice. To mitigate this issue, this paper
provides a holistic review of trending strategies that orchestrate privacy and
scalability for large-scale power system operations from a multi-agent
perspective, particularly for DER control problems. Furthermore, this review
extrapolates new approaches for future scalable, privacy-aware, and cybersecure
pathways to unlock the full potential of DERs through controlling, optimizing,
and learning generic multi-agent-based cyber-physical systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.14472v1">Blockchain Based Information Security and Privacy Protection: Challenges
  and Future Directions using Computational Literature Review</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-22T14:41:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gauri Shankar, Md Raihan Uddin, Saddam Mukta, Prabhat Kumar, Shareeful Islam, A. K. M. Najmul Islam</p>
    <p><b>Summary:</b> Blockchain technology is an emerging digital innovation that has gained
immense popularity in enhancing individual security and privacy within
Information Systems (IS). This surge in interest is reflected in the
exponential increase in research articles published on blockchain technology,
highlighting its growing significance in the digital landscape. However, the
rapid proliferation of published research presents significant challenges for
manual analysis and synthesis due to the vast volume of information. The
complexity and breadth of topics, combined with the inherent limitations of
human data processing capabilities, make it difficult to comprehensively
analyze and draw meaningful insights from the literature. To this end, we
adopted the Computational Literature Review (CLR) to analyze pertinent
literature impact and topic modelling using the Latent Dirichlet Allocation
(LDA) technique. We identified 10 topics related to security and privacy and
provided a detailed description of each topic. From the critical analysis, we
have observed several limitations, and several future directions are provided
as an outcome of this review.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.14457v1">Large Model Agents: State-of-the-Art, Cooperation Paradigms, Security
  and Privacy, and Future Trends</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-09-22T14:09:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuntao Wang, Yanghe Pan, Quan Zhao, Yi Deng, Zhou Su, Linkang Du, Tom H. Luan</p>
    <p><b>Summary:</b> Large Model (LM) agents, powered by large foundation models such as GPT-4 and
DALL-E 2, represent a significant step towards achieving Artificial General
Intelligence (AGI). LM agents exhibit key characteristics of autonomy,
embodiment, and connectivity, allowing them to operate across physical,
virtual, and mixed-reality environments while interacting seamlessly with
humans, other agents, and their surroundings. This paper provides a
comprehensive survey of the state-of-the-art in LM agents, focusing on the
architecture, cooperation paradigms, security, privacy, and future prospects.
Specifically, we first explore the foundational principles of LM agents,
including general architecture, key components, enabling technologies, and
modern applications. Then, we discuss practical collaboration paradigms from
data, computation, and knowledge perspectives towards connected intelligence of
LM agents. Furthermore, we systematically analyze the security vulnerabilities
and privacy breaches associated with LM agents, particularly in multi-agent
settings. We also explore their underlying mechanisms and review existing and
potential countermeasures. Finally, we outline future research directions for
building robust and secure LM agent ecosystems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.14261v1">Re-Evaluating Privacy in Centralized and Decentralized Learning: An
  Information-Theoretical and Empirical Study</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-21T23:05:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Changlong Ji, Stephane Maag, Richard Heusdens, Qiongxiu Li</p>
    <p><b>Summary:</b> Decentralized Federated Learning (DFL) has garnered attention for its
robustness and scalability compared to Centralized Federated Learning (CFL).
While DFL is commonly believed to offer privacy advantages due to the
decentralized control of sensitive data, recent work by Pasquini et, al.
challenges this view, demonstrating that DFL does not inherently improve
privacy against empirical attacks under certain assumptions. For investigating
fully this issue, a formal theoretical framework is required. Our study offers
a novel perspective by conducting a rigorous information-theoretical analysis
of privacy leakage in FL using mutual information. We further investigate the
effectiveness of privacy-enhancing techniques like Secure Aggregation (SA) in
both CFL and DFL. Our simulations and real-world experiments show that DFL
generally offers stronger privacy preservation than CFL in practical scenarios
where a fully trusted server is not available. We address discrepancies in
previous research by highlighting limitations in their assumptions about graph
topology and privacy attacks, which inadequately capture information leakage in
FL.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.14039v1">Towards Lightweight and Privacy-preserving Data Provision in Digital
  Forensics for Driverless Taxi</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-21T06:51:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yanwei Gong, Xiaolin Chang, Jelena Mišić, Vojislav B. Mišić, Junchao Fan, Kaiwen Wang</p>
    <p><b>Summary:</b> Data provision, referring to the data upload and data access, is one key
phase in vehicular digital forensics. The unique features of Driverless Taxi
(DT) bring new issues to this phase: 1) efficient verification of data
integrity when diverse Data Providers (DPs) upload data; 2) DP privacy
preservation during data upload; and 3) privacy preservation of both data and
INvestigator (IN) under complex data ownership when accessing data. To this
end, we propose a novel Lightweight and Privacy-preserving Data Provision
(LPDP) approach consisting of three mechanisms: 1) the Privacy-friendly Batch
Verification Mechanism (PBVm) based on elliptic curve cryptography, 2) Data
Access Control Mechanism (DACm) based on ciphertext-policy attribute-based
encryption, and 3) Decentralized IN Warrant Issuance Mechanism (DIWIm) based on
secret sharing. Privacy preservation of data provision is achieved through: 1)
ensuring the DP privacy preservation in terms of the location privacy and
unlinkability of data upload requests by PBVm, 2) ensuring data privacy
preservation by DACm and DIWIm, and 3) ensuring the identity privacy of IN in
terms of the anonymity and unlinkability of data access requests without
sacrificing the traceability. Lightweight of data provision is achieved
through: 1) ensuring scalable verification of data integrity by PBVm, and 2)
ensuring low-overhead warrant update with respect to DIWIm. Security analysis
and performance evaluation are conducted to validate the security and
performance features of LPDP.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.13953v1">Training Large ASR Encoders with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2024-09-21T00:01:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Geeticka Chauhan, Steve Chien, Om Thakkar, Abhradeep Thakurta, Arun Narayanan</p>
    <p><b>Summary:</b> Self-supervised learning (SSL) methods for large speech models have proven to
be highly effective at ASR. With the interest in public deployment of large
pre-trained models, there is a rising concern for unintended memorization and
leakage of sensitive data points from the training data. In this paper, we
apply differentially private (DP) pre-training to a SOTA Conformer-based
encoder, and study its performance on a downstream ASR task assuming the
fine-tuning data is public. This paper is the first to apply DP to SSL for ASR,
investigating the DP noise tolerance of the BEST-RQ pre-training method.
Notably, we introduce a novel variant of model pruning called gradient-based
layer freezing that provides strong improvements in privacy-utility-compute
trade-offs. Our approach yields a LibriSpeech test-clean/other WER (%) of 3.78/
8.41 with ($10$, 1e^-9)-DP for extrapolation towards low dataset scales, and
2.81/ 5.89 with (10, 7.9e^-11)-DP for extrapolation towards high scales.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.13875v1">Data Distribution Shifts in (Industrial) Federated Learning as a Privacy
  Issue</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-20T20:09:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> David Brunner, Alessio Montuoro</p>
    <p><b>Summary:</b> We consider industrial federated learning, a collaboration between a small
number of powerful, potentially competing industrial players, mediated by a
third party aspiring to improve the service it provides to its customers. We
argue that this configuration harbours covert privacy risks that do not arise
in e.g. cross-device settings. Companies are very protective of their
intellectual property and production processes. Information about changes to
their production and the timing of which is to be kept private. We study a
scenario in which one of the collaborators infers changes to their competitors'
production by detecting potentially subtle temporal data distribution shifts.
In this framing, a data distribution shift is always problematic, even if it
has no negative effect on training convergence. Thus, our goal is to find means
that allow the detection of distributional shifts better than customary
evaluation metrics. Based on the assumption that even minor shifts translate
into the collaboratively learned machine learning model, the attacker tracks
the shared models' internal state with a selection of metrics from literature
in order to pick up on relevant changes. In an empirical study on benchmark
datasets, we show an honest-but-curious attacker to be capable of detecting
subtle distributional shifts on other clients, in some cases long before they
become obvious in evaluation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.12874v1">Privacy-Preserving Framework for Cell-Free MIMO ISAC Systems</a></h3>
  
  <p><b>Published on:</b> 2024-09-19T16:13:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Henrik Åkesson, Diana Pamela Moya Osorio</p>
    <p><b>Summary:</b> Integrated Sensing and Communication (ISAC) systems are prone to privacy
violations, once they aim at handling sensitive identifiable information in
several applications. This paper raises the necessity of implementing
privacy-preservation measures on the design of cell-free massive multiple-input
multiple-output ISAC systems. To that purpose, given an adversary model, we
propose an iterative framework of two blocks, precoder design and access point
selection. The precoder design aims at maximizing the
signal-to-interference-plus-noise ratio at the sensing receivers given
communication constraints. The access point selection aims at minimizing the
mutual information between the received signal at users and the sensing signal,
by rearranging the access points that transmit ISAC-signals and the sensing
receivers. Results show that a reduction in the probability of detection by the
adversary is obtained with this method.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.12651v1">A Deep Dive into Fairness, Bias, Threats, and Privacy in Recommender
  Systems: Insights and Future Research</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-09-19T11:00:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Falguni Roy, Xiaofeng Ding, K. -K. R. Choo, Pan Zhou</p>
    <p><b>Summary:</b> Recommender systems are essential for personalizing digital experiences on
e-commerce sites, streaming services, and social media platforms. While these
systems are necessary for modern digital interactions, they face fairness,
bias, threats, and privacy challenges. Bias in recommender systems can result
in unfair treatment of specific users and item groups, and fairness concerns
demand that recommendations be equitable for all users and items. These systems
are also vulnerable to various threats that compromise reliability and
security. Furthermore, privacy issues arise from the extensive use of personal
data, making it crucial to have robust protection mechanisms to safeguard user
information. This study explores fairness, bias, threats, and privacy in
recommender systems. It examines how algorithmic decisions can unintentionally
reinforce biases or marginalize specific user and item groups, emphasizing the
need for fair recommendation strategies. The study also looks at the range of
threats in the form of attacks that can undermine system integrity and
discusses advanced privacy-preserving techniques. By addressing these critical
areas, the study highlights current limitations and suggests future research
directions to improve recommender systems' robustness, fairness, and privacy.
Ultimately, this research aims to help develop more trustworthy and ethical
recommender systems that better serve diverse user populations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.12384v1">Privacy-Preserving Student Learning with Differentially Private
  Data-Free Distillation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-09-19T01:00:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bochao Liu, Jianghu Lu, Pengju Wang, Junjie Zhang, Dan Zeng, Zhenxing Qian, Shiming Ge</p>
    <p><b>Summary:</b> Deep learning models can achieve high inference accuracy by extracting rich
knowledge from massive well-annotated data, but may pose the risk of data
privacy leakage in practical deployment. In this paper, we present an effective
teacher-student learning approach to train privacy-preserving deep learning
models via differentially private data-free distillation. The main idea is
generating synthetic data to learn a student that can mimic the ability of a
teacher well-trained on private data. In the approach, a generator is first
pretrained in a data-free manner by incorporating the teacher as a fixed
discriminator. With the generator, massive synthetic data can be generated for
model training without exposing data privacy. Then, the synthetic data is fed
into the teacher to generate private labels. Towards this end, we propose a
label differential privacy algorithm termed selective randomized response to
protect the label information. Finally, a student is trained on the synthetic
data with the supervision of private labels. In this way, both data privacy and
label privacy are well protected in a unified framework, leading to
privacy-preserving models. Extensive experiments and analysis clearly
demonstrate the effectiveness of our approach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.12341v1">Provable Privacy Guarantee for Individual Identities and Locations in
  Large-Scale Contact Tracing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-18T22:19:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tyler Nicewarner, Wei Jiang, Aniruddha Gokhale, Dan Lin</p>
    <p><b>Summary:</b> The task of infectious disease contact tracing is crucial yet challenging,
especially when meeting strict privacy requirements. Previous attempts in this
area have had limitations in terms of applicable scenarios and efficiency. Our
paper proposes a highly scalable, practical contact tracing system called
PREVENT that can work with a variety of location collection methods to gain a
comprehensive overview of a person's trajectory while ensuring the privacy of
individuals being tracked, without revealing their plain text locations to any
party, including servers. Our system is very efficient and can provide
real-time query services for large-scale datasets with millions of locations.
This is made possible by a newly designed secret-sharing based architecture
that is tightly integrated into unique private space partitioning trees.
Notably, our experimental results on both real and synthetic datasets
demonstrate that our system introduces negligible performance overhead compared
to traditional contact tracing methods. PREVENT could be a game-changer in the
fight against infectious diseases and set a new standard for privacy-preserving
location tracking.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.11845v1">Law-based and standards-oriented approach for privacy impact assessment
  in medical devices: a topic for lawyers, engineers and healthcare
  practitioners in MedTech</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-09-18T09:56:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuri R. Ladeia, David M. Pereira</p>
    <p><b>Summary:</b> Background: The integration of the General Data Protection Regulation (GDPR)
and the Medical Device Regulation (MDR) creates complexities in conducting Data
Protection Impact Assessments (DPIAs) for medical devices. The adoption of
non-binding standards like ISO and IEC can harmonize these processes by
enhancing accountability and privacy by design. Methods: This study employs a
multidisciplinary literature review, focusing on GDPR and MDR intersection in
medical devices that process personal health data. It evaluates key standards,
including ISO/IEC 29134 and IEC 62304, to propose a unified approach for DPIAs
that aligns with legal and technical frameworks. Results: The analysis reveals
the benefits of integrating ISO/IEC standards into DPIAs, which provide
detailed guidance on implementing privacy by design, risk assessment, and
mitigation strategies specific to medical devices. The proposed framework
ensures that DPIAs are living documents, continuously updated to adapt to
evolving data protection challenges. Conclusions: A unified approach combining
European Union (EU) regulations and international standards offers a robust
framework for conducting DPIAs in medical devices. This integration balances
security, innovation, and privacy, enhancing compliance and fostering trust in
medical technologies. The study advocates for leveraging both hard law and
standards to systematically address privacy and safety in the design and
operation of medical devices, thereby raising the maturity of the MedTech
ecosystem.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.11805v1">Inside Out or Not: Privacy Implications of Emotional Disclosure</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-09-18T08:42:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Elham Naghizade, Kaixin Ji, Benjamin Tag, Flora Salim</p>
    <p><b>Summary:</b> Privacy is dynamic, sensitive, and contextual, much like our emotions.
Previous studies have explored the interplay between privacy and context,
privacy and emotion, and emotion and context. However, there remains a
significant gap in understanding the interplay of these aspects simultaneously.
In this paper, we present a preliminary study investigating the role of
emotions in driving individuals' information sharing behaviour, particularly in
relation to urban locations and social ties. We adopt a novel methodology that
integrates context (location and time), emotion, and personal information
sharing behaviour, providing a comprehensive analysis of how contextual
emotions affect privacy. The emotions are assessed with both self-reporting and
electrodermal activity (EDA). Our findings reveal that self-reported emotions
influence personal information-sharing behaviour with distant social groups,
while neutral emotions lead individuals to share less precise information with
close social circles, a pattern is potentially detectable with wrist-worn EDA.
Our study helps lay the foundation for personalised emotion-aware strategies to
mitigate oversharing risks and enhance user privacy in the digital age.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.11680v1">What to Consider When Considering Differential Privacy for Policy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-18T03:41:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Priyanka Nanayakkara, Jessica Hullman</p>
    <p><b>Summary:</b> Differential privacy (DP) is a mathematical definition of privacy that can be
widely applied when publishing data. DP has been recognized as a potential
means of adhering to various privacy-related legal requirements. However, it
can be difficult to reason about whether DP may be appropriate for a given
context due to tensions that arise when it is brought from theory into
practice. To aid policymaking around privacy concerns, we identify three
categories of challenges to understanding DP along with associated questions
that policymakers can ask about the potential deployment context to anticipate
its impacts.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.11536v1">Obfuscation Based Privacy Preserving Representations are Recoverable
  Using Neighborhood Information</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-09-17T20:13:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kunal Chelani, Assia Benbihi, Fredrik Kahl, Torsten Sattler, Zuzana Kukelova</p>
    <p><b>Summary:</b> Rapid growth in the popularity of AR/VR/MR applications and cloud-based
visual localization systems has given rise to an increased focus on the privacy
of user content in the localization process.
  This privacy concern has been further escalated by the ability of deep neural
networks to recover detailed images of a scene from a sparse set of 3D or 2D
points and their descriptors - the so-called inversion attacks.
  Research on privacy-preserving localization has therefore focused on
preventing these inversion attacks on both the query image keypoints and the 3D
points of the scene map.
  To this end, several geometry obfuscation techniques that lift points to
higher-dimensional spaces, i.e., lines or planes, or that swap coordinates
between points % have been proposed.
  In this paper, we point to a common weakness of these obfuscations that
allows to recover approximations of the original point positions under the
assumption of known neighborhoods.
  We further show that these neighborhoods can be computed by learning to
identify descriptors that co-occur in neighborhoods.
  Extensive experiments show that our approach for point recovery is
practically applicable to all existing geometric obfuscation schemes.
  Our results show that these schemes should not be considered
privacy-preserving, even though they are claimed to be privacy-preserving.
  Code will be available at
\url{https://github.com/kunalchelani/RecoverPointsNeighborhood}.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.11295v1">EIA: Environmental Injection Attack on Generalist Web Agents for Privacy
  Leakage</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-09-17T15:49:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zeyi Liao, Lingbo Mo, Chejian Xu, Mintong Kang, Jiawei Zhang, Chaowei Xiao, Yuan Tian, Bo Li, Huan Sun</p>
    <p><b>Summary:</b> Generalist web agents have evolved rapidly and demonstrated remarkable
potential. However, there are unprecedented safety risks associated with these
them, which are nearly unexplored so far. In this work, we aim to narrow this
gap by conducting the first study on the privacy risks of generalist web agents
in adversarial environments. First, we present a threat model that discusses
the adversarial targets, constraints, and attack scenarios. Particularly, we
consider two types of adversarial targets: stealing users' specific personally
identifiable information (PII) or stealing the entire user request. To achieve
these objectives, we propose a novel attack method, termed Environmental
Injection Attack (EIA). This attack injects malicious content designed to adapt
well to different environments where the agents operate, causing them to
perform unintended actions. This work instantiates EIA specifically for the
privacy scenario. It inserts malicious web elements alongside persuasive
instructions that mislead web agents into leaking private information, and can
further leverage CSS and JavaScript features to remain stealthy. We collect 177
actions steps that involve diverse PII categories on realistic websites from
the Mind2Web dataset, and conduct extensive experiments using one of the most
capable generalist web agent frameworks to date, SeeAct. The results
demonstrate that EIA achieves up to 70% ASR in stealing users' specific PII.
Stealing full user requests is more challenging, but a relaxed version of EIA
can still achieve 16% ASR. Despite these concerning results, it is important to
note that the attack can still be detectable through careful human inspection,
highlighting a trade-off between high autonomy and security. This leads to our
detailed discussion on the efficacy of EIA under different levels of human
supervision as well as implications on defenses for generalist web agents.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.10667v1">Benchmarking Secure Sampling Protocols for Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-16T19:04:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yucheng Fu, Tianhao Wang</p>
    <p><b>Summary:</b> Differential privacy (DP) is widely employed to provide privacy protection
for individuals by limiting information leakage from the aggregated data. Two
well-known models of DP are the central model and the local model. The former
requires a trustworthy server for data aggregation, while the latter requires
individuals to add noise, significantly decreasing the utility of aggregated
results. Recently, many studies have proposed to achieve DP with Secure
Multi-party Computation (MPC) in distributed settings, namely, the distributed
model, which has utility comparable to central model while, under specific
security assumptions, preventing parties from obtaining others' information.
One challenge of realizing DP in distributed model is efficiently sampling
noise with MPC. Although many secure sampling methods have been proposed, they
have different security assumptions and isolated theoretical analyses. There is
a lack of experimental evaluations to measure and compare their performances.
We fill this gap by benchmarking existing sampling protocols in MPC and
performing comprehensive measurements of their efficiency. First, we present a
taxonomy of the underlying techniques of these sampling protocols. Second, we
extend widely used distributed noise generation protocols to be resilient
against Byzantine attackers. Third, we implement discrete sampling protocols
and align their security settings for a fair comparison. We then conduct an
extensive evaluation to study their efficiency and utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.10411v1">A Large-Scale Privacy Assessment of Android Third-Party SDKs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2024-09-16T15:44:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mark Huasong Meng, Chuan Yan, Yun Hao, Qing Zhang, Zeyu Wang, Kailong Wang, Sin Gee Teo, Guangdong Bai, Jin Song Dong</p>
    <p><b>Summary:</b> Third-party Software Development Kits (SDKs) are widely adopted in Android
app development, to effortlessly accelerate development pipelines and enhance
app functionality. However, this convenience raises substantial concerns about
unauthorized access to users' privacy-sensitive information, which could be
further abused for illegitimate purposes like user tracking or monetization.
Our study offers a targeted analysis of user privacy protection among Android
third-party SDKs, filling a critical gap in the Android software supply chain.
It focuses on two aspects of their privacy practices, including data
exfiltration and behavior-policy compliance (or privacy compliance), utilizing
techniques of taint analysis and large language models. It covers 158
widely-used SDKs from two key SDK release platforms, the official one and a
large alternative one. From them, we identified 338 instances of privacy data
exfiltration. On the privacy compliance, our study reveals that more than 30%
of the examined SDKs fail to provide a privacy policy to disclose their data
handling practices. Among those that provide privacy policies, 37% of them
over-collect user data, and 88% falsely claim access to sensitive data. We
revisit the latest versions of the SDKs after 12 months. Our analysis
demonstrates a persistent lack of improvement in these concerning trends. Based
on our findings, we propose three actionable recommendations to mitigate the
privacy leakage risks and enhance privacy protection for Android users. Our
research not only serves as an urgent call for industry attention but also
provides crucial insights for future regulatory interventions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.10337v1">Security, Trust and Privacy challenges in AI-driven 6G Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2024-09-16T14:48:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Helena Rifa-Pous, Victor Garcia-Font, Carlos Nunez-Gomez, Julian Salas</p>
    <p><b>Summary:</b> The advent of 6G networks promises unprecedented advancements in wireless
communication, offering wider bandwidth and lower latency compared to its
predecessors. This article explores the evolving infrastructure of 6G networks,
emphasizing the transition towards a more disaggregated structure and the
integration of artificial intelligence (AI) technologies. Furthermore, it
explores the security, trust and privacy challenges and attacks in 6G networks,
particularly those related to the use of AI. It presents a classification of
network attacks stemming from its AI-centric architecture and explores
technologies designed to detect or mitigate these emerging threats. The paper
concludes by examining the implications and risks linked to the utilization of
AI in ensuring a robust network.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.10226v1">Privacy-Preserving Distributed Maximum Consensus Without Accuracy Loss</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">  
  <p><b>Published on:</b> 2024-09-16T12:21:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenrui Yu, Richard Heusdens, Jun Pang, Qiongxiu Li</p>
    <p><b>Summary:</b> In distributed networks, calculating the maximum element is a fundamental
task in data analysis, known as the distributed maximum consensus problem.
However, the sensitive nature of the data involved makes privacy protection
essential. Despite its importance, privacy in distributed maximum consensus has
received limited attention in the literature. Traditional privacy-preserving
methods typically add noise to updates, degrading the accuracy of the final
result. To overcome these limitations, we propose a novel distributed
optimization-based approach that preserves privacy without sacrificing
accuracy. Our method introduces virtual nodes to form an augmented graph and
leverages a carefully designed initialization process to ensure the privacy of
honest participants, even when all their neighboring nodes are dishonest.
Through a comprehensive information-theoretical analysis, we derive a
sufficient condition to protect private data against both passive and
eavesdropping adversaries. Extensive experiments validate the effectiveness of
our approach, demonstrating that it not only preserves perfect privacy but also
maintains accuracy, outperforming existing noise-based methods that typically
suffer from accuracy loss.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.10192v1">PrePaMS: Privacy-Preserving Participant Management System for Studies
  with Rewards and Prerequisites</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-16T11:35:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Echo Meißner, Frank Kargl, Benjamin Erb, Felix Engelmann</p>
    <p><b>Summary:</b> Taking part in surveys, experiments, and studies is often compensated by
rewards to increase the number of participants and encourage attendance. While
privacy requirements are usually considered for participation, privacy aspects
of the reward procedure are mostly ignored. To this end, we introduce PrePaMS,
an efficient participation management system that supports prerequisite checks
and participation rewards in a privacy-preserving way. Our system organizes
participations with potential (dis-)qualifying dependencies and enables secure
reward payoffs. By leveraging a set of proven cryptographic primitives and
mechanisms such as anonymous credentials and zero-knowledge proofs,
participations are protected so that service providers and organizers cannot
derive the identity of participants even within the reward process. In this
paper, we have designed and implemented a prototype of PrePaMS to show its
effectiveness and evaluated its performance under realistic workloads. PrePaMS
covers the information whether subjects have participated in surveys,
experiments, or studies. When combined with other secure solutions for the
actual data collection within these events, PrePaMS can represent a cornerstone
for more privacy-preserving empirical research.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.10057v1">A Response to: A Note on "Privacy Preserving n-Party Scalar Product
  Protocol"</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-16T07:36:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Florian van Daalen, Lianne Ippel, Andre Dekker, Inigo Bermejo</p>
    <p><b>Summary:</b> We reply to the comments on our proposed privacy preserving n-party scalar
product protocol made by Liu. In their comment Liu raised concerns regarding
the security and scalability of the $n$-party scalar product protocol. In this
reply, we show that their concerns are unfounded and that the $n$-party scalar
product protocol is safe for its intended purposes. Their concerns regarding
the security are based on a misunderstanding of the protocol. Additionally,
while the scalability of the protocol puts limitations on its use, the protocol
still has numerous practical applications when applied in the correct
scenarios. Specifically within vertically partitioned scenarios, which often
involve few parties, the protocol remains practical. In this reply we clarify
Liu's misunderstanding. Additionally, we explain why the protocols scaling is
not a practical problem in its intended application.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.09972v1">Securing the Future: Exploring Privacy Risks and Security Questions in
  Robotic Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-09-16T04:10:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Diba Afroze, Yazhou Tu, Xiali Hei</p>
    <p><b>Summary:</b> The integration of artificial intelligence, especially large language models
in robotics, has led to rapid advancements in the field. We are now observing
an unprecedented surge in the use of robots in our daily lives. The development
and continual improvements of robots are moving at an astonishing pace.
Although these remarkable improvements facilitate and enhance our lives,
several security and privacy concerns have not been resolved yet. Therefore, it
has become crucial to address the privacy and security threats of robotic
systems while improving our experiences. In this paper, we aim to present
existing applications and threats of robotics, anticipated future evolution,
and the security and privacy issues they may imply. We present a series of open
questions for researchers and practitioners to explore further.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.09558v1">A Statistical Viewpoint on Differential Privacy: Hypothesis Testing,
  Representation and Blackwell's Theorem</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">  
  <p><b>Published on:</b> 2024-09-14T23:47:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Weijie J. Su</p>
    <p><b>Summary:</b> Differential privacy is widely considered the formal privacy for
privacy-preserving data analysis due to its robust and rigorous guarantees,
with increasingly broad adoption in public services, academia, and industry.
Despite originating in the cryptographic context, in this review paper we argue
that, fundamentally, differential privacy can be considered a \textit{pure}
statistical concept. By leveraging a theorem due to David Blackwell, our focus
is to demonstrate that the definition of differential privacy can be formally
motivated from a hypothesis testing perspective, thereby showing that
hypothesis testing is not merely convenient but also the right language for
reasoning about differential privacy. This insight leads to the definition of
$f$-differential privacy, which extends other differential privacy definitions
through a representation theorem. We review techniques that render
$f$-differential privacy a unified framework for analyzing privacy bounds in
data analysis and machine learning. Applications of this differential privacy
definition to private deep learning, private convex optimization, shuffled
mechanisms, and U.S.~Census data are discussed to highlight the benefits of
analyzing privacy bounds under this framework compared to existing
alternatives.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.09532v1">Using Synthetic Data to Mitigate Unfairness and Preserve Privacy through
  Single-Shot Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E"> 
  <p><b>Published on:</b> 2024-09-14T21:04:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chia-Yuan Wu, Frank E. Curtis, Daniel P. Robinson</p>
    <p><b>Summary:</b> To address unfairness issues in federated learning (FL), contemporary
approaches typically use frequent model parameter updates and transmissions
between the clients and server. In such a process, client-specific information
(e.g., local dataset size or data-related fairness metrics) must be sent to the
server to compute, e.g., aggregation weights. All of this results in high
transmission costs and the potential leakage of client information. As an
alternative, we propose a strategy that promotes fair predictions across
clients without the need to pass information between the clients and server
iteratively and prevents client data leakage. For each client, we first use
their local dataset to obtain a synthetic dataset by solving a bilevel
optimization problem that addresses unfairness concerns during the learning
process. We then pass each client's synthetic dataset to the server, the
collection of which is used to train the server model using conventional
machine learning techniques (that do not take fairness metrics into account).
Thus, we eliminate the need to handle fairness-specific aggregation weights
while preserving client privacy. Our approach requires only a single
communication between the clients and the server, thus making it
computationally cost-effective, able to maintain privacy, and able to ensuring
fairness. We present empirical evidence to demonstrate the advantages of our
approach. The results illustrate that our method effectively uses synthetic
data as a means to mitigate unfairness and preserve client privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.09510v1">Comparing Retrieval-Augmentation and Parameter-Efficient Fine-Tuning for
  Privacy-Preserving Personalization of Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-09-14T19:18:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alireza Salemi, Hamed Zamani</p>
    <p><b>Summary:</b> Privacy-preserving methods for personalizing large language models (LLMs) are
relatively under-explored. There are two schools of thought on this topic: (1)
generating personalized outputs by personalizing the input prompt through
retrieval augmentation from the user's personal information (RAG-based
methods), and (2) parameter-efficient fine-tuning of LLMs per user that
considers efficiency and space limitations (PEFT-based methods). This paper
presents the first systematic comparison between two approaches on a wide range
of personalization tasks using seven diverse datasets. Our results indicate
that RAG-based and PEFT-based personalization methods on average yield 14.92%
and 1.07% improvements over the non-personalized LLM, respectively. We find
that combining RAG with PEFT elevates these improvements to 15.98%.
Additionally, we identify a positive correlation between the amount of user
data and PEFT's effectiveness, indicating that RAG is a better choice for
cold-start users (i.e., user's with limited personal data).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.09495v1">Protecting Vehicle Location Privacy with Contextually-Driven Synthetic
  Location Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-14T17:47:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sourabh Yadav, Chenyang Yu, Xinpeng Xie, Yan Huang, Chenxi Qiu</p>
    <p><b>Summary:</b> Geo-obfuscation is a Location Privacy Protection Mechanism used in
location-based services that allows users to report obfuscated locations
instead of exact ones. A formal privacy criterion, geoindistinguishability
(Geo-Ind), requires real locations to be hard to distinguish from nearby
locations (by attackers) based on their obfuscated representations. However,
Geo-Ind often fails to consider context, such as road networks and vehicle
traffic conditions, making it less effective in protecting the location privacy
of vehicles, of which the mobility are heavily influenced by these factors.
  In this paper, we introduce VehiTrack, a new threat model to demonstrate the
vulnerability of Geo-Ind in protecting vehicle location privacy from
context-aware inference attacks. Our experiments demonstrate that VehiTrack can
accurately determine exact vehicle locations from obfuscated data, reducing
average inference errors by 61.20% with Laplacian noise and 47.35% with linear
programming (LP) compared to traditional Bayesian attacks. By using contextual
data like road networks and traffic flow, VehiTrack effectively eliminates a
significant number of seemingly "impossible" locations during its search for
the actual location of the vehicles. Based on these insights, we propose
TransProtect, a new geo-obfuscation approach that limits obfuscation to
realistic vehicle movement patterns, complicating attackers' ability to
differentiate obfuscated from actual locations. Our results show that
TransProtect increases VehiTrack's inference error by 57.75% with Laplacian
noise and 27.21% with LP, significantly enhancing protection against these
attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.09363v2">Security and Privacy Perspectives of People Living in Shared Home
  Environments</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-09-14T08:34:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nandita Pattnaik, Shujun Li, Jason R. C. Nurse</p>
    <p><b>Summary:</b> Security and privacy perspectives of people in a multi-user home are a
growing area of research, with many researchers reflecting on the complicated
power imbalance and challenging access control issues of the devices involved.
However, these studies primarily focused on the multi-user scenarios in
traditional family home settings, leaving other types of multi-user home
environments, such as homes shared by co-habitants without a familial
relationship, under-studied. This paper closes this research gap via
quantitative and qualitative analysis of results from an online survey and
content analysis of sampled online posts on Reddit. It explores the complex
roles of shared home users, which depend on various factors unique to the
shared home environment, e.g., who owns what home devices, how home devices are
used by multiple users, and more complicated relationships between the landlord
and people in the shared home and among co-habitants. Half (50.7%) of our
survey participants thought that devices in a shared home are less secure than
in a traditional family home. This perception was found statistically
significantly associated with factors such as the fear of devices being
tampered with in their absence and (lack of) trust in other co-habitants and
their visitors. Our study revealed new user types and relationships in a
multi-user environment such as ExternalPrimary-InternalPrimary while analysing
the landlord and shared home resident relationship with regard to shared home
device use. We propose a threat actor model for shared home environments, which
has a focus on possible malicious behaviours of current and past co-habitants
of a shared home, as a special type of insider threat in a home environment. We
also recommend further research to understand the complex roles co-habitants
can play in navigating and adapting to a shared home environment's security and
privacy landscape.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.09272v1">SafeEar: Content Privacy-Preserving Audio Deepfake Detection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Multimedia-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> 
  <p><b>Published on:</b> 2024-09-14T02:45:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xinfeng Li, Kai Li, Yifan Zheng, Chen Yan, Xiaoyu Ji, Wenyuan Xu</p>
    <p><b>Summary:</b> Text-to-Speech (TTS) and Voice Conversion (VC) models have exhibited
remarkable performance in generating realistic and natural audio. However,
their dark side, audio deepfake poses a significant threat to both society and
individuals. Existing countermeasures largely focus on determining the
genuineness of speech based on complete original audio recordings, which
however often contain private content. This oversight may refrain deepfake
detection from many applications, particularly in scenarios involving sensitive
information like business secrets. In this paper, we propose SafeEar, a novel
framework that aims to detect deepfake audios without relying on accessing the
speech content within. Our key idea is to devise a neural audio codec into a
novel decoupling model that well separates the semantic and acoustic
information from audio samples, and only use the acoustic information (e.g.,
prosody and timbre) for deepfake detection. In this way, no semantic content
will be exposed to the detector. To overcome the challenge of identifying
diverse deepfake audio without semantic clues, we enhance our deepfake detector
with real-world codec augmentation. Extensive experiments conducted on four
benchmark datasets demonstrate SafeEar's effectiveness in detecting various
deepfake techniques with an equal error rate (EER) down to 2.02%.
Simultaneously, it shields five-language speech content from being deciphered
by both machine and human auditory analysis, demonstrated by word error rates
(WERs) all above 93.93% and our user study. Furthermore, our benchmark
constructed for anti-deepfake and anti-content recovery evaluation helps
provide a basis for future research in the realms of audio privacy preservation
and deepfake detection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.11430v2">Federated Learning with Quantum Computing and Fully Homomorphic
  Encryption: A Novel Computing Paradigm Shift in Privacy-Preserving ML</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Neural and Evolutionary Computing-5BC0EB">
  <p><b>Published on:</b> 2024-09-14T01:23:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Siddhant Dutta, Pavana P Karanth, Pedro Maciel Xavier, Iago Leal de Freitas, Nouhaila Innan, Sadok Ben Yahia, Muhammad Shafique, David E. Bernal Neira</p>
    <p><b>Summary:</b> The widespread deployment of products powered by machine learning models is
raising concerns around data privacy and information security worldwide. To
address this issue, Federated Learning was first proposed as a
privacy-preserving alternative to conventional methods that allow multiple
learning clients to share model knowledge without disclosing private data. A
complementary approach known as Fully Homomorphic Encryption (FHE) is a
quantum-safe cryptographic system that enables operations to be performed on
encrypted weights. However, implementing mechanisms such as these in practice
often comes with significant computational overhead and can expose potential
security threats. Novel computing paradigms, such as analog, quantum, and
specialized digital hardware, present opportunities for implementing
privacy-preserving machine learning systems while enhancing security and
mitigating performance loss. This work instantiates these ideas by applying the
FHE scheme to a Federated Learning Neural Network architecture that integrates
both classical and quantum layers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.09222v1">Dark Patterns in the Opt-Out Process and Compliance with the California
  Consumer Privacy Act (CCPA)</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-09-13T22:20:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Van Hong Tran, Aarushi Mehrotra, Ranya Sharma, Marshini Chetty, Nick Feamster, Jens Frankenreiter, Lior Strahilevitz</p>
    <p><b>Summary:</b> To protect consumer privacy, the California Consumer Privacy Act (CCPA)
mandates that businesses provide consumers with a straightforward way to opt
out of the sale and sharing of their personal information. However, the control
that businesses enjoy over the opt-out process allows them to impose hurdles on
consumers aiming to opt out, including by employing dark patterns. Motivated by
the enactment of the California Privacy Rights Act (CPRA), which strengthens
the CCPA and explicitly forbids certain dark patterns in the opt-out process,
we investigate how dark patterns are used in opt-out processes and assess their
compliance with CCPA regulations. Our research reveals that websites employ a
variety of dark patterns. Some of these patterns are explicitly prohibited
under the CCPA; others evidently take advantage of legal loopholes. Despite the
initial efforts to restrict dark patterns by policymakers, there is more work
to be done.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.08913v2">HLTCOE JHU Submission to the Voice Privacy Challenge 2024</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-09-13T15:29:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Henry Li Xinyuan, Zexin Cai, Ashi Garg, Kevin Duh, Leibny Paola García-Perera, Sanjeev Khudanpur, Nicholas Andrews, Matthew Wiesner</p>
    <p><b>Summary:</b> We present a number of systems for the Voice Privacy Challenge, including
voice conversion based systems such as the kNN-VC method and the WavLM voice
Conversion method, and text-to-speech (TTS) based systems including
Whisper-VITS. We found that while voice conversion systems better preserve
emotional content, they struggle to conceal speaker identity in semi-white-box
attack scenarios; conversely, TTS methods perform better at anonymization and
worse at emotion preservation. Finally, we propose a random admixture system
which seeks to balance out the strengths and weaknesses of the two category of
systems, achieving a strong EER of over 40% while maintaining UAR at a
respectable 47%.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.08636v2">Utilizing Data Fingerprints for Privacy-Preserving Algorithm Selection
  in Time Series Classification: Performance and Uncertainty Estimation on
  Unseen Datasets</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-09-13T08:43:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lars Böcking, Leopold Müller, Niklas Kühl</p>
    <p><b>Summary:</b> The selection of algorithms is a crucial step in designing AI services for
real-world time series classification use cases. Traditional methods such as
neural architecture search, automated machine learning, combined algorithm
selection, and hyperparameter optimizations are effective but require
considerable computational resources and necessitate access to all data points
to run their optimizations. In this work, we introduce a novel data fingerprint
that describes any time series classification dataset in a privacy-preserving
manner and provides insight into the algorithm selection problem without
requiring training on the (unseen) dataset. By decomposing the multi-target
regression problem, only our data fingerprints are used to estimate algorithm
performance and uncertainty in a scalable and adaptable manner. Our approach is
evaluated on the 112 University of California riverside benchmark datasets,
demonstrating its effectiveness in predicting the performance of 35
state-of-the-art algorithms and providing valuable insights for effective
algorithm selection in time series classification service systems, improving a
naive baseline by 7.32% on average in estimating the mean performance and
15.81% in estimating the uncertainty.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.08538v1">An Efficient Privacy-aware Split Learning Framework for Satellite
  Communications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-13T04:59:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jianfei Sun, Cong Wu, Shahid Mumtaz, Junyi Tao, Mingsheng Cao, Mei Wang, Valerio Frascolla</p>
    <p><b>Summary:</b> In the rapidly evolving domain of satellite communications, integrating
advanced machine learning techniques, particularly split learning, is crucial
for enhancing data processing and model training efficiency across satellites,
space stations, and ground stations. Traditional ML approaches often face
significant challenges within satellite networks due to constraints such as
limited bandwidth and computational resources. To address this gap, we propose
a novel framework for more efficient SL in satellite communications. Our
approach, Dynamic Topology Informed Pruning, namely DTIP, combines differential
privacy with graph and model pruning to optimize graph neural networks for
distributed learning. DTIP strategically applies differential privacy to raw
graph data and prunes GNNs, thereby optimizing both model size and
communication load across network tiers. Extensive experiments across diverse
datasets demonstrate DTIP's efficacy in enhancing privacy, accuracy, and
computational efficiency. Specifically, on Amazon2M dataset, DTIP maintains an
accuracy of 0.82 while achieving a 50% reduction in floating-point operations
per second. Similarly, on ArXiv dataset, DTIP achieves an accuracy of 0.85
under comparable conditions. Our framework not only significantly improves the
operational efficiency of satellite communications but also establishes a new
benchmark in privacy-aware distributed learning, potentially revolutionizing
data handling in space-based networks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.08503v1">Enhancing Privacy in ControlNet and Stable Diffusion via Split Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-13T02:55:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dixi Yao</p>
    <p><b>Summary:</b> With the emerging trend of large generative models, ControlNet is introduced
to enable users to fine-tune pre-trained models with their own data for various
use cases. A natural question arises: how can we train ControlNet models while
ensuring users' data privacy across distributed devices? Exploring different
distributed training schemes, we find conventional federated learning and split
learning unsuitable. Instead, we propose a new distributed learning structure
that eliminates the need for the server to send gradients back. Through a
comprehensive evaluation of existing threats, we discover that in the context
of training ControlNet with split learning, most existing attacks are
ineffective, except for two mentioned in previous literature. To counter these
threats, we leverage the properties of diffusion models and design a new
timestep sampling policy during forward processes. We further propose a
privacy-preserving activation function and a method to prevent private text
prompts from leaving clients, tailored for image generation with diffusion
models. Our experimental results demonstrate that our algorithms and systems
greatly enhance the efficiency of distributed training for ControlNet while
ensuring users' data privacy without compromising image generation quality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.07997v1">Privacy-preserving federated prediction of pain intensity change based
  on multi-center survey data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-09-12T12:41:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Supratim Das, Mahdie Rafie, Paula Kammer, Søren T. Skou, Dorte T. Grønne, Ewa M. Roos, André Hajek, Hans-Helmut König, Md Shihab Ullaha, Niklas Probul, Jan Baumbacha, Linda Baumbach</p>
    <p><b>Summary:</b> Background: Patient-reported survey data are used to train prognostic models
aimed at improving healthcare. However, such data are typically available
multi-centric and, for privacy reasons, cannot easily be centralized in one
data repository. Models trained locally are less accurate, robust, and
generalizable. We present and apply privacy-preserving federated machine
learning techniques for prognostic model building, where local survey data
never leaves the legally safe harbors of the medical centers. Methods: We used
centralized, local, and federated learning techniques on two healthcare
datasets (GLA:D data from the five health regions of Denmark and international
SHARE data of 27 countries) to predict two different health outcomes. We
compared linear regression, random forest regression, and random forest
classification models trained on local data with those trained on the entire
data in a centralized and in a federated fashion. Results: In GLA:D data,
federated linear regression (R2 0.34, RMSE 18.2) and federated random forest
regression (R2 0.34, RMSE 18.3) models outperform their local counterparts
(i.e., R2 0.32, RMSE 18.6, R2 0.30, RMSE 18.8) with statistical significance.
We also found that centralized models (R2 0.34, RMSE 18.2, R2 0.32, RMSE 18.5,
respectively) did not perform significantly better than the federated models.
In SHARE, the federated model (AC 0.78, AUROC: 0.71) and centralized model (AC
0.84, AUROC: 0.66) perform significantly better than the local models (AC:
0.74, AUROC: 0.69). Conclusion: Federated learning enables the training of
prognostic models from multi-center surveys without compromising privacy and
with only minimal or no compromise regarding model performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.11423v1">Generated Data with Fake Privacy: Hidden Dangers of Fine-tuning Large
  Language Models on Generated Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-09-12T10:14:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Atilla Akkus, Mingjie Li, Junjie Chu, Michael Backes, Yang Zhang, Sinem Sav</p>
    <p><b>Summary:</b> Large language models (LLMs) have shown considerable success in a range of
domain-specific tasks, especially after fine-tuning. However, fine-tuning with
real-world data usually leads to privacy risks, particularly when the
fine-tuning samples exist in the pre-training data. To avoid the shortcomings
of real data, developers often employ methods to automatically generate
synthetic data for fine-tuning, as data generated by traditional models are
often far away from the real-world pertaining data. However, given the advanced
capabilities of LLMs, the distinction between real data and LLM-generated data
has become negligible, which may also lead to privacy risks like real data. In
this paper, we present an empirical analysis of this underexplored issue by
investigating a key question: "Does fine-tuning with LLM-generated data enhance
privacy, or does it pose additional privacy risks?" Based on the structure of
LLM's generated data, our research focuses on two primary approaches to
fine-tuning with generated data: supervised fine-tuning with unstructured
generated data and self-instruct tuning. The number of successful Personal
Information Identifier (PII) extractions for Pythia after fine-tuning our
generated data raised over $20\%$. Furthermore, the ROC-AUC score of membership
inference attacks for Pythia-6.9b after self-instruct methods also achieves
more than $40\%$ improvements on ROC-AUC score than base models. The results
indicate the potential privacy risks in LLMs when fine-tuning with the
generated data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.07809v1">Controllable Synthetic Clinical Note Generation with Privacy Guarantees</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-09-12T07:38:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tal Baumel, Andre Manoel, Daniel Jones, Shize Su, Huseyin Inan,  Aaron,  Bornstein, Robert Sim</p>
    <p><b>Summary:</b> In the field of machine learning, domain-specific annotated data is an
invaluable resource for training effective models. However, in the medical
domain, this data often includes Personal Health Information (PHI), raising
significant privacy concerns. The stringent regulations surrounding PHI limit
the availability and sharing of medical datasets, which poses a substantial
challenge for researchers and practitioners aiming to develop advanced machine
learning models. In this paper, we introduce a novel method to "clone" datasets
containing PHI. Our approach ensures that the cloned datasets retain the
essential characteristics and utility of the original data without compromising
patient privacy. By leveraging differential-privacy techniques and a novel
fine-tuning task, our method produces datasets that are free from identifiable
information while preserving the statistical properties necessary for model
training. We conduct utility testing to evaluate the performance of machine
learning models trained on the cloned datasets. The results demonstrate that
our cloned datasets not only uphold privacy standards but also enhance model
performance compared to those trained on traditional anonymized datasets. This
work offers a viable solution for the ethical and effective utilization of
sensitive medical data in machine learning, facilitating progress in medical
research and the development of robust predictive models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.07773v1">PDC-FRS: Privacy-preserving Data Contribution for Federated Recommender
  System</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2024-09-12T06:13:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chaoqun Yang, Wei Yuan, Liang Qu, Thanh Tam Nguyen</p>
    <p><b>Summary:</b> Federated recommender systems (FedRecs) have emerged as a popular research
direction for protecting users' privacy in on-device recommendations. In
FedRecs, users keep their data locally and only contribute their local
collaborative information by uploading model parameters to a central server.
While this rigid framework protects users' raw data during training, it
severely compromises the recommendation model's performance due to the
following reasons: (1) Due to the power law distribution nature of user
behavior data, individual users have few data points to train a recommendation
model, resulting in uploaded model updates that may be far from optimal; (2) As
each user's uploaded parameters are learned from local data, which lacks global
collaborative information, relying solely on parameter aggregation methods such
as FedAvg to fuse global collaborative information may be suboptimal. To bridge
this performance gap, we propose a novel federated recommendation framework,
PDC-FRS. Specifically, we design a privacy-preserving data contribution
mechanism that allows users to share their data with a differential privacy
guarantee. Based on the shared but perturbed data, an auxiliary model is
trained in parallel with the original federated recommendation process. This
auxiliary model enhances FedRec by augmenting each user's local dataset and
integrating global collaborative information. To demonstrate the effectiveness
of PDC-FRS, we conduct extensive experiments on two widely used recommendation
datasets. The empirical results showcase the superiority of PDC-FRS compared to
baseline methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.07751v1">Efficient Privacy-Preserving KAN Inference Using Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-12T04:51:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhizheng Lai, Yufei Zhou, Peijia Zheng, Lin Chen</p>
    <p><b>Summary:</b> The recently proposed Kolmogorov-Arnold Networks (KANs) offer enhanced
interpretability and greater model expressiveness. However, KANs also present
challenges related to privacy leakage during inference. Homomorphic encryption
(HE) facilitates privacy-preserving inference for deep learning models,
enabling resource-limited users to benefit from deep learning services while
ensuring data security. Yet, the complex structure of KANs, incorporating
nonlinear elements like the SiLU activation function and B-spline functions,
renders existing privacy-preserving inference techniques inadequate. To address
this issue, we propose an accurate and efficient privacy-preserving inference
scheme tailored for KANs. Our approach introduces a task-specific polynomial
approximation for the SiLU activation function, dynamically adjusting the
approximation range to ensure high accuracy on real-world datasets.
Additionally, we develop an efficient method for computing B-spline functions
within the HE domain, leveraging techniques such as repeat packing, lazy
combination, and comparison functions. We evaluate the effectiveness of our
privacy-preserving KAN inference scheme on both symbolic formula evaluation and
image classification. The experimental results show that our model achieves
accuracy comparable to plaintext KANs across various datasets and outperforms
plaintext MLPs. Additionally, on the CIFAR-10 dataset, our inference latency
achieves over 7 times speedup compared to the naive method.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.07444v2">Echoes of Privacy: Uncovering the Profiling Practices of Voice
  Assistants</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2024-09-11T17:44:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tina Khezresmaeilzadeh, Elaine Zhu, Kiersten Grieco, Daniel J. Dubois, Konstantinos Psounis, David Choffnes</p>
    <p><b>Summary:</b> Many companies, including Google, Amazon, and Apple, offer voice assistants
as a convenient solution for answering general voice queries and accessing
their services. These voice assistants have gained popularity and can be easily
accessed through various smart devices such as smartphones, smart speakers,
smartwatches, and an increasing array of other devices. However, this
convenience comes with potential privacy risks. For instance, while companies
vaguely mention in their privacy policies that they may use voice interactions
for user profiling, it remains unclear to what extent this profiling occurs and
whether voice interactions pose greater privacy risks compared to other
interaction modalities.
  In this paper, we conduct 1171 experiments involving a total of 24530 queries
with different personas and interaction modalities over the course of 20 months
to characterize how the three most popular voice assistants profile their
users. We analyze factors such as the labels assigned to users, their accuracy,
the time taken to assign these labels, differences between voice and web
interactions, and the effectiveness of profiling remediation tools offered by
each voice assistant. Our findings reveal that profiling can happen without
interaction, can be incorrect and inconsistent at times, may take several days
to weeks for changes to occur, and can be influenced by the interaction
modality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.07415v1">SoK: Security and Privacy Risks of Medical AI</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-09-11T16:59:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuanhaur Chang, Han Liu, Evin Jaff, Chenyang Lu, Ning Zhang</p>
    <p><b>Summary:</b> The integration of technology and healthcare has ushered in a new era where
software systems, powered by artificial intelligence and machine learning, have
become essential components of medical products and services. While these
advancements hold great promise for enhancing patient care and healthcare
delivery efficiency, they also expose sensitive medical data and system
integrity to potential cyberattacks. This paper explores the security and
privacy threats posed by AI/ML applications in healthcare. Through a thorough
examination of existing research across a range of medical domains, we have
identified significant gaps in understanding the adversarial attacks targeting
medical AI systems. By outlining specific adversarial threat models for medical
settings and identifying vulnerable application domains, we lay the groundwork
for future research that investigates the security and resilience of AI-driven
medical systems. Through our analysis of different threat models and
feasibility studies on adversarial attacks in different medical domains, we
provide compelling insights into the pressing need for cybersecurity research
in the rapidly evolving field of AI healthcare technology.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.07224v1">Analytic Class Incremental Learning for Sound Source Localization with
  Privacy Protection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> 
  <p><b>Published on:</b> 2024-09-11T12:31:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xinyuan Qian, Xianghu Yue, Jiadong Wang, Huiping Zhuang, Haizhou Li</p>
    <p><b>Summary:</b> Sound Source Localization (SSL) enabling technology for applications such as
surveillance and robotics. While traditional Signal Processing (SP)-based SSL
methods provide analytic solutions under specific signal and noise assumptions,
recent Deep Learning (DL)-based methods have significantly outperformed them.
However, their success depends on extensive training data and substantial
computational resources. Moreover, they often rely on large-scale annotated
spatial data and may struggle when adapting to evolving sound classes. To
mitigate these challenges, we propose a novel Class Incremental Learning (CIL)
approach, termed SSL-CIL, which avoids serious accuracy degradation due to
catastrophic forgetting by incrementally updating the DL-based SSL model
through a closed-form analytic solution. In particular, data privacy is ensured
since the learning process does not revisit any historical data
(exemplar-free), which is more suitable for smart home scenarios. Empirical
results in the public SSLR dataset demonstrate the superior performance of our
proposal, achieving a localization accuracy of 90.9%, surpassing other
competitive methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.07187v1">A Simple Linear Space Data Structure for ANN with Application in
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2024-09-11T11:14:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Martin Aumüller, Fabrizio Boninsegna, Francesco Silvestri</p>
    <p><b>Summary:</b> Locality Sensitive Filters are known for offering a quasi-linear space data
structure with rigorous guarantees for the Approximate Near Neighbor search
problem. Building on Locality Sensitive Filters, we derive a simple data
structure for the Approximate Near Neighbor Counting problem under differential
privacy. Moreover, we provide a simple analysis leveraging a connection with
concomitant statistics and extreme value theory. Our approach achieves the same
performance as the recent findings of Andoni et al. (NeurIPS 2023) but with a
more straightforward method. As a side result, the paper provides a more
compact description and analysis of Locality Sensitive Filters for Approximate
Near Neighbor Search under inner product similarity, improving a previous
result in Aum\"{u}ller et al. (TODS 2022).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.06955v2">Privacy-Preserving Federated Learning with Consistency via Knowledge
  Distillation Using Conditional Generator</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-09-11T02:36:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kangyang Luo, Shuai Wang, Xiang Li, Yunshi Lan, Ming Gao, Jinlong Shu</p>
    <p><b>Summary:</b> Federated Learning (FL) is gaining popularity as a distributed learning
framework that only shares model parameters or gradient updates and keeps
private data locally. However, FL is at risk of privacy leakage caused by
privacy inference attacks. And most existing privacy-preserving mechanisms in
FL conflict with achieving high performance and efficiency. Therefore, we
propose FedMD-CG, a novel FL method with highly competitive performance and
high-level privacy preservation, which decouples each client's local model into
a feature extractor and a classifier, and utilizes a conditional generator
instead of the feature extractor to perform server-side model aggregation. To
ensure the consistency of local generators and classifiers, FedMD-CG leverages
knowledge distillation to train local models and generators at both the latent
feature level and the logit level. Also, we construct additional classification
losses and design new diversity losses to enhance client-side training.
FedMD-CG is robust to data heterogeneity and does not require training extra
discriminators (like cGAN). We conduct extensive experiments on various image
classification tasks to validate the superiority of FedMD-CG.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.06564v1">Advancing Android Privacy Assessments with Automation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-10T14:56:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mugdha Khedkar, Michael Schlichtig, Eric Bodden</p>
    <p><b>Summary:</b> Android apps collecting data from users must comply with legal frameworks to
ensure data protection. This requirement has become even more important since
the implementation of the General Data Protection Regulation (GDPR) by the
European Union in 2018. Moreover, with the proposed Cyber Resilience Act on the
horizon, stakeholders will soon need to assess software against even more
stringent security and privacy standards. Effective privacy assessments require
collaboration among groups with diverse expertise to function effectively as a
cohesive unit.
  This paper motivates the need for an automated approach that enhances
understanding of data protection in Android apps and improves communication
between the various parties involved in privacy assessments. We propose the
Assessor View, a tool designed to bridge the knowledge gap between these
parties, facilitating more effective privacy assessments of Android
applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.06455v1">Continual Domain Incremental Learning for Privacy-aware Digital
  Pathology</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-09-10T12:21:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pratibha Kumari, Daniel Reisenbüchler, Lucas Luttner, Nadine S. Schaadt, Friedrich Feuerhake, Dorit Merhof</p>
    <p><b>Summary:</b> In recent years, there has been remarkable progress in the field of digital
pathology, driven by the ability to model complex tissue patterns using
advanced deep-learning algorithms. However, the robustness of these models is
often severely compromised in the presence of data shifts (e.g., different
stains, organs, centers, etc.). Alternatively, continual learning (CL)
techniques aim to reduce the forgetting of past data when learning new data
with distributional shift conditions. Specifically, rehearsal-based CL
techniques, which store some past data in a buffer and then replay it with new
data, have proven effective in medical image analysis tasks. However, privacy
concerns arise as these approaches store past data, prompting the development
of our novel Generative Latent Replay-based CL (GLRCL) approach. GLRCL captures
the previous distribution through Gaussian Mixture Models instead of storing
past samples, which are then utilized to generate features and perform latent
replay with new data. We systematically evaluate our proposed framework under
different shift conditions in histopathology data, including stain and organ
shift. Our approach significantly outperforms popular buffer-free CL approaches
and performs similarly to rehearsal-based CL approaches that require large
buffers causing serious privacy violations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.06422v1">A Pervasive, Efficient and Private Future: Realizing Privacy-Preserving
  Machine Learning Through Hybrid Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-10T11:04:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Khoa Nguyen, Mindaugas Budzys, Eugene Frimpong, Tanveer Khan, Antonis Michalas</p>
    <p><b>Summary:</b> Machine Learning (ML) has become one of the most impactful fields of data
science in recent years. However, a significant concern with ML is its privacy
risks due to rising attacks against ML models. Privacy-Preserving Machine
Learning (PPML) methods have been proposed to mitigate the privacy and security
risks of ML models. A popular approach to achieving PPML uses Homomorphic
Encryption (HE). However, the highly publicized inefficiencies of HE make it
unsuitable for highly scalable scenarios with resource-constrained devices.
Hence, Hybrid Homomorphic Encryption (HHE) -- a modern encryption scheme that
combines symmetric cryptography with HE -- has recently been introduced to
overcome these challenges. HHE potentially provides a foundation to build new
efficient and privacy-preserving services that transfer expensive HE operations
to the cloud. This work introduces HHE to the ML field by proposing
resource-friendly PPML protocols for edge devices. More precisely, we utilize
HHE as the primary building block of our PPML protocols. We assess the
performance of our protocols by first extensively evaluating each party's
communication and computational cost on a dummy dataset and show the efficiency
of our protocols by comparing them with similar protocols implemented using
plain BFV. Subsequently, we demonstrate the real-world applicability of our
construction by building an actual PPML application that uses HHE as its
foundation to classify heart disease based on sensitive ECG data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.06360v1">SoK: Evaluating 5G Protocols Against Legacy and Emerging Privacy and
  Security Attacks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2024-09-10T09:30:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stavros Eleftherakis, Domenico Giustiniano, Nicolas Kourtellis</p>
    <p><b>Summary:</b> Ensuring user privacy remains a critical concern within mobile cellular
networks, particularly given the proliferation of interconnected devices and
services. In fact, a lot of user privacy issues have been raised in 2G, 3G,
4G/LTE networks. Recognizing this general concern, 3GPP has prioritized
addressing these issues in the development of 5G, implementing numerous
modifications to enhance user privacy since 5G Release 15. In this
systematization of knowledge paper, we first provide a framework for studying
privacy and security related attacks in cellular networks, setting as privacy
objective the User Identity Confidentiality defined in 3GPP standards. Using
this framework, we discuss existing privacy and security attacks in pre-5G
networks, analyzing the weaknesses that lead to these attacks. Furthermore, we
thoroughly study the security characteristics of 5G up to the new Release 19,
and examine mitigation mechanisms of 5G to the identified pre-5G attacks.
Afterwards, we analyze how recent 5G attacks try to overcome these mitigation
mechanisms. Finally, we identify current limitations and open problems in
security of 5G, and propose directions for future work.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.06233v1">VBIT: Towards Enhancing Privacy Control Over IoT Devices</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-10T06:00:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jad Al Aaraj, Olivia Figueira, Tu Le, Isabela Figueira, Rahmadi Trimananda, Athina Markopoulou</p>
    <p><b>Summary:</b> Internet-of-Things (IoT) devices are increasingly deployed at home, at work,
and in other shared and public spaces. IoT devices collect and share data with
service providers and third parties, which poses privacy concerns. Although
privacy enhancing tools are quite advanced in other applications domains (\eg~
advertising and tracker blockers for browsers), users have currently no
convenient way to know or manage what and how data is collected and shared by
IoT devices. In this paper, we present VBIT, an interactive system combining
Mixed Reality (MR) and web-based applications that allows users to: (1) uncover
and visualize tracking services by IoT devices in an instrumented space and (2)
take action to stop or limit that tracking. We design and implement VBIT to
operate at the network traffic level, and we show that it has negligible
performance overhead, and offers flexibility and good usability. We perform a
mixed-method user study consisting of an online survey and an in-person
interview study. We show that VBIT users appreciate VBIT's transparency,
control, and customization features, and they become significantly more willing
to install an IoT advertising and tracking blocker, after using VBIT. In the
process, we obtain design insights that can be used to further iterate and
improve the design of VBIT and other systems for IoT transparency and control.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.06069v1">Privacy-Preserving Data Linkage Across Private and Public Datasets for
  Collaborative Agriculture Research</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-09-09T21:07:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Osama Zafar, Rosemarie Santa Gonzalez, Gabriel Wilkins, Alfonso Morales, Erman Ayday</p>
    <p><b>Summary:</b> Digital agriculture leverages technology to enhance crop yield, disease
resilience, and soil health, playing a critical role in agricultural research.
However, it raises privacy concerns such as adverse pricing, price
discrimination, higher insurance costs, and manipulation of resources,
deterring farm operators from sharing data due to potential misuse. This study
introduces a privacy-preserving framework that addresses these risks while
allowing secure data sharing for digital agriculture. Our framework enables
comprehensive data analysis while protecting privacy. It allows stakeholders to
harness research-driven policies that link public and private datasets. The
proposed algorithm achieves this by: (1) identifying similar farmers based on
private datasets, (2) providing aggregate information like time and location,
(3) determining trends in price and product availability, and (4) correlating
trends with public policy data, such as food insecurity statistics. We validate
the framework with real-world Farmer's Market datasets, demonstrating its
efficacy through machine learning models trained on linked privacy-preserved
data. The results support policymakers and researchers in addressing food
insecurity and pricing issues. This work significantly contributes to digital
agriculture by providing a secure method for integrating and analyzing data,
driving advancements in agricultural technology and development.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.05623v1">A Framework for Differential Privacy Against Timing Attacks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-09T13:56:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zachary Ratliff, Salil Vadhan</p>
    <p><b>Summary:</b> The standard definition of differential privacy (DP) ensures that a
mechanism's output distribution on adjacent datasets is indistinguishable.
However, real-world implementations of DP can, and often do, reveal information
through their runtime distributions, making them susceptible to timing attacks.
In this work, we establish a general framework for ensuring differential
privacy in the presence of timing side channels. We define a new notion of
timing privacy, which captures programs that remain differentially private to
an adversary that observes the program's runtime in addition to the output. Our
framework enables chaining together component programs that are timing-stable
followed by a random delay to obtain DP programs that achieve timing privacy.
Importantly, our definitions allow for measuring timing privacy and output
privacy using different privacy measures. We illustrate how to instantiate our
framework by giving programs for standard DP computations in the RAM and Word
RAM models of computation. Furthermore, we show how our framework can be
realized in code through a natural extension of the OpenDP Programming
Framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.05249v1">NetDPSyn: Synthesizing Network Traces under Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2024-09-08T23:54:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Danyu Sun, Joann Qiongna Chen, Chen Gong, Tianhao Wang, Zhou Li</p>
    <p><b>Summary:</b> As the utilization of network traces for the network measurement research
becomes increasingly prevalent, concerns regarding privacy leakage from network
traces have garnered the public's attention. To safeguard network traces,
researchers have proposed the trace synthesis that retains the essential
properties of the raw data. However, previous works also show that synthesis
traces with generative models are vulnerable under linkage attacks.
  This paper introduces NetDPSyn, the first system to synthesize high-fidelity
network traces under privacy guarantees. NetDPSyn is built with the
Differential Privacy (DP) framework as its core, which is significantly
different from prior works that apply DP when training the generative model.
The experiments conducted on three flow and two packet datasets indicate that
NetDPSyn achieves much better data utility in downstream tasks like anomaly
detection. NetDPSyn is also 2.5 times faster than the other methods on average
in data synthesis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.04877v1">Strong Privacy-Preserving Universally Composable AKA Protocol with
  Seamless Handover Support for Mobile Virtual Network Operator</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-07T18:04:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rabiah Alnashwan, Yang Yang, Yilu Dong, Prosanta Gope, Behzad Abdolmaleki, Syed Rafiul Hussain</p>
    <p><b>Summary:</b> Consumers seeking a new mobile plan have many choices in the present mobile
landscape. The Mobile Virtual Network Operator (MVNO) has recently gained
considerable attention among these options. MVNOs offer various benefits,
making them an appealing choice for a majority of consumers. These advantages
encompass flexibility, access to cutting-edge technologies, enhanced coverage,
superior customer service, and substantial cost savings. Even though MVNO
offers several advantages, it also creates some security and privacy concerns
for the customer simultaneously. For instance, in the existing solution, MVNO
needs to hand over all the sensitive details, including the users' identities
and master secret keys of their customers, to a mobile operator (MNO) to
validate the customers while offering any services. This allows MNOs to have
unrestricted access to the MVNO subscribers' location and mobile data,
including voice calls, SMS, and Internet, which the MNOs frequently sell to
third parties (e.g., advertisement companies and surveillance agencies) for
more profit. Although critical for mass users, such privacy loss has been
historically ignored due to the lack of practical and privacy-preserving
solutions for registration and handover procedures in cellular networks. In
this paper, we propose a universally composable authentication and handover
scheme with strong user privacy support, where each MVNO user can validate a
mobile operator (MNO) and vice-versa without compromising user anonymity and
unlinkability support. Here, we anticipate that our proposed solution will most
likely be deployed by the MVNO(s) to ensure enhanced privacy support to their
customer(s).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.04716v1">Privacy enhanced collaborative inference in the Cox proportional hazards
  model for distributed data</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> 
  <p><b>Published on:</b> 2024-09-07T05:32:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mengtong Hu, Xu Shi, Peter X. -K. Song</p>
    <p><b>Summary:</b> Data sharing barriers are paramount challenges arising from multicenter
clinical studies where multiple data sources are stored in a distributed
fashion at different local study sites. Particularly in the case of
time-to-event analysis when global risk sets are needed for the Cox
proportional hazards model, access to a centralized database is typically
necessary. Merging such data sources into a common data storage for a
centralized statistical analysis requires a data use agreement, which is often
time-consuming. Furthermore, the construction and distribution of risk sets to
participating clinical centers for subsequent calculations may pose a risk of
revealing individual-level information. We propose a new collaborative Cox
model that eliminates the need for accessing the centralized database and
constructing global risk sets but needs only the sharing of summary statistics
with significantly smaller dimensions than risk sets. Thus, the proposed
collaborative inference enjoys maximal protection of data privacy. We show
theoretically and numerically that the new distributed proportional hazards
model approach has little loss of statistical power when compared to the
centralized method that requires merging the entire data. We present a
renewable sieve method to establish large-sample properties for the proposed
method. We illustrate its performance through simulation experiments and a
real-world data example from patients with kidney transplantation in the Organ
Procurement and Transplantation Network (OPTN) to understand the factors
associated with the 5-year death-censored graft failure (DCGF) for patients who
underwent kidney transplants in the US.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.04652v2">Privacy-Preserving Race/Ethnicity Estimation for Algorithmic Bias
  Measurement in the U.S</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-06T23:29:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Saikrishna Badrinarayanan, Osonde Osoba, Miao Cheng, Ryan Rogers, Sakshi Jain, Rahul Tandra, Natesh S. Pillai</p>
    <p><b>Summary:</b> AI fairness measurements, including tests for equal treatment, often take the
form of disaggregated evaluations of AI systems. Such measurements are an
important part of Responsible AI operations. These measurements compare system
performance across demographic groups or sub-populations and typically require
member-level demographic signals such as gender, race, ethnicity, and location.
However, sensitive member-level demographic attributes like race and ethnicity
can be challenging to obtain and use due to platform choices, legal
constraints, and cultural norms. In this paper, we focus on the task of
enabling AI fairness measurements on race/ethnicity for \emph{U.S. LinkedIn
members} in a privacy-preserving manner. We present the Privacy-Preserving
Probabilistic Race/Ethnicity Estimation (PPRE) method for performing this task.
PPRE combines the Bayesian Improved Surname Geocoding (BISG) model, a sparse
LinkedIn survey sample of self-reported demographics, and privacy-enhancing
technologies like secure two-party computation and differential privacy to
enable meaningful fairness measurements while preserving member privacy. We
provide details of the PPRE method and its privacy guarantees. We then
illustrate sample measurement operations. We conclude with a review of open
research and engineering challenges for expanding our privacy-preserving
fairness measurement capabilities.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.04366v1">Deanonymizing Ethereum Validators: The P2P Network Has a Privacy Issue</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-06T15:57:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lioba Heimbach, Yann Vonlanthen, Juan Villacis, Lucianna Kiffer, Roger Wattenhofer</p>
    <p><b>Summary:</b> Many blockchain networks aim to preserve the anonymity of validators in the
peer-to-peer (P2P) network, ensuring that no adversary can link a validator's
identifier to the IP address of a peer due to associated privacy and security
concerns. This work demonstrates that the Ethereum P2P network does not offer
this anonymity. We present a methodology that enables any node in the network
to identify validators hosted on connected peers and empirically verify the
feasibility of our proposed method. Using data collected from four nodes over
three days, we locate more than 15% of Ethereum validators in the P2P network.
The insights gained from our deanonymization technique provide valuable
information on the distribution of validators across peers, their geographic
locations, and hosting organizations. We further discuss the implications and
risks associated with the lack of anonymity in the P2P network and propose
methods to help validators protect their privacy. The Ethereum Foundation has
awarded us a bug bounty, acknowledging the impact of our results.</p>
  </details>
</div>

