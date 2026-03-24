
<h2>2026-03</h2>

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
  <h3><a href="http://arxiv.org/abs/2603.21387v1">Knowledge Priors for Identity-Disentangled Open-Set Privacy-Preserving Video FER</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-03-22T20:18:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Feng Xu, Xun Li, Lars Petersson, Yulei Sui, David Ahmedt Aristizabal, Dadong Wang</p>
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
  <h3><a href="http://arxiv.org/abs/2603.21106v1">Tracing Users' Privacy Concerns Across the Lifecycle of a Romantic AI Companion</a></h3>
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
  <h3><a href="http://arxiv.org/abs/2603.20301v1">Voice Privacy from an Attribute-based Perspective</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-03-19T09:53:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mehtab Ur Rahman, Martha Larson, Cristian Tejedor García</p>
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


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.13667v1">TSDCRF: Balancing Privacy and Multi-Object Tracking via Time-Series CRF and Normalized Control Penalty</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-03-14T00:27:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bo Ma, Jinsong Wu, Weiqi Yan</p>
    <p><b>Summary:</b> Multi-object tracking in video often requires appearance or location cues that can reveal sensitive identity information, while adding privacy-preserving noise typically disrupts cross-frame association and causes ID switches or target loss. We propose TSDCRF, a plug-in refinement framework that balances privacy and tracking by combining three components: (i) $(\varepsilon,δ)$-differential privacy via calibrated Gaussian noise on sensitive regions under a configurable privacy budget; (ii) a Normalized Control Penalty (NCP) that down-weights unstable or conflicting class predictions before noise injection to stabilize association; and (iii) a time-series dynamic conditional random field (DCRF) that enforces temporal consistency and corrects trajectory deviation after noise, mitigating ID switches and resilience to trajectory hijacking. The pipeline is agnostic to the choice of detector and tracker (e.g., YOLOv4 and DeepSORT). We evaluate on MOT16, MOT17, Cityscapes, and KITTI. Results show that TSDCRF achieves a better privacy--utility trade-off than white noise and prior methods (NTPD, PPDTSA): lower KL-divergence shift, lower tracking RMSE, and improved robustness under trajectory hijacking while preserving privacy. Source code in https://github.com/mabo1215/TSDCRF.git</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.13655v1">Privacy Preserving Topic-wise Sentiment Analysis of the Iran Israel USA Conflict Using Federated Transformer Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-03-13T23:41:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Md Saiful Islam, Tanjim Taharat Aurpa, Sharad Hasan, Farzana Akter</p>
    <p><b>Summary:</b> The recent escalation of the Iran Israel USA conflict in 2026 has triggered widespread global discussions across social media platforms. As people increasingly use these platforms for expressing opinions, analyzing public sentiment from these discussions can provide valuable insights into global public perception. This study aims to analyze global public sentiment regarding the Iran Israel USA conflict by mining user-generated comments from YouTube news channels. The work contributes to public opinion analysis by introducing a privacy preserving framework that combines topic wise sentiment analysis with modern deep learning techniques and Federated Learning. To achieve this, approximately 19,000 YouTube comments were collected from major international news channels and preprocessed to remove noise and normalize text. Sentiment labels were initially generated using the VADER sentiment analyzer and later validated through manual inspection to improve reliability. Latent Dirichlet Allocation (LDA) was applied to identify key discussion topics related to the conflict. Several transformer-based models, including BERT, RoBERTa, XLNet, DistilBERT, ModernBERT, and ELECTRA, were fine tuned for sentiment classification. The best-performing model was further integrated into a federated learning environment to enable distributed training by preserving user data privacy. Additionally, Explainable Artificial Intelligence (XAI) techniques using SHAP were applied to interpret model predictions and identify influential words affecting sentiment classification. Experimental results demonstrate that transformer models perform effectively, and among them, ELECTRA achieved the best performance with 91.32% accuracy. The federated learning also maintained strong performance while preserving privacy, achieving 89.59% accuracy in a two client configuration.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.13617v1">Privacy-Preserving Federated Fraud Detection in Payment Transactions with NVIDIA FLARE</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computational Engineering, Finance, and Science-5BC0EB">
  <p><b>Published on:</b> 2026-03-13T21:50:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Holger R. Roth, Sarthak Tickoo, Mayank Kumar, Isaac Yang, Andrew Liu, Amit Varshney, Sayani Kundu, Iustina Vintila, Peter Madsgaard, Juraj Milcak, Chester Chen, Yan Cheng, Andrew Feng, Jeff Savio, Vikram Singh, Craig Stancill, Gloria Wan, Evan Powell, Anwar Ul Haq, Sudhir Upadhyay, Jisoo Lee</p>
    <p><b>Summary:</b> Fraud-related financial losses continue to rise, while regulatory, privacy, and data-sovereignty constraints increasingly limit the feasibility of centralized fraud detection systems. Federated Learning (FL) has emerged as a promising paradigm for enabling collaborative model training across institutions without sharing raw transaction data. Yet, its practical effectiveness under realistic, non-IID financial data distributions remains insufficiently validated. In this work, we present a multi-institution, industry-oriented proof-of-concept study evaluating federated anomaly detection for payment transactions using the NVIDIA FLARE framework. We simulate a realistic federation of heterogeneous financial institutions, each observing distinct fraud typologies and operating under strict data isolation. Using a deep neural network trained via federated averaging (FedAvg), we demonstrate that federated models achieve a mean F1-score of 0.903 - substantially outperforming locally trained models (0.643) and closely approaching centralized training performance (0.925), while preserving full data sovereignty. We further analyze convergence behavior, showing that strong performance is achieved within 10 federated communication rounds, highlighting the operational viability of FL in latency- and cost-sensitive financial environments. To support deployment in regulated settings, we evaluate model interpretability using Shapley-based feature attribution and confirm that federated models rely on semantically coherent, domain-relevant decision signals. Finally, we incorporate sample-level differential privacy via DP-SGD and demonstrate favorable privacy-utility trade-offs...</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.13570v2">Privacy-Preserving Machine Learning for IoT: A Cross-Paradigm Survey and Future Roadmap</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-13T20:19:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zakia Zaman, Praveen Gauravaram, Mahbub Hassan, Sanjay Jha, Wen Hu</p>
    <p><b>Summary:</b> The rapid proliferation of the Internet of Things has intensified demand for robust privacy-preserving machine learning mechanisms to safeguard sensitive data generated by large-scale, heterogeneous, and resource-constrained devices. Unlike centralized environments, IoT ecosystems are inherently decentralized, bandwidth-limited, and latency-sensitive, exposing privacy risks across sensing, communication, and distributed training pipelines. These characteristics render conventional anonymization and centralized protection strategies insufficient for practical deployments. This survey presents a comprehensive IoT-centric, cross-paradigm analysis of privacy-preserving machine learning. We introduce a structured taxonomy spanning perturbation-based mechanisms such as differential privacy, distributed paradigms such as federated learning, cryptographic approaches including homomorphic encryption and secure multiparty computation, and generative synthesis techniques based on generative adversarial networks. For each paradigm, we examine formal privacy guarantees, computational and communication complexity, scalability under heterogeneous device participation, and resilience against threats including membership inference, model inversion, gradient leakage, and adversarial manipulation. We further analyze deployment constraints in wireless IoT environments, highlighting trade-offs between privacy, communication overhead, model convergence, and system efficiency within next-generation mobile architectures. We also consolidate evaluation methodologies, summarize representative datasets and open-source frameworks, and identify open challenges including hybrid privacy integration, energy-aware learning, privacy-preserving large language models, and quantum-resilient machine learning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.13186v1">Learnability and Privacy Vulnerability are Entangled in a Few Critical Weights</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-13T17:20:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xingli Fang, Jung-Eun Kim</p>
    <p><b>Summary:</b> Prior approaches for membership privacy preservation usually update or retrain all weights in neural networks, which is costly and can lead to unnecessary utility loss or even more serious misalignment in predictions between training data and non-training data. In this work, we observed three insights: i) privacy vulnerability exists in a very small fraction of weights; ii) however, most of those weights also critically impact utility performance; iii) the importance of weights stems from their locations rather than their values. According to these insights, to preserve privacy, we score critical weights, and instead of discarding those neurons, we rewind only the weights for fine-tuning. We show that, through extensive experiments, this mechanism exhibits outperforming resilience in most cases against Membership Inference Attacks while maintaining utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.13444v1">Technical Case Study of Privacy-Enhancing Technologies (PETs) for Public Health</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-03-13T13:04:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Avinash Laddha, Danil Mikhailov, Uyi Stewart</p>
    <p><b>Summary:</b> We present a technical case study on the Privacy-Enhancing Technologies (PETs) for Public Health Challenge, a collaborative effort to safely leverage sensitive private sector data for social impact, specifically pandemic management. The project utilized Differential Privacy (DP) to create realistic, privacy-preserved synthetic financial transaction data, which was then combined with public health and mobility datasets. This approach successfully addressed the critical hurdle of sharing sensitive financial information for research and policy.
  The analysis demonstrated that this synthetic, DP-protected data possesses significant spatial-temporal and predictive power for public health. Key outcomes include the development of six reusable tools and frameworks supporting diagnostic nowcasting (e.g., Hotspot Detection, Pandemic Adherence Monitoring) and predictive forecasting (e.g., Mobility Analysis, Contact Matrix Estimation) for epidemiological decision-making. The study provides best practices for advancing data sharing in a privacy-compliant manner.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.12753v1">Balancing the privacy-utility trade-off: How to draw reliable conclusions from private data</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-13T07:54:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Raphaël de Fondeville</p>
    <p><b>Summary:</b> Absolute anonymization, conceived as an irreversible transformation that prevents re-identification and sensitive value disclosure, has proven to be a broken promise. Consequently, modern data protection must shift toward a privacy-utility trade-off grounded in risk mitigation. Differential Privacy (DP) offers a rigorous mathematical framework for balancing quantified disclosure risk with analytical usefulness. Nevertheless, widespread adoption remains limited, largely because effective translation of complex technical concepts, such as privacy-loss parameters, into forms meaningful to non-technical stakeholders has yet to be achieved. This difficulty arises from the inherent use of randomization: both legitimate analysts and potential adversaries must draw conclusions from uncertain observations rather than deterministic values. In this work, we propose a new interpretation of the privacy-utility trade-off based on hypothesis testing. This perspective explicitly accounts for the uncertainty introduced by randomized mechanisms in both membership inference scenarios and general data analysis. In particular, we introduce the concept of relative disclosure risk to quantify the maximum reduction in uncertainty an adversary can obtain from protected outputs, and we show that this measure is directly related to standard privacy-loss parameters. At the same time, we analyze how DP affects analytical validity by studying its impact on hypothesis tests commonly used to assess the statistical significance of empirical results. Finally, we provide practical guidance, accessible to non-experts, for navigating the privacy-utility trade-off, aiding in the selection of suitable protection mechanisms and the values for the privacy-loss parameters.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.12598v1">Neural Gate: Mitigating Privacy Risks in LVLMs via Neuron-Level Gradient Gating</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-03-13T03:03:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiangkui Cao, Jie Zhang, Meina Kan, Shiguang Shan, Xilin Chen</p>
    <p><b>Summary:</b> Large Vision-Language Models (LVLMs) have shown remarkable potential across a wide array of vision-language tasks, leading to their adoption in critical domains such as finance and healthcare. However, their growing deployment also introduces significant security and privacy risks. Malicious actors could potentially exploit these models to extract sensitive information, highlighting a critical vulnerability. Recent studies show that LVLMs often fail to consistently refuse instructions designed to compromise user privacy. While existing work on privacy protection has made meaningful progress in preventing the leakage of sensitive data, they are constrained by limitations in both generalization and non-destructiveness. They often struggle to robustly handle unseen privacy-related queries and may inadvertently degrade a model's performance on standard tasks. To address these challenges, we introduce Neural Gate, a novel method for mitigating privacy risks through neuron-level model editing. Our method improves a model's privacy safeguards by increasing its rate of refusal for privacy-related questions, crucially extending this protective behavior to novel sensitive queries not encountered during the editing process. Neural Gate operates by learning a feature vector to identify neurons associated with privacy-related concepts within the model's representation of a subject. This localization then precisely guides the update of model parameters. Through comprehensive experiments on MiniGPT and LLaVA, we demonstrate that our method significantly boosts the model's privacy protection while preserving its original utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.12374v1">The Privacy-Utility Trade-Off of Location Tracking in Ad Personalization</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-03-12T18:52:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohammad Mosaffa, Omid Rafieian</p>
    <p><b>Summary:</b> Firms collect vast amounts of behavioral and geographical data on individuals. While behavioral data captures an individual's digital footprint, geographical data reflects their physical footprint. Given the significant privacy risks associated with combining these data sources, it is crucial to understand their respective value and whether they act as complements or substitutes in achieving firms' business objectives. In this paper, we combine economic theory, machine learning, and causal inference to quantify the value of geographical data, the extent to which behavioral data can substitute for it, and the mechanisms through which it benefits firms. Using data from a leading in-app advertising platform in a large Asian country, we document that geographical data is most valuable in the early cold-start stage, when behavioral histories are limited. In this stage, geographical data complements behavioral data, improving targeting performance by almost 20%. As users accumulate richer behavioral histories, however, the role of geographical data shifts: it becomes largely substitutable, as behavioral data alone captures the relevant heterogeneity. These results highlight a central privacy-utility trade-off in ad personalization and inform managerial decisions about when location tracking creates value.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.12237v1">STAMP: Selective Task-Aware Mechanism for Text Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-03-12T17:55:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fengwei Tian, Payel Bhattacharjee, Heidi Hanson, Geoffrey D. Rubin, Joseph Y. Lo, Ravi Tandon</p>
    <p><b>Summary:</b> We present STAMP (Selective Task-Aware Mechanism for Text Privacy), a new framework for task-aware text privatization that achieves an improved privacy-utility trade-off. STAMP selectively allocates privacy budgets across tokens by jointly considering (i) each token's importance to the downstream task (as measured via a task- or query-specific representation), and (ii) its privacy sensitivity (e.g., names, dates, identifiers). This token-level partitioning enables fine-grained, group-wise control over the level of noise applied to different parts of the input, balancing privacy protection with task relevance. To privatize individual token embeddings, we introduce the polar mechanism, which perturbs only the direction of embeddings on the unit sphere while preserving their magnitude. Decoding is performed via cosine nearest-neighbor search, aligning the perturbation geometry with the decoding geometry. Unlike isotropic noise mechanisms, the polar mechanism maintains semantic neighborhoods in the embedding space and better preserves downstream utility. Experimental evaluations on SQuAD, Yelp, and AG News datasets demonstrate that STAMP, when combined with the normalized polar mechanism, consistently achieves superior privacy-utility trade-offs across varying per-token privacy budgets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.12195v1">Privacy in ERP Systems: Behavioral Models of Developers and Consultants</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-12T17:24:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alicia Pang, Katsiaryna Labunets, Olga Gadyatskaya</p>
    <p><b>Summary:</b> Applications like Enterprise Resource Planning (ERP) systems have become an indispensable part of the corporate digital infrastructure. These systems store sensitive data about customers, suppliers, and employees, and thus companies have to process these data in accordance with applicable regulations like the GDPR (the EU General Data Protection Regulation). This can be challenging due to a variety of reasons. For example, prior research has shown that developers sometimes lack knowledge about privacy.
  In this work, we focus on privacy in ERP systems in the context of an international consultancy firm. We investigate the privacy awareness regarding privacy-by-design and data minimization of two important populations: developers of ERP systems and managers and consultants responsible for services related to ERP systems. Applying thematic analysis, we elicit privacy behavioral models of these two populations using Fogg's Behavioral Model (FBM) framework. Our findings provide a means to stimulate more adequate privacy-related behaviors for developers and consultants.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.12142v1">Understanding Disclosure Risk in Differential Privacy with Applications to Noise Calibration and Auditing (Extended Version)</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-03-12T16:43:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Patricia Guerra-Balboa, Annika Sauer, Héber H. Arcolezi, Thorsten Strufe</p>
    <p><b>Summary:</b> Differential Privacy (DP) is widely adopted in data management systems to enable data sharing with formal disclosure guarantees. A central systems challenge is understanding how DP noise translates into effective protection against inference attacks, since this directly determines achievable utility. Most existing analyses focus only on membership inference -- capturing only a threat -- or rely on reconstruction robustness (ReRo). However, under realistic assumptions, we show that ReRo can yield misleading risk estimates and violate claimed bounds, limiting their usefulness for principled DP calibration and auditing.
  This paper introduces reconstruction advantage, a unified risk metric that consistently captures risk across membership inference, attribute inference, and data reconstruction. We derive tight bounds that relate DP noise to adversarial advantage and characterize optimal adversarial strategies for arbitrary DP mechanisms and attacker knowledge. These results enable risk-driven noise calibration and provide a foundation for systematic DP auditing. We show that reconstruction advantage improves the accuracy and scope of DP auditing and enables more effective utility-privacy trade-offs in DP-enabled data management systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.12094v1">Human-Centred LLM Privacy Audits: Findings and Frictions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-03-12T16:01:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dimitri Staufer, Kirsten Morehouse, David Hartmann, Bettina Berendt</p>
    <p><b>Summary:</b> Large language models (LLMs) learn statistical associations from massive training corpora and user interactions, and deployed systems can surface or infer information about individuals. Yet people lack practical ways to inspect what a model associates with their name. We report interim findings from an ongoing study and introduce LMP2, a browser-based self-audit tool. In two user studies ($N_{total}{=}458$), GPT-4o predicts 11 of 50 features for everyday people with $\ge$60\% accuracy, and participants report wanting control over LLM-generated associations despite not considering all outputs privacy violations. To validate our probing method, we evaluate eight LLMs on public figures and non-existent names, observing clear separation between stable name-conditioned associations and model defaults. Our findings also contribute to exposing a broader generative AI evaluation crisis: when outputs are probabilistic, context-dependent, and user-mediated through elicitation, what model--individual associations even include is under-specified and operationalisation relies on crafting probes and metrics that are hard to validate or compare. To move towards reliable, actionable human-centred LLM privacy audits, we identify nine frictions that emerged in our study and offer recommendations for future work and the design of human-centred LLM privacy audits.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.13407v1">Universal Shuffle Asymptotics, Part III: Dominant-Block Quotient Geometry and Hybrid Gaussian--Compound-Poisson Limits in Finite-Alphabet Shuffle Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-03-12T09:35:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alex Shvets</p>
    <p><b>Summary:</b> Part I of this series (arXiv:2602.09029) establishes a sharp Gaussian (LAN/GDP) limit theory for neighboring shuffle experiments in the fixed full-support regime. Part II (arXiv:2603.10073) identifies the first universality-breaking frontier: critical Poisson, Skellam, and multivariate compound-Poisson regimes. The present paper completes the finite-alphabet weak-limit theory by identifying the dominant-block quotient geometry that governs neighboring shuffle experiments. We treat dominant blocks of arbitrary finite size, allow overlap between the dominant output sets under the two neighboring hypotheses, and show that the limiting experiment decomposes according to this geometry: projecting onto the sum of the dominant tangent spaces yields a Gaussian factor, while quotienting by those same tangent spaces isolates a compound-Poisson jump field in the rare block. We also identify the regimes in which this quotient description determines the full privacy-curve, as well as the obstruction that appears when projected jump limits alone do not suffice. Two further sections sharpen the rate picture and the boundary interface: we show that the O(n^{-1/2}) rate for the full hybrid experiment is sharp in general, identify a compatibility condition restoring the O(n^{-1}) rate, and prove a boundary Berry--Esseen theorem giving O(c) Le Cam proximity between the critical Poisson-shift and Gaussian shift experiments as c tends to 0. Together with Parts I--II, this yields a three-regime universality picture and a precise finite-alphabet Levy--Khintchine layer for shuffle privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.11526v1">CFD-HAR: User-controllable Privacy through Conditional Feature Disentanglement</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-03-12T04:29:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alex Gn, Fan Li, S Kuniyilh, Ada Axan</p>
    <p><b>Summary:</b> Modern wearable and mobile devices are equipped with inertial measurement units (IMUs). Human Activity Recognition (HAR) applications running on such devices use machine-learning-based, data-driven techniques that leverage such sensor data. However, sensor-data-driven HAR deployments face two critical challenges: protecting sensitive user information embedded in sensor data in accordance with users' privacy preferences and maintaining high recognition performance with limited labeled samples. This paper proposes a technique for user-controllable privacy through feature disentanglement-based representation learning at the granular level for dynamic privacy filtering. We also compare the efficacy of our technique against few-shot HAR using autoencoder-based representation learning. We analyze their architectural designs, learning objectives, privacy guarantees, data efficiency, and suitability for edge Internet of Things (IoT) deployment. Our study shows that CFD-based HAR provides explicit, tunable privacy protection controls by separating activity and sensitive attributes in the latent space, whereas autoencoder-based few-shot HAR offers superior label efficiency and lightweight adaptability but lacks inherent privacy safeguards. We further examine the security implications of both approaches in continual IoT settings, highlighting differences in susceptibility to representation leakage and embedding-level attacks. The analysis reveals that neither paradigm alone fully satisfies the emerging requirements of next-generation IoT HAR systems. We conclude by outlining research directions toward unified frameworks that jointly optimize privacy preservation, few-shot adaptability, and robustness for trustworthy IoT intelligence.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.11523v2">Strict Optimality of Frequency and Distribution Estimation Under Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-12T04:16:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mingen Pan</p>
    <p><b>Summary:</b> This paper establishes the strict optimality in precision for frequency and distribution estimation under local differential privacy (LDP). We prove that a linear estimator with a symmetric and extremal configuration, and a constant support size equal to an optimized value, is sufficient to achieve the theoretical lower bound of the $\mathcal{L}_2$ loss for both frequency and distribution estimation. The theoretical $\mathcal{L}_1$ lower bound is also achieved asymptotically. Furthermore, we derive that the communication cost of such an optimal estimator can be as low as $\log_2(\frac{d(d-1)}{2}+1)$ bits, where $d$ denotes the dictionary size, and propose an algorithm to generate this optimal estimator.
  In addition, we introduce a modified Count-Mean Sketch and demonstrate that it is practically indistinguishable from theoretical optimality with a sufficiently large dictionary size (e.g., $d=100$ for a privacy parameter of $ε= 1$). We compare existing methods with our proposed optimal estimator to provide selection guidelines for practical deployment. Finally, the performance of these estimators is evaluated experimentally, showing that the empirical results are consistent with our theoretical derivations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.11029v1">Separating Oblivious and Adaptive Differential Privacy under Continual Observation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2026-03-11T17:51:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mark Bun, Marco Gaboardi, Connor Wagaman</p>
    <p><b>Summary:</b> We resolve an open question of Jain, Raskhodnikova, Sivakumar, and Smith (ICML 2023) by exhibiting a problem separating differential privacy under continual observation in the oblivious and adaptive settings. The continual observation (a.k.a. continual release) model formalizes privacy for streaming algorithms, where data is received over time and output is released at each time step. In the oblivious setting, privacy need only hold for data streams fixed in advance; in the adaptive setting, privacy is required even for streams that can be chosen adaptively based on the streaming algorithm's output.
  We describe the first explicit separation between the oblivious and adaptive settings. The problem showing this separation is based on the correlated vector queries problem of Bun, Steinke, and Ullman (SODA 2017). Specifically, we present an $(\varepsilon,0)$-DP algorithm for the oblivious setting that remains accurate for exponentially many time steps in the dimension of the input. On the other hand, we show that every $(\varepsilon,δ)$-DP adaptive algorithm fails to be accurate after releasing output for only a constant number of time steps.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.16918v1">Privacy and Safety Experiences and Concerns of U.S. Women Using Generative AI for Seeking Sexual and Reproductive Health Information</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-03-10T20:53:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ina Kaleva, Xiao Zhan, Ruba Abu-Salma, Jose Such</p>
    <p><b>Summary:</b> The rapid adoption of generative AI (GenAI) chatbots has reshaped access to sexual and reproductive health (SRH) information, particularly following the overturning of Roe v. Wade, as individuals assigned female at birth increasingly turn to online sources. However, existing research remains largely model-centered, paying limited attention to user privacy and safety. We conducted semi-structured interviews with 18 U.S.-based participants from both restrictive and non-restrictive states who had used GenAI chatbots to seek SRH information. Adoption was influenced by perceived utility, usability, credibility, accessibility, and anthropomorphism, and many participants disclosed sensitive personal SRH details. Participants identified multiple privacy risks, including excessive data collection, government surveillance, profiling, model training, and data commodification. While most participants accepted these risks in exchange for perceived utility, abortion-related queries elicited heightened safety concerns. Few participants employed protective strategies beyond minimizing disclosures or deleting data. Based on these findings, we offer design and policy recommendations, such as health-specific features and stronger moderation practices, to enhance privacy and safety in GenAI-supported SRH information seeking.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.09904v1">Dynamic Average Consensus with Privacy Guarantees and Its Application to Battery Energy Storage Systems</a></h3>
  
  <p><b>Published on:</b> 2026-03-10T16:56:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mihitha Maithripala, Chenyang Qiu, Zongli Lin</p>
    <p><b>Summary:</b> A privacy-preserving dynamic average consensus (DAC) algorithm is proposed that achieves consensus while preventing external eavesdroppers from inferring the reference signals and their derivatives. During the initialization phase, each agent generates a set of sinusoidal signals with randomly selected frequencies and exchanges them with its neighboring agents to construct a masking signal. Each agent masks its reference signals using this composite masking signal before executing the DAC update rule. It is shown that the developed scheme preserves the convergence properties of the conventional DAC framework while preventing information leakage to external eavesdroppers. Furthermore, the developed algorithm is applied to state-of-charge (SoC) balancing in a networked battery energy storage system to demonstrate its practical applicability. Simulation results validate the theoretical findings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.09583v2">Nonparametric Variational Differential Privacy via Embedding Parameter Clipping</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-03-10T12:34:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dina El Zein, Shashi Kumar, James Henderson</p>
    <p><b>Summary:</b> The nonparametric variational information bottleneck (NVIB) provides the foundation for nonparametric variational differential privacy (NVDP), a framework for building privacy-preserving language models. However, the learned latent representations can drift into regions with high information content, leading to poor privacy guarantees, but also low utility due to numerical instability during training. In this work, we introduce a principled parameter clipping strategy to directly address this issue. Our method is mathematically derived from the objective of minimizing the Rényi Divergence (RD) upper bound, yielding specific, theoretically grounded constraints on the posterior mean, variance, and mixture weight parameters. We apply our technique to an NVIB based model and empirically compare it against an unconstrained baseline. Our findings demonstrate that the clipped model consistently achieves tighter RD bounds, implying stronger privacy, while simultaneously attaining higher performance on several downstream tasks. This work presents a simple yet effective method for improving the privacy-utility trade-off in variational models, making them more robust and practical.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.09577v1">Randomized Distributed Function Computation (RDFC): Ultra-Efficient Semantic Communication Applications to Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Symbolic Computation-5BC0EB"> 
  <p><b>Published on:</b> 2026-03-10T12:23:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Onur Günlü</p>
    <p><b>Summary:</b> We establish the randomized distributed function computation (RDFC) framework, in which a sender transmits just enough information for a receiver to generate a randomized function of the input data. Describing RDFC as a form of semantic communication, which can be essentially seen as a generalized remote-source-coding problem, we show that security and privacy constraints naturally fit this model, as they generally require a randomization step. Using strong coordination metrics, we ensure (local differential) privacy for every input sequence and prove that such guarantees can be met even when no common randomness is shared between the transmitter and receiver.
  This work provides lower bounds on Wyner's common information (WCI), which is the communication cost when common randomness is absent, and proposes numerical techniques to evaluate the other corner point of the RDFC rate region for continuous-alphabet random variables with unlimited shared randomness. Experiments illustrate that a sufficient amount of common randomness can reduce the semantic communication rate by up to two orders of magnitude compared to the WCI point, while RDFC without any shared randomness still outperforms lossless transmission by a large margin. A finite blocklength analysis further confirms that the privacy parameter gap between the asymptotic and non-asymptotic RDFC methods closes exponentially fast with input length. Our results position RDFC as an energy-efficient semantic communication strategy for privacy-aware distributed computation systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.10073v1">Universal Shuffle Asymptotics, Part II: Non-Gaussian Limits for Shuffle Privacy -- Poisson, Skellam, and Compound-Poisson Regimes</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Probability-5BC0EB">
  <p><b>Published on:</b> 2026-03-10T05:39:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alex Shvets</p>
    <p><b>Summary:</b> Part I of this series (arXiv:2602.09029) develops a sharp Gaussian (LAN/GDP) limit theory for neighboring shuffle experiments when the local randomizer is fixed and has full support bounded away from zero. The present paper characterizes the first universality-breaking frontier: critical sequences of increasingly concentrated local randomizers for which classical Lindeberg conditions fail and the shuffle score exhibits rare macroscopic jumps.
  For shuffled binary randomized response with local privacy $\varepsilon_0 = \varepsilon_0(n)$, we prove experiment-level convergence (in Le Cam distance) to explicit shift limit experiments: a Poisson-shift limit for the canonical neighboring pair when $\exp(\varepsilon_0(n))/n \to c^2$, and a Skellam-shift limit for proportional compositions $k/n \to π\in (0,1)$ in the same scaling, including an explicit disappearance of the two-sided $δ$-floor away from boundary compositions.
  For general finite alphabets, we introduce a sparse-error critical regime and prove a multivariate compound-Poisson / independent Poisson vector limit for the centered released histogram, yielding a multivariate Poisson-shift experiment and an explicit limiting $(\varepsilon, δ)$ curve as a multivariate Poisson series. Together with Part I, these results yield a three-regime picture (Gaussian/GDP, critical Poisson/Skellam/compound-Poisson, and super-critical no privacy) under convergent macroscopic scalings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.09214v1">PrivPRISM: Automatically Detecting Discrepancies Between Google Play Data Safety Declarations and Developer Privacy Policies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-03-10T05:33:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bhanuka Silva, Dishanika Denipitiyage, Anirban Mahanti, Aruna Seneviratne, Suranga Seneviratne</p>
    <p><b>Summary:</b> End-users seldom read verbose privacy policies, leading app stores like Google Play to mandate simplified data safety declarations as a user-friendly alternative. However, these self-declared disclosures often contradict the full privacy policies, deceiving users about actual data practices and violating regulatory requirements for consistency. To address this, we introduce PrivPRISM, a robust framework that combines encoder and decoder language models to systematically extract and compare fine-grained data practices from privacy policies and to compare against data safety declarations, enabling scalable detection of non-compliance. Evaluating 7,770 popular mobile games uncovers discrepancies in nearly 53% of cases, rising to 61% among 1,711 widely used generic apps. Additionally, static code analysis reveals possible under-disclosures, with privacy policies disclosing just 66.8% of potential accesses to sensitive data like location and financial information, versus only 36.4% in data safety declarations of mobile games. Our findings expose systemic issues, including widespread reuse of generic privacy policies, vague / contradictory statements, and hidden risks in high-profile apps with 100M+ downloads, underscoring the urgent need for automated enforcement to protect platform integrity and for end-users to be vigilant about sensitive data they disclose via popular apps.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.09167v2">Optimal partition selection with Rényi differential privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-10T04:13:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Charlie Harrison, Pasin Manurangsi</p>
    <p><b>Summary:</b> A common problem in private data analysis is the partition selection problem, where each user holds a set of partitions (e.g. keys in a GROUP BY operation) from a possibly unbounded set. The challenge here is in maximizing the set of released partitions while respecting a differential privacy constraint. Previous work [Desfontaines et al., PoPETS 2022] presented an optimal $(\varepsilon, δ)$-DP algorithm when each user submits only a single partition. We generalize this approach to find the optimal algorithm under $δ$-approximate $(α, \varepsilon)$-Rényi differential privacy (RDP), which allows much tighter analysis under composition. Motivated by the non-existence of a general optimality result in the case where users submit multiple partitions each, we present an extension of our optimal algorithm tuned for $L^2$ bounded weighted partition selection which can be used as a drop-in improvement over the Gaussian mechanism any time the partition frequency is not also needed. We show that our primitive can be easily plugged into state of the art partition selection algorithms (PolicyGaussian from [Gopi et al., ICML 2020] and MAD2R from [Chen et al., ICML 2025]), improving performance both for parallel and sequential adaptive algorithms. Finally, we show that there is an inherent cost to algorithms which do support releasing the frequency as well as the partitions. Specifically, we formulate a basic notion of optimal approximate RDP algorithm for partition selection using additive noise, and show that there is a numerical separation between additive and non-additive noise mechanisms for this problem.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.10063v1">Building Privacy-and-Security-Focused Federated Learning Infrastructure for Global Multi-Centre Healthcare Research</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2026-03-09T22:13:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fan Zhang, Daniel Kreuter, Javier Fernandez-Marques, BloodCounts Consortium, Gregory Verghese, Bernard Butler, Nicholas Lane, Suthesh Sivapalaratnam, Joseph Taylor, Norbert C. J. de Wit, Nicholas S. Gleadall, Carola-Bibiane Schönlieb, Michael Roberts</p>
    <p><b>Summary:</b> Collaborative healthcare research across multiple institutions increasingly requires diverse clinical datasets, but cross-border data sharing is strictly constrained by privacy regulations. Federated learning (FL) enables model training while keeping data local; however, many existing frameworks remain proof-of-concept and do not adequately address governance risks such as unauthorised participation, misuse, and lack of accountability. In particular, enforceable mechanisms for authentication, authorisation, and accounting (AAA) are often missing, limiting real-world clinical deployment. This paper presents FLA$^3$ (Federated Learning with Authentication, Authorisation, and Accounting), a governance-aware federated learning platform that operationalises regulatory obligations through runtime policy enforcement. FLA$^3$ integrates eXtensible Access Control Markup Language (XACML) compliant attribute-based access control (ABAC), cryptographic accounting, and study-scoped federation directly into the federated learning orchestration layer to enforce institutional sovereignty and protocol adherence. We evaluate FLA$^3$ through two complementary studies. First, we demonstrate operational feasibility by deploying the platform infrastructure across five BloodCounts! Consortium institutions in four countries: United Kingdom, Netherlands, India, and The Gambia. Second, we assess clinical utility using simulated federation of full blood count (FBC) data from 54,446 samples from 35,315 subjects across 25 centres in the INTERVAL study. Results show that FLA$^3$ achieves predictive performance comparable to centralised training while strictly enforcing governance constraints. These results show that enforceable governance can function as a first-class privacy-preserving control, improving trustworthiness for scalable artificial intelligence (AI) in cross-jurisdictional healthcare deployments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.08913v1">Quantifying Memorization and Privacy Risks in Genomic Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2026-03-09T20:30:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alexander Nemecek, Wenbiao Li, Xiaoqian Jiang, Jaideep Vaidya, Erman Ayday</p>
    <p><b>Summary:</b> Genomic language models (GLMs) have emerged as powerful tools for learning representations of DNA sequences, enabling advances in variant prediction, regulatory element identification, and cross-task transfer learning. However, as these models are increasingly trained or fine-tuned on sensitive genomic cohorts, they risk memorizing specific sequences from their training data, raising serious concerns around privacy, data leakage, and regulatory compliance. Despite growing awareness of memorization risks in general-purpose language models, little systematic evaluation exists for these risks in the genomic domain, where data exhibit unique properties such as a fixed nucleotide alphabet, strong biological structure, and individual identifiability. We present a comprehensive, multi-vector privacy evaluation framework designed to quantify memorization risks in GLMs. Our approach integrates three complementary risk assessment methodologies: perplexity-based detection, canary sequence extraction, and membership inference. These are combined into a unified evaluation pipeline that produces a worst-case memorization risk score. To enable controlled evaluation, we plant canary sequences at varying repetition rates into both synthetic and real genomic datasets, allowing precise quantification of how repetition and training dynamics influence memorization. We evaluate our framework across multiple GLM architectures, examining the relationship between sequence repetition, model capacity, and memorization risk. Our results establish that GLMs exhibit measurable memorization and that the degree of memorization varies across architectures and training regimes. These findings reveal that no single attack vector captures the full scope of memorization risk, underscoring the need for multi-vector privacy auditing as a standard practice for genomic AI systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.08854v1">DeZent: Decentralized z-Anonymity with Privacy-Preserving Coordination</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-09T19:14:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Carolin Brunn, Florian Tschorsch</p>
    <p><b>Summary:</b> Analyzing large volumes of sensor network data, such as electricity consumption measurements from smart meters, is essential for modern applications but raises significant privacy concerns. Privacy-enhancing technologies like z-anonymity offer efficient anonymization for continuous data streams by suppressing rare values that could lead to re-identification, making it particularly suited for resource-constrained environments. Originally designed for centralized architectures, z-anonymity assumes a trusted central entity. In this paper, we introduce deZent, a decentralized implementation of z-anonymity that minimizes trust in the central entity by realizing local z-anonymity with lightweight coordination. We develop deZent using a stochastic counting structure and secure sum to coordinate private anonymization across the network. Our results show that deZent achieves comparable performance to centralized z-anonymity in terms of publication ratio, while reducing the communication overhead towards the central entity. Thus, deZent presents a promising approach for enhancing privacy in sensor networks while preserving system efficiency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.08848v1">The Data-Dollars Tradeoff: Privacy Harms vs. Economic Risk in Personalized AI Adoption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> 
  <p><b>Published on:</b> 2026-03-09T19:03:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alexander Erlei, Tahir Abbas, Kilian Bizer, Ujwal Gadiraju</p>
    <p><b>Summary:</b> Privacy concerns significantly impact AI adoption, yet little is known about how information environments shape user responses to data leak threats. We conducted a 2 x 3 between-subjects experiment (N=610) examining how risk versus ambiguity about privacy leaks affects the adoption of AI personalization. Participants chose between standard and AI-personalized product baskets, with personalization requiring data sharing that could leak to pricing algorithms. Under risk (30% leak probability), we found no difference in AI adoption between privacy-threatening and neutral conditions (ca. 50% adoption). Under ambiguity (10-50% range), privacy threats significantly reduced adoption compared to neutral conditions. This effect holds for sensitive demographic data as well as anonymized preference data. Users systematically over-bid for privacy disclosure labels, suggesting strong demand for transparency institutions. Notably, privacy leak threats did not affect subsequent bargaining behavior with algorithms. Our findings indicate that ambiguity over data leaks, rather than only privacy preferences per se, drives avoidance behavior among users towards personalized AI.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.08221v1">SplitAgent: A Privacy-Preserving Distributed Architecture for Enterprise-Cloud Agent Collaboration</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-03-09T10:51:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jianshu She</p>
    <p><b>Summary:</b> Enterprise adoption of cloud-based AI agents faces a fundamental privacy dilemma: leveraging powerful cloud models requires sharing sensitive data, while local processing limits capability. Current agent frameworks like MCP and A2A assume complete data sharing, making them unsuitable for enterprise environments with confidential information. We present SplitAgent, a novel distributed architecture that enables privacy-preserving collaboration between enterprise-side privacy agents and cloud-side reasoning agents. Our key innovation is context-aware dynamic sanitization that adapts privacy protection based on task semantics -- contract review requires different sanitization than code review or financial analysis. SplitAgent extends existing agent protocols with differential privacy guarantees, zero-knowledge tool verification, and privacy budget management. Through comprehensive experiments on enterprise scenarios, we demonstrate that SplitAgent achieves 83.8\% task accuracy while maintaining 90.1\% privacy protection, significantly outperforming static approaches (73.2\% accuracy, 79.7\% privacy). Context-aware sanitization improves task utility by 24.1\% over static methods while reducing privacy leakage by 67\%. Our architecture provides a practical path for enterprise AI adoption without compromising sensitive data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.08179v1">Privacy-Preserving End-to-End Full-Duplex Speech Dialogue Models</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> 
  <p><b>Published on:</b> 2026-03-09T10:01:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nikita Kuzmin, Tao Zhong, Jiajun Deng, Yingke Zhu, Tristan Tsoi, Tianxiang Cao, Simon Lui, Kong Aik Lee, Eng Siong Chng</p>
    <p><b>Summary:</b> End-to-end full-duplex speech models feed user audio through an always-on LLM backbone, yet the speaker privacy implications of their hidden representations remain unexamined. Following the VoicePrivacy 2024 protocol with a lazy-informed attacker, we show that the hidden states of SALM-Duplex and Moshi leak substantial speaker identity across all transformer layers. Layer-wise and turn-wise analyses reveal that leakage persists across all layers, with SALM-Duplex showing stronger leakage in early layers while Moshi leaks uniformly, and that Linkability rises sharply within the first few turns. We propose two streaming anonymization setups using Stream-Voice-Anon: a waveform-level front-end (Anon-W2W) and a feature-domain replacement (Anon-W2F). Anon-W2F raises EER by over 3.5x relative to the discrete encoder baseline (11.2% to 41.0%), approaching the 50% random-chance ceiling, while Anon-W2W retains 78-93% of baseline sBERT across setups with sub-second response latency (FRL under 0.8 s).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.07522v1">Beyond Data Splitting: Full-Data Conformal Prediction by Differential Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-03-08T08:25:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Young Hyun Cho, Jordan Awan</p>
    <p><b>Summary:</b> Privacy protection and uncertainty quantification are increasingly important in data-driven decision making. Conformal prediction provides finite-sample marginal coverage, but existing private approaches often rely on data splitting, reducing the effective sample size. We propose a full-data privacy-preserving conformal prediction framework that avoids splitting. Our framework leverages stability induced by differential privacy to control the gap between in-sample and out-of-sample conformal scores, and pairs this with a conservative private quantile routine designed to prevent under-coverage. We show that a generic differential privacy guarantee yields a universal coverage floor, yet cannot generally recover the nominal $1-α$ level. We then provide a refined, mechanism-specific stability analysis and yields asymptotic recovery of the nominal level. Experiments demonstrate sharper prediction sets than the split-based private baseline.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.07314v1">Faster-HEAL: An Efficient and Privacy-Preserving Collaborative Perception Framework for Heterogeneous Autonomous Vehicles</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E">
  <p><b>Published on:</b> 2026-03-07T19:18:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Armin Maleki, Hayder Radha</p>
    <p><b>Summary:</b> Collaborative perception (CP) is a promising paradigm for improving situational awareness in autonomous vehicles by overcoming the limitations of single-agent perception. However, most existing approaches assume homogeneous agents, which restricts their applicability in real-world scenarios where vehicles use diverse sensors and perception models. This heterogeneity introduces a feature domain gap that degrades detection performance. Prior works address this issue by retraining entire models/major components, or using feature interpreters for each new agent type, which is computationally expensive, compromises privacy, and may reduce single-agent accuracy. We propose Faster-HEAL, a lightweight and privacy-preserving CP framework that fine-tunes a low-rank visual prompt to align heterogeneous features with a unified feature space while leveraging pyramid fusion for robust feature aggregation. This approach reduces the trainable parameters by 94%, enabling efficient adaptation to new agents without retraining large models. Experiments on the OPV2V-H dataset show that Faster-HEAL improves detection performance by 2% over state-of-the-art methods with significantly lower computational overhead, offering a practical solution for scalable heterogeneous CP.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.07027v1">Resource-Adaptive Federated Text Generation with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-03-07T04:11:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiayi Wang, John Gounley, Heidi Hanson</p>
    <p><b>Summary:</b> In cross-silo federated learning (FL), sensitive text datasets remain confined to local organizations due to privacy regulations, making repeated training for each downstream task both communication-intensive and privacy-demanding. A promising alternative is to generate differentially private (DP) synthetic datasets that approximate the global distribution and can be reused across tasks. However, pretrained large language models (LLMs) often fail under domain shift, and federated finetuning is hindered by computational heterogeneity: only resource-rich clients can update the model, while weaker clients are excluded, amplifying data skew and the adverse effects of DP noise. We propose a flexible participation framework that adapts to client capacities. Strong clients perform DP federated finetuning, while weak clients contribute through a lightweight DP voting mechanism that refines synthetic text. To ensure the synthetic data mirrors the global dataset, we apply control codes (e.g., labels, topics, metadata) that represent each client's data proportions and constrain voting to semantically coherent subsets. This two-phase approach requires only a single round of communication for weak clients and integrates contributions from all participants. Experiments show that our framework improves distribution alignment and downstream robustness under DP and heterogeneity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.07001v1">Privacy-Preserving Patient Identity Management Framework for Secure Healthcare Access</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-07T02:47:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nasif Muslim, Jean-Charles Grégoire</p>
    <p><b>Summary:</b> Effective healthcare delivery depends on accurate longitudinal health records and addressing patients' concerns regarding the privacy of their information. While patient authentication is essential, reusing patient identifiers exposes individuals to linkability (associating multiple visits) and traceability (tying visits to real-world identities) risks. This paper presents a privacy-preserving, patient-centric identity management framework specifically tailored to the operational and regulatory requirements of healthcare. The framework balances operational reliability with strong privacy protections through a rooted trust anchor, anonymous pseudonyms, and a conditional traceability mechanism. It is formally specified, and its security and privacy properties are evaluated through MSRA-based architectural analysis and complementary formal verification. Simulation-based evaluation demonstrates that the framework's identity workflows are operationally feasible within the latency bounds typical of clinical environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.06540v1">Proteus: A Practical Framework for Privacy-Preserving Device Logs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-06T18:28:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sanket Goutam, Hunter Kippen, Mike Grace, Amir Rahmati</p>
    <p><b>Summary:</b> Device logs are essential for forensic investigations, enterprise monitoring, and fraud detection; however, they often leak personally identifiable information (PII) when exported for third-party analysis. Existing approaches either fail to minimize PII exposure across all stages of log collection and analysis or sacrifice data fidelity, resulting in less effective analysis. We present Proteus, a privacy-preserving device logging framework that enables forensic analysis without disclosing plaintext PII or compromising fidelity, even when facing adversaries with access to multiple snapshots of the log files. To achieve this, Proteus proposes a two-layer scheme that employs keyed-hash pseudonymization of PII fields and time-rotating encryption with ratcheted ephemeral keys to prevent multi-snapshot correlation. For controlled sharing, clients export ratchet states that grant time-bounded access, permitting decryption of pseudonymized tokens that enable linkage and timeline reconstruction without exposing the underlying PII. Subsequent ratchet rotations ensure forward secrecy, while DICE-based attestation authenticates device provenance. We implement Proteus as a transparent extension to Android's logcat and evaluate it across three generations of hardware. Our results demonstrate a median latency of 0.2 ms per message and an average per-PII-field size overhead of only 97.1 bytes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.06051v1">A LINDDUN-based Privacy Threat Modeling Framework for GenAI</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2026-03-06T09:04:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qianying Liao, Jonah Bellemans, Laurens Sion, Xue Jiang, Dmitrii Usynin, Xuebing Zhou, Dimitri Van Landuyt, Lieven Desmet, Wouter Joosen</p>
    <p><b>Summary:</b> As generative AI (GenAI) systems become increasingly prevalent across various technological stacks, the question of how such systems handle sensitive and personal data flows becomes increasingly important. Specifically, both the ability to harness and process large swaths of information as well as their stochastic nature raise key concerns related to both security and privacy. Unfortunately, while some of the traditional security threat modeling can effectively identify certain violations, privacy-related issues are often overlooked. To respond to these challenges, we introduce a novel domain-specific privacy threat modeling framework to support the privacy threat analysis of GenAI-based applications. This framework is constructed through a two-pronged approach: (1) a systematic review of the emerging literature on GenAI privacy threats, and (2) a case-driven application to a representative Chatbot system. These efforts yield a foundational GenAI privacy threat modeling framework built on LINDDUN. The new framework affects three out of the seven privacy threat types of LINDDUN and introduces 100 new GenAI examples to the knowledge base. Its effectiveness is validated on an AI Agent system, which demonstrates that a comprehensive privacy analysis can be supported by the new framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.05915v1">ThermoCAPTCHA: Privacy-Preserving Human Verification with Farm-Resistant Traceable Tokens</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-06T05:07:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shovon Paul, Md Imran Hossen, Xiali Hei</p>
    <p><b>Summary:</b> CAPTCHAs remain a critical defense against automated abuse, yet modern systems suffer from well-known limitations in usability, accessibility, and resistance to increasingly capable bots and low-cost CAPTCHA farms. Behavioral and puzzle-based mechanisms often impose cognitive burdens, collect extensive interaction data, or permit outsourcing to human solvers. In this paper, we present ThermoCAPTCHA, a novel privacy-preserving human verification system that uses real-time thermal imaging to detect live human presence without requiring users to solve challenges. A lightweight YOLOv4-tiny model identifies human heat signatures from a single thermal capture, while cryptographically bound traceable tokens prevent forwarding attacks by CAPTCHA farm workers. Our prototype achieves 96.70% detection accuracy with a 73.60 ms verification latency on a low-powered server. Comprehensive security evaluation, including MITM manipulation, spoofing attempts, adversarial perturbations, and misuse scenarios, shows that ThermoCAPTCHA withstands threats that commonly defeat behavioral CAPTCHAs. A user study with 50 participants, including visually challenged users, demonstrates improved accuracy, faster completion times, and higher perceived usability compared to reCAPTCHA v2.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.05158v1">Balancing Privacy-Quality-Efficiency in Federated Learning through Round-Based Interleaving of Protection Techniques</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-03-05T13:28:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yenan Wang, Carla Fabiana Chiasserini, Elad Michael Schiller</p>
    <p><b>Summary:</b> In federated learning (FL), balancing privacy protection, learning quality, and efficiency remains a challenge. Privacy protection mechanisms, such as Differential Privacy (DP), degrade learning quality, or, as in the case of Homomorphic Encryption (HE), incur substantial system overhead. To address this, we propose Alt-FL, a privacy-preserving FL framework that combines DP, HE, and synthetic data via a novel round-based interleaving strategy. Alt-FL introduces three new methods, Privacy Interleaving (PI), Synthetic Interleaving with DP (SI/DP), and Synthetic Interleaving with HE (SI/HE), that enable flexible quality-efficiency trade-offs while providing privacy protection.
  We systematically evaluate Alt-FL against representative reconstruction attacks, including Deep Leakage from Gradients, Inverting Gradients, When the Curious Abandon Honesty, and Robbing the Fed, using a LeNet-5 model on CIFAR-10 and Fashion-MNIST. To enable fair comparison between DP- and HE-based defenses, we introduce a new attacker-centric framework that compares empirical attack success rates across the three proposed interleaving methods. Our results show that, for the studied attacker model and dataset, PI achieves the most balanced trade-offs at high privacy protection levels, while DP-based methods are preferable at intermediate privacy requirements. We also discuss how such results can be the basis for selecting privacy-preserving FL methods under varying privacy and resource constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.05073v1">Robust Single-message Shuffle Differential Privacy Protocol for Accurate Distribution Estimation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-05T11:40:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaoguang Li, Hanyi Wang, Yaowei Huang, Jungang Yang, Qingqing Ye, Haonan Yan, Ke Pan, Zhe Sun, Hui Li</p>
    <p><b>Summary:</b> Shuffler-based differential privacy (shuffle-DP) is a privacy paradigm providing high utility by involving a shuffler to permute noisy report from users. Existing shuffle-DP protocols mainly focus on the design of shuffler-based categorical frequency oracle (SCFO) for frequency estimation on categorical data. However, numerical data is a more prevalent type and many real-world applications depend on the estimation of data distribution with ordinal nature. In this paper, we study the distribution estimation under pure shuffle model, which is a prevalent shuffle-DP framework without strong security assumptions. We initially attempt to transplant existing SCFOs and the naïve distribution recovery technique to this task, and demonstrate that these baseline protocols cannot simultaneously achieve outstanding performance in three metrics: 1) utility, 2) message complexity; and 3) robustness to data poisoning attacks. Therefore, we further propose a novel single-message \textit{adaptive shuffler-based piecewise} (ASP) protocol with high utility and robustness. In ASP, we first develop a randomizer by parameter optimization using our proposed tighter bound of mutual information. We also design an \textit{Expectation Maximization with Adaptive Smoothing} (EMAS) algorithm to accurately recover distribution with enhanced robustness. To quantify robustness, we propose a new evaluation framework to examine robustness under different attack targets, enabling us to comprehensively understand the protocol resilience under various adversarial scenarios. Extensive experiments demonstrate that ASP outperforms baseline protocols in all three metrics. Especially under small $ε$ values, ASP achieves an order of magnitude improvement in utility with minimal message complexity, and exhibits over threefold robustness compared to baseline methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.04930v1">Mind the Gap: Mapping Wearer-Bystander Privacy Tensions and Context-Adaptive Pathways for Camera Glasses</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-03-05T08:27:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xueyang Wang, Kewen Peng, Xin Yi, Hewu Li</p>
    <p><b>Summary:</b> Camera glasses create fundamental privacy tensions between wearers seeking recording functionality and bystanders concerned about unauthorized surveillance. We present a systematic multi-stakeholder evaluation of privacy mechanisms through surveys (N=525) and paired interviews (N=20) in China. Study 1 quantifies expectation-willingness gaps: bystanders consistently demand stronger information transparency and protective measures than wearers will provide, with disparities intensifying in sensitive contexts where 65-90% of bystanders would take defensive action. Study 2 evaluates twelve privacy-enhancing technologies, revealing four fundamental trade-offs that undermine current approaches: visibility versus disruption, empowerment versus burden, protection versus agency, and accountability versus exposure. These gaps reflect structural incompatibilities rather than inadequate goodwill, with context emerging as the primary determinant of privacy acceptability. We propose context-adaptive pathways that dynamically adjust protection strategies: minimal-friction visibility in public spaces, structured negotiation in semi-public environments, and automatic protection in sensitive contexts. Our findings contribute a diagnostic framework for evaluating privacy mechanisms and implications for context-aware design in ubiquitous sensing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.04902v1">AgentSCOPE: Evaluating Contextual Privacy Across Agentic Workflows</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-03-05T07:45:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ivoline C. Ngong, Keerthiram Murugesan, Swanand Kadhe, Justin D. Weisz, Amit Dhurandhar, Karthikeyan Natesan Ramamurthy</p>
    <p><b>Summary:</b> Agentic systems are increasingly acting on users' behalf, accessing calendars, email, and personal files to complete everyday tasks. Privacy evaluation for these systems has focused on the input and output boundaries, but each task involves several intermediate information flows, from agent queries to tool responses, that are not currently evaluated. We argue that every boundary in an agentic pipeline is a site of potential privacy violation and must be assessed independently. To support this, we introduce the Privacy Flow Graph, a Contextual Integrity-grounded framework that decomposes agentic execution into a sequence of information flows, each annotated with the five CI parameters, and traces violations to their point of origin. We present AgentSCOPE, a benchmark of 62 multi-tool scenarios across eight regulatory domains with ground truth at every pipeline stage. Our evaluation across seven state-of-the-art LLMs show that privacy violations in the pipeline occur in over 80% of scenarios, even when final outputs appear clean (24%), with most violations arising at the tool-response stage where APIs return sensitive data indiscriminately. These results indicate that output-level evaluation alone substantially underestimates the privacy risk of agentic systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.04881v1">Differential Privacy in Two-Layer Networks: How DP-SGD Harms Fairness and Robustness</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-03-05T07:19:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruichen Xu, Kexin Chen</p>
    <p><b>Summary:</b> Differentially private learning is essential for training models on sensitive data, but empirical studies consistently show that it can degrade performance, introduce fairness issues like disparate impact, and reduce adversarial robustness. The theoretical underpinnings of these phenomena in modern, non-convex neural networks remain largely unexplored. This paper introduces a unified feature-centric framework to analyze the feature learning dynamics of differentially private stochastic gradient descent (DP-SGD) in two-layer ReLU convolutional neural networks. Our analysis establishes test loss bounds governed by a crucial metric: the feature-to-noise ratio (FNR). We demonstrate that the noise required for privacy leads to suboptimal feature learning, and specifically show that: 1) imbalanced FNRs across classes and subpopulations cause disparate impact; 2) even in the same class, noise has a greater negative impact on semantically long-tailed data; and 3) noise injection exacerbates vulnerability to adversarial attacks. Furthermore, our analysis reveals that the popular paradigm of public pre-training and private fine-tuning does not guarantee improvement, particularly under significant feature distribution shifts between datasets. Experiments on synthetic and real-world data corroborate our theoretical findings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.04775v1">Privacy-Aware Camera 2.0 Technical Report</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-03-05T03:46:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Huan Song, Shuyu Tian, Ting Long, Jiang Liu, Cheng Yuan, Zhenyu Jia, Jiawei Shao, Xuelong Li</p>
    <p><b>Summary:</b> With the increasing deployment of intelligent sensing technologies in highly sensitive environments such as restrooms and locker rooms, visual surveillance systems face a profound privacy-security paradox. Existing privacy-preserving approaches, including physical desensitization, encryption, and obfuscation, often compromise semantic understanding or fail to ensure mathematically provable irreversibility. Although Privacy Camera 1.0 eliminated visual data at the source to prevent leakage, it provided only textual judgments, leading to evidentiary blind spots in disputes. To address these limitations, this paper proposes a novel privacy-preserving perception framework based on the AI Flow paradigm and a collaborative edge-cloud architecture. By deploying a visual desensitizer at the edge, raw images are transformed in real time into abstract feature vectors through nonlinear mapping and stochastic noise injection under the Information Bottleneck principle, ensuring identity-sensitive information is stripped and original images are mathematically unreconstructable. The abstract representations are transmitted to the cloud for behavior recognition and semantic reconstruction via a "dynamic contour" visual language, achieving a critical balance between perception and privacy while enabling illustrative visual reference without exposing raw images.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.04742v1">Efficient Privacy-Preserving Sparse Matrix-Vector Multiplication Using Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-05T02:29:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yang Gao, Gang Quan, Wujie Wen, Scott Piersall, Qian Lou, Liqiang Wang</p>
    <p><b>Summary:</b> Sparse matrix-vector multiplication (SpMV) is a fundamental operation in scientific computing, data analysis, and machine learning. When the data being processed are sensitive, preserving privacy becomes critical, and homomorphic encryption (HE) has emerged as a leading approach for addressing this challenge. Although HE enables privacy-preserving computation, its application to SpMV has remained largely unaddressed. To the best of our knowledge, this paper presents the first framework that efficiently integrates HE with SpMV, addressing the dual challenges of computational efficiency and data privacy. In particular, we introduce a novel compressed matrix format, named Compressed Sparse Sorted Column (CSSC), which is specifically designed to optimize encrypted sparse matrix computations. By preserving sparsity and enabling efficient ciphertext packing, CSSC significantly reduces storage and computational overhead. Our experimental results on real-world datasets demonstrate that the proposed method achieves significant gains in both processing time and memory usage. This study advances privacy-preserving SpMV and lays the groundwork for secure applications in federated learning, encrypted databases, scientific computing, and beyond.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.04595v1">A Late-Fusion Multimodal AI Framework for Privacy-Preserving Deduplication in National Healthcare Data Environments</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-03-04T20:46:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohammed Omer Shakeel Ahmed</p>
    <p><b>Summary:</b> Duplicate records pose significant challenges in customer relationship management (CRM)and healthcare, often leading to inaccuracies in analytics, impaired user experiences, and compliance risks. Traditional deduplication methods rely heavily on direct identifiers such as names, emails, or Social Security Numbers (SSNs), making them ineffective under strict privacy regulations like GDPR and HIPAA, where such personally identifiable information (PII) is restricted or masked. In this research, I propose a novel, scalable, multimodal AI framework for detecting duplicates without depending on sensitive information. This system leverages three distinct modalities: semantic embeddings derived from textual fields (names, cities) using pre-trained DistilBERT models, behavioral patterns extracted from user login timestamps, and device metadata encoded through categorical embeddings. These heterogeneous modalities are combined using a late fusion approach and clustered via DBSCAN, an unsupervised density-based algorithm. This proposed model is evaluated against a traditional string-matching baseline on a synthetic CRM dataset specifically designed to reflect privacy-preserving constraints. The multimodal framework demonstrated good performance, achieving a good F1-score by effectively identifying duplicates despite variations and noise inherent in the data. This approach offers a privacy-compliant solution to entity resolution and supports secure digital infrastructure, enhances the reliability of public health analytics, and promotes ethical AI adoption across government and enterprise settings. It is well-suited for integration into national health data modernization efforts, aligning with broader goals of privacy-first innovation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.04493v2">Rethinking quantum smooth entropies: Tight one-shot analysis of quantum privacy amplification</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2026-03-04T19:00:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bartosz Regula, Marco Tomamichel</p>
    <p><b>Summary:</b> We introduce an improved one-shot characterisation of randomness extraction against quantum side information (privacy amplification), strengthening known one-shot bounds and providing a unified derivation of the tightest known asymptotic constraints. Our main tool is a new class of smooth conditional entropies defined by lifting classical smooth divergences through measurements. A key role is played by the measured smooth Rényi relative entropy of order 2, which we show to admit an equivalent variational form: it can be understood as allowing for smoothing over not only states, but also non-positive Hermitian operators. Building on this, we establish a tightened leftover hash lemma, significantly improving over all known smooth min-entropy bounds on extractable randomness and recovering the sharpest classical achievability results. We extend these methods to decoupling, the coherent analogue of privacy amplification, obtaining a corresponding improved one-shot bound. Relaxing our smooth entropy bounds leads to one-shot achievability results in terms of measured Rényi divergences, which in the asymptotic i.i.d. limit recover the state-of-the-art error exponent of [Dupuis, arXiv:2105.05342]. We show an approximate optimality of our results by giving a matching one-shot converse bound up to additive logarithmic terms. This yields an optimal second-order asymptotic expansion of privacy amplification under trace distance, establishing a significantly tighter one-shot achievability result than previously shown in [Shen et al., arXiv:2202.11590] and proving its optimality for all hash functions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.04367v1">Scrollytelling as an Alternative Format for Privacy Policies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-03-04T18:32:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gonzalo Gabriel Méndez, Jose Such</p>
    <p><b>Summary:</b> Privacy policies are long, complex, and rarely read, which limits their effectiveness in informed consent. We investigate scrollytelling, a scroll-driven narrative approach, as a privacy policy presentation format. We built a prototype that interleaves the full policy text with animated visuals to create a dynamic reading experience. In an online study (N=454), we compared our tool against text, two nutrition-label variants, and a standalone interactive visualization. Scrollytelling improved user experience over text, yielding higher engagement, lower cognitive load, greater willingness to adopt the format, and increased perceived clarity. It also matched other formats on comprehension accuracy and confidence, with only one nutrition-label variant performing slightly better. Changes in perceived understanding, transparency, and trust were small and statistically inconclusive. These findings suggest that scrollytelling can preserve comprehension while enhancing the experience of policy reading. We discuss design implications for accessible policy communication and identify directions for increasing transparency and user trust.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.04340v1">Balancing Fidelity, Utility, and Privacy in Synthetic Cardiac MRI Generation: A Comparative Study</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-03-04T17:59:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Madhura Edirisooriya, Dasuni Kawya, Ishan Kumarasinghe, Isuri Devindi, Mary M. Maleckar, Roshan Ragel, Isuru Nawinne, Vajira Thambawita</p>
    <p><b>Summary:</b> Deep learning in cardiac MRI (CMR) is fundamentally constrained by both data scarcity and privacy regulations. This study systematically benchmarks three generative architectures: Denoising Diffusion Probabilistic Models (DDPM), Latent Diffusion Models (LDM), and Flow Matching (FM) for synthetic CMR generation. Utilizing a two-stage pipeline where anatomical masks condition image synthesis, we evaluate generated data across three critical axes: fidelity, utility, and privacy. Our results show that diffusion-based models, particularly DDPM, provide the most effective balance between downstream segmentation utility, image fidelity, and privacy preservation under limited-data conditions, while FM demonstrates promising privacy characteristics with slightly lower task-level performance. These findings quantify the trade-offs between cross-domain generalization and patient confidentiality, establishing a framework for safe and effective synthetic data augmentation in medical imaging.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.04323v1">PTOPOFL: Privacy-Preserving Personalised Federated Learning via Persistent Homology</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">  
  <p><b>Published on:</b> 2026-03-04T17:44:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kelly L Vomo-Donfack, Adryel Hoszu, Grégory Ginot, Ian Morilla</p>
    <p><b>Summary:</b> Federated learning (FL) faces two structural tensions: gradient sharing enables data-reconstruction attacks, while non-IID client distributions degrade aggregation quality. We introduce PTOPOFL, a framework that addresses both challenges simultaneously by replacing gradient communication with topological descriptors derived from persistent homology (PH). Clients transmit only 48-dimensional PH feature vectors-compact shape summaries whose many-to-one structure makes inversion provably ill-posed-rather than model gradients. The server performs topology-guided personalised aggregation: clients are clustered by Wasserstein similarity between their PH diagrams, intra-cluster models are topology-weighted,and clusters are blended with a global consensus. We prove an information-contraction theorem showing that PH descriptors leak strictly less mutual information per sample than gradients under strongly convex loss functions, and we establish linear convergence of the Wasserstein-weighted aggregation scheme with an error floor strictly smaller than FedAvg. Evaluated against FedAvg, FedProx, SCAFFOLD, and pFedMe on a non-IID healthcare scenario (8 hospitals, 2 adversarial) and a pathological benchmark (10 clients), PTOPOFL achieves AUC 0.841 and 0.910 respectively-the highest in both settings-while reducing reconstruction risk by a factor of 4.5 relative to gradient sharing. Code is publicly available at https://github.com/MorillaLab/TopoFederatedL and data at https://doi.org/10.5281/zenodo.18827595.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.04199v1">Bayesian Adversarial Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2026-03-04T15:46:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Cameron Bell, Timothy Johnston, Antoine Luciano, Christian P Robert</p>
    <p><b>Summary:</b> Theoretical and applied research into privacy encompasses an incredibly broad swathe of differing approaches, emphasis and aims. This work introduces a new quantitative notion of privacy that is both contextual and specific. We argue that it provides a more meaningful notion of privacy than the widely utilised framework of differential privacy and a more explicit and rigorous formulation than what is commonly used in statistical disclosure theory. Our definition relies on concepts inherent to standard Bayesian decision theory, while departing from it in several important respects. In particular, the party controlling the release of sensitive information should make disclosure decisions from the prior viewpoint, rather than conditional on the data, even when the data is itself observed. Illuminating toy examples and computational methods are discussed in high detail in order to highlight the specificities of the method.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.05541v1">Privacy-Preserving Collaborative Medical Image Segmentation Using Latent Transform Networks</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2026-03-04T12:05:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Saheed Ademola Bello, Muhammad Shahid Jabbar, Muhammad Sohail Ibrahim, Shujaat Khan</p>
    <p><b>Summary:</b> Collaborative training across multiple institutions is becoming essential for building reliable medical image segmentation models. However, privacy regulations, data silos, and uneven data availability prevent hospitals from sharing raw scans or annotations, limiting the ability to train generalizable models. Latent-space collaboration frameworks such as privacy-segmentation framework (SF) offer a promising alternative, but such methods still face challenges in segmentation accuracy and vulnerability to latent inversion and membership-inference attacks. This work introduces a privacy-preserving collaborative medical image segmentation framework (PPCMI-SF) designed for heterogeneous medical datasets. The approach combines skip-connected autoencoders for images and masks with a keyed latent transform that applies client-specific orthogonal mixing and permutation to protect latent features before they are shared. A unified mapping network on the server-side performs multi-scale latent-to-latent translation, enabling segmentation inference without exposing raw data. Experiments on four datasets: PSFH ultrasound, ultrasound nerve segmentation, FUMPE CTA, and cardiac MRI show that the proposed PPCMI-SF consistently achieves high Dice scores and improved boundary accuracy, as reflected by lower 95th percentile Hausdorff distance (HD95) and average symmetric surface distance (ASD) compared to the current state-of-the-art and performs competitively with privacy-agnostic baselines. Privacy tests confirm strong resistance to inversion and membership attacks, and the overall system achieves real-time inference with low communication overhead. These results demonstrate that accurate and efficient medical image segmentation can be achieved without compromising data privacy in multi-institution settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.03906v2">Measuring Privacy vs. Fidelity in Synthetic Social Media Datasets</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-04T10:12:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Henry Tari, Adriana Iamnitchi</p>
    <p><b>Summary:</b> Synthetic data is increasingly used to support research without exposing sensitive user content. Social media data is one of the types of datasets that would hugely benefit from representative synthetic equivalents that can be used to bootstrap research and allow reproducibility through data sharing. However, recent studies show that (tabular) synthetic data is not inherently privacy-preserving. Much less is known, however, about the privacy risks of synthetically generated unstructured texts. This work evaluates the privacy of synthetic Instagram posts generated by three state-of-the-art large language models using two prompting strategies. We propose a methodology that quantifies privacy by framing re-identification as an authorship attribution attack. A RoBERTa-large classifier trained on real posts achieved 81\% accuracy in authorship attribution on real data, but only 16.5--29.7\% on synthetic posts, showing reduced, though non-negligible, risk. Fidelity was assessed via text traits, sentiment, topic overlap, and embedding similarity, confirming the expected trade-off: higher fidelity coincides with greater privacy leakage. This work provides a framework for evaluating privacy in synthetic text and demonstrates the privacy--fidelity tension in social media datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.03711v2">LDP-Slicing: Local Differential Privacy for Images via Randomized Bit-Plane Slicing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-03-04T04:25:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuanming Cao, Chengqi Li, Wenbo He</p>
    <p><b>Summary:</b> Local Differential Privacy (LDP) is the gold standard trust model for privacy-preserving machine learning by guaranteeing privacy at the data source. However, its application to image data has long been considered impractical due to the high dimensionality of pixel space. Canonical LDP mechanisms are designed for low-dimensional data, resulting in severe utility degradation when applied to high-dimensional pixel spaces. This paper demonstrates that this utility loss is not inherent to LDP, but from its application to an inappropriate data representation. We introduce LDP-Slicing, a lightweight, training-free framework that resolves this domain mismatch. Our key insight is to decompose pixel values into a sequence of binary bit-planes. This transformation allows us to apply the LDP mechanism directly to the bit-level representation. To further strengthen privacy and preserve utility, we integrate a perceptual obfuscation module that mitigates human-perceivable leakage and an optimization-based privacy budget allocation strategy. This pipeline satisfies rigorous pixel-level $\varepsilon$-LDP while producing images that retain high utility for downstream tasks. Extensive experiments on face recognition and image classification demonstrate that LDP-Slicing outperforms existing DP/LDP baselines under comparable privacy budgets, with negligible computational overhead.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.03659v2">Reckless Designs and Broken Promises: Privacy Implications of Targeted Interactive Advertisements on Social Media Platforms</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-03-04T02:27:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Julia B. Kieserman, Athanasios Andreou, Laura Edelson, Sandra Siby, Damon McCoy</p>
    <p><b>Summary:</b> Popular social media platforms TikTok, Facebook and Instagram allow third-parties to run targeted advertising campaigns on sensitive attributes in-platform. These ads are interactive by default, meaning users can comment or ``react'' (e.g., ``like'', ``love'') to them. We find that this platform-level design choice creates a privacy loophole such that advertisers can view the profiles of those who interact with their ads, thus identifying individuals that fulfill certain targeting criteria. This behavior is in contradiction to the promises made by the platforms to hide user data from advertisers. We conclude by suggesting design modifications that could provide users with transparency about the consequences of ad interaction to protect against unintentional disclosure.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.03606v1">Are You Comfortable Sharing It?: Leveraging Image Obfuscation Techniques to Enhance Sharing Privacy for Blind and Visually Impaired Users</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-03-04T00:29:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Satabdi Das, Nahian Beente Firuj, Manjot Singh, Arshad Nasser, Khalad Hasan</p>
    <p><b>Summary:</b> People with Blind Visual Impairments (BVI) face unique challenges when sharing images, as these may accidentally contain sensitive or inappropriate content. In many instances, they are unaware of the potential risks associated with sharing such content, which can compromise their privacy and interpersonal relationships. To address this issue, we investigated image filtering techniques that could help BVI users manage sensitive content before sharing with various audiences, including family, friends, or strangers. We conducted a study with 20 BVI participants, evaluating different filters applied to images varying in sensitivity, such as personal moments or embarrassing shots. Results indicated that pixelation was the least preferred method, while preferences for other filters varied depending on image type and sharing context. Additionally, participants reported greater comfort when sharing filtered versus unfiltered images across audiences. Based on the results, we offer a set of design guidelines to enhance the image-sharing experience for BVI individuals.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.03412v1">PRIVATEEDIT: A Privacy-Preserving Pipeline for Face-Centric Generative Image Editing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-03-03T18:27:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dipesh Tamboli, Vineet Punyamoorty, Atharv Pawar, Vaneet Aggarwal</p>
    <p><b>Summary:</b> Recent advances in generative image editing have enabled transformative applications, from professional head shot generation to avatar stylization. However, these systems often require uploading high-fidelity facial images to third-party models, raising concerns around biometric privacy, data misuse, and user consent. We propose a privacy-preserving pipeline that supports high-quality editing while keeping users in control over their biometric data in face-centric use cases. Our approach separates identity-sensitive regions from editable image context using on-device segmentation and masking, enabling secure, user-controlled editing without modifying third-party generative models. Unlike traditional cloud-based tools, PRIVATEEDIT enforces privacy by default: biometric data is never exposed or transmitted. This design requires no access to or retraining of third-party models, making it compatible with a wide range of commercial APIs. By treating privacy as a core design constraint, our system supports responsible generative AI centered on user autonomy and trust. The pipeline includes a tunable masking mechanism that lets users control how much facial information is concealed, allowing them to balance privacy and output fidelity based on trust level or use case. We demonstrate its applicability in professional and creative workflows and provide a user interface for selective anonymization. By advocating privacy-by-design in generative AI, our work offers both technical feasibility and normative guidance for protecting digital identity. The source code is available at https://github.com/Dipeshtamboli/PrivateEdit-Privacy-Preserving-GenAI.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.03226v1">Adaptive Methods Are Preferable in High Privacy Settings: An SDE Perspective</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-03T18:17:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Enea Monzio Compagnoni, Alessandro Stanghellini, Rustem Islamov, Aurelien Lucchi, Anastasiia Koloskova</p>
    <p><b>Summary:</b> Differential Privacy (DP) is becoming central to large-scale training as privacy regulations tighten. We revisit how DP noise interacts with adaptivity in optimization through the lens of stochastic differential equations, providing the first SDE-based analysis of private optimizers. Focusing on DP-SGD and DP-SignSGD under per-example clipping, we show a sharp contrast under fixed hyperparameters: DP-SGD converges at a Privacy-Utility Trade-Off of $\mathcal{O}(1/\varepsilon^2)$ with speed independent of $\varepsilon$, while DP-SignSGD converges at a speed linear in $\varepsilon$ with an $\mathcal{O}(1/\varepsilon)$ trade-off, dominating in high-privacy or large batch noise regimes. By contrast, under optimal learning rates, both methods achieve comparable theoretical asymptotic performance; however, the optimal learning rate of DP-SGD scales linearly with $\varepsilon$, while that of DP-SignSGD is essentially $\varepsilon$-independent. This makes adaptive methods far more practical, as their hyperparameters transfer across privacy levels with little or no re-tuning. Empirical results confirm our theory across training and test metrics, and empirically extend from DP-SignSGD to DP-Adam.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2603.03108v1">RAIN: Secure and Robust Aggregation under Shuffle Model of Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-03-03T15:41:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuhang Li, Yajie Wang, Xiangyun Tang, Peng Jiang, Yu-an Tan, Liehuang Zhu</p>
    <p><b>Summary:</b> Secure aggregation is a foundational building block of privacy-preserving learning, yet achieving robustness under adversarial behavior remains challenging. Modern systems increasingly adopt the shuffle model of differential privacy (Shuffle-DP) to locally perturb client updates and globally anonymize them via shuffling for enhanced privacy protection. However, these perturbations and anonymization distort gradient geometry and remove identity linkage, leaving systems vulnerable to adversarial poisoning attacks. Moreover, the shuffler, typically a third party, can be compromised, undermining security against malicious adversaries. To address these challenges, we present Robust Aggregation in Noise (RAIN), a unified framework that reconciles privacy, robustness, and verifiability under Shuffle-DP. At its core, RAIN adopts sign-space aggregation to robustly measure update consistency and limit malicious influence under noise and anonymization. Specifically, we design two novel secret-shared protocols for shuffling and aggregation that operate directly on additive shares and preserve Shuffle-DP's tight privacy guarantee. In each round, the aggregated result is verified to ensure correct aggregation and detect any selective dropping, achieving malicious security with minimal overhead. Extensive experiments across comprehensive benchmarks show that RAIN maintains strong privacy guarantees under Shuffle-DP and remains robust to poisoning attacks with negligible degradation in accuracy and convergence. It further provides real-time integrity verification with complete tampering detection, while achieving up to 90x lower communication cost and 10x faster aggregation compared with prior work.</p>
  </details>
</div>

