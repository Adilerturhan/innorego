# Summary of Module 5: AI and Data Regulation

This summary provides a comprehensive overview of the key legal and ethical issues surrounding AI and data regulation, based on the lecture "Lezioni Tilburg 2025.md" and supplemented by in-depth papers on bias and fairness. The module covers the legal framework for data collection, the core principles of the GDPR, the risk-based approach of the EU AI Act, and a deep dive into the practical and theoretical aspects of identifying and mitigating bias in AI systems.

## 1. Introduction: The Challenge of Data Collection for Machine Learning

The foundation of any machine learning model is the data it is trained on. However, the methods used for data collection are fraught with legal and ethical challenges. High-profile cases involving companies like **IBM**, **ClearviewAI**, and **OpenAI** highlight a common pitfall: the wrongful collection and use of data scraped from the web. These companies faced legal action for scraping images, texts, and other personal data without consent, failing to inform individuals about their data practices, and using copyrighted materials without authorization.

A critical misconception is that "publicly available" data is equivalent to "public domain" data. This is incorrect. As detailed in `Module_5/Lezioni Tilburg 2025.md`, several legal and ethical frameworks govern the use of online data:

1.  **Copyright Laws**: Publicly accessible content, including logos, text, and images, is often still protected by copyright.
2.  **Data Protection Laws (GDPR)**: Personal data of living individuals remains protected under privacy laws like the GDPR, even if it is publicly visible online.
3.  **Web Scraping Laws**: The EU, through regulations like the **DSM Directive**, has specific rules governing web scraping.
4.  **Contract Laws**: Websites have terms of service that can contractually prohibit data scraping.
5.  **Ethics**: Beyond the law, ethical principles dictate that using people's data without consent, information, or for potentially harmful purposes is wrong.

### Legal Precedents in Data Scraping

The legal landscape of data scraping is complex and context-dependent, as illustrated by several key court cases:

-   **The Database Directive & *Ryanair***: In a case between **Ryanair** and websites like **Volagratis**, the court ruled that scraping for price comparison was lawful because Ryanair's database lacked the "creative intellectual contribution" required for copyright protection. The *sui generis* right was also excluded, as Ryanair's intent seemed to be preventing competition rather than protecting a substantial investment in the database itself. This case, however, is noted as not being applicable to AI training.

-   **DSM Directive & Text and Data Mining (TDM)**: **Article 4 of the Directive (EU) 2019/790** provides a crucial exception for TDM (automated analysis of digital information). It allows reproductions and extractions for TDM purposes, but with a significant caveat: this exception does not apply if the rights holders have "expressly reserved" their rights in a machine-readable format (e.g., in `robots.txt`). This gives content owners an "opt-out" mechanism.

-   **US Case Law**:
    -   ***LinkedIn Corp. v. hiQ Labs Inc.***: This landmark case involved hiQ scraping public LinkedIn profiles for business analytics. While lower courts initially sided with hiQ, the legal battle highlighted the tension between public data access and a platform's terms of service. The final ruling emphasized **contract liability**, suggesting that violating a user agreement that prohibits scraping can be a basis for legal action.
    -   ***Ryanair DAC v. Booking Holdings Inc.***: This US case, under the Computer Fraud and Abuse Act (CFAA), established that scraping publicly available information without an authentication mechanism (like a password) is not a violation of the CFAA. However, the court noted that a cease-and-desist letter *could* withdraw authorization to access a *protected* (i.e., authenticated) part of a website.

The overarching rule is that **web scraping can be limited by a contractual clause**.

## 2. Foundational Principles of Data Protection (GDPR)

The **General Data Protection Regulation (GDPR)** is the cornerstone of data protection in the EU. It aims to protect the personal data of natural persons and facilitate its free movement within the EU.

-   **Scope**: The GDPR applies to any data controller or processor established in the EU, or to those outside the EU whose activities target subjects within the EU. It does not apply to purely personal/household activities or to law enforcement activities related to criminal offenses.
-   **Key Definitions**:
    -   **Personal Data**: Any information directly or indirectly related to a natural person (e.g., biometric data, identifiers, location, opinions).
    -   **Processing**: Any operation performed on personal data, from collection and storage to analysis, modification, and deletion. **Data collection for AI is a form of processing.**

### The Seven GDPR Principles

The GDPR is built on seven core principles that must be adhered to throughout the data lifecycle:

1.  **Lawfulness, Fairness, and Transparency**: Processing must have a valid legal basis, be fair to the data subject, and be transparent. In ML, this means ensuring you have the right to use the data, respecting licenses, and informing data subjects.
2.  **Purpose Limitation**: Data must be collected for specified, explicit, and legitimate purposes and not be further processed in a manner incompatible with those purposes. You cannot collect data "just in case."
3.  **Data Minimization**: Only data that is strictly necessary for each specific purpose should be collected.
4.  **Accuracy**: Personal data must be kept correct and up-to-date. Inaccurate data must be rectified or erased.
5.  **Storage Limitation**: Data should be kept in a form which permits identification of data subjects for no longer than is necessary for the purposes for which the data are processed.
6.  **Integrity and Confidentiality**: Data must be processed in a manner that ensures appropriate security, including protection against unauthorized or unlawful processing and against accidental loss, destruction, or damage.
7.  **Accountability**: The data controller is responsible for, and must be able to demonstrate, compliance with all the GDPR principles.

### Legal Basis for Processing in AI

For AI development, the most common legal bases under the GDPR are:
-   **Legitimate Interest**: Can be used for research or further use of public datasets, but requires a Legitimate Interest Assessment (LIA) to balance the controller's interest against the data subject's rights.
-   **Consent**: Must be freely given, specific, informed, and unambiguous. For special categories of data, it must be explicit. Consent can be withdrawn at any time.
-   **Public Task**: Applicable when training models for public functions, such as law enforcement.

## 3. The EU AI Act: A Risk-Based Framework

The proposed **EU AI Act** is the world's first comprehensive regulation on artificial intelligence. It adopts a **risk-based approach**, classifying AI systems into four categories based on the potential risk they pose to health, safety, and fundamental rights.

### Risk Categories

1.  **Unacceptable Risk (Banned)**: These AI systems are deemed a clear threat to the safety, livelihoods, and rights of people and will be banned. This includes:
    -   AI deploying **subliminal techniques** to distort behavior.
    -   AI that **exploits vulnerabilities** of specific groups (e.g., due to age or disability).
    -   **Social scoring** by public authorities.
    -   **'Real-time' remote biometric identification** in public spaces for law enforcement purposes (with very narrow exceptions).

2.  **High-Risk**: These systems are not banned but are subject to strict requirements. They include AI used in:
    -   Critical infrastructure (e.g., transport).
    -   Education and vocational training.
    -   Employment and workers management.
    -   Access to essential public and private services (e.g., credit scoring).
    -   Law enforcement, migration, and administration of justice.
    -   Medical devices.

3.  **Limited Risk**: These systems have specific transparency obligations. For example, users must be informed that they are interacting with an AI system (e.g., chatbots) or that content is AI-generated (e.g., deepfakes).

4.  **Minimal or No Risk**: This category includes the vast majority of AI systems (e.g., spam filters, AI in video games), which can be developed and used without additional legal obligations.

### Mandatory Requirements for High-Risk AI Systems

The AI Act imposes stringent obligations on providers of high-risk systems:

1.  **Risk Management System**: A continuous process to identify, analyze, and mitigate risks throughout the AI system's lifecycle.
2.  **Data and Data Governance**: This is a cornerstone of the Act, directly addressing the problem of "garbage in, garbage out." Training, validation, and testing datasets must be:
    -   **Relevant, representative, free of errors, and complete.**
    -   Examined for possible **biases**.
    -   Take into account the specific context in which the AI will be used.
    The Act explicitly allows for the processing of **special categories of personal data** (like health or ethnicity) if it is strictly necessary for **bias monitoring, detection, and correction**, providing a substantial public interest legal basis.
3.  **Technical Documentation**: Detailed documentation must be drawn up to demonstrate compliance.
4.  **Record-Keeping (Logs)**: Systems must be able to automatically record events to ensure traceability of their operation.
5.  **Transparency and Provision of Information**: Users must be provided with clear instructions for use, including the AI's capabilities, limitations, and human oversight measures.
6.  **Human Oversight**: Systems must be designed to be effectively overseen by humans, who should be able to intervene or stop the system.
7.  **Accuracy, Robustness, and Cybersecurity**: Systems must be resilient against errors, faults, and attempts by unauthorized third parties to alter their use or performance (e.g., data poisoning, adversarial attacks).

## 4. Deep Dive: Bias, Fairness, and Data Quality

A central theme of the module is the critical importance of addressing bias to achieve fairness. Bias in AI is not just a technical flaw; it is a societal issue with profound ethical and legal implications.

### What is Bias?

As defined by Friedman and Nissenbaum, bias refers to computer systems that **"systematically and unfairly discriminate against certain individuals or groups of individuals in favor of others."** This can originate from pre-existing societal biases that are implicitly or explicitly present in the data.

The lecture and supplementary papers (`Identifying Bias in Data Collection.md`, `Investigating Fairness with FanFAIR.md`, `Investigating Semi-Automatic Assessment of Data Sets Fairness by Means of Fuzzy Logic.md`) outline several types of bias:

-   **Selection Bias**: Occurs when data is not selected in a way that is representative of the real world (e.g., sampling bias, participation bias).
-   **Reporting Bias**: The selective inclusion of results, such as publishing only studies with positive outcomes.
-   **Group Attribution Bias**: The tendency to generalize from a group to an individual (stereotyping) or vice versa.
-   **Implicit Bias**: Unconscious assumptions and stereotypes that influence how data is collected and interpreted.
-   **Overfitting/Underfitting**: Technical issues where a model learns noise from the training data (overfitting) or fails to capture the underlying trend (underfitting).

### Fairness in Practice: The FanFAIR Framework

The paper `Investigating Semi-Automatic Assessment of Data Sets Fairness by Means of Fuzzy Logic.md` introduces **FAnFAIR**, a tool designed to provide a semi-automated assessment of a dataset's fairness. It moves beyond purely technical metrics to integrate qualitative, legal, and ethical considerations.

FAnFAIR uses a fuzzy logic system to generate a fairness score based on six key features:

1.  **Balance**: How well-represented different classes are in the dataset. An unbalanced dataset (e.g., far more examples of "healthy" than "unhealthy" patients) can lead to a biased model.
2.  **Numerosity**: The ratio of instances (rows) to features (columns). A low ratio can lead to spurious correlations.
3.  **Unevenness**: The presence of outliers, which can indicate data errors or create privacy risks (singling out).
4.  **Incompleteness**: The amount of missing data ("holes") in the dataset.
5.  **Quality (User-Defined)**: A qualitative assessment by a domain expert on the overall quality and reliability of the data.
6.  **Compliance (User-Defined)**: An assessment of whether the data collection adhered to legal and ethical rules (Data Protection, Copyright, Medical Law, Non-discrimination, Ethics).

The paper `Investigating Fairness with FanFAIR.md` extends this tool and applies it to a real-world COVID-19 dataset. The case study demonstrates that **data cleaning and pre-processing steps not only improve the predictive performance of a model but also increase the dataset's fairness score.** This finding challenges the common assumption that fairness and performance are always in opposition.

### Case Study: Identifying Bias in Drug Distribution

The paper `Identifying Bias in Data Collection.md` provides a practical case study on identifying bias in pharmaceutical data from Italy. The analysis reveals several critical issues:

-   **Missing Data**: A significant percentage of geographical data was missing, making it impossible to verify if certain communities were underrepresented.
-   **Gender Disparities**: While the dataset was balanced in the number of male and female patients, analysis showed significant differences in the *types* of drugs used. For example, women had higher utilization of medications for the Alimentary Tract and Nervous System, while men used more drugs for the Cardiovascular System.
-   **Age and Chronic Conditions**: The age distribution for patients with chronic conditions was heavily skewed towards older individuals, and these patients showed a higher use of cardiovascular medications.

This study proves the importance of **Exploratory Data Analysis (EDA)** as a first step to uncover hidden biases. It highlights that even if a dataset appears balanced on the surface (e.g., by gender), deeper analysis can reveal social biases that may stem from prescription patterns, physiological differences, or systemic healthcare disparities. Such analysis is a crucial part of the "Data Governance" framework required by the AI Act.

## 5. Conclusion: Towards Trustworthy AI

Module 5 emphasizes that building trustworthy AI is a multi-faceted challenge that cannot be solved by technical means alone. It requires a holistic approach that integrates legal compliance, ethical principles, and robust technical practices.

-   **Lawfulness is the Baseline**: Adherence to regulations like the GDPR and the AI Act is non-negotiable. Wrongful data collection is a foundational error that can undermine an entire AI project.
-   **Data is the Foundation**: The quality, representativeness, and fairness of data are paramount. As the FAnFAIR and drug distribution studies show, a rigorous assessment of datasets is the first line of defense against building biased and discriminatory systems.
-   **Fairness is Contextual**: Fairness is not a simple mathematical formula. It involves legal principles, ethical considerations, and an understanding of the societal context. Tools like FAnFAIR provide a framework for this complex assessment.
-   **Anticipatory Regulation**: The AI Act encourages a proactive approach. By embedding requirements for data governance, risk management, and bias detection directly into the development process, the regulation aims to build trust and safety from the ground up, rather than trying to fix harms after they occur.

Ultimately, the development and deployment of AI, especially in high-risk domains, is not just a technical exercise but a socio-technical one that demands accountability, transparency, and a steadfast commitment to protecting fundamental rights.

---
*Citations:*
- `Module_5/Lezioni Tilburg 2025.md`
- `Module_5/Identifying Bias in Data Collection.md`
- `Module_5/Investigating Fairness with FanFAIR.md`
- `Module_5/Investigating Semi-Automatic Assessment of Data Sets Fairness by Means of Fuzzy Logic.md`