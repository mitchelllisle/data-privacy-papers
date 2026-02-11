
<h2>2026-02</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.10100v1">Towards Explainable Federated Learning: Understanding the Impact of Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-02-10T18:58:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Júlio Oliveira, Rodrigo Ferreira, André Riker, Glaucio H. S. Carvalho, Eirini Eleni Tsilopoulou</p>
    <p><b>Summary:</b> Data privacy and eXplainable Artificial Intelligence (XAI) are two important aspects for modern Machine Learning systems. To enhance data privacy, recent machine learning models have been designed as a Federated Learning (FL) system. On top of that, additional privacy layers can be added, via Differential Privacy (DP). On the other hand, to improve explainability, ML must consider more interpretable approaches with reduced number of features and less complex internal architecture. In this context, this paper aims to achieve a machine learning (ML) model that combines enhanced data privacy with explainability. So, we propose a FL solution, called Federated EXplainable Trees with Differential Privacy (FEXT-DP), that: (i) is based on Decision Trees, since they are lightweight and have superior explainability than neural networks-based FL systems; (ii) provides additional layer of data privacy protection applying Differential Privacy (DP) to the Tree-Based model. However, there is a side effect adding DP: it harms the explainability of the system. So, this paper also presents the impact of DP protection on the explainability of the ML model. The carried out performance assessment shows improvements of FEXT-DP in terms of a faster training, i.e., numbers of rounds, Mean Squared Error and explainability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.09904v1">Safeguarding Privacy: Privacy-Preserving Detection of Mind Wandering and Disengagement Using Federated Learning in Online Education</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-02-10T15:40:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anna Bodonhelyi, Mengdi Wang, Efe Bozkir, Babette Bühler, Enkelejda Kasneci</p>
    <p><b>Summary:</b> Since the COVID-19 pandemic, online courses have expanded access to education, yet the absence of direct instructor support challenges learners' ability to self-regulate attention and engagement. Mind wandering and disengagement can be detrimental to learning outcomes, making their automated detection via video-based indicators a promising approach for real-time learner support. However, machine learning-based approaches often require sharing sensitive data, raising privacy concerns. Federated learning offers a privacy-preserving alternative by enabling decentralized model training while also distributing computational load. We propose a framework exploiting cross-device federated learning to address different manifestations of behavioral and cognitive disengagement during remote learning, specifically behavioral disengagement, mind wandering, and boredom. We fit video-based cognitive disengagement detection models using facial expressions and gaze features. By adopting federated learning, we safeguard users' data privacy through privacy-by-design and introduce a novel solution with the potential for real-time learner support. We further address challenges posed by eyeglasses by incorporating related features, enhancing overall model performance. To validate the performance of our approach, we conduct extensive experiments on five datasets and benchmark multiple federated learning algorithms. Our results show great promise for privacy-preserving educational technologies promoting learner engagement.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.09627v1">Parallel Composition for Statistical Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-02-10T10:13:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dennis Breutigam, Rüdiger Reischuk</p>
    <p><b>Summary:</b> Differential Privacy (DP) considers a scenario in which an adversary has almost complete information about the entries of a database. This worst-case assumption is likely to overestimate the privacy threat faced by an individual in practice. In contrast, Statistical Privacy (SP), as well as related notions such as noiseless privacy or limited background knowledge privacy, describe a setting in which the adversary knows the distribution of the database entries, but not their exact realizations. In this case, privacy analysis must account for the interaction between uncertainty induced by the entropy of the underlying distributions and privacy mechanisms that distort query answers, which can be highly non-trivial.
  This paper investigates this problem for multiple queries (composition). A privacy mechanism is proposed that is based on subsampling and randomly partitioning the database to bound the dependency among queries. This way for the first time, to the best of our knowledge, upper privacy bounds against limited adversaries are obtained without any further restriction on the database.
  These bounds show that in realistic application scenarios taking the entropy of distributions into account yields improvements of privacy and precision guarantees. We illustrate examples where for fixed privacy parameters and utility loss SP allows significantly more queries than DP.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.09357v1">Data Sharing with Endogenous Choices over Differential Privacy Levels</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-02-10T03:01:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Raef Bassily, Kate Donahue, Diptangshu Sen, Annuo Zhao, Juba Ziani</p>
    <p><b>Summary:</b> We study coalition formation for data sharing under differential privacy when agents have heterogeneous privacy costs. Each agent holds a sensitive data point and decides whether to participate in a data-sharing coalition and how much noise to add to their data. Privacy choices induce a fundamental trade-off: higher privacy reduces individual data-sharing costs but degrades data utility and statistical accuracy for the coalition. These choices generate externalities across agents, making both participation and privacy levels strategic. Our goal is to understand which coalitions are stable, how privacy choices shape equilibrium outcomes, and how decentralized data sharing compares to a centralized, socially optimal benchmark.
  We provide a comprehensive equilibrium analysis across a broad range of privacy-cost regimes, from decreasing costs (e.g., privacy amplification from pooling data) to increasing costs (e.g., greater exposure to privacy attacks in larger coalitions). We first characterize Nash equilibrium coalitions with endogenous privacy levels and show that equilibria may fail to exist and can be non-monotonic in problem parameters. We also introduce a weaker equilibrium notion called robust equilibrium (that allows more widespread equilibrium existence by equipping existing players in the coalition with the power to prevent or veto external players from joining) and fully characterize such equilibria. Finally, we analyze, for both Nash and robust equilibria, the efficiency relative to the social optimum in terms of social welfare and estimator accuracy. We derive bounds that depend sharply on the number of players, properties of the cost profile and how privacy costs scale with coalition size.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.09338v1">Privacy Amplification for BandMF via $b$-Min-Sep Subsampling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-02-10T02:10:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Andy Dong, Arun Ganesh</p>
    <p><b>Summary:</b> We study privacy amplification for BandMF, i.e., DP-SGD with correlated noise across iterations via a banded correlation matrix. We propose $b$-min-sep subsampling, a new subsampling scheme that generalizes Poisson and balls-in-bins subsampling, extends prior practical batching strategies for BandMF, and enables stronger privacy amplification than cyclic Poisson while preserving the structural properties needed for analysis. We give a near-exact privacy analysis using Monte Carlo accounting, based on a dynamic program that leverages the Markovian structure in the subsampling procedure. We show that $b$-min-sep matches cyclic Poisson subsampling in the high noise regime and achieves strictly better guarantees in the mid-to-low noise regime, with experimental results that bolster our claims. We further show that unlike previous BandMF subsampling schemes, our $b$-min-sep subsampling naturally extends to the multi-attribution user-level privacy setting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.09288v1">Measuring Privacy Risks and Tradeoffs in Financial Synthetic Data Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-02-10T00:14:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Michael Zuo, Inwon Kang, Stacy Patterson, Oshani Seneviratne</p>
    <p><b>Summary:</b> We explore the privacy-utility tradeoff of synthetic data generation schemes on tabular financial datasets, a domain characterized by high regulatory risk and severe class imbalance. We consider representative tabular data generators, including autoencoders, generative adversarial networks, diffusion, and copula synthesizers. To address the challenges of the financial domain, we provide novel privacy-preserving implementations of GAN and autoencoder synthesizers. We evaluate whether and how well the generators simultaneously achieve data quality, downstream utility, and privacy, with comparison across balanced and imbalanced input datasets. Our results offer insight into the distinct challenges of generating synthetic data from datasets that exhibit severe class imbalance and mixed-type attributes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.09273v1">The Price of Privacy For Approximating Max-CSP</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-02-09T23:16:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Prathamesh Dharangutte, Jingcheng Liu, Pasin Manurangsi, Akbar Rafiey, Phanu Vajanopath, Zongrui Zou</p>
    <p><b>Summary:</b> We study approximation algorithms for Maximum Constraint Satisfaction Problems (Max-CSPs) under differential privacy (DP) where the constraints are considered sensitive data. Information-theoretically, we aim to classify the best approximation ratios possible for a given privacy budget $\varepsilon$. In the high-privacy regime ($\varepsilon \ll 1$), we show that any $\varepsilon$-DP algorithm cannot beat a random assignment by more than $O(\varepsilon)$ in the approximation ratio. We devise a polynomial-time algorithm which matches this barrier under the assumptions that the instances are bounded-degree and triangle-free. Finally, we show that one or both of these assumptions can be removed for specific CSPs--such as Max-Cut or Max $k$-XOR--albeit at the cost of computational efficiency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.09254v1">Investigating Bystander Privacy in Chinese Smart Home Apps</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-02-09T22:38:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shijing He, Xuchen Wang, Yaxiong Lei, Chi Zhang, Ruba Abu-Salma, Jose Such</p>
    <p><b>Summary:</b> Bystander privacy in smart homes has been widely studied in Western contexts, yet it remains underexplored in non-Western countries such as China. In this study, we analyze 49 Chinese smart home apps using a mixed-methods approach, including privacy policy review, UX/UI evaluation, and assessment of Apple App Store privacy labels. While most apps nominally comply with national regulations, we identify significant gaps between written policies and actual implementation. Our traceability analysis highlights inconsistencies in data controls and a lack of transparency in data-sharing practices. Crucially, bystander privacy -- particularly for visitors and non-user individuals -- is largely absent from both policy documents and interface design. Additionally, discrepancies between privacy labels and actual data practices threaten user trust and undermine informed consent. We provide design recommendations to strengthen bystander protections, improve privacy-oriented UI transparency, and enhance the credibility of privacy labels, supporting the development of inclusive smart home ecosystems in non-Western contexts.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.08657v1">Two-Stage Data Synthesization: A Statistics-Driven Restricted Trade-off between Privacy and Prediction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2026-02-09T13:49:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaotong Liu, Shao-Bo Lin, Jun Fan, Ding-Xuan Zhou</p>
    <p><b>Summary:</b> Synthetic data have gained increasing attention across various domains, with a growing emphasis on their performance in downstream prediction tasks. However, most existing synthesis strategies focus on maintaining statistical information. Although some studies address prediction performance guarantees, their single-stage synthesis designs make it challenging to balance the privacy requirements that necessitate significant perturbations and the prediction performance that is sensitive to such perturbations. We propose a two-stage synthesis strategy. In the first stage, we introduce a synthesis-then-hybrid strategy, which involves a synthesis operation to generate pure synthetic data, followed by a hybrid operation that fuses the synthetic data with the original data. In the second stage, we present a kernel ridge regression (KRR)-based synthesis strategy, where a KRR model is first trained on the original data and then used to generate synthetic outputs based on the synthetic inputs produced in the first stage. By leveraging the theoretical strengths of KRR and the covariant distribution retention achieved in the first stage, our proposed two-stage synthesis strategy enables a statistics-driven restricted privacy--prediction trade-off and guarantee optimal prediction performance. We validate our approach and demonstrate its characteristics of being statistics-driven and restricted in achieving the privacy--prediction trade-off both theoretically and numerically. Additionally, we showcase its generalizability through applications to a marketing problem and five real-world datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.08617v1">ERIS: Enhancing Privacy and Communication Efficiency in Serverless Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-02-09T13:05:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dario Fenoglio, Pasquale Polverino, Jacopo Quizi, Martin Gjoreski, Marc Langheinrich</p>
    <p><b>Summary:</b> Scaling federated learning (FL) to billion-parameter models introduces critical trade-offs between communication efficiency, model accuracy, and privacy guarantees. Existing solutions often tackle these challenges in isolation, sacrificing accuracy or relying on costly cryptographic tools. We propose ERIS, a serverless FL framework that balances privacy and accuracy while eliminating the server bottleneck and distributing the communication load. ERIS combines a model partitioning strategy, distributing aggregation across multiple client-side aggregators, with a distributed shifted gradient compression mechanism. We theoretically prove that ERIS (i) converges at the same rate as FedAvg under standard assumptions, and (ii) bounds mutual information leakage inversely with the number of aggregators, enabling strong privacy guarantees with no accuracy degradation. Experiments across image and text tasks, including large language models, confirm that ERIS achieves FedAvg-level accuracy while substantially reducing communication cost and improving robustness to membership inference and reconstruction attacks, without relying on heavy cryptography or noise injection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.08465v1">A Two-Week In-the-Wild Study of Screen Filters and Camera Sliders for Smartphone Privacy in Public Spaces</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-02-09T10:14:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Andreas Tjeldflaat, Piero Romare, Yuki Onishi, Morten Fjeld, Bjørn Sætrevik</p>
    <p><b>Summary:</b> Smartphone usage in public spaces can raise privacy concerns, in terms of shoulder surfing and unintended camera capture. In real-world public space settings, we investigated the impact of tangible privacy-enhancing tools (here: screen filter and camera slider) on smartphone users' reported privacy perception, behavioral adaptations, usability and social dynamics. We conducted a mixed-method, in-the-wild study ($N = 22$) using off-the-shelf smartphone privacy tools. We investigated subjective behavioral transition by combining questionnaires with semi-structured interviews. Participants used the screen filter and the camera slider for two weeks; they reported changes in attitude and behavior after using a screen filter including screen visibility and comfort when using phones publicly. They explained decreased privacy-protective behaviors, such as actively covering their screens, suggesting a shift in perceived risk. Qualitative findings about the camera slider suggested underlying psychological mechanisms, including privacy awareness and concerns about social perception, while also offering insights regarding the tools' effectiveness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.08268v2">Puda: Private User Dataset Agent for User-Sovereign and Privacy-Preserving Personalized AI</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-02-09T05:00:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Akinori Maeda, Yuto Sekiya, Sota Sugimura, Tomoya Asai, Yu Tsuda, Kohei Ikeda, Hiroshi Fujii, Kohei Watanabe</p>
    <p><b>Summary:</b> Personal data centralization among dominant platform providers including search engines, social networking services, and e-commerce has created siloed ecosystems that restrict user sovereignty, thereby impeding data use across services. Meanwhile, the rapid proliferation of Large Language Model (LLM)-based agents has intensified demand for highly personalized services that require the dynamic provision of diverse personal data. This presents a significant challenge: balancing the utilization of such data with privacy protection. To address this challenge, we propose Puda (Private User Dataset Agent), a user-sovereign architecture that aggregates data across services and enables client-side management. Puda allows users to control data sharing at three privacy levels: (i) Detailed Browsing History, (ii) Extracted Keywords, and (iii) Predefined Category Subsets. We implemented Puda as a browser-based system that serves as a common platform across diverse services and evaluated it through a personalized travel planning task. Our results show that providing Predefined Category Subsets achieves 97.2% of the personalization performance (evaluated via an LLM-as-a-Judge framework across three criteria) obtained when sharing Detailed Browsing History. These findings demonstrate that Puda enables effective multi-granularity management, offering practical choices to mitigate the privacy-personalization trade-off. Overall, Puda provides an AI-native foundation for user sovereignty, empowering users to safely leverage the full potential of personalized AI.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.07936v1">Privacy-Preserving Covert Communication Using Encrypted Wearable Gesture Recognition</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-02-08T12:06:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tasnia Ashrafi Heya, Sayed Erfan Arefin</p>
    <p><b>Summary:</b> Secure communication is essential in covert and safety-critical settings where verbal interactions may expose user intent or operational context. Wearable gesture-based communication enables low-effort, nonverbal interaction, but existing systems leak motion data, intermediate representations, or inference outputs to untrusted infrastructure, enabling intent inference, behavioral biometric leakage, and insider attacks. This work proposes a privacy-preserving gesture-based covert communication system that ensures, no raw sensor signals, learned features, or classification outputs are exposed to any third-party. The system employs a multi-party homomorphic learning pipeline for gesture recognition directly over encrypted motion data, preventing adversaries from inferring gesture semantics, replaying sensor traces, or accessing intermediate representations. To our knowledge, this work is the first to apply encrypted gesture recognition in a wearable-based covert communication setting. We design and evaluate haptic and visual feedback mechanisms for covert signal delivery and evaluate the system using 600 gesture samples from a commodity smartwatch, achieving over 94.44% classification accuracy and demonstrating the feasibility of the proposed system with practical deployability from high-performance systems to resource-constrained edge devices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.07850v1">Privacy-Preserving Coding Schemes for Multi-Access Distributed Computing Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-02-08T07:40:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shanuja Sasi</p>
    <p><b>Summary:</b> Distributed computing frameworks such as MapReduce have become essential for large-scale data processing by decomposing tasks across multiple nodes. The multi-access distributed computing (MADC) model further advances this paradigm by decoupling mapper and reducer roles: dedicated mapper nodes store data and compute intermediate values, while reducer nodes are connected to multiple mappers and aggregate results to compute final outputs. This separation reduces communication bottlenecks without requiring file replication. In this paper, we introduce privacy constraints into MADC and develop private coded schemes for two specific connectivity models. We construct new families of extended placement delivery arrays and derive corresponding coding schemes that guarantee privacy of each reducer's assigned function.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.07722v1">IPBAC: Interaction Provenance-Based Access Control for Secure and Privacy-Aware Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-02-07T22:32:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sharif Noor Zisad, Ragib Hasan</p>
    <p><b>Summary:</b> Traditional access control systems, including RBAC, face significant limitations such as inflexible role definitions, difficulty handling dynamic scenarios, and lack of detailed accountability and traceability. To this end, we introduce the Interaction Provenance-based Access Control (IPBAC) model. In this paper, we explore the integration of interaction provenance with access control to overcome these limitations. Interaction provenance refers to the detailed recording of actions and interactions within a system, capturing comprehensive metadata such as the identity of the actor, the time of an action, and the context. IPBAC ensures stronger protection against unauthorized access, enhances traceability for auditing and compliance, and supports adaptive security policies. This provenance-based access control not only strengthens security, but also provides a robust framework for auditing and compliance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.07149v1">Privacy in Image Datasets: A Case Study on Pregnancy Ultrasounds</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-02-06T19:47:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rawisara Lohanimit, Yankun Wu, Amelia Katirai, Yuta Nakashima, Noa Garcia</p>
    <p><b>Summary:</b> The rise of generative models has led to increased use of large-scale datasets collected from the internet, often with minimal or no data curation. This raises concerns about the inclusion of sensitive or private information. In this work, we explore the presence of pregnancy ultrasound images, which contain sensitive personal information and are often shared online. Through a systematic examination of LAION-400M dataset using CLIP embedding similarity, we retrieve images containing pregnancy ultrasound and detect thousands of entities of private information such as names and locations. Our findings reveal that multiple images have high-risk information that could enable re-identification or impersonation. We conclude with recommended practices for dataset curation, data privacy, and ethical use of public image datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.06756v1">$f$-Differential Privacy Filters: Validity and Approximate Solutions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-02-06T15:04:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Long Tran, Antti Koskela, Ossi Räisä, Antti Honkela</p>
    <p><b>Summary:</b> Accounting for privacy loss under fully adaptive composition -- where both the choice of mechanisms and their privacy parameters may depend on the entire history of prior outputs -- is a central challenge in differential privacy (DP). In this setting, privacy filters are stopping rules for compositions that ensure a prescribed global privacy budget is not exceeded. It remains unclear whether optimal trade-off-function-based notions, such as $f$-DP, admit valid privacy filters under fully adaptive interaction. We show that the natural approach to defining an $f$-DP filter -- composing individual trade-off curves and stopping when the prescribed $f$-DP curve is crossed -- is fundamentally invalid. We characterise when and why this failure occurs, and establish necessary and sufficient conditions under which the natural filter is valid. Furthermore, we prove a fully adaptive central limit theorem for $f$-DP and construct an approximate Gaussian DP filter for subsampled Gaussian mechanisms at small sampling rates $q<0.2$ and large sampling rates $q>0.8$, yielding tighter privacy guarantees than filters based on Rényi DP in the same setting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.07090v1">Concept-Aware Privacy Mechanisms for Defending Embedding Inversion Attacks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-02-06T09:28:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yu-Che Tsai, Hsiang Hsiao, Kuan-Yu Chen, Shou-De Lin</p>
    <p><b>Summary:</b> Text embeddings enable numerous NLP applications but face severe privacy risks from embedding inversion attacks, which can expose sensitive attributes or reconstruct raw text. Existing differential privacy defenses assume uniform sensitivity across embedding dimensions, leading to excessive noise and degraded utility. We propose SPARSE, a user-centric framework for concept-specific privacy protection in text embeddings. SPARSE combines (1) differentiable mask learning to identify privacy-sensitive dimensions for user-defined concepts, and (2) the Mahalanobis mechanism that applies elliptical noise calibrated by dimension sensitivity. Unlike traditional spherical noise injection, SPARSE selectively perturbs privacy-sensitive dimensions while preserving non-sensitive semantics. Evaluated across six datasets with three embedding models and attack scenarios, SPARSE consistently reduces privacy leakage while achieving superior downstream performance compared to state-of-the-art DP methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.06518v1">Sequential Auditing for f-Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">  
  <p><b>Published on:</b> 2026-02-06T09:22:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tim Kutta, Martin Dunsche, Yu Wei, Vassilis Zikas</p>
    <p><b>Summary:</b> We present new auditors to assess Differential Privacy (DP) of an algorithm based on output samples. Such empirical auditors are common to check for algorithmic correctness and implementation bugs. Most existing auditors are batch-based or targeted toward the traditional notion of $(\varepsilon,δ)$-DP; typically both. In this work, we shift the focus to the highly expressive privacy concept of $f$-DP, in which the entire privacy behavior is captured by a single tradeoff curve. Our auditors detect violations across the full privacy spectrum with statistical significance guarantees, which are supported by theory and simulations. Most importantly, and in contrast to prior work, our auditors do not require a user-specified sample size as an input. Rather, they adaptively determine a near-optimal number of samples needed to reach a decision, thereby avoiding the excessively large sample sizes common in many auditing studies. This reduction in sampling cost becomes especially beneficial for expensive training procedures such as DP-SGD. Our method supports both whitebox and blackbox settings and can also be executed in single-run frameworks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.06390v1">Generating High-quality Privacy-preserving Synthetic Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-02-06T05:03:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> David Yavo, Richard Khoury, Christophe Pere, Sadoune Ait Kaci Azzou</p>
    <p><b>Summary:</b> Synthetic tabular data enables sharing and analysis of sensitive records, but its practical deployment requires balancing distributional fidelity, downstream utility, and privacy protection. We study a simple, model agnostic post processing framework that can be applied on top of any synthetic data generator to improve this trade off. First, a mode patching step repairs categories that are missing or severely underrepresented in the synthetic data, while largely preserving learned dependencies. Second, a k nearest neighbor filter replaces synthetic records that lie too close to real data points, enforcing a minimum distance between real and synthetic samples. We instantiate this framework for two neural generative models for tabular data, a feed forward generator and a variational autoencoder, and evaluate it on three public datasets covering credit card transactions, cardiovascular health, and census based income. We assess marginal and joint distributional similarity, the performance of models trained on synthetic data and evaluated on real data, and several empirical privacy indicators, including nearest neighbor distances and attribute inference attacks. With moderate thresholds between 0.2 and 0.35, the post processing reduces divergence between real and synthetic categorical distributions by up to 36 percent and improves a combined measure of pairwise dependence preservation by 10 to 14 percent, while keeping downstream predictive performance within about 1 percent of the unprocessed baseline. At the same time, distance based privacy indicators improve and the success rate of attribute inference attacks remains largely unchanged. These results provide practical guidance for selecting thresholds and applying post hoc repairs to improve the quality and empirical privacy of synthetic tabular data, while complementing approaches that provide formal differential privacy guarantees.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.06238v1">Private Sum Computation: Trade-Offs between Communication, Randomness, and Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-02-05T22:29:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Remi A. Chou, Joerg Kliewer, Aylin Yener</p>
    <p><b>Summary:</b> Consider multiple users and a fusion center. Each user possesses a sequence of bits and can communicate with the fusion center through a one-way public channel. The fusion center's task is to compute the sum of all the sequences under the privacy requirement that a set of colluding users, along with the fusion center, cannot gain more than a predetermined amount $δ$ of information, measured through mutual information, about the sequences of other users. Our first contribution is to characterize the minimum amount of necessary communication between the users and the fusion center, as well as the minimum amount of necessary randomness at the users. Our second contribution is to establish a connection between private sum computation and secret sharing by showing that secret sharing is necessary to generate the local randomness needed for private sum computation, and prove that it holds true for any $δ\geq 0$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.05833v1">Synthesizing Realistic Test Data without Breaking Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-02-05T16:22:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Laura Plein, Alexi Turcotte, Arina Hallemans, Andreas Zeller</p>
    <p><b>Summary:</b> There is a need for synthetic training and test datasets that replicate statistical distributions of original datasets without compromising their confidentiality. A lot of research has been done in leveraging Generative Adversarial Networks (GANs) for synthetic data generation. However, the resulting models are either not accurate enough or are still vulnerable to membership inference attacks (MIA) or dataset reconstruction attacks since the original data has been leveraged in the training process. In this paper, we explore the feasibility of producing a synthetic test dataset with the same statistical properties as the original one, with only indirectly leveraging the original data in the generation process. The approach is inspired by GANs, with a generation step and a discrimination step. However, in our approach, we use a test generator (a fuzzer) to produce test data from an input specification, preserving constraints set by the original data; a discriminator model determines how close we are to the original data. By evolving samples and determining "good samples" with the discriminator, we can generate privacy-preserving data that follows the same statistical distributions are the original dataset, leading to a similar utility as the original data. We evaluated our approach on four datasets that have been used to evaluate the state-of-the-art techniques. Our experiments highlight the potential of our approach towards generating synthetic datasets that have high utility while preserving privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.05803v1">Privacy-Preserving Dynamic Average Consensus by Masking Reference Signals</a></h3>
  
  <p><b>Published on:</b> 2026-02-05T15:57:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mihitha Maithripala, Zongli Lin</p>
    <p><b>Summary:</b> In multi-agent systems, dynamic average consensus (DAC) is a decentralized estimation strategy in which a set of agents tracks the average of time-varying reference signals. Because DAC requires exchanging state information with neighbors, attackers may gain access to these states and infer private information. In this paper, we develop a privacy-preserving method that protects each agent's reference signal from external eavesdroppers and honest-but-curious agents while achieving the same convergence accuracy and convergence rate as conventional DAC. Our approach masks the reference signals by having each agent draw a random real number for each neighbor, exchanges that number over an encrypted channel at the initialization, and computes a masking value to form a masked reference. Then the agents run the conventional DAC algorithm using the masked references. Convergence and privacy analyses show that the proposed algorithm matches the convergence properties of conventional DAC while preserving the privacy of the reference signals. Numerical simulations validate the effectiveness of the proposed privacy-preserving DAC algorithm.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.05797v1">Classification Under Local Differential Privacy with Model Reversal and Model Averaging</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2026-02-05T15:52:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Caihong Qin, Yang Bai</p>
    <p><b>Summary:</b> Local differential privacy (LDP) has become a central topic in data privacy research, offering strong privacy guarantees by perturbing user data at the source and removing the need for a trusted curator. However, the noise introduced by LDP often significantly reduces data utility. To address this issue, we reinterpret private learning under LDP as a transfer learning problem, where the noisy data serve as the source domain and the unobserved clean data as the target. We propose novel techniques specifically designed for LDP to improve classification performance without compromising privacy: (1) a noised binary feedback-based evaluation mechanism for estimating dataset utility; (2) model reversal, which salvages underperforming classifiers by inverting their decision boundaries; and (3) model averaging, which assigns weights to multiple reversed classifiers based on their estimated utility. We provide theoretical excess risk bounds under LDP and demonstrate how our methods reduce this risk. Empirical results on both simulated and real-world datasets show substantial improvements in classification accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.05016v1">From Fragmentation to Integration: Exploring the Design Space of AI Agents for Human-as-the-Unit Privacy Management</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2026-02-04T20:12:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Eryue Xu, Tianshi Li</p>
    <p><b>Summary:</b> Managing one's digital footprint is overwhelming, as it spans multiple platforms and involves countless context-dependent decisions. Recent advances in agentic AI offer ways forward by enabling holistic, contextual privacy-enhancing solutions. Building on this potential, we adopted a ''human-as-the-unit'' perspective and investigated users' cross-context privacy challenges through 12 semi-structured interviews. Results reveal that people rely on ad hoc manual strategies while lacking comprehensive privacy controls, highlighting nine privacy-management challenges across applications, temporal contexts, and relationships. To explore solutions, we generated nine AI agent concepts and evaluated them via a speed-dating survey with 116 US participants. The three highest-ranked concepts were all post-sharing management tools with half or full agent autonomy, with users expressing greater trust in AI accuracy than in their own efforts. Our findings highlight a promising design space where users see AI agents bridging the fragments in privacy management, particularly through automated, comprehensive post-sharing remediation of users' digital footprints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.04994v1">SIDeR: Semantic Identity Decoupling for Unrestricted Face Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-02-04T19:30:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhuosen Bao, Xia Du, Zheng Lin, Jizhe Zhou, Zihan Fang, Jiening Wu, Yuxin Zhang, Zhe Chen, Chi-man Pun, Wei Ni, Jun Luo</p>
    <p><b>Summary:</b> With the deep integration of facial recognition into online banking, identity verification, and other networked services, achieving effective decoupling of identity information from visual representations during image storage and transmission has become a critical challenge for privacy protection. To address this issue, we propose SIDeR, a Semantic decoupling-driven framework for unrestricted face privacy protection. SIDeR decomposes a facial image into a machine-recognizable identity feature vector and a visually perceptible semantic appearance component. By leveraging semantic-guided recomposition in the latent space of a diffusion model, it generates visually anonymous adversarial faces while maintaining machine-level identity consistency. The framework incorporates momentum-driven unrestricted perturbation optimization and a semantic-visual balancing factor to synthesize multiple visually diverse, highly natural adversarial samples. Furthermore, for authorized access, the protected image can be restored to its original form when the correct password is provided. Extensive experiments on the CelebA-HQ and FFHQ datasets demonstrate that SIDeR achieves a 99% attack success rate in black-box scenarios and outperforms baseline methods by 41.28% in PSNR-based restoration quality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.04616v1">A Human-Centered Privacy Approach (HCP) to AI</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-02-04T14:43:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Luyi Sun, Wei Xu, Zaifeng Gao</p>
    <p><b>Summary:</b> As the paradigm of Human-Centered AI (HCAI) gains prominence, its benefits to society are accompanied by significant ethical concerns, one of which is the protection of individual privacy. This chapter provides a comprehensive overview of privacy within HCAI, proposing a human-centered privacy (HCP) framework, providing integrated solution from technology, ethics, and human factors perspectives. The chapter begins by mapping privacy risks across each stage of AI development lifecycle, from data collection to deployment and reuse, highlighting the impact of privacy risks on the entire system. The chapter then introduces privacy-preserving techniques such as federated learning and dif erential privacy. Subsequent chapters integrate the crucial user perspective by examining mental models, alongside the evolving regulatory and ethical landscapes as well as privacy governance. Next, advice on design guidelines is provided based on the human-centered privacy framework. After that, we introduce practical case studies across diverse fields. Finally, the chapter discusses persistent open challenges and future research directions, concluding that a multidisciplinary approach, merging technical, design, policy, and ethical expertise, is essential to successfully embed privacy into the core of HCAI, thereby ensuring these technologies advance in a manner that respects and ensures human autonomy, trust and dignity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.04562v1">Optimal conversion from Rényi Differential Privacy to $f$-Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-02-04T13:49:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anneliese Riess, Juan Felipe Gomez, Flavio du Pin Calmon, Julia Anne Schnabel, Georgios Kaissis</p>
    <p><b>Summary:</b> We prove the conjecture stated in Appendix F.3 of [Zhu et al. (2022)]: among all conversion rules that map a Rényi Differential Privacy (RDP) profile $τ\mapsto ρ(τ)$ to a valid hypothesis-testing trade-off $f$, the rule based on the intersection of single-order RDP privacy regions is optimal. This optimality holds simultaneously for all valid RDP profiles and for all Type I error levels $α$. Concretely, we show that in the space of trade-off functions, the tightest possible bound is $f_{ρ(\cdot)}(α) = \sup_{τ\geq 0.5} f_{τ,ρ(τ)}(α)$: the pointwise maximum of the single-order bounds for each RDP privacy region. Our proof unifies and sharpens the insights of [Balle et al. (2019)], [Asoodeh et al. (2021)], and [Zhu et al. (2022)]. Our analysis relies on a precise geometric characterization of the RDP privacy region, leveraging its convexity and the fact that its boundary is determined exclusively by Bernoulli mechanisms. Our results establish that the "intersection-of-RDP-privacy-regions" rule is not only valid, but optimal: no other black-box conversion can uniformly dominate it in the Blackwell sense, marking the fundamental limit of what can be inferred about a mechanism's privacy solely from its RDP guarantees.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.04933v1">The Birthmark Standard: Privacy-Preserving Photo Authentication via Hardware Roots of Trust and Consortium Blockchain</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-02-04T13:16:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sam Ryan</p>
    <p><b>Summary:</b> The rapid advancement of generative AI systems has collapsed the credibility landscape for photographic evidence. Modern image generation models produce photorealistic images undermining the evidentiary foundation upon which journalism and public discourse depend. Existing authentication approaches, such as the Coalition for Content Provenance and Authenticity (C2PA), embed cryptographically signed metadata directly into image files but suffer from two critical failures: technical vulnerability to metadata stripping during social media reprocessing, and structural dependency on corporate-controlled verification infrastructure where commercial incentives may conflict with public interest. We present the Birthmark Standard, an authentication architecture leveraging manufacturing-unique sensor entropy from non-uniformity correction (NUC) maps and PRNU patterns to generate hardware-rooted authentication keys. During capture, cameras create anonymized authentication certificates proving sensor authenticity without exposing device identity via a key table architecture maintaining anonymity sets exceeding 1,000 devices. Authentication records are stored on a consortium blockchain operated by journalism organizations rather than commercial platforms, enabling verification that survives all metadata loss. We formally verify privacy properties using ProVerif, proving observational equivalence for Manufacturer Non-Correlation and Blockchain Observer Non-Identification under Dolev-Yao adversary assumptions. The architecture is validated through prototype implementation using Raspberry Pi 4 hardware, demonstrating the complete cryptographic pipeline. Performance analysis projects camera overhead below 100ms and verification latency below 500ms at scale of one million daily authentications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.04927v1">PriMod4AI: Lifecycle-Aware Privacy Threat Modeling for AI Systems using LLM</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-02-04T08:58:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gautam Savaliya, Robert Aufschläger, Abhishek Subedi, Michael Heigl, Martin Schramm</p>
    <p><b>Summary:</b> Artificial intelligence systems introduce complex privacy risks throughout their lifecycle, especially when processing sensitive or high-dimensional data. Beyond the seven traditional privacy threat categories defined by the LINDDUN framework, AI systems are also exposed to model-centric privacy attacks such as membership inference and model inversion, which LINDDUN does not cover. To address both classical LINDDUN threats and additional AI-driven privacy attacks, PriMod4AI introduces a hybrid privacy threat modeling approach that unifies two structured knowledge sources, a LINDDUN knowledge base representing the established taxonomy, and a model-centric privacy attack knowledge base capturing threats outside LINDDUN. These knowledge bases are embedded into a vector database for semantic retrieval and combined with system level metadata derived from Data Flow Diagram. PriMod4AI uses retrieval-augmented and Data Flow specific prompt generation to guide large language models (LLMs) in identifying, explaining, and categorizing privacy threats across lifecycle stages. The framework produces justified and taxonomy-grounded threat assessments that integrate both classical and AI-driven perspectives. Evaluation on two AI systems indicates that PriMod4AI provides broad coverage of classical privacy categories while additionally identifying model-centric privacy threats. The framework produces consistent, knowledge-grounded outputs across LLMs, as reflected in agreement scores in the observed range.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.04262v1">Parameter Privacy-Preserving Data Sharing: A Particle-Belief MDP Formulation</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E">
  <p><b>Published on:</b> 2026-02-04T06:55:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haokun Yu, Jingyuan Zhou, Kaidi Yang</p>
    <p><b>Summary:</b> This paper investigates parameter-privacy-preserving data sharing in continuous-state dynamical systems, where a data owner designs a data-sharing policy to support downstream estimation and control while preventing adversarial inference of a sensitive parameter. This data-sharing problem is formulated as an optimization problem that trades off privacy leakage and the impact of data sharing on the data owner's utility, subject to a data-usability constraint. We show that this problem admits an equivalent belief Markov decision process (MDP) formulation, which provides a simplified representation of the optimal policy. To efficiently characterize information-theoretic privacy leakage in continuous state and action spaces, we propose a particle-belief MDP formulation that tracks the parameter posterior via sequential Monte Carlo, yielding a tractable belief-state approximation that converges asymptotically as the number of particles increases. We further derive a tractable closed-form upper bound on particle-based MI via Gaussian mixture approximations, which enables efficient optimization of the particle-belief MDP. Experiments on a mixed-autonomy platoon show that the learned continuous policy substantially impedes inference attacks on human-driving behavior parameters while maintaining data usability and system performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.04124v2">Privacy Amplification for Synthetic data using Range Restriction</a></h3>
  
  <p><b>Published on:</b> 2026-02-04T01:36:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jingchen Hu, Matthew R. Williams, Terrance D. Savitsky</p>
    <p><b>Summary:</b> We introduce a new class of range restricted formal data privacy standards that condition on owner beliefs about sensitive data ranges. By incorporating this additional information, we can provide a stronger privacy guarantee (e.g. an amplification). The range restricted formal privacy standards protect only a subset (or ball) of data values and exclude ranges (or balls) believed to be already publicly known. The privacy standards are designed for the risk-weighted pseudo posterior (model) mechanism (PPM) used to generate synthetic data under an asymptotic Differential (aDP) privacy guarantee. The PPM downweights the likelihood contribution for each record proportionally to its disclosure risk. The PPM is adapted under inclusion of beliefs by adjusting the risk-weighted pseudo likelihood. We introduce two alternative adjustments. The first expresses data owner knowledge of the sensitive range as a probability, $λ$, that a datum value drawn from the underlying generating distribution lies outside the ball or subspace of values that are sensitive. The portion of each datum likelihood contribution deemed sensitive is then $(1-λ) \leq 1$ and is the only portion of the likelihood subject to risk down-weighting. The second adjustment encodes knowledge as the difference in probability masses $P(R) \leq 1$ between the edges of the sensitive range, $R$. We use the resulting conditional (pseudo) likelihood for a sensitive record, which boosts its worst case tail values away from 0. We compare privacy and utility properties for the PPM under the aDP and range restricted privacy standards.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.03948v1">Privacy utility trade offs for parameter estimation in degree heterogeneous higher order networks</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">
  <p><b>Published on:</b> 2026-02-03T19:11:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bibhabasu Mandal, Sagnik Nandy</p>
    <p><b>Summary:</b> In sensitive applications involving relational datasets, protecting information about individual links from adversarial queries is of paramount importance. In many such settings, the available data are summarized solely through the degrees of the nodes in the network. We adopt the $β$ model, which is the prototypical statistical model adopted for this form of aggregated relational information, and study the problem of minimax-optimal parameter estimation under both local and central differential privacy constraints. We establish finite sample minimax lower bounds that characterize the precise dependence of the estimation risk on the network size and the privacy parameters, and we propose simple estimators that achieve these bounds up to constants and logarithmic factors under both local and central differential privacy frameworks. Our results provide the first comprehensive finite sample characterization of privacy utility trade offs for parameter estimation in $β$ models, addressing the classical graph case and extending the analysis to higher order hypergraph models. We further demonstrate the effectiveness of our methods through experiments on synthetic data and a real world communication network.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.03671v1">mopri - An Analysis Framework for Unveiling Privacy Violations in Mobile Apps</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-02-03T15:52:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Cornell Ziepel, Stephan Escher, Sebastian Rehms, Stefan Köpsell</p>
    <p><b>Summary:</b> Everyday services of society increasingly rely on mobile applications, resulting in a conflicting situation between the possibility of participation on the one side and user privacy and digital freedom on the other. In order to protect users' rights to informational self-determination, regulatory approaches for the collection and processing of personal data have been developed, such as the EU's GDPR. However, inspecting the compliance of mobile apps with privacy regulations remains difficult. Thus, in order to enable end users and enforcement bodies to verify and enforce data protection compliance, we propose mopri, a conceptual framework designed for analyzing the behavior of mobile apps through a comprehensive, adaptable, and user-centered approach. Recognizing the gaps in existing frameworks, mopri serves as a foundation for integrating various analysis tools into a streamlined, modular pipeline that employs static and dynamic analysis methods. Building on this concept, a prototype has been developed which effectively extracts permissions and tracking libraries while employing robust methods for dynamic traffic recording and decryption. Additionally, it incorporates result enrichment and reporting features that enhance the clarity and usability of the analysis outcomes. The prototype showcases the feasibility of a holistic and modular approach to privacy analysis, emphasizing the importance of continuous adaptation to the evolving challenges presented by the mobile app ecosystem.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.03611v1">Explanations Leak: Membership Inference with Differential Privacy and Active Learning Defense</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-02-03T15:04:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fatima Ezzeddine, Osama Zammar, Silvia Giordano, Omran Ayoub</p>
    <p><b>Summary:</b> Counterfactual explanations (CFs) are increasingly integrated into Machine Learning as a Service (MLaaS) systems to improve transparency; however, ML models deployed via APIs are already vulnerable to privacy attacks such as membership inference and model extraction, and the impact of explanations on this threat landscape remains insufficiently understood. In this work, we focus on the problem of how CFs expand the attack surface of MLaaS by strengthening membership inference attacks (MIAs), and on the need to design defense mechanisms that mitigate this emerging risk without undermining utility and explainability. First, we systematically analyze how exposing CFs through query-based APIs enables more effective shadow-based MIAs. Second, we propose a defense framework that integrates Differential Privacy (DP) with Active Learning (AL) to jointly reduce memorization and limit effective training data exposure. Finally, we conduct an extensive empirical evaluation to characterize the three-way trade-off between privacy leakage, predictive performance, and explanation quality. Our findings highlight the need to carefully balance transparency, utility, and privacy in the responsible deployment of explainable MLaaS systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.03423v1">Origin Lens: A Privacy-First Mobile Framework for Cryptographic Image Provenance and AI Detection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-02-03T11:49:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alexander Loth, Dominique Conceicao Rosario, Peter Ebinger, Martin Kappes, Marc-Oliver Pahl</p>
    <p><b>Summary:</b> The proliferation of generative AI poses challenges for information integrity assurance, requiring systems that connect model governance with end-user verification. We present Origin Lens, a privacy-first mobile framework that targets visual disinformation through a layered verification architecture. Unlike server-side detection systems, Origin Lens performs cryptographic image provenance verification and AI detection locally on the device via a Rust/Flutter hybrid architecture. Our system integrates multiple signals - including cryptographic provenance, generative model fingerprints, and optional retrieval-augmented verification - to provide users with graded confidence indicators at the point of consumption. We discuss the framework's alignment with regulatory requirements (EU AI Act, DSA) and its role in verification infrastructure that complements platform-level mechanisms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.04895v1">Privacy Amplification Persists under Unlimited Synthetic Data Release</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2026-02-03T09:27:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Clément Pierquin, Aurélien Bellet, Marc Tommasi, Matthieu Boussard</p>
    <p><b>Summary:</b> We study privacy amplification by synthetic data release, a phenomenon in which differential privacy guarantees are improved by releasing only synthetic data rather than the private generative model itself. Recent work by Pierquin et al. (2025) established the first formal amplification guarantees for a linear generator, but they apply only in asymptotic regimes where the model dimension far exceeds the number of released synthetic records, limiting their practical relevance. In this work, we show a surprising result: under a bounded-parameter assumption, privacy amplification persists even when releasing an unbounded number of synthetic records, thereby improving upon the bounds of Pierquin et al. (2025). Our analysis provides structural insights that may guide the development of tighter privacy guarantees for more complex release mechanisms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.03277v1">BlockRR: A Unified Framework of RR-type Algorithms for Label Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-02-03T09:00:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haixia Liu, Yi Ding</p>
    <p><b>Summary:</b> In this paper, we introduce BlockRR, a novel and unified randomized-response mechanism for label differential privacy. This framework generalizes existed RR-type mechanisms as special cases under specific parameter settings, which eliminates the need for separate, case-by-case analysis. Theoretically, we prove that BlockRR satisfies $ε$-label DP. We also design a partition method for BlockRR based on a weight matrix derived from label prior information; the parallel composition principle ensures that the composition of two such mechanisms remains $ε$-label DP. Empirically, we evaluate BlockRR on two variants of CIFAR-10 with varying degrees of class imbalance. Results show that in the high-privacy and moderate-privacy regimes ($ε\leq 3.0$), our propsed method gets a better balance between test accuaracy and the average of per-class accuracy. In the low-privacy regime ($ε\geq 4.0$), all methods reduce BlockRR to standard RR without additional performance loss.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.02914v1">FaceLinkGen: Rethinking Identity Leakage in Privacy-Preserving Face Recognition with Identity Extraction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-02-02T23:41:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenqi Guo, Shan Du</p>
    <p><b>Summary:</b> Transformation-based privacy-preserving face recognition (PPFR) aims to verify identities while hiding facial data from attackers and malicious service providers. Existing evaluations mostly treat privacy as resistance to pixel-level reconstruction, measured by PSNR and SSIM. We show that this reconstruction-centric view fails. We present FaceLinkGen, an identity extraction attack that performs linkage/matching and face regeneration directly from protected templates without recovering original pixels. On three recent PPFR systems, FaceLinkGen reaches over 98.5\% matching accuracy and above 96\% regeneration success, and still exceeds 92\% matching and 94\% regeneration in a near zero knowledge setting. These results expose a structural gap between pixel distortion metrics, which are widely used in PPFR evaluation, and real privacy. We show that visual obfuscation leaves identity information broadly exposed to both external intruders and untrusted service providers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.02744v1">An introduction to local differential privacy protocols using block designs</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-02-02T19:58:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maura B. Paterson, Douglas R. Stinson</p>
    <p><b>Summary:</b> The design of protocols for local differential privacy (or LDP) has been a topic of considerable research interest in recent years. LDP protocols utilise the randomised encoding of outcomes of an experiment using a transition probability matrix (TPM). Several authors have observed that balanced incomplete block designs (BIBDs) provide nice examples of TPMs for LDP protocols. Indeed, it has been shown that such BIBD-based LDP protocols provide optimal estimators.
  In this primarily expository paper, we give a detailed introduction to LDP protocols and their connections with block designs. We prove that a subclass of LDP protocols known as pure LDP protocols are equivalent to $(r,λ)$-designs (which contain balanced incomplete block designs as a special case). An unbiased estimator for an LDP scheme is a left inverse of the transition probability matrix. We show that the optimal estimators for BIBD-based TPMs are precisely those obtained from the Moore-Penrose inverse of the corresponding TPM. We also review some existing work on optimal LDP protocols in the context of pure protocols.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.02718v1">Composition for Pufferfish Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-02-02T19:36:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiamu Bai, Guanlin He, Xin Gu, Daniel Kifer, Kiwan Maeng</p>
    <p><b>Summary:</b> When creating public data products out of confidential datasets, inferential/posterior-based privacy definitions, such as Pufferfish, provide compelling privacy semantics for data with correlations. However, such privacy definitions are rarely used in practice because they do not always compose. For example, it is possible to design algorithms for these privacy definitions that have no leakage when run once but reveal the entire dataset when run more than once. We prove necessary and sufficient conditions that must be added to ensure linear composition for Pufferfish mechanisms, hence avoiding such privacy collapse. These extra conditions turn out to be differential privacy-style inequalities, indicating that achieving both the interpretable semantics of Pufferfish for correlated data and composition benefits requires adopting differentially private mechanisms to Pufferfish. We show that such translation is possible through a concept called the $(a,b)$-influence curve, and many existing differentially private algorithms can be translated with our framework into a composable Pufferfish algorithm. We illustrate the benefit of our new framework by designing composable Pufferfish algorithms for Markov chains that significantly outperform prior work.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.02364v1">Guaranteeing Privacy in Hybrid Quantum Learning through Theoretical Mechanisms</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-02-02T17:23:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hoang M. Ngo, Tre' R. Jeter, Incheol Shin, Wanli Xing, Tamer Kahveci, My T. Thai</p>
    <p><b>Summary:</b> Quantum Machine Learning (QML) is becoming increasingly prevalent due to its potential to enhance classical machine learning (ML) tasks, such as classification. Although quantum noise is often viewed as a major challenge in quantum computing, it also offers a unique opportunity to enhance privacy. In particular, intrinsic quantum noise provides a natural stochastic resource that, when rigorously analyzed within the differential privacy (DP) framework and composed with classical mechanisms, can satisfy formal $(\varepsilon, δ)$-DP guarantees. This enables a reduction in the required classical perturbation without compromising the privacy budget, potentially improving model utility. However, the integration of classical and quantum noise for privacy preservation remains unexplored. In this work, we propose a hybrid noise-added mechanism, HYPER-Q, that combines classical and quantum noise to protect the privacy of QML models. We provide a comprehensive analysis of its privacy guarantees and establish theoretical bounds on its utility. Empirically, we demonstrate that HYPER-Q outperforms existing classical noise-based mechanisms in terms of adversarial robustness across multiple real-world datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.02296v2">Decoupling Generalizability and Membership Privacy Risks in Neural Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-02-02T16:32:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xingli Fang, Jung-Eun Kim</p>
    <p><b>Summary:</b> A deep learning model usually has to sacrifice some utilities when it acquires some other abilities or characteristics. Privacy preservation has such trade-off relationships with utilities. The loss disparity between various defense approaches implies the potential to decouple generalizability and privacy risks to maximize privacy gain. In this paper, we identify that the model's generalization and privacy risks exist in different regions in deep neural network architectures. Based on the observations that we investigate, we propose Privacy-Preserving Training Principle (PPTP) to protect model components from privacy risks while minimizing the loss in generalizability. Through extensive evaluations, our approach shows significantly better maintenance in model generalizability while enhancing privacy preservation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.01928v2">Privacy Amplification by Missing Data</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-02-02T10:28:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Simon Roburin, Rafaël Pinot, Erwan Scornet</p>
    <p><b>Summary:</b> Privacy preservation is a fundamental requirement in many high-stakes domains such as medicine and finance, where sensitive personal data must be analyzed without compromising individual confidentiality. At the same time, these applications often involve datasets with missing values due to non-response, data corruption, or deliberate anonymization. Missing data is traditionally viewed as a limitation because it reduces the information available to analysts and can degrade model performance. In this work, we take an alternative perspective and study missing data from a privacy preservation standpoint. Intuitively, when features are missing, less information is revealed about individuals, suggesting that missingness could inherently enhance privacy. We formalize this intuition by analyzing missing data as a privacy amplification mechanism within the framework of differential privacy. We show, for the first time, that incomplete data can yield privacy amplification for differentially private algorithms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.01804v1">Fostering Data Collaboration in Digital Transportation Marketplaces: The Role of Privacy-Preserving Mechanisms</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB">
  <p><b>Published on:</b> 2026-02-02T08:35:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qiqing Wang, Haokun Yu, Kaidi Yang</p>
    <p><b>Summary:</b> Data collaboration between municipal authorities (MA) and mobility providers (MPs) has brought tremendous benefits to transportation systems in the era of big data. Engaging in collaboration can improve the service operations (e.g., reduced delay) of these data owners, however, it can also raise privacy concerns and discourage data-sharing willingness. Specifically, data owners may be concerned that the shared data may leak sensitive information about their customers' mobility patterns or business secrets, resulting in the failure of collaboration. This paper investigates how privacy-preserving mechanisms can foster data collaboration in such settings. We propose a game-theoretic framework to investigate data-sharing among transportation stakeholders, especially considering perturbation-based privacy-preserving mechanisms. Numerical studies demonstrate that lower data quality expectations can incentivize voluntary data sharing, improving transport-related welfare for both MAs and MPs. Our findings provide actionable insights for policymakers and system designers on how privacy-preserving technologies can help bridge data silos and promote collaborative, privacy-aware transportation systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.01387v1">Disclose with Care: Designing Privacy Controls in Interview Chatbots</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-02-01T18:48:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ziwen Li, Ziang Xiao, Tianshi Li</p>
    <p><b>Summary:</b> Collecting data on sensitive topics remains challenging in HCI, as participants often withhold information due to privacy concerns and social desirability bias. While chatbots' perceived anonymity may reduce these barriers, research paradoxically suggests people tend to over-share personal or sensitive information with chatbots. In this work, we explore privacy controls in chatbot interviews to address this problem. The privacy control allows participants to revise their transcripts at the end of the interview, featuring two design variants: free editing and AI-aided editing. In a between-subjects study \red{($N=188$)}, we compared no-editing, free-editing, and AI-aided editing conditions in a chatbot-based interview on a sensitive topic. Our results confirm the prevalent issue of oversharing in chatbot-based interviews and show that AI-aided editing serves as an effective privacy-control mechanism, reducing PII disclosure while maintaining data quality and user engagement, thereby offering a promising approach to balancing ethical practice and data quality in such interviews.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.01177v2">Equivalence of Privacy and Stability with Generalization Guarantees in Quantum Learning</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-02-01T12:03:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ayanava Dasgupta, Naqueeb Ahmad Warsi, Masahito Hayashi</p>
    <p><b>Summary:</b> We present a unified information-theoretic framework elucidating the interplay between stability, privacy, and the generalization performance of quantum learning algorithms. We establish a bound on the expected generalization error in terms of quantum mutual information and derive a probabilistic upper bound that generalizes the classical result by Esposito et al. (2021). Complementing these findings, we provide a lower bound on the expected true loss relative to the expected empirical loss. Additionally, we demonstrate that $(\varepsilon, δ)$-quantum differentially private learning algorithms are stable, thereby ensuring strong generalization guarantees. Finally, we extend our analysis to dishonest learning algorithms, introducing Information-Theoretic Admissibility (ITA) to characterize the fundamental limits of privacy when the learning algorithm is oblivious to specific dataset instances.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.01126v1">WinFLoRA: Incentivizing Client-Adaptive Aggregation in Federated LoRA under Privacy Heterogeneity</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-02-01T09:52:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mengsha Kou, Xiaoyu Xia, Ziqi Wang, Ibrahim Khalil, Runkun Luo, Jingwen Zhou, Minhui Xue</p>
    <p><b>Summary:</b> Large Language Models (LLMs) increasingly underpin intelligent web applications, from chatbots to search and recommendation, where efficient specialization is essential. Low-Rank Adaptation (LoRA) enables such adaptation with minimal overhead, while federated LoRA allows web service providers to fine-tune shared models without data sharing. However, in privacy-sensitive deployments, clients inject varying levels of differential privacy (DP) noise, creating privacy heterogeneity that misaligns individual incentives and global performance. In this paper, we propose WinFLoRA, a privacy-heterogeneous federated LoRA that utilizes aggregation weights as incentives with noise awareness. Specifically, the noises from clients are estimated based on the uploaded LoRA adapters. A larger weight indicates greater influence on the global model and better downstream task performance, rewarding lower-noise contributions. By up-weighting low-noise updates, WinFLoRA improves global accuracy while accommodating clients' heterogeneous privacy requirements. Consequently, WinFLoRA aligns heterogeneous client utility in terms of privacy and downstream performance with global model objectives without third-party involvement. Extensive evaluations demonstrate that across multiple LLMs and datasets, WinFLoRA achieves up to 52.58% higher global accuracy and up to 2.56x client utility than state-of-the-art benchmarks. Source code is publicly available at https://github.com/koums24/WinFLoRA.git.</p>
  </details>
</div>



<h2>2026-01</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.00821v1">Edge-Native Generative De-identification: Inversion-Free Flow for Privacy-Preserving Federated Skin Image Analysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-01-31T17:19:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Konstantinos Moutselos, Ilias Maglogiannis</p>
    <p><b>Summary:</b> The deployment of Federated Learning (FL) for clinical dermatology is hindered by the competing requirements of protecting patient privacy and preserving diagnostic features. Traditional de-identification methods often degrade pathological fidelity, while standard generative editing techniques rely on computationally intensive inversion processes unsuitable for resource-constrained edge devices. We propose a framework for identity-agnostic pathology preservation that serves as a client-side privacy-preserving utility. By leveraging inversion-free Rectified Flow Transformers (FlowEdit), the system performs high-fidelity identity transformation in near real-time (less than 20s), facilitating local deployment on clinical nodes. We introduce a "Segment-by-Synthesis" mechanism that generates counterfactual healthy and pathological twin pairs locally. This enables the extraction of differential erythema masks that are decoupled from biometric markers and semantic artifacts (e.g. jewelry). Pilot validation on high-resolution clinical samples demonstrates an Intersection over Union (IoU) stability greater than 0.67 across synthetic identities. By generating privacy-compliant synthetic surrogates at the edge, this framework mitigates the risk of gradient leakage at the source, providing a secure pathway for high-precision skin image analysis in federated environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.00689v1">Computing Maximal Per-Record Leakage and Leakage-Distortion Functions for Privacy Mechanisms under Entropy-Constrained Adversaries</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-31T12:23:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Genqiang Wu, Xiaoying Zhang, Yu Qi, Hao Wang, Jikui Wang, Yeping He</p>
    <p><b>Summary:</b> The exponential growth of data collection necessitates robust privacy protections that preserve data utility. We address information disclosure against adversaries with bounded prior knowledge, modeled by an entropy constraint $H(X) \geq b$. Within this information privacy framework -- which replaces differential privacy's independence assumption with a bounded-knowledge model -- we study three core problems: maximal per-record leakage, the primal leakage-distortion tradeoff (minimizing worst-case leakage under distortion $D$), and the dual distortion minimization (minimizing distortion under leakage constraint $L$).
  These problems resemble classical information-theoretic ones (channel capacity, rate-distortion) but are more complex due to high dimensionality and the entropy constraint. We develop efficient alternating optimization algorithms that exploit convexity-concavity duality, with theoretical guarantees including local convergence for the primal problem and convergence to a stationary point for the dual.
  Experiments on binary symmetric channels and modular sum queries validate the algorithms, showing improved privacy-utility tradeoffs over classical differential privacy mechanisms. This work provides a computational framework for auditing privacy risks and designing certified mechanisms under realistic adversary assumptions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.00515v1">Contrastive Learning for Privacy Enhancements in Industrial Internet of Things</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-01-31T05:11:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lin Liu, Rita Machacy, Simi Kuniyilh</p>
    <p><b>Summary:</b> The Industrial Internet of Things (IIoT) integrates intelligent sensing, communication, and analytics into industrial environments, including manufacturing, energy, and critical infrastructure. While IIoT enables predictive maintenance and cross-site optimization of modern industrial control systems, such as those in manufacturing and energy, it also introduces significant privacy and confidentiality risks due to the sensitivity of operational data. Contrastive learning, a self-supervised representation learning paradigm, has recently emerged as a promising approach for privacy-preserving analytics by reducing reliance on labeled data and raw data sharing. Although contrastive learning-based privacy-preserving techniques have been explored in the Internet of Things (IoT) domain, this paper offers a comprehensive review of these techniques specifically for privacy preservation in Industrial Internet of Things (IIoT) systems. It emphasizes the unique characteristics of industrial data, system architectures, and various application scenarios. Additionally, the paper discusses solutions and open challenges and outlines future research directions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.00417v1">Shuffle and Joint Differential Privacy for Generalized Linear Contextual Bandits</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-31T00:15:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sahasrajit Sarmasarkar</p>
    <p><b>Summary:</b> We present the first algorithms for generalized linear contextual bandits under shuffle differential privacy and joint differential privacy. While prior work on private contextual bandits has been restricted to linear reward models -- which admit closed-form estimators -- generalized linear models (GLMs) pose fundamental new challenges: no closed-form estimator exists, requiring private convex optimization; privacy must be tracked across multiple evolving design matrices; and optimization error must be explicitly incorporated into regret analysis.
  We address these challenges under two privacy models and context settings. For stochastic contexts, we design a shuffle-DP algorithm achieving $\tilde{O}(d^{3/2}\sqrt{T}/\sqrt{\varepsilon})$ regret. For adversarial contexts, we provide a joint-DP algorithm with $\tilde{O}(d\sqrt{T}/\sqrt{\varepsilon})$ regret -- matching the non-private rate up to a $1/\sqrt{\varepsilon}$ factor. Both algorithms remove dependence on the instance-specific parameter $κ$ (which can be exponential in dimension) from the dominant $\sqrt{T}$ term. Unlike prior work on locally private GLM bandits, our methods require no spectral assumptions on the context distribution beyond $\ell_2$ boundedness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.22945v1">Persuasive Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2026-01-30T13:03:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joshua J Bon, James Bailie, Judith Rousseau, Christian P Robert</p>
    <p><b>Summary:</b> We propose a novel framework for measuring privacy from a Bayesian game-theoretic perspective. This framework enables the creation of new, purpose-driven privacy definitions that are rigorously justified, while also allowing for the assessment of existing privacy guarantees through game theory. We show that pure and probabilistic differential privacy are special cases of our framework, and provide new interpretations of the post-processing inequality in this setting. Further, we demonstrate that privacy guarantees can be established for deterministic algorithms, which are overlooked by current privacy standards.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.22938v1">A Real-Time Privacy-Preserving Behavior Recognition System via Edge-Cloud Collaboration</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">  
  <p><b>Published on:</b> 2026-01-30T12:55:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Huan Song, Shuyu Tian, Junyi Hao, Cheng Yuan, Zhenyu Jia, Jiawei Shao, Xuelong Li</p>
    <p><b>Summary:</b> As intelligent sensing expands into high-privacy environments such as restrooms and changing rooms, the field faces a critical privacy-security paradox. Traditional RGB surveillance raises significant concerns regarding visual recording and storage, while existing privacy-preserving methods-ranging from physical desensitization to traditional cryptographic or obfuscation techniques-often compromise semantic understanding capabilities or fail to guarantee mathematical irreversibility against reconstruction attacks. To address these challenges, this study presents a novel privacy-preserving perception technology based on the AI Flow theoretical framework and an edge-cloud collaborative architecture. The proposed methodology integrates source desensitization with irreversible feature mapping. Leveraging Information Bottleneck theory, the edge device performs millisecond-level processing to transform raw imagery into abstract feature vectors via non-linear mapping and stochastic noise injection. This process constructs a unidirectional information flow that strips identity-sensitive attributes, rendering the reconstruction of original images impossible. Subsequently, the cloud platform utilizes multimodal family models to perform joint inference solely on these abstract vectors to detect abnormal behaviors. This approach fundamentally severs the path to privacy leakage at the architectural level, achieving a breakthrough from video surveillance to de-identified behavior perception and offering a robust solution for risk management in high-sensitivity public spaces.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.22935v1">Protecting Private Code in IDE Autocomplete using Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-01-30T12:51:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Evgeny Grigorenko, David Stanojević, David Ilić, Egor Bogomolov, Kostadin Cvejoski</p>
    <p><b>Summary:</b> Modern Integrated Development Environments (IDEs) increasingly leverage Large Language Models (LLMs) to provide advanced features like code autocomplete. While powerful, training these models on user-written code introduces significant privacy risks, making the models themselves a new type of data vulnerability. Malicious actors can exploit this by launching attacks to reconstruct sensitive training data or infer whether a specific code snippet was used for training. This paper investigates the use of Differential Privacy (DP) as a robust defense mechanism for training an LLM for Kotlin code completion. We fine-tune a \texttt{Mellum} model using DP and conduct a comprehensive evaluation of its privacy and utility. Our results demonstrate that DP provides a strong defense against Membership Inference Attacks (MIAs), reducing the attack's success rate close to a random guess (AUC from 0.901 to 0.606). Furthermore, we show that this privacy guarantee comes at a minimal cost to model performance, with the DP-trained model achieving utility scores comparable to its non-private counterpart, even when trained on 100x less data. Our findings suggest that DP is a practical and effective solution for building private and trustworthy AI-powered IDE features.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.22752v1">OSNIP: Breaking the Privacy-Utility-Efficiency Trilemma in LLM Inference via Obfuscated Semantic Null Space</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-30T09:29:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhiyuan Cao, Zeyu Ma, Chenhao Yang, Han Zheng, Mingang Chen</p>
    <p><b>Summary:</b> We propose Obfuscated Semantic Null space Injection for Privacy (OSNIP), a lightweight client-side encryption framework for privacy-preserving LLM inference. Generalizing the geometric intuition of linear kernels to the high-dimensional latent space of LLMs, we formally define the ``Obfuscated Semantic Null Space'', a high-dimensional regime that preserves semantic fidelity while enforcing near-orthogonality to the original embedding. By injecting perturbations that project the original embedding into this space, OSNIP ensures privacy without any post-processing. Furthermore, OSNIP employs a key-dependent stochastic mapping that synthesizes individualized perturbation trajectories unique to each user. Evaluations on 12 generative and classification benchmarks show that OSNIP achieves state-of-the-art performance, sharply reducing attack success rates while maintaining strong model utility under strict security constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.22710v1">AlienLM: Alienization of Language for API-Boundary Privacy in Black-Box LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-01-30T08:32:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jaehee Kim, Pilsung Kang</p>
    <p><b>Summary:</b> Modern LLMs are increasingly accessed via black-box APIs, requiring users to transmit sensitive prompts, outputs, and fine-tuning data to external providers, creating a critical privacy risk at the API boundary. We introduce AlienLM, a deployable API-only privacy layer that protects text by translating it into an Alien Language via a vocabulary-scale bijection, enabling lossless recovery on the client side. Using only standard fine-tuning APIs, Alien Adaptation Training (AAT) adapts target models to operate directly on alienized inputs. Across four LLM backbones and seven benchmarks, AlienLM retains over 81\% of plaintext-oracle performance on average, substantially outperforming random-bijection and character-level baselines. Under adversaries with access to model weights, corpus statistics, and learning-based inverse translation, recovery attacks reconstruct fewer than 0.22\% of alienized tokens. Our results demonstrate a practical pathway for privacy-preserving LLM deployment under API-only access, substantially reducing plaintext exposure while maintaining task performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.22625v1">RPWithPrior: Label Differential Privacy in Regression</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-30T06:27:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haixia Liu, Ruifan Huang</p>
    <p><b>Summary:</b> With the wide application of machine learning techniques in practice, privacy preservation has gained increasing attention. Protecting user privacy with minimal accuracy loss is a fundamental task in the data analysis and mining community. In this paper, we focus on regression tasks under $ε$-label differential privacy guarantees. Some existing methods for regression with $ε$-label differential privacy, such as the RR-On-Bins mechanism, discretized the output space into finite bins and then applied RR algorithm. To efficiently determine these finite bins, the authors rounded the original responses down to integer values. However, such operations does not align well with real-world scenarios. To overcome these limitations, we model both original and randomized responses as continuous random variables, avoiding discretization entirely. Our novel approach estimates an optimal interval for randomized responses and introduces new algorithms designed for scenarios where a prior is either known or unknown. Additionally, we prove that our algorithm, RPWithPrior, guarantees $ε$-label differential privacy. Numerical results demonstrate that our approach gets better performance compared with the Gaussian, Laplace, Staircase, and RRonBins, Unbiased mechanisms on the Communities and Crime, Criteo Sponsored Search Conversion Log, California Housing datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.22434v1">Rethinking Anonymity Claims in Synthetic Data Generation: A Model-Centric Privacy Attack Perspective</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-30T00:57:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Georgi Ganev, Emiliano De Cristofaro</p>
    <p><b>Summary:</b> Training generative machine learning models to produce synthetic tabular data has become a popular approach for enhancing privacy in data sharing. As this typically involves processing sensitive personal information, releasing either the trained model or generated synthetic datasets can still pose privacy risks. Yet, recent research, commercial deployments, and privacy regulations like the General Data Protection Regulation (GDPR) largely assess anonymity at the level of an individual dataset.
  In this paper, we rethink anonymity claims about synthetic data from a model-centric perspective and argue that meaningful assessments must account for the capabilities and properties of the underlying generative model and be grounded in state-of-the-art privacy attacks. This perspective better reflects real-world products and deployments, where trained models are often readily accessible for interaction or querying. We interpret the GDPR's definitions of personal data and anonymization under such access assumptions to identify the types of identifiability risks that must be mitigated and map them to privacy attacks across different threat settings. We then argue that synthetic data techniques alone do not ensure sufficient anonymization. Finally, we compare the two mechanisms most commonly used alongside synthetic data -- Differential Privacy (DP) and Similarity-based Privacy Metrics (SBPMs) -- and argue that while DP can offer robust protections against identifiability risks, SBPMs lack adequate safeguards. Overall, our work connects regulatory notions of identifiability with model-centric privacy attacks, enabling more responsible and trustworthy regulatory assessment of synthetic data systems by researchers, practitioners, and policymakers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.22409v2">Optimization, Generalization and Differential Privacy Bounds for Gradient Descent on Kolmogorov-Arnold Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> 
  <p><b>Published on:</b> 2026-01-29T23:43:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Puyu Wang, Junyu Zhou, Philipp Liznerski, Marius Kloft</p>
    <p><b>Summary:</b> Kolmogorov--Arnold Networks (KANs) have recently emerged as a structured alternative to standard MLPs, yet a principled theory for their training dynamics, generalization, and privacy properties remains limited. In this paper, we analyze gradient descent (GD) for training two-layer KANs and derive general bounds that characterize their training dynamics, generalization, and utility under differential privacy (DP). As a concrete instantiation, we specialize our analysis to logistic loss under an NTK-separable assumption, where we show that polylogarithmic network width suffices for GD to achieve an optimization rate of order $1/T$ and a generalization rate of order $1/n$, with $T$ denoting the number of GD iterations and $n$ the sample size. In the private setting, we characterize the noise required for $(ε,δ)$-DP and obtain a utility bound of order $\sqrt{d}/(nε)$ (with $d$ the input dimension), matching the classical lower bound for general convex Lipschitz problems. Our results imply that polylogarithmic width is not only sufficient but also necessary under differential privacy, revealing a qualitative gap between non-private (sufficiency only) and private (necessity also emerges) training regimes. Experiments further illustrate how these theoretical insights can guide practical choices, including network width selection and early stopping.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.22320v1">Matrix Factorization for Practical Continual Mean Estimation Under User-Level Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2026-01-29T21:02:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nikita P. Kalinin, Ali Najar, Valentin Roth, Christoph H. Lampert</p>
    <p><b>Summary:</b> We study continual mean estimation, where data vectors arrive sequentially and the goal is to maintain accurate estimates of the running mean. We address this problem under user-level differential privacy, which protects each user's entire dataset even when they contribute multiple data points. Previous work on this problem has focused on pure differential privacy. While important, this approach limits applicability, as it leads to overly noisy estimates. In contrast, we analyze the problem under approximate differential privacy, adopting recent advances in the Matrix Factorization mechanism. We introduce a novel mean estimation specific factorization, which is both efficient and accurate, achieving asymptotically lower mean-squared error bounds in continual mean estimation under user-level differential privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.22265v1">Privacy-Preserving Sensor-Based Human Activity Recognition for Low-Resource Healthcare Using Classical Machine Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-01-29T19:35:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ramakant Kumar, Pravin Kumar</p>
    <p><b>Summary:</b> Limited access to medical infrastructure forces elderly and vulnerable patients to rely on home-based care, often leading to neglect and poor adherence to therapeutic exercises such as yoga or physiotherapy. To address this gap, we propose a low-cost and automated human activity recognition (HAR) framework based on wearable inertial sensors and machine learning. Activity data, including walking, walking upstairs, walking downstairs, sitting, standing, and lying, were collected using accelerometer and gyroscope measurements. Four classical classifiers, Logistic Regression, Random Forest, Support Vector Machine (SVM), and k-Nearest Neighbors (k-NN), were evaluated and compared with the proposed Support Tensor Machine (STM). Experimental results show that SVM achieved an accuracy of 93.33 percent, while Logistic Regression, Random Forest, and k-NN achieved 91.11 percent. In contrast, STM significantly outperformed these models, achieving a test accuracy of 96.67 percent and the highest cross-validation accuracy of 98.50 percent. Unlike conventional methods, STM leverages tensor representations to preserve spatio-temporal motion dynamics, resulting in robust classification across diverse activities. The proposed framework demonstrates strong potential for remote healthcare, elderly assistance, child activity monitoring, yoga feedback, and smart home wellness, offering a scalable solution for low-resource and rural healthcare settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.22104v1">Social Media Data for Population Mapping: A Bayesian Approach to Address Representativeness and Privacy Challenges</a></h3>
   
  <p><b>Published on:</b> 2026-01-29T18:36:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Paolo Andrich, Shengjie Lai, Halim Jun, Qianwen Duan, Zhifeng Cheng, Seth R. Flaxman, Andrew J. Tatem</p>
    <p><b>Summary:</b> Accurate and timely population data are essential for disaster response and humanitarian planning, but traditional censuses often cannot capture rapid demographic changes. Social media data offer a promising alternative for dynamic population monitoring, but their representativeness remains poorly understood and stringent privacy requirements limit their reliability. Here, we address these limitations in the context of the Philippines by calibrating Facebook user counts with the country's 2020 census figures. First, we find that differential privacy techniques commonly applied to social media-based population datasets disproportionately mask low-population areas. To address this, we propose a Bayesian imputation approach to recover missing values, restoring data coverage for $5.5\%$ of rural areas. Further, using the imputed social media data and leveraging predictors such as urbanisation level, demographic composition, and socio-economic status, we develop a statistical model for the proportion of Facebook users in each municipality, which links observed Facebook user numbers to the true population levels. Out-of-sample validation demonstrates strong result generalisability, with errors as low as ${\approx}18\%$ and ${\approx}24\%$ for urban and rural Facebook user proportions, respectively. We further demonstrate that accounting for overdispersion and spatial correlations in the data is crucial to obtain accurate estimates and appropriate credible intervals. Crucially, as predictors change over time, the models can be used to regularly update the population predictions, providing a dynamic complement to census-based estimates. These results have direct implications for humanitarian response in disaster-prone regions and offer a general framework for using biased social media signals to generate reliable and timely population data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.21859v1">Adaptive Privacy of Sequential Data Releases Under Collusion</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-01-29T15:29:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sophie Taylor, Praneeth Kumar Vippathalla, Justin Coon</p>
    <p><b>Summary:</b> The fundamental trade-off between privacy and utility remains an active area of research. Our contribution is motivated by two observations. First, privacy mechanisms developed for one-time data release cannot straightforwardly be extended to sequential releases. Second, practical databases are likely to be useful to multiple distinct parties. Furthermore, we can not rule out the possibility of data sharing between parties. With utility in mind, we formulate a privacy-utility trade-off problem to adaptively tackle sequential data requests made by different, potentially colluding entities. We consider both expected distortion and mutual information as measures to quantify utility, and use mutual information to measure privacy. We assume an attack model whereby illicit data sharing, which we call collusion, can occur between data receivers. We develop an adaptive algorithm for data releases that makes use of a modified Blahut-Arimoto algorithm. We show that the resulting data releases are optimal when expected distortion quantifies utility, and locally optimal when mutual information quantifies utility. Finally, we discuss how our findings may extend to applications in machine learning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.21719v1">LoRA and Privacy: When Random Projections Help (and When They Don't)</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2026-01-29T13:43:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yaxi Hu, Johanna Düngler, Bernhard Schölkopf, Amartya Sanyal</p>
    <p><b>Summary:</b> We introduce the (Wishart) projection mechanism, a randomized map of the form $S \mapsto M f(S)$ with $M \sim W_d(1/r I_d, r)$ and study its differential privacy properties. For vector-valued queries $f$, we prove non-asymptotic DP guarantees without any additive noise, showing that Wishart randomness alone can suffice. For matrix-valued queries, however, we establish a sharp negative result: in the noise-free setting, the mechanism is not DP, and we demonstrate its vulnerability by implementing a near perfect membership inference attack (AUC $> 0.99$). We then analyze a noisy variant and prove privacy amplification due to randomness and low rank projection, in both large- and small-rank regimes, yielding stronger privacy guarantees than additive noise alone. Finally, we show that LoRA-style updates are an instance of the matrix-valued mechanism, implying that LoRA is not inherently private despite its built-in randomness, but that low-rank fine-tuning can be more private than full fine-tuning at the same noise level. Preliminary experiments suggest that tighter accounting enables lower noise and improved accuracy in practice.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.21636v2">Sampling-Free Privacy Accounting for Matrix Mechanisms under Random Allocation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2026-01-29T12:40:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jan Schuchardt, Nikita Kalinin</p>
    <p><b>Summary:</b> We study privacy amplification for differentially private model training with matrix factorization under random allocation (also known as the balls-in-bins model). Recent work by Choquette-Choo et al. (2025) proposes a sampling-based Monte Carlo approach to compute amplification parameters in this setting. However, their guarantees either only hold with some high probability or require random abstention by the mechanism. Furthermore, the required number of samples for ensuring $(ε,δ)$-DP is inversely proportional to $δ$. In contrast, we develop sampling-free bounds based on Rényi divergence and conditional composition. The former is facilitated by a dynamic programming formulation to efficiently compute the bounds. The latter complements it by offering stronger privacy guarantees for small $ε$, where Rényi divergence bounds inherently lead to an over-approximation. Our framework applies to arbitrary banded and non-banded matrices. Through numerical comparisons, we demonstrate the efficacy of our approach across a broad range of matrix mechanisms used in research and practice.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.21265v1">A Quantum-Memory-Free Quantum Secure Direct Communication Protocol Based on Privacy Amplification of Coded Sequences</a></h3>
  
  <p><b>Published on:</b> 2026-01-29T04:55:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shang-Jen Su, Shi-Yuan Wang, Matthieu R. Bloch</p>
    <p><b>Summary:</b> We develop an information-theoretic analysis of Quantum-Memory-Free (QMF) Quantum Secure Direct Communication (QSDC) under collective attacks as an alternative to the conventional Quantum Key Distribution (QKD) protocol with one-time pads. Our main contributions are: 1) a QMF-QSDC protocol that only relies on universal hashing of coded sequences without wiretap coding; 2) a set of privacy amplification theorems for extracting secrecy from coded classical sequences against quantum side-information. These tools open the way to the design of robust QMF-QSDC protocols.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.20792v1">Jurisdiction as Structural Barrier: How Privacy Policy Organization May Reduce Visibility of Substantive Disclosures</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-01-28T17:29:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Thomas Brackin</p>
    <p><b>Summary:</b> Privacy policies are supposed to provide notice. But what if substantive information appears only where users skip it? We identify a structural pattern we call jurisdiction-siloed disclosure: information about data practices appearing in specific, actionable form only within regional compliance sections labeled "California Residents" or "EU/UK Users," while general sections use vague or qualified language for the same practices.
  Our audit of 123 major companies identifies 282 potential instances across 77 companies (62.6% of this purposive sample). A conservative estimate restricted to practice categories validated against OPP-115 human annotations finds 138 instances across 54 companies (44%); post-2018 categories central to our findings await independent validation. If users skip jurisdiction-labeled sections as information foraging theory predicts, users outside regulated jurisdictions would receive less specific information about practices affecting them--a transparency failure operating through document architecture rather than omission.
  We propose universal substantive disclosure: practices affecting all users should appear in the main policy body, with regional sections containing only procedural rights information. This standard finds support in analogous disclosure regimes (securities, truth-in-lending, nutritional labeling) where material information must reach all affected parties. Regulators could operationalize this through the FTC's "clear and conspicuous" standard and GDPR transparency principles.
  This work is hypothesis-generating: we establish that the structural pattern exists and ground the transparency concern in behavioral theory, but direct measurement of jurisdiction-specific section skipping remains the critical validation priority. We release our methodology and annotated dataset to enable replication.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.20716v1">Decentralized Identity in Practice: Benchmarking Latency, Cost, and Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2026-01-28T15:48:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abylay Satybaldy, Kamil Tylinski, Jiahua Xu</p>
    <p><b>Summary:</b> Decentralized Identifiers (DIDs) are increasingly deployed on distributed ledgers, yet systematic cross-platform evidence on their operational behavior remains limited. We present an empirical benchmarking study of three prominent ledger-based DID methods - Ethereum, Hedera, and XRP Ledger - using reference Software Development Kits (SDKs) under a unified experimental setup. We measure latency, transaction cost, and on-chain metadata exposure, normalizing latency by each platform's block or consensus interval and cost by its native value transfer fee. Privacy leakage is quantified using a Metadata-Leakage Score (MLS), an entropy-based measure expressed in bits per operation.
  Our results reveal distinct architectural trade-offs. Ethereum enables near-instant, off-chain DID creation, but incurs the highest latency and cost for on-chain lifecycle operations. XRPL delivers deterministic and stable latency with fixed, low fees, yet exhibits higher metadata leakage due to more verbose transaction payloads. Hedera achieves the lowest on-chain latency and low fees with minimal metadata leakage, while occasional variance arises from SDK-side processing and confirmation pipelines.
  Overall, the findings show that ledger architecture and SDK workflows play a major role in shaping DID latency, cost, and metadata exposure, complementing the effects of the underlying consensus mechanism. These results provide evidence-based insights to support informed selection and configuration of DID systems under performance and privacy constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.20325v1">UnlearnShield: Shielding Forgotten Privacy against Unlearning Inversion</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-01-28T07:42:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lulu Xue, Shengshan Hu, Wei Lu, Ziqi Zhou, Yufei Song, Jianhong Cheng, Minghui Li, Yanjun Zhang, Leo Yu Zhang</p>
    <p><b>Summary:</b> Machine unlearning is an emerging technique that aims to remove the influence of specific data from trained models, thereby enhancing privacy protection. However, recent research has uncovered critical privacy vulnerabilities, showing that adversaries can exploit unlearning inversion to reconstruct data that was intended to be erased. Despite the severity of this threat, dedicated defenses remain lacking. To address this gap, we propose UnlearnShield, the first defense specifically tailored to counter unlearning inversion. UnlearnShield introduces directional perturbations in the cosine representation space and regulates them through a constraint module to jointly preserve model accuracy and forgetting efficacy, thereby reducing inversion risk while maintaining utility. Experiments demonstrate that it achieves a good trade-off among privacy protection, accuracy, and forgetting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.20161v2">Supporting Informed Self-Disclosure: Design Recommendations for Presenting AI-Estimates of Privacy Risks to Users</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-01-28T01:35:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Isadora Krsek, Meryl Ye, Wei Xu, Alan Ritter, Laura Dabbish, Sauvik Das</p>
    <p><b>Summary:</b> People candidly discuss sensitive topics online under the perceived safety of anonymity; yet, for many, this perceived safety is tenuous, as miscalibrated risk perceptions can lead to over-disclosure. Recent advances in Natural Language Processing (NLP) afford an unprecedented opportunity to present users with quantified disclosure-based re-identification risk (i.e., "population risk estimates", PREs). How can PREs be presented to users in a way that promotes informed decision-making, mitigating risk without encouraging unnecessary self-censorship? Using design fictions and comic-boarding, we story-boarded five design concepts for presenting PREs to users and evaluated them through an online survey with N = 44 Reddit users. We found participants had detailed conceptions of how PREs may impact risk awareness and motivation, but envisioned needing additional context and support to effectively interpret and act on risks. We distill our findings into four key design recommendations for how best to present users with quantified privacy risks to support informed disclosure decision-making.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.19837v1">Self-Sovereign Identity and eIDAS 2.0: An Analysis of Control, Privacy, and Legal Implications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2026-01-27T17:43:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nacereddine Sitouah, Marco Esposito, Francesco Bruschi</p>
    <p><b>Summary:</b> European digital identity initiatives are grounded in regulatory frameworks designed to ensure interoperability and robust, harmonized security standards. The evolution of these frameworks culminates in eIDAS 2.0, whose origins trace back to the Electronic Signatures Directive 1999/93/EC, the first EU-wide legal foundation for the use of electronic signatures in cross-border electronic transactions. As technological capabilities advanced, the initial eIDAS 1.0 framework was increasingly criticized for its limitations and lack of comprehensiveness. Emerging decentralized approaches further exposed these shortcomings and introduced the possibility of integrating innovative identity paradigms, such as Self-Sovereign Identity (SSI) models.
  In this article, we analyse key provisions of the eIDAS 2.0 Regulation and its accompanying recitals, drawing on existing literature to identify legislative gaps and implementation challenges. Furthermore, we examine the European Digital Identity Architecture and Reference Framework (ARF), assessing its proposed guidelines and evaluating the extent to which its emerging implementations align with SSI principles.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.19575v3">Putting Privacy to the Test: Introducing Red Teaming for Research Data Anonymization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-01-27T13:04:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Luisa Jansen, Tim Ulmann, Robine Jordi, Malte Elson</p>
    <p><b>Summary:</b> Recently, the data protection practices of researchers in human-computer interaction and elsewhere have gained attention. Initial results suggest that researchers struggle with anonymization, partly due to a lack of clear, actionable guidance. In this work, we propose simulating re-identification attacks using the approach of red teaming versus blue teaming: a technique commonly employed in security testing, where one team tries to re-identify data, and the other team tries to prevent it. We discuss our experience applying this method to data collected in a mixed-methods study in human-centered privacy. We present usable materials for researchers to apply red teaming when anonymizing and publishing their studies' data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.19502v1">VisGuardian: A Lightweight Group-based Privacy Control Technique For Front Camera Data From AR Glasses in Home Environments</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-27T11:41:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuning Zhang, Qucheng Zang, Yongquan `Owen' Hu, Jiachen Du, Xueyang Wang, Yan Kong, Xinyi Fu, Suranga Nanayakkara, Xin Yi, Hewu Li</p>
    <p><b>Summary:</b> Always-on sensing of AI applications on AR glasses makes traditional permission techniques ill-suited for context-dependent visual data, especially within home environments. The home presents a highly challenging privacy context due to the high density of sensitive objects, and the frequent presence of non-consenting family members, and the intimate nature of daily routines, making it a critical focus area for scalable privacy control mechanisms. Existing fine-grained controls, while offering nuanced choices, are inefficient for managing multiple private objects. We propose VisGuardian, a fine-grained content-based visual permission technique for AR glasses. VisGuardian features a group-based control mechanism that enables users to efficiently manage permissions for multiple private objects. VisGuardian detects objects using YOLO and adopts a pre-classified schema to group them. By selecting a single object, users can efficiently obscure groups of related objects based on criteria including privacy sensitivity, object category, or spatial proximity. A technical evaluation shows VisGuardian achieves mAP50 of 0.6704 with only 14.0 ms latency and a 1.7% increase in battery consumption per hour. Furthermore, a user study (N=24) comparing VisGuardian to slider-based and object-based baselines found it to be significantly faster for setting permissions and was preferred by users for its efficiency, effectiveness, and ease of use.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.19956v1">VoxPrivacy: A Benchmark for Evaluating Interactional Privacy of Speech Language Models</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36">
  <p><b>Published on:</b> 2026-01-27T06:22:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuxiang Wang, Hongyu Liu, Dekun Chen, Xueyao Zhang, Zhizheng Wu</p>
    <p><b>Summary:</b> As Speech Language Models (SLMs) transition from personal devices to shared, multi-user environments such as smart homes, a new challenge emerges: the model is expected to distinguish between users to manage information flow appropriately. Without this capability, an SLM could reveal one user's confidential schedule to another, a privacy failure we term interactional privacy. Thus, the ability to generate speaker-aware responses becomes essential for SLM safe deployment. Current SLM benchmarks test dialogue ability but overlook speaker identity. Multi-speaker benchmarks check who said what without assessing whether SLMs adapt their responses. Privacy benchmarks focus on globally sensitive data (e.g., bank passwords) while neglecting contextual privacy-sensitive information (e.g., a user's private appointment). To address this gap, we introduce VoxPrivacy, the first benchmark designed to evaluate interactional privacy in SLMs. VoxPrivacy spans three tiers of increasing difficulty, from following direct secrecy commands to proactively protecting privacy. Our evaluation of nine SLMs on a 32-hour bilingual dataset reveals a widespread vulnerability: most open-source models perform close to random chance (around 50% accuracy) on conditional privacy decisions, while even strong closed-source systems fall short on proactive privacy inference. We further validate these findings on Real-VoxPrivacy, a human-recorded subset, confirming that failures observed on synthetic data persist in real speech. Finally, we demonstrate a viable path forward: by fine-tuning on a new 4,000-hour training set, we improve privacy-preserving abilities while maintaining robustness. To support future work, we release the VoxPrivacy benchmark, the large-scale training set, and the fine-tuned model to foster the development of safer and more context-aware SLMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.19206v1">Universal Operational Privacy in Distributed Quantum Sensing</a></h3>
  
  <p><b>Published on:</b> 2026-01-27T05:17:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Min Namkung, Dong-Hyun Kim, Seongjin Hong, Yong-Su Kim, Su-Yong Lee, Hyang-Tag Lim</p>
    <p><b>Summary:</b> Privacy is a fundamental requirement in distributed quantum sensing networks, where multiple clients estimate spatially distributed parameters using shared quantum resources while interacting with potentially untrusted servers. Despite its importance, existing privacy conditions rely on idealized quantum bounds and do not fully capture the operational constraints imposed by realistic measurements. Here, we introduce a universal operational privacy framework for distributed quantum sensing, formulated in terms of the experimentally accessible classical Fisher information matrix and applicable to arbitrary protocols characterized by singular information structures. The proposed condition provides a protocol-independent criterion ensuring that no information about individual parameters is accessible to untrusted parties. We further experimentally demonstrate that a distributed quantum sensing protocol employing fewer photons than the number of estimated parameters simultaneously satisfies the universal privacy condition and achieves Heisenberg-limited precision. Our results establish universal operational constraints governing privacy in distributed quantum sensing networks and provide a foundation for practical, privacy-preserving quantum sensing beyond full-rank regimes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.19154v2">Analysis of Shuffling Beyond Pure Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-01-27T03:35:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shun Takagi, Seng Pei Liew</p>
    <p><b>Summary:</b> Shuffling is a powerful way to amplify privacy of a local randomizer in private distributed data analysis, but existing analyses mostly treat the local differential privacy (DP) parameter $\varepsilon_0$ as the only knob and give generic upper bounds that can be loose and do not even characterize how shuffling amplifies privacy for basic mechanisms such as the Gaussian mechanism. We revisit the privacy blanket bound of Balle et al. (the blanket divergence) and develop an asymptotic analysis that applies to a broad class of local randomizers under mild regularity assumptions, without requiring pure local DP. Our key finding is that the leading term of the blanket divergence depends on the local mechanism only through a single scalar parameter $χ$, which we call the shuffle index. By applying this asymptotic analysis to both upper and lower bounds, we obtain a tight band for $δ_n$ in the shuffled mechanism's $(\varepsilon_n,δ_n)$-DP guarantee. Moreover, we derive a simple structural necessary and sufficient condition on the local randomizer under which the blanket-divergence-based upper and lower bounds coincide asymptotically. $k$-RR families with $k\ge3$ satisfy this condition, while for generalized Gaussian mechanisms the condition may not hold but the resulting band remains tight. Finally, we complement the asymptotic theory with an FFT-based algorithm for computing the blanket divergence at finite $n$, which offers rigorously controlled relative error and near-linear running time in $n$, providing a practical numerical analysis for shuffle DP.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.19126v1">How Entanglement Reshapes the Geometry of Quantum Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2026-01-27T02:50:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xi Wang, Parastoo Sadeghi, Guodong Shi</p>
    <p><b>Summary:</b> Quantum differential privacy provides a rigorous framework for quantifying privacy guarantees in quantum information processing. While classical correlations are typically regarded as adversarial to privacy, the role of their quantum analogue, entanglement, is not well understood. In this work, we investigate how quantum entanglement fundamentally shapes quantum local differential privacy (QLDP). We consider a bipartite quantum system whose input state has a prescribed level of entanglement, characterized by a lower bound on the entanglement entropy. Each subsystem is then processed by a local quantum mechanism and measured using local operations only, ensuring that no additional entanglement is generated during the process. Our main result reveals a sharp phase-transition phenomenon in the relation between entanglement and QLDP: below a mechanism-dependent entropy threshold, the optimal privacy leakage level mirrors that of unentangled inputs; beyond this threshold, the privacy leakage level decreases with the entropy, which strictly improves privacy guarantees and can even turn some non-private mechanisms into private ones. The phase-transition phenomenon gives rise to a nonlinear dependence of the privacy leakage level on the entanglement entropy, even though the underlying quantum mechanisms and measurements are linear. We show that the transition is governed by the intrinsic non-convex geometry of the set of entanglement-constrained quantum states, which we parametrize as a smooth manifold and analyze via Riemannian optimization. Our findings demonstrate that entanglement serves as a genuine privacy-enhancing resource, offering a geometric and operational foundation for designing robust privacy-preserving quantum protocols.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.19090v1">Privacy-Preserving Model Transcription with Differentially Private Synthetic Distillation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-01-27T01:51:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bochao Liu, Shiming Ge, Pengju Wang, Shikun Li, Tongliang Liu</p>
    <p><b>Summary:</b> While many deep learning models trained on private datasets have been deployed in various practical tasks, they may pose a privacy leakage risk as attackers could recover informative data or label knowledge from models. In this work, we present \emph{privacy-preserving model transcription}, a data-free model-to-model conversion solution to facilitate model deployment with a privacy guarantee. To this end, we propose a cooperative-competitive learning approach termed \emph{differentially private synthetic distillation} that learns to convert a pretrained model (teacher) into its privacy-preserving counterpart (student) via a trainable generator without access to private data. The learning collaborates with three players in a unified framework and performs alternate optimization: i)~the generator is learned to generate synthetic data, ii)~the teacher and student accept the synthetic data and compute differential private labels by flexible data or label noisy perturbation, and iii)~the student is updated with noisy labels and the generator is updated by taking the student as a discriminator for adversarial training. We theoretically prove that our approach can guarantee differential privacy and convergence. The transcribed student has good performance and privacy protection, while the resulting generator can generate private synthetic data for downstream tasks. Extensive experiments clearly demonstrate that our approach outperforms 26 state-of-the-arts.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.18661v1">Balancing Privacy and Robustness in Coded Computing Under Profiled Workers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-01-26T16:37:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rimpi Borah, J. Harshan, Aaditya Sharma</p>
    <p><b>Summary:</b> In distributed computing with untrusted workers, the assignment of evaluation indices plays a critical role in determining both privacy and robustness. In this work, we study how the placement of unreliable workers within the Numerically Stable Lagrange Coded Computing (NS-LCC) framework influences privacy and the ability to localize Byzantine errors. We derive analytical bounds that quantify how different evaluation-index assignments affect privacy against colluding curious workers and robustness against Byzantine corruption under finite-precision arithmetic. Using these bounds, we formulate optimization problems that identify privacy-optimal and robustness-optimal index placements and show that the resulting assignments are fundamentally different. This exposes that index choices that maximizes privacy degrade error-localization, and vice versa. To jointly navigate this trade-off, we propose a low-complexity greedy assignment strategy that closely approximates the optimal balance between privacy and robustness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.18612v1">Multimodal Privacy-Preserving Entity Resolution with Fully Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-01-26T15:53:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Susim Roy, Nalini Ratha</p>
    <p><b>Summary:</b> The canonical challenge of entity resolution within high-compliance sectors, where secure identity reconciliation is frequently confounded by significant data heterogeneity, including syntactic variations in personal identifiers, is a longstanding and complex problem. To this end, we introduce a novel multimodal framework operating with the voluminous data sets typical of government and financial institutions. Specifically, our methodology is designed to address the tripartite challenge of data volume, matching fidelity, and privacy. Consequently, the underlying plaintext of personally identifiable information remains computationally inaccessible throughout the matching lifecycle, empowering institutions to rigorously satisfy stringent regulatory mandates with cryptographic assurances of client confidentiality while achieving a demonstrably low equal error rate and maintaining computational tractability at scale.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.18511v1">Scaling up Privacy-Preserving ML: A CKKS Implementation of Llama-2-7B</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-26T14:17:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jaiyoung Park, Sejin Park, Jai Hyun Park, Jung Ho Ahn, Jung Hee Cheon, Guillaume Hanrot, Jung Woo Kim, Minje Park, Damien Stehlé</p>
    <p><b>Summary:</b> As large language models (LLMs) become ubiquitous, privacy concerns pertaining to inference inputs keep growing. In this context, fully homomorphic encryption (FHE) has emerged as a primary cryptographic solution to provide non-interactive confidential LLM inference. Existing solutions scale poorly with the input token length, and hence focus either on small models or larger models with a small number of input tokens. They also suffer from the existence of large outlier values. These values have a strong impact on the evaluation of non-linear layers, leading to large-degree polynomial approximation and thus heavy evaluation costs.
  We propose an FHE-based private LLM inference solution that allows thousands of input tokens with only a part of them being encrypted: this fits with a scenario where the context is benign and only part of the input is sensitive. To do so, we suggest an unbalanced chunked prefill framework that processes the private and public parts of the input tokens differently. Our framework contains plaintext-plaintext, plaintext-ciphertext and ciphertext-ciphertext computational components. We adopt different strategies and ingredients for each component. We also devise new homomorphic algorithms for specific matrix multiplication and polynomial evaluation tasks encountered during LLM inference.
  Furthermore, without retraining, we tailor the LLM inference algorithm to reduce the ranges of outlier values: we leverage machine learning strategies (token prepending and rotations) to mitigate the impact of the outliers on non-linear layers.
  Based on these ingredients, we describe a CKKS-based end-to-end implementation of Llama-2-7B private inference for up to 4096 input tokens, of which the last 128 are encrypted. On a cluster of 8~NVIDIA RTX-4090 GPUs, inference takes 85s for summarization and 33s for generation per output token.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.18497v2">BAIT: Visual-illusion-inspired Privacy Preservation for Mobile Data Visualization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-01-26T13:58:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sizhe Cheng, Songheng Zhang, Dong Ma, Yong Wang</p>
    <p><b>Summary:</b> With the prevalence of mobile data visualizations, there have been growing concerns about their privacy risks, especially shoulder surfing attacks. Inspired by prior research on visual illusion, we propose BAIT, a novel approach to automatically generate privacy-preserving visualizations by stacking a decoy visualization over a given visualization. It allows visualization owners at proximity to clearly discern the original visualization and makes shoulder surfers at a distance be misled by the decoy visualization, by adjusting different visual channels of a decoy visualization (e.g., shape, position, tilt, size, color and spatial frequency). We explicitly model human perception effect at different viewing distances to optimize the decoy visualization design. Privacy-preserving examples and two in-depth user studies demonstrate the effectiveness of BAIT in both controlled lab study and real-world scenarios.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.18842v2">GUIGuard: Toward a General Framework for Privacy-Preserving GUI Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-01-26T11:33:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yanxi Wang, Zhiling Zhang, Wenbo Zhou, Weiming Zhang, Jie Zhang, Qiannan Zhu, Yu Shi, Shuxin Zheng, Jiyan He</p>
    <p><b>Summary:</b> GUI agents enable end-to-end automation through direct perception of and interaction with on-screen interfaces. However, these agents frequently access interfaces containing sensitive personal information, and screenshots are often transmitted to remote models, creating substantial privacy risks. These risks are particularly severe in GUI workflows: GUIs expose richer, more accessible private information, and privacy risks depend on interaction trajectories across sequential scenes. We propose GUIGuard, a three-stage framework for privacy-preserving GUI agents: (1) privacy recognition, (2) privacy protection, and (3) task execution under protection. We further construct GUIGuard-Bench, a cross-platform benchmark with 630 trajectories and 13,830 screenshots, annotated with region-level privacy grounding and fine-grained labels of risk level, privacy category, and task necessity. Evaluations reveal that existing agents exhibit limited privacy recognition, with state-of-the-art models achieving only 13.3% accuracy on Android and 1.4% on PC. Under privacy protection, task-planning semantics can still be maintained, with closed-source models showing stronger semantic consistency than open-source ones. Case studies on MobileWorld show that carefully designed protection strategies achieve higher task accuracy while preserving privacy. Our results highlight privacy recognition as a critical bottleneck for practical GUI agents. Project: https://futuresis.github.io/GUIGuard-page/</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.18125v1">Understanding Users' Privacy Reasoning and Behaviors During Chatbot Use to Support Meaningful Agency in Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-01-26T04:13:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohammad Hadi Nezhad, Francisco Enrique Vicente Castro, Ivon Arroyo</p>
    <p><b>Summary:</b> Conversational agents (CAs) (e.g., chatbots) are increasingly used in settings where users disclose sensitive information, raising significant privacy concerns. Because privacy judgments are highly contextual, supporting users to engage in privacy-protective actions during chatbot interactions is essential. However, enabling meaningful engagement requires a deeper understanding of how users currently reason about and manage sensitive information during realistic chatbot use scenarios. To investigate this, we qualitatively examined computer science (undergraduate and masters) students' in-the-moment disclosure and protection behaviors, as well as the reasoning underlying these behaviors, across a range of realistic chatbot tasks. Participants used a simulated ChatGPT interface with and without a privacy notice panel that intercepts message submissions, highlights potentially sensitive information, and offers privacy protective actions. The panel supports anonymization through retracting, faking, and generalizing, and surfaces two of ChatGPT's built-in privacy controls to improve their discoverability. Drawing on interaction logs, think-alouds, and survey responses, we analyzed how the panel fostered privacy awareness, encouraged protective actions, and supported context-specific reasoning about what information to protect and how. We further discuss design opportunities for tools that provide users greater and more meaningful agency in protecting sensitive information during CA interactions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.18834v1">CanaryBench: Stress Testing Privacy Leakage in Cluster-Level Conversation Summaries</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-01-25T20:30:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Deep Mehta</p>
    <p><b>Summary:</b> Aggregate analytics over conversational data are increasingly used for safety monitoring, governance, and product analysis in large language model systems. A common practice is to embed conversations, cluster them, and publish short textual summaries describing each cluster. While raw conversations may never be exposed, these derived summaries can still pose privacy risks if they contain personally identifying information (PII) or uniquely traceable strings copied from individual conversations.
  We introduce CanaryBench, a simple and reproducible stress test for privacy leakage in cluster-level conversation summaries. CanaryBench generates synthetic conversations with planted secret strings ("canaries") that simulate sensitive identifiers. Because canaries are known a priori, any appearance of these strings in published summaries constitutes a measurable leak.
  Using TF-IDF embeddings and k-means clustering on 3,000 synthetic conversations (24 topics) with a canary injection rate of 0.60, we evaluate an intentionally extractive example snippet summarizer that models quote-like reporting. In this configuration, we observe canary leakage in 50 of 52 canary-containing clusters (cluster-level leakage rate 0.961538), along with nonzero regex-based PII indicator counts. A minimal defense combining a minimum cluster-size publication threshold (k-min = 25) and regex-based redaction eliminates measured canary leakage and PII indicator hits in the reported run while maintaining a similar cluster-coherence proxy. We position this work as a societal impacts contribution centered on privacy risk measurement for published analytics artifacts rather than raw user data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.17935v1">FedGraph-VASP: Privacy-Preserving Federated Graph Learning with Post-Quantum Security for Cross-Institutional Anti-Money Laundering</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B">
  <p><b>Published on:</b> 2026-01-25T18:14:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Daniel Commey, Matilda Nkoom, Yousef Alsenani, Sena G. Hounsinou, Garth V. Crosby</p>
    <p><b>Summary:</b> Virtual Asset Service Providers (VASPs) face a fundamental tension between regulatory compliance and user privacy when detecting cross-institutional money laundering. Current approaches require either sharing sensitive transaction data or operating in isolation, leaving critical cross-chain laundering patterns undetected. We present FedGraph-VASP, a privacy-preserving federated graph learning framework that enables collaborative anti-money laundering (AML) without exposing raw user data. Our key contribution is a Boundary Embedding Exchange protocol that shares only compressed, non-invertible graph neural network representations of boundary accounts. These exchanges are secured using post-quantum cryptography, specifically the NIST-standardized Kyber-512 key encapsulation mechanism combined with AES-256-GCM authenticated encryption. Experiments on the Elliptic Bitcoin dataset with realistic Louvain partitioning show that FedGraph-VASP achieves an F1-score of 0.508, outperforming the state-of-the-art generative baseline FedSage+ (F1 = 0.453) by 12.1 percent on binary fraud detection. We further show robustness under low-connectivity settings where generative imputation degrades performance, while approaching centralized performance (F1 = 0.620) in high-connectivity regimes. We additionally evaluate generalization on an Ethereum fraud detection dataset, where FedGraph-VASP (F1 = 0.635) is less effective under sparse cross-silo connectivity, while FedSage+ excels (F1 = 0.855), outperforming even local training (F1 = 0.785). These results highlight a topology-dependent trade-off: embedding exchange benefits connected transaction graphs, whereas generative imputation can dominate in highly modular sparse graphs. A privacy audit shows embeddings are only partially invertible (R^2 = 0.32), limiting exact feature recovery.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.17909v1">From Statistical Disclosure Control to Fair AI: Navigating Fundamental Tradeoffs in Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-25T17:07:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Adriana Watson</p>
    <p><b>Summary:</b> Differential privacy has become the gold standard for privacy-preserving machine learning systems. Unfortunately, subsequent work has primarily fixated on the privacy-utility tradeoff, leaving the subject of fairness constraints undervalued and under-researched. This paper provides a systematic treatment connecting three threads: (1) Dalenius's impossibility results for semantic privacy, (2) Dwork's differential privacy as an achievable alternative, and (3) emerging impossibility results from the addition of a fairness requirement. Through concrete examples and technical analysis, the three-way Pareto frontier between privacy, utility, and fairness is demonstrated to showcase the fundamental limits on what can be simultaneously achieved. In this work, these limits are characterized, the impact on minority groups is demonstrated, and practical guidance for navigating these tradeoffs are provided. This forms a unified framework synthesizing scattered results to help practitioners and policymakers make informed decisions when deploying private fair learning systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.17644v2">A Systemic Evaluation of Multimodal RAG Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-01-25T01:37:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ali Al-Lawati, Suhang Wang</p>
    <p><b>Summary:</b> The growing adoption of multimodal Retrieval-Augmented Generation (mRAG) pipelines for vision-centric tasks (e.g. visual QA) introduces important privacy challenges. In particular, while mRAG provides a practical capability to connect private datasets to improve model performance, it risks the leakage of private information from these datasets during inference. In this paper, we perform an empirical study to analyze the privacy risks inherent in the mRAG pipeline observed through standard model prompting. Specifically, we implement a case study that attempts to infer the inclusion of a visual asset, e.g. image, in the mRAG, and if present leak the metadata, e.g. caption, related to it. Our findings highlight the need for privacy-preserving mechanisms and motivate future research on mRAG privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.17569v1">Improving User Privacy in Personalized Generation: Client-Side Retrieval-Augmented Modification of Server-Side Generated Speculations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2026-01-24T19:46:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alireza Salemi, Hamed Zamani</p>
    <p><b>Summary:</b> Personalization is crucial for aligning Large Language Model (LLM) outputs with individual user preferences and background knowledge. State-of-the-art solutions are based on retrieval augmentation, where relevant context from a user profile is retrieved for LLM consumption. These methods deal with a trade-off between exposing retrieved private data to cloud providers and relying on less capable local models. We introduce $P^3$, an interactive framework for high-quality personalization without revealing private profiles to server-side LLMs. In $P^3$, a large server-side model generates a sequence of $k$ draft tokens based solely on the user query, while a small client-side model, with retrieval access to the user's private profile, evaluates and modifies these drafts to better reflect user preferences. This process repeats until an end token is generated. Experiments on LaMP-QA, a recent benchmark consisting of three personalized question answering datasets, show that $P^3$ consistently outperforms both non-personalized server-side and personalized client-side baselines, achieving statistically significant improvements of $7.4%$ to $9%$ on average. Importantly, $P^3$ recovers $90.3%$ to $95.7%$ of the utility of a ``leaky'' upper-bound scenario in which the full profile is exposed to the large server-side model. Privacy analyses, including linkability and attribute inference attacks, indicate that $P^3$ preserves the privacy of a non-personalized server-side model, introducing only marginal additional leakage ($1.5%$--$3.5%$) compared to submitting a query without any personal context. Additionally, the framework is efficient for edge deployment, with the client-side model generating only $9.2%$ of the total tokens. These results demonstrate that $P^3$ provides a practical, effective solution for personalized generation with improved privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.17373v1">"Privacy across the boundary": Examining Perceived Privacy Risk Across Data Transmission and Sharing Ranges of Smart Home Personal Assistants</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-01-24T08:42:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuning Zhang, Shixuan Li, Haobin Xing, Jiarui Liu, Yan Kong, Xin Yi, Hewu Li</p>
    <p><b>Summary:</b> As Smart Home Personal Assistants (SPAs) evolve into social agents, understanding user privacy necessitates interpersonal communication frameworks, such as Privacy Boundary Theory (PBT). To ground our investigation, our three-phase preliminary study (1) identified transmission and sharing ranges as key boundary-related risk factors, (2) categorized relevant SPA functions and data types, and (3) analyzed commercial practices, revealing widespread data sharing and non-transparent safeguards. A subsequent mixed-methods study (N=412 survey, N=40 interviews among the survey participants) assessed users' perceived privacy risks across data types, transmission ranges and sharing ranges. Results demonstrate a significant, non-linear escalation in perceived risk when data crosses two critical boundaries: the `public network' (transmission) and `third parties' (sharing). This boundary effect holds robustly across data types and demographics. Furthermore, risk perception is modulated by data attributes (e.g., social relational data), and contextual privacy calculus. Conversely, anonymization safeguards show limited efficacy especially for third-party sharing, a finding attributed to user distrust. These findings empirically ground PBT in the SPA context and inform design of boundary-aware privacy protection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.17368v1">A Scoping Review and Guidelines on Privacy Policy's Visualization from an HCI Perspective</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-01-24T08:22:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuning Zhang, Eve He, Sixing Tao, Yuting Yang, Ying Ma, Ailei Wang, Xin Yi, Hewu Li</p>
    <p><b>Summary:</b> Privacy Policies are a cornerstone of informed consent, yet a persistent gap exists between their legal intent and practical efficacy. Despite decades of Human-Computer Interaction (HCI) research proposing various visualizations, user comprehension remains low, and designs rarely see widespread adoption. To understand this landscape and chart a path forward, we synthesized 65 top-tier papers using a framework adapted from the user-centered design lifecycle. Our analysis presented findings of the field's evolution across four dimensions: (1) the trade-off between information load and decision efficacy, which demonstrates a shift from augmenting disclosures to prioritizing information condensation and cognitive load management to counter the inefficacy of comprehensive texts, (2) the co-evolutionary dynamic of design and automation, revealing that complex design ambitions such as context-awareness drove the need for advanced NLP, while recent LLM breakthroughs are enabling the semantic interpretation required to realize those designs, (3) the tension between generality and specificity, highlighting the divergence between standardized, cross-platform solutions and the increasing necessity for specialized, context-aware interaction patterns in IoT and immersive environments, and (4) balancing stakeholder opinions, which shows that visualization efficacy is constrained by the complex interplay of regulatory mandates, developer capabilities and provider incentives. We conclude by outlining four critical challenges for future research.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.17360v1">Robust Privacy: Inference-Time Privacy through Certified Robustness</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-24T08:13:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiankai Jin, Xiangzheng Zhang, Zhao Liu, Deyue Zhang, Quanchen Zou</p>
    <p><b>Summary:</b> Machine learning systems can produce personalized outputs that allow an adversary to infer sensitive input attributes at inference time. We introduce Robust Privacy (RP), an inference-time privacy notion inspired by certified robustness: if a model's prediction is provably invariant within a radius-$R$ neighborhood around an input $x$ (e.g., under the $\ell_2$ norm), then $x$ enjoys $R$-Robust Privacy, i.e., observing the prediction cannot distinguish $x$ from any input within distance $R$ of $x$. We further develop Attribute Privacy Enhancement (APE) to translate input-level invariance into an attribute-level privacy effect. In a controlled recommendation task where the decision depends primarily on a sensitive attribute, we show that RP expands the set of sensitive-attribute values compatible with a positive recommendation, expanding the inference interval accordingly. Finally, we empirically demonstrate that RP also mitigates model inversion attacks (MIAs) by masking fine-grained input-output dependence. Even at small noise levels ($σ=0.1$), RP reduces the attack success rate (ASR) from 73% to 4% with partial model performance degradation. RP can also partially mitigate MIAs (e.g., ASR drops to 44%) with no model performance degradation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.17183v1">Federated Proximal Optimization for Privacy-Preserving Heart Disease Prediction: A Controlled Simulation Study on Non-IID Clinical Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-01-23T21:18:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Farzam Asad, Junaid Saif Khan, Maria Tariq, Sundus Munir, Muhammad Adnan Khan</p>
    <p><b>Summary:</b> Healthcare institutions have access to valuable patient data that could be of great help in the development of improved diagnostic models, but privacy regulations like HIPAA and GDPR prevent hospitals from directly sharing data with one another. Federated Learning offers a way out to this problem by facilitating collaborative model training without having the raw patient data centralized. However, clinical datasets intrinsically have non-IID (non-independent and identically distributed) features brought about by demographic disparity and diversity in disease prevalence and institutional practices. This paper presents a comprehensive simulation research of Federated Proximal Optimization (FedProx) for Heart Disease prediction based on UCI Heart Disease dataset. We generate realistic non-IID data partitions by simulating four heterogeneous hospital clients from the Cleveland Clinic dataset (303 patients), by inducing statistical heterogeneity by demographic-based stratification. Our experimental results show that FedProx with proximal parameter mu=0.05 achieves 85.00% accuracy, which is better than both centralized learning (83.33%) and isolated local models (78.45% average) without revealing patient privacy. Through generous sheer ablation studies with statistical validation on 50 independent runs we demonstrate that proximal regularization is effective in curbing client drift in heterogeneous environments. This proof-of-concept research offers algorithmic insights and practical deployment guidelines for real-world federated healthcare systems, and thus, our results are directly transferable to hospital IT-administrators, implementing privacy-preserving collaborative learning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.16857v1">Perfect Privacy and Strong Stationary Times for Markovian Sources</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-01-23T16:04:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fangwei Ye, Zonghong Liu, Parimal Parag, Salim El Rouayheb</p>
    <p><b>Summary:</b> We consider the problem of sharing correlated data under a perfect information-theoretic privacy constraint. We focus on redaction (erasure) mechanisms, in which data are either withheld or released unchanged, and measure utility by the average cardinality of the released set, equivalently, the expected Hamming distortion. Assuming the data are generated by a finite time-homogeneous Markov chain, we study the protection of the initial state while maximizing the amount of shared data. We establish a connection between perfect privacy and window-based redaction schemes, showing that erasing data up to a strong stationary time preserves privacy under suitable conditions. We further study an optimal sequential redaction mechanism and prove that it admits an equivalent window interpretation. Interestingly, we show that both mechanisms achieve the optimal distortion while redacting only a constant average number of data points, independent of the data length~$N$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.16825v1">Privacy-Resolution Tradeoff for Adaptive Noisy Twenty Questions Estimation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-01-23T15:23:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chunsong Sun, Lin Zhou</p>
    <p><b>Summary:</b> We revisit noisy twenty questions estimation and study the privacy-resolution tradeoff for adaptive query procedures. Specifically, in twenty questions estimation, there are two players: an oracle and a questioner. The questioner aims to estimate target variables by posing queries to the oracle that knows the variables and using noisy responses to form reliable estimates. Typically, there are adaptive and non-adaptive query procedures. In adaptive querying, one designs the current query using previous queries and their noisy responses while in non-adaptive querying, all queries are posed simultaneously. Generally speaking, adaptive query procedures yield better performance. However, adaptive querying leads to privacy concerns, which were first studied by Tsitsiklis, Xu and Xu (COLT 2018) and by Xu, Xu and Yang (AISTATS 2021) for the noiseless case, where the oracle always provides correct answers to queries. In this paper, we generalize the above results to the more practical noisy case, by proposing a two-stage private query procedure, analyzing its non-asymptotic and second-order asymptotic achievable performance and discussing the impact of privacy concerns. Furthermore, when specialized to the noiseless case, our private query procedure achieves better performance than above-mentioned query procedures (COLT 2018, AISTATS 2021).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.16824v1">Privacy in Human-AI Romantic Relationships: Concerns, Boundaries, and Agency</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-01-23T15:23:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rongjun Ma, Shijing He, Jose Luis Martin-Navarro, Xiao Zhan, Jose Such</p>
    <p><b>Summary:</b> An increasing number of LLM-based applications are being developed to facilitate romantic relationships with AI partners, yet the safety and privacy risks in these partnerships remain largely underexplored. In this work, we investigate privacy in human-AI romantic relationships through an interview study (N=17), examining participants' experiences and privacy perceptions across stages of exploration, intimacy, and dissolution, alongside platforms they used. We found that these relationships took varied forms, from one-to-one to one-to-many, and were shaped by multiple actors, including creators, platforms, and moderators. AI partners were perceived as having agency, actively negotiating privacy boundaries with participants and sometimes encouraging disclosure of personal details. As intimacy deepened, these boundaries became more permeable, though some participants voiced concerns such as conversation exposure and sought to preserve anonymity. Overall, platform affordances and diverse romantic dynamics expand the privacy landscape, underscoring the need to rethink how privacy is constructed in human-AI intimacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.16658v1">Talking about privacy always feels like opening a can of worms. How Intimate Partners Navigate Boundary-Setting in Mobile Phone Without Words</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-01-23T11:21:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sima Amirkhani, Mahla Fatemeh Alizadeh, Farzaneh Gerami, Dave Randall, Gunnar Stevens</p>
    <p><b>Summary:</b> Mobile phones, as simultaneously personal and shared technologies, complicate how partners manage digital privacy in intimate relationships. While prior research has examined device-access practices, explicit privacy-rule negotiation, and toxic practices such as surveillance, little is known about how couples manage digital privacy without direct discussion in everyday relationships. To address this gap, we ask: How is digital privacy managed nonverbally and across different media on mobile phones? Drawing on 20 semi-structured interviews, we find that partners often regulate privacy practices through privacy silence -- the intentional avoidance of privacy-related conversations. We identify five motivations for leaving boundaries unspoken: perceiving privacy as unnecessary in intimacy, assuming implicit respect for boundaries, signaling trust and closeness, avoiding potential conflict or harm, and responding to broader societal and cultural expectations that discourage explicit privacy talk. We also identify a hierarchical grouping of content-specific privacy sensitivities, ranging from highly private domains such as financial data to lower-risk domains such as streaming accounts, and show how these priorities shift across relationship stages. These findings show how silence, culture, and content sensitivity shape everyday boundary-setting and underscore the relational and emotional dynamics underpinning mobile phone privacy management.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.16354v1">NOIR: Privacy-Preserving Generation of Code with Open-Source LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-01-22T22:39:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Khoa Nguyen, Khiem Ton, NhatHai Phan, Issa Khalil, Khang Tran, Cristian Borcea, Ruoming Jin, Abdallah Khreishah, My T. Thai</p>
    <p><b>Summary:</b> Although boosting software development performance, large language model (LLM)-powered code generation introduces intellectual property and data security risks rooted in the fact that a service provider (cloud) observes a client's prompts and generated code, which can be proprietary in commercial systems. To mitigate this problem, we propose NOIR, the first framework to protect the client's prompts and generated code from the cloud. NOIR uses an encoder and a decoder at the client to encode and send the prompts' embeddings to the cloud to get enriched embeddings from the LLM, which are then decoded to generate the code locally at the client. Since the cloud can use the embeddings to infer the prompt and the generated code, NOIR introduces a new mechanism to achieve indistinguishability, a local differential privacy protection at the token embedding level, in the vocabulary used in the prompts and code, and a data-independent and randomized tokenizer on the client side. These components effectively defend against reconstruction and frequency analysis attacks by an honest-but-curious cloud. Extensive analysis and results using open-source LLMs show that NOIR significantly outperforms existing baselines on benchmarks, including the Evalplus (MBPP and HumanEval, Pass@1 of 76.7 and 77.4), and BigCodeBench (Pass@1 of 38.7, only a 1.77% drop from the original LLM) under strong privacy against attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2601.16160v1">CONTEX-T: Contextual Privacy Exploitation via Transformer Spectral Analysis for IoT Device Fingerprinting</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-01-22T18:03:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nazmul Islam, Mohammad Zulkernine</p>
    <p><b>Summary:</b> The rapid expansion of internet of things (IoT) devices have created a pervasive ecosystem where encrypted wireless communications serve as the primary privacy and security protection mechanism. While encryption effectively protects message content, packet metadata and statistics inadvertently expose device identities and user contexts. Various studies have exploited raw packet statistics and their visual representations for device fingerprinting and identification. However, these approaches remain confined to the spatial domain with limited feature representation. Therefore, this paper presents CONTEX-T, a novel framework that exploits contextual privacy vulnerabilities using spectral representation of encrypted wireless traffic for IoT device characterization. The experiments show that spectral analysis provides new and rich feature representation for covert reconnaissance attacks, revealing a complex and expanding threat landscape that would require robust countermeasures for IoT security management. CONTEXT-T first transforms raw packet length sequences into time-frequency spectral representations and then utilizes transformer-based spectral analysis for the device identification. We systematically evaluated multiple spectral representation techniques and transformer-based models across encrypted traffic samples from various IoT devices. CONTEXT-T effectively exploited privacy vulnerabilities and achieved device classification accuracy exceeding 99% across all devices while remaining completely passive and undetectable.</p>
  </details>
</div>

