
<h2>2024-06</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.20088v1">Minimax And Adaptive Transfer Learning for Nonparametric Classification
  under Distributed Differential Privacy Constraints</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">    
  <p><b>Published on:</b> 2024-06-28T17:55:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arnab Auddy, T. Tony Cai, Abhinav Chakraborty</p>
    <p><b>Summary:</b> This paper considers minimax and adaptive transfer learning for nonparametric
classification under the posterior drift model with distributed differential
privacy constraints. Our study is conducted within a heterogeneous framework,
encompassing diverse sample sizes, varying privacy parameters, and data
heterogeneity across different servers. We first establish the minimax
misclassification rate, precisely characterizing the effects of privacy
constraints, source samples, and target samples on classification accuracy. The
results reveal interesting phase transition phenomena and highlight the
intricate trade-offs between preserving privacy and achieving classification
accuracy. We then develop a data-driven adaptive classifier that achieves the
optimal rate within a logarithmic factor across a large collection of parameter
spaces while satisfying the same set of differential privacy constraints.
Simulation studies and real-world data applications further elucidate the
theoretical analysis with numerical results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.19964v1">Secure Outsourced Decryption for HE-based Privacy-preserving Cloud
  Computing System</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-28T14:51:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xirong Ma, Chuan Li, Yuchang Hu, Yunting Tao, Yali Jiang, Yanbin Li, Fanyu Kong, Chunpeng Ge</p>
    <p><b>Summary:</b> The demand for processing vast volumes of data has surged dramatically due to
the advancement of machine learning technology. Large-scale data processing
necessitates substantial computational resources, prompting individuals and
enterprises to turn to cloud services. Accompanying this trend is a growing
concern regarding data leakage and misuse. Homomorphic encryption (HE) is one
solution for safeguarding data privacy, enabling encrypted data to be processed
securely in the cloud. However, we observe that encryption and decryption
routines of some HE schemes require considerable computational resources,
presenting non-trivial work for clients. In this paper, we propose an
outsourced decryption protocol for RLWE-based HE schemes, which splits the
original decryption into two routines, with the computationally intensive part
executed remotely by the cloud. Its security relies on an invariant of the
NTRU-search problem with a newly designed secret distribution. Cryptographic
analyses are conducted to configure protocol parameters across varying security
levels. Our experiments demonstrate that the proposed protocol achieves up to a
$67\%$ acceleration in the client's local decryption, accompanied by a $50\%$
reduction in space usage.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.19642v1">IDT: Dual-Task Adversarial Attacks for Privacy Protection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-06-28T04:14:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pedro Faustini, Shakila Mahjabin Tonni, Annabelle McIver, Qiongkai Xu, Mark Dras</p>
    <p><b>Summary:</b> Natural language processing (NLP) models may leak private information in
different ways, including membership inference, reconstruction or attribute
inference attacks. Sensitive information may not be explicit in the text, but
hidden in underlying writing characteristics. Methods to protect privacy can
involve using representations inside models that are demonstrated not to detect
sensitive attributes or -- for instance, in cases where users might not trust a
model, the sort of scenario of interest here -- changing the raw text before
models can have access to it. The goal is to rewrite text to prevent someone
from inferring a sensitive attribute (e.g. the gender of the author, or their
location by the writing style) whilst keeping the text useful for its original
intention (e.g. the sentiment of a product review). The few works tackling this
have focused on generative techniques. However, these often create extensively
different texts from the original ones or face problems such as mode collapse.
This paper explores a novel adaptation of adversarial attack techniques to
manipulate a text to deceive a classifier w.r.t one task (privacy) whilst
keeping the predictions of another classifier trained for another task
(utility) unchanged. We propose IDT, a method that analyses predictions made by
auxiliary and interpretable models to identify which tokens are important to
change for the privacy task, and which ones should be kept for the utility
task. We evaluate different datasets for NLP suitable for different tasks.
Automatic and human evaluations show that IDT retains the utility of text,
while also outperforming existing methods when deceiving a classifier w.r.t
privacy task.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.19035v1">SD-BLS: Privacy Preserving Selective Disclosure and Unlinkable
  Revocation of Verifiable Credentials</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-27T09:41:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Denis Roio, Rebecca Selvaggini, Andrea D'Intino</p>
    <p><b>Summary:</b> It is of critical importance to design digital identity systems that ensure
the privacy of citizens as well as protecting them from issuer corruption.
Unfortunately, what Europe's and USA's public sectors are currently developing
does not offer such basic protections. We aim to solve this issue and propose a
method for untraceable selective disclosure and privacy preserving revocation
of digital credentials, using the unique homomorphic characteristics of second
order Elliptic Curves and Boneh-Lynn-Shacham (BLS) signatures. Our approach
ensures that users can selectively reveal only the necessary credentials, while
protecting their privacy across multiple presentations. We also aim to protect
users from issuer corruption, by making it possible to apply a threshold for
revocation to require collective agreement among multiple revocation issuers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.18940v1">Efficient Verifiable Differential Privacy with Input Authenticity in the
  Local and Shuffle Model</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-27T07:12:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tariq Bontekoe, Hassan Jameel Asghar, Fatih Turkmen</p>
    <p><b>Summary:</b> Local differential privacy (LDP) is an efficient solution for providing
privacy to client's sensitive data while simultaneously releasing aggregate
statistics without relying on a trusted central server (aggregator) as in the
central model of differential privacy. The shuffle model with LDP provides an
additional layer of privacy, by disconnecting the link between clients and the
aggregator, further improving the utility of LDP. However, LDP has been shown
to be vulnerable to malicious clients who can perform both input and output
manipulation attacks, i.e., before and after applying the LDP mechanism, to
skew the aggregator's results. In this work, we show how to prevent malicious
clients from compromising LDP schemes. Specifically, we give efficient
constructions to prevent both input \'and output manipulation attacks from
malicious clients for generic LDP algorithms. Our proposed schemes for
verifiable LDP (VLDP), completely protect from output manipulation attacks, and
prevent input attacks using signed data, requiring only one-time interaction
between client and server, unlike existing alternatives [28, 33]. Most
importantly, we are the first to provide an efficient scheme for VLDP in the
shuffle model. We describe and prove secure, two schemes for VLDP in the
regular model, and one in the shuffle model. We show that all schemes are
highly practical, with client runtimes of < 2 seconds, and server runtimes of
5-7 milliseconds per client.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.18812v1">A Survey on Privacy Attacks Against Digital Twin Systems in AI-Robotics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-06-27T00:59:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ivan A. Fernandez, Subash Neupane, Trisha Chakraborty, Shaswata Mitra, Sudip Mittal, Nisha Pillai, Jingdao Chen, Shahram Rahimi</p>
    <p><b>Summary:</b> Industry 4.0 has witnessed the rise of complex robots fueled by the
integration of Artificial Intelligence/Machine Learning (AI/ML) and Digital
Twin (DT) technologies. While these technologies offer numerous benefits, they
also introduce potential privacy and security risks. This paper surveys privacy
attacks targeting robots enabled by AI and DT models. Exfiltration and data
leakage of ML models are discussed in addition to the potential extraction of
models derived from first-principles (e.g., physics-based). We also discuss
design considerations with DT-integrated robotics touching on the impact of ML
model training, responsible AI and DT safeguards, data governance and ethical
considerations on the effectiveness of these attacks. We advocate for a trusted
autonomy approach, emphasizing the need to combine robotics, AI, and DT
technologies with robust ethical frameworks and trustworthiness principles for
secure and reliable AI robotic systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.18731v1">WavRx: a Disease-Agnostic, Generalizable, and Privacy-Preserving Speech
  Health Diagnostic Model</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-06-26T19:59:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yi Zhu, Tiago Falk</p>
    <p><b>Summary:</b> Speech is known to carry health-related attributes, which has emerged as a
novel venue for remote and long-term health monitoring. However, existing
models are usually tailored for a specific type of disease, and have been shown
to lack generalizability across datasets. Furthermore, concerns have been
raised recently towards the leakage of speaker identity from health embeddings.
To mitigate these limitations, we propose WavRx, a speech health diagnostics
model that captures the respiration and articulation related dynamics from a
universal speech representation. Our in-domain and cross-domain experiments on
six pathological speech datasets demonstrate WavRx as a new state-of-the-art
health diagnostic model. Furthermore, we show that the amount of speaker
identity entailed in the WavRx health embeddings is significantly reduced
without extra guidance during training. An in-depth analysis of the model was
performed, thus providing physiological interpretation of its improved
generalizability and privacy-preserving ability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.18491v1">Enhancing Federated Learning with Adaptive Differential Privacy and
  Priority-Based Aggregation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-06-26T16:55:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mahtab Talaei, Iman Izadi</p>
    <p><b>Summary:</b> Federated learning (FL), a novel branch of distributed machine learning (ML),
develops global models through a private procedure without direct access to
local datasets. However, it is still possible to access the model updates
(gradient updates of deep neural networks) transferred between clients and
servers, potentially revealing sensitive local information to adversaries using
model inversion attacks. Differential privacy (DP) offers a promising approach
to addressing this issue by adding noise to the parameters. On the other hand,
heterogeneities in data structure, storage, communication, and computational
capabilities of devices can cause convergence problems and delays in developing
the global model. A personalized weighted averaging of local parameters based
on the resources of each device can yield a better aggregated model in each
round. In this paper, to efficiently preserve privacy, we propose a
personalized DP framework that injects noise based on clients' relative impact
factors and aggregates parameters while considering heterogeneities and
adjusting properties. To fulfill the DP requirements, we first analyze the
convergence boundary of the FL algorithm when impact factors are personalized
and fixed throughout the learning process. We then further study the
convergence property considering time-varying (adaptive) impact factors.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.19418v1">A Quantization-based Technique for Privacy Preserving Distributed
  Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-06-26T14:54:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maurizio Colombo, Rasool Asal, Ernesto Damiani, Lamees Mahmoud AlQassem, Al Anoud Almemari, Yousof Alhammadi</p>
    <p><b>Summary:</b> The massive deployment of Machine Learning (ML) models raises serious
concerns about data protection. Privacy-enhancing technologies (PETs) offer a
promising first step, but hard challenges persist in achieving confidentiality
and differential privacy in distributed learning. In this paper, we describe a
novel, regulation-compliant data protection technique for the distributed
training of ML models, applicable throughout the ML life cycle regardless of
the underlying ML architecture. Designed from the data owner's perspective, our
method protects both training data and ML model parameters by employing a
protocol based on a quantized multi-hash data representation Hash-Comb combined
with randomization. The hyper-parameters of our scheme can be shared using
standard Secure Multi-Party computation protocols. Our experimental results
demonstrate the robustness and accuracy-preserving properties of our approach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.18221v1">Enhancing Data Privacy in Large Language Models through Private
  Association Editing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-06-26T10:08:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Davide Venditti, Elena Sofia Ruzzetti, Giancarlo A. Xompero, Cristina Giannone, Andrea Favalli, Raniero Romagnoli, Fabio Massimo Zanzotto</p>
    <p><b>Summary:</b> Large Language Models (LLMs) are powerful tools with extensive applications,
but their tendency to memorize private information raises significant concerns
as private data leakage can easily happen. In this paper, we introduce Private
Association Editing (PAE), a novel defense approach for private data leakage.
PAE is designed to effectively remove Personally Identifiable Information (PII)
without retraining the model. Our approach consists of a four-step procedure:
detecting memorized PII, applying PAE cards to mitigate memorization of private
data, verifying resilience to targeted data extraction (TDE) attacks, and
ensuring consistency in the post-edit LLMs. The versatility and efficiency of
PAE, which allows for batch modifications, significantly enhance data privacy
in LLMs. Experimental results demonstrate the effectiveness of PAE in
mitigating private data leakage. We believe PAE will serve as a critical tool
in the ongoing effort to protect data privacy in LLMs, encouraging the
development of safer models for real-world applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.18100v1">Natural Language but Omitted? On the Ineffectiveness of Large Language
  Models' privacy policy from End-users' Perspective</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-06-26T06:31:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuning Zhang, Haobin Xing, Xin Yi, Hewu Li</p>
    <p><b>Summary:</b> LLMs driven products were increasingly prevalent in our daily lives, With a
natural language based interaction style, people may potentially leak their
personal private information. Thus, privacy policy and user agreement played an
important role in regulating and alerting people. However, there lacked the
work examining the reading of LLM's privacy policy. Thus, we conducted the
first user study to let participants read the privacy policy and user agreement
with two different styles (a cursory and detailed style). We found users lack
important information upon cursory reading and even detailed reading. Besides,
their privacy concerns was not solved even upon detailed reading. We provided
four design implications based on the findings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.17649v1">Privacy Preserving Reinforcement Learning for Population Processes</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-25T15:41:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Samuel Yang-Zhao, Kee Siong Ng</p>
    <p><b>Summary:</b> We consider the problem of privacy protection in Reinforcement Learning (RL)
algorithms that operate over population processes, a practical but understudied
setting that includes, for example, the control of epidemics in large
populations of dynamically interacting individuals. In this setting, the RL
algorithm interacts with the population over $T$ time steps by receiving
population-level statistics as state and performing actions which can affect
the entire population at each time step. An individual's data can be collected
across multiple interactions and their privacy must be protected at all times.
We clarify the Bayesian semantics of Differential Privacy (DP) in the presence
of correlated data in population processes through a Pufferfish Privacy
analysis. We then give a meta algorithm that can take any RL algorithm as input
and make it differentially private. This is achieved by taking an approach that
uses DP mechanisms to privatize the state and reward signal at each time step
before the RL algorithm receives them as input. Our main theoretical result
shows that the value-function approximation error when applying standard RL
algorithms directly to the privatized states shrinks quickly as the population
size and privacy budget increase. This highlights that reasonable
privacy-utility trade-offs are possible for differentially private RL
algorithms in population processes. Our theoretical findings are validated by
experiments performed on a simulated epidemic control problem over large
population sizes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.16826v1">Practical privacy metrics for synthetic data</a></h3>
  
  <p><b>Published on:</b> 2024-06-24T17:35:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gillian M Raab, Beata Nowok, Chris Dibben</p>
    <p><b>Summary:</b> This paper explains how the synthpop package for R has been extended to
include functions to calculate measures of identity and attribute disclosure
risk for synthetic data that measure risks for the records used to create the
synthetic data. The basic function, disclosure, calculates identity disclosure
for a set of quasi-identifiers (keys) and attribute disclosure for one variable
specified as a target from the same set of keys. The second function,
disclosure.summary, is a wrapper for the first and presents summary results for
a set of targets. This short paper explains the measures of disclosure risk and
documents how they are calculated. We recommend two measures: $RepU$
(replicated uniques) for identity disclosure and $DiSCO$ (Disclosive in
Synthetic Correct Original) for attribute disclosure. Both are expressed a \%
of the original records and each can be compared to similar measures calculated
from the original data. Experience with using the functions on real data found
that some apparent disclosures could be identified as coming from relationships
in the data that would be expected to be known to anyone familiar with its
features. We flag cases when this seems to have occurred and provide means of
excluding them.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.16456v1">Automated Privacy-Preserving Techniques via Meta-Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-24T08:53:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tânia Carvalho, Nuno Moniz, Luís Antunes</p>
    <p><b>Summary:</b> Sharing private data for learning tasks is pivotal for transparent and secure
machine learning applications. Many privacy-preserving techniques have been
proposed for this task aiming to transform the data while ensuring the privacy
of individuals. Some of these techniques have been incorporated into tools,
whereas others are accessed through various online platforms. However, such
tools require manual configuration, which can be complex and time-consuming.
Moreover, they require substantial expertise, potentially restricting their use
to those with advanced technical knowledge. In this paper, we propose AUTOPRIV,
the first automated privacy-preservation method, that eliminates the need for
any manual configuration. AUTOPRIV employs meta-learning to automate the
de-identification process, facilitating the secure release of data for machine
learning tasks. The main goal is to anticipate the predictive performance and
privacy risk of a large set of privacy configurations. We provide a ranked list
of the most promising solutions, which are likely to achieve an optimal
approximation within a new domain. AUTOPRIV is highly effective as it reduces
computational complexity and energy consumption considerably.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.16313v1">Thinking Inside The Box: Privacy Against Stronger Adversaries</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-24T04:40:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Eldon Chung</p>
    <p><b>Summary:</b> In this thesis, we study extensions of statistical cryptographic primitives.
In particular we study leakage-resilient secret sharing, non-malleable
extractors, and immunized ideal one-way functions. The thesis is divided into
three main chapters. In the first chapter, we show that 2-out-of-2 leakage
resilient (and also non-malleable) secret sharing requires randomness sources
that are also extractable. This rules out the possibility of using min-entropic
sources. In the second, we introduce collision-resistant seeded extractors and
show that any seeded extractor can be made collision resistant at a small
overhead in seed length. We then use it to give a two-source non-malleable
extractor with entropy rate 0.81 in one source and polylogarithmic in the
other. The non-malleable extractor lead to the first statistical privacy
amplification protocol against memory tampering adversaries. In the final
chapter, we study the hardness of the data structure variant of the 3SUM
problem which is motivated by a recent construction to immunise random oracles
against pre-processing adversaries. We give worst-case data structure hardness
for the 3SUM problem matching known barriers in data structures for adaptive
adversaries. We also give a slightly stronger lower bound in the case of
non-adaptivity. Lastly, we give a novel result in the bit-probe setting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.16305v1">On Computing Pairwise Statistics with Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-24T04:06:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Badih Ghazi, Pritish Kamath, Ravi Kumar, Pasin Manurangsi, Adam Sealfon</p>
    <p><b>Summary:</b> We study the problem of computing pairwise statistics, i.e., ones of the form
$\binom{n}{2}^{-1} \sum_{i \ne j} f(x_i, x_j)$, where $x_i$ denotes the input
to the $i$th user, with differential privacy (DP) in the local model. This
formulation captures important metrics such as Kendall's $\tau$ coefficient,
Area Under Curve, Gini's mean difference, Gini's entropy, etc. We give several
novel and generic algorithms for the problem, leveraging techniques from DP
algorithms for linear queries.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.16182v1">Privacy-Preserving and Trustworthy Localization in an IoT Environment</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-06-23T18:13:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guglielmo Zocca, Omar Hasan</p>
    <p><b>Summary:</b> The Internet of Things (IoT) is increasingly prevalent in various
applications, such as healthcare and logistics. One significant service of IoT
technologies that is essential for these applications is localization. The goal
of this service is to determine the precise position of a specific target. The
localization data often needs to be private, accessible only to specific
entities, and must maintain authenticity and integrity to ensure
trustworthiness. IoT technology has evolved significantly, with Ultra-Wide Band
(UWB) technology enhancing localization speed and precision. However, IoT
device security remains a concern, as devices can be compromised or act
maliciously. Furthermore, localization data is typically stored centrally,
which can also be a point of vulnerability. Our approach leverages the features
of a permissioned blockchain, specifically Hyperledger Fabric, to address these
challenges. Hyperledger Fabric's collection feature ensures data privacy, and
its smart contracts (chaincode) enhance trustworthiness. We tested our solution
using a network of devices known as CLOVES, demonstrating robust performance
characteristics with UWB technology. Additionally, we evaluated our approach
through an indoor localization use case.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.15962v1">Privacy Preserving Machine Learning for Electronic Health Records using
  Federated Learning and Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2024-06-23T00:01:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Naif A. Ganadily, Han J. Xia</p>
    <p><b>Summary:</b> An Electronic Health Record (EHR) is an electronic database used by
healthcare providers to store patients' medical records which may include
diagnoses, treatments, costs, and other personal information. Machine learning
(ML) algorithms can be used to extract and analyze patient data to improve
patient care. Patient records contain highly sensitive information, such as
social security numbers (SSNs) and residential addresses, which introduces a
need to apply privacy-preserving techniques for these ML models using federated
learning and differential privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.15842v1">Privacy Requirements and Realities of Digital Public Goods</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-06-22T13:06:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Geetika Gopi, Aadyaa Maddi, Omkhar Arasaratnam, Giulia Fanti</p>
    <p><b>Summary:</b> In the international development community, the term "digital public goods"
is used to describe open-source digital products (e.g., software, datasets)
that aim to address the United Nations (UN) Sustainable Development Goals. DPGs
are increasingly being used to deliver government services around the world
(e.g., ID management, healthcare registration). Because DPGs may handle
sensitive data, the UN has established user privacy as a first-order
requirement for DPGs. The privacy risks of DPGs are currently managed in part
by the DPG standard, which includes a prerequisite questionnaire with questions
designed to evaluate a DPG's privacy posture.
  This study examines the effectiveness of the current DPG standard for
ensuring adequate privacy protections. We present a systematic assessment of
responses from DPGs regarding their protections of users' privacy. We also
present in-depth case studies from three widely-used DPGs to identify privacy
threats and compare this to their responses to the DPG standard. Our findings
reveal limitations in the current DPG standard's evaluation approach. We
conclude by presenting preliminary recommendations and suggestions for
strengthening the DPG standard as it relates to privacy. Additionally, we hope
this study encourages more usable privacy research on communicating privacy,
not only to end users but also third-party adopters of user-facing
technologies.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.15789v1">Privacy Implications of Explainable AI in Data-Driven Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-22T08:51:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fatima Ezzeddine</p>
    <p><b>Summary:</b> Machine learning (ML) models, demonstrably powerful, suffer from a lack of
interpretability. The absence of transparency, often referred to as the black
box nature of ML models, undermines trust and urges the need for efforts to
enhance their explainability. Explainable AI (XAI) techniques address this
challenge by providing frameworks and methods to explain the internal
decision-making processes of these complex models. Techniques like
Counterfactual Explanations (CF) and Feature Importance play a crucial role in
achieving this goal. Furthermore, high-quality and diverse data remains the
foundational element for robust and trustworthy ML applications. In many
applications, the data used to train ML and XAI explainers contain sensitive
information. In this context, numerous privacy-preserving techniques can be
employed to safeguard sensitive information in the data, such as differential
privacy. Subsequently, a conflict between XAI and privacy solutions emerges due
to their opposing goals. Since XAI techniques provide reasoning for the model
behavior, they reveal information relative to ML models, such as their decision
boundaries, the values of features, or the gradients of deep learning models
when explanations are exposed to a third entity. Attackers can initiate privacy
breaching attacks using these explanations, to perform model extraction,
inference, and membership attacks. This dilemma underscores the challenge of
finding the right equilibrium between understanding ML decision-making and
safeguarding privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.15655v1">ProBE: Proportioning Privacy Budget for Complex Exploratory Decision
  Support</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">
  <p><b>Published on:</b> 2024-06-21T21:20:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nada Lahjouji, Sameera Ghayyur, Xi He, Sharad Mehrotra</p>
    <p><b>Summary:</b> This paper studies privacy in the context of complex decision support queries
composed of multiple conditions on different aggregate statistics combined
using disjunction and conjunction operators. Utility requirements for such
queries necessitate the need for private mechanisms that guarantee a bound on
the false negative and false positive errors. This paper formally defines
complex decision support queries and their accuracy requirements, and provides
algorithms that proportion the existing budget to optimally minimize privacy
loss while supporting a bounded guarantee on the accuracy. Our experimental
results on multiple real-life datasets show that our algorithms successfully
maintain such utility guarantees, while also minimizing privacy loss.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.15346v1">Privacy Preserved Blood Glucose Level Cross-Prediction: An Asynchronous
  Decentralized Federated Learning Approach</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-06-21T17:57:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chengzhe Piao, Taiyu Zhu, Yu Wang, Stephanie E Baldeweg, Paul Taylor, Pantelis Georgiou, Jiahao Sun, Jun Wang, Kezhi Li</p>
    <p><b>Summary:</b> Newly diagnosed Type 1 Diabetes (T1D) patients often struggle to obtain
effective Blood Glucose (BG) prediction models due to the lack of sufficient BG
data from Continuous Glucose Monitoring (CGM), presenting a significant "cold
start" problem in patient care. Utilizing population models to address this
challenge is a potential solution, but collecting patient data for training
population models in a privacy-conscious manner is challenging, especially
given that such data is often stored on personal devices. Considering the
privacy protection and addressing the "cold start" problem in diabetes care, we
propose "GluADFL", blood Glucose prediction by Asynchronous Decentralized
Federated Learning. We compared GluADFL with eight baseline methods using four
distinct T1D datasets, comprising 298 participants, which demonstrated its
superior performance in accurately predicting BG levels for cross-patient
analysis. Furthermore, patients' data might be stored and shared across various
communication networks in GluADFL, ranging from highly interconnected (e.g.,
random, performs the best among others) to more structured topologies (e.g.,
cluster and ring), suitable for various social networks. The asynchronous
training framework supports flexible participation. By adjusting the ratios of
inactive participants, we found it remains stable if less than 70% are
inactive. Our results confirm that GluADFL offers a practical,
privacy-preserving solution for BG prediction in T1D, significantly enhancing
the quality of diabetes management.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.15309v1">The Privacy-Utility Trade-off in the Topics API</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-21T17:01:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mário S. Alvim, Natasha Fernandes, Annabelle McIver, Gabriel H. Nunes</p>
    <p><b>Summary:</b> The ongoing deprecation of third-party cookies by web browser vendors has
sparked the proposal of alternative methods to support more privacy-preserving
personalized advertising on web browsers and applications. The Topics API is
being proposed by Google to provide third-parties with "coarse-grained
advertising topics that the page visitor might currently be interested in". In
this paper, we analyze the re-identification risks for individual Internet
users and the utility provided to advertising companies by the Topics API, i.e.
learning the most popular topics and distinguishing between real and random
topics. We provide theoretical results dependent only on the API parameters
that can be readily applied to evaluate the privacy and utility implications of
future API updates, including novel general upper-bounds that account for
adversaries with access to unknown, arbitrary side information, the value of
the differential privacy parameter $\epsilon$, and experimental results on
real-world data that validate our theoretical model.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.15074v1">Balancing The Perception of Cheating Detection, Privacy and Fairness: A
  Mixed-Methods Study of Visual Data Obfuscation in Remote Proctoring</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-06-21T11:40:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Suvadeep Mukherjee, Verena Distler, Gabriele Lenzini, Pedro Cardoso-Leite</p>
    <p><b>Summary:</b> Remote proctoring technology, a cheating-preventive measure, often raises
privacy and fairness concerns that may affect test-takers' experiences and the
validity of test results. Our study explores how selectively obfuscating
information in video recordings can protect test-takers' privacy while ensuring
effective and fair cheating detection. Interviews with experts (N=9) identified
four key video regions indicative of potential cheating behaviors: the
test-taker's face, body, background and the presence of individuals in the
background. Experts recommended specific obfuscation methods for each region
based on privacy significance and cheating behavior frequency, ranging from
conventional blurring to advanced methods like replacement with deepfake, 3D
avatars and silhouetting. We then conducted a vignette experiment with
potential test-takers (N=259, non-experts) to evaluate their perceptions of
cheating detection, visual privacy and fairness, using descriptions and
examples of still images for each expert-recommended combination of video
regions and obfuscation methods. Our results indicate that the effectiveness of
obfuscation methods varies by region. Tailoring remote proctoring with
region-specific advanced obfuscation methods can improve the perceptions of
privacy and fairness compared to the conventional methods, though it may
decrease perceived information sufficiency for detecting cheating. However,
non-experts preferred conventional blurring for videos they were more willing
to share, highlighting a gap between the perceived effectiveness of the
advanced obfuscation methods and their practical acceptance. This study
contributes to the field of user-centered privacy by suggesting promising
directions to address current remote proctoring challenges and guiding future
research.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.14773v1">Mitigating the Privacy Issues in Retrieval-Augmented Generation (RAG)
  via Pure Synthetic Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-20T22:53:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shenglai Zeng, Jiankun Zhang, Pengfei He, Jie Ren, Tianqi Zheng, Hanqing Lu, Han Xu, Hui Liu, Yue Xing, Jiliang Tang</p>
    <p><b>Summary:</b> Retrieval-augmented generation (RAG) enhances the outputs of language models
by integrating relevant information retrieved from external knowledge sources.
However, when the retrieval process involves private data, RAG systems may face
severe privacy risks, potentially leading to the leakage of sensitive
information. To address this issue, we propose using synthetic data as a
privacy-preserving alternative for the retrieval data. We propose SAGE, a novel
two-stage synthetic data generation paradigm. In the stage-1, we employ an
attribute-based extraction and generation approach to preserve key contextual
information from the original data. In the stage-2, we further enhance the
privacy properties of the synthetic data through an agent-based iterative
refinement process. Extensive experiments demonstrate that using our synthetic
data as the retrieval context achieves comparable performance to using the
original data while substantially reducing privacy risks. Our work takes the
first step towards investigating the possibility of generating high-utility and
privacy-preserving synthetic data for RAG, opening up new opportunities for the
safe application of RAG systems in various domains.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.14772v1">Consistent community detection in multi-layer networks with
  heterogeneous differential privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B">
  <p><b>Published on:</b> 2024-06-20T22:49:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yaoming Zhen, Shirong Xu, Junhui Wang</p>
    <p><b>Summary:</b> As network data has become increasingly prevalent, a substantial amount of
attention has been paid to the privacy issue in publishing network data. One of
the critical challenges for data publishers is to preserve the topological
structures of the original network while protecting sensitive information. In
this paper, we propose a personalized edge flipping mechanism that allows data
publishers to protect edge information based on each node's privacy preference.
It can achieve differential privacy while preserving the community structure
under the multi-layer degree-corrected stochastic block model after
appropriately debiasing, and thus consistent community detection in the
privatized multi-layer networks is achievable. Theoretically, we establish the
consistency of community detection in the privatized multi-layer network and
show that better privacy protection of edges can be obtained for a proportion
of nodes while allowing other nodes to give up their privacy. Furthermore, the
advantage of the proposed personalized edge-flipping mechanism is also
supported by its numerical performance on various synthetic networks and a
real-life multi-layer network.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.14322v1">Mind the Privacy Unit! User-Level Differential Privacy for Language
  Model Fine-Tuning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-06-20T13:54:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lynn Chua, Badih Ghazi, Yangsibo Huang, Pritish Kamath, Daogao Liu, Pasin Manurangsi, Amer Sinha, Chiyuan Zhang</p>
    <p><b>Summary:</b> Large language models (LLMs) have emerged as powerful tools for tackling
complex tasks across diverse domains, but they also raise privacy concerns when
fine-tuned on sensitive data due to potential memorization. While differential
privacy (DP) offers a promising solution by ensuring models are `almost
indistinguishable' with or without any particular privacy unit, current
evaluations on LLMs mostly treat each example (text record) as the privacy
unit. This leads to uneven user privacy guarantees when contributions per user
vary. We therefore study user-level DP motivated by applications where it
necessary to ensure uniform privacy protection across users. We present a
systematic evaluation of user-level DP for LLM fine-tuning on natural language
generation tasks. Focusing on two mechanisms for achieving user-level DP
guarantees, Group Privacy and User-wise DP-SGD, we investigate design choices
like data selection strategies and parameter tuning for the best
privacy-utility tradeoff.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.14318v1">The Fire Thief Is Also the Keeper: Balancing Usability and Privacy in
  Prompts</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-06-20T13:52:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhili Shen, Zihang Xi, Ying He, Wei Tong, Jingyu Hua, Sheng Zhong</p>
    <p><b>Summary:</b> The rapid adoption of online chatbots represents a significant advancement in
artificial intelligence. However, this convenience brings considerable privacy
concerns, as prompts can inadvertently contain sensitive information exposed to
large language models (LLMs). Limited by high computational costs, reduced task
usability, and excessive system modifications, previous works based on local
deployment, embedding perturbation, and homomorphic encryption are inapplicable
to online prompt-based LLM applications.
  To address these issues, this paper introduces Prompt Privacy Sanitizer
(i.e., ProSan), an end-to-end prompt privacy protection framework that can
produce anonymized prompts with contextual privacy removed while maintaining
task usability and human readability. It can also be seamlessly integrated into
the online LLM service pipeline. To achieve high usability and dynamic
anonymity, ProSan flexibly adjusts its protection targets and strength based on
the importance of the words and the privacy leakage risk of the prompts.
Additionally, ProSan is capable of adapting to diverse computational resource
conditions, ensuring privacy protection even for mobile devices with limited
computing power. Our experiments demonstrate that ProSan effectively removes
private information across various tasks, including question answering, text
summarization, and code generation, with minimal reduction in task performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.14091v1">Protecting Privacy Through Approximating Optimal Parameters for Sequence
  Unlearning in Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-06-20T08:12:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dohyun Lee, Daniel Rim, Minseok Choi, Jaegul Choo</p>
    <p><b>Summary:</b> Although language models (LMs) demonstrate exceptional capabilities on
various tasks, they are potentially vulnerable to extraction attacks, which
represent a significant privacy risk. To mitigate the privacy concerns of LMs,
machine unlearning has emerged as an important research area, which is utilized
to induce the LM to selectively forget about some of its training data. While
completely retraining the model will guarantee successful unlearning and
privacy assurance, it is impractical for LMs, as it would be time-consuming and
resource-intensive. Prior works efficiently unlearn the target token sequences,
but upon subsequent iterations, the LM displays significant degradation in
performance. In this work, we propose Privacy Protection via Optimal Parameters
(POP), a novel unlearning method that effectively forgets the target token
sequences from the pretrained LM by applying optimal gradient updates to the
parameters. Inspired by the gradient derivation of complete retraining, we
approximate the optimal training objective that successfully unlearns the
target sequence while retaining the knowledge from the rest of the training
data. Experimental results demonstrate that POP exhibits remarkable retention
performance post-unlearning across 9 classification and 4 dialogue benchmarks,
outperforming the state-of-the-art by a large margin. Furthermore, we introduce
Remnant Memorization Accuracy that quantifies privacy risks based on token
likelihood and validate its effectiveness through both qualitative and
quantitative analyses.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.13880v1">Privacy-Preserving ECG Data Analysis with Differential Privacy: A
  Literature Review and A Case Study</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-19T23:17:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arin Ghazarian, Jianwei Zheng, Cyril Rakovski</p>
    <p><b>Summary:</b> Differential privacy has become the preeminent technique to protect the
privacy of individuals in a database while allowing useful results from data
analysis to be shared. Notably, it guarantees the amount of privacy loss in the
worst-case scenario. Although many theoretical research papers have been
published, practical real-life application of differential privacy demands
estimating several important parameters without any clear solutions or
guidelines. In the first part of the paper, we provide an overview of key
concepts in differential privacy, followed by a literature review and
discussion of its application to ECG analysis. In the second part of the paper,
we explore how to implement differentially private query release on an
arrhythmia database using a six-step process. We provide guidelines and discuss
the related literature for all the steps involved, such as selection of the
$\epsilon$ value, distribution of the total $\epsilon$ budget across the
queries, and estimation of the sensitivity for the query functions. At the end,
we discuss the shortcomings and challenges of applying differential privacy to
ECG datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.13433v1">Certificates of Differential Privacy and Unlearning for Gradient-Based
  Training</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-06-19T10:47:00Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Matthew Wicker, Philip Sosnin, Adrianna Janik, Mark N. Müller, Adrian Weller, Calvin Tsay</p>
    <p><b>Summary:</b> Proper data stewardship requires that model owners protect the privacy of
individuals' data used during training. Whether through anonymization with
differential privacy or the use of unlearning in non-anonymized settings, the
gold-standard techniques for providing privacy guarantees can come with
significant performance penalties or be too weak to provide practical
assurances. In part, this is due to the fact that the guarantee provided by
differential privacy represents the worst-case privacy leakage for any
individual, while the true privacy leakage of releasing the prediction for a
given individual might be substantially smaller or even, as we show,
non-existent. This work provides a novel framework based on convex relaxations
and bounds propagation that can compute formal guarantees (certificates) that
releasing specific predictions satisfies $\epsilon=0$ privacy guarantees or do
not depend on data that is subject to an unlearning request. Our framework
offers a new verification-centric approach to privacy and unlearning
guarantees, that can be used to further engender user trust with tighter
privacy guarantees, provide formal proofs of robustness to certain membership
inference attacks, identify potentially vulnerable records, and enhance current
unlearning approaches. We validate the effectiveness of our approach on tasks
from financial services, medical imaging, and natural language processing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.13221v1">Privacy-Preserving Logistic Regression Training on Large Datasets</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-19T05:19:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> John Chiang</p>
    <p><b>Summary:</b> Privacy-preserving machine learning is one class of cryptographic methods
that aim to analyze private and sensitive data while keeping privacy, such as
homomorphic logistic regression training over large encrypted data. In this
paper, we propose an efficient algorithm for logistic regression training on
large encrypted data using Homomorphic Encryption (HE), which is the mini-batch
version of recent methods using a faster gradient variant called
$\texttt{quadratic gradient}$. It is claimed that $\texttt{quadratic gradient}$
can integrate curve information (Hessian matrix) into the gradient and
therefore can effectively accelerate the first-order gradient (descent)
algorithms. We also implement the full-batch version of their method when the
encrypted dataset is so large that it has to be encrypted in the mini-batch
manner. We compare our mini-batch algorithm with our full-batch implementation
method on real financial data consisting of 422,108 samples with 200 freatures.
%Our experiments show that Nesterov's accelerated gradient (NAG) Given the
inefficiency of HEs, our results are inspiring and demonstrate that the
logistic regression training on large encrypted dataset is of practical
feasibility, marking a significant milestone in our understanding.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.13183v1">Communication-Efficient and Privacy-Preserving Decentralized
  Meta-Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-06-19T03:29:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hansi Yang, James T. Kwok</p>
    <p><b>Summary:</b> Distributed learning, which does not require gathering training data in a
central location, has become increasingly important in the big-data era. In
particular, random-walk-based decentralized algorithms are flexible in that
they do not need a central server trusted by all clients and do not require all
clients to be active in all iterations. However, existing distributed learning
algorithms assume that all learning clients share the same task. In this paper,
we consider the more difficult meta-learning setting, in which different
clients perform different (but related) tasks with limited training data. To
reduce communication cost and allow better privacy protection, we propose
LoDMeta (Local Decentralized Meta-learning) with the use of local auxiliary
optimization parameters and random perturbations on the model parameter.
Theoretical results are provided on both convergence and privacy analysis.
Empirical results on a number of few-shot learning data sets demonstrate that
LoDMeta has similar meta-learning accuracy as centralized meta-learning
algorithms, but does not require gathering data from each client and is able to
better protect data privacy for each client.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.13012v1">Data Plagiarism Index: Characterizing the Privacy Risk of Data-Copying
  in Tabular Generative Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-06-18T19:05:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joshua Ward, Chi-Hua Wang, Guang Cheng</p>
    <p><b>Summary:</b> The promise of tabular generative models is to produce realistic synthetic
data that can be shared and safely used without dangerous leakage of
information from the training set. In evaluating these models, a variety of
methods have been proposed to measure the tendency to copy data from the
training dataset when generating a sample. However, these methods suffer from
either not considering data-copying from a privacy threat perspective, not
being motivated by recent results in the data-copying literature or being
difficult to make compatible with the high dimensional, mixed type nature of
tabular data. This paper proposes a new similarity metric and Membership
Inference Attack called Data Plagiarism Index (DPI) for tabular data. We show
that DPI evaluates a new intuitive definition of data-copying and characterizes
the corresponding privacy risk. We show that the data-copying identified by DPI
poses both privacy and fairness threats to common, high performing
architectures; underscoring the necessity for more sophisticated generative
modeling techniques to mitigate this issue.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.12815v1">Privacy Preserving Federated Learning in Medical Imaging with
  Uncertainty Estimation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">  
  <p><b>Published on:</b> 2024-06-18T17:35:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nikolas Koutsoubis, Yasin Yilmaz, Ravi P. Ramachandran, Matthew Schabath, Ghulam Rasool</p>
    <p><b>Summary:</b> Machine learning (ML) and Artificial Intelligence (AI) have fueled remarkable
advancements, particularly in healthcare. Within medical imaging, ML models
hold the promise of improving disease diagnoses, treatment planning, and
post-treatment monitoring. Various computer vision tasks like image
classification, object detection, and image segmentation are poised to become
routine in clinical analysis. However, privacy concerns surrounding patient
data hinder the assembly of large training datasets needed for developing and
training accurate, robust, and generalizable models. Federated Learning (FL)
emerges as a compelling solution, enabling organizations to collaborate on ML
model training by sharing model training information (gradients) rather than
data (e.g., medical images). FL's distributed learning framework facilitates
inter-institutional collaboration while preserving patient privacy. However,
FL, while robust in privacy preservation, faces several challenges. Sensitive
information can still be gleaned from shared gradients that are passed on
between organizations during model training. Additionally, in medical imaging,
quantifying model confidence\uncertainty accurately is crucial due to the noise
and artifacts present in the data. Uncertainty estimation in FL encounters
unique hurdles due to data heterogeneity across organizations. This paper
offers a comprehensive review of FL, privacy preservation, and uncertainty
estimation, with a focus on medical imaging. Alongside a survey of current
research, we identify gaps in the field and suggest future directions for FL
research to enhance privacy and address noisy medical imaging data challenges.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.12736v1">Beyond Visual Appearances: Privacy-sensitive Objects Identification via
  Hybrid Graph Reasoning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-06-18T15:58:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhuohang Jiang, Bingkui Tong, Xia Du, Ahmed Alhammadi, Jizhe Zhou</p>
    <p><b>Summary:</b> The Privacy-sensitive Object Identification (POI) task allocates bounding
boxes for privacy-sensitive objects in a scene. The key to POI is settling an
object's privacy class (privacy-sensitive or non-privacy-sensitive). In
contrast to conventional object classes which are determined by the visual
appearance of an object, one object's privacy class is derived from the scene
contexts and is subject to various implicit factors beyond its visual
appearance. That is, visually similar objects may be totally opposite in their
privacy classes. To explicitly derive the objects' privacy class from the scene
contexts, in this paper, we interpret the POI task as a visual reasoning task
aimed at the privacy of each object in the scene. Following this
interpretation, we propose the PrivacyGuard framework for POI. PrivacyGuard
contains three stages. i) Structuring: an unstructured image is first converted
into a structured, heterogeneous scene graph that embeds rich scene contexts.
ii) Data Augmentation: a contextual perturbation oversampling strategy is
proposed to create slightly perturbed privacy-sensitive objects in a scene
graph, thereby balancing the skewed distribution of privacy classes. iii)
Hybrid Graph Generation & Reasoning: the balanced, heterogeneous scene graph is
then transformed into a hybrid graph by endowing it with extra "node-node" and
"edge-edge" homogeneous paths. These homogeneous paths allow direct message
passing between nodes or edges, thereby accelerating reasoning and facilitating
the capturing of subtle context changes. Based on this hybrid graph... **For
the full abstract, see the original paper.**</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.12592v1">Unmasking the Veil: An Investigation into Concept Ablation for Privacy
  and Copyright Protection in Images</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-06-18T13:22:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shivank Garg, Manyana Tiwari</p>
    <p><b>Summary:</b> In this paper, we extend the study of concept ablation within pre-trained
models as introduced in 'Ablating Concepts in Text-to-Image Diffusion Models'
by (Kumari et al.,2022). Our work focuses on reproducing the results achieved
by the different variants of concept ablation proposed and validated through
predefined metrics. We also introduce a novel variant of concept ablation,
namely 'trademark ablation'. This variant combines the principles of
memorization and instance ablation to tackle the nuanced influence of
proprietary or branded elements in model outputs. Further, our research
contributions include an observational analysis of the model's limitations.
Moreover, we investigate the model's behavior in response to ablation
leakage-inducing prompts, which aim to indirectly ablate concepts, revealing
insights into the model's resilience and adaptability. We also observe the
model's performance degradation on images generated by concepts far from its
target ablation concept, documented in the appendix.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.12457v1">Data Trade and Consumer Privacy</a></h3>
  
  <p><b>Published on:</b> 2024-06-18T10:00:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiadong Gu</p>
    <p><b>Summary:</b> This paper studies optimal mechanisms for collecting and trading data.
Consumers benefit from revealing information about their tastes to a service
provider because this improves the service. However, the information is also
valuable to a third party as it may extract more revenue from the consumer in
another market called the product market. The paper characterizes the
constrained optimal mechanism for the service provider subject to incentive
feasibility. It is shown that the service provider sometimes sells no
information or only partial information in order to preserve profits in the
service market. In a general setup, the service provision distortion and
no-price discrimination in the product market are exclusive. Moreover, a ban on
data trade may reduce social welfare because it makes it harder to price
discriminate in the product market.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.12403v1">PDSS: A Privacy-Preserving Framework for Step-by-Step Distillation of
  Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-06-18T08:48:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tao Fan, Yan Kang, Weijing Chen, Hanlin Gu, Yuanfeng Song, Lixin Fan, Kai Chen, Qiang Yang</p>
    <p><b>Summary:</b> In the context of real-world applications, leveraging large language models
(LLMs) for domain-specific tasks often faces two major challenges:
domain-specific knowledge privacy and constrained resources. To address these
issues, we propose PDSS, a privacy-preserving framework for step-by-step
distillation of LLMs. PDSS works on a server-client architecture, wherein
client transmits perturbed prompts to the server's LLM for rationale
generation. The generated rationales are then decoded by the client and used to
enrich the training of task-specific small language model(SLM) within a
multi-task learning paradigm. PDSS introduces two privacy protection
strategies: the Exponential Mechanism Strategy and the Encoder-Decoder
Strategy, balancing prompt privacy and rationale usability. Experiments
demonstrate the effectiveness of PDSS in various text generation tasks,
enabling the training of task-specific SLM with enhanced performance while
prioritizing data privacy protection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.12330v1">Security and Privacy of 6G Federated Learning-enabled Dynamic Spectrum
  Sharing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2024-06-18T06:54:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Viet Vo, Thusitha Dayaratne, Blake Haydon, Xingliang Yuan, Shangqi Lai, Sharif Abuadbba, Hajime Suzuki, Carsten Rudolph</p>
    <p><b>Summary:</b> Spectrum sharing is increasingly vital in 6G wireless communication,
facilitating dynamic access to unused spectrum holes. Recently, there has been
a significant shift towards employing machine learning (ML) techniques for
sensing spectrum holes. In this context, federated learning (FL)-enabled
spectrum sensing technology has garnered wide attention, allowing for the
construction of an aggregated ML model without disclosing the private spectrum
sensing information of wireless user devices. However, the integrity of
collaborative training and the privacy of spectrum information from local users
have remained largely unexplored. This article first examines the latest
developments in FL-enabled spectrum sharing for prospective 6G scenarios. It
then identifies practical attack vectors in 6G to illustrate potential
AI-powered security and privacy threats in these contexts. Finally, the study
outlines future directions, including practical defense challenges and
guidelines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.12238v1">PFID: Privacy First Inference Delegation Framework for LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-06-18T03:27:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haoyan Yang, Zhitao Li, Yong Zhang, Jianzong Wang, Ning Cheng, Ming Li, Jing Xiao</p>
    <p><b>Summary:</b> This paper introduces a novel privacy-preservation framework named PFID for
LLMs that addresses critical privacy concerns by localizing user data through
model sharding and singular value decomposition. When users are interacting
with LLM systems, their prompts could be subject to being exposed to
eavesdroppers within or outside LLM system providers who are interested in
collecting users' input. In this work, we proposed a framework to camouflage
user input, so as to alleviate privacy issues. Our framework proposes to place
model shards on the client and the public server, we sent compressed hidden
states instead of prompts to and from servers. Clients have held back
information that can re-privatized the hidden states so that overall system
performance is comparable to traditional LLMs services. Our framework was
designed to be communication efficient, computation can be delegated to the
local client so that the server's computation burden can be lightened. We
conduct extensive experiments on machine translation tasks to verify our
framework's performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.12103v1">Centering Policy and Practice: Research Gaps around Usable Differential
  Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-06-17T21:32:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rachel Cummings, Jayshree Sarathy</p>
    <p><b>Summary:</b> As a mathematically rigorous framework that has amassed a rich theoretical
literature, differential privacy is considered by many experts to be the gold
standard for privacy-preserving data analysis. Others argue that while
differential privacy is a clean formulation in theory, it poses significant
challenges in practice. Both perspectives are, in our view, valid and
important. To bridge the gaps between differential privacy's promises and its
real-world usability, researchers and practitioners must work together to
advance policy and practice of this technology. In this paper, we outline
pressing open questions towards building usable differential privacy and offer
recommendations for the field, such as developing risk frameworks to align with
user needs, tailoring communications for different stakeholders, modeling the
impact of privacy-loss parameters, investing in effective user interfaces, and
facilitating algorithmic and procedural audits of differential privacy systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.12003v1">P3GNN: A Privacy-Preserving Provenance Graph-Based Model for APT
  Detection in Software Defined Networking</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-17T18:14:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hedyeh Nazari, Abbas Yazdinejad, Ali Dehghantanha, Fattane Zarrinkalam, Gautam Srivastava</p>
    <p><b>Summary:</b> Software Defined Networking (SDN) has brought significant advancements in
network management and programmability. However, this evolution has also
heightened vulnerability to Advanced Persistent Threats (APTs), sophisticated
and stealthy cyberattacks that traditional detection methods often fail to
counter, especially in the face of zero-day exploits. A prevalent issue is the
inadequacy of existing strategies to detect novel threats while addressing data
privacy concerns in collaborative learning scenarios. This paper presents P3GNN
(privacy-preserving provenance graph-based graph neural network model), a novel
model that synergizes Federated Learning (FL) with Graph Convolutional Networks
(GCN) for effective APT detection in SDN environments. P3GNN utilizes
unsupervised learning to analyze operational patterns within provenance graphs,
identifying deviations indicative of security breaches. Its core feature is the
integration of FL with homomorphic encryption, which fortifies data
confidentiality and gradient integrity during collaborative learning. This
approach addresses the critical challenge of data privacy in shared learning
contexts. Key innovations of P3GNN include its ability to detect anomalies at
the node level within provenance graphs, offering a detailed view of attack
trajectories and enhancing security analysis. Furthermore, the models
unsupervised learning capability enables it to identify zero-day attacks by
learning standard operational patterns. Empirical evaluation using the DARPA
TCE3 dataset demonstrates P3GNNs exceptional performance, achieving an accuracy
of 0.93 and a low false positive rate of 0.06.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.11323v2">Transparency, Privacy, and Fairness in Recommender Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2024-06-17T08:37:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dominik Kowald</p>
    <p><b>Summary:</b> Recommender systems have become a pervasive part of our daily online
experience, and are one of the most widely used applications of artificial
intelligence and machine learning. Therefore, regulations and requirements for
trustworthy artificial intelligence, for example, the European AI Act, which
includes notions such as transparency, privacy, and fairness are also highly
relevant for the design of recommender systems in practice. This habilitation
elaborates on aspects related to these three notions in the light of
recommender systems, namely: (i) transparency and cognitive models, (ii)
privacy and limited preference information, and (iii) fairness and popularity
bias in recommender systems. Specifically, with respect to aspect (i), we
highlight the usefulness of incorporating psychological theories for a
transparent design process of recommender systems. We term this type of systems
psychology-informed recommender systems. In aspect (ii), we study and address
the trade-off between accuracy and privacy in differentially-private
recommendations. We design a novel recommendation approach for collaborative
filtering based on an efficient neighborhood reuse concept, which reduces the
number of users that need to be protected with differential privacy.
Furthermore, we address the related issue of limited availability of user
preference information, e.g., click data, in the settings of session-based and
cold-start recommendations. With respect to aspect (iii), we analyze popularity
bias in recommender systems. We find that the recommendation frequency of an
item is positively correlated with this item's popularity. This also leads to
the unfair treatment of users with little interest in popular content. Finally,
we study long-term fairness dynamics in algorithmic decision support in the
labor market using agent-based modeling techniques.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.11208v1">Privacy-preserving Pseudonym Schemes for Personalized 3D Avatars in
  Mobile Social Metaverses</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2024-06-17T04:58:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Cheng Su, Xiaofeng Luo, Zhenmou Liu, Jiawen Kang, Min Hao, Zehui Xiong, Zhaohui Yang, Chongwen Huang</p>
    <p><b>Summary:</b> The emergence of mobile social metaverses, a novel paradigm bridging physical
and virtual realms, has led to the widespread adoption of avatars as digital
representations for Social Metaverse Users (SMUs) within virtual spaces.
Equipped with immersive devices, SMUs leverage Edge Servers (ESs) to deploy
their avatars and engage with other SMUs in virtual spaces. To enhance
immersion, SMUs incline to opt for 3D avatars for social interactions. However,
existing 3D avatars are typically generated through scanning the real faces of
SMUs, which can raise concerns regarding information privacy and security, such
as profile identity leakages. To tackle this, we introduce a new framework for
personalized 3D avatar construction, leveraging a two-layer network model that
provides SMUs with the option to customize their personal avatars for privacy
preservation. Specifically, our approach introduces avatar pseudonyms to
jointly safeguard the profile and digital identity privacy of the generated
avatars. Then, we design a novel metric named Privacy of Personalized Avatars
(PoPA), to evaluate effectiveness of the avatar pseudonyms. To optimize
pseudonym resource, we model the pseudonym distribution process as a
Stackelberg game and employ Deep Reinforcement Learning (DRL) to learn
equilibrium strategies under incomplete information. Simulation results
validate the efficacy and feasibility of our proposed schemes for mobile social
metaverses.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.11149v1">GoldCoin: Grounding Large Language Models in Privacy Laws via Contextual
  Integrity Theory</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-17T02:27:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wei Fan, Haoran Li, Zheye Deng, Weiqi Wang, Yangqiu Song</p>
    <p><b>Summary:</b> Privacy issues arise prominently during the inappropriate transmission of
information between entities. Existing research primarily studies privacy by
exploring various privacy attacks, defenses, and evaluations within narrowly
predefined patterns, while neglecting that privacy is not an isolated,
context-free concept limited to traditionally sensitive data (e.g., social
security numbers), but intertwined with intricate social contexts that
complicate the identification and analysis of potential privacy violations. The
advent of Large Language Models (LLMs) offers unprecedented opportunities for
incorporating the nuanced scenarios outlined in privacy laws to tackle these
complex privacy issues. However, the scarcity of open-source relevant case
studies restricts the efficiency of LLMs in aligning with specific legal
statutes. To address this challenge, we introduce a novel framework, GoldCoin,
designed to efficiently ground LLMs in privacy laws for judicial assessing
privacy violations. Our framework leverages the theory of contextual integrity
as a bridge, creating numerous synthetic scenarios grounded in relevant privacy
statutes (e.g., HIPAA), to assist LLMs in comprehending the complex contexts
for identifying privacy risks in the real world. Extensive experimental results
demonstrate that GoldCoin markedly enhances LLMs' capabilities in recognizing
privacy risks across real court cases, surpassing the baselines on different
judicial tasks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.11087v2">MemDPT: Differential Privacy for Memory Efficient Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-06-16T22:11:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yanming Liu, Xinyue Peng, Jiannan Cao, Yuwei Zhang, Chen Ma, Songhang Deng, Mengchen Fu, Xuhong Zhang, Sheng Cheng, Xun Wang, Jianwei Yin, Tianyu Du</p>
    <p><b>Summary:</b> Large language models have consistently demonstrated remarkable performance
across a wide spectrum of applications. Nonetheless, the deployment of these
models can inadvertently expose user privacy to potential risks. The
substantial memory demands of these models during training represent a
significant resource consumption challenge. The sheer size of these models
imposes a considerable burden on memory resources, which is a matter of
significant concern in practice. In this paper, we present an innovative
training framework MemDPT that not only reduces the memory cost of large
language models but also places a strong emphasis on safeguarding user data
privacy. MemDPT provides edge network and reverse network designs to
accommodate various differential privacy memory-efficient fine-tuning schemes.
Our approach not only achieves $2 \sim 3 \times$ memory optimization but also
provides robust privacy protection, ensuring that user data remains secure and
confidential. Extensive experiments have demonstrated that MemDPT can
effectively provide differential privacy efficient fine-tuning across various
task scenarios.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.10976v1">Promoting Data and Model Privacy in Federated Learning through Quantized
  LoRA</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-16T15:23:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> JianHao Zhu, Changze Lv, Xiaohua Wang, Muling Wu, Wenhao Liu, Tianlong Li, Zixuan Ling, Cenyuan Zhang, Xiaoqing Zheng, Xuanjing Huang</p>
    <p><b>Summary:</b> Conventional federated learning primarily aims to secure the privacy of data
distributed across multiple edge devices, with the global model dispatched to
edge devices for parameter updates during the learning process. However, the
development of large language models (LLMs) requires substantial data and
computational resources, rendering them valuable intellectual properties for
their developers and owners. To establish a mechanism that protects both data
and model privacy in a federated learning context, we introduce a method that
just needs to distribute a quantized version of the model's parameters during
training. This method enables accurate gradient estimations for parameter
updates while preventing clients from accessing a model whose performance is
comparable to the centrally hosted one. Moreover, we combine this quantization
strategy with LoRA, a popular and parameter-efficient fine-tuning method, to
significantly reduce communication costs in federated learning. The proposed
framework, named \textsc{FedLPP}, successfully ensures both data and model
privacy in the federated learning context. Additionally, the learned central
model exhibits good generalization and can be trained in a resource-efficient
manner.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.10884v1">Linkage on Security, Privacy and Fairness in Federated Learning: New
  Balances and New Perspectives</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-06-16T10:31:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Linlin Wang, Tianqing Zhu, Wanlei Zhou, Philip S. Yu</p>
    <p><b>Summary:</b> Federated learning is fast becoming a popular paradigm for applications
involving mobile devices, banking systems, healthcare, and IoT systems. Hence,
over the past five years, researchers have undertaken extensive studies on the
privacy leaks, security threats, and fairness associated with these emerging
models. For the most part, these three critical concepts have been studied in
isolation; however, recent research has revealed that there may be an intricate
interplay between them. For instance, some researchers have discovered that
pursuing fairness may compromise privacy, or that efforts to enhance security
can impact fairness. These emerging insights shed light on the fundamental
connections between privacy, security, and fairness within federated learning,
and, by delving deeper into these interconnections, we may be able to
significantly augment research and development across the field. Consequently,
the aim of this survey is to offer comprehensive descriptions of the privacy,
security, and fairness issues in federated learning. Moreover, we analyze the
complex relationships between these three dimensions of cyber safety and
pinpoint the fundamental elements that influence each of them. We contend that
there exists a trade-off between privacy and fairness and between security and
gradient sharing. On this basis, fairness can function as a bridge between
privacy and security to build models that are either more secure or more
private. Building upon our observations, we identify the trade-offs between
privacy and fairness and between security and fairness within the context of
federated learning. The survey then concludes with promising directions for
future research in this vanguard field.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.10803v1">HiddenTables & PyQTax: A Cooperative Game and Dataset For TableQA to
  Ensure Scale and Data Privacy Across a Myriad of Taxonomies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2024-06-16T04:53:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> William Watson, Nicole Cho, Tucker Balch, Manuela Veloso</p>
    <p><b>Summary:</b> A myriad of different Large Language Models (LLMs) face a common challenge in
contextually analyzing table question-answering tasks. These challenges are
engendered from (1) finite context windows for large tables, (2) multi-faceted
discrepancies amongst tokenization patterns against cell boundaries, and (3)
various limitations stemming from data confidentiality in the process of using
external models such as gpt-3.5-turbo. We propose a cooperative game dubbed
"HiddenTables" as a potential resolution to this challenge. In essence,
"HiddenTables" is played between the code-generating LLM "Solver" and the
"Oracle" which evaluates the ability of the LLM agents to solve Table QA tasks.
This game is based on natural language schemas and importantly, ensures the
security of the underlying data. We provide evidential experiments on a diverse
set of tables that demonstrate an LLM's collective inability to generalize and
perform on complex queries, handle compositional dependencies, and align
natural language to programmatic commands when concrete table schemas are
provided. Unlike encoder-based models, we have pushed the boundaries of
"HiddenTables" to not be limited by the number of rows - therefore we exhibit
improved efficiency in prompt and completion tokens. Our infrastructure has
spawned a new dataset "PyQTax" that spans across 116,671 question-table-answer
triplets and provides additional fine-grained breakdowns & labels for varying
question taxonomies. Therefore, in tandem with our academic contributions
regarding LLMs' deficiency in TableQA tasks, "HiddenTables" is a tactile
manifestation of how LLMs can interact with massive datasets while ensuring
data security and minimizing generation costs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.10563v1">Privacy-Preserving Heterogeneous Federated Learning for Sensitive
  Healthcare Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-15T08:43:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yukai Xu, Jingfeng Zhang, Yujie Gu</p>
    <p><b>Summary:</b> In the realm of healthcare where decentralized facilities are prevalent,
machine learning faces two major challenges concerning the protection of data
and models. The data-level challenge concerns the data privacy leakage when
centralizing data with sensitive personal information. While the model-level
challenge arises from the heterogeneity of local models, which need to be
collaboratively trained while ensuring their confidentiality to address
intellectual property concerns. To tackle these challenges, we propose a new
framework termed Abstention-Aware Federated Voting (AAFV) that can
collaboratively and confidentially train heterogeneous local models while
simultaneously protecting the data privacy. This is achieved by integrating a
novel abstention-aware voting mechanism and a differential privacy mechanism
onto local models' predictions. In particular, the proposed abstention-aware
voting mechanism exploits a threshold-based abstention method to select
high-confidence votes from heterogeneous local models, which not only enhances
the learning utility but also protects model confidentiality. Furthermore, we
implement AAFV on two practical prediction tasks of diabetes and in-hospital
patient mortality. The experiments demonstrate the effectiveness and
confidentiality of AAFV in testing accuracy and privacy protection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.09682v1">Privacy-preserving Quantification of Non-IID Degree in Federated
  Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-14T03:08:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuping Yan, Yizhi Wang, Yingchao Yu, Yaochu Jin</p>
    <p><b>Summary:</b> Federated learning (FL) offers a privacy-preserving approach to machine
learning for multiple collaborators without sharing raw data. However, the
existence of non-independent and non-identically distributed (non-IID) datasets
across different clients presents a significant challenge to FL, leading to a
sharp drop in accuracy, reduced efficiency, and hindered implementation. To
address the non-IID problem, various methods have been proposed, including
clustering and personalized FL frameworks. Nevertheless, to date, a formal
quantitative definition of the non-IID degree between different clients'
datasets is still missing, hindering the clients from comparing and obtaining
an overview of their data distributions with other clients. For the first time,
this paper proposes a quantitative definition of the non-IID degree in the
federated environment by employing the cumulative distribution function (CDF),
called Fully Homomorphic Encryption-based Federated Cumulative Distribution
Function (FHE-FCDF). This method utilizes cryptographic primitive fully
homomorphic encryption to enable clients to estimate the non-IID degree while
ensuring privacy preservation. The experiments conducted on the CIFAR-100
non-IID dataset validate the effectiveness of our proposed method.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.09547v2">FLea: Addressing Data Scarcity and Label Skew in Federated Learning via
  Privacy-preserving Feature Augmentation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-06-13T19:28:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tong Xia, Abhirup Ghosh, Xinchi Qiu, Cecilia Mascolo</p>
    <p><b>Summary:</b> Federated Learning (FL) enables model development by leveraging data
distributed across numerous edge devices without transferring local data to a
central server. However, existing FL methods still face challenges when dealing
with scarce and label-skewed data across devices, resulting in local model
overfitting and drift, consequently hindering the performance of the global
model. In response to these challenges, we propose a pioneering framework
called FLea, incorporating the following key components: i) A global feature
buffer that stores activation-target pairs shared from multiple clients to
support local training. This design mitigates local model drift caused by the
absence of certain classes; ii) A feature augmentation approach based on local
and global activation mix-ups for local training. This strategy enlarges the
training samples, thereby reducing the risk of local overfitting; iii) An
obfuscation method to minimize the correlation between intermediate activations
and the source data, enhancing the privacy of shared features. To verify the
superiority of FLea, we conduct extensive experiments using a wide range of
data modalities, simulating different levels of local data scarcity and label
skew. The results demonstrate that FLea consistently outperforms
state-of-the-art FL counterparts (among 13 of the experimented 18 settings, the
improvement is over 5% while concurrently mitigating the privacy
vulnerabilities associated with shared features. Code is available at
https://github.com/XTxiatong/FLea.git.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.09214v1">Applying Multi-Agent Negotiation to Solve the Production Routing Problem
  With Privacy Preserving</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2024-06-13T15:15:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Luiza Pellin Biasoto, Vinicius Renan de Carvalho, Jaime Simão Sichman</p>
    <p><b>Summary:</b> This paper presents a novel approach to address the Production Routing
Problem with Privacy Preserving (PRPPP) in supply chain optimization. The
integrated optimization of production, inventory, distribution, and routing
decisions in real-world industry applications poses several challenges,
including increased complexity, discrepancies between planning and execution,
and constraints on information sharing. To mitigate these challenges, this
paper proposes the use of intelligent agent negotiation within a hybrid
Multi-Agent System (MAS) integrated with optimization algorithms. The MAS
facilitates communication and coordination among entities, encapsulates private
information, and enables negotiation. This, along with optimization algorithms,
makes it a compelling framework for establishing optimal solutions. The
approach is supported by real-world applications and synergies between MAS and
optimization methods, demonstrating its effectiveness in addressing complex
supply chain optimization problems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.09037v1">Evaluating Privacy, Security, and Trust Perceptions in Conversational
  AI: A Systematic Review</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">  
  <p><b>Published on:</b> 2024-06-13T12:20:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anna Leschanowsky, Silas Rech, Birgit Popp, Tom Bäckström</p>
    <p><b>Summary:</b> Conversational AI (CAI) systems which encompass voice- and text-based
assistants are on the rise and have been largely integrated into people's
everyday lives. Despite their widespread adoption, users voice concerns
regarding privacy, security and trust in these systems. However, the
composition of these perceptions, their impact on technology adoption and usage
and the relationship between privacy, security and trust perceptions in the CAI
context remain open research challenges. This study contributes to the field by
conducting a Systematic Literature Review and offers insights into the current
state of research on privacy, security and trust perceptions in the context of
CAI systems. The review covers application fields and user groups and sheds
light on empirical methods and tools used for assessment. Moreover, it provides
insights into the reliability and validity of privacy, security and trust
scales, as well as extensively investigating the subconstructs of each item as
well as additional concepts which are concurrently collected. We point out that
the perceptions of trust, privacy and security overlap based on the
subconstructs we identified. While the majority of studies investigate one of
these concepts, only a few studies were found exploring privacy, security and
trust perceptions jointly. Our research aims to inform on directions to develop
and use reliable scales for users' privacy, security and trust perceptions and
contribute to the development of trustworthy CAI systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.09005v1">Privacy Aware Memory Forensics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-13T11:18:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Janardhan Kalikiri, Gaurav Varshney, Jaswinder Kour, Tarandeep Singh</p>
    <p><b>Summary:</b> In recent years, insider threats and attacks have been increasing in terms of
frequency and cost to the corporate business. The utilization of end-to-end
encrypted instant messaging applications (WhatsApp, Telegram, VPN) by malicious
insiders raised data breach incidents exponentially. The Securities and
Exchange Board of India (SEBI) investigated reports on such data leak incidents
and reported about twelve companies where earnings data and financial
information were leaked using WhatsApp messages. Recent surveys indicate that
60% of data breaches are primarily caused by malicious insider threats.
Especially, in the case of the defense environment, information leaks by
insiders will jeopardize the countrys national security. Sniffing of network
and host-based activities will not work in an insider threat detection
environment due to end-to-end encryption. Memory forensics allows access to the
messages sent or received over an end-to-end encrypted environment but with a
total compromise of the users privacy. In this research, we present a novel
solution to detect data leakages by insiders in an organization. Our approach
captures the RAM of the insiders device and analyses it for sensitive
information leaks from a host system while maintaining the users privacy.
Sensitive data leaks are identified with context using a deep learning model.
The feasibility and effectiveness of the proposed idea have been demonstrated
with the help of a military use case. The proposed architecture can however be
used across various use cases with minor modifications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.08918v1">Beyond the Calibration Point: Mechanism Comparison in Differential
  Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">  
  <p><b>Published on:</b> 2024-06-13T08:30:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Georgios Kaissis, Stefan Kolek, Borja Balle, Jamie Hayes, Daniel Rueckert</p>
    <p><b>Summary:</b> In differentially private (DP) machine learning, the privacy guarantees of DP
mechanisms are often reported and compared on the basis of a single
$(\varepsilon, \delta)$-pair. This practice overlooks that DP guarantees can
vary substantially \emph{even between mechanisms sharing a given $(\varepsilon,
\delta)$}, and potentially introduces privacy vulnerabilities which can remain
undetected. This motivates the need for robust, rigorous methods for comparing
DP guarantees in such cases. Here, we introduce the $\Delta$-divergence between
mechanisms which quantifies the worst-case excess privacy vulnerability of
choosing one mechanism over another in terms of $(\varepsilon, \delta)$, $f$-DP
and in terms of a newly presented Bayesian interpretation. Moreover, as a
generalisation of the Blackwell theorem, it is endowed with strong
decision-theoretic foundations. Through application examples, we show that our
techniques can facilitate informed decision-making and reveal gaps in the
current understanding of privacy risks, as current practices in DP-SGD often
result in choosing mechanisms with high excess privacy vulnerabilities.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.07973v2">Unique Security and Privacy Threats of Large Language Model: A
  Comprehensive Survey</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-12T07:55:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shang Wang, Tianqing Zhu, Bo Liu, Ming Ding, Xu Guo, Dayong Ye, Wanlei Zhou, Philip S. Yu</p>
    <p><b>Summary:</b> With the rapid development of artificial intelligence, large language models
(LLMs) have made remarkable advancements in natural language processing. These
models are trained on vast datasets to exhibit powerful language understanding
and generation capabilities across various applications, including machine
translation, chatbots, and agents. However, LLMs have revealed a variety of
privacy and security issues throughout their life cycle, drawing significant
academic and industrial attention. Moreover, the risks faced by LLMs differ
significantly from those encountered by traditional language models. Given that
current surveys lack a clear taxonomy of unique threat models across diverse
scenarios, we emphasize the unique privacy and security threats associated with
five specific scenarios: pre-training, fine-tuning, retrieval-augmented
generation systems, deployment, and LLM-based agents. Addressing the
characteristics of each risk, this survey outlines potential threats and
countermeasures. Research on attack and defense situations can offer feasible
research directions, enabling more areas to benefit from LLMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.10280v1">Transferable Embedding Inversion Attack: Uncovering Privacy Risks in
  Text Embeddings without Model Queries</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-06-12T05:09:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yu-Hsiang Huang, Yuche Tsai, Hsiang Hsiao, Hong-Yi Lin, Shou-De Lin</p>
    <p><b>Summary:</b> This study investigates the privacy risks associated with text embeddings,
focusing on the scenario where attackers cannot access the original embedding
model. Contrary to previous research requiring direct model access, we explore
a more realistic threat model by developing a transfer attack method. This
approach uses a surrogate model to mimic the victim model's behavior, allowing
the attacker to infer sensitive information from text embeddings without direct
access. Our experiments across various embedding models and a clinical dataset
demonstrate that our transfer attack significantly outperforms traditional
methods, revealing the potential privacy vulnerabilities in embedding
technologies and emphasizing the need for enhanced security measures.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.07314v1">Rethinking the impact of noisy labels in graph classification: A utility
  and privacy perspective</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-06-11T14:44:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> De Li, Xianxian Li, Zeming Gan, Qiyu Li, Bin Qu, Jinyan Wang</p>
    <p><b>Summary:</b> Graph neural networks based on message-passing mechanisms have achieved
advanced results in graph classification tasks. However, their generalization
performance degrades when noisy labels are present in the training data. Most
existing noisy labeling approaches focus on the visual domain or graph node
classification tasks and analyze the impact of noisy labels only from a utility
perspective. Unlike existing work, in this paper, we measure the effects of
noise labels on graph classification from data privacy and model utility
perspectives. We find that noise labels degrade the model's generalization
performance and enhance the ability of membership inference attacks on graph
data privacy. To this end, we propose the robust graph neural network approach
with noisy labeled graph classification. Specifically, we first accurately
filter the noisy samples by high-confidence samples and the first feature
principal component vector of each class. Then, the robust principal component
vectors and the model output under data augmentation are utilized to achieve
noise label correction guided by dual spatial information. Finally, supervised
graph contrastive learning is introduced to enhance the embedding quality of
the model and protect the privacy of the training graph data. The utility and
privacy of the proposed method are validated by comparing twelve different
methods on eight real graph classification datasets. Compared with the
state-of-the-art methods, the RGLC method achieves at most and at least 7.8%
and 0.8% performance gain at 30% noisy labeling rate, respectively, and reduces
the accuracy of privacy attacks to below 60%.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.06990v2">Privacy-Utility Tradeoff Based on $α$-lift</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2024-06-11T06:39:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohammad Amin Zarrabian, Parastoo Sadeghi</p>
    <p><b>Summary:</b> Information density and its exponential form, known as lift, play a central
role in information privacy leakage measures. $\alpha$-lift is the power-mean
of lift, which is tunable between the worst-case measure max-lift
($\alpha=\infty$) and more relaxed versions ($\alpha<\infty$). This paper
investigates the optimization problem of the privacy-utility tradeoff (PUT)
where $\alpha$-lift and mutual information are privacy and utility measures,
respectively. Due to the nonlinear nature of $\alpha$-lift for $\alpha<\infty$,
finding the optimal solution is challenging. Therefore, we propose a heuristic
algorithm to estimate the optimal utility for each value of $\alpha$, inspired
by the optimal solution for $\alpha=\infty$ and the convexity of $\alpha$-lift
with respect to the lift, which we prove. The numerical results show the
efficacy of the algorithm and indicate the effective range of $\alpha$ and
privacy budget $\varepsilon$ with good PUT performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.06755v1">Optimal Federated Learning for Nonparametric Regression with
  Heterogeneous Distributed Differential Privacy Constraints</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">   
  <p><b>Published on:</b> 2024-06-10T19:34:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> T. Tony Cai, Abhinav Chakraborty, Lasse Vuursteen</p>
    <p><b>Summary:</b> This paper studies federated learning for nonparametric regression in the
context of distributed samples across different servers, each adhering to
distinct differential privacy constraints. The setting we consider is
heterogeneous, encompassing both varying sample sizes and differential privacy
constraints across servers. Within this framework, both global and pointwise
estimation are considered, and optimal rates of convergence over the Besov
spaces are established.
  Distributed privacy-preserving estimators are proposed and their risk
properties are investigated. Matching minimax lower bounds, up to a logarithmic
factor, are established for both global and pointwise estimation. Together,
these findings shed light on the tradeoff between statistical accuracy and
privacy preservation. In particular, we characterize the compromise not only in
terms of the privacy budget but also concerning the loss incurred by
distributing data within the privacy framework as a whole. This insight
captures the folklore wisdom that it is easier to retain privacy in larger
samples, and explores the differences between pointwise and global estimation
under distributed privacy constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.06749v1">Federated Nonparametric Hypothesis Testing with Differential Privacy
  Constraints: Optimal Rates and Adaptive Tests</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">   
  <p><b>Published on:</b> 2024-06-10T19:25:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> T. Tony Cai, Abhinav Chakraborty, Lasse Vuursteen</p>
    <p><b>Summary:</b> Federated learning has attracted significant recent attention due to its
applicability across a wide range of settings where data is collected and
analyzed across disparate locations. In this paper, we study federated
nonparametric goodness-of-fit testing in the white-noise-with-drift model under
distributed differential privacy (DP) constraints.
  We first establish matching lower and upper bounds, up to a logarithmic
factor, on the minimax separation rate. This optimal rate serves as a benchmark
for the difficulty of the testing problem, factoring in model characteristics
such as the number of observations, noise level, and regularity of the signal
class, along with the strictness of the $(\epsilon,\delta)$-DP requirement. The
results demonstrate interesting and novel phase transition phenomena.
Furthermore, the results reveal an interesting phenomenon that distributed
one-shot protocols with access to shared randomness outperform those without
access to shared randomness. We also construct a data-driven testing procedure
that possesses the ability to adapt to an unknown regularity parameter over a
large collection of function classes with minimal additional cost, all while
maintaining adherence to the same set of DP constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.06473v1">DiffAudit: Auditing Privacy Practices of Online Services for Children
  and Adolescents</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-10T17:14:53Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Olivia Figueira, Rahmadi Trimananda, Athina Markopoulou, Scott Jordan</p>
    <p><b>Summary:</b> Children's and adolescents' online data privacy are regulated by laws such as
the Children's Online Privacy Protection Act (COPPA) and the California
Consumer Privacy Act (CCPA). Online services that are directed towards general
audiences (i.e., including children, adolescents, and adults) must comply with
these laws. In this paper, first, we present DiffAudit, a platform-agnostic
privacy auditing methodology for general audience services. DiffAudit performs
differential analysis of network traffic data flows to compare data processing
practices (i) between child, adolescent, and adult users and (ii) before and
after consent is given and user age is disclosed. We also present a data type
classification method that utilizes GPT-4 and our data type ontology based on
COPPA and CCPA, allowing us to identify considerably more data types than prior
work. Second, we apply DiffAudit to a set of popular general audience mobile
and web services and observe a rich set of behaviors extracted from over 440K
outgoing requests, containing 3,968 unique data types we extracted and
classified. We reveal problematic data processing practices prior to consent
and age disclosure, lack of differentiation between age-specific data flows,
inconsistent privacy policy disclosures, and sharing of linkable data with
third parties, including advertising and tracking services.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.06186v1">A Survey on Machine Unlearning: Techniques and New Emerged Privacy Risks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-10T11:31:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hengzhu Liu, Ping Xiong, Tianqing Zhu, Philip S. Yu</p>
    <p><b>Summary:</b> The explosive growth of machine learning has made it a critical
infrastructure in the era of artificial intelligence. The extensive use of data
poses a significant threat to individual privacy. Various countries have
implemented corresponding laws, such as GDPR, to protect individuals' data
privacy and the right to be forgotten. This has made machine unlearning a
research hotspot in the field of privacy protection in recent years, with the
aim of efficiently removing the contribution and impact of individual data from
trained models. The research in academia on machine unlearning has continuously
enriched its theoretical foundation, and many methods have been proposed,
targeting different data removal requests in various application scenarios.
However, recently researchers have found potential privacy leakages of various
of machine unlearning approaches, making the privacy preservation on machine
unlearning area a critical topic. This paper provides an overview and analysis
of the existing research on machine unlearning, aiming to present the current
vulnerabilities of machine unlearning approaches. We analyze privacy risks in
various aspects, including definitions, implementation methods, and real-world
applications. Compared to existing reviews, we analyze the new challenges posed
by the latest malicious attack techniques on machine unlearning from the
perspective of privacy threats. We hope that this survey can provide an initial
but comprehensive discussion on this new emerging area.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.05858v1">Comments on "Federated Learning with Differential Privacy: Algorithms
  and Performance Analysis"</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Performance-F9C80E">
  <p><b>Published on:</b> 2024-06-09T17:03:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mahtab Talaei, Iman Izadi</p>
    <p><b>Summary:</b> In the paper by Wei et al. ("Federated Learning with Differential Privacy:
Algorithms and Performance Analysis"), the convergence performance of the
proposed differential privacy algorithm in federated learning (FL), known as
Noising before Model Aggregation FL (NbAFL), was studied. However, the
presented convergence upper bound of NbAFL (Theorem 2) is incorrect. This
comment aims to present the correct form of the convergence upper bound for
NbAFL.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.05545v1">Privacy-Preserving Optimal Parameter Selection for Collaborative
  Clustering</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-08T18:21:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maryam Ghasemian, Erman Ayday</p>
    <p><b>Summary:</b> This study investigates the optimal selection of parameters for collaborative
clustering while ensuring data privacy. We focus on key clustering algorithms
within a collaborative framework, where multiple data owners combine their
data. A semi-trusted server assists in recommending the most suitable
clustering algorithm and its parameters. Our findings indicate that the privacy
parameter ($\epsilon$) minimally impacts the server's recommendations, but an
increase in $\epsilon$ raises the risk of membership inference attacks, where
sensitive information might be inferred. To mitigate these risks, we implement
differential privacy techniques, particularly the Randomized Response
mechanism, to add noise and protect data privacy. Our approach demonstrates
that high-quality clustering can be achieved while maintaining data
confidentiality, as evidenced by metrics such as the Adjusted Rand Index and
Silhouette Score. This study contributes to privacy-aware data sharing, optimal
algorithm and parameter selection, and effective communication between data
owners and the server.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.05459v1">PriviFy: Designing Tangible Interfaces for Configuring IoT Privacy
  Preferences</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2024-06-08T12:35:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bayan Al Muhander, Omer Rana, Charith Perera</p>
    <p><b>Summary:</b> The Internet of Things (IoT) devices, such as smart speakers can collect
sensitive user data, necessitating the need for users to manage their privacy
preferences. However, configuring these preferences presents users with
multiple challenges. Existing privacy controls often lack transparency, are
hard to understand, and do not provide meaningful choices. On top of that,
users struggle to locate privacy settings due to multiple menus or confusing
labeling, which discourages them from using these controls. We introduce
PriviFy (Privacy Simplify-er), a novel and user-friendly tangible interface
that can simplify the configuration of smart devices privacy settings. PriviFy
is designed to propose an enhancement to existing hardware by integrating
additional features that improve privacy management. We envision that positive
feedback and user experiences from our study will inspire consumer product
developers and smart device manufacturers to incorporate the useful design
elements we have identified. Using fidelity prototyping, we iteratively
designed PriviFy prototype with 20 participants to include interactive features
such as knobs, buttons, lights, and notifications that allow users to configure
their data privacy preferences and receive confirmation of their choices. We
further evaluated PriviFy high-fidelity prototype with 20 more participants.
Our results show that PriviFy helps simplify the complexity of privacy
preferences configuration with a significant usability score at p < .05 (P =
0.000000017, t = -8.8639). PriviFy successfully met users privacy needs and
enabled them to regain control over their data. We conclude by recommending the
importance of designing specific privacy configuration options.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.05451v1">PrivacyCube: Data Physicalization for Enhancing Privacy Awareness in IoT</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E">
  <p><b>Published on:</b> 2024-06-08T12:20:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bayan Al Muhander, Nalin Arachchilage, Yasar Majib, Mohammed Alosaimi, Omer Rana, Charith Perera</p>
    <p><b>Summary:</b> People are increasingly bringing Internet of Things (IoT) devices into their
homes without understanding how their data is gathered, processed, and used. We
describe PrivacyCube, a novel data physicalization designed to increase privacy
awareness within smart home environments. PrivacyCube visualizes IoT data
consumption by displaying privacy-related notices. PrivacyCube aims to assist
smart home occupants to (i) understand their data privacy better and (ii) have
conversations around data management practices of IoT devices used within their
homes. Using PrivacyCube, households can learn and make informed privacy
decisions collectively. To evaluate PrivacyCube, we used multiple research
methods throughout the different stages of design. We first conducted a focus
group study in two stages with six participants to compare PrivacyCube to text
and state-of-the-art privacy policies. We then deployed PrivacyCube in a
14-day-long field study with eight households. Our results show that
PrivacyCube helps home occupants comprehend IoT privacy better with
significantly increased privacy awareness at p < .05 (p=0.00041, t= -5.57).
Participants preferred PrivacyCube over text privacy policies because it was
comprehensive and easier to use. PrivacyCube and Privacy Label, a
state-of-the-art approach, both received positive reviews from participants,
with PrivacyCube being preferred for its interactivity and ability to encourage
conversations. PrivacyCube was also considered by home occupants as a piece of
home furniture, encouraging them to socialize and discuss IoT privacy
implications using this device.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.04827v1">Black Box Differential Privacy Auditing Using Total Variation Distance</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-06-07T10:52:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Antti Koskela, Jafar Mohammadi</p>
    <p><b>Summary:</b> We present a practical method to audit the differential privacy (DP)
guarantees of a machine learning model using a small hold-out dataset that is
not exposed to the model during the training. Having a score function such as
the loss function employed during the training, our method estimates the total
variation (TV) distance between scores obtained with a subset of the training
data and the hold-out dataset. With some meta information about the underlying
DP training algorithm, these TV distance values can be converted to
$(\varepsilon,\delta)$-guarantees for any $\delta$. We show that these score
distributions asymptotically give lower bounds for the DP guarantees of the
underlying training algorithm, however, we perform a one-shot estimation for
practicality reasons. We specify conditions that lead to lower bounds for the
DP guarantees with high probability. To estimate the TV distance between the
score distributions, we use a simple density estimation method based on
histograms. We show that the TV distance gives a very close to optimally robust
estimator and has an error rate $\mathcal{O}(k^{-1/3})$, where $k$ is the total
number of samples. Numerical experiments on benchmark datasets illustrate the
effectiveness of our approach and show improvements over baseline methods for
black-box auditing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.04702v1">Marking the Pace: A Blockchain-Enhanced Privacy-Traceable Strategy for
  Federated Recommender Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-06-07T07:21:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhen Cai, Tao Tang, Shuo Yu, Yunpeng Xiao, Feng Xia</p>
    <p><b>Summary:</b> Federated recommender systems have been crucially enhanced through data
sharing and continuous model updates, attributed to the pervasive connectivity
and distributed computing capabilities of Internet of Things (IoT) devices.
Given the sensitivity of IoT data, transparent data processing in data sharing
and model updates is paramount. However, existing methods fall short in tracing
the flow of shared data and the evolution of model updates. Consequently, data
sharing is vulnerable to exploitation by malicious entities, raising
significant data privacy concerns, while excluding data sharing will result in
sub-optimal recommendations. To mitigate these concerns, we present LIBERATE, a
privacy-traceable federated recommender system. We design a blockchain-based
traceability mechanism, ensuring data privacy during data sharing and model
updates. We further enhance privacy protection by incorporating local
differential privacy in user-server communication. Extensive evaluations with
the real-world dataset corroborate LIBERATE's capabilities in ensuring data
privacy during data sharing and model update while maintaining efficiency and
performance. Results underscore blockchain-based traceability mechanism as a
promising solution for privacy-preserving in federated recommender systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.04610v1">Contrastive explainable clustering with differential privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-07T03:37:36Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dung Nguyen, Ariel Vetzler, Sarit Kraus, Anil Vullikanti</p>
    <p><b>Summary:</b> This paper presents a novel approach in Explainable AI (XAI), integrating
contrastive explanations with differential privacy in clustering methods. For
several basic clustering problems, including $k$-median and $k$-means, we give
efficient differential private contrastive explanations that achieve
essentially the same explanations as those that non-private clustering
explanations can obtain. We define contrastive explanations as the utility
difference between the original clustering utility and utility from clustering
with a specifically fixed centroid. In each contrastive scenario, we designate
a specific data point as the fixed centroid position, enabling us to measure
the impact of this constraint on clustering utility under differential privacy.
Extensive experiments across various datasets show our method's effectiveness
in providing meaningful explanations without significantly compromising data
privacy or clustering utility. This underscores our contribution to
privacy-aware machine learning, demonstrating the feasibility of achieving a
balance between privacy and utility in the explanation of clustering tasks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.04535v1">Tangent differential privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-06-06T22:11:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lexing Ying</p>
    <p><b>Summary:</b> Differential privacy is a framework for protecting the identity of individual
data points in the decision-making process. In this note, we propose a new form
of differential privacy called tangent differential privacy. Compared with the
usual differential privacy that is defined uniformly across data distributions,
tangent differential privacy is tailored towards a specific data distribution
of interest. It also allows for general distribution distances such as total
variation distance and Wasserstein distance. In the case of risk minimization,
we show that entropic regularization guarantees tangent differential privacy
under rather general conditions on the risk function.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.04129v1">LenslessFace: An End-to-End Optimized Lensless System for
  Privacy-Preserving Face Verification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-06-06T14:50:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xin Cai, Hailong Zhang, Chenchen Wang, Wentao Liu, Jinwei Gu, Tianfan Xue</p>
    <p><b>Summary:</b> Lensless cameras, innovatively replacing traditional lenses for ultra-thin,
flat optics, encode light directly onto sensors, producing images that are not
immediately recognizable. This compact, lightweight, and cost-effective imaging
solution offers inherent privacy advantages, making it attractive for
privacy-sensitive applications like face verification. Typical lensless face
verification adopts a two-stage process of reconstruction followed by
verification, incurring privacy risks from reconstructed faces and high
computational costs. This paper presents an end-to-end optimization approach
for privacy-preserving face verification directly on encoded lensless captures,
ensuring that the entire software pipeline remains encoded with no visible
faces as intermediate results. To achieve this, we propose several techniques
to address unique challenges from the lensless setup which precludes
traditional face detection and alignment. Specifically, we propose a face
center alignment scheme, an augmentation curriculum to build robustness against
variations, and a knowledge distillation method to smooth optimization and
enhance performance. Evaluations under both simulation and real environment
demonstrate our method outperforms two-stage lensless verification while
enhancing privacy and efficiency. Project website:
\url{lenslessface.github.io}.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.03820v2">A Survey on Intelligent Internet of Things: Applications, Security,
  Privacy, and Future Directions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-06-06T07:55:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ons Aouedi, Thai-Hoc Vu, Alessio Sacco, Dinh C. Nguyen, Kandaraj Piamrat, Guido Marchetto, Quoc-Viet Pham</p>
    <p><b>Summary:</b> The rapid advances in the Internet of Things (IoT) have promoted a revolution
in communication technology and offered various customer services. Artificial
intelligence (AI) techniques have been exploited to facilitate IoT operations
and maximize their potential in modern application scenarios. In particular,
the convergence of IoT and AI has led to a new networking paradigm called
Intelligent IoT (IIoT), which has the potential to significantly transform
businesses and industrial domains. This paper presents a comprehensive survey
of IIoT by investigating its significant applications in mobile networks, as
well as its associated security and privacy issues. Specifically, we explore
and discuss the roles of IIoT in a wide range of key application domains, from
smart healthcare and smart cities to smart transportation and smart industries.
Through such extensive discussions, we investigate important security issues in
IIoT networks, where network attacks, confidentiality, integrity, and intrusion
are analyzed, along with a discussion of potential countermeasures. Privacy
issues in IIoT networks were also surveyed and discussed, including data,
location, and model privacy leakage. Finally, we outline several key challenges
and highlight potential research directions in this important area.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.03802v1">Continual Counting with Gradual Privacy Expiration</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2024-06-06T07:20:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Joel Daniel Andersson, Monika Henzinger, Rasmus Pagh, Teresa Anna Steiner, Jalaj Upadhyay</p>
    <p><b>Summary:</b> Differential privacy with gradual expiration models the setting where data
items arrive in a stream and at a given time $t$ the privacy loss guaranteed
for a data item seen at time $(t-d)$ is $\epsilon g(d)$, where $g$ is a
monotonically non-decreasing function. We study the fundamental
$\textit{continual (binary) counting}$ problem where each data item consists of
a bit, and the algorithm needs to output at each time step the sum of all the
bits streamed so far. For a stream of length $T$ and privacy $\textit{without}$
expiration continual counting is possible with maximum (over all time steps)
additive error $O(\log^2(T)/\varepsilon)$ and the best known lower bound is
$\Omega(\log(T)/\varepsilon)$; closing this gap is a challenging open problem.
  We show that the situation is very different for privacy with gradual
expiration by giving upper and lower bounds for a large set of expiration
functions $g$. Specifically, our algorithm achieves an additive error of $
O(\log(T)/\epsilon)$ for a large set of privacy expiration functions. We also
give a lower bound that shows that if $C$ is the additive error of any
$\epsilon$-DP algorithm for this problem, then the product of $C$ and the
privacy expiration function after $2C$ steps must be
$\Omega(\log(T)/\epsilon)$. Our algorithm matches this lower bound as its
additive error is $O(\log(T)/\epsilon)$, even when $g(2C) = O(1)$.
  Our empirical evaluation shows that we achieve a slowly growing privacy loss
with significantly smaller empirical privacy loss for large values of $d$ than
a natural baseline algorithm.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.03785v1">Count-mean Sketch as an Optimized Framework for Frequency Estimation
  with Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-06T06:55:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mingen Pan</p>
    <p><b>Summary:</b> This paper identifies that a group of state-of-the-art
locally-differentially-private (LDP) algorithms for frequency estimation are
equivalent to the private Count-Mean Sketch (CMS) algorithm with different
parameters. Therefore, we revisit the private CMS, correct errors in the
original CMS paper regarding expectation and variance, modify the CMS
implementation to eliminate existing bias, and explore optimized parameters for
CMS to achieve optimality in reducing the worst-case mean squared error (MSE),
$l_1$ loss, and $l_2$ loss. Additionally, we prove that pairwise-independent
hashing is sufficient for CMS, reducing its communication cost to the logarithm
of the cardinality of all possible values (i.e., a dictionary). As a result,
the aforementioned optimized CMS is proven theoretically and empirically to be
the only algorithm optimized for reducing the worst-case MSE, $l_1$ loss, and
$l_2$ loss when dealing with a very large dictionary. Furthermore, we
demonstrate that randomness is necessary to ensure the correctness of CMS, and
the communication cost of CMS, though low, is unavoidable despite the
randomness being public or private.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.03766v1">Privacy Preserving Semi-Decentralized Mean Estimation over
  Intermittently-Connected Networks</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">  
  <p><b>Published on:</b> 2024-06-06T06:12:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rajarshi Saha, Mohamed Seif, Michal Yemini, Andrea J. Goldsmith, H. Vincent Poor</p>
    <p><b>Summary:</b> We consider the problem of privately estimating the mean of vectors
distributed across different nodes of an unreliable wireless network, where
communications between nodes can fail intermittently. We adopt a
semi-decentralized setup, wherein to mitigate the impact of intermittently
connected links, nodes can collaborate with their neighbors to compute a local
consensus, which they relay to a central server. In such a setting, the
communications between any pair of nodes must ensure that the privacy of the
nodes is rigorously maintained to prevent unauthorized information leakage. We
study the tradeoff between collaborative relaying and privacy leakage due to
the data sharing among nodes and, subsequently, propose PriCER: Private
Collaborative Estimation via Relaying -- a differentially private collaborative
algorithm for mean estimation to optimize this tradeoff. The privacy guarantees
of PriCER arise (i) implicitly, by exploiting the inherent stochasticity of the
flaky network connections, and (ii) explicitly, by adding Gaussian
perturbations to the estimates exchanged by the nodes. Local and central
privacy guarantees are provided against eavesdroppers who can observe different
signals, such as the communications amongst nodes during local consensus and
(possibly multiple) transmissions from the relays to the central server. We
substantiate our theoretical findings with numerical simulations. Our
implementation is available at
https://github.com/rajarshisaha95/private-collaborative-relaying.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.03749v1">NAP^2: A Benchmark for Naturalness and Privacy-Preserving Text Rewriting
  by Learning from Human</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-06-06T05:07:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuo Huang, William MacLean, Xiaoxi Kang, Anqi Wu, Lizhen Qu, Qiongkai Xu, Zhuang Li, Xingliang Yuan, Gholamreza Haffari</p>
    <p><b>Summary:</b> Increasing concerns about privacy leakage issues in academia and industry
arise when employing NLP models from third-party providers to process sensitive
texts. To protect privacy before sending sensitive data to those models, we
suggest sanitizing sensitive text using two common strategies used by humans:
i) deleting sensitive expressions, and ii) obscuring sensitive details by
abstracting them. To explore the issues and develop a tool for text rewriting,
we curate the first corpus, coined NAP^2, through both crowdsourcing and the
use of large language models (LLMs). Compared to the prior works based on
differential privacy, which lead to a sharp drop in information utility and
unnatural texts, the human-inspired approaches result in more natural rewrites
and offer an improved balance between privacy protection and data utility, as
demonstrated by our extensive experiments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.03695v1">FACOS: Enabling Privacy Protection Through Fine-Grained Access Control
  with On-chain and Off-chain System</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-06T02:23:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Chao Liu, Cankun Hou, Tianyu Jiang, Jianting Ning, Hui Qiao, Yusen Wu</p>
    <p><b>Summary:</b> Data-driven landscape across finance, government, and healthcare, the
continuous generation of information demands robust solutions for secure
storage, efficient dissemination, and fine-grained access control. Blockchain
technology emerges as a significant tool, offering decentralized storage while
upholding the tenets of data security and accessibility. However, on-chain and
off-chain strategies are still confronted with issues such as untrusted
off-chain data storage, absence of data ownership, limited access control
policy for clients, and a deficiency in data privacy and auditability. To solve
these challenges, we propose a permissioned blockchain-based privacy-preserving
fine-grained access control on-chain and off-chain system, namely FACOS. We
applied three fine-grained access control solutions and comprehensively
analyzed them in different aspects, which provides an intuitive perspective for
system designers and clients to choose the appropriate access control method
for their systems. Compared to similar work that only stores encrypted data in
centralized or non-fault-tolerant IPFS systems, we enhanced off-chain data
storage security and robustness by utilizing a highly efficient and secure
asynchronous Byzantine fault tolerance (BFT) protocol in the off-chain
environment. As each of the clients needs to be verified and authorized before
accessing the data, we involved the Trusted Execution Environment (TEE)-based
solution to verify the credentials of clients. Additionally, our evaluation
results demonstrated that our system offers better scalability and practicality
than other state-of-the-art designs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.03187v1">Ariadne: a Privacy-Preserving Communication Protocol</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-05T12:20:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Antoine Fressancourt, Luigi Iannone, Mael Kerichard</p>
    <p><b>Summary:</b> In this article, we present Ariadne, a privacy-preserving communication
network layer protocol that uses a source routing approach to avoid relying on
trusted third parties. In Ariadne, a source node willing to send anonymized
network traffic to a destination uses a path consisting in nodes with which it
has pre-shared symmetric keys. Temporary keys derived from those pre-shared
keys to protect communication privacy using onion routing techniques, ensuring
session unlinkability for packets following the same path.
  Ariadne enhances previous approaches to preserve communication privacy by
introducing two novelties. First, the source route is encoded in a fixed size,
sequentially encrypted vector of routing information elements, in which the
elements' positions in the vector are pseudo-randomly permuted. Second, the
temporary keys used to process the packets on the path are referenced using
mutually known encrypted patterns. This avoids the use of an explicit key
reference that could be used to de-anonymize the communications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.02797v1">Auditing Privacy Mechanisms via Label Inference Attacks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-04T21:48:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Róbert István Busa-Fekete, Travis Dick, Claudio Gentile, Andrés Muñoz Medina, Adam Smith, Marika Swanberg</p>
    <p><b>Summary:</b> We propose reconstruction advantage measures to audit label privatization
mechanisms. A reconstruction advantage measure quantifies the increase in an
attacker's ability to infer the true label of an unlabeled example when
provided with a private version of the labels in a dataset (e.g., aggregate of
labels from different users or noisy labels output by randomized response),
compared to an attacker that only observes the feature vectors, but may have
prior knowledge of the correlation between features and labels. We consider two
such auditing measures: one additive, and one multiplicative. These incorporate
previous approaches taken in the literature on empirical auditing and
differential privacy. The measures allow us to place a variety of proposed
privatization schemes -- some differentially private, some not -- on the same
footing. We analyze these measures theoretically under a distributional model
which encapsulates reasonable adversarial settings. We also quantify their
behavior empirically on real and simulated prediction tasks. Across a range of
experimental settings, we find that differentially private schemes dominate or
match the privacy-utility tradeoff of more heuristic approaches.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.02794v1">PriME: Privacy-aware Membership profile Estimation in networks</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> 
  <p><b>Published on:</b> 2024-06-04T21:43:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abhinav Chakraborty, Sayak Chatterjee, Sagnik Nandy</p>
    <p><b>Summary:</b> This paper presents a novel approach to estimating community membership
probabilities for network vertices generated by the Degree Corrected Mixed
Membership Stochastic Block Model while preserving individual edge privacy.
Operating within the $\varepsilon$-edge local differential privacy framework,
we introduce an optimal private algorithm based on a symmetric edge flip
mechanism and spectral clustering for accurate estimation of vertex community
memberships. We conduct a comprehensive analysis of the estimation risk and
establish the optimality of our procedure by providing matching lower bounds to
the minimax risk under privacy constraints. To validate our approach, we
demonstrate its performance through numerical simulations and its practical
application to real-world data. This work represents a significant step forward
in balancing accurate community membership estimation with stringent privacy
preservation in network data analysis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.02520v1">Digital Privacy for Migrants: Exploring Current Research Trends and
  Future Prospects</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-06-04T17:41:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sarah Tabassum, Cori Faklaris</p>
    <p><b>Summary:</b> This paper explores digital privacy challenges for migrants, analyzing trends
from 2013 to 2023. Migrants face heightened risks such as government
surveillance and identity theft. Understanding these threats is vital for
raising awareness and guiding research towards effective solutions and policies
to protect migrant digital privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.02463v1">Click Without Compromise: Online Advertising Measurement via Per User
  Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-04T16:31:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yingtai Xiao, Jian Du, Shikun Zhang, Qiang Yan, Danfeng Zhang, Daniel Kifer</p>
    <p><b>Summary:</b> Online advertising is a cornerstone of the Internet ecosystem, with
advertising measurement playing a crucial role in optimizing efficiency. Ad
measurement entails attributing desired behaviors, such as purchases, to ad
exposures across various platforms, necessitating the collection of user
activities across these platforms. As this practice faces increasing
restrictions due to rising privacy concerns, safeguarding user privacy in this
context is imperative. Our work is the first to formulate the real-world
challenge of advertising measurement systems with real-time reporting of
streaming data in advertising campaigns. We introduce Ads-BPC, a novel
user-level differential privacy protection scheme for advertising measurement
results. This approach optimizes global noise power and results in a
non-identically distributed noise distribution that preserves differential
privacy while enhancing measurement accuracy. Through experiments on both
real-world advertising campaigns and synthetic datasets, Ads-BPC achieves a 25%
to 50% increase in accuracy over existing streaming DP mechanisms applied to
advertising measurement. This highlights our method's effectiveness in
achieving superior accuracy alongside a formal privacy guarantee, thereby
advancing the state-of-the-art in privacy-preserving advertising measurement.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.02424v1">Contextual Dynamic Pricing: Algorithms, Optimality, and Local
  Differential Privacy Constraints</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36">  
  <p><b>Published on:</b> 2024-06-04T15:44:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zifeng Zhao, Feiyu Jiang, Yi Yu</p>
    <p><b>Summary:</b> We study the contextual dynamic pricing problem where a firm sells products
to $T$ sequentially arriving consumers that behave according to an unknown
demand model. The firm aims to maximize its revenue, i.e. minimize its regret
over a clairvoyant that knows the model in advance. The demand model is a
generalized linear model (GLM), allowing for a stochastic feature vector in
$\mathbb R^d$ that encodes product and consumer information. We first show that
the optimal regret upper bound is of order $\sqrt{dT}$, up to a logarithmic
factor, improving upon existing upper bounds in the literature by a $\sqrt{d}$
factor. This sharper rate is materialised by two algorithms: a confidence
bound-type (supCB) algorithm and an explore-then-commit (ETC) algorithm. A key
insight of our theoretical result is an intrinsic connection between dynamic
pricing and the contextual multi-armed bandit problem with many arms based on a
careful discretization. We further study contextual dynamic pricing under the
local differential privacy (LDP) constraints. In particular, we propose a
stochastic gradient descent based ETC algorithm that achieves an optimal regret
upper bound of order $d\sqrt{T}/\epsilon$, up to a logarithmic factor, where
$\epsilon>0$ is the privacy parameter. The regret upper bounds with and without
LDP constraints are accompanied by newly constructed minimax lower bounds,
which further characterize the cost of privacy. Extensive numerical experiments
and a real data application on online lending are conducted to illustrate the
efficiency and practical value of the proposed algorithms in dynamic pricing.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.03404v1">ST-DPGAN: A Privacy-preserving Framework for Spatiotemporal Data
  Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-04T04:43:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wei Shao, Rongyi Zhu, Cai Yang, Chandra Thapa, Muhammad Ejaz Ahmed, Seyit Camtepe, Rui Zhang, DuYong Kim, Hamid Menouar, Flora D. Salim</p>
    <p><b>Summary:</b> Spatiotemporal data is prevalent in a wide range of edge devices, such as
those used in personal communication and financial transactions. Recent
advancements have sparked a growing interest in integrating spatiotemporal
analysis with large-scale language models. However, spatiotemporal data often
contains sensitive information, making it unsuitable for open third-party
access. To address this challenge, we propose a Graph-GAN-based model for
generating privacy-protected spatiotemporal data. Our approach incorporates
spatial and temporal attention blocks in the discriminator and a spatiotemporal
deconvolution structure in the generator. These enhancements enable efficient
training under Gaussian noise to achieve differential privacy. Extensive
experiments conducted on three real-world spatiotemporal datasets validate the
efficacy of our model. Our method provides a privacy guarantee while
maintaining the data utility. The prediction model trained on our generated
data maintains a competitive performance compared to the model trained on the
original data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.02629v1">SSNet: A Lightweight Multi-Party Computation Scheme for Practical
  Privacy-Preserving Machine Learning Service in the Cloud</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-06-04T00:55:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shijin Duan, Chenghong Wang, Hongwu Peng, Yukui Luo, Wujie Wen, Caiwen Ding, Xiaolin Xu</p>
    <p><b>Summary:</b> As privacy-preserving becomes a pivotal aspect of deep learning (DL)
development, multi-party computation (MPC) has gained prominence for its
efficiency and strong security. However, the practice of current MPC frameworks
is limited, especially when dealing with large neural networks, exemplified by
the prolonged execution time of 25.8 seconds for secure inference on
ResNet-152. The primary challenge lies in the reliance of current MPC
approaches on additive secret sharing, which incurs significant communication
overhead with non-linear operations such as comparisons. Furthermore, additive
sharing suffers from poor scalability on party size. In contrast, the evolving
landscape of MPC necessitates accommodating a larger number of compute parties
and ensuring robust performance against malicious activities or computational
failures.
  In light of these challenges, we propose SSNet, which for the first time,
employs Shamir's secret sharing (SSS) as the backbone of MPC-based ML
framework. We meticulously develop all framework primitives and operations for
secure DL models tailored to seamlessly integrate with the SSS scheme. SSNet
demonstrates the ability to scale up party numbers straightforwardly and embeds
strategies to authenticate the computation correctness without incurring
significant performance overhead. Additionally, SSNet introduces masking
strategies designed to reduce communication overhead associated with non-linear
operations. We conduct comprehensive experimental evaluations on commercial
cloud computing infrastructure from Amazon AWS, as well as across diverse
prevalent DNN models and datasets. SSNet demonstrates a substantial performance
boost, achieving speed-ups ranging from 3x to 14x compared to SOTA MPC
frameworks. Moreover, SSNet also represents the first framework that is
evaluated on a five-party computation setup, in the context of secure DL
inference.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.01811v1">A Game-Theoretic Approach to Privacy-Utility Tradeoff in Sharing Genomic
  Summary Statistics</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-03T22:09:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tao Zhang, Rajagopal Venkatesaramani, Rajat K. De, Bradley A. Malin, Yevgeniy Vorobeychik</p>
    <p><b>Summary:</b> The advent of online genomic data-sharing services has sought to enhance the
accessibility of large genomic datasets by allowing queries about genetic
variants, such as summary statistics, aiding care providers in distinguishing
between spurious genomic variations and those with clinical significance.
However, numerous studies have demonstrated that even sharing summary genomic
information exposes individual members of such datasets to a significant
privacy risk due to membership inference attacks. While several approaches have
emerged that reduce privacy risks by adding noise or reducing the amount of
information shared, these typically assume non-adaptive attacks that use
likelihood ratio test (LRT) statistics. We propose a Bayesian game-theoretic
framework for optimal privacy-utility tradeoff in the sharing of genomic
summary statistics. Our first contribution is to prove that a very general
Bayesian attacker model that anchors our game-theoretic approach is more
powerful than the conventional LRT-based threat models in that it induces worse
privacy loss for the defender who is modeled as a von Neumann-Morgenstern (vNM)
decision-maker. We show this to be true even when the attacker uses a
non-informative subjective prior. Next, we present an analytically tractable
approach to compare the Bayesian attacks with arbitrary subjective priors and
the Neyman-Pearson optimal LRT attacks under the Gaussian mechanism common in
differential privacy frameworks. Finally, we propose an approach for
approximating Bayes-Nash equilibria of the game using deep neural network
generators to implicitly represent player mixed strategies. Our experiments
demonstrate that the proposed game-theoretic framework yields both stronger
attacks and stronger defense strategies than the state of the art.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.01394v1">PrivacyRestore: Privacy-Preserving Inference in Large Language Models
  via Privacy Removal and Restoration</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-06-03T14:57:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ziqian Zeng, Jianwei Wang, Zhengdong Lu, Huiping Zhuang, Cen Chen</p>
    <p><b>Summary:</b> The widespread usage of online Large Language Models (LLMs) inference
services has raised significant privacy concerns about the potential exposure
of private information in user inputs to eavesdroppers or untrustworthy service
providers. Existing privacy protection methods for LLMs suffer from
insufficient privacy protection, performance degradation, or severe inference
time overhead. In this paper, we propose PrivacyRestore to protect the privacy
of user inputs during LLM inference. PrivacyRestore directly removes privacy
spans in user inputs and restores privacy information via activation steering
during inference. The privacy spans are encoded as restoration vectors. We
propose Attention-aware Weighted Aggregation (AWA) which aggregates restoration
vectors of all privacy spans in the input into a meta restoration vector. AWA
not only ensures proper representation of all privacy spans but also prevents
attackers from inferring the privacy spans from the meta restoration vector
alone. This meta restoration vector, along with the query with privacy spans
removed, is then sent to the server. The experimental results show that
PrivacyRestore can protect private information while maintaining acceptable
levels of performance and inference efficiency.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.01363v1">Privacy in LLM-based Recommendation: Recent Advances and Future
  Directions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2024-06-03T14:31:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sichun Luo, Wei Shao, Yuxuan Yao, Jian Xu, Mingyang Liu, Qintong Li, Bowei He, Maolin Wang, Guanzhi Deng, Hanxu Hou, Xinyi Zhang, Linqi Song</p>
    <p><b>Summary:</b> Nowadays, large language models (LLMs) have been integrated with conventional
recommendation models to improve recommendation performance. However, while
most of the existing works have focused on improving the model performance, the
privacy issue has only received comparatively less attention. In this paper, we
review recent advancements in privacy within LLM-based recommendation,
categorizing them into privacy attacks and protection mechanisms. Additionally,
we highlight several challenges and propose future directions for the community
to address these critical problems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.01085v1">FedAdOb: Privacy-Preserving Federated Deep Learning with Adaptive
  Obfuscation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-06-03T08:12:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hanlin Gu, Jiahuan Luo, Yan Kang, Yuan Yao, Gongxi Zhu, Bowen Li, Lixin Fan, Qiang Yang</p>
    <p><b>Summary:</b> Federated learning (FL) has emerged as a collaborative approach that allows
multiple clients to jointly learn a machine learning model without sharing
their private data. The concern about privacy leakage, albeit demonstrated
under specific conditions, has triggered numerous follow-up research in
designing powerful attacking methods and effective defending mechanisms aiming
to thwart these attacking methods. Nevertheless, privacy-preserving mechanisms
employed in these defending methods invariably lead to compromised model
performances due to a fixed obfuscation applied to private data or gradients.
In this article, we, therefore, propose a novel adaptive obfuscation mechanism,
coined FedAdOb, to protect private data without yielding original model
performances. Technically, FedAdOb utilizes passport-based adaptive obfuscation
to ensure data privacy in both horizontal and vertical federated learning
settings. The privacy-preserving capabilities of FedAdOb, specifically with
regard to private features and labels, are theoretically proven through
Theorems 1 and 2. Furthermore, extensive experimental evaluations conducted on
various datasets and network architectures demonstrate the effectiveness of
FedAdOb by manifesting its superior trade-off between privacy preservation and
model performance, surpassing existing methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.01080v1">No Vandalism: Privacy-Preserving and Byzantine-Robust Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-06-03T07:59:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhibo Xing, Zijian Zhang, Zi'ang Zhang, Jiamou Liu, Liehuang Zhu, Giovanni Russello</p>
    <p><b>Summary:</b> Federated learning allows several clients to train one machine learning model
jointly without sharing private data, providing privacy protection. However,
traditional federated learning is vulnerable to poisoning attacks, which can
not only decrease the model performance, but also implant malicious backdoors.
In addition, direct submission of local model parameters can also lead to the
privacy leakage of the training dataset. In this paper, we aim to build a
privacy-preserving and Byzantine-robust federated learning scheme to provide an
environment with no vandalism (NoV) against attacks from malicious
participants. Specifically, we construct a model filter for poisoned local
models, protecting the global model from data and model poisoning attacks. This
model filter combines zero-knowledge proofs to provide further privacy
protection. Then, we adopt secret sharing to provide verifiable secure
aggregation, removing malicious clients that disrupting the aggregation
process. Our formal analysis proves that NoV can protect data privacy and weed
out Byzantine attackers. Our experiments illustrate that NoV can effectively
address data and model poisoning attacks, including PGD, and outperforms other
related schemes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.00966v1">Guaranteeing Data Privacy in Federated Unlearning with Dynamic User
  Participation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-03T03:39:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ziyao Liu, Yu Jiang, Weifeng Jiang, Jiale Guo, Jun Zhao, Kwok-Yan Lam</p>
    <p><b>Summary:</b> Federated Unlearning (FU) is gaining prominence for its capacity to eliminate
influences of Federated Learning (FL) users' data from trained global FL
models. A straightforward FU method involves removing the unlearned users and
subsequently retraining a new global FL model from scratch with all remaining
users, a process that leads to considerable overhead. To enhance unlearning
efficiency, a widely adopted strategy employs clustering, dividing FL users
into clusters, with each cluster maintaining its own FL model. The final
inference is then determined by aggregating the majority vote from the
inferences of these sub-models. This method confines unlearning processes to
individual clusters for removing a user, thereby enhancing unlearning
efficiency by eliminating the need for participation from all remaining users.
However, current clustering-based FU schemes mainly concentrate on refining
clustering to boost unlearning efficiency but overlook the potential
information leakage from FL users' gradients, a privacy concern that has been
extensively studied. Typically, integrating secure aggregation (SecAgg) schemes
within each cluster can facilitate a privacy-preserving FU. Nevertheless,
crafting a clustering methodology that seamlessly incorporates SecAgg schemes
is challenging, particularly in scenarios involving adversarial users and
dynamic users. In this connection, we systematically explore the integration of
SecAgg protocols within the most widely used federated unlearning scheme, which
is based on clustering, to establish a privacy-preserving FU framework, aimed
at ensuring privacy while effectively managing dynamic user participation.
Comprehensive theoretical assessments and experimental results show that our
proposed scheme achieves comparable unlearning effectiveness, alongside
offering improved privacy protection and resilience in the face of varying user
participation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.00808v1">EchoNet-Synthetic: Privacy-preserving Video Generation for Safe Medical
  Data Sharing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-06-02T17:18:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hadrien Reynaud, Qingjie Meng, Mischa Dombrowski, Arijit Ghosh, Thomas Day, Alberto Gomez, Paul Leeson, Bernhard Kainz</p>
    <p><b>Summary:</b> To make medical datasets accessible without sharing sensitive patient
information, we introduce a novel end-to-end approach for generative
de-identification of dynamic medical imaging data. Until now, generative
methods have faced constraints in terms of fidelity, spatio-temporal coherence,
and the length of generation, failing to capture the complete details of
dataset distributions. We present a model designed to produce high-fidelity,
long and complete data samples with near-real-time efficiency and explore our
approach on a challenging task: generating echocardiogram videos. We develop
our generation method based on diffusion models and introduce a protocol for
medical video dataset anonymization. As an exemplar, we present
EchoNet-Synthetic, a fully synthetic, privacy-compliant echocardiogram dataset
with paired ejection fraction labels. As part of our de-identification
protocol, we evaluate the quality of the generated dataset and propose to use
clinical downstream tasks as a measurement on top of widely used but
potentially biased image quality metrics. Experimental outcomes demonstrate
that EchoNet-Synthetic achieves comparable dataset fidelity to the actual
dataset, effectively supporting the ejection fraction regression task. Code,
weights and dataset are available at
https://github.com/HReynaud/EchoNet-Synthetic.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.02599v1">Privacy-Aware Randomized Quantization via Linear Programming</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-06-01T18:40:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhongteng Cai, Xueru Zhang, Mohammad Mahdi Khalili</p>
    <p><b>Summary:</b> Differential privacy mechanisms such as the Gaussian or Laplace mechanism
have been widely used in data analytics for preserving individual privacy.
However, they are mostly designed for continuous outputs and are unsuitable for
scenarios where discrete values are necessary. Although various quantization
mechanisms were proposed recently to generate discrete outputs under
differential privacy, the outcomes are either biased or have an inferior
accuracy-privacy trade-off. In this paper, we propose a family of quantization
mechanisms that is unbiased and differentially private. It has a high degree of
freedom and we show that some existing mechanisms can be considered as special
cases of ours. To find the optimal mechanism, we formulate a linear
optimization that can be solved efficiently using linear programming tools.
Experiments show that our proposed mechanism can attain a better
privacy-accuracy trade-off compared to baselines.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.00359v1">Location Privacy in B5G/6G: Systematization of Knowledge</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2024-06-01T08:25:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hannah B. Pasandi, Faith Parastar</p>
    <p><b>Summary:</b> As we transition into the era of B5G/6G networks, the promise of seamless,
high-speed connectivity brings unprecedented opportunities and challenges.
Among the most critical concerns is the preservation of location privacy, given
the enhanced precision and pervasive connectivity of these advanced networks.
This paper systematically reviews the state of knowledge on location privacy in
B5G/6G networks, highlighting the architectural advancements and
infrastructural complexities that contribute to increased privacy risks. The
urgency of studying these technologies is underscored by the rapid adoption of
B5G/6G and the growing sophistication of location tracking methods. We evaluate
current and emerging privacy-preserving mechanisms, exploring the implications
of sophisticated tracking methods and the challenges posed by the complex
network infrastructures. Our findings reveal the effectiveness of various
mitigation strategies and emphasize the important role of physical layer
security. Additionally, we propose innovative approaches, including
decentralized authentication systems and the potential of satellite
communications, to enhance location privacy. By addressing these challenges,
this paper provides a comprehensive perspective on preserving user privacy in
the rapidly evolving landscape of modern communication networks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.00256v1">Over-the-Air Collaborative Inference with Feature Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-06-01T01:39:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohamed Seif, Yuqi Nie, Andrea Goldsmith, Vincent Poor</p>
    <p><b>Summary:</b> Collaborative inference in next-generation networks can enhance Artificial
Intelligence (AI) applications, including autonomous driving, personal
identification, and activity classification. This method involves a three-stage
process: a) data acquisition through sensing, b) feature extraction, and c)
feature encoding for transmission. Transmission of the extracted features
entails the potential risk of exposing sensitive personal data. To address this
issue, in this work a new privacy-protecting collaborative inference mechanism
is developed. Under this mechanism, each edge device in the network protects
the privacy of extracted features before transmitting them to a central server
for inference. This mechanism aims to achieve two main objectives while
ensuring effective inference performance: 1) reducing communication overhead,
and 2) maintaining strict privacy guarantees during features transmission.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2406.00249v1">Privacy Challenges in Meta-Learning: An Investigation on Model-Agnostic
  Meta-Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-06-01T01:10:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mina Rafiei, Mohammadmahdi Maheri, Hamid R. Rabiee</p>
    <p><b>Summary:</b> Meta-learning involves multiple learners, each dedicated to specific tasks,
collaborating in a data-constrained setting. In current meta-learning methods,
task learners locally learn models from sensitive data, termed support sets.
These task learners subsequently share model-related information, such as
gradients or loss values, which is computed using another part of the data
termed query set, with a meta-learner. The meta-learner employs this
information to update its meta-knowledge. Despite the absence of explicit data
sharing, privacy concerns persist. This paper examines potential data leakage
in a prominent metalearning algorithm, specifically Model-Agnostic
Meta-Learning (MAML). In MAML, gradients are shared between the metalearner and
task-learners. The primary objective is to scrutinize the gradient and the
information it encompasses about the task dataset. Subsequently, we endeavor to
propose membership inference attacks targeting the task dataset containing
support and query sets. Finally, we explore various noise injection methods
designed to safeguard the privacy of task data and thwart potential attacks.
Experimental results demonstrate the effectiveness of these attacks on MAML and
the efficacy of proper noise injection methods in countering them.</p>
  </details>
</div>



<h2>2024-05</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2405.20914v1">RASE: Efficient Privacy-preserving Data Aggregation against Disclosure
  Attacks for IoTs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-05-31T15:21:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zuyan Wang, Jun Tao, Dika Zou</p>
    <p><b>Summary:</b> The growing popular awareness of personal privacy raises the following
quandary: what is the new paradigm for collecting and protecting the data
produced by ever-increasing sensor devices. Most previous studies on co-design
of data aggregation and privacy preservation assume that a trusted fusion
center adheres to privacy regimes. Very recent work has taken steps towards
relaxing the assumption by allowing data contributors to locally perturb their
own data. Although these solutions withhold some data content to mitigate
privacy risks, they have been shown to offer insufficient protection against
disclosure attacks. Aiming at providing a more rigorous data safeguard for the
Internet of Things (IoTs), this paper initiates the study of privacy-preserving
data aggregation. We propose a novel paradigm (called RASE), which can be
generalized into a 3-step sequential procedure, noise addition, followed by
random permutation, and then parameter estimation. Specially, we design a
differentially private randomizer, which carefully guides data contributors to
obfuscate the truth. Then, a shuffler is employed to receive the noisy data
from all data contributors. After that, it breaks the correct linkage between
senders and receivers by applying a random permutation. The estimation phase
involves using inaccurate data to calculate an approximate aggregate value.
Extensive simulations are provided to explore the privacy-utility landscape of
our RASE.</p>
  </details>
</div>

