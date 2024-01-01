
<details>
<summary>Stochastic Privacy (Published on: 2014-04-22T10:55:19Z)</summary>
**Link**: [http://arxiv.org/abs/1404.5454v1](http://arxiv.org/abs/1404.5454v1)
**Updated**: 2014-04-22T10:55:19Z
**Authors**: Adish Singla, Eric Horvitz, Ece Kamar, Ryen White
**Summary**: Online services such as web search and e-commerce applications typically rely
on the collection of data about users, including details of their activities on
the web. Such personal data is used to enhance the quality of service via
personalization of content and to maximize revenues via better targeting of
advertisements and deeper engagement of users on sites. To date, service
providers have largely followed the approach of either requiring or requesting
consent for opting-in to share their data. Users may be willing to share
private information in return for better quality of service or for incentives,
or in return for assurances about the nature and extend of the logging of data.
We introduce \emph{stochastic privacy}, a new approach to privacy centering on
a simple concept: A guarantee is provided to users about the upper-bound on the
probability that their personal data will be used. Such a probability, which we
refer to as \emph{privacy risk}, can be assessed by users as a preference or
communicated as a policy by a service provider. Service providers can work to
personalize and to optimize revenues in accordance with preferences about
privacy risk. We present procedures, proofs, and an overall system for
maximizing the quality of services, while respecting bounds on allowable or
communicated privacy risk. We demonstrate the methodology with a case study and
evaluation of the procedures applied to web search personalization. We show how
we can achieve near-optimal utility of accessing information with provable
guarantees on the probability of sharing data.
</details>


<details>
<summary>Privacy Games (Published on: 2014-10-07T21:31:59Z)</summary>
**Link**: [http://arxiv.org/abs/1410.1920v1](http://arxiv.org/abs/1410.1920v1)
**Updated**: 2014-10-07T21:31:59Z
**Authors**: Yiling Chen, Or Sheffet, Salil Vadhan
**Summary**: The problem of analyzing the effect of privacy concerns on the behavior of
selfish utility-maximizing agents has received much attention lately. Privacy
concerns are often modeled by altering the utility functions of agents to
consider also their privacy loss. Such privacy aware agents prefer to take a
randomized strategy even in very simple games in which non-privacy aware agents
play pure strategies. In some cases, the behavior of privacy aware agents
follows the framework of Randomized Response, a well-known mechanism that
preserves differential privacy.
  Our work is aimed at better understanding the behavior of agents in settings
where their privacy concerns are explicitly given. We consider a toy setting
where agent A, in an attempt to discover the secret type of agent B, offers B a
gift that one type of B agent likes and the other type dislikes. As opposed to
previous works, B's incentive to keep her type a secret isn't the result of
"hardwiring" B's utility function to consider privacy, but rather takes the
form of a payment between B and A. We investigate three different types of
payment functions and analyze B's behavior in each of the resulting games. As
we show, under some payments, B's behavior is very different than the behavior
of agents with hardwired privacy concerns and might even be deterministic.
Under a different payment we show that B's BNE strategy does fall into the
framework of Randomized Response.
</details>


<details>
<summary>Inverse Privacy (Published on: 2015-10-12T14:44:05Z)</summary>
**Link**: [http://arxiv.org/abs/1510.03311v1](http://arxiv.org/abs/1510.03311v1)
**Updated**: 2015-10-12T14:44:05Z
**Authors**: Yuri Gurevich, Efim Hudis, Jeannette M. Wing
**Summary**: An item of your personal information is inversely private if some party has
access to it but you do not. We analyze the provenance of inversely private
information and its rise to dominance over other kinds of personal information.
In a nutshell, the inverse privacy problem is unjustified inaccessibility to
you of your inversely private information. We argue that the inverse privacy
problem has a market-based solution.
</details>


<details>
<summary>Privacy Patterns (Published on: 2016-12-05T21:19:24Z)</summary>
**Link**: [http://arxiv.org/abs/1612.01553v1](http://arxiv.org/abs/1612.01553v1)
**Updated**: 2016-12-05T21:19:24Z
**Authors**: Clark Thomborson
**Summary**: Inspired by the design patterns of object-oriented software architecture, we
offer an initial set of "privacy patterns". Our intent is to describe the most
important ways in which software systems can offer privacy to their
stakeholders. We express our privacy patterns as class diagrams in the UML
(Universal Modelling Language), because this is a commonly-used language for
expressing the high-level architecture of an object-oriented system. In this
initial set of privacy patterns, we sketch how each of Westin's four states of
privacy can be implemented in a software system. In addition to Westin's states
of Solitude, Intimacy, Anonymity, and Reserve, we develop a privacy pattern for
an institutionalised form of Intimacy which we call Confidence.
</details>


<details>
<summary>Privacy protocols (Published on: 2019-04-11T05:37:58Z)</summary>
**Link**: [http://arxiv.org/abs/1904.05540v1](http://arxiv.org/abs/1904.05540v1)
**Updated**: 2019-04-11T05:37:58Z
**Authors**: Jason Castiglione, Dusko Pavlovic, Peter-Michael Seidel
**Summary**: Security protocols enable secure communication over insecure channels.
Privacy protocols enable private interactions over secure channels. Security
protocols set up secure channels using cryptographic primitives. Privacy
protocols set up private channels using secure channels. But just like some
security protocols can be broken without breaking the underlying cryptography,
some privacy protocols can be broken without breaking the underlying security.
Such privacy attacks have been used to leverage e-commerce against targeted
advertising from the outset; but their depth and scope became apparent only
with the overwhelming advent of influence campaigns in politics. The blurred
boundaries between privacy protocols and privacy attacks present a new
challenge for protocol analysis. Covert channels turn out to be concealed not
only below overt channels, but also above: subversions, and the level-below
attacks are supplemented by sublimations and the level-above attacks.
</details>


<details>
<summary>Noiseless Privacy (Published on: 2019-10-29T01:09:26Z)</summary>
**Link**: [http://arxiv.org/abs/1910.13027v1](http://arxiv.org/abs/1910.13027v1)
**Updated**: 2019-10-29T01:09:26Z
**Authors**: Farhad Farokhi
**Summary**: In this paper, we define noiseless privacy, as a non-stochastic rival to
differential privacy, requiring that the outputs of a mechanism (i.e., function
composition of a privacy-preserving mapping and a query) can attain only a few
values while varying the data of an individual (the logarithm of the number of
the distinct values is bounded by the privacy budget). Therefore, the output of
the mechanism is not fully informative of the data of the individuals in the
dataset. We prove several guarantees for noiselessly-private mechanisms. The
information content of the output about the data of an individual, even if an
adversary knows all the other entries of the private dataset, is bounded by the
privacy budget. The zero-error capacity of memory-less channels using
noiselessly private mechanisms for transmission is upper bounded by the privacy
budget. The performance of a non-stochastic hypothesis-testing adversary is
bounded again by the privacy budget. Finally, assuming that an adversary has
access to a stochastic prior on the dataset, we prove that the estimation error
of the adversary for individual entries of the dataset is lower bounded by a
decreasing function of the privacy budget. In this case, we also show that the
maximal information leakage is bounded by the privacy budget. In addition to
privacy guarantees, we prove that noiselessly-private mechanisms admit
composition theorem and post-processing does not weaken their privacy
guarantees. We prove that quantization operators can ensure noiseless privacy
if the number of quantization levels is appropriately selected based on the
sensitivity of the query and the privacy budget. Finally, we illustrate the
privacy merits of noiseless privacy using multiple datasets in energy and
transport.
</details>


<details>
<summary>Imitation Privacy (Published on: 2020-08-30T20:29:41Z)</summary>
**Link**: [http://arxiv.org/abs/2009.00442v1](http://arxiv.org/abs/2009.00442v1)
**Updated**: 2020-08-30T20:29:41Z
**Authors**: Xun Xian, Xinran Wang, Mingyi Hong, Jie Ding, Reza Ghanadan
**Summary**: In recent years, there have been many cloud-based machine learning services,
where well-trained models are provided to users on a pay-per-query scheme
through a prediction API. The emergence of these services motivates this work,
where we will develop a general notion of model privacy named imitation
privacy. We show the broad applicability of imitation privacy in classical
query-response MLaaS scenarios and new multi-organizational learning scenarios.
We also exemplify the fundamental difference between imitation privacy and the
usual data-level privacy.
</details>


<details>
<summary>XYZ Privacy (Published on: 2017-10-09T21:24:22Z)</summary>
**Link**: [http://arxiv.org/abs/1710.03322v5](http://arxiv.org/abs/1710.03322v5)
**Updated**: 2018-02-21T19:54:24Z
**Authors**: Josh Joy, Dylan Gray, Ciaran McGoldrick, Mario Gerla
**Summary**: Future autonomous vehicles will generate, collect, aggregate and consume
significant volumes of data as key gateway devices in emerging Internet of
Things scenarios. While vehicles are widely accepted as one of the most
challenging mobility contexts in which to achieve effective data
communications, less attention has been paid to the privacy of data emerging
from these vehicles. The quality and usability of such privatized data will lie
at the heart of future safe and efficient transportation solutions.
  In this paper, we present the XYZ Privacy mechanism. XYZ Privacy is to our
knowledge the first such mechanism that enables data creators to submit
multiple contradictory responses to a query, whilst preserving utility measured
as the absolute error from the actual original data. The functionalities are
achieved in both a scalable and secure fashion. For instance, individual
location data can be obfuscated while preserving utility, thereby enabling the
scheme to transparently integrate with existing systems (e.g. Waze). A new
cryptographic primitive Function Secret Sharing is used to achieve
non-attributable writes and we show an order of magnitude improvement from the
default implementation.
</details>


<details>
<summary>Bistochastic privacy (Published on: 2022-07-08T14:50:31Z)</summary>
**Link**: [http://arxiv.org/abs/2207.03940v1](http://arxiv.org/abs/2207.03940v1)
**Updated**: 2022-07-08T14:50:31Z
**Authors**: Nicolas Ruiz, Josep Domingo-Ferrer
**Summary**: We introduce a new privacy model relying on bistochastic matrices, that is,
matrices whose components are nonnegative and sum to 1 both row-wise and
column-wise. This class of matrices is used to both define privacy guarantees
and a tool to apply protection on a data set. The bistochasticity assumption
happens to connect several fields of the privacy literature, including the two
most popular models, k-anonymity and differential privacy. Moreover, it
establishes a bridge with information theory, which simplifies the thorny issue
of evaluating the utility of a protected data set. Bistochastic privacy also
clarifies the trade-off between protection and utility by using bits, which can
be viewed as a natural currency to comprehend and operationalize this
trade-off, in the same way than bits are used in information theory to capture
uncertainty. A discussion on the suitable parameterization of bistochastic
matrices to achieve the privacy guarantees of this new model is also provided.
</details>


<details>
<summary>Transparent Privacy is Principled Privacy (Published on: 2020-06-15T16:30:29Z)</summary>
**Link**: [http://arxiv.org/abs/2006.08522v3](http://arxiv.org/abs/2006.08522v3)
**Updated**: 2022-09-18T18:02:14Z
**Authors**: Ruobin Gong
**Summary**: In a technical treatment, this article establishes the necessity of
transparent privacy for drawing unbiased statistical inference for a wide range
of scientific questions. Transparency is a distinct feature enjoyed by
differential privacy: the probabilistic mechanism with which the data are
privatized can be made public without sabotaging the privacy guarantee.
Uncertainty due to transparent privacy may be conceived as a dynamic and
controllable component from the total survey error perspective. As the 2020
U.S. Decennial Census adopts differential privacy, constraints imposed on the
privatized data products through optimization constitute a threat to
transparency and result in limited statistical usability. Transparent privacy
presents a viable path toward principled inference from privatized data
releases, and shows great promise toward improved reproducibility,
accountability, and public trust in modern data curation.
</details>


<details>
<summary>Randomized Privacy Budget Differential Privacy (Published on: 2022-09-03T17:33:49Z)</summary>
**Link**: [http://arxiv.org/abs/2209.01468v1](http://arxiv.org/abs/2209.01468v1)
**Updated**: 2022-09-03T17:33:49Z
**Authors**: Meisam Mohammady
**Summary**: While pursuing better utility by discovering knowledge from the data,
individual's privacy may be compromised during an analysis. To that end,
differential privacy has been widely recognized as the state-of-the-art privacy
notion. By requiring the presence of any individual's data in the input to only
marginally affect the distribution over the output, differential privacy
provides strong protection against adversaries in possession of arbitrary
background. However, the privacy constraints (e.g., the degree of
randomization) imposed by differential privacy may render the released data
less useful for analysis, the fundamental trade-off between privacy and utility
(i.e., analysis accuracy) has attracted significant attention in various
settings. In this report we present DP mechanisms with randomized parameters,
i.e., randomized privacy budget, and formally analyze its privacy and utility
and demonstrate that randomizing privacy budget in DP mechanisms will boost the
accuracy in a humongous scale.
</details>


<details>
<summary>Smart Meter Privacy: A Utility-Privacy Framework (Published on: 2011-08-10T18:14:16Z)</summary>
**Link**: [http://arxiv.org/abs/1108.2234v1](http://arxiv.org/abs/1108.2234v1)
**Updated**: 2011-08-10T18:14:16Z
**Authors**: S. Raj Rajagopalan, Lalitha Sankar, Soheil Mohajer, H. Vincent Poor
**Summary**: End-user privacy in smart meter measurements is a well-known challenge in the
smart grid. The solutions offered thus far have been tied to specific
technologies such as batteries or assumptions on data usage. Existing solutions
have also not quantified the loss of benefit (utility) that results from any
such privacy-preserving approach. Using tools from information theory, a new
framework is presented that abstracts both the privacy and the utility
requirements of smart meter data. This leads to a novel privacy-utility
tradeoff problem with minimal assumptions that is tractable. Specifically for a
stationary Gaussian Markov model of the electricity load, it is shown that the
optimal utility-and-privacy preserving solution requires filtering out
frequency components that are low in power, and this approach appears to
encompass most of the proposed privacy approaches.
</details>


<details>
<summary>Participatory Privacy: Enabling Privacy in Participatory Sensing (Published on: 2012-01-20T20:15:53Z)</summary>
**Link**: [http://arxiv.org/abs/1201.4376v2](http://arxiv.org/abs/1201.4376v2)
**Updated**: 2013-02-08T03:22:25Z
**Authors**: Emiliano De Cristofaro, Claudio Soriente
**Summary**: Participatory Sensing is an emerging computing paradigm that enables the
distributed collection of data by self-selected participants. It allows the
increasing number of mobile phone users to share local knowledge acquired by
their sensor-equipped devices, e.g., to monitor temperature, pollution level or
consumer pricing information. While research initiatives and prototypes
proliferate, their real-world impact is often bounded to comprehensive user
participation. If users have no incentive, or feel that their privacy might be
endangered, it is likely that they will not participate. In this article, we
focus on privacy protection in Participatory Sensing and introduce a suitable
privacy-enhanced infrastructure. First, we provide a set of definitions of
privacy requirements for both data producers (i.e., users providing sensed
information) and consumers (i.e., applications accessing the data). Then, we
propose an efficient solution designed for mobile phone users, which incurs
very low overhead. Finally, we discuss a number of open problems and possible
research directions.
</details>


<details>
<summary>Connecting Robust Shuffle Privacy and Pan-Privacy (Published on: 2020-04-20T17:58:14Z)</summary>
**Link**: [http://arxiv.org/abs/2004.09481v4](http://arxiv.org/abs/2004.09481v4)
**Updated**: 2020-08-12T03:45:00Z
**Authors**: Victor Balcer, Albert Cheu, Matthew Joseph, Jieming Mao
**Summary**: In the \emph{shuffle model} of differential privacy, data-holding users send
randomized messages to a secure shuffler, the shuffler permutes the messages,
and the resulting collection of messages must be differentially private with
regard to user data. In the \emph{pan-private} model, an algorithm processes a
stream of data while maintaining an internal state that is differentially
private with regard to the stream data. We give evidence connecting these two
apparently different models.
  Our results focus on \emph{robustly} shuffle private protocols, whose privacy
guarantees are not greatly affected by malicious users. First, we give robustly
shuffle private protocols and upper bounds for counting distinct elements and
uniformity testing. Second, we use pan-private lower bounds to prove robustly
shuffle private lower bounds for both problems. Focusing on the dependence on
the domain size $k$, we find that robust approximate shuffle privacy and
approximate pan-privacy have additive error $\Theta(\sqrt{k})$ for counting
distinct elements. For uniformity testing, we give a robust approximate shuffle
private protocol with sample complexity $\tilde O(k^{2/3})$ and show that an
$\Omega(k^{2/3})$ dependence is necessary for any robust pure shuffle private
tester. Finally, we show that this connection is useful in both directions: we
give a pan-private adaptation of recent work on shuffle private histograms and
use it to recover further separations between pan-privacy and interactive local
privacy.
</details>


<details>
<summary>Privacy Preserving Face Recognition Utilizing Differential Privacy (Published on: 2020-05-21T06:59:33Z)</summary>
**Link**: [http://arxiv.org/abs/2005.10486v2](http://arxiv.org/abs/2005.10486v2)
**Updated**: 2020-07-04T14:04:25Z
**Authors**: M. A. P. Chamikara, P. Bertok, I. Khalil, D. Liu, S. Camtepe
**Summary**: Facial recognition technologies are implemented in many areas, including but
not limited to, citizen surveillance, crime control, activity monitoring, and
facial expression evaluation. However, processing biometric information is a
resource-intensive task that often involves third-party servers, which can be
accessed by adversaries with malicious intent. Biometric information delivered
to untrusted third-party servers in an uncontrolled manner can be considered a
significant privacy leak (i.e. uncontrolled information release) as biometrics
can be correlated with sensitive data such as healthcare or financial records.
In this paper, we propose a privacy-preserving technique for "controlled
information release", where we disguise an original face image and prevent
leakage of the biometric features while identifying a person. We introduce a
new privacy-preserving face recognition protocol named PEEP (Privacy using
EigEnface Perturbation) that utilizes local differential privacy. PEEP applies
perturbation to Eigenfaces utilizing differential privacy and stores only the
perturbed data in the third-party servers to run a standard Eigenface
recognition algorithm. As a result, the trained model will not be vulnerable to
privacy attacks such as membership inference and model memorization attacks.
Our experiments show that PEEP exhibits a classification accuracy of around 70%
- 90% under standard privacy settings.
</details>


<details>
<summary>Privacy-Aware Eye Tracking Using Differential Privacy (Published on: 2018-12-19T15:10:05Z)</summary>
**Link**: [http://arxiv.org/abs/1812.08000v3](http://arxiv.org/abs/1812.08000v3)
**Updated**: 2019-04-29T21:19:15Z
**Authors**: Julian Steil, Inken Hagestedt, Michael Xuelin Huang, Andreas Bulling
**Summary**: With eye tracking being increasingly integrated into virtual and augmented
reality (VR/AR) head-mounted displays, preserving users' privacy is an ever
more important, yet under-explored, topic in the eye tracking community. We
report a large-scale online survey (N=124) on privacy aspects of eye tracking
that provides the first comprehensive account of with whom, for which services,
and to what extent users are willing to share their gaze data. Using these
insights, we design a privacy-aware VR interface that uses differential
privacy, which we evaluate on a new 20-participant dataset for two privacy
sensitive tasks: We show that our method can prevent user re-identification and
protect gender information while maintaining high performance for gaze-based
document type classification. Our results highlight the privacy challenges
particular to gaze data and demonstrate that differential privacy is a
potential means to address them. Thus, this paper lays important foundations
for future research on privacy-aware gaze interfaces.
</details>


<details>
<summary>Individual Privacy Accounting with Gaussian Differential Privacy (Published on: 2022-09-30T17:19:40Z)</summary>
**Link**: [http://arxiv.org/abs/2209.15596v2](http://arxiv.org/abs/2209.15596v2)
**Updated**: 2023-08-24T14:00:18Z
**Authors**: Antti Koskela, Marlon Tobaben, Antti Honkela
**Summary**: Individual privacy accounting enables bounding differential privacy (DP) loss
individually for each participant involved in the analysis. This can be
informative as often the individual privacy losses are considerably smaller
than those indicated by the DP bounds that are based on considering worst-case
bounds at each data access. In order to account for the individual privacy
losses in a principled manner, we need a privacy accountant for adaptive
compositions of randomised mechanisms, where the loss incurred at a given data
access is allowed to be smaller than the worst-case loss. This kind of analysis
has been carried out for the R\'enyi differential privacy (RDP) by Feldman and
Zrnic (2021), however not yet for the so-called optimal privacy accountants. We
make first steps in this direction by providing a careful analysis using the
Gaussian differential privacy which gives optimal bounds for the Gaussian
mechanism, one of the most versatile DP mechanisms. This approach is based on
determining a certain supermartingale for the hockey-stick divergence and on
extending the R\'enyi divergence-based fully adaptive composition results by
Feldman and Zrnic. We also consider measuring the individual
$(\varepsilon,\delta)$-privacy losses using the so-called privacy loss
distributions. With the help of the Blackwell theorem, we can then make use of
the RDP analysis to construct an approximative individual
$(\varepsilon,\delta)$-accountant.
</details>


<details>
<summary>Inferential Privacy: From Impossibility to Database Privacy (Published on: 2023-03-14T10:47:40Z)</summary>
**Link**: [http://arxiv.org/abs/2303.07782v1](http://arxiv.org/abs/2303.07782v1)
**Updated**: 2023-03-14T10:47:40Z
**Authors**: Sara Saeidian, Giulia Cervia, Tobias J. Oechtering, Mikael Skoglund
**Summary**: We investigate the possibility of guaranteeing inferential privacy for
mechanisms that release useful information about some data containing sensitive
information, denoted by $X$. We describe a general model of utility and privacy
in which utility is achieved by disclosing the value of low-entropy features of
$X$, while privacy is maintained by keeping high-entropy features of $X$
secret. Adopting this model, we prove that meaningful inferential privacy
guarantees can be obtained, even though this is commonly considered to be
impossible by the well-known result of Dwork and Naor. Then, we specifically
discuss a privacy measure called pointwise maximal leakage (PML) whose
guarantees are of the inferential type. We use PML to show that differential
privacy admits an inferential formulation: it describes the information leaking
about a single entry in a database assuming that every other entry is known,
and considering the worst-case distribution on the data. Moreover, we define
inferential instance privacy (IIP) as a bound on the (non-conditional)
information leaking about a single entry in the database under the worst-case
distribution, and show that it is equivalent to free-lunch privacy. Overall,
our approach to privacy unifies, formalizes, and explains many existing ideas,
e.g., why the informed adversary assumption may lead to underestimating the
information leaking about each entry in the database. Furthermore, insights
obtained from our results suggest general methods for improving privacy
analyses; for example, we argue that smaller privacy parameters can be obtained
by excluding low-entropy prior distributions from protection.
</details>


<details>
<summary>Gaussian Operations and Privacy (Published on: 2005-02-01T15:04:33Z)</summary>
**Link**: [http://arxiv.org/abs/quant-ph/0502010v1](http://arxiv.org/abs/quant-ph/0502010v1)
**Updated**: 2005-02-01T15:04:33Z
**Authors**: Miguel Navascues, Antonio Acin
**Summary**: We consider the possibilities offered by Gaussian states and operations for
two honest parties, Alice and Bob, to obtain privacy against a third
eavesdropping party, Eve. We first extend the security analysis of the protocol
proposed in M. Navascues et al., Phys. Rev. Lett. 94, 010502 (2005). Then, we
prove that a generalized version of this protocol does not allow to distill a
secret key out of bound entangled Gaussian states.
</details>


<details>
<summary>Differential Privacy with Compression (Published on: 2009-01-10T12:12:31Z)</summary>
**Link**: [http://arxiv.org/abs/0901.1365v1](http://arxiv.org/abs/0901.1365v1)
**Updated**: 2009-01-10T12:12:31Z
**Authors**: Shuheng Zhou, Katrina Ligett, Larry Wasserman
**Summary**: This work studies formal utility and privacy guarantees for a simple
multiplicative database transformation, where the data are compressed by a
random linear or affine transformation, reducing the number of data records
substantially, while preserving the number of original input variables. We
provide an analysis framework inspired by a recent concept known as
differential privacy (Dwork 06). Our goal is to show that, despite the general
difficulty of achieving the differential privacy guarantee, it is possible to
publish synthetic data that are useful for a number of common statistical
learning applications. This includes high dimensional sparse regression (Zhou
et al. 07), principal component analysis (PCA), and other statistical measures
(Liu et al. 06) based on the covariance of the initial data.
</details>


<details>
<summary>Privacy in Search Logs (Published on: 2009-04-04T05:49:00Z)</summary>
**Link**: [http://arxiv.org/abs/0904.0682v4](http://arxiv.org/abs/0904.0682v4)
**Updated**: 2011-05-11T22:39:23Z
**Authors**: Michaela Goetz, Ashwin Machanavajjhala, Guozhang Wang, Xiaokui Xiao, Johannes Gehrke
**Summary**: Search engine companies collect the "database of intentions", the histories
of their users' search queries. These search logs are a gold mine for
researchers. Search engine companies, however, are wary of publishing search
logs in order not to disclose sensitive information. In this paper we analyze
algorithms for publishing frequent keywords, queries and clicks of a search
log. We first show how methods that achieve variants of $k$-anonymity are
vulnerable to active attacks. We then demonstrate that the stronger guarantee
ensured by $\epsilon$-differential privacy unfortunately does not provide any
utility for this problem. We then propose an algorithm ZEALOUS and show how to
set its parameters to achieve $(\epsilon,\delta)$-probabilistic privacy. We
also contrast our analysis of ZEALOUS with an analysis by Korolova et al. [17]
that achieves $(\epsilon',\delta')$-indistinguishability. Our paper concludes
with a large experimental study using real applications where we compare
ZEALOUS and previous work that achieves $k$-anonymity in search log publishing.
Our results show that ZEALOUS yields comparable utility to $k-$anonymity while
at the same time achieving much stronger privacy guarantees.
</details>


<details>
<summary>Extensive nonadditivity of privacy (Published on: 2009-04-26T19:02:50Z)</summary>
**Link**: [http://arxiv.org/abs/0904.4050v2](http://arxiv.org/abs/0904.4050v2)
**Updated**: 2009-08-27T12:49:25Z
**Authors**: Graeme Smith, John A. Smolin
**Summary**: Quantum information theory establishes the ultimate limits on communication
and cryptography in terms of channel capacities for various types of
information. The private capacity is particularly important because it
quantifies achievable rates of quantum key distribution. We study the power of
quantum channels with limited private capacity, focusing on channels that
dephase in random bases. These display extensive nonadditivity of private
capacity: a channel with 2 log d input qubits has a private capacity less than
2, but when used together with a second channel with zero private capacity the
joint capacity jumps to (1/2)log d. In contrast to earlier work which found
nonadditivity vanishing as a fraction of input size or conditional on unproven
mathematical assumptions, this provides a natural setting manifesting
nonadditivity of privacy of the strongest possible sort.
</details>


<details>
<summary>Selling Privacy at Auction (Published on: 2010-11-05T12:04:53Z)</summary>
**Link**: [http://arxiv.org/abs/1011.1375v4](http://arxiv.org/abs/1011.1375v4)
**Updated**: 2011-11-29T14:51:37Z
**Authors**: Arpita Ghosh, Aaron Roth
**Summary**: We initiate the study of markets for private data, though the lens of
differential privacy. Although the purchase and sale of private data has
already begun on a large scale, a theory of privacy as a commodity is missing.
In this paper, we propose to build such a theory. Specifically, we consider a
setting in which a data analyst wishes to buy information from a population
from which he can estimate some statistic. The analyst wishes to obtain an
accurate estimate cheaply. On the other hand, the owners of the private data
experience some cost for their loss of privacy, and must be compensated for
this loss. Agents are selfish, and wish to maximize their profit, so our goal
is to design truthful mechanisms. Our main result is that such auctions can
naturally be viewed and optimally solved as variants of multi-unit procurement
auctions. Based on this result, we derive auctions for two natural settings
which are optimal up to small constant factors:
  1. In the setting in which the data analyst has a fixed accuracy goal, we
show that an application of the classic Vickrey auction achieves the analyst's
accuracy goal while minimizing his total payment.
  2. In the setting in which the data analyst has a fixed budget, we give a
mechanism which maximizes the accuracy of the resulting estimate while
guaranteeing that the resulting sum payments do not exceed the analysts budget.
  In both cases, our comparison class is the set of envy-free mechanisms, which
correspond to the natural class of fixed-price mechanisms in our setting.
  In both of these results, we ignore the privacy cost due to possible
correlations between an individuals private data and his valuation for privacy
itself. We then show that generically, no individually rational mechanism can
compensate individuals for the privacy loss incurred due to their reported
valuations for privacy.
</details>


<details>
<summary>Privacy Preserving Spam Filtering (Published on: 2011-02-19T20:40:56Z)</summary>
**Link**: [http://arxiv.org/abs/1102.4021v2](http://arxiv.org/abs/1102.4021v2)
**Updated**: 2011-09-18T05:37:43Z
**Authors**: Manas A. Pathak, Mehrbod Sharifi, Bhiksha Raj
**Summary**: Email is a private medium of communication, and the inherent privacy
constraints form a major obstacle in developing effective spam filtering
methods which require access to a large amount of email data belonging to
multiple users. To mitigate this problem, we envision a privacy preserving spam
filtering system, where the server is able to train and evaluate a logistic
regression based spam classifier on the combined email data of all users
without being able to observe any emails using primitives such as homomorphic
encryption and randomization. We analyze the protocols for correctness and
security, and perform experiments of a prototype system on a large scale spam
filtering task.
  State of the art spam filters often use character n-grams as features which
result in large sparse data representation, which is not feasible to be used
directly with our training and evaluation protocols. We explore various data
independent dimensionality reduction which decrease the running time of the
protocol making it feasible to use in practice while achieving high accuracy.
</details>


<details>
<summary>Quantum privacy witness (Published on: 2011-09-12T14:47:40Z)</summary>
**Link**: [http://arxiv.org/abs/1109.2486v1](http://arxiv.org/abs/1109.2486v1)
**Updated**: 2011-09-12T14:47:40Z
**Authors**: Konrad Banaszek, Karol Horodecki, Paweł Horodecki
**Summary**: While it is usually known that the mean value of a single observable is
enough to detect entanglement or its distillability, the counterpart of such an
approach in the case of quatum privacy has been missing. Here we develop the
concept of a privacy witness, i.e. a single observable that may detect presence
of the secure key even in the case of bound entanglement. Then we develop the
notion of secret key estimation based on few observables and discuss the
witness decomposition into local measurements. The surprising property of the
witness is that with the help of a low number of product mesurements involved
it may still report the key values that are {\it strictly above} distillable
entanglement of the state. For an exemplary four-qubit state studied in a
recent experiment [K. Dobek {\em et al.}, Phys. Rev. Lett. {\bf 106}, 030501
(2011)] this means 6 Pauli operator product measurements versus 81 needed to
carry out the complete quantum state tomography. The present approach may be
viewed as a paradigm for the general program of experimentally friendly
detection and estimation of task-dedicated quantum entanglement.
</details>


<details>
<summary>Privacy-Aware Mechanism Design (Published on: 2011-11-14T20:32:33Z)</summary>
**Link**: [http://arxiv.org/abs/1111.3350v2](http://arxiv.org/abs/1111.3350v2)
**Updated**: 2012-02-14T14:24:21Z
**Authors**: Kobbi Nissim, Claudio Orlandi, Rann Smorodinsky
**Summary**: In traditional mechanism design, agents only care about the utility they
derive from the outcome of the mechanism. We look at a richer model where
agents also assign non-negative dis-utility to the information about their
private types leaked by the outcome of the mechanism.
  We present a new model for privacy-aware mechanism design, where we only
assume an upper bound on the agents' loss due to leakage, as opposed to
previous work where a full characterization of the loss was required.
  In this model, under a mild assumption on the distribution of how agents
value their privacy, we show a generic construction of privacy-aware mechanisms
and demonstrate its applicability to electronic polling and pricing of a
digital good.
</details>


<details>
<summary>Random Differential Privacy (Published on: 2011-12-12T20:16:03Z)</summary>
**Link**: [http://arxiv.org/abs/1112.2680v1](http://arxiv.org/abs/1112.2680v1)
**Updated**: 2011-12-12T20:16:03Z
**Authors**: Rob Hall, Alessandro Rinaldo, Larry Wasserman
**Summary**: We propose a relaxed privacy definition called {\em random differential
privacy} (RDP). Differential privacy requires that adding any new observation
to a database will have small effect on the output of the data-release
procedure. Random differential privacy requires that adding a {\em randomly
drawn new observation} to a database will have small effect on the output. We
show an analog of the composition property of differentially private procedures
which applies to our new definition. We show how to release an RDP histogram
and we show that RDP histograms are much more accurate than histograms obtained
using ordinary differential privacy. We finally show an analog of the global
sensitivity framework for the release of functions under our privacy
definition.
</details>


<details>
<summary>Privacy Preservation by Disassociation (Published on: 2012-06-30T20:16:16Z)</summary>
**Link**: [http://arxiv.org/abs/1207.0135v1](http://arxiv.org/abs/1207.0135v1)
**Updated**: 2012-06-30T20:16:16Z
**Authors**: Manolis Terrovitis, John Liagouris, Nikos Mamoulis, Spiros Skiadopoulos
**Summary**: In this work, we focus on protection against identity disclosure in the
publication of sparse multidimensional data. Existing multidimensional
anonymization techniquesa) protect the privacy of users either by altering the
set of quasi-identifiers of the original data (e.g., by generalization or
suppression) or by adding noise (e.g., using differential privacy) and/or (b)
assume a clear distinction between sensitive and non-sensitive information and
sever the possible linkage. In many real world applications the above
techniques are not applicable. For instance, consider web search query logs.
Suppressing or generalizing anonymization methods would remove the most
valuable information in the dataset: the original query terms. Additionally,
web search query logs contain millions of query terms which cannot be
categorized as sensitive or non-sensitive since a term may be sensitive for a
user and non-sensitive for another. Motivated by this observation, we propose
an anonymization technique termed disassociation that preserves the original
terms but hides the fact that two or more different terms appear in the same
record. We protect the users' privacy by disassociating record terms that
participate in identifying combinations. This way the adversary cannot
associate with high probability a record with a rare combination of terms. To
the best of our knowledge, our proposal is the first to employ such a technique
to provide protection against identity disclosure. We propose an anonymization
algorithm based on our approach and evaluate its performance on real and
synthetic datasets, comparing it against other state-of-the-art methods based
on generalization and differential privacy.
</details>


<details>
<summary>On Privacy-Preserving Histograms (Published on: 2012-07-04T16:06:07Z)</summary>
**Link**: [http://arxiv.org/abs/1207.1371v1](http://arxiv.org/abs/1207.1371v1)
**Updated**: 2012-07-04T16:06:07Z
**Authors**: Shuchi Chawla, Cynthia Dwork, Frank McSherry, Kunal Talwar
**Summary**: We advance the approach initiated by Chawla et al. for sanitizing (census)
data so as to preserve the privacy of respondents while simultaneously
extracting "useful" statistical information. First, we extend the scope of
their techniques to a broad and rich class of distributions, specifically,
mixtures of highdimensional balls, spheres, Gaussians, and other "nice"
distributions. Second, we randomize the histogram constructions to preserve
spatial characteristics of the data, allowing us to approximate various
quantities of interest, e.g., cost of the minimum spanning tree on the data, in
a privacy-preserving fashion.
</details>


<details>
<summary>Privacy Aware Learning (Published on: 2012-10-07T18:27:03Z)</summary>
**Link**: [http://arxiv.org/abs/1210.2085v2](http://arxiv.org/abs/1210.2085v2)
**Updated**: 2013-10-10T17:53:36Z
**Authors**: John C. Duchi, Michael I. Jordan, Martin J. Wainwright
**Summary**: We study statistical risk minimization problems under a privacy model in
which the data is kept confidential even from the learner. In this local
privacy framework, we establish sharp upper and lower bounds on the convergence
rates of statistical estimation procedures. As a consequence, we exhibit a
precise tradeoff between the amount of privacy the data preserves and the
utility, as measured by convergence rate, of any statistical estimator or
learning procedure.
</details>


<details>
<summary>Privacy Against Statistical Inference (Published on: 2012-10-08T01:07:48Z)</summary>
**Link**: [http://arxiv.org/abs/1210.2123v1](http://arxiv.org/abs/1210.2123v1)
**Updated**: 2012-10-08T01:07:48Z
**Authors**: Flavio du Pin Calmon, Nadia Fawaz
**Summary**: We propose a general statistical inference framework to capture the privacy
threat incurred by a user that releases data to a passive but curious
adversary, given utility constraints. We show that applying this general
framework to the setting where the adversary uses the self-information cost
function naturally leads to a non-asymptotic information-theoretic approach for
characterizing the best achievable privacy subject to utility constraints.
Based on these results we introduce two privacy metrics, namely average
information leakage and maximum information leakage. We prove that under both
metrics the resulting design problem of finding the optimal mapping from the
user's data to a privacy-preserving output can be cast as a modified
rate-distortion problem which, in turn, can be formulated as a convex program.
Finally, we compare our framework with differential privacy.
</details>


<details>
<summary>Privacy Design Strategies (Published on: 2012-10-24T18:25:32Z)</summary>
**Link**: [http://arxiv.org/abs/1210.6621v2](http://arxiv.org/abs/1210.6621v2)
**Updated**: 2013-05-06T06:35:51Z
**Authors**: Jaap-Henk Hoepman
**Summary**: In this paper we define the notion of a privacy design strategy. These
strategies help IT architects to support privacy by design early in the
software development life cycle, during concept development and analysis. Using
current data protection legislation as point of departure we derive the
following eight privacy design strategies: minimise, hide, separate, aggregate,
inform, control, enforce, and demonstrate. The strategies also provide a useful
classification of privacy design patterns and the underlying privacy enhancing
technologies. We therefore believe that these privacy design strategies are not
only useful when designing privacy friendly systems, but also helpful when
evaluating the privacy impact of existing IT systems.
</details>


<details>
<summary>Privacy and Mechanism Design (Published on: 2013-06-10T01:41:38Z)</summary>
**Link**: [http://arxiv.org/abs/1306.2083v1](http://arxiv.org/abs/1306.2083v1)
**Updated**: 2013-06-10T01:41:38Z
**Authors**: Mallesh Pai, Aaron Roth
**Summary**: This paper is a survey of recent work at the intersection of mechanism design
and privacy. The connection is a natural one, but its study has been
jump-started in recent years by the advent of differential privacy, which
provides a rigorous, quantitative way of reasoning about the costs that an
agent might experience because of the loss of his privacy. Here, we survey
several facets of this study, and differential privacy plays a role in more
than one way. Of course, it provides us a basis for modeling agent costs for
privacy, which is essential if we are to attempt mechanism design in a setting
in which agents have preferences for privacy. It also provides a toolkit for
controlling those costs. However, perhaps more surprisingly, it provides a
powerful toolkit for controlling the stability of mechanisms in general, which
yields a set of tools for designing novel mechanisms even in economic settings
completely unrelated to privacy.
</details>


<details>
<summary>Maximal Privacy Without Coherence (Published on: 2013-12-17T22:28:06Z)</summary>
**Link**: [http://arxiv.org/abs/1312.4989v2](http://arxiv.org/abs/1312.4989v2)
**Updated**: 2014-02-05T03:20:38Z
**Authors**: Debbie Leung, Ke Li, Graeme Smith, John Smolin
**Summary**: Privacy lies at the fundament of quantum mechanics. A coherently transmitted
quantum state is inherently private. Remarkably, coherent quantum communication
is not a prerequisite for privacy: there are quantum channels that are too
noisy to transmit any quantum information reliably that can nevertheless send
private classical information. Here, we ask how much private classical
information a channel can transmit if it has little quantum capacity. We
present a class of channels N_d with input dimension d^2, quantum capacity
Q(N_d) <= 1, and private capacity P(N_d) = log d. These channels asymptotically
saturate an interesting inequality P(N) <= (log d_A + Q(N))/2 for any channel N
with input dimension d_A, and capture the essence of privacy stripped of the
confounding influence of coherence.
</details>


<details>
<summary>Privacy for Personal Neuroinformatics (Published on: 2014-03-11T20:33:20Z)</summary>
**Link**: [http://arxiv.org/abs/1403.2745v1](http://arxiv.org/abs/1403.2745v1)
**Updated**: 2014-03-11T20:33:20Z
**Authors**: Arkadiusz Stopczynski, Dazza Greenwood, Lars Kai Hansen, Alex Pentland
**Summary**: Human brain activity collected in the form of Electroencephalography (EEG),
even with low number of sensors, is an extremely rich signal. Traces collected
from multiple channels and with high sampling rates capture many important
aspects of participants' brain activity and can be used as a unique personal
identifier. The motivation for sharing EEG signals is significant, as a mean to
understand the relation between brain activity and well-being, or for
communication with medical services. As the equipment for such data collection
becomes more available and widely used, the opportunities for using the data
are growing; at the same time however inherent privacy risks are mounting. The
same raw EEG signal can be used for example to diagnose mental diseases, find
traces of epilepsy, and decode personality traits. The current practice of the
informed consent of the participants for the use of the data either prevents
reuse of the raw signal or does not truly respect participants' right to
privacy by reusing the same raw data for purposes much different than
originally consented to. Here we propose an integration of a personal
neuroinformatics system, Smartphone Brain Scanner, with a general privacy
framework openPDS. We show how raw high-dimensionality data can be collected on
a mobile device, uploaded to a server, and subsequently operated on and
accessed by applications or researchers, without disclosing the raw signal.
Those extracted features of the raw signal, called answers, are of
significantly lower-dimensionality, and provide the full utility of the data in
given context, without the risk of disclosing sensitive raw signal. Such
architecture significantly mitigates a very serious privacy risk related to raw
EEG recordings floating around and being used and reused for various purposes.
</details>


<details>
<summary>Privacy and Anonymity (Published on: 2014-07-01T22:52:00Z)</summary>
**Link**: [http://arxiv.org/abs/1407.0423v1](http://arxiv.org/abs/1407.0423v1)
**Updated**: 2014-07-01T22:52:00Z
**Authors**: Adrian Yanes
**Summary**: Since the beginning of the digital area, privacy and anonymity have been
impacted drastically (both, positively and negatively), by the different
technologies developed for communications purposes. The broad possibilities
that the Internet offers since its conception, makes it a mandatory target for
those entities that are aiming to know and control the different channels of
communication and the information that flows through. In this paper, we address
the current threats against privacy and anonymity on the Internet, together
with the methods applied against them. In addition, we enumerate the publicly
known entities behind those threats and their motivations. Finally, we analyze
the state of the art concerning the protection of the privacy and anonymity on
the Internet; introducing future lines of research.
</details>


<details>
<summary>Perception Games and Privacy (Published on: 2014-09-04T16:53:26Z)</summary>
**Link**: [http://arxiv.org/abs/1409.1487v4](http://arxiv.org/abs/1409.1487v4)
**Updated**: 2017-05-17T15:17:48Z
**Authors**: Ronen Gradwohl, Rann Smorodinsky
**Summary**: Players (people, firms, states, etc.) have privacy concerns that may affect
their choice of actions in strategic settings. We use a variant of signaling
games to model this effect and study its relation to pooling behavior,
misrepresentation of information, and inefficiency. We discuss these issues and
show that common intuitions may lead to inaccurate conclusions about the
implications of privacy concerns.
</details>


<details>
<summary>Privacy-preserving Loyalty Programs (Published on: 2014-11-14T16:32:44Z)</summary>
**Link**: [http://arxiv.org/abs/1411.3961v2](http://arxiv.org/abs/1411.3961v2)
**Updated**: 2014-12-01T16:25:19Z
**Authors**: Alberto Blanco-Justicia, Josep Domingo-Ferrer
**Summary**: Loyalty programs are promoted by vendors to incentivize loyalty in buyers.
Although such programs have become widespread, they have been criticized by
business experts and consumer associations: loyalty results in profiling and
hence in loss of privacy of consumers. We propose a protocol for
privacy-preserving loyalty programs that allows vendors and consumers to enjoy
the benefits of loyalty (returning customers and discounts, respectively),
while allowing consumers to stay anonymous and empowering them to decide how
much of their profile they reveal to the vendor. The vendor must offer
additional reward if he wants to learn more details on the consumer's profile.
Our protocol is based on partially blind signatures and generalization
techniques, and provides anonymity to consumers and their purchases, while
still allowing negotiated consumer profiling.
</details>


<details>
<summary>Heterogeneous Differential Privacy (Published on: 2015-04-27T09:35:46Z)</summary>
**Link**: [http://arxiv.org/abs/1504.06998v1](http://arxiv.org/abs/1504.06998v1)
**Updated**: 2015-04-27T09:35:46Z
**Authors**: Mohammad Alaggan, Sébastien Gambs, Anne-Marie Kermarrec
**Summary**: The massive collection of personal data by personalization systems has
rendered the preservation of privacy of individuals more and more difficult.
Most of the proposed approaches to preserve privacy in personalization systems
usually address this issue uniformly across users, thus ignoring the fact that
users have different privacy attitudes and expectations (even among their own
personal data). In this paper, we propose to account for this non-uniformity of
privacy expectations by introducing the concept of heterogeneous differential
privacy. This notion captures both the variation of privacy expectations among
users as well as across different pieces of information related to the same
user. We also describe an explicit mechanism achieving heterogeneous
differential privacy, which is a modification of the Laplacian mechanism by
Dwork, McSherry, Nissim, and Smith. In a nutshell, this mechanism achieves
heterogeneous differential privacy by manipulating the sensitivity of the
function using a linear transformation on the input domain. Finally, we
evaluate on real datasets the impact of the proposed mechanism with respect to
a semantic clustering task. The results of our experiments demonstrate that
heterogeneous differential privacy can account for different privacy attitudes
while sustaining a good level of utility as measured by the recall for the
semantic clustering task.
</details>


<details>
<summary>Quadratic Gaussian Privacy Games (Published on: 2015-09-18T03:36:23Z)</summary>
**Link**: [http://arxiv.org/abs/1509.05497v1](http://arxiv.org/abs/1509.05497v1)
**Updated**: 2015-09-18T03:36:23Z
**Authors**: Farhad Farokhi, Henrik Sandberg, Iman Shames, Michael Cantoni
**Summary**: A game-theoretic model for analysing the effects of privacy on strategic
communication between agents is devised. In the model, a sender wishes to
provide an accurate measurement of the state to a receiver while also
protecting its private information (which is correlated with the state) private
from a malicious agent that may eavesdrop on its communications with the
receiver. A family of nontrivial equilibria, in which the communicated messages
carry information, is constructed and its properties are studied.
</details>


<details>
<summary>Privacy Constrained Information Processing (Published on: 2015-10-13T00:53:17Z)</summary>
**Link**: [http://arxiv.org/abs/1510.03495v1](http://arxiv.org/abs/1510.03495v1)
**Updated**: 2015-10-13T00:53:17Z
**Authors**: Emrah Akyol, Cedric Langbort, Tamer Basar
**Summary**: This paper studies communication scenarios where the transmitter and the
receiver have different objectives due to privacy concerns, in the context of a
variation of the strategic information transfer (SIT) model of Sobel and
Crawford. We first formulate the problem as the minimization of a common
distortion by the transmitter and the receiver subject to a privacy constrained
transmitter. We show the equivalence of this formulation to a Stackelberg
equilibrium of the SIT problem. Assuming an entropy based privacy measure, a
quadratic distortion measure and jointly Gaussian variables, we characterize
the Stackelberg equilibrium. Next, we consider asymptotically optimal
compression at the transmitter which inherently provides some level of privacy,
and study equilibrium conditions. We finally analyze the impact of the presence
of an average power constrained Gaussian communication channel between the
transmitter and the receiver on the equilibrium conditions.
</details>


<details>
<summary>Privacy-Aware MMSE Estimation (Published on: 2016-01-27T15:44:04Z)</summary>
**Link**: [http://arxiv.org/abs/1601.07417v1](http://arxiv.org/abs/1601.07417v1)
**Updated**: 2016-01-27T15:44:04Z
**Authors**: Shahab Asoodeh, Fady Alajaji, Tamás Linder
**Summary**: We investigate the problem of the predictability of random variable $Y$ under
a privacy constraint dictated by random variable $X$, correlated with $Y$,
where both predictability and privacy are assessed in terms of the minimum
mean-squared error (MMSE). Given that $X$ and $Y$ are connected via a
binary-input symmetric-output (BISO) channel, we derive the \emph{optimal}
random mapping $P_{Z|Y}$ such that the MMSE of $Y$ given $Z$ is minimized while
the MMSE of $X$ given $Z$ is greater than $(1-\epsilon)\mathsf{var}(X)$ for a
given $\epsilon\geq 0$. We also consider the case where $(X,Y)$ are continuous
and $P_{Z|Y}$ is restricted to be an additive noise channel.
</details>


<details>
<summary>Concentrated Differential Privacy (Published on: 2016-03-06T22:41:12Z)</summary>
**Link**: [http://arxiv.org/abs/1603.01887v2](http://arxiv.org/abs/1603.01887v2)
**Updated**: 2016-03-16T16:29:29Z
**Authors**: Cynthia Dwork, Guy N. Rothblum
**Summary**: We introduce Concentrated Differential Privacy, a relaxation of Differential
Privacy enjoying better accuracy than both pure differential privacy and its
popular "(epsilon,delta)" relaxation without compromising on cumulative privacy
loss over multiple computations.
</details>


<details>
<summary>Privacy Preserving Linear Programming (Published on: 2016-10-07T16:17:02Z)</summary>
**Link**: [http://arxiv.org/abs/1610.02339v1](http://arxiv.org/abs/1610.02339v1)
**Updated**: 2016-10-07T16:17:02Z
**Authors**: Yuan Hong, Jaideep Vaidya, Nicholas Rizzo, Qi Liu
**Summary**: With the rapid increase in computing, storage and networking resources, data
is not only collected and stored, but also analyzed. This creates a serious
privacy problem which often inhibits the use of this data. In this chapter, we
investigate and resolve the privacy issues in a fundamental optimization
problem -- linear programming (LP) which is formulated by data collected from
different parties. We first consider the case where the objective function and
constraints of the linear programming problem are not partitioned between two
parties where one party privately holds the objective function while the other
party privately holds the constraints. Second, we present a privacy preserving
technique for the case that objective function and constraints are arbitrarily
partitioned between two parties where each party privately holds a share of
objective function and constraints. Finally, we extend the technique for
securely solving two-party arbitrarily partitioned linear programming problems
to a multi-party scenario. In summary, we propose a set of efficient and secure
transformation based techniques that create significant value-added benefits of
being independent of the specific algorithms used for solving the linear
programming problem.
</details>


<details>
<summary>Renyi Differential Privacy (Published on: 2017-02-24T06:46:38Z)</summary>
**Link**: [http://arxiv.org/abs/1702.07476v3](http://arxiv.org/abs/1702.07476v3)
**Updated**: 2017-08-25T23:54:30Z
**Authors**: Ilya Mironov
**Summary**: We propose a natural relaxation of differential privacy based on the Renyi
divergence. Closely related notions have appeared in several recent papers that
analyzed composition of differentially private mechanisms. We argue that the
useful analytical tool can be used as a privacy definition, compactly and
accurately representing guarantees on the tails of the privacy loss.
  We demonstrate that the new definition shares many important properties with
the standard definition of differential privacy, while additionally allowing
tighter analysis of composite heterogeneous mechanisms.
</details>


<details>
<summary>Certificate Transparency with Privacy (Published on: 2017-03-07T04:31:39Z)</summary>
**Link**: [http://arxiv.org/abs/1703.02209v4](http://arxiv.org/abs/1703.02209v4)
**Updated**: 2017-08-07T16:05:26Z
**Authors**: Saba Eskandarian, Eran Messeri, Joseph Bonneau, Dan Boneh
**Summary**: Certificate transparency (CT) is an elegant mechanism designed to detect when
a certificate authority (CA) has issued a certificate incorrectly. Many CAs now
support CT and it is being actively deployed in browsers. However, a number of
privacy-related challenges remain. In this paper we propose practical solutions
to two issues. First, we develop a mechanism that enables web browsers to audit
a CT log without violating user privacy. Second, we extend CT to support
non-public subdomains.
</details>


<details>
<summary>Anonymized Local Privacy (Published on: 2017-03-23T07:15:55Z)</summary>
**Link**: [http://arxiv.org/abs/1703.07949v3](http://arxiv.org/abs/1703.07949v3)
**Updated**: 2017-04-04T01:40:22Z
**Authors**: Joshua Joy, Mario Gerla
**Summary**: In this paper, we introduce the family of Anonymized Local Privacy
mechanisms. These mechanisms have an output space of three values "Yes", "No",
or "$\perp$" (not participating) and leverage the law of large numbers to
generate linear noise in the number of data owners to protect privacy both
before and after aggregation yet preserve accuracy.
  We describe the suitability in a distributed on-demand network and evaluate
over a real dataset as we scale the population.
</details>


<details>
<summary>Privacy-Aware Guessing Efficiency (Published on: 2017-04-12T03:28:37Z)</summary>
**Link**: [http://arxiv.org/abs/1704.03606v1](http://arxiv.org/abs/1704.03606v1)
**Updated**: 2017-04-12T03:28:37Z
**Authors**: Shahab Asoodeh, Mario Diaz, Fady Alajaji, Tamás Linder
**Summary**: We investigate the problem of guessing a discrete random variable $Y$ under a
privacy constraint dictated by another correlated discrete random variable $X$,
where both guessing efficiency and privacy are assessed in terms of the
probability of correct guessing. We define $h(P_{XY}, \epsilon)$ as the maximum
probability of correctly guessing $Y$ given an auxiliary random variable $Z$,
where the maximization is taken over all $P_{Z|Y}$ ensuring that the
probability of correctly guessing $X$ given $Z$ does not exceed $\epsilon$. We
show that the map $\epsilon\mapsto h(P_{XY}, \epsilon)$ is strictly increasing,
concave, and piecewise linear, which allows us to derive a closed form
expression for $h(P_{XY}, \epsilon)$ when $X$ and $Y$ are connected via a
binary-input binary-output channel. For $(X^n, Y^n)$ being pairs of independent
and identically distributed binary random vectors, we similarly define
$\underline{h}_n(P_{X^nY^n}, \epsilon)$ under the assumption that $Z^n$ is also
a binary vector. Then we obtain a closed form expression for
$\underline{h}_n(P_{X^nY^n}, \epsilon)$ for sufficiently large, but nontrivial
values of $\epsilon$.
</details>


<details>
<summary>Per-instance Differential Privacy (Published on: 2017-07-24T18:35:31Z)</summary>
**Link**: [http://arxiv.org/abs/1707.07708v4](http://arxiv.org/abs/1707.07708v4)
**Updated**: 2018-11-14T07:11:31Z
**Authors**: Yu-Xiang Wang
**Summary**: We consider a refinement of differential privacy --- per instance
differential privacy (pDP), which captures the privacy of a specific individual
with respect to a fixed data set. We show that this is a strict generalization
of the standard DP and inherits all its desirable properties, e.g.,
composition, invariance to side information and closedness to postprocessing,
except that they all hold for every instance separately. When the data is drawn
from a distribution, we show that per-instance DP implies generalization.
Moreover, we provide explicit calculations of the per-instance DP for the
output perturbation on a class of smooth learning problems. The result reveals
an interesting and intuitive fact that an individual has stronger privacy if
he/she has small "leverage score" with respect to the data set and if he/she
can be predicted more accurately using the leave-one-out data set. Our
simulation shows several orders-of-magnitude more favorable privacy and utility
trade-off when we consider the privacy of only the users in the data set. In a
case study on differentially private linear regression, provide a novel
analysis of the One-Posterior-Sample (OPS) estimator and show that when the
data set is well-conditioned it provides $(\epsilon,\delta)$-pDP for any target
individuals and matches the exact lower bound up to a
$1+\tilde{O}(n^{-1}\epsilon^{-2})$ multiplicative factor. We also demonstrate
how we can use a "pDP to DP conversion" step to design AdaOPS which uses
adaptive regularization to achieve the same results with
$(\epsilon,\delta)$-DP.
</details>


<details>
<summary>Quantum Privacy-Preserving Perceptron (Published on: 2017-07-31T14:42:57Z)</summary>
**Link**: [http://arxiv.org/abs/1707.09893v1](http://arxiv.org/abs/1707.09893v1)
**Updated**: 2017-07-31T14:42:57Z
**Authors**: Shenggang Ying, Mingsheng Ying, Yuan Feng
**Summary**: With the extensive applications of machine learning, the issue of private or
sensitive data in the training examples becomes more and more serious: during
the training process, personal information or habits may be disclosed to
unexpected persons or organisations, which can cause serious privacy problems
or even financial loss. In this paper, we present a quantum privacy-preserving
algorithm for machine learning with perceptron. There are mainly two steps to
protect original training examples. Firstly when checking the current
classifier, quantum tests are employed to detect data user's possible
dishonesty. Secondly when updating the current classifier, private random noise
is used to protect the original data. The advantages of our algorithm are: (1)
it protects training examples better than the known classical methods; (2) it
requires no quantum database and thus is easy to implement.
</details>


<details>
<summary>Differential Privacy By Sampling (Published on: 2017-08-06T13:05:57Z)</summary>
**Link**: [http://arxiv.org/abs/1708.01884v1](http://arxiv.org/abs/1708.01884v1)
**Updated**: 2017-08-06T13:05:57Z
**Authors**: Josh Joy, Mario Gerla
**Summary**: In this paper we present the Sampling Privacy mechanism for privately
releasing personal data. Sampling Privacy is a sampling based privacy mechanism
that satisfies differential privacy.
</details>


<details>
<summary>Privacy-Enabled Biometric Search (Published on: 2017-08-16T00:25:11Z)</summary>
**Link**: [http://arxiv.org/abs/1708.04726v1](http://arxiv.org/abs/1708.04726v1)
**Updated**: 2017-08-16T00:25:11Z
**Authors**: Scott Streit, Brian Streit, Stephen Suffian
**Summary**: Biometrics have a long-held hope of replacing passwords by establishing a
non-repudiated identity and providing authentication with convenience.
Convenience drives consumers toward biometrics-based access management
solutions. Unlike passwords, biometrics cannot be script-injected; however,
biometric data is considered highly sensitive due to its personal nature and
unique association with users. Biometrics differ from passwords in that
compromised passwords may be reset. Compromised biometrics offer no such
relief. A compromised biometric offers unlimited risk in privacy (anyone can
view the biometric) and authentication (anyone may use the biometric).
Standards such as the Biometric Open Protocol Standard (BOPS) (IEEE 2410-2016)
provide a detailed mechanism to authenticate biometrics based on pre-enrolled
devices and a previous identity by storing the biometric in encrypted form.
This paper describes a biometric-agnostic approach that addresses the privacy
concerns of biometrics through the implementation of BOPS. Specifically, two
novel concepts are introduced. First, a biometric is applied to a neural
network to create a feature vector. This neural network alone can be used for
one-to-one matching (authentication), but would require a search in linear time
for the one-to-many case (identity lookup). The classifying algorithm described
in this paper addresses this concern by producing normalized floating-point
values for each feature vector. This allows authentication lookup to occur in
up to polynomial time, allowing for search in encrypted biometric databases
with speed, accuracy and privacy.
</details>


<details>
<summary>Monogamy of Quantum Privacy (Published on: 2017-09-28T18:43:48Z)</summary>
**Link**: [http://arxiv.org/abs/1709.10124v1](http://arxiv.org/abs/1709.10124v1)
**Updated**: 2017-09-28T18:43:48Z
**Authors**: Arun Kumar Pati, Kratveer Singh, Manish K. Gupta
**Summary**: Quantum mechanics ensures that the information stored in a quantum state is
secure and the ability to send private information through a quantum channel is
at least as great as the coherent information. We derive trade-off relations
between quantum privacy, information gain by Eve and the disturbance caused by
Eve to the quantum state that is being sent through a noisy channel. For
tripartite quantum states, we show that monogamy of privacy exists in the case
of a single sender and multiple receivers. When Alice prepares a tripartite
entangled state and shares it with Bob and Charlie through two different noisy
quantum channels, we prove that if the minimally guaranteed quantum privacy
between Alice and Bob is positive, then the privacy of information between
Alice and Charlie has to be negative. Thus, quantum privacy for more than two
parties respects mutual exclusiveness. Then, we prove a monogamy relation for
the minimally guaranteed quantum privacy for tripartite systems. We also prove
a trade-off relation between the entanglement of formation across one partition
and the quantum privacy along another partition. Our results show that quantum
privacy cannot be freely shared among multiple parties and can have implication
in future quantum networks.
</details>


<details>
<summary>One-sided Differential Privacy (Published on: 2017-12-16T01:29:27Z)</summary>
**Link**: [http://arxiv.org/abs/1712.05888v1](http://arxiv.org/abs/1712.05888v1)
**Updated**: 2017-12-16T01:29:27Z
**Authors**: Stelios Doudalis, Ios Kotsogiannis, Samuel Haney, Ashwin Machanavajjhala, Sharad Mehrotra
**Summary**: In this paper, we study the problem of privacy-preserving data sharing,
wherein only a subset of the records in a database are sensitive, possibly
based on predefined privacy policies. Existing solutions, viz, differential
privacy (DP), are over-pessimistic and treat all information as sensitive.
Alternatively, techniques, like access control and personalized differential
privacy, reveal all non-sensitive records truthfully, and they indirectly leak
information about sensitive records through exclusion attacks.
  Motivated by the limitations of prior work, we introduce the notion of
one-sided differential privacy (OSDP). We formalize the exclusion attack and we
show how OSDP protects against it. OSDP offers differential privacy like
guarantees, but only to the sensitive records. OSDP allows the truthful release
of a subset of the non-sensitive records. The sample can be used to support
applications that must output true data, and is well suited for publishing
complex types of data, e.g. trajectories. Though some non-sensitive records are
suppressed to avoid exclusion attacks, our experiments show that the
suppression results in a small loss in utility in most cases. Additionally, we
present a recipe for turning DP mechanisms for answering counting queries into
OSDP techniques for the same task. Our OSDP algorithms leverage the presence of
non-sensitive records and are able to offer up to a 25x improvement in accuracy
over state-of-the-art DP-solutions.
</details>


<details>
<summary>Privacy-Preserving Adversarial Networks (Published on: 2017-12-19T15:53:45Z)</summary>
**Link**: [http://arxiv.org/abs/1712.07008v3](http://arxiv.org/abs/1712.07008v3)
**Updated**: 2019-06-12T14:42:37Z
**Authors**: Ardhendu Tripathy, Ye Wang, Prakash Ishwar
**Summary**: We propose a data-driven framework for optimizing privacy-preserving data
release mechanisms to attain the information-theoretically optimal tradeoff
between minimizing distortion of useful data and concealing specific sensitive
information. Our approach employs adversarially-trained neural networks to
implement randomized mechanisms and to perform a variational approximation of
mutual information privacy. We validate our Privacy-Preserving Adversarial
Networks (PPAN) framework via proof-of-concept experiments on discrete and
continuous synthetic data, as well as the MNIST handwritten digits dataset. For
synthetic data, our model-agnostic PPAN approach achieves tradeoff points very
close to the optimal tradeoffs that are analytically-derived from model
knowledge. In experiments with the MNIST data, we visually demonstrate a
learned tradeoff between minimizing the pixel-level distortion versus
concealing the written digit.
</details>


<details>
<summary>On Perfect Privacy (Published on: 2017-12-22T15:16:40Z)</summary>
**Link**: [http://arxiv.org/abs/1712.08500v8](http://arxiv.org/abs/1712.08500v8)
**Updated**: 2021-01-21T22:12:53Z
**Authors**: Borzoo Rassouli, Deniz Gunduz
**Summary**: The problem of private data disclosure is studied from an information
theoretic perspective. Considering a pair of dependent random variables
$(X,Y)$, where $X$ and $Y$ denote the private and useful data, respectively,
the following problem is addressed: What is the maximum information that can be
revealed about $Y$ (measured by mutual information $I(Y;U)$, in which $U$ is
the revealed data), while disclosing no information about $X$ (captured by the
condition of statistical independence, i.e., $X\independent U$, and henceforth,
called \textit{perfect privacy})? We analyze the supremization of
\textit{utility}, i.e., $I(Y;U)$ under the condition of perfect privacy for two
scenarios: \textit{output perturbation} and \textit{full data observation}
models, which correspond to the cases where a Markov kernel, called
\textit{privacy-preserving mapping}, applies to $Y$ and the pair $(X,Y)$,
respectively. When both $X$ and $Y$ have a finite alphabet, the linear
algebraic analysis involved in the solution provides some interesting results,
such as upper/lower bounds on the size of the released alphabet and the maximum
utility. Afterwards, it is shown that for the jointly Gaussian $(X,Y)$, perfect
privacy is not possible in the output perturbation model in contrast to the
full data observation model. Finally, an asymptotic analysis is provided to
obtain the rate of released information when a sufficiently small leakage is
allowed. In particular, in the context of output perturbation model, it is
shown that this rate is always finite when perfect privacy is not feasible, and
two lower bounds are provided for it; When perfect privacy is feasible, it is
shown that under mild conditions, this rate becomes unbounded.
</details>


<details>
<summary>Towards Measuring Membership Privacy (Published on: 2017-12-25T22:23:28Z)</summary>
**Link**: [http://arxiv.org/abs/1712.09136v1](http://arxiv.org/abs/1712.09136v1)
**Updated**: 2017-12-25T22:23:28Z
**Authors**: Yunhui Long, Vincent Bindschaedler, Carl A. Gunter
**Summary**: Machine learning models are increasingly made available to the masses through
public query interfaces. Recent academic work has demonstrated that malicious
users who can query such models are able to infer sensitive information about
records within the training data. Differential privacy can thwart such attacks,
but not all models can be readily trained to achieve this guarantee or to
achieve it with acceptable utility loss. As a result, if a model is trained
without differential privacy guarantee, little is known or can be said about
the privacy risk of releasing it. In this work, we investigate and analyze
membership attacks to understand why and how they succeed. Based on this
understanding, we propose Differential Training Privacy (DTP), an empirical
metric to estimate the privacy risk of publishing a classier when methods such
as differential privacy cannot be applied. DTP is a measure of a classier with
respect to its training dataset, and we show that calculating DTP is efficient
in many practical cases. We empirically validate DTP using state-of-the-art
machine learning models such as neural networks trained on real-world datasets.
Our results show that DTP is highly predictive of the success of membership
attacks and therefore reducing DTP also reduces the privacy risk. We advocate
for DTP to be used as part of the decision-making process when considering
publishing a classifier. To this end, we also suggest adopting the DTP-1
hypothesis: if a classifier has a DTP value above 1, it should not be
published.
</details>


<details>
<summary>Segmentation, Incentives and Privacy (Published on: 2018-06-04T06:01:47Z)</summary>
**Link**: [http://arxiv.org/abs/1806.00966v1](http://arxiv.org/abs/1806.00966v1)
**Updated**: 2018-06-04T06:01:47Z
**Authors**: Kobbi Nissim, Rann Smorodinsky, Moshe Tennenholtz
**Summary**: Data driven segmentation is the powerhouse behind the success of online
advertising. Various underlying challenges for successful segmentation have
been studied by the academic community, with one notable exception - consumers
incentives have been typically ignored. This lacuna is troubling as consumers
have much control over the data being collected. Missing or manipulated data
could lead to inferior segmentation. The current work proposes a model of
prior-free segmentation, inspired by models of facility location, and to the
best of our knowledge provides the first segmentation mechanism that addresses
incentive compatibility, efficient market segmentation and privacy in the
absence of a common prior.
</details>


<details>
<summary>Integral Privacy for Sampling (Published on: 2018-06-13T02:01:22Z)</summary>
**Link**: [http://arxiv.org/abs/1806.04819v5](http://arxiv.org/abs/1806.04819v5)
**Updated**: 2019-07-02T22:41:35Z
**Authors**: Hisham Husain, Zac Cranko, Richard Nock
**Summary**: Differential privacy is a leading protection setting, focused by design on
individual privacy. Many applications, in medical / pharmaceutical domains or
social networks, rather posit privacy at a group level, a setting we call
integral privacy. We aim for the strongest form of privacy: the group size is
in particular not known in advance. We study a problem with related
applications in domains cited above that have recently met with substantial
recent press: sampling.
  Keeping correct utility levels in such a strong model of statistical
indistinguishability looks difficult to be achieved with the usual differential
privacy toolbox because it would typically scale in the worst case the
sensitivity by the sample size and so the noise variance by up to its square.
We introduce a trick specific to sampling that bypasses the sensitivity
analysis. Privacy enforces an information theoretic barrier on approximation,
and we show how to reach this barrier with guarantees on the approximation of
the target non private density. We do so using a recent approach to non private
density estimation relying on the original boosting theory, learning the
sufficient statistics of an exponential family with classifiers. Approximation
guarantees cover the mode capture problem. In the context of learning, the
sampling problem is particularly important: because integral privacy enjoys the
same closure under post-processing as differential privacy does, any algorithm
using integrally privacy sampled data would result in an output equally
integrally private. We also show that this brings fairness guarantees on
post-processing that would eventually elude classical differential privacy: any
decision process has bounded data-dependent bias when the data is integrally
privately sampled. Experimental results against private kernel density
estimation and private GANs displays the quality of our results.
</details>


<details>
<summary>Privacy Amplification by Iteration (Published on: 2018-08-20T18:49:32Z)</summary>
**Link**: [http://arxiv.org/abs/1808.06651v2](http://arxiv.org/abs/1808.06651v2)
**Updated**: 2018-12-10T23:43:40Z
**Authors**: Vitaly Feldman, Ilya Mironov, Kunal Talwar, Abhradeep Thakurta
**Summary**: Many commonly used learning algorithms work by iteratively updating an
intermediate solution using one or a few data points in each iteration.
Analysis of differential privacy for such algorithms often involves ensuring
privacy of each step and then reasoning about the cumulative privacy cost of
the algorithm. This is enabled by composition theorems for differential privacy
that allow releasing of all the intermediate results. In this work, we
demonstrate that for contractive iterations, not releasing the intermediate
results strongly amplifies the privacy guarantees.
  We describe several applications of this new analysis technique to solving
convex optimization problems via noisy stochastic gradient descent. For
example, we demonstrate that a relatively small number of non-private data
points from the same distribution can be used to close the gap between private
and non-private convex optimization. In addition, we demonstrate that we can
achieve guarantees similar to those obtainable using the
privacy-amplification-by-sampling technique in several natural settings where
that technique cannot be applied.
</details>


<details>
<summary>SoK: Differential Privacies (Published on: 2019-06-04T10:55:01Z)</summary>
**Link**: [http://arxiv.org/abs/1906.01337v6](http://arxiv.org/abs/1906.01337v6)
**Updated**: 2022-11-13T21:39:01Z
**Authors**: Damien Desfontaines, Balázs Pejó
**Summary**: Shortly after it was first introduced in 2006, differential privacy became
the flagship data privacy definition. Since then, numerous variants and
extensions were proposed to adapt it to different scenarios and attacker
models. In this work, we propose a systematic taxonomy of these variants and
extensions. We list all data privacy definitions based on differential privacy,
and partition them into seven categories, depending on which aspect of the
original definition is modified.
  These categories act like dimensions: variants from the same category cannot
be combined, but variants from different categories can be combined to form new
definitions. We also establish a partial ordering of relative strength between
these notions by summarizing existing results. Furthermore, we list which of
these definitions satisfy some desirable properties, like composition,
post-processing, and convexity by either providing a novel proof or collecting
existing ones.
</details>


<details>
<summary>Capacity Bounded Differential Privacy (Published on: 2019-07-03T23:07:34Z)</summary>
**Link**: [http://arxiv.org/abs/1907.02159v1](http://arxiv.org/abs/1907.02159v1)
**Updated**: 2019-07-03T23:07:34Z
**Authors**: Kamalika Chaudhuri, Jacob Imola, Ashwin Machanavajjhala
**Summary**: Differential privacy, a notion of algorithmic stability, is a gold standard
for measuring the additional risk an algorithm's output poses to the privacy of
a single record in the dataset. Differential privacy is defined as the distance
between the output distribution of an algorithm on neighboring datasets that
differ in one entry. In this work, we present a novel relaxation of
differential privacy, capacity bounded differential privacy, where the
adversary that distinguishes output distributions is assumed to be
capacity-bounded -- i.e. bounded not in computational power, but in terms of
the function class from which their attack algorithm is drawn. We model
adversaries in terms of restricted f-divergences between probability
distributions, and study properties of the definition and algorithms that
satisfy them.
</details>


<details>
<summary>Location Privacy in Conservation (Published on: 2019-07-16T15:11:48Z)</summary>
**Link**: [http://arxiv.org/abs/1907.07054v1](http://arxiv.org/abs/1907.07054v1)
**Updated**: 2019-07-16T15:11:48Z
**Authors**: Hayyu Imanda, Joss Wright
**Summary**: The growing public nature of academic journals along with current best
practices of sharing primary data for scientific research are profoundly
valuable for the understanding of a species and their conservation efforts. On
the other hand, public spatial data on endangered species may be easily abused
by wildlife criminals. In this paper, we discuss how geo-indistinguishability,
a formal notion of privacy for location-based systems, can be used to add noise
to published spatial data whilst allowing quantification of such tradeoff.
</details>


<details>
<summary>Privacy-Preserving Bandits (Published on: 2019-09-10T11:39:58Z)</summary>
**Link**: [http://arxiv.org/abs/1909.04421v4](http://arxiv.org/abs/1909.04421v4)
**Updated**: 2020-03-11T12:39:06Z
**Authors**: Mohammad Malekzadeh, Dimitrios Athanasakis, Hamed Haddadi, Benjamin Livshits
**Summary**: Contextual bandit algorithms~(CBAs) often rely on personal data to provide
recommendations. Centralized CBA agents utilize potentially sensitive data from
recent interactions to provide personalization to end-users. Keeping the
sensitive data locally, by running a local agent on the user's device, protects
the user's privacy, however, the agent requires longer to produce useful
recommendations, as it does not leverage feedback from other users. This paper
proposes a technique we call Privacy-Preserving Bandits (P2B); a system that
updates local agents by collecting feedback from other local agents in a
differentially-private manner. Comparisons of our proposed approach with a
non-private, as well as a fully-private (local) system, show competitive
performance on both synthetic benchmarks and real-world data. Specifically, we
observed only a decrease of 2.6% and 3.6% in multi-label classification
accuracy, and a CTR increase of 0.0025 in online advertising for a privacy
budget $\epsilon \approx 0.693$. These results suggest P2B is an effective
approach to challenges arising in on-device privacy-preserving personalization.
</details>


<details>
<summary>Privacy Preserving Count Statistics (Published on: 2019-10-15T19:42:00Z)</summary>
**Link**: [http://arxiv.org/abs/1910.07020v1](http://arxiv.org/abs/1910.07020v1)
**Updated**: 2019-10-15T19:42:00Z
**Authors**: Lu Yu, Oluwakemi Hambolu, Yu Fu, Jon Oakley, Richard R. Brooks
**Summary**: The ability to preserve user privacy and anonymity is important. One of the
safest ways to maintain privacy is to avoid storing personally identifiable
information (PII), which poses a challenge for maintaining useful user
statistics. Probabilistic counting has been used to find the cardinality of a
multiset when precise counting is too resource intensive. In this paper,
probabilistic counting is used as an anonymization technique that provides a
reliable estimate of the number of unique users. We extend previous work in
probabilistic counting by considering its use for preserving user anonymity,
developing application guidelines and including hash collisions in the
estimate. Our work complements previous method by attempting to explore the
causes of the deviation of uncorrected estimate from the real value. The
experimental results show that if the proper register size is used, collision
compensation provides estimates are as good as, if not better than, the
original probabilistic counting. We develop a new anonymity metric to precisely
quantify the degree of anonymity the algorithm provides.
</details>


<details>
<summary>Federated Generative Privacy (Published on: 2019-10-18T12:41:15Z)</summary>
**Link**: [http://arxiv.org/abs/1910.08385v1](http://arxiv.org/abs/1910.08385v1)
**Updated**: 2019-10-18T12:41:15Z
**Authors**: Aleksei Triastcyn, Boi Faltings
**Summary**: In this paper, we propose FedGP, a framework for privacy-preserving data
release in the federated learning setting. We use generative adversarial
networks, generator components of which are trained by FedAvg algorithm, to
draw privacy-preserving artificial data samples and empirically assess the risk
of information disclosure. Our experiments show that FedGP is able to generate
labelled data of high quality to successfully train and validate supervised
models. Finally, we demonstrate that our approach significantly reduces
vulnerability of such models to model inversion attacks.
</details>


<details>
<summary>Empirical Differential Privacy (Published on: 2019-10-28T17:26:18Z)</summary>
**Link**: [http://arxiv.org/abs/1910.12820v5](http://arxiv.org/abs/1910.12820v5)
**Updated**: 2023-01-03T23:14:52Z
**Authors**: Paul Burchard, Anthony Daoud, Dominic Dotterrer
**Summary**: We show how to achieve differential privacy with no or reduced added noise,
based on the empirical noise in the data itself. Unlike previous works on
noiseless privacy, the empirical viewpoint avoids making any explicit
assumptions about the random process generating the data.
</details>


<details>
<summary>Privacy-Preserving Payment Splitting (Published on: 2019-11-20T23:53:23Z)</summary>
**Link**: [http://arxiv.org/abs/1911.09222v1](http://arxiv.org/abs/1911.09222v1)
**Updated**: 2019-11-20T23:53:23Z
**Authors**: Saba Eskandarian, Mihai Christodorescu, Payman Mohassel
**Summary**: Widely used payment splitting apps allow members of a group to keep track of
debts between members by sending charges for expenses paid by one member on
behalf of others. While offering a great deal of convenience, these apps gain
access to sensitive data on users' financial transactions. In this paper, we
present a payment splitting app that hides all transaction data within a group
from the service provider, provides privacy protections between users in a
group, and provides integrity against malicious users or even a malicious
server.
  The core protocol proceeds in a series of rounds in which users either submit
real data or cover traffic, and the server blindly updates balances, informs
users of charges, and computes integrity checks on user-submitted data. Our
protocol requires no cryptographic operations on the server, and after a
group's initial setup, the only cryptographic tool users need is AES.
  We implement the payment splitting protocol as an Android app and the
accompanying server. We find that, for realistic group sizes, it requires fewer
than 50 milliseconds per round of computation on a user's phone and the server
requires fewer than 300 microseconds per round for each group, meaning that our
protocol enjoys excellent performance and scalability properties.
</details>


<details>
<summary>Successive Refinement of Privacy (Published on: 2020-05-24T04:16:01Z)</summary>
**Link**: [http://arxiv.org/abs/2005.11651v1](http://arxiv.org/abs/2005.11651v1)
**Updated**: 2020-05-24T04:16:01Z
**Authors**: Antonious M. Girgis, Deepesh Data, Kamalika Chaudhuri, Christina Fragouli, Suhas Diggavi
**Summary**: This work examines a novel question: how much randomness is needed to achieve
local differential privacy (LDP)? A motivating scenario is providing {\em
multiple levels of privacy} to multiple analysts, either for distribution or
for heavy-hitter estimation, using the \emph{same} (randomized) output. We call
this setting \emph{successive refinement of privacy}, as it provides
hierarchical access to the raw data with different privacy levels. For example,
the same randomized output could enable one analyst to reconstruct the input,
while another can only estimate the distribution subject to LDP requirements.
This extends the classical Shannon (wiretap) security setting to local
differential privacy. We provide (order-wise) tight characterizations of
privacy-utility-randomness trade-offs in several cases for distribution
estimation, including the standard LDP setting under a randomness constraint.
We also provide a non-trivial privacy mechanism for multi-level privacy.
Furthermore, we show that we cannot reuse random keys over time while
preserving privacy of each user.
</details>


<details>
<summary>Privacy Preserving Visual SLAM (Published on: 2020-07-20T18:00:06Z)</summary>
**Link**: [http://arxiv.org/abs/2007.10361v2](http://arxiv.org/abs/2007.10361v2)
**Updated**: 2020-07-27T07:34:46Z
**Authors**: Mikiya Shibuya, Shinya Sumikura, Ken Sakurada
**Summary**: This study proposes a privacy-preserving Visual SLAM framework for estimating
camera poses and performing bundle adjustment with mixed line and point clouds
in real time. Previous studies have proposed localization methods to estimate a
camera pose using a line-cloud map for a single image or a reconstructed point
cloud. These methods offer a scene privacy protection against the inversion
attacks by converting a point cloud to a line cloud, which reconstruct the
scene images from the point cloud. However, they are not directly applicable to
a video sequence because they do not address computational efficiency. This is
a critical issue to solve for estimating camera poses and performing bundle
adjustment with mixed line and point clouds in real time. Moreover, there has
been no study on a method to optimize a line-cloud map of a server with a point
cloud reconstructed from a client video because any observation points on the
image coordinates are not available to prevent the inversion attacks, namely
the reversibility of the 3D lines. The experimental results with synthetic and
real data show that our Visual SLAM framework achieves the intended
privacy-preserving formation and real-time performance using a line-cloud map.
</details>


<details>
<summary>Privacy vs National Security (Published on: 2020-07-10T19:35:10Z)</summary>
**Link**: [http://arxiv.org/abs/2007.12633v1](http://arxiv.org/abs/2007.12633v1)
**Updated**: 2020-07-10T19:35:10Z
**Authors**: Tajdar Jawaid
**Summary**: There are growing concerns and anxiety about privacy among the general public
especially after the revelations of former NSA contractor and whistleblowers
like Edward Snowden and others. While privacy is the fundamental concept of
being human, the growing tug-of-war between an individuals privacy and freedom
vs national security has renewed the concerns about where the fine balance
should lie between the two. For the first time in history the technological
advancement has made the mass data gathering, analysis, and storage a
financially and technologically feasible option for the governments and private
businesses. This has led to the growing interest of governments and security
agencies around the globe to develop sophisticated algorithms using the power
of Big-Data, Machine-Learning and Artificial Intelligence. The technology has
enabled governments and private businesses to collect and store thousands of
data points on every individual, which has put an individuals privacy under
constant threat. This article analyses the individual's privacy concepts and
its perceived link with national security. The article will also discuss the
various aspects of privacy and national-security, arguments of both sides and
where a boundary should be drawn between privacy and national security.
</details>


<details>
<summary>Adversarial Privacy-preserving Filter (Published on: 2020-07-25T05:41:00Z)</summary>
**Link**: [http://arxiv.org/abs/2007.12861v2](http://arxiv.org/abs/2007.12861v2)
**Updated**: 2020-08-04T05:12:11Z
**Authors**: Jiaming Zhang, Jitao Sang, Xian Zhao, Xiaowen Huang, Yanfeng Sun, Yongli Hu
**Summary**: While widely adopted in practical applications, face recognition has been
critically discussed regarding the malicious use of face images and the
potential privacy problems, e.g., deceiving payment system and causing personal
sabotage. Online photo sharing services unintentionally act as the main
repository for malicious crawler and face recognition applications. This work
aims to develop a privacy-preserving solution, called Adversarial
Privacy-preserving Filter (APF), to protect the online shared face images from
being maliciously used.We propose an end-cloud collaborated adversarial attack
solution to satisfy requirements of privacy, utility and nonaccessibility.
Specifically, the solutions consist of three modules: (1) image-specific
gradient generation, to extract image-specific gradient in the user end with a
compressed probe model; (2) adversarial gradient transfer, to fine-tune the
image-specific gradient in the server cloud; and (3) universal adversarial
perturbation enhancement, to append image-independent perturbation to derive
the final adversarial noise. Extensive experiments on three datasets validate
the effectiveness and efficiency of the proposed solution. A prototype
application is also released for further evaluation.We hope the end-cloud
collaborated attack framework could shed light on addressing the issue of
online multimedia sharing privacy-preserving issues from user side.
</details>


<details>
<summary>Smart Meter Data Privacy (Published on: 2020-09-02T21:59:03Z)</summary>
**Link**: [http://arxiv.org/abs/2009.01364v1](http://arxiv.org/abs/2009.01364v1)
**Updated**: 2020-09-02T21:59:03Z
**Authors**: Giulio Giaconi, Deniz Gunduz, H. Vincent Poor
**Summary**: Smart grids (SGs) promise to deliver dramatic improvements compared to
traditional power grids thanks primarily to the large amount of data being
exchanged and processed within the grid, which enables the grid to be monitored
more accurately and at a much faster pace. The smart meter (SM) is one of the
key devices that enable the SG concept by monitoring a household's electricity
consumption and reporting it to the utility provider (UP), i.e., the entity
that sells energy to customers, or to the distribution system operator (DSO),
i.e., the entity that operates and manages the grid, with high accuracy and at
a much faster pace compared to traditional meters. However, the very
availability of rich and high-frequency household electricity consumption data,
which enables a very efficient power grid management, also opens up
unprecedented challenges on data security and privacy. To counter these
threats, it is necessary to develop techniques that keep SM data private, and,
for this reason, SM privacy has become a very active research area. The aim of
this chapter is to provide an overview of the most significant
privacy-preserving techniques for SM data, highlighting their main benefits and
disadvantages.
</details>


<details>
<summary>Multi-Central Differential Privacy (Published on: 2020-09-11T12:47:27Z)</summary>
**Link**: [http://arxiv.org/abs/2009.05401v1](http://arxiv.org/abs/2009.05401v1)
**Updated**: 2020-09-11T12:47:27Z
**Authors**: Thomas Steinke
**Summary**: Differential privacy is typically studied in the central model where a
trusted "aggregator" holds the sensitive data of all the individuals and is
responsible for protecting their privacy. A popular alternative is the local
model in which the aggregator is untrusted and instead each individual is
responsible for their own privacy. The decentralized privacy guarantee of the
local model comes at a high price in statistical utility or computational
complexity. Thus intermediate models such as the shuffled model and pan privacy
have been studied in an attempt to attain the best of both worlds.
  In this note, we propose an intermediate trust model for differential
privacy, which we call the multi-central model. Here there are multiple
aggregators and we only assume that they do not collude nefariously. This model
relaxes the trust requirements of the central model while avoiding the price of
the local model. We motivate this model and provide some simple and efficient
algorithms for it. We argue that this model is a promising direction for
further research.
</details>


<details>
<summary>Pretty Good Phone Privacy (Published on: 2020-09-18T19:27:49Z)</summary>
**Link**: [http://arxiv.org/abs/2009.09035v3](http://arxiv.org/abs/2009.09035v3)
**Updated**: 2020-12-28T19:49:34Z
**Authors**: Paul Schmitt, Barath Raghavan
**Summary**: To receive service in today's cellular architecture, phones uniquely identify
themselves to towers and thus to operators. This is now a cause of major
privacy violations, as operators now sell and leak identity and location data
of hundreds of millions of mobile users.
  In this paper, we take an end-to-end perspective on the cellular architecture
and find key points of decoupling that enable us to protect user identity and
location privacy with no changes to physical infrastructure, no added latency,
and no requirement of direct cooperation from existing operators.
  We describe Pretty Good Phone Privacy (PGPP) and demonstrate how our modified
backend stack (NGC) works with real phones to provide ordinary yet
privacy-preserving connectivity. We explore inherent privacy and efficiency
tradeoffs in a simulation of a large metropolitan region. We show how PGPP
maintains today's control overheads while significantly improving user identity
and location privacy.
</details>


<details>
<summary>Privacy-Preserving XGBoost Inference (Published on: 2020-11-09T21:46:07Z)</summary>
**Link**: [http://arxiv.org/abs/2011.04789v4](http://arxiv.org/abs/2011.04789v4)
**Updated**: 2020-11-24T18:07:27Z
**Authors**: Xianrui Meng, Joan Feigenbaum
**Summary**: Although machine learning (ML) is widely used for predictive tasks, there are
important scenarios in which ML cannot be used or at least cannot achieve its
full potential. A major barrier to adoption is the sensitive nature of
predictive queries. Individual users may lack sufficiently rich datasets to
train accurate models locally but also be unwilling to send sensitive queries
to commercial services that vend such models. One central goal of
privacy-preserving machine learning (PPML) is to enable users to submit
encrypted queries to a remote ML service, receive encrypted results, and
decrypt them locally. We aim at developing practical solutions for real-world
privacy-preserving ML inference problems. In this paper, we propose a
privacy-preserving XGBoost prediction algorithm, which we have implemented and
evaluated empirically on AWS SageMaker. Experimental results indicate that our
algorithm is efficient enough to be used in real ML production environments.
</details>


<details>
<summary>N-grams Bayesian Differential Privacy (Published on: 2021-01-29T18:48:49Z)</summary>
**Link**: [http://arxiv.org/abs/2101.12736v1](http://arxiv.org/abs/2101.12736v1)
**Updated**: 2021-01-29T18:48:49Z
**Authors**: Osman Ramadan, James Withers, Douglas Orr
**Summary**: Differential privacy has gained popularity in machine learning as a strong
privacy guarantee, in contrast to privacy mitigation techniques such as
k-anonymity. However, applying differential privacy to n-gram counts
significantly degrades the utility of derived language models due to their
large vocabularies. We propose a differential privacy mechanism that uses
public data as a prior in a Bayesian setup to provide tighter bounds on the
privacy loss metric epsilon, and thus better privacy-utility trade-offs. It
first transforms the counts to log space, approximating the distribution of the
public and private data as Gaussian. The posterior distribution is then
evaluated and softmax is applied to produce a probability distribution. This
technique achieves up to 85% reduction in KL divergence compared to previously
known mechanisms at epsilon equals 0.1. We compare our mechanism to k-anonymity
in a n-gram language modelling task and show that it offers competitive
performance at large vocabulary sizes, while also providing superior privacy
protection.
</details>


<details>
<summary>Federated $f$-Differential Privacy (Published on: 2021-02-22T16:28:21Z)</summary>
**Link**: [http://arxiv.org/abs/2102.11158v1](http://arxiv.org/abs/2102.11158v1)
**Updated**: 2021-02-22T16:28:21Z
**Authors**: Qinqing Zheng, Shuxiao Chen, Qi Long, Weijie J. Su
**Summary**: Federated learning (FL) is a training paradigm where the clients
collaboratively learn models by repeatedly sharing information without
compromising much on the privacy of their local sensitive data. In this paper,
we introduce federated $f$-differential privacy, a new notion specifically
tailored to the federated setting, based on the framework of Gaussian
differential privacy. Federated $f$-differential privacy operates on record
level: it provides the privacy guarantee on each individual record of one
client's data against adversaries. We then propose a generic private federated
learning framework {PriFedSync} that accommodates a large family of
state-of-the-art FL algorithms, which provably achieves federated
$f$-differential privacy. Finally, we empirically demonstrate the trade-off
between privacy guarantee and prediction performance for models trained by
{PriFedSync} in computer vision tasks.
</details>


<details>
<summary>Rejoinder: Gaussian Differential Privacy (Published on: 2021-04-05T16:27:56Z)</summary>
**Link**: [http://arxiv.org/abs/2104.01987v2](http://arxiv.org/abs/2104.01987v2)
**Updated**: 2021-06-26T02:40:17Z
**Authors**: Jinshuo Dong, Aaron Roth, Weijie J. Su
**Summary**: In this rejoinder, we aim to address two broad issues that cover most
comments made in the discussion. First, we discuss some theoretical aspects of
our work and comment on how this work might impact the theoretical foundation
of privacy-preserving data analysis. Taking a practical viewpoint, we next
discuss how f-differential privacy (f-DP) and Gaussian differential privacy
(GDP) can make a difference in a range of applications.
</details>


<details>
<summary>Privacy-aware VR streaming (Published on: 2021-04-20T06:28:31Z)</summary>
**Link**: [http://arxiv.org/abs/2104.09779v1](http://arxiv.org/abs/2104.09779v1)
**Updated**: 2021-04-20T06:28:31Z
**Authors**: Xing Wei, Chenyang Yang
**Summary**: Proactive tile-based virtual reality (VR) video streaming employs the current
tracking data of a user to predict future requested tiles, then renders and
delivers the predicted tiles to be requested before playback. The quality of
experience (QoE) depends on the overall performance of prediction, computing
(i.e., rendering) and communication. All prior works neglect that users may
have privacy requirement, i.e., not all the current tracking data are allowed
to be uploaded. In this paper, we investigate the privacy-aware VR streaming.
We first establish a dataset that collects the privacy requirement of 66 users
among 18 panoramic videos. The dataset shows that the privacy requirements of
360$^{\circ}$ videos are heterogeneous. Only 41\% of the total watched videos
have no privacy requirement. Based on these findings, we formulate the privacy
requirement as the \textit{degree of privacy} (DoP), and investigate the impact
of DoP on the proactive VR streaming. First, we find that with DoP, the length
of the observation window and prediction window of a tile predictor should be
variable. Then, we jointly optimize the durations for computing and
transmitting the selected tiles as well as the computing and communication
capability, aimed at maximizing the QoE given arbitrary predictor and
configured resources. From the obtained optimal closed-form solution, we find a
resource-saturated region where DoP has no impact on the QoE and a
resource-unsaturated region where the two-fold impacts of DoP are
contradictory. On the one hand, the increase of DoP will degrade the prediction
performance and thus degrade the QoE. On the other hand, the increase of DoP
will improve the capability of computing and communication and thus improve the
QoE. Simulation results using two predictors and a real dataset validate the
analysis and demonstrate the overall impact of DoP on the QoE.
</details>


<details>
<summary>Privacy-Preserving Portrait Matting (Published on: 2021-04-29T09:20:19Z)</summary>
**Link**: [http://arxiv.org/abs/2104.14222v2](http://arxiv.org/abs/2104.14222v2)
**Updated**: 2021-07-29T13:07:00Z
**Authors**: Jizhizi Li, Sihan Ma, Jing Zhang, Dacheng Tao
**Summary**: Recently, there has been an increasing concern about the privacy issue raised
by using personally identifiable information in machine learning. However,
previous portrait matting methods were all based on identifiable portrait
images. To fill the gap, we present P3M-10k in this paper, which is the first
large-scale anonymized benchmark for Privacy-Preserving Portrait Matting.
P3M-10k consists of 10,000 high-resolution face-blurred portrait images along
with high-quality alpha mattes. We systematically evaluate both trimap-free and
trimap-based matting methods on P3M-10k and find that existing matting methods
show different generalization capabilities when following the
Privacy-Preserving Training (PPT) setting, i.e., training on face-blurred
images and testing on arbitrary images. To devise a better trimap-free portrait
matting model, we propose P3M-Net, which leverages the power of a unified
framework for both semantic perception and detail matting, and specifically
emphasizes the interaction between them and the encoder to facilitate the
matting process. Extensive experiments on P3M-10k demonstrate that P3M-Net
outperforms the state-of-the-art methods in terms of both objective metrics and
subjective visual quality. Besides, it shows good generalization capacity under
the PPT setting, confirming the value of P3M-10k for facilitating future
research and enabling potential real-world applications. The source code and
dataset are available at https://github.com/JizhiziLi/P3M
</details>


<details>
<summary>Privacy-Preserving Database Fingerprinting (Published on: 2021-09-06T22:50:51Z)</summary>
**Link**: [http://arxiv.org/abs/2109.02768v2](http://arxiv.org/abs/2109.02768v2)
**Updated**: 2022-03-06T15:55:50Z
**Authors**: Tianxi Ji, Erman Ayday, Emre Yilmaz, Pan Li
**Summary**: When sharing sensitive relational databases with other parties, a database
owner aims to (i) have privacy guarantees for the database entries, (ii) have
liability guarantees (via fingerprinting) in case of unauthorized sharing of
its database by the recipients, and (iii) provide a high quality (utility)
database to the recipients. We observe that sharing a relational database with
privacy and liability guarantees are orthogonal objectives. The former can be
achieved by injecting noise into the database to prevent inference of the
original data values, whereas, the latter can be achieved by hiding unique
marks inside the database to trace malicious parties (data recipients) who
redistribute the data without the authorization. We achieve these two
objectives simultaneously by proposing a novel entry-level
differentially-private fingerprinting mechanism for relational databases.
  At a high level, the proposed mechanism fulfills the privacy and liability
requirements by leveraging the randomization nature that is intrinsic to
fingerprinting and achieves desired entry-level privacy guarantees. To be more
specific, we devise a bit-level random response scheme to achieve differential
privacy guarantee for arbitrary data entries when sharing the entire database,
and then, based on this, we develop an $\epsilon$-entry-level
differentially-private fingerprinting mechanism. Next, we theoretically analyze
the relationships between privacy guarantee, fingerprint robustness, and
database utility by deriving closed form expressions. The outcome of this
analysis allows us to bound the privacy leakage caused by attribute inference
attack and characterize the privacy-utility coupling and privacy-fingerprint
robustness coupling. Furthermore, we also propose a SVT-based solution to
control the cumulative privacy loss when fingerprinted copies of a database are
shared with multiple recipients.
</details>


<details>
<summary>Personalization, Privacy, and Me (Published on: 2021-09-14T22:09:44Z)</summary>
**Link**: [http://arxiv.org/abs/2109.06990v1](http://arxiv.org/abs/2109.06990v1)
**Updated**: 2021-09-14T22:09:44Z
**Authors**: Reshma Narayanan Kutty, Claudia Orellana-Rodriguez, Igor Brigadir, Ernesto Diaz-Aviles
**Summary**: News recommendation and personalization is not a solved problem. People are
growing concerned of their data being collected in excess in the name of
personalization and the usage of it for purposes other than the ones they would
think reasonable. Our experience in building personalization products for
publishers while adhering to safeguard user privacy led us to investigate more
on the user perspective of privacy and personalization. We conducted a survey
to explore people's experience with personalization and privacy and the
viewpoints of different age groups. In this paper, we share our major findings
with publishers and the community that can inform algorithmic design and
implementation of the next generation of news recommender systems, which must
put the human at its core and reach a balance between personalization
experiences and privacy to reap the benefits of both.
</details>


<details>
<summary>Physical Underpinnings of Privacy (Published on: 2008-03-20T23:46:03Z)</summary>
**Link**: [http://arxiv.org/abs/0803.3096v2](http://arxiv.org/abs/0803.3096v2)
**Updated**: 2008-10-20T10:09:57Z
**Authors**: Joseph M. Renes, Jean-Christian Boileau
**Summary**: One of the remarkable features of quantum mechanics is the ability to ensure
secrecy. Private states embody this effect, as they are precisely those
multipartite quantum states from which two parties can produce a shared secret
that cannot in any circumstance be correlated to an external system. Naturally,
these play an important role in quantum key distribution (QKD) and quantum
information theory. However, a general distillation method has heretofore been
missing. Inspired by Koashi's complementary control scenario (arXiv:0704.3661v1
[quant-ph]), we give a new definition of private states in terms of one party's
potential knowledge of two complementary measurements made on the other and use
this to construct a general method of private state distillation using quantum
error-correcting codes. The procedure achieves the same key rate as recent,
more information-theoretic approaches while demonstrating the physical
principles underlying privacy of the key. Additionally, the same approach can
be used to establish the hashing inequality for entanglement distillation, as
well as the direct quantum coding theorem.
</details>


<details>
<summary>WaveCluster with Differential Privacy (Published on: 2015-08-02T04:41:51Z)</summary>
**Link**: [http://arxiv.org/abs/1508.00192v1](http://arxiv.org/abs/1508.00192v1)
**Updated**: 2015-08-02T04:41:51Z
**Authors**: Ling Chen, Ting Yu, Rada Chirkova
**Summary**: WaveCluster is an important family of grid-based clustering algorithms that
are capable of finding clusters of arbitrary shapes. In this paper, we
investigate techniques to perform WaveCluster while ensuring differential
privacy. Our goal is to develop a general technique for achieving differential
privacy on WaveCluster that accommodates different wavelet transforms. We show
that straightforward techniques based on synthetic data generation and
introduction of random noise when quantizing the data, though generally
preserving the distribution of data, often introduce too much noise to preserve
useful clusters. We then propose two optimized techniques, PrivTHR and
PrivTHREM, which can significantly reduce data distortion during two key steps
of WaveCluster: the quantization step and the significant grid identification
step. We conduct extensive experiments based on four datasets that are
particularly interesting in the context of clustering, and show that PrivTHR
and PrivTHREM achieve high utility when privacy budgets are properly allocated.
</details>


<details>
<summary>Privacy with Estimation Guarantees (Published on: 2017-10-02T01:14:10Z)</summary>
**Link**: [http://arxiv.org/abs/1710.00447v5](http://arxiv.org/abs/1710.00447v5)
**Updated**: 2020-03-20T14:12:00Z
**Authors**: Hao Wang, Lisa Vo, Flavio P. Calmon, Muriel Médard, Ken R. Duffy, Mayank Varia
**Summary**: We study the central problem in data privacy: how to share data with an
analyst while providing both privacy and utility guarantees to the user that
owns the data. In this setting, we present an estimation-theoretic analysis of
the privacy-utility trade-off (PUT). Here, an analyst is allowed to reconstruct
(in a mean-squared error sense) certain functions of the data (utility), while
other private functions should not be reconstructed with distortion below a
certain threshold (privacy). We demonstrate how chi-square information captures
the fundamental PUT in this case and provide bounds for the best PUT. We
propose a convex program to compute privacy-assuring mappings when the
functions to be disclosed and hidden are known a priori and the data
distribution is known. We derive lower bounds on the minimum mean-squared error
of estimating a target function from the disclosed data and evaluate the
robustness of our approach when an empirical distribution is used to compute
the privacy-assuring mappings instead of the true data distribution. We
illustrate the proposed approach through two numerical experiments.
</details>


<details>
<summary>Privacy-preserving Targeted Advertising (Published on: 2017-10-09T19:31:22Z)</summary>
**Link**: [http://arxiv.org/abs/1710.03275v2](http://arxiv.org/abs/1710.03275v2)
**Updated**: 2018-06-18T00:28:51Z
**Authors**: Theja Tulabandhula, Shailesh Vaya, Aritra Dhar
**Summary**: Recommendation systems form the center piece of a rapidly growing trillion
dollar online advertisement industry. Even with numerous optimizations and
approximations, collaborative filtering (CF) based approaches require real-time
computations involving very large vectors. Curating and storing such related
profile information vectors on web portals seriously breaches the user's
privacy. Modifying such systems to achieve private recommendations further
requires communication of long encrypted vectors, making the whole process
inefficient. We present a more efficient recommendation system alternative, in
which user profiles are maintained entirely on their device, and appropriate
recommendations are fetched from web portals in an efficient privacy preserving
manner. We base this approach on association rules.
</details>


<details>
<summary>Privacy-preserving Prediction (Published on: 2018-03-27T18:40:05Z)</summary>
**Link**: [http://arxiv.org/abs/1803.10266v2](http://arxiv.org/abs/1803.10266v2)
**Updated**: 2018-05-09T00:36:56Z
**Authors**: Cynthia Dwork, Vitaly Feldman
**Summary**: Ensuring differential privacy of models learned from sensitive user data is
an important goal that has been studied extensively in recent years. It is now
known that for some basic learning problems, especially those involving
high-dimensional data, producing an accurate private model requires much more
data than learning without privacy. At the same time, in many applications it
is not necessary to expose the model itself. Instead users may be allowed to
query the prediction model on their inputs only through an appropriate
interface. Here we formulate the problem of ensuring privacy of individual
predictions and investigate the overheads required to achieve it in several
standard models of classification and regression.
  We first describe a simple baseline approach based on training several models
on disjoint subsets of data and using standard private aggregation techniques
to predict. We show that this approach has nearly optimal sample complexity for
(realizable) PAC learning of any class of Boolean functions. At the same time,
without strong assumptions on the data distribution, the aggregation step
introduces a substantial overhead. We demonstrate that this overhead can be
avoided for the well-studied class of thresholds on a line and for a number of
standard settings of convex regression. The analysis of our algorithm for
learning thresholds relies crucially on strong generalization guarantees that
we establish for all differentially private prediction algorithms.
</details>


<details>
<summary>Generative Adversarial Privacy (Published on: 2018-07-13T23:40:33Z)</summary>
**Link**: [http://arxiv.org/abs/1807.05306v3](http://arxiv.org/abs/1807.05306v3)
**Updated**: 2019-06-26T04:32:46Z
**Authors**: Chong Huang, Peter Kairouz, Xiao Chen, Lalitha Sankar, Ram Rajagopal
**Summary**: We present a data-driven framework called generative adversarial privacy
(GAP). Inspired by recent advancements in generative adversarial networks
(GANs), GAP allows the data holder to learn the privatization mechanism
directly from the data. Under GAP, finding the optimal privacy mechanism is
formulated as a constrained minimax game between a privatizer and an adversary.
We show that for appropriately chosen adversarial loss functions, GAP provides
privacy guarantees against strong information-theoretic adversaries. We also
evaluate GAP's performance on the GENKI face database.
</details>


<details>
<summary>Understanding Compressive Adversarial Privacy (Published on: 2018-09-21T07:39:50Z)</summary>
**Link**: [http://arxiv.org/abs/1809.08911v2](http://arxiv.org/abs/1809.08911v2)
**Updated**: 2018-10-02T04:18:23Z
**Authors**: Xiao Chen, Peter Kairouz, Ram Rajagopal
**Summary**: Designing a data sharing mechanism without sacrificing too much privacy can
be considered as a game between data holders and malicious attackers. This
paper describes a compressive adversarial privacy framework that captures the
trade-off between the data privacy and utility. We characterize the optimal
data releasing mechanism through convex optimization when assuming that both
the data holder and attacker can only modify the data using linear
transformations. We then build a more realistic data releasing mechanism that
can rely on a nonlinear compression model while the attacker uses a neural
network. We demonstrate in a series of empirical applications that this
framework, consisting of compressive adversarial privacy, can preserve
sensitive information.
</details>


<details>
<summary>Privacy in Blockchain Systems (Published on: 2018-09-27T17:07:44Z)</summary>
**Link**: [http://arxiv.org/abs/1809.10642v1](http://arxiv.org/abs/1809.10642v1)
**Updated**: 2018-09-27T17:07:44Z
**Authors**: Jad Wahab
**Summary**: In this literature review, we first briefly provide an introduction on the
privacy aspect of blockchain systems and why it is a difficult quality to
achieve, especially using traditional methods. Next, we go over a wide range of
different strategies and techniques, along with their respective empirical
implementations. Starting with approaches that attempted to provide privacy on
Bitcoin/existing blockchain systems, then going into more advanced techniques,
such as secure multi-party computations, ring signatures, and zero knowledge
proofs, that construct a more advanced blockchain system from scratch with the
objective of preserving privacy. Finally, we conclude that the current state of
privacy on blockchains still needs work for it to be reliable. Nevertheless,
the field of privacy in this domain is developing and advancing at a rapid
rate.
</details>


<details>
<summary>Incentivising Privacy in Cryptocurrencies (Published on: 2019-01-09T12:30:07Z)</summary>
**Link**: [http://arxiv.org/abs/1901.02695v2](http://arxiv.org/abs/1901.02695v2)
**Updated**: 2019-01-11T14:25:12Z
**Authors**: Sarah Azouvi, Haaroon Yousaf, Alexander Hicks
**Summary**: Privacy was one of the key points mentioned in Nakamoto's Bitcoin whitepaper,
and one of the selling points of Bitcoin in its early stages. In hindsight,
however, de-anonymising Bitcoin users turned out to be more feasible than
expected. Since then, privacy focused cryptocurrencies such as Zcash and Monero
have surfaced. Both of these examples cannot be described as fully successful
in their aims, as recent research has shown. Incentives are integral to the
security of cryptocurrencies, so it is interesting to investigate whether they
could also be aligned with privacy goals. A lack of privacy often results from
low user counts, resulting in low anonymity sets. Could users be incentivised
to use the privacy preserving implementations of the systems they use? Not only
is Zcash much less used than Bitcoin (which it forked from), but most Zcash
transactions are simply transparent transactions, rather than the (at least
intended to be) privacy-preserving shielded transactions. This paper and poster
briefly discusses how incentives could be incorporated into systems like
cryptocurrencies with the aim of achieving privacy goals. We take Zcash as
example, but the ideas discussed could apply to other privacy-focused
cryptocurrencies. This work was presented as a poster at OPERANDI 2018, the
poster can be found within this short document.
</details>


<details>
<summary>Is Privacy Controllable? (Published on: 2019-01-28T16:57:31Z)</summary>
**Link**: [http://arxiv.org/abs/1901.09804v1](http://arxiv.org/abs/1901.09804v1)
**Updated**: 2019-01-28T16:57:31Z
**Authors**: Yefim Shulman, Joachim Meyer
**Summary**: One of the major views of privacy associates privacy with the control over
information. This gives rise to the question how controllable privacy actually
is. In this paper, we adapt certain formal methods of control theory and
investigate the implications of a control theoretic analysis of privacy. We
look at how control and feedback mechanisms have been studied in the privacy
literature. Relying on the control theoretic framework, we develop a simplistic
conceptual control model of privacy, formulate privacy controllability issues
and suggest directions for possible research.
</details>


<details>
<summary>Gaussian Differential Privacy (Published on: 2019-05-07T06:57:19Z)</summary>
**Link**: [http://arxiv.org/abs/1905.02383v3](http://arxiv.org/abs/1905.02383v3)
**Updated**: 2019-05-30T23:51:04Z
**Authors**: Jinshuo Dong, Aaron Roth, Weijie J. Su
**Summary**: Differential privacy has seen remarkable success as a rigorous and practical
formalization of data privacy in the past decade. This privacy definition and
its divergence based relaxations, however, have several acknowledged
weaknesses, either in handling composition of private algorithms or in
analyzing important primitives like privacy amplification by subsampling.
Inspired by the hypothesis testing formulation of privacy, this paper proposes
a new relaxation, which we term `$f$-differential privacy' ($f$-DP). This
notion of privacy has a number of appealing properties and, in particular,
avoids difficulties associated with divergence based relaxations. First, $f$-DP
preserves the hypothesis testing interpretation. In addition, $f$-DP allows for
lossless reasoning about composition in an algebraic fashion. Moreover, we
provide a powerful technique to import existing results proven for original DP
to $f$-DP and, as an application, obtain a simple subsampling theorem for
$f$-DP.
  In addition to the above findings, we introduce a canonical single-parameter
family of privacy notions within the $f$-DP class that is referred to as
`Gaussian differential privacy' (GDP), defined based on testing two shifted
Gaussians. GDP is focal among the $f$-DP class because of a central limit
theorem we prove. More precisely, the privacy guarantees of \emph{any}
hypothesis testing based definition of privacy (including original DP)
converges to GDP in the limit under composition. The CLT also yields a
computationally inexpensive tool for analyzing the exact composition of private
algorithms.
  Taken together, this collection of attractive properties render $f$-DP a
mathematically coherent, analytically tractable, and versatile framework for
private data analysis. Finally, we demonstrate the use of the tools we develop
by giving an improved privacy analysis of noisy stochastic gradient descent.
</details>


<details>
<summary>Privacy-aware Data Trading (Published on: 2020-03-31T01:17:27Z)</summary>
**Link**: [http://arxiv.org/abs/2003.13897v1](http://arxiv.org/abs/2003.13897v1)
**Updated**: 2020-03-31T01:17:27Z
**Authors**: Shengling Wang, Lina Shi, Junshan Zhang, Xiuzhen Cheng, Jiguo Yu
**Summary**: The growing threat of personal data breach in data trading pinpoints an
urgent need to develop countermeasures for preserving individual privacy. The
state-of-the-art work either endows the data collector with the responsibility
of data privacy or reports only a privacy-preserving version of the data. The
basic assumption of the former approach that the data collector is trustworthy
does not always hold true in reality, whereas the latter approach reduces the
value of data. In this paper, we investigate the privacy leakage issue from the
root source. Specifically, we take a fresh look to reverse the inferior
position of the data provider by making her dominate the game with the
collector to solve the dilemma in data trading. To that aim, we propose the
noisy-sequentially zero-determinant (NSZD) strategies by tailoring the
classical zero-determinant strategies, originally designed for the
simultaneous-move game, to adapt to the noisy sequential game. NSZD strategies
can empower the data provider to unilaterally set the expected payoff of the
data collector or enforce a positive relationship between her and the data
collector's expected payoffs. Both strategies can stimulate a rational data
collector to behave honestly, boosting a healthy data trading market. Numerical
simulations are used to examine the impacts of key parameters and the feasible
region where the data provider can be an NSZD player. Finally, we prove that
the data collector cannot employ NSZD to further dominate the data market for
deteriorating privacy leakage.
</details>


<details>
<summary>Learning With Differential Privacy (Published on: 2020-06-10T02:04:13Z)</summary>
**Link**: [http://arxiv.org/abs/2006.05609v2](http://arxiv.org/abs/2006.05609v2)
**Updated**: 2020-06-11T14:11:44Z
**Authors**: Poushali Sengupta, Sudipta Paul, Subhankar Mishra
**Summary**: The leakage of data might have been an extreme effect on the personal level
if it contains sensitive information. Common prevention methods like
encryption-decryption, endpoint protection, intrusion detection system are
prone to leakage. Differential privacy comes to the rescue with a proper
promise of protection against leakage, as it uses a randomized response
technique at the time of collection of the data which promises strong privacy
with better utility. Differential privacy allows one to access the forest of
data by describing their pattern of groups without disclosing any individual
trees. The current adaption of differential privacy by leading tech companies
and academia encourages authors to explore the topic in detail. The different
aspects of differential privacy, it's application in privacy protection and
leakage of information, a comparative discussion, on the current research
approaches in this field, its utility in the real world as well as the
trade-offs - will be discussed.
</details>


<details>
<summary>Security Versus Privacy (Published on: 2020-08-11T02:04:58Z)</summary>
**Link**: [http://arxiv.org/abs/2008.04477v1](http://arxiv.org/abs/2008.04477v1)
**Updated**: 2020-08-11T02:04:58Z
**Authors**: Farhad Farokhi, Peyman Mohajerin Esfahani
**Summary**: Linear queries can be submitted to a server containing private data. The
server provides a response to the queries systematically corrupted using an
additive noise to preserve the privacy of those whose data is stored on the
server. The measure of privacy is inversely proportional to the trace of the
Fisher information matrix. It is assumed that an adversary can inject a false
bias to the responses. The measure of the security, capturing the ease of
detecting the presence of the false data injection, is the sensitivity of the
Kullback-Leiber divergence to the additive bias. An optimization problem for
balancing privacy and security is proposed and subsequently solved. It is shown
that the level of guaranteed privacy times the level of security equals a
constant. Therefore, by increasing the level of privacy, the security
guarantees can only be weakened and vice versa. Similar results are developed
under the differential privacy framework.
</details>


<details>
<summary>Privacy Preserving Passive DNS (Published on: 2020-08-14T15:54:00Z)</summary>
**Link**: [http://arxiv.org/abs/2008.06430v1](http://arxiv.org/abs/2008.06430v1)
**Updated**: 2020-08-14T15:54:00Z
**Authors**: Pavlos Papadopoulos, Nikolaos Pitropakis, William J. Buchanan, Owen Lo, Sokratis Katsikas
**Summary**: The Domain Name System (DNS) was created to resolve the IP addresses of the
web servers to easily remembered names. When it was initially created, security
was not a major concern; nowadays, this lack of inherent security and trust has
exposed the global DNS infrastructure to malicious actors. The passive DNS data
collection process creates a database containing various DNS data elements,
some of which are personal and need to be protected to preserve the privacy of
the end users. To this end, we propose the use of distributed ledger
technology. We use Hyperledger Fabric to create a permissioned blockchain,
which only authorized entities can access. The proposed solution supports
queries for storing and retrieving data from the blockchain ledger, allowing
the use of the passive DNS database for further analysis, e.g. for the
identification of malicious domain names. Additionally, it effectively protects
the DNS personal data from unauthorized entities, including the administrators
that can act as potential malicious insiders, and allows only the data owners
to perform queries over these data. We evaluated our proposed solution by
creating a proof-of-concept experimental setup that passively collects DNS data
from a network and then uses the distributed ledger technology to store the
data in an immutable ledger, thus providing a full historical overview of all
the records.
</details>


<details>
<summary>Privacy Amplification by Decentralization (Published on: 2020-12-09T21:33:33Z)</summary>
**Link**: [http://arxiv.org/abs/2012.05326v4](http://arxiv.org/abs/2012.05326v4)
**Updated**: 2022-03-07T12:37:44Z
**Authors**: Edwige Cyffers, Aurélien Bellet
**Summary**: Analyzing data owned by several parties while achieving a good trade-off
between utility and privacy is a key challenge in federated learning and
analytics. In this work, we introduce a novel relaxation of local differential
privacy (LDP) that naturally arises in fully decentralized algorithms, i.e.,
when participants exchange information by communicating along the edges of a
network graph without central coordinator. This relaxation, that we call
network DP, captures the fact that users have only a local view of the system.
To show the relevance of network DP, we study a decentralized model of
computation where a token performs a walk on the network graph and is updated
sequentially by the party who receives it. For tasks such as real summation,
histogram computation and optimization with gradient descent, we propose simple
algorithms on ring and complete topologies. We prove that the privacy-utility
trade-offs of our algorithms under network DP significantly improve upon what
is achievable under LDP, and often match the utility of the trusted curator
model. Our results show for the first time that formal privacy gains can be
obtained from full decentralization. We also provide experiments to illustrate
the improved utility of our approach for decentralized training with stochastic
gradient descent.
</details>


<details>
<summary>Preference-Based Privacy Trading (Published on: 2020-12-10T07:03:10Z)</summary>
**Link**: [http://arxiv.org/abs/2012.05484v1](http://arxiv.org/abs/2012.05484v1)
**Updated**: 2020-12-10T07:03:10Z
**Authors**: Ranjan Pal, Yixuan Wang, Swades De, Bodhibrata Nag, Pan Hui
**Summary**: The question we raise through this paper is: Is it economically feasible to
trade consumer personal information with their formal consent (permission) and
in return provide them incentives (monetary or otherwise)?. In view of (a) the
behavioral assumption that humans are `compromising' beings and have privacy
preferences, (b) privacy as a good not having strict boundaries, and (c) the
practical inevitability of inappropriate data leakage by data holders
downstream in the data-release supply-chain, we propose a design of regulated
efficient/bounded inefficient economic mechanisms for oligopoly data trading
markets using a novel preference function bidding approach on a simplified
sellers-broker market. Our methodology preserves the heterogeneous privacy
preservation constraints (at a grouped consumer, i.e., app, level) upto certain
compromise levels, and at the same time satisfies information demand (via the
broker) of agencies (e.g., advertising organizations) that collect client data
for the purpose of targeted behavioral advertising.
</details>
