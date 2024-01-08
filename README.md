
<h2>2024-01</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.02453v1">Adaptive Differential Privacy in Federated Learning: A Priority-Based
  Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-01-04T03:01:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mahtab Talaei, Iman Izadi</p>
    <p><b>Summary:</b> Federated learning (FL) as one of the novel branches of distributed machine
learning (ML), develops global models through a private procedure without
direct access to local datasets. However, access to model updates (e.g.
gradient updates in deep neural networks) transferred between clients and
servers can reveal sensitive information to adversaries. Differential privacy
(DP) offers a framework that gives a privacy guarantee by adding certain
amounts of noise to parameters. This approach, although being effective in
terms of privacy, adversely affects model performance due to noise involvement.
Hence, it is always needed to find a balance between noise injection and the
sacrificed accuracy. To address this challenge, we propose adaptive noise
addition in FL which decides the value of injected noise based on features'
relative importance. Here, we first propose two effective methods for
prioritizing features in deep neural network models and then perturb models'
weights based on this information. Specifically, we try to figure out whether
the idea of adding more noise to less important parameters and less noise to
more important parameters can effectively save the model accuracy while
preserving privacy. Our experiments confirm this statement under some
conditions. The amount of noise injected, the proportion of parameters
involved, and the number of global iterations can significantly change the
output. While a careful choice of parameters by considering the properties of
datasets can improve privacy without intense loss of accuracy, a bad choice can
make the model performance worse.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.01589v1">The Security and Privacy of Mobile Edge Computing: An Artificial
  Intelligence Perspective</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-01-03T07:47:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Cheng Wang, Zenghui Yuan, Pan Zhou, Zichuan Xu, Ruixuan Li, Dapeng Oliver Wu</p>
    <p><b>Summary:</b> Mobile Edge Computing (MEC) is a new computing paradigm that enables cloud
computing and information technology (IT) services to be delivered at the
network's edge. By shifting the load of cloud computing to individual local
servers, MEC helps meet the requirements of ultralow latency, localized data
processing, and extends the potential of Internet of Things (IoT) for
end-users. However, the crosscutting nature of MEC and the multidisciplinary
components necessary for its deployment have presented additional security and
privacy concerns. Fortunately, Artificial Intelligence (AI) algorithms can cope
with excessively unpredictable and complex data, which offers a distinct
advantage in dealing with sophisticated and developing adversaries in the
security industry. Hence, in this paper we comprehensively provide a survey of
security and privacy in MEC from the perspective of AI. On the one hand, we use
European Telecommunications Standards Institute (ETSI) MEC reference
architecture as our based framework while merging the Software Defined Network
(SDN) and Network Function Virtualization (NFV) to better illustrate a
serviceable platform of MEC. On the other hand, we focus on new security and
privacy issues, as well as potential solutions from the viewpoints of AI.
Finally, we comprehensively discuss the opportunities and challenges associated
with applying AI to MEC security and privacy as possible future research
directions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.01575v1">Enhancing Generalization of Invisible Facial Privacy Cloak via Gradient
  Accumulation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-01-03T07:00:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xuannan Liu, Yaoyao Zhong, Weihong Deng, Hongzhi Shi, Xingchen Cui, Yunfeng Yin, Dongchao Wen</p>
    <p><b>Summary:</b> The blooming of social media and face recognition (FR) systems has increased
people's concern about privacy and security. A new type of adversarial privacy
cloak (class-universal) can be applied to all the images of regular users, to
prevent malicious FR systems from acquiring their identity information. In this
work, we discover the optimization dilemma in the existing methods -- the local
optima problem in large-batch optimization and the gradient information
elimination problem in small-batch optimization. To solve these problems, we
propose Gradient Accumulation (GA) to aggregate multiple small-batch gradients
into a one-step iterative gradient to enhance the gradient stability and reduce
the usage of quantization operations. Experiments show that our proposed method
achieves high performance on the Privacy-Commons dataset against black-box face
recognition models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.01294v1">Efficient Sparse Least Absolute Deviation Regression with Differential
  Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">  
  <p><b>Published on:</b> 2024-01-02T17:13:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Weidong Liu, Xiaojun Mao, Xiaofei Zhang, Xin Zhang</p>
    <p><b>Summary:</b> In recent years, privacy-preserving machine learning algorithms have
attracted increasing attention because of their important applications in many
scientific fields. However, in the literature, most privacy-preserving
algorithms demand learning objectives to be strongly convex and Lipschitz
smooth, which thus cannot cover a wide class of robust loss functions (e.g.,
quantile/least absolute loss). In this work, we aim to develop a fast
privacy-preserving learning solution for a sparse robust regression problem.
Our learning loss consists of a robust least absolute loss and an $\ell_1$
sparse penalty term. To fast solve the non-smooth loss under a given privacy
budget, we develop a Fast Robust And Privacy-Preserving Estimation (FRAPPE)
algorithm for least absolute deviation regression. Our algorithm achieves a
fast estimation by reformulating the sparse LAD problem as a penalized least
square estimation problem and adopts a three-stage noise injection to guarantee
the $(\epsilon,\delta)$-differential privacy. We show that our algorithm can
achieve better privacy and statistical accuracy trade-off compared with the
state-of-the-art privacy-preserving regression algorithms. In the end, we
conduct experiments to verify the efficiency of our proposed FRAPPE algorithm.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.01204v1">PPBFL: A Privacy Protected Blockchain-based Federated Learning Model</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-01-02T13:13:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yang Li, Chunhe Xia, Wanshuang Lin, Tianbo Wang</p>
    <p><b>Summary:</b> With the rapid development of machine learning and growing concerns about
data privacy, federated learning has become an increasingly prominent focus.
However, challenges such as attacks on model parameters and the lack of
incentive mechanisms hinder the effectiveness of federated learning. Therefore,
we propose a Privacy Protected Blockchain-based Federated Learning Model
(PPBFL) to enhance the security of federated learning and promote the active
participation of nodes in model training. Blockchain ensures that model
parameters stored in the InterPlanetary File System (IPFS) remain unaltered. A
novel adaptive differential privacy addition algorithm is simultaneously
applied to local and global models, preserving the privacy of local models and
preventing a decrease in the security of the global model due to the presence
of numerous local models in federated learning. Additionally, we introduce a
new mix transactions mechanism to better protect the identity privacy of local
training clients. Security analysis and experimental results demonstrate that
PPBFL outperforms baseline methods in both model performance and security.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.01146v1">Privacy Preserving Personal Assistant with On-Device Diarization and
  Spoken Dialogue System for Home and Beyond</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-01-02T10:56:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gérard Chollet, Hugues Sansen, Yannis Tevissen, Jérôme Boudy, Mossaab Hariz, Christophe Lohr, Fathy Yassa</p>
    <p><b>Summary:</b> In the age of personal voice assistants, the question of privacy arises.
These digital companions often lack memory of past interactions, while relying
heavily on the internet for speech processing, raising privacy concerns. Modern
smartphones now enable on-device speech processing, making cloud-based
solutions unnecessary. Personal assistants for the elderly should excel at
memory recall, especially in medical examinations. The e-ViTA project developed
a versatile conversational application with local processing and speaker
recognition. This paper highlights the importance of speaker diarization
enriched with sensor data fusion for contextualized conversation preservation.
The use cases applied to the e-VITA project have shown that truly personalized
dialogue is pivotal for individual voice assistants. Secure local processing
and sensor data fusion ensure virtual companions meet individual user needs
without compromising privacy or data security.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.00973v1">Facebook Report on Privacy of fNIRS data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-01-01T23:30:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Md Imran Hossen, Sai Venkatesh Chilukoti, Liqun Shan, Vijay Srinivas Tida, Xiali Hei</p>
    <p><b>Summary:</b> The primary goal of this project is to develop privacy-preserving machine
learning model training techniques for fNIRS data. This project will build a
local model in a centralized setting with both differential privacy (DP) and
certified robustness. It will also explore collaborative federated learning to
train a shared model between multiple clients without sharing local fNIRS
datasets. To prevent unintentional private information leakage of such clients'
private datasets, we will also implement DP in the federated learning setting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.00794v1">Privacy-Preserving Data in IoT-based Cloud Systems: A Comprehensive
  Survey with AI Integration</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-01-01T15:48:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> D. Dhinakaran, S. M. Udhaya Sankar, D. Selvaraj, S. Edwin Raja</p>
    <p><b>Summary:</b> As the integration of Internet of Things devices with cloud computing
proliferates, the paramount importance of privacy preservation comes to the
forefront. This survey paper meticulously explores the landscape of privacy
issues in the dynamic intersection of IoT and cloud systems. The comprehensive
literature review synthesizes existing research, illuminating key challenges
and discerning emerging trends in privacy preserving techniques. The
categorization of diverse approaches unveils a nuanced understanding of
encryption techniques, anonymization strategies, access control mechanisms, and
the burgeoning integration of artificial intelligence. Notable trends include
the infusion of machine learning for dynamic anonymization, homomorphic
encryption for secure computation, and AI-driven access control systems. The
culmination of this survey contributes a holistic view, laying the groundwork
for understanding the multifaceted strategies employed in securing sensitive
data within IoT-based cloud environments. The insights garnered from this
survey provide a valuable resource for researchers, practitioners, and
policymakers navigating the complex terrain of privacy preservation in the
evolving landscape of IoT and cloud computing</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.00793v1">SecFormer: Towards Fast and Accurate Privacy-Preserving Inference for
  Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-01-01T15:40:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jinglong Luo, Yehong Zhang, Jiaqi Zhang, Xin Mu, Hui Wang, Yue Yu, Zenglin Xu</p>
    <p><b>Summary:</b> With the growing use of large language models hosted on cloud platforms to
offer inference services, privacy concerns are escalating, especially
concerning sensitive data like investment plans and bank account details.
Secure Multi-Party Computing (SMPC) emerges as a promising solution to protect
the privacy of inference data and model parameters. However, the application of
SMPC in Privacy-Preserving Inference (PPI) for large language models,
particularly those based on the Transformer architecture, often leads to
considerable slowdowns or declines in performance. This is largely due to the
multitude of nonlinear operations in the Transformer architecture, which are
not well-suited to SMPC and are difficult to circumvent or optimize
effectively. To address this concern, we introduce an advanced optimization
framework called SecFormer, designed to strike an optimal balance between
performance and efficiency in PPI for Transformer models. By implementing
knowledge distillation techniques, we successfully eliminate the high-cost
exponential and maximum operations in PPI without sacrificing model
performance. Additionally, we have developed a suite of efficient SMPC
protocols that utilize segmented polynomials and Goldschmidt's method to handle
other complex nonlinear functions within PPI, such as GeLU, LayerNorm, and
Softmax. Our extensive experiments reveal that SecFormer outperforms MPCFormer
in performance, showing improvements of $5.6\%$ and $24.2\%$ for
BERT$_{\text{BASE}}$ and BERT$_{\text{LARGE}}$, respectively. In terms of
efficiency, SecFormer is 3.4 and 3.2 times faster than Puma, demonstrating its
effectiveness and speed.</p>
  </details>
</div>



<h2>2023-12</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.00583v1">Improving the Privacy and Practicality of Objective Perturbation for
  Differentially Private Linear Learners</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-31T20:32:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rachel Redberg, Antti Koskela, Yu-Xiang Wang</p>
    <p><b>Summary:</b> In the arena of privacy-preserving machine learning, differentially private
stochastic gradient descent (DP-SGD) has outstripped the objective perturbation
mechanism in popularity and interest. Though unrivaled in versatility, DP-SGD
requires a non-trivial privacy overhead (for privately tuning the model's
hyperparameters) and a computational complexity which might be extravagant for
simple models such as linear and logistic regression. This paper revamps the
objective perturbation mechanism with tighter privacy analyses and new
computational tools that boost it to perform competitively with DP-SGD on
unconstrained convex generalized linear problems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.00879v1">SoK: Demystifying Privacy Enhancing Technologies Through the Lens of
  Software Developers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2023-12-30T12:24:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maisha Boteju, Thilina Ranbaduge, Dinusha Vatsalan, Nalin Asanka Gamagedara Arachchilage</p>
    <p><b>Summary:</b> In the absence of data protection measures, software applications lead to
privacy breaches, posing threats to end-users and software organisations.
Privacy Enhancing Technologies (PETs) are technical measures that protect
personal data, thus minimising such privacy breaches. However, for software
applications to deliver data protection using PETs, software developers should
actively and correctly incorporate PETs into the software they develop.
Therefore, to uncover ways to encourage and support developers to embed PETs
into software, this Systematic Literature Review (SLR) analyses 39 empirical
studies on developers' privacy practices. It reports the usage of six PETs in
software application scenarios. Then, it discusses challenges developers face
when integrating PETs into software, ranging from intrinsic challenges, such as
the unawareness of PETs, to extrinsic challenges, such as the increased
development cost. Next, the SLR presents the existing solutions to address
these challenges, along with the limitations of the solutions. Further, it
outlines future research avenues to better understand PETs from a developer
perspective and minimise the challenges developers face when incorporating PETs
into software.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.00870v1">Teach Large Language Models to Forget Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> 
  <p><b>Published on:</b> 2023-12-30T01:26:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ran Yan, Yujun Li, Wenqian Li, Peihua Mai, Yan Pang, Yinchuan Li</p>
    <p><b>Summary:</b> Large Language Models (LLMs) have proven powerful, but the risk of privacy
leakage remains a significant concern. Traditional privacy-preserving methods,
such as Differential Privacy and Homomorphic Encryption, are inadequate for
black-box API-only settings, demanding either model transparency or heavy
computational resources. We propose Prompt2Forget (P2F), the first framework
designed to tackle the LLM local privacy challenge by teaching LLM to forget.
The method involves decomposing full questions into smaller segments,
generating fabricated answers, and obfuscating the model's memory of the
original input. A benchmark dataset was crafted with questions containing
privacy-sensitive information from diverse fields. P2F achieves zero-shot
generalization, allowing adaptability across a wide range of use cases without
manual adjustments. Experimental results indicate P2F's robust capability to
obfuscate LLM's memory, attaining a forgetfulness score of around 90\% without
any utility loss. This represents an enhancement of up to 63\% when contrasted
with the naive direct instruction technique, highlighting P2F's efficacy in
mitigating memory retention of sensitive information within LLMs. Our findings
establish the first benchmark in the novel field of the LLM forgetting task,
representing a meaningful advancement in privacy preservation in the emerging
LLM domain.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.00058v1">Exploring the language of the sharing economy: Building trust and
  reducing privacy concern on Airbnb in German and English</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2023-12-29T19:28:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alex Zarifis, Richard Ingham, Julia Kroenung</p>
    <p><b>Summary:</b> The text in the profile of those offering their properties in England in
English and in Germany in German, are compared to explore whether trust is
built, and privacy concerns are reduced in the same way. Six methods of
building trust are used by the landlords: (1) the level of formality, (2)
distance and proximity, (3) emotiveness and humor, (4) being assertive and
passive aggressive, (5) conformity to the platform language style and
terminology and (6) setting boundaries. Privacy concerns are not usually
reduced directly as this is left to the platform. The findings indicate that
language has a limited influence and the platform norms and habits are the
biggest influence.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.17708v1">The six ways to build trust and reduce privacy concern in a Central Bank
  Digital Currency (CBDC)</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2023-12-29T17:52:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alex Zarifis, Xusen Cheng</p>
    <p><b>Summary:</b> Central Bank Digital Currencies (CBDCs) have been implemented by only a
handful of countries, but they are being explored by many more. CBDCs are
digital currencies issued and backed by a central bank. Consumer trust can
encourage or discourage the adoption of this currency, which is also a payment
system and a technology. This research attempts to understand consumer trust in
CBDCs so that the development and adoption stages are more effective and
satisfying for all the stakeholders.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.17667v1">AIJack: Security and Privacy Risk Simulator for Machine Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-29T16:10:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hideaki Takahashi</p>
    <p><b>Summary:</b> This paper introduces AIJack, an open-source library designed to assess
security and privacy risks associated with the training and deployment of
machine learning models. Amid the growing interest in big data and AI,
advancements in machine learning research and business are accelerating.
However, recent studies reveal potential threats, such as the theft of training
data and the manipulation of models by malicious attackers. Therefore, a
comprehensive understanding of machine learning's security and privacy
vulnerabilities is crucial for the safe integration of machine learning into
real-world products. AIJack aims to address this need by providing a library
with various attack and defense methods through a unified API. The library is
publicly available on GitHub (https://github.com/Koukyosyumei/AIJack).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.16954v1">Blockchain-based Privacy-Preserving Public Key Searchable Encryption
  with Strong Traceability</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-28T10:58:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yue Han, Jinguang Han, Weizhi Meng, Jianchang Lai, Ge Wu</p>
    <p><b>Summary:</b> Public key searchable encryption (PKSE) scheme allows data users to search
over encrypted data. To identify illegal users, many traceable PKSE schemes
have been proposed. However, existing schemes cannot trace the keywords which
illegal users searched and protect users' privacy simultaneously. In some
practical applications, tracing both illegal users' identities and the keywords
which they searched is quite important to against the abuse of data. It is a
challenge to bind users' identities and keywords while protecting their
privacy. Moreover, existing traceable PKSE schemes do not consider the
unforgeability and immutability of trapdoor query records, which can lead to
the occurrence of frame-up and denying. In this paper, to solve these problems,
we propose a blockchain-based privacy-preserving PKSE with strong traceability
(BP3KSEST) scheme. Our scheme provides the following features: (1) authorized
users can authenticate to trapdoor generation center and obtain trapdoors
without releasing their identities and keywords; (2) when data users misbehave
in the system, the trusted third party (TTP) can trace both their identities
and the keywords which they searched; (3) trapdoor query records are
unforgeable; (4) trapdoor query records are immutable because records are
stored in blockchain. Notably, this scheme is suitable to the scenarios where
privacy must be considered, e.g., electronic health record (EHR). We formalize
both the definition and security model of our BP3KSEST scheme, and present a
concrete construction. Furthermore, the security of the proposed scheme is
formally proven. Finally, the implementation and evaluation are conducted to
analyze its efficiency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.16554v1">A Theoretical Analysis of Efficiency Constrained Utility-Privacy
  Bi-Objective Optimization in Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2023-12-27T12:37:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hanlin Gu, Xinyuan Zhao, Yuxing Han, Yan Kang, Lixin Fan, Qiang Yang</p>
    <p><b>Summary:</b> Federated learning (FL) enables multiple clients to collaboratively learn a
shared model without sharing their individual data. Concerns about utility,
privacy, and training efficiency in FL have garnered significant research
attention. Differential privacy has emerged as a prevalent technique in FL,
safeguarding the privacy of individual user data while impacting utility and
training efficiency. Within Differential Privacy Federated Learning (DPFL),
previous studies have primarily focused on the utility-privacy trade-off,
neglecting training efficiency, which is crucial for timely completion.
Moreover, differential privacy achieves privacy by introducing controlled
randomness (noise) on selected clients in each communication round. Previous
work has mainly examined the impact of noise level ($\sigma$) and communication
rounds ($T$) on the privacy-utility dynamic, overlooking other influential
factors like the sample ratio ($q$, the proportion of selected clients). This
paper systematically formulates an efficiency-constrained utility-privacy
bi-objective optimization problem in DPFL, focusing on $\sigma$, $T$, and $q$.
We provide a comprehensive theoretical analysis, yielding analytical solutions
for the Pareto front. Extensive empirical experiments verify the validity and
efficacy of our analysis, offering valuable guidance for low-cost parameter
design in DPFL.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.15608v1">Federated learning-outcome prediction with multi-layer privacy
  protection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">  
  <p><b>Published on:</b> 2023-12-25T04:29:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yupei Zhang, Yuxin Li, Yifei Wang, Shuangshuang Wei, Yunan Xu, Xuequn Shang</p>
    <p><b>Summary:</b> Learning-outcome prediction (LOP) is a long-standing and critical problem in
educational routes. Many studies have contributed to developing effective
models while often suffering from data shortage and low generalization to
various institutions due to the privacy-protection issue. To this end, this
study proposes a distributed grade prediction model, dubbed FecMap, by
exploiting the federated learning (FL) framework that preserves the private
data of local clients and communicates with others through a global generalized
model. FecMap considers local subspace learning (LSL), which explicitly learns
the local features against the global features, and multi-layer privacy
protection (MPP), which hierarchically protects the private features, including
model-shareable features and not-allowably shared features, to achieve
client-specific classifiers of high performance on LOP per institution. FecMap
is then achieved in an iteration manner with all datasets distributed on
clients by training a local neural network composed of a global part, a local
part, and a classification head in clients and averaging the global parts from
clients on the server. To evaluate the FecMap model, we collected three
higher-educational datasets of student academic records from engineering
majors. Experiment results manifest that FecMap benefits from the proposed LSL
and MPP and achieves steady performance on the task of LOP, compared with the
state-of-the-art models. This study makes a fresh attempt at the use of
federated learning in the learning-analytical task, potentially paving the way
to facilitating personalized education with privacy protection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.15591v1">Privacy-Preserving Neural Graph Databases</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2023-12-25T02:32:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qi Hu, Haoran Li, Jiaxin Bai, Yangqiu Song</p>
    <p><b>Summary:</b> In the era of big data and rapidly evolving information systems, efficient
and accurate data retrieval has become increasingly crucial. Neural graph
databases (NGDBs) have emerged as a powerful paradigm that combines the
strengths of graph databases (graph DBs) and neural networks to enable
efficient storage, retrieval, and analysis of graph-structured data. The usage
of neural embedding storage and complex neural logical query answering provides
NGDBs with generalization ability. When the graph is incomplete, by extracting
latent patterns and representations, neural graph databases can fill gaps in
the graph structure, revealing hidden relationships and enabling accurate query
answering. Nevertheless, this capability comes with inherent trade-offs, as it
introduces additional privacy risks to the database. Malicious attackers can
infer more sensitive information in the database using well-designed
combinatorial queries, such as by comparing the answer sets of where Turing
Award winners born before 1950 and after 1940 lived, the living places of
Turing Award winner Hinton are probably exposed, although the living places may
have been deleted in the training due to the privacy concerns. In this work,
inspired by the privacy protection in graph embeddings, we propose a
privacy-preserving neural graph database (P-NGDB) to alleviate the risks of
privacy leakage in NGDBs. We introduce adversarial training techniques in the
training stage to force the NGDBs to generate indistinguishable answers when
queried with private information, enhancing the difficulty of inferring
sensitive information through combinations of multiple innocuous queries.
Extensive experiment results on three datasets show that P-NGDB can effectively
protect private information in the graph database while delivering high-quality
public answers responses to queries.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.15420v1">FedDMF: Privacy-Preserving User Attribute Prediction using Deep Matrix
  Factorization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-24T06:49:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ming Cheung</p>
    <p><b>Summary:</b> User attribute prediction is a crucial task in various industries. However,
sharing user data across different organizations faces challenges due to
privacy concerns and legal requirements regarding personally identifiable
information. Regulations such as the General Data Protection Regulation (GDPR)
in the European Union and the Personal Information Protection Law of the
People's Republic of China impose restrictions on data sharing. To address the
need for utilizing features from multiple clients while adhering to legal
requirements, federated learning algorithms have been proposed. These
algorithms aim to predict user attributes without directly sharing the data.
However, existing approaches typically rely on matching users across companies,
which can result in dishonest partners discovering user lists or the inability
to utilize all available features. In this paper, we propose a novel algorithm
for predicting user attributes without requiring user matching. Our approach
involves training deep matrix factorization models on different clients and
sharing only the item vectors. This allows us to predict user attributes
without sharing the user vectors themselves. The algorithm is evaluated using
the publicly available MovieLens dataset and demonstrate that it achieves
similar performance to the FedAvg algorithm, reaching 96% of a single model's
accuracy. The proposed algorithm is particularly well-suited for improving
customer targeting and enhancing the overall customer experience. This paper
presents a valuable contribution to the field of user attribute prediction by
offering a novel algorithm that addresses some of the most pressing privacy
concerns in this area.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.15383v1">SoK: Technical Implementation and Human Impact of Internet Privacy
  Regulations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2023-12-24T01:48:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Eleanor Birrell, Jay Rodolitz, Angel Ding, Jenna Lee, Emily McReynolds, Jevan Hutson, Ada Lerner</p>
    <p><b>Summary:</b> Growing recognition of the potential for exploitation of personal data and of
the shortcomings of prior privacy regimes has led to the passage of a multitude
of new online privacy regulations. Some of these laws -- notably the European
Union's General Data Protection Regulation (GDPR) and the California Consumer
Privacy Act (CCPA) -- have been the focus of large bodies of research by the
computer science community, while others have received less attention. In this
work, we analyze a set of Internet privacy and data protection regulations
drawn from around the world -- both those that have frequently been studied by
computer scientists and those that have not -- and develop a taxonomy of rights
granted and obligations imposed by these laws. We then leverage this taxonomy
to systematize 270 technical research papers published in computer science
venues that investigate the impact of these laws and explore how technical
solutions can complement legal protections. Finally, we analyze the results in
this space through an interdisciplinary lens and make recommendations for
future work at the intersection of computer science and legal privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.15375v1">An Empirical Study of Efficiency and Privacy of Federated Learning
  Algorithms</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2023-12-24T00:13:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sofia Zahri, Hajar Bennouri, Ahmed M. Abdelmoniem</p>
    <p><b>Summary:</b> In today's world, the rapid expansion of IoT networks and the proliferation
of smart devices in our daily lives, have resulted in the generation of
substantial amounts of heterogeneous data. These data forms a stream which
requires special handling. To handle this data effectively, advanced data
processing technologies are necessary to guarantee the preservation of both
privacy and efficiency. Federated learning emerged as a distributed learning
method that trains models locally and aggregates them on a server to preserve
data privacy. This paper showcases two illustrative scenarios that highlight
the potential of federated learning (FL) as a key to delivering efficient and
privacy-preserving machine learning within IoT networks. We first give the
mathematical foundations for key aggregation algorithms in federated learning,
i.e., FedAvg and FedProx. Then, we conduct simulations, using Flower Framework,
to show the \textit{efficiency} of these algorithms by training deep neural
networks on common datasets and show a comparison between the accuracy and loss
metrics of FedAvg and FedProx. Then, we present the results highlighting the
trade-off between maintaining privacy versus accuracy via simulations -
involving the implementation of the differential privacy (DP) method - in
Pytorch and Opacus ML frameworks on common FL datasets and data distributions
for both FedAvg and FedProx strategies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.15000v1">The Impact of Cloaking Digital Footprints on User Privacy and
  Personalization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2023-12-22T16:32:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sofie Goethals, Sandra Matz, Foster Provost, Yanou Ramon, David Martens</p>
    <p><b>Summary:</b> Our online lives generate a wealth of behavioral records -'digital
footprints'- which are stored and leveraged by technology platforms. This data
can be used to create value for users by personalizing services. At the same
time, however, it also poses a threat to people's privacy by offering a highly
intimate window into their private traits (e.g., their personality, political
ideology, sexual orientation). Prior work has proposed a potential remedy: The
cloaking of users' footprints. That is, platforms could allow users to hide
portions of their digital footprints from predictive algorithms to avoid
undesired inferences. While such an approach has been shown to offer privacy
protection in the moment, there are two open questions. First, it remains
unclear how well cloaking performs over time. As people constantly leave new
digital footprints, the algorithm might regain the ability to predict
previously cloaked traits. Second, cloaking digital footprints to avoid one
undesirable inference may degrade the performance of models for other,
desirable inferences (e.g., those driving desired personalized content). In the
light of these research gaps, our contributions are twofold: 1) We propose a
novel cloaking strategy that conceals 'metafeatures' (automatically generated
higher-level categories) and compares its effectiveness against existing
cloaking approaches, and 2) we test the spill-over effects of cloaking one
trait on the accuracy of inferences on other traits. A key finding is that the
effectiveness of cloaking degrades over times, but the rate at which it
degrades is significantly smaller when cloaking metafeatures rather than
individual footprints. In addition, our findings reveal the expected trade-off
between privacy and personalization: Cloaking an undesired trait also partially
conceals other desirable traits.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.14633v1">Evaluating the Security and Privacy Risk Postures of Virtual Assistants</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2023-12-22T12:10:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Borna Kalhor, Sanchari Das</p>
    <p><b>Summary:</b> Virtual assistants (VAs) have seen increased use in recent years due to their
ease of use for daily tasks. Despite their growing prevalence, their security
and privacy implications are still not well understood. To address this gap, we
conducted a study to evaluate the security and privacy postures of eight widely
used voice assistants: Alexa, Braina, Cortana, Google Assistant, Kalliope,
Mycroft, Hound, and Extreme. We used three vulnerability testing tools,
AndroBugs, RiskInDroid, and MobSF, to assess the security and privacy of these
VAs. Our analysis focused on five areas: code, access control, tracking, binary
analysis, and sensitive data confidentiality. The results revealed that these
VAs are vulnerable to a range of security threats, including not validating SSL
certificates, executing raw SQL queries, and using a weak mode of the AES
algorithm. These vulnerabilities could allow malicious actors to gain
unauthorized access to users' personal information. This study is a first step
toward understanding the risks associated with these technologies and provides
a foundation for future research to develop more secure and privacy-respecting
VAs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.14521v1">Tuning Quantum Computing Privacy through Quantum Error Correction</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2023-12-22T08:35:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hui Zhong, Keyi Ju, Manojna Sistla, Xinyue Zhang, Xiaoqi Qin, Xin Fu, Miao Pan</p>
    <p><b>Summary:</b> Quantum computing is a promising paradigm for efficiently solving large and
high-complexity problems. To protect quantum computing privacy, pioneering
research efforts proposed to redefine differential privacy (DP) in quantum
computing, i.e., quantum differential privacy (QDP), and harvest inherent
noises generated by quantum computing to implement QDP. However, such an
implementation approach is limited by the amount of inherent noises, which
makes the privacy budget of the QDP mechanism fixed and uncontrollable. To
address this issue, in this paper, we propose to leverage quantum error
correction (QEC) techniques to reduce quantum computing errors, while tuning
the privacy protection levels in QDP. In short, we gradually decrease the
quantum noise error rate by deciding whether to apply QEC operations on the
gate in a multiple single qubit gates circuit. We have derived a new
calculation formula for the general error rate and corresponding privacy
budgets after QEC operation. Then, we expand to achieve further noise reduction
using multi-level concatenated QEC operation. Through extensive numerical
simulations, we demonstrate that QEC is a feasible way to regulate the degree
of privacy protection in quantum computing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.16191v1">SoK: Taming the Triangle -- On the Interplays between Fairness,
  Interpretability and Privacy in Machine Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2023-12-22T08:11:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Julien Ferry, Ulrich Aïvodji, Sébastien Gambs, Marie-José Huguet, Mohamed Siala</p>
    <p><b>Summary:</b> Machine learning techniques are increasingly used for high-stakes
decision-making, such as college admissions, loan attribution or recidivism
prediction. Thus, it is crucial to ensure that the models learnt can be audited
or understood by human users, do not create or reproduce discrimination or
bias, and do not leak sensitive information regarding their training data.
Indeed, interpretability, fairness and privacy are key requirements for the
development of responsible machine learning, and all three have been studied
extensively during the last decade. However, they were mainly considered in
isolation, while in practice they interplay with each other, either positively
or negatively. In this Systematization of Knowledge (SoK) paper, we survey the
literature on the interactions between these three desiderata. More precisely,
for each pairwise interaction, we summarize the identified synergies and
tensions. These findings highlight several fundamental theoretical and
empirical conflicts, while also demonstrating that jointly considering these
different requirements is challenging when one aims at preserving a high level
of utility. To solve this issue, we also discuss possible conciliation
mechanisms, showing that a careful design can enable to successfully handle
these different concerns in practice.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.14407v1">AdvCloak: Customized Adversarial Cloak for Privacy Protection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2023-12-22T03:18:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xuannan Liu, Yaoyao Zhong, Xing Cui, Yuhang Zhang, Peipei Li, Weihong Deng</p>
    <p><b>Summary:</b> With extensive face images being shared on social media, there has been a
notable escalation in privacy concerns. In this paper, we propose AdvCloak, an
innovative framework for privacy protection using generative models. AdvCloak
is designed to automatically customize class-wise adversarial masks that can
maintain superior image-level naturalness while providing enhanced
feature-level generalization ability. Specifically, AdvCloak sequentially
optimizes the generative adversarial networks by employing a two-stage training
strategy. This strategy initially focuses on adapting the masks to the unique
individual faces via image-specific training and then enhances their
feature-level generalization ability to diverse facial variations of
individuals via person-specific training. To fully utilize the limited training
data, we combine AdvCloak with several general geometric modeling methods, to
better describe the feature subspace of source identities. Extensive
quantitative and qualitative evaluations on both common and celebrity datasets
demonstrate that AdvCloak outperforms existing state-of-the-art methods in
terms of efficiency and effectiveness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.14388v1">A Generalized Shuffle Framework for Privacy Amplification: Strengthening
  Privacy Guarantees and Enhancing Utility</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2023-12-22T02:31:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> E Chen, Yang Cao, Yifei Ge</p>
    <p><b>Summary:</b> The shuffle model of local differential privacy is an advanced method of
privacy amplification designed to enhance privacy protection with high utility.
It achieves this by randomly shuffling sensitive data, making linking
individual data points to specific individuals more challenging. However, most
existing studies have focused on the shuffle model based on
$(\epsilon_0,0)$-Locally Differentially Private (LDP) randomizers, with limited
consideration for complex scenarios such as $(\epsilon_0,\delta_0)$-LDP or
personalized LDP (PLDP). This hinders a comprehensive understanding of the
shuffle model's potential and limits its application in various settings. To
bridge this research gap, we propose a generalized shuffle framework that can
be applied to any $(\epsilon_i,\delta_i)$-PLDP setting with personalized
privacy parameters. This generalization allows for a broader exploration of the
privacy-utility trade-off and facilitates the design of privacy-preserving
analyses in diverse contexts. We prove that shuffled
$(\epsilon_i,\delta_i)$-PLDP process approximately preserves $\mu$-Gaussian
Differential Privacy with \mu = \sqrt{\frac{2}{\sum_{i=1}^{n}
\frac{1-\delta_i}{1+e^{\epsilon_i}}-\max_{i}{\frac{1-\delta_{i}}{1+e^{\epsilon_{i}}}}}}.
$
  This approach allows us to avoid the limitations and potential inaccuracies
associated with inequality estimations. To strengthen the privacy guarantee, we
improve the lower bound by utilizing hypothesis testing} instead of relying on
rough estimations like the Chernoff bound or Hoeffding's inequality.
Furthermore, extensive comparative evaluations clearly show that our approach
outperforms existing methods in achieving strong central privacy guarantees
while preserving the utility of the global model. We have also carefully
designed corresponding algorithms for average function, frequency estimation,
and stochastic gradient descent.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.13985v1">Rényi Pufferfish Privacy: General Additive Noise Mechanisms and
  Privacy Amplification by Iteration</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2023-12-21T16:18:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Clément Pierquin, Aurélien Bellet, Marc Tommasi, Matthieu Boussard</p>
    <p><b>Summary:</b> Pufferfish privacy is a flexible generalization of differential privacy that
allows to model arbitrary secrets and adversary's prior knowledge about the
data. Unfortunately, designing general and tractable Pufferfish mechanisms that
do not compromise utility is challenging. Furthermore, this framework does not
provide the composition guarantees needed for a direct use in iterative machine
learning algorithms. To mitigate these issues, we introduce a R\'enyi
divergence-based variant of Pufferfish and show that it allows us to extend the
applicability of the Pufferfish framework. We first generalize the Wasserstein
mechanism to cover a wide range of noise distributions and introduce several
ways to improve its utility. We also derive stronger guarantees against
out-of-distribution adversaries. Finally, as an alternative to composition, we
prove privacy amplification results for contractive noisy iterations and
showcase the first use of Pufferfish in private convex optimization. A common
ingredient underlying our results is the use and extension of shift reduction
lemmas.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.13813v1">How Does Connecting Online Activities to Advertising Inferences Impact
  Privacy Perceptions?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2023-12-21T13:05:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Florian M. Farke, David G. Balash, Maximilian Golla, Adam J. Aviv</p>
    <p><b>Summary:</b> Data dashboards are designed to help users manage data collected about them.
However, prior work showed that exposure to some dashboards, notably Google's
My Activity dashboard, results in significant decreases in perceived concern
and increases in perceived benefit from data collection, contrary to
expectations. We theorize that this result is due to the fact that data
dashboards currently do not sufficiently "connect the dots" of the data food
chain, that is, by connecting data collection with the use of that data. To
evaluate this, we designed a study where participants assigned advertising
interest labels to their own real activities, effectively acting as a
behavioral advertising engine to "connect the dots." When comparing pre- and
post-labeling task responses, we find no significant difference in concern with
Google's data collection practices, which indicates that participants' priors
are maintained after more exposure to the data food chain (differing from prior
work), suggesting that data dashboards that offer deeper perspectives of how
data collection is used have potential. However, these gains are offset when
participants are exposed to their true interest labels inferred by Google.
Concern for data collection dropped significantly as participants viewed
Google's labeling as generic compared to their own more specific labeling. This
presents a possible new paradox that must be overcome when designing data
dashboards, the generic paradox, which occurs when users misalign individual,
generic inferences from collected data as benign compared to the totality and
specificity of many generic inferences made about them.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.13712v1">Conciliating Privacy and Utility in Data Releases via Individual
  Differential Privacy and Microaggregation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-21T10:23:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jordi Soria-Comas, David Sánchez, Josep Domingo-Ferrer, Sergio Martínez, Luis Del Vasto-Terrientes</p>
    <p><b>Summary:</b> $\epsilon$-Differential privacy (DP) is a well-known privacy model that
offers strong privacy guarantees. However, when applied to data releases, DP
significantly deteriorates the analytical utility of the protected outcomes. To
keep data utility at reasonable levels, practical applications of DP to data
releases have used weak privacy parameters (large $\epsilon$), which dilute the
privacy guarantees of DP. In this work, we tackle this issue by using an
alternative formulation of the DP privacy guarantees, named
$\epsilon$-individual differential privacy (iDP), which causes less data
distortion while providing the same protection as DP to subjects. We enforce
iDP in data releases by relying on attribute masking plus a pre-processing step
based on data microaggregation. The goal of this step is to reduce the
sensitivity to record changes, which determines the amount of noise required to
enforce iDP (and DP). Specifically, we propose data microaggregation strategies
designed for iDP whose sensitivities are significantly lower than those used in
DP. As a result, we obtain iDP-protected data with significantly better utility
than with DP. We report on experiments that show how our approach can provide
strong privacy (small $\epsilon$) while yielding protected data that do not
significantly degrade the accuracy of secondary data analysis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.13389v1">Enhancing Trade-offs in Privacy, Utility, and Computational Efficiency
  through MUltistage Sampling Technique (MUST)</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2023-12-20T19:38:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xingyuan Zhao, Fang Liu</p>
    <p><b>Summary:</b> Applying a randomized algorithm to a subset of a dataset rather than the
entire dataset is a common approach to amplify its privacy guarantees in the
released information. We propose a class of subsampling methods named
MUltistage Sampling Technique (MUST) for privacy amplification (PA) in the
context of differential privacy (DP). We conduct comprehensive analyses of the
PA effects and utility for several 2-stage MUST procedures, namely, MUST.WO,
MUST.OW, and MUST.WW that respectively represent sampling with (W), without
(O), with (W) replacement from the original dataset in stage I and then
sampling without (O), with (W), with (W) replacement in stage II from the
subset drawn in stage I. We also provide the privacy composition analysis over
repeated applications of MUST via the Fourier accountant algorithm. Our
theoretical and empirical results suggest that MUST.OW and MUST.WW have
stronger PA in $\epsilon$ than the common one-stage sampling procedures
including Poisson sampling, sampling without replacement, and sampling with
replacement, while the results on $\delta$ vary case by case. We also prove
that MUST.WO is equivalent to sampling with replacement in PA. Furthermore, the
final subset generated by a MUST procedure is a multiset that may contain
multiple copies of the same data points due to sampling with replacement
involved, which enhances the computational efficiency of algorithms that
require complex function calculations on distinct data points (e.g., gradient
descent). Our utility experiments show that MUST delivers similar or improved
utility and stability in the privacy-preserving outputs compared to one-stage
subsampling methods at similar privacy loss. MUST can be seamlessly integrated
into stochastic optimization algorithms or procedures that involve parallel or
simultaneous subsampling (e.g., bagging and subsampling bootstrap) when DP
guarantees are necessary.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.13334v1">Transparency and Privacy: The Role of Explainable AI and Federated
  Learning in Financial Fraud Detection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-20T18:26:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tomisin Awosika, Raj Mani Shukla, Bernardi Pranggono</p>
    <p><b>Summary:</b> Fraudulent transactions and how to detect them remain a significant problem
for financial institutions around the world. The need for advanced fraud
detection systems to safeguard assets and maintain customer trust is paramount
for financial institutions, but some factors make the development of effective
and efficient fraud detection systems a challenge. One of such factors is the
fact that fraudulent transactions are rare and that many transaction datasets
are imbalanced; that is, there are fewer significant samples of fraudulent
transactions than legitimate ones. This data imbalance can affect the
performance or reliability of the fraud detection model. Moreover, due to the
data privacy laws that all financial institutions are subject to follow,
sharing customer data to facilitate a higher-performing centralized model is
impossible. Furthermore, the fraud detection technique should be transparent so
that it does not affect the user experience. Hence, this research introduces a
novel approach using Federated Learning (FL) and Explainable AI (XAI) to
address these challenges. FL enables financial institutions to collaboratively
train a model to detect fraudulent transactions without directly sharing
customer data, thereby preserving data privacy and confidentiality. Meanwhile,
the integration of XAI ensures that the predictions made by the model can be
understood and interpreted by human experts, adding a layer of transparency and
trust to the system. Experimental results, based on realistic transaction
datasets, reveal that the FL-based fraud detection system consistently
demonstrates high performance metrics. This study grounds FL's potential as an
effective and privacy-preserving tool in the fight against fraud.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.13312v1">Multi-label Learning from Privacy-Label</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-20T09:09:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhongnian Li, Haotian Ren, Tongfeng Sun, Zhichen Li</p>
    <p><b>Summary:</b> Multi-abel Learning (MLL) often involves the assignment of multiple relevant
labels to each instance, which can lead to the leakage of sensitive information
(such as smoking, diseases, etc.) about the instances. However, existing MLL
suffer from failures in protection for sensitive information. In this paper, we
propose a novel setting named Multi-Label Learning from Privacy-Label (MLLPL),
which Concealing Labels via Privacy-Label Unit (CLPLU). Specifically, during
the labeling phase, each privacy-label is randomly combined with a non-privacy
label to form a Privacy-Label Unit (PLU). If any label within a PLU is
positive, the unit is labeled as positive; otherwise, it is labeled negative,
as shown in Figure 1. PLU ensures that only non-privacy labels are appear in
the label set, while the privacy-labels remain concealed. Moreover, we further
propose a Privacy-Label Unit Loss (PLUL) to learn the optimal classifier by
minimizing the empirical risk of PLU. Experimental results on multiple
benchmark datasets demonstrate the effectiveness and superiority of the
proposed method.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.12216v1">Sharing is CAIRing: Characterizing Principles and Assessing Properties
  of Universal Privacy Evaluation for Synthetic Tabular Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2023-12-19T15:05:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tobias Hyrup, Anton Danholt Lautrup, Arthur Zimek, Peter Schneider-Kamp</p>
    <p><b>Summary:</b> Data sharing is a necessity for innovative progress in many domains,
especially in healthcare. However, the ability to share data is hindered by
regulations protecting the privacy of natural persons. Synthetic tabular data
provide a promising solution to address data sharing difficulties but does not
inherently guarantee privacy. Still, there is a lack of agreement on
appropriate methods for assessing the privacy-preserving capabilities of
synthetic data, making it difficult to compare results across studies. To the
best of our knowledge, this is the first work to identify properties that
constitute good universal privacy evaluation metrics for synthetic tabular
data. The goal of such metrics is to enable comparability across studies and to
allow non-technical stakeholders to understand how privacy is protected. We
identify four principles for the assessment of metrics: Comparability,
Applicability, Interpretability, and Representativeness (CAIR). To quantify and
rank the degree to which evaluation metrics conform to the CAIR principles, we
design a rubric using a scale of 1-4. Each of the four properties is scored on
four parameters, yielding 16 total dimensions. We study the applicability and
usefulness of the CAIR principles and rubric by assessing a selection of
metrics popular in other studies. The results provide granular insights into
the strengths and weaknesses of existing metrics that not only rank the metrics
but highlight areas of potential improvements. We expect that the CAIR
principles will foster agreement among researchers and organizations on which
universal privacy evaluation metrics are appropriate for synthetic tabular
data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.12183v2">Poincaré Differential Privacy for Hierarchy-Aware Graph Embedding</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-19T14:15:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuecen Wei, Haonan Yuan, Xingcheng Fu, Qingyun Sun, Hao Peng, Xianxian Li, Chunming Hu</p>
    <p><b>Summary:</b> Hierarchy is an important and commonly observed topological property in
real-world graphs that indicate the relationships between supervisors and
subordinates or the organizational behavior of human groups. As hierarchy is
introduced as a new inductive bias into the Graph Neural Networks (GNNs) in
various tasks, it implies latent topological relations for attackers to improve
their inference attack performance, leading to serious privacy leakage issues.
In addition, existing privacy-preserving frameworks suffer from reduced
protection ability in hierarchical propagation due to the deficiency of
adaptive upper-bound estimation of the hierarchical perturbation boundary. It
is of great urgency to effectively leverage the hierarchical property of data
while satisfying privacy guarantees. To solve the problem, we propose the
Poincar\'e Differential Privacy framework, named PoinDP, to protect the
hierarchy-aware graph embedding based on hyperbolic geometry. Specifically,
PoinDP first learns the hierarchy weights for each entity based on the
Poincar\'e model in hyperbolic space. Then, the Personalized Hierarchy-aware
Sensitivity is designed to measure the sensitivity of the hierarchical
structure and adaptively allocate the privacy protection strength. Besides, the
Hyperbolic Gaussian Mechanism (HGM) is proposed to extend the Gaussian
mechanism in Euclidean space to hyperbolic space to realize random
perturbations that satisfy differential privacy under the hyperbolic space
metric. Extensive experiment results on five real-world datasets demonstrate
the proposed PoinDP's advantages of effective privacy protection while
maintaining good performance on the node classification task.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.11845v1">A Summary of Privacy-Preserving Data Publishing in the Local Setting</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-19T04:23:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenjun Lin, Jiahao Qian, Wenwen Liu, Lang Wu</p>
    <p><b>Summary:</b> The exponential growth of collected, processed, and shared data has given
rise to concerns about individuals' privacy. Consequently, various laws and
regulations have been established to oversee how organizations handle and
safeguard data. One such method is Statistical Disclosure Control, which aims
to minimize the risk of exposing confidential information by de-identifying it.
This de-identification is achieved through specific privacy-preserving
techniques. However, a trade-off exists: de-identified data can often lead to a
loss of information, which might impact the accuracy of data analysis and the
predictive capability of models. The overarching goal remains to safeguard
individual privacy while preserving the data's interpretability, meaning its
overall usefulness. Despite advances in Statistical Disclosure Control, the
field continues to evolve, with no definitive solution that strikes an optimal
balance between privacy and utility. This survey delves into the intricate
processes of de-identification. We outline the current privacy-preserving
techniques employed in microdata de-identification, delve into privacy measures
tailored for various disclosure scenarios, and assess metrics for information
loss and predictive performance. Herein, we tackle the primary challenges posed
by privacy constraints, overview predominant strategies to mitigate these
challenges, categorize privacy-preserving techniques, offer a theoretical
assessment of current comparative research, and highlight numerous unresolved
issues in the domain.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.11712v1">A Simple and Practical Method for Reducing the Disparate Impact of
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2023-12-18T21:19:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lucas Rosenblatt, Julia Stoyanovich, Christopher Musco</p>
    <p><b>Summary:</b> Differentially private (DP) mechanisms have been deployed in a variety of
high-impact social settings (perhaps most notably by the U.S. Census). Since
all DP mechanisms involve adding noise to results of statistical queries, they
are expected to impact our ability to accurately analyze and learn from data,
in effect trading off privacy with utility. Alarmingly, the impact of DP on
utility can vary significantly among different sub-populations. A simple way to
reduce this disparity is with stratification. First compute an independent
private estimate for each group in the data set (which may be the intersection
of several protected classes), then, to compute estimates of global statistics,
appropriately recombine these group estimates. Our main observation is that
naive stratification often yields high-accuracy estimates of population-level
statistics, without the need for additional privacy budget. We support this
observation theoretically and empirically. Our theoretical results center on
the private mean estimation problem, while our empirical results center on
extensive experiments on private data synthesis to demonstrate the
effectiveness of stratification on a variety of private mechanisms. Overall, we
argue that this straightforward approach provides a strong baseline against
which future work on reducing utility disparities of DP mechanisms should be
compared.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.11126v1">Harnessing Inherent Noises for Privacy Preservation in Quantum Machine
  Learning</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2023-12-18T11:52:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Keyi Ju, Xiaoqi Qin, Hui Zhong, Xinyue Zhang, Miao Pan, Baoling Liu</p>
    <p><b>Summary:</b> Quantum computing revolutionizes the way of solving complex problems and
handling vast datasets, which shows great potential to accelerate the machine
learning process. However, data leakage in quantum machine learning (QML) may
present privacy risks. Although differential privacy (DP), which protects
privacy through the injection of artificial noise, is a well-established
approach, its application in the QML domain remains under-explored. In this
paper, we propose to harness inherent quantum noises to protect data privacy in
QML. Especially, considering the Noisy Intermediate-Scale Quantum (NISQ)
devices, we leverage the unavoidable shot noise and incoherent noise in quantum
computing to preserve the privacy of QML models for binary classification. We
mathematically analyze that the gradient of quantum circuit parameters in QML
satisfies a Gaussian distribution, and derive the upper and lower bounds on its
variance, which can potentially provide the DP guarantee. Through simulations,
we show that a target privacy protection level can be achieved by running the
quantum circuit a different number of times.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.11581v1">Protect Your Score: Contact Tracing With Differential Privacy Guarantees</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2023-12-18T11:16:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rob Romijnders, Christos Louizos, Yuki M. Asano, Max Welling</p>
    <p><b>Summary:</b> The pandemic in 2020 and 2021 had enormous economic and societal
consequences, and studies show that contact tracing algorithms can be key in
the early containment of the virus. While large strides have been made towards
more effective contact tracing algorithms, we argue that privacy concerns
currently hold deployment back. The essence of a contact tracing algorithm
constitutes the communication of a risk score. Yet, it is precisely the
communication and release of this score to a user that an adversary can
leverage to gauge the private health status of an individual. We pinpoint a
realistic attack scenario and propose a contact tracing algorithm with
differential privacy guarantees against this attack. The algorithm is tested on
the two most widely used agent-based COVID19 simulators and demonstrates
superior performance in a wide range of settings. Especially for realistic test
scenarios and while releasing each risk score with epsilon=1 differential
privacy, we achieve a two to ten-fold reduction in the infection rate of the
virus. To the best of our knowledge, this presents the first contact tracing
algorithm with differential privacy guarantees when revealing risk scores for
COVID19.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.11575v1">Blind-Touch: Homomorphic Encryption-Based Distributed Neural Network
  Inference for Privacy-Preserving Fingerprint Authentication</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-18T09:05:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hyunmin Choi, Simon Woo, Hyoungshick Kim</p>
    <p><b>Summary:</b> Fingerprint authentication is a popular security mechanism for smartphones
and laptops. However, its adoption in web and cloud environments has been
limited due to privacy concerns over storing and processing biometric data on
servers. This paper introduces Blind-Touch, a novel machine learning-based
fingerprint authentication system leveraging homomorphic encryption to address
these privacy concerns. Homomorphic encryption allows computations on encrypted
data without decrypting. Thus, Blind-Touch can keep fingerprint data encrypted
on the server while performing machine learning operations. Blind-Touch
combines three strategies to efficiently utilize homomorphic encryption in
machine learning: (1) It optimizes the feature vector for a distributed
architecture, processing the first fully connected layer (FC-16) in plaintext
on the client side and the subsequent layer (FC-1) post-encryption on the
server, thereby minimizing encrypted computations; (2) It employs a homomorphic
encryptioncompatible data compression technique capable of handling 8,192
authentication results concurrently; and (3) It utilizes a clustered server
architecture to simultaneously process authentication results, thereby
enhancing scalability with increasing user numbers. Blind-Touch achieves high
accuracy on two benchmark fingerprint datasets, with a 93.6% F1- score for the
PolyU dataset and a 98.2% F1-score for the SOKOTO dataset. Moreover,
Blind-Touch can match a fingerprint among 5,000 in about 0.65 seconds. With its
privacyfocused design, high accuracy, and efficiency, Blind-Touch is a
promising alternative to conventional fingerprint authentication for web and
cloud applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.10951v1">Viral Privacy: Contextual Integrity as a Lens to Understand Content
  Creators' Privacy Perceptions and Needs After Sudden Attention</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2023-12-18T06:04:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joseph S. Schafer, Annie Denton, Chloe Seelhoff, Jordyn Vo, Kate Starbird</p>
    <p><b>Summary:</b> When designing multi-stakeholder privacy systems, it is important to consider
how different groups of social media users have different goals and
requirements for privacy. Additionally, we must acknowledge that it is
important to keep in mind that even a single creator's needs can change as
their online visibility and presence shifts, and that robust multi-stakeholder
privacy systems should account for these shifts. Using the framework of
contextual integrity, we explain a theoretical basis for how to evaluate the
potential changing privacy needs of users as their profiles undergo a sudden
rise in online attention, and ongoing projects to understand these potential
shifts in perspectives.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.11564v1">Privacy-preserving transactive energy systems: Key topics and open
  research challenges</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2023-12-17T21:23:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Daniel Gerbi Duguma, Juliana Zhang, Meysam Aboutalebi, Shiliang Zhang, Catherine Banet, Cato Bjørkli, Chinmayi Baramashetru, Frank Eliassen, Hui Zhang, Jonathan Muringani, Josef Noll, Knut Inge Fostervold, Lars Böcker, Lee Andrew Bygrave, Matin Bagherpour, Maunya Doroudi Moghadam, Olaf Owe, Poushali Sengupta, Roman Vitenberg, Sabita Maharjan, Thiago Garrett, Yushuai Li, Zhengyu Shan</p>
    <p><b>Summary:</b> This manuscript aims to formalize and conclude the discussions initiated
during the PriTEM workshop 22-23 March 2023. We present important ideas and
discussion topics in the context of transactive energy systems. Moreover, the
conclusions from the discussions articulate potential aspects to be explored in
future studies on transactive energy management. Particularly, these
conclusions cover research topics in energy technology and energy informatics,
energy law, data law, energy market and socio-psychology that are relevant to
the seamless integration of renewable energy resources and the transactive
energy systems-in smart microgrids-focusing on distributed frameworks such as
peer-to-peer (P2P) energy trading. We clarify issues, identify barriers, and
suggest possible solutions to open questions in diversified topics, such as
block-chain interoperability, consumer privacy and data sharing, and
participation incentivization. Furthermore, we also elaborate challenges
associated with cross-disciplinary collaboration and coordination for
transactive energy systems, and enumerate the lessons learned from our work so
far.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.10789v1">Federated learning with differential privacy and an untrusted aggregator</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-17T18:26:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kunlong Liu, Trinabh Gupta</p>
    <p><b>Summary:</b> Federated learning for training models over mobile devices is gaining
popularity. Current systems for this task exhibit significant trade-offs
between model accuracy, privacy guarantee, and device efficiency. For instance,
Oort (OSDI 2021) provides excellent accuracy and efficiency but requires a
trusted central server. On the other hand, Orchard (OSDI 2020) provides good
accuracy and the rigorous guarantee of differential privacy over an untrusted
server, but creates huge overhead for the devices. This paper describes Aero, a
new federated learning system that significantly improves this trade-off. Aero
guarantees good accuracy, differential privacy over an untrusted server, and
keeps the device overhead low. The key idea of Aero is to tune system
architecture and design to a specific set of popular, federated learning
algorithms. This tuning requires novel optimizations and techniques, e.g., a
new protocol to securely aggregate updates from devices. An evaluation of Aero
demonstrates that it provides comparable accuracy to plain federated learning
(without differential privacy), and it improves efficiency (CPU and network)
over Orchard by up to $10^5\times$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.10698v1">HE-DKSAP: Privacy-Preserving Stealth Address Protocol via Additively
  Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-17T12:23:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuping Yan, George Shao, Dennis Song, Mason Song, Yaochu Jin</p>
    <p><b>Summary:</b> Blockchain transactions have gained widespread adoption across various
industries, largely attributable to their unparalleled transparency and robust
security features. Nevertheless, this technique introduces various privacy
concerns, including pseudonymity, Sybil attacks, and potential susceptibilities
to quantum computing, to name a few. In response to these challenges,
innovative privacy-enhancing solutions like zero-knowledge proofs, homomorphic
encryption, and stealth addresses (SA) have been developed. Among the various
schemes, SA stands out as it prevents the association of a blockchain
transaction's output with the recipient's public address, thereby ensuring
transactional anonymity. However, the basic SA schemes have exhibited
vulnerabilities to key leakage and quantum computing attacks. To address these
shortcomings, we present a pioneering solution - Homomorphic Encryption-based
Dual-Key Stealth Address Protocol (HE-DKSAP), which can be further extended to
Fully HE-DKSAP (FHE-DKSAP). By leveraging the power of homomorphic encryption,
HE-DKSAP introduces a novel approach to safeguarding transaction privacy and
preventing potential quantum computing attacks. This paper delves into the core
principles of HE-DKSAP, highlighting its capacity to enhance privacy,
scalability, and security in programmable blockchains. Through a comprehensive
exploration of its design architecture, security analysis, and practical
implementations, this work establishes a privacy-preserving, practical, and
efficient stealth address protocol via additively homomorphic encryption.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.10645v1">FedMKGC: Privacy-Preserving Federated Multilingual Knowledge Graph
  Completion</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2023-12-17T08:09:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wei Tang, Zhiqian Wu, Yixin Cao, Yong Liao, Pengyuan Zhou</p>
    <p><b>Summary:</b> Knowledge graph completion (KGC) aims to predict missing facts in knowledge
graphs (KGs), which is crucial as modern KGs remain largely incomplete. While
training KGC models on multiple aligned KGs can improve performance, previous
methods that rely on transferring raw data among KGs raise privacy concerns. To
address this challenge, we propose a new federated learning framework that
implicitly aggregates knowledge from multiple KGs without demanding raw data
exchange and entity alignment. We treat each KG as a client that trains a local
language model through textbased knowledge representation learning. A central
server then aggregates the model weights from clients. As natural language
provides a universal representation, the same knowledge thus has similar
semantic representations across KGs. As such, the aggregated language model can
leverage complementary knowledge from multilingual KGs without demanding raw
user data sharing. Extensive experiments on a benchmark dataset demonstrate
that our method substantially improves KGC on multilingual KGs, achieving
comparable performance to state-of-the-art alignment-based models without
requiring any labeled alignments or raw user data sharing. Our codes will be
publicly available.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.10380v1">PPIDSG: A Privacy-Preserving Image Distribution Sharing Scheme with GAN
  in Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2023-12-16T08:32:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuting Ma, Yuanzhi Yao, Xiaohua Xu</p>
    <p><b>Summary:</b> Federated learning (FL) has attracted growing attention since it allows for
privacy-preserving collaborative training on decentralized clients without
explicitly uploading sensitive data to the central server. However, recent
works have revealed that it still has the risk of exposing private data to
adversaries. In this paper, we conduct reconstruction attacks and enhance
inference attacks on various datasets to better understand that sharing trained
classification model parameters to a central server is the main problem of
privacy leakage in FL. To tackle this problem, a privacy-preserving image
distribution sharing scheme with GAN (PPIDSG) is proposed, which consists of a
block scrambling-based encryption algorithm, an image distribution sharing
method, and local classification training. Specifically, our method can capture
the distribution of a target image domain which is transformed by the block
encryption algorithm, and upload generator parameters to avoid classifier
sharing with negligible influence on model performance. Furthermore, we apply a
feature extractor to motivate model utility and train it separately from the
classifier. The extensive experimental results and security analyses
demonstrate the superiority of our proposed scheme compared to other
state-of-the-art defense methods. The code is available at
https://github.com/ytingma/PPIDSG.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.10108v1">Privacy-Aware Document Visual Question Answering</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2023-12-15T06:30:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rubèn Tito, Khanh Nguyen, Marlon Tobaben, Raouf Kerkouche, Mohamed Ali Souibgui, Kangsoo Jung, Lei Kang, Ernest Valveny, Antti Honkela, Mario Fritz, Dimosthenis Karatzas</p>
    <p><b>Summary:</b> Document Visual Question Answering (DocVQA) is a fast growing branch of
document understanding. Despite the fact that documents contain sensitive or
copyrighted information, none of the current DocVQA methods offers strong
privacy guarantees.
  In this work, we explore privacy in the domain of DocVQA for the first time.
We highlight privacy issues in state of the art multi-modal LLM models used for
DocVQA, and explore possible solutions.
  Specifically, we focus on the invoice processing use case as a realistic,
widely used scenario for document understanding, and propose a large scale
DocVQA dataset comprising invoice documents and associated questions and
answers. We employ a federated learning scheme, that reflects the real-life
distribution of documents in different businesses, and we explore the use case
where the ID of the invoice issuer is the sensitive information to be
protected.
  We demonstrate that non-private models tend to memorise, behaviour that can
lead to exposing private information. We then evaluate baseline training
schemes employing federated learning and differential privacy in this
multi-modal scenario, where the sensitive information might be exposed through
any of the two input modalities: vision (document image) or language (OCR
tokens).
  Finally, we design an attack exploiting the memorisation effect of the model,
and demonstrate its effectiveness in probing different DocVQA models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.10096v1">Open Government Data Programs and Information Privacy Concerns: A
  Literature Review</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2023-12-14T16:03:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mehdi Barati</p>
    <p><b>Summary:</b> This study presents a narrative review of the literature on privacy concerns
of Open Government Data (OGD) programs and identifies suggested technical,
procedural, and legal remedies. Peer-reviewed articles were identified and
analysed from major bibliographic databases, including Web of Science, Digital
ACM Library, IEEE Explore Digital Library and Science Direct. Included articles
focus on identifying individual information privacy concerns from the viewpoint
of OGD stakeholders or providing solutions for mitigating concerns and risks.
Papers that discussed and focused on general privacy issues or privacy concerns
of open data in general or open science privacy concerns were excluded. Three
streams of research were identified: 1) exploring privacy concerns and balance
with OGD value propositions, 2) proposing solutions for mitigating privacy
concerns, and 3) developing risk-based frameworks for the OGD program at
different governmental levels. Findings suggest that contradictions with Fair
Information Practices, reidentification risks, conflicts with OGD value
propositions, and smart city data practices are significant privacy concerns in
the literature. Proposed solutions include technical, legal, and procedural
measures to mitigate privacy concerns. Building on the findings, practical
implications and suggested future research directions are provided.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.08685v1">Privacy Amplification by Iteration for ADMM with (Strongly) Convex
  Objective Functions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E">
  <p><b>Published on:</b> 2023-12-14T06:52:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> T-H. Hubert Chan, Hao Xie, Mengshi Zhao</p>
    <p><b>Summary:</b> We examine a private ADMM variant for (strongly) convex objectives which is a
primal-dual iterative method. Each iteration has a user with a private function
used to update the primal variable, masked by Gaussian noise for local privacy,
without directly adding noise to the dual variable. Privacy amplification by
iteration explores if noises from later iterations can enhance the privacy
guarantee when releasing final variables after the last iteration. Cyffers et
al. [ICML 2023] explored privacy amplification by iteration for the proximal
ADMM variant, where a user's entire private function is accessed and noise is
added to the primal variable. In contrast, we examine a private ADMM variant
requiring just one gradient access to a user's function, but both primal and
dual variables must be passed between successive iterations. To apply Balle et
al.'s [NeurIPS 2019] coupling framework to the gradient ADMM variant, we tackle
technical challenges with novel ideas. First, we address the non-expansive
mapping issue in ADMM iterations by using a customized norm. Second, because
the dual variables are not masked with any noise directly, their privacy
guarantees are achieved by treating two consecutive noisy ADMM iterations as a
Markov operator. Our main result is that the privacy guarantee for the gradient
ADMM variant can be amplified proportionally to the number of iterations. For
strongly convex objective functions, this amplification exponentially increases
with the number of iterations. These amplification results align with the
previously studied special case of stochastic gradient descent.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.08210v1">Differential Privacy Preserving Quantum Computing via Projection
  Operator Measurements</a></h3>
  
  <p><b>Published on:</b> 2023-12-13T15:27:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuqing Li, Yusheng Zhao, Xinyue Zhang, Hui Zhong, Miao Pan, Chi Zhang</p>
    <p><b>Summary:</b> Quantum computing has been widely applied in various fields, such as quantum
physics simulations, quantum machine learning, and big data analysis. However,
in the domains of data-driven paradigm, how to ensure the privacy of the
database is becoming a vital problem. For classical computing, we can
incorporate the concept of differential privacy (DP) to meet the standard of
privacy preservation by manually adding the noise. In the quantum computing
scenario, researchers have extended classic DP to quantum differential privacy
(QDP) by considering the quantum noise. In this paper, we propose a novel
approach to satisfy the QDP definition by considering the errors generated by
the projection operator measurement, which is denoted as shot noises. Then, we
discuss the amount of privacy budget that can be achieved with shot noises,
which serves as a metric for the level of privacy protection. Furthermore, we
provide the QDP of shot noise in quantum circuits with depolarizing noise.
Through numerical simulations, we show that shot noise can effectively provide
privacy protection in quantum computing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.08413v1">Privacy Constrained Fairness Estimation for Decision Trees</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2023-12-13T14:54:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Florian van der Steen, Fré Vink, Heysem Kaya</p>
    <p><b>Summary:</b> The protection of sensitive data becomes more vital, as data increases in
value and potency. Furthermore, the pressure increases from regulators and
society on model developers to make their Artificial Intelligence (AI) models
non-discriminatory. To boot, there is a need for interpretable, transparent AI
models for high-stakes tasks. In general, measuring the fairness of any AI
model requires the sensitive attributes of the individuals in the dataset, thus
raising privacy concerns. In this work, the trade-offs between fairness,
privacy and interpretability are further explored. We specifically examine the
Statistical Parity (SP) of Decision Trees (DTs) with Differential Privacy (DP),
that are each popular methods in their respective subfield. We propose a novel
method, dubbed Privacy-Aware Fairness Estimation of Rules (PAFER), that can
estimate SP in a DP-aware manner for DTs. DP, making use of a third-party legal
entity that securely holds this sensitive data, guarantees privacy by adding
noise to the sensitive data. We experimentally compare several DP mechanisms.
We show that using the Laplacian mechanism, the method is able to estimate SP
with low error while guaranteeing the privacy of the individuals in the dataset
with high certainty. We further show experimentally and theoretically that the
method performs better for DTs that humans generally find easier to interpret.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.08144v1">Privacy-Preserving Distributed Optimisation using Stochastic PDMM</a></h3>
  
  <p><b>Published on:</b> 2023-12-13T13:46:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sebastian O. Jordan, Qiongxiu Li, Richard Heusdens</p>
    <p><b>Summary:</b> Privacy-preserving distributed processing has received considerable attention
recently. The main purpose of these algorithms is to solve certain signal
processing tasks over a network in a decentralised fashion without revealing
private/secret data to the outside world. Because of the iterative nature of
these distributed algorithms, computationally complex approaches such as
(homomorphic) encryption are undesired. Recently, an information theoretic
method called subspace perturbation has been introduced for synchronous update
schemes. The main idea is to exploit a certain structure in the update
equations for noise insertion such that the private data is protected without
compromising the algorithm's accuracy. This structure, however, is absent in
asynchronous update schemes. In this paper we will investigate such
asynchronous schemes and derive a lower bound on the noise variance after
random initialisation of the algorithm. This bound shows that the privacy level
of asynchronous schemes is always better than or at least equal to that of
synchronous schemes. Computer simulations are conducted to consolidate our
theoretical results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.07992v1">On the privacy of federated Clustering: A Cryptographic View</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-13T09:04:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qiongxiu Li, Lixia Luo</p>
    <p><b>Summary:</b> The privacy concern in federated clustering has attracted considerable
attention in past decades. Many privacy-preserving clustering algorithms
leverage cryptographic techniques like homomorphic encryption or secure
multiparty computation, to guarantee full privacy, i.e., no additional
information is leaked other than the final output. However, given the iterative
nature of clustering algorithms, consistently encrypting intermediate outputs,
such as centroids, hampers efficiency. This paper delves into this intricate
trade-off, questioning the necessity of continuous encryption in iterative
algorithms. Using the federated K-means clustering as an example, we
mathematically formulate the problem of reconstructing input private data from
the intermediate centroids as a classical cryptographic problem called hidden
subset sum problem (HSSP)-extended from an NP-complete problem called subset
sum problem (SSP). Through an in-depth analysis, we show that existing
lattice-based HSSP attacks fail in reconstructing the private data given the
knowledge of intermediate centroids, thus it is secure to reveal them for the
sake of efficiency. To the best of our knowledge, our work is the first to cast
federated clustering's privacy concerns as a cryptographic problem HSSP such
that a concrete and rigorous analysis can be conducted.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.07956v1">Topology-Dependent Privacy Bound For Decentralized Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2023-12-13T08:07:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qiongxiu Li, Wenrui Yu, Changlong Ji, Richard Heusdens</p>
    <p><b>Summary:</b> Decentralized Federated Learning (FL) has attracted significant attention due
to its enhanced robustness and scalability compared to its centralized
counterpart. It pivots on peer-to-peer communication rather than depending on a
central server for model aggregation. While prior research has delved into
various factors of decentralized FL such as aggregation methods and
privacy-preserving techniques, one crucial aspect affecting privacy is
relatively unexplored: the underlying graph topology. In this paper, we fill
the gap by deriving a stringent privacy bound for decentralized FL under the
condition that the accuracy is not compromised, highlighting the pivotal role
of graph topology. Specifically, we demonstrate that the minimum privacy loss
at each model aggregation step is dependent on the size of what we term as
'honest components', the maximally connected subgraphs once all untrustworthy
participants are excluded from the networks, which is closely tied to network
robustness. Our analysis suggests that attack-resilient networks will provide a
superior privacy guarantee. We further validate this by studying both Poisson
and power law networks, showing that the latter, being less robust against
attacks, indeed reveals more privacy. In addition to a theoretical analysis, we
consolidate our findings by examining two distinct privacy attacks: membership
inference and gradient inversion.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.07948v1">Zero-Knowledge Proof of Traffic: A Deterministic and Privacy-Preserving
  Cross Verification Mechanism for Cooperative Perception Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-13T07:53:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ye Tao, Ehsan Javanmardi, Pengfei Lin, Jin Nakazato, Yuze Jiang, Manabu Tsukada, Hiroshi Esaki</p>
    <p><b>Summary:</b> Cooperative perception is crucial for connected automated vehicles in
intelligent transportation systems (ITSs); however, ensuring the authenticity
of perception data remains a challenge as the vehicles cannot verify events
that they do not witness independently. Various studies have been conducted on
establishing the authenticity of data, such as trust-based statistical methods
and plausibility-based methods. However, these methods are limited as they
require prior knowledge such as previous sender behaviors or predefined rules
to evaluate the authenticity. To overcome this limitation, this study proposes
a novel approach called zero-knowledge Proof of Traffic (zk-PoT), which
involves generating cryptographic proofs to the traffic observations. Multiple
independent proofs regarding the same vehicle can be deterministically
cross-verified by any receivers without relying on ground truth, probabilistic,
or plausibility evaluations. Additionally, no private information is
compromised during the entire procedure. A full on-board unit software stack
that reflects the behavior of zk-PoT is implemented within a specifically
designed simulator called Flowsim. A comprehensive experimental analysis is
then conducted using synthesized city-scale simulations, which demonstrates
that zk-PoT's cross-verification ratio ranges between 80 % to 96 %, and 80 % of
the verification is achieved in 2 s, with a protocol overhead of approximately
25 %. Furthermore, the analyses of various attacks indicate that most of the
attacks could be prevented, and some, such as collusion attacks, can be
mitigated. The proposed approach can be incorporated into existing works,
including the European Telecommunications Standards Institute (ETSI) and the
International Organization for Standardization (ISO) ITS standards, without
disrupting the backward compatibility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.07947v1">Adaptive Differentially Quantized Subspace Perturbation (ADQSP): A
  Unified Framework for Privacy-Preserving Distributed Average Consensus</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-13T07:52:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qiongxiu Li, Jaron Skovsted Gundersen, Milan Lopuhaa-Zwakenberg, Richard Heusdens</p>
    <p><b>Summary:</b> Privacy-preserving distributed average consensus has received significant
attention recently due to its wide applicability. Based on the achieved
performances, existing approaches can be broadly classified into perfect
accuracy-prioritized approaches such as secure multiparty computation (SMPC),
and worst-case privacy-prioritized approaches such as differential privacy
(DP). Methods of the first class achieve perfect output accuracy but reveal
some private information, while methods from the second class provide privacy
against the strongest adversary at the cost of a loss of accuracy. In this
paper, we propose a general approach named adaptive differentially quantized
subspace perturbation (ADQSP) which combines quantization schemes with
so-called subspace perturbation. Although not relying on cryptographic
primitives, the proposed approach enjoys the benefits of both
accuracy-prioritized and privacy-prioritized methods and is able to unify them.
More specifically, we show that by varying a single quantization parameter the
proposed method can vary between SMPC-type performances and DP-type
performances. Our results show the potential of exploiting traditional
distributed signal processing tools for providing cryptographic guarantees. In
addition to a comprehensive theoretical analysis, numerical validations are
conducted to substantiate our results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.07371v1">Privacy-Aware Energy Consumption Modeling of Connected Battery Electric
  Vehicles using Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2023-12-12T15:40:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sen Yan, Hongyuan Fang, Ji Li, Tomas Ward, Noel O'Connor, Mingming Liu</p>
    <p><b>Summary:</b> Battery Electric Vehicles (BEVs) are increasingly significant in modern
cities due to their potential to reduce air pollution. Precise and real-time
estimation of energy consumption for them is imperative for effective itinerary
planning and optimizing vehicle systems, which can reduce driving range anxiety
and decrease energy costs. As public awareness of data privacy increases,
adopting approaches that safeguard data privacy in the context of BEV energy
consumption modeling is crucial. Federated Learning (FL) is a promising
solution mitigating the risk of exposing sensitive information to third parties
by allowing local data to remain on devices and only sharing model updates with
a central server. Our work investigates the potential of using FL methods, such
as FedAvg, and FedPer, to improve BEV energy consumption prediction while
maintaining user privacy. We conducted experiments using data from 10 BEVs
under simulated real-world driving conditions. Our results demonstrate that the
FedAvg-LSTM model achieved a reduction of up to 67.84\% in the MAE value of the
prediction results. Furthermore, we explored various real-world scenarios and
discussed how FL methods can be employed in those cases. Our findings show that
FL methods can effectively improve the performance of BEV energy consumption
prediction while maintaining user privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.07060v1">Layered Randomized Quantization for Communication-Efficient and
  Privacy-Preserving Distributed Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2023-12-12T08:27:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guangfeng Yan, Tan Li, Tian Lan, Kui Wu, Linqi Song</p>
    <p><b>Summary:</b> Next-generation wireless networks, such as edge intelligence and wireless
distributed learning, face two critical challenges: communication efficiency
and privacy protection. In this work, our focus is on addressing these issues
in a distributed learning framework. We consider a new approach that
simultaneously achieves communication efficiency and privacy protection by
exploiting the privacy advantage offered by quantization. Specifically, we use
a quantization scheme called \textbf{Gau}ssian \textbf{L}ayered
\textbf{R}andomized \textbf{Q}uantization (Gau-LRQ) that compresses the raw
model gradients using a layer multishift coupler. By adjusting the parameters
of Gau-LRQ, we shape the quantization error to follow the expected Gaussian
distribution, thus ensuring client-level differential privacy (CLDP). We
demonstrate the effectiveness of our proposed Gau-LRQ in the distributed
stochastic gradient descent (SGD) framework and theoretically quantify the
trade-offs between communication, privacy, and convergence performance. We
further improve the convergence performance by enabling dynamic private budget
and quantization bit allocation. We achieve this by using an optimization
formula that minimizes convergence error subject to the privacy budget
constraint. We evaluate our approach on multiple datasets, including MNIST,
CIFAR-10, and CIFAR-100, and show that our proposed method outperforms the
baselines in terms of learning performance under various privacy constraints.
Moreover, we observe that dynamic privacy allocation yields additional accuracy
improvements for the models compared to the fixed scheme.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.07055v1">Communication Cost Reduction for Subgraph Counting under Local
  Differential Privacy via Hash Functions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2023-12-12T08:12:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Quentin Hillebrand, Vorapong Suppakitpaisarn, Tetsuo Shibuya</p>
    <p><b>Summary:</b> We suggest the use of hash functions to cut down the communication costs when
counting subgraphs under edge local differential privacy. While various
algorithms exist for computing graph statistics, including the count of
subgraphs, under the edge local differential privacy, many suffer with high
communication costs, making them less efficient for large graphs. Though data
compression is a typical approach in differential privacy, its application in
local differential privacy requires a form of compression that every node can
reproduce. In our study, we introduce linear congruence hashing. With a
sampling rate of $s$, our method can cut communication costs by a factor of
$s^2$, albeit at the cost of increasing variance in the published graph
statistic by a factor of $s$. The experimental results indicate that, when
matched for communication costs, our method achieves a reduction in the
$\ell_2$-error for triangle counts by up to 1000 times compared to the
performance of leading algorithms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.06989v1">Task-Agnostic Privacy-Preserving Representation Learning for Federated
  Learning Against Attribute Inference Attacks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-12T05:17:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Caridad Arroyo Arevalo, Sayedeh Leila Noorbakhsh, Yun Dong, Yuan Hong, Binghui Wang</p>
    <p><b>Summary:</b> Federated learning (FL) has been widely studied recently due to its property
to collaboratively train data from different devices without sharing the raw
data. Nevertheless, recent studies show that an adversary can still be possible
to infer private information about devices' data, e.g., sensitive attributes
such as income, race, and sexual orientation. To mitigate the attribute
inference attacks, various existing privacy-preserving FL methods can be
adopted/adapted. However, all these existing methods have key limitations: they
need to know the FL task in advance, or have intolerable computational
overheads or utility losses, or do not have provable privacy guarantees.
  We address these issues and design a task-agnostic privacy-preserving
presentation learning method for FL ({\bf TAPPFL}) against attribute inference
attacks. TAPPFL is formulated via information theory. Specifically, TAPPFL has
two mutual information goals, where one goal learns task-agnostic data
representations that contain the least information about the private attribute
in each device's data, and the other goal ensures the learnt data
representations include as much information as possible about the device data
to maintain FL utility. We also derive privacy guarantees of TAPPFL against
worst-case attribute inference attacks, as well as the inherent tradeoff
between utility preservation and privacy protection. Extensive results on
multiple datasets and applications validate the effectiveness of TAPPFL to
protect data privacy, maintain the FL utility, and be efficient as well.
Experimental results also show that TAPPFL outperforms the existing
defenses\footnote{Source code and full version:
\url{https://github.com/TAPPFL}}.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.06658v1">Mean estimation in the add-remove model of differential privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">  
  <p><b>Published on:</b> 2023-12-11T18:59:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alex Kulesza, Ananda Theertha Suresh, Yuyan Wang</p>
    <p><b>Summary:</b> Differential privacy is often studied under two different models of
neighboring datasets: the add-remove model and the swap model. While the swap
model is used extensively in the academic literature, many practical libraries
use the more conservative add-remove model. However, analysis under the
add-remove model can be cumbersome, and obtaining results with tight constants
requires some additional work. Here, we study the problem of one-dimensional
mean estimation under the add-remove model of differential privacy. We propose
a new algorithm and show that it is min-max optimal, that it has the correct
constant in the leading term of the mean squared error, and that this constant
is the same as the optimal algorithm in the swap model. Our results show that,
for mean estimation, the add-remove and swap model give nearly identical error
even though the add-remove model cannot treat the size of the dataset as public
information. In addition, we demonstrate empirically that our proposed
algorithm yields a factor of two improvement in mean squared error over
algorithms often used in practice.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.06717v1">Privacy Issues in Large Language Models: A Survey</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2023-12-11T01:26:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Seth Neel, Peter Chang</p>
    <p><b>Summary:</b> This is the first survey of the active area of AI research that focuses on
privacy issues in Large Language Models (LLMs). Specifically, we focus on work
that red-teams models to highlight privacy risks, attempts to build privacy
into the training or inference process, enables efficient data deletion from
trained models to comply with existing privacy regulations, and tries to
mitigate copyright issues. Our focus is on summarizing technical research that
develops algorithms, proves theorems, and runs empirical evaluations. While
there is an extensive body of legal and policy work addressing these challenges
from a different angle, that is not the focus of our survey. Nevertheless,
these works, along with recent legal developments do inform how these technical
problems are formalized, and so we discuss them briefly in Section 1. While we
have made our best effort to include all the relevant work, due to the fast
moving nature of this research we may have missed some recent work. If we have
missed some of your work please contact us, as we will attempt to keep this
survey relatively up to date. We are maintaining a repository with the list of
papers covered in this survey and any relevant code that was publicly available
at https://github.com/safr-ml-lab/survey-llm.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.05720v1">Beyond Gradient and Priors in Privacy Attacks: Leveraging Pooler Layer
  Inputs of Language Models in Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-10T01:19:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jianwei Li, Sheng Liu, Qi Lei</p>
    <p><b>Summary:</b> Federated learning (FL) emphasizes decentralized training by storing data
locally and sending only model updates, underlining user privacy. Recently, a
line of works on privacy attacks impairs user privacy by extracting sensitive
training text from language models in the context of FL. Yet, these attack
techniques face distinct hurdles: some work chiefly with limited batch sizes
(e.g., batch size of 1), and others are easily detectable. This paper
introduces an innovative approach that is challenging to detect, significantly
enhancing the recovery rate of text in various batch-size settings. Building on
fundamental gradient matching and domain prior knowledge, we enhance the attack
by recovering the input of the Pooler layer of language models, which enables
us to provide additional supervised signals at the feature level. Unlike
gradient data, these signals do not average across sentences and tokens,
thereby offering more nuanced and effective insights. We benchmark our method
using text classification tasks on datasets such as CoLA, SST-2, and Rotten
Tomatoes. Across different batch sizes and models, our approach consistently
outperforms previous state-of-the-art results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.05686v1">Privacy Preserving Multi-Agent Reinforcement Learning in Supply Chains</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2023-12-09T21:25:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ananta Mukherjee, Peeyush Kumar, Boling Yang, Nishanth Chandran, Divya Gupta</p>
    <p><b>Summary:</b> This paper addresses privacy concerns in multi-agent reinforcement learning
(MARL), specifically within the context of supply chains where individual
strategic data must remain confidential. Organizations within the supply chain
are modeled as agents, each seeking to optimize their own objectives while
interacting with others. As each organization's strategy is contingent on
neighboring strategies, maintaining privacy of state and action-related
information is crucial. To tackle this challenge, we propose a game-theoretic,
privacy-preserving mechanism, utilizing a secure multi-party computation (MPC)
framework in MARL settings. Our major contribution is the successful
implementation of a secure MPC framework, SecFloat on EzPC, to solve this
problem. However, simply implementing policy gradient methods such as MADDPG
operations using SecFloat, while conceptually feasible, would be
programmatically intractable. To overcome this hurdle, we devise a novel
approach that breaks down the forward and backward pass of the neural network
into elementary operations compatible with SecFloat , creating efficient and
secure versions of the MADDPG algorithm. Furthermore, we present a learning
mechanism that carries out floating point operations in a privacy-preserving
manner, an important feature for successful learning in MARL framework.
Experiments reveal that there is on average 68.19% less supply chain wastage in
2 PC compared to no data share, while also giving on average 42.27% better
average cumulative revenue for each player. This work paves the way for
practical, privacy-preserving MARL, promising significant improvements in
secure computation within supply chain contexts and broadly.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.05659v1">Optimal Unbiased Randomizers for Regression with Label Differential
  Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-09T19:58:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ashwinkumar Badanidiyuru, Badih Ghazi, Pritish Kamath, Ravi Kumar, Ethan Leeman, Pasin Manurangsi, Avinash V Varadarajan, Chiyuan Zhang</p>
    <p><b>Summary:</b> We propose a new family of label randomizers for training regression models
under the constraint of label differential privacy (DP). In particular, we
leverage the trade-offs between bias and variance to construct better label
randomizers depending on a privately estimated prior distribution over the
labels. We demonstrate that these randomizers achieve state-of-the-art
privacy-utility trade-offs on several datasets, highlighting the importance of
reducing bias when training neural networks with label DP. We also provide
theoretical results shedding light on the structural properties of the optimal
unbiased randomizers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.05436v1">Trading Off Scalability, Privacy, and Performance in Data Synthesis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2023-12-09T02:04:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiao Ling, Tim Menzies, Christopher Hazard, Jack Shu, Jacob Beel</p>
    <p><b>Summary:</b> Synthetic data has been widely applied in the real world recently. One
typical example is the creation of synthetic data for privacy concerned
datasets. In this scenario, synthetic data substitute the real data which
contains the privacy information, and is used to public testing for machine
learning models. Another typical example is the unbalance data over-sampling
which the synthetic data is generated in the region of minority samples to
balance the positive and negative ratio when training the machine learning
models. In this study, we concentrate on the first example, and introduce (a)
the Howso engine, and (b) our proposed random projection based synthetic data
generation framework. We evaluate these two algorithms on the aspects of
privacy preservation and accuracy, and compare them to the two state-of-the-art
synthetic data generation algorithms DataSynthesizer and Synthetic Data Vault.
We show that the synthetic data generated by Howso engine has good privacy and
accuracy, which results the best overall score. On the other hand, our proposed
random projection based framework can generate synthetic data with highest
accuracy score, and has the fastest scalability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.05183v1">A Privacy-Preserving Framework for Cloud-Based HVAC Control</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2023-12-08T17:09:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhenan Feng, Ehsan Nekouei</p>
    <p><b>Summary:</b> The objective of this work is (i) to develop an encrypted cloud-based HVAC
control framework to ensure the privacy of occupancy information, (ii) to
reduce the communication and computation costs of encrypted HVAC control.
Occupancy of a building is sensitive and private information that can be
accurately inferred by cloud-based HVAC controllers. To ensure the privacy of
the privacy information, in our framework, the measurements of an HVAC system
are encrypted by a fully homomorphic encryption prior to communication with the
cloud controller. We first develop an encrypted fast gradient algorithm that
allows the cloud controller to regulate the indoor temperature and CO$_2$ of a
building by solving two model predictive control problems. We next develop an
event-triggered control policy to reduce the communication and computation
costs of the encrypted HVAC control. We cast the optimal design of the
event-triggered policy as an optimal control problem wherein the objective is
to minimize a linear combination of the control and communication costs. Using
Bellman's optimality principle, we study the structural properties of the
optimal event-triggered policy and show that the optimal triggering policy is a
function of the current state, the last communicated state with the cloud, and
the time since the last communication with the cloud. We also show that the
optimal design of the event-triggered policy can be transformed into a Markov
decision process by introducing two new states. We finally study the
performance of the developed encrypted HVAC control framework using the TRNSYS
simulator. Our numerical results show that the proposed framework not only
ensures efficient control of the indoor temperature and CO$_2$ but also reduces
the computation and communication costs of encrypted HVAC control by at least
60%.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.05114v1">On the Inadequacy of Similarity-based Privacy Metrics: Reconstruction
  Attacks against "Truly Anonymous Synthetic Data''</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2023-12-08T15:42:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Georgi Ganev, Emiliano De Cristofaro</p>
    <p><b>Summary:</b> Training generative models to produce synthetic data is meant to provide a
privacy-friendly approach to data release. However, we get robust guarantees
only when models are trained to satisfy Differential Privacy (DP). Alas, this
is not the standard in industry as many companies use ad-hoc strategies to
empirically evaluate privacy based on the statistical similarity between
synthetic and real data. In this paper, we review the privacy metrics offered
by leading companies in this space and shed light on a few critical flaws in
reasoning about privacy entirely via empirical evaluations. We analyze the
undesirable properties of the most popular metrics and filters and demonstrate
their unreliability and inconsistency through counter-examples. We then present
a reconstruction attack, ReconSyn, which successfully recovers (i.e., leaks all
attributes of) at least 78% of the low-density train records (or outliers) with
only black-box access to a single fitted generative model and the privacy
metrics. Finally, we show that applying DP only to the model or using
low-utility generators does not mitigate ReconSyn as the privacy leakage
predominantly comes from the metrics. Overall, our work serves as a warning to
practitioners not to deviate from established privacy-preserving mechanisms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.04903v1">Differential privacy statistical inference for a directed graph network
  model with covariates</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> 
  <p><b>Published on:</b> 2023-12-08T08:36:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jing Luo, Zhimeng Xu</p>
    <p><b>Summary:</b> The real network has two characteristics: heterogeneity and homogeneity. A
directed network model with covariates is proposed to analyze these two
features, and the asymptotic theory of parameter Maximum likelihood
estimators(MLEs) is established. However, in many practical cases, network data
often carries a lot of sensitive information. How to achieve the trade-off
between privacy and utility has become an important issue in network data
analysis. In this paper, we study a directed $\beta$-model with covariates
under differential privacy mechanism. It includes $2n$-dimensional node degree
parameters $\boldsymbol{\theta}$ and a $p$-dimensional homogeneity parameter
$\boldsymbol{\gamma}$ that describes the covariate effect. We use the discrete
Laplace mechanism to release noise for the bi-degree sequences. Based on moment
equations, we estimate the parameters of both degree heterogeneity and
homogeneity in the model, and derive the consistency and asymptotic normality
of the differentially private estimators as the number of nodes tends to
infinity. Numerical simulations and case studies are provided to demonstrate
the validity of our theoretical results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.04738v1">DPI: Ensuring Strict Differential Privacy for Infinite Data Streaming</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-07T22:37:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuya Feng, Meisam Mohammady, Han Wang, Xiaochen Li, Zhan Qin, Yuan Hong</p>
    <p><b>Summary:</b> Streaming data, crucial for applications like crowdsourcing analytics,
behavior studies, and real-time monitoring, faces significant privacy risks due
to the large and diverse data linked to individuals. In particular, recent
efforts to release data streams, using the rigorous privacy notion of
differential privacy (DP), have encountered issues with unbounded privacy
leakage. This challenge limits their applicability to only a finite number of
time slots (''finite data stream'') or relaxation to protecting the events
(''event or $w$-event DP'') rather than all the records of users. A persistent
challenge is managing the sensitivity of outputs to inputs in situations where
users contribute many activities and data distributions evolve over time. In
this paper, we present a novel technique for Differentially Private data
streaming over Infinite disclosure (DPI) that effectively bounds the total
privacy leakage of each user in infinite data streams while enabling accurate
data collection and analysis. Furthermore, we also maximize the accuracy of DPI
via a novel boosting mechanism. Finally, extensive experiments across various
streaming applications and real datasets (e.g., COVID-19, Network Traffic, and
USDA Production), show that DPI maintains high utility for infinite data
streams in diverse settings. Code for DPI is available at
https://github.com/ShuyaFeng/DPI.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.04692v1">Diffence: Fencing Membership Privacy With Diffusion Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2023-12-07T20:45:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuefeng Peng, Ali Naseh, Amir Houmansadr</p>
    <p><b>Summary:</b> Deep learning models, while achieving remarkable performance across various
tasks, are vulnerable to member inference attacks, wherein adversaries identify
if a specific data point was part of a model's training set. This
susceptibility raises substantial privacy concerns, especially when models are
trained on sensitive datasets. Current defense methods often struggle to
provide robust protection without hurting model utility, and they often require
retraining the model or using extra data. In this work, we introduce a novel
defense framework against membership attacks by leveraging generative models.
The key intuition of our defense is to remove the differences between member
and non-member inputs which can be used to perform membership attacks, by
re-generating input samples before feeding them to the target model. Therefore,
our defense works \emph{pre-inference}, which is unlike prior defenses that are
either training-time (modify the model) or post-inference time (modify the
model's output).
  A unique feature of our defense is that it works on input samples only,
without modifying the training or inference phase of the target model.
Therefore, it can be cascaded with other defense mechanisms as we demonstrate
through experiments. Through extensive experimentation, we show that our
approach can serve as a robust plug-n-play defense mechanism, enhancing
membership privacy without compromising model utility in both baseline and
defended settings. For example, our method enhanced the effectiveness of recent
state-of-the-art defenses, reducing attack accuracy by an average of 5.7\% to
12.4\% across three datasets, without any impact on the model's accuracy. By
integrating our method with prior defenses, we achieve new state-of-the-art
performance in the privacy-utility trade-off.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.04447v1">Privacy-preserving quantum federated learning via gradient hiding</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2023-12-07T17:16:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Changhao Li, Niraj Kumar, Zhixin Song, Shouvanik Chakrabarti, Marco Pistoia</p>
    <p><b>Summary:</b> Distributed quantum computing, particularly distributed quantum machine
learning, has gained substantial prominence for its capacity to harness the
collective power of distributed quantum resources, transcending the limitations
of individual quantum nodes. Meanwhile, the critical concern of privacy within
distributed computing protocols remains a significant challenge, particularly
in standard classical federated learning (FL) scenarios where data of
participating clients is susceptible to leakage via gradient inversion attacks
by the server. This paper presents innovative quantum protocols with quantum
communication designed to address the FL problem, strengthen privacy measures,
and optimize communication efficiency. In contrast to previous works that
leverage expressive variational quantum circuits or differential privacy
techniques, we consider gradient information concealment using quantum states
and propose two distinct FL protocols, one based on private inner-product
estimation and the other on incremental learning. These protocols offer
substantial advancements in privacy preservation with low communication
resources, forging a path toward efficient quantum communication-assisted FL
protocols and contributing to the development of secure distributed quantum
machine learning, thus addressing critical privacy concerns in the quantum
computing era.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.04404v2">On the Impact of Multi-dimensional Local Differential Privacy on
  Fairness</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2023-12-07T16:17:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Karima Makhlouf, Heber H. Arcolezi, Sami Zhioua, Ghassen Ben Brahim, Catuscia Palamidessi</p>
    <p><b>Summary:</b> Automated decision systems are increasingly used to make consequential
decisions in people's lives. Due to the sensitivity of the manipulated data as
well as the resulting decisions, several ethical concerns need to be addressed
for the appropriate use of such technologies, in particular, fairness and
privacy. Unlike previous work, which focused on centralized differential
privacy (DP) or local DP (LDP) for a single sensitive attribute, in this paper,
we examine the impact of LDP in the presence of several sensitive attributes
(i.e., multi-dimensional data) on fairness. Detailed empirical analysis on
synthetic and benchmark datasets revealed very relevant observations. In
particular, (1) multi-dimensional LDP is an efficient approach to reduce
disparity, (2) the multi-dimensional approach of LDP (independent vs. combined)
matters only at low privacy guarantees, and (3) the outcome Y distribution has
an important effect on which group is more sensitive to the obfuscation. Last,
we summarize our findings in the form of recommendations to guide practitioners
in adopting effective privacy-preserving practices while maintaining fairness
and utility in ML applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.04106v1">Identity-Obscured Neural Radiance Fields: Privacy-Preserving 3D Facial
  Reconstruction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2023-12-07T07:41:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiayi Kong, Baixin Xu, Xurui Song, Chen Qian, Jun Luo, Ying He</p>
    <p><b>Summary:</b> Neural radiance fields (NeRF) typically require a complete set of images
taken from multiple camera perspectives to accurately reconstruct geometric
details. However, this approach raise significant privacy concerns in the
context of facial reconstruction. The critical need for privacy protection
often leads invidividuals to be reluctant in sharing their facial images, due
to fears of potential misuse or security risks. Addressing these concerns, we
propose a method that leverages privacy-preserving images for reconstructing 3D
head geometry within the NeRF framework. Our method stands apart from
traditional facial reconstruction techniques as it does not depend on RGB
information from images containing sensitive facial data. Instead, it
effectively generates plausible facial geometry using a series of
identity-obscured inputs, thereby protecting facial privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.04068v1">Making Translators Privacy-aware on the User's Side</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2023-12-07T06:23:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ryoma Sato</p>
    <p><b>Summary:</b> We propose PRISM to enable users of machine translation systems to preserve
the privacy of data on their own initiative. There is a growing demand to apply
machine translation systems to data that require privacy protection. While
several machine translation engines claim to prioritize privacy, the extent and
specifics of such protection are largely ambiguous. First, there is often a
lack of clarity on how and to what degree the data is protected. Even if
service providers believe they have sufficient safeguards in place,
sophisticated adversaries might still extract sensitive information. Second,
vulnerabilities may exist outside of these protective measures, such as within
communication channels, potentially leading to data leakage. As a result, users
are hesitant to utilize machine translation engines for data demanding high
levels of privacy protection, thereby missing out on their benefits. PRISM
resolves this problem. Instead of relying on the translation service to keep
data safe, PRISM provides the means to protect data on the user's side. This
approach ensures that even machine translation engines with inadequate privacy
measures can be used securely. For platforms already equipped with privacy
safeguards, PRISM acts as an additional protection layer, reinforcing their
security furthermore. PRISM adds these privacy features without significantly
compromising translation accuracy. Our experiments demonstrate the
effectiveness of PRISM using real-world translators, T5 and ChatGPT
(GPT-3.5-turbo), and the datasets with two languages. PRISM effectively
balances privacy protection with translation accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.03918v1">Data Safety vs. App Privacy: Comparing the Usability of Android and iOS
  Privacy Labels</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2023-12-06T21:32:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yanzi Lin, Jaideep Juneja, Eleanor Birrell, Lorrie Cranor</p>
    <p><b>Summary:</b> Privacy labels -- standardized, compact representations of data collection
and data use practices -- have frequently been recommended as a solution to the
shortcomings of privacy policies. Apple introduced mandatory privacy labels for
apps in its App Store in December 2020; Google introduced data safety labels
for Android apps in July 2022. iOS app privacy labels have been evaluated and
critiqued in prior work. In this work, we evaluated Android data safety labels
and explored how differences between the two label designs impact user
comprehension and label utility. We conducted a between-subjects,
semi-structured interview study with 12 Android users and 12 iOS users. While
some users found Android Data Safety Labels informative and helpful, other
users found them too vague. Compared to iOS App Privacy Labels, Android users
found the distinction between data collection groups more intuitive and found
explicit inclusion of omitted data collection groups more salient. However,
some users expressed skepticism regarding elided information about collected
data type categories. Most users missed critical information due to not
expanding the accordion interface, and they were surprised by collection
practices excluded from Android's definitions. Our findings also revealed that
Android users generally appreciated information about security practices
included in the labels and iOS users wanted that information added.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2401.01353v1">The Boomerang protocol: A Decentralised Privacy-Preserving Verifiable
  Incentive Protocol</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-06T09:37:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ralph Ankele, Hamed Haddadi</p>
    <p><b>Summary:</b> In the era of data-driven economies, incentive systems and loyalty programs,
have become ubiquitous in various sectors, including advertising, retail,
travel, and financial services. While these systems offer advantages for both
users and companies, they necessitate the transfer and analysis of substantial
amounts of sensitive data. Privacy concerns have become increasingly pertinent,
necessitating the development of privacy-preserving incentive protocols.
Despite the rising demand for secure and decentralised systems, the existing
landscape lacks a comprehensive solution. We propose the Boomerang protocol, a
novel decentralised privacy-preserving incentive protocol that leverages
cryptographic black box accumulators to securely store user interactions within
the incentive system. Moreover, the protocol employs zero-knowledge proofs
based on BulletProofs to transparently compute rewards for users, ensuring
verifiability while preserving their privacy. To further enhance public
verifiability and transparency, we utilise a smart contract on a Layer 1
blockchain to verify these zero-knowledge proofs. The careful combination of
black box accumulators with selected elliptic curves in the zero-knowledge
proofs makes the Boomerang protocol highly efficient. Our proof of concept
implementation shows that we can handle up to 23.6 million users per day, on a
single-threaded backend server with financial costs of approximately 2 US$.
Using the Solana blockchain we can handle 15.5 million users per day with
approximate costs of 0.00011 US$ per user. The Boomerang protocol represents a
significant advancement in privacy-preserving incentive protocols, laying the
groundwork for a more secure and privacy-centric future.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.05265v1">Multimodal Group Emotion Recognition In-the-wild Using Privacy-Compliant
  Features</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2023-12-06T08:58:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anderson Augusma, Dominique Vaufreydaz, Frédérique Letué</p>
    <p><b>Summary:</b> This paper explores privacy-compliant group-level emotion recognition
''in-the-wild'' within the EmotiW Challenge 2023. Group-level emotion
recognition can be useful in many fields including social robotics,
conversational agents, e-coaching and learning analytics. This research imposes
itself using only global features avoiding individual ones, i.e. all features
that can be used to identify or track people in videos (facial landmarks, body
poses, audio diarization, etc.). The proposed multimodal model is composed of a
video and an audio branches with a cross-attention between modalities. The
video branch is based on a fine-tuned ViT architecture. The audio branch
extracts Mel-spectrograms and feed them through CNN blocks into a transformer
encoder. Our training paradigm includes a generated synthetic dataset to
increase the sensitivity of our model on facial expression within the image in
a data-driven way. The extensive experiments show the significance of our
methodology. Our privacy-compliant proposal performs fairly on the EmotiW
challenge, with 79.24% and 75.13% of accuracy respectively on validation and
test set for the best models. Noticeably, our findings highlight that it is
possible to reach this accuracy level with privacy-compliant features using
only 5 frames uniformly distributed on the video.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.03293v1">Securing Data Platforms: Strategic Masking Techniques for Privacy and
  Security for B2B Enterprise Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2023-12-06T05:04:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mandar Khoje</p>
    <p><b>Summary:</b> In today's digital age, the imperative to protect data privacy and security
is a paramount concern, especially for business-to-business (B2B) enterprises
that handle sensitive information. These enterprises are increasingly
constructing data platforms, which are integrated suites of technology
solutions architected for the efficient management, processing, storage, and
data analysis. It has become critical to design these data platforms with
mechanisms that inherently support data privacy and security, particularly as
they encounter the added complexity of safeguarding unstructured data types
such as log files and text documents. Within this context, data masking stands
out as a vital feature of data platform architecture. It proactively conceals
sensitive elements, ensuring data privacy while preserving the information's
value for business operations and analytics. This protective measure entails a
strategic two-fold process: firstly, accurately pinpointing the sensitive data
that necessitates concealment, and secondly, applying sophisticated methods to
disguise that data effectively within the data platform infrastructure. This
research delves into the nuances of embedding advanced data masking techniques
within the very fabric of data platforms and an in-depth exploration of how
enterprises can adopt a comprehensive approach toward effective data masking
implementation by exploring different identification and anonymization
techniques.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.03252v1">Privacy-Preserving Task-Oriented Semantic Communications Against Model
  Inversion Attacks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2023-12-06T02:57:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yanhu Wang, Shuaishuai Guo, Yiqin Deng, Haixia Zhang, Yuguang Fang</p>
    <p><b>Summary:</b> Semantic communication has been identified as a core technology for the sixth
generation (6G) of wireless networks. Recently, task-oriented semantic
communications have been proposed for low-latency inference with limited
bandwidth. Although transmitting only task-related information does protect a
certain level of user privacy, adversaries could apply model inversion
techniques to reconstruct the raw data or extract useful information, thereby
infringing on users' privacy. To mitigate privacy infringement, this paper
proposes an information bottleneck and adversarial learning (IBAL) approach to
protect users' privacy against model inversion attacks. Specifically, we
extract task-relevant features from the input based on the information
bottleneck (IB) theory. To overcome the difficulty in calculating the mutual
information in high-dimensional space, we derive a variational upper bound to
estimate the true mutual information. To prevent data reconstruction from
task-related features by adversaries, we leverage adversarial learning to train
encoder to fool adversaries by maximizing reconstruction distortion.
Furthermore, considering the impact of channel variations on privacy-utility
trade-off and the difficulty in manually tuning the weights of each loss, we
propose an adaptive weight adjustment method. Numerical results demonstrate
that the proposed approaches can effectively protect privacy without
significantly affecting task performance and achieve better privacy-utility
trade-offs than baseline methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.04594v1">FedGeo: Privacy-Preserving User Next Location Prediction with Federated
  Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2023-12-06T01:43:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chung Park, Taekyoon Choi, Taesan Kim, Mincheol Cho, Junui Hong, Minsung Choi, Jaegul Choo</p>
    <p><b>Summary:</b> A User Next Location Prediction (UNLP) task, which predicts the next location
that a user will move to given his/her trajectory, is an indispensable task for
a wide range of applications. Previous studies using large-scale trajectory
datasets in a single server have achieved remarkable performance in UNLP task.
However, in real-world applications, legal and ethical issues have been raised
regarding privacy concerns leading to restrictions against sharing human
trajectory datasets to any other server. In response, Federated Learning (FL)
has emerged to address the personal privacy issue by collaboratively training
multiple clients (i.e., users) and then aggregating them. While previous
studies employed FL for UNLP, they are still unable to achieve reliable
performance because of the heterogeneity of clients' mobility. To tackle this
problem, we propose the Federated Learning for Geographic Information (FedGeo),
a FL framework specialized for UNLP, which alleviates the heterogeneity of
clients' mobility and guarantees personal privacy protection. Firstly, we
incorporate prior global geographic adjacency information to the local client
model, since the spatial correlation between locations is trained partially in
each client who has only a heterogeneous subset of the overall trajectories in
FL. We also introduce a novel aggregation method that minimizes the gap between
client models to solve the problem of client drift caused by differences
between client models when learning with their heterogeneous data. Lastly, we
probabilistically exclude clients with extremely heterogeneous data from the FL
process by focusing on clients who visit relatively diverse locations. We show
that FedGeo is superior to other FL methods for model performance in UNLP task.
We also validated our model in a real-world application using our own
customers' mobile phones and the FL agent system.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.02611v1">Privacy-Aware Data Acquisition under Data Similarity in Regression
  Markets</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB">
  <p><b>Published on:</b> 2023-12-05T09:39:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shashi Raj Pandey, Pierre Pinson, Petar Popovski</p>
    <p><b>Summary:</b> Data markets facilitate decentralized data exchange for applications such as
prediction, learning, or inference. The design of these markets is challenged
by varying privacy preferences as well as data similarity among data owners.
Related works have often overlooked how data similarity impacts pricing and
data value through statistical information leakage. We demonstrate that data
similarity and privacy preferences are integral to market design and propose a
query-response protocol using local differential privacy for a two-party data
acquisition mechanism. In our regression data market model, we analyze
strategic interactions between privacy-aware owners and the learner as a
Stackelberg game over the asked price and privacy factor. Finally, we
numerically evaluate how data similarity affects market participation and
traded data value.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.02400v1">Auto DP-SGD: Dual Improvements of Privacy and Accuracy via Automatic
  Clipping Threshold and Noise Multiplier Estimation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2023-12-05T00:09:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sai Venkatesh Chilukoti, Md Imran Hossen, Liqun Shan, Vijay Srinivas Tida, Xiai Hei</p>
    <p><b>Summary:</b> DP-SGD has emerged as a popular method to protect personally identifiable
information in deep learning applications. Unfortunately, DP-SGD's per-sample
gradient clipping and uniform noise addition during training can significantly
degrade model utility. To enhance the model's utility, researchers proposed
various adaptive DP-SGD methods. However, we examine and discover that these
techniques result in greater privacy leakage or lower accuracy than the
traditional DP-SGD method, or a lack of evaluation on a complex data set such
as CIFAR100. To address these limitations, we propose an Auto DP-SGD. Our
method automates clipping threshold estimation based on the DL model's gradient
norm and scales the gradients of each training sample without losing gradient
information. This helps to improve the algorithm's utility while using a less
privacy budget. To further improve accuracy, we introduce automatic noise
multiplier decay mechanisms to decrease the noise multiplier after every epoch.
Finally, we develop closed-form mathematical expressions using tCDP accountant
for automatic noise multiplier and automatic clipping threshold estimation.
Through extensive experimentation, we demonstrate that Auto DP-SGD outperforms
existing SOTA DP-SGD methods in privacy and accuracy on various benchmark
datasets. We also show that privacy can be improved by lowering the scale
factor and using learning rate schedulers without significantly reducing
accuracy. Specifically, Auto DP-SGD, when used with a step noise multiplier,
improves accuracy by 3.20, 1.57, 6.73, and 1.42 for the MNIST, CIFAR10,
CIFAR100, and AG News Corpus datasets, respectively. Furthermore, it obtains a
substantial reduction in the privacy budget of 94.9, 79.16, 67.36, and 53.37
for the corresponding data sets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.02327v1">FLea: Improving federated learning on scarce and label-skewed data via
  privacy-preserving feature augmentation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2023-12-04T20:24:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tong Xia, Abhirup Ghosh, Cecilia Mascolo</p>
    <p><b>Summary:</b> Learning a global model by abstracting the knowledge, distributed across
multiple clients, without aggregating the raw data is the primary goal of
Federated Learning (FL). Typically, this works in rounds alternating between
parallel local training at several clients, followed by model aggregation at a
server. We found that existing FL methods under-perform when local datasets are
small and present severe label skew as these lead to over-fitting and local
model bias. This is a realistic setting in many real-world applications. To
address the problem, we propose \textit{FLea}, a unified framework that tackles
over-fitting and local bias by encouraging clients to exchange
privacy-protected features to aid local training. The features refer to
activations from an intermediate layer of the model, which are obfuscated
before being shared with other clients to protect sensitive information in the
data. \textit{FLea} leverages a novel way of combining local and shared
features as augmentations to enhance local model learning. Our extensive
experiments demonstrate that \textit{FLea} outperforms the start-of-the-art FL
methods, sharing only model parameters, by up to $17.6\%$, and FL methods that
share data augmentations by up to $6.3\%$, while reducing the privacy
vulnerability associated with shared data augmentations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.02112v1">Distributed Optimization with Feasible Set Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">  
  <p><b>Published on:</b> 2023-12-04T18:45:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shreya Meel, Sennur Ulukus</p>
    <p><b>Summary:</b> We consider the setup of a constrained optimization problem with two agents
$E_1$ and $E_2$ who jointly wish to learn the optimal solution set while
keeping their feasible sets $\mathcal{P}_1$ and $\mathcal{P}_2$ private from
each other. The objective function $f$ is globally known and each feasible set
is a collection of points from a global alphabet. We adopt a sequential
symmetric private information retrieval (SPIR) framework where one of the
agents (say $E_1$) privately checks in $\mathcal{P}_2$, the presence of
candidate solutions of the problem constrained to $\mathcal{P}_1$ only, while
learning no further information on $\mathcal{P}_2$ than the solution alone.
Further, we extract an information theoretically private threshold PSI (ThPSI)
protocol from our scheme and characterize its download cost. We show that,
compared to privately acquiring the feasible set $\mathcal{P}_1\cap
\mathcal{P}_2$ using an SPIR-based private set intersection (PSI) protocol, and
finding the optimum, our scheme is better as it incurs less information leakage
and less download cost than the former. Over all possible uniform mappings of
$f$ to a fixed range of values, our scheme outperforms the former with a high
probability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.02093v1">Cultural Differences in Students' Privacy Concerns in Learning Analytics
  across Germany, South Korea, Spain, Sweden, and the United States</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2023-12-04T18:10:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Olga Viberg, René F. Kizilcec, Ioana Jivet, Alejandra Martínez Monés, Alice Oh, Chantal Mutimukwe, Stefan Hrastinski, Maren Scheffel</p>
    <p><b>Summary:</b> Applications of learning analytics (LA) can raise concerns from students
about their privacy in higher education contexts. Developing effective
privacy-enhancing practices requires a systematic understanding of students'
privacy concerns and how they vary across national and cultural dimensions. We
conducted a survey study with established instruments to measure privacy
concerns and cultural values for university students in five countries
(Germany, South Korea, Spain, Sweden, and the United States; N = 762). The
results show that students generally trusted institutions with their data and
disclosed information as they perceived the risks to be manageable even though
they felt somewhat limited in their ability to control their privacy. Across
the five countries, German and Swedish students stood out as the most trusting
and least concerned, especially compared to US students who reported greater
perceived risk and less control. Students in South Korea and Spain responded
similarly on all five privacy dimensions (perceived privacy risk, perceived
privacy control, privacy concerns, trusting beliefs, and non-self-disclosure
behavior), despite their significant cultural differences. Culture measured at
the individual level affected the antecedents and outcomes of privacy concerns
more than country-level culture. Perceived privacy risk and privacy control
increase with power distance. Trusting beliefs increase with a desire for
uncertainty avoidance and lower masculinity. Non-self-disclosure behaviors rise
with power distance and masculinity, and decrease with more uncertainty
avoidance. Thus, cultural values related to trust in institutions, social
equality and risk-taking should be considered when developing privacy-enhancing
practices and policies in higher education.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.02003v1">A Survey on Large Language Model (LLM) Security and Privacy: The Good,
  the Bad, and the Ugly</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2023-12-04T16:25:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yifan Yao, Jinhao Duan, Kaidi Xu, Yuanfang Cai, Eric Sun, Yue Zhang</p>
    <p><b>Summary:</b> Large Language Models (LLMs), such as GPT-3 and BERT, have revolutionized
natural language understanding and generation. They possess deep language
comprehension, human-like text generation capabilities, contextual awareness,
and robust problem-solving skills, making them invaluable in various domains
(e.g., search engines, customer support, translation). In the meantime, LLMs
have also gained traction in the security community, revealing security
vulnerabilities and showcasing their potential in security-related tasks. This
paper explores the intersection of LLMs with security and privacy.
Specifically, we investigate how LLMs positively impact security and privacy,
potential risks and threats associated with their use, and inherent
vulnerabilities within LLMs. Through a comprehensive literature review, the
paper categorizes findings into "The Good" (beneficial LLM applications), "The
Bad" (offensive applications), and "The Ugly" (vulnerabilities and their
defenses). We have some interesting findings. For example, LLMs have proven to
enhance code and data security, outperforming traditional methods. However,
they can also be harnessed for various attacks (particularly user-level
attacks) due to their human-like reasoning abilities. We have identified areas
that require further research efforts. For example, research on model and
parameter extraction attacks is limited and often theoretical, hindered by LLM
parameter scale and confidentiality. Safe instruction tuning, a recent
development, requires more exploration. We hope that our work can shed light on
the LLMs' potential to both bolster and jeopardize cybersecurity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.01201v1">PAC Privacy Preserving Diffusion Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2023-12-02T18:42:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qipan Xu, Youlong Ding, Jie Gao, Hao Wang</p>
    <p><b>Summary:</b> Data privacy protection is garnering increased attention among researchers.
Diffusion models (DMs), particularly with strict differential privacy, can
potentially produce images with both high privacy and visual quality. However,
challenges arise in ensuring robust protection in privatizing specific data
attributes, areas where current models often fall short. To address these
challenges, we introduce the PAC Privacy Preserving Diffusion Model, a model
leverages diffusion principles and ensure Probably Approximately Correct (PAC)
privacy. We enhance privacy protection by integrating a private classifier
guidance into the Langevin Sampling Process. Additionally, recognizing the gap
in measuring the privacy of models, we have developed a novel metric to gauge
privacy levels. Our model, assessed with this new metric and supported by
Gaussian matrix computations for the PAC bound, has shown superior performance
in privacy protection over existing leading private generative models according
to benchmark tests.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.01151v1">Here Is Not There: Measuring Entailment-Based Trajectory Similarity for
  Location-Privacy Protection and Beyond</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Symbolic Computation-5BC0EB">
  <p><b>Published on:</b> 2023-12-02T14:41:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zilong Liu, Krzysztof Janowicz, Kitty Currier, Meilin Shi, Jinmeng Rao, Song Gao, Ling Cai, Anita Graser</p>
    <p><b>Summary:</b> While the paths humans take play out in social as well as physical space,
measures to describe and compare their trajectories are carried out in
abstract, typically Euclidean, space. When these measures are applied to
trajectories of actual individuals in an application area, alterations that are
inconsequential in abstract space may suddenly become problematic once overlaid
with geographic reality. In this work, we present a different view on
trajectory similarity by introducing a measure that utilizes logical
entailment. This is an inferential perspective that considers facts as triple
statements deduced from the social and environmental context in which the
travel takes place, and their practical implications. We suggest a
formalization of entailment-based trajectory similarity, measured as the
overlapping proportion of facts, which are spatial relation statements in our
case study. With the proposed measure, we evaluate LSTM-TrajGAN, a
privacy-preserving trajectory-generation model. The entailment-based model
evaluation reveals potential consequences of disregarding the rich structure of
geographic space (e.g., miscalculated insurance risk due to regional shifts in
our toy example). Our work highlights the advantage of applying logical
entailment to trajectory-similarity reasoning for location-privacy protection
and beyond.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.01045v1">PROFL: A Privacy-Preserving Federated Learning Method with Stringent
  Defense Against Poisoning Attacks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2023-12-02T06:34:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yisheng Zhong, Li-Ping Wang</p>
    <p><b>Summary:</b> Federated Learning (FL) faces two major issues: privacy leakage and poisoning
attacks, which may seriously undermine the reliability and security of the
system. Overcoming them simultaneously poses a great challenge. This is because
privacy protection policies prohibit access to users' local gradients to avoid
privacy leakage, while Byzantine-robust methods necessitate access to these
gradients to defend against poisoning attacks. To address these problems, we
propose a novel privacy-preserving Byzantine-robust FL framework PROFL. PROFL
is based on the two-trapdoor additional homomorphic encryption algorithm and
blinding techniques to ensure the data privacy of the entire FL process. During
the defense process, PROFL first utilize secure Multi-Krum algorithm to remove
malicious gradients at the user level. Then, according to the Pauta criterion,
we innovatively propose a statistic-based privacy-preserving defense algorithm
to eliminate outlier interference at the feature level and resist impersonation
poisoning attacks with stronger concealment. Detailed theoretical analysis
proves the security and efficiency of the proposed method. We conducted
extensive experiments on two benchmark datasets, and PROFL improved accuracy by
39% to 75% across different attack settings compared to similar
privacy-preserving robust methods, demonstrating its significant advantage in
robustness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.00989v1">Scrappy: SeCure Rate Assuring Protocol with PrivacY</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-12-02T01:07:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kosei Akama, Yoshimichi Nakatsuka, Masaaki Sato, Keisuke Uehara</p>
    <p><b>Summary:</b> Preventing abusive activities caused by adversaries accessing online services
at a rate exceeding that expected by websites has become an ever-increasing
problem. CAPTCHAs and SMS authentication are widely used to provide a solution
by implementing rate limiting, although they are becoming less effective, and
some are considered privacy-invasive. In light of this, many studies have
proposed better rate-limiting systems that protect the privacy of legitimate
users while blocking malicious actors. However, they suffer from one or more
shortcomings: (1) assume trust in the underlying hardware and (2) are
vulnerable to side-channel attacks. Motivated by the aforementioned issues,
this paper proposes Scrappy: SeCure Rate Assuring Protocol with PrivacY.
Scrappy allows clients to generate unforgeable yet unlinkable rate-assuring
proofs, which provides the server with cryptographic guarantees that the client
is not misbehaving. We design Scrappy using a combination of DAA and hardware
security devices. Scrappy is implemented over three types of devices, including
one that can immediately be deployed in the real world. Our baseline evaluation
shows that the end-to-end latency of Scrappy is minimal, taking only 0.32
seconds, and uses only 679 bytes of bandwidth when transferring necessary data.
We also conduct an extensive security evaluation, showing that the
rate-limiting capability of Scrappy is unaffected even if the hardware security
device is compromised.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.00933v1">Privacy Preserving Event Detection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2023-12-01T21:25:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaoshan Wang, Tan F. Wong</p>
    <p><b>Summary:</b> This paper presents a privacy-preserving event detection scheme based on
measurements made by a network of sensors. A diameter-like decision statistic
made up of the marginal types of the measurements observed by the sensors is
employed. The proposed detection scheme can achieve the best type-I error
exponent as the type-II error rate is required to be negligible. Detection
performance with finite-length observations is also demonstrated through a
simulation example of spectrum sensing. Privacy protection is achieved by
obfuscating the type data with random zero-modulo-sum numbers that are
generated and distributed via the exchange of encrypted messages among the
sensors. The privacy-preserving performance against ``honest but curious''
adversaries, including colluding sensors, the fusion center, and external
eavesdroppers, is analyzed through a series of cryptographic games. It is shown
that the probability that any probabilistic polynomial time adversary
successfully estimates the sensors' measured types can not be much better than
independent guessing, when there are at least two non-colluding sensors.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.04579v1">zkFDL: An efficient and privacy-preserving decentralized federated
  learning with zero knowledge proof</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2023-12-01T17:00:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mojtaba Ahmadi, Reza Nourmohammadi</p>
    <p><b>Summary:</b> Federated leaning (FL) has been frequently used in various field of studies
and businesses. Traditional centralized FL systems suffer from serious issues.
To address these concerns, decentralized federated learning (DFL) systems have
been introduced in recent years in which with the help of blockchains, try to
achieve more integrity and efficiency. On the other hand, privacy-preserving is
an uncovered part of these systems. To address this, and also scaling the
blockchain-based computations, we propose a zero knowledge proof (ZKP) based
aggregator (zkDFL) that allows clients to share their large-scale model
parameters with a trusted centralized server without revealing their individual
data to other clients. We utilize blockchain technology to manage the
aggregation algorithm via smart contracts. The server performs a ZKP algorithm
to prove to the clients that the aggregation is done according to the accepted
algorithm. The server can also prove that all inputs of clients have been used.
We evaluate our measure through a public dataset about wearable internet of
things. As demonstrated by numerical evaluations, zkDFL introduces
verifiability of correctness of aggregation process and enhances the privacy
protection and scalability of DFL systems, while the gas cost has declined
significantly.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.00645v2">Hashmarks: Privacy-Preserving Benchmarks for High-Stakes AI Evaluation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2023-12-01T15:16:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Paul Bricman</p>
    <p><b>Summary:</b> There is a growing need to gain insight into language model capabilities that
relate to sensitive topics, such as bioterrorism or cyberwarfare. However,
traditional open source benchmarks are not fit for the task, due to the
associated practice of publishing the correct answers in human-readable form.
At the same time, enforcing mandatory closed-quarters evaluations might stifle
development and erode trust. In this context, we propose hashmarking, a
protocol for evaluating language models in the open without having to disclose
the correct answers. In its simplest form, a hashmark is a benchmark whose
reference solutions have been cryptographically hashed prior to publication.
Following an overview of the proposed evaluation protocol, we go on to assess
its resilience against traditional attack vectors (e.g. rainbow table attacks),
as well as against failure modes unique to increasingly capable generative
models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.00519v1">The Impact of Privacy and Security Attitudes and Concerns of Travellers
  on Their Willingness to Use Mobility-as-a-Service Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2023-12-01T11:51:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maria Sophia Heering, Haiyue Yuan, Shujun Li</p>
    <p><b>Summary:</b> This paper reports results from an online survey on the impact of travellers'
privacy and security attitudes and concerns on their willingness to use
mobility-as-a-service (MaaS) systems. This study is part of a larger project
that aims at investigating barriers to potential MaaS uptake. The online survey
was designed to cover data privacy and security attitudes and concerns as well
as a variety of socio-psychological and socio-demographic variables associated
with travellers' intentions to use MaaS systems. The study involved $n=320$ UK
participants recruited via the Prolific survey platform. Overall, correlation
analysis and a multiple regression model indicated that, neither attitudes nor
concerns of participants over the privacy and security of personal data would
significantly impact their decisions to use MaaS systems, which was an
unexpected result, however, their trust in (commercial and governmental)
websites would. Another surprising result is that, having been a victim of
improper invasion of privacy did not appear to affect individuals' intentions
to use MaaS systems, whereas frequency with which one heard about misuse of
personal data did. Implications of the results and future directions are also
discussed, e.g., MaaS providers are encouraged to work on improving the
trustworthiness of their corporate image.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2312.04577v1">The Evolution of DNS Security and Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2023-12-01T06:14:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Levente Csikor, Dinil Mon Divakaran</p>
    <p><b>Summary:</b> DNS, one of the fundamental protocols of the TCP/IP stack, has evolved over
the years to protect against threats and attacks. This study examines the risks
associated with DNS and explores recent advancements that contribute towards
making the DNS ecosystem resilient against various attacks while safeguarding
user privacy.</p>
  </details>
</div>



<h2>2023-11</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2311.18252v1">Navigating Privacy and Copyright Challenges Across the Data Lifecycle of
  Generative AI</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2023-11-30T05:03:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dawen Zhang, Boming Xia, Yue Liu, Xiwei Xu, Thong Hoang, Zhenchang Xing, Mark Staples, Qinghua Lu, Liming Zhu</p>
    <p><b>Summary:</b> The advent of Generative AI has marked a significant milestone in artificial
intelligence, demonstrating remarkable capabilities in generating realistic
images, texts, and data patterns. However, these advancements come with
heightened concerns over data privacy and copyright infringement, primarily due
to the reliance on vast datasets for model training. Traditional approaches
like differential privacy, machine unlearning, and data poisoning only offer
fragmented solutions to these complex issues. Our paper delves into the
multifaceted challenges of privacy and copyright protection within the data
lifecycle. We advocate for integrated approaches that combines technical
innovation with ethical foresight, holistically addressing these concerns by
investigating and devising solutions that are informed by the lifecycle
perspective. This work aims to catalyze a broader discussion and inspire
concerted efforts towards data privacy and copyright integrity in Generative
AI.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2311.18190v1">Toward the Tradeoffs between Privacy, Fairness and Utility in Federated
  Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2023-11-30T02:19:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kangkang Sun, Xiaojin Zhang, Xi Lin, Gaolei Li, Jing Wang, Jianhua Li</p>
    <p><b>Summary:</b> Federated Learning (FL) is a novel privacy-protection distributed machine
learning paradigm that guarantees user privacy and prevents the risk of data
leakage due to the advantage of the client's local training. Researchers have
struggled to design fair FL systems that ensure fairness of results. However,
the interplay between fairness and privacy has been less studied. Increasing
the fairness of FL systems can have an impact on user privacy, while an
increase in user privacy can affect fairness. In this work, on the client side,
we use fairness metrics, such as Demographic Parity (DemP), Equalized Odds
(EOs), and Disparate Impact (DI), to construct the local fair model. To protect
the privacy of the client model, we propose a privacy-protection fairness FL
method. The results show that the accuracy of the fair model with privacy
increases because privacy breaks the constraints of the fairness metrics. In
our experiments, we conclude the relationship between privacy, fairness and
utility, and there is a tradeoff between these.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2311.17789v1">The Symmetric alpha-Stable Privacy Mechanism</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2023-11-29T16:34:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Christopher Zawacki, Eyad Abed</p>
    <p><b>Summary:</b> With the rapid growth of digital platforms, there is increasing apprehension
about how personal data is being collected, stored, and used by various
entities. These concerns range from data breaches and cyber-attacks to
potential misuse of personal information for targeted advertising and
surveillance. As a result, differential privacy (DP) has emerged as a prominent
tool for quantifying a system's level of protection. The Gaussian mechanism is
commonly used because the Gaussian density is closed under convolution, a
common method utilized when aggregating datasets. However, the Gaussian
mechanism only satisfies approximate differential privacy. In this work, we
present novel analysis of the Symmetric alpha-Stable (SaS) mechanism. We prove
that the mechanism is purely differentially private while remaining closed
under convolution. From our analysis, we believe the SaS Mechanism is an
appealing choice for privacy focused applications.</p>
  </details>
</div>

