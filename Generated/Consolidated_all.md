# Module 2: Health Data Sharing – Consolidated Summary

**Module Title:** The (EU) Regulation of Health Data Sharing  
**Instructor:** Tjaša Petročnik, TILT, Tilburg Law School  
**Date:** 2025  

This consolidated document synthesizes the essential concepts from Module 2, integrating foundational regulatory frameworks (GDPR, DGA, Data Act) with comprehensive coverage of the European Health Data Space (EHDS) Regulation and its implications for health data governance across the EU. The document combines depth from extensive lecture materials with detailed analysis of the newly enacted EHDS Regulation.

---

## Table of Contents

1. [Introduction: Health Data as Critical Infrastructure](#introduction)
2. [Foundational Economic Principles](#economics)
3. [Data Sensitivity and Multi-Framework Governance](#sensitivity)
4. [General Data Protection Regulation (GDPR) Framework](#gdpr)
5. [Data Governance Act (DGA)](#dga)
6. [Data Act (DA)](#data-act)
7. [European Health Data Space (EHDS) Regulation](#ehds)
8. [EHDS: Primary Use of Health Data](#ehds-primary)
9. [EHDS: Secondary Use of Health Data](#ehds-secondary)
10. [Implementation Roadmap and Timeline](#implementation)
11. [Critical Perspectives and Challenges](#challenges)
12. [Key Takeaways](#conclusions)

---

## 1. Introduction: Health Data as Critical Infrastructure {#introduction}

### The Data Sharing Imperative

Health data represents one of the most valuable and sensitive resource categories in the EU. The COVID-19 pandemic starkly demonstrated why rapid, secure health data exchange has become essential for modern healthcare and public health systems.

The ability to share health data effectively enables disease surveillance and response capabilities that allow authorities to respond to epidemiological threats in real time. When patients can access and share their health data across borders, diagnosis and treatment continuity improve significantly. Aggregated health datasets accelerate research and innovation, facilitating the development of new diagnostics, therapeutics, and medical devices that might otherwise take years to emerge. Finally, evidence-based health policymaking depends fundamentally on access to reliable, comprehensive health data. Without coordinated data sharing, policymakers lack the information necessary to design effective health interventions.

### Why Regulate Health Data Sharing?

Three primary justifications underpin the need for regulatory intervention. First, fundamental rights protection is paramount. Health data are inherently sensitive personal data that reveal information about physical, mental, genetic, and behavioral characteristics. EU law recognizes that natural persons possess fundamental rights to privacy, data protection, and human dignity that must be actively protected.

Second, market failures necessitate intervention. Without regulatory coordination, health data remains fragmented across disconnected national systems, providers, and repositories. Voluntary sharing mechanisms have proven insufficient to overcome technical and organizational fragmentation, lack of standardization and interoperability, competing economic interests among data holders, and information asymmetries between stakeholders. These barriers prevent the emergence of integrated health data ecosystems that would benefit all participants.

Third, strategic coordination can unlock significant innovation and public value. Beyond what individual actors could achieve in isolation, coordinated health data sharing generates societal benefits that justify regulatory investment. These benefits include improved healthcare efficiency, accelerated medical innovation, strengthened public health capabilities, and more effective health policy development.

---

## 2. Foundational Economic Principles {#economics}

### Non-Ordinary Characteristics of Data

Health data exhibits distinctive economic characteristics that fundamentally differentiate it from traditional goods. First, data is non-rivalrous—unlike physical assets, multiple parties can use the same data simultaneously without diminishing its value for any individual user. Once collected, the marginal reproduction cost approaches zero, enabling unlimited replication at minimal expense. Second, without legal frameworks in place, data becomes non-excludable; once it enters the public domain, it becomes difficult to exclude competitors from accessing it, creating classic public goods problems. Third, after initial collection, providing data to additional users incurs negligible costs. These characteristics enable powerful economies of scope and scale in health data ecosystems.

### Economic Efficiencies in Data Sharing

Several mechanisms drive the economic case for coordinated health data sharing. Economies of scope emerge because once a healthcare provider has invested in data collection for clinical purposes, the same data can be reused for secondary purposes such as research, public health, and policy development at minimal additional cost. Economies of scale operate through data aggregation—combining data from multiple sources dramatically increases statistical power and analytical capacity. Rare disease epidemiology, for instance, requires population-level datasets from multiple Member States; pharmacovigilance benefits from large numbers of adverse event reports; and health technology assessment is strengthened by comparative effectiveness data from diverse populations that might otherwise remain isolated.

Network effects further strengthen the case for coordinated ecosystems. The value of health data systems increases as more participants contribute data and more potential users can access it. Standardized data exchange formats create positive externalities for all ecosystem participants, making the system increasingly valuable as it scales. These three mechanisms—scope, scale, and network effects—combine to create strong economic justification for regulatory coordination of health data sharing.

### Primary vs. Secondary Use Economics

The EHDS framework recognizes that health data creates value through two fundamentally different mechanisms, requiring distinct governance approaches. Primary use—healthcare delivery to individual patients—is primarily driven by economies of scope. By enabling data portability and reducing lock-in to individual providers, primary use improves competition among healthcare providers through information transparency, which in turn facilitates informed patient choice and more efficient healthcare markets.

Secondary use—research, policy, and innovation activities—operates according to different economic principles. These purposes are driven by economies of scale and aggregation benefits, requiring large, representative datasets to generate meaningful insights. However, benefits from aggregation follow the law of diminishing returns: as datasets grow, each additional record contributes progressively less analytical value until further expansion provides minimal benefit. This economic reality has important implications for governance; secondary use requires fundamentally different regulatory structures than primary use, including mechanisms to manage access, prevent misuse, and balance individual privacy protection against public benefit.

---

## 3. Data Sensitivity and Multi-Framework Governance {#sensitivity}

### Conceptualizing Health Data Sensitivity

Health data sensitivity operates along two critical dimensions that interact in complex ways. The first dimension concerns intrinsic sensitiveness—certain categories of data inherently reveal personal characteristics of particular importance to individuals. Genetic information can identify biological ancestry and disease predispositions; mental health data reveals psychological conditions and vulnerabilities; sexual health data discloses intimate aspects of personal life; and substance use data indicates addiction or dependency. These data carry heightened sensitivity because they relate to core aspects of personal identity and autonomy.

The second dimension, computational distance, describes the extent to which personal inferences can be drawn from apparently non-health data. The sensitivity framework identifies three layers. Layer 1 data consists of explicitly health-relevant information such as diagnoses, treatments, and medications—data that is inherently sensitive. Layer 2 data comprises contextually health-relevant information such as behavioral data from fitness applications or location data reflecting mobility patterns. While not explicitly health-related, Layer 2 data is indirectly sensitive because it can be analyzed for health insights. Layer 3 data includes potentially health-relevant information such as social media activity or purchasing patterns that carry low intrinsic sensitivity but can reveal health information as an unintended by-product. Understanding these distinctions is crucial for designing appropriate governance frameworks that protect privacy while enabling beneficial data use.

### Five Legal Frameworks Governing Health Data Use

Health data on the internet remains subject to five distinct legal and ethical frameworks, even when publicly accessible. Understanding how these frameworks interact is essential for lawful data processing.

**Copyright law** protects publicly visible content. Users can see Disney+ images, but copyright protection remains active. Using copyrighted materials—logos, databases, text, images, videos, software, graphics—for training AI systems without authorization constitutes infringement regardless of public visibility.

**Data protection law**, comprising both the General Data Protection Regulation (EU), applicable in 27 Member States, and Convention 108+ (Council of Europe), applicable in 55 countries, protects personal data of living persons. Critical to understanding this framework is that public availability does not waive data protection rights. Names, email addresses, and photos on social media remain protected even when publicly visible.

**Web scraping laws**, established through the Directive on Copyright and Related Rights in the Digital Single Market (Directive (EU) 2019/790), provide limited exceptions for text and data mining from copyright restrictions. However, a critical limitation constrains commercial applications: the exception does not apply to commercial AI training. Rights holders can assert restrictions through machine-readable formats such as robots.txt and HTML meta tags, creating legally enforceable limitations on automated data collection.

**Contract law** operates through website terms of service, which constitute binding contracts. Automated data collection that violates contractual terms creates legal liability. The landmark case of LinkedIn Corp. v. hiQ Labs Inc. demonstrated that contractual restrictions can constrain data access even when data is technically public.

**Ethics**, codified in international frameworks including EU AI High-Level Expert Group Guidelines, UNESCO Recommendation on AI Ethics, and OECD AI Principles, establishes binding ethical principles including respect for human autonomy, prevention of harm, and fairness and transparency. Using data without consent, information, or for potentially harmful purposes violates these principles and fundamental human dignity.

---

## 4. General Data Protection Regulation (GDPR) Framework {#gdpr}

### Legal Hierarchy and Fundamental Rights

The GDPR operates within a hierarchical legal system:

1. **International Conventions and Treaties** (European Convention on Human Rights, Convention 108+)
2. **EU Primary Law** (EU Treaties, Charter of Fundamental Rights)
3. **EU Secondary Law** (GDPR, Directives)
4. **National Constitutions and Laws**
5. **Administrative Regulations**

When conflicts arise, higher-ranking instruments prevail. The GDPR must be interpreted in light of the **Charter of Fundamental Rights**, particularly Articles on privacy (Article 7) and personal data protection (Article 8).

### Scope of GDPR Application

The GDPR applies in three principal circumstances. First, when a data controller or processor is established in the EU, the regulation applies regardless of where processing actually occurs. Second, where processing activities target subjects located in the EU, the GDPR applies even if the controller operates outside EU territory. Third, when competent authorities process data for non-law-enforcement purposes, the regulation provides applicable rules.

A crucial point for practical application: a data subject's nationality is irrelevant to GDPR's scope. What matters is whether they are located in the EU or targeted by services. This territorial approach ensures broad protection for individuals in EU jurisdictions.

Conversely, the GDPR does not apply in certain circumstances. Personal or household activities—such as personal photographs on private devices—fall outside the regulation's scope, reflecting the principle that purely private, non-commercial data use requires no regulatory compliance. Law enforcement processing for criminal purposes is excluded because a separate directive, the Law Enforcement Directive, establishes tailored rules for that context. Similarly, activities of EU institutions themselves are covered by separate legislation, Regulation 2018/1725, rather than the GDPR.

### Core Definitions for Health Data

#### Personal Data (Article 4(1))

"Personal data" means any information relating to an identified or identifiable natural person. For health data, this definition encompasses far more than traditional medical records. Biometric data including photographs, fingerprints, video recordings, and facial recognition information qualify as personal data. Genetic data such as DNA sequences, genetic markers, and genomic profiles fall within the definition. Health-related inferences drawn through profiling techniques—health habit profiles, disease risk profiles, wellness scores—constitute personal data. Identifiers such as patient ID numbers, medical record numbers, and even nicknames indicating health status are covered. Location data including home addresses and patterns of hospital visits constitute personal data. Even data about medical beliefs such as religious or philosophical objections to treatments qualify for protection. Data about feelings and mental states, emotional states, burnout information, and mental health status are protected. Financial information related to health, including insurance claims and out-of-pocket healthcare spending, also qualifies.

A critical point emerging from this broad definition: personal data can exist in any format, not only text documents. Mathematical representations—embeddings and vectors used in machine learning models for clinical prediction—constitute personal data under the regulation. This means that AI systems trained on health information process personal data from their inception, triggering GDPR obligations at the earliest stages of model development.

#### Processing (Article 4(2))

The GDPR defines processing expansively to encompass virtually any action taken with personal data. Processing includes traditional activities such as collection, recording, organization, storage, modification, analysis, structuring, and deletion or erasure. Critically, the definition extends to less obvious activities: reading or consulting data constitutes processing, as does data sharing and dissemination through transmission to other parties. For health AI systems, this broad definition has significant implications: training a machine learning model on health data constitutes processing, meaning GDPR obligations arise from the moment data gathering begins, not only when the model is deployed.

### Seven GDPR Principles (Article 5)

#### 1. Lawfulness, Fairness, and Transparency (Article 5(1)(a))

Processing must satisfy three requirements working together. First, it must be lawful—supported by a valid legal basis that will be examined below. Second, it must be fair to the data subject, avoiding deceptive or exploitative practices. Third, it must be transparent, with data subjects fully informed about how their data is used. For health data processing, these requirements demand that organizations ensure they have proper authorization to use the data, respect applicable licenses and intellectual property restrictions, provide data subjects with accessible and understandable privacy notices, and avoid misleading individuals about data handling practices.

#### 2. Purpose Limitation (Article 5(1)(b))

A critical principle underlying GDPR is that data must be collected for specified, explicit, and legitimate purposes. Organizations cannot collect data "just in case" or for purposes not yet determined. Using data for different, incompatible purposes than those for which it was collected is prohibited without establishing an additional legal basis for the secondary purpose. This principle becomes particularly important in health data contexts. Patient data collected for direct clinical care cannot automatically be used for AI training without either demonstrating that the secondary purpose is compatible with the original clinical purpose, or establishing a new legal basis for the research use. For instance, if data was collected from patients with explicit understanding it would be used only for their individual care, repurposing that data for population-level AI model training may require either patient consent or application of research exemptions under Article 89 of the regulation.

#### 3. Data Minimization (Article 5(1)(c))

The data minimization principle requires that only data strictly necessary for each specific purpose be collected. Organizations must actively resist over-collection and eliminate unnecessary attributes. For health AI development, this means including only those attributes truly essential for the model's stated purpose. If the objective is predicting diabetes risk, the patient's name may be unnecessary after data anonymization. Applying data minimization rigorously protects individuals by limiting exposure of sensitive information to data holders and reducing the potential for mission creep where data originally collected for narrow purposes expands to broader uses.

#### 4. Accuracy (Article 5(1)(d))

Personal data must be maintained in correct and accurate form. When demonstrable errors are discovered, they must be rectified or the inaccurate data erased. This principle reflects the practical reality that inaccurate data propagates errors through downstream processes. For health data systems, accuracy becomes particularly critical because inaccurate training data propagates errors through machine learning models, potentially affecting clinical decision-support systems or research conclusions. Health data governance frameworks must establish mechanisms to identify and correct data quality issues before inaccurate information causes harm.

#### 5. Storage Limitation (Article 5(1)(e))

Personal data must be retained in identifiable form only for as long as necessary to fulfill the purposes for which it was collected. Once clinical purposes are fulfilled, original records should be securely deleted or anonymized where legally possible. This principle acknowledges that indefinite retention of identifiable data creates ongoing privacy risks even when the data is no longer needed. For health data systems, this means establishing clear retention policies that balance the competing obligations of clinical governance—which may require retention of original records for specified periods—with privacy protection principles requiring eventual deletion or anonymization of historical data.

#### 6. Integrity and Confidentiality (Article 5(1)(f))

Data must be processed with appropriate security measures that provide protection against unauthorized or unlawful processing as well as accidental loss, destruction, or damage. Implementing integrity and confidentiality requires deploying both technical and organizational measures. Technical measures include encryption of data both in transit and at rest, implementation of access controls limiting data access to authorized personnel, and deployment of intrusion detection systems to identify attempted unauthorized access. Organizational measures include comprehensive staff training on data security procedures, establishment of security policies, and development of incident response procedures for addressing breaches when they occur. Personnel security measures, including background checks for staff with data access, form a critical component of this principle.

#### 7. Accountability (Article 5(2))

Data controllers bear the fundamental responsibility for demonstrating compliance with all seven principles. This accountability principle shifts the burden of proof; organizations cannot simply claim they are compliant but must affirmatively demonstrate compliance through maintained documentation. Accountability requires maintaining detailed Records of Processing Activities documenting all processing operations. When required by risk assessment, organizations must conduct Data Protection Impact Assessments to systematically evaluate privacy risks. Compliance must be monitored through regular audits and reviews. When data breaches occur, organizations must document incidents and report them to supervisory authorities as specified in Article 33. This principle emphasizes that good faith intentions are insufficient; compliance requires systematic documentation and governance mechanisms demonstrating adherence to all other principles.

### Legal Basis for Processing (Article 6)

Processing is only lawful when a valid legal basis exists. The GDPR provides six alternative bases, and organizations must identify at least one applicable basis before processing can commence. Understanding these bases is essential because the presence of data does not create the legal right to use it; permission depends on satisfying one of these six categories.

**Consent (Article 6(1)(a))** requires that the data subject has freely given, specific, informed, and unambiguous consent to processing. For special categories of data including health information, consent must be explicitly given—merely informed consent is insufficient. A critical protection is that consent can be withdrawn at any time. However, consent becomes invalid if there is an imbalance of power between the data subject and controller, or if consent is presented as a precondition for accessing unrelated services.

**Contract (Article 6(1)(b))** permits processing when necessary to perform a contract to which the data subject is a party or to prepare to enter into a contract. This basis has limited applicability in healthcare contexts because healthcare delivery is typically governed by legal obligations rather than commercial contracts.

**Legal Obligation (Article 6(1)(c))** permits processing when EU or national law requires it. This basis is most commonly used for health data in healthcare delivery contexts. Medical record retention requirements imposed by law are prime examples of processing justified by legal obligation.

**Vital Interests (Article 6(1)(d))** permits processing when necessary to protect the vital interests—life or health—of the data subject or another person. This basis is rarely invoked in health research contexts but might apply in emergency situations where immediate processing is necessary to save lives.

**Public Task (Article 6(1)(e))** permits processing when necessary for a task carried out in the public interest or when performing an official authority function. This basis is commonly used by public health authorities establishing disease registries or conducting surveillance. It requires explicit legal authorization for the specific public task.

**Legitimate Interest (Article 6(1)(f))** permits processing when necessary for legitimate interests pursued by the controller or a third party, except where such interests are overridden by the data subject's rights and freedoms. This basis requires conducting a Legitimate Interest Assessment balancing the controller's legitimate interests, the data subject's reasonable expectations, potential impacts on data subjects, and available safeguards.

For health AI development in particular, both Legitimate Interest and Consent commonly serve as legal bases for training on health datasets, though the analysis differs depending on context and safeguards available.

### Special Categories of Personal Data (Article 9)

#### Prohibited Categories

Article 9(1) establishes heightened protection for eight special categories of personal data: racial or ethnic origin, political opinions, religious or philosophical beliefs, trade union membership, genetic data, biometric data for identification purposes, health data, and sex life or sexual orientation data. These categories receive heightened protection because they are particularly sensitive and carry high potential for discrimination. Health data, most relevant for healthcare organizations and researchers, comprises one of these eight protected categories.

#### Lawful Exceptions (Article 9(2))

Processing special categories is generally prohibited, but the regulation provides specific exceptions where processing becomes lawful. Explicit consent by the data subject constitutes one exception, though it differs from the standard consent requirement by requiring explicit rather than merely informed agreement. Employment and social security law obligations may permit processing without consent when required by law. If a data subject manifestly makes their special category data public, processing that publicly declared information becomes lawful. Health and occupational medicine represent important exceptions for healthcare contexts. Organizations can process special category health data when purposes involve health and occupational medicine under appropriate safeguards. Processing is permitted where protecting health interests or managing health and safety at work is the objective. Scientists can process special category data for scientific research purposes "subject to suitable safeguards," creating flexibility for research institutions. Public interest reasons can justify processing when based on EU or national law and accompanied by appropriate safeguards for fundamental rights. The research exception under Article 9(2)(j) is particularly important for health data, allowing relaxation of purpose and storage limitation principles where necessary for research aims while permitting derogations from certain data subject rights where necessary to preserve research validity.

---

## 5. Data Governance Act (DGA) {#dga}

**Regulation (EU) 2022/868** establishes governance rules for European data spaces and incentivizes data sharing while protecting data subjects.

### Scope and Objectives

The DGA serves three primary functions relevant to health data:

1. **Facilitate reuse of public sector data** (Chapter 2)
2. **Establish rules for data intermediation services** (Chapter 3)
3. **Create framework for data altruism** (Chapter 4)

### Chapter 2: Reuse of Public Sector Data

#### Types of Data Subject to Reuse (Article 3)

Designated categories of public sector data that must be made available for reuse:
- High-value datasets (health surveillance data, mortality registries)
- Documents held by public bodies
- Exception: Data excluded for public interest, confidentiality, or third-party rights

#### Important Limitation (Article 1(2))

**No obligation on public sector bodies to allow reuse of data**. Member States decide which datasets to make available, but where they do, must follow DGA rules.

#### Conditions for Reuse (Article 5)

- **Non-discriminatory**: Equal treatment of different users
- **Fair pricing**: Fees limited to marginal cost of data provision
- **Transparent**: Clear information on terms and conditions
- **Machine-readable format**: Data provided in open, structured formats

### Chapter 3: Data Intermediation Services

#### Definition (Article 11)

"Data intermediation service" means a service establishing **commercial relationships for data sharing** between:
- Undetermined number of data subjects and data holders, AND
- Data users

Through technical, legal, or other means, including enabling exercise of data subject rights.

#### Scope in Healthcare

Data intermediaries can facilitate:
- Health data holders (hospitals, clinics) sharing data with researchers
- Individual patients exercising portability rights through intermediary platforms
- Aggregation of dispersed health datasets

---

## 6. Data Act (DA) {#data-act}

**Regulation (EU) 2023/2854** establishes rules for fair access to and use of data, particularly IoT and machine-generated data.

### Applicability to Health Data

### Applicability to Health Data

While the Data Act focuses primarily on business-to-consumer and business-to-business data sharing from connected products and Internet of Things devices, its foundational principles have significantly influenced the design of the EHDS framework. Understanding these principles helps contextualize the governance model adopted for health data.

The Data Act establishes that users of connected products have a **right to access their data**. Connected products must enable users to easily, securely, and comprehensively access their data directly in machine-readable formats, free of charge, and without undue barriers. Beyond mere access, the regulation imposes **transparency obligations** requiring data holders to make data readily available with relevant metadata enabling proper interpretation and use of that data. Responses must come with no undue delay.

When users request third-party access to their data, the Data Act requires making data available to third parties upon request. These requirements include safeguards preventing gatekeeper abuse and restrictions preventing data holders from using their data control to develop competing products using insights from their position. The regulation also establishes principles for **fair compensation**, requiring fair, reasonable, and non-discriminatory arrangements where compensation is provided and ensuring that data holders receive compensation proportionate to costs incurred.

The Data Act's Chapter 5 extends these principles to business-to-government contexts, permitting public sector bodies to request data from private data holders during **exceptional circumstances**, including public health emergencies. This mechanism differs from the EHDS secondary use framework, which does not impose an "exceptional need" limitation on research and policy uses of health data. Instead, EHDS creates a more permissive environment for secondary uses by establishing systematic access mechanisms rather than requiring emergency justifications.

---

## 7. European Health Data Space (EHDS) Regulation {#ehds}

**Regulation (EU) 2025/327** (adopted 11 February 2025, published 5 March 2025) establishes harmonized rules for health data access and use across the EU. This is the flagship regulation for health data governance.

### Fundamental Objectives

The EHDS pursues four interconnected fundamental objectives outlined in Article 1 and elaborated in the regulation's preamble. First, the regulation aims to improve natural persons' access to and control over their personal electronic health data within healthcare contexts. This objective reflects fundamental rights principles by empowering individuals as data subjects rather than treating them as passive data holders. Second, EHDS seeks to better enable purposes that benefit society through health data use, encompassing research and innovation, policy-making and education, health threat preparedness and response including pandemic prevention, patient safety enhancements, personalized medicine development, official statistics generation, and regulatory activities. These broadly articulated purposes reflect recognition that health data creates value far beyond individual clinical care.

The third objective addresses internal market functioning by establishing uniform legal and technical frameworks for electronic health record systems across Member States. By creating harmonized standards and interoperability requirements, EHDS removes technical and regulatory barriers that fragmented national systems create. This harmonization enables cross-border data flows, supporting healthcare provider mobility and patient portability while reducing implementation costs for organizations operating across multiple jurisdictions. Finally, EHDS serves as a key element of a strong, resilient European Health Union, reflecting recognition that health security and health system performance are matters of strategic EU importance requiring coordinated action across Member States rather than isolated national responses.

### Key Definitions

#### Electronic Health Data (Recital 6)

The regulation defines electronic health data expansively to encompass multiple categories. It includes personal data related to the physical or mental health of natural persons and data on the provision of healthcare services. Genetic information—inherited or acquired genetic characteristics—comprises part of electronic health data. The definition captures data on health determinants including behavioral factors, environmental and physical influences, medical care elements, and social and educational factors affecting health. Significantly, electronic health data encompasses data initially collected for research, statistical, health threat assessment, policy-making, or regulatory purposes, not merely data collected for individual clinical care. This broad scope means that research datasets, public health surveillance systems, and regulatory data systems all constitute electronic health data subject to EHDS rules. The definition includes inferred and derived data such as diagnostics, tests, and medical examinations—data generated through processing or analysis rather than directly observed. Finally, data observed and recorded by automated means—such as continuous glucose monitors, fitness tracking devices, or telemedicine systems—qualify as electronic health data.

#### Electronic Health Records (EHR) (Recital 7)

Electronic health records typically contain comprehensive patient information including medical history, diagnoses, and treatment records. They document medications, allergies, and vaccination status. Radiology images, laboratory results, and other diagnostic materials form components of typical EHRs. Importantly, EHRs frequently contain medical data spread across multiple healthcare system actors—general practitioners, hospitals, pharmacies, and care services—rather than consolidated in single systems. This distributed nature reflects how modern healthcare actually operates, with patients receiving care from multiple providers who maintain separate records.

### GDPR Relationship (Recital 5, Article 1(5))

The EHDS does not operate in isolation from existing data protection frameworks but rather exists within the broader GDPR ecosystem. The General Data Protection Regulation applies fully to all processing activities governed by EHDS, providing a foundational layer of protection. EHDS complements and extends GDPR rights where appropriate for the health sector context, creating additional protections beyond what GDPR provides. Critically, EHDS does not reduce GDPR protections—it only adds health-sector-specific rights and governance mechanisms. This means organizations implementing EHDS must comply with both frameworks simultaneously, using GDPR's principles and requirements as a baseline and adding EHDS-specific requirements on top.

---

## 8. EHDS: Primary Use of Health Data {#ehds-primary}

Primary use refers to **processing of health data for provision of healthcare to individuals** (Article 2(2)(d)).

### Patient Rights for Primary Use

The EHDS establishes several complementary rights beyond GDPR, tailored to health context:

#### Right to Immediate Access (Article 9, complementing GDPR Article 15)

- Natural persons have right to **immediate, free-of-charge access** to specific priority categories of their personal electronic health data
- Exercised through **electronic health data access services** (not individual controllers)
- **Technological practicability** caveat noted

**Contrast with GDPR Article 15**:
- GDPR grants access within one month
- EHDS grants immediate access but limited to priority categories
- EHDS exercised via service, not individual controller

#### Priority Categories of Health Data (Article 14)

Prioritized for exchange and access:

1. **Patient Summaries** — core clinical information
2. **Electronic Prescriptions and Dispensations** — medication history
3. **Medical Imaging Studies and Related Reports** — diagnostic images and interpretations
4. **Medical Test Results** — laboratory and diagnostic results
5. **Discharge Reports** — hospital episode summaries

Additional categories may be added per Article 25.

#### Right to Add Information (Article 5)

Natural persons can add health data to their EHRs or store in separate personal health records accessible to health professionals.

**Important caveat**: Data added by patients must be **clearly distinguishable** from professional data and lacks same clinical/legal value.

#### Right to Request Rectification (Article 6)

- Natural persons can request **online, immediate, free-of-charge rectification** of incorrect data through electronic health data access service
- Healthcare provider remains responsible for assessing rectification requests under GDPR Article 16

#### Enhanced Right to Data Portability (Article 7-8, complementing GDPR Article 20)

**GDPR Article 20** limits portability to:
- Data based on consent or contract
- Data provided by data subject
- Direct transmission only where technically feasible

**EHDS extends this**:
- Applies to priority categories regardless of legal basis
- Transmittable in **European electronic health record exchange format**
- Health professionals must not hinder use of cross-border data in interoperable format
- Natural persons can download or request transmission to third party (e.g., healthcare provider in another MS)

#### Right to Restrict Access (Article 10)

- Natural persons can **set restrictions** on access to parts of their health data
- Granular control possible (e.g., restrict specific sensitive categories)
- Restrictions apply uniformly within Member State and cross-border

**Important caveat**: 
- Must be informed of patient safety risks from restricted data
- Emergency access possible where vital interests at risk
- Data subject assumes responsibility for restricted data impacting care quality

#### Right to Opt-Out from Cross-Border Access (Article 9(2), Article 18)

Member States **may** provide absolute right to opt out from access by anyone other than original healthcare provider.

- No data made available through EHDS services other than to original provider
- Healthcare provider must still maintain records
- Reversible decision

### Infrastructure for Primary Use

#### Electronic Health Data Access Services (Article 4)

Member States must establish one or more electronic health data access services:
- National, regional, or local level
- Provided by healthcare providers, national authorities, or third parties
- Form: Online patient portal, mobile app, or other means
- Design: Accessible to persons with disabilities
- Legal basis: Article 6(1)(e) and Article 9(2)(g) GDPR (public task)

#### Health Professional Access Services (Article 12)

- Member States must establish services enabling health professionals to access patient data
- Legal basis: Article 6(1)(e) GDPR (public task) and Article 9(2)(h) (healthcare provision)
- **Data minimization required**: Health professionals access only data necessary for specific care episode
- **Logging and transparency**: Detailed records of who accessed what data when

#### Proxy Services (Article 13-14)

- Enable natural persons to authorize others (family, relatives, guardians) to access or manage their health data
- Must accommodate minors and dependent persons
- Should align with eIDAS Regulation for interoperability
- Member States can establish safeguards to protect minors' interests

#### European Electronic Health Record Exchange Format (Article 15-16)

- Common format for transmitting health data across EU
- Based on **Commission Recommendation (EU) 2019/243**
- Enables translation into EU official languages (where possible)
- Used for both national and cross-border exchange
- Subject to quality and security requirements

#### MyHealth@EU Infrastructure (Article 23-24)

- **Mandatory cross-border infrastructure** for primary use
- Enables natural persons to share health data when accessing healthcare in other Member States
- **Member State participation mandatory** (was previously voluntary)
- Commission acts as processor on behalf of Member States
- **Significant funding implications** for MS implementation

#### Digital Health Authorities (Article 2)

- Member States must designate relevant digital health authorities
- Responsible for planning and implementing standards
- Separate organizations or existing bodies
- Staff must be independent with no financial conflicts of interest
- Cooperate with DPAs, eID supervisory bodies, AI Board, Medical Device Coordination Group

### Protection of Fundamental Rights in Primary Use

#### Restrictions on Access to Sensitive Categories (Article 17-18)

Similar to GDPR Article 23, Member States can restrict EHDS access where:
- Necessary and proportionate in democratic society
- Examples: Delaying urgent health information until patient can be counseled by physician

#### Patient Safety Considerations (Article 10, Recital 17)

- Patient must be informed of risks that access restrictions could harm care quality
- Patient assumes responsibility for consequences of restrictions
- Emergency override possible where vital interests at risk

#### Enforcement and Data Protection Rights (Article 40-42)

- **Data Protection Authorities** enforce EHDS rights
- Must have adequate financial and human resources
- Competent to impose administrative fines
- Denmark exception: Fines imposed as criminal penalty by courts instead

---

## 9. EHDS: Secondary Use of Health Data {#ehds-secondary}

Secondary use refers to **processing of health data for purposes other than initial purposes for which collected or produced** (Article 2(2)(e)). Permitted purposes:

- Research and innovation
- Policy-making and education
- Patient safety and personalised medicine
- Regulatory activities

### Legal Framework for Secondary Use

#### Legal Basis (Recital 52)

Secondary use of health data must rest on one of four legal bases from GDPR Article 6. Consent by the data subject constitutes one available basis. Legal Obligation—created by the EHDS itself—provides another basis, reflecting that the regulation imposes affirmative obligations on data holders to make data available. Public Task provision applies when health data access bodies manage access and perform their regulatory functions. Legitimate Interest constitutes the fourth basis, applicable when the balancing of interests favors data use.

Processing special categories of personal data, including health data, must additionally satisfy requirements under GDPR Article 9(2). Health data specifically qualifies for protection under paragraphs 9(2)(g-j) concerning scientific research, meaning organizations can invoke research exemptions that relax certain GDPR requirements while maintaining appropriate safeguards.

#### Permitted Categories of Health Data for Secondary Use (Article 51)

The regulation establishes broadly permissive categories of health data available for secondary use. Electronic health records data from clinical encounters comprise the primary category. Claims data from insurance and reimbursement systems provide economic and utilization perspectives. Dispensation data from pharmacy systems document medication use patterns. Disease registries focusing on specific conditions offer rich longitudinal information. Genomic data—specifically mentioned in the regulation—reflects recognition of the importance of genetic information for research. Automatically generated data from medical devices provides real-world clinical information. Person-generated data from wellness applications and patient-reported outcomes capture patient perspectives. Clinical trials and clinical investigations data offer controlled research evidence. Environmental and socioeconomic health determinants capture social factors affecting health. Automatically recorded data from various sources rounds out the permissible categories, reflecting a recognition that useful health information exists in diverse formats and sources.

#### Prohibited Uses (Article 62)

The EHDS regulation establishes strict prohibitions on certain uses of health data for secondary purposes. Uses that would be detrimental to natural persons are strictly prohibited, including measures that increase insurance premiums, determine employment decisions or pension amounts, or affect banking and mortgage decisions. Marketing of products or treatments using health data is prohibited. Automated individual decision-making affecting a person's legal situation is not permitted. Health data users must not attempt to re-identify natural persons even when working with pseudonymized data. Development of harmful products using health data is prohibited. Activities contrary to ethical provisions under national law are not permitted (though important exceptions exist for consent and opt-out situations where EHDS takes precedence over conflicting ethical provisions). Sharing data with unauthorized third parties violates the secondary use framework.

### Key Administrative Actors

#### Health Data Holders (Article 60)

Health data holders encompass diverse entities that hold health data for secondary use purposes. Healthcare providers such as hospitals, clinics, and general practitioner offices constitute primary examples, as do specialized care providers. Research entities operating in health and care sectors qualify as data holders. Organizations developing products and services for health and care contexts, including wellness application developers, fall within this category. Both public and private entities can serve as data holders, as can not-for-profit organizations. The regulation exempts natural persons and microenterprises from data holder obligations, unless Member States choose to extend obligations to these smaller actors.

A critical requirement introduced by EHDS: data holders must make their health data available for secondary use through the permit system. This obligation represents a significant shift in governance, transforming data holders from entities with discretionary control over data into regulated actors with affirmative obligations to facilitate secondary use.

#### Health Data Access Bodies (HDAB) (Article 36, 59-68)

Central governance entities at Member State level:

- At least one per Member State
- Can be dedicated organization or unit in existing body
- Designated **Digital Health Authority** oversees oversight
- When multiple bodies exist, one designated as **coordinator**

**Key responsibilities**:

1. **Decision-making on data access applications** (Article 67-68)
2. **Issuance of data permits** specifying conditions and limitations
3. **Enforcement** of secondary use rules
4. **Transparency**: Publish data permits and justifications
5. **Support to data holders**: Assist with data provision, quality assurance
6. **Cooperation**: With other HDABs, supervisory authorities, stakeholders

**Independence**: Members and staff must avoid conflicts of interest and incompatible occupations.

**Resources**: Must receive adequate financial, technical, and human resources for effective performance.

#### Health Data Users (Article 61)

Entities accessing data for secondary use:

- Public or private entities
- Not-for-profit organizations
- Individual researchers
- Public sector bodies
- Private companies and innovators
- Academic institutions

**Must demonstrate**: Valid legal basis under GDPR Article 6 and compliance with EHDS requirements.

### Right to Opt-Out (Article 54)

#### General Opt-Out Right

Natural persons can exercise **right to opt-out** from having their personal electronic health data made available for secondary use.

- **Simple and reversible mechanism** must be provided
- No reasons required
- Can be exercised at any time
- Users must be informed of **benefits and drawbacks** of opting out

#### Override Possibilities (Article 54(2))

For **strong public interest purposes only**, Member States can provide mechanism to override opt-out where:

1. **Public interest purposes**:
   - Protection against serious cross-border health threats
   - Scientific research for **important reasons of public interest** (e.g., rare diseases, emerging health threats)

2. **Restrictive conditions**:
   - Only for **public sector bodies** or Union institutions with public health mandate
   - Data cannot be obtained by alternative means in timely and effective way
   - Necessary and proportionate in democratic society
   - Justification required for each individual application

3. **Safeguards maintained**:
   - Prohibition on re-identification strictly enforced
   - Processing in secure processing environment
   - Other safeguards under Chapter IV continue

#### Transparency on Opt-Out

- **Information requirement**: Natural persons must be fully informed of right to opt-out
- **Accessibility**: Mechanism must be easily understandable and accessible
- **Tracking**: Health data access bodies must maintain records of opt-outs

### Data Quality and Utility

#### Data Minimization (Article 72)

Core principle: **Use least sensitive data format possible**

1. **Non-personal data preferred**: When sufficient for purpose, use anonymized/non-personal data
2. **Pseudonymization required**: When personal data necessary, must be pseudonymized as early as possible
3. **Justification**: Health data user must justify why personal data needed
4. **HDAB assessment**: Body assesses whether justification valid

#### Anonymization and Pseudonymization (Article 72)

When pseudonymization or anonymization is employed, it must use state-of-the-art techniques designed to make re-identification as difficult as possible. Either the health data access body or the original data holder can perform this technical work. However, the regulation acknowledges a realistic constraint: for rare diseases and certain sensitive data categories, some residual re-identification risk may remain despite best efforts, meaning perfect anonymization cannot always be guaranteed. This acknowledgment reflects recognition that truly rare populations of patients may be re-identifiable even after sophisticated anonymization techniques.

#### Re-identification Prohibition (Article 72)

A strict prohibition forbids health data users from attempting to re-identify natural persons, even when working with data presented in pseudonymized or anonymized form. Violation of this prohibition carries serious consequences, including both criminal penalties possible under national law and administrative fines under the EHDS framework itself. This prohibition reflects recognition that the most significant privacy risk in secondary use contexts comes not from the data holder's actions but from sophisticated attempts by researchers or malicious actors to reverse anonymization.

#### Data Quality and Utility Framework (Article 85-87)

The EHDS establishes mechanisms to address a critical challenge in health data use: researchers often lack information about the quality, completeness, and limitations of available datasets. To address this, the regulation introduces a Data Quality and Utility Label—a standardized label indicating dataset quality characteristics that enables informed decision-making by researchers about which datasets suit their purposes. An EU Dataset Catalogue functions as a central registry of available datasets with quality information, complemented by National Dataset Catalogues maintained at the Member State level and linked to the central catalogue. This distributed catalogue approach minimizes burden on individual data holders while maintaining searchability and discoverability. The regulation establishes Minimum Data Fields to be specified through implementing acts, creating harmonized datasets that facilitate comparison and aggregation across sources. Disease-specific harmonized templates for structured data further promote data quality and utility by establishing common coding standards and data structures.

### Data Permit System (Article 67-68)

#### Health Data Access Application (Article 67)

Researchers seeking to access health data for secondary use must submit applications containing essential information. The application must describe the intended purpose and proposed use of the data. It must identify the principal investigator responsible for the project. It must provide justification for whether the research requires personal data or whether anonymized or pseudonymized data would suffice. Researchers specify the data categories they require. They must explain the duration of the research project and arrangements for data storage. Critically, applicants must provide a declaration that their intended use does not pose risk of stigmatization or harm to dignity of data subjects. Where national law requires, an ethical assessment or research ethics review must accompany the application.

#### Data Permit Issuance (Article 68)

Health data access bodies issue data permits only when all specified conditions are satisfied. They must verify that all conditions established under Chapter IV of the regulation are met. They must confirm that the proposed purpose falls within permitted categories under Articles 53-54. They must ensure applicants have demonstrated a valid legal basis under GDPR Article 6. Where required, they must verify that risk assessments or ethical reviews have been completed. They must satisfy themselves that appropriate safeguards exist to protect data and respect fundamental rights.

The data permit itself must specify several critical elements including which data categories are authorized for access, who is authorized to use the data (the principal investigator and named team members), the research purpose and authorized duration, any specific conditions or limitations on use, requirements for secure processing environments, explicit re-identification prohibitions, and conditions for any potential re-use or extension of the permit.

#### Timeline for Decisions

The EHDS establishes decision timelines to prevent indefinite delays that would hinder research. Standard procedures provide for data permits to be issued within timelines to be specified through implementing acts, providing certainty while allowing flexibility in the regulations. Accelerated procedures serve Union institutions with public health mandates, allowing them to receive expedited decisions ordinarily within two months, with an additional month permitted for particularly complex cases. This expedited track recognizes that public health emergencies sometimes require rapid access to data. Permits can be extended (for instance, when researchers need additional time for publication review), subject to amendment and potentially additional fees, allowing flexibility as research evolves.

When applications are refused, health data access bodies must provide clear justification, but rejection does not preclude resubmission of new applications, allowing researchers to reframe proposals or provide additional information addressing the body's concerns.

### Secure Processing Environments (Article 73, 77)

#### Definition and Purpose

Secure processing environments constitute controlled, isolated computing environments where researchers can access pseudonymized or anonymized health data while technical and security safeguards prevent unauthorized access or data extraction. These environments embody a "questions to data, not data to questions" principle—rather than downloading raw data for external analysis, researchers pose analytical questions and receive only aggregated, anonymized results. Data remains under the physical and logical control of the health data access body or data holder, preventing removal from secure environments.

#### Key Requirements

Secure processing environments must meet state-of-the-art security standards providing multiple layers of protection. A critical requirement prohibits download of personal data from the environment; only aggregated and anonymized results can be extracted and made available to researchers. The health data access body or data holder retains continuous control over data access and removal, enabling them to revoke access if violations occur. The environments must comply with GDPR requirements including processor obligations under Article 28, whether operated directly or delegated to third-party processors. Comprehensive logging and audit capabilities enable tracking of all data access and analysis activities. Member States and health data access bodies provide access to secure processing environments, though the Commission can establish union-level environments for multi-national analysis requiring coordination. Technical specifications for environments are established through implementing acts. Critically, data minimization principles persist even within secure environments; users access only data necessary for their specific research question.

### Secondary Use Infrastructure: HealthData@EU (Article 80-84)

#### Purpose and Architecture

- **Cross-border infrastructure** for secondary use
- Accelerates access while ensuring privacy
- Enables linking health data with other sectoral data spaces
- Principles: Privacy by design, privacy by default

#### Participants

- **National contact points for secondary use**: Organizational gateways from each MS
- **Authorized participants**:
  - Research infrastructures (ERIC, EDIC)
  - European research infrastructures (ESFRI)
  - EOSC-federated infrastructures
  - Third countries (with compliance checks)
  - International organizations

#### Commission Services

Commission provides and manages:

- Support for cross-border data access request handling
- Maintenance of catalogues of available datasets
- Network discoverability and metadata queries
- Connectivity services
- Compliance services
- Potential secure processing environment for multi-national analysis

#### Data Transfer Instruments

- Third-country connections require appropriate **Chapter V GDPR transfer instruments** (adequacy decisions, standard contractual clauses)
- Reciprocity principle applies: Third countries must allow equivalent access by EU entities

#### Single Application Principle (Article 83)

- Health data users can submit single application for data from multiple Member States
- Reduces burden and barriers
- Enhances cross-border research

### Trusted Health Data Holders (Article 76)

#### Concept

Member States can designate **trusted health data holders** for simplified data permit procedures:

- Large repositories with high-quality datasets
- Demonstrated expertise in data provision
- Meet security and ethical standards

#### Simplified Procedure

- Trusted holder can **assess applications** based on expertise
- Issues **recommendation** to HDAB (not binding decision)
- HDAB retains final decision authority
- Reduces administrative burden on HDAB

#### Limitations

- Health data intermediation entities cannot be designated as trusted holders

### Fees and Cost Recovery (Article 69-70)

#### Principles

- Health data holders can charge **proportionate, justified, transparent fees**
- Fees reflect costs of making data available
- Public sector bodies: Fees cannot include cost of initial data collection
- **SMEs, individual researchers, public bodies**: May receive reduced fees

#### Consistency Framework

- HDAB charges fees for its operations
- HDAB can charge additional fees for health data holder costs
- Single invoice to user (HDAB collects and transfers to holder)
- Implementing acts establish harmonized fee framework
- **Article 10 of DGA** principles apply

#### Fairness Obligation

Health data holders must:

- Not withhold data unjustifiably
- Not impose unjustified fees deterring access
- Not require co-publication as condition
- Consider ethical approval separately from data access

### Enforcement and Penalties (Article 71, 103-106)

Violations of EHDS secondary use requirements carry multiple enforcement mechanisms. Administrative fines apply to serious infringements including re-identification of natural persons, downloading personal data outside secure processing environments, processing health data for prohibited uses, or using data not covered by a valid data permit. When determining fine amounts, health data access bodies assess them proportionately based on the nature, gravity, and duration of the infringement, the consequences of violations, compliance measures the violator had taken, and any mitigating factors.

Non-compliant health data users face temporary or permanent exclusion from EHDS access, creating significant business consequences for organizations that violate rules. Similarly, non-compliant health data holders face enforcement measures, potentially losing their status as authorized data providers.

All relevant parties—health data access bodies, data holders, data users, and health professionals—bear liability for damages resulting from infringements. The regulation interprets damage broadly, extending beyond economic losses to encompass damage to fundamental rights. Member States establish proportionate and dissuasive penalties for violations, with re-identification receiving particularly serious treatment as an especially grave breach.

### Transparency and Accountability (Article 81-82, 86)

The EHDS establishes comprehensive transparency and accountability mechanisms designed to enable public oversight and evidence-based governance of health data use. Health data access bodies publish activity reports every two years documenting the overview of data permit decisions, audit findings, stakeholder engagement activities, and the outcomes of secondary use research including links to publications generated from permitted data. This reporting creates accountability and enables stakeholders to understand how their health data is being used.

Organizations must provide dataset transparency information on data permits granted with justifications for permission decisions, measures protecting natural persons' rights, methods for individuals to exercise their rights, and outcomes of research conducted with permitted data (including lay summaries making results accessible to non-technical audiences). These transparency obligations complement but do not replace GDPR Article 14 requirements for information provision.

Where health data users make significant health findings about natural persons during their research, regulations require that data holders inform those persons of the findings. Individuals retain the ability to opt out of receiving such notifications. Member States can delay notification for patient safety or ethics reasons when immediate notification might cause harm.

The EU Dataset Catalogue serves as a user-friendly, accessible, cost-effective central registry connecting national catalogues operated by Member States, avoiding redundant registration while improving discoverability. The catalogue can align with existing data.europa.eu initiatives and maintain interoperability with research infrastructure catalogues, creating a federated discovery infrastructure.

### Governance: European Health Data Space Board (Article 95-98)

#### Composition and Role

The EHDS Board brings together digital health authorities and health data access bodies from all Member States under commission co-chairing, creating a central coordination mechanism for consistent application of the regulation across the Union. The Board can establish subgroups focused on specific topics including primary use, secondary use, and other governance issues, allowing specialization while maintaining overall coordination.

#### Tasks

The Board issues written contributions on consistent application of EHDS rules across Member States, coordinating how different national implementations approach similar situations. It coordinates Member State use of health data, ensuring that national policies complement rather than conflict with each other. It shares information on risks, incidents, and emerging challenges in health data governance, enabling collective learning and early warning of systematic problems. The Board operates independently in the public interest, with governance arrangements ensuring it remains focused on health system outcomes rather than narrow political considerations.

#### Stakeholder Forum (Article 97)

An advisory stakeholder forum composed of patient and consumer organizations, health professionals, industry representatives, scientific researchers, and academia ensures diverse perspectives inform the Board's decision-making. The composition is deliberately balanced to represent competing interests and ensure that the Board considers perspectives from affected populations, healthcare workers, commercial innovators, and scientific experts.

#### Steering Groups (Article 98)

Member State representative committees at operational levels handle day-to-day management decisions and technical infrastructure development, allowing practical governance to proceed efficiently without requiring full Board involvement in all matters. These groups can invite observers and expert consultants as needed to address specific technical or policy questions.

---

## 10. Implementation Roadmap and Timeline {#implementation}

### Entry into Force and Application Timeline

#### Key Dates

- **5 March 2025**: Regulation published in Official Journal
- **26 March 2025**: Regulation enters into force (transition period begins)
- **26 March 2027**: Regulation applies generally (main application date)

#### Gradual Implementation Phases (Recital 115, Articles 103-109)

##### **2025-2027: Transition Period**

- Commission adopts implementing acts
- Member States prepare infrastructure
- Organizations build capacity
- Limited voluntary early implementation possible

##### **2027-2029: Primary Use Phase 1**

- **March 2027**: Legal entry into effect
- **March 2029**: First mandatory exchange of priority category 1 health data
  - Patient Summaries
  - Electronic Prescriptions and Dispensations
- MyHealth@EU becomes mandatory cross-border infrastructure
- EHR system certification begins (1st categories)

##### **2029-2031: Primary Use Phase 2 & Secondary Use Begins**

- **March 2030**: Mandatory exchange of priority category 2 health data
  - Medical imaging studies and reports
  - Medical test results
  - Discharge reports
- **March 2029**: Secondary use begins for most data categories
- **March 2030**: Secondary use includes genomics, omics, wellness applications
- EHR system certification continues (2nd categories)

##### **2031-2036: Secondary Use Expansion & Third Countries**

- **March 2031**: Secondary use rules fully operational
- **March 2032**: All EHR systems require compliance certification
- **March 2034**: Third countries can join HealthData@EU for secondary use

### Implementation Requirements for Member States

#### Primary Use Infrastructure

1. **Electronic Health Data Access Services** (Article 4)
   - Patient portals
   - Mobile applications
   - Other interfaces enabling data access

2. **Health Professional Access Services** (Article 12)
   - Provider access to patient data
   - Logging and audit capabilities

3. **Proxy Services** (Article 13-14)
   - Enable authorization of third parties
   - Integration with eID services

4. **MyHealth@EU Participation** (Article 23-24)
   - Mandatory connection
   - National contact points for digital health
   - Healthcare provider connections

5. **Digital Health Authorities** (Article 30)
   - Designated responsible entity
   - Sufficient technical expertise
   - Cooperation with DPAs, other bodies

#### Secondary Use Infrastructure

1. **Health Data Access Bodies** (Article 59-68)
   - One or more per Member State
   - Sufficient staffing and resources
   - Decision-making capacity

2. **HealthData@EU Connection** (Article 80)
   - National contact points for secondary use
   - Compliance with technical specifications

3. **Secure Processing Environments** (Article 77)
   - Established by HDAB or delegated to third party
   - Meets security standards

4. **Digital Literacy and Training** (Article 89)
   - Health professional training on new systems
   - Natural person support services
   - Targeted programs for vulnerable groups

#### Data Preparation

EHDS imposes several data preparation requirements before implementation can proceed. First, organizations must register health data in electronic format systematically using the established European electronic health record exchange format. This requirement goes beyond simply storing data electronically—it mandates active registration in specified formats enabling interoperability. Specific data quality requirements must be met to ensure data is fit for its intended purposes. Standards and coding systems must be harmonized across organizations to enable meaningful exchange and analysis. These preparation requirements represent substantial work, particularly for healthcare systems using legacy systems not designed for standardized data sharing.

### Key Implementing Acts Needed (Article 105-109)

The regulation delegates significant technical details to implementing acts that the Commission must adopt. For primary use, the Commission must specify proxy service technical specifications, data quality requirements for EHR registration, cross-border identification and authentication requirements, implementation mechanisms for patient data access rights, MyHealth@EU technical specifications and security requirements, and interoperability requirements between MyHealth@EU and other health data systems.

For secondary use, implementing acts must address data permit templates and procedures, requirements for health data access applications, fee policy principles, secure processing environment technical requirements and security standards, HealthData@EU architecture and connection requirements, data quality and utility label specifications, and criteria for designating trusted health data holders.

General implementing acts must establish common specifications for EHR system compliance and certification, detailed specifications of the European electronic health record exchange format, requirements for EHR systems digital testing environments to enable compliance validation, and labelling requirements for wellness applications.

### Estimated Economic Costs

Implementation of EHDS entails substantial costs across multiple categories. Infrastructure development requires significant investment by healthcare systems, national authorities, and technology vendors to establish the connectivity, data systems, and governance mechanisms the regulation requires. Staff training for health professionals, IT personnel, and administrators is essential given the complexity of new systems and procedures. Data preparation activities including digitization of legacy records, standardization to common formats, and quality assurance represent ongoing operational demands. Security enhancement involves investing in cybersecurity infrastructure appropriate to the sensitivity of health data. Ongoing operational costs sustain health data access bodies and health authorities.

Funding mechanisms to support these costs come from diverse sources. EU funding through structural funds, research programs, and digital infrastructure initiatives provides some support. Member State budgets from national healthcare systems provide the primary funding source. User fees charged by health data access bodies for secondary use provide revenue, though the regulation limits these fees to prevent deterring legitimate research. Cost-sharing arrangements aim to distribute the implementation burden fairly between EU-level and Member State-level actors, reflecting the principle that both benefit from coordinated systems.

### Expected Benefits

The EHDS produces estimated economic benefits of approximately €5.5 billion in savings over ten years from improved healthcare delivery alone, alongside 20-30% growth in the digital health market. Secondary use of health data generates estimated €5.4 billion in additional savings over the same period.

Healthcare systems benefit through improved continuity of care for patients accessing healthcare across borders, reducing duplicative testing and administrative burden that currently characterizes fragmented systems. Data availability enables faster diagnosis and treatment by providing clinicians with comprehensive patient histories. Better-informed clinical decisions result from access to complete information. Health system efficiency improvements emerge from standardization and elimination of redundant processes.

Research and innovation receive substantial benefits. Larger datasets drawn from multiple Member States accelerate drug development by providing evidence from more diverse populations than individual national systems could offer. Rare disease research becomes feasible for the first time when aggregating data from small populations across an entire continent. Real-world evidence for regulatory decisions becomes available, complementing traditional randomized trials. Personalized medicine advancement accelerates through access to larger datasets enabling more granular analysis. New digital health products and services emerge as entrepreneurs develop applications leveraging standardized health data infrastructure.

Public health and policy benefit from improved pandemic preparedness as real-time health data enables early warning and rapid response to emerging threats. Evidence-based health policy development improves when policymakers have comprehensive data about health system performance and health outcomes. Patient safety monitoring at population level enables identification of safety signals affecting large numbers of people. Health inequalities reduction becomes possible through data-driven interventions targeting specific populations identified through health data analysis.

---

## 11. Critical Perspectives and Challenges {#challenges}

### Academic and Expert Concerns

#### Patient Control and Consent Issues (Marelli et al., 2023)

Academic experts have raised important concerns that EHDS—as initially proposed—could paradoxically undermine rather than enhance patient control over health data. These concerns focus on several interrelated dimensions. First, transparency may be reduced through lower requirements for individual-level information provision to data subjects and consent waivers for certain secondary uses. The practical effect is that patients may only learn about data processing generally or when they specifically request information, rather than receiving proactive notification of how their data flows through the system. This creates risks that patients remain unaware of processing activities.

Second, informational self-determination becomes diminished when patients cannot determine specifically by whom and for which purposes their data is processed. Control over research participation—including the ability to object on moral grounds to participation in research they find ethically problematic—becomes constrained. This dynamic creates tension with GDPR's foundational principle of informed consent as the basis for personal data protection.

Third, safeguard gaps emerge as large datasets built through EHDS accumulate, increasing re-identification risks and creating opportunities for privacy intrusions. Meanwhile, patients receive reduced opportunities to become informed of these heightened risks. The alignment between health data access bodies and existing oversight structures like ethics review boards and data protection authorities remains unclear, potentially creating gaps in accountability.

Fourth, public trust risks accompany these developments. Research demonstrates that public opinion about health data reuse depends critically on maintaining strong consent requirements and meaningful control mechanisms. Regulatory frameworks appearing to prioritize data access over patient autonomy risk eroding the public trust necessary for voluntary participation in health data systems. If citizens lose confidence that their data will be handled in ways they control and understand, willingness to share health information may decline, potentially undermining the entire EHDS project.

#### Health Professional Burden

Health regulations impose substantial responsibilities on health professionals that carry risks of creating administrative burden affecting care delivery. Healthcare workers must navigate complex obligations regarding data access, transfer, and confidentiality while continuing to provide patient care. Regulations risk placing health professionals in positions where they might violate professional confidentiality duties or other ethical obligations. When patient data crosses borders under EHDS mechanisms, responsibility allocation becomes unclear—does liability rest with the sending provider, the receiving provider, or the infrastructure operator? Insufficient guidance navigating legal uncertainties leaves health professionals exposed to liability when genuine ambiguities arise.

#### Data Quality and Standardization Challenges

Existing data collection practices across EU Member States are heterogeneous, reflecting different healthcare system designs, clinical terminologies, and documentation traditions. Converting this diverse data to common formats is both costly and technically challenging. Data collected from different sources using different definitions proves difficult to combine meaningfully for analysis, potentially reducing the actual utility of aggregated datasets. A persistent problem emerges: even when formal standards are adopted, different organizations often implement them differently, creating apparent standardization that masks underlying semantic differences. This "same standards used differently" phenomenon can propagate errors into research findings using apparently standardized data.

#### Data Quality and Standardization Challenges

- **Semantic heterogeneity**: Same diagnostic codes used differently across healthcare systems with different disease classification traditions, remuneration systems, and registration practices
- **Implementation complexity**: Achieving agreement on data standards among diverse Member States is "monumental challenge"
- **Cost estimates**: Previous experience (EU Clinical Trials Regulation) shows digital infrastructure projects experience massive delays and cost overruns
- **Data usefulness questions**: Shared standards without addressing contextual differences can result in frequent misinterpretations and faulty analyses

#### Infrastructure Investment Risk

- EHDS requires "widespread, technically complex, and massively costly digital infrastructure"
- Previous projects (EU Clinical Trials Regulation) experienced multi-year delays despite significant investment
- Risk of infrastructure "lock-in" and stranded investments

#### Value Extraction and Benefit-Sharing

**Big Tech Involvement**:
- Major technology corporations increasingly entering health research
- EHDS provides few safeguards ensuring returns on public investment
- Example: NHS COVID-19 data partnerships with Google, Amazon, Microsoft, Palantir where companies retained IP rights and profit from NHS data

**Recommended Solutions**:
- Explicit benefit-sharing agreements and licensing requirements
- Ensuring commercial profits derived from public health data flow back to public sector
- Restrictions on IP concentration among private corporations

#### Digital Divide and Health Inequalities

Risk that EHDS **exacerbates existing digital inequalities**:

- Assumes digital literacy and device access among all citizens
- Vulnerable populations (elderly, disadvantaged socioeconomic status, chronic disease sufferers, ethnic minorities) may lack:
  - Digital literacy
  - Device and connectivity access
  - Language skills for cross-border systems
  
**Result**: Those who could most benefit from system improvements potentially excluded.

**Mitigation needed**:
- Targeted digital literacy programs
- Ensure non-digital access alternatives
- Address digital infrastructure gaps in underserved regions

#### Resource and Capacity Issues

- Healthcare systems already stretched for resources
- Significant additional burden to collect, store, standardize, and provide health data
- Additional burden on HDABs to manage secondary use requests
- Training requirements for health professionals, IT personnel
- No guarantee EU or MS funding adequate to support implementation

### Regulatory Coordination Challenges

#### Interaction with GDPR

- **Reduced consent requirements in EHDS** appear inconsistent with GDPR's emphasis on informed consent
- **Scope of scientific research exception**: GDPR Article 9(2)(j) allows relaxation of rights where research aims might be "hampered"; EHDS takes different approach with broader default access to data

#### Interaction with Data Act

- **Different regime for B2G data sharing**: Data Act Chapter 5 limited to "exceptional need" while EHDS provides broader secondary use access
- **Reciprocity requirements**: Data Act Article 10 and EHDS both include reciprocity principles but with potentially different applications

#### Interaction with DGA

- **Data intermediation services**: Overlap between DGA intermediaries and EHDS health data intermediaries
- **Trusted health data holders**: New concept in health sector may conflict with existing DGA-defined data intermediation services

#### Medical Device and AI Regulation Overlaps

- EHR systems may qualify as medical devices under Regulation (EU) 2017/745
- AI systems in EHRs subject to EU AI Act (Regulation (EU) 2024/1689)
- Multiple regulatory frameworks may create conflicting requirements

### Implementation and Enforcement Issues

#### Compliance and Implementation Deficit Risk

- Complex infrastructure requirements may not be met by all MS
- Fragmentation continues if some MS implement slowly or incompletely
- No clear enforcement mechanism for persistent non-compliance
- Risk of "two-speed" Europe with advanced and lagging MS

#### Data Quality and Interoperability Challenges

- Existing data collection practices heterogeneous across MS
- Conversion to common formats costly and challenging
- Data from different sources, collected with different definitions, difficult to combine meaningfully
- "Same standards used differently" problem persists despite formal standardization

#### Cybersecurity and Data Protection Risks

Large centralized datasets create attractive targets for cybercriminals precisely because health data possesses exceptional value in criminal markets. Identity theft using genetic information or mental health diagnoses commands premium prices. Blackmail possibilities arise from disclosure of sensitive health information. Breach consequences prove particularly severe because genetic information, mental health diagnoses, substance use history, and sexual health data cannot be changed if compromised; unlike financial fraud where accounts can be closed or passwords reset, health data breaches create permanent privacy intrusions. Secure processing environments represent new technology with unknown implementation risks, and reliance on specific vendors creates potential vendor lock-in concerns where future switching becomes prohibitively expensive.

#### Third-Country Data Transfer Issues

EHDS enables transfers of health data to third countries through HealthData@EU connections, but these transfers depend on legal mechanisms under GDPR Chapter V. Relatively few jurisdictions possess adequacy decisions recognizing equivalent data protection; most third countries require standard contractual clauses or other transfer instruments that provide weaker protections than direct adequacy findings. Health data transferred to third countries may become subject to foreign law enforcement demands, intelligence gathering activities, or other government access that European individuals cannot challenge under European law. These dynamics create risks that health data intended for narrow research purposes becomes accessible to third-country governments through legal processes individuals cannot contest or even learn about.

### Ethical Concerns

#### Individual vs. Collective Autonomy

Fundamental tension exists between respecting individual rights to control personal data and achieving collective benefits from large-scale data aggregation. EHDS attempts to navigate this tension through mechanisms like the right to opt out, but these mechanisms contain important limitations. Override mechanisms for public health purposes (Article 54) raise questions about proportionality and necessity when individual autonomy is set aside. Determining when public interest genuinely justifies overriding individual preferences proves inherently contestable; there exists risk of abuse if "public interest" receives expansive interpretation extending beyond genuine emergency contexts.

#### Justice and Equity

Health data distribution across EU Member States is systematically unequal, with over-representation from wealthy Member States possessing advanced digital infrastructure while data from populations in less-developed regions may be scarcer or lower quality. This creates risk that research and innovation benefits concentrate in wealthy countries while valuable data originates from less-advantaged populations. Such dynamics echo historical exploitation patterns where developing countries provide raw materials while developed countries capture value-added processing and profits. Addressing this requires explicit attention to equitable benefit-sharing and ensuring governance structures represent and include voices from underrepresented regions and populations.

#### Profiling and Discrimination Risk

Large-scale health data aggregation enables sophisticated profiling capable of categorizing individuals by health risk, susceptibility, and predicted healthcare costs. Despite formal prohibitions on detrimental treatment (Article 62), algorithmic discrimination remains possible through subtle mechanisms where decisions appear neutral but produce disparate impact on specific populations. Historical patterns of discrimination in medicine—from syphilis studies on African American subjects to contemporary disparities in pain management and cardiac care—demonstrate how medical systems can embed bias in ways that appear scientifically justified. Health data systems enabling automated decision-making risk systematizing and amplifying these existing patterns unless deliberate safeguards address them.

---

## 12. Key Takeaways {#conclusions}

### Regulatory Architecture

Health data governance operates through a layered regulatory framework comprising multiple complementary instruments. The General Data Protection Regulation provides the foundational privacy and personal data protection framework applicable to all processing. The Data Governance Act establishes general principles for data spaces and intermediation services. The Data Act provides a model for fair data access based on reciprocity and transparency. EHDS builds upon these foundations by creating health-sector-specific governance tailored to the particular needs of healthcare systems and populations.

Health data receives this heightened regulatory attention because it merits exceptionalism within data governance. The sensitivity of health information—revealing personal health status, genetic characteristics, and individual vulnerabilities—demands special protection. Medical confidentiality traditions reflecting centuries of healthcare ethics inform regulatory design. Risk of discrimination based on health status or genetic information creates stakes for discrimination prevention that exceed ordinary data governance concerns. Critically, healthcare systems depend on patient trust; regulatory frameworks that appear to undermine data control risk eroding the trust necessary for individuals to seek healthcare and share sensitive information with providers.

EHDS attempts to balance multiple competing interests and rights. Patient autonomy and control must be protected through primary use rights, opt-out mechanisms, and granular access restrictions. Simultaneously, public health and research benefits must be realized through enabling secondary uses and cross-border data flows. Data provider interests must be protected through appropriate fees and protection mechanisms. Data user access must be facilitated through structured permit systems that reduce unnecessary barriers while maintaining appropriate safeguards. This balance reflects recognition that health data governance serves multiple legitimate purposes that cannot be entirely optimized simultaneously.

### Primary Use Transformation

EHDS significantly enhances patient rights beyond what GDPR provides. Patients enjoy the right to immediate access to priority health data without the one-month delay GDPR typically allows. Enhanced portability rights enable moving data across borders in standardized formats rather than only where technically feasible as GDPR requires. Granular access controls allow patients to restrict access to specific sensitive data categories while remaining accessible for other purposes. Rectification mechanisms enable correcting inaccurate records. Importantly, patients retain opt-out rights from cross-border sharing where Member States choose to provide them, offering meaningful control over data export.

These patient rights are supported by mandatory infrastructure requirements. Member States must establish electronic health data access services enabling patients to access their data. Health professional access services enable healthcare providers to access patient data to provide care. MyHealth@EU infrastructure enables cross-border healthcare through standardized data sharing when patients seek care in other Member States. Digital health authorities provide governance and coordination. These infrastructure requirements represent substantial investment but enable the functional exercise of patient rights rather than merely theoretical rights on paper.

Underlying this infrastructure is an interoperability imperative. The European electronic health record exchange format enables data portability across systems and borders. Harmonized standards and common specifications are essential for systems to function together rather than remaining in separate silos. Healthcare system digitalization is accelerated throughout the EU as this regulatory push forces modernization of systems that might otherwise operate indefinitely with legacy technology.

### Secondary Use Framework

The EHDS replaces ad-hoc health data governance with a structured access system built around health data access bodies, data permits, and secure processing environments. Health data access bodies provide centralized governance replacing the previous system where individual data holders determined access unilaterally. Data permits specify exactly which data can be used, for what purposes, under which safeguards, and for how long, creating transparency and consistency. Secure processing environments prevent unauthorized access and prohibit re-identification attempts, maintaining data holder control throughout analysis. Public reporting requirements ensure transparent decision-making rather than opaque governance conducted behind closed doors.

This framework attempts to balance innovation with protection through permissive scope combined with meaningful safeguards. Permitted purposes encompass broad categories including research, policy-making, regulatory activities, and innovation, creating space for diverse beneficial uses. Prohibited uses—detrimental treatment, marketing, automated decision-making, re-identification attempts—establish clear bright-line boundaries that data users cannot cross. Data minimization principles require use of anonymized data where possible and pseudonymized data where necessary, reducing privacy risks. Criminal liability for re-identification attempts establishes severe consequences for violating privacy protections.

Importantly, data subjects retain agency within this framework. The right to opt out from secondary use in principle (with exceptions only for genuine public health emergencies) preserves individual decision-making. Information rights ensure individuals learn how their data is used. Significant findings notification requires researchers to inform individuals of health discoveries about them. Complaint mechanisms allow individuals to report violations. These provisions attempt to maintain data subject voice even within large-scale automated systems.

### Governance Innovations

EHDS introduces several governance innovations enabling coordination across the EU while respecting national healthcare system autonomy. HealthData@EU provides cross-border infrastructure connecting Member States for secondary use, accelerating research coordination across national boundaries. The single application principle enables researchers to submit one application rather than separate applications to each Member State, significantly reducing burden and barriers to cross-border research. Reciprocity requirements ensure that third-country participation creates mutual obligations rather than one-way data extraction. Trusted third countries can participate in the framework, extending benefits beyond the EU.

Multi-stakeholder coordination mechanisms ensure diverse perspectives inform governance. The EHDS Board coordinates Member States and the Commission, creating a forum for resolving conflicts and establishing consistent practice. A stakeholder forum including patients, health professionals, industry, researchers, and academics ensures the Board considers perspectives beyond government actors. Steering groups manage day-to-day operations while the full Board addresses strategic questions. Cooperation with other authorities including data protection authorities, the AI Board, and medical device bodies ensures EHDS integration into the broader EU regulatory ecosystem rather than operating in isolation.

Data quality receives explicit governance focus recognizing that datasets of poor quality serve no one—neither protecting privacy nor enabling research. Data quality and utility labels inform potential users about dataset characteristics, enabling informed decisions about fitness for particular purposes. The EU dataset catalogue improves discoverability of available datasets, reducing duplication and enabling optimal allocation of data to appropriate uses. Harmonized standards for coding and registration reduce the translation burden researchers face when combining data from multiple sources. Data enrichment mechanisms improve datasets over time as researchers identify completeness gaps.

### Implementation Challenges

The transition from current fragmented health data systems to the EHDS framework represents a complex undertaking unfolding gradually between 2025 and 2034. This extended timeline reflects recognition that simultaneous implementation across all EU Member States and healthcare systems is not feasible. The transition requires significant infrastructure investment throughout the EU, technical standardization across diverse existing national systems that evolved independently, extensive staff training and capacity building, and organizational restructuring to accommodate new governance mechanisms. These requirements fall heavily on healthcare systems and Member State authorities already managing substantial demands.

Funding sustainability remains incompletely resolved. Cost-sharing between EU and Member State budgets lacks clear specification, creating uncertainty about who bears various costs. Fee structures for secondary use must be carefully calibrated—high enough to support operations and reasonable data holder compensation, yet low enough not to deter research and innovation. Healthcare system burdens from data provision and management responsibilities may accumulate, particularly if funding proves inadequate. Risk of implementation deficit exists if some Member States lack resources or political will to implement fully, potentially creating a "two-speed Europe" where some jurisdictions implement advanced systems while others lag.

Trust and social license represent critical success factors that cannot be mandated. Public support is essential for health data systems to function effectively; citizens must be willing to trust healthcare organizations with sensitive information. Individual control and consent remain valued by citizens more highly than many policymakers assume; frameworks appearing to minimize patient choice risk eroding participation. Transparency requirements are essential for regulatory legitimacy; if governance operates behind closed doors, trust erodes even if actual practices prove benign. Benefit-sharing mechanisms are needed to ensure that returns on public investment in health data systems accrue to publics rather than narrowly to commercial beneficiaries.

### Strategic Considerations for Stakeholders

**Healthcare Providers** must prepare comprehensively for EHDS implementation. They should anticipate mandatory requirements for electronic health record system compliance with EHDS standards and begin planning infrastructure for patient data access services and health professional access services. Staff training programs must be developed to ensure personnel understand new systems and procedures. Data governance frameworks addressing data quality, access control, and responsibility allocation should be established before implementation deadlines. Engagement with digital health authorities and early participation in implementation planning can help ensure that healthcare provider perspectives inform regulation implementation.

**Researchers and Innovators** should familiarize themselves with data permit requirements and application procedures before implementation, enabling rapid access once systems become operational. Understanding secure processing environment rules and technical constraints helps researchers plan efficient analytical workflows within regulatory parameters. Multi-country data access strategies should be developed recognizing that EHDS enables cross-border research that was previously prohibitively complex. Budgeting for health data access body fees should be incorporated into research financial planning. Ensuring that research projects include ethical approval mechanisms as required by national law demonstrates compliance from inception rather than discovering problems during application review.

**Patient and Consumer Organizations** play crucial advocacy roles in ensuring EHDS implementation respects patient interests. Advocating for transparent implementation procedures helps ensure that decisions reflect evidence rather than hidden agendas. Ensuring patient voice in health data access body governance directly shapes how those bodies exercise their powers. Monitoring whether patient consent and control are preserved as implementation proceeds enables early warning if actual practice diverges from regulatory intent. Tracking benefit-sharing outcomes reveals whether EHDS generates public benefits or narrowly enriches commercial actors. Supporting digital literacy initiatives helps ensure that patient agency becomes meaningful as systems grow more complex.

**Digital Health Authorities and Health Data Access Bodies** serve as primary implementation actors bearing responsibility for system success. They must develop robust governance frameworks establishing decision-making processes, conflict resolution procedures, and accountability mechanisms. Establishing data quality standards for acceptable datasets requires technical expertise and stakeholder consultation. Creating efficient permit issuance processes demonstrates responsiveness to researchers while maintaining appropriate safeguards. Building secure processing infrastructure requires substantial technical and financial resources. Stakeholder engagement throughout implementation builds legitimacy and improves outcomes by incorporating diverse perspectives.

**The EU Commission** bears responsibility for implementation guidance and system coherence. Developing detailed implementing acts within the timelines the regulation specifies enables Member States to proceed with implementation. Supporting Member State capacity building recognizes that unequal resources across Member States could produce unequal implementation. Monitoring implementation progress and intervening when serious gaps emerge prevents backsliding toward pre-EHDS fragmentation. Addressing emerging interoperability issues ensures that systems designed independently can actually communicate. Ensuring coherence with other EU regulations including the AI Act, Cybersecurity Act, and medical device regulations prevents conflicting requirements from creating compliance confusion.

---

## References and Key Articles

### EHDS Regulation

- **Regulation (EU) 2025/327** of 11 February 2025 on the European Health Data Space, OJ L 327, 5.3.2025

### Related EU Regulations

- **Regulation (EU) 2016/679** (GDPR), OJ L 119, 4.5.2016
- **Regulation (EU) 2022/868** (DGA), OJ L 152, 3.6.2022
- **Regulation (EU) 2023/2854** (Data Act), OJ L 2023/2854, 22.12.2023
- **Regulation (EU) 2024/1689** (AI Act), OJ L 2024/1689, 12.7.2024
- **Regulation (EU) 2024/2847** (Cyber Resilience Act), OJ L 2024/2847, 20.11.2024
- **Regulation (EU) No 910/2014** (eIDAS), OJ L 257, 28.8.2014
- **Directive 2011/24/EU** (Cross-border healthcare), OJ L 88, 4.4.2011

### Key Academic and Policy Analysis

- Marelli, L., et al. (2023). "The European health data space: Too big to succeed?" *Health Policy*, 135, 104861.
- Marcus, J.S., Martens, B., Carugati, C., Bucher, A., & Godlovitch, I. (2022). *The European Health Data Space*. Policy Department for Economic, Scientific and Quality of Life Policies, European Parliament.
- Malgieri, G., & Comandé, G. (2017). "Sensitive-by-distance: quasi-health data in the algorithmic era." *Information & Communications Technology Law*, 26(3), 229-259.
- Fiske, A., et al. (2022). "Value-creation in the health data domain: a typology of what health data help us do." *Biosocieties*, 18, 473-494.
- Fiske, A., et al. (2020). "Sharing health data for research." *Lancet*, 395(10224), 491-492.

### Foundational EU Documents

- Commission Recommendation (EU) 2019/243 on European Electronic Health Record exchange format
- eHealth Network Working Documents on digital health governance
- European ethical principles for digital health (eHealth Network, January 2022)

---

**End of Consolidated Summary**

This document is part of Module 2: The (EU) Regulation of Health Data Sharing, as part of the JBL110 Innovation and Regulation course at Tilburg Law School. For the most current information and official guidance, consult the full EHDS Regulation text and implementing acts as adopted by the European Commission.

# Module 3: Competition Law – Consolidated Summary

**Module Title:** Data and Regulation of Competition  
**Instructor:** Merve Oner Kabadayi, PhD Researcher at TILT/Tilburg Law School  
**Date:** 23 September 2025

This consolidated document synthesizes the essential concepts from Module 3, integrating the core lecture materials with comprehensive additional readings on competition law, with particular emphasis on **Articles 101 and 102 of the Treaty on the Functioning of the European Union (TFEU)** and their application in the digital economy and data-driven markets.

---

## Table of Contents

1. [Introduction: Competition Law in Context](#introduction)
2. [Objectives and Foundations of EU Competition Law](#objectives)
3. [Articles 101 and 102 TFEU: Core Provisions](#articles-101-102)
4. [Article 101 TFEU: Anti-Competitive Behaviour (Cartel Prohibition)](#article-101)
5. [Article 102 TFEU: Abuse of Dominant Position](#article-102)
6. [Merger Control Under the EUMR](#merger-control)
7. [Data and Competition Law: Emerging Challenges](#data-competition)
8. [Case Studies and Practical Application](#case-studies)
9. [EU vs. US Competition Law](#eu-vs-us)
10. [Key Takeaways](#conclusions)

---

## Introduction: Competition Law in Context {#introduction}

### Historical Background

Competition law emerged in the late 19th and early 20th centuries in response to the concentration of economic power. The **Sherman Act** (1890) in the United States first established that "every contract, combination in the form of trust or otherwise, or conspiracy, in restraint of trade or commerce among the several States" is illegal. This foundational principle aimed to protect competitive markets from being dominated by powerful monopolies controlled by the "Robber Barons" such as John D. Rockefeller, Cornelius Vanderbilt, Andrew Carnegie, and J. P. Morgan.

The European Union later developed its own competition framework, enshrining competition principles in the Treaties and establishing competition as a fundamental component of the internal market project.

### Why Competition Law Matters Today

The digital economy presents unprecedented challenges to traditional competition law frameworks. The shift from the **Oil & Gas Era** (where 2005 market leaders like Exxon and GE dominated) to the **Big Tech Era** (where 2024 market leaders include Microsoft, Apple, Amazon, Alphabet, and Meta) illustrates the transformation of value creation from tangible assets to intangible data and digital platforms.

**Key Transformations:**
- Data is now considered the "new oil" and the world's most valuable resource
- Data generation: ~2.5 quintillion bytes daily (Forbes)
- Data is the new currency of the digital economy
- Tech giants accumulate overwhelming advantages through data accumulation

**The Central Question:** Can & should EU competition law address the dominant positions of tech giants built primarily through data accumulation?

### Competition Law's Scope

Competition law concerns itself with five critical parameters:
1. **Price** – Advertisement-dependent "free" services where data is the main currency
2. **Quality** – Privacy concerns elevated as competition concerns
3. **Output** – Data as an asset; monopolization of data
4. **Choice** – Availability of alternative providers
5. **Innovation** – Does competition law facilitate or hinder innovation?

---

## Objectives and Foundations of EU Competition Law {#objectives}

### Legal Basis

EU competition law rests on:

- **Treaty on the Functioning of the European Union (TFEU):** Articles 101–109 define rules applying to undertakings
- **Protocol No. 27 on the Internal Market and Competition:** Clarifies that competition protection is integral to the internal market
- **Article 3 TEU:** Establishes that the EU shall work for a "highly competitive social market economy"

The founding principle is Margrethe Vestager's observation: "There would be **no genuine integration without a Single Market** – and **no functioning Single Market without a strong competition policy enforced by a central competition authority**."

### Primary Objectives of EU Competition Law

**1. Facilitation and Safeguarding of the Internal Market**

The internal market is "an area without internal frontiers in which the free movement of goods, persons, services and capital is ensured." A functioning competitive process is essential to this goal. Competition rules protect "not only the immediate interests of individual competitors or consumers but also the structure of the market and thus competition as such" (*C-8/08 T-Mobile Netherlands BV*).

**2. Protection of Consumer Welfare**

"Our aim is simple: to protect competition in the market as a means of **enhancing consumer welfare** and ensuring an **efficient allocation of resources**" – former Commissioner Neelie Kroes (2005). Consumer welfare encompasses:
- Access to goods and services at competitive prices
- Choice among market alternatives
- Quality and innovation incentives

**3. Economic Efficiency**

Competition law promotes three forms of economic efficiency:
- **Allocative Efficiency:** Resources directed to their most valued uses
- **Cost Efficiency:** Companies minimizing production costs
- **Dynamic (Innovative) Efficiency:** Incentives for continuous innovation and long-term economic growth

**4. Protection of the Competitive Process**

Competition as a discovery procedure (Friedrich A. von Hayek) allows markets to allocate resources dynamically through autonomous decisions by market participants rather than through central planning or dominant player control.

---

## Articles 101 and 102 TFEU: Core Provisions {#articles-101-102}

### Overview of the Two Pillars

EU competition law rests on two fundamental prohibitions that form the backbone of antitrust enforcement:

| Provision | Focus | Type of Violation | Legal Test |
|-----------|-------|------------------|-----------|
| **Article 101 TFEU** | Anti-competitive agreements, decisions, concerted practices | Horizontal/vertical collusion, cartels | Between undertakings + effect on trade + effect on competition |
| **Article 102 TFEU** | Abuse of dominant position | Monopoly abuse, exploitative/exclusionary conduct | Dominant position + abuse + effect on trade |

Both provisions are essential tools:
- **Article 101** prevents companies from colluding to reduce competition
- **Article 102** prevents dominant companies from using their power to further restrict competition

---

## Article 101 TFEU: Anti-Competitive Behaviour {#article-101}

### The Provision

**Article 101 TFEU** (ex Article 81 TEC):

> The following shall be prohibited as incompatible with the internal market: all **agreements** between **undertakings**, **decisions by associations of undertakings** and **concerted practices** which may **affect trade between Member States** and which have as their **object or effect** the **prevention, restriction or distortion of competition** within the internal market, and in particular those which:
> 
> (a) directly or indirectly fix purchase or selling prices or any other trading conditions;
> (b) limit or control production, markets, technical development, or investment;
> (c) share markets or sources of supply;
> (d) apply dissimilar conditions to equivalent transactions with other trading parties, thereby placing them at a competitive disadvantage;
> (e) make the conclusion of contracts subject to acceptance by the other parties of supplementary obligations which, by their nature or according to commercial usage, have no connection with the subject of such contracts.

This article applies to all conduct that restricts competition through coordination between independent market participants.

### Legal Test for Article 101 TFEU Violation

A violation of Article 101(1) requires establishing five elements:

#### 1) Between Undertakings

An **undertaking** is any entity engaged in economic or commercial activities, regardless of:
- Whether activities are carried out for profit
- Legal form (company, partnership, individual trader, public body engaged in commercial activity)
- Sector (manufacturing, services, public utilities)

**Examples:** Microsoft, Facebook, Google, telecommunications providers, hospitals offering paid services.

**Exclusion:** Purely personal or household activities do not constitute economic activities.

#### 2) Agreements or Concerted Practices

Article 101 captures two distinct forms of coordination:

##### a) **Agreements**

An agreement is any arrangement where parties determine how they will behave on the market. Key characteristics:
- **No formal document required:** Oral agreements suffice (phone calls, emails, "handshake deals")
- **Intent immaterial:** Parties need not intend to restrict competition; effect is what matters
- **No meeting necessary:** Communication can occur indirectly or through intermediaries

**Types of Agreements:**

**Horizontal Agreements (Between Competitors at Same Supply Level)**
- Price fixing (most serious: "hard-core cartel")
- Market sharing
- Bid rigging
- Information exchange at competitors' level
- Production quotas
- Technology pools

*Example:* Spotify and Apple Music agreeing to charge the same subscription price to consumers.

**Vertical Agreements (Between Undertakings at Different Supply Levels)**
- Resale price maintenance (fixing retail prices)
- Exclusive distribution arrangements
- Territorial restrictions
- Selective distribution systems
- Tied selling (tying one product to purchase of another)

*Example:* A manufacturer fixing the retail price at which a distributor may sell its products.

**The Principle:** "Competitors know each other so well, even a wink and a nod between them could lead to anti-competitive behaviour."

##### b) **Concerted Practices**

A concerted practice is informal coordination where undertakings:
- Knowingly coordinate their behavior
- Substitute practical cooperation for the risks of competition
- Do NOT have a formal agreement or decision

**Key Distinction:** Evidence of direct agreement is not required. It suffices that parties reveal their strategies to each other such that each knows the other's intended conduct.

**Test (from CJEU Case Law):**
- Parties coordinate behavior
- Each party is aware of the other's conduct
- This conduct influences each party's own behavior
- Practical cooperation is substituted for independent competition

*Example:* Two airlines independently adjusting prices in parallel based on competitor's price signals transmitted through reservation systems.

#### 3) Effect on Trade Between Member States

The agreement/practice must **affect trade between at least two Member States**. The threshold is low:

- Effect can be **direct or indirect**
- Effect can be **actual or potential**
- Effect can be **minimal** in absolute terms

**NOT Required:**
- Trade must cross borders
- Effect must increase trade volumes
- Parties must be in different Member States

**Standard:** If the pattern of trade between at least two Member States is likely to be impacted (even modestly), the requirement is met.

**Presumption:** If an agreement covers several EU Member States or a substantial part of one Member State, effect on inter-state trade is presumed.

#### 4) Effect on Competition: "By Object" or "By Effect"

The restriction must affect competition through one of two pathways:

##### a) **Restriction By Object**

Certain conduct is **inherently restrictive** of competition and requires no analysis of actual effects. These are known as **"hard-core cartels"**:

**Per Se Violations (No Effects Analysis Required):**
1. **Price Fixing** – Directly or indirectly fixing prices
2. **Market Sharing** – Allocating customers, territories, or markets
3. **Bid Rigging** – Collusion in tender processes
4. **Production/Sales Limiting** – Quotas or output restrictions

For these practices, competition authorities need not prove actual harm; the conduct's object itself reveals anticompetitive intent.

**Legal Presumption:** If an agreement's object is to restrict competition, it is presumed to have that effect. The burden shifts to parties to prove otherwise.

##### b) **Restriction By Effect**

Conduct is evaluated based on its **actual or likely competitive impact**. This analysis requires:

- Economic analysis of market conditions
- Counterfactual reasoning (what would happen without the agreement?)
- Evaluation of whether agreement prevents, restricts, or distorts competition

**Competitive Harm Indicators:**
- Price increases or price stabilization at higher levels
- Output reduction
- Reduction in innovation
- Reduction in product variety or quality
- Decreased consumer choice

**De Minimis Rule:** If an agreement's effect on competition is insignificant, Article 101(1) does not apply. The Commission Regulation defines thresholds:
- Horizontal agreements: Combined market share < 10%
- Vertical agreements: Market share < 30%

**When Effect is NOT Insignificant:**
- Information exchange among competitors has clear negative effects if frequent, current, and individualised

#### 5) No Objective Justification Under Article 101(3) TFEU

**Article 101(3) Exemption:**

Even if an agreement violates Article 101(1), it may be exempted if it satisfies all four conditions:

```
An agreement which restricts competition may be declared compatible if:

1) It contributes to improving the production or distribution of goods or 
   technical or economic progress;

2) It allows consumers a fair share of the resulting benefits;

3) It does not impose restrictions beyond those indispensable to achieve 
   these objectives; AND

4) It does not eliminate competition for a substantial part of the products 
   concerned.
```

**Key Points:**

- **All four conditions must be satisfied.** Failure in any one element means no exemption.
- **Burden of Proof:** Parties claiming exemption bear the burden of proving all four conditions.
- **No Automatic Exemption:** Exemptions were historically granted on a case-by-case basis, but now typically covered by **Block Exemption Regulations** for certain agreement categories (e.g., vertical agreements, technology transfer agreements, horizontal cooperation agreements).

**Balancing Test:**
The exemption performs a **balancing test**: Do the efficiency benefits to consumers outweigh the competitive restrictions? If yes, the agreement serves pro-competitive purposes and merits exemption.

### Horizontal Block Exemption Regulations

The Commission has issued **Block Exemption Regulations** for categories of agreements presumed to satisfy Article 101(3):

1. **Horizontal Cooperation Agreements:** R&D agreements, production agreements, purchasing agreements, marketing agreements, standardization agreements
2. **Vertical Agreements:** Distribution agreements, exclusive distribution, selective distribution (max 30% market share threshold)
3. **Technology Transfer Agreements:** Patent licenses, know-how licenses, software licenses (max 30% market share threshold)

### Enforcement: Fines and Remedies

**Administrative Penalties (Article 23 TFEU):**
- **Up to 10% of annual worldwide turnover** of the company
- Applied to both participating companies in an agreement
- Can exceed €1 billion for major cartels

**Example Fines:**
- **Google (2018):** €4.342 billion for abusing dominant position in search
- **Truck Cartel (2016):** €3.8 billion
- **Google (2025):** €2.95 billion
- **Google Shopping (2017):** €2.42 billion

**Private Enforcement:**
- Injured parties may sue for damages in national courts
- **Directive 2014/104/EU (Actions for Damages Directive)** facilitates private claims
- Court can award lost profits, price overcharges, and costs

---

## Article 102 TFEU: Abuse of Dominant Position {#article-102}

### The Provision

**Article 102 TFEU** (ex Article 82 TEC):

> Any **abuse** by one or more **undertakings of a dominant position** within the **internal market or in a substantial part of it** shall be prohibited as incompatible with the internal market in so far as it may **affect trade between Member States**.
>
> Such abuse may, in particular, consist in:
>
> (a) directly or indirectly imposing unfair purchase or selling prices or other unfair trading conditions;
> (b) limiting production, markets or technical development to the prejudice of consumers;
> (c) applying dissimilar conditions to equivalent transactions with other trading parties, thereby placing them at a competitive disadvantage;
> (d) making the conclusion of contracts subject to acceptance by the other parties of supplementary obligations which, by their nature or according to commercial usage, have no connection with the subject of such contracts.

Unlike Article 101, which prohibits **coordination between undertakings**, Article 102 addresses **unilateral conduct by a single dominant firm** or joint dominance by multiple firms.

### Legal Test for Article 102 TFEU Violation

A violation of Article 102 requires establishing five elements:

#### 1) Undertaking

Same definition as Article 101: any entity engaged in economic/commercial activities.

#### 2) Dominant Position

**Definition (CJEU):**
> A position of economic strength enjoyed by an undertaking which enables it to **prevent effective competition being maintained on the relevant market** by giving it the power to behave to an **appreciable extent independently of its competitors, customers and ultimately of its consumers**.

**Key Elements:**
- **Economic strength:** The undertaking has substantial market power
- **Independence:** Ability to act without regard to competitors' reactions
- **Prevention of effective competition:** Power to maintain supracompetitive prices, reduce output, or limit innovation

**Assessment:**
- Dominance is evaluated in relation to the **internal market as a whole or a substantial part of it**
- **Single Member State suffices:** Dominance in one EU Member State is sufficient for Article 102 to apply
- Market definition is critical (using SSNIP test – Small but Significant Non-transitory Increase in Price)

**Market Share as Indicator:**
- > 50% market share: Generally indicates dominance (rebuttable presumption)
- 40-50% market share: May indicate dominance depending on context
- < 40% market share: Rarely indicates dominance unless other factors present

**Other Factors:**
- Barriers to entry and expansion
- Financial resources and technological lead
- Vertical integration
- Access to supply and distribution channels
- Network effects and switching costs
- Customer loyalty

#### 3) Abuse

**Definition:** No single definition exists, but abuse is the improper use of dominant position that distorts or restricts competition. Articles 102(a)-(d) provide **non-exhaustive examples** of abusive conduct.

**Distinction:** A dominant position itself is **not illegal**. The TFEU specifically provides that dominance confers upon the undertaking a **special responsibility not to allow its conduct to impair genuine undistorted competition** (*Guidance on Article 82 Enforcement Priorities*, 2009).

**Categories of Abusive Conduct:**

##### a) **Exploitative Abuse**

Conduct that exploits customers or trading partners by imposing **unfair prices or trading conditions**:

**Excessive Pricing (Article 102(a)):**
- Imposing prices that have no reasonable relationship to the economic value provided
- *Example:* Charging excessive pharmaceutical prices for life-saving drugs with no close substitutes

**Unfair Trading Conditions (Article 102(a), (d)):**
- Imposing payment terms, delivery conditions, or other terms that are grossly disadvantageous
- Bundling products in ways that exploit consumers
- *Example:* Forcing retailers to stock slow-moving products to access fast-moving products

**Price Discrimination (Article 102(c)):**
- Applying dissimilar conditions to equivalent transactions with different trading parties
- *Requirement:* Transactions must be **equivalent** (similar products, similar volumes, similar timing)
- *Exception:* Objective justification (e.g., cost differences, market conditions)
- *Example:* Charging the same supplier different prices for identical products based solely on buyer identity

##### b) **Exclusionary Abuse**

Conduct that forecloses market access for **competitors** or prevents their competition:

**Predatory Pricing:**
- Setting prices below costs to eliminate or discipline competitors
- *Condition:* Reasonable expectation of recouping losses through supracompetitive pricing post-exit
- *Example:* Microsoft pricing its browser below cost to eliminate Netscape

**Refusal to Deal:**
- Refusing to supply an essential input to competitors
- *Requirements* ("Exceptional Circumstances Test" from *Magill* and *IMS Health*):
  1. The input is **indispensable** for downstream competition (no substitute)
  2. Refusal **excludes all effective competition** on the downstream market
  3. Refusal **prevents emergence of a new product** for which consumer demand exists
  4. Refusal is **objectively unjustified**
- *Example:* **Microsoft** refusing to disclose interface information to competitors wanting to develop interoperable software

**Predatory Exclusion:**
- Pricing strategies, exclusive dealing, or other conduct designed to foreclose competitors
- *Analysis:* Would an equally efficient competitor be able to compete?
- *Standard:* "As Efficient Competitor Test" – would a competitor as efficient as the dominant firm be forced to exit or unable to enter?
- *Example:* Tying or bundling to foreclose access to markets

**Exclusive Dealing:**
- Requiring customers to purchase exclusively from the dominant firm
- Preventing customers from dealing with competitors
- *Example:* Long-term exclusive contracts foreclosing alternatives
- *Countervailing Factors:* Efficiency gains, pro-competitive justifications

**Tying and Bundling:**
- Conditioning sale of one product (the "tying product") on purchase of another product (the "tied product")
- Particularly problematic if leveraging dominance from one market to another
- *Example:* Conditioning Windows licensing on acceptance of Internet Explorer browser
- *Requirements:* Two separate products, dominant position in tying product, coercion, foreclosure effect

**Margin Squeeze:**
- Narrowing the gap between upstream wholesale prices and downstream retail prices
- Forecloses downstream competitors unable to operate profitably at resulting margins
- *Example:* Vertically integrated telecom incumbent raising interconnection charges while reducing retail prices

#### 4) Effect on Trade Between Member States

Same standard as Article 101: trade between at least two Member States must be **potentially or actually** affected. Low threshold, typically presumed for companies with multi-Member State operations.

#### 5) No Objective Justification

Dominant conduct may escape Article 102 liability if objectively justified:

**Possible Justifications:**
1. **Efficiency gains:** Conduct generates substantial offsetting pro-competitive benefits
2. **Consumer benefits:** Conduct benefits consumers overall despite competitive restrictions
3. **Safety/health:** Conduct necessary for safety, health, or consumer protection
4. **Technical feasibility:** Conduct necessary due to technical requirements
5. **Competition on merits:** Conduct results from superior performance, not anticompetitive tactics

**Burden:** Dominant firm must prove justification. Efficiency claims must be substantiated with concrete evidence.

### Special Responsibility of Dominant Undertakings

A critical principle undergirds Article 102: **Dominant undertakings have a special responsibility to ensure their conduct does not distort competition.**

This means:
- Conduct lawful for non-dominant firms may be abusive for dominant firms
- Higher behavioral standards apply
- Stricter scrutiny of contractual arrangements and pricing practices

### Digital Markets Act: Complementary Framework

The **Digital Markets Act (DMA)**, which became operative in 2024, supplements Article 102 by imposing **ex-ante (preventive) obligations** on designated "gatekeeper" online platforms. Unlike Article 102 (which requires proving abuse after the fact), the DMA prohibits specified conduct prospectively for platforms meeting designation criteria (size, control of digital services, strategic importance).

---

## Merger Control Under the EUMR {#merger-control}

### Legal Framework

**Regulation (EC) No 139/2004 on the Control of Concentrations (EUMR)** provides a separate competition tool: **preventive merger control**. Unlike Articles 101-102, which apply to post-merger conduct, merger control assesses concentration **before it occurs**.

### Rationale for Merger Control

Mergers can reduce competition in several ways:
- **Horizontal mergers:** Eliminate a competitor, reduce market participants
- **Vertical mergers:** Create foreclosure opportunities (access denial)
- **Conglomerate mergers:** Enable leveraging of dominance across markets

Merger control is a **prophylactic tool**: problems are prevented rather than remedied after harm occurs.

### Legal Test for Incompatible Merger

**Article 2(3) EUMR:**

> A concentration which would **significantly impede effective competition** (SIEC) in the **common market** or in a **substantial part** of it, in particular as a result of the creation or strengthening of a dominant position, shall be declared **incompatible with the common market**.

### Elements of the SIEC Test

#### 1) Concentration

A **concentration** occurs when:

**a) Merger:** Two previously independent undertakings become one
- *Example:* Facebook acquires WhatsApp, combining two independent social media platforms

**b) Acquisition of Control:** One undertaking gains control over another
- *Example:* Microsoft acquires 55% of Netflix shares
- **Control:** Power to exercise decisive influence on an undertaking's operations

**NOT a Concentration:**
- Temporary shareholding for investment purposes only
- Transactions between companies already under common control (e.g., parent company reorganizations)

#### 2) EU Dimension

The merger must meet jurisdictional thresholds. **Primary Thresholds (Article 1(2)):**

**General Thresholds:**
- **Combined worldwide turnover > €5,000 million** AND
- **EU-wide turnover of at least two undertakings > €250 million each**

**Alternative Threshold:**
- **EU-wide turnover of at least three undertakings > €100 million each** AND
- **At least two of these with turnover > €30 million in same Member State** AND
- **Each of at least two undertakings > €25 million worldwide**

**German Amendment (§ 35 (1a) ARC, 2017):**
- **Transaction value > €400 million** (even if turnover thresholds not met)
- Responds to concerns about free services (zero turnover but high value)

**Referral Rules:**
- Concentration can be referred from Member States to Commission if competent
- Commission can refer back to Member States (Article 4(5), Article 9)

#### 3) Significantly Impede Effective Competition (SIEC Test)

The merger must be assessed as likely to **significantly impede competition** (standard: lower than outright prohibition, higher than trivial effect).

**Analysis Methods:**

**a) Non-Coordinated Effects:**
- Risk of **unilateral price increases** due to loss of competitive constraint
- Merger creates incentive and ability to raise prices post-merger
- Competitors cannot compensate for lost competitor
- *Example:* Removal of significant price competitor → remaining firms raise prices

**b) Coordinated Effects:**
- Merger makes **coordination easier** among remaining competitors
- Post-merger market structure facilitates collusion (fewer, more symmetric players)
- *Example:* Merger of two of five competitors → remaining three can more easily coordinate prices

**c) Foreclosure Effects (Vertical/Conglomerate Mergers):**
- Merged firm can deny competitors access to essential inputs
- *Example:* Upstream firm acquired by downstream rival → input unavailable to other downstream competitors

**d) Conglomerate Merger Leverage:**
- Dominant position in one market leveraged to adjacent market
- *Example:* Dominant software company acquiring hardware distributor → leverages software dominance to hardware sales

#### 4) Substantial Part of the Internal Market

**Geographic Market Definition:**
- Merger must affect EU internal market as a whole or a "substantial part"
- **One Member State suffices** to meet threshold
- Market definition uses SSNIP test (similar to antitrust cases)

#### 5) Prior Notification

**Procedural Requirement:**
- Parties must notify merger **before closing the transaction**
- Failure to notify can result in dissolution orders and fines

### Data in Merger Control

Data mergers present novel challenges because:

**Quantification Issues:**
- Turnover thresholds become irrelevant for data-dependent companies (Facebook/WhatsApp: $19 billion paid for company with minimal revenue)
- Valuation of data assets difficult
- Market share calculation problematic for "free" services

**Data Concentration Concerns:**
- Merger may combine datasets, reducing market access for competitors
- Lock-in effects increase when data becomes more comprehensive
- Network effects amplified by combined datasets

### Key Merger Cases Involving Data

#### Microsoft/Skype (2011)

**Facts:** Microsoft acquired Skype (video calling service) for €7.5 billion.

**Commission Concerns:**
- Combined market position in consumer communications
- Potential to integrate Skype with Outlook/Windows ecosystem
- Network effects could create tipping

**Resolution:** Cleared without conditions.

**Reasoning:**
- High price sensitivity (services free – customers switch if charged)
- Low market barriers (easy entry for new communication services)
- Dynamic sector with short innovation cycles
- High market share (90% in video calls) not determinative due to market dynamism

**Lesson:** Commission discounts static market share analysis in dynamic digital markets.

#### Facebook/WhatsApp (2014)

**Facts:** Facebook acquired WhatsApp for **$19 billion** – extraordinary price for company with minimal revenue.

**Jurisdictional Challenge:**
- Traditional turnover thresholds not met
- Invoked **Article 4(5) EUMR**: referral by three Member States
- Exceptional procedure to establish jurisdiction

**Commission Concerns:**
- **Data concentration:** Combining Facebook's and WhatsApp's user data
- Facebook's extensive user profiling + WhatsApp's communication data
- Enhanced advertising targeting capability

**Resolution:** Cleared without conditions.

**Reasoning:**
- WhatsApp collected minimal personal data at time of merger
- Large amount of competing ad-targeting data available outside Facebook
- Data portability rights under future GDPR would enable switching
- Privacy concerns fall within **GDPR jurisdiction, not competition law**

**Post-Merger Enforcement:**
- Commission fined Facebook €110 million (2017) for **misleading information** in merger notification
- Facebook had claimed user matching between platforms was "impossible or unreliable"
- Actually, integration was easily feasible

**Lessons:**
- Data concentration itself not automatically problematic under traditional test
- Novel issue of data valuation in M&A pricing unresolved
- Privacy/GDPR considerations distinct from competition concerns (though now recognized as interconnected)

#### Microsoft/LinkedIn (2016)

**Facts:** Microsoft acquired LinkedIn for **$26 billion** (largest tech acquisition by price).

**Jurisdictional Issue:**
- More easily met traditional thresholds given Microsoft's size
- Turnover-based jurisdiction less problematic for Microsoft

**Commission Concerns:**

**1. Professional Social Network Market:**
- LinkedIn dominant in professional networking
- Microsoft could leverage Windows/Office integration
- Pre-installation on Windows and integration with Outlook
- Network effects could tip market

**2. CRM Software Market:**
- LinkedIn data valuable for machine learning in CRM tools
- Microsoft could deny competitors access to full LinkedIn dataset
- Competitors could be hampered in developing competing CRM solutions

**3. Online Advertising Market:**
- Combined Microsoft-LinkedIn data valuable for ad targeting
- Microsoft could increase advertising market power

**Commission Decision: **Cleared with Commitments** (Article 8(2) EUMR)

**Imposed Commitments:**
1. No pre-installation of LinkedIn on Windows PCs
2. Maintain API interoperability with Microsoft Office
3. Continued access to LinkedIn data for third-party CRM competitors
4. Interoperability commitments for Outlook calendar/contact data

**Lesson:** Commitments can resolve data-driven merger concerns; not all data mergers prohibited.

#### Google/Fitbit (2020)

**Facts:** Google acquired Fitbit (wearable health data company) for ~$2.1 billion.

**Concerns:**
- Health/fitness data concentration with Google
- Google's vast user profiling + health data integration
- Potential for health insurance discrimination, targeted advertising

**Resolution:** Cleared with commitment to data silo.

**Key Commitment:** 
- Google committed to **data silo**: health data from Fitbit will not be combined with Google's advertising profile data
- Separation enforced through technical and organizational measures
- Monitoring provisions

**Lesson:** Data silos can address competition concerns in health/sensitive data contexts.

### State Aid

**Article 107-109 TFEU** address **State aid** (subsidies to undertakings). State aid distorts competition by enabling undertakings to compete using public funds rather than merit.

**General Prohibition (Article 107(1)):**
Aid granted by Member States that distorts or threatens to distort competition and affects inter-state trade is prohibited.

**Exceptions:** Certain aid may be justified for public interest purposes (regional development, environmental protection, etc.).

---

## Data and Competition Law: Emerging Challenges {#data-competition}

### Why Data Is a Topic for Competition Law

Data has become a critical asset affecting market power and competitive dynamics. Competition authorities must account for data as they assess:
- **Market power:** Does control of data create market dominance?
- **Market foreclosure:** Can dominant firms deny competitors access to essential data?
- **Merger effects:** Does combination of datasets significantly impede competition?
- **Innovation:** Do data-driven network effects reduce incentives for competitive innovation?

### Microsoft Case: Data as Essential Facility

**Microsoft (COMP/C-3/37.792, 2004)** remains foundational for data in competition law.

**Facts:**
- Microsoft dominant in corporate PC operating systems (Windows)
- Competitors wanting to develop interoperable software needed **interface information** (data about how Windows operates)
- Microsoft withheld this data or discriminated through pricing
- Competitors unable to offer products compatible with Windows

**Commission Finding:**
- Interface information was **essential facility** for secondary software market competition
- Refusal to disclose constituted **abuse of dominant position** (Article 102)
- Dominance in OS market leveraged to block competition in software market

**Significance for Data:**
- Established that **refusal to disclose data** can constitute Article 102 abuse
- Demonstrated data's importance as competitive input
- Set standards for when access obligations arise ("exceptional circumstances")

**Remedy:**
- Microsoft ordered to disclose interface information
- License on **RAND terms** (Reasonable And Non-Discriminatory)
- Fine of €497 million

### Paradigm Shifts in Digital Economy

Data challenges traditional competition law concepts in fundamental ways:

#### 1) Quantification Issues

**Problem:** Competition law depends on precise quantification (prices, market shares, turnovers) but data value resists quantification.

**SSNIP Test Failure:**
- Test asks: Would customers switch from Product A to Product B if price increased 5-10%?
- For free services (Google Search, Facebook): **What is the price?**
- How to measure effect of price increase on zero-priced service?

**Market Share Issues:**
- Market share calculated on sales basis
- Free services have zero revenue (data collected in exchange)
- How to calculate market share of "free" service?

**Transaction Value Problem:**
- Facebook paid $19 billion for WhatsApp with minimal revenue
- Price reflects data value, not current sales
- Traditional turnover thresholds miss high-value acquisitions

**German Response (2017):**
- Amended merger control thresholds to include transaction value ($400 million) even if turnover not met
- Directly addresses free service valuations

#### 2) Multi-Sided Markets and Network Effects

**Definition:** Platforms matching supply and demand across multiple "sides" (e.g., Uber: drivers + riders, Facebook: users + advertisers).

**Network Effects:**
- **Direct network effects:** More users of platform = more valuable for all users (WhatsApp)
- **Indirect network effects:** More users on one side = more valuable for other side (Airbnb)

**Tipping:**
- Network effects can cause markets to "tip" toward single winner
- Once one platform dominates, competitors cannot attract users ("the winner takes it all")
- Peter Thiel: "Competition is for losers" – reflects Silicon Valley strategy to monopolize markets

**Competitive Implications:**
- Once market tips, effective competition ceases
- Locked-in users generate switching costs
- Data accumulation feeds network effects (more data = better recommendations = more valuable platform)

**Countervailing Factors:**
- **Multi-homing:** Users can maintain profiles on multiple platforms (dating apps)
- **Data portability:** GDPR Article 20 enables users to transfer personal data to competitors
- **Interoperability:** Platform access for third-party developers

#### 3) Loss of Customer Interface

**Problem:** Traditional markets connect supplier directly with customer. In digital markets, platforms control access.

**Gatekeeping:**
- Platform operator sits between supplier and customer
- Controls terms of access, data visibility, pricing visibility
- Can exclude suppliers or discriminate among them

**Implications:**
- Suppliers lose direct market access
- Coordination process disrupted
- Platform has informational advantage (sees all suppliers and customers)
- Market power concentrated at platform layer

**Example:** Amazon Marketplace – sellers dependent on Amazon for access to customers.

#### 4) Algorithms and AI

**Problem:** As machines increasingly make pricing and supply decisions through algorithms, traditional cartel enforcement becomes difficult.

**Scenario - Algorithmic Collusion:**
- Two retailers program pricing algorithms to optimize profit
- Algorithms, given prices of competitor, autonomously determine best price response
- Result: Prices stabilize at high levels (cartel-like outcome)
- But no agreement between retailers; merely independent algorithm optimization
- Detection difficult (no email trails, meetings, or communications)

**Legal Issues:**
- Does Article 101 require **intent to restrict competition**?
- Can machines violate Article 101 without human decision?
- How to prove "meeting of minds" if algorithms autonomously coordinate?

**Regulatory Response:**
- Commissioner Vestager's "antitrust compliance by design"
- May require software design that prevents algorithmic collusion
- Emerging focus on **technological approach** to competition enforcement

#### 5) Market Dynamics and Disruption

**Debate:** Are digital markets self-regulating, or do they require intervention?

**"Disruption" Thesis:**
- Markets supposedly dynamic and contestable ("just one click away")
- Yahoo, Myspace, Nokia, Netscape seemed invincible but declined
- New entrants (initially: Google, Facebook, Amazon) disrupted incumbents
- Regulatory intervention may undermine innovation incentives

**"Lock-In" Counter-thesis:**
- GAFAM companies (Google, Apple, Facebook, Amazon, Microsoft) dominated >10 years
- Not replaced by new entrants despite apparent contestability
- Network effects and switching costs create durable positions

**Market-Making Strategies:**
- Acquisition of nascent competitors (e.g., Facebook acquiring Instagram, Snapchat competitors)
- Copy competing features (e.g., Snapchat Stories → Instagram Stories)
- Financial advantages enabling buy-outs of potential disruptors
- Wealth accumulated through past dominance protects future dominance

**Competition Law Implication:**
- Traditional tools (Articles 101-102, Merger Control) may be necessary to maintain contestability
- Market does not "self-correct" if barriers to entry/competition high
- Intervention justified to preserve competitive process, not to micromanage markets

---

## Case Studies and Practical Application {#case-studies}

### Case 1: Commission v Microsoft (Data Exclusion)

**Scenario:** Microsoft dominates corporate PC operating systems. Introduces new Windows version supporting only its Office software, degrading performance of Google Docs and LibreOffice.

**Analysis Under Article 102:**

**Element 1 - Undertaking:** ✓ Microsoft is undertaking engaged in commercial activities.

**Element 2 - Dominant Position:** ✓ Microsoft has >90% market share in corporate PC OS market. Can act independently of competitors.

**Element 3 - Abuse:**
- Exclusionary abuse: Excludes Google Docs and LibreOffice from corporate market
- Leverages dominance in OS to restrict competition in office software market
- Network effects reinforce exclusion (if locked into Office, harder to switch)

**Element 4 - Effect on Trade:** ✓ Affects multiple Member States.

**Element 5 - No Justification:**
- Microsoft claims: Architectural decisions for better performance/security
- Counterargument: Could achieve goals without excluding competitors
- Microsoft could maintain interoperability with competitors
- Exclusion appears designed to strengthen Office market position, not efficiency

**Likely Outcome:** **Violation of Article 102 TFEU**
- Abuse of dominant position through exclusionary conduct
- Remedy: Requirement to maintain interoperability, possible fine (up to 10% worldwide turnover)

**Legal Precedent:** Similar to actual Microsoft case (COMP/C-3/37.792) addressing refusal to disclose interface information.

### Case 2: Apple/Netflix Merger

**Scenario:** Apple proposes acquiring 55% of Netflix. Apple controls App Store, Apple TV+, hardware. Netflix has vast content library.

**Merger Control Analysis Under EUMR:**

**Element 1 - Concentration:** ✓ Acquisition of control (55% shares).

**Element 2 - EU Dimension:** ✓ Both companies have combined worldwide turnover >>€5 billion, EU-wide revenue >>€250 million.

**Element 3 - SIEC Test:**

**Horizontal Effects (Digital Entertainment/Streaming):**
- Both active in video streaming
- Combined market share in streaming substantial
- Combined Netflix content + Apple ecosystem powerful
- Could raise prices or degrade service quality

**Vertical Effects (Hardware-Software Integration):**
- Apple could pre-install Netflix on hardware
- Could integrate Netflix with Apple ecosystem (Siri, recommendations)
- Competitors (Disney+, Amazon Prime) disadvantaged

**Conglomerate Effects (Leveraging):**
- Apple could leverage hardware dominance (iPhones, iPads) to Netflix advantage
- Preferential treatment in App Store

**Element 4 - Substantial Part:** ✓ Affects EU-wide digital entertainment market.

**Likely Outcome (if notified today): **Likely Approved with Conditions**
- Conditional clearance most probable (similar to Microsoft/LinkedIn)
- **Potential Commitments:**
  - No pre-installation of Netflix on Apple devices
  - Continued access to App Store with neutral terms
  - Maintained interoperability with other streaming services
  - No preferential treatment in Siri recommendations
  - Data silo: Netflix data not integrated with Apple user profiling

**Alternative:** Outright prohibition if competitive concerns too severe, or unconditional clearance if efficiencies substantial.

### Case 3: Meta/TikTok Concerted Practice

**Scenario:** Meta executives meet with TikTok executives. They discuss algorithms, user engagement strategies, and advertising pricing models. Later: "Two giants coming together to make more profit."

**Analysis Under Article 101:**

**Element 1 - Between Undertakings:** ✓ Meta and TikTok are separate undertakings engaged in commercial activities.

**Element 2 - Agreement or Concerted Practice:**
- Explicit agreement unclear (no formal contract signed)
- **Concerted Practice** likely established:
  - Parties revealed competitive strategies to each other
  - Each now aware of other's intended pricing and algorithm approaches
  - Practical cooperation substituted for competitive risk
  - Statements ("two giants making more profit") suggest coordination

**Element 3 - Effect on Trade:** ✓ Affects social media/advertising markets across multiple Member States.

**Element 4 - Effect on Competition By Object:**
- If discussing price coordination in advertising: **Hard-core cartel (by object)**
- If discussing user engagement strategies: May be by object if intent to allocate customers
- **By effect analysis:** Likely coordinated pricing → higher advertising rates, reduced choice, less innovation

**Element 5 - No Justification:** None apparent. Coordination to increase profit is not efficiency-promoting.

**Likely Outcome: **Violation of Article 101 TFEU**

**Liability:**
- Both Meta and TikTok liable as participants in concerted practice
- Each faces fine up to 10% worldwide turnover
- Meta: ~$116 billion annual revenue → fine up to $11.6 billion
- TikTok: ~$15 billion annual revenue → fine up to $1.5 billion

**Individual Liability - Junior Data Analyst Observer:**

**Commission Question:** Would mere observation change liability?

**Legal Analysis:**
- **As observer only:** If analyst truly did not participate, not liable
- **BUT:** Analyst's presence may constitute evidence of meeting
- **Potential liability triggers:**
  1. If analyst participated in discussions (voiced support, contributed to strategy)
  2. If analyst's role was to document/report on coordination
  3. If analyst failed to distance themselves publicly from unlawful conduct
  4. If analyst reported back to superiors with knowledge of coordination

**CJEU Precedent (Eturas Case C-74/14):**
- Mere awareness of competitors' conduct insufficient for liability
- Must demonstrate **active participation** or **failure to distance oneself**
- Presumption of innocence requires clear evidence of complicity

**Conclusion:** Analyst likely **not liable** if true observer and no active participation. However, if pressed in Commission interview, analyst should carefully document:
- Exact role at meeting
- Whether any statements made
- Timing of awareness
- Whether raised concerns about legality

---

## EU vs. US Competition Law {#eu-vs-us}

### Comparative Framework

| Aspect | EU | US |
|--------|----|----|
| **Main Objective** | Internal Market integration + Consumer welfare | Consumer Welfare (strictly economic approach) |
| **Enforcement Mechanism** | Administrative system (Commission decides) | Criminal law + civil enforcement |
| **Enforcement Actors** | European Commission (DG Competition) + National Competition Authorities | Department of Justice (DOJ) + Federal Trade Commission (FTC) |
| **Penalties (Antitrust)** | Up to 10% of annual worldwide turnover | Up to $100 million USD per violation or higher based on damages |
| **Legal Standard (Cartels)** | Automatic prohibition (with narrow exemption) | Rule of reason (requires effects analysis) |
| **Legal Standard (Dominance)** | Abuse must be shown (dominance itself legal) | Monopoly + anticompetitive conduct |
| **Merger Thresholds** | Turnover-based (+ transaction value in Germany) | Turnover-based + Hart-Scott-Rodino review |
| **Economic Approach** | More economic approach (post-2000); consumer welfare focus | Chicago School (per se rules for hardcore cartels); evolving |

### Philosophical Differences

**EU Approach: Internal Market + Structural Protection**
- Competition law serves broader goal of market integration
- Concern for market structure itself (not just price effects)
- Structural remedies acceptable (divestiture, interoperability requirements)
- More interventionist in principle

**US Approach: Consumer Welfare + Chicago School**
- Efficiency and consumer welfare paramount
- Less concern for market structure if consumer welfare advanced
- Behavioral remedies preferred; structural remedies disfavored
- Less interventionist; market generally self-correcting

### Application: Google Shopping Case

**EU (Commission 2017):**
- **Violation Found:** Article 102 TFEU abuse of dominance
- **Rationale:** Leveraging search dominance (>90% market share) to Google Shopping market
- Preferential placement of Google Shopping results
- Demotion of competing comparison shopping services
- **Remedies:** Conduct remedies (listing requirements, non-discrimination), fine €2.42 billion
- **Duration:** Investigation 7 years

**US (Similar Conduct, Different Outcome):**
- **2020:** DOJ filed antitrust suit against Google for search/advertising practices
- **2023:** Case still pending; no final decision
- **Likelihood:** Case may succeed on search market concerns, but shopping service integration harder to challenge
- **US judges more skeptical:** Integration of services may constitute lawful innovation
- **Efficiency argument stronger:** Vertical integration of shopping into search arguably benefits consumers (better results)

### Cooperation: EU-US Coordination

Despite differences, EU and US authorities cooperate on multi-jurisdictional cases:

**Cooperation Agreements:**
- Bilateral Cooperation Agreement (1991)
- Positive Comity Agreement (1998)
- Best Practices Document (2011)

**Mechanism:**
- Authorities share confidential information (within limits)
- Coordinate investigation timing
- Coordinate remedies where possible
- May reach different conclusions on same facts if focusing on different markets

**Divergence Examples:**
- **Facebook/WhatsApp:** EU cleared after long review; FTC separately addressed antitrust concerns through separate privacy action
- **Microsoft/LinkedIn:** EU approved with commitments; US authorities did not challenge
- **Google Search:** EU fined for abuse; US cases progress slowly

---

## Key Takeaways {#conclusions}

### Article 101 TFEU: Anti-Competitive Behaviour

1. **Scope:** Prohibits agreements, decisions, and concerted practices between independent undertakings that restrict competition and affect inter-state trade.

2. **Hard-Core Cartels:** Price fixing, market sharing, bid rigging are per se violations (by object) requiring no effects analysis.

3. **Legal Test:**
   - Between undertakings
   - Agreement/concerted practice
   - Effect on trade between Member States
   - Effect on competition (by object or effect)
   - No valid Article 101(3) exemption

4. **Enforcement:** Fines up to 10% worldwide turnover; private damages actions possible.

5. **Digital Economy Challenges:**
   - Algorithmic coordination difficult to detect
   - Information exchange among competitors increasingly scrutinized
   - Data pools may facilitate collusion or pro-competitive cooperation

### Article 102 TFEU: Abuse of Dominant Position

1. **Scope:** Prohibits unilateral conduct by dominant undertakings that abuses their power.

2. **Special Responsibility:** Dominant firms held to higher behavioral standards; conduct lawful for non-dominant competitors may be abusive.

3. **Legal Test:**
   - Undertaking
   - Dominant position (economic strength enabling independent behavior)
   - Abuse (exclusionary or exploitative conduct)
   - Effect on trade between Member States
   - No objective justification

4. **Categories of Abuse:**
   - **Exploitative:** Excessive prices, unfair terms, discrimination
   - **Exclusionary:** Refusal to deal, predatory pricing, tying, leveraging

5. **Data-Specific Applications:**
   - Refusal to disclose essential data (Microsoft interface information)
   - Denial of data access to foreclosure competitors
   - Leveraging data dominance across markets

### Merger Control

1. **Tool:** Preventive assessment of proposed concentrations before closing.

2. **Test:** Significantly impede effective competition (SIEC) through creation/strengthening of dominant position.

3. **Data Issues:**
   - Quantification challenges for free services
   - Transaction value thresholds needed (Germany: €400 million)
   - Data concentration may trigger concerns even without price effects
   - Commitments can address competitive concerns (interoperability, data silos)

### Data as Competition Concern

1. **Why Data Matters:** Data is critical competitive input; control of data creates market power; data accumulation feeds network effects.

2. **Essential Facility Doctrine:** Dominant firm cannot refuse access to essential data indispensable for downstream competition (Microsoft precedent).

3. **Multi-Sided Markets:** Network effects from data combinations may create tipping; data portability and interoperability become competitive tools.

4. **Emerging Framework:**
   - Traditional tools (Articles 101-102, Merger Control) applied with adaptations
   - Digital Markets Act adds ex-ante obligations for gatekeepers
   - GDPR intersects with competition (privacy as competitive concern)
   - European Commission emphasizing "more technological approach"

### Practical Enforcement

1. **Commission Enforcement:**
   - Investigatory powers: Inspections, document requests, interviews
   - Decisions imposing fines, conduct remedies, structural remedies
   - Appeals to General Court and Court of Justice

2. **National Authorities:** 
   - Apply EU and national competition law
   - Coordinate through European Competition Network
   - Handle smaller cases, local enforcement

3. **Private Enforcement:**
   - Injured parties sue in national courts for damages
   - Facilitated by Directive 2014/104/EU
   - Growing use for follow-on actions after Commission decisions

### Looking Forward

1. **Digital Market Act:** Complements Articles 101-102 with ex-ante regulation of gatekeepers (non-discrimination, interoperability obligations, data access rights).

2. **Data Access Rights:** Emerging principle that competitors may have right to access essential data, balanced against legitimate data protection and IP interests.

3. **Algorithmic Accountability:** Focus on preventing algorithms from facilitating collusion; "antitrust compliance by design" principle.

4. **Cross-Jurisdictional Coordination:** EU and US increasingly interact; differences in approach require companies to satisfy stricter standard (EU).

## Conclusion

Competition law remains fundamental to the functioning of the EU's internal market and protection of consumer welfare. As the digital economy transforms business models and competitive dynamics, Articles 101 and 102 TFEU continue to provide the core legal framework for enforcement, with important adaptations emerging to address data-driven markets, network effects, algorithmic decision-making, and platform gatekeeping.

The tension between **protecting competition as a process** (enabling contestable markets and dynamic innovation) and **intervening to prevent foreclosure/dominance abuses** (protecting consumers from supracompetitive prices and limited choice) remains central to competition law policy. The Digital Markets Act and evolving case law suggest a trajectory toward stronger intervention in digital markets, recognizing that unfettered network effects and data accumulation may require regulatory guardrails to maintain competitive markets.

For businesses, the key takeaway is that competition law applies rigorously to digital platforms and data-driven business models. Companies must:
- Avoid agreements with competitors regarding pricing, output, or market allocation
- Exercise special care with dominant market positions, ensuring conduct does not foreclose competition
- Obtain clearance for significant mergers before closing
- Consider data access and interoperability obligations
- Design compliance programs recognizing algorithmic risks to competition

---

## References

### Primary Sources
- Treaty on the Functioning of the European Union (TFEU), Articles 101-109
- Regulation (EC) No 139/2004 (EC Merger Regulation)
- Digital Markets Act (Regulation (EU) 2022/1925)
- General Data Protection Regulation (GDPR)

### Case Law
- *Microsoft Corp. v. Commission* (COMP/C-3/37.792, 2004)
- *Case C-238/05 Asnef-Equifax* [2006] ECLI:EU:C:2006:734
- *Microsoft/Skype* (Case M.6281)
- *Facebook/WhatsApp* (Case M.7217)
- *Microsoft/LinkedIn* (Case M.8124)
- *Google Shopping* (Case AT.39.740)
- *Case C-74/14 Eturas* [2016] ECLI:EU:C:2016:42

### Secondary Sources
- Podszun, R. & Kreifels, S. "Data and Competition Law" in *Research Handbook in Data Science and Law*
- European Parliament Factsheet on Competition Policy (2024)
- Lecture Materials: "Data and Regulation of Competition" (Merve Oner Kabadayi, TILT, 2025)
- European Commission Guidance on Article 82 Enforcement Priorities (2009)
- European Commission Merger Guidelines

---
# Module 4: Intellectual Property Law & Database Protection – Consolidated Summary

**Module Title:** Intellectual Property Law & Database Protection  
**Instructor:** Dr. Sunimal Mendis, Assistant Professor in Intellectual Property Law, Tilburg University, TILT  
**Date:** 07/10/2025

This consolidated document synthesizes the essential concepts from Module 4, integrating comprehensive coverage of database protection regimes, text and data mining exceptions, and the critical EU legal frameworks governing data use in the digital economy. It combines theoretical foundations with practical implications for artificial intelligence development and data-driven innovation.

---

## Table of Contents

1. [Introduction: Data and IP Law](#introduction)
2. [Foundational Concepts: Data, Information, and IP Protection](#foundations)
3. [The EU Database Directive: Two-Regime Protection](#database-directive)
4. [Copyright Protection of Databases](#copyright-protection)
5. [Sui Generis Database Rights](#sui-generis-right)
6. [Machine-Generated Databases](#machine-generated)
7. [Text and Data Mining (TDM) Under the DSM Directive](#tdm-exceptions)
8. [Contract Law as a Barrier to Data Mining](#contract-law)
9. [Implications for AI and Data-Driven Innovation](#ai-implications)
10. [Key Takeaways and Recommendations](#conclusions)

---

## Introduction: Data and IP Law {#introduction}

### The Central Question

**Does EU IP law allow data mining of non-personal data contained in a database that has been made available to the public?**

This deceptively simple question underlies complex legal, economic, and ethical tensions in contemporary European law. The answer requires navigation through multiple legal regimes, each with different scopes, requirements, and exceptions.

The question is critical for multiple interconnected reasons. Data serves as the raw material for artificial intelligence, and algorithms require enormous volumes of data to train effectively. Start-ups and small or medium-sized enterprises lack the resources to generate equivalent datasets independently, creating a genuine need for data access. Simultaneously, the European Union aims to foster innovation through its Digital Single Market policies, which explicitly prioritize data-driven innovation. Yet this objective must be balanced against the legitimate interests of database creators who have invested considerable resources in data collection and organization and deserve compensation for their efforts. Beyond these economic considerations, there exists a broader public interest in information access, as freedom of information and knowledge dissemination underpin democratic societies and individual development.

### The Fundamental Misconception: "Available ≠ Free to Use"

A critical misunderstanding pervades contemporary data practices: the belief that publicly accessible data can be freely exploited. This conflates five distinct legal and ethical frameworks that operate independently and simultaneously.

Intellectual property law provides the first layer of protection. Data remain protected by copyright and database rights even when publicly visible. A publicly searchable database does not mean the data within it are in the public domain. Copyright law protects databases that demonstrate originality in their selection and arrangement, and the *sui generis* database right extends to protect compilations regardless of originality, provided substantial investment was made in their creation or verification.

Data protection law, particularly the General Data Protection Regulation, provides a second framework. Personal data remain protected even when publicly visible online. Individuals retain fundamental rights over their personal information regardless of whether they posted it on social media or otherwise made it publicly accessible. The right to data protection cannot be waived by publication, and collection of personal data triggers detailed legal obligations on the collector.

Web scraping law under the DSM Directive creates a third framework, though it is more permissive than the first two. The EU Copyright in the Digital Single Market Directive provides limited exceptions to copyright restrictions for text and data mining, but these exceptions contain critical limitations. The exceptions apply only to lawfully accessed content, and right holders can opt-out through machine-readable signals such as robots.txt files. For research organizations, opt-out is not permitted and the exception is mandatory, but for commercial users, the ability to opt-out significantly limits text and data mining freedoms and reduces the practical utility of this exception.

Contract law functions as a fourth framework. Website Terms of Service constitute binding contracts in EU law, and terms prohibiting automated access or data extraction create legal obligations enforceable against users. The landmark *Ryanair v. PR Aviation* case established a particularly important principle: contractual restrictions on scraping even unprotected databases are enforceable, meaning right holders can create contractual protection more extensive than intellectual property law itself permits.

Beyond legal requirements, ethical frameworks establish a fifth dimension. Using data without consent, transparency, or legitimate purpose violates human autonomy and dignity. International frameworks including the EU's High-Level Expert Group Guidelines on AI and the UNESCO Recommendation on AI Ethics emphasize respect for persons and prevention of harm, establishing normative expectations that extend beyond what law formally requires.

---

## Foundational Concepts: Data, Information, and IP Protection {#foundations}

### Distinguishing Data from Information

The Database Directive protects not individual data points but rather compilations—specifically the selection and arrangement of data. Understanding this fundamental distinction is essential to comprehending the entire framework of database protection.

Raw data consists of unrefined, unorganized symbols such as numbers, text, or images that do not inherently carry specific meaning unless they are processed, organized, and structured within a specific context. Individual units of such raw data are generally not protected under intellectual property law because they do not typically qualify as products of human intellect. A single customer name, address, or phone number has no inherent intellectual property protection, and data in isolation are considered common goods that cannot be appropriated.

Information, by contrast, consists of data that has been processed, organized, and structured within a specific context in order to enable analysis and knowledge acquisition. Information and informational goods can be protected under intellectual property rights when human intellectual effort has been invested in their production. Two principal protections apply: trade secrets protect arrangements of data under the Trade Secrets Directive of 2016, and databases protect collections of data under the Database Directive of 1996.

This distinction proves critical for understanding database protection. The law does not protect the individual facts or data points themselves but rather the human creativity, effort, or investment reflected in how those data are selected, arranged, organized, or verified. This means that the same data could potentially be reused if reorganized or presented in a sufficiently different manner, as the protection extends to the database as a compilation rather than to the data as such.

### Criteria for IP Protection

Three foundational requirements must be met for intellectual property protection to attach to any subject matter. First, the subject matter must qualify as a protectable form, such as a literary work, database, or invention that can potentially receive protection. Second, the specific conditions for that particular form of protection must be fulfilled—originality for copyright, novelty and non-obviousness for patents, distinctiveness for trademarks, and so forth. Third, the rights must be properly exercised through appropriate assignment, licensing, or attribution procedures.

These requirements operate together to ensure that intellectual property protection applies only where both the subject matter is appropriate and the legal requirements have been satisfied. This prevents over-protection while ensuring legitimate protectable interests receive legal recognition.

### What Can Be Protected Under IP Law?

Only products of human intellectual effort qualify for intellectual property protection. This fundamental principle means certain categories are necessarily excluded from protection: raw data that remains unprocessed and disorganized, physical objects, natural phenomena occurring without human intervention, and abstract ideas or facts in their isolated form. These exclusions reflect a policy judgment that IP law should protect human creativity and investment, not simply the discovery or documentation of pre-existing facts or phenomena.

What intellectual property law does protect includes original literary, artistic, and scientific expression through copyright, inventions meeting novelty and non-obviousness criteria through patent law, distinctive commercial signs through trademark law, distinctive product designs through design rights, and databases exhibiting either originality in their selection and arrangement through copyright or substantial investment in obtaining, verifying, or presenting their contents through the *sui generis* right. This positive list demonstrates that IP protection extends across creative works, technical innovations, commercial signification, design achievements, and specialized compilations of information.

---

## The EU Database Directive: Two-Regime Protection {#database-directive}

The **EU Directive 96/9/EC on the legal protection of databases** represents a unique European approach to database protection. Rather than adopting a single regime, it establishes **two parallel protection mechanisms**, each addressing different policy objectives.

### Defining a Database (Article 1(2))

A database is formally defined as "a collection of independent works, data or other materials arranged in a systematic or methodical way and individually accessible by electronic or other means." This definition requires four cumulative criteria to be satisfied, and all must be present for something to qualify as a database under the Directive.

First, the subject must constitute a collection or compilation of multiple elements gathered into a coherent whole. Importantly, databases need not contain large numbers of elements or elements drawn from identical sources. A relatively small collection can qualify as a database if the other criteria are satisfied, provided that some assembly of elements has occurred.

Second, the contents must have independence in the sense that each item retains autonomous informative value. The test for independence requires that each data unit retains independent meaning even when separated from the collection as a whole. A decline in informative value after extraction does not negate the independence of an item; what matters is that the item possesses some meaningful value on its own.

Third, these elements must be arranged in a systematic or methodical way, which means the arrangement follows a logical system, plan, or method rather than occurring arbitrarily. The Directive excludes arbitrary, accidental, or hazardous arrangements. Alphabetical, chronological, and logical ordering all satisfy this criterion as they demonstrate methodical organization.

Fourth, independent items must be individually accessible, which means there must exist some means of retrieving any particular item. This might be a search engine for electronic databases, an index for printed materials, a particular plan of organization, or other classification system. The criterion applies to both electronic and non-electronic means of retrieval.

Several familiar examples qualify as databases: e-versions of newspapers and websites, catalogues and address lists, transportation schedules such as flight timetables or television program listings, telephone directories, grids of pharmaceutical results, calendars and agendas, and maps such as those provided by Google Maps. Even social media profiles with structured data can constitute databases. Notably, other materials commonly confused with databases do not qualify. A film like "The Matrix" as watched in a cinema constitutes a single creative work rather than a database. Collections without systematic organization lack the required structure. Collections where items lack independent informative value similarly fail to qualify.

An important limitation deserves emphasis: database protection does not extend to individual units of data contained within the database. However, such content may independently qualify for protection. For instance, individual photographs incorporated into a photography catalogue may themselves be protected by copyright as photographic works even if the database comprising the collection receives only database-level protection. This distinction proves critical when training artificial intelligence models, as doing so requires navigating both database-level intellectual property protections and potentially content-level protections for individual items within the database.

---

## Copyright Protection of Databases {#copyright-protection}

### Subject-Matter and Criteria

Copyright protection applies to original databases. The sole criterion for such protection is originality—specifically, the AOIC (Author's Own Intellectual Creation) standard, which represents a particularly demanding originality test unique to the European legal tradition.

The database must be original "by reason of the selection and/or arrangement of the contents [which] constitute the author's own intellectual creation." This formulation makes clear that protection attaches not necessarily to the content itself but to how the creator chose and arranged that content.

### The AOIC Standard: Two-Part Test

The AOIC standard establishes a demanding two-part test that both creates opportunities for and erects significant barriers to copyright protection of databases.

The first part of the test requires that the creator must have possessed freedom to engage in genuine creative decision-making. The AOIC standard fails when the creation process is dictated by technical considerations, functional requirements, rules or restrictions, or mandatory legal provisions. These constraints eliminate the creative discretion necessary for the AOIC standard because they leave no meaningful space for personal creative choices. To illustrate this principle, consider a database sorted alphabetically or chronologically by necessity or structured according to a mandatory legal format. Such a database would lack originality because the creator had no meaningful creative choice in how to organize the information; technical or legal requirements determined the structure rather than personal creativity.

The second part of the test requires that the creator must have actually exercised this freedom to make personal creative choices, thereby leaving their personal touch on the work. A critical point emerges from jurisprudence on this matter: mere expenditure of skill, labor, and know-how is insufficient to establish the AOIC standard. The Court of Justice of the European Union has explicitly rejected "labor theory" approaches that would give protection based on effort and investment. What matters is not how much effort was expended but whether creative choices were made and whether those choices bear the creator's personal stamp.

To illustrate AOIC fulfillment, consider the Louvre Museum curator who selects 100 paintings from a collection of 300 renaissance portrait paintings based on personal aesthetic judgment and arranges them thematically according to emotional resonance. This curator clearly exercises the AOIC standard because they possessed freedom to choose differently and actually made personal creative choices—a different curator might have selected different works or arranged them differently. The resulting selection and arrangement are stamped with this particular curator's personal touch. By contrast, a database system that includes all available data with no selection or arranges data alphabetically with no creative choices would fail the AOIC standard despite potentially involving great effort.

### Practical Application: Most Databases Lack Copyright Protection

In practical application, the AOIC originality standard proves so demanding that most digital databases fail to qualify for copyright protection, despite potentially involving considerable effort and investment.

Multiple factors combine to create this result. First, digital databases tend to be comprehensive rather than selective in their approach, including all available data rather than curated subsets. Such comprehensive inclusion, while useful for users, demonstrates no creative selection. Second, most databases necessarily follow alphabetical, chronological, or logical ordering to maximize usability and maintainability. While such organization is essential, it does not reflect creative choices and thus lacks the originality required. Third, digital database structure is often determined by technical requirements rather than creative decisions. Databases are designed to be efficiently searchable and organized, which means technical functionality dictates structure. Fourth, standard database structures do not reflect the personal creative touch that the AOIC standard requires; they look like countless other databases because they serve the same functional purpose.

The cumulative result is that many databases that might intuitively seem to deserve protection—particularly those involving substantial investment and effort—fall outside copyright protection because they fail to meet the AOIC originality standard. This gap in copyright protection is precisely what motivated the creation of the *sui generis* database right, which provides protection based on investment rather than creativity.

### Scope of Copyright Protection

Article 5 of the Database Directive specifies the acts that copyright holders can prevent. Copyright holders have exclusive rights to prevent temporary or permanent reproduction in whole or in part, by any means and in any form, whether direct or indirect. This protection extends to copying the database structure and contents, though notably it does not cover mere consultation of publicly available databases. It does cover indirect reproductions such as uploading contents to another system.

Copyright holders may also prevent distribution of the database or copies to the public, including sale, rental, or lending of copies. They can prevent adaptation or modification, which encompasses translation, alteration of structure, or reorganization of contents. Finally, copyright holders may prevent communication, display, or performance to the public, including interactive on-demand transmission or making the database available in such a way that members of the public may access it from a time and place of their choosing. Importantly, communication to a public requires that the transmission be to a "new public"—an audience to whom the right holder did not intend to make the work available.

### Duration of Protection

Copyright protection in databases extends for the lifetime of the author plus seventy years. The protection term is calculated from the first of January of the year following the author's death, which means that databases created by long-lived authors receive protection extending well into the future.

### Ownership

Copyright ownership vests according to Article 4 in either the natural person who carried out the selection and arrangement of contents—the author—or the employer of that person, which may be a natural or legal person such as a company or institution. This dual ownership structure means that for institutional databases such as those created by corporations, universities, or government agencies, ownership typically vests in the institution itself rather than in individual employees who may have performed the creative work.

Multiple joint authors can hold copyright if multiple individuals made creative contributions to the selection or arrangement. This possibility arises because copyright can vest in more than one person if multiple individuals exercise creative choice in the database's creation.

### Infringement Test: Copyright

Determining whether copyright infringement occurs in a database context requires applying a three-step analysis. First, one must establish that the database is actually protected by copyright—that it meets the AOIC originality standard and that protection has not expired. Second, one must determine whether the intended act falls within the scope of copyright protection as defined above—whether it constitutes reproduction, distribution, adaptation, or communication to the public. Third, one must establish whether authorization has been granted or whether a legal exception permits the act. An act is lawful only if the copyright owner has licensed it or if a legal exception explicitly permits it.

---

## Sui Generis Database Rights {#sui-generis-right}

### Context and Rationale

The *sui generis* database right ("of its own kind") was introduced in the Database Directive to address a gap in copyright protection. Recognizing that many valuable databases lack copyright protection (because they lack originality), the EU created this novel right to protect investment in database creation.

**Justification:** Database creation requires substantial investment of financial resources, human effort, and expertise. Copyright alone didn't adequately incentivize production, particularly of non-original but valuable databases.

### Preliminary Conditions (Article 11)

Access to *sui generis* protection is conditioned on the database maker being from certain jurisdictions. Only specific entities can benefit from this protection.

Natural persons must either be EU citizens or maintain habitual residence in EU territory. This requirement ensures that EU residents are protected but excludes third-country nationals unless they have established EU residence.

Legal persons such as companies and firms must satisfy two cumulative conditions. First, they must be formed in accordance with the law of an EU Member State, meaning they must be properly established under EU law. Second, they must have their central administration or principal place of business within the EU territory. This second requirement is particularly important because it ensures that the company's operations are genuinely linked to the EU economy on an ongoing basis. A company registered in the EU but operating exclusively outside the EU would not qualify, as its economic operations lack the necessary EU connection. This dual condition reflects a policy judgment that the protection should benefit entities whose economic interests are substantially aligned with the EU.

**Effect:** Non-EU entities and companies with only tangential EU connections cannot obtain *sui generis* protection.

### Subject-Matter and Criteria (Article 7)

The *sui generis* right extends to any database, whether original or non-original. The criterion for protection is the presence of substantial investment in obtaining, verifying, or presenting the database's contents. Unlike copyright, which requires creative originality, the *sui generis* right protects investment, and investment can take multiple forms.

Investment can be financial, such as spending money to acquire data. It can be material, such as acquiring specialized equipment for data collection. It can be human, consisting of spending time, energy, and effort. Expertise and specialized knowledge also constitute investments. The Directive does not further define the threshold for investment to qualify as "substantial," and to this day, the Court of Justice has not provided binding guidance on what constitutes substantiality. This absence of clear definition means national courts interpret the requirement, creating some uncertainty. However, scholarly consensus suggests the threshold for substantiality is relatively low compared to other IP standards. A moderate investment may often suffice, and both small and large investments can be substantial depending on context and industry.

The Directive specifies three types of qualifying investments. Obtaining refers to seeking out and collecting existing data to be included in the database. A critical distinction must be drawn between investments made in collecting existing materials, which qualifies for protection, and investments made in creating materials, which does not. A company spending money to purchase viewership data from media research companies makes a qualifying investment in obtaining data. A company spending money to create television program schedules does not make a qualifying investment in obtaining data but rather invests in creating the underlying material.

Verification refers to monitoring the accuracy of gathered materials to ensure the reliability of database contents. This monitoring can occur at creation, during the database's operation, or afterward. Verification includes checking, correcting, and updating contents to maintain reliability and completeness. Regular quality checks and systematic updates all constitute verification investments.

Presentation refers to the organization of gathered materials, which encompasses structuring the database and implementing electronic or other means enabling individual item accessibility. Creating an index system, implementing search functionality, or organizing data hierarchically all represent presentation investments.

### Substantiality of Investment

The question of what constitutes "substantial" investment is critically important and persistently contested. The Directive provides no definition, and the Court of Justice has offered limited guidance on the question, choosing instead to allow national courts to determine substantiality in context.

The CJEU has distinguished between quantitatively and qualitatively substantial investments. Quantitatively substantial investments are measured in quantifiable resources such as time and money spent. Qualitatively substantial investments are measured in non-quantifiable resources such as energy, effort, and expertise. The Court has not established a bright-line threshold for either measure, leaving considerable discretion to national tribunals.

The resulting situation creates both advantages and disadvantages. On one hand, flexibility allows assessment to reflect industry context and database type. On the other hand, the absence of certainty creates unpredictability for database makers and users. Generally, scholarly consensus suggests the substantiality threshold for *sui generis* protection is relatively low compared to originality standards for copyright. A moderate investment often suffices, and both large and small investments can be deemed substantial depending on context. This relatively low threshold means a significant proportion of databases obtain *sui generis* protection compared to copyright protection.

The British Horseracing Board case illustrates the practical application. BHB organizes horse races, which requires substantial investment of approximately €4 million annually in registering owners, trainers, jockeys, and horses, deciding which horses enter each race based on weight and handicapping, and compiling race lists. The CJEU held that these investments, while substantial, constituted investments in creating data through the actual organization of races rather than investments in obtaining pre-existing data. Therefore, despite the substantial financial investment, the database failed to qualify for *sui generis* protection because the investment was in the wrong category.

This distinction between creating and obtaining data prevents what scholars call "spin-off" databases from obtaining *sui generis* protection. Databases generated as by-products of other activities cannot claim protection based on the investment in creating the underlying activity. A TV program schedule generated by a TV station, a flight schedule generated by an airline, or a delivery route generated by a logistics company all constitute spin-offs. They are valuable databases, but they were not created through collecting pre-existing data; rather, they were created through the primary business activity. This limitation attempts to balance the rights of data creators against the risk that essential business data would become locked behind database protection.

### Scope of *Sui Generis* Rights (Article 7)

The *sui generis* right holder enjoys two exclusive forms of protection. The first is the right to prevent extraction, which concerns the transfer of all or a substantial part of database contents from one medium to another. Extraction encompasses both physical copying and electronic transfer, as well as indirect extraction that occurs when contents are accessed through on-screen visual consultation and then transferred. The substantiality requirement for extraction is measured on both qualitative and quantitative bases—qualitatively by considering the scale of investment in the extracted materials, and quantitatively by assessing the volume of data removed.

The second exclusive right is re-utilization, which prevents making available all or a substantial part of database contents to the public. Re-utilization covers numerous forms of public access, including distribution and sale of copies, lending arrangements, communication and display to the public, and performance or adaptation of the database contents. The Directive uses intentionally expansive language to capture "any new forms of making available" that might emerge as technology evolves.

A particularly important provision addresses repeated and systematic extraction. Even if individual extractions are not substantial in themselves, the right extends to prevent this pattern when repeated and systematic extraction either conflicts with the normal commercial exploitation of the database or unreasonably prejudices the legitimate interests of the database maker. This provision creates significant uncertainty for AI and data mining applications. An algorithm that iteratively processes a protected database to identify patterns and extract training data may not extract a substantial portion in any single operation, yet the cumulative effect of many systematic extractions could theoretically violate the right. The legal status of algorithmic mining remains unresolved, creating a critical ambiguity for AI developers.

### Duration of Protection

The *sui generis* right extends for an initial term of fifteen years, measured from 1 January of the year following the database's completion. This timing mechanism means a database completed on November 1, 2024 receives protection beginning January 1, 2025, while one completed on January 2, 2024 receives the same initial protection period, effectively meaning different temporal lengths depending on completion date.

The most distinctive feature of *sui generis* protection is the rolling renewal mechanism. Any substantial change to the database contents requiring substantial new investment triggers a fresh fifteen-year protection period from the date of that change. A database that receives regular updates—additions of new records, deletions of outdated information, rearrangement of existing data, or verification of accuracy—can thus enjoy effectively perpetual protection. This open-ended term reflects policy recognition that database maintenance is itself an investment-generating activity, distinct from copyright's author-centric duration measures.

### Ownership

The *sui generis* right vests in the "maker" of the database—defined as the person responsible for the substantial investment in obtaining, verifying, or presenting the contents. This differs fundamentally from copyright ownership, which vests in the author. The database maker can be either a natural person or a legal person, meaning corporations and other entities can own *sui generis* rights. The right does not extend to authors or creative contributors unless they are also responsible for the substantial investment in the database compilation itself. An author who contributes creative expression within an authored entry owns copyright in that entry, while a corporation that collected all such entries into a protected database owns the *sui generis* right in the compilation.
- Different from copyright, which vests in the author

---

## Machine-Generated Databases {#machine-generated}

### Definition and Characteristics

Machine-generated databases are created, updated, and managed primarily through automated processes and machines, including Internet of Things (IoT) devices operating with minimal or no human intervention. These databases are fundamentally different from traditional databases in their operational characteristics and behavioral patterns.

Machine-generated databases are distinctively dynamic, with data continuously or periodically collected, modified, and updated through automated systems. They exhibit high velocity, with data generation occurring in real-time or near-real-time. The structural organization of these databases may itself evolve automatically, adapting its format and organization as new types of data arrive or as processing requirements change. Furthermore, machine-generated databases typically operate at massive scale, involving extraordinarily large volumes of data that human operators could not feasibly manage or comprehend.

Practical examples include sensor data aggregated from extensive IoT networks, real-time traffic or weather data continuously updated from distributed measurement systems, satellite imagery databases that receive new imagery on regular schedules, and transactional databases from e-commerce systems that record millions of transactions daily.

### The Conceptual Problem

A fundamental difficulty arises when attempting to apply *sui generis* protection to machine-generated databases: the distinction between "creating" and "obtaining" data becomes profoundly blurred. The entire framework of *sui generis* rights depends on this distinction—investment in obtaining pre-existing data deserves protection, while investment in creating data does not. Yet in automated data generation contexts, machines actively produce data rather than passively collect it, rendering the distinction meaningless.

Scholars diverge sharply on the appropriate response to this conceptual crisis. Gervais (2019) argues that "big data corpora are neither 'obtained' nor 'collected'; they are generated by the machine," contending that machines actively generate data rather than passively collecting it. This perspective, if accepted, would wholly undermine the obtaining-versus-creating distinction that forms the conceptual foundation of *sui generis* protection. Under this reading, machine-generated databases should not qualify for protection because the investment is in creation, not obtaining.

An alternative scholarly view, articulated by Leistner, posits that infrastructure investment could justify *sui generis* protection for machine-generated databases. Under this theory, substantial investment in technological infrastructure—AI systems, data aggregation platforms, data cleaning processes—might constitute sufficient investment in the "presentation" of data to merit protection. The infrastructure investment in organizing and making data accessible, rather than the original collection, could be deemed substantial enough to warrant protection. This approach would extend *sui generis* rights to machine-generated databases where significant technological infrastructure was required to generate and manage the data.

### Observed vs. Generated Data

A potentially meaningful distinction can be drawn between two categories of machine-generated databases based on their epistemological character. Observed data refers to databases where machines record objectively appreciable occurrences that exist independently of the measurement system—for instance, satellite observations that detect naturally occurring phenomena. In these cases, one could argue the machines are "obtaining" data by recording objective facts, and the *sui generis* framework might extend protection to investment in the observation and recording infrastructure.

In contrast, generated data refers to databases where machines produce data as a primary output with no independent objective reality—for instance, algorithmic outputs or computational results. Here, the data is genuinely "created" by the machine's operations rather than "obtained" from pre-existing sources. Algorithmic outputs would not exist without the machine's generation process, making them conceptually and factually distinct from observed data. This distinction, while theoretically elegant, remains difficult to apply consistently. Many databases combine observed and generated components, or sit in ambiguous territory where it is unclear whether the machine is observing or generating.

### The EU Data Act Exclusion

Rather than resolve this conceptual uncertainty through case law development, EU legislators took a definitive policy stance. Article 35 of the EU Data Act explicitly excludes machine-generated data from *sui generis* protection by providing that "the *sui generis* right provided for in Article 7 of Directive 96/9/EC shall not apply when data is obtained from or generated by a product or related service falling within the scope of this Regulation."

The legislative rationale, articulated in Recital 84, explains this choice as addressing a specific regulatory risk: "In order to eliminate the risk that holders of data in databases obtained or generated by means of physical components, such as sensors, of a connected product and a related service or other machine-generated data, claim the *sui generis* right under Article 7 of Directive 96/9/EC, and in so doing hinder in particular the effective exercise of the right of users to access and use data and the right to share data with third parties under this Regulation, it should be clarified that the *sui generis* right does not apply to such databases."

This legislative choice produces a significant effect: databases of machine-generated data cannot benefit from *sui generis* protection, removing potential legal barriers to data access and reuse in IoT and connected device contexts. The underlying policy judgment reflects legislative intent that machine-generated databases should not become bottlenecks restricting data-driven innovation. While this resolves the immediate legal uncertainty, it represents a policy choice to facilitate data access over compensating those who invest in creating the infrastructure that generates data.

---

## Text and Data Mining (TDM) Under the DSM Directive {#tdm-exceptions}

### Overview: Two Exceptions for Two Purposes

The **Directive (EU) 2019/790 on copyright and related rights in the Digital Single Market (DSM Directive)** introduced two mandatory text and data mining exceptions to copyright and the *sui generis* database right. These exceptions reflect different policy objectives:

- **Article 3:** Secure scientific research through data mining (unwaivable exception)
- **Article 4:** Foster commercial innovation through data mining (waivable exception)

### Definition: Text and Data Mining (Article 2(2))

"Any automated analytical technique aimed at analysing text and data in digital form in order to **generate information** which includes but is not limited to **patterns, trends and correlations**."

**Application to AI:** This definition clearly encompasses machine learning processes:
- Training machine learning models on text/data is automated analytical technique
- The purpose is generating information (patterns, training signals, model weights)
- The process involves analyzing digital data to extract correlations

**Conclusion:** Text and data mining as defined in the DSM Directive includes AI training.

### The Three-Step Process in Data Mining

Data mining as a practical process unfolds through three distinct operational stages, each with separate IP implications. The process begins with preparation, which involves identifying, copying, and loading data into a dataset suitable for analysis. Preparation encompasses data collection from one or more sources, format conversion to machine-readable or analyzable formats, and data preprocessing or transformation to remove inconsistencies or prepare data for algorithmic processing. This stage triggers potential copyright reproduction rights and *sui generis* extraction rights, as data is being copied into a new medium or structure.

The second stage is extraction, where algorithms are executed on the prepared dataset. This stage involves running analytical or learning algorithms, identifying correlations and patterns within the data, and processing information to extract meaningful insights. During extraction, the original data undergoes algorithmic transformation, potentially triggering continued copyright reproduction rights and *sui generis* extraction rights as the algorithm accesses and processes database contents.

The final stage is recombination, where processed data is rearranged to visualize and present results to human audiences. This involves reorganizing the algorithmic outputs into human-interpretable format, generating output suitable for publication or further use, and storing or disseminating the results. The recombination stage may trigger *sui generis* re-utilization rights if the organized results are made available to the public, as well as potential copyright issues if the organized presentation constitutes a sufficiently original arrangement of information.

### Article 3: Mandatory Exception for Scientific Research

#### Beneficiaries: Qualified Organizations and Institutions

Article 3 restricts the exception to two specific classes of organizations, reflecting policy choices to prioritize publicly-funded research over commercial research operations.

Research organizations constitute the primary beneficiary class. Article 2(1) defines qualifying research organizations as entities whose primary goal is conducting scientific research, or whose primary goals encompass both educational activities and scientific research. These organizations must satisfy one of two operational criteria to qualify for protection. They either operate on a non-profit basis without generating surplus revenues, or they carry out a public interest mission formally recognized by their member state. The Directive indicates that public interest missions can be evidenced through public funding, public contracts explicitly specifying the mission, national law provisions establishing the mission, or organizational bylaws requiring that all profits be reinvested in scientific research. Additionally, research organizations must not fall under the decisive influence of commercial undertakings that would gain preferential access to research results. This control limitation prevents commercial entities from obtaining preferential benefits through shareholding or membership relationships that would grant them special access to research findings. Typical qualifying organizations include universities, public research institutes, government laboratories, and public hospitals.

Cultural heritage institutions constitute the second beneficiary class, as specified in Article 2(3). These are publicly accessible libraries or museums, archives, or film and audio heritage institutions. The Directive requires these entities to be institutional organizations dedicated to cultural heritage preservation and access, not commercial providers of content.

The restriction to these specific organizational types reflects a clear policy choice: only non-commercial organizations with public missions qualify for the mandatory exception. Commercial research organizations, private companies, and for-profit enterprises fall outside the scope, regardless of whether their research serves societal benefits.

#### Scope of Article 3

Qualifying research organizations and cultural heritage institutions receive two primary permissions under Article 3. First, they may make reproductions and extractions of lawfully accessible databases, whether protected by copyright or *sui generis* database rights. This permission removes the prohibition on copying and extraction that would normally apply to protected materials, allowing researchers to prepare datasets for analysis without seeking authorization.

Second, these organizations may store reproductions and extractions for scientific research purposes. This storage right is particularly important for research integrity. Storage can be retained long-term with appropriate security measures and is recognized as necessary for verification of research results. Notably, the Directive places no temporal limitation on storage duration, meaning research organizations can maintain their datasets indefinitely for verification and archival purposes. This extended storage right reflects the reality that scientific research often requires long-term data retention to enable reproducibility checks and validation by other researchers.

#### Conditions and Requirements

Two principal conditions must be satisfied for Article 3 to protect research activities. First, the beneficiary organization must have lawful access to the database on which text and data mining will be performed. Recital 14 clarifies that "lawful access" encompasses access through contractual arrangements such as subscriptions or licenses, content freely available online without access restrictions, or access granted based on the rightholder's explicit or implicit consent. This requirement prevents the exception from becoming an avenue to access restricted materials. If an organization has no legitimate right to access a database, the exception does not extend to that organization.

Second, the text and data mining must be conducted for purposes of scientific research. Recital 12 defines scientific research broadly to encompass both natural and human sciences, with the understanding that the research contributes to the existing state of science and applies scientific methods for the advancement of human knowledge. This purpose requirement excludes uses driven by commercial objectives or purposes unrelated to knowledge creation, even if the data mining process itself would otherwise qualify.

#### Contractual Override: Unwaivable Exception

Article 7 of the DSM Directive provides that any contractual provision contradicting Article 3 is categorically unenforceable. Rightholder cannot restrict text and data mining by research organizations through terms of service, license agreements, or other contractual means. This unenforceability of restrictive contractual terms ensures that even if a database is provided subject to a license that prohibits reproduction and extraction, research organizations can nevertheless conduct text and data mining for scientific purposes.

#### Limitations of Article 3: Non-Commercial Restriction

Despite its strong language guaranteeing access for research, Article 3 contains a critical shortcoming that limits its practical scope for AI development. The exception extends exclusively to non-commercial research. This limitation creates significant barriers for companies, start-ups, and mixed public-private research initiatives that combine for-profit and non-profit objectives.

Research organizations that participate in public-private partnerships face particular constraints. If a for-profit partner is involved, the research organization must exclude that partner from preferential access to research results. This requirement may actively deter partnerships between research organizations and commercial AI companies seeking to apply research findings. Start-ups and small and medium enterprises cannot benefit from the exception unless they partner with a qualifying research organization, and even then, they cannot exploit the research results for commercial purposes without obtaining separate authorization from rightholders.

The practical effect is to create a clear division: innovative applications with commercial purposes, even if those applications serve important societal benefits, fall outside the scope of the mandatory exception. A research organization could use Article 3 to train models for fundamental research, but a company using identical technical processes for commercialization would lack protection. Recital 11 acknowledges that research organizations may use private sector technological tools through partnerships, provided the for-profit entity does not obtain preferential access to research results. However, arranging such partnerships to satisfy this requirement typically requires sophisticated contractual arrangements and creates significant administrative burden for small research teams.

### Article 4: General Exception for Text and Data Mining

#### Beneficiaries: Unlimited and Inclusive

Article 4 removes the organizational restrictions present in Article 3 and extends protection to any person with lawful access to the database. This unlimited scope includes commercial entities seeking data mining for profit, small and medium enterprises developing new technologies, individual researchers and journalists gathering information, consumer associations analyzing business practices, and even competitors of the database holder seeking competitive intelligence through automated analysis. The expansive language emphasizes that Article 4 does not care about the applicant's commercial status, institutional affiliation, or end use.

#### Scope: Broader Acts but Temporary Storage

Article 4 permits both reproductions and extractions of lawfully accessible subject matter, whether protected by copyright or *sui generis* database rights. Users can copy the database and extract portions of its contents for text and data mining purposes.

However, Article 4 imposes a critical temporal limitation that distinguishes it from Article 3's generous storage provisions. Reproductions and extractions may be retained only for the duration necessary for purposes of text and data mining. Once the mining process is complete and any results have been generated, continued retention is prohibited. This temporary storage requirement prevents users from maintaining long-term copies of databases for potential future use, unlike Article 3's allowance of indefinite retention for verification purposes. The practical implication is that commercial data miners must design their systems to delete copies after processing, while research organizations may maintain permanent archives.

#### Purpose: Any Imaginable Use

Unlike Article 3's restriction to scientific research, Article 4 allows text and data mining for any purpose whatsoever. Recital 18 explicitly states that the exception covers "development of new applications or technologies," signaling that commercial innovation and profit-seeking enterprises receive protection. This broader purpose allows AI development to proceed without purpose-based restrictions, whether the application is research, commercial, or hybrid.

#### Lawful Access Requirement

Like Article 3, Article 4 requires that users have lawful access to the database before mining. Recital 14 clarifies that lawful access encompasses three situations: access based on contractual arrangements such as subscriptions or licenses; content freely available online without access barriers; and content made available with the explicit or implicit consent of the rights holder. This requirement prevents Article 4 from becoming a mechanism for circumventing access controls or obtaining unauthorized database access through automated means.

#### The Critical Opt-Out Provision: Rightholder Override

Article 4(3) permits rightholders to express a reservation restricting the exception through what the Directive terms "appropriate manner." For publicly available online content, machine-readable format is required. Recital 18 provides examples of appropriate machine-readable means, including metadata tags, robots.txt files, terms and conditions pages on websites or services, and standard technical protection measures. For non-publicly available content provided through restricted access, other means suffice, including contractual agreements and unilateral declarations.

The opt-out provision fundamentally alters the practical utility of Article 4 for commercial data mining. Unlike the mandatory exception in Article 3 where contractual terms cannot override the exception, Article 4 allows rightholders to prevent text and data mining through multiple routes: including anti-scraping terms in website terms of service, adding robots.txt file prohibitions preventing automated access, adding metadata opt-out signals to digital files, or including contractual restrictions in license agreements. This waivable structure means the exception functions as a default rule subject to rightholder override rather than a guarantee of access.

The practical effect is particularly significant for commercial data mining. Rightholders can effectively opt-out of the Article 4 exception for any publicly available content by adding appropriate signals. A data mining company scraping a website in violation of robots.txt files or terms of service violates Article 4, as the opt-out signals remove protection. This aspect creates substantial uncertainty for commercial ventures, as determining whether data sources have expressed opt-out reservations requires continuous monitoring of evolving terms, metadata, and technical signals.

#### Permitted Security Measures

Article 3(3) permits organizations to implement security measures to protect networks and databases against abuse or unauthorized access. These security measures must be proportionate and limited to what is strictly necessary to protect system security and database integrity. Security measures cannot exceed the scope necessary to protect the systems from attack or misuse, nor can they be used for purposes unrelated to security or for pure commercial advantage. This provision recognizes that while users receive TDM permissions, those permissions do not extend to systems abuse, network disruption, or unauthorized access beyond the specified permitted uses.

### Comparison: Article 3 vs. Article 4

| Aspect | Article 3 (Scientific Research) | Article 4 (General TDM) |
|--------|--------------------------------|------------------------|
| **Beneficiaries** | Research organizations, cultural heritage institutions | Any person with lawful access |
| **Purpose** | Scientific research only | Any purpose (including commercial) |
| **Storage** | Long-term retention permitted (for verification) | Only as long as necessary for TDM |
| **Contractual override** | No opt-out allowed (unwaivable) | Opt-out possible (waivable) |
| **Practical utility** | Strong protection for academic research | Limited by opt-out possibilities |
| **AI application** | Academic AI research beneficial | Commercial AI development less protected |

### Data Mining Barriers and Legal Framework

Even with the DSM Directive's Article 3 and Article 4 exceptions, data miners face multiple legal barriers that can prevent or restrict data mining activities. Understanding these barriers requires recognizing the distinct legal risks present at each stage of the mining process.

The first barrier involves copyright in the database structure itself. The Database Directive Article 5 protects the selection and arrangement of data by copyright when this arrangement constitutes the author's own intellectual creation. Protected databases cannot be reproduced without authorization, meaning that copying the entire database or a substantial portion for mining purposes infringes even if the underlying data elements are not themselves protected.

The second barrier is the *sui generis* database right. Article 7 of the Database Directive grants database makers the exclusive right to prevent extraction or re-utilization of the whole or a substantial part of the database contents. The repeated and systematic extraction provision creates particularly acute uncertainty for algorithmic mining, where iterative access might accumulate to substantial taking without any single access being substantial.

The third barrier involves trade secret protection. Databases may be protected as trade secrets under EU and national law, particularly when they provide competitive advantages and are subject to reasonable confidentiality measures. This protection prevents disclosure of the database's contents, structure, or organization, thereby preventing the data mining that requires knowing what data exists and how it is organized.

The fourth barrier, and most practically significant for commercial purposes, involves contractual restrictions. Article 7(5) of the DSM Directive explicitly permits rightholders to opt-out of Article 4's general exception, and databases commonly come with terms of service or license agreements prohibiting automated access or data extraction. These contractual restrictions are enforceable against users, creating legal barriers even when copyright or database rights might permit the same conduct.

#### Step-by-Step Analysis: When Does TDM Infringe?

**Stage 1: Copying and Loading Data**

*Potential IP infringement:* Copyright reproduction right, *sui generis* extraction right

**At preparation stage, if database is protected:**
- Copyright: Copying entire database or substantial parts = reproduction
- *Sui generis:* Transferring substantial part to new system = extraction
- **Exception**: Article 3/4 may permit if conditions met

**Stage 2: Running Algorithm**

*Potential IP infringement:* Continued extraction/reproduction through iterative processing

**At extraction stage:**
- Copyright: May involve further temporary copies in algorithm processing
- *Sui generis:* Iterative data access may constitute repeated extractions
- **Complex issue**: Does cumulative extraction of many insubstantial parts equal substantial extraction?

**Stage 3: Publishing Results**

*Potential IP infringement:* Re-utilization right, communication to public

**At recombination stage:**
- Copyright: Less likely to infringe (results typically don't reproduce database structure)
- *Sui generis:* Re-publication of results unlikely to constitute re-utilization of original database

### The "Lawful Access" Requirement

#### The CJEU Framework for Lawful Access

Court of Justice case law from *ACI Adam* (C-435/12) and *Copydan* (C-463/12) establishes a two-part test for determining whether a user has lawful access to copyrighted material or protected databases. The first test examines source legitimacy: content made available with the rightholder's explicit or implicit consent constitutes lawful access, while content made available without rightholder's consent raises presumptions of unlawful access. This distinction operates regardless of whether the content is technically accessible online.

The second test examines user knowledge and good faith: when content is available without rightholder's authorization, users who knew or should have known of this unauthorized availability are presumed to engage in unlawful use, while users acting in genuine good faith without actual or constructive knowledge may escape legal liability. The crucial implication is that the presumption operates differently for commercial and non-commercial users.

Commercial entities mining data face a rebuttable but strong presumption of knowledge when the source is unauthorized. Courts presume that profit-making businesses either know or should know whether they are accessing databases with permission. This presumption reflects the rationale that commercial entities have incentives and resources to verify legitimacy. In contrast, non-commercial actors and academic users may more easily demonstrate good faith and lack of knowledge regarding the legitimacy of their access sources, creating a distinction in practical enforceability against commercial versus non-commercial mining.

#### Application to Online Databases

The practical implication for databases made available online depends on whether they were made available with rightholder consent. Databases made available with such consent—including open access databases, licensed subscription services, and freely accessible websites—generally constitute lawful access for text and data mining. Users of these databases can safely conduct mining activities.

However, databases available online without the database maker's consent present more complex legal terrain. These databases remain unlawful sources for most users, though exceptions exist for non-commercial good faith users who acted without knowledge of the unauthorized nature. Commercial users accessing such databases face strong presumptions of knowledge and face liability for unauthorized use, making commercial mining of unauthorized online databases risky.

---

## Contract Law as a Barrier to Data Mining {#contract-law}

### The Critical Ryanair Judgment (CJEU C-30/14, 2015)

#### Factual Background

**Ryanair** operates low-cost airline services. Its website contains a database of:
- Flight schedules
- Routes
- Real-time pricing

**PR Aviation** operated a price-comparison website. It:
- Accessed Ryanair's website
- Used automated systems (screen scraping) to extract flight data
- Aggregated data from multiple airlines
- Allowed consumers to compare prices

**Ryanair's terms of service stipulated:**
- "Use only for private, non-commercial purposes"
- "Screen scraping for commercial purposes prohibited unless written license obtained"

#### Ryanair's Claims

Ryanair sued for:
1. Copyright infringement in the database
2. *Sui generis* database right infringement
3. Breach of contract

#### The CJEU Ruling

**Key holdings:**

1. **Ryanair's database was NOT protected** under the Database Directive
   - Failed to meet AOIC originality standard (copyright)
   - Failed to show substantial investment qualifying for *sui generis* right

2. **Database Directive exceptions don't apply** to unprotected databases
   - Article 6 lawful user rights only apply to protected databases
   - If database unprotected, no mandatory exceptions apply

3. **Contractual restrictions are enforceable**
   - Even though database is unprotected by IP law, rightholder may contractually restrict use
   - Freedom of contract governs unprotected databases
   - Website terms of service create binding contractual obligations

#### The Profound Implications

**Recital 39-40 language:**

> "...it is clear from the purpose and structure of Directive 96/9 that Articles 6(1), 8 and 15 thereof, which establish mandatory rights for lawful users of databases, are not applicable to a database which is not protected either by copyright or by the *sui generis* right under that directive, so that it does not prevent the adoption of contractual clauses concerning the conditions of use of such a database."

**Conclusion:** Where Database Directive protection doesn't apply, contract law fills the gap. Righthholders can contractually prevent reuse even of unprotected databases.

### Contractual Restrictions on Protected Databases

#### When Database Directive Protections Apply

**Article 8 DB Directive:** Contractual terms **cannot** override mandatory rights of lawful users of protected databases.

**Effect:** If database is protected by copyright or *sui generis* right, contractual terms claiming to restrict lawful user rights are **unenforceable**.

**Implication:** Rightholder cannot use contract to eliminate statutory rights.

#### When Contractual Terms Bind

**For optional exceptions** (not mandatory):
- Copyright private copying exception
- Scientific research exception (optional under DB Directive, though Article 3 DSM makes mandatory)
- Public security exception

Rightholder **can** contractually override these optional exceptions.

**For unprotected databases** (no IP protection):
- Full contractual freedom applies
- Rightholder can impose any contractual restrictions
- Terms of service are enforceable

### "Private Legislation" and the Public Domain Problem

#### The Ryanair Effect: Privatizing the Public Domain

The Ryanair judgment enables a paradoxical outcome:

1. Database lacks protection under IP law (correctly so, as it doesn't meet statutory criteria)
2. Therefore, it would normally remain in public domain (free to reuse)
3. BUT rightholder can contractually restrict reuse
4. Result: De facto private control over ostensibly public-domain data

This has been criticized as creating "private legislation" that:
- Bypasses legislative intent (Database Directive protects only specific categories)
- Creates stronger protection contractually than IP law permits
- Fragments the public domain
- Varies enforcement across Member States (depending on contract law interpretation)

#### Enforceability Variations

Following Ryanair, national courts have reached **opposite conclusions** on enforceability:
- **Ireland:** Contractual restrictions enforceable
- **Spain:** Not enforceable
- **Germany:** Not enforceable

This variation undermines Digital Single Market objectives.

### Contract as a Compliance Tool

Even where prohibited, contracts remain the **practical compliance mechanism:**

**Many organizations rely on:**
- Terms of service to define permitted uses
- License agreements to specify data mining restrictions
- User authentication to enforce access controls
- Technical measures combined with contractual terms

**Effect:** Contractual scaffolding often controls access to data regardless of underlying IP law.

### Interactions with DSM Directive Exceptions

#### Article 3 (Scientific Research)

**Exception is unwaivable** – contract cannot override Article 3 exception

**Implication:** Restrictive license terms cannot prevent research organizations from TDM for scientific purposes

#### Article 4 (General TDM)

**Exception is waivable** – rightholder can opt-out through machine-readable means

**Practical result:**
- Website terms of service can prohibit commercial TDM
- Robots.txt can signal opt-out
- Metadata can restrict mining
- Contractual restrictions take precedence

**Effect:** Most commercial right holders have effectively prohibited Article 4 TDM through opt-outs.

---

## Implications for AI and Data-Driven Innovation {#ai-implications}

### The Data Bottleneck for AI Development

#### Why Data Access Matters for AI

**Three fundamental requirements for effective AI:**

1. **Volume:** Large datasets required for statistical significance and pattern detection
2. **Quality:** Accurate, complete, representative data
3. **Diversity:** Data spanning multiple contexts, demographics, scenarios

**Practical reality:** AI systems trained on:
- Inadequate data = poor performance
- Biased data = biased results
- Limited data = narrow applicability

#### The SME/Start-up Challenge

Small and medium enterprises face critical barriers:

**Resource constraints:**
- Cannot generate equivalent-scale proprietary data
- Cannot invest in large-scale data collection
- Cannot negotiate high-value licensing deals

**Competitive disadvantage:**
- Large companies accumulate data advantages
- Network effects entrench dominance
- Market concentration increases

**Innovation consequences:**
- Reduced competition in AI development
- Higher barriers to market entry
- Reduced diversity of AI applications

### Current Legal Framework: Summary of Barriers

#### Four-Tier Barrier System

#### Specific Barriers to AI Training

**Stage 1: Data acquisition**
- Copying databases may infringe copyright (reproduction right)
- Accessing protected databases may infringe *sui generis* (extraction)
- Contracts may prohibit collection

**Stage 2: Data processing**
- Format conversion may constitute reproduction
- Algorithm training may involve repeated access
- Storage of training data may implicate *sui generis* rights

**Stage 3: Model deployment**
- Re-utilizing insights from database may infringe *sui generis* right
- Publishing results may require licensing

**Stage 4: Model updates**
- Retraining on new data
- Continuous mining for model improvement

### The DSM Directive Exceptions: Incomplete Solutions

#### Article 3 Benefits for Research Organizations

**Strengths:**
- Unwaivable protection for scientific research
- Permits long-term data storage
- Covers both copyright and *sui generis*

**Limitations for commercial AI:**
- Excludes for-profit entities
- Requires public interest mission
- Public-private partnerships complex

**Result:** Academic research benefits significantly, but commercial innovation partially excluded.

#### Article 4 Limitations for Commercial Users

**Strengths:**
- Covers any purpose (including commercial AI)
- Unlimited beneficiaries

**Critical weakness:**
- Waivable by rightholder opt-out
- Most publishers have opted-out
- Machine-readable restrictions easy to implement
- Commercial mining essentially prohibited for major databases

**Result:** Commercial TDM remains heavily restricted despite Article 4 exception.

### Unresolved Issues

#### The Machine-Generated Data Question

**Current status:**
- No *sui generis* protection for MGD (by Data Act Article 35)
- But copyright may still apply to structured databases
- Contract law may restrict access

**For AI:**
- IoT and sensor data become more accessible (no *sui generis*)
- But copyright protection remains
- Contractual restrictions still apply

#### The Repeated and Systematic Extraction Problem

**Article 7(5) *sui generis* provision unresolved:**
- Does iterative AI model training constitute prohibited extraction?
- Cumulative small extractions = substantial?
- Does "unreasonably prejudicing legitimate interests" apply?

**Current uncertainty:**
- National courts may differ in interpretation
- Some may permit mining despite provision
- Others may prohibit based on cumulative extraction theory

#### The Originality/Investment Thresholds

**Existing problems:**
- Databases easily obtain *sui generis* protection
- Rolling 15-year protection terms
- AOIC standard hard to meet but occasionally invoked

**For AI impact:**
- Most crawled databases likely have *sui generis* protection
- Long-term protection creates durability of barriers
- Copyright protection supplementary

### Recommendations: Toward Balanced Framework

Based on comprehensive analysis, authorities and scholars propose:

#### Option 1: Extend Article 4 Exception

**Make Article 4 TDM exception mandatory** (unwaivable like Article 3)

**Advantages:**
- Ensures consistent access for commercial innovation
- Aligns with DSM objective to foster innovation
- Simpler implementation

**Challenges:**
- Conflicts with three-step test (TRIPS/Berne)
- May threaten publisher business models
- May not overcome contract law barriers to unprotected databases

#### Option 2: Reform Sui Generis Right

**Possibilities:**

a) **Registration system:** Require registration for *sui generis* protection
   - Clearer identification of protected databases
   - Time-limited renewals (not indefinite rolling protection)
   - Higher transaction costs

b) **Reduced duration:** Shorten initial term or renewal period
   - Reduces long-term barriers
   - Creates entry points for new data mining

c) **Abolition:** Remove *sui generis* right entirely
   - Aligns with evidence it hasn't increased database production
   - Removes major barrier to data reuse
   - BUT removes protection for legitimate database investment

#### Option 3: Data User Rights

**Introduce unwaivable user rights:**

a) **Right to reuse non-personal data** from publicly disclosed databases
   - Unwaivable by contract
   - Applies even to unprotected databases
   - Reverses *Ryanair* effect

b) **Sector-specific access rights**
   - Conditional access to essential databases
   - Similar to FRAND licensing in patents
   - Applied to strategic data holders

c) **Data access rights for public interest**
   - Compulsory licensing for essential data
   - Public health, climate, safety applications
   - Proportionate compensation

#### Option 4: Hybrid Approach

Combine multiple measures:
- Make Article 4 unwaivable for commercial AI (balancing copyright interests)
- Introduce user rights for unprotected databases (reverse *Ryanair*)
- Reform *sui generis* for rolling protection (limit duration)
- Create sector-specific access rights for strategic data

---

## Key Takeaways and Recommendations {#conclusions}

### The Fundamental Tension

EU database protection law reflects an unresolved tension between:
- **Rights holders:** Deserve protection for investment
- **Data users:** Require access for innovation
- **Public interest:** Depends on both protection and access

The current framework tilts toward rights holders, potentially at cost to innovation and public welfare.

### Essential Concepts

**1. Data ≠ Information**
- Individual data points are generally unprotected
- Collections (databases) can receive dual protection
- Information goods reflect human intellectual effort

**2. Database Directive: Two Regimes**
- **Copyright:** Protects original databases (selection/arrangement)
  - High threshold (AOIC), but long duration (life + 70 years)
- **Sui generis:** Protects database investment (obtaining/verifying/presenting)
  - Lower threshold (substantial investment), but medium duration (15 years)
  - Both can apply to same database simultaneously

**3. TDM Exceptions: Asymmetric Protection**
- **Article 3:** Unwaivable exception for research organizations
  - Strong protection for academic research
  - Does not include commercial entities
- **Article 4:** Waivable exception for anyone
  - Theoretically broad, but practically limited
  - Right holders have effectively opted-out

**4. Contract Law: The Final Barrier**
- Unprotected databases can be contractually restricted (*Ryanair*)
- Creates de facto protection stronger than IP law permits
- Fragments Digital Single Market across national jurisdictions

### Practical Implications for AI Development

**For Academic Research:**
- Article 3 exception provides strong protection
- Can mine copyrighted and *sui generis* protected databases
- Long-term storage permitted for verification
- Non-commercial limitation significant but workable through partnerships

**For Commercial Innovation (Start-ups/SMEs):**
- Article 4 exception available but largely waivable
- Most publisher databases opted-out
- Must negotiate individual licenses (high cost)
- Unprotected databases remain subject to contract law restrictions
- Significant competitive disadvantage vs. large data collectors

**For Large Corporations:**
- Can afford licensing deals
- Can generate proprietary data at scale
- Article 4 restrictions less limiting
- Data monopolies potential

### Need for Reform

**Current evidence suggests:**
- *Sui generis* protection hasn't increased database production (Commission evaluations)
- Rolling protection creates indefinite barriers
- Article 4 waivability undermines innovation goal
- Contract law *Ryanair* effect fragments public domain

**Recommendation:** Balanced reform combining:
1. Mandatory Article 4 exception (unwaivable)
2. *Sui generis* reform (time limits or registration)
3. User rights for unprotected databases
4. Sector-specific access rights for strategic data
5. Preserved protection for legitimate investment

### Strategic Note on AI Development

The DSM Directive represents an important but **incomplete solution** to AI data access challenges. Its provisions:

**Do help with:**
- Academic research (Article 3)
- Use of open access materials
- Clear opt-out mechanisms enabling informed choice

**Do not adequately address:**
- Commercial AI innovation (Article 4 waivable)
- Start-up/SME competitiveness
- Unprotected database access (*Ryanair* problem)
- Rolling *sui generis* protection indefinitely

**Future policy** should balance protection of investment with innovation imperative, recognizing that:
- Data drives 21st-century innovation
- AI development depends on data access
- Europe competes globally on innovation capacity
- Current framework may disadvantage EU innovation relative to US/China

---

## References and Further Reading

### Primary EU Legal Instruments

- **Directive 96/9/EC** on the legal protection of databases (Database Directive)
- **Directive (EU) 2019/790** on copyright and related rights in the Digital Single Market (DSM Directive)
- **Regulation (EU) 2018/1807** on a framework for the free flow of non-personal data
- **Regulation (EU) 2016/679** General Data Protection Regulation (GDPR)
- **Directive (EU) 2015/2366** on Trade Secrets Protection

### Key CJEU Cases

- **C-203/02, BHB v William Hill** (2004) – *Sui generis* protection criteria
- **C-30/14, Ryanair v PR Aviation** (2015) – Contractual protection of unprotected databases
- **C-435/12, ACI Adam** (2014) – Lawful access requirement
- **C-463/12, Copydan** (2015) – Knowledge presumption for commercial users

### Recommended Academic Sources

- **Dr. Sunimal Mendis** – MENDIS_IP & Data Driven Innovation_Slides
- **Romain Meys** – "Data Mining Under the Directive on Copyright and Related Rights"
- **Tatiana Synodinou** – "Ryanair v PR Aviation: Contracts, Rights and Users"
- **Bernt Hugenholtz** – "The New Copyright Directive: Text and Data Mining"

---

**Last Updated:** November 3, 2025  
**Repository:** Innovation and Regulation (JBL110)  
**Status:** Consolidated Summary Complete

# Module 5: AI and Data Regulation – Consolidated Summary

**Module Title:** AI and Data Regulation  
**Instructor:** Avv. Chiara Gallese Nobile, Ph.D., CIPP/E, MSCA, Tilburg University, TILT  
**Date:** 07/10/2025

This consolidated document synthesizes the essential concepts from Module 5, integrating comprehensive legal frameworks, regulatory requirements, and practical guidance on bias and fairness assessment. It combines the depth of the extensive lecture materials with visual representations to support understanding of complex topics.

---

## Table of Contents

1. [Introduction: The Data Collection Crisis](#introduction)
2. [GDPR Foundational Principles](#gdpr-foundations)
3. [The EU AI Act Risk-Based Framework](#eu-ai-act)
4. [AI Ethics and Trustworthy AI](#ai-ethics)
5. [Bias, Fairness, and Data Quality](#bias-fairness)
6. [Practical Implementation and Case Studies](#practical)
7. [Key Takeaways](#conclusions)

---

## Introduction: The Data Collection Crisis {#introduction}

### Recent High-Profile Cases and the Pattern of Wrongdoing

The foundation of machine learning is data, yet the methods for collecting and using this data remain fraught with legal and ethical pitfalls. Three major companies—**IBM**, **ClearviewAI**, and **OpenAI**—serve as cautionary tales of wrongful data practices.

**IBM's Case: Biometric Data Scraping**

IBM scraped the web indiscriminately to collect random people's images to train facial recognition systems without consent or transparency. This processing of biometric data violated Article 9(1) of the GDPR (special categories of personal data), lacked transparency under Article 5(1)(a), and had no valid legal basis under Article 6.

**ClearviewAI: Facial Recognition for Law Enforcement**

ClearviewAI aggregated billions of images scraped from social media into a massive facial recognition database sold to law enforcement. This created systems designed to enable mass surveillance and uniquely identify natural persons through biometric means—a practice now explicitly banned under the EU AI Act. The company faced a €20 million GDPR fine in Europe.

**OpenAI: ChatGPT and Mass Data Scraping**

OpenAI scraped the web indiscriminately, collecting personal data, copyrighted texts, and code. This violated the **purpose limitation principle** (Article 5(1)(b) GDPR)—data collected for one purpose being used for another—and lacked transparency and valid legal basis. Italy became the first Western nation to ban ChatGPT in March 2023, citing GDPR violations.

**Common Pattern:** Unlawful data scraping, lack of transparency, and unauthorized use of protected materials.

### The Misconception: "Publicly Available" ≠ "Public Domain"

A fundamental misunderstanding underlies these violations: the belief that publicly accessible data can be freely used. In reality, five distinct legal and ethical frameworks govern online data use.

#### 1. Copyright Law

Publicly visible content remains copyrighted. This includes logos, databases, text, images, videos, software code, and graphics. Using copyrighted material to train AI without authorization constitutes copyright infringement, even if the content is publicly accessible on a website. Disney+ images, for example, are visible but protected by copyright.

#### 2. Data Protection Law (GDPR and Convention 108+)

Personal data of living persons remain protected even when publicly visible. Names, email addresses, photos on websites are covered by the General Data Protection Regulation (applicable in the EU across 27 Member States) and Convention 108+ (applicable in 55 countries). The fact that someone has made their information public on social media does not waive their data protection rights.

#### 3. Web Scraping Laws (DSM Directive)

The **Directive (EU) 2019/790 on copyright and related rights in the Digital Single Market** provides an exception for text and data mining (TDM) from copyright restrictions, but with a critical opt-out mechanism. Rights holders can exclude their content by specifying restrictions in machine-readable formats (e.g., `robots.txt` files, HTML meta tags). Importantly, this exception does NOT apply to commercial AI training.

#### 4. Contract Law

Website Terms of Service constitute binding contracts that can explicitly prohibit automated data collection and scraping. Violating these terms creates contractual liability. The landmark case **LinkedIn Corp. v. hiQ Labs Inc.** emphasized that breach of contractual scraping prohibitions can create legal liability, separate from criminal law considerations.

#### 5. Ethics

Beyond legal requirements, ethical principles establish that using data without consent, information, or for potentially harmful purposes violates human autonomy and dignity. International frameworks (EU AI HLEG Guidelines, UNESCO Recommendation on AI Ethics, OECD AI Principles) emphasize respect for human autonomy, prevention of harm, fairness, and transparency.

### Legal Precedents in Web Scraping

**Ryanair v. Volagratis/Lastminute (EU)**

Price-comparison websites scraped flight information from Ryanair's database. The court ruled that scraping was lawful because Ryanair's database lacked "creative intellectual contribution" and the purpose (price comparison) had consumer protection rationale. However, **this case does not apply to AI training**, which is a fundamentally different purpose.

**LinkedIn Corp. v. hiQ Labs Inc. (US)**

hiQ scraped public LinkedIn profiles for business analytics. The legal battle highlighted the tension between public data access and contractual terms. The final ruling emphasized **contract liability**: violating a website's user agreement that prohibits scraping creates legal liability, separate from criminal law considerations.

**Ryanair DAC v. Booking Holdings Inc. (US)**

Under the Computer Fraud and Abuse Act, scraping publicly available information without authentication (passwords) is not a violation. However, cease-and-desist letters can withdraw authorization to access protected (authenticated) portions of websites.

---

## GDPR Foundational Principles {#gdpr-foundations}

### The Hierarchical Nature of Legal Instruments

The GDPR does not exist in isolation. Legal instruments are arranged hierarchically, from highest to lowest authority:

1. International Conventions and Treaties (e.g., European Convention on Human Rights, Convention 108+)
2. EU Primary Law (EU Treaties, Charter of Fundamental Rights)
3. EU Secondary Law (GDPR, Directives)
4. National Constitutions
5. National Implementing Laws
6. National Administrative Regulations

When conflicts arise, higher-ranking instruments prevail. The GDPR, as an EU Regulation, has direct effect across all Member States but must be interpreted in light of the Charter of Fundamental Rights.

### Scope and Core Definitions

#### When the GDPR Applies

The GDPR applies when:
- A data controller or processor is established in the EU (regardless of where processing occurs)
- Activities target subjects located in the EU (even if the controller is outside the EU)
- Competent authorities process data for non-law-enforcement purposes

**Data subject's nationality does not matter.** What matters is whether they are in the EU or targeted by services.

**When the GDPR does NOT apply:**
- Personal or household activities (e.g., personal photos on a private device)
- Law enforcement processing for criminal purposes (covered by separate LED Directive)
- EU institutions' activities (covered by separate Regulation 2018/1725)

#### Personal Data (Article 4(1))

"Personal data" means any information relating to an identified or identifiable natural person. This encompasses:

- **Biometric data**: Photos, fingerprints, video recordings
- **Genomic data**: DNA sequences, genetic markers
- **Profiling**: Habits, preferences, shopping/viewing patterns
- **Identifiers**: Nicknames, usernames, device IDs
- **Location data**: GPS coordinates, home addresses
- **Opinions**: Religious beliefs, philosophical beliefs
- **Feelings**: Emotional states, burnout information
- **Financial information**: Income, credit reliability

Personal data can be in **any format**, including mathematical representations (embeddings, vectors in machine learning models).

#### Processing (Article 4(2))

Processing encompasses virtually any action taken with data:
- Collection, recording, organization, storage
- Modification, analysis, deletion
- Sharing, dissemination, access through VPN
- **Training a machine learning model**
- **Reading or consulting data**

**Critical point:** Data collection for AI is a form of processing, so GDPR applies from the moment data gathering begins.

### The Seven GDPR Principles (Article 5)

The GDPR is built on seven core principles that govern all data processing:

**1. Lawfulness, Fairness, and Transparency (Article 5(1)(a))**

Processing must have a valid legal basis, be fair to the data subject, and be transparent. In machine learning:
- Ensure you have the right to use the data
- Respect applicable licenses
- Inform data subjects how their data is used
- Provide accessible privacy notices

**2. Purpose Limitation (Article 5(1)(b))**

Data must be collected for specified, explicit, and legitimate purposes and not further processed in incompatible ways. You cannot collect data "just in case." If collected for one purpose (e.g., customer support), using it for AI training requires justification that the new purpose is compatible or a new legal basis.

**3. Data Minimization (Article 5(1)(c))**

Only data strictly necessary for each specific purpose should be collected. Avoid over-collection. For AI training, this means carefully selecting which attributes are essential to the model's purpose.

**4. Accuracy (Article 5(1)(d))**

Personal data must be kept correct and up-to-date. Inaccurate data must be rectified or erased. This is particularly important for AI, as inaccurate training data propagates errors through the model.

**5. Storage Limitation (Article 5(1)(e))**

Data should be kept in a form permitting identification of data subjects for no longer than necessary. For AI, this may mean securely deleting training data once models are deployed, or having clear retention policies.

**6. Integrity and Confidentiality (Article 5(1)(f))**

Data must be processed with appropriate security measures protecting against unauthorized or unlawful processing, accidental loss, destruction, or damage. This includes technical measures like encryption and organizational measures like access controls.

**7. Accountability (Article 5(2))**

The data controller is responsible for demonstrating compliance with all principles. This requires:
- Documentation of processing activities (Records of Processing, Article 30)
- Data Protection Impact Assessments (Article 35) when required
- Compliance monitoring and reporting

### Legal Basis for Processing (Article 6)

Processing is only lawful when a valid legal basis exists. Six bases are available:

1. **Consent (Article 6(1)(a))**: The data subject has freely given, specific, informed, and unambiguous consent. For special categories of data, consent must be explicit. Consent can be withdrawn at any time.

2. **Contract (Article 6(1)(b))**: Processing is necessary to perform a contract or prepare to enter into one.

3. **Legal Obligation (Article 6(1)(c))**: Processing is required by EU or national law.

4. **Vital Interests (Article 6(1)(d))**: Processing is necessary to protect vital interests (life, health) of the data subject or another person.

5. **Public Task (Article 6(1)(e))**: Processing is necessary for a task carried out in the public interest or official authority function.

6. **Legitimate Interest (Article 6(1)(f))**: Processing is necessary for legitimate interests pursued by the controller or a third party, except where such interests are overridden by the interests, rights, and freedoms of the data subject. This requires a Legitimate Interest Assessment (LIA) balancing controller interests against data subject rights.

For AI development, **Legitimate Interest** and **Consent** are most commonly used for training on public datasets.

### Special Categories of Data (Article 9)

Article 9 generally prohibits processing of eight special categories of personal data:

1. Racial or ethnic origin
2. Political opinions
3. Religious or philosophical beliefs
4. Trade union membership
5. Genetic data
6. **Biometric data for identification purposes**
7. Health data
8. Sex life or sexual orientation data

These categories receive heightened protection because of their sensitivity and potential for discrimination.

**Exceptions** allowing processing include:
- Explicit consent
- Employment and social security law obligations
- Vital interests (life or health protection)
- Manifestation of publicly shared data
- Legal claims
- Public health interests
- Archiving, research, or statistical purposes

**Critically for AI:** Article 9(2)(h) allows processing of special categories when "necessary for the purposes of the preventive or occupational medicine, for assessing the working capacity of the employee... or for monitoring and improving performance at work" under appropriate safeguards.

Furthermore, the AI Act allows processing of special categories for **bias monitoring, detection, and correction** when strictly necessary and proportionate—providing organizations a substantial basis to audit their systems for discriminatory impacts.

---

## The EU AI Act Risk-Based Framework {#eu-ai-act}

The **EU AI Act**, the world's first comprehensive AI regulation, takes a **risk-based approach** to governance. Rather than applying identical rules to all AI systems, it classifies systems into four tiers based on the risk they pose to safety, fundamental rights, and democratic values.

### Defining AI Systems (Article 3)

An AI system is a "machine-based system designed to operate with some degree of autonomy and that can, for explicitly defined or learned objectives, generate outputs such as content, predictions, recommendations or decisions influencing the physical or virtual environments."

This broad definition captures most machine learning systems, from recommender algorithms to large language models to computer vision systems.

### Four-Tier Risk Classification

#### Tier 1: Unacceptable Risk (Prohibited)

These AI systems are deemed a clear threat to safety, livelihoods, and fundamental rights. They are **outright banned**:

**1. Real-Time Remote Biometric Identification in Public Spaces**

AI systems that perform real-time remote biometric identification of individuals in publicly accessible spaces by law enforcement are prohibited. This targets mass surveillance technologies (e.g., ClearviewAI) that can enable discriminatory policing and undermine freedom of assembly.

Narrow exceptions exist for:
- Targeted search for specific individuals (wanted for serious crime)
- Prevention of imminent threats
- Scientific research under strict conditions

**2. Social Credit Systems**

AI systems that assign "social scores" to individuals or groups by public authorities, leading to discriminatory treatment, are banned. These systems risk enabling Orwellian surveillance and punishment based on algorithmic judgment.

**3. Subliminal Manipulation**

AI systems designed to deploy subliminal techniques—often imperceptible to humans—to distort behavior and decision-making. This includes dark patterns, deepfakes for disinformation, and psychological manipulation.

**4. Exploitation of Vulnerable Groups**

AI systems that exploit vulnerabilities of specific groups (children, elderly, persons with disabilities) to distort their behavior in ways harmful to their interests.

#### Tier 2: High-Risk Systems

These systems are not banned but subject to stringent requirements before deployment. High-risk systems include those used in:

- **Biometric Identification and Categorization**: Systems identifying or categorizing individuals based on biometric data (fingerprints, facial features, gait)
- **Critical Infrastructure Management**: Systems controlling essential services (transportation, energy, water)
- **Education and Vocational Training**: Systems determining educational placement or training opportunities
- **Employment and Workers Management**: Recruitment, performance evaluation, promotion systems
- **Access to Essential Public and Private Services**: Credit scoring, insurance, housing, healthcare eligibility
- **Law Enforcement**: Predicting criminal offenses, assessing risk, guidance for investigations
- **Migration and Asylum Administration**: Assessing applications, determining eligibility
- **Administration of Justice**: Supporting judicial decisions, case outcome prediction
- **Biometric Processing**: Registration or verification of biometric data

#### Tier 3: Limited Risk

Systems with limited risk require **transparency obligations**:

- **AI-Generated Content Disclosure**: Users must be informed when interacting with AI systems (e.g., chatbots) or when content is AI-generated (deepfakes, synthetic media)
- **Recommendation Systems**: Systems recommending content must disclose their operation and allow user control

#### Tier 4: Minimal or No Risk

The vast majority of AI systems fall here (spam filters, game AI, autocomplete) and face no additional obligations beyond general GDPR compliance.

### Mandatory Requirements for High-Risk AI Systems (Articles 8-15)

The AI Act imposes seven core requirements for high-risk systems:

**1. Risk Management System (Article 9)**

A continuous process throughout the system's lifecycle to:
- Identify potential risks and hazards
- Analyze and evaluate identified risks
- Implement risk mitigation measures
- Monitor effectiveness of mitigation
- Reassess risks continuously

**2. Data and Data Governance (Article 10)** ★ *Most critical for bias mitigation*

Training, validation, and testing datasets must be:
- **Relevant**: Suited to the intended purpose
- **Representative**: Covering relevant populations and use contexts
- **Free of errors**: Accurate, with quality checks
- **Complete**: Sufficient data without systematic gaps

Datasets must be examined for:
- **Possible biases**: Systematic disparities by protected characteristics
- **Discrimination risks**: Features that could enable unfair treatment
- Specific context in which the AI will operate

**Critically:** The Act allows processing of special categories of personal data (ethnicity, health data, etc.) when strictly necessary for **bias monitoring, detection, and correction**—providing a substantial public interest legal basis for auditing systems for discriminatory impacts.

**3. Technical Documentation (Article 11)**

Comprehensive documentation must be maintained demonstrating:
- System description and intended purpose
- Training data characteristics and sources
- Data preprocessing steps
- Validation and testing methodologies and results
- Performance metrics and limitations
- Human oversight measures
- Post-deployment monitoring plans

**4. Record-Keeping (Logs) (Article 12)**

Systems must automatically log events to ensure traceability of operation, including:
- Usage events and decisions
- Error events
- Performance variations
- Maintenance and updates
- User interactions and feedback

**5. Transparency and Provision of Information (Article 13)**

Users and affected parties must receive clear information:
- That they are interacting with an AI system
- The system's intended purpose
- Capabilities and limitations
- Expected accuracy and failure modes
- Restrictions on use
- Rights and remedies available
- How to contact responsible persons

**6. Human Oversight (Article 14)**

Systems must be designed to enable meaningful human control:
- Humans "in the loop" during decision-making
- Humans must understand system operations and recommendations
- Humans must be able to override, stop, or refuse system outputs
- Override mechanisms must be accessible and effective

**7. Accuracy, Robustness, and Cybersecurity (Article 15)**

Systems must be:
- **Accurate**: Correct outputs within specified tolerance levels
- **Robust**: Resilient against errors, faults, and anomalies
- **Cybersecure**: Protected against unauthorized alteration, manipulation (data poisoning, adversarial attacks)

---

## AI Ethics and Trustworthy AI {#ai-ethics}

Beyond legal compliance, international frameworks establish ethical principles for trustworthy AI. The **AI HLEG (High-Level Expert Group) Guidelines** and **UNESCO Recommendation on AI Ethics** define seven ethical principles:

### The Seven Ethical Principles

**1. Human Agency and Oversight**

AI systems should support human autonomy and enable meaningful human control. Humans should remain "in the loop" with ability to understand, contest, and override AI decisions. AI should enhance human capabilities rather than replacing human judgment entirely.

**2. Technical Robustness and Safety**

AI systems must be reliable, accurate, and resilient. They should fail gracefully and include safeguards against misuse. Security against adversarial attacks and data poisoning is essential.

**3. Privacy and Data Governance**

AI development requires careful data governance ensuring GDPR compliance, data minimization, and protection of sensitive information. Privacy by design and default should be embedded from the outset.

**4. Transparency**

AI systems should be explainable and transparent. Users should understand:
- That they are interacting with AI
- How the system makes decisions
- What capabilities and limitations exist
- What data it uses

**5. Accountability**

Clear responsibility chains must exist for AI systems. Organizations should be able to explain and justify decisions, with documented processes and external auditing where appropriate.

**6. Fairness and Non-Discrimination**

AI systems must not discriminate based on protected characteristics. This requires:
- Identifying discrimination risks early
- Testing models for disparate impact across groups
- Implementing bias mitigation techniques
- Continuous monitoring post-deployment

**7. Social and Environmental Well-being**

AI should contribute positively to society and the environment. Systems should be assessed for:
- Societal impact (access, equity, inclusion)
- Environmental sustainability (energy use, resource consumption)
- Long-term beneficial effects

---

## Bias, Fairness, and Data Quality {#bias-fairness}

A central challenge in AI governance is addressing bias. Biased AI systems can perpetuate and amplify existing societal inequities, leading to ethical harms, legal violations, and loss of public trust.

### Defining Bias: The Friedman & Nissenbaum Framework

Researchers Batya Friedman and David Hendry Nissenbaum define three types of bias in computer systems:

**Type 1: Preexisting Bias**

Societal bias that exists before AI systems are built and is reflected in historical data. For example, if women were historically excluded from certain professions, training data from those professions will show gender imbalance. The algorithm learns this historical bias from the data.

*Example:* Amazon's hiring algorithm learned historical gender bias from decades of hiring data where men dominated technical roles, leading the system to downrank women applicants.

**Type 2: Technical Bias**

Bias introduced by technical choices in system design:
- Data collection methodology
- Feature selection and engineering
- Algorithm choice
- Training data split (train/test)
- Hyperparameter tuning
- Decision thresholds

*Example:* Facial recognition systems trained primarily on light-skin tones often fail dramatically on dark-skin faces. This technical bias arose from dataset composition choices, not societal bias per se.

**Type 3: Interaction Bias**

Bias that emerges from how humans interact with and use AI systems:
- User misunderstanding of system capabilities
- Gaming the system (e.g., manipulating inputs to get desired outputs)
- Feedback loops (system predictions affecting reality, creating new biased data)
- Context drift (system trained on one context, deployed in another)

*Example:* Predictive policing systems create feedback loops. If the system recommends more police presence in low-income neighborhoods, more arrests occur there, which the system interprets as confirmation that the area is "high crime," reinforcing the prediction.

### Why Bias Matters

**Ethical Harm:** Biased AI systems perpetuate inequality and harm individuals' life chances. Discrimination in hiring, lending, criminal justice, or healthcare can devastate lives.

**Legal Risk:** Biased AI violates non-discrimination laws (EU Equal Treatment Directives, Title VII in the US, national laws). Regulators are increasingly holding companies liable for algorithmic discrimination.

**Economic and Reputational Cost:** Flawed decision-making leads to poor outcomes. Public discovery of bias causes reputational damage and loss of trust, threatening business viability.

**Systemic Amplification:** Bias in AI can amplify societal inequities over time through feedback loops. A system that sends more police to certain neighborhoods creates more arrests there, "confirming" the system's biased prediction and justifying continued overpolicing.

### Bias and the EU AI Act

The AI Act explicitly addresses bias in several provisions:

- **Recital 33:** "AI systems should be designed and developed in a way that respects... the principle of non-discrimination" and should be tested for "bias during the design phase and bias mitigation measures."
- **Article 10:** High-risk AI must examine training data for "possible biases" and discrimination risks.
- **Article 15:** Systems must monitor for errors and anomalies that could indicate emerging bias.

### Assessing Data Quality: The FAnFAIR Framework

The **FAnFAIR Framework** (Fuzzy Approach to Fairness Assessment in Datasets) provides a structured method for assessing dataset fairness across six dimensions:

**1. Balance (Class Imbalance)**

Are classes/groups evenly distributed? Severe imbalance (e.g., 99% negative examples, 1% positive) causes models to perform poorly on minority classes.

**2. Numerosity (Sample Size)**

Are there sufficient samples for learning? Each group/class should have adequate representation for the model to learn reliable patterns.

**3. Unevenness (Distributional Consistency)**

Is the distribution of attributes uniform across demographic groups? Uneven distribution (e.g., age varies more in one gender group) can lead to disparate impacts.

**4. Compliance (Constraint Satisfaction)**

Do values conform to specified constraints? Invalid or spurious values (e.g., age = 999) degrade data quality.

**5. Quality (Accuracy and Consistency)**

Are records complete and accurate? Errors, inconsistencies, and missing values in training data propagate through models.

**6. Incompleteness (Missing Data)**

What proportion of values are missing? High missingness can bias estimates and reduce model reliability.

### Practical Case Study: Bias in Pharmaceutical Research

A compelling example of bias cascades involves pharmaceutical research:

**The Problem:** Historically, clinical trials excluded minorities, women, and elderly persons. Drug efficacy and dosing were developed based on predominantly white male populations.

**The Cascade:**
1. **Biased Data Collection** → Trials excluded minorities
2. **Biased Training Data** → Models learned from unrepresentative data
3. **Biased Model Deployment** → Dosing/efficacy determined by majority group data
4. **Biased Health Outcomes** → Minorities receive suboptimal treatment
5. **Feedback Loop** → Poor outcomes attributed to other factors, bias perpetuated
6. **Cycle Repeats** → Bias embedded in future research

This demonstrates how bias in data collection creates cascading harms throughout a system's lifecycle.

### Data Balancing and Preprocessing Techniques

When datasets exhibit class imbalance, several techniques can rebalance them:

**Oversampling Minority Classes**
- Random duplication: Simply repeating minority class examples
- SMOTE (Synthetic Minority Over-sampling Technique): Generating synthetic examples via interpolation
- ADASYN (Adaptive Synthetic Sampling): Adaptively emphasizing harder cases
- Risk: Overfitting to minority class patterns

**Undersampling Majority Classes**
- Random removal: Randomly discarding majority class examples
- Stratified sampling: Removing examples while maintaining distribution properties
- Near-miss: Removing examples near decision boundaries
- Risk: Information loss

**Synthetic Data Generation**
- Generative models: Using GANs or VAEs to create realistic synthetic examples
- Copulas: Statistical models capturing dependencies between variables
- Domain-based generation: Creating examples aligned with domain knowledge
- Advantage: Realistic, diverse examples without information loss

### Machine Learning Lifecycle with Fairness Checkpoints

Fairness is not a one-time consideration but requires monitoring throughout the ML lifecycle:

**Stage 1: Define Objectives**
- Identify protected characteristics (race, gender, age, disability, etc.)
- Consider all stakeholders affected
- Define fairness criteria appropriate to context
- Establish fairness metrics to track

**Stage 2: Acquire and Explore Data**
- Use tools like FAnFAIR to assess data fairness
- Audit data for bias across demographic groups
- Check representativeness (all relevant populations included)
- Apply data balancing if severe imbalance detected

**Stage 3: Model and Train**
- Test model performance separately for each demographic group
- Check for disparate impact (unequal error rates across groups)
- Use fairness-aware algorithms that incorporate fairness constraints
- Monitor feature importance to identify proxies for protected attributes

**Stage 4: Interpret and Communicate**
- Explain model limitations and failure modes
- Communicate bias risks to stakeholders
- Discuss mitigation strategies undertaken
- Disclose discrimination risks to end users

**Stage 5: Implement and Maintain**
- Monitor performance by demographic group post-deployment
- Collect user feedback about fairness
- Retrain when performance disparities emerge
- Conduct regular fairness audits

---

## Practical Implementation and Case Studies {#practical}

### Case Study: Mozilla Common Voice Dataset

The Mozilla Common Voice project aims to create an open-source speech dataset for training speech recognition systems. The project revealed fairness challenges:

**Bias Issue:** Early versions of the dataset showed underrepresentation of certain accents and languages, leading to speech recognition models that worked well for English speakers with standard accents but poorly for speakers of other languages or non-standard accents.

**Resolution:** Mozilla actively worked to recruit speakers from underrepresented linguistic communities, achieving greater demographic and linguistic diversity in the dataset.

**Lesson:** Proactive curation and outreach are necessary to ensure datasets are representative of the populations they serve.

### Case Study: COVID-19 Datasets and FAnFAIR Application

During the COVID-19 pandemic, researchers used FAnFAIR to assess datasets used for epidemiological modeling:

**Findings:** COVID-19 datasets often showed:
- Underrepresentation of elderly and immunocompromised populations in clinical trial data
- Geographic imbalance (data concentrated in wealthy nations)
- Incomplete data on comorbidities affecting vulnerable groups
- Class imbalance (recovered cases vs. severe cases)

**Application of FAnFAIR:** The framework identified these issues early, prompting:
- Targeted data collection efforts in underrepresented regions
- Augmentation of datasets for vulnerable populations
- Stratified analysis accounting for demographic differences

**Outcome:** Fairer datasets led to models with more equitable predictions across populations.

**Lesson:** Systematic fairness assessment using frameworks like FAnFAIR can catch and correct bias before models are deployed to real populations.

### Practical Steps for Bias Mitigation

**1. Pre-Collection:** Define who should be represented and ensure data collection reaches diverse populations.

**2. During Collection:** Use stratified sampling to ensure adequate representation of all groups. Monitor collection processes for measurement bias.

**3. After Collection:** Use FAnFAIR or similar frameworks to assess dataset fairness. Apply balancing techniques as needed.

**4. Model Development:** Test models separately for each demographic group. Use fairness-aware algorithms if standard approaches show disparities.

**5. Deployment:** Monitor performance for disparities. Collect feedback from affected communities. Retrain when disparities emerge.

**6. Governance:** Establish fairness review boards with interdisciplinary expertise (data scientists, domain experts, affected community representatives, ethicists).

---

## Key Takeaways {#conclusions}

### Legal Landscape

1. **"Publicly available" ≠ "public domain"**: Five legal and ethical frameworks govern data use: copyright law, data protection law, web scraping law, contract law, and ethics.

2. **GDPR applies to AI**: Data collection for machine learning is processing under GDPR. Seven principles govern all processing: lawfulness, purpose limitation, minimization, accuracy, storage limitation, confidentiality, and accountability.

3. **Legal basis is essential**: Valid legal basis (consent, legitimate interest, public task, etc.) must exist for processing. This must be documented and defensible.

4. **Special categories require heightened protection**: Biometric and other sensitive data are generally prohibited but can be processed for bias detection and correction.

5. **The EU AI Act sets comprehensive requirements**: High-risk AI systems must meet data governance, risk management, transparency, human oversight, and other requirements. Unacceptable risk systems are banned.

### Ethical and Technical Landscape

6. **Bias has multiple sources**: Preexisting bias (historical), technical bias (design choices), and interaction bias (deployment effects) all require attention.

7. **Fairness is not a technical problem alone**: Fairness involves normative judgments about what kind of fairness matters in context. Multiple fairness metrics exist and often conflict.

8. **Data quality is foundational**: Biased, incomplete, or unrepresentative data cascades through the AI lifecycle, creating unfair systems. FAnFAIR provides a framework for assessing data fairness.

9. **Fairness monitoring is continuous**: Bias doesn't end after deployment. Regular monitoring for disparities and feedback loops is essential.

10. **Trustworthy AI requires interdisciplinary effort**: Technical tools alone are insufficient. Fairness assessment requires collaboration between data scientists, domain experts, affected communities, ethicists, and legal experts.

---

**Generated:** November 2025  
**Purpose:** Consolidated reference for Module 5 on AI and Data Regulation  
**Sources:** Lezioni Tilburg 2025.md, comprehensive research papers on bias and fairness, GDPR, EU AI Act