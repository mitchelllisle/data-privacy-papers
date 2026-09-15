
<h2>2026-09</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.15950v1">Privacy-Aligned Personalized Federated Learning with Compact Adaptation and Variable-Length Gaussian Communication</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-14T17:48:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yilin Xu, Chun Hei Michael Shiu, Chih Wei Ling, Linqi Song</p>
    <p><b>Summary:</b> Record-level differential privacy exposes a structural misalignment in personalized federated learning when client-specific variation is low-dimensional while training repeatedly releases high-dimensional updates. In this paper, we address this misalignment by releasing a private client context once and confining repeated adaptation to a fixed coefficient space. Beyond dimensionality reduction, the factorized generator induces an adaptive optimization geometry that reshapes noisy updates, and controlled ablations show that most of its private-training gain is retained by radial evolution. To further reduce the communication cost, we realize the Gaussian mechanism for coefficient updates directly through variable-length quantization with finite expected code length, so that the quantization error itself serves as the required privacy perturbation rather than extra distortion. Across MNIST and CIFAR-10, our design matches or outperforms full-model private adaptation across privacy budgets and client heterogeneity, while reducing protected uplink by a factor of 2.67 at \(\varepsilon=16\) on CIFAR-10 with comparable future-client accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.15885v1">Privacy-enhanced federated learning via asynchronous aggregation and local differential perturbation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computational Engineering, Finance, and Science-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2026-09-14T17:12:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhen Zhong, Shini Yang, Liesheng Wei</p>
    <p><b>Summary:</b> This study proposes a privacy-enhanced federated learning framework to address secure collaborative training in distributed data environments. The framework integrates Dynamic Differential Privacy (DDP), lightweight Homomorphic Encryption (HE), and Local Differential Privacy (LDP) mechanisms to ensure data privacy protection during model training. Additionally, the framework employs an asynchronous aggregation strategy with version control to support distributed training in asynchronous environments. Experimental validation on the CIFAR-10 and Purchase-100 benchmark datasets demonstrates that the method maintains high classification accuracy (up to 82.6%) even under stringent privacy constraints (ε = 0.1), while reducing communication overhead by 21.3% compared to FedAvg. Experimental results demonstrate that this framework effectively balances privacy protection and model performance in distributed machine learning scenarios, providing a scalable technical foundation for large-scale distributed collaborative computing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.15875v1">Private Information Retrieval With Arbitrary Privacy Requirements: Introduction and Capacity Results</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762"> 
  <p><b>Published on:</b> 2026-09-14T17:03:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohamed Nomeir, Shreya Meel, Sennur Ulukus</p>
    <p><b>Summary:</b> In this paper, we introduce the problem of private information retrieval (PIR) under arbitrary privacy requirements, in a graph-based storage system. This formulation is motivated by the server storage limitations, abundance of data (messages) and heterogeneous data privacy requirements. Under the arbitrary privacy requirement, each message has to be retrieved privately from a pre-specified subset of servers, where the subset always includes the servers storing it. Thus, each server is associated with a privacy set, which pre-specifies the message indices that should be privately retrieved from it. This setting is a generalization of the classical PIR setting, where the required message index needs to be kept private from all servers, i.e., there, the privacy set of each server comprises all message indices. Our setting is also a bridge between the newly formulated local PIR (LPIR) setting and the classical PIR setting, where in the former, the privacy set is exactly the set of stored message indices. In this paper, we derive general lower and upper bounds on the PIR capacity for general graphs, under certain privacy requirements, that capture the essence of both LPIR and classical PIR. Then, we focus on path and cyclic storage graphs under these and more fine-grained settings, for which we derive capacity results for certain cases, and establish lower and upper bounds for others. Their low degree allows for a more in-depth understanding of the new privacy formulation and admits more privacy requirement settings compared to other simple graphs. Finally, we introduce a new graph structure, the pyramid storage graph, to model server storage. Although this graph has never been investigated in the literature in any PIR context, it enjoys a nice symmetric structure for message storage and replication patterns.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.15871v1">LLM-Based Schema-Aware Split Learning for Privacy-Preserving Mental Distress Prediction Across Heterogeneous Surveys</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-14T16:59:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Md Khalid Syfullah, Alvi Ataur Khalil</p>
    <p><b>Summary:</b> Rising societal and lifestyle complexity has been linked to a growing prevalence of mental distress worldwide. Educational institutions, workplaces, clinics, etc. collect large volumes of mental health survey data to understand and reduce this burden. Collaborative analysis of such data could yield effective generalizable predictive models. Privacy constraints and varied survey designs (i.e., different questions, scales, and formats) hinder direct integration. We propose a schema-aware split learning (SL) framework that preserves privacy, using a large language model (LLM) as a shared semantic encoder to harmonize heterogeneous survey schemas across institutions. We serialize each survey record into a natural-language description, unifying disparate survey schemas into a common format. The LLM is fine-tuned for mental distress assessment via Low-Rank Adaptation (LoRA) and partitioned across client and server. Clients retain the raw survey responses locally and run only a lightweight front-end, so original records never leave the institution that collected them. The resource-intensive backbone runs on the server, minimizing client-side computation. Using LLaMA-3.2-3B-Instruct, the framework attains an average ANLS of 0.708 with only 2,000 training samples, surpasses federated learning (FL) in eight of nine settings, and cuts per-client computation by three orders of magnitude, while generalizing to unseen datasets. Overall, it enables accurate, privacy-preserving, and resource-efficient collaborative learning from heterogeneous mental health survey data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.15671v1">Don't Send What You Don't Need: Question-Guided Token Pruning as a Privacy Defense for Vision-Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-14T14:48:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Md Khalid Syfullah, Alvi Ataur Khalil</p>
    <p><b>Summary:</b> Visual Question Answering (VQA) with Vision-Language Models (VLMs) is increasingly used in privacy-sensitive and bandwidth-constrained settings. Federated Learning (FL), Split Learning (SL), and U-Shaped Split Learning (USL) keep raw data local, but transmitting all visual tokens across a model partition remains costly and can expose private information. We propose QPriv-VL, a question-guided, privacy-aware token-pruning framework for FL, SL, and USL that prunes visual tokens before transmission based on task utility and privacy sensitivity. Its core component is a lightweight Dynamic Threshold Predictor (DTP) that jointly estimates a sample-specific pruning ratio and a token-level retention mask in one forward pass. DTP combines question relevance, computed from cross-modal similarity between visual patches and the pooled question embedding, with a sensitivity signal derived from frozen DINOv2 features. This allows the model to suppress potentially sensitive regions while preserving patches useful for answering the question, without requiring sensitivity labels. We evaluate QPriv-VL on GQA, OK-VQA, VQAv2, SLAKE, VQA-RAD, and PathVQA against four privacy attack families: FSHA, FORA, iDLG, and attribute-inference membership inference attacks. DTP matches or outperforms fixed-ratio pruning while using substantially fewer transmitted tokens. On VQA-RAD, it reduces membership-inference attack success from 0.99 to 0.76-0.79, lowers FSHA and FORA reconstruction PSNR relative to fixed-ratio pruning, and preserves competitive VQA accuracy using about 40% of the original visual-token budget. A sensitivity exclusion ratio of 1.20 +/- 0.18 indicates preferential removal of privacy-sensitive patches, while explainability analysis shows that retention adapts to question semantics rather than generic visual saliency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.14778v1">Privacy Preserving Gossip Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E">
  <p><b>Published on:</b> 2026-09-13T20:37:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Erkan Bayram, Mohamed-Ali Belabbas, Tamer Başar</p>
    <p><b>Summary:</b> We propose a decentralized privacy-preserving learning algorithm in which each agent holds a single private sample and a shared model. Samples are learned sequentially, and each update must preserve the endpoint mappings at previously learned samples while protecting private data. This gives each agent three roles: (i) a learner that updates the model parameters, (ii) a teacher whose sample is learned at the current iteration, and (iii) a protected agent whose sample has already been learned. We build on Tuning without Forgetting (TwF) method to preserve previously learned mappings and show that TwF provides an indistinguishability guarantee for the learner whenever the set of protected agents contains another sample with the same label. For the teacher, we formulate a minimax optimal control problem that models the differential privacy noise as a worst-case disturbance to prevent performance loss while maintaining the same level of privacy for the gradient. For the protected agents, we compute the projections locally and aggregate them using a private push-sum gossip protocol. We prove geometric convergence of the decentralized gossip algorithm and of the distributed projection for TwF.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.14745v1">PIMENTO: A Privacy Framework for Querying Text</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-13T19:17:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mushtari Sadia, Ang Chen, Amrita Roy Chowdhury</p>
    <p><b>Summary:</b> Currently, there are two state-of-the-art, complementary privacy guarantees: contextual integrity (CI) for what may flow, and differential privacy (DP) for what may be inferred. Yet neither maps cleanly onto natural language, leaving existing approaches unable to provide these guarantees for analytics over unstructured text. We address this gap with Pimento, a framework that takes three forms of natural language: text corpus, queries, and privacy policies; and grounds them into a relational database, creating a common substrate on which both guarantees can be enforced formally. With this design, we not only provide end to end privacy guarantees, but also improvement to utility through three key contributions: DP aware Text-to-SQL, which searches for correct queries requiring the least DP noise; CI aware Text-to-SQL, which compiles natural language policies into executable CI rules over the database; and a new privacy definition we call contextual differential privacy, which redefines the traditional DP neighborhood under CI, and yields a tighter smooth sensitivity bound. Across new benchmarks, Pimento selects the best query in 75.3% of cases (upto +45 points over baselines) and achieves zero leakage under correct policy grounding. To our knowledge, Pimento is the first framework to provide formal privacy guarantees for natural language analytics under CI, DP, and their composition.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.14697v1">Vulnerabilities in Personalization: Assessing Health Privacy Risks in ChatGPT Logs and Memory</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-09-13T17:53:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> S M Mehedi Zaman, Md Mozammel Hoque</p>
    <p><b>Summary:</b> As conversational LLMs become deeply embedded in daily life, users frequently disclose sensitive personal health information during routine interactions. We present a large-scale computational audit analyzing 179,057 conversations across India, Nigeria, Brazil, and Pakistan (N = 1,057) to evaluate personal health disclosures and background memory synthesis in ChatGPT. We find that 21.31% of audited conversations contain personal health data, with 3.62% posing high-to-extreme privacy risks involving stigmatized conditions, direct identifiers, and precise locations. When evaluating the memory entries of ChatGPT, we uncover a stark disconnect between corporate framing and system behavior: over 95% of profile entries are implicitly extracted without explicit user prompts or consent. Furthermore, background memory synthesis selectively condenses temporary, symptom-level disclosures into permanent diagnostic traits, stripping contextual integrity and amplifying re-identification risks. We conclude with sociotechnical design guidelines to restore user agency and consent-driven boundaries in stateful AI systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.14125v1">A Graph-Based Framework for Extending Metric Differential Privacy Mechanisms</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-12T20:09:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruiyao Liu, Chenxi Qiu</p>
    <p><b>Summary:</b> Metric differential privacy (mDP) is well suited to structured secret domains, but directly constructing utility-aware mechanisms over large or fine-grained domains is often computationally prohibitive. We study extension-based mDP design, where a mechanism is first specified on a finite set of seed records and then extended to a larger target domain. To our knowledge, this is the first work to systematically formulate extension as a general design paradigm for mDP rather than a method-specific construction. We present a graph-based extension framework, identify three requirements for correctness, local mDP constraints, overlap consistency, and successor-level mDP preservation, and show that, under these conditions, the induced global mechanism is well defined and satisfies $ε$-mDP on the target domain. We further instantiate the framework with a tree-based extension algorithm for multi-resolution grids, where multi-dimensional extension is realized through one-dimensional interpolation and dimension-wise composition. Experiments on road-map datasets demonstrate that our approach achieves a strong utility-scalability trade-off while preserving exact mDP guarantees.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.14003v1">Confuse the Model, Control the Flow: Understanding and Mitigating Privacy Leakage from LLM Agents with Information Flow Control</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-09-12T15:31:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Minsun Shim, Ramisha Raida Karim, Ruthwik Jakkula, Kaiwen Zhou, Xin Liu, Xin Eric Wang, Zhou Li</p>
    <p><b>Summary:</b> Personal AI agents built on large language models (LLMs) are increasingly given access to a user's private data and communications in order to provide personalized assistance. This access creates a persistent privacy risk: the agent must decide whether a given sensitive information should be disclosed to a particular party. Existing defenses address this by making the agent's backend LLM more privacy-preserving through stronger system prompts, training, or explicit consent-checking procedures, but this approach has a structural challenge: whenever enforcement is a judgment the LLM makes over the same conversational context an adversary controls, the enforcement mechanism and the attack surface coincide. We demonstrate this against existing defenses with three new attacks that require only ordinary agent interaction and no prompt injection: Collaborative Workspace Lure reframes an extraction attempt as collaborative work; Semantic Obfuscation Attack induces disclosure through omission rather than through anything the agent writes; and Channel Decoupling Attack splits the extraction request and the disclosure across independent channels. All three achieve substantially higher leak rates than the attacks these defenses were originally designed to withstand. Guided by this observation, we present FLOWSEAL, a defense that enforces confidentiality through a tool-level interceptor outside the LLM's context, grounded in data provenance and an information-flow-control lattice with controlled declassification. Evaluated across three benchmarks, five prompt-based baselines, and eight attacks, including a real agent executing live tool calls through MCP, FLOWSEAL reduces leak rates to near zero (e.g., 52.2% to 0.5% against Collaborative Workspace Lure) while preserving task utility, regardless of the underlying LLM backend.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.13873v1">PriMobiBench: Characterizing Visual Privacy Leakage in VLM-Driven Mobile GUI Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-12T10:55:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qihang Cen, Tianshuo Cong, Da Song, Xinlei He, Jiaxing Song, Ke Xu, Qi Li</p>
    <p><b>Summary:</b> Mobile GUI agents increasingly rely on Vision-Language Models (VLMs) to automate smartphone tasks by interpreting screenshot streams. However, this design introduces serious and underexplored privacy risks, including direct leakage of sensitive on-screen information and unintended user profiling. The absence of standardized benchmarks makes it difficult to quantify these risks in realistic mobile agent workflows. To address this gap, we propose PriMobiBench, the first benchmark for systematically evaluating privacy leakage and visual profiling in screenshot-driven mobile agents. It provides a unified pipeline for data generation, agent trajectory construction, and multi-model evaluation. We also introduce MobiLeak, a dataset of execution traces from 16 apps, covering 25 privacy attributes with 2,960 embedded privacy instances. Our results reveal substantial risks: (1) VLMs can directly extract sensitive information with up to 82.5% success rate; (2) beyond explicit leakage, they can infer user profiles from aggregated visual evidence with approximately 70% success. We further propose a mitigation that masks privacy-sensitive but task-irrelevant UI elements before cloud processing, reducing profiling success by up to 58% with only approximately 8% performance loss. Overall, our work provides the first systematic benchmark for visual privacy risks in mobile GUI agents, demonstrates that both leakage and profiling are feasible at a highly concerning level, and offers a practical direction for mitigation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.13823v1">Semantic Privacy Protection with Utility Preservation for 3D Point Clouds</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-09-12T09:15:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jinchang zhang, Jiakai Lin, David Crandall, Guoyu Lu</p>
    <p><b>Summary:</b> Point cloud data face serious semantic privacy risks during acquisition, transmission, and cross-institutional sharing. Existing methods mostly rely on geometric perturbation or destructive encryption, which can reduce the recognizability of the original class but often impair downstream usability. This paper proposes a class-transfer-based semantic encryption framework for point clouds, aiming to conceal original class information while preserving task utility and supporting authorized recovery. Specifically, we construct a unified latent space with a shared-backbone Normalizing Flow, and combine LoRA and FiLM to achieve parameter-efficient class-conditional adaptation. We further introduce diffusion-guided flow alignment to regularize the latent distribution, construct an energy-based category transition graph, and obtain an optimal class-transfer table through global matching. Then, a latent-space Neural ODE continuously evolves source-class latents into target-class latents, which are decoded into target-class point clouds through the inverse flow. We adopt attacker-oriented metrics, including New-Class Recognition Rate (NCRR), Original-Class Leakage Rate (OCLR), and Original Label Recovery Rate (OLRR), to evaluate privacy and utility. Experiments on classification and segmentation benchmarks show that the proposed method achieves controllable semantic transformation, effectively reduces original-class semantic leakage, preserves downstream learnability in the protected domain, and supports reliable authorized reconstruction.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.13499v1">Canaries in the Bank: Auditing User-Level Privacy in Private Evolution</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-11T20:04:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sai Aparna Aketi, Enayat Ullah, Shripad Gade</p>
    <p><b>Summary:</b> Private Evolution (PE) generates high-fidelity synthetic data in federated settings without exposing users' raw data. It aggregates clipped user votes over a shared candidate bank into a differentially private histogram, with noise calibrated to the worst-case user contribution. However, it is unclear whether an adversary can realize this worst-case privacy loss while following the PE protocol. We introduce a protocol-aware empirical audit in which the server commits to a single shared candidate bank and replaces roughly 1% of its entries with probes derived from a known, non-private canary. We evaluate eight attacks, including an unchanged-bank baseline, exact copies, plausible paraphrases, and high-entropy synthetic nonces. Experiments on Yelp and Sentiment140 show that natural-text attacks remain substantially below the theoretical DP bound, while nonce-based attacks yield considerably stronger bounds and come closest to the mechanism's privacy ceiling. These results quantify the gap between formal worst-case privacy and leakage achievable through protocol-valid candidate-bank manipulation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.13418v1">High quantum local differential privacy breaks entanglement</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-09-11T18:29:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sujeet Bhalerao, Theshani Nuradha, Felix Leditzky</p>
    <p><b>Summary:</b> Differential privacy provides a mathematical framework for guaranteeing privacy for sensitive data. In quantum information processing, the interaction of privacy constraints with quantum resources such as entanglement remains a question of interest. Given that the utility of many protocols, and often the presence of a quantum advantage, relies on quantum resources such as entanglement, it is crucial to understand when a privacy requirement for a quantum channel is compatible with the channel's ability to preserve entanglement. We study this question for quantum local differential privacy (QLDP). Our main result shows that every $\varepsilon$-QLDP channel with a $d$-dimensional input is entanglement-breaking whenever $\varepsilon\leq\log\frac{d}{d-1}$. We also prove an approximate version for $(\varepsilon,δ)$-QLDP, where channels in the same high-privacy regime are close in diamond norm to an entanglement-breaking channel. We further prove a composition result for a collection of private quantum channels having entangled inputs and global measurements in the high-privacy regime. Finally, we apply our results to private quantum learning theory. We prove that any learning protocol using arbitrary quantum memory on copies of the output of an entanglement-breaking channel can be simulated by a protocol that measures the corresponding unprocessed input copies one at a time while storing only classical information. Combining this result with our high-privacy entanglement-breaking theorem, we show that under sufficiently private local noise, a learning protocol with quantum memory for purity testing and bipartite product testing is subject to the sample complexity lower bounds for protocols with single-copy measurements on the noiseless tasks. We also obtain stronger sample complexity lower bounds when a single highly private channel acts on the entire multipartite input.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.13393v1">Privacy-Preserving Deep Joint Source-Channel Coding with In-Loop Concept Erasure</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-11T18:02:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rami Eid, Maria Slim, Mariette Awad, Hadi Sarieddeen</p>
    <p><b>Summary:</b> Deep joint source-channel coding (DeepJSCC) transmits learned semantic features efficiently but can leak sensitive attributes such as gender, race, or speaker identity. We propose LEAPSC (LEACE-in-the-loop privacy for semantic communication), whose core contribution is the integration of in-loop least-squares concept erasure (LEACE) within a variational information bottleneck (VIB) encoder. By periodically refitting the projection operator during training, LEAPSC couples the encoder dynamics to the erasure mechanism, driving attribute-conditional mean differences toward zero within each task-label group on the fitting sample. Additional components, namely conditional value-at-risk (CVaR) tail-sensitive privacy, feature-wise linear modulation (FiLM) signal-to-noise ratio conditioning, and Lagrangian dual ascent, improve robustness across channel conditions and over the high-leakage tail of samples. On CelebA, FairFace, and Google Speech Commands, LEAPSC reaches task accuracy of 0.862, 0.755, and 0.925 respectively, with attacker accuracy at or below the label-only floor on CelebA (0.548 vs. floor 0.580) and within 2 percentage points (pp) of chance elsewhere, improving over an information-bottleneck adversarial baseline (IBAL) at a matched 52-epoch budget by +3.6, +2.5, and +1.3 pp (Welch's t-test, p=0.019 on CelebA).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.12571v1">PIA-Bench: Towards Automated Privacy Impact Assessment with Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-11T08:16:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiamin Zheng, Hao-Ping Lee, Luo Mai, Jingjie Li</p>
    <p><b>Summary:</b> Privacy impact assessment (PIA) is a critical instrument for institutions to proactively identify privacy risks and develop mitigation strategies before system deployment. While mandated across regulatory and institutional contexts, executing PIA requires extensive privacy and technical expertise, posing a particular challenge for teams without access to such resources. Prior work shows the potential of leveraging large language models (LLMs) to assist practitioners' privacy decisions, but little is known about how accurately and reliably LLMs can automate PIA. To this end, we develop PIA-Bench, the first open benchmark for evaluating LLMs on real-world PIAs. We first audited 499 expert-authored PIAs published by US federal agencies and curated 73 structured PIAs, comprising a total of 451 privacy risk and 831 mitigation items, to evaluate LLMs' ability to assess privacy risks and propose mitigations of complex systems. Our results show that off-the-shelf LLMs produce meaningful assessments and identify avenues for future improvement. Finally, we call for improving domain-specific workflows for LLM agents, developing accountable LLM infrastructure, and designing new quality standards for PIAs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.12508v1">Differential Privacy Meets Fixed Parameter Tractability: Algorithms and Lower Bounds</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-11T07:13:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pritish Kamath, Ravi Kumar, Pasin Manurangsi</p>
    <p><b>Summary:</b> We study combinatorial optimization problems under the constraint of $ε$-differential privacy ($ε$-DP). Given the strong lower bounds for explicitly outputting solutions, we work within the implicit representation framework of Gupta et al. (SODA 2010), where a private polynomial-time randomized "encoder" generates a representation of a solution, and a "decoder" uses this representation along with the input to extract a valid final solution.
  In this work, we generalize this framework by allowing the encoder to run in fixed-parameter tractable time. This circumvents approximation barriers inherent to polynomial-time algorithms and obtains improved guarantees for many fundamental combinatorial optimization problems.
  Finally, we establish the first representation-independent lower bounds for our framework. Assuming a non-uniform variant of the Gap Exponential Time Hypothesis, for sufficiently small $ε> 0$, we prove that no $ε$-DP encoder-decoder pair can achieve certain approximation guarantees, if the decoder runs in subexponential time. We further provide representation-dependent lower bounds that hold even for larger $ε$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.12415v1">Why User Studies and Participant Experience Reporting Matter for VR Motion Privacy?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-11T04:08:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Azim Ibragimov, Eric D. Ragan</p>
    <p><b>Summary:</b> Public VR game leaderboards contain tracked motion recordings uploaded by hundreds of thousands of users. Once uploaded, these recordings are accessible to anyone and create privacy risks (i.e., identification and profiling). Prior work has proposed mechanisms that modify tracked movement to reduce these risks. Their utility is commonly evaluated through physical deviation, where smaller deviations indicate better utility, while user studies are less common. However, it remains unclear how well physical deviation explains users' acceptance of a mechanism compared to user studies. We examine this through a user study of three VR motion privacy mechanisms at five physical deviation levels. We find that user studies explain substantially more variation in mechanism acceptance than physical deviation, although physical deviation remains significant. We also find that prior VR experience and exposure to VR privacy mechanisms significantly affect acceptance. We recommend combining physical deviation with user studies and reporting participants' prior experience.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.12378v1">An Open-Source End-to-End FHE Implementation for Privacy-Preserving Llama 3 8B Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-11T02:51:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuhang Fan, Yusi Chen, Kanyu Ye, Zhuoran Ji</p>
    <p><b>Summary:</b> Cloud LLM services typically require users to send prompts to a model provider, creating a privacy risk. Fully homomorphic encryption (FHE) lets a server perform inference without decrypting the input, but representing data as ciphertexts adds storage and computational overhead. In CKKS-based LLM inference, the packing scheme maps logical tensors to ciphertexts and slots. It therefore determines the ciphertext count and the homomorphic cost of linear layers, and it constrains how data pass between linear layers, attention, and nonlinear computation. As models and sequences grow, inefficient layouts accumulate encoding, compute, and layout-conversion overhead.
  We present Odin, an FHE inference system that co-designs ciphertext packing and model execution for Llama. Starting from a THOR-style baseline whose bottleneck is weight encoding, Odin uses a feature-major cross-layer layout to unify residual connections and layer interfaces, and builds transient intra-operator layouts for linear projections and attention. This reduces redundant plaintext encoding of weights in wide projections. Within attention, QK^T produces scores that Softmax can consume directly, and PV consumes the resulting probabilities, avoiding intermediate repacking. For nonlinear ops, we use minimax polynomial approximation with input-range control and joint error allocation guided by model quality, reducing polynomial degree and multiplicative depth. To our knowledge, Odin is the first open-source end-to-end GPU CKKS implementation of Llama-3.
  With Llama-3-8B weights and a 128-token input, Odin evaluates all 32 Transformer layers on a single NVIDIA H100 80 GB GPU. Server-side end-to-end FHE evaluation takes 366.4 s and 58.9 GiB peak device memory. Under the same model, input, CKKS parameters, and hardware, THOR takes 1651.9 s, a 4.51x speedup.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.12320v1">AIM: A Privacy-Aware Interoperable Memory Framework for Multi-Agent Multi-User LLM Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-11T01:00:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zachary Johnson, Nigel Boachie Kumankumah, Somya Chatterjee, Tejas Sathyamurthi, Min Chen, Xinyi Alice Li, Xiao Wang, Emily Morgan Gelchie, Jessica Lin, Sadid A. Hasan, Sulaiman Vesal</p>
    <p><b>Summary:</b> Traditional large language models (LLMs) are scoped to individual user sessions, limiting their knowledge to a single conversation and preventing them from learning user preferences that evolve over time. Existing agentic memory systems address this limitation but generally operate at the individual-user level, restricting the public knowledge that could be shared across users to improve downstream responses. We introduce AIM (Agentic Interoperable Memory), a unified, privacy-aware memory framework that enables multi-agent, multi-user LLM systems to persistently manage private and shared memory. AIM dynamically classifies information as private, scoped to one user and inaccessible to others, or public, accessible to all users. It enforces index-level access controls so that private memories are retrievable only by their owner, protecting sensitive data while allowing beneficial shared knowledge to improve coordination and consistency. We also introduce MUMBench (Multi-User Memory Benchmark), a dataset of multi-user interactions containing private and shareable information across four domains. To our knowledge, MUMBench is the first public dataset designed to evaluate multiple memory operations, including retrieval, creation, update, and deletion, in a multi-user environment. Across three independent runs on MUMBench, AIM achieves 96.0% visibility classification accuracy, 58.8% strict operation accuracy, and 70.5% state-aware operation accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.12067v1">Scalable Discrete-to-Continuous Channel Simulation for Compression and Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-09-10T18:01:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joseph Rowan, Buu Phan, Ashish J. Khisti</p>
    <p><b>Summary:</b> Channel simulation has recently emerged as a useful component in machine learning systems where samples from a prescribed probability distribution are to be compressed. Yet, general channel simulation algorithms often suffer from high computational costs, random stopping times or, in the worst case, can require generating an infinite number of shared random samples. We introduce a scheme for both exact and approximate simulation of discrete-to-continuous channels which conversely uses a fixed number of random samples, and therefore has a runtime independent of the channel and the input. Unlike existing channel simulation schemes which generate a sequence of independent samples from a proposal distribution, our approach generates one sample, or alternatively a fixed number of samples, from each potential target distribution. We then apply a latent permutation to the samples before performing sample selection using an exponential race. Our scheme provides a flexible tradeoff between the number of generated samples and the compression rate. Using polar and multilevel coding, we scale our approach to handle long blocklengths in $O(n \log n)$ time in order to benefit from reduced per-symbol overhead. We conclude by demonstrating applications to variable-rate compression with stochastic VQ-VAEs and communication-efficient differentially private distributed mean estimation via exact simulation of the Gaussian mechanism.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.11794v1">Second-Order Expansion of Privacy Amplification Under f-Divergence Criteria</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-09-10T16:47:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mario Berta, Hao-Chung Cheng, Marco Tomamichel</p>
    <p><b>Summary:</b> We derive the second-order asymptotics of randomness extraction from memoryless sources with side information under security criteria based on a broad class of Csiszàr f-divergences, treating both a fixed reference side-information marginal and optimization over that marginal. The conditional varentropy decomposes into fluctuations of the conditional entropy across different values of the side information and the average variance of the conditional surprisal for each value. Without marginal optimization, these contributions yield a Gaussian-mixture second-order profile. With marginal optimization, they combine into the total conditional varentropy, yielding a single Gaussian profile. As corollaries, we obtain second-order expansions for Rényi-entropy criteria of all orders $α\in (0,1)$ and recover the known expansion for total variation distance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.11780v1">Predicting Privacy Leakage from Weight Spectral Density</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Neural and Evolutionary Computing-5BC0EB">
  <p><b>Published on:</b> 2026-09-10T16:34:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Richard J. Preen, Jim Smith</p>
    <p><b>Summary:</b> Membership inference attacks (MIAs) are widely used to audit the privacy disclosure risk of machine learning models, however current state-of-the-art attacks require training computationally expensive shadow models, making large-scale privacy evaluation impractical. In this work, we investigate whether inexpensive spectral metrics derived from the heavy-tailed self-regularisation framework can serve as proxies for MIA vulnerability. We evaluate several WeightWatcher spectral metrics on image and tabular classification tasks and compare their relationship with MIA privacy leakage against conventional measures of generalisation. Across datasets, stable rank exhibits a strong positive correlation with overall MIA success, while Log alpha-Norm shows a consistent negative correlation with MIA vulnerability at the low false-positive regime. These associations are observed to be stronger than those obtained using the generalisation gap. The results indicate that neural network spectra may contain information about privacy leakage that is not fully captured by conventional measures of overfitting, motivating spectral analysis as a promising direction for scalable privacy auditing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.11777v1">Differentially Private EEG Feature Anonymization: A Privacy-Utility Case Study in Clinical Neurophysiology</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2026-09-10T16:31:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Noman Sadiq, Mohsen Toorani</p>
    <p><b>Summary:</b> Clinical electroencephalography (EEG) data are valuable for healthcare research and for developing artificial intelligence (AI)-based clinical decision-support systems, but EEG recordings and derived features may contain sensitive patient-specific information. This creates privacy risks when data are reused, analyzed, or shared across clinical and research environments. Conventional anonymization methods are often insufficient for high-dimensional biomedical signals, since removing direct identifiers does not necessarily prevent re-identification, linkage, or inference risks. At the same time, strong privacy protection may distort clinically relevant signal characteristics and reduce data utility. This paper studies subject-level differential privacy for protecting clinical EEG-derived feature representations using Gaussian and Laplace perturbations. The proposed framework considers three deployment scenarios: client-side anonymization, centralized server-side anonymization, and decentralized local training. Following EEG preprocessing and feature extraction, Gaussian and Laplace perturbations are applied to the resulting patient-level EEG feature representations. The Laplace experiments evaluate the implemented noise scales, while the scales required for formal full-vector calibration are derived separately. The effects of both perturbations are assessed using statistical utility measures and a downstream machine-learning-based utility check. The results show that differentially private perturbation can be integrated into EEG processing workflows, but the selected mechanism, privacy parameters, and sensitivity calibration strongly influence data utility. The study highlights the practical privacy-utility trade-off in DP-based EEG feature anonymization and the challenges of preserving downstream utility in small and imbalanced clinical EEG datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.11762v1">Component-Aware Differential Privacy for Federated Multilingual Speech-LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-09-10T16:17:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jordi Luque, Fernando López, Aleix Sant</p>
    <p><b>Summary:</b> Per-layer differential privacy (DP) clipping improves gradient fidelity in federated learning by allocating per-matrix clipping budgets proportional to parameter count. We show that this recipe breaks for speech large language models (speech-LLMs), when the acoustic encoder and the language decoder differ by an order of magnitude in update norm. Single-pool per-layer methods suffer \emph{cross-component budget collapse}, dragging word error rate (WER) far from flat global clipping or collapsing training entirely. When the norm imbalance is milder, adaptive single-pool methods partially recover, confirming that collapse severity scales with the inter-component norm ratio. We empirically diagnose the root cause across six per-layer methods and three speech-LLM architectures. We then propose \emph{$α$-split}, a two-pool allocation that normalises encoder and LLM parameters into independent pools, and show that joint $\ell_2$ sensitivity and the original $(\varepsilon,δ)$-DP guarantee are unchanged. At architecture-calibrated $α$, our method recovers WER utility compared to flat DP, while granting the encoder $4.47{\times}$ tighter per-component noise protection against speaker voice-based gradient-inversion attacks at only $+2.6\%$ LLM noise overhead.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.11685v1">Privacy-Preserving Causal Meta-Mediation Analysis with Survival Outcomes</a></h3>
   
  <p><b>Published on:</b> 2026-09-10T15:13:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marie-Félicia Beclin, Tat-Thang Vo</p>
    <p><b>Summary:</b> Privacy and data-governance constraints often prevent pooling individual-level data across studies, limiting the use of conventional approaches for causal media- tion analysis in multicenter settings. We propose a federated causal meta-mediation framework for right-censored time-to-event outcomes that enables collaborative es- timation without sharing individual-level data. Our framework targets natural indirect effects in a prespecified population by combining information on mediator and outcome mechanisms across distributed data sources. A site-by-site identifi- cation strategy further allows heterogeneity across data sources to be character- ized, with a variance decomposition separating outcome-related, mediator-related, and interaction components. We develop federated one-step and targeted maxi- mum likelihood estimators that accommodate data-adaptive and machine-learning methods for nuisance-function estimation. The finite-sample performance of the proposed estimators is evaluated through numerical simulations. To illustrate the practical utility of the framework, we apply it on data from the French National Health Data System to evaluate the role of methotrexate coprescription in explain- ing the effect of TNFi versus IL-12/23 inhibitor therapy on treatment persistence among psoriatic patients.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.10992v2">Demystifying the Privacy-Utility Trade-off in LLM Interactions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-10T02:12:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhenhua Liu, Zhanxu Xie, Junjie Yu, Tong Zhu, Lijun Li, Wenliang Chen</p>
    <p><b>Summary:</b> The integration of Large Language Models into daily tasks relies on context-rich instructions, inevitably exposing sensitive user information. Current privacy-preserving methods typically employ context-agnostic static rules, causing severe utility degradation. However, the specific mechanisms governing how sanitization impacts downstream performance remain largely underexplored. To address this, we conduct a systematic analysis to deconstruct the privacy-utility trade-off, uncovering three underlying mechanisms: (1) Context-Dependent Utility, which first establishes when to sanitize by revealing that data value shifts from critical constraints to dispensable noise based on user intent; (2) Strategic Adaptation, which subsequently determines how to sanitize by dictating that the choice between removal and replacement depends on the task's reliance on factual integrity versus structural coherence; and (3) Combinatorial Interplay, which finally extends the protection scope by demonstrating that attributes form a semantic web of synergistic dependencies or antagonistic redundancies. Guided by these insights, we introduce an intent-driven local protection framework. By distilling a lightweight model Veilmind-4B to drive a dynamic extraction-sanitization-restoration pipeline, our approach reaches a low-leakage privacy point while preserving substantially higher response utility than existing privacy-oriented baselines, advancing the privacy-utility trade-off toward the Pareto frontier.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.09963v1">CrossLink: Breaking Location Privacy by Linking Device Identifiers Across Protocols</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-09T09:51:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aneet Kumar Dutta, Mihirraj Dixit, Kevin Gni, Wouter Lueks, Mridula Singh</p>
    <p><b>Summary:</b> Smartphones simultaneously transmit temporary identifiers over LTE, WiFi, and BLE. Existing privacy defenses analyze identifier randomization per protocol, implicitly assuming that these protections compose across protocols. We show that they do not: Even when each protocol leaks only temporary identifiers and the adversary is fully passive, unsynchronized identifier rotations allow cross-protocol stitching of device traces. We present CrossLink, an uncertainty-aware tracing algorithm that links identifiers across time, space, and protocols under noisy localization and mobility. We evaluate CrossLink using controlled lab experiments with commodity devices and large-scale mobility simulation. Under large-scale mobility simulation, CrossLink reconstructs full traces for 83% of users, versus 22% for the best single-protocol baseline, showing that location privacy must be analyzed jointly across protocols. We further show that CrossLink remains effective under partial coverage: strategically placed sniffers near LTE handover regions, mobile sniffers, and limited high-coverage subregions retain sufficient cross-protocol evidence to bridge observation gaps, achieving substantially higher linkability than random deployments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.09794v1">Privacy-Preserving Split Learning for Federated LLM Fine-Tuning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-09T06:48:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Heng Jin, Chaoyu Zhang, Hexuan Yu, Wenjing Lou, Y. Thomas Hou</p>
    <p><b>Summary:</b> Fine-tuning large language models (LLMs) on domain-specific data is essential for downstream adaptation. In many deployments, a participant cannot hold the complete model locally. This happens because the model owner keeps the full model proprietary, or because the participant lacks sufficient compute resources. Split Learning (SL) addresses this by partitioning the model between the participant and a server so that only a small portion runs locally. When the underlying data is additionally distributed across multiple institutions with privacy requirements, Federated Learning (FL) further enables collaborative training across participants by sharing only model updates instead of raw data. In this combined setting, each client transmits intermediate activations to the server, and for LLM fine-tuning, this exchange poses an inherent privacy paradox. The autoregressive nature of LLMs causes the transmitted activations to leak the input, and existing perturbation-based defenses are fundamentally ineffective in this setting. We address this leakage through a learned obfuscate-and-recover scheme that protects participants' private datasets while still allowing an independently deployable model to be trained on the server side. Experiments demonstrate that our approach achieves strong privacy protection with modest utility loss and system overhead, making split-based federated LLM fine-tuning practically viable.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.09697v1">PrivAudit: A Dual-Lens Auditing Framework for Website Privacy Practices under the CCPA</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-09T04:31:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohamed Moustafa Dawoud, Riya Aggarwal, Likith Rahul Krishnamurthy, Ram Sundara Raman</p>
    <p><b>Summary:</b> Five years after the enforcement of the California Consumer Privacy Act (CCPA), understanding how website privacy practices evolve at scale in response to regulation remains a key challenge for both researchers and regulators. Prior work and regulatory efforts have focused on manual and case-specific enforcement, but there remain no scalable approaches to systematically audit two key user-facing facets of websites that are crucial signals for the CCPA: privacy disclosures and front-end user tracking behavior.
  In this paper, we present PrivAudit, an automated auditing framework that adopts a dual-lens approach to capture: (1) privacy disclosures through large language model-based analysis of privacy policies grounded in CCPA provisions, and (2) user-observable data collection behavior through automated browser measurements of cookie writes under diverse privacy configurations. We apply PrivAudit to 998 websites and report two broad findings. The law is associated with stronger privacy disclosures: CCPA-subject policies are more likely to disclose opt-out mechanisms, data-sharing practices, and user rights. On the other hand, cookie-based tracking remains pervasive, with both CCPA-subject and not-subject websites setting a total of 6,392 targeting cookies, 49% of which are third-party writes. Moreover, cookies show limited-to-moderate responsiveness to privacy signals and consent choices, even when websites claim to honor them in their disclosures.
  Our results highlight the need for multi-layered and scalable auditing approaches that combine policy analysis with behavioral evidence. PrivAudit can support these auditing workflows at scale by generating actionable signals and patterns for further manual review. We open-source PrivAudit and are engaging with regulators to support auditing in practice.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.10627v1">SoK: Privacy Attacks on Machine Learning via Explainable AI</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-09T02:05:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abdullah Caglar Oksuz, Anisa Halimi, Erman Ayday</p>
    <p><b>Summary:</b> Machine learning explanations reveal model behavior beyond predictions, creating attack surfaces for model confidentiality and data privacy. We systematize 25 studies that exploit explanations for model extraction, membership inference, and model inversion, treating attribute inference as partial inversion. Existing work is often labeled only black- or white-box, obscuring substantial differences in what explanation signal reaches an adversary. We therefore separate model knowledge from explanation acquisition and identify five paths: target-released, attacker-derived, secondary disclosure, privileged access, and released global artifacts. Across these paths, explanations reduce extraction cost, expose membership signals through explanation statistics, recourse distance, and explanation-guided robustness, and support spatial or algebraic reconstruction of private inputs. We compare system and threat models, explanation signals, auxiliary knowledge, target models, modalities, query budgets, evaluation metrics, reported performance, and defenses. Our analysis shows that no explanation family is uniformly unsafe and no defense is uniformly effective. Risk depends on which signal is exposed, how it is acquired, which asset is targeted, and what the attacker already knows. We argue that explanation privacy should therefore be evaluated as an end-to-end disclosure problem, with defenses matched to the acquisition path and protected asset.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.09591v1">Modality-Decoupled Federated Learning for Privacy-Preserving Embodied Intelligence in 6G</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-09-09T01:36:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhuodong Liu, Xiangyu Li, Chunhong Yuan, Hongyang Du, Bodong Shang, Qingqing Wu, Tony Q. S. Quek, Mohsen Guizani</p>
    <p><b>Summary:</b> Sixth-generation (6G) wireless networks are expected to provide a key infrastructure for large-scale embodied intelligence, where heterogeneous robots collaborate through low-latency connectivity, edge intelligence, and distributed sensing. Vision-language-action (VLA) models offer a foundation by integrating visual perception, language understanding, and action generation into a unified closed-loop policy. However, training and adapting VLA models to distributed robotic agents introduce challenges in privacy protection, communication efficiency, and model heterogeneity. Existing federated learning (FL) methods overlook the intrinsic differences among vision, language, and action pathways in parameter scale, privacy exposure, update dynamics, and tolerance to compression or perturbation. To address this issue, this article proposes FedMVLA, a modality-decoupled FL framework for privacy-preserving embodied intelligence in 6G networks. FedMVLA incorporates three mechanisms: modality-aware federated aggregation (MAFA), modality-aware privacy allocation (MAPA), and modality-aware communication compression (MACO), together with a modality-sliced transport design that routes the precision-critical action stream through a protected ultra-reliable low-latency slice. A case study on federated robotic manipulation over the Third Generation Partnership Project (3GPP)-based wireless substrate, covering fading, co-channel interference, and malicious jamming, shows that FedMVLA achieves an 84.8% task success rate, exceeds FedAvg by 22.2 percentage points, sustains a widening margin when scaling to 128 clients across eight cells, and reduces the schedule-averaged per-client uplink model-update payload by 95.6% (approximately 96%), while keeping the 95th percentile (p95) of the round-critical uplink completion time near 1.5s.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.09516v1">Differential Privacy Guarantees in Small Area Estimation</a></h3>
   
  <p><b>Published on:</b> 2026-09-08T22:57:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Soumojit Das, Jörg Drechsler</p>
    <p><b>Summary:</b> Statistical agencies increasingly rely on small area estimation to produce reliable estimates for subpopulations with limited sample sizes. These estimates are built from individual survey responses, so agencies must ensure that releasing them does not reveal information about any single respondent. We show that when a single draw from the posterior distribution of the Bayesian Fay-Herriot model is released, pure $\varepsilon$-differential privacy is unattainable, but the release satisfies formal privacy guarantees under Rényi differential privacy and zero-concentrated differential privacy without any noise being added, provided we treat the variance components as fixed. The key insight is that the posterior draw equals the posterior mean plus the Gaussian noise whose variance equals the posterior variance. The guarantee is thus governed by the sensitivity of the direct survey estimate and the posterior variance, and applies equally to a release of the posterior mean with that amount of noise added. For binary outcomes estimated with the Hájek estimator, the sensitivity equals the largest survey weight in the area divided by the sum of the weights. For the intercept-only model we derive exact coefficients describing how a change in one record propagates to every area's posterior mean, giving finite-sample per-area guarantees and a joint guarantee for releasing all areas at once that exceeds the largest per-area guarantee by at most a few percent in our applications. Two applications, poverty prevalence across 2,462 Public Use Microdata Areas in the American Community Survey and smoking prevalence across 52 substrata in the Washington state Behavioral Risk Factor Surveillance System, show that the guarantee is driven far more by the inequality of the survey weights than by the sample size, and that the shrinkage of the model tightens it substantially.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.09334v1">Execution-transcript privacy for fault-tolerant surface-code memories</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-08T18:20:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiachen Shen, Hui Zhong</p>
    <p><b>Summary:</b> A fault-tolerant quantum computer runs behind a telemetry stream logging syndromes, decoder actions, resets and timing separately from the answer. Can it reveal the logical input? For a distance-$d$ rotated surface-code memory on a fixed schedule of $T=Θ(d)$ rounds, under three stated hypotheses (sector-scalar honest backbone, transcript locality, Kotecky-Preiss smallness), the channel from logical qubit to transcript is $e^{-Θ(d)}$-close in diamond norm to one that ignores the input. A statement of this kind follows generically from correctability-privacy duality. Anisotropy does not. Each logical axis pays the distance of its own coset, so under amplitude damping the computational-basis label is governed by the code's $Z$-distance $d_Z\ge d_{\min}$ and not by the code distance. Two codes of quantum distance $1$ make the gap concrete. A phase-flip code's $X$-syndrome transcript is exactly input-independent under unobserved damping, while a repetition code leaks at first order. A matched converse identifies the records that do expose it, among them a lattice-surgery parity readout. On a 156-qubit superconducting processor our sufficient certificate misses by $21.5\times$, so the theorem cannot be invoked there. Measured directly, a $d_Z=1$ memory's record identifies its input with total variation $\ge 0.927$ under randomised, label-balanced acquisition. Holding the code fixed and varying the damping exposure reproduces the parameter-free law, with exponent $0.85\pm0.03$ against a predicted $0.86$. Randomized encoding returns the statistic to the floor at no two-qubit-gate cost. Fault tolerance does not grant transcript privacy. It relocates it, and only to the logical state, not to the circuit's identity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.08476v1">When Topology Betrays Privacy: Lattice-Based Reconstruction Attacks on Secure Aggregation in Decentralized Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-08T09:20:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenrui Yu, Changlong Ji, Johannes Bjerva, Qiongxiu Li</p>
    <p><b>Summary:</b> Secure Aggregation (SA) is widely regarded as a strong defense against model-update leakage in Federated Learning (FL), as it reveals only aggregate results while hiding individual updates. In Decentralized Federated Learning (DFL), SA is commonly instantiated as local neighborhood aggregation, where each node obtains a weighted aggregate over its neighbors. We show that this locality creates a structural leakage surface: sparse decentralized topologies provide colluding semi-honest nodes with asymmetric aggregate views, exposing multiple hidden linear combinations of honest participants' private states. Reconstructing private states from these aggregate views is fundamentally challenging, as both the private states and the aggregation coefficients are hidden. We tackle this challenge by establishing a formal connection to the Hidden Subset Sum Problem, a long-studied problem in cryptography. Building on this formulation, we design a lattice-based reconstruction approach that combines lattice reduction with structural filtering to reconstruct protected model states. We evaluate our attack on image, tabular, and text tasks under sparse DFL topologies. Our results show that colluding semi-honest nodes can recover the original local updates of honest nodes, enabling downstream reconstruction of private training data. These findings demonstrate that SA alone does not guarantee privacy in DFL when local aggregation induces asymmetric observations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.10608v1">Adaptive Diffusion Freezing: Privacy-preserving Diffusion Models Against Membership Inference Attacks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-08T08:58:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jialu Guo, Xiao Han, Junjie Wu</p>
    <p><b>Summary:</b> Diffusion models have achieved remarkable success in generative tasks across various areas, however their training process raises significant privacy concerns, particularly under membership inference attacks (MIAs). Prior studies on privacy-preserving of diffusion models fail to balance privacy, utility, and efficiency. To address this gap, we propose a novel framework of privacy-preserving diffusion models, Adaptive Diffusion Freezing (ADF), which can defend against MIAs with better trade-off. By leveraging cross-timestep adaptive freezing training, ADF explicitly control the participation of different data subsets across diffusion timesteps via a mask matrix, which reduces the over-memorization and leads to more uniform model behaviors between member and nonmember samples. To construct a freezing mask matrix that effectively reduce membership leakage without unnecessarily harming generation quality, we introduce a pretraining-based risk-aware freezing policy to estimate MIA risk based on memorization tendency, and suppress the contribution of the subset-timestep pairs with higher risk. Evaluations on multiple datasets demonstrate that ADF provides effective defense performance as well as state-of-the-art privacy-utility-efficiency trade-off performance compared to various baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.08103v2">AVP-Inspect: Coordinated Cyber-Physical Testing for Privacy Analysis of COTS Apple Vision Pro Applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-08T01:24:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yichang Xiong, Vamsi Shankar Simhadri, Yue Xiao, Xiaokuan Zhang</p>
    <p><b>Summary:</b> XR devices introduce substantial privacy concerns due to their comprehensive data collection capabilities that surpass traditional computing platforms. While existing works have demonstrated privacy concerns on Android-based XR devices such as Meta Quest series by performing network traffic analysis, little attention has been paid to the Apple Vision Pro (AVP) devices, mainly due to the closed nature and the technical challenges associated with AVP devices. In this work, we make a bold attempt to detect privacy violations of AVP applications from network traffic through automatic testing on AVP devices. Our key insight is that effective AVP application testing requires coordinated control of both cyber (software) and physical (hardware) components, which we term Coordinated Cyber-Physical Testing. Building on this insight, we design and implement AVP-Inspect, an automatic dynamic analysis framework for AVP applications, overcoming significant challenges enforced by the closed-source nature of AVP ecosystem. AVP-Inspect consists of three components: an automatic device controller by building customized hardware devices, a 3D UI explorer by designing a new exploration engine, and a privacy violation detector by constructing a unified privacy taxonomy for AVP. We first evaluated AVP-Inspect on a manually constructed ground truth dataset, then performed a large-scale analysis on 324 AVP applications downloaded from the App Store, with each app tested for 20 minutes. We found that 188 (58.0%) of apps exhibit at least one violation, and more than 60% of the network traffic flows are not properly disclosed.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.07654v1">ZK-eSIM: A Privacy-Centric Zero-Knowledge Approach for eSIM Provisioning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-07T15:42:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Liza Ahmad, Quan Shi, Joshua Haworth, Yilu Dong, Prosanta Gope, Behzad Abdolmaleki, Syed Rafiul Hussain</p>
    <p><b>Summary:</b> GSMA Remote SIM Provisioning (RSP) enables over-the-air delivery of eSIM profiles, but it exposes long-lived identifiers during profile ordering and download. In particular, stable device identifiers (e.g., EID), profile identifiers, and long-lived certificate material enable mobile operators and profile-delivery infrastructure to link provisioning events to the same eUICC and, when combined with account records, to the same subscriber. This undermines subscriber anonymity and enables cross-session tracking. We present ZK-eSIM, a privacy-preserving redesign that achieves subscriber anonymity and provisioning-session unlinkability while retaining accountable traceability by exception. ZK-eSIM (i) replaces direct disclosure of device identifiers with a zero-knowledge proof of device validity and eligibility; (ii) enforces session unlinkability through short-lived, one-time pseudonymous credentials and per-session identifiers to prevent cross-session tracking; and (iii) provides privacy-preserving accountable traceability through a jointly authorised escrow mechanism, so that no single entity can unilaterally deanonymise a user. We formalise a multi-entity, honest-but-curious threat model and prove subscriber anonymity and the unlinkability of provisioning sessions under standard cryptographic assumptions. We implement a Java Card applet on a test eUICC to evaluate performance on commodity hardware with a modified LPA and SM-DP+ server. Our experiments quantify end-to-end cryptographic overhead relative to conventional RSP, confirming that ZK-eSIM adds only practical overhead, closing a critical privacy gap while preserving deployability within existing GSMA roles and interfaces.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.07623v1">Privacy Leakage from a Thousand Words: Millipixel Location Recovery from Dot Maps</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-09-07T15:25:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuntao Du, Tanishq Pauskar, Hao Wang, Jing Su, Ninghui Li</p>
    <p><b>Summary:</b> Dot maps, which visualize individual data points as dots over a geographic region, are widely used across diverse domains to represent spatial patterns in sensitive data. However, the understanding of the privacy risks associated with dot maps remains limited, particularly for maps covering large geographic areas. In this paper, we systematically analyze these risks and present AutoLocate, an automated framework for high-precision location recovery. At its core, AutoLocate exploits anti-aliasing artifacts introduced during map rendering, which inadvertently encode sub-pixel information about dot locations. AutoLocate formulates location recovery as a black-box optimization problem, iteratively refining estimated coordinates by minimizing perceptual discrepancies over these artifacts between the target map and rendered candidate maps. Extensive experiments on both real-world and synthetic datasets, across different attack scenarios and a broad range of map configurations (e.g., map scale, background, resolution), demonstrate the effectiveness of AutoLocate. In particular, it achieves average recovery errors as low as 1 meter (approximately 0.0002 pixel precision) on small-scale maps of the United States, over 200x more accurate than existing approaches. We also propose mitigation strategies and introduce a privacy risk assessment tool to help practitioners evaluate and reduce privacy leakage when publishing dot maps.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.07428v1">Masking Radar Cognition under Adversarial Surveillance: A Distributional Privacy Framework</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-07T12:32:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sreedevi K, Nandhini K, Anup Aprem, Deepthi P P</p>
    <p><b>Summary:</b> In this article, we propose an online electronic counter-countermeasure (ECCM) framework designed to conceal the strategic decision-making processes of a cognitive radar (CR) operating under adversarial surveillance. We model the CR under two distinct decision paradigms: a static constrained utility-maximizing behavior and a dynamic expected utility-maximizing behavior. The radar's utility function is modeled via a von Mises--Fisher (vMF) distribution, with the distributional parameter constituting the private information to be protected from adversarial inference. We adopt a distribution privacy framework to conceal this private information and provide formal distribution privacy guarantees for cognition masking. In this work, we develop cognition-hiding algorithms for both static constrained utility maximization (WDPCH-SU), and dynamic expected utility maximization (WDPCH-DU). Through rigorous mathematical analysis, we show that both WDPCH-SU and WDPCH-DU satisfy $ε$-distribution privacy ($ε$-DistP) against inference-based adversarial attacks and present the privacy--performance trade-off bounds, quantifying utility loss (in static setting) and expected utility deviation (in dynamic setting) as functions of $ε$. Numerical results show that WDPCH-SU gives about 15\% improvement in utility loss at maximum privacy compared to the existing methodology while WDPCH-DU achieves a greater reduction in adversarial Fisher information without requiring explicit Fisher information constraints, at a moderate, analytically bounded utility deviation. These results are highly promising in many 6G communication scenarios such as network slicing for automated driving and swarm UAV coordination, where it is essential to keep the resource allocation policy robust against privacy attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.07217v1">Enhancing Privacy, Neglecting Harms: An Analysis of Real-World Digital Privacy Incidents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-09-07T08:34:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shannon Veitch, C. Shem, Lena Csomor, Oleksandr Dudiy, Naone Kim, Khoi Le, Lina Saha, Alexander Viand, Anwar Hithnawi, Bailey Kacsmar</p>
    <p><b>Summary:</b> Privacy-enhancing technologies (PETs) have emerged as a technical means for providing individuals with greater control over their information. Yet despite the growing deployment of PETs, people continue to experience privacy harms. In this work, we revisit our understanding of privacy incidents and the realities of those experiencing privacy harms, to assess whether the goals and abilities of PETs are misaligned with the harms people face.
  For our study, we collect news articles that correspond to a sample of 257 real-world privacy incidents. We employ content analysis over the articles to develop a new information flow model that encompasses the complexity of data flows and their relation to resulting harms. We demonstrate that our model captures both established and novel aspects of privacy incidents and their mitigations. In particular, it captures why consent is often insufficient to prevent privacy violations, how harms emerge from complex interactions among multiple entities and actions, and reveals a flaw in our understanding of PETs: a focus on enabling functionalities still permits the harms inherent in those functionalities. Moreover, we find that the entities best positioned to implement harm-preventing measures for the incidents in our sample are the least incentivized to do so. Overall, our model and analysis identify limitations of privacy technology research for harm prevention and further identifies paths for transforming how we approach the advancement of these technologies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.07038v1">AdoDAS: A Privacy-Preserving Multimodal Challenge for Adolescent Depression, Anxiety, and Stress Assessment</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Multimedia-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36">
  <p><b>Published on:</b> 2026-09-07T04:49:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhaojie Luo, Junkun Wang, Tianhua Qi, Yuxuan Wu, Xin Zhao, Tetsuya Takiguchi, Tomoko Matsui, Kun Qian, Fei Wang, Shuqiong Wu, Zhengjun Yue, Hiroshi Ishiguro, Xinyuan Qian, Haizhou Li</p>
    <p><b>Summary:</b> Adolescent depression, anxiety, and stress (D/A/S) call for scalable tools that complement, rather than replace, professional evaluation. Under a privacy-preserving policy, the AdoDAS Grand Challenge withholds minors' raw recordings and distributes anonymized audio-visual representations and ASR-derived text. Its 6,000 participants provide 24,000 segments across one scripted-reading and three open-response sessions. Two tracks assess multi-task binary D/A/S screening and ordinal prediction of 21 DASS-21 item responses. From 191 registrations, the final leaderboards included 95 eligible screening teams and 64 item-prediction teams. Audio-visual baselines achieved 0.4604 mean F1 and 0.2675 mean Quadratic Weighted Kappa; leading submissions reached 0.5921 and 0.2776. Representative systems emphasize cross-session modelling, temporal multimodal fusion, psychometric structure, and task-aware calibration.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.07022v1">CIPHER: Benchmarking Cross-record Inference over Privacy-Hardened Evidence Records</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-09-07T04:21:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Suparno Roy Chowdhury, Manan Roy Choudhury, Dhruv Madhwal, Vivek Gupta</p>
    <p><b>Summary:</b> Reasoning over privacy-constrained records requires combining structured attributes with evidence from free-text narratives. We introduce CIPHER (Cross-record Inference over Privacy-Hardened Evidence Records), a benchmark of expert-validated questions from consumer-finance, clinical, and law-enforcement records. The questions cover common tabular operations and include executable SQL supervision. We evaluate retrieval, prompting, table-specialist, and hybrid symbolic-neural systems under native redaction and surrogate-based evidence restoration. All system families exhibit substantial failures even when supporting records are provided. Most errors arise from incorrect record selection and predicate interpretation rather than arithmetic execution. Privacy transformations have non-uniform effects, sometimes obscuring necessary evidence and sometimes reducing distraction. CIPHER provides a reproducible testbed for diagnosing these failures and assessing how transformations of sensitive text affect reasoning over hybrid records.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.06928v1">Emo-DVS: A Multimodal Benchmark for Privacy-Aware Emotion Recognition with Event Cameras</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-09-07T01:55:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiaqi Chen, Qinfu Xu, Hao Zhuang, Liyuan Pan</p>
    <p><b>Summary:</b> Emotion analysis is a fundamental task in computer vision, but its practical deployment remains constrained by the privacy risks inherent to conventional RGB cameras. Bio-inspired event cameras present a promising hardware-level solution because they capture asynchronous brightness changes, thereby reducing exposure of facial identity details while leveraging high dynamic range for robust perception under challenging illumination conditions. Despite these advantages, existing event-based methods struggle in complex real-world settings due to limited dataset scales, simple acquisition conditions, and reliance on single-modality visual cues. To address these, we establish a challenging tri-modal benchmark with event, audio, and text modalities and propose the Information-Guided Gated Fusion (IGF) framework, which first pre-trains an event encoder on the FAU subset of Emo-DVS to capture fine-grained facial dynamics, then employs adaptive modality gating to suppress modality-specific noise, and finally leverages mutual information maximization to align robust cross-modal representations. To alleviate data scarcity, we introduce Emo-DVS, the first large-scale event-based emotion analysis dataset, which couples dynamic illumination with the Facial Action Unit (FAU) subset and emotion subset. Extensive experiments demonstrate that IGF achieves state-of-the-art performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.06749v1">A Novel Semantic Manifold Alignment Attack against Embedding-to-Embedding Obfuscation in Privacy-Preserving LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-09-06T17:45:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sicong Li, Lingfeng Yao, Xingke Yang, Ke Tu, Chenhao Wu, Hao Wang, Jiang Liu, Phone Lin, Xin Fu, Miao Pan</p>
    <p><b>Summary:</b> With the widespread applications of large language models (LLMs), privacy-preserving inference has become increasingly essential for sensitive queries. To balance privacy and utility, a series of lightweight obfuscation approaches has recently been proposed, where users locally transform plaintext embeddings into the fixed ciphertext ones. While such Embedding-to-Embedding Obfuscation (E2EO) schemes demonstrate considerable resilience against traditional token frequency and embedding inversion attacks, the core mechanism behind remains to be the large-scale one-to-one substitution, which provides no cryptographic guarantees. In this paper, we propose Proxy Manifold Alignment (PMA), a novel attack against E2EO in privacy-preserving LLMs. Our key observation is that E2EO schemes keep the original semantic structure, so that the obfuscated vector stream can be regarded as an unknown tokenizer-language whose symbols are the vectors themselves. Therefore, the proposed ciphertext to plaintext reconstruction attack can be formulated as a translation task from the unknown tokenizer-language to plaintext. Specifically, by only accessing the obfuscated vector stream, the target tokenizer and a public corpus, the PMA attack first employs Word2Vec to model the co-occurrence patterns within the obfuscated stream and the public corpus independently, and constructs two proxy vector embeddings. Then, the attack aligns the underlying manifolds of these two embeddings based on structural similarity. Finally, it maps the obfuscated vectors back to plaintext. Experimental results demonstrate that PMA consistently achieves higher plaintext recovery than other state-of-the-art attack methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.05702v2">Characterizing Privacy Risks of Quantum Machine Learning with Emergent Quantum-Native Access</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-04T20:14:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Liou Tang, James Joshi, Ashish Kundu</p>
    <p><b>Summary:</b> Quantum Machine Learning (QML) has shown rapid advances by utilizing quantum computing for machine learning tasks. Meanwhile, the privacy risks accompanying QML is also starting to be studied, which inherit privacy leakage channels from "classical" ML and also quantum-unique risks. Existing work on privacy-preserving QML largely focuses on a QML-as-a-service scenario, which generally assumes that the QML model owner provides only classical bit outputs to queries, while users (and adversaries) have only classical computing abilities. However, this view is increasingly challenged in a quantum-native world of quantum-capable users/adversaries, which may have access to both quantum computing abilities and access to quantum information output from service providers.
  In this paper, we aim to bridge this gap by examining membership inference attacks against QML models by demonstrating that increasing quantum access and quantum computing abilities provides provable theoretical privacy leakage and empirical adversarial gain. However, the probabilistic nature of QML introduces a gap between theoretical and empirical adversarial advantage. These results show that existing research on privacy leakage in QML models underestimates privacy leakage in emergent quantum-native access regimes, and we hope to establish a first step in examining potential privacy leakages for QML in the quantum-native world.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.05340v1">Trust-Aware Adaptive Disclosure for Inference Privacy Preservation in Multi-Agent Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-04T16:44:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Puspanjali Ghoshal, Tobias J. Oechtering</p>
    <p><b>Summary:</b> Agent based systems are increasingly deployed in information critical systems including healthcare management systems, and smart grids. In this paper, we consider a multi-agent system where each agent has a latent goal that needs to be kept hidden from observing adversaries. More specifically, this paper studies privacy-preserving consensus in networked multi-agent systems under goal inference attacks. We propose a Trust-Aware Privacy Control framework that adapts message disclosure based on the dynamic trust relationships between agents. The proposed method controls information release using a trust-dependent stochastic policy. This enables a tradeoff between consensus performance and privacy preservation. Experiments demonstrate that the proposed method reduces adversarial goal inference accuracy compared to representative baselines, while maintaining competitive consensus utility, thereby highlighting the effectiveness of trust-aware mechanisms in privacy preservation of the agents in multi-agent systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.05119v1">Understanding the Privacy-Preserving Potential of HTTP/2 Against Webpage Fingerprinting</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-04T13:16:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bogdan Cebere, Prateek Kumar, Sylvain Chatel, Wouter Lueks, Christian Rossow</p>
    <p><b>Summary:</b> Website fingerprinting (WF) attacks can infer which webpage a user visits from encrypted HTTPS traffic alone, compromising privacy even without decryption. WF defenses commonly shape traffic through noise, padding, delays, or flow splitting, yet they are most often studied from the perspective of encapsulating protocols like Tor or VPN rather than at the application layer (HTTP).
  In this work, we focus on application-layer defenses enabled by the most widely deployed version of HTTP, HTTP/2. We demonstrate how known defenses can be emulated through HTTP/2 features at the client side (HTTPOS, LLaMA, FRONT, Tamaraw) and the server side (ALPaCA, Tamaraw). We further show that HTTP/2 features, such as proactive resource suggestion, multiplexing, and flow control, offer untapped potential for lightweight yet effective defenses deployable at both endpoints.
  We evaluate these defenses using a unified blueprint that calibrates defense parameters per dataset, then combines practical attacks, information-theoretic leakage estimates, and overhead measurements. For each defense, this framework identifies the strongest hyperparameter-tuned fingerprinting model and estimates the residual uncertainty induced by the defense using two information-theoretic leakage estimators, all while accounting for the defense's privacy-overhead trade-offs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.05095v1">CAT-LDP: Cloud-edge Adaptive Taxonomy under Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2026-09-04T12:49:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Junzhe Yang, Chang Xia, Xiyun Wang, Anren Sun, Wenbo Ding, Xinye Chen</p>
    <p><b>Summary:</b> Recommender systems are widely used in daily life, but their direct collection and use of user preference data can also lead to privacy leakage. Existing privacy-preserving recommendation methods often find it hard to balance user privacy and recommendation performance. This problem is more serious in implicit-feedback settings, where data sparsity further increases the loss of useful signals caused by privacy perturbation. To solve this problem, we propose CAT-LDP, a cloud-local collaborative recommendation framework under local differential privacy constraints. CAT-LDP combines a hierarchical taxonomy tree with an adaptive privacy budget allocation strategy to keep more useful signals in users' active categories while protecting user privacy. Specifically, users upload perturbed category profiles that satisfy LDP. Based on these profiles, the cloud performs coarse-grained candidate generation, and the local device then carries out fine-grained reranking by using unperturbed local history. Experiments on the Amazon Video Games dataset show that CAT-LDP consistently outperforms its fixed-budget ablation variant and representative baselines on HR@K and NDCG@K under different privacy budgets. The results show that combining category-space modeling with cloud-local task decoupling can effectively reduce noise amplification in long-tail sparse settings and provide a better balance between privacy and utility for implicit-feedback recommendation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.05034v1">Faster Learning under Relaxed Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> 
  <p><b>Published on:</b> 2026-09-04T11:55:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Cristina Butucea, Huiyun Tang, Marie-Luce Taupin</p>
    <p><b>Summary:</b> We consider density estimation under the relaxed local differential privacy condition that the privatized distributions are $α$-close in total variation distance. We show that adding independent noise with a convenient symmetrized Gamma distribution to each sensitive observation attains the $α$-TV-LDP. We prove that the deconvolution estimator of $r$-Sobolev smooth functions attains the pointwise rate $(nα)^{-\frac{2r-1}{2r}}$ up to log factors which is faster than $(nα^2)^{-\frac{2r-1}{2r+1}}$ under the classical $α$-LDP and closer to the nonprivate minimax rate $n^{-\frac{2r-1}{2r}}$. Next, we use a Goldenshluger-Lepski procedure to build a free of the smoothness adaptive procedure and show optimality of our rates in the convolution model of our privatisation scheme. We illustrate the benefits of this simple privacy mechanism by implementing a neural network estimator which does not need to add more noise in the optimization steps. Numerical results show significant improvement of the estimation rate over the Laplace and the private-SGD mechanisms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.04592v1">Hidden In Plain Gaze: Gaze Representations as Privacy Controls for Utility and Re-identification Risk in XR</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-04T00:47:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Cory Ilo, Brendan-David John, Doug A. Bowman</p>
    <p><b>Summary:</b> Intelligent extended reality (XR) systems increasingly use eye and head tracking to infer user intent, task, and attention, but the same signals can also reveal biometric identity. We study whether gaze data representation choice can serve as a lightweight privacy control at feature extraction, before adding perturbation or formal privacy mechanisms. Using the egocentric HoloAssist dataset, we compare three gaze representations under matched model capacity: raw gaze, spatial attention heatmaps, and engineered eye-movement features. We evaluate each representation on action recognition as task utility and closed-set user re-identification as privacy leakage. Representation choice substantially changes the privacy-utility tradeoff. Engineered features retain roughly 85% of raw gaze's action-recognition accuracy while reducing re-identification by about an order of magnitude, to roughly four times the chance rate across 206 identities. This reduction attenuates rather than eliminates identity leakage, and the differences across representations show that abstraction alone does not guarantee privacy. Engineered features expose interpretable and auditable structure, giving designers a transparent privacy lever that complements mechanisms such as differential privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.04382v1">Privacy Failure in Split-LLM Training, The Returned Gradient Nullifies the Decoys</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-03T18:43:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Georgios Politis, Evangelos Pappas</p>
    <p><b>Summary:</b> We present a systems-security case study of a two-node split-LLM training system whose privacy evaluation passed while leaving an observable channel untested. The Trusted Local Node (TLN) sends protected activations to the Untrusted Cloud Node (UCN), the UCN returns its output, and TLN, holding the private loss, returns the output gradient. The frame the UCN receives mixes real rows with decoys, and the loss ignores the decoys. Their gradients are exactly zero, so the pattern of zeros reveals which rows were real. We measure it with a protocol fixed in advance: a leak injected at known strength to prove the instrument can see one, a shuffled-label control to prove it does not report absent leaks, and a threshold set before the runs. Across nine seeds, the zeros identified the real rows on every frame, 4,096 of 4,096 per run. An attack on the frame contents recovered about one extra token per hundred over a constant-guess baseline (+0.65 to +1.50 percentage points); the shuffled controls recovered nothing. A second set of runs repeated this on a configuration that keeps model quality within budget, so the finding is not confined to a setting nobody would deploy. On both datasets, every such run passed the forward-channel privacy check and the quality check, yet failed that same check once the returned gradient was included. Clipping and noising each row of the gradient closed the leak for about 0.01 nats of held-out cross-entropy. The system is not thereby safe: five classes of attack, including those accumulating observations across training steps, were never measured.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.03659v1">Security and Privacy in the Musical Metaverse: Threat Analysis and Design Implications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-03T10:56:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Luca Turchet, Michał Kłosinski</p>
    <p><b>Summary:</b> The Musical Metaverse (MM) introduces immersive, real-time environments for collaborative musical interaction, characterized by ultra-low-latency constraints, continuous multimodal data streams, and heterogeneous devices. These properties create a distinctive security and privacy landscape that differs significantly from conventional XR or multimedia systems. This paper presents a multi-layer threat analysis of MM ecosystems, identifying key assets including live musical content, expressive interaction data, identity and session metadata, and intellectual property. Threats are analyzed across network, application, data/AI, device, intellectual property rights, and social layers, with particular attention to risks arising from expressive and neurophysiological data, which enable inference, re-identification, and potential privacy violations. We describe a stakeholder-driven survey involving 14 participants from 13 organizations, revealing that neurophysiological data leakage and real-time stream disruption are perceived as the most critical risks, followed by intellectual property infringement and avatar impersonation. We further evaluate the suitability of existing security protocols under strict latency constraints, showing that conventional approaches such as TLS over TCP are often incompatible with real-time musical interaction, while lightweight, stream-oriented mechanisms (e.g., SRTP, DTLS) provide a more suitable balance between security and performance. Based on these findings, we derive a set of design guidelines for MM systems, emphasizing latency-aware security, differentiation of interaction paths, data minimization, and edge-centric processing. The results support a security-by-design approach that enables trust and compliance without compromising real-time performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.03615v1">Auditing Patient Privacy in Medical Generative Models: Scalable Memorization Detection with DeepSSIM++</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-09-03T09:59:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Antonio Scardace, Francesco Guarnera, Sebastiano Battiato, Daniele Ravì</p>
    <p><b>Summary:</b> While deep generative models offer new opportunities for medical image synthesis and data sharing, their ability to memorize and reproduce training samples raises serious concerns about patient confidentiality. Detecting such memorization at scale remains challenging: traditional pixel-based metrics are sensitive to generation artifacts, whereas generic embedding-based metrics often lack the anatomical sensitivity required for medical data. To address this challenge, we introduce DeepSSIM++, a self-supervised similarity metric for scalable memorization auditing in medical generative models. By leveraging multi-scale feature aggregation and anatomy-preserving augmentations, DeepSSIM++ learns an embedding space where cosine similarity approximates the Structural Similarity Index (SSIM), eliminating the need for exact pixel-level registration. Compared with state-of-the-art baselines, DeepSSIM++ achieves an average Macro F1 improvement of 33 percentage points under ideal alignment and 46 percentage points under realistic spatial and intensity perturbations. Furthermore, it accelerates large-scale similarity computation by several orders of magnitude compared with analytical SSIM. By combining anatomical sensitivity and computational efficiency, DeepSSIM++ provides an open-source tool for scalable memorization auditing in medical generative AI. Code and data are publicly available at: https://github.com/brAIn-science/DeepSSIM.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.03420v1">Privacy, Robustness, and Fairness Trade-offs in Federated Intrusion Detection: Geometric Indistinguishability at the Aggregation Interface</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-03T06:27:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Adrita Rahman Tory, ABM Shawkat Ali, Md Abu Layek, Khondokar Fida Hasan</p>
    <p><b>Summary:</b> Federated learning enables privacy-conscious collaboration for network intrusion detection without centralizing sensitive traffic data, yet its deployment in operational environments must simultaneously satisfy three competing requirements: formal differential privacy guaranties, tolerance to Byzantine-adversarial participants, and reliable detection coverage across severely imbalanced attack categories. Existing literature treats these properties as independently composable, an assumption that this paper challenges both theoretically and empirically. In this paper, we study how these requirements interact in class-imbalanced federated NIDS and introduce geometric indistinguishability as a conceptual lens for a regime in which privacy-induced dispersion in client updates can make minority-class signals harder for robust aggregation to preserve. Using UNSW-NB15 as a case study, we evaluate DP-SGD combined with coordinate-wise median under label-flip and model-poisoning attacks, with threat coverage assessed across attack categories. Our results provide initial evidence that the joint use of privacy noise and robust aggregation can disproportionately degrade detection of rare attacks relative to majority classes. We also show that part of the observed collapse under strong privacy can arise from training miscalibration, while a residual performance floor may remain for ultra-rare categories even after epsilon-dependent tuning. These findings motivate studying privacy, robustness, and rare-attack coverage jointly rather than as independently composable properties, and suggest that aggregation-aware modeling and sample-aware evaluation are promising directions for trustworthy federated NIDS.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.03245v1">A Joint Power-Privacy Control Framework for Decentralized Learning over Heterogeneous Wireless Multicasting Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-09-03T00:56:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Amir Ziaeddini, Yauhen Yakimenka, Joerg Kliewer</p>
    <p><b>Summary:</b> In this paper, we propose a decentralized learning framework that incorporates both power control and privacy guarantees. Specifically, we enable a set of clients in a wireless multicast network to jointly train a common model while maintaining a prescribed per-iteration maximum privacy leakage level. The communication network is represented by a rowstochastic adjacency matrix, allowing us to capture asymmetric channel gains as well as heterogeneous maximum transmit power levels. Differential privacy is enforced through an explicit powersplitting strategy that allocates each node's limited maximum transmit power between model coefficients and injected Gaussian noise, thereby jointly controlling learning performance and privacy leakage. We further prove that the proposed algorithm achieves a cumulative regret bound of O(logT), whereTdenotes the time horizon. To evaluate the practical performance of our approach, we perform comprehensive experiments on the CIFAR-10 dataset under both IID and non-IID data distributions, considering different privacy levels, diverse numbers of clients, and various graph topologies. The results demonstrate strong performance across the considered settings and improved performance over existing methods, highlighting the effectiveness of the proposed algorithm under realistic wireless communication constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.03055v1">Seeing Less Is Not Seeing Safely: Privacy Leakage from Task-Scoped Robot Perception Exports</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-02T18:29:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuqiao Xu, Erman Ayday</p>
    <p><b>Summary:</b> Domestic robots rely on rich perception to operate in private homes, but privacy risk persists even when raw sensor data remain local. Structured representations exported to downstream planners, cloud services, logs, or learning pipelines can still reveal household information through semantics, geometry, spatial structure, and task targets. We introduce Task-Functional Perception Distillation (TFPD), a task-scoped representation-export framework that keeps rich perception local and profiles downstream exports according to task utility, direct exposure, and multiple residual inference risks. Using 120 AI2-THOR scenes with scene-disjoint train/validation/test splits, frozen attacker selection, and representation-aware held-out attacks, we evaluate navigation, collision checking, and object-goal execution. Three navigation exports achieve identical success (1.000) and mean path ratio (0.898), yet representation-level linkability ranges from 0.532 to 0.970. Replacing an explicit target label with a target region reduces target-category macro-F1 from 1.000 to 0.077 while preserving success at 0.995, while geometric coarsening reduces object-category macro-F1 from 0.704 to 0.556 at a measurable collision-utility cost. A ProcTHOR replication preserves the navigation task-equivalence/privacy-inequivalence finding while changing the relative ordering of normalized and topological exports. These results show that neither field removal nor stronger abstraction induces a universal privacy ordering and motivate task-specific, multi-risk evaluation of the complete public representation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.02700v1">The PIONEER Project: A PrIvacy companion for mOtivatioN and knowlEdge transfER</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-09-02T15:06:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Simon Althaus, Nina Gerber, Sara Hahn, Andreas Heinemann, Angela Menig, Max Mülhäuser, Christian Reuter, Ephraim Zimmer</p>
    <p><b>Summary:</b> Remaining control over their private data is one of the key challenges in this century for users. We know from prior work that users are often neither in a position to fully grasp the content of the usually complicated texts, nor are they motivated to spend the time necessary to do so. We report on the progress made by the PIONEER project on a privacy support tool that combines knowledge transfer and persuasive elements to increase users' privacy awareness and motivation; thus empowering them to more privacy sovereignty. Throughout the research and design process, we consider user group specifics that may result in different requirements, e.g., for children, adolescents, parents, or elderly people. We further target sustainable behavior change by addressing different states of change, precisely: spark initial motivation, facilitate the creation of new habits, and encourage habituation of these habits in the long term (volition). Finally, we provide a privacy support tool demonstrator that can be utilized for research and education purposes, e.g., in school contexts.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.02495v1">Big data, differential privacy, and national statistical organisations</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-09-02T12:01:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> James Bailie</p>
    <p><b>Summary:</b> Differential privacy (DP) has emerged in the computer science literature as a measure of the impact on an individual's privacy resulting from the publication of a statistical output such as a frequency table. This paper provides an introduction to DP for official statisticians and discuss its relevance, benefits, and challenges from a National Statistical Organisation (NSO) perspective. We motivate our study by examining how privacy is evolving in the era of big data and how this might prompt a shift from traditional statistical disclosure techniques used in official statistics--which are generally applied on a cell-by-cell or table-by-table basis--to formal privacy methods, like DP, which are applied from a perspective encompassing the totality of the outputs generated from a given dataset. We identify an important interplay between DP's holistic privacy risk measure and the difficulty for NSOs in implementing DP, showing that DP's major advantage is also DP's major challenge. This paper provides new work addressing two key DP research areas for NSOs: DP's application to survey data and its incorporation within the Five Safes framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.02971v2">Privacy Leakage in Federated Learning: Gradient-Based Client Identity Inference and Defenses for Inertial Sensing in Vehicular Edge Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-09-02T09:49:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ali Akarma, Toqeer Ali Syed, Muhammad Khan, Qurat-ul-ain Mastoi, Adeel Ahmad</p>
    <p><b>Summary:</b> As vehicular networks move toward 5G/6G edge intelligence, federated learning (FL) is widely promoted as a privacy-preserving way for vehicles and infrastructure to train shared models without exposing raw sensor data. Yet the updates clients transmit still leak enough information to identify who sent them, which threatens the anonymity that safety-critical V2X applications assume and adds to existing concerns over adversarial ML, model poisoning, and backdoor attacks. We study server-side client identity inference from transmitted weight deltas using inertial (IMU) measurements, evaluated on the UCI Human Activity Recognition (HAR) benchmark as an accessible proxy for the IMU streams produced onboard connected vehicles. Across five attack classifiers and five non-IID partitions, an honest-but-curious server recovers client identity with near-perfect accuracy (approximately 1.000) from undefended updates, confirming a concrete identifiability risk. We then quantify the privacy-utility trade-off of a lightweight clip-then-noise defense by sweeping Gaussian noise (sigma in {0.00, 0.05, 0.10, 0.20, 0.50, 1.00}) at fixed clipping (C=1.0), and report formal (epsilon, delta)-DP budgets through Renyi accounting. A practical region (sigma in [0.1, 0.2]) drives attack accuracy to near-random while costing under 5% relative FL accuracy. Ensemble FL supplies complementary structural privacy with a 1/K anonymity-set bound and no noise penalty. Results are supported by cryptographic (SHA-256) train/evaluation gradient disjointness, three seeds, and a count-normalized attacker-advantage metric. We position HAR explicitly as a proxy and discuss what validation on true vehicular telemetry would require.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.02376v1">Removing Speech, Keeping Activities: A Privacy Firewall for Acoustic Sensing in Assisted Living</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-09-02T09:48:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pavlos Nicolaou, Christos Efstratiou</p>
    <p><b>Summary:</b> Acoustic sensing offers a promising non-intrusive approach for monitoring daily activities of older adults, yet speech privacy concerns remain a critical barrier to real-world deployment. We present a privacy firewall pipeline based on a U-Net encoder-decoder, trained entirely on synthetic data, that removes speech from ambient audio while preserving environmental sounds indicative of daily activities. Activity recognition is performed using VGGish transfer learning with an SVM classifier. Evaluated on the ESC-50 and SINS datasets across multiple speech content levels, the proposed model reduced residual speech to 0% VAD-detectable speech (Silero Voice Activity Detection) under all tested conditions, outperforming Facebook Denoiser (6.55% residual), SepFormer (36.34%) and ConvTasNet (47.21%) on ESC-50 at the 100\% speech level. On ESC-50 at 40% speech level, classification performance recovers to 85% precision and 85% recall after speech removal, compared with 81%/75% before removal and an 84%/83% speech-free baseline. Evaluation on real-world participant home recordings collected with the AudioHive app showed 0% VAD-detectable speech after processing while maintaining 76% precision and recall. The pipeline enables privacy-preserving acoustic sensing without sacrificing activity recognition performance, addressing a key obstacle to the adoption of ambient monitoring in elderly care.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.02323v1">Quantum Workload Privacy Beyond Data Confidentiality</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2026-09-02T09:06:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shaunak Suresh Pawar, Samuel Punch, Krishnendu Guha</p>
    <p><b>Summary:</b> Remote quantum computing exposes a confidentiality gap. Standard privacy mechanisms protect quantum states and outputs, but not the scientific structure of a workload. This work reveals that hardware-aware compilation leaves observable signatures, such as routing overhead, circuit depth, and gate composition, that correlate with hidden modelling choices like partial differential equation boundary conditions, discretisation scale, and molecular geometry. The leakage arises from the mismatch between logical topology and fixed hardware connectivity, forcing problem-dependent SWAP insertion. We formalise this threat as Scientific-Intent Indistinguishability and prove that passive security is asymptotically unachievable under routing-optimal compilation. Experiments on a 156-qubit IBM Heron processor achieve near-perfect classification of boundary regimes and molecular geometries, with leakage generalising across solver families via routing-scaling exponents. Conventional gate-padding fails as a defence, causing fidelity drops without reducing adversarial advantage. Our results show that protecting quantum data alone is insufficient; execution-level confidentiality must become a first-class design requirement.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.02967v1">Privacy-Preserving Topology-Guided Safety for LLM-Based Multi-Agent Systems via Federated Graph Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2026-09-02T07:57:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jinxi Yu, Eric Hanchen Jiang, Levina Li, Dong Liu, Zhi Zhang, Wenxiao Zhao, Yanxuan Yu, Kai-Wei Chang, Ying Nian Wu</p>
    <p><b>Summary:</b> Topology-guided safeguards for LLM-based multi-agent systems (MAS) train a GNN over the inter-agent communication graph to localize risky agents and intervene on the topology---but they assume one operator can pool all labeled traces. Across organizations that assumption breaks: episodes contain private prompts, tool outputs, and proprietary workflows, and no silo alone sees the full attack distribution. We cast privacy-preserving MAS safeguarding as graph federated learning and instantiate FGLGuard: each operator fits an edge-featured graph attention detector on its own judge-labeled episode graphs and shares only model updates. The method couples a proximal local objective for non-IID clients, domain-balanced aggregation, over-refusal-constrained threshold calibration, corroborated upstream scoring, and a guarded rewrite for blocked answers. Federation is not optional: off-the-shelf transfer collapses under distribution shift (AUROC 0.51 to 0.70 only after in-domain retraining), so a deployable guard must adapt on each site's private traces. On Agent-SafetyBench, R-Judge, and AgentDojo, federated FGLGuard exceeds the in-domain centralized ceiling on all three benchmarks without pooling any data---where unsupervised anomaly guards and local-only training fail. One guard federated across four different-domain operators comes within 0.03 AUROC of multi-domain centralization, while any single-domain guard collapses on the others. Live FGLGuard cuts AgentDojo's ground-truth attack-success rate by 43% at near-unguarded utility, zero API cost, and negligible capability loss.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.02055v1">Privacy Washing: Detecting Internal Contradictions in Privacy Policies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-09-02T03:33:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Thomas Brackin</p>
    <p><b>Summary:</b> Privacy policies may contain internal contradictions in which commitments are undermined by practices documented elsewhere in the same policy. We operationalize this phenomenon, privacy washing, through a four-stage pipeline: statement extraction, compatibility filtering and natural language inference screening, multi-model judge verification, and thematic analysis, with contradictions confirmed by majority vote of a three-model LLM panel. Applied to two corpora of website privacy policies, 123 collected in 2026 (OPPT) and 115 collected in 2015 (OPP-115), the pipeline finds the same category patterns recurring across the 11-year gap, with third-party sharing contradictions the majority of confirmed cases in each primary run, consistent with structural factors in policy composition rather than necessarily intentional deception. At least one panel-confirmed contradiction appears in 12.2% of OPPT companies (15/123; 9.8% excluding legacy pairs) and 36.5% of OPP-115 companies (42/115). A stability re-run seven months later, with a fully separated configuration (new extraction models, judges from three Chinese providers absent from both corpora, matched filters, no judge-submission similarity threshold), reproduces the OPPT prevalence under the original protocol (13.0% vs. 12.2%), finds sub-threshold pairs confirm at rates of the same order as those above (raising prevalence to 20.3% and 40.9%), and shows the third-party majority is panel-sensitive while the recurrence of the same category pairs is not. Two caveats govern all figures: panel verdicts are not validated against human expert judgment, so precision is unknown and prevalence figures are lower bounds; and the two primary runs used different filter configurations, so their prevalence difference is not interpretable as a corpus or era effect (the matched re-run reduces the gap to roughly twofold but does not eliminate it).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.01944v1">Privacy Amplification Without Independence: How Far Negative Dependence Carries the Guarantees of Poisson Subsampling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-01T23:20:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xujun Che, Depeng Xu</p>
    <p><b>Summary:</b> Poisson subsampling is the default sampler in differentially private optimization because its independence makes privacy amplification tractable. Practical systems, however, are moving toward structured participation: random allocation (balls-in-bins), per-epoch allocation, random check-ins, schemes widely believed to be at least as private as Poisson subsampling at the matched rate. We isolate the probabilistic mechanism behind this belief and delimit it exactly, for Gaussian mechanisms up to correlated-noise matrix mechanisms.
  (1) If the participation indicator vector is negatively associated (NA), then at every integer Rényi order $α\ge2$, exactly at all finite parameters, its remove-direction Rényi divergence is dominated by that of the marginal-matched independent scheme. For fixed gradient sequences, this extends to the mechanism level whenever the noise strategy's Gram matrix is sign-balanced, an $O(t^2)$-checkable condition.
  (2) The integer-order restriction is essential. For random allocation with $k=1$, we prove a linear law for the Rényi-difference criterion: at large $t$, dominance reverses for every $α<3/2$, including KL divergence, while the crossing order tends to $3/2$ independently of $σ$.
  (3) We also localize the known failure of rate-matched Poisson domination exactly: below $(1-q)^t$, the hockey-stick ordering reverses, so substituting the Poisson pair into composition machinery is unsound. An upper-tail argument yields a finite crossover $γ_\star$, connecting this threshold picture to the Rényi boundary at $3/2$.
  Together, these results give a substitution map for privacy accounting: when Poisson-based computations remain sound for structured participation, where they fail, and what sound alternatives cost in deployment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.02947v1">Privacy-Preserving Heterogeneous Multi-LLM Federated Inference for Cognitive Diagnosis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-01T21:07:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yagna Manasa Boyapati, Chong Yu, Tianyu Jiang, Justin Zhan</p>
    <p><b>Summary:</b> Significant challenges remain in AI-driven educational systems in balancing privacy preservation with accurate cognitive diagnosis. To overcome this, we propose a federated inference framework in which several commercial LLM APIs collaborate without requiring access to raw student data or proprietary model internals. Using multiple federated entities, such as LLaMA-3.3-70B, GPT-4o-mini, and Claude-3-Haiku, our framework builds upon a heterogeneous multi-LLM architecture. The predictions generated by these entities are combined with epsilon-local differential privacy by adding Laplace noise locally to each entity's prediction output before aggregation, while residual-based aggregation mitigates model heterogeneity. Our approach is predicated on an honest-but-curious trust paradigm in which API providers are presumed not to abuse submitted queries, and our differential privacy mechanism shields the published diagnostic results from external inference. We conduct rigorous privacy-utility analysis showing strong privacy guarantees with minimal accuracy loss, and extensive real-world evaluations across three educational benchmarks confirm the framework's practical usability and cross-domain generalizability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.01273v1">Position: Privacy Is a Claim, Not a Property of Synthetic Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-01T14:06:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiachen Zhao, Antonia Januszewicz, Taeho Jung</p>
    <p><b>Summary:</b> Synthetic data has become a common component of machine learning research. While widely adopted, its use in privacy-sensitive contexts has quietly shifted from a claim of residual inference risk under stated assumptions to an appearance-based property inferred from data generation itself. In this position paper, we argue that this shift reflects an implicit change in community standards for what counts as sufficient privacy evidence, rather than a misunderstanding of well-established privacy principles. Drawing on an empirical analysis of recent publications across major ML venues, we show that synthetic data is frequently used in privacy-sensitive settings without explicit articulation of threat models, inference risks, or falsifiable privacy claims. As a result, privacy assurance often remains implicit, difficult to verify, and unevenly distributed, with heightened exposure for rare and minority records. We argue for treating privacy as an explicit, evidence-based scientific claim and recommend that ML venues adopt norms requiring privacy-relevant assertions to be clearly scoped, testable, and contestable.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.01096v3">CRSF: Collusion-Resilient Privacy-Preserving Sensor Fusion with Byzantine-Robust Participation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-01T11:38:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chao Yin, Haihong Tian, Zheng Yang, Haibin Zhang, Fabio Massacci, Chenglu Jin</p>
    <p><b>Summary:</b> Privacy-preserving sensor fusion enables an untrusted server to compute an aggregate result over distributed sensor measurements without learning either individual inputs or the final output. Recent garbled-circuit-based protocols provide an efficient realization of this functionality in a sensor--server--client architecture, but remain vulnerable to sensor--server collusion and Byzantine manipulation of sensor participation. These weaknesses can compromise honest-sensor privacy, incorrectly exclude honest sensors, and corrupt the computed fusion result, thereby undermining the security guarantees expected from the protocol.
  We present CRSF, a collusion-resilient sensor-fusion protocol that addresses these weaknesses while providing privacy, correctness with explicit abort, and liveness. CRSF introduces a Practical Byzantine Fault Tolerance (PBFT)-based agreement phase for sensor submissions and uses server-specific, status-dependent label release with threshold protection of circuit-input labels. This design prevents any Byzantine server from unilaterally manipulating sensor participation and prevents any admissible sensor-server coalition from obtaining enough secret material to compromise honest-sensor privacy.
  We implement CRSF and compare its online execution time with the most relevant state-of-the-art baseline. Our Google Cloud evaluation measures the total computation and communication cost of the online protocol under fault-free and representative faulty executions. Across a range of fault-tolerant fusion circuits and up to 261 sensors, CRSF demonstrates a highly practical trade-off between robust security and protocol performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.00711v1">SoK: Motion Data Privacy in Extended Reality</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-09-01T04:40:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Azim Ibragimov, Alina Vasina, Uliana Polshcha, Eric D. Ragan</p>
    <p><b>Summary:</b> Extended Reality (XR) provides immersive, interactive 3D experiences. To enable these experiences, the devices must track user motion so the system can respond to actions such as grabbing, looking at, or moving an object. However, motion tracking has raised privacy concerns since it records a person's motion patterns. These motion patterns have been studied extensively across various fields (i.e., gait identification and profiling) and have been shown to reveal sensitive information. With the adoption of XR, these patterns became easier to record and obtain than ever. This creates a fundamental privacy tension: motion tracking enables core XR functionality yet requires users to compromise their privacy. Prior systematization-of-knowledge (SoK) studies on XR privacy have examined the field broadly, with motion-related research distributed across several privacy domains rather than treated as a distinct area of study. However, XR motion privacy has gained significant momentum since the prior SoK, with the literature nearly quadrupling in size and thereby warranting a dedicated systematization of this topic. This SoK examines 134 relevant papers on privacy concerns in motion patterns recorded by XR headsets, including how adversaries can obtain users' motion patterns, the inferences they can draw from them, and methods for protecting users. Based on this review, we synthesize a taxonomy of motion modalities, representations, and inference risks; develop an XR motion threat model; systematize the attack and defense approaches in the XR motion literature; identify gaps in the literature; and provide guidelines for future studies evaluating motion privacy mechanisms. Together, our SoK clarifies the state of XR motion privacy and provides recommendations for future evaluations.</p>
  </details>
</div>



<h2>2026-08</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.00492v1">The Privacy-Hallucination Tradeoff in Differentially Private Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-08-31T23:39:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Krithika Ramesh, Krishna Pillutla, Danish Pruthi, Anjalie Field</p>
    <p><b>Summary:</b> Both privacy and factual accuracy are paramount in high-stakes domains like healthcare. Concerningly, we uncover and investigate a privacy-hallucination tradeoff in differentially private (DP) language models. First, we empirically show that models pre-trained or fine-tuned with DP tend to produce more hallucinations than non-DP counterparts, with increased severity as the privacy budget grows stricter. Second, we investigate model properties driving this tradeoff, demonstrating that DP mechanisms flatten output distributions, potentially redistributing probability mass toward factually incorrect alternatives. Third, through experiments where we control fact frequency in training data, we characterize how information frequency can reduce hallucination risks in DP models. Overall, our findings underscore the need for more nuanced privacy-preserving interventions that offer rigorous privacy guarantees without compromising factual accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.00390v1">NeuroPriv: Adversarial Representation Learning for Privacy in Wearable EEG Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-31T21:19:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sarmistha Sarna Gomasta, Bhawana Chhaglani, Prashant Shenoy</p>
    <p><b>Summary:</b> Wearable EEG systems may expose sensitive information beyond their intended health function, creating substantial risks to neuroprivacy. In this work, we show that commonly used EEG features can reveal participant identity and demographic attributes in addition to supporting the intended cognitive task. Wearable EEG is increasingly being explored for cognitive monitoring, neurological assessment, and longitudinal digital-health applications, yet many systems assume that transmitting compact spectral or spatial features instead of raw EEG provides sufficient privacy protection. Using EEGMAT as a motivating case study, we find that compact EEG features achieve a balanced accuracy of 0.788 for cognitive-state classification while enabling gender, age, and subject-identity inference with balanced accuracies of 0.858, 0.789, and 0.692, respectively. We further show that privacy-aware representation learning preserves task performance at 0.781 while reducing these inference accuracies to 0.563, 0.467, and 0.206. These findings motivate purpose-limited representations and explicit privacy auditing in wearable neurohealth systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.31138v1">Scale Analysis and Shape Selection for the Generalized Gaussian Mechanism under Approximate Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> 
  <p><b>Published on:</b> 2026-08-31T17:44:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiang Zhang, Mohamedou Ould Haye, Yiqiang Q. Zhao</p>
    <p><b>Summary:</b> Differential privacy provides a rigorous framework for protecting private information, typically achieved by adding random noise to query results. The generalized Gaussian family is a flexible class of additive noise distributions indexed by the shape parameter $p$ and includes the Laplace and Gaussian distributions as special cases $p=1$ and $p=2$, respectively. This paper studies the privacy-feasible scale estimation and the shape parameter selection of the generalized Gaussian mechanism (GGM) under $(\varepsilon,δ)$-differential privacy. For a given sensitivity vector $Δ$ and $p\in[1,\infty]$, let $b(p)$ denote the smallest value of the scale parameter for which the mechanism satisfies this privacy requirement. In the one-dimensional case, $b(p)$ can be implicitly characterized by a system of equations. For vector-valued queries, we construct a computable upper approximation of $b(p)$ that preserves the privacy guarantee. Shapes are compared under a scale-homogeneous utility criterion, with the $m$-th absolute moment as the main example. We develop an interval-wise shape search algorithm with an approximation guarantee that can be made arbitrarily precise. We also establish the invariance of the optimal shape under rescaling of the sensitivity vector and characterize its limiting behaviour under high privacy limits. Computational experiments show that optimizing shape parameters can improve utility by reducing the variance of each coordinate by 5% to 20% across a variety of cases, with some cases showing even greater reductions, while maintaining the same level of privacy protection. Task-specific experiments further show that shape optimization can improve task-level utility, reduce attacker success, or achieve both.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.30473v1">Bounds on the Posterior-to-Prior Ratios for Inclusion Belief under Bounded Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-31T09:01:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jan Reiter Sørensen, Heidi Søgaard Christensen, Rasmus Rask Kragh Jørgensen, Martin Bøgsted</p>
    <p><b>Summary:</b> Differential privacy has become the standard for generating privacy-protected data releases. However, differential privacy does not translate intuitively to disclosure risk. In particular, it remains unclear how much an adversary's belief about an individual's inclusion in a dataset can change after observing a protected release. To address this question, we derive upper and lower bounds on the posterior-to-prior ratios of inclusion beliefs under bounded probabilistic and approximate differential privacy. By assuming a worst-case adversary with all-but-one auxiliary information, i.e., knowledge of all except for one of the participants in a dataset, we obtain bounds that apply to any adversary. Because these bounds may fail with non-zero probability, we study the corresponding failure probability for the Gaussian mechanism. We derive a theoretical upper limit on this probability and compare it with Monte Carlo estimates across a wide range of parameter settings. The observed failure rate is several orders of magnitude smaller than its theoretical upper limit, indicating that the latter is highly conservative. These findings suggest that the inferential privacy guarantees provided by differentially private mechanisms may be substantially stronger in practice than what is implied by the theoretical upper limit.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.30141v1">Balancing Privacy, Utility, and Safety in LLM Alignment through Preference Optimization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-31T01:46:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dishu Yang, Jingjing Liu, Jize Li</p>
    <p><b>Summary:</b> Preference optimization is widely used to align large language models with human preferences, but preference-data composition may also influence privacy-relevant memorization. We examine whether adding synthetic privacy-preference pairs to Direct Preference Optimization (DPO) is associated with lower canary-based memorization signals without modifying the objective or introducing a formal privacy mechanism. We propose Privacy-Pressure Preference Mixing (P3M), a data-composition protocol that varies the amount of privacy-preference data while keeping helpfulness and harmlessness preference data fixed. We evaluate a non-privacy Baseline and privacy-mixing ratios of 0.5, 1.0, and 2.0 using Gemma 3 270M-IT across five random seeds and validate the same four conditions using 4-bit-quantized Gemma 2 2B-IT across three seeds. Overall, under the tested conditions, privacy-preference mixing is associated with lower mean canary suffix log-likelihood proxy values across both model settings and lower aggregate membership-inference attack performance relative to the Baseline in the mixed-source 2B evaluation. Specifically, across the privacy-aware 2B configurations, the mean area under the receiver operating characteristic curve (AUROC) ranges from 0.596 to 0.629, and the mean area under the precision-recall curve (AUPRC) ranges from 0.541 to 0.575, compared with 0.804 and 0.790, respectively, for the Baseline. However, the reduction in membership distinguishability does not hold uniformly across data sources. Moreover, the relationship between the privacy ratio and harmlessness preference accuracy varies by model setting, whereas helpfulness preference accuracy remains broadly stable. These findings suggest that P3M should be viewed as a lightweight empirical protocol for examining privacy-utility-safety trade-offs rather than as a formal privacy guarantee or a defense against extraction attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.29674v1">Creation begins with understanding: LLMs as strategy designers for privacy-preserving tabular data synthesis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-30T09:16:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jinmeng Li, Quan Zhang, Hangting Ye, He Zhao, Firas Laakom, Dandan Guo, Jürgen Schmidhuber</p>
    <p><b>Summary:</b> Sharing tabular data in high-stakes domains is constrained by privacy regulations. Synthetic data offer a promising alternative, but deep generative models are costly to train and difficult to audit, while LLM-based methods often serialize records as text, obscuring tabular structure and exposing sensitive data. We introduce Tabular Synthesis Strategy Designer (TabSSD), which uses an LLM to design synthesis procedures rather than directly generate records. TabSSD provides the LLM with tree-derived summaries of variable dependence rather than raw records, which produces Python programs for local execution and evaluation. Across twelve datasets, TabSSD strikes a favourable balance among statistical fidelity, predictive utility, and empirical privacy risk, achieving the best average rank across six metrics among ten methods. Moreover, it substantially reduces local computation and token consumption relative to the compared methods. By enabling human-guided refinement and eliminating user-side model tuning, TabSSD lowers the expertise and infrastructure barriers to transparent tabular data synthesis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.29111v1">Auditing and Mitigating Privacy Leakage in Cloud-Edge Collaborative Decoding</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-08-29T07:40:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kejia Zhang, Tianyuan Zou, Zixuan GU, Yang Liu</p>
    <p><b>Summary:</b> Applications such as personalized assistance and proprietary document analysis require large language models (LLMs) to generate outputs from private data. Yet powerful LLMs typically cannot be deployed on the resource-constrained devices where private data resides, and uploading private data to cloud-hosted LLMs exposes sensitive information. Recent work addresses this tension with a cloud-edge collaborative decoding paradigm, where private data are kept on the edge with a small language model (SLM) producing next-token distributions, which are fused with predictions from a cloud LLM operating solely on public data. In this paper, we systematically analyze the privacy risks of such a paradigm with a novel evaluation framework using constructed QA datasets, which show that such collaboration can expose substantial private-context information. To address such privacy leakage, we propose CoVeil, a defense mechanism which dynamically optimizes transmitted signals to suppress leakage during decoding time while preserving the collaborative quality. Extensive evaluations demonstrate that CoVeil consistently improves the privacy-utility trade-off over existing baselines by reducing data leakage by up to 87.2%, with minimal accuracy loss.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.28950v2">The Web-CLI: Verifiable Privacy for Tools, Models, and Inference Engines in the Browser</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2026-08-28T23:40:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tejaswi Gowda</p>
    <p><b>Summary:</b> We introduce the Web-CLI, a novel application architecture deploying powerful computational capabilities (command-line tools compiled to WebAssembly, models run through client-side inference runtimes, and GPU-accelerated engines) as zero-install, offline-capable browser applications that preserve full underlying capability. Unlike web-based alternatives that require server-side processing and expose user data to third parties, Web-CLI applications execute entirely on the client, providing a verifiable privacy guarantee by architecture rather than policy. We define the pattern and its four properties: fidelity, progressive disclosure, offline-first, and zero egress. We present four reference implementations across distinct domains: ffmpeg-webCLI, a browser-based video editor built on FFmpeg; whisper-webCLI, speech transcription via Transformers.js; chat-webCLI, WebLLM-based language model inference; and 3mf-webCLI, a deterministic tool segmenting 3D models into multi-material files for physical 3D printing. Together they demonstrate that the pattern generalizes across deterministic media processing, neural speech recognition, LLM inference, and geometry processing with a physical output, and we outline how it extends to AI-native interfaces in which a local language model becomes the command surface itself. We further report early, anecdotal signs of independent reuse by third-party tools, suggesting the pattern generalizes beyond its reference implementations. We evaluate the primary implementation against native FFmpeg on performance and feature parity, and argue that progressive disclosure lowers the barrier for non-technical users. We argue that for applications processing sensitive user data (medical, legal, journalistic, or personal), the Web-CLI should be the default architecture, as it makes data locality an independently verifiable technical property rather than a policy promise.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.28934v1">Revisiting the Provable-Auditable Privacy Gap of DP-SGD</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-28T23:07:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Saloni Modi, Srivi Balaji, Yusong Zhu, Gautam Kamath, Kevin Tian</p>
    <p><b>Summary:</b> Differential privacy (DP) has traditionally been used to provide theoretical upper bounds on an algorithm's stability to changing its training data. In modern private machine learning applications, achieving strong tradeoffs between utility and theoretical privacy is challenging, and thus one may optimistically hope that existing theoretical privacy analyses are loose. Recent work on privacy auditing has adopted a dual viewpoint, instead lower bounding the true privacy of an algorithm by constructing empirical distinguishing events. The auditing literature has thus far yielded a pessimistic outlook on the looseness of theoretical privacy bounds for DP-SGD, the de facto private training method in modern ML, as nearly-matching empirical lower bounds have been achieved under various threat models [NHSBTJCT23, AC24, CBP25].
  In this work, we propose the empirical privacy lower bound of an algorithm as a concrete metric to optimize for, complementary to the theoretical upper bound. We give a lightweight defense framework that generically augments optimization methods in the ML pipeline to have significantly-improved empirical privacy on standard benchmarks. Moreover, we show that our framework comes at no theoretical privacy cost when augmenting DP-SGD, unlike previously-proposed defenses against membership inference attacks. We evaluate our defense against a broad range of audit constructions, models, and datasets to demonstrate its flexibility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.28198v2">Performative Privacy: When Differential Privacy Maximizes Utility</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> 
  <p><b>Published on:</b> 2026-08-28T11:13:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Uddalak Mukherjee, Edwige Cyffers, Yann Chevaleyre</p>
    <p><b>Summary:</b> Privacy-preserving learning is often motivated by the idea that protecting users' data can preserve trust and thus participation, improving utility in the long term. However, this claim has not been formalized so far. In parallel, performative learning provides a framework for studying learning systems whose deployment affects the data they later observe. In this work, we bring these two perspectives together and introduce performative privacy, where data leakage reduces future participation. We study a simple model where agents repeatedly contribute data for mean estimation but may leave the system when their data is leaked. Privacy is implemented through differentially private mechanisms, creating a trade-off between estimation noise and future participation. We show, through a theoretical study of the dynamics and numerical experiments, that a finite privacy budget can outperform non-private estimation in the long term when the feedback loop between leakage and participation is sufficiently strong. This provides first evidence that differential privacy can be optimal not only as a protection mechanism, but also from the perspective of long-term utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.27954v2">Not to Break, but to Attest: Adversarial Probes for Privacy-Preserving LLM Verification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-28T05:51:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Cameron Wilding, Mina Shaker, Fatemeh Ganji</p>
    <p><b>Summary:</b> Post-deployment changes to large language models can alter behavior while leaving routine outputs largely unchanged, creating a challenge for AI governance when model weights are proprietary. We present a privacy-preserving zk-SNARK-based audit framework that searches for probes designed in the spirit of adversarial examples to amplify logit drift between an approved model and a modified deployment. Our framework explores complementary probe families under different access models. Token-based probes operate in a black-box setting and require only the input interface, tokenizer, and vocabulary. Embedding-based probes require gray-box access to the embedding interface. Stress probes rely on additional interface capabilities but do not require full white-box access to model weights or architecture. This range allows probe selection to balance sensitivity, access requirements, and deployment cost. We evaluate probe constructions across LLM architectures, model-tampering scenarios representative of post-deployment attacks, and GPU platforms. Importantly, our experimental results demonstrate that token-based probes consistently deliver the strongest mean sensitivity across models and GPU platforms, although operating in a black-box setting. Our Groth16 zk-SNARK workflow remains practical as the probe set scales from 1 to 50, where proving time increases from 1.02 to 1.78 seconds, verification remains near 0.84 seconds, and proof size remains constant.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.27914v1">A User-Centric Context-Aware Permission Governance Framework for Privacy Control in Default Mobile Applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-28T04:41:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Asmau Yetunde Adeniran, Adeniran Kolade Ademuwagun, Fatimah Adamu-Fika, Samaila Musa Abdullahi, Freeman Bitrus, Fortune Daberechi Ifeanyi</p>
    <p><b>Summary:</b> Mobile operating systems provide runtime permission controls intended to improve user control over sensitive data. However, default or pre-installed applications are deeply integrated into the system, may operate with elevated privileges, and are difficult for users to scrutinize. Existing permission models generally grant persistent or temporary access for an application session without distinguishing among individual features, leaving users uncertain about when and why data are accessed. This paper presents a context-sensitive, user-focused permission governance framework for default mobile applications. It introduces a feature-based authorization option, "Allow When Needed," that restricts access to the functionality requiring the data rather than the entire application session. A weighted scoring system estimates the privacy implications of user choices based on permission sensitivity and authorization type. A web-based simulation platform was developed to model 30 realistic permission-request situations across six commonly used default application types and support controlled early-stage evaluation before native implementation. The exploratory assessment combined a cross-sectional survey of 104 respondents examining permission awareness and behavior with formative usability testing involving eight participants interacting with the prototype. Survey findings indicate that users do not consistently examine default-application permissions and prefer contextual explanations before granting access. The results provide preliminary evidence that context-aware permission governance can improve user understanding and decision clarity. This simulation-based study represents an initial step toward evaluating feature-level authorization and privacy-feedback mechanisms before native mobile deployment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.27782v1">Memorization Is Not Extraction: Tight Differential-Privacy Bounds and Audit Blind Spots</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-27T23:28:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xujun Che, Depeng Xu, Shuhan Yuan</p>
    <p><b>Summary:</b> Memorization in large language models is measured through a zoo of definitions whose formal relations are unknown, and differential privacy (DP) is treated as a proxy against all of them at once. We pin down the exact DP constant for the two that carry the practical weight, counterfactual memorization and adaptive extraction, and show that they do not control each other. Under $f$-DP, every adaptive extraction protocol with list budget $m$ succeeds with probability at most $1-f(κ)$ for the oblivious baseline $κ$, and the bound is tight on a dense set of baselines: DP uniformly controls extraction exactly up to a threshold in how well the secret can be guessed a priori. Min-entropy certifies that baseline distribution-free, since $H_\infty\geε\log_2 e+\log_2(m/τ)$ holds extraction below a risk level $τ\le1/2$ under pure $ε$-DP for every prior, and is exact on uniform priors. On the memorization side, $f$-DP caps the counterfactual memorization of any bounded score at an advantage functional $η(f)$, equal to $\tanh(ε/2)$ under pure DP; for $k\ge2$ duplicated copies the naive $ε\mapsto kε$ bound $\tanh(kε/2)$ is unattainable, the exact constant being a closed-form staircase attained by geometric noisy counting. That cap is attained inside the local score class used in practice, and it is there that the two measures separate: one mechanism is memorized yet unextractable, another fully extractable yet exactly invisible to every loss-based score. The two-sided blind spot this opens for loss-based auditing and unlearning verification survives on billion-parameter models: a reserved-trigger release is recovered verbatim from one prompt while the audits practitioners deploy certify it clean.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.27766v1">Revisiting Continuous Noise Sampling for Multi-Party Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-27T22:57:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yucheng Fu, Tianhao Wang</p>
    <p><b>Summary:</b> Combining secure multi-party computation (MPC) with differential privacy (DP) enables multiple parties to release aggregate statistics without a trusted curator, and the core primitive is the protocol to sample noise from a continuous distribution under finite-precision arithmetic. In this paper, we revisit the continuous noise sampling protocols and present several improvements in both security and efficiency.
  We start by identifying a vulnerability in widely used sample-and-scale constructions. We demonstrate that the scaling operation in arithmetic circuits confines the noise to a sparse, publicly known set of values, so that an adversary can observe the released noisy queries and decide which dataset produced them. As concrete demonstrations, we instantiate attacks on two systems employing such ``flawed'' sampling protocols: Orchard (OSDI'20) for DP secure aggregation and DP-BREM$^+$ (USENIX Sec'25) for DP federated learning. We report a near-$100\%$ attack success rate on both systems, under any noise scaler $s\geq 2$ used in practice.
  The leakage we reveal is intrinsic to the scaling operation, and direct repairs either substantially sacrifice utility or add significant precision bits to make the sampling more expensive. To address the security and efficiency issues together, we turn to discrete sampling at the granularity of individual biased bits. We make several optimizations to the sampler and prove its security. Our implementation achieves $4\times \sim 612\times$ speedup over existing secure discrete samplers and orders-of-magnitude speedup over the insecure sample-and-scale paradigm, with negligible utility loss compared to the ideal continuous mechanism.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.27108v1">SecureDrive-FL: Joint Differential Privacy and Gradient-Aware Selective Homomorphic Encryption for Federated Driver Monitoring</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-27T13:24:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Baran Can Gül, Hanuma Siddhartha Tunuguntla, Anjana Arvind Naik, Abhishek Vijay Potekar, Nasser Jazdi, Michael Weyrich</p>
    <p><b>Summary:</b> Federated Learning (FL) enables privacy-aware distributed training, yet gradient updates remain exploitable: Man-in-the-Middle (MitM) interception exposes updates in transit, while model poisoning corrupts global convergence. We first introduce GASHE (Gradient-Aware Selective Homomorphic Encryption), a novel selective encryption strategy that dynamically identifies and encrypts only the gradient components exceeding a DP-calibrated sensitivity threshold, rather than encrypting all parameters uniformly as in static layer-based or full-parameter CKKS schemes. Building on GASHE, we introduce SecureDrive-FL, a federated driver monitoring framework that couples DP-SGD with GASHE to create the first closed-loop DP+HE privacy pipeline: DP-SGD calibration parameters directly derive the GASHE encryption mask, unifying training-time privacy and communication-time confidentiality. Evaluated on a ten-class distracted driver classification task under non-IID federated splits, SecureDrive-FL matches DP-SGD alone's poisoning resistance (73.6% vs. 74.0% accuracy, 3.9% Attack Success Rate for both) while additionally withstanding MitM interception, where DP-SGD alone collapses to near-random accuracy (78.2% vs. 10.4%), all under only approx. 8--10% additional runtime overhead relative to DP-SGD alone---under DP-SGD noise injection with per-round privacy parameter epsilon_0=4.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.27066v1">Beyond Classification: Task-Dependent Learnability under Privacy-Motivated Image Transformations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-27T12:52:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Leon Ranke, Wolfgang Hübner, Ronny Hug, Michael Arens, Jürgen Beyerer</p>
    <p><b>Summary:</b> Privacy-Enhancing Technologies (PETs) in computer vision often rely on noise or image perturbations to protect visual data while securely processing it, creating a trade-off between task performance and protection. This trade-off is commonly evaluated using image classification, which primarily captures semantic separability and remains robust despite significant geometric, spatial layout or local boundary alterations. As a result, it is too simplistic as a proxy for generic vision tasks. Exhaustive downstream-task evaluation, however, is computationally expensive because models must often be trained for each PET transformation and parameter setting. We therefore propose a compute-aware multi-task protocol for evaluating PETs in model training. It combines lightweight proxy tasks that target complementary aspects of visual structure while remaining simple and fast to compute. Across irreversible privacy transformations, key-based block primitives, and learnable image encryption schemes, we demonstrate that PETs with similar classification accuracy can differ substantially on other tasks. The outcomes highlight the need for PET evaluation protocols that move beyond classification-only reporting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.27037v1">Neighborhood Watch: Privacy Risks in Seeded Local Combination Synthetic Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-27T12:22:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hadrien Lautraite, Tristan Allard, Anne-Sophie Charest, Jean-François Rajotte, Sébastien Gambs</p>
    <p><b>Summary:</b> Synthetic data is seen as a promising solution for sharing data in sensitive contexts. However, recent work on privacy attacks have shown that there are still significant residual risks, especially for synthetic data generations methods that are not based on formal approaches such as differential privacy. In this paper, we investigate the privacy risks associated with local combination approaches for generating synthetic data in which synthetic profiles are built by combining real neighbouring profiles. More precisely, we focus on three methods from this family, namely SMOTE, Simulant and Avatar, which have been recently used as a way to share 'anonymised data' in the healthcare domain. In particular, we conduct an extensive privacy analysis through a diverse set of attacks: membership inference, linkage and reconstruction attacks. Our results demonstrate substantial privacy leakage for all three methods, raising serious doubts about whether their outputs should be regarded as anonymous in practice.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.26655v1">When Privacy Hurts Mergeability: Geometry-Aware Model Merging under Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-27T06:08:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jin Liu, Junkang Liu, Ning Xi, Yinbin Miao, Dawei Wei, Ke Cheng, Jianfeng Ma</p>
    <p><b>Summary:</b> Model merging promises to construct a single multi-task model from independently fine-tuned task models without accessing the original task data. This makes it attractive when task data cannot be centralized, but released task models may still leak private fine-tuning data. Differential privacy (DP) provides a principled mechanism for limiting such leakage, yet its effect on model merging remains poorly understood. In this paper, we study the geometry of differentially private model merging and identify two geometric obstacles that make private task models difficult to merge: \emph{local sharpness}, which makes task losses sensitive to the parameter displacement induced by merging, and \emph{reference drift}, which measures the displacement of private task models from the shared pretrained initialization and amplifies cross-task interference. Based on these observations, we propose \textbf{DP-Merging}, a geometry-aware framework that improves the mergeability of differentially private task models. DP-Merging uses a DP-compatible sharpness-aware objective to guide each private task model toward flatter loss regions, and a reference-based alignment regularizer to keep task models close to the shared pretrained initialization. We derive a merge-gap upper bound showing that reducing local curvature and reference drift tightens the bound on the loss increase induced by merging. Experiments on vision and language tasks across multiple privacy budgets show that DP-Merging consistently improves private merged-model performance while preserving the privacy guarantees of the underlying DP fine-tuning procedures.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.26324v1">Privacy Without Regret: Differentially Private Inference-Time Alignment</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-26T18:56:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ishi Jain, Nandini Bhattad, Sayak Ray Chowdhury</p>
    <p><b>Summary:</b> Best-of-N (BoN) sampling is the simplest and most widely deployed inference-time alignment strategy, but it suffers from two distinct problems: reward hacking, in which the selected response exploits errors in the proxy reward model, and the absence of any privacy protection for the sensitive human preference data used to train that reward model. We show that a single intervention-adding calibrated noise to reward scores before selection-resolves both. Our first result, Private Best-of-N (PrivBoN), establishes that Gumbel noise at an appropriate scale simultaneously provides $ε$-differential privacy and implements KL-regularized alignment. Whenever the privacy budget exceeds a critical threshold $ε^*$, the privacy-mandated noise is the regret-optimal regularization, and privacy imposes zero additional alignment cost-matching the information-theoretic skyline of Huang et al. (2025). Because $ε^*$ depends on an unknown coverage coefficient, we introduce Private Inference-Time Pessimism (PrivITP), which combines $χ^2$-regularized rejection sampling with a two-phase Gaussian mechanism. PrivITP achieves ex-post $(ε,δ)$-DP with a privacy cost independent of the number of responses $n$, cleanly decouples the regularization parameter from the privacy parameter, and attains the skyline up to a noise-inflation term. Experiments across several language models, datasets, and reward models confirm our results: PrivBoN and PrivITP are scaling-monotonic (unlike BoN, which degrades past a critical $n$), and PrivITP matches or outperforms PrivBoN at equivalent privacy levels, with the largest gains in the strong-privacy regime.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.25750v1">Toward Interpretable Privacy Guarantees in Face-Swapping Anonymization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-26T12:59:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vishnu Bondalakunta, Arman Zareian Jahromi, Shuangqing Wei, George Amariucai</p>
    <p><b>Summary:</b> Face-swapping has emerged as a promising approach to facial privacy protection, replacing a target individual's appearance with that of a donor while preserving non-facial context. The resulting images visually resemble the donor, and face recognition systems tend to suppress the target's match scores -- ostensibly satisfying privacy requirements. Empirical evaluation across a range of face-swapping models, however, reveals that significant target identity leakage still occurs. This raises a deeper question: why does leakage occur, and can it be predicted? We propose a linear stochastic model that treats face-swappers as transformations on the space of identity embeddings, providing an interpretable account of the leakage mechanism. The model is fit to empirical observations and used to derive testable predictions. The aim is to ground privacy assessments in principled, interpretable analysis, thus making formal privacy guarantees explainable -- and perfectible -- rather than purely observational.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.25727v1">Are LLM-Enhanced GNNs Privacy-Safe?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-26T12:42:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Longzhu He, Zelang Wen, Chaozhuo Li, Sen Su</p>
    <p><b>Summary:</b> Large language models (LLMs) have recently advanced graph neural networks (GNNs) by enriching node representations with semantic information, giving rise to LLM-enhanced GNNs that achieve substantial performance gains. However, their vulnerability to privacy attacks, in which adversaries infer sensitive information from model outputs, remains largely underexplored. To bridge this gap, we present a systematic evaluation of privacy risks in LLM-enhanced GNNs through a unified framework consisting of five stages: (1) dataset preparation, (2) victim model training, (3) privacy attack, (4) risk assessment, and (5) defense analysis. Specifically, we conduct experiments on six real-world text-attributed graph datasets covering diverse domains. We consider six representative privacy attack methods targeting three fundamental threats, namely link, label, and membership inference, and construct 42 victim model configurations by combining multiple LLM-based feature enhancers with representative GNN backbones. Extensive experiments show that, despite their utility improvements, LLM-enhanced GNNs consistently exhibit increased vulnerability to privacy attacks compared to shallow text representation baselines. Further analysis reveals that semantic enrichment amplifies link-, label-, and membership-related signals in the embedding space, making them more exploitable by inference attacks. Finally, we evaluate differential privacy as a defense strategy and show that, while it can partially mitigate privacy risks, it introduces significant utility degradation, highlighting a fundamental privacy-utility trade-off in LLM-enhanced graph learning. Overall, this work provides a comprehensive understanding of privacy risks in LLM-enhanced GNNs and offers practical insights for developing more secure and trustworthy graph learning systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.24847v1">On the privacy cost for dependent Gaussian data: spectral density estimation under local differential privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">
  <p><b>Published on:</b> 2026-08-25T17:34:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yann Issartel, François Roueff</p>
    <p><b>Summary:</b> We study the fundamental problem of estimating the dependence structure of a centered stationary Gaussian process under local differential privacy (LDP). In this setting, the spectral density characterizes the dependence structure of the data and is the quantity to be estimated. Our main contribution is to close the open $α^2$-versus-$α^4$ gap between the previously known lower and upper bounds on the minimax rate. Specifically, we establish a minimax lower bound showing that, over Sobolev-type classes of spectral densities, the effective sample size in the high-privacy regime is $Nα^4$, rather than the usual $Nα^2$ arising for independent observations. This additional privacy cost is caused by the temporal dependence between the observations rather than by their marginal distributions. The proof relies on a contraction bound for privatized dependent Gaussian observations. Our second contribution is a matching upper bound, free of the polylogarithmic losses present in previous work. Rather than applying a generic privatization scheme to classical estimators, we construct a problem-specific procedure attaining the rate identified by our lower bound. Beyond closing the gaps in spectral density estimation, we apply the tools developed for this problem to several related questions. We (i) close the logarithmic gap for fixed-lag autocovariance estimation, (ii) show that the $α^4$ cost arises locally around every spectral density bounded away from zero, and (iii) establish that classical asymptotic equivalence with an independent Gaussian experiment generally fails under LDP.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.24957v1">ToolMinimize: Auditing and Rewriting LLM Agent Tool Calls to Minimize Privacy Exposure</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2026-08-25T03:48:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenbiao Li, Yuqiao Xu</p>
    <p><b>Summary:</b> LLM agents routinely include privacy-sensitive data (PSD) in tool call arguments beyond what the invoked tools require, crossing trust boundaries to third-party services on every invocation. A controlled measurement on three production LLMs (GPT-4o, Claude 3.5 Sonnet, Llama-3.3-70B) shows that 81--88\% of tool calls include unnecessary PSD under default prompts; explicit privacy instructions still leave 36--76\% over-sharing. Existing defenses gate calls (allow/block) or label flows (information-flow control) but cannot \emph{rewrite} argument values, and PII detection tools miss implicit PSD like ``Memorial Sloan Kettering'' (a hospital name that implies a diagnosis). We present \system{}, a middleware that intercepts tool calls and rewrites their arguments to the minimum data necessary for tool functionality, combining schema-aware necessity analysis with four operations: removal, generalization, substitution, and truncation. Live validation on 307 tool calls across the three LLMs above reduces privacy cost by 81.2--92.0\% at 100\% argument-level task validity (TOST equivalence $p{<}0.001$ at $Δ{=}1.0$); on 25 unannotated Model Context Protocol (MCP) schemas, by 79.0\% with no \texttt{minimum\_necessary} metadata. An optional LLM content-necessity layer strips task-irrelevant PSD from otherwise-necessary free-text fields, raising live-LLM reduction to 85.1--95.6\% and author-schema reduction from 71.1\% to 90.9\%. Median latency is 1.77\,ms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.23382v2">Spectrum-Aware Bounds on Invertibility for Privacy-Enhancing Instance Encoding</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-24T15:30:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Seokjin Hwang, Yuting Li, Kiwan Maeng</p>
    <p><b>Summary:</b> Instance encoding is a popular empirical technique for privacy enhancement when sharing data to an untrusted server. It transforms sensitive data through an encoding process before sharing, with the hope that the encoding process retains utility but makes it hard to reconstruct the original data. However, most work offers no theoretical guarantee that the encoding process is actually irreversible. A recent work derived a mean-squared error (MSE) bound limiting any adversary's reconstruction accuracy, offering one of the first theoretical results in this domain. This bound, however, has three critical limitations: it is often too loose, only works with randomized encoders (excluding many deterministic encoders practitioners use), and only bounds MSE. We introduce a family of new bounds that (1) are tighter, (2) applicable even to fully deterministic encoders, and (3) can extend beyond MSE to other norm-based similarity metrics, by properly accounting for the encoder's spectral structure. We evaluate our bounds across a range of encoders, datasets, and attacks, showing they hold consistently and improve upon the existing bound.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.23012v1">Misanthrope: A Privacy-Preserving Keypoint Detector</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-08-24T09:14:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Francesco Vultaggio, Predrag Djindjic, Markus Gerke, Sebastian Tschiatschek, Phillipp Fanta-Jende</p>
    <p><b>Summary:</b> Image matching is a core component of applications such as Simultaneous Localization and Mapping (SLAM), Visual Localization, and Structure from Motion (SfM). However, the local image features central to this task are vulnerable to inversion attacks, which enable adversaries to reconstruct privacy-sensitive scene content from local features. These attacks pose a particular threat in distributed computing scenarios where the pre-computed features leave edge devices to be processed by remote servers. In this work, we introduce Misanthrope, a novel privacy-preserving keypoint detector trained through self-distillation to avoid detecting keypoints on people---a predominant source of privacy-sensitive content in most localization scenarios---thus mitigating inversion attacks at the source rather than through post-hoc obfuscation. We demonstrate how inverted images from traditional feature detection pipelines can be used to detect and re-identify people in the scene, while Misanthrope is able to mitigate these attacks. Furthermore, Misanthrope maintains image matching performance on par with the state of the art and even surpasses it in challenging settings where people act as distractors, such as phototourism and in-the-wild odometry. On the Image Matching Challenge 2021 Phototourism test set, Misanthrope is the top-performing sparse feature extractor in 7 out of 9 scenes. We make our model and its evaluation script available here: https://github.com/fratopa/misanthrope</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.22987v1">The Anonymity Gap: Understanding Real Privacy in Shielded UTXO-based Protocols for DeFi</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-24T08:50:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hanze Guo, Stefanos Chaliasos, Yebo Feng, Jiahua Xu</p>
    <p><b>Summary:</b> Shielded UTXO-based protocols are becoming a core form of privacy infrastructure for DeFi. Unlike mixers that organize privacy mainly around deposits and withdrawals, these protocols allow assets, once inside the shielded pool, to continue moving and being re-spent within the hidden state, and to become public only when users withdraw or interact with public DeFi protocols. Their anonymity is therefore no longer a flat pool-size problem, but a provenance problem that propagates across the note/UTXO, proof, and transaction layers. Yet, a unified analysis framework for this setting is still missing. We propose a layered system model and an analysis pipeline that uses prior history as the temporal baseline, applies cumulative pruning and cross-proof propagation to each proof's Commitment Set, and recursively traces the survivors through historical hidden-state transitions to derive the final transaction-level Anonymity Set Size.
  We evaluate our methodology on the complete on-chain histories of all four Railgun production deployments and five independent Hinkal pools across six EVM chains, analyzing 186,356 unshielding spend transactions. Using only public protocol traces and constraints, our non-heuristic analysis yields mean Anonymity Set Size reductions of 40.1%-59.0% relative to each deployment's temporal baseline; 3,679 transactions retain at most 10 addresses, including 1,228 singletons. Public token constraints are the strongest and most stable source of pruning in both protocols, while the effects of tree number, proof roots, and value constraints vary with protocol design and historical state. Together with representative cases, these results reveal interpretable anonymity-loss patterns and implications for user behavior and future protocol design.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.22645v1">Obscura-PQ: Post-Quantum Privacy-Preserving Protocol for the Algorand Blockchain Using Lattice-Based Linkable Ring Signatures</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-23T23:03:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Navid Azimi</p>
    <p><b>Summary:</b> Public blockchains expose the complete transaction graph, and the privacy protocols deployed to obscure it rely almost exclusively on elliptic-curve cryptography, whose discrete-logarithm foundations fall to Shor's algorithm. Because ledgers are immutable, every anonymity set published today under classical assumptions can be retroactively deanonymized by a future quantum adversary. Transitioning to post-quantum alternatives remains challenging, as strict smart-contract resource limits prohibit native on-chain verification of computationally intensive post-quantum proofs. To address these challenges, we present \emph{Obscura-PQ}, a decentralized, non-custodial post-quantum privacy protocol that verifies natively on the Algorand blockchain. Its core is a setup-free lattice linkable ring signature over the cyclotomic ring $\mathcal{R}_q = \mathbb{Z}_q[X]/(X^{512}+1)$. A deposit is a Ring-SIS binding commitment to a short secret; a withdrawal proves knowledge of a ring opening via an AOS/Borromean-style challenge chain over two response-sharing linear relations with rejection-sampled short responses, while publishing a deterministic Ring-LWE serial number for double-spend detection. We reduce double-spend soundness and linkability to Ring-SIS, theft resistance to Ring-SIS for honestly generated deposits, and anonymity to Ring-LWE and an explicit decisional linking assumption in the classical random-oracle model. To overcome strict on-chain opcode and storage limits, Obscura-PQ evaluates verification relations entirely in the NTT domain. We split forward NTTs across opcode-pooled execution phases and stream oversized proofs through refundable box storage, enabling $O(1)$ membership and double-spend checks. We provide a complete Algorand testnet implementation, demonstrating native on-chain verification of a post-quantum privacy protocol under strict smart-contract limits.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.22185v1">Residual Privacy Budgeting with Weighted Scarcity Allocation for Online Query Answering</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2026-08-23T02:48:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mina Khoshmehr, Fernando Beltran</p>
    <p><b>Summary:</b> In many practical deployments of differential privacy, queries do not arrive all at once. We study online differentially private query answering under a finite zero-concentrated differential privacy (zCDP) contract. In this setting, queries arrive sequentially, carry different accuracy thresholds, and may overlap with information already released. We formulate this setting as residual privacy budgeting: for each arriving query, the mechanism first credits reusable support from previous DP outputs and then spends new budget only on the remaining support required to satisfy the current threshold. The controller separates feasible cases, where the minimal residual support is allocated exactly, from scarcity cases, where a weighted shortfall-conservation optimiser assigns limited support according to query difficulty. We define the weight using the Query Influence Factor (QIF), a diagnostic signal for query difficulty and instability rather than query importance. For scalar Gaussian exact reuse, inverse-variance fusion justifies additive support. We prove zCDP composition, residual minimality, 1-competitiveness against the offline optimum in the feasible regime, and avoidable expenditure for allocators that ignore released history. A scarcity impossibility result shows that no online allocator can guarantee a competitive ratio better than 1/n in threshold satisfaction, contextualising the QIF scarcity layer as a design choice for an inherently hard online problem.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.21773v1">Privacy Preserving Semantic Communications in Wireless Edge Networks with Vision Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2026-08-22T04:42:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haoran Chang, Mingzhe Chen, Qianqian Zhang</p>
    <p><b>Summary:</b> Semantic communication has emerged as a promising paradigm for next-generation wireless systems by transmitting high-level semantic features rather than raw bits. However, collaborative devices and multimodal transmission increase privacy risks because sensitive information may leak through inter-device semantic fusion and cross-modal representations. To address this issue, we propose a privacy-preserving semantic communication framework for wireless edge networks. Leveraging a vision-language model (VLM), the framework extracts textual semantics from images and identifies privacy-sensitive entities using a privacy database maintained only at the edge server. Before image transmission, each device removes the identified private regions while preserving useful semantic content. The server then reconstructs the removed regions from the received masked images using textual embeddings and VLM-based semantic priors. To protect textual information, we design an encrypted semantic-channel transceiver using physical-layer keys generated from reciprocal wireless channels, without pre-shared keys. We also introduce a semantic information bottleneck to suppress redundant information across multiple devices. The framework is evaluated against a strong model-aware adversary that can intercept wireless transmissions and access edge-device model parameters but not server-side data. Simulation results show that the proposed method reduces privacy leakage by more than 50% compared with a semantic communication scheme without privacy protection, while the authorized server achieves a 48% improvement in perceptual reconstruction quality over the adversary. The estimated mutual information between transmitted representations approaches 0 bit, indicating effective suppression of cross-device semantic redundancy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.21209v1">Personalized Privacy Control in LLMs via Attention Head Intervention</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-08-21T15:22:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Junseok Kim, Nakyeong Yang, Kyomin Jung</p>
    <p><b>Summary:</b> The rise of agentic AI enables LLMs to access diverse user data, raising critical privacy concerns. Prior work on contextual privacy studies whether LLMs regulate information disclosure according to context-dependent norms. However, acceptable disclosure boundaries may vary across users even within the same context. To address this limitation, we introduce \textit{personalized privacy}, which incorporates user-specific disclosure preferences into privacy control. We further present P3Bench~(\textbf{P}ersonalized \textbf{P}rivacy \textbf{P}reservation \textbf{Bench}mark), a novel benchmark extending contextual privacy policies with personalized disclosure policies. Experiments show that prompt-based policies fail to reliably enforce personalized privacy policies, with Qwen2.5-7B and Gemma3-4B showing average policy ignorance ratios of 51.25\% and 74.28\%, respectively. Finally, to address this problem, we propose \textsc{Repair}, a robust inference-time attention head intervention method that adjusts disclosure behavior toward policy-consistent responses. Our method significantly improves adherence to user-specific privacy preferences by reducing cases where the model fails to follow the given policy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2608.21205v1">Workplace Surveillance and Insider Threat Risk Management: Legal Limits and Privacy Harms</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-08-21T15:20:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haywood Gelman, John D. Hastings, Suvineetha Herath, Quentin Covert</p>
    <p><b>Summary:</b> Workplace surveillance is used by organizations to protect corporate assets and monitor employee productivity. This research presents two central arguments on workplace surveillance: although surveillance serves legitimate organizational purposes, over-surveillance can violate legal requirements and data privacy principles; and a primary security objective of workplace surveillance is the detection of insider threats (InT). InT are comprised of individuals with authorized resource access whose intentional or unintentional actions may damage or compromise corporate assets. This paper investigates InT personas to understand behavioral and psychological detection criteria. Employee surveillance tools and techniques are reviewed to characterize the employee surveillance landscape. Workplace privacy laws, examples of over-surveillance, and the resulting privacy harms are addressed. The review identifies research gaps related to over-surveillance, including the generation of excessive alerts that may obscure meaningful InT indicators. The paper concludes with recommendations to improve workplace surveillance transparency, implement InT training programs to improve organizational detection capabilities, and tune InT tools to detect relevant psychological and behavioral indicators.</p>
  </details>
</div>

