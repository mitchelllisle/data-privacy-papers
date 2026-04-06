
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
  <h3><a href="http://arxiv.org/abs/2603.29907v1">Security and Privacy in Virtual and Robotic Assistive Systems: A Comparative Framework</a></h3>
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
  <h3><a href="http://arxiv.org/abs/2603.26215v1">SuperDP: Differential Privacy Refutation via Supermartingales</a></h3>
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


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.19671v1">Acyclic Graph Pattern Counting under Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-20T06:12:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yihua Hu, Kuncan Wang, Wei Dong</p>
    <p><b>Summary:</b> Graph pattern counting serves as a cornerstone of network analysis with extensive real-world applications. Its integration with local differential privacy (LDP) has gained growing attention for protecting sensitive graph information in decentralized settings. However, existing LDP frameworks are largely ad hoc, offering solutions only for specific patterns such as triangles and stars. A general mechanism for counting arbitrary graph patterns, even for the subclass of acyclic patterns, has remained an open problem. To fill this gap, we present the first general solution for counting arbitrary acyclic patterns under LDP. We identify and tackle two fundamental challenges: generalizing pattern construction from distributed data and eliminating node duplication during the construction. To address the first challenge, we propose an LDP-tailored recursive subpattern counting framework that incrementally builds patterns across multiple communication rounds. For the second challenge, we apply a random marking technique that restricts each node to a unique position in the pattern during computation. Our mechanism achieves strong utility guarantees: for any acyclic graph pattern with $k$ edges, we achieve an additive error of $\tilde{O}(\sqrt{N}d(G)^k)$, where $N$ is the number of nodes and $d(G)$ is the maximum degree of the input graph $G$. Experiments on real-world graph datasets across multiple types of acyclic patterns demonstrate that our mechanisms achieve up to $46$-$2600\times$ improvement in utility and $300$-$650\times$ reduction in communication cost compared to the baseline methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.19416v1">Investigating In-Context Privacy Learning by Integrating User-Facing Privacy Tools into Conversational Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-03-19T19:18:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohammad Hadi Nezhad, Francisco Enrique Vicente Castro, Ivon Arroyo</p>
    <p><b>Summary:</b> Supporting users in protecting sensitive information when using conversational agents (CAs) is crucial, as users may undervalue privacy protection due to outdated, partial, or inaccurate knowledge about privacy in CAs. Although privacy knowledge can be developed through standalone resources, it may not readily translate into practice and may remain detached from real-time contexts of use. In this study, we investigate in-context, experiential learning by examining how interactions with privacy tools during chatbot use enhance users' privacy learning. We also explore interface design features that facilitate engagement with these tools and learning about privacy by simulating ChatGPT's interface which we integrated with a just-in-time privacy notice panel. The panel intercepts messages containing sensitive information, warns users about potential sensitivity, offers protective actions, and provides FAQs about privacy in CAs. Participants used versions of the chatbot with and without the privacy panel across two task sessions designed to approximate realistic chatbot use. We qualitatively analyzed participants' pre- and post-test survey responses and think-aloud transcripts and describe findings related to (a) participants' perceptions of privacy before and after the task sessions and (b) interface design features that supported or hindered user-led protection of sensitive information. Finally, we discuss future directions for designing user-facing privacy tools in CAs that promote privacy learning and user engagement in protecting privacy in CAs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.19040v1">When Differential Privacy Meets Wireless Federated Learning: An Improved Analysis for Privacy and Convergence</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-03-19T15:38:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chen Yaoling, Liang Hao, Tu Xiaotong</p>
    <p><b>Summary:</b> Differentially private wireless federated learning (DPWFL) is a promising framework for protecting sensitive user data. However, foundational questions on how to precisely characterize privacy loss remain open, and existing work is further limited by convergence analyses that rely on restrictive convexity assumptions or ignore the effect of gradient clipping. To overcome these issues, we present a comprehensive analysis of privacy and convergence for DPWFL with general smooth non-convex loss objectives. Our analysis explicitly incorporates both device selection and mini-batch sampling, and shows that the privacy loss can converge to a constant rather than diverge with the number of iterations. Moreover, we establish convergence guarantees with gradient clipping and derive an explicit privacy-utility trade-off. Numerical results validate our theoretical findings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.18914v1">Security, privacy, and agentic AI in a regulatory view: From definitions and distinctions to provisions and reflections</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-03-19T13:50:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shiliang Zhang, Sabita Maharjan</p>
    <p><b>Summary:</b> The rapid proliferation of artificial intelligence (AI) technologies has led to a dynamic regulatory landscape, where legislative frameworks strive to keep pace with technical advancements. As AI paradigms shift towards greater autonomy, specifically in the form of agentic AI, it becomes increasingly challenging to precisely articulate regulatory stipulations. This challenge is even more acute in the domains of security and privacy, where the capabilities of autonomous agents often blur traditional legal and technical boundaries. This paper reviews the evolving European Union (EU) AI regulatory provisions via analyzing 24 relevant documents published between 2024 and 2025. From this review, we provide a clarification of critical definitions. We deconstruct the regulatory interpretations of security, privacy, and agentic AI, distinguishing them from closely related concepts to resolve ambiguity. We synthesize the reviewed documents to articulate the current state of regulatory provisions targeting different types of AI, particularly those related to security and privacy aspects. We analyze and reflect on the existing provisions in the regulatory dimension to better align security and privacy obligations with AI and agentic behaviors. These insights serve to inform policymakers, developers, and researchers on the compliance and AI governance in the society with increasing algorithmic agencies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.20301v2">Voice Privacy from an Attribute-based Perspective</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-03-19T09:53:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mehtab Ur Rahman, Martha Larson, Cristian Tejedor-Garcia</p>
    <p><b>Summary:</b> Voice privacy approaches that preserve the anonymity of speakers modify speech in an attempt to break the link with the true identity of the speaker. Current benchmarks measure speaker protection based on signal-to-signal comparisons. In this paper, we introduce an attribute-based perspective, where we measure privacy protection in terms of comparisons between sets of speaker attributes. First, we analyze privacy impact by calculating speaker uniqueness for ground truth attributes, attributes inferred on the original speech, and attributes inferred on speech protected with standard anonymization. Next, we examine a threat scenario involving only a single utterance per speaker and calculate attack error rates. Overall, we observe that inferred attributes still present a risk despite attribute inference errors. Our research points to the importance of considering both attribute-related threats and protection mechanisms in future voice privacy research.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.18377v2">PlanTwin: Privacy-Preserving Planning Abstractions for Cloud-Assisted LLM Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2026-03-19T00:32:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guangsheng Yu, Qin Wang, Rui Lang, Shuai Su, Xu Wang</p>
    <p><b>Summary:</b> Cloud-hosted large language models (LLMs) have become the de facto planners in agentic systems, coordinating tools and guiding execution over local environments. In many deployments, however, the environment being planned over is private, containing source code, files, credentials, and metadata that cannot be exposed to the cloud. Existing solutions address adjacent concerns, such as execution isolation, access control, or confidential inference, but they do not control what cloud planners observe during planning: within the permitted scope, \textit{raw environment state is still exposed}.
  We introduce PlanTwin, a privacy-preserving architecture for cloud-assisted planning without exposing raw local context. The key idea is to project the real environment into a \textit{planning-oriented digital twin}: a schema-constrained and de-identified abstract graph that preserves planning-relevant structure while removing reconstructable details. The cloud planner operates solely on this sanitized twin through a bounded capability interface, while a local gatekeeper enforces safety policies and cumulative disclosure budgets. We further formalize the privacy-utility trade-off as a capability granularity problem, define architectural privacy goals using $(k,δ)$-anonymity and $ε$-unlinkability, and mitigate compositional leakage through multi-turn disclosure control.
  We implement PlanTwin as middleware between local agents and cloud planners and evaluate it on 60 agentic tasks across ten domains with four cloud planners. PlanTwin achieves full sensitive-item non-disclosure (SND = 1.0) while maintaining planning quality close to full-context systems: three of four planners achieve PQS $> 0.79$, and the full pipeline incurs less than 2.2\% utility loss.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.18254v1">Computation-Utility-Privacy Tradeoffs in Bayesian Estimation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computational Complexity-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2026-03-18T20:20:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sitan Chen, Jingqiu Ding, Mahbod Majid, Walter McKelvie</p>
    <p><b>Summary:</b> Bayesian methods lie at the heart of modern data science and provide a powerful scaffolding for estimation in data-constrained settings and principled quantification and propagation of uncertainty. Yet in many real-world use cases where these methods are deployed, there is a natural need to preserve the privacy of the individuals whose data is being scrutinized. While a number of works have attempted to approach the problem of differentially private Bayesian estimation through either reasoning about the inherent privacy of the posterior distribution or privatizing off-the-shelf Bayesian methods, these works generally do not come with rigorous utility guarantees beyond low-dimensional settings. In fact, even for the prototypical tasks of Gaussian mean estimation and linear regression, it was unknown how close one could get to the Bayes-optimal error with a private algorithm, even in the simplest case where the unknown parameter comes from a Gaussian prior. In this work, we give the first efficient algorithms for both of these problems that achieve mean-squared error $(1+o(1))\mathrm{OPT}$ and additionally show that both tasks exhibit an intriguing computational-statistical gap. For Bayesian mean estimation, we prove that the excess risk achieved by our method is optimal among all efficient algorithms within the low-degree framework, yet is provably worse than what is achievable by an exponential-time algorithm. For linear regression, we prove a qualitatively similar lower bound. Our algorithms draw upon the privacy-to-robustness framework of arXiv:2212.05015, but with the curious twist that to achieve private Bayes-optimal estimation, we need to design sum-of-squares-based robust estimators for inherently non-robust objects like the empirical mean and OLS estimator. Along the way we also add to the sum-of-squares toolkit a new kind of constraint based on short-flat decompositions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.17902v1">Differential Privacy in Generative AI Agents: Analysis and Optimal Tradeoffs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-03-18T16:35:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ya-Ting Yang, Quanyan Zhu</p>
    <p><b>Summary:</b> Large language models (LLMs) and AI agents are increasingly integrated into enterprise systems to access internal databases and generate context-aware responses. While such integration improves productivity and decision support, the model outputs may inadvertently reveal sensitive information. Although many prior efforts focus on protecting the privacy of user prompts, relatively few studies consider privacy risks from the enterprise data perspective. Hence, this paper develops a probabilistic framework for analyzing privacy leakage in AI agents based on differential privacy. We model response generation as a stochastic mechanism that maps prompts and datasets to distributions over token sequences. Within this framework, we introduce token-level and message-level differential privacy and derive privacy bounds that relate privacy leakage to generation parameters such as temperature and message length. We further formulate a privacy-utility design problem that characterizes optimal temperature selection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.18097v1">One Key Good, L Keys Better: List Decoding Meets Quantum Privacy Amplification</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-18T10:37:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Prateek P. Kulkarni</p>
    <p><b>Summary:</b> We introduce list privacy amplification (LPA), a relaxation of the final step of quantum key distribution (QKD) in which Alice and Bob extract a list of $L$ candidate keys from a raw string correlated with an eavesdropper Eve, with the guarantee that at least one key is perfectly secret while Eve cannot identify which. This parallels list decoding in error-correcting codes: relaxing unique decoding to list decoding increases the decoding radius; analogously, list extraction increases achievable key length beyond the standard quantum leftover hash lemma (QLHL). Within the abstract cryptography framework, we formalise LPA and prove the \emph{Quantum List Leftover Hash Lemma} (QLLHL): an $L$-list of $\ell$-bit keys can be extracted from an $n$-bit source with smooth min-entropy $k$ iff \[ \ell \le k + \log L - 2\log(1/ε) - 3, \] yielding a tight additive $\log L$ gain over QLHL. This gain arises because the index of the secure key is chosen after hashing and hidden from Eve, effectively contributing $\log L$ bits of entropy. Applying QLLHL to BB84-type QKD, a list size $L = 2^{αn'}$ increases the tolerable phase-error threshold from $h^{-1}(1 - h(e_b))$ to $h^{-1}(1 - h(e_b) + α)$, exceeding the standard $\approx 11\%$ bound for any $α> 0$. We prove tightness via a matching intercept-resend attack, establish composability with Wegman--Carter authentication, and present two constructions: a polynomial inner-product hash over $\mathbb{F}_{2^m}$ and a Toeplitz-based variant, running in $O(nL)$ and $O(nL \log n)$ time.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.18080v1">Growing Alphabets Do Not Automatically Amplify Shuffle Privacy: Obstruction, Estimation Bounds, and Optimal Mechanism Design</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-03-18T07:46:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alex Shvets</p>
    <p><b>Summary:</b> We study neighboring shuffle experiments for epsilon_0-LDP channels along growing alphabets d -> infinity, and optimal mechanism design for frequency estimation under a canonical pairwise chi-squared budget.
  On the privacy side, we prove an exact compression theorem: the shuffled histogram experiment depends only on the pushforward law of the pairwise likelihood ratio. We establish a sharp universal bound chi^2 <= (e^{epsilon_0}-1)^2/e^{epsilon_0}, construct explicit obstruction families for which the shuffled privacy curve equals binary randomized response for all d, and prove a sharp diluting/persistent dichotomy.
  On the estimation side, we prove a universal lower bound of order (d-1)/(n chi_*(W)) via Cramer-Rao and Assouad arguments, and show that symmetrization to equivariant channels is WLOG.
  On the design side, we show calibrated GRR is not optimal. The optimal mechanism is an augmented GRR: fraction p of users applies aggressive GRR with lambda_* = sqrt(d-1), the rest sends a null symbol. This thinning principle is specific to shuffle and has no local-DP counterpart. For low budget 0 < C <= C_*(d), augmented GRR is optimal among all permutation-equivariant channels. GRR is also the unique optimizer within the subset-selection family.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.17217v1">Anonymous-by-Construction: An LLM-Driven Framework for Privacy-Preserving Text</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-03-17T23:46:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Federico Albanese, Pablo Ronco, Nicolás D'Ippolito</p>
    <p><b>Summary:</b> Responsible use of AI demands that we protect sensitive information without undermining the usefulness of data, an imperative that has become acute in the age of large language models. We address this challenge with an on-premise, LLM-driven substitution pipeline that anonymizes text by replacing personally identifiable information (PII) with realistic, type-consistent surrogates. Executed entirely within organizational boundaries using local LLMs, the approach prevents data egress while preserving fluency and task-relevant semantics.
  We conduct a systematic, multi-metric, cross-technique evaluation on the Action-Based Conversation Dataset, benchmarking against industry standards (Microsoft Presidio and Google DLP) and a state-of-the-art approach (ZSTS, in redaction-only and redaction-plus-substitution variants). Our protocol jointly measures privacy, semantic utility, and trainability under privacy via a lifecycle-ready criterion obtained by fine-tuning a compact encoder (BERT+LoRA) on sanitized text. In addition, we assess agentic Q&A performance by inserting an on-premise anonymization layer before the answering LLM and evaluating the quality of its responses. This intermediate, type-preserving substitution stage ensures that no sensitive content is exposed to third-party APIs, enabling responsible deployment of Q\&A agents without compromising confidentiality.
  Our method attains state-of-the-art privacy, minimal topical drift, strong factual utility, and low trainability loss, outperforming rule-based approaches and named-entity recognition (NER) baselines and ZSTS variants on the combined privacy--utility--trainability frontier. These results show that local LLM substitution yields anonymized corpora that are both responsible to use and operationally valuable: safe for agentic pipelines and suitable for downstream fine-tuning with limited degradation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.17109v1">SENSE: Efficient EEG-to-Text via Privacy-Preserving Semantic Retrieval</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-03-17T19:59:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Akshaj Murhekar, Christina Liu, Abhijit Mishra, Shounak Roychowdhury, Jacek Gwizdka</p>
    <p><b>Summary:</b> Decoding brain activity into natural language is a major challenge in AI with important applications in assistive communication, neurotechnology, and human-computer interaction. Most existing Brain-Computer Interface (BCI) approaches rely on memory-intensive fine-tuning of Large Language Models (LLMs) or encoder-decoder models on raw EEG signals, resulting in expensive training pipelines, limited accessibility, and potential exposure of sensitive neural data. We introduce SENSE (SEmantic Neural Sparse Extraction), a lightweight and privacy-preserving framework that translates non-invasive electroencephalography (EEG) into text without LLM fine-tuning. SENSE decouples decoding into two stages: on-device semantic retrieval and prompt-based language generation. EEG signals are locally mapped to a discrete textual space to extract a non-sensitive Bag-of-Words (BoW), which conditions an off-the-shelf LLM to synthesize fluent text in a zero-shot manner. The EEG-to-keyword module contains only ~6M parameters and runs fully on-device, ensuring raw neural signals remain local while only abstract semantic cues interact with language models. Evaluated on a 128-channel EEG dataset across six subjects, SENSE matches or surpasses the generative quality of fully fine-tuned baselines such as Thought2Text while substantially reducing computational overhead. By localizing neural decoding and sharing only derived textual cues, SENSE provides a scalable and privacy-aware retrieval-augmented architecture for next-generation BCIs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.17061v1">Collecting Prosody in the Wild: A Content-Controlled, Privacy-First Smartphone Protocol and Empirical Evaluation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> 
  <p><b>Published on:</b> 2026-03-17T18:49:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Timo K. Koch, Florian Bemmann, Ramona Schoedel, Markus Buehner, Clemens Stachl</p>
    <p><b>Summary:</b> Collecting everyday speech data for prosodic analysis is challenging due to the confounding of prosody and semantics, privacy constraints, and participant compliance. We introduce and empirically evaluate a content-controlled, privacy-first smartphone protocol that uses scripted read-aloud sentences to standardize lexical content (including prompt valence) while capturing natural variation in prosodic delivery. The protocol performs on-device prosodic feature extraction, deletes raw audio immediately, and transmits only derived features for analysis. We deployed the protocol in a large study (N = 560; 9,877 recordings), evaluated compliance and data quality, and conducted diagnostic prediction tasks on the extracted features, predicting speaker sex and concurrently reported momentary affective states (valence, arousal). We discuss implications and directions for advancing and deploying the protocol.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.16780v1">Quantum-Enabled Probabilistic Optimal Power Flow with Built-in Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E">
  <p><b>Published on:</b> 2026-03-17T16:56:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuji Cao, Tongxin Li, Yue Chen</p>
    <p><b>Summary:</b> Quantum computing has been regarded as a promising approach to accelerate power system optimization. However, challenges such as limited qubits and inherent noise hinder their widespread adoption in power systems. In this paper, we propose a qubit-efficient framework for solving a crucial power system optimization problem, the probabilistic optimal power flow (POPF). We demonstrate that quantum noise, traditionally viewed as a drawback, can in fact be leveraged to provide a built-in differential privacy (DP) guarantee. Specifically, we first linearize POPF into a multi-parametric linear program (MP-LP) with renewable uncertainties being the parameters. This decomposes the parameter space into critical regions with precomputed solution maps. Second, a variational quantum circuit (VQC) classifies the critical region based on each uncertainty realization and then recovers the final solution. In this way, the required qubits scale with the uncertain parameters instead of the network size, with only 5 qubits versus 600+ for direct quantum OPF in a 69-bus system. Moreover, we prove the depolarizing noise of VQC provides DP guarantees and characterize the privacy-cost tradeoff. Case studies validate the proposed VQC achieves 2.1$\times$ smaller privacy budgets compared to its classical counterpart. At matched privacy levels, the VQC also maintains lower infeasibility and prediction error.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.15901v1">Federated Learning for Privacy-Preserving Medical AI</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-03-16T20:46:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tin Hoang</p>
    <p><b>Summary:</b> This dissertation investigates privacy-preserving federated learning for Alzheimer's disease classification using three-dimensional MRI data from the Alzheimer's Disease Neuroimaging Initiative (ADNI). Existing methodologies often suffer from unrealistic data partitioning, inadequate privacy guarantees, and insufficient benchmarking, limiting their practical deployment in healthcare. To address these gaps, this research proposes a novel site-aware data partitioning strategy that preserves institutional boundaries, reflecting real-world multi-institutional collaborations and data heterogeneity. Furthermore, an Adaptive Local Differential Privacy (ALDP) mechanism is introduced, dynamically adjusting privacy parameters based on training progression and parameter characteristics, thereby significantly improving the privacy-utility trade-off over traditional fixed-noise approaches. Systematic empirical evaluation across multiple client federations and privacy budgets demonstrated that advanced federated optimisation algorithms, particularly FedProx, could equal or surpass centralised training performance while ensuring rigorous privacy protection. Notably, ALDP achieved up to 80.4% accuracy in a two-client configuration, surpassing fixed-noise Local DP by 5-7 percentage points and demonstrating substantially greater training stability. The comprehensive ablation studies and benchmarking establish quantitative standards for privacy-preserving collaborative medical AI, providing practical guidelines for real-world deployment. This work thereby advances the state-of-the-art in federated learning for medical imaging, establishing both methodological foundations and empirical evidence necessary for future privacy-compliant AI adoption in healthcare.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.15842v1">Informationally Compressive Anonymization: Non-Degrading Sensitive Input Protection for Privacy-Preserving Supervised Machine Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-03-16T19:17:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jeremy J Samuelson</p>
    <p><b>Summary:</b> Modern machine learning systems increasingly rely on sensitive data, creating significant privacy, security, and regulatory risks that existing privacy-preserving machine learning (ppML) techniques, such as Differential Privacy (DP) and Homomorphic Encryption (HE), address only at the cost of degraded performance, increased complexity, or prohibitive computational overhead. This paper introduces Informationally Compressive Anonymization (ICA) and the VEIL architecture, a privacy-preserving ML framework that achieves strong privacy guarantees through architectural and mathematical design rather than noise injection or cryptography. ICA embeds a supervised, multi-objective encoder within a trusted Source Environment to transform raw inputs into low-dimensional, task-aligned latent representations, ensuring that only irreversibly anonymized vectors are exported to untrusted Training and Inference Environments. The paper rigorously proves that these encodings are structurally non-invertible using topological and information-theoretic arguments, showing that inversion is logically impossible, even under idealized attacker assumptions, and that, in realistic deployments, the attackers conditional entropy over the original data diverges, driving reconstruction probability to zero. Unlike prior autoencoder-based ppML approaches, ICA preserves predictive utility by aligning representation learning with downstream supervised objectives, enabling low-latency, high-performance ML without gradient clipping, noise budgets, or encryption at inference time. The VEIL architecture enforces strict trust boundaries, supports scalable multi-region deployment, and naturally aligns with privacy-by-design regulatory frameworks, establishing a new foundation for enterprise ML that is secure, performant, and safe by construction, even in the face of post-quantum threats.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.15609v1">Differential Privacy for Network Connectedness Indices</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B"> 
  <p><b>Published on:</b> 2026-03-16T17:57:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tom A. Rutter, Yuxin Liu, M. Amin Rahimian</p>
    <p><b>Summary:</b> Researchers increasingly use data on social and economic networks to study a range of social science questions, but releasing statistics derived from networks can raise significant privacy concerns. We show how to release network connectedness indices that quantify assortative mixing across node attributes under edge-adjacent differential privacy. Standard privacy techniques perform poorly in this setting both because connectedness indices have high global sensitivity and because a single node's attribute can potentially be an input to connectedness in thousands of cells, leading to poor composition. Our method, which is straightforward to apply, first adds noise to node attributes, then analytically debiases downstream statistics, and finally applies a second layer of noise to protect the presence or absence of individual edges. We prove consistency and asymptotic normality of our estimators for both discrete and continuous labels and show our method works well in simulations and on real networks with as few as 200 nodes collected by social scientists.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.15705v1">Remarks on the Relevance of Privacy Expectations for Default Opt-out Settings</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-03-16T12:48:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sebastian Zimmeck</p>
    <p><b>Summary:</b> Over the past few years an increasing number of states in the US have adopted new privacy laws. The majority of these laws require compliance with universal opt-out mechanisms (UOOMs), which allow consumers to send legally binding opt-out signals. However, a number of laws generally do not allow UOOMs to be enabled by default. While some laws exempt privacy-protective software from this prohibition, the exemption does not apply to pre-installed software, e.g., a privacy-protective web browser bundled with an operating system. The reason for not allowing default opt-out settings for pre-installed software is to ensure that settings reflect consumers' "affirmative, freely given, and unambiguous choice," as, for example, the Colorado Privacy Act (CPA) is putting it. However, prohibiting vendors of privacy-protective software from turning on UOOMs by default can force them into committing unfair or deceptive acts or practices under the FTC Act and equivalent state laws. Thus, whether UOOMs can be turned on by default on pre-installed software should depend on consumers' privacy expectations. For pre-installed software that is creating a reasonable expectation for consumers that their privacy will be protected, the simple use of such software should be considered a valid choice for enabling UOOMs. In such software a turned-on UOOM is not a "default setting" but rather the software's inherent behavior that a consumer expects and chooses through its use. This interpretation of consumer choice is preferable under the CPA and similar laws as it grounds the notice and choice principle in the privacy expectations of consumers and enables companies to compete on better privacy for consumers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.15023v3">SIMD-PAC-DB: Pretty Performant PAC Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2026-03-16T09:24:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ilaria Battiston, Dandan Yuan, Xiaochen Zhu, Peter Boncz</p>
    <p><b>Summary:</b> This work presents a highly optimized implementation of PAC-DB, a recent and promising database privacy model. We prove that our SIMD-PAC-DB can compute the same privatized answer with just a single query, instead of the 128 stochastic executions against different 50% database sub-samples needed by the original PAC-DB. Our key insight is that every bit of a hashed primary key can be seen to represent membership of such a sub-sample. We present new algorithms for approximate computation of stochastic aggregates based on these hashes, which, thanks to their SIMD-friendliness, run up to 40x faster than scalar equivalents. We release an open-source DuckDB community extension which includes a rewriter that PAC-privatizes arbitrary SQL queries. Our experiments on TPC-H, Clickbench, and SQLStorm evaluate thousands of queries in terms of performance and utility, significantly advancing the ease of use and functionality of privacy-aware data systems in practice.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.14994v2">DP-S4S: Accurate and Scalable Select-Join-Aggregate Query Processing with User-Level Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-16T08:58:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuan Qiu, Xiaokui Xiao, Yin Yang</p>
    <p><b>Summary:</b> Answering Select-Join-Aggregate queries with DP is a fundamental problem with important applications in various domains. The current SOTA methods ensure user-level DP (i.e., the adversary cannot infer the presence or absence of any given individual user with high confidence) and achieve instance-optimal accuracy on the query results. However, these solutions involve solving expensive optimization programs, which may incur prohibitive computational overhead for large databases.
  One promising direction to achieve scalability is through sampling, which provides a tunable trade-off between result utility and computational costs. However, applying sampling to differentially private SJA processing is a challenge for two reasons. First, it is unclear what to sample, in order to achieve the best accuracy within a given computational budget. Second, prior solutions were not designed with sampling in mind, and their mathematical tool chains are not sampling-friendly. To our knowledge, the only known solution that applies sampling to private SJA processing is S&E, a recent proposal that (i) samples users and (ii) combines sampling directly with existing solutions to enforce DP. We show that both are suboptimal designs; consequently, even with a relatively high sample rate, the error incurred by S&E can be 10x higher than the underlying DP mechanism without sampling.
  Motivated by this, we propose Differentially Private Sampling for Scale (DP-S4S), a novel mechanism that addresses the above challenges by (i) sampling aggregation units instead of users, and (ii) laying the mathematical foundation for SJA processing under RDP, which composes more easily with sampling. Further, DP-S4S can answer both scalar and vector SJA queries. Extensive experiments on real data demonstrate that DP-S4S enables scalable SJA processing on large datasets under user-level DP, while maintaining high result utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.14778v1">$p^2$RAG: Privacy-Preserving RAG Service Supporting Arbitrary Top-$k$ Retrieval</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-03-16T03:19:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yulong Ming, Mingyue Wang, Jijia Yang, Cong Wang, Xiaohua Jia</p>
    <p><b>Summary:</b> Retrieval-Augmented Generation (RAG) enables large language models to use external knowledge, but outsourcing the RAG service raises privacy concerns for both data owners and users. Privacy-preserving RAG systems address these concerns by performing secure top-$k$ retrieval, which typically is secure sorting to identify relevant documents. However, existing systems face challenges supporting arbitrary $k$ due to their inability to change $k$, new security issues, or efficiency degradation with large $k$. This is a significant limitation because modern long-context models generally achieve higher accuracy with larger retrieval sets. We propose $p^2$RAG, a privacy-preserving RAG service that supports arbitrary top-$k$ retrieval. Unlike existing systems, $p^2$RAG avoids sorting candidate documents. Instead, it uses an interactive bisection method to determine the set of top-$k$ documents. For security, $p^2$RAG uses secret sharing on two semi-honest non-colluding servers to protect the data owner's database and the user's prompt. It enforces restrictions and verification to defend against malicious users and tightly bound the information leakage of the database. The experiments show that $p^2$RAG is 3--300$\times$ faster than the state-of-the-art PRAG for $k = 16$--$1024$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.14756v1">Towards Privacy-Preserving Machine Translation at the Inference Stage: A New Task and Benchmark</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-03-16T02:41:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wei Shao, Lemao Liu, Yinqiao Li, Guoping Huang, Shuming Shi, Linqi Song</p>
    <p><b>Summary:</b> Current online translation services require sending user text to cloud servers, posing a risk of privacy leakage when the text contains sensitive information. This risk hinders the application of online translation services in privacy-sensitive scenarios. One way to mitigate this risk for online translation services is introducing privacy protection mechanisms targeting the inference stage of translation models. However, compared to subfields of NLP like text classification and summarization, the machine translation research community has limited exploration of privacy protection during the inference stage. There is no clearly defined privacy protection task for the inference stage, dedicated evaluation datasets and metrics, and reference benchmark methods. The absence of these elements has seriously constrained researchers' in-depth exploration of this direction. To bridge this gap, this paper proposes a novel "Privacy-Preserving Machine Translation" (PPMT) task, aiming to protect the private information in text during the model inference stage. For this task, we constructed three benchmark test datasets, designed corresponding evaluation metrics, and proposed a series of benchmark methods as a starting point for this task. The definition of privacy is complex and diverse. Considering that named entities often contain a large amount of personal privacy and commercial secrets, we have focused our research on protecting only the named entity's privacy in the text. We expect this research work will provide a new perspective and a solid foundation for the privacy protection problem in machine translation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.14606v1">Collective Grid: Privacy-Preserved Multi-Operator Energy Sharing Optimization via Federated Energy Prediction</a></h3>
  
  <p><b>Published on:</b> 2026-03-15T21:02:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Meysam Masoudi, Tahar Zanouda, Milad Ganjalizadeh, Cicek Cavdar</p>
    <p><b>Summary:</b> Electricity consumption in mobile networks is increasing with the continued 5G expansion, rising data traffic, and more complex infrastructures. However, energy management is often handled independently by each mobile network operator (MNO), leading to limited coordination and missed opportunities for collective efficiency gains. To address this gap, we propose a privacy-preserving framework for automated energy infrastructure sharing among co-located MNOs. Our framework consists of three modules: (i) a federated learning-based privacy-preserving site energy consumption forecasting module, (ii) an orchestration module in which a mixed-integer linear program is solved to schedule energy purchases from the grid, utilization of renewable sources, and shared battery charging or discharging, based on real-time prices, forecasts, and battery state, and (iii) an energy source selection module which handles the selection of cost-effective power sources and storage actions based on predicted demand across MNOs for the next control window. Using data from operational networks, our experiments confirm that the proposed solution substantially reduces operational costs and outperforms non-sharing baselines, with gains that increase as network density rises in 5G-and-beyond deployments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.14265v1">MedPriv-Bench: Benchmarking the Privacy-Utility Trade-off of Large Language Models in Medical Open-End Question Answering</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2026-03-15T07:47:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shaowei Guan, Yu Zhai, Hin Chi Kwok, Jiawei Du, Xinyu Feng, Jing Li, Harry Qin, Vivian Hui</p>
    <p><b>Summary:</b> Recent advances in Retrieval-Augmented Generation (RAG) have enabled large language models (LLMs) to ground outputs in clinical evidence. However, connecting LLMs with external databases introduces the risk of contextual leakage: a subtle privacy threat where unique combinations of medical details enable patient re-identification even without explicit identifiers. Current benchmarks in healthcare heavily focus on accuracy, ignoring such privacy issues, despite strict regulations like Health Insurance Portability and Accountability Act (HIPAA) and General Data Protection Regulation (GDPR). To fill this gap, we present MedPriv-Bench, the first benchmark specifically designed to jointly evaluate privacy preservation and clinical utility in medical open-ended question answering. Our framework utilizes a multi-agent, human-in-the-loop pipeline to synthesize sensitive medical contexts and clinically relevant queries that create realistic privacy pressure. We establish a standardized evaluation protocol leveraging a pre-trained RoBERTa-Natural Language Inference (NLI) model as an automated judge to quantify data leakage, achieving an average of 85.9% alignment with human experts. Through an extensive evaluation of 9 representative LLMs, we demonstrate a pervasive privacy-utility trade-off. Our findings underscore the necessity of domain-specific benchmarks to validate the safety and efficacy of medical AI systems in privacy-sensitive environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.14208v1">Tracing Your Account: A Gradient-Aware Dynamic Window Graph Framework for Ethereum under Privacy-Preserving Services</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computational Engineering, Finance, and Science-5BC0EB">
  <p><b>Published on:</b> 2026-03-15T03:55:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Miao Shuyi, Qiu Wangjie, Tu Xiaofan, Li Yunze, Wen Yongxin, Zheng Zhiming</p>
    <p><b>Summary:</b> With the rapid advancement of Web 3.0 technologies, public blockchain platforms are witnessing the emergence of novel services designed to enhance user privacy and anonymity. However, the powerful untraceability features inherent in these services inadvertently make them attractive tools for criminals seeking to launder illicit funds. Notably, existing de-anonymization methods face three major challenges when dealing with such transactions: highly homogenized transactional semantics, limited ability to model temporal discontinuities, and insufficient consideration of structural sparsity in account association graphs. To address these, we propose GradWATCH, designed to track anonymous accounts in Ethereum privacy-preserving services. Specifically, we first design a learnable account feature mapping module to extract informative transactional semantics from raw on-chain data. We then incorporate transaction relations into the account association graph to alleviate the adverse effects of structural sparsity. To capture temporal evolution, we further propose an edge-aware sliding-window mechanism that propagates and updates gradients at three granularities. Finally, we identify accounts controlled by the same entity by measuring their embedding distances in the learned representation space. Experimental results show that even under the conditions of unbalanced labels and sparse transactions, GradWATCH still achieves significant performance gains, with relative improvements ranging from 1.62% to 15. 22% in the MRR and from 3. 85% to 7. 31% in the F_1.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.13978v1">When Visual Privacy Protection Meets Multimodal Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-03-14T15:15:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaofei Hui, Qian Wu, Haoxuan Qu, Majid Mirmehdi, Hossein Rahmani, Jun Liu</p>
    <p><b>Summary:</b> The emergence of Multimodal Large Language Models (MLLMs) and the widespread usage of MLLM cloud services such as GPT-4V raised great concerns about privacy leakage in visual data. As these models are typically deployed in cloud services, users are required to submit their images and videos, posing serious privacy risks. However, how to tackle such privacy concerns is an under-explored problem. Thus, in this paper, we aim to conduct a new investigation to protect visual privacy when enjoying the convenience brought by MLLM services. We address the practical case where the MLLM is a "black box", i.e., we only have access to its input and output without knowing its internal model information. To tackle such a challenging yet demanding problem, we propose a novel framework, in which we carefully design the learning objective with Pareto optimality to seek a better trade-off between visual privacy and MLLM's performance, and propose critical-history enhanced optimization to effectively optimize the framework with the black-box MLLM. Our experiments show that our method is effective on different benchmarks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.19314v1">DPxFin: Adaptive Differential Privacy for Anti-Money Laundering Detection via Reputation-Weighted Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-14T08:34:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Renuga Kanagavelu, Manjil Nepal, Ning Peiyan, Cai Kangning, Xu Jiming, Fei Gao, Yong Liu, Goh Siow Mong Rick, Qingsong Wei</p>
    <p><b>Summary:</b> In the modern financial system, combating money laundering is a critical challenge complicated by data privacy concerns and increasingly complex fraud transaction patterns. Although federated learning (FL) is a promising problem-solving approach as it allows institutions to train their models without sharing their data, it has the drawback of being prone to privacy leakage, specifically in tabular data forms like financial data. To address this, we propose DPxFin, a novel federated framework that integrates reputation-guided adaptive differential privacy. Our approach computes client reputation by evaluating the alignment between locally trained models and the global model. Based on this reputation, we dynamically assign differential privacy noise to client updates, enhancing privacy while maintaining overall model utility. Clients with higher reputations receive lower noise to amplify their trustworthy contributions, while low-reputation clients are allocated stronger noise to mitigate risk. We validate DPxFin on the Anti-Money Laundering (AML) dataset under both IID and non-IID settings using Multi Layer Perceptron (MLP). Experimental analysis established that our approach has a more desirable trade-off between accuracy and privacy than those of traditional FL and fixed-noise Differential Privacy (DP) baselines, where performance improvements were consistent, even though on a modest scale. Moreover, DPxFin does withstand tabular data leakage attacks, proving its effectiveness under real-world financial conditions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.13747v1">Designing for Understanding: How Interface-Level Consent Designs Shape Attention and Understanding in Privacy Disclosures</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-03-14T04:35:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wei Xiao, Mengke Wu, Yeeun Jo</p>
    <p><b>Summary:</b> Privacy policies are intended to support informed consent, yet users rarely read them fully. This study examines how common privacy policy interface structures influence attention allocation, reading behavior, and perceived experience. Using eye-tracking and post-task surveys, we compared three interface designs: continuous scrolling text, collapsible sections, and collapsible sections with brief previews. Results show that interface structure systematically shaped how users allocated attention and navigated policy content, but did not uniformly improve comprehension. Guided layouts supported more efficient and coherent reading patterns, whereas more interactive designs elicited higher perceived engagement and satisfaction. Importantly, comprehension was closely linked to sustained attention rather than interface type alone. These findings highlight the limits of interface-centered consent approaches and suggest that effective consent design must account for attention dynamics and selective engagement, rather than assuming that improved layout alone ensures understanding.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.13728v2">Bodhi VLM: Privacy-Alignment Modeling for Hierarchical Visual Representations in Vision Backbones and VLM Encoders via Bottom-Up and Top-Down Feature Search</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-14T03:11:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bo Ma, Wei Qi Yan, Jinsong Wu</p>
    <p><b>Summary:</b> Learning systems that preserve privacy often inject noise into hierarchical visual representations; a central challenge is to \emph{model} how such perturbations align with a declared privacy budget in a way that is interpretable and applicable across vision backbones and vision--language models (VLMs). We propose \emph{Bodhi VLM}, a \emph{privacy-alignment modeling} framework for \emph{hierarchical neural representations}: it (1) links sensitive concepts to layer-wise grouping via NCP and MDAV-based clustering; (2) locates sensitive feature regions using bottom-up (BUA) and top-down (TDA) strategies over multi-scale representations (e.g., feature pyramids or vision-encoder layers); and (3) uses an Expectation-Maximization Privacy Assessment (EMPA) module to produce an interpretable \emph{budget-alignment signal} by comparing the fitted sensitive-feature distribution to an evaluator-specified reference (e.g., Laplace or Gaussian with scale $c/ε$). The output is reference-relative and is \emph{not} a formal differential-privacy estimator. We formalize BUA/TDA over hierarchical feature structures and validate the framework on object detectors (YOLO, PPDPTS, DETR) and on the \emph{visual encoders} of VLMs (CLIP, LLaVA, BLIP). BUA and TDA yield comparable deviation trends; EMPA provides a stable alignment signal under the reported setups. We compare with generic discrepancy baselines (Chi-square, K-L, MMD) and with task-relevant baselines (MomentReg, NoiseMLE, Wass-1). Results are reported as mean$\pm$std over multiple seeds with confidence intervals in the supplementary materials. This work contributes a learnable, interpretable modeling perspective for privacy-aligned hierarchical representations rather than a post hoc audit only. Source code: \href{https://github.com/mabo1215/bodhi-vlm.git}{Bodhi-VLM GitHub repository}</p>
  </details>
</div>



<h2>2026-04</h2>

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
  <h3><a href="http://arxiv.org/abs/2604.01487v1">AgentSocialBench: Evaluating Privacy Risks in Human-Centered Agentic Social Networks</a></h3>
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

