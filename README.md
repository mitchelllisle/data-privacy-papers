
<h2>2025-08</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.20736v1">Leveraging Semantic Triples for Private Document Generation with Local
  Differential Privacy Guarantees</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-08-28T12:59:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stephen Meisenbacher, Maulik Chevli, Florian Matthes</p>
    <p><b>Summary:</b> Many works at the intersection of Differential Privacy (DP) in Natural
Language Processing aim to protect privacy by transforming texts under DP
guarantees. This can be performed in a variety of ways, from word perturbations
to full document rewriting, and most often under local DP. Here, an input text
must be made indistinguishable from any other potential text, within some bound
governed by the privacy parameter $\varepsilon$. Such a guarantee is quite
demanding, and recent works show that privatizing texts under local DP can only
be done reasonably under very high $\varepsilon$ values. Addressing this
challenge, we introduce DP-ST, which leverages semantic triples for
neighborhood-aware private document generation under local DP guarantees.
Through the evaluation of our method, we demonstrate the effectiveness of the
divide-and-conquer paradigm, particularly when limiting the DP notion (and
privacy guarantees) to that of a privatization neighborhood. When combined with
LLM post-processing, our method allows for coherent text generation even at
lower $\varepsilon$ values, while still balancing privacy and utility. These
findings highlight the importance of coherence in achieving balanced
privatization outputs at reasonable $\varepsilon$ levels.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.20613v1">Revisiting the Privacy Risks of Split Inference: A GAN-Based Data
  Reconstruction Attack via Progressive Feature Optimization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-28T10:00:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yixiang Qiu, Yanhan Liu, Hongyao Yu, Hao Fang, Bin Chen, Shu-Tao Xia, Ke Xu</p>
    <p><b>Summary:</b> The growing complexity of Deep Neural Networks (DNNs) has led to the adoption
of Split Inference (SI), a collaborative paradigm that partitions computation
between edge devices and the cloud to reduce latency and protect user privacy.
However, recent advances in Data Reconstruction Attacks (DRAs) reveal that
intermediate features exchanged in SI can be exploited to recover sensitive
input data, posing significant privacy risks. Existing DRAs are typically
effective only on shallow models and fail to fully leverage semantic priors,
limiting their reconstruction quality and generalizability across datasets and
model architectures. In this paper, we propose a novel GAN-based DRA framework
with Progressive Feature Optimization (PFO), which decomposes the generator
into hierarchical blocks and incrementally refines intermediate representations
to enhance the semantic fidelity of reconstructed images. To stabilize the
optimization and improve image realism, we introduce an L1-ball constraint
during reconstruction. Extensive experiments show that our method outperforms
prior attacks by a large margin, especially in high-resolution scenarios,
out-of-distribution settings, and against deeper and more complex DNNs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.20250v1">Efficient and Privacy-Protecting Background Removal for 2D Video
  Streaming using iPhone 15 Pro Max LiDAR</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Multimedia-5BC0EB">  
  <p><b>Published on:</b> 2025-08-27T20:14:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jessica Kinnevan, Naifa Alqahtani, Toral Chauhan</p>
    <p><b>Summary:</b> Light Detection and Ranging (LiDAR) technology in consumer-grade mobile
devices can be used as a replacement for traditional background removal and
compositing techniques. Unlike approaches such as chroma keying and trained AI
models, LiDAR's depth information is independent of subject lighting, and
performs equally well in low-light and well-lit environments. We integrate the
LiDAR and color cameras on the iPhone 15 Pro Max with GPU-based image
processing. We use Apple's SwiftUI and Swift frameworks for user interface and
backend development, and Metal Shader Language (MSL) for realtime image
enhancement at the standard iPhone streaming frame rate of 60 frames per
second. The only meaningful limitations of the technology are the streaming
bandwidth of the depth data, which currently reduces the depth map resolution
to 320x240, and any pre-existing limitations of the LiDAR IR laser to reflect
accurate depth from some materials. If the LiDAR resolution on a mobile device
like the iPhone can be improved to match the color image resolution, LiDAR
could feasibly become the preeminent method of background removal for video
applications and photography.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.19640v1">Optimal Cox regression under federated differential privacy:
  coefficients and cumulative hazards</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">  
  <p><b>Published on:</b> 2025-08-27T07:29:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Elly K. H. Hung, Yi Yu</p>
    <p><b>Summary:</b> We study two foundational problems in distributed survival analysis:
estimating Cox regression coefficients and cumulative hazard functions, under
federated differential privacy constraints, allowing for heterogeneous
per-sever sample sizes and privacy budgets. To quantify the fundamental cost of
privacy, we derive minimax lower bounds along with matching (up to
poly-logarithmic factors) upper bounds. In particular, to estimate the
cumulative hazard function, we design a private tree-based algorithm for
nonparametric integral estimation. Our results reveal server-level phase
transitions between the private and non-private rates, as well as the reduced
estimation accuracy from imposing privacy constraints on distributed subsets of
data.
  To address scenarios with partially public information, we also consider a
relaxed differential privacy framework and provide a corresponding minimax
analysis. To our knowledge, this is the first treatment of partially public
data in survival analysis, and it establishes a no-gain in accuracy phenomenon.
Finally, we conduct extensive numerical experiments, with an accompanying R
package FDPCox, validating our theoretical findings. These experiments also
include a fully-interactive algorithm with tighter privacy composition, which
demonstrates improved estimation accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.19493v1">Mind the Third Eye! Benchmarking Privacy Awareness in MLLM-powered
  Smartphone Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-08-27T00:41:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhixin Lin, Jungang Li, Shidong Pan, Yibo Shi, Yue Yao, Dongliang Xu</p>
    <p><b>Summary:</b> Smartphones bring significant convenience to users but also enable devices to
extensively record various types of personal information. Existing smartphone
agents powered by Multimodal Large Language Models (MLLMs) have achieved
remarkable performance in automating different tasks. However, as the cost,
these agents are granted substantial access to sensitive users' personal
information during this operation. To gain a thorough understanding of the
privacy awareness of these agents, we present the first large-scale benchmark
encompassing 7,138 scenarios to the best of our knowledge. In addition, for
privacy context in scenarios, we annotate its type (e.g., Account Credentials),
sensitivity level, and location. We then carefully benchmark seven available
mainstream smartphone agents. Our results demonstrate that almost all
benchmarked agents show unsatisfying privacy awareness (RA), with performance
remaining below 60% even with explicit hints. Overall, closed-source agents
show better privacy ability than open-source ones, and Gemini 2.0-flash
achieves the best, achieving an RA of 67%. We also find that the agents'
privacy detection capability is highly related to scenario sensitivity level,
i.e., the scenario with a higher sensitivity level is typically more
identifiable. We hope the findings enlighten the research community to rethink
the unbalanced utility-privacy tradeoff about smartphone agents. Our code and
benchmark are available at https://zhixin-l.github.io/SAPA-Bench.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.19458v1">The Sample Complexity of Membership Inference and Privacy Auditing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2025-08-26T22:19:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mahdi Haghifam, Adam Smith, Jonathan Ullman</p>
    <p><b>Summary:</b> A membership-inference attack gets the output of a learning algorithm, and a
target individual, and tries to determine whether this individual is a member
of the training data or an independent sample from the same distribution. A
successful membership-inference attack typically requires the attacker to have
some knowledge about the distribution that the training data was sampled from,
and this knowledge is often captured through a set of independent reference
samples from that distribution. In this work we study how much information the
attacker needs for membership inference by investigating the sample
complexity-the minimum number of reference samples required-for a successful
attack. We study this question in the fundamental setting of Gaussian mean
estimation where the learning algorithm is given $n$ samples from a Gaussian
distribution $\mathcal{N}(\mu,\Sigma)$ in $d$ dimensions, and tries to estimate
$\hat\mu$ up to some error $\mathbb{E}[\|\hat \mu - \mu\|^2_{\Sigma}]\leq
\rho^2 d$. Our result shows that for membership inference in this setting,
$\Omega(n + n^2 \rho^2)$ samples can be necessary to carry out any attack that
competes with a fully informed attacker. Our result is the first to show that
the attacker sometimes needs many more samples than the training algorithm uses
to train the model. This result has significant implications for practice, as
all attacks used in practice have a restricted form that uses $O(n)$ samples
and cannot benefit from $\omega(n)$ samples. Thus, these attacks may be
underestimating the possibility of membership inference, and better attacks may
be possible when information about the distribution is easy to obtain.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.19345v1">Privacy-Preserving Distributed Control for a Networked Battery Energy
  Storage System</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2025-08-26T18:06:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mihitha Maithripala, Zongli Lin</p>
    <p><b>Summary:</b> The increasing deployment of distributed Battery Energy Storage Systems
(BESSs) in modern power grids necessitates effective coordination strategies to
ensure state-of-charge (SoC) balancing and accurate power delivery. While
distributed control frameworks offer scalability and resilience, they also
raise significant privacy concerns due to the need for inter-agent information
exchange. This paper presents a novel privacy-preserving distributed control
algorithm for SoC balancing in a networked BESS. The proposed framework
includes distributed power allocation law that is designed based on two
privacy-preserving distributed estimators, one for the average unit state and
the other for the average desired power. The average unit state estimator is
designed via the state decomposition method without disclosing sensitive
internal states. The proposed power allocation law based on these estimators
ensures asymptotic SoC balancing and global power delivery while safeguarding
agent privacy from external eavesdroppers. The effectiveness and
privacy-preserving properties of the proposed control strategy are demonstrated
through simulation results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.19115v1">SecureV2X: An Efficient and Privacy-Preserving System for
  Vehicle-to-Everything (V2X) Applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> 
  <p><b>Published on:</b> 2025-08-26T15:17:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joshua Lee, Ali Arastehfard, Weiran Liu, Xuegang Ban, Yuan Hong</p>
    <p><b>Summary:</b> Autonomous driving and V2X technologies have developed rapidly in the past
decade, leading to improved safety and efficiency in modern transportation.
These systems interact with extensive networks of vehicles, roadside
infrastructure, and cloud resources to support their machine learning
capabilities. However, the widespread use of machine learning in V2X systems
raises issues over the privacy of the data involved. This is particularly
concerning for smart-transit and driver safety applications which can
implicitly reveal user locations or explicitly disclose medical data such as
EEG signals. To resolve these issues, we propose SecureV2X, a scalable,
multi-agent system for secure neural network inferences deployed between the
server and each vehicle. Under this setting, we study two multi-agent V2X
applications: secure drowsiness detection, and secure red-light violation
detection. Our system achieves strong performance relative to baselines, and
scales efficiently to support a large number of secure computation interactions
simultaneously. For instance, SecureV2X is $9.4 \times$ faster, requires
$143\times$ fewer computational rounds, and involves $16.6\times$ less
communication on drowsiness detection compared to other secure systems.
Moreover, it achieves a runtime nearly $100\times$ faster than state-of-the-art
benchmarks in object detection tasks for red light violation detection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.18976v1">The Double-edged Sword of LLM-based Data Reconstruction: Understanding
  and Mitigating Contextual Vulnerability in Word-level Differential Privacy
  Text Sanitization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-08-26T12:22:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stephen Meisenbacher, Alexandra Klymenko, Andreea-Elena Bodea, Florian Matthes</p>
    <p><b>Summary:</b> Differentially private text sanitization refers to the process of privatizing
texts under the framework of Differential Privacy (DP), providing provable
privacy guarantees while also empirically defending against adversaries seeking
to harm privacy. Despite their simplicity, DP text sanitization methods
operating at the word level exhibit a number of shortcomings, among them the
tendency to leave contextual clues from the original texts due to randomization
during sanitization $\unicode{x2013}$ this we refer to as $\textit{contextual
vulnerability}$. Given the powerful contextual understanding and inference
capabilities of Large Language Models (LLMs), we explore to what extent LLMs
can be leveraged to exploit the contextual vulnerability of DP-sanitized texts.
We expand on previous work not only in the use of advanced LLMs, but also in
testing a broader range of sanitization mechanisms at various privacy levels.
Our experiments uncover a double-edged sword effect of LLM-based data
reconstruction attacks on privacy and utility: while LLMs can indeed infer
original semantics and sometimes degrade empirical privacy protections, they
can also be used for good, to improve the quality and privacy of DP-sanitized
texts. Based on our findings, we propose recommendations for using LLM data
reconstruction as a post-processing step, serving to increase privacy
protection by thinking adversarially.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.18971v1">Can we make NeRF-based visual localization privacy-preserving?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-08-26T12:17:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maxime Pietrantoni, Martin Humenberger, Torsten Sattler, Gabriela Csurka</p>
    <p><b>Summary:</b> Visual localization (VL) is the task of estimating the camera pose in a known
scene. VL methods, a.o., can be distinguished based on how they represent the
scene, e.g., explicitly through a (sparse) point cloud or a collection of
images or implicitly through the weights of a neural network. Recently,
NeRF-based methods have become popular for VL. While NeRFs offer high-quality
novel view synthesis, they inadvertently encode fine scene details, raising
privacy concerns when deployed in cloud-based localization services as
sensitive information could be recovered. In this paper, we tackle this
challenge on two ends. We first propose a new protocol to assess
privacy-preservation of NeRF-based representations. We show that NeRFs trained
with photometric losses store fine-grained details in their geometry
representations, making them vulnerable to privacy attacks, even if the head
that predicts colors is removed. Second, we propose ppNeSF (Privacy-Preserving
Neural Segmentation Field), a NeRF variant trained with segmentation
supervision instead of RGB images. These segmentation labels are learned in a
self-supervised manner, ensuring they are coarse enough to obscure identifiable
scene details while remaining discriminativeness in 3D. The segmentation space
of ppNeSF can be used for accurate visual localization, yielding
state-of-the-art results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.18942v1">EnerSwap: Large-Scale, Privacy-First Automated Market Maker for V2G
  Energy Trading</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-26T11:31:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ahmed Mounsf Rafik Bendada, Yacine Ghamri-Doudane</p>
    <p><b>Summary:</b> With the rapid growth of Electric Vehicle (EV) technology, EVs are destined
to shape the future of transportation. The large number of EVs facilitates the
development of the emerging vehicle-to-grid (V2G) technology, which realizes
bidirectional energy exchanges between EVs and the power grid. This has led to
the setting up of electricity markets that are usually confined to a small
geographical location, often with a small number of participants. Usually,
these markets are manipulated by intermediaries responsible for collecting bids
from prosumers, determining the market-clearing price, incorporating grid
constraints, and accounting for network losses. While centralized models can be
highly efficient, they grant excessive power to the intermediary by allowing
them to gain exclusive access to prosumers \textquotesingle price preferences.
This opens the door to potential market manipulation and raises significant
privacy concerns for users, such as the location of energy providers. This lack
of protection exposes users to potential risks, as untrustworthy servers and
malicious adversaries can exploit this information to infer trading activities
and real identities. This work proposes a secure, decentralized exchange market
built on blockchain technology, utilizing a privacy-preserving Automated Market
Maker (AMM) model to offer open and fair, and equal access to traders, and
mitigates the most common trading-manipulation attacks. Additionally, it
incorporates a scalable architecture based on geographical dynamic sharding,
allowing for efficient resource allocation and improved performance as the
market grows.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.18911v2">Enhancing Model Privacy in Federated Learning with Random Masking and
  Quantization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-26T10:34:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhibo Xu, Jianhao Zhu, Jingwen Xu, Changze Lv, Zisu Huang, Xiaohua Wang, Muling Wu, Qi Qian, Xiaoqing Zheng, Xuanjing Huang</p>
    <p><b>Summary:</b> The primary goal of traditional federated learning is to protect data privacy
by enabling distributed edge devices to collaboratively train a shared global
model while keeping raw data decentralized at local clients. The rise of large
language models (LLMs) has introduced new challenges in distributed systems, as
their substantial computational requirements and the need for specialized
expertise raise critical concerns about protecting intellectual property (IP).
This highlights the need for a federated learning approach that can safeguard
both sensitive data and proprietary models. To tackle this challenge, we
propose FedQSN, a federated learning approach that leverages random masking to
obscure a subnetwork of model parameters and applies quantization to the
remaining parameters. Consequently, the server transmits only a
privacy-preserving proxy of the global model to clients during each
communication round, thus enhancing the model's confidentiality. Experimental
results across various models and tasks demonstrate that our approach not only
maintains strong model performance in federated learning settings but also
achieves enhanced protection of model parameters compared to baseline methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.18832v1">A Tight Context-aware Privacy Bound for Histogram Publication</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2025-08-26T09:12:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sara Saeidian, Ata Yavuzyılmaz, Leonhard Grosse, Georg Schuppe, Tobias J. Oechtering</p>
    <p><b>Summary:</b> We analyze the privacy guarantees of the Laplace mechanism releasing the
histogram of a dataset through the lens of pointwise maximal leakage (PML).
While differential privacy is commonly used to quantify the privacy loss, it is
a context-free definition that does not depend on the data distribution. In
contrast, PML enables a more refined analysis by incorporating assumptions
about the data distribution. We show that when the probability of each
histogram bin is bounded away from zero, stronger privacy protection can be
achieved for a fixed level of noise. Our results demonstrate the advantage of
context-aware privacy measures and show that incorporating assumptions about
the data can improve privacy-utility tradeoffs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.18513v1">An Analytical Approach to Privacy and Performance Trade-Offs in
  Healthcare Data Sharing</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-08-25T21:36:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yusi Wei, Hande Y. Benson, Muge Capan</p>
    <p><b>Summary:</b> The secondary use of healthcare data is vital for research and clinical
innovation, but it raises concerns about patient privacy. This study
investigates how to balance privacy preservation and data utility in healthcare
data sharing, considering the perspectives of both data providers and data
users. Using a dataset of adult patients hospitalized between 2013 and 2015, we
predict whether sepsis was present at admission or developed during the
hospital stay. We identify sub-populations, such as older adults, frequently
hospitalized patients, and racial minorities, that are especially vulnerable to
privacy attacks due to their unique combinations of demographic and healthcare
utilization attributes. These groups are also critical for machine learning
(ML) model performance. We evaluate three anonymization methods-$k$-anonymity,
the technique by Zheng et al., and the MO-OBAM model-based on their ability to
reduce re-identification risk while maintaining ML utility. Results show that
$k$-anonymity offers limited protection. The methods of Zheng et al. and
MO-OBAM provide stronger privacy safeguards, with MO-OBAM yielding the best
utility outcomes: only a 2% change in precision and recall compared to the
original dataset. This work provides actionable insights for healthcare
organizations on how to share data responsibly. It highlights the need for
anonymization methods that protect vulnerable populations without sacrificing
the performance of data-driven models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.18453v1">Privacy-Preserving Federated Learning Framework for Risk-Based Adaptive
  Authentication</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-25T20:02:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yaser Baseri, Abdelhakim Senhaji Hafid, Dimitrios Makrakis, Hamidreza Fereidouni</p>
    <p><b>Summary:</b> Balancing robust security with strong privacy guarantees is critical for
Risk-Based Adaptive Authentication (RBA), particularly in decentralized
settings. Federated Learning (FL) offers a promising solution by enabling
collaborative risk assessment without centralizing user data. However, existing
FL approaches struggle with Non-Independent and Identically Distributed
(Non-IID) user features, resulting in biased, unstable, and poorly generalized
global models. This paper introduces FL-RBA2, a novel Federated Learning
framework for Risk-Based Adaptive Authentication that addresses Non-IID
challenges through a mathematically grounded similarity transformation. By
converting heterogeneous user features (including behavioral, biometric,
contextual, interaction-based, and knowledge-based modalities) into IID
similarity vectors, FL-RBA2 supports unbiased aggregation and personalized risk
modeling across distributed clients. The framework mitigates cold-start
limitations via clustering-based risk labeling, incorporates Differential
Privacy (DP) to safeguard sensitive information, and employs Message
Authentication Codes (MACs) to ensure model integrity and authenticity.
Federated updates are securely aggregated into a global model, achieving strong
balance between user privacy, scalability, and adaptive authentication
robustness. Rigorous game-based security proofs in the Random Oracle Model
formally establish privacy, correctness, and adaptive security guarantees.
Extensive experiments on keystroke, mouse, and contextual datasets validate
FL-RBA2's effectiveness in high-risk user detection and its resilience to model
inversion and inference attacks, even under strong DP constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.17962v1">"Nobody should control the end user": Exploring Privacy Perspectives of
  Indian Internet Users in Light of DPDPA</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-08-25T12:22:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sana Athar, Devashish Gosain, Anja Feldmann, Mannat Kaur, Ha Dao</p>
    <p><b>Summary:</b> With the rapid increase in online interactions, concerns over data privacy
and transparency of data processing practices have become more pronounced.
While regulations like the GDPR have driven the widespread adoption of cookie
banners in the EU, India's Digital Personal Data Protection Act (DPDPA)
promises similar changes domestically, aiming to introduce a framework for data
protection. However, certain clauses within the DPDPA raise concerns about
potential infringements on user privacy, given the exemptions for government
accountability and user consent requirements. In this study, for the first
time, we explore Indian Internet users' awareness and perceptions of cookie
banners, online privacy, and privacy regulations, especially in light of the
newly passed DPDPA. We conducted an online anonymous survey with 428 Indian
participants, which addressed: (1) users' perspectives on cookie banners, (2)
their attitudes towards online privacy and privacy regulations, and (3) their
acceptance of 10 contentious DPDPA clauses that favor state authorities and may
enable surveillance. Our findings reveal that privacy-conscious users often
lack consistent awareness of privacy mechanisms, and their concerns do not
always lead to protective actions. Our thematic analysis of 143 open ended
responses shows that users' privacy and data protection concerns are rooted in
skepticism towards the government, shaping their perceptions of the DPDPA and
fueling demands for policy revisions. Our study highlights the need for clearer
communication regarding the DPDPA, user-centric consent mechanisms, and policy
refinements to enhance data privacy practices in India.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.19286v1">RL-Finetuned LLMs for Privacy-Preserving Synthetic Rewriting</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-08-25T04:38:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhan Shi, Yefeng Yuan, Yuhong Liu, Liang Cheng, Yi Fang</p>
    <p><b>Summary:</b> The performance of modern machine learning systems depends on access to
large, high-quality datasets, often sourced from user-generated content or
proprietary, domain-specific corpora. However, these rich datasets inherently
contain sensitive personal information, raising significant concerns about
privacy, data security, and compliance with regulatory frameworks. While
conventional anonymization techniques can remove explicit identifiers, such
removal may result in performance drop in downstream machine learning tasks.
More importantly, simple anonymization may not be effective against inference
attacks that exploit implicit signals such as writing style, topical focus, or
demographic cues, highlighting the need for more robust privacy safeguards
during model training. To address the challenging issue of balancing user
privacy and data utility, we propose a reinforcement learning framework that
fine-tunes a large language model (LLM) using a composite reward function that
jointly optimizes for explicit and implicit privacy, semantic fidelity, and
output diversity. To effectively capture population level regularities, the
privacy reward combines semantic cues with structural patterns derived from a
minimum spanning tree (MST) over latent representations. By modeling these
privacy-sensitive signals in their distributional context, the proposed
approach guides the model to generate synthetic rewrites that preserve utility
while mitigating privacy risks. Empirical results show that the proposed method
significantly enhances author obfuscation and privacy metrics without degrading
semantic quality, providing a scalable and model-agnostic solution for privacy
preserving data generation in the era of large language models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.17341v1">MetaFed: Advancing Privacy, Performance, and Sustainability in Federated
  Metaverse Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2025-08-24T12:53:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Muhammet Anil Yagiz, Zeynep Sude Cengiz, Polat Goktas</p>
    <p><b>Summary:</b> The rapid expansion of immersive Metaverse applications introduces complex
challenges at the intersection of performance, privacy, and environmental
sustainability. Centralized architectures fall short in addressing these
demands, often resulting in elevated energy consumption, latency, and privacy
concerns. This paper proposes MetaFed, a decentralized federated learning (FL)
framework that enables sustainable and intelligent resource orchestration for
Metaverse environments. MetaFed integrates (i) multi-agent reinforcement
learning for dynamic client selection, (ii) privacy-preserving FL using
homomorphic encryption, and (iii) carbon-aware scheduling aligned with
renewable energy availability. Evaluations on MNIST and CIFAR-10 using
lightweight ResNet architectures demonstrate that MetaFed achieves up to 25\%
reduction in carbon emissions compared to conventional approaches, while
maintaining high accuracy and minimal communication overhead. These results
highlight MetaFed as a scalable solution for building environmentally
responsible and privacy-compliant Metaverse infrastructures.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.17222v1">Exposing Privacy Risks in Graph Retrieval-Augmented Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2025-08-24T06:19:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiale Liu, Jiahao Zhang, Suhang Wang</p>
    <p><b>Summary:</b> Retrieval-Augmented Generation (RAG) is a powerful technique for enhancing
Large Language Models (LLMs) with external, up-to-date knowledge. Graph RAG has
emerged as an advanced paradigm that leverages graph-based knowledge structures
to provide more coherent and contextually rich answers. However, the move from
plain document retrieval to structured graph traversal introduces new,
under-explored privacy risks. This paper investigates the data extraction
vulnerabilities of the Graph RAG systems. We design and execute tailored data
extraction attacks to probe their susceptibility to leaking both raw text and
structured data, such as entities and their relationships. Our findings reveal
a critical trade-off: while Graph RAG systems may reduce raw text leakage, they
are significantly more vulnerable to the extraction of structured entity and
relationship information. We also explore potential defense mechanisms to
mitigate these novel attack surfaces. This work provides a foundational
analysis of the unique privacy challenges in Graph RAG and offers insights for
building more secure systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.18318v1">ZTFed-MAS2S: A Zero-Trust Federated Learning Framework with Verifiable
  Privacy and Trust-Aware Aggregation for Wind Power Data Imputation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36"> 
  <p><b>Published on:</b> 2025-08-24T01:50:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yang Li, Hanjie Wang, Yuanzheng Li, Jiazheng Li, Zhaoyang Dong</p>
    <p><b>Summary:</b> Wind power data often suffers from missing values due to sensor faults and
unstable transmission at edge sites. While federated learning enables
privacy-preserving collaboration without sharing raw data, it remains
vulnerable to anomalous updates and privacy leakage during parameter exchange.
These challenges are amplified in open industrial environments, necessitating
zero-trust mechanisms where no participant is inherently trusted. To address
these challenges, this work proposes ZTFed-MAS2S, a zero-trust federated
learning framework that integrates a multi-head attention-based
sequence-to-sequence imputation model. ZTFed integrates verifiable differential
privacy with non-interactive zero-knowledge proofs and a confidentiality and
integrity verification mechanism to ensure verifiable privacy preservation and
secure model parameters transmission. A dynamic trust-aware aggregation
mechanism is employed, where trust is propagated over similarity graphs to
enhance robustness, and communication overhead is reduced via sparsity- and
quantization-based compression. MAS2S captures long-term dependencies in wind
power data for accurate imputation. Extensive experiments on real-world wind
farm datasets validate the superiority of ZTFed-MAS2S in both federated
learning performance and missing data imputation, demonstrating its
effectiveness as a secure and efficient solution for practical applications in
the energy sector.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.17135v1">Rao Differential Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2025-08-23T20:25:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Carlos Soto</p>
    <p><b>Summary:</b> Differential privacy (DP) has recently emerged as a definition of privacy to
release private estimates. DP calibrates noise to be on the order of an
individuals contribution. Due to the this calibration a private estimate
obscures any individual while preserving the utility of the estimate. Since the
original definition, many alternate definitions have been proposed. These
alternates have been proposed for various reasons including improvements on
composition results, relaxations, and formalizations. Nevertheless, thus far
nearly all definitions of privacy have used a divergence of densities as the
basis of the definition. In this paper we take an information geometry
perspective towards differential privacy. Specifically, rather than define
privacy via a divergence, we define privacy via the Rao distance. We show that
our proposed definition of privacy shares the interpretation of previous
definitions of privacy while improving on sequential composition.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.17043v1">ZAPS: A Zero-Knowledge Proof Protocol for Secure UAV Authentication with
  Flight Path Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-23T14:45:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shayesta Naziri, Xu Wang, Guangsheng Yu, Christy Jie Liang, Wei Ni</p>
    <p><b>Summary:</b> The increasing deployment of Unmanned Aerial Vehicles (UAVs) for military,
commercial, and logistics applications has raised significant concerns
regarding flight path privacy. Conventional UAV communication systems often
expose flight path data to third parties, making them vulnerable to tracking,
surveillance, and location inference attacks. Existing encryption techniques
provide security but fail to ensure complete privacy, as adversaries can still
infer movement patterns through metadata analysis. To address these challenges,
we propose a zk-SNARK(Zero-Knowledge Succinct Non-Interactive Argument of
Knowledge)-based privacy-preserving flight path authentication and verification
framework. Our approach ensures that a UAV can prove its authorisation,
validate its flight path with a control centre, and comply with regulatory
constraints without revealing any sensitive trajectory information. By
leveraging zk-SNARKs, the UAV can generate cryptographic proofs that verify
compliance with predefined flight policies while keeping the exact path and
location undisclosed. This method mitigates risks associated with real-time
tracking, identity exposure, and unauthorised interception, thereby enhancing
UAV operational security in adversarial environments. Our proposed solution
balances privacy, security, and computational efficiency, making it suitable
for resource-constrained UAVs in both civilian and military applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.16765v1">Guarding Your Conversations: Privacy Gatekeepers for Secure Interactions
  with Cloud-Based AI Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-08-22T19:49:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> GodsGift Uzor, Hasan Al-Qudah, Ynes Ineza, Abdul Serwadda</p>
    <p><b>Summary:</b> The interactive nature of Large Language Models (LLMs), which closely track
user data and context, has prompted users to share personal and private
information in unprecedented ways. Even when users opt out of allowing their
data to be used for training, these privacy settings offer limited protection
when LLM providers operate in jurisdictions with weak privacy laws, invasive
government surveillance, or poor data security practices. In such cases, the
risk of sensitive information, including Personally Identifiable Information
(PII), being mishandled or exposed remains high. To address this, we propose
the concept of an "LLM gatekeeper", a lightweight, locally run model that
filters out sensitive information from user queries before they are sent to the
potentially untrustworthy, though highly capable, cloud-based LLM. Through
experiments with human subjects, we demonstrate that this dual-model approach
introduces minimal overhead while significantly enhancing user privacy, without
compromising the quality of LLM responses.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.15523v1">Stabilization of Perturbed Loss Function: Differential Privacy without
  Gradient Noise</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2025-08-21T12:54:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Salman Habib, Remi Chou, Taejoon Kim</p>
    <p><b>Summary:</b> We propose SPOF (Stabilization of Perturbed Loss Function), a differentially
private training mechanism intended for multi-user local differential privacy
(LDP). SPOF perturbs a stabilized Taylor expanded polynomial approximation of a
model's training loss function, where each user's data is privatized by
calibrated noise added to the coefficients of the polynomial. Unlike
gradient-based mechanisms such as differentially private stochastic gradient
descent (DP-SGD), SPOF does not require injecting noise into the gradients of
the loss function, which improves both computational efficiency and stability.
This formulation naturally supports simultaneous privacy guarantees across all
users. Moreover, SPOF exhibits robustness to environmental noise during
training, maintaining stable performance even when user inputs are corrupted.
We compare SPOF with a multi-user extension of DP-SGD, evaluating both methods
in a wireless body area network (WBAN) scenario involving heterogeneous user
data and stochastic channel noise from body sensors. Our results show that SPOF
achieves, on average, up to 3.5% higher reconstruction accuracy and reduces
mean training time by up to 57.2% compared to DP-SGD, demonstrating superior
privacy-utility trade-offs in multi-user environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.15421v1">A Study of Privacy-preserving Language Modeling Approaches</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-08-21T10:22:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pritilata Saha, Abhirup Sinha</p>
    <p><b>Summary:</b> Recent developments in language modeling have increased their use in various
applications and domains. Language models, often trained on sensitive data, can
memorize and disclose this information during privacy attacks, raising concerns
about protecting individuals' privacy rights. Preserving privacy in language
models has become a crucial area of research, as privacy is one of the
fundamental human rights. Despite its significance, understanding of how much
privacy risk these language models possess and how it can be mitigated is still
limited. This research addresses this by providing a comprehensive study of the
privacy-preserving language modeling approaches. This study gives an in-depth
overview of these approaches, highlights their strengths, and investigates
their limitations. The outcomes of this study contribute to the ongoing
research on privacy-preserving language modeling, providing valuable insights
and outlining future research directions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.15089v1">Tighter Privacy Analysis for Truncated Poisson Sampling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-20T22:00:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arun Ganesh</p>
    <p><b>Summary:</b> We give a new privacy amplification analysis for truncated Poisson sampling,
a Poisson sampling variant that truncates a batch if it exceeds a given maximum
batch size.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.15036v1">MoEcho: Exploiting Side-Channel Attacks to Compromise User Privacy in
  Mixture-of-Experts LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-20T20:02:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruyi Ding, Tianhong Xu, Xinyi Shen, Aidong Adam Ding, Yunsi Fei</p>
    <p><b>Summary:</b> The transformer architecture has become a cornerstone of modern AI, fueling
remarkable progress across applications in natural language processing,
computer vision, and multimodal learning. As these models continue to scale
explosively for performance, implementation efficiency remains a critical
challenge. Mixture of Experts (MoE) architectures, selectively activating
specialized subnetworks (experts), offer a unique balance between model
accuracy and computational cost. However, the adaptive routing in MoE
architectures, where input tokens are dynamically directed to specialized
experts based on their semantic meaning inadvertently opens up a new attack
surface for privacy breaches. These input-dependent activation patterns leave
distinctive temporal and spatial traces in hardware execution, which
adversaries could exploit to deduce sensitive user data. In this work, we
propose MoEcho, discovering a side channel analysis based attack surface that
compromises user privacy on MoE based systems. Specifically, in MoEcho, we
introduce four novel architectural side channels on different computing
platforms, including Cache Occupancy Channels and Pageout+Reload on CPUs, and
Performance Counter and TLB Evict+Reload on GPUs, respectively. Exploiting
these vulnerabilities, we propose four attacks that effectively breach user
privacy in large language models (LLMs) and vision language models (VLMs) based
on MoE architectures: Prompt Inference Attack, Response Reconstruction Attack,
Visual Inference Attack, and Visual Reconstruction Attack. MoEcho is the first
runtime architecture level security analysis of the popular MoE structure
common in modern transformers, highlighting a serious security and privacy
threat and calling for effective and timely safeguards when harnessing MoE
based models for developing efficient large scale AI services.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.14815v1">A Lightweight Privacy-Preserving Smart Metering Billing Protocol with
  Dynamic Tariff Policy Adjustment</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-20T16:06:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Farid Zaredar, Morteza Amini</p>
    <p><b>Summary:</b> The integration of information and communication technology (ICT) with
traditional power grids has led to the emergence of smart grids. Advanced
metering infrastructure (AMI) plays a crucial role in smart grids by
facilitating two-way communication between smart meters and the utility
provider. This bidirectional communication allows intelligent meters to report
fine-grained consumption data at predefined intervals, enabling accurate
billing, efficient grid monitoring and management, and rapid outage detection.
However, the collection of detailed consumption data can inadvertently disclose
consumers' daily activities, raising privacy concerns and potentially leading
to privacy violations. To address these issues and preserve individuals'
privacy, we propose a lightweight privacy-preserving smart metering protocol
specifically designed to support real-time tariff billing service with dynamic
policy adjustment. Our scheme employs an efficient data perturbation technique
to obscure precise energy usage data from internal adversaries, including the
intermediary gateways and the utility provider. Subsequently, we validate the
efficiency and security of our protocol through comprehensive performance and
privacy evaluations. We examined the computational, memory, and communication
overhead of the proposed scheme. The execution time of our secure and
privacy-aware billing system is approximately 3.94540 seconds for a complete
year. Furthermore, we employed the Jensen-Shannon divergence as a privacy
metric to demonstrate that our protocol can effectively safeguard users'
privacy by increasing the noise scale.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.14744v1">A Collusion-Resistance Privacy-Preserving Smart Metering Protocol for
  Operational Utility</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-20T14:40:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Farid Zaredar, Morteza Amini</p>
    <p><b>Summary:</b> Modern grids have adopted advanced metering infrastructure (AMI) to
facilitate bidirectional communication between smart meters and control
centers. This enables smart meters to report consumption values at predefined
intervals to utility providers for purposes including demand balancing, load
forecasting, dynamic billing, and operational efficiency. Compared to
traditional power grids, smart grids offer advantages such as enhanced
reliability, improved energy efficiency, and increased security. However,
utility providers can compromise user privacy by analyzing fine-grained
readings and extracting individuals' daily activities from this time-series
data. To address this concern, we propose a collusion-resistant,
privacy-preserving aggregation protocol for smart metering in operational
services. Our protocol ensures privacy by leveraging techniques such as
partially additive homomorphic encryption, aggregation, data perturbation, and
data minimization. The scheme aggregates perturbed readings using the additive
homomorphic property of the Paillier cryptosystem to provide results for
multiple operational purposes. We evaluate the protocol in terms of both
performance and privacy. Computational, memory, and communication overhead were
examined. The total execution time with 1024-bit key size is about 2.21
seconds. We also evaluated privacy through the normalized conditional entropy
(NCE) metric. Higher NCE values, closer to 1, indicate stronger privacy. By
increasing noise scale, the NCE value rises, showing perturbed values retain
minimal information about the original, thereby reducing risks. Overall,
evaluation demonstrates the protocol's efficiency while employing various
privacy-preserving techniques.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.14703v1">A Lightweight Incentive-Based Privacy-Preserving Smart Metering Protocol
  for Value-Added Services</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-20T13:28:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Farid Zaredar, Morteza Amini</p>
    <p><b>Summary:</b> The emergence of smart grids and advanced metering infrastructure (AMI) has
revolutionized energy management. Unlike traditional power grids, smart grids
benefit from two-way communication through AMI, which surpasses earlier
automated meter reading (AMR). AMI enables diverse demand- and supply-side
utilities such as accurate billing, outage detection, real-time grid control,
load forecasting, and value-added services. Smart meters play a key role by
delivering consumption values at predefined intervals to the utility provider
(UP). However, such reports may raise privacy concerns, as adversaries can
infer lifestyle patterns, political orientations, and the types of electrical
devices in a household, or even sell the data to third parties (TP) such as
insurers. In this paper, we propose a lightweight, privacy-preserving smart
metering protocol for incentive-based value-added services. The scheme employs
local differential privacy, hash chains, blind digital signatures, pseudonyms,
temporal aggregation, and anonymous overlay networks to report coarse-grained
values with adjustable granularity to the UP. This protects consumers' privacy
while preserving data utility. The scheme prevents identity disclosure while
enabling automatic token redemption. From a performance perspective, our
results show that with a 1024-bit RSA key, a 7-day duration, and four reports
per day, our protocol runs in approximately 0.51s and consumes about 4.5 MB of
memory. From a privacy perspective, the protocol resists semi-trusted and
untrusted adversaries.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.15844v1">Ransomware Negotiation: Dynamics and Privacy-Preserving Mechanism Design</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-19T20:29:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haohui Zhang, Sirui Shen, Xinyu Hu, Chenglu Jin</p>
    <p><b>Summary:</b> Ransomware attacks have become a pervasive and costly form of cybercrime,
causing tens of millions of dollars in losses as organizations increasingly pay
ransoms to mitigate operational disruptions and financial risks. While prior
research has largely focused on proactive defenses, the post-infection
negotiation dynamics between attackers and victims remains underexplored. This
paper presents a formal analysis of attacker-victim interactions in modern
ransomware incidents using a finite-horizon alternating-offers bargaining game
model. Our analysis demonstrates how bargaining alters the optimal strategies
of both parties. In practice, incomplete information-attackers lacking
knowledge of victims' data valuations and victims lacking knowledge of
attackers' reservation ransoms-can prolong negotiations and increase victims'
business interruption costs. To address this, we design a Bayesian
incentive-compatible mechanism that facilitates rapid agreement on a fair
ransom without requiring either party to disclose private valuations. We
further implement this mechanism using secure two-party computation based on
garbled circuits, thereby eliminating the need for trusted intermediaries and
preserving the privacy of both parties throughout the negotiation. To the best
of our knowledge, this is the first automated, privacy-preserving negotiation
mechanism grounded in a formal analysis of ransomware negotiation dynamics.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.13914v1">Development of a defacing algorithm to protect the privacy of head and
  neck cancer patients in publicly-accessible radiotherapy datasets</a></h3>
  
  <p><b>Published on:</b> 2025-08-19T15:14:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kayla O'Sullivan-Steben, Luc Galarneau, John Kildea</p>
    <p><b>Summary:</b> Introduction: The rise in public medical imaging datasets has raised concerns
about patient reidentification from head CT scans. However, existing defacing
algorithms often remove or distort Organs at Risk (OARs) and Planning Target
Volumes (PTVs) in head and neck cancer (HNC) patients, and ignore DICOM-RT
Structure Set and Dose data. Therefore, we developed and validated a novel
automated defacing algorithm that preserves these critical structures while
removing identifiable features from HNC CTs and DICOM-RT data.
  Methods: Eye contours were used as landmarks to automate the removal of CT
pixels above the inferior-most eye slice and anterior to the eye midpoint.
Pixels within PTVs were retained if they intersected with the removed region.
The body contour and dose map were reshaped to reflect the defaced image. We
validated our approach on 829 HNC CTs from 622 patients. Privacy protection was
evaluated by applying the FaceNet512 facial recognition algorithm before and
after defacing on 3D-rendered CT pairs from 70 patients. Research utility was
assessed by examining the impact of defacing on autocontouring performance
using LimbusAI and analyzing PTV locations relative to the defaced regions.
  Results: Before defacing, FaceNet512 matched 97% of patients' CTs. After
defacing, this rate dropped to 4%. LimbusAI effectively autocontoured organs in
the defaced CTs, with perfect Dice scores of 1 for OARs below the defaced
region, and excellent scores exceeding 0.95 for OARs on the same slices as the
crop. We found that 86% of PTVs were entirely below the cropped region, 9.1%
were on the same slice as the crop without overlap, and only 4.9% extended into
the cropped area.
  Conclusions: We developed a novel defacing algorithm that anonymizes HNC CT
scans and related DICOM-RT data while preserving essential structures, enabling
the sharing of HNC imaging datasets for Big Data and AI.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.13730v1">On the Security and Privacy of Federated Learning: A Survey with
  Attacks, Defenses, Frameworks, Applications, and Future Directions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-08-19T11:06:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Daniel M. Jimenez-Gutierrez, Yelizaveta Falkouskaya, Jose L. Hernandez-Ramos, Aris Anagnostopoulos, Ioannis Chatzigiannakis, Andrea Vitaletti</p>
    <p><b>Summary:</b> Federated Learning (FL) is an emerging distributed machine learning paradigm
enabling multiple clients to train a global model collaboratively without
sharing their raw data. While FL enhances data privacy by design, it remains
vulnerable to various security and privacy threats. This survey provides a
comprehensive overview of more than 200 papers regarding the state-of-the-art
attacks and defense mechanisms developed to address these challenges,
categorizing them into security-enhancing and privacy-preserving techniques.
Security-enhancing methods aim to improve FL robustness against malicious
behaviors such as byzantine attacks, poisoning, and Sybil attacks. At the same
time, privacy-preserving techniques focus on protecting sensitive data through
cryptographic approaches, differential privacy, and secure aggregation. We
critically analyze the strengths and limitations of existing methods, highlight
the trade-offs between privacy, security, and model performance, and discuss
the implications of non-IID data distributions on the effectiveness of these
defenses. Furthermore, we identify open research challenges and future
directions, including the need for scalable, adaptive, and energy-efficient
solutions operating in dynamic and heterogeneous FL environments. Our survey
aims to guide researchers and practitioners in developing robust and
privacy-preserving FL systems, fostering advancements safeguarding
collaborative learning frameworks' integrity and confidentiality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.13425v1">When Secure Aggregation Falls Short: Achieving Long-Term Privacy in
  Asynchronous Federated Learning for LEO Satellite Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-19T00:55:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohamed Elmahallawy, Tie Luo</p>
    <p><b>Summary:</b> Secure aggregation is a common technique in federated learning (FL) for
protecting data privacy from both curious internal entities (clients or server)
and external adversaries (eavesdroppers). However, in dynamic and
resource-constrained environments such as low Earth orbit (LEO) satellite
networks, traditional secure aggregation methods fall short in two aspects: (1)
they assume continuous client availability while LEO satellite visibility is
intermittent and irregular; (2) they consider privacy in each communication
round but have overlooked the possible privacy leakage through multiple rounds.
To address these limitations, we propose LTP-FLEO, an asynchronous FL framework
that preserves long-term privacy (LTP) for LEO satellite networks. LTP-FLEO
introduces (i) privacy-aware satellite partitioning, which groups satellites
based on their predictable visibility to the server and enforces joint
participation; (ii) model age balancing, which mitigates the adverse impact of
stale model updates; and (iii) fair global aggregation, which treats satellites
of different visibility durations in an equitable manner. Theoretical analysis
and empirical validation demonstrate that LTP-FLEO effectively safeguards both
model and data privacy across multi-round training, promotes fairness in line
with satellite contributions, accelerates global convergence, and achieves
competitive model accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.12832v2">Efficient and Verifiable Privacy-Preserving Convolutional Computation
  for CNN Inference with Untrusted Clouds</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-08-18T11:17:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jinyu Lu, Xinrong Sun, Yunting Tao, Tong Ji, Fanyu Kong, Guoqiang Yang</p>
    <p><b>Summary:</b> The widespread adoption of convolutional neural networks (CNNs) in
resource-constrained scenarios has driven the development of Machine Learning
as a Service (MLaaS) system. However, this approach is susceptible to privacy
leakage, as the data sent from the client to the untrusted cloud server often
contains sensitive information. Existing CNN privacy-preserving schemes, while
effective in ensuring data confidentiality through homomorphic encryption and
secret sharing, face efficiency bottlenecks, particularly in convolution
operations. In this paper, we propose a novel verifiable privacy-preserving
scheme tailored for CNN convolutional layers. Our scheme enables efficient
encryption and decryption, allowing resource-constrained clients to securely
offload computations to the untrusted cloud server. Additionally, we present a
verification mechanism capable of detecting the correctness of the results with
a success probability of at least $1-\frac{1}{\left|Z\right|}$. Extensive
experiments conducted on 10 datasets and various CNN models demonstrate that
our scheme achieves speedups ranging $26 \times$ ~ $\ 87\times$ compared to the
original plaintext model while maintaining accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.12539v1">The Hidden Cost of Correlation: Rethinking Privacy Leakage in Local
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2025-08-18T00:34:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sandaru Jayawardana, Sennur Ulukus, Ming Ding, Kanchana Thilakarathna</p>
    <p><b>Summary:</b> Local differential privacy (LDP) has emerged as a promising paradigm for
privacy-preserving data collection in distributed systems, where users
contribute multi-dimensional records with potentially correlated attributes.
Recent work has highlighted that correlation-induced privacy leakage (CPL)
plays a critical role in shaping the privacy-utility trade-off under LDP,
especially when correlations exist among attributes. Nevertheless, it remains
unclear to what extent the prevailing assumptions and proposed solutions are
valid and how significant CPL is in real-world data. To address this gap, we
first perform a comprehensive statistical analysis of five widely used LDP
mechanisms -- GRR, RAPPOR, OUE, OLH and Exponential mechanism -- to assess CPL
across four real-world datasets. We identify that many primary assumptions and
metrics in current approaches fall short of accurately characterising these
leakages. Moreover, current studies have been limited to a set of pure LDP
(i.e., {\delta = 0}) mechanisms. In response, we develop the first algorithmic
framework to theoretically quantify CPL for any general approximated LDP
(({\varepsilon},{\delta})-LDP) mechanism. We validate our theoretical results
against empirical statistical results and provide a theoretical explanation for
the observed statistical patterns. Finally, we propose two novel benchmarks to
validate correlation analysis algorithms and evaluate the utility vs CPL of LDP
mechanisms. Further, we demonstrate how these findings can be applied to
achieve an efficient privacy-utility trade-off in real-world data governance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.12158v1">LLM-as-a-Judge for Privacy Evaluation? Exploring the Alignment of Human
  and LLM Perceptions of Privacy in Textual Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-08-16T20:49:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stephen Meisenbacher, Alexandra Klymenko, Florian Matthes</p>
    <p><b>Summary:</b> Despite advances in the field of privacy-preserving Natural Language
Processing (NLP), a significant challenge remains the accurate evaluation of
privacy. As a potential solution, using LLMs as a privacy evaluator presents a
promising approach $\unicode{x2013}$ a strategy inspired by its success in
other subfields of NLP. In particular, the so-called $\textit{LLM-as-a-Judge}$
paradigm has achieved impressive results on a variety of natural language
evaluation tasks, demonstrating high agreement rates with human annotators.
Recognizing that privacy is both subjective and difficult to define, we
investigate whether LLM-as-a-Judge can also be leveraged to evaluate the
privacy sensitivity of textual data. Furthermore, we measure how closely LLM
evaluations align with human perceptions of privacy in text. Resulting from a
study involving 10 datasets, 13 LLMs, and 677 human survey participants, we
confirm that privacy is indeed a difficult concept to measure empirically,
exhibited by generally low inter-human agreement rates. Nevertheless, we find
that LLMs can accurately model a global human privacy perspective, and through
an analysis of human and LLM reasoning patterns, we discuss the merits and
limitations of LLM-as-a-Judge for privacy evaluation in textual data. Our
findings pave the way for exploring the feasibility of LLMs as privacy
evaluators, addressing a core challenge in solving pressing privacy issues with
innovative technical solutions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.12093v2">PP-STAT: An Efficient Privacy-Preserving Statistical Analysis Framework
  using Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-16T16:24:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hyunmin Choi</p>
    <p><b>Summary:</b> With the widespread adoption of cloud computing, the need for outsourcing
statistical analysis to third-party platforms is growing rapidly. However,
handling sensitive data such as medical records and financial information in
cloud environments raises serious privacy concerns. In this paper, we present
PP-STAT, a novel and efficient Homomorphic Encryption (HE)-based framework for
privacy-preserving statistical analysis. HE enables computations to be
performed directly on encrypted data without revealing the underlying
plaintext. PP-STAT supports advanced statistical measures, including Z-score
normalization, skewness, kurtosis, coefficient of variation, and Pearson
correlation coefficient, all computed securely over encrypted data. To improve
efficiency, PP-STAT introduces two key optimizations: (1) a Chebyshev-based
approximation strategy for initializing inverse square root operations, and (2)
a pre-normalization scaling technique that reduces multiplicative depth by
folding constant scaling factors into mean and variance computations. These
techniques significantly lower computational overhead and minimize the number
of expensive bootstrapping procedures. Our evaluation on real-world datasets
demonstrates that PP-STAT achieves high numerical accuracy, with mean relative
error (MRE) below 2.4x10-4. Notably, the encrypted Pearson correlation between
the smoker attribute and charges reaches 0.7873, with an MRE of 2.86x10-4.
These results confirm the practical utility of PP-STAT for secure and precise
statistical analysis in privacy-sensitive domains.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.11907v1">Deciphering the Interplay between Attack and Protection Complexity in
  Privacy-Preserving Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-16T04:39:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaojin Zhang, Mingcong Xu, Yiming Li, Wei Chen, Qiang Yang</p>
    <p><b>Summary:</b> Federated learning (FL) offers a promising paradigm for collaborative model
training while preserving data privacy. However, its susceptibility to gradient
inversion attacks poses a significant challenge, necessitating robust privacy
protection mechanisms. This paper introduces a novel theoretical framework to
decipher the intricate interplay between attack and protection complexities in
privacy-preserving FL. We formally define "Attack Complexity" as the minimum
computational and data resources an adversary requires to reconstruct private
data below a given error threshold, and "Protection Complexity" as the expected
distortion introduced by privacy mechanisms. Leveraging Maximum Bayesian
Privacy (MBP), we derive tight theoretical bounds for protection complexity,
demonstrating its scaling with model dimensionality and privacy budget.
Furthermore, we establish comprehensive bounds for attack complexity, revealing
its dependence on privacy leakage, gradient distortion, model dimension, and
the chosen privacy level. Our findings quantitatively illuminate the
fundamental trade-offs between privacy guarantees, system utility, and the
effort required for both attacking and defending. This framework provides
critical insights for designing more secure and efficient federated learning
systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.11797v1">AegisBlock: A Privacy-Preserving Medical Research Framework using
  Blockchain</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-08-15T20:43:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Calkin Garg, Omar Rios Cruz, Tessa Andersen, Gaby G. Dagher, Donald Winiecki, Min Long</p>
    <p><b>Summary:</b> Due to HIPAA and other privacy regulations, it is imperative to maintain
patient privacy while conducting research on patient health records. In this
paper, we propose AegisBlock, a patient-centric access controlled framework to
share medical records with researchers such that the anonymity of the patient
is maintained while ensuring the trustworthiness of the data provided to
researchers. AegisBlock allows for patients to provide access to their medical
data, verified by miners. A researcher submits a time-based range query to
request access to records from a certain patient, and upon patient approval,
access will be granted. Our experimental evaluation results show that
AegisBlock is scalable with respect to the number of patients and hospitals in
the system, and efficient with up to 50% of malicious miners.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.11742v1">Assessing User Privacy Leakage in Synthetic Packet Traces: An
  Attack-Grounded Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2025-08-15T17:54:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Minhao Jin, Hongyu He, Maria Apostolaki</p>
    <p><b>Summary:</b> Current synthetic traffic generators (SynNetGens) promise privacy but lack
comprehensive guarantees or empirical validation, even as their fidelity
steadily improves. We introduce the first attack-grounded benchmark for
assessing the privacy of SynNetGens directly from the traffic they produce. We
frame privacy as membership inference at the traffic-source level--a realistic
and actionable threat for data holders. To this end, we present TraceBleed, the
first attack that exploits behavioral fingerprints across flows using
contrastive learning and temporal chunking, outperforming prior membership
inference baselines by 172%. Our large-scale study across GAN-, diffusion-, and
GPT-based SynNetGens uncovers critical insights: (i) SynNetGens leak user-level
information; (ii) differential privacy either fails to stop these attacks or
severely degrades fidelity; and (iii) sharing more synthetic data amplifies
leakage by 59% on average. Finally, we introduce TracePatch, the first
SynNetGen-agnostic defense that combines adversarial ML with SMT constraints to
mitigate leakage while preserving fidelity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.11575v1">Activate Me!: Designing Efficient Activation Functions for
  Privacy-Preserving Machine Learning with Fully Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-15T16:31:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nges Brian Njungle, Michel A. Kinsy</p>
    <p><b>Summary:</b> The growing adoption of machine learning in sensitive areas such as
healthcare and defense introduces significant privacy and security challenges.
These domains demand robust data protection, as models depend on large volumes
of sensitive information for both training and inference. Fully Homomorphic
Encryption (FHE) presents a compelling solution by enabling computations
directly on encrypted data, maintaining confidentiality across the entire
machine learning workflow. However, FHE inherently supports only linear
operations, making it difficult to implement non-linear activation functions,
essential components of modern neural networks. This work focuses on designing,
implementing, and evaluating activation functions tailored for FHE-based
machine learning. We investigate two commonly used functions: the Square
function and Rectified Linear Unit (ReLU), using LeNet-5 and ResNet-20
architectures with the CKKS scheme from the OpenFHE library. For ReLU, we
assess two methods: a conventional low-degree polynomial approximation and a
novel scheme-switching technique that securely evaluates ReLU under FHE
constraints. Our findings show that the Square function performs well in
shallow networks like LeNet-5, achieving 99.4% accuracy with 128 seconds per
image. In contrast, deeper models like ResNet-20 benefit more from ReLU. The
polynomial approximation yields 83.8% accuracy with 1,145 seconds per image,
while our scheme-switching method improves accuracy to 89.8%, albeit with a
longer inference time of 1,697 seconds. These results underscore a critical
trade-off in FHE-based ML: faster activation functions often reduce accuracy,
whereas those preserving accuracy demand greater computational resources.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.11495v1">KV-Auditor: Auditing Local Differential Privacy for Correlated Key-Value
  Estimation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-15T14:17:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jingnan Xu, Leixia Wang, Xiaofeng Meng</p>
    <p><b>Summary:</b> To protect privacy for data-collection-based services, local differential
privacy (LDP) is widely adopted due to its rigorous theoretical bound on
privacy loss. However, mistakes in complex theoretical analysis or subtle
implementation errors may undermine its practical guarantee. To address this,
auditing is crucial to confirm that LDP protocols truly protect user data.
However, existing auditing methods, though, mainly target machine learning and
federated learning tasks based on centralized differentially privacy (DP), with
limited attention to LDP. Moreover, the few studies on LDP auditing focus
solely on simple frequency estimation task for discrete data, leaving
correlated key-value data - which requires both discrete frequency estimation
for keys and continuous mean estimation for values - unexplored.
  To bridge this gap, we propose KV-Auditor, a framework for auditing LDP-based
key-value estimation mechanisms by estimating their empirical privacy lower
bounds. Rather than traditional LDP auditing methods that relies on binary
output predictions, KV-Auditor estimates this lower bound by analyzing
unbounded output distributions, supporting continuous data. Specifically, we
classify state-of-the-art LDP key-value mechanisms into interactive and
non-interactive types. For non-interactive mechanisms, we propose horizontal
KV-Auditor for small domains with sufficient samples and vertical KV-Auditor
for large domains with limited samples. For interactive mechanisms, we design a
segmentation strategy to capture incremental privacy leakage across iterations.
Finally, we perform extensive experiments to validate the effectiveness of our
approach, offering insights for optimizing LDP-based key-value estimators.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.11419v1">Training-free Dimensionality Reduction via Feature Truncation: Enhancing
  Efficiency in Privacy-preserving Multi-Biometric Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-08-15T11:49:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Florian Bayer, Maximilian Russo, Christian Rathgeb</p>
    <p><b>Summary:</b> Biometric recognition is widely used, making the privacy and security of
extracted templates a critical concern. Biometric Template Protection schemes,
especially those utilizing Homomorphic Encryption, introduce significant
computational challenges due to increased workload. Recent advances in deep
neural networks have enabled state-of-the-art feature extraction for face,
fingerprint, and iris modalities. The ubiquity and affordability of biometric
sensors further facilitate multi-modal fusion, which can enhance security by
combining features from different modalities. This work investigates the
biometric performance of reduced multi-biometric template sizes. Experiments
are conducted on an in-house virtual multi-biometric database, derived from
DNN-extracted features for face, fingerprint, and iris, using the FRGC, MCYT,
and CASIA databases. The evaluated approaches are (i) explainable and
straightforward to implement under encryption, (ii) training-free, and (iii)
capable of generalization. Dimensionality reduction of feature vectors leads to
fewer operations in the Homomorphic Encryption (HE) domain, enabling more
efficient encrypted processing while maintaining biometric accuracy and
security at a level equivalent to or exceeding single-biometric recognition.
Our results demonstrate that, by fusing feature vectors from multiple
modalities, template size can be reduced by 67 % with no loss in Equal Error
Rate (EER) compared to the best-performing single modality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.11115v1">UWB-PostureGuard: A Privacy-Preserving RF Sensing System for Continuous
  Ergonomic Sitting Posture Monitoring</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> 
  <p><b>Published on:</b> 2025-08-14T23:40:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haotang Li, Zhenyu Qi, Sen He, Kebin Peng, Sheng Tan, Yili Ren, Tomas Cerny, Jiyue Zhao, Zi Wang</p>
    <p><b>Summary:</b> Improper sitting posture during prolonged computer use has become a
significant public health concern. Traditional posture monitoring solutions
face substantial barriers, including privacy concerns with camera-based systems
and user discomfort with wearable sensors. This paper presents
UWB-PostureGuard, a privacy-preserving ultra-wideband (UWB) sensing system that
advances mobile technologies for preventive health management through
continuous, contactless monitoring of ergonomic sitting posture. Our system
leverages commercial UWB devices, utilizing comprehensive feature engineering
to extract multiple ergonomic sitting posture features. We develop PoseGBDT to
effectively capture temporal dependencies in posture patterns, addressing
limitations of traditional frame-wise classification approaches. Extensive
real-world evaluation across 10 participants and 19 distinct postures
demonstrates exceptional performance, achieving 99.11% accuracy while
maintaining robustness against environmental variables such as clothing
thickness, additional devices, and furniture configurations. Our system
provides a scalable, privacy-preserving mobile health solution on existing
platforms for proactive ergonomic management, improving quality of life at low
costs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.10880v1">Searching for Privacy Risks in LLM Agents via Simulation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-08-14T17:49:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yanzhe Zhang, Diyi Yang</p>
    <p><b>Summary:</b> The widespread deployment of LLM-based agents is likely to introduce a
critical privacy threat: malicious agents that proactively engage others in
multi-turn interactions to extract sensitive information. These dynamic
dialogues enable adaptive attack strategies that can cause severe privacy
violations, yet their evolving nature makes it difficult to anticipate and
discover sophisticated vulnerabilities manually. To tackle this problem, we
present a search-based framework that alternates between improving attacker and
defender instructions by simulating privacy-critical agent interactions. Each
simulation involves three roles: data subject, data sender, and data recipient.
While the data subject's behavior is fixed, the attacker (data recipient)
attempts to extract sensitive information from the defender (data sender)
through persistent and interactive exchanges. To explore this interaction space
efficiently, our search algorithm employs LLMs as optimizers, using parallel
search with multiple threads and cross-thread propagation to analyze simulation
trajectories and iteratively propose new instructions. Through this process, we
find that attack strategies escalate from simple direct requests to
sophisticated multi-turn tactics such as impersonation and consent forgery,
while defenses advance from rule-based constraints to identity-verification
state machines. The discovered attacks and defenses transfer across diverse
scenarios and backbone models, demonstrating strong practical utility for
building privacy-aware agents.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.11716v2">Privacy-Aware Detection of Fake Identity Documents: Methodology,
  Benchmark, and Improved Algorithms (FakeIDet2)</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> 
  <p><b>Published on:</b> 2025-08-14T17:30:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Javier Muñoz-Haro, Ruben Tolosana, Julian Fierrez, Ruben Vera-Rodriguez, Aythami Morales</p>
    <p><b>Summary:</b> Remote user verification in Internet-based applications is becoming
increasingly important nowadays. A popular scenario for it consists of
submitting a picture of the user's Identity Document (ID) to a service
platform, authenticating its veracity, and then granting access to the
requested digital service. An ID is well-suited to verify the identity of an
individual, since it is government issued, unique, and nontransferable.
However, with recent advances in Artificial Intelligence (AI), attackers can
surpass security measures in IDs and create very realistic physical and
synthetic fake IDs. Researchers are now trying to develop methods to detect an
ever-growing number of these AI-based fakes that are almost indistinguishable
from authentic (bona fide) IDs. In this counterattack effort, researchers are
faced with an important challenge: the difficulty in using real data to train
fake ID detectors. This real data scarcity for research and development is
originated by the sensitive nature of these documents, which are usually kept
private by the ID owners (the users) and the ID Holders (e.g., government,
police, bank, etc.). The main contributions of our study are: 1) We propose and
discuss a patch-based methodology to preserve privacy in fake ID detection
research. 2) We provide a new public database, FakeIDet2-db, comprising over
900K real/fake ID patches extracted from 2,000 ID images, acquired using
different smartphone sensors, illumination and height conditions, etc. In
addition, three physical attacks are considered: print, screen, and composite.
3) We present a new privacy-aware fake ID detection method, FakeIDet2. 4) We
release a standard reproducible benchmark that considers physical and synthetic
attacks from popular databases in the literature.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.10737v1">Privacy-enhancing Sclera Segmentation Benchmarking Competition: SSBC
  2025</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-08-14T15:16:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Matej Vitek, Darian Tomašević, Abhijit Das, Sabari Nathan, Gökhan Özbulak, Gözde Ayşe Tataroğlu Özbulak, Jean-Paul Calbimonte, André Anjos, Hariohm Hemant Bhatt, Dhruv Dhirendra Premani, Jay Chaudhari, Caiyong Wang, Jian Jiang, Chi Zhang, Qi Zhang, Iyyakutti Iyappan Ganapathi, Syed Sadaf Ali, Divya Velayudan, Maregu Assefa, Naoufel Werghi, Zachary A. Daniels, Leeon John, Ritesh Vyas, Jalil Nourmohammadi Khiarak, Taher Akbari Saeed, Mahsa Nasehi, Ali Kianfar, Mobina Pashazadeh Panahi, Geetanjali Sharma, Pushp Raj Panth, Raghavendra Ramachandra, Aditya Nigam, Umapada Pal, Peter Peer, Vitomir Štruc</p>
    <p><b>Summary:</b> This paper presents a summary of the 2025 Sclera Segmentation Benchmarking
Competition (SSBC), which focused on the development of privacy-preserving
sclera-segmentation models trained using synthetically generated ocular images.
The goal of the competition was to evaluate how well models trained on
synthetic data perform in comparison to those trained on real-world datasets.
The competition featured two tracks: $(i)$ one relying solely on synthetic data
for model development, and $(ii)$ one combining/mixing synthetic with (a
limited amount of) real-world data. A total of nine research groups submitted
diverse segmentation models, employing a variety of architectural designs,
including transformer-based solutions, lightweight models, and segmentation
networks guided by generative frameworks. Experiments were conducted across
three evaluation datasets containing both synthetic and real-world images,
collected under diverse conditions. Results show that models trained entirely
on synthetic data can achieve competitive performance, particularly when
dedicated training strategies are employed, as evidenced by the top performing
models that achieved $F_1$ scores of over $0.8$ in the synthetic data track.
Moreover, performance gains in the mixed track were often driven more by
methodological choices rather than by the inclusion of real data, highlighting
the promise of synthetic data for privacy-aware biometric development. The code
and data for the competition is available at:
https://github.com/dariant/SSBC_2025.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.10672v2">Hybrid Generative Fusion for Efficient and Privacy-Preserving Face
  Recognition Dataset Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-14T14:14:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Feiran Li, Qianqian Xu, Shilong Bao, Boyu Han, Zhiyong Yang, Qingming Huang</p>
    <p><b>Summary:</b> In this paper, we present our approach to the DataCV ICCV Challenge, which
centers on building a high-quality face dataset to train a face recognition
model. The constructed dataset must not contain identities overlapping with any
existing public face datasets. To handle this challenge, we begin with a
thorough cleaning of the baseline HSFace dataset, identifying and removing
mislabeled or inconsistent identities through a Mixture-of-Experts (MoE)
strategy combining face embedding clustering and GPT-4o-assisted verification.
We retain the largest consistent identity cluster and apply data augmentation
up to a fixed number of images per identity. To further diversify the dataset,
we generate synthetic identities using Stable Diffusion with prompt
engineering. As diffusion models are computationally intensive, we generate
only one reference image per identity and efficiently expand it using Vec2Face,
which rapidly produces 49 identity-consistent variants. This hybrid approach
fuses GAN-based and diffusion-based samples, enabling efficient construction of
a diverse and high-quality dataset. To address the high visual similarity among
synthetic identities, we adopt a curriculum learning strategy by placing them
early in the training schedule, allowing the model to progress from easier to
harder samples. Our final dataset contains 50 images per identity, and all
newly generated identities are checked with mainstream face datasets to ensure
no identity leakage. Our method achieves \textbf{1st place} in the competition,
and experimental results show that our dataset improves model performance
across 10K, 20K, and 100K identity scales. Code is available at
https://github.com/Ferry-Li/datacv_fr.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.10482v2">When Explainability Meets Privacy: An Investigation at the Intersection
  of Post-hoc Explainability and Differential Privacy in the Context of Natural
  Language Processing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-08-14T09:34:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mahdi Dhaini, Stephen Meisenbacher, Ege Erdogan, Florian Matthes, Gjergji Kasneci</p>
    <p><b>Summary:</b> In the study of trustworthy Natural Language Processing (NLP), a number of
important research fields have emerged, including that of explainability and
privacy. While research interest in both explainable and privacy-preserving NLP
has increased considerably in recent years, there remains a lack of
investigation at the intersection of the two. This leaves a considerable gap in
understanding of whether achieving both explainability and privacy is possible,
or whether the two are at odds with each other. In this work, we conduct an
empirical investigation into the privacy-explainability trade-off in the
context of NLP, guided by the popular overarching methods of Differential
Privacy (DP) and Post-hoc Explainability. Our findings include a view into the
intricate relationship between privacy and explainability, which is formed by a
number of factors, including the nature of the downstream task and choice of
the text privatization and explainability method. In this, we highlight the
potential for privacy and explainability to co-exist, and we summarize our
findings in a collection of practical recommendations for future work at this
important intersection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.10469v1">Enhanced Sparse Point Cloud Data Processing for Privacy-aware Human
  Action Recognition</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-14T09:09:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maimunatu Tunau, Vincent Gbouna Zakka, Zhuangzhuang Dai</p>
    <p><b>Summary:</b> Human Action Recognition (HAR) plays a crucial role in healthcare, fitness
tracking, and ambient assisted living technologies. While traditional vision
based HAR systems are effective, they pose privacy concerns. mmWave radar
sensors offer a privacy preserving alternative but present challenges due to
the sparse and noisy nature of their point cloud data. In the literature, three
primary data processing methods: Density-Based Spatial Clustering of
Applications with Noise (DBSCAN), the Hungarian Algorithm, and Kalman Filtering
have been widely used to improve the quality and continuity of radar data.
However, a comprehensive evaluation of these methods, both individually and in
combination, remains lacking. This paper addresses that gap by conducting a
detailed performance analysis of the three methods using the MiliPoint dataset.
We evaluate each method individually, all possible pairwise combinations, and
the combination of all three, assessing both recognition accuracy and
computational cost. Furthermore, we propose targeted enhancements to the
individual methods aimed at improving accuracy. Our results provide crucial
insights into the strengths and trade-offs of each method and their
integrations, guiding future work on mmWave based HAR systems</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.10373v1">Privacy-Preserving Approximate Nearest Neighbor Search on
  High-Dimensional Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2025-08-14T06:09:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yingfan Liu, Yandi Zhang, Jiadong Xie, Hui Li, Jeffrey Xu Yu, Jiangtao Cui</p>
    <p><b>Summary:</b> In the era of cloud computing and AI, data owners outsource ubiquitous
vectors to the cloud, which furnish approximate $k$-nearest neighbors
($k$-ANNS) services to users. To protect data privacy against the untrusted
server, privacy-preserving $k$-ANNS (PP-ANNS) on vectors has been a fundamental
and urgent problem. However, existing PP-ANNS solutions fall short of meeting
the requirements of data privacy, efficiency, accuracy, and minimal user
involvement concurrently. To tackle this challenge, we introduce a novel
solution that primarily executes PP-ANNS on a single cloud server to avoid the
heavy communication overhead between the cloud and the user. To ensure data
privacy, we introduce a novel encryption method named distance comparison
encryption, facilitating secure, efficient, and exact distance comparisons. To
optimize the trade-off between data privacy and search performance, we design a
privacy-preserving index that combines the state-of-the-art $k$-ANNS method
with an approximate distance computation method. Then, we devise a search
method using a filter-and-refine strategy based on the index. Moreover, we
provide the security analysis of our solution and conduct extensive experiments
to demonstrate its superiority over existing solutions. Based on our
experimental results, our method accelerates PP-ANNS by up to 3 orders of
magnitude compared to state-of-the-art methods, while not compromising the
accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.09882v1">Location Privacy-Enabled Beamforming in ISAC Scenarios</a></h3>
  
  <p><b>Published on:</b> 2025-08-13T15:32:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Umair Ali Khan, Lester Ho, Holger Claussen, Chinmoy Kundu</p>
    <p><b>Summary:</b> Integrated sensing and communication (ISAC) technology enables simultaneous
environmental perception and data transmission in wireless networks; however,
it also exposes user location to receivers. In this paper, we introduce a novel
beamforming framework guided by the proposed privacy metric direction of
arrival obfuscation ratio (DAOR) to protect transmitter location privacy in
ISAC scenarios. Unlike previous approaches, we do not suppress the
line-of-sight (LOS) component while reshaping the angular power distribution so
that a false direction appears dominant at the receiver. We derive closed-form
bounds on the feasible DAOR via generalized eigenvalue analysis and formulate
an achievable rate-maximization problem under the DAOR constraint. The
resulting problem is non-convex, which is efficiently solved using semidefinite
relaxation, eigenmode selection, and optimal power allocation. A suboptimal
design strategy is also proposed with reduced complexity. Numerical results
demonstrate that the proposed DAOR-based beamformer achieves a trade-off
between location privacy and communication rate without nullifying the LOS
path. Results also show that a suboptimal design achieves a near-optimal
communication rate with nearly an 85% reduction in computation time at a
signal-to-noise ratio (SNR) of 10 dB.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.09442v1">Shadow in the Cache: Unveiling and Mitigating Privacy Risks of KV-cache
  in LLM Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-08-13T02:48:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhifan Luo, Shuo Shao, Su Zhang, Lijing Zhou, Yuke Hu, Chenxu Zhao, Zhihao Liu, Zhan Qin</p>
    <p><b>Summary:</b> The Key-Value (KV) cache, which stores intermediate attention computations
(Key and Value pairs) to avoid redundant calculations, is a fundamental
mechanism for accelerating Large Language Model (LLM) inference. However, this
efficiency optimization introduces significant yet underexplored privacy risks.
This paper provides the first comprehensive analysis of these vulnerabilities,
demonstrating that an attacker can reconstruct sensitive user inputs directly
from the KV-cache. We design and implement three distinct attack vectors: a
direct Inversion Attack, a more broadly applicable and potent Collision Attack,
and a semantic-based Injection Attack. These methods demonstrate the
practicality and severity of KV-cache privacy leakage issues. To mitigate this,
we propose KV-Cloak, a novel, lightweight, and efficient defense mechanism.
KV-Cloak uses a reversible matrix-based obfuscation scheme, combined with
operator fusion, to secure the KV-cache. Our extensive experiments show that
KV-Cloak effectively thwarts all proposed attacks, reducing reconstruction
quality to random noise. Crucially, it achieves this robust security with
virtually no degradation in model accuracy and minimal performance overhead,
offering a practical solution for trustworthy LLM deployment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.09426v1">Security Analysis of ChatGPT: Threats and Privacy Risks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-13T02:03:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yushan Xiang, Zhongwen Li, Xiaoqi Li</p>
    <p><b>Summary:</b> As artificial intelligence technology continues to advance, chatbots are
becoming increasingly powerful. Among them, ChatGPT, launched by OpenAI, has
garnered widespread attention globally due to its powerful natural language
processing capabilities based on the GPT model, which enables it to engage in
natural conversations with users, understand various forms of linguistic
expressions, and generate useful information and suggestions. However, as its
application scope expands, user demand grows, and malicious attacks related to
it become increasingly frequent, the security threats and privacy risks faced
by ChatGPT are gradually coming to the forefront. In this paper, the security
of ChatGPT is mainly studied from two aspects, security threats and privacy
risks. The article systematically analyzes various types of vulnerabilities
involved in the above two types of problems and their causes. Briefly, we
discuss the controversies that ChatGPT may cause at the ethical and moral
levels. In addition, this paper reproduces several network attack and defense
test scenarios by simulating the attacker's perspective and methodology.
Simultaneously, it explores the feasibility of using ChatGPT for security
vulnerability detection and security tool generation from the defender's
perspective.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.09245v1">Beyond Blanket Masking: Examining Granularity for Privacy Protection in
  Images Captured by Blind and Low Vision Users</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-08-12T17:56:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jeffri Murrugarra-LLerena, Haoran Niu, K. Suzanne Barber, Hal Daumé III, Yang Trista Cao, Paola Cascante-Bonilla</p>
    <p><b>Summary:</b> As visual assistant systems powered by visual language models (VLMs) become
more prevalent, concerns over user privacy have grown, particularly for blind
and low vision users who may unknowingly capture personal private information
in their images. Existing privacy protection methods rely on coarse-grained
segmentation, which uniformly masks entire private objects, often at the cost
of usability. In this work, we propose FiGPriv, a fine-grained privacy
protection framework that selectively masks only high-risk private information
while preserving low-risk information. Our approach integrates fine-grained
segmentation with a data-driven risk scoring mechanism. We evaluate our
framework using the BIV-Priv-Seg dataset and show that FiG-Priv preserves +26%
of image content, enhancing the ability of VLMs to provide useful responses by
11% and identify the image content by 45%, while ensuring privacy protection.
Project Page: https://artcs1.github.io/VLMPrivacy/</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.09036v1">Can We Trust AI to Govern AI? Benchmarking LLM Performance on Privacy
  and AI Governance Exams</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-12T15:57:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zane Witherspoon, Thet Mon Aye, YingYing Hao</p>
    <p><b>Summary:</b> The rapid emergence of large language models (LLMs) has raised urgent
questions across the modern workforce about this new technology's strengths,
weaknesses, and capabilities. For privacy professionals, the question is
whether these AI systems can provide reliable support on regulatory compliance,
privacy program management, and AI governance. In this study, we evaluate ten
leading open and closed LLMs, including models from OpenAI, Anthropic, Google
DeepMind, Meta, and DeepSeek, by benchmarking their performance on
industry-standard certification exams: CIPP/US, CIPM, CIPT, and AIGP from the
International Association of Privacy Professionals (IAPP). Each model was
tested using official sample exams in a closed-book setting and compared to
IAPP's passing thresholds. Our findings show that several frontier models such
as Gemini 2.5 Pro and OpenAI's GPT-5 consistently achieve scores exceeding the
standards for professional human certification - demonstrating substantial
expertise in privacy law, technical controls, and AI governance. The results
highlight both the strengths and domain-specific gaps of current LLMs and offer
practical insights for privacy officers, compliance leads, and technologists
assessing the readiness of AI tools for high-stakes data governance roles. This
paper provides an overview for professionals navigating the intersection of AI
advancement and regulatory risk and establishes a machine benchmark based on
human-centric evaluations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.08785v1">Privacy-protected Retrieval-Augmented Generation for Knowledge Graph
  Question Answering</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-08-12T09:38:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yunfeng Ning, Mayi Xu, Jintao Wen, Qiankun Pi, Yuanyuan Zhu, Ming Zhong, Jiawei Jiang, Tieyun Qian</p>
    <p><b>Summary:</b> LLMs often suffer from hallucinations and outdated or incomplete knowledge.
RAG is proposed to address these issues by integrating external knowledge like
that in KGs into LLMs. However, leveraging private KGs in RAG systems poses
significant privacy risks due to the black-box nature of LLMs and potential
insecure data transmission, especially when using third-party LLM APIs lacking
transparency and control. In this paper, we investigate the privacy-protected
RAG scenario for the first time, where entities in KGs are anonymous for LLMs,
thus preventing them from accessing entity semantics. Due to the loss of
semantics of entities, previous RAG systems cannot retrieve question-relevant
knowledge from KGs by matching questions with the meaningless identifiers of
anonymous entities. To realize an effective RAG system in this scenario, two
key challenges must be addressed: (1) How can anonymous entities be converted
into retrievable information. (2) How to retrieve question-relevant anonymous
entities. Hence, we propose a novel ARoG framework including relation-centric
abstraction and structure-oriented abstraction strategies. For challenge (1),
the first strategy abstracts entities into high-level concepts by dynamically
capturing the semantics of their adjacent relations. It supplements meaningful
semantics which can further support the retrieval process. For challenge (2),
the second strategy transforms unstructured natural language questions into
structured abstract concept paths. These paths can be more effectively aligned
with the abstracted concepts in KGs, thereby improving retrieval performance.
To guide LLMs to effectively retrieve knowledge from KGs, the two strategies
strictly protect privacy from being exposed to LLMs. Experiments on three
datasets demonstrate that ARoG achieves strong performance and
privacy-robustness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.08749v2">Approximate DBSCAN under Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2025-08-12T08:55:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuan Qiu, Ke Yi</p>
    <p><b>Summary:</b> This paper revisits the DBSCAN problem under differential privacy (DP).
Existing DP-DBSCAN algorithms aim at publishing the cluster labels of the input
points. However, we show that both empirically and theoretically, this approach
cannot offer any utility in the published results. We therefore propose an
alternative definition of DP-DBSCAN based on the notion of spans. We argue that
publishing the spans actually better serves the purposes of visualization and
classification of DBSCAN. Then we present a linear-time DP-DBSCAN algorithm
achieving the sandwich quality guarantee in any constant dimensions, as well as
matching lower bounds on the approximation ratio. A key building block in our
algorithm is a linear-time algorithm for constructing a histogram under
pure-DP, which is of independent interest. Finally, we conducted experiments on
both synthetic and real-world datasets to verify the practical performance of
our DP-DBSCAN algorithm.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.09232v1">PETLP: A Privacy-by-Design Pipeline for Social Media Data in AI Research</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Multimedia-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2025-08-12T08:33:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nick Oh, Giorgos D. Vrakas, Siân J. M. Brooke, Sasha Morinière, Toju Duke</p>
    <p><b>Summary:</b> Social media data presents AI researchers with overlapping obligations under
the GDPR, copyright law, and platform terms -- yet existing frameworks fail to
integrate these regulatory domains, leaving researchers without unified
guidance. We introduce PETLP (Privacy-by-design Extract, Transform, Load, and
Present), a compliance framework that embeds legal safeguards directly into
extended ETL pipelines. Central to PETLP is treating Data Protection Impact
Assessments as living documents that evolve from pre-registration through
dissemination. Through systematic Reddit analysis, we demonstrate how
extraction rights fundamentally differ between qualifying research
organisations (who can invoke DSM Article 3 to override platform restrictions)
and commercial entities (bound by terms of service), whilst GDPR obligations
apply universally. We reveal why true anonymisation remains unachievable for
social media data and expose the legal gap between permitted dataset creation
and uncertain model distribution. By structuring compliance decisions into
practical workflows and simplifying institutional data management plans, PETLP
enables researchers to navigate regulatory complexity with confidence, bridging
the gap between legal requirements and research practice.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.14905v1">Privacy Preserving Inference of Personalized Content for Out of Matrix
  Users</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-08-12T02:55:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Michael Sun, Tai Vu, Andrew Wang</p>
    <p><b>Summary:</b> Recommender systems for niche and dynamic communities face persistent
challenges from data sparsity, cold start users and items, and privacy
constraints. Traditional collaborative filtering and content-based approaches
underperform in these settings, either requiring invasive user data or failing
when preference histories are absent. We present DeepNaniNet, a deep neural
recommendation framework that addresses these challenges through an inductive
graph-based architecture combining user-item interactions, item-item relations,
and rich textual review embeddings derived from BERT. Our design enables cold
start recommendations without profile mining, using a novel "content basket"
user representation and an autoencoder-based generalization strategy for unseen
users. We introduce AnimeULike, a new dataset of 10,000 anime titles and 13,000
users, to evaluate performance in realistic scenarios with high proportions of
guest or low-activity users. DeepNaniNet achieves state-of-the-art cold start
results on the CiteULike benchmark, matches DropoutNet in user recall without
performance degradation for out-of-matrix users, and outperforms Weighted
Matrix Factorization (WMF) and DropoutNet on AnimeULike warm start by up to 7x
and 1.5x in Recall@100, respectively. Our findings demonstrate that DeepNaniNet
delivers high-quality, privacy-preserving recommendations in data-sparse, cold
start-heavy environments while effectively integrating heterogeneous content
sources.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.08502v1">AirSignatureDB: Exploring In-Air Signature Biometrics in the Wild and
  its Privacy Concerns</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-08-11T22:24:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marta Robledo-Moreno, Ruben Vera-Rodriguez, Ruben Tolosana, Javier Ortega-Garcia, Andres Huergo, Julian Fierrez</p>
    <p><b>Summary:</b> Behavioral biometrics based on smartphone motion sensors are growing in
popularity for authentication purposes. In this study, AirSignatureDB is
presented: a new publicly accessible dataset of in-air signatures collected
from 108 participants under real-world conditions, using 83 different
smartphone models across four sessions. This dataset includes genuine samples
and skilled forgeries, enabling a comprehensive evaluation of system robustness
against realistic attack scenarios. Traditional and deep learning-based methods
for in-air signature verification are benchmarked, while analyzing the
influence of sensor modality and enrollment strategies. Beyond verification, a
first approach to reconstructing the three-dimensional trajectory of in-air
signatures from inertial sensor data alone is introduced. Using on-line
handwritten signatures as a reference, we demonstrate that the recovery of
accurate trajectories is feasible, challenging the long-held assumption that
in-air gestures are inherently traceless. Although this approach enables
forensic traceability, it also raises critical questions about the privacy
boundaries of behavioral biometrics. Our findings underscore the need for a
reevaluation of the privacy assumptions surrounding inertial sensor data, as
they can reveal user-specific information that had not previously been
considered in the design of in-air signature systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.08190v1">Differential Privacy for Regulatory Compliance in Cyberattack Detection
  on Critical Infrastructure Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-11T17:10:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Paritosh Ramanan, H. M. Mohaimanul Islam, Abhiram Reddy Alugula</p>
    <p><b>Summary:</b> Industrial control systems are a fundamental component of critical
infrastructure networks (CIN) such as gas, water and power. With the growing
risk of cyberattacks, regulatory compliance requirements are also increasing
for large scale critical infrastructure systems comprising multiple utility
stakeholders. The primary goal of regulators is to ensure overall system
stability with recourse to trustworthy stakeholder attack detection. However,
adhering to compliance requirements requires stakeholders to also disclose
sensor and control data to regulators raising privacy concerns. In this paper,
we present a cyberattack detection framework that utilizes differentially
private (DP) hypothesis tests geared towards enhancing regulatory confidence
while alleviating privacy concerns of CIN stakeholders. The hallmark of our
approach is a two phase privacy scheme that protects the privacy of covariance,
as well as the associated sensor driven test statistics computed as a means to
generate alarms. Theoretically, we show that our method induces a
misclassification error rate comparable to the non-DP cases while delivering
robust privacy guarantees. With the help of real-world datasets, we show the
reliability of our DP-detection outcomes for a wide variety of attack scenarios
for interdependent stakeholders.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.07960v1">VOIDFace: A Privacy-Preserving Multi-Network Face Recognition With
  Enhanced Security</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-08-11T13:15:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ajnas Muhammed, Iurri Medvedev, Nuno Gonçalves</p>
    <p><b>Summary:</b> Advancement of machine learning techniques, combined with the availability of
large-scale datasets, has significantly improved the accuracy and efficiency of
facial recognition. Modern facial recognition systems are trained using large
face datasets collected from diverse individuals or public repositories.
However, for training, these datasets are often replicated and stored in
multiple workstations, resulting in data replication, which complicates
database management and oversight. Currently, once a user submits their face
for dataset preparation, they lose control over how their data is used, raising
significant privacy and ethical concerns. This paper introduces VOIDFace, a
novel framework for facial recognition systems that addresses two major issues.
First, it eliminates the need of data replication and improves data control to
securely store training face data by using visual secret sharing. Second, it
proposes a patch-based multi-training network that uses this novel training
data storage mechanism to develop a robust, privacy-preserving facial
recognition system. By integrating these advancements, VOIDFace aims to improve
the privacy, security, and efficiency of facial recognition training, while
ensuring greater control over sensitive personal face data. VOIDFace also
enables users to exercise their Right-To-Be-Forgotten property to control their
personal data. Experimental evaluations on the VGGFace2 dataset show that
VOIDFace provides Right-To-Be-Forgotten, improved data control, security, and
privacy while maintaining competitive facial recognition performance. Code is
available at: https://github.com/ajnasmuhammed89/VOIDFace</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.07676v1">Multi-Hop Privacy Propagation for Differentially Private Federated
  Learning in Social Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB">
  <p><b>Published on:</b> 2025-08-11T06:53:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chenchen Lin, Xuehe Wang</p>
    <p><b>Summary:</b> Federated learning (FL) enables collaborative model training across
decentralized clients without sharing local data, thereby enhancing privacy and
facilitating collaboration among clients connected via social networks.
However, these social connections introduce privacy externalities: a client's
privacy loss depends not only on its privacy protection strategy but also on
the privacy decisions of others, propagated through the network via multi-hop
interactions. In this work, we propose a socially-aware privacy-preserving FL
mechanism that systematically quantifies indirect privacy leakage through a
multi-hop propagation model. We formulate the server-client interaction as a
two-stage Stackelberg game, where the server, as the leader, optimizes
incentive policies, and clients, as followers, strategically select their
privacy budgets, which determine their privacy-preserving levels by controlling
the magnitude of added noise. To mitigate information asymmetry in networked
privacy estimation, we introduce a mean-field estimator to approximate the
average external privacy risk. We theoretically prove the existence and
convergence of the fixed point of the mean-field estimator and derive
closed-form expressions for the Stackelberg Nash Equilibrium. Despite being
designed from a client-centric incentive perspective, our mechanism achieves
approximately-optimal social welfare, as revealed by Price of Anarchy (PoA)
analysis. Experiments on diverse datasets demonstrate that our approach
significantly improves client utilities and reduces server costs while
maintaining model performance, outperforming both Social-Agnostic (SA)
baselines and methods that account for social externalities.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.07672v1">Towards Aligning Personalized Conversational Recommendation Agents with
  Users' Privacy Preferences</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-08-11T06:51:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuning Zhang, Ying Ma, Jingruo Chen, Simin Li, Xin Yi, Hewu Li</p>
    <p><b>Summary:</b> The proliferation of AI agents, with their complex and context-dependent
actions, renders conventional privacy paradigms obsolete. This position paper
argues that the current model of privacy management, rooted in a user's
unilateral control over a passive tool, is inherently mismatched with the
dynamic and interactive nature of AI agents. We contend that ensuring effective
privacy protection necessitates that the agents proactively align with users'
privacy preferences instead of passively waiting for the user to control. To
ground this shift, and using personalized conversational recommendation agents
as a case, we propose a conceptual framework built on Contextual Integrity (CI)
theory and Privacy Calculus theory. This synthesis first reframes automatically
controlling users' privacy as an alignment problem, where AI agents initially
did not know users' preferences, and would learn their privacy preferences
through implicit or explicit feedback. Upon receiving the preference feedback,
the agents used alignment and Pareto optimization for aligning preferences and
balancing privacy and utility. We introduced formulations and instantiations,
potential applications, as well as five challenges.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.07667v1">1-2-3 Check: Enhancing Contextual Privacy in LLM via Multi-Agent
  Reasoning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-11T06:34:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenkai Li, Liwen Sun, Zhenxiang Guan, Xuhui Zhou, Maarten Sap</p>
    <p><b>Summary:</b> Addressing contextual privacy concerns remains challenging in interactive
settings where large language models (LLMs) process information from multiple
sources (e.g., summarizing meetings with private and public information). We
introduce a multi-agent framework that decomposes privacy reasoning into
specialized subtasks (extraction, classification), reducing the information
load on any single agent while enabling iterative validation and more reliable
adherence to contextual privacy norms. To understand how privacy errors emerge
and propagate, we conduct a systematic ablation over information-flow
topologies, revealing when and why upstream detection mistakes cascade into
downstream leakage. Experiments on the ConfAIde and PrivacyLens benchmark with
several open-source and closed-sourced LLMs demonstrate that our best
multi-agent configuration substantially reduces private information leakage
(\textbf{18\%} on ConfAIde and \textbf{19\%} on PrivacyLens with GPT-4o) while
preserving the fidelity of public content, outperforming single-agent
baselines. These results highlight the promise of principled information-flow
design in multi-agent systems for contextual privacy with LLMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.07664v1">Understanding Users' Privacy Perceptions Towards LLM's RAG-based Memory</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-08-11T06:26:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuning Zhang, Rongjun Ma, Ying Ma, Shixuan Li, Yiqun Xu, Xin Yi, Hewu Li</p>
    <p><b>Summary:</b> Large Language Models (LLMs) are increasingly integrating memory
functionalities to provide personalized and context-aware interactions.
However, user understanding, practices and expectations regarding these memory
systems are not yet well understood. This paper presents a thematic analysis of
semi-structured interviews with 18 users to explore their mental models of
LLM's Retrieval Augmented Generation (RAG)-based memory, current usage
practices, perceived benefits and drawbacks, privacy concerns and expectations
for future memory systems. Our findings reveal diverse and often incomplete
mental models of how memory operates. While users appreciate the potential for
enhanced personalization and efficiency, significant concerns exist regarding
privacy, control and the accuracy of remembered information. Users express a
desire for granular control over memory generation, management, usage and
updating, including clear mechanisms for reviewing, editing, deleting and
categorizing memories, as well as transparent insight into how memories and
inferred information are used. We discuss design implications for creating more
user-centric, transparent, and trustworthy LLM memory systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.07505v1">Enhancing Privacy in Decentralized Min-Max Optimization: A
  Differentially Private Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-08-10T23:24:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yueyang Quan, Chang Wang, Shengjie Zhai, Minghong Fang, Zhuqing Liu</p>
    <p><b>Summary:</b> Decentralized min-max optimization allows multi-agent systems to
collaboratively solve global min-max optimization problems by facilitating the
exchange of model updates among neighboring agents, eliminating the need for a
central server. However, sharing model updates in such systems carry a risk of
exposing sensitive data to inference attacks, raising significant privacy
concerns. To mitigate these privacy risks, differential privacy (DP) has become
a widely adopted technique for safeguarding individual data. Despite its
advantages, implementing DP in decentralized min-max optimization poses
challenges, as the added noise can hinder convergence, particularly in
non-convex scenarios with complex agent interactions in min-max optimization
problems. In this work, we propose an algorithm called DPMixSGD (Differential
Private Minmax Hybrid Stochastic Gradient Descent), a novel privacy-preserving
algorithm specifically designed for non-convex decentralized min-max
optimization. Our method builds on the state-of-the-art STORM-based algorithm,
one of the fastest decentralized min-max solutions. We rigorously prove that
the noise added to local gradients does not significantly compromise
convergence performance, and we provide theoretical bounds to ensure privacy
guarantees. To validate our theoretical findings, we conduct extensive
experiments across various tasks and models, demonstrating the effectiveness of
our approach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.07057v1">Rethinking Privacy Indicators in Extended Reality: Multimodal Design for
  Situationally Impaired Bystanders</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2025-08-09T17:48:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Syed Ibrahim Mustafa Shah Bukhari, Maha Sajid, Bo Ji, Brendan David-John</p>
    <p><b>Summary:</b> As Extended Reality (XR) devices become increasingly prevalent in everyday
settings, they raise significant privacy concerns for bystanders: individuals
in the vicinity of an XR device during its use, whom the device sensors may
accidentally capture. Current privacy indicators, such as small LEDs, often
presume that bystanders are attentive enough to interpret the privacy signals.
However, these cues can be easily overlooked when bystanders are distracted or
have limited vision. We define such individuals as situationally impaired
bystanders. This study explores XR privacy indicator designs that are effective
for situationally impaired bystanders. A focus group with eight participants
was conducted to design five novel privacy indicators. We evaluated these
designs through a user study with seven additional participants. Our results
show that visual-only indicators, typical in commercial XR devices, received
low ratings for perceived usefulness in impairment scenarios. In contrast,
multimodal indicators were preferred in privacy-sensitive scenarios with
situationally impaired bystanders. Ultimately, our results highlight the need
to move toward adaptable, multimodal, and situationally aware designs that
effectively support bystander privacy in everyday XR environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.07044v1">Balancing Privacy and Efficiency: Music Information Retrieval via
  Additive Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-09T17:00:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> William Zerong Wang, Dongfang Zhao</p>
    <p><b>Summary:</b> In the era of generative AI, ensuring the privacy of music data presents
unique challenges: unlike static artworks such as images, music data is
inherently temporal and multimodal, and it is sampled, transformed, and remixed
at an unprecedented scale. These characteristics make its core vector
embeddings, i.e, the numerical representations of the music, highly susceptible
to being learned, misused, or even stolen by models without accessing the
original audio files. Traditional methods like copyright licensing and digital
watermarking offer limited protection for these abstract mathematical
representations, thus necessitating a stronger, e.g., cryptographic, approach
to safeguarding the embeddings themselves. Standard encryption schemes, such as
AES, render data unintelligible for computation, making such searches
impossible. While Fully Homomorphic Encryption (FHE) provides a plausible
solution by allowing arbitrary computations on ciphertexts, its substantial
performance overhead remains impractical for large-scale vector similarity
searches. Given this trade-off, we propose a more practical approach using
Additive Homomorphic Encryption (AHE) for vector similarity search. The primary
contributions of this paper are threefold: we analyze threat models unique to
music information retrieval systems; we provide a theoretical analysis and
propose an efficient AHE-based solution through inner products of music
embeddings to deliver privacy-preserving similarity search; and finally, we
demonstrate the efficiency and practicality of the proposed approach through
empirical evaluation and comparison to FHE schemes on real-world MP3 files.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.06760v1">Understanding Privacy Norms Around LLM-Based Chatbots: A Contextual
  Integrity Perspective</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-08-09T00:22:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sarah Tran, Hongfan Lu, Isaac Slaughter, Bernease Herman, Aayushi Dangol, Yue Fu, Lufei Chen, Biniyam Gebreyohannes, Bill Howe, Alexis Hiniker, Nicholas Weber, Robert Wolfe</p>
    <p><b>Summary:</b> LLM-driven chatbots like ChatGPT have created large volumes of conversational
data, but little is known about how user privacy expectations are evolving with
this technology. We conduct a survey experiment with 300 US ChatGPT users to
understand emerging privacy norms for sharing chatbot data. Our findings reveal
a stark disconnect between user concerns and behavior: 82% of respondents rated
chatbot conversations as sensitive or highly sensitive - more than email or
social media posts - but nearly half reported discussing health topics and over
one-third discussed personal finances with ChatGPT. Participants expressed
strong privacy concerns (t(299) = 8.5, p < .01) and doubted their conversations
would remain private (t(299) = -6.9, p < .01). Despite this, respondents
uniformly rejected sharing personal data (search history, emails, device
access) for improved services, even in exchange for premium features worth
$200. To identify which factors influence appropriate chatbot data sharing, we
presented participants with factorial vignettes manipulating seven contextual
factors. Linear mixed models revealed that only the transmission factors such
as informed consent, data anonymization, or the removal of personally
identifiable information, significantly affected perceptions of appropriateness
and concern for data access. Surprisingly, contextual factors including the
recipient of the data (hospital vs. tech company), purpose (research vs.
advertising), type of content, and geographic location did not show significant
effects. Our results suggest that users apply consistent baseline privacy
expectations to chatbot data, prioritizing procedural safeguards over recipient
trustworthiness. This has important implications for emerging agentic AI
systems that assume user willingness to integrate personal data across
platforms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.06647v1">Privacy-Preserving Tabular Synthetic Data Generation Using TabularARGN</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-08-08T18:57:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Andrey Sidorenko, Paul Tiwald</p>
    <p><b>Summary:</b> Synthetic data generation has become essential for securely sharing and
analyzing sensitive data sets. Traditional anonymization techniques, however,
often fail to adequately preserve privacy. We introduce the Tabular
Auto-Regressive Generative Network (TabularARGN), a neural network architecture
specifically designed for generating high-quality synthetic tabular data. Using
a discretization-based auto-regressive approach, TabularARGN achieves high data
fidelity while remaining computationally efficient. We evaluate TabularARGN
against existing synthetic data generation methods, showing competitive results
in statistical similarity, machine learning utility, and detection robustness.
We further perform an in-depth privacy evaluation using systematic
membership-inference attacks, highlighting the robustness and effective
privacy-utility balance of our approach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.06301v1">FedMeNF: Privacy-Preserving Federated Meta-Learning for Neural Fields</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-08-08T13:24:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Junhyeog Yun, Minui Hong, Gunhee Kim</p>
    <p><b>Summary:</b> Neural fields provide a memory-efficient representation of data, which can
effectively handle diverse modalities and large-scale data. However, learning
to map neural fields often requires large amounts of training data and
computations, which can be limited to resource-constrained edge devices. One
approach to tackle this limitation is to leverage Federated Meta-Learning
(FML), but traditional FML approaches suffer from privacy leakage. To address
these issues, we introduce a novel FML approach called FedMeNF. FedMeNF
utilizes a new privacy-preserving loss function that regulates privacy leakage
in the local meta-optimization. This enables the local meta-learner to optimize
quickly and efficiently without retaining the client's private data. Our
experiments demonstrate that FedMeNF achieves fast optimization speed and
robust reconstruction performance, even with few-shot or non-IID data across
diverse data modalities, while preserving client data privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.06251v1">Synthetic Data Generation and Differential Privacy using Tensor
  Networks' Matrix Product States (MPS)</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2025-08-08T12:14:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alejandro Moreno R., Desale Fentaw, Samuel Palmer, Raúl Salles de Padua, Ninad Dixit, Samuel Mugel, Roman Orús, Manuel Radons, Josef Menter, Ali Abedi</p>
    <p><b>Summary:</b> Synthetic data generation is a key technique in modern artificial
intelligence, addressing data scarcity, privacy constraints, and the need for
diverse datasets in training robust models. In this work, we propose a method
for generating privacy-preserving high-quality synthetic tabular data using
Tensor Networks, specifically Matrix Product States (MPS). We benchmark the
MPS-based generative model against state-of-the-art models such as CTGAN, VAE,
and PrivBayes, focusing on both fidelity and privacy-preserving capabilities.
To ensure differential privacy (DP), we integrate noise injection and gradient
clipping during training, enabling privacy guarantees via R\'enyi Differential
Privacy accounting. Across multiple metrics analyzing data fidelity and
downstream machine learning task performance, our results show that MPS
outperforms classical models, particularly under strict privacy constraints.
This work highlights MPS as a promising tool for privacy-aware synthetic data
generation. By combining the expressive power of tensor network representations
with formal privacy mechanisms, the proposed approach offers an interpretable
and scalable alternative for secure data sharing. Its structured design
facilitates integration into sensitive domains where both data quality and
confidentiality are critical.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.06208v1">Graph Federated Learning for Personalized Privacy Recommendation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-08T10:44:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ce Na, Kai Yang, Dengzhao Fang, Yu Li, Jingtong Gao, Chengcheng Zhu, Jiale Zhang, Xiaobing Sun, Yi Chang</p>
    <p><b>Summary:</b> Federated recommendation systems (FedRecs) have gained significant attention
for providing privacy-preserving recommendation services. However, existing
FedRecs assume that all users have the same requirements for privacy
protection, i.e., they do not upload any data to the server. The approaches
overlook the potential to enhance the recommendation service by utilizing
publicly available user data. In real-world applications, users can choose to
be private or public. Private users' interaction data is not shared, while
public users' interaction data can be shared. Inspired by the issue, this paper
proposes a novel Graph Federated Learning for Personalized Privacy
Recommendation (GFed-PP) that adapts to different privacy requirements while
improving recommendation performance. GFed-PP incorporates the interaction data
of public users to build a user-item interaction graph, which is then used to
form a user relationship graph. A lightweight graph convolutional network (GCN)
is employed to learn each user's user-specific personalized item embedding. To
protect user privacy, each client learns the user embedding and the scoring
function locally. Additionally, GFed-PP achieves optimization of the federated
recommendation framework through the initialization of item embedding on
clients and the aggregation of the user relationship graph on the server.
Experimental results demonstrate that GFed-PP significantly outperforms
existing methods for five datasets, offering superior recommendation accuracy
without compromising privacy. This framework provides a practical solution for
accommodating varying privacy preferences in federated recommendation systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.06087v1">Adaptive Backtracking for Privacy Protection in Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2025-08-08T07:29:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhihao Yao, Yuxuan Gu, Xiachong Feng, Weitao Ma, Bo Li, Xiaocheng Feng</p>
    <p><b>Summary:</b> The preservation of privacy has emerged as a critical topic in the era of
artificial intelligence. However, current work focuses on user-oriented
privacy, overlooking severe enterprise data leakage risks exacerbated by the
Retrieval-Augmented Generation paradigm. To address this gap, our paper
introduces a novel objective: enterprise-oriented privacy concerns. Achieving
this objective requires overcoming two fundamental challenges: existing methods
such as data sanitization severely degrade model performance, and the field
lacks public datasets for evaluation. We address these challenges with several
solutions. (1) To prevent performance degradation, we propose ABack, a
training-free mechanism that leverages a Hidden State Model to pinpoint the
origin of a leakage intention and rewrite the output safely. (2) To solve the
lack of datasets, we construct PriGenQA, a new benchmark for enterprise privacy
scenarios in healthcare and finance. To ensure a rigorous evaluation, we move
beyond simple static attacks by developing a powerful adaptive attacker with
Group Relative Policy Optimization. Experiments show that against this superior
adversary, ABack improves the overall privacy utility score by up to 15\% over
strong baselines, avoiding the performance trade-offs of prior methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.09186v2">RL-MoE: An Image-Based Privacy Preserving Approach In Intelligent
  Transportation System</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-07T18:07:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abdolazim Rezaei, Mehdi Sookhak, Mahboobeh Haghparast</p>
    <p><b>Summary:</b> The proliferation of AI-powered cameras in Intelligent Transportation Systems
(ITS) creates a severe conflict between the need for rich visual data and the
right to privacy. Existing privacy-preserving methods, such as blurring or
encryption, are often insufficient due to creating an undesirable trade-off
where either privacy is compromised against advanced reconstruction attacks or
data utility is critically degraded. To resolve this challenge, we propose
RL-MoE, a novel framework that transforms sensitive visual data into
privacy-preserving textual descriptions, eliminating the need for direct image
transmission. RL-MoE uniquely combines a Mixture-of-Experts (MoE) architecture
for nuanced, multi-aspect scene decomposition with a Reinforcement Learning
(RL) agent that optimizes the generated text for a dual objective of semantic
accuracy and privacy preservation. Extensive experiments demonstrate that
RL-MoE provides superior privacy protection, reducing the success rate of
replay attacks to just 9.4\% on the CFP-FP dataset, while simultaneously
generating richer textual content than baseline methods. Our work provides a
practical and scalable solution for building trustworthy AI systems in
privacy-sensitive domains, paving the way for more secure smart city and
autonomous vehicle networks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.05518v1">Local Distance Query with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-07T15:48:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Weihong Sheng, Jiajun Chen, Bin Cai, Chunqiang Hu, Meng Han, Jiguo Yu</p>
    <p><b>Summary:</b> Differential Privacy (DP) is commonly employed to safeguard graph analysis or
publishing. Distance, a critical factor in graph analysis, is typically handled
using curator DP, where a trusted curator holds the complete neighbor lists of
all vertices and answers queries privately. However, in many real-world
scenarios, such a curator may not be present, posing a significant challenge
for implementing differentially private distance queries under Local
Differential Privacy (LDP). This paper proposes two approaches to address this
challenge. The first approach generates a synthetic graph by randomizing
responses and applies bitwise operations to reduce noise interference. However,
like other synthetic graph methods, this approach suffers from low utility. To
overcome this limitation, we propose a second approach, the first LDP method
specifically designed for distance queries, which captures the global graph
structure by continuously aggregating local distance vectors from neighboring
vertices. This process enables the accurate updating of global distances. We
demonstrate the effectiveness of our method through comprehensive theoretical
analysis and experimental evaluations on real-world datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.06577v1">Leveraging LLMs for Privacy-Aware Predictions in Participatory Budgeting</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-07T15:26:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Juan Zambrano, Clément Contet, Jairo Gudiño, Felipe Garrido-Lucero, Umberto Grandi, Cesar A Hidalgo</p>
    <p><b>Summary:</b> Participatory Budgeting (PB) empowers citizens to propose and vote on public
investment projects. Yet, despite its democratic potential, PB initiatives
often suffer from low participation rates, limiting their visibility and
perceived legitimacy. In this work, we aim to strengthen PB elections in two
key ways: by supporting project proposers in crafting better proposals, and by
helping PB organizers manage large volumes of submissions in a transparent
manner. We propose a privacy-preserving approach to predict which PB proposals
are likely to be funded, using only their textual descriptions and anonymous
historical voting records -- without relying on voter demographics or
personally identifiable information. We evaluate the performance of GPT 4 Turbo
in forecasting proposal outcomes across varying contextual scenarios, observing
that the LLM's prior knowledge needs to be complemented by past voting data to
obtain predictions reflecting real-world PB voting behavior. Our findings
highlight the potential of AI-driven tools to support PB processes by improving
transparency, planning efficiency, and civic engagement.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.05250v2">Privacy Disclosure of Similarity Rank in Speech and Language Processing</a></h3>
  
  <p><b>Published on:</b> 2025-08-07T10:40:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tom Bäckström, Mohammad Hassan Vali, My Nguyen, Silas Rech</p>
    <p><b>Summary:</b> Speaker, author, and other biometric identification applications often
compare a sample's similarity to a database of templates to determine the
identity. Given that data may be noisy and similarity measures can be
inaccurate, such a comparison may not reliably identify the true identity as
the most similar. Still, even the similarity rank based on an inaccurate
similarity measure can disclose private information about the true identity. We
propose a methodology for quantifying the privacy disclosure of such a
similarity rank by estimating its probability distribution. It is based on
determining the histogram of the similarity rank of the true speaker, or when
data is scarce, modeling the histogram with the beta-binomial distribution. We
express the disclosure in terms of entropy (bits), such that the disclosure
from independent features are additive. Our experiments demonstrate that all
tested speaker and author characterizations contain personally identifying
information (PII) that can aid in identification, with embeddings from speaker
recognition algorithms containing the most information, followed by phone
embeddings, linguistic embeddings, and fundamental frequency. Our initial
experiments show that the disclosure of PII increases with the length of test
samples, but it is bounded by the length of database templates. The provided
metric, similarity rank disclosure, provides a way to compare the disclosure of
PII between biometric features and merge them to aid identification. It can
thus aid in the holistic evaluation of threats to privacy in speech and other
biometric technologies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.04583v1">Measuring the Carbon Footprint of Cryptographic Privacy-Enhancing
  Technologies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-06T16:07:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marc Damie, Mihai Pop, Merijn Posthuma</p>
    <p><b>Summary:</b> Privacy-enhancing technologies (PETs) have attracted significant attention in
response to privacy regulations, driving the development of applications that
prioritize user data protection. At the same time, the information and
communication technology (ICT) sector faces growing pressure to reduce its
environmental footprint, particularly its carbon emissions. While numerous
studies have assessed the energy footprint of various ICT applications, the
environmental footprint of cryptographic PETs remains largely unexplored.
  Our work addresses this gap by proposing a standardized methodology for
evaluating the carbon footprint of PETs. To demonstrate this methodology, we
focus on PETs supporting client-server applications as they are the simplest to
deploy. In particular, we measure the energy consumption and carbon footprint
increase induced by five cryptographic PETs (compared to their non-private
equivalent): HTTPS web browsing, encrypted machine learning (ML) inference,
encrypted ML training, encrypted databases, and encrypted emails. Our findings
reveal significant variability in carbon footprint increases, ranging from a
twofold increase in HTTPS web browsing to a 100,000-fold increase in encrypted
ML.
  Our study provides essential data to help decision-makers assess
privacy-carbon trade-offs in such applications. Finally, we outline key
research directions for developing PETs that balance strong privacy protection
with environmental sustainability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.04542v1">Privacy Risk Predictions Based on Fundamental Understanding of Personal
  Data and an Evolving Threat Landscape</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B">
  <p><b>Published on:</b> 2025-08-06T15:30:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haoran Niu, K. Suzanne Barber</p>
    <p><b>Summary:</b> It is difficult for individuals and organizations to protect personal
information without a fundamental understanding of relative privacy risks. By
analyzing over 5,000 empirical identity theft and fraud cases, this research
identifies which types of personal data are exposed, how frequently exposures
occur, and what the consequences of those exposures are. We construct an
Identity Ecosystem graph--a foundational, graph-based model in which nodes
represent personally identifiable information (PII) attributes and edges
represent empirical disclosure relationships between them (e.g., the
probability that one PII attribute is exposed due to the exposure of another).
Leveraging this graph structure, we develop a privacy risk prediction framework
that uses graph theory and graph neural networks to estimate the likelihood of
further disclosures when certain PII attributes are compromised. The results
show that our approach effectively answers the core question: Can the
disclosure of a given identity attribute possibly lead to the disclosure of
another attribute?</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.04202v1">Unplug, Mute, Avoid: Investigating smart speaker users' privacy
  protection behaviours in Saudi Homes</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-08-06T08:32:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abdulrhman Alorini, Yufeng Wu, Abdullah Bin Sawad, Mukesh Prasad, A. Baki Kocaballi</p>
    <p><b>Summary:</b> Smart speakers are increasingly integrated into domestic life worldwide, yet
their privacy risks remain underexplored in non-Western cultural contexts. This
study investigates how Saudi Arabian users of smart speakers navigate privacy
concerns within collectivist, gendered, and often multigenerational households.
Using cultural probes followed by semi-structured interviews with 16
participants, we uncover everyday privacy-protective behaviours including
unplugging devices, muting microphones, and avoiding voice interactions
altogether. These practices are shaped not only by individual risk perceptions
but also by household norms, room configurations, and interpersonal dynamics.
We contribute empirical insights from an underrepresented region, theoretical
extensions to contextual integrity frameworks, and design directions for
culturally responsive voice interfaces. This work expands the global
conversation on smart speaker privacy and informs more inclusive HCI practices
in increasingly diverse smart home environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.03991v1">Galaxy: A Cognition-Centered Framework for Proactive,
  Privacy-Preserving, and Self-Evolving LLM Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-06T00:46:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chongyu Bao, Ruimin Dai, Yangbo Shen, Runyang Jian, Jinghan Zhang, Xiaolan Liu, Kunpeng Liu</p>
    <p><b>Summary:</b> Intelligent personal assistants (IPAs) such as Siri and Google Assistant are
designed to enhance human capabilities and perform tasks on behalf of users.
The emergence of LLM agents brings new opportunities for the development of
IPAs. While responsive capabilities have been widely studied, proactive
behaviors remain underexplored. Designing an IPA that is proactive,
privacy-preserving, and capable of self-evolution remains a significant
challenge. Designing such IPAs relies on the cognitive architecture of LLM
agents. This work proposes Cognition Forest, a semantic structure designed to
align cognitive modeling with system-level design. We unify cognitive
architecture and system design into a self-reinforcing loop instead of treating
them separately. Based on this principle, we present Galaxy, a framework that
supports multidimensional interactions and personalized capability generation.
Two cooperative agents are implemented based on Galaxy: KoRa, a
cognition-enhanced generative agent that supports both responsive and proactive
skills; and Kernel, a meta-cognition-based meta-agent that enables Galaxy's
self-evolution and privacy preservation. Experimental results show that Galaxy
outperforms multiple state-of-the-art benchmarks. Ablation studies and
real-world interaction cases validate the effectiveness of Galaxy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.03989v1">Dynamic User-controllable Privacy-preserving Few-shot Sensing Framework</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-06T00:44:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ajesh Koyatan Chathoth, Shuhao Yu, Stephen Lee</p>
    <p><b>Summary:</b> User-controllable privacy is important in modern sensing systems, as privacy
preferences can vary significantly from person to person and may evolve over
time. This is especially relevant in devices equipped with Inertial Measurement
Unit (IMU) sensors, such as smartphones and wearables, which continuously
collect rich time-series data that can inadvertently expose sensitive user
behaviors. While prior work has proposed privacy-preserving methods for sensor
data, most rely on static, predefined privacy labels or require large
quantities of private training data, limiting their adaptability and user
agency. In this work, we introduce PrivCLIP, a dynamic, user-controllable,
few-shot privacy-preserving sensing framework. PrivCLIP allows users to specify
and modify their privacy preferences by categorizing activities as sensitive
(black-listed), non-sensitive (white-listed), or neutral (gray-listed).
Leveraging a multimodal contrastive learning approach, PrivCLIP aligns IMU
sensor data with natural language activity descriptions in a shared embedding
space, enabling few-shot detection of sensitive activities. When a
privacy-sensitive activity is identified, the system uses a language-guided
activity sanitizer and a motion generation module (IMU-GPT) to transform the
original data into a privacy-compliant version that semantically resembles a
non-sensitive activity. We evaluate PrivCLIP on multiple human activity
recognition datasets and demonstrate that it significantly outperforms baseline
methods in terms of both privacy protection and data utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.03836v1">DP-NCB: Privacy Preserving Fair Bandits</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2025-08-05T18:34:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dhruv Sarkar, Nishant Pandey, Sayak Ray Chowdhury</p>
    <p><b>Summary:</b> Multi-armed bandit algorithms are fundamental tools for sequential
decision-making under uncertainty, with widespread applications across domains
such as clinical trials and personalized decision-making. As bandit algorithms
are increasingly deployed in these socially sensitive settings, it becomes
critical to protect user data privacy and ensure fair treatment across decision
rounds. While prior work has independently addressed privacy and fairness in
bandit settings, the question of whether both objectives can be achieved
simultaneously has remained largely open. Existing privacy-preserving bandit
algorithms typically optimize average regret, a utilitarian measure, whereas
fairness-aware approaches focus on minimizing Nash regret, which penalizes
inequitable reward distributions, but often disregard privacy concerns.
  To bridge this gap, we introduce Differentially Private Nash Confidence Bound
(DP-NCB)-a novel and unified algorithmic framework that simultaneously ensures
$\epsilon$-differential privacy and achieves order-optimal Nash regret,
matching known lower bounds up to logarithmic factors. The framework is
sufficiently general to operate under both global and local differential
privacy models, and is anytime, requiring no prior knowledge of the time
horizon. We support our theoretical guarantees with simulations on synthetic
bandit instances, showing that DP-NCB incurs substantially lower Nash regret
than state-of-the-art baselines. Our results offer a principled foundation for
designing bandit algorithms that are both privacy-preserving and fair, making
them suitable for high-stakes, socially impactful applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.03831v1">A Type System for Data Privacy Compliance in Active Object Languages</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Programming Languages-D91E36">
  <p><b>Published on:</b> 2025-08-05T18:21:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chinmayi Prabhu Baramashetru, Paola Giannini, Silvia Lizeth Tapia Tarifa, Olaf Owe</p>
    <p><b>Summary:</b> Data protection laws such as GDPR aim to give users unprecedented control
over their personal data. Compliance with these regulations requires
systematically considering information flow and interactions among entities
handling sensitive data. Privacy-by-design principles advocate embedding data
protection into system architectures as a default. However, translating these
abstract principles into concrete, explicit methods remains a significant
challenge. This paper addresses this gap by proposing a language-based approach
to privacy integration, combining static and runtime techniques. By employing
type checking and type inference in an active object language, the framework
enables the tracking of authorised data flows and the automatic generation of
constraints checked at runtime based on user consent. This ensures that
personal data is processed in compliance with GDPR constraints. The key
contribution of this work is a type system that gather the compliance checks
and the changes to users consent and integrates data privacy compliance
verification into system execution. The paper demonstrates the feasibility of
this approach through a soundness proof and several examples, illustrating how
the proposed language addresses common GDPR requirements, such as user consent,
purpose limitation, and data subject rights. This work advances the state of
the art in privacy-aware system design by offering a systematic and automated
method for integrating GDPR compliance into programming languages. This
capability has implications for building trustworthy systems in domains such as
healthcare or finance, where data privacy is crucial.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.03413v1">Smart Car Privacy: Survey of Attacks and Privacy Issues</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-05T12:59:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Akshay Madhav Deshmukh</p>
    <p><b>Summary:</b> Automobiles are becoming increasingly important in our day to day life.
Modern automobiles are highly computerized and hence potentially vulnerable to
attack. Providing many wireless connectivity for vehicles enables a bridge
between vehicles and their external environments. Such a connected vehicle
solution is expected to be the next frontier for automotive revolution and the
key to the evolution to next generation intelligent transportation systems.
Vehicular Ad hoc Networks (VANETs) are emerging mobile ad hoc network
technologies incorporating mobile routing protocols for inter-vehicle data
communications to support intelligent transportation systems. Thus security and
privacy are the major concerns in VANETs due to the mobility of the vehicles.
Thus designing security mechanisms to remove adversaries from the network
remarkably important in VANETs.
  This paper provides an overview of various vehicular network architectures.
The evolution of security in modern vehicles. Various security and privacy
attacks in VANETs with their defending mechanisms with examples and classify
these mechanisms. It also provides an overview of various privacy implication
that a vehicular network possess.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.03209v1">GeoShield: Safeguarding Geolocation Privacy from Vision-Language Models
  via Adversarial Perturbations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-05T08:37:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xinwei Liu, Xiaojun Jia, Yuan Xun, Simeng Qin, Xiaochun Cao</p>
    <p><b>Summary:</b> Vision-Language Models (VLMs) such as GPT-4o now demonstrate a remarkable
ability to infer users' locations from public shared images, posing a
substantial risk to geoprivacy. Although adversarial perturbations offer a
potential defense, current methods are ill-suited for this scenario: they often
perform poorly on high-resolution images and low perturbation budgets, and may
introduce irrelevant semantic content. To address these limitations, we propose
GeoShield, a novel adversarial framework designed for robust geoprivacy
protection in real-world scenarios. GeoShield comprises three key modules: a
feature disentanglement module that separates geographical and non-geographical
information, an exposure element identification module that pinpoints
geo-revealing regions within an image, and a scale-adaptive enhancement module
that jointly optimizes perturbations at both global and local levels to ensure
effectiveness across resolutions. Extensive experiments on challenging
benchmarks show that GeoShield consistently surpasses prior methods in
black-box settings, achieving strong privacy protection with minimal impact on
visual or semantic quality. To our knowledge, this work is the first to explore
adversarial perturbations for defending against geolocation inference by
advanced VLMs, providing a practical and effective solution to escalating
privacy concerns.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.03204v1">Current State in Privacy-Preserving Text Preprocessing for
  Domain-Agnostic NLP</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-08-05T08:26:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abhirup Sinha, Pritilata Saha, Tithi Saha</p>
    <p><b>Summary:</b> Privacy is a fundamental human right. Data privacy is protected by different
regulations, such as GDPR. However, modern large language models require a huge
amount of data to learn linguistic variations, and the data often contains
private information. Research has shown that it is possible to extract private
information from such language models. Thus, anonymizing such private and
sensitive information is of utmost importance. While complete anonymization may
not be possible, a number of different pre-processing approaches exist for
masking or pseudonymizing private information in textual data. This report
focuses on a few of such approaches for domain-agnostic NLP tasks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.03098v1">Privacy-Aware Decoding: Mitigating Privacy Leakage of Large Language
  Models in Retrieval-Augmented Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-08-05T05:22:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haoran Wang, Xiongxiao Xu, Baixiang Huang, Kai Shu</p>
    <p><b>Summary:</b> Retrieval-Augmented Generation (RAG) enhances the factual accuracy of large
language models (LLMs) by conditioning outputs on external knowledge sources.
However, when retrieval involves private or sensitive data, RAG systems are
susceptible to extraction attacks that can leak confidential information
through generated responses. We propose Privacy-Aware Decoding (PAD), a
lightweight, inference-time defense that adaptively injects calibrated Gaussian
noise into token logits during generation. PAD integrates confidence-based
screening to selectively protect high-risk tokens, efficient sensitivity
estimation to minimize unnecessary noise, and context-aware noise calibration
to balance privacy with generation quality. A \renyi Differential Privacy (RDP)
accountant rigorously tracks cumulative privacy loss, enabling explicit
per-response $(\varepsilon, \delta)$-DP guarantees for sensitive outputs.
Unlike prior approaches requiring retraining or corpus-level filtering, PAD is
model-agnostic and operates entirely at decoding time with minimal
computational overhead. Experiments on three real-world datasets demonstrate
that PAD substantially reduces private information leakage while preserving
response utility, outperforming existing retrieval- and post-processing-based
defenses. Our work takes an important step toward mitigating privacy risks in
RAG via decoding strategies, paving the way for universal and scalable privacy
solutions in sensitive domains. Our code is available:
https://github.com/wang2226/PAD.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.02551v1">PrivAR: Real-Time Privacy Protection for Location-Based Augmented
  Reality Applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-04T16:02:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shafizur Rahman Seeam, Ye Zheng, Zhengxiong Li, Yidan Hu</p>
    <p><b>Summary:</b> Location-based augmented reality (LB-AR) applications, such as Pok\'emon Go,
stream sub-second GPS updates to deliver responsive and immersive user
experiences. However, this high-frequency location reporting introduces serious
privacy risks. Protecting privacy in LB-AR is significantly more challenging
than in traditional location-based services (LBS), as it demands real-time
location protection with strong per-location and trajectory-level privacy
guaranteed while maintaining low latency and high quality of service (QoS).
Existing methods fail to meet these combined demands.
  To fill the gap, we present PrivAR, the first client-side privacy framework
for real-time LB-AR. PrivAR introduces two lightweight mechanisms: (i) Planar
Staircase Mechanism (PSM) which designs a staircase-shaped distribution to
generate noisy location with strong per-location privacy and low expected
error; and (ii) Thresholded Reporting with PSM (TR-PSM), a selective scheme
that releases a noisy location update only when a displacement exceeds a
private threshold, enabling many-to-one mappings for enhanced trace-level
privacy while preserving high QoS. We present theoretical analysis, extensive
experiments on two public datasets and our proprietary GeoTrace dataset, and
validate PrivAR on a Pok\'emon-Go-style prototype. Results show PrivAR improves
QoS (Gamescore) by up to 50%, while increasing attacker error by 1.8x over
baseline with an additional 0.06 milliseconds runtime overhead.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.02483v1">Revisiting the Privacy of Low-Frequency Speech Signals: Exploring
  Resampling Methods, Evaluation Scenarios, and Speaker Characteristics</a></h3>
  
  <p><b>Published on:</b> 2025-08-04T14:53:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jule Pohlhausen, Jörg Bitzer</p>
    <p><b>Summary:</b> While audio recordings in real life provide insights into social dynamics and
conversational behavior, they also raise concerns about the privacy of
personal, sensitive data. This article explores the effectiveness of
restricting recordings to low-frequency audio to protect spoken content. For
resampling the audio signals to different sampling rates, we compare the effect
of employing anti-aliasing filtering. Privacy enhancement is measured by an
increased word error rate of automatic speech recognition models. The impact on
utility performance is measured with voice activity detection models. Our
experimental results show that for clean recordings, models trained with a
sampling rate of up to 800 Hz transcribe the majority of words correctly. For
both models, we analyzed the impact of the speaker's sex and pitch, and we
demonstrated that missing anti-aliasing filters more strongly compromise speech
privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.02461v1">Experimental Evaluation of Post-Quantum Homomorphic Encryption for
  Privacy-Preserving V2X Communication</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-04T14:28:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abdullah Al Mamun, Kyle Yates, Antsa Rakotondrafara, Mashrur Chowdhury, Ryann Cartor, Shuhong Gao</p>
    <p><b>Summary:</b> Intelligent Transportation Systems (ITS) fundamentally rely on
vehicle-generated data for applications such as congestion monitoring and route
optimization, making the preservation of user privacy a critical challenge.
Homomorphic Encryption (HE) offers a promising solution by enabling computation
on encrypted data without revealing underlying content. This study presents the
first real-world experimental evaluation of three post-quantum secure HE
schemes, i.e., Brakerski-Fan-Vercauteren (BFV), Brakerski-Gentry-Vaikuntanathan
(BGV), and Cheon-Kim-Kim-Song (CKKS), for vehicular communication scenarios.
Two representative privacy-preserving use cases are considered: encrypted
vehicle counting and average speed aggregation. Experiments are conducted over
both Wi-Fi and Ethernet to assess performance under wireless and wired
vehicle-to-everything (V2X) settings. Results show that BFV and BGV are
suitable for latency-tolerant applications such as intersection monitoring and
regional traffic analysis, with total end-to-end latencies under 10 seconds.
While CKKS experiences higher overhead, it remains viable for periodic
encrypted aggregation of numerical data. The experimental results demonstrate
that HE can be feasibly deployed in ITS environments under 128-bit post-quantum
security, provided that scheme-specific latency constraints are considered.
This reinforces its potential to serve as a foundational tool for secure and
privacy-preserving V2X data processing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.02034v1">Protego: User-Centric Pose-Invariant Privacy Protection Against Face
  Recognition-Induced Digital Footprint Exposure</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-08-04T04:03:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ziling Wang, Shuya Yang, Jialin Lu, Ka-Ho Chow</p>
    <p><b>Summary:</b> Face recognition (FR) technologies are increasingly used to power large-scale
image retrieval systems, raising serious privacy concerns. Services like
Clearview AI and PimEyes allow anyone to upload a facial photo and retrieve a
large amount of online content associated with that person. This not only
enables identity inference but also exposes their digital footprint, such as
social media activity, private photos, and news reports, often without their
consent. In response to this emerging threat, we propose Protego, a
user-centric privacy protection method that safeguards facial images from such
retrieval-based privacy intrusions. Protego encapsulates a user's 3D facial
signatures into a pose-invariant 2D representation, which is dynamically
deformed into a natural-looking 3D mask tailored to the pose and expression of
any facial image of the user, and applied prior to online sharing. Motivated by
a critical limitation of existing methods, Protego amplifies the sensitivity of
FR models so that protected images cannot be matched even among themselves.
Experiments show that Protego significantly reduces retrieval accuracy across a
wide range of black-box FR models and performs at least 2x better than existing
methods. It also offers unprecedented visual coherence, particularly in video
settings where consistency and natural appearance are essential. Overall,
Protego contributes to the fight against the misuse of FR for mass surveillance
and unsolicited identity tracing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.01960v1">Non-Verbal Vocalisations and their Challenges: Emotion, Privacy,
  Sparseness, and Real Life</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">   
  <p><b>Published on:</b> 2025-08-03T23:59:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anton Batliner, Shahin Amiriparian, Björn W. Schuller</p>
    <p><b>Summary:</b> Non-Verbal Vocalisations (NVVs) are short `non-word' utterances without
proper linguistic (semantic) meaning but conveying connotations -- be this
emotions/affects or other paralinguistic information. We start this
contribution with a historic sketch: how they were addressed in psychology and
linguistics in the last two centuries, how they were neglected later on, and
how they came to the fore with the advent of emotion research. We then give an
overview of types of NVVs (formal aspects) and functions of NVVs, exemplified
with the typical NVV \textit{ah}. Interesting as they are, NVVs come, however,
with a bunch of challenges that should be accounted for: Privacy and general
ethical considerations prevent them of being recorded in real-life (private)
scenarios to a sufficient extent. Isolated, prompted (acted) exemplars do not
necessarily model NVVs in context; yet, this is the preferred strategy so far
when modelling NVVs, especially in AI. To overcome these problems, we argue in
favour of corpus-based approaches. This guarantees a more realistic modelling;
however, we are still faced with privacy and sparse data problems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.01898v1">Revenue Optimization in Wireless Video Caching Networks: A
  Privacy-Preserving Two-Stage Solution</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36"> 
  <p><b>Published on:</b> 2025-08-03T19:16:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yijing Zhang, Md-Ferdous Pervej, Andreas F. Molisch</p>
    <p><b>Summary:</b> Video caching can significantly improve delivery efficiency and enhance
quality of video streaming, which constitutes the majority of wireless
communication traffic. Due to limited cache size, caching strategies must be
designed to adapt to and dynamic user demand in order to maximize system
revenue. The system revenue depends on the benefits of delivering the requested
videos and costs for (a) transporting the files to the users and (b) cache
replacement. Since the cache content at any point in time impacts the
replacement costs in the future, demand predictions over multiple cache
placement slots become an important prerequisite for efficient cache planning.
Motivated by this, we introduce a novel two-stage privacy-preserving solution
for revenue optimization in wireless video caching networks. First, we train a
Transformer using privacy-preserving federated learning (FL) to predict
multi-slot future demands. Given that prediction results are never entirely
accurate, especially for longer horizons, we further combine global content
popularity with per-user prediction results to estimate the content demand
distribution. Then, in the second stage, we leverage these estimation results
to find caching strategies that maximize the long-term system revenue. This
latter problem takes on the form of a multi-stage knapsack problem, which we
then transform to a integer linear program. Our extensive simulation results
demonstrate that (i) our FL solution delivers nearly identical performance to
that of the ideal centralized solution and outperforms other existing caching
methods, and (ii) our novel revenue optimization approach provides deeper
system performance insights than traditional cache hit ratio (CHR)-based
optimization approaches.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.01798v1">A Survey on Privacy-Preserving Computing in the Automotive Domain</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-03T15:23:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nergiz Yuca, Nikolay Matyunin, Ektor Arzoglou, Nikolaos Athanasios Anagnostopoulos, Stefan Katzenbeisser</p>
    <p><b>Summary:</b> As vehicles become increasingly connected and autonomous, they accumulate and
manage various personal data, thereby presenting a key challenge in preserving
privacy during data sharing and processing. This survey reviews applications of
Secure Multi-Party Computation (MPC) and Homomorphic Encryption (HE) that
address these privacy concerns in the automotive domain. First, we identify the
scope of privacy-sensitive use cases for these technologies, by surveying
existing works that address privacy issues in different automotive contexts,
such as location-based services, mobility infrastructures, traffic management,
etc. Then, we review recent works that employ MPC and HE as solutions for these
use cases in detail. Our survey highlights the applicability of these
privacy-preserving technologies in the automotive context, while also
identifying challenges and gaps in the current research landscape. This work
aims to provide a clear and comprehensive overview of this emerging field and
to encourage further research in this domain.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.01749v1">Improving Noise Efficiency in Privacy-preserving Dataset Distillation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-08-03T13:15:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Runkai Zheng, Vishnu Asutosh Dasu, Yinong Oliver Wang, Haohan Wang, Fernando De la Torre</p>
    <p><b>Summary:</b> Modern machine learning models heavily rely on large datasets that often
include sensitive and private information, raising serious privacy concerns.
Differentially private (DP) data generation offers a solution by creating
synthetic datasets that limit the leakage of private information within a
predefined privacy budget; however, it requires a substantial amount of data to
achieve performance comparable to models trained on the original data. To
mitigate the significant expense incurred with synthetic data generation,
Dataset Distillation (DD) stands out for its remarkable training and storage
efficiency. This efficiency is particularly advantageous when integrated with
DP mechanisms, curating compact yet informative synthetic datasets without
compromising privacy. However, current state-of-the-art private DD methods
suffer from a synchronized sampling-optimization process and the dependency on
noisy training signals from randomly initialized networks. This results in the
inefficient utilization of private information due to the addition of excessive
noise. To address these issues, we introduce a novel framework that decouples
sampling from optimization for better convergence and improves signal quality
by mitigating the impact of DP noise through matching in an informative
subspace. On CIFAR-10, our method achieves a \textbf{10.0\%} improvement with
50 images per class and \textbf{8.3\%} increase with just \textbf{one-fifth}
the distilled set size of previous state-of-the-art methods, demonstrating
significant potential to advance privacy-preserving DD.</p>
  </details>
</div>

