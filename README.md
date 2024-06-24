
<h2>2024-06</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.15346v1">Privacy Preserved Blood Glucose Level Cross-Prediction: An Asynchronous
  Decentralized Federated Learning Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-06-21T17:57:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chengzhe Piao, Taiyu Zhu, Yu Wang, Stephanie E Baldeweg, Paul Taylor, Pantelis Georgiou, Jiahao Sun, Jun Wang, Kezhi Li</p>
    <p><b>Summary:</b> Newly diagnosed Type 1 Diabetes (T1D) patients often struggle to obtain
effective Blood Glucose (BG) prediction models due to the lack of sufficient BG
data from Continuous Glucose Monitoring (CGM), presenting a significant "cold
start" problem in patient care. Utilizing population models to address this
challenge is a potential solution, but collecting patient data for training
population models in a privacy-conscious manner is challenging, especially
given that such data is often stored on personal devices. Considering the
privacy protection and addressing the "cold start" problem in diabetes care, we
propose "GluADFL", blood Glucose prediction by Asynchronous Decentralized
Federated Learning. We compared GluADFL with eight baseline methods using four
distinct T1D datasets, comprising 298 participants, which demonstrated its
superior performance in accurately predicting BG levels for cross-patient
analysis. Furthermore, patients' data might be stored and shared across various
communication networks in GluADFL, ranging from highly interconnected (e.g.,
random, performs the best among others) to more structured topologies (e.g.,
cluster and ring), suitable for various social networks. The asynchronous
training framework supports flexible participation. By adjusting the ratios of
inactive participants, we found it remains stable if less than 70% are
inactive. Our results confirm that GluADFL offers a practical,
privacy-preserving solution for BG prediction in T1D, significantly enhancing
the quality of diabetes management.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.15309v1">The Privacy-Utility Trade-off in the Topics API</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-21T17:01:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mário S. Alvim, Natasha Fernandes, Annabelle McIver, Gabriel H. Nunes</p>
    <p><b>Summary:</b> The ongoing deprecation of third-party cookies by web browser vendors has
sparked the proposal of alternative methods to support more privacy-preserving
personalized advertising on web browsers and applications. The Topics API is
being proposed by Google to provide third-parties with "coarse-grained
advertising topics that the page visitor might currently be interested in". In
this paper, we analyze the re-identification risks for individual Internet
users and the utility provided to advertising companies by the Topics API, i.e.
learning the most popular topics and distinguishing between real and random
topics. We provide theoretical results dependent only on the API parameters
that can be readily applied to evaluate the privacy and utility implications of
future API updates, including novel general upper-bounds that account for
adversaries with access to unknown, arbitrary side information, the value of
the differential privacy parameter $\epsilon$, and experimental results on
real-world data that validate our theoretical model.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.15074v1">Balancing The Perception of Cheating Detection, Privacy and Fairness: A
  Mixed-Methods Study of Visual Data Obfuscation in Remote Proctoring</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-06-21T11:40:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Suvadeep Mukherjee, Verena Distler, Gabriele Lenzini, Pedro Cardoso-Leite</p>
    <p><b>Summary:</b> Remote proctoring technology, a cheating-preventive measure, often raises
privacy and fairness concerns that may affect test-takers' experiences and the
validity of test results. Our study explores how selectively obfuscating
information in video recordings can protect test-takers' privacy while ensuring
effective and fair cheating detection. Interviews with experts (N=9) identified
four key video regions indicative of potential cheating behaviors: the
test-taker's face, body, background and the presence of individuals in the
background. Experts recommended specific obfuscation methods for each region
based on privacy significance and cheating behavior frequency, ranging from
conventional blurring to advanced methods like replacement with deepfake, 3D
avatars and silhouetting. We then conducted a vignette experiment with
potential test-takers (N=259, non-experts) to evaluate their perceptions of
cheating detection, visual privacy and fairness, using descriptions and
examples of still images for each expert-recommended combination of video
regions and obfuscation methods. Our results indicate that the effectiveness of
obfuscation methods varies by region. Tailoring remote proctoring with
region-specific advanced obfuscation methods can improve the perceptions of
privacy and fairness compared to the conventional methods, though it may
decrease perceived information sufficiency for detecting cheating. However,
non-experts preferred conventional blurring for videos they were more willing
to share, highlighting a gap between the perceived effectiveness of the
advanced obfuscation methods and their practical acceptance. This study
contributes to the field of user-centered privacy by suggesting promising
directions to address current remote proctoring challenges and guiding future
research.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.14773v1">Mitigating the Privacy Issues in Retrieval-Augmented Generation (RAG)
  via Pure Synthetic Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-20T22:53:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shenglai Zeng, Jiankun Zhang, Pengfei He, Jie Ren, Tianqi Zheng, Hanqing Lu, Han Xu, Hui Liu, Yue Xing, Jiliang Tang</p>
    <p><b>Summary:</b> Retrieval-augmented generation (RAG) enhances the outputs of language models
by integrating relevant information retrieved from external knowledge sources.
However, when the retrieval process involves private data, RAG systems may face
severe privacy risks, potentially leading to the leakage of sensitive
information. To address this issue, we propose using synthetic data as a
privacy-preserving alternative for the retrieval data. We propose SAGE, a novel
two-stage synthetic data generation paradigm. In the stage-1, we employ an
attribute-based extraction and generation approach to preserve key contextual
information from the original data. In the stage-2, we further enhance the
privacy properties of the synthetic data through an agent-based iterative
refinement process. Extensive experiments demonstrate that using our synthetic
data as the retrieval context achieves comparable performance to using the
original data while substantially reducing privacy risks. Our work takes the
first step towards investigating the possibility of generating high-utility and
privacy-preserving synthetic data for RAG, opening up new opportunities for the
safe application of RAG systems in various domains.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.14772v1">Consistent community detection in multi-layer networks with
  heterogeneous differential privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B">
  <p><b>Published on:</b> 2024-06-20T22:49:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yaoming Zhen, Shirong Xu, Junhui Wang</p>
    <p><b>Summary:</b> As network data has become increasingly prevalent, a substantial amount of
attention has been paid to the privacy issue in publishing network data. One of
the critical challenges for data publishers is to preserve the topological
structures of the original network while protecting sensitive information. In
this paper, we propose a personalized edge flipping mechanism that allows data
publishers to protect edge information based on each node's privacy preference.
It can achieve differential privacy while preserving the community structure
under the multi-layer degree-corrected stochastic block model after
appropriately debiasing, and thus consistent community detection in the
privatized multi-layer networks is achievable. Theoretically, we establish the
consistency of community detection in the privatized multi-layer network and
show that better privacy protection of edges can be obtained for a proportion
of nodes while allowing other nodes to give up their privacy. Furthermore, the
advantage of the proposed personalized edge-flipping mechanism is also
supported by its numerical performance on various synthetic networks and a
real-life multi-layer network.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.14322v1">Mind the Privacy Unit! User-Level Differential Privacy for Language
  Model Fine-Tuning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-06-20T13:54:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lynn Chua, Badih Ghazi, Yangsibo Huang, Pritish Kamath, Daogao Liu, Pasin Manurangsi, Amer Sinha, Chiyuan Zhang</p>
    <p><b>Summary:</b> Large language models (LLMs) have emerged as powerful tools for tackling
complex tasks across diverse domains, but they also raise privacy concerns when
fine-tuned on sensitive data due to potential memorization. While differential
privacy (DP) offers a promising solution by ensuring models are `almost
indistinguishable' with or without any particular privacy unit, current
evaluations on LLMs mostly treat each example (text record) as the privacy
unit. This leads to uneven user privacy guarantees when contributions per user
vary. We therefore study user-level DP motivated by applications where it
necessary to ensure uniform privacy protection across users. We present a
systematic evaluation of user-level DP for LLM fine-tuning on natural language
generation tasks. Focusing on two mechanisms for achieving user-level DP
guarantees, Group Privacy and User-wise DP-SGD, we investigate design choices
like data selection strategies and parameter tuning for the best
privacy-utility tradeoff.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.14318v1">The Fire Thief Is Also the Keeper: Balancing Usability and Privacy in
  Prompts</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-06-20T13:52:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhili Shen, Zihang Xi, Ying He, Wei Tong, Jingyu Hua, Sheng Zhong</p>
    <p><b>Summary:</b> The rapid adoption of online chatbots represents a significant advancement in
artificial intelligence. However, this convenience brings considerable privacy
concerns, as prompts can inadvertently contain sensitive information exposed to
large language models (LLMs). Limited by high computational costs, reduced task
usability, and excessive system modifications, previous works based on local
deployment, embedding perturbation, and homomorphic encryption are inapplicable
to online prompt-based LLM applications.
  To address these issues, this paper introduces Prompt Privacy Sanitizer
(i.e., ProSan), an end-to-end prompt privacy protection framework that can
produce anonymized prompts with contextual privacy removed while maintaining
task usability and human readability. It can also be seamlessly integrated into
the online LLM service pipeline. To achieve high usability and dynamic
anonymity, ProSan flexibly adjusts its protection targets and strength based on
the importance of the words and the privacy leakage risk of the prompts.
Additionally, ProSan is capable of adapting to diverse computational resource
conditions, ensuring privacy protection even for mobile devices with limited
computing power. Our experiments demonstrate that ProSan effectively removes
private information across various tasks, including question answering, text
summarization, and code generation, with minimal reduction in task performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.14091v1">Protecting Privacy Through Approximating Optimal Parameters for Sequence
  Unlearning in Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-06-20T08:12:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dohyun Lee, Daniel Rim, Minseok Choi, Jaegul Choo</p>
    <p><b>Summary:</b> Although language models (LMs) demonstrate exceptional capabilities on
various tasks, they are potentially vulnerable to extraction attacks, which
represent a significant privacy risk. To mitigate the privacy concerns of LMs,
machine unlearning has emerged as an important research area, which is utilized
to induce the LM to selectively forget about some of its training data. While
completely retraining the model will guarantee successful unlearning and
privacy assurance, it is impractical for LMs, as it would be time-consuming and
resource-intensive. Prior works efficiently unlearn the target token sequences,
but upon subsequent iterations, the LM displays significant degradation in
performance. In this work, we propose Privacy Protection via Optimal Parameters
(POP), a novel unlearning method that effectively forgets the target token
sequences from the pretrained LM by applying optimal gradient updates to the
parameters. Inspired by the gradient derivation of complete retraining, we
approximate the optimal training objective that successfully unlearns the
target sequence while retaining the knowledge from the rest of the training
data. Experimental results demonstrate that POP exhibits remarkable retention
performance post-unlearning across 9 classification and 4 dialogue benchmarks,
outperforming the state-of-the-art by a large margin. Furthermore, we introduce
Remnant Memorization Accuracy that quantifies privacy risks based on token
likelihood and validate its effectiveness through both qualitative and
quantitative analyses.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.13880v1">Privacy-Preserving ECG Data Analysis with Differential Privacy: A
  Literature Review and A Case Study</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-19T23:17:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arin Ghazarian, Jianwei Zheng, Cyril Rakovski</p>
    <p><b>Summary:</b> Differential privacy has become the preeminent technique to protect the
privacy of individuals in a database while allowing useful results from data
analysis to be shared. Notably, it guarantees the amount of privacy loss in the
worst-case scenario. Although many theoretical research papers have been
published, practical real-life application of differential privacy demands
estimating several important parameters without any clear solutions or
guidelines. In the first part of the paper, we provide an overview of key
concepts in differential privacy, followed by a literature review and
discussion of its application to ECG analysis. In the second part of the paper,
we explore how to implement differentially private query release on an
arrhythmia database using a six-step process. We provide guidelines and discuss
the related literature for all the steps involved, such as selection of the
$\epsilon$ value, distribution of the total $\epsilon$ budget across the
queries, and estimation of the sensitivity for the query functions. At the end,
we discuss the shortcomings and challenges of applying differential privacy to
ECG datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.13433v1">Certificates of Differential Privacy and Unlearning for Gradient-Based
  Training</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-06-19T10:47:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Matthew Wicker, Philip Sosnin, Adrianna Janik, Mark N. Müller, Adrian Weller, Calvin Tsay</p>
    <p><b>Summary:</b> Proper data stewardship requires that model owners protect the privacy of
individuals' data used during training. Whether through anonymization with
differential privacy or the use of unlearning in non-anonymized settings, the
gold-standard techniques for providing privacy guarantees can come with
significant performance penalties or be too weak to provide practical
assurances. In part, this is due to the fact that the guarantee provided by
differential privacy represents the worst-case privacy leakage for any
individual, while the true privacy leakage of releasing the prediction for a
given individual might be substantially smaller or even, as we show,
non-existent. This work provides a novel framework based on convex relaxations
and bounds propagation that can compute formal guarantees (certificates) that
releasing specific predictions satisfies $\epsilon=0$ privacy guarantees or do
not depend on data that is subject to an unlearning request. Our framework
offers a new verification-centric approach to privacy and unlearning
guarantees, that can be used to further engender user trust with tighter
privacy guarantees, provide formal proofs of robustness to certain membership
inference attacks, identify potentially vulnerable records, and enhance current
unlearning approaches. We validate the effectiveness of our approach on tasks
from financial services, medical imaging, and natural language processing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.13221v1">Privacy-Preserving Logistic Regression Training on Large Datasets</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-19T05:19:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> John Chiang</p>
    <p><b>Summary:</b> Privacy-preserving machine learning is one class of cryptographic methods
that aim to analyze private and sensitive data while keeping privacy, such as
homomorphic logistic regression training over large encrypted data. In this
paper, we propose an efficient algorithm for logistic regression training on
large encrypted data using Homomorphic Encryption (HE), which is the mini-batch
version of recent methods using a faster gradient variant called
$\texttt{quadratic gradient}$. It is claimed that $\texttt{quadratic gradient}$
can integrate curve information (Hessian matrix) into the gradient and
therefore can effectively accelerate the first-order gradient (descent)
algorithms. We also implement the full-batch version of their method when the
encrypted dataset is so large that it has to be encrypted in the mini-batch
manner. We compare our mini-batch algorithm with our full-batch implementation
method on real financial data consisting of 422,108 samples with 200 freatures.
%Our experiments show that Nesterov's accelerated gradient (NAG) Given the
inefficiency of HEs, our results are inspiring and demonstrate that the
logistic regression training on large encrypted dataset is of practical
feasibility, marking a significant milestone in our understanding.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.13183v1">Communication-Efficient and Privacy-Preserving Decentralized
  Meta-Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-06-19T03:29:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hansi Yang, James T. Kwok</p>
    <p><b>Summary:</b> Distributed learning, which does not require gathering training data in a
central location, has become increasingly important in the big-data era. In
particular, random-walk-based decentralized algorithms are flexible in that
they do not need a central server trusted by all clients and do not require all
clients to be active in all iterations. However, existing distributed learning
algorithms assume that all learning clients share the same task. In this paper,
we consider the more difficult meta-learning setting, in which different
clients perform different (but related) tasks with limited training data. To
reduce communication cost and allow better privacy protection, we propose
LoDMeta (Local Decentralized Meta-learning) with the use of local auxiliary
optimization parameters and random perturbations on the model parameter.
Theoretical results are provided on both convergence and privacy analysis.
Empirical results on a number of few-shot learning data sets demonstrate that
LoDMeta has similar meta-learning accuracy as centralized meta-learning
algorithms, but does not require gathering data from each client and is able to
better protect data privacy for each client.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.13012v1">Data Plagiarism Index: Characterizing the Privacy Risk of Data-Copying
  in Tabular Generative Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-06-18T19:05:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joshua Ward, Chi-Hua Wang, Guang Cheng</p>
    <p><b>Summary:</b> The promise of tabular generative models is to produce realistic synthetic
data that can be shared and safely used without dangerous leakage of
information from the training set. In evaluating these models, a variety of
methods have been proposed to measure the tendency to copy data from the
training dataset when generating a sample. However, these methods suffer from
either not considering data-copying from a privacy threat perspective, not
being motivated by recent results in the data-copying literature or being
difficult to make compatible with the high dimensional, mixed type nature of
tabular data. This paper proposes a new similarity metric and Membership
Inference Attack called Data Plagiarism Index (DPI) for tabular data. We show
that DPI evaluates a new intuitive definition of data-copying and characterizes
the corresponding privacy risk. We show that the data-copying identified by DPI
poses both privacy and fairness threats to common, high performing
architectures; underscoring the necessity for more sophisticated generative
modeling techniques to mitigate this issue.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.12815v1">Privacy Preserving Federated Learning in Medical Imaging with
  Uncertainty Estimation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">  
  <p><b>Published on:</b> 2024-06-18T17:35:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nikolas Koutsoubis, Yasin Yilmaz, Ravi P. Ramachandran, Matthew Schabath, Ghulam Rasool</p>
    <p><b>Summary:</b> Machine learning (ML) and Artificial Intelligence (AI) have fueled remarkable
advancements, particularly in healthcare. Within medical imaging, ML models
hold the promise of improving disease diagnoses, treatment planning, and
post-treatment monitoring. Various computer vision tasks like image
classification, object detection, and image segmentation are poised to become
routine in clinical analysis. However, privacy concerns surrounding patient
data hinder the assembly of large training datasets needed for developing and
training accurate, robust, and generalizable models. Federated Learning (FL)
emerges as a compelling solution, enabling organizations to collaborate on ML
model training by sharing model training information (gradients) rather than
data (e.g., medical images). FL's distributed learning framework facilitates
inter-institutional collaboration while preserving patient privacy. However,
FL, while robust in privacy preservation, faces several challenges. Sensitive
information can still be gleaned from shared gradients that are passed on
between organizations during model training. Additionally, in medical imaging,
quantifying model confidence\uncertainty accurately is crucial due to the noise
and artifacts present in the data. Uncertainty estimation in FL encounters
unique hurdles due to data heterogeneity across organizations. This paper
offers a comprehensive review of FL, privacy preservation, and uncertainty
estimation, with a focus on medical imaging. Alongside a survey of current
research, we identify gaps in the field and suggest future directions for FL
research to enhance privacy and address noisy medical imaging data challenges.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.12736v1">Beyond Visual Appearances: Privacy-sensitive Objects Identification via
  Hybrid Graph Reasoning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-06-18T15:58:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhuohang Jiang, Bingkui Tong, Xia Du, Ahmed Alhammadi, Jizhe Zhou</p>
    <p><b>Summary:</b> The Privacy-sensitive Object Identification (POI) task allocates bounding
boxes for privacy-sensitive objects in a scene. The key to POI is settling an
object's privacy class (privacy-sensitive or non-privacy-sensitive). In
contrast to conventional object classes which are determined by the visual
appearance of an object, one object's privacy class is derived from the scene
contexts and is subject to various implicit factors beyond its visual
appearance. That is, visually similar objects may be totally opposite in their
privacy classes. To explicitly derive the objects' privacy class from the scene
contexts, in this paper, we interpret the POI task as a visual reasoning task
aimed at the privacy of each object in the scene. Following this
interpretation, we propose the PrivacyGuard framework for POI. PrivacyGuard
contains three stages. i) Structuring: an unstructured image is first converted
into a structured, heterogeneous scene graph that embeds rich scene contexts.
ii) Data Augmentation: a contextual perturbation oversampling strategy is
proposed to create slightly perturbed privacy-sensitive objects in a scene
graph, thereby balancing the skewed distribution of privacy classes. iii)
Hybrid Graph Generation & Reasoning: the balanced, heterogeneous scene graph is
then transformed into a hybrid graph by endowing it with extra "node-node" and
"edge-edge" homogeneous paths. These homogeneous paths allow direct message
passing between nodes or edges, thereby accelerating reasoning and facilitating
the capturing of subtle context changes. Based on this hybrid graph... **For
the full abstract, see the original paper.**</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.12592v1">Unmasking the Veil: An Investigation into Concept Ablation for Privacy
  and Copyright Protection in Images</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-06-18T13:22:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shivank Garg, Manyana Tiwari</p>
    <p><b>Summary:</b> In this paper, we extend the study of concept ablation within pre-trained
models as introduced in 'Ablating Concepts in Text-to-Image Diffusion Models'
by (Kumari et al.,2022). Our work focuses on reproducing the results achieved
by the different variants of concept ablation proposed and validated through
predefined metrics. We also introduce a novel variant of concept ablation,
namely 'trademark ablation'. This variant combines the principles of
memorization and instance ablation to tackle the nuanced influence of
proprietary or branded elements in model outputs. Further, our research
contributions include an observational analysis of the model's limitations.
Moreover, we investigate the model's behavior in response to ablation
leakage-inducing prompts, which aim to indirectly ablate concepts, revealing
insights into the model's resilience and adaptability. We also observe the
model's performance degradation on images generated by concepts far from its
target ablation concept, documented in the appendix.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.12457v1">Data Trade and Consumer Privacy</a></h3>
  
  <p><b>Published on:</b> 2024-06-18T10:00:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiadong Gu</p>
    <p><b>Summary:</b> This paper studies optimal mechanisms for collecting and trading data.
Consumers benefit from revealing information about their tastes to a service
provider because this improves the service. However, the information is also
valuable to a third party as it may extract more revenue from the consumer in
another market called the product market. The paper characterizes the
constrained optimal mechanism for the service provider subject to incentive
feasibility. It is shown that the service provider sometimes sells no
information or only partial information in order to preserve profits in the
service market. In a general setup, the service provision distortion and
no-price discrimination in the product market are exclusive. Moreover, a ban on
data trade may reduce social welfare because it makes it harder to price
discriminate in the product market.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.12403v1">PDSS: A Privacy-Preserving Framework for Step-by-Step Distillation of
  Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-06-18T08:48:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tao Fan, Yan Kang, Weijing Chen, Hanlin Gu, Yuanfeng Song, Lixin Fan, Kai Chen, Qiang Yang</p>
    <p><b>Summary:</b> In the context of real-world applications, leveraging large language models
(LLMs) for domain-specific tasks often faces two major challenges:
domain-specific knowledge privacy and constrained resources. To address these
issues, we propose PDSS, a privacy-preserving framework for step-by-step
distillation of LLMs. PDSS works on a server-client architecture, wherein
client transmits perturbed prompts to the server's LLM for rationale
generation. The generated rationales are then decoded by the client and used to
enrich the training of task-specific small language model(SLM) within a
multi-task learning paradigm. PDSS introduces two privacy protection
strategies: the Exponential Mechanism Strategy and the Encoder-Decoder
Strategy, balancing prompt privacy and rationale usability. Experiments
demonstrate the effectiveness of PDSS in various text generation tasks,
enabling the training of task-specific SLM with enhanced performance while
prioritizing data privacy protection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.12330v1">Security and Privacy of 6G Federated Learning-enabled Dynamic Spectrum
  Sharing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2024-06-18T06:54:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Viet Vo, Thusitha Dayaratne, Blake Haydon, Xingliang Yuan, Shangqi Lai, Sharif Abuadbba, Hajime Suzuki, Carsten Rudolph</p>
    <p><b>Summary:</b> Spectrum sharing is increasingly vital in 6G wireless communication,
facilitating dynamic access to unused spectrum holes. Recently, there has been
a significant shift towards employing machine learning (ML) techniques for
sensing spectrum holes. In this context, federated learning (FL)-enabled
spectrum sensing technology has garnered wide attention, allowing for the
construction of an aggregated ML model without disclosing the private spectrum
sensing information of wireless user devices. However, the integrity of
collaborative training and the privacy of spectrum information from local users
have remained largely unexplored. This article first examines the latest
developments in FL-enabled spectrum sharing for prospective 6G scenarios. It
then identifies practical attack vectors in 6G to illustrate potential
AI-powered security and privacy threats in these contexts. Finally, the study
outlines future directions, including practical defense challenges and
guidelines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.12238v1">PFID: Privacy First Inference Delegation Framework for LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-06-18T03:27:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haoyan Yang, Zhitao Li, Yong Zhang, Jianzong Wang, Ning Cheng, Ming Li, Jing Xiao</p>
    <p><b>Summary:</b> This paper introduces a novel privacy-preservation framework named PFID for
LLMs that addresses critical privacy concerns by localizing user data through
model sharding and singular value decomposition. When users are interacting
with LLM systems, their prompts could be subject to being exposed to
eavesdroppers within or outside LLM system providers who are interested in
collecting users' input. In this work, we proposed a framework to camouflage
user input, so as to alleviate privacy issues. Our framework proposes to place
model shards on the client and the public server, we sent compressed hidden
states instead of prompts to and from servers. Clients have held back
information that can re-privatized the hidden states so that overall system
performance is comparable to traditional LLMs services. Our framework was
designed to be communication efficient, computation can be delegated to the
local client so that the server's computation burden can be lightened. We
conduct extensive experiments on machine translation tasks to verify our
framework's performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.12103v1">Centering Policy and Practice: Research Gaps around Usable Differential
  Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-06-17T21:32:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rachel Cummings, Jayshree Sarathy</p>
    <p><b>Summary:</b> As a mathematically rigorous framework that has amassed a rich theoretical
literature, differential privacy is considered by many experts to be the gold
standard for privacy-preserving data analysis. Others argue that while
differential privacy is a clean formulation in theory, it poses significant
challenges in practice. Both perspectives are, in our view, valid and
important. To bridge the gaps between differential privacy's promises and its
real-world usability, researchers and practitioners must work together to
advance policy and practice of this technology. In this paper, we outline
pressing open questions towards building usable differential privacy and offer
recommendations for the field, such as developing risk frameworks to align with
user needs, tailoring communications for different stakeholders, modeling the
impact of privacy-loss parameters, investing in effective user interfaces, and
facilitating algorithmic and procedural audits of differential privacy systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.12003v1">P3GNN: A Privacy-Preserving Provenance Graph-Based Model for APT
  Detection in Software Defined Networking</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-17T18:14:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hedyeh Nazari, Abbas Yazdinejad, Ali Dehghantanha, Fattane Zarrinkalam, Gautam Srivastava</p>
    <p><b>Summary:</b> Software Defined Networking (SDN) has brought significant advancements in
network management and programmability. However, this evolution has also
heightened vulnerability to Advanced Persistent Threats (APTs), sophisticated
and stealthy cyberattacks that traditional detection methods often fail to
counter, especially in the face of zero-day exploits. A prevalent issue is the
inadequacy of existing strategies to detect novel threats while addressing data
privacy concerns in collaborative learning scenarios. This paper presents P3GNN
(privacy-preserving provenance graph-based graph neural network model), a novel
model that synergizes Federated Learning (FL) with Graph Convolutional Networks
(GCN) for effective APT detection in SDN environments. P3GNN utilizes
unsupervised learning to analyze operational patterns within provenance graphs,
identifying deviations indicative of security breaches. Its core feature is the
integration of FL with homomorphic encryption, which fortifies data
confidentiality and gradient integrity during collaborative learning. This
approach addresses the critical challenge of data privacy in shared learning
contexts. Key innovations of P3GNN include its ability to detect anomalies at
the node level within provenance graphs, offering a detailed view of attack
trajectories and enhancing security analysis. Furthermore, the models
unsupervised learning capability enables it to identify zero-day attacks by
learning standard operational patterns. Empirical evaluation using the DARPA
TCE3 dataset demonstrates P3GNNs exceptional performance, achieving an accuracy
of 0.93 and a low false positive rate of 0.06.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.11323v1">Transparency, Privacy, and Fairness in Recommender Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2024-06-17T08:37:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dominik Kowald</p>
    <p><b>Summary:</b> Recommender systems have become a pervasive part of our daily online
experience, and are one of the most widely used applications of artificial
intelligence and machine learning. Therefore, regulations and requirements for
trustworthy artificial intelligence, for example, the European AI Act, which
includes notions such as transparency, privacy, and fairness are also highly
relevant for the design of recommender systems in practice. This habilitation
elaborates on aspects related to these three notions in the light of
recommender systems, namely: (i) transparency and cognitive models, (ii)
privacy and limited preference information, and (iii) fairness and popularity
bias in recommender systems. Specifically, with respect to aspect (i), we
highlight the usefulness of incorporating psychological theories for a
transparent design process of recommender systems. We term this type of systems
psychology-informed recommender systems. In aspect (ii), we study and address
the trade-off between accuracy and privacy in differentially-private
recommendations. We design a novel recommendation approach for collaborative
filtering based on an efficient neighborhood reuse concept, which reduces the
number of users that need to be protected with differential privacy.
Furthermore, we address the related issue of limited availability of user
preference information, e.g., click data, in the settings of session-based and
cold-start recommendations. With respect to aspect (iii), we analyze popularity
bias in recommender systems. We find that the recommendation frequency of an
item is positively correlated with this item's popularity. This also leads to
the unfair treatment of users with little interest in popular content. Finally,
we study long-term fairness dynamics in algorithmic decision support in the
labor market using agent-based modeling techniques.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.11208v1">Privacy-preserving Pseudonym Schemes for Personalized 3D Avatars in
  Mobile Social Metaverses</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2024-06-17T04:58:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Cheng Su, Xiaofeng Luo, Zhenmou Liu, Jiawen Kang, Min Hao, Zehui Xiong, Zhaohui Yang, Chongwen Huang</p>
    <p><b>Summary:</b> The emergence of mobile social metaverses, a novel paradigm bridging physical
and virtual realms, has led to the widespread adoption of avatars as digital
representations for Social Metaverse Users (SMUs) within virtual spaces.
Equipped with immersive devices, SMUs leverage Edge Servers (ESs) to deploy
their avatars and engage with other SMUs in virtual spaces. To enhance
immersion, SMUs incline to opt for 3D avatars for social interactions. However,
existing 3D avatars are typically generated through scanning the real faces of
SMUs, which can raise concerns regarding information privacy and security, such
as profile identity leakages. To tackle this, we introduce a new framework for
personalized 3D avatar construction, leveraging a two-layer network model that
provides SMUs with the option to customize their personal avatars for privacy
preservation. Specifically, our approach introduces avatar pseudonyms to
jointly safeguard the profile and digital identity privacy of the generated
avatars. Then, we design a novel metric named Privacy of Personalized Avatars
(PoPA), to evaluate effectiveness of the avatar pseudonyms. To optimize
pseudonym resource, we model the pseudonym distribution process as a
Stackelberg game and employ Deep Reinforcement Learning (DRL) to learn
equilibrium strategies under incomplete information. Simulation results
validate the efficacy and feasibility of our proposed schemes for mobile social
metaverses.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.11149v1">GoldCoin: Grounding Large Language Models in Privacy Laws via Contextual
  Integrity Theory</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-17T02:27:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wei Fan, Haoran Li, Zheye Deng, Weiqi Wang, Yangqiu Song</p>
    <p><b>Summary:</b> Privacy issues arise prominently during the inappropriate transmission of
information between entities. Existing research primarily studies privacy by
exploring various privacy attacks, defenses, and evaluations within narrowly
predefined patterns, while neglecting that privacy is not an isolated,
context-free concept limited to traditionally sensitive data (e.g., social
security numbers), but intertwined with intricate social contexts that
complicate the identification and analysis of potential privacy violations. The
advent of Large Language Models (LLMs) offers unprecedented opportunities for
incorporating the nuanced scenarios outlined in privacy laws to tackle these
complex privacy issues. However, the scarcity of open-source relevant case
studies restricts the efficiency of LLMs in aligning with specific legal
statutes. To address this challenge, we introduce a novel framework, GoldCoin,
designed to efficiently ground LLMs in privacy laws for judicial assessing
privacy violations. Our framework leverages the theory of contextual integrity
as a bridge, creating numerous synthetic scenarios grounded in relevant privacy
statutes (e.g., HIPAA), to assist LLMs in comprehending the complex contexts
for identifying privacy risks in the real world. Extensive experimental results
demonstrate that GoldCoin markedly enhances LLMs' capabilities in recognizing
privacy risks across real court cases, surpassing the baselines on different
judicial tasks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.11087v2">MemDPT: Differential Privacy for Memory Efficient Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-06-16T22:11:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yanming Liu, Xinyue Peng, Jiannan Cao, Yuwei Zhang, Chen Ma, Songhang Deng, Mengchen Fu, Xuhong Zhang, Sheng Cheng, Xun Wang, Jianwei Yin, Tianyu Du</p>
    <p><b>Summary:</b> Large language models have consistently demonstrated remarkable performance
across a wide spectrum of applications. Nonetheless, the deployment of these
models can inadvertently expose user privacy to potential risks. The
substantial memory demands of these models during training represent a
significant resource consumption challenge. The sheer size of these models
imposes a considerable burden on memory resources, which is a matter of
significant concern in practice. In this paper, we present an innovative
training framework MemDPT that not only reduces the memory cost of large
language models but also places a strong emphasis on safeguarding user data
privacy. MemDPT provides edge network and reverse network designs to
accommodate various differential privacy memory-efficient fine-tuning schemes.
Our approach not only achieves $2 \sim 3 \times$ memory optimization but also
provides robust privacy protection, ensuring that user data remains secure and
confidential. Extensive experiments have demonstrated that MemDPT can
effectively provide differential privacy efficient fine-tuning across various
task scenarios.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.10976v1">Promoting Data and Model Privacy in Federated Learning through Quantized
  LoRA</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-16T15:23:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> JianHao Zhu, Changze Lv, Xiaohua Wang, Muling Wu, Wenhao Liu, Tianlong Li, Zixuan Ling, Cenyuan Zhang, Xiaoqing Zheng, Xuanjing Huang</p>
    <p><b>Summary:</b> Conventional federated learning primarily aims to secure the privacy of data
distributed across multiple edge devices, with the global model dispatched to
edge devices for parameter updates during the learning process. However, the
development of large language models (LLMs) requires substantial data and
computational resources, rendering them valuable intellectual properties for
their developers and owners. To establish a mechanism that protects both data
and model privacy in a federated learning context, we introduce a method that
just needs to distribute a quantized version of the model's parameters during
training. This method enables accurate gradient estimations for parameter
updates while preventing clients from accessing a model whose performance is
comparable to the centrally hosted one. Moreover, we combine this quantization
strategy with LoRA, a popular and parameter-efficient fine-tuning method, to
significantly reduce communication costs in federated learning. The proposed
framework, named \textsc{FedLPP}, successfully ensures both data and model
privacy in the federated learning context. Additionally, the learned central
model exhibits good generalization and can be trained in a resource-efficient
manner.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.10884v1">Linkage on Security, Privacy and Fairness in Federated Learning: New
  Balances and New Perspectives</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-06-16T10:31:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Linlin Wang, Tianqing Zhu, Wanlei Zhou, Philip S. Yu</p>
    <p><b>Summary:</b> Federated learning is fast becoming a popular paradigm for applications
involving mobile devices, banking systems, healthcare, and IoT systems. Hence,
over the past five years, researchers have undertaken extensive studies on the
privacy leaks, security threats, and fairness associated with these emerging
models. For the most part, these three critical concepts have been studied in
isolation; however, recent research has revealed that there may be an intricate
interplay between them. For instance, some researchers have discovered that
pursuing fairness may compromise privacy, or that efforts to enhance security
can impact fairness. These emerging insights shed light on the fundamental
connections between privacy, security, and fairness within federated learning,
and, by delving deeper into these interconnections, we may be able to
significantly augment research and development across the field. Consequently,
the aim of this survey is to offer comprehensive descriptions of the privacy,
security, and fairness issues in federated learning. Moreover, we analyze the
complex relationships between these three dimensions of cyber safety and
pinpoint the fundamental elements that influence each of them. We contend that
there exists a trade-off between privacy and fairness and between security and
gradient sharing. On this basis, fairness can function as a bridge between
privacy and security to build models that are either more secure or more
private. Building upon our observations, we identify the trade-offs between
privacy and fairness and between security and fairness within the context of
federated learning. The survey then concludes with promising directions for
future research in this vanguard field.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.10803v1">HiddenTables & PyQTax: A Cooperative Game and Dataset For TableQA to
  Ensure Scale and Data Privacy Across a Myriad of Taxonomies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2024-06-16T04:53:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> William Watson, Nicole Cho, Tucker Balch, Manuela Veloso</p>
    <p><b>Summary:</b> A myriad of different Large Language Models (LLMs) face a common challenge in
contextually analyzing table question-answering tasks. These challenges are
engendered from (1) finite context windows for large tables, (2) multi-faceted
discrepancies amongst tokenization patterns against cell boundaries, and (3)
various limitations stemming from data confidentiality in the process of using
external models such as gpt-3.5-turbo. We propose a cooperative game dubbed
"HiddenTables" as a potential resolution to this challenge. In essence,
"HiddenTables" is played between the code-generating LLM "Solver" and the
"Oracle" which evaluates the ability of the LLM agents to solve Table QA tasks.
This game is based on natural language schemas and importantly, ensures the
security of the underlying data. We provide evidential experiments on a diverse
set of tables that demonstrate an LLM's collective inability to generalize and
perform on complex queries, handle compositional dependencies, and align
natural language to programmatic commands when concrete table schemas are
provided. Unlike encoder-based models, we have pushed the boundaries of
"HiddenTables" to not be limited by the number of rows - therefore we exhibit
improved efficiency in prompt and completion tokens. Our infrastructure has
spawned a new dataset "PyQTax" that spans across 116,671 question-table-answer
triplets and provides additional fine-grained breakdowns & labels for varying
question taxonomies. Therefore, in tandem with our academic contributions
regarding LLMs' deficiency in TableQA tasks, "HiddenTables" is a tactile
manifestation of how LLMs can interact with massive datasets while ensuring
data security and minimizing generation costs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.10563v1">Privacy-Preserving Heterogeneous Federated Learning for Sensitive
  Healthcare Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-15T08:43:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yukai Xu, Jingfeng Zhang, Yujie Gu</p>
    <p><b>Summary:</b> In the realm of healthcare where decentralized facilities are prevalent,
machine learning faces two major challenges concerning the protection of data
and models. The data-level challenge concerns the data privacy leakage when
centralizing data with sensitive personal information. While the model-level
challenge arises from the heterogeneity of local models, which need to be
collaboratively trained while ensuring their confidentiality to address
intellectual property concerns. To tackle these challenges, we propose a new
framework termed Abstention-Aware Federated Voting (AAFV) that can
collaboratively and confidentially train heterogeneous local models while
simultaneously protecting the data privacy. This is achieved by integrating a
novel abstention-aware voting mechanism and a differential privacy mechanism
onto local models' predictions. In particular, the proposed abstention-aware
voting mechanism exploits a threshold-based abstention method to select
high-confidence votes from heterogeneous local models, which not only enhances
the learning utility but also protects model confidentiality. Furthermore, we
implement AAFV on two practical prediction tasks of diabetes and in-hospital
patient mortality. The experiments demonstrate the effectiveness and
confidentiality of AAFV in testing accuracy and privacy protection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.09682v1">Privacy-preserving Quantification of Non-IID Degree in Federated
  Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-14T03:08:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuping Yan, Yizhi Wang, Yingchao Yu, Yaochu Jin</p>
    <p><b>Summary:</b> Federated learning (FL) offers a privacy-preserving approach to machine
learning for multiple collaborators without sharing raw data. However, the
existence of non-independent and non-identically distributed (non-IID) datasets
across different clients presents a significant challenge to FL, leading to a
sharp drop in accuracy, reduced efficiency, and hindered implementation. To
address the non-IID problem, various methods have been proposed, including
clustering and personalized FL frameworks. Nevertheless, to date, a formal
quantitative definition of the non-IID degree between different clients'
datasets is still missing, hindering the clients from comparing and obtaining
an overview of their data distributions with other clients. For the first time,
this paper proposes a quantitative definition of the non-IID degree in the
federated environment by employing the cumulative distribution function (CDF),
called Fully Homomorphic Encryption-based Federated Cumulative Distribution
Function (FHE-FCDF). This method utilizes cryptographic primitive fully
homomorphic encryption to enable clients to estimate the non-IID degree while
ensuring privacy preservation. The experiments conducted on the CIFAR-100
non-IID dataset validate the effectiveness of our proposed method.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.09547v2">FLea: Addressing Data Scarcity and Label Skew in Federated Learning via
  Privacy-preserving Feature Augmentation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-06-13T19:28:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tong Xia, Abhirup Ghosh, Xinchi Qiu, Cecilia Mascolo</p>
    <p><b>Summary:</b> Federated Learning (FL) enables model development by leveraging data
distributed across numerous edge devices without transferring local data to a
central server. However, existing FL methods still face challenges when dealing
with scarce and label-skewed data across devices, resulting in local model
overfitting and drift, consequently hindering the performance of the global
model. In response to these challenges, we propose a pioneering framework
called FLea, incorporating the following key components: i) A global feature
buffer that stores activation-target pairs shared from multiple clients to
support local training. This design mitigates local model drift caused by the
absence of certain classes; ii) A feature augmentation approach based on local
and global activation mix-ups for local training. This strategy enlarges the
training samples, thereby reducing the risk of local overfitting; iii) An
obfuscation method to minimize the correlation between intermediate activations
and the source data, enhancing the privacy of shared features. To verify the
superiority of FLea, we conduct extensive experiments using a wide range of
data modalities, simulating different levels of local data scarcity and label
skew. The results demonstrate that FLea consistently outperforms
state-of-the-art FL counterparts (among 13 of the experimented 18 settings, the
improvement is over 5% while concurrently mitigating the privacy
vulnerabilities associated with shared features. Code is available at
https://github.com/XTxiatong/FLea.git.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.09214v1">Applying Multi-Agent Negotiation to Solve the Production Routing Problem
  With Privacy Preserving</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2024-06-13T15:15:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Luiza Pellin Biasoto, Vinicius Renan de Carvalho, Jaime Simão Sichman</p>
    <p><b>Summary:</b> This paper presents a novel approach to address the Production Routing
Problem with Privacy Preserving (PRPPP) in supply chain optimization. The
integrated optimization of production, inventory, distribution, and routing
decisions in real-world industry applications poses several challenges,
including increased complexity, discrepancies between planning and execution,
and constraints on information sharing. To mitigate these challenges, this
paper proposes the use of intelligent agent negotiation within a hybrid
Multi-Agent System (MAS) integrated with optimization algorithms. The MAS
facilitates communication and coordination among entities, encapsulates private
information, and enables negotiation. This, along with optimization algorithms,
makes it a compelling framework for establishing optimal solutions. The
approach is supported by real-world applications and synergies between MAS and
optimization methods, demonstrating its effectiveness in addressing complex
supply chain optimization problems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.09037v1">Evaluating Privacy, Security, and Trust Perceptions in Conversational
  AI: A Systematic Review</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">  
  <p><b>Published on:</b> 2024-06-13T12:20:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anna Leschanowsky, Silas Rech, Birgit Popp, Tom Bäckström</p>
    <p><b>Summary:</b> Conversational AI (CAI) systems which encompass voice- and text-based
assistants are on the rise and have been largely integrated into people's
everyday lives. Despite their widespread adoption, users voice concerns
regarding privacy, security and trust in these systems. However, the
composition of these perceptions, their impact on technology adoption and usage
and the relationship between privacy, security and trust perceptions in the CAI
context remain open research challenges. This study contributes to the field by
conducting a Systematic Literature Review and offers insights into the current
state of research on privacy, security and trust perceptions in the context of
CAI systems. The review covers application fields and user groups and sheds
light on empirical methods and tools used for assessment. Moreover, it provides
insights into the reliability and validity of privacy, security and trust
scales, as well as extensively investigating the subconstructs of each item as
well as additional concepts which are concurrently collected. We point out that
the perceptions of trust, privacy and security overlap based on the
subconstructs we identified. While the majority of studies investigate one of
these concepts, only a few studies were found exploring privacy, security and
trust perceptions jointly. Our research aims to inform on directions to develop
and use reliable scales for users' privacy, security and trust perceptions and
contribute to the development of trustworthy CAI systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.09005v1">Privacy Aware Memory Forensics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-13T11:18:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Janardhan Kalikiri, Gaurav Varshney, Jaswinder Kour, Tarandeep Singh</p>
    <p><b>Summary:</b> In recent years, insider threats and attacks have been increasing in terms of
frequency and cost to the corporate business. The utilization of end-to-end
encrypted instant messaging applications (WhatsApp, Telegram, VPN) by malicious
insiders raised data breach incidents exponentially. The Securities and
Exchange Board of India (SEBI) investigated reports on such data leak incidents
and reported about twelve companies where earnings data and financial
information were leaked using WhatsApp messages. Recent surveys indicate that
60% of data breaches are primarily caused by malicious insider threats.
Especially, in the case of the defense environment, information leaks by
insiders will jeopardize the countrys national security. Sniffing of network
and host-based activities will not work in an insider threat detection
environment due to end-to-end encryption. Memory forensics allows access to the
messages sent or received over an end-to-end encrypted environment but with a
total compromise of the users privacy. In this research, we present a novel
solution to detect data leakages by insiders in an organization. Our approach
captures the RAM of the insiders device and analyses it for sensitive
information leaks from a host system while maintaining the users privacy.
Sensitive data leaks are identified with context using a deep learning model.
The feasibility and effectiveness of the proposed idea have been demonstrated
with the help of a military use case. The proposed architecture can however be
used across various use cases with minor modifications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.08918v1">Beyond the Calibration Point: Mechanism Comparison in Differential
  Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">  
  <p><b>Published on:</b> 2024-06-13T08:30:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Georgios Kaissis, Stefan Kolek, Borja Balle, Jamie Hayes, Daniel Rueckert</p>
    <p><b>Summary:</b> In differentially private (DP) machine learning, the privacy guarantees of DP
mechanisms are often reported and compared on the basis of a single
$(\varepsilon, \delta)$-pair. This practice overlooks that DP guarantees can
vary substantially \emph{even between mechanisms sharing a given $(\varepsilon,
\delta)$}, and potentially introduces privacy vulnerabilities which can remain
undetected. This motivates the need for robust, rigorous methods for comparing
DP guarantees in such cases. Here, we introduce the $\Delta$-divergence between
mechanisms which quantifies the worst-case excess privacy vulnerability of
choosing one mechanism over another in terms of $(\varepsilon, \delta)$, $f$-DP
and in terms of a newly presented Bayesian interpretation. Moreover, as a
generalisation of the Blackwell theorem, it is endowed with strong
decision-theoretic foundations. Through application examples, we show that our
techniques can facilitate informed decision-making and reveal gaps in the
current understanding of privacy risks, as current practices in DP-SGD often
result in choosing mechanisms with high excess privacy vulnerabilities.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.07973v2">Unique Security and Privacy Threats of Large Language Model: A
  Comprehensive Survey</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-12T07:55:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shang Wang, Tianqing Zhu, Bo Liu, Ming Ding, Xu Guo, Dayong Ye, Wanlei Zhou, Philip S. Yu</p>
    <p><b>Summary:</b> With the rapid development of artificial intelligence, large language models
(LLMs) have made remarkable advancements in natural language processing. These
models are trained on vast datasets to exhibit powerful language understanding
and generation capabilities across various applications, including machine
translation, chatbots, and agents. However, LLMs have revealed a variety of
privacy and security issues throughout their life cycle, drawing significant
academic and industrial attention. Moreover, the risks faced by LLMs differ
significantly from those encountered by traditional language models. Given that
current surveys lack a clear taxonomy of unique threat models across diverse
scenarios, we emphasize the unique privacy and security threats associated with
five specific scenarios: pre-training, fine-tuning, retrieval-augmented
generation systems, deployment, and LLM-based agents. Addressing the
characteristics of each risk, this survey outlines potential threats and
countermeasures. Research on attack and defense situations can offer feasible
research directions, enabling more areas to benefit from LLMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.10280v1">Transferable Embedding Inversion Attack: Uncovering Privacy Risks in
  Text Embeddings without Model Queries</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-06-12T05:09:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yu-Hsiang Huang, Yuche Tsai, Hsiang Hsiao, Hong-Yi Lin, Shou-De Lin</p>
    <p><b>Summary:</b> This study investigates the privacy risks associated with text embeddings,
focusing on the scenario where attackers cannot access the original embedding
model. Contrary to previous research requiring direct model access, we explore
a more realistic threat model by developing a transfer attack method. This
approach uses a surrogate model to mimic the victim model's behavior, allowing
the attacker to infer sensitive information from text embeddings without direct
access. Our experiments across various embedding models and a clinical dataset
demonstrate that our transfer attack significantly outperforms traditional
methods, revealing the potential privacy vulnerabilities in embedding
technologies and emphasizing the need for enhanced security measures.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.07314v1">Rethinking the impact of noisy labels in graph classification: A utility
  and privacy perspective</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-06-11T14:44:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> De Li, Xianxian Li, Zeming Gan, Qiyu Li, Bin Qu, Jinyan Wang</p>
    <p><b>Summary:</b> Graph neural networks based on message-passing mechanisms have achieved
advanced results in graph classification tasks. However, their generalization
performance degrades when noisy labels are present in the training data. Most
existing noisy labeling approaches focus on the visual domain or graph node
classification tasks and analyze the impact of noisy labels only from a utility
perspective. Unlike existing work, in this paper, we measure the effects of
noise labels on graph classification from data privacy and model utility
perspectives. We find that noise labels degrade the model's generalization
performance and enhance the ability of membership inference attacks on graph
data privacy. To this end, we propose the robust graph neural network approach
with noisy labeled graph classification. Specifically, we first accurately
filter the noisy samples by high-confidence samples and the first feature
principal component vector of each class. Then, the robust principal component
vectors and the model output under data augmentation are utilized to achieve
noise label correction guided by dual spatial information. Finally, supervised
graph contrastive learning is introduced to enhance the embedding quality of
the model and protect the privacy of the training graph data. The utility and
privacy of the proposed method are validated by comparing twelve different
methods on eight real graph classification datasets. Compared with the
state-of-the-art methods, the RGLC method achieves at most and at least 7.8%
and 0.8% performance gain at 30% noisy labeling rate, respectively, and reduces
the accuracy of privacy attacks to below 60%.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.06990v2">Privacy-Utility Tradeoff Based on $α$-lift</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2024-06-11T06:39:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohammad Amin Zarrabian, Parastoo Sadeghi</p>
    <p><b>Summary:</b> Information density and its exponential form, known as lift, play a central
role in information privacy leakage measures. $\alpha$-lift is the power-mean
of lift, which is tunable between the worst-case measure max-lift
($\alpha=\infty$) and more relaxed versions ($\alpha<\infty$). This paper
investigates the optimization problem of the privacy-utility tradeoff (PUT)
where $\alpha$-lift and mutual information are privacy and utility measures,
respectively. Due to the nonlinear nature of $\alpha$-lift for $\alpha<\infty$,
finding the optimal solution is challenging. Therefore, we propose a heuristic
algorithm to estimate the optimal utility for each value of $\alpha$, inspired
by the optimal solution for $\alpha=\infty$ and the convexity of $\alpha$-lift
with respect to the lift, which we prove. The numerical results show the
efficacy of the algorithm and indicate the effective range of $\alpha$ and
privacy budget $\varepsilon$ with good PUT performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.06755v1">Optimal Federated Learning for Nonparametric Regression with
  Heterogeneous Distributed Differential Privacy Constraints</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">   
  <p><b>Published on:</b> 2024-06-10T19:34:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> T. Tony Cai, Abhinav Chakraborty, Lasse Vuursteen</p>
    <p><b>Summary:</b> This paper studies federated learning for nonparametric regression in the
context of distributed samples across different servers, each adhering to
distinct differential privacy constraints. The setting we consider is
heterogeneous, encompassing both varying sample sizes and differential privacy
constraints across servers. Within this framework, both global and pointwise
estimation are considered, and optimal rates of convergence over the Besov
spaces are established.
  Distributed privacy-preserving estimators are proposed and their risk
properties are investigated. Matching minimax lower bounds, up to a logarithmic
factor, are established for both global and pointwise estimation. Together,
these findings shed light on the tradeoff between statistical accuracy and
privacy preservation. In particular, we characterize the compromise not only in
terms of the privacy budget but also concerning the loss incurred by
distributing data within the privacy framework as a whole. This insight
captures the folklore wisdom that it is easier to retain privacy in larger
samples, and explores the differences between pointwise and global estimation
under distributed privacy constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.06749v1">Federated Nonparametric Hypothesis Testing with Differential Privacy
  Constraints: Optimal Rates and Adaptive Tests</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">   
  <p><b>Published on:</b> 2024-06-10T19:25:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> T. Tony Cai, Abhinav Chakraborty, Lasse Vuursteen</p>
    <p><b>Summary:</b> Federated learning has attracted significant recent attention due to its
applicability across a wide range of settings where data is collected and
analyzed across disparate locations. In this paper, we study federated
nonparametric goodness-of-fit testing in the white-noise-with-drift model under
distributed differential privacy (DP) constraints.
  We first establish matching lower and upper bounds, up to a logarithmic
factor, on the minimax separation rate. This optimal rate serves as a benchmark
for the difficulty of the testing problem, factoring in model characteristics
such as the number of observations, noise level, and regularity of the signal
class, along with the strictness of the $(\epsilon,\delta)$-DP requirement. The
results demonstrate interesting and novel phase transition phenomena.
Furthermore, the results reveal an interesting phenomenon that distributed
one-shot protocols with access to shared randomness outperform those without
access to shared randomness. We also construct a data-driven testing procedure
that possesses the ability to adapt to an unknown regularity parameter over a
large collection of function classes with minimal additional cost, all while
maintaining adherence to the same set of DP constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.06473v1">DiffAudit: Auditing Privacy Practices of Online Services for Children
  and Adolescents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-10T17:14:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Olivia Figueira, Rahmadi Trimananda, Athina Markopoulou, Scott Jordan</p>
    <p><b>Summary:</b> Children's and adolescents' online data privacy are regulated by laws such as
the Children's Online Privacy Protection Act (COPPA) and the California
Consumer Privacy Act (CCPA). Online services that are directed towards general
audiences (i.e., including children, adolescents, and adults) must comply with
these laws. In this paper, first, we present DiffAudit, a platform-agnostic
privacy auditing methodology for general audience services. DiffAudit performs
differential analysis of network traffic data flows to compare data processing
practices (i) between child, adolescent, and adult users and (ii) before and
after consent is given and user age is disclosed. We also present a data type
classification method that utilizes GPT-4 and our data type ontology based on
COPPA and CCPA, allowing us to identify considerably more data types than prior
work. Second, we apply DiffAudit to a set of popular general audience mobile
and web services and observe a rich set of behaviors extracted from over 440K
outgoing requests, containing 3,968 unique data types we extracted and
classified. We reveal problematic data processing practices prior to consent
and age disclosure, lack of differentiation between age-specific data flows,
inconsistent privacy policy disclosures, and sharing of linkable data with
third parties, including advertising and tracking services.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.06186v1">A Survey on Machine Unlearning: Techniques and New Emerged Privacy Risks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-10T11:31:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hengzhu Liu, Ping Xiong, Tianqing Zhu, Philip S. Yu</p>
    <p><b>Summary:</b> The explosive growth of machine learning has made it a critical
infrastructure in the era of artificial intelligence. The extensive use of data
poses a significant threat to individual privacy. Various countries have
implemented corresponding laws, such as GDPR, to protect individuals' data
privacy and the right to be forgotten. This has made machine unlearning a
research hotspot in the field of privacy protection in recent years, with the
aim of efficiently removing the contribution and impact of individual data from
trained models. The research in academia on machine unlearning has continuously
enriched its theoretical foundation, and many methods have been proposed,
targeting different data removal requests in various application scenarios.
However, recently researchers have found potential privacy leakages of various
of machine unlearning approaches, making the privacy preservation on machine
unlearning area a critical topic. This paper provides an overview and analysis
of the existing research on machine unlearning, aiming to present the current
vulnerabilities of machine unlearning approaches. We analyze privacy risks in
various aspects, including definitions, implementation methods, and real-world
applications. Compared to existing reviews, we analyze the new challenges posed
by the latest malicious attack techniques on machine unlearning from the
perspective of privacy threats. We hope that this survey can provide an initial
but comprehensive discussion on this new emerging area.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.05858v1">Comments on "Federated Learning with Differential Privacy: Algorithms
  and Performance Analysis"</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Performance-F9C80E">
  <p><b>Published on:</b> 2024-06-09T17:03:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mahtab Talaei, Iman Izadi</p>
    <p><b>Summary:</b> In the paper by Wei et al. ("Federated Learning with Differential Privacy:
Algorithms and Performance Analysis"), the convergence performance of the
proposed differential privacy algorithm in federated learning (FL), known as
Noising before Model Aggregation FL (NbAFL), was studied. However, the
presented convergence upper bound of NbAFL (Theorem 2) is incorrect. This
comment aims to present the correct form of the convergence upper bound for
NbAFL.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.05545v1">Privacy-Preserving Optimal Parameter Selection for Collaborative
  Clustering</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-08T18:21:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maryam Ghasemian, Erman Ayday</p>
    <p><b>Summary:</b> This study investigates the optimal selection of parameters for collaborative
clustering while ensuring data privacy. We focus on key clustering algorithms
within a collaborative framework, where multiple data owners combine their
data. A semi-trusted server assists in recommending the most suitable
clustering algorithm and its parameters. Our findings indicate that the privacy
parameter ($\epsilon$) minimally impacts the server's recommendations, but an
increase in $\epsilon$ raises the risk of membership inference attacks, where
sensitive information might be inferred. To mitigate these risks, we implement
differential privacy techniques, particularly the Randomized Response
mechanism, to add noise and protect data privacy. Our approach demonstrates
that high-quality clustering can be achieved while maintaining data
confidentiality, as evidenced by metrics such as the Adjusted Rand Index and
Silhouette Score. This study contributes to privacy-aware data sharing, optimal
algorithm and parameter selection, and effective communication between data
owners and the server.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.05459v1">PriviFy: Designing Tangible Interfaces for Configuring IoT Privacy
  Preferences</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2024-06-08T12:35:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bayan Al Muhander, Omer Rana, Charith Perera</p>
    <p><b>Summary:</b> The Internet of Things (IoT) devices, such as smart speakers can collect
sensitive user data, necessitating the need for users to manage their privacy
preferences. However, configuring these preferences presents users with
multiple challenges. Existing privacy controls often lack transparency, are
hard to understand, and do not provide meaningful choices. On top of that,
users struggle to locate privacy settings due to multiple menus or confusing
labeling, which discourages them from using these controls. We introduce
PriviFy (Privacy Simplify-er), a novel and user-friendly tangible interface
that can simplify the configuration of smart devices privacy settings. PriviFy
is designed to propose an enhancement to existing hardware by integrating
additional features that improve privacy management. We envision that positive
feedback and user experiences from our study will inspire consumer product
developers and smart device manufacturers to incorporate the useful design
elements we have identified. Using fidelity prototyping, we iteratively
designed PriviFy prototype with 20 participants to include interactive features
such as knobs, buttons, lights, and notifications that allow users to configure
their data privacy preferences and receive confirmation of their choices. We
further evaluated PriviFy high-fidelity prototype with 20 more participants.
Our results show that PriviFy helps simplify the complexity of privacy
preferences configuration with a significant usability score at p < .05 (P =
0.000000017, t = -8.8639). PriviFy successfully met users privacy needs and
enabled them to regain control over their data. We conclude by recommending the
importance of designing specific privacy configuration options.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.05451v1">PrivacyCube: Data Physicalization for Enhancing Privacy Awareness in IoT</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2024-06-08T12:20:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bayan Al Muhander, Nalin Arachchilage, Yasar Majib, Mohammed Alosaimi, Omer Rana, Charith Perera</p>
    <p><b>Summary:</b> People are increasingly bringing Internet of Things (IoT) devices into their
homes without understanding how their data is gathered, processed, and used. We
describe PrivacyCube, a novel data physicalization designed to increase privacy
awareness within smart home environments. PrivacyCube visualizes IoT data
consumption by displaying privacy-related notices. PrivacyCube aims to assist
smart home occupants to (i) understand their data privacy better and (ii) have
conversations around data management practices of IoT devices used within their
homes. Using PrivacyCube, households can learn and make informed privacy
decisions collectively. To evaluate PrivacyCube, we used multiple research
methods throughout the different stages of design. We first conducted a focus
group study in two stages with six participants to compare PrivacyCube to text
and state-of-the-art privacy policies. We then deployed PrivacyCube in a
14-day-long field study with eight households. Our results show that
PrivacyCube helps home occupants comprehend IoT privacy better with
significantly increased privacy awareness at p < .05 (p=0.00041, t= -5.57).
Participants preferred PrivacyCube over text privacy policies because it was
comprehensive and easier to use. PrivacyCube and Privacy Label, a
state-of-the-art approach, both received positive reviews from participants,
with PrivacyCube being preferred for its interactivity and ability to encourage
conversations. PrivacyCube was also considered by home occupants as a piece of
home furniture, encouraging them to socialize and discuss IoT privacy
implications using this device.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.04827v1">Black Box Differential Privacy Auditing Using Total Variation Distance</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-06-07T10:52:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Antti Koskela, Jafar Mohammadi</p>
    <p><b>Summary:</b> We present a practical method to audit the differential privacy (DP)
guarantees of a machine learning model using a small hold-out dataset that is
not exposed to the model during the training. Having a score function such as
the loss function employed during the training, our method estimates the total
variation (TV) distance between scores obtained with a subset of the training
data and the hold-out dataset. With some meta information about the underlying
DP training algorithm, these TV distance values can be converted to
$(\varepsilon,\delta)$-guarantees for any $\delta$. We show that these score
distributions asymptotically give lower bounds for the DP guarantees of the
underlying training algorithm, however, we perform a one-shot estimation for
practicality reasons. We specify conditions that lead to lower bounds for the
DP guarantees with high probability. To estimate the TV distance between the
score distributions, we use a simple density estimation method based on
histograms. We show that the TV distance gives a very close to optimally robust
estimator and has an error rate $\mathcal{O}(k^{-1/3})$, where $k$ is the total
number of samples. Numerical experiments on benchmark datasets illustrate the
effectiveness of our approach and show improvements over baseline methods for
black-box auditing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.04702v1">Marking the Pace: A Blockchain-Enhanced Privacy-Traceable Strategy for
  Federated Recommender Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-06-07T07:21:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhen Cai, Tao Tang, Shuo Yu, Yunpeng Xiao, Feng Xia</p>
    <p><b>Summary:</b> Federated recommender systems have been crucially enhanced through data
sharing and continuous model updates, attributed to the pervasive connectivity
and distributed computing capabilities of Internet of Things (IoT) devices.
Given the sensitivity of IoT data, transparent data processing in data sharing
and model updates is paramount. However, existing methods fall short in tracing
the flow of shared data and the evolution of model updates. Consequently, data
sharing is vulnerable to exploitation by malicious entities, raising
significant data privacy concerns, while excluding data sharing will result in
sub-optimal recommendations. To mitigate these concerns, we present LIBERATE, a
privacy-traceable federated recommender system. We design a blockchain-based
traceability mechanism, ensuring data privacy during data sharing and model
updates. We further enhance privacy protection by incorporating local
differential privacy in user-server communication. Extensive evaluations with
the real-world dataset corroborate LIBERATE's capabilities in ensuring data
privacy during data sharing and model update while maintaining efficiency and
performance. Results underscore blockchain-based traceability mechanism as a
promising solution for privacy-preserving in federated recommender systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.04610v1">Contrastive explainable clustering with differential privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-07T03:37:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dung Nguyen, Ariel Vetzler, Sarit Kraus, Anil Vullikanti</p>
    <p><b>Summary:</b> This paper presents a novel approach in Explainable AI (XAI), integrating
contrastive explanations with differential privacy in clustering methods. For
several basic clustering problems, including $k$-median and $k$-means, we give
efficient differential private contrastive explanations that achieve
essentially the same explanations as those that non-private clustering
explanations can obtain. We define contrastive explanations as the utility
difference between the original clustering utility and utility from clustering
with a specifically fixed centroid. In each contrastive scenario, we designate
a specific data point as the fixed centroid position, enabling us to measure
the impact of this constraint on clustering utility under differential privacy.
Extensive experiments across various datasets show our method's effectiveness
in providing meaningful explanations without significantly compromising data
privacy or clustering utility. This underscores our contribution to
privacy-aware machine learning, demonstrating the feasibility of achieving a
balance between privacy and utility in the explanation of clustering tasks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.04535v1">Tangent differential privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-06-06T22:11:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lexing Ying</p>
    <p><b>Summary:</b> Differential privacy is a framework for protecting the identity of individual
data points in the decision-making process. In this note, we propose a new form
of differential privacy called tangent differential privacy. Compared with the
usual differential privacy that is defined uniformly across data distributions,
tangent differential privacy is tailored towards a specific data distribution
of interest. It also allows for general distribution distances such as total
variation distance and Wasserstein distance. In the case of risk minimization,
we show that entropic regularization guarantees tangent differential privacy
under rather general conditions on the risk function.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.04129v1">LenslessFace: An End-to-End Optimized Lensless System for
  Privacy-Preserving Face Verification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-06-06T14:50:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xin Cai, Hailong Zhang, Chenchen Wang, Wentao Liu, Jinwei Gu, Tianfan Xue</p>
    <p><b>Summary:</b> Lensless cameras, innovatively replacing traditional lenses for ultra-thin,
flat optics, encode light directly onto sensors, producing images that are not
immediately recognizable. This compact, lightweight, and cost-effective imaging
solution offers inherent privacy advantages, making it attractive for
privacy-sensitive applications like face verification. Typical lensless face
verification adopts a two-stage process of reconstruction followed by
verification, incurring privacy risks from reconstructed faces and high
computational costs. This paper presents an end-to-end optimization approach
for privacy-preserving face verification directly on encoded lensless captures,
ensuring that the entire software pipeline remains encoded with no visible
faces as intermediate results. To achieve this, we propose several techniques
to address unique challenges from the lensless setup which precludes
traditional face detection and alignment. Specifically, we propose a face
center alignment scheme, an augmentation curriculum to build robustness against
variations, and a knowledge distillation method to smooth optimization and
enhance performance. Evaluations under both simulation and real environment
demonstrate our method outperforms two-stage lensless verification while
enhancing privacy and efficiency. Project website:
\url{lenslessface.github.io}.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.03820v2">A Survey on Intelligent Internet of Things: Applications, Security,
  Privacy, and Future Directions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-06-06T07:55:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ons Aouedi, Thai-Hoc Vu, Alessio Sacco, Dinh C. Nguyen, Kandaraj Piamrat, Guido Marchetto, Quoc-Viet Pham</p>
    <p><b>Summary:</b> The rapid advances in the Internet of Things (IoT) have promoted a revolution
in communication technology and offered various customer services. Artificial
intelligence (AI) techniques have been exploited to facilitate IoT operations
and maximize their potential in modern application scenarios. In particular,
the convergence of IoT and AI has led to a new networking paradigm called
Intelligent IoT (IIoT), which has the potential to significantly transform
businesses and industrial domains. This paper presents a comprehensive survey
of IIoT by investigating its significant applications in mobile networks, as
well as its associated security and privacy issues. Specifically, we explore
and discuss the roles of IIoT in a wide range of key application domains, from
smart healthcare and smart cities to smart transportation and smart industries.
Through such extensive discussions, we investigate important security issues in
IIoT networks, where network attacks, confidentiality, integrity, and intrusion
are analyzed, along with a discussion of potential countermeasures. Privacy
issues in IIoT networks were also surveyed and discussed, including data,
location, and model privacy leakage. Finally, we outline several key challenges
and highlight potential research directions in this important area.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.03802v1">Continual Counting with Gradual Privacy Expiration</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2024-06-06T07:20:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joel Daniel Andersson, Monika Henzinger, Rasmus Pagh, Teresa Anna Steiner, Jalaj Upadhyay</p>
    <p><b>Summary:</b> Differential privacy with gradual expiration models the setting where data
items arrive in a stream and at a given time $t$ the privacy loss guaranteed
for a data item seen at time $(t-d)$ is $\epsilon g(d)$, where $g$ is a
monotonically non-decreasing function. We study the fundamental
$\textit{continual (binary) counting}$ problem where each data item consists of
a bit, and the algorithm needs to output at each time step the sum of all the
bits streamed so far. For a stream of length $T$ and privacy $\textit{without}$
expiration continual counting is possible with maximum (over all time steps)
additive error $O(\log^2(T)/\varepsilon)$ and the best known lower bound is
$\Omega(\log(T)/\varepsilon)$; closing this gap is a challenging open problem.
  We show that the situation is very different for privacy with gradual
expiration by giving upper and lower bounds for a large set of expiration
functions $g$. Specifically, our algorithm achieves an additive error of $
O(\log(T)/\epsilon)$ for a large set of privacy expiration functions. We also
give a lower bound that shows that if $C$ is the additive error of any
$\epsilon$-DP algorithm for this problem, then the product of $C$ and the
privacy expiration function after $2C$ steps must be
$\Omega(\log(T)/\epsilon)$. Our algorithm matches this lower bound as its
additive error is $O(\log(T)/\epsilon)$, even when $g(2C) = O(1)$.
  Our empirical evaluation shows that we achieve a slowly growing privacy loss
with significantly smaller empirical privacy loss for large values of $d$ than
a natural baseline algorithm.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.03785v1">Count-mean Sketch as an Optimized Framework for Frequency Estimation
  with Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-06T06:55:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mingen Pan</p>
    <p><b>Summary:</b> This paper identifies that a group of state-of-the-art
locally-differentially-private (LDP) algorithms for frequency estimation are
equivalent to the private Count-Mean Sketch (CMS) algorithm with different
parameters. Therefore, we revisit the private CMS, correct errors in the
original CMS paper regarding expectation and variance, modify the CMS
implementation to eliminate existing bias, and explore optimized parameters for
CMS to achieve optimality in reducing the worst-case mean squared error (MSE),
$l_1$ loss, and $l_2$ loss. Additionally, we prove that pairwise-independent
hashing is sufficient for CMS, reducing its communication cost to the logarithm
of the cardinality of all possible values (i.e., a dictionary). As a result,
the aforementioned optimized CMS is proven theoretically and empirically to be
the only algorithm optimized for reducing the worst-case MSE, $l_1$ loss, and
$l_2$ loss when dealing with a very large dictionary. Furthermore, we
demonstrate that randomness is necessary to ensure the correctness of CMS, and
the communication cost of CMS, though low, is unavoidable despite the
randomness being public or private.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.03766v1">Privacy Preserving Semi-Decentralized Mean Estimation over
  Intermittently-Connected Networks</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">  
  <p><b>Published on:</b> 2024-06-06T06:12:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rajarshi Saha, Mohamed Seif, Michal Yemini, Andrea J. Goldsmith, H. Vincent Poor</p>
    <p><b>Summary:</b> We consider the problem of privately estimating the mean of vectors
distributed across different nodes of an unreliable wireless network, where
communications between nodes can fail intermittently. We adopt a
semi-decentralized setup, wherein to mitigate the impact of intermittently
connected links, nodes can collaborate with their neighbors to compute a local
consensus, which they relay to a central server. In such a setting, the
communications between any pair of nodes must ensure that the privacy of the
nodes is rigorously maintained to prevent unauthorized information leakage. We
study the tradeoff between collaborative relaying and privacy leakage due to
the data sharing among nodes and, subsequently, propose PriCER: Private
Collaborative Estimation via Relaying -- a differentially private collaborative
algorithm for mean estimation to optimize this tradeoff. The privacy guarantees
of PriCER arise (i) implicitly, by exploiting the inherent stochasticity of the
flaky network connections, and (ii) explicitly, by adding Gaussian
perturbations to the estimates exchanged by the nodes. Local and central
privacy guarantees are provided against eavesdroppers who can observe different
signals, such as the communications amongst nodes during local consensus and
(possibly multiple) transmissions from the relays to the central server. We
substantiate our theoretical findings with numerical simulations. Our
implementation is available at
https://github.com/rajarshisaha95/private-collaborative-relaying.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.03749v1">NAP^2: A Benchmark for Naturalness and Privacy-Preserving Text Rewriting
  by Learning from Human</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-06-06T05:07:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuo Huang, William MacLean, Xiaoxi Kang, Anqi Wu, Lizhen Qu, Qiongkai Xu, Zhuang Li, Xingliang Yuan, Gholamreza Haffari</p>
    <p><b>Summary:</b> Increasing concerns about privacy leakage issues in academia and industry
arise when employing NLP models from third-party providers to process sensitive
texts. To protect privacy before sending sensitive data to those models, we
suggest sanitizing sensitive text using two common strategies used by humans:
i) deleting sensitive expressions, and ii) obscuring sensitive details by
abstracting them. To explore the issues and develop a tool for text rewriting,
we curate the first corpus, coined NAP^2, through both crowdsourcing and the
use of large language models (LLMs). Compared to the prior works based on
differential privacy, which lead to a sharp drop in information utility and
unnatural texts, the human-inspired approaches result in more natural rewrites
and offer an improved balance between privacy protection and data utility, as
demonstrated by our extensive experiments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.03695v1">FACOS: Enabling Privacy Protection Through Fine-Grained Access Control
  with On-chain and Off-chain System</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-06T02:23:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chao Liu, Cankun Hou, Tianyu Jiang, Jianting Ning, Hui Qiao, Yusen Wu</p>
    <p><b>Summary:</b> Data-driven landscape across finance, government, and healthcare, the
continuous generation of information demands robust solutions for secure
storage, efficient dissemination, and fine-grained access control. Blockchain
technology emerges as a significant tool, offering decentralized storage while
upholding the tenets of data security and accessibility. However, on-chain and
off-chain strategies are still confronted with issues such as untrusted
off-chain data storage, absence of data ownership, limited access control
policy for clients, and a deficiency in data privacy and auditability. To solve
these challenges, we propose a permissioned blockchain-based privacy-preserving
fine-grained access control on-chain and off-chain system, namely FACOS. We
applied three fine-grained access control solutions and comprehensively
analyzed them in different aspects, which provides an intuitive perspective for
system designers and clients to choose the appropriate access control method
for their systems. Compared to similar work that only stores encrypted data in
centralized or non-fault-tolerant IPFS systems, we enhanced off-chain data
storage security and robustness by utilizing a highly efficient and secure
asynchronous Byzantine fault tolerance (BFT) protocol in the off-chain
environment. As each of the clients needs to be verified and authorized before
accessing the data, we involved the Trusted Execution Environment (TEE)-based
solution to verify the credentials of clients. Additionally, our evaluation
results demonstrated that our system offers better scalability and practicality
than other state-of-the-art designs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.03187v1">Ariadne: a Privacy-Preserving Communication Protocol</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-05T12:20:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Antoine Fressancourt, Luigi Iannone, Mael Kerichard</p>
    <p><b>Summary:</b> In this article, we present Ariadne, a privacy-preserving communication
network layer protocol that uses a source routing approach to avoid relying on
trusted third parties. In Ariadne, a source node willing to send anonymized
network traffic to a destination uses a path consisting in nodes with which it
has pre-shared symmetric keys. Temporary keys derived from those pre-shared
keys to protect communication privacy using onion routing techniques, ensuring
session unlinkability for packets following the same path.
  Ariadne enhances previous approaches to preserve communication privacy by
introducing two novelties. First, the source route is encoded in a fixed size,
sequentially encrypted vector of routing information elements, in which the
elements' positions in the vector are pseudo-randomly permuted. Second, the
temporary keys used to process the packets on the path are referenced using
mutually known encrypted patterns. This avoids the use of an explicit key
reference that could be used to de-anonymize the communications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.02797v1">Auditing Privacy Mechanisms via Label Inference Attacks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-04T21:48:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Róbert István Busa-Fekete, Travis Dick, Claudio Gentile, Andrés Muñoz Medina, Adam Smith, Marika Swanberg</p>
    <p><b>Summary:</b> We propose reconstruction advantage measures to audit label privatization
mechanisms. A reconstruction advantage measure quantifies the increase in an
attacker's ability to infer the true label of an unlabeled example when
provided with a private version of the labels in a dataset (e.g., aggregate of
labels from different users or noisy labels output by randomized response),
compared to an attacker that only observes the feature vectors, but may have
prior knowledge of the correlation between features and labels. We consider two
such auditing measures: one additive, and one multiplicative. These incorporate
previous approaches taken in the literature on empirical auditing and
differential privacy. The measures allow us to place a variety of proposed
privatization schemes -- some differentially private, some not -- on the same
footing. We analyze these measures theoretically under a distributional model
which encapsulates reasonable adversarial settings. We also quantify their
behavior empirically on real and simulated prediction tasks. Across a range of
experimental settings, we find that differentially private schemes dominate or
match the privacy-utility tradeoff of more heuristic approaches.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.02794v1">PriME: Privacy-aware Membership profile Estimation in networks</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> 
  <p><b>Published on:</b> 2024-06-04T21:43:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abhinav Chakraborty, Sayak Chatterjee, Sagnik Nandy</p>
    <p><b>Summary:</b> This paper presents a novel approach to estimating community membership
probabilities for network vertices generated by the Degree Corrected Mixed
Membership Stochastic Block Model while preserving individual edge privacy.
Operating within the $\varepsilon$-edge local differential privacy framework,
we introduce an optimal private algorithm based on a symmetric edge flip
mechanism and spectral clustering for accurate estimation of vertex community
memberships. We conduct a comprehensive analysis of the estimation risk and
establish the optimality of our procedure by providing matching lower bounds to
the minimax risk under privacy constraints. To validate our approach, we
demonstrate its performance through numerical simulations and its practical
application to real-world data. This work represents a significant step forward
in balancing accurate community membership estimation with stringent privacy
preservation in network data analysis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.02520v1">Digital Privacy for Migrants: Exploring Current Research Trends and
  Future Prospects</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-06-04T17:41:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sarah Tabassum, Cori Faklaris</p>
    <p><b>Summary:</b> This paper explores digital privacy challenges for migrants, analyzing trends
from 2013 to 2023. Migrants face heightened risks such as government
surveillance and identity theft. Understanding these threats is vital for
raising awareness and guiding research towards effective solutions and policies
to protect migrant digital privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.02463v1">Click Without Compromise: Online Advertising Measurement via Per User
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-04T16:31:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yingtai Xiao, Jian Du, Shikun Zhang, Qiang Yan, Danfeng Zhang, Daniel Kifer</p>
    <p><b>Summary:</b> Online advertising is a cornerstone of the Internet ecosystem, with
advertising measurement playing a crucial role in optimizing efficiency. Ad
measurement entails attributing desired behaviors, such as purchases, to ad
exposures across various platforms, necessitating the collection of user
activities across these platforms. As this practice faces increasing
restrictions due to rising privacy concerns, safeguarding user privacy in this
context is imperative. Our work is the first to formulate the real-world
challenge of advertising measurement systems with real-time reporting of
streaming data in advertising campaigns. We introduce Ads-BPC, a novel
user-level differential privacy protection scheme for advertising measurement
results. This approach optimizes global noise power and results in a
non-identically distributed noise distribution that preserves differential
privacy while enhancing measurement accuracy. Through experiments on both
real-world advertising campaigns and synthetic datasets, Ads-BPC achieves a 25%
to 50% increase in accuracy over existing streaming DP mechanisms applied to
advertising measurement. This highlights our method's effectiveness in
achieving superior accuracy alongside a formal privacy guarantee, thereby
advancing the state-of-the-art in privacy-preserving advertising measurement.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.02424v1">Contextual Dynamic Pricing: Algorithms, Optimality, and Local
  Differential Privacy Constraints</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">  
  <p><b>Published on:</b> 2024-06-04T15:44:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zifeng Zhao, Feiyu Jiang, Yi Yu</p>
    <p><b>Summary:</b> We study the contextual dynamic pricing problem where a firm sells products
to $T$ sequentially arriving consumers that behave according to an unknown
demand model. The firm aims to maximize its revenue, i.e. minimize its regret
over a clairvoyant that knows the model in advance. The demand model is a
generalized linear model (GLM), allowing for a stochastic feature vector in
$\mathbb R^d$ that encodes product and consumer information. We first show that
the optimal regret upper bound is of order $\sqrt{dT}$, up to a logarithmic
factor, improving upon existing upper bounds in the literature by a $\sqrt{d}$
factor. This sharper rate is materialised by two algorithms: a confidence
bound-type (supCB) algorithm and an explore-then-commit (ETC) algorithm. A key
insight of our theoretical result is an intrinsic connection between dynamic
pricing and the contextual multi-armed bandit problem with many arms based on a
careful discretization. We further study contextual dynamic pricing under the
local differential privacy (LDP) constraints. In particular, we propose a
stochastic gradient descent based ETC algorithm that achieves an optimal regret
upper bound of order $d\sqrt{T}/\epsilon$, up to a logarithmic factor, where
$\epsilon>0$ is the privacy parameter. The regret upper bounds with and without
LDP constraints are accompanied by newly constructed minimax lower bounds,
which further characterize the cost of privacy. Extensive numerical experiments
and a real data application on online lending are conducted to illustrate the
efficiency and practical value of the proposed algorithms in dynamic pricing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.03404v1">ST-DPGAN: A Privacy-preserving Framework for Spatiotemporal Data
  Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-04T04:43:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wei Shao, Rongyi Zhu, Cai Yang, Chandra Thapa, Muhammad Ejaz Ahmed, Seyit Camtepe, Rui Zhang, DuYong Kim, Hamid Menouar, Flora D. Salim</p>
    <p><b>Summary:</b> Spatiotemporal data is prevalent in a wide range of edge devices, such as
those used in personal communication and financial transactions. Recent
advancements have sparked a growing interest in integrating spatiotemporal
analysis with large-scale language models. However, spatiotemporal data often
contains sensitive information, making it unsuitable for open third-party
access. To address this challenge, we propose a Graph-GAN-based model for
generating privacy-protected spatiotemporal data. Our approach incorporates
spatial and temporal attention blocks in the discriminator and a spatiotemporal
deconvolution structure in the generator. These enhancements enable efficient
training under Gaussian noise to achieve differential privacy. Extensive
experiments conducted on three real-world spatiotemporal datasets validate the
efficacy of our model. Our method provides a privacy guarantee while
maintaining the data utility. The prediction model trained on our generated
data maintains a competitive performance compared to the model trained on the
original data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.02629v1">SSNet: A Lightweight Multi-Party Computation Scheme for Practical
  Privacy-Preserving Machine Learning Service in the Cloud</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-06-04T00:55:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shijin Duan, Chenghong Wang, Hongwu Peng, Yukui Luo, Wujie Wen, Caiwen Ding, Xiaolin Xu</p>
    <p><b>Summary:</b> As privacy-preserving becomes a pivotal aspect of deep learning (DL)
development, multi-party computation (MPC) has gained prominence for its
efficiency and strong security. However, the practice of current MPC frameworks
is limited, especially when dealing with large neural networks, exemplified by
the prolonged execution time of 25.8 seconds for secure inference on
ResNet-152. The primary challenge lies in the reliance of current MPC
approaches on additive secret sharing, which incurs significant communication
overhead with non-linear operations such as comparisons. Furthermore, additive
sharing suffers from poor scalability on party size. In contrast, the evolving
landscape of MPC necessitates accommodating a larger number of compute parties
and ensuring robust performance against malicious activities or computational
failures.
  In light of these challenges, we propose SSNet, which for the first time,
employs Shamir's secret sharing (SSS) as the backbone of MPC-based ML
framework. We meticulously develop all framework primitives and operations for
secure DL models tailored to seamlessly integrate with the SSS scheme. SSNet
demonstrates the ability to scale up party numbers straightforwardly and embeds
strategies to authenticate the computation correctness without incurring
significant performance overhead. Additionally, SSNet introduces masking
strategies designed to reduce communication overhead associated with non-linear
operations. We conduct comprehensive experimental evaluations on commercial
cloud computing infrastructure from Amazon AWS, as well as across diverse
prevalent DNN models and datasets. SSNet demonstrates a substantial performance
boost, achieving speed-ups ranging from 3x to 14x compared to SOTA MPC
frameworks. Moreover, SSNet also represents the first framework that is
evaluated on a five-party computation setup, in the context of secure DL
inference.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.01811v1">A Game-Theoretic Approach to Privacy-Utility Tradeoff in Sharing Genomic
  Summary Statistics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-03T22:09:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tao Zhang, Rajagopal Venkatesaramani, Rajat K. De, Bradley A. Malin, Yevgeniy Vorobeychik</p>
    <p><b>Summary:</b> The advent of online genomic data-sharing services has sought to enhance the
accessibility of large genomic datasets by allowing queries about genetic
variants, such as summary statistics, aiding care providers in distinguishing
between spurious genomic variations and those with clinical significance.
However, numerous studies have demonstrated that even sharing summary genomic
information exposes individual members of such datasets to a significant
privacy risk due to membership inference attacks. While several approaches have
emerged that reduce privacy risks by adding noise or reducing the amount of
information shared, these typically assume non-adaptive attacks that use
likelihood ratio test (LRT) statistics. We propose a Bayesian game-theoretic
framework for optimal privacy-utility tradeoff in the sharing of genomic
summary statistics. Our first contribution is to prove that a very general
Bayesian attacker model that anchors our game-theoretic approach is more
powerful than the conventional LRT-based threat models in that it induces worse
privacy loss for the defender who is modeled as a von Neumann-Morgenstern (vNM)
decision-maker. We show this to be true even when the attacker uses a
non-informative subjective prior. Next, we present an analytically tractable
approach to compare the Bayesian attacks with arbitrary subjective priors and
the Neyman-Pearson optimal LRT attacks under the Gaussian mechanism common in
differential privacy frameworks. Finally, we propose an approach for
approximating Bayes-Nash equilibria of the game using deep neural network
generators to implicitly represent player mixed strategies. Our experiments
demonstrate that the proposed game-theoretic framework yields both stronger
attacks and stronger defense strategies than the state of the art.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.01394v1">PrivacyRestore: Privacy-Preserving Inference in Large Language Models
  via Privacy Removal and Restoration</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-06-03T14:57:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ziqian Zeng, Jianwei Wang, Zhengdong Lu, Huiping Zhuang, Cen Chen</p>
    <p><b>Summary:</b> The widespread usage of online Large Language Models (LLMs) inference
services has raised significant privacy concerns about the potential exposure
of private information in user inputs to eavesdroppers or untrustworthy service
providers. Existing privacy protection methods for LLMs suffer from
insufficient privacy protection, performance degradation, or severe inference
time overhead. In this paper, we propose PrivacyRestore to protect the privacy
of user inputs during LLM inference. PrivacyRestore directly removes privacy
spans in user inputs and restores privacy information via activation steering
during inference. The privacy spans are encoded as restoration vectors. We
propose Attention-aware Weighted Aggregation (AWA) which aggregates restoration
vectors of all privacy spans in the input into a meta restoration vector. AWA
not only ensures proper representation of all privacy spans but also prevents
attackers from inferring the privacy spans from the meta restoration vector
alone. This meta restoration vector, along with the query with privacy spans
removed, is then sent to the server. The experimental results show that
PrivacyRestore can protect private information while maintaining acceptable
levels of performance and inference efficiency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.01363v1">Privacy in LLM-based Recommendation: Recent Advances and Future
  Directions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2024-06-03T14:31:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sichun Luo, Wei Shao, Yuxuan Yao, Jian Xu, Mingyang Liu, Qintong Li, Bowei He, Maolin Wang, Guanzhi Deng, Hanxu Hou, Xinyi Zhang, Linqi Song</p>
    <p><b>Summary:</b> Nowadays, large language models (LLMs) have been integrated with conventional
recommendation models to improve recommendation performance. However, while
most of the existing works have focused on improving the model performance, the
privacy issue has only received comparatively less attention. In this paper, we
review recent advancements in privacy within LLM-based recommendation,
categorizing them into privacy attacks and protection mechanisms. Additionally,
we highlight several challenges and propose future directions for the community
to address these critical problems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.01085v1">FedAdOb: Privacy-Preserving Federated Deep Learning with Adaptive
  Obfuscation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-06-03T08:12:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hanlin Gu, Jiahuan Luo, Yan Kang, Yuan Yao, Gongxi Zhu, Bowen Li, Lixin Fan, Qiang Yang</p>
    <p><b>Summary:</b> Federated learning (FL) has emerged as a collaborative approach that allows
multiple clients to jointly learn a machine learning model without sharing
their private data. The concern about privacy leakage, albeit demonstrated
under specific conditions, has triggered numerous follow-up research in
designing powerful attacking methods and effective defending mechanisms aiming
to thwart these attacking methods. Nevertheless, privacy-preserving mechanisms
employed in these defending methods invariably lead to compromised model
performances due to a fixed obfuscation applied to private data or gradients.
In this article, we, therefore, propose a novel adaptive obfuscation mechanism,
coined FedAdOb, to protect private data without yielding original model
performances. Technically, FedAdOb utilizes passport-based adaptive obfuscation
to ensure data privacy in both horizontal and vertical federated learning
settings. The privacy-preserving capabilities of FedAdOb, specifically with
regard to private features and labels, are theoretically proven through
Theorems 1 and 2. Furthermore, extensive experimental evaluations conducted on
various datasets and network architectures demonstrate the effectiveness of
FedAdOb by manifesting its superior trade-off between privacy preservation and
model performance, surpassing existing methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.01080v1">No Vandalism: Privacy-Preserving and Byzantine-Robust Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-06-03T07:59:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhibo Xing, Zijian Zhang, Zi'ang Zhang, Jiamou Liu, Liehuang Zhu, Giovanni Russello</p>
    <p><b>Summary:</b> Federated learning allows several clients to train one machine learning model
jointly without sharing private data, providing privacy protection. However,
traditional federated learning is vulnerable to poisoning attacks, which can
not only decrease the model performance, but also implant malicious backdoors.
In addition, direct submission of local model parameters can also lead to the
privacy leakage of the training dataset. In this paper, we aim to build a
privacy-preserving and Byzantine-robust federated learning scheme to provide an
environment with no vandalism (NoV) against attacks from malicious
participants. Specifically, we construct a model filter for poisoned local
models, protecting the global model from data and model poisoning attacks. This
model filter combines zero-knowledge proofs to provide further privacy
protection. Then, we adopt secret sharing to provide verifiable secure
aggregation, removing malicious clients that disrupting the aggregation
process. Our formal analysis proves that NoV can protect data privacy and weed
out Byzantine attackers. Our experiments illustrate that NoV can effectively
address data and model poisoning attacks, including PGD, and outperforms other
related schemes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.00966v1">Guaranteeing Data Privacy in Federated Unlearning with Dynamic User
  Participation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-03T03:39:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ziyao Liu, Yu Jiang, Weifeng Jiang, Jiale Guo, Jun Zhao, Kwok-Yan Lam</p>
    <p><b>Summary:</b> Federated Unlearning (FU) is gaining prominence for its capacity to eliminate
influences of Federated Learning (FL) users' data from trained global FL
models. A straightforward FU method involves removing the unlearned users and
subsequently retraining a new global FL model from scratch with all remaining
users, a process that leads to considerable overhead. To enhance unlearning
efficiency, a widely adopted strategy employs clustering, dividing FL users
into clusters, with each cluster maintaining its own FL model. The final
inference is then determined by aggregating the majority vote from the
inferences of these sub-models. This method confines unlearning processes to
individual clusters for removing a user, thereby enhancing unlearning
efficiency by eliminating the need for participation from all remaining users.
However, current clustering-based FU schemes mainly concentrate on refining
clustering to boost unlearning efficiency but overlook the potential
information leakage from FL users' gradients, a privacy concern that has been
extensively studied. Typically, integrating secure aggregation (SecAgg) schemes
within each cluster can facilitate a privacy-preserving FU. Nevertheless,
crafting a clustering methodology that seamlessly incorporates SecAgg schemes
is challenging, particularly in scenarios involving adversarial users and
dynamic users. In this connection, we systematically explore the integration of
SecAgg protocols within the most widely used federated unlearning scheme, which
is based on clustering, to establish a privacy-preserving FU framework, aimed
at ensuring privacy while effectively managing dynamic user participation.
Comprehensive theoretical assessments and experimental results show that our
proposed scheme achieves comparable unlearning effectiveness, alongside
offering improved privacy protection and resilience in the face of varying user
participation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.00808v1">EchoNet-Synthetic: Privacy-preserving Video Generation for Safe Medical
  Data Sharing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-06-02T17:18:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hadrien Reynaud, Qingjie Meng, Mischa Dombrowski, Arijit Ghosh, Thomas Day, Alberto Gomez, Paul Leeson, Bernhard Kainz</p>
    <p><b>Summary:</b> To make medical datasets accessible without sharing sensitive patient
information, we introduce a novel end-to-end approach for generative
de-identification of dynamic medical imaging data. Until now, generative
methods have faced constraints in terms of fidelity, spatio-temporal coherence,
and the length of generation, failing to capture the complete details of
dataset distributions. We present a model designed to produce high-fidelity,
long and complete data samples with near-real-time efficiency and explore our
approach on a challenging task: generating echocardiogram videos. We develop
our generation method based on diffusion models and introduce a protocol for
medical video dataset anonymization. As an exemplar, we present
EchoNet-Synthetic, a fully synthetic, privacy-compliant echocardiogram dataset
with paired ejection fraction labels. As part of our de-identification
protocol, we evaluate the quality of the generated dataset and propose to use
clinical downstream tasks as a measurement on top of widely used but
potentially biased image quality metrics. Experimental outcomes demonstrate
that EchoNet-Synthetic achieves comparable dataset fidelity to the actual
dataset, effectively supporting the ejection fraction regression task. Code,
weights and dataset are available at
https://github.com/HReynaud/EchoNet-Synthetic.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.02599v1">Privacy-Aware Randomized Quantization via Linear Programming</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-06-01T18:40:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhongteng Cai, Xueru Zhang, Mohammad Mahdi Khalili</p>
    <p><b>Summary:</b> Differential privacy mechanisms such as the Gaussian or Laplace mechanism
have been widely used in data analytics for preserving individual privacy.
However, they are mostly designed for continuous outputs and are unsuitable for
scenarios where discrete values are necessary. Although various quantization
mechanisms were proposed recently to generate discrete outputs under
differential privacy, the outcomes are either biased or have an inferior
accuracy-privacy trade-off. In this paper, we propose a family of quantization
mechanisms that is unbiased and differentially private. It has a high degree of
freedom and we show that some existing mechanisms can be considered as special
cases of ours. To find the optimal mechanism, we formulate a linear
optimization that can be solved efficiently using linear programming tools.
Experiments show that our proposed mechanism can attain a better
privacy-accuracy trade-off compared to baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.00359v1">Location Privacy in B5G/6G: Systematization of Knowledge</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2024-06-01T08:25:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hannah B. Pasandi, Faith Parastar</p>
    <p><b>Summary:</b> As we transition into the era of B5G/6G networks, the promise of seamless,
high-speed connectivity brings unprecedented opportunities and challenges.
Among the most critical concerns is the preservation of location privacy, given
the enhanced precision and pervasive connectivity of these advanced networks.
This paper systematically reviews the state of knowledge on location privacy in
B5G/6G networks, highlighting the architectural advancements and
infrastructural complexities that contribute to increased privacy risks. The
urgency of studying these technologies is underscored by the rapid adoption of
B5G/6G and the growing sophistication of location tracking methods. We evaluate
current and emerging privacy-preserving mechanisms, exploring the implications
of sophisticated tracking methods and the challenges posed by the complex
network infrastructures. Our findings reveal the effectiveness of various
mitigation strategies and emphasize the important role of physical layer
security. Additionally, we propose innovative approaches, including
decentralized authentication systems and the potential of satellite
communications, to enhance location privacy. By addressing these challenges,
this paper provides a comprehensive perspective on preserving user privacy in
the rapidly evolving landscape of modern communication networks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.00256v1">Over-the-Air Collaborative Inference with Feature Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-06-01T01:39:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohamed Seif, Yuqi Nie, Andrea Goldsmith, Vincent Poor</p>
    <p><b>Summary:</b> Collaborative inference in next-generation networks can enhance Artificial
Intelligence (AI) applications, including autonomous driving, personal
identification, and activity classification. This method involves a three-stage
process: a) data acquisition through sensing, b) feature extraction, and c)
feature encoding for transmission. Transmission of the extracted features
entails the potential risk of exposing sensitive personal data. To address this
issue, in this work a new privacy-protecting collaborative inference mechanism
is developed. Under this mechanism, each edge device in the network protects
the privacy of extracted features before transmitting them to a central server
for inference. This mechanism aims to achieve two main objectives while
ensuring effective inference performance: 1) reducing communication overhead,
and 2) maintaining strict privacy guarantees during features transmission.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.00249v1">Privacy Challenges in Meta-Learning: An Investigation on Model-Agnostic
  Meta-Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-01T01:10:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mina Rafiei, Mohammadmahdi Maheri, Hamid R. Rabiee</p>
    <p><b>Summary:</b> Meta-learning involves multiple learners, each dedicated to specific tasks,
collaborating in a data-constrained setting. In current meta-learning methods,
task learners locally learn models from sensitive data, termed support sets.
These task learners subsequently share model-related information, such as
gradients or loss values, which is computed using another part of the data
termed query set, with a meta-learner. The meta-learner employs this
information to update its meta-knowledge. Despite the absence of explicit data
sharing, privacy concerns persist. This paper examines potential data leakage
in a prominent metalearning algorithm, specifically Model-Agnostic
Meta-Learning (MAML). In MAML, gradients are shared between the metalearner and
task-learners. The primary objective is to scrutinize the gradient and the
information it encompasses about the task dataset. Subsequently, we endeavor to
propose membership inference attacks targeting the task dataset containing
support and query sets. Finally, we explore various noise injection methods
designed to safeguard the privacy of task data and thwart potential attacks.
Experimental results demonstrate the effectiveness of these attacks on MAML and
the efficacy of proper noise injection methods in countering them.</p>
  </details>
</div>



<h2>2024-05</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.20914v1">RASE: Efficient Privacy-preserving Data Aggregation against Disclosure
  Attacks for IoTs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-31T15:21:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zuyan Wang, Jun Tao, Dika Zou</p>
    <p><b>Summary:</b> The growing popular awareness of personal privacy raises the following
quandary: what is the new paradigm for collecting and protecting the data
produced by ever-increasing sensor devices. Most previous studies on co-design
of data aggregation and privacy preservation assume that a trusted fusion
center adheres to privacy regimes. Very recent work has taken steps towards
relaxing the assumption by allowing data contributors to locally perturb their
own data. Although these solutions withhold some data content to mitigate
privacy risks, they have been shown to offer insufficient protection against
disclosure attacks. Aiming at providing a more rigorous data safeguard for the
Internet of Things (IoTs), this paper initiates the study of privacy-preserving
data aggregation. We propose a novel paradigm (called RASE), which can be
generalized into a 3-step sequential procedure, noise addition, followed by
random permutation, and then parameter estimation. Specially, we design a
differentially private randomizer, which carefully guides data contributors to
obfuscate the truth. Then, a shuffler is employed to receive the noisy data
from all data contributors. After that, it breaks the correct linkage between
senders and receivers by applying a random permutation. The estimation phase
involves using inaccurate data to calculate an approximate aggregate value.
Extensive simulations are provided to explore the privacy-utility landscape of
our RASE.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.20900v1">Large Language Models: A New Approach for Privacy Policy Analysis at
  Scale</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-05-31T15:12:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> David Rodriguez, Ian Yang, Jose M. Del Alamo, Norman Sadeh</p>
    <p><b>Summary:</b> The number and dynamic nature of web and mobile applications presents
significant challenges for assessing their compliance with data protection
laws. In this context, symbolic and statistical Natural Language Processing
(NLP) techniques have been employed for the automated analysis of these
systems' privacy policies. However, these techniques typically require
labor-intensive and potentially error-prone manually annotated datasets for
training and validation. This research proposes the application of Large
Language Models (LLMs) as an alternative for effectively and efficiently
extracting privacy practices from privacy policies at scale. Particularly, we
leverage well-known LLMs such as ChatGPT and Llama 2, and offer guidance on the
optimal design of prompts, parameters, and models, incorporating advanced
strategies such as few-shot learning. We further illustrate its capability to
detect detailed and varied privacy practices accurately. Using several renowned
datasets in the domain as a benchmark, our evaluation validates its exceptional
performance, achieving an F1 score exceeding 93%. Besides, it does so with
reduced costs, faster processing times, and fewer technical knowledge
requirements. Consequently, we advocate for LLM-based solutions as a sound
alternative to traditional NLP techniques for the automated analysis of privacy
policies at scale.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.20761v1">Share Your Secrets for Privacy! Confidential Forecasting with Vertical
  Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-05-31T12:27:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aditya Shankar, Lydia Y. Chen, Jérémie Decouchant, Dimitra Gkorou, Rihan Hai</p>
    <p><b>Summary:</b> Vertical federated learning (VFL) is a promising area for time series
forecasting in industrial applications, such as predictive maintenance and
machine control. Critical challenges to address in manufacturing include data
privacy and over-fitting on small and noisy datasets during both training and
inference. Additionally, to increase industry adaptability, such forecasting
models must scale well with the number of parties while ensuring strong
convergence and low-tuning complexity. We address those challenges and propose
'Secret-shared Time Series Forecasting with VFL' (STV), a novel framework that
exhibits the following key features: i) a privacy-preserving algorithm for
forecasting with SARIMAX and autoregressive trees on vertically partitioned
data; ii) serverless forecasting using secret sharing and multi-party
computation; iii) novel N-party algorithms for matrix multiplication and
inverse operations for direct parameter optimization, giving strong convergence
with minimal hyperparameter tuning complexity. We conduct evaluations on six
representative datasets from public and industry-specific contexts. Our results
demonstrate that STV's forecasting accuracy is comparable to those of
centralized approaches. They also show that our direct optimization can
outperform centralized methods, which include state-of-the-art diffusion models
and long-short-term memory, by 23.81% on forecasting accuracy. We also conduct
a scalability analysis by examining the communication costs of direct and
iterative optimization to navigate the choice between the two. Code and
appendix are available: https://github.com/adis98/STV</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.20681v1">No Free Lunch Theorem for Privacy-Preserving LLM Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-05-31T08:22:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaojin Zhang, Yulin Fei, Yan Kang, Wei Chen, Lixin Fan, Hai Jin, Qiang Yang</p>
    <p><b>Summary:</b> Individuals and businesses have been significantly benefited by Large
Language Models (LLMs) including PaLM, Gemini and ChatGPT in various ways. For
example, LLMs enhance productivity, reduce costs, and enable us to focus on
more valuable tasks. Furthermore, LLMs possess the capacity to sift through
extensive datasets, uncover underlying patterns, and furnish critical insights
that propel the frontiers of technology and science. However, LLMs also pose
privacy concerns. Users' interactions with LLMs may expose their sensitive
personal or company information. A lack of robust privacy safeguards and legal
frameworks could permit the unwarranted intrusion or improper handling of
individual data, thereby risking infringements of privacy and the theft of
personal identities. To ensure privacy, it is essential to minimize the
dependency between shared prompts and private information. Various
randomization approaches have been proposed to protect prompts' privacy, but
they may incur utility loss compared to unprotected LLMs prompting. Therefore,
it is essential to evaluate the balance between the risk of privacy leakage and
loss of utility when conducting effective protection mechanisms. The current
study develops a framework for inferring privacy-protected Large Language
Models (LLMs) and lays down a solid theoretical basis for examining the
interplay between privacy preservation and utility. The core insight is
encapsulated within a theorem that is called as the NFL (abbreviation of the
word No-Free-Lunch) Theorem.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.20576v1">Federated Graph Analytics with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-31T02:09:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shang Liu, Yang Cao, Takao Murakami, Weiran Liu, Seng Pei Liew, Tsubasa Takahashi, Jinfei Liu, Masatoshi Yoshikawa</p>
    <p><b>Summary:</b> Collaborative graph analysis across multiple institutions is becoming
increasingly popular. Realistic examples include social network analysis across
various social platforms, financial transaction analysis across multiple banks,
and analyzing the transmission of infectious diseases across multiple
hospitals. We define the federated graph analytics, a new problem for
collaborative graph analytics under differential privacy. Although
differentially private graph analysis has been widely studied, it fails to
achieve a good tradeoff between utility and privacy in federated scenarios, due
to the limited view of local clients and overlapping information across
multiple subgraphs. Motivated by this, we first propose a federated graph
analytic framework, named FEAT, which enables arbitrary downstream common graph
statistics while preserving individual privacy. Furthermore, we introduce an
optimized framework based on our proposed degree-based partition algorithm,
called FEAT+, which improves the overall utility by leveraging the true local
subgraphs. Finally, extensive experiments demonstrate that our FEAT and FEAT+
significantly outperform the baseline approach by approximately one and four
orders of magnitude, respectively.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.00073v1">A Novel Review of Stability Techniques for Improved Privacy-Preserving
  Machine Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-31T00:30:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Coleman DuPlessie, Aidan Gao</p>
    <p><b>Summary:</b> Machine learning models have recently enjoyed a significant increase in size
and popularity. However, this growth has created concerns about dataset
privacy. To counteract data leakage, various privacy frameworks guarantee that
the output of machine learning models does not compromise their training data.
However, this privatization comes at a cost by adding random noise to the
training process, which reduces model performance. By making models more
resistant to small changes in input and thus more stable, the necessary amount
of noise can be decreased while still protecting privacy. This paper
investigates various techniques to enhance stability, thereby minimizing the
negative effects of privatization in machine learning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.20483v1">Hiding Your Awful Online Choices Made More Efficient and Secure: A New
  Privacy-Aware Recommender System</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-30T21:08:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shibam Mukherjee, Roman Walch, Fredrik Meisingseth, Elisabeth Lex, Christian Rechberger</p>
    <p><b>Summary:</b> Recommender systems are an integral part of online platforms that recommend
new content to users with similar interests. However, they demand a
considerable amount of user activity data where, if the data is not adequately
protected, constitute a critical threat to the user privacy. Privacy-aware
recommender systems enable protection of such sensitive user data while still
maintaining a similar recommendation accuracy compared to the traditional
non-private recommender systems. However, at present, the current privacy-aware
recommender systems suffer from a significant trade-off between privacy and
computational efficiency. For instance, it is well known that architectures
that rely purely on cryptographic primitives offer the most robust privacy
guarantees, however, they suffer from substantial computational and network
overhead. Thus, it is crucial to improve this trade-off for better performance.
This paper presents a novel privacy-aware recommender system that combines
privacy-aware machine learning algorithms for practical scalability and
efficiency with cryptographic primitives like Homomorphic Encryption and
Multi-Party Computation - without assumptions like trusted-party or secure
hardware - for solid privacy guarantees. Experiments on standard benchmark
datasets show that our approach results in time and memory gains by three
orders of magnitude compared to using cryptographic primitives in a standalone
for constructing a privacy-aware recommender system. Furthermore, for the first
time our method makes it feasible to compute private recommendations for
datasets containing 100 million entries, even on memory-constrained low-power
SOC (System on Chip) devices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.20405v1">Private Mean Estimation with Person-Level Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">  
  <p><b>Published on:</b> 2024-05-30T18:20:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sushant Agarwal, Gautam Kamath, Mahbod Majid, Argyris Mouzakis, Rose Silver, Jonathan Ullman</p>
    <p><b>Summary:</b> We study differentially private (DP) mean estimation in the case where each
person holds multiple samples. Commonly referred to as the "user-level"
setting, DP here requires the usual notion of distributional stability when all
of a person's datapoints can be modified. Informally, if $n$ people each have
$m$ samples from an unknown $d$-dimensional distribution with bounded $k$-th
moments, we show that
  \[n = \tilde \Theta\left(\frac{d}{\alpha^2 m} + \frac{d }{ \alpha m^{1/2}
\varepsilon} + \frac{d}{\alpha^{k/(k-1)} m \varepsilon} +
\frac{d}{\varepsilon}\right)\]
  people are necessary and sufficient to estimate the mean up to distance
$\alpha$ in $\ell_2$-norm under $\varepsilon$-differential privacy (and its
common relaxations). In the multivariate setting, we give computationally
efficient algorithms under approximate DP (with slightly degraded sample
complexity) and computationally inefficient algorithms under pure DP, and our
nearly matching lower bounds hold for the most permissive case of approximate
DP. Our computationally efficient estimators are based on the well known
noisy-clipped-mean approach, but the analysis for our setting requires new
bounds on the tails of sums of independent, vector-valued, bounded-moments
random variables, and a new argument for bounding the bias introduced by
clipping.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.19831v2">Just Rewrite It Again: A Post-Processing Method for Enhanced Semantic
  Similarity and Privacy Preservation of Differentially Private Rewritten Text</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-05-30T08:41:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stephen Meisenbacher, Florian Matthes</p>
    <p><b>Summary:</b> The study of Differential Privacy (DP) in Natural Language Processing often
views the task of text privatization as a $\textit{rewriting}$ task, in which
sensitive input texts are rewritten to hide explicit or implicit private
information. In order to evaluate the privacy-preserving capabilities of a DP
text rewriting mechanism, $\textit{empirical privacy}$ tests are frequently
employed. In these tests, an adversary is modeled, who aims to infer sensitive
information (e.g., gender) about the author behind a (privatized) text. Looking
to improve the empirical protections provided by DP rewriting methods, we
propose a simple post-processing method based on the goal of aligning rewritten
texts with their original counterparts, where DP rewritten texts are rewritten
$\textit{again}$. Our results show that such an approach not only produces
outputs that are more semantically reminiscent of the original inputs, but also
texts which score on average better in empirical privacy evaluations.
Therefore, our approach raises the bar for DP rewriting methods in their
empirical privacy evaluations, providing an extra layer of protection against
malicious adversaries.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.20785v1">How the Future Works at SOUPS: Analyzing Future Work Statements and
  Their Impact on Usable Security and Privacy Research</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-05-30T07:07:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jacques Suray, Jan H. Klemmer, Juliane Schmüser, Sascha Fahl</p>
    <p><b>Summary:</b> Extending knowledge by identifying and investigating valuable research
questions and problems is a core function of research. Research publications
often suggest avenues for future work to extend and build upon their results.
Considering these suggestions can contribute to developing research ideas that
build upon previous work and produce results that tie into existing knowledge.
Usable security and privacy researchers commonly add future work statements to
their publications. However, our community lacks an in-depth understanding of
their prevalence, quality, and impact on future research.
  Our work aims to address this gap in the research literature. We reviewed all
27 papers from the 2019 SOUPS proceedings and analyzed their future work
statements. Additionally, we analyzed 978 publications that cite any paper from
SOUPS 2019 proceedings to assess their future work statements' impact. We find
that most papers from the SOUPS 2019 proceedings include future work
statements. However, they are often unspecific or ambiguous, and not always
easy to find. Therefore, the citing publications often matched the future work
statements' content thematically, but rarely explicitly acknowledged them,
indicating a limited impact. We conclude with recommendations for the usable
security and privacy community to improve the utility of future work statements
by making them more tangible and actionable, and avenues for future work.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.19272v1">Mitigating Disparate Impact of Differential Privacy in Federated
  Learning through Robust Clustering</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-05-29T17:03:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Saber Malekmohammadi, Afaf Taik, Golnoosh Farnadi</p>
    <p><b>Summary:</b> Federated Learning (FL) is a decentralized machine learning (ML) approach
that keeps data localized and often incorporates Differential Privacy (DP) to
enhance privacy guarantees. Similar to previous work on DP in ML, we observed
that differentially private federated learning (DPFL) introduces performance
disparities, particularly affecting minority groups. Recent work has attempted
to address performance fairness in vanilla FL through clustering, but this
method remains sensitive and prone to errors, which are further exacerbated by
the DP noise in DPFL. To fill this gap, in this paper, we propose a novel
clustered DPFL algorithm designed to effectively identify clients' clusters in
highly heterogeneous settings while maintaining high accuracy with DP
guarantees. To this end, we propose to cluster clients based on both their
model updates and training loss values. Our proposed approach also addresses
the server's uncertainties in clustering clients' model updates by employing
larger batch sizes along with Gaussian Mixture Model (GMM) to alleviate the
impact of noise and potential clustering errors, especially in
privacy-sensitive scenarios. We provide theoretical analysis of the
effectiveness of our proposed approach. We also extensively evaluate our
approach across diverse data distributions and privacy budgets and show its
effectiveness in mitigating the disparate impact of DP in FL settings with a
small computational cost.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.19259v1">A Privacy-Preserving Graph Encryption Scheme Based on Oblivious RAM</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-29T16:47:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Seyni Kane, Anis Bkakria</p>
    <p><b>Summary:</b> Graph encryption schemes play a crucial role in facilitating secure queries
on encrypted graphs hosted on untrusted servers. With applications spanning
navigation systems, network topology, and social networks, the need to
safeguard sensitive data becomes paramount. Existing graph encryption methods,
however, exhibit vulnerabilities by inadvertently revealing aspects of the
graph structure and query patterns, posing threats to security and privacy. In
response, we propose a novel graph encryption scheme designed to mitigate
access pattern and query pattern leakage through the integration of oblivious
RAM and trusted execution environment techniques, exemplified by a Trusted
Execution Environment (TEE). Our solution establishes two key security
objectives: (1) ensuring that adversaries, when presented with an encrypted
graph, remain oblivious to any information regarding the underlying graph, and
(2) achieving query indistinguishability by concealing access patterns.
Additionally, we conducted experimentation to evaluate the efficiency of the
proposed schemes when dealing with real-world location navigation services.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.19187v1">Algorithmic Transparency and Participation through the Handoff Lens:
  Lessons Learned from the U.S. Census Bureau's Adoption of Differential
  Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-05-29T15:29:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Amina A. Abdu, Lauren M. Chambers, Deirdre K. Mulligan, Abigail Z. Jacobs</p>
    <p><b>Summary:</b> Emerging discussions on the responsible government use of algorithmic
technologies propose transparency and public participation as key mechanisms
for preserving accountability and trust. But in practice, the adoption and use
of any technology shifts the social, organizational, and political context in
which it is embedded. Therefore translating transparency and participation
efforts into meaningful, effective accountability must take into account these
shifts. We adopt two theoretical frames, Mulligan and Nissenbaum's handoff
model and Star and Griesemer's boundary objects, to reveal such shifts during
the U.S. Census Bureau's adoption of differential privacy (DP) in its updated
disclosure avoidance system (DAS) for the 2020 census. This update preserved
(and arguably strengthened) the confidentiality protections that the Bureau is
mandated to uphold, and the Bureau engaged in a range of activities to
facilitate public understanding of and participation in the system design
process. Using publicly available documents concerning the Census'
implementation of DP, this case study seeks to expand our understanding of how
technical shifts implicate values, how such shifts can afford (or fail to
afford) greater transparency and participation in system design, and the
importance of localized expertise throughout. We present three lessons from
this case study toward grounding understandings of algorithmic transparency and
participation: (1) efforts towards transparency and participation in
algorithmic governance must center values and policy decisions, not just
technical design decisions; (2) the handoff model is a useful tool for
revealing how such values may be cloaked beneath technical decisions; and (3)
boundary objects alone cannot bridge distant communities without trusted
experts traveling alongside to broker their adoption.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.18888v1">Proactive Load-Shaping Strategies with Privacy-Cost Trade-offs in
  Residential Households based on Deep Reinforcement Learning</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2024-05-29T08:45:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruichang Zhang, Youcheng Sun, Mustafa A. Mustafa</p>
    <p><b>Summary:</b> Smart meters play a crucial role in enhancing energy management and
efficiency, but they raise significant privacy concerns by potentially
revealing detailed user behaviors through energy consumption patterns. Recent
scholarly efforts have focused on developing battery-aided load-shaping
techniques to protect user privacy while balancing costs. This paper proposes a
novel deep reinforcement learning-based load-shaping algorithm (PLS-DQN)
designed to protect user privacy by proactively creating artificial load
signatures that mislead potential attackers. We evaluate our proposed algorithm
against a non-intrusive load monitoring (NILM) adversary. The results
demonstrate that our approach not only effectively conceals real energy usage
patterns but also outperforms state-of-the-art methods in enhancing user
privacy while maintaining cost efficiency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.18878v1">Privacy Preserving Data Imputation via Multi-party Computation for
  Medical Applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-05-29T08:36:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Julia Jentsch, Ali Burak Ünal, Şeyma Selcan Mağara, Mete Akgün</p>
    <p><b>Summary:</b> Handling missing data is crucial in machine learning, but many datasets
contain gaps due to errors or non-response. Unlike traditional methods such as
listwise deletion, which are simple but inadequate, the literature offers more
sophisticated and effective methods, thereby improving sample size and
accuracy. However, these methods require accessing the whole dataset, which
contradicts the privacy regulations when the data is distributed among multiple
sources. Especially in the medical and healthcare domain, such access reveals
sensitive information about patients. This study addresses privacy-preserving
imputation methods for sensitive data using secure multi-party computation,
enabling secure computations without revealing any party's sensitive
information. In this study, we realized the mean, median, regression, and kNN
imputation methods in a privacy-preserving way. We specifically target the
medical and healthcare domains considering the significance of protection of
the patient data, showcasing our methods on a diabetes dataset. Experiments on
the diabetes dataset validated the correctness of our privacy-preserving
imputation methods, yielding the largest error around $3 \times 10^{-3}$,
closely matching plaintext methods. We also analyzed the scalability of our
methods to varying numbers of samples, showing their applicability to
real-world healthcare problems. Our analysis demonstrated that all our methods
scale linearly with the number of samples. Except for kNN, the runtime of all
our methods indicates that they can be utilized for large datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.18802v1">Enhancing Security and Privacy in Federated Learning using Update
  Digests and Voting-Based Defense</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-05-29T06:46:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenjie Li, Kai Fan, Jingyuan Zhang, Hui Li, Wei Yang Bryan Lim, Qiang Yang</p>
    <p><b>Summary:</b> Federated Learning (FL) is a promising privacy-preserving machine learning
paradigm that allows data owners to collaboratively train models while keeping
their data localized. Despite its potential, FL faces challenges related to the
trustworthiness of both clients and servers, especially in the presence of
curious or malicious adversaries. In this paper, we introduce a novel framework
named \underline{\textbf{F}}ederated \underline{\textbf{L}}earning with
\underline{\textbf{U}}pdate \underline{\textbf{D}}igest (FLUD), which addresses
the critical issues of privacy preservation and resistance to Byzantine attacks
within distributed learning environments. FLUD utilizes an innovative approach,
the $\mathsf{LinfSample}$ method, allowing clients to compute the $l_{\infty}$
norm across sliding windows of updates as an update digest. This digest enables
the server to calculate a shared distance matrix, significantly reducing the
overhead associated with Secure Multi-Party Computation (SMPC) by three orders
of magnitude while effectively distinguishing between benign and malicious
updates. Additionally, FLUD integrates a privacy-preserving, voting-based
defense mechanism that employs optimized SMPC protocols to minimize
communication rounds. Our comprehensive experiments demonstrate FLUD's
effectiveness in countering Byzantine adversaries while incurring low
communication and runtime overhead. FLUD offers a scalable framework for secure
and reliable FL in distributed environments, facilitating its application in
scenarios requiring robust data management and security.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.18534v1">Individualized Privacy Accounting via Subsampling with Applications in
  Combinatorial Optimization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-28T19:02:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Badih Ghazi, Pritish Kamath, Ravi Kumar, Pasin Manurangsi, Adam Sealfon</p>
    <p><b>Summary:</b> In this work, we give a new technique for analyzing individualized privacy
accounting via the following simple observation: if an algorithm is one-sided
add-DP, then its subsampled variant satisfies two-sided DP. From this, we
obtain several improved algorithms for private combinatorial optimization
problems, including decomposable submodular maximization and set cover. Our
error guarantees are asymptotically tight and our algorithm satisfies pure-DP
while previously known algorithms (Gupta et al., 2010; Chaturvedi et al., 2021)
are approximate-DP. We also show an application of our technique beyond
combinatorial optimization by giving a pure-DP algorithm for the shifting heavy
hitter problem in a stream; previously, only an approximateDP algorithm was
known (Kaplan et al., 2021; Cohen & Lyu, 2023).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.18430v1">Feasibility of Privacy-Preserving Entity Resolution on Confidential
  Healthcare Datasets Using Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computational Engineering, Finance, and Science-5BC0EB">
  <p><b>Published on:</b> 2024-05-28T17:59:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yixiang Yao, Joseph Cecil, Praveen Angyan, Neil Bahroos, Srivatsan Ravi</p>
    <p><b>Summary:</b> Patient datasets contain confidential information which is protected by laws
and regulations such as HIPAA and GDPR. Ensuring comprehensive patient
information necessitates privacy-preserving entity resolution (PPER), which
identifies identical patient entities across multiple databases from different
healthcare organizations while maintaining data privacy. Existing methods often
lack cryptographic security or are computationally impractical for real-world
datasets. We introduce a PPER pipeline based on AMPPERE, a secure abstract
computation model utilizing cryptographic tools like homomorphic encryption.
Our tailored approach incorporates extensive parallelization techniques and
optimal parameters specifically for patient datasets. Experimental results
demonstrate the proposed method's effectiveness in terms of accuracy and
efficiency compared to various baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.17971v1">A Qualitative Analysis Framework for mHealth Privacy Practices</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-05-28T08:57:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Thomas Cory, Wolf Rieder, Thu-My Huynh</p>
    <p><b>Summary:</b> Mobile Health (mHealth) applications have become a crucial part of health
monitoring and management. However, the proliferation of these applications has
also raised concerns over the privacy and security of Personally Identifiable
Information and Protected Health Information. Addressing these concerns, this
paper introduces a novel framework for the qualitative evaluation of privacy
practices in mHealth apps, particularly focusing on the handling and
transmission of sensitive user data. Our investigation encompasses an analysis
of 152 leading mHealth apps on the Android platform, leveraging the proposed
framework to provide a multifaceted view of their data processing activities.
Despite stringent regulations like the General Data Protection Regulation in
the European Union and the Health Insurance Portability and Accountability Act
in the United States, our findings indicate persistent issues with negligence
and misuse of sensitive user information. We uncover significant instances of
health information leakage to third-party trackers and a widespread neglect of
privacy-by-design and transparency principles. Our research underscores the
critical need for stricter enforcement of data protection laws and sets a
foundation for future efforts aimed at enhancing user privacy within the
mHealth ecosystem.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.20769v1">Avoiding Pitfalls for Privacy Accounting of Subsampled Mechanisms under
  Composition</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2024-05-27T20:30:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Christian Janos Lebeda, Matthew Regehr, Gautam Kamath, Thomas Steinke</p>
    <p><b>Summary:</b> We consider the problem of computing tight privacy guarantees for the
composition of subsampled differentially private mechanisms. Recent algorithms
can numerically compute the privacy parameters to arbitrary precision but must
be carefully applied.
  Our main contribution is to address two common points of confusion. First,
some privacy accountants assume that the privacy guarantees for the composition
of a subsampled mechanism are determined by self-composing the worst-case
datasets for the uncomposed mechanism. We show that this is not true in
general. Second, Poisson subsampling is sometimes assumed to have similar
privacy guarantees compared to sampling without replacement. We show that the
privacy guarantees may in fact differ significantly between the two sampling
schemes. In particular, we give an example of hyperparameters that result in
$\varepsilon \approx 1$ for Poisson subsampling and $\varepsilon > 10$ for
sampling without replacement. This occurs for some parameters that could
realistically be chosen for DP-SGD.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.17423v1">Privacy-Aware Visual Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-05-27T17:59:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Laurens Samson, Nimrod Barazani, Sennay Ghebreab, Yuki M. Asano</p>
    <p><b>Summary:</b> This paper aims to advance our understanding of how Visual Language Models
(VLMs) handle privacy-sensitive information, a crucial concern as these
technologies become integral to everyday life. To this end, we introduce a new
benchmark PrivBench, which contains images from 8 sensitive categories such as
passports, or fingerprints. We evaluate 10 state-of-the-art VLMs on this
benchmark and observe a generally limited understanding of privacy,
highlighting a significant area for model improvement. Based on this we
introduce PrivTune, a new instruction-tuning dataset aimed at equipping VLMs
with knowledge about visual privacy. By tuning two pretrained VLMs, TinyLLaVa
and MiniGPT-v2, on this small dataset, we achieve strong gains in their ability
to recognize sensitive content, outperforming even GPT4-V. At the same time, we
show that privacy-tuning only minimally affects the VLMs performance on
standard benchmarks such as VQA. Overall, this paper lays out a crucial
challenge for making VLMs effective in handling real-world data safely and
provides a simple recipe that takes the first step towards building
privacy-aware VLMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.17079v1">Learning with User-Level Local Differential Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-05-27T11:52:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Puning Zhao, Li Shen, Rongfei Fan, Qingming Li, Huiwen Wu, Jiafei Wu, Zhe Liu</p>
    <p><b>Summary:</b> User-level privacy is important in distributed systems. Previous research
primarily focuses on the central model, while the local models have received
much less attention. Under the central model, user-level DP is strictly
stronger than the item-level one. However, under the local model, the
relationship between user-level and item-level LDP becomes more complex, thus
the analysis is crucially different. In this paper, we first analyze the mean
estimation problem and then apply it to stochastic optimization,
classification, and regression. In particular, we propose adaptive strategies
to achieve optimal performance at all privacy levels. Moreover, we also obtain
information-theoretic lower bounds, which show that the proposed methods are
minimax optimal up to logarithmic factors. Unlike the central DP model, where
user-level DP always leads to slower convergence, our result shows that under
the local model, the convergence rates are nearly the same between user-level
and item-level cases for distributions with bounded support. For heavy-tailed
distributions, the user-level rate is even faster than the item-level one.</p>
  </details>
</div>

