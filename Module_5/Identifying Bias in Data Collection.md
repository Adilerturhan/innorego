# Identifying Bias in Data Collection: A Case Study on Drugs Distribution
Anonymous Authors

**Abstract**—A critical aspect of modern healthcare involves recognizing and addressing pharmaceutical needs. Predictive models serve as valuable decision-making tools in the healthcare sector to proactively prevent supply chain failures. However, training these models on real historical data to reliably reflect actual demand is a delicate process. An effective model, capable of reliably estimating the amount of drugs to be distributed in relation to the patient's needs, must be accurate and inherently fair. Our study endeavors to bridge legal perspectives on fairness with practical assessments of algorithmic fairness, specifically in the context of predicting drugs to be distributed in the specific area of reference. We provide an in-depth overview of the Italian National Healthcare Service, emphasizing its regulatory role in drug dispensation and its inherent challenges. Furthermore, we delve into fundamental bias research principles, encompassing legal and statistical viewpoints. In addition, we present a com-prehensive Exploratory Data Analysis using real-world data to highlight challenges encountered in the initial modeling phase. Our analysis unveils the presence of crucial missing data fields and disparities in medication utilization between genders, poten-tially indicative of social bias. These findings contribute to an in-depth understanding of patient populations concerning drug collection. Importantly, our study promotes a comprehensive approach that incorporates legal considerations and technical elements to improve the fairness and efficacy of predictive models in healthcare.

**Index Terms**—bias, algorithmic fairness, data protection, non-discrimination, statistical analysis, drug administration

## I. INTRODUCTION

Considering the rapid changes and the several challenges affecting nowadays the healthcare sector, a structured and ef-ficient management of the pharmaceutical supply chain and of the Italian drugs' distribution network is identified as a critical factor for public health protection and proper management of healthcare resources. In a socialized Healthcare Service such as the Italian National Healthcare Service (INHS), it is necessary to overcome geographical obstacles and break down social barriers to ensure equal treatment for all patients. To achieve this challenging objective, it is necessary to structure a drug distribution network in such a way that could guarantee accessibility to patients, highlighting the importance of accu-rate estimations in procurement processes [1], without forcing to bear large social costs for the purchase, collection, and distribution processes [2].

Thus, designing and managing the drug distribution network becomes a strategic activity for those who administer health-care resources and to all stakeholders in general, both at the national and regional level. The ability of a Healthcare System to guarantee accessibility to drug distribution and therapeutic continuity represents a quality indicator and a fundamental patient right. Failure to guarantee the availability of drugs for each patient, forcing them to change brands or even active ingredients, or making them wait for drug shortages, is a violation of their right to health under Article 32 of the Italian Constitution and Article 3 of the European Charter of Fundamental Rights on the protection of physical integrity [3], [4].

All those actions and interventions, capable of bringing an improvement to the supply chain and distribution network [5], could promote a more inclusive and equal model of care. In addition, disparities in health infrastructure and resources could exacerbate inequalities in access to medicines, a sit-uation highlighted during the COVID-19 pandemic [6], [7]. Furthermore, it allows for reducing the burden on hospitals, enhancing patient outcomes, and optimizing the utilization of the available resources [8].

The drugs' distribution in Italy is predominantly carried out through two different distribution models: "Direct Distribu-tion" (DD), which is centralized through hospital channels, and "Distribution Through Pharmacies on behalf of the hospital" (DTP), which directly involves the community pharmacies to enhance patient accessibility. Both models present their own distinct challenges, encompassing cost management as well as drug delivery [9].

There are many challenges that, for several years, the INHS has been facing: on the one hand, there is the continuous increase in demand for goods (including drugs) and healthcare services, while, on the other hand, there is the goal of achiev-ing economic sustainability while maintaining the level of service, that for decades has distinguished the INHS as one of the best Healthcare System in the international landscape. New approaches, including revisiting many processes and adopting new models, need to be explored to achieve this twofold purpose. Among these, one area of possible efficiency gains is the definition of a more efficient and robust drugs supply chain. With this end, the process of care reallocation could be considered, repositioning services delivery to territory, community, and primary care facilities, taking advantages and support of the new territorial structures, envisaged by the recent regulatory reform (PNRR, DM77) [10], [11].

Coordinating the pharmaceutical supply chain in a country

***

like Italy, characterized by geographical, demographic, and regulatory peculiarities, represents an activity that requires significant efforts to coordinate the multiple stakeholders involved. It is not always straightforward to determine the best distribution network for a territory that, in addition to the aforementioned peculiarities, may present additional challenges dictated by product characteristics, delivery service features, the infrastructure in place, and any regional or national regulations [12].

Furthermore, recognizing the ethical value of drugs and the need to collect and accurately register all the information also to support an informed decision-making process, reliable data collection is of utmost importance in ensuring adherence to regulations, monitoring the medication safety profile, assessing the efficacy and the effectiveness of the distribution models [13].

Critical aspects in the management of equitable drug dis-tribution planning are related to prediction and strategic pro-curement. To operate at their best, it is essential for decision-makers to have accurate and reliable data to promulgate virtuous and transparent management processes [14]. The timely and accurate dissemination of information is crucial in promptly addressing emerging healthcare requirements, optimizing resource allocation, and minimizing inefficiencies [15].

However, historical data not only record trends in healthcare disparities but also run the risk of perpetuating these biases when machine-learning models are trained on them [3], with several consequences on the patient care pathway and the final clinical outcomes. For this reason, a structured administration of the Italian drug distribution network is crucial not only for patient well-being but also for the healthcare system's economic sustainability and future resilience [16].

Any reforms [3], [4], such as those regulating competencies between state and regions [17], as described in Figure 1, have caused fragmentation of accessibility to health care, in turn creating significant inequalities [18], and have also increased the financial costs of fulfilling the tasks of the welfare state [19], [20].

Our research consists of two macro-areas of activities: a theoretical contribution that provides a full overview of the regulatory framework as well as studies on biases in drugs distribution and pharmaceutical fields, and a practical contribu-tion, analyzing real-world drugs' distribution data in a specific Italian context [21]. At the beginning of the study, the context of the INHS distribution network is presented, and the basic concepts necessary for bias research are introduced. Following that, an Exploratory Data Analysis of actual drugs' distribution data from the Italian setting is performed. At the end of this study, some insights and potential future developments are provided based on the situation described, so as to identify and solve those existing deficiencies in the availability of data related to the management of the pharmaceutical distribution network in the Italian healthcare service. Finally, a focus is placed on predictive tools application to support the planning and control of the drug distribution process.

## II. THEORETICAL FRAMEWORK

### A. The Italian National Healthcare Service and Access to Drugs Services

In Italy, the Republican Constitution protects the right to health in Article 32. It is one of the most characteristic points of the principles of the welfare state based on equality and the full realization of the person, the goal of the Republic that arose after the end of World War II, and the unraveling of the previously constituted order [22].

The pharmaceutical sector constitutes one of the areas in which the tension between the “financially contingent” nature of the right to health and the need to protect its fundamental core has manifested itself most dramatically [23]. Among the many factors in the increase in pharmaceutical spending [23], [24] is the aging of the population, which is followed by an increase in chronic and degenerative diseases [25] or the trend toward the medicalization of every phase of life, even in the presence of minor diseases [26].

In this perspective, pharmaceutical distribution embedded in a welfare system is complex. It involves many players: univer-sities (for scientific research), manufacturers (pharmaceutical companies), distributors (logistics operators, intermediaries, wholesalers, hospitals, and pharmacies), regulators (legislators, health agencies, legal professionals), and patients who are the final customers in the chain [27], [28].

It is a task complicated by the specifics of the drugs that are to be distributed, which may require specific treatments for their preservation, in order to guarantee the usability of the product; otherwise, the whole process results in a negative externality and financial inefficiencies. Among these externalities, possibly direct or indirect discrimination in phar-maceutical distribution is a particularly sensitive issue because it would deny access to the pharmaceutical product to those who would be entitled to it.

The pharmaceutical sector is not exempt from discrimina-tory bias. Among the most notorious cases, there is the un-derrepresentation of specific social categories, such as women [29]-[32] and infants [33]-[35]. It means that each of these categories has resorted to drugs that have often been tested on a predominantly male population and an adult age group.

There is another element related to bias that can have discriminatory effects, such as access to technical knowl-edge. Especially after the COVID-19 pandemic, anti-scientific theories have permeated public opinion. Consequently, such bias may affect those who refuse pharmaceutical treatment administration, to the disadvantage of the INHS. This can lead to dealing with diseases that are caused or aggravated by patients' refusal to undergo treatments administered by the official healthcare system [36].

The issue described should not be confused with the expres-sion of self-determination in the refusal of treatment expressed through informed medical consent. In the former case, we are dealing with people who refuse to receive treatments and medication based on their erroneous beliefs or false information found online. In the latter case, the refusal of

***

## Italian National Healthcare Service Relevant Reforms

| 1948 | 1978 | 1992 | 1999 | 2001 | 2011 | 2024 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Italian Constitution: Article No.3: Principle of equality Article No. 32: Right to health | Law No. 833/1978 established the National Health Service (hereafter NHS), which follows the universal health care model | D. Lgs 502/1992: The LEAs (Essential Levels of Care) are established. | D. Lgs: 229/1999: Private companies could replace public health care providers in the delivery of health care services (principle of subsidiarity) | Reform of Article No. 117 of the Constitution: a new partition of competencies between the State and the regions in health care and welfare state | Decree No. 68/2011 regarding financial autonomy among the regions, as well as determining standard costs and requirements in the health sector | A new bill ("A.S.615") aims to strengthen private and regional intervention in public health care. In this way, the "universal" model of public health care would become a residual option. |

**Fig. 1. Reforms of the Italian National Healthcare Service**

treatment is expressed after a healthcare staff member has explained the consequences of refusal, and the patient, who is properly aware of the risks, expresses a valid consent [37].

### B. Discrimination and Data Protection

With the implementation of increasingly refined models, health data processing is becoming more complex as the traditional division between personal data and non-personal data is blurring [38].

Clear evidence emerges precisely in the area of health data protection, especially about the use of IoT apps in health care [39]–[42], since they enable the collection of personal data related to a person's health status, adjusting, for example, their drug therapy according to changes in their health condition. However, these devices are very often invasive with respect to users' privacy and used in a field sensitive to discrimination, thus requiring specific regulation [43].

In any case, such data should be collected and stored following the principles established by Article 5 GDPR, i.e., minimization of data collection concerning its use, accuracy, limitation of storage, integrity, and confidentiality in process-ing. However, these principles may need to be considered by overcoming the traditional bipartition between personal and non-personal data [38], [44], [45].

Health data is subject to several measures to avoid bias and consequent discrimination in the provision of a service, such as administration of drugs, that are essential to ensure health rights protection. It is a good of primary importance both in light of Article 32 of the Italian Constitution, which qualifies it as a fundamental right, and in light of Article 35 of the Charter of Fundamental Rights of the European Union, which guarantees "a high level of protection of human health".

On this issue, EU Regulation 679/2016 provides specific definitions of what is to be understood as "data concerning health." Indeed, Article No. 4(15) states that it "means personal data related to the physical or mental health of a natural person, including the provision of health care services, which reveal information about his or her health status." In contrast, Article No. 9 of GDPR is precisely about the safeguards given to the owner of personal data that may cause discriminatory situations [46], [47].

However, EU Regulation 679/2016 provides specific defini-tions of what is to be understood as “data concerning health.” Indeed, Article No. 4(15) states that it “means personal data related to the physical or mental health of a natural person, including the provision of health care services, which reveal information about his or her health status." In contrast, Article No. 9 of GDPR is precisely about the safeguards given to the owner of personal data that may cause discriminatory effects [48], [49].

Regarding anti-discrimination law, a distinction must first be made between direct and indirect discrimination. This approach is typically European, in particular from the Court of Justice of the European Union (most recently, Court of Justice of the European Union, 13/7/2023, C-765/21), and was elab-orated in case law before it was implemented into legislation, by Directive No. 2000/78/EC, 27/11/2000, which defines the concepts of direct discrimination and indirect discrimination. "Direct discrimination occurs when, because of religion, be-lief, disability, age, or sexual orientation, a person is treated less favorably than another is, has been, or would be treated in a similar situation. Whereas indirect discrimination occurs when a neutral provision, criterion, practice, act, covenant, or conduct may place persons professing a particular religion or ideology of another nature, persons with disabilities, or persons of a specific age or sexual orientation at a particular disadvantage compared to other persons” (Supreme Court of Cassation May 26, 2004 No. 10179, in Lav. e Prev. Oggi, 2004, 1839).

In the non-EU context, such as in the United States, no such distinction is known, amounting to a lack of recognition of indirect discrimination. Indeed, the decision maker focuses solely on the intent to discriminate, disregarding the actual dis-criminatory impact, since "disparate treatment" (comparable

***

to direct discrimination) is prohibited, but "disparate impact" (comparable to indirect discrimination) is not (*Washington v. Davis*, 426 U. S. 229, 242 (1976)) [50].

### C. Algorithmic Fairness in Medical Applications

The popularity of machine learning and AI applications has made fairness a much more relevant concern over the last years. Several definitions of fairness have been proposed, both in the legal field [51]–[53], and in the mathematical domain [54], [55], where different formulas are used to formalize philosophical problems.

In a broader perspective, fairness can be defined as “the absence of any prejudice or favoritism towards an individual or a group based on their inherent or acquired characteristics" [55]. Potential sources of unfairness in machine learning outcomes manifest in: bias in the data upon which models are trained, bias in the algorithms, and human bias, rising from the intricate interplay between humans and the design and utilization of algorithms [56], [57].

Identifying and mitigating bias is thus a crucial theme when addressing algorithmic fairness [58]. We distinguish between statistical bias – the systematic error introduced in the collec-tion (selection bias, sampling bias, non-response bias), which leads the observed sample not to reflect the distribution of the true population – and social bias – pertaining to situations in which unequal outcomes or unequal model performance or unfair allocation of resources are observed for different groups of the population, based on various factors such as race, gender, ethnicity, socioeconomic status, or other identity markers [59]. These two types of bias are interconnected, as social bias can manifest in data collection processes, leading to statistical bias in modeling and analysis. Moreover, statistical models and algorithms can reflect and perpetuate social bias, contributing to unequal outcomes that reinforce existing social inequalities [60].

When it comes to the healthcare sector, the issues of fair-ness and bias become critical as underrepresented populations tend to be affected by bias more severely, with algorithmic predictions either being less accurate or underestimating the necessity for care [61]. Indeed, failing to account for the difference in disease prevalence or incidence among different populations could generate sub-optimal results, potentially harming underrepresented groups. Social bias is prevalent in the healthcare environment, shaping the dynamics within the workplace and the effectiveness of the care provided [62].

Literature reports evidence of social bias, including health-care disparities among genders and races in terms of treatment and testing recommendations [63]–[65], differences in drug prescription or utilization patterns [66]–[69], and health data poverty in the context of clinical trials and pre-clinical stages [70]. Healthcare disparities reflected in the data contribute to the creation of a "digital divide", resulting in a scenario in which digital advances are not enough to guarantee an improvement in healthcare outcomes [71].

A careful analysis of medical data is thus a first step towards awareness about social biases and a fairer care, more capable of meeting the needs of all patients. Current approaches to mit-igate bias include preprocessing strategies, fair representation techniques, model selection methods that prioritize fairness, and post-processing adjustments to the model outcomes aimed at making them more impartial [72]–[74].

Focusing on preprocessing strategies, the path to fairness starts with the evaluation of fairness in datasets [75], meaning the identification of any possible sampling bias, measurement bias, and social bias. This can be achieved through specific additional data curation or data standardization steps that promote transparency of the selected data [76]–[78]. Once a bias is identified, several de-biasing techniques can be applied, including re-sampling and re-weighting [73].

The empirical part of this work focuses on the bias iden-tification phase, with the goal of revealing hidden biases and gaps present in our real pharmaceutical data. Addressing these issues is crucial for ensuring the reliability of any prospective predictive model for pharmaceutical needs and for creating models that conform to the AI Act.

## III. MATERIALS AND METHODS

### A. The Data

**TABLE I**
**DESCRIPTION OF VARIABLES IN THE FINAL DATASET**

| Name | Description |
| :--- | :--- |
| DS | Original Data Source (either 1 or 2) |
| Date | Date in which the drug was dispensed |
| Pharma\_PresErog | The drug supplier (either a hospital pharmacy or a territorial pharmacy), encoded |
| Pharmacy\_Location | A generic identifier of the location of the supplier (either province or municipality code) |
| Pharmacy\_Municipality | The municipality of the supplier, when available |
| Codice\_Fiscale | The unique identifier of the patient, encoded from the fiscal code |
| ID | The prescription ID |
| Gender | Gender of the patient, binary |
| Age | Numeric value for the age of the patient at the moment of the dispensation |
| Region\_Res | The residence region of the patient |
| Province\_Res | The residence province of the patient |
| Comune\_Res | The residence municipality of the patient |
| ASL | The Local Health Unit Authority to which the patient is registered |
| Flag\_Exemption | Binary variable identifying the presence of an exemption to payment of a drug (1 if the patient is exempt to pay) |
| ATC | Drug code, according to the ATC (Anatomical Therapeutic Chemical) clas-sification system |
| AIC | Drug code, according to the AIC (Autor-izzazione all’Immissione in Commercio) classification system |
| UoM | Unit of measure of the drug (e.g. pieces, packs) |
| Price | Price paid by the patient |
| Quantity | Quantity dispensed |

The database at the core of our research comprises pharma-ceutical data representing all the drugs therapies distributed in the three-year period from 2018 to 2020 by pharmacies in some Northern Italian provinces. The data have been pseudonymized in order to ensure compliance with data pro-tection regulations. Hence, it is impossible to trace patients' identities from the data, but the available variables allow us to stratify the population according to their different charac-teristics.

The original database consists of two different datasets. In particular, patients suffering from chronic pathologies requir-ing home treatment under a hospital specialist prescription are registered in the first dataset, made of 700,621 rows and 26 columns, while another dataset, made of 34,883,706 rows and 23 columns includes information about drugs dispensed by the community pharmacies without a specialist prescription to all groups of patients.

Both datasets contain information about the drug being dispensed, identified by its ATC and AIC codes [79], [80], and about the dispenser, either a community pharmacy or an hospital pharmacy. Moreover, they contain information about the patient collecting the drug, such as gender, age and region of residence. A unique identifier for each patient, encoded from their fiscal code for privacy reasons, allows us to track the drug collection history of single individuals over time. Hence, combining the two original datasets makes it possible to identify all the dispensations to patients affected by chronic diseases to stratify the population more deeply.

Since the key variables recorded in the two dataset were different, we performed several feature engineering steps in order to remove empty fields and standardize the names and codification to create a unique dataset of comparable streams of data. The resulting variables are summarized in III-A.

### B. Analytical Methodology

We conducted an **Exploratory Data Analysis (EDA)** [81] aimed at unveiling hidden patterns of biases and missing data which can be attributable to the data collection phase or to possible category-related drug prescription patterns.

We first identified outliers in the **Date** field and inconsistent data in the **Age** field, which we remove, as they could com-promise the trustworthiness of the dataset: in particular, we dropped rows corresponding to dispensations performed before 2018, because they were too few in number with respect to the following years, and rows corresponding to patients whose age recorded was higher than 116 years old - the age of the oldest living person in Italy in the reference period [82] - which together amounted to the 0.04% of the overall size. We believe inconsistent values in the **Age** field are attributable to human error, either in the manual collection or in the several transfers that the data has undergone before our analysis. The final dataset we considered for the analysis was made of 35,569,278 rows and 19 columns.

Then, we analyzed characteristics of the study population and inspected the drug use patterns using descriptive statistics and statistical tests. Baseline statistics of the study sample are reported in table II. We used Chi-Squared test for propor-tions to compare the proportion of counts in each category of categorical variables (e.g. **Gender**), and the Kolmogorov-Smirnov (KS) test to compare the distribution of numerical variables across different categories of individuals (e.g. **Age** by **Gender**). In statistical tests, a p-value of < 0.05 denoted statistically significant differences. Moreover, we completed the analysis with a visual representation of patterns and distributions through Bar Plots, Violin Plots, Pie Charts and Q-Q Plots.

Data management and analysis have been performed using **Python** (3.9.12 version). All plots have been produced using **matplotlib** and **seaborn** libraries of the Python language.

## IV. DISCUSSION

This study provides crucial insights that contribute to the ongoing dialogue about algorithmic fairness. In cases such as drug administration, where data-driven decisions would impact directly individuals' right to health, it is crucial to adopt a transparent way of verifying the data base, i.e., through the traceability of the information and data with which the model is fed by the human hand, meaning by its programmer, who decides and thus chooses which data to allow it to access.

In our specific case, most of the missing values are found in the variables which represent geographical information, either about the pharmacy or about the residence of the patient, as

***

**TABLE II**
**CHARACTERISTICS OF THE PATIENTS SAMPLE**

| Gender | Chronic | F | M |
| :--- | :--- | :--- | :--- |
| | | No | Yes (6.82%) | No | Yes (9.33%) |
| Average age | 68.04 | 70.17 | 65.87 | 69.70 |
| % of patients with a payment exemption | 3.34% | 2.21% | 3.22% | 2.21% |
| Average # sales / patient | 24.64 | 87.99 | 23.87 | 90.02 |
| Average # differ-ent ATC / patient | 5.15 | 13.14 | 4.60 | 12.69 |
| Average # differ-ent AIC / patient | 6.84 | 18.88 | 6.22 | 18.50 |

[IMAGE: Bar chart illustrating the percentage of missing values for each field. **Pharma\_PresErog** has 0.0% missing values. **Pharmacy\_Location** has 57.36% missing values. **Pharmacy\_Municipality** has 65.28% missing values. **Codice\_Fiscale** has 0.56% missing values. **Gender** has 1.29% missing values. **Age** has 2.71% missing values. **Region\_Res** has 98.0% missing values. **Province\_Res** has 98.03% missing values. **Comune\_Res** has 98.0% missing values. **ASL** has 1.53% missing values. **Flag\_Exemption, ATC, AIC, UoM, Price, Quantity** all have 0.0% missing values.]

**Fig. 2. Percentage of missing values for each field.**

[IMAGE: Pie chart illustrating the number of dispensations and of unique patients by Gender. **F** (Female) dispenses account for 52.9%, **M** (Male) for 45.8%, **nan** (Not a number/missing) for 1.3%. For unique patients, **F** accounts for 51.8%, **M** for 45.3%, and **nan** for 2.8%.]

**Fig. 3. Pie chart illustrating the number of dispensations and of unique patients by Gender.**

shown in figure 2. The incompleteness of these fields consti-tutes an issue for two distinct reasons: it makes any analysis of these fields unreliable and it makes it impossible to verify that geographical communities are not underrepresented. A small percentage of missing values is present in **Codice\_Fiscale** and **ID** as well, but this is attributable to the possibility for patients in Italy to purchase some of the drugs without showing an identification document. However, these missing values make it impossible to identify which and how many patients carry out the respective collections.

Our dataset demonstrates balance in both the number of dispensations and the count of unique patients across the two genders, as confirmed by the Chi-Squared test for proportions, which is clear in figure 3. Hence, we did not find any representation bias related to gender.

A comprehensive examination of the distribution of patients' ages based on gender unveiled a significant difference in the age distribution across genders. We investigate even further this distribution across therapeutic groups (ATC I - anatomical main group) through QQ Plots and KS test, as shown in figure 4. In this case the KS test is not informative, being it very sensitive to sample size. However, a visual analysis reveals a difference in age distribution by gender for some therapeutic groups. In particular, while for adult to senile ages the drug consumption for most therapeutic groups looks similar for men and women, data show that teenage boys use medications belonging to therapeutic groups H, P, R more frequently than their female counterpart, which confirms evidences from the literature [66]. Instead, women across all age groups exhibit a higher likelihood of utilizing medications classified under Group G, encompassing gynecological and sex hormone-related drugs.

Furthermore, a notable disparity emerges in the age dis-tributions between patients utilizing medication for chronic conditions and those that we classify as non-chronic patients, as shown in figure 5. Specifically, the age distribution among chronic patients exhibits a pronounced leftward skewness, suggesting that individuals with chronic health issues in the considered region tend to be older compared to their non-chronic counterparts [66].

Examining the overall sales data categorized by **Gender** (figure 6), it becomes evident that women consistently demon-strate a higher utilization of medications classified under the

[IMAGE: QQ Plot illustrating the distribution of Age across therapeutic groups (ATC I) stratified by Gender. The red line represents 100 percentiles of Age for female individuals plotted against themselves, serving as a reference line. The blue scatter plot compares 100 percentiles of the age distribution for females (x-axis) with those of males (y-axis), providing insights into potential gender-based differences within each therapeutic group. Therapeutic groups shown are A: Alimentary tract, B: Blood organs, M: Musculo-skeletal, J: Antiinfectives, N: Nervous, P: Antiparasitic, C: Cardiovascular, R: Respiratory, H: Systemic hormons, G: Genito-urinary, D: Dermatologicals, S: Sensory organs, L: Antineoplastic, V: Various. All therapeutic groups show p-value: 0.0, except D: Dermatologicals (p-value: 0.0002).]

**Fig. 4. QQ Plot illustrating the distribution of Age across therapeutic groups (ATC I) stratified by Gender. The red line represents 100 percentiles of Age for female individuals plotted against themselves, serving as a reference line. The blue scatter plot compares 100 percentiles of the age distribution for females (x-axis) with those of males (y-axis), providing insights into potential gender-based differences within each therapeutic group.**

Alimentary Tract and Metabolism (A) group and Nervous System (N) group compared to men who are more frequent users of drugs from the Cardiovascular System (C) group, which is in line with recent studies [68] (figure 7).

Concurrently, a positive correlation is observed between chronic conditions and a more frequent use of medications targeting cardiovascular issues. Notably, the consumption of medications for the Cardiovascular System has exhibited a steady increase over the study period, aligning with recent findings in other European countries [83].

Given these results, it becomes crucial to consult medical experts to determine whether these discrepancies stem from physiological variations between individuals of the two gen-ders or are influenced by the gender biases already known in the literature.

***

[IMAGE: Violin plots representing the distribution of patient's age stratified by Gender above and membership to the group of chronic patients below.
**Top plot (Gender):** Age distribution for females (F, n = 726,464) and males (M, n = 635,619). Both distributions are skewed towards older ages.
**Bottom plot (Chronic Patient):** Age distribution for non-chronic patients (False, n = 1,368,307) and chronic patients (True, n = 31,692). The distribution for chronic patients is more heavily skewed to the left (older ages).]

**Fig. 5. Violin plots representing the distribution of patient's age stratified by Gender above and membership to the group of chronic patients below.**

[IMAGE: Horizontal bar plot, illustrating the percentage of dispensations in the three-year period for drugs of each therapeutic group (ATC I), stratified by patients' gender (F and M).]

**Fig. 6. Horizontal bar plot, illustrating the percentage of dispensations in the three-year period for drugs of each therapeutic group (ATC I), stratified by patients' gender.**

[IMAGE: Horizontal bar plot, representing the percentage mix of drugs across the three-year period in the chronic and non-chronic patients group.]

**Fig. 7. Horizontal bar plot, representing the percentage mix of drugs across the three-year period in the chronic and non-chronic patients group.**

The successful detection of potential biases in our data proves the importance of performing an exploratory data analysis before moving to the modeling phase. Such kind of analysis becomes even more effective in preventing the perpetuation of social biases within machine learning models when using complex black-box predictive models, where the opacity makes the task of detecting biases and unfairness more complicated [84]. Hence, conducting an EDA, allows us to strenghten any future predictive model's ethical foundations, contributing to the broader goal of trustworthy and equitable artificial intelligence.

Our analysis is part of an anticipatory regulation approach [85]–[87], since we incorporated our analysis in the context of the "Data Governance" framework created by the AI Act [88]. This new legislation, the world's first statutory regulation on AI, provides for a set of complex requirements related to training, validation, and testing.

According to this regulation, "High-risk" AI models, such as medical device software, that are trained with health data must be developed according to training, validation and testing criteria detailed in Article 10, par. 2-5. In particular: "Training, validation, and testing data sets shall be relevant, represen-tative, and to the best extent possible, free of errors and complete. They shall have the appropriate statistical properties, including, where applicable, as regards the persons or groups of persons on which the high-risk AI system is intended to be used. These characteristics of the data sets may be met at the level of individual data sets or a combination thereof. Training, validation and testing data sets shall take into account, to the extent required by the intended purpose, the characteristics or elements that are particular to the specific geographical, behavioural or functional setting within which the high-risk AI system is intended to be used".

Anticipatory regulation, in this context, represents a strategy that proactively addresses potential issues and challenges in the application of the AI Act during the development of AI models.

The outcomes of the study could be used by policymakers to assess how well the AI Act's provisions for recognizing and reducing biases are being used in real-world situations. This may help policymakers identify areas in the regulatory system that require further effort or improvement.

## V. CONCLUSIONS

Our investigation highlights the significance of detecting and mitigating biases in pharmaceutical data in view of applying the AI Act's provisions. The theoretical insights we provided include a brief overview of regulations and bias-related research in the context of pharmaceutical data and the importance of applying ethical and legal principles at each step of the processing.

In this context, legal fragmentation is a factor of discrimina-tion since it has a clear and decisive impact on the organization of the healthcare system regarding pharmaceutical distribution. It differs according to regional (and, therefore, local) regu-lations [89], violating the Italian Constitution under Article

***

32 (right to health) and, in particular, Article 3 (principle of equality). In the latter case, it becomes even more evident that the Republic seems to be failing its mandatory obligation "to remove those obstacles of an economic or social nature which constrain the freedom and equality of citizens”.

As for practical insights, our analysis of regional phar-maceutical data not only provides evidence of social bias e.g. potential healthcare disparities, but also advocates for an interdisciplinary approach, combining legal requirements and technical best practices. We identified a presence of high percentages of missing data in some key fields, constituting a lack of transparency that undermines the ability to verify the completeness and balance of data under all dimensions. Nevertheless, in the available data we were able to detect dis-parities in the utilization of specific categories of medications between men and women.

It has to be highlighted that our dataset, however, does not depict prescription patterns or consumption habits but rather offers a snapshot of the patient populations collecting medi-cations from pharmacies. Consequently, wrongly interpreting the nature of the collected data may lead to potentially biased conclusions and decisions.

Despite this limitation, our findings provide insights into the analysis of demographic characteristics of individuals access-ing prescribed medications in a view of mitigating biases. Our analysis also contributes to understanding patient populations in the context of drug collection practices in Italy, which could be useful to public entities dealing with drug procurement.

Further research should investigate effective strategies to mitigate the bias in pharmaceutical data, with a specific focus on the disparities in drug delivery throughout the different Italian regions.

In the context of anticipatory regulation, several projects related to the practical implementation of the AI Act high-risk requirements have been conducted in the last years [90]. Future research should follow this direction to understand what are the shortcomings of the new regulation and what strategies are needed to ensure effective implementation of the legal requirements. In particular, the intersections between GDPR and the AI Act should be further explored, as the new proposal provides for a novel, ad hoc legal basis for processing special categories of data (such as health data) for bias mitigation. This visionary provision will be very useful in building trustworthy AI systems; however, it could also raise some privacy concerns that need to be further examined.

## REFERENCES

[1] F. Bartolini, G. Papini, and C. Sara, "Il processo degli acquisti. parte 3," *Boll SIFO; 66(3):165-170*. Accessed on 05/01/2024. [Online]. Available: https://www.bollettinosifo.it/archivio/3396/articoli/33787/, 2020.
[2] A. Compagni, L. Cavalli, and C. Jommi, "Pharmaceutical companies and italian regional governments: Managing relationships in an increasing institutional complexity," *Health policy*, vol. 87, no. 3, pp. 333-341, 2008.
[3] G. Vicarelli, "The creation of the national health system in italy (1961-1978)," *Dynamis*, vol. 39, no. 1, pp. 21-43, 2019.
[4] M. Podetta et al., "Il tentativo di attuazione dell'autonomia differenziata: dal disegno di legge calderoli alla legge di bilancio per il 2023," *CONSULTA ONLINE*, no. 2, pp. 353-366, 2023.
[5] F. Bertolotti and R. Occa, ""roads? where we're going we don't need roads." using agent-based modeling to analyze the economic impact of hyperloop introduction on a supply chain," in *Multi-Agent Systems and Agreement Technologies: 17th European Conference, EUMAS 2020, and 7th International Conference, AT 2020, Thessaloniki, Greece, September 14-15, 2020, Revised Selected Papers 17*. Springer, 2020, pp. 493-500.
[6] M. Noera and M. Onado, "Una crisi annunciata: analisi economica della sanità italiana dopo la pandemia," *Mercato Concorrenza Regole*, vol. 34, no. 2, pp. 291-322, 2022.
[7] C. F. Giulio, "La riforma dell'assistenza sanitaria e socio-sanitaria territoriale e le problematiche connesse alla sua attuazione," *Federalismi*, 2022.
[8] A. Oliver and E. Mossialos, "Equity of access to health care: outlining the foundations for action," *Journal of epidemiology and community health*, vol. 58, no. 8, p. 655, 2004.
[9] M. P. Fanti, A. M. Mangini, M. Roccotelli, and B. Silvestri, "Drugs cross-distribution management in urban areas through an incentives scheme," *IFAC-PapersOnLine*, vol. 53, no. 2, pp. 17053-17058, 2020, 21st IFAC World Congress.
[10] A. Compagni, F. Tediosi, V. D. Tozzi et al., "L'integrazione tra ospedale e territorio nelle aziende sanitarie," in *Rapporto OASI 2010*. Egea, 2010, pp. 519-538.
[11] A. Creazza, U. Restelli, E. Porazzi, E. R. Garagiola, D. Croce, M. Arpesella, F. Dallari, and C. Noè, "Benchmarking of health technologies dis-tribution models: an investigation of lombardy's local health authorities," *Benchmarking: An International Journal*, vol. 23, no. 4, pp. 817-842, 2016.
[12] M. Baglio, E. Garagiola, and F. Dallari, "Outsourcing strategies and distribution models in italian pharma supply chain," in *2017 IEEE International Conference on Service Operations and Logistics, and Informatics (SOLI)*. IEEE, 2017, pp. 175-180.
[13] S. Khoukhi, C. Bojji, and Y. Bensouda, "A review of medical distribution logistics in pharmaceutical supply chain," *International Journal of Logistics Systems and Management*, vol. 34, no. 3, pp. 297-326, 2019.
[14] F. Bertolotti and S. Roman, "The evolution of risk sensitivity in a sustainability game: an agent-based model," 2022.
[15] G. Dobson, D. Tilson, V. Tilson, and C. E. Haas, "Quantitative case study: Use of pharmacy patient information systems to improve oper-ational efficiency," in *2014 47th Hawaii International Conference on System Sciences*. IEEE, 2014, pp. 4220-4228.
[16] S. Roman and F. Bertolotti, "Global history, the emergence of chaos and inducing sustainability in networks of socio-ecological systems," *Plos one*, vol. 18, no. 11, p. e0293391, 2023.
[17] L. Chieffi et al., "La tutela del diritto alla salute tra prospettive di regionalismo differenziato e persistenti divari territoriali," *Nomos. Le attualità del diritto*, no. 1, p. 7, 2020.
[18] A. Pioggia, "La sanità nel piano nazionale di ripresa e resilienza," 2022.
[19] G. Rulli, "L'istituzione del servizio sanitario nazionale e la sua eredità," *PROBLEMI ORGANIZZATIVI E PROSPETTIVE DEL SISTEMA SANITARIO IN ITALIA*, p. 11, 2023.
[20] M. Sala et al., "L'assistenza farmaceutica fra tutela della salute, evoluzione delle politiche di controllo della spesa farmaceutica e prospettive future," 2023.
[21] R. Pinna, P. P. Carrus, F. Marras et al., “Emerging trends in health-care supply chain management an italian experience," *Applications of contemporary management approaches in supply chains*, pp. 117-137, 2015.
[22] L. Busatta, "Potenzialità e aspetti critici del nuovo volto della sanità territoriale, tra esigenze di uniformità e difficoltà attuative," *Federalismi*, 2023.
[23] V. Molaschi, "Crescita della spesa sanitaria e livelli massimi di prestazione assistenziale farmaceutica." *Foro Amm.*, pp. 618-625, 2002.
[24] F. Bocchini, "La sanità lesiva: ideologie e strategie a confronto,” *Contratto e impresa*, vol. 34, no. 4, pp. 1284-1322, 2018.
[25] B. G. Tedeschi, "L'invecchiamento della popolazione e il ruolo del diritto," *Quaderni di diritto e politica ecclesiastica*, vol. 26, no. Speciale, pp. 3-18, 2023.
[26] F. Marin, "Vulnerabilità, salute e medicalizzazione della vita," *Teoria. Rivista di filosofia*, vol. 43, no. 1, pp. 127-144, 2023.
[27] M. Jaberidoost, S. Nikfar, A. Abdollahiasl, and R. Dinarvand, "Phar-maceutical supply chain risks: a systematic review," *DARU Journal of Pharmaceutical Sciences*, vol. 21, pp. 1-7, 2013.
[28] E. Vann Yaroson, L. Breen, J. Hou, and J. Sowter, "The role of power-based behaviours on pharmaceutical supply chain resilience," *Supply

***

Chain Management: An International Journal*, vol. 28, no. 4, pp. 738-759, 2023.
[29] J. Plevkova, M. Brozmanova, J. Harsanyiova, M. Sterusky, J. Honetschlager, and T. Buday, "Various aspects of sex and gender bias in biomedical research," *Physiological research*, vol. 69, no. Suppl 3, p. S367, 2020.
[30] D. Westergaard, P. Moseley, F. K. H. Sørup, P. Baldi, and S. Brunak, "Population-wide analysis of differences in disease progression patterns in men and women," *Nature communications*, vol. 10, no. 1, p. 666, 2019.
[31] A. M. Whelan, "Unequal representation: Women in clinical research," *Cornell L. Rev. Online*, vol. 106, p. 87, 2020.
[32] M.-T. Ruiz-Cantero, M. Blasco-Blasco, E. Chilet-Rosell, and A.-M. Peiró, "Gender bias in therapeutic effort: from research to health care," *Farmacia Hospitalaria*, vol. 44, no. 3, pp. 109-113, 2020.
[33] M. M. Laughon, D. K. Benjamin, E. V. Capparelli, G. L. Kearns, K. Berezny, I. M. Paul, K. Wade, J. Barrett, P. B. Smith, and M. Cohen-Wolkowiez, "Innovative clinical trial design for pediatric therapeutics," *Expert review of clinical pharmacology*, vol. 4, no. 5, pp. 643-652, 2011.
[34] M. M. Laughon, D. Avant, N. Tripathi, C. P. Hornik, M. Cohen-Wolkowiez, R. H. Clark, P. B. Smith, and W. Rodriguez, "Drug labeling and exposure in neonates," *JAMA pediatrics*, vol. 168, no. 2, pp. 130-136, 2014.
[35] E. Falletti, "Multidisciplinary issues on scientific research and medical treatment on infants in comparative law," *Ius comparatum*, vol. 2, pp. 28-70, 2022.
[36] C. Gerardi and S. Garattini, "Pregiudizi a-scientifici e spesa farmaceu-tica," *Ithaca: Viaggio nella Scienza*, vol. 2017, no. 9, pp. 77-82, 2017.
[37] E. Daly et al., "Trattamento sanitario obbligatorio e somministrazione coattiva di farmaci, con particolare riferimento ai lai [compulsory health treatment and forced administration of drugs, with particular reference to lai]," *NOTIZIE DI POLITEIA*, vol. 37, no. 141, pp. 97-111, 2021.
[38] L. Ruggeri et al., "La dicotomia dati personali e dati non personali: il problema della tutela della persona nei c. dd. dati misti," *DIRITTO DI FAMIGLIA E DELLE PERSONE*, no. 2, pp. 808-832, 2023.
[39] L. Carmi, M. Zohar, and G. M. Riva, "The european general data protection regulation (gdpr) in mhealth: Theoretical and practical aspects for practitioners' use," *Medicine, Science and the Law*, vol. 63, no. 1, pp. 61-68, 2023.
[40] C. G. Nobile, "Legal aspects of the use artificial intelligence in telemedicine," *Journal of Digital Technologies and Law*, vol. 1, no. 2, pp. 314-336, 2023.
[41] C. Gallese, "Legal issues of the use of chatbot apps for mental health support," in *20th International Conference on Practical Applications of Agents and Multi-Agent Systems, PAAMS 2022*. Springer, 2022, pp. 258-267.
[42] E. Falletti, "Privacy protection, big data gathering and public health issues: Covid-19 tracking app use in italy," *Big Data Gathering and Public Health Issues: COVID-19 Tracking App Use in Italy (January 2, 2021)*, 2021.
[43] C. G. Nobile, "Regulating smart robots and artificial intelligence in the european union," *Journal of Digital Technologies and Law*, vol. 1, no. 1, pp. 33-61, 2023.
[44] I. Graef, R. Gellert, and M. Husovec, "Towards a holistic regulatory approach for the european data economy: Why the illusive notion of non-personal data is counterproductive to data innovation," 2018.
[45] E. Falletti, "Tutela europea della privacy e dei dati personali," in *Le scommesse dell'Europa: diritti, istituzioni, politiche*. Ediesse, 2009.
[46] J. W. de Kok, M. Á. A. de la Hoz, Y. de Jong, V. Brokke, P. W. Elbers, P. Thoral, A. Castillejo, T. Trenor, J. M. Castellano, A. E. Bronchalo et al., "A guide to sharing open healthcare data under the general data protection regulation," *Scientific data*, vol. 10, no. 1, p. 404, 2023.
[47] G. R. Ferrè, "Data donation and data altruism to face algorithmic bias for an inclusive digital healthcare," *BioLaw Journal-Rivista di BioDiritto*, no. 1, pp. 115–129, 2023.
[48] G. Bincoletto, "Scientific research processing health data in the european union: data protection regime vs. open data," *J. Open Access L.*, vol. 11, p. 1, 2023.
[49] G. Lofaro, "Dati sanitari e e-health europea: tra trattamento dei dati personali e decisione amministrativa algoritmica," *Medialaws*, 2022.
[50] V. Foggo, J. Villasenor, and P. Garg, "Algorithms and fairness," *Ohio St. Tech. LJ*, vol. 17, p. 123, 2021.
[51] J. Klijnsma, "Contract law as fairness," *Ratio Juris*, vol. 28, no. 1, p. 68-88, Feb. 2015. [Online]. Available: http://dx.doi.org/10.1111/raju.12067
[52] D. Clifford and J. Ausloos, "Data protection and the role of fairness," *SSRN Electronic Journal*, 2017. [Online]. Available: http://dx.doi.org/10.2139/ssrn.3013139
[53] G. Malgieri, "The concept of fairness in the gdpr: a linguistic and contextual interpretation," in *Proceedings of the 2020 Conference on Fairness, Accountability, and Transparency, ser. FAT* '20*. ACM, Jan. 2020. [Online]. Available: http://dx.doi.org/10.1145/3351095.3372868
[54] R. Berk, H. Heidari, S. Jabbari, M. Kearns, and A. Roth, "Fairness in criminal justice risk assessments: The state of the art," *Sociological Methods & Research*, vol. 50, no. 1, p. 3-44, Jul. 2018. [Online]. Available: http://dx.doi.org/10.1177/0049124118782533
[55] N. Mehrabi, F. Morstatter, N. Saxena, K. Lerman, and A. Galstyan, "A survey on bias and fairness in machine learning," *ACM Computing Surveys*, vol. 54, no. 6, p. 1-35, Jul. 2021. [Online]. Available: http://dx.doi.org/10.1145/3457607
[56] N. Norori, Q. Hu, F. M. Aellen, F. D. Faraci, and A. Tzovara, "Addressing bias in big data and ai for health care: A call for open science," *Patterns*, vol. 2, no. 10, p. 100347, Oct. 2021. [Online]. Available: http://dx.doi.org/10.1016/j.patter.2021.100347
[57] L. Vicente and H. Matute, "Humans inherit artificial intelligence biases," *Scientific Reports*, vol. 13, no. 1, Oct. 2023. [Online]. Available: http://dx.doi.org/10.1038/s41598-023-42384-8
[58] E. Falletti, *Discriminazione algoritmica: una prospettiva comparata*. Giappichelli, 2022.
[59] A. Rajkomar, M. Hardt, M. D. Howell, G. Corrado, and M. H. Chin, "Ensuring fairness in machine learning to advance health equity," *Annals of Internal Medicine*, vol. 169, no. 12, p. 866, Dec. 2018. [Online]. Available: http://dx.doi.org/10.7326/M18-1990
[60] R. B. Parikh, S. Teeple, and A. S. Navathe, "Addressing bias in artificial intelligence in health care," vol. 322, no. 24, pp. 2377-2378. [Online]. Available: https://doi.org/10.1001/jama.2019.18058
[61] Z. Obermeyer, B. Powers, C. Vogeli, and S. Mullainathan, "Dissecting racial bias in an algorithm used to manage the health of populations," *Science*, vol. 366, no. 6464, p. 447-453, Oct. 2019. [Online]. Available: http://dx.doi.org/10.1126/science.aax2342
[62] C. S. Webster, S. Taylor, C. Thomas, and J. M. Weller, "Social bias, discrimination and inequity in healthcare: mechanisms, implications and recommendations," *BJA Education*, vol. 22, no. 4, p. 131-137, Apr. 2022. [Online]. Available: http://dx.doi.org/10.1016/j.bjae.2021.11.011
[63] A. M. McCarthy, M. Bristol, S. M. Domchek, P. W. Groeneveld, Y. Kim, U. N. Motanya, J. A. Shea, and K. Armstrong, "Health care segregation, physician recommendation, and racial disparities in brca1/2 testing among women with breast cancer," *Journal of Clinical Oncology*, vol. 34, no. 22, pp. 2610-2618, 2016, PMID: 27161971. [Online]. Available: https://doi.org/10.1200/JCO.2015.66.0019
[64] K. M. Hoffman, S. Trawalter, J. R. Axt, and M. N. Oliver, "Racial bias in pain assessment and treatment recommendations, and false beliefs about biological differences between blacks and whites," *Proceedings of the National Academy of Sciences*, vol. 113, no. 16, p. 4296-4301, Apr. 2016. [Online]. Available: http://dx.doi.org/10.1073/pnas.1516047113
[65] A. Samulowitz, I. Gremyr, E. Eriksson, and G. Hensing, ""brave men" and "emotional women": A theory-guided literature review on gender bias in health care and gendered norms towards patients with chronic pain," *Pain Research and Management*, vol. 2018, p. 1-14, 2018. [Online]. Available: http://dx.doi.org/10.1155/2018/6358624
[66] C. M. Roe, A. M. McNamara, and B. R. Motheral, "Gender- and age-related prescription drug use patterns," *Annals of Pharmacotherapy*, vol. 36, no. 1, pp. 30-39, 2002, PMID: 11816254. [Online]. Available: https://doi.org/10.1345/aph.1A113
[67] J. Y. Ho, "Life course patterns of prescription drug use in the united states," *Demography*, Sep. 2023. [Online]. Available: http://dx.doi.org/10.1215/00703370-10965990
[68] M. Alwhaibi and B. Balkhi, "Gender differences in potentially inappro-priate medication use among older adults," *Pharmaceuticals*, vol. 16, no. 6, p. 869, 2023.
[69] V. Orlando, S. Mucherino, I. Guarino, F. Guerriero, U. Trama, and E. Menditto, "Gender differences in medication use: A drug utilization study based on real world data," *International Journal of Environmental Research and Public Health*, vol. 17, no. 11, p. 3926, Jun. 2020. [Online]. Available: http://dx.doi.org/10.3390/ijerph17113926
[70] S. S. Oh, J. Galanter, N. Thakur, M. Pino-Yanes, N. E. Barcelo, M. J. White, D. M. de Bruin, R. M. Greenblatt, K. Bibbins-Domingo, A. H. B. Wu, L. N. Borrell, C. Gunter, N. R. Powe, and E. G. Burchard, "Diversity in clinical and biomedical research: A promise yet to be fulfilled," *PLOS Medicine*, vol. 12, no. 12, p. e1001918, Dec. 2015. [Online]. Available: http://dx.doi.org/10.1371/journal.pmed.1001918
[71] S. A. Saeed and R. M. Masters, "Disparities in health care and the digital divide," *Current Psychiatry Reports*, vol. 23, no. 9, Jul. 2021. [Online]. Available: http://dx.doi.org/10.1007/s11920-021-01274-4
[72] M. Du, F. Yang, N. Zou, and X. Hu, "Fairness in deep learning: A computational perspective," 2019. [Online]. Available: https://arxiv.org/abs/1908.08843
[73] J. Xu, Y. Xiao, W. H. Wang, Y. Ning, E. A. Shenkman, J. Bian, and F. Wang, "Algorithmic fairness in computational medicine," *eBioMedicine*, vol. 84, p. 104250, Oct. 2022. [Online]. Available: http://dx.doi.org/10.1016/j.ebiom.2022.104250
[74] E. Ferrara, "Fairness and bias in artificial intelligence: A brief survey of sources, impacts, and mitigation strategies," 2023. [Online]. Available: https://arxiv.org/abs/2304.07683
[75] C. Gallese, T. Scantamburlo, L. Manzoni, and M. S. Nobile, "Investigating semi-automatic assessment of data sets fairness by means of fuzzy logic," in *2023 IEEE Conference on Computational Intelligence in Bioinformatics and Computational Biology (CIBCB)*. IEEE, Aug. 2023. [Online]. Available: http://dx.doi.org/10.1109/CIBCB56990.2023.10264913
[76] T. Gebru, J. Morgenstern, B. Vecchione, J. W. Vaughan, H. Wallach, H. Daumé, and K. Crawford, "Datasheets for datasets," 2018. [Online]. Available: https://arxiv.org/abs/1803.09010
[77] S. Holland, A. Hosny, S. Newman, J. Joseph, and K. Chmielinski, "The dataset nutrition label: A framework to drive higher data quality standards," 2018. [Online]. Available: https://arxiv.org/abs/1805.03677
[78] R. F. Wolff, K. G. Moons, R. D. Riley, P. F. Whiting, M. Westwood, G. S. Collins, J. B. Reitsma, J. Kleijnen, and S. Mallett, "Probast: A tool to assess the risk of bias and applicability of prediction model studies," *Annals of Internal Medicine*, vol. 170, no. 1, p. 51, Jan. 2019. [Online]. Available: http://dx.doi.org/10.7326/M18-1376
[79] WHO Collaborating Centre for Drug Statistics Methodology. (2024) *ATC/DDD Index*. Accessed on 05/01/2024. [Online]. Available: www.whocc.no/atc\_ddd\_index/
[80] I. M. Agency, "The Italian drug traceability system," 2020, [Accessed 05/01/2024].
[81] J. W. Tukey et al., *Exploratory data analysis*. Reading, MA, 1977, vol. 2.
[82] ISTAT, "I centenari in italia," 2019, [Accessed 05/01/2024]. [Online]. Available: www.istat.it/it/files/2019/07/Statistiche\_Today-I-centenari-in-Italia.pdf
[83] A. Naser, H. Alwafi, T. Al-Daghastani, S. Hemmo, H. M. Alrawashdeh, Z. Jalal, V. Paudyal, N. Alyamani, M. Almaghrabi, and A. Shamieh, "Drugs utilization profile in england and wales in the past 15 years: a secular trend analysis," *BMC Primary Care*, vol. 23, 09 2022.
[84] C. Rudin, "Stop explaining black box machine learning models for high stakes decisions and use interpretable models instead," 2018. [Online]. Available: https://arxiv.org/abs/1811.10154
[85] D. Morgan, "Anticipatory regulatory instruments for ai systems: A comparative study of regulatory sandbox schemes," in *Proceedings of the 2023 AAAI/ACM Conference on AI, Ethics, and Society*, 2023, pp. 980-981.
[86] S. Lee, "(a) study on the anticipatory regulation in an era of technolog-ical innovation," 2023.
[87] E. Fosch-Villaronga and M. Heldeweg, "regulation, i presume?" said the robot-towards an iterative regulatory process for robot governance," *Computer law & security review*, vol. 34, no. 6, pp. 1258-1277, 2018.
[88] E. Parliament. (2023, June) *Eu ai act: first regulation on artificial intelligence*.
[89] S. Perna, A. Pierantozzi, F. Fortinguerra, S. M. Cammarata, F. Trotta, A. Cangini, F. Ambrosino, F. Milozzi, and A. Di Filippo, "Disug-uaglianze sociali nell'uso dei farmaci per la cura delle malattie croniche. le principali evidenze dall'atlante aifa," *Recenti Progressi in Medicina*, vol. 112, no. 11, pp. 711-719, 2021.
[90] T. Scantamburlo, P. Falcarin, A. Veneri, A. Fabris, C. Gallese, V. Billa, F. Rotolo, and F. Marcuzzi, "Software Systems Compliance with the AI Act. Lessons Learned from an International Challenge," in *2nd International Workshop on Responsible AI Engineering (RAIE'24)*, 2024.