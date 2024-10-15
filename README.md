
<h2>2024-10</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.09721v1">"I inherently just trust that it works": Investigating Mental Models of
  Open-Source Libraries for Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-10-13T04:24:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Patrick Song, Jayshree Sarathy, Michael Shoemate, Salil Vadhan</p>
    <p><b>Summary:</b> Differential privacy (DP) is a promising framework for privacy-preserving
data science, but recent studies have exposed challenges in bringing this
theoretical framework for privacy into practice. These tensions are
particularly salient in the context of open-source software libraries for DP
data analysis, which are emerging tools to help data stewards and analysts
build privacy-preserving data pipelines for their applications. While there has
been significant investment into such libraries, we need further inquiry into
the role of these libraries in promoting understanding of and trust in DP, and
in turn, the ways in which design of these open-source libraries can shed light
on the challenges of creating trustworthy data infrastructures in practice. In
this study, we use qualitative methods and mental models approaches to analyze
the differences between conceptual models used to design open-source DP
libraries and mental models of DP held by users. Through a two-stage study
design involving formative interviews with 5 developers of open-source DP
libraries and user studies with 17 data analysts, we find that DP libraries
often struggle to bridge the gaps between developer and user mental models. In
particular, we highlight the tension DP libraries face in maintaining rigorous
DP implementations and facilitating user interaction. We conclude by offering
practical recommendations for further development of DP libraries.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.09506v1">Distribution-Aware Mean Estimation under User-level Local Differential
  Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2024-10-12T11:57:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Corentin Pla, Hugo Richard, Maxime Vono</p>
    <p><b>Summary:</b> We consider the problem of mean estimation under user-level local
differential privacy, where $n$ users are contributing through their local pool
of data samples. Previous work assume that the number of data samples is the
same across users. In contrast, we consider a more general and realistic
scenario where each user $u \in [n]$ owns $m_u$ data samples drawn from some
generative distribution $\mu$; $m_u$ being unknown to the statistician but
drawn from a known distribution $M$ over $\mathbb{N}^\star$. Based on a
distribution-aware mean estimation algorithm, we establish an $M$-dependent
upper bounds on the worst-case risk over $\mu$ for the task of mean estimation.
We then derive a lower bound. The two bounds are asymptotically matching up to
logarithmic factors and reduce to known bounds when $m_u = m$ for any user $u$.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.08756v1">Privacy-Preserving Optimal State Estimation with Low Complexity via
  Cramér-Rao Lower Bound Approach</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2024-10-11T12:15:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Liping Guo, Jimin Wang, Yanlong Zhao, Ji-Feng Zhang</p>
    <p><b>Summary:</b> This paper addresses the optimal state estimation problem for dynamic systems
while preserving private information against an adversary. To dominate the
adversary's estimation accuracy about private information in the mean square
error (MSE) sense, the Cram\'er-Rao lower bound (CRLB) is employed to evaluate
privacy level. The problem is formulated as a constrained optimization, which
minimizes the MSE of the state estimate with a constraint on privacy level,
achieving a trade-off between privacy and utility. To solve the constrained
optimization problem, an explicit expression for CRLB is first provided using
the information inequality. To overcome the increasing sizes of the involved
matrices over time, a low-complexity approach is then proposed to achieve
online calculation for CRLB, significantly reducing computational complexity.
Next, the optimization problem is relaxed to a semi-definite programming
problem, and a relaxed solution is provided. Finally, a privacy-preserving
state estimation algorithm with low complexity is developed and proved to
achieve differential privacy. Two illustrative examples, including a practical
case of building occupancy, demonstrate the effectiveness of the proposed
algorithm.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.08755v1">PILLAR: an AI-Powered Privacy Threat Modeling Tool</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Multiagent Systems-662E9B">
  <p><b>Published on:</b> 2024-10-11T12:13:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Majid Mollaeefar, Andrea Bissoli, Silvio Ranise</p>
    <p><b>Summary:</b> The rapid evolution of Large Language Models (LLMs) has unlocked new
possibilities for applying artificial intelligence across a wide range of
fields, including privacy engineering. As modern applications increasingly
handle sensitive user data, safeguarding privacy has become more critical than
ever. To protect privacy effectively, potential threats need to be identified
and addressed early in the system development process. Frameworks like LINDDUN
offer structured approaches for uncovering these risks, but despite their
value, they often demand substantial manual effort, expert input, and detailed
system knowledge. This makes the process time-consuming and prone to errors.
Current privacy threat modeling methods, such as LINDDUN, typically rely on
creating and analyzing complex data flow diagrams (DFDs) and system
descriptions to pinpoint potential privacy issues. While these approaches are
thorough, they can be cumbersome, relying heavily on the precision of the data
provided by users. Moreover, they often generate a long list of threats without
clear guidance on how to prioritize them, leaving developers unsure of where to
focus their efforts. In response to these challenges, we introduce PILLAR
(Privacy risk Identification with LINDDUN and LLM Analysis Report), a new tool
that integrates LLMs with the LINDDUN framework to streamline and enhance
privacy threat modeling. PILLAR automates key parts of the LINDDUN process,
such as generating DFDs, classifying threats, and prioritizing risks. By
leveraging the capabilities of LLMs, PILLAR can take natural language
descriptions of systems and transform them into comprehensive threat models
with minimal input from users, reducing the workload on developers and privacy
experts while improving the efficiency and accuracy of the process.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.08555v1">Design of Secure, Privacy-focused, and Accessible E-Payment Applications
  for Older Adults</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-10-11T06:12:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sanchari Das</p>
    <p><b>Summary:</b> E-payments are essential for transactional convenience in today's digital
economy and are becoming increasingly important for older adults, emphasizing
the need for enhanced security, privacy, and usability. To address this, we
conducted a survey-based study with 400 older adults aged 65 and above to
evaluate a high-fidelity prototype of an e-payment mobile application, which
included features such as multi-factor authentication (MFA) and QR code-based
recipient addition. Based on our findings, we developed a tailored \b{eta}
version of the application to meet the specific needs of this demographic.
Notably, approximately 91% of participants preferred traditional
knowledge-based and single-mode authentication compared to expert-recommended
MFA. We concluded by providing recommendations aimed at developing inclusive
e-payment solutions that address the security, privacy, and usability
requirements of older adults.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.08553v1">Balancing Innovation and Privacy: Data Security Strategies in Natural
  Language Processing Applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-10-11T06:05:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shaobo Liu, Guiran Liu, Binrong Zhu, Yuanshuai Luo, Linxiao Wu, Rui Wang</p>
    <p><b>Summary:</b> This research addresses privacy protection in Natural Language Processing
(NLP) by introducing a novel algorithm based on differential privacy, aimed at
safeguarding user data in common applications such as chatbots, sentiment
analysis, and machine translation. With the widespread application of NLP
technology, the security and privacy protection of user data have become
important issues that need to be solved urgently. This paper proposes a new
privacy protection algorithm designed to effectively prevent the leakage of
user sensitive information. By introducing a differential privacy mechanism,
our model ensures the accuracy and reliability of data analysis results while
adding random noise. This method not only reduces the risk caused by data
leakage but also achieves effective processing of data while protecting user
privacy. Compared to traditional privacy methods like data anonymization and
homomorphic encryption, our approach offers significant advantages in terms of
computational efficiency and scalability while maintaining high accuracy in
data analysis. The proposed algorithm's efficacy is demonstrated through
performance metrics such as accuracy (0.89), precision (0.85), and recall
(0.88), outperforming other methods in balancing privacy and utility. As
privacy protection regulations become increasingly stringent, enterprises and
developers must take effective measures to deal with privacy risks. Our
research provides an important reference for the application of privacy
protection technology in the field of NLP, emphasizing the need to achieve a
balance between technological innovation and user privacy. In the future, with
the continuous advancement of technology, privacy protection will become a core
element of data-driven applications and promote the healthy development of the
entire industry.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.08462v1">Driving Privacy Forward: Mitigating Information Leakage within Smart
  Vehicles through Synthetic Data Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-10-11T02:28:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Krish Parikh</p>
    <p><b>Summary:</b> Smart vehicles produce large amounts of data, much of which is sensitive and
at risk of privacy breaches. As attackers increasingly exploit anonymised
metadata within these datasets to profile drivers, it's important to find
solutions that mitigate this information leakage without hindering innovation
and ongoing research. Synthetic data has emerged as a promising tool to address
these privacy concerns, as it allows for the replication of real-world data
relationships while minimising the risk of revealing sensitive information. In
this paper, we examine the use of synthetic data to tackle these challenges. We
start by proposing a comprehensive taxonomy of 14 in-vehicle sensors,
identifying potential attacks and categorising their vulnerability. We then
focus on the most vulnerable signals, using the Passive Vehicular Sensor (PVS)
dataset to generate synthetic data with a Tabular Variational Autoencoder
(TVAE) model, which included over 1 million data points. Finally, we evaluate
this against 3 core metrics: fidelity, utility, and privacy. Our results show
that we achieved 90.1% statistical similarity and 78% classification accuracy
when tested on its original intent while also preventing the profiling of the
driver. The code can be found at
https://github.com/krish-parikh/Synthetic-Data-Generation</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.08381v1">Assessing Privacy Policies with AI: Ethical, Legal, and Technical
  Challenges</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-10-10T21:36:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Irem Aydin, Hermann Diebel-Fischer, Vincent Freiberger, Julia Möller-Klapperich, Erik Buchmann, Michael Färber, Anne Lauber-Rönsberg, Birte Platow</p>
    <p><b>Summary:</b> The growing use of Machine Learning and Artificial Intelligence (AI),
particularly Large Language Models (LLMs) like OpenAI's GPT series, leads to
disruptive changes across organizations. At the same time, there is a growing
concern about how organizations handle personal data. Thus, privacy policies
are essential for transparency in data processing practices, enabling users to
assess privacy risks. However, these policies are often long and complex. This
might lead to user confusion and consent fatigue, where users accept data
practices against their interests, and abusive or unfair practices might go
unnoticed. LLMss can be used to assess privacy policies for users
automatically. In this interdisciplinary work, we explore the challenges of
this approach in three pillars, namely technical feasibility, ethical
implications, and legal compatibility of using LLMs to assess privacy policies.
Our findings aim to identify potential for future research, and to foster a
discussion on the use of LLM technologies for enabling users to fulfil their
important role as decision-makers in a constantly developing AI-driven digital
economy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.08302v1">A Framework to Audit Email Address Privacy and Analyze Email Marketing
  Practices of Online Services and Apps</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-10T18:44:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Scott Seidenberger, Oluwasijibomi Ajisegiri, Noah Pursell, Fazil Raja, Anindya Maiti</p>
    <p><b>Summary:</b> This study explores the widespread perception that personal data, such as
email addresses, may be shared or sold without informed user consent,
investigating whether these concerns are reflected in actual practices of
popular online services and apps. Over the course of a year, we collected and
analyzed the source, volume, frequency, and content of emails received by users
after signing up for the 150 most popular online services and apps across
various sectors. By examining patterns in email communications, we aim to
identify consistent strategies used across industries, including potential
signs of third-party data sharing. This analysis provides a critical evaluation
of how email marketing tactics may intersect with data-sharing practices, with
important implications for consumer privacy and regulatory oversight. Our study
findings, conducted post-CCPA and GDPR, indicate that while no third-party spam
email was detected, internal email marketing practices were pervasive, with
companies frequently sending promotional and CRM emails despite opt-out
preferences. The framework established in this work is designed to be scalable,
allowing for continuous monitoring, and can be extended to include a more
diverse set of apps and services for broader analysis, ultimately contributing
to improved user perception of data privacy practices.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.08122v1">PP-GWAS: Privacy Preserving Multi-Site Genome-wide Association Studies</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-10T17:07:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arjhun Swaminathan, Anika Hannemann, Ali Burak Ünal, Nico Pfeifer, Mete Akgün</p>
    <p><b>Summary:</b> Genome-wide association studies are pivotal in understanding the genetic
underpinnings of complex traits and diseases. Collaborative, multi-site GWAS
aim to enhance statistical power but face obstacles due to the sensitive nature
of genomic data sharing. Current state-of-the-art methods provide a
privacy-focused approach utilizing computationally expensive methods such as
Secure Multi-Party Computation and Homomorphic Encryption. In this context, we
present a novel algorithm PP-GWAS designed to improve upon existing standards
in terms of computational efficiency and scalability without sacrificing data
privacy. This algorithm employs randomized encoding within a distributed
architecture to perform stacked ridge regression on a Linear Mixed Model to
ensure rigorous analysis. Experimental evaluation with real world and synthetic
data indicates that PP-GWAS can achieve computational speeds twice as fast as
similar state-of-the-art algorithms while using lesser computational resources,
all while adhering to a robust security model that caters to an all-but-one
semi-honest adversary setting. We have assessed its performance using various
datasets, emphasizing its potential in facilitating more efficient and private
genomic analyses.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.07900v1">CL3: A Collaborative Learning Framework for the Medical Data Ensuring
  Data Privacy in the Hyperconnected Environment</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-10-10T13:29:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohamamd Zavid Parvez, Rafiqul Islam, Md Zahidul Islam</p>
    <p><b>Summary:</b> In a hyperconnected environment, medical institutions are particularly
concerned with data privacy when sharing and transmitting sensitive patient
information due to the risk of data breaches, where malicious actors could
intercept sensitive information. A collaborative learning framework, including
transfer, federated, and incremental learning, can generate efficient, secure,
and scalable models while requiring less computation, maintaining patient data
privacy, and ensuring an up-to-date model. This study aims to address the
detection of COVID-19 using chest X-ray images through a proposed collaborative
learning framework called CL3. Initially, transfer learning is employed,
leveraging knowledge from a pre-trained model as the starting global model.
Local models from different medical institutes are then integrated, and a new
global model is constructed to adapt to any data drift observed in the local
models. Additionally, incremental learning is considered, allowing continuous
adaptation to new medical data without forgetting previously learned
information. Experimental results demonstrate that the CL3 framework achieved a
global accuracy of 89.99\% when using Xception with a batch size of 16 after
being trained for six federated communication rounds.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.07772v1">Towards Quantifying The Privacy Of Redacted Text</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-10-10T10:00:27Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vaibhav Gusain, Douglas Leith</p>
    <p><b>Summary:</b> In this paper we propose use of a k-anonymity-like approach for evaluating
the privacy of redacted text. Given a piece of redacted text we use a state of
the art transformer-based deep learning network to reconstruct the original
text. This generates multiple full texts that are consistent with the redacted
text, i.e. which are grammatical, have the same non-redacted words etc, and
represents each of these using an embedding vector that captures sentence
similarity. In this way we can estimate the number, diversity and quality of
full text consistent with the redacted text and so evaluate privacy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.07632v1">Provable Privacy Attacks on Trained Shallow Neural Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-10T05:54:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guy Smorodinsky, Gal Vardi, Itay Safran</p>
    <p><b>Summary:</b> We study what provable privacy attacks can be shown on trained, 2-layer ReLU
neural networks. We explore two types of attacks; data reconstruction attacks,
and membership inference attacks. We prove that theoretical results on the
implicit bias of 2-layer neural networks can be used to provably reconstruct a
set of which at least a constant fraction are training points in a univariate
setting, and can also be used to identify with high probability whether a given
point was used in the training set in a high dimensional setting. To the best
of our knowledge, our work is the first to show provable vulnerabilities in
this setting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.07414v1">Bayes-Nash Generative Privacy Protection Against Membership Inference
  Attacks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-09T20:29:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tao Zhang, Rajagopal Venkatesaraman, Rajat K. De, Bradley A. Malin, Yevgeniy Vorobeychik</p>
    <p><b>Summary:</b> An ability to share data, even in aggregated form, is critical to advancing
both conventional and data science. However, insofar as such datasets are
comprised of individuals, their membership in these datasets is often viewed as
sensitive, with membership inference attacks (MIAs) threatening to violate
their privacy. We propose a Bayesian game model for privacy-preserving
publishing of data-sharing mechanism outputs (for example, summary statistics
for sharing genomic data). In this game, the defender minimizes a combination
of expected utility and privacy loss, with the latter being maximized by a
Bayes-rational attacker. We propose a GAN-style algorithm to approximate a
Bayes-Nash equilibrium of this game, and introduce the notions of Bayes-Nash
generative privacy (BNGP) and Bayes generative privacy (BGP) risk that aims to
optimally balance the defender's privacy and utility in a way that is robust to
the attacker's heterogeneous preferences with respect to true and false
positives. We demonstrate the properties of composition and post-processing for
BGP risk and establish conditions under which BNGP and pure differential
privacy (PDP) are equivalent. We apply our method to sharing summary
statistics, where MIAs can re-identify individuals even from aggregated data.
Theoretical analysis and empirical results demonstrate that our Bayesian
game-theoretic method outperforms state-of-the-art approaches for
privacy-preserving sharing of summary statistics.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.06814v1">Defending Membership Inference Attacks via Privacy-aware Sparsity Tuning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-10-09T12:13:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Qiang Hu, Hengxiang Zhang, Hongxin Wei</p>
    <p><b>Summary:</b> Over-parameterized models are typically vulnerable to membership inference
attacks, which aim to determine whether a specific sample is included in the
training of a given model. Previous Weight regularizations (e.g., L1
regularization) typically impose uniform penalties on all parameters, leading
to a suboptimal tradeoff between model utility and privacy. In this work, we
first show that only a small fraction of parameters substantially impact the
privacy risk. In light of this, we propose Privacy-aware Sparsity Tuning
(PAST), a simple fix to the L1 Regularization, by employing adaptive penalties
to different parameters. Our key idea behind PAST is to promote sparsity in
parameters that significantly contribute to privacy leakage. In particular, we
construct the adaptive weight for each parameter based on its privacy
sensitivity, i.e., the gradient of the loss gap with respect to the parameter.
Using PAST, the network shrinks the loss gap between members and non-members,
leading to strong resistance to privacy attacks. Extensive experiments
demonstrate the superiority of PAST, achieving a state-of-the-art balance in
the privacy-utility trade-off.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.06587v1">Bots can Snoop: Uncovering and Mitigating Privacy Risks of Bots in Group
  Chats</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-09T06:37:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kai-Hsiang Chou, Yi-Min Lin, Yi-An Wang, Jonathan Weiping Li, Tiffany Hyun-Jin Kim, Hsu-Chun Hsiao</p>
    <p><b>Summary:</b> New privacy concerns arise with chatbots on group messaging platforms.
Chatbots may access information beyond their intended functionalities, such as
messages unintended for chatbots or sender's identities. Chatbot operators may
exploit such information to infer personal information and link users across
groups, potentially leading to personal data breaches, pervasive tracking, and
targeted advertising. Our analysis of conversation datasets shows that (1)
chatbots often access far more messages than needed, and (2) when a user joins
a new group with chatbots, there is a 3.4% chance that at least one of the
chatbots can recognize and associate the user with their previous interactions
in other groups. Although state-of-the-art group messaging protocols provide
robust end-to-end security and some platforms have implemented policies to
limit chatbot access, no platforms successfully combine these features. This
paper introduces SnoopGuard, a secure group messaging protocol that ensures
user privacy against chatbots while maintaining strong end-to-end security. Our
method offers selective message access, preventing chatbots from accessing
unrelated messages, and ensures sender anonymity within the group. SnoopGuard
achieves $O(\log n + m)$ message-sending complexity for a group of $n$ users
and $m$ chatbots, compared to $O(\log(n + m))$ in state-of-the-art protocols,
with acceptable overhead for enhanced privacy. Our prototype implementation
shows that sending a message in a group of 50 users and 10 chatbots takes about
30 milliseconds when integrated with Message Layer Security (MLS).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.06266v1">Near Exact Privacy Amplification for Matrix Mechanisms</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-08T18:05:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Christopher A. Choquette-Choo, Arun Ganesh, Saminul Haque, Thomas Steinke, Abhradeep Thakurta</p>
    <p><b>Summary:</b> We study the problem of computing the privacy parameters for DP machine
learning when using privacy amplification via random batching and noise
correlated across rounds via a correlation matrix $\textbf{C}$ (i.e., the
matrix mechanism). Past work on this problem either only applied to banded
$\textbf{C}$, or gave loose privacy parameters. In this work, we give a
framework for computing near-exact privacy parameters for any lower-triangular,
non-negative $\textbf{C}$. Our framework allows us to optimize the correlation
matrix $\textbf{C}$ while accounting for amplification, whereas past work could
not. Empirically, we show this lets us achieve smaller RMSE on prefix sums than
the previous state-of-the-art (SOTA). We also show that we can improve on the
SOTA performance on deep learning tasks. Our two main technical tools are (i)
using Monte Carlo accounting to bypass composition, which was the main
technical challenge for past work, and (ii) a "balls-in-bins" batching scheme
that enables easy privacy analysis and is closer to practical random batching
than Poisson sampling.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.05930v1">Fortify Your Foundations: Practical Privacy and Security for Foundation
  Model Deployments In The Cloud</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-10-08T11:33:09Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marcin Chrapek, Anjo Vahldiek-Oberwagner, Marcin Spoczynski, Scott Constable, Mona Vij, Torsten Hoefler</p>
    <p><b>Summary:</b> Foundation Models (FMs) display exceptional performance in tasks such as
natural language processing and are being applied across a growing range of
disciplines. Although typically trained on large public datasets, FMs are often
fine-tuned or integrated into Retrieval-Augmented Generation (RAG) systems,
which rely on private data. This access, along with their size and costly
training, heightens the risk of intellectual property theft. Moreover,
multimodal FMs may expose sensitive information. In this work, we examine the
FM threat model and discuss the practicality and comprehensiveness of various
approaches for securing against them, such as ML-based methods and trusted
execution environments (TEEs). We demonstrate that TEEs offer an effective
balance between strong security properties, usability, and performance.
Specifically, we present a solution achieving less than 10\% overhead versus
bare metal for the full Llama2 7B and 13B inference pipelines running inside
\intel\ SGX and \intel\ TDX. We also share our configuration files and insights
from our implementation. To our knowledge, our work is the first to show the
practicality of TEEs for securing FMs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.05907v1">Privacy-Enhanced Over-the-Air Federated Learning via Client-Driven Power
  Balancing</a></h3>
  
  <p><b>Published on:</b> 2024-10-08T11:05:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bumjun Kim, Hyowoon Seo, Wan Choi</p>
    <p><b>Summary:</b> This paper introduces a novel privacy-enhanced over-the-air Federated
Learning (OTA-FL) framework using client-driven power balancing (CDPB) to
address privacy concerns in OTA-FL systems. In recent studies, a server
determines the power balancing based on the continuous transmission of channel
state information (CSI) from each client. Furthermore, they concentrate on
fulfilling privacy requirements in every global iteration, which can heighten
the risk of privacy exposure as the learning process extends. To mitigate these
risks, we propose two CDPB strategies -- CDPB-n (noisy) and CDPB-i (idle) --
allowing clients to adjust transmission power independently, without sharing
CSI. CDPB-n transmits noise during poor conditions, while CDPB-i pauses
transmission until conditions improve. To further enhance privacy and learning
efficiency, we show a mixed strategy, CDPB-mixed, which combines CDPB-n and
CDPB-i. Our experimental results show that CDPB outperforms traditional
approaches in terms of model accuracy and privacy guarantees, providing a
practical solution for enhancing OTA-FL in resource-constrained environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.05842v1">Privacy-aware Fully Model-Free Event-triggered Cloud-based HVAC Control</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2024-10-08T09:15:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhenan Feng, Ehsan Nekouei</p>
    <p><b>Summary:</b> Privacy is a major concern when computing-as-a-service (CaaS) platforms,
e.g., cloud-computing platforms, are utilized for building automation, as CaaS
platforms can infer sensitive information, such as occupancy, using the sensor
measurements of a building. Although the existing encrypted model-based control
algorithms can ensure the security and privacy of sensor measurements, they are
highly complex to implement and require high computational resources, which
result in a high cost of using CaaS platforms. To address these issues, in this
paper, we propose an encrypted fully model-free event-triggered cloud-based
HVAC control framework that ensures the privacy of occupancy information and
minimizes the communication and computation overhead associated with encrypted
HVAC control. To this end, we first develop a model-free controller for
regulating indoor temperature and CO2 levels. We then design a model-free
event-triggering unit which reduces the communication and computation costs of
encrypted HVAC control using an optimal triggering policy. Finally, we evaluate
the performance of the proposed encrypted fully model-free event-triggered
cloud-based HVAC control framework using the TRNSYS simulator, comparing it to
an encrypted model-based event-triggered control framework, which uses model
predictive control to regulate the indoor climate. Our numerical results
demonstrate that, compared to the encrypted model-based method, the proposed
fully model-free framework improves the control performance while reducing the
communication and computation costs. More specifically, it reduces the
communication between the system and the CaaS platform by 64% amount, and its
computation time is 75% less than that of the model-based control.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.05725v2">KnowledgeSG: Privacy-Preserving Synthetic Text Generation with Knowledge
  Distillation from Server</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-10-08T06:42:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenhao Wang, Xiaoyu Liang, Rui Ye, Jingyi Chai, Siheng Chen, Yanfeng Wang</p>
    <p><b>Summary:</b> The success of large language models (LLMs) facilitate many parties to
fine-tune LLMs on their own private data. However, this practice raises privacy
concerns due to the memorization of LLMs. Existing solutions, such as utilizing
synthetic data for substitution, struggle to simultaneously improve performance
and preserve privacy. They either rely on a local model for generation,
resulting in a performance decline, or take advantage of APIs, directly
exposing the data to API servers. To address this issue, we propose
KnowledgeSG, a novel client-server framework which enhances synthetic data
quality and improves model performance while ensuring privacy. We achieve this
by learning local knowledge from the private data with differential privacy
(DP) and distilling professional knowledge from the server. Additionally,
inspired by federated learning, we transmit models rather than data between the
client and server to prevent privacy leakage. Extensive experiments in medical
and financial domains demonstrate the effectiveness of KnowledgeSG. Our code is
now publicly available at https://github.com/wwh0411/KnowledgeSG.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.05653v1">A Blockchain-Enhanced Framework for Privacy and Data Integrity in
  Crowdsourced Drone Services</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-08T03:08:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Junaid Akram, Ali Anaissi</p>
    <p><b>Summary:</b> We present an innovative framework that integrates consumer-grade drones into
bushfire management, addressing both service improvement and data privacy
concerns under Australia's Privacy Act 1988. This system establishes a
marketplace where bushfire management authorities, as data consumers, access
critical information from drone operators, who serve as data providers. The
framework employs local differential privacy to safeguard the privacy of data
providers from all system entities, ensuring compliance with privacy standards.
Additionally, a blockchain-based solution facilitates fair data and fee
exchanges while maintaining immutable records for enhanced accountability.
Validated through a proof-of-concept implementation, the framework's
scalability and adaptability make it well-suited for large-scale, real-world
applications in bushfire management.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.05506v1">Privacy Vulnerabilities in Marginals-based Synthetic Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-10-07T21:24:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Steven Golob, Sikha Pentyala, Anuar Maratkhan, Martine De Cock</p>
    <p><b>Summary:</b> When acting as a privacy-enhancing technology, synthetic data generation
(SDG) aims to maintain a resemblance to the real data while excluding
personally-identifiable information. Many SDG algorithms provide robust
differential privacy (DP) guarantees to this end. However, we show that the
strongest class of SDG algorithms--those that preserve \textit{marginal
probabilities}, or similar statistics, from the underlying data--leak
information about individuals that can be recovered more efficiently than
previously understood. We demonstrate this by presenting a novel membership
inference attack, MAMA-MIA, and evaluate it against three seminal DP SDG
algorithms: MST, PrivBayes, and Private-GSD. MAMA-MIA leverages knowledge of
which SDG algorithm was used, allowing it to learn information about the hidden
data more accurately, and orders-of-magnitude faster, than other leading
attacks. We use MAMA-MIA to lend insight into existing SDG vulnerabilities. Our
approach went on to win the first SNAKE (SaNitization Algorithm under attacK
... $\varepsilon$) competition.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.05033v1">Extended Functional Representation Lemma: A Tool For Privacy, Semantic
  Representation, Caching, and Compression Design</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2024-10-07T13:33:23Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Amirreza Zamani, Mikael Skoglund</p>
    <p><b>Summary:</b> This paper provides an overview of a problem in information-theoretic privacy
mechanism design, addressing two scenarios in which private data is either
observable or hidden. In each scenario, different privacy measures are used,
including bounded mutual information and two types of per-letter privacy
constraints. Considering the first scenario, an agent observes useful data that
is correlated with private data, and wants to disclose the useful information
to a user. Due to the privacy concerns, direct disclosure is prohibited. Hence,
a privacy mechanism is designed to generate disclosed data which maximizes the
revealed information about the useful data while satisfying a privacy
constraint. In the second scenario, the agent has additionally access to the
private data. We discuss how the Functional Representation Lemma, the Strong
Functional Representation Lemma, and their extended versions are useful for
designing low-complexity privacy mechanisms that achieve optimal
privacy-utility trade-offs under certain constraints. Furthermore, another
privacy design problem is presented where part of the private attribute is more
private than the remaining part. Finally, we provide applications including
semantic communications, caching and delivery, and compression designs, where
the approach can be applied.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.05020v1">FRIDA: Free-Rider Detection using Privacy Attacks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-07T13:20:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pol G. Recasens, Ádám Horváth, Alberto Gutierrez-Torre, Jordi Torres, Josep Ll. Berral, Balázs Pejó</p>
    <p><b>Summary:</b> Federated learning is increasingly popular as it enables multiple parties
with limited datasets and resources to train a high-performing machine learning
model collaboratively. However, similarly to other collaborative systems,
federated learning is vulnerable to free-riders -- participants who do not
contribute to the training but still benefit from the shared model. Free-riders
not only compromise the integrity of the learning process but also slow down
the convergence of the global model, resulting in increased costs for the
honest participants.
  To address this challenge, we propose FRIDA: free-rider detection using
privacy attacks, a framework that leverages inference attacks to detect
free-riders. Unlike traditional methods that only capture the implicit effects
of free-riding, FRIDA directly infers details of the underlying training
datasets, revealing characteristics that indicate free-rider behaviour. Through
extensive experiments, we demonstrate that membership and property inference
attacks are effective for this purpose. Our evaluation shows that FRIDA
outperforms state-of-the-art methods, especially in non-IID settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.04754v1">A Comprehensive Study on GDPR-Oriented Analysis of Privacy Policies:
  Taxonomy, Corpus and GDPR Concept Classifiers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-07T05:19:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Peng Tang, Xin Li, Yuxin Chen, Weidong Qiu, Haochen Mei, Allison Holmes, Fenghua Li, Shujun Li</p>
    <p><b>Summary:</b> Machine learning based classifiers that take a privacy policy as the input
and predict relevant concepts are useful in different applications such as
(semi-)automated compliance analysis against requirements of the EU GDPR. In
all past studies, such classifiers produce a concept label per segment (e.g.,
sentence or paragraph) and their performances were evaluated by using a dataset
of labeled segments without considering the privacy policy they belong to.
However, such an approach could overestimate the performance in real-world
settings, where all segments in a new privacy policy are supposed to be unseen.
Additionally, we also observed other research gaps, including the lack of a
more complete GDPR taxonomy and the less consideration of hierarchical
information in privacy policies. To fill such research gaps, we developed a
more complete GDPR taxonomy, created the first corpus of labeled privacy
policies with hierarchical information, and conducted the most comprehensive
performance evaluation of GDPR concept classifiers for privacy policies. Our
work leads to multiple novel findings, including the confirmed
inappropriateness of splitting training and test sets at the segment level, the
benefits of considering hierarchical information, and the limitations of the
"one size fits all" approach, and the significance of testing cross-corpus
generalizability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.04606v1">Privacy's Peril: Unmasking the Unregulated Underground Market of Data
  Brokers and the Suggested Framework</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-06T19:51:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rabia Bajwa, Farah Tasnur Meem</p>
    <p><b>Summary:</b> The internet is a common place for businesses to collect and store as much
client data as possible and computer storage capacity has increased
exponentially due to this trend. Businesses utilize this data to enhance
customer satisfaction, generate revenue, boost sales, and increase profile.
However, the emerging sector of data brokers is plagued with legal challenges.
In part I, we will look at what a data broker is, how it collects information,
the data industry, and some of the difficulties it encounters. In Part II, we
will look at potential options for regulating data brokers. All options are
provided in light of the EU General Data Protection Regulation (GDPR). In Part
III, we shall present our analysis and findings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.04302v1">PANav: Toward Privacy-Aware Robot Navigation via Vision-Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Robotics-F9C80E">
  <p><b>Published on:</b> 2024-10-05T22:54:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bangguo Yu, Hamidreza Kasaei, Ming Cao</p>
    <p><b>Summary:</b> Navigating robots discreetly in human work environments while considering the
possible privacy implications of robotic tasks presents significant challenges.
Such scenarios are increasingly common, for instance, when robots transport
sensitive objects that demand high levels of privacy in spaces crowded with
human activities. While extensive research has been conducted on robotic path
planning and social awareness, current robotic systems still lack the
functionality of privacy-aware navigation in public environments. To address
this, we propose a new framework for mobile robot navigation that leverages
vision-language models to incorporate privacy awareness into adaptive path
planning. Specifically, all potential paths from the starting point to the
destination are generated using the A* algorithm. Concurrently, the
vision-language model is used to infer the optimal path for privacy-awareness,
given the environmental layout and the navigational instruction. This approach
aims to minimize the robot's exposure to human activities and preserve the
privacy of the robot and its surroundings. Experimental results on the S3DIS
dataset demonstrate that our framework significantly enhances mobile robots'
privacy awareness of navigation in human-shared public environments.
Furthermore, we demonstrate the practical applicability of our framework by
successfully navigating a robotic platform through real-world office
environments. The supplementary video and code can be accessed via the
following link: https://sites.google.com/view/privacy-aware-nav.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.03925v1">C3PA: An Open Dataset of Expert-Annotated and Regulation-Aware Privacy
  Policies to Enable Scalable Regulatory Compliance Audits</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB">
  <p><b>Published on:</b> 2024-10-04T21:04:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Maaz Bin Musa, Steven M. Winston, Garrison Allen, Jacob Schiller, Kevin Moore, Sean Quick, Johnathan Melvin, Padmini Srinivasan, Mihailis E. Diamantis, Rishab Nithyanand</p>
    <p><b>Summary:</b> The development of tools and techniques to analyze and extract organizations
data habits from privacy policies are critical for scalable regulatory
compliance audits. Unfortunately, these tools are becoming increasingly limited
in their ability to identify compliance issues and fixes. After all, most were
developed using regulation-agnostic datasets of annotated privacy policies
obtained from a time before the introduction of landmark privacy regulations
such as EUs GDPR and Californias CCPA. In this paper, we describe the first
open regulation-aware dataset of expert-annotated privacy policies, C3PA (CCPA
Privacy Policy Provision Annotations), aimed to address this challenge. C3PA
contains over 48K expert-labeled privacy policy text segments associated with
responses to CCPA-specific disclosure mandates from 411 unique organizations.
We demonstrate that the C3PA dataset is uniquely suited for aiding automated
audits of compliance with CCPA-related disclosure mandates.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.03621v1">A Global Medical Data Security and Privacy Preserving Standards
  Identification Framework for Electronic Healthcare Consumers</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-10-04T17:22:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vinaytosh Mishra, Kishu Gupta, Deepika Saxena, Ashutosh Kumar Singh</p>
    <p><b>Summary:</b> Electronic Health Records (EHR) are crucial for the success of digital
healthcare, with a focus on putting consumers at the center of this
transformation. However, the digitalization of healthcare records brings along
security and privacy risks for personal data. The major concern is that
different countries have varying standards for the security and privacy of
medical data. This paper proposed a novel and comprehensive framework to
standardize these rules globally, bringing them together on a common platform.
To support this proposal, the study reviews existing literature to understand
the research interest in this issue. It also examines six key laws and
standards related to security and privacy, identifying twenty concepts. The
proposed framework utilized K-means clustering to categorize these concepts and
identify five key factors. Finally, an Ordinal Priority Approach is applied to
determine the preferred implementation of these factors in the context of EHRs.
The proposed study provides a descriptive then prescriptive framework for the
implementation of privacy and security in the context of electronic health
records. Therefore, the findings of the proposed framework are useful for
professionals and policymakers in improving the security and privacy associated
with EHRs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.03407v1">Camel: Communication-Efficient and Maliciously Secure Federated Learning
  in the Shuffle Model of Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-04T13:13:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuangqing Xu, Yifeng Zheng, Zhongyun Hua</p>
    <p><b>Summary:</b> Federated learning (FL) has rapidly become a compelling paradigm that enables
multiple clients to jointly train a model by sharing only gradient updates for
aggregation, without revealing their local private data. In order to protect
the gradient updates which could also be privacy-sensitive, there has been a
line of work studying local differential privacy (LDP) mechanisms to provide a
formal privacy guarantee. With LDP mechanisms, clients locally perturb their
gradient updates before sharing them out for aggregation. However, such
approaches are known for greatly degrading the model utility, due to heavy
noise addition. To enable a better privacy-utility tradeoff, a recently
emerging trend is to apply the shuffle model of DP in FL, which relies on an
intermediate shuffling operation on the perturbed gradient updates to achieve
privacy amplification. Following this trend, in this paper, we present Camel, a
new communication-efficient and maliciously secure FL framework in the shuffle
model of DP. Camel first departs from existing works by ambitiously supporting
integrity check for the shuffle computation, achieving security against
malicious adversary. Specifically, Camel builds on the trending cryptographic
primitive of secret-shared shuffle, with custom techniques we develop for
optimizing system-wide communication efficiency, and for lightweight integrity
checks to harden the security of server-side computation. In addition, we also
derive a significantly tighter bound on the privacy loss through analyzing the
Renyi differential privacy (RDP) of the overall FL process. Extensive
experiments demonstrate that Camel achieves better privacy-utility trade-offs
than the state-of-the-art work, with promising performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.03069v1">Interactive GDPR-Compliant Privacy Policy Generation for Software
  Applications</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2024-10-04T01:22:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pattaraporn Sangaroonsilp, Hoa Khanh Dam, Omar Haggag, John Grundy</p>
    <p><b>Summary:</b> Software applications are designed to assist users in conducting a wide range
of tasks or interactions. They have become prevalent and play an integral part
in people's lives in this digital era. To use those software applications,
users are sometimes requested to provide their personal information. As privacy
has become a significant concern and many data protection regulations exist
worldwide, software applications must provide users with a privacy policy
detailing how their personal information is collected and processed. We propose
an approach that generates a comprehensive and compliant privacy policy with
respect to the General Data Protection Regulation (GDPR) for diverse software
applications. To support this, we first built a library of privacy clauses
based on existing privacy policy analysis. We then developed an interactive
rule-based system that prompts software developers with a series of questions
and uses their answers to generate a customised privacy policy for a given
software application. We evaluated privacy policies generated by our approach
in terms of readability, completeness and coverage and compared them to privacy
policies generated by three existing privacy policy generators and a Generative
AI-based tool. Our evaluation results show that the privacy policy generated by
our approach is the most complete and comprehensive.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.02912v1">Fine-Tuning Language Models with Differential Privacy through Adaptive
  Noise Allocation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-10-03T19:02:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xianzhi Li, Ran Zmigrod, Zhiqiang Ma, Xiaomo Liu, Xiaodan Zhu</p>
    <p><b>Summary:</b> Language models are capable of memorizing detailed patterns and information,
leading to a double-edged effect: they achieve impressive modeling performance
on downstream tasks with the stored knowledge but also raise significant
privacy concerns. Traditional differential privacy based training approaches
offer robust safeguards by employing a uniform noise distribution across all
parameters. However, this overlooks the distinct sensitivities and
contributions of individual parameters in privacy protection and often results
in suboptimal models. To address these limitations, we propose ANADP, a novel
algorithm that adaptively allocates additive noise based on the importance of
model parameters. We demonstrate that ANADP narrows the performance gap between
regular fine-tuning and traditional DP fine-tuning on a series of datasets
while maintaining the required privacy constraints.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.02547v1">Personalized Quantum Federated Learning for Privacy Image Classification</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-10-03T14:53:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jinjing Shi, Tian Chen, Shichao Zhang, Xuelong Li</p>
    <p><b>Summary:</b> Quantum federated learning has brought about the improvement of privacy image
classification, while the lack of personality of the client model may
contribute to the suboptimal of quantum federated learning. A personalized
quantum federated learning algorithm for privacy image classification is
proposed to enhance the personality of the client model in the case of an
imbalanced distribution of images. First, a personalized quantum federated
learning model is constructed, in which a personalized layer is set for the
client model to maintain the personalized parameters. Second, a personalized
quantum federated learning algorithm is introduced to secure the information
exchanged between the client and server.Third, the personalized federated
learning is applied to image classification on the FashionMNIST dataset, and
the experimental results indicate that the personalized quantum federated
learning algorithm can obtain global and local models with excellent
performance, even in situations where local training samples are imbalanced.
The server's accuracy is 100% with 8 clients and a distribution parameter of
100, outperforming the non-personalized model by 7%. The average client
accuracy is 2.9% higher than that of the non-personalized model with 2 clients
and a distribution parameter of 1. Compared to previous quantum federated
learning algorithms, the proposed personalized quantum federated learning
algorithm eliminates the need for additional local training while safeguarding
both model and data privacy.It may facilitate broader adoption and application
of quantum technologies, and pave the way for more secure, scalable, and
efficient quantum distribute machine learning solutions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.02371v1">NTU-NPU System for Voice Privacy 2024 Challenge</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-10-03T10:45:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nikita Kuzmin, Hieu-Thi Luong, Jixun Yao, Lei Xie, Kong Aik Lee, Eng Siong Chng</p>
    <p><b>Summary:</b> In this work, we describe our submissions for the Voice Privacy Challenge
2024. Rather than proposing a novel speech anonymization system, we enhance the
provided baselines to meet all required conditions and improve evaluated
metrics. Specifically, we implement emotion embedding and experiment with WavLM
and ECAPA2 speaker embedders for the B3 baseline. Additionally, we compare
different speaker and prosody anonymization techniques. Furthermore, we
introduce Mean Reversion F0 for B5, which helps to enhance privacy without a
loss in utility. Finally, we explore disentanglement models, namely $\beta$-VAE
and NaturalSpeech3 FACodec.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.02246v1">PFGuard: A Generative Framework with Privacy and Fairness Safeguards</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-10-03T06:37:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Soyeon Kim, Yuji Roh, Geon Heo, Steven Euijong Whang</p>
    <p><b>Summary:</b> Generative models must ensure both privacy and fairness for Trustworthy AI.
While these goals have been pursued separately, recent studies propose to
combine existing privacy and fairness techniques to achieve both goals.
However, naively combining these techniques can be insufficient due to
privacy-fairness conflicts, where a sample in a minority group may be amplified
for fairness, only to be suppressed for privacy. We demonstrate how these
conflicts lead to adverse effects, such as privacy violations and unexpected
fairness-utility tradeoffs. To mitigate these risks, we propose PFGuard, a
generative framework with privacy and fairness safeguards, which simultaneously
addresses privacy, fairness, and utility. By using an ensemble of multiple
teacher models, PFGuard balances privacy-fairness conflicts between fair and
private training stages and achieves high utility based on ensemble learning.
Extensive experiments show that PFGuard successfully generates synthetic data
on high-dimensional data while providing both fairness convergence and strict
DP guarantees - the first of its kind to our knowledge.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.01068v1">Convergent Privacy Loss of Noisy-SGD without Convexity and Smoothness</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-01T20:52:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Eli Chien, Pan Li</p>
    <p><b>Summary:</b> We study the Differential Privacy (DP) guarantee of hidden-state Noisy-SGD
algorithms over a bounded domain. Standard privacy analysis for Noisy-SGD
assumes all internal states are revealed, which leads to a divergent R'enyi DP
bound with respect to the number of iterations. Ye & Shokri (2022) and
Altschuler & Talwar (2022) proved convergent bounds for smooth (strongly)
convex losses, and raise open questions about whether these assumptions can be
relaxed. We provide positive answers by proving convergent R'enyi DP bound for
non-convex non-smooth losses, where we show that requiring losses to have
H\"older continuous gradient is sufficient. We also provide a strictly better
privacy bound compared to state-of-the-art results for smooth strongly convex
losses. Our analysis relies on the improvement of shifted divergence analysis
in multiple aspects, including forward Wasserstein distance tracking,
identifying the optimal shifts allocation, and the H"older reduction lemma. Our
results further elucidate the benefit of hidden-state analysis for DP and its
applicability.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.00897v1">The Gradient of Health Data Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> 
  <p><b>Published on:</b> 2024-10-01T17:35:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Baihan Lin</p>
    <p><b>Summary:</b> In the era of digital health and artificial intelligence, the management of
patient data privacy has become increasingly complex, with significant
implications for global health equity and patient trust. This paper introduces
a novel "privacy gradient" approach to health data governance, offering a more
nuanced and adaptive framework than traditional binary privacy models. Our
multidimensional concept considers factors such as data sensitivity,
stakeholder relationships, purpose of use, and temporal aspects, allowing for
context-sensitive privacy protections. Through policy analyses, ethical
considerations, and case studies spanning adolescent health, integrated care,
and genomic research, we demonstrate how this approach can address critical
privacy challenges in diverse healthcare settings worldwide. The privacy
gradient model has the potential to enhance patient engagement, improve care
coordination, and accelerate medical research while safeguarding individual
privacy rights. We provide policy recommendations for implementing this
approach, considering its impact on healthcare systems, research
infrastructures, and global health initiatives. This work aims to inform
policymakers, healthcare leaders, and digital health innovators, contributing
to a more equitable, trustworthy, and effective global health data ecosystem in
the digital age.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.00836v1">Towards Fairness and Privacy: A Novel Data Pre-processing Optimization
  Framework for Non-binary Protected Attributes</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-10-01T16:17:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Manh Khoi Duong, Stefan Conrad</p>
    <p><b>Summary:</b> The reason behind the unfair outcomes of AI is often rooted in biased
datasets. Therefore, this work presents a framework for addressing fairness by
debiasing datasets containing a (non-)binary protected attribute. The framework
proposes a combinatorial optimization problem where heuristics such as genetic
algorithms can be used to solve for the stated fairness objectives. The
framework addresses this by finding a data subset that minimizes a certain
discrimination measure. Depending on a user-defined setting, the framework
enables different use cases, such as data removal, the addition of synthetic
data, or exclusive use of synthetic data. The exclusive use of synthetic data
in particular enhances the framework's ability to preserve privacy while
optimizing for fairness. In a comprehensive evaluation, we demonstrate that
under our framework, genetic algorithms can effectively yield fairer datasets
compared to the original data. In contrast to prior work, the framework
exhibits a high degree of flexibility as it is metric- and task-agnostic, can
be applied to both binary or non-binary protected attributes, and demonstrates
efficient runtime.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.00751v1">Thinking Outside of the Differential Privacy Box: A Case Study in Text
  Privatization with Language Model Prompting</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-10-01T14:46:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stephen Meisenbacher, Florian Matthes</p>
    <p><b>Summary:</b> The field of privacy-preserving Natural Language Processing has risen in
popularity, particularly at a time when concerns about privacy grow with the
proliferation of Large Language Models. One solution consistently appearing in
recent literature has been the integration of Differential Privacy (DP) into
NLP techniques. In this paper, we take these approaches into critical view,
discussing the restrictions that DP integration imposes, as well as bring to
light the challenges that such restrictions entail. To accomplish this, we
focus on $\textbf{DP-Prompt}$, a recent method for text privatization
leveraging language models to rewrite texts. In particular, we explore this
rewriting task in multiple scenarios, both with DP and without DP. To drive the
discussion on the merits of DP in NLP, we conduct empirical utility and privacy
experiments. Our results demonstrate the need for more discussion on the
usability of DP in NLP and its benefits over non-DP approaches.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.00542v1">Differentially Private Active Learning: Balancing Effective Data
  Selection and Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-01T09:34:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kristian Schwethelm, Johannes Kaiser, Jonas Kuntzer, Mehmet Yigitsoy, Daniel Rueckert, Georgios Kaissis</p>
    <p><b>Summary:</b> Active learning (AL) is a widely used technique for optimizing data labeling
in machine learning by iteratively selecting, labeling, and training on the
most informative data. However, its integration with formal privacy-preserving
methods, particularly differential privacy (DP), remains largely underexplored.
While some works have explored differentially private AL for specialized
scenarios like online learning, the fundamental challenge of combining AL with
DP in standard learning settings has remained unaddressed, severely limiting
AL's applicability in privacy-sensitive domains. This work addresses this gap
by introducing differentially private active learning (DP-AL) for standard
learning settings. We demonstrate that naively integrating DP-SGD training into
AL presents substantial challenges in privacy budget allocation and data
utilization. To overcome these challenges, we propose step amplification, which
leverages individual sampling probabilities in batch creation to maximize data
point participation in training steps, thus optimizing data utilization.
Additionally, we investigate the effectiveness of various acquisition functions
for data selection under privacy constraints, revealing that many commonly used
functions become impractical. Our experiments on vision and natural language
processing tasks show that DP-AL can improve performance for specific datasets
and model architectures. However, our findings also highlight the limitations
of AL in privacy-constrained environments, emphasizing the trade-offs between
privacy, model accuracy, and data selection accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.00433v1">PrivTuner with Homomorphic Encryption and LoRA: A P3EFT Scheme for
  Privacy-Preserving Parameter-Efficient Fine-Tuning of AI Foundation Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-10-01T06:30:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yang Li, Wenhan Yu, Jun Zhao</p>
    <p><b>Summary:</b> AI foundation models have recently demonstrated impressive capabilities
across a wide range of tasks. Fine-tuning (FT) is a method of customizing a
pre-trained AI foundation model by further training it on a smaller, targeted
dataset. In this paper, we initiate the study of the Privacy-Preserving
Parameter-Efficient FT (P3EFT) framework, which can be viewed as the
intersection of Parameter-Efficient FT (PEFT) and Privacy-Preserving FT (PPFT).
PEFT modifies only a small subset of the model's parameters to achieve FT
(i.e., adapting a pre-trained model to a specific dataset), while PPFT uses
privacy-preserving technologies to protect the confidentiality of the model
during the FT process. There have been many studies on PEFT or PPFT but very
few on their fusion, which motivates our work on P3EFT to achieve both
parameter efficiency and model privacy. To exemplify our P3EFT, we present the
PrivTuner scheme, which incorporates Fully Homomorphic Encryption (FHE) enabled
privacy protection into LoRA (short for ``Low-Rank Adapter''). Intuitively
speaking, PrivTuner allows the model owner and the external data owners to
collaboratively implement PEFT with encrypted data. After describing PrivTuner
in detail, we further investigate its energy consumption and privacy
protection. Then, we consider a PrivTuner system over wireless communications
and formulate a joint optimization problem to adaptively minimize energy while
maximizing privacy protection, with the optimization variables including FDMA
bandwidth allocation, wireless transmission power, computational resource
allocation, and privacy protection. A resource allocation algorithm is devised
to solve the problem. Experiments demonstrate that our algorithm can
significantly reduce energy consumption while adapting to different privacy
requirements.</p>
  </details>
</div>



<h2>2024-09</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2410.00069v2">An interdisciplinary exploration of trade-offs between energy, privacy
  and accuracy aspects of data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-09-30T10:01:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pepijn de Reus, Kyra Dresen, Ana Oprescu, Kristina Irion, Ans Kolk</p>
    <p><b>Summary:</b> The digital era has raised many societal challenges, including ICT's rising
energy consumption and protecting privacy of personal data processing. This
paper considers both aspects in relation to machine learning accuracy in an
interdisciplinary exploration. We first present a method to measure the effects
of privacy-enhancing techniques on data utility and energy consumption. The
environmental-privacy-accuracy trade-offs are discovered through an
experimental set-up. We subsequently take a storytelling approach to translate
these technical findings to experts in non-ICT fields. We draft two examples
for a governmental and auditing setting to contextualise our results.
Ultimately, users face the task of optimising their data processing operations
in a trade-off between energy, privacy, and accuracy considerations where the
impact of their decisions is context-sensitive.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.19988v1">Enhancing Security Using Random Binary Weights in Privacy-Preserving
  Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-30T06:28:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hiroto Sawada, Shoko Imaizumi, Hitoshi Kiya</p>
    <p><b>Summary:</b> In this paper, we propose a novel method for enhancing security in
privacy-preserving federated learning using the Vision Transformer. In
federated learning, learning is performed by collecting updated information
without collecting raw data from each client. However, the problem is that this
raw data may be inferred from the updated information. Conventional
data-guessing countermeasures (security enhancement methods) for addressing
this issue have a trade-off relationship between privacy protection strength
and learning efficiency, and they generally degrade model performance. In this
paper, we propose a novel method of federated learning that does not degrade
model performance and that is robust against data-guessing attacks on updated
information. In the proposed method, each client independently prepares a
sequence of binary (0 or 1) random numbers, multiplies it by the updated
information, and sends it to a server for model learning. In experiments, the
effectiveness of the proposed method is confirmed in terms of model performance
and resistance to the APRIL (Attention PRIvacy Leakage) restoration attack.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.19964v1">Comments on "Privacy-Enhanced Federated Learning Against Poisoning
  Adversaries"</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-09-30T05:34:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Thomas Schneider, Ajith Suresh, Hossein Yalame</p>
    <p><b>Summary:</b> In August 2021, Liu et al. (IEEE TIFS'21) proposed a privacy-enhanced
framework named PEFL to efficiently detect poisoning behaviours in Federated
Learning (FL) using homomorphic encryption. In this article, we show that PEFL
does not preserve privacy. In particular, we illustrate that PEFL reveals the
entire gradient vector of all users in clear to one of the participating
entities, thereby violating privacy. Furthermore, we clearly show that an
immediate fix for this issue is still insufficient to achieve privacy by
pointing out multiple flaws in the proposed system.
  Note: Although our privacy issues mentioned in Section II have been published
in January 2023 (Schneider et. al., IEEE TIFS'23), several subsequent papers
continued to reference Liu et al. (IEEE TIFS'21) as a potential solution for
private federated learning. While a few works have acknowledged the privacy
concerns we raised, several of subsequent works either propagate these errors
or adopt the constructions from Liu et al. (IEEE TIFS'21), thereby
unintentionally inheriting the same privacy vulnerabilities. We believe this
oversight is partly due to the limited visibility of our comments paper at
TIFS'23 (Schneider et. al., IEEE TIFS'23). Consequently, to prevent the
continued propagation of the flawed algorithms in Liu et al. (IEEE TIFS'21)
into future research, we also put this article to an ePrint.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.19756v1">Advances in Privacy Preserving Federated Learning to Realize a Truly
  Learning Healthcare System</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-09-29T20:02:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ravi Madduri, Zilinghan Li, Tarak Nandi, Kibaek Kim, Minseok Ryu, Alex Rodriguez</p>
    <p><b>Summary:</b> The concept of a learning healthcare system (LHS) envisions a self-improving
network where multimodal data from patient care are continuously analyzed to
enhance future healthcare outcomes. However, realizing this vision faces
significant challenges in data sharing and privacy protection.
Privacy-Preserving Federated Learning (PPFL) is a transformative and promising
approach that has the potential to address these challenges by enabling
collaborative learning from decentralized data while safeguarding patient
privacy. This paper proposes a vision for integrating PPFL into the healthcare
ecosystem to achieve a truly LHS as defined by the Institute of Medicine (IOM)
Roundtable.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.19413v1">Membership Privacy Evaluation in Deep Spiking Neural Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-09-28T17:13:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiaxin Li, Gorka Abad, Stjepan Picek, Mauro Conti</p>
    <p><b>Summary:</b> Artificial Neural Networks (ANNs), commonly mimicking neurons with non-linear
functions to output floating-point numbers, consistently receive the same
signals of a data point during its forward time. Unlike ANNs, Spiking Neural
Networks (SNNs) get various input signals in the forward time of a data point
and simulate neurons in a biologically plausible way, i.e., producing a spike
(a binary value) if the accumulated membrane potential of a neuron is larger
than a threshold. Even though ANNs have achieved remarkable success in multiple
tasks, e.g., face recognition and object detection, SNNs have recently obtained
attention due to their low power consumption, fast inference, and event-driven
properties. While privacy threats against ANNs are widely explored, much less
work has been done on SNNs. For instance, it is well-known that ANNs are
vulnerable to the Membership Inference Attack (MIA), but whether the same
applies to SNNs is not explored.
  In this paper, we evaluate the membership privacy of SNNs by considering
eight MIAs, seven of which are inspired by MIAs against ANNs. Our evaluation
results show that SNNs are more vulnerable (maximum 10% higher in terms of
balanced attack accuracy) than ANNs when both are trained with neuromorphic
datasets (with time dimension). On the other hand, when training ANNs or SNNs
with static datasets (without time dimension), the vulnerability depends on the
dataset used. If we convert ANNs trained with static datasets to SNNs, the
accuracy of MIAs drops (maximum 11.5% with a reduction of 7.6% on the test
accuracy of the target model). Next, we explore the impact factors of MIAs on
SNNs by conducting a hyperparameter study. Finally, we show that the basic data
augmentation method for static data and two recent data augmentation methods
for neuromorphic data can considerably (maximum reduction of 25.7%) decrease
MIAs' performance on SNNs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.19334v1">OnePath: Efficient and Privacy-Preserving Decision Tree Inference in the
  Cloud</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-28T12:35:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuai Yuan, Hongwei Li, Xinyuan Qian, Wenbo Jiang, Guowen Xu</p>
    <p><b>Summary:</b> The expansive storage capacity and robust computational power of cloud
servers have led to the widespread outsourcing of machine learning inference
services to the cloud. While this practice offers significant operational
benefits, it also poses substantial privacy risks, including the exposure of
proprietary models and sensitive user data. In this paper, we introduce
OnePath, a framework designed for secure and efficient decision tree inference
in cloud environments. Unlike existing schemes that require traversing all
internal nodes of a decision tree, our protocol securely identifies and
processes only the nodes on the prediction path, maintaining data privacy under
ciphertext throughout the inference process. This selective traversal enhances
both security and efficiency. To further optimize privacy and performance,
OnePath employs lightweight cryptographic techniques, such as functional
encryption, during the online phase of secure inference. Notably, our protocol
allows both providers and clients to perform secure inference without the need
to remain online continuously, a critical advantage for real-world
applications. We substantiate the security of our framework with formal proofs,
demonstrating that OnePath robustly protects the privacy of decision tree
classifiers and user data. Experimental results highlight the efficiency of our
approach, with our scheme processing query data in mere microseconds on the
tested dataset. Through OnePath, we provide a practical solution that balances
the needs for security and efficiency in cloud-based decision tree inference,
making it a promising option for a variety of applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.19306v1">CausalVE: Face Video Privacy Encryption via Causal Video Prediction</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-09-28T10:34:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yubo Huang, Wenhao Feng, Xin Lai, Zixi Wang, Jingzehua Xu, Shuai Zhang, Hongjie He, Fan Chen</p>
    <p><b>Summary:</b> Advanced facial recognition technologies and recommender systems with
inadequate privacy technologies and policies for facial interactions increase
concerns about bioprivacy violations. With the proliferation of video and
live-streaming websites, public-face video distribution and interactions pose
greater privacy risks. Existing techniques typically address the risk of
sensitive biometric information leakage through various privacy enhancement
methods but pose a higher security risk by corrupting the information to be
conveyed by the interaction data, or by leaving certain biometric features
intact that allow an attacker to infer sensitive biometric information from
them. To address these shortcomings, in this paper, we propose a neural network
framework, CausalVE. We obtain cover images by adopting a diffusion model to
achieve face swapping with face guidance and use the speech sequence features
and spatiotemporal sequence features of the secret video for dynamic video
inference and prediction to obtain a cover video with the same number of frames
as the secret video. In addition, we hide the secret video by using reversible
neural networks for video hiding so that the video can also disseminate secret
data. Numerous experiments prove that our CausalVE has good security in public
video dissemination and outperforms state-of-the-art methods from a
qualitative, quantitative, and visual point of view.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.19301v1">Privacy Attack in Federated Learning is Not Easy: An Experimental Study</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-09-28T10:06:34Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Hangyu Zhu, Liyuan Huang, Zhenping Xie</p>
    <p><b>Summary:</b> Federated learning (FL) is an emerging distributed machine learning paradigm
proposed for privacy preservation. Unlike traditional centralized learning
approaches, FL enables multiple users to collaboratively train a shared global
model without disclosing their own data, thereby significantly reducing the
potential risk of privacy leakage. However, recent studies have indicated that
FL cannot entirely guarantee privacy protection, and attackers may still be
able to extract users' private data through the communicated model gradients.
Although numerous privacy attack FL algorithms have been developed, most are
designed to reconstruct private data from a single step of calculated
gradients. It remains uncertain whether these methods are effective in
realistic federated environments or if they have other limitations. In this
paper, we aim to help researchers better understand and evaluate the
effectiveness of privacy attacks on FL. We analyze and discuss recent research
papers on this topic and conduct experiments in a real FL environment to
compare the performance of various attack methods. Our experimental results
reveal that none of the existing state-of-the-art privacy attack algorithms can
effectively breach private client data in realistic FL settings, even in the
absence of defense strategies. This suggests that privacy attacks in FL are
more challenging than initially anticipated.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.19092v1">Federated Online Prediction from Experts with Differential Privacy:
  Separations and Regret Speed-ups</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-09-27T18:43:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fengyu Gao, Ruiquan Huang, Jing Yang</p>
    <p><b>Summary:</b> We study the problems of differentially private federated online prediction
from experts against both stochastic adversaries and oblivious adversaries. We
aim to minimize the average regret on $m$ clients working in parallel over time
horizon $T$ with explicit differential privacy (DP) guarantees. With stochastic
adversaries, we propose a Fed-DP-OPE-Stoch algorithm that achieves
$\sqrt{m}$-fold speed-up of the per-client regret compared to the single-player
counterparts under both pure DP and approximate DP constraints, while
maintaining logarithmic communication costs. With oblivious adversaries, we
establish non-trivial lower bounds indicating that collaboration among clients
does not lead to regret speed-up with general oblivious adversaries. We then
consider a special case of the oblivious adversaries setting, where there
exists a low-loss expert. We design a new algorithm Fed-SVT and show that it
achieves an $m$-fold regret speed-up under both pure DP and approximate DP
constraints over the single-player counterparts. Our lower bound indicates that
Fed-SVT is nearly optimal up to logarithmic factors. Experiments demonstrate
the effectiveness of our proposed algorithms. To the best of our knowledge,
this is the first work examining the differentially private online prediction
from experts in the federated setting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.19078v1">Differential privacy for protecting patient data in speech disorder
  detection using deep learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> 
  <p><b>Published on:</b> 2024-09-27T18:25:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Soroosh Tayebi Arasteh, Mahshad Lotfinia, Paula Andrea Perez-Toro, Tomas Arias-Vergara, Juan Rafael Orozco-Arroyave, Maria Schuster, Andreas Maier, Seung Hee Yang</p>
    <p><b>Summary:</b> Speech pathology has impacts on communication abilities and quality of life.
While deep learning-based models have shown potential in diagnosing these
disorders, the use of sensitive data raises critical privacy concerns. Although
differential privacy (DP) has been explored in the medical imaging domain, its
application in pathological speech analysis remains largely unexplored despite
the equally critical privacy concerns. This study is the first to investigate
DP's impact on pathological speech data, focusing on the trade-offs between
privacy, diagnostic accuracy, and fairness. Using a large, real-world dataset
of 200 hours of recordings from 2,839 German-speaking participants, we observed
a maximum accuracy reduction of 3.85% when training with DP with a privacy
budget, denoted by {\epsilon}, of 7.51. To generalize our findings, we
validated our approach on a smaller dataset of Spanish-speaking Parkinson's
disease patients, demonstrating that careful pretraining on large-scale
task-specific datasets can maintain or even improve model accuracy under DP
constraints. We also conducted a comprehensive fairness analysis, revealing
that reasonable privacy levels (2<{\epsilon}<10) do not introduce significant
gender bias, though age-related disparities may require further attention. Our
results suggest that DP can effectively balance privacy and utility in speech
disorder detection, but also highlight the unique challenges in the speech
domain, particularly regarding the privacy-fairness trade-off. This provides a
foundation for future work to refine DP methodologies and address fairness
across diverse patient groups in real-world deployments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.18907v1">In-depth Analysis of Privacy Threats in Federated Learning for Medical
  Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-09-27T16:45:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Badhan Chandra Das, M. Hadi Amini, Yanzhao Wu</p>
    <p><b>Summary:</b> Federated learning is emerging as a promising machine learning technique in
the medical field for analyzing medical images, as it is considered an
effective method to safeguard sensitive patient data and comply with privacy
regulations. However, recent studies have revealed that the default settings of
federated learning may inadvertently expose private training data to privacy
attacks. Thus, the intensity of such privacy risks and potential mitigation
strategies in the medical domain remain unclear. In this paper, we make three
original contributions to privacy risk analysis and mitigation in federated
learning for medical data. First, we propose a holistic framework, MedPFL, for
analyzing privacy risks in processing medical data in the federated learning
environment and developing effective mitigation strategies for protecting
privacy. Second, through our empirical analysis, we demonstrate the severe
privacy risks in federated learning to process medical images, where
adversaries can accurately reconstruct private medical images by performing
privacy attacks. Third, we illustrate that the prevalent defense mechanism of
adding random noises may not always be effective in protecting medical images
against privacy attacks in federated learning, which poses unique and pressing
challenges related to protecting the privacy of medical data. Furthermore, the
paper discusses several unique research questions related to the privacy
protection of medical data in the federated learning environment. We conduct
extensive experiments on several benchmark medical image datasets to analyze
and mitigate the privacy risks associated with federated learning for medical
data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.18674v1">Image-guided topic modeling for interpretable privacy classification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-09-27T12:02:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Alina Elena Baia, Andrea Cavallaro</p>
    <p><b>Summary:</b> Predicting and explaining the private information contained in an image in
human-understandable terms is a complex and contextual task. This task is
challenging even for large language models. To facilitate the understanding of
privacy decisions, we propose to predict image privacy based on a set of
natural language content descriptors. These content descriptors are associated
with privacy scores that reflect how people perceive image content. We generate
descriptors with our novel Image-guided Topic Modeling (ITM) approach. ITM
leverages, via multimodality alignment, both vision information and image
textual descriptions from a vision language model. We use the ITM-generated
descriptors to learn a privacy predictor, Priv$\times$ITM, whose decisions are
interpretable by design. Our Priv$\times$ITM classifier outperforms the
reference interpretable method by 5 percentage points in accuracy and performs
comparably to the current non-interpretable state-of-the-art model.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.18632v5">Differentially Private and Byzantine-Resilient Decentralized Nonconvex
  Optimization: System Modeling, Utility, Resilience, and Privacy Analysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E">
  <p><b>Published on:</b> 2024-09-27T10:59:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jinhui Hu, Guo Chen, Huaqing Li, Huqiang Cheng, Xiaoyu Guo, Tingwen Huang</p>
    <p><b>Summary:</b> Privacy leakage and Byzantine failures are two adverse factors to the
intelligent decision-making process of multi-agent systems (MASs). Considering
the presence of these two issues, this paper targets the resolution of a class
of nonconvex optimization problems under the Polyak-{\L}ojasiewicz (P-{\L})
condition. To address this problem, we first identify and construct the
adversary system model. To enhance the robustness of stochastic gradient
descent methods, we mask the local gradients with Gaussian noises and adopt a
resilient aggregation method self-centered clipping (SCC) to design a
differentially private (DP) decentralized Byzantine-resilient algorithm, namely
DP-SCC-PL, which simultaneously achieves differential privacy and Byzantine
resilience. The convergence analysis of DP-SCC-PL is challenging since the
convergence error can be contributed jointly by privacy-preserving and
Byzantine-resilient mechanisms, as well as the nonconvex relaxation, which is
addressed via seeking the contraction relationships among the disagreement
measure of reliable agents before and after aggregation, together with the
optimal gap. Theoretical results reveal that DP-SCC-PL achieves consensus among
all reliable agents and sublinear (inexact) convergence with well-designed
step-sizes. It has also been proved that if there are no privacy issues and
Byzantine agents, then the asymptotic exact convergence can be recovered.
Numerical experiments verify the utility, resilience, and differential privacy
of DP-SCC-PL by tackling a nonconvex optimization problem satisfying the P-{\L}
condition under various Byzantine attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.18611v1">Differentially Private Non Parametric Copulas: Generating synthetic data
  with non parametric copulas under privacy guarantees</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Databases-5BC0EB">  
  <p><b>Published on:</b> 2024-09-27T10:18:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pablo A. Osorio-Marulanda, John Esteban Castro Ramirez, Mikel Hernández Jiménez, Nicolas Moreno Reyes, Gorka Epelde Unanue</p>
    <p><b>Summary:</b> Creation of synthetic data models has represented a significant advancement
across diverse scientific fields, but this technology also brings important
privacy considerations for users. This work focuses on enhancing a
non-parametric copula-based synthetic data generation model, DPNPC, by
incorporating Differential Privacy through an Enhanced Fourier Perturbation
method. The model generates synthetic data for mixed tabular databases while
preserving privacy. We compare DPNPC with three other models (PrivBayes,
DP-Copula, and DP-Histogram) across three public datasets, evaluating privacy,
utility, and execution time. DPNPC outperforms others in modeling multivariate
dependencies, maintaining privacy for small $\epsilon$ values, and reducing
training times. However, limitations include the need to assess the model's
performance with different encoding methods and consider additional privacy
attacks. Future research should address these areas to enhance
privacy-preserving synthetic data generation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.18601v1">Privacy-Preserving Quantum Annealing for Quadratic Unconstrained Binary
  Optimization (QUBO) Problems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-09-27T10:05:08Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Moyang Xie, Yuan Zhang, Sheng Zhong, Qun Li</p>
    <p><b>Summary:</b> Quantum annealers offer a promising approach to solve Quadratic Unconstrained
Binary Optimization (QUBO) problems, which have a wide range of applications.
However, when a user submits its QUBO problem to a third-party quantum
annealer, the problem itself may disclose the user's private information to the
quantum annealing service provider. To mitigate this risk, we introduce a
privacy-preserving QUBO framework and propose a novel solution method. Our
approach employs a combination of digit-wise splitting and matrix permutation
to obfuscate the QUBO problem's model matrix $Q$, effectively concealing the
matrix elements. In addition, based on the solution to the obfuscated version
of the QUBO problem, we can reconstruct the solution to the original problem
with high accuracy. Theoretical analysis and empirical tests confirm the
efficacy and efficiency of our proposed technique, demonstrating its potential
for preserving user privacy in quantum annealing services.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.18360v1">Architecture for Protecting Data Privacy in Decentralized Social
  Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-27T00:35:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Quang Cao, Katerina Vgena, Aikaterini-Georgia Mavroeidi, Christos Kalloniatis, Xun Yi, Son Hoang Dau</p>
    <p><b>Summary:</b> Centralized social networks have experienced a transformative impact on our
digital era communication, connection, and information-sharing information.
However, it has also raised significant concerns regarding users' privacy and
individual rights. In response to these concerns, this paper proposes a novel
Decentralized Social Network employing Blockchain technology and Decentralized
Storage Networks completed by Access Control Smart Contracts. The initial phase
comprises a comprehensive literature review, delving into decentralized social
networks, explaining the review methodology, and presenting the resulting
findings. Building upon these findings and an analysis of previous research
gaps, we propose a novel architecture for decentralized social networks. In
conclusion, the principal results highlight the benefit of our decentralized
social network to protect user privacy. Moreover, the users have all rights to
their posted information following the General Data Protection Regulation
(GDPR).</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.18356v1">FedDCL: a federated data collaboration learning as a hybrid-type
  privacy-preserving framework based on federated learning and data
  collaboration</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-27T00:22:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Akira Imakura, Tetsuya Sakurai</p>
    <p><b>Summary:</b> Recently, federated learning has attracted much attention as a
privacy-preserving integrated analysis that enables integrated analysis of data
held by multiple institutions without sharing raw data. On the other hand,
federated learning requires iterative communication across institutions and has
a big challenge for implementation in situations where continuous communication
with the outside world is extremely difficult. In this study, we propose a
federated data collaboration learning (FedDCL), which solves such communication
issues by combining federated learning with recently proposed non-model
share-type federated learning named as data collaboration analysis. In the
proposed FedDCL framework, each user institution independently constructs
dimensionality-reduced intermediate representations and shares them with
neighboring institutions on intra-group DC servers. On each intra-group DC
server, intermediate representations are transformed to incorporable forms
called collaboration representations. Federated learning is then conducted
between intra-group DC servers. The proposed FedDCL framework does not require
iterative communication by user institutions and can be implemented in
situations where continuous communication with the outside world is extremely
difficult. The experimental results show that the performance of the proposed
FedDCL is comparable to that of existing federated learning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.18245v1">PDFed: Privacy-Preserving and Decentralized Asynchronous Federated
  Learning for Diffusion Models</a></h3>
  
  <p><b>Published on:</b> 2024-09-26T19:38:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kar Balan, Andrew Gilbert, John Collomosse</p>
    <p><b>Summary:</b> We present PDFed, a decentralized, aggregator-free, and asynchronous
federated learning protocol for training image diffusion models using a public
blockchain. In general, diffusion models are prone to memorization of training
data, raising privacy and ethical concerns (e.g., regurgitation of private
training data in generated images). Federated learning (FL) offers a partial
solution via collaborative model training across distributed nodes that
safeguard local data privacy. PDFed proposes a novel sample-based score that
measures the novelty and quality of generated samples, incorporating these into
a blockchain-based federated learning protocol that we show reduces private
data memorization in the collaboratively trained model. In addition, PDFed
enables asynchronous collaboration among participants with varying hardware
capabilities, facilitating broader participation. The protocol records the
provenance of AI models, improving transparency and auditability, while also
considering automated incentive and reward mechanisms for participants. PDFed
aims to empower artists and creators by protecting the privacy of creative
works and enabling decentralized, peer-to-peer collaboration. The protocol
positively impacts the creative economy by opening up novel revenue streams and
fostering innovative ways for artists to benefit from their contributions to
the AI space.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.18118v1">Slowly Scaling Per-Record Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2024-09-26T17:56:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Brian Finley, Anthony M Caruso, Justin C Doty, Ashwin Machanavajjhala, Mikaela R Meyer, David Pujol, William Sexton, Zachary Terner</p>
    <p><b>Summary:</b> We develop formal privacy mechanisms for releasing statistics from data with
many outlying values, such as income data. These mechanisms ensure that a
per-record differential privacy guarantee degrades slowly in the protected
records' influence on the statistics being released.
  Formal privacy mechanisms generally add randomness, or "noise," to published
statistics. If a noisy statistic's distribution changes little with the
addition or deletion of a single record in the underlying dataset, an attacker
looking at this statistic will find it plausible that any particular record was
present or absent, preserving the records' privacy. More influential records --
those whose addition or deletion would change the statistics' distribution more
-- typically suffer greater privacy loss. The per-record differential privacy
framework quantifies these record-specific privacy guarantees, but existing
mechanisms let these guarantees degrade rapidly (linearly or quadratically)
with influence. While this may be acceptable in cases with some moderately
influential records, it results in unacceptably high privacy losses when
records' influence varies widely, as is common in economic data.
  We develop mechanisms with privacy guarantees that instead degrade as slowly
as logarithmically with influence. These mechanisms allow for the accurate,
unbiased release of statistics, while providing meaningful protection for
highly influential records. As an example, we consider the private release of
sums of unbounded establishment data such as payroll, where our mechanisms
extend meaningful privacy protection even to very large establishments. We
evaluate these mechanisms empirically and demonstrate their utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17886v1">Upper-Body Pose-based Gaze Estimation for Privacy-Preserving 3D Gaze
  Target Detection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-09-26T14:35:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Andrea Toaiari, Vittorio Murino, Marco Cristani, Cigdem Beyan</p>
    <p><b>Summary:</b> Gaze Target Detection (GTD), i.e., determining where a person is looking
within a scene from an external viewpoint, is a challenging task, particularly
in 3D space. Existing approaches heavily rely on analyzing the person's
appearance, primarily focusing on their face to predict the gaze target. This
paper presents a novel approach to tackle this problem by utilizing the
person's upper-body pose and available depth maps to extract a 3D gaze
direction and employing a multi-stage or an end-to-end pipeline to predict the
gazed target. When predicted accurately, the human body pose can provide
valuable information about the head pose, which is a good approximation of the
gaze direction, as well as the position of the arms and hands, which are linked
to the activity the person is performing and the objects they are likely
focusing on. Consequently, in addition to performing gaze estimation in 3D, we
are also able to perform GTD simultaneously. We demonstrate state-of-the-art
results on the most comprehensive publicly accessible 3D gaze target detection
dataset without requiring images of the person's face, thus promoting privacy
preservation in various application contexts. The code is available at
https://github.com/intelligolabs/privacy-gtd-3D.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17744v1">Privacy for Quantum Annealing. Attack on Spin Reversal Transformations
  in the case of cryptanalysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-26T11:17:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mateusz Leśniak, Michał Wroński</p>
    <p><b>Summary:</b> This paper demonstrates that applying spin reversal transformations (SRT),
commonly known as a sufficient method for privacy enhancing in problems solved
using quantum annealing, does not guarantee privacy for all possible problems.
We show how to recover the original problem from the Ising problem obtained
using SRT when the resulting problem in Ising form represents the algebraic
attack on the $E_0$ stream cipher. A small example is used to illustrate how to
retrieve the original problem from the one transformed by SRT. Moreover, it is
shown that our method is efficient even for full-scale problems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17742v1">TADAR: Thermal Array-based Detection and Ranging for Privacy-Preserving
  Human Sensing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-09-26T11:17:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xie Zhang, Chenshu Wu</p>
    <p><b>Summary:</b> Human sensing has gained increasing attention in various applications. Among
the available technologies, visual images offer high accuracy, while sensing on
the RF spectrum preserves privacy, creating a conflict between imaging
resolution and privacy preservation. In this paper, we explore thermal array
sensors as an emerging modality that strikes an excellent resolution-privacy
balance for ubiquitous sensing. To this end, we present TADAR, the first
multi-user Thermal Array-based Detection and Ranging system that estimates the
inherently missing range information, extending thermal array outputs from 2D
thermal pixels to 3D depths and empowering them as a promising modality for
ubiquitous privacy-preserving human sensing. We prototype TADAR using a single
commodity thermal array sensor and conduct extensive experiments in different
indoor environments. Our results show that TADAR achieves a mean F1 score of
88.8% for multi-user detection and a mean accuracy of 32.0 cm for multi-user
ranging, which further improves to 20.1 cm for targets located within 3 m. We
conduct two case studies on fall detection and occupancy estimation to showcase
the potential applications of TADAR. We hope TADAR will inspire the vast
community to explore new directions of thermal array sensing, beyond wireless
and acoustic sensing. TADAR is open-sourced on GitHub:
https://github.com/aiot-lab/TADAR.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17705v1">On the Output Redundancy of LTI Systems: A Geometric Approach with
  Application to Privacy</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2024-09-26T10:21:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Guitao Yang, Alexander J. Gallo, Angelo Barboni, Riccardo M. G. Ferrari, Andrea Serrani, Thomas Parisini</p>
    <p><b>Summary:</b> This paper examines the properties of output-redundant systems, that is,
systems possessing a larger number of outputs than inputs, through the lenses
of the geometric approach of Wonham et al. We begin by formulating a simple
output allocation synthesis problem, which involves ``concealing" input
information from a malicious eavesdropper having access to the system output,
while still allowing for a legitimate user to reconstruct it. It is shown that
the solvability of this problem requires the availability of a redundant set of
outputs. This very problem is instrumental to unveiling the fundamental
geometric properties of output-redundant systems, which form the basis for our
subsequent constructions and results. As a direct application, we demonstrate
how output allocation can be employed to effectively protect the information of
input information from certain output eavesdroppers with guaranteed results.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17700v1">Demystifying Privacy in 5G Stand Alone Networks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Networking and Internet Architecture-04E762">
  <p><b>Published on:</b> 2024-09-26T10:14:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Stavros Eleftherakis, Timothy Otim, Giuseppe Santaromita, Almudena Diaz Zayas, Domenico Giustiniano, Nicolas Kourtellis</p>
    <p><b>Summary:</b> Ensuring user privacy remains critical in mobile networks, particularly with
the rise of connected devices and denser 5G infrastructure. Privacy concerns
have persisted across 2G, 3G, and 4G/LTE networks. Recognizing these concerns,
the 3rd Generation Partnership Project (3GPP) has made privacy enhancements in
5G Release 15. However, the extent of operator adoption remains unclear,
especially as most networks operate in 5G Non Stand Alone (NSA) mode, relying
on 4G Core Networks. This study provides the first qualitative and experimental
comparison between 5G NSA and Stand Alone (SA) in real operator networks,
focusing on privacy enhancements addressing top eight pre-5G attacks based on
recent academic literature. Additionally, it evaluates the privacy levels of
OpenAirInterface (OAI), a leading open-source software for 5G, against real
network deployments for the same attacks. The analysis reveals two new 5G
privacy vulnerabilities, underscoring the need for further research and
stricter standards.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17642v2">AI Delegates with a Dual Focus: Ensuring Privacy and Strategic
  Self-Disclosure</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-09-26T08:45:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xi Chen, Zhiyang Zhang, Fangkai Yang, Xiaoting Qin, Chao Du, Xi Cheng, Hangxin Liu, Qingwei Lin, Saravan Rajmohan, Dongmei Zhang, Qi Zhang</p>
    <p><b>Summary:</b> Large language model (LLM)-based AI delegates are increasingly utilized to
act on behalf of users, assisting them with a wide range of tasks through
conversational interfaces. Despite their advantages, concerns arise regarding
the potential risk of privacy leaks, particularly in scenarios involving social
interactions. While existing research has focused on protecting privacy by
limiting the access of AI delegates to sensitive user information, many social
scenarios require disclosing private details to achieve desired outcomes,
necessitating a balance between privacy protection and disclosure. To address
this challenge, we conduct a pilot study to investigate user preferences for AI
delegates across various social relations and task scenarios, and then propose
a novel AI delegate system that enables privacy-conscious self-disclosure. Our
user study demonstrates that the proposed AI delegate strategically protects
privacy, pioneering its use in diverse and dynamic social interactions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17623v1">Fully Dynamic Graph Algorithms with Edge Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-26T08:17:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sofya Raskhodnikova, Teresa Anna Steiner</p>
    <p><b>Summary:</b> We study differentially private algorithms for analyzing graphs in the
challenging setting of continual release with fully dynamic updates, where
edges are inserted and deleted over time, and the algorithm is required to
update the solution at every time step. Previous work has presented
differentially private algorithms for many graph problems that can handle
insertions only or deletions only (called partially dynamic algorithms) and
obtained some hardness results for the fully dynamic setting. The only
algorithms in the latter setting were for the edge count, given by
Fichtenberger, Henzinger, and Ost (ESA 21), and for releasing the values of all
graph cuts, given by Fichtenberger, Henzinger, and Upadhyay (ICML 23). We
provide the first differentially private and fully dynamic graph algorithms for
several other fundamental graph statistics (including the triangle count, the
number of connected components, the size of the maximum matching, and the
degree histogram), analyze their error and show strong lower bounds on the
error for all algorithms in this setting. We study two variants of edge
differential privacy for fully dynamic graph algorithms: event-level and
item-level. We give upper and lower bounds on the error of both event-level and
item-level fully dynamic algorithms for several fundamental graph problems. No
fully dynamic algorithms that are private at the item-level (the more stringent
of the two notions) were known before. In the case of item-level privacy, for
several problems, our algorithms match our lower bounds.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17578v1">Expanding Perspectives on Data Privacy: Insights from Rural Togo</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-09-26T06:47:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zoe Kahn, Meyebinesso Farida Carelle Pere, Emily Aiken, Nitin Kohli, Joshua E. Blumenstock</p>
    <p><b>Summary:</b> Passively collected "big" data sources are increasingly used to inform
critical development policy decisions in low- and middle-income countries.
While prior work highlights how such approaches may reveal sensitive
information, enable surveillance, and centralize power, less is known about the
corresponding privacy concerns, hopes, and fears of the people directly
impacted by these policies -- people sometimes referred to as experiential
experts. To understand the perspectives of experiential experts, we conducted
semi-structured interviews with people living in rural villages in Togo shortly
after an entirely digital cash transfer program was launched that used machine
learning and mobile phone metadata to determine program eligibility. This paper
documents participants' privacy concerns surrounding the introduction of big
data approaches in development policy. We find that the privacy concerns of our
experiential experts differ from those raised by privacy and development domain
experts. To facilitate a more robust and constructive account of privacy, we
discuss implications for policies and designs that take seriously the privacy
concerns raised by both experiential experts and domain experts.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17538v1">On the Implicit Relation Between Low-Rank Adaptation and Differential
  Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2024-09-26T04:56:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Saber Malekmohammadi, Golnoosh Farnadi</p>
    <p><b>Summary:</b> A significant approach in natural language processing involves large-scale
pre-training on general domain data followed by adaptation to specific tasks or
domains. As models grow in size, full fine-tuning all parameters becomes
increasingly impractical. To address this, some methods for low-rank task
adaptation of language models have been proposed, e.g. LoRA and FLoRA. These
methods keep the pre-trained model weights fixed and incorporate trainable
low-rank decomposition matrices into some layers of the transformer
architecture, called adapters. This approach significantly reduces the number
of trainable parameters required for downstream tasks compared to full
fine-tuning all parameters. In this work, we look at low-rank adaptation from
the lens of data privacy. We show theoretically that the low-rank adaptation
used in LoRA and FLoRA is equivalent to injecting some random noise into the
batch gradients w.r.t the adapter parameters coming from their full
fine-tuning, and we quantify the variance of the injected noise. By
establishing a Berry-Esseen type bound on the total variation distance between
the noise distribution and a Gaussian distribution with the same variance, we
show that the dynamics of LoRA and FLoRA are very close to differentially
private full fine-tuning the adapters, which suggests that low-rank adaptation
implicitly provides privacy w.r.t the fine-tuning data. Finally, using
Johnson-Lindenstrauss lemma, we show that when augmented with gradient
clipping, low-rank adaptation is almost equivalent to differentially private
full fine-tuning adapters with a fixed noise scale.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17535v1">Privacy-Preserving Redaction of Diagnosis Data through Source Code
  Analysis</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-26T04:41:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lixi Zhou, Lei Yu, Jia Zou, Hong Min</p>
    <p><b>Summary:</b> Protecting sensitive information in diagnostic data such as logs, is a
critical concern in the industrial software diagnosis and debugging process.
While there are many tools developed to automatically redact the logs for
identifying and removing sensitive information, they have severe limitations
which can cause either over redaction and loss of critical diagnostic
information (false positives), or disclosure of sensitive information (false
negatives), or both. To address the problem, in this paper, we argue for a
source code analysis approach for log redaction. To identify a log message
containing sensitive information, our method locates the corresponding log
statement in the source code with logger code augmentation, and checks if the
log statement outputs data from sensitive sources by using the data flow graph
built from the source code. Appropriate redaction rules are further applied
depending on the sensitiveness of the data sources to preserve the privacy
information in the logs. We conducted experimental evaluation and comparison
with other popular baselines. The results demonstrate that our approach can
significantly improve the detection precision of the sensitive information and
reduce both false positives and negatives.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17509v1">BioZero: An Efficient and Privacy-Preserving Decentralized Biometric
  Authentication Protocol on Open Blockchain</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-26T03:37:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Junhao Lai, Taotao Wang, Shengli Zhang, Qing Yang, Soung Chang Liew</p>
    <p><b>Summary:</b> Digital identity plays a vital role in enabling secure access to resources
and services in the digital world. Traditional identity authentication methods,
such as password-based and biometric authentications, have limitations in terms
of security, privacy, and scalability. Decentralized authentication approaches
leveraging blockchain technology have emerged as a promising solution. However,
existing decentralized authentication methods often rely on indirect identity
verification (e.g. using passwords or digital signatures as authentication
credentials) and face challenges such as Sybil attacks. In this paper, we
propose BioZero, an efficient and privacy-preserving decentralized biometric
authentication protocol that can be implemented on open blockchain. BioZero
leverages Pedersen commitment and homomorphic computation to protect user
biometric privacy while enabling efficient verification. We enhance the
protocol with non-interactive homomorphic computation and employ zero-knowledge
proofs for secure on-chain verification. The unique aspect of BioZero is that
it is fully decentralized and can be executed by blockchain smart contracts in
a very efficient way. We analyze the security of BioZero and validate its
performance through a prototype implementation. The results demonstrate the
effectiveness, efficiency, and security of BioZero in decentralized
authentication scenarios. Our work contributes to the advancement of
decentralized identity authentication using biometrics.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17315v1">KIPPS: Knowledge infusion in Privacy Preserving Synthetic Data
  Generation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-25T19:50:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anantaa Kotal, Anupam Joshi</p>
    <p><b>Summary:</b> The integration of privacy measures, including differential privacy
techniques, ensures a provable privacy guarantee for the synthetic data.
However, challenges arise for Generative Deep Learning models when tasked with
generating realistic data, especially in critical domains such as Cybersecurity
and Healthcare. Generative Models optimized for continuous data struggle to
model discrete and non-Gaussian features that have domain constraints.
Challenges increase when the training datasets are limited and not diverse. In
such cases, generative models create synthetic data that repeats sensitive
features, which is a privacy risk. Moreover, generative models face
difficulties comprehending attribute constraints in specialized domains. This
leads to the generation of unrealistic data that impacts downstream accuracy.
To address these issues, this paper proposes a novel model, KIPPS, that infuses
Domain and Regulatory Knowledge from Knowledge Graphs into Generative Deep
Learning models for enhanced Privacy Preserving Synthetic data generation. The
novel framework augments the training of generative models with supplementary
context about attribute values and enforces domain constraints during training.
This added guidance enhances the model's capacity to generate realistic and
domain-compliant synthetic data. The proposed model is evaluated on real-world
datasets, specifically in the domains of Cybersecurity and Healthcare, where
domain constraints and rules add to the complexity of the data. Our experiments
evaluate the privacy resilience and downstream accuracy of the model against
benchmark methods, demonstrating its effectiveness in addressing the balance
between privacy preservation and data accuracy in complex domains.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17283v1">Investigating Privacy Attacks in the Gray-Box Setting to Enhance
  Collaborative Learning Schemes</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-25T18:49:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Federico Mazzone, Ahmad Al Badawi, Yuriy Polyakov, Maarten Everts, Florian Hahn, Andreas Peter</p>
    <p><b>Summary:</b> The notion that collaborative machine learning can ensure privacy by just
withholding the raw data is widely acknowledged to be flawed. Over the past
seven years, the literature has revealed several privacy attacks that enable
adversaries to extract information about a model's training dataset by
exploiting access to model parameters during or after training. In this work,
we study privacy attacks in the gray-box setting, where the attacker has only
limited access - in terms of view and actions - to the model. The findings of
our investigation provide new insights for the development of
privacy-preserving collaborative learning solutions. We deploy SmartCryptNN, a
framework that tailors homomorphic encryption to protect the portions of the
model posing higher privacy risks. Our solution offers a trade-off between
privacy and efficiency, which varies based on the extent and selection of the
model components we choose to protect. We explore it on dense neural networks,
where through extensive evaluation of diverse datasets and architectures, we
uncover instances where a favorable sweet spot in the trade-off can be achieved
by safeguarding only a single layer of the network. In one of such instances,
our approach trains ~4 times faster compared to fully encrypted solutions,
while reducing membership leakage by 17.8 times compared to plaintext
solutions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17144v1">Differential Privacy Regularization: Protecting Training Data Through
  Loss Function Regularization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Neural and Evolutionary Computing-5BC0EB">
  <p><b>Published on:</b> 2024-09-25T17:59:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Francisco Aguilera-Martínez, Fernando Berzal</p>
    <p><b>Summary:</b> Training machine learning models based on neural networks requires large
datasets, which may contain sensitive information. The models, however, should
not expose private information from these datasets. Differentially private SGD
[DP-SGD] requires the modification of the standard stochastic gradient descent
[SGD] algorithm for training new models. In this short paper, a novel
regularization strategy is proposed to achieve the same goal in a more
efficient manner.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.17201v1">Immersion and Invariance-based Coding for Privacy-Preserving Federated
  Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-09-25T15:04:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haleh Hayati, Carlos Murguia, Nathan van de Wouw</p>
    <p><b>Summary:</b> Federated learning (FL) has emerged as a method to preserve privacy in
collaborative distributed learning. In FL, clients train AI models directly on
their devices rather than sharing data with a centralized server, which can
pose privacy risks. However, it has been shown that despite FL's partial
protection of local data privacy, information about clients' data can still be
inferred from shared model updates during training. In recent years, several
privacy-preserving approaches have been developed to mitigate this privacy
leakage in FL, though they often provide privacy at the cost of model
performance or system efficiency. Balancing these trade-offs presents a
significant challenge in implementing FL schemes. In this manuscript, we
introduce a privacy-preserving FL framework that combines differential privacy
and system immersion tools from control theory. The core idea is to treat the
optimization algorithms used in standard FL schemes (e.g., gradient-based
algorithms) as a dynamical system that we seek to immerse into a
higher-dimensional system (referred to as the target optimization algorithm).
The target algorithm's dynamics are designed such that, first, the model
parameters of the original algorithm are immersed in its parameters; second, it
operates on distorted parameters; and third, it converges to an encoded version
of the true model parameters from the original algorithm. These encoded
parameters can then be decoded at the server to retrieve the original model
parameters. We demonstrate that the proposed privacy-preserving scheme can be
tailored to offer any desired level of differential privacy for both local and
global model parameters, while maintaining the same accuracy and convergence
rate as standard FL algorithms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.16777v1">PhD Forum: Efficient Privacy-Preserving Processing via Memory-Centric
  Computing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Hardware Architecture-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2024-09-25T09:37:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mpoki Mwaisela</p>
    <p><b>Summary:</b> Privacy-preserving computation techniques like homomorphic encryption (HE)
and secure multi-party computation (SMPC) enhance data security by enabling
processing on encrypted data. However, the significant computational and
CPU-DRAM data movement overhead resulting from the underlying cryptographic
algorithms impedes the adoption of these techniques in practice. Existing
approaches focus on improving computational overhead using specialized hardware
like GPUs and FPGAs, but these methods still suffer from the same
processor-DRAM overhead. Novel hardware technologies that support in-memory
processing have the potential to address this problem. Memory-centric
computing, or processing-in-memory (PIM), brings computation closer to data by
introducing low-power processors called data processing units (DPUs) into
memory. Besides its in-memory computation capability, PIM provides extensive
parallelism, resulting in significant performance improvement over
state-of-the-art approaches. We propose a framework that uses recently
available PIM hardware to achieve efficient privacy-preserving computation. Our
design consists of a four-layer architecture: (1) an application layer that
decouples privacy-preserving applications from the underlying protocols and
hardware; (2) a protocol layer that implements existing secure computation
protocols (HE and MPC); (3) a data orchestration layer that leverages data
compression techniques to mitigate the data transfer overhead between DPUs and
host memory; (4) a computation layer which implements DPU kernels on which
secure computation algorithms are built.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.16688v2">Cycle Counting under Local Differential Privacy for Degeneracy-bounded
  Graphs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2024-09-25T07:23:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Quentin Hillebrand, Vorapong Suppakitpaisarn, Tetsuo Shibuya</p>
    <p><b>Summary:</b> We propose an algorithm for counting the number of cycles under local
differential privacy for degeneracy-bounded input graphs. Numerous studies have
focused on counting the number of triangles under the privacy notion,
demonstrating that the expected $\ell_2$-error of these algorithms is
$\Omega(n^{1.5})$, where $n$ is the number of nodes in the graph. When
parameterized by the number of cycles of length four ($C_4$), the best existing
triangle counting algorithm has an error of $O(n^{1.5} + \sqrt{C_4}) = O(n^2)$.
In this paper, we introduce an algorithm with an expected $\ell_2$-error of
$O(\delta^{1.5} n^{0.5} + \delta^{0.5} d_{\max}^{0.5} n^{0.5})$, where $\delta$
is the degeneracy and $d_{\max}$ is the maximum degree of the graph. For
degeneracy-bounded graphs ($\delta \in \Theta(1)$) commonly found in practical
social networks, our algorithm achieves an expected $\ell_2$-error of
$O(d_{\max}^{0.5} n^{0.5}) = O(n)$. Our algorithm's core idea is a precise
count of triangles following a preprocessing step that approximately sorts the
degree of all nodes. This approach can be extended to approximate the number of
cycles of length $k$, maintaining a similar $\ell_2$-error, namely
$O(\delta^{(k-2)/2} d_{\max}^{0.5} n^{(k-2)/2} + \delta^{k/2} n^{(k-2)/2})$ or
$O(d_{\max}^{0.5} n^{(k-2)/2}) = O(n^{(k-1)/2})$ for degeneracy-bounded graphs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.16621v1">Entailment-Driven Privacy Policy Classification with LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-09-25T05:07:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bhanuka Silva, Dishanika Denipitiyage, Suranga Seneviratne, Anirban Mahanti, Aruna Seneviratne</p>
    <p><b>Summary:</b> While many online services provide privacy policies for end users to read and
understand what personal data are being collected, these documents are often
lengthy and complicated. As a result, the vast majority of users do not read
them at all, leading to data collection under uninformed consent. Several
attempts have been made to make privacy policies more user friendly by
summarising them, providing automatic annotations or labels for key sections,
or by offering chat interfaces to ask specific questions. With recent advances
in Large Language Models (LLMs), there is an opportunity to develop more
effective tools to parse privacy policies and help users make informed
decisions. In this paper, we propose an entailment-driven LLM based framework
to classify paragraphs of privacy policies into meaningful labels that are
easily understood by users. The results demonstrate that our framework
outperforms traditional LLM methods, improving the F1 score in average by
11.2%. Additionally, our framework provides inherently explainable and
meaningful predictions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.16340v1">Future-Proofing Medical Imaging with Privacy-Preserving Federated
  Learning and Uncertainty Quantification: A Review</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-09-24T16:55:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nikolas Koutsoubis, Asim Waqas, Yasin Yilmaz, Ravi P. Ramachandran, Matthew Schabath, Ghulam Rasool</p>
    <p><b>Summary:</b> Artificial Intelligence (AI) has demonstrated significant potential in
automating various medical imaging tasks, which could soon become routine in
clinical practice for disease diagnosis, prognosis, treatment planning, and
post-treatment surveillance. However, the privacy concerns surrounding patient
data present a major barrier to the widespread adoption of AI in medical
imaging, as large, diverse training datasets are essential for developing
accurate, generalizable, and robust Artificial intelligence models. Federated
Learning (FL) offers a solution that enables organizations to train AI models
collaboratively without sharing sensitive data. federated learning exchanges
model training information, such as gradients, between the participating sites.
Despite its promise, federated learning is still in its developmental stages
and faces several challenges. Notably, sensitive information can still be
inferred from the gradients shared during model training. Quantifying AI
models' uncertainty is vital due to potential data distribution shifts
post-deployment, which can affect model performance. Uncertainty quantification
(UQ) in FL is particularly challenging due to data heterogeneity across
participating sites. This review provides a comprehensive examination of FL,
privacy-preserving FL (PPFL), and UQ in FL. We identify key gaps in current FL
methodologies and propose future research directions to enhance data privacy
and trustworthiness in medical imaging applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.16106v2">Scenario of Use Scheme: Threat Model Specification for Speaker Privacy
  Protection in the Medical Domain</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36">
  <p><b>Published on:</b> 2024-09-24T14:07:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mehtab Ur Rahman, Martha Larson, Louis ten Bosch, Cristian Tejedor-García</p>
    <p><b>Summary:</b> Speech recordings are being more frequently used to detect and monitor
disease, leading to privacy concerns. Beyond cryptography, protection of speech
can be addressed by approaches, such as perturbation, disentanglement, and
re-synthesis, that eliminate sensitive information of the speaker, leaving the
information necessary for medical analysis purposes. In order for such privacy
protective approaches to be developed, clear and systematic specifications of
assumptions concerning medical settings and the needs of medical professionals
are necessary. In this paper, we propose a Scenario of Use Scheme that
incorporates an Attacker Model, which characterizes the adversary against whom
the speaker's privacy must be defended, and a Protector Model, which specifies
the defense. We discuss the connection of the scheme with previous work on
speech privacy. Finally, we present a concrete example of a specified Scenario
of Use and a set of experiments about protecting speaker data against gender
inference attacks while maintaining utility for Parkinson's detection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.15868v3">Privacy Evaluation Benchmarks for NLP Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2024-09-24T08:41:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wei Huang, Yinggui Wang, Cen Chen</p>
    <p><b>Summary:</b> By inducing privacy attacks on NLP models, attackers can obtain sensitive
information such as training data and model parameters, etc. Although
researchers have studied, in-depth, several kinds of attacks in NLP models,
they are non-systematic analyses. It lacks a comprehensive understanding of the
impact caused by the attacks. For example, we must consider which scenarios can
apply to which attacks, what the common factors are that affect the performance
of different attacks, the nature of the relationships between different
attacks, and the influence of various datasets and models on the effectiveness
of the attacks, etc. Therefore, we need a benchmark to holistically assess the
privacy risks faced by NLP models. In this paper, we present a privacy attack
and defense evaluation benchmark in the field of NLP, which includes the
conventional/small models and large language models (LLMs). This benchmark
supports a variety of models, datasets, and protocols, along with standardized
modules for comprehensive evaluation of attacks and defense strategies. Based
on the above framework, we present a study on the association between auxiliary
data from different domains and the strength of privacy attacks. And we provide
an improved attack method in this scenario with the help of Knowledge
Distillation (KD). Furthermore, we propose a chained framework for privacy
attacks. Allowing a practitioner to chain multiple attacks to achieve a
higher-level attack objective. Based on this, we provide some defense and
enhanced attack strategies. The code for reproducing the results can be found
at https://github.com/user2311717757/nlp_doctor.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.15656v1">Identified-and-Targeted: The First Early Evidence of the
  Privacy-Invasive Use of Browser Fingerprinting for Online Tracking</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-24T01:39:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zengrui Liu, Jimmy Dani, Shujiang Wu, Yinzhi Cao, Nitesh Saxena</p>
    <p><b>Summary:</b> While advertising has become commonplace in today's online interactions,
there is a notable dearth of research investigating the extent to which browser
fingerprinting is harnessed for user tracking and targeted advertising. Prior
studies only measured whether fingerprinting-related scripts are being run on
the websites but that in itself does not necessarily mean that fingerprinting
is being used for the privacy-invasive purpose of online tracking because
fingerprinting might be deployed for the defensive purposes of bot/fraud
detection and user authentication. It is imperative to address the mounting
concerns regarding the utilization of browser fingerprinting in the realm of
online advertising.
  To understand the privacy-invasive use of fingerprinting for user tracking,
this paper introduces a new framework ``FPTrace'' (fingerprinting-based
tracking assessment and comprehensive evaluation framework) designed to
identify alterations in advertisements resulting from adjustments in browser
fingerprinting settings. Our approach involves emulating genuine user
interactions, capturing advertiser bid data, and closely monitoring HTTP
information. Using FPTrace we conduct a large-scale measurement study to
identify whether browser fingerprinting is being used for the purpose of user
tracking and ad targeting. The results we have obtained provide robust evidence
supporting the utilization of browser fingerprinting for the purposes of
advertisement tracking and targeting. This is substantiated by significant
disparities in bid values and a reduction in HTTP records subsequent to changes
in fingerprinting. In conclusion, our research unveils the widespread
employment of browser fingerprinting in online advertising, prompting critical
considerations regarding user privacy and data security within the digital
advertising landscape.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.15561v1">Analyzing Privacy Implications of Data Collection in Android Automotive
  OS</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-23T21:35:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bulut Gözübüyük, Brian Tang, Kang G. Shin, Mert D. Pesé</p>
    <p><b>Summary:</b> Modern vehicles have become sophisticated computation and sensor systems, as
evidenced by advanced driver assistance systems, in-car infotainment, and
autonomous driving capabilities. They collect and process vast amounts of data
through various embedded subsystems. One significant player in this landscape
is Android Automotive OS (AAOS), which has been integrated into over 100M
vehicles and has become a dominant force in the in-vehicle infotainment market.
With this extensive data collection, privacy has become increasingly crucial.
The volume of data gathered by these systems raises questions about how this
information is stored, used, and protected, making privacy a critical issue for
manufacturers and consumers. However, very little has been done on vehicle data
privacy. This paper focuses on the privacy implications of AAOS, examining the
exact nature and scope of data collection and the corresponding privacy
policies from the original equipment manufacturers (OEMs). We develop a novel
automotive privacy analysis tool called PriDrive which employs three
methodological approaches: network traffic inspection, and both static and
dynamic analyses of Android images using rooted emulators from various OEMs.
These methodologies are followed by an assessment of whether the collected data
types were properly disclosed in OEMs and 3rd party apps' privacy policies (to
identify any discrepancies or violations). Our evaluation on three different
OEM platforms reveals that vehicle speed is collected at a sampling rate of
roughly 25 Hz. Other properties such as model info, climate & AC, and seat data
are collected in a batch 30 seconds into vehicle startup. In addition, several
vehicle property types were collected without disclosure in their respective
privacy policies. For example, OEM A's policies only covers 110 vehicle
properties or 13.02% of the properties found in our static analysis.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.14919v1">Voice Conversion-based Privacy through Adversarial Information Hiding</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> 
  <p><b>Published on:</b> 2024-09-23T11:16:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jacob J Webber, Oliver Watts, Gustav Eje Henter, Jennifer Williams, Simon King</p>
    <p><b>Summary:</b> Privacy-preserving voice conversion aims to remove only the attributes of
speech audio that convey identity information, keeping other speech
characteristics intact. This paper presents a mechanism for privacy-preserving
voice conversion that allows controlling the leakage of identity-bearing
information using adversarial information hiding. This enables a deliberate
trade-off between maintaining source-speech characteristics and modification of
speaker identity. As such, the approach improves on voice-conversion techniques
like CycleGAN and StarGAN, which were not designed for privacy, meaning that
converted speech may leak personal information in unpredictable ways. Our
approach is also more flexible than ASR-TTS voice conversion pipelines, which
by design discard all prosodic information linked to textual content.
Evaluations show that the proposed system successfully modifies perceived
speaker identity whilst well maintaining source lexical content.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.14879v1">Privacy Policy Analysis through Prompt Engineering for LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2024-09-23T10:23:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arda Goknil, Femke B. Gelderblom, Simeon Tverdal, Shukun Tokas, Hui Song</p>
    <p><b>Summary:</b> Privacy policies are often obfuscated by their complexity, which impedes
transparency and informed consent. Conventional machine learning approaches for
automatically analyzing these policies demand significant resources and
substantial domain-specific training, causing adaptability issues. Moreover,
they depend on extensive datasets that may require regular maintenance due to
changing privacy concerns.
  In this paper, we propose, apply, and assess PAPEL (Privacy Policy Analysis
through Prompt Engineering for LLMs), a framework harnessing the power of Large
Language Models (LLMs) through prompt engineering to automate the analysis of
privacy policies. PAPEL aims to streamline the extraction, annotation, and
summarization of information from these policies, enhancing their accessibility
and comprehensibility without requiring additional model training. By
integrating zero-shot, one-shot, and few-shot learning approaches and the
chain-of-thought prompting in creating predefined prompts and prompt templates,
PAPEL guides LLMs to efficiently dissect, interpret, and synthesize the
critical aspects of privacy policies into user-friendly summaries. We
demonstrate the effectiveness of PAPEL with two applications: (i) annotation
and (ii) contradiction analysis. We assess the ability of several LLaMa and GPT
models to identify and articulate data handling practices, offering insights
comparable to existing automated analysis approaches while reducing training
efforts and increasing the adaptability to new analytical needs. The
experiments demonstrate that the LLMs PAPEL utilizes (LLaMA and Chat GPT
models) achieve robust performance in privacy policy annotation, with F1 scores
reaching 0.8 and above (using the OPP-115 gold standard), underscoring the
effectiveness of simpler prompts across various advanced language models.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.14798v1">PrivaMatch: A Privacy-Preserving DNA Matching Scheme for Forensic
  Investigation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-23T08:22:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sankha Das</p>
    <p><b>Summary:</b> DNA fingerprinting and matching for identifying suspects has been a common
practice in criminal investigation. Such proceedings involve multiple parties
such as investigating agencies, suspects and forensic labs. A major challenge
in such settings is to carry out the matching process between the suspects' DNA
samples and the samples obtained from the crime scene without compromising the
privacy of the suspects' DNA profiles. Additionally, it is necessary that
sensitive details pertaining to the investigation such as the identities of the
suspects and evidence obtained from the crime scene must be kept private to the
investigating agency. We present a novel DNA matching scheme, termed as
PrivaMatch, which addresses multiple concerns about privacy of the suspects'
DNA profiles and the crime scene evidence. In the proposed scheme, the
investigating agencies oblivious transfer and zero-knowledge proofs to
privately obtain the DNA profiles of the suspects from the forensic lab's
database.In addition, we present a clever data obfuscation technique using
homomorphic encryption and modular arithmetic for the investigating agency to
privately obtain the DNA profile of the crime scene's sample, keeping the
profile oblivious from the forensic lab. The DNA profile of the crime scene
sample is operated on using a homomorphic cryptosystem such that neither of the
parties (e.g., the investigation agency, forensic labs, DNA database owners)
learns about the private data of the other parties. The proposed scheme is
analysed formally and the practicality of its security strengths is verified
using simulations under standard assumptions.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.14499v1">A Review of Scalable and Privacy-Preserving Multi-Agent Frameworks for
  Distributed Energy Resource Control</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Optimization and Control-F9C80E">
  <p><b>Published on:</b> 2024-09-22T15:52:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiang Huo, Hao Huang, Katherine R. Davis, H. Vincent Poor, Mingxi Liu</p>
    <p><b>Summary:</b> Distributed energy resources (DERs) are gaining prominence due to their
advantages in improving energy efficiency, reducing carbon emissions, and
enhancing grid resilience. Despite the increasing deployment, the potential of
DERs has yet to be fully explored and exploited. A fundamental question
restrains the management of numerous DERs in large-scale power systems, "How
should DER data be securely processed and DER operations be efficiently
optimized?" To address this question, this paper considers two critical issues,
namely privacy for processing DER data and scalability in optimizing DER
operations, then surveys existing and emerging solutions from a multi-agent
framework perspective. In the context of scalability, this paper reviews
state-of-the-art research that relies on parallel control, optimization, and
learning within distributed and/or decentralized information exchange
structures, while in the context of privacy, it identifies privacy preservation
measures that can be synthesized into the aforementioned scalable structures.
Despite research advances in these areas, challenges remain because these
highly interdisciplinary studies blend a wide variety of scalable computing
architectures and privacy preservation techniques from different fields, making
them difficult to adapt in practice. To mitigate this issue, this paper
provides a holistic review of trending strategies that orchestrate privacy and
scalability for large-scale power system operations from a multi-agent
perspective, particularly for DER control problems. Furthermore, this review
extrapolates new approaches for future scalable, privacy-aware, and cybersecure
pathways to unlock the full potential of DERs through controlling, optimizing,
and learning generic multi-agent-based cyber-physical systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.14472v1">Blockchain Based Information Security and Privacy Protection: Challenges
  and Future Directions using Computational Literature Review</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-22T14:41:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gauri Shankar, Md Raihan Uddin, Saddam Mukta, Prabhat Kumar, Shareeful Islam, A. K. M. Najmul Islam</p>
    <p><b>Summary:</b> Blockchain technology is an emerging digital innovation that has gained
immense popularity in enhancing individual security and privacy within
Information Systems (IS). This surge in interest is reflected in the
exponential increase in research articles published on blockchain technology,
highlighting its growing significance in the digital landscape. However, the
rapid proliferation of published research presents significant challenges for
manual analysis and synthesis due to the vast volume of information. The
complexity and breadth of topics, combined with the inherent limitations of
human data processing capabilities, make it difficult to comprehensively
analyze and draw meaningful insights from the literature. To this end, we
adopted the Computational Literature Review (CLR) to analyze pertinent
literature impact and topic modelling using the Latent Dirichlet Allocation
(LDA) technique. We identified 10 topics related to security and privacy and
provided a detailed description of each topic. From the critical analysis, we
have observed several limitations, and several future directions are provided
as an outcome of this review.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.14457v1">Large Model Agents: State-of-the-Art, Cooperation Paradigms, Security
  and Privacy, and Future Trends</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2024-09-22T14:09:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuntao Wang, Yanghe Pan, Quan Zhao, Yi Deng, Zhou Su, Linkang Du, Tom H. Luan</p>
    <p><b>Summary:</b> Large Model (LM) agents, powered by large foundation models such as GPT-4 and
DALL-E 2, represent a significant step towards achieving Artificial General
Intelligence (AGI). LM agents exhibit key characteristics of autonomy,
embodiment, and connectivity, allowing them to operate across physical,
virtual, and mixed-reality environments while interacting seamlessly with
humans, other agents, and their surroundings. This paper provides a
comprehensive survey of the state-of-the-art in LM agents, focusing on the
architecture, cooperation paradigms, security, privacy, and future prospects.
Specifically, we first explore the foundational principles of LM agents,
including general architecture, key components, enabling technologies, and
modern applications. Then, we discuss practical collaboration paradigms from
data, computation, and knowledge perspectives towards connected intelligence of
LM agents. Furthermore, we systematically analyze the security vulnerabilities
and privacy breaches associated with LM agents, particularly in multi-agent
settings. We also explore their underlying mechanisms and review existing and
potential countermeasures. Finally, we outline future research directions for
building robust and secure LM agent ecosystems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.14261v1">Re-Evaluating Privacy in Centralized and Decentralized Learning: An
  Information-Theoretical and Empirical Study</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-21T23:05:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Changlong Ji, Stephane Maag, Richard Heusdens, Qiongxiu Li</p>
    <p><b>Summary:</b> Decentralized Federated Learning (DFL) has garnered attention for its
robustness and scalability compared to Centralized Federated Learning (CFL).
While DFL is commonly believed to offer privacy advantages due to the
decentralized control of sensitive data, recent work by Pasquini et, al.
challenges this view, demonstrating that DFL does not inherently improve
privacy against empirical attacks under certain assumptions. For investigating
fully this issue, a formal theoretical framework is required. Our study offers
a novel perspective by conducting a rigorous information-theoretical analysis
of privacy leakage in FL using mutual information. We further investigate the
effectiveness of privacy-enhancing techniques like Secure Aggregation (SA) in
both CFL and DFL. Our simulations and real-world experiments show that DFL
generally offers stronger privacy preservation than CFL in practical scenarios
where a fully trusted server is not available. We address discrepancies in
previous research by highlighting limitations in their assumptions about graph
topology and privacy attacks, which inadequately capture information leakage in
FL.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.14039v1">Towards Lightweight and Privacy-preserving Data Provision in Digital
  Forensics for Driverless Taxi</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-21T06:51:26Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yanwei Gong, Xiaolin Chang, Jelena Mišić, Vojislav B. Mišić, Junchao Fan, Kaiwen Wang</p>
    <p><b>Summary:</b> Data provision, referring to the data upload and data access, is one key
phase in vehicular digital forensics. The unique features of Driverless Taxi
(DT) bring new issues to this phase: 1) efficient verification of data
integrity when diverse Data Providers (DPs) upload data; 2) DP privacy
preservation during data upload; and 3) privacy preservation of both data and
INvestigator (IN) under complex data ownership when accessing data. To this
end, we propose a novel Lightweight and Privacy-preserving Data Provision
(LPDP) approach consisting of three mechanisms: 1) the Privacy-friendly Batch
Verification Mechanism (PBVm) based on elliptic curve cryptography, 2) Data
Access Control Mechanism (DACm) based on ciphertext-policy attribute-based
encryption, and 3) Decentralized IN Warrant Issuance Mechanism (DIWIm) based on
secret sharing. Privacy preservation of data provision is achieved through: 1)
ensuring the DP privacy preservation in terms of the location privacy and
unlinkability of data upload requests by PBVm, 2) ensuring data privacy
preservation by DACm and DIWIm, and 3) ensuring the identity privacy of IN in
terms of the anonymity and unlinkability of data access requests without
sacrificing the traceability. Lightweight of data provision is achieved
through: 1) ensuring scalable verification of data integrity by PBVm, and 2)
ensuring low-overhead warrant update with respect to DIWIm. Security analysis
and performance evaluation are conducted to validate the security and
performance features of LPDP.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.13953v1">Training Large ASR Encoders with Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> 
  <p><b>Published on:</b> 2024-09-21T00:01:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Geeticka Chauhan, Steve Chien, Om Thakkar, Abhradeep Thakurta, Arun Narayanan</p>
    <p><b>Summary:</b> Self-supervised learning (SSL) methods for large speech models have proven to
be highly effective at ASR. With the interest in public deployment of large
pre-trained models, there is a rising concern for unintended memorization and
leakage of sensitive data points from the training data. In this paper, we
apply differentially private (DP) pre-training to a SOTA Conformer-based
encoder, and study its performance on a downstream ASR task assuming the
fine-tuning data is public. This paper is the first to apply DP to SSL for ASR,
investigating the DP noise tolerance of the BEST-RQ pre-training method.
Notably, we introduce a novel variant of model pruning called gradient-based
layer freezing that provides strong improvements in privacy-utility-compute
trade-offs. Our approach yields a LibriSpeech test-clean/other WER (%) of 3.78/
8.41 with ($10$, 1e^-9)-DP for extrapolation towards low dataset scales, and
2.81/ 5.89 with (10, 7.9e^-11)-DP for extrapolation towards high scales.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.13875v1">Data Distribution Shifts in (Industrial) Federated Learning as a Privacy
  Issue</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-20T20:09:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> David Brunner, Alessio Montuoro</p>
    <p><b>Summary:</b> We consider industrial federated learning, a collaboration between a small
number of powerful, potentially competing industrial players, mediated by a
third party aspiring to improve the service it provides to its customers. We
argue that this configuration harbours covert privacy risks that do not arise
in e.g. cross-device settings. Companies are very protective of their
intellectual property and production processes. Information about changes to
their production and the timing of which is to be kept private. We study a
scenario in which one of the collaborators infers changes to their competitors'
production by detecting potentially subtle temporal data distribution shifts.
In this framing, a data distribution shift is always problematic, even if it
has no negative effect on training convergence. Thus, our goal is to find means
that allow the detection of distributional shifts better than customary
evaluation metrics. Based on the assumption that even minor shifts translate
into the collaboratively learned machine learning model, the attacker tracks
the shared models' internal state with a selection of metrics from literature
in order to pick up on relevant changes. In an empirical study on benchmark
datasets, we show an honest-but-curious attacker to be capable of detecting
subtle distributional shifts on other clients, in some cases long before they
become obvious in evaluation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.12874v1">Privacy-Preserving Framework for Cell-Free MIMO ISAC Systems</a></h3>
  
  <p><b>Published on:</b> 2024-09-19T16:13:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Henrik Åkesson, Diana Pamela Moya Osorio</p>
    <p><b>Summary:</b> Integrated Sensing and Communication (ISAC) systems are prone to privacy
violations, once they aim at handling sensitive identifiable information in
several applications. This paper raises the necessity of implementing
privacy-preservation measures on the design of cell-free massive multiple-input
multiple-output ISAC systems. To that purpose, given an adversary model, we
propose an iterative framework of two blocks, precoder design and access point
selection. The precoder design aims at maximizing the
signal-to-interference-plus-noise ratio at the sensing receivers given
communication constraints. The access point selection aims at minimizing the
mutual information between the received signal at users and the sensing signal,
by rearranging the access points that transmit ISAC-signals and the sensing
receivers. Results show that a reduction in the probability of detection by the
adversary is obtained with this method.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.12651v1">A Deep Dive into Fairness, Bias, Threats, and Privacy in Recommender
  Systems: Insights and Future Research</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Information Retrieval-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2024-09-19T11:00:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Falguni Roy, Xiaofeng Ding, K. -K. R. Choo, Pan Zhou</p>
    <p><b>Summary:</b> Recommender systems are essential for personalizing digital experiences on
e-commerce sites, streaming services, and social media platforms. While these
systems are necessary for modern digital interactions, they face fairness,
bias, threats, and privacy challenges. Bias in recommender systems can result
in unfair treatment of specific users and item groups, and fairness concerns
demand that recommendations be equitable for all users and items. These systems
are also vulnerable to various threats that compromise reliability and
security. Furthermore, privacy issues arise from the extensive use of personal
data, making it crucial to have robust protection mechanisms to safeguard user
information. This study explores fairness, bias, threats, and privacy in
recommender systems. It examines how algorithmic decisions can unintentionally
reinforce biases or marginalize specific user and item groups, emphasizing the
need for fair recommendation strategies. The study also looks at the range of
threats in the form of attacks that can undermine system integrity and
discusses advanced privacy-preserving techniques. By addressing these critical
areas, the study highlights current limitations and suggests future research
directions to improve recommender systems' robustness, fairness, and privacy.
Ultimately, this research aims to help develop more trustworthy and ethical
recommender systems that better serve diverse user populations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.12384v1">Privacy-Preserving Student Learning with Differentially Private
  Data-Free Distillation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2024-09-19T01:00:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Bochao Liu, Jianghu Lu, Pengju Wang, Junjie Zhang, Dan Zeng, Zhenxing Qian, Shiming Ge</p>
    <p><b>Summary:</b> Deep learning models can achieve high inference accuracy by extracting rich
knowledge from massive well-annotated data, but may pose the risk of data
privacy leakage in practical deployment. In this paper, we present an effective
teacher-student learning approach to train privacy-preserving deep learning
models via differentially private data-free distillation. The main idea is
generating synthetic data to learn a student that can mimic the ability of a
teacher well-trained on private data. In the approach, a generator is first
pretrained in a data-free manner by incorporating the teacher as a fixed
discriminator. With the generator, massive synthetic data can be generated for
model training without exposing data privacy. Then, the synthetic data is fed
into the teacher to generate private labels. Towards this end, we propose a
label differential privacy algorithm termed selective randomized response to
protect the label information. Finally, a student is trained on the synthetic
data with the supervision of private labels. In this way, both data privacy and
label privacy are well protected in a unified framework, leading to
privacy-preserving models. Extensive experiments and analysis clearly
demonstrate the effectiveness of our approach.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.12341v1">Provable Privacy Guarantee for Individual Identities and Locations in
  Large-Scale Contact Tracing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2024-09-18T22:19:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tyler Nicewarner, Wei Jiang, Aniruddha Gokhale, Dan Lin</p>
    <p><b>Summary:</b> The task of infectious disease contact tracing is crucial yet challenging,
especially when meeting strict privacy requirements. Previous attempts in this
area have had limitations in terms of applicable scenarios and efficiency. Our
paper proposes a highly scalable, practical contact tracing system called
PREVENT that can work with a variety of location collection methods to gain a
comprehensive overview of a person's trajectory while ensuring the privacy of
individuals being tracked, without revealing their plain text locations to any
party, including servers. Our system is very efficient and can provide
real-time query services for large-scale datasets with millions of locations.
This is made possible by a newly designed secret-sharing based architecture
that is tightly integrated into unique private space partitioning trees.
Notably, our experimental results on both real and synthetic datasets
demonstrate that our system introduces negligible performance overhead compared
to traditional contact tracing methods. PREVENT could be a game-changer in the
fight against infectious diseases and set a new standard for privacy-preserving
location tracking.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.11845v1">Law-based and standards-oriented approach for privacy impact assessment
  in medical devices: a topic for lawyers, engineers and healthcare
  practitioners in MedTech</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-09-18T09:56:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yuri R. Ladeia, David M. Pereira</p>
    <p><b>Summary:</b> Background: The integration of the General Data Protection Regulation (GDPR)
and the Medical Device Regulation (MDR) creates complexities in conducting Data
Protection Impact Assessments (DPIAs) for medical devices. The adoption of
non-binding standards like ISO and IEC can harmonize these processes by
enhancing accountability and privacy by design. Methods: This study employs a
multidisciplinary literature review, focusing on GDPR and MDR intersection in
medical devices that process personal health data. It evaluates key standards,
including ISO/IEC 29134 and IEC 62304, to propose a unified approach for DPIAs
that aligns with legal and technical frameworks. Results: The analysis reveals
the benefits of integrating ISO/IEC standards into DPIAs, which provide
detailed guidance on implementing privacy by design, risk assessment, and
mitigation strategies specific to medical devices. The proposed framework
ensures that DPIAs are living documents, continuously updated to adapt to
evolving data protection challenges. Conclusions: A unified approach combining
European Union (EU) regulations and international standards offers a robust
framework for conducting DPIAs in medical devices. This integration balances
security, innovation, and privacy, enhancing compliance and fostering trust in
medical technologies. The study advocates for leveraging both hard law and
standards to systematically address privacy and safety in the design and
operation of medical devices, thereby raising the maturity of the MedTech
ecosystem.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2409.11805v1">Inside Out or Not: Privacy Implications of Emotional Disclosure</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2024-09-18T08:42:45Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Elham Naghizade, Kaixin Ji, Benjamin Tag, Flora Salim</p>
    <p><b>Summary:</b> Privacy is dynamic, sensitive, and contextual, much like our emotions.
Previous studies have explored the interplay between privacy and context,
privacy and emotion, and emotion and context. However, there remains a
significant gap in understanding the interplay of these aspects simultaneously.
In this paper, we present a preliminary study investigating the role of
emotions in driving individuals' information sharing behaviour, particularly in
relation to urban locations and social ties. We adopt a novel methodology that
integrates context (location and time), emotion, and personal information
sharing behaviour, providing a comprehensive analysis of how contextual
emotions affect privacy. The emotions are assessed with both self-reporting and
electrodermal activity (EDA). Our findings reveal that self-reported emotions
influence personal information-sharing behaviour with distant social groups,
while neutral emotions lead individuals to share less precise information with
close social circles, a pattern is potentially detectable with wrist-worn EDA.
Our study helps lay the foundation for personalised emotion-aware strategies to
mitigate oversharing risks and enhance user privacy in the digital age.</p>
  </details>
</div>

