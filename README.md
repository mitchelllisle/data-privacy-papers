
<h2>2025-07</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.08412v1">Enforcing Speech Content Privacy in Environmental Sound Recordings using
  Segment-wise Waveform Reversal</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> 
  <p><b>Published on:</b> 2025-07-11T08:48:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Modan Tailleur, Mathieu Lagrange, Pierre Aumond, Vincent Tourre</p>
    <p><b>Summary:</b> Environmental sound recordings often contain intelligible speech, raising
privacy concerns that limit analysis, sharing and reuse of data. In this paper,
we introduce a method that renders speech unintelligible while preserving both
the integrity of the acoustic scene, and the overall audio quality. Our
approach involves reversing waveform segments to distort speech content. This
process is enhanced through a voice activity detection and speech separation
pipeline, which allows for more precise targeting of speech.
  In order to demonstrate the effectivness of the proposed approach, we
consider a three-part evaluation protocol that assesses: 1) speech
intelligibility using Word Error Rate (WER), 2) sound sources detectability
using Sound source Classification Accuracy-Drop (SCAD) from a widely used
pre-trained model, and 3) audio quality using the Fr\'echet Audio Distance
(FAD), computed with our reference dataset that contains unaltered speech.
Experiments on this simulated evaluation dataset, which consists of linear
mixtures of speech and environmental sound scenes, show that our method
achieves satisfactory speech intelligibility reduction (97.9% WER), minimal
degradation of the sound sources detectability (2.7% SCAD), and high perceptual
quality (FAD of 1.40). An ablation study further highlights the contribution of
each component of the pipeline. We also show that incorporating random splicing
to our speech content privacy enforcement method can enhance the algorithm's
robustness to attempt to recover the clean speech, at a slight cost of audio
quality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.08158v1">Beyond the Worst Case: Extending Differential Privacy Guarantees to
  Realistic Adversaries</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-10T20:36:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marika Swanberg, Meenatchi Sundaram Muthu Selva Annamalai, Jamie Hayes, Borja Balle, Adam Smith</p>
    <p><b>Summary:</b> Differential Privacy (DP) is a family of definitions that bound the
worst-case privacy leakage of a mechanism. One important feature of the
worst-case DP guarantee is it naturally implies protections against adversaries
with less prior information, more sophisticated attack goals, and complex
measures of a successful attack. However, the analytical tradeoffs between the
adversarial model and the privacy protections conferred by DP are not well
understood thus far. To that end, this work sheds light on what the worst-case
guarantee of DP implies about the success of attackers that are more
representative of real-world privacy risks.
  In this paper, we present a single flexible framework that generalizes and
extends the patchwork of bounds on DP mechanisms found in prior work. Our
framework allows us to compute high-probability guarantees for DP mechanisms on
a large family of natural attack settings that previous bounds do not capture.
One class of such settings is the approximate reconstruction of multiple
individuals' data, such as inferring nearly entire columns of a tabular data
set from noisy marginals and extracting sensitive information from DP-trained
language models.
  We conduct two empirical case studies to illustrate the versatility of our
bounds and compare them to the success of state-of-the-art attacks.
Specifically, we study attacks that extract non-uniform PII from a DP-trained
language model, as well as multi-column reconstruction attacks where the
adversary has access to some columns in the clear and attempts to reconstruct
the remaining columns for each person's record. We find that the absolute
privacy risk of attacking non-uniform data is highly dependent on the
adversary's prior probability of success. Our high probability bounds give us a
nuanced understanding of the privacy leakage of DP mechanisms in a variety of
previously understudied attack settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.07700v1">Rethinking the Privacy of Text Embeddings: A Reproducibility Study of
  "Text Embeddings Reveal (Almost) As Much As Text"</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2025-07-10T12:27:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dominykas Seputis, Yongkang Li, Karsten Langerak, Serghei Mihailov</p>
    <p><b>Summary:</b> Text embeddings are fundamental to many natural language processing (NLP)
tasks, extensively applied in domains such as recommendation systems and
information retrieval (IR). Traditionally, transmitting embeddings instead of
raw text has been seen as privacy-preserving. However, recent methods such as
Vec2Text challenge this assumption by demonstrating that controlled decoding
can successfully reconstruct original texts from black-box embeddings. The
unexpectedly strong results reported by Vec2Text motivated us to conduct
further verification, particularly considering the typically non-intuitive and
opaque structure of high-dimensional embedding spaces. In this work, we
reproduce the Vec2Text framework and evaluate it from two perspectives: (1)
validating the original claims, and (2) extending the study through targeted
experiments. First, we successfully replicate the original key results in both
in-domain and out-of-domain settings, with only minor discrepancies arising due
to missing artifacts, such as model checkpoints and dataset splits.
Furthermore, we extend the study by conducting a parameter sensitivity
analysis, evaluating the feasibility of reconstructing sensitive inputs (e.g.,
passwords), and exploring embedding quantization as a lightweight privacy
defense. Our results show that Vec2Text is effective under ideal conditions,
capable of reconstructing even password-like sequences that lack clear
semantics. However, we identify key limitations, including its sensitivity to
input sequence length. We also find that Gaussian noise and quantization
techniques can mitigate the privacy risks posed by Vec2Text, with quantization
offering a simpler and more widely applicable solution. Our findings emphasize
the need for caution in using text embeddings and highlight the importance of
further research into robust defense mechanisms for NLP systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.07565v1">Secure Cooperative Gradient Coding: Optimality, Reliability, and Global
  Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2025-07-10T09:10:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shudi Weng</p>
    <p><b>Summary:</b> This paper studies privacy-sensitive federated learning (FL) with unreliable
communication, focusing on secure aggregation and straggler mitigation. While
secure aggregation cryptographically reconstructs the global model without
exposing client updates, random link failures disrupt its key coordination,
degrading model accuracy. Moreover, unreliable communication can lead to
objective inconsistency, causing the global model to converge to arbitrary,
sub-optimal points far from the intended optimum. This paper proposes Secure
Cooperative Gradient Coding (SecCoGC), a practical solution that achieves
secure aggregation with arbitrarily strong privacy guarantees and robust
straggler mitigation under unreliable communication. SecCoGC operates natively
in the real field, making it directly applicable to practical deployments. To
ensure equitable privacy protection across clients, we further introduce
Fair-SecCoGC, an extension that enforces fairness in the level of privacy
offered to all users. To conclude, this paper formally formulates the problem
of secure aggregation in the real field and presents both general and
computationally efficient key construction methods. Moreover, it provides a
comprehensive privacy analysis under Local Mutual Information Privacy (LMIP)
and Local Differential Privacy (LDP) across all protocol layers. Robustness and
convergence properties are also rigorously analyzed. Finally, extensive
simulations are performed across diverse network conditions and benchmark
datasets to validate the effectiveness of the proposed methods. The results
show that SecCoGC achieves strong robustness to unreliable communication under
arbitrarily strong privacy guarantees. It outperforms existing
privacy-preserving methods with performance gains of up to 20\%-70\%.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.08050v1">An Enhanced Privacy-preserving Federated Few-shot Learning Framework for
  Respiratory Disease Diagnosis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-10T07:47:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ming Wang, Zhaoyang Duan, Dong Xue, Fangzhou Liu, Zhongheng Zhang</p>
    <p><b>Summary:</b> The labor-intensive nature of medical data annotation presents a significant
challenge for respiratory disease diagnosis, resulting in a scarcity of
high-quality labeled datasets in resource-constrained settings. Moreover,
patient privacy concerns complicate the direct sharing of local medical data
across institutions, and existing centralized data-driven approaches, which
rely on amounts of available data, often compromise data privacy. This study
proposes a federated few-shot learning framework with privacy-preserving
mechanisms to address the issues of limited labeled data and privacy protection
in diagnosing respiratory diseases. In particular, a meta-stochastic gradient
descent algorithm is proposed to mitigate the overfitting problem that arises
from insufficient data when employing traditional gradient descent methods for
neural network training. Furthermore, to ensure data privacy against gradient
leakage, differential privacy noise from a standard Gaussian distribution is
integrated into the gradients during the training of private models with local
data, thereby preventing the reconstruction of medical images. Given the
impracticality of centralizing respiratory disease data dispersed across
various medical institutions, a weighted average algorithm is employed to
aggregate local diagnostic models from different clients, enhancing the
adaptability of a model across diverse scenarios. Experimental results show
that the proposed method yields compelling results with the implementation of
differential privacy, while effectively diagnosing respiratory diseases using
data from different structures, categories, and distributions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.07320v1">Optimizing Communication and Device Clustering for Clustered Federated
  Learning with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-07-09T22:44:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dongyu Wei, Xiaoren Xu, Shiwen Mao, Mingzhe Chen</p>
    <p><b>Summary:</b> In this paper, a secure and communication-efficient clustered federated
learning (CFL) design is proposed. In our model, several base stations (BSs)
with heterogeneous task-handling capabilities and multiple users with
non-independent and identically distributed (non-IID) data jointly perform CFL
training incorporating differential privacy (DP) techniques. Since each BS can
process only a subset of the learning tasks and has limited wireless resource
blocks (RBs) to allocate to users for federated learning (FL) model parameter
transmission, it is necessary to jointly optimize RB allocation and user
scheduling for CFL performance optimization. Meanwhile, our considered CFL
method requires devices to use their limited data and FL model information to
determine their task identities, which may introduce additional communication
overhead. We formulate an optimization problem whose goal is to minimize the
training loss of all learning tasks while considering device clustering, RB
allocation, DP noise, and FL model transmission delay. To solve the problem, we
propose a novel dynamic penalty function assisted value decomposed multi-agent
reinforcement learning (DPVD-MARL) algorithm that enables distributed BSs to
independently determine their connected users, RBs, and DP noise of the
connected users but jointly minimize the training loss of all learning tasks
across all BSs. Different from the existing MARL methods that assign a large
penalty for invalid actions, we propose a novel penalty assignment scheme that
assigns penalty depending on the number of devices that cannot meet
communication constraints (e.g., delay), which can guide the MARL scheme to
quickly find valid actions, thus improving the convergence speed. Simulation
results show that the DPVD-MARL can improve the convergence rate by up to 20%
and the ultimate accumulated rewards by 15% compared to independent Q-learning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.07258v1">FedP3E: Privacy-Preserving Prototype Exchange for Non-IID IoT Malware
  Detection in Cross-Silo Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-09T20:07:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rami Darwish, Mahmoud Abdelsalam, Sajad Khorsandroo, Kaushik Roy</p>
    <p><b>Summary:</b> As IoT ecosystems continue to expand across critical sectors, they have
become prominent targets for increasingly sophisticated and large-scale malware
attacks. The evolving threat landscape, combined with the sensitive nature of
IoT-generated data, demands detection frameworks that are both
privacy-preserving and resilient to data heterogeneity. Federated Learning (FL)
offers a promising solution by enabling decentralized model training without
exposing raw data. However, standard FL algorithms such as FedAvg and FedProx
often fall short in real-world deployments characterized by class imbalance and
non-IID data distributions -- particularly in the presence of rare or disjoint
malware classes. To address these challenges, we propose FedP3E
(Privacy-Preserving Prototype Exchange), a novel FL framework that supports
indirect cross-client representation sharing while maintaining data privacy.
Each client constructs class-wise prototypes using Gaussian Mixture Models
(GMMs), perturbs them with Gaussian noise, and transmits only these compact
summaries to the server. The aggregated prototypes are then distributed back to
clients and integrated into local training, supported by SMOTE-based
augmentation to enhance representation of minority malware classes. Rather than
relying solely on parameter averaging, our prototype-driven mechanism enables
clients to enrich their local models with complementary structural patterns
observed across the federation -- without exchanging raw data or gradients.
This targeted strategy reduces the adverse impact of statistical heterogeneity
with minimal communication overhead. We evaluate FedP3E on the N-BaIoT dataset
under realistic cross-silo scenarios with varying degrees of data imbalance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.07210v1">WatchWitch: Interoperability, Privacy, and Autonomy for the Apple Watch</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-09T18:33:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nils Rollshausen, Alexander Heinrich, Matthias Hollick, Jiska Classen</p>
    <p><b>Summary:</b> Smartwatches such as the Apple Watch collect vast amounts of intimate health
and fitness data as we wear them. Users have little choice regarding how this
data is processed: The Apple Watch can only be used with Apple's iPhones, using
their software and their cloud services. We are the first to publicly
reverse-engineer the watch's wireless protocols, which led to discovering
multiple security issues in Apple's proprietary implementation. With
WatchWitch, our custom Android reimplementation, we break out of Apple's walled
garden -- demonstrating practical interoperability with enhanced privacy
controls and data autonomy. We thus pave the way for more consumer choice in
the smartwatch ecosystem, offering users more control over their devices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.06969v1">Unifying Re-Identification, Attribute Inference, and Data Reconstruction
  Risks in Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> 
  <p><b>Published on:</b> 2025-07-09T15:59:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bogdan Kulynych, Juan Felipe Gomez, Georgios Kaissis, Jamie Hayes, Borja Balle, Flavio du Pin Calmon, Jean Louis Raisaro</p>
    <p><b>Summary:</b> Differentially private (DP) mechanisms are difficult to interpret and
calibrate because existing methods for mapping standard privacy parameters to
concrete privacy risks -- re-identification, attribute inference, and data
reconstruction -- are both overly pessimistic and inconsistent. In this work,
we use the hypothesis-testing interpretation of DP ($f$-DP), and determine that
bounds on attack success can take the same unified form across
re-identification, attribute inference, and data reconstruction risks. Our
unified bounds are (1) consistent across a multitude of attack settings, and
(2) tunable, enabling practitioners to evaluate risk with respect to arbitrary
(including worst-case) levels of baseline risk. Empirically, our results are
tighter than prior methods using $\varepsilon$-DP, R\'enyi DP, and concentrated
DP. As a result, calibrating noise using our bounds can reduce the required
noise by 20% at the same risk level, which yields, e.g., more than 15pp
accuracy increase in a text classification task. Overall, this unifying
perspective provides a principled framework for interpreting and calibrating
the degree of protection in DP against specific levels of re-identification,
attribute inference, or data reconstruction risk.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.06652v1">Federated Learning Inspired Fuzzy Systems: Decentralized Rule Updating
  for Privacy and Scalable Decision Making</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-07-09T08:34:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arthur Alexander Lim, Zhen Bin It, Jovan Bowen Heng, Tee Hui Teo</p>
    <p><b>Summary:</b> Fuzzy systems are a way to allow machines, systems and frameworks to deal
with uncertainty, which is not possible in binary systems that most computers
use. These systems have already been deployed for certain use cases, and fuzzy
systems could be further improved as proposed in this paper. Such technologies
to draw inspiration from include machine learning and federated learning.
Machine learning is one of the recent breakthroughs of technology and could be
applied to fuzzy systems to further improve the results it produces. Federated
learning is also one of the recent technologies that have huge potential, which
allows machine learning training to improve by reducing privacy risk, reducing
burden on networking infrastructure, and reducing latency of the latest model.
Aspects from federated learning could be used to improve federated learning,
such as applying the idea of updating the fuzzy rules that make up a key part
of fuzzy systems, to further improve it over time. This paper discusses how
these improvements would be implemented in fuzzy systems, and how it would
improve fuzzy systems. It also discusses certain limitations on the potential
improvements. It concludes that these proposed ideas and improvements require
further investigation to see how far the improvements are, but the potential is
there to improve fuzzy systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.06619v1">Steps Adaptive Decay DPSGD: Enhancing Performance on Imbalanced Datasets
  with Differential Privacy with HAM10000</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2025-07-09T07:46:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaobo Huang, Fang Xie</p>
    <p><b>Summary:</b> When applying machine learning to medical image classification, data leakage
is a critical issue. Previous methods, such as adding noise to gradients for
differential privacy, work well on large datasets like MNIST and CIFAR-100, but
fail on small, imbalanced medical datasets like HAM10000. This is because the
imbalanced distribution causes gradients from minority classes to be clipped
and lose crucial information, while majority classes dominate. This leads the
model to fall into suboptimal solutions early. To address this, we propose
SAD-DPSGD, which uses a linear decaying mechanism for noise and clipping
thresholds. By allocating more privacy budget and using higher clipping
thresholds in the initial training phases, the model avoids suboptimal
solutions and enhances performance. Experiments show that SAD-DPSGD outperforms
Auto-DPSGD on HAM10000, improving accuracy by 2.15% under $\epsilon = 3.0$ ,
$\delta = 10^{-3}$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.06508v1">Subgraph Counting under Edge Local Differential Privacy Based on Noisy
  Adjacency Matrix</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-09T03:13:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jintao Guo, Ying Zhou, Chao Li, Guixun Luo</p>
    <p><b>Summary:</b> When analyzing connection patterns within graphs, subgraph counting serves as
an effective and fundamental approach. Edge-local differential privacy
(edge-LDP) and shuffle model have been employed to achieve subgraph counting
under a privacy-preserving situation. Existing algorithms are plagued by high
time complexity, excessive download costs, low accuracy, or dependence on
trusted third parties. To address the aforementioned challenges, we propose the
Noisy Adjacency Matrix (NAM), which combines differential privacy with the
adjacency matrix of the graph. NAM offers strong versatility and scalability,
making it applicable to a wider range of DP variants, DP mechanisms, and graph
types. Based on NAM, we designed five algorithms (TriOR, TriTR, TriMTR, QuaTR,
and 2STAR) to count three types of subgraphs: triangles, quadrangles, and
2-stars. Theoretical and experimental results demonstrate that in triangle
counting, TriOR maximizes accuracy with reduced time complexity among one-round
algorithms, TriTR achieves optimal accuracy, TriMTR achieves the highest
accuracy under low download costs, and QuaTR stands as the first quadrangle
counting algorithm under pure edge-LDP. We implement edge-LDP for noisy data
via a confidence interval-inspired method, providing DP guarantees on
randomized data. Our 2STAR algorithm achieves the highest accuracy in 2-star
counting and can be derived as a byproduct of two-round triangle or quadrangle
counting algorithms, enabling efficient joint estimation of triangle,
quadrangle, and 2-star counts within two query rounds.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.06350v1">An Architecture for Privacy-Preserving Telemetry Scheme</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-07-08T19:20:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kenneth Odoh</p>
    <p><b>Summary:</b> We present a privacy-preserving telemetry aggregation scheme. Our underlying
frequency estimation routine works within the framework of differential
privacy. The design philosophy follows a client-server architecture.
Furthermore, the system uses a local differential privacy scheme where data
gets randomized on the client before submitting the request to the resource
server. This scheme allows for data analysis on de-identified data by carefully
adding noise to prevent re-identification attacks, thereby facilitating public
data release without compromising the identifiability of the individual record.
This work further enhances privacy guarantees by leveraging Oblivious HTTP
(OHTTP) to achieve increased privacy protection for data in transit that
addresses pre-existing privacy vulnerabilities in raw HTTP. We provide an
implementation that focuses on frequency estimation with a histogram of a known
dictionary. Our resulting formulation based on OHTTP has provided stricter
privacy safeguards when compared to trusting an organization to manually delete
identifying information from the client's request in the ingestor as deployed
in reference work~\cite{apple2017}. Code available at
https://github.com/kenluck2001/miscellaneous/tree/master/src/Privacy-Preserving-Telemetry.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.06008v1">The Impact of Event Data Partitioning on Privacy-aware Process Discovery</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2025-07-08T14:13:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jungeun Lim, Stephan A. Fahrenkrog-Petersen, Xixi Lu, Jan Mendling, Minseok Song</p>
    <p><b>Summary:</b> Information systems support the execution of business processes. The event
logs of these executions generally contain sensitive information about
customers, patients, and employees. The corresponding privacy challenges can be
addressed by anonymizing the event logs while still retaining utility for
process discovery. However, trading off utility and privacy is difficult: the
higher the complexity of event log, the higher the loss of utility by
anonymization. In this work, we propose a pipeline that combines anonymization
and event data partitioning, where event abstraction is utilized for
partitioning. By leveraging event abstraction, event logs can be segmented into
multiple parts, allowing each sub-log to be anonymized separately. This
pipeline preserves privacy while mitigating the loss of utility. To validate
our approach, we study the impact of event partitioning on two anonymization
techniques using three real-world event logs and two process discovery
techniques. Our results demonstrate that event partitioning can bring
improvements in process discovery utility for directly-follows-based
anonymization techniques.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.05875v1">Post-Processing in Local Differential Privacy: An Extensive Evaluation
  and Benchmark Platform</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-08T10:59:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alireza Khodaie, Berkay Kemal Balioglu, Mehmet Emre Gursoy</p>
    <p><b>Summary:</b> Local differential privacy (LDP) has recently gained prominence as a powerful
paradigm for collecting and analyzing sensitive data from users' devices.
However, the inherent perturbation added by LDP protocols reduces the utility
of the collected data. To mitigate this issue, several post-processing (PP)
methods have been developed. Yet, the comparative performance of PP methods
under diverse settings remains underexplored. In this paper, we present an
extensive benchmark comprising 6 popular LDP protocols, 7 PP methods, 4 utility
metrics, and 6 datasets to evaluate the behaviors and optimality of PP methods
under diverse conditions. Through extensive experiments, we show that while PP
can substantially improve utility when the privacy budget is small (i.e.,
strict privacy), its benefit diminishes as the privacy budget grows. Moreover,
our findings reveal that the optimal PP method depends on multiple factors,
including the choice of LDP protocol, privacy budget, data characteristics
(such as distribution and domain size), and the specific utility metric. To
advance research in this area and assist practitioners in identifying the most
suitable PP method for their setting, we introduce LDP$^3$, an open-source
benchmark platform. LDP$^3$ contains all methods used in our experimental
analysis, and it is designed in a modular, extensible, and multi-threaded way
for future use and development.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.05872v1">LDP$^3$: An Extensible and Multi-Threaded Toolkit for Local Differential
  Privacy Protocols and Post-Processing Methods</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-08T10:51:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Berkay Kemal Balioglu, Alireza Khodaie, Mehmet Emre Gursoy</p>
    <p><b>Summary:</b> Local differential privacy (LDP) has become a prominent notion for
privacy-preserving data collection. While numerous LDP protocols and
post-processing (PP) methods have been developed, selecting an optimal
combination under different privacy budgets and datasets remains a challenge.
Moreover, the lack of a comprehensive and extensible LDP benchmarking toolkit
raises difficulties in evaluating new protocols and PP methods. To address
these concerns, this paper presents LDP$^3$ (pronounced LDP-Cube), an
open-source, extensible, and multi-threaded toolkit for LDP researchers and
practitioners. LDP$^3$ contains implementations of several LDP protocols, PP
methods, and utility metrics in a modular and extensible design. Its modular
design enables developers to conveniently integrate new protocols and PP
methods. Furthermore, its multi-threaded nature enables significant reductions
in execution times via parallelization. Experimental evaluations demonstrate
that: (i) using LDP$^3$ to select a good protocol and post-processing method
substantially improves utility compared to a bad or random choice, and (ii) the
multi-threaded design of LDP$^3$ brings substantial benefits in terms of
efficiency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.05610v2">On the Inherent Privacy of Zeroth Order Projected Gradient Descent</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2025-07-08T02:38:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Devansh Gupta, Meisam Razaviyayn, Vatsal Sharan</p>
    <p><b>Summary:</b> Differentially private zeroth-order optimization methods have recently gained
popularity in private fine tuning of machine learning models due to their
reduced memory requirements. Current approaches for privatizing zeroth-order
methods rely on adding Gaussian noise to the estimated zeroth-order gradients.
However, since the search direction in the zeroth-order methods is inherently
random, researchers including Tang et al. (2024) and Zhang et al. (2024a) have
raised an important question: is the inherent noise in zeroth-order estimators
sufficient to ensure the overall differential privacy of the algorithm? This
work settles this question for a class of oracle-based optimization algorithms
where the oracle returns zeroth-order gradient estimates. In particular, we
show that for a fixed initialization, there exist strongly convex objective
functions such that running (Projected) Zeroth-Order Gradient Descent (ZO-GD)
is not differentially private. Furthermore, we show that even with random
initialization and without revealing (initial and) intermediate iterates, the
privacy loss in ZO-GD can grow superlinearly with the number of iterations when
minimizing convex objective functions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.05415v1">Layered, Overlapping, and Inconsistent: A Large-Scale Analysis of the
  Multiple Privacy Policies and Controls of U.S. Banks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-07T18:55:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lu Xian, Van Tran, Lauren Lee, Meera Kumar, Yichen Zhang, Florian Schaub</p>
    <p><b>Summary:</b> Privacy policies are often complex. An exception is the two-page standardized
notice that U.S. financial institutions must provide under the
Gramm-Leach-Bliley Act (GLBA). However, banks now operate websites, mobile
apps, and other services that involve complex data sharing practices that
require additional privacy notices and do-not-sell opt-outs. We conducted a
large-scale analysis of how U.S. banks implement privacy policies and controls
in response to GLBA; other federal privacy policy requirements; and the
California Consumer Privacy Act (CCPA), a key example for U.S. state privacy
laws. We focused on the disclosure and control of a set of especially
privacy-invasive practices: third-party data sharing for marketing-related
purposes. We collected privacy policies for the 2,067 largest U.S. banks,
45.3\% of which provided multiple policies. Across disclosures and controls
within the \textit{same} bank, we identified frequent, concerning
inconsistencies -- such as banks indicating in GLBA notices that they do not
share with third parties but disclosing sharing elsewhere, or using third-party
marketing/advertising cookies without disclosure. This multiplicity of
policies, with the inconsistencies it causes, may create consumer confusion and
undermine the transparency goals of the very laws that require them. Our
findings call into question whether current policy requirements, such as the
GLBA notice, are achieving their intended goals in today's online banking
landscape. We discuss potential avenues for reforming and harmonizing privacy
policies and control requirements across federal and state laws.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.05391v1">Controlling What You Share: Assessing Language Model Adherence to
  Privacy Preferences</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-07T18:22:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guillem Ramírez, Alexandra Birch, Ivan Titov</p>
    <p><b>Summary:</b> Large language models (LLMs) are primarily accessed via commercial APIs, but
this often requires users to expose their data to service providers. In this
paper, we explore how users can stay in control of their data by using privacy
profiles: simple natural language instructions that say what should and should
not be revealed. We build a framework where a local model uses these
instructions to rewrite queries, only hiding details deemed sensitive by the
user, before sending them to an external model, thus balancing privacy with
performance. To support this research, we introduce PEEP, a multilingual
dataset of real user queries annotated to mark private content and paired with
synthetic privacy profiles. Our experiments with lightweight LLMs show they can
follow these instructions to some extent, but also face consistent challenges,
highlighting the need for models that better understand and comply with
user-defined privacy preferences.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.05175v1">Blind Targeting: Personalization under Third-Party Privacy Constraints</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">  
  <p><b>Published on:</b> 2025-07-07T16:30:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anya Shchetkina</p>
    <p><b>Summary:</b> Major advertising platforms recently increased privacy protections by
limiting advertisers' access to individual-level data. Instead of providing
access to granular raw data, the platforms only allow a limited number of
aggregate queries to a dataset, which is further protected by adding
differentially private noise. This paper studies whether and how advertisers
can design effective targeting policies within these restrictive privacy
preserving data environments. To achieve this, I develop a probabilistic
machine learning method based on Bayesian optimization, which facilitates
dynamic data exploration. Since Bayesian optimization was designed to sample
points from a function to find its maximum, it is not applicable to aggregate
queries and to targeting. Therefore, I introduce two innovations: (i) integral
updating of posteriors which allows to select the best regions of the data to
query rather than individual points and (ii) a targeting-aware acquisition
function that dynamically selects the most informative regions for the
targeting task. I identify the conditions of the dataset and privacy
environment that necessitate the use of such a "smart" querying strategy. I
apply the strategic querying method to the Criteo AI Labs dataset for uplift
modeling (Diemert et al., 2018) that contains visit and conversion data from
14M users. I show that an intuitive benchmark strategy only achieves 33% of the
non-privacy-preserving targeting potential in some cases, while my strategic
querying method achieves 97-101% of that potential, and is statistically
indistinguishable from Causal Forest (Athey et al., 2019): a state-of-the-art
non-privacy-preserving machine learning targeting method.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.04771v1">Efficient Unlearning with Privacy Guarantees</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-07-07T08:46:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Josep Domingo-Ferrer, Najeeb Jebreel, David Sánchez</p>
    <p><b>Summary:</b> Privacy protection laws, such as the GDPR, grant individuals the right to
request the forgetting of their personal data not only from databases but also
from machine learning (ML) models trained on them. Machine unlearning has
emerged as a practical means to facilitate model forgetting of data instances
seen during training. Although some existing machine unlearning methods
guarantee exact forgetting, they are typically costly in computational terms.
On the other hand, more affordable methods do not offer forgetting guarantees
and are applicable only to specific ML models. In this paper, we present
\emph{efficient unlearning with privacy guarantees} (EUPG), a novel machine
unlearning framework that offers formal privacy guarantees to individuals whose
data are being unlearned. EUPG involves pre-training ML models on data
protected using privacy models, and it enables {\em efficient unlearning with
the privacy guarantees offered by the privacy models in use}. Through empirical
evaluation on four heterogeneous data sets protected with $k$-anonymity and
$\epsilon$-differential privacy as privacy models, our approach demonstrates
utility and forgetting effectiveness comparable to those of exact unlearning
methods, while significantly reducing computational and storage costs. Our code
is available at https://github.com/najeebjebreel/EUPG.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.04528v1">Towards integration of Privacy Enhancing Technologies in Explainable
  Artificial Intelligence</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-06T20:45:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sonal Allana, Rozita Dara, Xiaodong Lin, Pulei Xiong</p>
    <p><b>Summary:</b> Explainable Artificial Intelligence (XAI) is a crucial pathway in mitigating
the risk of non-transparency in the decision-making process of black-box
Artificial Intelligence (AI) systems. However, despite the benefits, XAI
methods are found to leak the privacy of individuals whose data is used in
training or querying the models. Researchers have demonstrated privacy attacks
that exploit explanations to infer sensitive personal information of
individuals. Currently there is a lack of defenses against known privacy
attacks targeting explanations when vulnerable XAI are used in production and
machine learning as a service system. To address this gap, in this article, we
explore Privacy Enhancing Technologies (PETs) as a defense mechanism against
attribute inference on explanations provided by feature-based XAI methods. We
empirically evaluate 3 types of PETs, namely synthetic training data,
differentially private training and noise addition, on two categories of
feature-based XAI. Our evaluation determines different responses from the
mitigation methods and side-effects of PETs on other system properties such as
utility and performance. In the best case, PETs integration in explanations
reduced the risk of the attack by 49.47%, while maintaining model utility and
explanation quality. Through our evaluation, we identify strategies for using
PETs in XAI for maximizing benefits and minimizing the success of this privacy
attack on sensitive personal information.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.04185v1">From Legal Text to Tech Specs: Generative AI's Interpretation of Consent
  in Privacy Law</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-07-05T23:36:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aniket Kesari, Travis Breaux, Tom Norton, Sarah Santos, Anmol Singhal</p>
    <p><b>Summary:</b> Privacy law and regulation have turned to "consent" as the legitimate basis
for collecting and processing individuals' data. As governments have rushed to
enshrine consent requirements in their privacy laws, such as the California
Consumer Privacy Act (CCPA), significant challenges remain in understanding how
these legal mandates are operationalized in software. The opaque nature of
software development processes further complicates this translation. To address
this, we explore the use of Large Language Models (LLMs) in requirements
engineering to bridge the gap between legal requirements and technical
implementation. This study employs a three-step pipeline that involves using an
LLM to classify software use cases for compliance, generating LLM modifications
for non-compliant cases, and manually validating these changes against legal
standards. Our preliminary findings highlight the potential of LLMs in
automating compliance tasks, while also revealing limitations in their
reasoning capabilities. By benchmarking LLMs against real-world use cases, this
research provides insights into leveraging AI-driven solutions to enhance legal
compliance of software.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.04104v1">Human-Centered Interactive Anonymization for Privacy-Preserving Machine
  Learning: A Case for Human-Guided k-Anonymity</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-05T17:20:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sri Harsha Gajavalli</p>
    <p><b>Summary:</b> Privacy-preserving machine learning (ML) seeks to balance data utility and
privacy, especially as regulations like the GDPR mandate the anonymization of
personal data for ML applications. Conventional anonymization approaches often
reduce data utility due to indiscriminate generalization or suppression of data
attributes. In this study, we propose an interactive approach that incorporates
human input into the k-anonymization process, enabling domain experts to guide
attribute preservation based on contextual importance. Using the UCI Adult
dataset, we compare classification outcomes of interactive human-influenced
anonymization with traditional, fully automated methods. Our results show that
human input can enhance data utility in some cases, although results vary
across tasks and settings. We discuss limitations of our approach and suggest
potential areas for improved interactive frameworks in privacy-aware ML.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.03694v1">Willchain: Decentralized, Privacy-Preserving, Self-Executing, Digital
  Wills</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computational Engineering, Finance, and Science-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2025-07-04T16:23:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jovonni L. PHarr</p>
    <p><b>Summary:</b> This work presents a novel decentralized protocol for digital estate planning
that integrates advances distributed computing, and cryptography. The original
proof-of-concept was constructed using purely solidity contracts. Since then,
we have enhanced the implementation into a layer-1 protocol that uses modern
interchain communication to connect several heterogeneous chain types. A key
contribution of this research is the implementation of several modern
cryptographic primitives to support various forms of claims for information
validation. These primitives introduce an unmatched level of privacy to the
process of digital inheritance. We also demonstrate on a set of heterogeneous
smart contracts, following the same spec, on each chain to serve as entry
points, gateways, or bridge contracts that are invoked via a path from the will
module on our protocol, to the contract. This ensures a fair and secure
distribution of digital assets in accordance with the wishes of the decedent
without the requirement of moving their funds. This research further extends
its innovations with a user interaction model, featuring a check-in system and
account abstraction process, which enhances flexibility and user-friendliness
without compromising on security. By developing a dedicated permissionless
blockchain that is secured by a network of validators, and interchain relayers,
the proposed protocol signifies a transformation in the digital estate planning
industry and illustrates the potential of blockchain technology in
revolutionizing traditional legal and personal spheres. Implementing a
cryptoeconomic network at the core of inheritance planning allows for unique
incentive compatible economic mechanisms to be constructed.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.02727v1">Quantifying Classifier Utility under Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2025-07-03T15:42:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ye Zheng, Yidan Hu</p>
    <p><b>Summary:</b> Local differential privacy (LDP) provides a rigorous and quantifiable privacy
guarantee for personal data by introducing perturbation at the data source.
However, quantifying the impact of these perturbations on classifier utility
remains a theoretical challenge, particularly for complex or black-box
classifiers.
  This paper presents a framework for theoretically quantifying classifier
utility under LDP mechanisms. The key insight is that LDP perturbation is
concentrated around the original data with a specific probability, transforming
utility analysis of the classifier into its robustness analysis in this
concentrated region. Our framework connects the concentration analysis of LDP
mechanisms with the robustness analysis of classifiers. It treats LDP
mechanisms as general distributional functions and classifiers as black-box
functions, thus applicable to any LDP mechanism and classifier. A direct
application of our utility quantification is guiding the selection of LDP
mechanisms and privacy parameters for a given classifier. Notably, our analysis
shows that a piecewise-based mechanism leads to better utility compared to
alternatives in common scenarios.
  Using this framework alongside two novel refinement techniques, we conduct
case studies on utility quantification for typical mechanism-classifier
combinations. The results demonstrate that our theoretical utility
quantification aligns closely with empirical observations, particularly when
classifiers operate in lower-dimensional input spaces.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.02414v1">Privacy-preserving Preselection for Face Identification Based on Packing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-03T08:15:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rundong Xin, Taotao Wang, Jin Wang, Chonghe Zhao, Jing Wang</p>
    <p><b>Summary:</b> Face identification systems operating in the ciphertext domain have garnered
significant attention due to increasing privacy concerns and the potential
recovery of original facial data. However, as the size of ciphertext template
libraries grows, the face retrieval process becomes progressively more
time-intensive. To address this challenge, we propose a novel and efficient
scheme for face retrieval in the ciphertext domain, termed Privacy-Preserving
Preselection for Face Identification Based on Packing (PFIP). PFIP incorporates
an innovative preselection mechanism to reduce computational overhead and a
packing module to enhance the flexibility of biometric systems during the
enrollment stage. Extensive experiments conducted on the LFW and CASIA datasets
demonstrate that PFIP preserves the accuracy of the original face recognition
model, achieving a 100% hit rate while retrieving 1,000 ciphertext face
templates within 300 milliseconds. Compared to existing approaches, PFIP
achieves a nearly 50x improvement in retrieval efficiency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.03033v1">Preserving Privacy, Increasing Accessibility, and Reducing Cost: An
  On-Device Artificial Intelligence Model for Medical Transcription and Note
  Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-07-03T01:51:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Johnson Thomas, Ayush Mudgal, Wendao Liu, Nisten Tahiraj, Zeeshaan Mohammed, Dhruv Diddi</p>
    <p><b>Summary:</b> Background: Clinical documentation represents a significant burden for
healthcare providers, with physicians spending up to 2 hours daily on
administrative tasks. Recent advances in large language models (LLMs) offer
promising solutions, but privacy concerns and computational requirements limit
their adoption in healthcare settings. Objective: To develop and evaluate a
privacy-preserving, on-device medical transcription system using a fine-tuned
Llama 3.2 1B model capable of generating structured medical notes from medical
transcriptions while maintaining complete data sovereignty entirely in the
browser. Methods: We fine-tuned a Llama 3.2 1B model using Parameter-Efficient
Fine-Tuning (PEFT) with LoRA on 1,500 synthetic medical
transcription-to-structured note pairs. The model was evaluated against the
base Llama 3.2 1B on two datasets: 100 endocrinology transcripts and 140
modified ACI benchmark cases. Evaluation employed both statistical metrics
(ROUGE, BERTScore, BLEURT) and LLM-as-judge assessments across multiple
clinical quality dimensions. Results: The fine-tuned OnDevice model
demonstrated substantial improvements over the base model. On the ACI
benchmark, ROUGE-1 scores increased from 0.346 to 0.496, while BERTScore F1
improved from 0.832 to 0.866. Clinical quality assessments showed marked
reduction in major hallucinations (from 85 to 35 cases) and enhanced factual
correctness (2.81 to 3.54 on 5-point scale). Similar improvements were observed
on the internal evaluation dataset, with composite scores increasing from 3.13
to 4.43 (+41.5%). Conclusions: Fine-tuning compact LLMs for medical
transcription yields clinically meaningful improvements while enabling complete
on-device browser deployment. This approach addresses key barriers to AI
adoption in healthcare: privacy preservation, cost reduction, and accessibility
for resource-constrained environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.01808v1">Empowering Manufacturers with Privacy-Preserving AI Tools: A Case Study
  in Privacy-Preserving Machine Learning to Solve Real-World Problems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> 
  <p><b>Published on:</b> 2025-07-02T15:25:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaoyu Ji, Jessica Shorland, Joshua Shank, Pascal Delpe-Brice, Latanya Sweeney, Jan Allebach, Ali Shakouri</p>
    <p><b>Summary:</b> Small- and medium-sized manufacturers need innovative data tools but, because
of competition and privacy concerns, often do not want to share their
proprietary data with researchers who might be interested in helping. This
paper introduces a privacy-preserving platform by which manufacturers may
safely share their data with researchers through secure methods, so that those
researchers then create innovative tools to solve the manufacturers' real-world
problems, and then provide tools that execute solutions back onto the platform
for others to use with privacy and confidentiality guarantees. We illustrate
this problem through a particular use case which addresses an important problem
in the large-scale manufacturing of food crystals, which is that quality
control relies on image analysis tools. Previous to our research, food crystals
in the images were manually counted, which required substantial and
time-consuming human efforts, but we have developed and deployed a crystal
analysis tool which makes this process both more rapid and accurate. The tool
enables automatic characterization of the crystal size distribution and numbers
from microscope images while the natural imperfections from the sample
preparation are automatically removed; a machine learning model to count high
resolution translucent crystals and agglomeration of crystals was also
developed to aid in these efforts. The resulting algorithm was then packaged
for real-world use on the factory floor via a web-based app secured through the
originating privacy-preserving platform, allowing manufacturers to use it while
keeping their proprietary data secure. After demonstrating this full process,
future directions are also explored.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.01752v1">Tuning without Peeking: Provable Privacy and Generalization Bounds for
  LLM Post-Training</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-02T14:29:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ismail Labiad, Mathurin Videau, Matthieu Kowalski, Marc Schoenauer, Alessandro Leite, Julia Kempe, Olivier Teytaud</p>
    <p><b>Summary:</b> Gradient-based optimization is the workhorse of deep learning, offering
efficient and scalable training via backpropagation. However, its reliance on
large volumes of labeled data raises privacy and security concerns such as
susceptibility to data poisoning attacks and the risk of overfitting. In
contrast, black box optimization methods, which treat the model as an opaque
function, relying solely on function evaluations to guide optimization, offer a
promising alternative in scenarios where data access is restricted, adversarial
risks are high, or overfitting is a concern. However, black box methods also
pose significant challenges, including poor scalability to high-dimensional
parameter spaces, as prevalent in large language models (LLMs), and high
computational costs due to reliance on numerous model evaluations. This paper
introduces BBoxER, an evolutionary black-box method for LLM post-training that
induces an information bottleneck via implicit compression of the training
data. Leveraging the tractability of information flow, we provide strong
theoretical bounds on generalization, differential privacy, susceptibility to
data poisoning attacks, and robustness to extraction attacks. BBoxER operates
on top of pre-trained LLMs, offering a lightweight and modular enhancement
suitable for deployment in restricted or privacy-sensitive environments, in
addition to non-vacuous generalization guarantees. In experiments with LLMs, we
demonstrate empirically that Retrofitting methods are able to learn, showing
how a few iterations of BBoxER improve performance and generalize well on a
benchmark of reasoning datasets. This positions BBoxER as an attractive add-on
on top of gradient-based optimization.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.01581v1">A Privacy-Preserving Indoor Localization System based on Hierarchical
  Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2025-07-02T10:53:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Masood Jan, Wafa Njima, Xun Zhang</p>
    <p><b>Summary:</b> Location information serves as the fundamental element for numerous Internet
of Things (IoT) applications. Traditional indoor localization techniques often
produce significant errors and raise privacy concerns due to centralized data
collection. In response, Machine Learning (ML) techniques offer promising
solutions by capturing indoor environment variations. However, they typically
require central data aggregation, leading to privacy, bandwidth, and server
reliability issues. To overcome these challenges, in this paper, we propose a
Federated Learning (FL)-based approach for dynamic indoor localization using a
Deep Neural Network (DNN) model. Experimental results show that FL has the
nearby performance to Centralized Model (CL) while keeping the data privacy,
bandwidth efficiency and server reliability. This research demonstrates that
our proposed FL approach provides a viable solution for privacy-enhanced indoor
localization, paving the way for advancements in secure and efficient indoor
localization systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.01487v1">How to Securely Shuffle? A survey about Secure Shufflers for
  privacy-preserving computations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-07-02T08:48:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marc Damie, Florian Hahn, Andreas Peter, Jan Ramon</p>
    <p><b>Summary:</b> Ishai et al. (FOCS'06) introduced secure shuffling as an efficient building
block for private data aggregation. Recently, the field of differential privacy
has revived interest in secure shufflers by highlighting the privacy
amplification they can provide in various computations. Although several works
argue for the utility of secure shufflers, they often treat them as black
boxes; overlooking the practical vulnerabilities and performance trade-offs of
existing implementations. This leaves a central question open: what makes a
good secure shuffler?
  This survey addresses that question by identifying, categorizing, and
comparing 26 secure protocols that realize the necessary shuffling
functionality. To enable a meaningful comparison, we adapt and unify existing
security definitions into a consistent set of properties. We also present an
overview of privacy-preserving technologies that rely on secure shufflers,
offer practical guidelines for selecting appropriate protocols, and outline
promising directions for future work.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.01216v1">PAE MobiLLM: Privacy-Aware and Efficient LLM Fine-Tuning on the Mobile
  Device via Additive Side-Tuning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-01T22:27:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xingke Yang, Liang Li, Zhiyi Wan, Sicong Li, Hao Wang, Xiaoqi Qi, Jiang Liu, Tomoaki Ohtsuki, Xin Fu, Miao Pan</p>
    <p><b>Summary:</b> There is a huge gap between numerous intriguing applications fostered by
on-device large language model (LLM) fine-tuning (FT) from fresh mobile data
and the limited resources of a mobile device. While existing server-assisted
methods (e.g., split learning or side-tuning) may enable LLM FT on the local
mobile device, they suffer from heavy communication burdens of activation
transmissions, and may disclose data, labels or fine-tuned models to the
server. To address those issues, we develop PAE MobiLLM, a privacy-aware and
efficient LLM FT method which can be deployed on the mobile device via
server-assisted additive side-tuning. To further accelerate FT convergence and
improve computing efficiency, PAE MobiLLM integrates activation caching on the
server side, which allows the server to reuse historical activations and saves
the mobile device from repeatedly computing forward passes for the recurring
data samples. Besides, to reduce communication cost, PAE MobiLLM develops a
one-token (i.e., ``pivot'' token) activation shortcut that transmits only a
single activation dimension instead of full activation matrices to guide the
side network tuning. Last but not least, PAE MobiLLM introduces the additive
adapter side-network design which makes the server train the adapter modules
based on device-defined prediction differences rather than raw ground-truth
labels. In this way, the server can only assist device-defined side-network
computing, and learn nothing about data, labels or fine-tuned models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.00920v2">Privacy-Preserving Quantized Federated Learning with Diverse Precision</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2025-07-01T16:26:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dang Qua Nguyen, Morteza Hashemi, Erik Perrins, Sergiy A. Vorobyov, David J. Love, Taejoon Kim</p>
    <p><b>Summary:</b> Federated learning (FL) has emerged as a promising paradigm for distributed
machine learning, enabling collaborative training of a global model across
multiple local devices without requiring them to share raw data. Despite its
advancements, FL is limited by factors such as: (i) privacy risks arising from
the unprotected transmission of local model updates to the fusion center (FC)
and (ii) decreased learning utility caused by heterogeneity in model
quantization resolution across participating devices. Prior work typically
addresses only one of these challenges because maintaining learning utility
under both privacy risks and quantization heterogeneity is a non-trivial task.
In this paper, our aim is therefore to improve the learning utility of a
privacy-preserving FL that allows clusters of devices with different
quantization resolutions to participate in each FL round. Specifically, we
introduce a novel stochastic quantizer (SQ) that is designed to simultaneously
achieve differential privacy (DP) and minimum quantization error. Notably, the
proposed SQ guarantees bounded distortion, unlike other DP approaches. To
address quantization heterogeneity, we introduce a cluster size optimization
technique combined with a linear fusion approach to enhance model aggregation
accuracy. Numerical simulations validate the benefits of our approach in terms
of privacy protection and learning utility compared to the conventional
LaplaceSQ-FL algorithm.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.00596v1">Gaze3P: Gaze-Based Prediction of User-Perceived Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-07-01T09:26:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mayar Elfares, Pascal Reisert, Ralf Küsters, Andreas Bulling</p>
    <p><b>Summary:</b> Privacy is a highly subjective concept and perceived variably by different
individuals. Previous research on quantifying user-perceived privacy has
primarily relied on questionnaires. Furthermore, applying user-perceived
privacy to optimise the parameters of privacy-preserving techniques (PPT)
remains insufficiently explored. To address these limitations, we introduce
Gaze3P -- the first dataset specifically designed to facilitate systematic
investigations into user-perceived privacy. Our dataset comprises gaze data
from 100 participants and 1,000 stimuli, encompassing a range of private and
safe attributes. With Gaze3P, we train a machine learning model to implicitly
and dynamically predict perceived privacy from human eye gaze. Through
comprehensive experiments, we show that the resulting models achieve high
accuracy. Finally, we illustrate how predicted privacy can be used to optimise
the parameters of differentially private mechanisms, thereby enhancing their
alignment with user expectations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.00402v1">GRAND: Graph Release with Assured Node Differential Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">  
  <p><b>Published on:</b> 2025-07-01T03:39:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Suqing Liu, Xuan Bi, Tianxi Li</p>
    <p><b>Summary:</b> Differential privacy is a well-established framework for safeguarding
sensitive information in data. While extensively applied across various
domains, its application to network data -- particularly at the node level --
remains underexplored. Existing methods for node-level privacy either focus
exclusively on query-based approaches, which restrict output to pre-specified
network statistics, or fail to preserve key structural properties of the
network. In this work, we propose GRAND (Graph Release with Assured Node
Differential privacy), which is, to the best of our knowledge, the first
network release mechanism that releases entire networks while ensuring
node-level differential privacy and preserving structural properties. Under a
broad class of latent space models, we show that the released network
asymptotically follows the same distribution as the original network. The
effectiveness of the approach is evaluated through extensive experiments on
both synthetic and real-world datasets.</p>
  </details>
</div>



<h2>2025-06</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.00286v1">Visual Privacy Management with Generative AI for Blind and Low-Vision
  People</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2025-06-30T21:55:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tanusree Sharma, Yu-Yun Tseng, Lotus Zhang, Ayae Ide, Kelly Avery Mack, Leah Findlater, Danna Gurari, Yang Wang</p>
    <p><b>Summary:</b> Blind and low vision (BLV) individuals use Generative AI (GenAI) tools to
interpret and manage visual content in their daily lives. While such tools can
enhance the accessibility of visual content and so enable greater user
independence, they also introduce complex challenges around visual privacy. In
this paper, we investigate the current practices and future design preferences
of blind and low vision individuals through an interview study with 21
participants. Our findings reveal a range of current practices with GenAI that
balance privacy, efficiency, and emotional agency, with users accounting for
privacy risks across six key scenarios, such as self-presentation,
indoor/outdoor spatial privacy, social sharing, and handling professional
content. Our findings reveal design preferences, including on-device
processing, zero-retention guarantees, sensitive content redaction,
privacy-aware appearance indicators, and multimodal tactile mirrored
interaction methods. We conclude with actionable design recommendations to
support user-centered visual privacy through GenAI, expanding the notion of
privacy and responsible handling of others data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.00230v2">PPFL-RDSN: Privacy-Preserving Federated Learning-based Residual Dense
  Spatial Networks for Encrypted Lossy Image Reconstruction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-30T19:54:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Peilin He, James Joshi</p>
    <p><b>Summary:</b> Reconstructing high-quality images from low-resolution inputs using Residual
Dense Spatial Networks (RDSNs) is crucial yet challenging, particularly in
collaborative scenarios where centralized training poses significant privacy
risks, including data leakage and inference attacks, as well as high
computational costs. We propose a novel Privacy-Preserving Federated
Learning-based RDSN (PPFL-RDSN) framework specifically tailored for lossy image
reconstruction. PPFL-RDSN integrates Federated Learning (FL), local
differential privacy, and robust model watermarking techniques, ensuring data
remains secure on local devices, safeguarding sensitive information, and
maintaining model authenticity without revealing underlying data. Empirical
evaluations show that PPFL-RDSN achieves comparable performance to the
state-of-the-art centralized methods while reducing computational burdens, and
effectively mitigates security and privacy vulnerabilities, making it a
practical solution for secure and privacy-preserving collaborative computer
vision applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.02974v1">InvisibleInk: High-Utility and Low-Cost Text Generation with
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-30T18:00:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vishnu Vinod, Krishna Pillutla, Abhradeep Guha Thakurta</p>
    <p><b>Summary:</b> As major progress in LLM-based long-form text generation enables paradigms
such as retrieval-augmented generation (RAG) and inference-time scaling, safely
incorporating private information into the generation remains a critical open
question. We present InvisibleInk, a highly scalable long-form text generation
framework satisfying rigorous differential privacy guarantees with respect to
the sensitive references. It interprets sampling from the LLM's
next-token-distribution as the exponential mechanism over the LLM logits with
two innovations. First, we reduce the privacy cost by isolating and clipping
only the sensitive information in the model logits (relative to the public
logits). Second, we improve text quality by sampling from a small superset of
the top-$k$ private tokens. Empirical evaluations demonstrate a consistent
$8\times$ reduction in computation cost over state-of-the-art baselines to
generate long-form private text of the same utility across privacy levels. In
summary, InvisibleInk is able to generate private long-form text at less than
$10\times$ the computation cost of non-private generation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.24033v1">Poisoning Attacks to Local Differential Privacy for Ranking Estimation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-30T16:39:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pei Zhan, Peng Tang, Yangzhuo Li, Puwen Wei, Shanqing Guo</p>
    <p><b>Summary:</b> Local differential privacy (LDP) involves users perturbing their inputs to
provide plausible deniability of their data. However, this also makes LDP
vulnerable to poisoning attacks. In this paper, we first introduce novel
poisoning attacks for ranking estimation. These attacks are intricate, as fake
attackers do not merely adjust the frequency of target items. Instead, they
leverage a limited number of fake users to precisely modify frequencies,
effectively altering item rankings to maximize gains. To tackle this challenge,
we introduce the concepts of attack cost and optimal attack item (set), and
propose corresponding strategies for kRR, OUE, and OLH protocols. For kRR, we
iteratively select optimal attack items and allocate suitable fake users. For
OUE, we iteratively determine optimal attack item sets and consider the
incremental changes in item frequencies across different sets. Regarding OLH,
we develop a harmonic cost function based on the pre-image of a hash to select
that supporting a larger number of effective attack items. Lastly, we present
an attack strategy based on confidence levels to quantify the probability of a
successful attack and the number of attack iterations more precisely. We
demonstrate the effectiveness of our attacks through theoretical and empirical
evidence, highlighting the necessity for defenses against these attacks. The
source code and data have been made available at
https://github.com/LDP-user/LDP-Ranking.git.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2507.02968v1">Unveiling Privacy Policy Complexity: An Exploratory Study Using Graph
  Mining, Machine Learning, and Natural Language Processing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-06-30T14:55:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vijayalakshmi Ramasamy, Seth Barrett, Gokila Dorai, Jessica Zumbach</p>
    <p><b>Summary:</b> Privacy policy documents are often lengthy, complex, and difficult for
non-expert users to interpret, leading to a lack of transparency regarding the
collection, processing, and sharing of personal data. As concerns over online
privacy grow, it is essential to develop automated tools capable of analyzing
privacy policies and identifying potential risks. In this study, we explore the
potential of interactive graph visualizations to enhance user understanding of
privacy policies by representing policy terms as structured graph models. This
approach makes complex relationships more accessible and enables users to make
informed decisions about their personal data (RQ1). We also employ graph mining
algorithms to identify key themes, such as User Activity and Device
Information, using dimensionality reduction techniques like t-SNE and PCA to
assess clustering effectiveness. Our findings reveal that graph-based
clustering improves policy content interpretability. It highlights patterns in
user tracking and data sharing, which supports forensic investigations and
identifies regulatory non-compliance. This research advances AI-driven tools
for auditing privacy policies by integrating interactive visualizations with
graph mining. Enhanced transparency fosters accountability and trust.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.23866v3">Exploring Privacy and Security as Drivers for Environmental
  Sustainability in Cloud-Based Office Solutions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-06-30T13:58:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jason Kayembe, Iness Ben Guirat, Jan Tobias Mühlberg</p>
    <p><b>Summary:</b> In this paper, we explore the intersection of privacy, security, and
environmental sustainability in cloud-based office solutions, focusing on
quantifying user- and network-side energy use and associated carbon emissions.
We hypothesise that privacy-focused services are typically more
energy-efficient than those funded through data collection and advertising. To
evaluate this, we propose a framework that systematically measures
environmental costs based on energy usage and network data traffic during
well-defined, automated usage scenarios. To test our hypothesis, we first
analyse how underlying architectures and business models, such as monetisation
through personalised advertising, contribute to the environmental footprint of
these services. We then explore existing methodologies and tools for software
environmental impact assessment. We apply our framework to three mainstream
email services selected to reflect different privacy policies, from
ad-supported tracking-intensive models to privacy-focused designs: Microsoft
Outlook, Google Mail (Gmail), and Proton Mail. We extend this comparison to a
self-hosted email solution, evaluated with and without end-to-end encryption.
We show that the self-hosted solution, even with 14% of device energy and 15%
of emissions overheads from PGP encryption, remains the most energy-efficient,
saving up to 33% of emissions per session compared to Gmail. Among commercial
providers, Proton Mail is the most efficient, saving up to 0.1 gCO2 e per
session compared to Outlook, whose emissions can be further reduced by 2%
through ad-blocking.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.23622v1">Privacy-Preserving Federated Learning Scheme with Mitigating Model
  Poisoning Attacks: Vulnerabilities and Countermeasures</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-30T08:39:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiahui Wu, Fucai Luo, Tiecheng Sun, Haiyan Wang, Weizhe Zhang</p>
    <p><b>Summary:</b> The privacy-preserving federated learning schemes based on the setting of two
honest-but-curious and non-colluding servers offer promising solutions in terms
of security and efficiency. However, our investigation reveals that these
schemes still suffer from privacy leakage when considering model poisoning
attacks from malicious users. Specifically, we demonstrate that the
privacy-preserving computation process for defending against model poisoning
attacks inadvertently leaks privacy to one of the honest-but-curious servers,
enabling it to access users' gradients in plaintext. To address both privacy
leakage and model poisoning attacks, we propose an enhanced privacy-preserving
and Byzantine-robust federated learning (PBFL) scheme, comprising three
components: (1) a two-trapdoor fully homomorphic encryption (FHE) scheme to
bolster users' privacy protection; (2) a novel secure normalization judgment
method to preemptively thwart gradient poisoning; and (3) an innovative secure
cosine similarity measurement method for detecting model poisoning attacks
without compromising data privacy. Our scheme guarantees privacy preservation
and resilience against model poisoning attacks, even in scenarios with
heterogeneous, non-IID (Independently and Identically Distributed) datasets.
Theoretical analyses substantiate the security and efficiency of our scheme,
and extensive experiments corroborate the efficacy of our private attacks.
Furthermore, the experimental results demonstrate that our scheme accelerates
training speed while reducing communication overhead compared to the
state-of-the-art PBFL schemes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.23603v1">SoK: Semantic Privacy in Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-06-30T08:08:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Baihe Ma, Yanna Jiang, Xu Wang, Guangshen Yu, Qin Wang, Caijun Sun, Chen Li, Xuelei Qi, Ying He, Wei Ni, Ren Ping Liu</p>
    <p><b>Summary:</b> As Large Language Models (LLMs) are increasingly deployed in sensitive
domains, traditional data privacy measures prove inadequate for protecting
information that is implicit, contextual, or inferable - what we define as
semantic privacy. This Systematization of Knowledge (SoK) introduces a
lifecycle-centric framework to analyze how semantic privacy risks emerge across
input processing, pretraining, fine-tuning, and alignment stages of LLMs. We
categorize key attack vectors and assess how current defenses, such as
differential privacy, embedding encryption, edge computing, and unlearning,
address these threats. Our analysis reveals critical gaps in semantic-level
protection, especially against contextual inference and latent representation
leakage. We conclude by outlining open challenges, including quantifying
semantic leakage, protecting multimodal inputs, balancing de-identification
with generation quality, and ensuring transparency in privacy enforcement. This
work aims to inform future research on designing robust, semantically aware
privacy-preserving techniques for LLMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.23583v1">Detect \& Score: Privacy-Preserving Misbehaviour Detection and
  Contribution Evaluation in Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-30T07:40:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marvin Xhemrishi, Alexandre Graell i Amat, Balázs Pejó</p>
    <p><b>Summary:</b> Federated learning with secure aggregation enables private and collaborative
learning from decentralised data without leaking sensitive client information.
However, secure aggregation also complicates the detection of malicious client
behaviour and the evaluation of individual client contributions to the
learning. To address these challenges, QI (Pejo et al.) and FedGT (Xhemrishi et
al.) were proposed for contribution evaluation (CE) and misbehaviour detection
(MD), respectively. QI, however, lacks adequate MD accuracy due to its reliance
on the random selection of clients in each training round, while FedGT lacks
the CE ability. In this work, we combine the strengths of QI and FedGT to
achieve both robust MD and accurate CE. Our experiments demonstrate superior
performance compared to using either method independently.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.23481v1">Evaluation of Geolocation Capabilities of Multimodal Large Language
  Models and Analysis of Associated Privacy Risks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> 
  <p><b>Published on:</b> 2025-06-30T03:05:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xian Zhang, Xiang Cheng</p>
    <p><b>Summary:</b> Objectives: The rapid advancement of Multimodal Large Language Models (MLLMs)
has significantly enhanced their reasoning capabilities, enabling a wide range
of intelligent applications. However, these advancements also raise critical
concerns regarding privacy and ethics. MLLMs are now capable of inferring the
geographic location of images -- such as those shared on social media or
captured from street views -- based solely on visual content, thereby posing
serious risks of privacy invasion, including doxxing, surveillance, and other
security threats.
  Methods: This study provides a comprehensive analysis of existing geolocation
techniques based on MLLMs. It systematically reviews relevant litera-ture and
evaluates the performance of state-of-the-art visual reasoning models on
geolocation tasks, particularly in identifying the origins of street view
imagery.
  Results: Empirical evaluation reveals that the most advanced visual large
models can successfully localize the origin of street-level imagery with up to
$49\%$ accuracy within a 1-kilometer radius. This performance underscores the
models' powerful capacity to extract and utilize fine-grained geographic cues
from visual data.
  Conclusions: Building on these findings, the study identifies key visual
elements that contribute to suc-cessful geolocation, such as text,
architectural styles, and environmental features. Furthermore, it discusses the
potential privacy implications associated with MLLM-enabled geolocation and
discuss several technical and policy-based coun-termeasures to mitigate
associated risks. Our code and dataset are available at
https://github.com/zxyl1003/MLLM-Geolocation-Evaluation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.23014v1">Generating Privacy Stories From Software Documentation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-06-28T20:55:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wilder Baldwin, Shashank Chintakuntla, Shreyah Parajuli, Ali Pourghasemi, Ryan Shanz, Sepideh Ghanavati</p>
    <p><b>Summary:</b> Research shows that analysts and developers consider privacy as a security
concept or as an afterthought, which may lead to non-compliance and violation
of users' privacy. Most current approaches, however, focus on extracting legal
requirements from the regulations and evaluating the compliance of software and
processes with them. In this paper, we develop a novel approach based on
chain-of-thought prompting (CoT), in-context-learning (ICL), and Large Language
Models (LLMs) to extract privacy behaviors from various software documents
prior to and during software development, and then generate privacy
requirements in the format of user stories. Our results show that most commonly
used LLMs, such as GPT-4o and Llama 3, can identify privacy behaviors and
generate privacy user stories with F1 scores exceeding 0.8. We also show that
the performance of these models could be improved through parameter-tuning. Our
findings provide insight into using and optimizing LLMs for generating privacy
requirements given software documents created prior to or throughout the
software development lifecycle.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.22789v1">WavShape: Information-Theoretic Speech Representation Learning for Fair
  and Privacy-Aware Audio Processing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> 
  <p><b>Published on:</b> 2025-06-28T07:03:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Oguzhan Baser, Ahmet Ege Tanriverdi, Kaan Kale, Sandeep P. Chinchali, Sriram Vishwanath</p>
    <p><b>Summary:</b> Speech embeddings often retain sensitive attributes such as speaker identity,
accent, or demographic information, posing risks in biased model training and
privacy leakage. We propose WavShape, an information-theoretic speech
representation learning framework that optimizes embeddings for fairness and
privacy while preserving task-relevant information. We leverage mutual
information (MI) estimation using the Donsker-Varadhan formulation to guide an
MI-based encoder that systematically filters sensitive attributes while
maintaining speech content essential for downstream tasks. Experimental results
on three known datasets show that WavShape reduces MI between embeddings and
sensitive attributes by up to 81% while retaining 97% of task-relevant
information. By integrating information theory with self-supervised speech
models, this work advances the development of fair, privacy-aware, and
resource-efficient speech systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.22787v1">What's Privacy Good for? Measuring Privacy as a Shield from Harms due to
  Personal Data Use</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-06-28T07:00:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sri Harsha Gajavalli, Junichi Koizumi, Rakibul Hasan</p>
    <p><b>Summary:</b> We propose a harm-centric conceptualization of privacy that asks: What harms
from personal data use can privacy prevent? The motivation behind this research
is limitations in existing privacy frameworks (e.g., Contextual Integrity) to
capture or categorize many of the harms that arise from modern technology's use
of personal data. We operationalize this conceptualization in an online study
with 400 college and university students. Study participants indicated their
perceptions of different harms (e.g., manipulation, discrimination, and
harassment) that may arise when artificial intelligence-based algorithms infer
personal data (e.g., demographics, personality traits, and cognitive
disability) and use it to identify students who are likely to drop out of a
course or the best job candidate. The study includes 14 harms and six types of
personal data selected based on an extensive literature review.
  Comprehensive statistical analyses of the study data show that the 14 harms
are internally consistent and collectively represent a general notion of
privacy harms. The study data also surfaces nuanced perceptions of harms, both
across the contexts and participants' demographic factors. Based on these
results, we discuss how privacy can be improved equitably. Thus, this research
not only contributes to enhancing the understanding of privacy as a concept but
also provides practical guidance to improve privacy in the context of education
and employment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.22752v1">Privacy-Preserving Methods for Bug Severity Prediction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-06-28T04:40:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Havvanur Dervişoğlu, Ruşen Halepmollası, Elif Eyvaz</p>
    <p><b>Summary:</b> Bug severity prediction is a critical task in software engineering as it
enables more efficient resource allocation and prioritization in software
maintenance. While AI-based analyses and models significantly require access to
extensive datasets, industrial applications face challenges due to data-sharing
constraints and the limited availability of labeled data. In this study, we
investigate method-level bug severity prediction using source code metrics and
Large Language Models (LLMs) with two widely used datasets. We compare the
performance of models trained using centralized learning, federated learning,
and synthetic data generation. Our experimental results, obtained using two
widely recognized software defect datasets, indicate that models trained with
federated learning and synthetic data achieve comparable results to centrally
trained models without data sharing. Our finding highlights the potential of
privacy-preserving approaches such as federated learning and synthetic data
generation to enable effective bug severity prediction in industrial context
where data sharing is a major challenge.
  The source code and dataset are available at our GitHub repository:
https://github.com/drvshavva/EASE2025-Privacy-Preserving-Methods-for-Bug-Severity-Prediction.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.22727v1">Convergent Privacy Framework with Contractive GNN Layers for Multi-hop
  Aggregations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-28T02:17:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yu Zheng, Chenang Li, Zhou Li, Qingsong Wang</p>
    <p><b>Summary:</b> Differential privacy (DP) has been integrated into graph neural networks
(GNNs) to protect sensitive structural information, e.g., edges, nodes, and
associated features across various applications. A common approach is to
perturb the message-passing process, which forms the core of most GNN
architectures. However, existing methods typically incur a privacy cost that
grows linearly with the number of layers (Usenix Security'23), ultimately
requiring excessive noise to maintain a reasonable privacy level. This
limitation becomes particularly problematic when deep GNNs are necessary to
capture complex and long-range interactions in graphs. In this paper, we
theoretically establish that the privacy budget can converge with respect to
the number of layers by applying privacy amplification techniques to the
message-passing process, exploiting the contractive properties inherent to
standard GNN operations. Motivated by this analysis, we propose a simple yet
effective Contractive Graph Layer (CGL) that ensures the contractiveness
required for theoretical guarantees while preserving model utility. Our
framework, CARIBOU, supports both training and inference, equipped with a
contractive aggregation module, a privacy allocation module, and a privacy
auditing module. Experimental evaluations demonstrate that CARIBOU
significantly improves the privacy-utility trade-off and achieves superior
performance in privacy auditing tasks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.22606v1">A User-Centric, Privacy-Preserving, and Verifiable Ecosystem for
  Personal Data Management and Utilization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-27T20:05:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Osama Zafar, Mina Namazi, Yuqiao Xu, Youngjin Yoo, Erman Ayday</p>
    <p><b>Summary:</b> In the current paradigm of digital personalized services, the centralized
management of personal data raises significant privacy concerns, security
vulnerabilities, and diminished individual autonomy over sensitive information.
Despite their efficiency, traditional centralized architectures frequently fail
to satisfy rigorous privacy requirements and expose users to data breaches and
unauthorized access risks. This pressing challenge calls for a fundamental
paradigm shift in methodologies for collecting, storing, and utilizing personal
data across diverse sectors, including education, healthcare, and finance.
  This paper introduces a novel decentralized, privacy-preserving architecture
that handles heterogeneous personal information, ranging from educational
credentials to health records and financial data. Unlike traditional models,
our system grants users complete data ownership and control, allowing them to
selectively share information without compromising privacy. The architecture's
foundation comprises advanced privacy-enhancing technologies, including secure
enclaves and federated learning, enabling secure computation, verification, and
data sharing. The system supports diverse functionalities, including local
computation, model training, and privacy-preserving data sharing, while
ensuring data credibility and robust user privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.22342v1">A Framework for Multi-source Privacy Preserving Epidemic Analysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-06-27T15:52:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zihan Guan, Zhiyuan Zhao, Fengwei Tian, Dung Nguyen, Payel Bhattacharjee, Ravi Tandon, B. Aditya Prakash, Anil Vullikanti</p>
    <p><b>Summary:</b> It is now well understood that diverse datasets provide a lot of value in key
epidemiology and public health analyses, such as forecasting and nowcasting,
development of epidemic models, evaluation and design of interventions and
resource allocation. Some of these datasets are often sensitive, and need
adequate privacy protections. There are many models of privacy, but
Differential Privacy (DP) has become a de facto standard because of its strong
guarantees, without making models about adversaries. In this paper, we develop
a framework the integrates deep learning and epidemic models to simultaneously
perform epidemic forecasting and learning a mechanistic model of epidemic
spread, while incorporating multiple datasets for these analyses, including
some with DP guarantees. We demonstrate our framework using a realistic but
synthetic financial dataset with DP; such a dataset has not been used in such
epidemic analyses. We show that this dataset provides significant value in
forecasting and learning an epidemic model, even when used with DP guarantees.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.21998v1">INTACT: Compact Storage of Data Streams in Mobile Devices to Unlock User
  Privacy at the Edge</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2025-06-27T08:09:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rémy Raes, Olivier Ruas, Adrien Luxey-Bitri, Romain Rouvoy</p>
    <p><b>Summary:</b> Data streams produced by mobile devices, such as smartphones, offer highly
valuable sources of information to build ubiquitous services. Such data streams
are generally uploaded and centralized to be processed by third parties,
potentially exposing sensitive personal information. In this context, existing
protection mechanisms, such as Location Privacy Protection Mechanisms (LPPMs),
have been investigated. Alas, none of them have actually been implemented, nor
deployed in real-life, in mobile devices to enforce user privacy at the edge.
Moreover, the diversity of embedded sensors and the resulting data deluge makes
it impractical to provision such services directly on mobiles, due to their
constrained storage capacity, communication bandwidth and processing power.
This article reports on the FLI technique, which leverages a piece-wise linear
approximation technique to capture compact representations of data streams in
mobile devices. Beyond the FLI storage layer, we introduce Divide \& Stay, a
new privacy preservation technique to execute Points of Interest (POIs)
inference. Finally, we deploy both of them on Android and iOS as the INTACT
framework, making a concrete step towards enforcing privacy and trust in
ubiquitous computing systems.</p>
  </details>
</div>


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
  <h3><a href="http://arxiv.org/abs/2506.17336v2">Privacy-Preserving LLM Interaction with Socratic Chain-of-Thought
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
  <h3><a href="http://arxiv.org/abs/2506.15854v2">Privacy-Preserving in Connected and Autonomous Vehicles Through Vision
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
  <h3><a href="http://arxiv.org/abs/2506.22462v1">Privacy-aware IoT Fall Detection Services For Aging in Place</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-06-18T03:28:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abdallah Lakhdari, Jiajie Li, Amani Abusafia, Athman Bouguettaya</p>
    <p><b>Summary:</b> Fall detection is critical to support the growing elderly population,
projected to reach 2.1 billion by 2050. However, existing methods often face
data scarcity challenges or compromise privacy. We propose a novel IoT-based
Fall Detection as a Service (FDaaS) framework to assist the elderly in living
independently and safely by accurately detecting falls. We design a
service-oriented architecture that leverages Ultra-wideband (UWB) radar sensors
as an IoT health-sensing service, ensuring privacy and minimal intrusion. We
address the challenges of data scarcity by utilizing a Fall Detection
Generative Pre-trained Transformer (FD-GPT) that uses augmentation techniques.
We developed a protocol to collect a comprehensive dataset of the elderly daily
activities and fall events. This resulted in a real dataset that carefully
mimics the elderly's routine. We rigorously evaluate and compare various models
using this dataset. Experimental results show our approach achieves 90.72%
accuracy and 89.33% precision in distinguishing between fall events and regular
activities of daily living.</p>
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
  <h3><a href="http://arxiv.org/abs/2506.13972v2">Membership Inference Attacks as Privacy Tools: Reliability, Disparity
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
    <p><b>Authors:</b> Imdad Ullah, Najm Hassan, Tariq Ahamed Ahangar, Zawar Hussain Shah, Mehregan Mahdavi, Andrew Levula</p>
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
  <h3><a href="http://arxiv.org/abs/2506.12846v2">VFEFL: Privacy-Preserving Federated Learning against Malicious Clients
  via Verifiable Functional Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-06-15T13:38:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nina Cai, Jinguang Han, Weizhi Meng</p>
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

