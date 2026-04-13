
<h2>2026-03</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.00326v1">Inference-Aware & Privacy-Preserving Deletion in Databases</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2026-03-31T23:58:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vishal Chakraborty, Youri Kaminsky, Arnav Abhijit Dhariya, Sharad Mehrotra, Felix Naumann, Sarvesh Pandey</p>
    <p><b>Summary:</b> Deletion is a fundamental database operation, yet modern systems often fail to provide the privacy guarantee that users expect from it. A deleted value may disappear from query results and even from physical storage, yet remain inferable from dependencies, derived data, or traces exposed by the deletion event itself. Meaningful deletion, therefore, requires more than logical removal or physical erasure; it requires a privacy guarantee that limits what remains inferable after deletion. In this paper, we take an inference-centric view of deletion, focusing on two leakage channels: leakage from the post-deletion state and leakage from the deletion pattern itself. We use this lens to distinguish logical, physical, and semantic deletion, organize the design space of deletion operations, and highlight open research challenges for building deletion mechanisms with meaningful privacy guarantees in database systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.00312v1">Physically-intuitive Privacy and Security: A Design Paradigm for Building User Trust in Smart Sensing Environments</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-03-31T23:26:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Youngwook Do, Yuxi Wu, Gregory D. Abowd, Sauvik Das</p>
    <p><b>Summary:</b> Sensor-based interactive systems -- e.g., "smart" speakers, webcams, and RFID tags -- allow us to embed computational functionality into physical environments. They also expose users to real and perceived privacy risks: users know that device manufacturers, app developers, and malicious third parties want to collect and monetize their personal data, which fuels their mistrust of these systems even in the presence of privacy and security controls. We propose a new design paradigm, physically-intuitive privacy and security (PIPS), which aims to improve user trust by designing privacy and security controls that provide users with simple, physics-based conceptual models of their operation. PIPS consists of three principles: (1) direct physical manipulation of sensor state; (2) perceptible assurance of sensor state; and, (3) intent-aligned sensor (de)activation. We illustrate these principles through three case studies -- Smart Webcam Cover, Powering for Privacy, and On-demand RFID -- each of which has been shown to improve trust relative to existing sensor-based systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.00209v1">Do LLMs Know What Is Private Internally? Probing and Steering Contextual Privacy Norms in Large Language Model Representations</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-03-31T20:23:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haoran Wang, Li Xiong, Kai Shu</p>
    <p><b>Summary:</b> Large language models (LLMs) are increasingly deployed in high-stakes settings, yet they frequently violate contextual privacy by disclosing private information in situations where humans would exercise discretion. This raises a fundamental question: do LLMs internally encode contextual privacy norms, and if so, why do violations persist? We present the first systematic study of contextual privacy as a structured latent representation in LLMs, grounded in contextual integrity (CI) theory. Probing multiple models, we find that the three norm-determining CI parameters (information type, recipient, and transmission principle) are encoded as linearly separable and functionally independent directions in activation space. Despite this internal structure, models still leak private information in practice, revealing a clear gap between concept representation and model behavior. To bridge this gap, we introduce CI-parametric steering, which independently intervenes along each CI dimension. This structured control reduces privacy violations more effectively and predictably than monolithic steering. Our results demonstrate that contextual privacy failures arise from misalignment between representation and behavior rather than missing awareness, and that leveraging the compositional structure of CI enables more reliable contextual privacy control, shedding light on potential improvement of contextual privacy understanding in LLMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.29907v2">Security and Privacy in Virtual and Robotic Assistive Systems: A Comparative Framework</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-31T15:53:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nelly Elsayed</p>
    <p><b>Summary:</b> Assistive technologies increasingly support independence, accessibility, and safety for older adults, people with disabilities, and individuals requiring continuous care. Two major categories are virtual assistive systems and robotic assistive systems operating in physical environments. Although both offer significant benefits, they introduce important security and privacy risks due to their reliance on artificial intelligence, network connectivity, and sensor-based perception. Virtual systems are primarily exposed to threats involving data privacy, unauthorized access, and adversarial voice manipulation. In contrast, robotic systems introduce additional cyber-physical risks such as sensor spoofing, perception manipulation, command injection, and physical safety hazards. In this paper, we present a comparative analysis of security and privacy challenges across these systems. We develop a unified comparative threat-modeling framework that enables structured analysis of attack surfaces, risk profiles, and safety implications across both systems. Moreover, we provide design recommendations for developing secure, privacy-preserving, and trustworthy assistive technologies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.29668v1">An Empirical Comparison of Security and Privacy Characteristics of Android Messaging Apps</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-31T12:27:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ioannis Karyotakis, Foivos Timotheos Proestakis, Evangelos Talos, Diomidis Spinellis, Nikolaos Alexopoulos</p>
    <p><b>Summary:</b> Mobile messaging apps are a fundamental communication infrastructure, used by billions of people every day to share information, including sensitive data. Security and Privacy are thus critical concerns for such applications. Although the cryptographic protocols prevalent in messaging apps are generally well studied, other relevant implementation characteristics of such apps, such as their software architecture, permission use, and network-related runtime behavior, have not received enough attention. In this paper, we present a methodology for comparing implementation characteristics of messaging applications by employing static and dynamic analysis under reproducible scenarios to identify discrepancies with potential security and privacy implications. We apply this methodology to study the Android clients of the Meta Messenger, Signal, and Telegram apps. Our main findings reveal discrepancies in application complexity, attack surface, and network behavior. Statically, Messenger presents the largest attack surface and the highest number of static analysis warnings, while Telegram requests the most dangerous permissions. In contrast, Signal consistently demonstrates a minimalist design with the fewest dependencies and dangerous permissions. Dynamically, these differences are reflected in network activity; Messenger is by far the most active, exhibiting persistent background communication, whereas Signal is the least active. Furthermore, our analysis shows that all applications properly adhere to the Android permission model, with no evidence of unauthorized data access.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.29497v1">Distilling Human-Aligned Privacy Sensitivity Assessment from Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-03-31T09:40:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gabriel Loiseau, Damien Sileo, Damien Riquet, Maxime Meyer, Marc Tommasi</p>
    <p><b>Summary:</b> Accurate privacy evaluation of textual data remains a critical challenge in privacy-preserving natural language processing. Recent work has shown that large language models (LLMs) can serve as reliable privacy evaluators, achieving strong agreement with human judgments; however, their computational cost and impracticality for processing sensitive data at scale limit real-world deployment. We address this gap by distilling the privacy assessment capabilities of Mistral Large 3 (675B) into lightweight encoder models with as few as 150M parameters. Leveraging a large-scale dataset of privacy-annotated texts spanning 10 diverse domains, we train efficient classifiers that preserve strong agreement with human annotations while dramatically reducing computational requirements. We validate our approach on human-annotated test data and demonstrate its practical utility as an evaluation metric for de-identification systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.29063v1">Uncovering Relationships between Android Developers, User Privacy, and Developer Willingness to Reduce Fingerprinting Risks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-03-30T23:01:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alex Berke, Güliz Seray Tuncay, Michael Specter, Mihai Christodorescu</p>
    <p><b>Summary:</b> The major mobile platforms, Android and iOS, have introduced changes that restrict user tracking to improve user privacy, yet apps continue to covertly track users via device fingerprinting. We study the opportunity to improve this dynamic with a case study on mobile fingerprinting that evaluates developers' perceptions of how well platforms protect user privacy and how developers perceive platform privacy interventions. Specifically, we study developers' willingness to make changes to protect users from fingerprinting and how developers consider trade-offs between user privacy and developer effort. We do this via a survey of 246 Android developers, presented with a hypothetical Android change that protects users from fingerprinting at the cost of additional developer effort.
  We find developers overwhelmingly (89%) support this change, even when they anticipate significant effort, yet prefer the change be optional versus required. Surprisingly, developers who use fingerprinting are six times more likely to support the change, despite being most impacted by it. We also find developers are most concerned about compliance and enforcement. In addition, our results show that while most rank iOS above Android for protecting user privacy, this distinction significantly reduces among developers very familiar with fingerprinting. Thus there is an important opportunity for platforms and developers to collaboratively build privacy protections, and we present actionable ways platforms can facilitate this.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.28972v1">Privacy Guard & Token Parsimony by Prompt and Context Handling and LLM Routing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-03-30T20:16:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alessio Langiu</p>
    <p><b>Summary:</b> The large-scale adoption of Large Language Models (LLMs) forces a trade-off between operational cost (OpEx) and data privacy. Current routing frameworks reduce costs but ignore prompt sensitivity, exposing users and institutions to leakage risks towards third-party cloud providers. We formalise the "Inseparability Paradigm": advanced context management intrinsically coincides with privacy management. We propose a local "Privacy Guard" -- a holistic contextual observer powered by an on-premise Small Language Model (SLM) -- that performs abstractive summarisation and Automatic Prompt Optimisation (APO) to decompose prompts into focused sub-tasks, re-routing high-risk queries to Zero-Trust or NDA-covered models. This dual mechanism simultaneously eliminates sensitive inference vectors (Zero Leakage) and reduces cloud token payloads (OpEx Reduction). A LIFO-based context compacting mechanism further bounds working memory, limiting the emergent leakage surface. We validate the framework through a 2x2 benchmark (Lazy vs. Expert users; Personal vs. Institutional secrets) on a 1,000-sample dataset, achieving a 45% blended OpEx reduction, 100% redaction success on personal secrets, and -- via LLM-as-a-Judge evaluation -- an 85% preference rate for APO-compressed responses over raw baselines. Our results demonstrate that Token Parsimony and Zero Leakage are mathematically dual projections of the same contextual compression operator.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.28903v1">Differential Privacy for Symbolic Trajectories via the Permute-and-Flip Mechanism</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-30T18:30:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alexander Benvenuti, Huaiyuan Rao, Matthew Hale</p>
    <p><b>Summary:</b> Privacy techniques have been developed for data-driven systems, but systems with non-numeric data cannot use typical noise-adding techniques. Therefore, we develop a new mechanism for privatizing state trajectories of symbolic systems that may be represented as words over a finite alphabet. Such systems include Markov chains, Markov decision processes, and finite-state automata, and we protect their symbolic trajectories with differential privacy. The mechanism we develop randomly selects a private approximation to be released in place of the original sensitive word, with a bias towards low-error private words. This work is based on the permute-and-flip mechanism for differential privacy, which can be applied to non-numeric data. However, a naïve implementation would have to enumerate an exponentially large list of words to generate a private word. As a result, we develop a new mechanism that generates private words without ever needing to enumerate such a list. We prove that the accuracy of our mechanism is never worse than the prior state of the art, and we empirically show on a real traffic dataset that it introduces up to $55\%$ less error than the prior state of the art under a conventional privacy implementation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.28334v1">Key-Embedded Privacy for Decentralized AI in Biomedical Omics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-03-30T12:04:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rongyu Zhang, Hongyu Dong, Gaole Dai, Ziqi Qiao, Shenli Zheng, Yuan Zhang, Aosong Cheng, Xiaowei Chi, Jincai Luo, Pin Li, Li Du, Dan Wang, Yuan Du, Xudong Xing, Jianxu Chen, Shanghang Zhang</p>
    <p><b>Summary:</b> The rapid adoption of data-driven methods in biomedicine has intensified concerns over privacy, governance, and regulation, limiting raw data sharing and hindering the assembly of representative cohorts for clinically relevant AI. This landscape necessitates practical, efficient privacy solutions, as cryptographic defenses often impose heavy overhead and differential privacy can degrade performance, leading to sub-optimal outcomes in real-world settings. Here, we present a lightweight federated learning method, INFL, based on Implicit Neural Representations that addresses these challenges. Our approach integrates plug-and-play, coordinate-conditioned modules into client models, embeds a secret key directly into the architecture, and supports seamless aggregation across heterogeneous sites. Across diverse biomedical omics tasks, including cohort-scale classification in bulk proteomics, regression for perturbation prediction in single-cell transcriptomics, and clustering in spatial transcriptomics and multi-omics with both public and private data, we demonstrate that INFL achieves strong, controllable privacy while maintaining utility, preserving the performance necessary for downstream scientific and clinical applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.28329v1">Privacy as Commodity: MFG-RegretNet for Large-Scale Privacy Trading in Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB">
  <p><b>Published on:</b> 2026-03-30T12:02:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kangkang Sun, Jianhua Li, Xiuzhen Chen, Weizhi Meng, Minyi Guo</p>
    <p><b>Summary:</b> Federated Learning (FL) has emerged as a prominent paradigm for privacy-preserving distributed machine learning, yet two fundamental challenges hinder its large-scale adoption. First, gradient inversion attacks can reconstruct sensitive training data from uploaded model updates, so privacy risk persists even when raw data remain local. Second, without adequate monetary compensation, rational clients have little incentive to contribute high-quality gradients, limiting participation at scale. To address these challenges, a privacy trading market is developed in which clients sell their differential privacy budgets as a commodity and receive explicit economic compensation for privacy sacrifice. This market is formalized as a Privacy Auction Game (PAG), and the existence of a Bayesian Nash Equilibrium is established under dominant-strategy incentive compatibility (DSIC), individual rationality (IR), and budget feasibility. To overcome the NP-hard, high-dimensional Nash Equilibrium computation at scale, \textit{MFG-RegretNet} is introduced as a deep-learning-based auction mechanism that combines mean-field game (MFG) approximation with differentiable mechanism design. The MFG reduction lowers per-round computational complexity from $\mathcal{O}(N^2 \log N)$ to $\mathcal{O}(N)$ while incurring only an $\mathcal{O}(N^{-1/2})$ equilibrium approximation gap. Extensive experiments on MNIST and CIFAR-10 demonstrate that MFG-RegretNet outperforms state-of-the-art baselines in incentive compatibility, auction revenue, and social welfare, while maintaining competitive downstream FL model accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.27986v1">FedFG: Privacy-Preserving and Robust Federated Learning via Flow-Matching Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-03-30T03:11:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruiyang Wang, Rong Pan, Zhengan Yao</p>
    <p><b>Summary:</b> Federated learning (FL) enables distributed clients to collaboratively train a global model using local private data. Nevertheless, recent studies show that conventional FL algorithms still exhibit deficiencies in privacy protection, and the server lacks a reliable and stable aggregation rule for updating the global model. This situation creates opportunities for adversaries: on the one hand, they may eavesdrop on uploaded gradients or model parameters, potentially leaking benign clients' private data; on the other hand, they may compromise clients to launch poisoning attacks that corrupt the global model. To balance accuracy and security, we propose FedFG, a robust FL framework based on flow-matching generation that simultaneously preserves client privacy and resists sophisticated poisoning attacks. On the client side, each local network is decoupled into a private feature extractor and a public classifier. Each client is further equipped with a flow-matching generator that replaces the extractor when interacting with the server, thereby protecting private features while learning an approximation of the underlying data distribution. Complementing the client-side design, the server employs a client-update verification scheme and a novel robust aggregation mechanism driven by synthetic samples produced by the flow-matching generator. Experiments on MNIST, FMNIST, and CIFAR-10 demonstrate that, compared with prior work, our approach adapts to multiple attack strategies and achieves higher accuracy while maintaining strong privacy protection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.27572v1">On the role of symmetry for staircase mechanisms in local differential privacy efficiency across different privacy regimes</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Probability-5BC0EB"> 
  <p><b>Published on:</b> 2026-03-29T08:13:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chiara Amorino, Arnaud Gloter</p>
    <p><b>Summary:</b> We investigate the structural foundations of statistical efficiency under $α$-local differential privacy, with a focus on maximizing Fisher information. Building on the role of continuous staircase mechanisms, we identify a fundamental symmetry regarding the extremal values $1$ and $e^α$. We demonstrate that when the optimal measure satisfies this symmetry, the Fisher information admits a closed-form expression. More generally, we derive a decomposition of the Fisher information into symmetric and asymmetric components, scaling as $α^{2}$ and $α^{3}$, respectively, for $α\to 0$. This reveals that, if in the high-privacy regime asymmetry is negligible, it is no longer the case as privacy constraints are relaxed.
  Motivated by this, we introduce a class of fully asymmetric privacy mechanisms constructed via pushforward mappings, proving that-unlike their symmetric counterparts-they recover the full Fisher information of the non-private model as $α\to \infty$. We bridge the gap between theory and practice by providing a tractable implementation of these mechanisms, governed by a tuning parameter $c$. This parameter allows for a smooth interpolation between the symmetric regime and the fully asymmetric regime. Furthermore, we demonstrate the versatility of this framework by showing that it encompasses the binomial mechanism as a limiting case.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.27117v1">Gender-Based Heterogeneity in Youth Privacy-Protective Behavior for Smart Voice Assistants: Evidence from Multigroup PLS-SEM</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-03-28T04:11:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Molly Campbell, Yulia Bobkova, Ajay Kumar Shrestha</p>
    <p><b>Summary:</b> This paper investigates how gender shapes privacy decision-making in youth smart voice assistant (SVA) ecosystems. Using survey data from 469 Canadian youths aged 16-24, we apply multigroup Partial Least Squares Structural Equation Modeling to compare males (N=241) and females (N=174) (total N = 415) across five privacy constructs: Perceived Privacy Risks (PPR), Perceived Privacy Benefits (PPBf), Algorithmic Transparency and Trust (ATT), Privacy Self-Efficacy (PSE), and Privacy Protective Behavior (PPB). Results provide exploratory evidence of gender heterogeneity in selected pathways. The direct effect of PPR on PPB is stronger for males (Male: \b{eta} = 0.424; Female: \b{eta} = 0.233; p < 0.1), while the indirect effect of ATT on PPB via PSE is stronger for females (Female: \b{eta} = 0.229; Male: \b{eta} = 0.132; p < 0.1). Descriptive analysis of non-binary (N=15) and prefer-not-to-say participants (N=39) shows lower trust and higher perceived risk than the binary groups, motivating future work with adequately powered gender-diverse samples. Overall, the findings provide exploratory evidence that gender may moderate key privacy pathways, supporting more responsive transparency and control interventions for youth SVA use.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.26970v1">HFIPay: Privacy-Preserving, Cross-Chain Cryptocurrency Payments to Human-Friendly Identifiers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-03-27T20:26:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jian Sheng Wang</p>
    <p><b>Summary:</b> Sending cryptocurrency to an email address or phone number should be as simple as a bank transfer, yet naive schemes that map identifiers directly to blockchain addresses expose the recipient's balances and transaction history to anyone who knows the identifier.
  HFIPay separates private routing, sender-side quote verification, and on-chain claim authorization. A relay resolves the human-friendly identifier off-chain and commits only a per-intent blinded binding rho_i plus the quoted payment tuple; the chain sees neither the identifier nor a reusable recipient tag. In a verified-quote deployment, the relay returns a sender-verifiable off-chain proof linking rho_i to an attested binding-key commitment, so the relay cannot substitute a different recipient before funding. To claim, the recipient proves in zero knowledge -- via ZK-ACE -- that the funded intent's blinded binding matches a handle derived from the same deterministic identity, authorizing release of the quoted asset and amount to a chosen destination.
  We formalize two privacy goals: enumeration resistance and pre-claim unlinkability, and distinguish a baseline deployment (relay trusted for binding correctness) from the verified-quote deployment (binding is sender-verifiable without a public registry). When composed with an NVM runtime, the same mechanism extends to cross-chain settlement. The result is a relay-assisted but non-custodial architecture: relays are privacy and availability dependencies, but cannot redirect funds.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.26890v1">Privacy-Preserving Iris Recognition: Performance Challenges and Outlook</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-03-27T18:10:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Christina Karakosta, Lian Alhedaithy, William J. Knottenbelt</p>
    <p><b>Summary:</b> Iris-based biometric identification is increasingly recognized for its significant accuracy and long-term stability compared to other biometric modalities such as fingerprints or facial features. However, all biometric modalities are highly sensitive data that raise serious privacy and security concerns, particularly in decentralized and untrusted environments. While Fully Homomorphic Encryption (FHE) has emerged as a promising solution for protecting sensitive data during computation, existing privacy-preserving iris recognition systems face significant performance limitations that hinder their practical deployment. This paper investigates the performance challenges of the current landscape of privacy-preserving iris recognition systems using FHE. Based on these insights, we outline a scalable privacy-preserving framework that aligns with all the requirements specified in the ISO/IEC 24745 standard. Leveraging the Open Iris library, our approach starts with robust iris segmentation, followed by normalization and feature extraction using Gabor filters to generate iris codes. We then apply binary masking to filter out unreliable regions and perform matching using Hamming distance on encrypted iris codes. The accuracy and performance of our proposed privacy-preserving framework is evaluated on the CASIA-Iris-Thousand dataset. Results show that our privacy-preserving framework yields very similar accuracy to the cleartext equivalent, but a much higher computational overhead with respect to pairwise iris template comparisons, of $\sim 120\,000 \times$. This points towards the need for the deployment of two-level schemes in the context of scalable $1-N$ template comparisons.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.26603v1">Sustainability Is Not Linear: Quantifying Performance, Energy, and Privacy Trade-offs in On-Device Intelligence</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-03-27T17:00:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Eziyo Ehsani, Luca Giamattei, Ivano Malavolta, Roberto Pietrantuono</p>
    <p><b>Summary:</b> The migration of Large Language Models (LLMs) from cloud clusters to edge devices promises enhanced privacy and offline accessibility, but this transition encounters a harsh reality: the physical constraints of mobile batteries, thermal limits, and, most importantly, memory constraints. To navigate this landscape, we constructed a reproducible experimental pipeline to profile the complex interplay between energy consumption, latency, and quality. Unlike theoretical studies, we captured granular power metrics across eight models ranging from 0.5B to 9B parameters without requiring root access, ensuring our findings reflect realistic user conditions. We harness this pipeline to conduct an empirical case study on a flagship Android device, the Samsung Galaxy S25 Ultra, establishing foundational hypotheses regarding the trade-offs between generation quality, performance, and resource consumption. Our investigation uncovered a counter-intuitive quantization-energy paradox. While modern importance-aware quantization successfully reduces memory footprints to fit larger models into RAM, we found it yields negligible energy savings compared to standard mixed-precision methods. This proves that for battery life, the architecture of the model, not its quantization scheme, is the decisive factor. We further identified that Mixture-of-Experts (MoE) architectures defy the standard size-energy trend, offering the storage capacity of a 7B model while maintaining the lower energy profile of a 1B to 2B model. Finally, an analysis of these multi-objective trade-offs reveals a pragmatic sweet spot of mid-sized models, such as Qwen2.5-3B, that effectively balance response quality with sustainable energy consumption.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.26483v1">EcoFair: Trustworthy and Energy-Aware Routing for Privacy-Preserving Vertically Partitioned Medical Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-03-27T14:45:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mostafa Anoosha, Dhavalkumar Thakker, Kuniko Paxton, Koorosh Aslansefat, Bhupesh Kumar Mishra, Baseer Ahmad, Rameez Raja Kureshi</p>
    <p><b>Summary:</b> Privacy-preserving medical inference must balance data locality, diagnostic reliability, and deployment efficiency. This paper presents EcoFair, a simulated vertically partitioned inference framework for dermatological diagnosis in which raw image and tabular data remain local and only modality-specific embeddings are transmitted for server-side multimodal fusion. EcoFair introduces a lightweight-first routing mechanism that selectively activates a heavier image encoder when local uncertainty or metadata-derived clinical risk indicates that additional computation is warranted. The routing decision combines predictive uncertainty, a safe--danger probability gap, and a tabular neurosymbolic risk score derived from patient age and lesion localisation. Experiments on three dermatology benchmarks show that EcoFair can substantially reduce edge-side inference energy in representative model pairings while remaining competitive in classification performance. The results further indicate that selective routing can improve subgroup-sensitive malignant-case behaviour in representative settings without modifying the global training objective. These findings position EcoFair as a practical framework for privacy-preserving and energy-aware medical inference under edge deployment constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.26417v1">Towards Privacy-Preserving Federated Learning using Hybrid Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-27T13:46:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ivan Costa, Pedro Correia, Ivone Amorim, Eva Maia, Isabel Praça</p>
    <p><b>Summary:</b> Federated Learning (FL) enables collaborative training while keeping sensitive data on clients' devices, but local model updates can still leak private information. Hybrid Homomorphic Encryption (HHE) has recently been applied to FL to mitigate client overhead while preserving privacy. However, existing HHE-FL systems rely on a single homomorphic key pair shared across all clients, which forces them to assume an unrealistically weak threat model: if a client misbehaves or intercepts another's traffic, private updates can be exposed. We eliminate this weakness by integrating two alternative key protection mechanisms into the HHE-FL workflow. The first is masking, where client keys are blinded before homomorphic encryption and later unblinded homomorphically by the server. The second is RSA encapsulation, where homomorphically encrypted keys are additionally wrapped under the server's RSA public key. These countermeasures prevent key misuse by other clients and extend HHE-FL security to adversarial settings with malicious participants. We implement both approaches on top of the Flower framework using the PASTA/BFV HHE scheme and evaluate them on the MNIST dataset with 12 clients. Results show that both mechanisms preserve model accuracy while adding minimal overhead: masking incurs negligible cost, and RSA encapsulation introduces only modest runtime and communication overhead.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.26354v1">Only Whats Necessary: Pareto Optimal Data Minimization for Privacy Preserving Video Anomaly Detection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-03-27T12:26:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nazia Aslam, Abhisek Ray, Thomas B. Moeslund, Kamal Nasrollahi</p>
    <p><b>Summary:</b> Video anomaly detection (VAD) systems are increasingly deployed in safety critical environments and require a large amount of data for accurate detection. However, such data may contain personally identifiable information (PII), including facial cues and sensitive demographic attributes, creating compliance challenges under the EU General Data Protection Regulation (GDPR). In particular, GDPR requires that personal data be limited to what is strictly necessary for a specified processing purpose. To address this, we introduce Only What's Necessary, a privacy-by-design framework for VAD that explicitly controls the amount and type of visual information exposed to the detection pipeline. The framework combines breadth based and depth based data minimization mechanisms to suppress PII while preserving cues relevant to anomaly detection. We evaluate a range of minimization configurations by feeding the minimized videos to both a VAD model and a privacy inference model. We employ two ranking based methods, along with Pareto analysis, to characterize the resulting trade off between privacy and utility. From the non-dominated frontier, we identify sweet spot operating points that minimize personal data exposure with limited degradation in detection performance. Extensive experiments on publicly available datasets demonstrate the effectiveness of the proposed framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.26336v1">From Pixels to Privacy: Temporally Consistent Video Anonymization via Token Pruning for Privacy Preserving Action Recognition</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-03-27T11:57:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nazia Aslam, Abhisek Ray, Joakim Bruslund Haurum, Lukas Esterle, Kamal Nasrollahi</p>
    <p><b>Summary:</b> Recent advances in large-scale video models have significantly improved video understanding across domains such as surveillance, healthcare, and entertainment. However, these models also amplify privacy risks by encoding sensitive attributes, including facial identity, race, and gender. While image anonymization has been extensively studied, video anonymization remains relatively underexplored, even though modern video models can leverage spatiotemporal motion patterns as biometric identifiers. To address this challenge, we propose a novel attention-driven spatiotemporal video anonymization framework based on systematic disentanglement of utility and privacy features. Our key insight is that attention mechanisms in Vision Transformers (ViTs) can be explicitly structured to separate action-relevant information from privacy-sensitive content. Building on this insight, we introduce two task-specific classification tokens, an action CLS token and a privacy CLS token, that learn complementary representations within a shared Transformer backbone. We contrast their attention distributions to compute a utility-privacy score for each spatiotemporal tubelet, and keep the top-k tubelets with the highest scores. This selectively prunes tubelets dominated by privacy cues while preserving those most critical for action recognition. Extensive experiments demonstrate that our approach maintains action recognition performance comparable to models trained on raw videos, while substantially reducing privacy leakage. These results indicate that attention-driven spatiotemporal pruning offers an effective and principled solution for privacy-preserving video analytics.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.26227v2">Privacy-Accuracy Trade-offs in High-Dimensional LASSO under Perturbation Mechanisms</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-03-27T09:50:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ayaka Sakata, Haruka Tanzawa</p>
    <p><b>Summary:</b> We study privacy-preserving sparse linear regression in the high-dimensional regime, focusing on the LASSO estimator. We analyze two widely used mechanisms for differential privacy: output perturbation, which injects noise into the estimator, and objective perturbation, which adds a random linear term to the loss function. Using approximate message passing (AMP), we characterize the typical behavior of these estimators under random design and privacy noise. To quantify privacy, we adopt typical-case measures, including the on-average KL divergence, which admits a hypothesis-testing interpretation in terms of distinguishability between neighboring datasets. Our analysis reveals that sparsity plays a central role in shaping the privacy-accuracy trade-off: stronger regularization can improve privacy by stabilizing the estimator against single-point data changes. We further show that the two mechanisms exhibit qualitatively different behaviors. In particular, for objective perturbation, increasing the noise level can have non-monotonic effects, and excessive noise may destabilize the estimator, leading to increased sensitivity to data perturbations. Our results demonstrate that AMP provides a powerful framework for analyzing privacy-accuracy trade-offs in high-dimensional sparse models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.26224v1">Privacy-Enhancing Encryption in Data Sharing: A Survey on Security, Performance and Functionality</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-27T09:49:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yongyang Lv, Xiaohong Li, Ruitao Feng, Xinyu Li, Guangdong Bai, Leo Zhang, Lili Quan, Willy Susilo</p>
    <p><b>Summary:</b> The vigorous development of the Internet has spurred exponential data growth, yet data is predominantly stored in isolated user entities, hampering its full value realization. In large-scale deployment of ``AI+industries'' such as smart medical care, intelligent transportation and smart homes, the gap between data supply and demand continues to widen, and establishing an effective data sharing mechanism is the core of promoting high-quality industrial development. However, data sharing faces significant challenges in security, performance, and functional adaptability. Privacy-enhancing encryption technologies, including Attribute-Based Encryption (ABE), Proxy Re-encryption (PRE), and Searchable Encryption (SE), offer promising solutions with distinct advantages in enhancing security, improving flexibility, and enabling efficient sharing. Statistical analysis of relevant literature from 2020 to 2025 reveals a rising research trend in ABE, PRE and SE, focusing on their data sharing applications. Firstly, this work proposes a data sharing process framework and identifies 20 potential attacks across its stages. Secondly, this work integrates ABE, SE, PRE with 12 enhancement technologies and examines their multi-dimensional impacts on the security, performance, and functional adaptability of data sharing schemes. Lastly, this work outlines key application scenarios, challenges, and future research directions, providing valuable insights for advancing data sharing mechanisms based on privacy-enhancing encryption technologies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.26219v1">EPDQ: Efficient and Privacy-Preserving Exact Distance Query on Encrypted Graphs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-27T09:42:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xuemei Fu</p>
    <p><b>Summary:</b> With the explosive growth of graph-structured data, graph databases have become a critical infrastructure for supporting large-scale and complex data analysis. Among various graph operations, shortest distance queries play a fundamental role in numerous applications, such as path planning, recommendation systems, and knowledge graphs. However, existing encrypted graph query methods still suffer from limitations in computational efficiency and system scalability, making it challenging to support efficient query processing over large-scale encrypted graph data. To address these challenges, this paper proposes a tensor-based shortest distance query scheme for encrypted graph databases. The proposed method integrates an encrypted 2-hop cover indexing framework with the Pruned Landmark Labeling (PLL) technique, thereby constructing an efficient and privacy-preserving indexing mechanism. Furthermore, a tensorized representation is introduced to uniformly model graph structures, which effectively reduces computational complexity while ensuring data privacy, and significantly improves the scalability of the system. Extensive experimental evaluations on large-scale graph datasets demonstrate that the proposed approach achieves superior scalability and lower computational costs compared with existing encrypted graph query methods. Moreover, it provides strong privacy protection guarantees, making it well suited for privacy-preserving graph query applications in cloud computing and distributed environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.26215v2">SuperDP: Differential Privacy Refutation via Supermartingales</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Programming Languages-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Formal Languages and Automata Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Logic in Computer Science-662E9B">
  <p><b>Published on:</b> 2026-03-27T09:39:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Krishnendu Chatterjee, Ehsan Kafshdar Goharshady, Đorđe Žikelić</p>
    <p><b>Summary:</b> Differential privacy (DP) has established itself as one of the standards for ensuring privacy of individual data. However, reasoning about DP is a challenging and error-prone task, hence methods for formal verification and refutation of DP properties have received significant interest in recent years. In this work, we present a novel method for automated formal refutation of $ε$-DP. Our method refutes $ε$-DP by searching for a pair of inputs together with a non-negative function over outputs whose expected value on these two inputs differs by a significant amount. The two inputs and the non-negative function over outputs are computed simultaneously, by utilizing upper expectation supermartingales and lower expectation submartingales from probabilistic program analysis, which we leverage to introduce a sound and complete proof rule for $ε$-DP refutation. To the best of our knowledge, our method is the first method for $ε$-DP refutation to offer the following four desirable features: (1)~it is fully automated, (2)~it is applicable to stochastic mechanisms with sampling instructions from both discrete and continuous distributions, (3)~it provides soundness guarantees, and (4)~it provides semi-completeness guarantees. Our experiments show that our prototype tool SuperDP achieves superior performance compared to the state of the art and manages to refute $ε$-DP for a number of challenging examples collected from the literature, including ones that were out of the reach of prior methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.26074v1">Not All Entities are Created Equal: A Dynamic Anonymization Framework for Privacy-Preserving Retrieval-Augmented Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-27T05:03:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xinyuan Zhu, Zekun Fei, Enye Wang, Ruiqi He, Zheli Liu</p>
    <p><b>Summary:</b> Retrieval-Augmented Generation (RAG) enhances the utility of Large Language Models (LLMs) by retrieving external documents. Since the knowledge databases in RAG are predominantly utilized via cloud services, private data in sensitive domains such as finance and healthcare faces the risk of personal information leakage. Thus, effectively anonymizing knowledge bases is crucial for privacy preservation. Existing studies equate the privacy risk of text to the linear superposition of the privacy risks of individual, isolated sensitive entities. The "one-size-fits-all" full processing of all sensitive entities severely degrades utility of LLM. To address this issue, we introduce a dynamic anonymization framework named TRIP-RAG. Based on context-aware entity quantification, this framework evaluates entities from the perspectives of marginal privacy risk, knowledge divergence, and topical relevance. It identifies highly sensitive entities while trading off utility, providing a feasible approach for variable-intensity privacy protection scenarios. Our theoretical analysis and experiments indicate that TRIP-RAG can effectively reduce context inference risks. Extensive experimental results demonstrate that, while maintaining privacy protection comparable to full anonymization, TRIP-RAG's Recall@k decreases by less than 35% compared to the original data, and the generation quality improves by up to 56% over existing baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.26032v1">Protecting User Prompts Via Character-Level Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-27T03:02:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shashie Dilhara Batan Arachchige, Hassan Jameel Asghar, Benjamin Zi Hao Zhao, Dinusha Vatsalan, Dali Kaafar</p>
    <p><b>Summary:</b> Large Language Models (LLMs) generate responses based on user prompts. Often, these prompts may contain highly sensitive information, including personally identifiable information (PII), which could be exposed to third parties hosting these models. In this work, we propose a new method to sanitize user prompts. Our mechanism uses the randomized response mechanism of differential privacy to randomly and independently perturb each character in a word. The perturbed text is then sent to a remote LLM, which first performs a prompt restoration and subsequently performs the intended downstream task. The idea is that the restoration will be able to reconstruct non-sensitive words even when they are perturbed due to cues from the context, as well as the fact that these words are often very common. On the other hand, perturbation would make reconstruction of sensitive words difficult because they are rare. We experimentally validate our method on two datasets, i2b2/UTHealth and Enron, using two LLMs: Llama-3.1 8B Instruct and GPT-4o mini. We also compare our approach with a word-level differentially private mechanism, and with a rule-based PII redaction baseline, using a unified privacy-utility evaluation. Our results show that sensitive PII tagged in these datasets are reconstructed at a rate close to the theoretical rate of reconstructing completely random words, whereas non-sensitive words are reconstructed at a much higher rate. Our method has the advantage that it can be applied without explicitly identifying sensitive pieces of information in the prompt, while showing a good privacy-utility tradeoff for downstream tasks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.25190v2">zk-X509: Privacy-Preserving On-Chain Identity from Legacy PKI via Zero-Knowledge Proofs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-03-26T08:55:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yeongju Bak</p>
    <p><b>Summary:</b> Public blockchains impose an inherent tension between regulatory compliance and user privacy. Existing on-chain identity solutions require centralized KYC attestors, specialized hardware, or Decentralized Identifier (DID) frameworks needing entirely new credential infrastructure. Meanwhile, over four billion active X.509 certificates constitute a globally deployed, government-grade trust infrastructure largely unexploited for decentralized identity.
  This paper presents zk-X509, a privacy-preserving identity system bridging legacy Public Key Infrastructure (PKI) with public ledgers via a RISC-V zero-knowledge virtual machine (zkVM). Users prove ownership of standard X.509 certificates without revealing private keys or personal identifiers. Crucially, the private key never enters the ZK circuit; ownership is proven via OS keychain signature delegation (macOS Security.framework, Windows CNG). The circuit verifies certificate chain validity, temporal validity, key ownership, trustless CRL revocation, blockchain address binding, and Sybil-resistant nullifier generation. It commits 13 public values, including a Certificate Authority (CA) Merkle root hiding the issuing CA, and four selective disclosure hashes.
  We formalize eight security properties under a Dolev-Yao adversary with game-based definitions and reductions to sEUF-CMA, SHA-256 collision resistance, and ZK soundness. Evaluated on the SP1 zkVM, the system achieves 11.8M cycles for ECDSA P-256 (17.4M for RSA-2048), with on-chain Groth16 verification costing ~300K gas. By leveraging certificates deployed at scale across jurisdictions, zk-X509 enables adoption without new trust establishment, complementing emerging DID-based systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.25186v1">Knowledge-Guided Retrieval-Augmented Generation for Zero-Shot Psychiatric Data: Privacy Preserving Synthetic Data Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-03-26T08:52:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Adam Jakobsen, Sushant Gautam, Hugo Lewi Hammer, Susanne Olofsdotter, Miriam S Johanson, Pål Halvorsen, Vajira Thambawita</p>
    <p><b>Summary:</b> AI systems in healthcare research have shown potential to increase patient throughput and assist clinicians, yet progress is constrained by limited access to real patient data. To address this issue, we present a zero-shot, knowledge-guided framework for psychiatric tabular data in which large language models (LLMs) are steered via Retrieval-Augmented Generation using the Diagnostic and Statistical Manual of Mental Disorders (DSM-5) and the International Classification of Diseases (ICD-10). We conducted experiments using different combinations of knowledge bases to generate privacy-preserving synthetic data. The resulting models were benchmarked against two state-of-the-art deep learning models for synthetic tabular data generation, namely CTGAN and TVAE, both of which rely on real data and therefore entail potential privacy risks. Evaluation was performed on six anxiety-related disorders: specific phobia, social anxiety disorder, agoraphobia, generalized anxiety disorder, separation anxiety disorder, and panic disorder. CTGAN typically achieves the best marginals and multivariate structure, while the knowledge-augmented LLM is competitive on pairwise structure and attains the lowest pairwise error in separation anxiety and social anxiety. An ablation study shows that clinical retrieval reliably improves univariate and pairwise fidelity over a no-retrieval LLM. Privacy analyses indicate that the real data-free LLM yields modest overlaps and a low average linkage risk comparable to CTGAN, whereas TVAE exhibits extensive duplication despite a low k-map score. Overall, grounding an LLM in clinical knowledge enables high-quality, privacy-preserving synthetic psychiatric data when real datasets are unavailable or cannot be shared.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.24735v1">Examining the Effect of Explanations of AI Privacy Redaction in AI-mediated Interactions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-03-25T18:59:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Roshni Kaushik, Maarten Sap, Koichi Onoue</p>
    <p><b>Summary:</b> AI-mediated communication is increasingly being utilized to help facilitate interactions; however, in privacy sensitive domains, an AI mediator has the additional challenge of considering how to preserve privacy. In these contexts, a mediator may redact or withhold information, raising questions about how users perceive these interventions and whether explanations of system behavior can improve trust. In this work, we investigate how explanations of redaction operations can affect user trust in AI-mediated communication. We devise a scenario where a validated system removes sensitive content from messages and generates explanations of varying detail to communicate its decisions to recipients. We then conduct a user study with $180$ participants that studies how user trust and preferences vary for cases with different amounts of redacted content and different levels of explanation detail. Our results show that participants believed our system was more effective at preserving privacy when explanations were provided ($p<0.05$, Cohen's $d \approx 0.3$). We also found that contextual factors had an impact; participants relied more on explanations and found them more helpful when the system performed extensive redactions ($p<0.05$, Cohen's $f \approx 0.2$). We also found that explanation preferences depended on individual differences as well, and factors such as age and baseline familiarity with AI affected user trust in our system. These findings highlight the importance and challenge of balancing transparency and privacy in AI-mediated communications and suggest that adaptive, context-aware explanations are essential for designing privacy-aware, trustworthy AI systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.24695v1">Amplified Patch-Level Differential Privacy for Free via Random Cropping</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-03-25T18:15:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kaan Durmaz, Jan Schuchardt, Sebastian Schmidt, Stephan Günnemann</p>
    <p><b>Summary:</b> Random cropping is one of the most common data augmentation techniques in computer vision, yet the role of its inherent randomness in training differentially private machine learning models has thus far gone unexplored. We observe that when sensitive content in an image is spatially localized, such as a face or license plate, random cropping can probabilistically exclude that content from the model's input. This introduces a third source of stochasticity in differentially private training with stochastic gradient descent, in addition to gradient noise and minibatch sampling. This additional randomness amplifies differential privacy without requiring changes to model architecture or training procedure. We formalize this effect by introducing a patch-level neighboring relation for vision data and deriving tight privacy bounds for differentially private stochastic gradient descent (DP-SGD) when combined with random cropping. Our analysis quantifies the patch inclusion probability and shows how it composes with minibatch sampling to yield a lower effective sampling rate. Empirically, we validate that patch-level amplification improves the privacy-utility trade-off across multiple segmentation architectures and datasets. Our results demonstrate that aligning privacy accounting with domain structure and additional existing sources of randomness can yield stronger guarantees at no additional cost.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.24392v1">Federated fairness-aware classification under differential privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2026-03-25T15:09:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gengyu Xue, Yi Yu</p>
    <p><b>Summary:</b> Privacy and algorithmic fairness have become two central issues in modern machine learning. Although each has separately emerged as a rapidly growing research area, their joint effect remains comparatively under-explored. In this paper, we systematically study the joint impact of differential privacy and fairness on classification in a federated setting, where data are distributed across multiple servers. Targeting demographic disparity constrained classification under federated differential privacy, we propose a two-step algorithm, namely FDP-Fair. In the special case where there is only one server, we further propose a simple yet powerful algorithm, namely CDP-Fair, serving as a computationally-lightweight alternative. Under mild structural assumptions, theoretical guarantees on privacy, fairness and excess risk control are established. In particular, we disentangle the source of the private fairness-aware excess risk into a) intrinsic cost of classification, b) cost of private classification, c) non-private cost of fairness and d) private cost of fairness. Our theoretical findings are complemented by extensive numerical experiments on both synthetic and real datasets, highlighting the practicality of our designed algorithms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.23935v1">An Empirical Analysis of Google Play Data Safety Disclosures: A Consistency Study of Privacy Indicators in Mobile Gaming Apps</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-25T04:50:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bakheet Aljedaani</p>
    <p><b>Summary:</b> The Google Play marketplace has introduced the Data Safety section to improve transparency regarding how mobile applications (apps) collect, share, and protect user data. This mechanism requires developers to disclose privacy and security-related practices. However, the reliability of these disclosures remains dependent on developer self-reporting, raising concerns about their accuracy. This study investigates the consistency between developer-reported Data Safety disclosures and observable privacy indicators extracted from Android Application Packages (APKs). An empirical analysis was conducted on a dataset of 41 mobile gaming apps. A static analysis approach was used to extract key privacy indicators from APK files, including device IDs, data sharing, personal information access, and location access. These indicators were systematically compared with the corresponding disclosures reported in the Google Play Data Safety labels using a structured consistency evaluation framework. The results revealed varying levels of agreement across privacy categories. Device ID disclosures demonstrated relatively high consistency (87.8%), whereas other indicators exhibited substantial mismatches. Location-related disclosures showed the highest inconsistency rate (56.1%), followed by personal information and data sharing. Comparative analysis between children-oriented and general-audience apps revealed similar mismatch patterns. Also, Chi-square statistical tests indicate that these differences are not statistically significant, suggesting that disclosure inconsistencies are not associated with app category but instead reflect broader ecosystem-level challenges. These findings highlight limitations in the reliability of current marketplace transparency mechanisms and emphasize the need for improved validation and verification approaches to ensure accurate privacy reporting in mobile app ecosystems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.23678v1">PLACID: Privacy-preserving Large language models for Acronym Clinical Inference and Disambiguation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-03-24T19:33:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Manjushree B. Aithal, Ph. D., Alexander Kotz, James Mitchell, Ph. D</p>
    <p><b>Summary:</b> Large Language Models (LLMs) offer transformative solutions across many domains, but healthcare integration is hindered by strict data privacy constraints. Clinical narratives are dense with ambiguous acronyms, misinterpretation these abbreviations can precipitate severe outcomes like life-threatening medication errors. While cloud-dependent LLMs excel at Acronym Disambiguation, transmitting Protected Health Information to external servers violates privacy frameworks. To bridge this gap, this study pioneers the evaluation of small-parameter models deployed entirely on-device to ensure privacy preservation. We introduce a privacy-preserving cascaded pipeline leveraging general-purpose local models to detect clinical acronyms, routing them to domain-specific biomedical models for context-relevant expansions. Results reveal that while general instruction-following models achieve high detection accuracy (~0.988), their expansion capabilities plummet (~0.655). Our cascaded approach utilizes domain-specific medical models to increase expansion accuracy to (~0.81). This novel work demonstrates that privacy-preserving, on-device (2B-10B) models deliver high-fidelity clinical acronym disambiguation support.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.23221v1">PRETTINESS -- Privacy pResErving aTTrIbute maNagEment SyStem</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-24T13:59:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jelizaveta Vakarjuk, Alisa Pankova</p>
    <p><b>Summary:</b> European Digital Identity (EUDI) Wallet aims to provide end users with a way to get attested credentials from issuers, and present them to different relying parties. An important property mentioned in the regulatory frameworks is the possibility to revoke a previously issued credential. While it is possible to issue a short-lived credential, in some cases it may be inconvenient, and a separate revocation service which allows to revoke a credential at any time may be necessary. In this work, we propose a full end-to-end description of a generic credential revocation system, which technically relies on a single server and secure transmission channels between parties. We prove security of the proposed revocation functionality in the universal composability model, and estimate its efficiency based on a proof-of-concept implementation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.23197v1">Privacy-Aware Smart Cameras: View Coverage via Socially Responsible Coordination</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B"> 
  <p><b>Published on:</b> 2026-03-24T13:43:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chuhao Qin, Lukas Esterle, Evangelos Pournaras</p>
    <p><b>Summary:</b> Coordination of view coverage via privacy-aware smart cameras is key to a more socially responsible urban intelligence. Rather than maximizing view coverage at any cost or over relying on expensive cryptographic techniques, we address how cameras can coordinate to legitimately monitor public spaces while excluding privacy-sensitive regions by design. This article proposes a decentralized framework in which interactive smart cameras coordinate to autonomously select their orientation via collective learning, while eliminating privacy violations via soft and hard constraint satisfaction. The approach scales to hundreds up to thousands of cameras without any centralized control. Experimental evidence shows 18.42% higher coverage efficiency and 85.53% lower privacy violation than baselines and other state-of-the-art approaches. This significant advance further unravels practical guidelines for operators and policymakers: how the field of view, spatial placement, and budget of cameras operating by ethically-aligned artificial intelligence jointly influence coverage efficiency and privacy protection in large-scale and sensitive urban environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.22987v1">A Critical Review on the Effectiveness and Privacy Threats of Membership Inference Attacks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-03-24T09:23:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Najeeb Jebreel, David Sánchez, Josep Domingo-Ferrer</p>
    <p><b>Summary:</b> Membership inference attacks (MIAs) aim to determine whether a data sample was included in a machine learning (ML) model's training set and have become the de facto standard for measuring privacy leakages in ML. We propose an evaluation framework that defines the conditions under which MIAs constitute a genuine privacy threat, and review representative MIAs against it. We find that, under the realistic conditions defined in our framework, MIAs represent weak privacy threats. Thus, relying on them as a privacy metric in ML can lead to an overestimation of risk and to unnecessary sacrifices in model utility as a consequence of employing too strong defenses.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.22968v1">Beyond Theoretical Bounds: Empirical Privacy Loss Calibration for Text Rewriting Under Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-03-24T09:05:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Weijun Li, Arnaud Grivet Sébert, Qiongkai Xu, Annabelle McIver, Mark Dras</p>
    <p><b>Summary:</b> The growing use of large language models has increased interest in sharing textual data in a privacy-preserving manner. One prominent line of work addresses this challenge through text rewriting under Local Differential Privacy (LDP), where input texts are locally obfuscated before release with formal privacy guarantees. These guarantees are typically expressed by a parameter $\varepsilon$ that upper bounds the worst-case privacy loss. However, nominal $\varepsilon$ values are often difficult to interpret and compare across mechanisms. In this work, we investigate how to empirically calibrate across text rewriting mechanisms under LDP. We propose TeDA, which formulates calibration via a hypothesis-testing framework that instantiates text distinguishability audits in both surface and embedding spaces, enabling empirical assessment of indistinguishability from privatized texts. Applying this calibration to several representative mechanisms, we demonstrate that similar nominal $\varepsilon$ bounds can imply very different levels of distinguishability. Empirical calibration thus provides a more comparable footing for evaluating privacy-utility trade-offs, as well as a practical tool for mechanism comparison and analysis in real-world LDP text rewriting deployments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.22954v1">Privacy-Preserving EHR Data Transformation via Geometric Operators: A Human-AI Co-Design Technical Report</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-03-24T08:49:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maolin Wang, Beining Bao, Gan Yuan, Hongyu Chen, Bingkun Zhao, Baoshuo Kan, Jiming Xu, Qi Shi, Yinggong Zhao, Yao Wang, Wei Ying Ma, Jun Yan</p>
    <p><b>Summary:</b> Electronic health records (EHRs) and other real-world clinical data are essential for clinical research, medical artificial intelligence, and life science, but their sharing is severely limited by privacy, governance, and interoperability constraints. These barriers create persistent data silos that hinder multi-center studies, large-scale model development, and broader biomedical discovery. Existing privacy-preserving approaches, including multi-party computation and related cryptographic techniques, provide strong protection but often introduce substantial computational overhead, reducing the efficiency of large-scale machine learning and foundation-model training. In addition, many such methods make data usable for restricted computation while leaving them effectively invisible to clinicians and researchers, limiting their value in workflows that still require direct inspection, exploratory analysis, and human interpretation. We propose a real-world-data transformation framework for privacy-preserving sharing of structured clinical records. Instead of converting data into opaque representations, our approach constructs transformed numeric views that preserve medical semantics and major statistical properties while, under a clearly specified threat model, provably breaking direct linkage between those views and protected patient-level attributes. Through collaboration between computer scientists and the AI agent \textbf{SciencePal}, acting as a constrained tool inventor under human guidance, we design three transformation operators that are non-reversible within this threat model, together with an additional mixing strategy for high-risk scenarios, supported by theoretical analysis and empirical evaluation under reconstruction, record linkage, membership inference, and attribute inference attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.22808v4">Combinatorial Privacy: Private Multi-Party Bitstream Grand Sum by Hiding in Birkhoff Polytopes</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-03-24T05:08:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Praneeth Vepakomma</p>
    <p><b>Summary:</b> We introduce PolyVeil, a protocol for private Boolean summation across $k$ clients that encodes private bits as permutation matrices in the Birkhoff polytope. A two-layer architecture gives the server perfect simulation-based security (statistical distance zero) while a separate aggregator faces \#P-hard likelihood inference via the permanent and mixed discriminant. Two variants (full and compressed) differ in what the aggregator observes.
  We develop a finite-sample $(\varepsilon,δ)$-DP analysis with explicit constants. In the full variant, where the aggregator sees a doubly stochastic matrix per client, the log-Lipschitz constant grows as $n^4 K_t$ and a signal-to-noise analysis shows the DP guarantee is non-vacuous only when the private signal is undetectable. In the compressed variant, where the aggregator sees a single scalar, the univariate density ratio yields non-vacuous $\varepsilon$ at moderate SNR, with the optimal decoy count balancing CLT accuracy against noise concentration.
  This exposes a fundamental tension. \#P-hardness requires the full matrix view (Birkhoff structure visible), while non-vacuous DP requires the scalar view (low dimensionality). Whether both hold simultaneously in one variant remains open. The protocol needs no PKI, has $O(k)$ communication, and outputs exact aggregates.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.22751v2">Observable Channels, Not Just Storage: Evaluating Privacy Leakage in LLM Agent Pipelines</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-24T03:29:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tao Huang, Chen Hou, Guosen Wu, Jiayang Meng</p>
    <p><b>Summary:</b> Privacy leakage in LLM agents is often studied through individual storage or execution components, such as memory modules, retrieval pipelines, or tool-mediated artifacts. However, these settings are typically analyzed in isolation, making it difficult to compare how private internal dependence becomes externally recoverable across heterogeneous agent pipelines. In this paper, we present CIPL (Channel Inversion for Privacy Leakage) as a unified channel-oriented measurement interface for evaluating privacy leakage in LLM agent pipelines. Rather than claiming a universally strongest attack recipe, CIPL provides a shared way to represent a target through its sensitive source, selection, assembly, execution, observation, and extraction stages, and to measure how internal exposure is transformed into attacker-recoverable leakage under a common protocol. Using memory-based, retrieval-mediated, and tool-mediated instantiations under this shared interface, we identify a distinct cross-target risk picture. Memory behaves as a near-saturated high-risk special case, while beyond-memory leakage exhibits a different regime: retrieval-mediated targets show frequent but often incomplete leakage, and tool-mediated targets are strongly shaped by the exposed observation surface and provider behavior. We further show that leakage is governed by channel conditions rather than by a universally dominant recipe: cleaned weak controls sharply suppress leakage, and semantic annotation reveals attacker-useful leakage beyond exact-match extraction. Together, these findings suggest that privacy risk in LLM agent pipelines is better understood through \emph{observable channels}, not just storage components. More broadly, our results motivate channel-oriented privacy evaluation as a necessary complement to component-local or exact-only analyses.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.22563v1">Privacy-Preserving Reinforcement Learning from Human Feedback via Decoupled Reward Modeling</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-03-23T20:45:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Young Hyun Cho, Will Wei Sun</p>
    <p><b>Summary:</b> Preference-based fine-tuning has become an important component in training large language models, and the data used at this stage may contain sensitive user information. A central question is how to design a differentially private pipeline that is well suited to the distinct structure of reinforcement learning from human feedback. We propose a privacy-preserving framework that imposes differential privacy only on reward learning and derives the final policy from the resulting private reward model. Theoretically, we study the suboptimality gap and show that privacy contributes an additional additive term beyond the usual non-private statistical error. We also establish a minimax lower bound and show that the dominant term changes with sample size and privacy level, which in turn characterizes regimes in which the upper bound is rate-optimal up to logarithmic factors. Empirically, synthetic experiments confirm the scaling predicted by the theory, and experiments on the Anthropic HH-RLHF dataset using the Gemma-2B-IT model show stronger private alignment performance than existing differentially private baseline methods across privacy budgets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.21804v1">Privacy-Preserving Formation Control for Networked Underactuated USVs: A Passivity-Based Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E">
  <p><b>Published on:</b> 2026-03-23T10:47:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jingyi Zhao, Wenxuan Wang, Weijun Zhou, Yongxin Wu, Yuhu Wu, Yann Le Gorrec</p>
    <p><b>Summary:</b> This paper studies coordinated trajectory planning and tracking control for multiple unmanned surface vessels (USVs) under strict privacy requirements. To avoid the privacy risks associated with direct position sharing in conventional cooperative methods, the proposed approach adopts an estimated fleet centroid as the only shared variable, preventing individual trajectory disclosure while enabling coordination. Based on this interaction mechanism, a formation-oriented trajectory is generated for the fleet. The collective dynamics are modeled using Port-Hamiltonian systems, and a passivity-based tracking controller is designed for each USV to accurately follow the planned trajectories. The stability of the closed-loop system is rigorously proven, and experiments on a real USV platform confirm effective formation tracking and privacy preservation. The proposed result extends and validates through experimental results the approach in [26] that was limited to idealized pointmass models and lacked a feedback control.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.26745v1">Motion Semantics Guided Normalizing Flow for Privacy-Preserving Video Anomaly Detection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-03-23T08:45:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yang Liu, Boan Chen, Yuanyuan Meng, Jing Liu, Zhengliang Guo, Wei Zhou, Peng Sun, Hong Chen</p>
    <p><b>Summary:</b> As embodied perception systems increasingly bridge digital and physical realms in interactive multimedia applications, the need for privacy-preserving approaches to understand human activities in physical environments has become paramount. Video anomaly detection is a critical task in such embodied multimedia systems for intelligent surveillance and forensic analysis. Skeleton-based approaches have emerged as a privacy-preserving alternative that processes physical world information through abstract human pose representations while discarding sensitive visual attributes such as identity and facial features. However, existing skeleton-based methods predominantly model continuous motion trajectories in a monolithic manner, failing to capture the hierarchical nature of human activities composed of discrete semantic primitives and fine-grained kinematic details, which leads to reduced discriminability when anomalies manifest at different abstraction levels. In this regard, we propose Motion Semantics Guided Normalizing Flow (MSG-Flow) that decomposes skeleton-based VAD into hierarchical motion semantics modeling. It employs vector quantized variational auto-encoder to discretize continuous motion into interpretable primitives, an autoregressive Transformer to model semantic-level temporal dependencies, and a conditional normalizing flow to capture detail-level pose variations. Extensive experiments on benchmarks (HR-ShanghaiTech & HR-UBnormal) demonstrate that MSG-Flow achieves state-of-the-art performance with 88.1% and 75.8% AUC respectively.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.21656v1">TrustFed: Enabling Trustworthy Medical AI under Data Privacy Constraints</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-03-23T07:34:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vagish Kumar, Syed Bahauddin Alam, Souvik Chakraborty</p>
    <p><b>Summary:</b> Protecting patient privacy remains a fundamental barrier to scaling machine learning across healthcare institutions, where centralizing sensitive data is often infeasible due to ethical, legal, and regulatory constraints. Federated learning offers a promising alternative by enabling privacy-preserving, multi-institutional training without sharing raw patient data; however, real-world deployments face severe challenges from data heterogeneity, site-specific biases, and class imbalance, which degrade predictive reliability and render existing uncertainty quantification methods ineffective. Here, we present TrustFed, a federated uncertainty quantification framework that provides distribution-free, finite-sample coverage guarantees under heterogeneous and imbalanced healthcare data, without requiring centralized access. TrustFed introduces a representation-aware client assignment mechanism that leverages internal model representations to enable effective calibration across institutions, along with a soft-nearest threshold aggregation strategy that mitigates assignment uncertainty while producing compact and reliable prediction sets. Using over 430,000 medical images across six clinically distinct imaging modalities, we conduct one of the most comprehensive evaluations of uncertainty-aware federated learning in medical imaging, demonstrating robust coverage guarantees across datasets with diverse class cardinalities and imbalance regimes. By validating TrustFed at this scale and breadth, our study advances uncertainty-aware federated learning from proof-of-concept toward clinically meaningful, modality-agnostic deployment, positioning statistically guaranteed uncertainty as a core requirement for next-generation healthcare AI systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.21640v1">Compressed Distributed Stochastic Nonconvex Optimization with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E">
  <p><b>Published on:</b> 2026-03-23T07:15:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Antai Xie, Xiaoqiang Ren, Xinlei Yi, Tao Yang, Xiaofan Wang</p>
    <p><b>Summary:</b> This paper studies distributed stochastic nonconvex optimization problems with compressed communication and differential privacy, in which each agent aims to minimize the sum of all agents' cost functions by using local compressed information exchange. To this end, we propose a compressed distributed stochastic gradient descent algorithm, which is robust under a general class of compression operators that allow both relative and absolute compression errors. We then show that the proposed algorithm finds the first-order stationary point for smooth nonconvex functions with the linear speedup convergence rate $\mathcal{O}(1/\sqrt{nT})$ and converges to the optimum if the global cost function additionally satisfies the Polyak--Łojasiewicz (P--Ł) condition with the convergence rate $\mathcal{O}(1/(nT^θ)),θ\in(0,1)$, where $T$ is the total number of iterations and $n$ is the number of agents. Furthermore, if the P--Ł~constant is known in advance, we show that the proposed algorithm achieves a convergence rate $\mathcal{O}(1/(nT))$. Finally, we show that the proposed algorithm is able to achieve $(0,δ)$-differential privacy without sacrificing convergence accuracy. Numerical experiments are carried out to</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.21573v1">Rethinking Visual Privacy: A Compositional Privacy Risk Framework for Severity Assessment with VLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-03-23T04:48:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Efthymios Tsaprazlis, Tiantian Feng, Anil Ramakrishna, Sai Praneeth Karimireddy, Rahul Gupta, Shrikanth Narayanan</p>
    <p><b>Summary:</b> Existing visual privacy benchmarks largely treat privacy as a binary property, labeling images as private or non-private based on visible sensitive content. We argue that privacy is fundamentally compositional. Attributes that are benign in isolation may combine to produce severe privacy violations. We introduce the Compositional Privacy Risk Taxonomy (CPRT), a regulation-aware framework that organizes visual attributes according to standalone identifiability and compositional harm potential. CPRT defines four graded severity levels and is paired with an interpretable scoring function that assigns continuous privacy severity scores. We further construct a taxonomy-aligned dataset of 6.7K images and derive ground-truth compositional risk scores. By evaluating frontier and open-weight VLMs we find that frontier models align well with compositional severity when provided structured guidance, but systematically underestimate composition-driven risks. Smaller models struggle to internalize graded privacy reasoning. To bridge this gap, we introduce a deployable 8B supervised fine-tuned (SFT) model that closely matches frontier-level performance on compositional privacy assessment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.21387v2">Knowledge Priors for Identity-Disentangled Open-Set Privacy-Preserving Video FER</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-03-22T20:18:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Feng Xu, Xun Li, Lars Petersson, Yulei Sui, David Ahmedt-Aristizabal, Dadong Wang</p>
    <p><b>Summary:</b> Facial expression recognition relies on facial data that inherently expose identity and thus raise significant privacy concerns. Current privacy-preserving methods typically fail in realistic open-set video settings where identities are unknown, and identity labels are unavailable. We propose a two-stage framework for video-based privacy-preserving FER in challenging open-set settings that requires no identity labels at any stage. To decouple privacy and utility, we first train an identity-suppression network using intra- and inter-video knowledge priors derived from real-world videos without identity labels. This network anonymizes identity while preserving expressive cues. A subsequent denoising module restores expression-related information and helps recover FER performance. Furthermore, we introduce a falsification-based validation method that uses recognition priors to rigorously evaluate privacy robustness without requiring annotated identity labels. Experiments on three video datasets demonstrate that our method effectively protects privacy while maintaining FER accuracy comparable to identity-supervised baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.21305v1">Privacy-Preserving Federated Action Recognition via Differentially Private Selective Tuning and Efficient Communication</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-03-22T16:05:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Idris Zakariyya, Pai Chet Ng, Kaushik Bhargav Sivangi, S. Mohammad Sheikholeslami, Konstantinos N. Plataniotis, Fani Deligianni</p>
    <p><b>Summary:</b> Federated video action recognition enables collaborative model training without sharing raw video data, yet remains vulnerable to two key challenges: \textit{model exposure} and \textit{communication overhead}. Gradients exchanged between clients and the server can leak private motion patterns, while full-model synchronization of high-dimensional video networks causes significant bandwidth and communication costs. To address these issues, we propose \textit{Federated Differential Privacy with Selective Tuning and Efficient Communication for Action Recognition}, namely \textit{FedDP-STECAR}. Our \textit{FedDP-STECAR} framework selectively fine-tunes and perturbs only a small subset of task-relevant layers under Differential Privacy (DP), reducing the surface of information leakage while preserving temporal coherence in video features. By transmitting only the tuned layers during aggregation, communication traffic is reduced by over 99\% compared to full-model updates. Experiments on the UCF-101 dataset using the MViT-B-16x4 transformer show that \textit{FedDP-STECAR} achieves up to \textbf{70.2\% higher accuracy} under strict privacy ($ε=0.65$) in centralized settings and \textbf{48\% faster training} with \textbf{73.1\% accuracy} in federated setups, enabling scalable and privacy-preserving video action recognition. Code available at https://github.com/izakariyya/mvit-federated-videodp</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.21211v1">Security and Privacy in O-RAN for 6G: A Comprehensive Review of Threats and Mitigation Approaches</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-03-22T13:11:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lujia Liang, Lei Zhang</p>
    <p><b>Summary:</b> Open Radio Access Network (O-RAN) is a major advancement in the telecommunications field, providing standardized interfaces that promote interoperability between different vendors' technologies, thereby enhancing network flexibility and reducing operational expenses. By leveraging cutting-edge developments in network virtualization and artificial intelligence, O-RAN enhances operational efficiency and stimulates innovation within an open ecosystem. In the context of 6G, the potential capabilities of O-RAN have been significantly expanded, enabling ultra-reliable low-latency communication, terabit-level data rates, and seamless integration of terrestrial and non-terrestrial networks. Despite these benefits, its open architecture paradigm also brings critical security and privacy challenges, which, if not addressed, could compromise network integrity and data confidentiality. This paper conducts a comprehensive investigation into the security vulnerabilities and privacy issues associated with the O-RAN architecture in the context of the evolving 6G landscape, systematically categorizing fundamental vulnerabilities, meticulously examining potential attack vectors, and assessing current and future threats. In addition, this study also examines the existing and emerging security mechanisms of O-RAN and reviews the ongoing standardization activities aimed at strengthening the O-RAN security framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.21197v1">Anchored Likelihood-Ratio Geometry of Anonymous Shuffle Experiments: Exact Privacy Envelopes and Universal Low-Budget Design</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-03-22T12:34:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alex Shvets</p>
    <p><b>Summary:</b> We develop a geometric framework for anonymous shuffle experiments based on an anchored affine likelihood-ratio law: a mean-zero measure on the regular simplex polytope. Every finite-output d-ary channel corresponds, up to refinements, to a unique anchored law, and conversely. On privacy: among all epsilon_0-LDP channels, binary randomized response universally extremizes all convex f-divergences and hockey-stick profiles after shuffling. A rigidity converse shows that saturation of both directed envelopes at finite n forces the binary endpoint law. On design: under the pairwise chi_* budget, we prove exact trace-cap and two-orbit frontier theorems. Every frontier point is realized by a mixture of at most two orbit laws. In the low-budget regime, augmented randomized response is minimax-optimal to the sharp constant over all channels and estimators. Under the raw LDP cap, the problem reduces to subset-selection with explicit optimal subset size. The arguments are self-contained and independent of the author's trilogy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.21106v2">Tracing Users' Privacy Concerns Across the Lifecycle of a Romantic AI Companion</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-03-22T07:49:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kazi Ababil Azam, Imtiaz Karim, Dipto Das</p>
    <p><b>Summary:</b> Romantic AI chatbots have quickly attracted users, but their emotional use raises concerns about privacy and safety. As people turn to these systems for intimacy, comfort, and emotionally significant interaction, they often disclose highly sensitive information. Yet the privacy implications of such disclosure remain poorly understood in platforms shaped by persistence, intimacy, and opaque data practices. In this paper, we examine public Reddit discussions about privacy in romantic AI chatbot ecosystems through a lifecycle lens. Analyzing 2,909 posts from 79 subreddits collected over one year, we identify four recurring patterns: disproportionate entry requirements, intensified sensitivity in intimate use, interpretive uncertainty and perceived surveillance, and irreversibility, persistence, and user burden. We show that privacy in romantic AI is best understood as an evolving socio-technical governance problem spanning access, disclosure, interpretation, retention, and exit. These findings highlight the need for privacy and safety governance in romantic AI that is staged across the lifecycle of use, supports meaningful reversibility, and accounts for the emotional vulnerability of intimate human-AI interaction.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.20968v1">Composition Theorems for Multiple Differential Privacy Constraints</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">
  <p><b>Published on:</b> 2026-03-21T22:39:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Cemre Cadir, Salim Najib, Yanina Y. Shkel</p>
    <p><b>Summary:</b> The exact composition of mechanisms for which two differential privacy (DP) constraints hold simultaneously is studied. The resulting privacy region admits an exact representation as a mixture over compositions of mechanisms of heterogeneous DP guarantees, yielding a framework that naturally generalizes to the composition of mechanisms for which any number of DP constraints hold. This result is shown through a structural lemma for mixtures of binary hypothesis tests. Lastly, the developed methodology is applied to approximate $f$-DP composition.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.20107v1">Sharing The Secret: Distributed Privacy-Preserving Monitoring</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Formal Languages and Automata Theory-D91E36">
  <p><b>Published on:</b> 2026-03-20T16:30:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mahyar Karimi, K. S. Thejaswini, Roderick Bloem, Thomas A. Henzinger</p>
    <p><b>Summary:</b> In traditional runtime verification, a system is typically observed by a monolithic monitor. Enforcing privacy in such settings is computationally expensive, as it necessitates heavy cryptographic primitives. Therefore, privacy-preserving monitoring remains impractical for real-time applications. In this work, we address this scalability challenge by distributing the monitor across multiple parties -- at least one of which is honest. This architecture enables the use of efficient secret-sharing schemes instead of computationally intensive cryptography, dramatically reducing over-head while maintaining strong privacy guarantees. While existing secret-sharing approaches are typically limited to one-shot executions which do not maintain an internal state, we introduce a protocol tailored for continuous monitoring that supports repeated evaluations over an evolving internal state (kept secret from the system and the monitoring entities). We implement our approach using the MP-SPDZ framework. Our experiments demonstrate that, under these architectural assumptions, our protocol is significantly more scalable than existing alternatives.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.19791v1">Text-Based Personas for Simulating User Privacy Decisions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-20T09:28:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kassem Fawaz, Ren Yi, Octavian Suciu, Rishabh Khandelwal, Hamza Harkous, Nina Taft, Marco Gruteser</p>
    <p><b>Summary:</b> The ability to simulate human privacy decisions has significant implications for aligning autonomous agents with individual intent and conducting cost-effective, large-scale privacy-centric user studies. Prior approaches prompt Large Language Models (LLMs) with natural language user statements, data-sharing histories, or demographic attributes to simulate privacy decisions. These approaches, however, fail to balance individual-level accuracy, prompt usability, token efficiency, and population-level representation. We present Narriva, an approach that generates text-based synthetic privacy personas to address these shortcomings. Narriva grounds persona generation in prior user privacy decisions, such as those from large-scale survey datasets, rather than purely relying on demographic stereotypes. It compresses this data into concise, human-readable summaries structured by established privacy theories. Through benchmarking across five diverse datasets, we analyze the characteristics of Narriva's synthetic personas in modeling both individual and population-level privacy preferences. We find that grounding personas in past privacy behaviors achieves up to 88% predictive accuracy (significantly outperforming a non-personalized LLM baseline), and yields an 80-95% reduction in prompt tokens compared to in-context learning with raw examples. Finally, we demonstrate that personas synthesized from a single survey can reproduce the aggregate privacy behaviors and statistical distributions (TVComplement up to 0.85) of entirely different studies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.19703v1">Minimax and Adaptive Covariance Matrix Estimation under Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-03-20T07:13:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> T. Tony Cai, Yicheng Li</p>
    <p><b>Summary:</b> The covariance matrix plays a fundamental role in the analysis of high-dimensional data. This paper studies minimax and adaptive estimation of high-dimensional bandable covariance matrices under differential privacy constraints. We propose a novel differentially private blockwise tridiagonal estimator that achieves minimax-optimal convergence rates under both the operator norm and the Frobenius norm. In contrast to the non-private setting, the privacy-induced error exhibits a polynomial dependence on the ambient dimension, revealing a substantial additional cost of privacy.
  To establish optimality, we develop a new differentially private van Trees inequality and construct carefully designed prior distributions to obtain matching minimax lower bounds. The proposed private van Trees inequality applies more broadly to general private estimation problems and is of independent interest. We further introduce an adaptive estimator that attains the optimal rate up to a logarithmic factor without prior knowledge of the decay parameter, based on a novel hierarchical tridiagonal approach. Numerical experiments corroborate the theoretical results and illustrate the fundamental privacy-accuracy trade-off.</p>
  </details>
</div>



<h2>2026-04</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.09518v1">Demonstrably Informed Consent in Privacy Policy Flows: Evidence from a Randomized Experiment</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-04-10T17:39:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qian Ma, Aditya Majumdar, Sarah Rajtmajer, Brett Frischmann</p>
    <p><b>Summary:</b> Privacy policies govern how personal data is collected, used, and shared. Yet, in most privacy-policy consent flows, agreement is operationalized as a single click at the end of a long, opaque policy document. Recent privacy-law scholarship has argued for a standard of demonstrably informed consent. That is, the party drafting and designing privacy-policy consent mechanisms must generate reliable evidence that a person demonstrates comprehension of the consequential terms to which they agree. To this end, we study pedagogical friction as a design framing: minimal interventions embedded within a privacy-policy consent flow that aim to support demonstrated comprehension while keeping burden on the user low. In a randomized experiment, we tested pedagogical friction for demonstrably informed consent in the context of a privacy policy for an edtech app for young children. We recruited 293 parents of kids ages 3-8 to review the app's privacy policy under one of six conditions that varied presentation format and pacing, then complete a six-question comprehension quiz. Three conditions offered a second policy review and quiz retake for participants who did not pass this quiz on their first attempt. We find that the slide-based condition (G3) achieved the highest first-attempt threshold attainment (>=80%) (41.7%), followed by the paced, sectioned condition (G4) (30.6%). In the retake conditions, 64.9% of participants who completed a second attempt improved their score. Notably, in conditions that did not gate consent on demonstrated comprehension, 97.3% of participants who scored below the threshold still chose to consent, suggesting that ungated consent flows can record agreement without demonstrated comprehension. Our results suggest that pedagogical friction can strengthen the evidentiary basis of consent and clarify what it costs in time and burden.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.08860v1">Optimal Privacy-Aware Co-Design of Quantizer and Controller in Networked Control Systems</a></h3>
  
  <p><b>Published on:</b> 2026-04-10T01:48:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chuanghong Weng, Ehsan Nekouei</p>
    <p><b>Summary:</b> This paper investigates the optimal privacy-aware networked control problem, in which the dynamical system affected by a private input process sends its measurement to a remote controller after stochastic quantization. An adversary seeks to infer private system inputs from quantization results and control outputs. The optimal privacy-aware quantizer and controller are obtained by solving a stochastic control problem with mutual information regularization, where the mutual information measures the privacy leakage through the quantizer and controller. We first derive the coupled Bellman equations for the optimal quantizer and controller using the dynamic programming decomposition method. We then analyze the structural properties of the solution, showing that the optimal controller is deterministic, while the optimal quantizer regulates the adversary's belief in a closed-loop manner to enhance privacy. To enable numerical optimization, the quantizer and controller are jointly parameterized and then updated via policy gradient methods, and a binary classification approach is used to approximate privacy leakage. Finally, we validate the effectiveness of the proposed approach through numerical experiments on a building control system.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.08743v1">Balancing Functionality and GDPR-Driven Privacy in ISAC Trajectory Sharing</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-04-09T20:11:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zexin Fang, Bin Han, Zhuojun Tian, Hans D. Schotten</p>
    <p><b>Summary:</b> Integrated Sensing and Communications (ISAC) enables trajectory sharing that enhances beamforming, resource allocation, and cooperative perception, yet raises fundamental privacy concerns under the General Data Protection Regulation (GDPR) data minimisation principle. This paper proposes a Fisher Information Density (FID)-constrained trajectory sharing framework that enforces a local lower bound on estimation uncertainty, providing hard, quantifiable privacy guarantees by construction. Unlike fixed-noise approaches, the proposed method bounds the Privacy Leak Ratio (PLR) regardless of sensing power or adversarial post-processing, ensuring that no trajectory segment can be reconstructed beyond a prescribed accuracy threshold. Simulations on the OpenTraj dataset demonstrate that the framework keeps the average PLR below 20-25% and the maximum leakage segment duration under 2-2.5 s, while preserving data utility for downstream tasks such as movement prediction. The resulting criterion is interpretable, model-agnostic, and compatible with GDPR-compliant ISAC system design.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.08630v1">Realisation-Level Privacy Filtering</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-04-09T16:31:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sophie Taylor, Praneeth Vippathalla, Justin Coon</p>
    <p><b>Summary:</b> We study differentially private data release, where a database is accessed through successive, possibly adaptive queries and mechanisms. Existing composition theorems and privacy filters combine worst case per-round privacy parameters, leaving room for more refined accounting based on realised leakage, which we term realisation-level accounting. We propose a realisation-level filtering approach to determine stopping times for data releases, and design one such filter. Despite technical challenges arising from conditioning on realisations and stopping time, we prove that the filter guarantees $(ε, δ)$-differential privacy, with $ε$ and $δ$ chosen by the data handler. Through numerical evidence, we demonstrate that realisation-level filtering provides a path to better utility beyond mechanism-level methods. Furthermore, our proposed filter applies to arbitrary mechanisms, including those that are badly behaved under Rényi differential privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.08113v1">TADP-RME: A Trust-Adaptive Differential Privacy Framework for Enhancing Reliability of Data-Driven Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-04-09T11:32:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Labani Halder, Payel Sadhukhan, Sarbani Palit</p>
    <p><b>Summary:</b> Ensuring reliability in adversarial settings necessitates treating privacy as a foundational component of data-driven systems. While differential privacy and cryptographic protocols offer strong guarantees, existing schemes rely on a fixed privacy budget, leading to a rigid utility-privacy trade-off that fails under heterogeneous user trust. Moreover, noise-only differential privacy preserves geometric structure, which inference attacks exploit, causing privacy leakage.
  We propose TADP-RME (Trust-Adaptive Differential Privacy with Reverse Manifold Embedding), a framework that enhances reliability under varying levels of user trust. It introduces an inverse trust score in the range [0,1] to adaptively modulate the privacy budget, enabling smooth transitions between utility and privacy. Additionally, Reverse Manifold Embedding applies a nonlinear transformation to disrupt local geometric relationships while preserving formal differential privacy guarantees through post-processing.
  Theoretical and empirical results demonstrate improved privacy-utility trade-offs, reducing attack success rates by up to 3.1 percent without significant utility degradation. The framework consistently outperforms existing methods against inference attacks, providing a unified approach for reliable learning in adversarial environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.08037v1">PrivFedTalk: Privacy-Aware Federated Diffusion with Identity-Stable Adapters for Personalized Talking-Head Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-04-09T09:41:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Soumya Mazumdar, Vineet Kumar Rakesh, Tapas Samanta</p>
    <p><b>Summary:</b> Talking-head generation has advanced rapidly with diffusion-based generative models, but training usually depends on centralized face-video and speech datasets, raising major privacy concerns. The problem is more acute for personalized talking-head generation, where identity-specific data are highly sensitive and often cannot be pooled across users or devices. PrivFedTalk is presented as a privacy-aware federated framework for personalized talking-head generation that combines conditional latent diffusion with parameter-efficient identity adaptation. A shared diffusion backbone is trained across clients, while each client learns lightweight LoRA identity adapters from local private audio-visual data, avoiding raw data sharing and reducing communication cost. To address heterogeneous client distributions, Identity-Stable Federated Aggregation (ISFA) weights client updates using privacy-safe scalar reliability signals computed from on-device identity consistency and temporal stability estimates. Temporal-Denoising Consistency (TDC) regularization is introduced to reduce inter-frame drift, flicker, and identity drift during federated denoising. To limit update-side privacy risk, secure aggregation and client-level differential privacy are applied to adapter updates. The implementation supports both low-memory GPU execution and multi-GPU client-parallel training on heterogeneous shared hardware. Comparative experiments on the present setup across multiple training and aggregation conditions with PrivFedTalk, FedAvg, and FedProx show stable federated optimization and successful end-to-end training and evaluation under constrained resources. The results support the feasibility of privacy-aware personalized talking-head training in federated environments, while suggesting that stronger component-wise, privacy-utility, and qualitative claims need further standardized evaluation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.08019v1">xDup: Privacy-Preserving Deduplication for Humanitarian Organizations using Fuzzy PSI</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-09T09:18:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tim Rausch, Sylvain Chatel, Wouter Lueks</p>
    <p><b>Summary:</b> Humanitarian organizations help to ensure people's livelihoods in crisis situations. Typically, multiple organizations operate in the same region. To ensure that the limited budget of these organizations can help as many people as possible, organizations perform cross-organizational deduplication to detect duplicate registrations and ensure recipients receive aid from at most one organization. Current deduplication approaches risk privacy harm to vulnerable aid recipients by sharing their data with other organizations. We analyzed the needs of humanitarian organizations to identify the requirements for privacy-friendly cross-organizational deduplication fit for real-life humanitarian missions. We present xDup, a new practical deduplication system that meets the requirements of humanitarian organizations and is two orders of magnitude faster than current solutions. xDup builds on Fuzzy PSI, and we present otFPSI, a concretely efficient Fuzzy PSI protocol for Hamming Space without input assumptions. We show that it is more efficient than existing Fuzzy PSI protocols.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.07884v1">Reinforcement-Guided Synthetic Data Generation for Privacy-Sensitive Identity Recognition</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-04-09T06:52:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xuemei Jia, Jiawei Du, Hui Wei, Jun Chen, Joey Tianyi Zhou, Zheng Wang</p>
    <p><b>Summary:</b> High-fidelity generative models are increasingly needed in privacy-sensitive scenarios, where access to data is severely restricted due to regulatory and copyright constraints. This scarcity hampers model development--ironically, in settings where generative models are most needed to compensate for the lack of data. This creates a self-reinforcing challenge: limited data leads to poor generative models, which in turn fail to mitigate data scarcity. To break this cycle, we propose a reinforcement-guided synthetic data generation framework that adapts general-domain generative priors to privacy-sensitive identity recognition tasks. We first perform a cold-start adaptation to align a pretrained generator with the target domain, establishing semantic relevance and initial fidelity. Building on this foundation, we introduce a multi-objective reward that jointly optimizes semantic consistency, coverage diversity, and expression richness, guiding the generator to produce both realistic and task-effective samples. During downstream training, a dynamic sample selection mechanism further prioritizes high-utility synthetic samples, enabling adaptive data scaling and improved domain alignment. Extensive experiments on benchmark datasets demonstrate that our framework significantly improves both generation fidelity and classification accuracy, while also exhibiting strong generalization to novel categories in small-data regimes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.07839v1">A Hardware-Anchored Privacy Middleware for PII Sharing Across Heterogeneous Embedded Consumer Devices</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Operating Systems-04E762">
  <p><b>Published on:</b> 2026-04-09T05:40:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aditya Sabbineni, Pravin Nagare, Devendra Dahiphale, Preetam Dedu, Willison Lopes</p>
    <p><b>Summary:</b> The rapid expansion of the Internet of Things (IoT) and smart home ecosystems has led to a fragmented landscape of user data management across consumer electronics (CE) such as Smart TVs, gaming consoles, and set-top boxes. Current onboarding processes on these devices are characterized by high friction due to manual data entry and opaque data-sharing practices. This paper introduces the User Data Sharing System (UDSS), a platform-agnostic framework designed to facilitate secure, privacy-first PII (Personally Identifiable Information) exchange between device platforms and third-party applications. Our system implements a Contextual Scope Enforcement (CSE) mechanism that programmatically restricts data exposure based on user intent - specifically distinguishing between Sign-In and Sign-Up workflows. Unlike cloud-anchored identity standards such as FIDO2/WebAuthn, UDSS is designed for shared, device-centric CE environments where persistent user-to-device binding cannot be assumed. We further propose a tiered access model that balances developer needs with regulatory compliance (GDPR/CCPA). A proof-of-concept implementation on a reference ARMv8 Linux-based middleware demonstrates that UDSS reduces user onboarding latency by 65% and measurably reduces PII over-exposure risk through protocol-enforced data minimization. This framework provides a standardized approach to identity management in the heterogeneous CE market.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.07797v1">BRASP: Boolean Range Queries over Encrypted Spatial Data with Access and Search Pattern Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-09T04:50:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jing Zhang, Ganxuan Yang, Yifei Yang, Siqi Wen, Zhengyang Qiu</p>
    <p><b>Summary:</b> Searchable Encryption (SE) enables users to query outsourced encrypted data while preserving data confidentiality. However, most efficient schemes still leak the search pattern and access pattern, which may allow an honest-but-curious cloud server to infer query contents, user interests, or returned records from repeated searches and observed results. Existing pattern-hiding solutions mainly target keyword queries and do not naturally support Boolean range queries over encrypted spatial data. This paper presents BRASP, a searchable encryption scheme for Boolean range queries over encrypted spatial data. BRASP combines Hilbert-curve-based prefix encoding with encrypted prefix--ID and keyword--ID inverted indexes to support efficient spatial range filtering and conjunctive keyword matching. To hide the search pattern and access pattern under a dual-server setting, BRASP integrates index shuffling for encrypted keyword and prefix entries with ID-field redistribution across two non-colluding cloud servers. BRASP also supports dynamic updates and achieves forward security. We formalize the security of BRASP through confidentiality, shuffle indistinguishability, query unforgeability, and forward-security analyses, and we evaluate its performance experimentally on a real-world dataset. The results show that BRASP effectively protects query privacy while incurring relatively low computation and communication overhead. To facilitate reproducibility and further research, the source code of BRASP is publicly available at https://github.com/Egbert-Lannister/BRASP</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.07531v1">PRISM: Evaluating a Rule-Based, Scenario-Driven Social Media Privacy Education Program for Young Autistic Adults</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-04-08T19:13:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kirsten Chapman, Garrett Smith, Kaitlyn Klabacka, Joseph Thomas Bills, Addisyn Bushman, Terisa Gabrielsen, Pamela J Wisniewski, Xinru Page</p>
    <p><b>Summary:</b> Young autistic adults may garner benefits through social media but also disproportionately experience privacy harms. Prior research found that these harms often stem from perceiving the affordances of social media differently than the general population, leading to unintentional risky behaviors and interactions with others. While educational interventions have been shown to increase social media privacy literacy for the general population, research has yet to focus on effective educational interventions for autistic young adults. We address this gap by developing and deploying Privacy Rules for Inclusive Social Media (PRISM), a classroom-based educational intervention tailored to the unique risks and neurodevelopmental differences of this population. Twenty-nine autistic students with substantial (level 2) support needs participated in a 14-week social media privacy literacy class. During these classes, participants often communicated their existing rule-based "all or nothing" approaches to privacy management (such as completely disengaging from social media to avoid privacy issues). Our course focused on empowering them by providing more nuanced guidance on safe privacy practices through the use of scenario-based formats and contextual, rule-based scenarios. Using pre- and post-knowledge assessments for each of our 6 course topics, our intervention led to a statistically significant increase in their making safer social media privacy decisions. We conclude with recommendations for how privacy educators and technology designers can leverage neuro-affirming educational interventions to increase privacy literacy for autistic social media users.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.07486v1">Private Seeds, Public LLMs: Realistic and Privacy-Preserving Synthetic Data Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-04-08T18:26:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qian Ma, Sarah Rajtmajer</p>
    <p><b>Summary:</b> Large language models (LLMs) have emerged as a powerful tool for synthetic data generation. A particularly important use case is producing synthetic replicas of private text, which requires carefully balancing privacy and utility. We propose Realistic and Privacy-Preserving Synthetic Data Generation (RPSG), which leverages privacy-preserving mechanisms, including formal differential privacy (DP); and private seeds, in particular text containing personal information, to generate realistic synthetic data. Comprehensive experiments against state-of-the-art private synthetic data generation methods demonstrate that RPSG achieves high fidelity to private data while providing strong privacy protection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.07238v1">On the Price of Privacy for Language Identification and Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2026-04-08T16:04:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaoyu Li, Andi Han, Jiaojiao Jiang, Junbin Gao</p>
    <p><b>Summary:</b> As large language models (LLMs) are increasingly trained on sensitive user data, understanding the fundamental cost of privacy in language learning becomes essential. We initiate the study of differentially private (DP) language identification and generation in the agnostic statistical setting, establishing algorithms and matching lower bounds that precisely quantify the cost of privacy. For both tasks, approximate $(\varepsilon, δ)$-DP with constant $\varepsilon > 0$ recovers the non-private error rates: $\exp(-r(n))$ for identification (for any $r(n) = o(n)$) and $\exp(-Ω(n))$ for generation. Under pure $\varepsilon$-DP, the exponents degrade by a multiplicative factor of $\min\{1, \varepsilon\}$, which we show is tight up to constants. Notably, for generation under pure DP with mild assumptions, the upper bound $\exp(-\min\{1,\varepsilon\} \cdot Ω(n))$ matches the lower bound up to some constants, establishing an optimal rate. Our results show that the cost of privacy in language learning is surprisingly mild: absent entirely under approximate DP, and exactly a $\min\{1,\varepsilon\}$ factor in the exponent under pure DP.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.07132v1">CSA-Graphs: A Privacy-Preserving Structural Dataset for Child Sexual Abuse Research</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-04-08T14:26:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Carlos Caetano, Camila Laranjeira, Clara Ernesto, Artur Barros, João Macedo, Leo S. F. Ribeiro, Jefersson A. dos Santos, Sandra Avila</p>
    <p><b>Summary:</b> Child Sexual Abuse Imagery (CSAI) classification is an important yet challenging problem for computer vision research due to the strict legal and ethical restrictions that prevent the public sharing of CSAI datasets. This limitation hinders reproducibility and slows progress in developing automated methods. In this work, we introduce CSA-Graphs, a privacy-preserving structural dataset. Instead of releasing the original images, we provide structural representations that remove explicit visual content while preserving contextual information. CSA-Graphs includes two complementary graph-based modalities: scene graphs describing object relationships and skeleton graphs encoding human pose. Experiments show that both representations retain useful information for classifying CSAI, and that combining them further improves performance. This dataset enables broader research on computer vision methods for child safety while respecting legal and ethical constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.07125v1">DDP-SA: Scalable Privacy-Preserving Federated Learning via Distributed Differential Privacy and Secure Aggregation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-04-08T14:19:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenjing Wei, Farid Nait-Abdesselam, Alla Jammine</p>
    <p><b>Summary:</b> This article presents DDP-SA, a scalable privacy-preserving federated learning framework that jointly leverages client-side local differential privacy (LDP) and full-threshold additive secret sharing (ASS) for secure aggregation. Unlike existing methods that rely solely on differential privacy or on secure multi-party computation (MPC), DDP-SA integrates both techniques to deliver stronger end-to-end privacy guarantees while remaining computationally practical. The framework introduces a two-stage protection mechanism: clients first perturb their local gradients with calibrated Laplace noise, then decompose the noisy gradients into additive secret shares that are distributed across multiple intermediate servers. This design ensures that (i) no single compromised server or communication channel can reveal any information about individual client updates, and (ii) the parameter server reconstructs only the aggregated noisy gradient, never any client-specific contribution. Extensive experiments show that DDP-SA achieves substantially higher model accuracy than standalone LDP while providing stronger privacy protection than MPC-only approaches. The proposed framework scales linearly with the number of participants and offers a practical, privacy-preserving solution for federated learning applications with controllable computational and communication overhead.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.06831v1">Towards Privacy-Preserving Large Language Model: Text-free Inference Through Alignment and Adaptation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-04-08T08:49:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jeongho Yoon, Chanhee Park, Yongchan Chun, Hyeonseok Moon, Heuiseok Lim</p>
    <p><b>Summary:</b> Current LLM-based services typically require users to submit raw text regardless of its sensitivity. While intuitive, such practice introduces substantial privacy risks, as unauthorized access may expose personal, medical, or legal information. Although prior defenses strived to mitigate these risks, they often incur substantial computational overhead and degrade model performance. To overcome this privacy-efficiency trade-off, we introduce Privacy-Preserving Fine-Tuning (PPFT), a novel training pipeline that eliminates the need for transmitting raw prompt text while maintaining a favorable balance between privacy preservation and model utility for both clients and service providers. Our approach operates in two stages: first, we train a client-side encoder together with a server-side projection module and LLM, enabling the server to condition on k-pooled prompt embeddings instead of raw text; second, we fine-tune the projection module and LLM on private, domain-specific data using noise-injected embeddings, allowing effective adaptation without exposing plain text prompts and requiring access to the decoder's internal parameters. Extensive experiments on domain-specific and general benchmarks demonstrate that PPFT achieves a striking balance between privacy and utility, maintaining competitive performance with minimal degradation compared to noise-free upper bounds.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.06518v1">Adaptive Differential Privacy for Federated Medical Image Segmentation Across Diverse Modalities</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-04-07T23:18:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Puja Saha, Eranga Ukwatta</p>
    <p><b>Summary:</b> Large volumes of medical data remain underutilized because centralizing distributed data is often infeasible due to strict privacy regulations and institutional constraints. In addition, models trained in centralized settings frequently fail to generalize across clinical sites because of heterogeneity in imaging protocols and continuously evolving data distributions arising from differences in scanners, acquisition parameters, and patient populations. Federated learning offers a promising solution by enabling collaborative model training without sharing raw data. However, incorporating differential privacy into federated learning, while essential for privacy guarantees, often leads to degraded accuracy, unstable convergence, and reduced generalization. In this work, we propose an adaptive differentially private federated learning (ADP-FL) framework for medical image segmentation that dynamically adjusts privacy mechanisms to better balance the privacy-utility trade-off. The proposed approach stabilizes training, significantly improves Dice scores and segmentation boundary quality, and maintains rigorous privacy guarantees. We evaluated ADP-FL across diverse imaging modalities and segmentation tasks, including skin lesion segmentation in dermoscopic images, kidney tumor segmentation in 3D CT scans, and brain tumor segmentation in multi-parametric MRI. Compared with conventional federated learning and standard differentially private federated learning, ADP-FL consistently achieves higher accuracy, improved boundary delineation, faster convergence, and greater training stability, with performance approaching that of non-private federated learning under the same privacy budgets. These results demonstrate the practical viability of ADP-FL for high-performance, privacy-preserving medical image segmentation in real-world federated settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.06499v1">Equivalence Testing Under Privacy Constraints</a></h3>
   
  <p><b>Published on:</b> 2026-04-07T22:06:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Savita Pareek, Luca Insolia, Roberto Molinari, Stéphane Guerrier</p>
    <p><b>Summary:</b> Protecting individual privacy is essential across research domains, from socio-economic surveys to big-tech user data. This need is particularly acute in healthcare, where analyses often involve sensitive patient information. A typical example is comparing treatment efficacy across hospitals or ensuring consistency in diagnostic laboratory calibrations, both requiring privacy-preserving statistical procedures. However, standard equivalence testing procedures for differences in proportions or means, commonly used to assess average equivalence, can inadvertently disclose sensitive information. To address this problem, we develop differentially private equivalence testing procedures that rely on simulation-based calibration, as the finite-sample distribution is analytically intractable. Our approach introduces a unified framework, termed DP-TOST, for conducting differentially private equivalence testing of both means and proportions. Through numerical simulations and real-world applications, we demonstrate that the proposed method maintains type-I error control at the nominal level and achieves power comparable to its non-private counterpart as the privacy budget and/or sample size increases, while ensuring strong privacy guarantees. These findings establish a reliable and practical framework for privacy-preserving equivalence testing in high-stakes fields such as healthcare, among others.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.06409v1">Say Something Else: Rethinking Contextual Privacy as Information Sufficiency</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-04-07T19:44:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yunze Xiao, Wenkai Li, Xiaoyuan Wu, Ningshan Ma, Yueqi Song, Weihao Xuan</p>
    <p><b>Summary:</b> LLM agents increasingly draft messages on behalf of users, yet users routinely overshare sensitive information and disagree on what counts as private. Existing systems support only suppression (omitting sensitive information) and generalization (replacing information with an abstraction), and are typically evaluated on single isolated messages, leaving both the strategy space and evaluation setting incomplete. We formalize privacy-preserving LLM communication as an \textbf{Information Sufficiency (IS)} task, introduce \textbf{free-text pseudonymization} as a third strategy that replaces sensitive attributes with functionally equivalent alternatives, and propose a \textbf{conversational evaluation protocol} that assesses strategies under realistic multi-turn follow-up pressure. Across 792 scenarios spanning three power-relation types (institutional, peer, intimate) and three sensitivity categories (discrimination risk, social cost, boundary), we evaluate seven frontier LLMs on privacy at two granularities, covertness, and utility. Pseudonymization yields the strongest privacy\textendash utility tradeoff overall, and single-message evaluation systematically underestimates leakage, with generalization losing up to 16.3 percentage points of privacy under follow-up.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.06382v1">Designing Privacy-Preserving Visual Perception for Robot Navigation Based on User Privacy Preferences</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E">
  <p><b>Published on:</b> 2026-04-07T19:12:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xuying Huang, Sicong Pan, Delphine Reinhardt, Maren Bennewitz</p>
    <p><b>Summary:</b> Visual navigation is a fundamental capability of mobile service robots, yet the onboard cameras required for such navigation can capture privacy-sensitive information and raise user privacy concerns. Existing approaches to privacy-preserving navigation-oriented visual perception have largely been driven by technical considerations, with limited grounding in user privacy preferences. In this work, we propose a user-centered approach to designing privacy-preserving visual perception for robot navigation. To investigate how user privacy preferences can inform such design, we conducted two user studies. The results show that users prefer privacy-preserving visual abstractions and capture-time low-resolution preservation mechanisms: their preferred RGB resolution depends both on the desired privacy level and robot proximity during navigation. Based on these findings, we further derive a user-configurable distance-to-resolution privacy policy for privacy-preserving robot visual navigation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.06367v1">WebSP-Eval: Evaluating Web Agents on Website Security and Privacy Tasks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-04-07T18:43:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guruprasad Viswanathan Ramesh, Asmit Nayak, Basieem Siddique, Kassem Fawaz</p>
    <p><b>Summary:</b> Web agents automate browser tasks, ranging from simple form completion to complex workflows like ordering groceries. While current benchmarks evaluate general-purpose performance~(e.g., WebArena) or safety against malicious actions~(e.g., SafeArena), no existing framework assesses an agent's ability to successfully execute user-facing website security and privacy tasks, such as managing cookie preferences, configuring privacy-sensitive account settings, or revoking inactive sessions. To address this gap, we introduce WebSP-Eval, an evaluation framework for measuring web agent performance on website security and privacy tasks. WebSP-Eval comprises 1) a manually crafted task dataset of 200 task instances across 28 websites; 2) a robust agentic system supporting account and initial state management across runs using a custom Google Chrome extension; and 3) an automated evaluator. We evaluate a total of 8 web agent instantiations using state-of-the-art multimodal large language models, conducting a fine-grained analysis across websites, task categories, and UI elements. Our evaluation reveals that current models suffer from limited autonomous exploration capabilities to reliably solve website security and privacy tasks, and struggle with specific task categories and websites. Crucially, we identify stateful UI elements such as toggles and checkboxes are a primary reason for agent failure, failing at a rate of more than 45\% in tasks containing these elements across many models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.06101v1">Towards Securing IIoT: An Innovative Privacy-Preserving Anomaly Detector Based on Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-07T17:14:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Samira Kamali Poorazad, Chafika Benzaïd, Tarik Taleb</p>
    <p><b>Summary:</b> In the light of the growing connectivity and sensitivity of industrial data,
  cyberattacks and data breaches are becoming more common in the Industrial Internet of Things (IIoT). To cope with such threats, this study presents an anomaly detection system based on a novel Federated Learning (FL) framework. This system detects anomalies such as cyberattacks and protects industrial data privacy by processing data locally and training anomaly detection models on industrial agents without sharing raw data. The proposed FL framework incorporates two key components to enhance both privacy and efficiency. The first component is Homomorphic Encryption (HE), which is integrated into the framework to further protect sensitive data transmissions such as model parameters. HE enhances privacy in FL by preventing adversaries from inferring private industrial data through attacks, such as model inversion attacks. The second component is an innovative dynamic agent selection scheme, wherein a selection threshold is calculated based on agent delays and data size. The purpose of this new scheme is to mitigate the straggler effect and the communication bottleneck that occur in traditional FL architectures, such as synchronous and asynchronous architectures. It ensures that agents are not unfairly selected by the different delays resulting from heterogeneous data in IIoT environments, while simultaneously improving model performance and convergence speed.
  The proposed framework exhibits superior performance over
  baseline approaches in terms of accuracy, precision, F1-scores, communication costs, convergence speeds, and fairness rate.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.05793v1">BodhiPromptShield: Pre-Inference Prompt Mediation for Suppressing Privacy Propagation in LLM/VLM Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-04-07T12:29:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bo Ma, Jinsong Wu, Weiqi Yan</p>
    <p><b>Summary:</b> In LLM/VLM agents, prompt privacy risk propagates beyond a single model call because raw user content can flow into retrieval queries, memory writes, tool calls, and logs. Existing de-identification pipelines address document boundaries but not this cross-stage propagation. We propose BodhiPromptShield, a policy-aware framework that detects sensitive spans, routes them via typed placeholders, semantic abstraction, or secure symbolic mapping, and delays restoration to authorized boundaries. Relative to enterprise redaction, this adds explicit propagation-aware mediation and restoration timing as a security variable. Under controlled evaluation on the Controlled Prompt-Privacy Benchmark (CPPB), stage-wise propagation suppresses from 10.7\% to 7.1\% across retrieval, memory, and tool stages; PER reaches 9.3\% with 0.94 AC and 0.92 TSR, outperforming generic de-identification. These are controlled systems results on CPPB rather than formal privacy guarantees or public-benchmark transfer claims.
  The project repository is available at https://github.com/mabo1215/BodhiPromptShield.git.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.05571v1">Understanding User Privacy Perceptions of GenAI Smartphones</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-04-07T08:13:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ran Jin, Liu Wang, Shidong Pan, Luona Xu, Tianming Liu, Haoyu Wang</p>
    <p><b>Summary:</b> GenAI smartphones, which natively embed generative AI at the system level, are transforming mobile interactions by automating a wide range of tasks and executing UI actions on behalf of users. Their superior capabilities rely on continuous access to sensitive and context-rich data, raising privacy concerns that surpass those of traditional mobile devices. Yet, little is known about how users perceive the privacy implications of such devices or what safeguards they expect, which is especially critical at this early stage of GenAI smartphone adoption. To address this gap, we conduct 22 semi-structured interviews with everyday mobile users to explore their usage of GenAI smartphones, privacy concerns, and privacy design expectations. Our findings show that users engage with GenAI smartphones with limited understanding of how these systems operate to deliver functions, but show heightened privacy concerns once exposed to the technical details. Participants' concerns span the entire data lifecycle, including nontransparent collection, insecure storage, and weak data control. In a follow-up focus group, participants discuss a range of privacy-enhancing suggestions that call for coordinated changes across system-level controls, data management practices, and user-facing transparency. Their concerns and suggestions offer user-centered guidances for designing GenAI smartphones that balance functionality with privacy protection, offering valuable takeaways for system designers and regulators.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.05077v1">Feature-Aware Anisotropic Local Differential Privacy for Utility-Preserving Graph Representation Learning in Metal Additive Manufacturing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-06T18:29:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> MD Shafikul Islam, Mahathir Mohammad Bappy, Saifur Rahman Tushar, Md Arifuzzaman</p>
    <p><b>Summary:</b> Metal additive manufacturing (AM) enables the fabrication of safety-critical components, but reliable quality assurance depends on high-fidelity sensor streams containing proprietary process information, limiting collaborative data sharing. Existing defect-detection models typically treat melt-pool observations as independent samples, ignoring layer-wise physical couplings. Moreover, conventional privacy-preserving techniques, particularly Local Differential Privacy (LDP), lead to severe utility degradation because they inject uniform noise across all feature dimensions. To address these interrelated challenges, we propose FI-LDP-HGAT. This computational framework combines two methodological components: a stratified Hierarchical Graph Attention Network (HGAT) that captures spatial and thermal dependencies across scan tracks and deposited layers, and a feature-importance-aware anisotropic Gaussian mechanism (FI-LDP) for non-interactive feature privatization. Unlike isotropic LDP, FI-LDP redistributes the privacy budget across embedding coordinates using an encoder-derived importance prior, assigning lower noise to task-critical thermal signatures and higher noise to redundant dimensions while maintaining formal LDP guarantees. Experiments on a Directed Energy Deposition (DED) porosity dataset demonstrate that FI-LDP-HGAT achieves 81.5% utility recovery at a moderate privacy budget (epsilon = 4) and maintains defect recall of 0.762 under strict privacy (epsilon = 2), while outperforming classical ML, standard GNNs, and alternative privacy mechanisms, including DP-SGD across all evaluated metrics. Mechanistic analysis confirms a strong negative correlation (Spearman = -0.81) between feature importance and noise magnitude, providing interpretable evidence that the privacy-utility gains are driven by principled anisotropic allocation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.04572v1">Digital Privacy in IoT: Exploring Challenges, Approaches and Open Issues</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-06T10:08:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shini Girija, Pranav M. Pawar, Raja Muthalagu, Mithun Mukherjee</p>
    <p><b>Summary:</b> Privacy has always been a critical issue in the digital era, particularly with the increasing use of Internet of Things (IoT) devices. As the IoT continues to transform industries such as healthcare, smart cities, and home automation, it has also introduced serious challenges regarding the security of sensitive and private data. This paper examines the complex landscape of digital privacy in IoT ecosystems, highlighting the need to protect personally identifiable information (PII) of individuals and uphold their rights to digital independence. Global events, such as the COVID-19 pandemic, have accelerated the adoption of IoT, raising concerns about privacy and data protection. This paper provides an in-depth examination of digital privacy risks in the IoT domain and introduces a clear taxonomy for evaluating them using the IEEE Digital Privacy Model. The proposed framework categorizes privacy risks into five types: identity-oriented, behavioral, inference, data manipulation, and regulatory risks. We review existing digital privacy solutions, including encryption technologies, blockchain, federated learning, differential privacy, reinforcement learning, AI, and dynamic consent mechanisms, to mitigate these risks. We also highlight how these privacy-enhancing technologies (PETs) help with data confidentiality, access control, and trust management. Additionally, this study presents AURA-IoT, a futuristic framework that tackles AI-driven privacy risks through a multi-layered structure. AURA-IoT integrates adversarial robustness, explainability, transparency, fairness, compliance, dynamic consent, and policy enforcement mechanisms to ensure digital privacy, security, and accountable IoT operations. Finally, we discuss ongoing challenges and potential research directions for integrating AI and encryption-based privacy solutions to achieve comprehensive digital privacy in future IoT systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.04195v1">Stable and Privacy-Preserving Synthetic Educational Data with Empirical Marginals: A Copula-Based Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-04-05T17:34:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gabriel Diaz Ramos, Lorenzo Luzi, Debshila Basu Mallick, Richard Baraniuk</p>
    <p><b>Summary:</b> To advance Educational Data Mining (EDM) within strict privacy-protecting regulatory frameworks, researchers must develop methods that enable data-driven analysis while protecting sensitive student information. Synthetic data generation is one such approach, enabling the release of statistically generated samples instead of real student records; however, existing deep learning and parametric generators often distort marginal distributions and degrade under iterative regeneration, leading to distribution drift and progressive loss of distributional support that compromise reliability. In response, we introduce the Non-Parametric Gaussian Copula (NPGC), a plug-and-play synthesis method that replaces deep learning and parametric optimization with empirical statistical anchoring to preserve the observed marginal distributions while modeling dependencies through a copula framework. NPGC integrates Differential Privacy (DP) at both the marginal and correlation levels, supports heterogeneous variable types, and treats missing data as an explicit state to retain informative absence patterns. We evaluate NPGC against deep learning and parametric baselines on five benchmark datasets and demonstrate that it remains stable across multiple regeneration cycles and achieves competitive downstream performance at substantially lower computational cost. We further validate NPGC through deployment in a real-world online learning platform, demonstrating its practicality for privacy-preserving research.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.03640v1">ComPrivDet: Efficient Privacy Object Detection in Compressed Domains Through Inference Reuse</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-04T08:32:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yunhao Yao, Zhiqiang Wang, Ruiqi Li, Haoran Cheng, Puhan Luo, Xiangyang Li</p>
    <p><b>Summary:</b> As the Internet of Things (IoT) becomes deeply embedded in daily life, users are increasingly concerned about privacy leakage, especially from video data. Since frame-by-frame protection in large-scale video analytics (e.g., smart communities) introduces significant latency, a more efficient solution is to selectively protect frames containing privacy objects (e.g., faces). Existing object detectors require fully decoded videos or per-frame processing in compressed videos, leading to decoding overhead or reduced accuracy. Therefore, we propose ComPrivDet, an efficient method for detecting privacy objects in compressed video by reusing I-frame inference results. By identifying the presence of new objects through compressed-domain cues, ComPrivDet either skips P- and B-frame detections or efficiently refines them with a lightweight detector. ComPrivDet maintains 99.75% accuracy in private face detection and 96.83% in private license plate detection while skipping over 80% of inferences. It averages 9.84% higher accuracy with 75.95% lower latency than existing compressed-domain detection methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.06235v1">Negotiating Privacy with Smart Voice Assistants: Risk-Benefit and Control-Acceptance Tensions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-04-04T06:35:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Molly Campbell, Mohamad Sheikho Al Jasem, Ajay Kumar Shrestha</p>
    <p><b>Summary:</b> Smart Voice assistants (SVAs) are widely adopted by youth, yet privacy decision-making in these environments is often characterized by competing considerations rather than clear-cut preferences. While our prior research has examined privacy risks, benefits, trust, and self-efficacy as distinct predictors of behavior, less attention has been paid to how these factors combine into higher-level tension that shapes privacy outcomes. This study introduces a negotiation-based framework for understanding youth privacy decision-making with SVAs by operationalizing two composite indices: the Risk-Benefit Tension Index (RBTI) and the Control-Acceptance Tension Index (CATI), using survey data from 469 Canadian youth aged 16-24. We examine the distribution of these indices and their relationship with privacy-protective behavior and SVA usage. Results show that both indices are meaningfully associated with protective action. Frequent SVA usage exhibits more benefit-dominant and acceptance-leaning negotiation profiles, suggesting that convenience-driven engagement may come at the expense of perceived control. By reframing privacy decision-making as a process of negotiation rather than inconsistency, this study offers a complementary perspective on the privacy paradox and provides a compact measurement approach for capturing how youth navigate competing privacy pressures in voice-enabled ecosystems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.02616v1">Unlocking Multi-Site Clinical Data: A Federated Approach to Privacy-First Child Autism Behavior Analysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-04-03T01:08:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guangyu Sun, Wenhan Wu, Zhishuai Guo, Ziteng Wang, Pegah Khosravi, Chen Chen</p>
    <p><b>Summary:</b> Automated recognition of autistic behaviors in children is essential for early intervention and objective clinical assessment. However, the development of robust models is severely hindered by strict privacy regulations (e.g., HIPAA) and the sensitive nature of pediatric data, which prevents the centralized aggregation of clinical datasets. Furthermore, individual clinical sites often suffer from data scarcity, making it difficult to learn generalized behavior patterns or tailor models to site-specific patient distributions. To address these challenges, we observe that Federated Learning (FL) can decouple model training from raw data access, enabling multi-site collaboration while maintaining strict data residency. In this paper, we present the first study exploring Federated Learning for pose-based child autism behavior recognition. Our framework employs a two-layer privacy protection mechanism: utilizing human skeletal abstraction to remove identifiable visual information from the raw RGB videos and FL to ensure sensitive pose data remains within the clinic. This approach leverages distributed clinical data to learn generalized representations while providing the flexibility for site-specific personalization. Experimental results on the MMASD benchmark demonstrate that our framework achieves high recognition accuracy, outperforming traditional federated baselines and providing a robust, privacy-first solution for multi-site clinical analysis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.02558v1">Communication-Efficient Distributed Learning with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E">
  <p><b>Published on:</b> 2026-04-02T22:19:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaoxing Ren, Yuwen Ma, Nicola Bastianello, Karl H. Johansson, Thomas Parisini, Andreas A. Malikopoulos</p>
    <p><b>Summary:</b> We address nonconvex learning problems over undirected networks. In particular, we focus on the challenge of designing an algorithm that is both communication-efficient and that guarantees the privacy of the agents' data. The first goal is achieved through a local training approach, which reduces communication frequency. The second goal is achieved by perturbing gradients during local training, specifically through gradient clipping and additive noise. We prove that the resulting algorithm converges to a stationary point of the problem within a bounded distance. Additionally, we provide theoretical privacy guarantees within a differential privacy framework that ensure agents' training data cannot be inferred from the trained model shared over the network. We show the algorithm's superior performance on a classification task under the same privacy budget, compared with state-of-the-art methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.02248v1">BVFLMSP : Bayesian Vertical Federated Learning for Multimodal Survival with Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-04-02T16:37:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abhilash Kar, Basisth Saha, Tanmay Sen, Biswabrata Pradhan</p>
    <p><b>Summary:</b> Multimodal time-to-event prediction often requires integrating sensitive data distributed across multiple parties, making centralized model training impractical due to privacy constraints. At the same time, most existing multimodal survival models produce single deterministic predictions without indicating how confident the model is in its estimates, which can limit their reliability in real-world decision making. To address these challenges, we propose BVFLMSP, a Bayesian Vertical Federated Learning (VFL) framework for multimodal time-to-event analysis based on a Split Neural Network architecture. In BVFLMSP, each client independently models a specific data modality using a Bayesian neural network, while a central server aggregates intermediate representations to perform survival risk prediction. To enhance privacy, we integrate differential privacy mechanisms by perturbing client side representations before transmission, providing formal privacy guarantees against information leakage during federated training.
  We first evaluate our Bayesian multimodal survival model against widely used single modality survival baselines and the centralized multimodal baseline MultiSurv. Across multimodal settings, the proposed method shows consistent improvements in discrimination performance, with up to 0.02 higher C-index compared to MultiSurv. We then compare federated and centralized learning under varying privacy budgets across different modality combinations, highlighting the tradeoff between predictive performance and privacy. Experimental results show that BVFLMSP effectively includes multimodal data, improves survival prediction over existing baselines, and remains robust under strict privacy constraints while providing uncertainty estimates.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.02397v1">Variational Encoder--Multi-Decoder (VE-MD) for Privacy-by-functional-design (Group) Emotion Recognition</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-04-02T13:38:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anderson Augusma, Dominique Vaufreydaz, Fédérique Letué</p>
    <p><b>Summary:</b> Group Emotion Recognition (GER) aims to infer collective affect in social environments such as classrooms, crowds, and public events. Many existing approaches rely on explicit individual-level processing, including cropped faces, person tracking, or per-person feature extraction, which makes the analysis pipeline person-centric and raises privacy concerns in deployment scenarios where only group-level understanding is needed. This research proposes VE-MD, a Variational Encoder-Multi-Decoder framework for group emotion recognition under a privacy-aware functional design. Rather than providing formal anonymization or cryptographic privacy guarantees, VE-MD is designed to avoid explicit individual monitoring by constraining the model to predict only aggregate group-level affect, without identity recognition or per-person emotion outputs. VE-MD learns a shared latent representation jointly optimized for emotion classification and internal prediction of body and facial structural representations. Two structural decoding strategies are investigated: a transformer-based PersonQuery decoder and a dense Heatmap decoder that naturally accommodates variable group sizes. Experiments on six in-the-wild datasets, including two GER and four Individual Emotion Recognition (IER) benchmarks, show that structural supervision consistently improves representation learning. More importantly, the results reveal a clear distinction between GER and IER: optimizing the latent space alone is often insufficient for GER because it tends to attenuate interaction-related cues, whereas preserving explicit structural outputs improves collective affect inference. In contrast, projected structural representations seem to act as an effective denoising bottleneck for IER. VE-MD achieves state-of-the-art performance on GAF-3.0 (up to 90.06%) and VGAF (82.25% with multimodal fusion with audio). These results show that preserving interaction-related structural information is particularly beneficial for group-level affect modeling without relying on prior individual feature extraction. On IER datasets using multimodal fusion with audio modality, VE-MD outperforms SOTA on SamSemo (77.9%, adding text modality) while achieving competitive performances on MER-MULTI (63.8%), DFEW (70.7%) and EngageNet (69.0).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.01616v2">Quantum-Enhanced Processing with Tensor-Network Frontends for Privacy-Aware Federated Medical Diagnosis</a></h3>
  
  <p><b>Published on:</b> 2026-04-02T04:52:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hiroshi Yamauchi, Anders Peter Kragh Dalskov, Hideaki Kawaguchi, Rodney Van Meter</p>
    <p><b>Summary:</b> We propose a privacy-aware hybrid framework for federated medical image classification that combines tensor-network representation learning, MPC-secured aggregation, and post-aggregation quantum refinement. The framework is motivated by two practical constraints in privacy-aware federated learning: MPC can introduce substantial communication overhead, and direct quantum processing of high-dimensional medical images is unrealistic with a small number of qubits. To address both constraints within a single architecture, client-side tensor-network frontends, Matrix Product State (MPS), Tree Tensor Network (TTN), and Multi-scale Entanglement Renormalization Ansatz (MERA), compress local inputs into compact latent representations, after which a Quantum-Enhanced Processor (QEP) refines the aggregated latent feature through quantum-state embedding and observable-based readout. Experiments on PneumoniaMNIST show that the effect of the QEP is frontend-dependent rather than uniform across architectures. In the present setting, the TTN+QEP combination exhibits the most balanced overall profile. The results also suggest that the QEP behaves more stably when the qubit count is sufficiently matched to the latent dimension, while noisy conditions degrade performance relative to the noiseless setting. The MPC benchmark further shows that communication cost is governed primarily by the dimension of the protected latent representation. This indicates that tensor-network compression plays a dual role: it enables small-qubit quantum processing on compressed latent features and reduces the communication overhead associated with secure aggregation. Taken together, these results support a co-design perspective in which representation compression, post-aggregation quantum refinement, and privacy-aware deployment should be optimized jointly.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.01487v2">AgentSocialBench: Evaluating Privacy Risks in Human-Centered Agentic Social Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B">
  <p><b>Published on:</b> 2026-04-01T23:43:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Prince Zizhuang Wang, Shuli Jiang</p>
    <p><b>Summary:</b> With the rise of personalized, persistent LLM agent frameworks such as OpenClaw, human-centered agentic social networks in which teams of collaborative AI agents serve individual users in a social network across multiple domains are becoming a reality. This setting creates novel privacy challenges: agents must coordinate across domain boundaries, mediate between humans, and interact with other users' agents, all while protecting sensitive personal information. While prior work has evaluated multi-agent coordination and privacy preservation, the dynamics and privacy risks of human-centered agentic social networks remain unexplored. To this end, we introduce AgentSocialBench, the first benchmark to systematically evaluate privacy risk in this setting, comprising scenarios across seven categories spanning dyadic and multi-party interactions, grounded in realistic user profiles with hierarchical sensitivity labels and directed social graphs. Our experiments reveal that privacy in agentic social networks is fundamentally harder than in single-agent settings: (1) cross-domain and cross-user coordination creates persistent leakage pressure even when agents are explicitly instructed to protect information, (2) privacy instructions that teach agents how to abstract sensitive information paradoxically cause them to discuss it more (we call it abstraction paradox). These findings underscore that current LLM agents lack robust mechanisms for privacy preservation in human-centered agentic social networks, and that new approaches beyond prompt engineering are needed to make agent-mediated social coordination safe for real-world deployment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.01481v1">DISCO-TAB: A Hierarchical Reinforcement Learning Framework for Privacy-Preserving Synthesis of Complex Clinical Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-04-01T23:37:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arshia Ilaty, Hossein Shirazi, Amir Rahmani, Hajar Homayouni</p>
    <p><b>Summary:</b> The development of robust clinical decision support systems is frequently impeded by the scarcity of high-fidelity, privacy-preserving biomedical data. While Generative Large Language Models (LLMs) offer a promising avenue for synthetic data generation, they often struggle to capture the complex, non-linear dependencies and severe class imbalances inherent in Electronic Health Records (EHR), leading to statistically plausible but clinically invalid records. To bridge this gap, we introduce DISCO-TAB (DIScriminator-guided COntrol for TABular synthesis), a novel framework that orchestrates a fine-tuned LLM with a multi-objective discriminator system optimized via Reinforcement Learning. Unlike prior methods relying on scalar feedback, DISCO-TAB evaluates synthesis at four granularities, token, sentence, feature, and row, while integrating Automated Constraint Discovery and Inverse-Frequency Reward Shaping to autonomously preserve latent medical logic and resolve minority-class collapse. We rigorously validate our framework across diverse benchmarks, including high-dimensional, small-sample medical datasets (e.g., Heart Failure, Parkinson's). Our results demonstrate that hierarchical feedback yields state-of-the-art performance, achieving up to 38.2% improvement in downstream clinical classifier utility compared to GAN and Diffusion baselines, while ensuring exceptional statistical fidelity (JSD < 0.01) and robust resistance to membership inference attacks. This work establishes a new standard for generating trustworthy, utility-preserving synthetic tabular data for sensitive healthcare applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.01393v1">Identifying Privacy Concerns in Upcoming Software Release: A Peek into the Future</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2026-04-01T20:51:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aurek Chattopadhyay, Nan Niu</p>
    <p><b>Summary:</b> Identifying the features to be released in the next version of software, from a pool of potential candidates, is a challenging problem. User feedback from app stores is frequently used by software vendors for the evolution of apps across releases. Privacy feedback, although smaller in volume, carries a larger impact influencing app's success. Multiple existing work has focused on summarizing privacy concerns at the app level and has also shown that developers utilize feedback to implement security and privacy-related changes in subsequent releases. However, the current literature offers little support for release managers and developers in identifying privacy concerns prior to release. This gap exists as user reviews are typically available in app stores only after new features of a software system is released. In this paper, we introduce Pre-PI, a novel approach that summarizes privacy concerns for to-be-released features. Our method first maps existing features to semantically similar privacy reviews to learn feature-privacy review relations. We then simulate feedback for candidate features and generate concise summaries of privacy concerns. We evaluate Pre-PI across three real-world apps, and compare it with Hark, a state-of-the-art method that relies on post-release user feedback to identify privacy concerns. Results show that Pre-PI generates additional valid privacy concerns and identifies these concerns earlier than Hark, allowing proactive mitigation prior to release.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.01370v1">"The System Will Choose Security Over Humanity Every Time": Understanding Security and Privacy for U.S. Incarcerated Users</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-01T20:28:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yael Eiger, Nino Migineishvili, Emi Yoshikawa, Liza Nadtochiy, Kentrell Owens, Franziska Roesner</p>
    <p><b>Summary:</b> Digital devices like tablets, media players, and kiosks are increasingly deployed in U.S. prisons. These technologies can enable incarcerated people to access education, communicate with loved ones, and develop vital reentry skills. However, they can also introduce new privacy and security risks for incarcerated people who have little agency over their usage and contracts, and are currently carved out of many consumer protection safeguards. To investigate these issues, we conducted focus groups and interviews with system-impacted people (n=17), i.e., those formerly incarcerated, and their relatives, to investigate experiences with device-related security and privacy vulnerabilities and the power dynamics that affect their use. In our findings, participants describe pervasive surveillance, censorship, and usability problems with the technology available to them, including shifting and seemingly arbitrary usage policies. These policies strain relationships both inside and outside prisons and contribute to negative downstream effects for incarcerated users. We recommend ways to better balance prison security concerns with privacy-related needs of system-impacted individuals by promoting accountability for technology-related decisions, providing public oversight of digital purchasing and use policies, and designing digital tools with them -- the actual end-users -- in mind.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.01113v1">CARE: Privacy-Compliant Agentic Reasoning with Evidence Discordance</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-04-01T16:37:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haochen Liu, Weien Li, Rui Song, Zeyu Li, Chun Jason Xue, Xiao-Yang Liu, Sam Nallaperuma, Xue Liu, Ye Yuan</p>
    <p><b>Summary:</b> Large language model (LLM) systems are increasingly used to support high-stakes decision-making, but they typically perform worse when the available evidence is internally inconsistent. Such a scenario exists in real-world healthcare settings, with patient-reported symptoms contradicting medical signs. To study this problem, we introduce MIMIC-DOS, a dataset for short-horizon organ dysfunction worsening prediction in the intensive care unit (ICU) setting. We derive this dataset from the widely recognized MIMIC-IV, a publicly available electronic health record dataset, and construct it exclusively from cases in which discordance between signs and symptoms exists. This setting poses a substantial challenge for existing LLM-based approaches, with single-pass LLMs and agentic pipelines often struggling to reconcile such conflicting signals. To address this problem, we propose CARE: a multi-stage privacy-compliant agentic reasoning framework in which a remote LLM provides guidance by generating structured categories and transitions without accessing sensitive patient data, while a local LLM uses these categories and transitions to support evidence acquisition and final decision-making. Empirically, CARE achieves stronger performance across all key metrics compared to multiple baseline settings, showing that CARE can more robustly handle conflicting clinical evidence while preserving privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.00986v2">Do Phone-Use Agents Respect Your Privacy?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-04-01T14:50:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhengyang Tang, Ke Ji, Xidong Wang, Zihan Ye, Xinyuan Wang, Yiduo Guo, Ziniu Li, Chenxin Li, Jingyuan Hu, Shunian Chen, Tongxu Luo, Jiaxi Bi, Zeyu Qin, Shaobo Wang, Xin Lai, Pengyuan Lyu, Junyi Li, Can Xu, Chengquan Zhang, Han Hu, Ming Yan, Benyou Wang</p>
    <p><b>Summary:</b> We study whether phone-use agents respect privacy while completing benign mobile tasks. This question has remained hard to answer because privacy-compliant behavior is not operationalized for phone-use agents, and ordinary apps do not reveal exactly what data agents type into which form entries during execution. To make this question measurable, we introduce MyPhoneBench, a verifiable evaluation framework for privacy behavior in mobile agents. We operationalize privacy-respecting phone use as permissioned access, minimal disclosure, and user-controlled memory through a minimal privacy contract, iMy, and pair it with instrumented mock apps plus rule-based auditing that make unnecessary permission requests, deceptive re-disclosure, and unnecessary form filling observable and reproducible. Across five frontier models on 10 mobile apps and 300 tasks, we find that task success, privacy-compliant task completion, and later-session use of saved preferences are distinct capabilities, and no single model dominates all three. Evaluating success and privacy jointly reshuffles the model ordering relative to either metric alone. The most persistent failure mode across models is simple data minimization: agents still fill optional personal entries that the task does not require. These results show that privacy failures arise from over-helpful execution of benign tasks, and that success-only evaluation overestimates the deployment readiness of current phone-use agents. All code, mock apps, and agent trajectories are publicly available at~ https://github.com/FreedomIntelligence/MyPhoneBench.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.00903v1">IDDM: Identity-Decoupled Personalized Diffusion Models with a Tunable Privacy-Utility Trade-off</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-04-01T13:46:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Linyan Dai, Xinwei Zhang, Haoyang Li, Qingqing Ye, Haibo Hu</p>
    <p><b>Summary:</b> Personalized text-to-image diffusion models (e.g., DreamBooth, LoRA) enable users to synthesize high-fidelity avatars from a few reference photos for social expression. However, once these generations are shared on social media platforms (e.g., Instagram, Facebook), they can be linked to the real user via face recognition systems, enabling identity tracking and profiling. Existing defenses mainly follow an anti-personalization strategy that protects publicly released reference photos by disrupting model fine-tuning. While effective against unauthorized personalization, they do not address another practical setting in which personalization is authorized, but the resulting public outputs still leak identity information.
  To address this problem, we introduce a new defense setting, termed model-side output immunization, whose goal is to produce a personalized model that supports authorized personalization while reducing the identity linkability of public generations, with tunable control over the privacy-utility trade-off to accommodate diverse privacy needs. To this end, we propose Identity-Decoupled personalized Diffusion Models (IDDM), a model-side defense that integrates identity decoupling into the personalization pipeline. Concretely, IDDM follows an alternating procedure that interleaves short personalization updates with identity-decoupled data optimization, using a two-stage schedule to balance identity linkability suppression and generation utility. Extensive experiments across multiple datasets, diverse prompts, and state-of-the-art face recognition systems show that IDDM consistently reduces identity linkability while preserving high-quality personalized generation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.00761v1">PrivHAR-Bench: A Graduated Privacy Benchmark Dataset for Video-Based Action Recognition</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-01T11:24:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Samar Ansari</p>
    <p><b>Summary:</b> Existing research on privacy-preserving Human Activity Recognition (HAR) typically evaluates methods against a binary paradigm: clear video versus a single privacy transformation. This limits cross-method comparability and obscures the nuanced relationship between privacy strength and recognition utility. We introduce \textit{PrivHAR-Bench}, a multi-tier benchmark dataset designed to standardize the evaluation of the \textit{Privacy-Utility Trade-off} in video-based action recognition. PrivHAR-Bench applies a graduated spectrum of visual privacy transformations: from lightweight spatial obfuscation to cryptographic block permutation, to a curated subset of 15 activity classes selected for human articulation diversity. Each of the 1,932 source videos is distributed across 9 parallel tiers of increasing privacy strength, with additional background-removed variants to isolate the contribution of human motion features from contextual scene bias. We provide lossless frame sequences, per-frame bounding boxes, estimated pose keypoints with joint-level confidence scores, standardized group-based train/test splits, and an evaluation toolkit computing recognition accuracy and privacy metrics. Empirical validation using R3D-18 demonstrates a measurable and interpretable degradation curve across tiers, with within-tier accuracy declining from 88.8\% (clear) to 53.5\% (encrypted, background-removed) and cross-domain accuracy collapsing to 4.8\%, establishing PrivHAR-Bench as a controlled benchmark for comparing privacy-preserving HAR methods under standardized conditions. The dataset, generation pipeline, and evaluation code are publicly available.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.00559v1">FecalFed: Privacy-Preserving Poultry Disease Detection via Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-04-01T07:08:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tien-Yu Chi</p>
    <p><b>Summary:</b> Early detection of highly pathogenic avian influenza (HPAI) and endemic poultry diseases is critical for global food security. While computer vision models excel at classifying diseases from fecal imaging, deploying these systems at scale is bottlenecked by farm data privacy concerns and institutional data silos. Furthermore, existing open-source agricultural datasets frequently suffer from severe, undocumented data contamination. In this paper, we introduce $\textbf{FecalFed}$, a privacy-preserving federated learning framework for poultry disease classification. We first curate and release $\texttt{poultry-fecal-fl}$, a rigorously deduplicated dataset of 8,770 unique images across four disease classes, revealing and eliminating a 46.89$\%$ duplication rate in popular public repositories. To simulate realistic agricultural environments, we evaluate FecalFed under highly heterogeneous, non-IID conditions (Dirichlet $α=0.5$). While isolated single-farm training collapses under this data heterogeneity, yielding only 64.86$\%$ accuracy, our federated approach recovers performance without centralizing sensitive data. Specifically, utilizing server-side adaptive optimization (FedAdam) with a Swin-Small architecture achieves 90.31$\%$ accuracy, closely approaching the centralized upper bound of 95.10\%. Furthermore, we demonstrate that an edge-optimized Swin-Tiny model maintains highly competitive performance at 89.74$\%$, establishing a highly efficient, privacy-first blueprint for on-farm avian disease monitoring.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2604.00430v1">Secure Forgetting: A Framework for Privacy-Driven Unlearning in Large Language Model (LLM)-Based Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-04-01T03:17:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dayong Ye, Tainqing Zhu, Congcong Zhu, Feng He, Qi He, Shang Wang, Bo Liu, Wanlei Zhou</p>
    <p><b>Summary:</b> Large language model (LLM)-based agents have recently gained considerable attention due to the powerful reasoning capabilities of LLMs. Existing research predominantly focuses on enhancing the task performance of these agents in diverse scenarios. However, as LLM-based agents become increasingly integrated into real-world applications, significant concerns emerge regarding their accumulation of sensitive or outdated knowledge. Addressing these concerns requires the development of mechanisms that allow agents to selectively forget previously learned knowledge, giving rise to a new term LLM-based agent unlearning. This paper initiates research on unlearning in LLM-based agents. Specifically, we propose a novel and comprehensive framework that categorizes unlearning scenarios into three contexts: state unlearning (forgetting specific states or items), trajectory unlearning (forgetting sequences of actions) and environment unlearning (forgetting entire environments or categories of tasks). Within this framework, we introduce a natural language-based unlearning method that trains a conversion model to transform high-level unlearning requests into actionable unlearning prompts, guiding agents through a controlled forgetting process. Moreover, to evaluate the robustness of the proposed framework, we introduce an unlearning inference adversary capable of crafting prompts, querying agents, and observing their behaviors in an attempt to infer the forgotten knowledge. Experimental results show that our approach effectively enables agents to forget targeted knowledge while preserving performance on untargeted tasks, and prevents the adversary from inferring the forgotten knowledge.</p>
  </details>
</div>

