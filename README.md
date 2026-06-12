
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
  <h3><a href="http://arxiv.org/abs/2605.30123v2">Privacy-Enhanced Zero-Order Federated Learning via xMK-CKKS over Wireless Channels</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-05-28T15:56:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anthony Ayli, Khalil Harris, Jihad Fahs, Mohamad Assaad</p>
    <p><b>Summary:</b> Homomorphic encryption (HE) enables privacy-preserving aggregation in federated learning (FL) by allowing the server to operate on encrypted data without decryption. Existing HE-over-the-air (OTA) methods mainly rely on single-key HE schemes and require channel estimation or pre-equalization to compensate for wireless fading. However, single-key HE remains vulnerable to honest-but-curious (HBC) clients holding the shared secret key, while multi-key HE provides stronger client-level security by assigning each device its own secret key. We propose a four-phase protocol that enables the aggregation of xMK-CKKS over a shared wireless channel without channel estimation. The protocol retransmits partial public keys and ciphertexts through the same channel realization, so that the dominant large-modulus encryption terms cancel algebraically during decryption. We integrate this protocol with zero-order FL over slowly varying LoS-dominant channels, where each device transmits a single encrypted scalar per round and the communication/encryption overhead is independent of the model dimension. We show that the residual noise induced by encryption and wireless aggregation preserves the standard convergence rate \(O(1/\sqrt{K})\) up to a negligible noise floor, where $K$ is the number of communication rounds. The protocol assumes an non-trusted server and is secure against HBC clients, preventing any client from recovering the local updates of other participants. Numerical results on MNIST validate the theoretical analysis.</p>
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
  <h3><a href="http://arxiv.org/abs/2606.07585v1">Multimodal Group Emotion Recognition In-the-Wild Towards a Privacy-Safe Non-Individual Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-05-27T16:36:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anderson Augusma</p>
    <p><b>Summary:</b> This thesis addresses group emotion recognition (GER) in-the-wild with a focus on privacy preservation. Unlike traditional emotion recognition methods that rely on individual-level cues such as face, gaze, or voice analysis, this work uses collective audio-video signals to infer emotions at the group level, reducing risks of individual monitoring and surveillance. Two complementary frameworks are proposed. The first is a cross-attention multimodal architecture for audio-video fusion, combined with Frames Attention Pooling (FAP) for temporal aggregation. It is supported by synthetic data augmentation and validated through ablation studies, demonstrating robustness in real-world GER conditions. The second framework, Variational Encoder Multi-Decoder (VE-MD), learns a shared latent space for emotion classification and structural representation prediction, including body and face cues. Two decoding strategies, DETR-based and heatmap-based, are explored to analyze the role of structural representations in group and individual settings. The thesis makes three main contributions: it clarifies the role of multimodality and structural cues in group-level affective computing; introduces two architectures for privacy-preserving multimodal GER; and shows that competitive performance can be achieved without using individual features as input data.</p>
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
  <h3><a href="http://arxiv.org/abs/2605.27292v2">Detectability in Diversity: Improved Canary Crafting for Privacy Auditing in One Run</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2026-05-26T17:06:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mathieu Dagréou, Aurélien Bellet</p>
    <p><b>Summary:</b> Privacy auditing aims to empirically assess privacy leakage in machine learning models using membership inference attacks (MIAs), and to derive lower bounds on differential privacy (DP) parameters. Recent one-run auditing methods address the high cost of standard approaches by relying on a single training run with multiple "canary" points whose inclusion or exclusion must be detected by the auditor. In this work, we study the problem of efficiently crafting canaries for one-run privacy auditing. Motivated by recent theoretical insights suggesting that interference between canaries contributes to weaker leakage estimates compared to multi-run methods, we propose to optimize canaries to be both highly detectable and minimally interfering. Our approach combines a greedy initialization based on influence functions with a bilevel optimization procedure that maximizes distinguishability while promoting diversity in embedding space, enabling the use of computationally efficient bilevel algorithms. Experiments show that our method achieves stronger privacy leakage estimates at a lower computational cost than existing canary crafting approaches.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2605.27278v2">Optimal quantum locally differentially private mechanisms in the high-privacy regime</a></h3>
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
  <h3><a href="http://arxiv.org/abs/2605.25791v2">Efficient and Privacy-Preserving Distribution Statistics Analytics on Mobile Spatial Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-05-25T12:37:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xuhao Ren, Mingyang Zhao, Ruichen Zhang, Liehuang Zhu, Bin Xiao</p>
    <p><b>Summary:</b> With the rapid development of mobile computing technology, massive amounts of spatial data are continuously generated from various mobile terminals and sensing devices, such as smartphones, connected vehicles, and drones. Performing efficient distributed statistical analysis on this data is crucial for real-time mobile computing applications. However, the constrained and dynamic nature of mobile environments exacerbates the privacy challenge: centralizing sensitive data for analysis risks severe privacy leaks, while existing privacy-preserving techniques often introduce excessive overhead or inaccuracies. In this paper, we design, implement, and evaluate the first system that supports efficient and privacy-preserving distribution statistics analysis for mobile spatial data. First, we propose eSpat-B, which leverages two non-colluding servers and a newly designed improved distributed point functions (DPF) with octree partitioning. Furthermore, considering the frequent updates of spatial data, we propose another more efficient scheme, eSpat+. The core idea of this scheme is to utilize a K-Dimensional tree for spatial partitioning, combine it with incremental DPF for performing statistics analysis, and design an efficient update algorithm. Security analysis demonstrates that our schemes effectively protect data privacy throughout the statistical process. Extensive experiments on real-world trajectory datasets demonstrate that the proposed schemes significantly outperform existing approaches, reducing computation overhead by up to 1.2x and communication overhead by up to 20x while maintaining 100% statistical accuracy.</p>
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



<h2>2026-06</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.12845v1">A Privacy-Preserving Framework Using Remote Data Science for Inter-Institutional Student Retention Prediction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-06-11T03:18:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> John Fields, K M Sajjadul Islam, Ruchitha Thota, Victor Chen, Praveen Madiraju</p>
    <p><b>Summary:</b> This study explores privacy-preserving machine learning (PPML) techniques using the PySyft platform to enable collaborative prediction of student retention between institutions. We developed a remote data science (RDS) framework with a semi-air-gapped architecture consisting of high-side and low-side servers, allowing researchers from three universities to build predictive models on sensitive student data without direct data access. Using historical data from a small private university (N=720), we evaluated three synthetic data generation approaches and validated the framework through inter-institutional collaboration. The results demonstrate consistent classification performance across institutions (Macro F1: 0.690--0.695) while maintaining strict Family Educational Rights and Privacy Act (FERPA) compliance. We also propose Data-Type-Aware Templates, a novel synthetic data method that prioritizes privacy over distributional fidelity. Our findings confirm that RDS-based PPML is technically feasible for educational settings and offers a practical alternative to federated learning for small-scale inter-institutional collaborations. The code is available at https://github.com/jtfields/NAIRR240195-Privacy-Preserving-Machine-Learning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.12733v1">Let's Ask Gauss: Improved One-Run Privacy Auditing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-06-10T22:44:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Adya Agrawal, Yu Wei, Jaspal Singh, Malik Magdon-Ismail, Vassilis Zikas</p>
    <p><b>Summary:</b> Privacy auditing provides an important safeguard by estimating the actual information leaked by a model, thus ensuring that theoretical privacy guarantees hold in practice. We study empirical privacy auditing for differentially private (DP) machine learning, focusing on efficient one-run methods for mechanisms such as DP-SGD. Prior one-run approaches threshold training examples or "canaries" into binary membership guesses, which discards useful information. We show that, in the white-box DP-SGD setting, canary-aligned signals naturally form a sequence of random variables whose normalized sum is asymptotically Gaussian. Leveraging this distributional perspective, we develop a DP-auditing framework that leads to tighter privacy lower bounds from a single training run.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.12679v1">Fed-FBD: Federated Functional Block Diversification for Isolation, Privacy, and Surgical Unlearning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2026-06-10T21:06:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Weijie Chen, Alan B. McMillan</p>
    <p><b>Summary:</b> Federated learning (FL) enables collaborative model training without sharing raw patient data, but standard approaches such as FedAvg treat each client as a black box and provide no mechanism for isolating an adversarial contributor, auditing per-client influence, or honoring a departed participant's right to be forgotten. We present Fed-FBD (Federated Functional Block Diversification), a modular federated architecture that decomposes a ResNet backbone into six functional blocks (the stem, four residual groups, and the classification head) and maintains a warehouse of N color variants, each assembled from independently tracked and contributor-stamped blocks. Fed-FBD provides three capabilities absent in FedAvg: (i) architecturally guaranteed block-level isolation, so that an adversarial or mislabelled client cannot contaminate the clean colous; (ii) privacy-by-design, where membership inference advantage is already indistinguishable from chance before any privacy mechanism is applied; and (iii) surgical machine unlearning of a departed participant's contribution at sub-second cost and without retraining. Experiments on six MedMNIST-2D datasets, PathMNIST at 224x224, and CIFAR-10 show that Fed-FBD trades a modest 0.3%-3.1% IID accuracy gap on the adequately sized datasets for these guarantees, remains within 0.8%-4.0% of FedAvg at Dirichlet alpha=1.0 on three of four datasets, and confines all six adversarial attacks we study to the poisoned client's own blocks with at most +/-0.01 AUC drift on the clean colors.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.12666v1">CAPED: Context-Aware Privacy Exposure Defense for Mobile GUI Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-10T20:48:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Siyu Shen, Fenghao Xu, Wenrui Diao, Kehuan Zhang</p>
    <p><b>Summary:</b> Screenshot-based mobile GUI agents can operate ordinary smartphone apps through the same visual interface as a human user, but this capability also turns every screen observation into a privacy boundary. During normal task execution, screenshots may expose contacts, messages, photos, files, recommendations, health cues, and other sensitive context that is unrelated to the user's request. We call this problem incidental visual privacy exposure. It is difficult to address with existing defenses: text anonymization misses many visual and inferential cues, while generic privacy masking can remove the evidence and controls that a GUI agent needs to complete the task.
  This paper presents CAPED, a context-aware pre-upload exposure control layer for mobile GUI agents. CAPED is designed as a phone-side protection layer: before screenshots are released to a remote multimodal agent, it extracts task requirements, uses screen context as a privacy prior, parses visible UI elements, and selectively exposes only content needed for the current task while masking incidental private content. We evaluate CAPED on AndroidWorld for broad task utility and with a controlled 28-task seeded privacy evaluation used as a measurement instrument for trajectory-level incidental leakage. In this seeded evaluation, Full CAPED reduces success-conditioned weighted seeded leakage from 0.766 under raw screenshots to 0.268 while preserving high task utility. A broader AndroidWorld run shows a remaining prototype-level utility cost, but the results support the central claim that screenshot upload should be treated as an explicit device--cloud boundary decision, governed by task-driven selective exposure rather than all-or-nothing screen sharing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.12341v1">OCELOT: Inference-Leakage Budgets for Privacy-Preserving LLM Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-10T17:13:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jin Xie, Songze Li</p>
    <p><b>Summary:</b> Large language model (LLM) agents increasingly act on a user's behalf -- reading personal files, calling tools, transacting with external services -- possibly leaking personally identifiable information (PII) across trust boundaries at every step. Privacy here is a property not of a single output but of an entire trajectory, and three properties make it hard: leakage is cumulative, as individually innocuous releases accumulate across honest-but-curious or colluding sinks into inferences about a protected secret; bidirectional, as a malicious observation can inject instructions that turn the agent's own reasoning model against the user; and task-dependent, as the same field is necessary for one recipient yet gratuitous for another. Per-release contextual-integrity filters, information-flow controls, and posterior-leakage monitors each address part of this but none controls cumulative, inference-based leakage at runtime. We recast agent privacy as \emph{posterior-risk control} and present OCELOT, a runtime mediator that budgets how much an adversary's belief about a secret may improve across a trajectory, rather than filtering outputs. Its mechanism, \emph{Witness-Verified Declassification}, separates judgment from trust: an untrusted, locally fine-tuned defender model inspects each candidate release and emits structured evidence -- labeled atoms and proposed declassification operators -- which a deterministic verifier audits, charging a certified min-entropy cost for the chosen variant and authorizing the least-disclosing useful release under a sink-trust-weighted budget recorded on a tamper-evident ledger. Across diverse agent benchmarks and recent defenses, OCELOT attains significantly lower leakage at higher task utility, resists adaptive injection, jailbreak, cumulative inference, and sink collusion, and adds only modest overhead.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.11556v1">Privacy-Preserving Federated Autoencoder for ECG Anomaly Detection on Edge Devices</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-06-10T01:33:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kaan Arda Akyol, Jakub Kacper Szeląg, Aydin Abadi, Maha Alghamdi, Ghadah Albalawi, Ghouse Ibrahim Kaleelullah, Hilal Tutus, Sarah Al Subaiei, Shardul Kapse, Syed Mohammed Raheeb, Mujeeb Ahmed, Rehmat Ullah</p>
    <p><b>Summary:</b> Continuous electrocardiography (ECG) monitoring could surface rhythm abnormalities before they escalate into cardiovascular events. However, a deployable system must satisfy three requirements simultaneously: legal-grade privacy (GDPR, HIPAA), real-time inference on constrained edge hardware, and detection quality under non-IID cross-hospital data.
  We design and evaluate an end-to-end federated system addressing all three for unsupervised 12-lead ECG anomaly detection on PTB-XL dataset, combining three autoencoder families (VanillaAE, ConvAE, VAE), Flower-based federated averaging (FedAvg) across ten simulated hospitals, client-side differentially private SGD (DP-SGD) with a Rényi-DP accountant, and 8-bit integer (INT8) post-training quantization with Raspberry Pi 4 benchmarking. Our main contributions are: an empirical characterization of how these mechanisms compose, practical DP-specific recommendations, and technical and security insights for a clinically sensitive setting. Federated learning matches or exceeds the centralized baseline across all architectures (ConvAE federated area under the ROC curve, AUROC, $0.782$), and an $\varepsilon$ sweep identifies $\varepsilon=4$ as the recommended clinical operating point. INT8 quantization roughly halves model size and cuts Pi 4 latency by up to $44%$ with $<0.12%$ AUROC loss. Crucially, DP and quantization penalties are empirically independent, so practitioners need not trade a strong privacy guarantee for a compact edge footprint. To our knowledge, this is the first system combining federated learning, formal $(\varepsilon,δ)$-DP, unsupervised reconstruction-based detection, and quantized AArch64 deployment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.11539v1">PriME-Deal: Privacy-Preserving Bilateral Data Trading with Efficient Matchmaking and Auditable Fair Exchange on Blockchain</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-10T00:49:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jie Zhang, Xiaohong Li, Shanshan Xu, Hanwei Wu, Ruitao Feng, Guangdong Bai</p>
    <p><b>Summary:</b> Bilateral attribute-based access control for data trading must hide policies, provide cryptographic fairness, and avoid trusted third parties. Existing solutions either leak policy information, incur super-linear costs, or rely on trusted dispute resolution. We present PriME-Deal, a non-interactive protocol that simultaneously achieves policy-hiding bilateral matching, efficient threshold access control, and auditable fair exchange on public blockchains. The seller embeds a secret token under the buyer policy into an oblivious key-value store with pseudorandom masking; the buyer reconstructs the token locally via tag-based probing, eliminating combinatorial enumeration, and proves correctness in zero-knowledge. Fair exchange is enforced through a collateralized on-chain reveal with a cryptographic audit that penalizes misbehaviour without trusted parties.
  We prove security in the Universal Composability framework under standard assumptions. Compared with the state-of-the-art threshold fuzzy IB-ME scheme, the seller's publishing time is reduced by two orders of magnitude (e.g., 8.76s vs. 690s for a policy of 500 attributes). For a typical configuration of (200,20,5), the buyer completes token reconstruction and proof generation in 8.9s, with the zero-knowledge proof taking under 0.6s and remaining constant across all parameter scales. The on-chain cost is approximately 28.6M gas, well within Ethereum's block limit. PriME-Deal thus delivers the first practical privacy-preserving data trading protocol that combines linear seller overhead, bilateral policy hiding, and auditable fairness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.11272v1">Federated continual learning: A comprehensive survey on lifelong and privacy-preserving learning over distributed and non-stationary data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-09T08:35:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Masoume Gholizade, Fabrizio Ruffini, Pietro Ducange, Francesco Marcelloni</p>
    <p><b>Summary:</b> Federated Learning (FL) enables collaborative and privacy-preserving model training across distributed clients, but most existing FL systems implicitly assume data stationarity. In real-world settings-such as healthcare, industrial IoT (IIOT), cybersecurity, and smart cities-data streams are inherently non-stationary, leading classical FL methods to suffer from performance degradation, instability, and catastrophic forgetting.
  Continual Learning (CL) addresses learning under evolving data distributions but has been largely studied in centralized settings, overlooking key constraints of federated systems, including privacy, limited communication, and client heterogeneity. Federated Continual Learning (FCL) emerges at the intersection of FL and CL, aiming to support lifelong, adaptive, and privacy-aware learning over distributed and non-stationary data.
  This survey provides a comprehensive and systematic overview of FCL. We first present a formal definition of the FCL problem and clarify its distinctive characteristics. We then analyze the limitations of classical FL under non-stationary conditions, highlighting how CL principles support long-term adaptation. To organize the rapidly growing literature, we propose a multi-dimensional taxonomy of FCL approaches. Furthermore, we review representative application domains and data modalities, summarize commonly used evaluation metrics, and discuss experimental perspectives for assessing long-term performance and forgetting. Finally, we highlight key open challenges, including handling extreme heterogeneity under temporal drift, designing scalable and privacy-preserving memory mechanisms, and establishing standardized benchmarks. This survey aims to serve as a reference and a roadmap for advancing FCL toward robust and deployable real-world systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.10502v1">When VR Meets BCI: (Un)Observable Brainwave-aware Privacy Reconstruction in the Metaverse via Unrestricted Inbuilt Motion Sensors</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-09T07:28:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tao Ni, Zehua Sun, Qingchuan Zhao, Wei-Bin Lee, Cong Wang</p>
    <p><b>Summary:</b> Metaverse devices, such as virtual reality (VR), have seen substantial development and widespread applications in numerous areas. Although recent studies have revealed privacy leakages in VR, these vulnerabilities were limited in the scope of observable behaviors in virtual scenes (e.g., what a user is seeing). In this work, we uncover the feasibility of going beyond the scope of observable user behaviors to unobservable brain EEG-correlated representations (e.g., what a user is perceiving) by leveraging unrestricted motion sensors in VR headsets to reconstruct brain EEG signals, a seemingly neglected but promising vector. The insight is that the inbuilt motion sensors (e.g., accelerometers) in the VR headset can capture subtle vibrations induced by pupillary responses, which are highly correlated with users' visual stimuli and in-brain perceptions.
  Therefore, we design and implement BraVeSpy to systematically investigate and demonstrate the feasibility of this severe privacy leakage originating from brain EEG-correlated representations reconstructed from variations of inbuilt motion sensors. Our extensive evaluation results from different VR devices show that BraVeSpy, for the first time in the Metaverse, can reveal unobservable privacy, where we successfully unveiled perceptive images in the brain with 52.0%-67.2% accuracy. In particular, we also find that BraVeSpy outperforms the current approaches that are limited to coarse-grained inference of observable behaviors and achieves over 85.0% accuracy in inferring user activity-related sensitive information, such as fingerprinting websites, apps, and streaming videos, and over 96.0% accuracy in user de-anonymization, gaze movement tracking, and virtual keystroke inference.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.10481v1">Advancing the State-of-the-Art in Empirical Privacy Auditing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2026-06-09T06:50:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nicole Mitchell, Galen Andrew, Arun Ganesh, Brendan McMahan, Peter Kairouz</p>
    <p><b>Summary:</b> Parameter-efficient fine-tuning of large language models (LLMs) can exhibit problematic memorization of individual training examples. Empirical privacy auditing (EPA) quantifies this risk by measuring realistic data leakage on membership inference (MI) or reconstruction attacks. A key challenge in EPA is designing ``canary'' examples that are mixed with the privacy-sensitive training data. We propose generating synthetic canaries via high-temperature sampling ($T \geq 0.8$) from LLMs, using prompts tailored to the privacy-sensitive training data. These canaries act as high-influence outliers, ensuring high identifiability and hence strong audits. Further, since the canaries are themselves non-private, they are inspectable and can be inserted with repetition without jeopardizing the privacy of the real data. An important use of models fine-tuned on privacy-sensitive data is the generation of synthetic data. This also comes with privacy risk. We introduce a powerful synthetic data audit based on fine-tuning an auxiliary model on the synthetic data. Auditing the auxiliary model for the original canaries then provides a strong estimate of the privacy leakage through the synthetic data. Finally, leveraging our strong auditing methodologies, we perform a systematic investigation into the interacting effects of model capacity and canary entropy on memorization.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.10333v1">Privacy-Preserving Credit Risk Prediction with Alternative Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-09T02:27:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hongzhe Zhang, Jiarong Xu, Jing He, Xiao Fang</p>
    <p><b>Summary:</b> Credit risk prediction is a critical problem in the consumer credit industry. Traditionally, financial institutions construct credit risk prediction models using borrowers' demographic, financial, and credit history data, collectively referred to as traditional data. Recent studies have demonstrated that alternative data, such as borrowers' mobile phone communication data, enable lenders to acquire fuller and more accurate profiles of borrowers' creditworthiness, thereby improving credit risk prediction performance. Nevertheless, alternative data are held by external entities independent of financial institutions. Directly sharing alternative data with financial institutions infringe on consumer privacy, yet existing credit risk prediction studies largely overlook this issue. To address this gap, we define a new problem, namely privacy-preserving credit risk prediction with alternative data, which simultaneously considers three practical constraints: the privacy-preserving constraint that protects consumer privacy, the model-confidentiality constraint that learns and stores the model centrally at the financial institution, and the lossless constraint that maintains the performance of the learned model. To solve this problem, we develop PrivacyCredit, a novel privacy-preserving machine learning method. We then theoretically demonstrate the privacy-preserving, model-confidential, and lossless properties of PrivacyCredit. Through extensive experiments using a real-world credit dataset linked with alternative data, we demonstrate the predictive value of securely incorporating alternative data into credit risk prediction and show that PrivacyCredit achieves the same predictive performance as the model learned from the insecure plaintext combination of traditional and alternative data. We further evaluate its model-confidentiality property and computational efficiency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.10173v1">Local Is Not a Sufficient Privacy Boundary: Governing OS-Integrated On-Device AI</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-08T21:07:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jonghyun Chung, Sanket Badhe</p>
    <p><b>Summary:</b> As AI systems move into operating systems, privacy no longer turns only on whether a model runs locally. A local assistant may assemble email, calendar entries, files, screenshots, notifications, and app intents; retain embeddings or summaries; invoke tools; emit telemetry; or route difficult requests to cloud infrastructure. Local inference reduces some exposure, but it answers only one question: where computation occurs. It does not answer who may assemble context, what derived state persists, which actions are authorized, or how updates change the system's authority. We develop an OS-centered privacy framework for on-device AI that treats privacy as an institutional accountability problem rather than a deployment attribute. The framework specifies a threat model, a six-part privacy risk taxonomy, privacy-by-architecture controls, and a four-level audit rubric. We demonstrate the rubric through a documentation-bounded comparison of Apple Intelligence/Foundation Models, Android AICore/Gemini Nano, and Microsoft Recall. Meaningful privacy in on-device AI depends on constrained information flow, bounded authority, visible user control, and auditable governance across the operating-system lifecycle.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.10097v1">Secrets Best Not Shared: DNS Privacy Enhancements for the Constrained IoT</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-06-08T19:22:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Martine S. Lenders, Thomas C. Schmidt, Matthias Wählisch</p>
    <p><b>Summary:</b> Attackers often identify DNS traffic to disrupt or compromise Internet services. While prior work has focused on encrypting queries using DNS over TLS, HTTPS, or QUIC to counter such attacks, we consider IETF protocols designed for resource-constrained IoT devices and empirically analyze the potential of obfuscating DNS traffic in addition to encryption. We create a dataset of machine-to-machine-compatible data objects along with the corresponding DNS resolution processes, evaluating 296 deployment scenarios of resolving host names, including DNS over the Constrained Application Layer Protocol (CoAP) and an onion routing flavor of CoAP under varying link-layer conditions. We compare them to DNS over HTTPS. Using Random Forest and a header field analysis, we identify fields that leak most information. Our findings show that DNS over CoAP with equalized packet lengths, block-wise transfer, and header compression reduces the accuracy of identifying DNS frames to 86% and further to 77% with payload compression. Our approach outperforms DNS over HTTPS, where classifiers always identify DNS frames based on IP addresses. The dataset is publicly available.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.09590v1">Clinically Grounded Privacy Evaluation of Medical LMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-08T15:02:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sasha Ronaghi, Sana Tonekaboni, Lena Stempfle, Vivian Utti, Jordan Li Cahoon, Nathaniel Hendrix, Ayin Vala, Marzyeh Ghassemi, Emily Alsentzer</p>
    <p><b>Summary:</b> Medical language models (LMs) can memorize and reproduce protected health information, but privacy evaluations often focus on recovery of training text rather than disclosure under realistic threat models. We introduce a clinically grounded framework that evaluates leakage along a graded axis of adversarial access, ranging from publicly inferable demographics to leaked note fragments. At each tier, we measure verbatim memorization of patient-specific text and semantic leakage of sensitive diagnoses. Applying the framework to an LM pretrained on 378k clinical notes, we find that routine encounter metadata (i.e. name, date of birth, provider, practice, visit date) elicits high rates of verbatim memorization across a patient's timeline and sensitive-diagnosis recovery (AUROC 0.91 for abortion, 0.81 for HIV). At the same time, exact-match memorization can overstate disclosure: 36% of memorized tokens reflect templated documentation. Our work highlights the risks of training on longitudinal clinical data, providing a practical framework for contextual privacy evaluation of medical LMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.09582v1">On Choosing the $μ$ Parameter in Gaussian Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2026-06-08T14:56:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bogdan Kulynych, Antti Honkela</p>
    <p><b>Summary:</b> Recent work argues for using Gaussian differential privacy (GDP) to report the privacy guarantees in privacy-preserving machine learning. We provide principled mappings from pure-DP $\varepsilon$ to GDP $μ$ by matching the worst-case success of a strong-adversary membership inference attack in terms of three metrics: multiplicative advantage at fixed FPR, precision at fixed recall, and the standard privacy profile. We tabulate $μ$ values across a useful range of parameters and recommend $μ\approx \varepsilon/5$ as a conservative general-purpose conversion.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.09402v1">Fully Oblivious Differential Privacy for Frequency Estimation in the Augmented Shuffle Model with Trusted Processors</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-08T12:21:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Takao Murakami, Yuichi Sei, Reo Eriguchi</p>
    <p><b>Summary:</b> In the shuffle model of DP (Differential Privacy), a shuffler randomly permutes users' data to achieve high accuracy and privacy. Recent studies show that most existing shuffle protocols are vulnerable to collusion attacks by the data collector and users. They address this issue by introducing the augmented shuffle model that incorporates random sampling and dummy data addition into the shuffler. However, it remains open how to ensure the shuffler follows the protocol and does not collude with the data collector in this model.
  We address this trust issue by thoroughly exploring the augmented shuffle model with TEEs (Trusted Execution Environments). We first introduce a new privacy notion, FODP (Fully Oblivious DP), which strengthens DP to prevent various TEE side-channel attacks based on external/internal memory access patterns and control flows. We propose a general framework for FODP algorithms based on memory-size obfuscation and three concrete algorithms within it. We also improve the efficiency of our algorithms by using the count-min sketch and optimizing the number of hashes. We evaluate our algorithms on Intel SGX and demonstrate their effectiveness through comparisons with nine baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.09401v1">Benchmarking Empirical Privacy Protection for Adaptations of Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-08T12:21:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bartłomiej Marek, Lorenzo Rossi, Vincent Hanke, Xun Wang, Michael Backes, Franziska Boenisch, Adam Dziedzic</p>
    <p><b>Summary:</b> Recent work has applied differential privacy (DP) to adapt large language models (LLMs) for sensitive applications, offering theoretical guarantees. However, its practical effectiveness remains unclear, partly due to LLM pretraining, where overlaps and interdependencies with adaptation data can undermine privacy despite DP efforts. To analyze this issue in practice, we investigate privacy risks under DP adaptations in LLMs using state-of-the-art attacks such as robust membership inference and canary data extraction. We benchmark these risks by systematically varying the adaptation data distribution, from exact overlaps with pretraining data, through in-distribution (IID) cases, to entirely out-of-distribution (OOD) examples. Additionally, we evaluate how different adaptation methods and different privacy regimes impact the vulnerability. Our results show that distribution shifts strongly influence privacy vulnerability: the closer the adaptation data is to the pretraining distribution, the higher the practical privacy risk at the same theoretical guarantee, even without direct data overlap. We find that parameter-efficient fine-tuning methods, such as LoRA, achieve the highest empirical privacy protection for OOD data. Our benchmark identifies key factors for achieving practical privacy in DP LLM adaptation, providing actionable insights for deploying customized models in sensitive settings. Looking forward, we propose a structured framework for holistic privacy assessment beyond adaptation privacy, to identify and evaluate risks across the full pretrain-adapt pipeline of LLMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.09125v1">Unveiling Privacy Risks in Multi-modal Large Language Models: Task-specific Vulnerabilities and Mitigation Challenges</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-08T07:19:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tiejin Chen, Pingzhi Li, Kaixiong Zhou, Tianlong Chen, Hua Wei</p>
    <p><b>Summary:</b> Privacy risks in text-only Large Language Models (LLMs) are well studied, particularly their tendency to memorize and leak sensitive information. However, Multi-modal Large Language Models (MLLMs), which process both text and images, introduce unique privacy challenges that remain underexplored. Compared to text-only models, MLLMs can extract and expose sensitive information embedded in images, posing new privacy risks. We reveal that some MLLMs are susceptible to privacy breaches, leaking sensitive data embedded in images or stored in memory. Specifically, in this paper, we (1) introduce MM-Privacy, a comprehensive dataset designed to assess privacy risks across various multi-modal tasks and scenarios, where we define Disclosure Risks and Retention Risks. (2) systematically evaluate different MLLMs using MM-Privacy and demonstrate how models leak sensitive data across various tasks, and (3) provide additional insights into the role of task inconsistency in privacy risks, emphasizing the urgent need for mitigation strategies. Our findings highlight privacy concerns in MLLMs, underscoring the necessity of safeguards to prevent data exposure. Our dataset and code can be found here.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.09946v1">SPARX: Secure and Privacy-Aware Approximate CNN Acceleration with Edge RISC-V SoC</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Hardware Architecture-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-06-08T07:02:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sonu Kumar, Akash Sankhe, Mukul Lokhande, Santosh Kumar Vishvakarma</p>
    <p><b>Summary:</b> Edge-AI systems increasingly require real-time CNN inference under strict energy, performance, security, and privacy constraints. Approximate computing improves hardware efficiency by exploiting the error resilience of neural network workloads; however, most approximate CNN accelerators do not jointly consider secure, privacy-aware edge deployment. This paper presents SPARX, a Secure and Privacy-Aware Approximate CNN Acceleration framework integrated within a heterogeneous RV32IMC RISC-V System-on-Chip (SoC). SPARX combines a custom RISC-V instruction extension, an approximate logarithmic CNN acceleration unit, a lightweight differential-noise-based privacy engine, and a challenge-response authentication mechanism. To guide arithmetic selection, an approximation-aware decision framework is introduced that uses the Approximation Severity Index (ASI), Approximation Efficiency (AE), Quality of Approximation (QoA), Approximation Figure-of-Merit (AFOM), and Hardware Acceleration Efficiency (HAE). Evaluation across 11 state-of-the-art approximate MAC architectures identifies the Iterative Logarithmic Multiplier (ILM) as the most suitable design, achieving 51.7% area reduction, 81.5% power reduction, and 2.13x throughput improvement compared with an accurate radix-4 Booth MAC, while only reducing ResNet-20/CIFAR-10 accuracy by 2.82 percentage points. FPGA implementation on a Xilinx VC707 platform achieves 58.4 GOPS/W energy efficiency at 250 MHz, while 28-nm CMOS physical implementation validates ASIC feasibility</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.08681v1">Asymptotic Optimality of the High-Dimensional Gaussian Mechanism and Improved Low-Dimensional Mechanisms for Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-07T15:33:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yu Wei, Alexander Bienstock, Antigoni Polychroniadou</p>
    <p><b>Summary:</b> The additive noise mechanism is a foundational tool for differential privacy (DP) of $T$-dimensional real-valued vector queries. The Gaussian mechanism, utilizing Gaussian noise, is the mostly widely used such mechanism, due to its simplicity and strong privacy guarantees. In this work, we provide justification for this choice, showing that as the dimension $T\to\infty$, no additive-noise mechanism can asymptotically improve on the Gaussian mechanism's privacy--utility tradeoff for the strong privacy settings typically used.We also develop a new family of \emph{Spherical Generalized Gamma} DP mechanisms, which contains both the Gaussian mechanism and the recently studied $\ell_2$ mechanism (Joseph \emph{et al.}, ICML 2025). We identify members of this family that outperform both the Gaussian and $\ell_2$ mechanisms in certain low-dimensional settings, and show tight composition of all mechanisms in this family, answering an open question of Joseph \emph{et al.}~regarding the $\ell_2$ mechanism.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.08521v1">Exploring CKKS Parameter Trade-offs for Privacy-Preserving Personalized Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-07T08:58:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kamolchanok Saengtong, Phanwadee Sinthong, Norrathep Rattanavipanon</p>
    <p><b>Summary:</b> Privacy-preserving Personalized Federated Learning (PFL) enables clients to collaboratively train personalized models without exposing raw data, but exchanged model updates remain vulnerable to inference attacks from honest-but-curious servers. Homomorphic Encryption (HE) addresses this by allowing server-side aggregation directly on encrypted updates, with the CKKS scheme being particularly suitable due to its native support for approximate floating-point arithmetic. However, no prior work has examined how to configure CKKS for PFL deployments, leaving practitioners without principled guidance on parameter selection that directly affects privacy, precision, and computational cost. This paper presents pFedCKKS, a generic framework integrating CKKS into PFL, and provides the first systematic parameter selection guide for practitioners. We derive the full CKKS parameter constraints under 128-bit security for the PFL setting, showing the selection problem reduces to choosing just two values: the inner and outer ciphertext prime. Implemented using the Flower framework and TenSEAL library, pFedCKKS is evaluated on the FEMNIST, CelebA and Sentiment140 datasets with FedFinetune, Ditto and FedPer which represents PFL algorithms. Experimental results reveal an empirical trade-off between precision and computational/communication costs. This allows us to draw a concrete guideline for selecting proper CKKS parameters that balance efficiency and accuracy in real-world deployments of pFedCKKS.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.08252v1">Quantifying and Defending against the Privacy Risk in Logit-based Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-06-06T16:40:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sheng Wan, Dashan Gao, Hanlin Gu, Lixin Fan, Daning Hu, Qiang Yang</p>
    <p><b>Summary:</b> Federated learning aims to protect data privacy by collaboratively learning a model without sharing private data among clients. Unlike traditional parameter-based FL methods that exchange model weights or gradients during training, emerging logit-based FL approaches share model outputs (logits) on public data. This strategy promotes model heterogeneity, reduces communication overhead, and enhances clients' privacy. However, the potential privacy risks associated with these logit-based methods have been largely overlooked. This research presents the first theoretical and empirical analysis of a hidden privacy risk in logit-based FL methods - the risk that a semi-honest server (adversary) may learn clients' private models from logits. To quantify and address this threat, we develop the Adaptive Model Stealing Attack (AdaMSA) by leveraging historical logits during training. Notably, we observe that this inherent privacy risk persists even when public data is unrelated to private data, emphasizing the urgency to address privacy vulnerabilities in logit-based FL methods. Moreover, our theoretical analysis establishes the bounds of this privacy risk. We then propose a simple but effective defense strategy that perturbs the transmitted logits in the direction that minimizes the privacy risk while maximally preserving the training performance. The experimental results validate our analysis and demonstrate the effectiveness of AdaMSA and our defense strategy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.09908v1">IDP-Bench: Benchmarking ability of LLMs to protect personal information in interdependent privacy contexts</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-06T07:59:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ayana Hussain, Soumya Sharma, Golnoosh Farnadi, Nicholas Vincent, Héber Hwang Arcolezi, Ulrich Aïvodji</p>
    <p><b>Summary:</b> Large language models (LLMs) are becoming widely deployed as personal AI assistants with access to sensitive user data, making privacy a major challenge for their design and evaluation. Prior work focuses mainly on individual-level risks, overlooking \textbf{interdependent privacy (IDP)}--where one person's data may be revealed by others without their knowledge or consent. We address this gap by introducing \textbf{IDP-Bench}: the first LLM benchmark for IDP scenarios, grounded in the Contextual Integrity (CI) framework. We evaluate eight open-source LLMs on their understanding of IDP scenarios across three levels of IDP reasoning using two LLM judges. Results show strong co-ownership recognition (6/8 models exceed 90\%) but persistent weaknesses in identifying CI parameters (information attribute, primary subject) and IDP-specific parameters such as secondary subjects, where 7/8 models score below 74\%. Models also struggle to judge sharing appropriateness (5/8 scoring below 77\%). While the ability to judge the appropriateness of sharing improves with scale, performance tends to decline in smaller models, and prompt sensitivity remains high on IDP-specific questions--highlighting the need for more targeted study of IDP in LLM privacy research. Data \& code available \href{https://github.com/tisl-lab/Interdependent_Privacy_Bench}{here}.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.07883v1">DP4SQL: Differentially Private SQL with Flexible Privacy Policies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2026-06-05T22:35:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Andrew Cascio, KinChin Tong, Daniel Kifer, Zeyu Ding, Danfeng Zhang</p>
    <p><b>Summary:</b> The plausible deniability model of differential privacy for single-table datasets is well-understood. However, applying differential privacy to relational databases is much trickier: each application needs flexibility in specifying the pieces of information about an entity, spread across multiple relations, that require plausible deniability guarantees. Existing differentially private SQL systems only support rigid privacy policies. Even seemingly small changes, such as specifying that some tables need to protect the existence of records while others only need to protect the record contents, require significant manual effort in updating their privacy accountants and proving their correctness.
  One example of a challenge is the presence of partially public data. Public columns in a table (e.g., faculty names in a university dataset and partial course enrollment information) can cause some queries to require more noise (compared to fully private data), while others require less noise. This kind of reasoning is not supported in existing systems. Another example is when different parts of records (e.g., demographics, financial data) require different levels of privacy protection. Again, existing differentially private SQL systems need to rewrite their rules for calculating query stability in order to support such a feature. This paper presents DP4SQL, a differentially private SQL system that allows data curators to better customize the plausible deniability requirements for their relational databases. This avoids the drawbacks of the "one-size-fits-all" systems that would either underprotect the data or inject too much noise into query answers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.09460v1">A 65-nm Privacy-Preserving Neuromorphic Encoder With 7.13-nJ Efficiency, 2.38-Mb/mm^2 Item-Memory Density, and Federated Learning Support</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Hardware Architecture-04E762">
  <p><b>Published on:</b> 2026-06-05T16:50:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Boyang Cheng, Jianbo Liu, Steven Davis, Zephan M. Enciso, Likai Pei, Xueji Zhao, Muya Chang, Ningyuan Cao</p>
    <p><b>Summary:</b> The increasing demand for privacy-preserving personal data analytics in smart assistants, wearable health monitors, and context-aware systems calls for hardware that is both energy-efficient and secure. This work presents a 65-nm privacy-preserving neuromorphic encoder that leverages transistor-level process variation as physically unclonable entropy for hyperdimensional computing. The proposed 2T-2T entropy cell enables compact, device-specific, and write-free item memory, allowing privacy-preserving bio-signal encoding without storing random basis vectors in conventional memory. The fabricated prototype achieves 7.13 nJ per encoding, 2.38 Mb/mm^2 item-memory density, 76.44 nJ per prediction, and 357.32 nJ per training update. It also supports in-situ decision-making, continual learning, and federated learning for multi-user deployment and cold-start personalization. Evaluations across bio-signal datasets demonstrate 93.2% accuracy on EMG and 96.1% accuracy on UCI-HAR, while reducing hypervector dimensionality by 14.3x compared with binary hyperdimensional computing. These results demonstrate an energy-efficient and privacy-preserving neuromorphic hardware platform for secure edge biomedical intelligence.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.07443v1">Sort, Partition, Randomize: Optimal Binary Hypothesis Testing under Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-05T16:41:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Elena Ghazi, Jawad Nasser, Flavio Calmon, Ibrahim Issa</p>
    <p><b>Summary:</b> We study optimal design of $\varepsilon$-locally differentially private mechanisms for binary hypothesis testing. Each observation is drawn from one of two known distributions $P_0,P_1$ on a finite alphabet of size $k$, privatized by a mechanism $Q$, and then used to infer which distribution generated the data. We measure testing utility using an $f$-divergence, including total variation, KL, and hockey-stick divergences, between the two induced output distributions. Previous work established structural properties of optimal mechanisms, but only yielded exponential-time algorithms. We prove a sharp structure: for every $\varepsilon$ and every $f$-divergence objective, after sorting the alphabet by likelihood ratio, there exists an optimal mechanism that partitions the sorted alphabet into contiguous blocks and applies randomized response to the block label. We call this class Sort-Partition-Randomize (SPR). This characterization yields an exact dynamic program that computes an optimal mechanism in $O(k^3)$ time, and more generally in $O(\ell k^2)$ time with an $\ell$-output budget. Our results make it possible to efficiently compute and characterize the exact optimum across the full privacy range, beyond asymptotic privacy regimes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.07175v1">Seeing Without Exposing: Adaptive Privacy Control for Open-World, Context-Hungry MLLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-06-05T11:41:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Siyuan Xu, Yibing Liu, Peilin Chen, Yung-Hui Li, Shiqi Wang, Sam Kwong</p>
    <p><b>Summary:</b> Multimodal large language models (MLLMs) have raised new privacy challenges. On the data side, user-provided inputs often include unpredictable sensitive information; while on the downstream task side, model reasoning depends on rich visual context that may itself be privacy-sensitive. Existing privacy protection methods, however, rely on predefined sensitive categories and fixed obfuscation strategies, struggling to tackle such challenges in MLLMs. To address this dilemma, we propose Anchored Privacy Drifting (APD), a training-free method that drifts privacy-sensitive elements toward semantically equivalent alternatives while anchoring contextual cues to the source image. To systematically evaluate this dual objective of privacy protection and contextual preservation, we introduce AdaptShield, a comprehensive benchmark covering 22 privacy categories, which combines conventional privacy metrics with MLLM-based assessments of contextual utility. Extensive experiments show that our method achieves balanced improvements in both privacy sanitization and content retention, with average gains of 10.4% on textual categories and 8.5% under MLLM-based evaluation across four MLLM series, i.e., Qwen2.5, Qwen3, InternVL3, and InternVL3.5.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.07171v1">When Recovery Matters: The Blind Spot of Surrogate Privacy in MLLM Editing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-06-05T11:40:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Siyuan Xu, Yibing Liu, Peilin Chen, Yung-Hui LI, Shiqi Wang, Sam Kwong</p>
    <p><b>Summary:</b> Multimodal Large Language Models (MLLMs) enable flexible instruction-driven image editing, but privacy risks arise when user images expose diverse and user-specific private content. Canonical privacy protection strategies typically substitute sensitive regions with surrogate content before cloud editing. Yet, the resulting output is often an edited surrogate rather than the desired edited source image, neglecting the local recovery in both design and evaluation scope. To this end, we introduce SPPE (Surrogate-based Privacy-Preserving Editing), the first recovery-oriented benchmark covering 36 fine-grained privacy categories and 65 editing instructions. It defines two complementary tasks: 1) editability assessment, which estimates before cloud interaction whether a surrogate can induce an edit consistent with the original image; and 2) surrogate-to-source edit recovery, which evaluates whether the edited surrogate can be transferred back to the private source with the edit effect preserved. We address each task with a dedicated method: ERMA predicts surrogate editability through instruction-aware multimodal relation modeling, while \method performs cycle-consistent recovery by using the surrogate editing pair as visual edit evidence and the source image as a source-preserving anchor. Experiments on SPPE and InstructPix2Pix show consistent improvements on both tasks. For editability assessment, ERMA improves over the best-performing baselines by 13.9% in SRCC and 12.3% in PLCC. For surrogate-to-source edit recovery, C2E-S2SER outperforms SOER across all 8 source integrity and edit consistency metrics on SPPE.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.07150v1">From Privacy to Workflow Integrity: Communication-Graph Metadata in Autonomous Agent Interoperability</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-06-05T11:07:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bijaya Dangol</p>
    <p><b>Summary:</b> Agent-interoperability protocols such as A2A and MCP standardize what agents say to one another, but assume address-based transport over HTTP(S). Such transports protect message content, increasingly with end-to-end encryption. What they leave in the clear is the communication graph: which agent contacts which, when, and how often. In agent systems this graph is more consequential than a privacy framing suggests. Endpoints are often capability-labeled, workflows are structured and chained, and interactions are coupled to real actions, so an observer recovers more than past relationships. It can infer the pending workflow, the task being assembled and the action likely to follow. At machine speed, it can act on that inference before the workflow completes. The threat is therefore one of workflow integrity, not privacy alone: predictive leverage over autonomous action. We give a threat model for the agent communication graph; identify what makes agent metadata distinctively revealing (semanticity, prospectivity, actuation); define transport- and bootstrap-layer privacy properties and weigh candidate transports (SimpleX/SMP, Tor, mixnets) against them; and present an A2A case study in which a metadata-protecting binding is expressible but surfaces the protocol's identity assumptions. We test these on a generative model anchored to a real A2A capture. From passive metadata alone, with no payloads, a classifier recovers a task's class well above chance, from only the workflow's opening; applied together, the properties drive that recovery sharply back toward chance. Beyond what an observer can recover, we measure the leverage of acting on the leak: from a workflow's opening and under a fixed budget, an adversary choosing which workflows to act on realizes in this model most of a clairvoyant attacker's advantage over a metadata-blind one, and the same properties suppress it.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.06784v1">What Your Posts Reveal: A Benchmark and Agentic Framework for User-Level Privacy Leakage on Social Media</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-06-05T00:02:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zifan Peng, Yini Huang, Aiwen Lu, Qiming Ye, Peixian Zhang, Jingyi Zheng, Yule Liu, Xuechao Wang, Xinlei He, Jiaheng Wei</p>
    <p><b>Summary:</b> Public social media posts can reveal private information through weak cues scattered across text, images, or metadata. Such leakage is often cumulative and cross-post: cues that appear harmless in isolation may jointly expose a user's home, workplace, or routine. However, current research lacks a unified benchmark for user-level multimodal privacy leakage and an evaluation metric that captures exposure severity beyond binary accuracy.
  To address these gaps, we propose SopriBench, a synthetic benchmark guided by leakage patterns abstracted from a private reference corpus of Rednote and Instagram accounts, covering 50 user profiles and 1,569 images with attributes, contextual sensitivity, granularity, leakage type, inference difficulty, and supporting evidence. We further introduce the Privacy Exposure Score (PES), which weights value granularity by contextual sensitivity. Inspired by abductive reasoning, we introduce Argus, a training-free agentic framework for cumulative leakage inference. Argus forms hypotheses from accumulated evidence, verifies supporting evidence, and aggregates cross-post cues into privacy profiles, achieving 0.55 PES, a 25% improvement over the strongest baseline, with the largest gain on cross-post leakage.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.06354v1">Credential Disclosure in (EU) Digital Identity Wallets: Privacy Risks and Practical Mitigations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-04T16:22:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sheila Zingg, Daniele Lain, Yoshimichi Nakatsuka, Kari Kostiainen, Stefan Bechtold, Srdjan Čapkun</p>
    <p><b>Summary:</b> The European Union will introduce the EUDI Wallet by late 2026, which allows users to hold digital credentials (i.e., representations of physical official identity documents) on their devices. This will allow users to securely and privately disclose identity attributes to websites. Although such a system has many benefits, it also introduces risks caused by poor credential disclosure decisions. In this paper, we (i) conduct a large-scale survey on credential disclosure with users and experts and (ii) evaluate the effectiveness and feasibility of our Credential Assistant that displays expert recommendations and user opinions. Our results show that users are likely to overshare (e.g., ~20% of users disclosed their official ID to news websites). This indicates that users struggle to protect their privacy, which will impact the usability of the EUDI Wallet and lead to privacy violations, identity theft, and other abuses of leaked credentials. Finally, we show that our Credential Assistant significantly reduces users' credential disclosure mistakes from ~15% to ~7%. However, it does not fully eliminate poor credential disclosure decisions, indicating that stronger interventions may be necessary, especially for sensitive attributes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.06334v1">Quantifying the Privacy of Counterfactuals by Leveraging Membership Inference Attacks Against Synthetic Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-06-04T16:08:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maryam Babaei, Yingke Wang, Hadrien Lautraite, Heber H. Arcolezi, Ulrich Aivodji, Sebastien Gambs</p>
    <p><b>Summary:</b> Counterfactuals are typically used in high-stakes decision areas to explain a machine learning model by showing how changes to the user profiles result in the desired outcome. However, explaining the model's decisions through counterfactuals can also be exploited by an adversary to conduct privacy attacks against the model or its training data. Drawing on the analogy that counterfactuals provide realistic substitutes for real training data, similar to synthetic data, we demonstrate in this paper how it is possible to successfully perform privacy attacks on counterfactuals by drawing on the attacks developed against synthetic data. More precisely, we investigate the effectiveness of the membership inference attacks designed for synthetic data on various types of counterfactuals. Additionally, while existing membership inference attacks against counterfactuals usually require to be able to query the model, we show how it is possible to perform successful membership inference attacks using only a set of counterfactuals, with no access to the model from which they are generated. Our results demonstrate that model developers should be more cautious when releasing counterfactuals to various users, as it can lead to a privacy breach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.05902v1">PriSrv+: Privacy and Usability-Enhanced Wireless Service Discovery with Fast and Expressive Matchmaking Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-04T09:07:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yang Yang, Guomin Yang, Yingjiu Li, Pengfei Wu, Rui Shi, Minming Huang, Jian Weng, HweeHwa Pang, Robert H. Deng</p>
    <p><b>Summary:</b> Service discovery is a fundamental process in wireless networks, enabling devices to find and communicate with services dynamically, and is critical for the seamless operation of modern systems like 5G and IoT. This paper introduces PriSrv+, an advanced privacy and usability-enhanced service discovery protocol for modern wireless networks and resource-constrained environments. PriSrv+ builds upon PriSrv (NDSS'24), by addressing critical limitations in expressiveness, privacy, scalability, and efficiency, while maintaining compatibility with widely-used wireless protocols such as mDNS, BLE, and Wi-Fi.
  A key innovation in PriSrv+ is the development of Fast and Expressive Matchmaking Encryption (FEME), the first matchmaking encryption scheme capable of supporting expressive access control policies with an unbounded attribute universe, allowing any arbitrary string to be used as an attribute. FEME significantly enhances the flexibility of service discovery while ensuring robust message and attribute privacy. Compared to PriSrv, PriSrv+ optimizes cryptographic operations, achieving 7.62* faster for encryption and 6.23* faster for decryption, and dramatically reduces ciphertext sizes by 87.33%. In addition, PriSrv+ reduces communication costs by 87.33% for service broadcast and 86.64% for anonymous mutual authentication compared with PriSrv. Formal security proofs confirm the security of FEME and PriSrv+. Extensive evaluations on multiple platforms demonstrate that PriSrv+ achieves superior performance, scalability, and efficiency compared to existing state-of-the-art protocols.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.05821v1">PriSrv: Privacy-Enhanced and Highly Usable Service Discovery in Wireless Communications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-04T08:00:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yang Yang, Robert H. Deng, Guomin Yang, Yingjiu Li, HweeHwa Pang, Minming Huang, Rui Shi, Jian Weng</p>
    <p><b>Summary:</b> Service discovery is essential in wireless communications. However, existing protocols provide limited privacy protection, leaking sensitive device information and opening routes to network attacks. This paper proposes a private service discovery protocol, called PriSrv, which enables both service providers and clients to specify fine-grained authentication policies before establishing connections. PriSrv achieves this via a dual-layer matching architecture: an outer layer filters mismatched entities using public attributes, while an inner layer handles mutual authentication using selectively disclosed private attributes. As a core component, we introduce the primitive of anonymous credential-based matchmaking encryption (ACME), which enables dual-layer matching in a single step to achieve bilateral policy control, selective attribute disclosure, and multi-show unlinkability. To instantiate ACME, we design a fast anonymous credential (FAC) scheme providing constant-size credentials and efficient verification. We demonstrate PriSrv's interoperability by integrating it with popular wireless frameworks including EAP, mDNS, BLE, and AirDrop. Detailed formal security proofs and extensive performance evaluations across desktop, laptop, smartphone, and Raspberry Pi platforms demonstrate that PriSrv provides enhanced privacy guarantees with high usability, achieving secure discovery in less than one second on mainstream mobile devices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.05596v1">Multi-Objective Submodular Maximization with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-04T02:18:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ting Hou, Yanhao Wang, Yiping Wang, Cen Chen, Minghao Zhao, Fan Dang</p>
    <p><b>Summary:</b> In this paper, we study multi-objective submodular maximization (MOSM) subject to a cardinality constraint under differential privacy (DP). Specifically, we aim to select a set of at most $k \in \mathbb{Z}_{+}$ elements to maximize the minimum of $d > 1$ monotone submodular functions while satisfying $\varepsilon$-DP. Although extensive studies have been conducted on both differentially private single-objective submodular maximization on sensitive data and non-private MOSM, to the best of our knowledge, there has not yet been any prior work on MOSM with DP. We propose two novel algorithms: the first extends the classic greedy algorithm and the second employs a truncation technique, both of which are integrated with DP mechanisms for privacy protection and achieve approximation guarantees for MOSM. Finally, we conduct numerical experiments on two submodular maximization applications, namely maximum coverage and facility location, in multi-objective settings to validate the efficacy and efficiency of our proposed algorithms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.05561v1">InfoShield: Privacy-Preserving Speech Representations for Mental Health Screening via Information-Theoretic Optimization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-04T01:16:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xueyang Wu, Siyuan Liu, Kezhuo Yang, Guang Ling</p>
    <p><b>Summary:</b> Speech-based mental health screening offers scalable depression detection, yet clinical deployment faces a significant barrier: users' privacy concerns about demographic information exposure. Current techniques struggle to resolve this conflict. Adversarial training often fails against unseen threats, whereas Differential Privacy tends to compromise diagnostic performance by injecting noise across all features. This paper presents InfoShield, which minimizes mutual information between speech representations and sensitive attributes while preserving depression classification accuracy. We identify that standard MINE estimators struggle with sequential speech due to temporal-static misalignment, and introduce TimeAwareMINE with cross-modal attention to align acoustic frames with attribute embeddings. Experiments on the Androids Corpus show InfoShield reduces gender inference from 92.6\% to 55.5\% and age inference from 55.7\% to 30.3\% with limited utility loss (6\% F1 reduction), achieving F1=0.784 compared to prior SOTA's 0.723.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.05129v1">Preserving Data Privacy in Learning Causal Structure with Fully Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-06-03T17:33:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jian Yang, Yuan Tong, Qinbin Li, Zeyi Wen, Xiaofang Zhou</p>
    <p><b>Summary:</b> Preserving data privacy is an important topic in structural data management and data mining. However, the issue of privacy leakage in distributed causal structure learning is a persistent challenge, especially in cases where data transmission and computation are required. In this paper, we propose a method based on fully homomorphic encryption (FHE) that performs calculations on ciphertexts, keeping data encrypted in transition and computation. Nevertheless, adopting FHE to causal structure learning is challenging due to the high computation cost and limited support on division as well as logarithm operations in FHE. To tackle this challenge, we propose a series of novel techniques including (i) circuit simplification for better efficiency, (ii) approximation of division and logarithm through Newton-Raphson Reciprocal and Taylor expansion, and (iii) a batching technique with SIMD-acceleration to enhance the whole learning process. Additionally, our method can be easily extended beyond FHE by demonstration of its portability to support differential privacy. Empirical results show that our method achieves high consistency and comparable causal structure with the plaintext version in the datasets tested. Last, our method is efficient and practical to complete learning causal structures in tens of minutes even under the privacy protection of FHE.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.05273v1">Online Safety Regulation Increases Privacy Risk: Evidence from the UK Online Safety Act</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-03T17:24:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dhyey Mehta, Eldar Jalilzade, Maksim Kalameyets, Rebecca Owens, Marc Juarez, Stergios Aidinlis, Lei Shi, Tuğrulcan Elmas</p>
    <p><b>Summary:</b> Governments worldwide are increasingly regulating digital platforms to reduce online harms, particularly those affecting children. However, access restrictions can alter user behaviour and introduce new privacy and security risks. The UK Online Safety Act (OSA), passed in October 2023, illustrates this trend: it extends age-assurance and safety requirements to social media, search, and pornography services, and rolled out in phases. Ofcom's illegal content enforcement duties came into force in March 2025, and mandatory age verification for adult content took effect in July 2025. This phased rollout enables real-time observation of behavioural responses to regulation. To address this, we analyse Reddit discourse across VPN and UK Politics communities and conduct a privacy-policy risk analysis of 69 unique VPN services.
  We find that each of these three milestones produced significant stepwise increases in VPN-related discussion on Reddit: among UK-based users, posts and comments explicitly about VPN use in a regulatory or privacy context rose by +100%, +217%, and +415% respectively. UK Politics communities showed even larger effects, with OSA-related political discourse rising by +213%, +545%, and +464%, respectively, among UK-based users. UK VPN search interest on Google rose by +89% at the age-verification deadline. Users primarily framed this response around privacy, surveillance, and distrust of age-verification intermediaries rather than simple access-seeking. Demand increased across low, medium, and high-risk VPNs, but the proportional distribution remained broadly stable. These findings suggest that online safety regulation can create secondary privacy costs even when it does not disproportionately shift attention toward higher-risk providers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.05055v1">"A Glimpse, Not a Gaze": Using Generative AI to Balance Privacy and Awareness in Inter-generational Caregiving</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-06-03T16:14:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zixi Christina Li, Keiko Katsuragawa, James R. Wallace</p>
    <p><b>Summary:</b> As older adults increasingly prefer to age in place, their adult children often assume the role of informal caregivers. This dynamic creates a distinct tension between the adult child's need for awareness and the older adult's fundamental right to privacy. Traditional monitoring technologies, such as raw video feeds, often compromise the older adult's autonomy. To address this challenge, this study explores the use of generative Artificial Intelligence (GenAI) to create abstract, privacy-preserving ``visual summaries'' of daily activities. We design a 10-day Experience Sampling Method (ESM) study with dyads consisting of older adults and their adult children. Through daily smartphone prompts, participants report their current context and evaluate pre-generated AI sketches, indicating their willingness to share or receive these images. Follow-up interviews will further investigate participants' boundary-setting behaviours. This research aims to quantify the privacy mismatch between generations and provide actionable design guidelines for applying visual abstraction in AI-mediated caregiving tools, ultimately supporting inter-generational connection while protecting user dignity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.05004v1">SharedRequest: Privacy-Preserving Model-Agnostic Inference for Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-03T15:23:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Peihua Mai, Xuanrong Gao, Youlong Ding, Xianglong Du, Wei Liu, Yan Pang</p>
    <p><b>Summary:</b> With the widespread deployment of public large language models (LLMs) such as ChatGPT, protecting user prompt privacy has become an increasingly critical issue. Existing privacy-preserving inference methods sacrifice either utility or efficiency, and often require model-specific modifications that limit their compatibility. In this paper, we propose SharedRequest, a model-agnostic framework for privacy-preserving LLM inference that reformulates privacy protection at the batch level rather than the individual-prompt level. The key idea is to obscure sensitive information by mixing original prompts with noisy variants, while grouping semantically equivalent instructions to amortize the inference cost over a large batch of queries with minimal impact on LLM response quality. This design is independent of the LLM architecture, requiring no access to model parameters or architectural modification. Empirical results demonstrate that SharedRequest achieves over $20\%$ higher utility compared to prior differential privacy baselines, and its shared-prompt mechanism reduces query cost by up to $5\times$ compared to non-batched inference.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.04411v1">Pepper: High-bandwidth and Scalable Anonymous Broadcast with Cryptographic Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-03T03:38:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chenghao Li, Haoyuan Wang, Xianghang Mi</p>
    <p><b>Summary:</b> We present Pepper, a high-bandwidth anonymous broadcast protocol that provides cryptographic sender anonymity against global adversaries. Pepper builds on a two-server DC-net architecture but introduces three key innovations: a self-contained anonymous registration subprotocol using verifiable distributed point functions, support for batch messaging via distributed multi-point functions, and a lightweight access control mechanism based on secret-shared proofs. Unlike prior systems, Pepper eliminates the need for external dialing services and allows each broadcaster to send multiple messages per epoch with a single audit, significantly improving throughput for large data transfers. Our implementation demonstrates that Pepper achieves millisecond-level registration audits, scales efficiently to thousands of channels, and delivers 1.2--20$\times$ higher effective messaging rates than state-of-the-art alternatives. Furthermore, Pepper is designed for practical deployment, with natural compatibility for co-deployment alongside Tor and federated social networks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.04399v1">DPDL: Towards Differential Privacy Preservation in Decentralized Stochastic Learning on Non-IID Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-03T03:27:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yunsheng Yuan, Xue Xiao, Lina Wang, Feng Li</p>
    <p><b>Summary:</b> In the paradigm of decentralized learning, a group of agents collaborate to train a global model using distributed datasets without a central server. Although the power of collaboration has been verified by many state-of-the-art studies, it entails extensive gradient information exchanging among the agents and thus induces high risk of privacy leakage for the individual agents. Moreover, in real-world applications, the training data are usually non-identically and independently distributed across the agents, inducing more challenges to enable privacy-preserved decentralized learning. To address these issues, we propose a privacy-preserved decentralized learning algorithm with non-IID data, DPDL, which leverages the notion of Differential Privacy (DP) in cross-gradient aggregation through a similarity-based calibration technique. Specifically, in each round, each agent perturbs the cross-gradients (i.e., the derivatives of its neighbors' local model in its private local data) by Gaussian noise mechanism before sharing them with its neighbors; it then adopt cosine similarity to calibrate the received perturbed cross-gradients such that the aggregation of the calibrated cross-gradients can be utilized to effectively update local model in a momentum-like manner. Our rigorous theoretical analysis not only reveals the minimum noise level required to achieve a specific level of privacy preservation, but also illustrates that our algorithm still achieves a linear speedup in training with non-IID data. We finally conduct extensive experiments on real-world dataset to validate the effectiveness of our algorithm in defending privacy attacks and in training accurate models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.04384v1">Revisiting Privacy Amplification by Subsampling in Selective Release DPSGD</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2026-06-03T03:00:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaobo Huang, Fang Xie</p>
    <p><b>Summary:</b> Machine learning's reliance on sensitive data necessitates privacy-preserving techniques like Differentially Private Stochastic Gradient Descent (DPSGD). However, DPSGD suffers from substantial utility degradation and slow convergence due to gradient clipping and noise injection. Prior works have attempted to improve DPSGD from various perspectives; notably, the Differentially Private Selective Update and Release (DPSUR) algorithm has achieved remarkable model utility. However, the privacy accounting in DPSUR overlooks the variation in sampling probability introduced by the selective release mechanism, which compromises the rigor of its privacy guarantees. To address these limitations, we re-evaluate the privacy analysis of the selective release mechanism and propose a novel algorithm: Differentially Private Selective Release based on Clipped Gradients (DPSR-CG). Through a rigorous, newly derived privacy analysis and extensive experiments on multiple datasets (MNIST, CIFAR-10, IMDB, and FMNIST), we demonstrate that our DPSR-CG mechanism maintains strict privacy guarantees while achieving exceptional model performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.04338v1">Federated Learning for Multi-Center Sepsis Early Prediction with Privacy-Preserving</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-03T01:35:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xixi Tian, Di Wu, Xiang Liu, Yiziting Zhu, Yujie Li, Xin Shu, Bin Yi</p>
    <p><b>Summary:</b> Privacy-sensitive and distributed characteristics of multi-center medical data bring severe obstacles to centralized modeling for accurate early prediction of sepsis. Federated learning (FL) has attracted growing attention as a promising framework for collaborative model development, as it allows multiple institutions to jointly train predictive models without directly sharing or centralizing raw data. Nevertheless, its practical performance, robustness, and privacy-preserving benefits remain insufficiently evaluated using real-world clinical datasets. To bridge this gap, this study systematically examines the application of federated learning to multi-center sepsis prediction. The experimental dataset consists of 648 clinically screened samples collected from three tertiary hospitals in China, with rigorous inclusion and exclusion criteria. We establish a centralized training paradigm as the performance baseline, and then implement a horizontal federated learning framework for distributed collaborative modeling. Extensive experimental results demonstrate that the federated learning-based model achieves highly comparable prediction accuracy to the centralized counterpart, while fundamentally avoiding privacy leakage. Further privacy security analysis verifies that malicious attackers cannot reconstruct the original patient data from the transmitted model parameters, indicating strong resistance against data reconstruction attacks. This work not only validates the practicality and security of federated learning in clinical sepsis prediction, but also provides a reliable and feasible solution for privacy-preserving multi-center medical collaboration.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.03878v1">Privacy-Robust Incrementality Measurement for Advertising Systems under Signal Loss</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-06-02T16:46:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Prashant Shekhar, Caroline Howard</p>
    <p><b>Summary:</b> Advertising platforms use randomized lift tests to measure incrementality, but privacy-preserving reporting systems degrade the observed signal through match-rate loss, linkability loss, attribution-window loss, aggregation-threshold suppression, randomized reporting noise, and segment-heterogeneous signal loss. This paper formulates privacy-constrained advertising measurement as a robust causal decision problem under the mentioned signal losses. Given a randomized experiment and an ambiguity set for privacy-induced degradation, the framework projects the observation-compatible fiber of clean/unfiltered experimental worlds onto the incrementality functional and returns certified, rejected, and unresolved decisions. The main result gives a sharp decision frontier. Reports outside the frontier support uniformly valid certification or rejection, whereas reports inside it contain too little information for any method to uniformly distinguish above-threshold incrementality from non-incrementality. Supporting results give finite-sample certification, sample-complexity guarantees, a minimax lower bound showing that signal loss reduces effective information, and a reporting-granularity tradeoff. On 2.0M Criteo Uplift rows and the 64K-row Hillstrom email experiment, clean conversion lift is positive in both datasets, with lifts 0.00112 and 0.00495, respectively. Population certification survives mild degradation in Criteo and severe degradation in Hillstrom, while all considered finite-sample stress settings in both datasets remain unresolved after simultaneous uncertainty and reporting noise are included. Overall, the research contributes a decision-theoretic layer for privacy-aware incrementality measurement whose output is the strongest causal-claim justified by degraded ads signals.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.03714v1">Don't Trust Us: A privacy-by-design android malware detection pipeline</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-02T14:36:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Emmanuele Massidda, Diego Soi, Giorgio Giacinto</p>
    <p><b>Summary:</b> Android malware detection increasingly relies on collecting and processing sensitive user data, including device identifiers, network artifacts, and runtime traces, while privacy is too often treated as a secondary concern. Existing privacy-aware approaches typically enforce privacy after data collection, for example, through anonymization, encryption, or federated learning, yet still require access to user information and therefore demand a high level of user trust in systems that already operate with privileged access to device activity. We argue that this requirement should be removed rather than managed. Android malware detection should be privacy-aware by design, so that effective analysis does not depend on sensitive data being accessed in the first place. To this end, we first formalize a set of design requirements for privacy-by-design detection and then implement each requirement in a comprehensive pipeline. First, static analysis is performed to extract relevant data from each APK, following the Drebin representation, which is then submitted to an SVM after vectorization. The model is equipped with a dual-reject threshold rule that either commits to a confident decision or defers uncertain samples to a dynamic analysis stage within a sandboxed environment, so that genuine user information never enters the analysis loop. Results confirm that, on a temporally split dataset spanning from 2024 to 2025, the pipeline achieves an F1 score of 0.87 with the first static analysis stage, deferring only 6.7% of test samples to secondary dynamic analysis. Additionally, dynamic sandboxing helps recognize applications' maliciousness with high confidence without extracting any sensitive data. These results demonstrate that strong detection performance is achievable without sacrificing user privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.04069v1">Bayesian Membership Privacy for Graph Neural Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-06-02T14:33:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sinan Yıldırım, Megha Khosla</p>
    <p><b>Summary:</b> Existing privacy analyses for Graph Neural Networks (GNNs) largely inherit assumptions from non-graph settings, overlooking structural correlations and stochastic training-graph sampling. In particular, node-dependent priors make type-I and type-II errors alone insufficient to characterize the best membership inference test. To address this, we introduce Bayesian Membership Privacy (BMP), a sampling-aware formulation of node-level membership privacy that incorporates node-dependent priors and treats graph sampling probabilities as part of the adversary's knowledge. BMP casts membership inference as a Bayesian hypothesis test and accordingly quantifies membership privacy in terms of posterior membership probability. We explore theoretical properties of BMP in relation to the existing definitions in the literature. We further propose a practical, sampling-aware auditing mechanism to estimate the parameters of BMP as a measure of node-level privacy leakage in GNNs. We conduct experiments on benchmark graph datasets and show that BMP yields fine-grained privacy insights that are not visible through global attack accuracy alone.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.03711v1">Ghost: Plausible Yet Unlearnable Trajectories via On-Manifold Substitution for Next-POI Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2026-06-02T14:31:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhenyu Yu, Jihong Guan, Shuigeng Zhou</p>
    <p><b>Summary:</b> A publisher who releases check-in trajectories inadvertently publishes a strong predictor of every user's future locations. We address this risk by generating unlearnable trajectories, perturbed sequences that yield victim models with degraded next-Point-of-Interest (next-POI) accuracy on clean test inputs. Direct ports of image-domain unlearnable examples fail on two counts. The published data must remain geographically and semantically plausible, and the perturbation must resist purification adversaries that exploit the structure of randomized defences. We propose Ghost, a manifold-aligned framework whose perturbations look like plausible human check-in sequences yet leave no learnable signal behind. Ghost steers each substitution onto the real-trajectory manifold through a frozen trajectory language model, so a denoising-bridge adversary has nothing to invert and a context-free frequency-table adversary recovers a near-uniform distribution. Across two standard benchmarks, and four attacker postures, Ghost achieves protection-gap competitive with the strongest deterministic baseline (PGD) while attaining the lowest restored accuracy under the bigram adaptive purification adversary on both datasets, and lies within one per-cell standard deviation of PGD on the protection-versus-purification-resistance plane. Ablations confirm the manifold prior subsumes the entropy-floor knob of prior randomized defences, with the frequency-table adversary's survival gap remaining within 0.04 even when twenty percent of the pairs are leaked.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.04067v1">Need to Know: Contextual-Integrity-Grounded Query Rewriting for Privacy-Conscious LLM Delegation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-02T14:28:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xinyue Huang, Xiaochun Cao, Wenyuan Yang</p>
    <p><b>Summary:</b> As LLMs become increasingly woven into everyday workflows, user queries sent to cloud hosted LLMs routinely mix task-essential content with task non-essential sensitive disclosures, yet type based PII redaction is context agnostic and may raise two issues: over disclosing untyped sensitive context and over removing answer bearing spans. We recast privacy preserving query rewriting under Contextual Integrity: a span should be forwarded only if it is necessary for the task. We introduce DelegateCI-Bench, the first task based Contextual Integrity benchmark for privacy-conscious delegation, comprising 3,167 samples that combine high quality synthetic data spanning 11 tasks and 20 task types, WildChat based real user queries, and a medical challenge set with dense sensitive information. Building on this benchmark, we propose a CI-guided reinforcement learning framework that converts essential and non-essential sensitive spans into verifiable optimization signals, and train a query rewriter to preserve task critical information while suppressing unnecessary sensitive disclosure. Experiments show that our learned rewriter achieves the best privacy-utility tradeoff, achieving up to +10.1 average utility over on-device baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.03571v1">Channel Chart Location Privacy Based on Geo-Indistinguishability</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-06-02T12:39:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Atsu Kokuvi Angélo Passah, Rodrigo C. de Lamare, Arsenia Chorti</p>
    <p><b>Summary:</b> Channel charting enables location-based services (LBSs) without requiring explicit position information by using pseudo-locations from the channel chart. While this property implies inherent privacy advantages, it does not provide formal privacy guarantees. In this work, we address location privacy in channel charting referred to as chart location indistinguishability (CLI), which extends geo-indistinguishability (GI) to channel charting representations. In order to achieve CLI, a standard planar Laplace mechanism is investigated and a geometry-aware Mahalanobis norm planar Laplace (MNPL) mechanism is devised. The proposed MNPL mechanism perturbs the channel chart by injecting noise aligned with the local structure of the chart. In the CLI framework with MNPL, privacy is defined in latent channel chart manifolds using locally adaptive covariance derived from chart neighborhoods, while preserving manifold topology under privacy constraints. In addition, differential privacy is considered as a privacy baseline. The proposed approach is evaluated across multiple channel charting schemes. The performance is assessed using utility metrics such as quality loss (QL) and range query error (RQE), as well as geometry-aware metrics including trustworthiness (TW) and continuity (CT). Numerical results demonstrate that the proposed privacy mechanism provides strong privacy guarantees while preserving the channel chart for LBSs tasks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.03513v1">Privacy-Preserving High-Resolution Image Gradient Computation Based on Fully Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-02T11:32:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yufei Zhou</p>
    <p><b>Summary:</b> With growing emphasis on privacy protection, homomorphic encryption (HE) has emerged as a core method for privacy-preserving image processing, as it enables operations directly on encrypted data. However, existing research predominantly focuses on low-resolution image processing, and techniques for privacy-preserving high-resolution image processing remain underexplored. As the image size increases, the HE parameters must be adjusted accordingly, and directly applying existing methods can lead to significant computational overhead. In this work, we propose a multi-ciphertext privacy-preserving framework for large images, enabling efficient image encryption and computation under the semi-honest model. Specifically, we divide the large image into multiple sub-images, which allows us to maintain smaller HE parameters and reduce key size. By parallel processing the sub-image ciphertexts and introducing a new bootstrapping placement strategy, we significantly reduce encryption overhead and enhance user experience. On the server side, we optimize the large image convolution operation through a repeated packing technique and implement the Sobel operator computation based on HE. To improve gradient direction calculation for the Sobel operator, we introduce a new polynomial approximation method for the reciprocal function based on the sign function, which can be applied to other HE-based protocols.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.03399v1">Selective Token-Level Cryptographic Redaction for Privacy-Preserving Clinical Deployment of Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-06-02T09:40:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Farhan Sheth, Ziyuan Yang, Yongying Lan, Si Yong Yeo</p>
    <p><b>Summary:</b> While large language models (LLMs) are increasingly used for clinical applications, many existing pipelines require sending raw sensitive health information to remote servers for processing, which heightens the risk of privacy leakage. A natural approach to mitigate this risk is to encrypt the data before transmission. However, straightforward solutions such as encrypting the entire dataset introduce prohibitive computational, alignment, and communication overheads, rendering large-scale practical deployment infeasible. To preserve privacy while maintaining usability, we present Healthcare Encryption & Redaction via Adaptive Linguistic Decomposition (HERALD), a token-level cryptographic redaction framework designed to achieve this balance by encrypting only sensitive tokens while preserving the surrounding context for downstream model utility. HERALD combines medical named-entity recognizer (NER) with part-of-speech (POS) driven policies to select candidate tokens, performs targeted lemmatization to stabilize surface forms, and substitutes each protected token with a deterministic ciphertext wrapped in explicit delimiters. Notably, HERALD is model-agnostic and operates entirely on the client side, ensuring that sensitive content remains encrypted throughout storage, transmission, and processing without requiring changes to downstream models. We evaluated HERALD on both classification and medical question answering (MQA) tasks on public datasets. Across different tasks, experiments illustrate that fully secured baselines suffer significant utility loss, whereas HERALD consistently recovers performance close to plaintext. Overall, HERALD provides a novel utilization pipeline.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.03248v1">Investigating Novice Researchers' Perceptions of Research Privacy Within LLM-Assisted Workflows</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-06-02T07:10:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuning Zhang, Changxi Wen, Eve He, Ying Ma, Robert Xiao, Xin Yi, Hewu Li</p>
    <p><b>Summary:</b> Large Language Model (LLMs)-assisted scholarly workflows introduce critical privacy and intellectual property risks. As a uniquely vulnerable cohort driven by publication pressure and a lack of institutional support, novice researchers rely heavily on public LLMs, compelling them to navigate high-stakes privacy-publication trade-offs. To investigate these concerns, we conducted semi-structured interviews with 44 researchers across diverse disciplines. Our findings reveal that the fear of idea leakage paradoxically accelerates, rather than deters, reliance on LLMs, as researchers utilize them to expedite publication. They also held misconceptions that their ideas lacked the unique value to attract targeted attacks, and that their inputs would be safely diluted within massive datasets, preventing reconstruction. From interviews, we identified five types of mitigations including input fragmentation and adversarial probing, though we found that participants largely perceived these measures as ineffective. We outline implications including implementing institution-level sandboxed isolation, scenario-based privacy pedagogy, and verifiable data-deletion audits for transparency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.03190v1">Focused on the User, Overlooking the Risks: Security and Privacy Understandings, Practices and Challenges of Independent Chinese AI Agent Developers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-06-02T05:49:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuning Zhang, Mingyao Xu, Zhixin Huang, Yutong Jiang, Rongjun Ma, Yuting Yang, Xin Yi, Kanye Ye Wang, Hewu Li</p>
    <p><b>Summary:</b> The proliferation of AI agents empowers independent developers, defined as individual or small groups who self-initiate projects rather than fulfill client-based contracts, to create sophisticated autonomous systems, but also introduces novel security and privacy (S&P) challenges beyond traditional corporate structures. We conducted an interview study (N=28) with Chinese developers, whose extensive use of global LLM services offer valuable insights into this population. We investigate their understandings, practices and challenges of S&P challenges in their developed AI agent products. We revealed that independent developers frequently think and act from their users' perspective. They focused on user-facing safety risks such as harmful content while exhibiting low awareness of security vulnerabilities. Consequently, developers rely almost exclusively on ad-hoc, manually crafted safeguards and informal communication, with an absence of formal tools or processes for S&P practices. We found these actions are driven by various inhibitors, primarily a lack of formal training on S&P related skills, accessible security tools and actionable guidance from platforms. Our work contributed the first exploration of independent AI agent developers' S&P understanding, outlining opportunities for tailored security tooling.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2606.02958v1">Echelon: Auditable Aggregate-Only Language-Model Adaptation Across Privacy Boundaries</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-06-01T23:28:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hina Dixit, Punit Kumar, Irene Tenison, Nevasini Sasikumar</p>
    <p><b>Summary:</b> Cross-organization language-model adaptation increasingly faces hard governance constraints: in many deployments, device-level model state-parameters, activations, optimizer state, and per-device updates-cannot be exported outside an administrative boundary. Existing distributed and federated stacks typically assume cross-site model exchange and then retrofit privacy mechanisms, which complicates compliance and makes auditing brittle. We present Echelon, a boundary-first training architecture that enforces device-level model-state non-export as a systems invariant. Devices train locally inside each boundary; the only cross-boundary payloads are securely aggregated boundary-level deltas plus O(1) coordination metadata, exposed through a concrete audit surface. Restricting exchange to aggregates changes the optimization problem: the system must remain stable under WAN delay, heterogeneous participation, churn, and non-IID data even though the global plane never sees per-device updates. Echelon combines buffered semi-asynchronous secure aggregation, staleness-aware weighting, participation windows, proximal local objectives, and a drift-aware outer synchronization controller. In 1B-parameter LoRA adaptation across M= 2 boundaries, a budget-matched contest over three seeds (24.88M tokens) reaches validation loss 3.887 +/-0.010 and is best or tied-best among tuned low-communication baselines under fixed-token, fixed-bytes, fixed-wall-clock, and fixed-sync-count budgets. In OpenWebText stress tests, Echelon sustains 2,139-2,176 tokens/s across evaluated WAN and non-IID treatments, Echelon-DA improves time-to-target under WAN latency relative to a privacy-parityDiLoCo+SA baseline, and quality degrades by at most 2.2% under 200ms emulated latency or severe non-IID partitioning.</p>
  </details>
</div>


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

