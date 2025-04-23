
<h2>2025-04</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.16000v1">How Private is Your Attention? Bridging Privacy with In-Context Learning</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-04-22T16:05:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Soham Bonnerjee, Zhen Wei,  Yeon, Anna Asch, Sagnik Nandy, Promit Ghosal</p>
    <p><b>Summary:</b> In-context learning (ICL)-the ability of transformer-based models to perform
new tasks from examples provided at inference time-has emerged as a hallmark of
modern language models. While recent works have investigated the mechanisms
underlying ICL, its feasibility under formal privacy constraints remains
largely unexplored. In this paper, we propose a differentially private
pretraining algorithm for linear attention heads and present the first
theoretical analysis of the privacy-accuracy trade-off for ICL in linear
regression. Our results characterize the fundamental tension between
optimization and privacy-induced noise, formally capturing behaviors observed
in private training via iterative methods. Additionally, we show that our
method is robust to adversarial perturbations of training prompts, unlike
standard ridge regression. All theoretical findings are supported by extensive
simulations across diverse settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.15995v1">OPUS-VFL: Incentivizing Optimal Privacy-Utility Tradeoffs in Vertical
  Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-04-22T16:00:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sindhuja Madabushi, Ahmad Faraz Khan, Haider Ali, Jin-Hee Cho</p>
    <p><b>Summary:</b> Vertical Federated Learning (VFL) enables organizations with disjoint feature
spaces but shared user bases to collaboratively train models without sharing
raw data. However, existing VFL systems face critical limitations: they often
lack effective incentive mechanisms, struggle to balance privacy-utility
tradeoffs, and fail to accommodate clients with heterogeneous resource
capabilities. These challenges hinder meaningful participation, degrade model
performance, and limit practical deployment. To address these issues, we
propose OPUS-VFL, an Optimal Privacy-Utility tradeoff Strategy for VFL.
OPUS-VFL introduces a novel, privacy-aware incentive mechanism that rewards
clients based on a principled combination of model contribution, privacy
preservation, and resource investment. It employs a lightweight leave-one-out
(LOO) strategy to quantify feature importance per client, and integrates an
adaptive differential privacy mechanism that enables clients to dynamically
calibrate noise levels to optimize their individual utility. Our framework is
designed to be scalable, budget-balanced, and robust to inference and poisoning
attacks. Extensive experiments on benchmark datasets (MNIST, CIFAR-10, and
CIFAR-100) demonstrate that OPUS-VFL significantly outperforms state-of-the-art
VFL baselines in both efficiency and robustness. It reduces label inference
attack success rates by up to 20%, increases feature inference reconstruction
error (MSE) by over 30%, and achieves up to 25% higher incentives for clients
that contribute meaningfully while respecting privacy and cost constraints.
These results highlight the practicality and innovation of OPUS-VFL as a
secure, fair, and performance-driven solution for real-world VFL.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.15580v1">On the Price of Differential Privacy for Hierarchical Clustering</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-04-22T04:39:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chengyuan Deng, Jie Gao, Jalaj Upadhyay, Chen Wang, Samson Zhou</p>
    <p><b>Summary:</b> Hierarchical clustering is a fundamental unsupervised machine learning task
with the aim of organizing data into a hierarchy of clusters. Many applications
of hierarchical clustering involve sensitive user information, therefore
motivating recent studies on differentially private hierarchical clustering
under the rigorous framework of Dasgupta's objective. However, it has been
shown that any privacy-preserving algorithm under edge-level differential
privacy necessarily suffers a large error. To capture practical applications of
this problem, we focus on the weight privacy model, where each edge of the
input graph is at least unit weight. We present a novel algorithm in the weight
privacy model that shows significantly better approximation than known
impossibility results in the edge-level DP setting. In particular, our
algorithm achieves $O(\log^{1.5}n/\varepsilon)$ multiplicative error for
$\varepsilon$-DP and runs in polynomial time, where $n$ is the size of the
input graph, and the cost is never worse than the optimal additive error in
existing work. We complement our algorithm by showing if the unit-weight
constraint does not apply, the lower bound for weight-level DP hierarchical
clustering is essentially the same as the edge-level DP, i.e.
$\Omega(n^2/\varepsilon)$ additive error. As a result, we also obtain a new
lower bound of $\tilde{\Omega}(1/\varepsilon)$ additive error for balanced
sparsest cuts in the weight-level DP model, which may be of independent
interest. Finally, we evaluate our algorithm on synthetic and real-world
datasets. Our experimental results show that our algorithm performs well in
terms of extra cost and has good scalability to large graphs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.15525v1">Federated Latent Factor Learning for Recovering Wireless Sensor Networks
  Signal with Privacy-Preserving</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-04-22T02:01:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chengjun Yu, Yixin Ran, Yangyi Xia, Jia Wu, Xiaojing Liu</p>
    <p><b>Summary:</b> Wireless Sensor Networks (WSNs) are a cutting-edge domain in the field of
intelligent sensing. Due to sensor failures and energy-saving strategies, the
collected data often have massive missing data, hindering subsequent analysis
and decision-making. Although Latent Factor Learning (LFL) has been proven
effective in recovering missing data, it fails to sufficiently consider data
privacy protection. To address this issue, this paper innovatively proposes a
federated latent factor learning (FLFL) based spatial signal recovery (SSR)
model, named FLFL-SSR. Its main idea is two-fold: 1) it designs a sensor-level
federated learning framework, where each sensor uploads only gradient updates
instead of raw data to optimize the global model, and 2) it proposes a local
spatial sharing strategy, allowing sensors within the same spatial region to
share their latent feature vectors, capturing spatial correlations and
enhancing recovery accuracy. Experimental results on two real-world WSNs
datasets demonstrate that the proposed model outperforms existing federated
methods in terms of recovery performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.15233v1">A Review on Privacy in DAG-Based DLTs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-04-21T17:08:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mayank Raikwar</p>
    <p><b>Summary:</b> Directed Acyclic Graph (DAG)-based Distributed Ledger Technologies (DLTs)
have emerged as a promising solution to the scalability issues inherent in
traditional blockchains. However, amidst the focus on scalability, the crucial
aspect of privacy within DAG-based DLTs has been largely overlooked. This paper
seeks to address this gap by providing a comprehensive examination of privacy
notions and challenges within DAG-based DLTs. We delve into potential
methodologies to enhance privacy within these systems, while also analyzing the
associated hurdles and real-world implementations within state-of-the-art
DAG-based DLTs. By exploring these methodologies, we not only illuminate the
current landscape of privacy in DAG-based DLTs but also outline future research
directions in this evolving field.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.15090v1">Federated Latent Factor Model for Bias-Aware Recommendation with
  Privacy-Preserving</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-04-21T13:24:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Junxiang Gao, Yixin Ran, Jia Chen</p>
    <p><b>Summary:</b> A recommender system (RS) aims to provide users with personalized item
recommendations, enhancing their overall experience. Traditional RSs collect
and process all user data on a central server. However, this centralized
approach raises significant privacy concerns, as it increases the risk of data
breaches and privacy leakages, which are becoming increasingly unacceptable to
privacy-sensitive users. To address these privacy challenges, federated
learning has been integrated into RSs, ensuring that user data remains secure.
In centralized RSs, the issue of rating bias is effectively addressed by
jointly analyzing all users' raw interaction data. However, this becomes a
significant challenge in federated RSs, as raw data is no longer accessible due
to privacy-preserving constraints. To overcome this problem, we propose a
Federated Bias-Aware Latent Factor (FBALF) model. In FBALF, training bias is
explicitly incorporated into every local model's loss function, allowing for
the effective elimination of rating bias without compromising data privacy.
Extensive experiments conducted on three real-world datasets demonstrate that
FBALF achieves significantly higher recommendation accuracy compared to other
state-of-the-art federated RSs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.14993v1">Dual Utilization of Perturbation for Stream Data Publication under Local
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2025-04-21T09:51:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rong Du, Qingqing Ye, Yaxin Xiao, Liantong Yu, Yue Fu, Haibo Hu</p>
    <p><b>Summary:</b> Stream data from real-time distributed systems such as IoT, tele-health, and
crowdsourcing has become an important data source. However, the collection and
analysis of user-generated stream data raise privacy concerns due to the
potential exposure of sensitive information. To address these concerns, local
differential privacy (LDP) has emerged as a promising standard. Nevertheless,
applying LDP to stream data presents significant challenges, as stream data
often involves a large or even infinite number of values. Allocating a given
privacy budget across these data points would introduce overwhelming LDP noise
to the original stream data.
  Beyond existing approaches that merely use perturbed values for estimating
statistics, our design leverages them for both perturbation and estimation.
This dual utilization arises from a key observation: each user knows their own
ground truth and perturbed values, enabling a precise computation of the
deviation error caused by perturbation. By incorporating this deviation into
the perturbation process of subsequent values, the previous noise can be
calibrated. Following this insight, we introduce the Iterative Perturbation
Parameterization (IPP) method, which utilizes current perturbed results to
calibrate the subsequent perturbation process. To enhance the robustness of
calibration and reduce sensitivity, two algorithms, namely Accumulated
Perturbation Parameterization (APP) and Clipped Accumulated Perturbation
Parameterization (CAPP) are further developed. We prove that these three
algorithms satisfy $w$-event differential privacy while significantly improving
utility. Experimental results demonstrate that our techniques outperform
state-of-the-art LDP stream publishing solutions in terms of utility, while
retaining the same privacy guarantee.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.14959v1">ScaleGuard: Rational and Scalable Configuration Privacy Protection with
  Topology Expansion</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2025-04-21T08:38:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qianye Wang, Yuejie Wang, Yongting Chen, Guyue Liu</p>
    <p><b>Summary:</b> As networks grow in size and complexity, safeguarding sensitive data while
sharing configuration files is critical for network management and research.
Existing anonymization tools primarily hide fields like IP addresses or AS
numbers to mitigate direct data exposure. However, they often lack mechanisms
to preserve privacy around network scale, an increasingly sensitive aspect that
can reveal organizational size or resource distribution. We propose ScaleGuard,
which preserves network functional equivalence while adding fake routers and
hosts to conceal network scale, and generating complete router configurations
that resemble the originals. Our system introduces a graph embedding-based
expansion method and k-degree mapping anonymity, reducing unnecessary topology
modifications when adversaries only know the original degree sequence. For
routing repair, ScaleGuard designs a network repair framework combining SMT and
iterative methods, delivering stable performance under randomized link costs
and complex cross-protocol routing. Experiment results show that ScaleGuard
expands network scale effectively, providing consistent anonymization of
topology, scale, and routing, while achieving strong topological rationality,
configuration fidelity, and repairing efficiency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.14780v1">Delay-Angle Information Spoofing for Channel State Information-Free
  Location-Privacy Enhancement</a></h3>
  
  <p><b>Published on:</b> 2025-04-21T00:40:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jianxiu Li, Urbashi Mitra</p>
    <p><b>Summary:</b> In this paper, a delay-angle information spoofing (DAIS) strategy is proposed
to enhance the location privacy at the physical layer. More precisely, the
location-relevant delays and angles are artificially shifted without the aid of
channel state information (CSI) at the transmitter, such that the location
perceived by the eavesdropper is incorrect and distinct from the true one. By
leveraging the intrinsic structure of the wireless channel, a precoder is
designed to achieve DAIS while the legitimate localizer can remove the
obfuscation via securely receiving a modest amount of information, i.e., the
delay-angle shifts. A lower bound on eavesdropper's localization error is
derived, revealing that location privacy is enhanced not only due to estimation
error, but also by the geometric mismatch introduced by DAIS. Furthermore, the
lower bound is explicitly expressed as a function of the delay-angle shifts,
characterizing performance trends and providing the appropriate design of these
shift parameters. The statistical hardness of maliciously inferring the
delay-angle shifts by a single-antenna eavesdropper as well as the challenges
for a multi-antenna eavesdropper are investigated to assess the robustness of
the proposed DAIS strategy. Numerical results show that the proposed DAIS
strategy results in more than 15 dB performance degradation for the
eavesdropper as compared with that for the legitimate localizer at high
signal-to-noise ratios, and provides more effective location-privacy
enhancement than the prior art.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.14730v1">Optimal Additive Noise Mechanisms for Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2025-04-20T20:04:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Atefeh Gilani, Juan Felipe Gomez, Shahab Asoodeh, Flavio P. Calmon, Oliver Kosut, Lalitha Sankar</p>
    <p><b>Summary:</b> We propose a unified optimization framework for designing continuous and
discrete noise distributions that ensure differential privacy (DP) by
minimizing R\'enyi DP, a variant of DP, under a cost constraint. R\'enyi DP has
the advantage that by considering different values of the R\'enyi parameter
$\alpha$, we can tailor our optimization for any number of compositions. To
solve the optimization problem, we reduce it to a finite-dimensional convex
formulation and perform preconditioned gradient descent. The resulting noise
distributions are then compared to their Gaussian and Laplace counterparts.
Numerical results demonstrate that our optimized distributions are consistently
better, with significant improvements in $(\varepsilon, \delta)$-DP guarantees
in the moderate composition regimes, compared to Gaussian and Laplace
distributions with the same variance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.14368v1">Do You Really Need Public Data? Surrogate Public Data for Differential
  Privacy on Tabular Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-04-19T17:55:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shlomi Hod, Lucas Rosenblatt, Julia Stoyanovich</p>
    <p><b>Summary:</b> Differentially private (DP) machine learning often relies on the availability
of public data for tasks like privacy-utility trade-off estimation,
hyperparameter tuning, and pretraining. While public data assumptions may be
reasonable in text and image domains, they are less likely to hold for tabular
data due to tabular data heterogeneity across domains. We propose leveraging
powerful priors to address this limitation; specifically, we synthesize
realistic tabular data directly from schema-level specifications - such as
variable names, types, and permissible ranges - without ever accessing
sensitive records. To that end, this work introduces the notion of "surrogate"
public data - datasets generated independently of sensitive data, which consume
no privacy loss budget and are constructed solely from publicly available
schema or metadata. Surrogate public data are intended to encode plausible
statistical assumptions (informed by publicly available information) into a
dataset with many downstream uses in private mechanisms. We automate the
process of generating surrogate public data with large language models (LLMs);
in particular, we propose two methods: direct record generation as CSV files,
and automated structural causal model (SCM) construction for sampling records.
Through extensive experiments, we demonstrate that surrogate public tabular
data can effectively replace traditional public data when pretraining
differentially private tabular classifiers. To a lesser extent, surrogate
public data are also useful for hyperparameter tuning of DP synthetic data
generators, and for estimating the privacy-utility tradeoff.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.14301v1">Balancing Privacy and Action Performance: A Penalty-Driven Approach to
  Image Anonymization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Multimedia-5BC0EB">
  <p><b>Published on:</b> 2025-04-19T13:52:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nazia Aslam, Kamal Nasrollahi</p>
    <p><b>Summary:</b> The rapid development of video surveillance systems for object detection,
tracking, activity recognition, and anomaly detection has revolutionized our
day-to-day lives while setting alarms for privacy concerns. It isn't easy to
strike a balance between visual privacy and action recognition performance in
most computer vision models. Is it possible to safeguard privacy without
sacrificing performance? It poses a formidable challenge, as even minor privacy
enhancements can lead to substantial performance degradation. To address this
challenge, we propose a privacy-preserving image anonymization technique that
optimizes the anonymizer using penalties from the utility branch, ensuring
improved action recognition performance while minimally affecting privacy
leakage. This approach addresses the trade-off between minimizing privacy
leakage and maintaining high action performance. The proposed approach is
primarily designed to align with the regulatory standards of the EU AI Act and
GDPR, ensuring the protection of personally identifiable information while
maintaining action performance. To the best of our knowledge, we are the first
to introduce a feature-based penalty scheme that exclusively controls the
action features, allowing freedom to anonymize private attributes. Extensive
experiments were conducted to validate the effectiveness of the proposed
method. The results demonstrate that applying a penalty to anonymizer from
utility branch enhances action performance while maintaining nearly consistent
privacy leakage across different penalty settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.14208v1">FedCIA: Federated Collaborative Information Aggregation for
  Privacy-Preserving Recommendation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2025-04-19T06:59:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mingzhe Han, Dongsheng Li, Jiafeng Xia, Jiahao Liu, Hansu Gu, Peng Zhang, Ning Gu, Tun Lu</p>
    <p><b>Summary:</b> Recommendation algorithms rely on user historical interactions to deliver
personalized suggestions, which raises significant privacy concerns. Federated
recommendation algorithms tackle this issue by combining local model training
with server-side model aggregation, where most existing algorithms use a
uniform weighted summation to aggregate item embeddings from different client
models. This approach has three major limitations: 1) information loss during
aggregation, 2) failure to retain personalized local features, and 3)
incompatibility with parameter-free recommendation algorithms. To address these
limitations, we first review the development of recommendation algorithms and
recognize that their core function is to share collaborative information,
specifically the global relationship between users and items. With this
understanding, we propose a novel aggregation paradigm named collaborative
information aggregation, which focuses on sharing collaborative information
rather than item parameters. Based on this new paradigm, we introduce the
federated collaborative information aggregation (FedCIA) method for
privacy-preserving recommendation. This method requires each client to upload
item similarity matrices for aggregation, which allows clients to align their
local models without constraining embeddings to a unified vector space. As a
result, it mitigates information loss caused by direct summation, preserves the
personalized embedding distributions of individual clients, and supports the
aggregation of parameter-free models. Theoretical analysis and experimental
results on real-world datasets demonstrate the superior performance of FedCIA
compared with the state-of-the-art federated recommendation algorithms. Code is
available at https://github.com/Mingzhe-Han/FedCIA.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.13526v1">Multi-class Item Mining under Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-04-18T07:37:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yulian Mao, Qingqing Ye, Rong Du, Qi Wang, Kai Huang, Haibo Hu</p>
    <p><b>Summary:</b> Item mining, a fundamental task for collecting statistical data from users,
has raised increasing privacy concerns. To address these concerns, local
differential privacy (LDP) was proposed as a privacy-preserving technique.
Existing LDP item mining mechanisms primarily concentrate on global statistics,
i.e., those from the entire dataset. Nevertheless, they fall short of
user-tailored tasks such as personalized recommendations, whereas classwise
statistics can improve task accuracy with fine-grained information. Meanwhile,
the introduction of class labels brings new challenges. Label perturbation may
result in invalid items for aggregation. To this end, we propose frameworks for
multi-class item mining, along with two mechanisms: validity perturbation to
reduce the impact of invalid data, and correlated perturbation to preserve the
relationship between labels and items. We also apply these optimized methods to
two multi-class item mining queries: frequency estimation and top-$k$ item
mining. Through theoretical analysis and extensive experiments, we verify the
effectiveness and superiority of these methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.13267v1">Leveraging Functional Encryption and Deep Learning for
  Privacy-Preserving Traffic Forecasting</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36"> 
  <p><b>Published on:</b> 2025-04-17T18:21:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Isaac Adom, Mohammmad Iqbal Hossain, Hassan Mahmoud, Ahmad Alsharif, Mahmoud Nabil Mahmoud, Yang Xiao</p>
    <p><b>Summary:</b> Over the past few years, traffic congestion has continuously plagued the
nation's transportation system creating several negative impacts including
longer travel times, increased pollution rates, and higher collision risks. To
overcome these challenges, Intelligent Transportation Systems (ITS) aim to
improve mobility and vehicular systems, ensuring higher levels of safety by
utilizing cutting-edge technologies, sophisticated sensing capabilities, and
innovative algorithms. Drivers' participatory sensing, current/future location
reporting, and machine learning algorithms have considerably improved real-time
congestion monitoring and future traffic management. However, each driver's
sensitive spatiotemporal location information can create serious privacy
concerns. To address these challenges, we propose in this paper a secure,
privacy-preserving location reporting and traffic forecasting system that
guarantees privacy protection of driver data while maintaining high traffic
forecasting accuracy. Our novel k-anonymity scheme utilizes functional
encryption to aggregate encrypted location information submitted by drivers
while ensuring the privacy of driver location data. Additionally, using the
aggregated encrypted location information as input, this research proposes a
deep learning model that incorporates a Convolutional-Long Short-Term Memory
(Conv-LSTM) module to capture spatial and short-term temporal features and a
Bidirectional Long Short-Term Memory (Bi-LSTM) module to recover long-term
periodic patterns for traffic forecasting. With extensive evaluation on real
datasets, we demonstrate the effectiveness of the proposed scheme with less
than 10% mean absolute error for a 60-minute forecasting horizon, all while
protecting driver privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.12931v1">Explainable AI in Usable Privacy and Security: Challenges and
  Opportunities</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-04-17T13:28:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vincent Freiberger, Arthur Fleig, Erik Buchmann</p>
    <p><b>Summary:</b> Large Language Models (LLMs) are increasingly being used for automated
evaluations and explaining them. However, concerns about explanation quality,
consistency, and hallucinations remain open research challenges, particularly
in high-stakes contexts like privacy and security, where user trust and
decision-making are at stake. In this paper, we investigate these issues in the
context of PRISMe, an interactive privacy policy assessment tool that leverages
LLMs to evaluate and explain website privacy policies. Based on a prior user
study with 22 participants, we identify key concerns regarding LLM judgment
transparency, consistency, and faithfulness, as well as variations in user
preferences for explanation detail and engagement. We discuss potential
strategies to mitigate these concerns, including structured evaluation
criteria, uncertainty estimation, and retrieval-augmented generation (RAG). We
identify a need for adaptive explanation strategies tailored to different user
profiles for LLM-as-a-judge. Our goal is to showcase the application area of
usable privacy and security to be promising for Human-Centered Explainable AI
(HCXAI) to make an impact.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.12747v1">Privacy Protection Against Personalized Text-to-Image Synthesis via
  Cross-image Consistency Constraints</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-04-17T08:39:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guanyu Wang, Kailong Wang, Yihao Huang, Mingyi Zhou, Zhang Qing cnwatcher, Geguang Pu, Li Li</p>
    <p><b>Summary:</b> The rapid advancement of diffusion models and personalization techniques has
made it possible to recreate individual portraits from just a few publicly
available images. While such capabilities empower various creative
applications, they also introduce serious privacy concerns, as adversaries can
exploit them to generate highly realistic impersonations. To counter these
threats, anti-personalization methods have been proposed, which add adversarial
perturbations to published images to disrupt the training of personalization
models. However, existing approaches largely overlook the intrinsic multi-image
nature of personalization and instead adopt a naive strategy of applying
perturbations independently, as commonly done in single-image settings. This
neglects the opportunity to leverage inter-image relationships for stronger
privacy protection. Therefore, we advocate for a group-level perspective on
privacy protection against personalization. Specifically, we introduce
Cross-image Anti-Personalization (CAP), a novel framework that enhances
resistance to personalization by enforcing style consistency across perturbed
images. Furthermore, we develop a dynamic ratio adjustment strategy that
adaptively balances the impact of the consistency loss throughout the attack
iterations. Extensive experiments on the classical CelebHQ and VGGFace2
benchmarks show that CAP substantially improves existing methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.12681v1">GRAIL: Gradient-Based Adaptive Unlearning for Privacy and Copyright in
  LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-04-17T06:16:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kun-Woo Kim, Ji-Hoon Park, Ju-Min Han, Seong-Whan Lee</p>
    <p><b>Summary:</b> Large Language Models (LLMs) trained on extensive datasets often learn
sensitive information, which raises significant social and legal concerns under
principles such as the "Right to be forgotten." Retraining entire models from
scratch to remove undesired information is both costly and impractical.
Furthermore, existing single-domain unlearning methods fail to address
multi-domain scenarios, where knowledge is interwoven across domains such as
privacy and copyright, creating overlapping representations that lead to
excessive knowledge removal or degraded performance. To tackle these issues, we
propose GRAIL (GRadient-based AdaptIve unLearning), a novel multi-domain
unlearning framework. GRAIL leverages gradient information from multiple
domains to precisely distinguish the unlearning scope from the retention scope,
and applies an adaptive parameter-wise localization strategy to selectively
remove targeted knowledge while preserving critical parameters for each domain.
Experimental results on unlearning benchmarks show that GRAIL achieves
unlearning success on par with the existing approaches, while also
demonstrating up to 17% stronger knowledge retention success compared to the
previous state-of-art method. Our findings establish a new paradigm for
effectively managing and regulating sensitive information in large-scale
pre-trained language models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.12623v1">Privacy-Preserving CNN Training with Transfer Learning: Two Hidden
  Layers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-04-17T03:58:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> John Chiang</p>
    <p><b>Summary:</b> In this paper, we present the demonstration of training a four-layer neural
network entirely using fully homomorphic encryption (FHE), supporting both
single-output and multi-output classification tasks in a non-interactive
setting. A key contribution of our work is identifying that replacing
\textit{Softmax} with \textit{Sigmoid}, in conjunction with the Binary
Cross-Entropy (BCE) loss function, provides an effective and scalable solution
for homomorphic classification. Moreover, we show that the BCE loss function,
originally designed for multi-output tasks, naturally extends to the
multi-class setting, thereby enabling broader applicability. We also highlight
the limitations of prior loss functions such as the SLE loss and the one
proposed in the 2019 CVPR Workshop, both of which suffer from vanishing
gradients as network depth increases. To address the challenges posed by
large-scale encrypted data, we further introduce an improved version of the
previously proposed data encoding scheme, \textit{Double Volley Revolver},
which achieves a better trade-off between computational and memory efficiency,
making FHE-based neural network training more practical. The complete, runnable
C++ code to implement our work can be found at:
\href{https://github.com/petitioner/ML.NNtraining}{$\texttt{https://github.com/petitioner/ML.NNtraining}$}.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.12552v1">Privacy-Preserving Operating Room Workflow Analysis using Digital Twins</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-04-17T00:46:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alejandra Perez, Han Zhang, Yu-Chun Ku, Lalithkumar Seenivasan, Roger Soberanis, Jose L. Porras, Richard Day, Jeff Jopling, Peter Najjar, Mathias Unberath</p>
    <p><b>Summary:</b> Purpose: The operating room (OR) is a complex environment where optimizing
workflows is critical to reduce costs and improve patient outcomes. The use of
computer vision approaches for the automatic recognition of perioperative
events enables identification of bottlenecks for OR optimization. However,
privacy concerns limit the use of computer vision for automated event detection
from OR videos, which makes privacy-preserving approaches needed for OR
workflow analysis. Methods: We propose a two-stage pipeline for
privacy-preserving OR video analysis and event detection. In the first stage,
we leverage vision foundation models for depth estimation and semantic
segmentation to generate de-identified Digital Twins (DT) of the OR from
conventional RGB videos. In the second stage, we employ the SafeOR model, a
fused two-stream approach that processes segmentation masks and depth maps for
OR event detection. We evaluate this method on an internal dataset of 38
simulated surgical trials with five event classes. Results: Our results
indicate that this DT-based approach to the OR event detection model achieves
performance on par and sometimes even better than raw RGB video-based models on
detecting OR events. Conclusion: DTs enable privacy-preserving OR workflow
analysis, facilitating the sharing of de-identified data across institutions
and they can potentially enhance model generalizability by mitigating
domain-specific appearance differences.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.12520v1">Interpreting Network Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> 
  <p><b>Published on:</b> 2025-04-16T22:45:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jonathan Hehir, Xiaoyue Niu, Aleksandra Slavkovic</p>
    <p><b>Summary:</b> How do we interpret the differential privacy (DP) guarantee for network data?
We take a deep dive into a popular form of network DP ($\varepsilon$--edge DP)
to find that many of its common interpretations are flawed. Drawing on prior
work for privacy with correlated data, we interpret DP through the lens of
adversarial hypothesis testing and demonstrate a gap between the pairs of
hypotheses actually protected under DP (tests of complete networks) and the
sorts of hypotheses implied to be protected by common claims (tests of
individual edges). We demonstrate some conditions under which this gap can be
bridged, while leaving some questions open. While some discussion is specific
to edge DP, we offer selected results in terms of abstract DP definitions and
provide discussion of the implications for other forms of network DP.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.12129v1">Anti-Aesthetics: Protecting Facial Privacy against Customized
  Text-to-Image Synthesis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-04-16T14:44:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Songping Wang, Yueming Lyu, Shiqi Liu, Ning Li, Tong Tong, Hao Sun, Caifeng Shan</p>
    <p><b>Summary:</b> The rise of customized diffusion models has spurred a boom in personalized
visual content creation, but also poses risks of malicious misuse, severely
threatening personal privacy and copyright protection. Some studies show that
the aesthetic properties of images are highly positively correlated with human
perception of image quality. Inspired by this, we approach the problem from a
novel and intriguing aesthetic perspective to degrade the generation quality of
maliciously customized models, thereby achieving better protection of facial
identity. Specifically, we propose a Hierarchical Anti-Aesthetic (HAA)
framework to fully explore aesthetic cues, which consists of two key branches:
1) Global Anti-Aesthetics: By establishing a global anti-aesthetic reward
mechanism and a global anti-aesthetic loss, it can degrade the overall
aesthetics of the generated content; 2) Local Anti-Aesthetics: A local
anti-aesthetic reward mechanism and a local anti-aesthetic loss are designed to
guide adversarial perturbations to disrupt local facial identity. By seamlessly
integrating both branches, our HAA effectively achieves the goal of
anti-aesthetics from a global to a local level during customized generation.
Extensive experiments show that HAA outperforms existing SOTA methods largely
in identity removal, providing a powerful tool for protecting facial privacy
and copyright.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.11860v1">From Data Behavior to Code Analysis: A Multimodal Study on Security and
  Privacy Challenges in Blockchain-Based DApp</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-04-16T08:30:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haoyang Sun, Yishun Wang, Xiaoqi Li</p>
    <p><b>Summary:</b> The recent proliferation of blockchain-based decentralized applications
(DApp) has catalyzed transformative advancements in distributed systems, with
extensive deployments observed across financial, entertainment, media, and
cybersecurity domains. These trustless architectures, characterized by their
decentralized nature and elimination of third-party intermediaries, have
garnered substantial institutional attention. Consequently, the escalating
security challenges confronting DApp demand rigorous scholarly investigation.
This study initiates with a systematic analysis of behavioral patterns derived
from empirical DApp datasets, establishing foundational insights for subsequent
methodological developments. The principal security vulnerabilities in
Ethereum-based smart contracts developed via Solidity are then critically
examined. Specifically, reentrancy vulnerability attacks are addressed by
formally representing contract logic using highly expressive code fragments.
This enables precise source code-level detection via bidirectional long
short-term memory networks with attention mechanisms (BLSTM-ATT). Regarding
privacy preservation challenges, contemporary solutions are evaluated through
dual analytical lenses: identity privacy preservation and transaction anonymity
enhancement, while proposing future research trajectories in cryptographic
obfuscation techniques.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.11793v3">Selective Attention Federated Learning: Improving Privacy and Efficiency
  for Clinical Text Classification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-04-16T05:59:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yue Li, Lihong Zhang</p>
    <p><b>Summary:</b> Federated Learning (FL) faces major challenges regarding communication
overhead and model privacy when training large language models (LLMs),
especially in healthcare applications. To address these, we introduce Selective
Attention Federated Learning (SAFL), a novel approach that dynamically
fine-tunes only those transformer layers identified as attention-critical. By
employing attention patterns to determine layer importance, SAFL significantly
reduces communication bandwidth and enhances differential privacy resilience.
Evaluations on clinical NLP benchmarks (i2b2 Clinical Concept Extraction and
MIMIC-III discharge summaries) demonstrate that SAFL achieves competitive
performance with centralized models while substantially improving communication
efficiency and privacy preservation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.11429v1">Improving Statistical Privacy by Subsampling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-04-15T17:40:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dennis Breutigam, Rüdiger Reischuk</p>
    <p><b>Summary:</b> Differential privacy (DP) considers a scenario, where an adversary has almost
complete information about the entries of a database This worst-case assumption
is likely to overestimate the privacy thread for an individual in real life.
Statistical privacy (SP) denotes a setting where only the distribution of the
database entries is known to an adversary, but not their exact values. In this
case one has to analyze the interaction between noiseless privacy based on the
entropy of distributions and privacy mechanisms that distort the answers of
queries, which can be quite complex.
  A privacy mechanism often used is to take samples of the data for answering a
query. This paper proves precise bounds how much different methods of sampling
increase privacy in the statistical setting with respect to database size and
sampling rate. They allow us to deduce when and how much sampling provides an
improvement and how far this depends on the privacy parameter {\epsilon}. To
perform these investigations we develop a framework to model sampling
techniques.
  For the DP setting tradeoff functions have been proposed as a finer measure
for privacy compared to ({\epsilon},{\delta})-pairs. We apply these tools to
statistical privacy with subsampling to get a comparable characterization</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.11511v1">Position Paper: Rethinking Privacy in RL for Sequential Decision-making
  in the Age of LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-04-15T10:45:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Flint Xiaofeng Fan, Cheston Tan, Roger Wattenhofer, Yew-Soon Ong</p>
    <p><b>Summary:</b> The rise of reinforcement learning (RL) in critical real-world applications
demands a fundamental rethinking of privacy in AI systems. Traditional privacy
frameworks, designed to protect isolated data points, fall short for sequential
decision-making systems where sensitive information emerges from temporal
patterns, behavioral strategies, and collaborative dynamics. Modern RL
paradigms, such as federated RL (FedRL) and RL with human feedback (RLHF) in
large language models (LLMs), exacerbate these challenges by introducing
complex, interactive, and context-dependent learning environments that
traditional methods do not address. In this position paper, we argue for a new
privacy paradigm built on four core principles: multi-scale protection,
behavioral pattern protection, collaborative privacy preservation, and
context-aware adaptation. These principles expose inherent tensions between
privacy, utility, and interpretability that must be navigated as RL systems
become more pervasive in high-stakes domains like healthcare, autonomous
vehicles, and decision support systems powered by LLMs. To tackle these
challenges, we call for the development of new theoretical frameworks,
practical mechanisms, and rigorous evaluation methodologies that collectively
enable effective privacy protection in sequential decision-making systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2504.10698v1">Optimising Intrusion Detection Systems in Cloud-Edge Continuum with
  Knowledge Distillation for Privacy-Preserving and Efficient Communication</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-04-14T20:45:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Soad Almabdy, Amjad Ullah</p>
    <p><b>Summary:</b> The growth of the Internet of Things has amplified the need for secure data
interactions in cloud-edge ecosystems, where sensitive information is
constantly processed across various system layers. Intrusion detection systems
are commonly used to protect such environments from malicious attacks.
Recently, Federated Learning has emerged as an effective solution for
implementing intrusion detection systems, owing to its decentralised
architecture that avoids sharing raw data with a central server, thereby
enhancing data privacy. Despite its benefits, Federated Learning faces
criticism for high communication overhead from frequent model updates,
especially in large-scale Cloud-Edge infrastructures. This paper explores
Knowledge Distillation to reduce communication overhead in Cloud-Edge intrusion
detection while preserving accuracy and data privacy. Experiments show
significant improvements over state-of-the-art methods.</p>
  </details>
</div>


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
  <h3><a href="http://arxiv.org/abs/2504.10267v2">Trade-offs in Privacy-Preserving Eye Tracking through Iris Obfuscation:
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
  <h3><a href="http://arxiv.org/abs/2504.09517v2">RoboComm: A DID-based scalable and privacy-preserving Robot-to-Robot
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
  <h3><a href="http://arxiv.org/abs/2504.07414v3">A Unified Framework and Efficient Computation for Privacy Amplification
  via Shuffling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-04-10T03:11:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pengcheng Su, Haibo Cheng, Ping Wang</p>
    <p><b>Summary:</b> The shuffle model offers significant privacy amplification over local
differential privacy (LDP), enabling improved privacy-utility trade-offs. To
analyze and quantify this amplification effect, two primary frameworks have
been proposed: the \textit{privacy blanket} (Balle et al., CRYPTO 2019) and the
\textit{clone paradigm}, which includes both the \textit{standard clone} and
\textit{stronger clone} (Feldman et al., FOCS 2021; SODA 2023). All of these
approaches are grounded in decomposing the behavior of local randomizers.
  In this work, we present a unified perspective--termed the \textit{general
clone paradigm}--that captures all decomposition-based analyses. We identify
the optimal decomposition within this framework and design a simple yet
efficient algorithm based on the Fast Fourier Transform (FFT) to compute tight
privacy amplification bounds. Empirical results show that our computed upper
bounds nearly match the corresponding lower bounds, demonstrating the accuracy
and tightness of our method.
  Furthermore, we apply our algorithm to derive optimal privacy amplification
bounds for both joint composition and parallel composition of LDP mechanisms in
the shuffle model.</p>
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

