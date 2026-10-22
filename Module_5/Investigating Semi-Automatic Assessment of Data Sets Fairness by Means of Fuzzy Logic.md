# Investigating Semi-Automatic Assessment of Data Sets Fairness by Means of Fuzzy Logic

**Chiara Gallese**
Department of Electrical Engineering
Eindhoven University of Technology
chiara.gallese@mensa.it

**Luca Manzoni**
Department of Mathematics and Geosciences
University of Trieste
lmanzoni@units.it

**Teresa Scantamburlo**
Department of Environmental Sciences, Informatics and Statistics
Ca' Foscari University of Venice
European Centre for Living Technology
teresa.scantamburlo@unive.it

**Marco S. Nobile**
Department of Environmental Sciences, Informatics and Statistics
Ca' Foscari University of Venice
Department of Industrial Engineering & Innovation Sciences
Eindhoven University of Technology
marco.nobile@unive.it

**Abstract**—Research has shown how data sets contains social bias in AI systems, especially those based on machine learning. A biased data set is not representative of reality and might contribute to perpetuate societal biases within the model. To tackle this problem, it is important to understand how to avoid biases, errors, and unethical practices while creating the data sets. In this work we offer a preliminary framework for the semi-automated evaluation of fairness in data sets, by combining statistical information about data with qualitative consideration. We address the issue of how much (un)fairness can be included in a data set used for machine learning research, focusing on classification issues. In order to provide guidance for the use of data sets in contexts of critical decision-making, such as health decisions, we identify six fundamental features (balance, numerosity, unevenness, compliance, quality, incompleteness) that could affect model fairness. We developed a rule-based approach based on fuzzy logic that combines these characteristics into a single score and enables a semi-automatic evaluation of a data set in algorithmic fairness research.

**Index Terms**—Data Bias, Fairness, Trustworthy Artificial Intelligence, Fuzzy Logic

## I. INTRODUCTION

Data is one of the most common source of algorithmic discrimination, a problem studied since the nineties and referred to “computer systems that systematically and unfairly discriminate against certain individuals or groups” [1]. Scholars and activists already showed how data sets convey social bias in modern AI systems—in particular those based on machine learning—for relevant examples consider unfair outcomes in semantic representation [2], face recognition [3], clinical decisions [4], speech recognition [5] and text generation [6] among others. However, the bulk of works has mostly focused on models, rather than data, and produced a vast array of metrics to measure fairness in the algorithmic outputs [7].

The evaluation of algorithmic fairness in the context of data was comparatively much more limited and concerned, by and large, with transparency and documentation processes. This work aims to extend this body of research by providing a framework for the automated assessment of fairness in data sets. In particular, the problem we want to address is the following: given a data set to be used in machine learning research$^1$, how much (un)fairness can be injected by it? To answer this question we identify six fundamental features (balance, numerosity, unevenness, compliance, quality, incompleteness) that could impinge on model fairness and offer guidance in the use of data sets in contexts of critical decision-making, such as health decisions, regardless of the model used. Based on Fuzzy Logic, we elaborated a rule-based system that combines these features into a single score and allows a semi-automatic assessment of a data set in algorithmic fairness research. Our contribution is twofold: first, we identified a set of fairness indicators to support policy decisions about data use in a flexible way – i.e. allowing adaptations depending on the context of the application (e.g. the domain and the existing laws); second, we introduced a rule-based method to measure the (un)fairness induced by a data set.

So far, the assessment of algorithmic fairness in the context of data sets has followed two main directions. A research track regards the analysis of data curation processes or the development of new documentation frameworks [8], [9]. Recently, [10] annotated hundreds of data sets employed in algorithmic research efforts specifying key fairness-related characteristics (e.g. the domain of application, the target task and the sensitive attributes encoded in the data set) in order to address the so-called "documentation debt" [11]. Another direction focuses on the empirical analysis of fairness-related data dimensions. These efforts include pre-processing techniques such as sanitisation and instance re-weighting (for an overview see [12]) and procedures evaluating distinct sources of discrimination in data collection [13] or studying the effect of data-related factors on the fairness of algorithms [14].

Our work moves along the line of this empirical research

$^1$Note that for the sake of simplicity we focus on classification problems.

979-8-3503-1017-7/23/$31.00 ©2023 IEEE

***

with some important distinctions. The fairness-related features we explore are agnostic about the sensitive attribute in that they capture essential vulnerabilities that may contribute to model (un)fairness. Another distinct aspect of our approach is to integrate statistical information about the data sets (balance, numerosity, unevenness, incompleteness) with qualitative consideration (compliance, quality) which take into account legal and ethical requirements of data-related practices, e.g. the General Data Protection Regulation (GDPR) and principles of research integrity [15]. This integration is operated through the application of fuzzy rule-base logic and reflected in a score that can be indicative of the fairness potentially introduced by a given data set. Differently from the work of Alowairdhi and Ma, in this work we do not use fuzzy logic to assess the respect of FAIR principles (findability, accessibility, interoperability, and reusability) [16] of a digital resource [17], which the authors define with the word FAIRness, but we rather use it to quantify and integrate multiple metrics of a data set and assess the overall fairness of the whole resource. In fact, we focus on a different topic, integrating the ethical principles regarding fairness with those found in the law literature.

[IMAGE: Figure 1. Diagram illustrating the interaction between FAnFAIR, Data, and different practitioners (Lawyers, AI developers, Doctors, Patients) involved in data use. Arrows show data use, collection, compliance checks, assessment, evaluation, and creation among the entities.]

**Fig. 1. The interaction between FAnFAIR, the data, and the different practitioners involved in their use.**

Mainstream works in computer science addresses the problem of fairness in a context of prediction-based decisions [18]. Usually, mathematical definitions requires achieving parities across distributions of outcomes or scores (common examples include statistical parity and calibration, for an overview of popular metrics see [19]). Definitions can refer to individuals (e.g., requiring that similar individuals are treated similarly) or groups (e.g., requiring that any error measure is equal across groups, defined by so-called protected characteristics like gender or race). Mathematical definitions can reflect philosophical conceptualisations, such as the equality of outcomes and the equality of opportunities, and previous studies attempt to connect these complex, distinct literature [20], [21]. In general, computer science literature expresses in empirical and formal terms philosophical problems of distributive justice in which the goal of fairness is to achieve an equal allocation of goods [22].

Since there is no consensus among academics on this subject, algorithmic fairness research has led to the development of numerous mutually incompatible frameworks and formal notions of fairness in AI [23]. Furthermore, as Birhane points out, a lot of the proposed theories only focus on technical improvements and fail to prioritise the people and communities that are disproportionately affected, while "automated and standardised solutions to complex and contingent social issues often contribute more harm than good—they often fail to grasp complex problems and provide a false sense of solution and safety. Complex social issues require historical, political, and moral awareness, and structural change" [24].

Along this line of research, Tubella et al. designed the ACROCPoLis framework, tanking into consideration "Actors, Context, Resources, Outcome, Criteria, Power, and Links", in order to "provide the means to represent more accurately the elements and relations that should underlie assessments of the fairness of a process and/or situation, and that can help reveal where disagreements lie when conflicting fairness assessments are defended by different parties" [23].

If we refer to the ACROCPoLis categories, our work identifies four different stakeholders in the ‘Actors' category: the doctors who collect the data and assess its quality; the domain experts who perform the compliance; the AI experts who will use the data set; and the patients whose data is processed, as shown in Figure 1. The compliance elements can be seen both under the lens of the **Context** and those of the **Resources**, while the other elements we identified fall under the ‘Criteria' category. While ‘Power' and ‘Outcome' are strictly dependent on the organisational model surrounding data processing.

The concept of fairness is frequently found also in text of law and it has been extensively analysed by the legal scholarship, having its roots in the "bona fide" concept in Roman law [25], and it is this concept that we are considering in the present work. The fairness principle is an overarching obligation in the European Digital Strategy, for example in Art. 5, par. 1, of GDPR, and in the Data Act, but it is also found in the EU and in other countries in many pieces of law, such as Art. 8, par. 2, of the Charter of Fundamental Rights of the European Union, contract law [26], and others [27].

The data protection law scholarship divide the fairness principle into two elements, procedural fairness and fair balancing [28], noting that the concept of fairness is related to data subjects, who are in a vulnerable position as opposed to data controllers, therefore it tries to make a balance between the fundamental rights and freedoms of the former and the interests of the latter.

However, although in this paper we take into consideration GDPR, we do not limit the concept of (legal) fairness to data protection law, but we expand the notion to other areas of law, including the non-discrimination principle, that is found, *inter alia*, in the European Convention of Human Rights [29], the equity principle [30], and the *bona fide* principle in contractual agreements [31]. In our opinion, a data set which data collection has been flawed by discrimination or another breach of the

***

law (e.g., copyright law, criminal law, medical law) cannot be considered fair. The lawfulness criteria is also in line with the High-Level Expert Group on AI (AI HLEG)'s guidelines on Trustworthy AI [32].

## II. FUZZY LOGIC AND SIMPFUL

Fuzzy Logic (FL) is one form of many-valued logic that deals with approximate reasoning, in order to handle uncertain or vague concepts. FL allows computers to make partially informed decisions by taking into account imprecise, approximate, or uncertain data which gives it the ability to handle complex real-world scenarios. The concept at the core of FL is the fuzzy set, which extends traditional set theory with the possibility of elements to have a membership degree ranging from 0 (the element does not belong to the set) to 1 (the element fully belong to the set), allowing for partial membership corresponding to all intermediate values. As a consequence, in fuzzy set theory the elements can belong to multiple (possibly disjoint) sets simultaneously with different degrees of membership. In order to associate elements to membership degrees, a membership function (MF) must be defined. The simplest and most intuitive form is the triangular membership (see some examples in Figure 2), which is easy to interpret and already allows for modelling the transition between fuzzy sets. For this preliminary work, we assume normalised triangular fuzzy sets (i.e., the sum of the memberships values for any element of the universe of discourse is always 1), although more complex MFs could be exploited to refine the characterisation of each variable.

Multiple fuzzy sets can be used to characterise linguistic variables, that is, variables whose values are words or sentences expressed in a natural language. For instance, a linguistic variable "room temperature" could take values "cold" or "warm". Linguistic terms are associated to fuzzy sets that characterise the membership of any possible value in the universe of discourse to that set. Given an arbitrary temperature, we can evaluate the membership of that value to both fuzzy sets. For instance, if the room temperature is 25 degrees, the membership degree to the set "cold" will be very low, while the membership degree to the set "warm" will be quite high.

Linguistic variables and linguistic terms can be composed with logical connectors to form fuzzy rules, which are IF/THEN sentences representing implications (i.e., antecedents leading to some consequence) under specific circumstances. Specifically, a fuzzy rule takes the form:

$$
\text{IF } X \text{ is } a \text{ THEN } Y \text{ is } b,
$$

where X and Y are linguistic variables, a is one of X's linguistic terms, and b is a linguistic term for Y or some function used to calculate the output. Due to fuzzy sets, the antecedent can be satisfied to a certain degree; in turn, the whole rule is satisfied with a degree that ranges from 0 (not satisfied) to 1 (fully satisfied). A fuzzy inference system typically has multiple rules, covering all relevant cases. We will denote the degree of satisfaction of the i-th rule by $w_i \in [0, 1]$. Each rule produces an output value, which is denoted by $z_i$. Multiple fuzzy rules are thus evaluated and aggregated using a fuzzy inference method, which is responsible for the calculation of the final output value, according to the degree of satisfaction of each rule. In this work we exploit a 0-order Takagi-Sugeno inference system [33], which calculates the final output of the system as follows:

$$
\text{output} = \frac{\sum_{i=1}^N w_i z_i}{\sum_{i=1}^N w_i}
\quad (1)
$$

where $N$ is the number of rules, $w_i$ is the degree of satisfaction of the $i$-th rule, and $z_i$ is the output constant specified in the consequent of the $i$-th rule. To build our inference system, we exploited the Simpful Python library, which is designed to simplify and streamline the building of fuzzy models [34]. Simpful provides a set of components for the definition of fuzzy sets, linguistic variables, and fuzzy rules. In order to facilitate the definition of the rule-base and assist the interpretation of the whole model—fuzzy rules can be entered as strings of natural text. Simpful is totally flexible, so that membership functions and fuzzy rules can have arbitrary complexity. Simpful supports multiple reasoning systems, including the 0-order Takagi-Sugeno reasoning, which was used in this work.

## III. FANFAIR: AUTOMATIC ASSESSMENT OF DATA SET FAIRNESS USING FUZZY LOGIC

In order to assess the potential fairness of a data set, we identified six different elements that should be addressed before employing the data set. Table I summarises the features considered for this work and gives a brief explanation of their role. To identify each criteria, we were inspired by general principle of civil law and EU law, and established ethics guidelines [35]. We will now provide a detailed explanation of the rationale of each variable, along with the mathematical formalisation of their calculation. In what follows, we denote by $S \in \mathbb{N}$ the number of instances in the data set. $D \in \mathbb{N}$ represents the number of features in the data set.

We denote by $\mathbf{x}_d, d=1,\ldots,D$, the vector of values of the $d$-th variable in the data set. $X_{d,s}$ denotes the value of the $d$-th variable of the $s$-th sample of the data set, where $s=1,\ldots,S$. We use the symbols $\mu_d$ and $\sigma_d$ to denote the mean and standard deviation, respectively, calculated on $\mathbf{x}_d$. We will denote by $\mathbf{y}$ the vector of output values (e.g., labels).

### A. Balance

A data set can be defined as "balanced" if all classes are well represented in the data set. The importance of balance is described in a wealth of literature: an unbalanced data set may produce biased models, unable to generalise and with prejudicial effects [36] on single individuals or entire categories of individuals, such as disparity in accuracy [37], [38].

For example, if a data set, which is used to train a model aimed at classifying patients in healthy or non-healthy, contains thousands of examples of patients with a disease and only a few example of healthy individuals, the model will probably be unable to recognise healthy individuals with high accuracy.

***

[IMAGE: Figure 2. Six graphs showing the membership degree (Y-axis, ranging from 0.0 to 1.0) for two linguistic terms ('low' and 'high') across the universe of discourse (X-axis) for the six linguistic variables: `balance`, `numerosity`, `outliers`, `compliance`, `quality`, and `incompleteness`. All graphs show triangular membership functions intersecting at 0.5/0.5, with 'low' decreasing and 'high' increasing with value.]

**Fig. 2. The six linguistic variables used by FAnFAIR's rule-based system.**

## TABLE I
**DESCRIPTION OF THE DATA SET FEATURES / LINGUISTIC VARIABLES CONSIDERED IN THIS WORK.**

| Feature | Meaning |
| :--- | :--- |
| **balance** | How balanced is the data set, with respect to the output labels. |
| **numerosity** | The numerosity of instances with respect to the number of features. |
| **unevenness** | A metric assessing the amount of outliers in the data set. |
| **compliance** | How much the data set is compliant with respect to governmental rules. |
| **quality** | A user-defined evaluation of the overall quality of the data set. |
| **incompleteness** | This metric measures the amount of missing data in the data set. |

It is therefore crucial to have a similar number of examples in each class.

Formally, we calculate a normalised balance as follows. We begin by calculating the frequency of each class in the data set. Then, we divide by the number of instances to obtain the vector of the ratio of each class. We use that information to calculate the standard deviation of the ratio vector: intuitively, a standard deviation $\sigma=0$ corresponds to a perfectly balanced data set. On the contrary, the worst case scenario is the case in which there is only one class in the data set (i.e., the ratio is 1 for one class, and 0 for all the other classes). We denote by $\sigma^*$ the standard deviation calculated in the latter case. Therefore, $\frac{\sigma}{\sigma^*} \in [0, 1]$ is a measure of similarity of the current data set with a completely imbalanced one. We can finally assess the balance of the data set as follows: $\text{balance} = 1 - \frac{\sigma}{\sigma^*}$.

### B. Numerosity

This data set feature refers to the quantity of instances normalised by the number of features in the data set. The quantity is important in order to mitigate possible biases in the model output: a model with a low number of examples will not be able to generalise.

To show an example of why this can happen, consider the situation in which all the features have no relation with the outputs to be predicted. In that case, we would like to have a machine learning algorithm to be unable to perform well since there is actually no relation between the inputs and the outputs: any learned relation will be purely the effect of chance, it will not be representative of the phenomenon being modelled, and will clearly be unable to generalise. However, when there are more features than instances in a data set, there are multiple results showing that we can "fit perfectly” the training set with a linear relations, the simplest possible class of models.

Formally, this undesirable situation happens when linear systems $\mathbf{A}\mathbf{x} = \mathbf{b}$, with $\mathbf{A}$ the $S \times D$ matrix of the inputs and $\mathbf{b}$ the output vector, has a solution when $\mathbf{A}$ and $\mathbf{b}$ are random. It has been shown [39] that random linear systems with more variables (features) than equations (instances) are solvable with probability 1, i.e., even with random data it is possible to predict exactly all the output values using a linear relation. In fact, there is actually a sharp transition between almost-certain solvability and almost-certain unsolvability that depends on the actual distribution of of the random data and on the ration between the number of variables and equations [40].

Since we want to learn relations that actually exist for the real phenomenon from which the samples comprising a data set were taken, we want to be at least in a situation in which "random data" do not give us a solvable system $\mathbf{A}\mathbf{x} = \mathbf{b}$. Thus, it is important to have a ratio $\alpha = \frac{S}{D}$ between number of instances and features that is large enough to avoid the creation of spurious relations.

In this example we considered only the case of spurious linear relations, without considering relations expressible only with more complex (non linear) functions. In more general case, when the hypothesis space (e.g., the set of all functions representable by a specific network architecture) is known, the size of the training sample can be assessed through the Vapnik-Chervonenkis (VC) dimension, expressing the number of distinct instances that can be discriminated by an hypothesis space (for an introduction see [41], chapter seven). Hence, if we have less samples than the VC dimension of the hypothesis space, we know that we will be able to find a model that fits all the data. In that case we can consider the numerosity requirement not satisfied since no generalisation is required to and even pure noise could be learnt.

A deeper issue in using the VC dimension is, however, the assumption that we already know the hypothesis space. That is, not only the general technique to use but, for example, the exact network architecture. This is generally not feasible when building a data set, since no assumptions can be made on the techniques that will be used to develop the model.

As a minimal requirement, we assume to have a sufficient numerosity at least for linear functions, where a widespread rule of thumb suggests that an optimal number of instances $S$ would be $10 \times D$ [42]. This leads to the definition of a universe of discourse $[0, 10]$ for this linguistic variable, so that the feature is calculated as $\text{numerosity} = \min(10, \alpha)$. Intuitively, the data set has optimal numerosity when $\alpha \geq 10$, as shown in the corresponding membership functions of Figure 2.

### C. Unevenness

This feature refers to the number of outliers in the examples. If a value is very different from all other values in the data set, it is important to understand why this occurs. For example, in a data set made of physiological values of non-healthy patients, in the weight column we could find abnormal values (too high or too low). The domain expert will certainly understand that an adult individual cannot have a weight of 100 grams or of 20000 kilograms, and therefore there is an error in the data collection.

However, outliers might sometimes be just individuals with unique features with respect to the average, such as a patient with a weight over 600 kilograms. In this case, there is a risk of singling out and the patient's identity will likely be recognised if the data set is released to the public.

In addition to the risk for privacy, it is important to note that outliers are not useful for the model, since they refers to particular cases which might better be assessed individually by the domain expert instead of by an automatic mean such as an AI model. The model will not be able to generalise and give an accurate output for outliers' cases. Instead, it would be more useful to create a different model specifically calibrated to individuals who present abnormal values.

Several methods to detect and process outliers in data exist [43]. In this preliminary study, we assume that our data is normally distributed so that we can rely on z-scores, a simple and efficient way to detect outliers in a vector of numbers. The z-score for a value $X_{d,s}$ is calculated as: $z_{d,s} = \frac{X_{d,s} - \mu_d}{\sigma_d}$. For simplicity, we do not exploit a Bonferroni correction and we use the heuristic to label as outliers all values such that $z_{d,s} > 3$. All z-scores are computed using the stats module offered by the scipy library. We then create a matrix $\mathbf{U} \in \{0,1\}^{S \times D}$ where an element $U_{d,s}$ is calculated as follows:

$$
U_{d,s} =
\begin{cases}
1 & \text{if } z_{d,s} > 3, \\
0 & \text{otherwise}.
\end{cases}
\quad (2)
$$

The total number of outliers, across all variables, is finally divided by the overall number of values in the data set to assess the **Unevenness** score, that is:

$$
\text{unevenness} = \frac{\sum_{d=1}^D \sum_{s=1}^S U_{d,s}}{S \times D}
\quad (3)
$$

We assume that a data set with a ratio of outliers greater than or equal to 0.1 is already extremely uneven, so that the universe of discourse is limited to $[0, 0.1]$.

### D. Compliance

**Compliance** refers to a set of rules that must be respected by law in each country, such as copyright law, privacy, medical law, and such. We were inspired by the EU law and civil law systems, but the model can be easily adapted to other legal system as well. We understand that the concept of fairness might be different in each culture around the world and that different populations might have a different sensibility.

The compliance to applicable laws and regulations is not *per se* sufficient to determine the ethics degree of a data set, but it is an essential part of it. The lawfulness criteria is one of the three pillar of Trustworthy AI as set by the AI HLEG [32]: employing illegally collected data to feed an AI model is certainly unethical and unfair.

We selected five criteria that are relevant to assess the fairness of a data set in relation to compliance:
1) **Data Protection law:** Anonymization, Legal Basis, Data Protection Impact Assessment, Legitimate Interest Assessment, Transfer Impact Assessment, Re-use Impact Assessment, Contracts, Data Minimization, Data Retention, Data Subjects Rights, Transparency Obligations
2) **Copyright law**
3) **Medical law:** Informed Consent, Ethical Review, Clinical and Diagnostic Regulations
4) **Non-discrimination law:** Fairness Principle
5) **Ethics:** Accountability, Dignity and Self-Determination, Traceability, involvement of stakeholders, Risk assessment, Impact on Society

The first criterion is related to the compliance to data protection laws and regulations, such as GDPR, Convention 108+, etc. These rules may apply even to anonimized data sets. The elements that must be taken into account in order and on the I on the contractual provisions between the data owner and the data utiliser. In order to be legal, both data collection and data utilisation must comply with those rules.

The third criterion is related to national laws in the medical sector, which is different in each country. Requirements regarding consent, age, reuse of data, the possibility of using deceased individuals' data and such may vary to a great extent to comply with the applicable law, in addition to all other principles drawn by GDPR, are at least the following:

*   **Anonymization:** if the data set need to be anonymized, the process must ensure that no re-identification is possible;
*   **Legal Basis:** the data collection and re-use must have an appropriate legal basis (in accordance with Art. 6 GDPR), e.g., consent, legitimate interest, contract, law;
*   **Data Protection Impact Assessment (DPIA):** in the cases mentioned by the European Data Protection Board or the national Data Protection Authority, an impact assessment must be carried out (in accordance with Art. 35 GDPR);
*   **Legitimate Interest Assessment (LIA):** in case of legitimate interest as a legal basis, a LIA must be carried out in order to determined if such interest exists, if it is not overridden by the interests or fundamental rights and freedoms of the data subjects, and if the "processing is necessary for the purposes of the legitimate interests pursued by the controller or by a third party" (Art. 6 GDPR);
*   **Transfer Impact Assessment:** if the data is transferred outside the EU (for example because it is stored on a server located in a third country), a careful assessment of the impact, risks, and security implications of the transfer must be performed, as required by GDPR;
*   **Re-use Impact Assessment (RIA):** according to GDPR, data can be reused only for purposes that are compatible with the original purposes for which the data were originally collected and processed, therefore, a careful assessment regarding compatibility must be carried out;
*   **Contracts:** in case of data transfer or joint constrollership, an appropriate data agreement must be signed by the interested parties, according to the different privacy roles (Art. 28 GDPR);
*   **Data Minimization:** only the minimum amount of data necessary to reach the processing purposes can be collected or employed (Art. 5 GDPR);
*   **Data Retention:** data can be kept only for the minimum amount of time sufficient to fulfil the data processing purposes, and after that time it must be deleted (Art. 5 GDPR);
*   **Data Subjects Rights:** the exercise of data subjects' rights must be ensured (Articles 12-22 GDPR);
*   **Transparency Obligations:** all transparency obligations, such as informed consent and privacy notices, must be respected, in accordance with GDPR and other applicable laws.

The second criterion is related to intellectual property law, such as licensing. The specific applicable law and the copyrights vary depending on the country, on the purposes of utilisation, depending on the place in which the data is collected.

The fourth criterion is related to the non discrimination principle in national and international law and to the respect of fundamental rights of data subjects. Marginalised groups (e.g., women, foreigners, persons with a disability, neurodivergent individuals) often face discrimination in the medical practice and the collection of their data might be less accurate or less extensive, leading to a lower standard of care. In addition, the uses of the AI model trained on their data might perpetuate societal bias and have a detrimental impact on their lives. In order to ensure fairness, these circumstances need to be taken into account since the first stages of the data collection.

The fifth and last criterion is related to ethical principles to be applied since the first phases of the data collection, such as:

*   **Accountability:** this principle is present in GDPR but it is also an important ethical principle even when personal data are not involved. It means that there must be someone who takes responsibility for actions, decisions and consequences of data collection and use;
*   **Dignity and Self-Determination:** even when data collection and use is permitted by law, human dignity should be respected and individuals should have the right to decide how their data is used (e.g., in case of deceased individual, their will should be respected);
*   **Traceability:** it should always be possible to trace back when, how, and by whom the ethical assessment was performed;
*   **Involvement of stakeholders:** the persons on whom the data processing will have an impact should be heard and their opinion should be taken into account;
*   **Risk assessment:** an assessment of ethical issues and risks should be carried out since the beginning of the data collection;
*   **Impact on Society:** the impact of the data use on society should be careful assessed and risks should be mitigated with appropriate measures.

Due to its nature, the **Compliance** variable cannot be computed automatically from data, as the legal requirements may vary depending on the country of data collection and data usage, on the type of data, and, in general, on different circumstances occurring in each specific situation. The user must manually set the value of this variable by using the $\text{set\_compliance}$ method of the **FAnFAIR** object. In particular, the user must pass as argument a dictionary where the items are the five criteria names, and the associated data are the Boolean values denoting whether that criterion is satisfied or not.

[IMAGE: Figure 3. Four graphs showing membership degrees for linguistic variables: `compliance`, `quality`, and `incompleteness` for UCI's Wisconsin Breast Cancer data set. The compliance graph shows a value of 4, quality shows a value of 0.6, and incompleteness shows a value of 0.05. A fourth graph for a variable not labeled is also present.]

**Fig. 3. Membership values calculated for UCI's Wisconsin Breast Cancer data set.**

### E. Quality

This feature refers to the quality of data as assessed by the domain expert (such as if an image is clear or complete, or if the sound can be recognised in a recording).

The domain expert will make an assessment about the quality of the data set, based on the state of the art in the specific field (such as medical imaging) and on the needs related to each specific model. This step is needed because the data collection is often performed by different people without direct supervision (e.g., nurses, young medical trainees, students, etc.), therefore errors in acquiring clear data may occur.

Aspects of data quality may regard the design of the annotation scheme and process. Large data collections (e.g. those based on crowdsourcing platforms may pose challenges to the quality of labels, and issue that is particularly critical in high-stake domains such as medicine. Often, quality controls involve the assessment of annotators' performance or the measurement of consistency of annotators' assignments. In the medical domain [44] investigates the experience of medical experts partnering with AI practitioners to ensure data quality in image labelling tasks.

In this paper we adopt an holistic approach to data quality allowing experts to set the value of this variable manually by using the $\text{set\_quality}$ method of the **FAnFAIR** object. The value assigned to this variable may reflect broader considerations and reasoning based on domain-specific criteria (e.g. meaningfulness, clarity of annotation instructions, transparency of annotation scheme, etc) similar to those elaborated by fact-checking organizations [45].

### F. Incompleteness

This feature refers to "holes" in the data set regarding relevant elements, such as missing information about a patient in one or more physiological values. When this circumstance occurs, it is necessary to exploit imputation techniques or to discard the patient from the data set altogether, if too little information is provided.

There are three possible types of incomplete data sets:
1) some variables (e.g., dataframe columns) may have missing values. For instance, this might happen when the variable is related to some exam that is only administered to very specific patients;
2) some instances (e.g., dataframe rows) may have missing values. For instance, this might happen to fragile patients that cannot undergo some treatments or exams;
3) finally, the holes can be randomly distributed across all variables and instances of the data sets.

For simplicity, in this preliminary work we assume the last circumstance, so that **Incompleteness** is calculated as the ratio between valid values and NaNs in the data set. Formally, we build an additional matrix $\mathbf{I} \in \{0,1\}^{S \times D}$ where an element $I_{s,d}$ is calculated as follows:

$$
I_{s,d} =
\begin{cases}
1 & \text{if NaN,} \\
0 & \text{otherwise.}
\end{cases}
\quad (4)
$$

Finally, similarly to the Unevenness score, we calculate the Incompleteness value as: $\text{incompleteness} = \frac{\sum_{d=1}^D \sum_{s=1}^S I_{s,d}}{S \times D}$. The universe of discourse of this variable ranges from 0 (all values are valid) to 1 (the data set is completely empty).

### G. FAnFAIR's fuzzy rule-base

The six linguistic variables described in the previous subsections are designed to capture the main sources of "unfairness" in data sets used for machine learning. A summary of the fuzzy sets, and the corresponding membership functions, is shown in Figure 2. In order to calculate a single fairness score $\phi$, that encompasses all the information about the data set, we exploit a 0-order Takagi-Sugeno fuzzy inference system [33]. Table II

reports the twelve rules used in this preliminary work.

## TABLE II
**RULE-BASE USED BY FANFAIR FOR THE ASSESSMENT OF DATA SET FAIRNESS.**

| | | | |
| :--- | :--- | :--- | :--- |
| **Rule 1:** | IF balance IS high THEN $\phi$ IS high\_fairness | **Rule 7:** | IF compliance IS high THEN $\phi$ IS high\_fairness |
| **Rule 2:** | IF balance IS low THEN $\phi$ IS low\_fairness | **Rule 8:** | IF compliance IS low THEN $\phi$ IS low\_fairness |
| **Rule 3:** | IF numerosity IS high THEN $\phi$ IS high\_fairness | **Rule 9:** | IF quality IS high THEN $\phi$ IS high\_fairness |
| **Rule 4:** | IF numerosity IS low THEN $\phi$ IS low\_fairness | **Rule 10:** | IF quality IS low THEN $\phi$ IS low\_fairness |
| **Rule 5:** | IF unevenness IS high THEN $\phi$ IS low\_fairness | **Rule 11:** | IF incompleteness IS high THEN $\phi$ IS low\_fairness |
| **Rule 6:** | IF unevenness IS low THEN $\phi$ IS high\_fairness | **Rule 12:** | IF incompleteness IS low THEN $\phi$ IS high\_fairness |

The consequents' possible output values are: low\_fairness=0, high\_fairness=100. The fuzzy reasoner was implemented using Python and the Simpful library [34]. FAnFAIR is open source and available as python package, so that it can be easily installed with pip.

## IV. RESULTS

In this section, we apply **FAnFAIR** to two well-known public data sets from the UCI library: the Wisconsin breast cancer and the Parkinson data sets. These tests represent two practical use cases to investigate the feasibility of our approach. We discuss our results and the fairness estimated by our method; however, being a preliminary investigation, our goal is to discuss the methodology and not to assess the actual fairness of these data sets. In all tests that follow, we run **FAnFAIR** using the following python packages: scipy v1.7.3, numpy v1.21.6, simpful v2.10.

### A. Use case 1: the Wisconsin Breast Cancer data set.

The first use case was the Wisconsin Breast Cancer data set$^2$ from the UCI Machine Learning Repository [46]. The data set describe the textural features of the cell nuclei (e.g., smoothness, fractal dimension). Specifically, it refers to digitised images of fine needle aspirates of breast mass.

We analysed the data set's metadata in order to assess the compliance requirements. In the original version of the data set, it is specified that "Samples arrive periodically as Dr. Wolberg reports his clinical cases", but no information is provided regarding informed consent, medical consent, and other elements regarding Data Protection Law and ethical review. However, since the data set is quite old and it would be impossible to retrieve this information from patients, we assumed that the hospital correctly took care of these aspects. Regarding copyright issues, the license is clearly stated and it allows the reuse of the data set. The overall **Compliance** score for this data set was then set to 4.

You can see the output of **FAnFAIR** applied to this data set in Figure 3. The first thing that can be observed is that the data set has very low incompleteness and very low unevenness. The data set is not perfectly but reasonably balanced (212 malignant vs 357 benign instances). The data set also has high numerosity, which is automatically capped to 10 by **FAnFAIR**. The final fairness score calculated by the fuzzy reasoner on the Cancer data set was $\phi = 84\%$, which would make it well suitable for research.

### B. Use case 2: Parkinsons data set.

The second use case that we tested was the Parkinsons data set$^3$ from the UCI Machine Learning Repository [47]. The data set is composed of a range of biomedical voice measurements from 31 people, where 23 suffer from Parkinson's disease. The columns of the data set correspond to 23 specific voice measures (e.g., average vocal fundamental frequency, jittering, shimmer); the 195 rows corresponds to vocal recording from these individuals [48]. Similarly to the previous use case, we analysed the data set's metadata in order to find information about the data source; however, we were unsuccessful, since the data collection was not described in the data set nor in the related publication. We decided to hence give a negative score in the Ethics **Compliance**, while we assumed the Data Protection Law requirements were carefully respected since the paper was supported by a NIH grant. The Copyright Law has a positive score since the license allowing the reuse is clearly indicated. Overall, we assigned a 3 to the **Compliance** score of this data set.

According to our results, shown in Figure 4, it is immediately clear that the data set is not well balanced ($<50\%$). As a matter of fact, the data set contains 147 positive instances vs 48 negative instances. Although it is probably possible to counterbalance the circumstance by using under- or over-sampling methods, the fairness of the data set is nevertheless affected since this class of methods might introduce a slight bias in the model downstream. Finally, the data set does not have NaN values (i.e., incompleteness is zero), so that imputation is not necessary. The data set has good numerosity (8.86), and very low unevenness (0.01). The final fairness score assessed by **FAnFAIR** is $\phi = 75\%$. One important feature of this data set is that many entries refer to the same patient. Thus, although **FAnFAIR** calculated a high numerosity score, many instances are correlated since they come from the same patient. This

$^2$https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic)
$^3$https://archive.ics.uci.edu/ml/datasets/parkinsons

***

[IMAGE: Figure 4. Graphs showing membership degrees for linguistic variables: `balance`, `numerosity`, and `unevenness` for UCI's Parkinsons data set. The balance graph shows a value of approximately 0.25, numerosity shows 8.86, and unevenness shows 0.01.]
[IMAGE: Figure 4 (continued). Graphs showing membership degrees for linguistic variables: `compliance`, `quality`, and `incompleteness` for UCI's Parkinsons data set. The compliance graph shows a value of 3, quality shows 0.6, and incompleteness shows 0.0.]

**Fig. 4. Membership values calculated for UCI's Parkinsons data set.**

circumstance can hamper the generalization, lead to a bias during the training phase and, in turn, affect the overall fairness of the data set. Unfortunately, the fact that some instances come from a same patient cannot be detected automatically from data, for it is an information that belongs to either the meta-data or is merely reported in the article associated to the data sets. We can envision the use of NLP to automatically infer similar circumstances, but that goes beyond the scope of this work.

## V. CONCLUSION

In this paper, we presented **FAnFAIR**, a python package for the semi-automatic assessment of fairness in data sets. **FAnFAIR** is based on a fuzzy rule-based system that estimates the fairness based on six input linguistic variables: balance, numerosity, unevenness, compliance, quality, and incompleteness. These variables represent important characteristics that are automatically extracted by the data set or (in the case of compliance and quality) are entered by the user. **FAnFAIR** returns a summary of the contribution of all variables to the final fairness value. The contributions are expressed both in fuzzy terms (e.g., "compliance is fairly high") and by using a visual plot. The final fairness value is calculated as a value between 0 (totally unfair) and 1 (maximum theoretical fairness).

Among the limitations of this work, **FAnFAIR** bases the estimation of the fairness also on the presence of outliers. However, the definition of outlier in the case of non-ordinal categorical data can be far from trivial [49]. As future development, we will investigate the extension of **FAnFAIR** to data sets composed of non-numerical values. In this preliminary experiment, outliers detection was based on z-scores, with an underlying assumption that the values in the data set are normally distributed, which is not always the case. In the future, we will implement more advanced outlier detection methods, providing support for alternative distributions. Similarly, we will develop more advanced measures, based on entropy, to assess the balance. Finally, we plan to explore if numerosity requirements can be provided starting from other (non-linear) models and their VC dimension to ensure stronger guarantees for specific hypothesis spaces. Another limitation of this work is that we used a definition of fairness from an European perspective, which may not be shared by different cultures outside the EU. However, we believe that our system can be adapted to different countries with minimum effort.

Finally, in this paper two public data sets were employed as use cases without having the exact information regarding **Compliance**. We want to stress that, in real life scenarios, when an in-house data set is employed, all the **Compliance** elements should be carefully investigated and weighted by experts, and in case of scientific research an ethical approval should be obtained before collecting and using patients' personal data.

## REFERENCES

[1] B. Friedman and H. Nissenbaum, "Bias in computer systems," *ACM Transactions on Information Systems*, vol. 14, no. 3, pp. 330-347, 1996.
[2] A. Caliskan, J. J. Bryson, and A. Narayanan, "Semantics derived automatically from language corpora contain human-like biases," *Science*, vol. 356, no. 6334, pp. 183-186, 2017.
[3] J. Buolamwini and T. Gebru, "Gender shades: Intersectional accuracy disparities in commercial gender classification," in *Conference on fairness, accountability and transparency*. PMLR, 2018, pp. 77-91.
[4] D. Wen, S. M. Khan, A. J. Xu, H. Ibrahim, L. Smith, J. Caballero, L. Zepeda, C. de Blas Perez, A. K. Denniston, X. Liu et al., "Characteristics of publicly available skin cancer image datasets: a systematic review," *The Lancet Digital Health*, vol. 4, no. 1, pp. e64-e74, 2022.
[5] D. Harwell, "The accent gap," 2018. [Online]. Available: https://www.washingtonpost.com/graphics/2018/business/alexa-does-not-understand-your-accent/
[6] A. Abid, M. Farooqi, and J. Zou, "Persistent anti-muslim bias in large language models," in *Proceedings of the 2021 AAAI/ACM Conference on AI, Ethics, and Society*, 2021, pp. 298-306.
[7] N. Mehrabi, F. Morstatter, N. Saxena, K. Lerman, and A. Galstyan, "A survey on bias and fairness in machine learning," *ACM Computing Surveys (CSUR)*, vol. 54, no. 6, pp. 1-35, 2021.
[8] T. Gebru, J. Morgenstern, B. Vecchione, J. W. Vaughan, H. Wallach, H. D. Iii, and K. Crawford, "Datasheets for datasets," *Communications of the ACM*, vol. 64, no. 12, pp. 86-92, 2021.
[9] S. Holland, A. Hosny, S. Newman, J. Joseph, and K. Chmielinski, "The dataset nutrition label: A framework to drive higher data quality standards," *arXiv preprint arXiv:1805.03677*, 2018.
[10] A. Fabris, S. Messina, G. Silvello, and G. A. Susto, "Algorithmic fairness datasets: the story so far," *Data Mining and Knowledge Discovery*, vol. 36, no. 6, pp. 2074-2152, 2022.
[11] E. M. Bender, T. Gebru, A. McMillan-Major, and S. Shmitchell, "On the dangers of stochastic parrots: Can language models be too big?" in *Proceedings of the 2021 ACM conference on fairness, accountability, and transparency*, 2021, pp. 610-623.
[12] A. Romei and S. Ruggieri, "A multidisciplinary survey on discrimination analysis," *The Knowledge Engineering Review*, vol. 29, no. 5, pp. 582-638, 2014.
[13] I. Chen, F. D. Johansson, and D. Sontag, "Why is my classifier discriminatory?" *Advances in neural information processing systems*, vol. 31, 2018.
[14] N. Li, N. Goel, and E. Ash, "Data-centric factors in algorithmic fairness," in *Proceedings of the 2022 AAAI/ACM Conference on AI, Ethics, and Society*, 2022, pp. 396-410.
[15] All European Academies, "The european code of conduct for research integrity," 2017.
[16] M. D. Wilkinson, M. Dumontier, I. J. Aalbersberg, G. Appleton, M. Axton, A. Baak, N. Blomberg, J.-W. Boiten, L. B. da Silva Santos, P. E. Bourne et al., "The FAIR guiding principles for scientific data management and stewardship," *Scientific data*, vol. 3, no. 1, pp. 1-9, 2016.
[17] A. Alowairdhi and X. Ma, "Utilizing fuzzy logic for assessing 'FAIRness' of a digital resource," in *2020 International Conference on Computational Science and Computational Intelligence*. IEEE, 2020, pp. 358-363.
[18] S. Mitchell, E. Potash, S. Barocas, A. D'Amour, and K. Lum, "Prediction-based decisions and fairness: A catalogue of choices, assumptions, and definitions," *arXiv preprint arXiv:1811.07867*, 2018.
[19] R. Berk, H. Heidari, S. Jabbari, M. Kearns, and A. Roth, "Fairness in criminal justice risk assessments: The state of the art," *Sociological Methods & Research*, vol. 50, no. 1, pp. 3-44, 2021.
[20] H. Heidari, M. Loi, K. P. Gummadi, and A. Krause, "A moral framework for understanding fair ml through economic models of equality of opportunity," in *Proceedings of the conference on fairness, accountability, and transparency*, 2019, pp. 181-190.
[21] J. Baumann, C. Hertweck, M. Loi, and C. Heitz, "Distributive justice as the foundational premise of fair ML: Unification, extension, and interpretation of group fairness metrics," *arXiv preprint arXiv:2206.02897*, 2022.
[22] J. Lamont and C. Favor, "Distributive Justice," in *The Stanford Encyclopedia of Philosophy, Winter 2017 ed.*, E. N. Zalta, Ed. Metaphysics Research Lab, Stanford University, 2017.
[23] A. Aler Tubella, D. Coelho Mollo, A. Dahlgren Lindström, H. Devinney, V. Dignum, P. Ericson, A. Jonsson, T. Kampik, T. Lenaerts, J. Alfredo Mendez et al., "Acrocpolis: A descriptive framework for making sense of fairness," *arXiv e-prints*, pp. *arXiv-2304*, 2023.
[24] A. Birhane, "Algorithmic injustice: a relational ethics approach," *Patterns*, vol. 2, no. 2, p. 100205, 2021.
[25] G. Malgieri, "The concept of fairness in the GDPR: a linguistic and contextual interpretation," in *Proceedings of the 2020 Conference on fairness, accountability, and transparency*, 2020, pp. 154-166.
[26] J. Klijnsma, "Contract law as fairness," *Ratio Juris*, vol. 28, no. 1, pp. 60-88, 2015.
[27] C. Sala, "Il principio di correttezza e buona fede nel diritto del lavoro alla luce delle sentenze più significative dell'ultimo decennio," *Diritto delle relazioni industriali: rivista della Associazione lavoro e riceche*, vol. 11, no. 2, pp. 249-260, 2001.
[28] D. Clifford and J. Ausloos, "Data Protection and the Role of Fairness," *Yearbook of European Law*, vol. 37, pp. 130-187, 08 2018. [Online]. Available: https://doi.org/10.1093/yel/yey004
[29] G. Dolso et al., *Il principio di non discriminazione nella giurisprudenza della Corte europea dei diritti dell'uomo*. JOVENE EDITORE, 2013.
[30] G. Maggiore, *L'equità e il suo valore nel diritto*. Soc. Poligrafica Italiana, 1923.
[31] M. Barcellona, “La buona fede e il controllo giudiziale del contratto,” in *Il contratto e le tutele*. Torino: Giappichelli, 2002, p. 324.
[32] B. Buruk, P. E. Ekmekci, and B. Arda, "A critical perspective on guidelines for responsible and trustworthy artificial intelligence," *Medicine, Health Care and Philosophy*, vol. 23, no. 3, pp. 387-399, 2020.
[33] T. Takagi and M. Sugeno, "Fuzzy identification of systems and its applications to modeling and control," *IEEE Transactions on Systems, Man, and Cybernetics*, no. 1, pp. 116-132, 1985.
[34] S. Spolaor, C. Fuchs, P. Cazzaniga, U. Kaymak, D. Besozzi, and M. S. Nobile, "Simpful: a user-friendly python library for fuzzy logic," *International Journal of Computational Intelligence Systems*, vol. 13, no. 1, pp. 1687-1698, 2020.
[35] A. Jobin, M. Ienca, and E. Vayena, "The global landscape of ai ethics guidelines," *Nature Machine Intelligence*, vol. 1, no. 9, pp. 389-399, 2019.
[36] N. Criado and J. M. Such, "Digital discrimination," *Algorithmic regulation*, pp. 82-97, 2019.
[37] P. Burlina, N. Joshi, W. Paul, K. D. Pacheco, and N. M. Bressler, "Addressing artificial intelligence bias in retinal diagnostics," *Translational Vision Science & Technology*, vol. 10, no. 2, pp. 13-13, 2021.
[38] T. Jang, F. Zheng, and X. Wang, "Constructing a fair classifier with generated fair data," in *Proceedings of the AAAI Conference on Artificial Intelligence*, vol. 35, no. 9, 2021, pp. 7908-7916.
[39] X. Feng and Z. Zhang, "The rank of a random matrix," *Applied mathematics and computation*, vol. 185, no. 1, pp. 689-694, 2007.
[40] S. Landmann and A. Engel, "Large systems of random linear equations with nonnegative solutions: Characterizing the solvable and the unsolvable phase," *Physical Review E*, vol. 101, no. 6, p. 062119, 2020.
[41] T. M. Mitchell et al., *Machine learning*. McGraw-hill New York, 2007, vol. 1.
[42] F. E. Harrell, "Regression modeling strategies," *Bios*, vol. 330, no. 2018, p. 14, 2017.
[43] D. Cousineau and S. Chartier, "Outliers detection and treatment: a review." *International Journal of Psychological Research*, vol. 3, no. 1, pp. 58-67, 2010.
[44] B. Freeman, N. Hammel, S. Phene, A. Huang, R. Ackermann, O. Kanzheleva, M. Hutson, C. Taggart, Q. Duong, and R. Sayres, "Iterative quality control strategies for expert medical image labeling," in *Proceedings of the AAAI Conference on Human Computation and Crowdsourcing*, vol. 9, 2021, pp. 60-71.
[45] NewsGuard, "Rating process and criteria." [Online]. Available: https://www.newsguardtech.com/ratings/rating-process-criteria/
[46] K. P. Bennett and O. L. Mangasarian, "Robust linear programming discrimination of two linearly inseparable sets," *Optimization methods and software*, vol. 1, no. 1, pp. 23-34, 1992.
[47] M. Little, P. Mcsharry, S. Roberts, D. Costello, and I. Moroz, “Exploiting nonlinear recurrence and fractal scaling properties for voice disorder detection," *BioMedical Engineering OnLine*, vol. 6, 2007.
[48] M. Little, P. McSharry, E. Hunter, J. Spielman, and L. Ramig, "Suitability of dysphonia measurements for telemonitoring of Parkinson's disease," *IEEE Transactions on Biomedical Engineering*, vol. 56, p. 1015, 2009.
[49] N. R. Suri, M. N. Murty, and G. Athithan, "An algorithm for mining outliers in categorical data through ranking," in *12th International Conference on Hybrid Intelligent Systems (HIS)*. IEEE, 2012, pp. 247-252.