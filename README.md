
<h2>2024-07</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.08529v1">Enhancing Privacy of Spatiotemporal Federated Learning against Gradient
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


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.20088v1">Minimax And Adaptive Transfer Learning for Nonparametric Classification
  under Distributed Differential Privacy Constraints</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">    
  <p><b>Published on:</b> 2024-06-28T17:55:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arnab Auddy, T. Tony Cai, Abhinav Chakraborty</p>
    <p><b>Summary:</b> This paper considers minimax and adaptive transfer learning for nonparametric
classification under the posterior drift model with distributed differential
privacy constraints. Our study is conducted within a heterogeneous framework,
encompassing diverse sample sizes, varying privacy parameters, and data
heterogeneity across different servers. We first establish the minimax
misclassification rate, precisely characterizing the effects of privacy
constraints, source samples, and target samples on classification accuracy. The
results reveal interesting phase transition phenomena and highlight the
intricate trade-offs between preserving privacy and achieving classification
accuracy. We then develop a data-driven adaptive classifier that achieves the
optimal rate within a logarithmic factor across a large collection of parameter
spaces while satisfying the same set of differential privacy constraints.
Simulation studies and real-world data applications further elucidate the
theoretical analysis with numerical results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.19964v2">Secure Outsourced Decryption for FHE-based Privacy-preserving Cloud
  Computing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-28T14:51:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xirong Ma, Chuan Li, Yuchang Hu, Yunting Tao, Yali Jiang, Yanbin Li, Fanyu Kong, Chunpeng Ge</p>
    <p><b>Summary:</b> The demand for processing vast volumes of data has surged dramatically due to
the advancement of machine learning technology. Large-scale data processing
necessitates substantial computational resources, prompting individuals and
enterprises to turn to cloud services. Accompanying this trend is a growing
concern regarding data leakage and misuse. Homomorphic encryption (HE) is one
solution for safeguarding data privacy, enabling encrypted data to be processed
securely in the cloud. However, the encryption and decryption routines of some
HE schemes require considerable computational resources, presenting non-trivial
work for clients. In this paper, we propose an outsourced decryption protocol
for the prevailing RLWE-based fully homomorphic encryption schemes. The
protocol splits the original decryption into two routines, with the
computationally intensive part executed remotely by the cloud. Its security
relies on an invariant of the NTRU-search problem with a newly designed
blinding key distribution. Cryptographic analyses are conducted to configure
protocol parameters across varying security levels. Our experiments demonstrate
that the proposed protocol achieves up to a $67\%$ acceleration in the client's
local decryption, accompanied by a $50\%$ reduction in space usage.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.19642v1">IDT: Dual-Task Adversarial Attacks for Privacy Protection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-06-28T04:14:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pedro Faustini, Shakila Mahjabin Tonni, Annabelle McIver, Qiongkai Xu, Mark Dras</p>
    <p><b>Summary:</b> Natural language processing (NLP) models may leak private information in
different ways, including membership inference, reconstruction or attribute
inference attacks. Sensitive information may not be explicit in the text, but
hidden in underlying writing characteristics. Methods to protect privacy can
involve using representations inside models that are demonstrated not to detect
sensitive attributes or -- for instance, in cases where users might not trust a
model, the sort of scenario of interest here -- changing the raw text before
models can have access to it. The goal is to rewrite text to prevent someone
from inferring a sensitive attribute (e.g. the gender of the author, or their
location by the writing style) whilst keeping the text useful for its original
intention (e.g. the sentiment of a product review). The few works tackling this
have focused on generative techniques. However, these often create extensively
different texts from the original ones or face problems such as mode collapse.
This paper explores a novel adaptation of adversarial attack techniques to
manipulate a text to deceive a classifier w.r.t one task (privacy) whilst
keeping the predictions of another classifier trained for another task
(utility) unchanged. We propose IDT, a method that analyses predictions made by
auxiliary and interpretable models to identify which tokens are important to
change for the privacy task, and which ones should be kept for the utility
task. We evaluate different datasets for NLP suitable for different tasks.
Automatic and human evaluations show that IDT retains the utility of text,
while also outperforming existing methods when deceiving a classifier w.r.t
privacy task.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.19035v3">SD-BLS: Privacy Preserving Selective Disclosure of Verifiable
  Credentials with Unlinkable Threshold Revocation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-27T09:41:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Denis Roio, Rebecca Selvaggini, Gabriele Bellini, Andrea D'Intino</p>
    <p><b>Summary:</b> Ensuring privacy and protection from issuer corruption in digital identity
systems is crucial. We propose a method for selective disclosure and
privacy-preserving revocation of digital credentials using second-order
Elliptic Curves and Boneh-Lynn-Shacham (BLS) signatures. We make holders able
to present proofs of possession of selected credentials without disclosing
them, and we protect their presentations from replay attacks. Revocations may
be distributed among multiple revocation issuers using publicly verifiable
secret sharing (PVSS) and activated only by configurable consensus, ensuring
robust protection against issuer corruption. Our system's unique design enables
extremely fast revocation checks, even with large revocation lists, leveraging
optimized hash map lookups.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.18940v1">Efficient Verifiable Differential Privacy with Input Authenticity in the
  Local and Shuffle Model</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-27T07:12:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tariq Bontekoe, Hassan Jameel Asghar, Fatih Turkmen</p>
    <p><b>Summary:</b> Local differential privacy (LDP) is an efficient solution for providing
privacy to client's sensitive data while simultaneously releasing aggregate
statistics without relying on a trusted central server (aggregator) as in the
central model of differential privacy. The shuffle model with LDP provides an
additional layer of privacy, by disconnecting the link between clients and the
aggregator, further improving the utility of LDP. However, LDP has been shown
to be vulnerable to malicious clients who can perform both input and output
manipulation attacks, i.e., before and after applying the LDP mechanism, to
skew the aggregator's results. In this work, we show how to prevent malicious
clients from compromising LDP schemes. Specifically, we give efficient
constructions to prevent both input \'and output manipulation attacks from
malicious clients for generic LDP algorithms. Our proposed schemes for
verifiable LDP (VLDP), completely protect from output manipulation attacks, and
prevent input attacks using signed data, requiring only one-time interaction
between client and server, unlike existing alternatives [28, 33]. Most
importantly, we are the first to provide an efficient scheme for VLDP in the
shuffle model. We describe and prove secure, two schemes for VLDP in the
regular model, and one in the shuffle model. We show that all schemes are
highly practical, with client runtimes of < 2 seconds, and server runtimes of
5-7 milliseconds per client.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.18812v1">A Survey on Privacy Attacks Against Digital Twin Systems in AI-Robotics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-06-27T00:59:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ivan A. Fernandez, Subash Neupane, Trisha Chakraborty, Shaswata Mitra, Sudip Mittal, Nisha Pillai, Jingdao Chen, Shahram Rahimi</p>
    <p><b>Summary:</b> Industry 4.0 has witnessed the rise of complex robots fueled by the
integration of Artificial Intelligence/Machine Learning (AI/ML) and Digital
Twin (DT) technologies. While these technologies offer numerous benefits, they
also introduce potential privacy and security risks. This paper surveys privacy
attacks targeting robots enabled by AI and DT models. Exfiltration and data
leakage of ML models are discussed in addition to the potential extraction of
models derived from first-principles (e.g., physics-based). We also discuss
design considerations with DT-integrated robotics touching on the impact of ML
model training, responsible AI and DT safeguards, data governance and ethical
considerations on the effectiveness of these attacks. We advocate for a trusted
autonomy approach, emphasizing the need to combine robotics, AI, and DT
technologies with robust ethical frameworks and trustworthiness principles for
secure and reliable AI robotic systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.18731v1">WavRx: a Disease-Agnostic, Generalizable, and Privacy-Preserving Speech
  Health Diagnostic Model</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-06-26T19:59:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yi Zhu, Tiago Falk</p>
    <p><b>Summary:</b> Speech is known to carry health-related attributes, which has emerged as a
novel venue for remote and long-term health monitoring. However, existing
models are usually tailored for a specific type of disease, and have been shown
to lack generalizability across datasets. Furthermore, concerns have been
raised recently towards the leakage of speaker identity from health embeddings.
To mitigate these limitations, we propose WavRx, a speech health diagnostics
model that captures the respiration and articulation related dynamics from a
universal speech representation. Our in-domain and cross-domain experiments on
six pathological speech datasets demonstrate WavRx as a new state-of-the-art
health diagnostic model. Furthermore, we show that the amount of speaker
identity entailed in the WavRx health embeddings is significantly reduced
without extra guidance during training. An in-depth analysis of the model was
performed, thus providing physiological interpretation of its improved
generalizability and privacy-preserving ability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.18491v1">Enhancing Federated Learning with Adaptive Differential Privacy and
  Priority-Based Aggregation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-06-26T16:55:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mahtab Talaei, Iman Izadi</p>
    <p><b>Summary:</b> Federated learning (FL), a novel branch of distributed machine learning (ML),
develops global models through a private procedure without direct access to
local datasets. However, it is still possible to access the model updates
(gradient updates of deep neural networks) transferred between clients and
servers, potentially revealing sensitive local information to adversaries using
model inversion attacks. Differential privacy (DP) offers a promising approach
to addressing this issue by adding noise to the parameters. On the other hand,
heterogeneities in data structure, storage, communication, and computational
capabilities of devices can cause convergence problems and delays in developing
the global model. A personalized weighted averaging of local parameters based
on the resources of each device can yield a better aggregated model in each
round. In this paper, to efficiently preserve privacy, we propose a
personalized DP framework that injects noise based on clients' relative impact
factors and aggregates parameters while considering heterogeneities and
adjusting properties. To fulfill the DP requirements, we first analyze the
convergence boundary of the FL algorithm when impact factors are personalized
and fixed throughout the learning process. We then further study the
convergence property considering time-varying (adaptive) impact factors.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.19418v1">A Quantization-based Technique for Privacy Preserving Distributed
  Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-06-26T14:54:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maurizio Colombo, Rasool Asal, Ernesto Damiani, Lamees Mahmoud AlQassem, Al Anoud Almemari, Yousof Alhammadi</p>
    <p><b>Summary:</b> The massive deployment of Machine Learning (ML) models raises serious
concerns about data protection. Privacy-enhancing technologies (PETs) offer a
promising first step, but hard challenges persist in achieving confidentiality
and differential privacy in distributed learning. In this paper, we describe a
novel, regulation-compliant data protection technique for the distributed
training of ML models, applicable throughout the ML life cycle regardless of
the underlying ML architecture. Designed from the data owner's perspective, our
method protects both training data and ML model parameters by employing a
protocol based on a quantized multi-hash data representation Hash-Comb combined
with randomization. The hyper-parameters of our scheme can be shared using
standard Secure Multi-Party computation protocols. Our experimental results
demonstrate the robustness and accuracy-preserving properties of our approach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.18221v1">Enhancing Data Privacy in Large Language Models through Private
  Association Editing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-06-26T10:08:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Davide Venditti, Elena Sofia Ruzzetti, Giancarlo A. Xompero, Cristina Giannone, Andrea Favalli, Raniero Romagnoli, Fabio Massimo Zanzotto</p>
    <p><b>Summary:</b> Large Language Models (LLMs) are powerful tools with extensive applications,
but their tendency to memorize private information raises significant concerns
as private data leakage can easily happen. In this paper, we introduce Private
Association Editing (PAE), a novel defense approach for private data leakage.
PAE is designed to effectively remove Personally Identifiable Information (PII)
without retraining the model. Our approach consists of a four-step procedure:
detecting memorized PII, applying PAE cards to mitigate memorization of private
data, verifying resilience to targeted data extraction (TDE) attacks, and
ensuring consistency in the post-edit LLMs. The versatility and efficiency of
PAE, which allows for batch modifications, significantly enhance data privacy
in LLMs. Experimental results demonstrate the effectiveness of PAE in
mitigating private data leakage. We believe PAE will serve as a critical tool
in the ongoing effort to protect data privacy in LLMs, encouraging the
development of safer models for real-world applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.18100v1">Natural Language but Omitted? On the Ineffectiveness of Large Language
  Models' privacy policy from End-users' Perspective</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-06-26T06:31:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuning Zhang, Haobin Xing, Xin Yi, Hewu Li</p>
    <p><b>Summary:</b> LLMs driven products were increasingly prevalent in our daily lives, With a
natural language based interaction style, people may potentially leak their
personal private information. Thus, privacy policy and user agreement played an
important role in regulating and alerting people. However, there lacked the
work examining the reading of LLM's privacy policy. Thus, we conducted the
first user study to let participants read the privacy policy and user agreement
with two different styles (a cursory and detailed style). We found users lack
important information upon cursory reading and even detailed reading. Besides,
their privacy concerns was not solved even upon detailed reading. We provided
four design implications based on the findings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.17649v1">Privacy Preserving Reinforcement Learning for Population Processes</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-25T15:41:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Samuel Yang-Zhao, Kee Siong Ng</p>
    <p><b>Summary:</b> We consider the problem of privacy protection in Reinforcement Learning (RL)
algorithms that operate over population processes, a practical but understudied
setting that includes, for example, the control of epidemics in large
populations of dynamically interacting individuals. In this setting, the RL
algorithm interacts with the population over $T$ time steps by receiving
population-level statistics as state and performing actions which can affect
the entire population at each time step. An individual's data can be collected
across multiple interactions and their privacy must be protected at all times.
We clarify the Bayesian semantics of Differential Privacy (DP) in the presence
of correlated data in population processes through a Pufferfish Privacy
analysis. We then give a meta algorithm that can take any RL algorithm as input
and make it differentially private. This is achieved by taking an approach that
uses DP mechanisms to privatize the state and reward signal at each time step
before the RL algorithm receives them as input. Our main theoretical result
shows that the value-function approximation error when applying standard RL
algorithms directly to the privatized states shrinks quickly as the population
size and privacy budget increase. This highlights that reasonable
privacy-utility trade-offs are possible for differentially private RL
algorithms in population processes. Our theoretical findings are validated by
experiments performed on a simulated epidemic control problem over large
population sizes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.16826v1">Practical privacy metrics for synthetic data</a></h3>
  
  <p><b>Published on:</b> 2024-06-24T17:35:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gillian M Raab, Beata Nowok, Chris Dibben</p>
    <p><b>Summary:</b> This paper explains how the synthpop package for R has been extended to
include functions to calculate measures of identity and attribute disclosure
risk for synthetic data that measure risks for the records used to create the
synthetic data. The basic function, disclosure, calculates identity disclosure
for a set of quasi-identifiers (keys) and attribute disclosure for one variable
specified as a target from the same set of keys. The second function,
disclosure.summary, is a wrapper for the first and presents summary results for
a set of targets. This short paper explains the measures of disclosure risk and
documents how they are calculated. We recommend two measures: $RepU$
(replicated uniques) for identity disclosure and $DiSCO$ (Disclosive in
Synthetic Correct Original) for attribute disclosure. Both are expressed a \%
of the original records and each can be compared to similar measures calculated
from the original data. Experience with using the functions on real data found
that some apparent disclosures could be identified as coming from relationships
in the data that would be expected to be known to anyone familiar with its
features. We flag cases when this seems to have occurred and provide means of
excluding them.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.16456v1">Automated Privacy-Preserving Techniques via Meta-Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-24T08:53:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tânia Carvalho, Nuno Moniz, Luís Antunes</p>
    <p><b>Summary:</b> Sharing private data for learning tasks is pivotal for transparent and secure
machine learning applications. Many privacy-preserving techniques have been
proposed for this task aiming to transform the data while ensuring the privacy
of individuals. Some of these techniques have been incorporated into tools,
whereas others are accessed through various online platforms. However, such
tools require manual configuration, which can be complex and time-consuming.
Moreover, they require substantial expertise, potentially restricting their use
to those with advanced technical knowledge. In this paper, we propose AUTOPRIV,
the first automated privacy-preservation method, that eliminates the need for
any manual configuration. AUTOPRIV employs meta-learning to automate the
de-identification process, facilitating the secure release of data for machine
learning tasks. The main goal is to anticipate the predictive performance and
privacy risk of a large set of privacy configurations. We provide a ranked list
of the most promising solutions, which are likely to achieve an optimal
approximation within a new domain. AUTOPRIV is highly effective as it reduces
computational complexity and energy consumption considerably.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.16313v1">Thinking Inside The Box: Privacy Against Stronger Adversaries</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-24T04:40:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Eldon Chung</p>
    <p><b>Summary:</b> In this thesis, we study extensions of statistical cryptographic primitives.
In particular we study leakage-resilient secret sharing, non-malleable
extractors, and immunized ideal one-way functions. The thesis is divided into
three main chapters. In the first chapter, we show that 2-out-of-2 leakage
resilient (and also non-malleable) secret sharing requires randomness sources
that are also extractable. This rules out the possibility of using min-entropic
sources. In the second, we introduce collision-resistant seeded extractors and
show that any seeded extractor can be made collision resistant at a small
overhead in seed length. We then use it to give a two-source non-malleable
extractor with entropy rate 0.81 in one source and polylogarithmic in the
other. The non-malleable extractor lead to the first statistical privacy
amplification protocol against memory tampering adversaries. In the final
chapter, we study the hardness of the data structure variant of the 3SUM
problem which is motivated by a recent construction to immunise random oracles
against pre-processing adversaries. We give worst-case data structure hardness
for the 3SUM problem matching known barriers in data structures for adaptive
adversaries. We also give a slightly stronger lower bound in the case of
non-adaptivity. Lastly, we give a novel result in the bit-probe setting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.16305v1">On Computing Pairwise Statistics with Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-24T04:06:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Badih Ghazi, Pritish Kamath, Ravi Kumar, Pasin Manurangsi, Adam Sealfon</p>
    <p><b>Summary:</b> We study the problem of computing pairwise statistics, i.e., ones of the form
$\binom{n}{2}^{-1} \sum_{i \ne j} f(x_i, x_j)$, where $x_i$ denotes the input
to the $i$th user, with differential privacy (DP) in the local model. This
formulation captures important metrics such as Kendall's $\tau$ coefficient,
Area Under Curve, Gini's mean difference, Gini's entropy, etc. We give several
novel and generic algorithms for the problem, leveraging techniques from DP
algorithms for linear queries.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.16182v1">Privacy-Preserving and Trustworthy Localization in an IoT Environment</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-06-23T18:13:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guglielmo Zocca, Omar Hasan</p>
    <p><b>Summary:</b> The Internet of Things (IoT) is increasingly prevalent in various
applications, such as healthcare and logistics. One significant service of IoT
technologies that is essential for these applications is localization. The goal
of this service is to determine the precise position of a specific target. The
localization data often needs to be private, accessible only to specific
entities, and must maintain authenticity and integrity to ensure
trustworthiness. IoT technology has evolved significantly, with Ultra-Wide Band
(UWB) technology enhancing localization speed and precision. However, IoT
device security remains a concern, as devices can be compromised or act
maliciously. Furthermore, localization data is typically stored centrally,
which can also be a point of vulnerability. Our approach leverages the features
of a permissioned blockchain, specifically Hyperledger Fabric, to address these
challenges. Hyperledger Fabric's collection feature ensures data privacy, and
its smart contracts (chaincode) enhance trustworthiness. We tested our solution
using a network of devices known as CLOVES, demonstrating robust performance
characteristics with UWB technology. Additionally, we evaluated our approach
through an indoor localization use case.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.15962v1">Privacy Preserving Machine Learning for Electronic Health Records using
  Federated Learning and Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2024-06-23T00:01:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Naif A. Ganadily, Han J. Xia</p>
    <p><b>Summary:</b> An Electronic Health Record (EHR) is an electronic database used by
healthcare providers to store patients' medical records which may include
diagnoses, treatments, costs, and other personal information. Machine learning
(ML) algorithms can be used to extract and analyze patient data to improve
patient care. Patient records contain highly sensitive information, such as
social security numbers (SSNs) and residential addresses, which introduces a
need to apply privacy-preserving techniques for these ML models using federated
learning and differential privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.15842v1">Privacy Requirements and Realities of Digital Public Goods</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-06-22T13:06:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Geetika Gopi, Aadyaa Maddi, Omkhar Arasaratnam, Giulia Fanti</p>
    <p><b>Summary:</b> In the international development community, the term "digital public goods"
is used to describe open-source digital products (e.g., software, datasets)
that aim to address the United Nations (UN) Sustainable Development Goals. DPGs
are increasingly being used to deliver government services around the world
(e.g., ID management, healthcare registration). Because DPGs may handle
sensitive data, the UN has established user privacy as a first-order
requirement for DPGs. The privacy risks of DPGs are currently managed in part
by the DPG standard, which includes a prerequisite questionnaire with questions
designed to evaluate a DPG's privacy posture.
  This study examines the effectiveness of the current DPG standard for
ensuring adequate privacy protections. We present a systematic assessment of
responses from DPGs regarding their protections of users' privacy. We also
present in-depth case studies from three widely-used DPGs to identify privacy
threats and compare this to their responses to the DPG standard. Our findings
reveal limitations in the current DPG standard's evaluation approach. We
conclude by presenting preliminary recommendations and suggestions for
strengthening the DPG standard as it relates to privacy. Additionally, we hope
this study encourages more usable privacy research on communicating privacy,
not only to end users but also third-party adopters of user-facing
technologies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.15789v1">Privacy Implications of Explainable AI in Data-Driven Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-22T08:51:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fatima Ezzeddine</p>
    <p><b>Summary:</b> Machine learning (ML) models, demonstrably powerful, suffer from a lack of
interpretability. The absence of transparency, often referred to as the black
box nature of ML models, undermines trust and urges the need for efforts to
enhance their explainability. Explainable AI (XAI) techniques address this
challenge by providing frameworks and methods to explain the internal
decision-making processes of these complex models. Techniques like
Counterfactual Explanations (CF) and Feature Importance play a crucial role in
achieving this goal. Furthermore, high-quality and diverse data remains the
foundational element for robust and trustworthy ML applications. In many
applications, the data used to train ML and XAI explainers contain sensitive
information. In this context, numerous privacy-preserving techniques can be
employed to safeguard sensitive information in the data, such as differential
privacy. Subsequently, a conflict between XAI and privacy solutions emerges due
to their opposing goals. Since XAI techniques provide reasoning for the model
behavior, they reveal information relative to ML models, such as their decision
boundaries, the values of features, or the gradients of deep learning models
when explanations are exposed to a third entity. Attackers can initiate privacy
breaching attacks using these explanations, to perform model extraction,
inference, and membership attacks. This dilemma underscores the challenge of
finding the right equilibrium between understanding ML decision-making and
safeguarding privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.15655v1">ProBE: Proportioning Privacy Budget for Complex Exploratory Decision
  Support</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2024-06-21T21:20:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nada Lahjouji, Sameera Ghayyur, Xi He, Sharad Mehrotra</p>
    <p><b>Summary:</b> This paper studies privacy in the context of complex decision support queries
composed of multiple conditions on different aggregate statistics combined
using disjunction and conjunction operators. Utility requirements for such
queries necessitate the need for private mechanisms that guarantee a bound on
the false negative and false positive errors. This paper formally defines
complex decision support queries and their accuracy requirements, and provides
algorithms that proportion the existing budget to optimally minimize privacy
loss while supporting a bounded guarantee on the accuracy. Our experimental
results on multiple real-life datasets show that our algorithms successfully
maintain such utility guarantees, while also minimizing privacy loss.</p>
  </details>
</div>


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
  <h3><a href="http://arxiv.org/abs/2406.14322v2">Mind the Privacy Unit! User-Level Differential Privacy for Language
  Model Fine-Tuning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-06-20T13:54:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lynn Chua, Badih Ghazi, Yangsibo Huang, Pritish Kamath, Ravi Kumar, Daogao Liu, Pasin Manurangsi, Amer Sinha, Chiyuan Zhang</p>
    <p><b>Summary:</b> Large language models (LLMs) have emerged as powerful tools for tackling
complex tasks across diverse domains, but they also raise privacy concerns when
fine-tuned on sensitive data due to potential memorization. While differential
privacy (DP) offers a promising solution by ensuring models are 'almost
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
  <h3><a href="http://arxiv.org/abs/2406.12457v2">Data Trade and Consumer Privacy</a></h3>
  
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
  <h3><a href="http://arxiv.org/abs/2406.12003v2">P3GNN: A Privacy-Preserving Provenance Graph-Based Model for APT
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
  <h3><a href="http://arxiv.org/abs/2406.11323v2">Transparency, Privacy, and Fairness in Recommender Systems</a></h3>
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
  <h3><a href="http://arxiv.org/abs/2406.10563v2">Privacy-Preserving Heterogeneous Federated Learning for Sensitive
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
  <h3><a href="http://arxiv.org/abs/2406.08918v2">Beyond the Calibration Point: Mechanism Comparison in Differential
  Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">  
  <p><b>Published on:</b> 2024-06-13T08:30:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Georgios Kaissis, Stefan Kolek, Borja Balle, Jamie Hayes, Daniel Rueckert</p>
    <p><b>Summary:</b> In differentially private (DP) machine learning, the privacy guarantees of DP
mechanisms are often reported and compared on the basis of a single
$(\varepsilon, \delta)$-pair. This practice overlooks that DP guarantees can
vary substantially even between mechanisms sharing a given $(\varepsilon,
\delta)$, and potentially introduces privacy vulnerabilities which can remain
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

