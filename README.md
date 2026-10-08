
<h2>2026-09</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.00822v1">TRACE: Privacy-Preserving Next-Best-View Selection over Distributed 3D Gaussian-Splat Maps</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E">
  <p><b>Published on:</b> 2026-09-30T23:32:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Amirhossein Mollaei Khass, Athanasios Cosse, Qiyu Sun, Nader Motee</p>
    <p><b>Summary:</b> Share the light, not the map. We study next-best-view selection for a team of robots, each of which builds its own 3D Gaussian Splatting map and keeps it private. A robot picks the view with the largest expected information gain (EIG) about the splats along its own path. This gain depends on the other maps. Their splats occlude its own and shine behind them, so the gain has to be evaluated against the pooled map. No robot has this map. We show that the coupling passes through only two ray quantities, the transmittance in front of a splat and the radiance behind it, and that both are sums over the hits of the ray. Hence, they decompose across the robots, and each robot sums them over depth bins in its own map, along the rays of a candidate view, and sends the sums with their pose derivatives. The robot planning the view turns them into its EIG and gradient on SO(3). Transmittance and Radiance Aggregates, communicated for the EIG, give the protocol its name: TRACE. No robot shares its splats, and the message size does not grow with a map. We prove that the reconstruction is exact unless a depth bin behind a splat mixes hits of two robots, and we bound the error otherwise. Over 100 next-best-view decisions in Habitat-Sim, TRACE picks a heading within 15 degrees of the centralized one in 83.3% of the cases, and its views reach 97.9% of the centralized EIG.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.39787v1">Privacy Foundations for Multi-Institutional Scientific Artificial Intelligence</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-30T14:08:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Olivera Kotevska, Sumit Jha, Aurélien Bellet, Rui Hu, Nathaniel D. Bastian, Rafael Ferreira da Silva, Ravi Madduri, Kibaek Kim</p>
    <p><b>Summary:</b> Scientific artificial intelligence (AI), spanning foundation models (FMs) to federated data-analysis pipelines, is becoming shared infrastructure across national laboratories, universities, hospitals, and industrial partners. This collaboration creates privacy risks whose natural unit is often an institution's participation, research strategy, or technical capability rather than a single record. Differential privacy (DP), federated learning (FL), secure computation, trusted execution, and provenance each protect parts of the stack, but their guarantees rarely compose across mixed-trust institutions, access tiers, and autonomous agents. This perspective recasts privacy for scientific AI as an assurance problem defined by six elements: protected asset, observer, channel, permitted disclosure, guarantee, and evidence. We demonstrate the framing through a claim register for a composite cross-institutional scenario and use it to assess the model lifecycle. Two of the resulting gaps are specific to leadership-class facilities: scheduler, allocation, and telemetry metadata expose an institution's resource posture, and instrument-attached control loops leak research strategy through timing and contention on shared accelerators. We identify six research priorities: institution-level guarantees, agent-communication privacy, cross-tier information flow, privacy-compatible reproducibility, leadership-scale accounting, and instrument side channels. The contribution is a common form for stating, comparing, and auditing claims whose guarantees otherwise remain fragmented across the scientific AI stack.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.39362v1">Link Inference Attack on Privacy-Preserving Knowledge Graphs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-30T09:18:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Emna Bouguerra, Ibtissam Harrouche, Ferran Alborch, Melek Önen</p>
    <p><b>Summary:</b> Knowledge Graphs (KGs) are widely used to store and share structured information across sensitive domains such as healthcare, fi- nance, and social networks. A common privacy practice is to delete sen- sitive relations before publishing the graph, under the assumption that removing edges is sufficient to prevent their recovery. In this paper, we challenge this assumption and show that even when a relation is fully or partially hidden, its existence leaves structural traces in the public graph that can be exploited to recover it with high accuracy. To this end, we propose a link inference attack that operates on the topology of the public graph, and evaluate it under two privacy scenarios that differ in how the adversary exploits the knowledge available to him. In the first setting where the adversary exploits all topological information, the attack achieves near-perfect discrimination (AP = 0.949, ROC-AUC = 0.999), while in the more realistic one where the adversary makes use of some semantic information, it recovers up to 74% of hidden edges. Build- ing on these results, we further conduct a structural analysis to identify which topological properties of the graph drive the attack success, re- vealing that privacy risk is not uniform across entities and that certain structural patterns make specific relations significantly more vulnerable to inference than others.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.38934v1">PrivCert: Certifying Statement Support under Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-30T04:12:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tsubasa Takahashi, Takumi Hiraoka</p>
    <p><b>Summary:</b> Differentially private (DP) text generation can protect individual records, but privacy alone does not specify what evidence a released statement carries about the underlying data. We identify this as an evidence gap: a private report may contain plausible claims without indicating whether they are strongly supported by the private dataset. We introduce PrivCert, a framework for privacy-preserving reporting that makes statement support explicit through privacy-preserving certificates and emit-or-abstain decisions. As a canonical instantiation, PrivCert-PF (Proposal-and-Filter) separates data-independent candidate discovery from private support certification, emitting only statements whose support passes a private evidence test. We provide theoretical grounding for this framework by characterizing the limits of implicit evidence under DP, deriving a sharp privacy--honesty frontier for single-statement certification, and establishing a worst-case cost for fine-grained multi-statement certification. Experiments on synthetic tasks and TAB, WildChat, and Yelp show that explicit certification maintains low unsupported emission, while free-text DP baselines frequently produce low-support claims under the same declared support semantics. We further show that the PrivCert contract can be realized with histogram, sparse-vector, and Gaussian mechanisms, and use DP synthetic data to illustrate an important boundary: support in a private proxy does not automatically certify support in the original data. Together, these results position privacy-preserving reporting as an evidence-design problem: not only how to generate private text, but what a private report can substantiate about its underlying data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.38830v1">SparLeak: Privacy Leakage from Sparse Attention in LLM Inference on Shared GPUs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-30T02:52:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fahao Chen, Linkang Du, Jinhao Zhou, Peng Li, Zhou Su</p>
    <p><b>Summary:</b> Sparse attention is widely used to accelerate long-context inference in modern large language models (LLMs), but its input-dependent execution behavior introduces previously unexplored privacy risks. We identify a new GPU micro-architectural side channel, termed Sparsity-Induced Memory Access (SIMA), which arises from secret-dependent key-value cache access patterns induced by sparse attention.
  Based on this observation, we present SparLeak, a phase-aware side-channel attack that extracts SIMA traces during LLM inference and enables two practical privacy extractions: query attribute inference from prefill-phase traces and autoregressive response reconstruction from decoding-phase traces. By reconstructing approximate token-level sparsity profiles from page-level observations and applying profiling-based learning, SparLeak accurately recovers sensitive information, including user-query attributes and private LLM response content. Extensive evaluation across three LLM architectures, three sparse attention mechanisms, and three privacy-sensitive datasets shows that SparLeak achieves average attack success rates of 90.9% for attribute inference and 87.3% for response reconstruction under real-world LLM serving settings, highlighting the significance to account for SIMA leakage when deploying sparse-attention-based LLM systems. We provide anonymized SIMA traces, trained attack models, evaluation scripts, and documentation as artifacts at https://anonymous.4open.science/r/Janus_artifacts/.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.38630v2">Strong Multilingual Privacy Tagging at Encoder Speed</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-09-29T22:41:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jonathan Graehl</p>
    <p><b>Summary:</b> Privacy redaction must remove personal information while preserving relationships expressed in text. We develop a multilingual named-entity tagger with fine-grained distinctions supporting varied redaction policies and methods for cheaply learning additional distinctions. We fine-tune a multilingual encoder with an affine span-tagging head on frontier-model annotations in 35 languages, replay mapped human gold with coverage-aware masking so unannotated types are not treated as negatives, and repair subword boundaries with a learned +/-1-character adjustment. On 1,283 human-gold test segments in seven languages, best measured redaction F1 is 88.8, against 69.1 for published GLiNER2 with 11 unrepresentable types excluded from its task (68.8 without that exemption), 67.8 for GLiNER2 adapted to the new training data, 57.3 for Microsoft Presidio and 35.8 for the best published OpenAI Privacy Filter fine-tune. Adding about 50,000 annotated training sentences and increasing human-gold replay improves exact typed-span F1 from 74.5 to 76.3 on Ont3, our 31-type frontier-annotated NER evaluation of 1,201 development segments. Mapped-gold replay alone raises human-gold F1 by ten points without loss on frontier-annotated text; boundary adjustment adds 1.7 exact typed-span F1 points on Ont3. Local LLMs fitting on a single 96-GB GPU underperformed as prompted annotators and frozen encoders, with encoding 30-95 times slower than XLM-R inference and prompted annotation roughly 180-1,100 times slower in the evaluated configurations. The encoder architecture delivers 4.9 times GLiNER2's CPU throughput. We release code, prompts and training recipes, with data-acquisition scripts and source links.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.38458v1">PrivMeSA: Privacy-Aware Self-Evolving Multi-Agent System for Medicine via Local-Remote LLM Collaboration</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-09-29T19:47:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dannong Wang, Yuran Zhang, Bian Sun, Alex Stinard, Yuzhang Shang, Song Wang, Yu Tian</p>
    <p><b>Summary:</b> Clinical large language model (LLM) agents deployed locally can consult more capable remote models, but doing so risks exposing patient information. Privacy-conscious delegation places disclosure decisions with a local agent, yet removing explicit identifiers is insufficient: quasi-identifiers can accumulate across multi-turn consultations and repeated patient visits to enable re-identification. We introduce PrivMeSA, a privacy-aware self-evolving multi-agent system that learns to control disclosure and retains remote expertise for local reuse. A local agent manages each encounter and consults remote specialists that may request additional information. Reinforcement learning balances task accuracy against direct disclosure and registry-based re-identification risk, with privacy evaluated over the complete outbound transcript of each encounter. A local lesson memory distills completed consultations into generalized clinical guidance and retrieves relevant lessons before transmission, allowing subsequent cases to reuse expertise without another remote exchange. Memory grows without additional outcome labels or parameter updates. On an emergency-department benchmark built from MIMIC-IV-ED records, PrivMeSA improves mean task accuracy over delegation by up to 15.8 percentage points. In the same setting, PrivMeSA reduces the disclosure of personal details from 98.0% to 0.2% of cases and the share of cases in which the patient can be narrowed to ten or fewer registry patients from 74% to 0%.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.38339v1">Aegis: Generative Gradient Masking for Privacy-Preserving Medical Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-09-29T18:05:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chaoyu Zhang, Shanghao Shi, Heng Jin, Ning Wang, Y. Thomas Hou, Wenjing Lou</p>
    <p><b>Summary:</b> Federated learning (FL) has become a foundational paradigm for multi-institutional medical AI, allowing hospitals and research centers to jointly train diagnostic models without exchanging patient records. This privacy promise, however, is increasingly contested: a malicious or honest-but-curious server can launch model inversion attacks (MIAs) that reconstruct private patient images directly from shared model updates, and recent scalable, closed-form attacks penetrate even secure aggregation at clinically realistic batch sizes. Existing defenses face an unsatisfactory dilemma. Gradient-perturbation methods such as differential privacy and pruning trade away the diagnostic accuracy on which clinical reliability depends, while cryptographic protocols add system complexity yet still leave updates exposed to these scalable attacks. We propose Aegis, a principled client-side defense that breaks this dilemma without perturbing patient data or modifying the FL protocol. Our key insight is that the success of every known MIA is fundamentally bounded by the local batch size relative to the model's leakage capacity; once this limit is exceeded, distinct samples collide and reconstructions collapse into indistinguishable mixtures. Aegis turns this universal bottleneck into a defense: each client superimposes onto its real update a masking gradient computed on locally synthesized, task-relevant data, deliberately pushing the effective batch beyond the attack's recovery capacity. We complement the design with theoretical convergence guarantees under standard convex assumptions and evaluate Aegis on MNIST, CIFAR-10, and three MedMNIST modalities (chest X-ray, abdominal CT, colon pathology). Aegis neutralizes three state-of-the-art MIAs while preserving model utility and incurring only modest overhead, offering a practical privacy primitive for medical FL.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.38306v1">Making the most of leftovers: Improved privacy amplification for quantum key distribution</a></h3>
  
  <p><b>Published on:</b> 2026-09-29T18:00:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Matthew Simon Tan, Bartosz Regula, Marco Tomamichel</p>
    <p><b>Summary:</b> The amount of secret key that can be obtained from a quantum key distribution run depends on both the physically observed error rates and the mathematical bounds used to certify security. For finite datasets, conservative bounds force users to discard a substantial fraction of the potentially available key. Here we further refine and extend the privacy amplification bounds achievable through the recent leftover hash lemma of Regula and Tomamichel [arXiv:2603.04493] and incorporate them into the security analysis of quantum key distribution based on entropic uncertainty relations. This improves on state-of-the-art key rates in finite-block regimes, certifying more secret key from the same experimental data without changes to the protocol, and outperforming techniques based on entropy accumulation. The results illustrate how sharper mathematical estimates can directly increase the usable output of a quantum communication system.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.38289v1">Privacy in Personalized AI Is a System Property, Not Just a Model Property</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-29T17:06:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guillaume Salha-Galvan, Jiaying Xu</p>
    <p><b>Summary:</b> In personalized AI applications, such as conversational assistants and recommender systems, users interact not with models in isolation but with broader systems that access, infer, and reuse user information across components and over time. While such use of user information is integral to personalization, it also raises important privacy questions. In this paper, we argue that individual model- or component-level analyses may not capture all privacy risks arising in such systems, motivating a system-level perspective on privacy. We distinguish and analyze four interconnected privacy-risk channels in personalized AI, and subsequently propose four requirements for system-level privacy evaluation, covering interaction trajectories, internal information flows, indirect leakage, and the privacy-utility trade-off. We argue for their systematic incorporation into privacy audits of personalized AI.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.38281v1">Beyond the Headset: A Systematization of Knowledge on Extended Reality Privacy and Security in Healthcare</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-09-29T16:05:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nafisa Anjum, M. Rasel Mahmud</p>
    <p><b>Summary:</b> Extended reality (XR) systems are increasingly used in healthcare applications ranging from surgical planning to remote rehabilitation and mental health support. However, the rich streams of sensor, biometric, behavioral, and environmental data that enable these applications also introduce substantial privacy and security risks. Adversaries may exploit insecure communication, sensor side channels, application-layer vulnerabilities, or data-processing pipelines to infer sensitive information or disrupt clinical workflows. Despite growing interest in XR security and privacy, the healthcare-specific literature remains fragmented. In this Systematization of Knowledge (SoK), we review 65 peer-reviewed studies published between 2017 and 2024 across XR, security, privacy, and healthcare venues. We develop a unified threat taxonomy spanning device, user, network, and cloud layers and introduce XR-PRISM, a quantitative Privacy and Risk Impact Scoring Metric for systematically characterizing security and privacy risks. Our analysis identifies several gaps in the literature: more than 70% of proposed countermeasures lack standardized risk evaluation, fewer than 15% of studied attacks require high attack prerequisites, and reproducibility is limited by the scarcity of publicly released artifacts and datasets. Based on these findings, we outline a research roadmap emphasizing shared benchmark datasets, stronger artifact-release practices, improved cloud-layer protections, and more comprehensive detection, mitigation, and recovery mechanisms. This SoK provides a structured and data-driven foundation for understanding existing risks and guiding the development of more secure, privacy-preserving, and usable XR healthcare systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.37667v1">Where Privacy Belongs: Placement Diagnosis and Certified Selection for Private Counterfactual Explanations on Graphs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-29T14:23:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuxiang Yao, Zijun Zhao</p>
    <p><b>Summary:</b> Counterfactual explanations for graph neural networks (GNNs) find the minimal intervention that flips a node's prediction--but computing one requires reading sensitive graph structure, and releasing it discloses that structure. Both existing placements fail. Privatizing the graph before explaining corrupts the target on exactly the borderline nodes needing recourse, manufacturing spurious flips that flip the privatized graph but not the true one. Explaining on the clean graph and perturbing the released explanation resists certification: re-auditing the standard heuristic shows an implied full-release budget of 573--753 on Cora and 256 on CiteSeer--orders of magnitude beyond its advertised budget--with worst-case single-entry leakage at AUC 1.0. We propose PrivCFS, which replaces certification-by-optimization with certification-by-construction: counterfactual selection over a fixed, data-independent candidate universe--edge interventions from a public prior graph, feature interventions from a public schema--whose no-op semantics give neighboring graphs the same output support. A validity-gated, clipped utility of global sensitivity $Δu \le 1$ released through the exponential mechanism gives pure $\varepsilon$-DP for the complete released object, composable over queries--to our knowledge the first such guarantee on graphs. Privacy noise is the cheapest stage: at $\varepsilon$=8 the release retains 94--97% of its support-restricted non-private optimum on the recourse population and 83--95% on the general one; the optimal edge-inference audit attains AUC 0.50 on average and 0.59 worst-pair, versus the heuristic's worst entry 1.0; and transfers to a 15K-node graph at 0.96 valid rate. The dominant cost is a measurable, monotone price in public disclosure, readable off one table before any budget is spent--turning explanation privacy from an accounting risk into a purchasable decision.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.37344v1">A Sharp Transition in Data Reconstruction under Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> 
  <p><b>Published on:</b> 2026-09-29T12:12:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Max Cairney-Leeming, Simone Bombari, Marco Mondelli</p>
    <p><b>Summary:</b> Data reconstruction attacks have empirically been successful in recovering training samples from learned models, raising privacy concerns and motivating defenses with guarantees that remain valid against future threats. While differential privacy (DP) provides formal protection, choosing the privacy budget remains a challenge: small budgets severely reduce utility, but it is hard to quantify how large the budget can be without allowing accurate reconstruction. In this work, we study informed attackers who aim to reconstruct a single $d$-dimensional training sample from a $ρ$-zero-concentrated DP model, knowing all other training data. Our main contribution is to establish a sharp transition at $ρ\asymp d$ for data reconstruction: on the one hand, we derive entropy-based lower bounds for any private mechanism and any attack, characterizing a set of target priors for which reconstruction is information-theoretically impossible for $ρ\ll d$; on the other hand, we analyze a simple attack on private linear regression with output perturbation, showing that reconstruction is practically feasible for $ρ\gg d$. Remarkably, the transition moves to $ρ\asymp s$ for data lying in an $s$-dimensional subspace, demonstrating that the privacy budget guaranteeing adequate protection must be assessed in terms of the effective dimension of the data. We validate our findings via experiments on synthetic data and natural images (CIFAR-10, ImageNet).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.36153v1">Privacy-Friendly Cohort Determination: Sealed, CSP-Independent In-Browser ML Inference of Professional Segments for Identity-Less Advertising</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-28T19:24:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Om Shankar Tiwari, Navnit Shukla, Guanyu Wang, Akshay Jain</p>
    <p><b>Summary:</b> B2B advertising targets a viewer's professional attributes (employer size and industry, function, seniority) and has obtained them by matching identities across sites. Safari and Firefox block third-party cookies, Google retired the Privacy Sandbox cohort APIs in 2025, and reverse-IP firmographics decay under remote work. We present SIF (Sealed Inference Frame), which infers coarse professional cohorts on the device and emits only a locally differentially private, taxonomy-coded label into the OpenRTB bid stream, with no cross-site identifier. It rests on a property of the web platform we make precise: a navigated cross-origin iframe is the only way third-party code obtains a policy it controls, so inference runs in WebAssembly even where the publisher's CSP forbids it, and a nested worker served with default-src 'none' gives the model no network. Even a malicious model leaks at most about 5 bits per site per week. Labels pass through a memoised k-ary randomised response keyed to the publisher's first-party identifier, which gives $\varepsilon$-local differential privacy, defeats averaging, and links requests no better than the identifier already sent. An org-conditional k-anonymity rule suppresses cells, more strictly on corporate networks than at home. Cohorts ride OpenRTB user.data in a LinkedIn-aligned taxonomy, and attribution uses LinkedIn's click-scoped li_fat_id without bridging identities. We report a crawl of CSP deployment on 7,969 top sites and 431 B2B publishers, Heavy-Ad budgets, closed-form privacy-utility trade-offs, a re-identification simulation, and an assessment of which attributes are predictable at all: company type and size are, seniority largely is not. On-device is a design property, not a consent exemption.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.35951v1">When Privacy Becomes a Weapon: Understanding Doxxing and Privacy Vulnerabilities in Mainland China's Social Media Ecosystem</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-09-28T17:29:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiao Zhan, Shijing He, Chi Zhang, Jose Such</p>
    <p><b>Summary:</b> Doxxing, the malicious disclosure of personal information, has become a pervasive privacy threat. Yet existing research remains predominantly Western-centric, limiting our understanding of how doxxing unfolds in contexts where mandatory identity systems, platform governance, and cultural logics fundamentally reshape privacy risks and harm trajectories. We address this gap through semi-structured interviews with 18 doxxing survivors in mainland China, synthesizing their experiences into a framework conceptualizing how doxxing operates in this context. Our findings reveal both patterns echoing prior Western findings, such as platform amplification mechanisms that resonate with Western findings, and China-specific dynamics shaped by the interplay of regulatory mandates (compulsory identity linkage) and cultural logics including nationalist discourse, fandom culture, Confucian values, and low privacy literacy. Survivors' experiences further reveal how doxxing reshapes understanding of privacy: from preference to precondition, from momentary disclosure to temporal vulnerability, and from individual control to structural powerlessness. These insights challenge agency-centered privacy frameworks and suggest that effective protection requires constraining systemic vulnerabilities rather than relying solely on user empowerment. We conclude by proposing multifaceted recommendations spanning legal reform, platform design, and social initiatives.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.35534v1">Privacy-Aware ISAC for Full-Duplex Monostatic Systems Using Movable Antennas</a></h3>
  
  <p><b>Published on:</b> 2026-09-28T16:17:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yasas Savinda, Mohammadali Mohammadi, Himal A. Suraweera, Henk Wymeersch</p>
    <p><b>Summary:</b> This work investigates sensing privacy in full-duplex (FD) monostatic integrated sensing and communication (ISAC) systems with movable antennas (MAs). The proposed approach jointly optimizes beamforming and antenna trajectories to create a deceptive dummy DD-bin response at a passive sensing eavesdropper (Eve), while satisfying a true-bin sensing-quality requirement at the base station (BS). The resulting problem is highly non-convex. {To address this, a stage-wise alternating local-search framework is developed to obtain suboptimal solutions. Within this framework, we maximize the worst-case margin between dummy and true delay-Doppler (DD)-bin detector-oriented SINR surrogates over a discretized uncertainty region for Eve, incorporating detector-aligned dummy-bin refinement and true-bin preservation.} Simulation results show that the proposed MA-enabled design suppresses Eve's true-target DD-bin selection and increases dummy-bin selection probability compared with benchmark schemes, while maintaining reliable BS sensing performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.35937v1">PrivacySkills: How Privacy Guidance Shapes Source Selection in LLM Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-09-28T15:22:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lucas Biechy, Cédric Eichler, Héber H. Arcolezi, Nicolas Anciaux</p>
    <p><b>Summary:</b> While prior work has documented privacy failures in LLM agents, it remains unclear how the presentation of privacy guidance influences their choice of information sources. We introduce PrivacySkills, a controlled framework for evaluating how agents choose among acquisition pathways that provide the same task-relevant value: consulting publicly available personal information, accessing confidential sources, or interacting with the user. The evaluation framework comprises 55 synthetic tasks spanning 11 categories of personal information, with 169 associated skills that describe the available acquisition pathways. We consider privacy guidance through system-level instructions, skill-level metadata labels, or both. Separately, we vary user availability and urgency framing. With users available and no privacy guidance, agents access confidential sources in 30% of valid runs on average across five open-weight models, despite sufficient alternatives. This rate increases to 45% when users are unavailable, whereas urgency framing has no detectable effect. System-level privacy instructions alone have limited effects on confidential access, while skill-level intrusiveness labels produce a modest reduction (24% on average), but combining the two roughly halves confidential access. Our findings motivate incorporating privacy annotations into skill specifications and evaluating their effectiveness alongside system-level instructions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.35234v1">Poster: Towards ProofWeave: A Privacy-Minimised, Integrity-Anchored Evidence Plane for Continuous Agentic Assurance</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-28T14:11:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guy Lupo, Nguyen Hung Nguyen, Viet Vo, Chamikara M. A. P., Guangdong Bai</p>
    <p><b>Summary:</b> Agentic AI systems increasingly act via tools, memory, delegation, and external services. Existing observability and provenance mechanisms can reconstruct events post hoc, but they rarely show, at the time of the record, whether each policy-relevant action was checked by the intended control before execution. This leaves a trust-observability gap for continuous monitoring, detection, and response: later assurance may rest on evidence that is incomplete, privacy-leaking, mutable, or detached from the policy context that governed the event. What's missing in the literature is contemporaneous, policy-bound evidence that the intended control was evaluated under the policy in force at the time.
  We introduce ProofWeave, a record-time chain-of-evidence concept for agentic AI assurance. At each policy-relevant action boundary, ProofWeave generates a privacy-minimised and integrity-anchored evidence transaction that binds (i) agent intent or action, (ii) control response, and (iii) a policy-at-time snapshot. Each transaction is committed to an append-only ledger and materialised into a derived proof graph. A bounded Weaver Agent translates policy intent into proof obligations, while deterministic validators check evidence completeness, privacy minimisation, policy binding, and integrity.
  In the minimal scenario, an agent attempts to transmit a secret to an unapproved external sink. The audit compares a logs-only correlation baseline with ProofWeave across verdict latency, join ambiguity, privacy exposure, tamper detection, and resistance to graph-only proof injection. ProofWeave reduces candidate bindings per verdict from up to `10,201` to one, validation operations from up to `10,201` to approximately `26`, and assurance evidence storage from `0.79`MiB to `0.15`MiB per project.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.35233v1">EP-Mem: Elastic Privacy Memory for Social Relationship-Aware LLM Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-09-28T14:10:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fengzhou Sun, Yuan Zhang, Xintong Yu, Jinyao Yan</p>
    <p><b>Summary:</b> Large language model (LLM) agents face critical privacy risks when acting as delegates in human-agent-human communication. To prevent such breaches, agents must understand users' social relationships and adhere to context-dependent social information disclosure boundaries. Current studies on agent memory privacy focus on instantaneous interactions, leaving the long-term relational disclosure problem unexplored. In this paper, we propose EP-Mem, an Elastic Privacy Memory architecture that reframes privacy as user-owned boundary control across social roles. EP-Mem introduces (1) token-level memory driven by user-configurable a privacy policy that stratifies persons and events, combining domain-level default circulation rules with fact-level whitelist/blacklist exceptions; and (2) a pluggable sidecar with a privacy engine that aligns disclosure controls with memory across summary, detail, and boundary granularities, enforced throughout generation, storage, and retrieval. We construct EP-Bench, to our knowledge the first long-term multi-party benchmark with cross-session correlated events for policy-conditioned relational disclosure. Experiments show that EP-Mem achieves 94.0% privacy classification accuracy, improves disclosure-permission judgment from 22% to 68%, and reduces privacy leakage by 75.6%, while maintaining retrieval performance and cross-benchmark generalization.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.34768v3">Privacy-Preserving Full-Body Meshing from mmWave Radar via Mesh Foundation Model Supervision</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-09-28T09:49:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuxing Zhang, Yongquan Ni, Zhenyu Ding, Yawen Lin</p>
    <p><b>Summary:</b> Millimeter-wave (mmWave) radar enables privacy-preserving human perception, but the extreme sparsity of point clouds from commercial single-chip sensors (mean ~6.5 points/frame; ~28% empty frames) has confined prior art to body-part keypoints or discrete action classification. We present a cross-modal teacher-student framework that lifts commercial radar to full-body, per-frame, metric 3D mesh reconstruction with per-joint uncertainty. Three innovations: (1) a mesh-foundation-model teacher - SAM 3D Body produces whole-body MHR ground truth (70 joints, 18,439 mesh vertices) from a single RGB frame with zero training, slashing annotation cost by orders of magnitude; (2) StudentPoseFormer - set encoding with masked attention pooling, a temporal Transformer, and a CVAE multi-hypothesis head that outputs both the pose mean and per-joint variance, honestly reporting where the radar cannot see; and (3) a multi-stage ground-truth quality pipeline (confidence gating, depth validation, temporal smoothing, bone-length consistency, bad-frame rejection) plus systematic information-lever ablations. On the public MM-Fi benchmark (same TI IWR6843 sensor, cross-subject), our full configuration reaches 7.45 cm 12-joint MPJPE, with ablations proving the causal value of point accumulation (k = 3, -0.34 cm), Doppler (-0.85 cm; -2 cm at the wrist on fast actions), and velocity loss (-0.27 cm). On our own synchronized radar + RGB-D corpus with block-level held-out splits, the pipeline achieves 21.47 cm end-to-end (per-joint hierarchy from 4.8 cm at the hip to 34.7 cm at the wrist - matching physical information limits), could be improved to 15 cm with ~30k diverse samples, and a scaling law shows sample diversity, not volume, is the binding constraint. Deployment inference is radar-only - no camera, no image.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.34411v2">Coherence Rather Than Error Rate Governs Privacy in Multi-Tenant Quantum Computing</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-28T06:25:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Farhad Farokhi</p>
    <p><b>Summary:</b> Multi-tenant computing enables providers of commercial cloud quantum processors to rent disjoint sectors of a device to independent users. Average gate error, which cloud quantum computing providers report, does not determine how much one tenant learns about another. We propose an information-theoretic notion of information leakage across co-tenancy boundaries stemming from quantum state distinguishability. We measure this leakage on commercially-available 156-qubit (IBM Kingston) and 20-qubit (IQM Garnet) devices. Boundaries with identical benchmarked error can offer significantly different amount of information leakage because standard reported measures of error are blind to coherent-versus-stochastic nature of the error while the proposed notion of information leakage is not. A uniform Pauli randomisation implemented over the victim's whole register is used as a defence mechanism to reduce the information leakage to zero. The defence theoretically does not incur a fidelity cost, but the experiments show a non-trivial degradation caused by accumulation of errors. We provide a specific call-for-action to the providers of quantum cloud computing to report information leakage in addition to standard error rates in their device datasheet to enable users to compute privacy and security risks prior to engagement with the device.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.34220v2">mmHRI: Towards Privacy-Preserving Human-Robot Interaction with Millimeter-Wave Radar</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-09-28T03:24:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Junqiao Fan, Yuxuan Hu, Bofan Lyu, Yanshuo Lu, Pengfei Liu, Jiarui Zhang, Fangqiang Ding, Lihua Xie, Gen Li, Jianfei Yang</p>
    <p><b>Summary:</b> Assistive robots increasingly operate in many human-centered environments and perform various human-robot interaction (HRI) tasks, such as object delivery. However, most existing HRI systems rely on RGB cameras that continuously observe humans to respond to non-verbal commands, such as hand gestures. This raises privacy concerns in privacy- critical environments, such as hospital wards or restaurants, where direct camera observation of humans is restricted. To develop privacy-preserving HRI, we leverage millimeter-wave (mmWave) radar, which can sense human motion through privacy barriers without identifiable imagery. We propose mmHRI, the first multi-modal robot manipulation framework that achieves mmWave radar-guided privacy-preserving HRI. mmHRI introduces two key designs to mitigate the sparsity and temporal inconsistency of radar data in cluttered robot manipulation environments. First, we propose a dual-stream architecture that jointly learns from unfiltered raw radar tensors and radar point clouds to estimate both human actions and 3D poses. To mitigate signal inconsistency, mmHRI further incorporates a memory-based state-space model (MSSM) that retains historical radar features to reduce abrupt changes in pose/action. These estimated human states are then converted into structured textual robot instructions, which control a vision-language-action (VLA) policy for closed-loop robot manipulation and human-aware reactions. Our evaluation covers human action recognition and closed-loop delivery and retrieval. In the privacy-preserving curtain setting, mmHRI achieves 85.09% action-recognition accuracy, outperforming existing radar-based alternatives. Robot trials further demonstrate successful delivery and retrieval under visual occlusion, with stable task performance across unseen subjects, clutter configurations, and environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.33985v1">The Privacy Fallacy of Crowdsourced Fine-Tuning: Extracting Proprietary Data via Topic-Based Poisoning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-27T22:36:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sae Furukawa, Alina Oprea</p>
    <p><b>Summary:</b> Supervised fine-tuning (SFT) is widely used to adapt large language models to downstream tasks. Crowdsourcing user conversations is an established approach to collecting SFT data at scale while reducing the need for costly manual annotation. However, it also allows untrusted users to contribute data to the fine-tuning pipeline. We investigate an underexplored privacy risk arising from this setting: can a malicious user poison a small fraction of the crowdsourced data to amplify extraction of previously unseen instructions contributed by other users? We show that this is possible using only black-box, output-only access to the deployed model. Experiments across four models and two datasets demonstrate substantial increases in training-data extraction: with only 50 poisoned examples, near-verbatim extraction reaches $3.71\times$ the rate without poisoning for Qwen2.5-14B on OpenMathInstruct and $3.08\times$ for Llama-3.1-8B on AceReason. Data filtering also proves largely ineffective in detecting poisoned samples: even the best-performing method achieves only 0.378 in F-1 score, leaving the majority of poisoned samples undetected. These findings demonstrate that seemingly benign crowdsourced contributions can amplify leakage of other records while remaining difficult to identify through data filtering.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.33754v2">Collaborative Synthetic Data for Privacy-Preserving Financial Fraud Detection Across Organizational Silos</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-09-27T16:53:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Simeon Allmendinger, Domenique Zipperling, Burhanettin Bahadir Kibar, Niklas Kühl</p>
    <p><b>Summary:</b> Organizations seek analytical value from AI, yet relevant data are often fragmented across organizations and constrained by privacy. This is acute in financial fraud detection, where rare fraud cases and imbalanced local datasets limit decision-relevant analytics. Federated learning enables collaboration without direct data sharing but does not resolve minority-class scarcity. Synthetic data generation can help, yet lightweight methods are interpolation-bound, while generative models require substantial data and computation. Existing collaborative generative approaches often rely on federated learning, imposing considerable organization-side training burdens. In this paper, we examine CollaFuse as a collaborative diffusion-based alternative for fraud detection and evaluate it across five fraud datasets. Compared with classical oversampling, local generative baselines, and centralized diffusion benchmarks, CollaFuse does not achieve the highest local fidelity but improves downstream fraud detection more consistently across most datasets. These findings suggest that synthetic data create analytical value less through local realism than through transferable cross-organizational structure.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.08831v1">Is Word Error Rate Enough? Rethinking Privacy Evaluation in Speech with Entity-Aware Metrics</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Multimedia-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36">
  <p><b>Published on:</b> 2026-09-27T11:50:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anjana Rajasekhar, Jule Pohlhausen, Nayana Jacob Alappattu, Anna Leschanowsky</p>
    <p><b>Summary:</b> As the use of smart devices continues to increase, their potential to capture sensitive speech content raises growing privacy concerns. It is therefore critical to develop techniques that prevent information leakage while preserving the utility of the audio, and evaluation metrics that accurately quantify the level of privacy without overestimating it. In this work, we evaluate the effectiveness of two obfuscation techniques in protecting speech content, with particular emphasis on named entities, by adapting entity-aware privacy metrics from the Natural Language Processing field to the speech privacy domain. Further, we investigate several attack scenarios and show that fine-tuning on entity-rich data improves attack performance for some entity categories but not others. Finally, we provide guidance on metric selection based on whether the obfuscation method preserves temporal alignment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.33312v1">When Privacy Moves ML-Mediated Decisions On Device: Information and Incentive Misalignment in Auctions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-27T07:25:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dipankar Sarkar</p>
    <p><b>Summary:</b> Moving ML-mediated decision making onto privacy-preserving clients decentralises the economic decision along with the inference. Shared budget constraints then depend on information that cannot be globally current, creating an information-structure failure that conventional pacing is not designed to solve. We study this information misalignment in an auction-logic-faithful on-device simulation with 36 campaigns and 50 devices. Accounting is in dimensionless integer score units; no currency semantics are claimed. Across 30 paired demand paths, proportional Even pacing overspends 17.77% after one tick of staleness and 1,669.31% after 50 ticks under the original 20-times budget pressure. The effect does not depend on that severe a budget: at two-times pressure, 50-tick overspend remains 106.95%. A visible-budget no-sale guard makes zero-lag compliance exact at this score-unit granularity, yet leaves 11.88% overspend at one tick because other devices' debits remain invisible. A declared bursty, heterogeneous-device sweep retains a strictly increasing mean lag curve. We derive a finite-window expected excess-debit bound under conditional charge caps and find positive paired slack in every bounded-value cell. A second, incentive misalignment arises when the ML/pacing score transformation is allowed to change payment units: 98.23% of rival auctions at one tick admit a profitable deviation. An executable implementation-level counterexample isolates the runner-up's multiplier in the winner's price. Critical-base-bid payment is per-auction DSIC conditional on current multipliers, but does not establish dynamic truthfulness and does not repair base-value ranking disagreement.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.33004v1">On the Usage of Verifiable Credentials in Privacy-Preserving Federated Analytics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2026-09-26T22:57:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Andreea-Elena Drăgnoiu, Ruxandra F. Olimid</p>
    <p><b>Summary:</b> Privacy-Preserving Federated Analytics enables multiple nodes to collaboratively derive statistical insights without exchanging raw data. However, ensuring node authenticity and data validation (avoiding concerns such as identity tracking, data linkage, or data leakage) remain fundamental challenges. This paper offers some insights into the feasibility of defining an authenticated, integrity-preserving data model by coupling FPPA with Verifiable Credentials defined within the Self-Sovereign Identity framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.32835v1">FinancialAuditBench: Benchmark Construction under Differential Privacy Using Real-World Priors</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-09-26T18:07:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jerry Huang, Sarvesh Babu, Matt Van Buren, Alexander Wang, Pranav Pillai, Arush Jain, James P. Burton, Julia Hockenmaier</p>
    <p><b>Summary:</b> As AI agents are becoming widely adopted in the financial services industry, careful measurement is essential to understand where they can be reliably deployed and where oversight and professional review remain necessary. Such measurement, however, is constrained by limited access to proprietary or privacy-sensitive data. Existing benchmarks therefore often rely on publicly available data, human- and/or LLM-authored tasks, or simplified settings. We introduce FinancialAuditBench, a benchmark for evaluating agents on financial statement audit tasks, along with a framework for systematically generating synthetic engagements. Our task generation framework leverages differentially private aggregate statistics from historical audits along with audit expertise contributed through over 1,100 hours of benchmark development and review. FinancialAuditBench consists of 90 tasks spanning workpaper completion and review across six synthetic audit engagements, each containing an average of 179 files. Evaluation on eleven frontier models shows that while agents complete substantial portions of staff-level audit tasks well, they sometimes perform inappropriate procedures or produce incorrect documentation. Beyond financial auditing, our framework offers an approach for systematically generating synthetic tasks for model evaluation and training in privacy-sensitive domains.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.32706v1">Learning to Refer: Client-Resolved Generation for Privacy-Aware Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-09-26T15:13:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jeongho Yoon, Chanhee Park, Yongchan Chun, Duong Tuan Thanh, Sungbin Han, Chanjun Park, Hyeonseok Moon, Heuiseok Lim</p>
    <p><b>Summary:</b> Cloud-based large language models (LLMs) require users to disclose plaintext data to service providers, creating privacy risks in sensitive domains. Existing privacy-preserving approaches often trade utility for protection, incur substantial computational or communication overhead, remain vulnerable to reconstruction from intermediate representations, or protect only a subset of the training and inference pipeline. We introduce Client-Resolved Generation (CRG), a genera- tion interface that separates server-side generation from the lexical realization of input-derived content. The client transmits only pooled and noise-perturbed rep- resentations, while input-derived output content is represented using request-local positional references and resolved to its original strings only on the client. This interface protects private input and input-derived output content during both train- ing and inference while allowing the service provider to keep its proprietary model parameters hidden from the client. At the same time, exact lexical reuse remains possible without directly exposing the reused content on the provider-visible gen- eration path. We evaluate CRG on medical and document-grounded QA, sensi- tive identifier transfer, and tool calling, together with reconstruction and raw-logit leakage analyses. On SealTools, CRG improves complete-call exact match from 57.3% to 79.9% over the input-privacy framework PPFT, with larger gains as more required output content can be resolved through references. Together, these results show that CRG provides a practical interface for privacy-sensitive cloud LLMs by reducing plaintext exposure across both input and output pathways while preserv- ing task utility and server-side model confidentiality.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.32293v1">TRAP: Understanding and Mitigating Privacy Memorization in Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-26T06:36:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Muhammed Ustaomeroglu, Ziyue Xu, Hanshen Xiao, Peter Cnudde, Guannan Qu, Holger R. Roth</p>
    <p><b>Summary:</b> Fine-tuning a language model on sensitive records can leave it able to reproduce them. We ask when this memorization arises and how to prevent it without knowing in advance which spans are sensitive. Our starting point is that most memorization scores and attacks share one statistical core: whether the model assigns a token more probability than some reference would. Taking as the reference a model trained on the complementary half of the same corpus gives the Target Reference Advantage (TRA), a per-token signal that separates what a model fit to a particular record from what it learned across records, and is cheap and differentiable. We then study what drives memorization during fine-tuning: it keeps growing well past the validation minimum, is larger on small datasets and at higher learning rates, and higher when the underlying task is harder. Early stopping removes much of it, but because it is chosen by aggregate validation loss it helps least for rare, hard-to-predict spans embedded in otherwise learnable text, which is exactly what sensitive information tends to be. We therefore introduce TRAP, a one-sided penalty on tokenwise TRA that acts only where the target model pulls ahead of its reference. On student essays with annotated personal information and clinical cases with patient identifiers, TRAP brings memorization near the level of an untrained model at little utility cost, where generic regularizers barely move and differential privacy gives up most of what fine-tuning bought.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.32030v1">Who Governs Data in the AI Era? A Computational Analysis of the U.S. Privacy Workforce in Job Postings</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-25T21:52:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ramazan Yener, Muhammad Hassan, Masooda Bashir</p>
    <p><b>Summary:</b> Privacy protection now spans legal, technical, and managerial duties, and demand for privacy professionals is growing across sectors. However, little is known about how employers define these roles. We analyze 1,143 U.S. privacy job postings from LinkedIn and Indeed. We examine job titles, salaries, competencies, certifications, education, experience, regulatory references, and AI-related language by using rule-based text mining. We also apply Topic Modeling (BERTopic) to the same postings and identify 18 latent themes which we grouped them into four categories. Our findings show that privacy roles are hybrid and they combine legal knowledge, technical skills, and interpersonal competence. Artificial intelligence appears in more than half of postings, with AI language spread across compliance, legal, governance and security themes. Our research indicates that AI governance responsibilities are often embedded within existing privacy roles, contributing to the rise of hybrid positions alongside dedicated AI governance roles.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.31310v1">Revisiting Certified Defense with Differential Privacy on Vision Transformers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2026-09-25T14:17:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jun Yan, Weiquan Huang, Qixian Zhang, Yan Bai, Shutai Zhang</p>
    <p><b>Summary:</b> Certified defenses that incorporate differential privacy have proven effective on Convolutional Neural Networks (CNNs), furnishing rigorous robustness guarantees against norm-bounded adversaries. However, the certified robustness behavior of Pixel Differential Privacy (PixelDP) remains largely unexplored with the self-attention architecture now dominating the deep-learning landscape. Given that the Transformer has a profound impact on our daily applications from the digital world to the physical world, it is crucial to study certified robustness through differential-privacy-style stability. To fill this research gap, we revisit this construction in Vision Transformers and identify a failure mode that is largely hidden in the convolutional setting. When noise is injected after the patch embedding, the Laplace mechanism with the inherited grouped $\ell_1$ sensitivity bound collapses to chance-level accuracy across noise scales, whereas the Gaussian mechanism remains trainable. This contrast isolates the source of failure: not the injected noise itself, but the geometry of the sensitivity constraint. We show that the attenuation induced by the inherited $Δ_{1,1}$ projection increases with layer width and kernel size according to a random-matrix scale $C/(\sqrt{M}+\sqrt{N})$. Replacing the $\ell_1$-type constraint with a spectral-norm constraint eliminates the collapse across datasets and architectures, but creates a fundamental obstacle: the repaired models no longer satisfy the sensitivity condition required by the standard Laplace certificate. We resolve this mismatch by deriving a dimension-free $(\varepsilon,\ δ)$-privacy guarantee for the Laplace mechanism under $\ell_2$ sensitivity through concentration of the privacy loss.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.31262v1">Deduplication-while-Training: A Resilient Paradigm for Privacy-Preserving Cross-Client Deduplication in Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-09-25T13:39:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rongxi Wang, Guanxiong Ha, Chunfu Jia, Yongsheng Lin, Minfen Gao, Hanmiaomiao Wang</p>
    <p><b>Summary:</b> Cross-client duplicate data in large language model training corpora degrades the efficiency of federated learning (FL) while exacerbating model memorization and privacy risks. Privacy-preserving cross-client deduplication effectively mitigates this issue by eliminating duplicate training data. However, existing schemes all follow a "Deduplication-before-Training" paradigm. This serially coupled paradigm incurs high fault-tolerance costs and lacks support for dynamic client joining.
  To this end, we propose an unexplored paradigm called "Deduplication-while-Training (DwT)", which enables concurrent deduplication and training. DwT transforms cross-client deduplication from a one-time, globally synchronous preprocessing operation into a continuous online service with state management, concurrent claiming, and failure recovery. By enabling state synchronization and task takeover, it minimizes the impact of client disconnections on the overall training progress while supporting the dynamic joining of clients. We design DwT-FL, a privacy-preserving deduplication system, to support DwT. By designing a concurrent state-claim mechanism and a hot-cold dual-queue scheduling strategy, DwT-FL enables the parallel execution of secure deduplication and model training, while effectively handling client disconnections and dynamic joins. Experimental evaluations demonstrate that, compared to the state-of-the-art scheme, DwT-FL significantly reduces the time overhead of failure recovery and dynamic joining by up to 93.04% and 94.18%, respectively. This provides an efficient and elastic concurrent deduplication scheme for dynamic and unstable FL environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.30692v1">LUMO (Lightweight Unified Multilingual Orchestrator): A Privacy Preserving Offline Voice Assistant</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-25T01:57:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Md. Mehedi Hasan Naeem, Mst. Kamrunnahar Ruma, Nafiza Anjum, Shakila Sultana, Md. Sujan Ali</p>
    <p><b>Summary:</b> Reliable voice interaction is essential in environments with limited internet connectivity and strong privacy. However, most existing voice assistants depend on cloud-based services, which leads to latency issues, dependency on internet access, and privacy vulnerabilities. This research presents LUMO (Lightweight Unified Multilingual Orchestrator), a privacy preserving offline voice assistant designed for edge computing environments. This system integrates local Automatic Speech Recognition (ASR), locally deployed quantized Large Language Model (LLM), and Text-to-Speech (TTS) synthesis into a fully offline pipeline running on a Raspberry Pi 5 with 8 GB RAM.
  To enable efficient operation on resource constrained hardware, the language model is compressed using 4-bit GGUF quantization, which reduces memory usage while preserving practical conversational capability. Existing edge based voice assistants Mycroft provides partial offline functionality without a generative LLM, with an approximate latency of ~5 s and power consumption of ~12 W, while Rhasspy supports full offline operation but lacks generative capabilities, with ~3 s latency and ~11 W power usage. In contrast, LUMO achieves a Word Error Rate (WER) of 6.8% for short English utterances in low noise conditions, an end-to-end response latency of 2.0-4.0 s, and a lower peak power consumption of approximately 9.0 W. The system also achieves effective offline recognition for Bangla speech, supporting multilingual accessibility in low resource settings. By operating entirely offline, LUMO provides strong data privacy, reduced need for cloud connectivity, and suitability for privacy sensitive edge execution such as rural healthcare, education, and disaster response scenarios.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.30554v1">Privacy-Preserving Prompted Policy Search for Robotic Control</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E"> 
  <p><b>Published on:</b> 2026-09-24T21:03:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ali Irshayyid, Feng Lin, Chong Li, Jun Chen</p>
    <p><b>Summary:</b> Large language models (LLMs) have recently demonstrated promising capabilities as in-context policy optimizers for Reinforcement Learning (RL), enabling policy search driven by both numerical reward signals and natural language reasoning. However, deploying such methods in practice requires transmitting raw policy parameters and rewards history to cloud-based LLM APIs, exposing proprietary control strategies to third-party service providers. To address this issue, this paper introduces Privacy-Preserving Prompted Policy Search (PP-ProPS), a framework that enables LLM-guided policy optimization while keeping policy and environmental parameters confidential. PP-ProPS encodes policy parameters and reward values using secret client-side transformations before they are included in each API request, ensuring that the LLM provider observes only encoded policy parameters and scaled reward information. Furthermore, unlike Vanilla ProPS, the proposed framework does not require the true optimal episodic return to be known or disclosed to the LLM. Beyond protecting the optimization data, PP-ProPS improves the search process in two ways. First, it provides the LLM with individual reward components instead of only a single total return, offering more informative feedback about each candidate policy. Second, it uses a bounded history that prevents the prompt from growing indefinitely, improving search with high-dimensional policies and supporting the use of open-weight LLMs. The proposed PP-ProPS is evaluated on both continuous and discrete control problems spanning Multi-Joint dynamics with Contact (MuJoCo) locomotion, classic control, highway driving, and robotic arm manipulation. Compared to Vanilla ProPS, the proposed PP-ProPS outperforms ProPS in seven of the ten evaluated tasks, and surpasses conventional RL methods including PPO, SAC, and TRPO, in five of the six tasks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.29453v1">Decoupled Learning and Selection in Slate Recommendation for Privacy and Stability Under Noisy Scores</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2026-09-24T12:09:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sam Urmian, Qinyi Liu, Mohammad Khalil</p>
    <p><b>Summary:</b> We formalize slate recommendation as a randomized score learner followed by deterministic selection. First, an appropriately scoped differential-privacy guarantee passes through selection and its audit trace by post-processing. End-to-end privacy holds only when selector inputs are public or independent, previous private outputs, or separately privacy-accounted; fixing raw state or candidate information instead yields only a conditional guarantee. Second, we derive a logged margin certificate: bounded score-induced objective movement below half the smallest greedy decision margin guarantees that the ordered slate is unchanged.
  Controlled fixed-margin tests show near-linear exponent scaling, with an empirical slope of $-0.220$ (95% CI $[-0.231,-0.210]$) against the independent-noise reference $-1/4$. Real-anchor experiments on OULAD, MovieLens-25M, and Amazon Musical Instruments show that greater anchor weight reduces score-noise-induced ranking churn. OULAD and EdNet certificate checks validate the implementation of the logged inequality, while closed-loop simulations show bounded target drift and setting-dependent downstream utility. The contribution is therefore a privacy-scope contract and a certifiable score-to-slate stability mechanism, not a universal utility claim.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.31763v1">SMARtCARE: Privacy-Preserving Agentic AI Systems for Bounded-Autonomy Clinical Decision Support</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2026-09-24T02:44:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Srini Ramaswamy, Deveeshree Nayak</p>
    <p><b>Summary:</b> Long-context clinical AI systems can miss relevant patient history when prior admissions fall outside the active reasoning context. In ICU monitoring, this can cause early vital-sign drift to appear nonspecific even when it resembles a prior deterioration pattern. SMARtCARE addresses this gap through a four-state clinical decision-support architecture: Stable, Meta-cognitive, Assisted, and Regulated (Revoked). Rather than automatically retrieving prior records, SMARtCARE uses a lossy six-channel fingerprint of the patient's prior trajectory. When current drift matches that fingerprint and the prior record is absent from context, the system raises a Meta-cognitive escalation for clinician review; full retrieval occurs only through clinician action in the Assisted state. A patient-identity guard is designed to enforce correct attribution across data loading, logging, and audit layers. Evaluation combines a synthetic Monte Carlo study that validates the state-transition logic and estimator stability, not clinical performance, with real-data runs on both the MIMIC-III and MIMIC-IV Clinical Database Demos. On MIMIC-III, one prior-pattern recurrence was identified among 14 two-admission patients; on MIMIC-IV, the same pipeline produced no fingerprint matches among 9 two-admission patients, which illustrates a key limitation of a fixed canonical pattern library. Across both runs all logged decisions were fully traceable and correctly attributed. The results support SMARtCARE as a traceable, privacy-aware mechanism for surfacing middle-context risk; they are not a clinical efficacy claim.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.28685v1">"A Necessary Evil": Teenagers' Sensemaking of Privacy and Safety Settings on Social Media</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-09-23T18:26:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jingxin Dong, Lingyun Chen, Chen Ling, Colin M. Gray</p>
    <p><b>Summary:</b> Social media platforms are embedded in teenagers' daily lives, supporting friendship and identity while exposing teenagers to unwanted contact and privacy harms. Previous scholarship has documented how attention capture strategies and dark patterns shape social media use, and we extend this work to better understand platform settings that ostensibly provide privacy and safety protection. We report on think-aloud sessions with 11 teenagers aged 14 to 17 who completed six privacy and safety tasks on Instagram, TikTok, Snapchat, and YouTube. We show how participants worked out what a setting meant through their routines, boundaries, and prior experiences, how they accommodated protections softer and less predictable than expected, and how they treated the platform as the authority on what protection should look like. We argue that feature-by-feature evaluation cannot establish whether teenagers are protected, and that platforms should carry the obligation to show that a protective action took effect and is durable.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.28672v1">Available but Not Usable: Dark Patterns and Interaction Cost in Social Media Privacy and Safety Settings for Teens</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-09-23T18:13:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jingxin Dong, Lingyun Chen, Chen Ling, Colin M. Gray</p>
    <p><b>Summary:</b> Social media platforms are central to teenagers' lives, and their designs can expose users to privacy, safety, and wellbeing harms. Platforms increasingly offer protective settings, though the presence of a control reveals little about whether teenagers can find, use, and benefit from it over time. We paired an expert evaluation of six privacy and safety tasks across TikTok, Instagram, Snapchat, and YouTube with moderated think aloud sessions in which 11 teenagers aged 14 to 17 attempted the tasks. Interaction cost and dark patterns analysis allowed us to compare the complexity designed into each task with the effort participants incurred as they located, configured, and interpreted controls. Recurring dark patterns appeared across tasks, and most participant attempts exceeded the expert baseline. Protective settings therefore risk being insufficiently usable or durable in practice, and we propose a wayfinding audit that integrates expert evaluation, usability testing, interaction cost, and dark pattern analysis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.28360v1">Privacy-Preserving Semantic Segmentation from High-Resolution Depth and Ultra-Low-Resolution RGB</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E">
  <p><b>Published on:</b> 2026-09-23T16:31:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xuying Huang, Swithinraj Moses Daniel, Sicong Pan, Sebastian Houben, Maren Bennewitz</p>
    <p><b>Summary:</b> As mobile robots become increasingly integrated into everyday environments, privacy risks arising from onboard cameras have become a growing concern. Ultra-low-resolution (ULR) RGB can mitigate visual privacy exposure at the source, but ULR appearance alone substantially limits semantic and spatial understanding. We therefore introduce a privacy-preserving asymmetric sensing setting that combines high-resolution (HR) depth with ULR RGB, preserving dense geometry while restricting fine-grained visual information. To address the severe information imbalance between HR depth and ULR RGB, we propose a joint 2D framework using HR geometry to guide semantic-oriented RGB reconstruction and RGB-D segmentation. Despite reliable frame-level predictions, consistent scene-level understanding remains challenging under the asymmetric HR depth--ULR RGB setting. We therefore develop an end-to-end 2D-to-3D pipeline that consolidates 2D semantic features for 3D segmentation. Experiments on ScanNet show that our method achieves the best 2D and 3D segmentation performance among privacy-preserving approaches and delivers the strongest zero-shot transfer to SUN RGB-D and SceneNN. Privacy recoverability analysis shows that our proposed HR depth--ULR RGB input reduces the recoverability of sensitive data, and real-robot experiments demonstrate the utility of the resulting 3D semantics for object-goal navigation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.28297v1">Contraction and Statistical Inference under Privacy for Uniformly Bounded Distributions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">
  <p><b>Published on:</b> 2026-09-23T15:43:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Leonhard Grosse, Sara Saeidian, Tobias J. Oechtering, Mikael Skoglund</p>
    <p><b>Summary:</b> We investigate $c$-interior pointwise maximal leakage (PML) as a tool for contraction analyses and disclosure control. Based on the strong adversarial threat models from maximal leakage, $c$-interior PML generalizes local differential privacy (LDP) to data-generating distributions with densities uniformly bounded away from zero by $c>0$. Viewing $c$-interior PML as an algebraic constraint on a kernel yields more flexible (and often tighter) contraction analyses than standard LDP. We provide tight bounds on the Dobrushin coefficient, and bound the contraction coefficient of the Hockeystick-divergence. We further derive strong data processing inequalities on $f$-divergences under $c$-interior PML constraints when the input distributions to the divergence are restricted to be in the $c$-interior. These results extend beyond the regime of pure LDP to cover a larger class of kernels, including, e.g., arbitrary stochastic matrices. We apply the results to minimax theory and provide asymptotically optimal strategies under $c$-interior PML constraints for binary hypothesis testing and mean estimation. The results show that disclosure control with PML allows analysts to reason about systems in a more differentiated manner: For example, it allows us to quantify the privacy leakage of deterministic systems, and can give precise adversarial guarantees with respect to arbitrary distributional assumptions. Interestingly, a recurring theme in the disclosure analyses is that if the privacy problem is relatively regular (if the density bound $c$ is large), private inference can be possible without incurring any additional cost in terms of sample complexity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.28137v1">"We'll Fix It Later": Education, AI, and the Deferral of Privacy in EdTech</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-09-23T13:59:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Meghna Manoj Nair, Rachel Greenstadt</p>
    <p><b>Summary:</b> Educational technology (EdTech) platforms collect highly sensitive student data, including behavioral logs, disability records, and academic histories. However, privacy considerations are often postponed rather than treated as a foundational design requirement. We present a mixed-methods study combining 12 semi-structured interviews with EdTech professionals and a privacy policy audit of 48 platforms coded across five dimensions, with strong inter-rater reliability (mean Cohen's Kappa = 0.781). Our interviews reveal a recurring organizational pattern in which privacy is recognized as important but deferred across the product lifecycle as organizations prioritize product functionality, growth, funding, and immediate educational outcomes. Responsibility is often delegated to cloud providers, policy documents, or downstream institutions, while limited privacy-related feedback gives organizations little pressure to change these practices. The policy analysis reflects these patterns: platforms describe what data they collect relatively well but provide substantially less information about how that data is subsequently governed. Thirty-three percent make no meaningful Artificial Intelligence (AI) disclosure despite visible AI features, and 73% provide only generic accountability and breach-response language. K-12 platforms perform better on children's consent where regulation creates explicit requirements, but this advantage does not extend to AI governance or accountability. These findings suggest that meaningful improvement requires enforceable institutional and regulatory mechanisms rather than voluntary privacy commitments alone.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.27617v1">Finite-Sample Binary Hypothesis Testing via Rényi Divergences: Strong Converse and Local Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">
  <p><b>Published on:</b> 2026-09-23T09:41:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Roberto Bruno, Adrien Vandenbroucque, Amedeo Roberto Esposito</p>
    <p><b>Summary:</b> We study asymmetric simple binary hypothesis testing between $H_0:P_0^{n}$ and $H_1:P_1^{n}$, based on $n$ independent and identically distributed observations. Leveraging a variational representation of Rényi divergence of order $α$, we derive our main result: a finite-sample converse with $α>1$. The bound uses both directions of the divergence $D_α(P_1\|P_0)$ and $D_α(P_0\|P_1)$, tensorises under product measures, and contains familiar data-processing converses as boundary cases. For comparison, we apply the same variational approach to general $f$-divergences and specialise it to total variation, $E_γ$, Hellinger, and Kullback Leibler divergences, thereby recovering familiar converses within a unified framework. Together with an achievability bound involving Rényi divergence with $α\in (0,1)$, the main converse recovers the phase transition of the optimal Type II error under the exponentially decaying Type I error constraint $\varepsilon_n=e^{-nr}$. Under regularity conditions, the optimal Type II error vanishes exponentially when $r<D(P_1\|P_0)$ and converges exponentially fast to one when $r>D(P_1\|P_0)$. We also derive sample-complexity bounds and extend both the converse and achievability analyses to locally differentially private observations, quantifying the cost of privacy and recovering the non-private achievability bound as the privacy constraint vanishes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.27406v1">Only Pay What You Must Spend: On-Demand Privacy Budget Payment for Differentially Private RAG</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Digital Libraries-D91E36">
  <p><b>Published on:</b> 2026-09-23T06:20:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhonghao Sun, Zhiliang Tian, Xinyue Fang, Shuo Ma, Juhua Zhang, Yiping Song, Dongsheng Li</p>
    <p><b>Summary:</b> Deploying large language models (LLMs) on sensitive data via Retrieval-Augmented Generation (RAG) introduces severe privacy risks. Recent studies apply Differential Privacy (DP) to LLMs with RAG for formal privacy guarantees. However, existing DP-RAG frameworks rapidly exhaust the privacy budget. Although recent efforts attempt to save the budget by narrowing the retrieval scope or sparsifying private generation, these methods themselves cumulatively consume the budget, whereas they could actually rely merely on public information or at a negligible one-time privacy cost. This mismatch fails to align budget expenditure with the model's actual reliance on private data, causing substantial waste on operations that require no private access. To address this, we propose SparsePay-RAG, adopting "only pay what you must spend" as its core principle. Using public information as a zero-privacy prior, it charges the privacy budget only for the private increment. Specifically, SparsePay-RAG narrows the retrieval scope via public topic-guided clustering, adaptively controls private access frequency without privacy cost through isotonic cross-layer trajectory fitting, and compresses per-access budget via DP contrastive decoding. Under strong privacy constraints, experiments show SparsePay-RAG achieves superior privacy-utility trade-offs over baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.27100v1">Cryptographic Security Is Not Enough: Privacy Gaps in the Renegade Decentralized Dark Pool</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-22T21:54:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Prerna Arote, Adrian Saiz, Oriol Saguillo, Lucianna Kiffer</p>
    <p><b>Summary:</b> Dark pools are designed to provide pre-trade privacy, liveness, and post-trade confidentiality - concealing order flow before execution and limiting information leakage after. Decentralized dark pools, such as Renegade, aim to replicate these properties without custodial risk, using secure multi-party computation (MPC) and zero-knowledge proofs for private order matching and verifiable settlement.
  We show that Renegade's cryptographic guarantees do not deliver these dark pool properties in practice. MPC-with-abort ensures correctness but not fairness: a party may learn the match result and abort without penalty, breaking pre-trade privacy. We demonstrate that the protocol's discovery layer further leaks trading intent before MPC even begins, and that sustained probing via selective abort can probabilistically reconstruct counterparty order history, threatening post-trade confidentiality. We also show that the absence of input-consistency checks prior to MPC execution enables a griefing attack using invalid state commitments requiring no real token holdings that continuously locks honest users' wallets and wastes compute, breaking liveness under sustained conditions.
  We further analyze over 700,000 Renegade transactions on Base and probe the P2P layer, finding that the network is effectively centralized: 88% of traffic routes through a handful of relayers, with only four nodes sustaining the P2P layer. Since relayers hold their users' wallet state in plaintext, this concentration means the system operates as a centralized orderbook in practice - reproducing off-chain the information asymmetry that dark pools are designed to eliminate.
  Together, our results show that cryptographic privacy does not imply dark pool security: pre-trade privacy, liveness, and post-trade confidentiality each require additional protocol-level guarantees beyond MPC correctness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.28537v1">Privacy Leakage Through AI-mediated Analysis of Smartphone Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-09-22T20:24:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sarah Radway, Zoe Robert, Matthew Soto, Julianna Cimillo, Sebastian Diaz, Meg Marco, James Mickens</p>
    <p><b>Summary:</b> Over the past thirty years, the online advertising industry built a large-scale data collection ecosystem, with the goal of tracking a user's online activity to infer their demographics and interests. Traditionally, the ecosystem relied upon the collation and analysis of highly-structured text data like user IP addresses, GPS coordinates, e-commerce purchase histories, and visited URLs. However, recent ML models can parse not only structured text, but also multimedia files and unstructured text inputs---meaning a user's photos, videos, inboxes, and calendars are now ripe for automated analysis. The privacy risks are particularly acute in the context of smartphone apps. A user's phone already acts as a natural collation point for sensitive user information, but users may not understand that permitting an app to, for example, access a user's photo does not just give the app access to the bytes in the photo: the app also receives access to inferences about the user that are enabled by the photo.
  To explore these privacy risks, we built Priva-See, an LLM-based inference system for app-collected user data; Priva-See reflects our best understanding of how real-life adtech companies would leverage machine learning to build user profiles. Through an IRB-approved user study, 465 participants deployed Priva-See on their phones; Priva-See made privacy-invasive inferences despite having access to only a subset of a user's data. We see the experience significantly impacted participant willingness to share permissions data moving forward. Based on the observed privacy violations, we suggest changes to how smartphone OSes should gather user consent for data access, to better inform users about downstream data usage capability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.26680v1">Decoding the Legalese: A Scalable and Quantitative Framework for Analyzing Corporate Privacy Policies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-09-22T16:38:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiaming Tang, Chenlan Wang, Mingyan Liu, Armin Sarabi</p>
    <p><b>Summary:</b> Even though privacy policies are the primary mechanism organizations use to disclose how they collect, process, and share personal data, they are difficult for average users to interpret, perhaps by design, due to their verbosity and dense legal language. Importantly, there is a lack of standardized metrics that characterize key qualities of a privacy policy beyond regulatory requirements. Recent advances in large language models (LLMs) make it feasible to automatically structure and analyze these documents at scale. In this study, we develop and evaluate an end-to-end, LLM-enabled system that converts raw privacy policies into fine-grained structured representations and a set of quantitative measures. Our pipeline applies a detailed taxonomy to extract specific data elements and governing practices, capturing relational links that connect each practice to the data elements it references. We apply our framework to a diverse corpus of 10,000 website privacy policies, yielding, to the best of our knowledge, the most comprehensive dataset of its kind to date. Building on our structured representations, we introduce the first standardized and repeatable quantitative metrics for evaluating privacy policies along four dimensions: completeness, transparency, commitment to user protection, and emphasis on business-driven data practices. This allows us to compare policies within and across industry sectors, and to assess the tension between user protection and business interests.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.26623v1">A Data-Interventional Framework for Auditing Privacy and Fairness in Generative Medical Imaging</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-09-22T15:55:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mischa Dombrowski, Bernhard Kainz</p>
    <p><b>Summary:</b> Diffusion-based synthetic data generation offers a promising route for sharing medical imaging data without releasing sensitive patient records. However, generative models face a fundamental tension between privacy and fairness: they may memorize rare training samples, leading to privacy risks, or fail to reproduce underrepresented features, resulting in unfair synthetic distributions. While prior work has largely focused on either memorization or fairness in isolation, their interaction remains insufficiently understood. In this work, we introduce a data-interventional framework to systematically analyze privacy and fairness in diffusion models. We discuss synthetic anatomical fingerprints (SAFs), rare and manually injected image features, as controlled probes to study whether models generalize sensitive attributes across identities, memorize training samples, or suppress rare signals entirely. Across multiple conditioning modalities, we observe a consistent behavior: models either forget these fingerprints or memorize the entire image in which they appear, but do not generalize them to novel images. To support large-scale auditing where explicit sample extraction is infeasible, we further introduce the indicator metric t', which estimates a model's susceptibility to memorization by exploiting the internal structure of the diffusion process. By comparing conditioning signals of varying surprisal, we reveal a clear relationship between conditioning rarity and memorization behavior. Highly surprising conditioning signals act as retrieval keys that amplify memorization, whereas low-surprisal conditioning signals systematically suppress rare features, even when these appear repeatedly in the training data. Our findings provide actionable insights and concrete mitigation strategies for safe and fair synthetic medical data sharing. Code is available at https://github.com/MischaD/Privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.26508v1">Gap-Free Streaming PCA Beyond Rank-One Updates: Near-Optimal Rates and Applications to Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> 
  <p><b>Published on:</b> 2026-09-22T14:38:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anming Gu, Syamantak Kumar, Kevin Tian, Chutong Yang</p>
    <p><b>Summary:</b> Streaming principal component analysis (PCA) seeks to recover a leading spectral subspace in a single pass over a data stream. We give a new analysis of the ubiquitous Oja's algorithm [Oja82] for the most general, gap-free variant of this problem, where no eigengap assumptions are made on the underlying mean matrix, complemented by a nearly-matching lower bound. Prior works achieving near-optimal rates for streaming PCA either required gap assumptions [JJK+16, HNWW21], or were limited to rank-one updates [AZL17, Lia23]. Our proof only uses a second moment bound on the individual stochastic updates, bypassing the almost sure bounds needed by prior near-optimal analyses, and the analogous offline matrix Bernstein bound. We also extend our result to a Rayleigh quotient notion of approximate PCA, addressing an open question of [JJK+16]. As our main application, we give gap-free differentially private PCA guarantees for sub-Gaussian data, settling Conjecture 1.1 of [Bro26] up to logarithmic factors.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.26365v1">Privacy-Preserving Coordinated Operation of Power Grids and AI Data Centers: A Checkpoint-Aware Three-Phase Scheme</a></h3>
  
  <p><b>Published on:</b> 2026-09-22T13:07:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ziang Liu, Ruizhang Yang, Xin Cui, Francis Yunhe Hou</p>
    <p><b>Summary:</b> The rapid growth of large language model training and serving is driving AI data centers (AIDCs) toward gigawatt scale. Unlike conventional commercial loads, AIDCs possess significant operational flexibility through dynamic voltage and frequency scaling (DVFS) of training and inference workloads, while periodic model checkpointing can induce abrupt power drops and rebounds that erode operating reserves and increase transmission congestion risks. Coordinating AIDC operation with grid scheduling under these unique operational characteristics is challenging because grid and AIDC operators are generally unwilling to share proprietary data and decision-making authority. This paper proposes a hierarchical privacy-preserving coordinated operation scheme between the power grid and AIDCs to address this gap. The proposed scheme contains three phases. In Phase I, the grid operator computes a certified inner approximation of the AIDCs security region for subsequent coordination. In Phase II, the AIDC operator coordinates training and inference AIDCs to optimize workload allocation within the certified security region and generate power schedules and checkpoint alerts. In Phase III, the grid operator solves a checkpoint-aware two-stage robust optimal power flow (OPF) considering renewable generation and checkpoint uncertainties. By exchanging only compact interface information, the framework preserves the privacy of both grid and AIDCs, avoids frequent iterative communication, and enables secure coordination with guaranteed feasibility. Numerical studies on a modified IEEE 14-bus system and a modified NYISO system demonstrate the effectiveness, robustness, and security of the proposed framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.26295v1">On the security and privacy of LLMs in Mobility</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-09-22T12:09:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mauro Conti, Lorenzo Perinello, Umberto Salviati</p>
    <p><b>Summary:</b> The mobility sector is undergoing a paradigm shift driven by advances in Generative Artificial Intelligence. With a global market valued at approximately 2.9 trillion dollars annually, considering only cars, the integration of these technologies has the potential to impact more than 1.5 billion vehicles worldwide. As Large Language Models (LLMs) are increasingly adopted in mobility, concerns about cybersecurity, privacy, and reliability emerge. Accordingly, this paper surveys current applications and assesses these challenges. Since the European AI Act classifies transportation AI as high risk, we derive nine technical classes from its requirements to assess current research and future deployments. Our findings show that research mainly studies GPT and Llama models (over 50\% of reviewed works) and traffic applications while largely neglecting security, privacy, and reliability. This gap extends to AI Act compliance: among 35 reviewed works, only one includes a partial vulnerability assessment and one a partial risk management system. We identify a clear gap between strong optimization performance and regulatory adherence, suggesting compliance is limited less by technology than by a focus on static performance over lifecycle safety, and underscoring an urgent need for security-by-design in safety-critical intelligent transportation systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.25941v1">UE-Side Location Privacy for 5G NR Uplink Positioning: Mechanisms and Trade-offs</a></h3>
  
  <p><b>Published on:</b> 2026-09-22T09:47:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Giulia Focarelli, Alireza Pourafzal, Henk Wymeersch, Stefania Bartoletti</p>
    <p><b>Summary:</b> Future 5G-Advanced and 6G networks increasingly reuse uplink communication waveforms for positioning and sensing. This raises privacy concerns, as user equipments (UEs) may unintentionally reveal precise timing information even when positioning services are not explicitly requested. While prior works show generic orthogonal frequency division multiplexing (OFDM) pilots can be manipulated to degrade time-of-arrival (ToA) estimation without compromising data links, this paper extends these concepts to a realistic 5G new radio (NR) up-link framework including Sounding Reference Signal (SRS), Demodulation Reference Signal (DMRS), Physical Uplink Shared Channel (PUSCH), and standardized 3GPP channel models. We investigate several UE-side privacy mechanisms: optimized pilot distortion, artificial noise, artificial multipath, and delay spoofing. Through 3GPP-compliant sample-level simulations, we assess their impact via localization, communication, and consistency-based detection metrics. The resulting analysis highlights the trade-offs among privacy, communication reliability, and detectability, providing key insights into waveform-level obfuscation for future integrated sensing and communication (ISAC) systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.25798v1">Secure ISAC with Sensing Privacy under Eavesdropper Uncertainty</a></h3>
  
  <p><b>Published on:</b> 2026-09-22T07:34:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pigi P. Papanikolaou, Dimitrios Bozanis, Sotiris A. Tegos, Christos Masouros, George K. Karagiannidis</p>
    <p><b>Summary:</b> This paper investigates the joint protection of confidential data and legitimate-user directional information in integrated sensing and communication (ISAC) networks. We consider a multiuser downlink in which passive multi-antenna eavesdroppers (Eves) attempt to decode confidential signals while exploiting legitimate-user reflections for unauthorized angular sensing. To address both threats, we develop a robust covariance-design framework that jointly limits Eve decoding, maintains the transmitter's accuracy in estimating the Eves' directions and shifts the dominant passive-sensing response toward prescribed deceptive directions. A Bayesian angular prior and the corresponding Bayesian Cramer-Rao bound (BCRB) characterize the transmitter's eavesdropper-angle estimation accuracy. Angular uncertainty is represented through geometry-consistent samples, such that each candidate Eve direction jointly determines the corresponding transmitter-Eve channel, user-Eve bearing, and deceptive direction. The resulting design balances worst-user secrecy, sensing accuracy, sensing privacy, and deception power. Robust Eve-decoding constraints are handled through finite sufficient conditions with intersample margins, while continuous ghost dominance is enforced using interval sum-of-squares (SOS) constraints. The resulting nonconvex problem is addressed through successive convex approximation (SCA) and semidefinite relaxation. Numerical results show that the proposed design effectively preserves secrecy and sensing privacy under Eve-angle uncertainty, provides controlled angular deception in single- and multiple-Eve scenarios, and outperforms benchmarks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.25484v1">Learning Defensive Policies against Diverse Inference Attacks for Smart Meter Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-21T23:27:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruichang Zhang, Mustafa A. Mustafa</p>
    <p><b>Summary:</b> Smart meter (SM) data provides fine-grained visibility into household energy consumption, but also exposes users to privacy risks. Inference attacks, known as non-intrusive load monitoring (NILM), can perform appliance-level inference from aggregate signals and recover sensitive behavioral patterns. In practice, attacker models are unknown and heterogeneous, making robust defense challenging. We formulate SM privacy protection as a black-box inference defense problem, aiming to reduce the recoverability of appliance-level information while generalizing across diverse and unseen attackers. We propose a proxy-guided hierarchical reinforcement learning framework that learns battery-based load-shaping policies to inject realistic but misleading appliance-level signatures into the aggregate signal, thereby disrupting the structured patterns exploited by NILM. A self-supervised aggregate-structure privacy probe provides a reconstruction-error-based surrogate reward for disrupting recoverable load structure, while a signature library makes the perturbations appliance-relevant and physically realizable through battery control. We provide theoretical rationale showing that proxy-guided optimization improves inference robustness under attacker diversity. Experiments on real-world datasets UK-DALE and REDD demonstrate strong cross-model and cross-appliance generalization. Across six unseen NILM attackers, covering four appliances on UK-DALE and five on REDD, our proposed defense increases average appliance-level RMSE by 107% and 166%, respectively, while reducing F1 score by 79% and 80%.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.25352v2">SSP-Bench: A Hybrid Data Generation Framework for Safety, Security, and Privacy Evaluation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2026-09-21T19:44:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fatih Deniz, Yazan Boshmaf, Issa Khalil</p>
    <p><b>Summary:</b> Evaluation of large language models (LLMs) for safety, security, and privacy (SSP) relies heavily on static benchmarks, which suffer from score saturation, data contamination, and aggregation artifacts, and fail to capture sensitivity to linguistic variation. As a result, models that perform well on fixed test sets often fail under semantically equivalent rephrasings. We introduce SSP-Bench, a dynamic benchmarking framework that generates evaluation instances on demand while preserving domain consistency. The framework ensures label validity through externally grounded sources, enforces scope via service-specific validation, and calibrates difficulty using a multi-model steering panel. Benchmark construction is formulated as a multi-objective optimization problem over difficulty, separability, novelty, and diversity. Across 24 models and four SSP services, SSP-Bench reveals systematic failures of static evaluation, including near-zero correlation in safety rankings due to construct mixing, strong safety--over-refusal coupling, and hidden within-family regressions. These results show that static benchmarks can misrepresent model behavior, motivating dynamic, deployment-relevant evaluation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.24656v1">5G-Shark: A Network Security Auditor for 5G Subscriber Privacy and Unauthenticated Signalling Resilience</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-09-21T14:24:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Oscar Lasierra, Gines Garcia-Aviles, Antonio Skarmeta, Xavier Costa-Pérez</p>
    <p><b>Summary:</b> The fifth generation of mobile networks was standardised with an explicit mandate to close long-standing privacy and security gaps, mandating the concealment of the subscriber's permanent identity, resistance to generational downgrade, and protection against location tracking. Assessing whether these guarantees hold in operational networks, however, requires separating two sources of residual exposure that prior studies do not distinguish and do not evaluate in the wild: protocol-design limitations, which remain exploitable even against a fully specification-compliant deployment, and implementation gaps, which arise from incomplete or non-compliant implementations. We present 5G-Shark, a security assessment tool and methodology that turns a legitimate mobility procedure against the subscriber. Rather than relying on active jamming or malformed-packet injection, 5G-Shark manipulates the standardised cell-reselection criterion to pull a target User Equipment onto a self-created rogue cell, establishing an attack vantage with minimal service disruption. Then, the proposed methodology effectively performs the required interactions to expose the security risks of the system under test, classifying them into the aforementioned categories. Built solely from open-source stacks and Software Defined Radio hardware and evaluated against commercial 5G Standalone deployments, 5G-Shark requests subscriber identifiers, forces Radio Access Technology downgrade via crafted Registration Reject codes, and induces denial-of-service states. For each vector, we attribute the root cause to protocol design or deployment non-compliance. We further provide empirical evidence that in several commercial deployments, temporary identifiers are re-allocated in near-sequential steps that keep successive values linkable, a weakness that enables persistent user tracking despite correct subscriber ID concealment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.24537v1">MIRAGE: Full-Body Bystander Privacy for Smart Glasses with Consent-Based Restoration</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-09-21T13:09:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Muhammad Umair, Muhammad Danial Maqbool, Fatima Arshad Cheema, Kapal Dev, Muhammad Hamad Alizai, Muhammad Ali Siddiqi, Naveed Anwar Bhatti</p>
    <p><b>Summary:</b> Video recording on smart glasses exposes more than faces. Continuous capture reveals full-body biometric signatures, including gait, posture, and silhouette, that enable person re-identification (ReID) even after conventional face sanitization.
  We present MIRAGE, a three-tier architecture for privacy-preserving smart glasses that enforces full-body privacy, supports synthetic full-body replacement, and retains encrypted recovery material for consent-based restoration. We implement MIRAGE on a Raspberry Pi~5 (a CPU-only proxy for smart-glasses compute), companion phones, and a cloud generative backend. Compared to prior systems, MIRAGE achieves 0.948 AP and 0.976 AR while accurately detecting the complete visible body. Its bounding box masking reduces learned silhouette-based ReID to essentially random guessing, with 10.86% Rank-1 accuracy compared with an 11.12% measured chance level. Even against an adaptive adversary retrained on MIRAGE's sanitized pose signals, Rank-1 gait identification drops from 90.25% to 26.20%, removing 72.5% of the adversary's identification advantage.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.24173v1">Zero-Knowledge Remote Adversarial Attack against Wi-Fi-based Human Activity Recognition for Privacy Protection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762"> 
  <p><b>Published on:</b> 2026-09-21T06:43:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Byungjun Kim, Amogh Panchagatti, Peter Gerstoft, Xinyu Zhang, Minsung Kim</p>
    <p><b>Summary:</b> The growing capability of Wi-Fi devices to identify human activities using channel state information (CSI) raises privacy concerns. To counter this threat, we propose GRAW, an adversary system, acting as a privacy defender, that degrades the human activity recognition (HAR) system at the user device by perturbing the router's signals that the device uses to estimate CSI. GRAW employs generative adversarial imitation learning (GAIL) to construct perturbation signals, and thereby eliminates the need for any information on the target HAR systems and their inputs (i.e., zero-knowledge operation). We evaluate GRAW against seven representative HAR models, using datasets collected in five environments, including our own dataset. We observe that GRAW is the only remote attack scheme that degrades every tested HAR model to a random-selection level. At the same perturbation level, GRAW achieves an attack success ratio up to 76.7% higher than comparison methods, while maintaining over 99% packet success rate on regular Wi-Fi communication. We demonstrate the feasibility of GRAW through real-time, over-the-air experiments with software-defined radios.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.23827v1">Pattern-level Differential Privacy for High-utility Complex Event Processing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2026-09-20T19:23:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> He Gu, Thomas Plagemann, Vera Goebel, Maik Benndorf, Boris Koldehofe</p>
    <p><b>Summary:</b> Current privacy-preserving mechanisms (PPMs) in Complex Event Processing (CEP) systems are unnecessarily restrictive, reducing the utility of data received by data consumers. This article presents a novel approach to preserve privacy in CEP systems, improving the utility of detected event patterns by dynamically adapting the noise added to an unprotected data stream. We introduce a new guarantee named pattern-level differential privacy (DP), which enables us to apply and compare the strength of PPMs at the pattern level. We propose new pattern-level PPMs yielding pattern-level DP and analyze different trust settings of these PPMs and their requirements for context knowledge in the CEP system, e.g., the deployed queries. Our evaluation is based on three datasets (two real-world, one synthetic) and shows that the proposed PPMs increase data utility while preserving the same privacy level as the state-of-the-art PPMs. We use simulations to study the performance of our proposed PPMs in various practical scenarios. Furthermore, we demonstrate that computational complexity is not an obstacle to deployment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.23521v1">Feature Suppression and Differential Privacy for Residential Traffic Classification: A Two-Home Federated Study</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-09-20T10:17:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Márton Pál Lipcsey-Magyar, Adrian Pekar</p>
    <p><b>Summary:</b> Residential traffic classification supports service management, but learning across homes must account for heterogeneous traffic and privacy constraints. Privacy-aware training may impose uneven costs across traffic categories. We study this tradeoff in simulated two-client federated learning using 1.62 million preprocessed gateway-collected flows across six categories. We compare a full-feature baseline, feature suppression (FS), and differentially private stochastic gradient descent (DP-SGD) under one fixed record-level privacy setting. FS-mild excludes four timing features from 16 model inputs; it provides no formal privacy guarantee. With size-proportional aggregation, FS-mild achieves higher combined macro-F1 and worst-group F1 (the minimum per-class F1 across homes) than DP-SGD in all five seeds at both model capacities under stratified and temporal splits. The tested DP-SGD configuration incurs pronounced minority-category losses, especially in the smaller home, but FS-mild does not uniformly improve on the full-feature baseline. On stratified-split models, loss-based and shadow-model membership probes show near-chance aggregate discrimination without a consistent ranking across probes; this does not establish equivalent privacy. These findings support FS as an input-minimization baseline, not a substitute for formal privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.23403v1">Alignment and Divergence between Humans and AI in Interpersonal Privacy Decisions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-09-20T06:30:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hanxiang Zeng, Shuning Zhang, Xinyuan Zhou, Tianqi Song, Yuhan Yuan, Yuting Yang, Shuai Ma, Xin Yi</p>
    <p><b>Summary:</b> AI assistants increasingly mediate interpersonal communication on behalf of their primary user, but they risk violating the privacy expectations of third-party information owners. Resolving these tensions requires understanding how humans anticipate interpersonal privacy boundaries. Therefore, we conducted a dyadic study (N=76) and a matched evaluation of AI models across 18 information types and 3 recipient relationships. We found that data owners' privacy judgments are highly contextual and relationship dependent. While familiar data co-owners show meaningful alignment with owners' expectations, they significantly overestimate the need for permission. Interestingly, greater familiarity within the owner-co-owner dyad was associated with both higher disclosure acceptability and lower co-owner misalignment, whereas our exploratory four-item empathy measure was not. In contrast, AI models significantly underperform human co-owners in anticipating the data acceptability, even when provided with within-dyad examples. These findings underscore a core HCI design challenge to develop privacy-aware AI that respects multi-stakeholder information boundaries.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.25103v1">Physical-Layer Sensing Privacy via Constellation Shaping for OFDM-ISAC Systems: Theory, Design, and Experiments</a></h3>
  
  <p><b>Published on:</b> 2026-09-20T02:29:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kawon Han, Kaitao Meng, Christos Masouros</p>
    <p><b>Summary:</b> The integration of sensing into communication networks introduces a new privacy risk, as a passive eavesdropper (Eve) may exploit ISAC data signals as signals of opportunity to perform unauthorized sensing of targets. In this paper, we develop a sensing-privacy-enhancing geometric constellation shaping (GCS) framework for OFDM-ISAC systems. The key observation is that constellation-dependent ranging performance is receiver-specific. For matched filtering at Eve, the ranging MSE is governed by the constellation kurtosis $\kurt$, whereas reciprocal filtering at the legitimate receiver (Alice) is governed by the inverse second-order moment $\ism$. Based on closed-form MSE expressions, we define sensing privacy as the ranging MSE gap between Eve and Alice and characterize its dependence on these two moments. The analysis shows that positive skewness of the symbol-power distribution is necessary for a positive intrinsic moment gap, namely $\kurt-\ism$. We further derive an exact skewness-based decomposition of the intrinsic moment gap and a canonical two-ring characterization, providing analytical guidelines for privacy-enhancing constellation geometries. We then formulate Eve-aware and Eve-agnostic GCS designs that balance sensing privacy and communication reliability through the minimum Euclidean distance (MED), with the Eve-agnostic design depending only on the intrinsic moment gap. Numerical results demonstrate scalable privacy--communication trade-offs, while over-the-air experiments show that the proposed constellation shaping substantially increases the ranging error gap between Eve and Alice with only a small communication throughput loss.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.23193v1">LLMs as Linguistic Chameleons: Decoupling Semantics and Structure for Privacy-Preserving Communication</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-09-19T19:41:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuzhu Mao, Liang Zhao</p>
    <p><b>Summary:</b> As Large Language Model (LLM) APIs become increasingly integrated into privacy-sensitive workflows, ensuring inference-time privacy without compromising task utility remains a major challenge. Existing approaches preserve most of the original semantic content to maintain downstream performance, but this also leaves exploitable cues for reconstructing the original text. This work investigates semantic decoupling, which replaces original semantics with alternative content while preserving the structure needed for LLM reasoning. Based on this idea, we propose CROSS-MAP, a bidirectional framework that maps private inputs into a different semantic domain before inference and recovers the corresponding outputs afterward. Local models are trained with multi-objective optimization to maximize semantic divergence in the mapping stage while minimizing semantic inconsistency in the recovery stage. Experiments show that CROSS-MAP reduces reconstruction success across multiple attack settings while outperforming existing baselines in utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.22900v1">SMS-delivered network-initiated SUPL on Pixel 8: a privacy assessment</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-09-19T09:16:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Douglas Leith</p>
    <p><b>Summary:</b> A SUPL\_INIT message is a network-initiated trigger that can be sent to a handset using an SMS to unilaterally start a location session: on receipt, the handset is instructed to determine its own position and report it, together with an identifier such as its IMSI, to a server specified in the message, without any action by the phone's user. The concern motivating this investigation is whether such a message could be used to silently exfiltrate a handset's location and subscriber identity to a server under an attacker's control. We investigated this on a Google Pixel 8 handset, which uses a Samsung Exynos modem and a Broadcom GPS/GNSS subsystem. We find no privacy issue: the handset never sends location data to an attacker-chosen server as a result of an unsolicited SUPL\_INIT delivered by SMS.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.22720v1">When Disability Disclosure Travels: Memory, Privacy, and Contextual Integrity in Conversational AI</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-09-19T03:11:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Atieh Taheri, Mahya Tazike, Patrick Carrington, Jeffrey P. Bigham</p>
    <p><b>Summary:</b> Conversational AI assistants remember what people tell them, and for disabled people, that often includes disability. We interviewed 12 adults with disabilities in the United States who use LLM-based assistants such as ChatGPT, Claude, and Gemini about when, how, and why they disclose disability to these systems and how this compares with disclosing to people. Using contextual integrity as an analytic lens, we found that participants disclosed by need rather than by name, translating disability into task-scoped instructions; that the same disclosure was judged against two recipients, a non-judging interlocutor and a data-holding company, producing opposite norms; and that memory features relieved the burden of repeated disclosure while letting disability information drift into contexts where it did not belong. Participants did extensive boundary work to restore context and wanted control over scope, provenance, retention, and access rather than per-utterance toggles. We discuss implications for the design of conversational AI assistants.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.25082v1">Federating Quantum and Classical Computing: A Privacy-Preserving Hybrid Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-09-18T20:53:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Carlos Cano, Daniel M. Jimenez-Gutierrez, Diego Sal, Georgios Kellaris, Joaquin del Rio, Oleksii Sliusarenko, Xabi Uribe-Etxebarria</p>
    <p><b>Summary:</b> Quantum machine learning (QML) is increasingly recognized as one of the most promising near-term applications of quantum computing, viewed as a next-frontier candidate beyond purely classical approaches. Hybrid quantum-classical models operationalize this potential by embedding a parameterized quantum circuit within a model where all other components remain classical-a design already applied to chemistry simulation, financial modeling, and image classification. However, their deployment in privacy-sensitive, multi-party settings is constrained by the need to avoid centralizing raw data and by the requirement that modern quantum circuits remain parameter-efficient to stay trainable at scale.
  In this paper, we address these constraints by evaluating federated learning (FL) as a means of combining a hybrid quantum-classical active party with a classical passive party, using Sherpa.ai's Blind Vertical FL (SBVFL) protocol to avoid centralizing raw data, while drastically reducing communication. We construct the split multiplicative periodic parity (SMPP) benchmark, following common QML design practice. On this task, our simulations show that SBVFL raises accuracy from 0.7227 to 0.8757 compared to local training, closely approaching non-private centralized accuracy, and that the hybrid quantum-classical model achieves this with substantially fewer trainable parameters than the classical neural networks and random forest alternatives. These results show that FL enables high-performing, privacy-preserving quantum-classical collaboration without centralizing raw data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.21686v1">CIPL: A Channel-Aware Framework for Recoverable Privacy Leakage in LLM Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-09-18T12:23:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tao Huang, Guosen Wu, Guolong Zheng, Jiayang Meng, Chen Hou, Xu Yang, Xuechao Yang, Feng Xia</p>
    <p><b>Summary:</b> Privacy leakage in LLM agents is commonly evaluated within individual components such as memory, retrieval, or tool-use pipelines, which makes it difficult to distinguish internal exposure from information that an external observer can actually recover. We present CIPL (Channel Inversion for Privacy Leakage), a channel-aware evaluation framework for black-box privacy leakage in LLM agents. CIPL represents a target through sensitive source, selection, assembly, execution, observation, and extraction stages and evaluates the transition from selected sensitive units to attacker-recoverable output under a shared protocol. Experiments across memory-based, retrieval-mediated, and tool-mediated targets, together with a BrowserUse live-agent case study, show that storage labels alone do not determine recoverability. Memory targets form a near-saturated reference case, retrieval-mediated leakage is frequently partial, and tool-mediated and live-agent leakage varies strongly with observation surface, prompt-to-channel alignment, retrieval depth, and provider behavior. A stratified semantic audit further identifies attacker-useful disclosures that canonical exact matching misses. CIPL therefore provides a common framework for comparing how internal sensitive dependence is realized as externally recoverable leakage across heterogeneous agent pipelines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.21363v2">Hiding in Plain Sight: A Diffusion-based Mitigation of Geolocation Privacy Leakage in Vision-Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-09-18T06:24:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yining Wang, Xi Li, Mi Zhang, Xiaohan Zhang, Xiaoyu You, Zhenxing Qian, Mi Wen</p>
    <p><b>Summary:</b> Multimodal large reasoning models (MLRMs) have demonstrated remarkable capabilities in complex visual understanding. However, this very power introduces a critical yet underexplored privacy threat: adversaries can exploit MLRMs to precisely infer users' geographic locations from casually shared photographs, by performing structured reasoning over subtle visual cues such as architectural styles, vegetation, and lighting conditions. In this work, we present a systematic study of MLRM-driven geolocation privacy leakage. We first reveal that refusal-based safeguards are critically insufficient, as carefully crafted jailbreak prompts can raise model response rates to 100%. We further identify that existing defenses, which inject imperceptible perturbations into shared images, suffer from structural limitations intrinsic to their pixel-space optimization, resulting in degraded black-box transferability and pronounced visual artifacts. Motivated by these findings, we propose a diffusion-based framework that provides targeted, proactive defense against geolocation privacy leakage. By injecting perturbations into the latent space of a diffusion model during reverse sampling, our method operates directly on high-level semantic representations, thereby resolving the effectiveness-utility bottlenecks by construction. We further ground our optimization with GeoCLIP, a model explicitly aligned with GPS coordinates, as a surrogate to pinpoint and disrupt the geographic signals that MLRMs exploit for location inference. This targeted semantic disruption yields significantly stronger black-box transferability while preserving perceptual image quality, offering a seamless integration on social media platforms. Code is available at https://github.com/RachelWolowitz/Hiding_in_plain_sight.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.21340v1">Conformal Privacy Auditing: Calibrated Re-identification Attacks with Statistical Guarantees</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-09-18T05:49:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuo Huang, Gholamreza Haffari, Xingliang Yuan, Ting Yu, Lizhen Qu</p>
    <p><b>Summary:</b> Empirical identity leakage from released text is increasingly driven by attackers that combine large language models (LLMs) with auxiliary knowledge to link documents to individuals. Existing audits typically report success rates for specific attack pipelines but lack finite-sample statistical guarantees, while training-time protections such as differential privacy are difficult to translate into release-time decisions for individual natural-language documents. We introduce Conformal Privacy Auditing(CPA), a distribution-free calibration framework that provides a statistical certificate of re-identification risk for each released document against LLM-empowered adversaries. CPA outputs a conformal ambiguity set of candidate identities that is guaranteed to contain the true identity with user-chosen confidence under exchangeability, together with an interpretable leakage proxy derived from set size. CPA supports both logit-access and sampling-only attackers, enabling audits of open-source models and proprietary API models in a unified framework. Across multiple release benchmarks and attacker configurations, CPA achieves calibrated coverage and reveals sharp shifts in certified identifiability as auxiliary knowledge, LLM augmentation, and release mechanisms vary, providing a statistically grounded basis for reporting and comparing release-time linkage risk across attacker configurations, datasets, and release mechanisms alike.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2609.21338v1">Asymptotic Anytime-Valid Quantile Inference under Local Differential Privacy</a></h3>
  
  <p><b>Published on:</b> 2026-09-18T05:49:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Leheng Cai, Qirui Hu, Shuyuan Wu</p>
    <p><b>Summary:</b> Sequential quantile inference is difficult under local differential privacy because every record is randomized before reaching the analyst and the limiting quantile variance depends on an unknown density. We develop an online procedure that combines randomized response with dynamically chained parallel stochastic gradient descent (P-SGD). The resulting Polyak--Ruppert estimator admits a strong Gaussian approximation. A cross-chain quadratic statistic, computed entirely from private iterates, consistently estimates the limiting variance without a separate online density estimator. These results yield asymptotic confidence sequences and, under polynomial chain growth, asymptotic time-uniform coverage. Arm-wise constructions support locally private quantile best-arm identification, time-uniform simple-regret bounds, and sequential A/B tests of quantile treatment effects. Simulations and salary-data analyses illustrate the finite-sample behavior and practical use of the proposed methods.</p>
  </details>
</div>



<h2>2026-10</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.10002v1">The Price of Privacy: Randomness Complexity of Graph-Based Multi-Secret Sharing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-07T12:59:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Piotr Marszalik</p>
    <p><b>Summary:</b> We study the randomness required to share possibly correlated secret bits among parties connected by a graph. A dealer places shares on the edges so that each party can recover its own secret from its incident shares and learn nothing about the others beyond what its own secret reveals. Anilkumar et al. completely determined the minimum randomness required for three binary secrets. We extend this study to four secrets and obtain results for arbitrary numbers of secrets on general graphs. For four parties on a complete graph, we determine the minimum number of random states for every set of permitted secret combinations: the possible values are one, two, three and four. We also characterize when one random bit suffices on an arbitrary graph.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.09288v1">FaceKit: a Toolkit for Interpretable Facial Phenotyping, Synthetic Image Generation and Privacy Analysis in Rare Diseases</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-10-07T01:43:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hongzhuo Chen, Zhanliang Wang, Florent Pollet, Mian Umair Ahsan, Joshua Bie, Tzung-Chien Hsieh, Peter Krawitz, Cong Liu, Wendy K Chung, Chunhua Weng, Gamze Gürsoy, Kai Wang</p>
    <p><b>Summary:</b> Many rare genetic diseases are associated with recognizable craniofacial features. However, traditional approaches for describing facial morphology rely largely on qualitative clinical observation and free-text descriptions, which are often subjective, non-standardized, and difficult to reproduce across observers and institutions. Although the Human Phenotype Ontology (HPO) provides controlled terms for describing facial features, these terms are typically categorical rather than quantitative and may vary depending on examiner experience and interpretation. Here, we present FaceKit, a computational framework for quantitative facial phenotyping from frontal facial photographs. FaceKit extracts standardized measurements of facial landmarks and derived 120 morphological features, then reports feature-level z-scores representing deviation from population reference distributions. The reference distributions are built from the FairFace dataset spanning diverse ancestral groups. We evaluated FaceKit on a curated subset of the GestaltMatcher Database covering 50 rare-disease cohorts. In addition to quantitative facial analysis, FaceKit includes synthetic facial image generation to support rare disease model development and data augmentation. We also performed privacy evaluation to assess whether synthetic images reveal identifiable information from real patient photographs and could compromise patient privacy. Across disease case studies, FaceKit-derived quantitative measurements captured known facial features associated with rare genetic disorders and provided objective support for clinical phenotyping. Together, these results establish FaceKit as a useful tool for quantitative phenotyping, and has the potential to improve rare disease diagnosis, support genotype-phenotype studies, and enable more reproducible clinical characterization across diverse patient populations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.08414v1">Image Bitstream Fine-grained Understanding for Privacy-Friendly AIoT</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-10-06T14:18:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhen Yu, Wenyang Liu, Kejun Wu, Chengwang Xiao, Renjie Qiao, Chengtao Cai</p>
    <p><b>Summary:</b> Image Bitstream Fine-grained Understanding (IBFU) aims to directly perform fine-grained classification and semantic description generation from encoded image byte sequences. In contrast to conventional pixel-domain visual understanding, IBFU conducts semantic analysis without fully decoding images into the pixel domain. Since pixel-level visual content is not explicitly reconstructed during inference, this paradigm reduces visual exposure within the processing pipeline and suits privacy-friendly Artificial Intelligence of Things (AIoT) applications. In this paper, we propose Bitstream Fine-grained Generator (BFG), a novel foundation model tailored for IBFU. BFG consists of two main components: a Bitstream Semantic Encoder (BSeE) and a Fine-grained Semantic Generator (FSeG). BSeE directly models semantic representations from encoded image bitstreams without explicit pixel reconstruction, while FSeG transforms the extracted bitstream semantics into detailed natural-language descriptions through autoregressive generation. To train BFG and comprehensively evaluate IBFU in practical AIoT scenarios, where image bitstreams may suffer corruption during transmission and storage, we construct a large-scale Corrupted-bitstream Fine-grained Understanding dataset (CFU-D), containing both intact bitstreams and corrupted variants across multiple corruption types and severity levels. Experiments show that BFG maintains stable fine-grained caption generation under bitstream corruption. For example, the performance only has slight change from 0.6339 to 0.6077 in terms of average CIDEr score on Stanford Dogs Caption dataset, while vision-language models, such as Qwen-VL-Chat, BLIP-2, GLM, Gemini, and GPT suffer severe performance decrease. This paper provides a practical paradigm for privacy-friendly fine-grained understanding in AIoT.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.08255v1">HE-OFT: Privacy-Preserving One-Shot Federated Fine-Tuning under Homomorphic Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-06T12:35:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Halil İbrahim Kanpak, Sinem Sav, Alptekin Küpçü</p>
    <p><b>Summary:</b> Many organizations adapt large pretrained models to their own tasks by fine-tuning on private data. Several of these parties often hold data for the same task and wish to fine-tune a model together without pooling that data. Federated learning (FL) enables joint fine-tuning, but reconstruction attacks on shared intermediate values (the model or its gradients) remain a privacy risk. A one-shot protocol that exchanges one encrypted contribution exposes no intermediate value. Such a protocol still gives the trained model to every participant, which is not permitted where the model is a regulated or proprietary asset. We present HE-OFT, the first cryptographically secure one-shot federated fine-tuning protocol in which no party receives the trained model. Each client fine-tunes a low-rank adapter and a classifier head on a frozen public backbone and keeps the adapter. The client uploads one encrypted head displacement, which the server combines under multiparty CKKS and never decrypts. A quorum of clients returns only the predicted label to the querier. On four text classification tasks and one vision task, HE-OFT reaches 61 to 79 per cent accuracy, against 20 to 48 per cent for a client training alone. HE-OFT keeps 85 to 96 per cent of the accuracy of a disclosed model. A test-time query takes 443.1 to 1713.1 s on one core, or 56.1 to 255.1 s with level restoration on a GPU. Restoring levels at the server cuts the traffic per query from up to 1.6 GiB to 13.5 MiB.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.08174v1">FBAN: A Fully Homomorphic Encryption Compatible Bottleneck Attention Network for Privacy-Preserving Behavioral Authentication</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-06T11:28:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jichao Xiong, Atsuko Miyaji, Jiageng Chen</p>
    <p><b>Summary:</b> Continuous authentication (CA) strengthens session security by repeatedly verifying the user during device interaction, yet it inherently relies on highly sensitive behavioral traces (e.g., fine-grained touch dynamics) that are often outsourced to cloud/edge services for scalable inference. This raises a fundamental privacy-in-use challenge: protecting behavioral features during computation, not only in transit or at rest. Fully homomorphic encryption (FHE) offers a principled solution, but deploying modern CA models under FHE remains difficult due to non-linearities and attention-style operations that incur high ciphertext cost.
  We propose FBAN, a TFHE-compatible Bottleneck Attention Network and an end-to-end encrypted CA framework. FBAN is designed for integer-only execution via a two-stage pipeline (floating-point pretraining followed by quantization-aware training) and is compiled into TFHE circuits for homomorphic inference. We further specify a client-server protocol with session-bound blinding and decrypt-and-return verification, enabling the server to authenticate users without observing raw behavioral features. We provide a cryptographic security analysis against an honest-but-curious server under TFHE IND-CPA security, and formalize resistance to replay and impersonation without the TFHE secret key. Experiments on two public touchscreen datasets demonstrate that FBAN achieves strong authentication utility under encrypted inference while maintaining a lightweight model footprint, with TFHE parameters instantiated at $\geq 128$-bit security.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.07976v1">Quantifying the Privacy Posture of Operator-Side 5G/O-RAN Profiles</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-10-06T08:42:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nikolaos Kekatos, Apostolos Valiakos, Alexios Lekidis, Elpiniki Papageorgiou</p>
    <p><b>Summary:</b> Operator-side network profiles derived from 5G/ORAN traffic carry personal data such as ephemeral subscriber identifiers, slice-level KPIs, and control-plane signalling, and must be anonymised before release to a federated-learning aggregator, threat-intelligence exchange, or ML training pipeline. We study how much re-identification risk remains after standard operator-side anonymisation. We quantify privacy posture with k-anonymity, l-diversity and t-closeness, aggregate them into a composite Privacy-Posture Index (PPI), and measure residual re-identification across eight transformation configurations on internal PCAP captures and the public Idaho Labs 5GAD corpus, under a full-QI syntactic bound and two simulated adversaries. The evaluation is modest in scale, and we read its trends as indicative rather than definitive. Three findings emerge. Pseudonymisation alone leaves re-identification unchanged; material privacy gains arise when quasi-identifiers are coarsened through generalisation, optionally combined with suppression. A downstream classification task then shows that suppression-heavy releases retain majority-class utility but sacrifice much of their minority-class recall, a cost the aggregate metrics hide. Finally, the standard kmin-based PPI correlates only modestly with the disclosure bound and not at all with the partial-knowledge attack, whereas a mean-class-size variant PPI correlates strongly with all three disclosure/attack measures; we therefore read PPI as a regulator-facing summary, not a security bound. The profiles are produced by passive operator-side monitoring with rule-based DPI; our contribution is the privacy-quantification layer that computes these metrics, applies the transformation policy, and exposes both through an inspectable dashboard.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.07677v1">Adaptive Model Inversion Attacks Generalize a Privacy-Robustness Tradeoff</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-06T03:11:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shailen Smith, Rasmus Torp, Adam Breuer</p>
    <p><b>Summary:</b> In this paper, we show that standard evaluations of high-resolution Model Inversion Attacks (MIAs) significantly underestimate training-data privacy leakage. State-of-the-art privacy defenses, standard training techniques such as MixUp and Adversarial Training, and undefended models all leak training images at rates 1.16 to 6.59 times higher on FaceScrub under simple adaptive changes to the attack, with the largest increases among defenses reporting the strongest privacy. We further show that measured leakage depends on the feature basis of the external classifier used to evaluate reconstructions: for the same reconstructed images, an adversarially trained Inception evaluator identifies the targeted identity at different rates than the standard Inception evaluator. Our results suggest that standard MIA evaluation can mistake optimization and measurement failures for privacy.
  These underestimated leakage rates also concealed a broader relationship between privacy and adversarial robustness. Once we adapt the attack and vary the evaluator, reconstruction leakage closely tracks adversarial robustness across recent defenses and standard training regimes, suggesting that robustness provides an attack-agnostic proxy for reconstruction vulnerability that applies far more broadly than previously theorized. This raises an open question: can a practical defense reduce training-data reconstruction without paying a corresponding cost in adversarial robustness?</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.07399v1">Fed-BRDECS: Privacy-Preserving and Heterogeneity-Aware Federated Deep Embedded Clustering</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-05T21:11:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haemin Park, Diego Klabjan, Martin W. Braun, Xiuqi Li, Balakrishnan Ananthanarayanan</p>
    <p><b>Summary:</b> Federated deep clustering seeks to learn clustering-friendly representations from decentralized unlabeled data while preserving client privacy. However, Deep Embedded Clustering (DEC)-style objectives depend on global soft-assignment statistics that require clients to reveal their sensitive information. We propose Fed-BRDECS, a privacy-preserving and heterogeneity-aware federated deep embedded clustering framework. Fed-BRDECS replaces the globally normalized clustering objective with a locally computable sample-stability loss, avoiding the transmission of local soft-assignment distributions. To tackle non-IID client distributions, we introduce prediction-balanced sampling, which oversamples locally rare predicted clusters without requiring ground-truth labels, and centroid-level restarting, which periodically refreshes biased or inactive centroids. Experiments on image and text clustering benchmarks show that Fed-BRDECS consistently outperforms representative federated clustering and deep clustering baselines under both IID and non-IID partitions. We further demonstrate its applicability to federated time-series anomaly detection, where it improves reconstruction-based detectors without adding inference-time cost.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.07258v1">Lineage-Aware Memory Governance: A Derivation-Gated Framework for Privacy-Preserving Column-Level Access Control in Enterprise AI Agents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-05T18:56:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Venkata M Sangaraju, Sudhir Vissa</p>
    <p><b>Summary:</b> Enterprise AI agents that share a memory store face two unaddressed risks: sensitive data can leak through legitimately computed results the requester could not derive, and departments can silently compute a same-named key performance indicator (KPI) through conflicting logic. Existing agent-memory systems (e.g., MemGPT, Zep, A-MEM) gate retrieval by content, ownership, and role, not derivation, missing a cached insight that embeds a forbidden column. We introduce the Analytical Memory Unit (AMU), a memory schema that attaches a full derivation (lineage) graph to every cached result, gated by a retrieval policy that serves a hit only when the requester is authorised for every column touched. Provided lineage recording is complete, we prove by construction that the policy blocks retrieval of results derived from a sensitive column outside the requester's permissions, at O(n) worst case -- a conditional design guarantee, not an empirical claim, that excludes derived features encoding sensitive information without naming their source. Eliminating measured leakage required 75-90% recorded lineage completeness, so we treat 90% as a conservative deployment target. Across six experiments, lineage-gated retrieval removes the 18.8-25.5% cross-department leakage naive content-gated memory suffers, keeping 81.5-82.6% of memory reuse at 13.8 microsecond worst-case overhead. A real-agent proof-of-concept with LLM-generated SQL is consistent with the guarantee: zero leaks over 9 round-trips, two conflicts caught automatically -- though a feasibility demonstration, not evidence of production viability. This offers a practical governance layer for shared agent memory, complementing source-layer access control and supporting EU AI Act compliance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.07238v1">The Cost of Differential Privacy in Linear-Quadratic Dynamic Games</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E">
  <p><b>Published on:</b> 2026-10-05T18:43:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chih-Yuan Chiu, Matthew Hale</p>
    <p><b>Summary:</b> Multi-agent coordination often requires strategic agents to share sensitive information about their states or objectives, creating a tension between performance and privacy. Our paper studies this tradeoff in stochastic linear-quadratic (LQ) dynamic games with heterogeneous agent objectives. In our framework, agents share noise-perturbed state and reference information with a cloud computer that computes feedback Nash equilibrium strategies, with the injected noise calibrated to provide differential privacy. We derive an analytical expression for each agent's infinite-horizon steady-state cost of privacy relative to the non-private game. Then, we prove that when agents' objectives are sufficiently aligned, the injection of privacy noise necessarily incurs a positive performance cost. In contrast, we characterize a class of games with sufficiently misaligned objectives across agents for which an agent's cost of privacy can be strictly negative. Thus, counterintuitively, noise can simultaneously protect privacy and improve the equilibrium performance of an agent when the objectives of interacting agents are sufficiently misaligned. Finally, we present numerical experiments which corroborate our theoretical contributions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.07212v1">Reward-Driven Learning under Prompt-Level Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-05T18:26:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiachen Zhao, Antonia Januszewicz, Taeho Jung</p>
    <p><b>Summary:</b> Reinforcement learning with verifiable rewards (RLVR) trains a language model on problems that may themselves be confidential, and the trained model can reveal which problems it saw. We study RLVR under prompt-level differential privacy: the released weights must be (ε,δ)-differentially private with respect to the presence of any one training problem. Taking the group of responses to one prompt as the privacy record, our method aggregates their gradients, clips the prompt's contribution once, adds Gaussian noise, and composes the privacy loss across updates, so the budget depends on neither the number of responses per prompt nor the clipping norm; to our knowledge this is the first differential privacy guarantee for RLVR training. We train Qwen2.5-1.5B-Instruct with LoRA at a per-run budget of ε=8 and compare, on the same prompts and at the same budget, a control that removes only the reward signal and two private supervised fine-tuning recipes. The reward signal improves accuracy over the control by 2.65 points on MATH and 3.24 on GSM8K, in every seed; the improvement survives a format-robust scorer, at 1.3 points on MATH, and is not explained by response length. At the same budget the private model outperforms both supervised recipes on MATH and GSM8K by 2.3 to 3.8 points, retains 85--90% of the gain of non-private GRPO on these tasks, and on MATH the noise of an eightfold tighter budget costs at most 1.2 points. The reward effect also carries to CommonsenseQA, an exploratory non-mathematical task. Verifier feedback thus remains a usable learning signal under prompt-level privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.06454v1">AgentPrivArena: Evaluating and Auditing Real-world AI Agent Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-10-05T14:55:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shouju Wang, Haopeng Zhang</p>
    <p><b>Summary:</b> The rapid advancement of LLM agents has enabled systems to autonomously perform complex tasks through external tools, but their growing access to personal data introduces significant privacy risks. Existing benchmarks primarily evaluate LLM agent privacy through simulated trajectories and outcome-based metrics, limiting their ability to capture privacy risks arising during multi-step agent execution. In this work, we introduce AgentPrivArena, a framework for evaluating privacy risks in realistic LLM agent workflows. AgentPrivArena integrates authentic MCP tools and self-hosted services within a reproducible execution environment. We further propose trajectory-level privacy metrics that quantify unnecessary information access beyond final response leakage. Building on this framework, we introduce AgentPrivAudit, a runtime auditing approach for monitoring privacy violations during agent execution. Extensive experiments on state-of-the-art LLM agents reveal substantial privacy risks overlooked by existing evaluation paradigms, highlighting the importance of trajectory-level auditing for trustworthy agent deployment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.05867v1">Learning Sparse Support under Differential Privacy: Adaptive Algorithms and Minimax Limits</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">
  <p><b>Published on:</b> 2026-10-05T06:32:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jia Gu, T. Tony Cai</p>
    <p><b>Summary:</b> We study exact support recovery under $(ε,δ)$-differential privacy in sparse high-dimensional linear regression. We introduce Saturated Propose-test-release, a general mechanism that privately releases the output of a discrete selector with probability one once its stability certificate reaches a finite threshold. Exploiting the coordinatewise geometry of the LASSO, we construct a computable support-stability score. The resulting computationally efficient Saturated LASSO satisfies worst-case $(ε,δ)$-differential privacy and achieves exact support recovery with high probability under explicit regularity and beta-min conditions. Maximizing sparsity-indexed certificates yields an adaptive procedure requiring no sparsity knowledge and having exactly the same finite-sample exact-recovery risk as the oracle fixed-sparsity procedure under common public tuning parameters. We also establish a minimax lower bound explicitly tracking $δ$: under its recovery conditions, Saturated LASSO is minimax optimal up to logarithmic factors in $n$ and $1/δ$ uniformly over $0 < δ\leq ε/16$; in the broad moderate-$δ$ regime, it further matches the lower-bound $δ$-dependence. A complementary information-theoretic construction with known sparsity attains the lower-bound rates up to constant factors under independent Gaussian design, at exponential computational cost. Simulations and a semi-synthetic study using public American Community Survey covariates illustrate the numerical performance of the proposed procedures.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.05561v1">Beyond Monolithic Perturbation: Heterogeneous Mechanism Design for Multi-Attribute Metric Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-04T21:48:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruiyao Liu, Michael Oluwole, Chenxi Qiu</p>
    <p><b>Summary:</b> Multi-attribute user records are inherently heterogeneous, often combining continuous, categorical, and binary attributes, and they frequently exhibit strong cross-attribute dependencies. Designing high-utility metric differential privacy (mDP) mechanisms for such records is challenging. Simple predefined mechanisms, such as distance-based noise, may be poorly aligned with task-specific utility loss, whereas fully optimization-based mechanisms can be computationally prohibitive for multi-attribute records.
  We propose Dependency-aware Heterogeneous Data Perturbation (DepHDP)}, a framework for multi-attribute mDP that combines dependency-aware attribute grouping with heterogeneous perturbation design. Rather than applying a one-size-fits-all mechanism, DepHDP selects an appropriate perturbation strategy for each attribute or attribute group, choosing between efficient predefined mechanisms, such as Laplace or Exponential mechanisms, and optimization-based designs. This selection is guided by both domain size and a predefined-noise adequacy criterion, which quantifies whether task-induced utility loss can be well explained by perturbation magnitude. To support scalable end-to-end optimization, DepHDP estimates group-level utility loss through sampling and lightweight surrogate modeling, and jointly optimizes privacy-budget allocation and group-wise mechanism design under a global $\ell_p$-metric mDP constraint. Across three case studies, DepHDP improves privacy--utility trade-offs over uniform baselines at lower computational cost than full-record OPT on evaluated domains.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.05475v1">Poor Privacy Practices Of The Apple App Store: Cookies, Advertising and Tracking Of Users</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-10-04T19:34:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Douglas Leith</p>
    <p><b>Summary:</b> We analyse the data that the Apple App Store sends to and receives from Apple servers. We find that multiple cookies are sent by Apple servers and stored on the handset. Adverts with tracking identifiers are also stored on the handset, and we observe that adverts are selected by Apple servers using GDPR special category personal data such as sexuality, religious beliefs and health. User interactions with the Apple App Store (apps and adverts viewed, buttons clicked, searches made etc) are transmitted to Apple servers alongside identifiers linking this data to the individual user and device. We show that much of this data storage and transmission is not essential for the service requested by the user, namely to view, search and install apps. No consent is sought for any of this data storage and processing, and there is no opt out.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.05453v1">The Poisoned Conversation: Privacy-Leaking Watermarks in Unified Multimodal Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-10-04T18:53:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tobias Braun, Jonas Henry Grebe, Emil Sivic, Patrick Mohr Gordillo, Hossein Shakibania, Marcus Rohrbach, Anna Rohrbach</p>
    <p><b>Summary:</b> Multimodal models are increasingly shifting toward unified architectures that understand and generate text, images, and other modalities within a shared conversational context. This design enables fluid interaction across modalities, but it also changes the privacy threat model: Information revealed in one part of a conversation may remain accessible when the model later generates content in another modality. This risk is particularly concerning in settings where users rely on locally deployed models for privacy, assuming that sensitive interactions remain confined to their device. We introduce Privacy-Leaking Watermarks (PLWs): invisible, trigger-dependent watermarks that a malicious model provider can condition on prior chat history. With this adversarial intervention, the usual separation breaks: a sensitive keyword or semantic cue mentioned earlier in the conversation can cause a later, unrelated image to carry a hidden yet detectable watermark. PLWs pose a novel threat to users of unified multimodal models: A poisoned model can retain utility while covertly turning image generation into a channel for privacy leakage, even when deployed locally. Across 13 sensitive-attribute triggers and two model families, PLWs reach up to 100.0% TPR at 1% FPR. For example, across all tested conversational separations, OmniGen2 detects every prior disclosure of depression while falsely flagging only 1% of images generated without such a disclosure.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.06998v1">Order-Optimal Coded Caching With File and Demand Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-10-04T08:18:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Han Fang, Nan Liu, Wei Kang</p>
    <p><b>Summary:</b> We study coded caching with joint file and demand privacy: each user recovers its requested file while learning nothing about the remaining files and the other users' requests jointly. Let $N$ and $K$ be the numbers of files and users, and let $M$ and $R$ denote the cache memory and delivery rate, both normalized by the file size. For every $N,K\ge2$ and every feasible cache size, we give a scheme whose worst-case delivery rate is at most $9/2$ times the optimum. To reduce the memory used for file shares, the scheme secret-shares $N-1$ differences relative to a reference file. Cached masks supply the correction needed to recover the requested file from its difference. For each integer $t\in\{0,\ldots,K-1\}$, the scheme achieves $M=1+(N-1)t/(K-t)$ and $R=K/(t+1)$. To lower-bound the delivery rate, we compare the joint cache entropy of user groups under alternative demand vectors, using one fixed user's privacy constraint. Two choices of groups determine the optimal delivery rate up to constants at the scale $\min\{K,1+(N-1)/(M-1)\}$ for $M>1$. At $M=1$, the exact optimum is $K$. A complementary bound on joint broadcast entropy gives the minimum memory for unit delivery rate, $1+(N-1)(K-1)$, and the exact tradeoff on an interval ending at that memory. All schemes and bounds apply to repeated as well as distinct requests.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.04985v1">Hidden Risks of Jev: An Empirical Study of Security, Privacy, and Dual Use</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-10-04T06:09:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shang Wang, Tianqing Zhu, Huajie Chen, Jiayang Li, Meng Yang, Bo Liu</p>
    <p><b>Summary:</b> Jev turns natural-language questions into typed answers and probabilities with low latency and cost, enabling applications to route requests and select tools. While this interface allows Jev to integrate naturally into application workflows as a decision layer, the security and privacy implications of this emerging use remain largely unexplored. To address this gap, we conduct the first systematic study of these implications using the official Jev API and NanoJev, a local model with controllable training data and updates, focusing on three research questions: (1) What security threats arise when Jev is deployed as an application decision layer? (2) What private information can Jev reveal despite returning constrained typed outputs? (3) How can Jev's general-purpose decision capability be used for beneficial purposes or misused?
  Jev's decisions depend on application state and may be influenced by user-provided inputs. We therefore adapt prompt injection and adversarial suffixes to manipulate its decisions. Open-source Jev distribution and updates introduce supply-chain risks, which we examine by implanting backdoors in NanoJev through training data poisoning. Since Jev's outputs reflect both application state and information learned during training, we further adapt membership, private attribute, and internal knowledge inference attacks to recover sensitive information despite its constrained output format. Finally, Jev can serve as a general-purpose decision oracle for defensive and malicious workflows. We examine this dual use through four detection tasks covering prompt injection, jailbreak inputs, harmful content, and AI-generated text, alongside misuse scenarios involving jailbreak and model extraction. Our empirical evaluation shows that Jev remains vulnerable to the examined security and privacy threats, while its decision capability can support beneficial and malicious uses.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.04600v1">Asymptotically Optimal Best Arm Identification with Fixed-Budget under Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-10-03T15:38:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Keqin Chen, Jie Bian, Yulian Wu, Vincent Y. F. Tan</p>
    <p><b>Summary:</b> Best arm identification under differential privacy is a pure-exploration problem in which both statistical efficiency and privacy protection must be achieved simultaneously. We study fixed-budget best arm identification for bandits under pure $ε$-differential privacy, where the learner must recommend an arm after a prescribed sampling budget while protecting the full transcript. We prove that the optimal exponential decay rate of the error probability is upper bounded by an instance-dependent privacy-aware transportation exponent that differs from the analogous quantity used to characterize the stopping time in fixed-confidence analysis by Jourdan and Azize [2025]. Guided by this exponent, we propose AO-Pri-BAI, an adaptive algorithm that maintains private running estimates through Laplace-tree mechanisms and learns a sampling design through a min--max interaction between hard alternatives and arm allocations. We prove that AO-Pri-BAI satisfies pure $ε$-differential privacy. We also establish that the exponent of the failure probability of AO-Pri-BAI matches the privacy-aware benchmark. Numerical studies show that even in the non-asymptotic setting, AO-Pri-BAI outperforms benchmark algorithms on various instances, complementing the theoretical analyses.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.04060v1">Auditing the Privacy of Synthetic Gene Expression Data: A Unified Weighted-Distance Framework for No-Box Membership Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-02T21:14:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Owen Tucker, Lily Wang, Harutoshi Okumura, Ruixuan Liu, Li Xiong</p>
    <p><b>Summary:</b> Synthetic gene expression data is increasingly proposed as a privacy-preserving substitute for controlled-access genomic repositories, but its safety depends on empirical auditing. Membership inference attacks (MIAs) provide that audit by testing whether a patient's gene expression profile was used to train a generative model. We report a red-team study on synthetic gene expression data derived from bulk RNA-seq profiles in The Cancer Genome Atlas, released by the ELSA Health 2026 Challenge. We unify five no-box attacks under a single weighted-distance framework in which each variant differs only in how it weights genes: uniformly (baseline), by variance, by synthetic-versus-reference KL divergence, by spectral residualization removing dominant principal components, and by curated pathway membership. Against a conditional variational autoencoder, spectral residualization raises AUC from 0.8251 to 0.8951 and TPR at 1% FPR from 0.3842 to 0.5970 on pan-cancer TCGA. Biological pathway priors did not transfer across targets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.04042v1">Assessing Acceptance and Privacy Preferences of Third-party Financial Data Sharing in Bipolar Disorder</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-10-02T20:50:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jeff Brozena, Johnna Blair, Dahlia Mukherjee, Erika F. H. Saunders, Thomas Richardson, Saeed Abdullah</p>
    <p><b>Summary:</b> Bipolar disorder is strongly associated with financial instability. We examine how different interventions motivate individuals with bipolar disorder to share financial data with others. This approach can inform the development of tools for digital monitoring and intervention designed to promote financial stability in this population. 500 individuals with BD completed a pre-registered factorial vignette survey to examine level of comfort with hypothetical scenarios involving third-party financial interventions during symptomatic and euthymic periods. Scenario components were systematically varied between third-party actors, mood states, and intervention types. Participants rated sharing comfort on a 0-10 point scale. Multilevel models tested differences alongside clinical and financial histories, relational trust, and personality. Participants were most comfortable involving care partners in financial planning. They were more comfortable with temporary spending restrictions during symptomatic states than euthymic periods, underscoring the importance of accurate mood detection for intervention delivery. Prior financial help-seeking behavior and higher relational trust predicted greater comfort. Bankruptcy experience --- declared by 11.4% and considered by 31.7% --- was associated with increased comfort with spending restrictions. Individuals with psychiatric advance directives (8%) were significantly more comfortable sharing spending behaviors than those without. Comfort with financial interventions was higher among those with prior financial challenges or help-seeking histories. Participants distinguished between symptomatic and euthymic periods, favoring targeted, time-limited restrictions over general monitoring. These findings extend prior work on financial data sharing for illness self-management.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.02943v1">Kinematics-Induced Multimodal 3D Human Pose Estimation with Subject-Level Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2026-10-02T07:37:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kaushik Bhargav Sivangi, Fani Deligianni</p>
    <p><b>Summary:</b> Multimodal 3D Human Pose Estimation (3D HPE) combines complementary information from RGB, LiDAR, and mmWave radar, but models trained on correlated observations from the same individuals, raise privacy risks overlooked by record level analysis. We present a unified framework for multimodal 3D HPE that couples kinematics-induced sensor fusion with subject level privacy auditing and private training. First, our multimodal model aligns modality specific joint representation, injects skeletal structure and adaptively aggregates complementary sensor evidence for accurate pose prediction. Second, we formulate a black-box subject membership inference attack for 3D HPE, complemented by an empirical pointwise maximal leakage analysis, which characterizes how individual attack score outcomes change inference about the membership outcome. Third, we instantiate user-level differential privacy via Action Temporal Stratification, a population weighted within-subject sampling strategy that enforces action and temporal coverage. We evaluate our framework on the MM-Fi dataset across three diverse experimental protocols. Source-code will be released upon acceptance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.02716v1">Differential Privacy of Gradient Descent on Perturbed Objectives</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2026-10-02T02:52:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Austin Watkins, Raman Arora</p>
    <p><b>Summary:</b> Objective perturbation adds a random linear term to a regularized empirical risk and releases the exact perturbed minimizer. We study the finite computation obtained by releasing the $N$-th iterate of deterministic gradient descent on $w\mapsto F(w;S)+\langle z,w\rangle$, where $z\sim\mathcal N(0,σ^2I_d)$ is drawn once before optimization. For strongly convex and smooth objectives with Lipschitz Hessian, we prove an explicit condition under which the map $z\mapsto w_N$ is a $C^1$-diffeomorphism on the bounded domains used in the privacy argument, with a quantitative lower bound on the smallest singular value of its Jacobian. This permits a direct change-of-variables analysis of the finite iterate. For generalized linear models, the resulting privacy-profile bound has no explicit ambient-dimension factor once the iteration condition holds, and its finite-iteration correction decreases geometrically. By letting the free truncation parameter grow slowly with $N$, we recover the corresponding exact-minimizer certificate in the limit. We also bound the expected excess empirical risk by $dσ^2/(2μ)$ plus a geometrically decreasing optimization term, and transfer the result to population risk without an additional multiplicative condition-number factor in the leading statistical terms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.02504v1">HXAI: Hierarchical Privacy-Preserving Explainable AI in Distributed Energy Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-10-01T21:26:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Poushali Sengupta, Sabita Maharjan, Frank Eliassen, Yan Zhang</p>
    <p><b>Summary:</b> Balancing electricity demand and supply is increasingly difficult due to the inherent intermittency of renewable power generation and the stochastic power consumption. Grid operators require fine-grained, decision-relevant insights into household energy consumption to manage peak loads and design responsive tariffs, but increased transparency at this level raises significant privacy concerns. Traditional methods for explainable AI (XAI) can reveal sensitive information, while standard privacy techniques often reduce the usefulness of explanations. To address this issue, we introduce HXAI, a hierarchical framework that preserves privacy while enabling reasonable explainable analysis for grid-level demand management. HXAI consists of two main components: (1) a local model that generates fine-grained explanations within a secure, private environment, and (2) a zonal model that aggregates these explanations to support grid-level analysis while enforcing privacy through flexible privacy-budget management. We explicitly limit cumulative privacy exposure under repeated operator queries and show that the proposed framework preserves decision-relevant information without compromising household privacy. Experiments on both simulated and real-world energy datasets demonstrate that HXAI provides useful insights for zonal load management while ensuring that appliance-level consumption remains local and is never transmitted to grid operators. Our results show that preserving the semantic structure of explanations, rather than minimizing numerical error, is the key to XAI under differential privacy. This framework provides a way to achieve both privacy and explainability in energy management.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.02414v1">Unifying Privacy Accounting: Information Equivalence and Information Loss</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">
  <p><b>Published on:</b> 2026-10-01T19:37:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Buxin Su, Qiaoshi Yang, Yiding Su, Chendi Wang</p>
    <p><b>Summary:</b> Differential privacy (DP) admits several notions, but the choice among them may affect both privacy analysis and utility. In this paper, we consider four mainstream curve-based privacy notions within a unified information-theoretic framework. For a fixed ordered pair of output distributions, we establish information equivalence among the two directional privacy profiles of $(\varepsilon,δ)$-DP, the pair of hypothesis-testing trade-off functions, and the extended privacy-loss distribution. The exact Rényi differential privacy (RDP) curve joins this equivalence class whenever it is finite at some order greater than one. Under this mild condition, choosing among these notions changes only their semantic interpretation and computational requirements. In contrast, taking the maximum of the directional privacy profiles or compressing the RDP curve into a single zero-concentrated differential privacy (zCDP) parameter can lose information. We quantify the information loss between the exact RDP curve and its zCDP bound for standard noise mechanisms. This gap is zero for Gaussian noise but generally positive for Gaussian-mixture, Laplace, discrete Gaussian, and Poisson-subsampled Gaussian mechanisms. Moreover, this gap grows linearly with the number of independently composed mechanisms. Our information-theoretic perspective has practical consequences. At the same certified privacy level, retaining the full RDP curve rather than using zCDP reduces the required noise variance by up to $45\%$ for Gaussian-mixture noise in workloads comparable in size to the American Community Survey. For DP-SGD on Fashion-MNIST under Poisson subsampling, an RDP-based privacy accountant improves test accuracy by up to $8.73$ percentage points compared to a zCDP-based accountant when both are calibrated to the same $(\varepsilon,δ)$ guarantee.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.02374v1">"I'm trying not to get hacked:" How Adults with Intellectual and Developmental Disabilities Navigate Security and Privacy Notifications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-10-01T18:53:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hailey L. Johnson, Julia Nonnenkamp, Bilge Mutlu, Rahul Chatterjee</p>
    <p><b>Summary:</b> Security and privacy notifications, such as login alerts, spam email warnings, and cookie consent requests, play a critical role in shaping users' responses to digital risks. Yet most notifications overlook cognitive accessibility, limiting their effectiveness for people with intellectual and developmental disabilities (IDD). We investigate how adults with IDD perceive and respond to common security and privacy notifications across mobile and web applications. Through a formative user study with seven adults with IDD, we identify three factors shaping understanding and decision-making: (1) interpretation is influenced by task and interface context; (2) unfamiliar terms, both technical and non-technical, are grounded in everyday concepts; and (3) uncertainty about outcomes leads to hesitation, avoidance, diagnostic exploration, or support-seeking. These findings lead to three design implications: (1) address context-dependent language misunderstandings beyond jargon simplification; (2) make action-outcome connections transparent; and (3) enable interdependent decision-making. Together, these insights aim to inform the design of more cognitively accessible security and privacy notifications that better support safe and supported user action.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.02113v1">Quantum Advantage for Two-Party Differential Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36">
  <p><b>Published on:</b> 2026-10-01T17:32:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Daniel Alabi, Emil T. Khabiboulline</p>
    <p><b>Summary:</b> We introduce information-theoretically private quantum protocols for two-party Hamming distance when both parties must output the same estimate. Classically, for input length $n$, information-theoretic protocols require $Ω(\sqrt{n})$ error under pure differential privacy and $Ω(\sqrt{n}/\log n)$ error under strong approximate differential privacy, whereas computational security permits $O(1)$ error. In Klauck's honest, nonpreemptive, message-preserving model, we give an $O(n)$-communication quantum protocol with pure $\varepsilon$ quantum differential privacy (QDP) and expected error at most $\frac{2}{\sinh \varepsilon}+γ$, for every $γ>0$. For approximate $(\varepsilon, δ)$ QDP, an exact hockey-stick divergence calculation yields strictly smaller error, while preserving the $O(1)$-versus-$Ω(\sqrt{n}/\log n)$ separation for $δ=o(1/n)$. Thus, quantum communication achieves $O(1)$ information-theoretic error, matching the accuracy available classically only under computational assumptions.
  The main construction uses a guarded coherent round trip and an equal-Gram rigidity principle that prevents an honest player from retaining input-dependent complementary information. We separate this model from weaker prescribed-channel privacy, which already admits an exact classical realization, and from fully retention-robust security, against which measurement-and-abort attacks remain possible. Therefore, we identify preservation of non-orthogonal quantum messages as a resource for privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.01650v1">Combining Homomorphic Encryption and Differential Privacy in Federated Learning for Model Inspection and Availability</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-01T13:13:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ceren Yıldırım, Kamer Kaya, Sinan Yıldırım, Erkay Savaş</p>
    <p><b>Summary:</b> The increasing prevalence of decentralized data has led to a growing interest in federated learning, which enables collaborative model training without clients sharing their sensitive local data. However, FL alone does not sufficiently protect sensitive training data and is generally coupled with privacy-preserving techniques, such as differential privacy and homomorphic encryption. Although powerful, these techniques address separate concerns via different mechanisms, so relying on just one might prove insufficient or impractical for addressing challenges associated with federated learning. In this work, we propose a privacy-preserving federated learning framework that combines homomorphic encryption-based training with differential privacy-based model inspection and release. We adopt a Markov chain Monte Carlo-based Bayesian privacy estimation method to estimate the privacy of our proposed framework. Our results show that this method improves both model utility and estimated privacy over the baseline method that relies solely on differential privacy for training. In our experiments with the FEMNIST dataset, by the end of training, our method reaches a test loss of $1.09$, compared to $2.37$ for the differential privacy-only approach, while providing stronger estimated privacy protection, with the estimated posterior mean of the privacy parameter $ε$ of $4.32$, compared to $7.26$ for the differential privacy-only approach. We also show that intermittent model monitoring can preserve the encrypted training trajectory while, under our evaluated experimental setting, providing estimated privacy comparable to or stronger than the differential privacy-only approach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.01365v1">Sleeping Secrets: How Fine-Tuning Reawakens Privacy Risks in Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-01T09:36:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jianhong Li, Jiahao Chen, Yuwen Pu, Chunyi Zhou, Oubo Ma, Zhou Feng, Hangtao Zhang, Jichao Bi, Chunqiang Hu</p>
    <p><b>Summary:</b> Beyond adapting Large Language Models (LLMs) to specialized applications, fine-tuning has recently been shown to recover private information that is no longer accessible through direct queries. Previous fine-tuning recovery attacks, however, require genuine private supervision drawn from the same distribution, i.e., the previous training dataset. We argue that such recovery remains possible without such impractical knowledge. We show that LLM-generated candidates can provide sufficient supervision to recover previously learned private associations. Based on this, we propose ReGap, a data-free attack that recovers private associations using task structure, filters them by answer-token likelihood, and updates the target model via low-rank adaptation. Specifically, ReGap requires neither target answers nor auxiliary genuine private supervision. Across six GPT-2, OPT, and Qwen3 models, ReGap improves target-association recovery by 6-21 percentage points over the post-training target model. Recovery remains substantial even when the adaptation identities are disjoint from all memorized and evaluation identities, with no exact target answers appearing in the generated or selected supervision. Moreover, the same trained adapters increase recovery from 42\% to 63\% on a previously exposed checkpoint, but produce no gain on a matched checkpoint that never encountered the targets. This contrast shows that adaptation alone is insufficient to explain the observed recovery and that prior target exposure strongly affects post-adaptation recoverability. Our findings highlight that routine model customization can reawaken latent privacy risks, warranting urgent attention from the academic and industrial communities.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2610.01009v1">Helol Tunnel: Covert Channel Exploitation of TLS Extensibility & Privacy Features</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-10-01T03:55:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Reza Soosahabi, Rakesh Seal</p>
    <p><b>Summary:</b> Covert channels exploiting network protocols for data exfiltration and command-and-control (C2) are integral parts of modern cyberattacks. In search of a significant covert channel within the fabric of the Internet, we targeted the combinatorial properties of the Client Hello (CHLO) packets in the ubiquitous Transport Layer Security (TLS) protocol. The proposed Helol tunnel is a novel covert approach to embedding information in TLS Client Hello packets, which involves the strategic rearrangement of their cryptographic information elements. To sustain TLS protocol extensibility, the recent anti-ossification TLS compliance measures encourage the interactive middleboxes and next-generation firewalls (NGFWs) to preserve the parameter configuration in the Client Hello packets. Furthermore, to improve user privacy, popular Internet applications are varying their TLS CHLO parameter configurations to resist TLS fingerprinting by third-party network entities. We demonstrate the strength of the Helol tunnel to exploit these recent developments to evade NGFWs with interactive proxy and comprehensive threat protection. We also numerically show the efficacy of Helol tunneling over state-of-the-art covert channels that exploit TLS through the use of real traffic captures and public TLS fingerprinting data.</p>
  </details>
</div>

