
<h2>2026-05</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.01386v1">GuidaPA: Privacy-Preserving Chatbot for Public Administration via Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-31T18:20:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Daniel M. Jimenez-Gutierrez, Albenzio Cirillo, Raffaele Nicolussi, Alessio Beltrame, Andrea Vitaletti</p>
    <p><b>Summary:</b> We present GuidaPA, a privacy-preserving chatbot for the Italian Public Administration (PA) trained via Federated Learning (FL) on documentation from two national PA platforms, SIGESON and SIDFORS. Our corpus includes approximately 8 pages of SIGESON manuals and 31 pages of SIDFORS manuals/FAQs; while this study uses public documentation as a safe proxy, the intended deployment extends to restricted internal sources (e.g., tickets, officer manuals, database extracts) that can not be centrally pooled due to regulatory and organizational constraints. GuidaPA integrates role-based access control, secure client-side preprocessing, explicit monitoring of non-IID effects, and parameter-efficient federated fine-tuning of large language models. Using QLoRA (4-bit) over 15 federated rounds with an 80/20 train-test split per client, we evaluate answer quality with ROUGE, BLEU-4, and METEOR. The best federated model achieves ROUGE-1/2/L of 61.10/55.77/59.44, BLEU-4 of 45.02, and METEOR of 63.94-close to private centralized fine-tuning while keeping data on-site. Compared to the general-purpose baseline, domain fine-tuning improves ROUGE-1 from 41.45 to 62.18 and BLEU-4 from 26.97 to 50.90. Overall, the results indicate that FL can deliver high-quality conversational AI for public services without centralized data sharing</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.01225v1">Privacy-Preserving Smart Surveillance with Cross-Dataset Violence Detection and Decentralized Evidence Governance</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-31T13:16:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hasan Coşkun, Furkan Çolhak, Andrea Kulakov, Vesna Dimitrova</p>
    <p><b>Summary:</b> AI-enabled surveillance can accelerate public-safety response, yet most systems still leave recorded evidence under centralized administrative control. This paper proposes a privacy-preserving smart surveillance framework that separates incident detection from evidence disclosure. A lightweight MobileNetV2-based video classifier detects violent clips, while each recorded incident segment is immediately encrypted and made accessible only through threshold-based approval. The decryption key is split with Shamir's Secret Sharing, member shares are protected with public-key cryptography, and voting is supported by time-limited tokens, two-factor authentication, signatures, and audit logs. This study evaluates MobileNetV2+LSTM, MobileNetV2+BiLSTM, and MobileNetV2+temporal CNN heads on SCVD, RWF-2000, and Real-Life Violence Situations under seven in-domain and cross-dataset scenarios. The best all-source model, MobileNetV2+BiLSTM, reaches 93.5% test accuracy and ROC-AUC 0.980% on the merged held-out set, while lower RWF-2000 slice performance confirms persistent dataset shift.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.00986v1">Profiling Privacy Preservation Against Gradient Inversion Attacks in Tabular Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-31T03:54:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ivo Osterberg Nilsson, Maximilian Birr Engvall, Viktor Valadi, Teddy Lazebnik</p>
    <p><b>Summary:</b> Federated learning (FL) enables multiple data holders to train machine learning models collaboratively without centralizing raw data, making it useful in privacy sensitive domains such as healthcare and institutional data sharing. FL keeps data local to clients while communicating only model updates, such as gradients or model deltas. Nevertheless, these updates can expose private client data through gradient inversion attacks (GIAs). We study this risk for tabular FL under an honest-but-curious server threat model across FL protocols, client batch sizes, training stages, attacker assumptions, model architectures, and binary classification, multiclass classification, and regression tasks. We use MIMIC-IV and complementary benchmark datasets. Our evaluation distinguishes numerical and categorical recovery, baseline recoverability, feature level recovery, and exact match rate (EMR). We evaluate FedSGD gradients and FedAvg model deltas with an exposure aligned protocol, comparing attacked models after matched client data exposure rather than matched communication rounds. We compare multilayer perceptron (MLP), ResNet, and FT-Transformer models, and isolate architecture effects through an MLP grid over width, depth, activation, normalization, and dropout. The results show that small client batches and updates representing few distinct records are most vulnerable. Larger local batches and stronger aggregation reduce reconstruction but do not eliminate leakage. FT-Transformer is consistently harder to invert than one-hot baselines, while reconstructability also varies substantially within the MLP family. These findings identify architecture as a practical privacy variable in tabular FL. We also show that aggregate reconstruction accuracy can overstate complete record recovery in sparse data, making EMR and baseline comparisons essential.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.00962v1">SS-ZKR: Spatial-Semantic Zero-Knowledge Routing for Privacy-Preserving Multi-Agent Collaboration</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-31T02:34:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hassan Touheed</p>
    <p><b>Summary:</b> Foundational agent interoperability standards, notably the Agent-to-Agent (A2A) protocol and the Model Context Protocol (MCP), have advanced multi-agent system communication, and complementary identity frameworks leveraging W3C Decentralised Identifiers (DIDs) and Verifiable Credentials (VCs) provide cryptographic agent authentication. However, no existing protocol supports content-based semantic routing of agent payloads across organisational trust boundaries without requiring the routing intermediary to decrypt the payload, which is a hard constraint in compliance-sensitive environments governed by GDPR, HIPAA, and MiFID II. We propose SS-ZKR, a three-mechanism privacy-preserving routing protocol designed as a complementary layer atop A2A/MCP. Mechanism I introduces blind routing via differentially private semantic intent vectors cryptographically bound to zero-knowledge proofs of payload-schema consistency. Mechanism II offers vector-weighted adaptive payload sanitisation with formal (epsilon, delta)-differential privacy for numerical fields and heuristic semantic aggregation for textual fields. Mechanism III presents a spatial-to-cryptographic policy compiler that translates visually defined trust-zone topologies into deterministic zero-knowledge access circuits. We provide a formal threat model, analyse information leakage bounds of intent vectors, present pseudocode for all three mechanisms, and give analytical complexity comparisons against TEE-based and homomorphic encryption-based routing baselines. SS-ZKR lets enterprises in financial services, healthcare, and defence orchestrate heterogeneous AI agents across regulatory boundaries without exposing proprietary data to routing infrastructure.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.00407v1">Privacy-preserving Prosody Representation Learning</a></h3>
  
  <p><b>Published on:</b> 2026-05-29T22:49:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kevin Everson, Mari Ostendorf</p>
    <p><b>Summary:</b> Speech representations that capture prosodic information can be useful for both understanding and generation. However, speaker characteristics are reflected in acoustic-prosodic features (e.g., pitch). To address privacy concerns from the leakage of identity information, we propose a new self-supervised approach to learning prosody representations that incorporates speaker disentanglement strategies. We evaluate our encoder on three tasks to probe representation capabilities, including pitch reconstruction and detection of different prosodic events. Our encoder outperforms raw prosody and HuBERT-base baselines, achieving strong speaker disentanglement without adverse impact on prosody-related downstream tasks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.31167v1">LLM-FACETS: A Privacy-Preserving Framework for Evaluating LLM Transparency and Accountability</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-29T11:20:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tom Lucas, Alessio Buscemi, Alfredo Capozucca, German Castignani, Barbara Delacroix</p>
    <p><b>Summary:</b> Assessing whether Large Language Models outputs are factually grounded, epistemically calibrated, and methodologically reproducible is a prerequisite for responsible AI deployment. Yet auditing LLMs remains inaccessible to non-technical practitioners: existing tools require programming expertise and non-trivial environment setup, and cloud-hosted platforms transmit evaluation data to external services, creating barriers for domain experts and compliance officers legally responsible for AI oversight. We introduce LLM-FACETS (LLM FActuality Cross-EvaluaTion System): an open-source framework with a browser-accessible interface and a plugin architecture, structured around three practitioner profiles (technical experts, domain experts, compliance officers) that mirror the stakeholder categories identified in the EU AI Act and the NIST AI Risk Management Framework. The architecture makes data flows explicit: deterministic metrics (BLEU, ROUGE, BERTScore) run entirely within the self-hosted server with no outbound transmission; LLM-judge metrics contact external APIs explicitly, with users retaining full credential control. The framework operationalizes transparency through three mechanisms: token-level log-probability visualization for epistemic uncertainty, multi-judge consensus to mitigate judge bias, and RAG Triad metrics (Faithfulness, Answer Relevance, Context Relevance) to detect and localize hallucinations. A plugin architecture allows any new metric or dataset to be integrated without modifying the evaluation pipeline. The open-source implementation enables cross-checking across multiple metrics targeting the same property, ensuring reproducibility and decoupling AI accountability from the teams building the systems assessed. We verify the framework through cross-validation of 18 metric implementations against canonical reference libraries.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.30600v1">The Fast Mixing Mechanism for Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-05-28T21:48:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Omri Lev, Moshe Shenfeld, Vishwak Srinivasan, Katrina Ligett, Ashia C. Wilson</p>
    <p><b>Summary:</b> Randomized sketching is a central tool for compressing large-scale optimization problems while preserving accuracy. In particular, sketches that are based on structured matrices, such as the Hadamard matrix, can be applied efficiently and often yield solutions that approximate those of the original problem at much lower computational cost. In differential privacy (DP), Gaussian sketching has been used to solve DP linear regression, beginning with \citet{sheffet2017differentially, sheffet2019old} and later refined by \citet{lev2025gaussianmix, lev2026near}. However, although these methods achieve strong utility guarantees, they usually do not improve runtime over classical DP approaches. In this work, we introduce a new DP sketching mechanism based on fast transforms, which, in certain cases, matches the runtime of classical fast sketching methods. We prove state-of-the-art privacy guarantees for this mechanism and show that, in favorable regimes, they match those of the Gaussian sketch up to a constant factor. As an application, we combine this mechanism with recent sketch-based methods for DP linear regression to obtain a new algorithm with strong utility and improved runtime. We establish privacy and accuracy guarantees for this algorithm, yielding, to the best of our knowledge, the first fast method for DP ordinary least squares.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.30476v1">Local Differential Privacy with Correlated Noise Achieves Central-DP Optimal Cost</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-28T18:47:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Madhura Pathegama, Srikanth Avasarala, Viveck R. Cadambe, Juba Ziani</p>
    <p><b>Summary:</b> We study privately estimating the sum of $n$ user-held values in the presence of an honest-but-curious server. This motivates requiring privacy not only at data release but also throughout server-side computation. We therefore adopt the local (pure) differential privacy model, in which each user transmits a noise-perturbed value. It is well known that independent local noise typically incurs a substantial utility loss compared to the centralized model, where noise is added only after aggregation.
  We show that this gap is not fundamental. By carefully designing correlations among the locally added noise variables, we construct $\varepsilon$-DP mechanisms whose estimation cost matches the optimal cost achievable in the centralized setting, up to an arbitrarily small error.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.30123v1">Privacy-Enhanced Zero-Order Federated Learning via xMK-CKKS over Wireless Channels</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-28T15:56:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anthony Ayli, Khalil Harris, Jihad Fahs, Mohamad Assaad</p>
    <p><b>Summary:</b> Homomorphic encryption (HE) enables privacy-preserving aggregation in federated learning (FL) by allowing the server to operate on encrypted data without decryption. Existing HE-over-the-air methods mainly rely on single-key HE schemes and require channel estimation or pre-equalization to compensate for wireless fading. However, single-key HE remains vulnerable to honest-but-curious clients sharing the same secret key. In addition, compromising a single client may compromise the security of the entire network, while multi-key HE schemes provide stronger client-level security by assigning each device its own secret key. We propose a four-phase protocol that enables xMK-CKKS, a famous multi-key HE scheme, aggregation over a shared wireless channel without channel estimation. The protocol retransmits partial public keys and ciphertexts through the same channel realization, so that the dominant large-modulus encryption terms cancel algebraically during decryption. We integrate this protocol with zero-order FL over slowly varying LoS-dominant channels, where each device transmits a single encrypted scalar per round and the communication/encryption overhead is independent of the model dimension. We prove that the decoded encryption noise preserves the \(O(1/\sqrt{K})\) convergence rate up to a negligible noise floor. The protocol is secure against an honest-but-curious server colluding with up to \(N-1\) clients, and numerical results on MNIST validate the analysis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.29845v1">Local Differential Privacy via Dynamic Quantization in Distributed Online Stochastic Optimization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E">
  <p><b>Published on:</b> 2026-05-28T12:27:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhiguo Zhang, Cheng Kui, Qian Ma, Dongrui Wu</p>
    <p><b>Summary:</b> Distributed online stochastic optimization has received extensive attention in large-scale distributed learning and other related fields due to its unique advantage in processing streaming data. However, information exchange through the communication network during the optimization process may lead to privacy leakage. To address this issue, this paper proposes a locally differentially private distributed online stochastic optimization algorithm that employs an elaborately designed dynamic stochastic quantizer to mask the exchanged information prior to communication. Theoretical analysis shows that the proposed algorithm not only converges almost surely to the optimal solution but also achieves $(0,δ^i)$-local differential privacy for each agent $i$ even when the number of iterations tends to infinity. Furthermore, the algorithm is fully distributed and applicable to scenarios where the interaction network among agents is a directed graph. To the best of our knowledge, this is the first work on distributed online stochastic optimization that simultaneously achieves exact convergence and rigorous local differential privacy over a directed graph by exploiting quantization effects. Numerical experiments of distributed online training on the mushroom classification dataset, handwritten digits recognition dataset, and brain-computer interface dataset verify the effectiveness of the proposed method.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.29131v1">Techreport: Evaluating Tor-based Location Privacy for Ethereum Validators</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-27T21:50:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Muhammad Umar Janjua, Akshaya Mani, Uğur Şen, Daniel Kaiser</p>
    <p><b>Summary:</b> Privacy and anonymity of validators, especially regarding IP address linkability, are essential to protect the Ethereum network from various attacks. Network-level attacks, such as DoS, can interrupt validators and affect the overall security of the Ethereum network. Correlating the IP addresses of validators with their identities, along with knowledge about their action slots can be exploited by attackers to cause network delays, MEV exploitation, and finality risks. Therefore, ensuring the unlinkability of a validator's IP and identity is crucial for maintaining the network's trust and resilience. In this techreport, we first provide a review of the existing network and consensus layer techniques that have been proposed for maintaining validator privacy in the Ethereum blockchain. Secondly, we evaluate a Tor-based protocol named Tor push that helps unlink validator identities (IDs) from their nodes' IP addresses, thereby making it difficult to determine any end-to-end correlation between validator IDs and IP addresses of validators' beacon nodes. To evaluate the effectiveness of Tor push, we present a working, deployed proof-of-concept (PoC) implementation in the Nimbus Ethereum client. Our PoC deployment pushes attestations, aggregations, and block proposals over Tor to the Goerli testnet. Furthermore, we also analyse the security and latency of Tor push. Our experimental results suggest that Tor can be incorporated into the existing Ethereum network with a tolerable latency overhead of 613.82 ms on average and without compromising the overall network performance while enhancing the location privacy of validators in the Ethereum network.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.28646v2">MaskClaw: Edge-Side Personalized Privacy Arbitration for GUI Agents with Behavior-Driven Skill Evolution</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-05-27T15:51:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yanqiu Zhao, Dongying Zheng, Kaibo Huang, Yukun Wei, Zhongliang Yang, Linna Zhou</p>
    <p><b>Summary:</b> GUI agents rely on screenshots to infer intent and operate across applications, but these screenshots often contain private messages, medical records, payment credentials, and workplace-specific workflows. Privacy decisions in this setting depend on task, recipient, application state, and user role, yet static PII detectors miss these boundaries and cloud-side VLM reasoning can upload the raw screen before deciding what should be protected. We present MaskClaw, an edge-side privacy arbitrator for GUI agents. MaskClaw extracts local visual evidence, retrieves user- and task-specific policy memory, and decides Allow, Mask, or Ask before raw screenshots leave a trusted user- or organization-controlled environment. In five designed skill-evolution scenarios, it turns corrections, cancellations, and edits into reusable privacy skills checked by a sandbox gate. We introduce P-GUI-Evo, a benchmark built from real UI patterns, reconstructed HTML screens, and sanitized labels. Experiments show that pattern matching, cloud reasoning, and routing alone tend to over-confirm, over-mask, or expose raw screenshots under the same protocol. The artifact is available at https://github.com/Theodora-Y/MaskClaw.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.28642v1">Bandwidth-Efficient and Privacy-Preserving Edge-Cloud Many-to-Many Speech Translation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-27T15:47:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yexing Du, Kaiyuan Liu, Youcheng Pan, Bo Yang, Ming Liu, Bing Qin, Yang Xiang</p>
    <p><b>Summary:</b> Multimodal large language models (MLLMs) have demonstrated significant potential for speech-to-text translation (S2TT). However, existing deployment paradigms face critical challenges: pure on-device models suffer from resource constraints, while centralized cloud systems incur severe privacy risks and bandwidth bottlenecks by transmitting raw voice data. Furthermore, most models exhibit English-centric biases, restricting many-to-many translation scaling. In this paper, we propose Edge-cloud Speech Recognition and Translation (ESRT), a privacy-preserving and bandwidth-efficient collaborative edge-cloud MLLM framework. Specifically, we design an edge-cloud split inference architecture that retains a lightweight speech encoder and adapter on the device, transmitting only highly compressed intermediate features to the cloud. This fundamentally prevents voiceprint leakage and reduces bandwidth requirements by up to 10$\times$. To overcome English-centric bottlenecks, we introduce a multi-task weighted curriculum learning strategy with data balancing to ensure robust cross-lingual consistency. Extensive experiments on the FLEURS dataset demonstrate that our models, ESRT-4B and ESRT-12B, achieve state-of-the-art many-to-many S2TT performance across 45 languages ($45 \times 44$ directions). Code and models are released to facilitate reproducible, privacy-aware MLLM S2TT research. The code and models are released at https://github.com/yxduir/esrt.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.28325v1">ISAC Privacy: Challenges and Solutions for 6G</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">  
  <p><b>Published on:</b> 2026-05-27T11:25:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Onur Günlü, Stefano Tomasin, João P. Vilela, Francesco Chiti, Prajnamaya Dass, Angeliki Alexiou, Utz Roedig</p>
    <p><b>Summary:</b> Integrated sensing and communication (ISAC) is a promising feature of future communication networks. While spatial sensing can improve network performance and enable external services, it also creates privacy challenges that go beyond the confidentiality of communication content. Future networks using millimeter-wave (mmWave) and sub-terahertz (THz) frequencies may collect or infer detailed information about people, devices, bystanders, passive objects, and environments in a sixth-generation (6G) deployment area. Such sensing can reveal location and environment data, support behavioral profiling such as movement or activity recognition, and, in advanced cases, expose physiological information such as breathing frequency or heart-rate-related data. Thus, the capabilities of spatial sensing must be controlled to satisfy privacy requirements. In this work, we organize privacy-sensitive ISAC data into three sensing levels: location and environment data, behavioral data, and physiological data, and use this classification as the organizing principle throughout the paper. Based on this classification, we discuss internal and external ISAC applications, identify privacy challenges related to consent, transparency, data ownership, profiling, bystander exposure, and sensitive sensing data, review representative solution directions, and outline future research directions for privacy-preserving ISAC.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.28211v1">When Helpful Context Leaks: Privacy Risks in Domain-Adapted ASR</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-05-27T09:30:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maike Züfle, Jan Niehues</p>
    <p><b>Summary:</b> SpeechLLMs are increasingly deployed in professional settings where domain customisation is standard practice: users supply context in prompts with sensitive information, fine-tune on proprietary recordings, or both. We identify and systematically investigate an overlooked privacy risk of such customisation: a model adapted to recognise domain-specific terminology can be nudged into transcribing a phonetically similar word from its context or training data, even when a different word is spoken, thereby leaking private information. To evaluate this risk, we construct a controlled dataset and measure leakage rates across two customisation mechanisms, prompting and fine-tuning. Both mechanisms cause measurable leakage, compounding when combined. We evaluate a prompt-level mitigation strategy and analyse the accuracy-leakage trade-off across customisation approaches, finding that fine-tuning without context prompts offers the best balance. We release our code and dataset publicly.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.28089v1">BuddyBench: A Privacy-Constrained Multi-Task Benchmark for Pediatric Social-Communication Personalization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-27T07:44:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jeyeon Eo, Joo Young Kim, Ran Ju, Minyoung Jung, Unggi Lee</p>
    <p><b>Summary:</b> BuddyBench introduces a privacy-constrained multi-task benchmark for pediatric social-communication personalization. Unlike existing neurodevelopmental repositories that primarily emphasize imaging, genetics, or cross-sectional clinical phenotyping, BuddyBench links drill-level learning trajectories, standardized clinical assessments, BuddyPlan self-report, and randomized-treatment endpoints within a unified benchmark schema. BuddyBench combines two cohorts: ND-03 is an observational cohort with dense drill coverage for Tasks1-2 (n = 189), and ND-02 is a randomized controlled trial cohort for Tasks3-4 (n = 86 ITT). Together, they support knowledge tracing, next-drill recommendation, clinical prediction, and causal inference, linking behavioral personalization to clinical evaluation. We additionally introduce BuddyBench-Sim, a synthetic companion dataset for reproducible evaluation. Baselines show signal across tasks while keeping pediatric clinical records protected.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.28078v1">Mind the Gap: Mixtures of Gaussians in Approximate Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2026-05-27T07:32:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Huikang Liu, Aras Selvi, Wolfram Wiesemann</p>
    <p><b>Summary:</b> We design a class of additive noise mechanisms that satisfy \((\varepsilon, δ)\)-differential privacy (DP) for scalar, real-valued query functions with known sensitivities, with a particular focus on moderate and low-privacy regimes. These mechanisms, which we call \textit{mixture mechanisms}, are constructed by mixing multiple Gaussian distributions that share the same variance but differ in their means and mixture weights. The resulting distributions can be interpreted as convex combinations of a zero-mean Gaussian (as used in the analytic Gaussian mechanism) and additional Gaussians whose means depend on the sensitivity of the query function. We derive tight conditions on the variances required for \((\varepsilon, δ)\)-DP and provide efficient algorithms to compute them. Compared to the analytic Gaussian mechanism, our mechanisms yield substantially lower expected noise amplitudes (\(l_1\)-loss) and variances (\(l_2\)-loss for zero-mean distributions). In the low-privacy regime that motivates our design, our mechanisms approach optimality, mitigating nearly all of the optimality gap of the analytic Gaussian mechanism.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.27801v1">Local Privacy Laws in a Globalized World</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B">
  <p><b>Published on:</b> 2026-05-27T00:41:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shantanu Sharma, Ethan Myers, Lorenzo De Carli, Ritwik Banerjee, Indrakshi Ray</p>
    <p><b>Summary:</b> Personal data has emerged as a highly valuable yet sensitive asset that drives business decisions, enables targeted advertising, and generates substantial revenue for companies, while simultaneously facilitating invasive monitoring of users. In recent years, research on digital privacy violations, including undue access, collection, and sharing of user data, has grown significantly. Much of this research adopts the European General Data Protection Regulation (GDPR) as the primary reference framework. This is reasonable, as GDPR was a pioneering legislation, and many of its stipulations are clear and unambiguous. However, we argue that focusing solely on GDPR (and a small set of other Western regulatory frameworks) ignores privacy-related concerns, attitudes, and problems faced by users from other locales, creating a significant research blind spot. This work systematically normalizes the heterogeneous legal requirements of multiple data protection laws into a unified abstraction aligned with the data lifecycle, which forms the foundation for the implementation of such regulations. We further investigate the implications of these laws on different stakeholders, including users, organizations, and governments. Overall, this work aims to broaden the digital privacy research community's perspective and to serve as a set of guiding principles for developing technological privacy solutions spanning multiple countries.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.27782v1">Revisiting ML Training under Fully Homomorphic Encryption: Convergence Guarantees, Differential Privacy, and Efficient Algorithms</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-27T00:09:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yvonne Zhou, Mingyu Liang, Ivan Brugere, Danial Dervovic, Yue Guo, Antigoni Polychroniadou, Min Wu, Dana Dachman-Soled</p>
    <p><b>Summary:</b> We present the first theoretical convergence analysis of machine learning training under fully homomorphic encryption (FHE), combined with a differentially private (DP) training algorithm tailored to encrypted computation. Our approach improves computational efficiency over standard differentially private gradient descent (DP-GD) while achieving comparable utility. In particular, we prove convergence of approximate gradient descent using polynomial approximations of activation and loss functions, which are required for FHE compatibility. To preserve privacy in downstream tasks, we integrate differential privacy without relying on costly per-sample gradient clipping, enabling scalable encrypted learning. We also provide data-independent hyperparameter selection and theoretically grounded strategies for polynomial approximation which can be of independent interest. Together, these contributions advance the feasibility of efficient, private, and secure machine learning on sensitive data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.27766v1">Got a Secret? LLM Agents Can't Keep It: Evaluating Privacy in Multi-Agent Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-26T23:32:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aman Priyanshu, Supriti Vijay, Esha Pahwa</p>
    <p><b>Summary:</b> LLM safety evaluations predominantly test models in isolation, yet deployed AI agents increasingly operate within persistent social environments alongside other agents. We introduce a Moltbook-style simulation platform where thousands of LLM agents interact across communities over a simulated month, and use it to evaluate privacy as a downstream safety concern under varying degrees of social pressure. We find that shifting from single turn to multi turn social evaluation amplifies privacy violations (CIMemories 19.95% to Ours 45.30% across OpenAI models), that leakage is socially contagious, with agents 8 times more likely to disclose sensitive information after observing a peer do so, and that explicit privacy instructions reduce but do not eliminate this effect, leaving leakage rates above 37.8% even with safeguards. Our findings suggest that static chat based safety benchmarks systematically underestimate risks in agentic deployment, and that social context alone is sufficient to elicit sensitive disclosures that single turn evaluations would never surface.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.27292v1">Detectability in Diversity: Improved Canary Crafting for Privacy Auditing in One Run</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2026-05-26T17:06:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mathieu Dagréou, Aurélien Bellet</p>
    <p><b>Summary:</b> Privacy auditing aims to empirically assess privacy leakage in machine learning models using membership inference attacks (MIAs), and to derive lower bounds on differential privacy (DP) parameters. Recent one-run auditing methods address the high cost of standard approaches by relying on a single training run with multiple "canary" points whose inclusion or exclusion must be detected by the auditor. In this work, we study the problem of efficiently crafting canaries for one-run privacy auditing. Motivated by recent theoretical insights suggesting that interference between canaries contributes to weaker leakage estimates compared to multi-run methods, we propose to optimize canaries to be both highly detectable and minimally interfering. Our approach combines a greedy initialization based on influence functions with a bilevel optimization procedure that maximizes distinguishability while promoting diversity in embedding space, enabling the use of computationally efficient bilevel algorithms. Experiments show that our method achieves stronger privacy leakage estimates at a lower computational cost than existing canary crafting approaches.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.27278v1">Optimal quantum locally differentially private mechanisms in the high-privacy regime</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-05-26T16:57:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuuya Yoshida</p>
    <p><b>Summary:</b> We optimize the trade-off between privacy and utility in the high-privacy regime. We adopt local differential privacy (LDP) and its quantum extension, quantum local differential privacy (QLDP), for privacy protection, and investigate utility functions including the Holevo information (which reduces to the mutual information in the classical case) and the error exponents in symmetric and asymmetric hypothesis testing. These utility functions have classical and quantum optimal values, which are denoted by $C$ and $Q$, respectively, in this abstract for simplicity. In this paper, we provide optimal LDP and QLDP mechanisms achieving the classical and quantum optimal values in the high-privacy regime, and prove that the asymptotic ratio $Q/C$ in this regime takes the same value regardless of the utility function. Our results reveal quantum advantages (more precisely, $Q/C\ge3/2$) for the above utility functions when the protected private data are $n$-ary with $n\ge3$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.26931v1">Dual Privacy Guarantees for Distributed Nash Equilibrium Seeking in Aggregative Games</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E">
  <p><b>Published on:</b> 2026-05-26T12:24:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qingtan Meng, Qian Ma</p>
    <p><b>Summary:</b> This paper investigates the privacy-preserving distributed Nash equilibrium seeking problem for aggregative games. A novel differential privacy mechanism is designed by incorporating stochastic event-triggering with stochastic quantization, which provides strong privacy protection by obfuscating the temporal patterns of information exchange among players and quantizing the transmitted information at triggering instants. Based on this mechanism, a differentially private distributed Nash equilibrium seeking algorithm with dual randomness is proposed. By embedding a decaying factor sequence into both the triggering condition and interaction terms among players, it is proved that the proposed algorithm can achieve rigorous $(0,δ)$-differential privacy at each iteration while maintaining provable convergence. Crucially, this privacy guarantee is sustained over infinite iterations for a sufficiently large quantization interval and a sufficiently small trigger threshold tuning coefficient. Moreover, the synergy between event-triggered communication and quantization significantly enhances communication efficiency. Simulation results verify the validity of the proposed approach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.26882v1">Privacy-Preserving Screening for Record Linkage</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-26T11:43:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chenyu Huang, Fan Zhang, Huangxun Chen, Yongjun Zhao, Huaming Rao, Peng Chen, Danqing Huang</p>
    <p><b>Summary:</b> In an era dominated by big data and machine learning, establishing valuable data collaboration has never been more critical. However, such collaborations must operate under regulatory and legal constraints. Two-party Privacy-Preserving Record Linkage (PPRL) emerges to assess the potential collaboration value and also ensure the privacy and security of the involved data. Nevertheless, the substantial computational and communication overheads associated with PPRL hinder its practical adoption in data markets with numerous potential collaborators. Therefore, we present the Screening-then-Linkage framework, which incorporates a lightweight Screening phase prior to the resource-intensive PPRL phase, i.e., PPRS, to mitigate the scalability issue of PPRL. We propose a circuit-PSI-based system, named Appraisal to realize a secure, effective, and efficient PPRS. To reconcile the approximate matching and/or schema-aware setting required in PPRS with the limitations of the circuit-PSI supporting only symmetric functions, we propose a more communication-efficient secure permutation, i.e., Oblivious Attribute/Feature Alignment protocol tailored for PPRS. This protocol supports a broader range of comparison functions and significantly improves efficiency, i.e., reducing communication costs by a factor of 14 compared to the conventional protocol. Our rigorous analysis and comprehensive empirical evaluations demonstrate the security, effectiveness, and efficiency of Appraisal. Appraisal can accommodate up to $850\times$ more records than the SOTA PPRS system, SFour, within the same constraints. Moreover, it is $165 \times$ faster than SOTA PPRL, indicating the Screening-then-Linkage framework substantially decreases the computation time required to identify the most valuable collaborators from a large pool of candidates.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.26465v1">Beyond Epsilon: A Principled QIF Framework for Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-26T02:20:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ramon G. Gonze, Natasha Fernandes, Heber H. Arcolezi, Catuscia Palamidessi, Nataliia Bielova</p>
    <p><b>Summary:</b> Local Differential Privacy (LDP) has become the de facto standard for privacy-preserving data collection in large-scale systems, in particular for the purpose of estimating frequencies. However, the current research landscape lacks a systematic and principled way to compare LDP protocols. The parameter $\varepsilon$ of LDP is considered the measure of privacy, but it only bounds worst-case distinguishability. Other comparisons rely on utility-driven analyses, where mechanisms are ranked based on their ability to preserve data utility for a given privacy budget $\varepsilon$. Both such kinds of comparisons fail to account for the strength of protocols against diverse attacker models. In this paper, we propose a framework for analyzing LDP frequency estimation protocols through the lens of Quantitative Information Flow (QIF). By modeling LDP mechanisms as probabilistic channels, we leverage the concept of refinement (Blackwell ordering) to establish more principled classifications. This approach allows us to determine when one protocol is intrinsically superior to another for all possible adversaries, and to discuss the implications for utility. In particular, our analysis uncovers cases where protocols previously deemed "optimal" are, in fact, incomparable with, or strictly dominated by, other protocols. We provide a formal QIF-based treatment of seven state-of-the-art protocols, including Generalized Randomized Response (GRR), local hashing variants (BLH, OLH), unary encoding schemes (SUE, OUE), and Thresholding with Histogram Encoding (THE). This perspective bridges the gap between the LDP and formal methods communities and enables principled, adversary-aware reasoning about locally private systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.26351v1">Context-Aware Metric Differential Privacy for Vehicle Trajectory Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-25T21:54:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gaoyi Chen, Yan Huang, Chenxi Qiu</p>
    <p><b>Summary:</b> Metric Differential Privacy (mDP) generalizes differential privacy by allowing privacy guarantees to be expressed with respect to an arbitrary distance metric over secrets. While mDP has been adopted in geo-location protection, most existing mechanisms perturb each location record in isolation and do not model how contextual information (e.g., recent mobility history) affects the utility of the released data. This mismatch is particularly pronounced for vehicle mobility traces, where service quality often depends on temporally correlated locations.
  In this paper, we propose Context-aware mDP (C-mDP), a framework for vehicle location privacy that incorporates contextual dependencies into both the utility model and the privacy notion. C-mDP treats the protected secret as a context-augmented record and enforces metric indistinguishability over this augmented domain. We formulate optimal C-mDP mechanism design as a linear program (LP) that minimizes expected utility loss subject to C-mDP constraints. To improve scalability, we exploit conditional-independence structure between the current location and contextual variables to derive a reduced formulation with substantially fewer decision variables and constraints. We evaluate C-mDP on real-world vehicle mobility datasets and compare it with standard mDP baselines. The results show that C-mDP consistently achieves higher utility under the same privacy budget while satisfying the required metric privacy guarantees.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.26269v1">AgentSecBench: Measuring Prompt Injection, Privacy Leakage, and Tool-Use Integrity in LLM Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-25T18:53:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Faruk Alpay, Taylan Alpay</p>
    <p><b>Summary:</b> LLM agents process trusted instructions, retrieved records, and tool observations through a common generative channel. This conflates data flow with authority: an untrusted string can affect a secret-bearing response or an action proposal even when no application policy authorizes that influence. We introduce AgentSecBench as an empirical instantiation of a formal security framework for this problem. The framework defines three games-instruction-integrity, retrieval-confidentiality, and capability-integrity-under a common notion of intent-to-execution noninterference with permitted leakage. It represents an application policy as a projection onto authorized observations and capabilities, distinguishes prompt annotations from enforcing projections, and measures both adversarial advantage and whether a defense closes the relevant model-visible channel before generation. The exact-marker experiments are intentionally one observable instantiation of the games rather than a complete semantic security claim: they test disclosure and forbidden-action distinguishers with unambiguous ground truth. We evaluate six defense classes with Qwen3-0.6B and Qwen3-1.7B on paired adversarial and benign-control executions. The measurements show when risk reduction follows channel closure and when a model-visible adversarial capability remains exploitable. The result is a security-oriented evaluation method: prompt text can describe a boundary, whereas provenance projection, capability restriction, and output validation can enforce one.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.26243v1">Provably Communication-Efficient and Privacy-Preserving Federated Graph Neural Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-25T18:10:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhishuai Guo, Wenhan Wu, Chen Chen, Lei Zhang, Olivera Kotevska, Ravi K Madduri</p>
    <p><b>Summary:</b> Graph neural networks (GNNs) achieve strong performance on relational data, but real-world graphs are often distributed across organizations that cannot share raw data due to privacy and policy constraints. Existing federated GNN methods either ignore cross-client links, leading to degraded accuracy, or require frequent embedding exchanges, incurring substantial communication and privacy costs. We propose CE-FedGNN, a communication-efficient and privacy-preserving federated GNN framework for learning over such coupled graphs. Our approach avoids sharing raw data or per-round embeddings by infrequently exchanging aggregated node representations. To handle cross-client dependency and staleness, we introduce a moving-average estimator that continuously tracks node representations and enables their stable reuse across rounds. To provide formal privacy guarantees for the released representations, we adopt the metric differential privacy (metric-DP) framework, which measures privacy with respect to distances in the learned embedding space rather than worst-case input perturbations. This yields meaningful guarantees at noise levels where standard differential privacy becomes overly conservative. We establish convergence to a stationary point at a rate of $O(1/\sqrt{T})$ with $O(T^{3/4})$ communication complexity. In addition, we derive $(\varepsilon,δ)$-metric-DP guarantees via Rényi differential privacy composition under a public-cohort threat model. Experiments on synthetic interbank anti-money laundering benchmarks and citation networks demonstrate that CE-FedGNN achieves strong performance while significantly reducing communication and maintaining robustness under privacy-preserving noise.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.26222v1">From Privacy to Generalization: Linear Max-Information Bounds for DP-SGD</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2026-05-25T18:00:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Christoph H. Lampert, Hossein Zakerinia</p>
    <p><b>Summary:</b> Understanding the relationship between generalization and privacy remains a central challenge in modern machine learning theory, particularly for deep networks trained by variants of differentially private stochastic gradient descent (DP-SGD). In this work we make progress on this persistent open problem by proving a finite-sample bound on the approximate max-information of DP-SGD that exhibits scaling properties comparable with (Dwork et al, 2015)'s classic result for $ε$-differentially private algorithms, namely at most linear in the dataset size. From our result we obtain a general-purpose PAC-Bayes generalization bound in which the necessary prior distribution can be learned by DP-SGD, as well as a generalization bound for DP-SGD-trained models themselves, with a complexity term that is fully explicit and controlled by the optimization hyperparameters.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.25791v1">Efficient and Privacy-Preserving Distribution Statistics Analytics on Mobile Spatial Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-25T12:37:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xuhao Ren, Mingyang Zhao, Ruichen Zhang, Liehuang Zhu, Dusit Niyato, Bin Xiao</p>
    <p><b>Summary:</b> With the rapid development of mobile computing technology, massive amounts of spatial data are continuously generated from various mobile terminals and sensing devices, such as smartphones, connected vehicles, and drones. Performing efficient distributed statistical analysis on this data is crucial for real-time mobile computing applications. However, the constrained and dynamic nature of mobile environments exacerbates the privacy challenge: centralizing sensitive data for analysis risks severe privacy leaks, while existing privacy-preserving techniques often introduce excessive overhead or inaccuracies In this paper, we design, implement, and evaluate the first system that supports efficient and privacy-preserving distribution statistics analysis for mobile spatial data. First, we propose eSpat-B, which leverages two non-colluding servers and a newly designed improved distributed point functions (DPF) with octree partitioning. Furthermore, considering the frequent updates of spatial data, we propose another more efficient scheme, eSpat+. The core idea of this scheme is to utilize a K-Dimensional tree for spatial partitioning, combine it with incremental DPF for performing statistics analysis, and design an efficient update algorithm. Security analysis demonstrates that our schemes effectively protect data privacy throughout the statistical process. Theoretical analysis and experimental results on real-world mobile trajectory datasets demonstrate that our proposed schemes achieve a reduction of approximately 1.2* in computation overhead, 20* in communication overhead, and maintain 100% accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.25716v1">An Efficient and Privacy-Preserving Architecture for Cross-Institutional Collaborative RAG</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-05-25T11:18:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chenxin Mao, Shangyu Liu, Zhenzhe Zheng, Fan Wu, Jie Wu, Guihai Chen</p>
    <p><b>Summary:</b> Retrieval-Augmented Generation (RAG) empowers LLMs with external knowledge, making cross-institutional domain-specific knowledge base integration a highly promising deployment paradigm. Despite this potential, strict privacy regulations create severe "data silos" that obstruct such collaboration. Building federated RAG systems requires distributed inference, but the Transformer's self-attention mechanism fundamentally conflicts with this by mandating cross-node access to distributed Key-Value caches. To address this challenge, we present FedRAG, a high-throughput, privacy-preserving federated RAG framework. At its core is a novel Scrambled Distributed Attention protocol that utilizes numerically stable feature scrambling and token permutation. By dynamically delegating scrambled computations to collaborating nodes, our system successfully decouples attention execution from data localization without exposing plaintext. Crucially, our approach requires no specialized hardware or model retraining, circumventing the prohibitive latency and communication overheads of cryptographic solutions while robustly defending against intermediate state inversion attacks. Extensive evaluations demonstrate our framework preserves negligible (<0.1\%) model utility degradation and achieves up to a 62$\times$ latency reduction over existing secure baselines, sustaining practical, human-reading throughput for cross-institutional knowledge synergy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.25713v1">Ecosystem-Driven Privacy Exposure in Mobile Gaming Apps: A Configuration-Aware Empirical Analysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-25T11:14:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bakheet Aljedaani</p>
    <p><b>Summary:</b> Mobile gaming apps increasingly rely on third-party Software Development Kits SDKs for advertising, analytics, attribution, and user engagement, potentially introducing privacy exposure beyond traditional permission based risks. Existing studies have largely focused on permissions or isolated tracking behaviors, providing only a partial understanding of privacy exposure in modern mobile ecosystems. This study presents a configuration aware empirical assessment of privacy exposure in Android mobile gaming apps by examining permissions, manifest level configurations, exported components, and SDK ecosystem complexity across children-oriented and general-audience games. A systematic static analysis was conducted on 41 widely deployed Android mobile gaming apps collected from the Google Play ecosystem. The analysis incorporated SDK categorisation and statistical evaluation using Spearman correlation, Mann Whitney U, and Chi square testing. The results revealed that privacy exposure is strongly associated with ecosystem-level architectural decisions rather than permission requests alone. Child-oriented games frequently demonstrated exposure conditions comparable to general-audience apps despite sometimes requesting fewer sensitive permissions. Furthermore, larger and more diverse SDK ecosystems were significantly associated with elevated privacy exposure levels, while advertising-oriented SDKs showed strong association with high exposure classifications. These findings highlight the limitations of permission-centric assessment approaches and emphasize the importance of configuration aware and ecosystem-aware privacy evaluation methodologies for modern mobile software systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.25631v4">The Privacy Subsidy in Continuous-Time Kyle: Cumulative Welfare under Noise-Perturbed Order-Flow Observation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Probability-5BC0EB"> 
  <p><b>Published on:</b> 2026-05-25T09:31:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuki Nakamura</p>
    <p><b>Summary:</b> We extend the closed-form privacy-subsidy result of Nakamura~(2026, arXiv:2605.15746) from the single-period Kyle model to continuous-time. A committed Bayesian automated market maker observes the aggregate order flow perturbed by an independent Brownian privacy channel of diffusion intensity $σ_\varepsilon$. Under the Markovian linear equilibrium, the price-impact coefficient is $λ= σ_v / \sqrt{σ_u^2 + σ_\varepsilon^2}$ -- constant in time -- and the cumulative expected transfer from the protocol's liquidity pool to traders over $[0,1]$ is $|Π_M| = σ_v σ_\varepsilon^2 / \sqrt{σ_u^2 + σ_\varepsilon^2}$. We then establish a structural correspondence between this cumulative privacy subsidy and Loss-Versus-Rebalancing (Milionis et al.~2022), identifying privacy-noise welfare as the order-flow observation analog of LVR's price observation gap. The result completes the continuous-time Kyle leg of the program of quantifying break-even fees for committed-AMM exchanges under privacy-aggregated information environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.25020v1">Privacy-Preserving Local Language Models for Longitudinal Data Retrieval in Chronic Dermatologic Disease: Implementation in Pemphigus Patients</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-05-24T12:00:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abdurrahim Yilmaz, Ayşe Esra Koku Aksu, Duygu Yamen, Vefa Asli Erdemir, Mehmet Salih Gurel, Gulsum Gencoglan, Joram M. Posma, Burak Temelkuran</p>
    <p><b>Summary:</b> Chronic dermatologic diseases such as pemphigus require long-term follow-up, generating extensive longitudinal clinical documentation that is difficult to review comprehensively during routine visits and increasing clinician workload as well as the risk of missing critical historical information. We evaluated whether a locally deployed, privacy-preserving small language model (SLM) could retrieve structured clinical features and generate longitudinal summaries from long-term dermatology follow-up records. In this retrospective case series, thirty pemphigus patients contributed 541 visit notes that were aggregated into full longitudinal records (89,336 words); 56 clinically relevant features were annotated by two expert dermatologists. The locally deployed SLM (Qwen3 4B Thinking 2507) was queried with each complete record to retrieve 56 features and generate one final report summaries. Across 1,680 feature retrieval tasks, mean accuracy was 82.25%. Dermatologists' ratings of AI-generated summaries were high for overall quality (8.23-8.47), clinical accuracy (7.93-8.20), and usefulness (8.47-8.50), with no significant inter-evaluator differences and an overall preference for AI summaries in 53.3% of evaluations. These findings suggest that privacy-preserving, locally deployed SLMs can outperform medical experts and reliably generate clinically meaningful longitudinal summaries. SLMs may support clinical decision-making when integrated with appropriate oversight.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.24765v1">CyberMaskQA: A Privacy-Aware Benchmark for Evaluating Large Language Models in Cybersecurity Question Answering</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-23T22:57:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Matilda Gaddi, Jin Noh, Onat Gungor, Tajana Rosing</p>
    <p><b>Summary:</b> Large language models (LLMs) are increasingly applied to cybersecurity question answering (QA) for critical tasks such as incident response and vulnerability analysis. However, real-world operational contexts, including system logs and network configurations, inherently contain sensitive identifiers, e.g., IP addresses, host names, and user accounts. Processing this data with cloud-based models is often unsafe or infeasible in regulated environments. Furthermore, progress in privacy-preserving QA is hindered by the lack of annotated, context-rich datasets capable of jointly evaluating operational reasoning and privacy preservation. To address this gap, we introduce CYBERMASKQA, a privacy-aware QA benchmark covering key security domains. Unlike existing benchmarks that primarily test factual knowledge, CYBERMASKQA grounds questions in realistic organizational contexts with explicit causal dependencies among assets and privileges. Generated through a systematic pipeline, the dataset combines human-curated base scenarios with LLM-driven semantic expansion, annotating each instance with precise private entity labels to enable controlled information disclosure. Evaluations of QA accuracy and masking performance demonstrate the benchmark's utility for developing deployable, context-aware cybersecurity models and facilitating nuanced studies of privacy-utility trade-offs. Upon acceptance, we will release the dataset and the generation framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.24458v1">Balancing Fairness, Privacy, and Accuracy: A Multitask Adversarial Framework for Centralized Data-Driven Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-23T08:10:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Imesh Ekanayake, Elham Naghizade, Jeffrey Chan</p>
    <p><b>Summary:</b> The integration of fairness and privacy in centralized data-driven applications is critical, especially as these systems increasingly influence sectors with significant societal impact. Current methods rarely address privacy, fairness, and accuracy together, which can potentially compromise ethical standards and privacy regulations. However, balancing these three objectives is quite challenging since each of objective often imposes conflicting requirements on the design and training of models, making it difficult to optimize one without compromising the others. This paper introduces a novel multitask adversarial model that treats fairness and privacy as integral objectives rather than afterthoughts, and learns a latent representation that hides sensitive attributes while preserving essential task-related information. Our approach dynamically balances fairness with accuracy and privacy through an optimized cost function with minimal performance loss even under strict conditions. Extensive testing on diverse datasets shows the ability of our model to achieve high standards of fairness and privacy without significant sacrifice to accuracy. Benchmarking against state-of-the-art privacy and fairness standards shows that our method enhances the robustness of privacy, fairness, and accuracy optimization, proving its adaptability across various datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.24420v1">Batch Normalization Amplifies Memorization and Privacy Risks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-23T06:18:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ngoc Phu Doan, Chongyan Gu, Ihsen Alouani</p>
    <p><b>Summary:</b> Batch Normalization (BN) is widely adopted to enable faster convergence and more stable training of deep neural networks. However, its impact on privacy and memorization has remained largely unexplored. In this work, we investigate the effect of BN layers on the memorization of atypical or outlier samples and its implications for privacy leakage. We conduct an extensive empirical study using three complementary approaches: (i) unintended memorization of out-of-distribution training samples, (ii) per-sample influence measured via gradient norms, and (iii) susceptibility to membership inference attacks (MIA). Across multiple datasets and architectures, we consistently observe that BN substantially increases the memorization of outliers compared to models without BN. Critically, this amplified memorization translates directly into privacy vulnerabilities: models with BN exhibit significantly higher susceptibility to MIAs. We complement our empirical findings with a theoretical analysis showing that BN amplifies the per-step influence of outlier samples during training, providing mechanistic insight into this phenomenon. Our results highlight an underappreciated privacy risk associated with BN and provide both practical and theoretical insights into how normalization layers can amplify the influence of rare or sensitive training examples.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.24307v1">Modernizing User Privacy Preference Measurement through GPPI: A GDPR-aligned Privacy Preference Item Bank</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-05-23T00:36:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yahya Hmaiti, Mykola Maslych, Amirpouya Ghasemaghaei, Trung Cuong Dang, Corey Pittman, David Mohaisen, Joseph J. LaViola</p>
    <p><b>Summary:</b> Privacy measurement instruments (e.g., CFIP, IUIPC, PAQ) predate GDPR by over a decade and measure privacy concerns, distinct from preferences for regulatory protections (e.g., data portability, erasure, automated decision-making rights). This leaves practitioners without tools to assess whether users value the GDPR mechanisms implemented in compliant policies. We developed a GDPR-grounded privacy preference measurement item bank by extracting 669 statements from all 99 GDPR articles, validated by: (1) two-round expert review achieving full consensus on accuracy, (2) semantic clustering into 10 parent themes and 87 subthemes, and (3) consensus review with 50 privacy experts (5 per theme) using a larger or equal than 4/5 vote retention threshold. The final 527-item bank comprises 9 parent themes and 73 subthemes (18 to 112 items per parent theme, 1 to 29 per subtheme), enabling targeted measurement across granularities while covering GDPR at mean pairwise expert agreement of approx. 85%. This work introduces a complementary measurement dimension aligning user preferences with regulatory mechanisms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.24249v1">PrivFusion: A Privacy-preserving Multi-Agent Framework for Harmonizing Distributed Datasets</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-22T21:54:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anisa Halimi, Liubov Nedoshivina, Kieran Fraser, Stefano Braghin</p>
    <p><b>Summary:</b> The growing availability of clinical data has increased the use of machine learning, yet centralized data aggregation is often infeasible for sensitive health information. Federated Learning (FL) offers a distributed alternative, but its adoption is limited by substantial heterogeneity across institutional datasets, making harmonization a critical but frequently overlooked prerequisite for multi-site analytics. We introduce PrivFusion, a privacy-preserving multi-agent framework that automates the harmonization of structured datasets prior to federated training. PrivFusion uses agents to analyze local data, cluster semantically similar features across sites, and provide iterative transformation recommendations until alignment is achieved. Evaluation across four heterogeneous COVID-19 datasets demonstrates that PrivFusion effectively and efficiently harmonizes multi-site data while substantially reducing manual effort.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.24239v1">Unlocking Apple's Private Cloud Compute: An Analysis of Privacy-Preserving Artificial Intelligence</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-22T21:31:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yannik Dittmar, Marvin Jerome Stephan, Thomas Völkl, Matthias Hollick, Jiska Classen</p>
    <p><b>Summary:</b> Many existing Artificial Intelligence (AI) solutions on mobile devices rely on an extensive collection of sensitive data, raising privacy concerns and often requiring storage for both context and model improvement. Apple's Private Cloud Compute (PCC) aims to address this by emphasizing mobile device integration and a privacy-first design. The central claim of PCC is that it does not store any user data and that user input and user accounts are unlinkable.
  While most of the PCC system specifications are public, compiled binaries add a layer of opaqueness. There are no reproducible builds, and there are no symbols within those binaries, creating potential discrepancies between the specification and what is shipped to the user. Additionally, the underlying models and interfaces for querying PCC are not openly accessible, limiting academic evaluation of model properties, such as accuracy. This poses a challenge in assessing whether a privacy-preserving approach like PCC is actually trustworthy while also providing high-quality answers.
  We are the first to reverse-engineer the PCC implementation on mobile devices to evaluate privacy aspects and to open its non-public interfaces on local devices to support custom PCC queries. We demonstrate this level of access beyond Apple's intended use cases by independently benchmarking the PCC model. We enable future research by making our PCC benchmarking framework publicly available.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.24166v1">Optimal Quantum Differential Privacy via Fisher Information Spectral Analysis</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-22T19:36:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Justice Owusu Agyemang, Jerry John Kponyo, Elliot Amponsah, Godfred Manu Addo Boakye</p>
    <p><b>Summary:</b> The Quantum Fisher Information (QFI) metric governs a fundamental duality: it quantifies both how precisely a parameter can be estimated (metrology) and how distinguishable two quantum states are (privacy). We exploit this duality to establish a geometry-aware framework for quantum differential privacy (DP) that replaces isotropic depolarizing noise with direction-dependent noise aligned to the QFI eigenstructure of the quantum embedding. We prove six principal theorems: (1) the minimax-optimal mechanism concentrates the noise budget in the dominant QFI eigenmode, achieving $\varepsilon = (Δ^2/2)λ_{\max}(1-cγ)$ with $O(d/λ_{\max})$ advantage; (2) mixed-state QFI decomposition reveals that dephasing in the adversary's basis $\textit{increases}$ accessible information, while misaligned-basis dephasing provides constructive privacy amplification from hardware noise; (3) a tight privacy $-$ utility uncertainty relation $\varepsilon \cdot (1 - F) \ge \frac{Δ^2}{2}\frac{\operatorname{Tr}(F)}{d}$; (4) adaptive QFI estimation converging at $O(1/\sqrt{n})$ yields $1.92\times$ tighter bounds; (5) QFI-aligned composition saturates at $O(1)$ versus $O(k)$ for standard composition; and (6) hardware noise can be harnessed for privacy amplification. Adversarial vulnerabilities, Wasserstein guarantees, subspace projection, and a zero-knowledge audit protocol follow as corollaries. Results are validated on Qiskit Aer GPU simulations, IBM Quantum hardware (ibm_fez, 156 qubits), and against classical DP baselines, achieving equivalent utility at $\varepsilon \approx 0.001$ versus $\varepsilon \approx 4800$ for classical DP.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.23879v1">On the Stability of Spherical Hellinger-Kantorovich Flows and Their Implications for Differential Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">
  <p><b>Published on:</b> 2026-05-22T17:38:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aratrika Mustafi, Soumya Mukherjee</p>
    <p><b>Summary:</b> Gradient-flow sampling interprets a Gibbs distribution as the minimizer of an energy functional over probability measures and generates dynamics converging to this target. Under spherical Hellinger-Kantorovich (SHK) geometry, the flow couples transport and reaction and coincides with birth-death Langevin dynamics. In this work, we develop a perturbation theory for SHK gradient flows. For two potentials $V$ and $V^{\prime}$, we compare the associated flows from a common initialization and quantify how potential discrepancies propagate over time. A uniform perturbation bound yields dimension-free, pointwise control of the log-likelihood ratio and Rényi divergence, while additional structure allows us to derive bounds for the KL divergence as well. We apply these results to approximate sampling for the exponential mechanism in differential privacy. The likelihood-ratio control provides explicit time-dependent Pure-DP guarantees for SHK-based samplers, while the KL bound yields Approximate-DP certificates via hockey-stick divergence. We also derive a utility bound separating intrinsic exponential-mechanism suboptimality from finite-time sampling error.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.23820v1">Inferential Privacy Leakage in Anonymized Conversational AI Logs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B">
  <p><b>Published on:</b> 2026-05-22T16:22:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> S M Mehedi Zaman, Kiran Garimella</p>
    <p><b>Summary:</b> Hundreds of millions of users now hold detailed, multi-turn conversations with ChatGPT and similar LLM assistants. We measure two privacy-relevant features of these conversations on a corpus of complete ChatGPT histories donated by over 1,000 users in four Global South countries (Brazil, India, Nigeria, Pakistan). First, on explicit disclosure: 34.5% of user messages contain personal information across a twenty-category taxonomy, with the median user first revealing identifying content within the first 14% of their conversation history. Second, on inference beyond explicit disclosure: we restrict to a cohort whose conversations contain no messages flagged by an LLM-based filter for explicit demographic self-identification (a separate NER pass marks PII for the disclosure audit but does not drive cohort exclusion). On this filtered cohort, an off the shelf large language model still recovers each user's age, gender, and country at weighted F1 of 0.84, 0.90, and 0.88, respectively, with the median user identified from the first 5% of their conversation history. Reading the model's natural-language reasoning traces, we identify four recurring stereotype patterns that drive both successful inference and an asymmetric error distribution concentrating on women in technical fields, older users with contemporary skills, and Global South tech professionals. We also compare ChatGPT against the same users' Google Search and YouTube histories as inference surfaces, and find it competitive with these older substrates that have driven behavioral advertising for two decades. Message-level PII removal is insufficient on its own as a privacy intervention for conversational AI data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.23641v1">Kernel-Based ReLU Approximation for Homomorphic Encryption-Compatible Privacy-preserving Deep Learning Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-22T13:54:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dimitrios Sygletos, Dimitra Papatsaroucha, Marios Choudetsanakis, Ilias Politis, Evangelos K. Markakis</p>
    <p><b>Summary:</b> As privacy concerns in AI technologies continue to grow, Homomorphic Encryption (HE) offers a way to perform computations on encrypted data without the need of decryption during operations. However, HE is limited to addition and multiplication, making non-linear functions incompatible in their original form. This limitation has become more critical with the widespread use of Large Language Models (LLMs), where the non-linearity of activation functions such as the Rectified Linear Unit (ReLU) poses challenges for deployment in privacy-preserving Natural Language Processing (NLP) settings. This paper proposes a kernel-based approximation of ReLU, enabling its use within HE-constrained settings and thus contributing a critical step toward supporting privacy-preserving LLMs. A smooth kernel-based function, mimicking ReLU, is approximated using a second-degree polynomial, inspired by Jackson's theorem, to achieve low multiplicative depth. The proposed method is trained and assessed directly on token embeddings from pre-trained LLMs and evaluated in various scenarios, from simulated and tokenized data to deep learning and transformer models. Results show improved approximation fidelity, supporting the method's suitability for secure and privacy-preserving inference in various tasks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.23640v1">CachePrune: Privacy-Aware and Fine-Grained KV Cache Sharing for Efficient LLM Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-22T13:54:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guanlong Wu, Zhaohan li, Yao Zhang, Zheng Zhang, Jianyu Niu, Ye Wu, Yinqian Zhang</p>
    <p><b>Summary:</b> Large Language Models (LLMs) rely on Key-Value (KV) caching to accelerate inference, and many serving systems further share the KV cache across users' requests to reduce redundant computation. While widely adopted, unrestricted cross-user sharing introduces side-channel vulnerabilities, allowing an adversary to infer user inputs by probing for cache reuse. Existing defenses disable sharing entirely to prevent leakage; yet such a coarse-grained strategy sacrifices substantial reuse potential, since prompts often include large portions of privacy-irrelevant segments, such as system instructions or publicly accessible materials. Building on this, we present CachePrune, a privacy-aware KV cache sharing mechanism that enables fine-grained reuse of KV entries across requests. Realizing such fine granularity requires token-level cache management, as reusable segments vary in length and position due to sensitivity masking, making reuse more complex than the fixed-size or sentence-level chunking used in existing coarse-grained schemes. Specifically, CachePrune makes fine-grained reuse practical by addressing two key challenges: accurately and efficiently deriving reusable KV segments and efficiently retrieving them over variable-length spans. We implement CachePrune on top of vLLM and evaluate it on three datasets, showing that it eliminates direct leakage through KV cache reuse side channels while reducing TTFT by 4.5x and increasing cache hit rates by 44% compared with state-of-the-art approaches.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.23429v2">Communication Security and Sensing Privacy in FMCW-Based ISAC Through Signal Modulation</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-22T09:41:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Murat Temiz, Christos Masouros</p>
    <p><b>Summary:</b> This study proposes a novel radar-centric signaling design and architecture for secure integrated sensing and communication (ISAC) systems. The proposed framework is designed to provide robust physical layer security for data transmission while simultaneously enhancing sensing privacy. It employs index modulation and phase coding over frequency-modulated continuous-wave radar (FMCW) chirps, where index modulation (IM) provides an outer layer of data security, and we explicitly design the phase coding (PC) to perturb the resulting signal's ambiguity function (AF) to enhance sensing privacy. This design reduces the risk of unauthorized surveillance by rendering target velocity estimation practically infeasible for unauthorized passive sensing hardware (i.e., a sensing eavesdropper, S-Eve) and significantly impairing its range estimation capabilities. Furthermore, this study also presents the transmitter and receiver architectures required for effective modulation and demodulation of the proposed ISAC signaling and for performing sensing at the legitimate sensing hardware. Simulation results show that the proposed approach achieves high data throughput while enhancing communication security and sensing privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.23330v1">Security, Privacy, and Ethical Risks in OpenClaw</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-22T07:45:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yutong Jin, Zelin Zhang, Zhijin Lyu, Jianbing Ni</p>
    <p><b>Summary:</b> This paper systematically investigates the security, privacy, and ethical risks, as well as the traceability challenges of OpenClaw, a locally executable AI agent system for natural language interaction and real-world task completion. While OpenClaw shows strong potential for personal assistance, office automation, cross-platform task management, and information integration, it also raises serious security, privacy, and ethical concerns. By analyzing its system architecture, core functionalities, deployment model, and representative application scenarios, this paper aims to reveal the risks that may arise when such a highly privileged agent is integrated into personal and organizational digital environments. We focus in particular on the challenges associated with persistent local storage, tool invocation, cross-context information aggregation, multi-user interaction, and the integration of plugins and external services. We argue that these issues constitute major barriers to the trustworthy deployment and widespread adoption of this technology. Finally, we summarize the open challenges in security defenses, privacy protection, ethical governance, and traceability in agent use, and call for joint efforts from researchers, developers, deployers, and regulators to build AI agent systems that are safer, more reliable, and more trustworthy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.24063v1">Microbenchmarking Cloud Cryptographic Workloads for Privacy-Preserving Healthcare IoT</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-22T03:54:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jeremiah L. Webb, Laxima Niure Kandel, Deepti Gupta, Lavanya Elluri</p>
    <p><b>Summary:</b> Cryptographic operations are an essential component of cloud security architectures; their comprehensive performance characterization across different cloud services, hardware architectures, and programming language implementations remains unknown. Specifically, healthcare IoT devices are highly vulnerable and frequently targeted, yet the cryptographic performance trade offs in their cloud security architectures remain poorly understood. This research presents an extensive microbenchmark study evaluating the performance of core cryptographic workloads, including SHA HMAC generation, AES encryption, decryption, Elliptic Curve Cryptography (ECC) signature generation and verification, and RSA encryption, decryption, across Function as a Service (FaaS) integrated with Key Management Services (KMS) from Amazon Web Services (AWS) and Microsoft Azure. We evaluate FaaS platforms using Elastic Compute Cloud (EC2) instances and Azure Virtual Machines, specifically using burst optimized instance types to analyze performance under typical cloud workload patterns. The benchmark encompasses a comprehensive multi dimensional analysis spanning two CPU architectures (x86 64 and Arm64), six widely adopted programming languages (Rust, Go, Python, Java, C#, and TypeScript), multiple memory allocation configurations, and diverse instance types to capture the complex interplay between these factors. This study identifies optimal configurations for cryptographic workloads in FaaS environments, improving performance and cost efficiency while enabling secure and timely data protection for healthcare IoT applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.23158v1">What Does the Server See? Understanding Privacy Leakage from Large Language Models in Split Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-22T02:14:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mingyuan Fan, Yu Liu, Fuyi Wang, Cen Chen</p>
    <p><b>Summary:</b> The deployment of large language models (LLMs) on resource-constrained devices remains challenging, spurring interest in split inference, where models are partitioned between client and server to reduce computational burden and enhance privacy by transmitting only intermediate activations. However, the privacy-preserving capabilities of split inference, particularly in the context of LLMs, have not been exhaustively investigated. To fill this gap, we introduce ActInv, which solves an intermediate activation matching problem to reconstruct the client's input. Extensive evaluations demonstrate that ActInv achieves high-fidelity reconstructions, even in the presence of common perturbation-based defenses such as Gaussian noise injection and activation sparsification. To systematically understand this vulnerability, we develop Perturbation Amplification Factor (PAF), a metric for quantifying a layer's inherent resistance to reconstruction. Our analysis reveals that privacy vulnerability is not uniform across layers, with some layers being highly susceptible to leakage while others offer natural resistance. Furthermore, we demonstrate that defense effectiveness can be significantly improved by calibrating perturbation directions to maximize reconstruction error during backpropagation. Building on these insights, we design PriPert and conduct comprehensive evaluations, covering privacy, utility, and computational overhead, to demonstrate its effectiveness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.24042v2">Hidden-State Privacy Has an Empty Middle</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-21T20:12:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alexander Okezue Bell</p>
    <p><b>Summary:</b> Of $1{,}536$ Gaussian release covariances we tested for single-layer hidden-state privacy, zero achieve both moderate utility and moderate privacy against an adaptive retrieval attacker. We prove a complementary Fisher-ball lower bound: every full-rank Gaussian release at $O(1)$ Fisher utility admits a direction whose Mahalanobis signal grows linearly in hidden width, ruling out uniform Gaussian safety in the class and matching the empirical empty middle. The diagonal inverse-Fisher release $Σ^\star_{\mathrm{diag}}(\mathcal{K}) = (2\mathcal{K}/d)\,\mathrm{diag}(1/F_{ii})$ is the unique minimax-optimal diagonal mechanism at first-order KL budget $\mathcal{K}$ and the only release with worst-attacker top-1 $\le 0.001$ at every point of a 32 model-layer grid, but it sits on a privacy/utility edge rather than filling the middle. A generalized-eigen mechanism reaching $13\times$ Pareto reduction under Euclidean retrieval collapses to $100\%$ top-1 under the adaptive Mahalanobis attacker, and a full-trajectory sequence inverter recovers $94\%$ of clean GPT-2 prefixes but $0\%$ under $Σ_{\mathrm{diag}}$. A split-memory transformer trained from scratch reaches $G_{\mathrm{Mah}} \in [20, 33]$ at 90M and maintains a $6$--$24\times$ advantage over same-budget GPT baselines from 30M to 1B at a fixed-token language-modeling loss penalty; pretrained models top out at 9.3. These results reframe hidden-state release from mechanism-design within the Gaussian class to architecture or release co-design.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.22952v1">Measuring Database Unfairness via Dependency Quantification Under Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2026-05-21T18:31:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mariia Vologdin, Yuchao Tao, Amir Gilad</p>
    <p><b>Summary:</b> Differential privacy (DP) has become the de facto standard for protecting sensitive data, providing strong guarantees that published statistics or models reveal limited information about any individual. However, privacy noise and restricted data access make it increasingly difficult to assess the fairness and reliability of private datasets. In this paper, we propose a formal framework for quantifying data unfairness under DP. We identify three core desiderata for unfairness measures based on previous work: positivity, monotonicity, and DP computability. We further instantiate them through three complementary measures: (1) a mutual information-based measure with a total variation distance proxy suitable for DP, (2) a data repair-based measure approximated via a reduction to weighted MaxSAT, and (3) a top-$k$ tuple contribution measure that isolates the most influential records in fairness violations. We design privacy-preserving algorithms and analyze their sensitivity, accuracy, and efficiency. Extensive experiments on multiple real-world datasets demonstrate that our proposed measures faithfully approximate their non-private counterparts, effectively quantify bias under privacy constraints, and provide insights for data management.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.22924v2">Building a privacy-preserving Federated Recommender system for mobile devices</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2026-05-21T18:02:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aasheesh Singh</p>
    <p><b>Summary:</b> Serving personalized content on mobile devices has traditionally required pooling sensitive user data on centralized servers, a practice increasingly at odds with modern privacy expectations and geographical regulations. We present a two-stage federated recommendation system pipeline for mobile devices, built around a principled separation between non-sensitive user preference data and sensitive mobile context data that never leaves the device. The first stage runs a collaborative filtering model on non-sensitive app-context data in the cloud to generate a shortlist of relevant items. The second stage re-ranks these candidates on-device using sensitive mobile signals, with only model updates/gradients ever leaving the device. We validate the approach on MovieLens, UCI Human Activity Recognition, and a proprietary pilot dataset, and deliver a production-ready implementation as a Kotlin Multiplatform library deployable on Android and iOS.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.22898v1">FIRMA: FIbonacci Ring Model Aggregation for Privacy-preserving Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-21T16:06:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rachid Hedjam</p>
    <p><b>Summary:</b> Federated learning protocols face a structural trilemma: canonical server-based aggregation~\cite{mcmahan2017} creates a single point of failure and gradient inversion risk; decentralised ring-gossip alternatives~\cite{hu2019segmented} expose classification heads to semi-honest peers via uninformed uniform weights; and personalised methods~\cite{collins2021exploiting} reintroduce central aggregation. No existing protocol simultaneously achieves server-free operation, permanently private heads, ring topology, and principled asymmetric neighbour weighting. We propose FIRMA (\textbf{FI}bonacci \textbf{R}ing \textbf{M}odel \textbf{A}ggregation), a family of three progressively enhanced federated learning protocols: 1) \fibfl\ establishes the foundation: server-free ring aggregation with Fibonacci-weighted neighbour blending and permanently private classification heads. 2) \fibflp\ augments this with accuracy-gated neighbour suppression, selectively down-weighting poorly-converged peers while preserving the Fibonacci directional bias. 3) \fibflpp, the full system, completes the family with a 2-opt ring permutation that maximises adjacent-client class diversity, global ring coverage via $K_g{=}\lceil N/2\rceil$ gossip passes, and cosine-annealed self-retention calibration. We establish a convergence rate bound and three supporting propositions governing normalisation, coverage, retention, and diversity optimality. Systematic experiments across 28 configurations -- four benchmarks crossed with seven heterogeneity regimes -- demonstrate that \fibflpp\ surpasses \fedavg\ in all 12 label-skew configurations, with a peak advantage of $+20.7$\,pp on CIFAR-10 at $K{=}1$. Under Dirichlet heterogeneity, \fibflpp\ is the Pareto-dominant method among all server-free protocols, achieving the highest accuracy in 17 of 28 configurations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.21780v1">Provable Robustness against Backdoor Attacks via the Primal-Dual Perspective on Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-20T22:17:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aman Saxena, Jan Schuchardt, Yan Scholten, Stephan Günnemann</p>
    <p><b>Summary:</b> Randomized smoothing is a powerful tool for certifying robustness to adversarial perturbations, including poisoning attacks via randomized training and evasion attacks via randomized inference. Extending these guarantees to backdoor attacks, where training and test data are jointly perturbed, remains challenging because training- and test-time randomized mechanisms must be analyzed within a single robustness certificate. We address this by connecting randomized smoothing to the dual view of differential privacy through privacy profiles, which provide a numerical procedure for composing heterogeneous mechanisms. The resulting framework enables tight, modular, end-to-end certification of complex, composed mechanisms while leveraging existing analyses of differentially private mechanisms. We instantiate the framework for DP-SGD and Deep Partition Aggregation with inference-time smoothing, deriving joint robustness guarantees against both training-time and inference-time attacks. Experiments on MNIST and CIFAR-10 demonstrate the effectiveness of our framework. Overall, we provide a principled and general framework for using composite mechanisms to certify robustness under complex threat models that better capture the capabilities of real-world adversaries.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.21421v2">AIGaitor: Privacy-preserving and cloud-free motion analysis for everyone, using edge computing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-05-20T17:14:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lauhitya Reddy, Trisha M. Kesar, Hyeokhyen Kwon</p>
    <p><b>Summary:</b> Motion capture is the gold standard for measuring human movement, but clinical use remains limited by cost, technical complexity, and privacy concerns. AIGaitor is a privacy-preserving, cloud-free motion analysis system that runs markerless monocular motion-capture pipelines and downstream deep-learning analysis entirely on a consumer smartphone using on-device neural accelerators. To motivate its design, we surveyed 74 rehabilitation clinicians: 92 percent said they would adopt an accurate, cost-effective, easy-to-use AI gait analysis tool, while 79.7 percent cited operating cost, 68.9 percent insufficient training, and 64.9 percent privacy concerns as leading barriers. We then optimized and benchmarked mobile iOS implementations of current monocular pipeline components, including 2D and 3D pose estimation, pose optimization, skeleton-based deep-learning analysis, and a vision-language model. A Time-Priority end-to-end on-device pipeline processes a 10 s 4K 60 fps video clip in 77 s on an iPhone 14, matching or beating the same pipeline on a high-end NVIDIA H200 cloud server when network transfer is included: 94 s at global mobile-average uplink and 66 s at developed-world Wi-Fi. Lightweight models such as ViTPose-s achieve real-time keypoint extraction, and skeleton-based action-recognition models provide sub-millisecond gait classification on the same clip. To our knowledge, AIGaitor is the first monocular system to demonstrate end-to-end on-device motion capture and downstream deep-learning analysis, supporting clinically applicable movement analysis that is low-cost, private, and accessible to smartphone users.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.21376v1">Privacy Without Remedy: An Assessment of Data Broker Compliance with California Privacy Law</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-05-20T16:39:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anna-Maria Gueorguieva, Jennifer King, Apoorva Panidapu, Daniel E Ho</p>
    <p><b>Summary:</b> California's consumer privacy law is widely deemed to be the most protected in the United States, one of the few to expressly regulate third party entities that buy and sell consumer data (data brokers). We offer the first empirical assessment of data broker compliance with the 2018 California Consumer Privacy Act (CCPA) and the 2023 Delete Act, which requires data brokers to register with the state and report consumer rights requests metrics annually. First, we demonstrate that only 9% of 522 registered data brokers were fully compliant with transparency requirements after the Delete Act took effect, although we do identify slight improvements over time. Second, we descriptively characterize wide heterogeneity across data brokers in the volume of consumer rights requests received, with many reporting none. We bring in external business data to explore correlates associated with this variation, a challenge given the general lack of opacity into broker business practices. Third, in an audit of a sample of 250 data brokers' consumers request processes, we find that 43% make it impossible for consumers to exercise all privacy rights and 64% introduce at least one design feature that creates substantial friction into the consumer request process. Last, we show how these deficiencies stem from the decentralization of compliance decisions to brokers themselves, enforcement limitations, and regulatory ambiguity. We articulate reforms that could improve consumer privacy, transparency in broker practices, and compliance with these laws.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.21269v1">Transforming Privacy Artifacts into Accessible Reports for Non-Technical Stakeholders</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2026-05-20T14:58:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zoe Pfister, Clemens Sauerwein, Benedikt Dornauer, Tina Mersch, Christian Wolf, Ruth Breu, Michael Vierhauser</p>
    <p><b>Summary:</b> The transition toward Industry 5.0 is reshaping industrial work environments with an emphasis on human-centricity, enabling close collaboration between humans and machines to enhance productivity and flexibility. However, such systems typically require monitoring of human workers and operators, often involving sensitive data, raising significant privacy concerns. As a result, affected workers and unions frequently reject human-machine collaboration features due to a lack of transparency regarding privacy threats and implemented mitigation strategies. To enable early stakeholder involvement, establish trust, and support informed decision-making, privacy implications must be communicated in a way understandable to non-technical stakeholders. Yet, current Requirements Engineering (RE) practices provide limited methodological support for making privacy threats and mitigations accessible to non-technical stakeholders (e.g., individual workers or their representative unions). In this RE@Next paper, we propose a conceptual framework that guides software design from human monitoring-related use cases and requirements to informed decision-making guidance focusing on non-technical stakeholders. Building on principles such as Privacy by Design, the framework leverages Large Language Models (LLMs) to transform technical artifacts into accessible privacy reports. We share initial insights from two industry use cases, evaluate the quality of the generated reports, and outline future research directions toward integrating privacy transparency into RE processes for human-centric industrial systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.20944v1">Privacy-Preserving Distributed Optimization Under Time Constraints Using Secure Multi-Party Computation and Evolutionary Algorithms</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Neural and Evolutionary Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-20T09:29:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sebastian Gruber, Tobias Harzfeld, Christoph G. Schuetz, Florian Wohner, Thomas Lorünser</p>
    <p><b>Summary:</b> In distributed optimization, multiple parties collaborate to find an optimal solution to a problem. Privacy-preserving distributed optimization uses techniques, such as secure multi-party computation (MPC), to protect the private inputs of each party. In time-critical settings, the runtime overhead introduced by privacy-preserving computations may prevent the optimization from finishing within the deadline. This paper presents an approach for privacy-preserving distributed optimization in time-critical settings that combines evolutionary algorithms for solution search and MPC for the evaluation of solutions. The approach reduces the impact of privacy-preserving computations on runtime and allows to return solution within the deadline. Obfuscation of evaluation results provides additional protection for private inputs from an honest-but-curious platform provider, but introduces a potential trade-off between protection and solution quality. This trade-off is investigated in experiments using a genetic algorithm for both the single-objective assignment problem and the traveling salesperson problem, as well as NSGA-II for the multi-objective assignment problem.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.20765v1">Precision and Privacy in Distributed Quantum Sensing: A Quantum Fisher Information Duality</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-05-20T06:07:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Farhad Farokhi</p>
    <p><b>Summary:</b> We establish a quantum Fisher information (QFI) duality for distributed quantum sensor networks with local phase encoding. For any $N$-qubit probe state, where $N$ denotes the number of sensors, $F_Q(\boldsymbol{w}^\top \boldsymbolθ) + F_Q(\boldsymbol{v}^\top \boldsymbolθ) \leq N$ for all unit orthogonal sensing directions $\boldsymbol{w}$ and $\boldsymbol{v}$, with equality for all equatorial states when $N=2$ and for Greenberger--Horne--Zeilinger (GHZ) states when $N\geq 2$. Heisenberg-limited precision for direction $\boldsymbol{w}$, $F_Q(\boldsymbol{w}^\top \boldsymbolθ)=N$, saturates the bound and simultaneously forces zero QFI for all other independent directions. This can be interpreted as the condition for parameter privacy in distributed quantum sensing: attaining Heisenberg-limited precision for the sensing target renders all alternative privacy-intrusive estimations impossible.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.20521v1">An exponential mechanism based on quadratic approximations for fine-tuning machine learning models with privacy guarantees</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-19T21:43:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hoang Tran, Jorge Ramirez, Jiayi Wang, Alberto Bocchinfuso, Christopher Stanley, M. Paul Laiu</p>
    <p><b>Summary:</b> Fine-tuning adapts a pretrained machine learning model to a small, sensitive dataset, but this process risks memorizing individual new data points, making the model vulnerable to adversaries who seek to extract sensitive information. In this work, we develop a randomized algorithm based on the exponential mechanism for fine-tuning while ensuring differential privacy. Our key idea is to construct a simple utility function that combines a local quadratic approximation of the pretrained model with information from the new dataset. The resulting exponential mechanism admits exact sampling from a multivariate normal distribution in closed form. We establish theoretical privacy guarantees, sensitivity bounds, and accuracy estimations for our method. We further introduce a random-projection strategy that makes the approach scalable to high-dimensional models. Numerical experiments on the MNIST benchmark and the MIMIC clinical dataset demonstrate competitive performance against existing differentially private fine-tuning techniques.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.20505v1">Privacy-by-Design Adaptive Group Assignment for Digital Lifestyle Coaching at Scale</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-05-19T21:22:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nariman Mani, Salma Attaranasl</p>
    <p><b>Summary:</b> Digital lifestyle coaching systems must personalize peer support as user behavior and engagement evolve while preventing personally identifiable information (PII) and sensitive health information from leaking into analytics and AI pipelines. This creates a practical tension: personalization requires longitudinal linkability, while privacy engineering requires minimization, separation, and controlled re-identification. We present PRISM-Coach, a stakeholder-centered architecture and adaptive peer-group assignment method for privacy-preserving lifestyle coaching. PRISM-Coach separates each user into four bounded views: Identity, Operational, Learning, and Coaching, each with distinct access controls and risk profiles. Building on this separation, the system uses vault-based controlled identity restoration, a privacy-constrained contextual bandit to assign users to eligible peer groups under coach-capacity and stability constraints, and a human-in-the-loop coaching assistant that generates de-identified summaries and draft messages without sending raw PII or PHI to external AI services. We instantiate PRISM-Coach in a commercially deployed lifestyle coaching platform and evaluate it using three years of telemetry from approximately 2,800 users and an in-app needs assessment survey. At the population level, daily check-in adherence increases from 0.35 to 0.68, and engagement rises to 1.35 baseline. In a matched 19-week comparison window, the AI-enabled workflow achieves adherence of 0.74 versus 0.48 under static grouping and higher average weight loss: 5.2 kg versus 3.1 kg. Survey results show that 82% report positive perceived benefit, and 92% report increased privacy confidence after transparency disclosures. These results position PRISM-Coach as a practical blueprint for privacy-by-design adaptive learning systems in everyday wellness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.20450v1">SMA-DP: Spectral Memory-Aware Differential Privacy for Deep Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-19T20:02:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohammad Partohaghighi, Roummel Marcia</p>
    <p><b>Summary:</b> Differentially private stochastic gradient descent (DP-SGD) enables private deep learning through per-example clipping and calibrated Gaussian noise, but its high-variance updates can reduce utility on challenging datasets. We propose \textbf{SMA-DP-SGD}, a \textbf{Spectral Memory-Aware Differentially Private Stochastic Gradient Descent} method that augments DP-SGD with a fractional memory branch built only from previously privatized noisy releases. WeightWatcher-inspired power-law spectral exponents provide group-wise reliability signals, instantiated layer-wise in our experiments, to adapt the decay and effective memory depth. Private-history alignment, norm matching, and warm-up activation stabilize the memory contribution. Privacy remains transparent: conditioned on the private release history, the memory branch is fixed, and the only newly data-dependent term is the current clipped sum scaled by a fixed coefficient \(β\). Hence, SMA-DP-SGD preserves a clean conditional sensitivity structure and exactly recovers group-wise DP-SGD when \(β=1\). Experiments on CIFAR-100, CIFAR-10, and MNIST show competitive or superior accuracy over several DP optimization baselines, with the largest gains on CIFAR-100 and CIFAR-10. CIFAR-10 ablations show that \(β\) controls the privacy--utility trajectory, while spectral and memory diagnostics confirm a controlled short-to-moderate effective memory depth and a small memory-branch ratio. Runtime analysis shows that the mechanism incurs additional overhead, about \(2.94\times\) DP-SGD in our CIFAR-10 implementation, revealing a practical trade-off between adaptive private memory and computational cost.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.19847v2">Auditing Privacy in Multi-Tenant RAG under Account Collusion</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-19T13:41:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Florian A. D. Burnat</p>
    <p><b>Summary:</b> Multi-tenant RAG services often treat the account as the privacy boundary: each account receives an $(\varepsilon_{\text{acc}},δ_{\text{acc}})$-DP retrieval guarantee against the tenant index. We show that this framing understates leakage under same-index account collusion. For Gaussian noise-then-select retrieval, $k$ coordinated same-tenant accounts compose to joint leakage $Θ(\sqrt{k}\,\varepsilon_{\text{acc}})$, not $\varepsilon_{\text{acc}}$; we give a matching membership-inference attack and validate the predicted $\sqrt{k}$ AUC trend in scalar, top-$K$, trained-embedder, and production-scale HNSW settings. We then give a verifier-runnable audit protocol that attests noise-then-select retrieval and reports $(\textsf{PASS},\varepsilon_{\text{audit}})$ for coalitions up to a declared cap $k_{\max}$, without disclosing the index or changing the retrieval decision rule. The claim is retrieval-channel only: generation-channel leakage and adversarially robust coalition-size estimation are complementary audit predicates.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.19742v4">The Privacy Subsidy in Glosten-Milgrom: Bid-Ask Spread and Welfare under Flip-Noise Direction Observation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Probability-5BC0EB"> 
  <p><b>Published on:</b> 2026-05-19T12:12:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuki Nakamura</p>
    <p><b>Summary:</b> We derive a closed-form bid-ask spread and welfare decomposition for the Glosten-Milgrom 1985 sequential-trading model when the market maker observes the trade direction perturbed by a binary flip channel of probability $η$ -- a natural information-theoretic model of privacy mechanisms acting on the direction signal. Under a committed Bayesian market-maker pricing rule, the equilibrium spread is $μ(1-2η)Δ$, where $μ$ is the informed-trader fraction and $Δ= v_H - v_L$ the value range. The welfare decomposition identifies a per-trade transfer $μηΔ$ from the protocol's liquidity pool to traders -- the "privacy subsidy", mirroring the Gaussian-Kyle analog established in prior work. The result extends the privacy-subsidy concept from continuous Gaussian to discrete two-state microstructure, demonstrating robustness across both classical models. Primary application: MPC-based matching engines with $\varepsilon$-differentially-private direction disclosure, where the engine prices on a noisy direction signal.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.19578v2">Lens Privacy Sealing: A New Benchmark and Method for Physical Privacy-Preserving Action Recognition</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-19T09:21:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mengyuan Liu, Ziyi Wang, Peiming Li, Junsong Yuan</p>
    <p><b>Summary:</b> RGB camera-based surveillance systems enable human action recognition for public safety and healthcare, yet raise serious privacy concerns. Existing methods rely on post-capture algorithms, which fail to protect privacy during data acquisition. We propose Lens Privacy Sealing (LPS), a simple hardware solution that physically obscures camera lenses with adjustable laminating film, providing pre-sensor privacy protection at minimal cost. Unlike software methods or expensive engineered optics, LPS achieves strong privacy through stochastic multi-layer scattering that is physically irreversible. We introduce the P$^3$AR dataset for privacy-preserving action recognition, featuring both large-scale replay-captured (P$^3$AR-NTU, 114K videos) and real-world collected (P$^3$AR-PKU) subsets with privacy attribute annotations. To handle video degradation from LPS, we propose MSPNet, a single-stage framework incorporating Inter-Frame Noise Suppressor (IFNS) and Cross-Frame Semantic Aggregator (CFSA), enhanced by contrastive language-image pre-training for robust semantic extraction. Extensive experiments demonstrate that MSPNet with IFNS and CFSA nearly doubles action recognition accuracy compared to baseline methods while suppressing identity recognition to low levels. Comprehensive validation shows LPS achieves a superior privacy-utility trade-off compared to state-of-the-art hardware methods, resists reconstruction attacks including PSF inversion and data-driven recovery, and generalizes robustly across optical configurations and challenging environments. Code is available at https://github.com/wangzy01/MSPNet.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.19474v1">Worst-Case Utility Privacy Mechanism via Pointwise Maximal Leakage</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-05-19T07:24:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ci Song, Tobias J. Oechtering</p>
    <p><b>Summary:</b> We propose a discrete privacy mechanism exploiting beneficial properties of the novel privacy measure Pointwise Maximal Leakage (PML). Given the utility assignment characterized by every input-output letter pair, we study the mechanism design problem that satisfies PML privacy guarantees and maximizes the worst-case utility. Unlike popular privacy measures like Differential Privacy (DP), PML allows us to set some conditional probabilities in the mechanism to be zero and thereby preventing the occurrence of some low utilities while preserving a strict PML constraint. We show that the utility-safe mechanism, with low computational complexity, is optimal for the worst-case utility problem with an additional constraint on the output support set. We finally demonstrate the effectiveness in several numerical experiments. Due to DP's inability to have zeros in the mechanism, the design of privacy mechanisms that optimize the worst-case utility is underexplored, and this work shows that PML is a privacy measure that is perfectly suited for this purpose.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.19312v1">MultiBallot: Verifiable and privacy-preserving E-Collecting in the Swiss setting</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-19T03:48:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Florian Moser, Léo Louistisserand</p>
    <p><b>Summary:</b> As part of the political process, citizens may participate in signature collections to influence policy changes. In Switzerland, this even results in legally binding acts, similar to an election system. In this work, we first derive a realistic setting for e-collecting in Switzerland, based on the setting established for e-voting. Then, we propose a secure protocol in this setting, achieving both privacy and verifiability under realistic trust assumptions. Notably, participation privacy is guaranteed without assuming an anonymous channel, by considering the fact that at any given point in time, many collections are active in parallel.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.19127v1">POLAR-Bench: A Diagnostic Benchmark for Privacy-Utility Trade-offs in LLM Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-18T21:27:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qiaoyuan Zheng, Yiqu Yang, Qi Gao, Imanol Schlag</p>
    <p><b>Summary:</b> LLM agents increasingly have access to private user data and act on the user's behalf when interacting with third-party systems. The user defines what may and must not be shared, and the agent must robustly follow that intent even when third-party systems behave adversarially. We introduce POLAR-Bench (Policy-aware adversarial Benchmark), in which a trusted model with a privacy policy and a task converses with a third-party model that adversarially probes for both task-relevant and protected attributes. Across 10 domains and 7,852 samples, we score privacy and utility by deterministic set-membership and vary privacy policy dimension and attack strategy along two orthogonal axes, producing a 5 times 5 diagnostic surface per model. Our results reveal a sharp split: current frontier models withhold over 99% of protected attributes, while smaller open-weight models in the 1--30B range, the class users most commonly run as their own trusted agent on-device or via private inference, score notably worse, with the weakest leaking over half. POLAR-Bench thus localizes where each model's intent-following breaks down, providing a foothold for privacy alignment where it matters most.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.19032v1">Personalized Face Privacy Protection From a Single Image</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-05-18T18:56:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zachary Yahn, Fatih Ilhan, Tiansheng Huang, Selim Tekin, Sihao Hu, Yichang Xu, Margaret Loper, Ling Liu</p>
    <p><b>Summary:</b> Photos of faces uploaded online are vulnerable to malicious actors who can scrape facial images from online sources and intrude on personal privacy via unauthorized use of facial recognition models. This paper presents FaceCloak, a novel personalized face privacy protection system, which can generate defensive identity-specific universal face privacy masks from a single image of a user, causing facial recognition to fail. FaceCloak introduces a three-stage personalized face perturbation learning methodology: (1) It generates a small set of high-variety synthetic face images of a person based on a single image of the person. (2) It learns face cloaking by adding more protection to key facial-identity leakage regions through iterative perturbation generation over the small set of synthetic images, effectively shifting a user's identity embedding towards a distant anchor identity and away from a similar one. (3) It generates a personalized identity-protective mask in the form of pixel-wise cloaking, which is light-weight and can be efficiently applied to any facial image of a user while maintaining good perceptual quality. Extensive experiments on three popular face datasets across ten recognition models show the effectiveness of FaceCloak compared to 29 other existing representative methods. Code is available at https://github.com/zacharyyahn/FaceCloak</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.18455v1">OrganicHAR: Towards Activity Discovery in Organic Settings for Privacy Preserving Sensors Using Efficient Video Analysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-05-18T14:20:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Prasoon Patidar, Riku Arakawa, Ricardo Graça, Rúben Moutinho, Adriano Soares, Ana Vasconcelos, Filippo Talami, Joana Couto da Silva, Inês Silva, Cristina Mendes Santos, Mayank Goel, Yuvraj Agarwal</p>
    <p><b>Summary:</b> Deploying human activity recognition (HAR) at home is still rare because sensor signals vary wildly across houses, people, and time, essentially requiring in-situ data collection and training. Prior approaches use cameras to generate training labels for privacy-preserving sensors (LiDAR, RADAR, Thermal), but this forces sensors to detect predefined activities that cameras can see yet the sensors themselves cannot reliably distinguish. In this work, we introduce OrganicHAR, an activity discovery framework that inverts this relationship by placing sensor capabilities at the center of activity discovery. Our approach identifies naturally occurring signal patterns using privacy-preserving sensors, leverages Vision Language Models (VLMs) only during these key moments for scene understanding, and discovers discrete activity labels at granularities that these sensors can reliably detect. Our evaluation with 12 participants demonstrates OrganicHAR's effectiveness: it achieves 79% accuracy for coarse (4-5) activities using only basic ambient sensors (radar, lidar, thermal arrays), and 73% accuracy for fine-grained (8-9) activities when a wearable IMU, depth, and pose sensor are added. OrganicHAR maintains 77% accuracy on average across configurations while discovering 4-8 categories per user (15 across all users) tailored to each environment and sensor capabilities. By triggering video processing only at key moments identified by local sensors, we reduce queries to VLM by 90%, enabling practical and privacy-preserving activity recognition in natural settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.18246v1">Privacy Preserving Reinforcement Learning with One-Sided Feedback</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-18T11:41:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lin William Cong, Guangyan Gan, Hanzhang Qin, Zhenzhen Yan</p>
    <p><b>Summary:</b> We study reinforcement learning (RL) in multi-dimensional continuous state and action spaces with one-sided feedback, where the agent receives partial observations of the state and obtains reward information for only a subset of the state-action space at each time step. This setting introduces substantial challenges in both learning efficiency and privacy preservation. To address these challenges, we propose POOL, a novel privacy-preserving RL algorithm. We conduct a comprehensive theoretical analysis of POOL, deriving a sample complexity bound that matches the known lower bounds for non-private RL. Here, E_rho denotes the privacy parameter, H is the time horizon, and alpha is the optimality-gap parameter. Our findings show that it is possible to enforce strong privacy guarantees while maintaining high learning efficiency, marking a significant step toward practical, privacy-aware RL in multi-dimensional environments with one-sided feedback.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.18133v1">An Empirical Study of Privacy Leakage Chains via Prompt Injection in Black-Box Chatbot Environments</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2026-05-18T09:38:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hongjang Yang, Hyunsik Na, Daeseon Choi</p>
    <p><b>Summary:</b> LLM-based chatbot agents increasingly process user requests by combining natural-language reasoning with external tools such as web browsing. These capabilities improve usability, but they also create attack surfaces when untrusted external content is processed as part of a user' s task. This paper studies a privacy-leakage attack chain based on indirect prompt injection in black-box chatbot environments, where the attacker has no access to model weights, system prompts, or agent implementation details including how a trajectory is actually managed during its processing for a query. We first analyze how an attacker can hijack an agent' s intended task by crafting external content that appears benign to the victim while inducing the agent to execute an attacker-defined objective. We then evaluate a new prompt-injection technique, called exemplification, which uses a bridge in the external content to reframe the user prompt and the benign beginning of the retrieved page as few-shot examples before appending the attacker' s objective. We compare its attack success rate with a prior fake-completion technique. Finally, we demonstrate a proof-of-concept data-exfiltration chain using fictitious personal information in a controlled setting. Our results suggest that prompt injection, jailbreak-style instruction steering, and web-tool invocation can be combined into a feasible privacy-leakage path in deployed chatbot agents.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.23989v1">Towards trustworthy agentic AI: a comprehensive survey of safety, robustness, privacy, and system security</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-17T10:26:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jinhu Qi, Muzhi Li, Jiahong Liu, Yuqin Shu, Dianzhi Yu, Shicheng Ma, Wenqian Cui, Yiyang Zhao, Yiyi Chen, Ruoxi Jiang, Irwin King, Zenglin Xu</p>
    <p><b>Summary:</b> Agentic AI systems -- Large Language Models (LLMs) augmented with planning, tool use, memory, and long-horizon interactions -- can execute complex tasks autonomously, but their multi-step trajectories introduce new failure modes that challenge trustworthiness. This survey provides a focused examination of trustworthy agentic AI through two core dimensions that are critical for high-risk deployments: Safety and Robustness, and Privacy and System Security. For each dimension, we clarify key concepts, identify where risks emerge along the agent workflow, and summarize stage-targeted mitigation strategies. Other trustworthiness aspects (value alignment, transparency, fairness, and accountability) are discussed as relevant context rather than parallel chapters. To support consistent comparison and deployment decisions, we consolidate evaluation into a unified metrics-and-benchmarks hub, emphasizing both outcome and process signals (e.g., constraint violations, trace completeness, and adversarial success rates) and offering scenario-to-metric guidance for release gating. We conclude by outlining open challenges such as self-evolving agents, runtime monitoring and verification, privacy-preserving personalization, and the trust-utility trade-off, and present a case study of real-world security failures in open-source agentic systems. Our goal is to serve as a practical reference for researchers and practitioners building trustworthy agentic systems in high-stakes environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.17042v1">Thermal-Only Crowd Counting with Deployment-Time Privacy Protection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-05-16T15:21:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yifei Qian, Zhongliang Guo, Chun Tong Lei, Bowen Deng, Chun Pong Lau, Xiaopeng Hong, Michael P. Pound</p>
    <p><b>Summary:</b> While RGB-Thermal crowd counting has shown promise, the paradigm faces critical limitations: RGB data raises privacy concerns in public surveillance, and multi-modal misalignment degrades fusion performance. We propose the first thermal-only framework specifically designed for privacy-conscious crowd counting, eliminating RGB dependency at inference time and substantially reducing the privacy exposure associated with continuous RGB capture in public surveillance deployments. To mitigate thermal ambiguity, we leverage depth-to-RGB diffusion models as a cross-modal bridge, extracting discriminative features that enhance thermal representations. Critically, we demonstrate that single-step LCM denoising yields features most faithful to the structural content of the depth conditioning signal, while multi-step approaches progressively decouple features from the conditioning input and accumulate errors that degrade counting accuracy. Experiments on RGBT-CC and DroneRGBT datasets show our method achieves competitive performance against state-of-the-art RGB-T fusion methods, while requiring only thermal input during inference, eliminating the need for continuous RGB capture that constitutes the primary privacy concern in real-world surveillance deployment. The code will be made publicly available.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.17039v1">Privacy-Preserving Generation Fraud Detection for Distributed Photovoltaic Systems: A Solar Irradiance-Fused Federated Learning Framework</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computational Engineering, Finance, and Science-5BC0EB">
  <p><b>Published on:</b> 2026-05-16T15:19:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaolu Chen, Chenghao Huang, Yanru Zhang, Hao Wang</p>
    <p><b>Summary:</b> The wide adoption of residential photovoltaic (PV) systems introduces new challenges for generation fraud detection (FD). Unlike traditional electricity theft detection, which focuses on electricity consumption-side behavior, PV generation fraud detection (PVG-FD) is complicated by the inherent intermittency and uncertainty of PV generation. The distributed nature of PV systems poses further challenges for centralized PVG-FD approaches due to scalability and privacy concerns. This paper develops a privacy-preserving distributed PVG-FD framework based on federated learning (FL). In this framework, a utility company manages multiple household communities, where each of which is equipped with a local detector. The framework integrates a novel detection model architecture with privacy-preserving global collaboration. Each community's local model fuses PV generation and weather data via a co-attention mechanism to detect discrepancies critical for PVG-FD. The FL framework enables cross-community collaboration by aggregating model parameters and prototypes, leveraging global knowledge sharing with local refinement while preserving privacy. It also uses prototype alignment to address class imbalance by enhancing fraud sample representation. Extensive experiments on a real-world residential PV dataset validate the effectiveness of the developed method and demonstrate that it outperforms state-of-the-art FL methods across various scenarios. The results also show its scalability across varying community sizes and strong robustness to class imbalance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.17034v2">Privacy Policy Enforcement Guardrails for Data-Sensitive Retrieval-Augmented Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-16T15:08:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Osama Zafar, Alexander Nemecek, Yiqian Zhang, Wenbiao Li, Debargha Ganguly, Vikash Singh, Vipin Chaudhary, Erman Ayday</p>
    <p><b>Summary:</b> Standard PII filters often miss contextual data leakage in RAG systems, such as non-regulated attribute clusters that collectively identify individuals. We introduce a Privacy Policy Enforcement (PPE) framework using dual one-class density estimators with fused text embeddings and a calibrated abstain region for out-of-distribution inputs. Using an axis-stratified, multi-LLM synthetic data pipeline across medicine, finance, and law, we found that traditional Gaussian Mixture baselines fail on borderline-safe stress tests by focusing on linguistic register rather than content.
  Our proposed T3+OCSVM detector, trained on safe and borderline-safe data, achieves a borderline AUROC of 0.93+ while reducing false positives by 44-55 percentage points and maintaining millisecond latency. Compared to supervised MLP classifiers or 14B-parameter LLM judges, our framework offers superior operational suitability, as the former suffers from high abstention rates and the latter from latency and calibration issues. This methodology provides a robust stress-testing standard for any synthetic-data-trained classifier.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.16812v2">Jacobian-Guided Anisotropic Noise Reshaping for Enhancing Representation Utility under Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-16T05:01:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Youngmok Ha, Viktor Schlegel, Yidan Sun, Anil Anthony Bharath</p>
    <p><b>Summary:</b> While Local Differential Privacy (LDP) serves as a foundational primitive for distributed data collection, its stringent noise injection requirement often leads to severe degradation in data utility. This degradation stems from the task-agnostic nature of conventional LDP mechanisms, which inject noise uniformly across all dimensions regardless of their relative importance to the downstream objective. To address this issue, we propose a novel approach that mitigates noise in task-relevant subspaces of the data representation. Our method identifies task-critical subspaces via the Jacobian matrix of the public downstream model, selectively attenuates noise along those dimensions, and reshapes the isotropic noise of standard LDP into an anisotropic distribution. This method preserves the uniform per-dimension privacy budget while heterogeneously modulating noise impact across dimensions, thereby substantially enhancing data utility. Furthermore, our approach generalizes to both linear and non-linear models and integrates seamlessly with existing mechanisms. Extensive experiments on CIFAR-10-C (Brightness corruption at the highest severity level 5) demonstrate that integrating our approach improves the utility of PrivUnit2 and PrivUnitG by approximately 20\% at $ε=7.5$. The source code is available at https://github.com/ymha/jacobian-anr-ldp.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.16219v1">The Privacy Price of Tail-Risk Learning: Effective Tail Sample Size in Differentially Private CVaR Optimization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2026-05-15T17:30:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> El Mustapha Mansouri</p>
    <p><b>Summary:</b> Differential privacy changes the effective sample size governing CVaR learning. For tail mass $τ$, the privacy-relevant sample size is not $n$, but $nτ$; equivalently, the effective private tail sample size is $εnτ$. Private CVaR excess risk decomposes into ordinary tail-risk statistical error and a privacy price. This decomposition is complete for scalar estimation and finite classes: scalar estimation has rate $Θ(B \min\{1,(nτ)^{-1/2}+(εnτ)^{-1}\})$, and finite classes of size $M$ have rate $Θ(B \min\{1,\sqrt{\log(2M)/(nτ)}+\log(2M)/(εnτ)\})$. These complete rates hold under pure DP, and their lower bounds extend to approximate DP in the stated small-$δ$ regimes. For convex Lipschitz learning, modular upper and lower reductions show that the CVaR-specific privacy term necessarily scales as $1/(εnτ)$, with dimension dependence inherited from private stochastic convex optimization. Together, these results identify ordinary private learning on $Θ(nτ)$ informative tail records as the canonical hard subproblem inside private CVaR learning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.15934v1">Privacy is Fungibility: Why Endogenous Tokens Are Not Money</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-05-15T13:15:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alex Lynham, Geoffrey Goodell</p>
    <p><b>Summary:</b> In this paper, we make a case that endogenous tokens such as cryptoassets are not money. First, we define and classify tokens found on public, permissionless ledgers, contrasting them with privately issued stablecoins and proposed CBDC designs. We then discuss the work of Kahn et al in Money is Privacy on cash versus simplified credit, and we extend their analysis to the situation found on most public, permissionless ledgers. Many public, permissionless ledgers utilize an account-based abstraction for balances, resulting in a default state that maps onto the most harmful models of agent interaction enumerated in Money is Privacy. The conclusion is threefold: that most blockchain economies lack a cash-like primitive; that stablecoins do not intrinsically fulfil this role; and that the reliance of a network on an endogenous token for security exposes holders even of a privacy-preserving asset to the same risk, if that asset relies on the same global ledger state as the endogenous token.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.15746v5">The Privacy Subsidy: Kyle's $λ$ under Noise-Perturbed Order-Flow Observation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Probability-5BC0EB"> 
  <p><b>Published on:</b> 2026-05-15T08:56:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuki Nakamura</p>
    <p><b>Summary:</b> Privacy-preserving cryptocurrency exchanges alter what the pricing mechanism observes about order flow. We derive the unique linear Kyle equilibrium when a committed Bayesian market maker observes order flow perturbed by independent Gaussian privacy noise. The price-impact coefficient and informed-trader strategy rescale by reciprocal factors of the privacy parameter (one down, one up), so their product is invariant. A welfare decomposition then identifies a closed-form per-period transfer from the protocol's LP pool to traders -- the "privacy subsidy", the break-even fee any privacy-aggregated exchange must charge. The result is the single-period closed-form privacy-noise analog of Loss-Versus-Rebalancing (Milionis et al. 2022). The primary application is shielded AMMs with explicit additive-noise injection (e.g., differential privacy); related designs (batched swaps, sealed-bid auctions, oracle-pegged crossings) require separate frameworks that we leave to future work.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.15743v1">Preserving Topology Privacy of Network Systems by Feedback: Conditions and Distributed Design</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2026-05-15T08:52:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yushan Li, Jiabao He, Julien M. Hendrickx, Dimos V. Dimarogonas</p>
    <p><b>Summary:</b> This paper develops a feedback-based method to preserve the topology privacy of consensus protocols in network systems. The key idea is to intentionally violate topology identifiability conditions, thereby preventing unique or accurate recovery of the true topology from available observations, while preserving the intended consensus behavior. This problem is challenging because the feedback magnitude directly reflects the privacy level of edges, while it is strongly coupled with the consensus convergence and constrained by local communications at each node. To begin with, we derive the feedback conditions of both partial and full observation cases, where the topology unsolvability from observation data is characterized in the former, and the solution space that enforces topology inaccuracy from data is constructed in the latter. Then, we propose a novel distributed topology modification design under limited privacy budgets, and establish the performance guarantees through a controllable tradeoff between the consensus deviation and the topology privacy. Finally, we develop a low-complexity heuristic algorithm to achieve optimal privacy preservation on existing edges. Comparative simulations validate the effectiveness and outperformance of the proposed preservation design.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.15560v1">Privacy-Preserving Federated Radio Map Learning for Wireless Digital Twins via Adaptive Noise Allocation</a></h3>
  
  <p><b>Published on:</b> 2026-05-15T03:00:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jijia Tian, Hao Wang, Mu Jia, Yi Wang, Junting Chen, Pooi-Yuen Kam</p>
    <p><b>Summary:</b> Radio maps provide a foundational data layer for wireless digital twins, and federated learning offers a natural framework for their distributed construction without centralizing raw radio environment data. However, the exchanged client model updates may still leak transmitter-location information, even when the underlying measurement data are never shared. Existing noise-based privacy defenses inject perturbation either uniformly across all uploaded coordinates or according to a fixed static rule, thereby ignoring the architecture-specific structure of this leakage. This paper proposes a budget-constrained adaptive noise allocation mechanism that redistributes a fixed perturbation budget across transmitter-sensitive upload groups identified from the two-stage RadioUNet architecture. The proposed method uses low-dimensional upload statistics to dynamically adjust group-wise noise scales and is integrated locally before client upload transmission. We evaluate the framework on a federated radio map learning task under a unified noise multiplier, comparing it against uniform and structure-aware baselines using reconstruction mean squared error and transmitter localization error as metrics. Results show that adaptive allocation achieves the strongest privacy protection while maintaining the best reconstruction quality among all noise-based defenses under a matched perturbation budget.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.18862v1">Towards Family-Grouped Hierarchical Federated Learning on Sub-5KB Models: A Feasibility Study of Privacy-Preserving ECG Monitoring for Ultra-Resource-Constrained Wearables</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-15T01:51:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hangyu Wu</p>
    <p><b>Summary:</b> Cardiovascular disease remains the leading cause of death worldwide, and early detection of arrhythmias through continuous ECG monitoring on wearable devices can prevent life-threatening events. Federated Learning (FL) enables privacy-preserving collaborative training by keeping raw ECG data on device, yet standard FL incurs prohibitive communication overhead and standard deep learning models cannot fit on ultra-low-power microcontrollers. We propose Family-Grouped Hierarchical Federated Learning (Family-FL), a three-tier architecture that uses the family as a natural privacy boundary for intra-family aggregation before global synchronization. We further design a hardware-constrained Tiny CNN-LSTM architecture with only 669 parameters, INT8-quantized to occupy merely 4.65KB Flash and 2.95KB RAM, meeting the constraints of STC32G12K128-class microcontrollers. Experiments on the MIT-BIH Arrhythmia Database (mean of 5 independent runs with different seeds) demonstrate that Family-FL reduces communication volume by 76.7% compared to FedAvg while maintaining comparable accuracy. Family-FL-Tiny achieves 91.9 +/- 1.2% accuracy with macro-F1 of 0.483 +/- 0.031, reducing total communication to 0.31% of FedAvg. The model achieves reliable ventricular arrhythmia detection (per-class F1 = 0.80), the most clinically critical abnormality for home-based preliminary screening. These results demonstrate the technical feasibility of privacy-preserving federated learning on ultra-resource-constrained microcontrollers through simulation-based evaluation. We honestly discuss limitations: no hardware deployment, single-dataset validation (MIT-BIH, 47 subjects), reduced rare-class sensitivity, and absence of formal differential privacy guarantees.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.15248v1">Probing Privacy Leaks in LLM-based Code Generation via Test Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-14T12:16:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yifei Ge, Zhenpeng Chen, Weisong Sun, Yuchen Chen, Chunrong Fang, Juan Zhai, Xiaofang Zhang, Xia Feng, Yang Liu, Zhenyu Chen</p>
    <p><b>Summary:</b> The widespread availability of large-scale code datasets has fueled the rapid development of large language models (LLMs) for code-related tasks. These datasets may include sensitive personally identifiable information (PII), which can lead to privacy leakage when LLMs memorize and reproduce it. However, existing privacy-leakage detection methods rely on ad-hoc prompt construction (manually or automatically designed). Therefore, they do not adequately approximate the real-world contexts in which PII appears in code corpora, making it difficult to extract realistic privacy leakage. In this paper, we propose a pipeline that simulates practical privacy-related code generation scenarios and adopts a test-driven strategy to elicit the memorized information from the generated test cases. We further introduce an automatically constructed privacy feature library that replaces manual prompt engineering by providing realistic templates and examples to guide test case generation. Large-scale experiments on 5 widely used LLMs show that our pipeline exposes more confirmed privacy leakage, achieving a 2.56 times increase in detected leakage compared to existing baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.15246v1">Privacy Evaluation of Generative Models for Trajectory Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-14T10:57:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stavros Bouras, Ioannis Kontopoulos, Chiara Pugliese, Francesco Lettich, Emanuele Carlini, Hanna Kavalionak, Chiara Renso, Konstantinos Tserpes</p>
    <p><b>Summary:</b> Trajectory data is fundamental to modern urban intelligence, yet its sensitivity raises significant privacy concerns. Generative models such as Generative Adversarial Networks, Variational Autoencoders, and Diffusion Models have been developed to generate realistic synthetic trajectory data by capturing underlying spatiotemporal distributions and mobility patterns. Although these models are often assumed to preserve privacy due to their generative nature, this assumption does not necessarily hold. In this work, we investigate the intersection of generative trajectory modeling and privacy evaluation. By identifying applicable empirical methods for assessing privacy preservation in trajectory generation tasks, we demonstrate a significant gap in the evaluation of privacy for generative trajectory models. Motivated by this gap, we implement Membership Inference Attacks against representative models, demonstrating the feasibility of using such empirical privacy evaluation methods and showing that their generative nature does not eliminate privacy risks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.14591v1">Privacy Auditing with Zero (0) Training Run</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-14T09:00:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tudor Cebere, Mathieu Even, Linus Bleistein, Aurélien Bellet</p>
    <p><b>Summary:</b> Privacy auditing provides empirical lower bounds on the differential privacy parameters of learning algorithms. Existing methods, however, require interventional access to the training pipeline, either to retrain multiple times or to randomize data inclusion. This is often infeasible for large deployed systems such as foundation models. We introduce Zero-Run privacy auditing, a post-hoc framework for auditing models using two fixed datasets: examples known to be training-set members and examples known to be non-members. In this observational regime, membership is no longer randomized; instead, member and non-member data often differ in distribution, so membership inference scores may reflect a distribution shift rather than algorithmic leakage. Drawing on ideas from causal inference, we formalize this confounding effect and propose two complementary corrections that yield valid privacy audits. Our first approach models the combined effect of distribution shift and algorithmic leakage as an adaptive composition, producing conservative global corrections. Our second approach conditions on observed data and adjusts pointwise membership guesses, yielding sharper instance-dependent bounds. Experiments on synthetic data and large-scale models show that Zero-Run auditing enables practical privacy evaluation when retraining or controlled data insertion is infeasible.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.14289v1">MetaMoE: Diversity-Aware Proxy Selection for Privacy-Preserving Mixture-of-Experts Unification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-14T02:48:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Weisen Jiang, Shuhao Chen, Sinno Jialin Pan</p>
    <p><b>Summary:</b> Mixture-of-Experts (MoE) models scale capacity by combining specialized experts, but most existing approaches assume centralized access to training data. In practice, data are distributed across clients and cannot be shared due to privacy constraints, making unified MoE training challenging. We propose MetaMoE, a privacy-preserving framework that unifies independently trained, domain-specialized experts into a single MoE using public proxy data as surrogates for inaccessible private data. Central to MetaMoE is diversity-aware proxy selection, which selects client-domain-relevant and diverse samples from public data to effectively approximate private data distributions and supervise router learning. These proxies are further used to align expert training, improving expert coordination at unification time, while a context-aware router enhances expert selection across heterogeneous inputs. Experiments on computer vision and natural language processing benchmarks demonstrate that MetaMoE consistently outperforms recent privacy-preserving MoE unification methods. Code is available at https://github.com/ws-jiang/MetaMoE.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.14123v1">Keyed Nonlinear Transform: Lightweight Privacy-Enhancing Feature Sharing for Medical Image Analysis</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-05-13T21:17:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haebom Lee, Gyeongjung Kim</p>
    <p><b>Summary:</b> Feature sharing via split inference offers a lightweight alternative to federated learning for resource-constrained hospitals, but transmitted features still leak patient identity information and lack practical mechanisms for controlled feature sharing. We propose Keyed Nonlinear Transform (KNT), a drop-in feature transformation that applies key-conditioned obfuscation to intermediate representations. KNT reduces re-identification AUC from 0.635 to 0.586, corresponding to a 36% reduction in above-chance identity signal, while introducing only 0.15 ms CPU overhead, without backbone retraining, and preserving classification performance within 1.0 pp. Our analysis shows that KNT's nonlinear transform prevents closed-form inversion and shifts recovery to iterative gradient-based optimization under full key compromise, substantially increasing inversion difficulty. The same transform generalizes to dense prediction tasks, incurring only a 4.4 pp Dice reduction on skin-lesion segmentation without retraining. These results position KNT as a practical and efficient privacy layer for split inference deployments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.14119v1">Privacy Preserving Multi Agent Path Finding</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2026-05-13T21:08:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rotem Lev Lehman, Roni Stern, Guy Shani</p>
    <p><b>Summary:</b> In the multi-agent path finding (MAPF) problem, a group of agents search in a graph for a path for each agent where no two paths collide. While in all applications of MAPF the agents must not collide with each other, in some of them the agents may not wish to share their paths due to privacy constraints. In this work, we formulate two types of privacy constraints for MAPF and propose algorithms that preserve them. The first type of privacy we consider is planning-level privacy, which means that during planning, the agents cannot identify exactly the planned location of the other agents. We propose a general framework for obtaining planning-level privacy, which works by adding mock agents to the planning process. The second type of privacy we consider is execution-level privacy, which is relevant when agents have limited sensing capabilities. Execution-level privacy is preserved if none of the agents is allowed to sense the location of the other agents during execution. We show how to adapt two popular MAPF algorithms, namely PIBT and LaCAM, such that they preserve execution-level privacy. Lastly, we propose a post-processing technique that allows the agents to reduce the sum of costs of the returned solution without losing any privacy. We also implemented our algorithms and evaluated them empirically, showing that the proposed post-processing technique indeed improved cost significantly.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.14113v2">ProtoMedAgent: Multimodal Clinical Interpretability via Privacy-Aware Agentic Workflows</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2026-05-13T20:57:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alvaro Lopez Pellicer, Plamen Angelov, Marwan Bukhari, Yi Li, Eduardo Soares, Jemma Kerns</p>
    <p><b>Summary:</b> While interpretable prototype networks offer compelling case-based reasoning for clinical diagnostics, their raw continuous outputs lack the semantic structure required for medical documentation. Bridging this gap via standard Retrieval-Augmented Generation (RAG) routinely triggers ``retrieval sycophancy,'' where Large Language Models (LLMs) hallucinate post-hoc rationalizations to align with visual predictions. We introduce ProtoMedAgent, a framework that formalizes multimodal clinical reporting as an iterative, zero-gradient test-time optimization problem over a strict neuro-symbolic bottleneck. Operating on a frozen prototype backbone, we distill latent visual and tabular features into a discrete semantic memory. Online generation is strictly constrained by exact set-theoretic differentials and a reflective Scribe-Critic loop, mathematically precluding unsupported narrative claims. To safely bound data disclosure, we introduce a semantic privacy gate governed by $k$-anonymity and $\ell$-diversity. Evaluated on a 4,160-patient clinical cohort, ProtoMedAgent achieves 91.2% Comparison Set Faithfulness where it fundamentally outperforms standard RAG (46.2%). ProtoMedAgent additionally leverages a binding $\ell$-diversity phase transition to systematically reduce artifact-level membership inference risks by an absolute 9.8%.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.13503v1">Limits of Personalizing Differential Privacy Budgets</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-13T13:24:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Edwige Cyffers, Juba Ziani</p>
    <p><b>Summary:</b> A key technical difficulty in differential privacy is selecting a privacy budget that satisfies privacy requirements while maximizing utility. A natural and well-studied workaround is to use personalized privacy budgets, which may differ across agents. In this paper, we show that personalized budgets come with major limitations and that for mean estimation, the dominant factor is not full personalization, but rather choosing the right effective privacy budget. This can be achieved through a simple thresholding operator that we describe. Compared with this thresholding baseline, the gains obtained by fully personalized mechanisms are limited. In particular, we precisely quantify the constant-factor improvement in settings with mixed private and public datasets and in private datasets with two levels of privacy requirements. We also establish upper bounds and identify regimes of maximal gain for arbitrary privacy requirements.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.13418v1">DP-KFC: Data-Free Preconditioning for Privacy-Preserving Deep Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-13T12:14:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marc Molina Van den Bosch, Riccardo Taiello, Albert Sund Aillet, Andrea Protani, Miguel Angel Gonzalez Ballester, Luigi Serio</p>
    <p><b>Summary:</b> Differentially private optimization suffers from a fundamental geometric mismatch: deep networks have highly anisotropic loss landscapes, yet DP-SGD injects isotropic noise. Second-order preconditioning can resolve this, but estimating curvature typically requires private data (consuming privacy budget) or public data (introducing distribution shift). We show that the Fisher Information Matrix decouples into architectural sensitivity, recoverable via synthetic noise, and input correlations, approximable from modality-specific frequency statistics. We propose DP-KFC, which constructs KFAC preconditioners by probing networks with structured synthetic noise, requiring neither private nor public data. Empirically, DP-KFC consistently outperforms DP-SGD and adaptive baselines across diverse modalities in strong privacy regimes ($\varepsilon \leq 3$). DP-KFC matches private-data preconditioners while public-data variants degrade by up to $4.8\%$, showing that curvature can be estimated without consuming privacy budget or introducing distribution shift. This enables privacy-preserving learning in specialized domains (e.g., medical applications) where regulatory constraints make data scarce.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.13265v1">LightSplit: Practical Privacy-Preserving Split Learning via Orthogonal Projections</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-13T09:45:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mert Cihangiroglu, Alessandro Pegoraro, Phillip Rieger, Antonino Nocera, Ahmad-Reza Sadeghi</p>
    <p><b>Summary:</b> Split learning (SL) enables collaborative training by partitioning a neural network across clients and a central server, but the cut-layer interface introduces a key challenge: high-dimensional activations incur substantial communication overhead while exposing representations vulnerable to reconstruction attacks. Existing approaches typically address efficiency or privacy in isolation, relying on additional mechanisms such as sparsification, quantization, or noise injection. We propose LightSplit, which limits information exposure and reduces communication overhead by applying a lightweight fixed orthogonal random projection at the cut layer. Based on Shannon's information theory, this projection acts as an information bottleneck that restricts instance-specific information and suppresses exploitable per-sample signals. By transmitting low-dimensional projections instead of raw activations, the server operates on lifted representations without requiring architectural modifications, ensuring compatibility with existing SL architectures. By avoiding additional trainable components on the client, the method remains lightweight and suitable for edge devices while preserving end-to-end differentiability via exact gradient propagation. As the projection is non-invertible, part of the original representation is irreversibly discarded at the client, LightSplit reduces the information available for reconstruction and limits information exposure. We extensively evaluate LightSplit on state-of-the-art benchmarks in both IID and non-IID settings across varying projection dimensions and client scales. Our results show that the method retains more than 95% of the baseline accuracy at up to 32x reduction in transmitted dimensionality while maintaining stable training dynamics.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.12147v1">PrivacySIM: Evaluating LLM Simulation of User Privacy Behavior</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-12T14:05:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> James Flemings, Murali Annavaram</p>
    <p><b>Summary:</b> Large language models (LLMs) are increasingly used to simulate human behavior, but their ability to simulate $individual$ privacy decisions is not well understood. In this paper, we address the problem of evaluating whether a core set of user persona attributes can drive LLMs to simulate individual-level privacy behavior. We introduce PrivacySIM, an evaluation suite that benchmarks LLM simulation of user privacy behavior against the ground-truth responses of 1,000 users. These users are drawn from five published user studies on privacy spanning LLM healthcare consultations, conversational agents, and chatbots. Drawing on these user studies, we hypothesize three persona facets as plausible predictors of privacy decision-making: demographics, previous experiences, and stated privacy attitudes. We condition nine frontier LLMs on subsets of these three facets and measure how often each model's response to a data-sharing scenario matches the user's actual response. Our findings show that (1) privacy persona conditioning consistently improves simulation quality over no-persona conditioning, but even the strongest model (40.4\% accuracy) remains far from faithfully simulating individual privacy decisions. (2) A user's stated privacy attitudes alone may not be the best predictor because they often diverge from the user's actual privacy behavior. (3) Users with high AI/chatbot experience but low stated privacy attitudes are the most challenging to simulate. PrivacySIM is a first step toward understanding and improving the capabilities of LLMs to simulate user privacy decisions. We release PrivacySIM to enable further evaluation of LLM privacy simulation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.12566v1">On Privacy-Preserving Image Transmission in Low-Altitude Networks: A Swin Transformer-Based Framework with Federated Learning</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-12T09:18:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kexin Zhang, Lixin Li, Yuna Yan, Xin Zhang, Wensheng Lin, Rui Li, Dongwei Zhao, Zhu Han</p>
    <p><b>Summary:</b> The rapid development of low-altitude economy has driven the proliferation of Unmanned Aerial Vehicle (UAV) applications, including logistics, inspection, and emergency response. However, transmitting high-volume image data from UAVs to ground stations faces significant challenges due to limited bandwidth and stringent privacy requirements. To address these issues, a Semantic Communication (SC) framework based on Federated Learning (FL) is proposed for efficient and privacy-preserving image transmission. A Swin Transformer-based Semantic Communication (STSC) architecture is designed to extract multi-scale semantic features under constrained bandwidth conditions. Dedicated communication and computing nodes are deployed on UAVs to enhance real-time coverage and flexibility. Meanwhile, a FL mechanism enables global model training across distributed devices without sharing raw data, thus preserving user privacy. Simulation experiments conducted on the CIFAR-10 dataset demonstrate that the proposed STSC framework achieves at least 5.7 dB improvement in Peak Signal-to-Noise Ratio (PSNR) compared to DeepJSCC baselines, while also showing superior convergence and generalization performance. The framework effectively integrates UAV-assisted deployment with SC and privacy protection, offering a practical solution for bandwidth-constrained image transmission in low-altitude networks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.11386v1">Revisiting Privacy Preservation in Brain-Computer Interfaces: Conceptual Boundaries, Risk Pathways, and a Protection-Strength Grading Framework</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-12T01:17:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lei Sun, Xiuqing Mao, Shuai Zhang, Qingyu Zeng, Min Zhao, Jiyuan Li, Wenle Dong</p>
    <p><b>Summary:</b> Brain-computer interfaces (BCIs) are moving rapidly from laboratory research into clinical, edge, and real-world settings. Under ISO/IEC 8663:2025, a BCI is a direct communication link between central nervous system activity and external software or hardware systems. This link expands privacy risk beyond raw neural-signal leakage: neural data, derived representations, model assets, and decoded outputs can be re-associated with individuals across collection, transmission, storage, training, inference, and feedback, or used to infer information beyond what a task requires. Starting from the general BCI paradigm, this review deffnes privacy-protection boundaries, protection objects, and the relationship between user data privacy and model privacy within a shared risk pathway. It then proposes a three-dimensional framework - protection object, lifecycle stage, and dominant protection-strength level - to classify existing work into four levels of protection strength. Finally, mental privacy and neuroethical risks are treated as open issues, emphasizing that BCI privacy protection should not only obscure data but also disentangle task-irrelevant sensitive information while preserving downstream utility. Keywords: Brain-computer interface, Neural data privacy, User data privacy, Model privacy, Disentanglement of task-irrelevant sensitive information, Protection-strength grading, Neuroethical risks</p>
  </details>
</div>



<h2>2026-06</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.02563v1">IntraShuffler: A Privacy Preserving Framework for Heterogeneous DP Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-06-01T17:54:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Farhin Farhad Riya, Olivera Kotevska, Jinyuan Stella Sun</p>
    <p><b>Summary:</b> Heterogeneous Differential Privacy (HDP) in Federated Learning (FL) allows clients to select individual privacy budgets ($\varepsilon_i$) according to institutional policies and data sensitivity. In practice, many HDP-FL systems employ $\varepsilon$-aware server aggregation to improve model utility by re-weighting client updates according to their declared privacy budgets. However, gradient updates in FL retain structural patterns induced by non-independent and identically-distributed (non-IID) data, and these additional signals exposed by $\varepsilon$-aware aggregation create new opportunities for inference by an honest-but-curious server. In this work, we first show that a server equipped with gradient denoising and surrogate modeling can mount a \emph{Privacy Inference Attack} that infers distributional attributes of clients and links updates from the same client across training rounds, measured via surrogate inference accuracy and linkage success, under realistic knowledge constraints.
  The Shuffle-Model has been widely studied as a defense against such inference risks by anonymizing update sources, but it is fundamentally incompatible with HDP-FL $\varepsilon$-aware aggregation. To address this challenge, we propose \textbf{IntraShuffler}, a middleware defense framework designed for HDP-FL systems. IntraShuffler introduces a privacy-aware shuffling mechanism that groups clients into privacy-compatible buckets and performs parameter-level shuffling within each bucket to disrupt persistent gradient structure while preserving $\varepsilon$-aware aggregation. Experiments across four different datasets show that IntraShuffler reduces gradient recoverability by over 60% and decreases surrogate inference accuracy from 0.78 to 0.33 while maintaining comparable model utility across multiple FL aggregation rules.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.02483v1">Ghost Tool Calls: Issue-Time Privacy for Speculative Agent Tools</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-06-01T16:53:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bardia Mohammadi, Lars Klein, Akhil Arora, Laurent Bindschaedler</p>
    <p><b>Summary:</b> Tool-augmented language agents speculatively issue likely future tool calls to hide latency, but those calls leak inferred user intent to external services before the agent commits to the branch. Every external observer that received the call retains the disclosure after the agent abandons the branch. Timing is the issue, not authorization: no commit-time cleanup, read-only restriction, or access-control allow-list unsends what an observer already holds. We call these invocations ghost tool calls and propose Speculative Tool Privacy Contracts, a runtime abstraction that treats observation before commitment as a first-class effect, distinct from state mutation. We implement the contracts in a prototype runtime and evaluate twelve policies across three corpora. Speculative dispatch increases what an observer can infer about user intent; post-hoc filters, read-only restrictions, and access-control allow-lists leave that inference intact; only issue-time policies that change or suppress the speculative call's argument or destination projection before dispatch reduce it.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.02348v1">Privacy-preserving Information Sharing in Oligopoly Competitions</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB">
  <p><b>Published on:</b> 2026-06-01T14:58:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuxin Liu, M. Amin Rahimian</p>
    <p><b>Summary:</b> Information sharing among competing suppliers can improve decision-making under uncertainty, yet strategic concerns regarding rival exploitation often deter voluntary disclosure. We study information-sharing mechanisms in a Cournot oligopoly with uncertain demand, where a platform aggregates suppliers' signals through privacy-preserving channels and may also possess an exogenous external signal. The central challenge is to balance strategic safety with informational utility: privacy noise reduces the exposure of individual signals, but also lowers the value of the shared information pool. We first characterize a baseline setting in which access to aggregated information is contingent on participation. In a two-firm market without an external signal, firms refuse to share regardless of the privacy level. In an \(n\)-firm market, sharing may arise even without privacy safeguards because non-participating firms lose access to the aggregated signal. Building on this baseline, we show that privacy protection alone is insufficient to incentivize disclosure; it must be combined with a sufficiently informative external signal. We further show that firms with more accurate private signals require stronger privacy protection. Overall, our results characterize the sharing-feasible region and highlight the complementarity between privacy design and the external information environment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.01908v1">Private and Stable Test-Time Adaptation with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-06-01T08:45:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zefeng Li, Qiaoyue Tang, Mathias Lecuyer, Evan Shelhamer</p>
    <p><b>Summary:</b> Test-time adaptation (TTA) can reduce error on new and different data by updating the model on these inputs during inference. However, these updates raise the issue of privacy w.r.t. the testing data, because the model parameters now depend on all past inputs. To control this privacy risk, we cast multiple popular TTA methods (Tent, EATA, SAR, DeYO, and COME) into differential privacy (DP) forms that apply per-sample gradient clipping and Gaussian noise for all updates. On ImageNet-C, our DP-TTA methods provide adequate privacy at small cost to accuracy, and in the low-privacy regime the clipping mechanism of DP can even improve the accuracy and stability of adaptation in the continual setting. These improvements to privacy and accuracy come at only modest computational overhead. These first results on private TTA raise awareness of the issue, inform the development of more private test-time updates, and identify per-sample clipping as an effective technique for improving the accuracy and stability of adaptation.</p>
  </details>
</div>

