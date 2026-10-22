Module 5 - AI and Data Regulation: Fairness, Compliance, and Tools
The sources emphasize that the effectiveness and ethical integrity of AI systems depend entirely on the data they are trained on [1]. Biased datasets can lead to inaccurate or discriminatory ML systems, undermining predictions and risking harm, especially in high-risk applications such as biomedicine and healthcare [2].
I. The Challenge of Bias and AI Regulation
Fairness in AI relates to mitigating biases embedded in datasets to prevent AI systems from perpetuating or exacerbating inequities [3].
1. Sources of Bias and Regulatory Tension
Datasets can encode historical and structural biases that reflect an unfair world [3]. While technical methods like debiasing exist, there is a recognized tension [4]:
• Datasets can be technically debiased according to predefined metrics, but they may still perpetuate and amplify injustices inherent in the social systems from which the data were derived [4].
• Addressing fairness requires engaging with the larger social, political, and economic systems of power and inequality, rather than relying solely on technical fixes for deeply entrenched social problems [5].
• Unfairness is not solely dependent on the data, but extends to human activities like ensuring consent for personal data reuse, enacting transparency, and performing extensive ethical assessments (including principles like Accountability, Dignity, and Risk Assessment) [5].
2. Types of Bias and Errors in Data Sets
Bias is defined as computer systems that systematically and unfairly discriminate against certain individuals or groups [6]. Examples of types of bias related to data collection and modeling include:
• Selection Bias: When data are selected in a way that is not representative of the distribution in real life (e.g., participation bias, sampling bias) [7].
• Overfitting and Underfitting: Overfitting occurs when a model learns from noise and inaccurate data entries, failing to generalize to new data; underfitting occurs when the model fails to capture the underlying trend [8, 9].
• Reporting Bias: The inclusion of only a portion of results in an analysis, such as citation bias or publication bias [9, 10].
• Group Attribution Bias: The tendency to stereotype or think a group’s beliefs dictate an individual’s traits [11].
• Implicit Bias: Assumptions drawn from personal experiences that lead to acting with bias and stereotypes without awareness [12].
• Variance: The model’s sensitivity to changes in the data; high variance models focus excessively on training data [13].
II. The EU Regulatory Framework
The EU approach to AI is governed by the General Data Protection Regulation (GDPR) and the new AI Act, which uses a risk-based framework [14].
1. GDPR Basic Principles and Data Handling
GDPR protects the personal data of natural persons [15]. Data collection, web scraping, and training an AI model are all considered forms of data processing [16-18].
Principle
Description & Relevance
Source(s)
Lawfulness, Fairness, Transparency
Requires a legal basis for processing, respecting all laws, providing privacy notices (Articles 13 and 14), and not discriminating [18-21].
[18-21]
Purpose Limitation
Data must be used only for lawful purposes, and further purposes must be compatible with the original ones [20].
[20]
Data Minimisation
Only the data strictly necessary for each purpose can be collected; collecting data "just in case" is prohibited [20, 22].
[20, 22]
Accountability
The Data Controller (the entity determining purposes and means, e.g., MingleMore Ltd [23]) is responsible for compliance and must demonstrate it [23, 24].
[23, 24]
Special Categories of Data
Includes health data (e.g., physiological measurements), sexual orientation, religious beliefs, and political opinions [25, 26]. Processing these requires explicit consent (Article 9(2)(a)) [27, 28].
[25-28]
DPIA (Impact Assessment)
High-risk processing, such as processing special categories of personal data on a large scale (e.g., in the Heartsy application), requires the controller to conduct a Data Protection Impact Assessment (DPIA) (Article 35) to assess and mitigate risks [19, 29].
[29]
2. The AI Act and Risk-Based Regulation
The AI Act establishes four risk categories to protect citizens' fundamental rights, based on the intended purpose of the AI system [14, 30].
• Unacceptable Risk: AI systems presenting an unacceptable risk to fundamental rights are banned [14]. Examples include systems that deploy subliminal techniques to materially distort a person’s behavior, or the use of ‘real-time’ remote biometric identification systems in publicly accessible spaces for law enforcement purposes [31-33].
• High Risk: These systems have to meet complex mandatory requirements before being released [34]. Examples include AI systems used in medical devices, critical infrastructure, employment, and the administration of justice [34, 35].
• Mandatory Requirements for High-Risk Systems (Data Governance): Article 10 mandates that providers implement stringent data quality and bias mitigation measures [36, 37]:
    ◦ Data Sets: Training, validation, and testing data sets must be relevant, representative, and to the best extent possible, free of errors and complete [38, 39].
    ◦ Bias Monitoring: Providers may process special categories of personal data (e.g., health data) if strictly necessary for the purpose of bias monitoring, detection, and correction (Article 10) [40, 41]. This visionary provision provides an ad hoc legal basis for using sensitive data for bias mitigation, though it raises privacy concerns that need further examination [42].
    ◦ Risk Management: A system must be in place to identify, analyze, and evaluate known and foreseeable risks throughout the entire lifecycle [35, 43].
III. FanFAIR: A Tool for Dataset Fairness Assessment
FanFAIR is a Python tool designed for the semi-automatic assessment of dataset fairness using a rule-based approach that leverages fuzzy logic [2, 44, 45]. It aims to integrate statistical properties of a dataset with qualitative considerations like ethics, human rights, and data protection [2].
1. Fairness Features Assessed by FanFAIR
FanFAIR evaluates a dataset based on six linguistic variables, four statistical and two qualitative, which are combined into a single fairness score (ranging from 0 to 100) using a Fuzzy Inference System (FIS) [44, 46-49].
Feature
Assessment/Rationale
Source(s)
Balance
Measures how balanced the dataset is with respect to the output labels. An unbalanced dataset may produce biased models unable to generalize [50-52].
[50-53]
Numerosity
The quantity of instances normalized by the number of features. Low numerosity hinders generalization; a widespread rule of thumb suggests an optimal number of instances S would be 10
timesD (features) [54-57].
[53-57]
Unevenness
Measures the amount of outliers. Outliers are not useful for generalization and present a risk of singling out individuals, leading to potential privacy recognition if data is released [58-60].
[53, 58-60]
Incompleteness
Measures the frequency of missing values in the dataset. When this occurs, imputation techniques may be necessary, or patients may need to be discarded [53, 61-63].
[53, 61-63]
Compliance
Measures compliance with laws and legal duties (e.g., data protection, copyright, medical, non-discrimination, and ethics) [53, 64, 65]. This variable must be manually set by the user [46, 66].
[53, 64-66]
Quality
A manually set feature evaluating the overall data quality (e.g., clarity of images, noise, reliability of collection) as assessed by a domain expert [53, 67, 68].
[53, 67, 68]
2. Analysis of Sensitive Variables
FanFAIR has been extended to specifically analyze sensitive variables (e.g., gender, ethnicity, age) that should not be directly responsible for a given prediction [69, 70].
• The tool calculates the Pearson’s correlation coefficient between each sensitive input variable and the output variable [71].
• The fairness assessment is determined by the maximum absolute correlation found across all sensitive variables (Equation 2) [70].
• The rationale is that a high correlation of the output to even a single variable marked as sensitive is enough to classify the whole dataset as unfair, strongly advising the removal of that variable before model training [70].
IV. Practical Findings on Data Processing and Fairness
The application of FanFAIR and data analysis reveals the direct relationship between data preparation and algorithmic outcomes.
1. Performance and Fairness Improvement
A case study using real-world COVID-19 patient data showed that data fairness and model performance can improve in parallel when appropriate data processing (cleaning, variable selection) is set in place [2, 72]. This contradicts the common belief that performance and fairness are always in contrast [2].
• The most substantial contribution to the fairness score in the COVID study (+6.4%) was achieved by excluding variables with high sparsity (many undefined values) and restricting the cohort to the population of interest [73].
• Model performance (specifically, recall and F1 score on deceased patients) improved significantly when trained on more processed versions of the dataset [74].
2. Identifying Social and Statistical Bias (Drug Distribution Case)
Analysis of pharmaceutical data revealed critical issues impacting fairness and trustworthiness [75, 76]:
• Incompleteness (Missing Data): Most missing values were found in geographical information (pharmacy location, patient residence), making it impossible to reliably analyze these fields or verify that geographical communities are not underrepresented [76, 77].
• Social Bias (Gender/Age Disparities): While the overall dataset was balanced regarding the number of dispensations and unique patients across genders, a visual analysis revealed differences in age distribution by gender across therapeutic groups (ATC I) [78]. For instance, women across all age groups exhibit a higher utilization of gynecological and sex hormone-related drugs (Group G), while men use Cardiovascular System drugs (Group C) more frequently [78, 79].
• Mitigation Need: It is crucial to consult medical experts to determine if these discrepancies stem from physiological variations or are influenced by known gender biases in the literature [80]. The successful detection of potential biases proves the importance of performing an Exploratory Data Analysis (EDA) before the modeling phase to prevent the perpetuation of social biases [81, 82].
3. Data Processing Techniques and Risks
While pre-processing improves fairness, various techniques introduce new risks:
• Imputation: Filling missing values ("holes") with guessed, realistic values assumes similarity to existing data, which can reinforce existing patterns and potentially introduce biases by turning a non-significant pattern into a significant one [83, 84].
• Synthetic Data: Artificially created information protects privacy [85]. However, the quality of synthetic data is highly correlated with the quality of the original data and the generation model, meaning synthetic data may reflect the biases present in the original data [86].
• Oversampling/Undersampling: Used to balance a dataset. Imbalance can be problematic, particularly when the goal is to predict rare outcomes (minority classes) [87, 88]. Oversampling should only be applied to the training set, never the test set [89].