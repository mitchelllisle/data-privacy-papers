
<h2>2025-11</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.16377v1">Optimal Fairness under Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2025-11-20T14:00:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hrad Ghoukasian, Shahab Asoodeh</p>
    <p><b>Summary:</b> We investigate how to optimally design local differential privacy (LDP) mechanisms that reduce data unfairness and thereby improve fairness in downstream classification. We first derive a closed-form optimal mechanism for binary sensitive attributes and then develop a tractable optimization framework that yields the corresponding optimal mechanism for multi-valued attributes. As a theoretical contribution, we establish that for discrimination-accuracy optimal classifiers, reducing data unfairness necessarily leads to lower classification unfairness, thus providing a direct link between privacy-aware pre-processing and classification fairness. Empirically, we demonstrate that our approach consistently outperforms existing LDP mechanisms in reducing data unfairness across diverse datasets and fairness metrics, while maintaining accuracy close to that of non-private models. Moreover, compared with leading pre-processing and post-processing fairness methods, our mechanism achieves a more favorable accuracy-fairness trade-off while simultaneously preserving the privacy of sensitive attributes. Taken together, these results highlight LDP as a principled and effective pre-processing fairness intervention technique.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.15634v1">Rényi Differential Privacy for Heavy-Tailed SDEs via Fractional Poincaré Inequalities</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-11-19T17:18:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Benjamin Dupuis, Mert Gürbüzbalaban, Umut Şimşekli, Jian Wang, Sinan Yildirim, Lingjiong Zhu</p>
    <p><b>Summary:</b> Characterizing the differential privacy (DP) of learning algorithms has become a major challenge in recent years. In parallel, many studies suggested investigating the behavior of stochastic gradient descent (SGD) with heavy-tailed noise, both as a model for modern deep learning models and to improve their performance. However, most DP bounds focus on light-tailed noise, where satisfactory guarantees have been obtained but the proposed techniques do not directly extend to the heavy-tailed setting. Recently, the first DP guarantees for heavy-tailed SGD were obtained. These results provide $(0,δ)$-DP guarantees without requiring gradient clipping. Despite casting new light on the link between DP and heavy-tailed algorithms, these results have a strong dependence on the number of parameters and cannot be extended to other DP notions like the well-established Rényi differential privacy (RDP). In this work, we propose to address these limitations by deriving the first RDP guarantees for heavy-tailed SDEs, as well as their discretized counterparts. Our framework is based on new Rényi flow computations and the use of well-established fractional Poincaré inequalities. Under the assumption that such inequalities are satisfied, we obtain DP guarantees that have a much weaker dependence on the dimension compared to prior art.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.15434v1">Small Language Models for Phishing Website Detection: Cost, Performance, and Privacy Trade-Offs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-11-19T13:45:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Georg Goldenits, Philip Koenig, Sebastian Raubitzek, Andreas Ekelhart</p>
    <p><b>Summary:</b> Phishing websites pose a major cybersecurity threat, exploiting unsuspecting users and causing significant financial and organisational harm. Traditional machine learning approaches for phishing detection often require extensive feature engineering, continuous retraining, and costly infrastructure maintenance. At the same time, proprietary large language models (LLMs) have demonstrated strong performance in phishing-related classification tasks, but their operational costs and reliance on external providers limit their practical adoption in many business environments. This paper investigates the feasibility of small language models (SLMs) for detecting phishing websites using only their raw HTML code. A key advantage of these models is that they can be deployed on local infrastructure, providing organisations with greater control over data and operations. We systematically evaluate 15 commonly used Small Language Models (SLMs), ranging from 1 billion to 70 billion parameters, benchmarking their classification accuracy, computational requirements, and cost-efficiency. Our results highlight the trade-offs between detection performance and resource consumption, demonstrating that while SLMs underperform compared to state-of-the-art proprietary LLMs, they can still provide a viable and scalable alternative to external LLM services. By presenting a comparative analysis of costs and benefits, this work lays the foundation for future research on the adaptation, fine-tuning, and deployment of SLMs in phishing detection systems, aiming to balance security effectiveness and economic practicality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.15278v1">Privacy-Preserving IoT in Connected Aircraft Cabin</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2025-11-19T09:41:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nilesh Vyas, Benjamin Zhao, Aygün Baltaci, Gustavo de Carvalho Bertoli, Hassan Asghar, Markus Klügel, Gerrit Schramm, Martin Kubisch, Dali Kaafar</p>
    <p><b>Summary:</b> The proliferation of IoT devices in shared, multi-vendor environments like the modern aircraft cabin creates a fundamental conflict between the promise of data collaboration and the risks to passenger privacy, vendor intellectual property (IP), and regulatory compliance. While emerging standards like the Cabin Secure Media-Independent Messaging (CSMIM) protocol provide a secure communication backbone, they do not resolve data governance challenges at the application layer, leaving a privacy gap that impedes trust. This paper proposes and evaluates a framework that closes this gap by integrating a configurable layer of Privacy-Enhancing Technologies (PETs) atop a CSMIM-like architecture. We conduct a rigorous, empirical analysis of two pragmatic PETs: Differential Privacy (DP) for statistical sharing, and an additive secret sharing scheme (ASS) for data obfuscation. Using a high-fidelity testbed with resource-constrained hardware, we quantify the trade-offs between data privacy, utility, and computing performance. Our results demonstrate that the computational overhead of PETs is often negligible compared to inherent network and protocol latencies. We prove that architectural choices, such as on-device versus virtualized processing, have a far greater impact on end-to-end latency and computational performance than the PETs themselves. The findings provide a practical roadmap for system architects to select and configure appropriate PETs, enabling the design of trustworthy collaborative IoT ecosystems in avionics and other critical domains.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.14936v1">How to Train Private Clinical Language Models: A Comparative Study of Privacy-Preserving Pipelines for ICD-9 Coding</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-11-18T21:51:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mathieu Dufour, Andrew Duncan</p>
    <p><b>Summary:</b> Large language models trained on clinical text risk exposing sensitive patient information, yet differential privacy (DP) methods often severely degrade the diagnostic accuracy needed for deployment. Despite rapid progress in DP optimisation and text generation, it remains unclear which privacy-preserving strategy actually works best for clinical language tasks. We present the first systematic head-to-head comparison of four training pipelines for automated diagnostic coding from hospital discharge summaries. All pipelines use identical 1B-parameter models and matched privacy budgets to predict ICD-9 codes. At moderate and relaxed privacy budgets ($\varepsilon \in \{4, 6\}$), knowledge distillation from DP-trained teachers outperforms both direct DP-SGD and DP-synthetic data training, recovering up to 63\% of the non-private performance whilst maintaining strong empirical privacy (membership-inference AUC $\approx$ 0.5). These findings expose large differences in the privacy-utility trade-off across architectures and identify knowledge distillation as the most practical route to privacy-preserving clinical NLP.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.14524v1">Compression with Privacy-Preserving Random Access</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2025-11-18T14:24:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Venkat Chandar, Aslan Tchamkerten, Shashank Vatedka</p>
    <p><b>Summary:</b> It is shown that an i.i.d. binary source sequence $X_1, \ldots, X_n$ can be losslessly compressed at any rate above entropy such that the individual decoding of any $X_i$ reveals \emph{no} information about the other bits $\{X_j : j \neq i\}$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.14084v1">Observational Auditing of Label Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-18T03:12:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Iden Kalemaj, Luca Melis, Maxime Boucher, Ilya Mironov, Saeed Mahloujifar</p>
    <p><b>Summary:</b> Differential privacy (DP) auditing is essential for evaluating privacy guarantees in machine learning systems. Existing auditing methods, however, pose a significant challenge for large-scale systems since they require modifying the training dataset -- for instance, by injecting out-of-distribution canaries or removing samples from training. Such interventions on the training data pipeline are resource-intensive and involve considerable engineering overhead. We introduce a novel observational auditing framework that leverages the inherent randomness of data distributions, enabling privacy evaluation without altering the original dataset. Our approach extends privacy auditing beyond traditional membership inference to protected attributes, with labels as a special case, addressing a key gap in existing techniques. We provide theoretical foundations for our method and perform experiments on Criteo and CIFAR-10 datasets that demonstrate its effectiveness in auditing label privacy guarantees. This work opens new avenues for practical privacy auditing in large-scale production environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.14045v1">GRPO Privacy Is at Risk: A Membership Inference Attack Against Reinforcement Learning With Verifiable Rewards</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-11-18T01:51:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yule Liu, Heyi Zhang, Jinyi Zheng, Zhen Sun, Zifan Peng, Tianshuo Cong, Yilong Yang, Xinlei He, Zhuo Ma</p>
    <p><b>Summary:</b> Membership inference attacks (MIAs) on large language models (LLMs) pose significant privacy risks across various stages of model training. Recent advances in Reinforcement Learning with Verifiable Rewards (RLVR) have brought a profound paradigm shift in LLM training, particularly for complex reasoning tasks. However, the on-policy nature of RLVR introduces a unique privacy leakage pattern: since training relies on self-generated responses without fixed ground-truth outputs, membership inference must now determine whether a given prompt (independent of any specific response) is used during fine-tuning. This creates a threat where leakage arises not from answer memorization.
  To audit this novel privacy risk, we propose Divergence-in-Behavior Attack (DIBA), the first membership inference framework specifically designed for RLVR. DIBA shifts the focus from memorization to behavioral change, leveraging measurable shifts in model behavior across two axes: advantage-side improvement (e.g., correctness gain) and logit-side divergence (e.g., policy drift). Through comprehensive evaluations, we demonstrate that DIBA significantly outperforms existing baselines, achieving around 0.8 AUC and an order-of-magnitude higher TPR@0.1%FPR. We validate DIBA's superiority across multiple settings--including in-distribution, cross-dataset, cross-algorithm, black-box scenarios, and extensions to vision-language models. Furthermore, our attack remains robust under moderate defensive measures.
  To the best of our knowledge, this is the first work to systematically analyze privacy vulnerabilities in RLVR, revealing that even in the absence of explicit supervision, training data exposure can be reliably inferred through behavioral traces.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.13576v1">Exploring the Effectiveness of Google Play Store's Privacy Transparency Channels</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-11-17T16:40:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anhao Xiang, Weiping Pei, Chuan Yue</p>
    <p><b>Summary:</b> With the requirements and emphases on privacy transparency placed by regulations such as GDPR and CCPA, the Google Play Store requires Android developers to more responsibly communicate their apps' privacy practices to potential users by providing the proper information via the data safety, privacy policy, and permission manifest privacy transparency channels. However, it is unclear how effective those channels are in helping users make informed decisions in the app selection and installation process. In this article, we conducted a study for 190 participants to interact with our simulated privacy transparency channels of mobile apps. We quantitatively analyzed (supplemented by qualitative analysis) participants' responses to five sets of questions. We found that data safety provides the most intuitive user interfaces, privacy policy is most informative and effective, while permission manifest excels at raising participants' concerns about an app's overall privacy risks. These channels complement each other and should all be improved.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.13502v1">Tight and Practical Privacy Auditing for Differentially Private In-Context Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-17T15:39:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuyang Xia, Ruixuan Liu, Li Xiong</p>
    <p><b>Summary:</b> Large language models (LLMs) perform in-context learning (ICL) by adapting to tasks from prompt demonstrations, which in practice often contain private or proprietary data. Although differential privacy (DP) with private voting is a pragmatic mitigation, DP-ICL implementations are error-prone, and worst-case DP bounds may substantially overestimate actual leakage, calling for practical auditing tools. We present a tight and efficient privacy auditing framework for DP-ICL systems that runs membership inference attacks and translates their success rates into empirical privacy guarantees using Gaussian DP. Our analysis of the private voting mechanism identifies vote configurations that maximize the auditing signal, guiding the design of audit queries that reliably reveal whether a canary demonstration is present in the context. The framework supports both black-box (API-only) and white-box (internal vote) threat models, and unifies auditing for classification and generation by reducing both to a binary decision problem. Experiments on standard text classification and generation benchmarks show that our empirical leakage estimates closely match theoretical DP budgets on classification tasks and are consistently lower on generation tasks due to conservative embedding-sensitivity bounds, making our framework a practical privacy auditor and verifier for real-world DP-ICL deployments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.13365v1">InfoDecom: Decomposing Information for Defending against Privacy Leakage in Split Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-11-17T13:36:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruijun Deng, Zhihui Lu, Qiang Duan</p>
    <p><b>Summary:</b> Split inference (SI) enables users to access deep learning (DL) services without directly transmitting raw data. However, recent studies reveal that data reconstruction attacks (DRAs) can recover the original inputs from the smashed data sent from the client to the server, leading to significant privacy leakage. While various defenses have been proposed, they often result in substantial utility degradation, particularly when the client-side model is shallow. We identify a key cause of this trade-off: existing defenses apply excessive perturbation to redundant information in the smashed data. To address this issue in computer vision tasks, we propose InfoDecom, a defense framework that first decomposes and removes redundant information and then injects noise calibrated to provide theoretically guaranteed privacy. Experiments demonstrate that InfoDecom achieves a superior utility-privacy trade-off compared to existing baselines. The code and the appendix are available at https://github.com/SASA-cloud/InfoDecom.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.13319v1">Whistledown: Combining User-Level Privacy with Conversational Coherence in LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-11-17T12:56:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chelsea McMurray, Hayder Tirmazi</p>
    <p><b>Summary:</b> Users increasingly rely on large language models (LLMs) for personal, emotionally charged, and socially sensitive conversations. However, prompts sent to cloud-hosted models can contain personally identifiable information (PII) that users do not want logged, retained, or leaked. We observe this to be especially acute when users discuss friends, coworkers, or adversaries, i.e., when they spill the tea. Enterprises face the same challenge when they want to use LLMs for internal communication and decision-making.
  In this whitepaper, we present Whistledown, a best-effort privacy layer that modifies prompts before they are sent to the LLM. Whistledown combines pseudonymization and $ε$-local differential privacy ($ε$-LDP) with transformation caching to provide best-effort privacy protection without sacrificing conversational utility. Whistledown is designed to have low compute and memory overhead, allowing it to be deployed directly on a client's device in the case of individual users. For enterprise users, Whistledown is deployed centrally within a zero-trust gateway that runs on an enterprise's trusted infrastructure. Whistledown requires no changes to the existing APIs of popular LLM providers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.12936v1">Privacy-Preserving Federated Learning from Partial Decryption Verifiable Threshold Multi-Client Functional Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-11-17T03:44:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Minjie Wang, Jinguang Han, Weizhi Meng</p>
    <p><b>Summary:</b> In federated learning, multiple parties can cooperate to train the model without directly exchanging their own private data, but the gradient leakage problem still threatens the privacy security and model integrity. Although the existing scheme uses threshold cryptography to mitigate the inference attack, it can not guarantee the verifiability of the aggregation results, making the system vulnerable to the threat of poisoning attack. We construct a partial decryption verifiable threshold multi client function encryption scheme, and apply it to Federated learning to implement the federated learning verifiable threshold security aggregation protocol (VTSAFL). VTSAFL empowers clients to verify aggregation results, concurrently minimizing both computational and communication overhead. The size of the functional key and partial decryption results of the scheme are constant, which provides efficiency guarantee for large-scale deployment. The experimental results on MNIST dataset show that vtsafl can achieve the same accuracy as the existing scheme, while reducing the total training time by more than 40%, and reducing the communication overhead by up to 50%. This efficiency is critical for overcoming the resource constraints inherent in Internet of Things (IoT) devices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.12841v1">SoK: Synthesizing Smart Home Privacy Protection Mechanisms Across Academic Proposals and Commercial Documentations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-11-17T00:08:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuning Zhang, Yijing Liu, Yuyu Liu, Ying Ma, Shixuan Li, Xin Yi, Qian Wu, Hewu Li</p>
    <p><b>Summary:</b> Pervasive data collection by Smart Home Devices (SHDs) demands robust Privacy Protection Mechanisms (PPMs). The effectiveness of many PPMs, particularly user-facing controls, depends on user awareness and adoption, which are shaped by manufacturers' public documentations. However, the landscape of academic proposals and commercial disclosures remains underexplored. To address this gap, we investigate: (1) What PPMs have academics proposed, and how are these PPMs evaluated? (2) What PPMs do manufacturers document and what factors affect these documentation? To address these questions, we conduct a two-phase study, synthesizing a systematic review of 117 academic papers with an empirical analysis of 86 SHDs' publicly disclosed documentations. Our review of academic literature reveals a strong focus on novel system- and algorithm-based PPMs. However, these proposals neglect deployment barriers (e.g., cost, interoperability), and lack real-world field validation and legal analysis. Concurrently, our analysis of commercial SHDs finds that advanced academic proposals are absent from public discourse. Industry postures are fundamentally reactive, prioritizing compliance via post-hoc data management (e.g., deletion options), rather than the preventative controls favored by academia. The documented protections correspondingly converge on a small set of practical mechanisms, such as physical buttons and localized processing. By synthesizing these findings, we advocate for research to analyze challenges, provide deployable frameworks, real-world field validation, and interoperability solutions to advance practical PPMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.12575v1">Beyond Pixels: Semantic-aware Typographic Attack for Geo-Privacy Protection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-11-16T12:27:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiayi Zhu, Yihao Huang, Yue Cao, Xiaojun Jia, Qing Guo, Felix Juefei-Xu, Geguang Pu, Bin Wang</p>
    <p><b>Summary:</b> Large Visual Language Models (LVLMs) now pose a serious yet overlooked privacy threat, as they can infer a social media user's geolocation directly from shared images, leading to unintended privacy leakage. While adversarial image perturbations provide a potential direction for geo-privacy protection, they require relatively strong distortions to be effective against LVLMs, which noticeably degrade visual quality and diminish an image's value for sharing. To overcome this limitation, we identify typographical attacks as a promising direction for protecting geo-privacy by adding text extension outside the visual content. We further investigate which textual semantics are effective in disrupting geolocation inference and design a two-stage, semantics-aware typographical attack that generates deceptive text to protect user privacy. Extensive experiments across three datasets demonstrate that our approach significantly reduces geolocation prediction accuracy of five state-of-the-art commercial LVLMs, establishing a practical and visually-preserving protection strategy against emerging geo-privacy threats.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.12377v1">On the Security and Privacy of AI-based Mobile Health Chatbots</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-11-15T22:49:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Samuel Wairimu, Leonardo Horn Iwaya</p>
    <p><b>Summary:</b> The rise of Artificial Intelligence (AI) has impacted the development of mobile health (mHealth) apps, most notably with the advent of AI-based chatbots used as ubiquitous ``companions'' for various services, from fitness to mental health assistants. While these mHealth chatbots offer clear benefits, such as personalized health information and predictive diagnoses, they also raise significant concerns regarding security and privacy. This study empirically assesses 16 AI-based mHealth chatbots identified from the Google Play Store. The empirical assessment follows a three-phase approach (manual inspection, static code analysis, and dynamic analysis) to evaluate technical robustness and how design and implementation choices impact end users. Our findings revealed security vulnerabilities (e.g., enabling Remote WebView debugging), privacy issues, and non-compliance with Google Play policies (e.g., failure to provide publicly accessible privacy policies). Based on our findings, we offer several recommendations to enhance the security and privacy of mHealth chatbots. These recommendations focus on improving data handling processes, disclosure, and user security. Therefore, this work also seeks to support mHealth developers and security/privacy engineers in designing more transparent, privacy-friendly, and secure mHealth chatbots.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.12295v1">Privacy-Preserving Prompt Injection Detection for LLMs Using Federated Learning and Embedding-Based NLP Classification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-15T17:11:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hasini Jayathilaka</p>
    <p><b>Summary:</b> Prompt injection attacks are an emerging threat to large language models (LLMs), enabling malicious users to manipulate outputs through carefully designed inputs. Existing detection approaches often require centralizing prompt data, creating significant privacy risks. This paper proposes a privacy-preserving prompt injection detection framework based on federated learning and embedding-based classification. A curated dataset of benign and adversarial prompts was encoded with sentence embedding and used to train both centralized and federated logistic regression models. The federated approach preserved privacy by sharing only model parameters across clients, while achieving detection performance comparable to centralized training. Results demonstrate that effective prompt injection detection is feasible without exposing raw data, making this one of the first explorations of federated security for LLMs. Although the dataset is limited in scale, the findings establish a strong proof-of-concept and highlight new directions for building secure and privacy-aware LLM systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.11811v1">Lessons Learned from Developing a Privacy-Preserving Multimodal Wearable for Local Voice-and-Vision Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">   
  <p><b>Published on:</b> 2025-11-14T19:04:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yonatan Tussa, Andy Heredia, Nirupam Roy</p>
    <p><b>Summary:</b> Many promising applications of multimodal wearables require continuous sensing and heavy computation, yet users reject such devices due to privacy concerns. This paper shares our experiences building an ear-mounted voice-and-vision wearable that performs local AI inference using a paired smartphone as a trusted personal edge. We describe the hardware--software co-design of this privacy-preserving system, including challenges in integrating a camera, microphone, and speaker within a 30-gram form factor, enabling wake word-triggered capture, and running quantized vision-language and large-language models entirely offline. Through iterative prototyping, we identify key design hurdles in power budgeting, connectivity, latency, and social acceptability. Our initial evaluation shows that fully local multimodal inference is feasible on commodity mobile hardware with interactive latency. We conclude with design lessons for researchers developing embedded AI systems that balance privacy, responsiveness, and usability in everyday settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.11347v2">Privacy Challenges and Solutions in Retrieval-Augmented Generation-Enhanced LLMs for Healthcare Chatbots: A Review of Applications, Risks, and Future Directions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-11-14T14:33:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shaowei Guan, Hin Chi Kwok, Ngai Fong Law, Gregor Stiglic, Harry Qin, Vivian Hui</p>
    <p><b>Summary:</b> Retrieval-augmented generation (RAG) has rapidly emerged as a transformative approach for integrating large language models into clinical and biomedical workflows. However, privacy risks, such as protected health information (PHI) exposure, remain inconsistently mitigated. This review provides a thorough analysis of the current landscape of RAG applications in healthcare, including (i) sensitive data type across clinical scenarios, (ii) the associated privacy risks, (iii) current and emerging data-privacy protection mechanisms and (iv) future direction for patient data privacy protection. We synthesize 23 articles on RAG applications in healthcare and systematically analyze privacy challenges through a pipeline-structured framework encompassing data storage, transmission, retrieval and generation stages, delineating potential failure modes, their underlying causes in threat models and system mechanisms, and their practical implications. Building on this analysis, we critically review 17 articles on privacy-preserving strategies for RAG systems. Our evaluation reveals critical gaps, including insufficient clinical validation, absence of standardized evaluation frameworks, and lack of automated assessment tools. We propose actionable directions based on these limitations and conclude with a call to action. This review provides researchers and practitioners with a structured framework for understanding privacy vulnerabilities in healthcare RAG and offers a roadmap toward developing systems that achieve both clinical effectiveness and robust privacy preservation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.11249v1">Bridging Local and Federated Data Normalization in Federated Learning: A Privacy-Preserving Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-14T12:48:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Melih Coşğun, Mert Gençtürk, Sinem Sav</p>
    <p><b>Summary:</b> Data normalization is a crucial preprocessing step for enhancing model performance and training stability. In federated learning (FL), where data remains distributed across multiple parties during collaborative model training, normalization presents unique challenges due to the decentralized and often heterogeneous nature of the data. Traditional methods rely on either independent client-side processing, i.e., local normalization, or normalizing the entire dataset before distributing it to parties, i.e., pooled normalization. Local normalization can be problematic when data distributions across parties are non-IID, while the pooled normalization approach conflicts with the decentralized nature of FL. In this paper, we explore the adaptation of widely used normalization techniques to FL and define the term federated normalization. Federated normalization simulates pooled normalization by enabling the collaborative exchange of normalization parameters among parties. Thus, it achieves performance on par with pooled normalization without compromising data locality. However, sharing normalization parameters such as the mean introduces potential privacy risks, which we further mitigate through a robust privacy-preserving solution. Our contributions include: (i) We systematically evaluate the impact of various federated and local normalization techniques in heterogeneous FL scenarios, (ii) We propose a novel homomorphically encrypted $k$-th ranked element (and median) calculation tailored for the federated setting, enabling secure and efficient federated normalization, (iii) We propose privacy-preserving implementations of widely used normalization techniques for FL, leveraging multiparty fully homomorphic encryption (MHE).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.11209v1">Towards Usable Privacy Management for IoT TAPs: Deriving Privacy Clusters and Preference Profiles</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-11-14T12:08:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Piero Romare, Farzaneh Karegar, Simone Fischer-Hübner</p>
    <p><b>Summary:</b> IoT Trigger-Action Platforms (TAPs) typically offer coarse-grained permission controls. Even when fine-grained controls are available, users are likely overwhelmed by the complexity of setting privacy preferences. This paper contributes to usable privacy management for TAPs by deriving privacy clusters and profiles for different types of users that can be semi-automatically assigned or suggested to them. We developed and validated a questionnaire, based on users' privacy concerns regarding confidentiality and control and their requirements towards transparency in TAPs. In an online study (N=301), where participants were informed about potential privacy risks, we clustered users by their privacy concerns and requirements into Basic, Medium and High Privacy clusters. These clusters were then characterized by the users' data sharing preferences, based on a factorial vignette approach, considering the data categories, the data recipient types, and the purpose of data sharing. Our findings show three distinct privacy profiles, providing a foundation for more usable privacy controls in TAPs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.10771v1">Privacy protection under the exposure of systems' prior information</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2025-11-13T19:47:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Le Liu, Yu Kawano, Ming Cao</p>
    <p><b>Summary:</b> For systems whose states implicate sensitive information, their privacy is of great concern. While notions like differential privacy have been successfully introduced to dynamical systems, it is still unclear how a system's privacy can be properly protected when facing the challenging yet frequently-encountered scenario where an adversary possesses prior knowledge, e.g., the steady state, of the system. This paper presents a new systematic approach to protect the privacy of a discrete-time linear time-invariant system against adversaries knowledgeable of the system's prior information. We employ a tailored \emph{pointwise maximal leakage (PML) privacy} criterion. PML characterizes the worst-case privacy performance, which is sharply different from that of the better-known mutual-information privacy. We derive necessary and sufficient conditions for PML privacy and construct tractable design procedures. Furthermore, our analysis leads to insight into how PML privacy, differential privacy, and mutual-information privacy are related. We then revisit Kalman filters from the perspective of PML privacy and derive a lower bound on the steady-state estimation-error covariance in terms of the PML parameters. Finally, the derived results are illustrated in a case study of privacy protection for distributed sensing in smart buildings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.10516v1">How Worrying Are Privacy Attacks Against Machine Learning?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-13T17:22:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Josep Domingo-Ferrer</p>
    <p><b>Summary:</b> In several jurisdictions, the regulatory framework on the release and sharing of personal data is being extended to machine learning (ML). The implicit assumption is that disclosing a trained ML model entails a privacy risk for any personal data used in training comparable to directly releasing those data. However, given a trained model, it is necessary to mount a privacy attack to make inferences on the training data. In this concept paper, we examine the main families of privacy attacks against predictive and generative ML, including membership inference attacks (MIAs), property inference attacks, and reconstruction attacks. Our discussion shows that most of these attacks seem less effective in the real world than what a prima face interpretation of the related literature could suggest.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.10423v2">Enhanced Privacy Leakage from Noise-Perturbed Gradients via Gradient-Guided Conditional Diffusion Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-13T15:43:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiayang Meng, Tao Huang, Hong Chen, Chen Hou, Guolong Zheng</p>
    <p><b>Summary:</b> Federated learning synchronizes models through gradient transmission and aggregation. However, these gradients pose significant privacy risks, as sensitive training data is embedded within them. Existing gradient inversion attacks suffer from significantly degraded reconstruction performance when gradients are perturbed by noise-a common defense mechanism. In this paper, we introduce gradient-guided conditional diffusion models for reconstructing private images from leaked gradients, without prior knowledge of the target data distribution. Our approach leverages the inherent denoising capability of diffusion models to circumvent the partial protection offered by noise perturbation, thereby improving attack performance under such defenses. We further provide a theoretical analysis of the reconstruction error bounds and the convergence properties of the attack loss, characterizing the impact of key factors-such as noise magnitude and attacked model architecture-on reconstruction quality. Extensive experiments demonstrate our attack's superior reconstruction performance with Gaussian noise-perturbed gradients, and confirm our theoretical findings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.10284v1">Beyond Verification: Abductive Explanations for Post-AI Assessment of Privacy Leakage</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-11-13T13:14:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Belona Sonna, Alban Grastien, Claire Benn</p>
    <p><b>Summary:</b> Privacy leakage in AI-based decision processes poses significant risks, particularly when sensitive information can be inferred. We propose a formal framework to audit privacy leakage using abductive explanations, which identifies minimal sufficient evidence justifying model decisions and determines whether sensitive information disclosed. Our framework formalizes both individual and system-level leakage, introducing the notion of Potentially Applicable Explanations (PAE) to identify individuals whose outcomes can shield those with sensitive features. This approach provides rigorous privacy guarantees while producing human understandable explanations, a key requirement for auditing tools. Experimental evaluation on the German Credit Dataset illustrates how the importance of sensitive literal in the model decision process affects privacy leakage. Despite computational challenges and simplifying assumptions, our results demonstrate that abductive reasoning enables interpretable privacy auditing, offering a practical pathway to reconcile transparency, model interpretability, and privacy preserving in AI decision-making.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.10226v1">Privacy Structure and Blackwell Frontier</a></h3>
  
  <p><b>Published on:</b> 2025-11-13T11:56:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhang Xu, Wei Zhao</p>
    <p><b>Summary:</b> This paper characterizes the set of feasible posterior distributions subject to graph-based inferential privacy constraint, including both differential and inferential privacy. This characterization can be done through enumerating all extreme points of the feasible posterior set. A connection between extreme posteriors and strongly connected semi-chains is then established. All these semi-chains can be constructed through successive unfolding operations on semi-chains with two partitions, which can be constructed through classical spanning tree algorithm. A sharper characterization of semi-chains with two partitions for differential privacy is provided.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.10001v1">Mailing address aliasing as a method to protect consumer privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-11-13T06:12:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Greg Hather, Daniel Aranki</p>
    <p><b>Summary:</b> During online commerce, a customer will typically share his or her mailing address with a merchant to allow product delivery. This creates privacy risks for the customer, where the information may be misused, sold, or leaked by multiple merchants. While physical and virtual PO boxes can reduce the privacy risk, these solutions have associated costs that prevent greater adoption. Here, we introduce the concept of mailing address aliasing, which may offer lower cost and greater control in some cases. With this approach, an alias address is created that maps to the customer's true address. The mapping is kept private from the merchant but shared with the carrier. We discuss the advantages and disadvantages of this approach compared with traditional methods for mailing address privacy. We find that mailing address aliasing is likely to reduce unsolicited mail to a greater extent than physical or virtual PO boxes. However, mailing address aliasing may not be compatible with all merchants' ordering systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.09882v1">Truth, Justice, and Secrecy: Cake Cutting Under Privacy Constraints</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2025-11-13T02:28:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yaron Salman, Tamir Tassa, Omer Lev, Roie Zivan</p>
    <p><b>Summary:</b> Cake-cutting algorithms, which aim to fairly allocate a continuous resource based on individual agent preferences, have seen significant progress over the past two decades. Much of the research has concentrated on fairness, with comparatively less attention given to other important aspects. Chen et al. (2010) introduced an algorithm that, in addition to ensuring fairness, was strategyproof -- meaning agents had no incentive to misreport their valuations. However, even in the absence of strategic incentives to misreport, agents may still hesitate to reveal their true preferences due to privacy concerns (e.g., when allocating advertising time between firms, revealing preferences could inadvertently expose planned marketing strategies or product launch timelines). In this work, we extend the strategyproof algorithm of Chen et al. by introducing a privacy-preserving dimension. To the best of our knowledge, we present the first private cake-cutting protocol, and, in addition, this protocol is also envy-free and strategyproof. Our approach replaces the algorithm's centralized computation with a novel adaptation of cryptographic techniques, enabling privacy without compromising fairness or strategyproofness. Thus, our protocol encourages agents to report their true preferences not only because they are not incentivized to lie, but also because they are protected from having their preferences exposed.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.09846v1">Real-Time Lightweight Gaze Privacy-Preservation Techniques Validated via Offline Gaze-Based Interaction Simulation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-13T01:01:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mehedi Hasan Raju, Oleg V. Komogortsev</p>
    <p><b>Summary:</b> This study examines the effectiveness of the real-time privacy-preserving techniques through an offline gaze-based interaction simulation framework. Those techniques aim to reduce the amount of identity-related information in eye-tracking data while improving the efficacy of the gaze-based interaction. Although some real-time gaze privatization methods were previously explored, their validation on the large dataset was not conducted. We propose a functional framework that allows to study the efficacy of real-time gaze privatization on an already collected offline dataset. The key metric used to assess the reduction of identity-related information is the identification rate, while improvements in gaze-based interactions are evaluated through signal quality during interaction. Our additional contribution is the employment of an extremely lightweight Kalman filter framework that reduces the amount of identity-related information in the gaze signal and improves gaze-based interaction performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.09775v1">Privacy-Preserving Explainable AIoT Application via SHAP Entropy Regularization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2025-11-12T22:13:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dilli Prasad Sharma, Xiaowei Sun, Liang Xue, Xiaodong Lin, Pulei Xiong</p>
    <p><b>Summary:</b> The widespread integration of Artificial Intelligence of Things (AIoT) in smart home environments has amplified the demand for transparent and interpretable machine learning models. To foster user trust and comply with emerging regulatory frameworks, the Explainable AI (XAI) methods, particularly post-hoc techniques such as SHapley Additive exPlanations (SHAP), and Local Interpretable Model-Agnostic Explanations (LIME), are widely employed to elucidate model behavior. However, recent studies have shown that these explanation methods can inadvertently expose sensitive user attributes and behavioral patterns, thereby introducing new privacy risks. To address these concerns, we propose a novel privacy-preserving approach based on SHAP entropy regularization to mitigate privacy leakage in explainable AIoT applications. Our method incorporates an entropy-based regularization objective that penalizes low-entropy SHAP attribution distributions during training, promoting a more uniform spread of feature contributions. To evaluate the effectiveness of our approach, we developed a suite of SHAP-based privacy attacks that strategically leverage model explanation outputs to infer sensitive information. We validate our method through comparative evaluations using these attacks alongside utility metrics on benchmark smart home energy consumption datasets. Experimental results demonstrate that SHAP entropy regularization substantially reduces privacy leakage compared to baseline models, while maintaining high predictive accuracy and faithful explanation fidelity. This work contributes to the development of privacy-preserving explainable AI techniques for secure and trustworthy AIoT applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.09696v1">Cooperative Local Differential Privacy: Securing Time Series Data in Distributed Environments</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-12T19:52:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bikash Chandra Singh, Md Jakir Hossain, Rafael Diaz, Sandip Roy, Ravi Mukkamala, Sachin Shetty</p>
    <p><b>Summary:</b> The rapid growth of smart devices such as phones, wearables, IoT sensors, and connected vehicles has led to an explosion of continuous time series data that offers valuable insights in healthcare, transportation, and more. However, this surge raises significant privacy concerns, as sensitive patterns can reveal personal details. While traditional differential privacy (DP) relies on trusted servers, local differential privacy (LDP) enables users to perturb their own data. However, traditional LDP methods perturb time series data by adding user-specific noise but exhibit vulnerabilities. For instance, noise applied within fixed time windows can be canceled during aggregation (e.g., averaging), enabling adversaries to infer individual statistics over time, thereby eroding privacy guarantees.
  To address these issues, we introduce a Cooperative Local Differential Privacy (CLDP) mechanism that enhances privacy by distributing noise vectors across multiple users. In our approach, noise is collaboratively generated and assigned so that when all users' perturbed data is aggregated, the noise cancels out preserving overall statistical properties while protecting individual privacy. This cooperative strategy not only counters vulnerabilities inherent in time-window-based methods but also scales effectively for large, real-time datasets, striking a better balance between data utility and privacy in multiuser environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.09400v1">Abstract Gradient Training: A Unified Certification Framework for Data Poisoning, Unlearning, and Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-11-12T15:15:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Philip Sosnin, Matthew Wicker, Josh Collyer, Calvin Tsay</p>
    <p><b>Summary:</b> The impact of inference-time data perturbation (e.g., adversarial attacks) has been extensively studied in machine learning, leading to well-established certification techniques for adversarial robustness. In contrast, certifying models against training data perturbations remains a relatively under-explored area. These perturbations can arise in three critical contexts: adversarial data poisoning, where an adversary manipulates training samples to corrupt model performance; machine unlearning, which requires certifying model behavior under the removal of specific training data; and differential privacy, where guarantees must be given with respect to substituting individual data points. This work introduces Abstract Gradient Training (AGT), a unified framework for certifying robustness of a given model and training procedure to training data perturbations, including bounded perturbations, the removal of data points, and the addition of new samples. By bounding the reachable set of parameters, i.e., establishing provable parameter-space bounds, AGT provides a formal approach to analyzing the behavior of models trained via first-order optimization methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.09094v1">RIS-based Communication Enhancement and Location Privacy Protection in UAV Networks</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2025-11-12T08:10:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ziqi Chen, Jun Du, Chunxiao Jiang, Tony Q. S. Quek, Zhu Han</p>
    <p><b>Summary:</b> With the explosive advancement of unmanned aerial vehicles (UAVs), the security of efficient UAV networks has become increasingly critical. Owing to the open nature of its communication environment, illegitimate malicious UAVs (MUs) can infer the position of the source UAV (SU) by analyzing received signals, thus compromising the SU location privacy. To protect the SU location privacy while ensuring efficient communication with legitimate receiving UAVs (RUs), we propose an Active Reconfigurable Intelligent Surface (ARIS)-assisted covert communication scheme based on virtual partitioning and artificial noise (AN). Specifically, we design a novel ARIS architecture integrated with an AN module. This architecture dynamically partitions its reflecting elements into multiple sub-regions: one subset is optimized to enhance the communication rate between the SU and RUs, while the other subset generates AN to interfere with the localization of the SU by MUs. We first derive the Cramér-Rao Lower Bound (CRLB) for the localization with received signal strength (RSS), based on which, we establish a joint optimization framework for communication enhancement and localization interference. Subsequently, we derive and validate the optimal ARIS partitioning and power allocation under average channel conditions. Finally, tailored optimization methods are proposed for the reflection precoding and AN design of the two partitions. Simulation results validate that, compared to baseline schemes, the proposed scheme significantly increases the localization error of the SU by MUs while maintaining efficient communication between the SU and RUs, thereby effectively protecting the SU location privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.09043v1">MedHE: Communication-Efficient Privacy-Preserving Federated Learning with Adaptive Gradient Sparsification for Healthcare</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-11-12T06:50:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Farjana Yesmin</p>
    <p><b>Summary:</b> Healthcare federated learning requires strong privacy guarantees while maintaining computational efficiency across resource-constrained medical institutions. This paper presents MedHE, a novel framework combining adaptive gradient sparsification with CKKS homomorphic encryption to enable privacy-preserving collaborative learning on sensitive medical data. Our approach introduces a dynamic threshold mechanism with error compensation for top-k gradient selection, achieving 97.5 percent communication reduction while preserving model utility. We provide formal security analysis under Ring Learning with Errors assumptions and demonstrate differential privacy guarantees with epsilon less than or equal to 1.0. Statistical testing across 5 independent trials shows MedHE achieves 89.5 percent plus or minus 0.8 percent accuracy, maintaining comparable performance to standard federated learning (p=0.32) while reducing communication from 1277 MB to 32 MB per training round. Comprehensive evaluation demonstrates practical feasibility for real-world medical deployments with HIPAA compliance and scalability to 100 plus institutions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.08998v1">Experiences Building Enterprise-Level Privacy-Preserving Federated Learning to Power AI for Science</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-11-12T05:39:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zilinghan Li, Aditya Sinha, Yijiang Li, Kyle Chard, Kibaek Kim, Ravi Madduri</p>
    <p><b>Summary:</b> Federated learning (FL) is a promising approach to enabling collaborative model training without centralized data sharing, a crucial requirement in scientific domains where data privacy, ownership, and compliance constraints are critical. However, building user-friendly enterprise-level FL frameworks that are both scalable and privacy-preserving remains challenging, especially when bridging the gap between local prototyping and distributed deployment across heterogeneous client computing infrastructures. In this paper, based on our experiences building the Advanced Privacy-Preserving Federated Learning (APPFL) framework, we present our vision for an enterprise-grade, privacy-preserving FL framework designed to scale seamlessly across computing environments. We identify several key capabilities that such a framework must provide: (1) Scalable local simulation and prototyping to accelerate experimentation and algorithm design; (2) seamless transition from simulation to deployment; (3) distributed deployment across diverse, real-world infrastructures, from personal devices to cloud clusters and HPC systems; (4) multi-level abstractions that balance ease of use and research flexibility; and (5) comprehensive privacy and security through techniques such as differential privacy, secure aggregation, robust authentication, and confidential computing. We further discuss architectural designs to realize these goals. This framework aims to bridge the gap between research prototypes and enterprise-scale deployment, enabling scalable, reliable, and privacy-preserving AI for science.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.08666v1">Privacy Beyond Pixels: Latent Anonymization for Privacy-Preserving Video Understanding</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-11-11T18:56:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joseph Fioresi, Ishan Rajendrakumar Dave, Mubarak Shah</p>
    <p><b>Summary:</b> We introduce a novel formulation of visual privacy preservation for video foundation models that operates entirely in the latent space. While spatio-temporal features learned by foundation models have deepened general understanding of video content, sharing or storing these extracted visual features for downstream tasks inadvertently reveals sensitive personal information like skin color, gender, or clothing. Current privacy preservation methods focus on input-pixel-level anonymization, which requires retraining the entire utility video model and results in task-specific anonymization, making them unsuitable for recent video foundational models. To address these challenges, we introduce a lightweight Anonymizing Adapter Module (AAM) that removes private information from video features while retaining general task utility. AAM can be applied in a plug-and-play fashion to frozen video encoders, minimizing the computational burden of finetuning and re-extracting features. Our framework employs three newly designed training objectives: (1) a clip-level self-supervised privacy objective to reduce mutual information between static clips, (2) a co-training objective to retain utility across seen tasks, and (3) a latent consistency loss for generalization on unseen tasks. Our extensive evaluations demonstrate a significant 35% reduction in privacy leakage while maintaining near-baseline utility performance across various downstream tasks: Action Recognition (Kinetics400, UCF101, HMDB51), Temporal Action Detection (THUMOS14), and Anomaly Detection (UCF-Crime). We also provide an analysis on anonymization for sensitive temporal attribute recognition. Additionally, we propose new protocols for assessing gender bias in action recognition models, showing that our method effectively mitigates such biases and promotes more equitable video understanding.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.08059v1">"I need to learn better searching tactics for privacy policy laws.'' Investigating Software Developers' Behavior When Using Sources on Privacy Issues</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-11-11T09:58:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stefan Albert Horstmann, Sandy Hong, Maziar Niazian, Cristiana Santos, Alena Naiakshina</p>
    <p><b>Summary:</b> Since the introduction of the European General Data Protection Regulation (GDPR) and the California Consumer Privacy Act (CCPA), software developers increasingly have to make privacy-related decisions during system design and implementation. However, past research showed that they often lack legal expertise and struggle with privacy-compliant development. To shed light on how effective current information sources are in supporting them with privacy-sensitive implementation, we conducted a qualitative study with 30 developers. Participants were presented with a privacy-sensitive scenario and asked to identify privacy issues and suggest measures using their knowledge, online resources, and an AI assistant. We observed developers' decision-making in think-aloud sessions and discussed it in follow-up interviews. We found that participants struggled with all three sources: personal knowledge was insufficient, web content was often too complex, and while AI assistants provided clear and user-tailored responses, they lacked contextual relevance and failed to identify scenario-specific issues. Our study highlights major shortcomings in existing support for privacy-related development tasks. Based on our findings, we discuss the need for more accessible, understandable, and actionable privacy resources for developers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.07818v1">Blockchain-Integrated Privacy-Preserving Medical Insurance Claim Processing Using Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-11T04:22:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Diya Mamoria, Harshit Jain, Aswani Kumar Cherukuri</p>
    <p><b>Summary:</b> This research proposes a decentralized and cryptographically secure framework to address the most acute issues of privacy, data security, and protection in the ecosystem of medical insurance claim processing. The scope of this study focuses on enabling the management of insurance claims in a transparent, privacy-protecting manner while maintaining the efficiency and trust level needed by the patients, healthcare providers, and insurers. To accomplish this, the proposed system adds blockchain technology to provide an unchangeable, decentralized, and auditable claim transactions ledger which enhances overall claim-related processes and trust among all stakeholders. To protect critical patient information, the framework employs homomorphic encryption a modern form of cryptography to allow authorized insurance providers to perform necessary operations like claim adjudication and reimbursement on encrypted medical records without any decryption during the process. This method significantly reduces the third-party processing privacy risk because patient data can be kept secret even when third-party processing is done. In addition, smart contracts improve automation of the most important procedures in the claim processing pipeline, which decreases manual, operational, and susceptibility towards human blunders or deceitful acts. The integration of these two transformative technologiesblockchain and homomorphic encryption represents the core contribution of this work, enabling the coexistence of transparency and privacy which are usually viewed as competing objectives in traditional systems. As a result, these technologies are expected to foster the creation of a reliable, effective, and privacy safeguarding architecture that could transform the medical claim submission systems paradigm.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.07807v1">PRISM: Privacy-preserving Inference System with Homomorphic Encryption and Modular Activation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-11-11T03:57:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zeinab Elkhatib, Ali Sekmen, Kamrul Hasan</p>
    <p><b>Summary:</b> With the rapid advancements in machine learning, models have become increasingly capable of learning and making predictions in various industries. However, deploying these models in critical infrastructures presents a major challenge, as concerns about data privacy prevent unrestricted data sharing. Homomorphic encryption (HE) offers a solution by enabling computations on encrypted data, but it remains incompatible with machine learning models like convolutional neural networks (CNNs), due to their reliance on non-linear activation functions. To bridge this gap, this work proposes an optimized framework that replaces standard non-linear functions with homomorphically compatible approximations, ensuring secure computations while minimizing computational overhead. The proposed approach restructures the CNN architecture and introduces an efficient activation function approximation method to mitigate the performance trade-offs introduced by encryption. Experiments on CIFAR-10 achieve 94.4% accuracy with 2.42 s per single encrypted sample and 24,000 s per 10,000 encrypted samples, using a degree-4 polynomial and Softplus activation under CKKS, balancing accuracy and privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.07505v1">FedRW: Efficient Privacy-Preserving Data Reweighting for Enhancing Federated Learning of Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-11-10T18:29:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pukang Ye, Junwei Luo, Xiaolei Dong, Yunbo Yang</p>
    <p><b>Summary:</b> Data duplication within large-scale corpora often impedes large language models' (LLMs) performance and privacy. In privacy-concerned federated learning scenarios, conventional deduplication methods typically rely on trusted third parties to perform uniform deletion, risking loss of informative samples while introducing privacy vulnerabilities. To address these gaps, we propose Federated ReWeighting (FedRW), the first privacy-preserving framework, to the best of our knowledge, that performs soft deduplication via sample reweighting instead of deletion in federated LLM training, without assuming a trusted third party. At its core, FedRW proposes a secure, frequency-aware reweighting protocol through secure multi-party computation, coupled with a parallel orchestration strategy to ensure efficiency and scalability. During training, FedRW utilizes an adaptive reweighting mechanism with global sample frequencies to adjust individual loss contributions, effectively improving generalization and robustness. Empirical results demonstrate that FedRW outperforms the state-of-the-art method by achieving up to 28.78x speedup in preprocessing and approximately 11.42% improvement in perplexity, while offering enhanced security guarantees. FedRW thus establishes a new paradigm for managing duplication in federated LLM training.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.07242v3">Privacy on the Fly: A Predictive Adversarial Transformation Network for Mobile Sensor Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-10T15:57:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tianle Song, Chenhao Lin, Yang Cao, Zhengyu Zhao, Jiahao Sun, Chong Zhang, Le Yang, Chao Shen</p>
    <p><b>Summary:</b> Mobile motion sensors such as accelerometers and gyroscopes are now ubiquitously accessible by third-party apps via standard APIs. While enabling rich functionalities like activity recognition and step counting, this openness has also enabled unregulated inference of sensitive user traits, such as gender, age, and even identity, without user consent. Existing privacy-preserving techniques, such as GAN-based obfuscation or differential privacy, typically require access to the full input sequence, introducing latency that is incompatible with real-time scenarios. Worse, they tend to distort temporal and semantic patterns, degrading the utility of the data for benign tasks like activity recognition. To address these limitations, we propose the Predictive Adversarial Transformation Network (PATN), a real-time privacy-preserving framework that leverages historical signals to generate adversarial perturbations proactively. The perturbations are applied immediately upon data acquisition, enabling continuous protection without disrupting application functionality. Experiments on two datasets demonstrate that PATN substantially degrades the performance of privacy inference models, achieving Attack Success Rate (ASR) of 40.11% and 44.65% (reducing inference accuracy to near-random) and increasing the Equal Error Rate (EER) from 8.30% and 7.56% to 41.65% and 46.22%. On ASR, PATN outperforms baseline methods by 16.16% and 31.96%, respectively.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.07073v1">Breaking Privacy in Federated Clustering: Perfect Input Reconstruction via Temporal Correlations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-11-10T13:06:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guang Yang, Lixia Luo, Qiongxiu Li</p>
    <p><b>Summary:</b> Federated clustering allows multiple parties to discover patterns in distributed data without sharing raw samples. To reduce overhead, many protocols disclose intermediate centroids during training. While often treated as harmless for efficiency, whether such disclosure compromises privacy remains an open question. Prior analyses modeled the problem as a so-called Hidden Subset Sum Problem (HSSP) and argued that centroid release may be safe, since classical HSSP attacks fail to recover inputs.
  We revisit this question and uncover a new leakage mechanism: temporal regularities in $k$-means iterations create exploitable structure that enables perfect input reconstruction. Building on this insight, we propose Trajectory-Aware Reconstruction (TAR), an attack that combines temporal assignment information with algebraic analysis to recover exact original inputs. Our findings provide the first rigorous evidence, supported by a practical attack, that centroid disclosure in federated clustering significantly compromises privacy, exposing a fundamental tension between privacy and efficiency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.06778v2">SAFENLIDB: A Privacy-Preserving Safety Alignment Framework for LLM-based Natural Language Database Interfaces</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-11-10T07:05:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruiheng Liu, XiaoBing Chen, Jinyu Zhang, Qiongwen Zhang, Yu Zhang, Bailong Yang</p>
    <p><b>Summary:</b> The rapid advancement of Large Language Models (LLMs) has driven significant progress in Natural Language Interface to Database (NLIDB). However, the widespread adoption of LLMs has raised critical privacy and security concerns. During interactions, LLMs may unintentionally expose confidential database contents or be manipulated by attackers to exfiltrate data through seemingly benign queries. While current efforts typically rely on rule-based heuristics or LLM agents to mitigate this leakage risk, these methods still struggle with complex inference-based attacks, suffer from high false positive rates, and often compromise the reliability of SQL queries. To address these challenges, we propose \textsc{SafeNlidb}, a novel privacy-security alignment framework for LLM-based NLIDB. The framework features an automated pipeline that generates hybrid chain-of-thought interaction data from scratch, seamlessly combining implicit security reasoning with SQL generation. Additionally, we introduce reasoning warm-up and alternating preference optimization to overcome the multi-preference oscillations of Direct Preference Optimization (DPO), enabling LLMs to produce security-aware SQL through fine-grained reasoning without the need for human-annotated preference data. Extensive experiments demonstrate that our method outperforms both larger-scale LLMs and ideal-setting baselines, achieving significant security improvements while preserving high utility. WARNING: This work may contain content that is offensive and harmful!</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.06363v1">Privacy-Preserving Federated Learning for Fair and Efficient Urban Traffic Optimization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762"> 
  <p><b>Published on:</b> 2025-11-09T13:03:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rathin Chandra Shit, Sharmila Subudhi</p>
    <p><b>Summary:</b> The optimization of urban traffic is threatened by the complexity of achieving a balance between transport efficiency and the maintenance of privacy, as well as the equitable distribution of traffic based on socioeconomically diverse neighborhoods. Current centralized traffic management schemes invade user location privacy and further entrench traffic disparity by offering disadvantaged route suggestions, whereas current federated learning frameworks do not consider fairness constraints in multi-objective traffic settings. This study presents a privacy-preserving federated learning framework, termed FedFair-Traffic, that jointly and simultaneously optimizes travel efficiency, traffic fairness, and differential privacy protection. This is the first attempt to integrate three conflicting objectives to improve urban transportation systems. The proposed methodology enables collaborative learning between related vehicles with data locality by integrating Graph Neural Networks with differential privacy mechanisms ($ε$-privacy guarantees) and Gini coefficient-based fair constraints using multi-objective optimization. The framework uses federated aggregation methods of gradient clipping and noise injection to provide differential privacy and optimize Pareto-efficient solutions for the efficiency-fairness tradeoff. Real-world comprehensive experiments on the METR-LA traffic dataset showed that FedFair-Traffic can reduce the average travel time by 7\% (14.2 minutes) compared with their centralized baselines, promote traffic fairness by 73\% (Gini coefficient, 0.78), and offer high privacy protection (privacy score, 0.8) with an 89\% reduction in communication overhead. These outcomes demonstrate that FedFair-Traffic is a scalable privacy-aware smart city infrastructure with possible use-cases in metropolitan traffic flow control and federated transportation networks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.06305v1">Setting $\varepsilon$ is not the Issue in Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-11-09T10:03:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Edwige Cyffers</p>
    <p><b>Summary:</b> This position paper argues that setting the privacy budget in differential privacy should not be viewed as an important limitation of differential privacy compared to alternative methods for privacy-preserving machine learning. The so-called problem of interpreting the privacy budget is often presented as a major hindrance to the wider adoption of differential privacy in real-world deployments and is sometimes used to promote alternative mitigation techniques for data protection. We believe this misleads decision-makers into choosing unsafe methods. We argue that the difficulty in interpreting privacy budgets does not stem from the definition of differential privacy itself, but from the intrinsic difficulty of estimating privacy risks in context, a challenge that any rigorous method for privacy risk assessment face. Moreover, we claim that any sound method for estimating privacy risks should, given the current state of research, be expressible within the differential privacy framework or justify why it cannot.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.06231v1">Synheart Emotion: Privacy-Preserving On-Device Emotion Recognition from Biosignals</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-11-09T05:15:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Henok Ademtew, Israel Goytom</p>
    <p><b>Summary:</b> Human-computer interaction increasingly demands systems that recognize not only explicit user inputs but also implicit emotional states. While substantial progress has been made in affective computing, most emotion recognition systems rely on cloud-based inference, introducing privacy vulnerabilities and latency constraints unsuitable for real-time applications. This work presents a comprehensive evaluation of machine learning architectures for on-device emotion recognition from wrist-based photoplethysmography (PPG), systematically comparing different models spanning classical ensemble methods, deep neural networks, and transformers on the WESAD stress detection dataset. Results demonstrate that classical ensemble methods substantially outperform deep learning on small physiological datasets, with ExtraTrees achieving F1 = 0.826 on combined features and F1 = 0.623 on wrist-only features, compared to transformers achieving only F1 = 0.509-0.577. We deploy the wrist-only ExtraTrees model optimized via ONNX conversion, achieving a 4.08 MB footprint, 0.05 ms inference latency, and 152x speedup over the original implementation. Furthermore, ONNX optimization yields a 30.5% average storage reduction and 40.1x inference speedup, highlighting the feasibility of privacy-preserving on-device emotion recognition for real-world wearables.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.06064v1">A Privacy-Preserving Federated Learning Method with Homomorphic Encryption in Omics Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-11-08T16:18:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yusaku Negoya, Feifei Cui, Zilong Zhang, Miao Pan, Tomoaki Ohtsuki, Aohan Li</p>
    <p><b>Summary:</b> Omics data is widely employed in medical research to identify disease mechanisms and contains highly sensitive personal information. Federated Learning (FL) with Differential Privacy (DP) can ensure the protection of omics data privacy against malicious user attacks. However, FL with the DP method faces an inherent trade-off: stronger privacy protection degrades predictive accuracy due to injected noise. On the other hand, Homomorphic Encryption (HE) allows computations on encrypted data and enables aggregation of encrypted gradients without DP-induced noise can increase the predictive accuracy. However, it may increase the computation cost. To improve the predictive accuracy while considering the computational ability of heterogeneous clients, we propose a Privacy-Preserving Machine Learning (PPML)-Hybrid method by introducing HE. In the proposed PPML-Hybrid method, clients distributed select either HE or DP based on their computational resources, so that HE clients contribute noise-free updates while DP clients reduce computational overhead. Meanwhile, clients with high computational resources clients can flexibly adopt HE or DP according to their privacy needs. Performance evaluation on omics datasets show that our proposed method achieves comparable predictive accuracy while significantly reducing computation time relative to HE-only. Additionally, it outperforms DP-only methods under equivalent or stricter privacy budgets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.05327v1">Privacy-Preserving Cramér-Rao Lower Bound</a></h3>
  
  <p><b>Published on:</b> 2025-11-07T15:26:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jieming Ke, Jimin Wang, Ji-Feng Zhang</p>
    <p><b>Summary:</b> This paper establishes the privacy-preserving Cramér-Rao (CR) lower bound theory, characterizing the fundamental limit of identification accuracy under privacy constraint. An identifiability criterion under privacy constraint is derived by using Fisher information matrix as the privacy metric. In the identifiable case, the privacy-preserving CR lower bound is established and its attainability is demonstrated, thereby ensuring the existence of the privacy-preserving Fisher information matrix with explicit expression. Then, the privacy-preserving CR lower bound theory is extended to the multi-sensor multi-measurement system. Specifically, the additivity principle of privacy-preserving Fisher information matrices across both spatial and temporal dimensions is established, building a relationship between privacy-preserving CR lower bounds for the multi-sensor multi-measurement system and its subsystems. Using this additivity principle, distributed identification algorithms capable of achieving the privacy-preserving CR lower bound are further proposed. Numerical examples are provided to demonstrate the privacy-preserving CR lower bound and show the effectiveness of the proposed algorithms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.05092v1">A Dual-stage Prompt-driven Privacy-preserving Paradigm for Person Re-Identification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-11-07T09:17:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruolin Li, Min Liu, Yuan Bian, Zhaoyang Li, Yuzhen Li, Xueping Wang, Yaonan Wang</p>
    <p><b>Summary:</b> With growing concerns over data privacy, researchers have started using virtual data as an alternative to sensitive real-world images for training person re-identification (Re-ID) models. However, existing virtual datasets produced by game engines still face challenges such as complex construction and poor domain generalization, making them difficult to apply in real scenarios. To address these challenges, we propose a Dual-stage Prompt-driven Privacy-preserving Paradigm (DPPP). In the first stage, we generate rich prompts incorporating multi-dimensional attributes such as pedestrian appearance, illumination, and viewpoint that drive the diffusion model to synthesize diverse data end-to-end, building a large-scale virtual dataset named GenePerson with 130,519 images of 6,641 identities. In the second stage, we propose a Prompt-driven Disentanglement Mechanism (PDM) to learn domain-invariant generalization features. With the aid of contrastive learning, we employ two textual inversion networks to map images into pseudo-words representing style and content, respectively, thereby constructing style-disentangled content prompts to guide the model in learning domain-invariant content features at the image level. Experiments demonstrate that models trained on GenePerson with PDM achieve state-of-the-art generalization performance, surpassing those on popular real and virtual Re-ID datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.04438v1">Limiting one-way distillable secret key via privacy testing of extendible states</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2025-11-06T15:11:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vishal Singh, Karol Horodecki, Aby Philip, Mark M. Wilde</p>
    <p><b>Summary:</b> The notions of privacy tests and $k$-extendible states have both been instrumental in quantum information theory, particularly in understanding the limits of secure communication. In this paper, we determine the maximum probability with which an arbitrary $k$-extendible state can pass a privacy test, and we prove that it is equal to the maximum fidelity between an arbitrary $k$-extendible state and the standard maximally entangled state. Our findings, coupled with the resource theory of $k$-unextendibility, lead to an efficiently computable upper bound on the one-shot, one-way distillable key of a bipartite state, and we prove that it is equal to the best-known efficiently computable upper bound on the one-shot, one-way distillable entanglement. We also establish efficiently computable upper bounds on the one-shot, forward-assisted private capacity of channels. Extending our formalism to the independent and identically distributed setting, we obtain single-letter efficiently computable bounds on the $n$-shot, one-way distillable key of a state and the $n$-shot, forward-assisted private capacity of a channel. For some key examples of interest, our bounds are significantly tighter than other known efficiently computable bounds.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.04261v1">A Parallel Region-Adaptive Differential Privacy Framework for Image Pixelization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-06T10:51:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ming Liu</p>
    <p><b>Summary:</b> The widespread deployment of high-resolution visual sensing systems, coupled with the rise of foundation models, has amplified privacy risks in video-based applications. Differentially private pixelization offers mathematically guaranteed protection for visual data through grid-based noise addition, but challenges remain in preserving task-relevant fidelity, achieving scalability, and enabling efficient real-time deployment. To address this, we propose a novel parallel, region-adaptive pixelization framework that combines the theoretical rigor of differential privacy with practical efficiency. Our method adaptively adjusts grid sizes and noise scales based on regional complexity, leveraging GPU parallelism to achieve significant runtime acceleration compared to the classical baseline. A lightweight storage scheme is introduced by retaining only essential noisy statistics, significantly reducing space overhead. Formal privacy analysis is provided under the Laplace mechanism and parallel composition theorem. Extensive experiments on the PETS, Venice-2, and PPM-100 datasets demonstrate favorable privacy-utility trade-offs and significant runtime/storage reductions. A face re-identification attack experiment on CelebA further confirms the method's effectiveness in preventing identity inference. This validates its suitability for real-time privacy-critical applications such as elderly care, smart home monitoring, driver behavior analysis, and crowd behavior monitoring.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.03966v1">PrivacyCD: Hierarchical Unlearning for Protecting Student Privacy in Cognitive Diagnosis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-11-06T01:39:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mingliang Hou, Yinuo Wang, Teng Guo, Zitao Liu, Wenzhou Dou, Jiaqi Zheng, Renqiang Luo, Mi Tian, Weiqi Luo</p>
    <p><b>Summary:</b> The need to remove specific student data from cognitive diagnosis (CD) models has become a pressing requirement, driven by users' growing assertion of their "right to be forgotten". However, existing CD models are largely designed without privacy considerations and lack effective data unlearning mechanisms. Directly applying general purpose unlearning algorithms is suboptimal, as they struggle to balance unlearning completeness, model utility, and efficiency when confronted with the unique heterogeneous structure of CD models. To address this, our paper presents the first systematic study of the data unlearning problem for CD models, proposing a novel and efficient algorithm: hierarchical importanceguided forgetting (HIF). Our key insight is that parameter importance in CD models exhibits distinct layer wise characteristics. HIF leverages this via an innovative smoothing mechanism that combines individual and layer, level importance, enabling a more precise distinction of parameters associated with the data to be unlearned. Experiments on three real world datasets show that HIF significantly outperforms baselines on key metrics, offering the first effective solution for CD models to respond to user data removal requests and for deploying high-performance, privacy preserving AI systems</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.03665v1">A Lightweight 3D-CNN for Event-Based Human Action Recognition with Privacy-Preserving Potential</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-11-05T17:30:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mehdi Sefidgar Dilmaghani, Francis Fowley, Peter Corcoran</p>
    <p><b>Summary:</b> This paper presents a lightweight three-dimensional convolutional neural network (3DCNN) for human activity recognition (HAR) using event-based vision data. Privacy preservation is a key challenge in human monitoring systems, as conventional frame-based cameras capture identifiable personal information. In contrast, event cameras record only changes in pixel intensity, providing an inherently privacy-preserving sensing modality. The proposed network effectively models both spatial and temporal dynamics while maintaining a compact design suitable for edge deployment. To address class imbalance and enhance generalization, focal loss with class reweighting and targeted data augmentation strategies are employed. The model is trained and evaluated on a composite dataset derived from the Toyota Smart Home and ETRI datasets. Experimental results demonstrate an F1-score of 0.9415 and an overall accuracy of 94.17%, outperforming benchmark 3D-CNN architectures such as C3D, ResNet3D, and MC3_18 by up to 3%. These results highlight the potential of event-based deep learning for developing accurate, efficient, and privacy-aware human action recognition systems suitable for real-world edge applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.03538v1">Security and Privacy Management of IoT Using Quantum Computing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-05T15:08:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jaydip Sen</p>
    <p><b>Summary:</b> The convergence of the Internet of Things (IoT) and quantum computing is redefining the security paradigm of interconnected digital systems. Classical cryptographic algorithms such as RSA, Elliptic Curve Cryptography (ECC), and Advanced Encryption Standard (AES) have long provided the foundation for securing IoT communication. However, the emergence of quantum algorithms such as Shor's and Grover's threatens to render these techniques vulnerable, necessitating the development of quantum-resilient alternatives. This chapter examines the implications of quantum computing for IoT security and explores strategies for building cryptographically robust systems in the post-quantum era. It presents an overview of Post-Quantum Cryptographic (PQC) families, including lattice-based, code-based, hash-based, and multivariate approaches, analyzing their potential for deployment in resource-constrained IoT environments. In addition, quantum-based methods such as Quantum Key Distribution (QKD) and Quantum Random Number Generators (QRNGs) are discussed for their ability to enhance confidentiality and privacy through physics-based security guarantees. The chapter also highlights issues of privacy management, regulatory compliance, and standardization, emphasizing the need for collaborative efforts across academia, industry, and governance. Overall, it provides a comprehensive perspective on security IoT ecosystems against quantum threats and ensures resilience in the next generation of intelligent networks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.03248v2">Auditing M-LLMs for Privacy Risks: A Synthetic Benchmark and Evaluation Framework</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-05T07:23:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Junhao Li, Jiahao Chen, Zhou Feng, Chunyi Zhou</p>
    <p><b>Summary:</b> Recent advances in multi-modal Large Language Models (M-LLMs) have demonstrated a powerful ability to synthesize implicit information from disparate sources, including images and text. These resourceful data from social media also introduce a significant and underexplored privacy risk: the inference of sensitive personal attributes from seemingly daily media content. However, the lack of benchmarks and comprehensive evaluations of state-of-the-art M-LLM capabilities hinders the research of private attribute profiling on social media. Accordingly, we propose (1) PRISM, the first multi-modal, multi-dimensional and fine-grained synthesized dataset incorporating a comprehensive privacy landscape and dynamic user history; (2) an Efficient evaluation framework that measures the cross-modal privacy inference capabilities of advanced M-LLM. Specifically, PRISM is a large-scale synthetic benchmark designed to evaluate cross-modal privacy risks. Its key feature is 12 sensitive attribute labels across a diverse set of multi-modal profiles, which enables targeted privacy analysis. These profiles are generated via a sophisticated LLM agentic workflow, governed by a prior distribution to ensure they realistically mimic social media users. Additionally, we propose a Multi-Agent Inference Framework that leverages a pipeline of specialized LLMs to enhance evaluation capabilities. We evaluate the inference capabilities of six leading M-LLMs (Qwen, Gemini, GPT-4o, GLM, Doubao, and Grok) on PRISM. The comparison with human performance reveals that these MLLMs significantly outperform in accuracy and efficiency, highlighting the threat of potential privacy risks and the urgent need for robust defenses. Dataset available at https://huggingface.co/datasets/xaddh/multimodal-privacy</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.03753v2">Federated Learning with Gramian Angular Fields for Privacy-Preserving ECG Classification on Heterogeneous IoT Devices</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computational Engineering, Finance, and Science-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2025-11-04T22:23:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Youssef Elmir, Yassine Himeur, Abbes Amira</p>
    <p><b>Summary:</b> This study presents a federated learning (FL) framework for privacy-preserving electrocardiogram (ECG) classification in Internet of Things (IoT) healthcare environments. By transforming 1D ECG signals into 2D Gramian Angular Field (GAF) images, the proposed approach enables efficient feature extraction through Convolutional Neural Networks (CNNs) while ensuring that sensitive medical data remain local to each device. This work is among the first to experimentally validate GAF-based federated ECG classification across heterogeneous IoT devices, quantifying both performance and communication efficiency. To evaluate feasibility in realistic IoT settings, we deployed the framework across a server, a laptop, and a resource-constrained Raspberry Pi 4, reflecting edge-cloud integration in IoT ecosystems. Experimental results demonstrate that the FL-GAF model achieves a high classification accuracy of 95.18% in a multi-client setup, significantly outperforming a single-client baseline in both accuracy and training time. Despite the added computational complexity of GAF transformations, the framework maintains efficient resource utilization and communication overhead. These findings highlight the potential of lightweight, privacy-preserving AI for IoT-based healthcare monitoring, supporting scalable and secure edge deployments in smart health systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.02993v2">PrivyWave: Privacy-Aware Wireless Sensing of Heartbeat</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> 
  <p><b>Published on:</b> 2025-11-04T20:54:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yixuan Gao, Tanvir Ahmed, Zekun Chang, Thijs Roumen, Rajalakshmi Nandakumar</p>
    <p><b>Summary:</b> Wireless sensing technologies can now detect heartbeats using radio frequency and acoustic signals, raising significant privacy concerns. Existing privacy solutions either protect from all sensing systems indiscriminately preventing any utility or operate post-data collection, failing to enable selective access where authorized devices can monitor while unauthorized ones cannot. We present a key-based physical obfuscation system, PrivyWave, that addresses this challenge by generating controlled decoy heartbeat signals at cryptographically-determined frequencies. Unauthorized sensors receive a mixture of real and decoy signals that are indistinguishable without the secret key, while authorized sensors use the key to filter out decoys and recover accurate measurements. Our evaluation with 13 participants demonstrates effective protection across both sensing modalities: for mmWave radar, unauthorized sensors show 21.3 BPM mean absolute error while authorized sensors maintain a much smaller 5.8 BPM; for acoustic sensing, unauthorized error increases to 42.0 BPM while authorized sensors achieve 9.7 BPM. The system operates across multiple sensing modalities without per-modality customization and provides cryptographic obfuscation guarantees. Performance benchmarks show robust protection across different distances (30-150 cm), orientations (120° field of view), and diverse indoor environments, establishing physical-layer obfuscation as a viable approach for selective privacy in pervasive health monitoring.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.02797v1">Fast, Private, and Protected: Safeguarding Data Privacy and Defending Against Model Poisoning Attacks in Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-11-04T18:20:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nicolas Riccieri Gardin Assumpcao, Leandro Villas</p>
    <p><b>Summary:</b> Federated Learning (FL) is a distributed training paradigm wherein participants collaborate to build a global model while ensuring the privacy of the involved data, which remains stored on participant devices. However, proposals aiming to ensure such privacy also make it challenging to protect against potential attackers seeking to compromise the training outcome. In this context, we present Fast, Private, and Protected (FPP), a novel approach that aims to safeguard federated training while enabling secure aggregation to preserve data privacy. This is accomplished by evaluating rounds using participants' assessments and enabling training recovery after an attack. FPP also employs a reputation-based mechanism to mitigate the participation of attackers. We created a dockerized environment to validate the performance of FPP compared to other approaches in the literature (FedAvg, Power-of-Choice, and aggregation via Trimmed Mean and Median). Our experiments demonstrate that FPP achieves a rapid convergence rate and can converge even in the presence of malicious participants performing model poisoning attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.02785v1">Enhancing Federated Learning Privacy with QUBO</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2025-11-04T18:06:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Andras Ferenczi, Sutapa Samanta, Dagen Wang, Todd Hodges</p>
    <p><b>Summary:</b> Federated learning (FL) is a widely used method for training machine learning (ML) models in a scalable way while preserving privacy (i.e., without centralizing raw data). Prior research shows that the risk of exposing sensitive data increases cumulatively as the number of iterations where a client's updates are included in the aggregated model increase. Attackers can launch membership inference attacks (MIA; deciding whether a sample or client participated), property inference attacks (PIA; inferring attributes of a client's data), and model inversion attacks (MI; reconstructing inputs), thereby inferring client-specific attributes and, in some cases, reconstructing inputs. In this paper, we mitigate risk by substantially reducing per client exposure using a quantum computing-inspired quadratic unconstrained binary optimization (QUBO) formulation that selects a small subset of client updates most relevant for each training round. In this work, we focus on two threat vectors: (i) information leakage by clients during training and (ii) adversaries who can query or obtain the global model. We assume a trusted central server and do not model server compromise. This method also assumes that the server has access to a validation/test set with global data distribution. Experiments on the MNIST dataset with 300 clients in 20 rounds showed a 95.2% per-round and 49% cumulative privacy exposure reduction, with 147 clients' updates never being used during training while maintaining in general the full-aggregation accuracy or even better. The method proved to be efficient at lower scale and more complex model as well. A CINIC-10 dataset-based experiment with 30 clients resulted in 82% per-round privacy improvement and 33% cumulative privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.02297v1">Two-Parameter Rényi Information Quantities with Applications to Privacy Amplification and Soft Covering</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2025-11-04T06:21:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shi-Bing Li, Ke Li, Lei Yu</p>
    <p><b>Summary:</b> There are no universally accepted definitions of Rényi conditional entropy and Rényi mutual information, although motivated by different applications, several definitions have been proposed in the literature. In this paper, we consider a family of two-parameter Rényi conditional entropy and a family of two-parameter Rényi mutual information. By performing a change of variables for the parameters, the two-parameter Rényi conditional entropy we study coincides precisely with the definition introduced by Hayashi and Tan [IEEE Trans. Inf. Theory, 2016], and it also emerges naturally as the classical specialization of the three-parameter quantum Rényi conditional entropy recently put forward by Rubboli, Goodarzi, and Tomamichel [arXiv:2410.21976 (2024)]. We establish several fundamental properties of the two-parameter Rényi conditional entropy, including monotonicity with respect to the parameters and variational expression. The associated two-parameter Rényi mutual information considered in this paper is new and it unifies three commonly used variants of Rényi mutual information. For this quantity, we prove several important properties, including the non-negativity, additivity, data processing inequality, monotonicity with respect to the parameters, variational expression, as well as convexity and concavity. Finally, we demonstrate that these two-parameter Rényi information quantities can be used to characterize the strong converse exponents in privacy amplification and soft covering problems under Rényi divergence of order $α\in (0, \infty)$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.02283v1">Distributed Nonconvex Optimization with Double Privacy Protection and Exact Convergence</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E">
  <p><b>Published on:</b> 2025-11-04T05:51:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zichong Ou, Dandan Wang, Zixuan Liu, Jie Lu</p>
    <p><b>Summary:</b> Motivated by the pervasive lack of privacy protection in existing distributed nonconvex optimization methods, this paper proposes a decentralized proximal primal-dual algorithm enabling double protection of privacy ($\text{DPP}^2$) for minimizing nonconvex sum-utility functions over multi-agent networks, which ensures zero leakage of critical local information during inter-agent communications. We develop a two-tier privacy protection mechanism that first merges the primal and dual variables by means of a variable transformation, followed by embedding an additional random perturbation to further obfuscate the transmitted information. We theoretically establish that $\text{DPP}^2$ ensures differential privacy for local objectives while achieving exact convergence under nonconvex settings. Specifically, $\text{DPP}^2$ converges sublinearly to a stationary point and attains a linear convergence rate under the additional Polyak-Łojasiewicz (P-Ł) condition. Finally, a numerical example demonstrates the superiority of $\text{DPP}^2$ over a number of state-of-the-art algorithms, showcasing the faster, exact convergence achieved by $\text{DPP}^2$ under the same level of differential privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.02227v2">Interval Estimation for Binomial Proportions Under Differential Privacy</a></h3>
  
  <p><b>Published on:</b> 2025-11-04T03:41:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hsuan-Chen Kao, Jerome P. Reiter</p>
    <p><b>Summary:</b> When releasing binary proportions computed using sensitive data, several government agencies and other data stewards protect confidentiality of the underlying values by ensuring the released statistics satisfy differential privacy. Typically, this is done by adding carefully chosen noise to the sample proportion computed using the confidential data. In this article, we describe and compare methods for turning this differentially private proportion into an interval estimate for an underlying population probability. Specifically, we consider differentially private versions of the Wald and Wilson intervals, Bayesian credible intervals based on denoising the differentially private proportion, and an exact interval motivated by the Clopper-Pearson confidence interval. We examine the repeated sampling performances of the intervals using simulation studies under both the Laplace mechanism and discrete Gaussian mechanism across a range of privacy guarantees. We find that while several methods can offer reasonable performances, the Bayesian credible intervals are the most attractive.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.07441v1">AudAgent: Automated Auditing of Privacy Policy Compliance in AI Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-11-03T17:32:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ye Zheng, Yidan Hu</p>
    <p><b>Summary:</b> AI agents can autonomously perform tasks and, often without explicit user consent, collect or disclose users' sensitive local data, which raises serious privacy concerns. Although AI agents' privacy policies may describe their intended data practices, there remains limited transparency and accountability about whether runtime behavior matches those policies. To close this gap, we introduce AudAgent, a visual framework that continuously monitors AI agents' data practices in real time and guards compliance with stated privacy policies.
  AudAgent consists of four components for automated privacy auditing of AI agents. (i) Policy parsing: an ensemble of LLMs translates natural-language privacy policies into a structured privacy-policy model, where cross-LLM voting guarantees confidence of the parsing results. (ii) Runtime annotation: a lightweight Presidio-based analyzer detects sensitive data and annotates how the data is used based on the context of the AI agent's operations and the privacy-policy model. (iii) Compliance auditing: ontology alignment and automata-based evaluation connect the policy model with runtime annotations, enabling on-the-fly compliance checks between the natural-language policy and observed unordered data practices of AI agents. (iv) User interface: a platform-independent implementation visualizes the real-time execution trace of AI agents along with potential privacy risks detected during auditing, providing user-friendly transparency and accountability.
  In addition to common formatted privacy policies, AudAgent also supports user-defined policies for fine-grained control and customization. We evaluate AudAgent on AI agents built upon mainstream programming frameworks such as AutoGen, experiments show that AudAgent effectively identifies potential privacy policy violations in real time.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.01752v1">An assessment of the Commission's Proposal on Privacy and Electronic Communications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-11-03T17:01:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Frederik Zuiderveen Borgesius, Joris van Hoboken, Ronan Fahy, Kristina Irion, Max Rozendaal</p>
    <p><b>Summary:</b> This study, commissioned by the European Parliament's Policy Department for Citizens Rights and Constitutional Affairs at the request of the LIBE Committee, appraises the European Commission's proposal for an ePrivacy Regulation. The study assesses whether the proposal would ensure that the right to the protection of personal data, the right to respect for private life and communications, and related rights enjoy a high standard of protection. The study also highlights the proposal's potential benefits and drawbacks more generally.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.01654v1">Panther: A Cost-Effective Privacy-Preserving Framework for GNN Training and Inference Services in Cloud Environments</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-11-03T15:15:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Congcong Chen, Xinyu Liu, Kaifeng Huang, Lifei Wei, Yang Shi</p>
    <p><b>Summary:</b> Graph Neural Networks (GNNs) have marked significant impact in traffic state prediction, social recommendation, knowledge-aware question answering and so on. As more and more users move towards cloud computing, it has become a critical issue to unleash the power of GNNs while protecting the privacy in cloud environments. Specifically, the training data and inference data for GNNs need to be protected from being stolen by external adversaries. Meanwhile, the financial cost of cloud computing is another primary concern for users. Therefore, although existing studies have proposed privacy-preserving techniques for GNNs in cloud environments, their additional computational and communication overhead remain relatively high, causing high financial costs that limit their widespread adoption among users.
  To protect GNN privacy while lowering the additional financial costs, we introduce Panther, a cost-effective privacy-preserving framework for GNN training and inference services in cloud environments. Technically, Panther leverages four-party computation to asynchronously executing the secure array access protocol, and randomly pads the neighbor information of GNN nodes. We prove that Panther can protect privacy for both training and inference of GNN models. Our evaluation shows that Panther reduces the training and inference time by an average of 75.28% and 82.80%, respectively, and communication overhead by an average of 52.61% and 50.26% compared with the state-of-the-art, which is estimated to save an average of 55.05% and 59.00% in financial costs (based on on-demand pricing model) for the GNN training and inference process on Google Cloud Platform.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.01583v1">Federated Cyber Defense: Privacy-Preserving Ransomware Detection Across Distributed Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-11-03T13:54:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Daniel M. Jimenez-Gutierrez, Enrique Zuazua, Joaquin Del Rio, Oleksii Sliusarenko, Xabi Uribe-Etxebarria</p>
    <p><b>Summary:</b> Detecting malware, especially ransomware, is essential to securing today's interconnected ecosystems, including cloud storage, enterprise file-sharing, and database services. Training high-performing artificial intelligence (AI) detectors requires diverse datasets, which are often distributed across multiple organizations, making centralization necessary. However, centralized learning is often impractical due to security, privacy regulations, data ownership issues, and legal barriers to cross-organizational sharing. Compounding this challenge, ransomware evolves rapidly, demanding models that are both robust and adaptable.
  In this paper, we evaluate Federated Learning (FL) using the Sherpa.ai FL platform, which enables multiple organizations to collaboratively train a ransomware detection model while keeping raw data local and secure. This paradigm is particularly relevant for cybersecurity companies (including both software and hardware vendors) that deploy ransomware detection or firewall systems across millions of endpoints. In such environments, data cannot be transferred outside the customer's device due to strict security, privacy, or regulatory constraints. Although FL applies broadly to malware threats, we validate the approach using the Ransomware Storage Access Patterns (RanSAP) dataset.
  Our experiments demonstrate that FL improves ransomware detection accuracy by a relative 9% over server-local models and achieves performance comparable to centralized training. These results indicate that FL offers a scalable, high-performing, and privacy-preserving framework for proactive ransomware detection across organizational and regulatory boundaries.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.01467v2">Quantum Information Ordering and Differential Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-11-03T11:24:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ayanava Dasgupta, Naqueeb Ahmad Warsi, Masahito Hayashi</p>
    <p><b>Summary:</b> We study quantum differential privacy (QDP) by defining a notion of the order of informativeness between two pairs of quantum states. In particular, we show that if the hypothesis testing divergence of the one pair dominates over that of the other pair, then this dominance holds for every $f$-divergence. This approach completely characterizes $(\varepsilon,δ)$-QDP mechanisms by identifying the most informative $(\varepsilon,δ)$-DP quantum state pairs. We apply this to analyze the stability of quantum differentially private learning algorithms, generalizing classical results to the case $δ>0$. Additionally, we study precise limits for privatized hypothesis testing and privatized quantum parameter estimation, including tight upper-bounds on the quantum Fisher information under QDP. Finally, we establish near-optimal contraction bounds for differentially private quantum channels with respect to the hockey-stick divergence.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.01449v1">Privacy Preserving Ordinal-Meta Learning with VLMs for Fine-Grained Fruit Quality Prediction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-11-03T11:03:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Riddhi Jain, Manasi Patwardhan, Aayush Mishra, Parijat Deshpande, Beena Rai</p>
    <p><b>Summary:</b> To effectively manage the wastage of perishable fruits, it is crucial to accurately predict their freshness or shelf life using non-invasive methods that rely on visual data. In this regard, deep learning techniques can offer a viable solution. However, obtaining fine-grained fruit freshness labels from experts is costly, leading to a scarcity of data. Closed proprietary Vision Language Models (VLMs), such as Gemini, have demonstrated strong performance in fruit freshness detection task in both zero-shot and few-shot settings. Nonetheless, food retail organizations are unable to utilize these proprietary models due to concerns related to data privacy, while existing open-source VLMs yield sub-optimal performance for the task. Fine-tuning these open-source models with limited data fails to achieve the performance levels of proprietary models. In this work, we introduce a Model-Agnostic Ordinal Meta-Learning (MAOML) algorithm, designed to train smaller VLMs. This approach utilizes meta-learning to address data sparsity and leverages label ordinality, thereby achieving state-of-the-art performance in the fruit freshness classification task under both zero-shot and few-shot settings. Our method achieves an industry-standard accuracy of 92.71%, averaged across all fruits.
  Keywords: Fruit Quality Prediction, Vision Language Models, Meta Learning, Ordinal Regression</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.01307v1">Perturb a Model, Not an Image: Towards Robust Privacy Protection via Anti-Personalized Diffusion Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-11-03T07:42:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tae-Young Lee, Juwon Seo, Jong Hwan Ko, Gyeong-Moon Park</p>
    <p><b>Summary:</b> Recent advances in diffusion models have enabled high-quality synthesis of specific subjects, such as identities or objects. This capability, while unlocking new possibilities in content creation, also introduces significant privacy risks, as personalization techniques can be misused by malicious users to generate unauthorized content. Although several studies have attempted to counter this by generating adversarially perturbed samples designed to disrupt personalization, they rely on unrealistic assumptions and become ineffective in the presence of even a few clean images or under simple image transformations. To address these challenges, we shift the protection target from the images to the diffusion model itself to hinder the personalization of specific subjects, through our novel framework called Anti-Personalized Diffusion Models (APDM). We first provide a theoretical analysis demonstrating that a naive approach of existing loss functions to diffusion models is inherently incapable of ensuring convergence for robust anti-personalization. Motivated by this finding, we introduce Direct Protective Optimization (DPO), a novel loss function that effectively disrupts subject personalization in the target model without compromising generative quality. Moreover, we propose a new dual-path optimization strategy, coined Learning to Protect (L2P). By alternating between personalization and protection paths, L2P simulates future personalization trajectories and adaptively reinforces protection at each step. Experimental results demonstrate that our framework outperforms existing methods, achieving state-of-the-art performance in preventing unauthorized personalization. The code is available at https://github.com/KU-VGI/APDM.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.01197v3">CryptoMoE: Privacy-Preserving and Scalable Mixture of Experts Inference via Balanced Expert Routing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-11-03T03:45:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yifan Zhou, Tianshi Xu, Jue Hong, Ye Wu, Meng Li</p>
    <p><b>Summary:</b> Private large language model (LLM) inference based on cryptographic primitives offers a promising path towards privacy-preserving deep learning. However, existing frameworks only support dense LLMs like LLaMA-1 and struggle to scale to mixture-of-experts (MoE) architectures. The key challenge comes from securely evaluating the dynamic routing mechanism in MoE layers, which may reveal sensitive input information if not fully protected. In this paper, we propose CryptoMoE, the first framework that enables private, efficient, and accurate inference for MoE-based models. CryptoMoE balances expert loads to protect expert routing information and proposes novel protocols for secure expert dispatch and combine. CryptoMoE also develops a confidence-aware token selection strategy and a batch matrix multiplication protocol to improve accuracy and efficiency further. Extensive experiments on DeepSeekMoE-16.4B, OLMoE-6.9B, and QWenMoE-14.3B show that CryptoMoE achieves $2.8\sim3.5\times$ end-to-end latency reduction and $2.9\sim4.3\times$ communication reduction over a dense baseline with minimum accuracy loss. We also adapt CipherPrune (ICLR'25) for MoE inference and demonstrate CryptoMoE can reduce the communication by up to $4.3 \times$. Code is available at: https://github.com/PKU-SEC-Lab/CryptoMoE.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.00795v1">FedOnco-Bench: A Reproducible Benchmark for Privacy-Aware Federated Tumor Segmentation with Synthetic CT Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-11-02T04:17:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Viswa Chaitanya Marella, Suhasnadh Reddy Veluru, Sai Teja Erukude</p>
    <p><b>Summary:</b> Federated Learning (FL) allows multiple institutions to cooperatively train machine learning models while retaining sensitive data at the source, which has great utility in privacy-sensitive environments. However, FL systems remain vulnerable to membership-inference attacks and data heterogeneity. This paper presents FedOnco-Bench, a reproducible benchmark for privacy-aware FL using synthetic oncologic CT scans with tumor annotations. It evaluates segmentation performance and privacy leakage across FL methods: FedAvg, FedProx, FedBN, and FedAvg with DP-SGD. Results show a distinct trade-off between privacy and utility: FedAvg is high performance (Dice around 0.85) with more privacy leakage (attack AUC about 0.72), while DP-SGD provides a higher level of privacy (AUC around 0.25) at the cost of accuracy (Dice about 0.79). FedProx and FedBN offer balanced performance under heterogeneous data, especially with non-identical distributed client data. FedOnco-Bench serves as a standardized, open-source platform for benchmarking and developing privacy-preserving FL methods for medical image segmentation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.00737v1">EP-HDC: Hyperdimensional Computing with Encrypted Parameters for High-Throughput Privacy-Preserving Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-11-01T23:22:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jaewoo Park, Chenghao Quan, Jongeun Lee</p>
    <p><b>Summary:</b> While homomorphic encryption (HE) provides strong privacy protection, its high computational cost has restricted its application to simple tasks. Recently, hyperdimensional computing (HDC) applied to HE has shown promising performance for privacy-preserving machine learning (PPML). However, when applied to more realistic scenarios such as batch inference, the HDC-based HE has still very high compute time as well as high encryption and data transmission overheads. To address this problem, we propose HDC with encrypted parameters (EP-HDC), which is a novel PPML approach featuring client-side HE, i.e., inference is performed on a client using a homomorphically encrypted model. Our EP-HDC can effectively mitigate the encryption and data transmission overhead, as well as providing high scalability with many clients while providing strong protection for user data and model parameters. In addition to application examples for our client-side PPML, we also present design space exploration involving quantization, architecture, and HE-related parameters. Our experimental results using the BFV scheme and the Face/Emotion datasets demonstrate that our method can improve throughput and latency of batch inference by orders of magnitude over previous PPML methods (36.52~1068x and 6.45~733x, respectively) with less than 1% accuracy degradation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.00700v1">Privacy-Aware Time Series Synthesis via Public Knowledge Distillation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-11-01T20:44:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Penghang Liu, Haibei Zhu, Eleonora Kreacic, Svitlana Vyetrenko</p>
    <p><b>Summary:</b> Sharing sensitive time series data in domains such as finance, healthcare, and energy consumption, such as patient records or investment accounts, is often restricted due to privacy concerns. Privacy-aware synthetic time series generation addresses this challenge by enforcing noise during training, inherently introducing a trade-off between privacy and utility. In many cases, sensitive sequences is correlated with publicly available, non-sensitive contextual metadata (e.g., household electricity consumption may be influenced by weather conditions and electricity prices). However, existing privacy-aware data generation methods often overlook this opportunity, resulting in suboptimal privacy-utility trade-offs. In this paper, we present Pub2Priv, a novel framework for generating private time series data by leveraging heterogeneous public knowledge. Our model employs a self-attention mechanism to encode public data into temporal and feature embeddings, which serve as conditional inputs for a diffusion model to generate synthetic private sequences. Additionally, we introduce a practical metric to assess privacy by evaluating the identifiability of the synthetic data. Experimental results show that Pub2Priv consistently outperforms state-of-the-art benchmarks in improving the privacy-utility trade-off across finance, energy, and commodity trading domains.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.00487v1">With Privacy, Size Matters: On the Importance of Dataset Size in Differentially Private Text Rewriting</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-11-01T10:41:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stephen Meisenbacher, Florian Matthes</p>
    <p><b>Summary:</b> Recent work in Differential Privacy with Natural Language Processing (DP NLP) has proposed numerous promising techniques in the form of text rewriting mechanisms. In the evaluation of these mechanisms, an often-ignored aspect is that of dataset size, or rather, the effect of dataset size on a mechanism's efficacy for utility and privacy preservation. In this work, we are the first to introduce this factor in the evaluation of DP text privatization, where we design utility and privacy tests on large-scale datasets with dynamic split sizes. We run these tests on datasets of varying size with up to one million texts, and we focus on quantifying the effect of increasing dataset size on the privacy-utility trade-off. Our findings reveal that dataset size plays an integral part in evaluating DP text rewriting mechanisms; additionally, these findings call for more rigorous evaluation procedures in DP NLP, as well as shed light on the future of DP NLP in practice and at scale.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.00467v1">A Big Step Forward? A User-Centric Examination of iOS App Privacy Report and Enhancements</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-11-01T09:29:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Liu Wang, Dong Wang, Shidong Pan, Zheng Jiang, Haoyu Wang, Yi Wang</p>
    <p><b>Summary:</b> The prevalent engagement with mobile apps underscores the importance of understanding their data practices. Transparency plays a crucial role in this context, ensuring users to be informed and give consent before any data access occurs. Apple introduced a new feature since iOS 15.2, App Privacy Report, to inform users about detailed insights into apps' data access and sharing. This feature continues Apple's trend of privacy-focused innovations (following Privacy Nutrition Labels), and has been marketed as a big step forward in user privacy. However, its real-world impacts on user privacy and control remain unexamined. We thus proposed an end-to-end study involving systematic assessment of the App Privacy Report's real-world benefits and limitations, LLM-enabled and multi-technique synthesized enhancements, and comprehensive evaluation from both system and user perspectives. Through a structured focus group study with twelve everyday iOS users, we explored their experiences, understanding, and perceptions of the feature, suggesting its limited practical impact resulting from missing important details. We identified two primary user concerns: the clarity of data access purpose and domain description. In response, we proposed enhancements including a purpose inference framework and domain clarification pipeline. We demonstrated the effectiveness and benefits of such enhancements for mobile app users. This work provides practical insights that could help enhance user privacy transparency and discusses areas for future research.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.00414v1">Embedding based Encoding Scheme for Privacy Preserving Record Linkage</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2025-11-01T05:57:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sirintra Vaiwsri, Thilina Ranbaduge</p>
    <p><b>Summary:</b> To discover new insights from data, there is a growing need to share information that is often held by different organisations. One key task in data integration is the calculation of similarities between records in different databases to identify pairs or sets of records that correspond to the same real-world entities. Due to privacy and confidentiality concerns, however, the owners of sensitive databases are often not allowed or willing to exchange or share their data with other organisations to allow such similarity calculations. Privacy-preserving record linkage (PPRL) is the process of matching records that refer to the same entity across sensitive databases held by different organisations while ensuring no information about the entities is revealed to the participating parties. In this paper, we study how embedding based encoding techniques can be applied in the PPRL context to ensure the privacy of the entities that are being linked. We first convert individual q-grams into the embedded space and then convert the embedding of a set of q-grams of a given record into a binary representation. The final binary representations can be used to link records into matches and non-matches. We empirically evaluate our proposed encoding technique against different real-world datasets. The results suggest that our proposed encoding approach can provide better linkage accuracy and protect the privacy of individuals against attack compared to state-of-the-art techniques for short record values.</p>
  </details>
</div>



<h2>2025-10</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2511.00269v1">FedReplay: A Feature Replay Assisted Federated Transfer Learning Framework for Efficient and Privacy-Preserving Smart Agriculture</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-10-31T21:44:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Long Li, Jiajia Li, Dong Chen, Lina Pu, Haibo Yao, Yanbo Huang</p>
    <p><b>Summary:</b> Accurate classification plays a pivotal role in smart agriculture, enabling applications such as crop monitoring, fruit recognition, and pest detection. However, conventional centralized training often requires large-scale data collection, which raises privacy concerns, while standard federated learning struggles with non-independent and identically distributed (non-IID) data and incurs high communication costs. To address these challenges, we propose a federated learning framework that integrates a frozen Contrastive Language-Image Pre-training (CLIP) vision transformer (ViT) with a lightweight transformer classifier. By leveraging the strong feature extraction capability of the pre-trained CLIP ViT, the framework avoids training large-scale models from scratch and restricts federated updates to a compact classifier, thereby reducing transmission overhead significantly. Furthermore, to mitigate performance degradation caused by non-IID data distribution, a small subset (1%) of CLIP-extracted feature representations from all classes is shared across clients. These shared features are non-reversible to raw images, ensuring privacy preservation while aligning class representation across participants. Experimental results on agricultural classification tasks show that the proposed method achieve 86.6% accuracy, which is more than 4 times higher compared to baseline federated learning approaches. This demonstrates the effectiveness and efficiency of combining vision-language model features with federated learning for privacy-preserving and scalable agricultural intelligence.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.27275v1">Prevalence of Security and Privacy Risk-Inducing Usage of AI-based Conversational Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-31T08:35:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kathrin Grosse, Nico Ebert</p>
    <p><b>Summary:</b> Recent improvement gains in large language models (LLMs) have lead to everyday usage of AI-based Conversational Agents (CAs). At the same time, LLMs are vulnerable to an array of threats, including jailbreaks and, for example, causing remote code execution when fed specific inputs. As a result, users may unintentionally introduce risks, for example, by uploading malicious files or disclosing sensitive information. However, the extent to which such user behaviors occur and thus potentially facilitate exploits remains largely unclear. To shed light on this issue, we surveyed a representative sample of 3,270 UK adults in 2024 using Prolific. A third of these use CA services such as ChatGPT or Gemini at least once a week. Of these ``regular users'', up to a third exhibited behaviors that may enable attacks, and a fourth have tried jailbreaking (often out of understandable reasons such as curiosity, fun or information seeking). Half state that they sanitize data and most participants report not sharing sensitive data. However, few share very sensitive data such as passwords. The majority are unaware that their data can be used to train models and that they can opt-out. Our findings suggest that current academic threat models manifest in the wild, and mitigations or guidelines for the secure usage of CAs should be developed. In areas critical to security and privacy, CAs must be equipped with effective AI guardrails to prevent, for example, revealing sensitive information to curious employees. Vendors need to increase efforts to prevent the entry of sensitive data, and to create transparency with regard to data usage policies and settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.27213v1">Privacy-Aware Continual Self-Supervised Learning on Multi-Window Chest Computed Tomography for Domain-Shift Robustness</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-10-31T06:16:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ren Tasai, Guang Li, Ren Togo, Takahiro Ogawa, Kenji Hirata, Minghui Tang, Takaaki Yoshimura, Hiroyuki Sugimori, Noriko Nishioka, Yukie Shimizu, Kohsuke Kudo, Miki Haseyama</p>
    <p><b>Summary:</b> We propose a novel continual self-supervised learning (CSSL) framework for simultaneously learning diverse features from multi-window-obtained chest computed tomography (CT) images and ensuring data privacy. Achieving a robust and highly generalizable model in medical image diagnosis is challenging, mainly because of issues, such as the scarcity of large-scale, accurately annotated datasets and domain shifts inherent to dynamic healthcare environments. Specifically, in chest CT, these domain shifts often arise from differences in window settings, which are optimized for distinct clinical purposes. Previous CSSL frameworks often mitigated domain shift by reusing past data, a typically impractical approach owing to privacy constraints. Our approach addresses these challenges by effectively capturing the relationship between previously learned knowledge and new information across different training stages through continual pretraining on unlabeled images. Specifically, by incorporating a latent replay-based mechanism into CSSL, our method mitigates catastrophic forgetting due to domain shifts during continual pretraining while ensuring data privacy. Additionally, we introduce a feature distillation technique that integrates Wasserstein distance-based knowledge distillation (WKD) and batch-knowledge ensemble (BKE), enhancing the ability of the model to learn meaningful, domain-shift-robust representations. Finally, we validate our approach using chest CT images obtained across two different window settings, demonstrating superior performance compared with other approaches.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.27016v1">Semantically-Aware LLM Agent to Enhance Privacy in Conversational AI Services</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-10-30T21:34:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jayden Serenari, Stephen Lee</p>
    <p><b>Summary:</b> With the increasing use of conversational AI systems, there is growing concern over privacy leaks, especially when users share sensitive personal data in interactions with Large Language Models (LLMs). Conversations shared with these models may contain Personally Identifiable Information (PII), which, if exposed, could lead to security breaches or identity theft. To address this challenge, we present the Local Optimizations for Pseudonymization with Semantic Integrity Directed Entity Detection (LOPSIDED) framework, a semantically-aware privacy agent designed to safeguard sensitive PII data when using remote LLMs. Unlike prior work that often degrade response quality, our approach dynamically replaces sensitive PII entities in user prompts with semantically consistent pseudonyms, preserving the contextual integrity of conversations. Once the model generates its response, the pseudonyms are automatically depseudonymized, ensuring the user receives an accurate, privacy-preserving output. We evaluate our approach using real-world conversations sourced from ShareGPT, which we further augment and annotate to assess whether named entities are contextually relevant to the model's response. Our results show that LOPSIDED reduces semantic utility errors by a factor of 5 compared to baseline techniques, all while enhancing privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.26523v1">Interdependent Privacy in Smart Homes: Hunting for Bystanders in Privacy Policies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-30T14:16:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuaishuai Liu, Gergely Acs, Gergely Biczók</p>
    <p><b>Summary:</b> Smart home devices such as video doorbells and security cameras are becoming increasingly common in everyday life. While these devices offer convenience and safety, they also raise new privacy concerns: how these devices affect others, like neighbors, visitors, or people passing by. This issue is generally known as interdependent privacy, where one person's actions (or inaction) may impact the privacy of others, and, specifically, bystander privacy in the context of smart homes. Given lax data protection regulations in terms of shared physical spaces and amateur joint data controllers, we expect that the privacy policies of smart home products reflect the missing regulatory incentives. This paper presents a focused privacy policy analysis of 20 video doorbell and smart camera products, concentrating explicitly on the bystander aspect. We show that although some of the vendors acknowledge bystanders, they address it only to the extent of including disclaimers, shifting the ethical responsibility for collecting the data of non-users to the device owner. In addition, we identify and examine real-world cases related to bystander privacy, demonstrating how current deployments can impact non-users. Based on our findings, we analyze vendor privacy policies in light of existing legal frameworks and technical capabilities, and we provide practical recommendations for both policy language and system design to enhance transparency and empower both bystanders and device owners.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.26841v1">Accurate Target Privacy Preserving Federated Learning Balancing Fairness and Utility</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-10-30T07:14:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kangkang Sun, Jun Wu, Minyi Guo, Jianhua Li, Jianwei Huang</p>
    <p><b>Summary:</b> Federated Learning (FL) enables collaborative model training without data sharing, yet participants face a fundamental challenge, e.g., simultaneously ensuring fairness across demographic groups while protecting sensitive client data. We introduce a differentially private fair FL algorithm (\textit{FedPF}) that transforms this multi-objective optimization into a zero-sum game where fairness and privacy constraints compete against model utility. Our theoretical analysis reveals a surprising inverse relationship, i.e., stricter privacy protection fundamentally limits the system's ability to detect and correct demographic biases, creating an inherent tension between privacy and fairness. Counterintuitively, we prove that moderate fairness constraints initially improve model generalization before causing performance degradation, where a non-monotonic relationship that challenges conventional wisdom about fairness-utility tradeoffs. Experimental validation demonstrates up to 42.9 % discrimination reduction across three datasets while maintaining competitive accuracy, but more importantly, reveals that the privacy-fairness tension is unavoidable, i.e., achieving both objectives simultaneously requires carefully balanced compromises rather than optimization of either in isolation. The source code for our proposed algorithm is publicly accessible at https://github.com/szpsunkk/FedPF.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.26148v1">STAR: A Privacy-Preserving, Energy-Efficient Edge AI Framework for Human Activity Recognition via Wi-Fi CSI in Mobile and Pervasive Computing Environments</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-10-30T05:08:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kexing Liu</p>
    <p><b>Summary:</b> Human Activity Recognition (HAR) via Wi-Fi Channel State Information (CSI) presents a privacy-preserving, contactless sensing approach suitable for smart homes, healthcare monitoring, and mobile IoT systems. However, existing methods often encounter computational inefficiency, high latency, and limited feasibility within resource-constrained, embedded mobile edge environments. This paper proposes STAR (Sensing Technology for Activity Recognition), an edge-AI-optimized framework that integrates a lightweight neural architecture, adaptive signal processing, and hardware-aware co-optimization to enable real-time, energy-efficient HAR on low-power embedded devices. STAR incorporates a streamlined Gated Recurrent Unit (GRU)-based recurrent neural network, reducing model parameters by 33% compared to conventional LSTM models while maintaining effective temporal modeling capability. A multi-stage pre-processing pipeline combining median filtering, 8th-order Butterworth low-pass filtering, and Empirical Mode Decomposition (EMD) is employed to denoise CSI amplitude data and extract spatial-temporal features. For on-device deployment, STAR is implemented on a Rockchip RV1126 processor equipped with an embedded Neural Processing Unit (NPU), interfaced with an ESP32-S3-based CSI acquisition module. Experimental results demonstrate a mean recognition accuracy of 93.52% across seven activity classes and 99.11% for human presence detection, utilizing a compact 97.6k-parameter model. INT8 quantized inference achieves a processing speed of 33 MHz with just 8% CPU utilization, delivering sixfold speed improvements over CPU-based execution. With sub-second response latency and low power consumption, the system ensures real-time, privacy-preserving HAR, offering a practical, scalable solution for mobile and pervasive computing environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.26102v1">PEEL: A Poisoning-Exposing Encoding Theoretical Framework for Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-30T03:29:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lisha Shuai, Jiuling Dong, Nan Zhang, Shaofeng Tan, Haokun Zhang, Zilong Song, Gaoya Dong, Xiaolong Yang</p>
    <p><b>Summary:</b> Local Differential Privacy (LDP) is a widely adopted privacy-protection model in the Internet of Things (IoT) due to its lightweight, decentralized, and scalable nature. However, it is vulnerable to poisoning attacks, and existing defenses either incur prohibitive resource overheads or rely on domain-specific prior knowledge, limiting their practical deployment. To address these limitations, we propose PEEL, a Poisoning-Exposing Encoding theoretical framework for LDP, which departs from resource- or prior-dependent countermeasures and instead leverages the inherent structural consistency of LDP-perturbed data. As a non-intrusive post-processing module, PEEL amplifies stealthy poisoning effects by re-encoding LDP-perturbed data via sparsification, normalization, and low-rank projection, thereby revealing both output and rule poisoning attacks through structural inconsistencies in the reconstructed space. Theoretical analysis proves that PEEL, integrated with LDP, retains unbiasedness and statistical accuracy, while being robust to expose both output and rule poisoning attacks. Moreover, evaluation results show that LDP-integrated PEEL not only outperforms four state-of-the-art defenses in terms of poisoning exposure accuracy but also significantly reduces client-side computational costs, making it highly suitable for large-scale IoT deployments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.25932v2">FakeZero: Real-Time, Privacy-Preserving Misinformation Detection for Facebook and X</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-10-29T20:11:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Soufiane Essahli, Oussama Sarsar, Ahmed Bentajer, Anas Motii, Imane Fouad</p>
    <p><b>Summary:</b> Social platforms distribute information at unprecedented speed, which in turn accelerates the spread of misinformation and threatens public discourse. We present FakeZero, a fully client-side, cross-platform browser extension that flags unreliable posts on Facebook and X (formerly Twitter) while the user scrolls. All computation, DOM scraping, tokenization, Transformer inference, and UI rendering run locally through the Chromium messaging API, so no personal data leaves the device. FakeZero employs a three-stage training curriculum: baseline fine-tuning and domain-adaptive training enhanced with focal loss, adversarial augmentation, and post-training quantization. Evaluated on a dataset of 239,000 posts, the DistilBERT-Quant model (67.6 MB) reaches 97.1% macro-F1, 97.4% accuracy, and an AUROC of 0.996, with a median latency of approximately 103 ms on a commodity laptop. A memory-efficient TinyBERT-Quant variant retains 95.7% macro-F1 and 96.1% accuracy while shrinking the model to 14.7 MB and lowering latency to approximately 40 ms, showing that high-quality fake-news detection is feasible under tight resource budgets with only modest performance loss. By providing inline credibility cues, the extension can serve as a valuable tool for policymakers seeking to curb the spread of misinformation across social networks. With user consent, FakeZero also opens the door for researchers to collect large-scale datasets of fake news in the wild, enabling deeper analysis and the development of more robust detection techniques.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.25670v1">Spectral Perturbation Bounds for Low-Rank Approximation with Applications to Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Numerical Analysis-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Spectral Theory-D91E36">
  <p><b>Published on:</b> 2025-10-29T16:36:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Phuc Tran, Nisheeth K. Vishnoi, Van H. Vu</p>
    <p><b>Summary:</b> A central challenge in machine learning is to understand how noise or measurement errors affect low-rank approximations, particularly in the spectral norm. This question is especially important in differentially private low-rank approximation, where one aims to preserve the top-$p$ structure of a data-derived matrix while ensuring privacy. Prior work often analyzes Frobenius norm error or changes in reconstruction quality, but these metrics can over- or under-estimate true subspace distortion. The spectral norm, by contrast, captures worst-case directional error and provides the strongest utility guarantees. We establish new high-probability spectral-norm perturbation bounds for symmetric matrices that refine the classical Eckart--Young--Mirsky theorem and explicitly capture interactions between a matrix $A \in \mathbb{R}^{n \times n}$ and an arbitrary symmetric perturbation $E$. Under mild eigengap and norm conditions, our bounds yield sharp estimates for $\|(A + E)_p - A_p\|$, where $A_p$ is the best rank-$p$ approximation of $A$, with improvements of up to a factor of $\sqrt{n}$. As an application, we derive improved utility guarantees for differentially private PCA, resolving an open problem in the literature. Our analysis relies on a novel contour bootstrapping method from complex analysis and extends it to a broad class of spectral functionals, including polynomials and matrix exponentials. Empirical results on real-world datasets confirm that our bounds closely track the actual spectral error under diverse perturbation regimes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.25477v1">A Study on Privacy-Preserving Scholarship Evaluation Based on Decentralized Identity and Zero-Knowledge Proofs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-29T12:56:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yi Chen, Bin Chen, Peichang Zhang, Da Che</p>
    <p><b>Summary:</b> Traditional centralized scholarship evaluation processes typically require students to submit detailed academic records and qualification information, which exposes them to risks of data leakage and misuse, making it difficult to simultaneously ensure privacy protection and transparent auditability. To address these challenges, this paper proposes a scholarship evaluation system based on Decentralized Identity (DID) and Zero-Knowledge Proofs (ZKP). The system aggregates multidimensional ZKPs off-chain, and smart contracts verify compliance with evaluation criteria without revealing raw scores or computational details. Experimental results demonstrate that the proposed solution not only automates the evaluation efficiently but also maximally preserves student privacy and data integrity, offering a practical and trustworthy technical paradigm for higher education scholarship programs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.25277v1">A Privacy-Preserving Ecosystem for Developing Machine Learning Algorithms Using Patient Data: Insights from the TUM.ai Makeathon</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-10-29T08:37:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Simon Süwer, Mai Khanh Mai, Christoph Klein, Nicola Götzenberger, Denis Dalić, Andreas Maier, Jan Baumbach</p>
    <p><b>Summary:</b> The integration of clinical data offers significant potential for the development of personalized medicine. However, its use is severely restricted by the General Data Protection Regulation (GDPR), especially for small cohorts with rare diseases. High-quality, structured data is essential for the development of predictive medical AI. In this case study, we propose a novel, multi-stage approach to secure AI training: (1) The model is designed on a simulated clinical knowledge graph (cKG). This graph is used exclusively to represent the structural characteristics of the real cKG without revealing any sensitive content. (2) The model is then integrated into the FeatureCloud (FC) federated learning framework, where it is prepared in a single-client configuration within a protected execution environment. (3) Training then takes place within the hospital environment on the real cKG, either under the direct supervision of hospital staff or via a fully automated pipeline controlled by the hospital. (4) Finally, verified evaluation scripts are executed, which only return aggregated performance metrics. This enables immediate performance feedback without sensitive patient data or individual predictions, leaving the clinic. A fundamental element of this approach involves the incorporation of a cKG, which serves to organize multi-omics and patient data within the context of real-world hospital environments. This approach was successfully validated during the TUM.ai Makeathon 2024 (TUMaiM24) challenge set by the Dr. von Hauner Children's Hospital (HCH-LMU): 50 students developed models for patient classification and diagnosis without access to real data. Deploying secure algorithms via federated frameworks, such as the FC framework, could be a practical way of achieving privacy-preserving AI in healthcare.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.24498v1">Design and Optimization of Cloud Native Homomorphic Encryption Workflows for Privacy-Preserving ML Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-10-28T15:13:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tejaswini Bollikonda</p>
    <p><b>Summary:</b> As machine learning (ML) models become increasingly deployed through cloud infrastructures, the confidentiality of user data during inference poses a significant security challenge. Homomorphic Encryption (HE) has emerged as a compelling cryptographic technique that enables computation on encrypted data, allowing predictions to be generated without decrypting sensitive inputs. However, the integration of HE within large scale cloud native pipelines remains constrained by high computational overhead, orchestration complexity, and model compatibility issues.
  This paper presents a systematic framework for the design and optimization of cloud native homomorphic encryption workflows that support privacy-preserving ML inference. The proposed architecture integrates containerized HE modules with Kubernetes-based orchestration, enabling elastic scaling and parallel encrypted computation across distributed environments. Furthermore, optimization strategies including ciphertext packing, polynomial modulus adjustment, and operator fusion are employed to minimize latency and resource consumption while preserving cryptographic integrity. Experimental results demonstrate that the proposed system achieves up to 3.2times inference acceleration and 40% reduction in memory utilization compared to conventional HE pipelines. These findings illustrate a practical pathway for deploying secure ML-as-a-Service (MLaaS) systems that guarantee data confidentiality under zero-trust cloud conditions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.24233v1">PRIVET: Privacy Metric Based on Extreme Value Theory</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-10-28T09:42:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Antoine Szatkownik, Aurélien Decelle, Beatriz Seoane, Nicolas Bereux, Léo Planche, Guillaume Charpiat, Burak Yelmen, Flora Jay, Cyril Furtlehner</p>
    <p><b>Summary:</b> Deep generative models are often trained on sensitive data, such as genetic sequences, health data, or more broadly, any copyrighted, licensed or protected content. This raises critical concerns around privacy-preserving synthetic data, and more specifically around privacy leakage, an issue closely tied to overfitting. Existing methods almost exclusively rely on global criteria to estimate the risk of privacy failure associated to a model, offering only quantitative non interpretable insights. The absence of rigorous evaluation methods for data privacy at the sample-level may hinder the practical deployment of synthetic data in real-world applications. Using extreme value statistics on nearest-neighbor distances, we propose PRIVET, a generic sample-based, modality-agnostic algorithm that assigns an individual privacy leak score to each synthetic sample. We empirically demonstrate that PRIVET reliably detects instances of memorization and privacy leakage across diverse data modalities, including settings with very high dimensionality, limited sample sizes such as genetic data and even under underfitting regimes. We compare our method to existing approaches under controlled settings and show its advantage in providing both dataset level and sample level assessments through qualitative and quantitative outputs. Additionally, our analysis reveals limitations in existing computer vision embeddings to yield perceptually meaningful distances when identifying near-duplicate samples.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.24072v1">Covert Surveillance in Smart Devices: A SCOUR Framework Analysis of Youth Privacy Implications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-10-28T05:10:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Austin Shouli, Yulia Bobkova, Ajay Kumar Shrestha</p>
    <p><b>Summary:</b> This paper investigates how smart devices covertly capture private conversations and discusses in more in-depth the implications of this for youth privacy. Using a structured review guided by the PRISMA methodology, the analysis focuses on privacy concerns, data capture methods, data storage and sharing practices, and proposed technical mitigations. To structure and synthesize findings, we introduce the SCOUR framework, encompassing Surveillance mechanisms, Consent and awareness, Operational data flow, Usage and exploitation, and Regulatory and technical safeguards. Findings reveal that smart devices have been covertly capturing personal data, especially with smart toys and voice-activated smart gadgets built for youth. These issues are worsened by unclear data collection practices and insufficient transparency in smart device applications. Balancing privacy and utility in smart devices is crucial, as youth are becoming more aware of privacy breaches and value their personal data more. Strategies to improve regulatory and technical safeguards are also provided. The review identifies research gaps and suggests future directions. The limitations of this literature review are also explained. The findings have significant implications for policy development and the transparency of data collection for smart devices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.24807v1">Learning to Attack: Uncovering Privacy Risks in Sequential Data Releases</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-10-28T04:32:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ziyao Cui, Minxing Zhang, Jian Pei</p>
    <p><b>Summary:</b> Privacy concerns have become increasingly critical in modern AI and data science applications, where sensitive information is collected, analyzed, and shared across diverse domains such as healthcare, finance, and mobility. While prior research has focused on protecting privacy in a single data release, many real-world systems operate under sequential or continuous data publishing, where the same or related data are released over time. Such sequential disclosures introduce new vulnerabilities, as temporal correlations across releases may enable adversaries to infer sensitive information that remains hidden in any individual release. In this paper, we investigate whether an attacker can compromise privacy in sequential data releases by exploiting dependencies between consecutive publications, even when each individual release satisfies standard privacy guarantees. To this end, we propose a novel attack model that captures these sequential dependencies by integrating a Hidden Markov Model with a reinforcement learning-based bi-directional inference mechanism. This enables the attacker to leverage both earlier and later observations in the sequence to infer private information. We instantiate our framework in the context of trajectory data, demonstrating how an adversary can recover sensitive locations from sequential mobility datasets. Extensive experiments on Geolife, Porto Taxi, and SynMob datasets show that our model consistently outperforms baseline approaches that treat each release independently. The results reveal a fundamental privacy risk inherent to sequential data publishing, where individually protected releases can collectively leak sensitive information when analyzed temporally. These findings underscore the need for new privacy-preserving frameworks that explicitly model temporal dependencies, such as time-aware differential privacy or sequential data obfuscation strategies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.23931v1">Differential Privacy: Gradient Leakage Attacks in Federated Learning Environments</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-10-27T23:33:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Miguel Fernandez-de-Retana, Unai Zulaika, Rubén Sánchez-Corcuera, Aitor Almeida</p>
    <p><b>Summary:</b> Federated Learning (FL) allows for the training of Machine Learning models in a collaborative manner without the need to share sensitive data. However, it remains vulnerable to Gradient Leakage Attacks (GLAs), which can reveal private information from the shared model updates. In this work, we investigate the effectiveness of Differential Privacy (DP) mechanisms - specifically, DP-SGD and a variant based on explicit regularization (PDP-SGD) - as defenses against GLAs. To this end, we evaluate the performance of several computer vision models trained under varying privacy levels on a simple classification task, and then analyze the quality of private data reconstructions obtained from the intercepted gradients in a simulated FL environment. Our results demonstrate that DP-SGD significantly mitigates the risk of gradient leakage attacks, albeit with a moderate trade-off in model utility. In contrast, PDP-SGD maintains strong classification performance but proves ineffective as a practical defense against reconstruction attacks. These findings highlight the importance of empirically evaluating privacy mechanisms beyond their theoretical guarantees, particularly in distributed learning scenarios where information leakage may represent an unassumable critical threat to data security and privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.23463v2">Differential Privacy as a Perk: Federated Learning over Multiple-Access Fading Channels with a Multi-Antenna Base Station</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2025-10-27T16:01:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hao Liang, Haifeng Wen, Kaishun Wu, Hong Xing</p>
    <p><b>Summary:</b> Federated Learning (FL) is a distributed learning paradigm that preserves privacy by eliminating the need to exchange raw data during training. In its prototypical edge instantiation with underlying wireless transmissions enabled by analog over-the-air computing (AirComp), referred to as \emph{over-the-air FL (AirFL)}, the inherent channel noise plays a unique role of \emph{frenemy} in the sense that it degrades training due to noisy global aggregation while providing a natural source of randomness for privacy-preserving mechanisms, formally quantified by \emph{differential privacy (DP)}. It remains, nevertheless, challenging to effectively harness such channel impairments, as prior arts, under assumptions of either simple channel models or restricted types of loss functions, mostly considering (local) DP enhancement with a single-round or non-convergent bound on privacy loss. In this paper, we study AirFL over multiple-access fading channels with a multi-antenna base station (BS) subject to user-level DP requirements. Despite a recent study, which claimed in similar settings that artificial noise (AN) must be injected to ensure DP in general, we demonstrate, on the contrary, that DP can be gained as a \emph{perk} even \emph{without} employing any AN. Specifically, we derive a novel bound on DP that converges under general bounded-domain assumptions on model parameters, along with a convergence bound with general smooth and non-convex loss functions. Next, we optimize over receive beamforming and power allocations to characterize the optimal convergence-privacy trade-offs, which also reveal explicit conditions in which DP is achievable without compromising training. Finally, our theoretical findings are validated by extensive numerical results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.23427v1">PrivacyGuard: A Modular Framework for Privacy Auditing in Machine Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-10-27T15:33:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Luca Melis, Matthew Grange, Iden Kalemaj, Karan Chadha, Shengyuan Hu, Elena Kashtelyan, Will Bullock</p>
    <p><b>Summary:</b> The increasing deployment of Machine Learning (ML) models in sensitive domains motivates the need for robust, practical privacy assessment tools. PrivacyGuard is a comprehensive tool for empirical differential privacy (DP) analysis, designed to evaluate privacy risks in ML models through state-of-the-art inference attacks and advanced privacy measurement techniques. To this end, PrivacyGuard implements a diverse suite of privacy attack -- including membership inference , extraction, and reconstruction attacks -- enabling both off-the-shelf and highly configurable privacy analyses. Its modular architecture allows for the seamless integration of new attacks, and privacy metrics, supporting rapid adaptation to emerging research advances. We make PrivacyGuard available at https://github.com/facebookresearch/PrivacyGuard.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.23274v1">Privacy-Preserving Semantic Communication over Wiretap Channels with Learnable Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2025-10-27T12:34:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Weixuan Chen, Qianqian Yang, Shuo Shao, Shunpu Tang, Zhiguo Shi, Shui Yu</p>
    <p><b>Summary:</b> While semantic communication (SemCom) improves transmission efficiency by focusing on task-relevant information, it also raises critical privacy concerns. Many existing secure SemCom approaches rely on restrictive or impractical assumptions, such as favorable channel conditions for the legitimate user or prior knowledge of the eavesdropper's model. To address these limitations, this paper proposes a novel secure SemCom framework for image transmission over wiretap channels, leveraging differential privacy (DP) to provide approximate privacy guarantees. Specifically, our approach first extracts disentangled semantic representations from source images using generative adversarial network (GAN) inversion method, and then selectively perturbs private semantic representations with approximate DP noise. Distinct from conventional DP-based protection methods, we introduce DP noise with learnable pattern, instead of traditional white Gaussian or Laplace noise, achieved through adversarial training of neural networks (NNs). This design mitigates the inherent non-invertibility of DP while effectively protecting private information. Moreover, it enables explicitly controllable security levels by adjusting the privacy budget according to specific security requirements, which is not achieved in most existing secure SemCom approaches. Experimental results demonstrate that, compared with the previous DP-based method and direct transmission, the proposed method significantly degrades the reconstruction quality for the eavesdropper, while introducing only slight degradation in task performance. Under comparable security levels, our approach achieves an LPIPS advantage of 0.06-0.29 and an FPPSR advantage of 0.10-0.86 for the legitimate user compared with the previous DP-based method.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.23024v1">A Multi-Store Privacy Measurement of Virtual Reality App Ecosystem</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-10-27T05:42:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chuan Yan, Zeng Li, Kunlin Cai, Liuhuo Wan, Ruomai Ren, Yiran Shen, Guangdong Bai</p>
    <p><b>Summary:</b> Virtual Reality (VR) has gained increasing traction among various domains in recent years, with major companies such as Meta, Pico, and Microsoft launching their application stores to support third-party developers in releasing their applications (or simply apps). These apps offer rich functionality but inherently collect privacy-sensitive data, such as user biometrics, behaviors, and the surrounding environment. Nevertheless, there is still a lack of domain-specific regulations to govern the data handling of VR apps, resulting in significant variations in their privacy practices among app stores.
  In this work, we present the first comprehensive multi-store study of privacy practices in the current VR app ecosystem, covering a large-scale dataset involving 6,565 apps collected from five major app stores. We assess both declarative and behavioral privacy practices of VR apps, using a multi-faceted approach based on natural language processing, reverse engineering, and static analysis. Our assessment reveals significant privacy compliance issues across all stores, underscoring the premature status of privacy protection in this rapidly growing ecosystem. For instance, one third of apps fail to declare their use of sensitive data, and 21.5\% of apps neglect to provide valid privacy policies. Our work sheds light on the status quo of privacy protection within the VR app ecosystem for the first time. Our findings should raise an alert to VR app developers and users, and encourage store operators to implement stringent regulations on privacy compliance among VR apps.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.22387v1">Privacy-Aware Federated nnU-Net for ECG Page Digitization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-10-25T18:10:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nader Nemati</p>
    <p><b>Summary:</b> Deep neural networks can convert ECG page images into analyzable waveforms, yet centralized training often conflicts with cross-institutional privacy and deployment constraints. A cross-silo federated digitization framework is presented that trains a full-model nnU-Net segmentation backbone without sharing images and aggregates updates across sites under realistic non-IID heterogeneity (layout, grid style, scanner profile, noise).
  The protocol integrates three standard server-side aggregators--FedAvg, FedProx, and FedAdam--and couples secure aggregation with central, user-level differential privacy to align utility with formal guarantees. Key features include: (i) end-to-end full-model training and synchronization across clients; (ii) secure aggregation so the server only observes a clipped, weighted sum once a participation threshold is met; (iii) central Gaussian DP with Renyi accounting applied post-aggregation for auditable user-level privacy; and (iv) a calibration-aware digitization pipeline comprising page normalization, trace segmentation, grid-leakage suppression, and vectorization to twelve-lead signals.
  Experiments on ECG pages rendered from PTB-XL show consistently faster convergence and higher late-round plateaus with adaptive server updates (FedAdam) relative to FedAvg and FedProx, while approaching centralized performance. The privacy mechanism maintains competitive accuracy while preventing exposure of raw images or per-client updates, yielding deployable, auditable guarantees suitable for multi-institution settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.21946v1">$δ$-STEAL: LLM Stealing Attack with Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-10-24T18:19:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kieu Dang, Phung Lai, NhatHai Phan, Yelong Shen, Ruoming Jin, Abdallah Khreishah</p>
    <p><b>Summary:</b> Large language models (LLMs) demonstrate remarkable capabilities across various tasks. However, their deployment introduces significant risks related to intellectual property. In this context, we focus on model stealing attacks, where adversaries replicate the behaviors of these models to steal services. These attacks are highly relevant to proprietary LLMs and pose serious threats to revenue and financial stability. To mitigate these risks, the watermarking solution embeds imperceptible patterns in LLM outputs, enabling model traceability and intellectual property verification. In this paper, we study the vulnerability of LLM service providers by introducing $δ$-STEAL, a novel model stealing attack that bypasses the service provider's watermark detectors while preserving the adversary's model utility. $δ$-STEAL injects noise into the token embeddings of the adversary's model during fine-tuning in a way that satisfies local differential privacy (LDP) guarantees. The adversary queries the service provider's model to collect outputs and form input-output training pairs. By applying LDP-preserving noise to these pairs, $δ$-STEAL obfuscates watermark signals, making it difficult for the service provider to determine whether its outputs were used, thereby preventing claims of model theft. Our experiments show that $δ$-STEAL with lightweight modifications achieves attack success rates of up to $96.95\%$ without significantly compromising the adversary's model utility. The noise scale in LDP controls the trade-off between attack effectiveness and model utility. This poses a significant risk, as even robust watermarks can be bypassed, allowing adversaries to deceive watermark detectors and undermine current intellectual property protection methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2510.21668v1">Privacy Guarantee for Nash Equilibrium Computation of Aggregative Games Based on Pointwise Maximal Leakage</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2025-10-24T17:24:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhaoyang Cheng, Guanpu Chen, Tobias J. Oechtering, Mikael Skoglund</p>
    <p><b>Summary:</b> Privacy preservation has served as a key metric in designing Nash equilibrium (NE) computation algorithms. Although differential privacy (DP) has been widely employed for privacy guarantees, it does not exploit prior distributional knowledge of datasets and is ineffective in assessing information leakage for correlated datasets. To address these concerns, we establish a pointwise maximal leakage (PML) framework when computing NE in aggregative games. By incorporating prior knowledge of players' cost function datasets, we obtain a precise and computable upper bound of privacy leakage with PML guarantees. In the entire view, we show PML refines DP by offering a tighter privacy guarantee, enabling flexibility in designing NE computation. Also, in the individual view, we reveal that the lower bound of PML can exceed the upper bound of DP by constructing specific correlated datasets. The results emphasize that PML is a more proper privacy measure than DP since the latter fails to adequately capture privacy leakage in correlated datasets. Moreover, we conduct experiments with adversaries who attempt to infer players' private information to illustrate the effectiveness of our framework.</p>
  </details>
</div>

