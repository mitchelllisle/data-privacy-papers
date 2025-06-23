
<h2>2025-06</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.17185v1">A Common Pool of Privacy Problems: Legal and Technical Lessons from a
  Large-Scale Web-Scraped Machine Learning Dataset</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-06-20T17:40:05Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Rachel Hong, Jevan Hutson, William Agnew, Imaad Huda, Tadayoshi Kohno, Jamie Morgenstern</p>
    <p><b>Summary:</b> We investigate the contents of web-scraped data for training AI systems, at
sizes where human dataset curators and compilers no longer manually annotate
every sample. Building off of prior privacy concerns in machine learning
models, we ask: What are the legal privacy implications of web-scraped machine
learning datasets? In an empirical study of a popular training dataset, we find
significant presence of personally identifiable information despite
sanitization efforts. Our audit provides concrete evidence to support the
concern that any large-scale web-scraped dataset may contain personal data. We
use these findings of a real-world dataset to inform our legal analysis with
respect to existing privacy and data protection laws. We surface various
privacy risks of current data curation practices that may propagate personal
information to downstream models. From our findings, we argue for reorientation
of current frameworks of "publicly available" information to meaningfully limit
the development of AI built upon indiscriminate scraping of the internet.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.17012v1">A Novel Approach to Differential Privacy with Alpha Divergence</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-20T14:10:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yifeng Liu, Zehua Wang</p>
    <p><b>Summary:</b> As data-driven technologies advance swiftly, maintaining strong privacy
measures becomes progressively difficult. Conventional $(\epsilon,
\delta)$-differential privacy, while prevalent, exhibits limited adaptability
for many applications. To mitigate these constraints, we present alpha
differential privacy (ADP), an innovative privacy framework grounded in alpha
divergence, which provides a more flexible assessment of privacy consumption.
This study delineates the theoretical underpinnings of ADP and contrasts its
performance with competing privacy frameworks across many scenarios. Empirical
assessments demonstrate that ADP offers enhanced privacy guarantees in small to
moderate iteration contexts, particularly where severe privacy requirements are
necessary. The suggested method markedly improves privacy-preserving methods,
providing a flexible solution for contemporary data analysis issues in a
data-centric environment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.16578v1">SafeTriage: Facial Video De-identification for Privacy-Preserving Stroke
  Triage</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-06-19T20:02:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tongan Cai, Haomiao Ni, Wenchao Ma, Yuan Xue, Qian Ma, Rachel Leicht, Kelvin Wong, John Volpi, Stephen T. C. Wong, James Z. Wang, Sharon X. Huang</p>
    <p><b>Summary:</b> Effective stroke triage in emergency settings often relies on clinicians'
ability to identify subtle abnormalities in facial muscle coordination. While
recent AI models have shown promise in detecting such patterns from patient
facial videos, their reliance on real patient data raises significant ethical
and privacy challenges -- especially when training robust and generalizable
models across institutions. To address these concerns, we propose SafeTriage, a
novel method designed to de-identify patient facial videos while preserving
essential motion cues crucial for stroke diagnosis. SafeTriage leverages a
pretrained video motion transfer (VMT) model to map the motion characteristics
of real patient faces onto synthetic identities. This approach retains
diagnostically relevant facial dynamics without revealing the patients'
identities. To mitigate the distribution shift between normal population
pre-training videos and patient population test videos, we introduce a
conditional generative model for visual prompt tuning, which adapts the input
space of the VMT model to ensure accurate motion transfer without needing to
fine-tune the VMT model backbone. Comprehensive evaluation, including
quantitative metrics and clinical expert assessments, demonstrates that
SafeTriage-produced synthetic videos effectively preserve stroke-relevant
facial patterns, enabling reliable AI-based triage. Our evaluations also show
that SafeTriage provides robust privacy protection while maintaining diagnostic
accuracy, offering a secure and ethically sound foundation for data sharing and
AI-driven clinical analysis in neurological disorders.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.16460v1">Black-Box Privacy Attacks on Shared Representations in Multitask
  Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-19T16:56:41Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> John Abascal, Nicolás Berrios, Alina Oprea, Jonathan Ullman, Adam Smith, Matthew Jagielski</p>
    <p><b>Summary:</b> Multitask learning (MTL) has emerged as a powerful paradigm that leverages
similarities among multiple learning tasks, each with insufficient samples to
train a standalone model, to solve them simultaneously while minimizing data
sharing across users and organizations. MTL typically accomplishes this goal by
learning a shared representation that captures common structure among the tasks
by embedding data from all tasks into a common feature space. Despite being
designed to be the smallest unit of shared information necessary to effectively
learn patterns across multiple tasks, these shared representations can
inadvertently leak sensitive information about the particular tasks they were
trained on.
  In this work, we investigate what information is revealed by the shared
representations through the lens of inference attacks. Towards this, we propose
a novel, black-box task-inference threat model where the adversary, given the
embedding vectors produced by querying the shared representation on samples
from a particular task, aims to determine whether that task was present when
training the shared representation. We develop efficient, purely black-box
attacks on machine learning models that exploit the dependencies between
embeddings from the same task without requiring shadow models or labeled
reference data. We evaluate our attacks across vision and language domains for
multiple use cases of MTL and demonstrate that even with access only to fresh
task samples rather than training data, a black-box adversary can successfully
infer a task's inclusion in training. To complement our experiments, we provide
theoretical analysis of a simplified learning setting and show a strict
separation between adversaries with training samples and fresh samples from the
target task's distribution.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.16347v1">Emission Impossible: privacy-preserving carbon emissions claims</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-19T14:23:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jessica Man, Sadiq Jaffer, Patrick Ferris, Martin Kleppmann, Anil Madhavapeddy</p>
    <p><b>Summary:</b> Information and Communication Technologies (ICT) have a significant climate
impact, and data centres account for a large proportion of the carbon emissions
from ICT. To achieve sustainability goals, it is important that all parties
involved in ICT supply chains can track and share accurate carbon emissions
data with their customers, investors, and the authorities. However, businesses
have strong incentives to make their numbers look good, whilst less so to
publish their accounting methods along with all the input data, due to the risk
of revealing sensitive information. It would be uneconomical to use a trusted
third party to verify the data for every report for each party in the chain. As
a result, carbon emissions reporting in supply chains currently relies on
unverified data. This paper proposes a methodology that applies cryptography
and zero-knowledge proofs for carbon emissions claims that can be subsequently
verified without the knowledge of the private input data. The proposed system
is based on a zero-knowledge Succinct Non-interactive ARguments of Knowledge
(zk-SNARK) protocol, which enables verifiable emissions reporting mechanisms
across a chain of energy suppliers, cloud data centres, cloud services
providers, and customers, without any company needing to disclose commercially
sensitive information. This allows customers of cloud services to accurately
account for the emissions generated by their activities, improving data quality
for their own regulatory reporting. Cloud services providers would also be held
accountable for producing accurate carbon emissions data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.16196v1">Efficient and Privacy-Preserving Soft Prompt Transfer for LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-19T10:25:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xun Wang, Jing Xu, Franziska Boenisch, Michael Backes, Christopher A. Choquette-Choo, Adam Dziedzic</p>
    <p><b>Summary:</b> Prompting has become a dominant paradigm for adapting large language models
(LLMs). While discrete (textual) prompts are widely used for their
interpretability, soft (parameter) prompts have recently gained traction in
APIs. This is because they can encode information from more training samples
while minimizing the user's token usage, leaving more space in the context
window for task-specific input. However, soft prompts are tightly coupled to
the LLM they are tuned on, limiting their generalization to other LLMs. This
constraint is particularly problematic for efficiency and privacy: (1) tuning
prompts on each LLM incurs high computational costs, especially as LLMs
continue to grow in size. Additionally, (2) when the LLM is hosted externally,
soft prompt tuning often requires sharing private data with the LLM provider.
For instance, this is the case with the NVIDIA NeMo API. To address these
issues, we propose POST (Privacy Of Soft prompt Transfer), a framework that
enables private tuning of soft prompts on a small model and subsequently
transfers these prompts to a larger LLM. POST uses knowledge distillation to
derive a small model directly from the large LLM to improve prompt
transferability, tunes the soft prompt locally, optionally with differential
privacy guarantees, and transfers it back to the larger LLM using a small
public dataset. Our experiments show that POST reduces computational costs,
preserves privacy, and effectively transfers high-utility soft prompts.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.15924v1">FARFETCH'D: A Side-Channel Analysis Framework for Privacy Applications
  on Confidential Virtual Machines</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-18T23:58:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruiyi Zhang, Albert Cheu, Adria Gascon, Daniel Moghimi, Phillipp Schoppmann, Michael Schwarz, Octavian Suciu</p>
    <p><b>Summary:</b> Confidential virtual machines (CVMs) based on trusted execution environments
(TEEs) enable new privacy-preserving solutions. Yet, they leave side-channel
leakage outside their threat model, shifting the responsibility of mitigating
such attacks to developers. However, mitigations are either not generic or too
slow for practical use, and developers currently lack a systematic, efficient
way to measure and compare leakage across real-world deployments. In this
paper, we present FARFETCH'D, an open-source toolkit that offers configurable
side-channel tracing primitives on production AMD SEV-SNP hardware and couples
them with statistical and machine-learning-based analysis pipelines for
automated leakage estimation. We apply FARFETCH'D to three representative
workloads that are deployed on CVMs to enhance user privacy - private
information retrieval, private heavy hitters, and Wasm user-defined functions -
and uncover previously unnoticed leaks, including a covert channel that
exfiltrated data at 497 kbit/s. The results show that FARFETCH'D pinpoints
vulnerabilities and guides low-overhead mitigations based on oblivious memory
and differential privacy, giving practitioners a practical path to deploy CVMs
with meaningful confidentiality guarantees.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.15854v1">Privacy-Preserving in Connected and Autonomous Vehicles Through Vision
  to Text Transformation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-18T20:02:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abdolazim Rezaei, Mehdi Sookhak, Ahmad Patooghy</p>
    <p><b>Summary:</b> Connected and Autonomous Vehicles (CAVs) rely on a range of devices that
often process privacy-sensitive data. Among these, roadside units play a
critical role particularly through the use of AI-equipped (AIE) cameras for
applications such as violation detection. However, the privacy risks associated
with captured imagery remain a major concern, as such data can be misused for
identity theft, profiling, or unauthorized commercial purposes. While
traditional techniques such as face blurring and obfuscation have been applied
to mitigate privacy risks, individual privacy remains at risk, as individuals
can still be tracked using other features such as their clothing. This paper
introduces a novel privacy-preserving framework that leverages feedback-based
reinforcement learning (RL) and vision-language models (VLMs) to protect
sensitive visual information captured by AIE cameras. The main idea is to
convert images into semantically equivalent textual descriptions, ensuring that
scene-relevant information is retained while visual privacy is preserved. A
hierarchical RL strategy is employed to iteratively refine the generated text,
enhancing both semantic accuracy and privacy. Evaluation results demonstrate
significant improvements in both privacy protection and textual quality, with
the Unique Word Count increasing by approximately 77\% and Detail Density by
around 50\% compared to existing approaches.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.15349v1">Enhancing One-run Privacy Auditing with Quantile Regression-Based
  Membership Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-18T11:03:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Terrance Liu, Matteo Boglioni, Yiwei Fu, Shengyuan Hu, Pratiksha Thaker, Zhiwei Steven Wu</p>
    <p><b>Summary:</b> Differential privacy (DP) auditing aims to provide empirical lower bounds on
the privacy guarantees of DP mechanisms like DP-SGD. While some existing
techniques require many training runs that are prohibitively costly, recent
work introduces one-run auditing approaches that effectively audit DP-SGD in
white-box settings while still being computationally efficient. However, in the
more practical black-box setting where gradients cannot be manipulated during
training and only the last model iterate is observed, prior work shows that
there is still a large gap between the empirical lower bounds and theoretical
upper bounds. Consequently, in this work, we study how incorporating approaches
for stronger membership inference attacks (MIA) can improve one-run auditing in
the black-box setting. Evaluating on image classification models trained on
CIFAR-10 with DP-SGD, we demonstrate that our proposed approach, which utilizes
quantile regression for MIA, achieves tighter bounds while crucially
maintaining the computational efficiency of one-run methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.15307v1">SecFwT: Efficient Privacy-Preserving Fine-Tuning of Large Language
  Models Using Forward-Only Passes</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-18T09:36:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jinglong Luo, Zhuo Zhang, Yehong Zhang, Shiyu Liu, Ye Dong, Xun Zhou, Hui Wang, Yue Yu, Zenglin Xu</p>
    <p><b>Summary:</b> Large language models (LLMs) have transformed numerous fields, yet their
adaptation to specialized tasks in privacy-sensitive domains, such as
healthcare and finance, is constrained by the scarcity of accessible training
data due to stringent privacy requirements. Secure multi-party computation
(MPC)-based privacy-preserving machine learning offers a powerful approach to
protect both model parameters and user data, but its application to LLMs has
been largely limited to inference, as fine-tuning introduces significant
computational challenges, particularly in privacy-preserving backward
propagation and optimizer operations. This paper identifies two primary
obstacles to MPC-based privacy-preserving fine-tuning of LLMs: (1) the
substantial computational overhead of backward and optimizer processes, and (2)
the inefficiency of softmax-based attention mechanisms in MPC settings. To
address these challenges, we propose SecFwT, the first MPC-based framework
designed for efficient, privacy-preserving LLM fine-tuning. SecFwT introduces a
forward-only tuning paradigm to eliminate backward and optimizer computations
and employs MPC-friendly Random Feature Attention to approximate softmax
attention, significantly reducing costly non-linear operations and
computational complexity. Experimental results demonstrate that SecFwT delivers
substantial improvements in efficiency and privacy preservation, enabling
scalable and secure fine-tuning of LLMs for privacy-critical applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.15258v2">Privacy-Preserving Chest X-ray Classification in Latent Space with
  Homomorphically Encrypted Neural Inference</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-06-18T08:35:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jonghun Kim, Gyeongdeok Jo, Sinyoung Ra, Hyunjin Park</p>
    <p><b>Summary:</b> Medical imaging data contain sensitive patient information requiring strong
privacy protection. Many analytical setups require data to be sent to a server
for inference purposes. Homomorphic encryption (HE) provides a solution by
allowing computations to be performed on encrypted data without revealing the
original information. However, HE inference is computationally expensive,
particularly for large images (e.g., chest X-rays). In this study, we propose
an HE inference framework for medical images that uses VQGAN to compress images
into latent representations, thereby significantly reducing the computational
burden while preserving image quality. We approximate the activation functions
with lower-degree polynomials to balance the accuracy and efficiency in
compliance with HE requirements. We observed that a downsampling factor of
eight for compression achieved an optimal balance between performance and
computational cost. We further adapted the squeeze and excitation module, which
is known to improve traditional CNNs, to enhance the HE framework. Our method
was tested on two chest X-ray datasets for multi-label classification tasks
using vanilla CNN backbones. Although HE inference remains relatively slow and
introduces minor performance differences compared with unencrypted inference,
our approach shows strong potential for practical use in medical images</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.15224v1">Facility Location Problem under Local Differential Privacy without
  Super-set Assumption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-18T08:08:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kevin Pfisterer, Quentin Hillebrand, Vorapong Suppakitpaisarn</p>
    <p><b>Summary:</b> In this paper, we introduce an adaptation of the facility location problem
and analyze it within the framework of local differential privacy (LDP). Under
this model, we ensure the privacy of client presence at specific locations.
When n is the number of points, Gupta et al. established a lower bound of
$\Omega(\sqrt{n})$ on the approximation ratio for any differentially private
algorithm applied to the original facility location problem. As a result,
subsequent works have adopted the super-set assumption, which may, however,
compromise user privacy. We show that this lower bound does not apply to our
adaptation by presenting an LDP algorithm that achieves a constant
approximation ratio with a relatively small additive factor. Additionally, we
provide experimental results demonstrating that our algorithm outperforms the
straightforward approach on both synthetically generated and real-world
datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.15201v1">Privacy-Shielded Image Compression: Defending Against Exploitation from
  Vision-Language Pretrained Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-06-18T07:29:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xuelin Shen, Jiayin Xu, Kangsheng Yin, Wenhan Yang</p>
    <p><b>Summary:</b> The improved semantic understanding of vision-language pretrained (VLP)
models has made it increasingly difficult to protect publicly posted images
from being exploited by search engines and other similar tools. In this
context, this paper seeks to protect users' privacy by implementing defenses at
the image compression stage to prevent exploitation. Specifically, we propose a
flexible coding method, termed Privacy-Shielded Image Compression (PSIC), that
can produce bitstreams with multiple decoding options. By default, the
bitstream is decoded to preserve satisfactory perceptual quality while
preventing interpretation by VLP models. Our method also retains the original
image compression functionality. With a customizable input condition, the
proposed scheme can reconstruct the image that preserves its full semantic
information. A Conditional Latent Trigger Generation (CLTG) module is proposed
to produce bias information based on customizable conditions to guide the
decoding process into different reconstructed versions, and an
Uncertainty-Aware Encryption-Oriented (UAEO) optimization function is designed
to leverage the soft labels inferred from the target VLP model's uncertainty on
the training data. This paper further incorporates an adaptive multi-objective
optimization strategy to obtain improved encrypting performance and perceptual
quality simultaneously within a unified training process. The proposed scheme
is plug-and-play and can be seamlessly integrated into most existing Learned
Image Compression (LIC) models. Extensive experiments across multiple
downstream tasks have demonstrated the effectiveness of our design.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.15112v1">PDLRecover: Privacy-preserving Decentralized Model Recovery with Machine
  Unlearning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-18T03:30:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiangman Li, Xiaodong Wu, Jianbing Ni, Mohamed Mahmoud, Maazen Alsabaan</p>
    <p><b>Summary:</b> Decentralized learning is vulnerable to poison attacks, where malicious
clients manipulate local updates to degrade global model performance. Existing
defenses mainly detect and filter malicious models, aiming to prevent a limited
number of attackers from corrupting the global model. However, restoring an
already compromised global model remains a challenge. A direct approach is to
remove malicious clients and retrain the model using only the benign clients.
Yet, retraining is time-consuming, computationally expensive, and may
compromise model consistency and privacy.
  We propose PDLRecover, a novel method to recover a poisoned global model
efficiently by leveraging historical model information while preserving
privacy. The main challenge lies in protecting shared historical models while
enabling parameter estimation for model recovery. By exploiting the linearity
of approximate Hessian matrix computation, we apply secret sharing to protect
historical updates, ensuring local models are not leaked during transmission or
reconstruction. PDLRecover introduces client-side preparation, periodic
recovery updates, and a final exact update to ensure robustness and convergence
of the recovered model. Periodic updates maintain accurate curvature
information, and the final step ensures high-quality convergence. Experiments
show that the recovered global model achieves performance comparable to a fully
retrained model but with significantly reduced computation and time cost.
Moreover, PDLRecover effectively prevents leakage of local model parameters,
ensuring both accuracy and privacy in recovery.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.15106v2">Local Differential Privacy for Distributed Stochastic Aggregative
  Optimization with Guaranteed Optimality</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2025-06-18T03:22:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ziqin Chen, Yongqiang Wang</p>
    <p><b>Summary:</b> Distributed aggregative optimization underpins many cooperative optimization
and multi-agent control systems, where each agent's objective function depends
both on its local optimization variable and an aggregate of all agents'
optimization variables. Existing distributed aggregative optimization
approaches typically require access to accurate gradients of the objective
functions, which, however, are often hard to obtain in real-world applications.
For example, in machine learning, gradients are commonly contaminated by two
main sources of noise: the randomness inherent in sampled data, and the
additional variability introduced by mini-batch computations. In addition to
the issue of relying on accurate gradients, existing distributed aggregative
optimization approaches require agents to share explicit information, which
could breach the privacy of participating agents. We propose an algorithm that
can solve both problems with existing distributed aggregative optimization
approaches: not only can the proposed algorithm guarantee mean-square
convergence to an exact optimal solution when the gradients are subject to
noise, it also simultaneously ensures rigorous differential privacy, with the
cumulative privacy budget guaranteed to be finite even when the number of
iterations tends to infinity. To the best of our knowledge, this is the first
algorithm able to guarantee both accurate convergence and rigorous differential
privacy in distributed aggregative optimization. Besides characterizing the
convergence rates under nonconvex/convex/strongly convex conditions, we also
rigorously quantify the cost of differential privacy in terms of convergence
rates. Experimental results on personalized machine learning using benchmark
datasets confirm the efficacy of the proposed algorithm.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.14620v1">Differential Privacy and Survey Sampling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Statistics Theory-D91E36"> 
  <p><b>Published on:</b> 2025-06-17T15:17:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Daniel Bernard Bonnéry, Julien Jamme</p>
    <p><b>Summary:</b> The Horvitz-Thompson estimate of a total can be seen as as differentially
private mechanism applied to this population total. We provide forumlae to
compute the $\epsilon$ and $\delta$ parameter for this specific mecanism,
coupled or not coupled with the addition of a Laplace or a Gaussian noise. This
allows to determine the scale of the Laplace privacy mechanism to be added to
reach a specified level of privacy, expressed in terms of $\epsilon,\delta$
differential privacy. In particular, we provide simple formulae for the special
case of simple random sampling on binary data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.14576v1">SoK: Privacy-Enhancing Technologies in Artificial Intelligence</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-17T14:32:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nouha Oualha</p>
    <p><b>Summary:</b> As artificial intelligence (AI) continues to permeate various sectors,
safeguarding personal and sensitive data has become increasingly crucial. To
address these concerns, privacy-enhancing technologies (PETs) have emerged as a
suite of digital tools that enable data collection and processing while
preserving privacy. This paper explores the current landscape of data privacy
in the context of AI, reviews the integration of PETs within AI systems, and
assesses both their achievements and the challenges that remain.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.14251v1">Convergence-Privacy-Fairness Trade-Off in Personalized Federated
  Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB">
  <p><b>Published on:</b> 2025-06-17T07:15:28Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiyu Zhao, Qimei Cui, Weicai Li, Wei Ni, Ekram Hossain, Quan Z. Sheng, Xiaofeng Tao, Ping Zhang</p>
    <p><b>Summary:</b> Personalized federated learning (PFL), e.g., the renowned Ditto, strikes a
balance between personalization and generalization by conducting federated
learning (FL) to guide personalized learning (PL). While FL is unaffected by
personalized model training, in Ditto, PL depends on the outcome of the FL.
However, the clients' concern about their privacy and consequent perturbation
of their local models can affect the convergence and (performance) fairness of
PL. This paper presents PFL, called DP-Ditto, which is a non-trivial extension
of Ditto under the protection of differential privacy (DP), and analyzes the
trade-off among its privacy guarantee, model convergence, and performance
distribution fairness. We also analyze the convergence upper bound of the
personalized models under DP-Ditto and derive the optimal number of global
aggregations given a privacy budget. Further, we analyze the performance
fairness of the personalized models, and reveal the feasibility of optimizing
DP-Ditto jointly for convergence and fairness. Experiments validate our
analysis and demonstrate that DP-Ditto can surpass the DP-perturbed versions of
the state-of-the-art PFL models, such as FedAMP, pFedMe, APPLE, and FedALA, by
over 32.71% in fairness and 9.66% in accuracy.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.13972v1">Membership Inference Attacks as Privacy Tools: Reliability, Disparity
  and Ensemble</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-16T20:22:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhiqi Wang, Chengyu Zhang, Yuetian Chen, Nathalie Baracaldo, Swanand Kadhe, Lei Yu</p>
    <p><b>Summary:</b> Membership inference attacks (MIAs) pose a significant threat to the privacy
of machine learning models and are widely used as tools for privacy assessment,
auditing, and machine unlearning. While prior MIA research has primarily
focused on performance metrics such as AUC, accuracy, and TPR@low FPR - either
by developing new methods to enhance these metrics or using them to evaluate
privacy solutions - we found that it overlooks the disparities among different
attacks. These disparities, both between distinct attack methods and between
multiple instantiations of the same method, have crucial implications for the
reliability and completeness of MIAs as privacy evaluation tools. In this
paper, we systematically investigate these disparities through a novel
framework based on coverage and stability analysis. Extensive experiments
reveal significant disparities in MIAs, their potential causes, and their
broader implications for privacy evaluation. To address these challenges, we
propose an ensemble framework with three distinct strategies to harness the
strengths of state-of-the-art MIAs while accounting for their disparities. This
framework not only enables the construction of more powerful attacks but also
provides a more robust and comprehensive methodology for privacy evaluation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.13882v1">Toward Practical Privacy in XR: Empirical Analysis of Multimodal
  Anonymization Mechanisms</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-06-16T18:01:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Azim Ibragimov, Ethan Wilson, Kevin R. B. Butler, Eakta Jain</p>
    <p><b>Summary:</b> As extended reality (XR) systems become increasingly immersive and
sensor-rich, they enable the collection of fine-grained behavioral signals such
as eye and body telemetry. These signals support personalized and responsive
experiences and may also contain unique patterns that can be linked back to
individuals. However, privacy mechanisms that naively pair unimodal mechanisms
(e.g., independently apply privacy mechanisms for eye and body privatization)
are often ineffective at preventing re-identification in practice. In this
work, we systematically evaluate real-time privacy mechanisms for XR, both
individually and in pair, across eye and body modalities. To preserve
usability, all mechanisms were tuned based on empirically grounded thresholds
for real-time interaction. We evaluated four eye and ten body mechanisms across
multiple datasets, comprising up to 407 participants. Our results show that
while obfuscating eye telemetry alone offers moderate privacy gains, body
telemetry perturbation is substantially more effective. When carefully paired,
multimodal mechanisms reduce re-identification rate from 80.3% to 26.3% in
casual XR applications (e.g., VRChat and Job Simulator) and from 84.8% to 26.1%
in competitive XR applications (e.g., Beat Saber and Synth Riders), all without
violating real-time usability requirements. These findings underscore the
potential of modality-specific and context-aware privacy strategies for
protecting behavioral data in XR environments.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.13561v1">Perfect Privacy for Discriminator-Based Byzantine-Resilient Federated
  Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> 
  <p><b>Published on:</b> 2025-06-16T14:47:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yue Xia, Christoph Hofmeister, Maximilian Egger, Rawad Bitar</p>
    <p><b>Summary:</b> Federated learning (FL) shows great promise in large-scale machine learning
but introduces new privacy and security challenges. We propose ByITFL and
LoByITFL, two novel FL schemes that enhance resilience against Byzantine users
while keeping the users' data private from eavesdroppers. To ensure privacy and
Byzantine resilience, our schemes build on having a small representative
dataset available to the federator and crafting a discriminator function
allowing the mitigation of corrupt users' contributions. ByITFL employs
Lagrange coded computing and re-randomization, making it the first
Byzantine-resilient FL scheme with perfect Information-Theoretic (IT) privacy,
though at the cost of a significant communication overhead. LoByITFL, on the
other hand, achieves Byzantine resilience and IT privacy at a significantly
reduced communication cost, but requires a Trusted Third Party, used only in a
one-time initialization phase before training. We provide theoretical
guarantees on privacy and Byzantine resilience, along with convergence
guarantees and experimental results validating our findings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.13170v1">Dual Protection Ring: User Profiling Via Differential Privacy and
  Service Dissemination Through Private Information Retrieval</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-16T07:33:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Imdad Ullah, Najm Hassan, Tariq Ahamed Ahangar, Zawar Hussain Shah, Mehregan Mahdavi Andrew Levula</p>
    <p><b>Summary:</b> User profiling is crucial in providing personalised services, as it relies on
analysing user behaviour and preferences to deliver targeted services. This
approach enhances user experience and promotes heightened engagement.
Nevertheless, user profiling also gives rise to noteworthy privacy
considerations due to the extensive tracking and monitoring of personal data,
potentially leading to surveillance or identity theft. We propose a dual-ring
protection mechanism to protect user privacy by examining various threats to
user privacy, such as behavioural attacks, profiling fingerprinting and
monitoring, profile perturbation, etc., both on the user and service provider
sides. We develop user profiles that contain sensitive private attributes and
an equivalent profile based on differential privacy for evaluating personalised
services. We determine the entropy of the resultant profiles during each update
to protect profiling attributes and invoke various processes, such as data
evaporation, to artificially increase entropy or destroy private profiling
attributes. Furthermore, we use different variants of private information
retrieval (PIR) to retrieve personalised services against differentially
private profiles. We implement critical components of the proposed model via a
proof-of-concept mobile app to demonstrate its applicability over a specific
case study of advertising services, which can be generalised to other services.
Our experimental results show that the observed processing delays with
different PIR schemes are similar to the current advertising systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.13052v1">Buy it Now, Track Me Later: Attacking User Privacy via Wi-Fi AP Online
  Auctions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-16T02:42:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Steven Su, Erik Rye, Robert Beverly, Dave Levin</p>
    <p><b>Summary:</b> Static and hard-coded layer-two network identifiers are well known to present
security vulnerabilities and endanger user privacy. In this work, we introduce
a new privacy attack against Wi-Fi access points listed on secondhand
marketplaces. Specifically, we demonstrate the ability to remotely gather a
large quantity of layer-two Wi-Fi identifiers by programmatically querying the
eBay marketplace and applying state-of-the-art computer vision techniques to
extract IEEE 802.11 BSSIDs from the seller's posted images of the hardware. By
leveraging data from a global Wi-Fi Positioning System (WPS) that geolocates
BSSIDs, we obtain the physical locations of these devices both pre- and
post-sale. In addition to validating the degree to which a seller's location
matches the location of the device, we examine cases of device movement -- once
the device is sold and then subsequently re-used in a new environment. Our work
highlights a previously unrecognized privacy vulnerability and suggests, yet
again, the strong need to protect layer-two network identifiers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.13009v1">Rectifying Privacy and Efficacy Measurements in Machine Unlearning: A
  New Inference Attack Perspective</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-16T00:30:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nima Naderloui, Shenao Yan, Binghui Wang, Jie Fu, Wendy Hui Wang, Weiran Liu, Yuan Hong</p>
    <p><b>Summary:</b> Machine unlearning focuses on efficiently removing specific data from trained
models, addressing privacy and compliance concerns with reasonable costs.
Although exact unlearning ensures complete data removal equivalent to
retraining, it is impractical for large-scale models, leading to growing
interest in inexact unlearning methods. However, the lack of formal guarantees
in these methods necessitates the need for robust evaluation frameworks to
assess their privacy and effectiveness. In this work, we first identify several
key pitfalls of the existing unlearning evaluation frameworks, e.g., focusing
on average-case evaluation or targeting random samples for evaluation,
incomplete comparisons with the retraining baseline. Then, we propose RULI
(Rectified Unlearning Evaluation Framework via Likelihood Inference), a novel
framework to address critical gaps in the evaluation of inexact unlearning
methods. RULI introduces a dual-objective attack to measure both unlearning
efficacy and privacy risks at a per-sample granularity. Our findings reveal
significant vulnerabilities in state-of-the-art unlearning methods, where RULI
achieves higher attack success rates, exposing privacy risks underestimated by
existing methods. Built on a game-based foundation and validated through
empirical evaluations on both image and text data (spanning tasks from
classification to generation), RULI provides a rigorous, scalable, and
fine-grained methodology for evaluating unlearning techniques.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.12846v1">Privacy-Preserving Federated Learning against Malicious Clients Based on
  Verifiable Functional Encryption</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-06-15T13:38:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Nina Cai, Jinguang Han</p>
    <p><b>Summary:</b> Federated learning is a promising distributed learning paradigm that enables
collaborative model training without exposing local client data, thereby
protect data privacy. However, it also brings new threats and challenges. The
advancement of model inversion attacks has rendered the plaintext transmission
of local models insecure, while the distributed nature of federated learning
makes it particularly vulnerable to attacks raised by malicious clients. To
protect data privacy and prevent malicious client attacks, this paper proposes
a privacy-preserving federated learning framework based on verifiable
functional encryption, without a non-colluding dual-server setup or additional
trusted third-party. Specifically, we propose a novel decentralized verifiable
functional encryption (DVFE) scheme that enables the verification of specific
relationships over multi-dimensional ciphertexts. This scheme is formally
treated, in terms of definition, security model and security proof.
Furthermore, based on the proposed DVFE scheme, we design a privacy-preserving
federated learning framework VFEFL that incorporates a novel robust aggregation
rule to detect malicious clients, enabling the effective training of
high-accuracy models under adversarial settings. Finally, we provide formal
analysis and empirical evaluation of the proposed schemes. The results
demonstrate that our approach achieves the desired privacy protection,
robustness, verifiability and fidelity, while eliminating the reliance on
non-colluding dual-server settings or trusted third parties required by
existing methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.12749v2">Free Privacy Protection for Wireless Federated Learning: Enjoy It or
  Suffer from It?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-15T07:13:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Weicai Li, Tiejun Lv, Xiyu Zhao, Xin Yuan, Wei Ni</p>
    <p><b>Summary:</b> Inherent communication noises have the potential to preserve privacy for
wireless federated learning (WFL) but have been overlooked in digital
communication systems predominantly using floating-point number standards,
e.g., IEEE 754, for data storage and transmission. This is due to the
potentially catastrophic consequences of bit errors in floating-point numbers,
e.g., on the sign or exponent bits. This paper presents a novel channel-native
bit-flipping differential privacy (DP) mechanism tailored for WFL, where
transmit bits are randomly flipped and communication noises are leveraged, to
collectively preserve the privacy of WFL in digital communication systems. The
key idea is to interpret the bit perturbation at the transmitter and bit errors
caused by communication noises as a bit-flipping DP process. This is achieved
by designing a new floating-point-to-fixed-point conversion method that only
transmits the bits in the fraction part of model parameters, hence eliminating
the need for transmitting the sign and exponent bits and preventing the
catastrophic consequence of bit errors. We analyze a new metric to measure the
bit-level distance of the model parameters and prove that the proposed
mechanism satisfies (\lambda,\epsilon)-R\'enyi DP and does not violate the WFL
convergence. Experiments validate privacy and convergence analysis of the
proposed mechanism and demonstrate its superiority to the state-of-the-art
Gaussian mechanisms that are channel-agnostic and add Gaussian noise for
privacy protection.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.12699v2">SoK: The Privacy Paradox of Large Language Models: Advancements, Privacy
  Risks, and Mitigation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-06-15T03:14:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yashothara Shanmugarasa, Ming Ding, M. A. P Chamikara, Thierry Rakotoarivelo</p>
    <p><b>Summary:</b> Large language models (LLMs) are sophisticated artificial intelligence
systems that enable machines to generate human-like text with remarkable
precision. While LLMs offer significant technological progress, their
development using vast amounts of user data scraped from the web and collected
from extensive user interactions poses risks of sensitive information leakage.
Most existing surveys focus on the privacy implications of the training data
but tend to overlook privacy risks from user interactions and advanced LLM
capabilities. This paper aims to fill that gap by providing a comprehensive
analysis of privacy in LLMs, categorizing the challenges into four main areas:
(i) privacy issues in LLM training data, (ii) privacy challenges associated
with user prompts, (iii) privacy vulnerabilities in LLM-generated outputs, and
(iv) privacy challenges involving LLM agents. We evaluate the effectiveness and
limitations of existing mitigation mechanisms targeting these proposed privacy
challenges and identify areas for further research.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.12523v1">Privacy-preserving and reward-based mechanisms of proof of engagement</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Emerging Technologies-F9C80E"> 
  <p><b>Published on:</b> 2025-06-14T14:33:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Matteo Marco Montanari, Alessandro Aldini</p>
    <p><b>Summary:</b> Proof-of-Attendance (PoA) mechanisms are typically employed to demonstrate a
specific user's participation in an event, whether virtual or in-person. The
goal of this study is to extend such mechanisms to broader contexts where the
user wishes to digitally demonstrate her involvement in a specific activity
(Proof-of-Engagement, PoE). This work explores different solutions, including
DLTs as well as established technologies based on centralized systems. The main
aspects we consider include the level of privacy guaranteed to users, the scope
of PoA/PoE (both temporal and spatial), the transferability of the proof, and
the integration with incentive mechanisms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.12328v1">Information-theoretic Estimation of the Risk of Privacy Leaks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-14T03:39:11Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kenneth Odoh</p>
    <p><b>Summary:</b> Recent work~\cite{Liu2016} has shown that dependencies between items in a
dataset can lead to privacy leaks. We extend this concept to privacy-preserving
transformations, considering a broader set of dependencies captured by
correlation metrics. Specifically, we measure the correlation between the
original data and their noisy responses from a randomizer as an indicator of
potential privacy breaches. This paper aims to leverage information-theoretic
measures, such as the Maximal Information Coefficient (MIC), to estimate
privacy leaks and derive novel, computationally efficient privacy leak
estimators. We extend the $\rho_1$-to-$\rho_2$
formulation~\cite{Evfimievski2003} to incorporate entropy, mutual information,
and the degree of anonymity for a more comprehensive measure of privacy risk.
Our proposed hybrid metric can identify correlation dependencies between
attributes in the dataset, serving as a proxy for privacy leak vulnerabilities.
This metric provides a computationally efficient worst-case measure of privacy
loss, utilizing the inherent characteristics of the data to prevent privacy
breaches.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.12241v1">Privacy Reasoning in Ambiguous Contexts</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-13T21:42:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ren Yi, Octavian Suciu, Adria Gascon, Sarah Meiklejohn, Eugene Bagdasarian, Marco Gruteser</p>
    <p><b>Summary:</b> We study the ability of language models to reason about appropriate
information disclosure - a central aspect of the evolving field of agentic
privacy. Whereas previous works have focused on evaluating a model's ability to
align with human decisions, we examine the role of ambiguity and missing
context on model performance when making information-sharing decisions. We
identify context ambiguity as a crucial barrier for high performance in privacy
assessments. By designing Camber, a framework for context disambiguation, we
show that model-generated decision rationales can reveal ambiguities and that
systematically disambiguating context based on these rationales leads to
significant accuracy improvements (up to 13.3\% in precision and up to 22.3\%
in recall) as well as reductions in prompt sensitivity. Overall, our results
indicate that approaches for context disambiguation are a promising way forward
to enhance agentic privacy reasoning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.11687v1">Differential Privacy in Machine Learning: From Symbolic AI to LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Neural and Evolutionary Computing-5BC0EB">
  <p><b>Published on:</b> 2025-06-13T11:30:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Francisco Aguilera-Martínez, Fernando Berzal</p>
    <p><b>Summary:</b> Machine learning models should not reveal particular information that is not
otherwise accessible. Differential privacy provides a formal framework to
mitigate privacy risks by ensuring that the inclusion or exclusion of any
single data point does not significantly alter the output of an algorithm, thus
limiting the exposure of private information. This survey paper explores the
foundational definitions of differential privacy, reviews its original
formulations and tracing its evolution through key research contributions. It
then provides an in-depth examination of how DP has been integrated into
machine learning models, analyzing existing proposals and methods to preserve
privacy when training ML models. Finally, it describes how DP-based ML
techniques can be evaluated in practice. %Finally, it discusses the broader
implications of DP, highlighting its potential for public benefit, its
real-world applications, and the challenges it faces, including vulnerabilities
to adversarial attacks. By offering a comprehensive overview of differential
privacy in machine learning, this work aims to contribute to the ongoing
development of secure and responsible AI systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.11679v1">LLMs on support of privacy and security of mobile apps: state of the art
  and research directions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-06-13T11:17:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tran Thanh Lam Nguyen, Barbara Carminati, Elena Ferrari</p>
    <p><b>Summary:</b> Modern life has witnessed the explosion of mobile devices. However, besides
the valuable features that bring convenience to end users, security and privacy
risks still threaten users of mobile apps. The increasing sophistication of
these threats in recent years has underscored the need for more advanced and
efficient detection approaches. In this chapter, we explore the application of
Large Language Models (LLMs) to identify security risks and privacy violations
and mitigate them for the mobile application ecosystem. By introducing
state-of-the-art research that applied LLMs to mitigate the top 10 common
security risks of smartphone platforms, we highlight the feasibility and
potential of LLMs to replace traditional analysis methods, such as dynamic and
hybrid analysis of mobile apps. As a representative example of LLM-based
solutions, we present an approach to detect sensitive data leakage when users
share images online, a common behavior of smartphone users nowadays. Finally,
we discuss open research challenges.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.12106v1">Enhancing Privacy: The Utility of Stand-Alone Synthetic CT and MRI for
  Tumor and Bone Segmentation</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-06-13T08:17:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> André Ferreira, Kunpeng Xie, Caroline Wilpert, Gustavo Correia, Felix Barajas Ordonez, Tiago Gil Oliveira, Maike Bode, Robert Siepmann, Frank Hölzle, Rainer Röhrig, Jens Kleesiek, Daniel Truhn, Jan Egger, Victor Alves, Behrus Puladi</p>
    <p><b>Summary:</b> AI requires extensive datasets, while medical data is subject to high data
protection. Anonymization is essential, but poses a challenge for some regions,
such as the head, as identifying structures overlap with regions of clinical
interest. Synthetic data offers a potential solution, but studies often lack
rigorous evaluation of realism and utility. Therefore, we investigate to what
extent synthetic data can replace real data in segmentation tasks. We employed
head and neck cancer CT scans and brain glioma MRI scans from two large
datasets. Synthetic data were generated using generative adversarial networks
and diffusion models. We evaluated the quality of the synthetic data using MAE,
MS-SSIM, Radiomics and a Visual Turing Test (VTT) performed by 5 radiologists
and their usefulness in segmentation tasks using DSC. Radiomics indicates high
fidelity of synthetic MRIs, but fall short in producing highly realistic CT
tissue, with correlation coefficient of 0.8784 and 0.5461 for MRI and CT
tumors, respectively. DSC results indicate limited utility of synthetic data:
tumor segmentation achieved DSC=0.064 on CT and 0.834 on MRI, while bone
segmentation a mean DSC=0.841. Relation between DSC and correlation is
observed, but is limited by the complexity of the task. VTT results show
synthetic CTs' utility, but with limited educational applications. Synthetic
data can be used independently for the segmentation task, although limited by
the complexity of the structures to segment. Advancing generative models to
better tolerate heterogeneous inputs and learn subtle details is essential for
enhancing their realism and expanding their application potential.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.11434v1">Auditing Data Provenance in Real-world Text-to-Image Diffusion Models
  for Privacy and Copyright Protection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-06-13T03:16:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jie Zhu, Leye Wang</p>
    <p><b>Summary:</b> Text-to-image diffusion model since its propose has significantly influenced
the content creation due to its impressive generation capability. However, this
capability depends on large-scale text-image datasets gathered from web
platforms like social media, posing substantial challenges in copyright
compliance and personal privacy leakage. Though there are some efforts devoted
to explore approaches for auditing data provenance in text-to-image diffusion
models, existing work has unrealistic assumptions that can obtain model
internal knowledge, e.g., intermediate results, or the evaluation is not
reliable. To fill this gap, we propose a completely black-box auditing
framework called Feature Semantic Consistency-based Auditing (FSCA). It
utilizes two types of semantic connections within the text-to-image diffusion
model for auditing, eliminating the need for access to internal knowledge. To
demonstrate the effectiveness of our FSCA framework, we perform extensive
experiments on LAION-mi dataset and COCO dataset, and compare with eight
state-of-the-art baseline approaches. The results show that FSCA surpasses
previous baseline approaches across various metrics and different data
distributions, showcasing the superiority of our FSCA. Moreover, we introduce a
recall balance strategy and a threshold adjustment strategy, which collectively
allows FSCA to reach up a user-level accuracy of 90% in a real-world auditing
scenario with only 10 samples/user, highlighting its strong auditing potential
in real-world applications. Our code is made available at
https://github.com/JiePKU/FSCA.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.09690v1">Knockoffs Inference under Privacy Constraints</a></h3>
   
  <p><b>Published on:</b> 2025-06-11T13:06:21Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhanrui Cai, Yingying Fan, Lan Gao</p>
    <p><b>Summary:</b> Model-X knockoff framework offers a model-free variable selection method that
ensures finite sample false discovery rate (FDR) control. However, the
complexity of generating knockoff variables, coupled with the model-free
assumption, presents significant challenges for protecting data privacy in this
context. In this paper, we propose a comprehensive framework for knockoff
inference within the differential privacy paradigm. Our proposed method
guarantees robust privacy protection while preserving the exact FDR control
entailed by the original model-X knockoff procedure. We further conduct power
analysis and establish sufficient conditions under which the noise added for
privacy preservation does not asymptotically compromise power. Through various
applications, we demonstrate that the differential privacy knockoff
(DP-knockoff) method can be effectively utilized to safeguard privacy during
variable selection with FDR control in both low and high dimensional settings.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.10042v1">Multiverse Privacy Theory for Contextual Risks in Complex User-AI
  Interactions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-06-11T05:02:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ece Gumusel</p>
    <p><b>Summary:</b> In an era of increasing interaction with artificial intelligence (AI), users
face evolving privacy decisions shaped by complex, uncertain factors. This
paper introduces Multiverse Privacy Theory, a novel framework in which each
privacy decision spawns a parallel universe, representing a distinct potential
outcome based on user choices over time. By simulating these universes, this
theory provides a foundation for understanding privacy through the lens of
contextual integrity, evolving preferences, and probabilistic decision-making.
Future work will explore its application using real-world, scenario-based
survey data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.09387v1">Epass: Efficient and Privacy-Preserving Asynchronous Payment on
  Blockchain</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-11T04:32:54Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Weijie Wang, Jinwen Liang, Chuan Zhang, Ximeng Liu, Liehuang Zhu, Song Guo</p>
    <p><b>Summary:</b> Buy Now Pay Later (BNPL) is a rapidly proliferating e-commerce model,
offering consumers to get the product immediately and defer payments.
Meanwhile, emerging blockchain technologies endow BNPL platforms with digital
currency transactions, allowing BNPL platforms to integrate with digital
wallets. However, the transparency of transactions causes critical privacy
concerns because malicious participants may derive consumers' financial
statuses from on-chain asynchronous payments. Furthermore, the newly created
transactions for deferred payments introduce additional time overheads, which
weaken the scalability of BNPL services. To address these issues, we propose an
efficient and privacy-preserving blockchain-based asynchronous payment scheme
(Epass), which has promising scalability while protecting the privacy of
on-chain consumer transactions. Specifically, Epass leverages locally
verifiable signatures to guarantee the privacy of consumer transactions against
malicious acts. Then, a privacy-preserving asynchronous payment scheme can be
further constructed by leveraging time-release encryption to control trapdoors
of redactable blockchain, reducing time overheads by modifying transactions for
deferred payment. We give formal definitions and security models, generic
structures, and formal proofs for Epass. Extensive comparisons and experimental
analysis show that \textsf{Epass} achieves KB-level communication costs, and
reduces time overhead by more than four times in comparisons with locally
verifiable signatures and Go-Ethereum private test networks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.09312v1">What is the Cost of Differential Privacy for Deep Learning-Based
  Trajectory Generation?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-11T00:59:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Erik Buchholz, Natasha Fernandes, David D. Nguyen, Alsharif Abuadbba, Surya Nepal, Salil S. Kanhere</p>
    <p><b>Summary:</b> While location trajectories offer valuable insights, they also reveal
sensitive personal information. Differential Privacy (DP) offers formal
protection, but achieving a favourable utility-privacy trade-off remains
challenging. Recent works explore deep learning-based generative models to
produce synthetic trajectories. However, current models lack formal privacy
guarantees and rely on conditional information derived from real data during
generation. This work investigates the utility cost of enforcing DP in such
models, addressing three research questions across two datasets and eleven
utility metrics. (1) We evaluate how DP-SGD, the standard DP training method
for deep learning, affects the utility of state-of-the-art generative models.
(2) Since DP-SGD is limited to unconditional models, we propose a novel DP
mechanism for conditional generation that provides formal guarantees and assess
its impact on utility. (3) We analyse how model types - Diffusion, VAE, and GAN
- affect the utility-privacy trade-off. Our results show that DP-SGD
significantly impacts performance, although some utility remains if the
datasets is sufficiently large. The proposed DP mechanism improves training
stability, particularly when combined with DP-SGD, for unstable models such as
GANs and on smaller datasets. Diffusion models yield the best utility without
guarantees, but with DP-SGD, GANs perform best, indicating that the best
non-private model is not necessarily optimal when targeting formal guarantees.
In conclusion, DP trajectory generation remains a challenging task, and formal
guarantees are currently only feasible with large datasets and in constrained
use cases.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.12088v1">Risks & Benefits of LLMs & GenAI for Platform Integrity, Healthcare
  Diagnostics, Cybersecurity, Privacy & AI Safety: A Comprehensive Survey,
  Roadmap & Implementation Blueprint</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-06-10T18:03:19Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kiarash Ahi</p>
    <p><b>Summary:</b> Large Language Models (LLMs) and generative AI (GenAI) systems such as
ChatGPT, Claude, Gemini, LLaMA, and Copilot, developed by OpenAI, Anthropic,
Google, Meta, and Microsoft are reshaping digital platforms and app ecosystems
while introducing key challenges in cybersecurity, privacy, and platform
integrity. Our analysis shows alarming trends: LLM-assisted malware is
projected to rise from 2% in 2021 to 50% by 2025; AI-generated Google reviews
grew from 1.2% in 2021 to 12.21% in 2023, with an expected 30% by 2025; AI scam
reports surged 456%; and misinformation sites increased over 1500%, with a
50-60% increase in deepfakes in 2024. Concurrently, as LLMs have facilitated
code development, mobile app submissions grew from 1.8 million in 2020 to 3.0
million in 2024, with 3.6 million expected by 2025. To address AI threats,
platforms from app stores like Google Play and Apple to developer hubs like
GitHub Copilot, and social platforms like TikTok and Facebook, to marketplaces
like Amazon are deploying AI and LLM-based defenses. This highlights the dual
nature of these technologies as both the source of new threats and the
essential tool for their mitigation. Integrating LLMs into clinical diagnostics
also raises concerns about accuracy, bias, and safety, needing strong
governance. Drawing on a comprehensive analysis of 455 references, this paper
presents a survey of LLM and GenAI risks. We propose a strategic roadmap and
operational blueprint integrating policy auditing (CCPA, GDPR), fraud
detection, and compliance automation, and an advanced LLM-DA stack with modular
components including multi LLM routing, agentic memory, and governance layers
to enhance platform integrity. We also provide actionable insights,
cross-functional best practices, and real-world case studies. These
contributions offer paths to scalable trust, safety, and responsible innovation
across digital platforms.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.08918v1">Quantifying Mix Network Privacy Erosion with Generative Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-10T15:43:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Vasilios Mavroudis, Tariq Elahi</p>
    <p><b>Summary:</b> Modern mix networks improve over Tor and provide stronger privacy guarantees
by robustly obfuscating metadata. As long as a message is routed through at
least one honest mixnode, the privacy of the users involved is safeguarded.
However, the complexity of the mixing mechanisms makes it difficult to estimate
the cumulative privacy erosion occurring over time. This work uses a generative
model trained on mixnet traffic to estimate the loss of privacy when users
communicate persistently over a period of time. We train our large-language
model from scratch on our specialized network traffic ``language'' and then use
it to measure the sender-message unlinkability in various settings (e.g. mixing
strategies, security parameters, observation window). Our findings reveal
notable differences in privacy levels among mix strategies, even when they have
similar mean latencies. In comparison, we demonstrate the limitations of
traditional privacy metrics, such as entropy and log-likelihood, in fully
capturing an adversary's potential to synthesize information from multiple
observations. Finally, we show that larger models exhibit greater sample
efficiency and superior capabilities implying that further advancements in
transformers will consequently enhance the accuracy of model-based privacy
estimates.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.08654v1">A Privacy-Preserving Federated Learning Framework for Generalizable CBCT
  to Synthetic CT Translation in Head and Neck</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-10T10:10:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ciro Benito Raggio, Paolo Zaffino, Maria Francesca Spadea</p>
    <p><b>Summary:</b> Shortened Abstract
  Cone-beam computed tomography (CBCT) has become a widely adopted modality for
image-guided radiotherapy (IGRT). However, CBCT suffers from increased noise,
limited soft-tissue contrast, and artifacts, resulting in unreliable Hounsfield
unit values and hindering direct dose calculation. Synthetic CT (sCT)
generation from CBCT addresses these issues, especially using deep learning
(DL) methods. Existing approaches are limited by institutional heterogeneity,
scanner-dependent variations, and data privacy regulations that prevent
multi-center data sharing.
  To overcome these challenges, we propose a cross-silo horizontal federated
learning (FL) approach for CBCT-to-sCT synthesis in the head and neck region,
extending our FedSynthCT framework. A conditional generative adversarial
network was collaboratively trained on data from three European medical centers
in the public SynthRAD2025 challenge dataset.
  The federated model demonstrated effective generalization across centers,
with mean absolute error (MAE) ranging from $64.38\pm13.63$ to $85.90\pm7.10$
HU, structural similarity index (SSIM) from $0.882\pm0.022$ to $0.922\pm0.039$,
and peak signal-to-noise ratio (PSNR) from $32.86\pm0.94$ to $34.91\pm1.04$ dB.
Notably, on an external validation dataset of 60 patients, comparable
performance was achieved (MAE: $75.22\pm11.81$ HU, SSIM: $0.904\pm0.034$, PSNR:
$33.52\pm2.06$ dB) without additional training, confirming robust
generalization despite protocol, scanner differences and registration errors.
  These findings demonstrate the technical feasibility of FL for CBCT-to-sCT
synthesis while preserving data privacy and offer a collaborative solution for
developing generalizable models across institutions without centralized data
sharing or site-specific fine-tuning.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.08347v2">Differentially Private Relational Learning with Entity-level Privacy
  Guarantees</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-10T02:03:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yinan Huang, Haoteng Yin, Eli Chien, Rongzhe Wei, Pan Li</p>
    <p><b>Summary:</b> Learning with relational and network-structured data is increasingly vital in
sensitive domains where protecting the privacy of individual entities is
paramount. Differential Privacy (DP) offers a principled approach for
quantifying privacy risks, with DP-SGD emerging as a standard mechanism for
private model training. However, directly applying DP-SGD to relational
learning is challenging due to two key factors: (i) entities often participate
in multiple relations, resulting in high and difficult-to-control sensitivity;
and (ii) relational learning typically involves multi-stage, potentially
coupled (interdependent) sampling procedures that make standard privacy
amplification analyses inapplicable. This work presents a principled framework
for relational learning with formal entity-level DP guarantees. We provide a
rigorous sensitivity analysis and introduce an adaptive gradient clipping
scheme that modulates clipping thresholds based on entity occurrence frequency.
We also extend the privacy amplification results to a tractable subclass of
coupled sampling, where the dependence arises only through sample sizes. These
contributions lead to a tailored DP-SGD variant for relational data with
provable privacy guarantees. Experiments on fine-tuning text encoders over
text-attributed network-structured relational data demonstrate the strong
utility-privacy trade-offs of our approach. Our code is available at
https://github.com/Graph-COM/Node_DP.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.08330v1">Distortion Search, A Web Search Privacy Heuristic</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-10T01:35:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kato Mivule, Kenneth Hopkinson</p>
    <p><b>Summary:</b> Search engines have vast technical capabilities to retain Internet search
logs for each user and thus present major privacy vulnerabilities to both
individuals and organizations in revealing user intent. Additionally, many of
the web search privacy enhancing tools available today require that the user
trusts a third party, which make confidentiality of user intent even more
challenging. The user is left at the mercy of the third party without the
control over his or her own privacy. In this article, we suggest a user-centric
heuristic, Distortion Search, a web search query privacy methodology that works
by the formation of obfuscated search queries via the permutation of query
keyword categories, and by strategically applying k-anonymised web navigational
clicks on URLs and Ads to generate a distorted user profile and thus providing
specific user intent and query confidentiality. We provide empirical results
via the evaluation of distorted web search queries in terms of retrieved search
results and the resulting web ads from search engines. Preliminary experimental
results indicate that web search query and specific user intent privacy might
be achievable from the user side without the involvement of the search engine
or other third parties.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.08185v2">Agentic Surgical AI: Surgeon Style Fingerprinting and Privacy Risk
  Quantification via Discrete Diffusion in a Vision-Language-Action Framework</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-06-09T19:49:55Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Huixin Zhan, Jason H. Moore</p>
    <p><b>Summary:</b> Surgeons exhibit distinct operating styles shaped by training, experience,
and motor behavior-yet most surgical AI systems overlook this personalization
signal. We propose a novel agentic modeling approach for surgeon-specific
behavior prediction in robotic surgery, combining a discrete diffusion
framework with a vision-language-action (VLA) pipeline. Gesture prediction is
framed as a structured sequence denoising task, conditioned on multimodal
inputs including surgical video, intent language, and personalized embeddings
of surgeon identity and skill. These embeddings are encoded through natural
language prompts using third-party language models, allowing the model to
retain individual behavioral style without exposing explicit identity. We
evaluate our method on the JIGSAWS dataset and demonstrate that it accurately
reconstructs gesture sequences while learning meaningful motion fingerprints
unique to each surgeon. To quantify the privacy implications of
personalization, we perform membership inference attacks and find that more
expressive embeddings improve task performance but simultaneously increase
susceptibility to identity leakage. These findings demonstrate that while
personalized embeddings improve performance, they also increase vulnerability
to identity leakage, revealing the importance of balancing personalization with
privacy risk in surgical modeling. Code is available at:
https://github.com/huixin-zhan-ai/Surgeon_style_fingerprinting.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.10024v1">Private Memorization Editing: Turning Memorization into a Defense to
  Strengthen Data Privacy in Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-06-09T17:57:43Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Elena Sofia Ruzzetti, Giancarlo A. Xompero, Davide Venditti, Fabio Massimo Zanzotto</p>
    <p><b>Summary:</b> Large Language Models (LLMs) memorize, and thus, among huge amounts of
uncontrolled data, may memorize Personally Identifiable Information (PII),
which should not be stored and, consequently, not leaked. In this paper, we
introduce Private Memorization Editing (PME), an approach for preventing
private data leakage that turns an apparent limitation, that is, the LLMs'
memorization ability, into a powerful privacy defense strategy. While attacks
against LLMs have been performed exploiting previous knowledge regarding their
training data, our approach aims to exploit the same kind of knowledge in order
to make a model more robust. We detect a memorized PII and then mitigate the
memorization of PII by editing a model knowledge of its training data. We
verify that our procedure does not affect the underlying language model while
making it more robust against privacy Training Data Extraction attacks. We
demonstrate that PME can effectively reduce the number of leaked PII in a
number of configurations, in some cases even reducing the accuracy of the
privacy attacks to zero.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.07957v1">Understanding the Error Sensitivity of Privacy-Aware Computing</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Hardware Architecture-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-09T17:27:40Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Matías Mazzanti, Esteban Mocskos, Augusto Vega, Pradip Bose</p>
    <p><b>Summary:</b> Homomorphic Encryption (HE) enables secure computation on encrypted data
without decryption, allowing a great opportunity for privacy-preserving
computation. In particular, domains such as healthcare, finance, and
government, where data privacy and security are of utmost importance, can
benefit from HE by enabling third-party computation and services on sensitive
data. In other words, HE constitutes the "Holy Grail" of cryptography: data
remains encrypted all the time, being protected while in use.
  HE's security guarantees rely on noise added to data to make relatively
simple problems computationally intractable. This error-centric intrinsic HE
mechanism generates new challenges related to the fault tolerance and
robustness of HE itself: hardware- and software-induced errors during HE
operation can easily evade traditional error detection and correction
mechanisms, resulting in silent data corruption (SDC).
  In this work, we motivate a thorough discussion regarding the sensitivity of
HE applications to bit faults and provide a detailed error characterization
study of CKKS (Cheon-Kim-Kim-Song). This is one of the most popular HE schemes
due to its fixed-point arithmetic support for AI and machine learning
applications. We also delve into the impact of the residue number system (RNS)
and the number theoretic transform (NTT), two widely adopted HE optimization
techniques, on CKKS' error sensitivity. To the best of our knowledge, this is
the first work that looks into the robustness and error sensitivity of
homomorphic encryption and, as such, it can pave the way for critical future
work in this area.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.07868v1">Securing Unbounded Differential Privacy Against Timing Attacks</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-09T15:35:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zachary Ratliff, Salil Vadhan</p>
    <p><b>Summary:</b> Recent works have started to theoretically investigate how we can protect
differentially private programs against timing attacks, by making the joint
distribution the output and the runtime differentially private (JOT-DP).
However, the existing approaches to JOT-DP have some limitations, particularly
in the setting of unbounded DP (which protects the size of the dataset and
applies to arbitrarily large datasets). First, the known conversion of pure DP
programs to pure JOT-DP programs in the unbounded setting (a) incurs a constant
additive increase in error probability (and thus does not provide vanishing
error as $n\to\infty$) (b) produces JOT-DP programs that fail to preserve the
computational efficiency of the original pure DP program and (c) is analyzed in
a toy computational model in which the runtime is defined to be the number of
coin flips. In this work, we overcome these limitations. Specifically, we show
that the error required for pure JOT-DP in the unbounded setting depends on the
model of computation. In a randomized RAM model where the dataset size $n$ is
given (or can be computed in constant time) and we can generate random numbers
(not just random bits) in constant time, polynomially small error probability
is necessary and sufficient. If $n$ is not given or we only have a random-bit
generator, an (arbitrarily small) constant error probability is necessary and
sufficient. The aforementioned positive results are proven by efficient
procedures to convert any pure JOT-DP program $P$ in the upper-bounded setting
to a pure JOT-DP program $P'$ in the unbounded setting, such that the output
distribution of $P'$ is $\gamma$-close in total variation distance to that of
$P$, where $\gamma$ is either an arbitrarily small constant or polynomially
small, depending on the model of computation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.07605v2">TimberStrike: Dataset Reconstruction Attack Revealing Privacy Leakage in
  Federated Tree-Based Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-09T10:06:03Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marco Di Gennaro, Giovanni De Lucia, Stefano Longari, Stefano Zanero, Michele Carminati</p>
    <p><b>Summary:</b> Federated Learning has emerged as a privacy-oriented alternative to
centralized Machine Learning, enabling collaborative model training without
direct data sharing. While extensively studied for neural networks, the
security and privacy implications of tree-based models remain underexplored.
This work introduces TimberStrike, an optimization-based dataset reconstruction
attack targeting horizontally federated tree-based models. Our attack, carried
out by a single client, exploits the discrete nature of decision trees by using
split values and decision paths to infer sensitive training data from other
clients. We evaluate TimberStrike on State-of-the-Art federated gradient
boosting implementations across multiple frameworks, including Flower, NVFlare,
and FedTree, demonstrating their vulnerability to privacy breaches. On a
publicly available stroke prediction dataset, TimberStrike consistently
reconstructs between 73.05% and 95.63% of the target dataset across all
implementations. We further analyze Differential Privacy, showing that while it
partially mitigates the attack, it also significantly degrades model
performance. Our findings highlight the need for privacy-preserving mechanisms
specifically designed for tree-based Federated Learning systems, and we provide
preliminary insights into their design.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.07555v2">Synthesize Privacy-Preserving High-Resolution Images via Private Textual
  Intermediaries</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-06-09T08:48:06Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Haoxiang Wang, Zinan Lin, Da Yu, Huishuai Zhang</p>
    <p><b>Summary:</b> Generating high fidelity, differentially private (DP) synthetic images offers
a promising route to share and analyze sensitive visual data without
compromising individual privacy. However, existing DP image synthesis methods
struggle to produce high resolution outputs that faithfully capture the
structure of the original data. In this paper, we introduce a novel method,
referred to as Synthesis via Private Textual Intermediaries (SPTI), that can
generate high resolution DP images with easy adoption. The key idea is to shift
the challenge of DP image synthesis from the image domain to the text domain by
leveraging state of the art DP text generation methods. SPTI first summarizes
each private image into a concise textual description using image to text
models, then applies a modified Private Evolution algorithm to generate DP
text, and finally reconstructs images using text to image models. Notably, SPTI
requires no model training, only inference with off the shelf models. Given a
private dataset, SPTI produces synthetic images of substantially higher quality
than prior DP approaches. On the LSUN Bedroom dataset, SPTI attains an FID less
than or equal to 26.71 under epsilon equal to 1.0, improving over Private
Evolution FID of 40.36. Similarly, on MM CelebA HQ, SPTI achieves an FID less
than or equal to 33.27 at epsilon equal to 1.0, compared to 57.01 from DP fine
tuning baselines. Overall, our results demonstrate that Synthesis via Private
Textual Intermediaries provides a resource efficient and proprietary model
compatible framework for generating high resolution DP synthetic images,
greatly expanding access to private visual datasets.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.07102v1">Decentralized Optimization with Amplified Privacy via Efficient
  Communication</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2025-06-08T12:14:14Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wei Huo, Changxin Liu, Kemi Ding, Karl Henrik Johansson, Ling Shi</p>
    <p><b>Summary:</b> Decentralized optimization is crucial for multi-agent systems, with
significant concerns about communication efficiency and privacy. This paper
explores the role of efficient communication in decentralized stochastic
gradient descent algorithms for enhancing privacy preservation. We develop a
novel algorithm that incorporates two key features: random agent activation and
sparsified communication. Utilizing differential privacy, we demonstrate that
these features reduce noise without sacrificing privacy, thereby amplifying the
privacy guarantee and improving accuracy. Additionally, we analyze the
convergence and the privacy-accuracy-communication trade-off of the proposed
algorithm. Finally, we present experimental results to illustrate the
effectiveness of our algorithm.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.06742v1">LADSG: Label-Anonymized Distillation and Similar Gradient Substitution
  for Label Privacy in Vertical Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-07T10:10:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zeyu Yan, Yifei Yao, Xuanbing Wen, Juli Zhang, Kai Fan</p>
    <p><b>Summary:</b> Vertical federated learning (VFL) has become a key paradigm for collaborative
machine learning, enabling multiple parties to train models over distributed
feature spaces while preserving data privacy. Despite security protocols that
defend against external attacks - such as gradient masking and encryption,
which prevent unauthorized access to sensitive data - recent label inference
attacks from within the system have emerged. These attacks exploit gradients
and semantic embeddings to reconstruct private labels, bypassing traditional
defenses. For example, the passive label inference attack can reconstruct tens
of thousands of participants' private data using just 40 auxiliary labels,
posing a significant security threat. Existing defenses address single leakage
pathways, such as gradient leakage or label exposure. As attack strategies
evolve, their limitations become clear, especially against hybrid attacks that
combine multiple vectors. To address this, we propose Label-Anonymized Defense
with Substitution Gradient (LADSG), a unified defense framework that integrates
gradient substitution, label anonymization, and anomaly detection. LADSG
mitigates both gradient and label leakage while maintaining the scalability and
efficiency of VFL. Experiments on six real-world datasets show that LADSG
reduces label inference attack success rates by 30-60%, with minimal
computational overhead, underscoring the importance of lightweight defenses in
securing VFL.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.06591v1">Privacy Perspectives and Practices of Chinese Smart Home Product Teams</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36">
  <p><b>Published on:</b> 2025-06-06T23:49:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shijing He, Yaxiong Lei, Xiao Zhan, Chi Zhang, Juan Ye, Ruba Abu-Salma, Jose Such</p>
    <p><b>Summary:</b> Previous research has explored the privacy needs and concerns of device
owners, primary users, and different bystander groups with regard to smart home
devices like security cameras, smart speakers, and hubs, but little is known
about the privacy views and practices of smart home product teams, particularly
those in non-Western contexts. This paper presents findings from 27
semi-structured interviews with Chinese smart home product team members,
including product/project managers, software/hardware engineers, user
experience (UX) designers, legal/privacy experts, and marketers/operation
specialists. We examine their privacy perspectives, practices, and risk
mitigation strategies. Our results show that participants emphasized compliance
with Chinese data privacy laws, which typically prioritized national security
over individual privacy rights. China-specific cultural, social, and legal
factors also influenced participants' ethical considerations and attitudes
toward balancing user privacy and security with convenience. Drawing on our
findings, we propose a set of recommendations for smart home product teams,
along with socio-technical and legal interventions to address smart home
privacy issues-especially those belonging to at-risk groups-in Chinese
multi-user smart homes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.06530v1">Breaking the Gaussian Barrier: Residual-PAC Privacy for Automatic
  Privatization</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-06T20:52:47Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tao Zhang, Yevgeniy Vorobeychik</p>
    <p><b>Summary:</b> The Probably Approximately Correct (PAC) Privacy framework [1] provides a
powerful instance-based methodology for certifying privacy in complex
data-driven systems. However, existing PAC Privacy algorithms rely on a
Gaussian mutual information upper bound. We show that this is in general too
conservative: the upper bound obtained by these algorithms is tight if and only
if the perturbed mechanism output is jointly Gaussian with independent Gaussian
noise. To address the inefficiency inherent in the Gaussian-based approach, we
introduce Residual PAC Privacy, an f-divergence-based measure that quantifies
the privacy remaining after adversarial inference. When instantiated with
Kullback-Leibler divergence, Residual-PAC Privacy is governed by conditional
entropy. Moreover, we propose Stackelberg Residual-PAC (SR-PAC) privatization
mechanisms for RPAC Privacy, a game-theoretic framework that selects optimal
noise distributions through convex bilevel optimization. Our approach achieves
tight privacy budget utilization for arbitrary data distributions. Moreover, it
naturally composes under repeated mechanisms and provides provable privacy
guarantees with higher statistical efficiency. Numerical experiments
demonstrate that SR-PAC certifies the target privacy budget while consistently
improving utility compared to existing methods.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.06124v1">PrivTru: A Privacy-by-Design Data Trustee Minimizing Information Leakage</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-06T14:33:59Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Lukas Gehring, Florian Tschorsch</p>
    <p><b>Summary:</b> Data trustees serve as intermediaries that facilitate secure data sharing
between independent parties. This paper offers a technical perspective on Data
trustees, guided by privacy-by-design principles. We introduce PrivTru, an
instantiation of a data trustee that provably achieves optimal privacy
properties. Therefore, PrivTru calculates the minimal amount of information the
data trustee needs to request from data sources to respond to a given query.
Our analysis shows that PrivTru minimizes information leakage to the data
trustee, regardless of the trustee's prior knowledge, while preserving the
utility of the data.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.06062v2">Minoritised Ethnic People's Security and Privacy Concerns and Responses
  towards Essential Online Services</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> 
  <p><b>Published on:</b> 2025-06-06T13:17:44Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Aunam Quyoum, Mark Wong, Sebati Ghosh, Siamak F. Shahandashti</p>
    <p><b>Summary:</b> Minoritised ethnic people are marginalised in society, and therefore at a
higher risk of adverse online harms, including those arising from the loss of
security and privacy of personal data. Despite this, there has been very little
research focused on minoritised ethnic people's security and privacy concerns,
attitudes, and behaviours. In this work, we provide the results of one of the
first studies in this regard. We explore minoritised ethnic people's
experiences of using essential online services across three sectors: health,
social housing, and energy, their security and privacy-related concerns, and
responses towards these services. We conducted a thematic analysis of 44
semi-structured interviews with people of various reported minoritised
ethnicities in the UK. Privacy concerns and lack of control over personal data
emerged as a major theme, with many interviewees considering privacy as their
most significant concern when using online services. Several creative tactics
to exercise some agency were reported, including selective and inconsistent
disclosure of personal data. A core concern about how data may be used was
driven by a fear of repercussions, including penalisation and discrimination,
influenced by prior experiences of institutional and online racism. The
increased concern and potential for harm resulted in minoritised ethnic people
grappling with a higher-stakes dilemma of whether to disclose personal
information online or not. Furthermore, trust in institutions, or lack thereof,
was found to be embedded throughout as a basis for adapting behaviour. We draw
on our results to provide lessons learned for the design of more inclusive,
marginalisation-aware, and privacy-preserving online services.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.05908v1">QualitEye: Public and Privacy-preserving Gaze Data Quality Verification</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/HumanComputer Interaction-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-06-06T09:27:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mayar Elfares, Pascal Reisert, Ralf Küsters, Andreas Bulling</p>
    <p><b>Summary:</b> Gaze-based applications are increasingly advancing with the availability of
large datasets but ensuring data quality presents a substantial challenge when
collecting data at scale. It further requires different parties to collaborate,
therefore, privacy concerns arise. We propose QualitEye--the first method for
verifying image-based gaze data quality. QualitEye employs a new semantic
representation of eye images that contains the information required for
verification while excluding irrelevant information for better domain
adaptation. QualitEye covers a public setting where parties can freely exchange
data and a privacy-preserving setting where parties cannot reveal their raw
data nor derive gaze features/labels of others with adapted private set
intersection protocols. We evaluate QualitEye on the MPIIFaceGaze and
GazeCapture datasets and achieve a high verification performance (with a small
overhead in runtime for privacy-preserving versions). Hence, QualitEye paves
the way for new gaze analysis methods at the intersection of machine learning,
human-computer interaction, and cryptography.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.05743v1">When Better Features Mean Greater Risks: The Performance-Privacy
  Trade-Off in Contrastive Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-06-06T05:03:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ruining Sun, Hongsheng Hu, Wei Luo, Zhaoxi Zhang, Yanjun Zhang, Haizhuan Yuan, Leo Yu Zhang</p>
    <p><b>Summary:</b> With the rapid advancement of deep learning technology, pre-trained encoder
models have demonstrated exceptional feature extraction capabilities, playing a
pivotal role in the research and application of deep learning. However, their
widespread use has raised significant concerns about the risk of training data
privacy leakage. This paper systematically investigates the privacy threats
posed by membership inference attacks (MIAs) targeting encoder models, focusing
on contrastive learning frameworks. Through experimental analysis, we reveal
the significant impact of model architecture complexity on membership privacy
leakage: As more advanced encoder frameworks improve feature-extraction
performance, they simultaneously exacerbate privacy-leakage risks. Furthermore,
this paper proposes a novel membership inference attack method based on the
p-norm of feature vectors, termed the Embedding Lp-Norm Likelihood Attack
(LpLA). This method infers membership status, by leveraging the statistical
distribution characteristics of the p-norm of feature vectors. Experimental
results across multiple datasets and model architectures demonstrate that LpLA
outperforms existing methods in attack performance and robustness, particularly
under limited attack knowledge and query volumes. This study not only uncovers
the potential risks of privacy leakage in contrastive learning frameworks, but
also provides a practical basis for privacy protection research in encoder
models. We hope that this work will draw greater attention to the privacy risks
associated with self-supervised learning models and shed light on the
importance of a balance between model utility and training data privacy. Our
code is publicly available at: https://github.com/SeroneySun/LpLA_code.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.05683v3">Multi-Modal Multi-Task Federated Foundation Models for Next-Generation
  Extended Reality Systems: Towards Privacy-Preserving Distributed Intelligence
  in AR/VR/MR</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Multimedia-5BC0EB">
  <p><b>Published on:</b> 2025-06-06T02:23:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Fardis Nadimi, Payam Abdisarabshali, Kasra Borazjani, Jacob Chakareski, Seyyedali Hosseinalipour</p>
    <p><b>Summary:</b> Extended reality (XR) systems, which consist of virtual reality (VR),
augmented reality (AR), and mixed reality (XR), offer a transformative
interface for immersive, multi-modal, and embodied human-computer interaction.
In this paper, we envision that multi-modal multi-task (M3T) federated
foundation models (FedFMs) can offer transformative capabilities for XR systems
through integrating the representational strength of M3T foundation models
(FMs) with the privacy-preserving model training principles of federated
learning (FL). We present a modular architecture for FedFMs, which entails
different coordination paradigms for model training and aggregations. Central
to our vision is the codification of XR challenges that affect the
implementation of FedFMs under the SHIFT dimensions: (1) Sensor and modality
diversity, (2) Hardware heterogeneity and system-level constraints, (3)
Interactivity and embodied personalization, (4) Functional/task variability,
and (5) Temporality and environmental variability. We illustrate the
manifestation of these dimensions across a set of emerging and anticipated
applications of XR systems. Finally, we propose evaluation metrics, dataset
requirements, and design tradeoffs necessary for the development of
resource-aware FedFMs in XR. This perspective aims to chart the technical and
conceptual foundations for context-aware privacy-preserving intelligence in the
next generation of XR systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.05503v1">On Differential Privacy for Adaptively Solving Search Problems via
  Sketching</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B">
  <p><b>Published on:</b> 2025-06-05T18:40:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shiyuan Feng, Ying Feng, George Z. Li, Zhao Song, David P. Woodruff, Lichen Zhang</p>
    <p><b>Summary:</b> Recently differential privacy has been used for a number of streaming, data
structure, and dynamic graph problems as a means of hiding the internal
randomness of the data structure, so that multiple possibly adaptive queries
can be made without sacrificing the correctness of the responses. Although
these works use differential privacy to show that for some problems it is
possible to tolerate $T$ queries using $\widetilde{O}(\sqrt{T})$ copies of a
data structure, such results only apply to numerical estimation problems, and
only return the cost of an optimization problem rather than the solution
itself. In this paper, we investigate the use of differential privacy for
adaptive queries to search problems, which are significantly more challenging
since the responses to queries can reveal much more about the internal
randomness than a single numerical query. We focus on two classical search
problems: nearest neighbor queries and regression with arbitrary turnstile
updates. We identify key parameters to these problems, such as the number of
$c$-approximate near neighbors and the matrix condition number, and use
different differential privacy techniques to design algorithms returning the
solution vector with memory and time depending on these parameters. We give
algorithms for each of these problems that achieve similar tradeoffs.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.05290v1">Big Bird: Privacy Budget Management for W3C's Privacy-Preserving
  Attribution API</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-05T17:45:13Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Pierre Tholoniat, Alison Caulfield, Giorgio Cavicchioli, Mark Chen, Nikos Goutzoulias, Benjamin Case, Asaf Cidon, Roxana Geambasu, Mathias Lécuyer, Martin Thomson</p>
    <p><b>Summary:</b> Privacy-preserving advertising APIs like Privacy-Preserving Attribution (PPA)
are designed to enhance web privacy while enabling effective ad measurement.
PPA offers an alternative to cross-site tracking with encrypted reports
governed by differential privacy (DP), but current designs lack a principled
approach to privacy budget management, creating uncertainty around critical
design decisions. We present Big Bird, a privacy budget manager for PPA that
clarifies per-site budget semantics and introduces a global budgeting system
grounded in resource isolation principles. Big Bird enforces utility-preserving
limits via quota budgets and improves global budget utilization through a novel
batched scheduling algorithm. Together, these mechanisms establish a robust
foundation for enforcing privacy protections in adversarial environments. We
implement Big Bird in Firefox and evaluate it on real-world ad data,
demonstrating its resilience and effectiveness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.05101v1">Privacy Amplification Through Synthetic Data: Insights from Linear
  Regression</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2025-06-05T14:44:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Clément Pierquin, Aurélien Bellet, Marc Tommasi, Matthieu Boussard</p>
    <p><b>Summary:</b> Synthetic data inherits the differential privacy guarantees of the model used
to generate it. Additionally, synthetic data may benefit from privacy
amplification when the generative model is kept hidden. While empirical studies
suggest this phenomenon, a rigorous theoretical understanding is still lacking.
In this paper, we investigate this question through the well-understood
framework of linear regression. First, we establish negative results showing
that if an adversary controls the seed of the generative model, a single
synthetic data point can leak as much information as releasing the model
itself. Conversely, we show that when synthetic data is generated from random
inputs, releasing a limited number of synthetic data points amplifies privacy
beyond the model's inherent guarantees. We believe our findings in linear
regression can serve as a foundation for deriving more general bounds in the
future.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.04978v1">Evaluating the Impact of Privacy-Preserving Federated Learning on CAN
  Intrusion Detection</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-05T12:49:22Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Gabriele Digregorio, Elisabetta Cainazzo, Stefano Longari, Michele Carminati, Stefano Zanero</p>
    <p><b>Summary:</b> The challenges derived from the data-intensive nature of machine learning in
conjunction with technologies that enable novel paradigms such as V2X and the
potential offered by 5G communication, allow and justify the deployment of
Federated Learning (FL) solutions in the vehicular intrusion detection domain.
In this paper, we investigate the effects of integrating FL strategies into the
machine learning-based intrusion detection process for on-board vehicular
networks. Accordingly, we propose a FL implementation of a state-of-the-art
Intrusion Detection System (IDS) for Controller Area Network (CAN), based on
LSTM autoencoders. We thoroughly evaluate its detection efficiency and
communication overhead, comparing it to a centralized version of the same
algorithm, thereby presenting it as a feasible solution.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.05421v2">TRIDENT -- A Three-Tier Privacy-Preserving Propaganda Detection Model in
  Mobile Networks using Transformers, Adversarial Learning, and Differential
  Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB">
  <p><b>Published on:</b> 2025-06-05T02:38:02Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Al Nahian Bin Emran, Dhiman Goswami, Md Hasan Ullah Sadi, Sanchari Das</p>
    <p><b>Summary:</b> The proliferation of propaganda on mobile platforms raises critical concerns
around detection accuracy and user privacy. To address this, we propose TRIDENT
- a three-tier propaganda detection model implementing transformers,
adversarial learning, and differential privacy which integrates syntactic
obfuscation and label perturbation to mitigate privacy leakage while
maintaining propaganda detection accuracy. TRIDENT leverages multilingual
back-translation to introduce semantic variance, character-level noise, and
entity obfuscation for differential privacy enforcement, and combines these
techniques into a unified defense mechanism. Using a binary propaganda
classification dataset, baseline transformer models (BERT, GPT-2) we achieved
F1 scores of 0.89 and 0.90. Applying TRIDENT's third-tier defense yields a
reduced but effective cumulative F1 of 0.83, demonstrating strong privacy
protection across mobile ML deployments with minimal degradation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.04036v1">Privacy and Security Threat for OpenAI GPTs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-06-04T14:58:29Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wei Wenying, Zhao Kaifa, Xue Lei, Fan Ming</p>
    <p><b>Summary:</b> Large language models (LLMs) demonstrate powerful information handling
capabilities and are widely integrated into chatbot applications. OpenAI
provides a platform for developers to construct custom GPTs, extending
ChatGPT's functions and integrating external services. Since its release in
November 2023, over 3 million custom GPTs have been created. However, such a
vast ecosystem also conceals security and privacy threats. For developers,
instruction leaking attacks threaten the intellectual property of instructions
in custom GPTs through carefully crafted adversarial prompts. For users,
unwanted data access behavior by custom GPTs or integrated third-party services
raises significant privacy concerns. To systematically evaluate the scope of
threats in real-world LLM applications, we develop three phases instruction
leaking attacks target GPTs with different defense level. Our widespread
experiments on 10,000 real-world custom GPTs reveal that over 98.8% of GPTs are
vulnerable to instruction leaking attacks via one or more adversarial prompts,
and half of the remaining GPTs can also be attacked through multiround
conversations. We also developed a framework to assess the effectiveness of
defensive strategies and identify unwanted behaviors in custom GPTs. Our
findings show that 77.5% of custom GPTs with defense strategies are vulnerable
to basic instruction leaking attacks. Additionally, we reveal that 738 custom
GPTs collect user conversational information, and identified 8 GPTs exhibiting
data access behaviors that are unnecessary for their intended functionalities.
Our findings raise awareness among GPT developers about the importance of
integrating specific defensive strategies in their instructions and highlight
users' concerns about data privacy when using LLM-based applications.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.03870v1">Evaluating Apple Intelligence's Writing Tools for Privacy Against Large
  Language Model-Based Inference Attacks: Insights from Early Datasets</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-04T12:01:17Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Mohd. Farhan Israk Soumik, Syed Mhamudul Hasan, Abdur R. Shahid</p>
    <p><b>Summary:</b> The misuse of Large Language Models (LLMs) to infer emotions from text for
malicious purposes, known as emotion inference attacks, poses a significant
threat to user privacy. In this paper, we investigate the potential of Apple
Intelligence's writing tools, integrated across iPhone, iPad, and MacBook, to
mitigate these risks through text modifications such as rewriting and tone
adjustment. By developing early novel datasets specifically for this purpose,
we empirically assess how different text modifications influence LLM-based
detection. This capability suggests strong potential for Apple Intelligence's
writing tools as privacy-preserving mechanisms. Our findings lay the groundwork
for future adaptive rewriting systems capable of dynamically neutralizing
sensitive emotional content to enhance user privacy. To the best of our
knowledge, this research provides the first empirical analysis of Apple
Intelligence's text-modification tools within a privacy-preservation context
with the broader goal of developing on-device, user-centric privacy-preserving
mechanisms to protect against LLMs-based advanced inference attacks on deployed
systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.03618v1">GCFL: A Gradient Correction-based Federated Learning Framework for
  Privacy-preserving CPSS</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-06-04T06:52:37Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jiayi Wan, Xiang Zhu, Fanzhen Liu, Wei Fan, Xiaolong Xu</p>
    <p><b>Summary:</b> Federated learning, as a distributed architecture, shows great promise for
applications in Cyber-Physical-Social Systems (CPSS). In order to mitigate the
privacy risks inherent in CPSS, the integration of differential privacy with
federated learning has attracted considerable attention. Existing research
mainly focuses on dynamically adjusting the noise added or discarding certain
gradients to mitigate the noise introduced by differential privacy. However,
these approaches fail to remove the noise that hinders convergence and correct
the gradients affected by the noise, which significantly reduces the accuracy
of model classification. To overcome these challenges, this paper proposes a
novel framework for differentially private federated learning that balances
rigorous privacy guarantees with accuracy by introducing a server-side gradient
correction mechanism. Specifically, after clients perform gradient clipping and
noise perturbation, our framework detects deviations in the noisy local
gradients and employs a projection mechanism to correct them, mitigating the
negative impact of noise. Simultaneously, gradient projection promotes the
alignment of gradients from different clients and guides the model towards
convergence to a global optimum. We evaluate our framework on several benchmark
datasets, and the experimental results demonstrate that it achieves
state-of-the-art performance under the same privacy budget.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.02998v1">A Multi-Agent Framework for Mitigating Dialect Biases in Privacy Policy
  Question-Answering Systems</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-06-03T15:32:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Đorđe Klisura, Astrid R Bernaga Torres, Anna Karen Gárate-Escamilla, Rajesh Roshan Biswal, Ke Yang, Hilal Pataci, Anthony Rios</p>
    <p><b>Summary:</b> Privacy policies inform users about data collection and usage, yet their
complexity limits accessibility for diverse populations. Existing Privacy
Policy Question Answering (QA) systems exhibit performance disparities across
English dialects, disadvantaging speakers of non-standard varieties. We propose
a novel multi-agent framework inspired by human-centered design principles to
mitigate dialectal biases. Our approach integrates a Dialect Agent, which
translates queries into Standard American English (SAE) while preserving
dialectal intent, and a Privacy Policy Agent, which refines predictions using
domain expertise. Unlike prior approaches, our method does not require
retraining or dialect-specific fine-tuning, making it broadly applicable across
models and domains. Evaluated on PrivacyQA and PolicyQA, our framework improves
GPT-4o-mini's zero-shot accuracy from 0.394 to 0.601 on PrivacyQA and from
0.352 to 0.464 on PolicyQA, surpassing or matching few-shot baselines without
additional training data. These results highlight the effectiveness of
structured agent collaboration in mitigating dialect biases and underscore the
importance of designing NLP systems that account for linguistic diversity to
ensure equitable access to privacy information.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.02965v2">PC-MoE: Memory-Efficient and Privacy-Preserving Collaborative Training
  for Mixture-of-Experts LLMs</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-03T15:00:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ze Yu Zhang, Bolin Ding, Bryan Kian Hsiang Low</p>
    <p><b>Summary:</b> Mixture-of-Experts (MoE) has been gaining popularity due to its successful
adaptation to large language models (LLMs). In this work, we introduce
Privacy-preserving Collaborative Mixture-of-Experts (PC-MoE), which leverages
the sparsity of the MoE architecture for memory-efficient decentralized
collaborative LLM training, enabling multiple parties with limited GPU-memory
and data resources to collectively train more capable LLMs than they could
achieve individually. At the same time, this approach protects training data
privacy of each participant by keeping training data, as well as parts of the
forward pass signal and gradients locally within each party. By design, PC-MoE
synergistically combines the strengths of distributed computation with strong
confidentiality assurances. Unlike most privacy-preserving schemes, which pay
for confidentiality with lower task accuracy, our framework breaks that
trade-off: across seven popular LLM benchmarks, it almost matches (and
sometimes exceeds) the performance and convergence rate of a fully centralized
model, enjoys near 70% peak GPU RAM reduction, while being fully robust against
reconstruction attacks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.02725v1">Recursive Privacy-Preserving Estimation Over Markov Fading Channels</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">
  <p><b>Published on:</b> 2025-06-03T10:33:49Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jie Huang, Fanlin Jia, Xiao He</p>
    <p><b>Summary:</b> In industrial applications, the presence of moving machinery, vehicles, and
personnel, contributes to the dynamic nature of the wireless channel. This time
variability induces channel fading, which can be effectively modeled using a
Markov fading channel (MFC). In this paper, we investigate the problem of
secure state estimation for systems that communicate over a MFC in the presence
of an eavesdropper. The objective is to enable a remote authorized user to
accurately estimate the states of a dynamic system, while considering the
potential interception of the sensor's packet through a wiretap channel. To
prevent information leakage, a novel co-design strategy is established, which
combines a privacy-preserving mechanism with a state estimator. To implement
our encoding scheme, a nonlinear mapping of the innovation is introduced based
on the weighted reconstructed innovation previously received by the legitimate
user. Corresponding to this encoding scheme, we design a recursive
privacy-preserving filtering algorithm to achieve accurate estimation. The
boundedness of estimation error dynamics at the legitimate user's side is
discussed and the divergence of the eavesdropper's estimation error is
analyzed, which demonstrates the effectiveness of our co-design strategy in
ensuring secrecy. Furthermore, a simulation example of a three-tank system is
provided to demonstrate the effectiveness and feasibility of our
privacy-preserving estimation method.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.02711v1">Privacy Leaks by Adversaries: Adversarial Iterations for Membership
  Inference Attack</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-03T10:09:24Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jing Xue, Zhishen Sun, Haishan Ye, Luo Luo, Xiangyu Chang, Ivor Tsang, Guang Dai</p>
    <p><b>Summary:</b> Membership inference attack (MIA) has become one of the most widely used and
effective methods for evaluating the privacy risks of machine learning models.
These attacks aim to determine whether a specific sample is part of the model's
training set by analyzing the model's output. While traditional membership
inference attacks focus on leveraging the model's posterior output, such as
confidence on the target sample, we propose IMIA, a novel attack strategy that
utilizes the process of generating adversarial samples to infer membership. We
propose to infer the member properties of the target sample using the number of
iterations required to generate its adversarial sample. We conduct experiments
across multiple models and datasets, and our results demonstrate that the
number of iterations for generating an adversarial sample is a reliable feature
for membership inference, achieving strong performance both in black-box and
white-box attack scenarios. This work provides a new perspective for evaluating
model privacy and highlights the potential of adversarial example-based
features for privacy leakage assessment.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.02563v1">Privacy-Preserving Federated Convex Optimization: Balancing
  Partial-Participation and Efficiency via Noise Cancellation</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-03T07:48:35Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Roie Reshef, Kfir Yehuda Levy</p>
    <p><b>Summary:</b> This paper tackles the challenge of achieving Differential Privacy (DP) in
Federated Learning (FL) under partial-participation, where only a subset of the
machines participate in each time-step. While previous work achieved optimal
performance in full-participation settings, these methods struggled to extend
to partial-participation scenarios. Our approach fills this gap by introducing
a novel noise-cancellation mechanism that preserves privacy without sacrificing
convergence rates or computational efficiency. We analyze our method within the
Stochastic Convex Optimization (SCO) framework and show that it delivers
optimal performance for both homogeneous and heterogeneous data distributions.
This work expands the applicability of DP in FL, offering an efficient and
practical solution for privacy-preserving learning in distributed systems with
partial participation.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.02422v1">Enhancing Convergence, Privacy and Fairness for Wireless Personalized
  Federated Learning: Quantization-Assisted Min-Max Fair Scheduling</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Distributed, Parallel, and Cluster Computing-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-06-03T04:13:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiyu Zhao, Qimei Cui, Ziqiang Du, Weicai Li, Xi Yu, Wei Ni, Ji Zhang, Xiaofeng Tao, Ping Zhang</p>
    <p><b>Summary:</b> Personalized federated learning (PFL) offers a solution to balancing
personalization and generalization by conducting federated learning (FL) to
guide personalized learning (PL). Little attention has been given to wireless
PFL (WPFL), where privacy concerns arise. Performance fairness of PL models is
another challenge resulting from communication bottlenecks in WPFL. This paper
exploits quantization errors to enhance the privacy of WPFL and proposes a
novel quantization-assisted Gaussian differential privacy (DP) mechanism. We
analyze the convergence upper bounds of individual PL models by considering the
impact of the mechanism (i.e., quantization errors and Gaussian DP noises) and
imperfect communication channels on the FL of WPFL. By minimizing the maximum
of the bounds, we design an optimal transmission scheduling strategy that
yields min-max fairness for WPFL with OFDMA interfaces. This is achieved by
revealing the nested structure of this problem to decouple it into subproblems
solved sequentially for the client selection, channel allocation, and power
control, and for the learning rates and PL-FL weighting coefficients.
Experiments validate our analysis and demonstrate that our approach
substantially outperforms alternative scheduling strategies by 87.08%, 16.21%,
and 38.37% in accuracy, the maximum test loss of participating clients, and
fairness (Jain's index), respectively.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.02410v1">Testing for large-dimensional covariance matrix under differential
  privacy</a></h3>
  
  <p><b>Published on:</b> 2025-06-03T03:53:51Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shiwei Sang, Yicheng Zeng, Xuehu Zhu, Shurong Zheng</p>
    <p><b>Summary:</b> The increasing prevalence of high-dimensional data across various
applications has raised significant privacy concerns in statistical inference.
In this paper, we propose a differentially private integrated statistic for
testing large-dimensional covariance structures, enabling accurate statistical
insights while safeguarding privacy. First, we analyze the global sensitivity
of sample eigenvalues for sub-Gaussian populations, where our method bypasses
the commonly assumed boundedness of data covariates. For sufficiently large
sample size, the privatized statistic guarantees privacy with high probability.
Furthermore, when the ratio of dimension to sample size, $d/n \to y \in (0,
\infty)$, the privatized test is asymptotically distribution-free with
well-known critical values, and detects the local alternative hypotheses
distinct from the null at the fastest rate of $1/\sqrt{n}$. Extensive numerical
studies on synthetic and real data showcase the validity and powerfulness of
our proposed method.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.02156v2">Mitigating Data Poisoning Attacks to Local Differential Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-02T18:37:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Xiaolin Li, Ninghui Li, Boyang Wang, Wenhai Sun</p>
    <p><b>Summary:</b> The distributed nature of local differential privacy (LDP) invites data
poisoning attacks and poses unforeseen threats to the underlying LDP-supported
applications. In this paper, we propose a comprehensive mitigation framework
for popular frequency estimation, which contains a suite of novel defenses,
including malicious user detection, attack pattern recognition, and damaged
utility recovery. In addition to existing attacks, we explore new adaptive
adversarial activities for our mitigation design. For detection, we present a
new method to precisely identify bogus reports and thus LDP aggregation can be
performed over the ``clean'' data. When the attack behavior becomes stealthy
and direct filtering out malicious users is difficult, we further propose a
detection that can effectively recognize hidden adversarial patterns, thus
facilitating the decision-making of service providers. These detection methods
require no additional data and attack information and incur minimal
computational cost. Our experiment demonstrates their excellent performance and
substantial improvement over previous work in various settings. In addition, we
conduct an empirical analysis of LDP post-processing for corrupted data
recovery and propose a new post-processing method, through which we reveal new
insights into protocol recommendations in practice and key design principles
for future research.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.01907v1">SMOTE-DP: Improving Privacy-Utility Tradeoff with Synthetic Data</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2025-06-02T17:27:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yan Zhou, Bradley Malin, Murat Kantarcioglu</p>
    <p><b>Summary:</b> Privacy-preserving data publication, including synthetic data sharing, often
experiences trade-offs between privacy and utility. Synthetic data is generally
more effective than data anonymization in balancing this trade-off, however,
not without its own challenges. Synthetic data produced by generative models
trained on source data may inadvertently reveal information about outliers.
Techniques specifically designed for preserving privacy, such as introducing
noise to satisfy differential privacy, often incur unpredictable and
significant losses in utility. In this work we show that, with the right
mechanism of synthetic data generation, we can achieve strong privacy
protection without significant utility loss. Synthetic data generators
producing contracting data patterns, such as Synthetic Minority Over-sampling
Technique (SMOTE), can enhance a differentially private data generator,
leveraging the strengths of both. We prove in theory and through empirical
demonstration that this SMOTE-DP technique can produce synthetic data that not
only ensures robust privacy protection but maintains utility in downstream
learning tasks.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.01425v1">CSVAR: Enhancing Visual Privacy in Federated Learning via Adaptive
  Shuffling Against Overfitting</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-02T08:30:12Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Zhuo Chen, Zhenya Ma, Yan Zhang, Donghua Cai, Ye Zhang, Qiushi Li, Yongheng Deng, Ye Guo, Ju Ren,  Xuemin,  Shen</p>
    <p><b>Summary:</b> Although federated learning preserves training data within local privacy
domains, the aggregated model parameters may still reveal private
characteristics. This vulnerability stems from clients' limited training data,
which predisposes models to overfitting. Such overfitting enables models to
memorize distinctive patterns from training samples, thereby amplifying the
success probability of privacy attacks like membership inference. To enhance
visual privacy protection in FL, we present CSVAR(Channel-Wise Spatial Image
Shuffling with Variance-Guided Adaptive Region Partitioning), a novel image
shuffling framework to generate obfuscated images for secure data transmission
and each training epoch, addressing both overfitting-induced privacy leaks and
raw image transmission risks. CSVAR adopts region-variance as the metric to
measure visual privacy sensitivity across image regions. Guided by this, CSVAR
adaptively partitions each region into multiple blocks, applying fine-grained
partitioning to privacy-sensitive regions with high region-variances for
enhancing visual privacy protection and coarse-grained partitioning to
privacy-insensitive regions for balancing model utility. In each region, CSVAR
then shuffles between blocks in both the spatial domains and chromatic channels
to hide visual spatial features and disrupt color distribution. Experimental
evaluations conducted on diverse real-world datasets demonstrate that CSVAR is
capable of generating visually obfuscated images that exhibit high perceptual
ambiguity to human eyes, simultaneously mitigating the effectiveness of
adversarial data reconstruction attacks and achieving a good trade-off between
visual privacy protection and model utility.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.01325v1">Understanding the Identity-Transformation Approach in OIDC-Compatible
  Privacy-Preserving SSO Services</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-02T05:11:01Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jingqiang Lin, Baitao Zhang, Wei Wang, Quanwei Cai, Jiwu Jing, Huiyang He</p>
    <p><b>Summary:</b> OpenID Connect (OIDC) enables a user with commercial-off-the-shelf browsers
to log into multiple websites, called relying parties (RPs), by her username
and credential set up in another trusted web system, called the identity
provider (IdP). Identity transformations are proposed in UppreSSO to provide
OIDC-compatible SSO services, preventing both IdP-based login tracing and
RP-based identity linkage. While security and privacy of SSO services in
UppreSSO have been proved, several essential issues of this
identity-transformation approach are not well studied. In this paper, we
comprehensively investigate the approach as below. Firstly, several suggestions
for the efficient integration of identity transformations in OIDC-compatible
SSO are explained. Then, we uncover the relationship between
identity-transformations in SSO and oblivious pseudo-random functions (OPRFs),
and present two variations of the properties required for SSO security as well
as the privacy requirements, to analyze existing OPRF protocols. Finally, new
identity transformations different from those designed in UppreSSO, are
constructed based on OPRFs, satisfying different variations of SSO security
requirements. To the best of our knowledge, this is the first time to uncover
the relationship between identity transformations in OIDC-compatible
privacy-preserving SSO services and OPRFs, and prove the SSO-related properties
(i.e., key-identifier freeness, RP designation and user identification) of OPRF
protocols, in addition to the basic properties of correctness, obliviousness
and pseudo-randomness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.11069v1">Regularized Federated Learning for Privacy-Preserving Dysarthric and
  Elderly Speech Recognition</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Sound-D91E36">
  <p><b>Published on:</b> 2025-06-02T01:34:20Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Tao Zhong, Mengzhe Geng, Shujie Hu, Guinan Li, Xunying Liu</p>
    <p><b>Summary:</b> Accurate recognition of dysarthric and elderly speech remains challenging to
date. While privacy concerns have driven a shift from centralized approaches to
federated learning (FL) to ensure data confidentiality, this further
exacerbates the challenges of data scarcity, imbalanced data distribution and
speaker heterogeneity. To this end, this paper conducts a systematic
investigation of regularized FL techniques for privacy-preserving dysarthric
and elderly speech recognition, addressing different levels of the FL process
by 1) parameter-based, 2) embedding-based and 3) novel loss-based
regularization. Experiments on the benchmark UASpeech dysarthric and
DementiaBank Pitt elderly speech corpora suggest that regularized FL systems
consistently outperform the baseline FedAvg system by statistically significant
WER reductions of up to 0.55\% absolute (2.13\% relative). Further increasing
communication frequency to one exchange per batch approaches centralized
training performance.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.02063v1">Privacy-Aware, Public-Aligned: Embedding Risk Detection and Public
  Values into Scalable Clinical Text De-Identification for Trusted Research
  Environments</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-01T17:45:57Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Arlene Casey, Stuart Dunbar, Franz Gruber, Samuel McInerney, Matúš Falis, Pamela Linksted, Katie Wilde, Kathy Harrison, Alison Hamilton, Christian Cole</p>
    <p><b>Summary:</b> Clinical free-text data offers immense potential to improve population health
research such as richer phenotyping, symptom tracking, and contextual
understanding of patient care. However, these data present significant privacy
risks due to the presence of directly or indirectly identifying information
embedded in unstructured narratives. While numerous de-identification tools
have been developed, few have been tested on real-world, heterogeneous datasets
at scale or assessed for governance readiness. In this paper, we synthesise our
findings from previous studies examining the privacy-risk landscape across
multiple document types and NHS data providers in Scotland. We characterise how
direct and indirect identifiers vary by record type, clinical setting, and data
flow, and show how changes in documentation practice can degrade model
performance over time. Through public engagement, we explore societal
expectations around the safe use of clinical free text and reflect these in the
design of a prototype privacy-risk management tool to support transparent,
auditable decision-making. Our findings highlight that privacy risk is
context-dependent and cumulative, underscoring the need for adaptable, hybrid
de-identification approaches that combine rule-based precision with contextual
understanding. We offer a comprehensive view of the challenges and
opportunities for safe, scalable reuse of clinical free-text within Trusted
Research Environments and beyond, grounded in both technical evidence and
public perspectives on responsible data use.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.01072v1">IDCloak: A Practical Secure Multi-party Dataset Join Framework for
  Vertical Privacy-preserving Machine Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-06-01T16:20:39Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Shuyu Chen, Guopeng Lin, Haoyu Niu, Lushan Song, Chengxun Hong, Weili Han</p>
    <p><b>Summary:</b> Vertical privacy-preserving machine learning (vPPML) enables multiple parties
to train models on their vertically distributed datasets while keeping datasets
private. In vPPML, it is critical to perform the secure dataset join, which
aligns features corresponding to intersection IDs across datasets and forms a
secret-shared and joint training dataset. However, existing methods for this
step could be impractical due to: (1) they are insecure when they expose
intersection IDs; or (2) they rely on a strong trust assumption requiring a
non-colluding auxiliary server; or (3) they are limited to the two-party
setting.
  This paper proposes IDCloak, the first practical secure multi-party dataset
join framework for vPPML that keeps IDs private without a non-colluding
auxiliary server. IDCloak consists of two protocols: (1) a circuit-based
multi-party private set intersection protocol (cmPSI), which obtains
secret-shared flags indicating intersection IDs via an optimized communication
structure combining OKVS and OPRF; (2) a secure multi-party feature alignment
protocol, which obtains the secret-shared and joint dataset using secret-shared
flags, via our proposed efficient secure shuffle protocol. Experiments show
that: (1) compared to the state-of-the-art secure two-party dataset join
framework (iPrivjoin), IDCloak demonstrates higher efficiency in the two-party
setting and comparable performance when the party number increases; (2)
compared to the state-of-the-art cmPSI protocol under honest majority, our
proposed cmPSI protocol provides a stronger security guarantee (dishonest
majority) while improving efficiency by up to $7.78\times$ in time and
$8.73\times$ in communication sizes; (3) our proposed secure shuffle protocol
outperforms the state-of-the-art shuffle protocol by up to $138.34\times$ in
time and $132.13\times$ in communication sizes.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.00759v2">Understanding and Mitigating Cross-lingual Privacy Leakage via
  Language-specific and Universal Privacy Neurons</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-06-01T00:10:30Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Wenshuo Dong, Qingsong Yang, Shu Yang, Lijie Hu, Meng Ding, Wanyu Lin, Tianhang Zheng, Di Wang</p>
    <p><b>Summary:</b> Large Language Models (LLMs) trained on massive data capture rich information
embedded in the training data. However, this also introduces the risk of
privacy leakage, particularly involving personally identifiable information
(PII). Although previous studies have shown that this risk can be mitigated
through methods such as privacy neurons, they all assume that both the
(sensitive) training data and user queries are in English. We show that they
cannot defend against the privacy leakage in cross-lingual contexts: even if
the training data is exclusively in one language, these (private) models may
still reveal private information when queried in another language. In this
work, we first investigate the information flow of cross-lingual privacy
leakage to give a better understanding. We find that LLMs process private
information in the middle layers, where representations are largely shared
across languages. The risk of leakage peaks when converted to a
language-specific space in later layers. Based on this, we identify
privacy-universal neurons and language-specific privacy neurons.
Privacy-universal neurons influence privacy leakage across all languages, while
language-specific privacy neurons are only related to specific languages. By
deactivating these neurons, the cross-lingual privacy leakage risk is reduced
by 23.3%-31.6%.</p>
  </details>
</div>



<h2>2025-05</h2>

<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.00745v1">Controlling the Spread of Epidemics on Networks with Differential
  Privacy</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Data Structures and Algorithms-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computational Engineering, Finance, and Science-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Social and Information Networks-662E9B">
  <p><b>Published on:</b> 2025-05-31T23:17:38Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Dung Nguyen, Aravind Srinivasan, Renata Valieva, Anil Vullikanti, Jiayi Wu</p>
    <p><b>Summary:</b> Designing effective strategies for controlling epidemic spread by vaccination
is an important question in epidemiology, especially in the early stages when
vaccines are limited. This is a challenging question when the contact network
is very heterogeneous, and strategies based on controlling network properties,
such as the degree and spectral radius, have been shown to be effective.
Implementation of such strategies requires detailed information on the contact
structure, which might be sensitive in many applications. Our focus here is on
choosing effective vaccination strategies when the edges are sensitive and
differential privacy guarantees are needed. Our main contributions are
$(\varepsilon,\delta)$-differentially private algorithms for designing
vaccination strategies by reducing the maximum degree and spectral radius. Our
key technique is a private algorithm for the multi-set multi-cover problem,
which we use for controlling network properties. We evaluate privacy-utility
tradeoffs of our algorithms on multiple synthetic and real-world networks, and
show their effectiveness.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.00660v1">Differential Privacy for Deep Learning in Medicine</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">
  <p><b>Published on:</b> 2025-05-31T18:03:15Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Marziyeh Mohammadi, Mohsen Vejdanihemmat, Mahshad Lotfinia, Mirabela Rusu, Daniel Truhn, Andreas Maier, Soroosh Tayebi Arasteh</p>
    <p><b>Summary:</b> Differential privacy (DP) is a key technique for protecting sensitive patient
data in medical deep learning (DL). As clinical models grow more
data-dependent, balancing privacy with utility and fairness has become a
critical challenge. This scoping review synthesizes recent developments in
applying DP to medical DL, with a particular focus on DP-SGD and alternative
mechanisms across centralized and federated settings. Using a structured search
strategy, we identified 74 studies published up to March 2025. Our analysis
spans diverse data modalities, training setups, and downstream tasks, and
highlights the tradeoffs between privacy guarantees, model accuracy, and
subgroup fairness. We find that while DP-especially at strong privacy
budgets-can preserve performance in well-structured imaging tasks, severe
degradation often occurs under strict privacy, particularly in underrepresented
or complex modalities. Furthermore, privacy-induced performance gaps
disproportionately affect demographic subgroups, with fairness impacts varying
by data type and task. A small subset of studies explicitly addresses these
tradeoffs through subgroup analysis or fairness metrics, but most omit them
entirely. Beyond DP-SGD, emerging approaches leverage alternative mechanisms,
generative models, and hybrid federated designs, though reporting remains
inconsistent. We conclude by outlining key gaps in fairness auditing,
standardization, and evaluation protocols, offering guidance for future work
toward equitable and clinically robust privacy-preserving DL systems in
medicine.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.00476v2">Towards Graph-Based Privacy-Preserving Federated Learning: ModelNet -- A
  ResNet-based Model Classification Dataset</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-05-31T08:53:16Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Abhisek Ray, Lukas Esterle</p>
    <p><b>Summary:</b> Federated Learning (FL) has emerged as a powerful paradigm for training
machine learning models across distributed data sources while preserving data
locality. However, the privacy of local data is always a pivotal concern and
has received a lot of attention in recent research on the FL regime. Moreover,
the lack of domain heterogeneity and client-specific segregation in the
benchmarks remains a critical bottleneck for rigorous evaluation. In this
paper, we introduce ModelNet, a novel image classification dataset constructed
from the embeddings extracted from a pre-trained ResNet50 model. First, we
modify the CIFAR100 dataset into three client-specific variants, considering
three domain heterogeneities (homogeneous, heterogeneous, and random).
Subsequently, we train each client-specific subset of all three variants on the
pre-trained ResNet50 model to save model parameters. In addition to
multi-domain image data, we propose a new hypothesis to define the FL algorithm
that can access the anonymized model parameters to preserve the local privacy
in a more effective manner compared to existing ones. ModelNet is designed to
simulate realistic FL settings by incorporating non-IID data distributions and
client diversity design principles in the mainframe for both conventional and
futuristic graph-driven FL algorithms. The three variants are ModelNet-S,
ModelNet-D, and ModelNet-R, which are based on homogeneous, heterogeneous, and
random data settings, respectively. To the best of our knowledge, we are the
first to propose a cross-environment client-specific FL dataset along with the
graph-based variant. Extensive experiments based on domain shifts and
aggregation strategies show the effectiveness of the above variants, making it
a practical benchmark for classical and graph-based FL research. The dataset
and related code are available online.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.02038v1">Blockchain Powered Edge Intelligence for U-Healthcare in Privacy
  Critical and Time Sensitive Environment</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-05-31T06:58:52Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anum Nawaz, Hafiz Humza Mahmood Ramzan, Xianjia Yu, Zhuo Zou, Tomi Westerlund</p>
    <p><b>Summary:</b> Edge Intelligence (EI) serves as a critical enabler for privacy-preserving
systems by providing AI-empowered computation and distributed caching services
at the edge, thereby minimizing latency and enhancing data privacy. The
integration of blockchain technology further augments EI frameworks by ensuring
transactional transparency, auditability, and system-wide reliability through a
decentralized network model. However, the operational architecture of such
systems introduces inherent vulnerabilities, particularly due to the extensive
data interactions between edge gateways (EGs) and the distributed nature of
information storage during service provisioning. To address these challenges,
we propose an autonomous computing model along with its interaction topologies
tailored for privacy-critical and time-sensitive health applications. The
system supports continuous monitoring, real-time alert notifications, disease
detection, and robust data processing and aggregation. It also includes a data
transaction handler and mechanisms for ensuring privacy at the EGs. Moreover, a
resource-efficient one-dimensional convolutional neural network (1D-CNN) is
proposed for the multiclass classification of arrhythmia, enabling accurate and
real-time analysis of constrained EGs. Furthermore, a secure access scheme is
defined to manage both off-chain and on-chain data sharing and storage. To
validate the proposed model, comprehensive security, performance, and cost
analyses are conducted, demonstrating the efficiency and reliability of the
fine-grained access control scheme.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.00416v1">Blockchain-Enabled Privacy-Preserving Second-Order Federated Edge
  Learning in Personalized Healthcare</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2025-05-31T06:41:04Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anum Nawaz, Muhammad Irfan, Xianjia Yu, Zhuo Zou, Tomi Westerlund</p>
    <p><b>Summary:</b> Federated learning (FL) has attracted increasing attention to mitigate
security and privacy challenges in traditional cloud-centric machine learning
models specifically in healthcare ecosystems. FL methodologies enable the
training of global models through localized policies, allowing independent
operations at the edge clients' level. Conventional first-order FL approaches
face several challenges in personalized model training due to heterogeneous
non-independent and identically distributed (non-iid) data of each edge client.
Recently, second-order FL approaches maintain the stability and consistency of
non-iid datasets while improving personalized model training. This study
proposes and develops a verifiable and auditable optimized second-order FL
framework BFEL (blockchain-enhanced federated edge learning) based on optimized
FedCurv for personalized healthcare systems. FedCurv incorporates information
about the importance of each parameter to each client's task (through Fisher
Information Matrix) which helps to preserve client-specific knowledge and
reduce model drift during aggregation. Moreover, it minimizes communication
rounds required to achieve a target precision convergence for each edge client
while effectively managing personalized training on non-iid and heterogeneous
data. The incorporation of Ethereum-based model aggregation ensures trust,
verifiability, and auditability while public key encryption enhances privacy
and security. Experimental results of federated CNNs and MLPs utilizing Mnist,
Cifar-10, and PathMnist demonstrate the high efficiency and scalability of the
proposed framework.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.00158v1">Privacy Amplification in Differentially Private Zeroth-Order
  Optimization with Hidden States</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-05-30T18:55:32Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Eli Chien, Wei-Ning Chen, Pan Li</p>
    <p><b>Summary:</b> Zeroth-order optimization has emerged as a promising approach for fine-tuning
large language models on domain-specific data, particularly under differential
privacy (DP) and memory constraints. While first-order methods have been
extensively studied from a privacy perspective, the privacy analysis and
algorithmic design for zeroth-order methods remain significantly underexplored.
A critical open question concerns hidden-state DP analysis: although convergent
privacy bounds are known for first-order methods, it has remained unclear
whether similar guarantees can be established for zeroth-order methods. In this
work, we provide an affirmative answer by proving a convergent DP bound for
zeroth-order optimization. Our analysis generalizes the celebrated privacy
amplification-by-iteration framework to the setting of smooth loss functions in
zeroth-order optimization. Furthermore, it induces better DP zeroth-order
algorithmic designs that are previously unknown to the literature.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.00124v1">randextract: a Reference Library to Test and Validate Privacy
  Amplification Implementations</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-05-30T18:01:50Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Iyán Méndez Veiga, Esther Hänggi</p>
    <p><b>Summary:</b> Quantum cryptographic protocols do not rely only on quantum-physical
resources, they also require reliable classical communication and computation.
In particular, the secrecy of any quantum key distribution protocol critically
depends on the correct execution of the privacy amplification step. This is a
classical post-processing procedure transforming a partially secret bit string,
known to be somewhat correlated with an adversary, into a shorter bit string
that is close to uniform and independent of the adversary's knowledge. It is
typically implemented using randomness extractors. Standardization efforts in
quantum cryptography have focused on the security of physical devices and
quantum operations. Future efforts should also consider all algorithms used in
classical post-processing, especially in privacy amplification, due to its
critical role in ensuring the final security of the key. We present
randextract, a reference library to test and validate privacy amplification
implementations.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2505.24603v2">The Gaussian Mixing Mechanism: Renyi Differential Privacy via Gaussian
  Sketches</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-05-30T13:52:48Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Omri Lev, Vishwak Srinivasan, Moshe Shenfeld, Katrina Ligett, Ayush Sekhari, Ashia C. Wilson</p>
    <p><b>Summary:</b> Gaussian sketching, which consists of pre-multiplying the data with a random
Gaussian matrix, is a widely used technique for multiple problems in data
science and machine learning, with applications spanning computationally
efficient optimization, coded computing, and federated learning. This operation
also provides differential privacy guarantees due to its inherent randomness.
In this work, we revisit this operation through the lens of Renyi Differential
Privacy (RDP), providing a refined privacy analysis that yields significantly
tighter bounds than prior results. We then demonstrate how this improved
analysis leads to performance improvement in different linear regression
settings, establishing theoretical utility guarantees. Empirically, our methods
improve performance across multiple datasets and, in several cases, reduce
runtime.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.00100v2">Children's Voice Privacy: First Steps And Emerging Challenges</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762"> <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-05-30T13:21:18Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Ajinkya Kulkarni, Francisco Teixeira, Enno Hermann, Thomas Rolland, Isabel Trancoso, Mathew Magimai Doss</p>
    <p><b>Summary:</b> Children are one of the most under-represented groups in speech technologies,
as well as one of the most vulnerable in terms of privacy. Despite this,
anonymization techniques targeting this population have received little
attention. In this study, we seek to bridge this gap, and establish a baseline
for the use of voice anonymization techniques designed for adult speech when
applied to children's voices. Such an evaluation is essential, as children's
speech presents a distinct set of challenges when compared to that of adults.
This study comprises three children's datasets, six anonymization methods, and
objective and subjective utility metrics for evaluation. Our results show that
existing systems for adults are still able to protect children's voice privacy,
but suffer from much higher utility degradation. In addition, our subjective
study displays the challenges of automatic evaluation methods for speech
quality in children's speech, highlighting the need for further research.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.02030v1">Adaptive Privacy-Preserving SSD</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> 
  <p><b>Published on:</b> 2025-05-30T13:08:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Na Young Ahn, Dong Hoon Lee</p>
    <p><b>Summary:</b> Data remanence in NAND flash complicates complete deletion on IoT SSDs. We
design an adaptive architecture offering four privacy levels (PL0-PL3) that
select among address, data, and parity deletion techniques. Quantitative
analysis balances efficacy, latency, endurance, and cost. Machine-learning
adjusts levels contextually, boosting privacy with negligible performance
overhead and complexity.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2505.23655v3">Keyed Chaotic Dynamics for Privacy-Preserving Neural Inference</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B">  
  <p><b>Published on:</b> 2025-05-29T17:05:42Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Peter David Fagan</p>
    <p><b>Summary:</b> Neural network inference typically operates on raw input data, increasing the
risk of exposure during preprocessing and inference. Moreover, neural
architectures lack efficient built-in mechanisms for directly authenticating
input data. This work introduces a novel encryption method for ensuring the
security of neural inference. By constructing key-conditioned chaotic graph
dynamical systems, we enable the encryption and decryption of real-valued
tensors within the neural architecture. The proposed dynamical systems are
particularly suited to encryption due to their sensitivity to initial
conditions and their capacity to produce complex, key-dependent nonlinear
transformations from compact rules. This work establishes a paradigm for
securing neural inference and opens new avenues for research on the application
of graph dynamical systems in neural network security.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.00060v1">Comparative analysis of privacy-preserving open-source LLMs regarding
  extraction of diagnostic information from clinical CMR imaging reports</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computers and Society-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-05-29T11:25:10Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sina Amirrajab, Volker Vehof, Michael Bietenbeck, Ali Yilmaz</p>
    <p><b>Summary:</b> Purpose: We investigated the utilization of privacy-preserving,
locally-deployed, open-source Large Language Models (LLMs) to extract
diagnostic information from free-text cardiovascular magnetic resonance (CMR)
reports. Materials and Methods: We evaluated nine open-source LLMs on their
ability to identify diagnoses and classify patients into various cardiac
diagnostic categories based on descriptive findings in 109 clinical CMR
reports. Performance was quantified using standard classification metrics
including accuracy, precision, recall, and F1 score. We also employed confusion
matrices to examine patterns of misclassification across models. Results: Most
open-source LLMs demonstrated exceptional performance in classifying reports
into different diagnostic categories. Google's Gemma2 model achieved the
highest average F1 score of 0.98, followed by Qwen2.5:32B and DeepseekR1-32B
with F1 scores of 0.96 and 0.95, respectively. All other evaluated models
attained average scores above 0.93, with Mistral and DeepseekR1-7B being the
only exceptions. The top four LLMs outperformed our board-certified
cardiologist (F1 score of 0.94) across all evaluation metrics in analyzing CMR
reports. Conclusion: Our findings demonstrate the feasibility of implementing
open-source, privacy-preserving LLMs in clinical settings for automated
analysis of imaging reports, enabling accurate, fast and resource-efficient
diagnostic categorization.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2505.23031v1">Towards Privacy-Preserving Fine-Grained Visual Classification via
  Hierarchical Learning from Label Proportions</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computer Vision and Pattern Recognition-F9C80E">
  <p><b>Published on:</b> 2025-05-29T03:18:25Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Jinyi Chang, Dongliang Chang, Lei Chen, Bingyao Yu, Zhanyu Ma</p>
    <p><b>Summary:</b> In recent years, Fine-Grained Visual Classification (FGVC) has achieved
impressive recognition accuracy, despite minimal inter-class variations.
However, existing methods heavily rely on instance-level labels, making them
impractical in privacy-sensitive scenarios such as medical image analysis. This
paper aims to enable accurate fine-grained recognition without direct access to
instance labels. To achieve this, we leverage the Learning from Label
Proportions (LLP) paradigm, which requires only bag-level labels for efficient
training. Unlike existing LLP-based methods, our framework explicitly exploits
the hierarchical nature of fine-grained datasets, enabling progressive feature
granularity refinement and improving classification accuracy. We propose
Learning from Hierarchical Fine-Grained Label Proportions (LHFGLP), a framework
that incorporates Unrolled Hierarchical Fine-Grained Sparse Dictionary
Learning, transforming handcrafted iterative approximation into learnable
network optimization. Additionally, our proposed Hierarchical Proportion Loss
provides hierarchical supervision, further enhancing classification
performance. Experiments on three widely-used fine-grained datasets, structured
in a bag-based manner, demonstrate that our framework consistently outperforms
existing LLP-based methods. We will release our code and datasets to foster
further research in privacy-preserving fine-grained classification.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2505.23849v1">CADRE: Customizable Assurance of Data Readiness in Privacy-Preserving
  Federated Learning</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Artificial Intelligence-662E9B"> <img alt="Category Badge" src="https://img.shields.io/badge/Machine Learning-662E9B">
  <p><b>Published on:</b> 2025-05-28T21:24:46Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Kaveen Hiniduma, Zilinghan Li, Aditya Sinha, Ravi Madduri, Suren Byna</p>
    <p><b>Summary:</b> Privacy-Preserving Federated Learning (PPFL) is a decentralized machine
learning approach where multiple clients train a model collaboratively. PPFL
preserves privacy and security of the client's data by not exchanging it.
However, ensuring that data at each client is of high quality and ready for
federated learning (FL) is a challenge due to restricted data access. In this
paper, we introduce CADRE (Customizable Assurance of Data REadiness) for FL, a
novel framework that allows users to define custom data readiness (DR)
standards, metrics, rules, and remedies tailored to specific FL tasks. Our
framework generates comprehensive DR reports based on the user-defined metrics,
rules, and remedies to ensure datasets are optimally prepared for FL while
preserving privacy. We demonstrate the framework's practical application by
integrating it into an existing PPFL framework. We conducted experiments across
six diverse datasets, addressing seven different DR issues. The results
illustrate the framework's versatility and effectiveness in ensuring DR across
various dimensions, including data quality, privacy, and fairness. This
approach enhances the performance and reliability of FL models as well as
utilizes valuable resources by identifying and addressing data-related issues
before the training phase.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2506.06321v1">On the Interplay of Privacy, Persuasion and Quantization</a></h3>
   <img alt="Category Badge" src="https://img.shields.io/badge/Computer Science and Game Theory-5BC0EB"> <img alt="Category Badge" src="https://img.shields.io/badge/Information Theory-D91E36"> <img alt="Category Badge" src="https://img.shields.io/badge/Systems and Control-D91E36">  
  <p><b>Published on:</b> 2025-05-28T19:44:31Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Anju Anand, Emrah Akyol</p>
    <p><b>Summary:</b> We develop a communication-theoretic framework for privacy-aware and
resilient decision making in cyber-physical systems under misaligned objectives
between the encoder and the decoder. The encoder observes two correlated
signals ($X$,$\theta$) and transmits a finite-rate message $Z$ to aid a
legitimate controller (the decoder) in estimating $X+\theta$, while an
eavesdropper intercepts $Z$ to infer the private parameter $\theta$. Unlike
conventional setups where encoder and decoder share a common MSE objective,
here the encoder minimizes a Lagrangian that balances legitimate control
fidelity and the privacy leakage about $\theta$. In contrast, the decoder's
goal is purely to minimize its own estimation error without regard for privacy.
We analyze fully, partially, and non-revealing strategies that arise from this
conflict, and characterize optimal linear encoders when the rate constraints
are lifted. For finite-rate channels, we employ gradient-based methods to
compute the optimal controllers. Numerical experiments illustrate how tuning
the privacy parameter shapes the trade-off between control performance and
resilience against unauthorized inferences.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2505.22447v1">Privacy-preserving Prompt Personalization in Federated Learning for
  Multimodal Large Language Models</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-05-28T15:09:56Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Sizai Hou, Songze Li, Baturalp Buyukates</p>
    <p><b>Summary:</b> Prompt learning is a crucial technique for adapting pre-trained multimodal
language models (MLLMs) to user tasks. Federated prompt personalization (FPP)
is further developed to address data heterogeneity and local overfitting,
however, it exposes personalized prompts - valuable intellectual assets - to
privacy risks like prompt stealing or membership inference attacks.
Widely-adopted techniques like differential privacy add noise to prompts,
whereas degrading personalization performance. We propose SecFPP, a secure FPP
protocol harmonizing generalization, personalization, and privacy guarantees.
SecFPP employs hierarchical prompt adaptation with domain-level and class-level
components to handle multi-granular data imbalance. For privacy, it uses a
novel secret-sharing-based adaptive clustering algorithm for domain-level
adaptation while keeping class-level components private. While theoretically
and empirically secure, SecFPP achieves state-of-the-art accuracy under severe
heterogeneity in data distribution. Extensive experiments show it significantly
outperforms both non-private and privacy-preserving baselines, offering a
superior privacy-performance trade-off.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2505.22234v1">Evolution of repositories and privacy laws: commit activities in the
  GDPR and CCPA era</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Software Engineering-D91E36">
  <p><b>Published on:</b> 2025-05-28T11:10:58Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Georgia M. Kapitsaki, Maria Papoutsoglou</p>
    <p><b>Summary:</b> Free and open source software has gained a lot of momentum in the industry
and the research community. The latest advances in privacy legislation,
including the EU General Data Protection Regulation (GDPR) and the California
Consumer Privacy Act (CCPA), have forced the community to pay special attention
to users' data privacy. The main aim of this work is to examine software
repositories that are acting on privacy laws. We have collected commit data
from GitHub repositories in order to understand indications on main data
privacy laws (GDPR, CCPA, CPRA, UK DPA) in the last years. Via an automated
process, we analyzed 37,213 commits from 12,391 repositories since 2016,
whereas 594 commits from the 70 most popular repositories of the dataset were
manually analyzed. We observe that most commits were performed on the year the
law came into effect and privacy relevant terms appear in the commit messages,
whereas reference to specific data privacy user rights is scarce. The study
showed that more educational activities on data privacy user rights are needed,
as well as tools for privacy recommendations, whereas verifying actual
compliance via source code execution is a useful direction for software
engineering researchers.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2505.22061v1">Safeguarding Privacy of Retrieval Data against Membership Inference
  Attacks: Is This Query Too Close to Home?</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Computation and Language-04E762">
  <p><b>Published on:</b> 2025-05-28T07:35:07Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Yujin Choi, Youngjoo Park, Junyoung Byun, Jaewook Lee, Jinseong Park</p>
    <p><b>Summary:</b> Retrieval-augmented generation (RAG) mitigates the hallucination problem in
large language models (LLMs) and has proven effective for specific,
personalized applications. However, passing private retrieved documents
directly to LLMs introduces vulnerability to membership inference attacks
(MIAs), which try to determine whether the target datum exists in the private
external database or not. Based on the insight that MIA queries typically
exhibit high similarity to only one target document, we introduce Mirabel, a
similarity-based MIA detection framework designed for the RAG system. With the
proposed Mirabel, we show that simple detect-and-hide strategies can
successfully obfuscate attackers, maintain data utility, and remain
system-agnostic. We experimentally prove its detection and defense against
various state-of-the-art MIA methods and its adaptability to existing private
RAG systems.</p>
  </details>
</div>


<div class="arxiv-entry">
  <h3><a href="http://arxiv.org/abs/2505.23825v1">Privacy-Preserving Inconsistency Measurement</a></h3>
  <img alt="Category Badge" src="https://img.shields.io/badge/Cryptography and Security-D91E36">
  <p><b>Published on:</b> 2025-05-28T06:24:33Z</p>
  <details>
    <summary>More Details</summary>
    <p><b>Authors:</b> Carl Corea, Timotheus Kampik, Nico Potyka</p>
    <p><b>Summary:</b> We investigate a new form of (privacy-preserving) inconsistency measurement
for multi-party communication. Intuitively, for two knowledge bases K_A, K_B
(of two agents A, B), our results allow to quantitatively assess the degree of
inconsistency for K_A U K_B without having to reveal the actual contents of the
knowledge bases. Using secure multi-party computation (SMPC) and cryptographic
protocols, we develop two concrete methods for this use-case and show that they
satisfy important properties of SMPC protocols -- notably, input privacy, i.e.,
jointly computing the inconsistency degree without revealing the inputs.</p>
  </details>
</div>

