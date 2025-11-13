
<h2>2016-12</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1612.01553v1">Privacy Patterns</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2016-12-05T21:19:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Clark Thomborson</p>
    <p><b>Summary:</b> Inspired by the design patterns of object-oriented software architecture, we offer an initial set of "privacy patterns". Our intent is to describe the most important ways in which software systems can offer privacy to their stakeholders. We express our privacy patterns as class diagrams in the UML (Universal Modelling Language), because this is a commonly-used language for expressing the high-level architecture of an object-oriented system. In this initial set of privacy patterns, we sketch how each of Westin's four states of privacy can be implemented in a software system. In addition to Westin's states of Solitude, Intimacy, Anonymity, and Reserve, we develop a privacy pattern for an institutionalised form of Intimacy which we call Confidence.</p>
  </details>
</div>



<h2>2023-03</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2303.08213v2">The Overview of Privacy Labels and their Compatibility with Privacy Policies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2023-03-14T20:10:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rishabh Khandelwal, Asmit Nayak, Paul Chung, Kassem Fawaz</p>
    <p><b>Summary:</b> Privacy nutrition labels provide a way to understand an app's key data practices without reading the long and hard-to-read privacy policies. Recently, the app distribution platforms for iOS(Apple) and Android(Google) have implemented mandates requiring app developers to fill privacy nutrition labels highlighting their privacy practices such as data collection, data sharing, and security practices. These privacy labels contain very fine-grained information about the apps' data practices such as the data types and purposes associated with each data type. This provides us with a unique vantage point from which we can understand apps' data practices at scale.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2303.01017v1">On the Lift, Related Privacy Measures, and Applications to Privacy-Utility Tradeoffs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2023-03-02T07:10:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohammad Amin Zarrabian, Ni Ding, Parastoo Sadeghi</p>
    <p><b>Summary:</b> This paper investigates lift, the likelihood ratio between the posterior and prior belief about sensitive features in a dataset. Maximum and minimum lifts over sensitive features quantify the adversary's knowledge gain and should be bounded to protect privacy. We demonstrate that max and min lifts have a distinct range of values and probability of appearance in the dataset, referred to as \emph{lift asymmetry}. We propose asymmetric local information privacy (ALIP) as a compatible privacy notion with lift asymmetry, where different bounds can be applied to min and max lifts. We use ALIP in the watchdog and optimal random response (ORR) mechanisms, the main methods to achieve lift-based privacy. It is shown that ALIP enhances utility in these methods compared to existing local information privacy, which ensures the same (symmetric) bounds on both max and min lifts. We propose subset merging for the watchdog mechanism to improve data utility and subset random response for the ORR to reduce complexity. We then investigate the related lift-based measures, including $\ell_1$-norm, $χ^2$-privacy criterion, and $α$-lift. We reveal that they can only restrict max-lift, resulting in significant min-lift leakage. To overcome this problem, we propose corresponding lift-inverse measures to restrict the min-lift. We apply these lift-based and lift-inverse measures in the watchdog mechanism. We show that they can be considered as relaxations of ALIP, where a higher utility can be achieved by bounding only average max and min lifts.</p>
  </details>
</div>



<h2>2010-01</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1001.4459v1">The Privacy Coach: Supporting customer privacy in the Internet of Things</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2010-01-25T15:25:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gerben Broenink, Jaap-Henk Hoepman, Christian van 't Hof, Rob van Kranenburg, David Smits, Tijmen Wisman</p>
    <p><b>Summary:</b> The Privacy Coach is an application running on a mobile phone that supports customers in making privacy decisions when confronted with RFID tags. The approach we take to increase customer privacy is a radical departure from the mainstream research efforts that focus on implementing privacy enhancing technologies on the RFID tags themselves. Instead the Privacy Coach functions as a mediator between customer privacy preferences and corporate privacy policies, trying to find a match between the two, and informing the user of the outcome. In this paper we report on the architecture of the Privacy Coach, and show how it enables users to make informed privacy decisions in a user-friendly manner. We also spend considerable time to discuss lessons learnt and to describe future plans to further improve on the Privacy Coach concept.</p>
  </details>
</div>



<h2>2023-04</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2304.01689v1">Privacy-Preserving Federated Discovery of DNA Motifs with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-04-04T10:37:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yao Chen, Wensheng Gan, Gengsen Huang, Yongdong Wu, Philip S. Yu</p>
    <p><b>Summary:</b> DNA motif discovery is an important issue in gene research, which aims to identify transcription factor binding sites (i.e., motifs) in DNA sequences to reveal the mechanisms that regulate gene expression. However, the phenomenon of data silos and the problem of privacy leakage have seriously hindered the development of DNA motif discovery. On the one hand, the phenomenon of data silos makes data collection difficult. On the other hand, the collection and use of DNA data become complicated and difficult because DNA is sensitive private information. In this context, how discovering DNA motifs under the premise of ensuring privacy and security and alleviating data silos has become a very important issue. Therefore, this paper proposes a novel method, namely DP-FLMD, to address this problem. Note that this is the first application of federated learning to the field of genetics research. The federated learning technique is used to solve the problem of data silos. It has the advantage of enabling multiple participants to train models together and providing privacy protection services. To address the challenges of federated learning in terms of communication costs, this paper applies a sampling method and a strategy for reducing communication costs to DP-FLMD. In addition, differential privacy, a privacy protection technique with rigorous mathematical proof, is also applied to DP-FLMD. Experiments on the DNA datasets show that DP-FLMD has high mining accuracy and runtime efficiency, and the performance of the algorithm is affected by some parameters.</p>
  </details>
</div>



<h2>2018-06</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1806.04819v5">Integral Privacy for Sampling</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2018-06-13T02:01:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hisham Husain, Zac Cranko, Richard Nock</p>
    <p><b>Summary:</b> Differential privacy is a leading protection setting, focused by design on individual privacy. Many applications, in medical / pharmaceutical domains or social networks, rather posit privacy at a group level, a setting we call integral privacy. We aim for the strongest form of privacy: the group size is in particular not known in advance. We study a problem with related applications in domains cited above that have recently met with substantial recent press: sampling.
  Keeping correct utility levels in such a strong model of statistical indistinguishability looks difficult to be achieved with the usual differential privacy toolbox because it would typically scale in the worst case the sensitivity by the sample size and so the noise variance by up to its square. We introduce a trick specific to sampling that bypasses the sensitivity analysis. Privacy enforces an information theoretic barrier on approximation, and we show how to reach this barrier with guarantees on the approximation of the target non private density. We do so using a recent approach to non private density estimation relying on the original boosting theory, learning the sufficient statistics of an exponential family with classifiers. Approximation guarantees cover the mode capture problem. In the context of learning, the sampling problem is particularly important: because integral privacy enjoys the same closure under post-processing as differential privacy does, any algorithm using integrally privacy sampled data would result in an output equally integrally private. We also show that this brings fairness guarantees on post-processing that would eventually elude classical differential privacy: any decision process has bounded data-dependent bias when the data is integrally privately sampled. Experimental results against private kernel density estimation and private GANs displays the quality of our results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1806.00966v1">Segmentation, Incentives and Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB">
  <p><b>Published on:</b> 2018-06-04T06:01:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kobbi Nissim, Rann Smorodinsky, Moshe Tennenholtz</p>
    <p><b>Summary:</b> Data driven segmentation is the powerhouse behind the success of online advertising. Various underlying challenges for successful segmentation have been studied by the academic community, with one notable exception - consumers incentives have been typically ignored. This lacuna is troubling as consumers have much control over the data being collected. Missing or manipulated data could lead to inferior segmentation. The current work proposes a model of prior-free segmentation, inspired by models of facility location, and to the best of our knowledge provides the first segmentation mechanism that addresses incentive compatibility, efficient market segmentation and privacy in the absence of a common prior.</p>
  </details>
</div>



<h2>2019-01</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1901.09804v1">Is Privacy Controllable?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> 
  <p><b>Published on:</b> 2019-01-28T16:57:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yefim Shulman, Joachim Meyer</p>
    <p><b>Summary:</b> One of the major views of privacy associates privacy with the control over information. This gives rise to the question how controllable privacy actually is. In this paper, we adapt certain formal methods of control theory and investigate the implications of a control theoretic analysis of privacy. We look at how control and feedback mechanisms have been studied in the privacy literature. Relying on the control theoretic framework, we develop a simplistic conceptual control model of privacy, formulate privacy controllability issues and suggest directions for possible research.</p>
  </details>
</div>



<h2>2011-08</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1108.2234v1">Smart Meter Privacy: A Utility-Privacy Framework</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2011-08-10T18:14:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> S. Raj Rajagopalan, Lalitha Sankar, Soheil Mohajer, H. Vincent Poor</p>
    <p><b>Summary:</b> End-user privacy in smart meter measurements is a well-known challenge in the smart grid. The solutions offered thus far have been tied to specific technologies such as batteries or assumptions on data usage. Existing solutions have also not quantified the loss of benefit (utility) that results from any such privacy-preserving approach. Using tools from information theory, a new framework is presented that abstracts both the privacy and the utility requirements of smart meter data. This leads to a novel privacy-utility tradeoff problem with minimal assumptions that is tractable. Specifically for a stationary Gaussian Markov model of the electricity load, it is shown that the optimal utility-and-privacy preserving solution requires filtering out frequency components that are low in power, and this approach appears to encompass most of the proposed privacy approaches.</p>
  </details>
</div>



<h2>2022-09</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2209.15596v2">Individual Privacy Accounting with Gaussian Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2022-09-30T17:19:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Antti Koskela, Marlon Tobaben, Antti Honkela</p>
    <p><b>Summary:</b> Individual privacy accounting enables bounding differential privacy (DP) loss individually for each participant involved in the analysis. This can be informative as often the individual privacy losses are considerably smaller than those indicated by the DP bounds that are based on considering worst-case bounds at each data access. In order to account for the individual privacy losses in a principled manner, we need a privacy accountant for adaptive compositions of randomised mechanisms, where the loss incurred at a given data access is allowed to be smaller than the worst-case loss. This kind of analysis has been carried out for the Rényi differential privacy (RDP) by Feldman and Zrnic (2021), however not yet for the so-called optimal privacy accountants. We make first steps in this direction by providing a careful analysis using the Gaussian differential privacy which gives optimal bounds for the Gaussian mechanism, one of the most versatile DP mechanisms. This approach is based on determining a certain supermartingale for the hockey-stick divergence and on extending the Rényi divergence-based fully adaptive composition results by Feldman and Zrnic. We also consider measuring the individual $(\varepsilon,δ)$-privacy losses using the so-called privacy loss distributions. With the help of the Blackwell theorem, we can then make use of the RDP analysis to construct an approximative individual $(\varepsilon,δ)$-accountant.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2209.02948v3">Assessing Software Privacy using the Privacy Flow-Graph</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2022-09-07T06:11:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Feiyang Tang, Bjarte M. Østvold</p>
    <p><b>Summary:</b> We increasingly rely on digital services and the conveniences they provide. Processing of personal data is integral to such services and thus privacy and data protection are a growing concern, and governments have responded with regulations such as the EU's GDPR. Following this, organisations that make software have legal obligations to document the privacy and data protection of their software. This work must involve both software developers that understand the code and the organisation's data protection officer or legal department that understands privacy and the requirements of a Data Protection and Impact Assessment (DPIA).
  To help developers and non-technical people such as lawyers document the privacy and data protection behaviour of software, we have developed an automatic software analysis technique. This technique is based on static program analysis to characterise the flow of privacy-related data. The results of the analysis can be presented as a graph of privacy flows and operations - that is understandable also for non-technical people. We argue that our technique facilitates collaboration between technical and non-technical people in documenting the privacy behaviour of the software. We explain how to use the results produced by our technique to answer a series of privacy-relevant questions needed for a DPIA. To illustrate our work, we show both detailed and abstract analysis results from applying our analysis technique to the secure messaging service Signal and to the client of the cloud service NextCloud and show how their privacy flow-graphs inform the writing of a DPIA.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2209.01468v1">Randomized Privacy Budget Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2022-09-03T17:33:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Meisam Mohammady</p>
    <p><b>Summary:</b> While pursuing better utility by discovering knowledge from the data, individual's privacy may be compromised during an analysis. To that end, differential privacy has been widely recognized as the state-of-the-art privacy notion. By requiring the presence of any individual's data in the input to only marginally affect the distribution over the output, differential privacy provides strong protection against adversaries in possession of arbitrary background. However, the privacy constraints (e.g., the degree of randomization) imposed by differential privacy may render the released data less useful for analysis, the fundamental trade-off between privacy and utility (i.e., analysis accuracy) has attracted significant attention in various settings. In this report we present DP mechanisms with randomized parameters, i.e., randomized privacy budget, and formally analyze its privacy and utility and demonstrate that randomizing privacy budget in DP mechanisms will boost the accuracy in a humongous scale.</p>
  </details>
</div>



<h2>2017-01</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1701.00841v1">A Taxonomy of Privacy Constructs for Privacy-Sensitive Robotics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E">
  <p><b>Published on:</b> 2017-01-03T21:42:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Matthew Rueben, Cindy M. Grimm, Frank J. Bernieri, William D. Smart</p>
    <p><b>Summary:</b> The introduction of robots into our society will also introduce new concerns about personal privacy. In order to study these concerns, we must do human-subject experiments that involve measuring privacy-relevant constructs. This paper presents a taxonomy of privacy constructs based on a review of the privacy literature. Future work in operationalizing privacy constructs for HRI studies is also discussed.</p>
  </details>
</div>



<h2>2017-10</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1710.03322v5">XYZ Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2017-10-09T21:24:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Josh Joy, Dylan Gray, Ciaran McGoldrick, Mario Gerla</p>
    <p><b>Summary:</b> Future autonomous vehicles will generate, collect, aggregate and consume significant volumes of data as key gateway devices in emerging Internet of Things scenarios. While vehicles are widely accepted as one of the most challenging mobility contexts in which to achieve effective data communications, less attention has been paid to the privacy of data emerging from these vehicles. The quality and usability of such privatized data will lie at the heart of future safe and efficient transportation solutions.
  In this paper, we present the XYZ Privacy mechanism. XYZ Privacy is to our knowledge the first such mechanism that enables data creators to submit multiple contradictory responses to a query, whilst preserving utility measured as the absolute error from the actual original data. The functionalities are achieved in both a scalable and secure fashion. For instance, individual location data can be obfuscated while preserving utility, thereby enabling the scheme to transparently integrate with existing systems (e.g. Waze). A new cryptographic primitive Function Secret Sharing is used to achieve non-attributable writes and we show an order of magnitude improvement from the default implementation.</p>
  </details>
</div>



<h2>2023-02</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2302.09624v3">Breaking the Communication-Privacy-Accuracy Tradeoff with $f$-Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2023-02-19T16:58:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Richeng Jin, Zhonggen Su, Caijun Zhong, Zhaoyang Zhang, Tony Quek, Huaiyu Dai</p>
    <p><b>Summary:</b> We consider a federated data analytics problem in which a server coordinates the collaborative data analysis of multiple users with privacy concerns and limited communication capability. The commonly adopted compression schemes introduce information loss into local data while improving communication efficiency, and it remains an open problem whether such discrete-valued mechanisms provide any privacy protection. In this paper, we study the local differential privacy guarantees of discrete-valued mechanisms with finite output space through the lens of $f$-differential privacy (DP). More specifically, we advance the existing literature by deriving tight $f$-DP guarantees for a variety of discrete-valued mechanisms, including the binomial noise and the binomial mechanisms that are proposed for privacy preservation, and the sign-based methods that are proposed for data compression, in closed-form expressions. We further investigate the amplification in privacy by sparsification and propose a ternary stochastic compressor. By leveraging compression for privacy amplification, we improve the existing methods by removing the dependency of accuracy (in terms of mean square error) on communication cost in the popular use case of distributed mean estimation, therefore breaking the three-way tradeoff between privacy, communication, and accuracy. Finally, we discuss the Byzantine resilience of the proposed mechanism and its application in federated learning.</p>
  </details>
</div>



<h2>2010-11</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1011.2511v1">Individual Privacy vs Population Privacy: Learning to Attack Anonymization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2010-11-10T21:39:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Graham Cormode</p>
    <p><b>Summary:</b> Over the last decade there have been great strides made in developing techniques to compute functions privately. In particular, Differential Privacy gives strong promises about conclusions that can be drawn about an individual. In contrast, various syntactic methods for providing privacy (criteria such as kanonymity and l-diversity) have been criticized for still allowing private information of an individual to be inferred. In this report, we consider the ability of an attacker to use data meeting privacy definitions to build an accurate classifier. We demonstrate that even under Differential Privacy, such classifiers can be used to accurately infer "private" attributes in realistic data. We compare this to similar approaches for inferencebased attacks on other forms of anonymized data. We place these attacks on the same scale, and observe that the accuracy of inference of private attributes for Differentially Private data and l-diverse data can be quite similar.</p>
  </details>
</div>



<h2>2012-01</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1201.4376v2">Participatory Privacy: Enabling Privacy in Participatory Sensing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2012-01-20T20:15:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Emiliano De Cristofaro, Claudio Soriente</p>
    <p><b>Summary:</b> Participatory Sensing is an emerging computing paradigm that enables the distributed collection of data by self-selected participants. It allows the increasing number of mobile phone users to share local knowledge acquired by their sensor-equipped devices, e.g., to monitor temperature, pollution level or consumer pricing information. While research initiatives and prototypes proliferate, their real-world impact is often bounded to comprehensive user participation. If users have no incentive, or feel that their privacy might be endangered, it is likely that they will not participate. In this article, we focus on privacy protection in Participatory Sensing and introduce a suitable privacy-enhanced infrastructure. First, we provide a set of definitions of privacy requirements for both data producers (i.e., users providing sensed information) and consumers (i.e., applications accessing the data). Then, we propose an efficient solution designed for mobile phone users, which incurs very low overhead. Finally, we discuss a number of open problems and possible research directions.</p>
  </details>
</div>



<h2>2022-06</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2206.00240v1">Privacy for Free: How does Dataset Condensation Help Privacy?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2022-06-01T05:39:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tian Dong, Bo Zhao, Lingjuan Lyu</p>
    <p><b>Summary:</b> To prevent unintentional data leakage, research community has resorted to data generators that can produce differentially private data for model training. However, for the sake of the data privacy, existing solutions suffer from either expensive training cost or poor generalization performance. Therefore, we raise the question whether training efficiency and privacy can be achieved simultaneously. In this work, we for the first time identify that dataset condensation (DC) which is originally designed for improving training efficiency is also a better solution to replace the traditional data generators for private data generation, thus providing privacy for free. To demonstrate the privacy benefit of DC, we build a connection between DC and differential privacy, and theoretically prove on linear feature extractors (and then extended to non-linear feature extractors) that the existence of one sample has limited impact ($O(m/n)$) on the parameter distribution of networks trained on $m$ samples synthesized from $n (n \gg m)$ raw samples by DC. We also empirically validate the visual privacy and membership privacy of DC-synthesized data by launching both the loss-based and the state-of-the-art likelihood-based membership inference attacks. We envision this work as a milestone for data-efficient and privacy-preserving machine learning.</p>
  </details>
</div>



<h2>2018-12</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1812.08000v3">Privacy-Aware Eye Tracking Using Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2018-12-19T15:10:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Julian Steil, Inken Hagestedt, Michael Xuelin Huang, Andreas Bulling</p>
    <p><b>Summary:</b> With eye tracking being increasingly integrated into virtual and augmented reality (VR/AR) head-mounted displays, preserving users' privacy is an ever more important, yet under-explored, topic in the eye tracking community. We report a large-scale online survey (N=124) on privacy aspects of eye tracking that provides the first comprehensive account of with whom, for which services, and to what extent users are willing to share their gaze data. Using these insights, we design a privacy-aware VR interface that uses differential privacy, which we evaluate on a new 20-participant dataset for two privacy sensitive tasks: We show that our method can prevent user re-identification and protect gender information while maintaining high performance for gaze-based document type classification. Our results highlight the privacy challenges particular to gaze data and demonstrate that differential privacy is a potential means to address them. Thus, this paper lays important foundations for future research on privacy-aware gaze interfaces.</p>
  </details>
</div>



<h2>2022-02</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2202.12219v2">Debugging Differential Privacy: A Case Study for Privacy Auditing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2022-02-24T17:31:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Florian Tramer, Andreas Terzis, Thomas Steinke, Shuang Song, Matthew Jagielski, Nicholas Carlini</p>
    <p><b>Summary:</b> Differential Privacy can provide provable privacy guarantees for training data in machine learning. However, the presence of proofs does not preclude the presence of errors. Inspired by recent advances in auditing which have been used for estimating lower bounds on differentially private algorithms, here we show that auditing can also be used to find flaws in (purportedly) differentially private schemes. In this case study, we audit a recent open source implementation of a differentially private deep learning algorithm and find, with 99.99999999% confidence, that the implementation does not satisfy the claimed differential privacy guarantee.</p>
  </details>
</div>



<h2>2021-06</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2106.15335v1">Privacy Budget Scheduling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2021-06-29T12:43:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tao Luo, Mingen Pan, Pierre Tholoniat, Asaf Cidon, Roxana Geambasu, Mathias Lécuyer</p>
    <p><b>Summary:</b> Machine learning (ML) models trained on personal data have been shown to leak information about users. Differential privacy (DP) enables model training with a guaranteed bound on this leakage. Each new model trained with DP increases the bound on data leakage and can be seen as consuming part of a global privacy budget that should not be exceeded. This budget is a scarce resource that must be carefully managed to maximize the number of successfully trained models.
  We describe PrivateKube, an extension to the popular Kubernetes datacenter orchestrator that adds privacy as a new type of resource to be managed alongside other traditional compute resources, such as CPU, GPU, and memory. The abstractions we design for the privacy resource mirror those defined by Kubernetes for traditional resources, but there are also major differences. For example, traditional compute resources are replenishable while privacy is not: a CPU can be regained after a model finishes execution while privacy budget cannot. This distinction forces a re-design of the scheduler. We present DPF (Dominant Private Block Fairness) -- a variant of the popular Dominant Resource Fairness (DRF) algorithm -- that is geared toward the non-replenishable privacy resource but enjoys similar theoretical properties as DRF.
  We evaluate PrivateKube and DPF on microbenchmarks and an ML workload on Amazon Reviews data. Compared to existing baselines, DPF allows training more models under the same global privacy guarantee. This is especially true for DPF over Rényi DP, a highly composable form of DP.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2106.09565v3">Interval Privacy: A Framework for Privacy-Preserving Data Collection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2021-06-17T14:47:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jie Ding, Bangjun Ding</p>
    <p><b>Summary:</b> The emerging public awareness and government regulations of data privacy motivate new paradigms of collecting and analyzing data that are transparent and acceptable to data owners. We present a new concept of privacy and corresponding data formats, mechanisms, and theories for privatizing data during data collection. The privacy, named Interval Privacy, enforces the raw data conditional distribution on the privatized data to be the same as its unconditional distribution over a nontrivial support set. Correspondingly, the proposed privacy mechanism will record each data value as a random interval (or, more generally, a range) containing it. The proposed interval privacy mechanisms can be easily deployed through survey-based data collection interfaces, e.g., by asking a respondent whether its data value is within a randomly generated range. Another unique feature of interval mechanisms is that they obfuscate the truth but do not perturb it. Using narrowed range to convey information is complementary to the popular paradigm of perturbing data. Also, the interval mechanisms can generate progressively refined information at the discretion of individuals, naturally leading to privacy-adaptive data collection. We develop different aspects of theory such as composition, robustness, distribution estimation, and regression learning from interval-valued data. Interval privacy provides a new perspective of human-centric data privacy where individuals have a perceptible, transparent, and simple way of sharing sensitive data.</p>
  </details>
</div>



<h2>2021-12</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2112.08487v2">Differential Privacy in Aggregated Mobility Networks: Balancing Privacy and Utility</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2021-12-10T18:53:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ammar Haydari, Chen-Nee Chuah, Michael Zhang, Jane Macfarlane, Sean Peisert</p>
    <p><b>Summary:</b> Location data is collected from users continuously to understand their mobility patterns. Releasing the user trajectories may compromise user privacy. Therefore, the general practice is to release aggregated location datasets. However, private information may still be inferred from an aggregated version of location trajectories. Differential privacy (DP) protects the query output against inference attacks regardless of background knowledge. This paper presents a differential privacy-based privacy model that protects the user's origins and destinations from being inferred from aggregated mobility datasets. This is achieved by injecting Planar Laplace noise to the user origin and destination GPS points. The noisy GPS points are then transformed into a link representation using a link-matching algorithm. Finally, the link trajectories form an aggregated mobility network. The injected noise level is selected using the Sparse Vector Mechanism. This DP selection mechanism considers the link density of the location and the functional category of the localized links. Compared to the different baseline models, including a k-anonymity method, our differential privacy-based aggregation model offers query responses that are close to the raw data in terms of aggregate statistics at both the network and trajectory-levels with maximum 9% deviation from the baseline in terms of network length.</p>
  </details>
</div>



<h2>2024-08</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2408.08904v1">Privacy in Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-08-12T18:41:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jaydip Sen, Hetvi Waghela, Sneha Rakshit</p>
    <p><b>Summary:</b> Federated Learning (FL) represents a significant advancement in distributed machine learning, enabling multiple participants to collaboratively train models without sharing raw data. This decentralized approach enhances privacy by keeping data on local devices. However, FL introduces new privacy challenges, as model updates shared during training can inadvertently leak sensitive information. This chapter delves into the core privacy concerns within FL, including the risks of data reconstruction, model inversion attacks, and membership inference. It explores various privacy-preserving techniques, such as Differential Privacy (DP) and Secure Multi-Party Computation (SMPC), which are designed to mitigate these risks. The chapter also examines the trade-offs between model accuracy and privacy, emphasizing the importance of balancing these factors in practical implementations. Furthermore, it discusses the role of regulatory frameworks, such as GDPR, in shaping the privacy standards for FL. By providing a comprehensive overview of the current state of privacy in FL, this chapter aims to equip researchers and practitioners with the knowledge necessary to navigate the complexities of secure federated learning environments. The discussion highlights both the potential and limitations of existing privacy-enhancing techniques, offering insights into future research directions and the development of more robust solutions.</p>
  </details>
</div>



<h2>2020-05</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2005.10486v2">Privacy Preserving Face Recognition Utilizing Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2020-05-21T06:59:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> M. A. P. Chamikara, P. Bertok, I. Khalil, D. Liu, S. Camtepe</p>
    <p><b>Summary:</b> Facial recognition technologies are implemented in many areas, including but not limited to, citizen surveillance, crime control, activity monitoring, and facial expression evaluation. However, processing biometric information is a resource-intensive task that often involves third-party servers, which can be accessed by adversaries with malicious intent. Biometric information delivered to untrusted third-party servers in an uncontrolled manner can be considered a significant privacy leak (i.e. uncontrolled information release) as biometrics can be correlated with sensitive data such as healthcare or financial records. In this paper, we propose a privacy-preserving technique for "controlled information release", where we disguise an original face image and prevent leakage of the biometric features while identifying a person. We introduce a new privacy-preserving face recognition protocol named PEEP (Privacy using EigEnface Perturbation) that utilizes local differential privacy. PEEP applies perturbation to Eigenfaces utilizing differential privacy and stores only the perturbed data in the third-party servers to run a standard Eigenface recognition algorithm. As a result, the trained model will not be vulnerable to privacy attacks such as membership inference and model memorization attacks. Our experiments show that PEEP exhibits a classification accuracy of around 70% - 90% under standard privacy settings.</p>
  </details>
</div>



<h2>2019-04</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1904.05540v1">Privacy protocols</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B">
  <p><b>Published on:</b> 2019-04-11T05:37:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jason Castiglione, Dusko Pavlovic, Peter-Michael Seidel</p>
    <p><b>Summary:</b> Security protocols enable secure communication over insecure channels. Privacy protocols enable private interactions over secure channels. Security protocols set up secure channels using cryptographic primitives. Privacy protocols set up private channels using secure channels. But just like some security protocols can be broken without breaking the underlying cryptography, some privacy protocols can be broken without breaking the underlying security. Such privacy attacks have been used to leverage e-commerce against targeted advertising from the outset; but their depth and scope became apparent only with the overwhelming advent of influence campaigns in politics. The blurred boundaries between privacy protocols and privacy attacks present a new challenge for protocol analysis. Covert channels turn out to be concealed not only below overt channels, but also above: subversions, and the level-below attacks are supplemented by sublimations and the level-above attacks.</p>
  </details>
</div>



<h2>2020-02</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2002.01501v2">The Privacy Funnel from the viewpoint of Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2020-02-04T19:16:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Milan Lopuhaä-Zwakenberg</p>
    <p><b>Summary:</b> We consider a database $\vec{X} = (X_1,\cdots,X_n)$ containing the data of $n$ users. The data aggregator wants to publicise the database, but wishes to sanitise the dataset to hide sensitive data $S_i$ correlated to $X_i$. This setting is considered in the Privacy Funnel, which uses mutual information as a leakage metric. The downsides to this approach are that mutual information does not give worst-case guarantees, and that finding optimal sanitisation protocols can be computationally prohibitive. We tackle these problems by using differential privacy metrics, and by considering local protocols which operate on one entry at a time. We show that under both the Local Differential Privacy and Local Information Privacy leakage metrics, one can efficiently obtain optimal protocols; however, Local Information Privacy is both more closely aligned to the privacy requirements of the Privacy Funnel scenario, and more efficiently computable. We also consider the scenario where each user has multiple attributes (i.e. $X_i = (X^1_i,\cdots,X^m_i)$), for which we define \emph{Side-channel Resistant Local Information Privacy}, and we give efficient methods to find protocols satisfying this criterion while still offering good utility. Exploratory experiments confirm the validity of these methods.</p>
  </details>
</div>



<h2>2022-12</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2212.00528v1">A Value-Centered Exploration of Data Privacy and Personalized Privacy Assistants</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2022-12-01T14:26:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sarah E. Carter</p>
    <p><b>Summary:</b> In the the current post-GDPR landscape, privacy notices have become ever more prevalent on our phones and online. However, these notices are not well suited to their purpose of helping users make informed decisions. I suggest that instead of utilizing notice to eliciting informed consent, we could repurpose privacy notices to create the space for more meaningful, value-centered user decisions. Value-centered privacy decisions, or those that accurately reflect who we are and what we value, encapsulate the intuitive role of personal values in data privacy decisions. To explore how notices could be repurposed to support such decisions, I utilize Suzy Killmister's four-dimensional theory of autonomy (4DT) to operationalize value-centered privacy decisions. I then assess the degree that an existing technology, Personalized Privacy Assistants (PPAs), uses notices in a manner that allows for value-centered decision-making. Lastly, I explore the implications of the PPA assessment for designing a new assistant, called a value-centered privacy assistant (VcPA). A VcPA could ideally utilized notice to assists users in value-centered app selection and in other data privacy decisions.</p>
  </details>
</div>



<h2>2008-03</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/0803.3096v2">Physical Underpinnings of Privacy</a></h3>
  
  <p><b>Published on:</b> 2008-03-20T23:46:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joseph M. Renes, Jean-Christian Boileau</p>
    <p><b>Summary:</b> One of the remarkable features of quantum mechanics is the ability to ensure secrecy. Private states embody this effect, as they are precisely those multipartite quantum states from which two parties can produce a shared secret that cannot in any circumstance be correlated to an external system. Naturally, these play an important role in quantum key distribution (QKD) and quantum information theory. However, a general distillation method has heretofore been missing. Inspired by Koashi's complementary control scenario (arXiv:0704.3661v1 [quant-ph]), we give a new definition of private states in terms of one party's potential knowledge of two complementary measurements made on the other and use this to construct a general method of private state distillation using quantum error-correcting codes. The procedure achieves the same key rate as recent, more information-theoretic approaches while demonstrating the physical principles underlying privacy of the key. Additionally, the same approach can be used to establish the hashing inequality for entanglement distillation, as well as the direct quantum coding theorem.</p>
  </details>
</div>



<h2>2017-02</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1702.07476v3">Renyi Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2017-02-24T06:46:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ilya Mironov</p>
    <p><b>Summary:</b> We propose a natural relaxation of differential privacy based on the Renyi divergence. Closely related notions have appeared in several recent papers that analyzed composition of differentially private mechanisms. We argue that the useful analytical tool can be used as a privacy definition, compactly and accurately representing guarantees on the tails of the privacy loss.
  We demonstrate that the new definition shares many important properties with the standard definition of differential privacy, while additionally allowing tighter analysis of composite heterogeneous mechanisms.</p>
  </details>
</div>



<h2>2019-10</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1910.13027v1">Noiseless Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">  
  <p><b>Published on:</b> 2019-10-29T01:09:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Farhad Farokhi</p>
    <p><b>Summary:</b> In this paper, we define noiseless privacy, as a non-stochastic rival to differential privacy, requiring that the outputs of a mechanism (i.e., function composition of a privacy-preserving mapping and a query) can attain only a few values while varying the data of an individual (the logarithm of the number of the distinct values is bounded by the privacy budget). Therefore, the output of the mechanism is not fully informative of the data of the individuals in the dataset. We prove several guarantees for noiselessly-private mechanisms. The information content of the output about the data of an individual, even if an adversary knows all the other entries of the private dataset, is bounded by the privacy budget. The zero-error capacity of memory-less channels using noiselessly private mechanisms for transmission is upper bounded by the privacy budget. The performance of a non-stochastic hypothesis-testing adversary is bounded again by the privacy budget. Finally, assuming that an adversary has access to a stochastic prior on the dataset, we prove that the estimation error of the adversary for individual entries of the dataset is lower bounded by a decreasing function of the privacy budget. In this case, we also show that the maximal information leakage is bounded by the privacy budget. In addition to privacy guarantees, we prove that noiselessly-private mechanisms admit composition theorem and post-processing does not weaken their privacy guarantees. We prove that quantization operators can ensure noiseless privacy if the number of quantization levels is appropriately selected based on the sensitivity of the query and the privacy budget. Finally, we illustrate the privacy merits of noiseless privacy using multiple datasets in energy and transport.</p>
  </details>
</div>



<h2>2020-04</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2004.11131v2">Privacy at Scale: Introducing the PrivaSeer Corpus of Web Privacy Policies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2020-04-23T13:21:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mukund Srinath, Shomir Wilson, C. Lee Giles</p>
    <p><b>Summary:</b> Organisations disclose their privacy practices by posting privacy policies on their website. Even though users often care about their digital privacy, they often don't read privacy policies since they require a significant investment in time and effort. Although natural language processing can help in privacy policy understanding, there has been a lack of large scale privacy policy corpora that could be used to analyse, understand, and simplify privacy policies. Thus, we create PrivaSeer, a corpus of over one million English language website privacy policies, which is significantly larger than any previously available corpus. We design a corpus creation pipeline which consists of crawling the web followed by filtering documents using language detection, document classification, duplicate and near-duplication removal, and content extraction. We investigate the composition of the corpus and show results from readability tests, document similarity, keyphrase extraction, and explored the corpus through topic modeling.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2004.09481v4">Connecting Robust Shuffle Privacy and Pan-Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2020-04-20T17:58:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Victor Balcer, Albert Cheu, Matthew Joseph, Jieming Mao</p>
    <p><b>Summary:</b> In the \emph{shuffle model} of differential privacy, data-holding users send randomized messages to a secure shuffler, the shuffler permutes the messages, and the resulting collection of messages must be differentially private with regard to user data. In the \emph{pan-private} model, an algorithm processes a stream of data while maintaining an internal state that is differentially private with regard to the stream data. We give evidence connecting these two apparently different models.
  Our results focus on \emph{robustly} shuffle private protocols, whose privacy guarantees are not greatly affected by malicious users. First, we give robustly shuffle private protocols and upper bounds for counting distinct elements and uniformity testing. Second, we use pan-private lower bounds to prove robustly shuffle private lower bounds for both problems. Focusing on the dependence on the domain size $k$, we find that robust approximate shuffle privacy and approximate pan-privacy have additive error $Θ(\sqrt{k})$ for counting distinct elements. For uniformity testing, we give a robust approximate shuffle private protocol with sample complexity $\tilde O(k^{2/3})$ and show that an $Ω(k^{2/3})$ dependence is necessary for any robust pure shuffle private tester. Finally, we show that this connection is useful in both directions: we give a pan-private adaptation of recent work on shuffle private histograms and use it to recover further separations between pan-privacy and interactive local privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2004.02047v1">Privacy Shadow: Measuring Node Predictability and Privacy Over Time</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2020-04-04T23:31:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ivan Brugere, Tanya y. Berger-Wolf</p>
    <p><b>Summary:</b> The structure of network data enables simple predictive models to leverage local correlations between nodes to high accuracy on tasks such as attribute and link prediction. While this is useful for building better user models, it introduces the privacy concern that a user's data may be re-inferred from the network structure, after they leave the application. We propose the privacy shadow for measuring how long a user remains predictive from an arbitrary time within the network. Furthermore, we demonstrate that the length of the privacy shadow can be predicted for individual users in three real-world datasets.</p>
  </details>
</div>



<h2>2014-11</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1411.5718v2">Inequalities for the quantum privacy</a></h3>
   
  <p><b>Published on:</b> 2014-11-20T23:11:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> M. A. S Trindade, E. Pinto</p>
    <p><b>Summary:</b> In this work we investigate the asymptotic behavior related to the quantum privacy for multipartite systems. In this context, an inequality for quantum privacy was obtained by exploiting of quantum entropy properties. Subsequently, we derive a lower limit for the quantum privacy through the entanglement fidelity. In particular, we show that there is an interval where an increase in entanglement fidelity implies a decrease in quantum privacy.</p>
  </details>
</div>



<h2>2016-08</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1608.04001v1">Almost Perfect Privacy for Additive Gaussian Privacy Filters</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">
  <p><b>Published on:</b> 2016-08-13T16:30:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shahab Asoodeh, Fady Alajaji, Tamas Linder</p>
    <p><b>Summary:</b> We study the maximal mutual information about a random variable $Y$ (representing non-private information) displayed through an additive Gaussian channel when guaranteeing that only $ε$ bits of information is leaked about a random variable $X$ (representing private information) that is correlated with $Y$. Denoting this quantity by $g_ε(X,Y)$, we show that for perfect privacy, i.e., $ε=0$, one has $g_0(X,Y)=0$ for any pair of absolutely continuous random variables $(X,Y)$ and then derive a second-order approximation for $g_ε(X,Y)$ for small $ε$. This approximation is shown to be related to the strong data processing inequality for mutual information under suitable conditions on the joint distribution $P_{XY}$. Next, motivated by an operational interpretation of data privacy, we formulate the privacy-utility tradeoff in the same setup using estimation-theoretic quantities and obtain explicit bounds for this tradeoff when $ε$ is sufficiently small using the approximation formula derived for $g_ε(X,Y)$.</p>
  </details>
</div>



<h2>2023-08</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2308.05700v2">In Pursuit of Privacy: The Value-Centered Privacy Assistant</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2023-08-10T17:04:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sarah E. Carter, Mathieu d'Aquin, Dayana Spagnuelo, Ilaria Tiddi, Kathryn Cormican, Heike Felzmann</p>
    <p><b>Summary:</b> Many users make quick decisions that affect their data privacy without due consideration of their values. One such decision is whether to download a smartphone app to their device. Previous work has suggested a relationship between values, privacy preferences, and app choices, and proposed a value-centered approach to privacy that conceptually unites these relationships. In this work, we translate this theory into practice by constructing a prototype smartphone value-centered privacy assistant (VcPA) - a privacy assistant system that promotes user privacy decisions based on personal values. To do this, we designed and conducted an online survey that captured values and privacy preferences when considering whether to download an app from 273 smartphone users. Using this data, we constructed VcPA user profiles by clustering survey data based on the value rankings and stated privacy preferences. We then tested the VcPA, using selective notices, a "suggest alternatives" feature, and exploratory notices, with 77 users in a synthetic Mock App Store (MAS) setting and conducted follow-up semi-structured interviews. We establish proof-of-concept that a VcPA helps users make more value-centered app choices and identified improvements so that an assistant can be deployed on smartphone app stores.</p>
  </details>
</div>



<h2>2024-10</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.20555v2">Privacy-Enhanced Adaptive Authentication: User Profiling with Privacy Guarantees</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-27T19:11:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yaser Baseri, Abdelhakim Senhaji Hafid, Dimitrios Makrakis</p>
    <p><b>Summary:</b> User profiling is a critical component of adaptive risk-based authentication, yet it raises significant privacy concerns, particularly when handling sensitive data. Profiling involves collecting and aggregating various user features, potentially creating quasi-identifiers that can reveal identities and compromise privacy. Even anonymized profiling methods remain vulnerable to re-identification attacks through these quasi-identifiers. This paper introduces a novel privacy-enhanced adaptive authentication protocol that leverages Oblivious Pseudorandom Functions (OPRF), anonymous tokens, and Differential Privacy (DP) to provide robust privacy guarantees. Our proposed approach dynamically adjusts authentication requirements based on real-time risk assessments, enhancing security while safeguarding user privacy. By integrating privacy considerations into the core of adaptive risk-based adaptive authentication, this approach addresses a gap often overlooked in traditional models. Advanced cryptographic techniques ensure confidentiality, integrity, and unlinkability of user data, while differential privacy mechanisms minimize the impact of individual data points on overall analysis. Formal security and privacy proofs demonstrate the protocol's resilience against various threats and its ability to provide strong privacy guarantees. Additionally, a comprehensive performance evaluation reveals that the computational and communication overheads are manageable, making the protocol practical for real-world deployment. By adhering to data protection regulations such as GDPR and CCPA, our protocol not only enhances security but also fosters user trust and compliance with legal standards.</p>
  </details>
</div>



<h2>2014-04</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1404.5454v1">Stochastic Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2014-04-22T10:55:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Adish Singla, Eric Horvitz, Ece Kamar, Ryen White</p>
    <p><b>Summary:</b> Online services such as web search and e-commerce applications typically rely on the collection of data about users, including details of their activities on the web. Such personal data is used to enhance the quality of service via personalization of content and to maximize revenues via better targeting of advertisements and deeper engagement of users on sites. To date, service providers have largely followed the approach of either requiring or requesting consent for opting-in to share their data. Users may be willing to share private information in return for better quality of service or for incentives, or in return for assurances about the nature and extend of the logging of data. We introduce \emph{stochastic privacy}, a new approach to privacy centering on a simple concept: A guarantee is provided to users about the upper-bound on the probability that their personal data will be used. Such a probability, which we refer to as \emph{privacy risk}, can be assessed by users as a preference or communicated as a policy by a service provider. Service providers can work to personalize and to optimize revenues in accordance with preferences about privacy risk. We present procedures, proofs, and an overall system for maximizing the quality of services, while respecting bounds on allowable or communicated privacy risk. We demonstrate the methodology with a case study and evaluation of the procedures applied to web search personalization. We show how we can achieve near-optimal utility of accessing information with provable guarantees on the probability of sharing data.</p>
  </details>
</div>



<h2>2023-01</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2301.11754v1">Information-Theoretic Privacy-Preserving Schemes Based On Perfect Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2023-01-27T14:48:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Borzoo Rassouli, Deniz Gündüz</p>
    <p><b>Summary:</b> Consider a pair of random variables $(X,Y)$ distributed according to a given joint distribution $p_{XY}$. A curator wishes to maximally disclose information about $Y$, while limiting the information leakage incurred on $X$. Adopting mutual information to measure both utility and privacy of this information disclosure, the problem is to maximize $I(Y;U)$, subject to $I(X;U)\leqε$, where $U$ denotes the released random variable and $ε$ is a given privacy threshold. Two settings are considered, where in the first one, the curator has access to $(X,Y)$, and hence, the optimization is over $p_{U|XY}$, while in the second one, the curator can only observe $Y$ and the optimization is over $p_{U|Y}$. In both settings, the utility-privacy trade-off is investigated from theoretical and practical perspective. More specifically, several privacy-preserving schemes are proposed in these settings based on generalizing the notion of statistical independence. Moreover, closed-form solutions are provided in certain scenarios. Finally, convexity arguments are provided for the utility-privacy trade-off as functionals of the joint distribution $p_{XY}$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2301.00841v1">Ranking Differential Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">
  <p><b>Published on:</b> 2023-01-02T19:12:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shirong Xu, Will Wei Sun, Guang Cheng</p>
    <p><b>Summary:</b> Rankings are widely collected in various real-life scenarios, leading to the leakage of personal information such as users' preferences on videos or news. To protect rankings, existing works mainly develop privacy protection on a single ranking within a set of ranking or pairwise comparisons of a ranking under the $ε$-differential privacy. This paper proposes a novel notion called $ε$-ranking differential privacy for protecting ranks. We establish the connection between the Mallows model (Mallows, 1957) and the proposed $ε$-ranking differential privacy. This allows us to develop a multistage ranking algorithm to generate synthetic rankings while satisfying the developed $ε$-ranking differential privacy. Theoretical results regarding the utility of synthetic rankings in the downstream tasks, including the inference attack and the personalized ranking tasks, are established. For the inference attack, we quantify how $ε$ affects the estimation of the true ranking based on synthetic rankings. For the personalized ranking task, we consider varying privacy preferences among users and quantify how their privacy preferences affect the consistency in estimating the optimal ranking function. Extensive numerical experiments are carried out to verify the theoretical results and demonstrate the effectiveness of the proposed synthetic ranking algorithm.</p>
  </details>
</div>



<h2>2019-07</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1907.09311v1">On the Information Privacy Model: the Group and Composition Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2019-07-22T13:23:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Genqiang Wu</p>
    <p><b>Summary:</b> How to query a dataset in the way of preserving the privacy of individuals whose data is included in the dataset is an important problem. The information privacy model, a variant of Shannon's information theoretic model to the encryption systems, protects the privacy of an individual by controlling the amount of information of the individual's data obtained by each adversary from the query's output. This model also assumes that each adversary's uncertainty to the queried dataset is not so small in order to improve the data utility. In this paper, we prove some results to the group privacy and the composition privacy properties of this model, where the group privacy ensures a group of individuals' privacy is preserved, and where the composition privacy ensures multiple queries also preserve the privacy of an individual. Explicitly, we reduce the proof of the two properties to the estimation of the difference of two channel capacities. Our proofs are greatly benefited from some information-theoretic tools and approaches.</p>
  </details>
</div>



<h2>2014-07</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1407.0423v1">Privacy and Anonymity</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2014-07-01T22:52:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Adrian Yanes</p>
    <p><b>Summary:</b> Since the beginning of the digital area, privacy and anonymity have been impacted drastically (both, positively and negatively), by the different technologies developed for communications purposes. The broad possibilities that the Internet offers since its conception, makes it a mandatory target for those entities that are aiming to know and control the different channels of communication and the information that flows through. In this paper, we address the current threats against privacy and anonymity on the Internet, together with the methods applied against them. In addition, we enumerate the publicly known entities behind those threats and their motivations. Finally, we analyze the state of the art concerning the protection of the privacy and anonymity on the Internet; introducing future lines of research.</p>
  </details>
</div>



<h2>2020-08</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2009.00442v1">Imitation Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2020-08-30T20:29:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xun Xian, Xinran Wang, Mingyi Hong, Jie Ding, Reza Ghanadan</p>
    <p><b>Summary:</b> In recent years, there have been many cloud-based machine learning services, where well-trained models are provided to users on a pay-per-query scheme through a prediction API. The emergence of these services motivates this work, where we will develop a general notion of model privacy named imitation privacy. We show the broad applicability of imitation privacy in classical query-response MLaaS scenarios and new multi-organizational learning scenarios. We also exemplify the fundamental difference between imitation privacy and the usual data-level privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2008.13151v1">Data Sanitisation Protocols for the Privacy Funnel with Differential Privacy Guarantees</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2020-08-30T12:19:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Milan Lopuhaä-Zwakenberg, Haochen Tong, Boris Škorić</p>
    <p><b>Summary:</b> In the Open Data approach, governments and other public organisations want to share their datasets with the public, for accountability and to support participation. Data must be opened in such a way that individual privacy is safeguarded. The Privacy Funnel is a mathematical approach that produces a sanitised database that does not leak private data beyond a chosen threshold. The downsides to this approach are that it does not give worst-case privacy guarantees, and that finding optimal sanitisation protocols can be computationally prohibitive. We tackle these problems by using differential privacy metrics, and by considering local protocols which operate on one entry at a time. We show that under both the Local Differential Privacy and Local Information Privacy leakage metrics, one can efficiently obtain optimal protocols. Furthermore, Local Information Privacy is both more closely aligned to the privacy requirements of the Privacy Funnel scenario, and more efficiently computable. We also consider the scenario where each user has multiple attributes, for which we define Side-channel Resistant Local Information Privacy, and we give efficient methods to find protocols satisfying this criterion while still offering good utility. Finally, we introduce Conditional Reporting, an explicit LIP protocol that can be used when the optimal protocol is infeasible to compute, and we test this protocol on real-world and synthetic data. Experiments on real-world and synthetic data confirm the validity of these methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2008.12199v4">Privacy Intelligence: A Survey on Image Privacy in Online Social Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B">
  <p><b>Published on:</b> 2020-08-27T15:52:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chi Liu, Tianqing Zhu, Jun Zhang, Wanlei Zhou</p>
    <p><b>Summary:</b> Image sharing on online social networks (OSNs) has become an indispensable part of daily social activities, but it has also led to an increased risk of privacy invasion. The recent image leaks from popular OSN services and the abuse of personal photos using advanced algorithms (e.g. DeepFake) have prompted the public to rethink individual privacy needs in OSN image sharing. However, OSN image privacy itself is quite complicated, and solutions currently in place for privacy management in reality are insufficient to provide personalized, accurate and flexible privacy protection. A more intelligent environment for privacy-friendly OSN image sharing is in demand. To fill the gap, we contribute a survey of "privacy intelligence" that targets modern privacy issues in dynamic OSN image sharing from a user-centric perspective. Specifically, we present a definition and a taxonomy of OSN image privacy, and a high-level privacy analysis framework based on the lifecycle of OSN image sharing. The framework consists of three stages with different principles of privacy by design. At each stage, we identify typical user behaviors in OSN image sharing and the privacy issues associated with these behaviors. Then a systematic review on the representative intelligent solutions targeting those privacy issues is conducted, also in a stage-based manner. The resulting analysis describes an intelligent privacy firewall for closed-loop privacy management. We also discuss the challenges and future directions in this area.</p>
  </details>
</div>



<h2>2025-01</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2501.12893v2">Statistical Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-01-22T14:13:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dennis Breutigam, Rüdiger Reischuk</p>
    <p><b>Summary:</b> To analyze the privacy guarantee of personal data in a database that is subject to queries it is necessary to model the prior knowledge of a possible attacker. Differential privacy considers a worst-case scenario where he knows almost everything, which in many applications is unrealistic and requires a large utility loss.
  This paper considers a situation called statistical privacy where an adversary knows the distribution by which the database is generated, but no exact data of all (or sufficient many) of its entries. We analyze in detail how the entropy of the distribution guarantes privacy for a large class of queries called property queries. Exact formulas are obtained for the privacy parameters. We analyze how they depend on the probability that an entry fulfills the property under investigation. These formulas turn out to be lengthy, but can be used for tight numerical approximations of the privacy parameters. Such estimations are necessary for applying privacy enhancing techniques in practice. For this statistical setting we further investigate the effect of adding noise or applying subsampling and the privacy utility tradeoff. The dependencies on the parameters are illustrated in detail by a series of plots. Finally, these results are compared to the differential privacy model.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2501.01786v1">Advancing privacy in learning analytics using differential privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-01-03T12:36:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qinyi Liu, Ronas Shakya, Mohammad Khalil, Jelena Jovanovic</p>
    <p><b>Summary:</b> This paper addresses the challenge of balancing learner data privacy with the use of data in learning analytics (LA) by proposing a novel framework by applying Differential Privacy (DP). The need for more robust privacy protection keeps increasing, driven by evolving legal regulations and heightened privacy concerns, as well as traditional anonymization methods being insufficient for the complexities of educational data. To address this, we introduce the first DP framework specifically designed for LA and provide practical guidance for its implementation. We demonstrate the use of this framework through a LA usage scenario and validate DP in safeguarding data privacy against potential attacks through an experiment on a well-known LA dataset. Additionally, we explore the trade-offs between data privacy and utility across various DP settings. Our work contributes to the field of LA by offering a practical DP framework that can support researchers and practitioners in adopting DP in their works.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2501.01131v2">Privacy Bills of Materials: A Transparent Privacy Information Inventory for Collaborative Privacy Notice Generation in Mobile App Development</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-01-02T08:14:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhen Tao, Shidong Pan, Zhenchang Xing, Xiaoyu Sun, Omar Haggag, John Grundy, Jingjie Li, Liming Zhu</p>
    <p><b>Summary:</b> Privacy regulations mandate that developers must provide authentic and comprehensive privacy notices, e.g., privacy policies or labels, to inform users of their apps' privacy practices. However, due to a lack of knowledge of privacy requirements, developers often struggle to create accurate privacy notices, especially for sophisticated mobile apps with complex features and in crowded development teams. To address these challenges, we introduce Privacy Bills of Materials (PriBOM), a systematic software engineering approach that leverages different development team roles to better capture and coordinate mobile app privacy information. PriBOM facilitates transparency-centric privacy documentation and specific privacy notice creation, enabling traceability and trackability of privacy practices. We present a pre-fill of PriBOM based on static analysis and privacy notice analysis techniques. We demonstrate the perceived usefulness of PriBOM through a human evaluation with 150 diverse participants. Our findings suggest that PriBOM could serve as a significant solution for providing privacy support in DevOps for mobile apps.</p>
  </details>
</div>



<h2>2017-09</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1709.02753v2">Privacy Loss in Apple's Implementation of Differential Privacy on MacOS 10.12</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2017-09-08T16:00:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jun Tang, Aleksandra Korolova, Xiaolong Bai, Xueqiang Wang, Xiaofeng Wang</p>
    <p><b>Summary:</b> In June 2016, Apple announced that it will deploy differential privacy for some user data collection in order to ensure privacy of user data, even from Apple. The details of Apple's approach remained sparse. Although several patents have since appeared hinting at the algorithms that may be used to achieve differential privacy, they did not include a precise explanation of the approach taken to privacy parameter choice. Such choice and the overall approach to privacy budget use and management are key questions for understanding the privacy protections provided by any deployment of differential privacy.
  In this work, through a combination of experiments, static and dynamic code analysis of macOS Sierra (Version 10.12) implementation, we shed light on the choices Apple made for privacy budget management. We discover and describe Apple's set-up for differentially private data processing, including the overall data pipeline, the parameters used for differentially private perturbation of each piece of data, and the frequency with which such data is sent to Apple's servers.
  We find that although Apple's deployment ensures that the (differential) privacy loss per each datum submitted to its servers is $1$ or $2$, the overall privacy loss permitted by the system is significantly higher, as high as $16$ per day for the four initially announced applications of Emojis, New words, Deeplinks and Lookup Hints. Furthermore, Apple renews the privacy budget available every day, which leads to a possible privacy loss of 16 times the number of days since user opt-in to differentially private data collection for those four applications.
  We advocate that in order to claim the full benefits of differentially private data collection, Apple must give full transparency of its implementation, enable user choice in areas related to privacy loss, and set meaningful defaults on the privacy loss permitted.</p>
  </details>
</div>



<h2>2022-07</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2207.03940v1">Bistochastic privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2022-07-08T14:50:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nicolas Ruiz, Josep Domingo-Ferrer</p>
    <p><b>Summary:</b> We introduce a new privacy model relying on bistochastic matrices, that is, matrices whose components are nonnegative and sum to 1 both row-wise and column-wise. This class of matrices is used to both define privacy guarantees and a tool to apply protection on a data set. The bistochasticity assumption happens to connect several fields of the privacy literature, including the two most popular models, k-anonymity and differential privacy. Moreover, it establishes a bridge with information theory, which simplifies the thorny issue of evaluating the utility of a protected data set. Bistochastic privacy also clarifies the trade-off between protection and utility by using bits, which can be viewed as a natural currency to comprehend and operationalize this trade-off, in the same way than bits are used in information theory to capture uncertainty. A discussion on the suitable parameterization of bistochastic matrices to achieve the privacy guarantees of this new model is also provided.</p>
  </details>
</div>



<h2>2013-06</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1306.2083v1">Privacy and Mechanism Design</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2013-06-10T01:41:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mallesh Pai, Aaron Roth</p>
    <p><b>Summary:</b> This paper is a survey of recent work at the intersection of mechanism design and privacy. The connection is a natural one, but its study has been jump-started in recent years by the advent of differential privacy, which provides a rigorous, quantitative way of reasoning about the costs that an agent might experience because of the loss of his privacy. Here, we survey several facets of this study, and differential privacy plays a role in more than one way. Of course, it provides us a basis for modeling agent costs for privacy, which is essential if we are to attempt mechanism design in a setting in which agents have preferences for privacy. It also provides a toolkit for controlling those costs. However, perhaps more surprisingly, it provides a powerful toolkit for controlling the stability of mechanisms in general, which yields a set of tools for designing novel mechanisms even in economic settings completely unrelated to privacy.</p>
  </details>
</div>



<h2>2017-03</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1703.09847v2">Designing Privacy for You : A User Centric Approach For Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2017-03-29T00:27:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Awanthika Senarath, Nalin A. G. Arachchilage, Jill Slay</p>
    <p><b>Summary:</b> Privacy directly concerns the user as the data owner (data- subject) and hence privacy in systems should be implemented in a manner which concerns the user (user-centered). There are many concepts and guidelines that support development of privacy and embedding privacy into systems. However, none of them approaches privacy in a user- centered manner. Through this research we propose a framework that would enable developers and designers to grasp privacy in a user-centered manner and implement it along with the software development life cycle.</p>
  </details>
</div>



<h2>2024-07</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2407.18157v1">Enhanced Privacy Bound for Shuffle Model with Personalized Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2024-07-25T16:11:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yixuan Liu, Yuhan Liu, Li Xiong, Yujie Gu, Hong Chen</p>
    <p><b>Summary:</b> The shuffle model of Differential Privacy (DP) is an enhanced privacy protocol which introduces an intermediate trusted server between local users and a central data curator. It significantly amplifies the central DP guarantee by anonymizing and shuffling the local randomized data. Yet, deriving a tight privacy bound is challenging due to its complicated randomization protocol. While most existing work are focused on unified local privacy settings, this work focuses on deriving the central privacy bound for a more practical setting where personalized local privacy is required by each user. To bound the privacy after shuffling, we first need to capture the probability of each user generating clones of the neighboring data points. Second, we need to quantify the indistinguishability between two distributions of the number of clones on neighboring datasets. Existing works either inaccurately capture the probability, or underestimate the indistinguishability between neighboring datasets. Motivated by this, we develop a more precise analysis, which yields a general and tighter bound for arbitrary DP mechanisms. Firstly, we derive the clone-generating probability by hypothesis testing %from a randomizer-specific perspective, which leads to a more accurate characterization of the probability. Secondly, we analyze the indistinguishability in the context of $f$-DP, where the convexity of the distributions is leveraged to achieve a tighter privacy bound. Theoretical and numerical results demonstrate that our bound remarkably outperforms the existing results in the literature.</p>
  </details>
</div>



<h2>2020-01</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2001.01825v1">Protect Edge Privacy in Path Publishing with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2020-01-07T00:39:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhigang Lu, Hong Shen</p>
    <p><b>Summary:</b> Paths in a given network are a generalised form of time-serial chains in many real-world applications, such as trajectories and Internet flows. Differentially private trajectory publishing concerns publishing path information that is usable to the genuine users yet secure against adversaries to reconstruct the path with maximum background knowledge. The exiting studies all assume this knowledge to be all but one vertex on the path. To prevent the adversaries recovering the missing information, they publish a perturbed path where each vertex is sampled from a pre-defined set with differential privacy (DP) to replace the corresponding vertex in the original path. In this paper, we relax this assumption to be all but one edge on the path, and hence consider the scenario of more powerful adversaries with the maximum background knowledge of the entire network topology and the path (including all the vertices) except one (arbitrary) missing edge. Under such an assumption, the perturbed path produced by the existing work is vulnerable, because the adversary can reconstruct the missing edge from the existence of an edge in the perturbed path. To address this vulnerability and effectively protect edge privacy, instead of publishing a perturbed path, we propose a novel scheme of graph-based path publishing to protect the original path by embedding the path in a graph that contains fake edges and replicated vertices applying the differential privacy technique, such that only the legitimate users who have the full knowledge of the network topology are able to recover the exact vertices and edges of the original path with high probability. We theoretically analyse the performance of our algorithm in differential privacy, utility, and execution efficiency. We also conduct extensive experimental evaluations on a high-performance cluster system to validate our analytical results.</p>
  </details>
</div>



<h2>2023-09</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2309.15087v1">Privacy-preserving and Privacy-attacking Approaches for Speech and Audio -- A Survey</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2023-09-26T17:31:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuchen Liu, Apu Kapadia, Donald Williamson</p>
    <p><b>Summary:</b> In contemporary society, voice-controlled devices, such as smartphones and home assistants, have become pervasive due to their advanced capabilities and functionality. The always-on nature of their microphones offers users the convenience of readily accessing these devices. However, recent research and events have revealed that such voice-controlled devices are prone to various forms of malicious attacks, hence making it a growing concern for both users and researchers to safeguard against such attacks. Despite the numerous studies that have investigated adversarial attacks and privacy preservation for images, a conclusive study of this nature has not been conducted for the audio domain. Therefore, this paper aims to examine existing approaches for privacy-preserving and privacy-attacking strategies for audio and speech. To achieve this goal, we classify the attack and defense scenarios into several categories and provide detailed analysis of each approach. We also interpret the dissimilarities between the various approaches, highlight their contributions, and examine their limitations. Our investigation reveals that voice-controlled devices based on neural networks are inherently susceptible to specific types of attacks. Although it is possible to enhance the robustness of such models to certain forms of attack, more sophisticated approaches are required to comprehensively safeguard user privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2309.05330v1">Diff-Privacy: Diffusion-based Face Privacy Protection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2023-09-11T09:26:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiao He, Mingrui Zhu, Dongxin Chen, Nannan Wang, Xinbo Gao</p>
    <p><b>Summary:</b> Privacy protection has become a top priority as the proliferation of AI techniques has led to widespread collection and misuse of personal data. Anonymization and visual identity information hiding are two important facial privacy protection tasks that aim to remove identification characteristics from facial images at the human perception level. However, they have a significant difference in that the former aims to prevent the machine from recognizing correctly, while the latter needs to ensure the accuracy of machine recognition. Therefore, it is difficult to train a model to complete these two tasks simultaneously. In this paper, we unify the task of anonymization and visual identity information hiding and propose a novel face privacy protection method based on diffusion models, dubbed Diff-Privacy. Specifically, we train our proposed multi-scale image inversion module (MSI) to obtain a set of SDM format conditional embeddings of the original image. Based on the conditional embeddings, we design corresponding embedding scheduling strategies and construct different energy functions during the denoising process to achieve anonymization and visual identity information hiding. Extensive experiments have been conducted to validate the effectiveness of our proposed framework in protecting facial privacy.</p>
  </details>
</div>



<h2>2022-03</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2203.11586v1">Privacy: An axiomatic approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2022-03-22T10:10:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alexander Ziller, Tamara Mueller, Rickmer Braren, Daniel Rueckert, Georgios Kaissis</p>
    <p><b>Summary:</b> The increasing prevalence of large-scale data collection in modern society represents a potential threat to individual privacy. Addressing this threat, for example through privacy-enhancing technologies (PETs), requires a rigorous definition of what exactly is being protected, that is, of privacy itself. In this work, we formulate an axiomatic definition of privacy based on quantifiable and irreducible information flows. Our definition synthesizes prior work from the domain of social science with a contemporary understanding of PETs such as differential privacy (DP). Our work highlights the fact that the inevitable difficulties of protecting privacy in practice are fundamentally information-theoretic. Moreover, it enables quantitative reasoning about PETs based on what they are protecting, thus fostering objective policy discourse about their societal implementation.</p>
  </details>
</div>



<h2>2021-01</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2101.09139v1">The Privacy-Utility Tradeoff of Robust Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2021-01-22T15:00:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Milan Lopuhaä-Zwakenberg, Jasper Goseling</p>
    <p><b>Summary:</b> We consider data release protocols for data $X=(S,U)$, where $S$ is sensitive; the released data $Y$ contains as much information about $X$ as possible, measured as $\operatorname{I}(X;Y)$, without leaking too much about $S$. We introduce the Robust Local Differential Privacy (RLDP) framework to measure privacy. This framework relies on the underlying distribution of the data, which needs to be estimated from available data. Robust privacy guarantees are ensuring privacy for all distributions in a given set $\mathcal{F}$, for which we study two cases: when $\mathcal{F}$ is the set of all distributions, and when $\mathcal{F}$ is a confidence set arising from a $χ^2$ test on a publicly available dataset. In the former case we introduce a new release protocol which we prove to be optimal in the low privacy regime. In the latter case we present four algorithms that construct RLDP protocols from a given dataset. One of these approximates $\mathcal{F}$ by a polytope and uses results from robust optimisation to yield high utility release protocols. However, this algorithm relies on vertex enumeration and becomes computationally inaccessible for large input spaces. The other three algorithms are low-complexity and build on randomised response. Experiments verify that all four algorithms offer significantly improved utility over regular LDP.</p>
  </details>
</div>



<h2>2020-09</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2009.08000v3">The Limits of Pan Privacy and Shuffle Privacy for Learning and Estimation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2020-09-17T01:15:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Albert Cheu, Jonathan Ullman</p>
    <p><b>Summary:</b> There has been a recent wave of interest in intermediate trust models for differential privacy that eliminate the need for a fully trusted central data collector, but overcome the limitations of local differential privacy. This interest has led to the introduction of the shuffle model (Cheu et al., EUROCRYPT 2019; Erlingsson et al., SODA 2019) and revisiting the pan-private model (Dwork et al., ITCS 2010). The message of this line of work is that, for a variety of low-dimensional problems -- such as counts, means, and histograms -- these intermediate models offer nearly as much power as central differential privacy. However, there has been considerably less success using these models for high-dimensional learning and estimation problems. In this work, we show that, for a variety of high-dimensional learning and estimation problems, both the shuffle model and the pan-private model inherently incur an exponential price in sample complexity relative to the central model. For example, we show that, private agnostic learning of parity functions over $d$ bits requires $Ω(2^{d/2})$ samples in these models, and privately selecting the most common attribute from a set of $d$ choices requires $Ω(d^{1/2})$ samples, both of which are exponential separations from the central model. Our work gives the first non-trivial lower bounds for these problems for both the pan-private model and the general multi-message shuffle model.</p>
  </details>
</div>



<h2>2023-06</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2306.13054v2">Quantum Pufferfish Privacy: A Flexible Privacy Framework for Quantum Systems</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2023-06-22T17:21:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Theshani Nuradha, Ziv Goldfeld, Mark M. Wilde</p>
    <p><b>Summary:</b> We propose a versatile privacy framework for quantum systems, termed quantum pufferfish privacy (QPP). Inspired by classical pufferfish privacy, our formulation generalizes and addresses limitations of quantum differential privacy by offering flexibility in specifying private information, feasible measurements, and domain knowledge. We show that QPP can be equivalently formulated in terms of the Datta-Leditzky information spectrum divergence, thus providing the first operational interpretation thereof. We reformulate this divergence as a semi-definite program and derive several properties of it, which are then used to prove convexity, composability, and post-processing of QPP mechanisms. Parameters that guarantee QPP of the depolarization mechanism are also derived. We analyze the privacy-utility tradeoff of general QPP mechanisms and, again, study the depolarization mechanism as an explicit instance. The QPP framework is then applied to privacy auditing for identifying privacy violations via a hypothesis testing pipeline that leverages quantum algorithms. Connections to quantum fairness and other quantum divergences are also explored and several variants of QPP are examined.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2306.13214v2">Prior-itizing Privacy: A Bayesian Approach to Setting the Privacy Budget in Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2023-06-19T22:23:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zeki Kazan, Jerome P. Reiter</p>
    <p><b>Summary:</b> When releasing outputs from confidential data, agencies need to balance the analytical usefulness of the released data with the obligation to protect data subjects' confidentiality. For releases satisfying differential privacy, this balance is reflected by the privacy budget, $\varepsilon$. We provide a framework for setting $\varepsilon$ based on its relationship with Bayesian posterior probabilities of disclosure. The agency responsible for the data release decides how much posterior risk it is willing to accept at various levels of prior risk, which implies a unique $\varepsilon$. Agencies can evaluate different risk profiles to determine one that leads to an acceptable trade-off in risk and utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2306.10923v1">Toward the Cure of Privacy Policy Reading Phobia: Automated Generation of Privacy Nutrition Labels From Privacy Policies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2023-06-19T13:33:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shidong Pan, Thong Hoang, Dawen Zhang, Zhenchang Xing, Xiwei Xu, Qinghua Lu, Mark Staples</p>
    <p><b>Summary:</b> Software applications have become an omnipresent part of modern society. The consequent privacy policies of these applications play a significant role in informing customers how their personal information is collected, stored, and used. However, customers rarely read and often fail to understand privacy policies because of the ``Privacy Policy Reading Phobia'' (PPRP). To tackle this emerging challenge, we propose the first framework that can automatically generate privacy nutrition labels from privacy policies. Based on our ground truth applications about the Data Safety Report from the Google Play app store, our framework achieves a 0.75 F1-score on generating first-party data collection practices and an average of 0.93 F1-score on general security practices. We also analyse the inconsistencies between ground truth and curated privacy nutrition labels on the market, and our framework can detect 90.1% under-claim issues. Our framework demonstrates decent generalizability across different privacy nutrition label formats, such as Google's Data Safety Report and Apple's App Privacy Details.</p>
  </details>
</div>



<h2>2022-08</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2208.04591v2">Stronger Privacy Amplification by Shuffling for Rényi and Approximate Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2022-08-09T08:13:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vitaly Feldman, Audra McMillan, Kunal Talwar</p>
    <p><b>Summary:</b> The shuffle model of differential privacy has gained significant interest as an intermediate trust model between the standard local and central models [EFMRTT19; CSUZZ19]. A key result in this model is that randomly shuffling locally randomized data amplifies differential privacy guarantees. Such amplification implies substantially stronger privacy guarantees for systems in which data is contributed anonymously [BEMMRLRKTS17].
  In this work, we improve the state of the art privacy amplification by shuffling results both theoretically and numerically. Our first contribution is the first asymptotically optimal analysis of the Rényi differential privacy parameters for the shuffled outputs of LDP randomizers. Our second contribution is a new analysis of privacy amplification by shuffling. This analysis improves on the techniques of [FMT20] and leads to tighter numerical bounds in all parameter settings.</p>
  </details>
</div>



<h2>2021-03</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2103.07567v2">Privacy Regularization: Joint Privacy-Utility Optimization in Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2021-03-12T23:17:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fatemehsadat Mireshghallah, Huseyin A. Inan, Marcello Hasegawa, Victor Rühle, Taylor Berg-Kirkpatrick, Robert Sim</p>
    <p><b>Summary:</b> Neural language models are known to have a high capacity for memorization of training samples. This may have serious privacy implications when training models on user content such as email correspondence. Differential privacy (DP), a popular choice to train models with privacy guarantees, comes with significant costs in terms of utility degradation and disparate impact on subgroups of users. In this work, we introduce two privacy-preserving regularization methods for training language models that enable joint optimization of utility and privacy through (1) the use of a discriminator and (2) the inclusion of a triplet-loss term. We compare our methods with DP through extensive evaluation. We show the advantages of our regularizers with favorable utility-privacy trade-off, faster training with the ability to tap into existing optimization approaches, and ensuring uniform treatment of under-represented subgroups.</p>
  </details>
</div>



<h2>2015-10</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1510.03311v1">Inverse Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2015-10-12T14:44:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuri Gurevich, Efim Hudis, Jeannette M. Wing</p>
    <p><b>Summary:</b> An item of your personal information is inversely private if some party has access to it but you do not. We analyze the provenance of inversely private information and its rise to dominance over other kinds of personal information. In a nutshell, the inverse privacy problem is unjustified inaccessibility to you of your inversely private information. We argue that the inverse privacy problem has a market-based solution.</p>
  </details>
</div>



<h2>2025-05</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2505.15721v1">Privacy-Preserving Conformal Prediction Under Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2025-05-21T16:29:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Coby Penso, Bar Mahpud, Jacob Goldberger, Or Sheffet</p>
    <p><b>Summary:</b> Conformal prediction (CP) provides sets of candidate classes with a guaranteed probability of containing the true class. However, it typically relies on a calibration set with clean labels. We address privacy-sensitive scenarios where the aggregator is untrusted and can only access a perturbed version of the true labels. We propose two complementary approaches under local differential privacy (LDP). In the first approach, users do not access the model but instead provide their input features and a perturbed label using a k-ary randomized response. In the second approach, which enforces stricter privacy constraints, users add noise to their conformity score by binary search response. This method requires access to the classification model but preserves both data and label privacy. Both approaches compute the conformal threshold directly from noisy data without accessing the true labels. We prove finite-sample coverage guarantees and demonstrate robust coverage even under severe randomization. This approach unifies strong local privacy with predictive uncertainty control, making it well-suited for sensitive applications such as medical imaging or large language model queries, regardless of whether users can (or are willing to) compute their own scores.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2505.05648v1">Privacy-Preserving Transformers: SwiftKey's Differential Privacy Implementation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-05-08T21:08:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abdelrahman Abouelenin, Mohamed Abdelrehim, Raffy Fahim, Amr Hendy, Mohamed Afify</p>
    <p><b>Summary:</b> In this paper we train a transformer using differential privacy (DP) for language modeling in SwiftKey. We run multiple experiments to balance the trade-off between the model size, run-time speed and accuracy. We show that we get small and consistent gains in the next-word-prediction and accuracy with graceful increase in memory and speed compared to the production GRU. This is obtained by scaling down a GPT2 architecture to fit the required size and a two stage training process that builds a seed model on general data and DP finetunes it on typing data. The transformer is integrated using ONNX offering both flexibility and efficiency.</p>
  </details>
</div>



<h2>2024-12</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.19291v2">RAG with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-12-26T17:34:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nicolas Grislain</p>
    <p><b>Summary:</b> Retrieval-Augmented Generation (RAG) has emerged as the dominant technique to provide \emph{Large Language Models} (LLM) with fresh and relevant context, mitigating the risk of hallucinations and improving the overall quality of responses in environments with large and fast moving knowledge bases. However, the integration of external documents into the generation process raises significant privacy concerns. Indeed, when added to a prompt, it is not possible to guarantee a response will not inadvertently expose confidential data, leading to potential breaches of privacy and ethical dilemmas. This paper explores a practical solution to this problem suitable to general knowledge extraction from personal data. It shows \emph{differentially private token generation} is a viable approach to private RAG.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.16916v3">On the Differential Privacy and Interactivity of Privacy Sandbox Reports</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-12-22T08:22:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Badih Ghazi, Charlie Harrison, Arpana Hosabettu, Pritish Kamath, Alexander Knop, Ravi Kumar, Ethan Leeman, Pasin Manurangsi, Mariana Raykova, Vikas Sahu, Phillipp Schoppmann</p>
    <p><b>Summary:</b> The Privacy Sandbox initiative from Google includes APIs for enabling privacy-preserving advertising functionalities as part of the effort around limiting third-party cookies. In particular, the Private Aggregation API (PAA) and the Attribution Reporting API (ARA) can be used for ad measurement while providing different guardrails for safeguarding user privacy, including a framework for satisfying differential privacy (DP). In this work, we provide an abstract model for analyzing the privacy of these APIs and show that they satisfy a formal DP guarantee under certain assumptions. Our analysis handles the case where both the queries and database can change interactively based on previous responses from the API.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.10612v1">Meeting Utility Constraints in Differential Privacy: A Privacy-Boosting Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2024-12-13T23:34:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bo Jiang, Wanrong Zhang, Donghang Lu, Jian Du, Sagar Sharma, Qiang Yan</p>
    <p><b>Summary:</b> Data engineering often requires accuracy (utility) constraints on results, posing significant challenges in designing differentially private (DP) mechanisms, particularly under stringent privacy parameter $ε$. In this paper, we propose a privacy-boosting framework that is compatible with most noise-adding DP mechanisms. Our framework enhances the likelihood of outputs falling within a preferred subset of the support to meet utility requirements while enlarging the overall variance to reduce privacy leakage. We characterize the privacy loss distribution of our framework and present the privacy profile formulation for $(ε,δ)$-DP and Rényi DP (RDP) guarantees. We study special cases involving data-dependent and data-independent utility formulations. Through extensive experiments, we demonstrate that our framework achieves lower privacy loss than standard DP mechanisms under utility constraints. Notably, our approach is particularly effective in reducing privacy loss with large query sensitivity relative to the true answer, offering a more practical and flexible approach to designing differentially private mechanisms that meet specific utility constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.05183v1">Privacy Drift: Evolving Privacy Concerns in Incremental Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-12-06T17:04:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sayyed Farid Ahamed, Soumya Banerjee, Sandip Roy, Aayush Kapoor, Marc Vucovich, Kevin Choi, Abdul Rahman, Edward Bowen, Sachin Shetty</p>
    <p><b>Summary:</b> In the evolving landscape of machine learning (ML), Federated Learning (FL) presents a paradigm shift towards decentralized model training while preserving user data privacy. This paper introduces the concept of ``privacy drift", an innovative framework that parallels the well-known phenomenon of concept drift. While concept drift addresses the variability in model accuracy over time due to changes in the data, privacy drift encapsulates the variation in the leakage of private information as models undergo incremental training. By defining and examining privacy drift, this study aims to unveil the nuanced relationship between the evolution of model performance and the integrity of data privacy. Through rigorous experimentation, we investigate the dynamics of privacy drift in FL systems, focusing on how model updates and data distribution shifts influence the susceptibility of models to privacy attacks, such as membership inference attacks (MIA). Our results highlight a complex interplay between model accuracy and privacy safeguards, revealing that enhancements in model performance can lead to increased privacy risks. We provide empirical evidence from experiments on customized datasets derived from CIFAR-100 (Canadian Institute for Advanced Research, 100 classes), showcasing the impact of data and concept drift on privacy. This work lays the groundwork for future research on privacy-aware machine learning, aiming to achieve a delicate balance between model accuracy and data privacy in decentralized environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.04697v3">Privacy-Preserving Retrieval-Augmented Generation with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-12-06T01:20:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tatsuki Koga, Ruihan Wu, Zhiyuan Zhang, Kamalika Chaudhuri</p>
    <p><b>Summary:</b> With the recent remarkable advancement of large language models (LLMs), there has been a growing interest in utilizing them in the domains with highly sensitive data that lies outside their training data. For this purpose, retrieval-augmented generation (RAG) is particularly effective -- it assists LLMs by directly providing relevant information from the external knowledge sources. However, without extra privacy safeguards, RAG outputs risk leaking sensitive information from the external data source. In this work, we explore RAG under differential privacy (DP), a formal guarantee of data privacy. The main challenge with differentially private RAG is how to generate long accurate answers within a moderate privacy budget. We address this by proposing an algorithm that smartly spends privacy budget only for the tokens that require the sensitive information and uses the non-private LLM for other tokens. Our extensive empirical evaluations reveal that our algorithm outperforms the non-RAG baseline under a reasonable privacy budget of $ε\approx 10$ across different models and datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2412.02578v1">Private Linear Regression with Differential Privacy and PAC Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-12-03T17:04:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hillary Yang</p>
    <p><b>Summary:</b> Linear regression is a fundamental tool for statistical analysis, which has motivated the development of linear regression methods that satisfy provable privacy guarantees so that the learned model reveals little about any one data point used to construct it. Most existing privacy-preserving linear regression methods rely on the well-established framework of differential privacy, while the newly proposed PAC Privacy has not yet been explored in this context. In this paper, we systematically compare linear regression models trained with differential privacy and PAC privacy across three real-world datasets, observing several key findings that impact the performance of privacy-preserving linear regression.</p>
  </details>
</div>



<h2>2020-06</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2006.08522v3">Transparent Privacy is Principled Privacy</a></h3>
   
  <p><b>Published on:</b> 2020-06-15T16:30:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruobin Gong</p>
    <p><b>Summary:</b> In a technical treatment, this article establishes the necessity of transparent privacy for drawing unbiased statistical inference for a wide range of scientific questions. Transparency is a distinct feature enjoyed by differential privacy: the probabilistic mechanism with which the data are privatized can be made public without sabotaging the privacy guarantee. Uncertainty due to transparent privacy may be conceived as a dynamic and controllable component from the total survey error perspective. As the 2020 U.S. Decennial Census adopts differential privacy, constraints imposed on the privatized data products through optimization constitute a threat to transparency and result in limited statistical usability. Transparent privacy presents a viable path toward principled inference from privatized data releases, and shows great promise toward improved reproducibility, accountability, and public trust in modern data curation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2006.06535v1">Privacy Adversarial Network: Representation Learning for Mobile Data Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2020-06-08T09:42:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sicong Liu, Junzhao Du, Anshumali Shrivastava, Lin Zhong</p>
    <p><b>Summary:</b> The remarkable success of machine learning has fostered a growing number of cloud-based intelligent services for mobile users. Such a service requires a user to send data, e.g. image, voice and video, to the provider, which presents a serious challenge to user privacy. To address this, prior works either obfuscate the data, e.g. add noise and remove identity information, or send representations extracted from the data, e.g. anonymized features. They struggle to balance between the service utility and data privacy because obfuscated data reduces utility and extracted representation may still reveal sensitive information.
  This work departs from prior works in methodology: we leverage adversarial learning to a better balance between privacy and utility. We design a \textit{representation encoder} that generates the feature representations to optimize against the privacy disclosure risk of sensitive information (a measure of privacy) by the \textit{privacy adversaries}, and concurrently optimize with the task inference accuracy (a measure of utility) by the \textit{utility discriminator}. The result is the privacy adversarial network (\systemname), a novel deep model with the new training algorithm, that can automatically learn representations from the raw data.
  Intuitively, PAN adversarially forces the extracted representations to only convey the information required by the target task. Surprisingly, this constitutes an implicit regularization that actually improves task accuracy. As a result, PAN achieves better utility and better privacy at the same time! We report extensive experiments on six popular datasets and demonstrate the superiority of \systemname compared with alternative methods reported in prior work.</p>
  </details>
</div>



<h2>2011-09</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1109.2486v1">Quantum privacy witness</a></h3>
  
  <p><b>Published on:</b> 2011-09-12T14:47:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Konrad Banaszek, Karol Horodecki, Paweł Horodecki</p>
    <p><b>Summary:</b> While it is usually known that the mean value of a single observable is enough to detect entanglement or its distillability, the counterpart of such an approach in the case of quatum privacy has been missing. Here we develop the concept of a privacy witness, i.e. a single observable that may detect presence of the secure key even in the case of bound entanglement. Then we develop the notion of secret key estimation based on few observables and discuss the witness decomposition into local measurements. The surprising property of the witness is that with the help of a low number of product mesurements involved it may still report the key values that are {\it strictly above} distillable entanglement of the state. For an exemplary four-qubit state studied in a recent experiment [K. Dobek {\em et al.}, Phys. Rev. Lett. {\bf 106}, 030501 (2011)] this means 6 Pauli operator product measurements versus 81 needed to carry out the complete quantum state tomography. The present approach may be viewed as a paradigm for the general program of experimentally friendly detection and estimation of task-dedicated quantum entanglement.</p>
  </details>
</div>



<h2>2019-12</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1912.04042v1">Element Level Differential Privacy: The Right Granularity of Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2019-12-05T23:05:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hilal Asi, John Duchi, Omid Javidbakht</p>
    <p><b>Summary:</b> Differential Privacy (DP) provides strong guarantees on the risk of compromising a user's data in statistical learning applications, though these strong protections make learning challenging and may be too stringent for some use cases. To address this, we propose element level differential privacy, which extends differential privacy to provide protection against leaking information about any particular "element" a user has, allowing better utility and more robust results than classical DP. By carefully choosing these "elements," it is possible to provide privacy protections at a desired granularity. We provide definitions, associated privacy guarantees, and analysis to identify the tradeoffs with the new definition; we also develop several private estimation and learning methodologies, providing careful examples for item frequency and M-estimation (empirical risk minimization) with concomitant privacy and utility analysis. We complement our theoretical and methodological advances with several real-world applications, estimating histograms and fitting several large-scale prediction models, including deep networks.</p>
  </details>
</div>



<h2>2023-05</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2305.05227v4">Privacy in Speech Technology</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36">
  <p><b>Published on:</b> 2023-05-09T07:41:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tom Bäckström</p>
    <p><b>Summary:</b> Speech technology for communication, accessing information, and services has rapidly improved in quality. It is convenient and appealing because speech is the primary mode of communication for humans. Such technology, however, also presents proven threats to privacy. Speech is a tool for communication and it will thus inherently contain private information. Importantly, it however also contains a wealth of side information, such as information related to health, emotions, affiliations, and relationships, all of which are private. Exposing such private information can lead to serious threats such as price gouging, harassment, extortion, and stalking. This paper is a tutorial on privacy issues related to speech technology, modeling their threats, approaches for protecting users' privacy, measuring the performance of privacy-protecting methods, perception of privacy as well as societal and legal consequences. In addition to a tutorial overview, it also presents lines for further development where improvements are most urgently needed.</p>
  </details>
</div>



<h2>2022-10</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2210.03458v4">PAC Privacy: Automatic Privacy Measurement and Control of Data Processing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2022-10-07T11:01:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hanshen Xiao, Srinivas Devadas</p>
    <p><b>Summary:</b> We propose and study a new privacy definition, termed Probably Approximately Correct (PAC) Privacy. PAC Privacy characterizes the information-theoretic hardness to recover sensitive data given arbitrary information disclosure/leakage during/after any processing. Unlike the classic cryptographic definition and Differential Privacy (DP), which consider the adversarial (input-independent) worst case, PAC Privacy is a simulatable metric that quantifies the instance-based impossibility of inference. A fully automatic analysis and proof generation framework is proposed: security parameters can be produced with arbitrarily high confidence via Monte-Carlo simulation for any black-box data processing oracle. This appealing automation property enables analysis of complicated data processing, where the worst-case proof in the classic privacy regime could be loose or even intractable. Moreover, we show that the produced PAC Privacy guarantees enjoy simple composition bounds and the automatic analysis framework can be implemented in an online fashion to analyze the composite PAC Privacy loss even under correlated randomness. On the utility side, the magnitude of (necessary) perturbation required in PAC Privacy is not lower bounded by Theta(\sqrt{d}) for a d-dimensional release but could be O(1) for many practical data processing tasks, which is in contrast to the input-independent worst-case information-theoretic lower bound. Example applications of PAC Privacy are included with comparisons to existing works.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2210.00597v4">Composition of Differential Privacy & Privacy Amplification by Subsampling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2022-10-02T18:22:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Thomas Steinke</p>
    <p><b>Summary:</b> This chapter is meant to be part of the book "Differential Privacy for Artificial Intelligence Applications." We give an introduction to the most important property of differential privacy -- composition: running multiple independent analyses on the data of a set of people will still be differentially private as long as each of the analyses is private on its own -- as well as the related topic of privacy amplification by subsampling. This chapter introduces the basic concepts and gives proofs of the key results needed to apply these tools in practice.</p>
  </details>
</div>



<h2>2025-10</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.11299v2">How to Get Actual Privacy and Utility from Privacy Models: the k-Anonymity and Differential Privacy Families</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2025-10-13T11:41:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Josep Domingo-Ferrer, David Sánchez</p>
    <p><b>Summary:</b> Privacy models were introduced in privacy-preserving data publishing and statistical disclosure control with the promise to end the need for costly empirical assessment of disclosure risk. We examine how well this promise is kept by the main privacy models. We find they may fail to provide adequate protection guarantees because of problems in their definition or incur unacceptable trade-offs between privacy protection and utility preservation. Specifically, k-anonymity may not entirely exclude disclosure if enforced with deterministic mechanisms or without constraints on the confidential values. On the other hand, differential privacy (DP) incurs unacceptable utility loss for small budgets and its privacy guarantee becomes meaningless for large budgets. In the latter case, an ex post empirical assessment of disclosure risk becomes necessary, undermining the main appeal of privacy models. Whereas the utility preservation of DP can only be improved by relaxing its privacy guarantees, we argue that a semantic reformulation of k-anonymity can offer more robust privacy without losing utility with respect to traditional syntactic k-anonymity.</p>
  </details>
</div>



<h2>2022-05</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2205.03336v1">Statistical Data Privacy: A Song of Privacy and Utility</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2022-05-06T16:17:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aleksandra Slavkovic, Jeremy Seeman</p>
    <p><b>Summary:</b> To quantify trade-offs between increasing demand for open data sharing and concerns about sensitive information disclosure, statistical data privacy (SDP) methodology analyzes data release mechanisms which sanitize outputs based on confidential data. Two dominant frameworks exist: statistical disclosure control (SDC), and more recent, differential privacy (DP). Despite framing differences, both SDC and DP share the same statistical problems at its core. For inference problems, we may either design optimal release mechanisms and associated estimators that satisfy bounds on disclosure risk, or we may adjust existing sanitized output to create new optimal estimators. Both problems rely on uncertainty quantification in evaluating risk and utility. In this review, we discuss the statistical foundations common to both SDC and DP, highlight major developments in SDP, and present exciting open research problems in private inference.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2205.03083v1">Heal the Privacy: Functional Encryption and Privacy-Preserving Analytics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2022-05-06T09:00:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alexandros Bakas, Antonis Michalas</p>
    <p><b>Summary:</b> Secure cloud storage is an issue of paramount importance that both businesses and end-users should take into consideration before moving their data to, potentially, untrusted clouds. Migrating data to the cloud raises multiple privacy issues, as they are completely controlled by a cloud provider. Hence, an untrusted cloud provider can potentially breach users; privacy and gain access to sensitive information. The problem becomes even more pronounced when the could provider is required to store a statistical database and periodically publish analytics. In this work, we first present a detailed example showing that the use of cryptography is not enough to ensure the privacy of individuals. Then, we design a hybrid protocol based on Functional Encryption and Differential Privacy that allows the computations of statistics in a privacy-preserving way.</p>
  </details>
</div>



<h2>2014-02</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1402.3757v3">On the Relation Between Identifiability, Differential Privacy and Mutual-Information Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2014-02-16T05:43:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Weina Wang, Lei Ying, Junshan Zhang</p>
    <p><b>Summary:</b> This paper investigates the relation between three different notions of privacy: identifiability, differential privacy and mutual-information privacy. Under a unified privacy-distortion framework, where the distortion is defined to be the Hamming distance of the input and output databases, we establish some fundamental connections between these three privacy notions. Given a distortion level $D$, define $ε_{\mathrm{i}}^*(D)$ to be the smallest (best) identifiability level, and $ε_{\mathrm{d}}^*(D)$ to be the smallest differential privacy level. We characterize $ε_{\mathrm{i}}^*(D)$ and $ε_{\mathrm{d}}^*(D)$, and prove that $ε_{\mathrm{i}}^*(D)-ε_X\leε_{\mathrm{d}}^*(D)\leε_{\mathrm{i}}^*(D)$ for $D$ in some range, where $ε_X$ is a constant depending on the distribution of the original database $X$, and diminishes to zero when the distribution of $X$ is uniform. Furthermore, we show that identifiability and mutual-information privacy are consistent in the sense that given distortion level $D$, the mechanism that optimizes the mutual-information privacy also minimizes the identifiability level.</p>
  </details>
</div>



<h2>2023-10</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2311.00066v1">Assessing Mobile Application Privacy: A Quantitative Framework for Privacy Measurement</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2023-10-31T18:12:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joao Marono, Catarina Silva, Joao P. Barraca, Vitor Cunha, Paulo Salvador</p>
    <p><b>Summary:</b> The proliferation of mobile applications and the subsequent sharing of personal data with service and application providers have given rise to substantial privacy concerns. Application marketplaces have introduced mechanisms to conform to regulations and provide individuals with control over their data. However, a notable absence persists regarding clear indications, labels or scores elucidating the privacy implications of these applications. In response to this challenge, this paper introduces a privacy quantification framework. The purpose of this framework is to systematically evaluate the level of privacy risk when using particular Android applications. The main goal is to provide individuals with qualitative labels to make informed decisions about their privacy. This work aims to contribute to a digital environment that prioritizes privacy, promotes informed decision-making, and endorses the privacy-preserving design principles incorporation.</p>
  </details>
</div>



<h2>2019-09</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1909.04421v4">Privacy-Preserving Bandits</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B"> 
  <p><b>Published on:</b> 2019-09-10T11:39:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohammad Malekzadeh, Dimitrios Athanasakis, Hamed Haddadi, Benjamin Livshits</p>
    <p><b>Summary:</b> Contextual bandit algorithms~(CBAs) often rely on personal data to provide recommendations. Centralized CBA agents utilize potentially sensitive data from recent interactions to provide personalization to end-users. Keeping the sensitive data locally, by running a local agent on the user's device, protects the user's privacy, however, the agent requires longer to produce useful recommendations, as it does not leverage feedback from other users. This paper proposes a technique we call Privacy-Preserving Bandits (P2B); a system that updates local agents by collecting feedback from other local agents in a differentially-private manner. Comparisons of our proposed approach with a non-private, as well as a fully-private (local) system, show competitive performance on both synthetic benchmarks and real-world data. Specifically, we observed only a decrease of 2.6% and 3.6% in multi-label classification accuracy, and a CTR increase of 0.0025 in online advertising for a privacy budget $ε\approx 0.693$. These results suggest P2B is an effective approach to challenges arising in on-device privacy-preserving personalization.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1909.01862v1">Privacy with Surgical Robotics: Challenges in Applying Contextual Privacy Theory</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E">
  <p><b>Published on:</b> 2019-09-04T15:09:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ryan Shah, Shishir Nagaraja</p>
    <p><b>Summary:</b> The use of connected surgical robotics to automate medical procedures presents new privacy challenges. We argue that conventional patient consent protocols no longer work. Indeed robots that replace human surgeons take on an extraordinary level of responsibility. Surgeons undergo years of training and peer review in a strongly regulated environment, and derive trust via a patient's faith in the hospital system. Robots on the other hand derive trust differently, via the integrity of the software that governs their operation. From a privacy perspective, there are two fundamental shifts. First, the threat model has shifted from one where the humans involved were untrusted to one where the robotic software is untrusted. Second, the basic unit of privacy control is no longer a medical record, but is replaced by four new basic units: the subject on which the robot is taking action; the tools used by the robot; the sensors (i.e data) the robot can access; and, finally access to monitoring and calibration services which afford correct operation of the robot. We suggest that contextual privacy provides useful theoretical tools to solve the privacy problems posed by surgical robots. However, it also poses some challenges: not least that the complexity of the contextual-privacy policies, if rigorously specified to achieve verification and enforceability, will be exceedingly high to directly expose to humans that review contextual privacy policies. A medical robot works with both information and physical material. While informational norms allow for judgements about contextual integrity and the transmission principle governs the constraints applied on information transfer, nothing is said about material property. Certainly, contextual privacy provides an anchor for useful notions of privacy in this scenario and thus should be considered to be extended to cover both information and material flows.</p>
  </details>
</div>



<h2>2018-10</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1810.09152v2">PriSTE: From Location Privacy to Spatiotemporal Event Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2018-10-22T09:41:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yang Cao, Yonghui Xiao, Li Xiong, Liquan Bai</p>
    <p><b>Summary:</b> Location privacy-preserving mechanisms (LPPMs) have been extensively studied for protecting a user's location at each time point or a sequence of locations with different timestamps (i.e., a trajectory). We argue that existing LPPMs are not capable of protecting the sensitive information in user's spatiotemporal activities, such as "visited hospital in the last week" or "regularly commuting between Address 1 and Address 2 every morning and afternoon" (it is easy to infer that Addresses 1 and 2 may be home and office). We define such privacy as \textit{Spatiotemporal Event Privacy}, which can be formalized as Boolean expressions between location and time predicates. To understand how much spatiotemporal event privacy that existing LPPMs can provide, we first formally define spatiotemporal event privacy by extending the notion of differential privacy, and then provide a framework for calculating the spatiotemporal event privacy loss of a given LPPM under attackers who have knowledge of user's mobility pattern. We also show a case study of utilizing our framework to convert the state-of-the-art mechanism for location privacy, i.e., Planner Laplace Mechanism for Geo-indistinguishability, into one protecting spatiotemporal event privacy. Our experiments on real-life and synthetic data verified that the proposed method is effective and efficient.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1810.00877v2">Privacy and Utility Tradeoff in Approximate Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2018-10-01T17:54:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Quan Geng, Wei Ding, Ruiqi Guo, Sanjiv Kumar</p>
    <p><b>Summary:</b> We characterize the minimum noise amplitude and power for noise-adding mechanisms in $(ε, δ)$-differential privacy for single real-valued query function. We derive new lower bounds using the duality of linear programming, and new upper bounds by proposing a new class of $(ε,δ)$-differentially private mechanisms, the \emph{truncated Laplacian} mechanisms. We show that the multiplicative gap of the lower bounds and upper bounds goes to zero in various high privacy regimes, proving the tightness of the lower and upper bounds and thus establishing the optimality of the truncated Laplacian mechanism. In particular, our results close the previous constant multiplicative gap in the discrete setting. Numeric experiments show the improvement of the truncated Laplacian mechanism over the optimal Gaussian mechanism in all privacy regimes.</p>
  </details>
</div>



<h2>2020-03</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2003.00973v2">Differential Privacy at Risk: Bridging Randomness and Privacy Budget</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> 
  <p><b>Published on:</b> 2020-03-02T15:44:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ashish Dandekar, Debabrota Basu, Stephane Bressan</p>
    <p><b>Summary:</b> The calibration of noise for a privacy-preserving mechanism depends on the sensitivity of the query and the prescribed privacy level. A data steward must make the non-trivial choice of a privacy level that balances the requirements of users and the monetary constraints of the business entity. We analyse roles of the sources of randomness, namely the explicit randomness induced by the noise distribution and the implicit randomness induced by the data-generation distribution, that are involved in the design of a privacy-preserving mechanism. The finer analysis enables us to provide stronger privacy guarantees with quantifiable risks. Thus, we propose privacy at risk that is a probabilistic calibration of privacy-preserving mechanisms. We provide a composition theorem that leverages privacy at risk. We instantiate the probabilistic calibration for the Laplace mechanism by providing analytical results. We also propose a cost model that bridges the gap between the privacy level and the compensation budget estimated by a GDPR compliant business entity. The convexity of the proposed cost model leads to a unique fine-tuning of privacy level that minimises the compensation budget. We show its effectiveness by illustrating a realistic scenario that avoids overestimation of the compensation budget by using privacy at risk for the Laplace mechanism. We quantitatively show that composition using the cost optimal privacy at risk provides stronger privacy guarantee than the classical advanced composition.</p>
  </details>
</div>



<h2>2008-04</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/0804.3752v1">The privacy implications of Bluetooth</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2008-04-23T16:00:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vassilis Kostakos</p>
    <p><b>Summary:</b> A substantial amount of research, as well as media hype, has surrounded RFID technology and its privacy implications. Currently, researchers and the media focus on the privacy threats posed by RFID, while consumer groups choose to boycott products bearing RFID tags. At the same, however, a very similar technology has quietly become part of our everyday lives: Bluetooth. In this paper we highlight the fact that Bluetooth is a widespread technology that has real privacy implications. Furthermore, we explore the applicability of RFID-based solutions to address these privacy implications.</p>
  </details>
</div>



<h2>2014-10</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1410.1920v1">Privacy Games</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB">
  <p><b>Published on:</b> 2014-10-07T21:31:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yiling Chen, Or Sheffet, Salil Vadhan</p>
    <p><b>Summary:</b> The problem of analyzing the effect of privacy concerns on the behavior of selfish utility-maximizing agents has received much attention lately. Privacy concerns are often modeled by altering the utility functions of agents to consider also their privacy loss. Such privacy aware agents prefer to take a randomized strategy even in very simple games in which non-privacy aware agents play pure strategies. In some cases, the behavior of privacy aware agents follows the framework of Randomized Response, a well-known mechanism that preserves differential privacy.
  Our work is aimed at better understanding the behavior of agents in settings where their privacy concerns are explicitly given. We consider a toy setting where agent A, in an attempt to discover the secret type of agent B, offers B a gift that one type of B agent likes and the other type dislikes. As opposed to previous works, B's incentive to keep her type a secret isn't the result of "hardwiring" B's utility function to consider privacy, but rather takes the form of a payment between B and A. We investigate three different types of payment functions and analyze B's behavior in each of the resulting games. As we show, under some payments, B's behavior is very different than the behavior of agents with hardwired privacy concerns and might even be deterministic. Under a different payment we show that B's BNE strategy does fall into the framework of Randomized Response.</p>
  </details>
</div>



<h2>2014-09</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1409.6831v1">The Application of Differential Privacy for Rank Aggregation: Privacy and Accuracy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2014-09-24T05:19:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shang Shang, Tiance Wang, Paul Cuff, Sanjeev Kulkarni</p>
    <p><b>Summary:</b> The potential risk of privacy leakage prevents users from sharing their honest opinions on social platforms. This paper addresses the problem of privacy preservation if the query returns the histogram of rankings. The framework of differential privacy is applied to rank aggregation. The error probability of the aggregated ranking is analyzed as a result of noise added in order to achieve differential privacy. Upper bounds on the error rates for any positional ranking rule are derived under the assumption that profiles are uniformly distributed. Simulation results are provided to validate the probabilistic analysis.</p>
  </details>
</div>



<h2>2025-09</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2509.17871v2">B-Privacy: Defining and Enforcing Privacy in Weighted Voting</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-09-22T15:11:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Samuel Breckenridge, Dani Vilardell, Andrés Fábrega, Amy Zhao, Patrick McCorry, Rafael Solari, Ari Juels</p>
    <p><b>Summary:</b> In traditional, one-vote-per-person voting systems, privacy equates with ballot secrecy: voting tallies are published, but individual voters' choices are concealed.
  Voting systems that weight votes in proportion to token holdings, though, are now prevalent in cryptocurrency and web3 systems. We show that these weighted-voting systems overturn existing notions of voter privacy. Our experiments demonstrate that even with secret ballots, publishing raw tallies often reveals voters' choices.
  Weighted voting thus requires a new framework for privacy. We introduce a notion called B-privacy whose basis is bribery, a key problem in voting systems today. B-privacy captures the economic cost to an adversary of bribing voters based on revealed voting tallies.
  We propose a mechanism to boost B-privacy by noising voting tallies. We prove bounds on its tradeoff between B-privacy and transparency, meaning reported-tally accuracy. Analyzing 3,582 proposals across 30 Decentralized Autonomous Organizations (DAOs), we find that the prevalence of large voters ("whales") limits the effectiveness of any B-Privacy-enhancing technique. However, our mechanism proves to be effective in cases without extreme voting weight concentration: among proposals requiring coalitions of $\geq5$ voters to flip outcomes, our mechanism raises B-privacy by a geometric mean factor of $4.1\times$.
  Our work offers the first principled guidance on transparency-privacy tradeoffs in weighted-voting systems, complementing existing approaches that focus on ballot secrecy and revealing fundamental constraints that voting weight concentration imposes on privacy mechanisms.</p>
  </details>
</div>



<h2>2005-02</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/quant-ph/0502010v1">Gaussian Operations and Privacy</a></h3>
  
  <p><b>Published on:</b> 2005-02-01T15:04:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Miguel Navascues, Antonio Acin</p>
    <p><b>Summary:</b> We consider the possibilities offered by Gaussian states and operations for two honest parties, Alice and Bob, to obtain privacy against a third eavesdropping party, Eve. We first extend the security analysis of the protocol proposed in M. Navascues et al., Phys. Rev. Lett. 94, 010502 (2005). Then, we prove that a generalized version of this protocol does not allow to distill a secret key out of bound entangled Gaussian states.</p>
  </details>
</div>



<h2>2017-12</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1712.08500v8">On Perfect Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2017-12-22T15:16:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Borzoo Rassouli, Deniz Gunduz</p>
    <p><b>Summary:</b> The problem of private data disclosure is studied from an information theoretic perspective. Considering a pair of dependent random variables $(X,Y)$, where $X$ and $Y$ denote the private and useful data, respectively, the following problem is addressed: What is the maximum information that can be revealed about $Y$ (measured by mutual information $I(Y;U)$, in which $U$ is the revealed data), while disclosing no information about $X$ (captured by the condition of statistical independence, i.e., $X\independent U$, and henceforth, called \textit{perfect privacy})? We analyze the supremization of \textit{utility}, i.e., $I(Y;U)$ under the condition of perfect privacy for two scenarios: \textit{output perturbation} and \textit{full data observation} models, which correspond to the cases where a Markov kernel, called \textit{privacy-preserving mapping}, applies to $Y$ and the pair $(X,Y)$, respectively. When both $X$ and $Y$ have a finite alphabet, the linear algebraic analysis involved in the solution provides some interesting results, such as upper/lower bounds on the size of the released alphabet and the maximum utility. Afterwards, it is shown that for the jointly Gaussian $(X,Y)$, perfect privacy is not possible in the output perturbation model in contrast to the full data observation model. Finally, an asymptotic analysis is provided to obtain the rate of released information when a sufficiently small leakage is allowed. In particular, in the context of output perturbation model, it is shown that this rate is always finite when perfect privacy is not feasible, and two lower bounds are provided for it; When perfect privacy is feasible, it is shown that under mild conditions, this rate becomes unbounded.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/1712.02193v2">Systematizing Genome Privacy Research: A Privacy-Enhancing Technologies Perspective</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2017-12-06T14:22:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alexandros Mittos, Bradley Malin, Emiliano De Cristofaro</p>
    <p><b>Summary:</b> Rapid advances in human genomics are enabling researchers to gain a better understanding of the role of the genome in our health and well-being, stimulating hope for more effective and cost efficient healthcare. However, this also prompts a number of security and privacy concerns stemming from the distinctive characteristics of genomic data. To address them, a new research community has emerged and produced a large number of publications and initiatives.
  In this paper, we rely on a structured methodology to contextualize and provide a critical analysis of the current knowledge on privacy-enhancing technologies used for testing, storing, and sharing genomic data, using a representative sample of the work published in the past decade. We identify and discuss limitations, technical challenges, and issues faced by the community, focusing in particular on those that are inherently tied to the nature of the problem and are harder for the community alone to address. Finally, we report on the importance and difficulty of the identified challenges based on an online survey of genome data privacy experts</p>
  </details>
</div>



<h2>2025-08</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.17135v1">Rao Differential Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-08-23T20:25:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Carlos Soto</p>
    <p><b>Summary:</b> Differential privacy (DP) has recently emerged as a definition of privacy to release private estimates. DP calibrates noise to be on the order of an individuals contribution. Due to the this calibration a private estimate obscures any individual while preserving the utility of the estimate. Since the original definition, many alternate definitions have been proposed. These alternates have been proposed for various reasons including improvements on composition results, relaxations, and formalizations. Nevertheless, thus far nearly all definitions of privacy have used a divergence of densities as the basis of the definition. In this paper we take an information geometry perspective towards differential privacy. Specifically, rather than define privacy via a divergence, we define privacy via the Rao distance. We show that our proposed definition of privacy shares the interpretation of previous definitions of privacy while improving on sequential composition.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2508.03413v1">Smart Car Privacy: Survey of Attacks and Privacy Issues</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-08-05T12:59:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Akshay Madhav Deshmukh</p>
    <p><b>Summary:</b> Automobiles are becoming increasingly important in our day to day life. Modern automobiles are highly computerized and hence potentially vulnerable to attack. Providing many wireless connectivity for vehicles enables a bridge between vehicles and their external environments. Such a connected vehicle solution is expected to be the next frontier for automotive revolution and the key to the evolution to next generation intelligent transportation systems. Vehicular Ad hoc Networks (VANETs) are emerging mobile ad hoc network technologies incorporating mobile routing protocols for inter-vehicle data communications to support intelligent transportation systems. Thus security and privacy are the major concerns in VANETs due to the mobility of the vehicles. Thus designing security mechanisms to remove adversaries from the network remarkably important in VANETs.
  This paper provides an overview of various vehicular network architectures. The evolution of security in modern vehicles. Various security and privacy attacks in VANETs with their defending mechanisms with examples and classify these mechanisms. It also provides an overview of various privacy implication that a vehicular network possess.</p>
  </details>
</div>

