
<h2>2026-02</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.17454v1">Privacy in Theory, Bugs in Practice: Grey-Box Auditing of Differential Privacy Libraries</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-02-19T15:18:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tudor Cebere, David Erb, Damien Desfontaines, Aurélien Bellet, Jack Fitzsimons</p>
    <p><b>Summary:</b> Differential privacy (DP) implementations are notoriously prone to errors, with subtle bugs frequently invalidating theoretical guarantees. Existing verification methods are often impractical: formal tools are too restrictive, while black-box statistical auditing is intractable for complex pipelines and fails to pinpoint the source of the bug. This paper introduces Re:cord-play, a gray-box auditing paradigm that inspects the internal state of DP algorithms. By running an instrumented algorithm on neighboring datasets with identical randomness, Re:cord-play directly checks for data-dependent control flow and provides concrete falsification of sensitivity violations by comparing declared sensitivity against the empirically measured distance between internal inputs. We generalize this to Re:cord-play-sample, a full statistical audit that isolates and tests each component, including untrusted ones. We show that our novel testing approach is both effective and necessary by auditing 12 open-source libraries, including SmartNoise SDK, Opacus, and Diffprivlib, and uncovering 13 privacy violations that impact their theoretical guarantees. We release our framework as an open-source Python package, thereby making it easy for DP developers to integrate effective, computationally inexpensive, and seamless privacy testing as part of their software development lifecycle.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.17418v1">A Privacy by Design Framework for Large Language Model-Based Applications for Children</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-02-19T14:50:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Diana Addae, Diana Rogachova, Nafiseh Kahani, Masoud Barati, Michael Christensen, Chen Zhou</p>
    <p><b>Summary:</b> Children are increasingly using technologies powered by Artificial Intelligence (AI). However, there are growing concerns about privacy risks, particularly for children. Although existing privacy regulations require companies and organizations to implement protections, doing so can be challenging in practice. To address this challenge, this article proposes a framework based on Privacy-by-Design (PbD), which guides designers and developers to take on a proactive and risk-averse approach to technology design. Our framework includes principles from several privacy regulations, such as the General Data Protection Regulation (GDPR) from the European Union, the Personal Information Protection and Electronic Documents Act (PIPEDA) from Canada, and the Children's Online Privacy Protection Act (COPPA) from the United States. We map these principles to various stages of applications that use Large Language Models (LLMs), including data collection, model training, operational monitoring, and ongoing validation. For each stage, we discuss the operational controls found in the recent academic literature to help AI service providers and developers reduce privacy risks while meeting legal standards. In addition, the framework includes design guidelines for children, drawing from the United Nations Convention on the Rights of the Child (UNCRC), the UK's Age-Appropriate Design Code (AADC), and recent academic research. To demonstrate how this framework can be applied in practice, we present a case study of an LLM-based educational tutor for children under 13. Through our analysis and the case study, we show that by using data protection strategies such as technical and organizational controls and making age-appropriate design decisions throughout the LLM life cycle, we can support the development of AI applications for children that provide privacy protections and comply with legal requirements.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.17284v1">Efficient privacy loss accounting for subsampling and random allocation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-02-19T11:44:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vitaly Feldman, Moshe Shenfeld</p>
    <p><b>Summary:</b> We consider the privacy amplification properties of a sampling scheme in which a user's data is used in $k$ steps chosen randomly and uniformly from a sequence (or set) of $t$ steps. This sampling scheme has been recently applied in the context of differentially private optimization (Chua et al., 2024a; Choquette-Choo et al., 2025) and communication-efficient high-dimensional private aggregation (Asi et al., 2025), where it was shown to have utility advantages over the standard Poisson sampling. Theoretical analyses of this sampling scheme (Feldman & Shenfeld, 2025; Dong et al., 2025) lead to bounds that are close to those of Poisson sampling, yet still have two significant shortcomings. First, in many practical settings, the resulting privacy parameters are not tight due to the approximation steps in the analysis. Second, the computed parameters are either the hockey stick or Renyi divergence, both of which introduce overheads when used in privacy loss accounting.
  In this work, we demonstrate that the privacy loss distribution (PLD) of random allocation applied to any differentially private algorithm can be computed efficiently. When applied to the Gaussian mechanism, our results demonstrate that the privacy-utility trade-off for random allocation is at least as good as that of Poisson subsampling. In particular, random allocation is better suited for training via DP-SGD. To support these computations, our work develops new tools for general privacy loss accounting based on a notion of PLD realization. This notion allows us to extend accurate privacy loss accounting to subsampling which previously required manual noise-mechanism-specific analysis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.17223v1">Privacy-Preserving Mechanisms Enable Cheap Verifiable Inference of LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-02-19T10:15:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arka Pal, Louai Zahran, William Gvozdjak, Akilesh Potti, Micah Goldblum</p>
    <p><b>Summary:</b> As large language models (LLMs) continue to grow in size, fewer users are able to host and run models locally. This has led to increased use of third-party hosting services. However, in this setting, there is a lack of guarantees on the computation performed by the inference provider. For example, a dishonest provider may replace an expensive large model with a cheaper-to-run weaker model and return the results from the weaker model to the user. Existing tools to verify inference typically rely on methods from cryptography such as zero-knowledge proofs (ZKPs), but these add significant computational overhead, and remain infeasible for use for large models. In this work, we develop a new insight -- that given a method for performing private LLM inference, one can obtain forms of verified inference at marginal extra cost. Specifically, we propose two new protocols which leverage privacy-preserving LLM inference in order to provide guarantees over the inference that was carried out. Our approaches are cheap, requiring the addition of a few extra tokens of computation, and have little to no downstream impact. As the fastest privacy-preserving inference methods are typically faster than ZK methods, the proposed protocols also improve verification runtime. Our work provides novel insights into the connections between privacy and verifiability in LLM inference.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.16975v1">"It's like a pet...but my pet doesn't collect data about me": Multi-person Households' Privacy Design Preferences for Household Robots</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E">
  <p><b>Published on:</b> 2026-02-19T00:30:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jennica Li, Shirley Zhang, Dakota Sullivan, Bengisu Cagiltay, Heather Kirkorian, Bilge Mutlu, Kassem Fawaz</p>
    <p><b>Summary:</b> Household robots boasting mobility, more sophisticated sensors, and powerful processing models have become increasingly prevalent in the commercial market. However, these features may expose users to unwanted privacy risks, including unsolicited data collection and unauthorized data sharing. While security and privacy researchers thus far have explored people's privacy concerns around household robots, literature investigating people's preferred privacy designs and mitigation strategies is still limited. Additionally, the existing literature has not yet accounted for multi-user perspectives on privacy design and household robots. We aimed to fill this gap by conducting in-person participatory design sessions with 15 households to explore how they would design a privacy-aware household robot based on their concerns and expectations. We found that participants did not trust that robots, or their respective manufacturers, would respect the data privacy of household members or operate in a multi-user ecosystem without jeopardizing users' personal data. Based on these concerns, they generated designs that gave them authority over their data, contained accessible controls and notification systems, and could be customized and tailored to suit the needs and preferences of each user over time. We synthesize our findings into actionable design recommendations for robot manufacturers and developers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.16480v1">SRFed: Mitigating Poisoning Attacks in Privacy-Preserving Federated Learning with Heterogeneous Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-02-18T14:14:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yiwen Lu</p>
    <p><b>Summary:</b> Federated Learning (FL) enables collaborative model training without exposing clients' private data, and has been widely adopted in privacy-sensitive scenarios. However, FL faces two critical security threats: curious servers that may launch inference attacks to reconstruct clients' private data, and compromised clients that can launch poisoning attacks to disrupt model aggregation. Existing solutions mitigate these attacks by combining mainstream privacy-preserving techniques with defensive aggregation strategies. However, they either incur high computation and communication overhead or perform poorly under non-independent and identically distributed (Non-IID) data settings. To tackle these challenges, we propose SRFed, an efficient Byzantine-robust and privacy-preserving FL framework for Non-IID scenarios. First, we design a decentralized efficient functional encryption (DEFE) scheme to support efficient model encryption and non-interactive decryption. DEFE also eliminates third-party reliance and defends against server-side inference attacks. Second, we develop a privacy-preserving defensive model aggregation mechanism based on DEFE. This mechanism filters poisonous models under Non-IID data by layer-wise projection and clustering-based analysis. Theoretical analysis and extensive experiments show that SRFed outperforms state-of-the-art baselines in privacy protection, Byzantine robustness, and efficiency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.16760v1">Privacy-Aware Split Inference with Speculative Decoding for Large Language Models over Wide-Area Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-02-18T14:13:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Michael Cunningham</p>
    <p><b>Summary:</b> We present a practical system for privacy-aware large language model (LLM) inference that splits a transformer between a trusted local GPU and an untrusted cloud GPU, communicating only intermediate activations over the network. Our system addresses the unique challenges of autoregressive LLM decoding over high-latency wide-area networks (WANs), contributing: (1) an asymmetric layer split where embedding and unembedding layers remain local, ensuring raw tokens never leave the trusted device; (2) the first application of lookahead decoding to split inference over WANs, amortizing network round-trip latency across multiple tokens per iteration; (3) an empirical inversion attack evaluation showing that split depth provides a tunable privacy-performance tradeoff -- an attacker can recover ~59%% of tokens at a 2-layer split but only ~35%% at an 8-layer split, with minimal throughput impact; (4) ablation experiments showing that n-gram speculation accepts 1.2-1.3 tokens per decoding step on average (peak of 7 observed on code), with acceptance rates consistent across model scales; (5) formal verification that lookahead decoding produces token-identical output to sequential decoding under greedy argmax, with zero quality degradation; and (6) scaling validation on Mistral NeMo 12B (40 layers), demonstrating that the system generalizes to larger models with only 4.9 GB local VRAM and matching 7B throughput. Evaluated on Mistral 7B and NeMo 12B over a ~80ms WAN link, our system achieves 8.7-9.3 tok/s (7B) and 7.8-8.7 tok/s (12B) with lookahead decoding, with an RTT decomposition model (validated at <6.2%% cross-validation error) projecting 15-19 tok/s at 20ms RTT.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.16100v1">LLM-Driven Intent-Based Privacy-Aware Orchestration Across the Cloud-Edge Continuum</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2026-02-18T00:09:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zijie Su, Muhammed Tawfiqul Islam, Mohammad Goudarzi, Adel N. Toosi</p>
    <p><b>Summary:</b> With the rapid advancement of large language models (LLMs), efficiently serving LLM inference under limited GPU resources has become a critical challenge. Recently, an increasing number of studies have explored applying serverless computing paradigms to LLM serving in order to maximize resource utilization. However, LLM inference workloads are highly diverse, and modern GPU clusters are inherently heterogeneous, making it necessary to dynamically adjust deployment configurations online to better adapt to the elastic and dynamic nature of serverless environments. At the same time, enabling such online reconfiguration is particularly challenging due to the stateful nature of LLM inference and the massive size of model parameters. In this paper, we propose a dynamic pipeline reconfiguration approach that enables online adjustment of pipeline configurations while minimizing service downtime and performance degradation. Our method allows the system to select the optimal pipeline configuration in response to changing workloads. Experimental results on heterogeneous GPU platforms, including NVIDIA A100 and L40s, demonstrate that our migration mechanism incurs less than 50 ms of service downtime, while introducing under 10% overhead on both time-to-first-token (TTFT) and time-per-output-token (TPOT).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.15815v1">Natural Privacy Filters Are Not Always Free: A Characterization of Free Natural Filters</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2026-02-17T18:52:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Matthew Regehr, Bingshan Hu, Ethan Leeman, Pasin Manurangsi, Pierre Tholoniat, Mathias Lécuyer</p>
    <p><b>Summary:</b> We study natural privacy filters, which enable the exact composition of differentially private (DP) mechanisms with adaptively chosen privacy characteristics. Earlier privacy filters consider only simple privacy parameters such as Rényi-DP or Gaussian DP parameters. Natural filters account for the entire privacy profile of every query, promising greater utility for a given privacy budget. We show that, contrary to other forms of DP, natural privacy filters are not free in general. Indeed, we show that only families of privacy mechanisms that are well-ordered when composed admit free natural privacy filters.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.15802v1">Local Node Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-02-17T18:41:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sofya Raskhodnikova, Adam Smith, Connor Wagaman, Anatoly Zavyalov</p>
    <p><b>Summary:</b> We initiate an investigation of node differential privacy for graphs in the local model of private data analysis. In our model, dubbed LNDP, each node sees its own edge list and releases the output of a local randomizer on this input. These outputs are aggregated by an untrusted server to obtain a final output.
  We develop a novel algorithmic framework for this setting that allows us to accurately answer arbitrary linear queries on a blurry approximation of the input graph's degree distribution. For some natural problems, the resulting algorithms match the accuracy achievable with node privacy in the central model, where data are held and processed by a trusted server. We also prove lower bounds on the error required by LNDP that imply the optimality of our algorithms for several fundamental graph statistics. We then lift these lower bounds to the interactive LNDP setting, demonstrating the optimality of our algorithms even when constantly many rounds of interaction are permitted. Obtaining our lower bounds requires new approaches, since those developed for the usual local model do not apply to the inherently overlapping inputs that arise from graphs. Finally, we prove structural results that reveal qualitative differences between local node privacy and the standard local model for tabular data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.15705v1">Privacy-Preserving and Secure Spectrum Sharing for Database-Driven Cognitive Radio Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-02-17T16:39:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Saleh Darzia, Gökcan Cantalib, Attila Altay Yavuza, Gürkan Gür</p>
    <p><b>Summary:</b> Database-driven cognitive radio networks (DB-CRNs) enable dynamic spectrum sharing through geolocation databases but introduce critical security and privacy challenges, including mandatory location disclosure, susceptibility to location spoofing, and denial-of-service (DoS) attacks on centralized services. Existing approaches address these issues in isolation and lack a unified, regulation-compliant solution under realistic adversarial conditions. In this work, we present a unified security framework for DB-CRNs that simultaneously provides location privacy, user anonymity, verifiable location, and DoS resilience. Our framework, denoted as SLAPX, enables privacy-preserving spectrum queries using delegatable anonymous credentials, supports adaptive location verification without revealing precise user location, and mitigates DoS attacks through verifiable delay functions (VDFs) combined with RLRS-based rate limiting. Extensive cryptographic benchmarking and network simulations demonstrate that SLAPX achieves significantly lower latency and communication overhead than existing solutions while effectively resisting location spoofing and DoS attacks. These results show that SLAPX is practical and well-suited for secure next-generation DB-CRN deployments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.15614v1">Onto-DP: Constructing Neighborhoods for Differential Privacy on Ontological Databases</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-02-17T14:42:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yasmine Hayder, Adrien Boiret, Cédric Eichler, Benjamin Nguyen</p>
    <p><b>Summary:</b> In this paper, we investigate how attackers can discover sensitive information embedded within databases by exploiting inference rules. We demonstrate the inadequacy of naively applied existing state of the art differential privacy (DP) models in safeguarding against such attacks. We introduce ontology aware differential privacy (Onto-DP), a novel extension of differential privacy paradigms built on top of any classical DP model by enriching it with semantic awareness. We show that this extension is a sufficient condition to adequately protect against attackers aware of inference rules.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.15919v1">Generalized Leverage Score for Scalable Assessment of Privacy Vulnerability</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-02-17T07:07:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Valentin Dorseuil, Jamal Atif, Olivier Cappé</p>
    <p><b>Summary:</b> Can the privacy vulnerability of individual data points be assessed without retraining models or explicitly simulating attacks? We answer affirmatively by showing that exposure to membership inference attack (MIA) is fundamentally governed by a data point's influence on the learned model. We formalize this in the linear setting by establishing a theoretical correspondence between individual MIA risk and the leverage score, identifying it as a principled metric for vulnerability. This characterization explains how data-dependent sensitivity translates into exposure, without the computational burden of training shadow models. Building on this, we propose a computationally efficient generalization of the leverage score for deep learning. Empirical evaluations confirm a strong correlation between the proposed score and MIA success, validating this metric as a practical surrogate for individual privacy risk assessment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.15377v1">Orchestration-Free Customer Service Automation: A Privacy-Preserving and Flowchart-Guided Framework</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-02-17T06:17:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mengze Hong, Chen Jason Zhang, Zichang Guo, Hanlin Gu, Di Jiang, Li Qing</p>
    <p><b>Summary:</b> Customer service automation has seen growing demand within digital transformation. Existing approaches either rely on modular system designs with extensive agent orchestration or employ over-simplified instruction schemas, providing limited guidance and poor generalizability. This paper introduces an orchestration-free framework using Task-Oriented Flowcharts (TOFs) to enable end-to-end automation without manual intervention. We first define the components and evaluation metrics for TOFs, then formalize a cost-efficient flowchart construction algorithm to abstract procedural knowledge from service dialogues. We emphasize local deployment of small language models and propose decentralized distillation with flowcharts to mitigate data scarcity and privacy issues in model training. Extensive experiments validate the effectiveness in various service tasks, with superior quantitative and application performance compared to strong baselines and market products. By releasing a web-based system demonstration with case studies, we aim to promote streamlined creation of future service automation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.15304v1">Hybrid Federated and Split Learning for Privacy Preserving Clinical Prediction and Treatment Optimization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-02-17T01:57:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Farzana Akter, Rakib Hossain, Deb Kanna Roy Toushi, Mahmood Menon Khan, Sultana Amin, Lisan Al Amin</p>
    <p><b>Summary:</b> Collaborative clinical decision support is often constrained by governance and privacy rules that prevent pooling patient-level records across institutions. We present a hybrid privacy-preserving framework that combines Federated Learning (FL) and Split Learning (SL) to support decision-oriented healthcare modeling without raw-data sharing. The approach keeps feature-extraction trunks on clients while hosting prediction heads on a coordinating server, enabling shared representation learning and exposing an explicit collaboration boundary where privacy controls can be applied. Rather than assuming distributed training is inherently private, we audit leakage empirically using membership inference on cut-layer representations and study lightweight defenses based on activation clipping and additive Gaussian noise. We evaluate across three public clinical datasets under non-IID client partitions using a unified pipeline and assess performance jointly along four deployment-relevant axes: factual predictive utility, uplift-based ranking under capacity constraints, audited privacy leakage, and communication overhead. Results show that hybrid FL-SL variants achieve competitive predictive performance and decision-facing prioritization behavior relative to standalone FL or SL, while providing a tunable privacy-utility trade-off that can reduce audited leakage without requiring raw-data sharing. Overall, the work positions hybrid FL-SL as a practical design space for privacy-preserving healthcare decision support where utility, leakage risk, and deployment cost must be balanced explicitly.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.15290v1">Intellicise Wireless Networks Meet Agentic AI: A Security and Privacy Perspective</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2026-02-17T01:19:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rui Meng, Zhidi Zhang, Song Gao, Yaheng Wang, Xiaodong Xu, Yijing Lin, Yiming Liu, Chenyuan Feng, Lexi Xu, Yi Ma, Ping Zhang, Rahim Tafazolli</p>
    <p><b>Summary:</b> Intellicise (Intelligent and Concise) wireless network is the main direction of the evolution of future mobile communication systems, a perspective now widely acknowledged across academia and industry. As a key technology within it, Agentic AI has garnered growing attention due to its advanced cognitive capabilities, enabled through continuous perception-memory-reasoning-action cycles. This paper first analyses the unique advantages that Agentic AI introduces to intellicise wireless networks. We then propose a structured taxonomy for Agentic AI-enhanced secure intellicise wireless networks. Building on this framework, we identify emerging security and privacy challenges introduced by Agentic AI and summarize targeted strategies to address these vulnerabilities. A case study further demonstrates Agentic AI's efficacy in defending against intelligent eavesdropping attacks. Finally, we outline key open research directions to guide future exploration in this field.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.15028v1">Long Context, Less Focus: A Scaling Gap in LLMs Revealed through Privacy and Personalization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-02-16T18:59:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shangding Gu</p>
    <p><b>Summary:</b> Large language models (LLMs) are increasingly deployed in privacy-critical and personalization-oriented scenarios, yet the role of context length in shaping privacy leakage and personalization effectiveness remains largely unexplored. We introduce a large-scale benchmark, PAPerBench, to systematically study how increasing context length influences both personalization quality and privacy protection in LLMs. The benchmark comprises approximately 29,000 instances with context lengths ranging from 1K to 256K tokens, yielding a total of 377K evaluation questions. It jointly evaluates personalization performance and privacy risks across diverse scenarios, enabling controlled analysis of long-context model behavior. Extensive evaluations across state-of-the-art LLMs reveal consistent performance degradation in both personalization and privacy as context length increases. We further provide a theoretical analysis of attention dilution under context scaling, explaining this behavior as an inherent limitation of soft attention in fixed-capacity Transformers. The empirical and theoretical findings together suggest a general scaling gap in current models -- long context, less focus. We release the benchmark to support reproducible evaluation and future research on scalable privacy and personalization. Code and data are available at https://github.com/SafeRL-Lab/PAPerBench</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.13941v1">Avoiding Social Judgment, Seeking Privacy: Investigating why Mothers Shift from Facebook Groups to Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-02-15T00:37:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shayla Sharmin, Sadia Afrin</p>
    <p><b>Summary:</b> Social media platforms, especially Facebook parenting groups, have long been used as informal support networks for mothers seeking advice and reassurance. However, growing concerns about social judgment, privacy exposure, and unreliable information are changing how mothers seek help. This exploratory mixed-method study examines why mothers are moving from Facebook parenting groups to large language models such as ChatGPT and Gemini. We conducted a cross-sectional online survey of 109 mothers. Results show that 41.3% of participants avoided Facebook parenting groups because they expected judgment from others. This difference was statistically significant across location and family structure. Mothers living in their home country and those in joint families were more likely to avoid Facebook groups. Qualitative findings revealed three themes: social judgment and exposure, LLMs as safe and private spaces, and quick and structured support. Participants described LLMs as immediate, emotionally safe, and reliable alternatives that reduce social risk when asking for help. Rather than replacing human support, LLMs appear to fill emotional and practical gaps within existing support systems. These findings show a change in maternal digital support and highlight the need to design LLM systems that support both information and emotional safety.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.13840v1">PrivAct: Internalizing Contextual Privacy Preservation via Multi-Agent Preference Training</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-02-14T18:07:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuhan Cheng, Hancheng Ye, Hai Helen Li, Jingwei Sun, Yiran Chen</p>
    <p><b>Summary:</b> Large language model (LLM) agents are increasingly deployed in personalized tasks involving sensitive, context-dependent information, where privacy violations may arise in agents' action due to the implicitness of contextual privacy. Existing approaches rely on external, inference-time interventions which are brittle, scenario-specific, and may expand the privacy attack surface. We propose PrivAct, a contextual privacy-aware multi-agent learning framework that internalizes contextual privacy preservation directly into models' generation behavior for privacy-compliant agentic actions. By embedding privacy preferences into each agent, PrivAct enhances system-wide contextual integrity while achieving a more favorable privacy-helpfulness tradeoff. Experiments across multiple LLM backbones and benchmarks demonstrate consistent improvements in contextual privacy preservation, reducing leakage rates by up to 12.32% while maintaining comparable helpfulness, as well as zero-shot generalization and robustness across diverse multi-agent topologies. Code is available at https://github.com/chengyh23/PrivAct.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.13555v1">Privacy-Concealing Cooperative Perception for BEV Scene Segmentation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-02-14T02:11:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Song Wang, Lingling Li, Marcus Santos, Guanghui Wang</p>
    <p><b>Summary:</b> Cooperative perception systems for autonomous driving aim to overcome the limited perception range of a single vehicle by communicating with adjacent agents to share sensing information. While this improves perception performance, these systems also face a significant privacy-leakage issue, as sensitive visual content can potentially be reconstructed from the shared data. In this paper, we propose a novel Privacy-Concealing Cooperation (PCC) framework for Bird's Eye View (BEV) semantic segmentation. Based on commonly shared BEV features, we design a hiding network to prevent an image reconstruction network from recovering the input images from the shared features. An adversarial learning mechanism is employed to train the network, where the hiding network works to conceal the visual clues in the BEV features while the reconstruction network attempts to uncover these clues. To maintain segmentation performance, the perception network is integrated with the hiding network and optimized end-to-end. The experimental results demonstrate that the proposed PCC framework effectively degrades the quality of the reconstructed images with minimal impact on segmentation performance, providing privacy protection for cooperating vehicles. The source code will be made publicly available upon publication.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.12749v1">SoK: Understanding the Pedagogical, Health, Ethical, and Privacy Challenges of Extended Reality in Early Childhood Education</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-02-13T09:25:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Supriya Khadka, Sanchari Das</p>
    <p><b>Summary:</b> Extended Reality (XR) combines dense sensing, real-time rendering, and close-range interaction, making its use in early childhood education both promising and high risk. To investigate this, we conduct a Systematization of Knowledge (SoK) of 111 peer-reviewed studies with children aged 3-8, quantifying how technical, pedagogical, health, privacy, and equity challenges arise in practice. We found that AR dominates the landscape (73%), focusing primarily on tablets or phones, while VR remains uncommon and typically relies on head mounted displays (HMDs). We integrate these quantitative patterns into a joint risk and attention matrix and an Augmented Human Development (AHD) model that link XR pipeline properties to cognitive load, sensory conflict, and access inequity. Finally, implementing a seven dimension coding scheme on a 0 - 2 scale, we obtain mean scholarly attention scores of 1.56 for pedagogy, 1.04 for privacy (primarily procedural consent), 0.96 for technical reliability, 0.92 for accessibility in low resource contexts, 0.81 for medical and health issues, 0.52 for accessibility for disabilities, and 0.14 for data security practices. This indicates that pedagogy receives the most systematic scrutiny, while data access practices is largely overlooked. We conclude by offering a roadmap for Child-Centered XR that helps HCI researchers and educators move beyond novelty to design systems that are developmentally aligned, secure by default, and accessible to diverse learners.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.12009v1">On the Sensitivity of Firing Rate-Based Federated Spiking Neural Networks to Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-02-12T14:40:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Luiz Pereira, Mirko Perkusich, Dalton Valadares, Kyller Gorgônio</p>
    <p><b>Summary:</b> Federated Neuromorphic Learning (FNL) enables energy-efficient and privacy-preserving learning on devices without centralizing data. However, real-world deployments require additional privacy mechanisms that can significantly alter training signals. This paper analyzes how Differential Privacy (DP) mechanisms, specifically gradient clipping and noise injection, perturb firing-rate statistics in Spiking Neural Networks (SNNs) and how these perturbations are propagated to rate-based FNL coordination. On a speech recognition task under non-IID settings, ablations across privacy budgets and clipping bounds reveal systematic rate shifts, attenuated aggregation, and ranking instability during client selection. Moreover, we relate these shifts to sparsity and memory indicators. Our findings provide actionable guidance for privacy-preserving FNL, specifically regarding the balance between privacy strength and rate-dependent coordination.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.11510v1">AgentLeak: A Full-Stack Benchmark for Privacy Leakage in Multi-Agent LLM Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-02-12T03:10:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Faouzi El Yagoubi, Ranwa Al Mallah, Godwin Badu-Marfo</p>
    <p><b>Summary:</b> Multi-agent Large Language Model (LLM) systems create privacy risks that current benchmarks cannot measure. When agents coordinate on tasks, sensitive data passes through inter-agent messages, shared memory, and tool arguments; pathways that output-only audits never inspect. We introduce AgentLeak, to the best of our knowledge the first full-stack benchmark for privacy leakage covering internal channels, spanning 1,000 scenarios across healthcare, finance, legal, and corporate domains, paired with a 32-class attack taxonomy and three-tier detection pipeline. Testing GPT-4o, GPT-4o-mini, Claude 3.5 Sonnet, Mistral Large, and Llama 3.3 70B across 4,979 traces reveals that multi-agent configurations reduce per-channel output leakage (C1: 27.2% vs 43.2% in single-agent) but introduce unmonitored internal channels that raise total system exposure to 68.9% (OR-aggregated across C1, C2, C5). Internal channels account for most of this gap: inter-agent messages (C2) leak at 68.8%, compared to 27.2% on C1 (output channel). This means that output-only audits miss 41.7% of violations. Claude 3.5 Sonnet, which emphasizes safety alignment in its design, achieves the lowest leakage rates on both external (3.3%) and internal (28.1%) channels, suggesting that model-level safety training may transfer to internal channel protection. Across all five models and four domains, the pattern C2 > C1 holds consistently, confirming that inter-agent communication is the primary vulnerability. These findings underscore the need for coordination frameworks that incorporate internal-channel privacy protections and enforce privacy controls on inter-agent communication.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.11026v1">Normalized Surveillance in the Datafied Car: How Autonomous Vehicle Users Rationalize Privacy Trade-offs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-02-11T16:52:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yehuda Perry, Tawfiq Ammari</p>
    <p><b>Summary:</b> Autonomous vehicles (AVs) are characterized by pervasive datafication and surveillance through sensors like in-cabin cameras, LIDAR, and GPS. Drawing on 16 semi-structured interviews with AV drivers analyzed using constructivist grounded theory, this study examines how users make sense of vehicular surveillance within everyday datafication. Findings reveal drivers demonstrate few AV-specific privacy concerns, instead normalizing monitoring through comparisons with established digital platforms. We theorize this indifference by situating AV surveillance within the `surveillance ecology' of platform environments, arguing the datafied car functions as a mobile extension of the `leaky home' -- private spaces rendered permeable through connected technologies continuously transmitting behavioral data.
  The study contributes to scholarship on surveillance beliefs, datafication, and platform governance by demonstrating how users who have accepted comprehensive smartphone and smart home monitoring encounter AV datafication as just another node in normalized data extraction. We highlight how geographic restrictions on data access -- currently limiting driver log access to California -- create asymmetries that impede informed privacy deliberation, exemplifying `tertiary digital divides.' Finally, we examine how machine learning's reliance on data-intensive approaches creates structural pressure for surveillance that transcends individual manufacturer choices. We propose governance interventions to democratize social learning, including universal data access rights, binding transparency requirements, and data minimization standards to prevent race-to-the-bottom dynamics in automotive datafication.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.11023v1">IU-GUARD: Privacy-Preserving Spectrum Coordination for Incumbent Users under Dynamic Spectrum Sharing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-02-11T16:49:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shaoyu Li, Hexuan Yu, Shanghao Shi, Md Mohaimin Al Barat, Yang Xiao, Y. Thomas Hou, Wenjing Lou</p>
    <p><b>Summary:</b> With the growing demand for wireless spectrum, dynamic spectrum sharing (DSS) frameworks such as the Citizens Broadband Radio Service (CBRS) have emerged as practical solutions to improve utilization while protecting incumbent users (IUs) such as military radars. However, current incumbent protection mechanisms face critical limitations. The Environmental Sensing Capability (ESC) requires costly sensor deployments and remains vulnerable to interference and security risks. Alternatively, the Incumbent Informing Capability (IIC) requires IUs to disclose their identities and operational parameters to the Spectrum Coordination System (SCS), creating linkable records that compromise operational privacy and mission secrecy. We propose IU-GUARD, a privacy-preserving spectrum sharing framework that enables IUs to access spectrum without revealing their identities. Leveraging verifiable credentials (VCs) and zero-knowledge proofs (ZKPs), IU-GUARD allows IUs to prove their authorization to the SCS while disclosing only essential operational parameters. This decouples IU identity from spectrum access, prevents cross-request linkage, and mitigates the risk of centralized SCS data leakage. We implement a prototype, and our evaluation shows that IU-GUARD achieves strong privacy guarantees with practical computation and communication overhead, making it suitable for real-time DSS deployment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.10877v1">Beyond Permissions: An Empirical Static Analysis of Privacy and Security Risks in Children-Oriented and General-Audience Mobile Apps for Gaming</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2026-02-11T14:06:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bakheet Aljedaani</p>
    <p><b>Summary:</b> Mobile gaming applications (apps) have become increasingly pervasive, including a growing number of games designed for children. Despite their popularity, these apps often integrate complex analytics, advertising, and attribution infrastructures that may introduce privacy and security risks. Existing research has primarily focused on tracking behaviors or monetization models, leaving configuration-level privacy exposure and children-oriented apps underexplored. In this study, we conducted a comparative static analysis of Android mobile games to investigate privacy and security risks beyond permission usage. The analysis follows a three-phase methodology comprising (i) designing study protocol, (ii) Android Package Kit (APK) collection and static inspection, and (iii) data analysis. We examined permissions, manifest-level configuration properties (e.g., backup settings, cleartext network traffic, and exported components), and embedded third-party Software Development Kit (SDK) ecosystems across children-oriented and general-audience mobile games. The extracted indicators are synthesized into qualitative privacy-risk categories to support comparative reporting. The results showed that while children-oriented games often request fewer permissions, they frequently exhibit configuration-level risks and embed third-party tracking SDKs similar to general-audience games. Architectural and configuration decisions play a critical role in shaping privacy risks, particularly for apps targeting children. This study contributes a holistic static assessment of privacy exposure in mobile games and provides actionable insights for developers, platform providers, and researchers seeking to improve privacy-by-design practices in mobile applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.10735v1">Calliope: A TTS-based Narrated E-book Creator Ensuring Exact Synchronization, Privacy, and Layout Fidelity</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2026-02-11T10:54:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hugo L. Hammer, Vajira Thambawita, Pål Halvorsen</p>
    <p><b>Summary:</b> A narrated e-book combines synchronized audio with digital text, highlighting the currently spoken word or sentence during playback. This format supports early literacy and assists individuals with reading challenges, while also allowing general readers to seamlessly switch between reading and listening. With the emergence of natural-sounding neural Text-to-Speech (TTS) technology, several commercial services have been developed to leverage these technology for converting standard text e-books into high-quality narrated e-books. However, no open-source solutions currently exist to perform this task. In this paper, we present Calliope, an open-source framework designed to fill this gap. Our method leverages state-of-the-art open-source TTS to convert a text e-book into a narrated e-book in the EPUB 3 Media Overlay format. The method offers several innovative steps: audio timestamps are captured directly during TTS, ensuring exact synchronization between narration and text highlighting; the publisher's original typography, styling, and embedded media are strictly preserved; and the entire pipeline operates offline. This offline capability eliminates recurring API costs, mitigates privacy concerns, and avoids copyright compliance issues associated with cloud-based services. The framework currently supports the state-of-the-art open-source TTS systems XTTS-v2 and Chatterbox. A potential alternative approach involves first generating narration via TTS and subsequently synchronizing it with the text using forced alignment. However, while our method ensures exact synchronization, our experiments show that forced alignment introduces drift between the audio and text highlighting significant enough to degrade the reading experience. Source code and usage instructions are available at https://github.com/hugohammer/TTS-Narrated-Ebook-Creator.git.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.10734v1">Security, Privacy and System-Level Resillience of 6G End-to-End System: Hexa-X-II Perspective</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2026-02-11T10:53:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pawani Porambage, Diego Lopez, Antonio Pastor, Bin Han, José María Jorquera Valero, Manuel Gil Pérez, Noelia Pérez Palma, Antonio Skarmeta, Prajnamaya Dass, Stefan Köpsell, Sonika Ujjwal, Javier José Díaz Rivera, Pol Alemany, Raul Muñoz, Jafar Mohammadi, Chaitanya Aggarwal, Betul Guvenc Paltun, Ferhat Karakoc</p>
    <p><b>Summary:</b> The sixth generation (6G) of mobile networks are being developed to overcome limitations in previous generations and meet emerging user demands. As a European project, the Smart Networks and Services Joint Undertaking (SNS JU) 6G Flagship project Hexa-X-II has a leading role for developing technologies and anchoring 6G end-to-end system. This paper summarizes the security, privacy and resilient (SPR) controls identified by Hexa-X-II project and their validation frameworks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.10684v1">Privacy Control in Conversational LLM Platforms: A Walkthrough Study</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2026-02-11T09:39:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhuoyang Li, Yanlai Wu, Yao Li, Xinning Gui, Yuhan Luo</p>
    <p><b>Summary:</b> Large language models (LLMs) are increasingly integrated into daily life through conversational interfaces, processing user data via natural language inputs and exhibiting advanced reasoning capabilities, which raises new concerns about user control over privacy. While much research has focused on potential privacy risks, less attention has been paid to the data control mechanisms these platforms provide. This study examines six conversational LLM platforms, analyzing how they define and implement features for users to access, edit, delete, and share data. Our analysis reveals an emerging paradigm of data control in conversational LLM platforms, where user data is generated and derived through interaction itself, natural language enables flexible yet often ambiguous control, and multi-user interactions with shared data raise questions of co-ownership and governance. Based on these findings, we offer practical insights for platform developers, policymakers, and researchers to design more effective and usable privacy controls in LLM-powered conversational interactions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.10631v1">Generative clinical time series models trained on moderate amounts of patient data are privacy preserving</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-02-11T08:23:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rustam Zhumagambetov, Niklas Giesa, Sebastian D. Boie, Stefan Haufe</p>
    <p><b>Summary:</b> Sharing medical data for machine learning model training purposes is often impossible due to the risk of disclosing identifying information about individual patients. Synthetic data produced by generative artificial intelligence (genAI) models trained on real data is often seen as one possible solution to comply with privacy regulations. While powerful genAI models for heterogeneous hospital time series have recently been introduced, such modeling does not guarantee privacy protection, as the generated data may still reveal identifying information about individuals in the models' training cohort. Applying established privacy mechanisms to generative time series models, however, proves challenging as post-hoc data anonymization through k-anonymization or similar techniques is limited, while model-centered privacy mechanisms that implement differential privacy (DP) may lead to unstable training, compromising the utility of generated data. Given these known limitations, privacy audits for generative time series models are currently indispensable regardless of the concrete privacy mechanisms applied to models and/or data. In this work, we use a battery of established privacy attacks to audit state-of-the-art hospital time series models, trained on the public MIMIC-IV dataset, with respect to privacy preservation. Furthermore, the eICU dataset was used to mount a privacy attack against the synthetic data generator trained on the MIMIC-IV dataset. Results show that established privacy attacks are ineffective against generated multivariate clinical time series when synthetic data generators are trained on large enough training datasets. Furthermore, we discuss how the use of existing DP mechanisms for these synthetic data generators would not bring desired improvement in privacy, but only a decrease in utility for machine learning prediction tasks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.10584v1">When Gradient Clipping Becomes a Control Mechanism for Differential Privacy in Deep Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-02-11T07:18:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohammad Partohaghighi, Roummel Marcia, Bruce J. West, YangQuan Chen</p>
    <p><b>Summary:</b> Privacy-preserving training on sensitive data commonly relies on differentially private stochastic optimization with gradient clipping and Gaussian noise. The clipping threshold is a critical control knob: if set too small, systematic over-clipping induces optimization bias; if too large, injected noise dominates updates and degrades accuracy. Existing adaptive clipping methods often depend on per-example gradient norm statistics, adding computational overhead and introducing sensitivity to datasets and architectures. We propose a control-driven clipping strategy that adapts the threshold using a lightweight, weight-only spectral diagnostic computed from model parameters. At periodic probe steps, the method analyzes a designated weight matrix via spectral decomposition and estimates a heavy-tailed spectral indicator associated with training stability. This indicator is smoothed over time and fed into a bounded feedback controller that updates the clipping threshold multiplicatively in the log domain. Because the controller uses only parameters produced during privacy-preserving training, the resulting threshold updates are post-processing and do not increase privacy loss beyond that of the underlying DP optimizer under standard composition accounting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2602.10510v1">Privacy-Utility Tradeoffs in Quantum Information Processing</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2026-02-11T04:21:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Theshani Nuradha, Sujeet Bhalerao, Felix Leditzky</p>
    <p><b>Summary:</b> When sensitive information is encoded in data, it is important to ensure the privacy of information when attempting to learn useful information from the data. There is a natural tradeoff whereby increasing privacy requirements may decrease the utility of a learning protocol. In the quantum setting of differential privacy, such tradeoffs between privacy and utility have so far remained largely unexplored. In this work, we study optimal privacy-utility tradeoffs for both generic and application-specific utility metrics when privacy is quantified by $(\varepsilon,δ)$-quantum local differential privacy. In the generic setting, we focus on optimizing fidelity and trace distance between the original state and the privatized state. We show that the depolarizing mechanism achieves the optimal utility for given privacy requirements. We then study the specific application of learning the expectation of an observable with respect to an input state when only given access to privatized states. We derive a lower bound on the number of samples of privatized data required to achieve a fixed accuracy guarantee with high probability. To prove this result, we employ existing lower bounds on private quantum hypothesis testing, thus showcasing the first operational use of them. We also devise private mechanisms that achieve optimal sample complexity with respect to the privacy parameters and accuracy parameters, demonstrating that utility can be significantly improved for specific tasks in contrast to the generic setting. In addition, we show that the number of samples required to privately learn observable expectation values scales as $Θ((\varepsilon β)^{-2})$, where $\varepsilon \in (0,1)$ is the privacy parameter and $β$ is the accuracy tolerance. We conclude by initiating the study of private classical shadows, which promise useful applications for private learning tasks.</p>
  </details>
</div>


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
  <h3><a href="http://arxiv.org/abs/2602.10154v1">PRISM-XR: Empowering Privacy-Aware XR Collaboration with Multimodal Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Multimedia-5BC0EB">
  <p><b>Published on:</b> 2026-02-09T21:28:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiangong Chen, Mingyu Zhu, Bin Li</p>
    <p><b>Summary:</b> Multimodal Large Language Models (MLLMs) enhance collaboration in Extended Reality (XR) environments by enabling flexible object and animation creation through the combination of natural language and visual inputs. However, visual data captured by XR headsets includes real-world backgrounds that may contain irrelevant or sensitive user information, such as credit cards left on the table or facial identities of other users. Uploading those frames to cloud-based MLLMs poses serious privacy risks, particularly when such data is processed without explicit user consent. Additionally, existing colocation and synchronization mechanisms in commercial XR APIs rely on time-consuming, privacy-invasive environment scanning and struggle to adapt to the highly dynamic nature of MLLM-integrated XR environments. In this paper, we propose PRISM-XR, a novel framework that facilitates multi-user collaboration in XR by providing privacy-aware MLLM integration. PRISM-XR employs intelligent frame preprocessing on the edge server to filter sensitive data and remove irrelevant context before communicating with cloud generative AI models. Additionally, we introduce a lightweight registration process and a fully customizable content-sharing mechanism to enable efficient, accurate, and privacy-preserving content synchronization among users. Our numerical evaluation results indicate that the proposed platform achieves nearly 90% accuracy in fulfilling user requests and less than 0.27 seconds registration time while maintaining spatial inconsistencies of less than 3.5 cm. Furthermore, we conducted an IRB-approved user study with 28 participants, demonstrating that our system could automatically filter highly sensitive objects in over 90% of scenarios while maintaining strong overall usability.</p>
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
  <h3><a href="http://arxiv.org/abs/2602.10142v1">Privacy by Voice: Modeling Youth Privacy-Protective Behavior in Smart Voice Assistants</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2026-02-09T05:56:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Molly Campbell, Ajay Kumar Shrestha</p>
    <p><b>Summary:</b> Smart Voice Assistants (SVAs) are deeply embedded in the lives of youth, yet the mechanisms driving the privacy-protective behaviors among young users remain poorly understood. This study investigates how Canadian youth (aged 16-24) negotiate privacy with SVAs by developing and testing a structural model grounded in five key constructs: perceived privacy risks (PPR), perceived benefits (PPBf), algorithmic transparency and trust (ATT), privacy self-efficacy (PSE), and privacy-protective behaviors (PPB). A cross-sectional survey of N=469 youth was analyzed using partial least squares structural equation modeling. Results reveal that PSE is the strongest predictor of PPB, while the effect of ATT on PPB is fully mediated by PSE. This identifies a critical efficacy gap, where youth's confidence must first be built up for them to act. The model confirms that PPBf directly discourages protective action, yet also indirectly fosters it by slightly boosting self-efficacy. These findings empirically validate and extend earlier qualitative work, quantifying how policy overload and hidden controls erode the self-efficacy necessary for protective action. This study contributes an evidence-based pathway from perception to action and translates it into design imperatives that empower young digital citizens without sacrificing the utility of SVAs.</p>
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
  <h3><a href="http://arxiv.org/abs/2602.10139v2">Anonymization-Enhanced Privacy Protection for Mobile GUI Agents: Available but Invisible</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2026-02-08T15:50:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lepeng Zhao, Zhenhua Zou, Shuo Li, Zhuotao Liu</p>
    <p><b>Summary:</b> Mobile Graphical User Interface (GUI) agents have demonstrated strong capabilities in automating complex smartphone tasks by leveraging multimodal large language models (MLLMs) and system-level control interfaces. However, this paradigm introduces significant privacy risks, as agents typically capture and process entire screen contents, thereby exposing sensitive personal data such as phone numbers, addresses, messages, and financial information. Existing defenses either reduce UI exposure, obfuscate only task-irrelevant content, or rely on user authorization, but none can protect task-critical sensitive information while preserving seamless agent usability.
  We propose an anonymization-based privacy protection framework that enforces the principle of available-but-invisible access to sensitive data: sensitive information remains usable for task execution but is never directly visible to the cloud-based agent. Our system detects sensitive UI content using a PII-aware recognition model and replaces it with deterministic, type-preserving placeholders (e.g., PHONE_NUMBER#a1b2c) that retain semantic categories while removing identifying details. A layered architecture comprising a PII Detector, UI Transformer, Secure Interaction Proxy, and Privacy Gatekeeper ensures consistent anonymization across user instructions, XML hierarchies, and screenshots, mediates all agent actions over anonymized interfaces, and supports narrowly scoped local computations when reasoning over raw values is necessary.
  Extensive experiments on the AndroidLab and PrivScreen benchmarks show that our framework substantially reduces privacy leakage across multiple models while incurring only modest utility degradation, achieving the best observed privacy-utility trade-off among existing methods. Code available at: https://github.com/one-step-beh1nd/gui_privacy_protection</p>
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
  <h3><a href="http://arxiv.org/abs/2602.05016v2">From Fragmentation to Integration: Exploring the Design Space of AI Agents for Human-as-the-Unit Privacy Management</a></h3>
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

