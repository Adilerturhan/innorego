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

---

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

---

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
